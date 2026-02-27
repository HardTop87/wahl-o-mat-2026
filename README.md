# Wahl-O-Mat Kaufering & Landsberg 2026 🗳️

Dies ist eine professionelle, lokal angepasste Voting Advice Application (VAA) – besser bekannt als "Wahl-O-Mat" – für die Kommunalwahlen am 08. März 2026 in der Marktgemeinde Kaufering und dem Landkreis Landsberg am Lech.

## 🌟 Features
* **4 Wahlen in einer App:** Bürgermeister, Gemeinderat, Landrat und Kreistag.
* **Original bpb-Algorithmus:** Nutzt das offizielle Distanz-Modell der Bundeszentrale für politische Bildung (inkl. doppelter Gewichtung und Überspringen-Funktion).
* **Interaktiver Stimmenverteiler:** Berechnet nach dem Hare-Niemeyer-Verfahren exakt, wie du deine 24 (bzw. 60) Stimmen verteilen kannst.
* **Live-Sandkasten:** Im Ergebnisbildschirm kannst du in einer Tabelle deine Antworten nachträglich ändern – die Diagramme passen sich live an.
* **Auto-Save:** Dein Fortschritt wird im Browser gespeichert. Schließt du den Tab, kannst du später genau dort weitermachen.
* **Dark Mode & Print Ready:** Optimiert für Smartphones, Desktops (inkl. Milchglas-Effekten) und perfekt formatiert für den Ausdruck als Spickzettel.

## 🚀 Setup & Installation (GitHub Pages)

Diese App besteht aus einer einzigen, hochgradig optimierten HTML-Datei (`index.html`). Es werden keine externen Frameworks wie React oder Vue benötigt, und es gibt kein Backend (Zero Tracking).

1.  Lade die Datei `index.html` in dieses Repository hoch.
2.  Gehe in deinem Repository auf **Settings** -> **Pages**.
3.  Wähle unter "Source" den Zweig `main` (oder `master`) und den Ordner `/ (root)` aus. Klicke auf Save.
4.  Nach ein paar Minuten ist dein eigener Wahl-O-Mat unter `https://[dein-username].github.io/[dein-repo-name]/` online erreichbar!

## ⚖️ Rechtliches
* **Datenschutz:** Die App speichert keine Antworten auf Servern. Alles passiert lokal via `localStorage` im Browser des Nutzers. Eine DSGVO-konforme Datenschutzerklärung ist in die App integriert.
* **Impressumspflicht:** Vergiss nicht, im HTML-Code bei den Platzhaltern (`[DEIN VORNAME NACHNAME]`) deine Impressumsdaten einzutragen, bevor du die Seite live schaltest.

---
*Gebaut für eine starke lokale Demokratie in Bayern.*
