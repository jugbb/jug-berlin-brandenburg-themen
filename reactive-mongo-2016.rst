Reactive access to MongoDB with Java 8
=================

Checkliste
----------

**Raum angefragt**:

**Raum bestätigt**:

**Alle Referenten bestätigt**:

**Einladung Meetup**: 

**Einladung per XING**:

**Termin im Heise Kalender**:

**Kurztext zu Referenten**: OK

**Themenbeschreibung**:

**Google-Kalender**:

**JaxEnter benachrichtigt**:

**Blogeintrag**:

**Folien bekommen**:

**Folien online**:

Zeitpunkt der Veranstaltung
---------------------------

**Datum**: Oktober????

**Anfang**:

**Ende**:

Veranstaltungsort
-----------------

**Bezeichnung**:

**Adresse**:

**Max. Teilnehmer**:

Referenten
----------

Herrmann Hück
~~~~~~
I am Software Developer and Architect for Functional Reactive
Programming with Scala, Java 8, Akka and Play.

In the 90s I was programming C/C++ under Unix and Windows. After a short
intermezzo as Perl hacker in 2000/2001 I moved to the world of Java
Enterprise Applications using Servlets, JSP, EJB, Spring and Hibernate
(since 2001). Since 2014 I am focussing on Scala based Technologies
(Akka, Play, Spark). Scala taught me a new way of thinking and also
improved my Java programming skills.

For more details see my XING profile at:
https://www.xing.com/profile/Hermann_Hueck


Thema bzw. Themen
-----------------

Reactive access to MongoDB with Java 8
~~~~~~~~~~~~~~~~~~~
**Sprecher**: Herrmann Hück

This talk explores different Java Drivers for MongoDB and different
(mostly asynchronous) strategies to access the database. The combination
of Mongo drivers and programming strategies result in a great variety of
possible solutions each shown by a small code sample. With the samples
we can discuss the advantages and drawbacks of these stragegies.

Beginning with a discussion of …

         What is asynchronous and what is reactive?

The code samples are using the following Mongo drivers for Java:
- Sychronous Java Driver
- Asychronous Java Driver (using Callbacks)
- Asychronous Java Driver (using RxJava)
- Asychronous Java Driver (implementing Reactive Streams Interface)

The code samples use the drivers in combination with the following
access strategies:

- Synchronous DB access
- Async DB access with Future (from Java 5)
- Async DB access with CompletableFuture (from Java 8)
- Async DB access with Callbacks
- Reactive DB access with Callbacks and CompletableFuture
- Reactive DB access with RxJava Observables
- Reactive DB access with Reactive Streams Interface + RxJava Observables
- Reactive DB access with Reactive Streams Interface + Akka Streams

All code samples are written in Java 8 using Java 8 features like
Lambdas, java.util.Optional and java.util.concurrent.CompletableFuture.

A great introduction to CompletableFutures by Angelika Langner can be
viewed here: https://www.youtube.com/watch?v=Q_0_1mKTlnY
