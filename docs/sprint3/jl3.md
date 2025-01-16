# João Lucas Pinto Vasconcelos

## *Issues Anteriores*

### **Issue Concluída**: Atualização da versão do *upstream* do pacote **myst-nb**

- **Descrição**:
  Atualização do *upstream* do pacote **myst-nb**. O pacote é mantido pela equipe Python do Debian.
- **Links Relevantes**:
  - **Tracker do Debian**: [myst-nb Tracker](https://tracker.debian.org/pkg/myst-nb)
  - **Repositório Salsa**: [myst-nb no Salsa](https://salsa.debian.org/python-team/packages/myst-nb)
  - **Lintian**: [Lintian para myst-nb](https://udd.debian.org/lintian/?packages=myst-nb)
- **Status**:
  - **Situação Atual**: Finalizada, revisada e complementada conforme solicitado, incluindo atualização do *standards version*.

---

### **Issue Concluída**: Atualização da versão do *upstream* do pacote **djoser**

- **Descrição**:
  Atualização do *upstream* para o pacote **djoser**, garantindo que o código esteja sincronizado com as mudanças mais recentes.
- **Links Relevantes**:
  - **Tracker do Debian**: [djoser Tracker](https://tracker.debian.org/pkg/djoser)
  - **Repositório Salsa**: [djoser no Salsa](https://salsa.debian.org/python-team/packages/djoser)
  - **MR Links**:
    - **debian/master**: [Merge Request](https://salsa.debian.org/python-team/packages/djoser/-/merge_requests/8)
    - **pristine**: [Merge Request](https://salsa.debian.org/python-team/packages/djoser/-/merge_requests/9)
    - **upstream**: [Merge Request](https://salsa.debian.org/python-team/packages/djoser/-/merge_requests/10)
- **Status**:
  Apesar de ter sido finalizado e enviado para revisão, um outro desenvolvedor submeteu um *merge request* posterior que foi revisado e aprovado antes do meu. Assim, meu MR ficou obsoleto.

---

### **Em Desenvolvimento**: Atualização da versão do *upstream* do pacote **google-auth-java**

- **Descrição**:
  Implementação e atualização do *upstream* para o pacote **google-auth-java**. O pacote fornece uma biblioteca cliente de autenticação *open source* para Java.
- **Links Relevantes**:
  - **Tracker do Debian**: [google-auth-java Tracker](https://tracker.debian.org/pkg/google-auth-java)
  - **Repositório Salsa**: [google-auth-java no Salsa](https://salsa.debian.org/java-team/google-auth-java)
  - **Lintian**: [Lintian para google-auth-java](https://udd.debian.org/lintian/?packages=google-auth-java)
- **Status**:
  - Trabalho em andamento. A atualização apresenta desafios devido ao grande salto de versão (de 0.18.0-2 para 1.30.1-0), exigindo ajustes detalhados nos *patches* existentes.

---

## *Novas Issues*

### **Issue**: Atualização da versão do *upstream* do pacote **python-gflanguages**

- **Descrição**:
  Atualização da versão do *upstream* para o pacote **python-gflanguages**. O pacote possui uma nova versão upstream (0.7.1) e requer atualização do *standards version*.
- **Links Relevantes**:
  - **Tracker do Debian**: [python-gflanguages Tracker](https://tracker.debian.org/pkg/python-gflanguages)
  - **Repositório Salsa**: [python-gflanguages no Salsa](https://salsa.debian.org/python-team/packages/python-gflanguages)
- **Status**:
  A ser iniciado.

---

### **Issue**: Atualização do pacote **lua-lpeg**

- **Descrição**:
  Resolvição de avisos e erros reportados pelo *Lintian* e pelo log de construção do pacote.
- **Links Relevantes**:
  - **Tracker do Debian**: [lua-lpeg Tracker](https://tracker.debian.org/pkg/lua-lpeg)
  - **Repositório Salsa**: [lua-lpeg no Salsa](https://salsa.debian.org/lua-team/lua-lpeg)
- **Status**:
  A ser iniciado.

---

### **Issue**: Atualização da versão do *upstream* do pacote **bruteforce-luks**

- **Descrição**:
  Atualização para a nova versão do *upstream* (1.4.1). A versão atual também requer ajustes no *standards version* e resolução de um aviso do *Lintian*.
- **Links Relevantes**:
  - **Tracker do Debian**: [bruteforce-luks Tracker](https://tracker.debian.org/pkg/bruteforce-luks)
  - **Repositório Salsa**: [bruteforce-luks no Salsa](https://salsa.debian.org/pkg-security-team/bruteforce-luks)
- **Status**:
  Em progresso.

---

## **Resumo do Progresso**

1. **myst-nb**: Concluído, revisado e complementado.
2. **djoser**: Finalizado, mas MR foi tornado obsoleto por um MR posterior que foi revisado e aprovado antes.
3. **google-auth-java**: Em andamento, com trabalho detalhado em *patches* devido ao grande salto de versão.
4. **Novas Issues**: Três novas tarefas iniciadas:
    - **python-gflanguages**: Atualização do upstream e standards version.
    - **lua-lpeg**: Resolvição de avisos no Lintian e log de construção.
    - **bruteforce-luks**: Atualização para a nova versão upstream e ajustes no standards version.

