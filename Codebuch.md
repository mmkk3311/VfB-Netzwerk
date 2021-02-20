# Codebuch VfB-Netzwerk von Maren Krämer
Prüfungsvorleistung WS 20/21

Achtung: da es zum Zeitpunkt der Erhebung (19.02) gerade zu Veränderungen in den Gremien kommt, sind manche Personen (Vogt und Adrion) gleichzeitig in zwei Gremien vorhanden.

**Edgelist**  

- from = id Person
- to = alle aktiven Mitgliedschaften der Person, soweit in dem Dokument recherchierbar, dazu gehört z.B. politische Partei, Unternehmen, Verbände, Vereine und weitere Organisationen)

**Nodelist**

id (eindeutige ID der Person oder Organisation)

name (vollständiger Name der Person oder Organisation)

type (Einteilung in Person und Organisation)
- 0 = Person
- 1 = Organisation

age	(Alter der Person in Zahlenwerten; Organsiationen haben hier ein NA)

funktion (Einteilung in Organe des VfB Stuttgart)
- V = Vorstand
- AR = Aufsichtsrat	
- PR = Präsidium
- VB = Vereinsbeirat
- EP = Ehrenpräsident

representation (bezieht sich auf die Funktion innerhalb der VfB Gremien: Politik, Wirtschaft, Gewerkschaft, Umwelt, Sport, Wissenschaft, etc.)
- Codierung?

position (Vorsitz, Stellvertreter, Mitglied in der VfB Organisation)  
- Codierung?

