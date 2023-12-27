# Rust

## Table of Content
1. [Overview](#overview)
2. [History](#history)
3. [Installation](#installation)
4. [References](#references)
5. [Tutorial](#tutorial)

## Overview
- Programming languages like C and C++ are very fast because they support developers to direct work with Memory(RAM). This provides speed but causes a different problem like memory management bugs, data races, and other common issues. 
- If programmers accidentally forget to erase memory usage, then the system will lead to a crash of the program or provide data to hackers to steal the data.
- To avoid this, In the 90's, a new league of programming languages were born like Java, JavaScript, and Python that solved memory management issues by using `garbage collectors`. This led to a lack of fine-grained control & additional overhead to reduce the speed.
- Rust solved this problem by creating programming Rules/Constructs instead of adding overhead like GC. Your code would be harder to write, but it’d be `memory safe` with no fears that you’d accidentally inserted lethal memory bugs. It removed GC in 2012. 
- Many of the tricks Rust employed weren’t new ideas: “They’re mostly decades-old research,” says `Manish Goregaokar`, who runs Rust’s developer-­tools team and worked for Mozilla in those early years. 
- The chat platform `Discord` uses Rust to speed up its system, `Dropbox` uses it to sync files to your computer, `Cloudflare` uses it to process more than 20% of all internet traffic, `Meta` uses Rust to redesign software that its programmers use to manage their internal source code, `Microsoft` is rewriting core Windows libraries in Rust, `Amazon Web Services (AWS)` had used Rust for Firecracker, the open-source virtualization behind AWS Lambda, `Google` in Android 12 announced support for the Rust as a memory-safe alternative to C/C++, Rust support was added in `Linux` Kernel from 6.1.
- Rust developers are referred to as `Rustaceans`.

## History
- It was born out of the frustration of dealing with memory management of languages such as C and C++.
- Rust grew out of a personal project begun in `2006` by `Mozilla Research employees Steven Klabnik and Graydon Hoare`.
- Mozilla began sponsoring the project in `2009` as a part of the ongoing development of an experimental browser engine called `Servo`, which was officially announced by `Mozilla in 2010`.
- Its `first stable release` was made available to the public in `2015`.
- An independent organization `Rust Foundation` was found on `08 Feb 2021` with board of directors from different companies. Details available [here](https://foundation.rust-lang.org/news/2021-02-08-hello-world/)

## Installation
- Windows installer available [here](https://www.rust-lang.org/tools/install)
- For Linux
  ```bash
  curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
  ``` 
- Verification
  ```bash
  # Compiler
  rustc --version
  rustup update
  rustup self uninstall
  
  # Cargo is Rust’s build system and package manager
  cargo --version
  cargo new project_name
  cargo build
  cargo run
  cargo check
  ```

## Reference
- [Rust Lang](https://www.rust-lang.org/)
- [Github rust-lang](https://github.com/rust-lang)
- [Foundation](https://foundation.rust-lang.org/)
- [Package Registry - crates.io](https://crates.io/)

## Tutorial
- [Rust Programming - FreeCodeCamp](https://www.youtube.com/watch?v=BpPEoZW5IiY)
- [Rust Book](https://doc.rust-lang.org/book/ch01-01-installation.html)
- [Rust Examples](https://github.com/rust-lang/rustlings/)