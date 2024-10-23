# Java Mathematical Operators, Precedence, and Unexpected Results with Double Data Type

In Java, mathematical operators allow you to perform various arithmetic operations on numerical data. Understanding how these operators work, their precedence, and potential issues related to the `double` data type is essential for writing robust and accurate Java programs. In this tutorial, we will explore Java's mathematical operators, operator precedence, and common pitfalls related to the `double` data type.

### 1. Java Mathematical Operators
Java provides several mathematical operators that allow you to perform operations on numerical data:

#### 1.1. Addition (`+`)
The addition operator adds two values together.

#### 1.2. Subtraction (`-`)
The subtraction operator subtracts the right operand from the left operand.

#### 1.3. Multiplication (`*`)
The multiplication operator multiplies two values.

#### 1.4. Division (`/`)
The division operator divides the left operand by the right operand not including the remainder. // 5 / 2 = 2

#### 1.5. Modulus (`%`)
The modulus operator returns the remainder when the left operand is divided by the right operand. // 5 % 2 = 1

#### 1.6. Increment (`++`) and Decrement (`--`)
The increment operator (`++`) increases a variable's value by 1, and the decrement operator (`--`) decreases it by 1.

### 2. Operator Precedence
Operator precedence determines the order in which operators are evaluated within an expression. Understanding operator precedence is crucial for ensuring that expressions are evaluated correctly.

#### 2.1. The Order of Operations
The order of operations in Java is the same as in Math which is as follows:

1. Parentheses `( )`
2. Multiplication and Division (`*`, `/`, `%`)
3. Addition and Subtraction (`+`, `-`)

#### 2.2. Parentheses `( )`
Parentheses can be used to force a specific order of evaluation within an expression. Expressions enclosed in parentheses are evaluated first.

#### 2.3. Multiplication and Division (`*`, `/`, `%`)
Multiplication, division, and modulus operations are evaluated from left to right.

#### 2.4. Addition and Subtraction (`+`, `-`)
Addition and subtraction operations are also evaluated from left to right.

### 3. Unexpected Results with Double Data Type
The `double` data type in Java represents floating-point numbers with decimal precision. However, it is important to be aware of potential issues that can lead to unexpected results when working with `double` values.

#### 3.1. Floating-Point Precision
Floating-point numbers have limited precision. Because our code is translated into binary and some values cannot be represented precisely in binary, leading to rounding errors. For example:

```java
double result = 0.1 + 0.2; // The expected result is 0.3, but you may get a slightly different value.
```

#### 3.2. Rounding Errors
Rounding errors can occur when converting between `double` and other data types. For example, converting a `double` to an `int` truncates the decimal part, potentially causing loss of information.

```java
double pi = 3.14159;
int truncatedPi = (int) pi; // Truncation can result in loss of data.
```
What we did here is called type casting. We forced Java to convert the `double pi` into an `int` which made us lose the decimal points.

#### 3.3. Comparing Double Values
Comparing `double` values for equality using `==` can be problematic due to rounding errors. It's safer to compare within a small tolerance range.

```java
double a = 0.1 + 0.2;
double b = 0.3;

if (Math.abs(a - b) < 0.000001) {
    System.out.println("Approximately equal");
}
```

### 4. Tips for Handling Doubles
To minimize issues when working with `double` values:

- Be cautious when comparing `double` values for equality.
- Be aware of rounding errors and precision limitations.


### 5. Summary
In this tutorial, we explored Java's mathematical operators, operator precedence, and common pitfalls related to the `double` data type. Understanding how these operators work and being aware of potential issues with floating-point precision is crucial for writing accurate and reliable Java programs. Always consider the data types and operations involved when working with numerical values in Java.

[Prev](part4numericDataTypes.md) | [Up](part4.md) | [Next](part4labs1.md)
