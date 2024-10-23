# Tutorial: Methods in Java with Code Examples

Methods are a fundamental building block of Java programming, allowing you to encapsulate reusable blocks of code. In this tutorial, we will explore the concept of methods in Java, their syntax, how to define and call them, and provide code examples to illustrate their usage.

## 1. Introduction to Methods

### 1.1 What is a Method?
A method in Java is a block of code that performs a specific task or operation. Methods are used to modularize code by breaking it into smaller, more manageable pieces. Each method has a name and can be called to execute its code.

### 1.2 Advantages of Using Methods
- **Code Reusability:** Methods allow you to write code once and reuse it multiple times in your program.
- **Modularity:** Methods promote a modular code structure, making it easier to understand, maintain, and debug.
- **Abstraction:** Methods hide the implementation details and provide an abstract interface for using functionality.

## 2. Method Syntax

### 2.1 Method Declaration
A method declaration consists of the following components:
```java
accessModifier returnType methodName(parameters) {
    // Method body
}

public static void print(String printMe) {
    System.out.println(printMe);
}
```
- **Access Modifier:** Specifies the visibility of the method (e.g., `public`, `private`, `protected`, or package-private (More on this later)). 
- **Return Type:** Specifies the type of data the method returns (use `void` for methods that don't return a value).
- **Method Name:** The name of the method.
- **Parameters:** Input values passed to the method (optional).

### 2.2 Method Parameters
Parameters are values passed into a method when it is called. They act as placeholders for data that the method operates on.

### 2.3 Method Return Type
The return type specifies the type of data that the method will return. If a method doesn't return anything, you use the `void` keyword.

### 2.4 Method Body
The method body contains the code that defines what the method does when called. It is enclosed within curly braces `{}`.

## 3. Defining and Calling Methods
 In the example below we defined a method called sayHello().
Each time we call the mthod sayHello() all the code defined within it will be executed. In this case we called the method three times so we should see Hello, World! printed 3 times.
### 3.1 Calling Methods
```java
public class Main {
    public static void main(String[] args) {
        // Calling the method
        sayHello();
        sayHello();
        sayHello();
    }
    public static void sayHello() {
        // Method body
        System.out.println("Hello, World!");
    }
}
```
output:

```plaintext
    Hello, World!
    Hello, World!
    Hello, World!
```

## 4. Method Examples

### 4.1 Simple Method
```java
public class Greeting {
    public static void sayHello() {
        System.out.println("Hello, World!");
    }

    public static void main(String[] args) {
        sayHello();
    }
}
```

### 4.2 Method with Parameters
```java
public class Calculator {
    public static int add(int a, int b) {
        return a + b;
    }

    public static void main(String[] args) {
        int sum = add(5, 3);
        System.out.println("Sum: " + sum);
    }
}
```

### 4.3 Method with Return Value
```java
public class Square {
    public static int calculateSquare(int number) {
        return number * number;
    }

    public static void main(String[] args) {
        int result = calculateSquare(4);
        System.out.println("Square: " + result);
    }
}
```


## 5. Common Pitfalls and Best Practices

### 5.1 Naming Conventions
Follow Java naming conventions when naming methods. Use descriptive and meaningful names that indicate the purpose of the method.

### 5.2 Method Documentation
Consider adding comments or documentation to describe the purpose of the method, its parameters, and return values to make the code more understandable.

### 5.3 Avoiding Nested Methods
Avoid defining methods within methods (nested methods). Instead, keep methods at the class level for better code organization and readability.

By understanding methods in Java, you can effectively structure your code, improve code reusability, and create more maintainable and modular programs.


[Prev](part9.md) | [Up](part9.md) | [Next](part9labs1.md)