Event Sourcing - You are doing it wrong
=================

Checkliste
----------

**Raum angefragt**: ok

**Raum bestätigt**: ok

**Alle Referenten bestätigt**: ok

**Einladung Meetup**: ok

**Einladung per XING**: ok

**Termin im Heise Kalender**: nop

**Kurztext zu Referenten**: ok

**Themenbeschreibung**: ok

**Google-Kalender**: ok

**JaxEnter benachrichtigt**: nop

**Blogeintrag**:

Zeitpunkt der Veranstaltung
---------------------------

**Datum**: 6. Dezember 2018

**Anfang**: 18:30 Uhr Einlaß, 19:00 Uhr Vortragsbeginn

**Ende**: 21:00 Uhr

Veranstaltungsort
-----------------

**Bezeichnung**: E-Post Development GmbH

**Adresse**: Ehrenberger Straße 11-13, 10245 Berlin

**Max. Teilnehmer**: 140

Referenten
----------

David Schmitz
~~~~~~
David Schmith is a consulting architect, programmer, coach, building
applications for various rather large financial institutes and
insurance companies for more than 15 years. Since greenfield projects
are rare and precious, I have been using various tech stacks ranging
from WS-* with EJBs to HapiJS on Node.

Currently I am focusing on cloud architectures, serverless computing,
conversational user interfaces and any good reason to use Elixir.

Kontaktdaten
~~~~~~~~~~~~
E-Mail: David.Schmitz@senacor.com


Thema bzw. Themen
-----------------

Event Sourcing - You are doing it wrong

~~~~~~~~~~~~~~~~~~~
**Sprecher**: David Schmitz

This talk is about staying sane when using eventsouring in your microservices.

Eventsourcing and CQRS are two very useful and popular patterns when dealing with data and microservices. We often find in our customer's projects, that both have a severe impact on your future options and the maintainability of your architecture. Presentations and articles on both topics are often superficial and do not tackle real world problems like security and compliance requirements.

This combination of half-knowledge and technical confusion leads to many projects that either refactor back to a 'non-eventsourced' architecture or reduce eventsourcing to a message queue.

In this talk, I will summarize our experience while applying eventsourcing and CQRS accros multiple large financial and insurance companies over the last 5 years. We will cover the _Good_, the _Not so Good_, and the _'oh my god...all abandon ships!'_ when doing eventsourcing in the real world...and see how we solved these issues.

* Introduction to eventsourcing and CQRS - which problems does ES solve, why do we need it
* Your eventstore is not a message queue - why mixing both up is bad for you
* No, Kafka is not an eventsource - choosing the right tool
* Read models are overrated - why you should not start with readmodels
* GDPR, compliance and eventsourcing - what happens if you delete data from an immutable structure
* Transactions, concurrency and your eventsource - why serial writers are bad and how to handle consistency
* Versions, up-front-design and breaking things down the road - how to evolve eventsourced architectures