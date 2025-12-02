# Changelog
Alle relevanten Änderungen an diesem Projekt werden in diesem Dokument festgehalten.

Das Format orientiert sich an **Keep a Changelog**  
und nutzt **Semantic Versioning** (MAJOR.MINOR.PATCH).

## [v1.1.0] – 2025-02-xx
### Added
- **Neue MSP-Erkennung (Managed Service Provider)**  
  - Einführung der Frage zur Applikations-/Systembetriebsverantwortung  
  - NIS2-konforme Unterscheidung zwischen Hosting vs. MSP  
  - Erweiterte Klassifikationslogik für „wichtige Einrichtung – MSP“  
  - Neuer MSP-Hinweisblock in der Ergebnisanzeige  
  - MSP-spezifische Empfehlungen im Ergebnisbereich  

- **Neue Detailanzeige**  
  - Darstellung der MSP-Rolle in der Ergebnisübersicht  
  - Erweiterte Erklärungstexte für Dienstleister

### Changed
- Überarbeitete Einstufungslogik (`computeResult()`):  
  - MSP-Rollen werden nun korrekt als potenziell direkt betroffen bewertet  
  - Fälle ohne eigenes Hosting werden richtig erkannt (kein automatischer „indirekt“-Pfad mehr)
- Überarbeitete Fragen 3.2/3.3:  
  - 3.2 neu formuliert (Hosting & Infrastruktur)  
  - 3.3 neu hinzugefügt (Applikations-/Systembetrieb / MSP)
- Anpassungen an `showServiceQuestions()`  
  - `managedService` wird nun korrekt in den State übernommen
- Überarbeitete `showResult()`  
  - Integration des MSP-Hinweisblocks  
  - Erweiterung der Detail- und Empfehlungstexte

## [v1.0.0] – 2025-11-07  
### Added
- Erste vollständige Version der Web-App zur NIS2-Betroffenheitsprüfung  
- Schritt-für-Schritt-Abfragemodell für Sektor, Rolle, Kritikalität, Unternehmensgröße und Lieferkette  
- Grundlegende Klassifikationslogik für:
  - direkt betroffene Unternehmen  
  - indirekt betroffene Unternehmen  
  - nicht betroffene Unternehmen  
- Übersichtliche Ergebnisdarstellung inkl. Empfehlungen  
- Komplett client-side implementiert (keine Datenübertragung, kein Tracking)  
- Basis-Design, Layout und Benutzerführung  
- Downloadfunktion für Berichte

## Legende
- **Added** – Neue Features  
- **Changed** – Änderungen bestehender Funktionen  
- **Fixed** – Fehlerbehebungen  
- **Removed** – Entfernte Funktionen  
- **Security** – Sicherheitsrelevante Änderungen

