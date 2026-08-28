# Fix My Code Challenge - Tasks

This directory contains solutions for the individual debugging tasks in the challenge.

## Tasks

### 0. FizzBuzz (`0-fizzbuzz.py`)
- **Language:** Python
- **Problem:** Numbers divisible by 15 were incorrectly printing `Fizz` instead of `FizzBuzz` due to condition ordering.
- **Fix:** Placed `(i % 3 == 0 and i % 5 == 0)` check as the first condition.

### 1. Print square (`1-print_square.js`)
- **Language:** JavaScript (Node.js)
- **Problem:** `parseInt` used radix 16 instead of 10, causing incorrect size rendering for inputs.
- **Fix:** Fixed `parseInt` radix to `10`.

### 2. Sort (`2-sort.rb`)
- **Language:** Ruby
- **Problem:** Array insertion used `i - 1` instead of `i`, messing up element positions during insertion.
- **Fix:** Updated `result.insert(i, i_arg)` to insert elements at the correct position.

### 3. User password (`3-user.py`)
- **Language:** Python
- **Problem:** Property setter assigned to `_password` instead of `__password`, and hash comparison used `.upper()` instead of `.lower()`.
- **Fix:** Fixed private variable name and changed hash comparison casing to `.lower()`.

### 4. Double linked list (`4-delete_dnodeint/`)
- **Language:** C
- **Problem:** Invalid pointer assignments and memory management issues during node deletion in a doubly linked list.
- **Fix:** Rewrote pointer reassignment logic and proper memory cleanup in `delete_dnodeint_at_index.c`.
