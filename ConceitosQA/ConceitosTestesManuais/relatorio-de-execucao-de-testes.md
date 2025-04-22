# Relatório de Execução de Testes

Um **relatório de execução de testes** é um documento que registra, de forma clara e objetiva, os **resultados dos testes realizados em um projeto ou sprint**. Ele serve para apresentar o que foi testado, o que passou, o que falhou e se o sistema está estável para ser entregue.

Esse relatório é essencial para:

- Demonstrar o **andamento e a qualidade das entregas**
- **Formalizar os resultados obtidos**
- **Facilitar a comunicação entre QA, desenvolvimento e stakeholders**
- Ajudar na **decisão sobre a liberação do produto**

---

## 📌 Estrutura de um Relatório de Execução de Testes

### ✅ Informações Gerais

- **Projeto:** Nome do projeto
- **Sprint / Iteração:** Período de execução dos testes
- **Data do Teste:** Data da execução
- **Executado por:** Nome do responsável ou time
- **Plano de Teste:** Nome do plano utilizado
- **Suíte de Teste:** Funcionalidade ou área validada
- 

---

### ✅ Resumo da Execução

| **Métrica** | **Valor** |
| --- | --- |
| Casos de Teste | 35 |
| Testes Executados | 35 |
| Testes Aprovados | 32 |
| Testes Falhos | 3 |
| Testes Não Executados | 0 |
| **Para Rate (%)** | 91,4% |

---

> 📌 **Como clacular o Pass Rate (Taxa de Aprovação)?**
> 
> 
> Pass Rate(%) = Testes Aprovados/ Testes Executados * 100
> 

---

### ✅ Falhas Encontradas

| **ID do Teste** | **Caso de Teste** | **Resultado** | **Observações** | Bug |
| --- | --- | --- | --- | --- |
| TC-102 | Login com senha inválida | ❌ | Retorna 200 ao invés de 401 | BUG-234 |
| TC-109 | Recuperação de senha com e-mail | ❌ | Mensagem de erro não é exibida | BUG-238 |
| TC-115 | Redirecionamento após logout | ❌ | Redireciona para Dashboard | BUG-240 |

---

### ✅ Evidências e Anexos

- Exportação dos resultados (PDF ou Excel)
- Capturas de tela das falhas
- Links para os bugs no Azure Boards0

---

### ✅Conclusão

A execução alcançou **91,4% de aprovação**. Três falhas foram registradas, sem nenhum erro crítico. O sistema está apto para entrega após a correção desses pontos.

---

### ✅ Próximas Ações

- Corrigir os bugs registrados (BUG-234, BUG-238, BUG-240)
- Reexecutar os testes que falharam
- Retestar todo o plano após as correções
- Atualizar o relatório com os resultados finais
- 

---

### ✅ Ferramentas Utilizadas

- Azure Test Plans
- Azure Boards
- Ambiente: Staging v1.3.0 ou hml v1.3.0
- 

---

### ✅ Como Exportar os Dados no Azure Test Plans

- Acesse o **Test Plans**
- Selecione o plano/suite executado
- Clique em **Runs** ou **Test Results**
- Use a opção **Export** (CSV ou Excel)
- Preencha o relatório com os dados exportados

---