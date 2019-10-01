# Week-3 What I learned..

## HRM - Year 14, 16 and 17

* Human Resource Machine is a challenging game. I like to make a mental flowcharts when attacking each level.

* Level 17 took me a while to figure out. I started by adding in INBOX, COPYFROM and JUMPS.

* When you detect two numbers that are the same, you'll jump up above the COPYFROM 4, and when you detect two numbers that are different, you'll jump up above the COPYFROM 5.

* Level 14 you get a new jump command: Jump if negative. This allows a jump if holding a number in hand to make it negative to outbox.

---

## Basic Functions

* A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().
* Makes it easy to separate your code.
* Run the same code whenever you need to without repeating yourself.
* Easily see what a bit of code is supposed to do.
* Figure out why it's not, in fact, doing that.

  1. let x = 3;

  function nameX() {
      x = x + 1;
  }

#### Creating a return

* When JavaScript reaches a return statement, the function will stop executing.

* If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

function myFunction(num) {
    return num + 'jesse';

---

## String Methods (Return of the String)

* All string methods return a new value. They do not change the original variable.

* String indexes are zero-based: The first character is in position 0, the second in 1, and so on.

1. function capitalize(str) {
    return str.toUpperCase();
}

2. function exclaim(str) {
    return str + '!';
}

---

## Degree Converter App

* Making simple apps. This is a great example and learning new code and tools looking forward to expanding on adding more functions.

#### Example of App:

function toFahrenheit(celsius){
    const fahrenheit = celsius * 9 / 5 + 32;
    console.log(fahrenheit);
  }
const userInput = process.argv[2];
toFahrenheit(userInput);

---
