# Datenportal der Metropolregion Rhein-Neckar



Die Funktionen:

[1. Suchfunktion](#suche) <br>
[2. Tags](#tags) <br>
[3. Datensätze](#dataset) <br>
[4. Ressourcen](#ressourcen) <br>
[4.1 Ressourcendownload](#download) <br>
[4.2 Ressourcenvorschau](#vorschau) <br>

### <a id="suche"></a> 1. Suchfunktion

   <img src="https://github.com/metropolregion-rhein-neckar/CKAN/blob/main/images/CKAN_Suche.png?raw=true" height="10%" width="80%">
   
Abbildung 1


Die Suche ist eine der zentralen Funktionen des Datenportals der Metropolregion Rhein Neckar.
Es existieren mehrere Möglichkeiten auf diese Funktion zuzugreifen. Sie können entweder eines der beiden Suchfenster auf der Startseite nutzen (s. Abbildung 1), oder Sie klicken auf den Reiter "Datensätze", wodurch Sie auf die eigentliche Benutzeroberfläche des Datenportals weitergeleitet werden (s. Abbildung 2).

<img src="https://github.com/metropolregion-rhein-neckar/CKAN/blob/main/images/CKAN_Filter.png?raw=true" height="10%" width="80%">

Abbildung 2



Hier besteht zusätzlich die Möglichkeit die Suchergebnisse über einen Filter weiter einzugrenzen. In Abbildung 2 werden bpsw. nur Datensätze des Metropolatlas angezeigt. Sie erkennen einen aktiven Filter daran, dass dieser grau hinterlegt ist. Entfernen können Sie diesen wieder, indem Sie auf das nebenstehende Kreuz klicken. Die weiteren möglichen Filter sind alle fortführend untereinander aufgelistet.

<img src="https://github.com/metropolregion-rhein-neckar/CKAN/blob/main/images/CKAN_Suchergebnis_1.PNG?raw=true" height="300" width="90%"> 

Abbildung 3

<img src="https://github.com/metropolregion-rhein-neckar/CKAN/blob/main/images/CKAN_Suchergebnis_2.PNG?raw=true" height="240" width="90%">

Abbildung 4

Die Suchfunktion des CKAN-Frameworks kann etwas verwirrend sein. Angenommen Sie möchten alle Datensätze zum Thema "Ladestationen" suchen. Dann ist die Suche in Abbildung 3 natürlich erfolgreich, aber eine Teilwortsuche wie in Abbildung 4 ist in den meisten Fällen nicht erfolgreich. Es wird empfohlen die Suchbegriffe genau auszuschreiben, oder auf die CKAN-API auszuweichen, welche eine wesentlich bessere Suchfunktion bietet.

### <a id="tags"></a>  2. Tags

<img src="https://github.com/metropolregion-rhein-neckar/CKAN/blob/main/images/CKAN_Tags.png?raw=true" height="10%" width="80%">

Abbildung 5

Wir benutzen im Datenportal Tags für die Kategorisierung der Datensätze. Sprich über Tags werden die einzelnen Datensätze übergeordneten Themen zugeordnet. Eine Auflistung aller vorhanden Tags finden Sie wie in Abbildung 5 zu sehen ist am linken Rand der Benutzeroberfläche. Tags fungieren auch gleichzeitig als Filter und können per klick aktiviert werden. So können Sie sich einfach alle Datensätze zu einem übergeordnetem Thema anzeigen lassen. In Abbildung 5 werden bspw. alle Datensätze zum Thema Lebensqualität angezeigt.


###  <a id="dataset"></a> 3. Datensätze
<img src="https://github.com/metropolregion-rhein-neckar/CKAN/blob/main/images/CKAN_Datensatz.png?raw=true" height="10%" width="80%">

Abbildung 6

Die einzelnen Datensätze enthalten eine kurze Beschreibung (1.) und zusätzliche Metadaten wie bspw. die Lizenz (2.) oder  Quelle (3.).


### <a id="ressourcen"></a>  4. Ressourcen

<img src="https://github.com/metropolregion-rhein-neckar/CKAN/blob/main/images/CKAN_Ressourcen.png?raw=true" height="10%" width="80%">

Abbildung 7

Generell ist jeder unserer Datensätze als WMS, CSV, GeoJSON und Geopackage verfügbar. Aufgrund lizenzrechtlicher Einschränkungen, ist es möglich, dass ein Datensatz auch nur als WMS verfügbar ist.
Durch einen Klick auf das gewünschte Format, werden Sie zu der entsprechenden Ressource weitergeleitet (s. Abbildung 8)

Einige wenige Datensätze sind nicht auf unserem Geoserver abgelegt, daher stehen diese nicht als WMS zu Verfügung.

#### <a id="download"></a>  4.1 Ressourcendownload

<img src="https://github.com/metropolregion-rhein-neckar/CKAN/blob/main/images/CKAN_Ressource.png?raw=true" height="10%" width="80%">

Abbildung 8

Über einen weiteren Klick auf die URL können Sie die gewünschte Ressource herunterladen. Für CSV-Dateien und Geopackages, startet der Download automatisch. Bei GeoJSONs werden sie weitergeleitet und es erscheint das GeoJSON im Rohformat in einem neuen Tab Ihres Browsers. Dieses müssten Sie dann mit strg+a und strg+c kopieren und in eine neue Datei mit strg+c einfügen. Die so erstellte Datei sollte mit der Endung .geojson abgespeichert werden.

#### <a id="vorschau"></a> 4.2 Ressourcenvorschau
<img src="https://github.com/metropolregion-rhein-neckar/CKAN/blob/main/images/CKAN_Ressourcen_Vorschau.PNG?raw=true" height="10%" width="80%">

Abbildung 9

CKAN ermöglicht eine Ressourcenvorschau (s. Abbildung 9). Diese funktioniert jedoch nur mit GeoJSONs und auch nur wenn der gewünschte Datensatz nicht zu viele Features enthält (zu groß ist). Also bitte nicht wundern, falls diese bei manchen Datensätzen nicht funktioniert.


