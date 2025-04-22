# Matriz de Prioridade de Defeitos

Priorizar defeitos é uma das partes mais importantes da gestão de bugs, porque nem todo problema precisa ser resolvido agora — alguns são urgentes, outros podem esperar

---

## 📌 Como Priorizar Defeitos

### **🗒️ 1. Severidade (Impacto Técnico)** — O quqanto o bug afeta o funcionamento do sistema:

🔴 **Crítica**: Interrompe o uso (crash, perda de dados)

🟠 **Alta**: Impacta função importante, mas o sistema funciona

🟡 **Média**: Comportamento errado, sem quebrar nada essencial

🟢 **Baixa**: Só estética ou usabilidade leve

---

### **🗒️ 2. Prioridade (Urgência de Negócio)** — A urgência para resolver:

🔥 **Alta**: Precisa resolver rápido (afeta cliente ou entrega)

⏳ **Média**: Importante, mas pode esperar um pouco

💤 **Baixa**: Pode deixar para o futuro

---

### **🗒️** 3. Como Decidir:

- **Alta + Alta** → Corrigir imediatamente
- **Alta + Baixa** → Corrigir em breve
- **Baixa + Alta** → Corrigir com prioridade
- **Baixa + Baixa** → Corrigir quando der

---

> ✅ **Dica Prática**
> 
> 
> Se estiver usando ferramentas como Jira ou Trello:
> 
> - Use **labels**: `bug-crítico`, `urgente`, `pode-esperar`
> - Ou **cores**:
>     
>     🔴 Vermelho = alta prioridade
>     
>     🟡 Amarelo = média
>     
>     🟢 Verde = baixa
>     

---