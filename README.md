# Controller-Updater
AquaGrow Updater und Aktuelle Software Versionen

#AquaGrow Updater


Die Aquarow Controller verfügen über die Möglichkeit eines Software Updates per serieller Schnittstelle.
Hierfür sind auf allen Platinen entweder direkt ein USB Port oder ein Anschluss für den AquaGrow Programmer. 
  
An diesen Ports kann der AquaGrow Programmer direkt angeschlossen werden oder über Dupont Kabel angeschlossen werden.
Danach kann über die AquaGrow Update Software der neue Programmcode aufgespielt werden.

Falls Ihr zum ersten mal einen Programmer anschließt müsst Ihr die Treiber Software installieren. Diese findet Ihr im Ordner „Driver“. Wer nicht weiß wie man Treiber „per Hand“ installiert kann dies einfach in eine Suchmaschine seiner Wahl unter „Treiber manuell installieren“ suchen. Für andere UART Adapter auf Basis eines FTDI Chips oder ähnlichem bitte die Treiber selbst suchen und installieren.
Danach könnt Ihr unter Systemsteuerung/Gerätemanager den Programmer unter COM-Ports sehen. Nun müsst Ihr die Software starten und gegebenenfalls bestätigen das Änderungen am Computer vorgenommen werden dürfen. Danach seht Ihr die Programmoberfläche und könnt auswählen welche Platine geflashed werden soll. 
 
Als nächstes steht die Auswahl des Com-Ports an. Es werden alle auf dem PC Grade aktiven ComPorts angezeigt. Solltet Ihr Euch also nicht sicher sein welchen Ihr auswählen müsst, zieht den Programmer ab, wartet eine Sekunde und der der dann verschwunden ist, dies ist der Richtige. 
 
Über den Button „Select File“ könnt Ihr die neue Programmsoftware auswählen. Hierbei gibt es zwei verschiedene Varianten: Hex-Files sind zum Updaten von Chips, basierend auf dem Atmega da. Bin Files werden vom AquaFi Controller verwendet.
 
Nach auswahl des richtigen Software Files könnt Ihr über Flash Controller das Update starten.
 
An dieser Stelle kommt auch noch mal eine Abfrage die euch darauf hinweist. An diesem Zeitpunkt solltet Ihr auch andere Schritte durchführen die nötig sind, so zum Beispiel Reset drücken beim AquaFi.
 
Nachdem der Update Vorgang gestartet wurde passiert nichts bis die Software fertig geschrieben wurde und validiert ist. Dann kommt wieder eine Meldung und Ihr könnt die Software schließen. Solltet Ihr eine Debug Version bekommen haben um einen bestimmten Fehler zu analysieren, dann besteht über den Butten „Debug Output“ die Möglichkeit sich SourceCode Debug Infos anzeigen zu lassen.
 
Bitte vergesst nach dem Update des AquaFi Controllers nicht den Jumper wieder abzuziehen.
