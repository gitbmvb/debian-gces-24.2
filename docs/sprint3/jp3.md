# João Pedro

### Pacote golang-k8s-sigs-release-utils

Pacote que estava em revisão da Sprint passada. O MR desse pacote foi aprovado, com as alterações solicitadas implementadas e a nova branch Pristine-Tar criada foi merjada ao pacote.

[Link do MR](https://salsa.debian.org/go-team/packages/golang-k8s-sigs-release-utils/-/merge_requests/1)

### Pacote httpie

Nesse pacote estou tentando fechar um bug sobre a falha de sua build consecutiva, devido a arquivos não deletados após a build, ferindo as políticas do Debian.
O pacote já é mantido pelo Arthur Diniz, então não há necessidade de atualizações nele, embora a reprodução desse bug se faça difícil, me forçando a executar a build do arquivo fora do tradicional.
Além disso, é necessário um conhecimento mais aprofundado dos arquivos do diretório debian, em especial o debian/rules, o que tem tomado meu tempo em estudos.

[Link da issue](https://salsa.debian.org/debian-brasil-team/docs/-/issues/383)
