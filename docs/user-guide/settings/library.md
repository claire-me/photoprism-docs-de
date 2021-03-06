# Bibliothekseinstellungen #

## Umwandlung von RAW zu JPEG ##
Viele Fotografen, insbeondere Nutze einer digitalen SLR, verwenden ein verlustfreies RAW-Format anstelle des verlustbehafteten JPEG-Formats. Es gibt auch [Handies](https://www.fredericpaulussen.be/how-to-raw-photos-huawei-p30-pro/) die RAW-Daten abspeichern können oder das Format HEIC/HEIF nutzen.
Das Ziel von PhotoPrism ist eine umfangreiche Unterstützung für alle [RAW-Formate](https://en.wikipedia.org/wiki/Raw_image_format), unabhängig vom verwendeten Kameramodell. Deshalb bitten wir dich uns eine Nachricht zu schicken, falls du ein Problem mit den Dateien von einem deiner Geräte hast.

Webbrowser können keine RAW-Formate anzeigen. Deshalb muss PhotoPrism diese dateien *importieren* und *konvertieren*. Um diese Schritte zu konfigurieren, findest du entsprechende Schalter in den [User-Interface Einstellungen](ui.md).

Zusätzlich zu den oben genannten Formaten unterstützt PhotoPrism auch BMP-, GIF-, PNG- und TIFF-Dateien. Bevor du diese Formate zur Speicherung nutzt, solltest du bedenken, dass sie oft keine Metadaten speichern können. Deshalb werden sie in der Regel für Screenshots, Diagramme und Icons verwendet.

![](https://pbs.twimg.com/media/EPd-Lp1WAAYYBzs?format=png&name=large)

### Nur-lesen Modus ###
Die Konvertierung von RAW-Formaten benötigt sehr viel Rechenzeit, weshalb normalerweise die dann erzeugten JPEG-Dateien neben den RAW-Dateien für die zukünftige Verwendung abgespeichert werden. Im *nur-lesen Modus* schreibt PhotoPrism jedoch keine Daten in deine Bildverzeichnisse. Da es nicht sinnvoll wäre die konvertierten Daten im Arbeitsspeicher oder einem temporären Verzeichnis abzulegen, ist die automatische Konvertierung im *nur-lesen Modus* deaktviert.

Wenn du dir unsicher bist, ob du neben deinen RAW-Files auch JPEG-Dateien abspeichern solltest, solltest du bedenken, dass es in 20 Jahren bestimmt einen JPEG-Viewer geben wird. Die Unterstützung von einem proprietären RAW-File ist jedoch nicht garantiert.
Nutzern die PhotoPrism als [Fotobetrachter (im *nur-lesen Modus*)](https://github.com/photoprism/photoprism/issues/189) nutzen wollen, empfehlen wir die JPEGs manuell oder mithilfe eines anderen Tools zu erzeugen.

Wie PhotoPrism mit der automatischen Konvertierung im *nur-lesen Modus* in Zukunft umgehen wird, ist noch nicht abschließend entschieden. Vielleicht gibt es eine Möglichkeit, mit akzeptablem Rechenaufwand und Qualität RAW-Bilder automatisch zu konvertieren. Diese könnten dann in einen Ordner `cached/converted` abgelegt werden. Von da aus könnten sie dann in das Verzeichnis mit den Originalen kopiert/verschoben werden. Was hälst du davon? Wir freuen uns auf dein Feedback!