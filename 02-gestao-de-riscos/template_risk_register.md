# 🛡️ Documento de Avaliação e Tratamento de Riscos (Risk Register)

> **Instruções de Uso:** > Preencha este documento atuando como o Comitê de Segurança da Informação. Avalie os cenários utilizando a Régua Corporativa de Impacto e Probabilidade. No mundo corporativo, este artefato é vivo e deve ser revisado periodicamente.

**Projeto/Cenário:** [Ex: Migração Cloud - HealthTech Solutions]  
**Data da Avaliação:** [DD/MM/AAAA]  
**Responsável (Equipe):** [Insira os nomes dos membros do grupo]  

---

## 1. Mapeamento e Avaliação

| ID | Ativo Crítico | Vulnerabilidade Identificada | Ameaça (Agente Causal) | Prob. (1 a 3) | Imp. (1 a 3) | Risco (P x I) | Classificação |
| :---: | :--- | :--- | :--- | :---: | :---: | :---: | :--- |
| **R-01** | *Ex: BD de Prontuários* | *Ex: Storage público na nuvem* | *Ex: Vazamento via bots* | *3* | *3* | **9** | 🔴 Crítico |
| **R-02** | | | | | | | |
| **R-03** | | | | | | | |
| **R-04** | | | | | | | |

## 2. Plano de Tratamento de Riscos

| ID | Estratégia Adotada | Controle Proposto (Técnico ou Administrativo) | Prazo / Status |
| :---: | :--- | :--- | :--- |
| **R-01** | [x] Mitigar<br>[ ] Aceitar<br>[ ] Transferir<br>[ ] Evitar | **Técnico:** Bloquear acesso público nativo no bucket S3. <br>**Admin:** Revisão por pares obrigatória antes do *deploy*. | *Imediato (Bloqueante)* |
| **R-02** | [ ] Mitigar<br>[ ] Aceitar<br>[ ] Transferir<br>[ ] Evitar | | |
| **R-03** | [ ] Mitigar<br>[ ] Aceitar<br>[ ] Transferir<br>[ ] Evitar | | |
| **R-04** | [ ] Mitigar<br>[ ] Aceitar<br>[ ] Transferir<br>[ ] Evitar | | |

---
*Documento gerado para a disciplina de Engenharia de Software e Segurança da Informação.*