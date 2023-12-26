# Rust

## Table of Content
1. [Overview](#overview)
2. [History](#history)
3. [References](#references)
4. [Tutorial](#tutorial)

## Overview
- Programming languages like C and C++ are very fast because they support developer to direct work with Memory(RAM). This provides speed but causes a different problem like memory management bugs, data races, and other common issues. 
- If programmers accidentally forget to erase memory usage, then system will lead to crash of the program or provide data to hackers to steal the data.
- To avoid this, In the 90's, a new league of programming languages were born like Java, JavaScript, and Python that solved memory management issue by using `garbage collectors`. This lead to lack of fine grained control & additional overhead to reduce the speed.
- Rust solved this problem by creating programming Rules/Constructs instead of adding overhead like GC. Your code would be harder to write, but it’d be `memory safe` no fears that you’d accidentally inserted lethal memory bugs. It removed GC in 2012. 
- Many of the tricks Rust employed weren’t new ideas: “They’re mostly decades-old research,” says `Manish Goregaokar`, who runs Rust’s developer-­tools team and worked for Mozilla in those early years. 
- The chat platform `Discord` used Rust to speed up its system, `Dropbox` uses it to sync files to your computer, and `Cloudflare` uses it to process more than 20% of all internet traffic, `Meta` used Rust to redesign software that its programmers use to manage their internal source code.
- Rust developers reffered as `Rustaceans`.

## History
- It was born out of the frustration of dealing with memory management of languages such as C and C++.
- Rust grew out of a personal project begun in `2006` by `Mozilla Research employee Steven Klabnik and Graydon Hoare`.
- Mozilla began sponsoring the project in `2009` as a part of the ongoing development of an experimental browser engine called `Servo`, which was officially announced by `Mozilla in 2010`.
- Its `first stable release` being made available to the public in `2015`.

## Reference
- [rust-lang](https://www.rust-lang.org/)
- [Github rust-lang](https://github.com/rust-lang)

## Tutorial
- [Rust Programming - FreeCodeCamp](https://www.youtube.com/watch?v=BpPEoZW5IiY)