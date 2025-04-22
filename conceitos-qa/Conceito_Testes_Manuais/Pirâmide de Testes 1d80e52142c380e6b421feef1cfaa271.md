# Pirâmide de Testes

A **Pirâmide de Testes** é um conceito usado em desenvolvimento de software para orientar a melhor estratégia de testes, buscando **equilíbrio entre eficiência, custo e cobertura de qualidade**.

Ela propõe que a maior parte dos testes deve ser feita nos níveis mais baixos da aplicação (mais rápidos e baratos) e, à medida que se sobe para níveis mais complexos (mais lentos e caros), a quantidade de testes deve diminuir.

---

## ✅ Camadas da Pirâmide de Testes

![Net_Zero_Pyramid-removebg-preview.png](Pira%CC%82mide%20de%20Testes%201d80e52142c380e6b421feef1cfaa271/Net_Zero_Pyramid-removebg-preview.png)

### 📌 Testes Unitários — Base da Pirâmide

- **Testam pequenas unidades isoladas** do sistema, como funções ou métodos.
- São **rápidos, automatizáveis e fáceis de manter**.
- Devem representar a **maior parte dos testes**, pois ajudam a detectar erros logo no início do desenvolvimento.

---

### 📌 Testes de Integração — Meio da Pirâmide

- Verificam se **módulos ou componentes diferentes interagem corretamente**.
- São mais lentos que os unitários, já que envolvem comunicação entre partes do sistema.
- Devem ser em menor quantidade que os unitários, mas são **fundamentais para garantir o funcionamento conjunto dos componentes**.

---

### 📌 Testes de Interface — Topo da Pirâmide

- Validam a **interação do usuário com o sistema**, como testes de interface gráfica (UI) e testes de ponta a ponta (end-to-end).
- **São os mais lentos, caros e frágeis**, exigindo mais recursos e tempo.
- A quantidade de testes aqui deve ser a menor, pois mudanças frequentes na interface podem causar quebras.

---

## 🎯 Por quê usar a Pirâmide de Testes?

Essa abordagem:

- **Garante uma cobertura de testes eficiente e balanceada**
- **Prioriza testes rápidos e baratos**, reduzindo o custo e tempo de validação
- **Assegura que erros sejam detectados cedo**, quando são mais fáceis e baratos de corrigir
- **Evita excesso de testes caros e demorados**, focando naquilo que realmente importa para a estabilidade do sistema

---