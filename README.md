# Print vs Println vs \n in Java

## About This Repo
This repo is a simple explanation of how `print`, `println`, and `\n` work in Java. I created this to demonstrate their differences and how they can be used effectively.

---

## 1. `print()`
The `print()` method prints text on the console **without** moving to the next line. This means whatever you print next will appear right after the previous text.

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
The `println()` method prints text and then moves the cursor to the **next line**.

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
The `\n` is a special character that creates a **new line** inside a string, even if you're using `print()`.

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

## Why I Made This
I created this repo as a reference for anyone who is new to Java or needs a quick refresher on how printing works. Feel free to check out the code and experiment with it!



