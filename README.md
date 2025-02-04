# Print vs Println vs \n in Java

## Introduction
In Java, `print`, `println`, and `\n` are used for displaying output on the console. This README explains their differences with simple examples.

---

## 1. `print()`
The `print()` method prints text on the console **without** moving to the next line.

### Example:
```java
System.out.print("Hello");
System.out.print(" World");
```
### Output:
```
Hello World
```

---

## 2. `println()`
The `println()` method prints text and moves the cursor to the **next line**.

### Example:
```java
System.out.println("Hello");
System.out.println("World");
```
### Output:
```
Hello
World
```

---

## 3. `\n` (New Line Character)
The `\n` is a special character used to insert a **new line** within a string.

### Example:
```java
System.out.print("Hello\nWorld");
```
### Output:
```
Hello
World
```

---

## Summary Table:
| Method | Moves to Next Line? | Example |
|--------|------------------|---------|
| `print()` | ❌ No | `System.out.print("Hello");` |
| `println()` | ✅ Yes | `System.out.println("Hello");` |
| `\n` | ✅ Yes (inside a string) | `System.out.print("Hello\nWorld");` |

---

## Notes:
- `print()` is useful when you want to print text **on the same line**.
- `println()` is useful when you want to **move to the next line** after printing.
- `\n` can be used inside `print()` or `println()` to create new lines within the text.


