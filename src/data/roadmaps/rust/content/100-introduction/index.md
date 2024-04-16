# Introduction

Rust is a modern system programming language focused on performance, safety, and concurrency. It accomplishes these goals without having a garbage collector, making it a useful language for a number of use cases other languages aren’t good at. Its syntax is similar to C++, but Rust offers better memory safety while maintaining high performance.

# Basic Of Rust Programming

Here are some basic components and concepts in C++ programming:

## Main Function
```Rust
fn main()
{
//Your Code Goes Here
}
```

## Variables and Data Types
Rust is similiar to C++ that has several basic data types for representing:

- Integer: `i8, i16, i32, i64, u8, u16, u32, u64`: Integer Values
- Float: `f32, f64.`: single-precision floating-point values
- Boolean: `bool.`: double-precision floating-point values
- Char: `char`: single characters

First variables mus declared with `let` than the variables name for the data type compiler will specifes itself for you:

```Rust
let a: i32 = 0;
let b: bool = false;
let z: f32 = 1.4;
let c: char = 'a";
```

## Control Structures
Rust provides control structures for conditional exection iteraion, such as `if`, `else`, `while`, `for`, `loop`, and `match`

### If 
```Rust
fn main() {
    if (condition) {
    // Code to execute if the condition is true
    }
}
// If else condition
if condition {
    // code to execute if condition is true
} else {
    // code to execute if the condition is false
}
```

### If else
```Rust
while (condition) {   
    // Code to execute while the condition is true
}
```

### For
```Rust
for variable in range {
    // code to execute
}
```

### Loop
```Rust
loop {
    // code to execute
    if condition {
        break;
    }
}
```

### Match
```Rust
match value {
    pattern1 => {
        // code to execute if the value matches pattern1
    },
    pattern2 => {
        // code to execute if value matches pattern2
    },
    // etc.
}
```

## Functions

Functions in Rust are reusable blocks of code that can be called with arguments to perform specific tasks. A function in Rust is defined with its return type, a name, a parameter list, and a body.

```Rust
fn function_name(parameter1: ParameterType1, parameter2: ParameterType2) -> ReturnType {
    // Function body
    // ...
    return return_value;
}
```

For example, here's a function that adds two integers and returns the result:
```Rust
fn add(a: i32, b: i32) -> i32 {
    a + b
}

fn main() {
    let result = add(3, 4);
    println!("3 + 4 = {}", result);
}
```
This basic introduction to Rust should provide you with a solid foundation for further learning. Explore more topics such as structs, enums, traits, ownership, borrowing, generics, and the Rust Standard Library to deepen your understanding of Rust and start writing more advanced programs.

- [The Rust Programming Language](https://doc.rust-lang.org/book/)
- [Learn Rust Programming - Complete Course 🦀 by freeCodeCamp](https://youtu.be/BpPEoZW5IiY?si=lCfzx1uztuvJu54b)
