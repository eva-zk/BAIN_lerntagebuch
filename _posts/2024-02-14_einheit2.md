---
title: "Einheit 2: Technische Grundlagen 2/2"
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

**Man sollte meinen, dass es einfach ist, aber ... (Fehlerbeispiele)**
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

**Herausforderungen beim Erstellen eines Tagesbuchs**

- Neue Plattform, aber die gegebenen Anweisungen haben mir einen grossartigen Start ermöglicht.
- Ich habe Schwierigkeiten, das Format zu verstehen. Soll ich einfach einen neuen Absatz verwenden (es als Text behandeln) oder ist es besser, Tags wie <br> zu verwenden?
- Beim Versuch, Bilder und Screenshots zu den Posts hinzuzufügen, hatte ich einige Schwierigkeiten. Ich wollte nicht, dass Bilder im gleichen Folder wie Posts sind, weil ich mir vorstellen kann, dass es nach einer Weile zu Unordnung führen kann. Also habe ich einen Ordner "images" mit einer leeren .md-Datei als Platzhalter erstellt und dann die Bilder hochgeladen. Es hat nicht funktioniert, obwohl ich den Pfad zu den hochgeladenen Bildern hinzugefügt habe.

Dann habe ich versucht:
- Den Pfad zu ändern //, /, /... (alles ausprobiert, auch wenn das, was ich wusste, keinen Sinn macht und nicht funktioniert).
- /master zum Pfad hinzufügen.
- Überprüfen, ob die hinzugefügten Bilder mit png oder PNG enden (war ok).
- Überprüfen, ob die Bildnamen gleich geschrieben sind (Gross- und Kleinschreibung beachten) (war ok, Um sicher zu gehen, habe ich die Leerzeichen in den Namen gelöscht und sie in "_" geändert).

Ich kam an einen Punkt, an dem ich die Bilder bereits in der Vorschau sehen konnte, aber auf der Website wurde immer noch die alternative Beschreibung verwendet. Dann habe ich eine Quelle gefunden, die die Lösung bereitstellte:<a href="https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html">tomcam adding images</a>.

Also fügte ich schliesslich die Ordner docs/assets/images hinzu und änderte die Pfadangaben. Der eindeutige Nachteil dieses Prozesses waren eine Menge E-Mails und etwa 70 (!) Commits mit demselben Namen (ich war zu faul, ihn zu ändern), die keinen Zweck erfüllten. Sie waren nur das Ergebnis davon, dass ich verschiedene Dinge ausprobierte, in der Hoffnung, sie würden funktionieren.

Es ist klar, dass dies nicht die richtige Art ist, GitHub zu nutzen, und ich kann mir vorstellen, dass, wenn ich in einem Team arbeiten würde, andere sich über mein Verhalten ärgern würden.

Ich war auch etwas frustriert, weil ich die Änderungen auf der Website nicht erzwingen konnte. Ich habe einfach in den settings/pages Seitenansicht auf Aktualisieren geklickt, bis ich sagte, dass die letzte deployment "now" war, und dann das Tagebuch selbst aktualisiert, um zu sehen, ob das, was ich getan habe, eine Wirkung hatte. 

Ich werde dies dem Lernprozess zuschreiben. Ich bin froh, dass ich dabei geblieben bin, denn dadurch habe ich eine einfache Möglichkeit entdeckt, Bilder zu meinem Tagebuch hinzuzufügen, die ich sicher auch in den folgenden Beiträgen verwenden kann.
