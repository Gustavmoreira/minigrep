# Minigrep

This project is a simple implementation of a text search tool, inspired by the `grep` command-line utility.  
It was created as part of learning exercises from [The Rust Programming Language Book](https://doc.rust-lang.org/book/), Chapter 12.

## Features

- Search for a query string in a file.
- Case-sensitive and case-insensitive search options.
- Basic command-line argument parsing.

## Usage

```bash
# Basic usage
cargo run -- <query> <filename>

# Case-insensitive search
CASE_INSENSITIVE=1 cargo run -- <query> <filename>

