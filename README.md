# 🧠 Boas Práticas de Desenvolvimento de Software

Desenvolver software de qualidade vai além de “fazer funcionar”.  
Um bom desenvolvedor escreve código **escalável, legível e sustentável**, aplicando **princípios de design**, **padrões de projeto** e **boas práticas de legibilidade**.  

Este guia reúne três pilares essenciais de engenharia moderna:
- 🧩 **S.O.L.I.D**
- 🎨 **Design Patterns**
- ✨ **Clean Code**

---

## 🧩 S.O.L.I.D

Os princípios **S.O.L.I.D**, definidos por **Robert C. Martin (Uncle Bob)**, são fundamentos da programação orientada a objetos.  
Eles ajudam a criar sistemas **flexíveis, desacoplados e de fácil manutenção**.

| Letra | Nome | Conceito |
|--------|------|-----------|
| **S** | **Single Responsibility Principle** | Uma classe deve ter apenas **uma responsabilidade** e um único motivo para mudar. |
| **O** | **Open/Closed Principle** | As classes devem estar **abertas para extensão**, mas **fechadas para modificação**. |
| **L** | **Liskov Substitution Principle** | Subclasses devem poder **substituir suas superclasses** sem alterar o comportamento do sistema. |
| **I** | **Interface Segregation Principle** | Uma classe não deve ser forçada a **implementar métodos que não utiliza**. |
| **D** | **Dependency Inversion Principle** | Dependa de **abstrações, não de implementações** (injeção de dependências). |

📍 **Resultado:**  
Código **testável**, **flexível** e **desacoplado**.

---

## 🎨 **Design Patterns**

Os **Design Patterns** (*Padrões de Projeto*) são **soluções comprovadas** para problemas recorrentes de design de software.  
Eles **não são regras fixas**, mas sim **modelos reutilizáveis** que orientam boas decisões arquiteturais.

---

### 🔹 **Categorias Principais**

| Tipo | Objetivo | Exemplos |
|------|-----------|----------|
| **Criacionais** | Controlam a criação de objetos | Singleton, Factory Method, Builder |
| **Estruturais** | Organizam classes e objetos | Adapter, Composite, Decorator, Facade |
| **Comportamentais** | Definem interações e responsabilidades | Strategy, Observer, Command, Template Method |  



## ✨ **Clean Code**

O **Clean Code**, popularizado por *Robert C. Martin (Uncle Bob)*, é um conjunto de **boas práticas** que tornam o código  
**simples de entender**, **fácil de manter** e **agradável de evoluir**.

---

### 🧭 **Princípios Gerais**

| Princípio | Descrição |
|------------|------------|
| **Nomes significativos** | Métodos e variáveis devem descrever o que fazem. |
| **Funções pequenas** | Cada função deve ter uma única responsabilidade. |
| **Evite duplicação (DRY)** | Código duplicado é difícil de manter. |
| **Comentários claros** | Use comentários apenas quando o código não for autoexplicativo. |
| **Tratamento de erros** | Prefira exceções a códigos de erro. |
| **Formatação consistente** | Código limpo é também visualmente organizado. |  

📍 **Diferença:**  
Legibilidade, clareza e propósito explícito.

---

## 🧱 **Conexão entre os Três Pilares**

| Conceito | Objetivo Principal | Resultado Esperado |
|-----------|-------------------|---------------------|
| **S.O.L.I.D** | Estruturar código orientado a objetos | Menos acoplamento, mais testabilidade |
| **Design Patterns** | Reutilizar soluções de design comprovadas | Código extensível e sustentável |
| **Clean Code** | Garantir legibilidade e simplicidade | Código compreensível e fácil de evoluir |

---

## 💬 **Conclusão**

> Um bom desenvolvedor não mede seu valor pela quantidade de código escrito,  
> mas pela **qualidade, clareza e manutenibilidade** do que entrega.

---

### 🧠 **Aplique Sempre:**

- 🧩 **S.O.L.I.D** → para manter boas estruturas  
- 🎨 **Design Patterns** → para resolver problemas de design  
- ✨ **Clean Code** → para tornar o código legível e profissional

