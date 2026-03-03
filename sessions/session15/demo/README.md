# 🧩 JavaScript — Promises & Async/Await

## 📑 Index

- **Promises**
  - What a Promise is
    - Represents a future value
    - Handles asynchronous operations
  - Promise states
    - `pending`
    - `fulfilled`
    - `rejected`
  - `fetch()` returns a Promise
  - Consuming an existing Promise

- **then / catch**
  - `.then()`
    - Handles resolved value
    - Can return another Promise
    - Supports chaining
  - `.catch()`
    - Handles rejected state
    - Captures errors in the chain
  - `throw new Error()`
    - Manual error propagation
  - Limitations
    - Reduced readability in long chains
    - Nested logic can become harder to maintain

- **async / await**
  - `async`
    - Declares an asynchronous function
    - Automatically returns a Promise
  - `await`
    - Pauses execution until Promise resolves
    - Makes async flow appear synchronous
  - Improves readability
  - Cleaner sequential logic
  - Equivalent behavior to `.then()`

- **try / catch**
  - Structured error handling
  - Catches:
    - Network errors
    - JSON parsing errors
    - Manually thrown errors
  - Centralizes error control in one block

---

## 📚 Reference

- MDN — Promise:
  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise

- MDN — async function:
  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function

- MDN — Fetch API:
  https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API

---

## 🚀 Conceptual Focus

- `fetch()` already returns a **Promise** — no need to create one manually.
- `.then()` and `async/await` are two equivalent ways to consume Promises.
- `async/await` is generally preferred in professional codebases because:
  - It improves readability.
  - It simplifies error handling.
  - It scales better as logic grows.
- `try/catch` provides structured and centralized error handling.
- Choose syntax based on clarity and maintainability.

> [!TIP]
> If your async logic is sequential and involves multiple steps,
> prefer `async/await`.
> Use `.then()` when working directly with Promise composition or in legacy code.
