# Fundamentos de Algoritmos

## Tipologia e variáveis:

### Tipos de dados: 

#### Numérico: 
- Inteiros ( todos os números negativos e positivos que não possuem casas decimais); 
- Reais (positivos e negativos com casas decimais). 

#### Caractere: 
- Tudo aquilo que não representamos como número. 

#### Lógico/ booleano: 
- Verdadeiro;  
- Falso. 

### Para podermos usar esses tipos de dados precisamos das variáveis.

#### O que é uma variável?

uma variável é um tipo de estrutura mutável, pode mudar dentro do seu valor, pode ser subscrita, pode receber mais de um valor , inconstante, instável. A variável pode assumir qualquer um dos valores de um determinado conjunto de valores. 

#### Regras para nome de variável: 
- Atribuição de um ou mais caracteres;
- Primeira letra - não numérico;
- Sem espaço em branco; 
- Vedado à utilização de palavras reservadas; 

#### Papeis de uma variável: 
- Ação: Modifica o estado do algoritmo, estado do programa;
- Controle: Vigiada, controlada. 

### O que é constante? 
Tudo aquilo que é fixo ou estável. 

## Instruções primitivas:

 #### O que são instruções?
 Instruções são linguagem de palavra-chave(vocabulário) de uma determinada de programação que tem por finalidade comandar um computador que irá tratar os dados. Instruções determinam as ações que iremos usar em nossos dados. 

### Variáveis e Constantes 

- Operadores unário 
- Operadores Binários

#### Exemplo:

### Variável: 
Nota1 = 5
Nota2 = 8
Resultado = 0

### Constante:
Resultado = (Nota1 + Nota2) /2   

Escreva resultado

Fim programa 

Saída:
  6.5

## Estruturas condicionais e operadores

#### O que é condição?
Estado de uma pessoa ou coisa.

#### O que é condicional?
Que expressa uma condição ou suposição  contem ou implica uma suposição ou hipótese. 

### Estrutura condicional: 

Possui 3 tipos de estruturas são elas: 

#### Simples :

Se (<condição>) então 
<instruções para condição verdadeira> 
fim_se

#### Composta: 
Se (<condição>) então 
<instruções para condição verdadeira> 
Senão 
<instruções para condição falsa> 
fim_se

#### Encadeado:
Se (<condição1>) então 
<instruções para condição verdadeira> 
Senão 
Se (<condição2>) então 
<instruções para condição 2 verdadeira e condição 1 falsa> 
Senão 
<instruções para condição 1 e 2 falsa> 
fim_se

### Operadores lógicos:

#### Quando utilizar? 
- Quando tiver uma situação lógica como V ou F; 
- Substituição de encadeamento de condições.

#### Tipos de operadores lógicos:

#### And:
Operador Lógico que verifica as entradas que devem ser satisfeita, ele é sempre falso se for um ou outro ou verdadeiro se os dois são iguais. 

#### or:
Se uma condição é verdadeira e a outra falsa falo que a condição é verdadeira, caso as duas seja falsa então é falsa. 

#### NOT:
Operador lógico de negação, inversão do resultado lógico. Caso tenha uma condição verdadeira ela vira falsa e a falsa vira verdadeira. 

## Estrutura de repetição: 

A estrutura de repetição irá executar um determinado trecho de programa a partir de certos parâmetros, por isso existe as condições de paradas que podem ser:
- Números de repetições pré-fixada;
- Condição a ser satisfeita.

São sinônimos: laços, controle de fluxo, malhas de repetição, repetição, loop. 

#### Por que não repetir meu código?
Usar a estrutura de repetição pode:
- Reduzir linhas; 
- compreensão facilitada; 
- Redução de erro. 

## Vetores e matrizes 

#### Vetor: 
Um vetor é caracterizado por uma variável dimensionada com tamanho pré -fixado. Também pode ser encarado como um container ou como uma matriz unidimensional. 

### Matriz: 
Uma matriz é uma tabela organizada em linhas e colunas no formato m x n. M números de linhas (horizontal) N numero que colunas (vertical). 

#### O que conseguimos com vetores e matrizes? 
- Menor quantidade de linhas;
- Melhor compreensão de código e etc. 

## Função

#### O que é função? 
As funções ou sub- rotinas são blocos de instruções que realizam tarefas específicas. Vem da ideia de decomposição do algoritmo, modularização do problema. Similar ao conceito de função matemática. 

#### Por que usar função? 

- Modularização do problema;
- Código mais claro e conciso;
- Reutilização de instruções.

#### Função também é: 

- Blocos de instruções(códigos) identificados por nomes e parâmetroS; 
- Definição;
- Nome;
- Invocação;
- Variável local - são destruídas ao encerrar a função.

## Instruções de entrada/ saída

#### O que são Entradas?
Consiste na inserção e recebimento de dados do mundo real por meio de ação de alguma interface, seja teclado, mouse, arquivos, entre outros. 

 #### O que são saídas ?
Consiste na impressão dos dados do mundo abstrato, digital por meio de ação de alguma interface. Os formatos podem varias desde simples arquivos binários até complexas querys de banco de dados. 

Existem dois tipos de saídas dentro de um programa são eles: 

- Saída programada - condicional - guarda o dispositivo / incondicional; 
- Saída por interrupção - definida pelos periféricos.

#### Para toda saída existe um caso como:
- Bem sucedida;
- Erro de sintaxe ou outro; 
- Erros de programação;
- Problemas com a interface.
