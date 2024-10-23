Certainly! Here's a Part 9 Lab 3 where the developer must write a menu method:

## Part 9 Lab 3 - Creating a Menu Method

### Overview
In this lab, you will create a Java program that requires you to write a static menu method that displays a menu to the user and handles their menu selections. You'll practice defining static methods, working with user input, and using a menu-driven approach.

### Instructions

1. Create a file called `Part9Lab3.java` in the `PreLeap/Labs` directory.

2. Implement the program to perform the following steps:
   - Define a static method called `displayMenu` that takes no parameters and prints a menu with the following choices:
     1. Say Hello
     2. Say Goodbye
     3. Exit
   
   - Based on the user's choice, call either the `sayHello` method, the `sayGoodbye` method, or exit the program.

### Starter Code
```java
import java.util.Scanner;

public class Part9Lab3 {
    public static void sayHello(){
        System.out.println("Hello");
    }

    public static void sayGoodbye(){
        System.out.println("Goodbye");
    }

    // Define the static displayMenu method here

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        choice = 0;
        while(choice != 3){
        // Call the displayMenu method here
        // get input from user and store into choice variable
        // write if statements for option 1, 2, and 3 calling the correct method or using break statement
        }
    }
}
```

3. Write the code inside the `main` method to call the static `displayMenu` method.

4. Compile and run your program to verify that it correctly displays the menu, handles user selections, and calls the appropriate methods.

### Testing Your Code

To test your code, open Git Bash and navigate to the directory containing your Java file (`Part9Lab3.java`). Then, compile and run the program using the following commands:

```bash
javac Part9Lab3.java
java Part9Lab3
```

### Expected Output

After running the program, it should display the menu, prompt the user for their choice, and execute the corresponding method based on their selection. The program should continue running until the user chooses to exit.

Ensure that your code correctly defines and calls the static methods and handles the menu-driven functionality.

[Prev](part9labs2.md) | [Up](part9.md) | [Next](part9returntypes.md)