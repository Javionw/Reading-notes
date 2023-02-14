# JS Loops

Loops are used in programming to repeat a set of instructions multiple times. In JavaScript, there are three types of loops:

for loop: A for loop is used when you know the number of times you want to repeat a block of code. It has three parts: initialization, condition, and iteration. Here's an example:

for (let i = 0; i < 5; i++) {
  console.log(i);
}

This will output the numbers 0 through 4 to the console.

while loop: A while loop is used when you don't know how many times you want to repeat a block of code. It continues to execute the block of code as long as the condition is true. Here's an example:

let i = 0;

while (i < 5) {
  console.log(i);
  i++;
}

This will output the numbers 0 through 4 to the console.

do-while loop: A do-while loop is similar to a while loop, but it executes the block of code at least once before checking the condition. Here's an example:

let i = 0;

do {
  console.log(i);
  i++;
} while (i < 5);

This will output the numbers 0 through 4 to the console.

In addition to these basic loop types, JavaScript also has some higher-level functions that can loop over arrays, such as forEach, map, and reduce. These can be very useful when working with arrays of data.