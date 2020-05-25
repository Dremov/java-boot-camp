# Java Boot Camp

Boot Camp for developers interested to learn Java.


## [Primer](01%20-%20Primer.md)

1. [Java](01%20-%20Primer.md#java)
    1. [What is Java?](01%20-%20Primer.md#what-is-java)
    1. [How do we develop Java Applications?](01%20-%20Primer.md#how-do-we-develop-java-applications)
    1. [Java Language Specification](01%20-%20Primer.md#java-language-specification)
        1. [🤔 Given that the specification is hard to read and understand, why should I care?](01%20-%20Primer.md#-given-that-the-specification-is-hard-to-read-and-understand-why-should-i-care)
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
1. [Extend your application capabilities (using third-party libraries)](01%20-%20Primer.md#extend-your-application-capabilities-using-third-party-libraries)
    1. [The Classpath](01%20-%20Primer.md#the-classpath)
    1. [Make a fat JAR](01%20-%20Primer.md#make-a-fat-jar)
1. [Making Applications Portable (Containerisation using Docker)](01%20-%20Primer.md#making-applications-portable-containerisation-using-docker)
    1. [What is Docker?](01%20-%20Primer.md#what-is-docker)
    1. [How does this work?](01%20-%20Primer.md#how-does-this-work)
    1. [More than just Containers](01%20-%20Primer.md#more-than-just-containers)
    1. [Setup Docker](01%20-%20Primer.md#setup-docker)
    1. [Working with Docker](01%20-%20Primer.md#working-with-docker)
    1. [Dockerize the Application](01%20-%20Primer.md#dockerize-the-application)
    1. [Multi-Stage Docker Build](01%20-%20Primer.md#multi-stage-docker-build)
    1. [Managing Docker Containers](01%20-%20Primer.md#managing-docker-containers)

## [Java Light](02%20-%20Java%20Light.md)

1. [JShell](02%20-%20Java%20Light.md#jshell)
1. [Java single file execution](02%20-%20Java%20Light.md#java-single-file-execution)
1. [Introduction to classes and methods](02%20-%20Java%20Light.md#introduction-to-classes-and-methods)
    1. [Source and class files](02%20-%20Java%20Light.md#source-and-class-files)
    1. [Methods](02%20-%20Java%20Light.md#methods)
1. [Using existing functionality](02%20-%20Java%20Light.md#using-existing-functionality)
1. [Introduction to variables and types](02%20-%20Java%20Light.md#introduction-to-variables-and-types)
1. [Introduction to collections](02%20-%20Java%20Light.md#introduction-to-collections)
    1. [Arrays](02%20-%20Java%20Light.md#arrays)
    1. [Lists](02%20-%20Java%20Light.md#lists)
1. [Introduction to control-flow](02%20-%20Java%20Light.md#introduction-to-control-flow)
    1. [If-Else](02%20-%20Java%20Light.md#if-else)
    1. [switch](02%20-%20Java%20Light.md#switch)
    1. [For Loops](02%20-%20Java%20Light.md#for-loops)

## [Data Types](03%20-%20Data%20Types.md)

1. [Numbers and Strings (Variables and Scope)](03%20-%20Data%20Types.md#numbers-and-strings-variables-and-scope)
    1. [Puzzle (Time for a change)](03%20-%20Data%20Types.md#puzzle-time-for-a-change)
    1. [Puzzle (Long Division)](03%20-%20Data%20Types.md#puzzle-long-division)
    1. [Puzzle (It's Elementary)](03%20-%20Data%20Types.md#puzzle-its-elementary)
    1. [Puzzle (The Joy of Hex)](03%20-%20Data%20Types.md#puzzle-the-joy-of-hex)
    1. [Puzzle (Hello Whirled)](03%20-%20Data%20Types.md#puzzle-hello-whirled)
    1. [Puzzle (Line Printer)](03%20-%20Data%20Types.md#puzzle-line-printer)
    1. [Puzzle (huh?)](03%20-%20Data%20Types.md#puzzle-huh)
    1. [Puzzle (String Cheese)](03%20-%20Data%20Types.md#puzzle-string-cheese)
    1. [Puzzle (Classy Fire)](03%20-%20Data%20Types.md#puzzle-classy-fire)
    1. [Puzzle (What's my class?)](03%20-%20Data%20Types.md#puzzle-whats-my-class)
    1. [Puzzle (What's my class, Take 2)](03%20-%20Data%20Types.md#puzzle-whats-my-class-take-2)
    1. [Mutable Strings](03%20-%20Data%20Types.md#mutable-strings)
        1. [Puzzle (No Pain, No Gain)](03%20-%20Data%20Types.md#puzzle-no-pain-no-gain)
    1. [Text blocks and multiline strings](03%20-%20Data%20Types.md#text-blocks-and-multiline-strings)
    1. [Primitive Types](03%20-%20Data%20Types.md#primitive-types)
    1. [Signed and Unsigned Integrals](03%20-%20Data%20Types.md#signed-and-unsigned-integrals)
    1. [Reference Types (the rest)](03%20-%20Data%20Types.md#reference-types-the-rest)
    1. [Variables and their Values](03%20-%20Data%20Types.md#variables-and-their-values)
1. [Stack and Heap](03%20-%20Data%20Types.md#stack-and-heap)
    1. [OS Process Memory](03%20-%20Data%20Types.md#os-process-memory)
    1. [What goes in the Java Stack?](03%20-%20Data%20Types.md#what-goes-in-the-java-stack)
    1. [What goes in the Java Heap?](03%20-%20Data%20Types.md#what-goes-in-the-java-heap)
    1. [Variables without a value](03%20-%20Data%20Types.md#variables-without-a-value)
    1. [Can we have a reference variable without the equivalent object in the Java heap (null)?](03%20-%20Data%20Types.md#can-we-have-a-reference-variable-without-the-equivalent-object-in-the-java-heap-null)
        1. [What happens if we try to call a method on a null object?](03%20-%20Data%20Types.md#what-happens-if-we-try-to-call-a-method-on-a-null-object)
        1. [What is NullPointerException?](03%20-%20Data%20Types.md#what-is-nullpointerexception)
    1. [The new operator and the Java Heap](03%20-%20Data%20Types.md#the-new-operator-and-the-java-heap)
    1. [Garbage Collection](03%20-%20Data%20Types.md#garbage-collection)
    1. [String or new String?](03%20-%20Data%20Types.md#string-or-new-string)
    1. [What happens to a variable when it goes out of scope?](03%20-%20Data%20Types.md#what-happens-to-a-variable-when-it-goes-out-of-scope)
1. [Operators](03%20-%20Data%20Types.md#operators)
    1. [Puzzle (Tweedledum)](03%20-%20Data%20Types.md#puzzle-tweedledum)
    1. [Puzzle (Tweedledee)](03%20-%20Data%20Types.md#puzzle-tweedledee)
    1. [Puzzle (The Last Laugh)](03%20-%20Data%20Types.md#puzzle-the-last-laugh)
    1. [Puzzle (Oddity)](03%20-%20Data%20Types.md#puzzle-oddity)
    1. [Puzzle (Swap Meat)](03%20-%20Data%20Types.md#puzzle-swap-meat)
    1. [Puzzle (Escape Rout)](03%20-%20Data%20Types.md#puzzle-escape-rout)
    1. [Puzzle (A Big Delight in Every Byte)](03%20-%20Data%20Types.md#puzzle-a-big-delight-in-every-byte)
    1. [Puzzle (Inclement Increment)](03%20-%20Data%20Types.md#puzzle-inclement-increment)
1. [Mutable and Immutable](03%20-%20Data%20Types.md#mutable-and-immutable)
    1. [The final keyword](03%20-%20Data%20Types.md#the-final-keyword)
1. [Casting](03%20-%20Data%20Types.md#casting)
    1. [Puzzle (Multicast)](03%20-%20Data%20Types.md#puzzle-multicast)
1. [Autoboxing](03%20-%20Data%20Types.md#autoboxing)
    1. [Autoboxing is an easy target for NullPointerException](03%20-%20Data%20Types.md#autoboxing-is-an-easy-target-for-nullpointerexception)
1. [Enumerations](03%20-%20Data%20Types.md#enumerations)
    1. [Can we create an instance of an enum?](03%20-%20Data%20Types.md#can-we-create-an-instance-of-an-enum)
    1. [Enums in Java can have methods](03%20-%20Data%20Types.md#enums-in-java-can-have-methods)
    1. [Even enums have names too](03%20-%20Data%20Types.md#even-enums-have-names-too)
    1. [Enum's Ordinal](03%20-%20Data%20Types.md#enums-ordinal)
        1. [Can we retrieve the enum through the ordinal?](03%20-%20Data%20Types.md#can-we-retrieve-the-enum-through-the-ordinal)
    1. [Enums in Java can have state](03%20-%20Data%20Types.md#enums-in-java-can-have-state)
    1. [Considerations before Persisting Enums](03%20-%20Data%20Types.md#considerations-before-persisting-enums)
        1. [Using the Enum's Ordinal as the unit of Persistence](03%20-%20Data%20Types.md#using-the-enums-ordinal-as-the-unit-of-persistence)
        1. [Using the Enum's Name as the unit of Persistence](03%20-%20Data%20Types.md#using-the-enums-name-as-the-unit-of-persistence)
        1. [Using a specific property as the unit of Persistence](03%20-%20Data%20Types.md#using-a-specific-property-as-the-unit-of-persistence)
    1. [Enums can extend functionality](03%20-%20Data%20Types.md#enums-can-extend-functionality)
1. [Packages, Imports and Static Imports](03%20-%20Data%20Types.md#packages-imports-and-static-imports)
    1. [Packages](03%20-%20Data%20Types.md#packages)
        1. [Organise Packages by Technology](03%20-%20Data%20Types.md#organise-packages-by-technology)
        1. [Organise Packages by Feature](03%20-%20Data%20Types.md#organise-packages-by-feature)
        1. [Organise Packages by Feature and Technology (Hybrid)](03%20-%20Data%20Types.md#organise-packages-by-feature-and-technology-hybrid)
    1. [Imports](03%20-%20Data%20Types.md#imports)
        1. [Same class name in different packages](03%20-%20Data%20Types.md#same-class-name-in-different-packages)
    1. [Static Imports](03%20-%20Data%20Types.md#static-imports)
1. [Date Time API](03%20-%20Data%20Types.md#date-time-api)
1. [Internationalization](03%20-%20Data%20Types.md#internationalization)
1. [Miscellaneous](03%20-%20Data%20Types.md#miscellaneous)

## [Classes, Methods and Objects](04%20-%20Classes%2C%20Methods%20and%20Objects.md)

1. [Anatomy of a Java class](04%20-%20Classes%2C%20Methods%20and%20Objects.md#anatomy-of-a-java-class)
    1. [Terms](04%20-%20Classes%2C%20Methods%20and%20Objects.md#terms)
1. [Classes, methods and properties (static no OOP)](04%20-%20Classes%2C%20Methods%20and%20Objects.md#classes-methods-and-properties-static-no-oop)
    1. [Is `void` a type?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#is-void-a-type)
    1. [Properties (static no OOP)](04%20-%20Classes%2C%20Methods%20and%20Objects.md#properties-static-no-oop)
1. [How can we test functionality that makes use of `static` methods?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#how-can-we-test-functionality-that-makes-use-of-static-methods)
    1. [What does `static` mean?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#what-does-static-mean)
    1. [How do `static` fields behave?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#how-do-static-fields-behave)
1. [Access control](04%20-%20Classes%2C%20Methods%20and%20Objects.md#access-control)
    1. [Classes access modifiers table](04%20-%20Classes%2C%20Methods%20and%20Objects.md#classes-access-modifiers-table)
    1. [Class members access modifiers table](04%20-%20Classes%2C%20Methods%20and%20Objects.md#class-members-access-modifiers-table)
    1. [Which access modifier should I pick?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#which-access-modifier-should-i-pick)
1. [Simple objects](04%20-%20Classes%2C%20Methods%20and%20Objects.md#simple-objects)
    1. [Create a simple box object](04%20-%20Classes%2C%20Methods%20and%20Objects.md#create-a-simple-box-object)
    1. [Add open and close functionality to the box](04%20-%20Classes%2C%20Methods%20and%20Objects.md#add-open-and-close-functionality-to-the-box)
    1. [Is `boolean` the right choice?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#is-boolean-the-right-choice)
        1. [Are there any other advantages, besides readability?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#are-there-any-other-advantages-besides-readability)
        1. [Why is the enum declared `private`?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#why-is-the-enum-declared-private)
    1. [What does '*object state*' mean?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#what-does-object-state-mean)
    1. [How do instance methods interact with the object's state?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#how-do-instance-methods-interact-with-the-objects-state)
    1. [Adding more state to our object](04%20-%20Classes%2C%20Methods%20and%20Objects.md#adding-more-state-to-our-object)
    1. [How can we prevent the use of invalid labels?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#how-can-we-prevent-the-use-of-invalid-labels)
        1. [Why is the `isValidLabel()` method `private` and `static`?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#why-is-the-isvalidlabel-method-private-and-static)
1. [What does `this` means?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#what-does-this-means)
    1. [Can we access `static` methods using the `this` keyword?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#can-we-access-static-methods-using-the-this-keyword)
    1. [How does the `this` keyword works with inner anonymous classes?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#how-does-the-this-keyword-works-with-inner-anonymous-classes)
    1. [🤔 How does `this` works with nested inner anonymous classes?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#-how-does-this-works-with-nested-inner-anonymous-classes)
1. [Constructors](04%20-%20Classes%2C%20Methods%20and%20Objects.md#constructors)
    1. [How many constructors can a class have?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#how-many-constructors-can-a-class-have)
    1. [Can one constructor call another constructor in the same class?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#can-one-constructor-call-another-constructor-in-the-same-class)
    1. [What are static factory methods?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#what-are-static-factory-methods)
    1. [Should utilities classes, like the `Math` class, have a constructor?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#should-utilities-classes-like-the-math-class-have-a-constructor)
    1. [Can we call methods from within a constructor?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#can-we-call-methods-from-within-a-constructor)
1. [Mutable and immutable](04%20-%20Classes%2C%20Methods%20and%20Objects.md#mutable-and-immutable)
    1. [How can we create immutable objects?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#how-can-we-create-immutable-objects)
    1. [How does mutability works when we have nested objects?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#how-does-mutability-works-when-we-have-nested-objects)
1. [Inheritance](04%20-%20Classes%2C%20Methods%20and%20Objects.md#inheritance)
    1. [Extending the `Box` functionality (creating and evolving the `LightBox` class step by step)](04%20-%20Classes%2C%20Methods%20and%20Objects.md#extending-the-box-functionality-creating-and-evolving-the-lightbox-class-step-by-step)
    1. [Can we add items to a box if the box is not open?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#can-we-add-items-to-a-box-if-the-box-is-not-open)
    1. [🤔 Can we design our classes to automatically prevents the object from going into invalid state (finite state machine)?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#-can-we-design-our-classes-to-automatically-prevents-the-object-from-going-into-invalid-state-finite-state-machine)
    1. [Create the `HeavyBox` (complete example)](04%20-%20Classes%2C%20Methods%20and%20Objects.md#create-the-heavybox-complete-example)
    1. [How can a subclass invoke a method in the parent class (the `super` keyword)?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#how-can-a-subclass-invoke-a-method-in-the-parent-class-the-super-keyword)
    1. [Can we prevent a class from being extended (the `final` keyword)?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#can-we-prevent-a-class-from-being-extended-the-final-keyword)
    1. [Are constructors inherited?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#are-constructors-inherited)
    1. [How do `private` constructor effect inheritance?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#how-do-private-constructor-effect-inheritance)
    1. [Can a subclass invoke the constructor of a superclass (the `super()`)?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#can-a-subclass-invoke-the-constructor-of-a-superclass-the-super)
    1. [Can a constructor in a parent class call a method in a subclass?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#can-a-constructor-in-a-parent-class-call-a-method-in-a-subclass)
    1. [What happens when not all '*children*' are '*parents*'?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#what-happens-when-not-all-children-are-parents)
    1. [Is inheritance evil and should be considered as an anti-pattern?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#is-inheritance-evil-and-should-be-considered-as-an-anti-pattern)
1. [Abstraction](04%20-%20Classes%2C%20Methods%20and%20Objects.md#abstraction)
    1. [When a class must be abstract?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#when-a-class-must-be-abstract)
    1. [Can `final` classes be `abstract`?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#can-final-classes-be-abstract)
    1. [Can `abstract` classes have `private` constructors?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#can-abstract-classes-have-private-constructors)
1. [The `Object` class](04%20-%20Classes%2C%20Methods%20and%20Objects.md#the-object-class)
    1. [The `toString()` method](04%20-%20Classes%2C%20Methods%20and%20Objects.md#the-tostring-method)
    1. [The `equals()` and `hashCode()` methods](04%20-%20Classes%2C%20Methods%20and%20Objects.md#the-equals-and-hashcode-methods)
        1. [Puzzle (Animal Farm)](04%20-%20Classes%2C%20Methods%20and%20Objects.md#puzzle-animal-farm)
    1. [The `getClass()` method](04%20-%20Classes%2C%20Methods%20and%20Objects.md#the-getclass-method)
    1. [The `wait()`, `notify()` and `notifyAll()` methods](04%20-%20Classes%2C%20Methods%20and%20Objects.md#the-wait-notify-and-notifyall-methods)
1. [Interfaces](04%20-%20Classes%2C%20Methods%20and%20Objects.md#interfaces)
    1. [What is an interface?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#what-is-an-interface)
    1. [How is an interface different from a class?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#how-is-an-interface-different-from-a-class)
    1. [How can we use interfaces?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#how-can-we-use-interfaces)
    1. [Can we create an instance of an interface?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#can-we-create-an-instance-of-an-interface)
    1. [Functional interface and lambda functions](04%20-%20Classes%2C%20Methods%20and%20Objects.md#functional-interface-and-lambda-functions)
        1. [What is the relation between lambda and functional interfaces?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#what-is-the-relation-between-lambda-and-functional-interfaces)
    1. [Can an interface extend another class or another interface?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#can-an-interface-extend-another-class-or-another-interface)
    1. [How many interfaces can a class implement?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#how-many-interfaces-can-a-class-implement)
    1. [What happens if a class implements two interfaces that have the same abstract method?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#what-happens-if-a-class-implements-two-interfaces-that-have-the-same-abstract-method)
    1. [What's the purpose of an interface that has no abstract methods (marker interface)?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#whats-the-purpose-of-an-interface-that-has-no-abstract-methods-marker-interface)
    1. [What are `default` and `static` methods?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#what-are-default-and-static-methods)
    1. [What happens if a class implements two interfaces that have the same `default` methods?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#what-happens-if-a-class-implements-two-interfaces-that-have-the-same-default-methods)
1. [Sorting (the `Comparable` and `Comparator` interfaces)](04%20-%20Classes%2C%20Methods%20and%20Objects.md#sorting-the-comparable-and-comparator-interfaces)
    1. [How can we apply natural ordering to a custom class (the `Comparable` interface)?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#how-can-we-apply-natural-ordering-to-a-custom-class-the-comparable-interface)
    1. [How does the `compareTo()` method works?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#how-does-the-compareto-method-works)
    1. [What will happen if one of the properties used is `null`?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#what-will-happen-if-one-of-the-properties-used-is-null)
    1. [Can we use multiple properties to determine natural ordering?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#can-we-use-multiple-properties-to-determine-natural-ordering)
    1. [How can we sort the `Point` class (the `Comparator` interface)?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#how-can-we-sort-the-point-class-the-comparator-interface)
    1. [Can we compare two integers by subtracting one from the other?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#can-we-compare-two-integers-by-subtracting-one-from-the-other)
1. [The `instanceof` and cast operators](04%20-%20Classes%2C%20Methods%20and%20Objects.md#the-instanceof-and-cast-operators)
    1. [Are there good examples of the `instanceof` and cast operators?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#are-there-good-examples-of-the-instanceof-and-cast-operators)
    1. [What is upcasting and how is it different from casting or downcasting?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#what-is-upcasting-and-how-is-it-different-from-casting-or-downcasting)
    1. [Is there a better approach than relying on `instanceof` and cast operators (polymorphism)?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#is-there-a-better-approach-than-relying-on-instanceof-and-cast-operators-polymorphism)
    1. [Can we cast any object to any object?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#can-we-cast-any-object-to-any-object)
    1. [What happens if we cast the wrong object (the `ClassCastException`)?](04%20-%20Classes%2C%20Methods%20and%20Objects.md#what-happens-if-we-cast-the-wrong-object-the-classcastexception)
1. [Inheritance and composition](04%20-%20Classes%2C%20Methods%20and%20Objects.md#inheritance-and-composition)
1. [Overloading and overriding](04%20-%20Classes%2C%20Methods%20and%20Objects.md#overloading-and-overriding)
    1. [Overloading](04%20-%20Classes%2C%20Methods%20and%20Objects.md#overloading)
    1. [Overriding](04%20-%20Classes%2C%20Methods%20and%20Objects.md#overriding)
1. [Initialisation blocks, outer, inner and anonymous classes](04%20-%20Classes%2C%20Methods%20and%20Objects.md#initialisation-blocks-outer-inner-and-anonymous-classes)
    1. [Initialisation block](04%20-%20Classes%2C%20Methods%20and%20Objects.md#initialisation-block)
    1. [`static` initialisation block](04%20-%20Classes%2C%20Methods%20and%20Objects.md#static-initialisation-block)
    1. [Outer class](04%20-%20Classes%2C%20Methods%20and%20Objects.md#outer-class)
    1. [Inner instance class](04%20-%20Classes%2C%20Methods%20and%20Objects.md#inner-instance-class)
    1. [Inner static class](04%20-%20Classes%2C%20Methods%20and%20Objects.md#inner-static-class)
    1. [Inner anonymous class](04%20-%20Classes%2C%20Methods%20and%20Objects.md#inner-anonymous-class)
1. [Annotations](04%20-%20Classes%2C%20Methods%20and%20Objects.md#annotations)
    1. [Project Lombok](04%20-%20Classes%2C%20Methods%20and%20Objects.md#project-lombok)
1. [Generics](04%20-%20Classes%2C%20Methods%20and%20Objects.md#generics)
1. [Miscellaneous](04%20-%20Classes%2C%20Methods%20and%20Objects.md#miscellaneous)
    1. [Objects have two words headers](04%20-%20Classes%2C%20Methods%20and%20Objects.md#objects-have-two-words-headers)
    1. [Records](04%20-%20Classes%2C%20Methods%20and%20Objects.md#records)
    1. [Others](04%20-%20Classes%2C%20Methods%20and%20Objects.md#others)

## [Collections](05%20-%20Collections.md)

1. [Arrays](05%20-%20Collections.md#arrays)
    1. [Create Arrays](05%20-%20Collections.md#create-arrays)
        1. [Puzzle (ABC)](05%20-%20Collections.md#puzzle-abc)
    1. [Working with Arrays](05%20-%20Collections.md#working-with-arrays)
    1. [Read past the array's length](05%20-%20Collections.md#read-past-the-arrays-length)
    1. [Multidimensional Arrays](05%20-%20Collections.md#multidimensional-arrays)
        1. [Two dimensional array](05%20-%20Collections.md#two-dimensional-array)
        1. [Irregular Arrays](05%20-%20Collections.md#irregular-arrays)
    1. [Arrays are always Mutable](05%20-%20Collections.md#arrays-are-always-mutable)
    1. [Defensive Copying](05%20-%20Collections.md#defensive-copying)
    1. [Arrays of Objects](05%20-%20Collections.md#arrays-of-objects)
        1. [Working title](05%20-%20Collections.md#working-title)
    1. [Sorting and Searching](05%20-%20Collections.md#sorting-and-searching)
    1. [An Array of Characters Is Not a String](05%20-%20Collections.md#an-array-of-characters-is-not-a-string)
1. [Lists (Vector, ArrayList and LinkedList)](05%20-%20Collections.md#lists-vector-arraylist-and-linkedlist)
    1. [Create Lists](05%20-%20Collections.md#create-lists)
    1. [Types of Lists](05%20-%20Collections.md#types-of-lists)
        1. [Vector](05%20-%20Collections.md#vector)
        1. [ArrayList](05%20-%20Collections.md#arraylist)
        1. [LinkedList](05%20-%20Collections.md#linkedlist)
        1. [Which List to Use?](05%20-%20Collections.md#which-list-to-use)
    1. [Double Brace Initialization](05%20-%20Collections.md#double-brace-initialization)
    1. [Mutable and Immutable Lists](05%20-%20Collections.md#mutable-and-immutable-lists)
1. [Set (HashSet, LinkedHashSet and TreeSet)](05%20-%20Collections.md#set-hashset-linkedhashset-and-treeset)
    1. [Create Sets](05%20-%20Collections.md#create-sets)
    1. [Set values MUST BE Immutable](05%20-%20Collections.md#set-values-must-be-immutable)
    1. [Types of Sets](05%20-%20Collections.md#types-of-sets)
        1. [HashSet](05%20-%20Collections.md#hashset)
        1. [LinkedHashSet](05%20-%20Collections.md#linkedhashset)
        1. [TreeSet](05%20-%20Collections.md#treeset)
        1. [Which Set to Use?](05%20-%20Collections.md#which-set-to-use)
    1. [Mutable and Immutable Sets](05%20-%20Collections.md#mutable-and-immutable-sets)
1. [Map (Hashtable, HashMap, LinkedHashMap and TreeMap)](05%20-%20Collections.md#map-hashtable-hashmap-linkedhashmap-and-treemap)
    1. [Create Maps](05%20-%20Collections.md#create-maps)
    1. [Map Keys MUST BE Immutable](05%20-%20Collections.md#map-keys-must-be-immutable)
    1. [Types of Maps](05%20-%20Collections.md#types-of-maps)
        1. [Hashtable](05%20-%20Collections.md#hashtable)
        1. [HashMap](05%20-%20Collections.md#hashmap)
        1. [LinkedHashMap](05%20-%20Collections.md#linkedhashmap)
        1. [TreeMap](05%20-%20Collections.md#treemap)
        1. [Which Map to Use?](05%20-%20Collections.md#which-map-to-use)
1. [Covariance and invariance](05%20-%20Collections.md#covariance-and-invariance)
1. [Relation between Collections the Objects they contain](05%20-%20Collections.md#relation-between-collections-the-objects-they-contain)
    1. [List and the equals() method](05%20-%20Collections.md#list-and-the-equals-method)
    1. [Hash based Collections and the equals() and hashCode() methods](05%20-%20Collections.md#hash-based-collections-and-the-equals-and-hashcode-methods)
1. [Queue and Stack](05%20-%20Collections.md#queue-and-stack)
    1. [Queues](05%20-%20Collections.md#queues)
    1. [Stacks](05%20-%20Collections.md#stacks)
1. [Java Collections Framework](05%20-%20Collections.md#java-collections-framework)
1. [Google Guava (Collections)](05%20-%20Collections.md#google-guava-collections)
1. [Miscellaneous](05%20-%20Collections.md#miscellaneous)

## [Control Flow](06%20-%20Control%20Flow.md)

1. [Control Flow and Loops](06%20-%20Control%20Flow.md#control-flow-and-loops)
    1. [If (if/else) Control Flow Statement](06%20-%20Control%20Flow.md#if-ifelse-control-flow-statement)
        1. [If Example](06%20-%20Control%20Flow.md#if-example)
        1. [If/else Example](06%20-%20Control%20Flow.md#ifelse-example)
        1. [If/else-if/else Example](06%20-%20Control%20Flow.md#ifelse-ifelse-example)
        1. [Java Ternary Operator](06%20-%20Control%20Flow.md#java-ternary-operator)
    1. [Switch Control Flow Statement](06%20-%20Control%20Flow.md#switch-control-flow-statement)
        1. [Switch Example](06%20-%20Control%20Flow.md#switch-example)
        1. [Switch Fallthrough Example](06%20-%20Control%20Flow.md#switch-fallthrough-example)
        1. [Switch Default Example](06%20-%20Control%20Flow.md#switch-default-example)
        1. [Switch Expressions](06%20-%20Control%20Flow.md#switch-expressions)
    1. [For Loop](06%20-%20Control%20Flow.md#for-loop)
        1. [Puzzles (In the Loop)](06%20-%20Control%20Flow.md#puzzles-in-the-loop)
    1. [While Loop](06%20-%20Control%20Flow.md#while-loop)
        1. [Puzzle (Shifty i's)](06%20-%20Control%20Flow.md#puzzle-shifty-is)
        1. [Puzzles (Looper)](06%20-%20Control%20Flow.md#puzzles-looper)
        1. [Puzzle (Bride of Looper)](06%20-%20Control%20Flow.md#puzzle-bride-of-looper)
        1. [Puzzle (Son of Looper)](06%20-%20Control%20Flow.md#puzzle-son-of-looper)
        1. [Puzzle (Ghost of Looper)](06%20-%20Control%20Flow.md#puzzle-ghost-of-looper)
    1. [Do/While Loop](06%20-%20Control%20Flow.md#dowhile-loop)
    1. [Foreach Loop](06%20-%20Control%20Flow.md#foreach-loop)
    1. [Nested Loops](06%20-%20Control%20Flow.md#nested-loops)
    1. [Break, Continue, Labels and Return](06%20-%20Control%20Flow.md#break-continue-labels-and-return)
        1. [Break](06%20-%20Control%20Flow.md#break)
        1. [Label](06%20-%20Control%20Flow.md#label)
            1. [Puzzle (Dupe of URL)](06%20-%20Control%20Flow.md#puzzle-dupe-of-url)
        1. [Continue](06%20-%20Control%20Flow.md#continue)
        1. [Return](06%20-%20Control%20Flow.md#return)
    1. [Loop and Control Flow Examples](06%20-%20Control%20Flow.md#loop-and-control-flow-examples)
        1. [How many rolls it takes to roll a 6?](06%20-%20Control%20Flow.md#how-many-rolls-it-takes-to-roll-a-6)
        1. [A simple game with dice and random numbers](06%20-%20Control%20Flow.md#a-simple-game-with-dice-and-random-numbers)
1. [Exceptions](06%20-%20Control%20Flow.md#exceptions)
    1. [Alternative Approach](06%20-%20Control%20Flow.md#alternative-approach)

## [Testing](07%20-%20Testing.md)

1. [Testing with JUnit 5 (Hamcrest and AssertJ)](07%20-%20Testing.md#testing-with-junit-5-hamcrest-and-assertj)
    1. [Add JUnit 5](07%20-%20Testing.md#add-junit-5)
    1. [Parameterized Test](07%20-%20Testing.md#parameterized-test)
    1. [Custom Converters](07%20-%20Testing.md#custom-converters)
    1. [Tests Tagging](07%20-%20Testing.md#tests-tagging)
    1. [Nested Tests](07%20-%20Testing.md#nested-tests)
    1. [Hamcrest](07%20-%20Testing.md#hamcrest)
    1. [AssertJ](07%20-%20Testing.md#assertj)
    1. [JUnit 5, Hamcrest and AssertJ](07%20-%20Testing.md#junit-5-hamcrest-and-assertj)
    1. [Test Lifecycle](07%20-%20Testing.md#test-lifecycle)
1. [Mocking (Mockito and EasyMock)](07%20-%20Testing.md#mocking-mockito-and-easymock)
    1. [What is Mocking (Test Doubles) and Why do we need it?](07%20-%20Testing.md#what-is-mocking-test-doubles-and-why-do-we-need-it)
    1. [Test Doubles](07%20-%20Testing.md#test-doubles)
    1. [Mockito](07%20-%20Testing.md#mockito)
    1. [EasyMock](07%20-%20Testing.md#easymock)
    1. [Which Mocking Framework](07%20-%20Testing.md#which-mocking-framework)
1. [Mutation Testing (PIT)](07%20-%20Testing.md#mutation-testing-pit)
1. [Google Guava (Preconditions)](07%20-%20Testing.md#google-guava-preconditions)
1. [Miscellaneous](07%20-%20Testing.md#miscellaneous)

## [SOLID](08%20-%20SOLID.md)

1. [Single-responsibility Principle](08%20-%20SOLID.md#single-responsibility-principle)
1. [Open–closed principle](08%20-%20SOLID.md#open-closed-principle)
1. [Liskov substitution principle](08%20-%20SOLID.md#liskov-substitution-principle)
1. [Interface segregation principle](08%20-%20SOLID.md#interface-segregation-principle)
1. [Dependency inversion principle](08%20-%20SOLID.md#dependency-inversion-principle)
1. [Miscellaneous](08%20-%20SOLID.md#miscellaneous)

## [Lambda & Streams](09%20-%20Lambda%20&%20Streams.md)

1. [Lambda Expressions](09%20-%20Lambda%20&%20Streams.md#lambda-expressions)
    1. [Function as Parameters](09%20-%20Lambda%20&%20Streams.md#function-as-parameters)
    1. [Constructor as Parameters](09%20-%20Lambda%20&%20Streams.md#constructor-as-parameters)
1. [Multiple Parameters](09%20-%20Lambda%20&%20Streams.md#multiple-parameters)
1. [Dealing with Exceptions](09%20-%20Lambda%20&%20Streams.md#dealing-with-exceptions)
1. [Foreach Loops](09%20-%20Lambda%20&%20Streams.md#foreach-loops)
1. [Streams (Lambda)](09%20-%20Lambda%20&%20Streams.md#streams-lambda)
    1. [Filter](09%20-%20Lambda%20&%20Streams.md#filter)
    1. [ForEach](09%20-%20Lambda%20&%20Streams.md#foreach)
    1. [Map](09%20-%20Lambda%20&%20Streams.md#map)
    1. [FlatMap](09%20-%20Lambda%20&%20Streams.md#flatmap)
    1. [Mapping and Filtering](09%20-%20Lambda%20&%20Streams.md#mapping-and-filtering)
1. [Collectors](09%20-%20Lambda%20&%20Streams.md#collectors)
1. [Common Uses](09%20-%20Lambda%20&%20Streams.md#common-uses)
    1. [Sum numbers in List](09%20-%20Lambda%20&%20Streams.md#sum-numbers-in-list)
    1. [Sum content in List based on property](09%20-%20Lambda%20&%20Streams.md#sum-content-in-list-based-on-property)
    1. [Create Map from List](09%20-%20Lambda%20&%20Streams.md#create-map-from-list)
1. [Miscellaneous](09%20-%20Lambda%20&%20Streams.md#miscellaneous)

## [IO & Streams](10%20-%20IO%20&%20Streams.md)

1. [Try with Resources](10%20-%20IO%20&%20Streams.md#try-with-resources)
1. [Java Streams](10%20-%20IO%20&%20Streams.md#java-streams)
    1. [Buffered Streams](10%20-%20IO%20&%20Streams.md#buffered-streams)
1. [Java Readers](10%20-%20IO%20&%20Streams.md#java-readers)
    1. [Consuming an InputStream](10%20-%20IO%20&%20Streams.md#consuming-an-inputstream)
    1. [Writing to an OutputStream](10%20-%20IO%20&%20Streams.md#writing-to-an-outputstream)
1. [Java Non-Blocking IO](10%20-%20IO%20&%20Streams.md#java-non-blocking-io)
1. [HTTP Client (Java)](10%20-%20IO%20&%20Streams.md#http-client-java)
1. [Miscellaneous](10%20-%20IO%20&%20Streams.md#miscellaneous)

## [Databases](11%20-%20Databases.md)

1. [H2, MySQL and PostgreSQL](11%20-%20Databases.md#h2-mysql-and-postgresql)
1. [Data Sources (Hikari Connection Pool)](11%20-%20Databases.md#data-sources-hikari-connection-pool)
1. [Flyway (Database Migration)](11%20-%20Databases.md#flyway-database-migration)
1. [Statements, Prepared Statements, Result Sets](11%20-%20Databases.md#statements-prepared-statements-result-sets)
1. [Transactions](11%20-%20Databases.md#transactions)
1. [JOOQ](11%20-%20Databases.md#jooq)
1. [Query DSL](11%20-%20Databases.md#query-dsl)
1. [JPA and Hibernate](11%20-%20Databases.md#jpa-and-hibernate)

## [Concurrency](12%20-%20Concurrency.md)

1. [Java Memory Model](12%20-%20Concurrency.md#java-memory-model)
1. [Threads](12%20-%20Concurrency.md#threads)
    1. [Daemons](12%20-%20Concurrency.md#daemons)
    1. [Waiting for a thread to finish (Join)](12%20-%20Concurrency.md#waiting-for-a-thread-to-finish-join)
    1. [ThreadLocal](12%20-%20Concurrency.md#threadlocal)
    1. [Stale Caches](12%20-%20Concurrency.md#stale-caches)
    1. [Race Conditions](12%20-%20Concurrency.md#race-conditions)
    1. [Methods that should never be used.](12%20-%20Concurrency.md#methods-that-should-never-be-used)
1. [Concurrent Data Classes](12%20-%20Concurrency.md#concurrent-data-classes)
    1. [Primitive Wrappers](12%20-%20Concurrency.md#primitive-wrappers)
    1. [List](12%20-%20Concurrency.md#list)
    1. [Set](12%20-%20Concurrency.md#set)
    1. [Map](12%20-%20Concurrency.md#map)
    1. [Queue](12%20-%20Concurrency.md#queue)
    1. [Exchanger](12%20-%20Concurrency.md#exchanger)
1. [Classic Concurrency Control](12%20-%20Concurrency.md#classic-concurrency-control)
    1. [Volatile](12%20-%20Concurrency.md#volatile)
    1. [Synchronized](12%20-%20Concurrency.md#synchronized)
    1. [Deadlocks](12%20-%20Concurrency.md#deadlocks)
1. [New Approach to Concurrency](12%20-%20Concurrency.md#new-approach-to-concurrency)
    1. [Executors and Schedulers](12%20-%20Concurrency.md#executors-and-schedulers)
    1. [Lock and ReentrantLock](12%20-%20Concurrency.md#lock-and-reentrantlock)
    1. [Latch](12%20-%20Concurrency.md#latch)
    1. [CyclicBarrier](12%20-%20Concurrency.md#cyclicbarrier)
    1. [Fork Join Framework](12%20-%20Concurrency.md#fork-join-framework)
1. [Cost of Concurrency](12%20-%20Concurrency.md#cost-of-concurrency)
1. [Miscellaneous](12%20-%20Concurrency.md#miscellaneous)

## [Common Design Patterns](13%20-%20Common%20Design%20Patterns.md)

1. [Creational Design Pattern](13%20-%20Common%20Design%20Patterns.md#creational-design-pattern)
    1. [Factory Pattern](13%20-%20Common%20Design%20Patterns.md#factory-pattern)
    1. [Abstract Factory Pattern](13%20-%20Common%20Design%20Patterns.md#abstract-factory-pattern)
    1. [Singleton Pattern](13%20-%20Common%20Design%20Patterns.md#singleton-pattern)
    1. [Prototype Pattern](13%20-%20Common%20Design%20Patterns.md#prototype-pattern)
    1. [Builder Pattern.](13%20-%20Common%20Design%20Patterns.md#builder-pattern)
1. [Structural Design Pattern](13%20-%20Common%20Design%20Patterns.md#structural-design-pattern)
    1. [Adapter Pattern](13%20-%20Common%20Design%20Patterns.md#adapter-pattern)
    1. [Bridge Pattern](13%20-%20Common%20Design%20Patterns.md#bridge-pattern)
    1. [Composite Pattern](13%20-%20Common%20Design%20Patterns.md#composite-pattern)
    1. [Decorator Pattern](13%20-%20Common%20Design%20Patterns.md#decorator-pattern)
    1. [Facade Pattern](13%20-%20Common%20Design%20Patterns.md#facade-pattern)
    1. [Flyweight Pattern](13%20-%20Common%20Design%20Patterns.md#flyweight-pattern)
    1. [Proxy Pattern](13%20-%20Common%20Design%20Patterns.md#proxy-pattern)
1. [Behavioral Design Pattern](13%20-%20Common%20Design%20Patterns.md#behavioral-design-pattern)
    1. [Chain Of Responsibility Pattern](13%20-%20Common%20Design%20Patterns.md#chain-of-responsibility-pattern)
    1. [Command Pattern](13%20-%20Common%20Design%20Patterns.md#command-pattern)
    1. [Interpreter Pattern](13%20-%20Common%20Design%20Patterns.md#interpreter-pattern)
    1. [Iterator Pattern](13%20-%20Common%20Design%20Patterns.md#iterator-pattern)
    1. [Mediator Pattern](13%20-%20Common%20Design%20Patterns.md#mediator-pattern)
    1. [Memento Pattern](13%20-%20Common%20Design%20Patterns.md#memento-pattern)
    1. [Observer Pattern](13%20-%20Common%20Design%20Patterns.md#observer-pattern)
    1. [State Pattern](13%20-%20Common%20Design%20Patterns.md#state-pattern)
    1. [Strategy Pattern](13%20-%20Common%20Design%20Patterns.md#strategy-pattern)
    1. [Template Pattern](13%20-%20Common%20Design%20Patterns.md#template-pattern)
    1. [Visitor Pattern](13%20-%20Common%20Design%20Patterns.md#visitor-pattern)

## [Recommended Reading](14%20-%20Recommended%20Reading.md)

1. [Java](14%20-%20Recommended%20Reading.md#java)
1. [Gradle](14%20-%20Recommended%20Reading.md#gradle)
1. [Docker](14%20-%20Recommended%20Reading.md#docker)
1. [Kubernetes](14%20-%20Recommended%20Reading.md#kubernetes)
1. [JUnit](14%20-%20Recommended%20Reading.md#junit)
1. [Mockito](14%20-%20Recommended%20Reading.md#mockito)
1. [Miscellaneous](14%20-%20Recommended%20Reading.md#miscellaneous)
