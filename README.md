# Notes 1: print()
[Tutorial Video: print() and expressions](https://youtu.be/lkQT8zb0_A8?si=nqWw4YAs2XMVI9MX)

The `print()` function is used to **display information** on the screen.

You can use it to show:

* Text (like a message or label)
* Numbers or math results
* The value of variables

---

## Example:

```python
print("Hello, world!")
```

### Output:

```
Hello, world!
```

---

## Syntax
Python shows whatever is inside the `print()` parentheses.

```python
print(thing_to_show)
```

* Always use **parentheses** `()`
* Text must go inside **quotes**: `" "` or `' '`

---

## Examples

### Printing Text

```python
print("My name is Alex")
```

### Printing Math

```python
print(3 + 4)
```

### Printing Variables

```python
name = "Jordan"
print(name)
```

### Printing Multiple Items

```python
age = 16
print("I am", age, "years old")
```

---

## Common Mistakes

| Mistake          | Problem                                  |
| ---------------- | ---------------------------------------- |
| `Print("Hello")` | ❌ `Print` should be lowercase: `print()` |
| `print(Hello)`   | ❌ Missing quotes around text             |
| `print "Hello"`  | ❌ Missing parentheses in Python 3        |

---

## Why Use `print()`?

* Helps you test your code
* Lets you show messages to users
* Useful for debugging (finding mistakes)

---

## Practice

What does each of these lines print?

```python
print("2 + 2")
print(2 + 2)
```

**Answers:**

```
2 + 2
4
```

Why? The first one is **text** in quotes. The second one is **math**.


