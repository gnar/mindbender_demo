Zak McKracken and the Alien Rockstars - Techdemo.

Übersicht:

0. Einleitung
1. Anforderungen
2. Windows
3. Linux
4. Tastatur-Kommandos
5. Known Bugs
6. Kontakt

-------------------------------------------------------------------

0. Einleitung

Hallo und willkommen bei der Techdemo zu 
"Zak McKracken and the Alien Rockstars."

Mit dieser Techdemo wollen wir einen ersten FRÜHEN Eindruck über 
unsere selbst geschriebene Engine und dem kommenden Spiel geben.

Wie für eine Techdemo üblich muss noch nicht alles 100% stimmen und 
auch die Bedienung ist noch nicht immer optimal.

Für die Leute unter euch, die sich mehr für die programmiertechnischen
Details interessieren sind die Skripte für das Spiel unter 
/skripts zugänglich.

Ansonsten viel Spaß und eure Meinung bzw. Rückmeldungen
sind gerne unter http://www.zak2project.de/cgi-bin/forum.php
willkommen.

Bis dahin,
Euer ZMAR-Team

P.S.: Wir suchen übrigens immer fähige Leute, die uns bei der 
Vollendung des fertigen Spiels zur Hand gehen wollen.

-------------------------------------------------------------------

1. Anforderungen:

Betriebsystem:
Die Techdemo läuft sowohl unter Windows 2000/XP als
auch unter Linux. Die Techdemo funktioniert nicht (!!!)
unter Windows 95/98.

Mindest-Specificationen:
- Intel/AMD CPU 700MHz (i386)
- mind. 256 MByte RAM
- OpenGL-kompatible Grafikkarte 
- DirectX (windows) or Alsa(Linux) kompatible Soundkarte

Die Demo funktioniert sowohl mit 32-Bit als auch mit 64-Bit CPUs.

-------------------------------------------------------------------

2.Windows

Start: 
Doppelklick auf sushi.exe im Verzeichnis "zmar_techdemo".

Deinstallieren: 
Einfach das Verzeichnis "zmar_techdemo" löschen.

-------------------------------------------------------------------

3.Linux

Vorraussetzung: 
Die Techdemo benötigt zum Start Bibliotheken des ClanLib-Projects 
(http://www.clanlib.org/) ab der Version 0.7.8.

Falls die Clanlibs nicht installiert ist, sollte das Paket heruntergeladen
und installiert werden. Die Techdemo sucht dann im standart lib-Pfad 
(normalerweise /usr/lib) nach den entsprechenden shared libraries.

WICHTIG: Es ist zwingend notwendig dass die Clanlib mit der Option zur
unterstützung von OpenGL (./configure --enable-clanGL) kompiliert wird.

Das mitgelieferte Binary sushi_linux wurde unter Debian Linux kompiliert.
Sollte aber auch mit anderen Linux-Distributionen funktionieren.

Start: 
Im Verzeichnis "zmar_techdemo" den Befehl "./sushi_linux" eingeben.

Deinstallieren:
Einfach das Verzeichnis "zmar_techdemo" löschen.

-------------------------------------------------------------------

4. Tastatur-Commandos:

F4  - Startet das Spiel
F2  - Speichert das aktuelle Spiel als Quicksave
F3  - Lädt den letzten Quicksave
ESC - Bricht das Intro ab

-------------------------------------------------------------------

5. Known Bugs/Problems:

- Bei einem Umstieg von einer 32-Bit auf eine 64-Bit-CPU 
kommt es zu Problemen mit einem alten QuickSave-Spielstand.
Lösung: vorerst keine - von vorne spielen und den alten 
Spielstand mittels F2 Überschreiben

- In seltenen Einzelfällen kann es passieren, daß das Sprite kurzzeitig
nicht oder nur Unvollständig dargestellt wird. 
Lösung: Einfach einen Klick auf einen Ausgang in einen anderen Raum 
und das Spiel geht weiter

- Bei Quicksaves während des Intros und anschließenden einladen mittels 
Quickload stimmen danach die Lautstärken der Samples und Hintergrundmusik 
nicht mehr.
Lösung: Einfach nicht Quicksave/load im Intro benutzen (wer will das auch).

-------------------------------------------------------------------

6. Kontakt und weitere Informationen

Weitere Informationen findet man unter www.zak2project.de


-------------------------------------------------------------------
