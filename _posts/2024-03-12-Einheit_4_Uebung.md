---
title: "Aufgabe zur Einheit 4: Vergleich von ArchivesSpace und Access to Memory (AtoM)"
date: 2024-03-12
---
Weitere Informationen erhältst Du über den Link: 
<a href="https://pad.gwdg.de/JmDfo4JOSQuF12mGPmm7IA#">BAIN HedgeDoc</a>.

**ArchivesSpace (AS) vs Access to Memory (AtoM)**

**1 Was ich gemacht habe:**
- Erhebung von Basisdaten über die beiden Open-Source-Anwendungen
- durchzuklicken (alle Optionen rechts und links vom Suchfeld)
- "accession record", "place" und "subject" hinzugefügt

**2 Beobachtungen:**

- Anstatt den Mauszeiger zu bewegen, fügt AtoM einfach Informationen neben dem Feld ein, in das man Daten eingeben muss. Das macht den ganzen Prozess ein wenig entspannter, keine zusätzlichen Fenster, die wie Pop-ups aussehen, nur einfache Textfelder. Der Nachteil ist jedoch, dass man mehr Platz braucht und daher mehr scrollen muss. Ich denke auch, dass es weniger übersichtlich ist, weil es schwieriger ist, zwischen dem Namen/Titel des Feldes und den Beschreibungen zu unterscheiden.
- AS ändert das angegebene Datum tatsächlich in der gewünschten Form (ich schrieb 20/01/2020 und es wurde beim Speichern in J-M-T geändert). AtoM scheint dies nicht zu tun.
- Es scheint, dass AS mehr Felder bietet, was mehr Möglichkeiten für eine detaillierte Archivierung und Speicherung von Informationen über Akzessionen bedeutet. Aber in AtoM kann man über "Admin" zusätzliche Änderungen in den Feldern vornehmen, so dass ich mir nicht sicher bin, wie gross der Unterschied ist.
- Die AtoM-Schnittstelle bietet mehrere Sprachen: Englisch, Französisch, Spanisch, Niederländisch, Portugiesisch, das ist ein Plus.
- AtoM: Mir gefällt, dass man Institutionen, Artikel usw. in die Zwischenablage einfügen kann, um sie schnell und einfach zugänglich zu machen. Leider muss man noch den richtigen Entitätstyp auswählen, sonst bekommt man keine Ergebnisse (siehe unter).
<img src="/BAIN_lerntagebuch/docs/assets/images/7_Screenshot_2024-03-25.png" alt="Screenshot Ein Artikel Zwischenablage">

**3 Probleme/Lernerfahrungen:**

1) Ich habe zwei Akzessionsdatensätze über die Demo-Seite von AtoM erstellt. 
- Beim ersten füllte ich nur 4 Informationen aus (Akzessionsnummer, Akquisitionsdatum, unmittelbare Soruce der Akquisition und Standortinformationen) und konnte ihn speichern und wiederfinden, als ich auf "Verwalten" klickte und später einen Titel hinzufügte und ihn erneut speichern konnte.
- Beim zweiten Versuch füllte ich alle Felder aus (Basisinformationen, Bereich Spender/übergebende Stelle, Verwaltungsbereich und Bereich Archivbeschreibung). Als ich auf "Erstellen" klickte, passierte nichts. Ich habe es mehrere Male versucht. Ich habe auch versucht, einige Felder zu ändern, ohne Erfolg. Ich habe auch keine Fehlermeldung erhalten, also bin ich mir nicht sicher, was schief gelaufen ist.

2) CSV-Datei importieren. Ich wählte eine Liste mit den Lesegewohnheiten von Personen, die wir in einem anderen Fach verwendet haben. Ich bekam die Fehlermeldung "Unable to complete file import. Die Datei konnte nicht nach /mnt/st-atom/demo2/atom-494a8b17046bcf5a84ca3b33395286a0ed7ae1c8/uploads/tmp" verschoben werden. Ich habe versucht, den Typ und andere Eigenschaften zu ändern, aber ich hatte immer noch keinen Erfolg.
Ich habe auch versucht, die XML-Datei mit The Prudence Wayland-Smith Papers von EADIVA zu importieren, erhielt aber die gleiche Fehlermeldung. Schliesslich fand ich dies:

“PLEASE NOTE: For security reasons, uploads have been disabled on this site. If you would like to test uploads, we suggest you consider setting up a local testing environment, using our Vagrant box - more information can be found on our website in the Administrator's manual - look for "Using Vagrant.""
(<a href="https://demo.accesstomemory.org/help">Quelle</a>)
Ich vermute also, dass dies einfach nicht funktionieren soll, deswegen ist es schwierig, dies zu überprüfen/testen/anschauen.

3) Nach ca. 20 Minuten Nutzung musste ich mich erneut anmelden. Es könnte daran liegen, dass die Verbindung unterbrochen wurde oder dass in diesem Moment Dinge gelöscht/neu angelegt wurden. Mein Eintrag wurde gelöscht, 2 andere, die vor meinem Eintrag erstellt wurden, wurden nicht gelöscht, was sehr interessant ist.

4) Ich konnte den "Job history" als csv-Datei exportieren. Über das Suchfeld fand ich einen Eintrag und konnte das Dublin Core 1.1 XML-Dateiformat und EAD 2002 XML einsehen. 

5) Die Option neben einer Demo "Durchsuchen" verstehe ich nicht ganz. Ich bin mir nicht sicher, wie diese Elemente hinzugefügt wurden, was ist die Logik, die Hierarchie. Es ist schön, dass man nach Berufen von Personen suchen kann. 

6) Die Suchfunktion hat noch ein weiteres Problem (oder ist es ein Feature?): Ich habe Ljubljana als Ort hinzugefügt. Als ich in ein Suchfeld ging und begann, Ljubljana zu schreiben, wurde bei "Lju" bereits Ljubljana als Ort vorgeschlagen und ich konnte darauf klicken. Wenn ich aber Ljubljana (ganze Wort)in das Suchfeld schrieb und dann die Eingabetaste drückte, erhielt ich "keine Ergebnisse" (siehe unter).
   
<img src="/BAIN_lerntagebuch/docs/assets/images/8_Screenshot_2024-03-25.png" alt="Screenshot One item Clipboard">

<img src="/BAIN_lerntagebuch/docs/assets/images/9_Screenshot_2024-03-25.png" alt="Screenshot One item Clipboard">
