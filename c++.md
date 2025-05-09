Here's a comprehensive **C++ documentation** in Markdown format following the same structured approach:

```markdown
# C++ Language Documentation

## 📜 Introduction
C++ is a high-performance, general-purpose programming language created by Bjarne Stroustrup in 1985 as an extension of C.

### 🌍 Key Features
- **Multi-paradigm**: OOP, procedural, generic, functional
- **System programming** capabilities
- **Direct memory access** via pointers
- **STL** (Standard Template Library)
- **ISO Standardized** (C++23 latest)

```cpp
// Hello World Example
#include <iostream>
using namespace std;

int main() {
    cout << "Hello World!" << endl;
    return 0;
}
```

## 🕰️ History of C++
| Year | Standard | Key Features |
|------|----------|--------------|
| 1985 | C++ 1.0  | First commercial release |
| 1998 | C++98    | First ISO standard |
| 2011 | C++11    | Auto, lambdas, move semantics |
| 2020 | C++20    | Concepts, ranges, coroutines |
| 2023 | C++23    | std::mdspan, stacktraces |

---

## ⚙️ Setup and Compilation

### Compiler Installation
```bash
# Linux
sudo apt install g++

# macOS
brew install llvm

# Windows (MSVC via Visual Studio)
```

### Compilation Process
```bash
g++ program.cpp -o output
./output
```

---

## 🧠 Core Concepts

### 1. Variables and Data Types
```cpp
// Primitive Types
int age = 30;              // 4 bytes
double price = 9.99;       // 8 bytes
char grade = 'A';          // 1 byte
bool is_valid = true;      // 1 byte

// Type Modifiers
unsigned int positive_only = 42;
long double extended_precision = 3.1415926535;
```

### 2. Control Structures
```cpp
