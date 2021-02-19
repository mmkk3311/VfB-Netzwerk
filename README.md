# VfB-Netzwerk
Prüfungsvorleistung WS 20/21

**Anleitung**  
In diesem Dokument zeigen Sie, dass Sie die Inhalte der Veranstaltung anwenden können. Dazu entwickeln Sie ein Codebuch, recherchieren eine Edge- und Nodelist, generieren ein igraph-Objekt, das sie anschließend visualisieren und interpretieren. Wir verwenden dafür die Bibliothek igraph. 

Bitte vergessen Sie die Reflexionsfragen am Ende der Datei nicht!

Sie sollten folgende Programmbibliotheken in R installiert haben:  
- rmarkdown  
- knitr
- tidyverse
- igraph  
- remedy  

 **Bearbeitungshinweise**  
- Bitte verwenden Sie diese und beantworten Sie die die Fragen in der Vorlage.   
- Achten Sie darauf, die Vorlage vollständig auszufüllen (auch den Header)  
- Speichern Sie die Vorlage mit folgenden Namen hdm123.rmd  
- Sie reichen nur diese Datei auf Moodle ein. Die weiteren Links sind in ihrem Markdown-Dokument angelegt.  

**Datenquellen**  
Bitte laden Sie Ihre Edge- und Nodelist auch auf Moodle oder verwenden ihren github account, beides ist möglich.  
- Edgelist  
- Nodelist  

**Codebuch**  
Bitte erstellen Sie ein two-mode Netzwerk (Mitgliedschaft in Organisationen). Deshalb brauchen Sie das Node-Attribut type, da es um Personen und Organisationen geht. Im Codebuch dürfen Attribute nur ein Wort haben (keine Sonderzeichen). Folgende Variablen müssen erhoben werden:

__Edgelist__:   
- from (id Person),  
- to (alle aktiven Mitgliedschaften der Person, soweit in dem Dokument recherchierbar, dazu gehört z.B. politische Partei, Unternehmen, Verbände, Vereine und weitere Organisationen). 

achten Sie darauf, dass alle ids auch genau so in der Nodelist auftauchen, dort aber nur ein Mal)    


__Nodelist__:    
(ich gebe nicht überall die Codierung vor, das ist Teil der Aufgabe, eine sinnvolle Codierung zu entwickeln.) Die folgenden Node-Attribute sind aber gesetzt:  
- id (identisch mit edgelist, aber hier nur einmalige Nennung)   
- type (0 = person, 1 = organization),  
- age (natürliche Zahlen oder Skalierung) 
- function (V = Vorstand, AR = Aufsichtsrat),  wird zu funktion
- representation (bezieht sich auf die Funktion innerhalb der VfB Gremien: Politik, Wirtschaft, Gewerkschaft, Umwelt, Sport, Wissenschaft, etc.),  
- position (Vorsitz, Stellvertreter, Mitglied in der VfB Organisation)  

**Datenquellen**
Die Daten für das Netzwerk finden Sie unter  
- Mitglieder der Kohlekommission [VfB Aufsichtsrat und Vorstand](https://www.vfb.de/de/1893/club/vfb-ag/organe-der-vfb-ag/): Primärquelle für das Netzwerk  
- Ergänzung der Personendaten durch Munzinger Archiv (ergänzend, Zugang über HdM-Netzwerk) oder eigene Recherche, falls notwendig. 


**Bitte löschen Sie vor Abgabe von hier bis auf den Header alles aus dem Dokument (einschließlich dieser Anleitung) und reichen nur ihr Projekt ein**
