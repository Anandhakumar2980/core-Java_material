# Java 8 Features

# Java 8 - Streams API
## Introduction 
## Types
1. intermediate operations
2. terminal operations

## Intermediate Operations
### filter:

It takes a predicate (a boolean-valued function) and returns a stream that includes only the elements satisfying the predicate.

'
List<Employee> employees = Stream.of(empIds)
      .map(employeeRepository::findById)
      .filter(e -> e != null)
      .filter(e -> e.getSalary() > 200000)
      .collect(Collectors.toList();
  '


map: It takes a function and transforms each element of the stream into another element according to the provided function.

flatMap: It is similar to map, but it flattens the resulting stream of each element into a single stream. It is useful when you have nested collections or when you want to remove empty/null values.

distinct: It returns a stream with unique elements by eliminating duplicates based on the equals method.

sorted: It sorts the elements of the stream based on their natural order or a specified comparator.

limit: It returns a stream that is truncated to a specified maximum size.

skip: It returns a stream that skips a specified number of elements from the beginning.

peek: It allows you to perform a non-destructive action on each element of the stream without modifying the stream itself. It can be useful for debugging or logging purposes.

unordered: It returns an unordered stream, which means the elements can be processed in an arbitrary order. This operation can improve performance in some cases.

skip: It returns a stream that skips a specified number of elements from the beginning. It discards the initial elements and returns a new stream with the remaining elements.

takeWhile: It returns a stream that consists of the longest prefix of elements that satisfy a given predicate. It stops processing elements as soon as the predicate evaluates to false.

dropWhile: It returns a stream that discards the longest prefix of elements that satisfy a given predicate. It skips elements until the predicate evaluates to false and returns the remaining elements.

parallel: It returns a parallel stream, which can leverage multiple threads for concurrent processing. It can potentially improve performance on large data sets.


# Core Java Topics 

Variables and data types<br>
Operators and expressions<br>
Control flow statements (if-else, loops, switch)<br>
Arrays and collections<br>
Methods and parameters<br>
Object-oriented programming (classes, objects, inheritance, polymorphism)<br>
Exception handling<br>
File I/O operations<br>
Input/output streams<br>
Generics<br>
Java libraries (java.util, java.lang, java.io, etc.)<br>
Multi-threading and synchronization<br>
Networking (sockets, client-server communication)<br>
Reflection and annotations<br>
Java Database Connectivity (JDBC)<br>
JavaFX (GUI programming)<br>
Lambda expressions and functional programming<br>
Java Serialization<br>
Java Memory Management (garbage collection)<br>
Java Virtual Machine (JVM) and bytecode<br>
Enumerations (enums)<br>
String manipulation and regular expressions<br>
Inner classes and nested classes<br>
Java Annotations<br>
Java Collections Framework (List, Set, Map, etc.)<br>
Iterator and Iterable interfaces<br>
Java Streams API<br>
Functional interfaces<br>
Method references<br>
Default and static methods in interfaces<br>
Type inference (var keyword)<br>
Date and time API (java.time package)<br>
Java Concurrency API (Locks, Executors, CompletableFuture)<br>
I/O with NIO (Non-blocking I/O)<br>
Java Applets<br>
Internationalization and localization (i18n and l10n)<br>
XML processing (DOM, SAX, JAXB)<br>
JSON processing (Jackson, Gson)<br>
Unit testing with JUnit<br>
Debugging and troubleshooting in Java<br>
