# Project Sagittarius – Konzept der Sternenkarte

**Projekt:** Project Sagittarius / Sternenreiche  
**Dokument:** `docs/concept/map.md`  
**Dokumentversion:** 0.2  
**Stand:** 10. November 2026  
**Status:** Fachliches Spielkonzept  
**Geltungsbereich:** Galaxiekarte, Sternensystemkarte, astronomische Spielwelt und räumliche Navigation

---

# 1. Grundidee

Die Sternenkarte bildet die räumliche Grundlage von Project Sagittarius.

Die Spielwelt soll eine dreidimensionale Darstellung unserer Milchstraße bieten, deren Sternpositionen und astronomische Eigenschaften möglichst auf realen wissenschaftlichen Daten basieren.

Anders als bei einer rein prozedural erzeugten Galaxie soll der Spieler tatsächlich bekannte Sterne und Sternensysteme wiederfinden können.

Sterne wie die Sonne, Sirius oder Proxima Centauri sollen an den Positionen erscheinen, die sich aus den verwendeten astronomischen Katalogdaten ergeben.

Fehlende Informationen können durch eine deterministische prozedurale Generierung ergänzt werden.

Das Ergebnis ist eine hybride Spielwelt aus realen und fiktiven astronomischen Informationen.

## 1.1 Die Sternenkarte als zentrale Spielansicht

Die Sternenkarte ist nicht ausschließlich eine grafische Übersicht.

Sie bildet gleichzeitig die Grundlage für:

- Die Erkundung der Galaxie.
- Die Auswahl von Sternensystemen.
- Die Navigation von Raumschiffen.
- Die Darstellung von Kolonien.
- Die Darstellung politischer Einflussbereiche.
- Die Positionierung von Raumstationen und Sprungtoren.
- Die Visualisierung interstellarer Transportverbindungen.
- Die Bewegung und Positionierung von Raumflotten.
- Die strategische Planung einer Zivilisation.

Alle diese Funktionen verwenden eine gemeinsame räumliche Grundlage.

## 1.2 Zentrale Gestaltungsprinzipien

Die Sternenkarte soll folgende Eigenschaften besitzen:

**Astronomische Glaubwürdigkeit**

Die Positionen und Entfernungen realer Sterne sollen ihren wissenschaftlich dokumentierten Werten entsprechen.

**Räumliche Freiheit**

Der Spieler soll die Galaxie als echten dreidimensionalen Raum erleben und nicht als flaches Sternennetz.

**Konsistenz**

Die Galaxiekarte und die Sternensystemansicht verwenden dieselben astronomischen Informationen.

**Dynamik**

Planeten und andere geeignete Himmelskörper bewegen sich abhängig von der Spielzeit auf ihren festgelegten Umlaufbahnen.

**Übersichtlichkeit**

Trotz der großen Zahl astronomischer Objekte muss die Karte navigierbar und verständlich bleiben.

**Strategische Nutzbarkeit**

Die Sternenkarte muss wirtschaftliche, militärische und politische Spielinformationen darstellen können, ohne die astronomische Grundlage zu verändern.

---

# 2. Aufbau der Spielwelt

## 2.1 Die Milchstraße

Die langfristige Spielwelt orientiert sich an der tatsächlichen Milchstraße.

Ihre räumliche Struktur soll nicht ausschließlich durch frei erfundene Sternpositionen entstehen.

Stattdessen bilden astronomische Kataloge die Grundlage.

Wo geeignete Daten fehlen, können zusätzliche Systeme plausibel erzeugt werden.

Die räumlichen Beziehungen bekannter Sterne bleiben dabei erhalten.

## 2.2 Dreidimensionaler Raum

Die Galaxie besitzt drei räumliche Dimensionen.

Jedes Sternensystem erhält eine Position innerhalb eines einheitlichen astronomischen Koordinatenraums.

Damit sind auch Sterne sichtbar, die über oder unter der galaktischen Ebene liegen.

Die Karte darf nicht auf eine zweidimensionale Verteilung mit lediglich dekorativer Tiefenwirkung reduziert werden.

## 2.3 Tatsächliche Sternentfernungen

Die Entfernung zwischen zwei Sternensystemen ergibt sich aus ihren räumlichen Positionen.

Diese Entfernung bildet auch die Grundlage für die interstellare Reisezeit.

Die grafische Darstellung darf Sternpositionen nicht nachträglich verschieben, um kürzere Routen oder optisch gleichmäßigere Sternabstände zu erzeugen.

Visuelle Symbole können für die bessere Erkennbarkeit vergrößert werden.

Die zugrunde liegenden räumlichen Entfernungen bleiben davon unberührt.

## 2.4 Sternensysteme

Die grundlegende astronomische Einheit ist das Sternensystem.

Ein Sternensystem kann enthalten:

- Einen einzelnen Stern.
- Zwei oder mehrere Sterne.
- Planeten.
- Monde.
- Asteroiden.
- Asteroidengürtel.
- Weitere astronomische Kleinkörper.
- Künstliche Objekte wie Raumstationen.
- Raumschiffe und Raumflotten.
- Sprungtore.

Nicht jedes System muss alle Objekttypen enthalten.

Die tatsächliche Zusammensetzung richtet sich nach den vorhandenen astronomischen Informationen und den gegebenenfalls erzeugten Ergänzungen.

---

# 3. Astronomische Daten

## 3.1 Reale Daten als Grundlage

Die Sternenkarte soll möglichst viele wissenschaftlich dokumentierte Sterne verwenden.

Hierzu werden öffentlich zugängliche astronomische Kataloge als Quellen vorgesehen.

Die wissenschaftlichen Quelldaten bleiben von den durch die Spielsimulation veränderlichen Informationen getrennt.

## 3.2 Gaia

Gaia bildet eine zentrale astronomische Datenquelle.

Insbesondere Gaia DR3 wird als Ausgangsbasis für die Sternenpositionen vorgesehen.

Relevante Informationen sind unter anderem:

- Position am Himmel.
- Parallaxe und daraus ableitbare Entfernungsinformationen.
- Sternhelligkeit.
- Eigenbewegung.
- Radialgeschwindigkeit, soweit verfügbar.
- Weitere astrophysikalische Eigenschaften.

Nicht jeder Gaia-Datensatz besitzt sämtliche Informationen in gleicher Qualität.

Die Spielwelt muss deshalb auch unvollständige oder unsichere Angaben berücksichtigen können.

## 3.3 Hipparcos

Hipparcos kann als ergänzende astronomische Datenquelle verwendet werden.

Die Daten können beispielsweise für den Abgleich von Sternidentifikatoren und die Ergänzung ausgewählter Sterninformationen genutzt werden.

Sterne, die in mehreren Katalogen vorkommen, dürfen innerhalb der Spielwelt nicht versehentlich mehrfach angelegt werden.

## 3.4 NASA Exoplanet Archive

Das NASA Exoplanet Archive dient als vorgesehene Quelle für wissenschaftlich bekannte Exoplaneten.

Für einen Exoplaneten können je nach Datenlage unter anderem bekannt sein:

- Zugehöriger Zentralstern.
- Umlaufperiode.
- Große Halbachse.
- Planetengröße.
- Planetenmasse.
- Exzentrizität.
- Weitere Bahneigenschaften.

Unbekannte Eigenschaften werden bei Bedarf ergänzt.

Es wird nicht vorausgesetzt, dass für jeden wissenschaftlich bekannten Exoplaneten eine vollständig rekonstruierbare dreidimensionale Umlaufbahn existiert.

## 3.5 Unterschiedliche Datenherkunft

Jede relevante astronomische Eigenschaft soll einer Herkunftskategorie zugeordnet werden.

| Kategorie | Bedeutung |
|---|---|
| Beobachtet | Wissenschaftlich gemessene Eigenschaft |
| Geschätzt | Wissenschaftlich abgeleitete Eigenschaft |
| Generiert | Durch die Spielwelt erzeugte Eigenschaft |
| Fiktiv | Bewusst erfundenes Spielelement |

Die Herkunft wird möglichst für einzelne Eigenschaften geführt.

Ein Planet kann somit gleichzeitig beobachtete und generierte Eigenschaften besitzen.

Beispielsweise kann seine Umlaufperiode bekannt sein, während Temperatur, Atmosphäre und Oberflächenbedingungen generiert werden müssen.

## 3.6 Wissenschaftliche Unsicherheit

Messwerte sind nicht grundsätzlich exakt.

Die astronomische Datenbasis soll daher vorhandene Unsicherheiten und Qualitätsinformationen berücksichtigen können.

Falls eine Entfernung oder andere wesentliche Eigenschaft nicht zuverlässig bestimmt werden kann, wird diese Unsicherheit dokumentiert.

Für die Spielsimulation darf gegebenenfalls ein plausibler Ersatzwert verwendet werden, dessen Herkunft entsprechend gekennzeichnet ist.

Die wissenschaftliche Beobachtung selbst wird dabei nicht überschrieben.

---

# 4. Prozedurale Ergänzung der Galaxie

## 4.1 Grundprinzip

Die wissenschaftlich bekannten Daten bilden die Grundlage.

Da nicht sämtliche Sterne, Planeten und Monde der Milchstraße vollständig bekannt sind, ergänzt das Spiel fehlende Informationen durch ein prozedurales Generierungssystem.

Die Generierung soll sich an den verfügbaren astronomischen Eigenschaften orientieren.

## 4.2 Mögliche Ergänzungen

Prozedural ergänzt werden können:

- Noch nicht dokumentierte Planeten.
- Zusätzliche Monde.
- Asteroidengürtel.
- Fehlende Umlaufbahnparameter.
- Planetare Atmosphären.
- Planetentemperaturen.
- Geologische Eigenschaften.
- Ressourcenverteilungen.
- Weitere astronomisch plausible Systembestandteile.

Langfristig können auch zusätzliche Sterne in nicht ausreichend katalogisierten Bereichen der Milchstraße vorgesehen werden.

## 4.3 Wissenschaftliche Eigenschaften haben Vorrang

Bereits bekannte Eigenschaften dürfen nicht willkürlich durch generierte Werte ersetzt werden.

Ein wissenschaftlich dokumentierter Stern bleibt an seiner entsprechenden astronomischen Position.

Eine bekannte Umlaufperiode wird übernommen.

Generiert werden nur die notwendigen Ergänzungen.

## 4.4 Plausibilität

Die Generierung soll nach Möglichkeit berücksichtigen:

- Sternklasse.
- Sternmasse.
- Sternleuchtkraft.
- Planetengrößen.
- Temperaturverhältnisse.
- Plausible Planetenabstände.
- Vereinfacht geprüfte Stabilität der Umlaufbahnen.
- Eigenschaften von Einzel- und Mehrfachsternsystemen.

Die Spielwelt darf fiktive Elemente enthalten, soll jedoch bei gewöhnlichen astronomischen Objekten nachvollziehbare physikalische Zusammenhänge berücksichtigen.

## 4.5 Reproduzierbarkeit

Ein einmal generiertes Sternensystem muss dauerhaft dieselben astronomischen Eigenschaften besitzen.

Die Generierung erfolgt deshalb deterministisch.

Gleiche Ausgangsdaten, Objektkennungen und Generierungsparameter müssen dieselben Ergebnisse erzeugen.

Das erneute Öffnen eines Systems darf keine neuen Planeten oder veränderten Umlaufbahnen verursachen.

## 4.6 Erweiterbarkeit

Das Konzept lässt offen, ob langfristig ein eigenständiges Generierungssystem namens StellarForge zur Ergänzung weiterer Milchstraßenbereiche eingesetzt wird.

Eine solche Erweiterung muss mit den vorhandenen astronomischen Daten und der gemeinsamen Objektstruktur kompatibel bleiben.

---

# 5. Dreidimensionale Galaxiekarte

## 5.1 Grunddarstellung

Die Galaxiekarte stellt Sternensysteme innerhalb eines frei navigierbaren dreidimensionalen Raums dar.

Der Spieler blickt nicht auf eine zweidimensionale Karte mit symbolischen Verbindungen, sondern auf die räumliche Verteilung der Sterne.

Der visuelle Stil soll sich an modernen astronomischen Visualisierungen und der räumlichen Lesbarkeit der Galaxiekarte von Elite Dangerous orientieren.

Die konkrete Gestaltung von Symbolen, Oberfläche und visuellen Effekten wird eigenständig entwickelt.

## 5.2 Darstellung der Sterne

Ein Stern wird als gut erkennbares astronomisches Kartenobjekt dargestellt.

Seine visuelle Erscheinung kann folgende Eigenschaften berücksichtigen:

- Spektralklasse.
- Temperatur.
- Farbe.
- Helligkeit.
- Entfernung zur Kamera.
- Ausgewählten beziehungsweise hervorgehobenen Zustand.

Die tatsächliche Größe eines Sterns und die sichtbare Größe seines Kartensymbols müssen nicht identisch sein.

Eine visuelle Vergrößerung dient ausschließlich der Erkennbarkeit.

## 5.3 Darstellung unterschiedlicher Entfernungen

Die Karte muss große Entfernungsunterschiede sinnvoll vermitteln.

Dazu gehören Sterne in unmittelbarer Nähe des Sonnensystems ebenso wie weit entfernte Sternregionen.

Die Kamera soll sich zwischen unterschiedlichen Maßstabsebenen bewegen können.

Die astronomischen Positionen bleiben unabhängig von der jeweiligen Zoomstufe erhalten.

## 5.4 Beschriftungen

Die Karte soll Sternnamen und weitere Informationen anzeigen können.

Dabei dürfen Beschriftungen bei hoher Sterndichte nicht die gesamte Ansicht überdecken.

Vorgesehen ist eine situationsabhängige Anzeige:

- Ausgewählte Sterne erhalten eine hervorgehobene Beschriftung.
- Bedeutende oder bekannte Systeme können bevorzugt angezeigt werden.
- Bei größerer Annäherung werden zusätzliche Namen sichtbar.
- Bei großer Entfernung werden weniger Details eingeblendet.

## 5.5 Sternenauswahl

Der Spieler kann ein Sternensystem durch direkte Auswahl auf der Karte markieren.

Die Auswahl öffnet eine Informationsansicht.

Diese zeigt die verfügbaren astronomischen und spielrelevanten Eigenschaften.

Eine Auswahl bedeutet noch keinen automatischen Wechsel in die Sternensystemansicht.

Der Spieler soll das System zunächst untersuchen und anschließend gezielt öffnen können.

## 5.6 Suche

Eine Suchfunktion soll das Auffinden bekannter astronomischer Objekte ermöglichen.

Gesucht werden kann beispielsweise nach:

- Sternname.
- Alternativer Bezeichnung.
- Wissenschaftlicher Katalogkennung.
- Sternensystemname.
- Namen einer bekannten Kolonie.

Die Suche soll passende Ergebnisse zur Auswahl anbieten und die Karte auf das betreffende Objekt ausrichten können.

---

# 6. Kamerasystem der Galaxiekarte

## 6.1 Freie Bewegung

Der Spieler soll die Galaxiekamera frei bewegen können.

Vorgesehen sind:

- Bewegung innerhalb des dreidimensionalen Raums.
- Drehen.
- Neigen.
- Zoomen.
- Zentrieren ausgewählter Objekte.
- Wechsel zu gespeicherten beziehungsweise bekannten Positionen.

## 6.2 Objektfokus

Bei Auswahl eines Sternensystems kann die Kamera dieses automatisch in den Fokus nehmen.

Dabei bleibt die räumliche Orientierung erhalten.

Die Bewegung soll visuell nachvollziehbar sein, damit der Spieler seine Position innerhalb der Galaxie nicht unnötig verliert.

## 6.3 Kartenübergang

Wird ein ausgewähltes Sternensystem geöffnet, erfolgt ein Übergang von der Galaxieansicht in die Sternensystemansicht.

Der Übergang soll deutlich machen, dass der Spieler von einer übergeordneten strategischen Karte in ein einzelnes Sternensystem wechselt.

Beim Verlassen des Systems erfolgt die Rückkehr zur Galaxieansicht.

Die vorherige Kartenposition und Orientierung sollen dabei wiederhergestellt werden können.

---

# 7. Dreidimensionale Sternensystemansicht

## 7.1 Grundprinzip

Jedes auswählbare Sternensystem besitzt eine eigene dreidimensionale Systemansicht.

Diese stellt die astronomischen Objekte innerhalb des Systems räumlich dar.

Im Gegensatz zur Galaxiekarte werden hier nicht die Entfernungen zwischen Sternensystemen, sondern die lokalen Positionen und Umlaufbahnen innerhalb eines Systems sichtbar.

## 7.2 Einzelsternsysteme

Bei einem System mit einem einzelnen Zentralstern bildet dieser den räumlichen Mittelpunkt.

Planeten und weitere zugehörige Objekte bewegen sich auf ihren festgelegten Bahnen um diesen Stern.

Die Kamera öffnet das System zunächst mit einer sinnvollen Übersicht.

## 7.3 Doppelsternsysteme

Ein Doppelsternsystem besitzt zwei Sternkomponenten.

Diese können auf festen Bahnen um einen gemeinsamen Schwerpunkt dargestellt werden.

Planeten können, abhängig von ihrer Konfiguration, einen einzelnen Stern oder beide Sterne gemeinsam umkreisen.

Die Darstellung orientiert sich an den vorhandenen astronomischen Daten beziehungsweise an plausiblen generierten Bahnen.

## 7.4 Mehrfachsternsysteme

Sternensysteme mit mehr als zwei Sternen verwenden eine geeignete hierarchische Orbitalstruktur.

Dadurch können unterschiedliche Komponenten ihre festgelegten Bahnen um die jeweils passenden Zentren beschreiben.

Es findet auch hier keine Gravitationssimulation statt.

## 7.5 Planeten

Planeten werden als räumlich positionierte astronomische Kartenobjekte dargestellt.

Eine detaillierte, frei bebaubare dreidimensionale Planetenoberfläche ist ausdrücklich nicht vorgesehen.

Für die Sternensystemansicht genügen geeignete Symbole oder vereinfachte visuelle Darstellungen.

Die tatsächliche Kolonieverwaltung findet in einem zweidimensionalen Fenster statt.

## 7.6 Monde

Monde besitzen eine feste Umlaufbahn um ihren jeweiligen Planeten.

Sie bewegen sich gemeinsam mit dem Planeten um das übergeordnete Orbitalzentrum.

Ihre aktuelle räumliche Position ergibt sich aus dieser hierarchischen Zuordnung.

## 7.7 Asteroiden und Kleinkörper

Asteroidengürtel sollen als astronomisch plausible Ansammlungen kleiner Objekte dargestellt werden.

Die Darstellung kann vereinfacht werden, wenn sehr viele Kleinkörper vorhanden sind.

Einzelne wirtschaftlich oder spielerisch relevante Asteroiden können separat auswählbar sein.

## 7.8 Künstliche Objekte

Die Sternensystemansicht soll später auch künstliche Objekte anzeigen.

Dazu gehören:

- Raumstationen.
- Raumhäfen beziehungsweise orbitale Einrichtungen.
- Sprungtore.
- Raumschiffe.
- Raumflotten.
- Weitere Weltrauminfrastruktur.

Ihre Positionen werden vom jeweiligen Spielsystem bereitgestellt.

Nicht jedes künstliche Objekt muss zwingend einer natürlichen Planetenumlaufbahn folgen.

---

# 8. Feste Umlaufbahnen

## 8.1 Verbindliche Regel

**Alle natürlichen astronomischen Objekte bewegen sich auf festgelegten Umlaufbahnen.**

Es wird keine dynamische Gravitationssimulation durchgeführt.

Die Umlaufbahnen werden aus astronomischen Daten übernommen oder einmalig prozedural generiert.

Anschließend werden ihre Eigenschaften gespeichert.

## 8.2 Bahnparameter

Eine Umlaufbahn kann durch folgende Eigenschaften beschrieben werden:

| Eigenschaft | Bedeutung |
|---|---|
| Orbitalzentrum | Stern, Planet oder gemeinsamer Schwerpunkt |
| Große Halbachse | Geometrische Größe der Bahn |
| Exzentrizität | Abweichung von einer kreisförmigen Bahn |
| Inklination | Neigung der Bahnebene |
| Aufsteigender Knoten | Räumliche Ausrichtung |
| Argument des Perizentrums | Orientierung der Bahnellipse |
| Ausgangsphase | Position zu einem definierten Zeitpunkt |
| Umlaufperiode | Dauer eines vollständigen Umlaufs |
| Bezugsepoche | Zeitlicher Ausgangspunkt der Bahn |

Die genaue mathematische Darstellung wird in einem späteren technischen Dokument beschrieben.

## 8.3 Keine Gravitationssimulation

Die Simulation berechnet nicht fortlaufend die Gravitationskräfte zwischen den Himmelskörpern.

Insbesondere entstehen keine dynamischen Änderungen durch:

- Gegenseitige gravitative Störungen.
- Numerische N-Körper-Simulationen.
- Veränderungen der Stern- oder Planetenmassen.
- Automatisch entstehende neue Orbitkonfigurationen.

Die festgelegten Bahnen bleiben während des regulären Spielverlaufs erhalten.

## 8.4 Bewegung abhängig von der Spielzeit

Die Position eines Planeten hängt von seiner Umlaufbahn und der aktuellen Spielzeit ab.

Wird das Spiel pausiert, steht der Planet still.

Wird die Zeit beschleunigt, bewegt sich der Planet entsprechend schneller auf seiner Bahn.

Bei identischer Spielzeit und identischen Bahndaten muss die Position reproduzierbar sein.

## 8.5 Astronomische Genauigkeit

Sind ausreichend wissenschaftliche Bahndaten vorhanden, sollen diese verwendet werden.

Fehlende Parameter können plausibel ergänzt werden.

Dabei muss zwischen tatsächlichen Messdaten und generierten Eigenschaften unterschieden werden.

Die Position einer teilweise unbekannten Umlaufbahn darf nicht als vollständig wissenschaftlich bestimmt ausgegeben werden.

## 8.6 Sichtbare Umlaufbahnen

Umlaufbahnen sollen optional als Linien dargestellt werden können.

Vorgesehen sind folgende Anzeigemöglichkeiten:

- Alle relevanten Umlaufbahnen.
- Nur die Bahn des ausgewählten Objekts.
- Ausgeblendete Umlaufbahnen.
- Zusätzliche Bahndaten des ausgewählten Objekts.

Die Linien dienen der visuellen Orientierung.

---

# 9. Objektverfolgung und Planetenverwaltung

## 9.1 Planetenfokus

Wählt der Spieler einen Planeten aus, kann die Kamera dessen Bewegung verfolgen.

Der Planet bleibt dabei im Zentrum der Ansicht.

Die Kamera passt ihre Position entsprechend der aktuellen Umlaufposition an.

## 9.2 Verwaltung öffnen

Für besiedelte oder kolonisierbare Planeten kann ein eigenes Verwaltungsfenster geöffnet werden.

Die Kamera bleibt währenddessen auf den betreffenden Planeten ausgerichtet.

Die Verwaltung selbst wird in einer zweidimensionalen Benutzeroberfläche angezeigt.

## 9.3 Trennung von Karte und Verwaltung

Die Sternensystemansicht zeigt:

- Lage des Planeten.
- Umlaufbahn.
- Zugehörigen Stern.
- Monde.
- Astronomische Eigenschaften.
- Vorhandene künstliche Objekte.

Die Planetenverwaltung zeigt dagegen:

- Kachelraster.
- Gebäude.
- Bevölkerung.
- Ressourcen.
- Produktion.
- Wohnraum.
- Bildung.
- Weitere Koloniewerte.

Die Map darf nicht versuchen, diese planetaren Verwaltungsfunktionen auf einer dreidimensionalen Kugel abzubilden.

## 9.4 Planetengröße und Kacheln

Die bereits vereinbarte Kachelskalierung bleibt Bestandteil des gesamten Spielkonzepts.

Ein erdgroßer Planet besitzt 60 Verwaltungskacheln.

Andere Planeten werden proportional zu ihrer Oberfläche skaliert.

Die genaue Anzahl der Kacheln ist für die Darstellung der Sternenkarte selbst nicht entscheidend, muss aber bei der Übergabe an die Planetenverwaltung korrekt verfügbar sein.

---

# 10. Astronomische Objektinformationen

## 10.1 Sterne

Bei Auswahl eines Sterns können die verfügbaren Eigenschaften angezeigt werden.

Beispiele:

- Name und alternative Bezeichnungen.
- Spektralklasse.
- Temperatur.
- Masse.
- Radius.
- Leuchtkraft.
- Entfernung.
- Zugehöriges Sternensystem.
- Datenherkunft.

Nicht bekannte Eigenschaften werden entsprechend gekennzeichnet.

## 10.2 Planeten

Bei Auswahl eines Planeten sollen unter anderem folgende Informationen angezeigt werden können:

- Planetenname.
- Planetenklasse.
- Zentralstern.
- Radius.
- Masse.
- Temperatur.
- Atmosphärische Eigenschaften.
- Umlaufperiode.
- Entfernung zum Zentralstern.
- Monde.
- Bewohnbarkeit.
- Kolonisierungsstatus.

## 10.3 Planetenklassen

Die Klassifikation orientiert sich am erweiterten, aus Star Trek bekannten Buchstabensystem.

Sie wird durch eigene eindeutige Definitionen für Project Sagittarius umgesetzt.

Die Planetenklasse dient zur Beschreibung der Umwelt.

Die tatsächliche Bewohnbarkeit ist abhängig von den biologischen Eigenschaften der jeweiligen Spezies.

Ein Planet der Klasse M kann für Menschen geeignet sein, für eine andere Spezies jedoch ungeeignet.

Umgekehrt können für Menschen lebensfeindliche Welten von entsprechend angepassten Spezies bewohnt werden.

## 10.4 Bewohnbarkeit als Karteninformation

Die Map kann die Bewohnbarkeit eines Planeten für die ausgewählte Spezies anzeigen.

Die eigentliche Berechnung erfolgt im planetaren Bewohnbarkeitssystem.

Die Karte übernimmt das Ergebnis und stellt es verständlich dar.

---

# 11. Interstellare Navigation

## 11.1 Rolle der Sternenkarte

Die Sternenkarte dient als zentrale Oberfläche zur Planung und Darstellung interstellarer Reisen.

Der Spieler kann Start- und Zielsysteme auswählen und die geplante Reiseroute anzeigen lassen.

Die Route wird unter Berücksichtigung tatsächlicher dreidimensionaler Sternentfernungen und der bestehenden Raumfahrttechnologien berechnet.

## 11.2 Warpantrieb

Die Raumfahrt verwendet neun Warpstufen.

Die bisher vorgeschlagenen Geschwindigkeiten sind:

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

Diese Geschwindigkeiten sind vorläufige Balancewerte.

Die tatsächliche Reisedauer ergibt sich aus Entfernung und Warpgeschwindigkeit.

Eine gemeinsam reisende Flotte orientiert sich an der Geschwindigkeit ihres langsamsten Schiffes.

## 11.3 Stern-zu-Stern-Navigation

Interstellare Reisen erfolgen zwischen Sternensystemen.

Die Route kann über mehrere Zwischenstationen führen.

Der Routenplaner sucht eine zulässige, zeitlich günstige Verbindung.

Welche zusätzlichen Regeln für maximale Einzeletappen oder die Auswahl möglicher Zwischenstationen gelten, wird später festgelegt.

## 11.4 Sprungtore

Sprungtore sind von Fraktionen errichtete künstliche Einrichtungen.

Sie ermöglichen sofortige Reisen zwischen zugänglichen Toren.

Die bisher festgelegten Zugriffsregeln gelten weiterhin:

- Eigene Sprungtore sind zugänglich.
- Sprungtore befreundeter Fraktionen sind zugänglich.
- Sprungtore verbündeter Fraktionen sind zugänglich.
- Neutrale und feindliche Tore sind ohne zusätzliche Berechtigungen nicht zugänglich.

Die Map zeigt vorhandene Sprungtore und ihre Nutzbarkeit an.

## 11.5 Kombinierte Routen

Eine interstellare Route kann sowohl Warpstrecken als auch Sprungtorpassagen enthalten.

Beispiel:

`Startsystem → Warpstrecke → Sprungtor A → Sprungtor B → Warpstrecke → Zielsystem`

Sprungtorpassagen benötigen keine Spielzeit.

Alle anderen zeitbeanspruchenden Reiseabschnitte werden zur Gesamtreisezeit addiert.

## 11.6 Routenanzeige

Die Sternenkarte soll folgende Informationen darstellen können:

- Ausgangssystem.
- Zielsystem.
- Zwischenstationen.
- Warpstrecken.
- Sprungtorverbindungen.
- Geschätzte Gesamtreisezeit.
- Nicht zugängliche Verbindungen.
- Aktueller Standort eines Schiffes.

Die Darstellung soll unterschiedliche Arten von Reiseabschnitten erkennbar machen.

## 11.7 Änderungen während einer Reise

Routen können durch Ereignisse ungültig werden.

Beispiele:

- Ein Sprungtor wird zerstört.
- Ein Sprungtor fällt aus.
- Diplomatische Zugriffsrechte ändern sich.
- Ein Zwischenziel wird unzugänglich.

In solchen Fällen muss die Navigation eine erneute Routenplanung ermöglichen.

Die konkrete Behandlung bereits laufender Flugabschnitte gehört zum späteren Raumfahrtkonzept.

---

# 12. Transportnetzwerke

## 12.1 Unterschied zwischen Navigation und Transport

Nicht jede technisch mögliche Flugroute ist eine tatsächlich betriebene Transportverbindung.

Die Sternenkarte muss daher zwischen zwei unterschiedlichen Informationen unterscheiden:

**Mögliche Flugroute**

Eine Verbindung, die ein geeignetes Raumschiff unter den geltenden Navigationsregeln zurücklegen könnte.

**Aktive Transportlinie**

Eine tatsächlich bestehende Verbindung, die von Transportschiffen bedient wird.

## 12.2 Personentransport

Das Bevölkerungssystem verwendet vorhandene Transportschiffe, um Bewohner zwischen Kolonien umzusiedeln.

Voraussetzung sind passende Arbeitskräfteüberschüsse, ein Bedarf am Ziel und eine tatsächlich bestehende Transportverbindung.

Mehrgliedrige Transportwege mit Umstiegen sind zulässig.

Die Karte soll diese Verbindungen später anzeigen können.

## 12.3 Warentransport

Materielle Ressourcen und Produkte werden ebenfalls über geeignete Transportverbindungen zwischen Kolonien bewegt.

Die Sternenkarte stellt bestehende Verbindungen, Transportwege und relevante Verkehrsknoten dar.

Die Wirtschaft selbst wird nicht innerhalb der Map berechnet.

## 12.4 Strategische Bedeutung

Transportverbindungen können die wirtschaftliche Bedeutung eines Sternensystems erhöhen.

Ein System mit mehreren wichtigen Verbindungen kann als Verkehrsknoten dienen.

Die Unterbrechung einer solchen Verbindung kann Auswirkungen auf Handel und Bevölkerungsmigration haben.

Diese Zusammenhänge sollen auf der Sternenkarte sichtbar werden können.

---

# 13. Politische und strategische Darstellung

## 13.1 Fraktionszugehörigkeit

Sternensysteme können einer Fraktion zugeordnet sein oder keiner Fraktion gehören.

Die politische Kontrolle wird aus dem Spielzustand übernommen.

Sie verändert nicht die astronomischen Positionen der Sterne.

## 13.2 Fraktionsgebiete

Die Galaxiekarte soll politische Einflussbereiche darstellen können.

Die Darstellung muss berücksichtigen, dass Sternensysteme im dreidimensionalen Raum verteilt sind.

Eine ausschließlich flache, zweidimensionale Grenzdarstellung wäre daher nicht ausreichend.

Die konkrete Visualisierung von Einflussbereichen bleibt zunächst offen.

## 13.3 Kolonien

Besiedelte Systeme sollen als solche erkennbar sein.

Bei Bedarf können folgende Informationen eingeblendet werden:

- Anzahl der Kolonien.
- Kontrollierende Fraktion.
- Bevölkerungsgröße.
- Kolonietyp.
- Wirtschaftliche Bedeutung.

Die Informationen stammen aus der Koloniesimulation.

## 13.4 Raumflotten

Eigene und bekannte fremde Flotten sollen in der Karte angezeigt werden können.

Die Darstellung umfasst:

- Aktuellen Standort.
- Zugehörige Fraktion.
- Bewegungsstatus.
- Geplante Route, soweit bekannt.
- Zielsystem.

Die Sichtbarkeit fremder Flotten hängt später vom Erkundungs- und Sensorsystem ab.

## 13.5 Strategische Einrichtungen

Zu den anzuzeigenden Einrichtungen gehören:

- Raumstationen.
- Raumwerften.
- Sprungtore.
- Militärische Stützpunkte.
- Transportknoten.
- Weitere wichtige Weltrauminfrastruktur.

---

# 14. Kartenfilter und Informationsansichten

## 14.1 Grundprinzip

Die Sternenkarte soll unterschiedliche Informationsschichten anbieten.

Der Spieler kann dadurch gezielt die Informationen anzeigen, die für eine bestimmte strategische Entscheidung relevant sind.

## 14.2 Vorgesehene Informationsschichten

| Ansicht | Schwerpunkt |
|---|---|
| Astronomisch | Sterne und astronomische Eigenschaften |
| Erkundung | Bekannte und unbekannte Systeme |
| Politisch | Fraktionen und Einflussbereiche |
| Kolonien | Besiedelte Systeme |
| Wirtschaft | Wirtschaftsstandorte |
| Ressourcen | Bekannte Rohstoffvorkommen |
| Transport | Aktive Waren- und Passagierlinien |
| Navigation | Warpstrecken und Sprungtore |
| Militär | Flotten und militärische Einrichtungen |

Diese Ansichten verändern ausschließlich die Darstellung.

Sie erzeugen keine abweichenden astronomischen Karten.

## 14.3 Kombination von Informationen

Der Spieler soll mehrere relevante Informationen miteinander vergleichen können.

Beispielsweise können politische Gebiete zusammen mit Sprungtoren oder Kolonien zusammen mit Transportrouten dargestellt werden.

Die konkrete Zahl gleichzeitig aktivierbarer Informationsschichten bleibt offen.

## 14.4 Übersichtlichkeit

Mit zunehmender Informationsdichte muss die Map unwichtige Details zurücknehmen können.

Ausgewählte Objekte und aktuelle Aufträge sollen weiterhin gut erkennbar bleiben.

---

# 15. Erkundung und Wissen

## 15.1 Astronomische Daten und Zivilisationswissen

Die Datenbasis des Spiels und das Wissen einer Fraktion sind zwei unterschiedliche Dinge.

Die Spielwelt kann die tatsächlichen astronomischen Eigenschaften eines Sternensystems kennen, ohne dass die betreffende Zivilisation diese bereits erforscht oder untersucht hat.

## 15.2 Sichtbarkeit

Als konzeptionelle Grundlage können folgende Wissenszustände verwendet werden:

| Zustand | Bedeutung |
|---|---|
| Unbekannt | Der Fraktion fehlen Informationen über das System |
| Bekannt | Position und grundlegende Informationen sind vorhanden |
| Erkundet | Ein Raumschiff hat das System untersucht |
| Vermessen | Weitergehende astronomische Eigenschaften wurden ermittelt |

Die genauen Übergänge zwischen den Zuständen gehören zum späteren Erkundungskonzept.

## 15.3 Wissenschaftliche Realität

Der Erkundungszustand darf die Herkunft wissenschaftlicher Daten nicht verändern.

Ein in Gaia dokumentierter Stern bleibt ein realer astronomischer Datensatz, selbst wenn eine Spielfraktion seine Eigenschaften noch nicht kennt.

Die Map muss diese beiden Informationsebenen getrennt behandeln können.

---

# 16. Maßstäbe und Darstellung

## 16.1 Astronomische Maßstäbe

Die tatsächlichen Entfernungen zwischen Sternen sind wesentlich größer als die typischen Abstände innerhalb eines Sternensystems.

Die Galaxie- und Sternensystemansichten sollen deshalb jeweils geeignete lokale Darstellungsmaßstäbe verwenden.

## 16.2 Darstellung gegenüber Simulation

Für die Spielsimulation maßgeblich sind:

- Astronomische Positionen.
- Tatsächliche Entfernungen.
- Festgelegte Orbitalparameter.
- Aktuelle Spielzeit.

Die visuelle Darstellung darf dagegen Symbole vergrößern oder Informationen vereinfachen, damit die Karte bedienbar bleibt.

## 16.3 Keine Verzerrung der Navigation

Eine visuelle Anpassung darf niemals die reale Entfernung zwischen Sternensystemen verändern.

Auch Warp-Reisezeiten müssen auf den tatsächlichen räumlichen Entfernungen beruhen.

## 16.4 Lokale Sternensystemdarstellung

Innerhalb eines Sternensystems können Sterne und Planeten stark unterschiedliche Größen besitzen.

Die Darstellung soll deshalb die räumliche Orientierung ermöglichen, ohne vollständige maßstabsgetreue Planetenkugeln vorauszusetzen.

Für auswählbare Planeten sind geeignete Kartensymbole ausreichend.

---

# 17. Verhalten bei großen Datenmengen

## 17.1 Langfristige Zielsetzung

Die Sternenkarte soll langfristig sehr große Teile der Milchstraße darstellen können.

Das Konzept setzt nicht voraus, dass sämtliche astronomischen Objekte ständig vollständig geladen oder als eigenständige grafische Objekte vorhanden sind.

## 17.2 Unterschiedliche Detailgrade

Je nach Entfernung und Betrachtungssituation kann die visuelle Darstellung unterschiedlich detailliert sein.

Beispielsweise:

- Große Entfernung: vereinfachte Sternsymbole.
- Mittlere Entfernung: zusätzliche Sterninformationen.
- Ausgewählte Systeme: ausführlichere Informationsanzeige.
- Geöffnetes Sternensystem: vollständige lokale Systemdarstellung.

Die astronomischen Daten bleiben dabei konsistent.

## 17.3 Unabhängigkeit von der Kamera

Die Spielsimulation läuft unabhängig davon weiter, welchen Bereich der Spieler betrachtet.

Nicht sichtbare Sternensysteme müssen nicht dauerhaft grafisch animiert werden.

Ihre astronomischen Positionen müssen jedoch zu jedem relevanten Spielzeitpunkt bestimmt werden können.

## 17.4 Einheitliche Spielzeit

Alle Sternensysteme verwenden dieselbe zentrale Spielzeit.

Es darf nicht passieren, dass unterschiedliche Systeme aufgrund ihrer Sichtbarkeit mit voneinander abweichenden Zeitständen dargestellt werden.

---

# 18. Spielstände und dauerhafte Weltkonsistenz

## 18.1 Astronomische Stammdaten

Die verwendete astronomische Datenbasis besitzt einen definierten Versionsstand.

Ein Spielstand muss nachvollziehbar auf diese Datenbasis Bezug nehmen können.

## 18.2 Prozedurale Ergänzungen

Generierte Objekte und Eigenschaften bleiben über das Speichern und Laden erhalten.

Ein Planet darf nach dem Laden nicht eine andere Umlaufbahn oder eine andere astronomische Zusammensetzung erhalten.

## 18.3 Spielzustand

Der Spielstand enthält die veränderlichen Informationen der Spielwelt.

Dazu gehören beispielsweise:

- Spielzeit.
- Erkundungszustände.
- Politische Kontrolle.
- Kolonien.
- Flotten.
- Sprungtore.
- Transportverbindungen.
- Laufende Reiseaufträge.

## 18.4 Aktuelle Kartenansicht

Die aktuell ausgewählte Ansicht und der Kamerafokus sollen nach dem Laden wiederherstellbar sein.

Die Auswahl eines Planeten darf dabei keine Änderung seiner astronomischen Bahn verursachen.

## 18.5 Wissenschaftliche Datenupdates

Neue Versionen astronomischer Kataloge dürfen bestehende Spielstände nicht unkontrolliert verändern.

Ein laufendes Spiel soll seine zugrunde liegende astronomische Welt konsistent behalten.

Die konkrete Behandlung späterer Katalogupdates wird gesondert festgelegt.

---

# 19. Beispiel eines Spielablaufs

Der Spieler befindet sich in der dreidimensionalen Galaxiekarte.

Er sucht nach einem bestimmten Sternensystem.

Nach der Auswahl wird das System hervorgehoben.

Das Informationsfenster zeigt die verfügbaren astronomischen Eigenschaften und gegebenenfalls die politische Zugehörigkeit.

Der Spieler öffnet die Sternensystemansicht.

Die Kamera wechselt in das ausgewählte System.

Dort wird der Zentralstern beziehungsweise bei einem Mehrfachsternsystem die passende Sternenkonfiguration sichtbar.

Die Planeten bewegen sich auf ihren festgelegten Umlaufbahnen.

Der Spieler wählt einen Planeten aus.

Die Kamera richtet sich auf dessen aktuelle Position aus und folgt der Umlaufbewegung.

Das Informationsfenster zeigt beispielsweise die Planetenklasse, vorhandene Monde, die Umlaufperiode und die Bewohnbarkeit für die gewählte Spezies.

Ist eine Kolonie vorhanden, kann der Spieler die zweidimensionale Planetenverwaltung öffnen.

Dort verwaltet er Gebäude, Bevölkerung und Produktion über das Kachelraster.

Anschließend schließt er die Verwaltung und kehrt zur Sternensystemansicht zurück.

Über die Galaxiekarte kann er eine interstellare Reise zu einem anderen Sternensystem planen.

Die Karte zeigt eine gültige Route unter Berücksichtigung des vorhandenen Warpantriebs und zugänglicher Sprungtore.

Dieser Ablauf verbindet die verschiedenen Ansichten, ohne dass sie unterschiedliche astronomische Grundlagen verwenden.

---

# 20. Verbindliche Festlegungen

Für die Sternenkarte gelten die folgenden bereits vereinbarten Anforderungen:

1. Die Milchstraße wird dreidimensional dargestellt.
2. Reale astronomische Sternpositionen bilden die Grundlage.
3. Tatsächliche dreidimensionale Sternentfernungen werden berücksichtigt.
4. Fehlende astronomische Informationen können deterministisch generiert werden.
5. Wissenschaftliche und generierte Eigenschaften bleiben unterscheidbar.
6. Ein Sternensystem kann aus der Galaxiekarte ausgewählt werden.
7. Die Auswahl eines Systems ermöglicht den Wechsel in eine lokale 3D-Sternensystemansicht.
8. Bei Einzelsternsystemen bildet der Zentralstern den räumlichen Mittelpunkt.
9. Doppel- und Mehrfachsternsysteme verwenden passende hierarchische Bahnstrukturen.
10. Planeten und Monde besitzen festgelegte Umlaufbahnen.
11. Eine Gravitationssimulation findet nicht statt.
12. Die Bewegung der Himmelskörper hängt von der Spielzeit ab.
13. Die Kamera kann ausgewählte Planeten verfolgen.
14. Die Planetenverwaltung erfolgt in einem separaten 2D-Fenster.
15. Es gibt keine dreidimensional bebaubare Planetenoberfläche.
16. Die interstellare Navigation verwendet echte räumliche Sternentfernungen.
17. Raumschiffe verwenden Warpantriebe mit neun Stufen.
18. Sprungtore werden von Fraktionen errichtet.
19. Eine zugängliche Sprungtorpassage benötigt keine Spielzeit.
20. Eigene, befreundete und verbündete Fraktionen dürfen die entsprechenden Sprungtore benutzen.
21. Warpreisen und Sprungtorpassagen dürfen in einer Route kombiniert werden.
22. Eine mögliche Flugroute ist nicht automatisch eine aktive Transportschiffverbindung.
23. Astronomische Daten, Spielzustand und grafische Darstellung bleiben voneinander getrennt.
24. Die Sternenkarte soll langfristig große astronomische Datenbestände unterstützen.

---

# 21. Noch offene konzeptionelle Entscheidungen

Die folgenden Fragen bleiben bewusst offen und sind keine bereits beschlossenen Spielregeln.

## 21.1 Sichtbarkeit der Milchstraße

Soll die gesamte astronomische Sternenkarte von Spielbeginn an sichtbar sein, oder werden Sternregionen erst durch Erkundung freigegeben?

Eine Unterscheidung zwischen bekannten Sternpositionen und unbekannten planetaren Eigenschaften ist ebenfalls möglich.

## 21.2 Umfang der Galaxie

Wie groß soll der tatsächlich bespielbare Bereich der Milchstraße sein?

Die langfristige Ausrichtung ist eine möglichst umfangreiche Milchstraßendarstellung.

Die konkreten Grenzen werden später entschieden.

## 21.3 Sternbewegung

Sollen sich Sterne selbst aufgrund ihrer astronomischen Eigenbewegung während langer Spielzeiträume sichtbar verändern?

Die festgelegten planetaren Umlaufbahnen bleiben von dieser Entscheidung unberührt.

## 21.4 Darstellung der Planeten

Wie detailliert sollen die Symbole für Planeten, Monde und andere Himmelskörper innerhalb der Sternensystemansicht gestaltet werden?

Die Entscheidung muss mit dem Verzicht auf eine dreidimensionale Planetenverwaltung vereinbar bleiben.

## 21.5 Erkundungsmechanik

Welche Informationen besitzt eine Zivilisation zu Spielbeginn?

Welche Eigenschaften müssen durch wissenschaftliche Erkundung freigeschaltet werden?

## 21.6 Stern-zu-Stern-Verbindungen

Welche Sternsysteme darf ein Raumschiff unmittelbar per Warp anfliegen?

Soll es eine maximale einzelne Warpetappe geben oder ausschließlich zeitabhängige Entfernungsberechnungen?

## 21.7 Reisen innerhalb eines Sternensystems

Welche Zeit benötigen Raumschiffe für die Bewegung zwischen Planeten, Raumstationen und Sprungtoren innerhalb desselben Systems?

Diese Regel wurde noch nicht abschließend definiert.

## 21.8 Politische Raumgrenzen

Wie sollen dreidimensionale Einfluss- und Hoheitsgebiete dargestellt werden?

Die Darstellung muss die tatsächliche räumliche Sternverteilung berücksichtigen.

## 21.9 Kartengestaltung

Welche konkreten Farben, Symbole, Informationsebenen und visuellen Effekte soll die Sternenkarte besitzen?

Die Gestaltung soll sich an der gewünschten astronomischen Atmosphäre orientieren, aber eine eigenständige visuelle Identität besitzen.

---

# 22. Zusammenfassung

Die Sternenkarte von Project Sagittarius bildet eine hybride, dreidimensionale Milchstraße.

Ihre Grundlage sind reale astronomische Daten, die durch plausible und reproduzierbare Inhalte ergänzt werden können.

Die Spielwelt besitzt zwei räumliche Ansichten:

**Galaxiekarte**

Sie zeigt Sternsysteme, tatsächliche dreidimensionale Sternpositionen, strategische Informationen und interstellare Routen.

**Sternensystemansicht**

Sie zeigt Sterne, Planeten, Monde und weitere Objekte innerhalb eines ausgewählten Systems.

Die natürlichen Himmelskörper bewegen sich auf festgelegten Umlaufbahnen. Eine Gravitationssimulation findet nicht statt.

Die Auswahl eines Planeten ermöglicht eine automatische Kameraverfolgung.

Die eigentliche Kolonieverwaltung erfolgt über ein zweidimensionales Fenster und bleibt von der räumlichen Sternenkarte getrennt.

Die Sternenkarte stellt damit die gemeinsame astronomische und räumliche Grundlage für die späteren Spielmechaniken dar, ohne selbst deren vollständige Simulation zu übernehmen.

**Dieses Dokument beschreibt ausschließlich das fachliche Spielkonzept der Sternenkarte. Es enthält keinen Entwicklungsplan, keinen Implementierungsplan und keine technische Aufgabenliste.**

**Dokumentversion: 0.2**

---

# Referenzen

## Astronomische Quellen

- [ESA Gaia Archive](https://gea.esac.esa.int/archive/)
- [ESA Gaia](https://www.esa.int/Science_Exploration/Space_Science/Gaia)
- [Hipparcos-Kataloge](https://www.cosmos.esa.int/web/hipparcos)
- [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/)

## Projektbezug

- [Project Sagittarius – GitHub-Repository](https://github.com/Drezael/project_sagittarius)
- [README](../../readme.md)
- [Forschungskonzept](../../project.md)

Die Datenquellen sind als konzeptionelle Grundlage vorgesehen. Datenqualität, konkrete Importverfahren und Nutzungsbedingungen werden gesondert behandelt.