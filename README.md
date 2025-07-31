Decision-making is fundamental to intelligent programming in C++. By controlling the flow of execution based on specific conditions, programs can "think" and adapt to various inputs and states. C++ provides several constructs for this, including **`if-else`**, **`if-else-if` ladders**, and **`switch-case`** statements.

---

## `if-else` Statement

The `if-else` structure enables a program to make a binary decision. If a given condition evaluates to `true`, one block of code is executed; otherwise, an alternative block runs. This is ideal for simple, yes/no logic checks, allowing you to choose between two distinct paths.

**Example: Odd or Even Number Detection**

1.  Start
2.  Declare an integer variable `num`.
3.  Prompt the user to enter a number.
4.  Input the number into `num`.
5.  Check if `num % 2 == 0`.
    * If `true` $\rightarrow$ Display "Even".
    * Else $\rightarrow$ Display "Odd".
6.  End

---

## `if-else-if-else` Ladder

This structure expands decision-making to multiple conditions. The program evaluates conditions sequentially from top to bottom. As soon as one condition is `true`, its corresponding block executes, and the rest are skipped. The final `else` acts as a fallback if none of the preceding conditions match. This is perfect for layered logic where multiple outcomes are possible.

**Example: Largest of Three Numbers**

1.  Start
2.  Declare three integer variables: `a`, `b`, and `c`.
3.  Prompt the user to enter all three numbers.
4.  Input the values.
5.  Compare:
    * If `a > b && a > c` $\rightarrow$ Display `a` is largest.
    * Else if `b > c` $\rightarrow$ Display `b` is largest.
    * Else $\rightarrow$ Display `c` is largest.
6.  End

---

## `switch-case` Statement

The `switch-case` structure offers a cleaner alternative to multiple `if` checks when you're dealing with discrete values (like menu options or fixed states). It matches the value of a variable against predefined `case` labels and executes the code block associated with the matched `case`. A `default` case handles any value that doesn’t fit the listed options.

**Example: Vowel or Consonant Using ASCII**

1.  Start
2.  Declare a character variable `ch`.
3.  Prompt the user to enter a character.
4.  Input `ch`.
5.  Check if `ch` is between 'A'-'Z' or 'a'-'z' (ASCII 65–90 or 97–122).
    * If `true` $\rightarrow$ Check if `ch` is 'A', 'E', 'I', 'O', 'U' or their lowercase equivalents.
        * If `true` $\rightarrow$ Display "Vowel".
        * Else $\rightarrow$ Display "Consonant".
    * Else $\rightarrow$ Display "Not a letter".
6.  End

**Example: Month Selector Using `switch-case`**

1.  Start
2.  Declare an integer variable `choice`.
3.  Display menu options for months (1–12).
4.  Prompt the user to enter a choice.
5.  Input `choice`.
6.  Use `switch(choice)`:
    * Match `case`s from 1–12 to the corresponding month.
    * If no match $\rightarrow$ Display "Invalid Input".
7.  End

---

## Conclusion

Mastering decision-making structures is crucial for writing smarter, more dynamic code. Whether you're branching logic with `if-else`, scaling conditions with `if-else-if` ladders, or simplifying options via `switch-case`, these constructs equip you to guide the compiler line by line, decision by decision.
