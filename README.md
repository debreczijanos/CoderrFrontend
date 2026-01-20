# Coderr/ Frontend Project

![Coderr Logo](assets/logo/logo_coderr.svg)

Dieses Projekt ist ein einfaches Frontend, das mit **Vanilla JavaScript** (reines JavaScript ohne Frameworks) erstellt wurde. Es wurde speziell entwickelt, um Schülern der **Developer Akademie** mit Backend-Erfahrung den Einstieg in kleinere Frontend-Anpassungen zu erleichtern.

---

## Voraussetzungen

- Ein funktionierendes Django-Backend (`Coderr/`), das **nicht** in diesem Projekt enthalten ist.
- Visual Studio Code mit der **Live Server**-Erweiterung oder eine ähnliche Möglichkeit, die `index.html` lokal im Browser zu starten.

---

## Nutzung

1. Stelle sicher, dass das Backend `Coderr/` läuft.
2. Öffne dieses Projekt in **Visual Studio Code**.
3. Rechtsklicke auf die Datei `index.html` und wähle **Open with Live Server**, um das Projekt zu starten.

---

## Entwicklungs- und Produktionsumgebung (API-Anbindung)

Dieses Frontend erkennt automatisch, ob es lokal oder in Produktion läuft, und verwendet die passende Backend-API.

### Lokal (Development)

- Hostname: `localhost`, `127.0.0.1` oder `file://`
- Erwartete Backend-URL: `http://127.0.0.1:8000`
- Voraussetzung: Das Django-Backend läuft lokal mit `python manage.py runserver`

### Produktion (Live-Demo)

- Hostname: `coderr.debreczi.com`
- Verwendete Backend-API: `https://api.debreczi.com`

Die Umschaltung erfolgt automatisch über die Datei  
`shared/scripts/config.js` und erfordert **keine** manuelle Konfiguration.

---

## Ziel des Projekts

Dieses Frontend wurde bewusst mit **Vanilla JavaScript** erstellt, um die folgenden Ziele zu erreichen:

- **Einfacher Einstieg**: Durch den Verzicht auf Frameworks wie React oder Angular bleibt der Code leicht verständlich und nachvollziehbar.
- **Lernen durch Anpassung**: Schüler können den Code anpassen, um kleine Änderungen vorzunehmen und Frontend-Konzepte besser zu verstehen.
- **Backend-Erweiterung**: Das Projekt lässt sich einfach an das bestehende Django-Backend `Coderr/` anbinden.

---

## Hinweis

Dieses Projekt ist **ausschließlich für Schüler der Developer Akademie** gedacht und nicht zur freien Nutzung oder Weitergabe freigegeben.

---

## JSDoc - ansehen

1. Navigiere in den Ordner `docs/`
2. Du kannst das Projekt öffnen mit Doppelklick auf `docs/index.html`, oder im Terminal
   Windows: `start docs/index.html`
   macOS: `open docs/index.html`
   Linus: `xdg-open docs/index.html`
