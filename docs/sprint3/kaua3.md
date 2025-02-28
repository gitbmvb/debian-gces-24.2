# Kauã Vinícius

## Pacote Subliminal

O pacote permite com que o usuário crie legendas em linguagens definidas por eles de qualquer mp4. Seu repositório no salsa esta disponível [neste link](https://salsa.debian.org/python-team/packages/subliminal). 

## Issue 

Objetivo: Eliminar warnings presentes no pacote referentes a falta de Manual page e watcher desatualizado. Os warnings estão presentes [neste link](https://tracker.debian.org/pkg/subliminal).

### Execução

Para concluir a issue, foi necessário seguir os passos até o build disponíveis no [repositório do semetre anterior da disciplina](https://mylena-angelica.github.io/Debian-GCES-24.1/tutoriais/atualizacao_upstream/).</br>
Posteriormente, foi comprovado 2 warnings e pode-se seguir com a correção. Primeiramente, foi necessário atualizar a versão do watcher, que se encontrava na versão 3, e apenas passei para a 4 mudando a numeração no arquivo "debian/watch"
Assim, Foi criado o arquivo "debian/subliminal.1" no qual foi escrito o manual page, na sequência, criado o arquivo "debian/install" contendo o seguinte comando:
```
debian/subliminal.1 /usr/share/man/man1/
```
O mesmo é responsável por atualizar e inserir a man-page no pacote. Na sequência, também foi instalado a man-page no pacote atual com:
```
sudo cp subliminal.1 /usr/share/man/man1/ && mandb
```
Na sequência, verificado a efetividade da operação com:
```
man subliminal
```
E por fim, buildado novamente o pacote.

### Status

A issue ainda está sendo finalizada.

### Status da issue
Foi aberto apenas um [MR](https://salsa.debian.org/python-team/packages/subliminal/-/merge_requests/3). O mesmo foi mergado dia 19/12/2024.

## Issue 2

Atualizar sua versão upstream


## Pacote autocomplete

AutoComplete é uma biblioteca de conclusão de código para Swing JTextComponents, com funcionalidade aprimorada disponível quando usada com seu projeto irmão RSyntaxTextArea.. Seu repositório no salsa esta disponível [neste link](https://salsa.debian.org/java-team/autocomplete). 

### Issue

O objetivo é realizar uma atualização upstream do pacote com a necessidade de aplicar patches.

### Execução

Ao realizar a tentativa de atualização upstream do código, o seguinte erro está sendo exibido:


## Atualização pacote Golang A8M tree

No Merge Request, o revisor Carlos Henrique pontuou que deve-se verificar as dependências de determinadas bibliotecas utilizando o comando:

```
apt rdepends <name-of-the-package>
```

Oque não acusou nada negativo para o pacote em questão. Na sequência, foi comentado que há uma nova versão de política de empacotamento para tal pacote, sendo o objetivo agora realizar um bump de versão para este novo padrão. Os demais pacotes não foram revisados ainda.


## Versão

| Versão |    Data    |         Descrição          |  Autor(es)  |
| :----: | :--------: | :------------------------: | :---------: |
| `1.0`  | 19/12/2024 | Criação de documento | Kauã |
| `1.1`  | 03/01/2024 | Atualização de informações |Kauã|
| `1.2`  | 13/01/2024 | Atualização de informações | Kauã|
