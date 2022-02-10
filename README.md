# tgbbz1Base
Ein Projekt des TGBBZ1-SB welches als Grundlage für folgende Projekte der Schule dient.

Wie du deinen Code Pusht:

--> Git CheatSheet: https://education.github.com/git-cheat-sheet-education.pdf

Bitte beachte das Branching Concept
FeaturebranchXY -> Test -> main

Bitte nicht direkt in main Pushen!!
Lege dir einen Branch an für das Feature, dass du gerade entwicklest und pushe ihn nachdem du fertig bist in den test Branch.
Der Test Branch wird dan nach Abnahme vom Projektleiter in den Main Branch gepusht


Setup Backend:

1. Checke das Projekt aus in deiner IDE
2. Stelle sicher das du Django (Framework für unser Backend) installiert hast
3. Gehe mithilfe deines Terminals in den tgbbz1Base Odner in dem sich die manage.py Datei befindet
4. Bist du in diesem Ordner, gebe den Befehl " python manage.py runserver "
5. Gehe in deinem Browser auf die Adresse die dir im Terminal angezeigt wird.

Setup Fronend:
1. Das Projekt sollte nach dem Setup des Backends bereits ausgecheckt sein
2. Navigiere in den Odner tgbbz1-base-ui/tgbbz1-base-ui
3. Installiere dir mithilfe deines Terminals Node (JavaScript Laufzeitumgebung welche JS Code auserhalb des Browsers ausführen kann)
5. Installiere jetzt mithilfe von NPM 'yarn' (NPM= Node Package Manager, Yarn ist auch ein Package Manager aber schneller, besser, neuer...)
6. Führe jetzt den Befehl 'yarn install' aus
7. Führe jetzt den Befehl 'yarn start' aus
8. Jetzt sollte sich dein Browser mit dem UI des React development Servers geöffnet haben
