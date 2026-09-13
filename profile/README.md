# ProNet Systems GmbH

Wir sind ein IT-Systemhaus in Arnsberg und warten die IT-Infrastruktur mittelständischer
Unternehmen. Was uns im Alltag mit **TANSS** gefehlt hat, haben wir gebaut — und offengelegt.

> **Der Quelltext liegt unter [@pronet-systems](https://github.com/pronet-systems).**
> Diese Seite ist der Wegweiser dorthin.

Alle Werkzeuge haben denselben Zuschnitt: Sie sprechen unmittelbar mit der eigenen
TANSS-Instanz — kein Zwischendienst, kein Herstellerkonto, keine Daten außerhalb des Hauses.

## Zeiterfassung

- **[TANSS Log-Watcher](https://github.com/pronet-systems/tanss-log-watcher)** —
  erkennt Fernwartungssitzungen (AnyDesk, TeamViewer, Remotedesktop, ScreenConnect und drei
  Dutzend weitere) am Windows-Arbeitsplatz und bucht sie als Fernwartung.
- **[TANSS Git-Connector](https://github.com/pronet-systems/tanss-git-connector)** —
  bucht jeden Git-Commit per `post-commit`-Hook als Fernwartung. Linux, Windows, macOS.

## Microsoft 365

- **[TANSS Outlook Add-in](https://github.com/pronet-systems/tanss-outlook-addin)** —
  legt E-Mails an Tickets ab, erzeugt Tickets aus E-Mails, pflegt zum Outlook-Termin den Einsatz.
- **[TANSS Calendar Sync](https://github.com/pronet-systems/tanss-calendar-sync)** —
  gleicht Termine zwischen TANSS und Microsoft 365 in beide Richtungen ab.

## Schnittstellen

- **[TANSS MCP Server](https://github.com/pronet-systems/tanss-mcp-server)** —
  Model-Context-Protocol-Server für die TANSS-API: 237 Werkzeuge für Claude, n8n und andere
  Assistenten.
- **[tanss-coder](https://github.com/pronet-systems/tanss-coder)** —
  ver- und entschlüsselt Dokumente in der TANSS-Datenbank, etwa für ein RAG-System.

---

[www.pronet-systems.de](https://www.pronet-systems.de) · Arnsberg

TANSS ist ein Produkt der HUCK IT GmbH, Roßdorf (Amtsgericht Darmstadt, HRB 95700). Diese
Projekte sind unabhängige Werkzeuge, stehen in keiner Verbindung zur HUCK IT GmbH und werden von
ihr weder unterstützt noch geprüft. Marken gehören ihren jeweiligen Inhabern; die Nennung dient
allein dazu, zu sagen, wofür diese Werkzeuge gemacht sind.
