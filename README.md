# Download Rust

To download Rust, follow the instructions here: [https://www.rust-lang.org/learn/get-started](https://www.rust-lang.org/learn/get-started)

# Cargo and RustUp

Cargo is the CLI to build rust projects, RustUp is an Windows installer that is needed to download rust and cargo.
You start by downloading Rust in the official website, in my case, I'm using Windows.

## Chapter 1: Hello Rust

Let's create a hello world in Rust

To start, you must have installed Cargo through RustUp.

# Start a new Rust Project with Cargo New

Then, you will execute the following command to start a project.

```sh
cargo new hello-rust
```

`new` is a command that generates a new project.
`hello-rust` is the name of the project.

# Why we need a cargo.toml file

Then, you will see that the src folder was created with a main.rs folder, and also, you will see a cargo.toml file. This file is basically a file that indicates the project status and version.

# Run the Hello World file!

cd to `hello-rust` folder and then execute the following command

```sh
cargo run
```

This will print `Hello, world!`
