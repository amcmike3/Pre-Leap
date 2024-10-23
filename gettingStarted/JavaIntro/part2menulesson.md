**Objective 1: Creating Menus**

So far, we've explored how to print text on the screen using `System.out.println()`. However, let's delve into a bit more context regarding how we can use this printing technique.

In a later section of this pre-work, we will learn how to receive input from the user while our application is running. A common scenario is prompting the user for input, such as data or choices from a menu. Menus are often used for this purpose.

Here's an example:

```java
1 public class MenuExample {
2
3   public static void main(String[] args) {
4     System.out.println("Welcome to My Bank Application!");
5     System.out.println("-------------------------");
6     System.out.println("1) Check Balance");
7     System.out.println("2) Withdraw");
8     System.out.println("3) Deposit");  
9     System.out.println("-------------------------");
10   }
11 }
```

Running this program would produce the following output:

```bash
  >> Welcome to My Bank Application!
  >> -------------------------
  >> 1) Check Balance
  >> 2) Withdraw
  >> 3) Deposit
  >> -------------------------
```

This format expects the user to enter the number corresponding to their choice.

For instance, if the user typed in "1," we would allow them to check their balance.

[Previous](objective1-sysout.md) | [Up](README.md) | [Next](objective1-labs1.md)