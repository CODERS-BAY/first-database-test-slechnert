# DB-Test
## Aufgabe 1
Stelle Entitäten mittels Chen-Notation und Min,Max Notation dar.
Wähle ein sinnvolles Beispiel!

## Aufgabe 2
Kann eine Beziehung Attribute haben?
JA

Wenn ja, wie stelle ich es im ERD dar?
Als Rechteck von der Beziehung weg, oder Assoziativtabelle.

## Aufgabe 3
Welche Codd'schen Anforderungen gibt es (Nenne mindestens 5)
Benutzersichten
Datensicherungen
Integration
Integritätssicherung
Katalog
Operationen
Synchronisation
Transaktionen
Zugriffskontrollen

## Aufgabe 4
Nenne den Unterschied zwischen Konzeptuellen und Logischem Schema
Konzeptuel gibt Relation zwischen einzelnen Entitäten an, logisches zwischen allen.

## Aufgabe 5
Welche 3 Bestandteile gibt es im Entity Relationship Model
Entitäten, Attribute und Beziehungen

## Aufgabe 6
Welche Datentypen gibt es in MySQL? (Nenne mindestens 5)
smallint
int
bigint
varchar
date
timestamp
boolean

## Aufgabe 7
Welche Arten von Schlüsseln gibt es und welche Eigenschaften besitzen diese?
Primärschlüssel - zur eindeutigen Identifikation einer Entität
Sekundärschlüssel - zur eindeutigen Zuordnung einer Entität zu einer anderen Entität
Schlüsselkandidaten - potentielle Schlüssel die einer eigenen Entität zugeordnet werden sollten

## Aufgabe 8
Welche Arten von Beziehungen gibt es? Zeichne für jede ein Beispiel auf

## Aufgabe 9
Was bedeutet der Begriff Kardinalität und welche Kardinalitäten gibt es?
Beschreibt die Anzahl einer Entität in einer Relation näher.
1:1
1:N
N:1
N:M (Sollte mittels Entität oder Assoziativtabelle aufgelöst werden)

## Aufgabe 10
Was bedeutet der Begriff Datenintegrität und worin unterscheidet sich Integrität und referentielle Integrität?
Integrität bedeutet Richtigkeit der Daten, referentielle Integrität beschreibt die Richtigkeit der Beziehung von Daten zueinander.

## Aufgabe 11
Erkläre die 3 Normalformen
1NF: Atomare Aufteilung - in kleinstmögliche, sinnvolle Bestandteile spalten.
2NF: 1NF + Jeder Nicht-Schlüsselkandidat muss von einem Schlüssel abhängig sein.
3NF: 2NF + Keine direkte oder transitive Abhängigkeit von Nicht-Schlüsselkandidaten zueinander.

## Aufgabe 12
Erkläre den Unterschied zwischen starken und Schwachen Entitäten und erstelle ein Beispiel.
Starke Entitäten können alleine existieren, schwache Entitäten sind abhängig von starken Entitäten.
Flugzeug - FlugzeugTyp. Flugzeuge können alleine bestehen, FlugzeugTyp mit Attributen wie Modell, maxSitzkapazität und maxReichweite, sind eine Auslagerung der Flugzeug-Attribute und somit von der Entität "Flugzeug" abhänig.

## Aufgabe 13
Welche Grundregeln gibt es im Relationenmodell? (Nenne mindestens 4)
Es sollten so wenige Primärschlüssel wie möglich verwendet werden.
Bei Bedarf nutze einen Surrogate Key.
Vermeide Anomalien.
Vermeide Redundanzen.
Gib dir Mühe, es vereinfacht die Implementierung.
Farben machen das Leben schöner.
Nutze eindeutige Relationsbezeichnungen. (nicht z.B. "has" o.Ä.)

## Aufgabe 14
Wie löst man eine M:N Beziehung auf? Erstelle ein Beispiel

## Aufgabe 15
Ein Handelsbetrieb verkauft ein Sortiment von Artikeln, die er von verschiedenen Herstellern bezieht. Der Handelsbetrieb hat einen bestimmten Kundenkreis, der regelmäßig Bestellungen aufgibt. Eine Bestellung kann mehrere Artikel umfassen. Ein Artikel kann von mehreren Lieferanten bezogen werden und ein Lieferant liefert natürlich meist mehr als einen Artikel. Erstelle ein ERD und ein Relationenmodell, welches der 3. Normalform entspricht.

## Aufgabe 16
Welche Anomalien kennst du und was beschreiben sie?
Insert Anomaly - Fehler bei der Eingabe/ beim Speichern von Daten.
Update Anomaly - Fehler beim Editieren von Einträgen.
Delete Anomaly - Fehler beim Löschen von Einträgen.

## Aufgabe 17
Modellieren Sie den angeführten Realitätsausschnitt einer Fluggesellschaft mit Hilfe eines Entity Relationship- Diagramms. Treffen Sie, falls notwendig, sinnvolle Annahmen und dokumentieren Sie diese nachvollziehbar in Ihrer Lösung. Der zu betrachtende Realitätsausschnitt der Fluggesellschaft umfasst folgenden
Sachverhalt:
Flughäfen haben ein Kürzel (= Schlüssel) und gehören zu einer Stadt (z.B. „FRA“ für Frankfurt, „FCO“ für Roma Fiumicino).
Flüge haben eine Flugnummer (z.B. „LH 306“), führen von einem Flughafen zu einem anderen, mit jeweils einer festen Abflugs- und Ankunftszeit (z.B. ab Frankfurt um 07:30 nach Roma Fiumicino mit Ankunft um 09:15).
Jeder Flugzeugtyp hat einen Namen (z.B. „747-400“) und eine Sitzanzahl (z.B. 430 Sitze).
Piloten haben einen Namen (z.B. „Meier“), ein Geburtsdatum (z.B. „1.1.1960“) und eine Berechtigung, bestimmte Flugzeugtypen zu fliegen (z.B. „747-400“ und „A310“).
Jedes einzelne Flugzeug ist von einem bestimmten Flugzeugtyp (z.B. „747-400“) und hat einen Namen (z.B. „Mozart“).
Bei einem Flug-Einsatz wird ein Flug (z.B. „LH 306“) an einem bestimmten Datum (z.B. „6.2.2011“) von einem bestimmten Piloten (z.B. „Meier“) mit einem bestimmten Flugzeug (z.B. „Mozart“) geflogen.
Bilden Sie das konzeptuelle Schema in ein relationales Schema ab. Das relationale Schema soll der 3. Normalform genügen


[Aufgabe 1, 8 und 14](1_8_14.jpeg) <br>
[Aufgabe 15](15.jpeg) <br>
[Aufgabe 17](17.jpeg)
