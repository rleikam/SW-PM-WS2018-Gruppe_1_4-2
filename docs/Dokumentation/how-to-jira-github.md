# How to Jira-GitHub

Die Jira-GitHub Integration ermöglicht es, das aktualisieren und referenzieren der Jira Issues anhand
von GitHub Branches, Pull-Requests und Commits. Somit werden Sachverhalte in GitHub auf das Jira-Projekt
übertragen.

[Referenzierung](https://confluence.atlassian.com/jirasoftwarecloud/referencing-issues-in-your-development-work-777002789.html)

## Smart Commits

Smart Commits sind einfache GitHub-Commits, die auf Jira Issues verweisen. Die Smart Commits sind mit einer einfachen Syntax ausgestattet,
so dass die Jira App auf GitHub die Informationen für die Jira Software verarbeiten und bereitstellen kann. Dabei hält ein Commit einen
so gennanten Issue Key um damit den jeweiligen Issue auf Jira zu referenzieren.  

Der Issue Key hat folgende Form:
 
KÜRZEL-NUMMER

* KÜRZEL - Stellt den Projektkürzel dar
* NUMMER - Das ist die Issue Nummer

Im Board und im Backlog ist der Issue Key für die einzelnen Issues einsehbar. Ein Beispiel für so einen Key ist z.B.
W2SP-11, der den Issue "GitHub: Links der Projektdokumente und Ausarbeitung umstrukturieren" vom Sprint KW44 darstellt.

### Syntax

Die Syntax von einem Smart Commit ist vereinfacht folgende:  

ISSUE_KEY #KOMMANDO #PARAMETER  

Eine Eingabe in die Commit-Nachricht mit solch einer Syntax, die semantisch valide ist, veranlasst die Jira App
die Nachricht für Jira zu verarbeiten.

### Kommandos

Es gibt 3 Kommandos, die in Smart Commits verwendet werden können. Diese sind Comment, Time und Transition.
Nachfolgend werden allerdings nur die Kommandos Comment und Transition mit jeweils einem Beispiel behandelt.
Die Beispiele nehmen dabei den Issue Key W2SP-11 an.

#### Comment

Das Kommando Comment veranlasst einen Kommentar im jeweiligen Jira Issue abzugeben.  

Beispiel: W2SP-11 #comment Problem A wurde gelöst.

#### Transition

Das Kommando Transition veranlasst die Jira Software, Issues auf verschiedene Zustände zu bewegen. Die Zustände und
Transitionen werden normalerweise durch einen Workflow bestimmt. In unserem Projekt wird dies durch das Board dargestellt.
Dabei stellen die Spalten im Board Zustände dar, die hier allerdings als Transition genutzt werden können. Dieser Kommando
muss mit einem Nachfolgenden Comment-Kommando und Comment-Text gefolgt werden.

Beispiel: W2SP-11 #laufend #comment Ausarbeitung angefangen.

### Sonstiges

Die Smart Commits lassen sich auch mit mehreren Kommandos ausstatten. Hier wird allerdings nicht darauf eingegangen.
Weiteres findet man im "Jira Smart Commits"-Link.

[Jira Smart Commits](https://confluence.atlassian.com/bitbucket/use-smart-commits-298979931.html#id-_smart_commits_commands1-transition)