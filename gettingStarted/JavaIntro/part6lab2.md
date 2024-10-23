## Part 6 Lab 2 - String Comparison with `if` Statements

### Overview
In this lab, you will create a Java program that uses `if` statements to compare two strings and make decisions based on the comparison. You'll practice string comparison, equality checks, and using `if` statements for branching logic.

### Instructions

1. Create a file called `Part6Lab2.java` in the `PreLeap/Labs` directory.

2. Use the provided starter code and add your solution in the commented area.

3. Compare equality for `word1` with `word2` and `word3` using `if` statements.

4. If `word1` equals `word2`, print the message: "Word 1 equals Word 2."

5. If `word1` equals `word3`, print the message: "Word 1 equals Word 3."

6. If `word1` does not equal either, print the message: "Word 1 is not equal to Word 2 or Word 3"

### Hint
* remember to compare equality with Strings we use the .equals() method. 
```java
    String word1 = "apple";
    String word2 = "apple";
    boolean result = word1.equals(word2); // true contents are the same
    boolean result2 = word1 == word2; // false not the same identity
```


### Starter Code
```java
public class Part6Lab2 {
    public static void main(String[] args) {
        String word1 = "apple";
        String word2 = "banana";
        String word3 = "peach";

        /*
          Your solution goes here
        */
    }
}
```

### Testing Your Code

To test your code, open git bash and navigate to the directory containing your Java file (`Part6Lab2.java`). Then, compile and run the program using the following commands:

```bash
javac Part6Lab2.java
java Part6Lab2
```

### Expected Output

After running the program, it should compare `word1` and `word2` and display the appropriate message based on the comparison:

```bash
Word 1 is not equal to Word 2 or Word 3
```

Ensure that your code correctly compares the two words and prints the correct message based on the comparison.

[Prev](part6lab1.md) | [Up](part6.md) | [Next](part6lab3.md)
