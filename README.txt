Liebe Ina,

das hier ist der Erste Funktionale Prototyp mit dem du für derzeit 3Personen eine Performance mit 2 verschiedenen Icons bauen kannst.
Bitte schreib alles auf, was du später anders haben möchtest, die meisten visuellen Sachen wie ( Ziellinienposition, Icon Position nebeneinader, Icongröße) sind sehr schnell
änderbar. Die meisten Nutzungsarten (weitere Person hinzufügen, Glows und Fades der Icons, Videointegration, ...) würden teilweise sehr lange brauchen also solltest du dir darüber 
zuerst klar werden was fehlt/noch rein muss. Damit nich am Ende noch sehr Viel geändert werden muss.
Jetzt ist also die Zeit mal bisl rumzuspielen, zu sagen was noch rein muss und dann kann ich auch besser die Zeit abschätzen.
Der Prototyp hat mich jetz so 5Stunden gebraucht.

Grüße Michbeck.

---------------

Falls du nicht in der Lage sein solltest irgend etwas außer einer grauen Fläche zu sehen, dann folge bitte den Anweisungen im Link[1] oder
leg die beiden Dateien auf deinen Webserver, dann sollte das gehen.

[1]http://stackoverflow.com/questions/8449716/cross-origin-requests-are-only-supported-for-http-but-its-not-cross-domain
da beschreibt "Smokefoot" wie man in OSX den Chrome Browser mit Zugriff für Offlinedateien ausstattet.
"try (re-type the dashes if you copy paste):
open -a 'Google Chrome' --args -allow-file-access-from-files"

---------------

Die "beats" sind in der mytext.xml datei geschrieben. Diese kannst du einfach ändern um weiter beats hinzuzufügen oder das timing von meinen Beispielbeats zu ändern.

ein beat ist wie folgt definiert:
	<beat time="5500" group="1" icon="1"/>

time: bestimmt in MilliSekunden wann der Beat aufleuchten wird nach dem aufrufen der Webseite ( 5500ms = 5,5sek)
group: definiert für wen dieser Beat gilt
	   P1 P2 P3
group1  x  x  x
group2  x    
group3     x   
group4        x
group5  x  x   
group6     x  x
group7  x     x

icon: definiert ob Quadrat oder Kreis, du kannst hier auch schon "3","4",... usw nutzen wenn du schon richtig beats bauen willst da denk ich mir später noch "icons" für aus oder wir designen noch was zusammen.

---------------