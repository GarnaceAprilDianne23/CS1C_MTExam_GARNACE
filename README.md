// favoriteNumberGuess.js

const favNumber = 7; // You can change this value as needed
let guess;

do {
    guess = parseInt(prompt("Guess my favorite number:"));

    if (guess > favNumber) {
        console.log("Too high! Try again.");
    } else if (guess < favNumber) {
        console.log("Too low! Try again.");
    } else {
        console.log("Correct! You guessed the favorite number.");
    }
} while (guess !== favNumber);
