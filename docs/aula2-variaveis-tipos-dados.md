```markdown
# Variáveis e Tipos de Dados na Lógica de Programação

## 1. O que são Variáveis

Em lógica de programação, **variáveis** são espaços na memória do computador utilizados para **armazenar valores que podem ser utilizados e modificados durante a execução de um programa**.

Uma forma simples de entender uma variável é imaginá-la como **uma caixa com um nome**, onde guardamos um valor que pode ser acessado ou alterado quando necessário.

### Exemplo

```

idade = 20
nome = "Matheus"

```

Nesse exemplo:

- `idade` é uma variável que armazena o valor `20`
- `nome` é uma variável que armazena o texto `"Matheus"`

O valor de uma variável pode mudar ao longo do programa:

```

idade = 20
idade = 21

```

Após a segunda atribuição, o valor armazenado na variável passa a ser **21**.

---

## 2. Regras gerais para nomes de variáveis

Embora existam diferenças entre linguagens de programação, algumas regras são comuns:

- Devem **começar com letra ou underline (`_`)**
- **Não podem começar com números**
- **Não podem conter espaços**
- **Não podem usar palavras reservadas da linguagem**

### Exemplos de nomes válidos

```

nome
idade
total_compra
valorFinal

```

### Exemplos de nomes inválidos

```

1nome
valor total
if

```

---

## 3. O que são Tipos de Dados

Os **tipos de dados** definem **qual tipo de informação uma variável pode armazenar**.

Eles são importantes porque permitem que o computador **interprete e manipule corretamente os valores armazenados**.

Cada tipo de dado representa uma categoria específica de informação, como números, textos ou valores lógicos.

---

## 4. Principais Tipos de Dados

### 4.1 Inteiro (Integer / Int)

Representa **números inteiros**, ou seja, números **sem casas decimais**.

Exemplos:

```

idade = 25
quantidade = 10
ano = 2026

```

---

### 4.2 Real (Float / Double)

Representa **números que possuem casas decimais**.

Exemplos:

```

altura = 1.75
peso = 68.5
preco = 19.99

```

---

### 4.3 Texto (String)

O tipo **string** armazena **cadeias de caracteres**, como palavras, frases ou símbolos.

Normalmente os textos são representados entre **aspas**.

Exemplos:

```

nome = "Matheus"
cidade = "Brasília"
mensagem = "Olá, mundo!"

```

---

### 4.4 Booleano (Boolean / Bool)

O tipo **booleano** armazena **valores lógicos**, usados principalmente em decisões dentro do programa.

Existem apenas dois valores possíveis:

- `true` (verdadeiro)
- `false` (falso)

Exemplos:

```

aprovado = true
maiorDeIdade = false

```

---

## 5. Exemplo combinando variáveis e tipos de dados

```

nome = "Matheus"
idade = 20
altura = 1.75
estudante = true

```

Nesse exemplo temos:

| Variável | Tipo de Dado | Valor |
|----------|--------------|-------|
| nome | String | Matheus |
| idade | Inteiro | 20 |
| altura | Real | 1.75 |
| estudante | Booleano | true |

---

## 6. Importância das Variáveis e Tipos de Dados

Variáveis e tipos de dados são **fundamentais na programação**, pois permitem:

- armazenar informações  
- realizar cálculos  
- manipular dados  
- tomar decisões no programa  
- organizar melhor a lógica do sistema  

Sem esses conceitos seria impossível desenvolver programas capazes de **processar informações dinamicamente**.

---

## 7. Conclusão

Variáveis funcionam como **locais de armazenamento de dados**, enquanto os tipos de dados determinam **qual tipo de informação pode ser armazenada nesses locais**.

Compreender esses conceitos é essencial para aprender programação, pois eles formam a **base da lógica de programação e do desenvolvimento de software**.
```
