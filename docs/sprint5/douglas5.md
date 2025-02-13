# Douglas Alves

## Sprints Anteriores

### Pacote python-matplotlib-venn

As mudanças requisitadas no [MR](https://salsa.debian.org/python-team/packages/python-matplotlib-venn/-/merge_requests/1) foram feitas e ele segue esperando revisão.

### Pacote faker

As mudanças requisitadas no [MR](https://salsa.debian.org/python-team/packages/faker/-/merge_requests/4) foram feitas e ele segue esperando revisão.

### Pacote python-milc

As mudanças requisitadas no [MR](https://salsa.debian.org/python-team/packages/python-milc/-/merge_requests/1) foram feitas e ele segue esperando revisão.

## Sprint Atual

### Pacote  python-django-split-settings

O django-split-settings ([repo no salsa](https://salsa.debian.org/python-team/packages/python-django-split-settings)) é um pacote que permite dividir as configurações do Django em vários arquivos. Ele é útil para separar as configurações de desenvolvimento, teste e produção, por exemplo.

### Issue: [#428](https://salsa.debian.org/debian-brasil-team/docs/-/issues/428)

Para a escolha do pacote, foi observada sua página no tracker:

* [Link do Tracker](https://tracker.debian.org/pkg/python-django-split-settings)
 
#### Execução

Além do processo de atualização do pacote em si, foi necessário atualizar dois patches:

* d/p/0001-Disable-m2r2-extension-as-it-is-not-packaged-yet.patch: Add forwarded field;
* d/p/0002-Remove-remote-badges-to-prevent-privacy-issues.patch: Add forwarded field.

#### Status da issue

Um [MR](https://salsa.debian.org/python-team/packages/python-django-split-settings/-/merge_requests/1) foi criado. Em 13/02/2025, o MR ainda está em revisão.

### Pacote python-django-solo

O django-solo ([repo no salsa](https://salsa.debian.org/python-team/packages/python-django-solo)) é um pacote que ajuda a criar modelos singleton no Django. Um modelo singleton é um modelo que só pode ter uma instância, útil para configurações globais, por exemplo.

### Issue: [#427](https://salsa.debian.org/debian-brasil-team/docs/-/issues/427)

Para a escolha do pacote, foi observada sua página no tracker:

* [Link do Tracker](https://tracker.debian.org/pkg/python-django-solo)
 
#### Execução

Além do processo de atualização do pacote em si, foi necessário atualizar um dos patches e atualizar o Standards-Version para 4.7.0:

* d/control: Bump Standards-Version to 4.7.0 (no changes needed);
* d/p/solo_rename.patch: Refresh patch.

#### Status da issue

Um [MR](https://salsa.debian.org/python-team/packages/python-django-solo/-/merge_requests/1) foi criado. Em 13/02/2025, o MR ainda está em revisão.

### Pacote  python-license-expression

O license-expression ([repo no salsa](https://salsa.debian.org/python-team/packages/python-license-expression/-/tree/debian/latest)) é um pacote que permite analisar, comparar e simplificar expressões de licença de software usando lógica booleana. Ele é útil para verificar se uma licença é compatível com outra, por exemplo.

### Issue: [#429](https://salsa.debian.org/debian-brasil-team/docs/-/issues/429)

Para a escolha do pacote, foi observada sua página no tracker:

* [Link do Tracker](https://tracker.debian.org/pkg/python-license-expression)
 
#### Execução

Além do processo de atualização do pacote em si, foi necessário atualizar o Standards-Version para 4.7.0:

* d/control: Bump Standards-Version to 4.7.0 (no changes needed).

#### Status da issue

Um [MR](https://salsa.debian.org/python-team/packages/python-license-expression/-/merge_requests/1) foi criado. Em 13/02/2025, o MR ainda está em revisão.

## Histórico de Versão

| Versão |    Data    |         Descrição          |  Autor(es)  |
| :----: | :--------: | :------------------------: | :---------: |
| `1.0`  | 13/02/2025 | Criação do documento | [Douglas Alves](https://github.com/dougAlvs) |
