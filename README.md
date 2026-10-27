# 📦 Pfanderfassung – Palettenzähler

Eine einfache Web-Anwendung zum Zählen der fertigen Paletten pro Ordertyp.

## 📝 Beschreibung

Der Palettenzähler wurde für das FC2 entwickelt, um schnell zu erfassen, wie viele fertige Paletten es pro Ordertyp gibt. Er enthält die 35 Ordertypen aus dem Sortier-Ordner, in derselben Reihenfolge wie im Ordner und mit Bildern von Kasten und Flaschen.

Die bisherige **Pfandzählung V2** (mit weiteren Pfandartikeln wie Folie, RC, Plomben und Pfandsäcken) liegt unverändert auf dem Branch `main`.

Die Anwendung wurde von **Nando** mit Unterstützung von Claude (AI-Assistent) erstellt und ist ausschließlich für den internen Gebrauch im FC2 bestimmt.

## ✨ Features

- 📱 **Fürs Handy gebaut** – große Tippflächen, Summe und Kopieren-Button immer unten sichtbar
- 👆 **Antippen = +1 Palette** – mit dem **−** links wird ein Vertipper wieder abgezogen
- 🖼️ **Bilder aus dem Ordner** – zu jedem Ordertyp Kasten und Flaschen, über „Bilder anzeigen“ ausblendbar
- 📋 **Kopieren** – Liste im Format `Bier 0.33L: 5x`, auf Wunsch mit allen Ordertypen inklusive 0
- 💾 **Automatisches Speichern** – die Zählung bleibt im Browser erhalten, auch nach dem Neuladen
- 🔄 **Alle auf 0 setzen** – mit zweitem Tipp zur Bestätigung und „Rückgängig“
- 🌙 **Hell und dunkel** – folgt der Einstellung des Geräts

## 🔒 Datenschutz & Speicherung

**Wichtig:** Die Zählung erfolgt **lokal auf dem Endgerät** und wird **nicht auf einem Server gespeichert**. Es werden keine Logs erstellt oder Daten übertragen.

- Alle Eingaben werden automatisch im Browser-Speicher (localStorage) gespeichert
- Die Daten bleiben erhalten, bis unten auf „Alle auf 0 setzen“ getippt wird

## 🚀 Verwendung

1. Öffne die `index.html` in einem modernen Webbrowser (der Ordner `img/` muss daneben liegen)
2. Tippe für jede fertige Palette auf den passenden Ordertyp
3. Tippe unten auf **Kopieren** und füge die Liste ein, zum Beispiel:
   ```
   Bier 0.33L: 5x
   Stubbi 0.5L: 6x
   Cola PET 1L: 3x
   ```
4. Für eine neue Zählung unten auf **Alle auf 0 setzen** tippen

## 📦 Installation

Keine Installation erforderlich! Einfach `index.html` und den Ordner `img/` 1:1 kopieren und die `index.html` im Browser öffnen.

## 🖼️ Bildrechte

- `img/*.jpg` – Ausschnitte aus Fotos des Sortier-Ordners (Kasten und Flaschen je Ordertyp)
- `img/*.png` – Bilder der Pfandzählung V2 von Google Bilder, im Palettenzähler nicht verwendet

**Hinweis:** Es besteht **kein Recht an den Produktbildern**. Die Bilder dienen ausschließlich der internen Verwendung zur besseren Identifikation der Pfandartikel.

## 🛠️ Technologie

- HTML, CSS und Vanilla JavaScript in einer einzigen Datei
- Schriften Barlow und Barlow Condensed (Google Fonts); ohne Internet wird eine Systemschrift verwendet

## 👤 Autor

Erstellt von **Nando** für das FC2

## ⚠️ Haftungsausschluss

Diese Anwendung wurde speziell für den internen Gebrauch im FC2 entwickelt. Die Nutzung erfolgt auf eigene Verantwortung.
