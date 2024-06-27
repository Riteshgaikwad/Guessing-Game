# Guessing Game

A simple guessing game where users try to guess a random number between 1 and 100. The game provides feedback on whether the guess is too high or too low and keeps track of the number of guesses.

## Features

* Generates a random number between 1 and 100.
* Provides feedback to the user on their guess (higher, lower, or correct).
* Tracks the number of guesses made.
* Resets the game automatically after a correct guess.

## How to Play

1. Open the `index.html` file in a web browser.
2. Enter a number between 1 and 100 in the input field.
3. Click the "Guess" button.
4. The game will provide feedback on whether your guess is too high, too low, or correct.
5. The number of guesses will be displayed.
6. After a correct guess, the game will automatically reset after a short delay.

## Technologies Used

* HTML
* CSS
* JavaScript

## Installation

1. Clone or download the repository.
2. Open the `index.html` file in a web browser.

## Contributing

We encourage contributions to this project! Feel free to fork the repository and submit pull requests with your improvements.



## Author

* [Ritesh Gaikwad] ([https://github.com/Riteshgaikwad])



## Demo

[https://riteshgaikwad.github.io/Guessing-Game/]



## Code Snippets

Here are some relevant code snippets for reference:

**index.html** (Basic Structure)

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Guessing Game</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <script src="script.js"></script>
</body>
</html>


```

**script.js** (Example Logic)

```javascript
// Get references to DOM elements
let input = document.getElementById('input');
let btn = document.getElementById('btn');
let wrng = document.querySelector('.wrng');
let guesses = document.getElementById('guesses');

// Generate a random number
let answer = Math.floor(Math.random() * 100) + 1;

// Track number of guesses
let numGuesses = 0;

// Add event listener to button
btn.addEventListener("click", () => {
  // Handle guess logic here
});

```
***style.css***(Example style)

```CSS
body {
  /* Styles for the body element */
}

.container {
  /* Styles for the container element */
}

/* Add styles for other elements as needed */



