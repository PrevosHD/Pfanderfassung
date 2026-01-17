# 📦 Pfanderfassung

Eine einfache Web-Anwendung zur Erfassung und Zählung von Pfandartikeln.

## 📝 Beschreibung

Diese Webanwendung wurde speziell für das FC2 entwickelt, um die tägliche Erfassung des Pfandbestandes zu erleichtern. Jeden Abend müssen alle Pfandartikel wie Bierpaletten, Pfandsäcke und weitere Pfandartikel gezählt werden - diese App macht diesen Prozess deutlich einfacher und übersichtlicher.

Die Anwendung wurde von **Nando** mit Unterstützung von Claude (AI-Assistent) erstellt und ist ausschließlich für den internen Gebrauch im FC2 bestimmt.

## ✨ Features

- 📱 **Mobile-First Design** - Optimiert für Smartphones und Tablets
- 🎯 **Einfache Bedienung** - Schnelles Zählen durch Antippen der Artikel
- ➕ **Flexible Eingabe** - Einzelne Artikel hinzufügen oder Mengen direkt eingeben
- 💾 **Automatisches Speichern** - Alle Zählungen werden lokal im Browser gespeichert
- ⏰ **Auto-Löschung** - Daten älter als 6 Stunden werden automatisch gelöscht
- 📋 **Zusammenfassung** - Übersichtliche Darstellung aller gezählten Artikel
- 📄 **Copy-Funktion** - Ergebnisse mit einem Klick in die Zwischenablage kopieren
- 🔄 **Reset-Funktion** - Alle Werte zurücksetzen für eine neue Zählung
- 🚫 **Pull-to-Refresh deaktiviert** - Verhindert versehentliches Neuladen auf mobilen Geräten

## 🔒 Datenschutz & Speicherung

**Wichtig:** Die Zählung erfolgt **lokal auf dem Endgerät** und wird **nicht auf einem Server gespeichert**. Es werden keine Logs erstellt oder Daten übertragen. Alle Zählungen bleiben ausschließlich auf dem verwendeten Gerät.

**Automatische Speicherung:**
- Alle Eingaben werden automatisch im Browser-Speicher (localStorage) gespeichert
- Daten bleiben auch nach Neuladen der Seite erhalten
- Daten älter als **6 Stunden** werden beim nächsten Öffnen automatisch gelöscht
- Manuelle Löschung jederzeit über "Alle zurücksetzen" möglich

## 🚀 Verwendung

1. Öffne die `index.html` Datei in einem modernen Webbrowser
2. Tippe auf einen Artikel, um die Anzahl zu erhöhen
3. Nutze die Buttons für weitere Optionen:
   - **E** - Wert direkt bearbeiten
   - **+** - Bestimmte Menge hinzufügen
   - **-** - Wert um 1 verringern
4. Die Zusammenfassung erscheint automatisch am unteren Bildschirmrand
5. Nutze den "COPY" Button, um die Zählung in die Zwischenablage zu kopieren
6. Mit "Alle zurücksetzen" kannst du eine neue Zählung beginnen

## 📦 Installation

Keine Installation erforderlich! Einfach die Dateien 1:1 kopieren und die `index.html` im Browser öffnen.

## 🖼️ Bildrechte

**Hinweis:** Die in dieser Anwendung verwendeten Produktbilder stammen von Google Bilder. Es besteht **kein Recht an den Bildern**. Die Bilder dienen ausschließlich der internen Verwendung zur besseren Identifikation der Pfandartikel.

## 🛠️ Technologie

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- Lucide Icons

## 👤 Autor

Erstellt von **Nando** für das FC2

## ⚠️ Haftungsausschluss

Diese Anwendung wurde speziell für den internen Gebrauch im FC2 entwickelt. Die Nutzung erfolgt auf eigene Verantwortung.

