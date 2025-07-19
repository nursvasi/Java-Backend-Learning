# Lesson 4: Arrays and String Operations

This folder contains Java examples and exercises related to **arrays** and **string manipulation**, which are fundamental for storing collections of data and processing text in Java.

---

## 📚 Topics Covered

### Arrays
- One-dimensional arrays
- Multi-dimensional arrays (2D arrays)

### Strings
- `String` class basics
- Common string methods (e.g., `length()`, `charAt()`, `substring()`, `equals()`, `toUpperCase()`, etc.)

---

## 💻 Example Codes

### 📌 One-Dimensional Array

```java
public class OneDArrayExample {
    public static void main(String[] args) {
        int[] numbers = {10, 20, 30, 40, 50};

        for (int i = 0; i < numbers.length; i++) {
            System.out.println("Element at index " + i + ": " + numbers[i]);
        }
    }
}
```

---

### 🧮 Multi-Dimensional Array (2D Array)

```java
public class TwoDArrayExample {
    public static void main(String[] args) {
        int[][] matrix = {
            {1, 2, 3},
            {4, 5, 6}
        };

        for (int i = 0; i < matrix.length; i++) {
            for (int j = 0; j < matrix[i].length; j++) {
                System.out.print(matrix[i][j] + " ");
            }
            System.out.println();
        }
    }
}
```

---

### 🔤 String Basics

```java
public class StringExample {
    public static void main(String[] args) {
        String message = "Hello, Java!";
        System.out.println("Message: " + message);
        System.out.println("Length: " + message.length());
        System.out.println("First character: " + message.charAt(0));
        System.out.println("Substring (0-5): " + message.substring(0, 5));
    }
}
```

---

### 🛠️ String Methods

```java
public class StringMethodsExample {
    public static void main(String[] args) {
        String original = "java programming";
        String upper = original.toUpperCase();
        String lower = original.toLowerCase();
        boolean isEqual = original.equals("Java Programming");
        boolean contains = original.contains("program");

        System.out.println("Original: " + original);
        System.out.println("Upper case: " + upper);
        System.out.println("Lower case: " + lower);
        System.out.println("Equals 'Java Programming'? " + isEqual);
        System.out.println("Contains 'program'? " + contains);
    }
}
```

---

## ⚠️ Important Note About Java File Names and Class Names

In Java, the **file name must exactly match the name of the `public` class inside it**, including capitalization.

For example, if your class is declared as:

```java
public class StringExample {
    // code here
}
```

Then your file must be named:

```
StringExample.java
```

❌ `stringexample.java` → will cause a **compilation error**  
✅ `StringExample.java` → correct

---
