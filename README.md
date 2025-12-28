# Guessing Game

A classic number guessing game built with Rust.

## How It Works

1. The program generates a random integer between 1 and 100
2. You enter a guess
3. The program tells you if your guess is too high or too low
4. Keep guessing until you find the correct number!

## Features

- Random number generation using the `rand` crate
- Input validation (non-numeric inputs are handled gracefully)
- Continuous gameplay until you win

## Requirements

- Rust (1.70+)

## Running the Game

```bash
cargo run
```

## Example

```
Guess the number!
---- Please input your guess:
50
You guessed: 50
Too big!
---- Please input your guess:
25
You guessed: 25
Too small!
---- Please input your guess:
37
You guessed: 37
You win!
```
