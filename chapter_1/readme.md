## Variables and constants

## Variables

- Two ways to define variables
    - let(modern and prefered way)
    - var(old way)

```js
let age = 24;
let year = 2020
```

console.log(age, year);

- variables can be overwritten

## Constants

```js
 console.log(age);

 const points = 100;

 console.log(points);

 var score = 75;
 ```
 - constants cannot be overwritten

 ## old way of defining variables

 ```js
 var name = 'aashiq';
```

 ## Rules for naming variables

- Variables names should not have spaces
- variables can contain letters, numbers, symbols
- variables should not begin with numbers
- variable names should not mirror any reserved keywords in javascript

 ## Strings

```js
 console.log('hello, world');

 let email = 'aashiqms@outlook.com';

 console.log(email)
 ```

## String concatenation

```js
let firstName = 'Brandon';
let lastName = 'Sanderson';

let fullName = firstName + '' + lastName;

console.log(fullName);
 ```

 ## getting strings

```js
 console.log(fullName[0]);
 ```

 ## String length(length is a property of string)

```js
console.log(fullName.length);
```
 ## String methods(toUpperCase is a method)

```js
 console.log(fullName.toUpperCase);
 ```

 ```js
 console.log(fullName.toLowerCase);
 ```

- some methods alter the original value of the variable
- some methods don't alter original value of the variable
- the above methods don't alter the original value of the variable

```js
 let index = email.indexOf('@');

 console.log(index);

 ```


## Strings

- **what is string**
    - These just all go inside quotes so strings are a series of letters numbers and characters in quotes.
- **String Properties**
    - They have properties like the length and we use dot notation to get those properties.
- **String Methods**
    - They also have methods which are the same kind of things as functions the built in snippets of code that  do things for us and we did note methods and call them by using these parentheses at the end of them.

## Common string methods

- So next I'd like to do a method called slice and slice does is essentially slice a section from the  string.

#### slice method

```js
result = email.slice(0, 5);
```

- start from index and slice until index 5

#### substr method

```js
let result = email.substr(4, 2);
```

- This method is similar to slice method except it also includes the last index

#### replace method

```js
let result = email.replace('m', 'w')
```

- The above method takes 'm' in email and replaces it with 'w'

```js
let result = email.replace('a', 'w')
```

- In the above code it will replace the first instance of the letter 'a'

## Numbers

```js
 let radius = 10;

 let pi = 3.14;

 let modu = radius % 3

 console.log(modu)

 let area = 3 * pi * radius ** 2

 console.log(area)
 ```

 ## Increment operator
 
 ```js
 let likes = 10;
 likes++;
 ```

 ## Decrement Operator

 ```js
 let likes = 10
;
likes--;
```

## short hand way to perform operations

```js
let likes += 10;
```
```js
let likes -= 10;
```
```js
let likes *= 10;
```
```js
let likes /= 10;
```

#### NaN - not a number

```js
 console.log(5 / 'hello')
 ```
 **output:** NaN

 #### Concatenating numbers with strings

 ```js
  let likes = 0;
 likes += 10;

 let out = 'the blog has ' + likes + ' likes'

 console.log(out)
 ```

 ## Template Strings
 
```js
const title = 'Best reads of 2019';
const author = 'Mario';
const likes = 30;
```

// concatenation way

// let result = 'The blog called ' + title + ' by ' + author + ' has ' + likes + ' likes';
// console.log(result);

### template string way

```js
 let result = `The blog called ${title} by ${author} has  {likes} likes`;
 console.log(result);
 ```

 - template string is created using back ticks
 - we use $ sign and curly braces similar to formated strings in python

 ### creating html templates using templates string
 ```js
let html = `
  <h2>${title}</h2>
  <p>By ${author}</p>
  <span>This blog has ${likes} likes</span>
`;

console.log(html);
```

## Arrays

- we use arrays for collection of things

```js
let ninjas = ['sjaun', 'ryu', 'chunli'];

ninjas[1] = 'kim';

console.log(ninjas[1]);
let ages = [20, 25, 30];

let random = ['shaun', 'crystal', 30, 20];

console.log(random);

```
### Array Methods

#### join method

```js
let result = ninjas.join('-')
```
```
output: shaun-crystal-chunli
```

### indexOf method

```js

let result = ninjas.indexOf('chunli');

```

```
output: 2
```

### concatenate array method

```js
let result = ninjas.concat(['ken', 'crystal']);
```
```
output: ['sjaun', 'ryu', 'chunli', 'ken', 'crystal']
```
### push Array method

```js
let result = ninjas.push('new-item')
```
### pop Array method

```js
result = ninjas.pop();
console.log(result);
```
```
output: new-item
```

- The last item added.

## Null and Undefined

- Undefined is automatically defined by javascript when value is not given

```js
let age;

console.log(age, age + 3, `the age is ${age}`);
```

- Null is explicitly defined by us

```js
let age = null;

console.log(age, age + 3, `the age is ${age}`);
```

## Booleans

```js
// booleans & comparisons
// console.log(true, false, 'true', 'false');

// methods can return booleans
// let email = 'luigi@thenetninja.co.uk';
// let names = ['mario', 'luigi', 'toad'];

// let result = email.includes('@');
// let result = names.includes('luigi');

// console.log(result);

// comparison operators
let age = 25;

console.log(age == 25);
console.log(age == 30);
console.log(age != 30);
console.log(age > 20);
console.log(age < 20);
console.log(age <= 25);
console.log(age >= 25);

let name = 'shaun';

console.log(name == 'shaun');
console.log(name == 'Shaun');
console.log(name > 'crystal');
console.log(name > 'Shaun');
console.log(name > 'Crystal');
```








