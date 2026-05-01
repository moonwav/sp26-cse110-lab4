# Part 1

1. Line 9 prints:
values added: 20


---

2. Line 13 prints:
final result: 20

---

3. You should not use `var` because it is function-scoped instead of block-scoped, which can lead to naming conflicts and bugs. It ignores block boundaries like `if` statements, making code harder to reason about and debug.

---

4. Line 9 prints:
values added: 20

---

5. Line 13 causes an error:

 `let` is block-scoped, so `result` only exists inside the `if` block and cannot be accessed outside of it.

---

6. Line 9 causes an error:

 `const result = 0` cannot be reassigned. The line `result = num1 + num2` tries to change its value, which is not allowed.

---

7. Line 13 also does not execute due to the earlier error.