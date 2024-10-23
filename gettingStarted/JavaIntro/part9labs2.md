## Part 9 Lab 2 - Greetings with Static Methods

### Overview
In this lab, you will create a Java program that requires you to write two static methods: one to say hello and another to say goodbye, both taking a name as a parameter. You'll practice defining static methods and passing parameters.

### Instructions

1. Create a file called `Part9Lab2.java` in the `PreLeap/Labs` directory.

2. Implement the program to perform the following steps:
   - Define a static method called `sayHello` that takes a `String` parameter `name` and prints a greeting message, e.g., "Hello, John!"
   - Another static method called `sayGoodbye` that also takes a `String` parameter `name` and prints a farewell message, is already written for you.

### Starter Code
```java
public class Part9Lab2 {
    // Define the static sayHello method here

    public static void sayGoodbye(String name){
        System.out.println("Goodbye " + name);
    }

    public static void main(String[] args) {
        String name = "John";
        // Call the static methods here
        
    }
}
```

3. Write the code inside the `main` method to call both static methods `sayHello` and `sayGoodbye`, passing a name as an argument to each method.

4. Compile and run your program to verify that it correctly calls the static methods and prints the greeting and farewell messages.

### Testing Your Code

To test your code, open Git Bash and navigate to the directory containing your Java file (`Part9Lab2.java`). Then, compile and run the program using the following commands:

```bash
javac Part9Lab2.java
java Part9Lab2
```

### Expected Output

After running the program, it should call both static methods and print the greeting and farewell messages to the terminal:

```
Hello, John!
Goodbye, John!
```

Ensure that your code correctly defines and calls the static methods with the provided name parameter.

[Prev](part9labs1.md) | [Up](part9.md) | [Next](part9labs3.md)