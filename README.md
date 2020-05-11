# Java Boot Camp

Boot Camp for developers interested to learn Java.

## Plan

### [Primer](01%20-%20Primer.md)

1. [Java](01%20-%20Primer.md#java)
    1. [What is Java?](01%20-%20Primer.md#what-is-java)
    1. [How do we develop Java Applications?](01%20-%20Primer.md#how-do-we-develop-java-applications)
1. [Java Language Specification](01%20-%20Primer.md#java-language-specification)
1. [Setup Environment (SDKMAN)](01%20-%20Primer.md#setup-environment-sdkman)
1. [Gradle and Maven](01%20-%20Primer.md#gradle-and-maven)
    1. [Advantages of Gradle over Maven](01%20-%20Primer.md#advantages-of-gradle-over-maven)
    1. [Install Gradle](01%20-%20Primer.md#install-gradle)
1. [IDE (IntelliJ IDEA and VS Code)](01%20-%20Primer.md#ide-intellij-idea-and-vs-code)
1. [Create a project using Gradle](01%20-%20Primer.md#create-a-project-using-gradle)
    1. [Create Project](01%20-%20Primer.md#create-project)
    1. [Explore Project](01%20-%20Primer.md#explore-project)
1. [Hello World Application (from source to executable application)](01%20-%20Primer.md#hello-world-application-from-source-to-executable-application)
    1. [Gradle Task Dependency Tree](01%20-%20Primer.md#gradle-task-dependency-tree)
    1. [Project Dependencies](01%20-%20Primer.md#project-dependencies)
    1. [Package Project](01%20-%20Primer.md#package-project)
    1. [Make use of third-party libraries](01%20-%20Primer.md#make-use-of-third-party-libraries)
        1. [The Classpath](01%20-%20Primer.md#the-classpath)
    1. [Make a fat JAR](01%20-%20Primer.md#make-a-fat-jar)
1. [Docker](01%20-%20Primer.md#docker)
    1. [What is Docker?](01%20-%20Primer.md#what-is-docker)
    1. [How does this work?](01%20-%20Primer.md#how-does-this-work)
    1. [More than just Containers](01%20-%20Primer.md#more-than-just-containers)
    1. [Setup Docker](01%20-%20Primer.md#setup-docker)
    1. [Working with Docker](01%20-%20Primer.md#working-with-docker)
    1. [Dockerize the Application](01%20-%20Primer.md#dockerize-the-application)
    1. [Multi-Stage Docker Build](01%20-%20Primer.md#multi-stage-docker-build)
1. [Managing Docker Containers](01%20-%20Primer.md#managing-docker-containers)

### [Data Types](02%20-%20Data%20Types.md)

1. [JShell](02%20-%20Data%20Types.md#jshell)
1. [Numbers and Strings (Variables and Scope)](02%20-%20Data%20Types.md#numbers-and-strings-variables-and-scope)
    1. [Puzzle (Time for a change)](02%20-%20Data%20Types.md#puzzle-time-for-a-change)
    1. [Puzzle (Long Division)](02%20-%20Data%20Types.md#puzzle-long-division)
    1. [Puzzle (It's Elementary)](02%20-%20Data%20Types.md#puzzle-its-elementary)
    1. [Puzzle (The Joy of Hex)](02%20-%20Data%20Types.md#puzzle-the-joy-of-hex)
    1. [Puzzle (Hello Whirled)](02%20-%20Data%20Types.md#puzzle-hello-whirled)
    1. [Puzzle (Line Printer)](02%20-%20Data%20Types.md#puzzle-line-printer)
    1. [Puzzle (huh?)](02%20-%20Data%20Types.md#puzzle-huh)
    1. [Puzzle (String Cheese)](02%20-%20Data%20Types.md#puzzle-string-cheese)
    1. [Puzzle (Classy Fire)](02%20-%20Data%20Types.md#puzzle-classy-fire)
    1. [Puzzle (What's my class?)](02%20-%20Data%20Types.md#puzzle-whats-my-class)
    1. [Puzzle (What's my class, Take 2)](02%20-%20Data%20Types.md#puzzle-whats-my-class-take-2)
    1. [Mutable Strings](02%20-%20Data%20Types.md#mutable-strings)
        1. [Puzzle (No Pain, No Gain)](02%20-%20Data%20Types.md#puzzle-no-pain-no-gain)
    1. [Multiline Strings](02%20-%20Data%20Types.md#multiline-strings)
    1. [Primitive Types](02%20-%20Data%20Types.md#primitive-types)
    1. [Signed and Unsigned Integrals](02%20-%20Data%20Types.md#signed-and-unsigned-integrals)
    1. [Reference Types (the rest)](02%20-%20Data%20Types.md#reference-types-the-rest)
    1. [Variables and their Values](02%20-%20Data%20Types.md#variables-and-their-values)
1. [Stack and Heap](02%20-%20Data%20Types.md#stack-and-heap)
    1. [OS Process Memory](02%20-%20Data%20Types.md#os-process-memory)
    1. [What goes in the Java Stack?](02%20-%20Data%20Types.md#what-goes-in-the-java-stack)
    1. [What goes in the Java Heap?](02%20-%20Data%20Types.md#what-goes-in-the-java-heap)
    1. [Variables without a value](02%20-%20Data%20Types.md#variables-without-a-value)
    1. [Can we have a reference variable without the equivalent object in the Java heap (null)?](02%20-%20Data%20Types.md#can-we-have-a-reference-variable-without-the-equivalent-object-in-the-java-heap-null)
        1. [What happens if we try to call a method on a null object?](02%20-%20Data%20Types.md#what-happens-if-we-try-to-call-a-method-on-a-null-object)
        1. [What is NullPointerException?](02%20-%20Data%20Types.md#what-is-nullpointerexception)
    1. [The new operator and the Java Heap](02%20-%20Data%20Types.md#the-new-operator-and-the-java-heap)
    1. [Garbage Collection](02%20-%20Data%20Types.md#garbage-collection)
    1. [String or new String?](02%20-%20Data%20Types.md#string-or-new-string)
    1. [What happens to a variable when it goes out of scope?](02%20-%20Data%20Types.md#what-happens-to-a-variable-when-it-goes-out-of-scope)
1. [Operators](02%20-%20Data%20Types.md#operators)
    1. [Puzzle (Tweedledum)](02%20-%20Data%20Types.md#puzzle-tweedledum)
    1. [Puzzle (Tweedledee)](02%20-%20Data%20Types.md#puzzle-tweedledee)
    1. [Puzzle (The Last Laugh)](02%20-%20Data%20Types.md#puzzle-the-last-laugh)
    1. [Puzzle (Oddity)](02%20-%20Data%20Types.md#puzzle-oddity)
    1. [Puzzle (Swap Meat)](02%20-%20Data%20Types.md#puzzle-swap-meat)
    1. [Puzzle (Escape Rout)](02%20-%20Data%20Types.md#puzzle-escape-rout)
    1. [Puzzle (A Big Delight in Every Byte)](02%20-%20Data%20Types.md#puzzle-a-big-delight-in-every-byte)
    1. [Puzzle (Inclement Increment)](02%20-%20Data%20Types.md#puzzle-inclement-increment)
1. [Mutable and Immutable](02%20-%20Data%20Types.md#mutable-and-immutable)
    1. [The final keyword](02%20-%20Data%20Types.md#the-final-keyword)
1. [Casting](02%20-%20Data%20Types.md#casting)
    1. [Puzzle (Multicast)](02%20-%20Data%20Types.md#puzzle-multicast)
1. [Autoboxing](02%20-%20Data%20Types.md#autoboxing)
    1. [Autoboxing is an easy target for NullPointerException](02%20-%20Data%20Types.md#autoboxing-is-an-easy-target-for-nullpointerexception)
1. [Enumerations](02%20-%20Data%20Types.md#enumerations)
    1. [Enums in Java can have methods](02%20-%20Data%20Types.md#enums-in-java-can-have-methods)
    1. [Enum's Ordinal](02%20-%20Data%20Types.md#enums-ordinal)
    1. [Enums in Java can have state](02%20-%20Data%20Types.md#enums-in-java-can-have-state)
    1. [Enums can extend functionality](02%20-%20Data%20Types.md#enums-can-extend-functionality)
1. [Imports, Static Imports and Packages](02%20-%20Data%20Types.md#imports-static-imports-and-packages)
    1. [Imports](02%20-%20Data%20Types.md#imports)
    1. [Static Imports](02%20-%20Data%20Types.md#static-imports)
    1. [Packages](02%20-%20Data%20Types.md#packages)
1. [Date Time API](02%20-%20Data%20Types.md#date-time-api)
1. [Internationalization](02%20-%20Data%20Types.md#internationalization)

### [Collections](03%20-%20Collections.md)

1. [Arrays](03%20-%20Collections.md#arrays)
    1. [Create Arrays](03%20-%20Collections.md#create-arrays)
        1. [Puzzle (ABC)](03%20-%20Collections.md#puzzle-abc)
    1. [Working with Arrays](03%20-%20Collections.md#working-with-arrays)
    1. [Read past the array's length](03%20-%20Collections.md#read-past-the-arrays-length)
    1. [Multidimensional Arrays](03%20-%20Collections.md#multidimensional-arrays)
        1. [Two dimensional array](03%20-%20Collections.md#two-dimensional-array)
        1. [Irregular Arrays](03%20-%20Collections.md#irregular-arrays)
    1. [Arrays are always Mutable](03%20-%20Collections.md#arrays-are-always-mutable)
    1. [Defensive Copying](03%20-%20Collections.md#defensive-copying)
    1. [Arrays of Objects](03%20-%20Collections.md#arrays-of-objects)
    1. [Sorting and Searching](03%20-%20Collections.md#sorting-and-searching)
    1. [An Array of Characters Is Not a String](03%20-%20Collections.md#an-array-of-characters-is-not-a-string)
1. [Lists (Vector, ArrayList and LinkedList)](03%20-%20Collections.md#lists-vector-arraylist-and-linkedlist)
    1. [Create Lists](03%20-%20Collections.md#create-lists)
    1. [Types of Lists](03%20-%20Collections.md#types-of-lists)
        1. [Vector](03%20-%20Collections.md#vector)
        1. [ArrayList](03%20-%20Collections.md#arraylist)
        1. [LinkedList](03%20-%20Collections.md#linkedlist)
    1. [Double Brace Initialization](03%20-%20Collections.md#double-brace-initialization)
    1. [Mutable and Immutable Lists](03%20-%20Collections.md#mutable-and-immutable-lists)
1. [Set (HashSet, LinkedHashSet and TreeSet)](03%20-%20Collections.md#set-hashset-linkedhashset-and-treeset)
    1. [Create Sets](03%20-%20Collections.md#create-sets)
    1. [Types of Sets](03%20-%20Collections.md#types-of-sets)
        1. [HashSet](03%20-%20Collections.md#hashset)
        1. [LinkedHashSet](03%20-%20Collections.md#linkedhashset)
        1. [TreeSet](03%20-%20Collections.md#treeset)
    1. [Mutable and Immutable Sets](03%20-%20Collections.md#mutable-and-immutable-sets)
1. [Map (HashMap, LinkedHashMap and TreeMap)](03%20-%20Collections.md#map-hashmap-linkedhashmap-and-treemap)
1. [Queue and Stack](03%20-%20Collections.md#queue-and-stack)
1. [Java Collections Framework](03%20-%20Collections.md#java-collections-framework)
1. [Google Guava (Collections)](03%20-%20Collections.md#google-guava-collections)

### [Classes, Methods and Control Flow](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md)

1. [Classes and methods (static no OOP)](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#classes-and-methods-static-no-oop)
    1. [Is void a type?](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#is-void-a-type)
1. [Properties (static no OOP)](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#properties-static-no-oop)
1. [Access Control](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#access-control)
    1. [Classes Access Modifiers Table](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#classes-access-modifiers-table)
    1. [Class Members Access Modifiers Table](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#class-members-access-modifiers-table)
1. [Control Flow and Loops](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#control-flow-and-loops)
    1. [If (if/else) Control Flow Statement](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#if-ifelse-control-flow-statement)
        1. [If Example](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#if-example)
        1. [If/else Example](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#ifelse-example)
        1. [If/else-if/else Example](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#ifelse-ifelse-example)
        1. [Java Ternary Operator](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#java-ternary-operator)
    1. [Switch Control Flow Statement](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#switch-control-flow-statement)
        1. [Switch Example](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#switch-example)
        1. [Switch Fallthrough Example](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#switch-fallthrough-example)
        1. [Switch Default Example](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#switch-default-example)
        1. [Switch Expressions](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#switch-expressions)
    1. [For Loop](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#for-loop)
        1. [Puzzles (In the Loop)](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#puzzles-in-the-loop)
    1. [While Loop](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#while-loop)
        1. [Puzzle (Shifty i's)](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#puzzle-shifty-is)
        1. [Puzzles (Looper)](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#puzzles-looper)
        1. [Puzzle (Bride of Looper)](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#puzzle-bride-of-looper)
        1. [Puzzle (Son of Looper)](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#puzzle-son-of-looper)
        1. [Puzzle (Ghost of Looper)](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#puzzle-ghost-of-looper)
    1. [Do/While Loop](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#dowhile-loop)
    1. [Foreach Loop](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#foreach-loop)
    1. [Nested Loops](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#nested-loops)
    1. [Break, Continue, Labels and Return](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#break-continue-labels-and-return)
        1. [Break](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#break)
        1. [Label](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#label)
            1. [Puzzle (Dupe of URL)](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#puzzle-dupe-of-url)
        1. [Continue](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#continue)
        1. [Return](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#return)
    1. [Loop and Control Flow Examples](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#loop-and-control-flow-examples)
        1. [How many rolls it takes to roll a 6?](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#how-many-rolls-it-takes-to-roll-a-6)
        1. [A simple game with dice and random numbers](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#a-simple-game-with-dice-and-random-numbers)
1. [Exceptions](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#exceptions)
1. [Java Single File Execution](04%20-%20Classes%2C%20Methods%20and%20Control%20Flow.md#java-single-file-execution)

### [Testing](05%20-%20Testing.md)

1. [Testing with JUnit 5 (Hamcrest and AssertJ)](05%20-%20Testing.md#testing-with-junit-5-hamcrest-and-assertj)
    1. [Add JUnit 5](05%20-%20Testing.md#add-junit-5)
    1. [Parameterized Test](05%20-%20Testing.md#parameterized-test)
    1. [Custom Converters](05%20-%20Testing.md#custom-converters)
    1. [Tests Tagging](05%20-%20Testing.md#tests-tagging)
    1. [Nested Tests](05%20-%20Testing.md#nested-tests)
    1. [Hamcrest](05%20-%20Testing.md#hamcrest)
    1. [AssertJ](05%20-%20Testing.md#assertj)
    1. [JUnit 5, Hamcrest and AssertJ](05%20-%20Testing.md#junit-5-hamcrest-and-assertj)
    1. [Test Lifecycle](05%20-%20Testing.md#test-lifecycle)
1. [Mocking (Mockito and EasyMock)](05%20-%20Testing.md#mocking-mockito-and-easymock)
    1. [What is Mocking (Test Doubles) and Why do we need it?](05%20-%20Testing.md#what-is-mocking-test-doubles-and-why-do-we-need-it)
    1. [Test Doubles](05%20-%20Testing.md#test-doubles)
    1. [Mockito](05%20-%20Testing.md#mockito)
    1. [EasyMock](05%20-%20Testing.md#easymock)
    1. [Which Mocking Framework](05%20-%20Testing.md#which-mocking-framework)
1. [Mutation Testing (PIT)](05%20-%20Testing.md#mutation-testing-pit)
1. [Google Guava (Preconditions)](05%20-%20Testing.md#google-guava-preconditions)

### [Objects](06%20-%20Objects.md)

1. [Simple Objects](06%20-%20Objects.md#simple-objects)
    1. [Basic Object](06%20-%20Objects.md#basic-object)
    1. [Add State](06%20-%20Objects.md#add-state)
    1. [More State](06%20-%20Objects.md#more-state)
    1. [Multiple Instances](06%20-%20Objects.md#multiple-instances)
    1. [Mutable and Immutable](06%20-%20Objects.md#mutable-and-immutable)
1. [Inheritance](06%20-%20Objects.md#inheritance)
    1. [Light Box Example](06%20-%20Objects.md#light-box-example)
    1. [Heavy Box Example](06%20-%20Objects.md#heavy-box-example)
    1. [The `super` keyword](06%20-%20Objects.md#the-super-keyword)
    1. [The `final` keyword](06%20-%20Objects.md#the-final-keyword)
    1. [Private Constructor](06%20-%20Objects.md#private-constructor)
1. [Abstraction](06%20-%20Objects.md#abstraction)
    1. [When a class must be abstract?](06%20-%20Objects.md#when-a-class-must-be-abstract)
    1. [Final Classes](06%20-%20Objects.md#final-classes)
1. [The Object Class](06%20-%20Objects.md#the-object-class)
    1. [Puzzle (Animal Farm)](06%20-%20Objects.md#puzzle-animal-farm)
1. [Interfaces](06%20-%20Objects.md#interfaces)
1. [instanceof and cast operators](06%20-%20Objects.md#instanceof-and-cast-operators)
1. [Inheritance and Composition](06%20-%20Objects.md#inheritance-and-composition)
1. [Overloading and Overriding](06%20-%20Objects.md#overloading-and-overriding)
1. [Outer, Inner and Anonymous Classes](06%20-%20Objects.md#outer-inner-and-anonymous-classes)
1. [Annotations](06%20-%20Objects.md#annotations)
1. [Generics](06%20-%20Objects.md#generics)
1. [Miscellaneous](06%20-%20Objects.md#miscellaneous)

### [SOLID](07%20-%20SOLID.md)

1. [Single-responsibility Principle](07%20-%20SOLID.md#single-responsibility-principle)
1. [Open–closed principle](07%20-%20SOLID.md#open-closed-principle)
1. [Liskov substitution principle](07%20-%20SOLID.md#liskov-substitution-principle)
1. [Interface segregation principle](07%20-%20SOLID.md#interface-segregation-principle)
1. [Dependency inversion principle](07%20-%20SOLID.md#dependency-inversion-principle)

### [Lambda](08%20-%20Lambda.md)

1. [Lambda Expressions](08%20-%20Lambda.md#lambda-expressions)
1. [Multiple Parameters](08%20-%20Lambda.md#multiple-parameters)
1. [Dealing with Exceptions](08%20-%20Lambda.md#dealing-with-exceptions)
1. [Foreach Loops](08%20-%20Lambda.md#foreach-loops)
1. [Streams (Lambda)](08%20-%20Lambda.md#streams-lambda)
1. [Mapping and Filtering](08%20-%20Lambda.md#mapping-and-filtering)
1. [Collectors](08%20-%20Lambda.md#collectors)

### [IO & Streams](09%20-%20IO%20&%20Streams.md)

1. [Files](09%20-%20IO%20&%20Streams.md#files)
1. [Java Streams](09%20-%20IO%20&%20Streams.md#java-streams)
1. [Java Non-Blocking IO](09%20-%20IO%20&%20Streams.md#java-non-blocking-io)
1. [HTTP Client (Java)](09%20-%20IO%20&%20Streams.md#http-client-java)

### [Databases](10%20-%20Databases.md)

1. [Data Sources (Hikari Connection Pool)](10%20-%20Databases.md#data-sources-hikari-connection-pool)
1. [H2, MySQL and PostgreSQL](10%20-%20Databases.md#h2-mysql-and-postgresql)
1. [Flyway (Database Migration)](10%20-%20Databases.md#flyway-database-migration)
1. [Statements, Prepared Statements, Result Sets](10%20-%20Databases.md#statements-prepared-statements-result-sets)
1. [Transactions](10%20-%20Databases.md#transactions)
1. [JOOQ](10%20-%20Databases.md#jooq)
1. [Query DSL](10%20-%20Databases.md#query-dsl)
1. [JPA and Hibernate](10%20-%20Databases.md#jpa-and-hibernate)

### [Concurrency](11%20-%20Concurrency.md)

1. [Threads](11%20-%20Concurrency.md#threads)
1. [Synchronized](11%20-%20Concurrency.md#synchronized)
1. [Deadlocks](11%20-%20Concurrency.md#deadlocks)
1. [Race Conditions](11%20-%20Concurrency.md#race-conditions)
1. [Executors and Schedulers](11%20-%20Concurrency.md#executors-and-schedulers)
1. [New Concurrent Primitives](11%20-%20Concurrency.md#new-concurrent-primitives)
1. [Fork Join Framework](11%20-%20Concurrency.md#fork-join-framework)

### [Common Design Patterns](12%20-%20Common%20Design%20Patterns.md)

1. [Creational Design Pattern](12%20-%20Common%20Design%20Patterns.md#creational-design-pattern)
    1. [Factory Pattern](12%20-%20Common%20Design%20Patterns.md#factory-pattern)
    1. [Abstract Factory Pattern](12%20-%20Common%20Design%20Patterns.md#abstract-factory-pattern)
    1. [Singleton Pattern](12%20-%20Common%20Design%20Patterns.md#singleton-pattern)
    1. [Prototype Pattern](12%20-%20Common%20Design%20Patterns.md#prototype-pattern)
    1. [Builder Pattern.](12%20-%20Common%20Design%20Patterns.md#builder-pattern)
1. [Structural Design Pattern](12%20-%20Common%20Design%20Patterns.md#structural-design-pattern)
    1. [Adapter Pattern](12%20-%20Common%20Design%20Patterns.md#adapter-pattern)
    1. [Bridge Pattern](12%20-%20Common%20Design%20Patterns.md#bridge-pattern)
    1. [Composite Pattern](12%20-%20Common%20Design%20Patterns.md#composite-pattern)
    1. [Decorator Pattern](12%20-%20Common%20Design%20Patterns.md#decorator-pattern)
    1. [Facade Pattern](12%20-%20Common%20Design%20Patterns.md#facade-pattern)
    1. [Flyweight Pattern](12%20-%20Common%20Design%20Patterns.md#flyweight-pattern)
    1. [Proxy Pattern](12%20-%20Common%20Design%20Patterns.md#proxy-pattern)
1. [Behavioral Design Pattern](12%20-%20Common%20Design%20Patterns.md#behavioral-design-pattern)
    1. [Chain Of Responsibility Pattern](12%20-%20Common%20Design%20Patterns.md#chain-of-responsibility-pattern)
    1. [Command Pattern](12%20-%20Common%20Design%20Patterns.md#command-pattern)
    1. [Interpreter Pattern](12%20-%20Common%20Design%20Patterns.md#interpreter-pattern)
    1. [Iterator Pattern](12%20-%20Common%20Design%20Patterns.md#iterator-pattern)
    1. [Mediator Pattern](12%20-%20Common%20Design%20Patterns.md#mediator-pattern)
    1. [Memento Pattern](12%20-%20Common%20Design%20Patterns.md#memento-pattern)
    1. [Observer Pattern](12%20-%20Common%20Design%20Patterns.md#observer-pattern)
    1. [State Pattern](12%20-%20Common%20Design%20Patterns.md#state-pattern)
    1. [Strategy Pattern](12%20-%20Common%20Design%20Patterns.md#strategy-pattern)
    1. [Template Pattern](12%20-%20Common%20Design%20Patterns.md#template-pattern)
    1. [Visitor Pattern](12%20-%20Common%20Design%20Patterns.md#visitor-pattern)

### [Recommended Reading](13%20-%20Recommended%20Reading.md)

1. [Java](13%20-%20Recommended%20Reading.md#java)
1. [Gradle](13%20-%20Recommended%20Reading.md#gradle)
1. [Docker](13%20-%20Recommended%20Reading.md#docker)
1. [Kubernetes](13%20-%20Recommended%20Reading.md#kubernetes)
1. [JUnit](13%20-%20Recommended%20Reading.md#junit)
1. [Mockito](13%20-%20Recommended%20Reading.md#mockito)
1. [Miscellaneous](13%20-%20Recommended%20Reading.md#miscellaneous)
