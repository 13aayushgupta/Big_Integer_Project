# BigInt - Arbitrary Precision Integer Arithmetic in C++

This project implements a `BigInt` class in C++ that supports arbitrary precision integer arithmetic. It allows you to perform mathematical operations on integers of virtually unlimited size, beyond the limits of standard C++ integer types like `int`, `long`, or `long long`.

---

## Features

- Representation of large integers as digit strings (stored in reverse for easy arithmetic)
- Arithmetic operations:
  - Addition `+`
  - Subtraction `-`
  - Multiplication `*`
  - Division `/`
  - Modulo `%`
  - Power `^`
- Increment and decrement: `++`, `--` (both prefix and postfix)
- Comparison operators: `==`, `!=`, `<`, `>`, `<=`, `>=`
- Utility functions:
  - `Length()` – returns number of digits
  - `Null()` – checks if value is 0
  - `sqrt()` – computes square root (integer)
  - `NthFibonacci()` – computes nth Fibonacci number
  - `Factorial()` – computes factorial
  - `NthCatalan()` – computes nth Catalan number
- Stream input/output: `cin`, `cout` overloading
- Safe exception handling for invalid inputs or overflows

---

## How It Works

The number is stored internally as a `std::string` of digits in reverse order (`digits[0]` is the least significant digit). This makes arithmetic operations like addition and multiplication easier to implement similarly to manual pen-and-paper methods.