# Registro de BUG’s e Defeitos

O registro de bugs é uma prática fundamental no processo de desenvolvimento de software, pois garante a **organização, rastreabilidade e melhoria contínua do produto**. Sem essa documentação, erros podem passar despercebidos ou ser difíceis de reproduzir e corrigir.

A seguir, as principais razões para registrar bugs de forma estruturada e detalhada:

---

### ✅ Identificação e Solução de Problemas

Permite identificar rapidamente falhas no sistema, documentando o comportamento do erro, quando e como ocorreu. Isso facilita a análise da causa raiz e a aplicação de uma solução eficaz.

### ✅ Organização e Rastreabilidade

Manter bugs registrados em ferramentas como Jira, GitHub ou Trello facilita o acompanhamento do status das correções e priorizações, garantindo que nenhum problema seja esquecido e permitindo um controle claro do progresso.

### ✅ Priorização de Correções

O registro permite classificar os bugs por **severidade e impacto**, ajudando a equipe a focar nas falhas mais críticas primeiro e a alocar recursos de forma eficiente.

### ✅ Prevenção de Recorrências

Documentar não só o bug, mas também sua solução, contribui para que erros semelhantes não se repitam em versões futuras, criando um histórico de aprendizado e boas práticas.

### ✅ Melhoria Contínua

A análise de bugs recorrentes permite identificar pontos de melhoria no processo de desenvolvimento, levando a ajustes como revisão de testes, refatoração de código ou mudanças metodológicas.

### ✅ Comunicação Eficiente

Um bug bem documentado facilita a comunicação entre **desenvolvedores, QA, suporte e stakeholders**, tornando claro o que foi testado, o problema encontrado e sua solução, mesmo para quem não participou diretamente.

### ✅ Suporte ao Usuário

Para bugs que afetam o usuário final, o registro detalhado permite **respostas rápidas e precisas pelo suporte**, além de facilitar a reprodução e correção do problema, melhorando a experiência do cliente.

---

## 🗒️ Passo a Passo

## **📌 1. Identifique claramente o problema**

Confirme que é realmente um erro (algo que **não deveria acontecer**).

---

## **📌 2. Use uma ferramenta de rastreamento**

Registre o bug em uma ferramenta apropriada:

- **Jira**
- **Trello (com Power-Ups)**
- **GitHub Issues**
- **GitLab**
- **Bugzilla**
- **Azure DevOps**

---

## **📌 3. Preencha os campos com clareza**

| Campo | Descrição |
| --- | --- |
| Título | Curto e descritivo (ex.: *Erro ao salvar cadastro*). |
| Descrição | O que aconteceu, o que deveria acontecer e o que realmente ocorreu |
| Passos para reproduzir | Detalhe o passo a passo para o time conseguir replicar  |
| Ambiente  | Onde aconteceu (ex.: produção, homologação, navegador, dispositivo) |
| Logs ou Prints  | Inclua evidências: prints de tela, mensagens de erro ou logs |
| Gravidade/Prioridade | Avalie o impacto (baixa, média, alta, crítica) |

> 📌 **Nota:**
> 
> 
> **Exemplos de ambientes:**
> 
> - **Produção** → Sistema real usado pelo cliente/usuário final
> - **Homologação (HML)** → Ambiente de testes mais próximo da produção, usado para validar antes de liberar
> - **Desenvolvimento (DEV)** → Ambiente onde os desenvolvedores testam as funcionalidades durante a construção
> - **Navegador ou Dispositivo**:
>     - Google Chrome, Firefox, Edge
>     - Android, iOS, Windows, Mac

---

## **📌 4. Mantenha a comunicação fluida**

- Notifique QA, devs ou PO.
- Atualize o ticket com testes, descobertas ou correções.

> 📌 Nota:
> 
> 
> Quando você registra um bug numa ferramenta como Jira, Trello ou Azure DevOps, ele vira um **ticket** (um item de tarefa que será acompanhado).
> 
> **Atualizar um ticket** significa **adicionar informações novas ou mudanças no status do problema**, conforme ele vai sendo tratado.
> 
> **O que normalmente se atualiza em um ticket:**
> 
> - Mudança de status (ex: De **Aberto** para **Em andamento** ou **Corrigido**)
> - Anexar novas evidências (prints, logs, vídeos)
> - Adicionar comentários (ex: "Bug corrigido no ambiente de homologação, aguardando reteste")
> - Incluir responsáveis ou envolvidos
> - Informar a versão onde foi corrigido
> - Descrever o resultado dos testes após a correção

---

## **📌 5. Verifique após correção**

Assim que corrigido, reteste para **garantir** que: 

- O bug não voltou.
- A correção não causou efeitos colaterais (regressões).

---

# 🎯 Conclusão

Registrar bugs de forma organizada e completa é essencial para:

- Garantir qualidade
- Evitar retrabalho
- Aumentar a segurança e confiabilidade do software
- Melhorar a experiência do usuário

Essa prática fortalece a **gestão de qualidade (QA)** e torna o processo de desenvolvimento mais seguro, eficiente e transparente.

---