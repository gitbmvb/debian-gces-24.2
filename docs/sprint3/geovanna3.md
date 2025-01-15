# Sprint 3

# Geovanna Maciel Avelino da Costa

## Issue : [Package python-anyio](https://salsa.debian.org/debian-brasil-team/docs/-/issues/382)

## AnyIO
AnyIO é uma biblioteca assíncrona para redes e concorrência que funciona sobre as plataformas asyncio ou trio. Ela implementa a concorrência estruturada (SC) semelhante à do trio sobre o asyncio e trabalha em harmonia com a SC nativa do próprio trio.

A issue foi feita em dezembro antes do recesso. Ela se tratava de uma atualização de upstream. No período do recesso não houve feedback, mas após o recesso eu recebi do Matheus Polkorny um comentário dizendo que atualiazaram a versão dia 4 de janeiro. Ele disse que já tinha outra versão e eu poderia atualizar o pacote caso quisesse.

* MR : [https://salsa.debian.org/python-team/packages/python-anyio/-/merge_requests/2](https://salsa.debian.org/python-team/packages/python-anyio/-/merge_requests/2)
* Repositório no Salsa : [https://salsa.debian.org/python-team/packages/python-anyio](https://salsa.debian.org/python-team/packages/python-anyio)

## Issue : [Package mautrix-python](https://salsa.debian.org/debian-brasil-team/docs/-/issues/374)

## Mautrix 
É uma coleção de bibliotecas e frameworks projetados para simplificar o desenvolvimento de aplicações e pontes para o ecossistema Matrix, com funcionalidades específicas para APIs, criptografia de ponta a ponta, integração de serviços e utilitários.

O pacote necessitava de atualização do upstream e ficar de acordo com as Standards-Version 4.7.0. Fiz a atualização, mas no checklist eu pensei que precisava checar e caso não precisasse informar que não tinham modificações, mas o mesmo revisor de antes avisou sobre e precisa ter um commit com essas informações.

* MR : [https://salsa.debian.org/python-team/packages/mautrix-python/-/merge_requests/2](https://salsa.debian.org/python-team/packages/mautrix-python/-/merge_requests/2)
* Repositório no Salsa : [https://salsa.debian.org/python-team/packages/mautrix-python](https://salsa.debian.org/python-team/packages/mautrix-python)

## Issue : [Package micropython-mpremote](https://salsa.debian.org/debian-brasil-team/docs/-/issues/380)

## Micropython Mpremote

É uma ferramenta de linha de comando (CLI) fornece um conjunto integrado de utilitários para interagir remotamente e automatizar um dispositivo MicroPython por meio de uma conexão serial.

Se tratava de uma atualização também, mas assim como o AnyIO ele ficou parado no recesso e no dia 14 de janeiro recebi a mensagem que já estava atualizado. O MR foi fechado após isso.

* MR : [https://salsa.debian.org/python-team/packages/micropython-mpremote/-/merge_requests/1](https://salsa.debian.org/python-team/packages/micropython-mpremote/-/merge_requests/1)
* Repositório no Salsa : [https://salsa.debian.org/python-team/packages/micropython-mpremote](https://salsa.debian.org/python-team/packages/micropython-mpremote)