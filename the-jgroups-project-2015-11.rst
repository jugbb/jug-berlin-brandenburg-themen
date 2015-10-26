The jGroups Project
=================

Checkliste
----------

**Raum angefragt**: offen

**Raum bestätigt**: offen

**Alle Referenten bestätigt**: offen

**Einladung Meetup**: offen

**Einladung per XING**: offen

**Termin im Heise Kalender**: offen

**Kurztext zu Referenten**: offen

**Themenbeschreibung**: offen

**Google-Kalender**: offen

**Blogeintrag**: offen

**Folien bekommen**: offen

**Folien online**: offen

Zeitpunkt der Veranstaltung
---------------------------

**Datum**: 19.11.2015

**Anfang**: 18:30

**Ende**: 21:00

Veranstaltungsort
-----------------

**Bezeichnung**: 

**Adresse**: 

**Max. Teilnehmer**: 140

Referenten
----------

Paul Ferro
~~~~~~
Bio

Tristan Tarrant
~~~~~~
Bio

Galder Zamarreño
~~~~~~
Galder Zamarreño is a core R&D engineer at JBoss, a division of Red Hat.
He is one of the founding engineers of Infinispan, Red Hat's distributed, 
in-memory key-value store and he currently spends most of his time developing 
Infinispan's Functional Map API as well as other data grid and caching 
functionality. He is very keen on functional programming and has been 
developing Scala since 2009. Galder has previously worked with JBoss 
customers helping them build highly distributed and massively scalable 
Application Server clusters based on technologies such as 
JGroups and JBoss Cache.  Prior to joining Red Hat, Galder worked in the 
Retail industry where he was a software developer involved in the 
development of an EFT software switch solution based on JBoss technologies.
The love for distributed systems and open source software comes from his 
days at ESIDE faculty at University of Deusto (Bilbao, Spain) where he 
studied a master's degree in Computer Science.

Bela Ban
~~~~~~
After completing his PhD at the University of Zurich (on network
management) and 4 years as a researcher at IBM Research,
Bela spent 2 years at Cornell as a post-doc, and starting JGroups,
a toolkit for reliable group communication.

Bela then worked for Fujitsu Network Communications in San Jose, CA,
for 4 years (network management for optical switches).

In 2003, he joined JBoss (as employee #007) to work full-time on
JBossCache and JGroups. Later, he handed over JBossCache to focus only
on JGroups. To this day he's still working on JGroups... but recently started
a new project jgroups-raft

Bela's interests include network protocols, performance, group
communication, running, biking, beerathlon and tennis, but not
necessarily in that order.

Bela doesn't like maven, scala and talking about himself in the third
person. 

Thema bzw. Themen
-----------------

Overview on JGroups
~~~~~~~~~~~~~~~~~~~
**Sprecher**: Bela Ban

JGroups is a library for cluster communication. It provides cluster management 
(joining and leaving members, and handling crashed members), sending and 
receiving of messages reliably (e.g. over IP multicast), plus high-level 
functionality such as RPCs across clusters.
In this talk, Bela will give an overview of what JGroups is and what it can 
be used for, and show some code samples. 


Java 8 in Infinispan 8: Distributed Streams and Functional Map
~~~~~~~~~~~~~~~~~~~
**Sprecher**: Galder Zamarreño

Infinispan is a distributed in-memory key/value data store and recently 
Infinispan 8 was released which takes advantage of the new Java 8 
features to provide new ways to interact with the data:
- Stream operations exposed by Infinispan’s ConcurrentMap 
  implementation can now be distributed, meaning that the 
  processing can be distributed increasing the level of 
  parallelization to be cluster wide.
- A brand new experimental Functional Map API has been developed 
  that provides a fully-asynchronous, lambda-based, API for interacting 
  with data. The aim of this API is to complement existing Infinispan APIs 
  while at the same time offering an improved key/value data store 
  experience compared to Java’s ConcurrentMap and JSR-107’s JCache.

In this talk, Will and Galder give an introduction about the Distributed 
Streams and Functional Map API, explaining the best use cases for them and 
showing examples on how to make the most of these new APIs.

Infinispan: Distributed Cross-Application Caching 
~~~~~~~~~~~~~~~~~~~
**Sprecher**: Tristan Tarrant

Infinispan is a Java library for embedded caching. It is also a server 
for remote caching. It can run as a local cache. It can also scale 
to hundreds of distributed nodes. You can use it to store, retrieve, 
query, compute and listen to changes in your data.

In this talk Tristan will provide an overview of the variety of uses 
to which you can put Infinispan in your applications, from simple 
Java applications, to cross-language, cross-platform application 
ecosystems. 


Clustering in WildFly 10
~~~~~~~~~~~~~~~~~~~
**Sprecher**: Paul Ferro

WildFly, formerly JBoss Application Server, has made its name as the
world's fastest Java EE7 application server. This talk will provide
an overview of new and improved clustering features in the latest
releases, including the public clustering API, singleton deployments,
and using WildFly as a pure-java load balancer.