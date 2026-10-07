# Reflection – AI Number Program Lab

##  Student Name:
Thomas Rowe

##  GitHub Repository Link:
https://github.com/talrowe/cmsc115_unit8_lab2

## Iteration 1

What the AI code does:
- The method returns the first value in the array.

Tests passed/failed:
- `testSingleValue` passed.
- `testBasicArray`, `testNegativeNumbers`, and `testEmptyArray` failed.

What surprised you:
- The vague AI prompt produced code that was valid Java but did not match the intended behavior. It also failed on an empty array because it tried to access index 0.

Commit message:
- Iteration 1: AI-generated implementation

---

## Iteration 2

What changed:
- The method was changed to search through the array and return the largest integer.

What improved:
- `testBasicArray`, `testNegativeNumbers`, and `testSingleValue` now pass.

What still failed and why:
- `testEmptyArray` still failed because the method tries to access `values[0]`, which does not exist when the array is empty.

Commit message:
- Iteration 2: largest value implementation

---

## Iteration 3

Final behavior:
- The method returns the largest integer in the array. If the array is empty, it returns `Integer.MIN_VALUE`.

What was fixed:
- I added a check for an empty array before accessing the first element.

What you learned:
- I learned that a method can work correctly for normal inputs but still fail on edge cases such as an empty array.

Commit message:
- Iteration 3: final version passing all tests

---

## Final Reflection

- How did AI responses change across prompts?
  - The responses became more specific as the prompts became more specific. The first prompt produced a very basic implementation, while the later prompts clarified the intended behavior.

- How did testing affect your changes?
  - The JUnit tests showed exactly which cases were failing and helped guide each change until all tests passed.

- What did version control help you understand?
  - Git made it easy to track each iteration separately and see how the program changed from one version to the next.

---

## Final Reflection

- How did AI responses change across prompts?
- How did testing affect your changes?
- What did version control help you understand?