# Using the Scanner For User Input

The `Scanner` class in Java is a versatile and powerful tool for handling user input. It allows you to read various types of data, such as text, numbers, and more, from different sources, including the keyboard and files. In this tutorial, we will explore how to use the `Scanner` class to acquire user input effectively in Java programs.

### 1. Introduction to the Scanner Class

#### 1.1. Importing the Scanner Class
Before you can use the `Scanner` class, you need to import it into your Java program. Add the following import statement at the beginning of your code:

```java
import java.util.Scanner;
```

#### 1.2. Creating a Scanner Object
To read input from the user, you must create an instance of the `Scanner` class. Typically, you create one `Scanner` object for each source of input. For reading from the keyboard (standard input), create a `Scanner` object like this:

```java
Scanner input = new Scanner(System.in);
```

Now, you can use the `input` object to interact with the user and collect input.

### 2. Reading Different Types of Input

#### 2.1. Reading Text Input
You can use the `next()` method of the `Scanner` class to read a single word (a sequence of characters without spaces) from the user:

```java
System.out.print("Enter a word: ");
String word = input.next();
```

To read an entire line of text (including spaces), use the `nextLine()` method:

```java
System.out.print("Enter a sentence: ");
String sentence = input.nextLine();
```

#### 2.2. Reading Numeric Input
To read numeric input (integers, decimals, etc.), you can use methods like `nextInt()`, `nextDouble()`, or `nextFloat()`:

```java
System.out.print("Enter an integer: ");
int number = input.nextInt();

System.out.print("Enter a decimal number: ");
double decimal = input.nextDouble();
```

#### 2.3. Reading Single Characters
You can use the `next()` method to read a single character as a string and then extract the first character from that string:

```java
System.out.print("Enter a single character: ");
String charString = input.next();
char singleChar = charString.charAt(0);
```

#### Note:
When reading user input, it's essential to handle potential errors gracefully. For example, if the user enters a non-integer when you expect an integer, your program will blow up. We don't know how to properly handle this just yet but we will learn later (; . For now just be careful of what you input and take a deep breathe if your program breaks from bad inputs. 


### 3. Closing the Scanner
It's good practice to close the `Scanner` object when you are done with it to release any associated resources. You can close it using the `close()` method:

```java
input.close();
```

### 5. Summary
The `Scanner` class in Java is a valuable tool for reading user input. By importing the class, creating a `Scanner` object, and using its methods, you can efficiently collect text, numbers, and characters from the user. Remember to handle errors gracefully and validate input to ensure the reliability of your programs. Finally, don't forget to close the `Scanner` object when you're finished with it to free up system resources.

[Prev](part5.md) | [Up](part5.md) | [Next](part5usinginput.md)
