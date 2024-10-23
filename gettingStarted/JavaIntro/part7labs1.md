## Part 7 Lab 1 - Menu Selection with Switch Cases

### Overview
In this lab, you will create a Java program that allows users to select items from a menu using a switch statement. This lab will help you practice implementing a menu-driven program and using switch cases for different menu options.

### Instructions

1. Create a file called `Part7Lab1.java` in the `PreLeap/Labs` directory.

2. Use the provided starter code and add your solution in the commented area.

3. Display a menu with four options (Option 1, Option 2, Option 3, and Quit).

4. Prompt the user to enter a choice by entering a number (1-4).

5. Use a switch statement to perform different actions based on the user's choice:
   - If the user chooses Option 1, print "You selected Option 1."
   - If the user chooses Option 2, print "You selected Option 2."
   - If the user chooses Option 3, print "You selected Option 3."
   - If the user chooses Quit (Option 4), exit the program with the message "Goodbye!"


### Starter Code
```java
import java.util.Scanner;

public class Part7Lab1 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        // Display a menu with options
        System.out.println("Menu:");
        System.out.println("1. Option 1");
        System.out.println("2. Option 2");
        System.out.println("3. Option 3");
        System.out.println("4. Quit");

        // Prompt the user to enter a choice
        System.out.print("Enter your choice (1-4): ");
        int choice = input.nextInt();

        /*
          Your solution goes here
        */

        input.close();
    }
}
```



### Testing Your Code

To test your code, open Git Bash and navigate to the directory containing your Java file (`Part7Lab1.java`). Then, compile and run the program using the following commands:

```bash
javac Part7Lab1.java
java Part7Lab1
```

### Expected Output

After running the program, it should display the menu, allow the user to select an option, and provide the corresponding message based on the user's choice:

```bash
Menu:
1. Option 1
2. Option 2
3. Option 3
4. Quit
Enter your choice (1-4): 2
You selected Option 2.
```

Ensure that your code correctly handles menu selections and provides the appropriate messages for each option.

[Prev](part7switch.md) | [Up](part7.md) | [Next](part7labs2.md)