# Vibe Lab

Deine Arbeitsumgebung für eigene KI-Agenten mit Mistral Vibe. Läuft komplett
im Browser, du installierst nichts auf deinem Rechner.

## Start in drei Schritten

1. Oben auf **Code**, dann **Codespaces**, dann **Create codespace on main** klicken.
   Nach ein bis zwei Minuten ist VS Code im Browser offen.
2. Wenn VS Code fragt, ob du dem Ordner vertraust: **Ordner vertrauen**.
3. Im Terminal unten `vibe` eintippen, Enter. Beim ersten Start fragt Vibe nach
   deinem Mistral API Key (aus https://console.mistral.ai). Einfügen, fertig.

Danach vertraut Vibe dem Ordner einmal (ja), und `/mcp` zeigt deine Werkzeuge.

## Was drin ist

- **Vibe**, der Coding-Agent von Mistral, im Terminal und als VS-Code-Erweiterung
- **Werkzeuge ohne Key:** `context7` (aktuelle Doku zu Bibliotheken), `fetch` (Webseiten lesen)
- **Skills** in `.vibe/skills`, die Vibe strukturiert arbeiten lassen
  (brainstorming, writing-plans, test-driven-development, systematic-debugging, ...)

## Dein Key

Der Key liegt nur in deinem Codespace unter `~/.vibe/.env`, nie im Repository.
Er bleibt erhalten, wenn der Codespace pausiert. Löschst du den Codespace,
fragt Vibe beim nächsten Mal einfach erneut.
