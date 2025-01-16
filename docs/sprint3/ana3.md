# Sprint 3

## **Issue: Package prometheus-flask-exporter #348**

- [Link para Issue 348](https://salsa.debian.org/debian-brasil-team/docs/-/issues/348)

## Merge Request Aprovado! 🎉

O Merge Request para atualização do pacote prometheus-flask-exporter foi aprovado e mergado com sucesso!

![MR #348](../assets/ana_MR.png)

- [Link para o MR aprovado](https://salsa.debian.org/python-team/packages/prometheus-flask-exporter/-/merge_requests/6)


### Processo de Atualização

1. Foi corrigido o erro do gbp da Sprint 1 alterando o arquivo `~/.gbp.conf`
2. Realizada a atualização do upstream para versão 0.23.1
3. Ajuste no Team upload e enviado o MR para revisão
4. MR aprovado e mergado com sucesso

# Issue da sprint 2

Não fo possível dar andamento a aquela issue pois outra pessoa deu assign.

## Nova Issue em Andamento: Package jupyter-cache (#402)

### Sobre o jupyter-cache


O jupyter-cache é uma ferramenta que permite armazenar em cache e executar notebooks Jupyter, útil para:

- Acelerar a execução de notebooks
- Gerenciar execuções em lote
- Validar notebooks em pipelines CI/CD

![Issue #402](../assets/ana_package_jupyter.png)

- **Status**: Em andamento
- **Links**:
  - [Tracker Debian](https://tracker.debian.org/pkg/jupyter-cache)
  - [Repositório Salsa](https://salsa.debian.org/python-team/packages/jupyter-cache)
  - [Link do MR](https://salsa.debian.org/python-team/packages/jupyter-cache/-/merge_requests/1)

### Problemas enfrentados

Durante o processo de build do pacote houve alguns problemas com o lintian, esses problemas foram resolvidos alterando o changelog mudando de `mantic` para `unstable`

```ini
E: Lintian run failed (runtime error)

+------------------------------------------------------------------------------+
| Summary                                                                      |
+------------------------------------------------------------------------------+

Build Architecture: amd64
Build Type: full
Build-Space: 2376
Build-Time: 58
Distribution: unstable
Host Architecture: amd64
Install-Time: 92
Job: /home/ana/Debian/jupyter-cache/jupyter-cache_1.0.0-2.dsc
Lintian: error
Machine Architecture: amd64
Package: jupyter-cache
Package-Time: 155
Source-Version: 1.0.0-2
Space: 2376
Status: successful
Version: 1.0.0-2
--------------------------------------------------------------------------------

E: jupyter-cache changes: bad-distribution-in-changes-file unstable
E: jupyter-cache changes: unreleased-changes
W: python3-jupyter-cache: changelog-distribution-does-not-match-changes-file unreleased != unstable
```

O erro ocorreu porque o arquivo debian/changelog estava configurado para a distribuição errada. Após alterar de `mantic` para `unstable`, o build passou a funcionar corretamente.


## Enviado para Revisão

![MR #402](../assets/ana_MR1.png)

[Link do MR](https://salsa.debian.org/python-team/packages/jupyter-cache/-/merge_requests/1)



## Histórico de Versões

| Versão | Data | Descrição | Autor(es) |
| :----: | :--------: | :------------------: | :-------------------------------------------: |
| `1.0` | 15/01/2025  | Criação do documento | [Ana Beatriz](https://github.com/ananorberto) |
| `1.1` | 16/01/2025  | Adição de nova issue | [Ana Beatriz](https://github.com/ananorberto) |