# Dart hello world

The*main()*function:  
Every app must have a top-level main() function, which serves as the entrypoint to the app.  
the*main()*function returns void and has an optional List`<String>` parameter for arguments.  
```dart
void main(List args){ 
    // Dart entrypoint...
}
```

## Print hello world

To display output in dart we use print function.  
*Syntax:*  
``print( Object object );``  
*Description:*  
Prints a string representation of the object to the console.  
Every statement in dart must end with semicolon (;)

```dart
void main(List args){ 
    print("Hello world");
}
```

*Output:*  
``Hello world``