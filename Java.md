Here's the complete **Java documentation in a single, unified Markdown block** following the same style as your PHP documentation:

```markdown
# Java Language Documentation

## 📜 Introduction
Java is a high-level, object-oriented programming language developed by Sun Microsystems (now Oracle).

**Key Features**:
- Platform independent (Write Once, Run Anywhere)
- Automatic memory management (Garbage Collection)
- Strong type system
- Multi-threading support
- Rich standard library

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

## 🕰️ History of Java
| Year | Version | Significance |
|------|---------|--------------|
| 1995 | Java 1.0 | Initial release |
| 2004 | Java 5 | Generics, autoboxing |
| 2014 | Java 8 | Lambdas, Stream API |
| 2021 | Java 17 | LTS release |
| 2023 | Java 21 | Virtual threads |

## ⚙️ Setup and Installation
### Windows/Linux/macOS:
1. Download JDK from [Oracle](https://www.oracle.com/java/technologies/downloads/)
2. Set environment variables:
```bash
export JAVA_HOME=/path/to/jdk
export PATH=$JAVA_HOME/bin:$PATH
```
3. Verify:
```bash
java -version
```

## 🧠 Java Basics
### Syntax:
```java
// Single-line comment
/* Multi-line comment */
System.out.println("Hello"); // Output
```

## 🧮 Variables and Data Types
```java
String name = "John";      // String
int age = 30;              // Integer
double price = 9.99;       // Double
boolean isActive = true;   // Boolean
char grade = 'A';          // Character
int[] numbers = {1, 2, 3}; // Array
```

## 🔁 Control Structures
### If-Else:
```java
if (age > 18) {
    System.out.println("Adult");
} else {
    System.out.println("Minor");
}
```

### Loops:
```java
for (int i = 0; i < 5; i++) {
    System.out.println(i);
}

for (int num : numbers) {
    System.out.println(num);
