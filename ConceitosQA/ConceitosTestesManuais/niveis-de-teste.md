# Níveis de Teste

Os **níveis de teste** representam as diferentes etapas em que o software é validado ao longo do desenvolvimento. Cada nível tem um foco específico, desde testar pequenas partes isoladas do código até validar o sistema como um todo, pronto para uso real.

Os dois níveis mais comuns são:

- **Teste Unitário**: verifica se cada **função ou método individual** funciona corretamente.
- **Teste de Integração**: avalia se **módulos ou componentes diferentes funcionam bem juntos**.

Esses níveis ajudam a identificar falhas cedo, garantir estabilidade e aumentar a qualidade final do sistema.

---

# ✅ Teste Unitário

## 📖 O Que é Teste Unitário?

O **teste unitário** é um tipo de teste de software que verifica se **uma pequena parte isolada do código** (geralmente uma **função ou método**) está funcionando corretamente.

A ideia é **testar cada “peça” do sistema separadamente**, para garantir que ela funciona como esperado antes de integrar tudo.

Um **teste unitário** verifica se **uma parte pequena e isolada do código** (como uma função ou método) está funcionando corretamente. Ele:

- Recebe uma entrada
- Executa a função
- Verifica se a saída está certa

---

## 🎯 Objetivo dos Testes Unitários

- Detectar **erros rapidamente**, ainda na fase de desenvolvimento
- **Facilitar manutenções futuras** ou refatorações no código
- Garantir que **alterações no sistema não quebrem o que já funcionava**
- Servir como **documentação viva** sobre o que o código faz

---

## ✅ Onde são usados?

- Em testes **automatizados**
- Durante o desenvolvimento (frequentemente aplicados com TDD (Test-Driven Development — Desenvolvimento Guiado por Teste, uma prática de desenvolvimento onde os testes unitários são escritos antes mesmo do código funcional)).
- Principalmente por **desenvolvedores**, mas também em automações QA.

---

## 📌 Exemplo de Código com Teste Unitário (em Python)

### Código da função que será testada:

```python
def soma(a,b):
	return a+b
	
```

**Função simples:**  Recebe dois valores e retorna a soma.

Esta função é a “unidade” que queremos testar.

---

### Código do teste:

```python
import unittest 
#Importa a biblioteca padrão do Python para testes.

class TestSoma(unitteste.TestCase): 
#Cria uma classe de teste que herda os métodos de verificação da biblioteca unittest.

	def test_soma_positivos(self): 
	#Define um cso de teste para somar dois números positivos.
	
		self.assertEqual(soma(2, 3), 5)
		#Compara o resultado da função soma(2, 3) com o valor esperado 5.
		
	def teste_soma_negativos(self)
	#Define outro caso de teste para números negativos.
	
		self.assertEqual(soma(-1, -1), -2)
		# Verifica se soma/(-1, -1) retorna -2.
		
	if __name__ == '__main__':
	#Verifica se o script está sendo executado diretamente.
	
	unittest.main()
	#Roda todos os testes definidos na classe.
```

---

## ✅ Resultado Esperado

Ao executar esse script, o terminal irá mostrar:

- Quantos testes foram executados
- Se todos passaram ✅ ou se algum falhou ❌
- Detalhes sobre possíveis falhas, caso existam

---

# ✅ Teste de Integração

## 📖 O que é Teste de Integração?

O **teste de integração** é o tipo de teste que verifica se **diferentes partes do sistema trabalham bem juntas.** Enquanto o teste unitário foca em **funções isoladas,** o de integração garante que a **comunicação entre módulos, serviços, API’s ou banco de dados** funcione coretamente.

---

## 📌 O que é testado no teste de integração?

- Troca de dados entre funções e classes
- Acesso ao banco de dados
- Comunicação com **APIs, arquivos ou serviços externos**
- Interação entre front-end e back-end

---

### ✅ Exemplo prático

Você tem:

1. Uma função que **busca dados no banco**
2. Outra que **processa esses dados**

O teste de integração verifica se:

- A função 1 retorna os dados corretamente
- A função 2 consegue **usar essa resposta sem erro**

---

## 📊 Comparativo com outros tipos de teste

| **Tipo de Teste** | **O que testa** | **Isolado?** | **Velocidade** |
| --- | --- | --- | --- |
| **Unitário** | Função ou método individual | ✅ Sim | ⚡ Rápido |
| **Integração** | Módulos trabalhando juntos | ❌ Não | ⌛ Médio |
| **Sistema/E2E** | O sistema compelto, como um usuário | ❌ Não | 🐢 Mais lento |

---

## 🎯 Benefícios do Teste de Integração

- Garante que os **módulos se “conversem” direito**
- Captura erros que o teste unitário **não detecta**
- **Valida dependências externas** (como APIs e banco de dados)

---

# ✅ Teste de Sistema

## 📖 O que é?

O **teste de sistema** é o tipo de teste que verifica se o **sistema completo** funciona corretamente, de ponta a ponta, conforme os requisitos definidos.

Ele simula a interação **real do usuário final** com todas as partes da aplicação.

---

## 🎯 Objetivo

Garantir que:

- Todas as funcionalidades funcionem **em conjunto**.
- O sistema **atenda às regras de negócio**.
- A experiência do usuário esteja **fluida e consistente**.

---

## 🔍 Exemplo prático

Imagine um sistema de e-commerce. Um teste de sistema validaria todo o fluxo:

1. Abrir o site
2. Pesquisar um produto
3. Adicionar ao carrinho
4. Finalizar a compra
5. Confirmar o pedido

➔ O teste verificaria **cada etapa**, desde a interface até o banco de dados e APIs, tudo integrado.

---

## 📌 Características dos Testes de Sistema

- Testam a **aplicação completa**.
- Validação de **interfaces**, **banco de dados**, **APIs**, **regras de negócio**.
- Podem ser **manuais** ou **automatizados**.
- Geralmente realizados **após** os testes unitários e de integração.

---

# ✅ Teste de Aceitação

## 📖 O que é Teste de Aceitação?

O **teste de aceitação** é um tipo de teste que verifica se o sistema **atende às expectativas e requisitos** definidos pelo cliente ou usuário final.

Geralmente é realizado no **final do ciclo de desenvolvimento**, sendo a **última validação antes da entrega oficial** do software.

---

## 🎯 Objetivos dos Testes de Aceitação

Garantir que o sistema:

- Está **pronto para ser entregue**
- **Atende às regras de negócio** acordadas
- Funciona de acordo com os **requisitos e critérios de aceitação** definidos

---

## 🔍 Exemplo prático

Se o sistema de uma loja virtual prometeu:

- Permitir **cadastro de usuário**
- Permitir **adição de produtos ao carrinho**
- Permitir **pagamento com cartão de crédito**

➔ O teste de aceitação irá **simular todo esse fluxo**, confirmando que todas essas funcionalidades realmente funcionam como combinado.

---

## 📊 Diferença entre tipos de teste

| 🧪 Tipo de Teste | 🔥 Foco | 👤 Quem executa? |
| --- | --- | --- |
| Unitário | Funções isoladas | Devs |
| Integração | Comunicação entre módulos | Devs/QA |
| Sistema | Funcionamento do sistema completo | QA |
| Aceitação | Confirmação pelo ponto de vista do cliente | Cliente / PO / PM / QA |

---

> 📝 **Em resumo:**
> 
> 
> **Teste de aceitação = “**O sistema está pronto para o cliente?”
> 
> → Foco total no **valor entregue, não apenas no funcionamento interno.**
>
