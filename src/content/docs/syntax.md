---
title: NueScript Syntax Guide
description: Learn the basic syntax and language constructs of NueScript
---

# Syntax Guide

## Basic Types

```nue
let num: number = 42
let str: string = "Hello"
let bool: boolean = true
```

## Functions

```nue
fn greet(name: string) -> string {
  return `Hello, ${name}!`
}

// Arrow functions
let add = (a: number, b: number) -> number => a + b
```

## Pattern Matching

```nue
match value {
  | Some(x) => print(x)
  | None => print("No value")
}
```

## Type System

```nue
type User = {
  id: number
  name: string
  email: string
}

type Result<T, E> = Ok(T) | Err(E)
```

## Modules

```nue
import { useState } from "@nuescript/state"
export type { User } from "./types"
```