---
title: "Top 38 .NET Interview Questions Frequently Asked in 2026"
intro: "In this comprehensive guide, we'll delve into the essential topics, concepts, and techniques you need to master to ace your .NET interviews."
image: "BlogBannerDotNetInterview"
social: "/social/BlogBanner-DotNetInterview.png"
createdOn: "2024-06-07"
lastModifiedOn: "2025-09-18"
order: 1
---

# Top 38 .NET Interview Questions Frequently Asked in 2026

Preparing for a .NET interview can be daunting, but with the right guidance and resources, you can approach it with confidence. 

In this comprehensive guide, we'll delve into the essential topics, concepts, and techniques you need to master to ace your .NET interviews. 

From understanding key .NET frameworks to tackling tricky coding challenges, we've got you covered. 

Additional concepts such as SOLID Principles, OOPS AND SQL are also covered which would be asked in any technical interview including .NET.

### Introduction

.NET framework is developed by Microsoft, provides an environment to run, debug and deploy code using object-oriented programming.

Different languages like C#, Cobol, VB, F#, Perl, etc. can be used for writing .NET framework applications. The framework supports services, websites, desktop applications, and many more.

.NET Core is a newer version of the .NET framework and it is a general-purpose, cost-free, open-source development platform developed by Microsoft. 

.NET Core is a cross-platform framework that runs an application on different operating systems such as Windows, Linux, and macOS operating systems. 

This framework can be used to develop various kinds of applications like mobile, web, IoT, cloud, microservices, machine learning, game, etc.

This article covers the most frequently asked .NET and .NET Core interview questions that are mostly asked.

📌 If you prefer offline preparation, [download the .NET Interview ebook for free](https://hassansadeedali.gumroad.com/l/dotnetinterviews)

## Page Contents

[1\. How does .NET Framework work?](#1-how-does-net-framework-work)

[2\. What’s the difference between .NET and .NET Framework?](#2-whats-the-difference-between-net-and-net-framework)

[3\. What is an EXE and a DLL?](#3-what-is-an-exe-and-a-dll)

[4\. Explain MVC](#4-explain-mvc)

[5\. Explain OOPS Concept](#5-explain-oops-concept)

[6\. What is method overloading and method overriding?](#6-what-is-method-overloading-and-method-overriding)

[7\. Difference between abstraction and interface.](#7-difference-between-abstraction-and-interface)

[8\. Explain SOLID Principles](#8-explain-solid-principles)

[9\. How does ASP.NET Core handle dependency injection?](#9-how-does-asp-net-core-handle-dependency-injectio-)

[10\. What is the difference between Singleton, Transient and Scoped Lifetime?](#10-what-is-the-difference-between-singleton-transient-and-scoped-lifetime)

[11\. What is middleware in .NET core?](#11-what-is-middleware-in-net-core)

[12\. What’s the difference between middleware and a filter in ASP.NET Core?](#12-whats-the-difference-between-middleware-and-a-filter-in-aspnet-core)

[13\. What are different types of exceptions in .NET and how are they handled?](#13-what-are-different-types-of-exceptions-in-net-and-how-are-they-handled)

[14\. Explain the differences between value type and reference type.](#14-explain-the-differences-between-value-type-and-reference-type)

[15\. Explain boxing and unboxing in C# with example.](#15-explain-boxing-and-unboxing-in-c-with-example)

[16\. What is a garbage collector?](#16-what-is-a-garbage-collector)

[17\. What are the different authentication and authorization mechanisms available at ASP.NET core?](#17-what-are-the-different-authentication-and-authorization-mechanisms-available-at-aspnet-core)

[18\. Difference between IEnumerable, ICollection, IList, IQueryable](#18-difference-between-ienumerable-icollection-ilist-iqueryable)

[19\. What are different C# Access Modifiers?](#19-what-are-different-c-access-modifiers)

[20\. What is the difference between var and dynamic?](#20-what-is-the-difference-between-var-and-dynamic)

[21\. What is the difference between const, readonly and static?](#21-what-is-the-difference-between-const-readonly-and-static)

[22\. How can “using” keyword be used in .NET?](#22-how-can-using-keyword-be-used-in-net)

[23\. What are generics in C#?](#23-what-are-generics-in--)

[24\. What are delegates in C#?](#24-what-are-delegates-in-c)

[25\. What is Entity Framework?](#25-what-is-entity-framework)

[26\. What are the advantages of using EF Core over traditional ADO.NET?](#26-what-are-the-advantages-of-using-ef-core-over-traditional-adonet)

[27\. What are the advantages of LINQ over EF ?](#27-what-are-the-advantages-of-linq-over-ef)

[28\. What is the difference between throw; and throw ex;?](##28-what-is-the-difference-between-throw-and-throw-ex-)

[29\. What is IIS? And why use it?](#29-what-is-iis-and-why-use-it)

[30\. What is Kestrel and how does it differ from IIS?](#30-what-is-kestrel-and-how-does-it-differ-from-iis)

[31\. What’s the difference between synchronous and asynchronous programming in ASP.NET Core?](#31-whats-the-difference-between-synchronous-and-asynchronous-programming-in-aspnet-core)

[32\. What is the difference between Stored Procedure, View and Function in SQL?](#32-what-is-the-difference-between-stored-procedure-view-and-function-in-sql)

[33\. What is the difference between Primary Key and Unique Key in SQL?](#33-what-is-the-difference-between-primary-key-and-unique-key-in-sql)

[34\. What is the difference between DELETE, DROP and TRUNCATE in SQL?](#34-what-is-the-difference-between-delete-drop-and-truncate-in-sql)

[35\. What are the types of cookies available in ASP.NET?](#35-what-are-the-types-of-cookies-available-in-aspnet)

[36\. Difference between View Controller and APIs in ASP.NET?](#36-difference-between-view-controller-and-apis-in-aspnet)

[37\. Explain about caching in .NET](#37-explain-about-caching-in-net)

[38\. What is the difference between Dispose and Finalize in .NET?](#38-what-is-the-difference-between-dispose-and-finalize-in-net)

## Cracking the Code: Your Ultimate Guide to .NET Interview Preparation

### 1. How does .NET Framework work?

.NET framework-based applications, written in languages like C#, F#, or Visual Basic, are compiled into a special kind of code called **Common Intermediate Language** (CIL). This CIL code is stored in files known as assemblies, which usually have a .dll or .exe extension.

Now, when you run a .NET application, something called the **Common Language Runtime** (CLR) comes into play. The CLR is like the engine that makes .NET applications run smoothly. It takes the assembly file containing the CIL code and uses a component called the **Just-In-Time** (JIT) compiler to translate that CIL code into machine code.

Machine code is what your computer's processor understands and can execute. By converting the CIL into machine code on the fly, the JIT compiler ensures that the .NET application can run on any computer, regardless of its specific hardware architecture. This makes .NET applications highly portable and versatile.

C# / F# / VB → CIL (Common Intermediate Language) → Assembly (.dll / .exe) → CLR (Common Language Runtime) → JIT Compiler → Machine Code

### 2. What’s the difference between .NET and .NET Framework?

This is one of the most common dot NET Core interview questions that interviewers will ask you. .NET Core and .NET Framework are both web development frameworks for building applications using the .NET technology stack. However, the two have some key differences.

**.NET Core is an open-source, cross-platform framework** with core libraries (in NuGet packages) for building modern, cloud-based, and microservices-based applications. It supports development on Linux, macOS, and Windows and provides a modular lightweight runtime deployed as a self-contained executable or a shared library.

**.NET Framework**, on the other hand, is a **Windows-only framework** for developing classes and libraries and running code on web services and traditional desktop applications. It provides a larger set of libraries and features than .NET Core, but it’s limited to Windows and is not open-source.

### 3. What is an EXE and a DLL?

EXE and DLLs are both types of assembly executable modules used in .NET applications.

An EXE file is an executable file that runs the application it's designed for. When you build an application, you typically generate an EXE file. When you run this EXE, its associated assemblies are loaded directly. However, EXE files are typically specific to one application and cannot be easily shared with other applications.

On the other hand, a Dynamic Link Library (DLL) is a library containing code that can be shared among multiple applications. DLLs encapsulate code that needs to be hidden and can be used by different programs or applications. 

In a .NET application, you can have multiple DLLs, each containing specific functionality that can be shared across different parts of the application or even with other applications. This makes DLLs a powerful tool for modularizing code and promoting code reuse in software development.

### 4. Explain MVC

MVC, or Model-View-Controller, is a software architectural pattern widely used in web development to structure and organize code in a way that separates concerns and enhances maintainability, scalability, and testability of applications. Let's break down the components of MVC:

#### 1\. Model

- The Model represents the application's data and business logic.
- It encapsulates the data and behavior of the application and interacts with the database, file system, or any other data source.
- Models are responsible for managing data, performing calculations, and enforcing business rules.

#### 2\. View

- The View is responsible for presenting the user interface to the user.
- It receives data from the Model and displays it in a user-friendly format, such as HTML, XML, or JSON.
- Views are typically passive and do not contain business logic. They only display data provided by the Controller.

#### 3\. Controller

- The Controller acts as an intermediary between the Model and the View.
- It receives user input from the View, processes it, interacts with the Model to retrieve or modify data, and determines which View to render in response.
- Controllers handle user requests, execute business logic, and orchestrate the flow of data between the Model and the View.

#### Example Workflow

1. User Interaction: A user interacts with the View, such as submitting a form or clicking a button.
2. Controller Action: The View sends the user input to the Controller, which processes the request.
3. Model Update: The Controller interacts with the Model to perform business logic, such as updating the database or retrieving data.
4. View Rendering: The Controller selects an appropriate View and passes data to it.
5. Presentation: The View renders the data received from the Controller and presents it to the user.
6. Response: The rendered View is sent back to the user's browser for display.

### 5. Explain OOPS Concept

The key concepts of OOPs are

1. Abstraction
2. Encapsulation
3. Inheritance
4. Polymorphism

#### Encapsulation

Encapsulation is the concept of bundling data (attributes) and methods (functions) that operate on the data into a single unit, known as a class.

It restricts direct access to some of the object's components, which can help prevent accidental interference and misuse of the data. 

Instead, access to the data is typically provided through public methods.

#### Abstraction

Abstraction is the process of hiding the complex implementation details and showing only the essential features of the object. 

It helps to reduce programming complexity and effort. 

In OOP, abstraction can be achieved through abstract classes and interfaces.

#### Inheritance

Inheritance is the mechanism by which one class (child class) can inherit the properties and methods of another class (parent class). 

It promotes code reusability and establishes a relationship between different classes.

#### Polymorphism

Polymorphism allows methods to do different things based on the object it is acting upon, even though they share the same name. 

It can be achieved through method overloading (compile-time polymorphism) and method overriding (runtime polymorphism).

To learn more, check [OOPs interview questions with code examples.](oops-interview-questions)

### 6. What is method overloading and method overriding?

#### Method Overloading / Compile Time Polymorphism / Static Polymorphism

Method overloading is a compile-time polymorphism feature that allows a class to have multiple methods with the same name but different parameter lists (different number of parameters, types of parameters, or both). The correct method to call is determined at compile-time based on the method signature.

Key Points:

- Methods must have the same name.
- Methods must differ in the type, number, or order of parameters.
- Return type can be different, but it is not considered when determining method overloading.

```cs
using System;

class Calculator
{
    // Method Overloading based on the number of parameters
    public int Add(int a, int b)
    {
        return a + b;
    }

    // Overloaded method with different parameter type
    public double Add(double a, double b)
    {
        return a + b;
    }

    // Overloaded method with a different number of parameters
    public int Add(int a, int b, int c)
    {
        return a + b + c;
    }
}

class Program
{
    static void Main()
    {
        Calculator calc = new Calculator();
        Console.WriteLine(calc.Add(2, 3));        // Calls the first method (int, int)
        Console.WriteLine(calc.Add(2.5, 3.5));    // Calls the second method (double, double)
        Console.WriteLine(calc.Add(1, 2, 3));     // Calls the third method (int, int, int)
    }
}
```

#### Method Overriding / Runtime Polymorphism / Dynamic Polymorphism

Method overriding is a runtime polymorphism feature that allows a subclass to provide a specific implementation of a method that is already defined in its superclass. The overridden method in the subclass must have the same name, return type, and parameters as the method in the superclass.

Key Points:

- Methods must have the same name, return type, and parameters.
- The method in the base class must be marked as virtual, abstract, or override.
- The method in the derived class must use the override keyword.

```cs
using System;

class Animal
{
    // Base class method
    public virtual void Speak()
    {
        Console.WriteLine("Animal makes a sound");
    }
}

class Dog : Animal
{
    // Overriding the base class method
    public override void Speak()
    {
        Console.WriteLine("Dog barks");
    }
}

class Program
{
    static void Main()
    {
        Animal animal = new Animal();
        animal.Speak();   // Calls base class method
        
        Dog dog = new Dog();
        dog.Speak();      // Calls overridden method
        
        Animal dogAsAnimal = new Dog();
        dogAsAnimal.Speak();  // Calls overridden method using base class reference
    }
}
```

### 7. Difference between abstraction and interface

1. Purpose:
    - Abstraction: Focuses on hiding the implementation details and providing a template for derived classes.
    - Interface: Specifies a contract that classes must adhere to, enabling polymorphism.
2. Implementation:
    - Abstraction: Achieved using abstract classes that can include both abstract methods (without implementation) and concrete methods (with implementation).
    - Interface: Achieved using interfaces that can only contain method signatures and properties but no implementation.
3. Multiple Inheritance:
    - Abstraction: A class can inherit only one abstract class (single inheritance).
    - Interface: A class can implement multiple interfaces, allowing for multiple inheritance.
4. Method Implementation:
    - Abstraction: Abstract classes can have both abstract methods (which must be implemented by derived classes) and concrete methods (which are already implemented).
    - Interface: Interfaces cannot have any method implementations.
5. Access Modifiers:
    - Abstraction: Abstract classes can have access modifiers (public, protected, etc.) for their members.
    - Interface: Members of an interface are implicitly public, and access modifiers are not allowed.
6. State Management:
    - Abstraction: Abstract classes can have fields to maintain state.
    - Interface: Interfaces cannot have fields; they cannot maintain state.

#### Summary

Use abstract classes when you have a base class that should provide some default behavior or state and want to ensure that derived classes implement specific functionality.

Use interfaces when you want to define a contract that multiple classes can implement, promoting loose coupling and flexibility in your code design.

### 8. Explain SOLID Principles

#### S: Single Responsibility Principle (SRP)

SRP says, "Every software module should have only one reason to change."

#### O: Open-closed Principle (OCP)

The Open/closed Principle says, "A software module/class is open for extension and closed for modification."

#### L: Liskov substitution Principle (LSP)

The Liskov Substitution Principle (LSP) states, "you should be able to use any derived class instead of a parent class and have it behave in the same manner without modification.". 

It ensures that a derived class does not affect the behavior of the parent class; in other words, a derived class must be substitutable for its base class.

This principle is just an extension of the Open Closed Principle, and we must ensure that newly derived classes extend the base classes without changing their behavior.

#### I: Interface Segregation Principle (ISP)

The Interface Segregation Principle states "that clients should not be forced to implement interfaces they don't use. 

Instead of one fat interface, many small interfaces are preferred based on groups of methods, each serving one submodule.".

#### D: Dependency Inversion Principle (DIP)

The Dependency Inversion Principle (DIP) states that high-level modules/classes should not depend on low-level modules/classes. 

First, both should depend upon abstractions. 

Secondly, abstractions should not rely upon details. 

Finally, details should depend upon abstractions.

To learn more, check out [SOLID principles with code examples.](solid-principles-in-c-sharp-questions)

### 9. How does ASP.NET Core handle dependency injection?

Dependency Injection (DI) is a fundamental design pattern in ASP.NET Core that promotes the development of loosely coupled and testable code.

ASP.NET Core has a built-in dependency injection container that is both powerful and flexible, allowing developers to manage dependencies effectively.

There are several ways to configure the container, including the ConfigureServices method in the Startup class (the entry point of a .NET application), attributes on classes and properties, and the service provider itself. 

ASP.NET Core supports constructor, property, and method injection, allowing dependencies to be dynamically injected into methods at runtime.

However, a more up-to-date way to handle dependency injection in ASP.NET Core focuses on singleton, transient, and scoped service lifetimes.

### 10 What is the difference between Singleton, Transient and Scoped Lifetime?

In dependency injection (DI) within ASP.NET Core, the lifetime of a service dictates how long the service instance will be retained and reused. 

The three main lifetimes are Singleton, Transient, and Scoped. Here’s a detailed explanation of each:

- **Singleton Lifetime**

A singleton service is created only once per application (or per DI container) and is shared throughout the application's lifetime.

Use case: Configuration Settings that don't change, Logging Services not maintaining state, caching services, external API client and so on.

- **Transient Lifetime**

A transient service is created each time it is requested. A new instance is provided to every component that requires it.

Use case: Calculating user's score

- **Scoped Lifetime**

A scoped service is created once per request (or per scope). This means that within the context of a single web request, all components that require a scoped service will receive the same instance.

Use case: Database Context, Unit of Work etc which are tied to a single HTTP request.

### 11. What is middleware in .NET core?

Middleware plays a crucial role in ASP.NET Core applications, enabling developers to structure request and response handling effectively. Here's a breakdown of how middleware works and its significance:

#### 1\. Request and Response Handling

- Middleware components are assembled into an application pipeline, which manages incoming requests and outgoing responses.
- Each component in the pipeline decides whether to pass the request to the next component or carry out additional work before and after passing it along.

#### 2\. Built-in and Custom Middleware

- Middleware can be built-in within the .NET Core framework or developed as custom components.
- Built-in middleware is often added through NuGet packages and integrated into the application's startup class within the Configure method.

#### 3\. Request Processing Pipeline

- The Configure method within the application startup class sets up the request processing pipeline.
- This pipeline consists of a sequence of request delegates, with each middleware component representing a delegate.

#### 4\. Middleware Functionality

- Each middleware component typically handles incoming requests and then passes the response to the next middleware in the pipeline.
- However, a middleware component has the option to short-circuit the pipeline or terminate the request processing.
- Short-circuiting the pipeline occurs when a middleware component decides not to call the next middleware, thus avoiding unnecessary processing.

#### Example Scenarios

1. User Authentication Middleware: Verifies user credentials and authorizes access to protected resources.
2. Error Handling Middleware: Catches and processes exceptions, providing custom error responses.

#### Benefits of Middleware

- Flexibility: Middleware allows developers to modularize request processing logic, making it easy to add, remove, or reorder components.
- Efficiency: Short-circuiting the pipeline reduces unnecessary processing, improving application performance.
- Separation of Concerns: Each middleware component focuses on a specific aspect of request handling, promoting code organization and maintainability.

### 12. What’s the difference between middleware and a filter in ASP.NET Core?

In ASP.NET Core, middleware and filters are two mechanisms used for processing requests and responses.

#### Key Differences

1. Scope:
    - Middleware: Applies globally to all requests in the application.
    - Filters: Applied to specific controllers or actions within an MVC application.
2. Execution Context:
    - Middleware: Executes in a linear, pipeline manner where each middleware component can control the flow of request processing.
    - Filters: Executes in the context of MVC request processing, specifically around the execution of action methods.
3. Purpose:
    - Middleware: Generally used for broad tasks that need to be applied across all requests, such as logging, error handling, and serving static files.
    - Filters: Used for more specific tasks related to the execution of MVC actions, such as authorization, validation, and action result processing.
4. Implementation and Configuration:
    - Middleware: Configured in the Startup class within the Configure method.
    - Filters: Applied via attributes directly on controllers or actions, or globally via configuration in the Startup class.

### 13. What are different types of exceptions in .NET and how are they handled?

In .NET, exceptions are objects that encapsulate information about an error that has occurred. 

They are derived from the base class `System.Exception`. 

There are several types of exceptions in .NET, and they are handled using structured exception handling constructs like try, catch, finally, and throw.

### 14. Explain the differences between value type and reference type

The main differences between value type and reference type are given below:

#### Value Types

- Holds the actual data directly within the memory location.
- Stores its contents on the stack memory.
- When assigning a value type variable to another, the value is copied directly.
- Examples include predefined data types (int, float, bool), structures, and enums.

#### Reference Types

- Contains a pointer that refers to another memory location holding the actual data.
- Stores its contents on the heap memory.
- When assigning a reference type variable to another, it creates a second copy of the reference, not the actual data.
- Examples include classes, objects, arrays, indexers, and interfaces.

### 15. Explain boxing and unboxing in C# with example.

Boxing is the process of converting a value type into a reference type directly. Boxing is implicit.

Unboxing is the process where reference type is converted back into a value type. Unboxing is explicit.

An example is given below to demonstrate boxing and unboxing operations:

```cs
int a = 10; // a value type

object o = a; // boxing

int b = (int)o; // unboxing
```

### 16. What is a garbage collector?

In .NET development, the garbage collector plays a vital role in managing memory and ensuring efficient resource utilization. Let's dive into the key concepts surrounding garbage collection:

#### 1\. Generations in Memory Heap

- Generation 0: Contains short-lived objects.
- Generation 1: Stores medium-lived objects.
- Generation 2: Reserved for long-lived objects.

#### 2\. Garbage Collection Process

- Identification: The garbage collector identifies objects in the managed heap that are no longer in use by the application.
- Update References: References to compacted objects are updated to reflect their new memory locations.
- Reclamation: Memory space occupied by dead objects is reclaimed, and remaining objects are moved to an older segment.

#### 3\. Triggering Garbage Collection

- Garbage collection is automatically triggered by the runtime when memory pressure increases.
- Additionally, developers can manually trigger garbage collection using the `System.GC.Collect()` method.

### 17. What are the different authentication and authorization mechanisms available at ASP.NET core?

#### Authentication Mechanisms

1. Cookie Authentication : Uses cookies to maintain the user session across requests.
2. JWT Bearer Authentication : Uses JSON Web Tokens (JWT) for stateless authentication.
3. vOAuth2 and OpenID Connect : Protocols for secure authentication, supporting single sign-on (SSO).
4. API Key Authentication: Uses API keys for authenticating users.
5. Social Authentication : Enables authentication using social media accounts like Facebook, Google, and Twitter.

#### Authorization Mechanisms

1. Role-Based Authorization : Grants access to users based on their roles.
2. Policy-Based Authorization : Uses policies to implement complex access control rules.
3. Claims-Based Authorization : Grants access based on the claims present in the user’s identity.

### 18. Difference between IEnumerable, ICollection, IList, IQueryable

- **IEnumerable** allows you to access elements of a collection in a **read-only, forward-only** manner. No adding, deleting, or modifying the elements.
- **ICollection** inherits from the IEnumerable interface and provides additional functionality including **adding, deleting, and modifying** elements.
- **IList** extends the ICollection interface and represents strongly typed collections that are accessible via index. So in addition to **adding, deleting, and modifying,** you can insert or remove items **using index values**.
- **IQueryable** extends the IEnumerable interface, provides support for **LINQ**, and is well-suited for working with large datasets. When you use IQueryable with LINQ to SQL or LINQ to Entities, it generates a LINQ to SQL expression that is executed in the data layer of your application.

📌IEnumerable <--- ICollection <--- IList

Quick Recap of What's Inherited:
- IEnumerable: Basic iteration (read-only).
- ICollection: Adds modification (add, remove, clear).
- IList: Adds indexed access to elements (e.g., `myList[0]`).

### 19. What are different C# Access Modifiers?

**public :** The code is accessible for all classes

**private :** The code is only accessible within the same class

**protected :** The code is accessible within the same class, or in a class that is inherited from that class.

**internal :** The code is only accessible within its own assembly, but not from another assembly.

**private protected:** The code is accessible within the same class and derived classes in the same assembly, but not outside that assembly or outside the class hierarchy.

**protected internal:** The code is accessible from any class within the same assembly, as well as any class that inherits from it, even if the subclass is in a different assembly.

```cs
public class BaseClass
{
    public void PublicMethod() { }       // Accessible everywhere
    private void PrivateMethod() { }     // Accessible only within this class
    protected void ProtectedMethod() { } // Accessible within this class and derived classes
    internal void InternalMethod() { }   // Accessible within the same assembly
}
```

You'll likely be asked about **sealed** keyword, but remember it is not an access modifier. The sealed keyword is used to prevent inheritance. When a class or a method is marked as sealed, it means that no other class can inherit from or override the class or method.

### 20. What is the difference between var and dynamic?

**var**

- The variables declared using var keyword are statically typed.
- The type of the variable is decided by the compiler at compile time.
- The variable of this type should be initialized at the time of declaration. So that the compiler will decide the type of the variable according to the value it initialized.

**dynamic**

- The variables declared using dynamic keywords are dynamically typed.
- The type of the variable is decided by the compiler at run time.
- The variable of this type need not be initialized at the time of declaration. Because the compiler does not know the type of the variable at compile time.

### 21. What is the difference between const, readonly and static?

- **const** is used for compile-time constants. The value must be assigned at declaration and cannot be changed. 
- **readonly** is used for runtime constants whose values are set at initialization or in constructors.
- **static** is used for members that belong to the type itself rather than to individual instances and are shared across all instances of the class.

```cs
using System;

public class Example
{
    // const: Compile-time constant, cannot be changed once set
    public const double Pi = 3.14159;

    // readonly: Runtime constant, can only be set in constructor or during declaration
    public readonly int YearOfBirth;

    // static: Belongs to the class itself, shared across all instances
    public static int InstanceCount = 0;

    public Example(int year)
    {
        YearOfBirth = year; // Can set readonly during construction
        InstanceCount++;     // Increment static variable
    }

    public void Display()
    {
        Console.WriteLine($"Pi: {Pi}");                     // const is accessible
        Console.WriteLine($"Year of Birth: {YearOfBirth}");  // readonly can vary per instance
        Console.WriteLine($"Instance Count: {InstanceCount}"); // static is shared
    }
}

public class Program
{
    public static void Main()
    {
        // Create instances of Example
        var example1 = new Example(1990);
        var example2 = new Example(1985);

        // Display information for both instances
        example1.Display();
        example2.Display();

        // Access static variable directly from class
        Console.WriteLine($"Total Instances Created: {Example.InstanceCount}");
        
        // Trying to change const will result in an error
        // Example.Pi = 3.14; // Error: Cannot assign to 'Pi' because it is a 'const'
        
        // Trying to change readonly will result in an error (outside constructor)
        // example1.YearOfBirth = 2000; // Error: Cannot assign to 'YearOfBirth' because it is readonly
    }
}
```

### 22. How can “using” keyword be used in .NET?

- Using Directive

Generally, we use the using keyword to add namespaces in code-behind and class files. Then it makes all the classes, interfaces and abstract classes and their methods and properties available in the current page.

- Using Statement

This is another way to use the using keyword in C#. It plays a vital role in improving performance in Garbage Collection. The using statement ensures that Dispose() is called even if an exception occurs when you are creating objects and calling methods, properties and so on.

### 23. What are generics in C#?

Generics in C# are a way to create code that can be used with different data types. This makes the code more versatile and reusable. Generics are declared using the <> symbol.

Example: &lt;T&gt; tag

### 24. What are delegates in C#?

A [delegate](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/reference-types) is a type that safely encapsulates a method, similar to a function pointer in C and C++. Unlike C function pointers, delegates are object-oriented, type safe, and secure.

A delegate is an object which refers to a method or you can say it is a reference type variable that can hold a reference to the methods.

### 25. What is Entity Framework?

Entity framework (hereafter, EF) is the framework ORM (object-relational mapping) that Microsoft makes available as part of the .NET development.

Its purpose is to abstract the ties to a relational database, in such a way that the developer can relate to the database entity as to a set of objects and then to classes in addition to their properties.

EF mainly allows two types of approaches related to this use. They are Database-First and Code-First

- Code First Approach

In the code first approach we will first create entity classes with properties defined in it. Entity framework will create the database and tables based on the entity classes defined. So the database is generated from the code. When the dot net code is run the database will get created. Migration script is run in this approach.

- Database First Approach

In this approach Database and tables are created first. Then you create an entity Data Model using the created database. Scaffolding command is run in this approach.

### 26. What are the advantages of using EF Core over traditional ADO.NET?

#### **ADO.NET Characteristics**

- Manual SQL Writing: You need to write raw SQL queries or stored procedures, which can be error-prone and less maintainable.
- DataReader and DataSet: You work with lower-level abstractions like DataReader, DataSet, and DataTable, which require manual mapping of data.
- Verbose Code: ADO.NET often requires more verbose code for common data access patterns.

#### **EF Core Characteristics**

- Higher-Level Abstraction: Provides a higher-level abstraction over the database, reducing the need for manual SQL.
- Entity Classes: You work with entity classes that map directly to your database tables.
- Integrated with .NET: Seamlessly integrates with other .NET features like dependency injection and ASP.NET Core.

### 27. What are the advantages of LINQ over EF?

The LINQ to SQL is much simpler than Entity Framework. Because it provides an exact one-to-one mapping between the database table and the class. 

In terms of the Entity framework, there is a many-to-many relation between the database table and the class. A single database table can map to multiple classes. Or a single class can map to multiple tables.

LINQ could be applied to any data source: in-memory objects, XML, SQL, etc.

Entity Framework could use LINQ to perform queries against a relational database.

### 28. What is the difference between throw; and throw ex;?

- “throw” preserves the stack trace (the stack trace will point to the method that caused the exception in the first place)
- ”throw ex” does not preserve the stack trace (we will lose the information about the method that caused the exception in the first place. It will seem like the exception was thrown from the place of its catching and rethrowing).

These might look very similar but understanding these key concepts lays a solid foundation for C# and .NET development. Whether you're a beginner or an experienced developer, mastering these fundamentals will enhance your skills and productivity in building robust applications.

### 29. What is IIS? And why use it?

Internet Information Services (IIS) is a versatile and widely-used web server created by Microsoft for hosting web applications, including ASP.NET and ASP applications.

IIS has its own process engine to handle the requests. Using an IIS computer can work as a web server, and provides functionality to deploy ASP.NET Web applications. It is also responsible for providing responses to the requests made by the users.

### 30. What is Kestrel and how does it differ from IIS?

Kestrel is a cross-platform, lightweight web server used by default in ASP.NET Core applications.

#### **Key Differences Between Kestrel and IIS**

1. Platform Compatibility:
    - Kestrel: Cross-platform; runs on Linux, macOS, and Windows.
    - IIS: Windows-only.
2. Performance and Scalability:
    - Kestrel: Lightweight and designed for high performance and scalability, suitable for handling a large number of requests efficiently.
    - IIS: Also scalable but more resource-intensive due to its comprehensive feature set and deeper integration with Windows services.
3. Features:
    - Kestrel: Basic web server features focusing on speed and efficiency. It lacks some of the advanced features found in IIS.
    - IIS: Rich feature set, including support for HTTP/2, WebSockets, advanced authentication mechanisms, detailed logging, and more.
4. Use Cases:
    - Kestrel: Ideal for cross-platform applications and microservices where a lightweight, fast web server is needed. Often used in combination with a reverse proxy server.
    - IIS: Best suited for enterprise applications that require deep integration with Windows features, advanced security options, and robust management capabilities.
5. Reverse Proxy:
    - Kestrel: Typically used behind a reverse proxy server like IIS, Nginx, or Apache to handle tasks such as load balancing, SSL termination, and static content serving.
    - IIS: Can act as both the web server and reverse proxy, handling all aspects of web request processing.
6. Security and Authentication:
    - Kestrel: Provides basic security features; for advanced security needs, it relies on the reverse proxy server.
    - IIS: Extensive security features, including support for various authentication methods, SSL/TLS termination, and detailed access controls.


### 31. What’s the difference between synchronous and asynchronous programming in ASP.NET Core?

#### **Synchronous Programming**

In synchronous programming, the execution of code is sequential and blocks further execution until the current task is completed. Each operation must finish before the next one starts.

Characteristics:

- Blocking: When a synchronous method calls another method, it waits (blocks) until the called method completes before proceeding to the next line of code.
- Simple Execution Flow: Easier to write and understand because it follows a straightforward, step-by-step sequence.
- Resource Intensive: Can lead to inefficient use of resources, particularly when dealing with I/O-bound operations like reading from a database, file, or network.

Use Case Example:

- Simple Tasks: Suitable for quick, non-blocking operations where the overhead of context switching outweighs the benefits of asynchrony.

#### **Asynchronous Programming**

Asynchronous programming allows multiple operations to run concurrently. It frees up the main thread to perform other tasks while waiting for long-running operations to complete.

Characteristics:

- Non-Blocking: When an asynchronous method calls another method, it does not wait for the called method to complete. Instead, it continues executing the next line of code and returns control to the caller.
- Concurrency: Improves application responsiveness and scalability by handling I/O-bound operations more efficiently.
- Complex Execution Flow: Can be more challenging to write and understand due to the potential for race conditions and callback hell.

Keywords:

`async`: Used to define an asynchronous method.

`await`: Indicates that the calling code should wait for the asynchronous method to complete before continuing.

### 32. What is the difference between Stored Procedure, View and Function in SQL?

#### Stored Procedure

A stored procedure is a precompiled collection of SQL statements and procedural logic stored in the database.

It allows you to group and organize SQL statements into a single unit of work that can be executed repeatedly. 

Stored procedures are commonly used for complex data manipulation, business logic implementation, and to encapsulate frequently performed tasks.

#### View

A view is a virtual table generated as the result of a SELECT query stored in the database. 

It provides a way to simplify complex queries and encapsulate them into reusable objects. 

Views are commonly used to abstract complex joins, apply security filters, and present data in a structured format. 

It can be queried like a table, but the underlying data is not physically stored; instead, it's generated dynamically when the view is queried.

#### Function

A function is a reusable set of SQL statements that can accept parameters, perform computations, and return a single value or a table variable. 

It provides a way to encapsulate common computations or transformations into reusable modules. 

Functions are commonly used in calculations, data transformations, and as part of queries to simplify complex expressions.

It can accept input parameters, perform calculations or data manipulations, and return a single value or a result set.

### 33. What is the difference between Primary Key and Unique Key in SQL?

- **Null Values**: Primary Key columns cannot contain NULL values, while Unique Key columns can allow NULL values (with certain restrictions).
- **Number of Keys**: Each table can have only one Primary Key, but multiple Unique Key constraints can be defined in a table.
- **Indexing**: Primary Key constraints typically create a clustered index, while Unique Key constraints do not automatically create any index (though you can manually create indexes).
- **Usage**: Primary Keys are used to uniquely identify each row and establish relationships between tables, while Unique Keys are used to enforce uniqueness but are not necessarily used for identification.

### 34. What is the difference between DELETE, DROP and TRUNCATE in SQL? 

- `DELETE` is used to remove specific rows from a table based on conditions, while TRUNCATE removes all rows from a table.
- `DROP` is used to remove entire database objects, including tables, views, and stored procedures, from the database.
- `DELETE` and TRUNCATE can be rolled back (if used within a transaction), while DROP is irreversible.
- `TRUNCATE` is generally faster than DELETE, especially for large tables, as it doesn't log individual row deletions.

### 35. What are the types of cookies available in ASP.NET?

In ASP.NET, cookies are used to store small pieces of data on the client-side. There are two main types of cookies in ASP.NET:

#### 1\. Persistent Cookies
Persistent cookies are stored on the user's computer and remain there even after the browser is closed. They have an expiration date and time, which determines how long they will persist on the client-side.

#### 2\. Session Cookies
Session cookies are stored in memory and are available for the duration of the user's session. They are deleted once the user closes the browser.

### 36. Difference between View Controller and APIs in ASP.NET?

#### View Controller

A View Controller, often found in MVC (Model-View-Controller) architecture, is responsible for managing the user interface and user interactions. It acts as an intermediary between the Model (data) and the View (user interface), handling the input from users, updating the View, and sometimes manipulating the Model.

#### API (Application Programming Interface)

An API, particularly a web API, allows different software systems to communicate with each other over the internet. It exposes endpoints that can be accessed via HTTP requests, typically to perform CRUD (Create, Read, Update, Delete) operations on data.

To learn more, check [interview questions on .NET REST API.](rest-api-interview-questions)

### 37. Explain about caching in .NET

Caching in .NET is a technique used to store frequently accessed data in a temporary storage location to improve the performance and scalability of an application. By caching data, an application can reduce the need to repeatedly fetch the same data from a slower data source, such as a database or external service, thereby speeding up data retrieval and reducing load on the underlying data source.

#### Types of Caching in .NET

#### 1\. In-Memory Caching:
- Stores data in the memory of the application server.
- Suitable for caching small to moderate amounts of data that can fit into the memory.
- Commonly used for session data, small datasets, configuration settings, etc.

#### 2\. Distributed Caching:
- Stores data across multiple servers or nodes.
- Suitable for large-scale applications or applications deployed in a cloud environment.
- Examples include Redis, NCache, and Memcached.

### 38. What is the difference between Dispose and Finalize in .NET?

Dispose is used to explicitly release unmanaged resources (e.g., file handles, database connections, etc.) and perform other cleanup operations. Useful for deterministic cleanup of resources, meaning you know exactly when the resources will be released.

Finalize is used to release unmanaged resources before an object is reclaimed by the garbage collector. It is called by the garbage collector and not manually by the developer. Acts as a safety net to clean up resources in case Dispose was not called.

To learn more, check [interview questions on Entity Framework and SQL.](sql-entity-framework-interview-questions)

### Conclusion

ASP.NET is a versatile framework that empowers developers to build modern, scalable web applications and services. 

Whether you're building a simple website, a complex enterprise application, or a RESTful API, ASP.NET provides the tools and capabilities you need to succeed. 

By mastering ASP.NET, you can unlock new opportunities in your career and stay ahead in the ever-evolving field of web development.

If you prefer offline preparation for your .NET interview, [download the ebook for free](https://hassansadeedali.gumroad.com/l/dotnetinterviews)

Checkout [Blind 75 Leetcode problems](/blind-75-leetcode-problems), a curated list of the most essential coding questions to crack your next technical interviews.

And don’t miss our comprehensive guide, [Cracking Tech Interviews: From Resume Preparation To Offer Negotiation](https://dotnetinterviews.gumroad.com/l/cracktechinterview) 
