# Lesson 5: Methods and Overloading

This lesson covers **methods** in Java, how to define and use them, and the concept of **method overloading**, which allows multiple methods with the same name but different parameters.

---

## 📚 Topics Covered

- Defining and calling methods
- Method parameters and return values
- Method overloading

---

## 💻 Example Codes

### 🔹 Simple Method

```java
public class SimpleMethodExample {
    public static void greet() {
        System.out.println("Hello, welcome to Java methods!");
    }

    public static void main(String[] args) {
        greet();  // Method call
    }
}
```

---

### 🔸 Method with Parameters and Return Value

```java
public class MethodWithParams {
    public static int square(int number) {
        return number * number;
    }

    public static void main(String[] args) {
        int result = square(5);
        System.out.println("Square of 5 is: " + result);
    }
}
```

---

### 🔁 Method Overloading

```java
public class MethodOverloadingExample {
    public static int add(int a, int b) {
        return a + b;
    }

    public static double add(double a, double b) {
        return a + b;
    }

    public static void main(String[] args) {
        System.out.println("Int sum: " + add(3, 4));
        System.out.println("Double sum: " + add(2.5, 3.5));
    }
}
```

---

## ⚠️ Important Note About Java File Names and Class Names

In Java, the **file name must exactly match the name of the `public` class inside it**, including capitalization.

For example, if your class is declared as:

```java
public class MethodOverloadingExample {
    // code here
}
```

Then your file must be named:

```
MethodOverloadingExample.java
```
