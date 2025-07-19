# Lesson 2: Variables and Data Types

In this lesson, we learn how to declare variables in Java and use basic data types.

## 🔢 Data Types:

| Type      | Description        | Example      |
|-----------|--------------------|--------------|
| `int`     | Integer numbers     | `42`         |
| `double`  | Decimal numbers     | `3.14`       |
| `boolean` | True or False       | `true`       |
| `char`    | Single character    | `'A'`        |
| `String`  | Text (sequence)     | `"Hello"`    |

## 🧪 Example Code:
```java
public class Main {
    public static void main(String[] args) {
        int age = 24;
        double height = 1.75;
        boolean isStudent = true;
        char firstLetter = 'N';
        String name = "Nur Sultan";

        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Height: " + height);
        System.out.println("Student: " + isStudent);
        System.out.println("First letter: " + firstLetter);
    }
}
