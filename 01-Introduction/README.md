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

