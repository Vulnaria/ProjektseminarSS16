Projektseminar der Computerlinguistik der Universität Trier im Sommersemester 2016. 
Die Idee ist es, mittels eines lernenden Algorithmus ein Tool zur Textklassifizierung zu implementieren. 
########################################################################################################
Es gibt diverse Websites, die kostenlose Ebooks zur Verfügung stellen
bookrix.de erfordert keine Anmeldung, die Bücher sind allerdings von Laien geschrieben.
Ihren Zweck werden sie wahrscheinlich trotzdem erfüllen.
In den AGBs habe ich auch nichts gefunden, das die Nutzung der Texte zu nicht-gewerblichen Zwecken untersagt.
Man kann die Einträge nach Genre filtern und nach Seitenzahl sortieren.
Wenn ihr weitere gute Quellen findet, fügt sie in diese README ein und sendet ein Pull-Request.
########################################################################################################
http://www.bookrix.de/
########################################################################################################  
Calibre ist eine mächtiges Tool-Sammlung zur Verwaltung von diversen Ebook-Formaten.
Es stellt unter anderem das Tool ebook-convert zur Verfügung, mithilfe dessen man Ebooks in andere Formate
konvertieren kann.
https://calibre-ebook.com/
########################################################################################################
Linux: ebook-convert input.epub output.txt

Wenn ihr meherere Dateien in einem Verzeichnis konvertieren wollt, geht das folgendermaßen:
for f in *.epub; do ebook-convert "$f" "${f%.epub}.txt"; done

If you've installed calibre on OS X, the command line tool can be found here: /Applications/calibre.app/Contents/MacOS/ebook-convert

Windows ist doof!
######################################################################################################## 
Forkt und klont euch das Repositorium, fügt eure Ordner ein, und sendet Pull-Requests für eure commits.
######################################################################################################## 
