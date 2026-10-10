# Werkstatt-Software – Downloads

Hier liegen die Installationsdateien der Werkstatt-Software für Windows.

## Installieren

1. Unter **[Releases](https://github.com/Stan2449/werkstatt-software-releases/releases/latest)**
   die neueste Datei `Werkstatt-Setup-<Version>.exe` herunterladen
2. Doppelklick und den Schritten folgen (keine Administratorrechte nötig)
3. Meldet Windows „Der Computer wurde durch Windows geschützt“: **Weitere Informationen →
   Trotzdem ausführen**

## Updates

Das Programm prüft beim Start selbst, ob es eine neue Version gibt, und bietet die
Installation an (**Hilfe → Nach Updates suchen**). Vorher wird automatisch eine
Datensicherung angelegt. Ihre Daten bleiben bei Updates und auch bei einer Deinstallation
erhalten (`%LOCALAPPDATA%\Werkstatt`).

## Prüfsumme

Zu jeder Setup-Datei gibt es eine `.sha256`-Datei. Das Update im Programm prüft sie
automatisch. Von Hand in PowerShell:

```powershell
Get-FileHash .\Werkstatt-Setup-0.5.0.exe -Algorithm SHA256
```

## Probleme melden

Im Programm **Hilfe → Fehlerbericht erstellen** und die erzeugte ZIP-Datei an Ihren
Ansprechpartner schicken.

---

Diese Software ist nicht frei lizenziert. Alle Rechte vorbehalten.
