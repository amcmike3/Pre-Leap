## Part 9 Lab 1 - Printing with a Static Method

### Overview
In this lab, you will create a Java program that calls a static method to print a message. You'll practice working with static methods and calling them without creating an instance of the class.

### Instructions

1. Create a file called `Part9Lab1.java` in the `PreLeap/Labs` directory.

2. Implement the program to perform the following steps:
   - Define a static method called `printMessage` that takes no parameters and prints the message "Hello, Im printing from the Method!" to the console.

### Starter Code
```java
public class Part9Lab1 {
    public static void printMessage() {
        // print the variable param
        
    }
    public static void main(String[] args) {
        // Call the static method here
        
    }
}
```

3. Write the code inside the `main` method to call the static method `printMessage`.

4. Compile and run your program to verify that it correctly calls the static method and prints the message.

### Testing Your Code

To test your code, open Git Bash and navigate to the directory containing your Java file (`Part9Lab1.java`). Then, compile and run the program using the following commands:

```bash
javac Part9Lab1.java
java Part9Lab1
```

### Expected Output

After running the program, it should call the static method and print the following message to the terminal:

```bash
Hello, Im printing from the Method!
```

Ensure that your code correctly calls the static method to print the message.

[Prev](part9methods.md) | [Up](part9.md) | [Next](part9labs2.md)