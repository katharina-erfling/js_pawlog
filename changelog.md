# Changelog

Alle wichtigen Änderungen an PawLog werden in dieser Datei dokumentiert.


## [0.5.0]

### Hinzugefügt
- Neuer Bereich „Auswertungen“
- Eigener Menüpunkt für Statistiken und Diagramme
- Auswahl des Auswertungszeitraums:
  - 30 Tage
  - 90 Tage
  - 1 Jahr
  - Gesamtzeitraum
- Auswertungen werden individuell für den ausgewählten Hund erstellt
- Gewichtsdiagramm für den gewählten Zeitraum
- Zielgewicht wird im Gewichtsdiagramm berücksichtigt
- Ausgangsgewicht wird in der Auswertung berücksichtigt
- Diagramm zur gelaufenen Gassistrecke
- Wochenweise Darstellung der Gassistrecke bei kurzen Zeiträumen
- Monatsweise Darstellung der Gassistrecke bei längeren Zeiträumen
- Diagramm zur Trainingszeit im Verlauf
- Diagramm zur Trainingszeit nach Trainingsart bzw. Hundesport
- Kalorienauswertung für das Ernährungstagebuch
- Diagramm der dokumentierten Kalorien im Zeitverlauf
- Durchschnittliche dokumentierte Kalorien pro Tag
- Kennzahl zur Anzahl der Trainingseinheiten
- Kennzahl zur gesamten Trainingszeit
- Kennzahl zur Anzahl der Spaziergänge
- Kennzahl zur gesamten Gassizeit
- Kennzahl zur zurückgelegten Gassistrecke
- Durchschnittliche Strecke pro Spaziergang
- Vergleich mit dem vorherigen Zeitraum
- Prozentuale Veränderungsanzeige gegenüber dem vorherigen Zeitraum

### Verbessert
- Gewicht, Ernährung, Training und Gassi können jetzt gemeinsam ausgewertet werden
- Kurze und lange Zeiträume verwenden automatisch eine passende Diagrammaggregation
- Diagramme passen sich responsiv an Desktop und mobile Geräte an
- Fehlende Daten werden mit verständlichen Hinweisen dargestellt
- Kalorienauswertungen berücksichtigen ausschließlich Futter mit hinterlegten kcal-Werten
- Bestehende PawLog-Daten werden automatisch um die neuen Auswertungseinstellungen ergänzt
- Gewichts-Auswertungen verwenden weiterhin die eindeutige Zuordnung zum jeweiligen Hund
- Bestehende lokale Speicherung und Backup-Struktur bleiben kompatibel

## [0.4.0]

### Hinzugefügt
- Neues Trainingsbuch
- Trainingseinträge pro Hund
- Erfassung von Datum und Uhrzeit einer Trainingseinheit
- Erfassung der Trainingsdauer
- Freie Angabe von Trainingsart oder Hundesport
- Schwerpunkt einer Trainingseinheit
- Dokumentation konkreter Übungen und Trainingsinhalte
- Dokumentation von Verlauf und Ergebnis
- Bewertung einer Trainingseinheit
- Freie Trainingsnotizen
- Monatsübersicht mit Anzahl der Trainingseinheiten
- Monatsübersicht mit gesamter Trainingszeit
- Anzeige der zuletzt dokumentierten Trainingseinheit
- Filterung des Trainingsbuchs nach Trainingsart
- Bearbeiten bestehender Trainingseinträge
- Löschen bestehender Trainingseinträge
- Neues Gassibuch
- Spaziergänge können für einen oder mehrere Hunde gleichzeitig eingetragen werden
- Erfassung von Datum und Startzeit
- Erfassung der Dauer eines Spaziergangs
- Optionale Erfassung der zurückgelegten Strecke
- Unterscheidung verschiedener Spaziergangsarten
- Angabe von Leine, Freilauf, Schleppleine oder gemischter Nutzung
- Angabe von Ort und Route
- Freie Notizen für Begegnungen, Verhalten und Besonderheiten
- Monatsübersicht mit Anzahl der Spaziergänge
- Monatsübersicht mit gesamter Gassizeit
- Monatsübersicht mit zurückgelegter Strecke
- Anzeige des letzten Spaziergangs
- Profilbilder der beteiligten Hunde direkt an gemeinsamen Spaziergängen
- Bearbeiten bestehender Spaziergänge
- Löschen bestehender Spaziergänge
- Schnellaktionen für Training und Spaziergänge auf dem Dashboard

### Verbessert
- PawLog bildet neben Ernährung, Gewicht und Gesundheit jetzt auch Bewegung und Training ab
- Gemeinsame Spaziergänge müssen nicht mehrfach für jeden Hund eingetragen werden
- Trainings- und Gassidaten werden automatisch dem jeweiligen Hundesteckbrief zugeordnet
- Bestehende PawLog-Daten werden automatisch um Trainings- und Gassidaten erweitert
- Trainings- und Gassidaten werden im normalen JSON-Backup mitgesichert
- Beim Löschen eines Hundes werden zugehörige Trainingseinträge entfernt
- Bei gemeinsamen Spaziergängen wird ein gelöschter Hund automatisch aus dem Spaziergang entfernt
- Spaziergänge bleiben erhalten, solange noch mindestens ein Hund zugeordnet ist

## [0.3.0]

### Hinzugefügt
- Neue zentrale Futter- und Zutatenverwaltung
- Verwaltung konkreter Futterprodukte mit:
  - Name
  - Hersteller oder Marke
  - Futterart
  - Kategorie
  - Standard-Einheit
  - kcal pro 100 g
  - Notizen
  - optionalem Produktfoto
- Unterscheidung zwischen BARF, Fertigfutter, Zusätzen, Snacks und sonstigem Futter
- Suche und Filterung in der Futterverwaltung
- Individuelle Portionsgrößen pro Hund für gespeicherte Gerichte
- Automatische Skalierung eines Gerichts auf die für den ausgewählten Hund hinterlegte Portionsgröße
- Anzeige der Gesamtmenge eines Gerichts
- Kalorienanzeige für Gerichte, sofern entsprechende Futterdaten hinterlegt sind
- Bearbeitung bestehender Futterlog-Einträge
- Funktion „Letzte Mahlzeit wiederholen“
- Funktion „Wie gestern“
- Wochenansicht für das Ernährungstagebuch
- Tagesübersicht mit Anzahl der Fütterungen
- Unterscheidung zwischen automatischer Grundfütterung und zusätzlichen Einträgen
- Tagesbezogene Kalorienauswertung
- Wochenübersicht mit Fütterungsanzahl und Kalorien pro Tag
- Neue Gesundheitsakte
- Verwaltung von Tierarztbesuchen
- Verwaltung von Impfungen
- Verwaltung von Medikamenten
- Verwaltung von Parasitenprophylaxe
- Verwaltung von Dokumenten und Befunden
- Bearbeitung bestehender Gesundheitseinträge
- Lokale Speicherung von Bildern und PDFs innerhalb von Dokumenteinträgen
- Öffnen hinterlegter Dokumente direkt aus PawLog
- Gesundheitsdaten werden in Backup und Import aufgenommen

### Verbessert
- Bestehende Zutaten werden automatisch in die neue Futterverwaltung übernommen
- Bestehende Gerichte werden automatisch auf die neue Datenstruktur migriert
- Bestehende Futterpläne werden automatisch auf die neue Futterstruktur migriert
- Bestehende Futtertagebuch-Einträge bleiben erhalten
- Bestehende Hundeprofile, Profilbilder und Gewichtsdaten bleiben erhalten
- Futterlog stärker als echtes Ernährungstagebuch aufgebaut
- Schnellaktionen für wiederkehrende Fütterungen ergänzt
- Gerichte können jetzt einfacher für mehrere Hunde mit unterschiedlichen Portionsgrößen verwendet werden
- Futterpläne bleiben weiterhin automatisch im Ernährungstagebuch sichtbar
- Kalorien werden nur ausgewertet, wenn entsprechende Nährwertdaten vorhanden sind
- Gesundheitsbereiche als eigene übersichtliche Tabs aufgebaut
- Responsive Darstellung der neuen Wochen-, Futter- und Gesundheitsansichten
- Bestehende lokale Speicherung und JSON-Backups bleiben kompatibel

### Technisch
- Datenmodell für Futter, Gerichte und Fütterungseinträge erweitert
- Datenmodell für Gesundheitsdaten ergänzt
- Automatische Migration älterer PawLog-Daten auf die neue Struktur
- Bestehender lokaler PawLog-Speicher wird weiterverwendet
- Syntax und Datenmigration der neuen Version geprüft

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
