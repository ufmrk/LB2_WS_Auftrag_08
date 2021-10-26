# Werkstattauftrag W08 OwnCloud

## Autoren, Versionierung des Dokumentes

   • Autoren: Altin Maliqaj & Patrik Pribela
   
   • Mail: altin.maliqaj@edu.tbz.ch | patrik.pribela@edu.tbz.ch

   • Version: 1.0 (Vollständige Edition)
- - -
## Einführung
In der folgenden Dokumentation ist die Installation, sowie Konfiguration samt allen Anforderungen von OwnCloud dokumentiert.
Alle Kommandos, welche im Terminal des Raspberry Pis ausgeführt werden müssen, sind in der folgenden [Abbildung](../img/cmd.png) einsehbar.

   ### Beschreibung: Welche Funktionen wird der Service erfüllen
   OwnCloud ist Ihre eine eigene private Cloud zum Austausch von Dateien. Die wichtigsten Features und Funktionen von OwnCloud sind die Bereitstellung von Clients, Synchronisation, ActiveDirectory-Anbindung, Verschlüsselung und viele andere. Es wird angestrebt diese auf allen Plattformen betreiben zu können.
   ### Vorgesehener Zeitaufwand für die Realisierung
   Der Zeitaufwand beträgt unserer Schätzung nach 60 Minuten im Durchschnitt. Die Schätzung kann wegen Hardware-Build, Software-Version und Netzwerkanbindung abweichen.
   ### Stolpersteine
   Bei folgendem Projekt können mehrere **Stolpersteine** aufkommen, welche uns, sowie anschliessend Sie an einer erfolgreichen Umsetzung hindern können oder diese zumindest erschweren können. Um den gägnigsten **Stolpersteinen** aus dem Weg gehen zu können, wurden diese aufgelistet.<br><br>
- - -
## Benötigte Hard- und Software
   ### Hardware (Materialliste, Funktionalität)
• Raspberry Pi<br>
• Monitor + Peripherie (Maus und Tastatur)<br>
   ### Software (Anforderungen, Firmware, OS-Image, ergänzende SW-Packages, Abhängigkeiten, Funktionalität)
• Neuste OS Version von Raspberry PI inkl. Updates<br>
• Neuste Version von OwnCloud als Image<br>
- - -
## Installationsanleitung (Lösungsweg)
### Raspberry Pi Betriebssystem updaten<br>
Nach dem Sie den Raspi mit SD Karte von der Lehrperson erhalten haben, führen Sie als erstes die Betriebssystem Updates aus. So können Sie jegliche veraltete Systemfehler meiden. Dies machen Sie mit folgendem Befehl im Terminal:<br>
`sudo apt-get update`<br>
`sudo apt-get upgrade`
- - -
## Qualitaetskontrolle (Pruefen der Funktionalitaet mit Ablauf von Kommandos und entsprechenden Outputs)
- - -
## Error-Handling
Falls die Installation am Ende nicht ordnungsgemäss funktioniert, kann dies mehrere Gründe haben. Weiter unten finden Sie die gängigsten Fehler aufgelistet.
### Allgemeine Schritte vor weiterem Debugging zwingend ausführen
• Raspberry Pi neu starten
• Prüfen, ob der Dienst der Anwendung läuft
• Netzwerkverbindung prüfen
• Restriktionen im Netzwerk ausschliessen
- - -
## Quellen
https://www.tecmint.com/18-tar-command-examples-in-linux/<br>
https://sourceforge.net/projects/webadmin/files/webmin/
http://doxfer.webmin.com/Webmin/Main_Page
