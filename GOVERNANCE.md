# Framework de Governança: Aetheris Core

Este documento estabelece as regras de consenso para o ecossistema **Aetheris**.

### 🗳 Parâmetros de Votação

- **Token:** Aetheris ($AETHR)
- **Quórum de Ativação:** 15% do supply circulante.
- **Limite de Aprovação:** Maioria qualificada de 60% para mudanças no core.
- **Janela de Votação:** 5 dias úteis.
- **Timelock (Atraso de Execução):** 48 horas após a aprovação (medida de segurança).

### 📝 Categorias de Propostas (AEP)

| Prefixo   | Categoria                       | Requisito Mínimo ($AETHR) |
| :-------- | :------------------------------ | :------------------------ |
| **AEP-S** | Estratégia e Marketing          | 2,000 $AETHR              |
| **AEP-T** | Alocação de Tesouraria          | 10,000 $AETHR             |
| **AEP-C** | Atualizações de Contrato (Core) | 50,000 $AETHR             |

### 🛡 Conselho de Curadores (The Aether Council)

Um grupo de 7 membros eleitos bianualmente possui a chave do Multisig de emergência. Este conselho não pode criar propostas, apenas vetar ações que apresentem risco iminente de drenagem de fundos (exploit).

### 🔄 Fluxo de Trabalho

1. **Ideação:** Mínimo de 15 reações positivas no Discord.
2. **Drafting:** Criação da AEP com especificações técnicas.
3. **Votação:** Período de 120 horas para depósito de votos on-chain.
4. **Execução:** Após o Timelock, a alteração é implementada automaticamente.
