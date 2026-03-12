````markdown
# Estruturas de Decisão na Lógica de Programação

## 1. O que são Estruturas de Decisão

As **estruturas de decisão** são construções utilizadas na lógica de programação que permitem que um programa **tome decisões com base em determinadas condições**.

Elas possibilitam que o fluxo de execução de um algoritmo **siga caminhos diferentes**, dependendo do resultado de uma expressão lógica.

Em outras palavras, estruturas de decisão permitem que o programa responda a perguntas como:

- "Se isso acontecer, faça algo."
- "Caso contrário, faça outra coisa."

Essas decisões são normalmente baseadas em **expressões booleanas**, que resultam em dois valores possíveis:

- `true` (verdadeiro)
- `false` (falso)

---

## 2. Importância das Estruturas de Decisão

Sem estruturas de decisão, um programa executaria sempre **as mesmas instruções na mesma ordem**, sem considerar diferentes situações.

Com as estruturas de decisão, é possível:

- validar dados
- controlar o fluxo do programa
- executar ações diferentes dependendo das condições
- implementar regras de negócio

Essas estruturas são fundamentais para criar programas **dinâmicos e inteligentes**.

---

## 3. Estrutura Condicional Simples

A estrutura condicional simples executa um bloco de código **somente se uma condição for verdadeira**.

### Exemplo em pseudocódigo

```text
se idade >= 18 então
    escrever "Maior de idade"
fim_se
```

Nesse exemplo:

- o programa verifica se `idade >= 18`
- se a condição for verdadeira, a mensagem será exibida
- se for falsa, nada acontece

---

## 4. Estrutura Condicional Composta

A estrutura condicional composta permite executar **um bloco de código caso a condição seja verdadeira** e **outro bloco caso seja falsa**.

### Exemplo em pseudocódigo

```text
se idade >= 18 então
    escrever "Maior de idade"
senão
    escrever "Menor de idade"
fim_se
```

Nesse caso:

- se a idade for maior ou igual a 18, o programa exibe "Maior de idade"
- caso contrário, exibe "Menor de idade"

---

## 5. Estrutura Condicional Encadeada

Em algumas situações é necessário verificar **mais de duas possibilidades**. Para isso são utilizadas **estruturas condicionais encadeadas**.

### Exemplo em pseudocódigo

```text
se nota >= 7 então
    escrever "Aprovado"
senão se nota >= 5 então
    escrever "Recuperação"
senão
    escrever "Reprovado"
fim_se
```

Nesse exemplo:

- notas maiores ou iguais a 7 resultam em **Aprovado**
- notas entre 5 e 6 resultam em **Recuperação**
- notas menores que 5 resultam em **Reprovado**

---

## 6. Operadores Relacionais

As decisões em um programa geralmente utilizam **operadores relacionais**, que comparam valores.

Alguns operadores comuns são:

| Operador | Significado |
|--------|--------|
| `>` | maior que |
| `<` | menor que |
| `>=` | maior ou igual |
| `<=` | menor ou igual |
| `==` | igual |
| `!=` | diferente |

### Exemplo

```text
se temperatura > 30 então
    escrever "Está quente"
fim_se
```

---

## 7. Operadores Lógicos

Também é possível combinar várias condições usando **operadores lógicos**.

Os principais são:

| Operador | Significado |
|--------|--------|
| `E` | todas as condições devem ser verdadeiras |
| `OU` | pelo menos uma condição deve ser verdadeira |
| `NÃO` | inverte o valor lógico |

### Exemplo

```text
se idade >= 18 E possui_carteira = verdadeiro então
    escrever "Pode dirigir"
fim_se
```

Nesse caso, **as duas condições precisam ser verdadeiras**.

---

## 8. Conclusão

As **estruturas de decisão** são essenciais na lógica de programação porque permitem que os programas **tomem decisões e executem ações diferentes dependendo das condições**.

Utilizando condicionais e operadores lógicos, é possível criar algoritmos capazes de lidar com diferentes situações, tornando os programas **mais flexíveis e funcionais**.
````
