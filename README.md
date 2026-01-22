# ⚛️ Mastering React Components

This repository documents my journey learning how to build, structure, and manage **Components** in React. It includes code snippets, small projects, and notes on component-based architecture.

---

## 🧐 What is a Component?
In React, a component is an independent, reusable piece of UI. Think of them as custom HTML elements (like `<Button />` or `<Navbar />`) that manage their own rendering and logic. This repository focuses on **Functional Components**.



---

## 🛠️ Key Concepts Covered

### 1. JSX (JavaScript XML)
* Writing HTML-like syntax inside JavaScript.
* Embedding expressions with curly braces `{}`.
* Understanding the virtual DOM.

### 2. Props (Properties)
* Passing data from a parent component to a child component.
* Making components reusable and dynamic.
* Destructuring props for cleaner code.

### 3. State Management (useState)
* Understanding how data changes over time.
* Using the `useState` hook to make components interactive.
* Handling user inputs and events (e.g., `onClick`, `onChange`).

### 4. Component Lifecycle (useEffect)
* Handling side effects (fetching data, subscriptions).
* Understanding the dependency array `[]`.

---

## 💻 Code Examples

### 1. A Simple Functional Component (Props)
This component accepts a `name` prop and renders a greeting.

```jsx
import React from 'react';

const Greeting = ({ name }) => {
  return (
    <div className="greeting-card">
      <h1>Hello, {name}! 👋</h1>
      <p>Welcome to learning React.</p>
    </div>
  );
};

export default Greeting;
```
---
## 📚 Resources

* **[React Official Documentation](https://react.dev/)** – The new, interactive docs.
* **[React Components Guide](https://react.dev/learn/your-first-component)** – Specific guide on building components.
* **[Thinking in React](https://react.dev/learn/thinking-in-react)** – How to break a UI down into a component hierarchy.
