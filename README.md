# NIS2-Betroffenheitsprüfung (Web-App: nis2-quickcheck)

Eine browserbasierte Web-App zur **Erstbewertung**, ob ein Unternehmen unter die EU-NIS2-Richtlinie fällt.  
Die Anwendung führt Schritt für Schritt durch die relevanten Kriterien und liefert am Ende eine klare Einordnung inkl. Empfehlungen.

> **Hinweis:** Dieses Tool ist eine Orientierungshilfe und ersetzt keine rechtliche Beratung.

## 🎯 Zweck der Anwendung

Die EU-NIS2-Richtlinie erweitert den Kreis der verpflichteten Unternehmen deutlich – insbesondere in den Bereichen:

- Energie, Verkehr, Gesundheit, Wasser, digitale Dienste  
- Betreiber kritischer und wesentlicher Dienste  
- **Managed Service Provider (MSP)** und andere ICT-Dienstleister  
- Lieferkettenabhängigkeiten und Dienstleisterbeziehungen  

Diese Web-App ermöglicht eine **strukturierte Selbst­ein­schätzung**, ob ein Unternehmen:

- **direkt betroffen** (essentielle oder wichtige Einrichtung),  
- **als MSP direkt reguliert**,  
- **indirekt betroffen** (über Kunden / Lieferkette),  
- oder **vermutlich nicht betroffen**  

ist.

Die Entscheidung erfolgt anhand der NIS2-Kriterien, ergänzt durch spezifische Abfragen zu Hosting, Applikationsbetrieb, Lieferkette und Unternehmensgröße.

## 🚀 Funktionsumfang

- Schritt-für-Schritt-Abfrage der wichtigsten NIS2-Kriterien  
- **Erweiterte Logik für Managed Service Provider (MSP)**  
  – inkl. spezifischer Einstufung als wichtige Einrichtung  
  – inkl. eigenem Hinweisblock und Empfehlungen  
- Unterscheidung zwischen:
  - Betreiber / Essential Entities  
  - Wichtige Einrichtungen  
  - MSP / ICT Service Management  
  - Indirekt betroffene Unternehmen  
- Neue Trennung:
  - **eigene Infrastruktur / Hosting**  
  - **Applikations-/Systembetrieb für Kunden (MSP-Kriterium)**  
- Klare, verständliche Ergebnisdarstellung  
- Export-Option für Berichte (Browser-Download)  
- Vollständig client-side  
  – **kein Tracking, kein Server, keine Datenübertragung**

Ideal für:

- Unternehmen zur ersten Selbstbewertung  
- Beratungen, Compliance-Workshops, Awareness-Schulungen  
- Vorbereitung auf interne oder externe Audits

## 🧩 Hintergrund

Die EU-NIS2-Richtlinie verpflichtet betroffene Unternehmen zu umfangreichen Maßnahmen in den Bereichen:

- Informationssicherheits-Management  
- Risiko- und Krisenmanagement  
- Incident-Meldungen (24h/72h)  
- Governance und Verantwortlichkeiten  
- Lieferketten-Sicherheit  
- Technische und organisatorische Mindestanforderungen  

Diese Web-App wurde ursprünglich im Rahmen des folgenden Blogbeitrags entwickelt und seither erweitert:

🔗 https://www.cherware.de/reflect-it/831/

## 🛠️ Technologie

Diese App läuft vollständig im Browser:

- **HTML**  
- **CSS**  
- **JavaScript** (ohne Frameworks, 100 % client-side)

Keine Installation notwendig.

## 📄 Lizenz

Diese Software ist für Bildungszwecke oder erste Selbstbewertungen vorgesehen. Rechtliche Entscheidungen sollten stets durch professionelle Beratung abgesichert werden!

