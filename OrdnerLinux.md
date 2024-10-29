# Wichtige Ordner im Ubuntu-Dateisystem

Im Ubuntu-Dateisystem gibt es eine standardisierte Verzeichnisstruktur. Diese Struktur ist nach dem Filesystem Hierarchy Standard (FHS) organisiert, der festlegt, welche Verzeichnisse es gibt und wofür sie verwendet werden.

## 1. `/` - Root-Verzeichnis
Das oberste Verzeichnis im Dateisystem und enthält alle anderen Verzeichnisse. Es ist das Startverzeichnis des Dateisystems.

## 2. `/bin` - Binaries (Grundlegende Systemprogramme)
Enthält grundlegende ausführbare Dateien (Programme) wie `ls`, `cp`, `mv`, `cat` usw., die von allen Benutzern genutzt werden können. Diese Programme sind essenziell für den Systembetrieb und sollten immer verfügbar sein, auch wenn das System im Wartungsmodus läuft.

## 3. `/boot` - Startdateien
Enthält Dateien, die für den Startvorgang notwendig sind, darunter den **Linux-Kernel** und den **Bootloader** (z. B. GRUB). Hier liegen Dateien wie `vmlinuz` (Kernel) und `initrd.img` (Initial RAM Disk).

## 4. `/dev` - Device-Dateien
Hier befinden sich Gerätedateien, die auf Hardware-Komponenten verweisen, z. B. Festplatten (`/dev/sda`), USB-Geräte und virtuelle Geräte. Diese Dateien stellen die Schnittstelle zwischen Software und Hardware dar.

## 5. `/etc` - Konfigurationsdateien
Enthält System- und Anwendungs-Konfigurationsdateien. Beispiele sind Netzwerkeinstellungen in `/etc/network` oder Benutzerinformationen in `/etc/passwd`. Dies ist ein zentraler Ort für die Verwaltung und Anpassung des Systems.

## 6. `/home` - Benutzerverzeichnisse
Enthält für jeden Benutzer ein eigenes Verzeichnis (z. B. `/home/username`). Diese Verzeichnisse enthalten alle persönlichen Dateien, Einstellungen und Daten der jeweiligen Benutzer.

## 7. `/lib` - Systembibliotheken
Enthält essenzielle Bibliotheken, die von Programmen in `/bin` und `/sbin` benötigt werden. Diese Bibliotheken sind ähnlich wie `.dll`-Dateien unter Windows und werden zum Ausführen von Systemprogrammen gebraucht.

## 8. `/media` und `/mnt` - Einhängepunkte für Wechselmedien und temporäre Dateisysteme
- **`/media`**: Hier werden automatisch eingehängte externe Geräte wie USB-Sticks, externe Festplatten und DVDs gemountet.
- **`/mnt`**: Wird oft als temporärer Einhängepunkt für Dateisysteme genutzt, z. B. beim manuellen Einhängen eines Netzlaufwerks oder einer Partition.

## 9. `/opt` - Optionale Softwarepakete
In `/opt` werden häufig optionale oder zusätzliche Softwarepakete installiert, die nicht über das normale Paketverwaltungssystem installiert wurden. Dies ist üblich für kommerzielle oder große Softwarepakete.

## 10. `/proc` - Prozessinformationen und Systemstatus
Ein virtuelles Dateisystem, das Informationen über laufende Prozesse und den Systemstatus bereitstellt. Dateien wie `/proc/cpuinfo` (Informationen zur CPU) oder `/proc/meminfo` (Informationen zum Arbeitsspeicher) ermöglichen das Abfragen von Systemressourcen.

## 11. `/root` - Home-Verzeichnis des Root-Benutzers
Das Home-Verzeichnis des Root-Benutzers, des Systemadministrators. Im Gegensatz zu normalen Benutzerverzeichnissen befindet sich dieses Verzeichnis direkt unter `/`.

## 12. `/run` - Laufzeitdaten
Enthält Informationen und temporäre Dateien, die von laufenden Prozessen und Diensten benötigt werden. Diese Daten sind oft nur während der Systemlaufzeit gültig und werden beim Neustart gelöscht.

## 13. `/sbin` - Systembinaries
Enthält wichtige Systemverwaltungsprogramme, die vor allem vom Administrator (Root) genutzt werden, z. B. `reboot`, `ifconfig`, `fdisk`. Diese Programme sind notwendig für Systemadministration und -wartung.

## 14. `/srv` - Servicedaten
In `/srv` werden Daten abgelegt, die von Diensten und Serveranwendungen bereitgestellt werden, z. B. Dateien für Webserver oder FTP-Server.

## 15. `/tmp` - Temporäre Dateien
`/tmp` ist für temporäre Dateien, die während einer Sitzung erstellt werden und nach einem Neustart oft gelöscht werden. Programme nutzen `/tmp`, um Daten zwischenzuspeichern, die n
