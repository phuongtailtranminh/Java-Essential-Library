# Java Essential Library

## Table of Contents

- [Articles](#articles)
- [JSR](#jsr-java-specification-requests)
- [Books](#books)
- [Java 8](#java-8)
- [Apache Commons](#apache-commons)
- [Google Guava](#google-guava)
- [Dagger 2](#dagger-2)
- [Google Guice](#google-guice)
- [MapStruct](#mapstruct)
- [HikariCP](#hikaricp)
- [Joda-Time](#joda-time)
- [Hibernate ORM](#hibernate-orm)
- [Benchmark Tools](#benchmark-tools)
- [Google Truth](#google-truth)
- [Awesome Java index](https://java.libhunt.com/)
- [Keycloak](#keycloak)
- [Fernflower](#fernflower)
- [HDIV](#hdiv)
- [NekoHTML](#nekohtml)

### Articles

- [Oracle Technology Network - Java](http://www.oracle.com/technetwork/articles/java/index.html)
- [IBM developerWorks - Java](https://www.ibm.com/developerworks/views/global/libraryview.jsp?sort_by=&show_abstract=false&show_all=&search_flag=&contentarea_by=Java+technology&search_by=&product_by=-1&topic_by=-1&industry_by=-1&type_by=All+Types&ibm-search=Search)

### JSR (Java Specification Requests)

- [JSR 354: Money and Currency API](https://jcp.org/en/jsr/detail?id=354)
- [JSR 303: Bean Validation](https://jcp.org/en/jsr/detail?id=303)
- [JSR 330: Dependency Injection for Java](https://www.jcp.org/en/jsr/detail?id=330)
- [JSR 339: JAX-RS 2.0: The Java API for RESTful Web Services](https://jcp.org/en/jsr/detail?id=339)
- [JSR 311: JAX-RS: The JavaTM API for RESTful Web Services](https://jcp.org/en/jsr/detail?id=311)

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

### MapStruct

"MapStruct is a code generator that greatly simplifies the implementation of mappings between Java bean types based on a convention over configuration approach. The generated mapping code uses plain method invocations and thus is fast, type-safe and easy to understand."

I found out that MapStruct is generally better than ModelMapper and Orika, provides a clean-way to do the Bean Mapper work and the community is very productive.

- [Documentation](http://mapstruct.org/documentation/dev/reference/html/)

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

### Benchmark Tools

"JMH is a Java harness for building, running, and analysing nano/micro/milli/macro benchmarks written in Java and other languages targetting the JVM."

- [Homepage](http://openjdk.java.net/projects/code-tools/jmh/)

### Google Truth

"Truth is an open source, fluent testing framework for Java that is designed to make your test assertions and failure messages more readable, as well as other benefits. It natively supports many JDK types (e.g., Iterable, String, Map) and Guava types (e.g., Optional, Multimap, Multiset, Table), and is also extensible to new types (YourCustomType). See all of the known types here.

You can also read Truth’s source directly, view its API docs, and compare it to common alternatives."

- [Benefit](https://google.github.io/truth/benefits)
- [Comparation](https://google.github.io/truth/comparison)

### Keycloak

"Keycloak is an open source Identity and Access Management solution aimed at modern applications and services. It makes it easy to secure applications and services with little to no code."

- [Homepage](http://www.keycloak.org/index.html)

### Fernflower

"Fernflower is the first actually working analytical decompiler for Java and probably for a high-level programming language in general."

- [Github](https://github.com/fesh0r/fernflower)

### HDIV

"Hdiv is a leading provider of open source software for real-time, self-protected applications. Hdiv solutions are built into applications during development to deliver the strongest available runtime application self-protection (RASP) against OWASP Top 10 threats. Since 2008, Hdiv has pioneered self-protection cyber security software, and today its solutions are used by leading commercial software providers and global enterprises in banking, government, retail, technology, and aerospace."

- [Github](https://github.com/hdiv/hdiv)

### NekoHTML

"NekoHTML is a simple HTML scanner and tag balancer that enables application programmers to parse HTML documents and access the information using standard XML interfaces. The parser can scan HTML files and "fix up" many common mistakes that human (and computer) authors make in writing HTML documents. NekoHTML adds missing parent elements; automatically closes elements with optional end tags; and can handle mismatched inline element tags."

Shortcut: spring.thymeleaf.mode=LEGACYHTML5

- [Homepage](http://nekohtml.sourceforge.net/)
