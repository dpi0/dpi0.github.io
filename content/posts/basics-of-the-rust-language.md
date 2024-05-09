+++
title = "basics of the rust language"
date = 2024-05-09
tags = [
    "dev",
    "rust"
]
+++

{{<toc>}}

## what is rust?

[rust](https://www.rust-lang.org/) is a systems programming language that focuses on safety, speed, and concurrency. it provides powerful memory safety guarantees without needing a garbage collector.

## installation

to get started with rust, you need to install it on your system. you can do this by visiting the [official rust website](https://www.rust-lang.org/tools/install) and following the instructions for your platform.

## creating your first rust program

let's create a simple "hello, world!" program in rust. create a file named `main.rs`:

```rust
// main.rs
fn main() {
    println!("Hello, world!");
}
```
compile and run your program:
```rust
rustc main.rs
./main
```
you should see hello, world! printed to the console.

## variables and data types

rust is a statically typed language, which means that you must declare the type of each variable. here's an example of declaring variables and their data types in rust:
```rust
// main.rs
fn main() {
    let x: i32 = 5; // integer
    let y: f64 = 3.14; // floating point number
    let z: bool = true; // boolean
    let greeting: &str = "Hello, Rust!"; // string slice

    println!("x: {}, y: {}, z: {}, greeting: {}", x, y, z, greeting);
}
```
## rust ecosystem

rust has a vibrant ecosystem with a growing number of libraries and tools. you can explore more about rust and its ecosystem in the official documentation.

## conclusion

congratulations! you've created your first rust program and learned about its basic syntax and features. rust's safety and performance make it an excellent choice for systems programming tasks. happy coding in rust!
