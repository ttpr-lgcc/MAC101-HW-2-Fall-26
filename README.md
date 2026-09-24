# MAC101-HW-2 FizzBuzz on a Single Number

## Objective

This HW reinforces your understanding of:

* Declaring and using **integer variables**
* Taking **user input** with `cin`
* Using **conditional statements** (`if`, `else if`, `else`)
* Using the **modulo operator** (`%`) to check for divisibility

---

## Task Description

Write a C++ program that performs the classic **FizzBuzz** logic on a **single user-inputted number**.

### Your program should:

1. Ask the user to enter a single whole number.
2. Evaluate that specific number:
   * Print `Fizz` if the number is divisible by **3**.
   * Print `Buzz` if the number is divisible by **5**.
   * Print `FizzBuzz` if divisible by **both 3 and 5** (e.g., 15).
   * Otherwise, print the number itself.

---

## Example Outputs

**Example 1:**
```text
Enter a number: 15
FizzBuzz
```

**Example 2:**
```text
Enter a number: 9
Fizz
```

**Example 3:**
```text
Enter a number: 10
Buzz
```

**Example 4:**
```text
Enter a number: 7
7
```

---

## Starter Code

```cpp
#include <iostream>
using namespace std;

int main() {
    // TODO: Create an integer variable
    // TODO: Use cout to ask the user for a number
    // TODO: Use cin to store their input
    // TODO: Write your if/else if/else logic here

    return 0;
}
```

---

## Submission Instructions

* Save your file as **`main.cpp`**
* Test your program with several inputs (e.g., 3, 5, 15, 7) to make sure all conditions work.
* Submit your `.cpp` file via Github

---

## Bonus Challenge (Extra Points)

Modify the program so that instead of just checking one number, it loops! 

* Take **two inputs** from the user — a `start` and `end` value.
* Use a loop (like a `for` or `while` loop) to check and print the FizzBuzz result for *every* number from `start` to `end`.
* Validate that `start < end`. If not, show an error message.
