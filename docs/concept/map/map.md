# Project Sagittarius – Konzept der Galaxiekarte

**Projekt:** Project Sagittarius / Sternenreiche  
**Dokument:** `docs/concept/map/map.md`  
**Dokumentversion:** 0.3  
**Stand:** 10. November 2026  
**Status:** Fachliches Spielkonzept  
**Geltungsbereich:** Ausschließlich die dreidimensionale Galaxiekarte der Milchstraße  
**Visuelle und funktionale Referenz:** Galaxiekarte von Elite Dangerous

---

# 1. Grundidee

Die Galaxiekarte bildet die zentrale räumliche und strategische Übersicht der Spielwelt von Project Sagittarius.

Sie stellt die Milchstraße in einem vollständig dreidimensionalen Raum dar.

Die Positionen und Entfernungen realer Sterne sollen auf wissenschaftlichen astronomischen Daten basieren.

Anders als bei einer ausschließlich prozedural generierten Spielgalaxie sollen bekannte Sterne ihre tatsächlichen räumlichen Beziehungen zueinander behalten.

Beispielsweise sollen die Sonne, Sirius, Proxima Centauri und andere katalogisierte Sterne an ihren astronomisch bestimmten Positionen erscheinen.

Die Galaxiekarte dient als zentrales Instrument für die räumliche Orientierung, die interstellare Navigation und die strategische Verwaltung einer Zivilisation.

## 1.1 Orientierung an Elite Dangerous

**Die Galaxiekarte von Elite Dangerous ist die verbindliche visuelle und funktionale Referenz für die Galaxiekarte von Project Sagittarius.**

Die Orientierung umfasst ausdrücklich:

- Die dreidimensionale Darstellung der Sterne.
- Die räumliche Tiefenwirkung.
- Den grundsätzlichen Aufbau der Kartenansicht.
- Die freie Bewegung innerhalb des dreidimensionalen Raums.
- Das Drehen und Neigen der Kamera.
- Die Fokussierung ausgewählter Sternensysteme.
- Das Zoomverhalten.
- Die Darstellung von Sternnamen und Markierungen.
- Die Anzeige räumlicher Entfernungen.
- Die Verwendung von Orientierungsgittern.
- Die Suche nach Sternensystemen.
- Die Bedienung von Informations- und Filteransichten.
- Die Darstellung geplanter interstellarer Routen.
- Das allgemeine technisch-futuristische Erscheinungsbild.

Der Spieler soll bei der Verwendung der Galaxiekarte ein Bediengefühl erleben, das dem der Galaxiekarte von Elite Dangerous sehr nahekommt.

Die Karte soll sich wie ein leistungsfähiges astronomisches Navigationsinstrument anfühlen.

Die Gestaltung erhält dennoch eine eigene visuelle Identität für Project Sagittarius. Originalgrafiken, Benutzeroberflächen, Texte, Symbole oder andere geschützte Assets aus Elite Dangerous werden nicht übernommen.

## 1.2 Die Galaxiekarte als eigenständiges Spielsystem

Die Galaxiekarte ist ein eigenständiger Bestandteil von Project Sagittarius.

Sie ist ausschließlich für die galaktische Ebene zuständig.

Dazu gehören:

- Darstellung von Sternensystemen.
- Dreidimensionale Sternpositionen.
- Räumliche Navigation.
- Systemauswahl.
- Interstellare Flugrouten.
- Darstellung von Raumflotten.
- Darstellung politischer Einflussbereiche.
- Anzeige von Kolonien.
- Anzeige interstellarer Transportverbindungen.
- Anzeige von Sprungtoren.
- Strategische Informationsfilter.

Die Galaxiekarte ist nicht für die Darstellung des Inneren einzelner Sternensysteme zuständig.

## 1.3 Abgrenzung zur Sternensystemansicht

Die dreidimensionale Ansicht eines einzelnen Sternensystems ist ein vollständig eigenständiges Spielsystem.

Sie gehört ausdrücklich nicht zum Funktionsumfang der Galaxiekarte.

Die Galaxiekarte stellt daher nicht selbst dar:

- Einzelne Planeten innerhalb eines Sternensystems.
- Monde.
- Planetare Umlaufbahnen.
- Die Bewegung von Planeten um Sterne.
- Die Bewegung von Monden um Planeten.
- Asteroidengürtel innerhalb eines Sternensystems.
- Die räumliche Anordnung planetarer Einrichtungen.
- Die lokale Kamerasteuerung innerhalb eines Sternensystems.

Diese Funktionen werden später in einem eigenen Konzept für Sternensystemansichten beschrieben.

Ein Sternensystem erscheint auf der Galaxiekarte zunächst als auswählbares astronomisches Systemobjekt.

Eine spätere Verbindung zwischen Galaxiekarte und Sternensystemansicht ist möglich. Derzeit werden dafür jedoch keine konkreten Übergänge, Kameraanimationen oder Bedienabläufe festgelegt.

## 1.4 Abgrenzung zur Planetenverwaltung

Die Verwaltung einzelner Planeten gehört ebenfalls nicht zur Galaxiekarte.

Die Galaxiekarte stellt weder das zweidimensionale Kachelraster eines Planeten noch dessen Gebäude und Produktionsanlagen dar.

Sie kann lediglich strategische Informationen über vorhandene Kolonien anzeigen.

Beispielsweise:

- Anzahl der Kolonien innerhalb eines Systems.
- Eigentümerfraktion.
- Bevölkerungsgröße.
- Wirtschaftliche Bedeutung.
- Aktuelle Versorgungslage.

Die eigentliche Koloniesimulation und ihre Benutzeroberfläche bleiben eigenständige Systeme.

## 1.5 Abgrenzung zu StellarForge

StellarForge wird als eigenständiges zukünftiges Konzept behandelt.

Die Entwicklung, Architektur und Funktionsweise von StellarForge sind ausdrücklich nicht Bestandteil dieses Dokuments.

Das betrifft insbesondere:

- Verfahren zur Erzeugung zusätzlicher Sternensysteme.
- Verteilung generierter Sterne.
- Generierung von Planeten.
- Generierung astronomischer Umlaufbahnen.
- Erzeugung von Planeteneigenschaften.
- Eigene Algorithmen und Datenmodelle von StellarForge.

StellarForge erhält später ein separates Dokument.

Die Galaxiekarte soll unabhängig davon funktionieren, woher die ihr bereitgestellten Sternensystemdaten stammen.

---

# 2. Aufbau der galaktischen Spielwelt

## 2.1 Die Milchstraße

Die Galaxiekarte bildet die Milchstraße als dreidimensionalen astronomischen Raum ab.

Die langfristige Zielsetzung ist eine möglichst umfangreiche Darstellung unserer Galaxie.

Die vorhandenen wissenschaftlichen Sternkataloge dienen dabei als Grundlage.

Der dargestellte Raum ist nicht als flache Spielkarte mit lediglich simulierten Höhenunterschieden aufgebaut.

Stattdessen besitzt jedes Sternensystem eine tatsächliche dreidimensionale Position.

## 2.2 Dreidimensionale Sternverteilung

Jedes Sternensystem besitzt eine Position innerhalb eines einheitlichen galaktischen Koordinatenraums.

Die räumlichen Beziehungen zwischen den Sternen müssen erhalten bleiben.

Ein Stern, der sich oberhalb oder unterhalb einer gewählten Referenzebene befindet, muss auch entsprechend im Raum erscheinen.

Der Spieler muss die Karte drehen und neigen können, um diese räumlichen Unterschiede erkennen zu können.

## 2.3 Astronomische Entfernungen

Die Entfernung zwischen zwei Sternensystemen ergibt sich aus ihren dreidimensionalen Positionen.

Diese Entfernung bildet unter anderem die Grundlage für die interstellare Navigation.

Die Karte darf Sternpositionen nicht verändern, nur um gleichmäßigere Abstände oder ein optisch einfacheres Navigationsnetz zu erzeugen.

Die tatsächlichen Entfernungen sind für die räumliche Darstellung und die Spielsimulation maßgeblich.

## 2.4 Sternensystem als Kartenobjekt

Ein Sternensystem wird auf der Galaxiekarte als zusammengehöriges Objekt behandelt.

Das gilt sowohl für Einzelsternsysteme als auch für Doppel- und Mehrfachsternsysteme.

Ein Mehrfachsternsystem soll nicht automatisch als mehrere unabhängig anwählbare interstellare Reiseziele erscheinen.

Die einzelnen Sternkomponenten gehören zu einem gemeinsamen System.

Eine spätere eigenständige Sternensystemansicht kann diese Komponenten detailliert darstellen.

## 2.5 Systemidentifikation

Jedes Sternensystem besitzt eine dauerhafte interne Kennung.

Die Kennung ist unabhängig vom Anzeigenamen.

Ein System kann mehrere wissenschaftliche Bezeichnungen besitzen.

Beispielsweise:

- Gebräuchlicher Sternname.
- Gaia-Kennung.
- Hipparcos-Kennung.
- Weitere wissenschaftliche Katalogkennungen.
- Alternative historische Bezeichnungen.

Die Sternensuche soll diese Bezeichnungen berücksichtigen können.

---

# 3. Astronomische Datengrundlage

## 3.1 Reale astronomische Daten

Die Galaxiekarte basiert primär auf öffentlich zugänglichen wissenschaftlichen Sternkatalogen.

Für die Darstellung sind insbesondere folgende Informationen relevant:

- Astronomische Position.
- Räumliche Entfernung.
- Sternidentifikation.
- Spektralklasse.
- Farbe.
- Helligkeit.
- Temperatur.
- Weitere verfügbare Sternparameter.

Die Karte verwendet die Daten, die ihr von der astronomischen Datenbasis bereitgestellt werden.

Sie ist nicht selbst für die wissenschaftliche Analyse oder Erzeugung fehlender Werte zuständig.

## 3.2 Gaia

Gaia bildet die wichtigste vorgesehene Grundlage für die Positionierung großer Sternpopulationen.

Als erste Referenz dient Gaia DR3.

Relevante Angaben können sein:

- Rektaszension.
- Deklination.
- Parallaxe.
- Eigenbewegung.
- Radialgeschwindigkeit.
- Photometrische Eigenschaften.
- Weitere astrophysikalische Parameter.

Aus diesen Informationen können geeignete räumliche Positionen abgeleitet werden.

Die zugrunde liegenden wissenschaftlichen Unsicherheiten müssen berücksichtigt werden.

## 3.3 Hipparcos

Hipparcos dient als ergänzende astronomische Datenquelle.

Insbesondere können zusätzliche Sternkennungen und Referenzinformationen verwendet werden.

Sterne, die in mehreren Katalogen vorkommen, dürfen nicht doppelt auf der Galaxiekarte erscheinen.

## 3.4 Weitere astronomische Datenquellen

Die Galaxiekarte soll grundsätzlich unabhängig von einer einzelnen astronomischen Datenquelle sein.

Weitere Kataloge können die bestehende Datenbasis ergänzen.

Die Auswahl, Zusammenführung und wissenschaftliche Bewertung solcher Quellen wird nicht innerhalb der Galaxiekarte durchgeführt.

Die Karte erhält daraus einen einheitlichen Bestand von Sternensystemobjekten.

## 3.5 Wissenschaftliche Datenherkunft

Die Herkunft astronomischer Informationen muss nachvollziehbar bleiben.

Vorgesehen sind mindestens folgende Kategorien:

| Kategorie | Bedeutung |
|---|---|
| Beobachtet | Wissenschaftlich gemessener Wert |
| Geschätzt | Wissenschaftlich abgeleiteter Wert |
| Generiert | Künstlich erzeugter Wert |
| Fiktiv | Bewusst erfundenes Spielelement |

Die Karte soll diese Herkunft bei Bedarf anzeigen können.

Ein wissenschaftlich katalogisierter Stern soll nicht ohne Kennzeichnung mit einem fiktiven Stern gleichgesetzt werden.

## 3.6 Datenqualität

Astronomische Messwerte können unvollständig oder unsicher sein.

Die Karte muss damit umgehen können, dass bestimmte Eigenschaften fehlen.

Fehlende Daten dürfen nicht automatisch als Nullwerte oder als wissenschaftlich bestätigte Eigenschaften dargestellt werden.

Wenn eine Eigenschaft unbekannt ist, kann sie entsprechend gekennzeichnet oder aus der Informationsanzeige ausgeblendet werden.

## 3.7 Einheitliches Kartenmodell

Die Galaxiekarte verwendet einen einheitlichen Bestand von Sternensystemen.

Die Herkunft aus unterschiedlichen Katalogen darf für die grundlegende Kartenbedienung keine Rolle spielen.

Alle Sternensysteme unterstützen dieselben grundlegenden Funktionen:

- Anzeige.
- Auswahl.
- Fokussierung.
- Suche.
- Entfernungsbestimmung.
- Navigation.
- Strategische Informationsdarstellung.

---

# 4. Visuelle Gestaltung nach Elite Dangerous

## 4.1 Grundlegendes Erscheinungsbild

Die Galaxiekarte soll optisch möglichst eng an der Galaxiekarte von Elite Dangerous orientiert sein.

Im Mittelpunkt steht ein dreidimensionaler Sternenraum mit einer dunklen, technisch wirkenden Benutzeroberfläche.

Die Darstellung soll übersichtlich, präzise und hochwertig wirken.

Sie soll weniger an eine klassische Strategie-Weltkarte erinnern, sondern stärker an ein interstellares Navigationssystem.

## 4.2 Hintergrund

Der Hintergrund der Karte ist überwiegend dunkel.

Er kann eine visuelle Darstellung der Milchstraße und ihrer Sternenpopulation enthalten.

Der Hintergrund darf jedoch nicht mit den tatsächlich auswählbaren Sternensystemen verwechselt werden.

Daher wird zwischen folgenden Elementen unterschieden:

**Astronomische Kartenobjekte**

Sternensysteme mit tatsächlichen räumlichen Koordinaten und eigener Identifikation.

**Visueller Hintergrund**

Nicht unmittelbar auswählbare grafische Elemente zur Darstellung der galaktischen Umgebung.

Der Hintergrund dient der Atmosphäre und der räumlichen Orientierung.

Er verändert nicht die Positionen der Kartenobjekte.

## 4.3 Darstellung der Sterne

Sternensysteme werden durch leuchtende Markierungen dargestellt.

Die Darstellung soll sich an der Sternensymbolik von Elite Dangerous orientieren.

Berücksichtigt werden können:

- Farbe entsprechend dem Sterntyp.
- Helligkeit.
- Entfernung.
- Auswahlstatus.
- Strategische Bedeutung.
- Aktive Hervorhebung.

Die sichtbare Größe der Markierung muss nicht dem tatsächlichen Radius des Sterns entsprechen.

Wesentlich ist eine gute Erkennbarkeit bei unterschiedlichen Zoomstufen.

## 4.4 Tiefenwirkung

Ein zentrales Gestaltungsmerkmal ist die klare Wahrnehmbarkeit der dritten Dimension.

Diese wird unter anderem unterstützt durch:

- Perspektivische Darstellung.
- Unterschiedliche scheinbare Sternabstände.
- Kamerabewegung.
- Räumliche Referenzlinien.
- Ein optionales Orientierungsgitter.
- Höhenlinien zwischen Sternpositionen und Referenzebene.
- Sichtbare Parallaxe bei Kamerabewegungen.

Die Karte darf auch bei hoher Sternendichte nicht wie eine flache Punktwolke wirken.

## 4.5 Orientierungsgitter

Wie bei Elite Dangerous soll ein räumliches Orientierungsgitter vorgesehen werden.

Dieses dient als visuelle Referenz für die Position und Entfernung von Sternensystemen.

Das Gitter darf die tatsächlichen Sternpositionen nicht verändern.

Es stellt ausschließlich eine Orientierungshilfe dar.

## 4.6 Referenzebene

Das Orientierungsgitter kann auf einer horizontalen Referenzebene dargestellt werden.

Sterne befinden sich abhängig von ihren tatsächlichen Positionen oberhalb oder unterhalb dieser Ebene.

Die Referenzebene selbst ist kein physikalisches Hindernis und keine Grenze des spielbaren Raums.

## 4.7 Projektionslinien

Für ausgewählte Sternensysteme können Verbindungslinien zwischen ihrer räumlichen Position und der Referenzebene dargestellt werden.

Dadurch wird ihre Höhe beziehungsweise Tiefe im dreidimensionalen Raum besser erkennbar.

Diese Darstellung orientiert sich an der räumlichen Lesbarkeit der Elite-Dangerous-Galaxiekarte.

Die Projektionslinien sind keine Flugrouten.

## 4.8 Auswahlmarkierungen

Ein ausgewähltes Sternensystem erhält eine deutlich sichtbare Hervorhebung.

Vorgesehen sind:

- Leuchtende Auswahlmarkierung.
- Fokusrahmen oder Auswahlring.
- Hervorgehobener Systemname.
- Sichtbare räumliche Orientierung.
- Optional hervorgehobene Projektionslinie.
- Verbindung zum Informationsfenster.

Die Markierung soll auch bei vielen umliegenden Sternen eindeutig erkennbar bleiben.

## 4.9 Farben

Die Farbgestaltung orientiert sich am technisch-futuristischen Stil von Elite Dangerous.

Als visuelle Ausgangsrichtung sind geeignet:

- Dunkle Hintergründe.
- Weißliche oder farblich zum Stern passende Sternmarkierungen.
- Cyan- und Blautöne für ausgewählte technische Informationen.
- Orange beziehungsweise warme Akzentfarben für wichtige Bedien- und Navigationsinformationen.
- Dezente transparente Informationsebenen.

Die genaue Farbpalette bleibt Teil des eigenständigen Designs von Project Sagittarius.

## 4.10 Visuelle Zurückhaltung

Die Karte soll keine unnötig aufwendigen Effekte verwenden, die die Orientierung erschweren.

Bewegungen, Glüheffekte und Animationen sollen dem Verständnis der Karte dienen.

Im Vordergrund stehen:

- Sternpositionen.
- Entfernungen.
- Auswahl.
- Routen.
- Strategische Informationen.

---

# 5. Kamerasteuerung

## 5.1 Bedienphilosophie

Die Kamerasteuerung soll sich am Bediengefühl der Galaxiekarte von Elite Dangerous orientieren.

Sie muss dem Spieler erlauben, sich frei und präzise innerhalb des dreidimensionalen Sternenraums zu orientieren.

Der Spieler soll nicht an vorgegebene Kamerawinkel gebunden sein.

## 5.2 Freie Kamerabewegung

Vorgesehen sind:

- Dreidimensionales Verschieben der Ansicht.
- Drehen um einen Fokuspunkt.
- Neigen der Kamera.
- Zoomen.
- Zentrieren ausgewählter Systeme.
- Wechsel zwischen unterschiedlichen Maßstäben.
- Rückkehr zu einer vorherigen Kartenposition.

## 5.3 Rotation

Die Karte soll sich um den aktuellen Fokuspunkt drehen lassen.

Dadurch kann der Spieler die Sternenverteilung aus verschiedenen Richtungen betrachten.

Die Rotation soll flüssig und nachvollziehbar erfolgen.

Der Fokuspunkt soll dabei möglichst stabil bleiben.

## 5.4 Neigung

Die Kamera soll frei geneigt werden können.

Dadurch lässt sich die räumliche Anordnung von Sternensystemen oberhalb und unterhalb der Referenzebene betrachten.

Die Bedienung muss auch bei starken Neigungswinkeln verständlich bleiben.

## 5.5 Verschieben

Die Kamera kann unabhängig vom aktuellen Fokus durch den galaktischen Raum bewegt werden.

Das Verschieben soll sich direkt und präzise anfühlen.

Der Spieler muss nicht jedes Mal ein neues Sternensystem auswählen, um die Ansicht zu bewegen.

## 5.6 Zoom

Die Galaxiekarte benötigt einen großen Zoombereich.

Der Spieler soll zwischen der nahen Betrachtung einzelner Sternensysteme und der Übersicht größerer Sternregionen wechseln können.

Das Zoomverhalten soll sich an Elite Dangerous orientieren.

Insbesondere soll es:

- Flüssig sein.
- Unterschiedliche Größenordnungen sinnvoll abdecken.
- Den aktuellen Fokus berücksichtigen.
- Keine abrupten ungewollten Positionswechsel verursachen.

## 5.7 Fokus auf ein Sternensystem

Der Spieler kann ein Sternensystem auswählen und die Kamera darauf zentrieren.

Die Kamera bewegt sich zu einer geeigneten Betrachtungsposition.

Die umliegenden Sterne sollen weiterhin erkennbar bleiben, damit der räumliche Zusammenhang erhalten bleibt.

## 5.8 Wechsel des Fokus

Wählt der Spieler ein anderes System aus, soll die Kamera entsprechend neu ausgerichtet werden können.

Der Wechsel soll nachvollziehbar sein und keine unnötige Desorientierung erzeugen.

## 5.9 Rückkehr zum vorherigen Fokus

Der Spieler soll zu einer vorherigen Kartenposition oder einem zuvor ausgewählten Sternensystem zurückkehren können.

Auch eine Rückkehr zum Sonnensystem oder zur Hauptstadt der eigenen Fraktion soll als Kartenfunktion vorgesehen werden.

## 5.10 Eingabegeräte

Die Karte wird vorrangig für Maus und Tastatur konzipiert.

Die Bedienung soll direkte Mausinteraktionen für Auswahl, Drehen, Verschieben und Zoomen ermöglichen.

Konkrete Tastenbelegungen bleiben noch offen.

Die grundlegenden Bewegungsarten und das Bediengefühl sollen sich jedoch deutlich an Elite Dangerous orientieren.

## 5.11 Grenzen der Kamerabewegung

Die Kamera soll den vorgesehenen galaktischen Datenraum sinnvoll erkunden können.

Sie darf nicht auf eine einzige Kartenebene beschränkt sein.

Die konkreten Grenzen des darstellbaren und bespielbaren Bereichs werden später festgelegt.

---

# 6. Benutzeroberfläche

## 6.1 Grundaufbau

Die Galaxiekarte erhält eine eigenständige Benutzeroberfläche.

Der Grundaufbau soll sich an der Galaxiekarte von Elite Dangerous orientieren.

Dabei stehen die dreidimensionale Sternenansicht und ihre Bedienbarkeit im Vordergrund.

Informationsfenster sollen die räumliche Darstellung ergänzen, aber nicht unnötig verdecken.

## 6.2 Zentrale Kartenfläche

Der größte Teil des Bildschirms wird von der dreidimensionalen Sternenkarte eingenommen.

Hier erfolgt die eigentliche Navigation.

Sternensysteme können direkt ausgewählt werden.

Routen, Markierungen und strategische Informationen werden als zusätzliche Ebenen dargestellt.

## 6.3 Informationsbereiche

Die Benutzeroberfläche kann seitliche Informationsbereiche verwenden.

Diese enthalten beispielsweise:

- Ausgewähltes Sternensystem.
- Astronomische Eigenschaften.
- Suche.
- Filter.
- Navigationsinformationen.
- Fraktionsinformationen.
- Vorhandene Kolonien.
- Strategische Markierungen.

Die genaue räumliche Anordnung der einzelnen Bereiche wird im späteren UI-Konzept festgelegt.

Die grundsätzliche Panel-Bedienung soll jedoch dem funktionalen Stil von Elite Dangerous entsprechen.

## 6.4 Kontextbezogene Informationen

Die Oberfläche soll nicht ständig sämtliche verfügbaren Daten anzeigen.

Stattdessen werden Informationen abhängig von der aktuellen Auswahl und Kartenansicht eingeblendet.

Ein nicht ausgewählter Stern kann beispielsweise nur durch seine Markierung dargestellt werden.

Nach der Auswahl erscheinen zusätzliche Informationen.

## 6.5 Bedienaktionen

Für ein ausgewähltes Sternensystem sollen geeignete Aktionen verfügbar sein.

Beispiele:

- System fokussieren.
- Astronomische Informationen anzeigen.
- Als Navigationsziel markieren.
- Route berechnen.
- In Such- oder Favoritenlisten übernehmen.
- Strategische Informationen anzeigen.

Weitere Aktionen können später durch andere Spielsysteme bereitgestellt werden.

## 6.6 Kartenmodus

Die Galaxiekarte soll unterschiedliche Informationsmodi unterstützen.

Der Spieler kann beispielsweise zwischen einer astronomischen und einer politischen Ansicht wechseln.

Der zugrunde liegende dreidimensionale Raum bleibt dabei unverändert.

## 6.7 Darstellung bei hohen Auflösungen

Die Bedienoberfläche soll auch bei großen Bildschirmauflösungen übersichtlich bleiben.

Informationsfenster dürfen nicht unnötig viel Platz beanspruchen.

Die Sternenkarte bleibt das zentrale visuelle Element.

---

# 7. Auswahl und Suche von Sternensystemen

## 7.1 Direkte Auswahl

Der Spieler kann ein Sternensystem direkt auf der Karte auswählen.

Das ausgewählte Objekt wird hervorgehoben.

Die zugehörigen Informationen erscheinen in der Kartenoberfläche.

## 7.2 Auswahl in dichter Sternumgebung

Bei hoher Sternendichte können mehrere Kartenobjekte nahe beieinander erscheinen.

Die Auswahl muss trotzdem eindeutig und zuverlässig möglich sein.

Die visuelle Hervorhebung soll erkennen lassen, welches System ausgewählt wurde.

## 7.3 Suche nach Namen

Der Spieler soll Sternensysteme anhand ihres Namens suchen können.

Die Suche berücksichtigt auch alternative Bezeichnungen.

## 7.4 Suche nach Katalogkennungen

Zusätzlich sollen wissenschaftliche Katalogidentifikatoren verwendet werden können.

Beispielsweise Gaia- oder Hipparcos-Kennungen.

Dadurch kann der Spieler reale astronomische Objekte auch dann finden, wenn sie keinen allgemein bekannten Namen besitzen.

## 7.5 Suchergebnisse

Die Suche liefert eine Liste passender Sternensysteme.

Ein Suchergebnis kann ausgewählt und auf der Karte fokussiert werden.

Die Karte soll dabei nicht automatisch eine interstellare Reise auslösen.

## 7.6 Favoriten und Markierungen

Als zusätzliche Kartenfunktion werden Favoriten beziehungsweise gespeicherte Sternensystemmarkierungen vorgesehen.

Sie können beispielsweise für folgende Zwecke verwendet werden:

- Wichtige Kolonien.
- Strategische Systeme.
- Interessante astronomische Objekte.
- Geplante Expansionsziele.
- Relevante Verkehrsknoten.

Die genaue Verwaltung dieser Markierungen bleibt offen.

---

# 8. Astronomische Informationsanzeige

## 8.1 Informationsumfang

Nach Auswahl eines Sternensystems kann die Karte verfügbare astronomische Informationen anzeigen.

Dazu gehören:

- Systemname.
- Alternative Bezeichnungen.
- Astronomische Kennungen.
- Systemposition.
- Entfernung zu einer Referenzposition.
- Sternklasse beziehungsweise Sternklassen.
- Bekannte Sternkomponenten.
- Helligkeit.
- Weitere verfügbare physikalische Eigenschaften.
- Herkunft und Qualität der verwendeten Daten.

## 8.2 Einzel- und Mehrfachsternsysteme

Die Galaxiekarte unterscheidet zwischen Einzelsternsystemen und Mehrfachsternsystemen.

Ein Mehrfachsternsystem bleibt ein zusammengehöriges galaktisches Kartenobjekt.

Die Informationsanzeige kann die bekannte Anzahl seiner Sternkomponenten nennen.

Die räumliche Darstellung dieser Komponenten innerhalb des Sternensystems gehört nicht zur Galaxiekarte.

## 8.3 Systembezogene Spielinformationen

Neben astronomischen Daten können strategische Informationen angezeigt werden.

Beispiele:

- Eigentümerfraktion.
- Erkundungsstatus.
- Besiedlungsstatus.
- Anzahl vorhandener Kolonien.
- Vorhandene Sprungtore.
- Raumstationen.
- Bekannte Flotten.
- Aktive Transportverbindungen.

Diese Informationen werden von den jeweils zuständigen Spielsystemen bereitgestellt.

## 8.4 Unbekannte Informationen

Informationen, die der aktiven Fraktion nicht bekannt sind, dürfen nicht ohne entsprechende Berechtigung angezeigt werden.

Das gilt auch dann, wenn die Spielwelt oder die astronomische Datenbasis die entsprechenden Eigenschaften bereits enthält.

---

# 9. Interstellare Navigation

## 9.1 Aufgabe der Galaxiekarte

Die Galaxiekarte dient als zentrale Oberfläche zur Planung und Anzeige interstellarer Reisen.

Der Spieler kann:

- Ein Ausgangssystem bestimmen.
- Ein Zielsystem auswählen.
- Eine Route anzeigen.
- Die voraussichtliche Reisezeit einsehen.
- Zwischenstationen erkennen.
- Vorhandene Sprungtore berücksichtigen.
- Den Verlauf einer Reise verfolgen.

## 9.2 Warpantrieb

Die interstellare Raumfahrt verwendet neun Warpstufen.

Die bisher vorgeschlagenen Geschwindigkeiten bleiben erhalten.

| Warpstufe | Lichtjahre pro Spieljahr |
|---|---:|
| Warp 1 | 12 |
| Warp 2 | 18 |
| Warp 3 | 27 |
| Warp 4 | 40 |
| Warp 5 | 60 |
| Warp 6 | 90 |
| Warp 7 | 135 |
| Warp 8 | 200 |
| Warp 9 | 300 |

Diese Werte sind vorläufige Balancewerte.

Die tatsächliche Reisezeit ergibt sich aus der zurückzulegenden dreidimensionalen Entfernung und der jeweiligen Warpgeschwindigkeit.

## 9.3 Flottengeschwindigkeit

Besteht eine Flotte aus mehreren gemeinsam reisenden Schiffen, orientiert sich die Reisegeschwindigkeit grundsätzlich am langsamsten Schiff.

Die angezeigte Reisezeit muss diese Einschränkung berücksichtigen.

## 9.4 Navigation zwischen Sternensystemen

Normale interstellare Reisen erfolgen zwischen Sternensystemen.

Eine Route kann über mehrere Systeme führen.

Der Routenplaner soll eine zulässige Verbindung mit möglichst geringer Gesamtreisezeit ermitteln.

Zusätzliche Beschränkungen einzelner Warpetappen sind noch nicht abschließend festgelegt.

## 9.5 Sprungtore

Sprungtore werden von Spieler- und KI-Fraktionen errichtet.

Auf der Galaxiekarte erscheinen sie als strategische interstellare Infrastruktur.

Die bestehenden Zugriffsregeln bleiben erhalten:

- Eigene Sprungtore dürfen verwendet werden.
- Sprungtore befreundeter Fraktionen dürfen verwendet werden.
- Sprungtore verbündeter Fraktionen dürfen verwendet werden.
- Neutrale oder feindliche Sprungtore sind ohne zusätzliche Rechte nicht zugänglich.

Eine Sprungtorpassage benötigt keine Spielzeit.

## 9.6 Darstellung von Sprungtoren

Systeme mit Sprungtoren erhalten eine geeignete zusätzliche Kartenmarkierung.

Die Karte soll unterscheiden können zwischen:

- Eigenem Sprungtor.
- Zugänglichem fremdem Sprungtor.
- Nicht zugänglichem Sprungtor.
- Nicht funktionsfähigem Sprungtor.

Die konkrete Symbolgestaltung orientiert sich am technisch-futuristischen Look der Galaxiekarte.

## 9.7 Kombinierte Routen

Eine Route kann Warpstrecken und Sprungtorpassagen kombinieren.

Beispiel:

`Startsystem → Warp → Sprungtor A → Sprungtor B → Warp → Zielsystem`

Dabei berücksichtigt die Navigation die jeweiligen Reisezeiten und Zugriffsrechte.

## 9.8 Routenanzeige nach Elite-Dangerous-Vorbild

Die Darstellung interstellarer Routen soll sich an der klaren, räumlich nachvollziehbaren Routenvisualisierung von Elite Dangerous orientieren.

Routen erscheinen als Verbindungslinien zwischen den betreffenden Sternensystemen.

Verschiedene Arten von Verbindungen müssen erkennbar bleiben.

Beispielsweise:

- Normale Warpstrecke.
- Sprungtorpassage.
- Geplante Route.
- Aktuell bereiste Strecke.
- Nicht nutzbare Verbindung.

Die genaue Farb- und Liniengestaltung bleibt offen.

## 9.9 Keine Veränderung der Sternpositionen

Die Route wird durch den realen dreidimensionalen Sternenraum dargestellt.

Sternensysteme dürfen nicht für eine optisch einfachere Linienführung verschoben werden.

Eine gekrümmte oder aus mehreren Segmenten bestehende grafische Darstellung darf nur die Wegführung visualisieren und nicht die astronomischen Positionen verändern.

## 9.10 Reisezeit

Die Karte zeigt die voraussichtliche Reisezeit einer geplanten Route.

Diese berücksichtigt:

- Dreidimensionale Sternentfernungen.
- Aktuelle Warpstufe.
- Flottenzusammensetzung.
- Zwischenstationen.
- Zugängliche Sprungtore.

Die Reisezeit ist eine spielmechanische Berechnung und keine visuelle Schätzung anhand der Bildschirmabstände.

## 9.11 Routenänderungen

Routen können durch Ereignisse ungültig werden.

Beispiele:

- Ein Sprungtor fällt aus.
- Ein Sprungtor wird zerstört.
- Die diplomatischen Zugriffsrechte ändern sich.
- Ein benötigtes Zwischenziel wird unzugänglich.

Die Karte muss den aktuellen Routenstatus anzeigen können.

Bei Bedarf kann eine neue Route berechnet werden.

---

# 10. Transportnetzwerke

## 10.1 Grundprinzip

Die Galaxiekarte soll aktive interstellare Transportnetzwerke darstellen können.

Hierbei muss zwischen möglichen Flugrouten und tatsächlich betriebenen Transportlinien unterschieden werden.

## 10.2 Mögliche Flugroute

Eine mögliche Flugroute beschreibt eine Verbindung, die von einem geeigneten Raumschiff unter den geltenden Navigationsregeln zurückgelegt werden könnte.

Das Vorhandensein einer solchen Route bedeutet nicht, dass dort regelmäßig Transportschiffe verkehren.

## 10.3 Aktive Transportlinie

Eine aktive Transportlinie wird tatsächlich durch geeignete Transportschiffe bedient.

Sie besitzt entsprechende Haltepunkte und verfügbare Transportkapazitäten.

## 10.4 Passagiertransport

Das Bevölkerungssystem verwendet bestehende Transportschiffverbindungen für die automatische Migration.

Die Galaxiekarte kann diese Verbindungen darstellen.

Mehrgliedrige Routen und Umsteigepunkte müssen dabei erkennbar sein können.

Die eigentliche Bevölkerungszuweisung und Migrationsplanung werden nicht innerhalb der Galaxiekarte durchgeführt.

## 10.5 Warentransport

Materielle Ressourcen und Produkte können ebenfalls zwischen Kolonien transportiert werden.

Die Galaxiekarte stellt hierfür geeignete interstellare Verbindungen dar.

Die Produktion und Lagerhaltung verbleiben in den Wirtschaftssystemen.

## 10.6 Verkehrsknoten

Sternensysteme mit vielen Transportverbindungen können eine besondere strategische Bedeutung besitzen.

Die Karte soll solche Verkehrsknoten sichtbar machen können.

## 10.7 Transportfilter

Ein eigener Kartenfilter soll vorhandene Transportlinien anzeigen können.

Dabei sollen mindestens folgende Informationen unterscheidbar sein:

- Passagierverbindungen.
- Warenverbindungen.
- Wichtige Umsteigepunkte.
- Zentrale Transportknoten.

Die Darstellung kann später um Kapazitäten und Auslastungsinformationen ergänzt werden.

---

# 11. Politische und strategische Kartenansichten

## 11.1 Fraktionszugehörigkeit

Jedes Sternensystem kann einer Fraktion zugeordnet sein oder keiner Fraktion gehören.

Die Galaxiekarte kann diese Zugehörigkeit anzeigen.

Die zugrunde liegenden Sternpositionen bleiben unverändert.

## 11.2 Politische Einflussbereiche

Die Karte soll die räumliche Ausdehnung verschiedener Fraktionen darstellen können.

Da die Sternensysteme dreidimensional verteilt sind, müssen politische Gebiete ebenfalls räumlich nachvollziehbar dargestellt werden.

Eine ausschließlich zweidimensionale Grenzlinie reicht hierfür nicht grundsätzlich aus.

## 11.3 Politische Darstellung

Die politische Kartenansicht soll sich an der Filter- und Informationsdarstellung von Elite Dangerous orientieren.

Mögliche Darstellungsformen sind:

- Farblich markierte Sternensysteme.
- Transparente räumliche Einflussbereiche.
- Hervorgehobene Grenzen.
- Markierungen wichtiger Systeme.
- Zusätzliche Fraktionsinformationen.

Die konkrete Form der dreidimensionalen Gebietsvisualisierung bleibt offen.

## 11.4 Kolonien

Besiedelte Sternensysteme sollen auf der Galaxiekarte erkennbar sein.

Die Karte kann unter anderem anzeigen:

- Anzahl der Kolonien.
- Kontrollierende Fraktion.
- Wirtschaftliche Bedeutung.
- Bevölkerungsgröße.
- Strategische Bedeutung.

Die eigentlichen Koloniedaten werden vom zuständigen Spielsystem bereitgestellt.

## 11.5 Hauptstadt und Kernsysteme

Die Hauptsysteme einer Fraktion sollen besonders markiert werden können.

Dazu gehören:

- Hauptstadt.
- Wichtige Kolonien.
- Industrielle Zentren.
- Forschungszentren.
- Militärische Hauptstützpunkte.

## 11.6 Strategische Infrastruktur

Die Galaxiekarte kann interstellare Einrichtungen anzeigen.

Beispiele:

- Sprungtore.
- Große Raumwerften.
- Bedeutende Raumstationen.
- Militärische Stützpunkte.
- Verkehrsknoten.

Dabei werden die Einrichtungen auf der galaktischen Ebene ihrem jeweiligen Sternensystem zugeordnet.

Die detaillierte lokale Positionierung innerhalb des Sternensystems gehört nicht zur Galaxiekarte.

---

# 12. Flotten und militärische Informationen

## 12.1 Flotten auf der Galaxiekarte

Raumflotten sollen als eigenständige strategische Markierungen auf der Galaxiekarte erscheinen.

Eine Flotte besitzt einen aktuellen interstellaren Standort beziehungsweise einen laufenden Reiseabschnitt.

## 12.2 Flotteninformationen

Die Kartenansicht kann folgende Informationen anzeigen:

- Flottenname.
- Eigentümerfraktion.
- Anzahl der Schiffe.
- Aktueller Standort.
- Zielsystem.
- Geplanter Reiseweg.
- Voraussichtliche Ankunft.
- Bewegungsstatus.

## 12.3 Bewegte Flotten

Reisende Flotten sollen entlang ihrer geplanten interstellaren Route dargestellt werden können.

Die angezeigte Position wird aus dem tatsächlichen Reisefortschritt abgeleitet.

Die grafische Bewegung darf nicht unabhängig von der Spielsimulation ablaufen.

## 12.4 Fremde Flotten

Die Sichtbarkeit fremder Flotten hängt von den verfügbaren Informationen der Spielerfraktion ab.

Nicht entdeckte oder nicht erfassbare Flotten dürfen nicht allein aufgrund ihrer Existenz automatisch sichtbar sein.

## 12.5 Militärische Kartenansicht

Ein eigener Filter kann militärisch relevante Informationen hervorheben.

Beispielsweise:

- Eigene Flotten.
- Bekannte feindliche Flotten.
- Militärische Stützpunkte.
- Verteidigte Systeme.
- Strategisch wichtige Transportwege.

Die eigentliche Kampfsimulation ist nicht Bestandteil der Galaxiekarte.

---

# 13. Kartenfilter

## 13.1 Grundprinzip

Die Galaxiekarte erhält unterschiedliche Informationsansichten.

Die Bedienlogik soll sich an der Galaxiekarte von Elite Dangerous orientieren.

Der Spieler kann gezielt die Informationen hervorheben, die für seine aktuelle Aufgabe relevant sind.

## 13.2 Astronomischer Filter

Der astronomische Filter zeigt beispielsweise:

- Sternklassen.
- Sternfarben.
- Sternhelligkeiten.
- Wissenschaftlich bekannte Eigenschaften.
- Entfernungen.
- Interessante astronomische Systeme.

## 13.3 Politischer Filter

Der politische Filter stellt Fraktionen und ihren galaktischen Einfluss dar.

Er kann insbesondere hervorheben:

- Eigene Systeme.
- Befreundete Systeme.
- Verbündete Systeme.
- Neutrale Systeme.
- Feindliche Systeme.

Die tatsächliche diplomatische Beziehung wird vom Diplomatiesystem bereitgestellt.

## 13.4 Koloniefilter

Der Koloniefilter hebt besiedelte Sternensysteme hervor.

Optional können weitere Informationen angezeigt werden.

Beispiele:

- Bevölkerungsgröße.
- Kolonieanzahl.
- Wirtschaftliche Spezialisierung.
- Versorgungsstatus.

## 13.5 Wirtschaftsfilter

Der Wirtschaftsfilter stellt wichtige Produktions- und Handelsstandorte dar.

Die Karte kann beispielsweise bedeutende Industrie- oder Landwirtschaftssysteme hervorheben.

## 13.6 Ressourcenfilter

Der Ressourcenfilter stellt bekannte wirtschaftlich relevante Rohstoffinformationen auf Systemebene dar.

Er zeigt keine planetaren Kacheln oder einzelnen Lagerstätten innerhalb eines Planeten.

## 13.7 Transportfilter

Der Transportfilter zeigt tatsächlich betriebene Waren- und Passagierverbindungen.

Technisch mögliche, aber nicht betriebene Verbindungen werden davon getrennt behandelt.

## 13.8 Navigationsfilter

Der Navigationsfilter hebt interstellare Reiserouten, erreichbare Sternensysteme und zugängliche Sprungtore hervor.

## 13.9 Militärfilter

Der Militärfilter hebt bekannte Flotten und militärische Einrichtungen hervor.

## 13.10 Erkundungsfilter

Der Erkundungsfilter stellt das Wissen der aktuellen Fraktion über die Galaxie dar.

Er unterscheidet beispielsweise bekannte, unerforschte und bereits untersuchte Sternensysteme.

## 13.11 Kombinierte Filter

Der Spieler soll mehrere Informationsarten bei Bedarf miteinander kombinieren können.

Beispielsweise:

- Politische Karte und Sprungtore.
- Kolonien und Transportlinien.
- Militärische Flotten und geplante Routen.
- Erkundungsstatus und astronomische Sternklassen.

Die Darstellung darf dabei nicht unübersichtlich werden.

---

# 14. Erkundung und Informationsverfügbarkeit

## 14.1 Trennung von Sternendaten und Fraktionswissen

Die astronomische Datenbasis und das tatsächliche Wissen einer Zivilisation sind unterschiedliche Informationen.

Ein real katalogisierter Stern kann innerhalb der Spielwelt einer Fraktion unbekannt sein.

Die Herkunft des astronomischen Datensatzes bleibt davon unberührt.

## 14.2 Vorgesehene Erkundungszustände

Als konzeptionelle Grundlage können folgende Zustände verwendet werden:

| Zustand | Bedeutung |
|---|---|
| Unbekannt | Der Fraktion liegen keine verwertbaren Informationen vor |
| Bekannt | Position und grundlegende Informationen sind bekannt |
| Erkundet | Das System wurde untersucht |
| Vermessen | Weitergehende astronomische Informationen liegen vor |

Die genauen Bedingungen für diese Zustände werden im separaten Erkundungskonzept festgelegt.

## 14.3 Anzeige unbekannter Systeme

Wie unbekannte Sternensysteme auf der Karte erscheinen, bleibt eine offene konzeptionelle Entscheidung.

Möglichkeiten sind:

- Vollständige Ausblendung.
- Stark vereinfachte Markierung.
- Anzeige der bekannten Sternposition ohne weitere Eigenschaften.
- Darstellung einer unbekannten beziehungsweise nicht untersuchten Region.

Die endgültige Regel muss zur gewünschten Verbindung aus astronomischer Glaubwürdigkeit und 4X-Erkundung passen.

## 14.4 Sensordaten

Spätere Sensor- und Aufklärungssysteme können zusätzliche Informationen über Sternensysteme, Flotten und Infrastruktur bereitstellen.

Die Galaxiekarte übernimmt die verfügbaren Informationen und stellt sie dar.

Sie führt selbst keine eigenständige Sensorsimulation aus.

---

# 15. Maßstäbe und räumliche Genauigkeit

## 15.1 Astronomische Koordinaten

Sternensysteme besitzen ihre Positionen in einem gemeinsamen dreidimensionalen Koordinatenraum.

Die Koordinaten bleiben unabhängig von der aktuellen Kameraansicht.

## 15.2 Entfernungen

Interstellare Entfernungen werden mit geeigneten astronomischen Einheiten beschrieben.

Für den Spieler sollen Entfernungen üblicherweise in Lichtjahren angezeigt werden.

## 15.3 Maßstab der Karte

Die Darstellung verwendet einen für große interstellare Entfernungen geeigneten Maßstab.

Die Größe von Sternsymbolen und Beschriftungen darf unabhängig von der physikalischen Größe eines Sterns angepasst werden.

Die Sternpositionen selbst dürfen dadurch nicht verändert werden.

## 15.4 Referenzebene

Die Referenzebene dient ausschließlich der räumlichen Orientierung.

Sie ist keine Einschränkung des galaktischen Raums.

## 15.5 Dreidimensionale Tiefe

Die tatsächliche räumliche Position eines Sternensystems soll durch Drehung und Neigung der Karte erkennbar sein.

Die Karte darf die dritte Dimension nicht nur durch künstliche optische Effekte vortäuschen.

## 15.6 Visuelle Verzerrungen

Dekorative Effekte oder skalierte Markierungen dürfen die Entfernung zwischen zwei Sternensystemen nicht verändern.

Das Navigationssystem verwendet weiterhin die tatsächlichen räumlichen Koordinaten.

---

# 16. Zeit und Spielsimulation

## 16.1 Globale Spielzeit

Die Galaxiekarte verwendet die zentrale Spielzeit von Project Sagittarius.

Sie besitzt keine eigene, unabhängig fortschreitende Spielzeit.

## 16.2 Raumflotten

Flottenbewegungen werden anhand der aktuellen Spielzeit beziehungsweise des tatsächlich fortgeschrittenen Reisevorgangs dargestellt.

Wird das Spiel pausiert, dürfen sich Flotten nicht unabhängig davon weiterbewegen.

## 16.3 Zeitbeschleunigung

Wird die Spielgeschwindigkeit erhöht, soll die Anzeige von Flottenbewegungen und Reisezeiten entsprechend reagieren.

## 16.4 Astronomische Sternpositionen

Die wissenschaftlichen Sternkoordinaten beziehen sich auf eine definierte astronomische Bezugsepoche.

Ob und in welchem Umfang die Eigenbewegung von Sternen über lange Spielzeiträume berücksichtigt wird, ist noch nicht abschließend festgelegt.

Die Galaxiekarte darf jedoch keine frei erfundenen Sternbewegungen erzeugen.

## 16.5 Keine planetare Orbitalbewegung

Die Galaxiekarte ist ausdrücklich nicht für die Bewegung von Planeten oder Monden zuständig.

Sie berechnet und visualisiert keine planetaren Umlaufbahnen.

Das entsprechende Verhalten gehört ausschließlich zur späteren eigenständigen Sternensystemansicht.

---

# 17. Große astronomische Datenbestände

## 17.1 Langfristige Zielsetzung

Die Galaxiekarte soll sehr große astronomische Sternpopulationen darstellen können.

Die langfristige Spielwelt orientiert sich an der Milchstraße.

## 17.2 Visuelle Skalierbarkeit

Nicht jeder vorhandene Stern muss bei jeder Zoomstufe mit sämtlichen Details angezeigt werden.

Die Kartendarstellung kann ihre Detailtiefe abhängig von Entfernung und Betrachtungssituation anpassen.

## 17.3 Unterschiedliche Detailstufen

Beispielsweise:

**Weite Übersicht**

Darstellung großer Sternregionen mit reduzierten Details.

**Regionale Ansicht**

Darstellung einzelner Sternpopulationen und wichtiger Systeme.

**Nahe Sternenansicht**

Detaillierte Markierungen, Sternnamen und Auswahlmöglichkeiten.

Alle Ansichten verwenden dieselben astronomischen Positionen.

## 17.4 Beschriftungsdichte

Die Anzahl sichtbarer Namen und Informationen wird an die aktuelle Zoomstufe angepasst.

Wichtige und ausgewählte Objekte werden bevorzugt dargestellt.

## 17.5 Unabhängigkeit von der Grafikdarstellung

Die Spielsimulation darf nicht davon abhängen, dass jeder Stern ständig als vollständiges grafisches Objekt geladen ist.

Die Darstellung muss auch bei großen Datenbeständen unabhängig vom eigentlichen Spielzustand arbeiten können.

## 17.6 Übersichtlichkeit

Die Karte soll nicht ausschließlich möglichst viele Sterne gleichzeitig anzeigen.

Ebenso wichtig ist, dass der Spieler räumliche Zusammenhänge erkennen und einzelne Systeme zuverlässig auswählen kann.

---

# 18. Spielstände und Kartenstatus

## 18.1 Astronomische Datenbasis

Die Galaxiekarte verwendet einen definierten Stand der astronomischen Datenbasis.

Ein Spielstand muss nachvollziehbar auf den verwendeten Datenstand Bezug nehmen können.

## 18.2 Kartenposition

Der aktuelle Kamerastandort soll wiederherstellbar sein.

Dazu gehören gegebenenfalls:

- Kameraposition.
- Kamerarichtung.
- Zoomstufe.
- Aktueller Fokuspunkt.
- Ausgewähltes Sternensystem.

## 18.3 Kartenfilter

Die aktuell ausgewählten Informationsfilter können als Teil des Benutzerzustands gespeichert werden.

## 18.4 Markierungen

Vom Spieler gesetzte Favoriten und strategische Kartenmarkierungen sollen dauerhaft erhalten bleiben können.

## 18.5 Spielzustand

Die Galaxiekarte übernimmt aktuelle Informationen über:

- Fraktionen.
- Kolonien.
- Flotten.
- Sprungtore.
- Transportlinien.
- Erkundung.
- Navigationsaufträge.

Die Zuständigkeit für diese Daten verbleibt bei den entsprechenden Spielsystemen.

## 18.6 Konsistenz

Nach dem Laden eines Spielstands müssen Sternpositionen, sichtbare Systemmarkierungen und strategische Informationen mit dem gespeicherten Spielzustand übereinstimmen.

---

# 19. Beispiel einer Kartenbedienung

Der Spieler öffnet die Galaxiekarte.

Die Milchstraße wird als dreidimensionaler Sternenraum dargestellt.

Ein dunkler Hintergrund, räumliche Sternmarkierungen, ein optionales Orientierungsgitter und eine technisch wirkende Benutzeroberfläche bilden die Kartenansicht.

Der Spieler bewegt die Kamera durch den Raum.

Er dreht und neigt die Karte, um die räumliche Verteilung der Sterne zu betrachten.

Anschließend verwendet er die Suchfunktion, um ein bestimmtes Sternensystem zu finden.

Das System wird auf der Karte hervorgehoben.

Die Kamera richtet sich auf den ausgewählten Stern aus.

Im Informationsbereich erscheinen die verfügbaren astronomischen Eigenschaften und strategischen Daten.

Der Spieler aktiviert anschließend den politischen Kartenfilter.

Die kontrollierten Sternensysteme verschiedener Fraktionen werden entsprechend hervorgehoben.

Danach schaltet er auf den Navigationsfilter um.

Er wählt ein Zielsystem aus und lässt eine Route berechnen.

Die Karte zeigt den Verlauf der Route durch den dreidimensionalen Sternenraum.

Vorhandene und zugängliche Sprungtore werden berücksichtigt.

Die voraussichtliche Reisezeit wird angezeigt.

Der Spieler kann die Kamera währenddessen weiterhin drehen, neigen und zoomen, um den Verlauf der Route aus verschiedenen Perspektiven zu betrachten.

Anschließend aktiviert er den Transportfilter.

Die Karte zeigt die tatsächlich betriebenen interstellaren Transportverbindungen.

Dabei werden mögliche Flugrouten und aktive Transportschiffverbindungen klar unterschieden.

**Dieser Ablauf beschreibt ausschließlich die Galaxiekarte.**

Die Darstellung eines einzelnen Sternensystems, seiner Planeten und Umlaufbahnen ist nicht Bestandteil dieses Ablaufs.

---

# 20. Verbindliche Festlegungen

Für die Galaxiekarte gelten folgende verbindliche Anforderungen.

## 20.1 Grundaufbau

1. Die Map ist ausschließlich eine Galaxiekarte.
2. Sie stellt die Milchstraße dreidimensional dar.
3. Reale astronomische Sternpositionen bilden die Grundlage.
4. Tatsächliche dreidimensionale Sternentfernungen werden berücksichtigt.
5. Die dritte Dimension muss für den Spieler räumlich erkennbar sein.
6. Sternensysteme sind eigenständige galaktische Kartenobjekte.

## 20.2 Elite-Dangerous-Orientierung

7. Die Galaxiekarte von Elite Dangerous ist die verbindliche visuelle Referenz.
8. Die grundlegende räumliche Darstellung soll sich eng an Elite Dangerous orientieren.
9. Die Kameraführung soll ein vergleichbares Bediengefühl bieten.
10. Zoomen, Drehen, Neigen, Verschieben und Fokussieren sollen sich an dieser Bedienphilosophie orientieren.
11. Orientierungsgitter und räumliche Hilfslinien sind Bestandteil des vorgesehenen Kartenstils.
12. Sternenauswahl, Suchfunktionen, Informationsfenster und Kartenfilter sollen sich an der entsprechenden Bedienlogik orientieren.
13. Die Darstellung soll dunkel, technisch-futuristisch und räumlich übersichtlich sein.
14. Project Sagittarius erhält eine eigenständige grafische Identität und verwendet keine übernommenen Elite-Dangerous-Assets.

## 20.3 Funktionale Zuständigkeit

15. Die Map zeigt ausschließlich die galaktische Ebene.
16. Die Sternensystemansichten sind eigenständige Spielsysteme.
17. Die Map stellt keine planetaren Umlaufbahnen dar.
18. Die Map simuliert keine Planeten- oder Mondbewegungen.
19. Die Map enthält keine planetare Kachelverwaltung.
20. Die Map enthält keine detaillierte lokale Sternensystemkamera.
21. Eine spätere Anbindung anderer Ansichten bleibt möglich, wird hier jedoch nicht spezifiziert.

## 20.4 Daten

22. Wissenschaftliche Sterninformationen werden von der astronomischen Datenbasis bereitgestellt.
23. Die Herkunft astronomischer Daten bleibt nachvollziehbar.
24. Wissenschaftliche und generierte Informationen dürfen nicht verwechselt werden.
25. Sternpositionen bleiben unabhängig von der visuellen Symbolgröße erhalten.
26. Astronomische Daten, Spielzustand und grafische Darstellung bleiben voneinander getrennt.

## 20.5 StellarForge

27. StellarForge gehört nicht zum Umfang der Galaxiekarte.
28. Die Funktionsweise von StellarForge wird später in einem eigenen Konzeptdokument beschrieben.
29. Die Galaxiekarte muss ihre grundlegenden Aufgaben unabhängig von StellarForge erfüllen können.

## 20.6 Navigation

30. Die Galaxiekarte stellt interstellare Navigationsinformationen dar.
31. Die Navigation verwendet tatsächliche dreidimensionale Sternentfernungen.
32. Warpantriebe besitzen neun Geschwindigkeitsstufen.
33. Eine gemeinsam reisende Flotte richtet sich nach ihrem langsamsten Schiff.
34. Sprungtore werden von Fraktionen errichtet.
35. Zugängliche Sprungtorpassagen benötigen keine Spielzeit.
36. Eigene, befreundete und verbündete Sprungtore dürfen entsprechend den geltenden Rechten verwendet werden.
37. Warpstrecken und Sprungtorpassagen dürfen innerhalb derselben Route kombiniert werden.
38. Eine technisch mögliche Flugroute ist nicht automatisch eine aktiv betriebene Transportverbindung.

## 20.7 Strategische Darstellung

39. Fraktionsgebiete können auf der Galaxiekarte dargestellt werden.
40. Kolonien und wichtige Sternensysteme können markiert werden.
41. Flotten können als bewegliche galaktische Kartenobjekte dargestellt werden.
42. Aktive Transportverbindungen können angezeigt werden.
43. Kartenfilter verändern die Informationsdarstellung, nicht die astronomischen Positionen.
44. Die Galaxiekarte soll langfristig große astronomische Datenbestände unterstützen.

---

# 21. Offene konzeptionelle Entscheidungen

Die folgenden Punkte sind noch nicht abschließend festgelegt.

## 21.1 Vollständiger Umfang der Milchstraße

Wie groß soll der tatsächlich bespielbare Raum sein?

Die langfristige Zielsetzung ist eine möglichst umfangreiche Milchstraßendarstellung.

Die konkreten Grenzen bleiben offen.

## 21.2 Sichtbarkeit unbekannter Sterne

Sollen alle katalogisierten Sternpositionen von Beginn an sichtbar sein?

Oder sollen bestimmte Sterne und Regionen erst durch Erkundung freigeschaltet werden?

Eine Trennung zwischen bekannter Sternposition und unbekannten Systemeigenschaften ist möglich.

## 21.3 Stellare Eigenbewegung

Sollen Sterne über lange Spielzeiträume ihre wissenschaftlich bekannte Eigenbewegung berücksichtigen?

Die konkrete Regel bleibt offen.

## 21.4 Sternsymbole

Wie exakt sollen die Sternmarkierungen, Leuchteffekte und Auswahlrahmen gestaltet sein?

Die Elite-Dangerous-Orientierung ist verbindlich.

Die konkrete eigene Symbolgestaltung bleibt offen.

## 21.5 Farbpalette

Welche genauen Farben werden für Auswahl, Navigation, Fraktionen und Kartenfilter verwendet?

Die grundsätzliche visuelle Richtung ist festgelegt.

## 21.6 Kamerabedienung

Welche Mausaktionen und Tastenkombinationen werden für Drehen, Verschieben, Zoomen und Fokussieren verwendet?

Das Bediengefühl soll Elite Dangerous entsprechen.

Die genaue Eingabebelegung wird später definiert.

## 21.7 Informationsfenster

Wie werden die einzelnen Informationsbereiche räumlich angeordnet?

Welche Informationen sollen jederzeit und welche nur nach Auswahl sichtbar sein?

## 21.8 Politische Gebiete

Wie werden dreidimensionale Fraktionsgrenzen grafisch dargestellt?

Die Darstellung muss die räumliche Verteilung der Sternensysteme berücksichtigen.

## 21.9 Warp-Verbindungen

Welche Sternensysteme dürfen unmittelbar per Warp erreicht werden?

Soll eine maximale Einzelstrecke existieren?

Diese Regeln werden im eigenständigen Raumfahrtkonzept festgelegt.

## 21.10 Kartendichte

Wie sollen extrem dichte Sterngebiete dargestellt werden, ohne die Auswahl einzelner Sterne zu erschweren?

## 21.11 Darstellung beweglicher Flotten

Wie detailliert werden Flotten während interstellarer Reisen visualisiert?

Die Position muss dem tatsächlichen Reisefortschritt entsprechen.

Die genaue grafische Gestaltung bleibt offen.

---

# 22. Zusammenfassung

Die Galaxiekarte von Project Sagittarius ist ein eigenständiges strategisches Spielsystem.

Sie stellt die Milchstraße als realen dreidimensionalen Sternenraum dar.

Die Sternpositionen basieren möglichst auf wissenschaftlich dokumentierten astronomischen Daten.

Die tatsächlichen räumlichen Entfernungen bilden die Grundlage für die interstellare Navigation.

**Die Darstellung, Bedienung und das allgemeine Look & Feel orientieren sich ausdrücklich an der Galaxiekarte von Elite Dangerous.**

Besonders wichtig sind:

- Eine räumlich glaubwürdige 3D-Sternenkarte.
- Ein dunkler, technisch-futuristischer Stil.
- Ein Orientierungsgitter mit räumlichen Referenzlinien.
- Freie und präzise Kamerasteuerung.
- Flüssiges Zoomen, Drehen und Neigen.
- Eindeutige Auswahl und Fokussierung von Sternensystemen.
- Suchfunktionen.
- Astronomische und strategische Informationsansichten.
- Interstellare Routenplanung.
- Die Darstellung von Sprungtoren, Flotten und Transportverbindungen.

Die Galaxiekarte zeigt ausschließlich die galaktische Ebene.

**Die dreidimensionalen Sternensystemansichten sind unabhängig davon und erhalten ein eigenes Konzept.**

Innerhalb der Galaxiekarte werden keine Planetenumlaufbahnen, Monde oder lokalen Sternensystembewegungen dargestellt beziehungsweise berechnet.

**StellarForge ist ebenfalls kein Bestandteil der Galaxiekarte und erhält später ein eigenständiges Konzeptdokument.**

Die Galaxiekarte soll als eigenständiges System bestehen können und später die benötigten Informationen aus anderen Spielsystemen übernehmen.

Dieses Dokument beschreibt ausschließlich das fachliche Spielkonzept der Galaxiekarte. Es enthält keinen Entwicklungsplan, keinen Implementierungsplan und keine technische Aufgabenliste.

**Dokumentversion: 0.3**

---

# Referenzen

## Astronomische Quellen

- [ESA Gaia Archive](https://gea.esac.esa.int/archive/)
- [ESA Gaia](https://www.esa.int/Science_Exploration/Space_Science/Gaia)
- [Hipparcos-Kataloge](https://www.cosmos.esa.int/web/hipparcos)

## Visuelle und funktionale Referenz

- [Elite Dangerous – Offizielle Website](https://www.elitedangerous.com/)

Elite Dangerous dient als Referenz für die Darstellung, Bedienung und räumliche Navigation der Galaxiekarte.

Project Sagittarius erhält eine eigenständige grafische Gestaltung und verwendet keine übernommenen Originalassets.

## Projektbezug

- [Project Sagittarius – GitHub-Repository](https://github.com/Drezael/project_sagittarius)
- [README](../../../readme.md)
- [Forschungskonzept](../../../project.md)

Die astronomischen Quellen sind als fachliche Datengrundlage vorgesehen. Datenqualität, konkrete Importverfahren und Nutzungsbedingungen werden gesondert behandelt.