# Top 100 Java Interview Questions and Answers

## 1. What is Java?
Java is a high-level, object-oriented programming language that is platform-independent due to the Java Virtual Machine (JVM).

## 2. What are the features of Java?
Platform-independent, Object-oriented, Simple, Secure, Robust, Multithreaded, Distributed, Dynamic, Portable, and High-performance.

## 3. What is JVM, JDK, and JRE?
- **JVM (Java Virtual Machine):** Runs Java bytecode.
- **JDK (Java Development Kit):** Tools required to develop Java applications.
- **JRE (Java Runtime Environment):** Provides libraries and JVM to run Java applications.

## 4. What is the difference between JDK and JRE?
- **JDK** is used to develop Java applications (includes JRE).
- **JRE** is used to run Java applications.

## 5. What is a Class in Java?
A class is a blueprint for creating objects, defining properties and methods.

## 6. What is an Object in Java?
An instance of a class.

## 7. What is Inheritance?
Inheritance allows one class to inherit properties and methods from another.

## 8. What is Polymorphism in Java?
Polymorphism allows methods to behave differently based on the object calling them (method overloading and overriding).

## 9. What is Abstraction?
Abstraction hides implementation details and shows only functionality.

## 10. What is Encapsulation?
Encapsulation wraps data and methods in a single unit (class) and restricts access to them via access modifiers.

## 11. What are access modifiers?
Access modifiers define the visibility of classes, methods, and variables (private, public, protected, default).

## 12. What is the difference between private, protected, and public?
- **Private:** Accessible only within the same class.
- **Protected:** Accessible within the same package and subclasses.
- **Public:** Accessible from anywhere.

## 13. What is a Constructor in Java?
A constructor is a special method used to initialize objects. It has the same name as the class.

## 14. What is method overloading?
Method overloading occurs when multiple methods with the same name but different parameters are defined in a class.

## 15. What is method overriding?
Method overriding occurs when a subclass provides a specific implementation of a method already defined in its parent class.

## 16. What is the `super` keyword in Java?
`super` is used to refer to the immediate parent class object and call parent class methods or constructors.

## 17. What is `this` keyword in Java?
`this` refers to the current object instance.

## 18. What is a static method?
A static method belongs to the class rather than any instance and can be called without creating an object.

## 19. Can we override static methods?
No, static methods cannot be overridden because they belong to the class, not instances.

## 20. What is the difference between static and non-static methods?
- **Static methods** are class-level methods.
- **Non-static methods** are object-level methods.

## 21. What is final keyword?
The `final` keyword can be used with variables, methods, and classes to prevent modification:
- **Final variable:** Cannot be changed.
- **Final method:** Cannot be overridden.
- **Final class:** Cannot be extended.

## 22. Can a constructor be made final?
No, constructors cannot be declared as `final`.

## 23. What is an interface?
An interface is a reference type in Java, similar to a class, that can contain only constants, method signatures, default methods, static methods, and nested types.

## 24. Can a class implement multiple interfaces?
Yes, a class can implement multiple interfaces, providing multiple inheritance.

## 25. What is the difference between abstract class and interface?
- **Abstract class:** Can have both abstract and concrete methods, can have state.
- **Interface:** Can only have abstract methods (Java 7) and static/default methods (Java 8+).

## 26. What is an abstract class?
An abstract class cannot be instantiated and may contain abstract methods that must be implemented by subclasses.

## 27. Can a class extend multiple classes in Java?
No, Java does not support multiple inheritance of classes.

## 28. What is the purpose of the `main()` method?
The `main()` method serves as the entry point for Java applications.

## 29. Why is the main method static?
The `main()` method is static so it can be called without creating an instance of the class.

## 30. Can we overload the main method?
Yes, the main method can be overloaded, but the JVM calls only the signature `public static void main(String[] args)`.

## 31. What is the difference between Array and ArrayList?
- **Array:** Fixed in size, supports primitive types.
- **ArrayList:** Resizable, supports only objects.

## 32. What is the difference between String, StringBuilder, and StringBuffer?
- **String:** Immutable.
- **StringBuilder:** Mutable, not thread-safe.
- **StringBuffer:** Mutable, thread-safe.

## 33. What is a Wrapper class in Java?
Wrapper classes provide a way to use primitive data types (int, char, etc.) as objects (Integer, Character, etc.).

## 34. What is Autoboxing and Unboxing?
- **Autoboxing:** Converting a primitive type to its corresponding wrapper class.
- **Unboxing:** Converting a wrapper class to its corresponding primitive type.

## 35. What is Exception Handling in Java?
Exception handling is managing runtime errors using `try`, `catch`, `finally`, `throw`, and `throws`.

## 36. What are checked and unchecked exceptions?
- **Checked exceptions:** Checked at compile-time (e.g., IOException).
- **Unchecked exceptions:** Checked at runtime (e.g., NullPointerException).

## 37. What is the difference between `throw` and `throws`?
- **throw:** Used to explicitly throw an exception.
- **throws:** Used in method declaration to specify the exceptions a method can throw.

## 38. What is a try-catch block?
A `try-catch` block is used to handle exceptions by wrapping risky code in `try` and handling exceptions in `catch`.

## 39. What is the finally block?
The `finally` block is executed after `try-catch`, regardless of an exception being thrown.

## 40. What is a NullPointerException?
A NullPointerException occurs when trying to use an object reference that has a null value.

## 41. What is the use of `synchronized` keyword?
`synchronized` is used to ensure that a method or block is accessed by only one thread at a time.

## 42. What is multithreading?
Multithreading is the concurrent execution of multiple threads.

## 43. What is the difference between `wait()` and `sleep()`?
- **wait():** Pauses the thread and releases the lock.
- **sleep():** Pauses the thread but does not release the lock.

## 44. What is the `volatile` keyword?
`volatile` ensures visibility of changes to variables across threads.

## 45. What is the difference between `Runnable` and `Thread` in Java?
- **Runnable:** Interface that allows the creation of a thread by implementing the `run()` method.
- **Thread:** Class that directly extends thread capabilities.

## 46. What is a Deadlock?
A deadlock occurs when two or more threads are blocked forever, waiting for each other.

## 47. What is garbage collection in Java?
Garbage collection is the process of reclaiming unused memory automatically in Java.

## 48. What are memory areas allocated by JVM?
- Method Area
- Heap Area
- Stack Area
- PC Registers
- Native Method Stacks

## 49. What is the difference between `equals()` and `==`?
- `equals()` checks the equality of objects based on content.
- `==` checks reference equality.

## 50. What is a singleton class?
A singleton class allows only one instance to be created throughout the application.

...
## 51. What is the `hashCode()` method?
The `hashCode()` method provides a unique integer value for objects, which is used in hashing data structures like `HashMap`.

## 52. What is a `Map` in Java?
A `Map` is a collection that stores key-value pairs, where each key is unique.

## 53. What is the difference between `HashMap` and `Hashtable`?
- **HashMap:** Non-synchronized, allows null keys and values.
- **Hashtable:** Synchronized, does not allow null keys or values.

## 54. What is `fail-fast` in Java?
`Fail-fast` behavior occurs when a collection's iterator immediately throws an exception if the collection is structurally modified.

## 55. What is a `fail-safe` in Java?
`Fail-safe` behavior allows the collection to be modified while iterating over it without throwing an exception (e.g., `CopyOnWriteArrayList`).

## 56. What is the `Iterator` interface?
The `Iterator` interface is used to iterate over elements of a collection sequentially.

## 57. What is the `Comparable` interface?
`Comparable` is used to define the natural ordering of objects by implementing the `compareTo()` method.

## 58. What is the `Comparator` interface?
`Comparator` is used to define custom ordering of objects by implementing the `compare()` method.

## 59. What is the difference between `Comparable` and `Comparator`?
- **Comparable:** Defines natural ordering of objects (implemented in the object itself).
- **Comparator:** Defines custom ordering (implemented externally).

## 60. What is the `Collections` class?
`Collections` is a utility class in Java that provides static methods to manipulate and operate on collections (like sorting, searching).

## 61. What is an immutable object?
An immutable object is an object whose state cannot be changed after it is created (e.g., `String`).

## 62. How can you make an object immutable?
To make an object immutable:
- Declare all fields as `final`.
- Don't provide setter methods.
- Make fields private and ensure no references to mutable objects are returned.

## 63. What is the difference between `StringBuilder` and `StringBuffer`?
- **StringBuilder:** Faster, non-thread-safe.
- **StringBuffer:** Slower, thread-safe.

## 64. What is `ConcurrentHashMap`?
`ConcurrentHashMap` is a thread-safe implementation of `HashMap`, allowing concurrent access without locking the entire map.

## 65. What is the difference between `Set` and `List`?
- **Set:** Stores unique elements, unordered.
- **List:** Allows duplicate elements, ordered.

## 66. What is a `TreeMap` in Java?
`TreeMap` is a `Map` implementation that stores its entries in a sorted order based on the natural ordering of keys or a custom `Comparator`.

## 67. What is the `transient` keyword?
The `transient` keyword prevents variables from being serialized.

## 68. What is serialization?
Serialization is the process of converting an object into a byte stream to be stored or transmitted.

## 69. What is the `Serializable` interface?
`Serializable` is a marker interface used to indicate that a class's objects can be serialized.

## 70. What is externalization?
Externalization is an interface that provides more control over the serialization process by defining custom read and write methods.

## 71. What is reflection in Java?
Reflection allows inspection and modification of classes, methods, and fields at runtime.

## 72. What is the purpose of the `Class` class in Java?
The `Class` class is used to obtain information about a class, such as methods, fields, constructors, and more, at runtime.

## 73. What are annotations in Java?
Annotations provide metadata about code but do not affect the program's execution.

## 74. What are some built-in annotations in Java?
- `@Override`
- `@Deprecated`
- `@SuppressWarnings`

## 75. What is the `enum` type in Java?
An `enum` is a special data type that defines a collection of constants.

## 76. What is a marker interface?
A marker interface is an interface without any methods or fields, used to indicate special behavior (e.g., `Serializable`).

## 77. What is dependency injection?
Dependency injection is a design pattern where an object's dependencies are injected by an external entity (e.g., frameworks like Spring).

## 78. What is a `lambda` expression in Java?
A lambda expression provides a way to write anonymous methods, enabling functional programming in Java.

## 79. What is the `Optional` class?
`Optional` is a container object used to avoid null values and handle optional data safely.

## 80. What is the difference between `flatMap()` and `map()` in Java Streams?
- **map():** Applies a function to each element and returns a stream of transformed values.
- **flatMap():** Flattens nested structures, returning a single-level stream.

## 81. What are Java Streams?
Streams represent a sequence of elements supporting sequential and parallel operations on data (introduced in Java 8).

## 82. What is the difference between `ParallelStream` and `Stream`?
- **Stream:** Sequential stream processing.
- **ParallelStream:** Divides data into multiple chunks and processes them in parallel.

## 83. What is method reference in Java?
Method reference is a shorthand syntax to refer to a method directly using `::` (e.g., `Class::methodName`).

## 84. What are functional interfaces?
A functional interface is an interface with exactly one abstract method (e.g., `Runnable`, `Callable`).

## 85. What is a default method in an interface?
A default method is a method defined in an interface with a default implementation, introduced in Java 8.

## 86. What is the purpose of `Predicate` in Java?
`Predicate` is a functional interface that represents a condition or filter, typically used in lambda expressions.

## 87. What is the `Supplier` functional interface?
`Supplier` is a functional interface that takes no arguments and provides a result.

## 88. What is the `Consumer` functional interface?
`Consumer` represents an operation that takes a single argument and returns no result.

## 89. What is the `Function` functional interface?
`Function` takes one argument and returns a result, used in mapping operations.

## 90. What is a stream pipeline?
A stream pipeline is a sequence of stream operations (intermediate and terminal operations) that process data.

## 91. What are intermediate and terminal operations in streams?
- **Intermediate operations:** Transform a stream (e.g., `filter()`, `map()`).
- **Terminal operations:** Produce a result or side-effect (e.g., `forEach()`, `collect()`).

## 92. What is the `Collectors` class?
`Collectors` is a utility class that provides implementations for various reduction operations like `toList()`, `joining()`, etc.

## 93. What is the `Optional` class used for?
`Optional` is used to handle nullable objects gracefully, avoiding `NullPointerExceptions`.

## 94. What is method overriding with covariant return types?
In method overriding, the return type can be a subclass of the original return type.

## 95. What is the purpose of `synchronized` blocks?
A `synchronized` block ensures that only one thread can execute a block of code at a time.

## 96. What is the difference between `notify()` and `notifyAll()`?
- **notify():** Wakes up one thread waiting on an object's monitor.
- **notifyAll():** Wakes up all threads waiting on an object's monitor.

## 97. What is `ExecutorService` in Java?
`ExecutorService` is an interface that provides a way to manage and control thread execution, offering higher-level thread management.

## 98. What is the difference between `submit()` and `execute()` in `ExecutorService`?
- **submit():** Submits a task for execution and returns a `Future` object.
- **execute():** Executes a task without returning any result.

## 99. What is `Future` in Java?
`Future` represents the result of an asynchronous computation and provides methods to check the completion or cancel the execution of the task.

## 100. What is `Callable` in Java?
`Callable` is similar to `Runnable`, but it returns a result and can throw an exception.

