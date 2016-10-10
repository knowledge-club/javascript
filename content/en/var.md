## Var

Variables be common in any programming languagel, and in Javascript dont be different. You will use their to work with data. A user name typed, a valur to sum with another, only be examples. Variables are nothing more than memory allocation.

Let's see how create a variable in Javascript:

```js
var player;
```

In before example, we create a variable with name `player`, without value assigned.

Let some important details of the language, first, to create a variable use the reserved word `var` and next, give a nem to your variable.

But the name you give to the variable, cant begin for number, but may contain or end with numbers.

```js
// invalid
var 1player;
```

```js
// valid
var player1;
```

It is also not allowed to use language operators in the variable name, or use reserved words of language to name them.

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

Although symbols are allowed in variable names (_, $, @, entre outros), there are patterns of both Javascript, 
as tools that you probably will use. But in general, the patterns most important in Javascript is:

- name of variables in lower case
- if name is a compound name, example user address, use camel calse

The camel case consisting in to let the first letter of subsequent words (not the first) in upper case.

```js
// valid but not follow patterns
var user_height;
```

```js
// valid and following patterns
var userHeight;
```

Then, a last pattern to declare variables. If declare many at same time, the Javascript allow use commas, but not be the pattern.

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

Another thing, Javascript allow create variables without use the reserved word `var`, but has a series of problems with this.

```js
useName;
```

So, always use the word `var` to create your variables.