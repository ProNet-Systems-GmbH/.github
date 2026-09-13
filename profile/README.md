![ProNet Systems GmbH](logo.png)

# ProNet Systems GmbH

Die ProNet Systems GmbH ist seit 2008 ein Full-Service-IT-Dienstleister aus Arnsberg, ein
IT-Systemhaus aus dem Sauerland. Wir betreuen mittelständische Unternehmen mit bis zu 250
PC-Plätzen sowie kleine und mittlere Unternehmen ohne eigene IT-Abteilung.

## Was wir machen

- IT-Services: persönliche Betreuung, Fernwartung, Ticketsystem, Rollout von IT-Infrastrukturen,
  Software Defined Networking
- Netzwerkadministration: Windows-Server, Exchange, Remote Desktop Service, Virtualisierung,
  Server-Monitoring, IT-Dokumentation
- IT-Sicherheit: Backup, Firewall, Endpoint Security, Anti-Spam, E-Mail-Archivierung,
  Verschlüsselung, USV, Penetration Testing, Hilfe bei Ransomware-Befall, Datenrettung
- Kommunikation: IP-Telefonanlagen, Unified Communication, WiFi, Richtfunk
- Cloud-Services

Wir arbeiten mit Microsoft, VMware, Veeam, Sophos, Lancom, Lenovo, HP, Fujitsu, 3CX, Estos und
APC, sind anerkannter Ausbildungsbetrieb und beteiligen uns an der Allianz für Cybersicherheit.

---

## Was wir veröffentlichen

Was uns im eigenen Betrieb gefehlt hat, haben wir gebaut und einen Teil davon offengelegt. Bei
den Programmen auf dieser Seite sind wir zuerst Anwender und dann Entwickler. Geordnet ist das
nach dem Umfeld, für das ein Werkzeug gemacht ist — TANSS ist bislang das einzige.

> Der Quelltext liegt nicht in dieser Organisation, sondern im Benutzerkonto
> [github.com/pronet-systems](https://github.com/pronet-systems). Jeder Name unten führt
> unmittelbar in das zugehörige Repository.

### Werkzeuge für TANSS

TANSS ist das Ticketsystem, in dem wir Aufträge, Einsätze und die Zeiterfassung führen. Die
folgenden sechs Werkzeuge ergänzen es dort, wo unser Alltag mehr verlangt hat als den
Standardumfang.

- [TANSS Log-Watcher](https://github.com/pronet-systems/tanss-log-watcher) erkennt am
  Windows-Arbeitsplatz laufende Fernwartungssitzungen (AnyDesk, TeamViewer, Remotedesktop,
  ScreenConnect und drei Dutzend weitere), fragt nach Kommentar und Ticket und bucht die
  Fernwartung.
- [TANSS Git-Connector](https://github.com/pronet-systems/tanss-git-connector) bucht über einen
  post-commit-Hook jeden Git-Commit als Fernwartung. Für Linux, Windows und macOS.
- [TANSS Outlook Add-in](https://github.com/pronet-systems/tanss-outlook-addin) legt E-Mails
  samt Anhängen an Tickets ab, erzeugt aus E-Mails Tickets und pflegt zum Outlook-Termin den
  zugehörigen TANSS-Einsatz. Es besteht aus statischen Dateien und braucht keinen Dienst.
- [TANSS Calendar Sync](https://github.com/pronet-systems/tanss-calendar-sync) gleicht Termine
  zwischen TANSS und Microsoft 365 in beide Richtungen ab. Python, als systemd-Dienst.
- [TANSS MCP Server](https://github.com/pronet-systems/tanss-mcp-server) stellt die TANSS-API
  als Model-Context-Protocol-Server bereit, mit 237 Werkzeugen für Claude, n8n und andere
  Assistenten.
- [tanss-coder](https://github.com/pronet-systems/tanss-coder) ver- und entschlüsselt Dokumente
  in der TANSS-Datenbank, etwa als Zuarbeit für ein RAG-System.

Vier davon stehen unter der MIT-Lizenz und sind damit Open Source: Log-Watcher, Git-Connector,
Outlook Add-in und Calendar Sync. Für TANSS MCP Server und tanss-coder liegt keine Lizenzdatei
im Repository; sie sind nicht als Open Source veröffentlicht. Wer sie einsetzen möchte, spricht
uns vorher an.

## Kontakt

- ProNet Systems GmbH, Wiebelsheidestraße 51, 59757 Arnsberg
- [www.pronet-systems.de](https://www.pronet-systems.de)
- Quelltext: [github.com/pronet-systems](https://github.com/pronet-systems)

Fragen zu einem einzelnen Werkzeug gehören am besten in das jeweilige Repository.

---

TANSS ist ein Produkt der HUCK IT GmbH, Roßdorf (Amtsgericht Darmstadt, HRB 95700). Diese
Projekte sind unabhängige Werkzeuge, stehen in keiner Verbindung zur HUCK IT GmbH und werden
von ihr weder unterstützt noch geprüft. Marken gehören ihren jeweiligen Inhabern; die Nennung
dient allein dazu, zu sagen, wofür diese Werkzeuge gemacht sind.
