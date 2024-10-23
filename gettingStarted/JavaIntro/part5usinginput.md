Here are some examples of how to use inputs from `Scanner` objects for various types of user input:

### Example 1: Reading Text Input

```java
import java.util.Scanner;

public class TextInputExample {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter your name: ");
        String name = input.next(); // Read a single word
        System.out.println("Hello, " + name + "!");
        
        input.close();
    }
}
```

```bash
Enter your name: John
Hello, John!
```

In this example, the program prompts the user to enter their name, and then it reads and displays the input as text.

### Example 2: Reading Numeric Input

```java
import java.util.Scanner;

public class NumericInputExample {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter an integer: ");
        int number = input.nextInt(); // Read an integer
        System.out.println("You entered: " + number);

        System.out.print("Enter a decimal number: ");
        double decimal = input.nextDouble(); // Read a double
        System.out.println("You entered: " + decimal);
        
        input.close();
    }
}
```

```bash
Enter an integer: 42
You entered: 42

Enter a decimal number: 3.14
You entered: 3.14
```

In this example, the program reads both integers and decimal numbers from the user and displays the entered values.

### Example 3: Reading Text Lines

```java
import java.util.Scanner;

public class TextLineInputExample {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter a sentence: ");
        String sentence = input.nextLine(); // Read a line of text
        System.out.println("You entered: " + sentence);
        
        input.close();
    }
}
```

```bash
Enter a sentence: This is a sample sentence.
You entered: This is a sample sentence.
```

Here, the program reads an entire line of text (including spaces) entered by the user and displays it.

### Example 4: Reading Single Characters

```java
import java.util.Scanner;

public class CharInputExample {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter a single character: ");
        String charString = input.next(); // Read a single character as a string
        char singleChar = charString.charAt(0); // Extract the first character
        System.out.println("You entered: " + singleChar);
        
        input.close();
    }
}
```

```bash
Enter a single character: A
You entered: A
```

In this example, the program reads a single character as a string and then extracts the first character from the string to display it.

These examples demonstrate how to use `Scanner` objects to collect different types of user input in Java programs.

[Prev](part5userinput.md) | [Up](part5.md) | [Next](part5labs1.md)