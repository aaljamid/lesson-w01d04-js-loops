# Exercises: JavaScript loops

Paste your answers into this file.

<br>

## Print every number from 0 to 10

```
ANSWER HERE

for (let i= 0; i<=10; i++ ){
console.log(i);

};

}
```

<br>

## Print every number from 10 to 0

```
ANSWER HERE

for (let i= 10; i>0; i-- ){
console.log(i);

};
```

<br>

## Print every number from 4 to -16

```
ANSWER HERE

for (let i= 4; i >= -16 ; i-- ){
console.log(i);

};
```

<br>

## Print every fifth number from 8 to 41

```
ANSWER HERE

for (let i= 8; i < 41 ; i= i+5 ){
console.log(i);

};
```

<br>

# Exercises: JavaScript loops with array:

Paste your answers into this file.

1. Change all **odd** numbers to be those numbers multiplied by two:

```js
const numbers = [4, 9, 7, 2, 1, 8];

// your code here

for (let i = 0; i < 6; i++) {
  numbers[i] = numbers[i] * 2;

  console.log(numbers[i]);
}
console.log(numbers);

// => [4, 18, 14, 2, 2, 8]
```

2.  Create an array to hold your favorite colors. For each choice, log to the screen a string like: `My #1 choice is blue.`

```js
const numbers = ["black", "orange", "blue", "yellow"];

for (i = 0; i < numbers.length; i++) {
  console.log("My #" + i + " choice is " + numbers[i] + ".");
}
```

3.  Create an array of ages. Loop through and log only the ages that are over 21.

```js
const numbers = ["23", "24", "25", "26"];

for (i = 0; i < numbers.length; i++) {
  console.log("age #" + i + "  is " + numbers[i] + ".");
}
```

4.  Create an array to hold your top five choices of something (music, books, movies, whatever).

    - For each choice, log to the screen a string like: "My #1 choice is blue."
    - **Bonus:** Change it to log "My 1st choice, "My 2nd choice", "My 3rd choice", picking the right suffix for the number based on what it is.

```js
const choices = ["music", "books", "movies", "food", "coding", "water"];

for (i = 0; i < 5; i++) {
  console.log(
    "My choice number #" + (i += 1) + "  is " + choices[(i -= 1)] + "."
  );
}
```

## The classic Fizzbuzz Program

For every `number` between 1 and 100...

If the `number` is evenly divisible by 3, print "Fizz"

If the `number` is evenly divisible by 5, print "Buzz"

If the `number` is evenly divisible by 3 AND evenly divisible by 5, print "Fizzbuzz"

```js
ANSWER HERE

let options = ['Fizz','Buzz','Fizzbuzz' ]

for ( let i=0; i <= 100; i++){

  if (i % 3 === 0 ) {
console.log(options[0])


  }

  else if (i % 5 === 0 ) {
console.log(options[1])


  }

  if (i % 3 === 0 && i % 5 === 0  ) {
console.log(options[2])


  }

  else {
console.log(i);

  }


}






```

<br>

## The even/odd reporter

Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen (e.g. "2 is even").

```js
ANSWER HERE

let result = ['even', 'odd'];

for ( let i=0; i <= 20; i++){

  if (i % 2 === 0 ) {
console.log( i + ' is ' + result[0])


  }



  else {
console.log(i + ' is ' + result[1]);

  }


};





```

<br>

## Multiplication Tables

Write a for loop that will iterate from 0 to 10. For each iteration of the for loop, it will multiply the number by 9 and log the result (e.g. "2 \* 9 = 18").

Bonus: Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total).

```js
ANSWER HERE

for (let i=0; i<= 10; i++){

let total = i * 9;
  console.log( i + " x 9  = " + total )
}
```

<br>

## The Grade Assigner

Check the results for every value from 60 to 100 - so your log should show "For 89, you got a B. For 90, you got an A.", etc.

```js
ANSWER HERE

for (let i=60; i<=100; i++)

if ( i >= 90 && i <= 100){


  console.log('You got an A');
}

else if ( i >= 80 && i <= 89){


  console.log('You got an B');
}


else if ( i >= 70 && i <= 79){


  console.log('You got an C');
}

else {

  console.log('You got an D');


}


```
