# Operators and Loops

## Question 1

**Which of the following is invalid JavaScript code, and would result in a syntax error?**

  1. let i; 
for (i = 0; i == 0 || i < 8; i++) {
  console.log(i);
}

  1. for (let i = 12; i > 0; i--) {
  console.log(i);
}

  1. for (let a = 0; a <= 2000; a = a * 2) {
  console.log(a)
}

  1. <ins>***for ( i = 1 to 5 ) {
  console.log(i);
}***</ins>

## Question 2

**Pick the optimal type of loop to utilize for each of the following use-cases.**

  1. Ensuring a user has entered a numeric value

     <ins>***A while loop***</ins>
     
  1. Restricting access until a correct password is entered
    
     <ins>***A while loop***</ins>

  1. Showing each of the products in a shopping cart
    
     <ins>***A for loop***</ins>
     
  1. Displaying all the books on a digital bookshelf
    
     <ins>***A for loop***</ins>

## Question 3

**Which code example is a correctly-written JavaScript `while` loop?**

  1. while a === 'house': a = askUserAgain();

  1. let a = '';
while{ a === '42' } (
  a = getNewInput();
)

  1. while(false); { log.console('looping!'); }

  1. <ins>***let answer = ''; 
while (answer !== 'S3kreT P455w0rD') {
  answer = prompt('Enter the passphrase to proceed...');
}***</ins>

## Question 4

**Which `for` loop will have the most iterations?**

  1. for (let i = 0; i <= 8; i=i+2) {
  console.log(i);
}

  1. <ins>***for (let i = 0; i <= 8; i++) {
  console.log(i);
}***</ins>

  1. for (let i = 1; i < 8; i++) {
  console.log(i);
}

  1. for (let i = 0; i < 8; i++) {
  console.log(i);
}

## Question 5

**Which `while` loop will have the most iterations?**

  1. let i = 0;
while( i < 10 ) {
  console.log(i);
  i++;
}

  1. let c = 'o';
while( c.length <= 20 ) {
  console.log( c );
  c = c + c;
}

  1. <ins>***let i = 0;
while( i <= 10 ) {
  console.log(i);
  i++;
}***</ins>

  1. let i = 0;
while( i <= 10 ) {
  console.log(i++);
  i++;
}
