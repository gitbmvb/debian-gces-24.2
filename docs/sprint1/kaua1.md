# Kauã Vinícius

## Pacote golang-github-kalafut-imohash

O pacote ImoHash trata-se de uma biblioteca golang para calcular hashs em tempo constante. Com ele, é possível utilizar a linha de comando para fazer hash de arquivos utilizando o tamanho do mesmo como parâmetro. Seu repositório no salsa esta disponível [neste link](https://salsa.debian.org/go-team/packages/golang-github-kalafut-imohash). 

## Issue 

Objetivo: Gerar nova versão upstream para o pacote, atualizando-o para a versão indicada no [Tracker](https://tracker.debian.org/pkg/golang-github-kalafut-imohash).

### Execução

Para concluir a issue, foi necessário apenas seguir os passos disponíveis no [repositório do semetre anterior da disciplina](https://mylena-angelica.github.io/Debian-GCES-24.1/tutoriais/atualizacao_upstream/) com exceção a dois passos: </br>

1 - Foi necessário executar o comando abaixo para criar um arquivo compactado (tar.gz) contendo todos os arquivos do repositório Git no estado atual (HEAD). O conteúdo do tarball estará organizado dentro de uma pasta chamada golang-github-kalafut-imohash-1.0.4/. Este passo foi executado antes do primeiro sbuild.

```
git archive --prefix=golang-github-kalafut-imohash-1.0.4/ --output=../golang-github-kalafut-imohash_1.0.4.orig.tar.gz HEAD
```

2 - Foi necessário alterar o nome do último commit gerado pelo gbp. A princípio, foi gerado um commit indicando que a atualização era referênte à versão 1.0.42, todavia, o correto é 1.1.0, com isso, foi executado o seguinte comando:  </br>

```
git commit --amend -m "Update changelog for 1.1.0-1 release"
```

### Issue concluída 
No dia 27/11/2024 foi aprovado o [MR](https://salsa.debian.org/go-team/packages/golang-github-kalafut-imohash/-/merge_requests/2) referente a atualização do pacote.


| Versão |    Data    |         Descrição          |  Autor(es)  |
| :----: | :--------: | :------------------------: | :---------: |
| `1.0`  | 28/11/2024 | Criação de documento | Kauã |
