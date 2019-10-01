# Week-3 What I learned..

## HRM - Year 14, 16 and 17

* Level 17 took me a while to figure out. I started by adding in INBOX, COPYFROM and JUMPS.

* When you detect two numbers that are the same, you'll jump up above the COPYFROM 4, and when you detect two numbers that are different, you'll jump up above the COPYFROM 5.

* Level 14 you get a new jump command: Jump if negative. This allows a jump if holding a number in hand to make it negative to outbox.

---

## String Methods (Return of the String)

1. function capitalize(str) {
    return str.toUpperCase();
}

2. function exclaim(str) {
    return str + '!';
}

---

## Basic Functions

* Every part of your code should have one job! That makes it easy to separate your code, so you can:
* Run the same code whenever you need to without repeating yourself.
* Easily see what a bit of code is supposed to do.
* Figure out why it's not, in fact, doing that.

let x = 3;

function nameX() {
    x = x + 1;
}

#### Creating a call

let x = 3;

function nameX() {
    x = x + 1;
}
//Multiple Calls
nameX();
nameX();
nameX();

---

## Degree Converter App

* Making simple apps. This is a great example and learning new code and tools looking forward to expanding on adding more functions.

#### Example of App:

1. function toFahrenheit(celsius){
    const fahrenheit = celsius * 9 / 5 + 32;
    console.log(fahrenheit);
}
const userInput = process.argv[2];
toFahrenheit(userInput);


---
