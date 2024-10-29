# BDL - Grundlagen - 02: Linux


**Gestern**
- Kennenlernen
- Warum Linux
- Softwareentwicklung im Allgemeinen
- Kursübersicht

**HEUTE**
- Das Linux-Dateisystem
- Linux Terminal
- Terminalbefehle
- kleine Übung
- Bonus: "Terminalprogramm"


## Das Linux-Dateisystem

- Bevor wir anfangen, eine Erinnerung
    - **Du musst nicht alles perfekt behalten**
    - Du hast das Internet und viel Zeit zum Üben!


- Du kennst vielleicht die Funktionsweise von Dateien in Windows
- Dort hast du deine C:\ und möglicherweise D:\ usw. Laufwerke, die das Dateisystem enthalten
- In Linux gibt es keine solchen Laufwerke
- Dateien und Ordner (in Linux meist Verzeichnisse genannt) existieren in einer Hierarchie
- Alles beginnt vom Root-Verzeichnis, `/`
- Jede Datei und jeder Ordner hat einen einzigartigen Pfad

- `/tmp/notes.txt`
    - Im Root gibt es ein Verzeichnis namens tmp
    - In tmp gibt es eine Datei namens notes.txt

 `/home/dci/cv.pdf`
    - Im Root gibt es ein Verzeichnis namens home
    - In home gibt es ein Verzeichnis namens dci
    - In dci gibt es eine Datei namens `cv.pdf`

- Vier bemerkenswerte Verzeichnisse

    - `/`				das Root-Verzeichnis
    - `/etc`			Konfigurationsdateien
    - `/var`			Log-Dateien und andere Dateien variabler Größe
    - `/home`			Home-Verzeichnisse

- Normalerweise hat jeder Benutzer auf einem Linux-Computer sein eigenes Home-Verzeichnis
    - `/home/sarah`
    - `/home/ferdinand`
    - `/home/inkeri`
    - Der Verzeichnisname ihres Home-Verzeichnisses (`sarah`) entspricht ihrem Benutzernamen
    - Dies ist "nach Konvention"
        - Das bedeutet, es ist keine feste Regel, aber es wird praktisch überall verwendet    

- Das Home-Verzeichnis des aktuellen Benutzers hat auch eine kleine Abkürzung
    - Der Pfad `~` bezieht sich auf das Home-Verzeichnis des aktuellen Benutzers
    - Wenn man als `dci` eingeloggt ist, ist das Home-Verzeichnis oder `~` `/home/dci`


## Terminal
- Zentrale Schnittstelle des Betriebssystems: Die Shell ist das wichtigste Werkzeug, um direkt mit dem Linux-Betriebssystem zu interagieren und ermöglicht umfassenden Zugriff auf Systemressourcen und Konfigurationen.
- Effiziente Bedienung und Steuerung des Systems: Mit der Shell lassen sich alle Aspekte von Linux schnell und präzise kontrollieren, wodurch sie besonders für Automatisierung und Entwicklung essenziell ist.
- Wenn du arbeitest, empfehle ich **DRINGEND**, immer im Projekte-Ordner zu arbeiten
- Und **IMMER** Backups von allem Wichtigen zu machen


### Terminalbefehle
- siehe [Übersicht](./ÜbersichtTerminalBefehle.md)


### Wichtige Shortcuts
- `Strg`+ `Shift`+`c` - kopieren
- `Strg`+ `Shift`+`v` - einfügen
- `Strg`+ `a` - zum Anfang der Zeile springen
- `Strg`+ `e` - zum Anfang der Zeile springen
- `Pfeil hoch/runter` - durch die letzten Befehlen scrollen