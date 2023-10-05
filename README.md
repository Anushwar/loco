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
`hash`.2

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

> Note: The let statements can also be used to bind functions to names.

## Arithmetic Expressions

```sh
>> let a = 10;
>> let b = 20;
>> (a + b) / 2 - 3
12
```

## Conditional Expressions

```sh
>> let a = 10
>> let b = a * 2
>> let c = if (b > a) { true } else { false }
>> c
true

>> if (true) { 10 } else { 20 }
10
```

> Note: Loco does not support else-ifs (Bummer! I know, I just wanted to implement the basic if-else).

## Operators

Loco supports two type of operators: Prefix and Infix operators.

```sh
>> 1 + 2 + (3 * 4) - (10 / 5);
13

>> false != true
true

>> 500 / 2 != 250
false

>> !true;
false

>> !false;
true

>> let a = -10;
-10

>> !-5;
false

>> -true
null

>> !!!!-5
true

>> "Hello" + " " + "World";
Hello World
```
