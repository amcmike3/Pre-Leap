# Numeric Data Types in Java

In Java, numeric data types are fundamental for working with numbers, whether they are whole numbers, decimal numbers, or even characters that represent numbers. Understanding numeric data types is crucial for performing mathematical operations and manipulating numerical values in your Java programs. In this tutorial, we will explore Java's numeric data types, including integers, floating-point numbers, and characters.


### 1. Numeric Data Types in Java
Java provides several numeric data types to represent different kinds of numerical values. These data types are categorized into three main groups:

#### 1.1. Integer Data Types
Java supports various integer data types, which store whole numbers without fractional parts. Here are some common integer data types:

- `byte`: 8-bit signed integer (-128 to 127)
- `short`: 16-bit signed integer (-32,768 to 32,767)
- `int`: 32-bit signed integer (-2^31 to 2^31-1)
- `long`: 64-bit signed integer (-2^63 to 2^63-1)

#### 1.2. Floating-Point Data Types
Floating-point data types are used to represent numbers with fractional parts or numbers with a decimal point. The two main floating-point data types in Java are:

- `float`: 32-bit single-precision floating-point (approx. 6-7 decimal places)
- `double`: 64-bit double-precision floating-point (approx. 15 decimal places)

#### 1.3. Character Data Type
While characters are not typical numeric values, they can represent numbers, such as Unicode code points. The character data type is:

- `char`: 16-bit Unicode character (0 to 65,535)

### 2. Declaring Numeric Variables
To use numeric data types in Java, you need to declare variables of the appropriate type. Here's how you declare numeric variables for each data type:

#### 2.1. Integer Variables
```java
byte smallNumber;
short mediumNumber;
int largeNumber;
long hugeNumber;
```

#### 2.2. Floating-Point Variables
```java
float floatValue;
double doubleValue;
```

#### 2.3. Character Variables
```java
char grade;
```

### 3. Literal Values
Literal values are constant values that are directly written in your code. You can use literals to assign initial values to numeric variables. Examples of literals for different data types:

```java
byte age = 25;
short population = 30000;
int distance = 1500;
long bigNumber = 12345678901234L; // Note the 'L' suffix for long literals
float temperature = 98.6f; // Note the 'f' suffix for float literals
double pi = 3.141592653589793;
char grade = 'A';
```

### 4. Numeric Operations
Numeric data types allow you to perform various mathematical operations such as addition, subtraction, multiplication, and division. We will explore these more in the next lesson Here are some examples:

```java
int x = 10;
int y = 5;
int sum = x + y;
int difference = x - y;
int product = x * y;
int quotient = x / y;
```

### 5. Summary
In this tutorial, we covered Java's numeric data types, including integers, floating-point numbers, and characters. Understanding these data types and how to declare variables, use literals, perform numeric operations, and handle type casting is essential for working with numerical values in Java programs. Use the appropriate data type for your specific needs to ensure accuracy and efficient memory usage in your applications.

[Prev](part4.md) | [Up](part4.md) | [Next](part4mathOperators.md)
