## Part 6 Lab 3 - Number Comparison with User Input

### Overview
In this lab, you will create a Java program that takes user input and uses an `if` statement to determine whether the input number is greater or less than a specified number. You'll practice getting user input, converting it to a numeric type, and using `if` statements for comparison.

### Instructions

1. Create a file called `Part6Lab3.java` in the `PreLeap/Labs` directory.

2. Use the provided starter code and add your solution in the commented area.

3. Prompt the user to enter a number using the `Scanner` class.

4. Compare the user's input number with the `comparisonNumber` (which is set to 50 in the starter code) using an `if` statement.

5. If the user's input number is greater than the `comparisonNumber`, print the message: "Your number is greater than 50."

6. If the user's input number is less than the `comparisonNumber`, print the message: "Your number is less than 50."

7. If the user's input number is equal to the `comparisonNumber`, print the message: "Your number is equal to 50."

### Starter Code
```java
import java.util.Scanner;

public class Part6Lab3 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int comparisonNumber = 50;

        System.out.print("Enter a number: ");
        // Get user input and store it in a variable
        
        /*
          Your solution goes here
        */

        input.close();
    }
}
```

### Testing Your Code

To test your code, open git bash and navigate to the directory containing your Java file (`Part6Lab3.java`). Then, compile and run the program using the following commands:

```bash
javac Part6Lab3.java
java Part6Lab3
```

### Expected Output

After running the program, it should prompt the user to enter a number, compare it to 50, and display the appropriate message based on the comparison:

```bash
Enter a number: 42
Your number is less than 50.
```

Ensure that your code correctly handles user input and prints the correct message based on the comparison.

[Prev](part6labs2.md) | [Up](part6.md) | [Next](part6labs4.md)
