
## Part 5 Lab 1 - Input and Output

### Overview
In this lab, you will create a Java program that takes various types of user inputs using the `Scanner` class and then displays those inputs as output. This exercise will help you practice reading and printing different types of data.

### Instructions

1. Create a file called `Part5Lab.java` in the `PreLeap/Labs` directory.

2. Use the provided starter code and add your solution in the commented area.

3. Prompt the user to enter their name, age, and a sentence of their choice, each on a separate line.

4. Use the `Scanner` class to read the user's inputs.

5. Display the user's inputs in the following format:
   ```
   Name: [user's name]
   Age: [user's age]
   Why you want to learn to code: [user's why]
   ```


### Starter Code
```java
import java.util.Scanner;

public class Part5Lab {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        String name = "";
        int age = 0;
        String why = "";

        /*
          Your solution goes here
        */

        input.close();
    }
}
```

### Testing Your Code

To test your code, open git bash and navigate to the directory containing your Java file (`Part5Lab.java`). Then, compile and run the program using the following commands:

```bash
javac Part5Lab.java
java Part5Lab
```

### Expected Output

After running the program, you should be prompted to enter your name, age, and why you want to learn to code. Once you've entered all the values, the program should display your inputs in the specified format.

For example:

```bash
Enter your name: Alice
Enter your age: 30
Enter why you want to learn to code: I want to improve my life.
Name: Alice
Age: 30
Why you want to learn to code: I want to improve my life.
```

Ensure that your code correctly reads and displays the user's inputs as specified.

[Prev](part5usinginput.md) | [Up](part5.md) | [Next](part5labs2.md)
