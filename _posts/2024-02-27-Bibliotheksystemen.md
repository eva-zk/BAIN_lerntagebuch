---
title: "Einheit 1.2: Technische Grundlagen 2/2 (Nachmittag)"
date: 2024-02-14
---
Weitere Informationen erhältst du über den Link: <a href="https://pad.gwdg.de/H-dlBlKaS9-xqX0ZH8fqcw#">BAIN HedgeDoc</a>
Ich werde mich hier auf meine Erfahrungen konzentrieren. 

**Überblick** Was haben wir getan/besprochen?
**1) Retro, Fragen**
Lerntagebücher: Man kann seine eigenen Prioritäten setzen und das vertiefen, was man möchte (das ist eigentlich erwünscht). Aber man muss die Grundlagen der gesamten Vorlesungen abdecken, alle Lernihalte erwähnen (nicht nur eines der Unterkapitel).

**2) Metadatenstandards in Bibliotheken (MARC 21)**

Die Grundstruktur ist die gleiche geblieben und hat weiterhin Gültigkeit. 37 Aktualisierungen wurden vorgenommen, aber es handelt sich dabei eher um Ergänzungen als um grössere Änderungen. Die Struktur ist ziemlich gleich geblieben.

Feldnummern haben eine Bedeutung. Z.B. 245 "Titel" Erklärung

Es kann zu technischen Fehlern kommen, z.B.:
-	 wird ein Feld verwendet, das nicht existiert. 
-	ungerade Datumsangaben nach einem anderen Standard (z.B. TTMMJJJJ statt MMTJJJJ).

Was kann MARC noch nicht? /..???/

Dublin Core: schönes, kleines Format. 15 Felder namens Titel, Datum, Ersteller, Verlag, die auf der ersten Blick leichter zu verstehen sind. Das kann man gut mit MARC 21 vergleichen.

**Übung** Vergleich von Formaten Dublin Core (DC) vs MARC 21 (Marc)

Was sehe ich mir an? Mehrere Bücher. Es scheint auch einen Artikel dazwischen zu geben. 
Erste Eindrücke:

- Bei Marc sieht man die Art des Formats, bei DC ist es nicht so klar (record Schema).
- Bei Marc kann ich den Verlag sehen, aber der Titel und der Autor stehen weit darunter.
- Es scheint auch zwei Orte für den Verlag zu geben. Wahrscheinlich liegt es daran, dass es sich bei dem vorliegenden Buch um eine Übersetzung handelt.
- Bei Marc detailliert 505 und 520. DC nur ein Feld ... wie kann man das hier eintragen?

Weiter:

Keine Seitenzahlen bei DC, so dass Informationen verloren gehen, wenn wir von einem Format zum anderen wechseln. In diesem Sinne ist DC manchmal nicht gut genug und kann zu schlechteren Ergebnissen auch später bei der Recherche führen.

Marc hingegen ist spezifischer, bietet mehr Platz zum Speichern von Informationen, ist aber weniger modern /..???./.

Was wird häufiger verwendet, Marc oder DC? Marc ist eher spezifisch für Bibliotheken. DC wird auch von Google für die Auflistung von Websites, in Archiven usw. verwendet.

Seien Sie vorsichtig: 
-	Datenformat(e) vs Metadaten:
Wir verwenden Datenformat und Metadaten manchmal als Synonyme. Marc ist ein bibliographische Datenformat. Aber in diesem Fall ist in xml ein Dateiformat (Datenformat). Wenn wir also von Marc, DC sprechen, ist es besser, das Wort Metadatenstandard zu verwenden.
-	Datenformat vs Regelwerk:
Zusätzliche Regelwerke, die bei der Katalogisierung verwendet werden, wir müssen darauf achten, wie wir Informationen schreiben (Titel zum Beispiel). Es gibt internationale Unterschiede, Vorname, Nachname oder Nachname zuerst und dann Vorname. Datumsformat (USA vs EU). Um Fehler zu vermeiden, muss man wissen, welche Form benötigt wird = Regeln kennen und respektieren.

**3) Koha**

Website ansehen, gemeinsames Projekt.

Statistik: Wie gesund ist das Projekt? Wird es in 2 Jahren veraltet sein, weil niemand mehr daran arbeitet? Software-Evaluierung, einige nette Grafiken, die uns sagen, ob es sich lohnt, Ressourcen in das Erlernen der Nutzung und die Nutzung eines Open-Source-Produkts zu investieren. Nicht viele offene Projekte haben 20 Leute, die daran arbeiten, wie dieses hier.

Es gibt ein Handbuch, Kontakt mit der Gemeinschaft, so dass, wenn es etwas braucht, es getan wird. Die Dokumentation wird im Allgemeinen bei Open-Source-Projekten nicht so oft gepflegt wie bei kommerziellen Projekten. 

Vorteil von Koha ist, dass es viele Demo-Installationen gibt, die es uns ermöglichen, Zeit und Platz auf der Festplatte zu sparen.



**Übung**

Über Admin-Schnittstelle, umfangreiche Rechte, sog. Superlibrarian. Ansonsten werden einzelne Funktionen je nach Benutzertyp eingestellt.

Was ist mir aufgefallen, als ich einen Benutzer angelegt und versucht habe, ihm ein Buch auszuleihen? 

Es scheint sehr intuitiv zu sein, die Felder sind so beschrieben und aufgebaut, dass es Sinn macht. Die Dinge sind dort, wo ich sie erwarte, und das System reagiert schnell.

Ich würde mich fragen, wie schwierig es wäre, einen neuen Nutzertyp hinzuzufügen, wenn wir jemanden haben, der halbtags arbeitet, aber auch Student ist, oder halb im Ruhestand ... Und ob jemand, der zu einem bestimmten Nutzertyp gehört, die Nutzung bestimmter Medien einschränken würde (keine Erwachsenenbücher für Kinder).

Mir ist auch aufgefallen, dass einige meiner früheren Suchen bereits vorhanden waren, obwohl ich Koha zum ersten Mal benutze. Es wäre also interessant zu wissen, ob dies erwünscht ist, da es zu peinlichen Situationen führen kann.

<img src="/BAIN_lerntagebuch/docs/assets/images/3_Screenshot_2024-02-27.png" alt="Screenshot Koha Suchfeld">
