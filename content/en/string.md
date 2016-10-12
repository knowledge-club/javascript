## String

One type of variables that Javascript has is the String. 

String is the same as text. Technically, is an array of characters :D. 

To create strings, we use quotes or double quotes. See below:

```js
var phrase = 'You know nothing';
var username = "John"
```

Note, to *assign* a value to a variable, we use the `=` operator. 
Second, we create strings using quotes. In the above example, we use quotes and double quotes. While both are valid, in Javascript the code standard tells us that it is better to use only single quotes, so to fix the code above:

```js
// following standards, use single quotes
var phrase = 'You know nothing';
var username = 'John';
```

So much better!! Now we'll see how to work with these strings.

First, the username is wrong, it is John Snow. Then, to overwrite the value of a variable, just write the variable name again and assign a new value.

```js
username = 'John Snow';
```

Note, to assign another value for an existing variable, we only use the variable's name followed by the `=` operator and finally the value to be assigned, in our case, the string 'John Snow'. We use the keyword `var` only when creating, not when reading or setting a new value.

Next, lets print our variables to the console. The console is useful to test what we do. To show any variable in the console, you just need use the function `console.log`, i.e:

```js
console.log('Hello');
``` 

Between parentheses comes the value to be displayed. 

We will see more details about functions later on but, for now, know that `console.log` functions displays the variable value to the console.

So if we want to display the value of the variable username, use:

```js
console.log(username);
console.log(phrase);
```

Do not confuse, the quotes are meant to create a string, as our string has already been created, we can use their variable names to get their value.

We want to display the values of two variables at the same time, and there are two ways to do this. Let's look at the first.

This would be by what we call `concat`, which is nothing more than combining two or more strings into one. To concatenate strings, use the `+` operator in between the variables, eg:

```js
phrase + username;
```

However, the phrase and username variables continue to have distinct values, the above code only generates a new string containing both values concatenated together, without change the original ones.

But if we wish display on screen, we need to use `console.log`:

```js
console.log(phrase + username);
// displays 'You know nothingJohn Snow'
```

You may have noticed that the concatenated string has no spaces between the two parts. To display that in the right way, concatenate a string with space between them, like this:

```js
console.log(phrase + ' ' + username);
// now it's right, 'You know nothing John Snow';
```
