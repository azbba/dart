# Dart Operators:

The operators are special symbols that are used to carry out certain operations on the operands.

## Assignment Operators

Assignment operators are used to assign value to a variable.

| Operator  | Description                 | Example                               |
|-----------|-----------------------------|---------------------------------------|
| =         | Assignment operator         | `age = 30;`                           |
| +=        | Add add assign              | `age += 5; // 30 + 5 = 35`            |
| -=        | Subtract and assign         | `age -= 5; // 30 -5 = 25`             |
| *=        | Multiply and assign         | `age *= 2; // 30 * 2 = 60`            |
| /=        | Divide and assign           | `age /= 2; // 30 / 2 = 15`            |
| ~/=       | Divide and assign (integer) | `age ~/= 7; // 30; 30 / 7 = 4.28 = 4` |
| %=        | Mod and assign              | `age %= 7: // 30 % 7 = 28 - 30 = 2`   |

## Arithmetic Operators:

Arithmetic Operators are used to perform arithmetic operations.

| Operator  | Description                       								      | Example               |
|-----------|-------------------------------------------------------------------------|-----------------------|
| +         | Addition                                                                | `5 + 5; // 5`         |
| -         | Subtraction         		                                              | `5 - 5; // 0`         |
| *         | Multiply                                                                | `5 * 5; // 25`        |
| /         | Division                                                                | `8 / 2; // 4`         |
| ~/        | Truncating division operator.(**Division and return an integer value**) | `8 ~/ 3; // 2.66 = 2` |
| %=        | Modulus                                                                 | `8 % 4: // 2 = 0`     |

## Comparison Operators

Comparison Operators are used evaluate a comparison between two operands.

| Operator  | Description              | Example              |
|-----------|--------------------------|----------------------|
| >         | Greater than             | `5 > 10; // false`   |
| <         | Less than                | `5 < 10; // true`    |
| >=        | Greater than or equal to | `10 >= 10; // true`  |
| <=        | Less than or equal to    | `10 <= 10; // true`  |
| ==        | Is equal to              | `10 == 5; // false`  |
| !=        | Is not equal to          | `10 != 5; // true`   |

## Logical operators

Logical operators are used to combine expressions with conditional statements using logical (AND,OR,NOT) operators.

| Operator  | Description                                 | Example                    |
|-----------|---------------------------------------------|----------------------------|
| &&        | Logical AND (**Return true if all**)        | `5 == 5 && 5 > 3; // true` |
| `||`      | Logical OR (**return true if any is true**) | `5 == 5 || 1 > 3; // true` |
| !         | Logical NOT                                 | `10 != 10; // false`  	   |