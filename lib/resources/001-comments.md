# Dart Comments:

Dart provides three kinds of comments:

1.  Single line comment
2.  Multi-line Comments
3.  Documentation Comments

## Single line comment

We can apply comments on a single line by using the // (double-slash). 
```dart
void main(List args){ 
    // Single line comment 
}
```

## Multi-line Comments

We can apply comments on multiple lines by using the `/* ... */`.  
```dart
void main(List args){ 
    /**
     * Multi
     * line
     * Comments
    */
}
```

## Documentation Comments

The document comments are used to generate documentation or reference for a project/software package.  
It can be a single-line or multi-line comment that starts with `///` or `/*`
```dart
void main(List args){ 
    /// This Function do bla bla
    /// * @param String name
    /// * @return String sanitizedName

    /**
     * This is the second way to create document comments
    */
}
```

## Why we use comments

1. Comments make your code more readable and understandable to others and yourself.
2. Comments are helpful when debug or edit your code later.
3. Comments give you a brief idea of code that what is happening in the code. 
4. Comments give you the ability to stop code from execution.