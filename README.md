FOSS-Konzept Grün-Rot München 2020
==================================

<!---
Hier entsteht das Free and Open Source-Software-Konzept der grün-roten Regierungskoalition im Münchner Rathaus.
Wir freuen uns über Eure Teilnahme und Euer Feedback!
-->

Die [Koalitionsvereinbarung für die Stadtratsperiode 2020 –2026 zwischen Oberbürgermeister Dieter Reiter, den Münchner Parteien SPD und Die Grünen, der Stadtratsfraktion Die Grünen–Rosa Liste und der Fraktionsgemeinschaft SPD/Volt](https://www.gruene-muenchen.de/wp-content/uploads/2020/04/Druckfassung_Koalitionsvertrag-2020_2026.pdf) nennt unter dem Abschnitt "XII.Digitalisierung als Chance" folgende Punkte:

> Wo immer technisch und finanziell möglich setzt die Stadt auf offene Standards und freie Open Source-lizenzierte Software und vermeidet damit absehbare Herstellerabhängigkeiten. Diese Abwägung nehmen wir als Kriterium für Ausschreibungen mit auf, eine Abweichung von diesem Grundsatz muss begründet werden. Die Stadt unterhält ein öffentlich zugängliches Open Source Dashboard inkl. Kostenbilanz (auch bei Betriebssystemen und Office-Anwendungen), aus dem hervorgeht, in welchen Bereichen die Landeshauptstadt München auf Open Source setzt und welche Fortschritte in diesem Bereich gemacht wurden.

> Es gilt im Hoheitsbereich grundsätzlich das Prinzip “public money, public code”. Das heißt: Sofern keine personenbezogenen oder vertrauliche Daten enthalten sind, wird auch der Quellcode städtischer Software veröffentlicht. Die Stadt München unterstützt die Entwicklung von Open Source-Projekten mit einem "Munich Open Source Sabbatical". Professionelle Programmierer*innen, die sich für drei oder sechs Monate ganz auf die Fortentwicklung eines Open Source-Projektes konzentrieren möchten, können sich dafür auf ein städtisches bezahltes Stipendium bewerben. Die Projekte müssen einen kommunalen Nutzen haben.

Dieses Konzept definiert [Free Open Source Software](https://de.wikipedia.org/wiki/Free/Libre_Open_Source_Software) (FOSS) für die Landeshauptstadt München auf Basis des Koalitionsvertrags.
Es definiert Voraussetzungen, Abhängigkeiten, Ausschlüsse und Zielrichtung von Entwicklung, Beschaffung und Betrieb von OpenSource Software.

## Wieso Open Source?

Die Entscheidung für Open Source kann aus unterschiedlichen Gründen und Zugängen erfolgen, diese haben jeweils unterschiedliche Konsequenzen für die Umsetzung:

### Rückgewinnung digitaler Souveränität
Durch offenen Quellcode, [offene Standards](#offene-standards) und offene Schnittstellen ermöglichen wir eine Zusammenarbeit über eine Organisation hinaus. Dadurch lassen sich Gegengewichte zu den Netzwerkeffekten der großen Softwarekonzerne entwickeln. Offene Standards und Schnittstellen reduzieren zusätzlich die Herstellerabhängigkeit und ermöglichen größere Diversität.

### Sicherheit

Das Bundesamt für Scherheit in der Informationstechnik ([BSI](https://www.bsi.bund.de/DE/Themen/DigitaleGesellschaft/FreieSoftware/freiesoftware_node.html)) empfiehlt den Einsatz von FOSS und offenen Standards mit folgender Begründung: 

> Anpassbarkeit und Software-Vielfalt sowie die Verwendung offener Standards bieten eine Basis für IT-Sicherheit. Sicherheit ist jedoch ein Prozess. Um IT-Sicherheit erhalten zu können, müssen die Verantwortlichen das System genau kennen, regelmäßig warten und Sicherheitslücken schnell beheben. Der Einsatz von FLOSS bietet per se keine Gewähr für ein sicheres System. Er bietet in diesem Prozess jedoch bedeutende strategische Vorteile.

### Public Money, Public Code

[Von allen bezahlter Code sollte für alle verfügbar sein!](https://publiccode.eu/de/). Software, die von der öffentlichen Verwaltung entwickelt wird, ist bereits durch Steuergelder finanziert. Sie sollte damit als Allgemeingut den Bürger\*innen zur Verfügung stehen, wenn es dafür Verwendung gibt. Auch andere Kommunen oder Behörden können Open Source-Software wiederverwenden und damit eigene Entwicklungskosten oder Lizenzgebühren für proprietäre Anbieter einsparen.

## Offene Standards
Die Softwareprodukte, die in der Landeshauptstadt München verwendet werden, sind miteinander vernetzt. Zudem werden zwischen der LHM und anderen Behörden Daten ausgetauscht. Deshalb ist es wichtig, neben FOSS auch auf offene Standards zu setzen. 

[Ein Offener Standard ist ein Format oder Protokoll](https://fsfe.org/freesoftware/standards/def.de.html) das nur von anderen offenen Formaten abhängt, frei von rechtlichen Klauseln oder technischen Einschränkungen ist, gleichberechtigten weiterentwickelt wird, gleichermaßen für alle Beteiligten verfügbar ist und öffentlich geprüft und verwendet werden kann.

### Dokumentenstandards
In einer Behörde sind sehr viele Prozesse an Dokumenten orientiert. Deshalb sollen offene und damit von allen verwendbare Dokumentformate verwendet werden. Dies sind in der Regel Formate, deren Spezifikation von offenen Standardisierungsorganisationen betreut werden (z.B. PDF von der PDF Association), oder die entsprechend normiert sind (beispielsweise das Open Document Format nach ISO/IEC 26300).

### Austauschformate
Die Landeshauptstadt München tauscht regelmäßig Daten mit anderen Behörden aus. Hier ist es wichtig, dass diese Daten medienbruchfrei und automatisiert verarbeitet werden können. Für behördliche Spezialthemen (z.B. Einwohnermeldewesen oder Ausländerwesen) gibt es hier standardisierte Austauschformate wie [XÖV](https://www.xoev.de). Die Nutzung der XÖV-Formate ist häufig vom Gesetzgeber vorgeschrieben (z.B. im Bundesmeldegesetz). Darüber hinaus sollen auch in anderen Bereichen offene Austauschformate verwendet werden, wenn solche vorhanden sind.

### Standardisierte Protokolle
Um eine optimale Kommunikation innerhalb der Anwendungslandschaft zu gewährleisten, sollen die verwendeten Software Produkte ihre Schnittstellen über standardisierte und offene Protokolle zur Verfügung stellen. Solche Protokolle werden in der Regel von einer Standardisierungsorganisation (z.B. HTTP vom World Wide Web Consortium W3C) normiert und sind in der IT-Community weit verbreitet.

## Keine Herstellerabhängigkeiten

## Client-Betriebssysteme und Office-Anwendungen

## Individualentwicklungen

Individualentwicklungen sollen grundsätzlich mit Open Source-Frameworks und basierend auf Open Source-Komponenten entwickelt werden, unabhängig davon, ob die Software von der Stadt München oder einem Dienstleister im Auftrag entwickelt wird. Das ist Voraussetzung, um diese Fachanwendungen anderen Organisationen unter einer [Open Source-Lizenz](#lizenzen) zur Verfügung zu stellen.

## Betrieb von Open Source-Software

Open Source-Software mit anderen Behörden oder Kommunen zu teilen bedeutet, dass jede\*r die Software selber betreiben muss. Da insbesondere kleinere Kommunen nicht das Knowhow haben, Software selber zu betreiben, soll die Stadt München 

* darauf hinwirken, dass kommunale IT-Service-Provider, wie z.B. die AKDB, Open Source-Software der Stadt München für andere Kommunen oder Behörden betreibt und
* regelmäßig prüfen, ob sie selbst entwickelte Open Source-Software für andere Kommunen oder Behörden betreiben kann.

Dadurch können möglichst viele Kommunen (und damit Bürger\*innen) an den Investitionen der Stadt München partizipieren.

## Lizenzen

"Open Source"-Software bedeutet, dass der Quellcode frei zugänglich ist - der Code ist _einsehbar_ und _prüfbar_, wie bei einem Auto, dem man in den Motorraum sehen kann.

Lizenzverträge regeln, inwiefern der Quellcode auch _nutzbar_ ist.
Es gibt eine [Vielzahl unterschiedlicher Open Source-Lizenzen](https://choosealicense.com/).
In erster Linie unterscheiden sich diese in der Anforderung, ob [Bearbeitungen](https://en.wikipedia.org/wiki/Derivative_work) des Quellcodes fortan der selben Lizenz unterliegen müssen - der sogenannten "[Copyleft](https://de.wikipedia.org/wiki/Copyleft)" Klausel oder auch "Viralität" einer Lizenz.

"Virale" Lizenzen (wie die [GPL](https://choosealicense.com/licenses/gpl-3.0/) und die [EUPL](https://joinup.ec.europa.eu/collection/eupl/eupl-text-eupl-12)) erfordern, dass Bearbeitungen derselben Lizenz unterliegen wie das ursprüngliche Werk.
So müssen Veränderungen am Quellcode auch den ursprünglichen Autor\*innen zugänglich gemacht werden.
Unterschiedliche Copyleft-Lizenzen können zueinander inkompatibel sein, was die Nutzung solcher Software erschweren kann.

Bei "freizügigen" Lizenzen (wie der [MIT](https://choosealicense.com/licenses/mit/)) entfällt dieser Zwang.
Auch Firmen und Entitäten, die ihre Arbeit nicht ohne weiteres veröffentlichen können, können solche Software ohne Bedenken nutzen und für ihre Zwecke anpassen.

* Die Stadt München soll Open Source-Software unabhängig von diesen Kategorien nutzen können. Copyleft- wie auch freizügige Lizenzen sind besser als proprietäre Nutzungsverträge.
* Stellt die Stadt München [selbst Software her](#individualentwicklungen), sollte sie eine freizügige Lizenz (wie MIT) wählen.

## Beschaffung

Bei der Beschaffung von Software und Hardware sollen Lösungen aus dem Open Source-Umfeld präferiert werden.
Um die Funktionalität dieser Software sicherzustellen ist nicht nur Open Source-Software zu benutzen, sondern dazu auch Dienstleistungen zu beschaffen.
Dies schließt zahlreiche [Geschäftsmodelle für Open Source-Software](https://de.wikipedia.org/wiki/Gesch%C3%A4ftsmodelle_f%C3%BCr_Open-Source-Software#Ans%C3%A4tze) mit ein:

* es werden __Supportverträge__ für genutzte Open Source-Software beschafft (z.B. RedHat RHEL)
* es werden __Beratungsleistungen__ zu Einführung, Betrieb und Weiterentwicklung von Open Source-Software beschafft.
* es werden auch __Lizenzen__ für [dual-lizenzierte](#lizenzen) __proprietäre Erweiterungen__ von Software beschafft, deren freie Versionen bereits im Einsatz sind und deren relevanter Teil quelloffen ist (z.B. GitLab).

Die Landeshauptstadt München beschafft so professionelle Softwarelösungen, ohne sich mit der benutzten Software in eine [Herstellerabhängigkeit](#keine-herstellerabhängigkeiten) zu begeben.
So können Leistungen jederzeit neu ausgeschrieben und bestmöglich am Markt vergeben werden.
