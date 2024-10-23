## Part 8 Lab 4 - Sum of Five Numbers

### Overview
In this lab, you will create a Java program that prompts the user to enter five numbers and then calculates and displays their sum. This lab will help you practice working with loops, user input, and performing arithmetic operations.

### Instructions

1. Create a file called `Part8Lab4.java` in the `PreLeap/Labs` directory.

2. Implement the program to perform the following steps:
   - Prompt the user to enter five numbers, one at a time.
   - Use a loop to read each number from the user.
   - Calculate and store the sum of the five numbers.
   - Display the sum to the user.

### Starter Code
```java
import java.util.Scanner;

public class Part8Lab4 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int sum = 0;

        // Your code goes here

        input.close();
    }
}
```

3. Write the code inside the `main` method to implement the program as described in the instructions.

4. Compile and run your program to verify that it correctly calculates and displays the sum of the five numbers entered by the user.

### Testing Your Code

To test your code, open Git Bash and navigate to the directory containing your Java file (`Part8Lab4.java`). Then, compile and run the program using the following commands:

```bash
javac Part8Lab4.java
java Part8Lab4
```

### Expected Output

After running the program, it should prompt the user to enter five numbers, calculate their sum, and display the sum in the terminal.

For example, if the user enters the numbers `10`, `20`, `30`, `40`, and `50`, the program should display:

```
Enter number 1: 10
Enter number 2: 20
Enter number 3: 30
Enter number 4: 40
Enter number 5: 50
Sum of the numbers: 150
```

Ensure that your code correctly calculates and displays the sum of the user-entered numbers.

[Prev](part8labs3.md) | [Up](part8.md) | [Next](part8labs5.md)