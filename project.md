# Projekt Sternenreiche
## Forschungskonzept – Version 1.2
### Gemeinsame Forschungsleistung, parallele Forschungsprojekte und dauerhafte Fortschrittsspeicherung

**Status:** Verbindliche Überarbeitung des Forschungssystems aus Version 1.1  
**Grundlage:** Spielkonzept Version 1.1 einschließlich des bereits entworfenen Forschungsbaums mit 136 Technologien

---

# 1. Grundprinzip

Forschung basiert auf einem gemeinsamen, fraktionsweiten Forschungspunkte-Durchsatz.

Jeder tatsächlich forschende Wissenschaftler erzeugt pro Simulationstick eine definierte Menge an Forschungspunkten (FP).

Alle Wissenschaftler der Fraktion tragen zur gesamten Forschungsleistung bei.

Die während eines Ticks generierten Forschungspunkte werden auf sämtliche aktiven Forschungsprojekte verteilt.

Jede Technologie besitzt eine festgelegte Anzahl benötigter Forschungspunkte.

Sobald der angesammelte Projektfortschritt die benötigte Punktzahl erreicht, ist die Technologie erforscht.

## 1.1 Keine feste Forschungsdauer

Technologien erhalten keine unveränderliche Forschungsdauer mehr.

Stattdessen besitzen sie feste Forschungskosten.

Die tatsächliche Dauer ergibt sich aus:

- Anzahl der Wissenschaftler.
- Forschungsleistung je Wissenschaftler.
- Forschungseffizienz.
- Gebäudestufe der Forschungskomplexe.
- Anzahl und Priorität gleichzeitig laufender Forschungsprojekte.
- Verfügbarkeit von Energie und Betriebsmitteln.

Dadurch kann dieselbe Technologie in einem kleinen Imperium wesentlich länger dauern als in einem großen Imperium mit leistungsfähiger Forschungsinfrastruktur.

## 1.2 Forschungspunkte als Durchsatz

Forschungspunkte werden pro Tick erzeugt und unmittelbar aktiven Projekten zugeführt.

Es existiert kein zusätzliches globales Forschungspunktekonto, auf dem ungenutzte Punkte beliebig angespart werden können.

Dauerhaft gespeichert wird der Fortschritt der jeweiligen Technologie.

Wenn keine Forschungsprojekte laufen, entsteht kein nutzbares Forschungspunkteguthaben.

---

# 2. Wissenschaftler und Forschungskomplexe

## 2.1 Wissenschaftler

Wissenschaftler sind Bewohner mit der Bildungsstufe Akademiker, die in einem Forschungskomplex beschäftigt sind.

Nicht jeder Akademiker ist automatisch Wissenschaftler.

Ein Akademiker in einer Universität, einem Krankenhaus oder einer Fabrik erzeugt keine reguläre Forschungsleistung.

Nur tatsächlich in Forschungskomplexen beschäftigte Akademiker tragen zur technologischen Forschung bei.

## 2.2 Forschungskomplexe

Forschungskomplexe bleiben reguläre Gebäude.

Sie belegen genau eine Planetenkachel.

Ihre Ausbaustufen werden über Technologien freigeschaltet.

Ein Forschungskomplex besitzt:

- Eine maximale Anzahl an Wissenschaftlerarbeitsplätzen.
- Einen Stromverbrauch.
- Einen Bedarf an gegebenenfalls notwendigen Betriebsmitteln.
- Einen Forschungsleistungsfaktor.
- Eine technische Ausbaustufe.

Die Arbeitsplätze werden automatisch besetzt.

## 2.3 Forschungsleistung der Wissenschaftler

Jeder beschäftigte Wissenschaftler besitzt einen Basiswert für Forschungspunkte pro Tick.

Beispiel:

`1 Wissenschaftler = 10 Forschungspunkte pro Tick`

Die tatsächliche Leistung kann durch Gebäudeverbesserungen und andere Faktoren beeinflusst werden.

Insbesondere:

- Zufriedenheit.
- Arbeitsverfügbarkeit.
- Arbeitseffizienz.
- Forschungsgebäudestufe.
- Energieversorgung.
- Verfügbarkeit notwendiger Ressourcen.

## 2.4 Universitäten

Universitäten bleiben ausschließlich Bildungseinrichtungen.

Sie bilden Gebildete zu Akademikern aus.

Sie erzeugen selbst keine Forschungspunkte.

---

# 3. Berechnung der Forschungsleistung

## 3.1 Grundformel

Die gesamte Forschungsleistung einer Fraktion ergibt sich aus der Summe der effektiven Leistungen sämtlicher beschäftigter Wissenschaftler.

`Forschungspunkte pro Tick = Summe aller effektiven Wissenschaftlerleistungen`

## 3.2 Beispiel

Eine Fraktion besitzt fünf aktiv forschende Wissenschaftler.

Jeder erzeugt zehn Forschungspunkte pro Tick.

Damit ergibt sich:

`5 × 10 = 50 Forschungspunkte pro Tick`

Ein Forschungsprojekt benötigt insgesamt 5.000 Forschungspunkte.

Bei unveränderter Leistung und ohne weitere aktive Projekte:

`5.000 / 50 = 100 Ticks`

Die Forschung wird nach 100 Ticks abgeschlossen.

## 3.3 Effektive Forschungsleistung

Die individuelle Leistung wird durch die tatsächlichen Arbeitsbedingungen beeinflusst.

Vorgeschlagene Berechnung:

`Effektive FP = Basis-FP × Arbeitsverfügbarkeit × Arbeitseffizienz × Forschungsgebäudemodifikator × Betriebsfaktor`

Die Faktoren werden anhand der bereits bestehenden Bevölkerungs-, Gebäude- und Energieversorgungssysteme bestimmt.

## 3.4 Technologische Verbesserungen

Forschung kann die Leistung zukünftiger Forschungskomplexe verbessern.

Beispielsweise:

- Höhere Anzahl verfügbarer Forscherarbeitsplätze.
- Höhere Forschungspunkte je Wissenschaftler.
- Bessere Energieeffizienz.
- Geringerer Materialverbrauch.
- Verbesserte Forschungsanlagen.

Eine Modernisierung verbessert die Forschungsleistung, ohne bereits vorhandene Projektfortschritte zu verändern.

---

# 4. Parallele Forschungsprojekte

## 4.1 Gemeinsame Forschungsleistung

Alle Forschungskomplexe einer Fraktion erzeugen einen gemeinsamen Forschungspunkte-Durchsatz.

Dieser wird auf die gleichzeitig aktiven Projekte verteilt.

Ein Forschungskomplex muss nicht exklusiv einem bestimmten Projekt zugeordnet werden.

Damit entfällt die bisher vorgeschlagene Regel, nach der jeder Forschungskomplex nur ein eigenständiges Projekt betreiben darf.

## 4.2 Gleichmäßige Aufteilung

Als Standard werden alle aktiven Projekte gleichmäßig berücksichtigt.

Beispiel:

Gesamte Forschungsleistung: 60 FP pro Tick.

| Aktive Projekte | Forschungspunkte je Projekt und Tick |
|---|---:|
| 1 | 60 |
| 2 | 30 |
| 3 | 20 |
| 4 | 15 |
| 5 | 12 |

Die Gesamtsumme der verteilten Punkte darf die tatsächlich erzeugte Forschungsleistung nicht überschreiten.

## 4.3 Forschungsprioritäten

Als zusätzliche Steuerungsmöglichkeit wird vorgeschlagen, Forschungsprojekte unterschiedlich zu priorisieren.

Dafür können prozentuale Anteile der verfügbaren Forschungsleistung zugewiesen werden.

Beispiel:

- Projekt A: 50 %.
- Projekt B: 30 %.
- Projekt C: 20 %.

Bei 100 generierten FP pro Tick erhält Projekt A 50 FP, Projekt B 30 FP und Projekt C 20 FP.

Standardmäßig werden die Punkte gleichmäßig verteilt.

## 4.4 Fertigstellung während eines Ticks

Benötigt ein Projekt weniger Forschungspunkte als im aktuellen Tick zugewiesen wurden, wird nur die tatsächlich noch erforderliche Menge verbucht.

Die verbleibenden Punkte werden im selben Tick auf andere aktive und berechtigte Forschungsprojekte verteilt.

Sind keine weiteren aktiven Projekte vorhanden, verfallen die überschüssigen Punkte dieses Ticks.

---

# 5. Forschung starten

Ein Forschungsprojekt kann gestartet werden, wenn:

1. Die Technologie noch nicht vollständig erforscht wurde.
2. Sämtliche Forschungsvoraussetzungen erfüllt sind.
3. Die notwendigen allgemeinen Forschungsbedingungen erfüllt sind.
4. Die Fraktion über eine funktionsfähige Forschungsinfrastruktur verfügt.

Nach dem Start wird die Technologie in die Liste der aktiven Forschungsprojekte aufgenommen.

Sie erhält einen Anteil der pro Tick generierten Forschungspunkte.

Der Fortschritt wird dauerhaft der Technologie zugeordnet.

---

# 6. Forschung pausieren

Ein aktives Forschungsprojekt kann jederzeit pausiert werden.

Beim Pausieren:

- Bleibt der bisherige Forschungsfortschritt erhalten.
- Werden keine weiteren Forschungspunkte zugewiesen.
- Wird sein bisheriger Anteil an die übrigen aktiven Projekte verteilt.
- Bleibt die Technologie als pausiertes Projekt verfügbar.

Die Forschung kann später ohne Verlust des Fortschritts fortgesetzt werden.

---

# 7. Forschung abbrechen

## 7.1 Abbruch

Ein Forschungsprojekt darf jederzeit abgebrochen werden.

Dabei wird es aus der Liste der aktiven Forschungsprojekte entfernt.

**Der bisherige Forschungsfortschritt wird nicht gelöscht.**

## 7.2 Dauerhafte Fortschrittsspeicherung

Jede Fraktion besitzt für jede bereits begonnene Technologie einen dauerhaft gespeicherten Forschungsfortschritt.

Beispiel:

| Eigenschaft | Wert |
|---|---:|
| Technologie | Warpantrieb V |
| Forschungskosten | 10.000 FP |
| Bereits erforscht | 4.200 FP |
| Restlicher Bedarf | 5.800 FP |
| Status | Abgebrochen |

Wird die Forschung später erneut gestartet, beginnt sie bei 4.200 FP.

Es müssen lediglich die verbleibenden 5.800 FP erarbeitet werden.

## 7.3 Unterschied zwischen Pause und Abbruch

**Pausieren:** Das Projekt bleibt in der Forschungsliste, erhält aber keine weiteren Punkte.

**Abbrechen:** Das Projekt wird aus der aktiven Projektliste entfernt. Sein Fortschritt bleibt gespeichert und wird beim erneuten Start wiederhergestellt.

Beide Vorgänge verursachen keinen Forschungsfortschrittsverlust.

---

# 8. Dynamische Anpassungen

Die verfügbare Forschungsleistung wird regelmäßig neu berechnet.

Sie kann sich beispielsweise ändern, wenn:

- Ein neuer Forschungskomplex gebaut wird.
- Ein Forschungskomplex modernisiert wird.
- Zusätzliche Akademiker beschäftigt werden.
- Wissenschaftler auswandern.
- Die Bevölkerung unzufrieden wird.
- Ein Forschungskomplex wegen Energiemangels weniger leistet.
- Ein Gebäude zerstört oder deaktiviert wird.
- Eine Forschungstechnologie die Forschungsleistung verbessert.

Die auf aktive Projekte verteilten Punkte verändern sich automatisch.

Bereits erreichte Projektfortschritte bleiben unverändert.

---

# 9. Gemeinsamer Forschungsbaum

Alle Technologien gehören weiterhin zu einem einzigen zusammenhängenden Forschungsbaum.

Eine getrennte Verwaltung von Physik, Gesellschaft und Ingenieurswesen existiert nicht.

Die thematische Gruppierung dient ausschließlich der Übersicht.

Der bisher entworfene Forschungsbaum mit 136 Technologien bleibt als inhaltliche Grundlage erhalten.

## 9.1 Forschungsvoraussetzungen

Jede Technologie kann eine oder mehrere Vorgängertechnologien voraussetzen.

Ein Projekt wird erst verfügbar, wenn diese Voraussetzungen erfüllt sind.

## 9.2 Forschungskosten

Anstelle einer festen Forschungsdauer besitzt jede Technologie eine definierte Gesamtzahl an Forschungspunkten.

Die Forschungskosten steigen grundsätzlich mit der technologischen Komplexität.

Die konkreten Kosten aller 136 Technologien müssen entsprechend dem neuen Forschungsmodell festgelegt und ausbalanciert werden.

## 9.3 Technologiefreischaltungen

Der Abschluss einer Technologie kann unter anderem freischalten:

- Gebäudemodernisierungen.
- Neue Gebäude.
- Neue Produktionsrezepte.
- Höhere Warpstufen.
- Sprungtortechnologie.
- Fortschrittliche Raumschiffkomponenten.
- Verbesserte medizinische Versorgung.
- Terraforming.
- Neue Forschungsprojekte.

Das bestehende Freischaltungs- und Abhängigkeitssystem bleibt erhalten.

---

# 10. Gebäude-Upgrades

Verschiedene Gebäudetypen besitzen unterschiedlich viele Ausbaustufen.

Neue Stufen werden über den Forschungsbaum freigeschaltet.

Upgrades können insbesondere:

- Produktivität steigern.
- Wohnkomfort erhöhen.
- Produktionskapazitäten vergrößern.
- Arbeitskräftebedarf reduzieren.
- Energieeffizienz verbessern.
- Ausbildungskapazitäten erhöhen.
- Forschungsleistung je Wissenschaftler verbessern.

Ein Upgrade benötigt weiterhin materielle Ressourcen und Bauzeit.

Jedes Gebäude belegt unabhängig von seiner Ausbaustufe genau eine Kachel.

---

# 11. Benutzeroberfläche

## 11.1 Forschungsübersicht

Die Forschungsansicht zeigt:

- Gesamte Forschungspunkte pro Tick.
- Anzahl beschäftigter Wissenschaftler.
- Forschungskomplexe und ihre Ausbaustufen.
- Aktive Forschungsprojekte.
- Pausierte Forschungsprojekte.
- Bereits begonnene, aber abgebrochene Forschungen.
- Abgeschlossene Technologien.
- Aktuelle Projektfortschritte.
- Verbleibende Forschungspunkte.
- Voraussichtliche Restdauer.
- Zugewiesene Forschungsanteile.

## 11.2 Einzelnes Forschungsprojekt

Ein Forschungsprojekt zeigt:

**Beispiel: Warpantrieb V**

- Benötigt: 10.000 FP.
- Erforscht: 4.200 FP.
- Fortschritt: 42 %.
- Aktuelle Zuweisung: 100 FP/Tick.
- Voraussichtlich verbleibend: 58 Ticks.
- Zustand: Aktiv.

Die Restdauer wird laufend neu berechnet, da die Forschungsleistung veränderlich ist.

## 11.3 Bedienfunktionen

Der Spieler kann:

- Neue Forschungen starten.
- Mehrere Forschungen parallel starten.
- Forschungen pausieren.
- Forschungen fortsetzen.
- Forschungen abbrechen.
- Abgebrochene Forschungen erneut starten.
- Forschungsprioritäten festlegen.

Es erfolgt keine manuelle Zuordnung einzelner Wissenschaftler.

---

# 12. Technische Umsetzung

## 12.1 Forschungssystem

Der Simulationskern berechnet pro Forschungstick:

1. Alle beschäftigten Wissenschaftler erfassen.
2. Individuelle Forschungsleistung bestimmen.
3. Effektive Gesamtforschungsleistung berechnen.
4. Aktive Forschungsprojekte ermitteln.
5. Forschungspunkte gemäß Prioritäten verteilen.
6. Den gespeicherten Projektfortschritt erhöhen.
7. Abgeschlossene Forschungen erkennen.
8. Technologieeffekte und Freischaltungen aktivieren.
9. Verbleibende Forschungskapazität gegebenenfalls weiterverteilen.

## 12.2 Datenspeicherung

Für jede Fraktion werden gespeichert:

- Erforschte Technologien.
- Fortschritt jeder bereits begonnenen Technologie.
- Aktive Forschungsprojekte.
- Pausierte Projekte.
- Forschungsprioritäten.
- Forschungsgebäude und Beschäftigung.
- Aktueller Simulationszeitpunkt.

Der Forschungsfortschritt wird unabhängig vom Zustand der aktiven Projektliste gespeichert.

## 12.3 Datenmodell

Eine Technologie enthält beispielsweise:

- `technology_id`
- `research_cost`
- `prerequisite_ids`
- `unlocks`
- `technology_tier`

Der Forschungszustand einer Fraktion enthält:

- `technology_id`
- `accumulated_research`
- `status`
- `allocation_weight`

Mögliche Statuswerte:

- Nicht begonnen.
- Aktiv.
- Pausiert.
- Abgebrochen.
- Abgeschlossen.

## 12.4 Simulations-Ticks

Die Forschung wird unabhängig vom Rendering berechnet.

Als erster Vorschlag entspricht ein Forschungstick einem Spieltag.

Die tatsächliche Frequenz bleibt konfigurierbar.

Die Berechnung muss auch bei erhöhter Spielgeschwindigkeit korrekt funktionieren.

## 12.5 Numerische Genauigkeit

Für Forschungsfortschritte sollen ausreichend genaue numerische Werte verwendet werden.

Die Darstellung kann auf ganze Forschungspunkte gerundet werden.

Intern darf die Rundung jedoch nicht dazu führen, dass Forschungspunkte bei der Aufteilung auf mehrere Projekte verloren gehen oder mehrfach angerechnet werden.

---

# 13. Abnahmekriterien

1. Jeder tatsächlich forschende Wissenschaftler generiert Forschungspunkte pro Tick.
2. Akademiker außerhalb der Forschungskomplexe erzeugen keine Forschungspunkte.
3. Die gesamte Forschungsleistung wird fraktionsweit zusammengefasst.
4. Jede Technologie besitzt festgelegte Forschungskosten.
5. Der Forschungsfortschritt wird bei jedem Forschungstick erhöht.
6. Mehrere Forschungsprojekte können gleichzeitig aktiv sein.
7. Die Forschungspunkte werden auf aktive Projekte verteilt.
8. Die Summe der zugewiesenen Forschungspunkte überschreitet nicht die generierte Leistung.
9. Ein Forschungsprojekt kann pausiert werden.
10. Ein Forschungsprojekt kann abgebrochen werden.
11. Beim Pausieren oder Abbrechen geht kein Forschungsfortschritt verloren.
12. Beim Neustart wird der gespeicherte Fortschritt übernommen.
13. Forschungskomplex-Upgrades können die Forschungsleistung verbessern.
14. Arbeitsverfügbarkeit und Arbeitseffizienz beeinflussen die Forschungsleistung.
15. Fehlende Energie oder Betriebsmittel können die Forschungsleistung verringern.
16. Forschungsfortschritte bleiben nach Speichern und Laden erhalten.
17. Die Forschungsberechnung bleibt unabhängig von der grafischen Darstellung.
18. Spieler und KI verwenden dasselbe Forschungssystem.
19. Der gemeinsame Technologiebaum mit seinen Abhängigkeiten bleibt erhalten.
20. Gebäude-Upgrades werden weiterhin über Technologien freigeschaltet.

---

# 14. Verbindliche Änderungen gegenüber Version 1.1

**Ersetzt werden:**

- Feste Basisforschungsdauer pro Technologie.
- Zeitfortschritt ohne Forschungspunkte.
- Exklusive Bindung eines Forschungsprojekts an einen einzelnen Forschungskomplex.

**Neu verbindlich gelten:**

- Forschungspunkte pro Wissenschaftler und Tick.
- Gemeinsame fraktionsweite Forschungskapazität.
- Forschungskosten in Forschungspunkten pro Technologie.
- Verteilung der erzeugten Punkte auf parallele Projekte.
- Pausieren und Abbrechen ohne Fortschrittsverlust.
- Dauerhafte Speicherung bereits erforschter Teilfortschritte.
- Dynamische Forschungsdauer abhängig von der tatsächlichen Forschungsleistung.

**Unverändert bleiben:**

- Ein einziger, sehr weit verzweigter Forschungsbaum.
- Logische technologische Voraussetzungen.
- Forschungskomplexe als reguläre Gebäude.
- Schulen und Universitäten als reine Bildungseinrichtungen.
- Automatische Arbeitsplatzbesetzung.
- Forschungsgesteuerte Gebäude-Upgrades.
- Alle übrigen Systeme des Spielkonzepts.

**Konzeptstand: Version 1.2.**