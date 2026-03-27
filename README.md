## ATIVIDADE 1

## Exercícios

Foram feitos vários exercícios em C envolvendo vetores, matrizes, struct e ponteiros.

---

## Exercício 1
- lê três palavras
- imprime na ordem inversa

---

## Exercício 2
- cria um vetor com 5 números
- lê os valores
- imprime em ordem inversa

---

## Exercício 3
- lê uma matriz 3x3
- multiplica cada elemento por 5
- imprime o resultado

---

## Exercício 4
- gera a matriz identidade 3x3
- multiplica pela matriz original
- mostra que o resultado é a mesma matriz

---

## Exercício 5
- lê um vetor de 3 elementos
- lê uma matriz 3x3
- faz a multiplicação do vetor pelas colunas da matriz

---

## Exercício 6
- lê dados de 10 alunos (nome, matrícula, média)
- separa em aprovados e reprovados
- mostra os dois grupos

---

## Exercício 7
- lê dados de 5 livros
- busca por título
- mostra os livros encontrados

---

## Exercício 8
- lê um array de 5 inteiros
- usando ponteiros
- imprime o dobro de cada valor

---

## Exercício 9
- lê 3 valores
- ordena usando função com ponteiros
- retorna 1 se todos forem iguais, senão 0

---

## Exercício 10
- usa struct Aluno (nome e nota)
- aloca memória dinamicamente
- encontra o aluno com maior nota

---

## Como foi feito
- uso de struct
- uso de vetores e matrizes
- uso de ponteiros
- uso de malloc em alguns exercícios

---

## Regras do trabalho
- sem variáveis globais (ex 10)
- sem vetor estático (ex 10)
- acesso usando ponteiros (ex 10)
---------------------------------
## ATIVIDADE 2
## Desafio 1
Verificação de expressão.
O programa:
- recebe uma string com (), {} e []
- verifica se está correta
Regras:
- tudo que abre tem que fechar
- a ordem tem que estar certa
Exemplo:
- ([]) → válido  
- ([)] → inválido  
---
------------
## Desafio 2
Inversão de string com pilha.
O programa:
- recebe uma string
- coloca os caracteres na pilha
- retira para formar a string invertida
---
## Como foi feito
- uso de struct
- uso de ponteiros
- pilha implementada com lista encadeada
- uso de malloc e free
---
## Funções
- push -> inserir
- pop -> remover
- isEmpty -> verificar se está vazia
---
## Regras do trabalho
- não foram usadas bibliotecas prontas
- não foi usada função pronta para inverter string
- não foi utilizado vetor auxiliar
- manipulação feita apenas com a pilha
---------------------------------------------------------------
## ATIVIDADE 3
## Desafio 1
Fila de clientes.
Cada cliente tem:
- id
- tempo de atendimento
O programa:
- lê quantos clientes vão ter
- coloca eles na fila na ordem que chegam
- atende um por um
- mostra o id e quanto tempo esperou
O tempo de espera é a soma do tempo dos clientes que estão na frente.
---
---------
## Desafio 2
Fila de impressão com prioridade.
Cada documento tem:
- id
- número de páginas
- prioridade
Regras:
- menor número = maior prioridade
- se tiver empate, mantém quem chegou primeiro
A fila já fica organizada quando insere.
---
## Como foi feito
- uso de struct
- uso de ponteiros
- fila implementada com lista encadeada
- uso de malloc e free
---
## Funções
- enqueue -> inserir
- dequeue -> remover
---
## Regras do trabalho
- não foi utilizado vetor
- não foram usadas bibliotecas prontas
- não foi utilizado sort (ex: qsort)
----------
Feito por João Gabriel Bamberg e Ramon.
---------
