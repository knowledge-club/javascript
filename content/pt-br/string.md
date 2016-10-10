## String

Um dos tipos de variáveis que temos em Javascript é o tipo String. String é a mesma coisa que texto. Tecnicamente, é um conjunto de caracteres :D. Para criarmos strings, usamos aspas simples ou duplas. Vejamos exemplos:

```js
var phrase = 'You know nothing';
var username = "John"
```

Notem, para *atribuirmos* um valor a uma varíavel, usamos um operador `=`. Sempre o usaremos para isto, atribuir um valor a uma variável. Segundo, nós criamos strings, usando aspas. No exemplo acima fizemos com aspas simples, e outra com aspas duplas. Embora ambos sejam válidos, em Javascript o padrão é usarmos aspas simples, então corrigindo o código ficaria assim:

```js
// following patterns, use single quotes
var phrase = 'You know nothing';
var username = 'John';
```

Bem melhor!! Agora vejamos como trabalhar com estas strings.

Primeiro, o username está errado, o correto seria John Snow. Então, para sobrescrever o valor da variável, basta que chamemos o nome da variável novamente.

```js
username = 'John Snow';
``

Note, para atribuir outro valor a uma variável já existente, só usamos o nome da variável seguido do operador `=` e enfim o valor a ser atribuido, no caso a string 'John Snow'. O uso da palavra `var` é feito apenas quando se cria, não quando se usa.

Em seguida, vamos exibir console nossas variáveis. O console é útil para testarmos se o que estamos fazendo está correto. Para exibir alguma variável no console, basta usar a função `console.log`, exemplo:

```js
console.log('Hello');
``` 

Entre os parênteses, vem o valor a ser exibido. Veremos mais detalhes sobre funções mais para frente, mas por hora, saiba que a função console.log sabe exibir no console o valor da varíavel.

Portanto se desejamos exibir o valor da variável username, usamos:

```js
console.log(username);
console.log(phrase);
```

Não confunda, as aspas são para criar uma string, como nossa string já está vem variáveis, podemos usar tais variáveis apenas usando o nome delas.

Desejamos exibir os valores das duas variáveis ao mesmo tempo, e há duas formas de fazer isto. Vejamos a primeira que seria pelo que chamamos de `concatenacao`, que nada mais é do que juntar duas strings ou mais strings em uma só. Para concatenar strings, usamos o operador `+` entre as variáveis, exemplo:

```js
phrase + username;
```

No entanto, as variáveis phrase e username continuam tendo seus valores distintos, o código acima apenas gerou uma nova string e utilizou, sem alterar as originais.

Mas se quisemos exibir no console, precisamos usar o console.log, então:

```js
console.log(phrase + username);
// exibirá 'You know nothingJohn Snow'
```

E você deve ter notado que a string concatenada não teve espaço entre elas. Para exibí-las de forma adequada, concatenamos uma string com espaço entre elas, assim:

```js
console.log(phrase + ' ' + username);
// agora sim, 'You know nothing John Snow';
```