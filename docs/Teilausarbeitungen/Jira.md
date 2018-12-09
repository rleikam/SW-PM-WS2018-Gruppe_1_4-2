# Jira

## Einleitung

Jira ist eine von Atlassian entwickelte Webanwendung für das Projektmanagement überwiegend für Softwareprojekte [[Wikipedia Jira][WP-Jira]].
Mit Jira lassen sich Aufgaben, Anforderungen und Prozesse von ein oder mehreren Projekten planen, verwalten und überwachen. 
Es unterstützt insbesondere agile Ansätze, wie Scrum und Kanban. Desweiteren lassen sich auch Rollen und Gruppen
mit Zugriffsberechitgungen für die Mitglieder von Jira Projekten erstellen. Mit Apps vom Jira Marketplace, wie einer GitHub-Jira
Integration und weiteren Atlassian Anwendungen, wie Confluence lässt sich die bereitgestellte Plattform für die Projekte entsprechend
erweitern.

## Projekte

Die Jira Webanwendung ermöglicht das Erzeugen von verschiedenen Jira Projekten. Dabei können die Projekte unterschiedlich konfiguriert
sein z.B. hinsichtlich des Vorgehensmodell oder des Workflows. Beim Erstellen eines Projekts lässt sich dieses bereits mit einer
**Vorlage** konfigurieren. Als Vorlage kann man die bekannten Vorgehensmodelle Scrum oder Kanban wählen. Es gibt auch weitere Vorlagen,
wie z.B. für einfaches Projektmanagement zum Verfolgen von Aktivitäten, für das Verfolgen von Tasks aber auch wie Material-
oder Personalbeschaffung. Diese Vorlagen zählen zu den sogenannten **klassischen Projekt** von Jira. Es gibt auch für Teams mit weniger
Erfahrung die sogenannten **Next-Gen Projekte**, die einen einfachen Einstieg in Jira ohne eine komplizierte Konfiguration ermöglichen.
Je nach der ausgewählten Projektvorlage ist das Jira Projekt eingerichtet und bereit zur Nutzung.

![Jira Klassische Projekte](/../Abbildungen/Richard_Leikam/Jira_Klassische_Projekte.png)
Der Ausschnitt zeigt eine Teilmenge der Vorlagen für eine Projektkonfiguration in Jira.

## Issues

Issues stellen in gewisser Weise einen Abstraktionsbegriff in Jira dar. Unter einem Issue versteht man in Jira verschiedenes.
Ein Issue kann z.B. eine Aufgabe, Bugfix, Feature oder eine andere Art von Sachverhalt darstellen. Der genaue Sachverhalt wird mit dem
**Issue Typ** klassifiziert. In Jira gibt es standardmäßige Issues z.B. Task, Story oder Bug. Zu jedem Issue Typ existiert eine Vielzahl
an **Feldern**, die Merkmale eines Issue Typs beschreiben. Würde man beispielsweise eine Aufgabe mit einem Issue vom Typ Task beschreiben,
dann könnte die Ausprägung eines solchen Issue Typs mit konkret ausgefüllten Feldern für die Aufgabenbeschreibung, der Priorität, einer
Deadline und dem Namen eines Beauftragen, der die Aufgabe erledigen soll instanziiert werden. In Jira lassen sich eigene Issue Typen mit
deren dazugehörigen Feldern definieren.

## Workflows

Die Workflows in Jira beschreiben Zustände und Transitionen von Issues. Das heißt, dass einem Issue ein gewisser Lebenszyklus zugeschrieben
wird und innerhalb dessen zwischen einzelnen Zuständen gesprungen wird. Ein Issue darf dabei immer nur in einem Zustand bleiben. Um von einem
Zustand x zu einem anderen Zustand y zu gelangen muss dafür eine Transition von Zustand x nach Zustand y definiert werden. Die Transitionen
sind dabei nur unidirektional. Jira gibt schon ein standardmäßigen Workflow vor. Dieser lässt sich nicht modifizieren, aber dafür kopieren
und Modifikationen können dann darüber stattfinden [[Jira Workflows][Jira-Workflows]]. Um für bestimmte Issue Typen einen Workflow zuzuweisen muss ein **Workflow Schemata** her,
dass Abbildungen von mehreren Workflows mit Issues Typen schafft. Dabei dürfen einzelne Workflows im Schemata auf mehrere Issue Typen
verweisen [[Jira Workflow Schemata][Jira-Workflow-Schemata]].

![Jira Workflow](https://confluence.atlassian.com/adminjiraserver072/files/828787890/828787899/1/1456788407758/JIRA+Workflow.png)
Ein Standard Workflow in Jira mit seinen Zuständen und Transitionen[[Jira Workflow Abbild][Jira-Workflows]].

## Boards

Boards zeigen Issues von einem oder mehreren Projekten an. Mit ihnen werden einzelne Issues verwaltet. Innerhalb eines Jira Projekts dürfen
mehrere Boards existieren. In Jira gibt es drei unterschiedliche Typen von Boards nämlich das Scrum Board, das Kanban Board und das
Next-gen Board. Auf einem Scrum Board gibt es grundlegend zwei Bereiche, einmal der **Backlog** und einmal der **Sprint Backlog**.
Im Scrum Backlog werden sämtliche Issues verwaltet, während in einem Sprint Backlog die Issues für einen Scrum Sprint vorbereitet werden.
Aktive Sprints werden als Board mit Spalten dargestellt. Auf einem Kanban Board ist es ähnlich wie auf einem
Scrum Board. Es existiert ein typisches Kanban Board, bei der in der ersten Spalte, also die Backlog Spalte, sämtliche Issues hinzugefügt
werden. Optional lässt sich ein weiteres Backlog aktivieren, in der sämtliche Issues enthalten sind, damit die Backlog Spalte nicht zu
unübersichtlich wird. Kanban Boards werden generell als Board mit Spalten dargestellt. Next-gen Boards basieren auf Scrum- und Kanban Boards,
die wesentlich einfacher und flexibler sind [[Jira Boards][Jira-Boards]].

![Jira Board](https://confluence.atlassian.com/jirasoftwarecloud/files/946023490/946023491/1/1519281781266/Scrum+board.png)
Ein Scrum Board mit seinen jeweiligen Spalten und Issues [[Jira Board Abbild][Jira-Boards]].

## Berichte

Berichte erlauben es, den Projektfortschritt durch Versionen, Epics, Sprints und Issues zu verfolgen und zu analysieren. Je nach Projekttyp
existieren unterschiedliche Diagramme, die durch die entsprechenden Information eine Visualisierung darstellen. Für Scrum Projekte ist
zum Beispiel das Burnup-Diagramm interessant, dass die Arbeit innerhalb eines Sprints in Bezug zur gesamten Arbeit des Sprints anhand
von Storypunkten der Issues im Zeitraum des Sprints vergleicht oder der Velocity-Bericht der anhand von Storypunkten für jeden Sprint anzeigt,
wie viel Arbeit in einem Sprint vorhanden war und wie viel davon abgearbeitet wurde. 

[WP-Jira]: https://de.wikipedia.org/wiki/Jira_(Software)
[Jira-Workflows]: https://confluence.atlassian.com/adminjiraserver072/working-with-workflows-828787890.html
[Jira-Workflow-Schemata]: https://confluence.atlassian.com/adminjiraserver073/configuring-workflow-schemes-861253569.html
[Jira-Boards]: https://confluence.atlassian.com/jirasoftwarecloud/what-is-a-board-764477964.html