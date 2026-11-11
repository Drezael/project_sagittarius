# Project Sagittarius – Konzept der Galaxiekarte

**Projekt:** Project Sagittarius / Sternenreiche  
**Dokument:** `docs/concept/map/map.md`  
**Dokumentversion:** 0.4  
**Stand:** 10. November 2026  
**Status:** Fachliches Spiel- und Darstellungskonzept  
**Geltungsbereich:** Ausschließlich die dreidimensionale Galaxiekarte der Milchstraße

---

# 1. Grundidee

Die Galaxiekarte ist die zentrale astronomische, räumliche und strategische Übersicht von Project Sagittarius.

Sie stellt die Milchstraße als zusammenhängenden, dreidimensionalen Raum dar. Der Spieler kann sich frei innerhalb dieses Raums bewegen, Sternensysteme betrachten, suchen, auswählen und interstellare Reisen planen.

Die Karte soll wie ein fortschrittliches astronomisches Navigations- und Kartografiesystem wirken.

Im Vordergrund stehen die räumliche Glaubwürdigkeit, eine intuitive Kamerasteuerung und eine klare Informationsdarstellung.

Anders als eine klassische zweidimensionale Strategiespielkarte bildet die Galaxiekarte keine künstlich angeordneten Sternpunkte auf einer flachen Ebene ab. Die Sterne besitzen echte dreidimensionale Positionen.

Der Spieler betrachtet ihre räumliche Verteilung aus einer frei veränderbaren Perspektive.

## 1.1 Grundlegende Eigenschaften

Die Galaxiekarte soll folgende Merkmale besitzen:

- Einen frei navigierbaren dreidimensionalen Sternenraum.
- Wissenschaftlich begründete Sternpositionen und Entfernungen.
- Eine kontinuierliche Kamerabewegung von einzelnen Sternregionen bis zur gesamten Milchstraße.
- Eine dunkle, realistisch wirkende astronomische Darstellung.
- Tausende beziehungsweise langfristig wesentlich mehr sichtbare Sternmarkierungen.
- Sternfarben entsprechend ihren bekannten astrophysikalischen Eigenschaften.
- Eine zuschaltbare horizontale Koordinatenebene.
- Vertikale Projektionslinien zwischen Sternpositionen und der Koordinatenebene.
- Eine frei drehbare und neigbare Kamera.
- Direkt auswählbare Sternensysteme.
- Klare Fokus-, Auswahl- und Zielmarkierungen.
- Kontextbezogene Bedienaktionen.
- Suchfunktionen für Sternnamen und Katalogkennungen.
- Astronomische, politische und wirtschaftliche Kartenfilter.
- Dreidimensionale Routenvisualisierung.
- Darstellung von Sprungtoren, Flotten und Transportnetzwerken.
- Eine kompakte, technisch-futuristische Benutzeroberfläche.

## 1.2 Astronomische Karte als Ausgangszustand

Der grundlegende Zustand der Galaxiekarte ist eine astronomische Ansicht.

In dieser Ansicht stehen die Sterne und ihre räumliche Verteilung im Vordergrund.

Politische Gebiete, wirtschaftliche Daten und interstellare Verkehrsnetze werden nicht dauerhaft über sämtliche Sterne gezeichnet.

Diese Informationen können gezielt über unterschiedliche Kartenmodi eingeblendet werden.

Dadurch bleibt die eigentliche Galaxie jederzeit erkennbar.

## 1.3 Eigenständigkeit

Die Galaxiekarte ist ausschließlich für die galaktische Ebene zuständig.

Sie bildet keine einzelnen planetaren Umlaufbahnen ab und enthält keine lokale Darstellung der Planeten eines Sternensystems.

Ein Sternensystem wird auf dieser Karte als zusammengehöriges galaktisches Objekt behandelt.

Die detaillierte Sternensystemansicht ist ein eigenständiges Spielsystem und erhält ein eigenes Konzept.

Die Galaxiekarte muss unabhängig von der lokalen Sternensystemdarstellung funktionieren.

## 1.4 Abgrenzung zur Planetenverwaltung

Die Galaxiekarte enthält keine planetaren Kachelraster und keine Gebäudeansicht.

Kolonien können als strategische Informationen eines Sternensystems angezeigt werden.

Die eigentliche Verwaltung von Gebäuden, Bevölkerung, Bildung, Nahrung, Energie und Produktion findet außerhalb der Galaxiekarte statt.

## 1.5 Abgrenzung zur Weltgenerierung

Die Galaxiekarte erhält ihre astronomischen Objekte aus einer eigenständigen Datenbasis.

Die Erstellung zusätzlicher oder fiktiver astronomischer Objekte ist nicht Teil dieses Dokuments.

StellarForge wird zu einem späteren Zeitpunkt als eigenes Konzept behandelt.

---

# 2. Grundlegender Bildschirmaufbau

## 2.1 Zentrale Kartenfläche

Der überwiegende Teil des Bildschirms wird von der dreidimensionalen Galaxie eingenommen.

Die Sterne bilden dabei die Hauptdarstellung.

Informationsfenster sollen möglichst wenig Sichtfläche verdecken.

Der Spieler soll die Karte auch dann betrachten und bedienen können, wenn zusätzliche Informationsbereiche geöffnet sind.

## 2.2 Aufbau der Benutzeroberfläche

Die Kartenoberfläche besteht grundsätzlich aus fünf Bereichen.

| Bildschirmbereich | Funktion |
|---|---|
| Mitte | Frei navigierbarer dreidimensionaler Sternenraum |
| Links | Schmale vertikale Funktionsleiste und bei Bedarf ausgeklappte Menüs |
| Oben | Suchfeld und kompakte Karteninformationen |
| Rechts | Informationen zum ausgewählten Sternensystem oder strategischen Objekt |
| Unten | Navigationsstatus, aktuelle Position, Route und Bedienhinweise |

Die Informationsbereiche liegen über der 3D-Karte.

Sie dürfen den räumlichen Kartenausschnitt nicht vollständig ersetzen.

## 2.3 Linke Funktionsleiste

Am linken Bildschirmrand befindet sich eine schmale vertikale Leiste mit Symbolen.

Diese dient als Hauptnavigation innerhalb der Galaxiekarte.

Vorgesehene Funktionsgruppen:

- Astronomische Kartenansicht.
- Suche.
- Favoriten und gespeicherte Positionen.
- Eigene Flotten.
- Aktive Navigationsaufträge.
- Kartenfilter.
- Politische Informationen.
- Wirtschafts- und Transportinformationen.
- Routenplanung.
- Karteneinstellungen.

Durch Auswahl eines Symbols öffnet sich der entsprechende Informationsbereich seitlich.

Die Symbolleiste selbst bleibt kompakt.

## 2.4 Ausklappbare Menüs

Ein geöffnetes Menü erscheint unmittelbar neben der linken Funktionsleiste.

Darin können weitere Einstellungen, Kategorien und Filter enthalten sein.

Die Menüs sollen:

- Eine klare Überschrift besitzen.
- Einzelne Kategorien ein- und ausklappen können.
- Kontrollkästchen für Filter anbieten.
- Eine verständliche Hierarchie verwenden.
- Bei Bedarf scrollbar sein.
- Wieder geschlossen werden können.

Ein Wechsel des Menüs darf die Position oder Ausrichtung der Kamera nicht verändern.

## 2.5 Zentrales Suchfeld

Im oberen Bereich der Karte befindet sich ein Suchfeld.

Dieses soll schnell erreichbar sein und eine Suche innerhalb der gesamten verfügbaren astronomischen Datenbasis ermöglichen.

Während einer Eingabe können passende Treffer in einem aufklappbaren Bereich erscheinen.

Das Suchfeld darf die Kartendarstellung nicht unnötig verdecken.

## 2.6 Rechtes Informationsfenster

Wird ein Sternensystem ausgewählt, kann rechts ein Informationsfenster erscheinen.

Dieses zeigt die wichtigsten astronomischen und strategischen Eigenschaften.

Die Informationen werden in klar voneinander getrennte Bereiche gegliedert.

Beispielsweise:

- Sternensystem.
- Entfernung.
- Astronomische Eigenschaften.
- Politische Zugehörigkeit.
- Wirtschaft.
- Besiedlung.
- Infrastruktur.
- Navigationsaktionen.

## 2.7 Untere Statusleiste

Am unteren Bildschirmrand wird eine schmale Statusleiste vorgesehen.

Diese kann abhängig vom aktuellen Kartenmodus anzeigen:

- Aktuelles Bezugssystem.
- Ausgewähltes Sternensystem.
- Aktuelles Navigationsziel.
- Nächste Zwischenstation.
- Anzahl der verbleibenden Reiseabschnitte.
- Gesamte Reisezeit.
- Aktiver Kartenmodus.
- Bedienhinweise.

## 2.8 Kontextmenü an Sternen

Neben einem ausgewählten Stern kann zusätzlich ein kleines schwebendes Bedienfeld erscheinen.

Dieses ist direkt mit der Position des Sterns in der Bildschirmansicht verbunden.

Es enthält nur die wichtigsten Aktionen.

Vorgesehen sind:

- System fokussieren.
- Als Navigationsziel festlegen.
- Route berechnen.
- Als Favorit speichern.
- Informationen anzeigen.

Die verfügbaren Aktionen können vom aktuellen Spielzustand abhängen.

## 2.9 Transparenz und Abstände

Die Informationsfenster sollen überwiegend dunkel und leicht transparent sein.

Schmale Rahmen und dezente Trennlinien unterteilen die Inhalte.

Die hinter den Fenstern liegende Sternenkarte darf teilweise sichtbar bleiben, sofern die Lesbarkeit gewährleistet ist.

---

# 3. Die dreidimensionale Milchstraße

## 3.1 Räumliche Darstellung

Die gesamte Galaxiekarte ist ein zusammenhängender dreidimensionaler Raum.

Jedes Sternensystem besitzt eine feste räumliche Position.

Die Position kann durch drei Koordinaten beschrieben werden.

Die Darstellung der Sterne richtet sich nach diesen Koordinaten.

Eine künstliche gleichmäßige Verteilung der Sterne auf einer flachen Karte ist nicht vorgesehen.

## 3.2 Sternenverteilung

Die Sterne sollen so verteilt sein, dass ihre räumlichen Beziehungen zueinander den vorhandenen astronomischen Informationen entsprechen.

Bekannte Sterne werden anhand ihrer tatsächlichen Positionen dargestellt.

Die Karte darf ihre Positionen nicht zur besseren Bedienbarkeit oder aus optischen Gründen verändern.

## 3.3 Galaktische Gesamtansicht

Bei ausreichender Entfernung wird die gesamte Milchstraße sichtbar.

Die Darstellung soll folgende großräumige Eigenschaften erkennen lassen:

- Eine deutlich ausgeprägte galaktische Scheibe.
- Ein verdichtetes galaktisches Zentrum.
- Räumlich erkennbare Spiralarmstrukturen.
- Unterschiede in der Sternendichte.
- Dunkle Bereiche zwischen sichtbaren Sternpopulationen.
- Staub- und Nebelstrukturen.
- Außenbereiche der Galaxie.

Die großräumige Darstellung soll nicht wie ein flaches Hintergrundbild wirken.

Der Spieler kann die gesamte Galaxie drehen, neigen und aus verschiedenen Richtungen betrachten.

## 3.4 Sicht auf die galaktische Scheibe

Aus einer flachen Perspektive erscheint die Milchstraße als längliches, dichtes Sternenband.

Aus einer stärker geneigten Perspektive werden ihre räumliche Ausdehnung und die Spiralstruktur deutlicher.

Der Spieler kann zwischen diesen Perspektiven frei wechseln.

## 3.5 Galaktisches Zentrum

Das Zentrum der Milchstraße bildet einen räumlichen Orientierungspunkt.

Es darf visuell durch eine höhere Sternendichte und stärkere Hintergrundhelligkeit hervorgehoben werden.

Das Zentrum soll nicht so stark leuchten, dass andere wichtige Elemente der Karte unkenntlich werden.

## 3.6 Regionale Sternenansicht

Bei der Annäherung an eine galaktische Region werden einzelne Sternpopulationen zunehmend erkennbar.

Die Darstellung verändert sich kontinuierlich.

Aus einem großräumigen Sternenband entsteht eine räumliche Verteilung einzelner Sternmarkierungen.

Die lokale Ansicht soll ein deutliches Gefühl für die Entfernungen zwischen Sternen vermitteln.

## 3.7 Lokale Sternenansicht

Bei stärkerem Heranzoomen stehen einzelne Sternensysteme im Vordergrund.

Der Spieler soll die Positionen benachbarter Systeme erkennen und diese auswählen können.

Namen, Markierungen und Projektionslinien werden in dieser Ansicht stärker hervorgehoben.

## 3.8 Kontinuierlicher Maßstabswechsel

Der Wechsel von einer lokalen Sternenregion bis zur Gesamtgalaxie erfolgt durch kontinuierliches Zoomen.

Es wird dafür keine separate zweidimensionale Gesamtgalaxiekarte geöffnet.

Die Kamera bleibt innerhalb desselben logischen galaktischen Raums.

Die jeweils sichtbaren Details passen sich an die Entfernung an.

## 3.9 Hintergrunddarstellung

Die Karte erhält eine zurückhaltende astronomische Hintergrunddarstellung.

Diese kann enthalten:

- Entfernte Sternpopulationen.
- Lichtschwache Sternwolken.
- Staubstrukturen.
- Galaktische Nebel.
- Diffuse Lichtverteilungen.

Der Hintergrund unterstützt die Orientierung und die Atmosphäre.

Er darf nicht mit tatsächlich auswählbaren Sternensystemen verwechselt werden.

## 3.10 Keine künstlichen Sternverbindungen

Zwischen gewöhnlichen Sternen werden nicht automatisch dauerhaft Verbindungslinien gezeichnet.

Solche Linien würden die Karte unnötig überladen und eine künstliche Netzstruktur vortäuschen.

Verbindungslinien erscheinen nur dann, wenn sie eine definierte Bedeutung haben.

Beispiele:

- Geplante Navigationsroute.
- Aktive Transportverbindung.
- Zugängliche Sprungtorverbindung.
- Besondere strategische Beziehung.
- Räumliche Orientierungshilfe.

---

# 4. Darstellung einzelner Sternensysteme

## 4.1 Sternmarkierungen

Ein Sternensystem erscheint als leuchtender Punkt im dreidimensionalen Raum.

Abhängig von seiner Entfernung zur Kamera kann es als kleiner Lichtpunkt oder als deutlich sichtbare Sternmarkierung dargestellt werden.

Die Position der Markierung entspricht der galaktischen Position des Systems.

## 4.2 Farbgebung

Die Grundfarbe eines Sterns richtet sich nach den verfügbaren astronomischen Daten.

Vorgesehen ist folgende allgemeine Zuordnung:

| Sternklasse | Vorherrschende Darstellung |
|---|---|
| O | Blau |
| B | Blauweiß |
| A | Weiß bis blauweiß |
| F | Weißlich |
| G | Warmweiß bis gelblich |
| K | Orange |
| M | Rot bis orange-rot |

Die genaue Darstellung kann innerhalb der wissenschaftlichen Datenlage abgestimmt werden.

## 4.3 Helligkeit

Die sichtbare Helligkeit unterscheidet einzelne Sterne.

Sie muss so angepasst werden können, dass auch schwächere Sterne bei geeigneter Zoomstufe erkennbar bleiben.

Die sichtbare Markierungsgröße ist nicht mit dem tatsächlichen Sternradius gleichzusetzen.

## 4.4 Leuchteffekte

Die Sterne besitzen dezente Leuchteffekte.

Diese sollen:

- Die Lichtwirkung unterstützen.
- Sternfarben erkennbar machen.
- Die räumliche Tiefe hervorheben.
- Die Auswahl erleichtern.

Übermäßig große Lichtreflexe oder stark überzeichnete Strahlen sollen vermieden werden.

## 4.5 Sternnamen

Nicht jeder sichtbare Stern erhält jederzeit eine Beschriftung.

Die Anzahl der eingeblendeten Namen hängt unter anderem ab von:

- Zoomstufe.
- Entfernung.
- Aktuellem Kartenmodus.
- Bedeutung des Systems.
- Auswahlstatus.
- Verfügbarem Bildschirmplatz.

Ausgewählte und wichtige Sternensysteme dürfen bevorzugt beschriftet werden.

## 4.6 Räumliche Beschriftung

Die Beschriftung eines Sternensystems soll visuell an dessen Position gebunden sein.

Bei Kamerabewegungen folgt die Beschriftung der Position des Sterns auf dem Bildschirm.

Dabei muss sie ausreichend lesbar bleiben.

## 4.7 Mehrfachsternsysteme

Doppel- und Mehrfachsternsysteme werden grundsätzlich als zusammengehörige galaktische Kartenobjekte behandelt.

Ihre einzelnen Sternkomponenten können im Informationsfenster aufgeführt werden.

Die detaillierte Darstellung der lokalen Sternkonfiguration erfolgt nicht auf der Galaxiekarte.

## 4.8 Strategische Markierungen

Ein Stern kann zusätzliche Kennzeichnungen besitzen.

Beispiele:

- Besiedelt.
- Hauptstadt.
- Wichtige Industrie.
- Bedeutendes Forschungssystem.
- Sprungtor vorhanden.
- Militärstützpunkt.
- Geplantes Ziel.
- Favorit.

Die Markierungen werden nur angezeigt, wenn sie für den aktuellen Kartenmodus relevant sind.

---

# 5. Orientierungsgitter und Referenzebene

## 5.1 Grundprinzip

Die Galaxiekarte erhält eine horizontale Koordinatenebene.

Diese wird als perspektivisches Gitter dargestellt.

Das Gitter dient der räumlichen Orientierung innerhalb der dreidimensionalen Sternenverteilung.

Es ist kein physikalischer Bestandteil der Spielwelt.

## 5.2 Erscheinungsbild

Das Gitter besteht aus dünnen, zurückhaltenden Linien.

Als Grundgestaltung werden dunkle Blau-, Grau- oder Cyan-Töne vorgesehen.

Die Linien sollen aus der Nähe gut erkennbar sein, aber die Sternenkarte nicht dominieren.

## 5.3 Perspektivische Darstellung

Das Gitter wird entsprechend der Kameraperspektive dargestellt.

Bei einer flachen Kameraposition erscheint es stark perspektivisch verkürzt.

Bei einer Draufsicht ist seine Rasterstruktur deutlicher erkennbar.

Beim Drehen und Neigen der Kamera verändert sich seine Darstellung zusammen mit dem Sternenraum.

## 5.4 Räumliche Referenz

Die Koordinatenebene liegt auf einer definierten Höhe des galaktischen Koordinatensystems.

Sternensysteme können oberhalb und unterhalb dieser Ebene liegen.

Die Referenzebene ist nicht die Untergrenze des Raums.

## 5.5 Projektionslinien

Zwischen einem Sternensystem und seiner senkrechten Projektion auf die Koordinatenebene kann eine vertikale Linie angezeigt werden.

Diese Linie macht den Abstand des Sterns von der Referenzebene sichtbar.

Die Projektionslinien sollen dünn und überwiegend halbtransparent dargestellt werden.

## 5.6 Projektionslinien bei vielen Sternen

In einer dichten Sternregion dürfen nicht alle Projektionslinien gleich stark erscheinen.

Die Darstellung soll abhängig von Zoomstufe und Informationsdichte angepasst werden.

Mögliche Abstufungen:

- Schwache Projektionslinien für gewöhnliche nahe Sterne.
- Deutlichere Linien für wichtige Systeme.
- Besonders hervorgehobene Linie für das ausgewählte System.
- Ausblendung unwichtiger Linien bei zu großer Dichte.

## 5.7 Projektionspunkte

An der Stelle, an der eine Projektionslinie das Gitter erreicht, kann ein kleiner Punkt erscheinen.

Für ausgewählte Systeme kann dieser Punkt durch einen Kreis hervorgehoben werden.

## 5.8 Koordinatenbeschriftung

Das Gitter kann numerische Markierungen entlang seiner Achsen besitzen.

Die Beschriftung soll die aktuelle Entfernungsskala berücksichtigen.

Die Einheit wird eindeutig angegeben.

## 5.9 Dynamische Rastergröße

Die Rasterabstände passen sich der aktuellen Betrachtungsgröße an.

Bei kleinen Sternregionen werden feinere Rasterabstände angezeigt.

Bei großen Regionen werden gröbere Rasterabstände verwendet.

Die numerische Beschriftung muss dabei verständlich bleiben.

## 5.10 Ein- und Ausblendung

Der Spieler kann das Gitter jederzeit ein- oder ausblenden.

Ebenso sollen Projektionslinien bei Bedarf separat deaktivierbar sein.

Die astronomischen Sternpositionen bleiben davon unverändert.

---

# 6. Kamerasteuerung

## 6.1 Grundlegendes Verhalten

Die Kamera bewegt sich frei im dreidimensionalen galaktischen Raum.

Der Spieler kann die Sternenverteilung aus nahezu beliebigen Blickrichtungen betrachten.

Die Kamera darf nicht dauerhaft auf eine starre Draufsicht beschränkt sein.

## 6.2 Fokuspunkt

Die Kamera besitzt einen aktuellen Bezugspunkt.

Dieser kann eine frei gewählte Position oder ein ausgewähltes Sternensystem sein.

Bei einer Rotation bewegt sich die Kamera um diesen Fokuspunkt.

## 6.3 Horizontale Rotation

Die Kamera kann um die vertikale Achse des Fokuspunktes gedreht werden.

Dadurch verschiebt sich die sichtbare Anordnung der Sterne.

Der Spieler kann so räumliche Abstände erkennen, die aus einer vorherigen Perspektive nicht sichtbar waren.

## 6.4 Vertikale Neigung

Die Kamera kann nach oben und unten geneigt werden.

Dadurch kann der Spieler von einer flachen Ansicht auf die Sterne zu einer stärkeren Draufsicht wechseln.

Die Veränderung erfolgt flüssig und ohne abrupte Perspektivwechsel.

## 6.5 Freie Verschiebung

Der Spieler kann den Kamerafokus innerhalb des galaktischen Raums verschieben.

Damit lassen sich Sternregionen unabhängig von einer bestehenden Auswahl erkunden.

## 6.6 Zoom

Die Karte besitzt einen großen kontinuierlichen Zoombereich.

Der Spieler soll aus einer lokalen Sternregion herauszoomen können, bis die gesamte Milchstraße sichtbar ist.

Umgekehrt soll er aus der Gesamtgalaxie wieder bis zu einzelnen Sternensystemen heranzoomen können.

## 6.7 Großräumige Kamerafahrten

Die Kamera kann sich auch über sehr große astronomische Distanzen bewegen.

Bei der Auswahl eines weit entfernten Ziels soll eine geeignete Kamerafahrt möglich sein.

Der Übergang muss nachvollziehbar bleiben und darf nicht den Eindruck erwecken, dass die Karte gewechselt wird.

## 6.8 Entfernung und Bewegungsgeschwindigkeit

Die Kamerabewegung muss zur aktuellen Entfernungsskala passen.

Bei der Betrachtung der gesamten Milchstraße sind wesentlich größere Bewegungen erforderlich als in einer lokalen Sternregion.

Die Steuerung soll deshalb über den gesamten Zoombereich sinnvoll bedienbar bleiben.

## 6.9 Auswahl und Zentrierung

Die Auswahl eines Sternensystems und das Zentrieren der Kamera sind getrennte Funktionen.

Ein Stern kann ausgewählt werden, ohne dass die Kamera sofort ihre Position verändert.

Der Spieler kann anschließend ausdrücklich eine Fokussierung auslösen.

## 6.10 Fokusbewegung

Wird ein Sternensystem fokussiert, bewegt sich die Kamera zu einer geeigneten Betrachtungsposition.

Die Bewegung soll weich verlaufen.

Der ausgewählte Stern wird währenddessen weiterhin eindeutig markiert.

## 6.11 Rückkehr

Der Spieler kann zu vorherigen Positionen zurückkehren.

Zusätzlich sind direkte Fokusfunktionen für wichtige Systeme vorgesehen.

Beispiele:

- Sonnensystem.
- Hauptstadt.
- Aktuelle eigene Flotte.
- Gespeicherter Favorit.
- Letztes Navigationsziel.

## 6.12 Kontinuität

Kartenfilter dürfen die Kameraposition nicht verändern.

Auch das Öffnen oder Schließen eines Informationsfensters darf nicht automatisch zu einer unerwarteten Kamerabewegung führen.

---

# 7. Bedienung und Interaktion

## 7.1 Eingabegeräte

Die Galaxiekarte wird vorrangig für Maus und Tastatur konzipiert.

Eine spätere Unterstützung weiterer Eingabegeräte bleibt möglich.

## 7.2 Maussteuerung

Die Maus übernimmt grundlegende Interaktionen:

- Stern auswählen.
- Karte drehen.
- Kamera neigen.
- Ansicht verschieben.
- Zoomen.
- Kontextaktionen auslösen.
- Filter bedienen.
- Routenpunkte auswählen.

Die endgültige Belegung der Maustasten wird separat festgelegt.

## 7.3 Tastatursteuerung

Die Tastatur ermöglicht zusätzliche Bedienaktionen.

Beispiele:

- Kamera vorwärts und rückwärts bewegen.
- Kamera seitlich verschieben.
- Vertikale Bewegung.
- Suche öffnen.
- Auswahl fokussieren.
- Filtermenü öffnen.
- Routenplanung aktivieren.
- Gitter umschalten.
- Zu einer vorherigen Position zurückkehren.

## 7.4 Trennung der Eingaben

Eine Kamerabewegung darf nicht versehentlich einen Stern auswählen.

Die Interaktion muss zwischen Ziehen, Klicken und anderen Eingaben unterscheiden können.

## 7.5 Kontextabhängige Bedienung

Die verfügbaren Aktionen passen sich dem aktuellen Zustand an.

Beim ausgewählten Sternensystem werden beispielsweise System- und Navigationsaktionen angeboten.

Bei einer ausgewählten Flotte werden stattdessen flottenbezogene Informationen und Aktionen angezeigt.

## 7.6 Bedienhinweise

Eine schmale Leiste am unteren Bildschirmrand kann die wichtigsten Eingaben anzeigen.

Die Hinweise ändern sich abhängig von der aktiven Funktion.

---

# 8. Auswahlmarkierungen und Fokus

## 8.1 Grundlegende Zustände

Sternensysteme können unterschiedliche Interaktionszustände besitzen.

Mindestens vorgesehen sind:

- Nicht ausgewählt.
- Durch Mauszeiger hervorgehoben.
- Ausgewählt.
- Kamerafokus.
- Aktuelle Referenzposition.
- Navigationsziel.
- Zwischenstation.
- Favorit.

Diese Zustände sind logisch voneinander getrennt.

## 8.2 Normale Sternmarkierung

Ein gewöhnlicher Stern besitzt zunächst lediglich seine astronomische Darstellung.

Er erhält keine dauerhaft auffällige strategische Markierung.

## 8.3 Hervorhebung durch den Mauszeiger

Beim Bewegen des Mauszeigers über einen auswählbaren Stern wird dieser kurz hervorgehoben.

Ein kleiner Hinweis kann den Systemnamen anzeigen.

## 8.4 Ausgewähltes Sternensystem

Nach der Auswahl erscheint eine deutlich erkennbare Markierung.

Diese kann bestehen aus:

- Einem inneren Ring.
- Vier kurzen äußeren Rahmenmarkierungen.
- Einer hervorgehobenen Beschriftung.
- Einer deutlicheren Projektionslinie.
- Einem kleinen Kontextmenü.

Die Auswahlmarkierung darf den Stern nicht verdecken.

## 8.5 Aktuelle Referenzposition

Die aktuelle spielerbezogene Referenzposition kann gesondert dargestellt werden.

Vorgesehen ist eine kreisförmige Markierung mit einem eindeutig erkennbaren Richtungssymbol.

Sie soll sich visuell von der Markierung eines beliebigen ausgewählten Systems unterscheiden.

## 8.6 Navigationsziel

Ein gesetztes Navigationsziel erhält eine besondere Markierung.

Diese muss auch dann erkennbar bleiben, wenn das Ziel nicht gleichzeitig das aktuell ausgewählte Sternensystem ist.

## 8.7 Mehrere Markierungen

Ein Sternensystem kann gleichzeitig verschiedene Eigenschaften besitzen.

Beispielsweise kann es:

- Eine eigene Kolonie enthalten.
- Ein Sprungtor besitzen.
- Als Favorit gespeichert sein.
- Ziel einer Reise sein.

Die Darstellung darf deshalb nicht für jede Eigenschaft einen gleichwertigen großen Rahmen um den Stern zeichnen.

Stattdessen werden Prioritäten und kompakte Zusatzsymbole verwendet.

## 8.8 Räumliche Verankerung

Auswahlmarkierungen und Beschriftungen bleiben an die projizierte Bildschirmposition des entsprechenden 3D-Objekts gebunden.

Wenn die Kamera bewegt wird, folgen sie der sichtbaren Sternposition.

## 8.9 Verhalten bei großer Entfernung

Bei sehr großem Zoomabstand kann die normale Sternmarkierung kaum noch sichtbar sein.

Ein ausgewähltes System darf deshalb durch eine zusätzliche, maßstabsunabhängig gut erkennbare Markierung hervorgehoben werden.

## 8.10 Dichte Sternregionen

Bei eng beieinanderliegenden Markierungen muss eine zuverlässige Auswahl möglich bleiben.

Dafür sollen Zoom, Kameradrehung und die Suchfunktion verwendet werden können.

---

# 9. Sternbezogenes Kontextmenü

## 9.1 Zweck

Das Kontextmenü ermöglicht die wichtigsten Aktionen unmittelbar an einem Stern.

Der Spieler soll nicht für jede einfache Kartenaktion in ein großes Seitenmenü wechseln müssen.

## 9.2 Aufbau

Das Menü erscheint in der Nähe des ausgewählten Systems.

Es kann enthalten:

- Name.
- Entfernung.
- Kompakte Aktionssymbole.
- Eine deutliche Anzeige des Auswahlstatus.

## 9.3 Aktionen

Vorgesehen sind:

**Fokussieren**

Richtet die Kamera auf das Sternensystem aus.

**Navigationsziel festlegen**

Markiert das System als Ziel für eine Reise.

**Route berechnen**

Öffnet oder aktualisiert die Routenplanung.

**Favorit setzen**

Speichert das Sternensystem als persönlichen Favoriten.

**Informationen**

Zeigt die ausführliche Informationsansicht an.

## 9.4 Verhalten

Das Kontextmenü ist kompakt und darf die Sternenumgebung nicht unnötig verdecken.

Beim Wechsel der Auswahl wird sein Inhalt entsprechend aktualisiert.

## 9.5 Unverfügbare Aktionen

Nicht mögliche Aktionen sollen verständlich gekennzeichnet werden.

Eine nicht erreichbare Route darf nicht als bereits ausführbarer Navigationsauftrag erscheinen.

---

# 10. Suchfunktion

## 10.1 Zentrale Suche

Die Galaxiekarte besitzt eine prominent erreichbare Suchfunktion.

Diese soll jederzeit ohne lange Menüfolgen geöffnet werden können.

## 10.2 Suchbare Informationen

Gesucht werden können:

- Gebräuchliche Sternnamen.
- Alternative astronomische Bezeichnungen.
- Wissenschaftliche Katalogkennungen.
- Sternensystemnamen.
- Namen eigener Kolonien.
- Bedeutende eigene Einrichtungen, soweit sie einem Sternensystem zugeordnet sind.
- Favoriten.

## 10.3 Automatische Ergänzung

Während der Eingabe können passende Ergebnisse vorgeschlagen werden.

Die Vorschläge sollen übersichtlich dargestellt sein.

## 10.4 Ergebnisinformationen

Ein Suchergebnis kann anzeigen:

- Systemname.
- Alternative Kennung.
- Sternklasse.
- Entfernung.
- Politische Zugehörigkeit, soweit bekannt.

## 10.5 Auswahl eines Ergebnisses

Ein Treffer kann ausgewählt werden.

Das entsprechende Sternensystem wird auf der Karte markiert.

Der Spieler kann anschließend die Kamera auf dieses System zentrieren.

## 10.6 Suche über große Entfernungen

Die Suchfunktion darf nicht auf aktuell sichtbare Sterne beschränkt sein.

Auch Systeme außerhalb des aktuellen Bildausschnitts sollen gefunden werden können.

## 10.7 Keine automatische Reise

Das Auswählen eines Suchergebnisses löst keinen Reisebefehl aus.

Eine Reise muss gesondert geplant beziehungsweise bestätigt werden.

---

# 11. Astronomische Informationsanzeige

## 11.1 Grundlegende Informationen

Für ein ausgewähltes Sternensystem werden die verfügbaren astronomischen Daten angezeigt.

Vorgesehen sind:

- Systemname.
- Alternative Bezeichnungen.
- Katalogkennungen.
- Spektralklasse.
- Räumliche Koordinaten.
- Entfernung zur aktuellen Referenzposition.
- Anzahl bekannter Sternkomponenten.
- Helligkeit.
- Temperatur.
- Weitere verfügbare astrophysikalische Eigenschaften.

## 11.2 Struktur des Informationsfensters

Die Daten werden in logisch getrennte Abschnitte aufgeteilt.

**Systeminformationen**

Name, Kennungen und grundlegende Eigenschaften.

**Astronomische Daten**

Sternklasse, Position, Entfernung und physikalische Parameter.

**Strategische Daten**

Eigentümer, Erkundung, Kolonien, Infrastruktur und vorhandene Verbindungen.

## 11.3 Unbekannte Eigenschaften

Fehlende wissenschaftliche Werte werden als unbekannt behandelt.

Sie dürfen nicht ohne Kennzeichnung durch künstliche Angaben ersetzt werden.

## 11.4 Mehrfachsternsysteme

Das Informationsfenster kann die bekannten Komponenten eines Doppel- oder Mehrfachsternsystems auflisten.

Die detaillierte lokale räumliche Anordnung dieser Sterne gehört nicht zur Galaxiekarte.

## 11.5 Strategische Informationen

Zusätzliche Informationen können sein:

- Fraktion.
- Bevölkerungsgröße im gesamten System.
- Kolonieanzahl.
- Wirtschaftliche Bedeutung.
- Sicherheitsstatus.
- Vorhandene Sprungtore.
- Bedeutende Raumstationen.
- Bekannte Flotten.

Die Informationen werden von den jeweils zuständigen Spielsystemen bereitgestellt.

---

# 12. Astronomische Datengrundlage

## 12.1 Wissenschaftliche Ausgangsdaten

Die Sternenverteilung soll primär auf öffentlich zugänglichen astronomischen Daten beruhen.

Zu den vorgesehenen Datengrundlagen gehören insbesondere Gaia DR3 und ergänzende Sternkataloge wie Hipparcos.

## 12.2 Dreidimensionale Positionen

Astronomische Positionen werden in ein einheitliches räumliches Koordinatensystem überführt.

Die Karte verwendet diese Positionen für sämtliche räumlichen Darstellungen.

## 12.3 Reale Entfernungen

Die tatsächliche räumliche Entfernung zwischen zwei Sternensystemen wird aus ihren Koordinaten bestimmt.

Eine bloße Entfernung anhand zweidimensionaler Bildschirmpositionen ist ausgeschlossen.

## 12.4 Dauerhafte Identifikation

Jedes System besitzt eine eindeutige interne Kennung.

Alternative Katalogkennungen können diesem Objekt zugeordnet werden.

## 12.5 Datenherkunft

Die Herkunft astronomischer Informationen muss nachvollziehbar bleiben.

Vorgesehen sind:

| Herkunft | Bedeutung |
|---|---|
| Beobachtet | Wissenschaftlich gemessen |
| Geschätzt | Wissenschaftlich abgeleitet |
| Generiert | Künstlich erzeugt |
| Fiktiv | Bewusst erfunden |

## 12.6 Fehlende Messwerte

Fehlende Angaben gelten als unbekannt.

Die Karte darf wissenschaftliche Unsicherheiten nicht durch scheinbar präzise, unbelegte Werte verdecken.

## 12.7 Grenzen vorhandener Kataloge

Astronomische Kataloge enthalten keinen vollständig beobachteten Bestand aller Sterne der Milchstraße.

Die Karte muss deshalb zwischen tatsächlich katalogisierten Sternsystemen und der visuellen großräumigen Galaxiedarstellung unterscheiden.

Eine unvollständige wissenschaftliche Datenbasis darf nicht als vollständiger astronomischer Sternbestand ausgegeben werden.

## 12.8 Einheitliche Darstellung

Ein Sternensystem wird unabhängig von der Herkunft seiner Informationen mit denselben grundlegenden Kartenfunktionen dargestellt.

---

# 13. Galaktische Koordinaten und Maßstab

## 13.1 Koordinatenraum

Die Galaxiekarte verwendet einen einheitlichen dreidimensionalen Koordinatenraum.

Die Position eines Sternensystems wird durch drei räumliche Koordinaten beschrieben.

## 13.2 Koordinatenanzeigen

Die Oberfläche kann für ausgewählte Systeme numerische Positionsangaben anzeigen.

Auch die Kameraposition kann bei Bedarf dargestellt werden.

## 13.3 Entfernungseinheiten

Interstellare Entfernungen werden dem Spieler üblicherweise in Lichtjahren angezeigt.

## 13.4 Maßstabsanzeige

Die Karte besitzt eine zur aktuellen Zoomstufe passende Maßstabsanzeige.

Diese kann am unteren Bildschirmrand erscheinen.

## 13.5 Referenzebene und Koordinaten

Die Lage der horizontalen Orientierungsebene wird eindeutig definiert.

Koordinatenwerte und Projektionslinien beziehen sich auf dieselbe Definition.

## 13.6 Sternsymbol und physikalische Größe

Die Größe einer Sternmarkierung darf aus Gründen der Lesbarkeit angepasst werden.

Dadurch wird jedoch nicht die räumliche Entfernung zwischen den Sternen verändert.

---

# 14. Kartenmodi und Filter

## 14.1 Grundprinzip

Die Galaxiekarte unterstützt verschiedene Informationsmodi.

Ein Modus verändert nur die zusätzliche Darstellung der Informationen.

Die astronomischen Sternpositionen bleiben unverändert.

## 14.2 Astronomischer Standardmodus

Der Standardmodus stellt die astronomische Sternverteilung in den Vordergrund.

Sterne werden nach ihren astrophysikalischen Eigenschaften dargestellt.

Zusätzliche strategische Informationen bleiben zunächst reduziert.

## 14.3 Sternklassenfilter

Der Spieler kann bestimmte Sternklassen hervorheben beziehungsweise ausblenden.

Beispiele:

- O.
- B.
- A.
- F.
- G.
- K.
- M.
- Weitere vorhandene Klassen.

Es können mehrere Klassen gleichzeitig ausgewählt werden.

## 14.4 Politischer Modus

Der politische Modus zeigt die Zugehörigkeit von Sternensystemen und die Einflussbereiche der Fraktionen.

## 14.5 Wirtschaftlicher Modus

Der Wirtschaftsmodus zeigt wichtige wirtschaftliche Eigenschaften von Sternensystemen.

Beispiele:

- Industrielle Schwerpunkte.
- Landwirtschaft.
- Forschung.
- Rohstoffförderung.
- Handel.
- Versorgungslage.

## 14.6 Ressourcenmodus

Der Ressourcenmodus zeigt bekannte Ressourceninformationen auf Sternensystemebene.

Er stellt keine planetaren Abbaugebäude oder Kachelraster dar.

## 14.7 Transportmodus

Der Transportmodus stellt tatsächlich betriebene Verkehrsverbindungen dar.

Passagier- und Warenverbindungen können unterschieden werden.

## 14.8 Militärischer Modus

Der militärische Modus hebt bekannte Flotten und militärische Einrichtungen hervor.

## 14.9 Navigationsmodus

Der Navigationsmodus zeigt:

- Geplante Routen.
- Aktive Reisen.
- Warpetappen.
- Sprungtorpassagen.
- Zwischenstationen.
- Navigationsziele.

## 14.10 Erkundungsmodus

Der Erkundungsmodus stellt den Wissensstand der aktuellen Fraktion dar.

## 14.11 Filterkategorien

Filter sollen in logisch gegliederten Kategorien organisiert werden.

Der Spieler kann einzelne Kategorien aufklappen.

Innerhalb einer Kategorie sind Mehrfachauswahlen möglich.

## 14.12 Kombinierte Informationsebenen

Der Spieler kann geeignete Kartenebenen kombinieren.

Beispiele:

- Politische Gebiete mit Sprungtoren.
- Kolonien mit Transportlinien.
- Sternklassen mit Erkundungsstatus.
- Militärische Flotten mit Navigationsrouten.

## 14.13 Visuelle Prioritäten

Bei mehreren aktivierten Filtern müssen Auswahlmarkierungen und wichtige Navigationsinformationen weiterhin gut sichtbar bleiben.

Eine überladene Darstellung soll vermieden werden.

---

# 15. Politische und räumliche Einflussbereiche

## 15.1 Fraktionszugehörigkeit

Sternensysteme können einer Fraktion gehören oder unkontrolliert sein.

Die Zugehörigkeit ist unabhängig von der Position des Sterns.

## 15.2 Fraktionsfarben

Jede Fraktion erhält eine unterscheidbare Kartenfarbe.

Diese kann für kontrollierte Systeme, Flotten und politische Gebiete verwendet werden.

## 15.3 Dreidimensionale Einflussgebiete

Politische Einflussbereiche können als räumliche, halbtransparente Volumen dargestellt werden.

Die Gebiete sollen weich und organisch geformt wirken.

Sie dürfen nicht den Eindruck einer bloß auf das Orientierungsgitter gezeichneten zweidimensionalen Fläche vermitteln.

## 15.4 Transparenz

Die politischen Volumen dürfen die dahinterliegenden Sterne nicht vollständig verdecken.

Der Spieler muss ihre räumliche Verteilung weiterhin erkennen können.

## 15.5 Gebietsgrenzen

Die Grenzen politischer Einflussbereiche können durch dezente Konturen hervorgehoben werden.

Bei der Betrachtung aus unterschiedlichen Perspektiven müssen die räumlichen Zusammenhänge nachvollziehbar bleiben.

## 15.6 Darstellung und Spielmechanik

Eine grafische Einflussfläche stellt nicht automatisch eine zusätzliche, eigenständige Besitzregel für jeden Punkt des leeren Raums dar.

Maßgeblich sind die tatsächlichen Kontroll- und Einflussregeln des Spiels.

Die genaue politische Gebietsmechanik gehört zum entsprechenden Fraktionskonzept.

## 15.7 Strategische Systeme

Wichtige Systeme können gesonderte Markierungen erhalten.

Beispiele:

- Hauptstadt.
- Kernkolonie.
- Bedeutende Industrie.
- Forschungszentrum.
- Militärstützpunkt.
- Sprungtorknoten.

---

# 16. Interstellare Navigation

## 16.1 Grundprinzip

Die Galaxiekarte ist die zentrale Oberfläche zur Planung interstellarer Reisen.

Der Spieler kann Start, Ziel und gegebenenfalls Zwischenstationen festlegen.

Die Karte zeigt anschließend eine zulässige Route durch den dreidimensionalen Raum.

## 16.2 Tatsächliche Entfernung

Die Entfernung einer Warpstrecke wird aus der dreidimensionalen Position der beteiligten Sternensysteme bestimmt.

Die Kameraansicht und die Bildschirmpositionen haben keinen Einfluss auf diese Entfernung.

## 16.3 Warpstufen

Die interstellare Raumfahrt verwendet neun Warpstufen.

Die bisher vorgesehenen Geschwindigkeiten bleiben erhalten:

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

Die Werte sind vorläufige Balancewerte.

## 16.4 Flottengeschwindigkeit

Eine gemeinsam reisende Flotte richtet sich grundsätzlich nach dem langsamsten Schiff.

Die angezeigte Reisezeit berücksichtigt diese Geschwindigkeitsbegrenzung.

## 16.5 Mehrgliedrige Routen

Eine Route kann aus mehreren aufeinanderfolgenden Warpetappen bestehen.

Die einzelnen Zwischenstationen werden auf der Karte markiert.

## 16.6 Sprungtore

Sprungtore werden von Fraktionen errichtet.

Ein Sternensystem kann zunächst höchstens ein Sprungtor besitzen.

Die Tore bilden eine strategische interstellare Infrastruktur.

## 16.7 Zugriffsrechte

Für die Nutzung von Sprungtoren gelten die bisherigen Regeln:

- Eigene Tore sind zugänglich.
- Tore befreundeter Fraktionen sind zugänglich.
- Tore verbündeter Fraktionen sind zugänglich.
- Neutrale oder feindliche Tore sind ohne zusätzliche Rechte nicht zugänglich.

## 16.8 Reisezeit über Sprungtore

Eine Sprungtorpassage benötigt keine Spielzeit.

Sie kann auch zwischen weit voneinander entfernten Sternensystemen erfolgen.

## 16.9 Kombination von Warp und Sprungtoren

Eine interstellare Route kann unterschiedliche Reisearten kombinieren.

Beispiel:

`Startsystem → Warp → Sprungtor A → Sprungtor B → Warp → Zielsystem`

## 16.10 Routenoptimierung

Die Standardroutenplanung sucht eine zulässige Verbindung mit möglichst geringer Gesamtreisezeit.

Die Zugriffsrechte auf Sprungtore und deren tatsächlicher Betriebszustand werden berücksichtigt.

## 16.11 Alternative Routenoptionen

Die Kartenoberfläche soll Raum für unterschiedliche Routenoptionen besitzen.

Die schnellste Route ist die verbindliche Standardoption.

Weitere Optimierungsziele, beispielsweise geringere Reisekosten, können später ergänzt werden, wenn entsprechende Kostenregeln festgelegt sind.

---

# 17. Dreidimensionale Routenvisualisierung

## 17.1 Räumliche Linien

Eine berechnete Reise wird als räumliche Verbindung zwischen Sternensystemen dargestellt.

Die Linien verlaufen entsprechend den tatsächlichen Sternpositionen durch den dreidimensionalen Raum.

## 17.2 Grundgestaltung

Routenlinien sollen:

- Schlank sein.
- Gut erkennbar leuchten.
- Sich deutlich vom Orientierungsgitter unterscheiden.
- Auch in dichten Sternfeldern lesbar bleiben.
- Beim Drehen der Kamera ihre räumliche Lage erkennen lassen.

## 17.3 Aktive Route

Die aktuell geplante Route erhält eine deutliche Hervorhebung.

Sie kann beispielsweise in einer warmen Akzentfarbe dargestellt werden.

## 17.4 Startsystem

Das Startsystem wird durch eine eigene Markierung hervorgehoben.

## 17.5 Zielsystem

Das Zielsystem besitzt eine klar erkennbare Zielmarkierung.

## 17.6 Zwischenstationen

Zwischenstationen werden entlang der Route markiert.

Die Anzahl der Etappen kann im Navigationsbereich angezeigt werden.

## 17.7 Unterschiedliche Verbindungstypen

Die Karte muss mindestens unterscheiden zwischen:

- Warpstrecke.
- Sprungtorpassage.
- Aktuellem Reiseabschnitt.
- Bereits zurückgelegter Strecke.
- Nicht verfügbarer Verbindung.

Die Unterscheidung soll nicht ausschließlich auf Farben beruhen.

Unterschiedliche Linienformen oder zusätzliche Symbole sind vorgesehen.

## 17.8 Ausgewählte und nicht ausgewählte Routen

Eine aktuell ausgewählte Route wird deutlich hervorgehoben.

Andere angezeigte Routen können gedämpft dargestellt werden.

## 17.9 Vorschau

Eine berechnete Route wird zunächst als Vorschau angezeigt.

Erst ein gesonderter Befehl löst eine tatsächliche Reise aus.

## 17.10 Änderung während einer Reise

Ändert sich die Zugänglichkeit eines Sprungtors oder einer benötigten Zwischenstation, muss der Navigationsstatus entsprechend aktualisiert werden.

Die Karte darf eine nicht mehr gültige Verbindung nicht als weiterhin nutzbar kennzeichnen.

---

# 18. Routenplanungsfenster

## 18.1 Grundaufbau

Die Routenplanung besitzt einen eigenen Informationsbereich.

Dieser soll kompakt bleiben und die Karte möglichst wenig verdecken.

## 18.2 Start- und Zielangaben

Vorgesehen sind:

- Startsystem.
- Zielsystem.
- Zwischenstationen.
- Verwendete Flotte.
- Maßgebliche Warpstufe.

## 18.3 Ergebnisinformationen

Nach der Berechnung können angezeigt werden:

- Gesamtdistanz.
- Geschätzte Reisezeit.
- Anzahl der Warpetappen.
- Anzahl der Sprungtorpassagen.
- Verwendete Sprungtore.
- Aktueller Navigationsstatus.

## 18.4 Aktueller Reiseabschnitt

Während einer laufenden Reise kann die Karte anzeigen:

- Aktuelles System beziehungsweise aktuellen Reiseabschnitt.
- Nächstes Ziel.
- Verbleibende Gesamtstrecke.
- Voraussichtliche Ankunft.

## 18.5 Bestätigung

Die Routenplanung und die tatsächliche Auftragserteilung bleiben getrennt.

Der Spieler kann eine Route betrachten, bevor er sie bestätigt.

## 18.6 Fehlgeschlagene Routenplanung

Existiert keine zulässige Verbindung, erscheint eine verständliche Meldung.

Das Zielsystem bleibt trotzdem ausgewählt.

---

# 19. Sprungtore auf der Karte

## 19.1 Kennzeichnung

Sternensysteme mit einem Sprungtor erhalten eine zusätzliche Kartenmarkierung.

## 19.2 Unterschiedliche Torzustände

Die Karte kann unterscheiden zwischen:

- Eigenem aktivem Tor.
- Zugänglichem fremdem Tor.
- Nicht zugänglichem Tor.
- Beschädigtem Tor.
- Deaktiviertem Tor.
- Zerstörtem Tor.

## 19.3 Sichtbarkeit

Die Markierung wird nur angezeigt, soweit die aktuelle Fraktion entsprechende Informationen besitzt.

## 19.4 Sprungtorverbindungen

Im Navigationsmodus können vorhandene nutzbare Torverbindungen dargestellt werden.

Die Darstellung darf nicht unnötig jede mögliche Verbindung gleichzeitig als separate Linie zeigen, wenn dadurch ein unübersichtliches Netz entsteht.

## 19.5 Interaktion

Ein Sternensystem mit Sprungtor kann über das normale Systeminformationsfenster ausgewählt werden.

Die Galaxiekarte zeigt das Sprungtor als Eigenschaft beziehungsweise strategische Infrastruktur des Systems.

Die detaillierte lokale Darstellung des Tores gehört nicht zu dieser Karte.

---

# 20. Transportnetzwerke

## 20.1 Grundprinzip

Die Karte soll tatsächlich betriebene interstellare Transportnetzwerke darstellen können.

Diese sind von bloß theoretisch möglichen Flugrouten zu unterscheiden.

## 20.2 Transportarten

Vorgesehen sind:

- Passagiertransport.
- Warentransport.
- Gemeinsame Transportverbindungen.

## 20.3 Passagierlinien

Passagierverbindungen werden von tatsächlich vorhandenen Transportschiffen bedient.

Die Galaxiekarte stellt die Verbindung zwischen den bedienten Sternensystemen dar.

## 20.4 Mehrgliedrige Verbindungen

Transportwege dürfen aus mehreren Teilstrecken bestehen.

Zwischenstationen und Umsteigepunkte können visualisiert werden.

## 20.5 Warentransport

Warentransportlinien dienen der Bewegung materieller Ressourcen und Produkte zwischen Sternensystemen.

Die Galaxiekarte stellt nur die Verbindungen dar.

Die eigentliche Warenproduktion und Lagerhaltung verbleiben in den Wirtschaftssystemen.

## 20.6 Animierte Verkehrsströme

Aktive Transportverbindungen können als dünne leuchtende Linien mit dezenten bewegten Lichtpunkten dargestellt werden.

Die Bewegung der Lichtpunkte kann die Transportrichtung verdeutlichen.

Sie dient lediglich der verständlichen Darstellung vorhandener Verkehrsströme.

## 20.7 Transportstärke

Bei Bedarf kann die Darstellung die Bedeutung einer Verbindung kenntlich machen.

Beispielsweise durch:

- Linienhelligkeit.
- Begrenzte Variation der Linienstärke.
- Anzahl oder Dichte der animierten Lichtpunkte.

Konkrete Werte müssen aus der tatsächlichen Transportaktivität abgeleitet werden.

## 20.8 Transportkategorien

Ein Transportfilter soll die Auswahl unterschiedlicher Waren- beziehungsweise Transportkategorien ermöglichen.

Die Kategorien orientieren sich an den tatsächlich vorhandenen Wirtschaftsressourcen.

## 20.9 Keine fiktiven Transporte

Eine theoretisch mögliche Route darf nicht automatisch als aktiver Warenstrom erscheinen.

Ebenso darf die Darstellung keinen regelmäßigen Passagierverkehr behaupten, wenn keine entsprechende Transportschiffverbindung existiert.

## 20.10 Verkehrsknoten

Sternensysteme mit mehreren wichtigen Transportlinien können gesondert hervorgehoben werden.

---

# 21. Flotten und militärische Darstellung

## 21.1 Flotten als Kartenobjekte

Raumflotten werden als eigene strategische Markierungen dargestellt.

Sie müssen sich deutlich von gewöhnlichen Sternpunkten unterscheiden.

## 21.2 Flottenpositionen

Die aktuelle Position einer Flotte ergibt sich aus dem tatsächlichen Spielzustand.

Bei einer interstellaren Reise kann sie entlang der berechneten Route dargestellt werden.

## 21.3 Zeitabhängige Darstellung

Die Flottenbewegung wird an die zentrale Spielzeit gekoppelt.

Bei pausiertem Spiel steht die dargestellte Flotte still.

## 21.4 Flotteninformationen

Bei Auswahl können angezeigt werden:

- Flottenname.
- Zugehörigkeit.
- Schiffsanzahl.
- Aktueller Standort.
- Aktuelle Reise.
- Zielsystem.
- Geschätzte Ankunft.

## 21.5 Militärische Filter

Der militärische Kartenmodus kann hervorheben:

- Eigene Flotten.
- Bekannte fremde Flotten.
- Militärische Stützpunkte.
- Verteidigte Systeme.
- Relevante strategische Routen.

## 21.6 Sichtbarkeit

Fremde Flotten werden nur entsprechend dem tatsächlichen Informationsstand der aktuellen Fraktion angezeigt.

Die Karte führt selbst keine Sensorsimulation durch.

---

# 22. Erkundung und Informationsverfügbarkeit

## 22.1 Trennung von astronomischen Daten und Spielwissen

Wissenschaftlich bekannte Sternpositionen und das Wissen einer Fraktion sind getrennte Informationen.

Ein Stern kann in der astronomischen Datenbasis vorhanden sein, ohne dass seine Eigenschaften der aktuellen Fraktion vollständig bekannt sind.

## 22.2 Erkundungszustände

Als vorläufige Zustände sind vorgesehen:

| Zustand | Bedeutung |
|---|---|
| Unbekannt | Keine verwertbaren Informationen |
| Bekannt | Position und grundlegende Informationen bekannt |
| Erkundet | System untersucht |
| Vermessen | Weitergehende Informationen vorhanden |

## 22.3 Kartenanzeige

Die Karte zeigt Informationen entsprechend dem Wissensstand der aktuellen Fraktion.

Insbesondere politische, wirtschaftliche und militärische Angaben dürfen nicht ohne entsprechende Kenntnis sichtbar sein.

## 22.4 Anfangssichtbarkeit

Ob sämtliche astronomisch katalogisierten Sternpositionen bereits zu Beginn sichtbar sind, bleibt eine offene Spielentscheidung.

Die Sichtbarkeit einer Sternposition und das Wissen über ihre Eigenschaften dürfen getrennt behandelt werden.

---

# 23. Darstellung sehr großer Sternpopulationen

## 23.1 Langfristige Zielsetzung

Die Galaxiekarte soll langfristig einen sehr großen Bestand astronomischer Sternensysteme unterstützen.

## 23.2 Unterschiedliche Detailstufen

Die sichtbare Darstellung passt sich an den aktuellen Kartenmaßstab an.

**Gesamtgalaxie**

Die großräumige Struktur der Milchstraße steht im Vordergrund.

**Regionale Ansicht**

Sternpopulationen und wichtige Systeme werden deutlicher.

**Lokale Sternenansicht**

Einzelne Sternsysteme, Beschriftungen und Auswahlmarkierungen werden sichtbar.

## 23.3 Kontinuierliche Übergänge

Die Übergänge zwischen den Betrachtungsebenen sollen flüssig erscheinen.

Die Karte darf nicht den Eindruck erwecken, dass bei jedem größeren Zoomschritt eine völlig unabhängige Karte geladen wird.

## 23.4 Begrenzung der Beschriftungen

Nicht alle Sternnamen werden gleichzeitig angezeigt.

Die Beschriftungsdichte passt sich der aktuellen Situation an.

## 23.5 Priorisierung

Folgende Objekte dürfen bei der Darstellung bevorzugt werden:

- Ausgewähltes System.
- Aktuelles Ziel.
- Startsystem.
- Wichtige eigene Systeme.
- Favoriten.
- Aktuelle Zwischenstationen.

## 23.6 Unabhängigkeit von der Simulation

Nicht sichtbare oder stark vereinfachte Sterne bleiben Bestandteil der astronomischen und strategischen Datenbasis.

Die Spielsimulation darf nicht davon abhängen, dass sämtliche Sternensysteme gleichzeitig vollständig grafisch dargestellt werden.

---

# 24. Spielzeit und Aktualisierung

## 24.1 Gemeinsame Spielzeit

Die Galaxiekarte verwendet ausschließlich die zentrale Spielzeit.

Sie besitzt keine eigene unabhängig laufende Simulation.

## 24.2 Flottenbewegung

Die Position von Flotten wird aus ihrem tatsächlichen Reisefortschritt abgeleitet.

## 24.3 Zeitbeschleunigung

Bei erhöhter Spielgeschwindigkeit werden laufende Reisen entsprechend schneller dargestellt.

## 24.4 Pausieren

Wird die Spielsimulation pausiert, stehen alle zeitabhängigen galaktischen Vorgänge still.

Die Kamera bleibt trotzdem frei bedienbar.

## 24.5 Sternpositionen

Die astronomischen Sternkoordinaten beziehen sich auf eine definierte Bezugsepoche.

Ob ihre Eigenbewegung über sehr lange Spielzeiträume berücksichtigt wird, bleibt offen.

## 24.6 Keine planetaren Bewegungen

Die Galaxiekarte berechnet und visualisiert keine Umlaufbahnen einzelner Planeten oder Monde.

---

# 25. Gestaltung der Oberfläche

## 25.1 Visuelle Zielsetzung

Die Galaxiekarte soll hochwertig, technisch und zurückhaltend wirken.

Die Gestaltung orientiert sich an der Vorstellung eines funktionalen interstellaren Navigationsinstruments.

## 25.2 Hintergrundfarben

Als Grundfarben werden sehr dunkle Schwarz-, Blau- und Anthrazittöne vorgesehen.

## 25.3 Akzentfarben

Für die Benutzeroberfläche können folgende Funktionen farblich unterschieden werden:

| Funktion | Gestalterische Richtung |
|---|---|
| Normale astronomische Sterne | Physikalisch begründete Sternfarben |
| Aktueller Fokus beziehungsweise Referenzposition | Türkis oder Cyan |
| Aktive Bedienaktion | Warmer orangefarbener Akzent |
| Navigationsziel | Deutlich erkennbare Zielmarkierung |
| Orientierungsgitter | Gedämpftes Blau oder Grau |
| Projektionslinien | Schwaches Cyan oder Hellblau |
| Politische Zugehörigkeit | Fraktionsspezifische Farbe |
| Inaktive Information | Gedämpftes Grau |

Die endgültigen Werte werden im einheitlichen UI-Design festgelegt.

## 25.4 Panels

Informationsbereiche besitzen überwiegend:

- Dunkle Hintergründe.
- Schmale Rahmen.
- Dezente Transparenz.
- Klare Trennlinien.
- Gut erkennbare aktive Reiter.
- Kompakte Bedienelemente.

## 25.5 Symbolik

Die Oberfläche verwendet möglichst einfache, eindeutige Symbole.

Vorgesehen sind Symbole für:

- Suche.
- Fokus.
- Navigation.
- Route.
- Favorit.
- Flotte.
- Sprungtor.
- Kolonie.
- Fraktion.
- Filter.
- Informationen.

## 25.6 Typografie

Die Schrift soll modern und gut lesbar sein.

Wichtige Eigenschaften sind:

- Gute Erkennbarkeit kleiner Zahlen.
- Klare Darstellung astronomischer Kennungen.
- Ausreichender Kontrast.
- Einheitliche Schreibweisen für Entfernungen und Koordinaten.

## 25.7 Animationen

Animationen dienen überwiegend der Orientierung.

Geeignet sind:

- Sanfte Kamerafahrten.
- Ein- und Ausblenden von Informationsfenstern.
- Kurze Hervorhebung bei der Auswahl.
- Dezente Bewegung auf aktiven Transportlinien.
- Flüssige Aktualisierung von Routen.

Unnötig starke Glüheffekte, dauerhafte Blinkanimationen und störende Bewegung sollen vermieden werden.

---

# 26. Zustände und Bedienabläufe

## 26.1 Karte ohne Auswahl

Die Karte zeigt die astronomische Sternenverteilung.

Die Kamera ist frei bedienbar.

Such- und Filterfunktionen bleiben verfügbar.

## 26.2 Stern ausgewählt

Das System erhält eine sichtbare Markierung.

Das Kontextmenü und der Informationsbereich können geöffnet werden.

## 26.3 Stern fokussiert

Die Kamera wird auf das gewählte System ausgerichtet.

Die umgebende räumliche Sternverteilung bleibt sichtbar.

## 26.4 Suche aktiv

Das Suchfeld zeigt passende Ergebnisse.

Die Kartendarstellung bleibt erhalten.

## 26.5 Routenplanung aktiv

Start, Ziel und mögliche Zwischenstationen werden hervorgehoben.

Die Route erscheint als räumliche Linienführung.

## 26.6 Politischer Modus aktiv

Fraktionsinformationen werden zusätzlich eingeblendet.

Die astronomischen Positionen bleiben unverändert.

## 26.7 Transportmodus aktiv

Tatsächlich betriebene Transportlinien werden sichtbar.

## 26.8 Sehr große Entfernung

Bei einer großräumigen Betrachtung werden Detailinformationen reduziert.

Die galaktische Gesamtstruktur steht im Vordergrund.

## 26.9 Nicht erreichbares Ziel

Ein Zielsystem kann markiert bleiben, auch wenn keine zulässige Reiseverbindung besteht.

Die Karte zeigt den entsprechenden Navigationsstatus.

## 26.10 Fehlende Informationen

Unbekannte Daten werden als unbekannt gekennzeichnet.

---

# 27. Beispiel einer vollständigen Kartenbedienung

Der Spieler öffnet die Galaxiekarte.

Die Ansicht zeigt einen dunklen dreidimensionalen Sternenraum.

Im Hintergrund sind Sternwolken und Teile der Milchstraße sichtbar.

Die Kamera befindet sich zunächst in einer leicht geneigten Perspektive über einer lokalen Sternregion.

Die Sterne erscheinen als unterschiedlich helle Punkte.

Ihre Farben reichen von rötlichen und orangefarbenen Tönen bis zu weißlichen und bläulichen Sternen.

Unterhalb der Sternregion liegt ein feines Koordinatengitter.

Von einzelnen Sternen führen dünne vertikale Linien zur Referenzebene.

Der Spieler dreht die Kamera.

Die perspektivische Anordnung der Sterne verändert sich.

Sterne, die zuvor nahe beieinander erschienen, lassen sich nun räumlich unterscheiden.

Anschließend neigt der Spieler die Kamera.

Die unterschiedlichen Höhen der Sterne gegenüber dem Gitter werden erkennbar.

Der Spieler zoomt heraus.

Die einzelnen Sternsysteme werden kleiner.

Nach und nach geht die regionale Sternverteilung in eine großräumige galaktische Darstellung über.

Beim weiteren Herauszoomen erscheint die gesamte Milchstraße.

Das helle galaktische Zentrum, die Scheibe und die Spiralarmstrukturen werden sichtbar.

Der Spieler dreht die Gesamtgalaxie in eine stärker seitliche Perspektive.

Die räumliche Ausdehnung ihrer Scheibe wird erkennbar.

Anschließend öffnet er das Suchfeld.

Er sucht nach einem bestimmten Sternensystem.

Die Suche liefert passende Ergebnisse.

Der Spieler wählt den gewünschten Stern aus.

Die Karte zeigt die Position des Systems durch eine deutlich sichtbare Markierung an.

Mit der Fokusfunktion wird die Kamera auf das Ziel ausgerichtet.

Sie bewegt sich durch den galaktischen Raum, während die dargestellte Sternenverteilung kontinuierlich detaillierter wird.

Schließlich befindet sich die Kamera wieder in einer lokalen Sternregion.

Der ausgewählte Stern ist mit einem klaren Auswahlrahmen markiert.

Eine Projektionslinie verbindet seine Position mit der Referenzebene.

Neben dem Stern erscheint ein kleines Kontextmenü.

Im rechten Informationsbereich stehen der Systemname, die Sternklasse, die Entfernung und weitere bekannte Eigenschaften.

Der Spieler öffnet die Routenplanung.

Er wählt ein Zielsystem.

Die Karte zeigt eine räumliche Verbindung zwischen den beteiligten Sternen.

Zwischenstationen werden markiert.

Ein Teil der Route führt über gewöhnliche Warpstrecken.

Ein anderer Abschnitt verwendet zugängliche Sprungtore.

Die unterschiedlichen Verbindungen werden grafisch unterscheidbar dargestellt.

Im unteren Navigationsbereich erscheinen die geschätzte Reisezeit und die Anzahl der Reiseabschnitte.

Der Spieler dreht die Karte, um die räumliche Route aus einer anderen Perspektive zu betrachten.

Anschließend öffnet er den politischen Kartenmodus.

Die Karte hebt kontrollierte Sternsysteme verschiedener Fraktionen hervor.

Dreidimensionale halbtransparente Einflussbereiche zeigen die politische Verteilung in der Region.

Danach aktiviert der Spieler den Transportmodus.

Einzelne aktive Verkehrsverbindungen erscheinen als dünne leuchtende Linien.

Dezente bewegte Lichtpunkte verdeutlichen die Richtung der Transportströme.

Verkehrsknoten mit mehreren Verbindungen werden erkennbar.

Zum Schluss deaktiviert der Spieler die strategischen Informationsebenen.

Die astronomische Sternenkarte erscheint wieder in ihrer ursprünglichen, übersichtlichen Darstellung.

**Sämtliche beschriebenen Aktionen finden ausschließlich innerhalb der Galaxiekarte statt.**

---

# 28. Verbindliche Anforderungen

## 28.1 Kartenstruktur

1. Die Map ist ausschließlich eine dreidimensionale Galaxiekarte.
2. Sie stellt die Milchstraße dar.
3. Reale astronomische Sternpositionen bilden ihre Grundlage.
4. Die Sternpositionen besitzen tatsächliche räumliche Abstände.
5. Die Karte bildet keine planetaren Umlaufbahnen ab.
6. Die Galaxiekarte ist unabhängig von der eigenständigen Sternensystemansicht.

## 28.2 Darstellung

7. Der Hauptbereich zeigt einen frei betrachtbaren dreidimensionalen Sternenraum.
8. Die astronomische Sternenkarte ist der grundlegende Kartenmodus.
9. Die Darstellung verwendet überwiegend dunkle Hintergründe.
10. Sterne erscheinen als leuchtende Punkte.
11. Sternfarben orientieren sich an bekannten astrophysikalischen Eigenschaften.
12. Die Karte kann die gesamte Milchstraße in einer Übersicht darstellen.
13. Der Wechsel zwischen Gesamtgalaxie und lokaler Sternregion erfolgt kontinuierlich.
14. Die räumliche Darstellung bleibt beim Zoomen und Drehen nachvollziehbar.

## 28.3 Orientierung

15. Die Karte besitzt eine zuschaltbare horizontale Referenzebene.
16. Die Referenzebene wird als perspektivisches Koordinatengitter dargestellt.
17. Vertikale Projektionslinien können Sternpositionen mit der Ebene verbinden.
18. Projektionslinien dürfen bei hoher Sternendichte reduziert werden.
19. Der Spieler kann Gitter und Projektionslinien bei Bedarf ausblenden.
20. Koordinaten und Entfernungsskalen müssen eindeutig beschriftet sein.

## 28.4 Kamera

21. Die Kamera kann frei gedreht werden.
22. Die Kamera kann frei geneigt werden.
23. Die Kamera kann innerhalb des galaktischen Raums verschoben werden.
24. Die Kamera besitzt einen großen kontinuierlichen Zoombereich.
25. Sternensysteme können fokussiert werden.
26. Auswahl und Kamerafokussierung sind getrennte Aktionen.
27. Große räumliche Fokuswechsel sollen nachvollziehbar animiert werden.
28. Die Kamera bleibt unabhängig von den aktiven Kartenfiltern bedienbar.

## 28.5 Auswahl und Benutzeroberfläche

29. Sternensysteme können direkt ausgewählt werden.
30. Die Auswahl erhält eine deutlich erkennbare Markierung.
31. Die aktuelle Referenzposition und das Navigationsziel besitzen unterscheidbare Markierungen.
32. Ein kompaktes Kontextmenü kann unmittelbar am ausgewählten Stern erscheinen.
33. Die Hauptfunktionen werden über eine schmale vertikale Funktionsleiste erreichbar.
34. Such- und Filterbereiche können bei Bedarf geöffnet werden.
35. Ausführliche Systeminformationen werden in einem separaten Informationsbereich angezeigt.
36. Eine untere Statusleiste kann Navigationsinformationen anzeigen.
37. Die Oberfläche darf die dreidimensionale Kartenfläche nicht unnötig verdecken.

## 28.6 Astronomische Informationen

38. Sternensysteme besitzen eindeutige Kennungen.
39. Alternative astronomische Namen können durchsucht werden.
40. Wissenschaftliche Daten und generierte Informationen bleiben unterscheidbar.
41. Unbekannte Daten dürfen nicht als wissenschaftlich bestätigt dargestellt werden.
42. Die grafische Darstellung verändert keine astronomischen Sternpositionen.
43. Die Karte muss mit unvollständigen astronomischen Daten umgehen können.

## 28.7 Navigation

44. Die Galaxiekarte ist die zentrale Oberfläche zur interstellaren Routenplanung.
45. Reisezeiten berücksichtigen tatsächliche dreidimensionale Entfernungen.
46. Raumschiffe verwenden neun Warpstufen.
47. Gemeinsam reisende Flotten orientieren sich grundsätzlich am langsamsten Schiff.
48. Sprungtore werden von Fraktionen errichtet.
49. Sprungtorpassagen benötigen keine Spielzeit.
50. Eigene, befreundete und verbündete Sprungtore sind entsprechend den vereinbarten Rechten zugänglich.
51. Warpstrecken und Sprungtorpassagen können innerhalb derselben Route kombiniert werden.
52. Routen werden dreidimensional dargestellt.
53. Die Route wird zunächst als Vorschau berechnet.
54. Eine tatsächliche Reise benötigt einen gesonderten Befehl.
55. Unterschiedliche Verbindungstypen müssen visuell unterscheidbar bleiben.

## 28.8 Strategische Informationen

56. Politische Gebiete können als dreidimensionale halbtransparente Bereiche dargestellt werden.
57. Fraktionen erhalten unterschiedliche Kartenfarben.
58. Strategisch wichtige Systeme können markiert werden.
59. Flotten erscheinen als eigene strategische Kartenobjekte.
60. Aktive Transportverbindungen können als räumliche Linien dargestellt werden.
61. Transportlinien können dezente gerichtete Animationen besitzen.
62. Eine lediglich mögliche Flugroute ist keine aktive Transportlinie.
63. Die Karte zeigt strategische Informationen entsprechend dem Wissensstand der aktuellen Fraktion.

## 28.9 Abgrenzungen

64. Die Karte enthält keine eigenständige Sternensystemansicht.
65. Sie berechnet keine planetaren Umlaufbahnen.
66. Sie besitzt keine planetare Kachelverwaltung.
67. Sie simuliert keine Gebäudeproduktion.
68. Sie führt keine eigenständige Bevölkerungsmigration aus.
69. Sie führt keine eigenständige Forschungssimulation durch.
70. Sie ist nicht für die Erzeugung astronomischer Objekte zuständig.
71. StellarForge wird separat konzipiert und dokumentiert.

---

# 29. Offene konzeptionelle Entscheidungen

Die folgenden Fragen bleiben zunächst offen.

## 29.1 Umfang der Milchstraße

Welcher Teil der Milchstraße soll tatsächlich vollständig bespielbar sein?

## 29.2 Anfangssichtbarkeit

Welche katalogisierten Sternpositionen sind einer Fraktion bereits zu Spielbeginn bekannt?

## 29.3 Bezugsebene

Welche galaktische Referenzebene wird für das Orientierungsgitter verwendet?

## 29.4 Sternbewegungen

Sollen wissenschaftlich bekannte Eigenbewegungen der Sterne über sehr lange Spielzeiträume berücksichtigt werden?

## 29.5 Benutzersteuerung

Welche konkreten Maus- und Tastaturbelegungen werden verwendet?

## 29.6 Standardperspektive

In welcher Kameraneigung und Entfernung wird die Galaxiekarte standardmäßig geöffnet?

## 29.7 Auswahlmarkierungen

Welche endgültige grafische Form erhalten Fokus-, Auswahl- und Zielmarkierungen?

## 29.8 Politische Einflussgebiete

Wie werden die räumlichen Konturen politischer Einflussgebiete genau bestimmt und dargestellt?

## 29.9 Routenoptionen

Welche zusätzlichen Optimierungsziele sollen neben der schnellsten Route unterstützt werden?

## 29.10 Informationsdichte

Wie viele Sternnamen, Projektionslinien und strategische Symbole werden in den unterschiedlichen Betrachtungsmaßstäben angezeigt?

## 29.11 Transportdarstellung

Wie werden die verfügbaren Transportkapazitäten und die tatsächliche Auslastung von Verbindungen grafisch vermittelt?

## 29.12 Endgültige visuelle Gestaltung

Welche genaue Farbpalette, Symbolsprache und Typografie erhält die Galaxiekarte?

Diese Punkte werden im weiteren fachlichen Konzept festgelegt.

---

# 30. Zusammenfassung

Die Galaxiekarte von Project Sagittarius stellt die Milchstraße als frei navigierbaren dreidimensionalen Raum dar.

Die räumlichen Sternpositionen beruhen möglichst auf wissenschaftlich dokumentierten astronomischen Daten.

Die Kamera erlaubt einen kontinuierlichen Wechsel zwischen lokalen Sternregionen und der gesamten Galaxie.

Die astronomische Standardansicht besteht aus einem dunklen Sternenraum mit räumlich verteilten, leuchtenden Sternmarkierungen.

Ein optionales perspektivisches Koordinatengitter und vertikale Projektionslinien machen die dritte Dimension erkennbar.

Die Bedienung erfolgt überwiegend über direkte Kamera- und Sterninteraktionen.

Eine kompakte vertikale Funktionsleiste, ein Suchfeld, kontextbezogene Informationsfenster und eine untere Navigationsanzeige ergänzen die Karte.

Die strategischen Informationen werden in eigenen Kartenmodi dargestellt.

Dazu gehören insbesondere:

- Politische Gebiete.
- Fraktionszugehörigkeiten.
- Kolonien.
- Raumflotten.
- Sprungtore.
- Navigationsrouten.
- Passagierverbindungen.
- Warenströme.
- Erkundungsinformationen.

Die Karte bleibt dabei stets eine astronomisch begründete dreidimensionale Darstellung.

**Sie ist keine lokale Sternensystemansicht und keine planetare Verwaltungsoberfläche.**

Die eigenständigen Sternensystemansichten, die Planetenverwaltung und die astronomische Weltgenerierung werden in separaten Konzepten behandelt.

Das Ziel ist eine räumlich glaubwürdige, übersichtliche und angenehm bedienbare Galaxiekarte, die sowohl die astronomische Erforschung der Milchstraße als auch die strategische Führung eines interstellaren Reiches unterstützt.

**Dieses Dokument beschreibt ausschließlich das fachliche Spiel- und Darstellungskonzept. Es enthält keinen Entwicklungsplan und keinen Implementierungsplan.**

**Dokumentversion: 0.4**