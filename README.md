# Loco

An interpreted, dynamically typed general purpose programming language written in [Go](https://go.dev/).

`Note: The documentation of loco is currently WIP and will be available soon.`

## About Loco

Expressed as a list of features, Loco has the following:

- C-like syntax
- Variable bindings
- Integers and Booleans
- Arithmetic expressions
- Built-in functions
- First-class and Higher-Order Functions
- Closures
- Data Structures like string, array and hash.

## Types

Loco supports the following data types: `null`, `bool`, `int`, `str`, `array`,
`hash`.

| Type  | Syntax                         |
| ----- | ------------------------------ |
| null  | `null`                         |
| bool  | `true false`                   |
| int   | `0 11 -10`                     |
| str   | `"hello my string"`            |
| array | `[] [1, 2] [1, 2, 3]`          |
| hash  | `{} {"a": 1} {"a": 1, "b": 2}` |
| float | `1.6 321.16`                   |

## Variable Bindings

Here's how we can bind values in loco.

> You can use 'let (var) = (expression)'

```sh
>> let age = 1;
>> let name = "Loco";
```

## Arithmetic Expressions

```sh
>> let a = 10;
>> let b = 20;
>> (a + b) / 2 - 3
12
```
