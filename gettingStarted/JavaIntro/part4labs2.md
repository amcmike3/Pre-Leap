## Objective 4 Lab 2 - Finding the Hypotenuse of a Right Triangle

### Overview
In this lab, you will create a Java program that calculates the length of the hypotenuse of a right triangle using the Pythagorean theorem. You'll practice using variables, user input, and mathematical operators to find this important geometric value.

### Instructions

1. Create a file called `Part4Lab2.java` in the `PreLeap/Labs` directory.

2. Use the provided starter code and add your solution in the commented area.

### Starter Code
```java
import java.lang.Math; // Import the Math class for sqrt() function
public class Part4Lab2 {
  public static void main(String[] args) {
    // Declare variables to store the lengths of the two shorter sides of the right triangle
    double side1, side2;

    /*
      Your solution goes here
    */

  }
}
```

### Hint:
The pythagorean theorem is a^2 + b^2 = c^2.

Additionally we can use the Math.sqrt() function to find the square root.

```java 
   // Calculate the length of the hypotenuse
    hypotenuse = Math.sqrt(side1 * side1 + side2 * side2);
```


### Testing Your Code

To test your code, open git bash and navigate to the directory containing your Java file (`Part4Lab2.java`). Then, compile and run the program using the following commands:

```bash
javac Part4Lab2.java
java Part4Lab2
```

### Expected Output

After running the program should calculate and display the length of the hypotenuse.

For example:

```bash
The length of the hypotenuse is: 5.0 for a right triangle with side lengths of 3.0 and 4.0.
```

Ensure that your code correctly calculates and displays the length of the hypotenuse using the Pythagorean theorem.

[Prev](part4labs1.md) | [Up](part4.md) | [Next](part4labs3.md)
