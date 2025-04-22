# Critérios de Aceitação e Definição de “Pronto”

---

# ✅ DoR e DeR

As siglas DOR e DER são comumente usadas em contextos de desenvolvimento ágil e gestão
de projetos para representar conceitos importantes relacionados ao fluxo de trabalho e à
organização de atividades.

---

## 🗒️DoR - *Definition of Ready* (Definição de Pronto)

É o **conjunto de critérios** que uma tarefa ou história de usuário precisa cumprir **antes de ser iniciada**.

**Objetivo:**  Garantir que o time só comece atividades **claras, viáveis e priorizadas**, evitando retrabalho.

**Exemplos de critérios de DOR:**

- Requisitos estão claros e completos.
- Dividido em tarefas menores, se necessário.
- Sem dependências externas pendentes.
- A equipe tem o conhecimento necessário.
- A tarefa está priorizada no backlog.

> 📌 ***Pensa assim:***
> 
> 
>  Só entra em desenvolvimento aquilo que está “redondinho”.
> 

---

## 🗒️ DeR - *Definition of Done* (Definição de Pronto / Concluído)

É o **conjunto de critérios que indica que uma tarefa foi concluída com qualidade** e está pronta para entrega.

**Objetivo:** Garantir que o trabalho entregue está completo, testado e validado, sem pontas soltas.

**Exemplos de critérios de DER:**

- Código foi desenvolvido e passou em revisão.
- Testes (unitários e funcionais) executados com sucesso.
- Sem bugs críticos nem regressões.
- Documentação foi atualizada.
- Funcionalidade validada com o Product Owner.

> 📌 ***Pensa assim:***
> 
> 
> Só marca como "feito" o que realmente está pronto para produção ou entrega.
> 

---

## DoR 🆚 DeR

| **Conceito** | **Significado** | Quando se aplica | Para que serve |
| --- | --- | --- | --- |
| **DOR** (Definition of Ready) | Definição de Pronto | **Antes** da equipe iniciar uma tarefa | Garante que a tarefa está **bem definida, entendida e viável** para começar |
| **DER** (Definition of Done) | Definição de Concluído | **Depois** que o trabalho foi feito | Garante que o item está **totalmente finalizado, testado e validado** para entrega |

---

## 📑 DoR - Exemplos de Critérios

- A história de usuário tem todos os requisitos funcionais e não funcionais.
- Não há dependências externas pendentes.
- A complexidade está estimada.
- O time entende o que precisa ser feito.
- Os critérios de aceite estão definidos.

## 📑 DeR - Exemplos de Critérios

- Código implementado e revisado.
- Todos os testes (unitários, funcionais, automatizados) passaram.
- Sem bugs críticos.
- Documentação atualizada.
- Aprovado pelo PO.
- Pronto para deploy sem causar regressões.

> 📌 ***Resumo prático:***
> 
> 
> DoR: “Podemos começar?”
> 
> DeR: “Podemos entregar?”
> 

---

# ✅ Critérios de Aceite (Acceptance Criteria)

São **condições específicas e mensuráveis** que uma funcionalidade ou produto precisa cumprir para ser considerado **concluído e aceito** pelo cliente, PO (Product Owner) ou equipe responsável.

---

## 🖇️ Objetivos dos Critérios de Aceite

- Garantir que **requisitos foram atendidos corretamente**.
- Ajudar a evitar **interpretações ambíguas** do que precisa ser entregue.
- Servir como base para **testes de aceitação**.
- Definir o que é “feito” de forma objetiva (relacionado à DER).

---

## 📑 Exemplos de Critérios de Aceite por Categoria

| **Tipo** | **Exemplo** |
| --- | --- |
| **Funcionalidade** | O botão “Salvar” deve gravar os dados no banco de dados corretamente. |
| **Desempenho** | A funcionalidade deve responder em até 2 segundos com até 1000 usuários simultâneos. |
| **Segurança**  | A senha deve ser criptografada e visível apenas em formato de asteriscos. |
| **Usabilidade** | O formulário deve mostrar uma mensagem de confirmação após o envio. |
| **Compatibilidade** | O sistema deve funcionar em navegadores Chrome, Firefox e Edge (últimas versões). |

---

## 📌 Quem Usa os Critérios de Aceite?

- **Desenvolvedores**, para saber o que implementar.
- **Testers/QA**, para validar se a entrega está conforme.
- **Product Owner/Cliente**, para aprovar ou rejeitar a entrega.

---

# ✅ História de Usuário

Uma **história de usuário** é uma forma simples e eficaz de expressar **requisitos funcionais** do sistema **do ponto de vista do usuário final**, muito usada em metodologias ágeis como Scrum e Kanban.

---

## 📌 Estrutura Padrão

**Como** [tipo de usuário],

**Eu quero** [ação ou funcionalidade],

**Para que** [valor ou benefício].

---

## 📌 Ligação com Critérios de Aceite

Cada história vem acompanhada de **critérios de aceite**: condições que devem ser **cumpridas para que a história seja considerada concluída** (e muitas vezes, esses critérios se alinham com a DER — Definition of Done).

---

## 📑 Exemplos Reutilizáveis

### 🖇️ História 1 - App de Banco

**Como** usuário de um app de banco,

**Eu quero** visualizar o saldo na tela inicial,

**Para que** eu possa verificar rapidamente quanto tenho disponível.

**Critérios de aceite**:

- Exibir saldo na tela inicial após login.
- Atualização em tempo real.
- Design claro e destacado.
- Segurança via criptografia.

### 🖇️ História 2 - E-commerce

**Como** cliente de um e-commerce,

**Eu quero** filtrar os produtos por preço,

**Para que** eu possa encontrar opções dentro do meu orçamento.

**Critérios de aceite**:

- Filtro de preço na listagem.
- Intervalo mínimo e máximo configurável.
- Atualização automática da lista.
- Compatível com mobile.
    
    

### 🖇️ História 3 - Sistema de Conteúdo

**Como** administrador do sistema,

**Eu quero** adicionar, editar e excluir artigos,

**Para que** eu possa manter o conteúdo sempre atualizado.

**Critérios de aceite**:

- Interface para adicionar artigos.
- Funções de edição e exclusão.
- Validação de campos obrigatórios.
- Mensagem de confirmação após ação.

---