## String

One type of variables that have Javascript is the type String. String is the same as text. Technically, is a set of characters :D. To create strings, we use quotes or double quotes. See example:

```js
var phrase = 'You know nothing';
var username = "John"
```

Note, to *assign* a value to variable, we use the operator `=`. 
Notem, para *atribuirmos* um valor a uma varíavel, usamos um operador `=`. Always we use for this, assign a value to a variable. Second, we create strings, using quotes. In the above example, we use quotes, and double quotes. While both are valid, in Javascript the pattern is use only quotes, so to fix the code above:

```js
// following patterns, use single quotes
var phrase = 'You know nothing';
var username = 'John';
```

So better!! Now we see how to work with these strings.

First, the username are wrong, the write is John Snow. Then, to overwrite the value of variable, 

Primeiro, o username está errado, o correto seria John Snow. Então, para sobrescrever o valor da variável, just what we call the variable name again.

```js
username = 'John Snow';
``

Note, to assign another value for an existing variable, only we use the variable name followed by the operator `=` and finally the value to be assigned, in our case the string 'John Snow'. The use of word `var` is built only when creating, not when  O uso da palavra `var` é feito apenas quando se cria, not when using.

Next, lets show at console our variables. The console is useful to test what we do. To show any variable in console, you just need use the function `console.log`, i.e:

```js
console.log('Hello');
``` 

Between parentheses, come the
Entre os parênteses, is the value to be displayed. We will see more details about more forward functions, but for now, know that the console.log function knows the console display the variable value.

So if we want to display the value of the variable username, use:

```js
console.log(username);
console.log(phrase);
```

Do not confuse, the quotes are to create a string, as our string already has variables, we can use these variables just using their name.

We want to display the values of two variables at the same time, and there are two ways to do this. Let's look at the first would be by what we call `concat`, which is nothing more than combining two strings or more strings into one. To concatenate strings, use the operator `+` between the variables, eg:

```js
phrase + username;
```

However, the variables phrase and username continue have distinct values, the above code only generate a new string and use it, without change the originals.

But if we wish display on screen, we nee

Mas se quisemos exibir no console, we neeed use the console.log, then:

```js
console.log(phrase + username);
// display 'You know nothingJohn Snow'
```

And you should see 
And you may have noticed that the concatenated string had no space between them. To display that right way, concatenate a string with space between them, so:

```js
console.log(phrase + ' ' + username);
// now yes, 'You know nothing John Snow';
```