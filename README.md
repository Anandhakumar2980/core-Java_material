# CORE JAVA TOPICS

## Access and Non-access Modifiers in Java
![image](https://github.com/Anandhakumar2980/core-Java_material/assets/126327213/34c12442-8970-4c03-b42f-aa6dea938f9b)
![image](https://github.com/Anandhakumar2980/core-Java_material/assets/126327213/51d66b10-e621-4979-9890-1604e335f4d3)
### Access Modifiers 
- Access modifiers is used to __control the visibility or accessibility__ of classes, methods, and variables.
- There are four types of access modifiers in Java <br>
     1. __public:__ The public access modifier allows classes, methods, and variables to be accessed from anywhere in the program, within the same package or from any other package.

     2. __private:__ The private access modifier is accessible only within the class.

``` class A{  
private int data=40;  
private void msg(){System.out.println("Hello java");}  
}  
  
public class Simple{  
 public static void main(String args[]){  
   A obj=new A();  
   System.out.println(obj.data);//Compile Time Error  
   obj.msg();//Compile Time Error  
   }  
}  ```
     4. __protected:__ The protected access modifier allows access to the class, method, or variable within the same package and by subclasses (even if they are in different packages).

     5. __default (no modifier):__ If no access modifier is specified, it is considered to have default access. It allows access to the class, method, or variable within the same package but not from outside the package.
### Non - Access Modifiers 

# Java 8 Features

# Java 8 - Streams API

## Introduction 

## Types Based on Operations

### Intermediate Operations in Stream API 

filter (Java 8, Stream<T>)<br>
map (Java 8, Stream<R>)<br>
flatMap (Java 8, Stream<R>)<br>
distinct (Java 8, Stream<T>)<br>
sorted (Java 8, Stream<T>)<br>
peek (Java 8, Stream<T>)<br>
limit (Java 8, Stream<T>)<br>
skip (Java 8, Stream<T>)<br>
takeWhile (Java 9, Stream<T>)<br>
dropWhile (Java 9, Stream<T>)<br>
unordered (Java 9, Stream<T>)<br>
parallel (Java 9, Stream<T>)<br>
concat (Java 9, Stream<T>)<br>
iterate (Java 9, Stream<T>)<br>
ofNullable (Java 9, Stream<T>)<br>
flatMapToDouble (Java 9, DoubleStream)<br>
flatMapToInt (Java 9, IntStream)<br>
flatMapToLong (Java 9, LongStream)<br>
toArray (Java 9, Object[])<br>
filterNot (Java 9, Stream<T>)<br>
flatMapOptional (Java 9, Stream<R>)<br>
flatMapStream (Java 9, Stream<R>)<br>
mapMulti (Java 9, Stream<R>)<br>
flatMapCompletable (Java 9, CompletableFuture<Void>)<br>
flatMapMerged (Java 9, Stream<R>)<br>
mapToObj (Java 9, Stream<R>)<br>
mapToInt (Java 9, IntStream)<br>
mapToLong (Java 9, LongStream)<br>
mapToDouble (Java 9, DoubleStream)<br>
flatMapToObj (Java 9, Stream<R>)<br>
flatMapToInt (Java 9, IntStream)<br>
flatMapToLong (Java 9, LongStream)<br>
flatMapToDouble (Java 9, DoubleStream)<br>
mapToObj (Java 10, Stream<R>)<br>
mapToInt (Java 10, IntStream)<br>
mapToLong (Java 10, LongStream)<br>
mapToDouble (Java 10, DoubleStream)<br>
dropWhile (Java 11, Stream<T>)<br>
takeWhile (Java 11, Stream<T>)<br>
not (Java 11, Stream<T>)<br>
flatMap (Java 11, Stream<R>)<br>
map (Java 11, Stream<R>)<br>
filter (Java 11, Stream<T>)<br>
mapMulti (Java 16, Stream<R>)<br>
flatMapMulti (Java 16, Stream<R>)<br>
unordered (Java 16, Stream<T>)<br>
scan (Java 17, Stream<T>)<br>
reduce (Java 17, Optional<T>)<br>
      
### Terminal operations

forEach (Java 8, void)<br>
forEachOrdered (Java 8, void)<br>
toArray (Java 8, Object[])<br>
reduce (Java 8, Optional<T>)<br>
collect (Java 8, R)<br>
min (Java 8, Optional<T>)<br>
max (Java 8, Optional<T>)<br>
count (Java 8, long)<br>
anyMatch (Java 8, boolean)<br>
allMatch (Java 8, boolean)<br>
noneMatch (Java 8, boolean)<br>
findFirst (Java 8, Optional<T>)<br>
findAny (Java 8, Optional<T>)<br>
iterator (Java 9, Iterator<T>)<br>
spliterator (Java 9, Spliterator<T>)<br>
toList (Java 9, List<T>)<br>
toSet (Java 9, Set<T>)<br>
toMap (Java 9, Map<K, V>)<br>
toUnmodifiableList (Java 10, List<T>)<br>
toUnmodifiableSet (Java 10, Set<T>)<br>
toUnmodifiableMap (Java 10, Map<K, V>)<br>
forEachOrElse (Java 12, void)<br>
collectAndThen (Java 12, R)<br>
minBy (Java 12, Optional<T>)<br>
maxBy (Java 12, Optional<T>)<br>
joining (Java 8, String)<br>
summingInt (Java 8, int)<br>
summingLong (Java 8, long)<br>
summingDouble (Java 8, double)<br>
averagingInt (Java 8, double)<br>
averagingLong (Java 8, double)<br>
averagingDouble (Java 8, double)<br>
reducing (Java 8, Optional<T>)<br>
collectingAndThen (Java 8, R)<br>
groupingBy (Java 8, Map<K, List<T>>)<br>
partitioningBy (Java 8, Map<Boolean, List<T>>)<br>
teeing (Java 12, R)<br>
mapping (Java 9, Stream<R>)<br>
flatMap (Java 9, Stream<R>)<br>
forEach (Java 9, void)<br>
forEachOrdered (Java 9, void)<br>
toArray (Java 9, Object[])<br>
reduce (Java 9, Optional<T>)<br>
collect (Java 9, R)<br>
min (Java 9, Optional<T>)<br>
max (Java 9, Optional<T>)<br>
count (Java 9, long)<br>
anyMatch (Java 9, boolean)<br>
allMatch (Java 9, boolean)<br>
noneMatch (Java 9, boolean)<br>
findFirst (Java 9, Optional<T>)<br>
findAny (Java 9, Optional<T>)<br>
toList (Java 16, List<T>)<br>
toSet (Java 16, Set<T>)<br>
toMap (Java 16, Map<K, V>)<br>
toUnmodifiableList (Java 16, List<T>)<br>
toUnmodifiableSet (Java 16, Set<T>)<br>
toUnmodifiableMap (Java 16, Map<K, V>)<br>
forEachOrElse (Java 17, void)<br>
collectAndThen (Java 17, R)<br>
minBy (Java 17, Optional<T>)<br>
maxBy (Java 17, Optional<T>)<br>
joining (Java 17, String)<br>
summingInt (Java 17, int)<br>
summingLong (Java 17, long)<br>
summingDouble (Java 17, double)<br>
averagingInt (Java 17, double)<br>
averagingLong (Java 17, double)<br>
averagingDouble (Java 17, double)<br>
reducing (Java 17, Optional<T>)<br>
collectingAndThen (Java 17, R)<br>
groupingBy (Java 17, Map<K, List<T>>)<br>
partitioningBy (Java 17, Map<Boolean, List<T>>)<br>
teeing (Java 17, R)<br>
mapping (Java 9, Stream<R>)<br>
flatMap (Java 9, Stream<R>)<br>
forEach (Java 9, void)<br>
forEachOrdered (Java 9, void)<br>
toArray (Java 9, Object[])<br>
reduce (Java 9, Optional<T>)<br>
collect (Java 9, R)<br>
min (Java 9, Optional<T>)<br>
max (Java 9, Optional<T>)<br>
count (Java 9, long)<br>
anyMatch (Java 9, boolean)<br>
allMatch (Java 9, boolean)<br>
noneMatch (Java 9, boolean)<br>
findFirst (Java 9, Optional<T>)<br>
findAny (Java 9, Optional<T>)<br>
toList (Java 16, List<T>)<br>
toSet (Java 16, Set<T>)<br>
toMap (Java 16, Map<K, V>)<br>
toUnmodifiableList (Java 16, List<T>)<br>
toUnmodifiableSet (Java 16, Set<T>)<br>
toUnmodifiableMap (Java 16, Map<K, V>)<br>
forEachOrElse (Java 17, void)<br>
collectAndThen (Java 17, R)<br>
minBy (Java 17, Optional<T>)<br>
maxBy (Java 17, Optional<T>)<br>
joining (Java 17, String)<br>
summingInt (Java 17, int)<br>
summingLong (Java 17, long)<br>
summingDouble (Java 17, double)<br>
averagingInt (Java 17, double)<br>
averagingLong (Java 17, double)<br>
averagingDouble (Java 17, double)<br>
reducing (Java 17, Optional<T>)<br>
collectingAndThen (Java 17, R)<br>
groupingBy (Java 17, Map<K, List<T>>)<br>
partitioningBy (Java 17, Map<Boolean, List<T>>)<br>
teeing (Java 17, R)<br>
scan (Java 23, Stream<T>)<br>
      
# Stream Operations with Example
      
```
List<Employee> employees = Stream.of(empIds)
      .map(employeeRepository::findById)
      .filter(e -> e != null)
      .filter(e -> e.getSalary() > 200000)
      .collect(Collectors.toList();
```
