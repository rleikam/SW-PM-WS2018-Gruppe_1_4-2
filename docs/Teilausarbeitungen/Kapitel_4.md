## Vorgehensmodelle

### Wasserfallmodell

Das **Wasserfallmodell** ist einst der einfachsten **Vorgehensmodelle** und hat als Ziel ein **Meilenstein** in jeder Phase des Projekts
zu haben das immer weiter aufeinander aufbaut. Um Probleme lösen zu können wird aber meist noch eine weiter Verbindung zu der Vorherigen
**Phase** gemacht damit man Test und andere Fehler besser finden und vermeiden kann. 

Dieses **Vorgehensmodell** kann viele Probleme kriegen wenn unerwartete Schwierigkeiten entstehen da es nicht leicht ist Ergebnisse alter
**Phasen** abzuändern und anzupassen.

### Spiralmodell

### Iteratives Vorgehen

Das **Spiralmodell** funktioniert über wiederholtes durchlaufen der **Entwicklungsphasen**, diese unterteilt man für gewöhnlich
in 4 Schritte

1. **Analyse** : In diesem Schritt werden die Vorrausetzungen, Anforderungen, Ziele und Vorstellungen an das Projekt festgehalten.
2. **Evaluierung** : In diesem Schritt werden die Lösungsidee und Umsetzungen untersucht um zu erkennen welche Risiken bestehen und
wie oder ob man sie vermindern kann.
3. **Realisierung** : In der Realisierung wird alles umgesetzt dazu gehört alles vom Feinentwurf und Codierung bis zur Integration
und den Tests.
4. **Planung** : Am ende von jeden Durchgang wird ein Review des Durchlaufs gemacht und der nächste Durchlauf wird geplant

### Inkrementelles Vorgehen

Häufig wird auch das **Inkrementelle Vorgehen** genutzt. Dieses **Vorgehen** funktioniert ebenfalls im **Spiralmodell** und ist ein
Grundaufbau eines Systems in dem immer mehr hinzugefügt wird und aufeinander aufgebaut wird. Bei diesem **Vorgehen** ist wichtig in
welchen abständen die einzelnen Ausbaustufen abgeschlossen werden. 

Häufig wird eine Kombination der beiden **Vorgänge** benutzt da Sie sich ähneln.

### Prototyping

**Prototypen** werden häufiger auch in Spiralform genutzt das heißt das im laufe der Entwicklung viele **Prototypen** entstehen.
**Prototypen** können dazu benutzt werden bestimmte Funktionen zu testen und diese dann auf- oder auszubauen(evolutionäres **Prototyping**).
Ebenfalls kann **Protoyping** benutzt werden um neue Optionen zu testen und zu vergleichen ob sie sich lohnen oder überhaupt realisierbar
sind (experimentelles **Prototyping**).

**Prototyp** Arten:

* **Demonstratoren**: Wird in den frühen **Phasen** benutzt und zeigen den ungefähren weg des Projekts an.
* **Labormuster**: Ist dazu da technische Fragestellungen beantworten zu können.
* **Pilotsysteme**: Kann bereits vom Nutzern getestet und bewertet werden und geht somit in Richtung Ziel.

**Prototyp** Muster:

* **Horizontal**: Demonstriert einen Ausschnitt des Endprogramms ohne auf andere **Ebenen** zu greifen(z.B Funktionale Eigenschaften
vorerst ignorieren und die Nutzeroberfläche demonstrieren).
* **Vertikal**: Nimmt einen Ausschnitt aus allen ebenen und deren Interaktion zum demonstrieren und kann somit auch Funktionalität
in Kombination demonstrieren.

**Rapid Prototyping**:  Moderne Werkzeuge lassen schnell **Prototypen** ohne Funktionalität erstellen und können somit auch schnelles
Feedback erzeugen.

Ein großer Vorteil an **Prototypen** ist das so früh Feedback von späteren Nutzern genutzt werden kann um das Projekt in eine gewünschte
Richtung zu leiten.

## Agile Methoden

**Agile Methoden** sollen sich mehr mit dem direkten Code-Inhalt einen Projekt beschäftigen die Grundideen des Konzept wurden im
"**Agilen Manifest**" geschrieben:

* Individuals and interactions over processes and tools
*  Working software over comprehensive documentation
* Customer collaboration over contract negotiation
* Responding to change over following a plan

In diesen Konzepten wird die Priorität des Vorgehens festgehalten.

Beispiele für Arten des **Agilen Vorgehens**:

* **Refactoring:** Anpassung des Codes um unnötige Teile zu entfernen oder um Übersichtlichkeit zu Verbessern. 
* **Pair Programming:** Ein Programm wird im Paar erstellt ein Programmierer programmiert der andere reviewt den Code.
* **Test-driven Development**: Die Entwicklung orientiert sich and zuvor erstellte Tests und Ziel ist es nur diese Tests ohne
Extras zu bestehen.
* **Continuous Integration:** Ziel ist es kontinuierliche weiterzuarbeiten und in kurzen abständen den neuen Teil zu Integrieren und
mit automatisierten Tests zu überprüfen.
* **Planning Game:** Ideen und Voraussetzungen werden Von Nutzern and die Entwickler geschickt die dazu dann schätzen ob es umsetzbar
ist und ob es sich lohnt es überhaupt umzusetzen.

Da ein **Agiles Vorgehen** dazu dient möglichst Variabel zu bleiben kann es zu Problemen bei Verträgen geben da diese gerne feste Werte
und Ziele einschließen wollen.

## Konkrete Methoden

### Scrum

Mit Scrum werden Projekte in sogenannte **Sprints** eingeteilt. Diese **Sprints** enthalten einen Teil Anforderungen an das Projekt.
Die gesamten Anforderungen an das Projekt kann der **Product Owner** oder auch **Projektleiter** im **Backlog** festhalten. Im laufe eines
Projektes werden immer mehrere **Sprints** gehalten die eine bestimmte Dauer haben die für das Projekt festgehalten werden
(für gewöhnlich 30 Tage). Für diesen **Sprint** wählt das Projektteam dann aus welche der Anforderungen sie in diesem **Sprint**
erledigen wollen.

Für gewöhnlich wird auch noch ein **Scrum-Master** eingesetzt. Er gehört nicht zum Team und mischt sich auch nicht in Kommunikation
von **Projektleiter** und **Projektteam** ein er soll nun dafür sorgen das **Scrum-Abläufe** eingehalten werden.

Nach jedem **Sprint** soll ebenfalls eine lauffähige Version der Software vorhanden sein die durch Hilfe des Kunden in Form von Reviews
auf Fehler und ähnlichem Aufmerksam machen soll. Das **Projektteam** soll am **Ende** eines **Sprint** den abgelaufenen **Sprint** in einer
Retrospektive bewerten und wird daraufhin im nächsten **Sprint** beachtet und dem **Scrum-Master** mitgeteilt.

### Rational Unified Process (RUP)

**RUP** folgt den folgenden drei **Grundprinzipen**:

- RUP ist anwendungsfallgetrieben
- Die Architektur steht im Zentrum der Planung
- Das Vorgehen zur Entwicklung ist inkrementell/iterativ

Um ein sogenanntes **RUP-Gebirge** zu erstellen müssen die **Phasen** auf der X-Achse und **Disziplinen** auf der y-Achse in ein
Koordinatensystem dargestellt werden. Durch diese Darstellung sieht man deutlich die Schwerpunkte der **Phasen** und die damit
verbundenen Tätigkeiten. 

![Ein RUP-Gebirge](Abbildungen/Nick_Friedrich/RUP-Gebirge.png)

​				**RUP-Gebirge** :Literatur Verzeichnis

**RUP** teilt das Projekt in folgende **Phasen** und **Meilensteine**:

- Inception / Lifecycle Objectives
- Eloboration / Lifecycle Archetecture
- Construction / Initial Operational Capability
- Transistion / Product Release

Die **Phasen** sind in folgende  **Disziplinen** unterteilt:

- Business Modeling
- Requirements
- Analysis & Design
- Implementation
- Test
- Deployment
- Configuration & Change Management
- Project Management
- Environment

### V-Modell XT

Man unterteilt das V-Modell XT in vier mögliche Projekttypen:

- **Systementwicklungprojekt (Auftragsgeber[AG])**
- **Systementwicklungprojekt (Auftragsnehmer[AN])**
- **Systementwicklungprojekt (Eigenentwicklung[AG/AN])**
- Einführung und Pflege eines organisationsspezifischen Vorgehensmodells (ORG)

Diese Projekttypen werden genutzt um die Rahmen des V-Modell XT festzulegen.

Die Rollen:

- **Projektleiter** verantwortlich für Projekthandbuch,Projektplan und Risikoliste und wirkt mit an den Anforderungen
- **Anforderungsanalytiker(AG)** verantwortlich für die Anforderungen
- **QS-Verantwortlicher** wirkt mit am Projektplan
- **Projektmanager** wirkt mit am Projekthandbuch

### Anpassung von Modellen

Die Anpassung von **Vorgehensmodellen** wird von vielen Unternehmen entwickelt die daraus entstehenden Modelle nennt man
organisationsspezifische **Vorgehensmodelle**. Diese **Vorgehensmodelle** befinden sich in einem durchgehenden **Verbesserungsprozess**.
Das wichtigste für solchen einen Prozess ist natürlich der Feedback der aus dem einzelnen Projekten in dem das Modell genutzt wird
entsteht. Wichtig für das Modell ist hierbei das der **Verbesserungsprozess** mit einbezogen werden muss. Damit ist gemeint das die
Ressourcen und das Personal das sich mit der Verbesserung beschäftigt beinhaltet werden muss um wirklich zu Überprüfen ob sich für das
Unternehmen lohnt. Um ein organisationsspezifisches **Vorgehensmodell** zu erstellen muss man die Projekt und Unternehmenssituation
berücksichtigen und möglicherweise auf besondere Wünsche von Kunden (z.B. bestimmte Nachweise) eingehen. Damit man solche Probleme
leichter lösen kann gibt es sogenannte **Prozessframeworks**.

### Prozessmanagement

Die **Vorgehensmodelle** haben wie Software ein **Lebenszyklus** und dieser lässt sich in folgende Schritte unterteilen.

1. **Analyse** : Anforderungen an den Gesamtprozess festlegen.
2. **Konzeption**: Bedingungen mit den Anwendern einigen.
3. **Realisierung**: Das Model aus 2. technisch umsetzen. 
4. **Einführung**: Das Modell/der Vorgang wird eingeführt.

Zusätzlich muss man die langfristige Strategie(Prozess-Landschaft) und die Projektinfrastruktur analysieren und planen. Auch die
Einführung-Strategien muss man separat festlegen und planen. Für die entstandenen Vorgehensmodelle muss man auch Schulungen vorbereiten
und planen. 
