# PHP Language Documentation

## 📜 Introduction
## 🕰️ History of PHP
## ⚙️ PHP Setup and Installation
## 🧠 PHP Basics
## 🧮 Variables and Data Types
## 🔁 Control Structures
## 🧱 Functions
## 📦 Arrays
## 📁 File Handling
## 🗃️ Object-Oriented Programming in PHP
## 🌐 Working with Forms and $_GET/$_POST
## 🧑‍💻 Session and Cookie Management
## 🗄️ PHP and MySQL Integration
## 🧰 Useful Built-in Functions
## ⚠️ Error Handling
## 🚦 Best Practices
## 📚 PHP Frameworks (Laravel, Symfony, etc.)
## 🧪 Sample Projects and Scripts
## 🧾 Summary and Resources
## 📜 Introduction

PHP (Hypertext Preprocessor) is a widely-used, open-source, general-purpose scripting language that is especially suited for web development and can be embedded into HTML.

Originally created by Rasmus Lerdorf in 1994, PHP has evolved into a powerful tool for creating dynamic and interactive websites. Unlike frontend technologies such as HTML, CSS, and JavaScript, PHP runs on the server-side. This means that it executes on the server and sends only the output (usually HTML) to the user's web browser.

### 🌍 Why Learn PHP?

PHP powers **over 75%** of websites that use server-side programming. Some of the most popular platforms and content management systems, such as **WordPress, Drupal, Joomla, Magento, and Laravel**, are either written in or heavily rely on PHP.

### 🧩 Key Features of PHP

- ✅ **Open Source:** Free to download and use.
- ⚡ **Fast Execution:** Interpreted quickly and optimized for web applications.
- 💡 **Easy to Learn:** Simple syntax similar to C and Perl.
- 🔗 **Cross-Platform:** Works on Windows, Linux, macOS, and other systems.
- 🌐 **Database Integration:** Excellent support for databases like MySQL, PostgreSQL, SQLite, etc.
- 🧰 **Rich Library Support:** Offers thousands of built-in functions.
- 🔒 **Security:** Provides tools and practices to build secure web apps.

### 🔍 What Can PHP Do?

PHP is capable of performing a wide variety of tasks, including:

- Generating dynamic page content
- Collecting form data
- Sending and receiving cookies
- Performing server-side file manipulation (create, open, read, write)
- Managing sessions
- Interacting with databases
- Creating full-scale web applications
- Accessing and processing REST APIs
- Building CMS and eCommerce platforms

### 🖥️ PHP in Action

PHP is most commonly embedded directly into HTML files. Here's a very simple PHP example:

```php
<!DOCTYPE html>
<html>
<head>
    <title>My First PHP Page</title>
</head>
<body>

<h1>Welcome!</h1>
<p>The current date and time is: <?php echo date("Y-m-d H:i:s"); ?></p>

</body>
</html>
## 🕰️ History of PHP

The history of PHP is a fascinating journey of how a simple set of scripts evolved into one of the most popular programming languages on the web.

### 🔹 1994 – The Birth of PHP

- **Rasmus Lerdorf**, a Danish-Canadian programmer, originally created PHP in 1994.
- It began as a set of **Common Gateway Interface (CGI)** scripts written in C that he used to track visits to his online résumé.
- He called it **"Personal Home Page Tools"** or **PHP Tools**.

### 🔹 1995 – PHP/FI (Form Interpreter)

- Rasmus released the source code to the public to allow others to use and contribute.
- PHP was rewritten into a more robust scripting language called **PHP/FI** (Personal Home Page / Forms Interpreter).
- PHP/FI could handle form data and communicate with databases.

### 🔹 1997 – PHP 3

- Developers **Zeev Suraski** and **Andi Gutmans** rewrote PHP and launched **PHP 3**.
- This version brought significant improvements, including:
  - A more powerful parser
  - Support for many databases and protocols
  - The name was changed to **"PHP: Hypertext Preprocessor"** (a recursive acronym).
- PHP 3 became the first version widely used by developers.

### 🔹 2000 – PHP 4

- Built on the **Zend Engine 1.0**, developed by Suraski and Gutmans.
- Improved performance and introduced features like:
  - Output buffering
  - Session handling
  - More robust configuration options

### 🔹 2004 – PHP 5

- Introduced **Zend Engine 2.0**.
- Marked a major shift in the language with full support for **Object-Oriented Programming (OOP)**.
- Added features like:
  - `try/catch` exception handling
  - Better support for XML
  - Integration with web services (SOAP)
  - PDO (PHP Data Objects) for database abstraction

### 🔹 2015 – PHP 7

- Skipped PHP 6 due to internal challenges and confusion.
- **PHP 7** brought huge performance boosts (up to 2x faster) using **Zend Engine 3.0**.
- Introduced features like:
  - Scalar type declarations (`int`, `string`, etc.)
  - Return type declarations
  - Null coalescing operator (`??`)
  - Spaceship operator (`<=>`)
  - Anonymous classes

### 🔹 2020 – PHP 8

- Introduced **Just-In-Time (JIT)** compilation for even better performance.
- Brought modern language features:
  - Attributes (Annotations)
  - Match expressions (like `switch`, but better)
  - Named arguments
  - Constructor property promotion
  - Union types
  - Nullsafe operator (`?->`)

### 📈 PHP Usage Today

- PHP continues to be a dominant force in web development.
- It powers popular platforms such as:
  - **WordPress** (used by 40%+ of websites)
  - **MediaWiki** (used by Wikipedia)
  - **Drupal**
  - **Laravel framework** (modern PHP applications)
- Supported by a massive global community and tons of open-source tools.

### 🧪 Fun Fact

> Did you know? The first PHP code was a single file that displayed who visited Rasmus Lerdorf's resume page!

---

🚀 Up next: **How to install and run PHP on your machine**, and a guide to setting up your development environment.
## ⚙️ PHP Setup and Installation

Before writing and running PHP code, you need to set up a development environment. PHP is cross-platform and can run on Windows, macOS, and Linux. Let’s go through the different options for installing and running PHP.

---

### 🛠️ Option 1: Installing PHP Manually (Command Line)

#### 🔹 Windows

1. Download the latest PHP zip from: https://www.php.net/downloads
2. Extract it to `C:\php`
3. Add the PHP directory to your **System PATH**:
   - Go to Environment Variables → Edit System Variables → Add `C:\php`
4. Open Command Prompt and type:
   ```bash
   php -v
# 🐘 PHP Learning Roadmap

## 🧠 PHP Basics
- Introduction to PHP
- PHP Syntax and Tags
- Comments in PHP
- PHP in HTML

## 🧮 Variables and Data Types
- Declaring Variables
- Data Types: String, Integer, Float, Boolean, Array, Object, NULL
- Type Juggling and Type Casting

## 🔁 Control Structures
- if, else, elseif
- switch
- while, do...while
