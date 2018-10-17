# Tagebuch Richard Leikam

Datum      | Tätigkeiten                                                                                               | Dauer
---------- | --------------------------------------------------------------------------------------------------------- | -----
08.10.2018 | Erzeugung des Github Repositories, docsify in die GitHub-Pages integriert mit kurzer Anleitung            | 1:00
17.10.2018 | Schablone für Tagebuch erzeugt und in docsify integriert, README.md des GitHub-Repositories ausgearbeitet | 1:00

<script>
	let timeCells = document.querySelectorAll("#main > table > tbody > tr > td:last-child")
	
	let time = 0
	for (let cell of timeCells) {
		let components = cell.textContent.split(":")
		
		time += parseInt(components[0]*60)
		time += parseInt(components[1])
	}
	
	let tableBody = document.querySelector("#main > table > tbody")
	
	let totalTimeCellRow = document.createElement("tr")
	let totalTimeDescription = document.createElement("td")
	let totalTimeCell = document.createElement("td")
	
	totalTimeDescription.appendChild(document.createTextNode("Gesamtzeit"))
	
	let hours = time/60
	let minutes = time % 60
	if(minutes < 10) {
		minutes = "0" + minutes
	}
	totalTimeCell.appendChild(document.createTextNode(hours + ":" + minutes))
	
	tableBody.appendChild(totalTimeCellRow)
	totalTimeCellRow.appendChild(document.createElement("td"))
	totalTimeCellRow.appendChild(totalTimeDescription)
	totalTimeCellRow.appendChild(totalTimeCell)
</script>