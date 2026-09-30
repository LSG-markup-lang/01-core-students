# 🧩 JavaScript — Functions & Array Methods

## 📑 Index

- **Functions**

  - Function declaration
  - Function expression
  - Arrow functions
  - Parameters and return values
  - Differences in syntax and use cases

- **Callbacks**

  - What a callback function is
  - Passing functions as arguments
  - Executing dynamic behavior via callbacks
  - Why array methods use callbacks

- **Array Iteration & Transformation**

  - `forEach()`
    - Iterating over elements
    - No return value
  - `map()`
    - Transforming elements
    - Returns a new array
  - `filter()`
    - Selecting elements based on condition
    - Returns a new array
  - `find()`
    - Returns the first matching element
    - Stops after match
  - `reduce()`
    - Accumulator pattern
    - Produces a single value (number, object, array…)

- **Array Mutation Methods**

  - `push()` — add element at the end
  - `pop()` — remove last element
  - `reverse()` — reverse array order (mutates)

- **Array Copying & Extraction**

  - `slice(start, end)`
    - Returns a shallow copy
    - Does not mutate original array

- **String ↔ Array Conversion**

  - `split(separator)`
    - Converts string → array
  - `join(separator)`
    - Converts array → string

---

## 📚 Reference

- MDN — Array documentation:
  <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array>

---

## 🚀 Conceptual Focus

- Array methods rely on **callbacks**.
- Prefer declarative array methods over manual loops when transforming data.
- Distinguish clearly between:
  - Methods that **return new arrays**
  - Methods that **mutate the original array**
- `reduce()` generalizes many iteration patterns.

> [!TIP]
> Use `map`, `filter`, and `find` when the intent is clear.
> Use `reduce()` only when you need full control over how the result is accumulated.
