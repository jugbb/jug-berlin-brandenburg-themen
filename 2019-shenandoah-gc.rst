Shenandoah GC
=================

Checkliste
----------

**Raum angefragt**: ok

**Raum bestätigt**: ok

**Alle Referenten bestätigt**: ok

**Einladung Meetup**:

**Einladung per XING**:

**Termin im Heise Kalender**:

**Kurztext zu Referenten**: ok

**Themenbeschreibung**: ok

**Google-Kalender**:

**JaxEnter benachrichtigt**: nope

**Twitter**:

**Blogeintrag**: ok

**Folien bekommen**: nope

**Folien online**: nope

Zeitpunkt der Veranstaltung
---------------------------

**Datum**: 17. und 24.09.2019

**Anfang**: 18:30 Uhr Einlaß, Anfang 19:00

**Ende**: 21:00 Uhr

Veranstaltungsort
-----------------

**Bezeichnung**: innoQ Deutschland GmbH

**Adresse**: Ohlauer Str. 43, Treppenhaus C, 2. OG, 10999 Berlin

**Max. Teilnehmer**: 60 Kapazität

Referenten
----------

Aleksey Shipilëv
~~~~~~
Aleksey is working on Java performance for 10+ years. Today he is employed by Red Hat,
where he does OpenJDK development and performance work. Aleksey develops and maintains
a number of OpenJDK subprojects, including JMH, JOL, and JCStress. He is also an active
participant in expert groups and communities dealing with performance and concurrency.
Prior joining Red Hat, Aleksey was working on Apache Harmony at Intel, then moved to
Sun Microsystems, which was later consumed by Oracle.

Kontaktdaten
~~~~~~~~~~~~
aleksey.shipilev@gmail.com

Thema bzw. Themen
-----------------

Shenandoah GC Part I
~~~~~~~~~~~~~~~~~~~
**Sprecher**: Aleksey Shipilëv

The major problem for large Java applications is G... (wait for it...) C pauses.
Large heaps storing lots of live data, the failure to adhere to generational
hypothesis, fragmentation due to old objects coming and going, exacerbate the
issues even more. OpenJDK GCs managed to solve the first large part of the
puzzle, concurrent marking — the ability to estimate the object reachability
graph without stopping the application for a long time. Shenandoah is the
new low-pause collector that tries to solve the second large part of the
puzzle — the ability to move the objects without stopping the application, cutting
the GC pauses even more. This talk is the basic introduction in Shenandoah's
design choices, important internal details, performance benefits and trade-offs.

Shenandoah GC Part II
~~~~~~~~~~~~~~~~~~~
**Sprecher**: Aleksey Shipilëv

The major problem for large Java applications is G... (wait for it...) C pauses.
Large heaps storing lots of live data, the failure to adhere to generational
hypothesis, fragmentation due to old objects coming and going, exacerbate the
issues even more. OpenJDK GCs managed to solve the first large part of the
puzzle, concurrent marking — the ability to estimate the object reachability
graph without stopping the application for a long time. Shenandoah is the
new low-pause collector that tries to solve the second large part of the
puzzle — the ability to move the objects without stopping the application, cutting
the GC pauses even more. This talk is the basic introduction in Shenandoah's
design choices, important internal details, performance benefits and trade-offs.
