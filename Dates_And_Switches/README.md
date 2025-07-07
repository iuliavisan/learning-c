# Dates and Switches

This project is a basic date converter that takes a date in the format `mm/dd/yyyy` and converts it into a more natural language style, such as:

# Dates and Switches

This is a beginner-level C project completed as part of the **Codecademy C programming track**.  
It focuses on string formatting, user input, and control flow using `switch` statements.

The program takes a user-input date in the format `mm/dd/yyyy` and prints it in a human-readable English style, such as:  
`January 1st, 2021`.

---

## Example

**Input:**
```
01/01/2021
```

**Output:**
```
January 1st, 2021
```

---

## How It Works

1. The user is prompted to enter a date in numeric form.
2. The `month` is interpreted using a `switch` statement.
3. The `day` is printed with the appropriate English suffix:
   - `1st`, `2nd`, `3rd`, and so on
   - This is done using combined `case` blocks in the `switch`
4. The `year` is appended at the end.

---

## Technologies Used

- Language: **C**
- Compiler: **GCC**
- Functions: `scanf`, `printf`
- Control flow: `switch`, `default`, grouped cases

---

## How to Compile & Run

```bash
gcc date.c
./a.out
```

Then input a date when prompted (e.g. `04/27/2022`).

---

## Personal Notes

This was one of my first mini-projects in C and helped me get comfortable with conditional logic and formatting user data. It was part of the hands-on training on Codecademy, and gave me a strong foundation for future work with user input and branching logic.
