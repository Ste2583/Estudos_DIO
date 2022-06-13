# Introdução ao JavaScript

### O que é o JavaScript?
O JavaScrip é uma linguagem de programação de alto nível, que integra o desenvolvimento de apps a páginas Web. É uma das linguagens mais usadas. 

### Para que serve?
Para criar scripts dinâmicos que realizam a interação de apps ou páginas web ( é a parte interativa do projeto).

#### Características básicas:
- Linguagem interpretada
- Baseada em Protótipos 
- Multiparadigma
- Comumente utilizada em aplicações web client-side
- Segue o padrão ECMAScript

#### Aplicações 
- web
- Mobile
- Smartwatches
- Games
- Internet of Things
- APIs

## Recursos Básicos 

#### Para comentar um código: 
- comentário de linha: basta digitar //
- comentário de várias linhas: /* (para abrir o comentário) */ (para fechar o comentário)

#### o que é uma variável:
Valores que podem ser alterados para encontrar o valor desejado. 
Sempre dar nome para a variável, um nome que faça sentido

Existem 3 modos de declarar as variáveis em JavaScript:

- Var: escopo global e local, pode ter seu valor alterado, se não tiver um valor inicial será tratada como null;

- let: escopo local de bloco, pode ter seu valor alterado, se não tiver um valor inicial será tratada como null;

- const: escopo local de bloco, somente leitura, o valor inicial é obrigatório e não pode ser alterado.

#### O que é uma constante?

Valores que não podem ser manipulados são sempre o mesmo. 
Para declarar uma constante o nome tem que ser escrito em letras maiúsculas. 

## Escopo

O escopo em JavaScript define a limitação e visibilidade de um bloco de código.

- Escopo global: quando a variável é declarada fora de qualquer bloco, sua visibilidade fica disponível em todo o código.

- Escopo local: quando a variável é declarada dentro de um bloco, sua visibilidade pode ficar disponível ou não.

#### Atribuição: 
O sinal de igualdade “=“ em JavaScript, significa atribuição.

#### Comparação: 
Para fazermos uma comparação de valores em JavaScript usamos
“==“.

#### Comparação idêntica:
Para fazermos uma comparação de valores e tipos em JavaScript usamos “===“.

#### Operadores aritméticos:
São tipos de operadores matemáticos com valor numérico:

- (+) adição;
- (-) subtração;
- (*) multiplicação;
- (/) divisão real;
- (%) divisão inteira;
- (**) exponenciação;

#### Operadores relacionais:
São tipos de operadores que consultam a relação entre valores:

- (>) maior que;
- (<) menor que;
- (>=) maior ou igual a;
- (<=) menor ou igual a;

#### Operadores lógicos:
São tipos de operadores que consultam valores lógicos:

- && - “e” – considera que todos os valores sejam true;
- || - “ou” – considera que qualquer valor seja true;
- ! - “não” – inverte o valor de true para false ou vice-versa;


## Funções

#### Como declarar:

- usando a palavra function
- dar um nome a essa função 
- dizer o que ela faz 

### Exemplo:

function soma(a, b) {
  return a + b; 
}

soma (3, 5);

ou 

function soma(a, b) {
console. log ( a + b) 
  return a + b; 
}

soma (3, 5);


#### Console

Uma maneira de depurar seu código. Esse comando irá mostrar no console de seu navegador o que estiver escrito na função log.


## JavaScript em uma página Web

#### Estrutura de projeto 
- 1° = index.html
-2° = criar pasta = assets (para arquivos que não são HTML)
- 3° = dentro da pasta assets criar = pasta js e pasta css
- 4° = dentro da pasta js criar = arquivo scripts.js
- 5° = dentro da pasta css criar = arquivo styles.css


## DOM

- document Object Model
- Estrutura dos elementos dentro da janela

## Array

#### O que são Array?
Arrays são um tipo de lista, ou matriz de variáveis, onde cada variável possui um índice. Os valores podem ser de vários tipos.

Imagina que um array é uma caixa com várias outras caixas dentro e cada uma contendo algum valor.

O array deve ser declarado entre colchetes “[]”, e podem guardar qualquer valor dentro de seus índices: inclusive outros arrays.

#### Manipulando Arrays:
Ao ser declarado, o Array traz consigo uma série de métodos para manipulá-lo.

- forEach() – itera um array;
- push() – add item no final do array;
- pop() – remove item no final do array;
- shift() – remove item no início do array;
- unshift() – add item no início do array;
- indexOf() – retorna o índice de um valor;
- splice() – remove ou substitui um item pelo índice;
- slice() – retorna uma parte de um array existente;

