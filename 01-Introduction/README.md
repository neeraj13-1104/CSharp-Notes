# What is C#?

**C# (pronounced "C-Sharp")** is a modern, object-oriented, and type-safe programming language developed by Microsoft. It is built on the .NET platform and is widely used for developing web applications, desktop applications, mobile apps, cloud services, games (using Unity), APIs, and enterprise software.

C# provides powerful features such as object-oriented programming (OOP), automatic memory management through the .NET runtime, strong type checking, exception handling, asynchronous programming, and a rich standard library. These features make it a reliable, secure, and scalable language for building high-performance applications.

## Key Features

* Object-Oriented Programming (OOP)
* Strongly Typed Language
* Cross-Platform Development with .NET
* Automatic Memory Management (Garbage Collection)
* Rich Standard Library
* Asynchronous Programming (`async` / `await`)
* Secure and Type-Safe
* Easy to Learn and Maintain

## Common Uses of C#

* Web Applications using ASP.NET Core
* RESTful Web APIs
* Desktop Applications (Windows Forms, WPF)
* Mobile Applications (.NET MAUI)
* Cloud Applications (Microsoft Azure)
* Game Development with Unity
* Enterprise Software Solutions

## Why Learn C#?

C# is one of the most popular programming languages for modern software development. It offers excellent performance, readability, scalability, and strong integration with the .NET ecosystem, making it an ideal choice for beginners as well as professional developers.

# Difference Between C++ and C#

| Feature            | C++                                                                              | C#                                                                                                              |
| ------------------ | -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| Developed By       | Bjarne Stroustrup                                                                | Microsoft                                                                                                       |
| First Released     | 1985                                                                             | 2002                                                                                                            |
| Programming Type   | Procedural + Object-Oriented                                                     | Fully Object-Oriented                                                                                           |
| Platform           | Platform-dependent (requires recompilation for different operating systems)      | Cross-platform with .NET                                                                                        |
| Compilation        | Compiles directly to native machine code                                         | Compiles to Intermediate Language (IL), then executed by the .NET Runtime (CLR)                                 |
| Memory Management  | Manual (using `new` and `delete`)                                                | Automatic (Garbage Collection)                                                                                  |
| Pointers           | Fully supported                                                                  | Limited support (`unsafe` code only)                                                                            |
| Performance        | Very high                                                                        | High, with CLR optimizations                                                                                    |
| Standard Library   | STL (Standard Template Library)                                                  | .NET Base Class Library (BCL)                                                                                   |
| Exception Handling | Supported                                                                        | Supported                                                                                                       |
| Development Speed  | Slower due to manual memory management                                           | Faster due to rich .NET libraries and automatic memory management                                               |
| Primary Use Cases  | Operating Systems, Game Engines, Embedded Systems, High-Performance Applications | Web Applications, APIs, Desktop Applications, Mobile Apps, Cloud Applications, Enterprise Software, Unity Games |

## Key Differences

* **C++** gives developers low-level control over memory and hardware, making it suitable for system programming and performance-critical applications.
* **C#** is built on the **.NET** platform and focuses on rapid application development, productivity, security, and maintainability.
* **C++** requires manual memory management using `new` and `delete`.
* **C#** uses **Garbage Collection (GC)** to automatically manage memory.
* **C++** compiles directly into machine code.
* **C#** compiles into **Intermediate Language (IL)**, which is executed by the **Common Language Runtime (CLR)**.
* **C++** is commonly used for operating systems, game engines, and embedded systems.
* **C#** is widely used for ASP.NET Core Web APIs, web applications, desktop software, cloud services, and Unity game development.

## Summary

* Choose **C++** when you need maximum performance, direct hardware access, or system-level programming.
* Choose **C#** when building modern applications such as Web APIs, enterprise software, desktop applications, cloud services, or Unity games with faster development and easier maintenance.



# History of C#

C# (pronounced **"C-Sharp"**) is a modern, object-oriented programming language developed by **Microsoft**. It was designed by **Anders Hejlsberg** and his team as part of the **.NET Framework** initiative.

The first version of C# was released in **2002** along with the **.NET Framework 1.0**. It was created to provide a simple, secure, and modern programming language for building Windows applications and enterprise software. Over the years, C# has evolved significantly, introducing powerful features such as Generics, LINQ, Async/Await, Pattern Matching, Records, and Nullable Reference Types.

Today, C# is one of the world's most popular programming languages and is widely used for developing web applications, Web APIs, desktop applications, cloud services, mobile applications, and games using Unity.

## Milestones

| Year  | Version | Major Features                                                               |
| ----- | ------- | ---------------------------------------------------------------------------- |
| 2002  | C# 1.0  | First release with .NET Framework 1.0                                        |
| 2005  | C# 2.0  | Generics, Nullable Types, Anonymous Methods                                  |
| 2007  | C# 3.0  | LINQ, Lambda Expressions, Extension Methods                                  |
| 2012  | C# 5.0  | Async and Await                                                              |
| 2017  | C# 7.0  | Pattern Matching, Tuples                                                     |
| 2019  | C# 8.0  | Nullable Reference Types, Default Interface Methods                          |
| 2020  | C# 9.0  | Records, Init-only Properties                                                |
| 2021  | C# 10.0 | Global Using Directives, File-Scoped Namespaces                              |
| 2022  | C# 11.0 | Raw String Literals, Generic Math                                            |
| 2023+ | C# 12.0 | Primary Constructors, Collection Expressions and other language improvements |

---

# Features of C#

* **Simple and Easy to Learn** – Clean syntax that is easy for beginners and professionals.
* **Object-Oriented Programming (OOP)** – Supports encapsulation, inheritance, polymorphism, and abstraction.
* **Strongly Typed** – Variables must have a defined data type, reducing programming errors.
* **Type Safe** – Prevents many common programming mistakes through compile-time type checking.
* **Cross-Platform** – Runs on Windows, Linux, and macOS using .NET.
* **Automatic Memory Management** – Uses the Garbage Collector (GC) to automatically free unused memory.
* **Rich Base Class Library (BCL)** – Provides thousands of built-in classes for file handling, networking, collections, security, and more.
* **Exception Handling** – Supports `try`, `catch`, `finally`, and `throw` for robust error handling.
* **Asynchronous Programming** – Uses `async` and `await` for efficient non-blocking operations.
* **Language Integrated Query (LINQ)** – Allows querying data using a simple and readable syntax.
* **Interoperability** – Can work with other .NET languages and external libraries.
* **Secure** – Includes built-in features for type safety and runtime security.
* **Scalable** – Suitable for both small applications and large enterprise systems.
* **High Performance** – Optimized by the .NET Runtime (CLR) with features such as Just-In-Time (JIT) compilation.
* **Wide Range of Applications** – Used for Web Applications, ASP.NET Core Web APIs, Desktop Applications, Mobile Apps (.NET MAUI), Cloud Services (Azure), and Unity Game Development.

## Summary

C# is a modern, powerful, and versatile programming language that combines simplicity with high performance. Its strong integration with the .NET platform, rich libraries, and continuous improvements make it one of the best choices for developing modern software applications.



# Variables in C#

A **variable** is a named memory location used to store data. The value stored in a variable can be changed during program execution.

## Syntax

```csharp
dataType variableName = value;
```

## Examples

```csharp
int age = 22;
string name = "Neeraj";
double salary = 45000.50;
char grade = 'A';
bool isActive = true;
```

## Variable Naming Rules

* A variable name must start with a letter or underscore (`_`).
* It cannot start with a number.
* It cannot contain spaces.
* It cannot use C# keywords (unless prefixed with `@`).
* Variable names are **case-sensitive** (`Age` and `age` are different).

### Valid Variable Names

```csharp
int age;
string studentName;
double totalMarks;
bool isLoggedIn;
```

### Invalid Variable Names

```csharp
int 1age;          // Cannot start with a number
string student name; // Contains a space
int class;         // 'class' is a keyword
```

---

# Data Types in C#

A **data type** specifies the type of value that a variable can store. C# is a **strongly typed** language, which means every variable must have a defined data type.

## Common Value Types

| Data Type | Size     | Range / Description                     | Example                        |
| --------- | -------- | --------------------------------------- | ------------------------------ |
| `byte`    | 1 Byte   | 0 to 255                                | `byte age = 25;`               |
| `sbyte`   | 1 Byte   | -128 to 127                             | `sbyte value = -10;`           |
| `short`   | 2 Bytes  | -32,768 to 32,767                       | `short marks = 500;`           |
| `ushort`  | 2 Bytes  | 0 to 65,535                             | `ushort count = 1000;`         |
| `int`     | 4 Bytes  | -2,147,483,648 to 2,147,483,647         | `int salary = 50000;`          |
| `uint`    | 4 Bytes  | 0 to 4,294,967,295                      | `uint population = 1000000;`   |
| `long`    | 8 Bytes  | Very large integers                     | `long distance = 9000000000L;` |
| `ulong`   | 8 Bytes  | Very large positive integers            | `ulong number = 100000000UL;`  |
| `float`   | 4 Bytes  | Single-precision decimal                | `float pi = 3.14F;`            |
| `double`  | 8 Bytes  | Double-precision decimal                | `double price = 199.99;`       |
| `decimal` | 16 Bytes | High-precision decimal (financial data) | `decimal amount = 9999.99M;`   |
| `char`    | 2 Bytes  | Single Unicode character                | `char grade = 'A';`            |
| `bool`    | 1 Byte   | `true` or `false`                       | `bool isActive = true;`        |

---

## Reference Types

| Data Type   | Description                             | Example                      |
| ----------- | --------------------------------------- | ---------------------------- |
| `string`    | Stores text                             | `string name = "Neeraj";`    |
| `object`    | Base type of all C# types               | `object value = 100;`        |
| `dynamic`   | Type determined at runtime              | `dynamic data = "Hello";`    |
| `array`     | Stores multiple values of the same type | `int[] numbers = {1,2,3};`   |
| `class`     | User-defined reference type             | `Student s = new Student();` |
| `interface` | Defines a contract for classes          | `IStudent student;`          |

---

## Example Program

```csharp
using System;

class Program
{
    static void Main()
    {
        int age = 22;
        string name = "Neeraj";
        double salary = 45000.50;
        char grade = 'A';
        bool isActive = true;

        Console.WriteLine($"Name: {name}");
        Console.WriteLine($"Age: {age}");
        Console.WriteLine($"Salary: {salary}");
        Console.WriteLine($"Grade: {grade}");
        Console.WriteLine($"Active: {isActive}");
    }
}
```

## Output

```
Name: Neeraj
Age: 22
Salary: 45000.5
Grade: A
Active: True
```

---

# Summary

* A **Variable** is a named memory location used to store data.
* A **Data Type** defines what type of data a variable can store.
* C# supports **Value Types** (such as `int`, `char`, `bool`, `double`) and **Reference Types** (such as `string`, `object`, `class`, and `array`).
* Every variable in C# must be declared with a data type before it is used.




# Stack and Heap Memory in C#

Memory management in C# is primarily divided into two areas: **Stack Memory** and **Heap Memory**. Understanding these memory areas is essential for learning value types, reference types, object creation, and garbage collection.

## Stack Memory

The **Stack** is a fast memory area used to store:

* Local variables
* Method parameters
* Value types (`int`, `char`, `bool`, `double`, etc.)
* References (memory addresses) of reference type objects

### Characteristics of Stack Memory

* Stores local variables and method execution information.
* Memory allocation and deallocation are automatic.
* Faster than heap memory.
* Uses **LIFO (Last In, First Out)** order.
* Memory is released automatically when a method finishes execution.

### Example

```csharp
int age = 22;
double salary = 45000.50;
char grade = 'A';
```

These variables are stored directly in the **Stack**.

---

# Heap Memory

The **Heap** is a memory area used to store **reference type objects** created using the `new` keyword.

### Characteristics of Heap Memory

* Stores objects and dynamically allocated data.
* Used for reference types such as classes, arrays, and strings.
* Memory allocation is slower than the stack.
* Memory is automatically cleaned by the **Garbage Collector (GC)** when objects are no longer referenced.

### Example

```csharp
Student student = new Student();
```

The `Student` object is created in the **Heap**, while the variable `student` stores only the reference (memory address) in the **Stack**.

---

# Stack vs Heap

| Stack                                    | Heap                                  |
| ---------------------------------------- | ------------------------------------- |
| Stores local variables                   | Stores objects and dynamic data       |
| Faster memory allocation                 | Slower memory allocation              |
| Automatically managed                    | Managed by the Garbage Collector (GC) |
| Stores value types and object references | Stores reference type objects         |
| Uses LIFO (Last In, First Out)           | No LIFO structure                     |

---

# Memory Illustration

```text
Stack                          Heap
------                         -----------------
age = 22
student ---------------------> Student Object
                               Name = "Neeraj"
                               Age = 22
```

In this example:

* `age` is stored directly in the **Stack**.
* `student` stores only the memory address in the **Stack**.
* The actual `Student` object is stored in the **Heap**.

## Summary

* **Stack** stores local variables, method information, value types, and references.
* **Heap** stores objects created using the `new` keyword.
* Value types store their actual values in the stack.
* Reference types store their objects in the heap, while their references are stored in the stack.
* The .NET Garbage Collector automatically removes unused objects from the heap.


# Stack and Heap Memory in C#

In C#, memory is mainly divided into two parts:

* **Stack Memory**
* **Heap Memory**

Understanding these two memory areas helps you learn **Value Types** and **Reference Types**.

---

# Stack Memory

**Stack** is a fast memory area used to store:

* Local variables
* Method parameters
* Value types (`int`, `char`, `bool`, `double`, etc.)
* References (addresses) of objects

### Example

```csharp
int age = 22;
char grade = 'A';
bool isActive = true;
```

**Memory**

```text
Stack

age = 22
grade = 'A'
isActive = true
```

Here, the actual values are stored directly in the **Stack**.

---

# Heap Memory

**Heap** is used to store **objects** created using the `new` keyword.

### Example

```csharp
class Student
{
    public string Name;
}

Student student = new Student();
```

**Memory**

```text
Stack                     Heap

student ---------------> Student Object
                          Name = null
```

Here:

* `student` stores only the **reference (address)** in the **Stack**.
* The actual `Student` object is stored in the **Heap**.

---

# Value Type Example

```csharp
int a = 10;
int b = a;

b = 20;
```

**Memory**

```text
Stack

a = 10

b = 20
```

**Output**

```text
a = 10
b = 20
```

**Explanation**

`b` receives a copy of `a`. Changing `b` does **not** affect `a`.

---

# Reference Type Example

```csharp
class Student
{
    public string Name;
}

Student s1 = new Student();
Student s2 = s1;

s2.Name = "Neeraj";

Console.WriteLine(s1.Name);
```

**Memory**

```text
Stack

s1 -----------┐
              │
              ▼
s2 -----------┘

Heap

Student Object
Name = "Neeraj"
```

**Output**

```text
Neeraj
```

**Explanation**

Both `s1` and `s2` point to the **same object**. Changing the object through one reference is visible through the other.

---

# Stack vs Heap

| Stack                                                   | Heap                                            |
| ------------------------------------------------------- | ----------------------------------------------- |
| Stores value types                                      | Stores objects                                  |
| Stores local variables                                  | Stores reference type objects                   |
| Faster                                                  | Slower than Stack                               |
| Memory is released automatically after method execution | Memory is managed by the Garbage Collector (GC) |

---

# Key Points

* **Stack** stores actual values for **Value Types**.
* **Heap** stores actual objects for **Reference Types**.
* The `new` keyword creates an object in the **Heap**.
* Reference variables store only the object's **memory address**.



# Type Casting in C#

**Type Casting** is the process of converting a value from one data type to another.

There are two types of type casting in C#:

1. **Implicit Casting (Automatic)**
2. **Explicit Casting (Manual)**

---

# 1. Implicit Casting (Automatic)

Implicit casting is performed automatically by the compiler when there is **no risk of data loss**.

### Example

```csharp
int number = 100;
double value = number;

Console.WriteLine(number);
Console.WriteLine(value);
```

### Output

```text
100
100
```

### Explanation

* `int` is automatically converted to `double`.
* No data is lost during the conversion.

---

# 2. Explicit Casting (Manual)

Explicit casting is performed manually by the programmer when there is a **possibility of data loss**.

### Example

```csharp
double value = 99.99;
int number = (int)value;

Console.WriteLine(number);
```

### Output

```text
99
```

### Explanation

* `99.99` is converted to `99`.
* The decimal part (`.99`) is removed.

---

# Using Convert Class

The `Convert` class is used to convert one data type to another.

### Example

```csharp
string age = "22";

int result = Convert.ToInt32(age);

Console.WriteLine(result);
```

### Output

```text
22
```

---

# Using Parse()

The `Parse()` method converts a string into another data type.

### Example

```csharp
string number = "150";

int value = int.Parse(number);

Console.WriteLine(value);
```

### Output

```text
150
```

---

# Using TryParse()

`TryParse()` safely converts a string without throwing an exception for invalid input.

### Example

```csharp
string input = "123";

if (int.TryParse(input, out int result))
{
    Console.WriteLine(result);
}
else
{
    Console.WriteLine("Invalid Number");
}
```

### Output

```text
123
```

---

# Parse() vs Convert() vs TryParse()

| Feature             | Parse()          | Convert.ToInt32()   | TryParse()      |
| ------------------- | ---------------- | ------------------- | --------------- |
| Input Type          | String           | Any compatible type | String          |
| Invalid Input       | Throws Exception | Throws Exception    | Returns `false` |
| Null Value          | Throws Exception | Returns `0`         | Returns `false` |
| Safe for User Input | ❌ No             | ⚠️ Limited          | ✅ Yes           |

---

# Implicit vs Explicit Casting

| Implicit Casting          | Explicit Casting          |
| ------------------------- | ------------------------- |
| Automatic conversion      | Manual conversion         |
| No data loss              | Data loss may occur       |
| Safe conversion           | Programmer is responsible |
| Example: `int` → `double` | Example: `double` → `int` |

---

# Common Conversion Methods

| Method                | Description                       |
| --------------------- | --------------------------------- |
| `Convert.ToInt32()`   | Converts to `int`                 |
| `Convert.ToDouble()`  | Converts to `double`              |
| `Convert.ToDecimal()` | Converts to `decimal`             |
| `Convert.ToBoolean()` | Converts to `bool`                |
| `Convert.ToString()`  | Converts to `string`              |
| `int.Parse()`         | Converts a string to `int`        |
| `double.Parse()`      | Converts a string to `double`     |
| `int.TryParse()`      | Safely converts a string to `int` |

---

# ⭐ Interview Tips

### 1. What is Type Casting?

> Type Casting is the process of converting one data type into another.

---

### 2. Why is `int` → `double` Implicit?

Because there is **no data loss**.

```csharp
int num = 100;
double value = num;
```

---

### 3. Why is `double` → `int` Explicit?

Because the decimal part may be lost.

```csharp
double value = 99.99;
int num = (int)value;
```

Output

```text
99
```

---

### 4. Difference between Parse(), Convert(), and TryParse()

* `Parse()` throws an exception for invalid input.
* `Convert.ToInt32(null)` returns `0`.
* `TryParse()` returns `false` instead of throwing an exception.

---

### 5. Which method is best for user input?

✅ **`TryParse()`**

Reason:

* Prevents application crashes.
* Handles invalid input safely.

---

### 6. Does Explicit Casting always lose data?

No.

It **may** lose data depending on the conversion.

Example:

```csharp
double d = 10.0;
int i = (int)d;
```

No data is lost.

But

```csharp
double d = 10.75;
int i = (int)d;
```

Output

```text
10
```

The decimal part is removed.

---

# ❓Common Interview Questions

### Q1. What is Type Casting?

**Answer:** Type Casting is the process of converting one data type into another.

---

### Q2. What are the types of Type Casting?

* Implicit Casting
* Explicit Casting

---

### Q3. What is the difference between Implicit and Explicit Casting?

* Implicit casting is automatic and does not cause data loss.
* Explicit casting is manual and may cause data loss.

---

### Q4. What is the difference between Parse(), Convert(), and TryParse()?

* `Parse()` throws an exception for invalid input.
* `Convert()` returns `0` for `null`.
* `TryParse()` safely returns `true` or `false`.

---

### Q5. Which method should be used for user input?

**Answer:** `TryParse()`

---

# Summary

* Type Casting converts one data type into another.
* Implicit Casting is automatic and safe.
* Explicit Casting is manual and may lose data.
* Use `Convert()` for general conversions.
* Use `Parse()` when the input is guaranteed to be valid.
* Use `TryParse()` for user input because it is the safest option.


# C# Fundamentals

## Table of Contents

* What is C#?
* CLR (Common Language Runtime)
* CTS (Common Type System)
* CLS (Common Language Specification)
* IL Code (Intermediate Language)
* JIT Compiler (Just-In-Time Compiler)
* .NET Framework vs .NET Core vs .NET
* Summary

---

# What is C#?

**C# (pronounced "C-Sharp")** is a modern, object-oriented, strongly typed programming language developed by **Microsoft**. It is used with the **.NET Platform** to build Web Applications, Web APIs, Desktop Applications, Mobile Apps, Cloud Applications, and Unity Games.

### Example

```csharp
using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("Hello, World!");
    }
}
```

### Real-Life Example

Think of **C#** as the language you use to write instructions.

Just like English is used to communicate with people, **C# is used to communicate with the .NET Platform**.

### Key Features

* Object-Oriented Programming (OOP)
* Strongly Typed
* Type Safe
* Cross-Platform
* Automatic Memory Management
* Rich Base Class Library
* High Performance
* Secure

---

## ⭐ Interview Tips

* C# is a **Programming Language**.
* .NET is a **Development Platform**.
* C# was developed by **Microsoft**.
* Lead Designer: **Anders Hejlsberg**.
* First Released: **2002**.

---

## ❓Interview Questions

### Q1. What is C#?

**Answer:**

C# is a modern, object-oriented, strongly typed programming language developed by Microsoft for building applications on the .NET platform.

---

# CLR (Common Language Runtime)

CLR is the **execution engine** of the .NET Platform.

It is responsible for running .NET applications.

### Responsibilities of CLR

* Memory Management
* Garbage Collection
* Security
* Exception Handling
* JIT Compilation
* Thread Management

### Working

```
C# Code

↓

IL Code

↓

CLR

↓

Machine Code

↓

CPU
```

### Real-Life Example

Think of CLR as a **Car Engine**.

Without the engine, the car cannot run.

Similarly,

Without CLR,

A C# application cannot execute.

---

## ⭐ Interview Tips

Remember this line:

> CLR executes .NET applications and provides runtime services.

Runtime Services:

* Memory Management
* Garbage Collection
* Security
* Exception Handling
* JIT Compiler

---

## ❓Interview Questions

### Q1. What is CLR?

**Answer**

CLR (Common Language Runtime) is the execution engine of .NET that manages memory, security, exception handling, garbage collection, and JIT compilation while executing applications.

---

### Q2. What services are provided by CLR?

* Memory Management
* Garbage Collection
* Security
* Exception Handling
* JIT Compilation

---

# CTS (Common Type System)

CTS stands for **Common Type System**.

It defines all the data types that can be used in .NET languages.

Example:

```
int

string

double

bool
```

Whether you write code in C#, VB.NET, or F#, all languages follow the same type system.

### Real-Life Example

Think of CTS as a **dictionary** that defines standard data types for all .NET languages.

---

## ⭐ Interview Tips

Remember:

CTS defines **Types**.

---

## ❓Interview Questions

### Q1. What is CTS?

**Answer**

CTS (Common Type System) defines the data types that all .NET languages use, ensuring type compatibility between languages.

---

### Q2. Why is CTS required?

Because it allows different .NET languages to use the same data types and work together.

---

# CLS (Common Language Specification)

CLS stands for **Common Language Specification**.

CLS defines a common set of rules that every .NET language should follow.

This allows different .NET languages to communicate with each other.

### Example

A class written in C#

can be used inside

VB.NET

because both follow CLS rules.

---

### Real-Life Example

Think of CLS as **traffic rules**.

Every driver follows the same rules.

Similarly,

Every .NET language follows CLS rules.

---

## ⭐ Interview Tips

Remember:

CTS → Types

CLS → Rules

---

## ❓Interview Questions

### Q1. What is CLS?

**Answer**

CLS is a set of rules that all .NET languages follow to ensure language interoperability.

---

### Q2. Difference between CTS and CLS?

| CTS                         | CLS                             |
| --------------------------- | ------------------------------- |
| Defines Data Types          | Defines Rules                   |
| Common Type System          | Common Language Specification   |
| Used for Type Compatibility | Used for Language Compatibility |

---

# IL Code (Intermediate Language)

IL stands for **Intermediate Language**.

It is also called

* MSIL
* CIL

When C# code is compiled,

it is first converted into IL Code.

### Flow

```
C#

↓

IL Code

↓

CLR
```

IL is **CPU-independent**.

It cannot run directly.

It must be converted into Machine Code.

---

### Example

```
C# Source Code

↓

Compiler

↓

IL (.exe/.dll)
```

---

## ⭐ Interview Tips

Remember:

Compiler converts

C#

↓

IL

---

## ❓Interview Questions

### Q1. What is IL Code?

**Answer**

IL (Intermediate Language) is the intermediate code generated by the C# compiler before execution.

---

### Q2. Why is IL required?

It makes .NET applications platform-independent until runtime.

---

# JIT Compiler (Just-In-Time Compiler)

JIT stands for **Just-In-Time Compiler**.

It converts IL Code into Machine Code.

### Flow

```
C#

↓

IL

↓

JIT

↓

Machine Code

↓

CPU
```

### Real-Life Example

Imagine IL is a document written in English.

The CPU understands only Machine Language.

JIT works like a translator.

---

## ⭐ Interview Tips

Remember:

Compiler

C#

↓

IL

JIT

IL

↓

Machine Code

---

## ❓Interview Questions

### Q1. What is JIT Compiler?

**Answer**

JIT Compiler converts Intermediate Language (IL) into Machine Code during program execution.

---

### Q2. What is the difference between Compiler and JIT?

| Compiler               | JIT                         |
| ---------------------- | --------------------------- |
| Converts C# to IL      | Converts IL to Machine Code |
| Runs during Build Time | Runs during Runtime         |

---

# .NET Framework vs .NET Core vs .NET

| Feature             | .NET Framework      | .NET Core                 | .NET                |
| ------------------- | ------------------- | ------------------------- | ------------------- |
| Release             | 2002                | 2016                      | 2020                |
| Platform            | Windows Only        | Cross Platform            | Cross Platform      |
| Performance         | Good                | Better                    | Best                |
| Open Source         | No                  | Yes                       | Yes                 |
| Current Development | Maintenance Mode    | Merged into .NET          | Active Development  |
| Recommended         | Legacy Applications | Older Cross-Platform Apps | Modern Applications |

---

### Real-Life Example

Think of it like mobile phones.

Old Phone

↓

.NET Framework

Smartphone

↓

.NET Core

Latest Flagship Phone

↓

.NET

---

## ⭐ Interview Tips

* .NET Framework → Windows Only
* .NET Core → Cross Platform
* .NET (5+) → Modern Unified Platform
* New applications should use **.NET**.

---

## ❓Interview Questions

### Q1. Difference between .NET Framework and .NET Core?

* Framework supports Windows only.
* .NET Core supports Windows, Linux, and macOS.

---

### Q2. Should we use .NET Framework today?

Only for maintaining older applications.

For new projects,

Microsoft recommends **.NET**.

---

# Complete Architecture

```
C# Source Code

        │

        ▼

C# Compiler

        │

        ▼

Intermediate Language (IL)

        │

        ▼

Common Language Runtime (CLR)

 ├── Memory Management

 ├── Garbage Collection

 ├── Security

 ├── Exception Handling

 └── JIT Compiler

        │

        ▼

Machine Code

        │

        ▼

CPU
```

---

# Summary

| Topic          | Description                                     |
| -------------- | ----------------------------------------------- |
| C#             | Programming Language                            |
| CLR            | Executes .NET Applications                      |
| CTS            | Defines Common Data Types                       |
| CLS            | Defines Common Rules                            |
| IL             | Intermediate Language generated by the Compiler |
| JIT            | Converts IL into Machine Code                   |
| .NET Framework | Windows-only platform                           |
| .NET Core      | Cross-platform platform (pre-.NET 5)            |
| .NET           | Modern unified cross-platform platform          |



# CLR (Common Language Runtime)

## What is CLR?

**CLR (Common Language Runtime)** is the **execution engine** of the .NET platform. It is responsible for executing .NET applications and providing various runtime services.

It acts as a bridge between the **Intermediate Language (IL)** and the **Operating System**.

---

# CLR Architecture

```text
                    C# Source Code
                           │
                           ▼
                   C# Compiler (csc)
                           │
                           ▼
              Intermediate Language (IL)
                    (.exe / .dll)
                           │
                           ▼
          ┌─────────────────────────────────┐
          │              CLR                │
          │---------------------------------│
          │ • JIT Compiler                  │
          │ • Garbage Collector             │
          │ • Memory Management             │
          │ • Exception Handling            │
          │ • Security                      │
          │ • Thread Management             │
          └─────────────────────────────────┘
                           │
                           ▼
                  Native Machine Code
                           │
                           ▼
                           CPU
```

---

# Responsibilities of CLR

* Executes .NET applications
* Converts IL into Machine Code using the JIT Compiler
* Automatically manages memory
* Removes unused objects using the Garbage Collector
* Handles exceptions
* Provides security
* Manages threads

---

# Example

```csharp
using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("Hello World");
    }
}
```

### Execution Flow

```text
C# Code
   │
   ▼
Compiler
   │
   ▼
IL Code
   │
   ▼
CLR
   │
   ▼
Machine Code
   │
   ▼
CPU
```

---

# Real-Life Example

Think of **CLR as the engine of a car**.

* C# Code → Driver
* CLR → Engine
* CPU → Wheels

Without the engine, the car cannot move.

Similarly, without the CLR, a .NET application cannot execute.

---

# ⭐ Interview Tips

* CLR stands for **Common Language Runtime**.
* CLR is the **execution engine** of .NET.
* CLR executes **IL Code**, not C# source code directly.
* CLR uses the **JIT Compiler** to convert IL into Machine Code.
* CLR provides Memory Management, Garbage Collection, Security, Exception Handling, and Thread Management.

---

# ❓Interview Questions

### 1. What is CLR?

**Answer:**

CLR (Common Language Runtime) is the execution engine of the .NET platform. It executes .NET applications and provides runtime services such as memory management, garbage collection, security, exception handling, thread management, and JIT compilation.

---

### 2. What are the responsibilities of CLR?

* Memory Management
* Garbage Collection
* JIT Compilation
* Security
* Exception Handling
* Thread Management

---

### 3. Does CLR execute C# code directly?

**Answer:**

No.

The C# Compiler first converts C# code into IL (Intermediate Language). CLR then loads the IL code and uses the JIT Compiler to convert it into Machine Code.

---

### 4. Why is CLR important?

**Answer:**

CLR manages the execution of .NET applications, automatically handles memory, improves security, manages exceptions, and converts IL into Machine Code.

---

### 5. What is the difference between CLR and JIT?

| CLR                        | JIT                          |
| -------------------------- | ---------------------------- |
| Execution Engine           | Compiler                     |
| Executes .NET applications | Converts IL to Machine Code  |
| Provides runtime services  | Used by CLR during execution |

---

### 6. Can a .NET application run without CLR?

**Answer:**

No. Every .NET application requires the CLR to execute.

---

### 7. Which runtime services are provided by CLR?

* Memory Management
* Garbage Collection
* Security
* Exception Handling
* Thread Management
* JIT Compilation




# CLR Runtime Services 

The **Common Language Runtime (CLR)** provides many runtime services that help execute .NET applications efficiently and safely.

The major runtime services are:

* Memory Management
* Garbage Collection
* Security

---

# 1. Memory Management

## What is Memory Management?

Memory Management is the process of **allocating**, **using**, and **releasing** memory while a program is running.

The CLR automatically manages memory for .NET applications.

Developers do **not** need to manually allocate or free memory.

---

## Why is Memory Management Required?

Without memory management:

* Memory can become full.
* Applications become slow.
* Memory leaks may occur.
* The application may crash.

---

## How Memory Management Works

```text
Object Created
       │
       ▼
CLR Allocates Memory
       │
       ▼
Object is Used
       │
       ▼
Object Becomes Unused
       │
       ▼
Garbage Collector Frees Memory
```

---

## Example

```csharp
class Student
{
    public string Name;
}

Student s = new Student();
```

### Explanation

When the object is created,

```csharp
new Student();
```

CLR allocates memory in the **Heap**.

---

## Real-Life Example

Imagine a **hotel**.

When a customer arrives,

the receptionist assigns a room.

When the customer leaves,

the room becomes available for another customer.

Similarly,

CLR allocates memory when an object is created and releases it when the object is no longer needed.

---

## Diagram

```text
Student s = new Student();

        │

        ▼

CLR

        │

        ▼

Heap Memory

+----------------+
| Student Object |
+----------------+
```

---

## ⭐ Interview Tips

* CLR manages memory automatically.
* Objects are stored in the Heap.
* Developers do not manually free memory.
* Memory is released by the Garbage Collector.

---

## ❓Interview Questions

### What is Memory Management?

Memory Management is the process of allocating and releasing memory while a program is executing.

---

### Who manages memory in .NET?

The **CLR** manages memory.

---

### Why is Memory Management important?

It improves performance and prevents memory leaks.

---

# 2. Garbage Collection (GC)

## What is Garbage Collection?

Garbage Collection is the automatic process of removing **unused objects** from memory.

It is handled by the **Garbage Collector (GC)**.

---

## Why is Garbage Collection Required?

Suppose you create many objects.

Some objects are no longer used.

If they remain in memory,

memory usage continuously increases.

Garbage Collection removes these unused objects automatically.

---

## Working

```text
Object Created

      │

      ▼

Object Used

      │

      ▼

Object No Longer Used

      │

      ▼

Garbage Collector Removes It

      │

      ▼

Memory Becomes Free
```

---

## Example

```csharp
class Student
{
}

Student s = new Student();

s = null;
```

### Explanation

The object still exists in the Heap.

However,

no variable references it anymore.

Later,

the Garbage Collector automatically removes it.

---

## Real-Life Example

Imagine your room.

Books,

empty bottles,

paper,

old newspapers...

When they are no longer useful,

your mother throws them away.

Exactly the same,

Garbage Collector removes unused objects from memory.

---

## Diagram

```text
Heap

+----------------+
| Student Object |
+----------------+
        ▲
        │
     s = null

        │

        ▼

Garbage Collector

        │

        ▼

Memory Released
```

---

## ⭐ Interview Tips

* GC removes unused objects.
* GC works only on Heap memory.
* Developers do not manually delete objects.
* GC runs automatically.

---

## ❓Interview Questions

### What is Garbage Collection?

Garbage Collection is the automatic process of removing unused objects from Heap memory.

---

### Does GC remove Stack Memory?

No.

GC works only with Heap memory.

---

### Who performs Garbage Collection?

The CLR's Garbage Collector.

---

### Does GC run immediately?

No.

The CLR decides when to execute the Garbage Collector.

---

# 3. Security

## What is Security?

CLR provides security features to protect applications from executing unsafe or malicious code.

It helps prevent unauthorized operations and improves application safety.

---

## Why is Security Required?

Without security,

applications may:

* Access invalid memory.
* Execute malicious code.
* Corrupt system resources.
* Become unstable.

---

## Example

```csharp
string age = "Twenty";

int number = Convert.ToInt32(age);
```

The CLR detects invalid conversions and throws an exception instead of allowing incorrect execution.

---

## Real-Life Example

Think of airport security.

Every passenger is checked before entering the airport.

Similarly,

CLR verifies code before allowing it to execute.

---

## Diagram

```text
Program

      │

      ▼

CLR Security Check

      │

      ▼

Safe Code

      │

      ▼

Program Executes
```

---

## ⭐ Interview Tips

* CLR provides application security.
* It prevents unsafe execution.
* Security is handled automatically by the CLR.

---

## ❓Interview Questions

### What is CLR Security?

CLR Security protects .NET applications from executing unsafe code.

---

### Why is Security important?

It protects applications and system resources from invalid or malicious operations.

---

# Summary

| Runtime Service    | Description                                |
| ------------------ | ------------------------------------------ |
| Memory Management  | Allocates and manages memory automatically |
| Garbage Collection | Removes unused objects from Heap memory    |
| Security           | Protects applications from unsafe code     |

---

# Quick Revision

| Topic              | Remember This                              |
| ------------------ | ------------------------------------------ |
| Memory Management  | CLR allocates memory                       |
| Garbage Collection | GC removes unused Heap objects             |
| Security           | CLR protects applications from unsafe code |




# CLR Runtime Services 

The **Common Language Runtime (CLR)** provides several runtime services that help execute .NET applications efficiently.

In this section, we will learn about:

* Exception Handling
* Thread Management
* JIT (Just-In-Time) Compilation

---

# 1. Exception Handling

## What is Exception Handling?

**Exception Handling** is a mechanism that allows a program to handle runtime errors without crashing.

CLR automatically detects exceptions and transfers control to the appropriate `catch` block.

---

## Why is Exception Handling Required?

Without exception handling:

* The application may crash.
* Users may lose data.
* The program may terminate unexpectedly.

Exception handling makes applications more reliable.

---

## Example

```csharp
using System;

class Program
{
    static void Main()
    {
        try
        {
            int number = 10;
            int result = number / 0;
        }
        catch (Exception ex)
        {
            Console.WriteLine(ex.Message);
        }

        Console.WriteLine("Program Continues...");
    }
}
```

### Output

```text
Attempted to divide by zero.
Program Continues...
```

### Explanation

* An exception occurs because division by zero is not allowed.
* CLR detects the exception.
* Control moves to the `catch` block.
* The application continues running.

---

## Working

```text
Program Starts
       │
       ▼
Exception Occurs
       │
       ▼
CLR Detects Exception
       │
       ▼
Catch Block Executes
       │
       ▼
Program Continues
```

---

## Real-Life Example

Imagine you are driving a car.

Suddenly, a tyre gets punctured.

Instead of abandoning the car, you replace the tyre and continue your journey.

Exception handling works in the same way.

---

## ⭐ Interview Tips

* CLR automatically detects runtime exceptions.
* `try`, `catch`, and `finally` are used for exception handling.
* Exception handling prevents application crashes.

---

## ❓Interview Questions

### What is Exception Handling?

Exception Handling is a mechanism for handling runtime errors so that the application continues executing safely.

---

### Who handles exceptions in .NET?

The **CLR** detects exceptions and works with the exception handling mechanism (`try-catch-finally`).

---

### What happens if an exception is not handled?

The application may terminate unexpectedly.

---

# 2. Thread Management

## What is Thread Management?

A **Thread** is the smallest unit of execution inside a process.

CLR manages the creation, execution, and scheduling of threads.

---

## Why is Thread Management Required?

It allows applications to perform multiple tasks simultaneously.

Example:

* Downloading a file
* Playing music
* Updating the UI

All can happen at the same time.

---

## Example

```csharp
using System;
using System.Threading;

class Program
{
    static void PrintMessage()
    {
        Console.WriteLine("Running on another thread...");
    }

    static void Main()
    {
        Thread thread = new Thread(PrintMessage);
        thread.Start();

        Console.WriteLine("Main Thread");
    }
}
```

---

## Working

```text
Application Starts
        │
        ▼
Main Thread
        │
        ├──────────────┐
        │              │
        ▼              ▼
Worker Thread      Main Thread
        │              │
        ▼              ▼
Both Execute Simultaneously
```

---

## Real-Life Example

Imagine a restaurant.

One waiter takes orders.

Another serves food.

A third prepares the bill.

Everyone works at the same time.

This is similar to multithreading.

---

## ⭐ Interview Tips

* A process can have multiple threads.
* CLR manages thread execution.
* Threads improve application responsiveness.

---

## ❓Interview Questions

### What is a Thread?

A thread is the smallest unit of execution within a process.

---

### Who manages threads in .NET?

The CLR manages thread creation and execution.

---

### Why is multithreading used?

To execute multiple tasks simultaneously and improve performance.

---

# 3. JIT (Just-In-Time) Compilation

## What is JIT?

**JIT (Just-In-Time) Compiler** converts **Intermediate Language (IL)** into **Native Machine Code** at runtime.

The CPU can execute only Machine Code.

---

## Why is JIT Required?

The CPU cannot understand IL directly.

Therefore, IL must first be converted into Machine Code.

This conversion is performed by the JIT Compiler.

---

## Execution Flow

```text
C# Source Code
        │
        ▼
C# Compiler
        │
        ▼
IL Code
        │
        ▼
CLR
        │
        ▼
JIT Compiler
        │
        ▼
Machine Code
        │
        ▼
CPU
```

---

## Example

```csharp
Console.WriteLine("Hello World");
```

### Execution

```text
C# Code
      │
      ▼
Compiler
      │
      ▼
IL Code
      │
      ▼
JIT Compiler
      │
      ▼
Machine Code
      │
      ▼
CPU
```

---

## Real-Life Example

Suppose a book is written in English.

A translator converts it into Hindi before you read it.

* English Book → IL Code
* Translator → JIT Compiler
* Hindi Book → Machine Code

The CPU understands only the final translated version (Machine Code).

---

## ⭐ Interview Tips

* JIT stands for **Just-In-Time Compiler**.
* JIT converts IL into Machine Code.
* JIT works at runtime.
* The CPU executes Machine Code, not IL.

---

## ❓Interview Questions

### What is JIT?

JIT (Just-In-Time Compiler) converts IL into native Machine Code during program execution.

---

### Does JIT compile C# code directly?

No.

The C# Compiler first converts C# into IL.

Then JIT converts IL into Machine Code.

---

### What is the difference between the C# Compiler and the JIT Compiler?

| C# Compiler                | JIT Compiler                |
| -------------------------- | --------------------------- |
| Converts C# to IL          | Converts IL to Machine Code |
| Executes during build time | Executes during runtime     |

---

### Why is JIT important?

JIT allows .NET applications to execute efficiently by converting platform-independent IL into native Machine Code.

---

# Complete CLR Runtime Flow

```text
C# Source Code
       │
       ▼
C# Compiler
       │
       ▼
Intermediate Language (IL)
       │
       ▼
CLR
├── Memory Management
├── Garbage Collection
├── Security
├── Exception Handling
├── Thread Management
└── JIT Compilation
       │
       ▼
Machine Code
       │
       ▼
CPU
```

---

# Summary

| Runtime Service    | Description                                             |
| ------------------ | ------------------------------------------------------- |
| Exception Handling | Handles runtime errors without crashing the application |
| Thread Management  | Manages thread creation and execution                   |
| JIT Compilation    | Converts IL into Machine Code at runtime                |

---

# Quick Revision

| Topic              | Remember This                                           |
| ------------------ | ------------------------------------------------------- |
| Exception Handling | Prevents application crashes by handling runtime errors |
| Thread Management  | Executes multiple tasks concurrently                    |
| JIT Compiler       | Converts IL to Machine Code before execution            |


# Thread Management in C#

## What is a Thread?

A **Thread** is the **smallest unit of execution** inside a process.

A process can contain one or more threads.

Each thread performs a specific task.

---

# What is a Process?

A **Process** is a running application.

Examples:

* Google Chrome
* Visual Studio
* Microsoft Word
* Calculator

Each application running on your computer is a separate process.

---

# Relationship Between Process and Thread

```text
Process (Application)

│

├── Thread 1 (UI)

├── Thread 2 (Download)

├── Thread 3 (Background Task)

└── Thread 4 (Save File)
```

A single process can have multiple threads running simultaneously.

---

# Why Do We Need Threads?

Threads allow an application to perform multiple tasks at the same time.

For example:

* Downloading a file
* Playing music
* Updating the user interface
* Reading data from a database

These tasks can run concurrently.

---

# Example

```csharp
using System;
using System.Threading;

class Program
{
    static void Download()
    {
        Console.WriteLine("Downloading File...");
    }

    static void Main()
    {
        Thread downloadThread = new Thread(Download);

        downloadThread.Start();

        Console.WriteLine("Main Thread Running...");
    }
}
```

### Possible Output

```text
Main Thread Running...
Downloading File...
```

> **Note:** The exact order of the output may vary because both threads execute independently.

---

# How CLR Manages Threads

```text
Application Starts
        │
        ▼
Main Thread Created
        │
        ▼
Additional Threads Created
        │
        ▼
CLR Schedules Threads
        │
        ▼
Tasks Execute Concurrently
```

The CLR is responsible for:

* Creating threads
* Managing thread execution
* Scheduling threads
* Releasing thread resources when they finish

---

# Real-Life Example

Imagine a restaurant.

```text
Restaurant (Process)

│

├── Waiter (Thread)

├── Chef (Thread)

└── Cashier (Thread)
```

Each employee performs a different task at the same time.

Similarly, a process uses multiple threads to perform different tasks concurrently.

---

# Advantages of Threads

* Improves application performance
* Keeps the user interface responsive
* Executes multiple tasks simultaneously
* Better utilization of CPU resources

---

# Process vs Thread

| Process                      | Thread                     |
| ---------------------------- | -------------------------- |
| Running application          | Smallest unit of execution |
| Heavyweight                  | Lightweight                |
| Has its own memory           | Shares the process memory  |
| Can contain multiple threads | Exists inside a process    |

---

# ⭐ Interview Tips

* A **Process** is a running application.
* A **Thread** is the smallest unit of execution.
* Every process has at least one thread called the **Main Thread**.
* A process can have multiple threads.
* CLR manages thread creation and execution.
* Threads share the memory of their process.

---

# ❓Common Interview Questions

## 1. What is a Thread?

**Answer:**

A thread is the smallest unit of execution inside a process. It performs a specific task within an application.

---

## 2. What is a Process?

**Answer:**

A process is a running instance of an application.

---

## 3. What is the difference between a Process and a Thread?

**Answer:**

A process is an independent running application, while a thread is the smallest unit of execution inside a process.

---

## 4. Can a Process have multiple Threads?

**Answer:**

Yes.

A single process can contain multiple threads that execute different tasks simultaneously.

---

## 5. Who manages Threads in .NET?

**Answer:**

The **Common Language Runtime (CLR)** manages thread creation, scheduling, execution, and cleanup.

---

## 6. What is the Main Thread?

**Answer:**

The Main Thread is the first thread created when a .NET application starts.

---

## 7. Why do we use Threads?

**Answer:**

Threads allow applications to perform multiple tasks concurrently, improving responsiveness and performance.

---

## 8. Do Threads have separate memory?

**Answer:**

No.

Threads share the memory of the same process, but each thread has its own execution stack.

---

# Summary

| Topic          | Description                                     |
| -------------- | ----------------------------------------------- |
| Process        | Running application                             |
| Thread         | Smallest unit of execution                      |
| CLR            | Manages thread execution                        |
| Main Thread    | First thread created when an application starts |
| Multithreading | Running multiple threads concurrently           |



# Thread Management in C#

## What is a Thread?

A **Thread** is the **smallest unit of execution** inside a process.

A process can contain one or more threads.

Each thread performs a specific task.

---

# What is a Process?

A **Process** is a running application.

Examples:

* Google Chrome
* Visual Studio
* Microsoft Word
* Calculator

Each application running on your computer is a separate process.

---

# Relationship Between Process and Thread

```text
Process (Application)

│

├── Thread 1 (UI)

├── Thread 2 (Download)

├── Thread 3 (Background Task)

└── Thread 4 (Save File)
```

A single process can have multiple threads running simultaneously.

---

# Why Do We Need Threads?

Threads allow an application to perform multiple tasks at the same time.

For example:

* Downloading a file
* Playing music
* Updating the user interface
* Reading data from a database

These tasks can run concurrently.

---

# Example

```csharp
using System;
using System.Threading;

class Program
{
    static void Download()
    {
        Console.WriteLine("Downloading File...");
    }

    static void Main()
    {
        Thread downloadThread = new Thread(Download);

        downloadThread.Start();

        Console.WriteLine("Main Thread Running...");
    }
}
```

### Possible Output

```text
Main Thread Running...
Downloading File...
```

> **Note:** The exact order of the output may vary because both threads execute independently.

---

# How CLR Manages Threads

```text
Application Starts
        │
        ▼
Main Thread Created
        │
        ▼
Additional Threads Created
        │
        ▼
CLR Schedules Threads
        │
        ▼
Tasks Execute Concurrently
```

The CLR is responsible for:

* Creating threads
* Managing thread execution
* Scheduling threads
* Releasing thread resources when they finish

---

# Real-Life Example

Imagine a restaurant.

```text
Restaurant (Process)

│

├── Waiter (Thread)

├── Chef (Thread)

└── Cashier (Thread)
```

Each employee performs a different task at the same time.

Similarly, a process uses multiple threads to perform different tasks concurrently.

---

# Advantages of Threads

* Improves application performance
* Keeps the user interface responsive
* Executes multiple tasks simultaneously
* Better utilization of CPU resources

---

# Process vs Thread

| Process                      | Thread                     |
| ---------------------------- | -------------------------- |
| Running application          | Smallest unit of execution |
| Heavyweight                  | Lightweight                |
| Has its own memory           | Shares the process memory  |
| Can contain multiple threads | Exists inside a process    |

---

# ⭐ Interview Tips

* A **Process** is a running application.
* A **Thread** is the smallest unit of execution.
* Every process has at least one thread called the **Main Thread**.
* A process can have multiple threads.
* CLR manages thread creation and execution.
* Threads share the memory of their process.

---

# ❓Common Interview Questions

## 1. What is a Thread?

**Answer:**

A thread is the smallest unit of execution inside a process. It performs a specific task within an application.

---

## 2. What is a Process?

**Answer:**

A process is a running instance of an application.

---

## 3. What is the difference between a Process and a Thread?

**Answer:**

A process is an independent running application, while a thread is the smallest unit of execution inside a process.

---

## 4. Can a Process have multiple Threads?

**Answer:**

Yes.

A single process can contain multiple threads that execute different tasks simultaneously.

---

## 5. Who manages Threads in .NET?

**Answer:**

The **Common Language Runtime (CLR)** manages thread creation, scheduling, execution, and cleanup.

---

## 6. What is the Main Thread?

**Answer:**

The Main Thread is the first thread created when a .NET application starts.

---

## 7. Why do we use Threads?

**Answer:**

Threads allow applications to perform multiple tasks concurrently, improving responsiveness and performance.

---

## 8. Do Threads have separate memory?

**Answer:**

No.

Threads share the memory of the same process, but each thread has its own execution stack.

---

# Summary

| Topic          | Description                                     |
| -------------- | ----------------------------------------------- |
| Process        | Running application                             |
| Thread         | Smallest unit of execution                      |
| CLR            | Manages thread execution                        |
| Main Thread    | First thread created when an application starts |
| Multithreading | Running multiple threads concurrently           |


# ⭐ Most Asked Operator Interview Questions in C#

## 1. Difference Between `=` and `==`

These two operators are commonly confused.

| `=` (Assignment Operator)     | `==` (Equality Operator) |
| ----------------------------- | ------------------------ |
| Assigns a value to a variable | Compares two values      |
| Does not return True/False    | Returns True or False    |
| Used for assignment           | Used in conditions       |

### Example

```csharp
int a = 10;   // Assignment

Console.WriteLine(a == 10);   // Comparison
```

### Output

```text
True
```

### Interview Tip ⭐

Remember:

* `=` → Assign Value
* `==` → Compare Value

---

## 2. Difference Between `++i` and `i++`

Both increase the value by **1**, but the order is different.

### Pre-Increment (`++i`)

First increases the value, then uses it.

```csharp
int i = 5;

Console.WriteLine(++i);
```

Output

```text
6
```

---

### Post-Increment (`i++`)

First uses the current value, then increases it.

```csharp
int i = 5;

Console.WriteLine(i++);
Console.WriteLine(i);
```

Output

```text
5
6
```

### Interview Tip ⭐

* `++i` → Increment First
* `i++` → Use First

---

## 3. Difference Between `&&` and `&`

### `&&` (Logical AND)

Uses **Short-Circuit Evaluation**.

If the first condition is **false**, the second condition is **not checked**.

```csharp
int a = 10;

if(a > 20 && a < 50)
{
    Console.WriteLine("True");
}
```

Here, `a > 20` is false, so `a < 50` is not evaluated.

---

### `&` (Bitwise AND / Non-Short-Circuit AND)

Evaluates **both conditions**, even if the first one is false.

```csharp
if(a > 20 & a < 50)
{
    Console.WriteLine("True");
}
```

Both expressions are checked.

---

### Interview Tip ⭐

* `&&` → Stops early (Short-Circuit)
* `&` → Always evaluates both operands

---

## 4. Difference Between `||` and `|`

### `||` (Logical OR)

If the first condition is **true**, the second condition is **not evaluated**.

```csharp
int age = 25;

if(age > 18 || age < 10)
{
    Console.WriteLine("Eligible");
}
```

Since `age > 18` is true, the second condition is skipped.

---

### `|` (Bitwise OR / Non-Short-Circuit OR)

Evaluates **both conditions**, regardless of the first result.

---

### Interview Tip ⭐

* `||` → Short-Circuit OR
* `|` → Always evaluates both operands

---

## 5. Ternary Operator (`?:`)

The ternary operator is a short form of an `if-else` statement.

### Syntax

```csharp
condition ? value_if_true : value_if_false;
```

### Example

```csharp
int marks = 75;

string result = marks >= 40 ? "Pass" : "Fail";

Console.WriteLine(result);
```

### Output

```text
Pass
```

### Equivalent Using if-else

```csharp
if(marks >= 40)
{
    Console.WriteLine("Pass");
}
else
{
    Console.WriteLine("Fail");
}
```

---

## 6. Null-Coalescing Operator (`??`)

Returns the left value if it is **not null**.

Otherwise, returns the right value.

### Example

```csharp
string name = null;

string result = name ?? "Guest";

Console.WriteLine(result);
```

### Output

```text
Guest
```

### Another Example

```csharp
string city = "Jaipur";

Console.WriteLine(city ?? "Delhi");
```

Output

```text
Jaipur
```

### Interview Tip ⭐

`??` is commonly used to provide a **default value** when a variable is `null`.

---

## 7. Difference Between Logical and Bitwise Operators

| Logical Operators         | Bitwise Operators                |        |        |             |
| ------------------------- | -------------------------------- | ------ | ------ | ----------- |
| Work with Boolean values  | Work with binary bits            |        |        |             |
| `&&`, `                   |                                  | `, `!` | `&`, ` | `, `^`, `~` |
| Mainly used in conditions | Mainly used for bit manipulation |        |        |             |

### Logical Example

```csharp
bool isStudent = true;
bool hasID = false;

Console.WriteLine(isStudent && hasID);
```

Output

```text
False
```

---

### Bitwise Example

```csharp
int a = 5;
int b = 3;

Console.WriteLine(a & b);
Console.WriteLine(a | b);
```

Output

```text
1
7
```

---

# ⭐ Quick Revision

| Operator | Remember                                        |                               |                            |
| -------- | ----------------------------------------------- | ----------------------------- | -------------------------- |
| `=`      | Assign Value                                    |                               |                            |
| `==`     | Compare Values                                  |                               |                            |
| `++i`    | Increment First                                 |                               |                            |
| `i++`    | Use First, Then Increment                       |                               |                            |
| `&&`     | Logical AND (Short-Circuit)                     |                               |                            |
| `&`      | Bitwise AND / Always Evaluates                  |                               |                            |
| `        |                                                 | `                             | Logical OR (Short-Circuit) |
| `        | `                                               | Bitwise OR / Always Evaluates |                            |
| `?:`     | Short Form of `if-else`                         |                               |                            |
| `??`     | Returns Default Value if Left Operand is `null` |                               |                            |

---

# 🎯 Top Interview Questions

### Q1. What is the difference between `=` and `==`?

**Answer:** `=` assigns a value to a variable, whereas `==` compares two values and returns `true` or `false`.

---

### Q2. What is the difference between `++i` and `i++`?

**Answer:** `++i` increments the value before it is used, while `i++` uses the current value first and increments it afterward.

---

### Q3. What is Short-Circuit Evaluation?

**Answer:** Short-circuit evaluation means the second condition is skipped if the result can already be determined from the first condition. It is used by `&&` and `||`.

---

### Q4. What is the difference between `&&` and `&`?

**Answer:** `&&` uses short-circuit evaluation and may skip the second condition, while `&` always evaluates both operands.

---

### Q5. What is the difference between `||` and `|`?

**Answer:** `||` uses short-circuit evaluation and may skip the second condition, while `|` always evaluates both operands.

---

### Q6. What is the Ternary Operator?

**Answer:** The ternary operator (`?:`) is a concise way to write an `if-else` statement.

---

### Q7. What is the Null-Coalescing Operator?

**Answer:** The `??` operator returns the left operand if it is not `null`; otherwise, it returns the right operand.

---

### Q8. What is the difference between Logical and Bitwise Operators?

**Answer:** Logical operators work with Boolean expressions, while bitwise operators work on the binary representation of integer values.

# Keywords in C#

## What are Keywords?

**Keywords** are **reserved words** in C# that have a predefined meaning for the compiler.

These words are part of the C# language syntax and **cannot be used as variable names, method names, or class names** (unless prefixed with `@`).

### Example

```csharp
int age = 20;
```

Here:

* `int` → Keyword
* `age` → Variable
* `20` → Literal

---

# Why are Keywords Important?

Keywords tell the compiler what action to perform.

For example:

* `if` → Makes a decision.
* `for` → Creates a loop.
* `class` → Defines a class.
* `return` → Returns a value from a method.

---

# Types of Keywords in C#

There are three main categories:

1. Reserved Keywords
2. Contextual Keywords
3. Access Modifiers (also keywords)

---

# 1. Reserved Keywords

These keywords have a fixed meaning and cannot normally be used as identifiers.

### Common Reserved Keywords

| Keyword   | Purpose                                     |
| --------- | ------------------------------------------- |
| class     | Defines a class                             |
| namespace | Defines a namespace                         |
| using     | Imports a namespace                         |
| public    | Accessible from anywhere                    |
| private   | Accessible only inside the class            |
| protected | Accessible in the class and derived classes |
| internal  | Accessible within the same assembly         |
| static    | Belongs to the type, not an object          |
| void      | Method returns no value                     |
| return    | Returns a value                             |
| new       | Creates an object                           |
| if        | Conditional statement                       |
| else      | Alternative condition                       |
| switch    | Multiple conditions                         |
| case      | Case inside a switch                        |
| break     | Exits a loop or switch                      |
| continue  | Skips the current iteration                 |
| for       | Loop                                        |
| foreach   | Iterates over a collection                  |
| while     | Loop                                        |
| do        | Executes the loop body at least once        |
| try       | Starts exception handling                   |
| catch     | Handles an exception                        |
| finally   | Executes regardless of an exception         |
| throw     | Throws an exception                         |
| int       | Integer data type                           |
| string    | String data type                            |
| bool      | Boolean data type                           |
| double    | Double-precision floating-point type        |
| decimal   | High-precision decimal type                 |
| true      | Boolean true                                |
| false     | Boolean false                               |
| null      | Represents no value                         |

---

# Example

```csharp
using System;

class Program
{
    static void Main()
    {
        if (true)
        {
            Console.WriteLine("Hello");
        }
    }
}
```

Keywords used:

* using
* class
* static
* void
* if
* true

---

# 2. Contextual Keywords

Contextual keywords have a special meaning only in specific contexts.

Examples:

| Keyword | Usage                                |
| ------- | ------------------------------------ |
| var     | Implicitly typed local variable      |
| async   | Declares an asynchronous method      |
| await   | Waits for an asynchronous operation  |
| yield   | Returns elements one at a time       |
| where   | Generic constraints or LINQ          |
| partial | Splits a class across multiple files |
| record  | Defines a record type                |
| init    | Init-only property setter            |
| global  | Refers to the global namespace       |

### Example

```csharp
var name = "Neeraj";

Console.WriteLine(name);
```

---

# 3. Access Modifier Keywords

These keywords control the accessibility of classes and members.

| Keyword            | Accessibility                                   |
| ------------------ | ----------------------------------------------- |
| public             | Accessible from anywhere                        |
| private            | Accessible only within the same class           |
| protected          | Accessible within the class and derived classes |
| internal           | Accessible within the same assembly             |
| protected internal | Derived classes or same assembly                |
| private protected  | Derived classes within the same assembly        |

---

# Can We Use Keywords as Variable Names?

Normally, **No**.

This will cause a compile-time error:

```csharp
int class = 10;
```

### Correct Way

Use the `@` symbol.

```csharp
int @class = 10;

Console.WriteLine(@class);
```

Output

```text
10
```

---

# Real-Life Example

Imagine traffic signals.

* Red → Stop
* Green → Go
* Yellow → Wait

These words have predefined meanings.

Similarly, C# keywords have predefined meanings for the compiler.

---

# ⭐ Interview Tips

* Keywords are reserved words.
* They have predefined meanings.
* Keywords cannot normally be used as identifiers.
* `@` allows a keyword to be used as an identifier.
* `var` is a contextual keyword.
* `class`, `if`, `for`, `return`, `public` are reserved keywords.

---

# ❓Common Interview Questions

### 1. What are Keywords in C#?

**Answer:**

Keywords are reserved words with predefined meanings that are recognized by the C# compiler.

---

### 2. Can we use a keyword as a variable name?

**Answer:**

Not directly.

However, a keyword can be used as an identifier by prefixing it with `@`.

Example:

```csharp
int @class = 10;
```

---

### 3. What is the difference between Reserved Keywords and Contextual Keywords?

| Reserved Keywords                | Contextual Keywords                |
| -------------------------------- | ---------------------------------- |
| Always reserved                  | Reserved only in specific contexts |
| Example: `class`, `if`, `return` | Example: `var`, `async`, `await`   |

---

### 4. What is the `var` keyword?

**Answer:**

`var` is a contextual keyword that lets the compiler infer the type of a local variable from the assigned value.

Example:

```csharp
var age = 25; // Compiler infers int
```

---

### 5. What is the purpose of the `using` keyword?

**Answer:**

The `using` keyword imports a namespace so that its types can be used without writing the full namespace name.

Example:

```csharp
using System;
```

---

### 6. What is the purpose of the `new` keyword?

**Answer:**

The `new` keyword creates an object and allocates memory for it.

Example:

```csharp
Student s = new Student();
```

---

### 7. What is the difference between `break` and `continue`?

| break                    | continue                                                    |
| ------------------------ | ----------------------------------------------------------- |
| Exits the loop or switch | Skips the current iteration and continues with the next one |

---

# Quick Revision

| Keyword   | Purpose                   |
| --------- | ------------------------- |
| class     | Defines a class           |
| namespace | Defines a namespace       |
| using     | Imports a namespace       |
| static    | Belongs to the type       |
| void      | No return value           |
| new       | Creates an object         |
| return    | Returns a value           |
| if        | Decision making           |
| for       | Loop                      |
| foreach   | Collection iteration      |
| while     | Loop                      |
| break     | Exit loop/switch          |
| continue  | Skip current iteration    |
| try       | Start exception handling  |
| catch     | Handle exception          |
| finally   | Always executes           |
| throw     | Throw an exception        |
| var       | Implicitly typed variable |
| async     | Asynchronous method       |
| await     | Wait for async operation  |

---

# Summary

* Keywords are reserved words in C#.
* They have predefined meanings for the compiler.
* They cannot normally be used as identifiers.
* Contextual keywords have special meanings only in specific situations.
* The `@` prefix allows a keyword to be used as an identifier.


# 🎯 C# Keywords - Interview Questions & Answers

## 1. What are Keywords in C#?

**Answer:**

Keywords are **reserved words** that have a predefined meaning in the C# language. They are recognized by the compiler and cannot normally be used as identifiers.

**Example:**

```csharp
int age = 25;
```

Here, `int` is a keyword.

---

## 2. Why are Keywords called Reserved Words?

**Answer:**

Because they are reserved by the C# compiler for specific purposes and cannot normally be used as variable names, method names, or class names.

---

## 3. Can we use a Keyword as a Variable Name?

**Answer:**

Yes, but only by using the `@` symbol.

**Example:**

```csharp
int @class = 10;

Console.WriteLine(@class);
```

---

## 4. What is the Difference Between Reserved Keywords and Contextual Keywords?

| Reserved Keywords                        | Contextual Keywords                                         |
| ---------------------------------------- | ----------------------------------------------------------- |
| Always reserved                          | Reserved only in specific contexts                          |
| Cannot normally be used as identifiers   | Can act as normal identifiers outside their special context |
| Examples: `class`, `int`, `if`, `return` | Examples: `var`, `async`, `await`                           |

---

## 5. What is the `using` Keyword?

**Answer:**

The `using` keyword imports a namespace so that you can use its classes without writing the full namespace name.

**Example:**

```csharp
using System;

Console.WriteLine("Hello");
```

---

## 6. What is the `namespace` Keyword?

**Answer:**

A namespace is used to organize related classes, interfaces, enums, and other types. It also helps avoid naming conflicts.

**Example:**

```csharp
namespace MyApplication
{
    class Program
    {
    }
}
```

---

## 7. What is the `class` Keyword?

**Answer:**

The `class` keyword is used to define a class, which acts as a blueprint for creating objects.

**Example:**

```csharp
class Student
{
}
```

---

## 8. What is the `new` Keyword?

**Answer:**

The `new` keyword creates an object and allocates memory for it.

**Example:**

```csharp
Student s = new Student();
```

---

## 9. What is the `static` Keyword?

**Answer:**

The `static` keyword indicates that a member belongs to the class itself rather than to individual objects.

**Example:**

```csharp
class MathHelper
{
    public static int Square(int x)
    {
        return x * x;
    }
}
```

---

## 10. What is the `void` Keyword?

**Answer:**

The `void` keyword indicates that a method does not return any value.

**Example:**

```csharp
void Display()
{
    Console.WriteLine("Hello");
}
```

---

## 11. What is the `return` Keyword?

**Answer:**

The `return` keyword exits a method and optionally returns a value to the caller.

**Example:**

```csharp
int Add(int a, int b)
{
    return a + b;
}
```

---

## 12. What is the `var` Keyword?

**Answer:**

`var` is a contextual keyword that allows the compiler to infer the variable's type from the assigned value.

**Example:**

```csharp
var name = "Neeraj";
```

The compiler treats `name` as a `string`.

---

## 13. What is the Difference Between `var` and `dynamic`?

| var                                | dynamic                       |
| ---------------------------------- | ----------------------------- |
| Type is determined at compile time | Type is determined at runtime |
| Strongly typed                     | Not compile-time type checked |
| Better performance                 | More flexible but slower      |

---

## 14. What is the `const` Keyword?

**Answer:**

`const` declares a constant whose value cannot be changed after initialization.

**Example:**

```csharp
const double PI = 3.14159;
```

---

## 15. What is the Difference Between `const` and `readonly`?

| const                                 | readonly                                 |
| ------------------------------------- | ---------------------------------------- |
| Value must be assigned at declaration | Value can be assigned in the constructor |
| Compile-time constant                 | Runtime constant                         |
| Implicitly static                     | Instance or static                       |

---

## 16. What is the `this` Keyword?

**Answer:**

The `this` keyword refers to the current instance of the class.

**Example:**

```csharp
class Student
{
    string name;

    public Student(string name)
    {
        this.name = name;
    }
}
```

---

## 17. What is the `base` Keyword?

**Answer:**

The `base` keyword is used to access members of the base (parent) class.

**Example:**

```csharp
class Animal
{
    public void Eat()
    {
    }
}

class Dog : Animal
{
    public void Test()
    {
        base.Eat();
    }
}
```

---

## 18. What is the `abstract` Keyword?

**Answer:**

The `abstract` keyword is used to define incomplete classes or methods that must be implemented by derived classes.

---

## 19. What is the `sealed` Keyword?

**Answer:**

A `sealed` class cannot be inherited by another class.

---

## 20. What is the `virtual` Keyword?

**Answer:**

The `virtual` keyword allows a method to be overridden in a derived class.

---

## 21. What is the `override` Keyword?

**Answer:**

The `override` keyword provides a new implementation of a virtual method from the base class.

---

## 22. What is the `async` Keyword?

**Answer:**

The `async` keyword marks a method as asynchronous so it can use the `await` keyword.

---

## 23. What is the `await` Keyword?

**Answer:**

The `await` keyword pauses the execution of an asynchronous method until the awaited task completes.

---

## 24. What is the Difference Between `break` and `continue`?

| break                    | continue                                                    |
| ------------------------ | ----------------------------------------------------------- |
| Exits the loop or switch | Skips the current iteration and continues with the next one |

---

## 25. What is the Difference Between `if` and `switch`?

| if                                    | switch                                                   |
| ------------------------------------- | -------------------------------------------------------- |
| Suitable for complex conditions       | Best for checking one expression against multiple values |
| Supports ranges and logical operators | Best for equality-based multiple choices                 |

---

# ⭐ Rapid-Fire Interview Questions

* What are Keywords in C#?
* Can Keywords be used as variable names?
* What is the `using` keyword?
* What is a `namespace`?
* What is the `new` keyword?
* What is the `static` keyword?
* What is the `var` keyword?
* What is the difference between `var` and `dynamic`?
* What is the difference between `const` and `readonly`?
* What is the `this` keyword?
* What is the `base` keyword?
* What is the `abstract` keyword?
* What is the `sealed` keyword?
* What is the `virtual` keyword?
* What is the `override` keyword?
* What is the `async` keyword?
* What is the `await` keyword?
* What is the difference between `break` and `continue`?
* What is the difference between `if` and `switch`?
* Which keywords are used for exception handling?

---

# 💡 Interview Tip

For **Fresher interviews**, focus on:

* `using`
* `namespace`
* `class`
* `new`
* `static`
* `void`
* `return`
* `var`
* `const`
* `readonly`
* `this`
* `base`

For **1–3 years experienced interviews**, also prepare:

* `abstract`
* `sealed`
* `virtual`
* `override`
* `async`
* `await`
* `yield`
* `partial`
* `record`
* `dynamic`



# Input and Output in C#

## What is Input and Output?

Input means taking data from the user.

Output means displaying data to the user.

In C#, input and output are performed using the **Console** class.

---

# Console.Write()

## What is Console.Write()?

`Console.Write()` displays output on the console **without moving the cursor to the next line**.

### Syntax

```csharp
Console.Write("Hello");
```

### Example

```csharp
Console.Write("Hello ");
Console.Write("Neeraj");
```

### Output

```text
Hello Neeraj
```

### Interview Tip ⭐

* `Console.Write()` does **not** move to the next line.

---

# Console.WriteLine()

## What is Console.WriteLine()?

`Console.WriteLine()` displays output and **moves the cursor to the next line**.

### Syntax

```csharp
Console.WriteLine("Hello");
```

### Example

```csharp
Console.WriteLine("Hello");
Console.WriteLine("Neeraj");
```

### Output

```text
Hello
Neeraj
```

### Interview Tip ⭐

* `Console.WriteLine()` prints the output and moves to the next line.

---

# Difference Between Console.Write() and Console.WriteLine()

| Console.Write()                   | Console.WriteLine()              |
| --------------------------------- | -------------------------------- |
| Does not move to the next line    | Moves to the next line           |
| Output continues on the same line | Each output starts on a new line |

### Example

```csharp
Console.Write("Hello ");
Console.Write("World");

Console.WriteLine();

Console.WriteLine("Hello");
Console.WriteLine("World");
```

### Output

```text
Hello World
Hello
World
```

---

# Console.ReadLine()

## What is Console.ReadLine()?

`Console.ReadLine()` reads a complete line of input from the keyboard.

It always returns a **string**.

### Syntax

```csharp
string name = Console.ReadLine();
```

### Example

```csharp
Console.Write("Enter your name: ");

string name = Console.ReadLine();

Console.WriteLine("Welcome " + name);
```

### Output

```text
Enter your name: Neeraj
Welcome Neeraj
```

---

# Taking Integer Input

Since `Console.ReadLine()` returns a string, it must be converted to an integer.

### Example

```csharp
Console.Write("Enter Age: ");

int age = Convert.ToInt32(Console.ReadLine());

Console.WriteLine(age);
```

### Output

```text
Enter Age: 22
22
```

---

# String Concatenation

String concatenation combines two or more strings using the `+` operator.

### Example

```csharp
string firstName = "Neeraj";
string lastName = "Lalwani";

Console.WriteLine(firstName + " " + lastName);
```

### Output

```text
Neeraj Lalwani
```

---

# String Interpolation

## What is String Interpolation?

String interpolation is a cleaner way to insert variables into a string.

It uses the `$` symbol.

### Syntax

```csharp
$"Text {variable}"
```

### Example

```csharp
string name = "Neeraj";
int age = 22;

Console.WriteLine($"My Name is {name} and I am {age} years old.");
```

### Output

```text
My Name is Neeraj and I am 22 years old.
```

---

# Why Use String Interpolation?

Instead of:

```csharp
Console.WriteLine("Name: " + name + " Age: " + age);
```

Use:

```csharp
Console.WriteLine($"Name: {name} Age: {age}");
```

It is:

* Easier to read
* Cleaner
* Recommended by Microsoft

---

# Formatting

Formatting controls how values are displayed.

---

## Composite Formatting

### Example

```csharp
string name = "Neeraj";
int age = 22;

Console.WriteLine("Name: {0}, Age: {1}", name, age);
```

### Output

```text
Name: Neeraj, Age: 22
```

---

## Number Formatting

### Example

```csharp
double price = 1250.5;

Console.WriteLine(price.ToString("F2"));
```

### Output

```text
1250.50
```

---

## Currency Formatting

### Example

```csharp
double salary = 50000;

Console.WriteLine(salary.ToString("C"));
```

### Example Output

```text
₹50,000.00
```

*(The currency symbol depends on your system's culture settings.)*

---

## Date Formatting

### Example

```csharp
DateTime today = DateTime.Now;

Console.WriteLine(today.ToString("dd-MM-yyyy"));
```

### Output

```text
12-07-2026
```

---

# Real-Life Example

```csharp
Console.Write("Enter Your Name: ");
string name = Console.ReadLine();

Console.Write("Enter Your Age: ");
int age = Convert.ToInt32(Console.ReadLine());

Console.WriteLine($"Welcome {name}");
Console.WriteLine($"You are {age} years old.");
```

### Output

```text
Enter Your Name: Neeraj
Enter Your Age: 22

Welcome Neeraj
You are 22 years old.
```

---

# ⭐ Interview Tips

* `Console.Write()` prints on the same line.
* `Console.WriteLine()` prints and moves to the next line.
* `Console.ReadLine()` always returns a **string**.
* Use `Convert.ToInt32()` to convert string input to an integer.
* String interpolation uses the `$` symbol.
* `{}` placeholders are used inside interpolated strings.
* String interpolation is preferred over string concatenation because it is more readable.

---

# ❓Common Interview Questions

### 1. What is the difference between `Console.Write()` and `Console.WriteLine()`?

**Answer:**

`Console.Write()` prints output on the same line, while `Console.WriteLine()` prints output and moves the cursor to the next line.

---

### 2. What does `Console.ReadLine()` return?

**Answer:**

It always returns a **string**.

---

### 3. Why do we use `Convert.ToInt32(Console.ReadLine())`?

**Answer:**

Because `Console.ReadLine()` returns a string, and `Convert.ToInt32()` converts that string into an integer.

---

### 4. What is String Interpolation?

**Answer:**

String interpolation is a feature that allows variables to be embedded directly inside a string using the `$` symbol and `{}` placeholders.

---

### 5. What is the difference between String Concatenation and String Interpolation?

| String Concatenation  | String Interpolation           |
| --------------------- | ------------------------------ |
| Uses the `+` operator | Uses the `$` symbol and `{}`   |
| Less readable         | More readable                  |
| More typing           | Cleaner and easier to maintain |

---

### 6. What is Composite Formatting?

**Answer:**

Composite formatting uses numbered placeholders such as `{0}`, `{1}`, etc., to insert values into a string.

Example:

```csharp
Console.WriteLine("Name: {0}", name);
```

---

### 7. Which is the recommended way to build strings in modern C#?

**Answer:**

String Interpolation is the recommended approach because it is cleaner, easier to read, and easier to maintain.

---

# Quick Revision

| Method / Feature         | Purpose                                |
| ------------------------ | -------------------------------------- |
| `Console.Write()`        | Prints without a new line              |
| `Console.WriteLine()`    | Prints and moves to a new line         |
| `Console.ReadLine()`     | Reads user input as a string           |
| `Convert.ToInt32()`      | Converts string input to an integer    |
| `+`                      | String concatenation                   |
| `$""`                    | String interpolation                   |
| `{0}`, `{1}`             | Composite formatting                   |
| `ToString("F2")`         | Formats a number with 2 decimal places |
| `ToString("C")`          | Currency formatting                    |
| `ToString("dd-MM-yyyy")` | Date formatting                        |


# Input and Output in C#

## What is Input and Output?

Input means taking data from the user.

Output means displaying data to the user.

In C#, input and output are performed using the **Console** class.

---

# Console.Write()

## What is Console.Write()?

`Console.Write()` displays output on the console **without moving the cursor to the next line**.

### Syntax

```csharp
Console.Write("Hello");
```

### Example

```csharp
Console.Write("Hello ");
Console.Write("Neeraj");
```

### Output

```text
Hello Neeraj
```

### Interview Tip ⭐

* `Console.Write()` does **not** move to the next line.

---

# Console.WriteLine()

## What is Console.WriteLine()?

`Console.WriteLine()` displays output and **moves the cursor to the next line**.

### Syntax

```csharp
Console.WriteLine("Hello");
```

### Example

```csharp
Console.WriteLine("Hello");
Console.WriteLine("Neeraj");
```

### Output

```text
Hello
Neeraj
```

### Interview Tip ⭐

* `Console.WriteLine()` prints the output and moves to the next line.

---

# Difference Between Console.Write() and Console.WriteLine()

| Console.Write()                   | Console.WriteLine()              |
| --------------------------------- | -------------------------------- |
| Does not move to the next line    | Moves to the next line           |
| Output continues on the same line | Each output starts on a new line |

### Example

```csharp
Console.Write("Hello ");
Console.Write("World");

Console.WriteLine();

Console.WriteLine("Hello");
Console.WriteLine("World");
```

### Output

```text
Hello World
Hello
World
```

---

# Console.ReadLine()

## What is Console.ReadLine()?

`Console.ReadLine()` reads a complete line of input from the keyboard.

It always returns a **string**.

### Syntax

```csharp
string name = Console.ReadLine();
```

### Example

```csharp
Console.Write("Enter your name: ");

string name = Console.ReadLine();

Console.WriteLine("Welcome " + name);
```

### Output

```text
Enter your name: Neeraj
Welcome Neeraj
```

---

# Taking Integer Input

Since `Console.ReadLine()` returns a string, it must be converted to an integer.

### Example

```csharp
Console.Write("Enter Age: ");

int age = Convert.ToInt32(Console.ReadLine());

Console.WriteLine(age);
```

### Output

```text
Enter Age: 22
22
```

---

# String Concatenation

String concatenation combines two or more strings using the `+` operator.

### Example

```csharp
string firstName = "Neeraj";
string lastName = "Lalwani";

Console.WriteLine(firstName + " " + lastName);
```

### Output

```text
Neeraj Lalwani
```

---

# String Interpolation

## What is String Interpolation?

String interpolation is a cleaner way to insert variables into a string.

It uses the `$` symbol.

### Syntax

```csharp
$"Text {variable}"
```

### Example

```csharp
string name = "Neeraj";
int age = 22;

Console.WriteLine($"My Name is {name} and I am {age} years old.");
```

### Output

```text
My Name is Neeraj and I am 22 years old.
```

---

# Why Use String Interpolation?

Instead of:

```csharp
Console.WriteLine("Name: " + name + " Age: " + age);
```

Use:

```csharp
Console.WriteLine($"Name: {name} Age: {age}");
```

It is:

* Easier to read
* Cleaner
* Recommended by Microsoft

---

# Formatting

Formatting controls how values are displayed.

---

## Composite Formatting

### Example

```csharp
string name = "Neeraj";
int age = 22;

Console.WriteLine("Name: {0}, Age: {1}", name, age);
```

### Output

```text
Name: Neeraj, Age: 22
```

---

## Number Formatting

### Example

```csharp
double price = 1250.5;

Console.WriteLine(price.ToString("F2"));
```

### Output

```text
1250.50
```

---

## Currency Formatting

### Example

```csharp
double salary = 50000;

Console.WriteLine(salary.ToString("C"));
```

### Example Output

```text
₹50,000.00
```

*(The currency symbol depends on your system's culture settings.)*

---

## Date Formatting

### Example

```csharp
DateTime today = DateTime.Now;

Console.WriteLine(today.ToString("dd-MM-yyyy"));
```

### Output

```text
12-07-2026
```

---

# Real-Life Example

```csharp
Console.Write("Enter Your Name: ");
string name = Console.ReadLine();

Console.Write("Enter Your Age: ");
int age = Convert.ToInt32(Console.ReadLine());

Console.WriteLine($"Welcome {name}");
Console.WriteLine($"You are {age} years old.");
```

### Output

```text
Enter Your Name: Neeraj
Enter Your Age: 22

Welcome Neeraj
You are 22 years old.
```

---

# ⭐ Interview Tips

* `Console.Write()` prints on the same line.
* `Console.WriteLine()` prints and moves to the next line.
* `Console.ReadLine()` always returns a **string**.
* Use `Convert.ToInt32()` to convert string input to an integer.
* String interpolation uses the `$` symbol.
* `{}` placeholders are used inside interpolated strings.
* String interpolation is preferred over string concatenation because it is more readable.

---

# ❓Common Interview Questions

### 1. What is the difference between `Console.Write()` and `Console.WriteLine()`?

**Answer:**

`Console.Write()` prints output on the same line, while `Console.WriteLine()` prints output and moves the cursor to the next line.

---

### 2. What does `Console.ReadLine()` return?

**Answer:**

It always returns a **string**.

---

### 3. Why do we use `Convert.ToInt32(Console.ReadLine())`?

**Answer:**

Because `Console.ReadLine()` returns a string, and `Convert.ToInt32()` converts that string into an integer.

---

### 4. What is String Interpolation?

**Answer:**

String interpolation is a feature that allows variables to be embedded directly inside a string using the `$` symbol and `{}` placeholders.

---

### 5. What is the difference between String Concatenation and String Interpolation?

| String Concatenation  | String Interpolation           |
| --------------------- | ------------------------------ |
| Uses the `+` operator | Uses the `$` symbol and `{}`   |
| Less readable         | More readable                  |
| More typing           | Cleaner and easier to maintain |

---

### 6. What is Composite Formatting?

**Answer:**

Composite formatting uses numbered placeholders such as `{0}`, `{1}`, etc., to insert values into a string.

Example:

```csharp
Console.WriteLine("Name: {0}", name);
```

---

### 7. Which is the recommended way to build strings in modern C#?

**Answer:**

String Interpolation is the recommended approach because it is cleaner, easier to read, and easier to maintain.

---

# Quick Revision

| Method / Feature         | Purpose                                |
| ------------------------ | -------------------------------------- |
| `Console.Write()`        | Prints without a new line              |
| `Console.WriteLine()`    | Prints and moves to a new line         |
| `Console.ReadLine()`     | Reads user input as a string           |
| `Convert.ToInt32()`      | Converts string input to an integer    |
| `+`                      | String concatenation                   |
| `$""`                    | String interpolation                   |
| `{0}`, `{1}`             | Composite formatting                   |
| `ToString("F2")`         | Formats a number with 2 decimal places |
| `ToString("C")`          | Currency formatting                    |
| `ToString("dd-MM-yyyy")` | Date formatting                        |


# 🎯 C# Input & Output - Interview Questions

## Basic Level Questions

### 1. What is the Console class in C#?

**Answer:**

The `Console` class is used to perform input and output operations in a console application.

Example:

```csharp
Console.WriteLine("Hello World");
```

---

### 2. What is the difference between `Console.Write()` and `Console.WriteLine()`?

**Answer:**

| Console.Write()         | Console.WriteLine()               |
| ----------------------- | --------------------------------- |
| Prints on the same line | Prints and moves to the next line |
| Does not add a newline  | Adds a newline automatically      |

---

### 3. What does `Console.ReadLine()` do?

**Answer:**

`Console.ReadLine()` reads an entire line of input from the keyboard and returns it as a **string**.

---

### 4. What is the return type of `Console.ReadLine()`?

**Answer:**

```text
string
```

Even if the user enters a number like **25**, it is returned as `"25"` (a string).

---

### 5. Why do we use `Convert.ToInt32(Console.ReadLine())`?

**Answer:**

Because `Console.ReadLine()` always returns a string. `Convert.ToInt32()` converts that string into an integer.

Example:

```csharp
int age = Convert.ToInt32(Console.ReadLine());
```

---

### 6. What happens if the user enters "ABC" instead of a number?

**Answer:**

A **FormatException** is thrown because `"ABC"` cannot be converted to an integer.

---

### 7. How can we avoid a FormatException?

**Answer:**

Use `int.TryParse()` instead of `Convert.ToInt32()`.

Example:

```csharp
int age;

if (int.TryParse(Console.ReadLine(), out age))
{
    Console.WriteLine("Valid Input");
}
else
{
    Console.WriteLine("Invalid Input");
}
```

---

## String Questions

### 8. What is String Concatenation?

**Answer:**

Combining two or more strings using the `+` operator.

Example:

```csharp
string name = "Neeraj";

Console.WriteLine("Hello " + name);
```

---

### 9. What is String Interpolation?

**Answer:**

String interpolation inserts variables directly into a string using the `$` symbol and `{}` placeholders.

Example:

```csharp
Console.WriteLine($"Hello {name}");
```

---

### 10. Why is String Interpolation preferred?

**Answer:**

Because it is:

* More readable
* Easier to maintain
* Less error-prone
* Recommended in modern C#

---

### 11. What is Composite Formatting?

**Answer:**

Composite formatting uses numbered placeholders (`{0}`, `{1}`, etc.) to insert values into a string.

Example:

```csharp
Console.WriteLine("Name: {0}", name);
```

---

### 12. What is the difference between String Concatenation and String Interpolation?

| Concatenation     | Interpolation     |
| ----------------- | ----------------- |
| Uses `+` operator | Uses `$` and `{}` |
| Less readable     | More readable     |
| More typing       | Cleaner syntax    |

---

## Formatting Questions

### 13. How do you display a number with two decimal places?

**Answer:**

```csharp
double price = 123.456;

Console.WriteLine(price.ToString("F2"));
```

Output:

```text
123.46
```

---

### 14. How do you display a value as currency?

**Answer:**

```csharp
double salary = 50000;

Console.WriteLine(salary.ToString("C"));
```

---

### 15. How do you display the current date in `dd-MM-yyyy` format?

**Answer:**

```csharp
Console.WriteLine(DateTime.Now.ToString("dd-MM-yyyy"));
```

---

## Practical Questions

### 16. Write a program to take the user's name and display it.

```csharp
Console.Write("Enter Name: ");

string name = Console.ReadLine();

Console.WriteLine($"Welcome {name}");
```

---

### 17. Write a program to input two numbers and print their sum.

```csharp
Console.Write("Enter First Number: ");
int a = Convert.ToInt32(Console.ReadLine());

Console.Write("Enter Second Number: ");
int b = Convert.ToInt32(Console.ReadLine());

Console.WriteLine($"Sum = {a + b}");
```

---

### 18. What is the difference between `Convert.ToInt32()` and `int.Parse()`?

| Convert.ToInt32()               | int.Parse()                                |
| ------------------------------- | ------------------------------------------ |
| Handles `null` by returning `0` | Throws an exception if the input is `null` |
| Converts compatible types       | Expects a valid numeric string             |

---

### 19. Which is safer: `Convert.ToInt32()` or `int.TryParse()`?

**Answer:**

`int.TryParse()` is safer because it does not throw an exception for invalid input.

---

### 20. Which is the best method for validating user input?

**Answer:**

`TryParse()` methods (`int.TryParse()`, `double.TryParse()`, etc.) are recommended because they safely handle invalid input.

---

# ⭐ Rapid Fire Interview Questions

* What is the Console class?
* What is the difference between `Console.Write()` and `Console.WriteLine()`?
* What is the return type of `Console.ReadLine()`?
* Why do we use `Convert.ToInt32(Console.ReadLine())`?
* What exception occurs if the input is invalid?
* How can you avoid a `FormatException`?
* What is String Concatenation?
* What is String Interpolation?
* What is Composite Formatting?
* Which is better: Concatenation or Interpolation?
* What is `int.TryParse()`?
* Difference between `Convert.ToInt32()` and `int.Parse()`?
* Difference between `int.Parse()` and `int.TryParse()`?
* How do you format a number to two decimal places?
* How do you display currency?
* How do you format a date?

---

# ⭐ Interview Tips

* `Console.ReadLine()` always returns a **string**.
* Always validate numeric input using `TryParse()` in production code.
* Prefer **String Interpolation** over string concatenation.
* Know the differences between `Convert.ToInt32()`, `int.Parse()`, and `int.TryParse()`.
* Be familiar with basic formatting methods like `"F2"`, `"C"`, and `"dd-MM-yyyy"`.




