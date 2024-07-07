---
title: "Einheit 9: Suchmaschinen und Discovery-Systeme B"
date: 2024-06-03
---
Weitere Informationen erhältst Du über den Link: 
<a href="https://pad.gwdg.de/5jn060c8RDC6WukTIuP5RQ#">BAIN HedgeDoc</a>

**1 Gruppenarbeit Datenintegration**

Wir importieren Daten in VuFind und beobachten, was passiert und wie die Ergebnisse aussehen. 
Durch den Anbieter Digital Ocean wurde von snapshot VM erstellt und diese wurde für Gruppenarbeit bereit gemacht. Ich war ein Teil der Gruppe 3: mit June und Nina. 

- Der Zugriff auf den Server erfolgte über protokol SSH.
- Login, gegebener Befehl ssh root@ gefolgt von unserer Servernummer.
- Dann haben wir das Passwort eingegeben.
- Es folgt der Befehl um Solr zu starten. 
- Die Suchfunktion in VuFind sollte nun funktionieren. Und das tat es auch. 
- Wir haben die Testdaten gelöscht (stoppen, löschen, neu starten) und andere Daten importiert.
- Wir haben in 2 anderen Fächern etwas über den Texteditor Nano gelernt, aber wie June hatte auch ich Mühe, mir die wichtigen Befehle zu merken. Diese Liste war hilfreich:

<img src="/BAIN_lerntagebuch/docs/assets/images/13_Screenshot_2024_06_3.png" alt="Nano Befehle">

Wir haben Daten aus ArchivesSpace und DSpace importiert.

<img src="/BAIN_lerntagebuch/docs/assets/images/14_Screenshot_2024_06_3.png" alt="VuFind">

Der ganze Prozess war erstaunlich einfach. Ich weiss, dass wir nur winzige Steine auf riesige Gebäude setzen, aber mit ein paar Zeilen haben wir sozusagen eine neue Welt geschaffen.

**2 Gruppenarbeit VuFind-Konfiguration**

Um Änderungen zu vermeiden, wenn Software aktualisiert wird, kann man Configuration von Daten lokal speichern. Diese werden dann auch durch ein Update nicht verändert. VuFind liest zuerst lokal, und wenn nichts gefunden wird, geht von local/config(vufind zu config/vufind. Was von mir und meinen Klassenkameraden gemacht wurde:
- Facetten zu Links gebracht.
- Designänderungen
- Browser-Fenster den Titel geändert
- Facetten geändert (eng. sprachlichen Text)

**3 Zusammenhang mit anderem System, HAAB**

- Discoverysystem basiert auch auf VuFind. Einfache Installation, wenig Design. Hier auch Facetten auf der linken Seite.
- Suche, erweiterte Suche.
- Viele Online-Quellen, Filter wurden gesendet und Ergebnisse endeten bei 4 Millionen. 
- Extern wurde Solr verwendet.
- Wenn man ein Buch findet und es ausleihen will, muss man sehen können, ob es verfügbar ist. Die Informationen müssen live geliefert werden. Ausserdem muss das Bibliothekssystem damit verbunden sein, ein Login muss möglich sein, damit z.B. auch Bücher ausgeliehen werden können.
- Discovery-System sollte auch Liefersystem unterstützen. Direkter Link zu pdf oder so für ebooks, damit es für Benutzer einfach ist.

**4 Marktüberblick Discovery-Systeme**

- Ex Libris mit Software Primo (auch bei Swisscovery) = technologischer Marktführer
- SLP
- Frage der Benutzerverfolgung. Punkt: man braucht alternative Systeme +. Gegen Monopol

<sup>Bemerkung vom Ende des Semesters:</sup> _ Dies war die herausforderndste Vorlesung. Ich hatte Mühe, Notizen zu machen und zu beobachten, was der Dozent und die Klassenkameraden diskutierten und machten. Ich wollte meine Gruppe nicht im Stich lassen, also habe ich meine Notizen zur Seite gelegt. In der Pause und nach der Vorlesung habe ich versucht, Anpassungen meiner Notizen zu machen, aber sie waren leider immer noch unbrauchbar. All dies führte zu einem Tagebucheintrag, den ich am schlimmsten finde.
