## While Loop Execution Steps

The operation of a `while` loop can be summarized as follows:

```java
while (condition) {
  // Loop body
}
```

1. Check the _condition_. If it evaluates to `true`, proceed to execute the code block within the loop.
2. Execute the _loop body_.
3. Repeat until condition is false.

The _condition_ within a `while` loop is continually evaluated.
* This means that a `while` loop may execute any number of times including not at all.
* If the _condition_ is false when Java first encounters the loop, the loop will not execute at all.

If the _condition_ never becomes false, an "infinite loop" occurs.
* While this can sometimes be intentional, it can also indicate a programming error.

[Prev](part8whileloops.md) | [Up](part8.md) | [Next](part8dowhileloops.md)