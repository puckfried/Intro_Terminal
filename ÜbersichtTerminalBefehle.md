# Terminalbefehle

## Navigation und Dateiverwaltung

| **Befehl** | **Beschreibung** | **Beispiel** | **Anwendung** |
|------------|-------------------|--------------|---------------|
| `ls`       | Listet Dateien und Ordner im aktuellen Verzeichnis auf. | `ls -la` | `-l` zeigt detaillierte Liste mit Berechtigungen und Größen an. `-a` zeigt versteckte Elemente an |
| `cd`       | Wechselt das Verzeichnis. | `cd /home/user/Documents` | `cd ..` geht eine Ebene höher im Verzeichnisbaum. |
| `pwd`      | Zeigt den aktuellen Pfad (Print Working Directory). | `pwd` | Praktisch, um sich zu orientieren, wo man sich im Dateisystem befindet. |
| `which`      | Zeigt an, wo sich ein Programm befindet. | `which code` | Druckt den Installationsort von VS Code aus. |
| `mkdir`    | Erstellt ein neues Verzeichnis. | `mkdir neuerOrdner` | Keine Flags nötig, einfaches Erstellen von Ordnern. |
| `touch`    | Erstellt eine leere Datei. | `touch datei.txt` | Kann zum Erstellen von Platzhaltern verwendet werden. |
| `rm`       | Löscht Dateien oder Verzeichnisse. | `rm -r ordner` | `-r` löscht rekursiv, d. h. einschließlich aller Dateien im Ordner. |
| `cp`       | Kopiert Dateien oder Verzeichnisse. | `cp -r ordner /zielverzeichnis` | `-r` kopiert rekursiv, d. h. auch den gesamten Inhalt von Ordnern. |
| `mv`       | Verschiebt oder benennt Dateien um. | `mv datei.txt neuername.txt` | `mv datei.txt /ziel` verschiebt Datei ins Zielverzeichnis. |


### Textbearbeitung und Dateiinhalt

| **Befehl** | **Beschreibung** | **Beispiel** | **Anwendung** |
|------------|-------------------|--------------|---------------|
| `cat`      | Gibt den Inhalt einer Datei im Terminal aus. | `cat datei.txt` | Ideal zum schnellen Anzeigen kleinerer Textdateien. |
| `nano`     | Einfache Textbearbeitung direkt im Terminal. | `nano datei.txt` | Einfache Alternative zu komplexeren Editoren wie vim. |
| `head` / `tail` | Zeigt die ersten oder letzten Zeilen einer Datei an. | `head -n 5 datei.txt` | `-n 5` zeigt die ersten bzw. letzten 5 Zeilen. |
| `grep`     | Sucht nach bestimmten Wörtern oder Ausdrücken in einer Datei. | `grep "Suchwort" datei.txt` | `-i` ignoriert Groß-/Kleinschreibung in der Suche. |


### Nützliche Shell-Funktionen

| **Befehl** | **Beschreibung** | **Beispiel** | **Anwendung** |
|------------|-------------------|--------------|---------------|
| `history`  | Zeigt die Befehls-Historie an. | `history` | Hilfreich zum Nachschlagen oder Wiederverwenden alter Befehle. |
| `man`      | Zeigt die Handbuchseiten (Manual Pages) für Befehle an. | `man ls` | Zeigt Dokumentation und Optionen eines Befehls. |
| `echo`     | Gibt Text oder Variablen aus. | `echo $HOME` | `$HOME` gibt das Home-Verzeichnis des Benutzers aus. |
| `clear`    | Löscht den Terminal-Bildschirm und sorgt für eine übersichtliche Oberfläche. | `clear` | Macht das Terminal übersichtlich, ideal für längere Sessions. |


### Netzwerk und Internet

| **Befehl** | **Beschreibung** | **Beispiel** | **Anwendung** |
|------------|-------------------|--------------|---------------|
| `ping`     | Sendet Pakete an einen Server, um die Erreichbarkeit zu testen. | `ping -c 4 google.com` | `-c 4` begrenzt die Anzahl der Pakete auf 4. |
| `curl`     | Ruft Inhalte von URLs ab. Kann Dateien herunterladen. | `curl -O https://example.com/datei.zip` | `-O` speichert Datei mit dem Originalnamen im aktuellen Verzeichnis. |

