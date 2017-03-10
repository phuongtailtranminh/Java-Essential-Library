# Java Essential Library

- [JSR](#jsr-java-specification-requests)
- [Books](#books)
- [Java 8](#java-8)
- [Apache Commons](#apache-commons)
- [Google Guava](#google-guava)
- [Dagger 2](#dagger-2)
- [Bean Mapper](#bean-mapper)
- [HikariCP](#hikaricp)
- [Joda-Time](#joda-time)
- [Hibernate ORM](#hibernate-orm)

### JSR (Java Specification Requests)

- [JSR 354: Money and Currency API](https://jcp.org/en/jsr/detail?id=354)
- [JSR 303: Bean Validation](https://jcp.org/en/jsr/detail?id=303)

### Books

- [High-Performance Java Persistence](https://leanpub.com/high-performance-java-persistence)

### Java 8
- [A Few Hidden Treasures in Java 8](https://www.youtube.com/watch?v=GphO9fWhlAg)
- [Java 8 best practices by Stephen Colebourne](https://www.youtube.com/watch?v=wOks4LW6I24)
- [Refactoring to Java 8 by Trisha Gee](https://www.youtube.com/watch?v=NcetKbGayZY)
- [Java 8 Language Capabilities, What's in it for you?](https://www.youtube.com/watch?v=j9nj5dTo54Q)
- [Transforming Code to Java 8](https://www.youtube.com/watch?v=wk3WLaR2V2U)
- [Manning Publications: First class functions in Java 8](https://www.youtube.com/watch?v=gDTzlfjMe98)
- [GOTO 2014 • New Concurrency Utilities in Java 8 • Angelika Langer](https://www.youtube.com/watch?v=Q_0_1mKTlnY)
- [Java 8 Lambda Expressions & Streams](https://www.youtube.com/watch?v=8pDm_kH4YKY)
- [Get a Taste of Lambdas and Get Addicted to Streams by Venkat Subramaniam](https://www.youtube.com/watch?v=1OpAgZvYXLQ)
- [Asynchronous programming in Java 8: how to use CompletableFuture by José Paumard](https://www.youtube.com/watch?v=HdnHmbFg_hw)

### Apache Commons

"The Apache Commons Lang 3 library provides support for manipulation of core classes of the Java APIs. This support includes methods for handling strings, numbers, dates, concurrency, object reflection and more.

In addition to providing a general introduction to the library, this tutorial demonstrates methods of two of the most commonly used classes, namely ArrayUtils and StringUtils. ArrayUtils is used for operations on arrays, while StringUtils is used for manipulation of String instances." - BaelDung

- [Homepage](https://commons.apache.org/proper/commons-lang/)
- [String Processing with Apache Commons Lang 3](http://www.baeldung.com/string-processing-commons-lang)

### Google Guava

"Guava is a set of core libraries that includes new collection types (such as multimap and multiset), immutable collections, a graph library, functional types, an in-memory cache, and APIs/utilities for concurrency, I/O, hashing, primitives, reflection, string processing, and much more!

Requires JDK 1.8 or higher. If you need support for JDK 1.6 or Android, use 20.0 for now. In the next release (22.0) we will begin providing a backport for use on Android and lower JDK versions."

- [Wiki](https://github.com/google/guava/wiki)
- [An Overview of Guava: Google Core Libraries for Java](https://www.youtube.com/watch?v=MFEJll-wU7Q)
- [Four reasons to use Guava](https://www.youtube.com/watch?v=r8seIn7NZQw)
- [Google Guava, Mite Mitreski](https://www.youtube.com/watch?v=96R9I1i0AM4)
- [Java Caching with Guava](https://www.youtube.com/watch?v=keqKDhGIJZ8)
- [GTUG - Using the Google Collections Library for Java (1 of 2)](https://www.youtube.com/watch?v=ZeO_J2OcHYM)
- [GTUG - Using the Google Collections Library for Java (2 of 2)](https://www.youtube.com/watch?v=9ni_KEkHfto)

### Dagger 2

- [DAGGER 2 - A New Type of dependency injection](https://www.youtube.com/watch?v=oK_XtfXPkqw)
- [The Future of Dependency Injection with Dagger 2](https://www.youtube.com/watch?v=plK0zyRLIP8)
- [Dependency Injection Using Dagger 2](https://www.youtube.com/watch?v=cA4iEmWuSB8)
- [Dagger 2 @ Pandora](https://www.youtube.com/watch?v=wInzJ76uWTQ)

### Google Guice

"With dependency injection, objects accept dependencies in their constructors. To construct an object, you first build its dependencies. But to build each dependency, you need its dependencies, and so on. So when you build an object, you really need to build an object graph.

Building object graphs by hand is labour intensive, error prone, and makes testing difficult. Instead, Guice can build the object graph for you. But first, Guice needs to be configured to build the graph exactly as you want it."

- [Wiki](https://github.com/google/guice/wiki/GettingStarted)

### Bean Mapper

"Orika is a Java Bean mapping framework that recursively copies (among other capabilities) data from one object to another. It can be very useful when developing multi-layered applications."

I find out that Orika Mapper is better than ModelMapper when I need to excluse some properties (for Hibernate Lazy Loading). ModelMapper for List is really ugly and hard to use.

- [Github](https://github.com/orika-mapper/orika)

### HikariCP

The fastest stand-alone connection pool in Java world

"Fast, simple, reliable. HikariCP is a "zero-overhead" production ready JDBC connection pool. At roughly 130Kb, the library is very light"

- [Github](https://github.com/brettwooldridge/HikariCP)

### Joda-Time

"The standard date and time classes prior to Java SE 8 are poor. By tackling this problem head-on, Joda-Time became the de facto standard date and time library for Java prior to Java SE 8. Note that from Java SE 8 onwards, users are asked to migrate to java.time (JSR-310) - a core part of the JDK which replaces this project."

- [Quickstart](http://www.joda.org/joda-time/quickstart.html)

### Hibernate ORM

"Hibernate ORM enables developers to more easily write applications whose data outlives the application process. As an Object/Relational Mapping (ORM) framework, Hibernate is concerned with data persistence as it applies to relational databases (via JDBC). Unfamiliar with the notion of ORM? Read here."

- [Homepage](http://hibernate.org/orm/)
