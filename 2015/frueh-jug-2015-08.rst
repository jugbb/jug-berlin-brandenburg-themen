Make your tests fail - How randomisation adds a whole new dimension to finding bugs in your code
=================

Checkliste
----------

**Raum angefragt**: offen

**Raum bestätigt**: offen

**Alle Referenten bestätigt**: done

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

**Datum**: 26.08.2015

**Anfang**: 9:00

**Ende**: 11:00

Veranstaltungsort
-----------------

**Bezeichnung**: Restaurant Marcello

**Adresse**: Fritz-Reuter-Straße 7, 10827-Berlin Schöneberg

**Max. Teilnehmer**: 35

Referenten
----------

Isabel Drost-From
~~~~~~
Isabel Drost-Fromm is member of the Apache Software Foundation,
co-founder of Apache Mahout and mentored several incubating
projects. Interested in all things search and text mining with
a decent machine learning background she is working for
Elasticsearch as Software developer. True to the nature of
people living in Berlin she loves having friends fly in for
a brief visit - as a result she co-founded and is still one
of the creative heads behind Berlin Buzzwords, a tech
conference on all things search, scale and storage. Beyond
and above all that Isabel is mummy of a little geekling
since April 2014.

Thema bzw. Themen
-----------------

Make your tests fail - How randomisation adds a whole new dimension to finding bugs in your code
~~~~~~~~~~~~~~~~~~~
**Sprecher**: Isabel Drost-From

It's easy as pie: before checking in, your test suite should always
be green. Or should it? What if your tests are all green but you
forgot to check one important edge case? What if your underlying
system environment lets you down, but only under rare conditions
that you didn't cover in your tests?

This talk introduces randomised testing as used by projects like
Apache Lucene and Elasticsearch based on the Carrotsearch
Randomised Testing framework. It has helped uncover
(and ultimately fix) a huge number of bugs not only in these
project’s source code, but also in the JVM itself which those
projects rely on.

Writing unit and integration tests can be tricky: assumptions
about your code may not always be true as any number of
"this should never happen" log entries in production systems show.
When implementing a system that will be integrated in all sorts
of expected, unexpected, and outright weird ways by downstream
users, testing all possible code paths, configurations and
deployment environments gets complicated.

With the Carrotsearch Randomised Testing framework, projects like
Apache Lucene and Elasticsearch have introduced a new level to their
unit and integration tests. Input values are no longer statically
pre-defined but are generated based on developer defined constraints,
meaning The test suite is no longer re-run with a static set of
input data each time. Instead, every continuous integration run
adds to the search space covered. Though generated at random,
tests are still reproducible as all configurations are based on
specific test seeds that can be used to re-run the test
with the exact same configuration.

Add to this randomising the runtime environment by executing tests
with various JVM versions and configurations,and you are bound
to find cases where your application runs into limitations and
bugs in the JVM.

This talk introduces randomised testing as a concept, shows examples
of how the Carrotsearch Randomised Testing framework helps
with making your test cases more interesting, and provides some
insight into how randomising your execution environment can help
save downstream users from surprises. All without putting too
much strain on your continuous integration resources.
