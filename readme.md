# Project Sagittarius – Sternenreiche

**Projektstatus:** Konzept- und Planungsphase  
**Genre:** 4X-Weltraumstrategie / Grand Strategy  
**Zielplattformen:** Windows und Linux  
**Geplante Engine:** Unreal Engine 5  
**Geplante Technologien:** C++, Python und Blender

## Projektbeschreibung

Project Sagittarius ist ein eigenständiges Weltraumstrategiespiel, das eine auf realen astronomischen Daten basierende Milchstraße mit prozedural generierten Inhalten und einer umfangreichen Zivilisationssimulation verbindet.

Der Spieler übernimmt die Führung einer interstellaren Zivilisation und entwickelt diese durch Erkundung, Expansion, Wirtschaft, Wissenschaft, Diplomatie und militärische Entscheidungen.

Die Spielwelt und ihre Mechaniken werden modular, datengetrieben und langfristig erweiterbar entwickelt.

## Grundlegende Spielmechaniken

### Astronomie und Spielwelt

Die Galaxie wird dreidimensional dargestellt und verwendet reale Sternpositionen aus wissenschaftlichen Katalogen.

Fehlende astronomische Informationen können durch reproduzierbare prozedurale Generierung ergänzt werden.

Sternensysteme besitzen festgelegte Umlaufbahnen. Himmelskörper bewegen sich abhängig von der Spielzeit entlang dieser Bahnen. Eine Gravitationssimulation findet nicht statt.

### Planetenverwaltung

Die planetare Verwaltung erfolgt über ein zweidimensionales Kachelfenster.

Ein erdgroßer Planet besitzt 60 Verwaltungskacheln. Die Kachelanzahl anderer Planeten skaliert entsprechend ihrer Oberfläche.

Pro Kachel ist genau ein Gebäude erlaubt.

Planeten werden anhand eines an Star Trek orientierten Klassifikationssystems eingeteilt. Ihre Bewohnbarkeit hängt von den biologischen Eigenschaften der jeweiligen Spezies ab.

### Bevölkerung

Es existieren drei Bildungsstufen:

- Ungebildet
- Gebildet
- Akademiker

Schulen und Universitäten übernehmen die Ausbildung der Bevölkerung.

Die Zuordnung zu Arbeitsplätzen und Wohngebäuden erfolgt automatisch.

Wohnraum, Nahrungsversorgung und weitere Lebensbedingungen beeinflussen die Zufriedenheit und damit die effektive Arbeitsleistung.

Bei passenden Arbeitskräfteüberschüssen und -bedarfen können Bewohner automatisch zwischen Kolonien umziehen. Dafür müssen tatsächlich betriebene Transportschiffverbindungen existieren.

### Wirtschaft

Die Wirtschaft besitzt mehrstufige Produktionsketten und umfangreiche materielle Ressourcen.

Die Nahrungsmittelproduktion verwendet vier Ressourcen:

- RohNahrung
- Nahrung I
- Nahrung II
- Nahrung III

Farmen erzeugen RohNahrung. Die drei Nahrungsstufen werden in aufeinander aufbauenden Nahrungsmittelfabriken hergestellt.

Biomassekraftwerke können überschüssige RohNahrung zur Energieerzeugung verwenden.

Alle Gebäude verbrauchen Energie. Energieproduktion und Energieverbrauch werden global je Fraktion bilanziert.

### Forschung

Das Forschungssystem verwendet einen gemeinsamen, verzweigten Technologiebaum.

Forschungskomplexe beschäftigen Akademiker, die pro Simulationstick Forschungspunkte erzeugen.

Die Punkte werden auf aktive Forschungsprojekte verteilt. Mehrere Projekte können parallel laufen.

Forschungen können pausiert oder abgebrochen werden, ohne ihren bereits erreichten Fortschritt zu verlieren.

Schulen und Universitäten dienen ausschließlich der Ausbildung und erzeugen selbst keine Forschungspunkte.

Technologien schalten unter anderem Gebäude, Gebäudemodernisierungen, Produktionsverfahren und Raumfahrttechnik frei.

### Interstellare Raumfahrt

Raumschiffe verfügen über Warpantriebe mit neun Geschwindigkeitsstufen.

Normale Reisen erfolgen zwischen Sternensystemen und benötigen Spielzeit.

Zusätzlich können Fraktionen Sprungtore errichten. Die Reise zwischen zugänglichen Sprungtoren erfolgt ohne Zeitverlust.

Eigene sowie Sprungtore befreundeter und verbündeter Fraktionen können benutzt werden.

Das Navigationssystem berechnet kombinierte Routen aus Warpstrecken und Sprungtorverbindungen.

## Technische Grundsätze

Die eigentliche Spielsimulation wird von der grafischen Darstellung getrennt.

Astronomische Originaldaten bleiben unabhängig von prozedural generierten und durch das Spiel veränderlichen Informationen.

Wirtschaft, Bevölkerung, Forschung, Raumfahrt und KI verwenden gemeinsame, nachvollziehbare Simulationsregeln.

Die Entwicklung soll mit einer begrenzten, vollständig spielbaren Sternregion beginnen und anschließend schrittweise erweitert werden.

## Dokumentation

Die Datei [project.md](project.md) enthält derzeit das Forschungskonzept Version 1.2.

Weitere Konzeptdokumente, technische Architekturunterlagen, Entwicklungspläne und Implementierungspläne werden schrittweise ergänzt.

Jedes Dokument soll seinen Geltungsbereich und Konzeptstand eindeutig ausweisen.

## Entwicklungsprozess

Die Projektentwicklung erfolgt dokumentationsbasiert.

Neue Spielmechaniken werden zunächst konzeptionell definiert, mit bestehenden Systemen abgestimmt und anschließend in geeignete Entwicklungs- und Implementierungsschritte aufgeteilt.

Änderungen sollen bestehende verbindliche Designentscheidungen nicht unbeabsichtigt überschreiben.

Der jeweils aktuelle Stand der Dateien im GitHub-Repository dient als Grundlage für weitere Überarbeitungen.

## Aktueller Stand

Das Projekt befindet sich in der Konzeptphase.

Die bisher festgelegten Spielmechaniken werden schrittweise in eine strukturierte Projektdokumentation überführt.

Eine Implementierung des Spiels ist in diesem Repository derzeit noch nicht enthalten.