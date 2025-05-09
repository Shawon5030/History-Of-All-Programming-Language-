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
// If-Else with initializer
if (auto result = calculate(); result > 0) {
    cout << "Positive";
}

// Range-based for loop
for (const auto& num : {1, 2, 3}) {
    cout << num;
}
```

### 3. Functions
```cpp
// Function with default argument
int power(int base, int exp = 2) {
    return std::pow(base, exp);
}

// Lambda expression
auto greet = [](string name) { return "Hello " + name; };
```

### 4. Memory Management
```cpp
// Stack allocation
int stack_var = 10;

// Heap allocation
int* heap_var = new int(20);
delete heap_var;  // Manual deallocation

// Smart pointers (C++11+)
unique_ptr<int> smart_ptr = make_unique<int>(30);
```

---

## 🏗️ Object-Oriented Programming

### 1. Classes and Objects
```cpp
class Rectangle {
private:
    int width, height;
public:
    // Constructor
    Rectangle(int w, int h) : width(w), height(h) {}

    // Method
    int area() const { return width * height; }
};

Rectangle rect(10, 20);
cout << rect.area();
```

### 2. Inheritance
```cpp
class Shape {
public:
    virtual double area() const = 0;  // Pure virtual
};

class Circle : public Shape {
    double radius;
public:
    double area() const override {
        return 3.14 * radius * radius;
    }
};
```

### 3. Polymorphism
```cpp
Shape* shape = new Circle(5.0);
cout << shape->area();  // Dynamic dispatch
```

---

## 📦 Standard Template Library (STL)

### 1. Containers
```cpp
vector<int> nums = {1, 2, 3};
nums.push_back(4);

map<string, int> ages = {{"Alice", 30}, {"Bob", 25}};
```

### 2. Algorithms
```cpp
sort(nums.begin(), nums.end());
auto it = find(nums.begin(), nums.end(), 2);
```

### 3. Iterators
```cpp
for (auto it = nums.begin(); it != nums.end(); ++it) {
    cout << *it;
}
```

---

## ⚡ Advanced Features
