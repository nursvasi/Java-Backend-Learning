# Lesson 3: Conditions and Loops

This folder contains Java examples and exercises covering **conditional statements** and **loops**, which are essential building blocks for controlling the flow of your programs.

---

## 📚 Topics Covered

### Conditional Statements
- `if` statement
- `if-else` statement
- `if-else if-else` ladder
- `switch` statement

### Loops
- `for` loop
- `while` loop
- `do-while` loop
- Nested loops

---

## 💻 Example Codes

### 🟢 If Statement

```java
public class IfExample {
    public static void main(String[] args) {
        int number = 10;
        if (number > 0) {
            System.out.println("The number is positive.");
        }
    }
}
```

---

### 🟡 If-Else Statement

```java
public class IfElseExample {
    public static void main(String[] args) {
        int number = -5;
        if (number > 0) {
            System.out.println("Positive number");
        } else {
            System.out.println("Non-positive number");
        }
    }
}
```

---

### 🟠 If-Else If-Else Ladder

```java
public class IfElseIfElseExample {
    public static void main(String[] args) {
        int score = 75;
        if (score >= 90) {
            System.out.println("Grade: A");
        } else if (score >= 80) {
            System.out.println("Grade: B");
        } else if (score >= 70) {
            System.out.println("Grade: C");
        } else {
            System.out.println("Grade: F");
        }
    }
}
```

---

### 🔵 Switch Statement

```java
public class SwitchExample {
    public static void main(String[] args) {
        int day = 3;
        switch (day) {
            case 1:
                System.out.println("Monday");
                break;
            case 2:
                System.out.println("Tuesday");
                break;
            case 3:
                System.out.println("Wednesday");
                break;
            default:
                System.out.println("Invalid day");
        }
    }
}
```

---

### 🔁 For Loop

```java
public class ForLoopExample {
    public static void main(String[] args) {
        for (int i = 1; i <= 5; i++) {
            System.out.println("Count: " + i);
        }
    }
}
```

---

### 🔂 While Loop

```java
public class WhileLoopExample {
    public static void main(String[] args) {
        int i = 1;
        while (i <= 5) {
            System.out.println("Count: " + i);
            i++;
        }
    }
}
```

---

### 🔂 Do-While Loop

```java
public class DoWhileExample {
    public static void main(String[] args) {
        int i = 1;
        do {
            System.out.println("Count: " + i);
            i++;
        } while (i <= 5);
    }
}
```

---

### 🔀 Nested Loops

```java
public class NestedLoopsExample {
    public static void main(String[] args) {
        for (int i = 1; i <= 3; i++) {          // Outer loop
            for (int j = 1; j <= 2; j++) {      // Inner loop
                System.out.println("i = " + i + ", j = " + j);
            }
        }
    }
}
```

---

## ⚠️ Important Note About Java File Names and Class Names

In Java, the **file name must exactly match the name of the `public` class inside it**, including capitalization.

For example, if your class is declared as:

```java
public class NestedLoopsExample {
    // code here
}
```

Then your file must be named:

```
NestedLoopsExample.java
```

If the file name and the class name do not match, the compiler will throw an error.
