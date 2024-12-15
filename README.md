# Uncommon Loop Exit in Java

This example showcases a less common scenario in Java programming: an early exit from a while loop using a return statement inside the loop's body. While functional, this practice can sometimes decrease code readability and make it harder to pinpoint the control flow during debugging, especially in more complex scenarios.

The `bug.java` file demonstrates the issue; the loop prematurely terminates when the counter `i` equals 5. The `bugSolution.java` file provides a more conventional approach using a `break` statement for loop control.