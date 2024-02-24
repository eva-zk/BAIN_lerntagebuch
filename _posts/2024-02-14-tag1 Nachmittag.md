---
title: "Einheit 1.2: Technische Grundlagen 2/2 (Nachmittag)"
date: 2024-02-14
---
Weitere Informationen erhältst du über den Link: <a href="https://pad.gwdg.de/H-dlBlKaS9-xqX0ZH8fqcw#">BAIN HedgeDoc</a>
Ich werde mich hier auf meine Erfahrungen konzentrieren. 

**Überblick** Was haben wir getan/besprochen?

**1) GitHub**
   - Timeout von Codespaces auf 240 Minuten erhöhen.

**2) Grundlagen der Unix Shell** (<a href="https://librarycarpentry.org/lc-shell/02-navigating-the-filesystem.html">Library Carpentry Lesson 2: Navigating the filesystem</a>)

(Wieder-)erlernte Befehle
- pwd (wo bin ich)
- ls (Ausdruck des gesamten Inhalts des aktuellen Verzeichnisses)
- ls -l und ls -lh
- cd, cd .. (Verzeichniswechsel)

Keine grossen Probleme. Wir haben ähnliche Dinge getan, als wir die Grundlagen der Linux-Shell lernten und als ich Terminal auf dem Mac benutzten musste.

Was ist eine Shell? Aus _Library Carpentry_:
<br>"The shell is a program that is usually launched on your computer much in the way you would start any other program."
<br>"It /Shell/ is the primary interface used on Linux and Unix-based systems, such as macOS, and can be installed optionally on other operating systems such as Windows." <a href="https://librarycarpentry.org/lc-shell/01-intro-shell.html">Quelle</a>

***TO-DOs:*** Ich bin mir immer noch nicht sicher, ob ich verstehe, was Shell im Verbund mit Codespace ist. Unterschiede zwischen Shell, (command-line) Interface und einem Programm.

Das von _Geeks for Geeks_ ist ziemlich hilfreich: 
"Ein Terminal ist ein Programm, mit dem Sie eine Shell ausführen können." (<a href="https://www.geeksforgeeks.org/difference-between-terminal-console-shell-and-command-line/">Quelle</a>)

Das Terminal von Codespace fungiert also als ... nun ja, Terminal. Aber was funktioniert als Shell?

Ich erinnere mich, etwas Ähnliches wie dieses Diagramm gesehen zu haben:
<img src="/BAIN_lerntagebuch/docs/assets/images/architecture_of_linux_system.png" alt="Architektur eines Linux-systems">

<a href="https://www.javatpoint.com/architecture-of-linux">Quelle</a>

 Und es macht irgendwie Sinn, wenn ich an meinem eigenen Computer arbeite. Aber wenn ich GitHub&Codespace benutze, ist mein Gehirn immer noch vernebelt, wenn ich darüber nachdenke, was der Kernel und die Shell sind, wo sie sind und wie sie funktionieren.

**3) Grundlagen der Unix Shell** (<a href="https://librarycarpentry.org/lc-shell/03-working-with-files-and-folders.html">Library Carpentry Lesson 3: Working with files and directories</a>)
   
(Wieder-)erlernte Befehle: 

- mkdir (Verzeichnisse erstellen)
- tab (Anfang eintippen und dann Tabulator-Taste drücken, um die Finger zu schonen und weniger Zeit zu verlieren)
- cat (wenn man längere Texte im Vorbeigehen mag)
- head, tail + "Dateiname" + Anzahl der Zeilen
- head *.txt (um die Köpfe aller Dateien mit dieser Endung zu erhalten)
- ? findet ein Zeichen, * 0 oder mehr Zeichen
- Kopieren, Umbenennen, Verschieben von Dateien in ein Verzeichnis
- history, Pfeil nach oben drücken, ctrl + r, ctrl + c zum Speichern der History
- Echo

**Man sollte meinen, dass es einfach ist, aber ... (Fehlerbeispiele**
<br>**1**<br>
<img src="/BAIN_lerntagebuch/docs/assets/images/Screenshot_2024-02-16_(Zeilen).png" alt="Screenshot Zeigen erste 20 Zeilen">
(Wie man es nicht machen sollte)
<br>**2**<br>
Wie komme ich da raus? 
<img src="/BAIN_lerntagebuch/docs/assets/images/2_Screenshot_2024-02-20.png" alt="Screenshot im Text steckengeblieben">
(^ steht für die Steuerungstaste)
<br>**3**<br>
Beim Lernen der Pythongrundlagen hatte ich immer Schwierigkeiten zu verstehen, wann Buchstaben als Beispiel verwendet werden und wann sie Teil eines Befehls sind. Ähnlich hier, kann ich nur NAME verwenden oder kann ich auch etwas anderes verwenden? Antwort: Ich kann, aber vergiss nicht, dass du bei der Verwendung von Nicht-Grossbuchstaben vorsichtig sein musst.
<img src="/BAIN_lerntagebuch/docs/assets/images/1_Screenshot_2024-02-20.png" alt="Screenshot Echo Übung">

**4)GitHub**
-Demo: Typischer Git Workflow
- Fork erstellen
- Änderung vornehmen und committen
- Pull Request anlegen
- Tagesbuch starten

