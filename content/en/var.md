## var

Variables are common in any programming language, and in Javascript it is not different. You are going to use them to work with data such as: an user name, a value to sum with another. Variables are nothing more than memory allocation.

Let's see how we create a variable in Javascript:

```js
var player;
```

In the above example, we created a variable called `player`, without any value assigned.

Lets discuss some important details of the language. First: to create a variable use the keyword `var`; second give a name to it.

The variable names must follow some rules. One of them is that they may no begin with any kind of number or digit, but it is possible to have them in the end or in the middle.

```js
// invalid
var 1player;
```

```js
// valid
var player1;
```

It is also not allowed to use language operators in the variable name, or use any of the language's keywords to name them.

```js
// invalid, '-'' is a operator
var player-1;
// invalid, var is a reserved word
var var;
```

```js
// valid, 
var player_javasacript
```

Although symbols are allowed in variable names (`_`, `$`, `@`, etc), there are some Javascript patterns that define how they should be used, the most important of them is:

- Name of variables in lower case
- If the name is a compound name, Example 'user address', use camelCase

The camelCase consists in use the first letter of the first word in lower case and the subsequent words in upper case.

```js
// valid but don't follow patterns
var user_height;
```

```js
// valid and following patterns
var userHeight;
```

Then, one last pattern regarding variables. 

If you want to declare many at the same time, Javascript allows the use of commas. However this is not recommended by the Javascript codding standards.

```js
// valid but don't follow patterns
var userName, userAddress, userHeight;
```

```js
// valid and following patterns
var userName;
var userAddress;
var userHeight;
```

One last thing, Javascript allows us to create variables without the use of the reserved word `var`, but we will have a series of problems if we do this:

```js
useName;
```

So, always use the word `var` to create your variables.
