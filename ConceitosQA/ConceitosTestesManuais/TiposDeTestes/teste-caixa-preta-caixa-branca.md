# Testes Caixa Preta e Caixa Branca

Os testes de software podem ser classificados também pela **abordagem adotada** na construção e execução dos testes: **Caixa Preta** e **Caixa Branca**. Ambas têm papéis importantes e se complementam para garantir a qualidade do sistema.

---

## Teste caixa Preta (Black Box)

### 🎯 Foco:

Avaliar o **comportamento externo** do sistema, sem conhecer a lógica interna ou o código-fonte.
→ A ideia é fornecer entradas e verificar se as saídas estão corretas.

---

### 📌 Características:

- Baseado em **requisitos, histórias de usuário e especificações**
- **Não exige conhecimento de programação**
- Muito usado em **testes funcionais e testes de aceitação**
- Ideal para validar a experiência do usuário com o sistema

### ✅ Exemplos:

- Inserir um CPF válido e verificar se o sistema aceita
- Preencher um formulário e esperar o redirecionamento correto
- Fazer login e validar se o sistema responde com sucesso

---

## Teste Caixa Branca (White Box)

### 🎯 Foco:

Avaliar o **comportamento interno do código**, como estruturas lógicas, fluxos de decisão, condições e laços de repetição.

---

### 📌 Carcaterísticas:

- Requer **acesso ao código-fonte**
- **Exige conhecimento técnico em programação**
- Comum em **testes unitários e de integração**
- Garante **cobertura de código**, testando todos os caminhos possíveis

### ✅ Exemplos:

- Escrever testes que verificam se a função de soma retorna corretamente para:
    - Números positivos
    - Números negativos
    - Casos limite (ex: soma com zero)
- Verificar se todos os “**if/else**” e loops da aplicação são executados em testes

---

## 📊 Comparativo

| **Caracteristica** | **Caixa Preta** | **Caixa Branca** |
| --- | --- | --- |
| Foco | Comportamento externo | Estrutura interna do código |
| Conhecimento técnico | Não precisa saber programar | Requer programação |
| Base | Requisitos e funcionalidades | Lógica, fluxo e condições de código |
| Exemplo de uso | Teste de login | Teste de função de cálculo interno |
| Comum em | Testes funcionais, usabilidade, aceitação | Testes unitários, de cobertura |

---

# 🎯 Conclusão

Ambas abordagens são importantes e complementares:

- O **teste caixa preta** garante que o sistema **funcione como o usuário espera**
- O **testes caixa branca** garante que o sistema **funcione como foi programado**

---