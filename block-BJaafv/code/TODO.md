1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}
a+b is returned when sum is called;
// second
function sum(a, b) {
  console.log(a + b);
}
```
in console a+b will be shown;
2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
first = a + b value; second = no value;
3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
output : 36
4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
delare the variable add.and store sum inside it.

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
function sayello(name){
  return `hello ${name};
}
sayhello('arya');
6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
hello john;
7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1
alert(john)
showMessage(); // Output 2
hello john;
alert(userName); // Output 3
alert(john)

8. What is a Anonymous Function give example of three functions.
anonymous function is a function that was declared without any named identifier to refer to it.

let far = function (a, b) {
  retrun a + b
}
9. Can function declaration be a Anonymous Function? Explain
An anonymous function is a function that was declared without any named identifier to refer to it. ... function hello() { alert('Hello world'); } hello(); Anonymous function definition: var anon = function() { alert('I am anonymous'); } anon(); One common use for anonymous functions is as arguments to other functions.
10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
