**Lesson 2: Introduction to Screen Output**

Now that we've covered classes and the main method, it's time to give our application some instructions. Programming essentially involves providing precise commands to our computer for executing specific tasks.

One of the most fundamental actions to start with is displaying text on the screen. This is often the initial step when learning a new programming language, especially if it's your first time.

```java
1 public class OutputExample {
2
3   public static void main(String[] args) {
4     System.out.println("This will be output to the console.");
5   }
6
7 }
```

The code on line 4 is how we achieve text output. `System.out.println();` is the command responsible for displaying the text we specify. In this case, we instruct it to print "This will be output to the console."

When we compile with `javac OutputExample.java` and run this with `java OutputExample` in the terminal, we should observe the following output:

```bash
This will be output to the console.
```

Notice each time we use `System.out.println();` each output is on a new line.


```java
1 public class OutputExample {
2
3   public static void main(String[] args) {
4     System.out.println("These words will be displayed.");
5     System.out.println("and these.");
7     System.out.println("And also, these.");
8   }
9 }
```

This would generate the following output:

```bash
These words will be displayed.
and these .
And also, these.
```

[Previous](part2classlesson.md) | [Up](part2.md) | [Next](part2labs1.md)