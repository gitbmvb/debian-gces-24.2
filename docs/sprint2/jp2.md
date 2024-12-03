# João Pedro

### Pacote golang-k8s-apimachinery

Correções adicionais foram necessárias para esse pacote, o patch de correção dos testes em análise posterior não resolvia tão bem o problema e chegamos à conclusão de modificar o teste para pulá-lo.
Além disso, houve a necessidade de alterar o arquivo debian/copyright com atualização das licensas usadas pelo pacote ( e também corrigir um erro do mantenedor sobre o range dessas licensas).

[link da issue](https://salsa.debian.org/debian-brasil-team/docs/-/issues/333)

### Guia de uso do ratt

Durante o processo de contribuição do pacote do apimachinery, foi necessário rodar as suas dependências reversas no debian sid usando o ratt, o que para quem não está no ambiente Debian pode ser desafiador.
Então após conseguir configurar o ratt e fazer sua pinagem para não conflitar com os pacotes da distro utilizada, fiz uma contribuição à documentação da turma anterior e posteriormente pretendo adicioná-la
também à wiki do Debian Brasil, após revisá-la com o grupo.

Disponível [aqui](https://github.com/Mylena-angelica/Debian-GCES-24.1/blob/main/docs/tutoriais/tutorial_ratt.md)
