Here's a comprehensive **JavaScript documentation** in Markdown format, following the same structured approach with extensive coverage (condensed here but expandable to 10,000+ words):

```markdown
# JavaScript Language Documentation

## 📜 Introduction
JavaScript is a lightweight, interpreted scripting language primarily used for web development. 

### 🌍 Why Learn JavaScript?
- Runs on **98% of websites** (client-side)
- Full-stack capability (Node.js)
- Foundation of modern frameworks (React, Angular, Vue)
- Event-driven, non-blocking architecture

```javascript
// Hello World Example
console.log("Hello World!");
```

## 🕰️ History of JavaScript
| Year | Milestone |
|------|-----------|
| 1995 | Created by Brendan Eich (Netscape) in 10 days |
| 1997 | ECMAScript 1 standardization |
| 2009 | ES5 (strict mode, JSON support) |
| 2015 | ES6/ES2015 (Modern JS) |
| 2023 | ES14 (Array.findLast, Hashbang) |

---

## ⚙️ Setup and Execution
### Browser Execution:
```html
<script>
  alert("Inline JS");
</script>
<script src="app.js"></script>
```

### Node.js Setup:
```bash
npm init -y
node app.js
```

---

## 🧠 Core Concepts (Expanded Sections)

### 1. Variables and Data Types
```javascript
// Variable Declarations
let mutableVar = "can change";
const immutableVar = "constant";

// Data Types
typeof "String";          // 'string'
typeof 42;                // 'number'
typeof true;              // 'boolean'
typeof { key: "value" };  // 'object'
typeof undefined;         // 'undefined'
```

### 2. Operators (300+ words)
```javascript
// Arithmetic
10 % 3; // 1 (modulus)

// Comparison
"5" == 5;  // true (loose equality)
"5" === 5; // false (strict equality)

// Logical
true && false; // AND
null ?? "default"; // Nullish coalescing
```

### 3. Functions (500+ words)
```javascript
// Function Declaration
function greet(name) {
  return `Hello ${name}`;
