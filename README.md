# Pflichtenheft – Webauftritt „Clinique Dentaire du Maroc“
**Projekt:** Neuentwicklung der Website für die Clinique Dentaire du Maroc  
**Status:** Finale Version (Umsetzung abgeschlossen)

---

## 1. Einleitung & Projektziel

### 1.1 Ausgangslage
Die „Clinique Dentaire du Maroc“ hatte bisher keinen professionellen Webauftritt, der den hohen medizinischen Standards und dem modernen Charakter der Klinik gerecht wurde.  
Informationen zu den wichtigsten Behandlungen, der Praxisausstattung und dem Team waren nicht zentral einsehbar, und Patienten konnten sich nicht online über Angebote, Öffnungszeiten oder Terminmöglichkeiten informieren.  
Die Klinik benötigte deshalb einen strukturierten Online-Auftritt, der zuverlässig, verständlich und optisch ansprechend ist.

### 1.2 Zielsetzung
Ziel des Projekts war:  
• eine moderne, klare und benutzerfreundliche Website zu entwickeln,  
• alle wichtigen Inhalte in Französisch und Englisch verfügbar zu machen,  
• das Leistungsspektrum visuell ansprechend darzustellen,  
• Vertrauen durch hochwertige Fotos und klare Struktur aufzubauen,  
• ein einfaches System zur digitalen Kontaktaufnahme bereitzustellen.  

Dieses Pflichtenheft dokumentiert, wie die Anforderungen aus dem Lastenheft in der finalen Website umgesetzt wurden.

---

## 2. Struktur und Umfang der Website (Sitemap)

Die Website wurde mit einer logischen, leicht verständlichen Struktur konzipiert.  
Unterseiten wurden bewusst reduziert und Inhalte sinnvoll zusammengeführt, damit Besucher schnell das finden, was sie suchen.

Folgende Seiten wurden umgesetzt:

### 1. Startseite (Home)
**Inhalt:**  
• großflächiges Titelbild („Hero Section“),  
• klare Begrüßung in beiden Sprachen,  
• kurze Vorstellung der Klinik,  
• direkte Weiterleitung zur Terminbuchung,  
• eingebundene Fotos der Behandlungsräume.  

**Ziel:** Sofort Vertrauen schaffen und einen professionellen ersten Eindruck vermitteln.

### 2. Unsere Geschichte (Story)
**Inhalt:**  
• Werte, Vision und Philosophie der Klinik,  
• Beschreibung des Qualitätsanspruchs,  
• Hinweise auf patientenorientierte Betreuung.  

**Ziel:** Die Klinik als verlässlichen und kompetenten Partner positionieren, der auf langfristige Patientenzufriedenheit setzt.

### 3. Dienstleistungen (Services)
**Inhalt:**  
• übersichtliche Darstellung der Hauptleistungen in Form von Kacheln,  
• kurze Beschreibungen der wichtigsten Behandlungsgruppen,  
• Hervorhebung moderner Behandlungsmethoden,  
• Einbindung von Technologie- und Laborinformationen in die passenden Bereiche.  

**Ziel:** Besuchern schnelle Orientierung geben und Fachbereiche verständlich erklären.

### 4. Das Team (Team)
**Inhalt:**  
• Fotos und Kurzprofile des medizinischen Teams,  
• Spezialisierungen und Rollen,  
• freundliche, persönliche Darstellung.  

**Hinweis:** Die im Dokument verwendeten Namen dienen derzeit als Platzhalter und werden bei Projektabschluss durch echte Teamdaten ersetzt.

### 5. Kontakt
**Inhalt:**  
• vollständige Kontaktdaten (Adresse, Telefon, E-Mail),  
• Öffnungszeiten der Klinik,  
• Standortanzeige,  
• Kontaktformular für allgemeine Anfragen.  

**Ziel:** Eine möglichst einfache Kommunikationsmöglichkeit für Patienten sicherstellen.

### 6. Terminbuchung (Appointment)
**Inhalt:**  
• eigenes Formular für Terminanfragen,  
• Auswahl des Besuchsgrundes,  
• Eingabe eines Datumswunsches,  
• Kontaktmöglichkeiten (Name, E-Mail, Telefon),  
• optionales Kommentarfeld.  

**Ziel:** Patienten ermöglichen, unkompliziert Terminwünsche einzureichen.

---

## 3. Funktionale Umsetzung

### 3.1 Mehrsprachigkeit (Internationalisierung)
Die Website ist vollständig zweisprachig (Französisch & Englisch).

**Umsetzung:**  
• Sprachumschalter im Hauptmenü,  
• direkte Umschaltung aller sichtbaren Texte ohne Neuladen,  
• Speicherung der Sprache im Browser (localStorage),  
• Nutzer erhalten beim erneuten Besuch automatisch ihre bevorzugte Sprache.

Diese Funktion verbessert Benutzerfreundlichkeit und Zielgruppenreichweite erheblich.

### 3.2 Interaktive Formulare
Es wurden zwei separate Formularbereiche realisiert:

**Kontaktformular**  
• Felder: Name, E-Mail-Adresse, Nachricht  
• einfache HTML5-Validierung (Pflichtfelder)

**Terminformat**  
• Felder: Name, E-Mail, Telefon, Behandlungsgrund, Datum, Kommentar  
• HTML5-Validierung zur Sicherstellung vollständiger Eingaben

**Backend-Status:**  
Die Formulare sind funktional im Frontend integriert.  
Eine technische Anbindung an ein E-Mail-System ist geplant und kann in einer späteren Projektphase umgesetzt werden.

### 3.3 Navigation & Benutzerführung
• Mobile-First-Navigation für optimale Nutzung auf Smartphones  
• ausklappbares Burger-Menü auf kleineren Geräten  
• Sticky Header, damit wichtige Menüpunkte immer erreichbar sind  
• klare, leicht verständliche Menüstruktur  
• große Call-to-Action-Buttons für Terminbuchungen  

Die Struktur berücksichtigt schnelle Orientierung und Hindernisfreiheit für Nutzer.

---

## 4. Design & Benutzeroberfläche (UI/UX)

### 4.1 Farbkonzept
• Primary Blue (#003266): kompetent, seriös, medizinischer Charakter  
• Weiß: Sauberkeit, Hygiene, Modernität  
• Grautöne: ruhige Leseästhetik, Ausgewogenheit

### 4.2 Typografie
• Montserrat: starke, klare Überschriften  
• Roboto: angenehm lesbarer, moderner Textfluss

### 4.3 Bildsprache
• helle, professionelle Praxisbilder  
• freundliche visuelle Atmosphäre  
• Darstellung echter Arbeitsbereiche, falls vom Kunden geliefert  

Die UI vermittelt den hohen Qualitätsstandard der Klinik zuverlässig nach außen.

---

## 5. Technische Umsetzung

### 5.1 Technologie-Stack
• HTML5 für klare, suchmaschinenfreundliche Struktur  
• Tailwind CSS für sauberes und einheitliches Design  
• JavaScript (Vanilla) für Sprachumschaltung und Navigation  
• CDN-Ressourcen, um schnelle Ladezeiten zu gewährleisten

### 5.2 Responsive Design & Performance
• optimiert für Mobilgeräte, Tablets und Desktop  
• reduzierte Ladezeiten durch Verzicht auf große Skripte  
• erfüllt die Ladezeit-Anforderung des Lastenhefts („unter 3 Sekunden“) problemlos

### 5.3 Dark Mode
• systembasierter Dark Mode durch Tailwind-Klassen unterstützt  
• manueller Schalter optional als Erweiterung vorgesehen

---

## 6. Qualitätssicherung & Abnahme

Die Umsetzung wurde anhand der im Lastenheft definierten Kriterien überprüft:

• vollständige Seitenstruktur erstellt  
• modernes, ruhiges Erscheinungsbild  
• zweisprachige Umsetzung  
• klare Navigation und Benutzerführung  
• Formulare funktionsfähig im Frontend  
• mobile Darstellung korrekt  
• alle gelieferten Inhalte wurden integriert  

Die Anforderungen gelten damit als erfüllt.

---

## 7. Ausblick & Wartung

Empfohlene Schritte für die Weiterentwicklung:

1. Backend-E-Mail-Versand für beide Formulare  
2. Pflege & Aktualisierung der Texte durch die Klinik  
3. SEO-Optimierung, insbesondere für lokale Suchanfragen  
4. mögliche Erweiterung der Website (z. B. Labor/Technologie, Galerie)  

Der Webauftritt ist stabil, skalierbar und gut pflegbar konzipiert.
