## Var

Variáveis são comuns em quaisquer linguagem de programação, e em Javascript não é diferente. Você usará elas para trabalhar com dados. Um nome de usuário digitado, um valor para somar com outro, são apenas alguns exemplos. Variáveis nada mais são do que alocações em memória.

Vamos ver como criar uma variável em Javascript:

```js
var player;
```

No exemplo acima, criamos uma variável de nome `player`, ainda sem valor atribuido.

Vamos a alguns detalhes imporantes da linguagem, primeiro, para criar uma variável use a palavra reservada `var` e em seguida dê um nome para sua variável.

Já o nome que você dá à variável, não pode começar por número, mas pode conter ou terminar por números.

```js
// invalid
var 1player;
```

```js
// valid
var player1;
```

Também não é permitido usar operadores da linguagens no nome da variável, ou mesmo usar nomes reservados da linguagem para nomeá-las.

```js
// invalid, '-'' é um operador
var player-1;
// invalid, var é uma palavra reservada da linguagem
var var;
```

```js
// valid, 
var player_javasacript
```

Embora símbolos sejam permitidos no nome de variávies (_, $, @, entre outros), existem padrões tanto de Javascript, como de ferramentas que você provavelmente venha a usar. Mas em geral, os padrões mais importantes em Javascript são:

- nome de variáveis são em letras minúsculas
- se o nome da variável for composto, exemplo, user address, use camel case

O camel case consiste em deixar a primeira letra das palavras subsequentes (não a primeira) em maíuscula

```js
// valid but not follow patterns
var user_height;
```

```js
// valid and following patterns
var userHeight;
```

Por último, um último padrão sobre declaração de variáveis. Se for declarar muitas ao mesmo tempo, o Javascript permite usar vírgula, mas não é o padrão.

```js
// valid but not follow patterns
var userName, userAddress, userHeight;
```

```js
// valid and following patterns
var userName;
var userAddress;
var userHeight;
```

Outra coisa, Javascript permite criar variáveis sem usar a palavra reservada `var`, mas há uma série de problemas com relação a isto.

```js
useName;
```

Portanto, use sempre a palavra `var` para criar suas variáveis.