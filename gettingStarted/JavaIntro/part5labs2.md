## Part 5 Lab 2 - Calculating the Average of 5 Numbers

### Overview
In this lab, you will create a Java program that calculates the average of five numbers provided as input. You'll practice using variables, user input, and mathematical operators to compute and display the average.

### Instructions

1. Create a file called `Part5Lab2.java` in the `PreLeap/Labs` directory.

2. Use the provided starter code and add your solution in the commented area.

3. Prompt the user to enter five numbers, one at a time, using the `Scanner` class.

4. Calculate the average of the five numbers by adding them together and dividing by 5.

5. Display the calculated average to the console.

### Starter Code
```java
import java.util.Scanner;

public class Part5Lab2 {
  public static void main(String[] args) {
    // Create a new Scanner object to read user input
    Scanner input = new Scanner(System.in);

    // Declare variables to store five numbers and the average
    double num1, num2, num3, num4, num5;
    double average;

    /*
      Your solution goes here
    */

    // Close the Scanner object
    input.close();
  }
}
```

### Testing Your Code

To test your code, open git bash and navigate to the directory containing your Java file (`Part5Lab2.java`). Then, compile and run the program using the following commands:

```bash
javac Part5Lab2.java
java Part5Lab2
```

### Expected Output

After running the program, you should be prompted to enter five numbers one by one. Once you've entered all the numbers, the program should calculate and display the average of those numbers.

For example:

```bash
Enter the first number:
10
Enter the second number:
20
Enter the third number:
30
Enter the fourth number:
40
Enter the fifth number:
50
The average of the five numbers is: 30.0
```

Ensure that your code correctly calculates and displays the average of the five numbers entered by the user.

[Prev](part5labs1.md) | [Up](part5.md) | [Next](part5labs3.md)
