# João Pedro

### Pacote golang-k8s-apimachinery

Correções adicionais foram necessárias para esse pacote, o patch de correção dos testes em análise posterior não resolvia tão bem o problema e chegamos à conclusão de modificar o teste para pulá-lo.
Além disso, houve a necessidade de alterar o arquivo debian/copyright com atualização das licensas usadas pelo pacote ( e também corrigir um erro do mantenedor sobre o range dessas licensas).
Com isso, o pacote foi aprovado e o MR, merjado.

[Link do MR](https://salsa.debian.org/go-team/packages/golang-k8s-apimachinery/-/merge_requests/1?commit_id=4bb8331c1ccc3b179ba0fa3993acfaeeec693aea)
[Link da issue](https://salsa.debian.org/debian-brasil-team/docs/-/issues/333)

[Pacote migrado para Testing](https://tracker.debian.org/news/1591560/golang-k8s-apimachinery-0313-1-migrated-to-testing/)


### Pacote golang-k8s-sigs-json

Mais uma atualização de Upstream, seguindo a atualização de diversas dependências dos pacotes do K8s para a versão 0.31.x.
Esse pacote não possui depêndencias a serem atualizadas, diferente de diversos pacotes no monolito K8s. O trabalho de atualização nesse pacote foi simples, mas as alterações no arquivo d/copyright necessitarão de revisões adicionais de DDs, que só 
será viável ser feito na reunião semanal do Debian Brasil, após o "show me the code" de hoje.

[Link do MR](https://salsa.debian.org/go-team/packages/golang-k8s-sigs-json/-/merge_requests/1)
[Link da issue](https://salsa.debian.org/debian-brasil-team/docs/-/issues/360)

### Guia de uso do ratt

Durante o processo de contribuição do pacote do apimachinery, foi necessário rodar as suas dependências reversas no debian sid usando o ratt, o que para quem não está no ambiente Debian pode ser desafiador.
Então após conseguir configurar o ratt e fazer sua pinagem para não conflitar com os pacotes da distro utilizada, fiz uma contribuição à documentação da turma anterior e posteriormente pretendo adicioná-la
também à wiki do Debian Brasil, após revisá-la com o grupo.

Disponível [aqui](https://github.com/Mylena-angelica/Debian-GCES-24.1/blob/main/docs/tutoriais/tutorial_ratt.md)
