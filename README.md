# PLUCK

A lightweight interpreted scripting language written in Python.

PLUCK is an experimental programming language focused on readability, simplicity, and learning how languages work internally.

---

## Current Features

- Variables
- Arithmetic operations
- Functions
- Built-in functions
- Input / Output
- If / Elif / Else
- While loops
- For loops
- Boolean values
- Comparison operators
- Lists / Arrays
- List indexing
- List mutation
- Append support
- User-defined functions
- Comments

---

## Example

```pluck
numbers = @{1,2,3}@

numbers::append(4)

out(numbers)
```

Output:

```txt
[1, 2, 3, 4]
```

---

## Goals

PLUCK is being built to explore:

- lexer design
- parser construction
- AST generation
- interpreters
- runtime systems
- language tooling
- syntax design

Future plans include:

- modules/imports
- dictionaries/maps
- return statements
- proper scope system
- REPL
- package manager
- syntax highlighting
- standard library

---

## Project Structure

```txt
PLUCK/
│
├── pluck/
├── examples/
├── docs/
├── tests/
└── main.py
```

---

## Philosophy

PLUCK aims to stay:

- readable
- lightweight
- expressive
- beginner-friendly
- fun to experiment with

---

## Status

Currently in active development.

```txt
Version: v0.1.0
```

---

## Repository

Main project repository:

https://github.com/PluckScript/Pluck-Script

---

## Example Syntax

### Functions

```pluck
fn greet(name) {
    out("Hello", name)
}

greet("PLUCK")
```

### Conditionals

```pluck
if x >= 10 {
    out("large")
}
```

### Loops

```pluck
for i = 1; 5 {
    out(i)
}
```

---

## Why This Exists

PLUCK started as a personal project to learn how programming languages work internally by building one from scratch.

Over time it evolved into a larger long-term language project.

---
