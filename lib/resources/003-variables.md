# Dart Variables:

Variables is an identifier used to refer memory location in computer memory that holds a value for that variable.  
This value can be changed during the execution of the program.  

## Declaring Variables In Dart:

Variables are declared using the `[ var]` keyword followed by variable name that you want to declare.  

```dart
var firstName = "AzBba";
``` 

## Variable Naming Rules in Dart:

1. Variable name can consist of letter and alphabets.
2. Keywords are not allowed to use as a variable name.
3. Blank spaces are not allowed in variable name.
4. First character of variable should always be alphabet `[A-Za-z]` or underscore `[ _ ]`  or dollar sign `[ $ ]`, and cannot be digit `[0-9]`.
5. Variable name are case sensitive: `name` is not `NAME`.
6. Special characters like `#`, `$` are not allowed except the underscore `(_)` and the dollar `($)` sign.
7. In Dart you cannot declare two variables with the same name in the same scope.
8. Variables must be declared before they are used.

## Type Annotations:

You can optionally provide a type annotation while declaring a variable to suggest type of the value variable can hold, by prefixing the variable name with the data type ensures that a variable holds only data specific to a data type.  

```dart
String firstName = "AzBba";
int age = 30;
``` 

## Dynamic variables:

This is a special variable initialised with keyword `[ dynamic ]` or `[ var ]`.

1. `[ var ]: ` Can't change type of variable, can change value with the same data type of initialisation.
2. `[ dynamic ]:` Can change type of variable, can change value with other datatype.

```dart
var foo = "AzBba";
// foo = 30; // ERROR => Cannot change the data type to another data type after you initialise.
``` 

```dart
dynamic bar = "AzBba";
bar = 30; // You can change the data type to another type when you using [ dynamic ] keyword
print(bar.runtimeType); // int
``` 