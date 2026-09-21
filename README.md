# Java-Day-03-User-Input
# Java Day 3 - User Input

This is my third Java program.

In this program, I learned how to take input from the user using the `Scanner` class.

## Example

Input:

```text
Enter your name: Suyash
Enter your age: 21
```

Output:

```text
Name: Suyash
Age: 21
```

## Concepts Used

* `Scanner`
* User input
* `nextLine()`
* `nextInt()`
* `String`
* `int`
* Variables
* `System.out.print()`

## How It Works

1. Import the `Scanner` class.
2. Create a `Scanner` object.
3. Use `nextLine()` to take text input.
4. Use `nextInt()` to take integer input.
5. Store the input in variables.
6. Print the entered values.

## Java Code

```java
import java.util.Scanner;

public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter your name: ");
        String name = sc.nextLine();

        System.out.print("Enter your age: ");
        int age = sc.nextInt();

        System.out.println("Name: " + name);
        System.out.println("Age: " + age);

        sc.close();
    }
}
```

## Output

```text
Enter your name: Suyash
Enter your age: 21
Name: Suyash
Age: 21
```

## Goal

The goal of this project is to understand how to take basic user input using the `Scanner` class in Java.
