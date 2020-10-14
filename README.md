FOSS-Konzept Grün-Rot München 2020
==================================

<!-- 
Wenn wir am Anfang des Konzeptes sagen, welche Ziele mit dem Konzept verfolgt werden, dann kann der Rest davon abgeleitet werden. Mir ist klar, dass der Anstoß aus der Koalitionsvereinbarung kommt, aber es gab ja sicher Gründe, warum FOSS dort drin steht. Im besten Fall sind die deckungsgleich zu den Zielen, falls nicht dann bitte ergänzen.
-->
## Ziele des FOSS-Konzeptes

1. Nach dem Motto "public money, public code", sollen möglichst viele Bürger*innen von den Investitionen der Landeshauptstadt München in die Softwareentwicklung profitieren.
2. Vendor lock in soll vermieden werden
3. ...


## FOSS in der Koalitionsvereinbarung


<!--- 
Hier entsteht das Free and Open Source-Software-Konzept der grün-roten Regierungskoalition im Münchner Rathaus.
Wir freuen uns über Eure Teilnahme und Euer Feedback!
-->

Die [Koalitionsvereinbarung für die Stadtratsperiode 2020 –2026 zwischen Oberbürgermeister Dieter Reiter, den Münchner Parteien SPD und Die Grünen, der Stadtratsfraktion Die Grünen–Rosa Liste und der Fraktionsgemeinschaft SPD/Volt](https://www.gruene-muenchen.de/wp-content/uploads/2020/04/Druckfassung_Koalitionsvertrag-2020_2026.pdf) nennt unter dem Abschnitt "XII.Digitalisierung als Chance" folgende Punkte:

> Wo immer technisch und finanziell möglich setzt die Stadt auf offene Standards und freie Open Source-lizenzierte Software und vermeidet damit absehbare Herstellerabhängigkeiten. Diese Abwägung nehmen wir als Kriterium für Ausschreibungen mit auf, eine Abweichung von diesem Grundsatz muss begründet werden. Die Stadt unterhält ein öffentlich zugängliches Open Source Dashboard inkl. Kostenbilanz (auch bei Betriebssystemen und Office-Anwendungen), aus dem hervorgeht, in welchen Bereichen die Landeshauptstadt München auf Open Source setzt und welche Fortschritte in diesem Bereich gemacht wurden.

> Es gilt im Hoheitsbereich grundsätzlich das Prinzip “public money, public code”. Das heißt: Sofern keine personenbezogenen oder vertrauliche Daten enthalten sind, wird auch der Quellcode städtischer Software veröffentlicht. Die Stadt München unterstützt die Entwicklung von Open Source-Projekten mit einem "Munich Open Source Sabbatical". Professionelle Programmierer*innen, die sich für drei oder sechs Monate ganz auf die Fortentwicklung eines Open Source-Projektes konzentrieren möchten, können sich dafür auf ein städtisches bezahltes Stipendium bewerben. Die Projekte müssen einen kommunalen Nutzen haben.

Dieses Konzept definiert [Free Open Source Software](https://de.wikipedia.org/wiki/Free/Libre_Open_Source_Software) (FOSS) für die Landeshauptstadt München auf Basis des Koalitionsvertrags.
Es definiert Voraussetzungen, Abhängigkeiten, Ausschlüsse und Zielrichtung von Entwicklung, Beschaffung und Betrieb von OpenSource Software.

## Offene Standards als Basis
Die Softwareprodukte, die in der Landeshauptstadt München verwendet werden, sind miteinander vernetzt. Zudem werden zwischen der LHM und anderen Behörden Daten ausgetauscht. Deshalb ist es wichtig neben FOSS auch auf offene Standards zu setzen. 

### Dokumentstandards
In einer Behörde sind sehr viele Prozesse Dokumenten orientiert. Deshalb sollen offene und damit von allen verwendbare Dokumentformate verwendet werden. Dies sind in der Regel Formate, deren Spezifikation von offenen Standardisierungsorganisationen betreut werden (z.B. PDF von der PDF Association), oder die entsprechen normiert sind (beispielsweise das Open document format nach  ISO/IEC 26300).

### Austatuschformate
Die Landeshauptstadt München tauscht regelmäßig Daten mit anderen Behörden aus. Hier ist es wichtig, dass diese Daten medienbruchfrei und automatisiert verarbeitet werden können. Für behördliche Spezialthemen (z.B. Einwohnermeldewesen, oder Ausländerwesen) gibt es hier standardisierte Austauschformate wie den XÖV (https://www.xoev.de/). Die Nutzung ist der XÖV Formate ist häufig vom Gesetzgeber vorgeschrieben (z.B. im Bundesmeldegesetzt). Darüber hinaus sollen auch in anderen Bereichen offene Austauschformate verwendet werden, wenn solche vorhanden sind.

### Standadrisierte Protokolle
Um eine optimale Kommunikation innerhalb der Anwendungslandschaft zu gewährleisten, sollen die verwendeten Software Produkte ihre Schnittstellen über standardisierte und offene Protokolle zur Verfügung stellen. Solche Protokolle werden in der Regel von einer Standardisierungsorganisation (z.B. HTTP vom World Wide Web Consortium W3C) normiert und finden eine weite Verbreitung in der IT Community.

## Verwendung von FOSS in der LHM
<!-- Die Geschäftsmodelle sind ein übergeordnetes Thema, das praktisch für alle Bereiche gilt. Eingeschränkt auch für die Eigenentwicklung. Deshalb habe ich das mal ganz nach oben gesetzt. -->
Bei der Verwendung von Software und Hardware sollen Lösungen aus dem OpenSource Umfeld präferiert werden.
Dies schließt zahlreiche [Geschäftsmodelle für Open-Source-Software](https://de.wikipedia.org/wiki/Gesch%C3%A4ftsmodelle_f%C3%BCr_Open-Source-Software#Ans%C3%A4tze) mit ein: 

* es werden __Supportverträge__ für genutzte OpenSource Software beschafft (z.B. RedHat RHEL)
* es werden __Beratungsleistungen__ zur Einführung, Betrieb und Weiterentwicklung von OpenSource Software beschafft.
* es werden auch __Lizenzen__ für dual-lizenzierte __proprietäre Erweiterungen__ von Software beschafft, deren freie Versionen bereits im Einsatz sind und deren relevanter Teil quelloffen ist (z.B. GitLab).

Die Landeshauptstadt München beschafft so professionelle Softwarelösungen, ohne sich mit der benutzten Software in eine Herstellerabhängekeit zu begeben.
So können Leistungen jederzeit neu ausgeschrieben und bestmöglich am Markt vergeben werden.

### Client-Betriebssysteme und Office-Anwendungen
<!-- Habe ich als Punkt übernommen - finde es aber schwierig hier etwas darüber zu schreiben, nachdem gerade Libre Office und Linux - mit nicht unerheblichem Aufwand - durch MS Office und Windows ersetzt wird. -->

### Beschaffung von kommunaler Software
<!-- Ich würde das getrennt von anderen Beschaffungen sehen, da es aus meiner Sicht schwierig sein wird, auf dem kommunalesn Software Mart FOSS Produkte zu finden. -->

### Beschaffung von nicht kommunaler Software
Die Landeshauptstadt München verwendet auch Software, die nicht auf den Einsatz in einer Behörde beschränkt sind. Beispielweise GIT in der Softwareentwicklung, Serverbetriebssysteme im Anwendungsbetrieb, oder auch Videokonferenz Software. Hier sind die Möglichkeiten leistungsfähige FOSS Produkte auf dem Markt zu finden - auch in Kombination mit den oben genannten Geschäftsmodellen - deutlich höher, als bei kommunaler Spezialsoftware. Deshalb soll bei jeder Ausschreibung oder auch bei Abruf aus einem Rahmenvertrag, geprüft werden, ob es für den Einsatzzweck ein FOSS Produkt gibt und begründet werden, wenn dieses nicht verwendet wird.  

### Softwareentwicklung
Neben der Nutzung von Standartsoftware Produkten, wird bei der LHM auch Software entwickelt. Hierbei sollen durchgängig (sowohl im Front, als auch im Backend) Open-Source Bibliotheken mit einer möglicht liberalen Lizenz (beispielsweise Apache Licence) verwendet werden. Das gilt unabhängig davon, ob die Software von Mitarbeitern der Stadt München, oder einem Dienstleister im Auftrag entwickelt wird.

Wenn innerhalb der Individualsoftwareentwicklung technische Anbhängigkeiten zu Drittsystemen entstehen, dann soll darauf geachtet werden, dass es sich hierbei um Produkte handelt, die unter OSS Lizenz verfügbar sind. Solche Systeme können beispielsweise ein Datenbank Management System, Suchmaschine oder ein Authentifizierungs Server sein.  

## Die LHM als Anbieter von FOSS
Grundsätzlich sollte es für die meisten fachlichen Probleme eine Anwendung auf dem kommunalen Software Markt geben. Oft ist es allerdings so, dass die Landeshauptstadt München alleine aufgrund ihrer Größe für Proleme eine IT Lösung benötigt, die andere Kommunen mit einer Tabellenkalkulation lösen. Deshalb tritt die Stadtverwaltung regelmäßig als Software Hersteller auf.

Getreu dem Motto "public money, public code", soll der Source Code für Eigenentwicklungen öffentlich zugänglich gemacht werden. Dies geschieht in der Regel über ein öffentliches Source Code Repository. Ob dies von der Landeshauptstadt München selbst betrieben, oder ein öffentliches Repository wie Github verwendet wird, ist unerheblich. Wichtig ist, dass die Entwicklung aktiv innerhalb des Repositories statt findet und nicht von Zeit zu Zeit Code-Stände von innen nach außen kopiert werden. 

### Produkt vs. Projektarbeit
Wenn eine Softwareanwendung in Form von FOSS angeboten wird, so ist das für externe Personen wie ein Produkt. Innerhalb der LHM wird aber in der Regel in Form von Projekten gearbeitet. Die beiden unterscheiden sich vor allem darin, dass bei einem Projekt versucht wird, das definierte Ende einzuhalten, während bei einem Produkt alles getan wird, um das unbekannte Ende möglichst spät zu erreichen. Wenn die Landeshauptstadt München nun als FOSS Anbieter auftritt, so ist es wichtig, dass sie sich als Produkthersteller sieht (und auch so verhält). Das heißt sie sich nach einer anfänglichen Projektphase so in der Pflege und Weiterentwicklung der Software engagiert, dass es von außen als aktiv gepflegtes Open Source Projekt zu erkennen ist. Das ist wichtig für die Akzeptanz, denn niemand setzt auf ein augenscheinlich totes Pferd.     

### Teilhabe aus der Community
In Open Source Projekten kann die Community Anforderungen stellen, bzw. Anregungen geben, wie bestimmte Dinge innerhalb der Anwendung besser gelöst werden können. Dies kann in Form von Tickets, oder auch Code (Pull Request) erfolgen. Aktuell kommen die fachlichen Anfoderungten aus den Fachreferaten. Das eine weiter Stelle mitredet, wie ein Softwareprodukt aussehen kann ist für alle Beteiligten neu. Deshalb ist es wichtig klare Prozesse Regeln und auch Verantwortlichkeiten zu definieren (und auch zu kommunizieren), wie Dritte sich in die Software Entwicklung einbringen können. Beispielsweise:
- Eine Rolle wie Product Owner zu definieren, mit den entsprechenden Befugnissen auszustatten und auch zu besetzen.
- Ein Product Backlog Board zu definieren und zu besetzen, dass darüber abstimmen kann, welche Tickets es in das Product Backlog schaffen. Dort könnte sowohl der Fachbereich, als auch sehr aktive Contributors aus der Community sitzen.
- Einen klaren Code Contributor Prozess definieren, der fest schreibt wie Code beigesteuert werden kann. Z.B. ausschließlich für Tickets, die sich im Product Backlog befinden. 


### Zusammenarbeit mit Software Anbietern

### Entwicklungsgrundsätze
Um Source Code bzw. eine Software für Dritte verwendbar zu machen, müssen die Hürden zur Nutzung möglichst minimiert werden. Schon in der Entwicklungsphase sollen deshalb folgende Grundsätze beachtet werden:
- Die Abhängigkeiten zu anderen Anwendungen sollen auf das absoluten Minimum beschränkt werden. Vor allem, wenn es sich bei den Anwendungen um Kaufprodukte handelt. Sind diese Abhängigkeiten dennoch nicht zu vermeiden - beispielsweise weil die Daten benötigt werden - so soll der Zugriff auf die Fremdanwendung so gekapselt werden, dass der Zugriff mit vertretbarem Aufwand neu implementiert werden kann. 
- Wenn es Abhängigkeiten zu technischen Infrastrukturkomponenten gibt (beispielsweise ein Datenbank Management Server, eine Suchmaschine oder einen Authentifizierungs Server), dann sollte der Zugriff über standardisierte Schnittstellen/ Protokolle erfolgen (z.B. OAuth oder SQL). Im besten Fall sollten in der technischen Infrastruktur auch FOSS Komponenten verwendet werden. 
- Die verwendeten Technologien sollen möglichst weit verbreitet sein. Das gilt sowohl für die verwendeten Programmiersprachen, als auch die primären Frameworks, die verwendet werden. Das erhöht die Chance, dass die nutzende Behörde über Mitarbeiter verfügt, die die Technologien beherrschen. 
- Die Zielinfrastruktur soll möglichst offen gehalten werden. D.h. die Anwendung sollte ohne große Anpassungen sowohl auf einem klassischen Server, als auch in einer Container Plattform oder einem Cloud Anbieter wie Amazon oder Google ausgebracht werden können.
- Die Lizenzen der verwendeten Bibliotheken müssen so konsolidiert werden, dass die Software mit keinen oder möglichst niedrigen Auflagen weiter gegeben werden darf. Es muss möglich sein nachzuvollziehen, welche Lizenzen in der Anwendung verwendet wurden. 
- Die Anwendung muss globalen Standards entsprechen. Das gilt beispielsweise für Dinge wie Barrierefreiheit. Aber auch für die Dokumentation oder Code Formatierung.
- Personenbezogene Daten, Passwörter und andere vertrauliche Informationen gehören auf keinen Fall in ein Source Code Repository. Das ist unabhängig davon, ob es privat oder öffentlich ist.

## Lizenzen

"Open Source" Software bedeutet, dass der Quellcode frei zugänglich ist - der Code ist _einsehbar_ und _prüfbar_, wie bei einem Auto, dem man in den Motorraum sehen kann.

Lizenzverträge regeln, inwiefern der Quellcode auch _nutzbar_ ist.
Es gibt eine [Vielzahl unterschiedlicher Open Source Lizenzen](https://choosealicense.com/).
In erster Linie unterscheiden sich diese in der Anforderung, ob [Bearbeitungen](https://en.wikipedia.org/wiki/Derivative_work) des Quellcodes fortan der selben Lizenz unterliegen müssen - der sogenannten "[Copyleft](https://de.wikipedia.org/wiki/Copyleft)" Klausel oder auch "Viralität" einer Lizenz.

"Virale" Lizenzen (wie die [GPL](https://choosealicense.com/licenses/gpl-3.0/) und die [EUPL](https://joinup.ec.europa.eu/collection/eupl/eupl-text-eupl-12)) erfordern, dass Bearbeitungen derselben Lizenz unterliegen wie das ursprüngliche Werk.
So müssen Veränderungen am Quellcode auch den ursprünglichen Autoren zugänglich gemacht werden.
Unterschiedliche Copyleft-Lizenzen können zueinander inkompatibel sein, was die Nutzung solcher Software erschweren kann.

Bei "freizügigen" Lizenzen (wie der [MIT](https://choosealicense.com/licenses/mit/)) entfällt dieser Zwang.
Auch Firmen und Entitäten, die ihre Arbeit nicht ohne weiteres veröffentlichen können, können solche Software ohne Bedenken nutzen und für ihre Zwecke anpassen.

  - Die Stadt München soll Open Source Software unabhängig von diesen Kategorien nutzen können. Copyleft- wie auch freizügige Lizenzen sind besser als proprietäre Nutzungsverträge.
  - Stellt die Stadt München selbst Software her, sollte sie eine freizügige Lizenz (wie MIT) wählen.


