# 📦 Pfanderfassung – Pfandzählung V3

Eine einfache Web-Anwendung zur Erfassung und Zählung von Pfandartikeln.

## 📝 Beschreibung

Diese Webanwendung wurde speziell für das FC2 entwickelt, um die tägliche Erfassung des Pfandbestandes zu erleichtern. V3 verbindet das Design der Pfandzählung V2 mit einer Liste aller Artikel untereinander, jeweils mit Bild von Kasten und Flasche und der Anzahl Flaschen pro Kasten.

Die bisherige **Pfandzählung V2** liegt unverändert auf dem Branch `main`.

Die Anwendung wurde von **Nando** mit Unterstützung von Claude (AI-Assistent) erstellt und ist ausschließlich für den internen Gebrauch im FC2 bestimmt.

## ✨ Features

- 📱 **Fürs Handy gebaut** – alle Artikel untereinander, Getränke in der Reihenfolge des Sortier-Ordners
- 👆 **Antippen = +1**
- ✏️ **E** – Wert direkt bearbeiten, **+** – Menge hinzufügen, **−** – um 1 verringern
- 🖼️ **Bilder** – Kasten und Flasche je Artikel, mit Hinweis zur Flaschenzahl (z. B. „24 Flaschen“)
- 📋 **COPY** – Text wie in V2 („Pfandzählung vom: Datum“, alle Artikel, nicht Gezähltes mit 0)
- 💾 **Automatisches Speichern** – die Zählung bleibt beim Schließen und erneuten Öffnen erhalten
- ⏰ **Auto-Löschung** – nach 6 Stunden ohne Änderung wird die Zählung verworfen
- 🔄 **Alle zurücksetzen** – mit Bestätigung
- ⬆️ **Nach-oben-Knopf** unten rechts

## 🔒 Datenschutz & Speicherung

**Wichtig:** Die Zählung erfolgt **lokal auf dem Endgerät** und wird **nicht auf einem Server gespeichert**. Es werden keine Logs erstellt oder Daten übertragen.

- Alle Eingaben werden automatisch im Browser-Speicher (localStorage) gespeichert
- Daten älter als **6 Stunden** (seit der letzten Änderung) werden beim nächsten Öffnen automatisch gelöscht
- Manuelle Löschung jederzeit über „Alle zurücksetzen“

## 🚀 Verwendung

1. Öffne die `index.html` in einem modernen Webbrowser (der Ordner `img/` muss daneben liegen)
2. Tippe auf einen Artikel, um die Anzahl um 1 zu erhöhen
3. Rechts: **E** – Wert direkt eingeben, **+** – Menge hinzufügen, **−** – um 1 verringern
4. Tippe unten auf **COPY**, um die Zählung in die Zwischenablage zu kopieren
5. Mit „Alle zurücksetzen“ beginnst du eine neue Zählung

## 📦 Installation

Keine Installation erforderlich! Einfach `index.html` und den Ordner `img/` 1:1 kopieren und die `index.html` im Browser öffnen.

## 🖼️ Bildrechte

- `img/p-*.png` – Produktbilder (Kasten und Flasche), aus dem Internet zusammengestellt
- übrige Dateien in `img/` – Bilder der Pfandzählung V2 und ein Foto aus dem Sortier-Ordner

**Hinweis:** Es besteht **kein Recht an den Produktbildern**. Die Bilder dienen ausschließlich der internen Verwendung zur besseren Identifikation der Pfandartikel.

## 🛠️ Technologie

- HTML, CSS und Vanilla JavaScript in einer einzigen Datei
- Schriften Barlow und Barlow Condensed (Google Fonts); ohne Internet wird eine Systemschrift verwendet

## 👤 Autor

Erstellt von **Nando** für das FC2

## ⚠️ Haftungsausschluss

Diese Anwendung wurde speziell für den internen Gebrauch im FC2 entwickelt. Die Nutzung erfolgt auf eigene Verantwortung.
