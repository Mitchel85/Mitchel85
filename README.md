# Enterprise Architekturmanagement & ADMBw
[![CI](https://github.com/Mitchel85/EAM-Suite/actions/workflows/ci.yml/badge.svg)](https://github.com/Mitchel85/EAM-Suite/actions/workflows/ci.yml)
<p align="center">
  <a href="https://raw.githubusercontent.com/Mitchel85/Mitchel85/main/assets/toolfamilie-uebersicht.png" title="Übersichtsbild in voller Auflösung öffnen">
    <img src="assets/toolfamilie-uebersicht.png" alt="Übersicht der EAM-Toolfamilie in drei Gruppen: Basis (1 EAM-ADMBw-MDG-Parser, 2 EAM-QEA-Analyzer), KI-Werkzeuge (3 EAM-AI-QEA-Analyzer, 4 EAM-AI-ADMBw-Extractor, 5 EAM-AI-ADMBw-Batch, 6 EAM-AI-ADMBw-Script-Maker) und Suiten (7 EAM Suite, 8 EAM AI Suite, 9 EAM AI Suite Python; die beiden KI-Suiten nur auf Anfrage)." width="900">
  </a>
</p>

Neun Werkzeuge, eine Regelbasis: von der MDG-Auswertung über die KI-Extraktion bis zu den beiden Suiten für Prosa, Modelle und Automatisierung.

| Tool | Was es kann | Online ausprobieren | GitHub |
|---|---|---|---|
| <br>**Basis** – Regelbasis und Analyse | | | |
| 1 · 🔧 **EAM-ADMBw-MDG-Parser** | Extrahiert die Regeln aus der offiziellen ADMBw-MDG — hält die Wissensbasis aller KI-Tools bei jedem Update aktuell | [mitchel85.github.io/EAM-ADMBw-MDG-Parser](https://mitchel85.github.io/EAM-ADMBw-MDG-Parser/) | [Repository](https://github.com/Mitchel85/EAM-ADMBw-MDG-Parser) |
| 2 · 📊 **EAM-QEA-Analyzer** | Analyse von `.qea`-Dateien (Enterprise Architect) im Browser: Explorer, ADMBw/NAFv4-Farb-Graph, Pfadanalyse, PNG-/Excel-Export | [mitchel85.github.io/EAM-QEA-Analyzer](https://mitchel85.github.io/EAM-QEA-Analyzer/) | [Repository](https://github.com/Mitchel85/EAM-QEA-Analyzer) |
| <br>**KI-Werkzeuge** – sprachmodellgestützte Auswertung | | | |
| 3 · 💬 **EAM-AI-QEA-Analyzer** | Architekturmodelle per natürlicher Sprache befragen — lokal, in Open-WebUI oder per MCP; als Skill nutzbar | — | [Repository](https://github.com/Mitchel85/EAM-AI-QEA-Analyzer) |
| 4 · 📝 **EAM-AI-ADMBw-Extractor** | Extrahiert Stereotype, Beziehungen und Viewpoints aus Architektur-Prosa — konform zu ADMBw/NAFv4 (MDG 2026.05); als Skill nutzbar | — | [Repository](https://github.com/Mitchel85/EAM-AI-ADMBw-Extractor) |
| 5 · 📦 **EAM-AI-ADMBw-Batch** | Prosa → ADMBw-konforme JSON-Batches (Knoten & Kanten) für ArAMIS WEB / Neo4j; als Skill nutzbar | — | [Repository](https://github.com/Mitchel85/EAM-AI-ADMBw-Batch) |
| 6 · ⚙️ **EAM-AI-ADMBw-Script-Maker** | Generiert und verifiziert EA-JavaScript-Skripte für das Bundeswehr-Profil — idempotent, mit Re-Read-Prüfung; als Hermes-Skill nutzbar | — | [Repository](https://github.com/Mitchel85/EAM-AI-ADMBw-Script-Maker) |
| <br>**Suiten** – die Gesamtpakete | | | |
| 7 · 🗂️ **EAM Suite** | QEA-Architekturen im Browser bearbeiten und mehrere Modelle zu einer Landkarte verschmelzen — ohne KI, ohne Installation | [mitchel85.github.io/EAM-Suite](https://mitchel85.github.io/EAM-Suite/) | [Repository](https://github.com/Mitchel85/EAM-Suite) |
| 8 · 🤖 **EAM AI Suite** | Eine HTML-Datei: Prosa und MDG werden zum geprüften Modell — bearbeiten, prüfen, visualisieren direkt im Browser | ⚠️ **nur auf Anfrage** | ⚠️ **nur auf Anfrage** |
| 9 · 🐍 **EAM AI Suite Python** | Kommandozeile und Webdienst für Serien und Automatisierung: MDG, Startpaket, Reparatur, Viewer und Prosa-Rückweg | ⚠️ **nur auf Anfrage** | ⚠️ **nur auf Anfrage** |

<sub>Enterprise Architect und Sparx Systems sind Marken oder eingetragene Marken der Sparx Systems Pty Ltd. Alle genannten Werkzeuge sind unabhängige Drittanbieter-Produkte und stehen in keiner Verbindung zu Sparx Systems. Stand: Oktober 2026.</sub>

---

Interesse an **EAM AI Suite** oder **EAM AI Suite Python**? Beide Suiten sind nicht öffentlich — einfach melden.
