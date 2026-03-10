# 🔒 Matriz de Requisitos de Segurança e Modelagem (STRIDE)

> **Instruções de Uso:** > Este artefato faz a ponte entre a área de Produto e a de Segurança (*Shift-Left*). Todo Requisito Funcional (RF) gera um risco que deve ser classificado no STRIDE e mitigado por um Requisito Não Funcional (RNF). Anexe esta matriz à documentação de arquitetura da Sprint.

**Produto/Épico:** [Ex: Módulo de Faturamento - Freelasy]  
**Fase do SDLC:** Design / Levantamento de Requisitos  
**Arquiteto(s) de Segurança:** [Insira os nomes]  

---

## 1. Avaliação de Requisitos Funcionais

| ID | Requisito Funcional (RF) | Categoria STRIDE | Cenário de Ataque | Requisito Não Funcional (RNF) - Mitigação |
| :---: | :--- | :---: | :--- | :--- |
| **RF-01** | *Ex: Gerar link público para PDF da fatura.* | **I** *(Info Disclosure)* | *Ex: Atacante altera ID sequencial na URL (IDOR) e acessa dados financeiros de terceiros.* | **RNF-SEG-01:** Usar UUIDv4 na URL.<br>**RNF-SEG-02:** Expirar link em 7 dias. |
| **RF-02** | | | | |
| **RF-03** | | | | |
| **RF-04** | | | | |

---

## 💡 Guia Rápido: Framework STRIDE

Caso tenha dúvidas na classificação, utilize o guia abaixo:

* **S - Spoofing (Falsificação):** Falsificar a identidade de algo ou alguém. *(Mitigação: Autenticação)*
* **T - Tampering (Adulteração):** Modificar dados em trânsito ou repouso. *(Mitigação: Integridade/Hashes)*
* **R - Repudiation (Repúdio):** Realizar uma ação e negar autoria. *(Mitigação: Logs/Auditoria)*
* **I - Information Disclosure (Vazamento):** Expor dados a pessoas não autorizadas. *(Mitigação: Criptografia)*
* **D - Denial of Service (Negação de Serviço):** Degradar ou derrubar o sistema. *(Mitigação: Disponibilidade/Rate Limit)*
* **E - Elevation of Privilege (Elevação de Privilégio):** Obter permissões não autorizadas. *(Mitigação: Autorização/RBAC)*

---
*Documento gerado para a disciplina de Engenharia de Software e Segurança da Informação.*