Certainly! Here's a Part 8 Lab 5 that displays a menu with several choices, and different actions are performed based on the menu option selected by the user:

## Part 8 Lab 5 - Menu Selection

### Overview
In this lab, you will create a Java program that displays a menu with several choices to the user. Depending on the user's menu selection, the program will perform different actions. This lab will help you practice working with menu-driven programs and conditional statements.

### Instructions

1. Create a file called `Part8Lab5.java` in the `PreLeap/Labs` directory.

2. Implement the program to perform the following steps:
   - Display a menu with the following choices to the user:
     - Choice 1: Print "You selected Choice 1."
     - Choice 2: Print "You selected Choice 2."
     - Choice 3: Print "You selected Choice 3."
     - Choice 4: Print "You selected Choice 4."
     - Choice 5: Print "You selected Choice 5."
     - Choice 6: Exit the program.
   - Prompt the user to enter a menu choice (a number from 1 to 6).
   - Based on the user's choice, perform the corresponding action as described above.
   - If the user selects Choice 6, exit the program.

### Starter Code
```java
import java.util.Scanner;

public class Part8Lab5 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int choice = 0;
        while (choice != 6) {

            // Your menu goes here
            // reassign the choice vaiable to what the user chooses
            //use if-else else-if statements to print different messages based on user choice

            if (choice >= 6 || choice <= 0){
                System.out.println("Goodbye");
                break;
            }
        }
        input.close();
    }
}
```

3. Write the code inside the `main` method to implement the program as described in the instructions.

4. Compile and run your program to verify that it correctly displays the menu, performs actions based on user input, and exits the program when Choice 6 is selected.

### Testing Your Code

To test your code, open Git Bash and navigate to the directory containing your Java file (`Part8Lab5.java`). Then, compile and run the program using the following commands:

```bash
javac Part8Lab5.java
java Part8Lab5
```

### Expected Output

After running the program, it should display the menu to the user, prompt for a choice, and perform the corresponding action based on the user's selection. Here's an example of the expected output:

```
Menu:
1. Choice 1
2. Choice 2
3. Choice 3
4. Choice 4
5. Choice 5
6. Exit

Enter your choice (1-6): 3
You selected Choice 3

Enter your choice (1-6): 6
Goodbye
```

Ensure that your code correctly handles user input and performs the appropriate actions based on the menu choice.
[Prev](part8labs4.md) | [Up](part8.md) | [Next](README.md)