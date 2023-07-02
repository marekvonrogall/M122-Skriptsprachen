# Lern-Bericht

**Mitglieder:** Marek von Rogall

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Einleitung

In diesem Projekt sollten wir mithilfe von PowerShell einen Vorgang automatisieren.
Ich habe mich dazu entschieden, ein Skript zu erstellen, mit welchem man massenweise Audio-, Bild- & Videodateien konvertieren kann.

## Was habe ich gelernt?

In diesem Projekt habe ich gelernt, wie man die ForEach-Schleife benutzt.

## Code-Erklärung

Als Erstes habe ich ein Array definiert und mit verschiedenen Strings bestückt.
Mit der ForEach-Schleife sage ich nun, dass ich den Inhalt der Schleife für jedes Element in dem Array ausführen möchte.
In diesem Beispiel schreibe ich das Element in die Konsole.

```powershell
$objects = @('Stuhl', 'Tisch', 'Vase', 'Pflanze', 'Ofen', 'Kochtopf')

ForEach ($item in $objects) {
    Write-Host $item -ForegroundColor Red
}

Pause
```
*Dieser Code beinhaltet die oben beschriebenen Schritte um eine ForEach Schleife zu benutzen.*

![PowerShellAusgabe__LBM122](https://github.com/marekvonrogall/M122-Skriptsprachen/assets/110893394/dd2fb4d7-e62d-4bb4-bcb7-bb233dd85b9c)

*Hier sieht man die Ausgabe, wenn man den Code ausführt.*



## Verifikation

* `Textbeschreibung:` Die Textbeschreibung dient zur Verständlichkeit des Codes.

* `Code:` Dieser Code ist ein Beispiel, wie man eine ForEach-Schleife benutzen könnte.

* `Bild:` Das Bild dient zur Veranschaulichung des Codes.

# Reflexion zum Arbeitsprozess


👍Bei meiner Arbeit lief gut, dass ich schnell mit dem Skript vorangekommen bin.


👎Bei meiner Arbeit lief nicht gut, dass ich relativ spät mit den Dokumentationen begonnen habe.


**VBV**: Für mein nächstes Projekt nehme ich mir vor, früher mit den Projektdokumentationen zu beginnen, um nicht in Zeitdruck zu geraten.


