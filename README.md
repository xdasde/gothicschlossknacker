# Gothic Schloss-Knacker / Gothic Lock Cracker

🇩🇪 Ein Lösungshelfer für das Schloss-Minispiel. Du gibst die Ausgangslage des
Schlosses ein, und das Tool berechnet die **optimale Zugfolge** und führt dich
Schritt für Schritt durch die Tastendrücke.

🇬🇧 A solver helper for the lock mini-game. You enter the lock's starting state,
and the tool computes the **optimal move sequence** and walks you through the key
presses step by step.

**▶ Live:** https://gothic-lockpicker--xdas.replit.app/

---

## 🇩🇪 Funktion

1. **Riegel festlegen** – Anzahl der Riegel wählen.
2. **Schloss & Pin-Positionen eingeben** – aktuellen Zustand des Schlosses abbilden.
3. **Verbindungen setzen** – wie die Riegel zusammenhängen (in PIN-Richtung gedacht).
4. **Lösung berechnen** – das Tool ermittelt die kürzeste Zugfolge.

Danach kannst du:

- die **Zugfolge Schritt für Schritt** mitlaufen lassen (Vor/Zurück),
- in den **Präsentationsmodus** wechseln (großer Mitlauf-Modus fürs Handy oder
  einen zweiten Monitor),
- ein **AutoHotkey-Makro (.ahk)** herunterladen oder das Skript kopieren, das die
  Tastenfolge automatisch ausführt.

## 🇬🇧 How it works

1. **Set the bolts** – choose the number of bolts.
2. **Enter lock & pin positions** – mirror the lock's current state.
3. **Set connections** – how the bolts relate (thought of in PIN direction).
4. **Compute solution** – the tool finds the shortest move sequence.

Afterwards you can:

- step through the **move sequence** (forward/back),
- switch to **presentation mode** (large follow-along view for a phone or a
  second monitor),
- download an **AutoHotkey macro (.ahk)** or copy the script that runs the key
  sequence automatically.

---

## 🇩🇪 Bedienung / 🇬🇧 Controls

- **Sprache / Language:** Deutsch & Englisch, automatisch nach Browsersprache,
  oben rechts umschaltbar (DE/EN). / German & English, auto-detected from the
  browser, toggle top-right.
- **Schema / Scheme:** Tastatur- oder Controller-Belegung. / Keyboard or
  controller layout.
- **Präsentation / Presentation:** `→` / Leertaste = weiter · `←` = zurück ·
  `Esc` = schließen. / `→` / Space = next · `←` = back · `Esc` = close.

---

## 🇩🇪 Technik / 🇬🇧 Tech

🇩🇪 Eine einzige, eigenständige Datei: **`index.html`** – kein Build, keine
Abhängigkeiten, kein Server nötig. Einfach im Browser öffnen.

🇬🇧 A single self-contained file: **`index.html`** – no build, no dependencies,
no server needed. Just open it in a browser.
