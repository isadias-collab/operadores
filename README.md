# 🧮 Painel de Operadores JavaScript – SENAI

## 📌 Descrição do Projeto

Este projeto consiste em um painel interativo desenvolvido em HTML, CSS e JavaScript com o objetivo de praticar e visualizar o funcionamento dos principais operadores da linguagem JavaScript.

O usuário insere dois números e o sistema calcula automaticamente diversas operações, organizadas por categoria.

A aplicação funciona diretamente no navegador e não utiliza banco de dados.

---

## 🎯 Objetivo da Atividade

Compreender na prática o funcionamento dos operadores em JavaScript, incluindo:

- Operadores Aritméticos
- Operadores de Atribuição
- Operadores de Comparação
- Operadores Lógicos
- Operadores de Incremento e Decremento
- Operador Ternário
- Manipulação do DOM
- Validação de dados com `isNaN()`
- Conversão de tipos com `Number()`

---

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript

---

## ▶️ Como Executar o Projeto

1. Abra o VS Code (ou outro editor).
2. Crie um arquivo chamado:

```
painel_operadores.html
```

3. Copie o código fornecido.
4. Salve o arquivo.
5. Abra no navegador.
6. Digite dois números.
7. Clique em **Calcular Tudo**.

O painel exibirá automaticamente os resultados organizados por categoria.

---

## 🧠 Conceitos Trabalhados

### 🔢 1. Operadores Aritméticos

Realizam cálculos matemáticos:

- `+` Soma  
- `-` Subtração  
- `*` Multiplicação  
- `/` Divisão  
- `%` Resto da divisão  
- `**` Potência  

Exemplo:
```javascript
a + b
a ** b
```

---

### 📝 2. Operadores de Atribuição

Utilizados para atribuir valores às variáveis:

- `=` Atribuição simples  
- `+=` Soma e atribui  
- `-=` Subtrai e atribui  
- `*=` Multiplica e atribui  

---

### ⚖️ 3. Operadores de Comparação

Retornam valores booleanos (`true` ou `false`):

- `==` Igualdade (valor)
- `===` Igualdade estrita (valor e tipo)
- `!=` Diferente
- `>` Maior que
- `<=` Menor ou igual

---

### 🔗 4. Operadores Lógicos

Trabalham com expressões booleanas:

- `&&` E (AND)
- `||` OU (OR)
- `!` NÃO (NOT)

Exemplo:
```javascript
(a > 0 && b > 0)
```

---

### ➕➖ 5. Incremento e Decremento

- `++` Incrementa 1
- `--` Decrementa 1

---

### ❓ 6. Operador Ternário

Estrutura simplificada de condição:

```javascript
condição ? "valor se verdadeiro" : "valor se falso"
```

Exemplo:
```javascript
a > b ? "Sim" : "Não"
```

---

## 🌐 Manipulação do DOM

O conteúdo é gerado dinamicamente usando:

```javascript
painel.innerHTML = `...`
```

Isso permite que os resultados sejam exibidos na página sem recarregá-la.

---

## ✅ Validação de Dados

O sistema verifica se os valores inseridos são números válidos utilizando:

```javascript
isNaN()
```

Caso não sejam válidos, o sistema exibe um alerta ao usuário.

---

## 📚 Aprendizado Desenvolvido

Este projeto permite praticar:

- Lógica de programação
- Conversão de tipos de dados
- Estruturas condicionais
- Manipulação do DOM
- Organização de código JavaScript
- Uso de template strings (`` ` ` ``)

---

## 🚀 Possíveis Melhorias Futuras

- Adicionar tratamento para divisão por zero
- Permitir mais de dois números
- Melhorar responsividade
- Adicionar histórico de cálculos
- Implementar modo escuro

---

## 👩‍💻 Autoria

Projeto desenvolvido como prática de operadores JavaScript no SENAI.
