# Sprint 2

# Geovanna Maciel Avelino da Costa

## Issue : [Package hcloud-python](https://salsa.debian.org/debian-brasil-team/docs/-/issues/366)

### Hetzner Cloud
O package da issue trata do Hetzner Cloud, uma empresa especializada em hospedagem e serviços de infraestrutura, que disponibiliza diversas soluções para sites, aplicativos e serviços online. Entre os serviços mais populares da Hetzner Cloud está o VPS (Servidor Virtual Privado).

Essa issue necessitava da atualização do upstream então usei ela pra testar meu conhecimento do que foi feito na sprint anterior. Ocorreu tudo sem problemas, foi bem transquilo. O MR já está feito e estou no aguardo da revisão

* MR: [https://salsa.debian.org/python-team/packages/hcloud-python/-/merge_requests/2](https://salsa.debian.org/python-team/packages/hcloud-python/-/merge_requests/2)
* Repositório no Salsa: [https://salsa.debian.org/python-team/packages/hcloud-python](https://salsa.debian.org/python-team/packages/hcloud-python)

## Issue : [Package python-agate](https://salsa.debian.org/debian-brasil-team/docs/-/issues/367)

Agate é uma biblioteca de análise de dados em Python otimizada para humanos em vez de máquinas. É uma alternativa ao numpy e pandas, projetada para resolver problemas do mundo real com um código mais legível.

Essa issue precisava de atualização do upstream e um patch. Houveram alguns problemas no meio do caminho, o upstream foi atualizado, mas de forma não convencional, porque tive que testar várias coisas antes de pedir ajuda realmente. Então decidi por recomeçar do zero e mesmo assim dava um erro que não tinha acontecido antes e até mesmo depois das alternativas do monitor ele não funcionou. Decidi por testar com outros dois packages e deu o mesmo erro, então acredito que seja algum problema na minha máquina. Na próxima sprint pretendo finalizá-la.

## Issue : [Package mautrix-python](https://salsa.debian.org/debian-brasil-team/docs/-/issues/374)

Mautrix-python é uma biblioteca em Python desenvolvida para facilitar a criação de bots e bridges (pontes) para o Matrix, uma plataforma de comunicação descentralizada e de código aberto. O Matrix permite mensagens instantâneas, chamadas de voz/vídeo e troca de arquivos entre usuários em diferentes servidores, mantendo interoperabilidade e privacidade.

Essa issue necessitava da atualizaçã do upstream e foi um package de teste pra saber se o problema estava no package ``python-agate`` ou na minha máquina mesmo. Com o teste eu concluí que o problema era técnico mesmo, portanto vou reconfigurar minha máquina pra poder finalizar essas duas issues.

* MR [https://salsa.debian.org/python-team/packages/mautrix-python/-/merge_requests/1](https://salsa.debian.org/python-team/packages/mautrix-python/-/merge_requests/1)
* Repositório no Salsa: [https://salsa.debian.org/python-team/packages/mautrix-python](https://salsa.debian.org/python-team/packages/mautrix-python)
