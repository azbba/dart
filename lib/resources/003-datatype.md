# Dart Data Types:

To get data type of variable we use: `[ variable.runtimeType ]`. 

**Example:**

```dart
var age = 30;
print(age.runtimeType); // int
```

### 1- String:

A string variable is used to hold series or sequence of characters – letters, numbers, and special characters.  
String can be represented either using single quotes `[ '' ]` or double quotes `[ "" ]`.  
Strings can be declared using the `String` keyword  

**Example:**

```dart
String name = "AzBba";
print(name.runtimeType); // String
print(name); // AzBba
```

### 2- int:

Integers are used to store whole numbers.  
An integer data type is used to represent 64 bit non-decimal number between -263 to 263 – 1.  
An integer can be used to store either signed and unsigned integer value.  
Integers can be declared using `int` keyword.  

**Example:**

```dart
int age = 30;
print(age.runtimeType); // int
print(age); // 30
```

### 3- double:

Double is used to represent a 64-bit (double-precision) floating-point numbers or numbers with larger decimal points.  
Double can be declared using `double` keyword.  

**Example:**

```dart
double prix = 15.86;
print(prix.runtimeType); // double
print(prix); // 15.86
```

### 4- bool (Boolean)

The Boolean data type is used to represent the truth values.  
which can be either `true` or `false`.  
You cannot use `0` or `1` to represent `true` or `false`.  
Boolean can be declared using `bool` keyword. 

**Example:** 

```dart
bool appStatus = true;
print(appStatus.runtimeType); // bool
print(appStatus); // true
```

### 5- list:

List data type is used to represent a collection of objects.  
A List is an ordered group of objects.  
The List data type in Dart is synonymous to the concept of an `array` in other programming languages.  
An array is used to hold multiple values in single variable.  
A list variable is defined by having values separated by commas `,` and enclosed within square brackets `( [] )`.  

**Example:** 

```dart
List languages = ["dart", "Flutter", "HTML", "CSS", "JavaScript", "PHP", "MySQL"];
print(languages.runtimeType); // List
print(languages); // ["dart", "Flutter", "HTML", "CSS", "JavaScript", "PHP", "MySQL"]
```

### 6- Set:

A set in Dart is an unordered collection of unique items.  
Two elements in a set cannot be equal.  
Dart support for sets is provided by set literals and the Set type.  

**Example:** 

```dart
Set fruits = {"apple", "apricot", "avocado", "banana"};
print(languages.runtimeType); // Set
print(languages); // {"apple", "apricot", "avocado", "banana"}
```

### 7- Map:

The Map is an object that is used to represents a set of values as key-value pairs.  
Both keys and values can be of any type of object.  
In Map, each key can only occurs once, but the same value can be used multiple times.  
The Map can be defined by using curly braces `{}`.  
and values can be assigned and accessed using square braces `[]`.  

**Example:** 
```dart
Map userInfo = {
    "username": "AzBba",
    "email":    "az34bba@gmail.com",
    "age":      30,
    "status":   true
};
print(userInfo.runtimeType); // Map
print(userInfo); // {username: AzBba, email: az34bba@gmail.com, age: 30, status: true}
print(userInfo["name"]); // AzBba
```