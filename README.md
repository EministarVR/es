# 🚀 Es++ Cyber Editor

![Es++ Screenshot](logo.png) <!-- Hier Screenshot einfügen -->

**Eine deutsche Programmiersprache für Einsteiger**  
*Futuristischer Online-Editor mit Live-Interpreter*

![Version](https://img.shields.io/badge/version-1.0.0-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Stars](https://img.shields.io/github/stars/eministarvr/espp-editor?style=social)

## 🌟 Hauptmerkmale

- **🇩🇪 Deutsche Schlüsselwörter** statt englischer Begriffe
- **⚡ Live-Code-Interpreter** mit Echtzeit-Ausgabe
- **💻 Cyberpunk-Design** mit Neon-Effekten
- **📚 Integrierte Code-Beispiele**
- **🔍 Auto-Vervollständigung** für Es++-Syntax
- ❗ **Fehlerhighlighting** mit verständlichen Fehlermeldungen

## 🛠️ Installation

### 1. Repository klonen:
```
git clone https://github.com/dein-benutzername/espp-editor.git
```
### 2. In das Projektverzeichnis wechseln:
```
cd espp-editor
```
### 3. Editor starten:

Öffne die `index.html` im Browser oder starte sie lokal:
```
start index.html
```
> **Keine Server oder Installationen erforderlich!**

## 🕹️ Benutzung

- Code im Editor schreiben (Beispielcode vorhanden)
- Auf »Code starten« klicken
- Ausgabe im Terminal unten sehen

### Grundlegende Befehle:
```
// Variablen  
zahl = 10  
text = "Hallo Welt!"  
```
```
// Ausgabe  
ausgabe("Ergebnis: " + zahl)  
```
```
// Eingabe  
name = eingabe("Wie heißt du? ")  
```
```
// Schleife  
für i in reichweite(5):  
    ausgabe("Durchlauf: " + i)  
```
```
// Bedingung  
wenn zahl > 10:  
    ausgabe("Groß!")  
ansonsten:  
    ausgabe("Klein!")
```
---

## 🧰 Technische Umsetzung

- **Frontend**: HTML5, CSS3, JavaScript
- **Editor**: [Ace Editor](https://ace.c9.io/)
- **Syntax-Übersetzung**: Es++ → JavaScript
- **Design**: CSS-Animationen & Neon-Effekte

## 🧩 Beispielcode
```
// Zahlenraten-Spiel  
geheimzahl = 7  
eingabe = zahl(eingabe("Rate eine Zahl: "))  

wenn eingabe == geheimzahl:  
    ausgabe("Gewonnen! 🎉")  
ansonsten:  
    ausgabe("Falsch! ❌")  
```
```
// Rechenoperationen  
a = 10  
b = 5  
summe = a + b  
ausgabe("10 + 5 = " + summe)
```
---

## ❗ Fehlerbehandlung

- Rote Unterstreichung bei Syntaxfehlern
- Klare Fehlermeldungen auf Deutsch
- Automatische Zeilenmarkierung für schnelle Fehlerbehebung

## 🤝 Beitragen

- **Issue erstellen** für Bugs oder Feature-Anfragen
- **Repository forken** und Verbesserungen vornehmen
- **Pull Request stellen** – Alle Beiträge willkommen!

---

## 📜 Lizenz

MIT-Lizenz - Details [hier](LICENSE)

🛸 Viel Spaß beim Programmieren auf Deutsch!  
Ein Projekt von [EministarVR](https://github.com/EministarVR)
