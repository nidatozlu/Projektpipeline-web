# Interaktives Projekt-Pipeline Dashboard

Dieses Dashboard wurde entwickelt, um die manuelle und chaotische Projekt-Pipeline-Übersicht des Forschungsinstituts zu ersetzen. Es bietet eine zentrale, dynamische und benutzerfreundliche Oberfläche für die Erfassung, Analyse und Visualisierung aller Projekte.

### Kernfunktionen

* **Echtzeit-Kennzahlen (KPIs):** Bietet einen sofortigen Überblick über die Anzahl der Projekte, das Gesamtvolumen und die durchschnittliche Laufzeit.
* **Dynamische Filter:** Ermöglicht die Filterung von Daten nach Organisationseinheit (OE), Projektstatus und Suchbegriffen.
* **Status-Ansichten:** Ermöglicht die schnelle Anzeige von Projekten basierend auf ihrem Status (z. B. "Idee", "Laufend", "Genehmigt").
* **Interaktive Diagramme:** Visualisiert Projektverteilungen und Finanzprognosen, um Muster und Trends schnell zu erkennen.
* **Dateneingabe:** Bietet ein integriertes Formular zur schnellen und konsistenten Eingabe neuer Projekte.
* **AI-gestützte Beschreibung:** Nutzt die Gemini API zur automatischen Generierung professioneller Projektbeschreibungen.

### Verwendung

Da das Dashboard externe Bibliotheken und API-Aufrufe nutzt, wurde es als Single-Page Application (SPA) auf GitHub Pages gehostet.

Um das Dashboard zu verwenden, öffnen Sie einfach die folgende URL in Ihrem Browser:

https://<IhrBenutzername>.github.io/<IhrRepositoryname>/projekt-pipeline-dashboard.html

### Einbetten in Confluence oder SharePoint

Das Dashboard kann in jede Plattform, die das Einbetten von Inhalten über `iframes` unterstützt, nahtlos integriert werden.

Verwenden Sie das jeweilige `iframe`- oder "Embed"-Makro und fügen Sie die oben genannte URL ein. Stellen Sie die Breite auf `100%` und die Höhe auf `1200px` ein, um eine optimale Darstellung zu gewährleisten.

### Technologischer Stack

* **Frontend:** Reines HTML, CSS und JavaScript
* **Styling:** Tailwind CSS (über CDN)
* **Visualisierung:** Chart.js (über CDN)
* **AI-Integration:** Google Gemini API
