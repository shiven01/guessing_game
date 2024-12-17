# Rust Number Guessing Game

Welcome to my first Rust project! This is a simple command-line game where you try to guess a random number between 1 and 100. I created this while learning Rust to understand basic concepts like variables, loops, error handling, and user input.

## How the Game Works

When you run the game:
1. The program generates a random secret number between 1 and 100
2. You'll be prompted to input your guess
3. After each guess, the program will tell you if your guess was too big, too small, or exactly right
4. Keep guessing until you find the right number!

## Key Learning Points

Through this project, I learned several fundamental Rust concepts:

### Variables and Mutability
- Using `let` for variable declaration
- Understanding mutable variables with `mut`
- Type conversion (String to number) using `parse()`

### Error Handling
- Using `match` expressions to handle potential errors gracefully
- The `Result` type for handling success and failure cases
- Using `continue` to skip invalid inputs

### Control Flow
- `loop` for creating an infinite game loop
- `break` to exit the loop when the player wins
- Pattern matching with `match` for comparing numbers

### Standard Library Features
- Random number generation with `rand` crate
- Reading user input with `std::io`
- Comparing values with `std::cmp::Ordering`

## Running the Game

1. Make sure you have Rust installed on your system
2. Clone this repository
3. Navigate to the project directory
4. Run the game using:
```bash
cargo run
```

## License

This project is open source and available under the MIT License.
