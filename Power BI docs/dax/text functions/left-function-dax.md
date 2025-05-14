### 📌 `LEFT` Function

The `LEFT` function in DAX returns a specified number of characters from the **start** of a text string. It’s often used to extract substrings for formatting or categorization purposes.

#### 🔧 Syntax

```
LEFT(<text>, <num_of_characters>)
```

* `<text>`: The string from which to extract characters.
* `<num_of_characters>`: *(Optional)* The number of characters to extract, starting from the left. If omitted, returns just the first character.

#### 📝 Example

```dax
Month Short = 
UPPER(
    LEFT('Calendar Lookup'[Month Name], 3)
)
```

This expression takes the first 3 characters of the `Month Name` column in the `Calendar Lookup` table and converts them to uppercase — effectively creating a **3-letter month abbreviation** like `"JAN"`, `"FEB"`, etc.

---
