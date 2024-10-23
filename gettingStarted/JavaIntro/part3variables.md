
# Java Variables

Variables in Java are fundamental elements used for storing and managing data in your programs. They allow you to store values, such as numbers, text, or objects, so you can manipulate and work with them in your code. In this tutorial, we will cover the basics of Java variables, including how to declare, initialize, and use them.

### 1. Variable Declaration
In Java, variables must be declared before they can be used. The declaration specifies the variable's name and data type.

#### 1.1. Data Types
Java has several built-in data types that determine the kind of data a variable can hold. Here are some commonly used data types:

- `int`: Used for integer values (e.g., 42).
- `double`: Used for floating-point numbers with decimal points (e.g., 3.14).
- `boolean`: Used for true/false values (e.g., `true` or `false`).
- `char`: Used for single characters (e.g., 'A').
- `String`: Used for sequences of characters (e.g., "Hello, World!").

#### 1.2. Naming Conventions
- Variable names are case-sensitive (`myVariable` and `myvariable` are different).
- They can consist of letters, digits, underscores, and dollar signs.
- The first character must be a letter, underscore, or dollar sign.
- Variable names should be meaningful and follow a camelCase naming convention for readability. (As a reminder camelCase isWhen weLowercase the firstLetter, remove whiteSpace and uppercaseTheFollowingWords. CapitalCamelCase used for classes UppercasesEveryWord.)

### 2. Variable Initialization
Once you've declared a variable, you can initialize it, which means assigning an initial value to it. Think of a variable as a bucket and initializing it is putting something in your bucket. Variables can be initialized at the time of declaration or later in your code.

#### 2.1. Initializing Variables
```java
int age;                // Declaration without initialization
age = 25;               // Initialization later
double pi = 3.14159;    // Declaration and initialization in one step
```

#### 2.2. Default Values
Java assigns default values to variables if you don't explicitly initialize them. The default values depend on the data type. 

- `int`: 0
- `double`: 0.0
- `boolean`: false
- `char`: '\u0000' (null character)
- `String`: null (not an empty string)


When a variable contains "null," it signifies that there is no valid data or object associated with it. It's different from an empty string or a value of zero. it is simply the absence of any value.

### 3. Using Variables
You can use variables in various ways, such as performing calculations, displaying information, or making decisions in your code.

```java
int x = 5;
int y = 3;
int sum = x + y; // Adding x and y, storing the result in sum
System.out.println("The sum of x and y is: " + sum);
```

### 4. Example Programs
Let's look at some simple examples of using variables.

#### 4.1. Integer Variable
```java
public class IntegerVariableExample {
    public static void main(String[] args) {
        int age = 30;
        System.out.println("My age is: " + age);
    }
}
```

#### 4.2. String Variable
```java
public class StringVariableExample {
    public static void main(String[] args) {
        String greeting = "Hello, World!";
        System.out.println(greeting);
    }
}
```

### 5. Final Variables (Constants)
You can declare variables as `final` to make them constants, meaning their value cannot be changed once initialized.

```java
final double PI = 3.14159;
```

### 6. Scope of Variables
The scope of a variable defines where in your code it can be accessed. In Java, variables have block scope, which means they are only accessible within the block of code in which they are declared. typically denoted by the lowest level of curly brackets `{}` they are in.

### 7. Summary
In this Lesson, you've learned the basics of declaring, initializing, and using variables. These fundamental concepts are essential for building more complex programs in Java. Practice and experimentation are key to becoming proficient in working with variables in Java.

[Prev](part3.md) | [Up](part3.md) | [Next](part3escapeCharacters.md)