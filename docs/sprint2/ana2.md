# Sprint 2

## **Issue: Package prometheus-flask-exporter #348**

- [Link para Issue 348](https://salsa.debian.org/debian-brasil-team/docs/-/issues/348)


## **Prometheus-Flask-Exporter**

![alt text](../img/image.png)

---


Esse pacote, `prometheus-flask-exporter`, integra o Flask com o Prometheus, permitindo exportar métricas de desempenho da aplicação web para monitoramento.
Ele fornece contadores, histogramas e métricas de latência de requisições HTTP.

--- 

# Erro (Sprint 1)

- Na [Sprint 1](../sprint1/ana1.md) não foi possivel fazer a new upstream version por causa do erro com a chave **gbp**.

```
gbp import-orig --uscan --pristine-tar
```

![Erro](../img/ana-error.png)

### Erro corrigido

Este erro foi corrigido alterando o `~/.gbp.conf`

```ini
$ cat ~/.gbp.conf 

[DEFAULT]
builder = sbuild
pristine-tar = True
sign-tags = True //alterar para False
keyid = <gpg-fingerprint> //Remover linha

$ cat ~/.gbp.conf 
[DEFAULT]
builder = sbuild
pristine-tar = True
sign-tags = False
```
## Merge Request Feito - New upstream version 0.23.1

- [Link para o MR](https://salsa.debian.org/python-team/packages/prometheus-flask-exporter/-/merge_requests/5). (Esperando aprovação...)

#

## **Issue: Package ruby-unleash #281**


- [Link para Issue 348](https://salsa.debian.org/debian-brasil-team/docs/-/issues/281)

Essa é uma issue do semestre passado que foi aberta novamente.

## **Ruby-unleash**

![alt text](../img/ruby-unleash.png)


Esse pacote é um cliente Ruby para o **Unleash**, uma ferramenta de **feature toggling** (controle de funcionalidades) que permite controlar a ativação e desativação de funcionalidades em tempo real, sem precisar alterar o código ou realizar novos deploys.

## Erro (Sprint 2)

Após fazer os passos para atualização de pacote, quando o comando `gbp buildpackage` é executado novamente para construir novamente o pacote o Build falha e ocorre problemas com as dependencias, quando a nova versão é importada, o pacote continua com dependências antigas.

![alt text](../img/erro-ana2.png.png)




| Versão |    Data    |      Descrição       |                   Autor(es)                   |
| :----: | :--------: | :------------------: | :-------------------------------------------: |
| `1.0`  | 28/11/2024 | Criação de documento | [Ana Beatriz](https://github.com/ananorberto) |
| `1.1`  | 12/12/2024 | Atualização          | [Ana Beatriz](https://github.com/ananorberto) |

