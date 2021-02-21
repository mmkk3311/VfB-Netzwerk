# Codebuch VfB-Netzwerk von Maren Krämer
Prüfungsvorleistung WS 20/21

Erhoben werden soll ein Two-Mode-Netzwerk der Führungspersönlichkeiten des VfB Stuttgart inklusive der vorhandenen Gremien (Vorstand, Aufsichtsrat, Präsidium, Vereinsbeirat). Zusätzlich werden alle aktiven Mitgliedschaften der Personen, soweit mithilfe der vorhandenen Quellen recherchierbar, erhoben (dazu gehört z.B. politische Partei, Unternehmen, Verbände, Vereine und weitere Organisationen). 

Achtung: da es zum Zeitpunkt der Erhebung (19.02) gerade zu Veränderungen in den Gremien kommt, sind manche Personen (Vogt und Adrion) gleichzeitig in zwei Gremien vorhanden.

**Edgelist**  

- from = id Person
- to = alle aktiven Mitgliedschaften der Person, soweit in dem Dokument recherchierbar (dazu gehört z.B. politische Partei, Unternehmen, Verbände, Vereine und weitere Organisationen)
- status = genauere Erklärung, inwiefern die Person mit der Organisation verbunden ist (dient der Übersicht, für Netzwerk unrelevant)

**Nodelist**

id (eindeutige ID der Person oder Organisation)
label (entspricht der ID, dient der Visualisierung in R (R nimmt Attribut label automatisch als Label an))
name (vollständiger Name der Person oder Organisation)

type (Einteilung in Person und Organisation)
- 0 = Person
- 1 = Organisation

age	(Alter der Person in Zahlenwerten; Organsationen haben hier ein NA)

funktion (Einteilung in Organe des VfB Stuttgart; function wurde ersetzt, damit sich Attribut nicht mit gleichnamigem Befehl in R überschneidet)
- 1 = Vorstand mit Mitgliedern
- 2 = Aufsichtsrat mit Mitgliedern
- 3 = Vereinsbeirat mit Mitgliedern
- 4 = Anderweitige Organisationen

folgende Attribute werden für die Netzwerkerstellung, - visualisierung und -analyse nicht benötigt und dienen nur der Vollständig- und Verständlichkeit der Daten:

representation (bezieht sich auf die Funktion innerhalb der VfB Gremien: Politik, Wirtschaft, Gewerkschaft, Umwelt, Sport, Wissenschaft, etc.)
position (Vorsitz, Stellvertreter, Mitglied in der VfB Organisation)  



