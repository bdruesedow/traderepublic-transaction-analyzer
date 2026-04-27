# 📈 Trade Republic Analyzer (& AI Edition)

Ein leistungsstarkes, komplett lokal im Browser laufendes Tool zur Analyse deiner Trade Republic Transaktionsdaten. Finde endlich heraus, wie hoch dein wirklicher realisierter Netto-Profit nach allen Steuern und Gebühren ist.

## ✨ Funktionen

🔒 100% Datenschutz: Die App besteht aus einer einzigen HTML-Datei. Deine Finanzdaten (CSV) werden per JavaScript nur lokal in deinem Browser verarbeitet und niemals an einen Server gesendet.

* 🧮 Exakte FIFO-Berechnung: Käufe und Verkäufe werden intelligent nach dem First-In-First-Out (FIFO) Prinzip verknüpft.
* 💶 Echtes Netto: Ordergebühren (1€) und abgeführte Steuern werden exakt den einzelnen Trades zugeordnet. Du siehst deinen echten Netto-Profit.
* 📅 Trading-Kalender (Heatmap): Optische Übersicht deiner Gewinn- und Verlusttage in einer Kalenderansicht.
* 📊 Jahres- & Asset-Übersicht: Detaillierte Aufschlüsselung deiner Performance, Dividenden und Zinsen nach Jahren und einzelnen Wertpapieren.
* 🤖 KI-Features (Optional): Nutze die Power von Google Gemini, um dein Portfolio bewerten zu lassen oder aktuelle Live-News zu deinen Assets abzurufen.

## 🚀 Nutzung

Das Tool erfordert keine Installation oder Backend-Server.
1. Lade deinen Transaktionsexport in der Trade Republic App herunter:
  * Profil -> Kontoauszüge -> Transaktionsexport
2. Öffne die index.html Datei in einem beliebigen modernen Webbrowser.
  * Alternativ: Nutze den gehosteten Link über GitHub Pages
3. Klicke auf "CSV-Datei auswählen" und lade deinen Export hoch.
4. Fertig! Die Auswertung erscheint sofort.

## 🧠 KI-Funktionen aktivieren (Google Gemini)

Die KI-Funktionen sind standardmäßig deaktiviert, um die App so simpel wie möglich zu halten. Wenn du sie nutzen möchtest:
1. Klicke in der App oben rechts auf das Zahnrad-Symbol (⚙️).
2. Aktiviere den Schalter für "KI-Features aktivieren".
3. Besorge dir einen kostenlosen API-Key von Google AI Studio.
4. Füge den Key in das Feld ein. Der Key wird sicher und ausschließlich lokal im localStorage deines Browsers gespeichert.

Danach erscheinen neue Buttons in der App:
* KI-Depot-Check (Übersicht): Ein persönliches Fazit und Feedback zu deinem Portfolio.
* KI-News (Assets): Echtzeit-Nachrichten (via Google Search Grounding) und eine Zusammenfassung zum Geschäftsmodell einzelner Aktien/ETFs.

## 🛠️ Technische Details

* Single-File App: Alles (HTML, Logik, Styling) lebt in der index.html.
* React: Wird zur Laufzeit über CDN geladen (react.production.min.js).
* Tailwind CSS: Für das moderne, responsive UI (cdn.tailwindcss.com).
* Babel: Übersetzt das JSX direkt im Browser (babel.min.js).
* Icons: FontAwesome 6.4.

## ⚠️ Disclaimer

Dieses Projekt ist kein offizielles Produkt von Trade Republic. Es handelt sich um ein Open-Source-Hobbyprojekt. Die berechneten Gewinne, Verluste und Steuern dienen nur zur Veranschaulichung und Übersicht. Sie ersetzen keine offizielle Steuerberatung. Nutzung auf eigene Gefahr.
