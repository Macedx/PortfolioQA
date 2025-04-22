# Tipos de Teste de Software

Os testes de software são fundamentais para garantir que um sistema funcione corretamente, atenda aos requisitos definidos e ofereça boa experiência para os usuários. Eles podem ser classificados de acordo com **o foco, o objetivo e a abordagem utilizada**. 

---

### **📌 1. Testes Funcionais**

Verificam se o sistema está funcionando de acordo com os requisitos especificados.

- **Teste Unitário**: Testa pequenas partes do código (funções ou métodos) isoladamente.
- **Teste de Integração**: Avalia se os módulos ou componentes funcionam corretamente em conjunto.
- **Teste de Sistema**: Testa o sistema completo, garantindo que todos os requisitos funcionais e não funcionais sejam atendidos.
- **Teste de Aceitação**: Verifica se o sistema atende às expectativas do cliente ou usuário.
    - **UAT (User Acceptance Test)**: Validado pelos usuários finais.
    - **Aceitação Operacional**: Simula o funcionamento do sistema em ambiente real.

---

### **📌 2. Testes Não Funcionais**

Avaliam aspectos além das funcionalidades do sistema, como desempenho, segurança e compatibilidade.

- **Teste de Desempenho**: Verifica tempo de resposta e estabilidade sob carga.
    - **Carga**: Com usuários e dados esperados.
    - **Estresse**: Com sobrecarga, além do normal.
    - **Escalabilidade**: Verifica a capacidade do sistema de crescer.
- **Teste de Segurança**: Procura vulnerabilidades e riscos.
- **Teste de Usabilidade**: Avalia a experiência e facilidade de uso.
- **Teste de Compatibilidade**: Garante o funcionamento em diferentes navegadores, sistemas operacionais e dispositivos.

---

### **📌 3. Testes de Regressão**

São feitos para garantir que alterações ou correções no sistema não afetem funcionalidades já existentes.

---

### **📌 4. Testes de Qualidade**

Avaliam características como manutenção e adaptação do software.

- **Teste de Manutenibilidade**: Mede a facilidade de modificar, corrigir ou melhorar o sistema.
- **Teste de Portabilidade**: Verifica se o sistema funciona corretamente em diferentes ambientes ou plataformas.

---

### **📌 5. Testes Baseados em Caixa Preta**

Testam o comportamento do sistema **sem olhar o código-fonte**, focando apenas na entrada e saída dos dados.

- **Partição de Equivalência**: Divide as entradas em grupos para otimizar os testes.
- **Análise de Valor Limite**: Testa os valores nas bordas das faixas válidas.
- **Transição de Estado**: Avalia se o sistema responde corretamente às mudanças de estado.

---

### **📌 6. Testes Baseados em Caixa Branca**

São realizados com **acesso ao código**, verificando seu comportamento interno.

- **Teste de Caminho**: Garante que todos os caminhos possíveis no código sejam testados.
- **Teste de Condição**: Testa todas as condições lógicas possíveis.
- **Teste de Ciclo de Vida do Código**: Valida todas as partes do código para garantir sua estabilidade.

---

### **📌 7. Testes Exploratórios**

Feitos de forma **livre e criativa**, baseados na experiência e intuição do testador, sem roteiro fixo. Ótimos para encontrar falhas inesperadas.

---

### **📌 8. Testes de Acessibilidade**

Avaliam se o software é acessível para pessoas com deficiência (visual, auditiva ou motora), garantindo conformidade com diretrizes de acessibilidade.

---

# 🎯 **Conclusão**

Cada tipo de teste cumpre um papel específico para assegurar que o software seja **seguro, funcional, estável, acessível e compatível**, atendendo às expectativas dos usuários e às necessidades do negócio. Em projetos ágeis, muitos desses testes são integrados ao processo de forma contínua e automatizada, com o apoio do QA em todas as etapas.

---