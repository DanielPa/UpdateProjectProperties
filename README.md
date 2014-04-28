UpdateProjectProperties
=======================

Eplan Script liest Projekteigenschaften aus angegebenem Projekt und setzt sie im geöffneten Projekt.


Kurzanleitung:
- Das Projekt aus welchem gelesen werden soll muss in der UpdateProjectProps.cs eingetragen sein (Zeile 31 musterPrjPath). 
- Die Datei UpdateProjectProps.cs muss in Eplan geladen werden. 
- Die Datei PropertySettings.xml muss im selben Verzeichnis liegen wie die UpdateProjectProps.cs.
- In der Datei PropertySettings.xml werden die Eplan IDs der Projekteigenschaften mit Index eingetragen 
  deren Wert aktualisiert werden soll.
- Es sind noch keine oder wenige Exceptions behandel. Es ist möglich, dass der vollständige Pfad zur 
  PropertySettings.xml angegeben werden muss. 
