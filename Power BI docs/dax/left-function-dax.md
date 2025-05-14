### 📌 `LEFT`

The `LEFT` function returns a specified number of characters from the **start** of a text string.

#### 🔧 Syntax

```
LEFT(<text>, <num_of_characters>)
```

* `<text>`: The text string to extract from.
* `<num_of_characters>` *(optional)*: Number of characters to extract from the left. Defaults to 1 if not specified.

#### 📝 Example

```dax
Month Short = 
UPPER(
    LEFT('Calendar Lookup'[Month Name], 3)
)
```

This returns the first three letters of the month name in uppercase (e.g., "JAN", "FEB").

---
