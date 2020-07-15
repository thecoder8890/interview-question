Java Question
=================================

volatile and atomic variables
https://stackoverflow.com/questions/9749746/what-is-the-difference-between-atomic-volatile-synchronized

visibility and volatile
https://www.baeldung.com/java-volatile


Does volatile make non-atomic operation to atomic?
https://javarevisited.blogspot.com/2020/04/difference-between-atomic-volatile-and-synchronized-in-java-multi-threading.html

Is reading a long/double variable is atomic

https://stackoverflow.com/questions/517532/writing-long-and-double-is-not-atomic-in-java


Does long/double volatile variable is atomic
https://www.google.com/search?client=ubuntu&channel=fs&q=Does+long%2Fdouble+volatile+variable+is+atomic&ie=utf-8&oe=utf-8

Can a volatile variable be marked as final?
https://dzone.com/articles/longdouble-are-not-atomic-in-java

difference between locking and volatile variables.


How compiler and runtime treats a volatile variable 
what are atomic variables and how they work.
difference between volatile and atomic     
Synchronization
How synchronized keyword works
Synchronization, static, non static scenarios 
Can two threads call two different static synchronized methods of the same class?
Can two threads call a static synchronized and non static synchronized methods on the same instance?
How to make a class thread safe i.e immutable
what is happen-before relationship
Can a thread hold multiple locks at the same time
alternative to synchronization
Thread join, wait, notify and notify All, thread local
Implement a consumer and producer design pattern using wait and notify
can we call wait(), notify() and notifyAll() methods without holding a lock on the instance
How to create thread local variables in java
Does wait() releases lock
What happens if notify() is called and no thread is in waiting state?
What happens if notify() is called and more than one thread is in waiting state, which thread will get notified?
Why we will wake up all of the threads if only one is going to execute.
how to create a thread local variables and when you will use a thread local variable
what are daemon threads and how we can create a daemon thread.
What is a reentrant lock
Executors 
what is the difference between core pool size and max pool size
what happens if blocking queue associated with thread pool becomes full or what are saturation policies?
what will happen to the waiting tasks if shutdown method is called on thread pool
what is keep alive time in thread pool.
how to handle abnormal thread termination in thread pool.
can we configure thread pool to create daemon threads.
different implementation available for ExecutorService in java.
Fork join pool and work stealing queues
Collections
how hashmap works internally
what is hashmap load factor and why it is used in hashamp
what is hash collision and how hashmap resolves it
worst time complexity to insert an element into hashamp (ask about rehashing into this)
What is the difference between fail-fast and fail-safe? Arraylist Iterator`is fail-fast or fail-safe
We want to pass a Collection as argument to a function, how can we make sure the function will not be able to modify it?
is below code is valid in java, where number is the base class of Integer
          List<Number> numbers = new ArrayList<Integer>();
what is WeakHashMap and how it works internally.
Concurrent hashamp and how it works internally,
How to make an arraylist threadsafe
General questions :
a class has two overloaded method ,
A class has two overloaded methods
       display(String string){}
       display(Integer integer){}
Now calling display(null) will call which method and why?
 Parent class has a method defined below
                    public display(String string){}
 A child class override the method and declare the contract like below
                     protected display(String string){}
 will this code compile?
 class Parent{
       public static display(){}
        }
 class child {
          public static display(){}
         }
 Parent parent = new child();
 parent.display();
 which class display method will get called

-

1. hashmap and internal working -
2. hashmap various scenarios -
3. proxy , factory pattern -
4. singleton design pattern and various scenarios -
5. immutable classes - 
6. volatile and synchronized and static  - 
7. print sum of all elements of array using multi threading(Executor service implementation) - low could not tell the correct implementation
8. find last 4th element from linked list - 
9. hash code with math.random  
10. project wise architecture questions - 
11. deep and shallow copy -
12. transient working and usage - 
13. sample java code  - 
14. concurrent hashmap vs hash table - 
15. immutable vs final
16. Volatile detail working
17. Garbage collector working and memory model
18.count Total substring whose 1st and last character is same
19.Basic normalization scenerio for many to many mapping
20.Basic spring concept

-

1) difference between Inheritance and Composition in Java and OOP.
2) Why wait and notify is declared in Object class instead of Thread ?
3) Why Java doesn't support multiple inheritance, Default Methods in Java 8 has introduced Multiple Inheritance
4) What is the difference between creating String as new() and literal?
5) what happens if we update the key object that is in a hashmap?
6) Can we make array volatile in Java?
7) Can volatile make a non-atomic operation to atomic?
8) how to make a class immutable, further questions related to breaking it through reflection, cloning, serialization.
9) countdownlatch vs cyclic barrier

-

1) difference between Inheritance and Composition in Java and OOP.
2) Why wait and notify is declared in Object class instead of Thread ?
3) Why Java doesn't support multiple inheritance, Default Methods in Java 8 has introduced Multiple Inheritance
4) What is the difference between creating String as new() and literal?
5) what happens if we update the key object that is in a hashmap?
6) Can we make array volatile in Java?
7) Can volatile make a non-atomic operation to atomic?
8) how to make a class immutable, further questions related to breaking it through reflection, cloning, serialization.
9) countdownlatch vs cyclic barrier

-

1. Immutable class
4. Custom employee class as key in hashmap without equals and hashcode method
5. Only empId in class. Create one object e1 with some empId and put it in the map. Change the empId and now do a get on e1. Will I be getting any value?
6. Create two emp objects with same empId. Put e1 with value true and e2 with value false. What will we get when we will do get on e1?
7. Given a set of random tickets with only source and destination, print the itenary.
8. How re-hashing takes place in hashmap and concurrent hashmap. What is the time complexity of both?
9. Iterate over hashmap entry and print key and value pair code
10. Why we use serialVersionId ?
11. Difference between volatile and atomic Integer. How does they help with concurrency ?
12. Design a ratelimitor service.
13. Internal working of lambda
14. Questions around transaction management
15. How does GC work ?
16. Difference between execution and completion service.
17. How Arraylist get method works ?
18. Synchronization and static methods ?
19. How does Collections.synchronizedList() works? How can you write your own API?
20. Design a distributed cache.
21. Design a custom threadpool with pause and play option.

-

1. Code snippet where equals always returns true and hashcode always returns 1, behavior of map.
2. Behavior of calling static sync and sync in parallel
3. custom immutable class
4. ForkJoinpool
5. CompletionService
6. lambda internal implemention
7. runnable vs callable
8. countdownlatch vs cyclic barrier


Problem Solving
=================

Delete a node from a singly linked list, given only access to that node.
given two singly linked list, check if two linked list intersect , return the intersection node is exists, otherwise return null.
implement a min function in stack to return minimum element in the stack. Try to implement in O(1) time complexity
implement a queue using one stack
given a binary tree, create linked lists of nodes at each level, for each level there will be one linked list
Given java classpath of many projects and these projects depends on one another, find the build order of the these projects
given a weighted binary tree, find  pairs of nodes whose sum is equal to a given number
 given a very big array, find k mas elements where k is very small as compared to no of elements into the array
Imagine we have 30GB file with one string per line, how you will sort the file.
find out K-th largest sum of contiguous subarray within the array of numbers
find out k smallest elements in the same order from an array without using extra space

-

1) How do you check if two given String are anagrams
2) Java program to find all permutations of a given String using recursion
3) Finds first non repeated character in a String (in just one pass).
4) Add all even numbers, odd numbers in different threads
5) create a custom  comparator based on the initial alphabet of strings provided in a list
6) write LRU cache in Java using Generics
7) check a character count in a string without any loop

-

1. Arrange a number ito find minimum possible no in o new.
2. find if you can arrange a string to make palindrome.
3. Find immediate next biggest no.

-

1. Find pair of elements with a given sum in an array
2. Find pair of elements with a given sum in tree
3. Find the size of the loop in a LinkedList
4. Find nth element from last in a LinkedList
5. Print even and odd number using 2 threads
