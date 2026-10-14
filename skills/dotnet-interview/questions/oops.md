# OOP Interview Questions

## 1. OOP Fundamentals

### Beginner
1. What is object-oriented programming (OOP)?
2. What are the four pillars of OOP?
3. What is the difference between a class and an object?
4. What is the difference between a field, property, and method in C#?
5. What are constructors, and what types of constructors does C# support?
6. What is encapsulation? How does C# implement it?
7. What is abstraction? How is it different from encapsulation?

### Intermediate
8. What is the difference between an abstract class and an interface?
9. What is the difference between an object’s state and behavior?
10. What is composition, and how does it differ from inheritance?
11. What is the difference between association, aggregation, and composition?
12. What is the difference between a static class and a sealed class?

## 2. Inheritance

### Beginner
13. What is inheritance, and why is it useful?
14. Does C# support multiple inheritance of classes?
15. What is the difference between a base class and a derived class?
16. What is the purpose of the `base` keyword?

### Intermediate
17. What is the difference between `virtual`, `override`, and `new` in C#?
18. What happens when a derived class hides a base-class method using `new`?
19. Can constructors be inherited in C#?
20. What is the diamond problem, and how does C# avoid it for class inheritance?
21. When can inheritance lead to poor design?

### Advanced
22. Explain the Liskov Substitution Principle with a practical example.
23. How can inheritance introduce tight coupling?
24. When would you replace an inheritance hierarchy with composition?

## 3. Polymorphism

### Beginner
25. What is polymorphism?
26. What is the difference between compile-time and runtime polymorphism?
27. What is method overloading?
28. What is method overriding?

### Intermediate
29. What is the difference between overloading and overriding?
30. How does runtime polymorphism work in C#?
31. What happens when a virtual method is called through a base-class reference?
32. Can static methods be overridden?
33. Can properties be virtual or overridden in C#?

### Advanced
34. What is the difference between method hiding and method overriding?
35. How does polymorphism help implement the Open/Closed Principle?
36. How would you design a payment system that supports multiple payment providers using polymorphism?

## 4. Abstraction and Encapsulation

37. Why do we need abstraction?
38. How do interfaces help achieve abstraction?
39. How does encapsulation protect an object’s invariants?
40. Why might public setters lead to an anemic or invalid domain model?
41. When would you expose a method instead of a property?
42. Can an abstract class contain implemented methods and constructors?
43. Can an interface contain method implementations in modern C#?
44. When would you choose an abstract class over an interface?

## 5. Interfaces and Abstract Classes

45. Can a class implement multiple interfaces?
46. Can an abstract class implement an interface without implementing all its members?
47. What is explicit interface implementation?
48. When is explicit interface implementation useful?
49. What are default interface methods, and when might they be useful?
50. How do interfaces support dependency inversion and testability?
51. What problems can arise from creating too many small interfaces?

## 6. SOLID Principles

52. Explain the Single Responsibility Principle with a C# example.
53. Explain the Open/Closed Principle.
54. Explain the Liskov Substitution Principle.
55. Explain the Interface Segregation Principle.
56. Explain the Dependency Inversion Principle.
57. How is dependency inversion different from dependency injection?
58. Can following SOLID principles make a design worse? Explain.
59. How would you refactor a class that handles validation, persistence, email, and reporting?

## 7. Object and Type Behavior in C#

60. What is the difference between value types and reference types?
61. What is the difference between `==` and `Equals()`?
62. What is the purpose of `GetHashCode()`?
63. Why should `Equals()` and `GetHashCode()` remain consistent?
64. What is the difference between shallow copying and deep copying?
65. What are records, and how do they differ from ordinary classes?
66. What are immutable objects, and why are they useful?
67. What is the purpose of `IDisposable`?
68. How do access modifiers support encapsulation?

## 8. Design and Real-World Scenarios

69. Design a notification system that supports email, SMS, and push notifications.
70. How would you design a discount engine that supports new discount types without repeatedly modifying existing code?
71. A base class has several methods that some derived classes cannot meaningfully implement. What might this indicate?
72. A class has 15 dependencies injected through its constructor. What would you investigate before refactoring it?
73. How would you replace a large switch statement that selects behavior based on customer type?
74. How would you unit-test a class that depends on an external payment provider?
75. A developer creates an interface for every class. Is this good design? Why or why not?
76. How would you model an order that must never transition from Cancelled back to Confirmed?
77. How would you decide between inheritance, composition, and dependency injection for a new feature?

## 9. Senior-Level Discussion

78. Explain how the SOLID principles relate to maintainability and changeability.
79. Describe a case where composition is preferable even when an inheritance relationship appears natural.
80. How can abstractions make a system harder to understand or maintain?
81. How do domain models differ from data-transfer objects?
82. What is an anemic domain model, and when might a simpler data model be appropriate?
83. How would you evolve a public interface without breaking existing implementations?
84. How do polymorphism and dependency injection work together in an extensible .NET application?
85. Describe a design decision where you deliberately avoided introducing an abstraction.
