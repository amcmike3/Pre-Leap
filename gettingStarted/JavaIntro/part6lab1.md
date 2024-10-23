## Part 6 Lab 1 - Using `if` Statement Comparison

### Overview
In this lab, you will create a Java program that uses an `if` statement to compare two values and make a decision based on the comparison. You'll practice using comparison operators and `if` statements to control the program's flow.

### Instructions

1. Create a file called `Part6Lab1.java` in the `PreLeap/Labs` directory.

2. Use the provided starter code and add your solution in the commented area.

3. Compare `number1` and `number2` using an `if` statement.

4. If `number1` is greater than `number2`, print the message: "Number 1 is greater than Number 2."

5. If `number1` is less than `number2`, print the message: "Number 1 is less than Number 2."

6. If `number1` is equal to `number2`, print the message: "Number 1 is equal to Number 2."

### Starter Code
```java
public class Part6Lab1 {
    public static void main(String[] args) {
        int number1 = 10;
        int number2 = 20;

         if(number1 > number2) {
      /*
        Your solution goes here
      */
    } else if(number1 < number2) {
      /*
        Your solution goes here
      */
    } else {
        /*
        Your solution goes here
      */
    }
    }
}
```

### Testing Your Code

To test your code, open git bash and navigate to the directory containing your Java file (`Part6Lab1.java`). Then, compile and run the program using the following commands:

```bash
javac Part6Lab1.java
java Part6Lab1
```

### Expected Output

After running the program, it should compare `number1` and `number2` and display the appropriate message based on the comparison:

```bash
Number 1 is less than Number 2.
```

Ensure that your code correctly compares the two numbers and prints the correct message based on the comparison.

Once you have it working correctly, change the values of number1 and number2 to see how it changes the output.

[Prev](part6ifStatements.md) | [Up](part6.md) | [Next](part6lab2.md)