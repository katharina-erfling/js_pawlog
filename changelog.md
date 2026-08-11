# Changelog

Alle wichtigen Änderungen an PawLog werden in dieser Datei dokumentiert.

## [0.1.6]

### Verbessert
- Geöffnete Dialoge können jetzt mit der Escape-Taste geschlossen werden
- Tastaturbedienung der Dialoge verbessert
- Escape reagiert nur, wenn tatsächlich ein Dialog geöffnet ist


## [0.1.5]

### Verbessert
- Einheitlicher fester Fallback-Avatar für Hunde ohne Profilfoto
- Auswahl eines eigenen Fallback-Emojis aus dem Hundesteckbrief entfernt
- Profil- und Bearbeitungsdialoge schließen sich nur noch über eine bewusste Aktion
- Klickverhalten innerhalb von Hundekarten und Profilaktionen robuster gemacht

### Behoben
- Steckbrief bzw. Bearbeitungsdialog konnte sich durch einen unbeabsichtigten Klick auf den Hintergrund schließen
- Verschachtelte Klickaktionen konnten teilweise mehrere Aktionen gleichzeitig auslösen

## [0.1.4]

### Hinzugefügt
- Profilfoto kann im Fotoeditor direkt mit Maus oder Finger verschoben werden
- Live-Anzeige der horizontalen und vertikalen Bildposition in Prozent
- Visueller Hinweis zum Verschieben des Bildausschnitts

### Verbessert
- Regler für den horizontalen und vertikalen Fotoausschnitt aktualisieren die Vorschau jetzt direkt
- Fotoausschnitt wird während der Bearbeitung ohne Neuladen der Vorschau angepasst
- Gespeicherte Bildposition wird zuverlässig auf alle Profilbilddarstellungen übernommen
- Bedienung des Fotoausschnitts auf Touch-Geräten verbessert

### Behoben
- Fotoausschnitt ließ sich trotz vorhandener Regler nicht zuverlässig sichtbar verschieben

## [0.1.3]

### Hinzugefügt
- Ausgangsgewicht pro Hund
- Startdatum für die Gewichtsverfolgung
- Ausgangsgewicht und Startdatum im Hundesteckbrief
- Neue Gewichtsübersicht mit Ausgangsgewicht, aktuellem Gewicht und Zielgewicht
- Anzeige der Gewichtsveränderung seit Beginn der Aufzeichnung
- Ausgangsgewicht wird im Gewichtsdiagramm als Startpunkt berücksichtigt

### Verbessert
- Gewichtsverfolgung unterscheidet jetzt eindeutig zwischen Ausgangsgewicht, aktuellem Gewicht und Zielgewicht
- Gewichtsveränderung wird nicht mehr nur anhand der ersten vorhandenen Messung berechnet, sondern anhand des festgelegten Ausgangsgewichts
- Bestehende Hundeprofile werden automatisch um die neuen Gewichtsfelder ergänzt


## [0.1.2]

### Hinzugefügt
- Neues Ernährungstagebuch mit dem kurzen Navigationsnamen „Futterlog“
- Tagebuchartige Tagesansicht mit großem Datumsbereich
- Navigation zum vorherigen und nächsten Tag
- Schnellnavigation zurück zum heutigen Tag
- Manuelle Auswahl eines beliebigen Tagebuchdatums
- Tageszusammenfassung für automatische und manuelle Fütterungseinträge
- Chronologische Timeline für die Fütterungen eines Tages
- Eigene Tagesnotiz pro Hund und Datum
- Richtige Hundesteckbriefe
- Große Profilbilddarstellung im Hundesteckbrief
- Direkt sichtbare Aktion zum Hinzufügen oder Ändern des Profilfotos
- Geschlecht im Hundesteckbrief
- Fellfarbe im Hundesteckbrief
- Chipnummer im Hundesteckbrief
- Persönliche Notizen im Hundesteckbrief
- Übersicht von aktuellem Gewicht, Zielgewicht und Grundfütterung im Steckbrief
- Direkter Zugriff von den Hundekarten auf den jeweiligen Steckbrief

### Verbessert
- Profilbilder werden konsequent an allen passenden Stellen der Oberfläche verwendet
- Hundeübersicht stärker als Einstieg in die einzelnen Hundeakten aufgebaut
- Futtertagebuch deutlich übersichtlicher und persönlicher gestaltet
- Automatische Grundfütterung und manuelle Einträge im Futterlog optisch unterscheidbar
- Ein neuer Fütterungseintrag aus dem Futterlog übernimmt automatisch das aktuell angezeigte Tagebuchdatum
- Hundeprofile um zusätzliche Steckbriefdaten erweitert
- Bestehende Daten werden beim Laden automatisch an die erweiterte Datenstruktur angepasst

### Behoben
- Falsche Zuordnung von Gewichtsmessungen zu einem anderen Hund
- Hundewahl in Gewichtseinträgen verwendet jetzt zuverlässig den im Eingabefenster ausgewählten Hund
- Hundewahl in Fütterungseinträgen verwendet jetzt zuverlässig den im Eingabefenster ausgewählten Hund
- Hundewahl in Futterplänen verwendet jetzt zuverlässig den im Eingabefenster ausgewählten Hund
- Alter Demo-Gewichtseintrag wird aus bestehenden PawLog-Daten entfernt

## [0.1.1]

### Hinzugefügt
- Profilfoto-Upload direkt in der Hundeprofil-Bearbeitung
- Unterstützung für JPG, PNG und WebP
- Automatische Verkleinerung und Komprimierung hochgeladener Profilbilder
- Einstellbarer horizontaler und vertikaler Bildausschnitt pro Hund
- Profilbilder auf dem Dashboard
- Profilbilder in den Hundeprofilen und Futterplänen
- Profilbilder im Tagebuch
- Profilbilder im Gewichtsverlauf
- Emoji-Fallback für Hunde ohne hinterlegtes Profilbild
- Profilbilder werden im JSON-Backup mitgesichert und beim Import wiederhergestellt

### Verbessert
- Hundebezogene Ansichten zeigen den aktuell ausgewählten Hund deutlicher
- Profilbilder werden abhängig von der jeweiligen Ansicht passend skaliert
- Verbesserte Bildzuschnitte für unterschiedliche Fotoformate
- Responsive Darstellung der Profilbilder auf kleineren Bildschirmen
- Foto-Editor optisch in die bestehende PawLog-Oberfläche integriert

## [0.1.0]

### Hinzugefügt
- Erste lauffähige Version von PawLog
- Verwaltung mehrerer Hunde mit individuellen Profilen
- Individuelle Profilfarben für jeden Hund
- Zielgewicht pro Hund
- Dashboard mit Tagesübersicht und Schnellaktionen
- Dauerhafte Grundfütterungspläne mit Gültig-ab-Datum
- Automatische Anzeige der Grundfütterung im Tagesprotokoll
- Manuelle Fütterungseinträge für zusätzliche Mahlzeiten und Abweichungen
- Zutatenbibliothek für BARF, Fleisch, Innereien, Knochen, Gemüse, Obst, Öle, Supplemente, Trockenfutter, Nassfutter, Kauartikel und Leckerlis
- Wiederverwendbare Gerichte und Rezeptvorlagen
- Übernahme gespeicherter Gerichte in das Futtertagebuch
- Individuelle Anpassung übernommener Gerichte ohne Veränderung der ursprünglichen Vorlage
- Gewichtstagebuch mit grafischem Gewichtsverlauf
- Anzeige von aktuellem Gewicht und Zielgewicht
- Lokale Speicherung direkt im Browser
- JSON-Backup und Wiederherstellung per Import
- Responsive Oberfläche für Desktop, Tablet und Smartphone

### Design
- Moderne und freundliche Pastell-Oberfläche
- Kartenbasierte Benutzeroberfläche
- Abgerundete UI-Elemente
- Einheitliche Icons
- Individuelle Akzentfarben für Hundeprofile
- Mobile Navigation
