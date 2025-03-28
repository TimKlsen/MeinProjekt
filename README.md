# MeinProjekt
Einrichten des GitHub-Repositorys "MeinProjekt" :
Nachdem ich mich mit meinem Git Hub Account angemeldet habe, habe ich ein neues Repository mit dem Namen MeinProjekt erstellt. 

Erstellen eines SSH-Schlüssels:
Um die lokalen Daten mit den Befehlen zu pushen musste ich zu erst einen SSH Code generieren und diesen unter Einstellungen->SSH neuer SSH einfügen. Um den SSH Code zu generieren habe ich folgenden Code eingegeben:
C:/Windows/System32/OpenSSH/ssh-keygen.exe -t rsa -b 4096 -C "timkleinelsen@t-online.de" Danach habe ich den generierten Key online gespeichert.

Lokales Klonen/Konfigurieren von Git/Erstellen des initialen Commit:
Mit dem Befehl git clone git@github.com:DeinBenutzername/MeinProjekt.git habe ich dann das Repository geklont so das es lokal war. Danach habe ich das Repository mit dem Befehl
cd Mein Projekt
geöffnet und die Datei Main.py mit den Kommentar Initial Comment erstellt
git add main.py
git commit -m "Initialer Commit"

Erstellen des Feauture Bereich, Hinzufügen der neuen Datei:
Den Feature Branch habe ich mit 
git checkout -b feature
erstellt und anschließend die Datei database.py in den Ordner utils erstellt
git add utils/database.py
git commit -m "Neue Funktion hinzugefügt"
Mergen des feature Branch in Master Branch, Beheben des Auftretenden Fehler
Da es den Master Branch nicht gibt sondern nur den Main Branch habe ich einen checkout in den origin/main gemacht. Danach konnte ich auch den feature Branch mergen mit dem Befehl
git merge feauture



Die Bilder habe ich in einer Zip Datei hochgeladen dort sieht man den Code!

