# JavaAPCSA Section 4 Practice

## Overview
This repository contains solutions for Section 4 practice problems in Java APCSA. The practice is divided into two parts:  
- **Part A**: Writing methods  
- **Part B**: Processing a name  

## Part A - Writing Methods

### Problem 1: Writing Methods
In this practice, you'll implement methods that perform the following tasks:

1. **Convert temperature from Fahrenheit to Celsius**  
   Formula: `C = 5/9 * (F - 32)`

2. **Compute the hypotenuse of a triangle**  
   Formula: `c = √(b² + a²)`

3. **Simulate the rolling of two 6-sided dice and display their sum**

### Tasks
#### Task 1
Define the following methods in `ComputeMethods.java`:

```java
public double fToC(double degreesF)
public double hypotenuse(int a, int b)
public int roll()
```

# Task 2: Implementing the `TestClass.java`

### Objective
Perform the following tasks in the `TestClass.java` file to test the methods defined in `ComputeMethods.java`.

---

## Instructions

1. **Add a Main Method**  
   Define a `main` method in `TestClass.java`.

2. **Create an Instance of `ComputeMethods`**  
   Instantiate an object of the `ComputeMethods` class.

3. **Invoke Methods**  
   Call the following methods on the created instance:
   - `fToC(double degreesF)`
   - `hypotenuse(int a, int b)`
   - `roll()`

4. **Display Results**  
   Print the results of each method to the console.

---

## Code Example

```java
public class TestClass {
    public static void main(String[] args) {
        // Create an instance of ComputeMethods
        ComputeMethods compute = new ComputeMethods();

        // Invoke fToC method
        double tempCelsius = compute.fToC(100.0); // Example input
        System.out.println("Temp in Celsius is " + tempCelsius);

        // Invoke hypotenuse method
        double hypotenuse = compute.hypotenuse(6, 8); // Example input
        System.out.println("Hypotenuse is " + hypotenuse);

        // Invoke roll method
        int diceSum = compute.roll();
        System.out.println("The sum of the dice values is " + diceSum);
    }
}
```

