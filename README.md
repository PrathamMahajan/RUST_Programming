# Rust Coding Practice

Welcome to the Rust Coding Practice repository! This collection of coding questions is designed to help you practice and improve your Rust programming skills. Each question is practical and requires you to write code to solve it.

---

## Table of Contents

1. [Basic Rust Coding Questions](#basic-rust-coding-questions)
2. [Intermediate Rust Coding Questions](#intermediate-rust-coding-questions)
3. [Advanced Rust Coding Questions](#advanced-rust-coding-questions)

---

## Basic Rust Coding Questions

1. **Hello, World!**
   - Write a Rust program that prints `"Hello, World!"` to the console.

2. **Variables and Mutability**
   - Declare an immutable variable `x` with the value `10` and print it.
   - Then, declare a mutable variable `y` with the value `5`, update it to `15`, and print it.

3. **Basic Math Operations**
   - Write a program that takes two numbers as input, adds them, and prints the result.

4. **String Manipulation**
   - Create a `String` variable with the value `"Rust"` and append `" is awesome!"` to it. Print the final string.

5. **Conditional Statements**
   - Write a program that checks if a number is even or odd and prints the result.

6. **Loops**
   - Write a program that prints numbers from `1` to `10` using a `for` loop.

7. **Functions**
   - Write a function `add` that takes two integers as arguments and returns their sum. Call the function and print the result.

8. **Arrays**
   - Create an array of 5 integers, iterate over it, and print each element.

9. **Vectors**
   - Create a vector of strings, add 3 elements to it, and print all elements.

10. **Tuples**
    - Create a tuple containing an integer, a float, and a string. Print each element of the tuple.

---

## Intermediate Rust Coding Questions

11. **Ownership and Borrowing**
    - Write a function that takes a `String` as an argument, prints it, and returns it without transferring ownership.

12. **Slices**
    - Write a function that takes a slice of integers and returns the sum of all elements.

13. **Structs**
    - Define a `Person` struct with fields `name` (String) and `age` (u8). Create an instance of `Person` and print its fields.

14. **Enums**
    - Define an enum `Direction` with variants `North`, `South`, `East`, and `West`. Write a function that takes a `Direction` and prints a message based on the variant.

15. **Pattern Matching**
    - Use a `match` statement to handle an `Option<i32>`. Print `"Some(value)"` if the value exists, and `"None"` if it doesn't.

16. **Error Handling**
    - Write a function that divides two numbers and returns a `Result<f64, String>`. Handle the case where the denominator is zero.

17. **Closures**
    - Write a closure that takes two integers and returns their sum. Call the closure and print the result.

18. **Iterators**
    - Use an iterator to filter out even numbers from a vector of integers and print the result.

19. **HashMap**
    - Create a `HashMap` with keys as strings and values as integers. Insert 3 key-value pairs and print the map.

20. **File I/O**
    - Write a program that reads a file and prints its contents to the console.

---

## Advanced Rust Coding Questions

21. **Traits**
    - Define a trait `Shape` with a method `area()`. Implement the trait for a `Circle` struct and calculate its area.

22. **Generics**
    - Write a generic function `find_largest` that takes a slice of any type that implements the `PartialOrd` trait and returns the largest element.

23. **Lifetimes**
    - Write a function that takes two string references with the same lifetime and returns the longer one.

24. **Smart Pointers**
    - Use `Box` to create a recursive data structure (e.g., a linked list).

25. **Concurrency**
    - Write a program that spawns two threads, each printing a message, and waits for them to finish.

26. **Macros**
    - Create a custom macro `print_message!` that prints a given message to the console.

27. **Modules**
    - Organize your code into modules. Create a module `math` with a function `add` and call it from the main program.

28. **Testing**
    - Write a unit test for a function that adds two numbers.

29. **Custom Error Types**
    - Define a custom error type and use it in a function that returns a `Result`.

30. **Serde (Serialization/Deserialization)**
    - Use the `serde` crate to serialize a struct to JSON and deserialize it back.

---

## How to Use This Repository

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/rust-coding-practice.git
