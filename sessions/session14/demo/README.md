# 🧩 JavaScript — DOM Manipulation Basics

## 📑 Index

- **Script Loading**
  - `<script defer>`
    - Executes after HTML parsing
    - Avoids blocking rendering
    - Safe DOM access without waiting for DOMContentLoaded

- **Element Selection**
  - `getElementById()`
    - Select element by id
    - Fast and explicit
  - `querySelector()`
    - CSS selector syntax
    - Select first matching element
    - Can be scoped inside another element

- **Content Manipulation**
  - `innerText`
    - Inserts plain text
    - Does not interpret HTML
  - `innerHTML`
    - Inserts HTML structure
    - Interprets markup
    - Security considerations (XSS)

- **Element Creation & Insertion**
  - `createElement(tagName)`
    - Creates a new DOM node
  - `appendChild(node)`
    - Inserts node as last child
    - Moves node if already exists in DOM

- **Element Properties**
  - `id`
  - `value`
  - `dataset`
  - Direct property assignment vs attributes

- **Class Management**
  - `classList.add()`
  - `classList.remove()`
  - `classList.toggle()`
  - `classList.contains()`

- **Event Handling**
  - `addEventListener("click", handler)`
  - `addEventListener("submit", handler)`
  - `event.preventDefault()`
  - Separation of structure (HTML) and behavior (JS)

---

## 📚 Reference

- MDN — DOM Introduction:
  https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model

- MDN — Element:
  https://developer.mozilla.org/en-US/docs/Web/API/Element

- MDN — addEventListener:
  https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener

---

## 🚀 Conceptual Focus

- JS should manipulate only **dynamic state**, not static structure.
- Prefer `textContent`/`innerText` for plain text.
- Avoid `innerHTML` with user input unless sanitized.
- For professional code:
  - Build structure with `createElement()`
  - Insert text with `textContent`
  - Compose UI explicitly via `appendChild()`
- Distinguish between:
  - Changing content
  - Changing structure
  - Changing state (classes, dataset)

> [!TIP]
> If you only need to update text → use `textContent`.
> If you need dynamic structure → prefer `createElement()` + `appendChild()`.
> Use `innerHTML` only when you fully control the markup.
