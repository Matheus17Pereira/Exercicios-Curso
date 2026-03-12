````markdown
# Estruturas de Repetição na Lógica de Programação

## 1. O que são Estruturas de Repetição

As **estruturas de repetição** são utilizadas na lógica de programação para **executar um conjunto de instruções várias vezes**, enquanto uma determinada condição for verdadeira ou até que um critério de parada seja atingido.

Esse tipo de estrutura é útil quando uma mesma ação precisa ser repetida várias vezes, evitando a necessidade de escrever o mesmo código repetidamente.

Por exemplo, estruturas de repetição podem ser utilizadas para:

- percorrer uma lista de valores
- repetir um cálculo várias vezes
- processar vários dados de entrada
- executar ações até que uma condição seja satisfeita

---

## 2. Importância das Estruturas de Repetição

Sem estruturas de repetição, seria necessário escrever manualmente várias instruções iguais para realizar tarefas repetitivas.

Com essas estruturas, é possível:

- reduzir a quantidade de código
- tornar o algoritmo mais organizado
- automatizar processos repetitivos
- facilitar a manutenção do programa

Elas são essenciais para criar programas que lidam com **grandes quantidades de dados ou processos contínuos**.

---

## 3. Estrutura de Repetição "Enquanto" (While)

A estrutura **enquanto** executa um bloco de código **enquanto uma condição for verdadeira**.

Antes de cada repetição, a condição é verificada. Se ela for verdadeira, o bloco de código é executado novamente.

### Exemplo em pseudocódigo

```text
contador = 1

enquanto contador <= 5 faça
    escrever contador
    contador = contador + 1
fim_enquanto
```

Nesse exemplo:

- o contador começa em 1
- o programa repete enquanto `contador <= 5`
- a cada repetição o valor é incrementado

O resultado será a impressão dos números de **1 até 5**.

---

## 4. Estrutura de Repetição "Para" (For)

A estrutura **para** é utilizada quando sabemos **quantas vezes a repetição deve ocorrer**.

Ela normalmente possui três partes:

- inicialização da variável de controle
- condição de parada
- atualização da variável

### Exemplo em pseudocódigo

```text
para i de 1 até 5 faça
    escrever i
fim_para
```

Nesse exemplo, o valor de `i` varia de **1 até 5**, e o bloco de código é executado cinco vezes.

---

## 5. Estrutura de Repetição "Faça Enquanto" (Do While)

A estrutura **faça enquanto** executa o bloco de código **pelo menos uma vez**, pois a condição é verificada **após a execução do bloco**.

### Exemplo em pseudocódigo

```text
contador = 1

faça
    escrever contador
    contador = contador + 1
enquanto contador <= 5
```

Nesse caso, o bloco será executado antes da verificação da condição.

---

## 6. Variável de Controle

Em estruturas de repetição é comum utilizar uma **variável de controle**, que é responsável por acompanhar quantas vezes o laço foi executado.

Exemplo:

```text
contador = 1
```

Durante cada repetição, essa variável geralmente é **incrementada ou modificada** até atingir a condição de parada.

---

## 7. Condição de Parada

Toda estrutura de repetição precisa possuir uma **condição de parada**, caso contrário o programa pode entrar em um **loop infinito**.

Um **loop infinito** acontece quando a condição de repetição nunca se torna falsa.

Exemplo de problema:

```text
contador = 1

enquanto contador <= 5 faça
    escrever contador
fim_enquanto
```

Nesse caso, o valor de `contador` nunca é alterado, fazendo com que a condição permaneça sempre verdadeira.

---

## 8. Conclusão

As **estruturas de repetição** são fundamentais na lógica de programação, pois permitem executar instruções de forma repetida de maneira controlada.

Com estruturas como **enquanto**, **para** e **faça enquanto**, é possível criar algoritmos mais eficientes, organizados e capazes de lidar com tarefas repetitivas de forma automatizada.
````
