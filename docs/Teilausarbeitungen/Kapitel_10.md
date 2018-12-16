## Metriken

Metriken dienen zur Beurteilung von Software, der Softwareentwicklung und von Softwareentwicklungsprozessen. Eine Metrik stellt dabei
eine Funktion dar, die eine Softwareeinheit auf eine Maßzahl abbildet. Man nutzt sie um z.B. die Leistungsfähigkeit von Software oder
auch um die Produktivität und Qualität der Softwareentwicklung und von Softwareentwicklungsteams zu beurteilen.

### Sichten auf Metriken

Metriken können in bestimmten Bereichen z.B. bei Produkten oder in Entwicklungsprozessen verwendet werden. Kunden werden sich mehr mit den
Metriken der Produkte einlassen, während Manager sich mehr für Metriken von Entwicklungsprozessen interessieren. Aus diesen und weiteren
Bereichen lassen sich nun Aspekte der Metriken bilden, die Sichten genannt werden. Jede Sicht besitzt dabei eine Vielzahl auf ihren
Bereich zugeschnittene Metriken. Es haben sich dabei die Sichten **Managementsicht** für Metriken wie Kundenzufriedenheit und Kosten,
die Entwicklersicht für Effizienz und Wartbarkeit und die Kundensicht für Metriken der Termintreue und Kosteneinhaltung etabliert. Es
existieren noch weitere Metriken dieser Bereiche.

### Metriken bei Software und Softwareprozessen

Die Wahl der Metriken fällt immer mit den Aspekten von Software und Prozessen einher. Bei Software sind zum Beispiel Aspekte, wie Umfang
und Leistung, Komplexität und Effizienz zu untersuchen und bei Prozessen Aspekte wie Produktivität, Effektivität und Kommunikationsintensität.
Da diese Aspekte alle nicht sehr einfach zu messen sind, wählt man einfache Metriken. Mit der Metrik **Lines of Code (LOC)** beispielsweise
lässt sich die Anzahl der Codezeilen von Programmen messen. Vergleiche werden durch verschiedene Versionen von Programmiersprachen oder
verschiedener Programmkonstrukte, wie Methoden gemessen und analysiert. Selbstverständlich ist es möglich ein Problem durch Programme
mit verschiedener Programmzeilenlänge zu lösen, was die Aussagekraft von LOC anzweifelt. Die Metrik LOC wird allerdings trotzdem oft verwendet
um z.B. die Produktivität einer Softwareentwicklung zu bestimmten. Dabei werden Lines of Code pro Personentag zum Vergleich gemessen.
Mit Werkzeugen lassen sich mehrere Sätze von Metriken berechnen und darstellen um Schwachpunkte zu identifizieren.
Anhand von Erfahrungsdaten, die durch das Sammeln von Kennzahlen von entsprechenden Statistiken gewonnen wurden, die in entsprechende
Werkzeuge eingeführt werden, lassen sich Aussagen über die Situation und die Veränderung der Softwareentwicklung treffen.

### Beispiele für Metriken

In **Produktmetriken** werden die Produkte anhand von Eigenschaften, wie Umfang, Komplexität, Design und Performanz beschrieben.
Hierunter fällt zum Beispiel auch das bereits erwähnte LOC. Eine gebräuchliche Metrik ist die **Mean Time To Failure (MTTF)**,
mit der die mittlere Lebensdauer bis zum Ausfall eines Produktes beschrieben wird. Auch fällt hier die McCabe-Metrik, die auch als
zyklomatische Komplexität bekannt ist, mit der man die Komplexität eines Softwareteils durch Kontrollflussgraphen bestimmen kann.  

Mit **Prozessmetriken** kann die Leistung und Reife von Entwicklungsprozessen beschrieben werden. Somit kann die Projektfähigkeit
eines Unternehmens aus der Sicht von Softwareprozessen festgestellt werden. Abhängig vom Vorgehensmodell werden Kennzahlen, wie
der Zeitbedarf für Fehlerkorrekturen und Einarbeitung von Änderungen sowie die Prozessreife gewählt. Es gibt teilweise Überschneidungen
mit den Projektmetriken. Diese nennt man dann speziell **In-Process Quality Metric**.

Bei **Projektmetriken** nutzt man die Termintreue, Kosten- und Ressourcenverbrauch und die Produktivität als Beschreibung von Metriken.
Die Projektmetriken werden für **Soll-Ist-Analysen** im Projektmangagement verwendet um damit Steuerungsmaßnahmen zu treffen.

### Erfassen und Auswerten von Metriken

Das Erfassen und Auswerten von Metriken muss in Projekten untersucht werden. Dazu muss nach der Art der Metrik bzw. der Weg zur Metrik
mit dem jeweiligen Messverfahren, und der Festlegung von daraus ableitbaren Aussagen untersucht werden. Dafür existiert ein bereits 
ein bewährter Ansatz, der **Goal-Question-Metric (GQM)**. Das GQM ist eine Methode zur Planung und Durchführung von zielorientierten Messungen.
Dabei geht der GQM von **Messzielen** und weiteren Informationen aus um damit Metriken für **Fragestellungen** abzuleiten. Dabei wird hierarchisch
eine Struktur aufgebaut, auf dessen erster Ebene die Ziele stehen. In den darauffolgenden Ebenen werden Fragen gestellt und immer weiter
ebenenweise verfeinert bis zu einer Ebene auf der Metriken definiert sind. Die Auswertung folgt dann von Bottom-Up dieser Struktur, also
angefangen bei den Metriken. Der Vorteil liegt dabei auf dieser schrittweisen Vorgehensweise, so dass man nur im Sinne der Messziele
Metriken definiert und gemessen wird.

<div style="text-align:center"> 
	<img src="/../Abbildungen/Richard_Leikam/Kapitel_10_Goal-Question-Metric.png">
	<div><b>Die Abbildung zeigt den GQM-Ansatz mit einem Ziel, mehreren Fragen bezogen auf das Ziel und einzelner Metriken.</b></div>
</div>	