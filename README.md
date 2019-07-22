# Essential Java Question
Some Important Java, JVM and OS based Interview Question. 
<br> 
## Java foundation<br> 
#### 1.0 What are the basic data types in JAVA and how many bytes each is occupied.
#### 1.1 Can a String class be inherited, and why.
#### 1.2 The difference between String, Stringbuffer, and StringBuilder.
#### 1.3 What is the difference between ArrayList and LinkedList.
#### 1.4 talk about the instantiation order of classes, such as parent class static data, constructors, fields, subclass static data, constructors, fields, when new, their order of execution.
#### 1.5 What Maps have been used, what is the difference, HashMap is thread-safe, and what is the Map used, what are their internal principles, such as storage, hashcode, capacity expansion, default capacity, etc.
#### 1.6 Why does JAVA8's ConcurrentHashMap give up segmentation locks, what's the problem, if you come to design, how do you design.
#### 1.7 Is there a sequence of Map implementation classes, and if so, how are they guaranteed to be ordered?
#### 1.8 Differences between abstract classes and interfaces, can classes inherit multiple classes, can interfaces inherit multiple interfaces, and can classes implement multiple interfaces?
#### 1.9 What is the difference between inheritance and aggregation?
#### 2.0 What are the IO models? Let's talk about the nio you understand. The difference between him and bio, aio is 啥, talk about the reactor model.
#### 2.1 The principle of reflection, what are the three ways in which reflection creates an instance of a class.
#### 2.2 In reflection, Class.forName differs from ClassLoader.
#### 2.3 Describe several implementations of dynamic proxies, and say the corresponding advantages and disadvantages.
#### 2.4 The difference between dynamic proxy and cglib implementation.
#### 2.5 Why CGlib can implement proxy for interfaces.
#### 2.6 Final use.
#### 2.7 Write three singleton mode implementations.
#### 2.8 How do I automate all the hashcode and equals implementations for subclasses in the parent class? What are the advantages and disadvantages of doing this.
#### 2.9 Please combine the OO design concept to talk about the role of access modifiers public, private, protected, default in application design.
#### 3.0 Difference between deep copy and shallow copy.
#### 3.1 Array and linked list data structure description, their respective time complexity.
#### 3.2 The difference between error and exception, CheckedException, RuntimeException.
#### 3.3 Please list 5 runtime exceptions.
#### 3.4 In your own code, if you create a java.lang.String class, can this class be loaded by the class loader? why.
#### 3.5 Say your understanding of the hashCode and equals methods in the java.lang.Object object. In what scenario, you need to re-implement these two methods.
#### 3.6 In jdk1.5, generics were introduced, and the existence of generics was used to solve problems.
#### 3.7 What is the use of such a.hashcode(), and what does it have to do with a.equals(b).
#### 3.8 Is it possible that two unequal objects have the same hashcode.
#### 3.9 How does the internal work of HashSet in Java work?
#### 4.0 What is serialization, how to serialize, why serialization, deserialization will encounter problems, how to solve.
#### 4.1 New features of java8.
## JVM
#### 4.2 Under what circumstances a stack memory overflow will occur.
#### 4.3 JVM memory structure, Eden and Survivor ratio.
#### 4.4 Why should JVM memory be divided into new generation, old age, and durable generation. Why are the Eden and Survivor divided into the new generation?
#### 4.5 What is the complete GC process in the JVM, how the object is promoted to the old age, and talk about the main JVM parameters you know.
#### 4.6 You know which kinds of garbage collectors have their own advantages and disadvantages, focusing on cms and G1, including principles, processes, advantages and disadvantages.
#### 4.7 Implementation principle of the garbage collection algorithm.
#### 4.8 How do you troubleshoot when there is a memory leak?
#### 4.9 Learn about the JVM memory model, such as reordering, memory barrier, happen-before, main memory, working memory, etc.
#### 5.0 Simply talk about the class loader you know, you can break the parental appointment, how to break.
#### 5.1 talk about the reflection mechanism of JAVA.
#### 5.2 What are the JVM parameters for your online application?
#### 5.3 Difference between g1 and cms, throughput priority and response priority garbage collector selection.
#### 5.4 How to play the thread stack information.
## Operating System
#### 5.5 Which kernel parameters have you paid attention to under Linux system, let me know what you know.
#### 5.6 There are several IO models under Linux, what are their respective meanings.
#### 5.7 What is the difference between epoll and poll.
#### 5.8 Use the one-line command to view the last five lines of the file.
#### 5.9 Output a running java process with one line of commands.
#### 6.0 Introduce the thread switching process in the operating system you understand.
#### 6.1 Differences between processes and threads.
#### 6.2 What happens after the top command? What does it do?
#### 6.3 Online CPU is exploding. How do you find the problem?
