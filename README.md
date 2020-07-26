# JavaScript CheatSheet

---

---

> ## Variables

### JavaScript variables are containers for storing data values.

### JavaScript variables must be identified with unique names.

- ## Variables can be created in three way:-
  1. ### By using 'var' keyword (which is old way, do not use it that much).
  1. ### By using 'let' keyword.
  1. ### By using 'const' keyword.

---

### Remember some points while decalaring variables with 'let' keyword:-

1. ### you can initialize variable without assigning value to the variable.
1. ### you can redeclare variable value.

---

### Remember some points while decalaring variables with 'const' keyword:-

1. ### you can not initialize variable without assigning value to the variable.
1. ### you can redeclare variable value.
   - ### one suggestion use 'const' when you do not want to redeclare variable value.

---

### The general rules for constructing names for variables (unique identifiers) are:

- Names can contain letters, digits, underscores, and dollar signs.
- Names must begin with a letter.
- Names are case sensitive (v and V are different variables).
- Names can also begin with \$ and \_ .
- Reserved words (like let, const, for, etc.) cannot be used as names.

---

### **You can declare many variables in one statement.**

> #### Ex:-

```javascript
const javaScript = "behaviours",
  HTML = "content of webpage",
  CSS = "layout of webpage";
```

---

> ## Comments

### JavaScript comments can be used to explain JavaScript code, and to make it more readable.

- ### Comments can be declare in two ways:-
  1. ### Single Line Comment
  ```javascript
  //This is single line comment.
  ```
  2. ### Multiple Line Comment
  ```javascript
  /* 
    This is Multiple Line Comment.
    It can be used to explain the code in details manner.
   */
  ```
  - ### use comments to prevent execution of code for testing purpouse.

---

> ## Operators

- > ### JavaScript Arthemetic Operators

  | Operator | Description    |
  | -------- | -------------- |
  | +        | Addition       |
  | -        | Subtraction    |
  | \*       | Multiplication |
  | /        | Division       |
  | %        | Modulo         |
  | \*\*     | Exponentiation |
  | ++       | Increment      |
  | --       | Decrement      |

---

- > ### JavaScript Assignment Operators

  | Operator | Example   | Same As      |
  | -------- | --------- | ------------ |
  | =        | x = y     | x = y        |
  | +=       | x += y    | x = x + y    |
  | -=       | x -= y    | x = x - y    |
  | \*=      | x \*= y   | x = x \* y   |
  | /=       | x /= y    | x = x / y    |
  | %=       | x %= y    | x = x % y    |
  | \*\*=    | x \*\*= y | x = x \*\* y |

---

- > ### JavaScript Comparison Operators

  | Operator | Description                       |
  | -------- | --------------------------------- |
  | ==       | equal to                          |
  | ===      | equal value and equal type        |
  | !=       | not equal                         |
  | !==      | not equal value or not equal type |
  | >        | greater than                      |
  | <        | less than                         |
  | >=       | greater than or equal to          |
  | <=       | less than or equal to             |
  | ?        | ternary operator                  |

---

- > ### JavaScript Logical Operators

  | Operator | Description |
  | -------- | ----------- |
  | &&       | logical and |
  | \|\|     | logical or  |
  | !        | logical not |

---

- > ### JavaScript Bitwise Operators

  it will be Updated soon...
