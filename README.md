## IMCM-3BHK

## Einleitung

## Markdown

_Markdown_ist eine Auszeichnungssprache (Markup Language_). Mit Auszeichnungssprachen wird Text strukturiert. Einige Markup-Languages sind z.B.:

-HTML (_Hypertext Markup Language_)
-XML (_Extensible Markup Language_)
-MD  (_Markdown_)
-YAML (_YAML Ain't Markup Language)

Markdown ist heutzutage eine der beliebtesten Auszeichnungssprachen. Wenn eine README.md-Datei in eine GitHub-Repository vorhanden ist, wird diese automatisch auf der Startseite des Repositories angezeigt. Die README.md-Datei ist also die erste Anlaufstelle für alle, die sich über das Projekt infomieren möchten.

Um ein Git-Repository zu erstellen, sind folgende Schritte notwendig:

- im gewünschten Verzeichnis im Terminal (bzw. CLI - _Command Line Interface) den Befehl ' git init' ausführen ' code'.
 

> # Einschub zur Installation von Git:##
> Falls von der Eingabe von 'git init' die Meldung _"command not found"_ erscheint, ist Git nicht installiert und der Befehl wird nicht erkannt. Bei der Installation wird der Befehl der Umgebungsvariable **PATH** hinzugefügt. Darin sind die Bezeichnungen aller Programme erhalten, die im Terminal aufgerufen werden können. 

dann in Github-Desktop das lokale Repository hinzufügen(*File > Add Local Repository...*) - nun kann über die Schaltflächen **Commit to master** und **Push origin**  der aktuelle Stand des Projekts in das Github-Repository hochgeladen werden. 

## Statische und dynamische Websites

In den 1990er Jahren wurden Websites überwiegend statisch erstellt. Inhalte wurden als html-File auf einem Webserver hochgeladen. Bei jedem Aufruf der Website wurde das html-File vom Server an den Browser des Nutzers übertragen. Die Inhalte waren also immer gleich, unabhängig davon, wer die Website aufrief. 


![Funktionsweise von statistischen Websites](image.png)

Die Abbildung zeigt die Funktionsweise von statischen Websites. Zuerst muss der Domain-Name über das Domain Name System (DMS) in die IP-Addresse des Webservers aufgelöst werden (Schritt 1 und 2 in der Abbildung.) Danach schickt der Client eine http-Anfrage an den entsprechenden Webserver und erhält von diesem eine http-Antwort, die üblicherweise zuerst die index.html enthält (Schritt 3 und 4).