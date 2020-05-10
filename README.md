# MALIS19WP9 - Aufgabe 1
Datenintensive und datenfokussierte Aktivitäten im eigenen Arbeitsalltag

Autor: Jan Coenen

## Inhaltsverzeichnis

> 1. Einleitung
> 2. Bibliothek
> 3. Archiv
> 4. Sammlung
> 5. Server
> 6. Umgang mit Daten und Einsatzpotenziale für Software
>> 6.1 Umgang mit Daten

>> 6.2 Einsatzpotenziale für Software
> 7. Fazit
> 8. Quellenverzeichnis

## 1. Einleitung
Innerhalb der Tätigkeit des Teams Information Management beim [International Paralympic Committee](https://www.paralympic.org) fallen in verschiedenen Bereichen datenintensive und datenfokussierte Aktivitäten an. Diese sind:

* Bibliothek
* Archiv
* Sammlung
* Server

In dieser Ausarbeitung sollen zunächst die einzelnen Aktivitäten in ihren jeweiligen Bereichen kurz erläutert werden. Im Anschluss werden mögliche Potenziale zur Vereinfachung von Arbeitsprozessen diskutiert, bevor ein kurzes Fazit die Arbeit abschließt.

## 2. Bibliothek
Datenintensive Tätigkeiten im Bereich der Bibliothek sind vor allem im Bereich der Katalogisierung zu verzeichnen. Diese geschieht momentan für jedes neu hinzugekommene Werk händisch. Ebenso wird momentan von Hand im Rahmen einer jährlichen Statistik erfasst, wie sich Nutzungsverhalten und Bestand der Bibliothek im verändert haben. Beide Prozesse sind stark repetitiv und könnten von Automatisierung oder Vereinfachung profitieren.

## 3. Archiv
Das Archiv des International Paralympic Committee besteht im Wesentlichen aus zwei Teilen, einem administrativen Zwischenarchiv sowie einem Organisationsarchiv. Das Zwischenarchiv besteht dabei aus Arbeitsunterlagen, die bis zum Ablauf ihrer jeweiligen Rückhalteperioden aufbewahrt werden müssen. Hierfür werden die Ordner momentan intellektuell erfasst und entsprechend in Exceltabellen abgelegt, mit einem jeweiligen Vermerk auf das Ende der Rückhaltefrist, zu dem eine endgültige Bewertung der Objekte durchgeführt wird. Diese Tabellen stellen also eine Art elektronisches Findbuch dar. Aufgrund der großen Menge an eingelagerten Objekten im Zwischenarchiv werden diese allerdings schnell unübersichtlich, so dass hier sicherlich eine Vereinfachung der Prozesse möglich wäre. Im eigentlichen Organisationsarchiv erfolgt die Erfassung, Verschlagwortung und Katalogisierung von Objekten momentan einzeln. Da hier allerdings häufig sehr viele gleiche Objekte anfallen, wäre es eine Überlegung wert, diese vielleicht gebündelt zu katalogisieren und entsprechende Formalia nicht wiederholt eingeben zu müssen. 
Für das Archivsystem ist in absehbarer Zeit die Umstellung auf ein Open Source-System geplant. Probleme bereitet hierbei momentan noch der Export der Datensätze, damit mit möglichst wenig Neueingewöhnung durch die Mitarbeiter das neue System sinnvoll genutzt werden kann.

## 4. Sammlung
In der historischen Sammlung erfolgt die Katalogisierung der Objekte ebenfalls von Hand. Hier ist es auch der Fall, dass häufig gleiche Objekttypen verarbeitet werden, so dass sich einheitliche Arbeitsschritte, die möglicherweise automatisiert werden könnten, herausbilden. 

## 5. Server
Die Arbeit am Server und der elektronischen Ablage auf der Serveroberfläche sind in den letzten Jahren verstärkt in den Fokus der Arbeit meiner Abteilung gerückt, vor allem vor dem Hintergrund des möglichen Umzugs von Teilen des Servers auf Sharepoint. Hierzu wäre vor allem nötig, dass Dokumente entsprechend indexiert werden, um später gut gefunden werden zu können, so wie Regeln dafür zu finden, wie mit Dokumenten auf dem Server umgegangen wird. Von besonderer Wichtigkeit ist hierbei der Medienserver. Versuche, eine historische Bilddatenbank mit vergangenen Veranstaltungen anzulegen, scheiterten bislang an der großen Datenmenge, die eine Indexierung von Hand nahezu unmöglich macht. Desweiteren liegen auf dem Server momentan Digitalisate von Archivgütern, die im Zuge einer Schutzdigitalisierung hinterlegt wurden und jetzt im Sinne der digitalen Langzeitarchivierung abgelegt werden sollen. Hierfür müssen vor allem die Metadaten der Dokumente entsprechend hinterlegt werden, was ebenfalls aufgrund der großen Anzahl individueller Dokumente, die sich allerding im Dokumententyp stark ähneln, bislang nicht erfolgt ist.

## 6. Umgang mit Daten und Einsatzpotenziale für Software

### 6.1 Umgang mit Daten
Wie bereits im vorherigen Abschnitt zu den einzelnen Abteilungen kurz angerissen, werden Daten in meiner Institution händisch, das heißt ohne weitere Automatisierung, verarbeitet. Für die Bibliothek, das Archiv sowie die Sammlung steht hierbei für Verschlagwortung und Katalogisierung mit AdLib, dem Vorgänger von [Axiell Collections](https://www.axiell.com/solutions/product/axiell-collections/) ein Sammlungsmanagementprogramm zur Verfügung. In diesem werden die formalen und inhaltlichen Metadaten der einzelnen Objekte nach intellektueller Erfassung durch den Bearbeitenden erfasst. Als Basis hierfür dient ein interner Thesaurus, der sowohl formale als auch inhaltliche Metadaten abdeckt. Hierbei handelt es sich um ein gewachsenes System. Da das Programm selber bereits sehr alt ist und in dieser Form nicht mehr durch den Hersteller unterstützt wird, wird momentan ein Umstieg auf alternative Sammlungs- und Bibliotheksmanagementsysteme wie etwa [Koha](https://koha-community.org/) oder auch [Collective Access](https://www.collectiveaccess.org/) erwogen.

Im Zwischenarchiv werden Excellisten als Findbücher für die nach Abteilungen geordneten Akten geführt, die wiederum nach nummerus currens aufgestellt sind. Aufgrund der weiterhin hohen Dichte an papierbasierten Akten und Unterlagen, sowie der gesetzlichen Rückhaltepflicht, die zur Aufbewahrung bestimmter Dokumente über Zeit verpflichtet, sind diese Findbücher für die adäquate Verwaltung unerlässlich. Nicht zuletzt geben Sie Aufschluss darüber, wann Akten zur Bewertung und also im Zweifelsfall zur Kassation freigegeben werden können. Die Excellisten selber werden bei der Erfassung der einzelnen Akten von Hand ausgefüllt.

Die Bildersammlung des International Paralympic Committee liegt momentan nur ungeordnet auf der Serveroberfläche vor. Jede Suche nach bestimmten Bildmaterialien setzt die Durchsicht großer Datenmengen durch die Bearbeitenden voraus.

### 6.2 Einsatzpotenziale für Software
Einsatzpotenziale für Software bieten sich für die Datenverarbeitung im genannten Arbeitsumfeld vor allem dort an, wo Prozesse, wie die Verschlagwortung und Einarbeitung von Metadaten für größere Datenmengen automatisiert werden können. Ein Beispiel wäre hier die Bildsammlung. 

Um aus der Bildsammlung eine Bilddatenbank zu erstellen, die sinnvoll zu nutzen ist, müssten die Bilder zunächst verschlagwortet werden. Für das Arbeitsumfeld im International Paralympic Committee bedeutet das vor allem, das jeweilige Ereignis, die dargestellten Handlungen oder Sportarten, sowie im besten Falle abgebildete Personen festzuhalten. Gerade die Erfassung des Ereignisses, zu dem das Bild aufgenommen wurde, ließe sich dabei vermutlich sehr gut automatisieren, da die Kriterien hierfür eindeutig sind. Neben dieser inhaltlichen Erfassung müssten ebenfalls noch technische Spezifikationen wie Auflösung oder Nutzungsrechte erfasst werden. All diesen Prozessen ist gemein, dass sie, aufgrund der hohen Anzahl an einzelnen Dateien, eigentlich nicht manuell durchgeführt werden können. Der Einsatz von Software würde es hier ermöglichen, große Datenmengen mit wenig Aufwand zu verschlagworten und also eine brauchbare Metadatenstruktur zu implementieren.

Ein weiteres Beispiel, wie Software eingesetzt werden könnte, wäre bei der Nutzung der Findbücher für das Zwischenarchiv. Hier werden bestimmte Regeln bei jedem neu erfassten Dokument angewandt. Es wird immer die jeweilige Rückhalteperiode eingegeben, es wird eine laufende Nummer vergeben und es werden der Titel des Dokuments sowie das Aufnahmedatum in das Zwischenarchiv, wie auch die Bearbeitenden, erfasst. In Anbetracht des Umstandes, dass häufig große Mengen an Dokumenten gleichen Typs bearbeitet werden, gestaltet sich die Arbeit repetitiv und eine Automatisierung oder der Einsatz von Software könnten die Bearbeitung deutlich beschleunigen. Zudem könnte über den Einsatz von Software die Wiedervorlage des jeweiligen Dokuments geregelt werden, sodass eine Durchsicht der Findbücher zu diesem Zweck bestenfalls entfällt.

Als letzter Punkt wäre, im Angesicht des Umzugs auf ein neues Bibliotheks- und Sammlungsprogramm, eine Softwarelösung sinnvoll, die den Ex- und Import von Datensätzen aus dem derzeitigen Programm in die neue Umgebung erleichtert. AdLib bietet zwar die Möglichkeit des Datenexports in xml- oder csv-Dateien, dieser gestaltet sich allerdings recht kompliziert. Die Möglichkeit zur Auslesung und Übertragung von Datensätzen würde einen reibungslosen Übergang zu neuen Systemen ermöglichen und die Arbeit der Abteilung erleichtern.

## 7. Fazit
Das gewählte Arbeitsumfeld bietet, wie anhand einiger Beispiele verdeutlicht werden konnte, mehrere Ansätze datenintensiver Arbeit, als auch viele Anwendungspotenziale für technische Lösungen. Gerade aufgrund stetig wachsender Datenmengen, die verarbeitet werden müssten, kommt eine manuelle Lösung dabei auch für einige Probleme oder Arbeitsfelder immer weniger in Frage. Sinnvoller Einsatz automatischer Lösungen sowie die bessere Verarbeitung von Daten würden dazu beitragen, Prozesse zu straffen oder auch, im Falle einer Bilddatenbank, die Sammlung und Zugänglichmachung von Informationen erst zu ermöglichen. Inwiefern alle hier vorgestellten Probleme tatsächlich so gelöst werden können, hängt dabei selbstverständlich von einem Praxisversuch ab.

## 8. Quellenverzeichnis
Alle Internetquellen wurden zuletzt am 10.05.2020 abgerufen.

* [International Paralympic Committee](https://www.paralympic.org)
* [Axiell Collections](https://www.axiell.com/solutions/product/axiell-collections/)
* [Koha](https://koha-community.org/)
* [Collective Access](https://www.collectiveaccess.org/)
