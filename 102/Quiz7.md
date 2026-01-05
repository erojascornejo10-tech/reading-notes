## Question 1

**Which code snippet(s) correctly defines a function in JavaScript?**

  1. <ins>***var helloWorld = function(name) {
  console.log('A new world awaits, ' + name);
}***</ins>

  1. function helloWorld{name} {
  console.log('A new world awaits, ' + name);
}

  1. function = var helloWorld (name) (
  console.log('A new world awaits, ' + name);
)

  1. <ins>***function helloWorld(name) {
  console.log('A new world awaits, ' + name);
}***</ins>

## Question 2

**What's the advantage of using functions in JavaScript?**

  * Functions make the code run much faster in the CPU

  * <ins>***Functions help us avoid repeated code.***</ins>

  * <ins>***A well-named function communicates clearly it's purpose.***</ins>

  * Using functions ensures our code has no errors in it.

  * <ins>***Functions make code reusable.***</ins>

  * <ins>***Functions let us define the code once, and then run the code wherever we need it.***</ins>

  * We can't use `if` statements without functions.

## Question 3

**Which of the below is the best explanation of what a function is, in JavaScript?**

  1.  <ins>***A reusable set of step-by-step instructions, potentially based on input, to potentially provide some output.***</ins>

  2.  A conditional set of code blocks that runs when certain logic statements evaluate to true.

  3.  All code in JavaScript is functions.

  4.  A way to programmatically access a previously assigned value.

  5.  A flow-control language construct to execute a code block a specific amount of times.

## Question 4

**Select all statements that are true about functions in JavaScript.**

  * <ins>***Declaring a function and invoking (or 'calling') a function need to happen separately.***</ins>

  * Functions are invoked by using curly braces.

  * <ins>***The code in a function is executed at the time the function is invoked.***</ins>

  * <ins>***Functions are invoked by using parenthesis.***</ins>

  * The code in a function is executed at the time the function is declared.

  * All functions are required to have a return statement in them. 

## Question 5

**What would most likely be the correct way to invoke the function defined here, in order to display a complete sandwich?**

let makeSandwich = function(bread, meat, cheese) {
  let sandwich = '';
  
  sandwich = sandwich + '<img src="' + bread + '.png">'; 
  sandwich = sandwich + '<img src="' + meat + '.png">'; 
  sandwich = sandwich + '<img src="' + cheese + '.png">'; 
  sandwich = sandwich + '<img src="' + bread + '.png">'; 
  
  return sandwich;
}

1. makeSandwich;

2. makeSandwich();

3. makeSandwich(cheese, meat, bread);

4. > sudo makeSandwich

5. <ins>***makeSandwich('rye', 'pastrami', 'provalone');***</ins>
 
