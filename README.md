# MAC101-HW-2 FizzBuzz with User Input HW 2

## Objective

This quiz reinforces your understanding of:

* Declaring and using **integer variables**
* Taking **user input** with `cin`

---

## Task Description

Write a C++ program that performs the classic **FizzBuzz** logic — but with a **user-defined range**.

### Your program should:

1. Ask the user to enter a number (e.g., `int limit`).
2. Loop from `1` to `limit`.
3. For each number:

   * Print `Fizz` if the number is divisible by **3**.
   * Print `Buzz` if the number is divisible by **5**.
   * Print `FizzBuzz` if divisible by **both 3 and 5**.
   * Otherwise, print the number itself.

---

## Example Output
```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
```

---

## Starter Code

```cpp
#include <iostream>
using namespace std;

int main() {
    TODO: Create int var and cout and cin commands    


    return 0;
}
```

---

## Submission Instructions

* Save your file as **`main.cpp`**
* Test your program with several inputs (e.g., 10, 20, 50)
* Submit your `.cpp` file via Github

---

## Bonus Challenge (Extra Points)

Modify the program so that it:

* Takes **two inputs** — a `start` and `end` value — and loops from `start` to `end`
* Validates that `start < end`. If not, show an error message
