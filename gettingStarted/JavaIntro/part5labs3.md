## Part 5 Lab 3 - Adding or Subtracting Numbers

### Overview
In this lab, you will create a Java program that prompts the user to enter two numbers and then performs addition or subtraction based on the user's choice. You'll practice using the `Scanner` class, and arithmetic operations and get your first taste of conditionals and if statements.

### Instructions

1. Create a file called `Part5Lab3.java` in the `PreLeap/Labs` directory.

2. Use the provided starter code and add your solution in the commented area.

3. Prompt the user to enter two numbers, one at a time, using the `Scanner` class.

### Starter Code
```java
import java.util.Scanner;

public class Part5Lab3 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        double num1, num2, result;
        /*
          Your solution goes here
          prompt user for two numbers and assign them to num1 and num2
        */


        input.nextLine(); // Consume the newline character

        System.out.print("Choose an operation (add or subtract): ");
        String operation = input.nextLine();
       if (operation.equals("add")) {
            result = num1 + num2;
        } else if (operation.equals("subtract")) {
            result = num1 - num2;
        } else {
            System.out.println("Invalid operation. Please enter 'add' or 'subtract'.");
            return; // Exit the program
        }

        System.out.println("Result: " + result);

        input.close();
    }
}
```

### Testing Your Code

To test your code, open git bash and navigate to the directory containing your Java file (`Part5Lab3.java`). Then, compile and run the program using the following commands:

```bash
javac Part5Lab3.java
java Part5Lab3
```

### Expected Output

After running the program, you should be prompted to enter two numbers and choose an operation. Based on your inputs, the program should perform either addition or subtraction and display the result.

For example:

```bash
Enter the first number: 10
Enter the second number: 5
Choose an operation (add or subtract): add
Result: 15.0
```

Ensure that your code correctly reads the numbers, performs the selected operation, and displays the result.

* When you're done don't forget to push your new code to github. 
    (`git add .`, `git commit -m "some message",`, `git push origin master`)


[Prev](part5labs2.md) | [Up](part5.md) | [Next](README.md)