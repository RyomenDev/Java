## ✅ 1. Variables

A variable is a container that holds data that can be changed during program execution.

Syntax:

```java
datatype variableName = value;
```

Example:

```java
int age = 20;
String name = "Alice";
```

## ✅ 2. Data Types

Java is statically typed, so you must declare the type of a variable.

### 🔹 Primitive Data Types:

| Type      | Description      | Example                     |
| --------- | ---------------- | --------------------------- |
| `int`     | Integer numbers  | `int age = 25;`             |
| `double`  | Decimal numbers  | `double pi = 3.14;`         |
| `char`    | Single character | `char grade = 'A';`         |
| `boolean` | True or false    | `boolean isJavaFun = true;` |

### 🔹 Non-Primitive Types:

| Type                                            | Description       | Example                |
| ----------------------------------------------- | ----------------- | ---------------------- |
| `String`                                        | Sequence of chars | `String name = "Bob";` |
| Arrays, Classes, Interfaces (used later in OOP) |                   |                        |

## ✅ 3. Operators

### 🔸 Arithmetic Operators

Used to perform basic math operations.
| Operator | Description | Example |
| -------- | ------------------- | ------- |
| `+` | Addition | `a + b` |
| `-` | Subtraction | `a - b` |
| `*` | Multiplication | `a * b` |
| `/` | Division | `a / b` |
| `%` | Modulus (remainder) | `a % b` |

```java
int sum = 10 + 5;
int product = 4 * 2;
```

🔸 Relational / Comparison Operators
Compare two values.

| Operator | Meaning          | Example  |
| -------- | ---------------- | -------- |
| `==`     | Equal to         | `a == b` |
| `!=`     | Not equal to     | `a != b` |
| `>`      | Greater than     | `a > b`  |
| `<`      | Less than        | `a < b`  |
| `>=`     | Greater or equal | `a >= b` |
| `<=`     | Less or equal    | `a <= b` |

🔸 Logical Operators
Combine boolean expressions.
| Operator | Description | Example | | | | |
| -------- | ----------- | ----------------- | ---------- | ------- | - | -------- |
| `&&` | Logical AND | `a > 5 && b < 10` | | | | |
| \` | | \` | Logical OR | \`a > 5 | | b < 10\` |
| `!` | Logical NOT | `!(a > b)` | | | | |
