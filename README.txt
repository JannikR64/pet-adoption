Schreibe "doc für den Startercode

Einstellungen in VS-Code anpassen "Strg" + ","  
Dann oben rechts auf Open Settings

	{
	    "security.workspace.trust.untrustedFiles": "open",
	    "terminal.integrated.defaultProfile.windows": "Command Prompt",
	    "editor.columnSelection": true,
	    "window.zoomLevel": -1,  <- Zoom level
	    "editor.fontSize": 18,  	<- Schriftgröße
	    "editor.formatOnSave": true, 	<- automatisches Einrücken
	   "editor.tabSize": 2,
 	   "breadcrumbs.enabled": false,
	    "editor.minimap.enabled": false,
	}

Px in rem umrechnen 100px / 16 = 6.25rem

Positionierung von Elementen:

Mit diesen Parametern, kann man die Position des Elements einstellen:

 	   position: absolute;
	    top: -365px;
	    left: -123px;


Möchte man, dass diese Parameter passend an ein anderes Element ausgerichtet sind, muss man folgendes Parameter in das übergeordnete Element schreiben:

  	  position: relative;


Um Elemente passend im Fenster anzuzeigen, ohne dass Sie über den Rand ragen muss man bei dem umklammernden div folgendes eingeben:

	overflow: hidden;

Elemente in den Vordergrund rücken:

Je höher der angegebene z-index im Css ist, desto weiter vorne liegt das Element.

  	  z-index: 2;
	 position: relative;

Beim erstellen eines div Elements kann man "TAB" drücken und die tags werden automatisch generiert.

schreibt man div.klassenname und drückt dann "TAB" hat man sogar eine Klasse dabei.

"STRG" + "J" öffnen der command zeile
"git init" erstellt unsichtbaren .git ordner um den zielordner zu definieren

git config --global user.name "Jannik"
git config --global user.email "jannik.regenberg@gmail.com" <- Benutzer definieren

"git add -A" wählt alles aus 
"git commit -m "Our first commit"" loggin in files/speichern. 

Für erneutes speichern sollte man beide Schritte nochmal durchführen

git checkout -- .  <-- Macht Änderungen rückgängig. Greift auf den letzten Speicherzustand zurück.

ssh-keygen -t ed25519 -C "jannik.regenberg@gmail.com" <-- SSh Key für github generieren