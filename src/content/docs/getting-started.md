---
title: Getting Started with NueScript
description: Learn the basics of NueScript and write your first program
---

# Getting Started with NueScript

Welcome to NueScript! This guide will help you get started with the language and write your first program.

## Installation

```bash
npm install -g nuescript
```

## Your First Program

Create a new file called `hello.nue`:

```nue
fn main() -> void {
  print("Hello, NueScript!")
}
```

Run your program:

```bash
nue run hello.nue
```

## Basic Concepts

### Variables

```nue
let name = "NueScript"
let version: number = 1.0
```

### Functions

```nue
fn greet(name: string) -> string {
  return "Hello, " + name + "!"
}
```

### Types

NueScript is statically typed:

```nue
type User = {
  id: number
  name: string
  email: string
}

let user: User = {
  id: 1,
  name: "John",
  email: "john@example.com"
}
```

## Next Steps

- [Explore the Syntax Guide](/docs/syntax)
- [Learn about the Type System](/docs/types)
- [Check out Examples](/docs/examples)