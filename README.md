# FizzBuzz

## What is this project?

 FizzBuzz is a famous coding interview question that eliminates a ton of candidates. it involves using a loop, counting, and determining if a number is divisible by a certain number (in this case 3) the program would print "Fizz", or the number is divisible by another number (in this case 5) the program would print "Buzz". However, if the number is divisible by both the program prints "FizzBuzz"

## About the code

```java
for (int i = 1; i <= 100; i++) {
            if (i % 3 == 0 && i % 5 == 0) {
                System.out.println("FizzBuzz");
            }
            else if (i % 3 == 0) {
                System.out.println("Fizz");
            }
            else if (i % 5 == 0) {
                System.out.println("Buzz");
            }
            else {
                System.out.println(i);
            }
}
```
We can see here that the program is checking 3 and 5 to see if they are divisible by the current number being counted.