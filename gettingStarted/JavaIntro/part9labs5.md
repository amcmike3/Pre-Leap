Certainly! Here's a revised version of Part 9 Lab 6 that includes options to perform addition, subtraction, multiplication, division, and determine if a number is even or odd:

## Part 9 Lab 6 - Math Operations and Number Check Menu

### Overview
In this lab, you will create a Java program where the user sees a menu that prompts them to choose a math operation (addition, subtraction, multiplication, or division) or determine if a number is even or odd. The program will then perform the selected operation or check the number as per the user's choice. You'll practice defining methods, working with user input, and performing basic math operations.

### Instructions

1. Create a file called `Part9Lab6.java` in the `PreLeap/Labs` directory.

2. Implement the program to perform the following steps:

   - Define a static method called `displayMenu` that displays a menu to the user with the following choices:
     1. Add numbers
     2. Subtract numbers
     3. Multiply numbers
     4. Divide numbers
     5. Check if a number is even or odd
     6. Exit
   - Inside the `main` method, use a loop to repeatedly prompt the user to enter their choice (a number from 1 to 6) until they choose to exit.

   - Implement methods for addition, subtraction, multiplication, and division. Each method should take two `double` parameters (the numbers to operate on) and return the result as a `double`. Handle division by zero by displaying an error message and allowing the user to enter a different denominator.

   - Implement a method called `isEvenOrOdd` that takes an integer parameter and returns a `String` indicating whether the number is even or odd.

   - In the `main` method, call the `displayMenu` method to show the menu to the user.

   - Based on the user's choice, call the corresponding math operation method, the `isEvenOrOdd` method, or exit the program as appropriate.

### Starter Code
```java
import java.util.Scanner;

public class Part9Lab6 {
    // Define the displayMenu method here

    // Define the addition method here

    // Define the subtraction method here

    // Define the multiplication method here

    // Define the division method here

    // Define the isEvenOrOdd method here hint: use the modulo operator %

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int choice = 0;
        // write a loop based on choice variable
            // Call the displayMenu method here
            // get input from user and assign it to choice variable
            //write if statements based on choice variable and call correct method

        input.close();
    }
}
```

3. Write the code inside the `displayMenu` method to display the menu to the user.

4. Implement the addition, subtraction, multiplication, and division methods to perform the corresponding math operations and return the results.

5. Implement the `isEvenOrOdd` method to determine if a number is even or odd and return a `String` indicating the result "odd" or "even".

6. In the `main` method, call the `displayMenu` method to show the menu to the user and handle their choice by calling the appropriate math operation method or the `isEvenOrOdd` method.

7. Compile and run your program to verify that it correctly displays the menu, performs the selected operation or number check, and handles division by zero gracefully.

### Testing Your Code

To test your code, open Git Bash and navigate to the directory containing your Java file (`Part9Lab6.java`). Then, compile and run the program using the following commands:

```bash
javac Part9Lab6.java
java Part9Lab6
```

### Expected Output

After running the program, it should display the menu, prompt the user for their choice, and execute the selected math operation or number check, displaying the result. The program should continue running until the user chooses to exit.

Ensure that your code correctly defines and calls the methods for math operations and number checks and handles division by zero and even/odd checks appropriately.

* When you're done don't forget to push your new code to github. 
    (`git add .`, `git commit -m "some message",`, `git push origin master`)

[Prev](part9labs4.md) | [Up](part9.md) | [Next](README.md)