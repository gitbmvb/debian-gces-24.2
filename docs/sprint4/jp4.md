# João Pedro

### Pacote httpie

Esse pacote teve um processo interessante. O bug em questão ja havia sido resolvido ha quase um ano e meio. Basicamente, o bug atestava que arquivos *.egg.info não eram excluídos no processo da build, e após ele abrir esse bug, cerca de dias depois (em agosto de 2023) os mantenedores do dh-python (aka pybuild) atualizaram isso e fizeram com que o dh_auto_clean deletasse arquivos *.egg-info. Devido ao tempo que se passou, achar o commit que resolveu o bug foi relativamente complexo, mas conseguimos achar e eu fechei o bug.

[Link do update do dh-python](https://salsa.debian.org/python-team/tools/dh-python/-/blob/master/debian/changelog?ref_type=heads#L146)

[Link da issue](https://salsa.debian.org/debian-brasil-team/docs/-/issues/383)

[Link do bug](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1045338)
