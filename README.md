# M122-Skriptsprachen

**Ein Projekt aus dem Modul 122**

**Gruppenmitglieder:** Marek von Rogall

# Einleitung

Dieses Skript ermöglicht es mithilfe von [ffmpeg](https://github.com/FFmpeg/FFmpeg#readme) massenweise Video-, Bild- & Audiodateien zu konvertieren.
Dazu gibt der Benutzer den gewünschten Input- & Outputordner, sowie das gewünschte Dateiformat in der [Konfigurationsdatei](Skript/config.json) an.
Bitte beachten Sie, dass sich die Konfigurationsdatei & `ffmpeg.exe` (welches sie [hier](https://ffmpeg.org/download.html) heruntunterladen können) im selben Ordner wie [das Skript](Skript/vonRogallMarek_Skript.ps1) befinden.

# Anwendung

Die wichtigsten Einstellungen werden in der [Konfigurationsdatei](Skript/config.json) vorgenommen.
In dieser geben Sie den Input- & Outputordner, sowie das gewünschte Dateiformat an. Die Konfigurationsdatei unterliegt dem JSON-Format.
*Beispiele für die Angabe des Dateiformats: `.mp3`, `.mp4`, `.mov`, etc.*

```JSON
{
    "inputfolder": "C:\\PATH\\TO\\INPUT\\FOLDER",
    "outputfolder": "C:\\PATH\\TO\\OUTPUT\\FOLDER",
    "fileformat": "FILEFORMAT"
}
```
*Hier sehen Sie, wie die Konfigurationsdatei bestückt sein muss, damit das Skript ordnungsgemäss funktioniert.*

# Das Skript ausführen

Um die Konvertierung zu starten muss das Skript zunächst manuell ausgeführt werden. Dazu wählen Sie das Skript im Dateiexplorer mit Rechtsklick an, und wählen "mit PowerShell ausführen".
![image](https://github.com/marekvonrogall/M122-Skriptsprachen/assets/110893394/60fe3053-21ca-4da2-bc6f-4affae893e51)


Alternativ können Sie auch die PowerShell Applikation auf Ihrem Rechner öffnen und zu dem Speicherort des Skripts navigieren. Anschliessend können Sie dieses ausführen.
![image](https://github.com/marekvonrogall/M122-Skriptsprachen/assets/110893394/a1929b1b-f667-4eb8-8870-f251cf2a438c)

# Benötigte Berechtigungen & Clients

Um das Skript auszuführen sind ggf. zusätzliche Berechtigungen notwendig. Überprüfen Sie, dass Sie Ihre PowerShell ExecutionPolicy so eingestellt haben, dass das Ausführen von Skripts auf Ihrem Gerät erlaubt ist. Mehr über die ExecutionPolicy von PowerShell 5.1 erfahren sie [hier](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-5.1)
Das Skript kann auf verschiedenen Clients gleichzeitig ausgeführt werden, benötigt aber nur ein Gerät um ausgeführt zu werden.


