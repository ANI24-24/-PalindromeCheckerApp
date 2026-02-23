# -PalindromeCheckerApp
Objective:
The objective of the PalindromeChecker App is to design and implement a console-based Java application that validates whether a given string is a palindrome under different conditions, while strengthening core programming fundamentals and data structure concepts.

Use Case 1:-

Goal:
Display a welcome message and application information when the PalindromeChecker App starts.

Flow:-

Program starts.

JVM invokes the main() method.

Application name is displayed.

Application version is displayed.

Program continues to next use case or exits.

Key Concepts:

Class – Acts as a container for the Palindrome Checker application logic.

Main Method – Entry point of the Java application with the signature
public static void main(String[] args).

Static Keyword – Allows the JVM to invoke the main() method without creating an object.

Console Output – System.out.println() is used to display messages on the console.

Application Flow Control – Defines the startup behavior before palindrome processing begins.

Data Structure: None (Console based execution)

Use Case 2:-

Goal:
Display whether a hardcoded string is a palindrome.

Flow:

Program starts

Hardcoded string is checked

Result is printed

Program exits

Key Concepts:

Class – In Java, even the simplest program must be written inside a class, as a class acts as a container to hold program logic.

Main Method – Entry point of the Java application with the signature
public static void main(String[] args).

Static Keyword – Allows the JVM to invoke the main() method without creating an object of the class.

String – A built-in Java class used to store and manipulate textual data. Here, it stores the word to be checked for a palindrome.

String Literal – Text enclosed within double quotes ("madam"), stored in the String constant pool.

Conditional Statement (if-else) – Used to evaluate whether the given string satisfies the palindrome condition.

Console Output – System.out.println() is used to display the result on the console.

Data Structure: String

USE CASE 3:-

Goal: Check whether a string is a palindrome by reversing it.

Flow:

Reverse string using loop

Compare original and reversed

Display result

Key Concepts used in UC3:

Loop (for loop) – Used to iterate through the characters of the string in reverse order.

String Immutability – In Java, String objects are immutable; every modification creates a new String object.

equals() Method – Used to compare the actual content of two String objects instead of memory references.

Data Structure: String

