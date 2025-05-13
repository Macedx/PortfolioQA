# Criando BUG’s no Monday

A criação correta e padronizada de cards de bugs na plataforma Monday garante rastreabilidade, clareza na comunicação entre a equipe de QA com o time de desenvolvimento e alinhamento com os processos ágeis da Lojas Torra.

---

## 🛠️ Como preencher o formulário de criação de card

| **Campo** | **O que colocar** |
| --- | --- |
| **Nome** | [Módulo] Descrição objetiva do problema
Ex.: [Portal - Login] Após preencher a autenticação com o código o login não é realizado |
| **Sprint** | Selecione a **sprint atual** |
| **Esforço (Horas)** | Valor padrão: 4h |
| **Responsável (Resp.)** | Começa no nome do QA responsável, depois é transferido para o Dev |
| **Tipo** | Bug - Melhorias |
| **Área** | Depende do contexto
Ex.: Financeiro, Cadastro, Comercial, etc. |
| **Épicos**  | Vincule à inciativa correspondente.
Ex.: Migração FIDC (PDA) para o Portal Torra |
| **Orientações Técnicas**  | QA - BUG |
| **Ambientes Produtivos Envolvidos** | QA |

---

## 🌀 Fluxo do Bug no Kanban

O Monday possui as seguintes etapas na esteira de kanban:

0 - Pronto para Começar

1 - Em Andamento

2 - Testes 

3 - Homologação

6 - Feito

99 -Não Concluído na Sprint

### 🧭 Detalhamento do fluxo:

1. **Criação**
- O QA abre o card e o posiciona na esteira “Pronto para Começar”
- O QA é o reponsável incial.

1. **Desenvolvimento**
- O card é atribuído ao Dev e sme da eteira do QA
- O Dev movimenta o card de “Pronto para Começar”  → “Em Andamento”.

1. **Retorno para QA**
- Após a correção, o card volta para o QA, agora na esteira “Testes”.
- O QA valida a correção.

1. **Resultado dos Testes**
- **Se o bug ainda persistir:**  o card **permanece em “Testes”,**  mas o responsável volta a ser o Dev (já que não é possível mover o card para trás).
- **Se o bug estiver resolvido:**  o QA valida a correção nas atualizações e muda o status para “Feito”.

---

## ✅ Boas Práticas

- Crie **títulos objetivos** e fáceis de rastrear.
- Sempre atualize cada passo feito no card.
- Sempre anexe arquivos do bug.
- Mantenha o histórico de movimentação atualizado.
- Ao retestar, comente no card o resulatdo da validação.

 

---