### 📌 `RIGHT`

The `RIGHT` function returns a specified number of characters from the **end** of a text string.

#### 🔧 Syntax

```
RIGHT(<text>, <num_of_characters>)
```

* `<text>`: The text string to extract from.
* `<num_of_characters>`: Number of characters to extract from the right.

#### 📝 Example

```dax
Year Suffix = 
RIGHT('Calendar Lookup'[Year], 2)
```

This extracts the last two digits of the year (e.g., "2024" → "24").

---
