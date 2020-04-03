### Idee:
Zunächst jene abholen, die sich bisher gar nicht um Metadaten für ihre Forschungsdaten kümmern
Am besten einen einfachen, gangbaren Weg vorschlagen, Forschungsdaten mit möglichst informativen Metadaten zu versehen durch Beilegen einer Datei.
Langfristig wäre auch eine Softwarelösung zum Erstellen und Verwalten vorstellbar, aber zunächst: Keep it simple!

### Dateiformat:
einfache Textdatei, plain text, utf8, Key-Value-Paare

### Beispiel:
Title="Candle in the Wind"<br>
Subject="Diana, Princess of Wales"<br>
Date="1997"<br>
Creator="John, Elton"<br>
Type="sound"<br>
Description="Tribute to a dead princess"<br>
Relation="IsVersionOf Elton John's 1976 song Candle in the Wind"

### Standard/Vokabular:
Es gibt verschiedene Kandidaten, aus denen wir die Vokabulare für Keys (und evtl. Values) beziehen könnten und in deren Formate wir dann besonders einfach konvertieren könnten. Wobei Mappings zwischen den verschiedenen Standards auch nachträglich i.d.R. unproblematisch sein sollten.


#### Dublin Core:
weit verbreitet, deckt trotz übersichtlichem Vokabular vermutlich schon das Wichtigste ab
https://www.dublincore.org/specifications/dublin-core/dcmi-terms/
https://www.dublincore.org/specifications/dublin-core/usageguide/2001-04-12/generic/


#### DDI:
Data Documentation Initiative
http://www.dcc.ac.uk/resources/metadata-standards/ddi-data-documentation-initiative
hier gibt es ein verbreitetes Profil: CESSDA MLI - aktuell führen die Links dazu aber ins Leere

kontrollierte Vokabulare: https://ddialliance.org/controlled-vocabularies

#### CMDI:
Komponentenbasierte Metadaten, der CLARIN-Ansatz. Man könnte mittels vorhandener/ eigener Komponenten ein passendes Profil erstellen https://www.clarin.eu/content/component-metadata

Neben Registries für Komponenten (https://catalog.clarin.eu/ds/ComponentRegistry/) und Konzepte (https://concepts.clarin.eu/ccr/browser/) gibt es auch einen Online-Editor: http://clarino.uib.no/comedi/page
