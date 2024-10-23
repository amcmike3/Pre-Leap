## Objective 4 Lab 3 - Adding Random Numbers

### Overview
In this lab, you will create a Java program that generates two random numbers and calculates their sum. You'll practice using random number generation, variables, and mathematical operations to perform this simple arithmetic task.

### Instructions

1. Create a file called `Part4Lab3.java` in the `PreLeap/Labs` directory.

2. Use the provided starter code and add your solution in the commented area.

Your task is to write code that does the following:

3. Generate two random integers between 1 and 100 (inclusive) using the `Random` class. You can use the `nextInt()` method of the `Random` class to obtain random integers.

4. Calculate the sum of the two random integers.

5. Display both random integers and their sum to the console.

### Starter Code
```java
import java.util.Random;

public class Part4Lab3 {
  public static void main(String[] args) {
    // Create a new Random object to generate random numbers
    Random rand = new Random();

    // Declare variables to store the two random numbers and their sum
    int num1, num2, sum;

    /*
      Your solution goes here
    */
  }
}
```

### Hint:

The nextInt() method can be used to generate your random numbers. We can pass the argument 100 to tell it to give us a number between 0-99 and add 1 to move the range to 1-100. 
```java
    num1 = rand.nextInt(100) + 1;
```


### Testing Your Code

To test your code, open git bash and navigate to the directory containing your Java file (`Part4Lab3.java`). Then, compile and run the program using the following commands:

```bash
javac Part4Lab3.java
java Part4Lab3
```

### Expected Output

After running the program, you should see the following output:

```bash
Random number 1: 22
Random number 2: 58
Sum: 80
```

The actual values will vary each time you run the program due to the random number generation.

Ensure that your code correctly generates random numbers, calculates their sum, and displays the results to the console.

* When you're done don't forget to push your new code to github. 
    (`git add .`, `git commit -m "some message",`, `git push origin master`)


[Prev](part4labs2.md) | [Up](part4.md) | [Next](README.md)
