### 📌 `MID`

The `MID` function returns a specific number of characters from a text string, starting at a specified position.

#### 🔧 Syntax

```
MID(<text>, <start_position>, <num_of_characters>)
```

* `<text>`: The text string to extract from.
* `<start_position>`: Position to start extraction (1-based).
* `<num_of_characters>`: Number of characters to extract.

#### 📝 Example

```dax
MiddleText = 
MID('Product'[ProductCode], 4, 3)
```

This gets 3 characters starting from the 4th character in the `ProductCode`.

---
