---
title: "Einheit 10: Linked Data"
date: 2024-06-03
---
Weitere Informationen erhältst Du über den Link: 
<a href="https://pad.gwdg.de/KY1DbBllTM2UC4C3CTNy5w#">BAIN HedgeDoc</a>

**Aktuelle Datenmodelle für Metadaten**

**1 BIBFRAME**

Wenn ich das richtig verstehe, besteht einer der grösseren Unterschiede zwischen MARC und BIBFRAME darin, dass MARC eine flache, datensatzbasierte Struktur mit festen Feldern und Unterfeldern (Personenname, Firmenname) verwendet, aber jedes Element/Entität (z. B. Buch) in gewisser Weise isoliert ist. 

BIBFRAME hingegen verwendet eine graphbasierte Struktur, die verschiedene Elemente/Entitäten miteinander verbindet und ihre Beziehungen definiert. Das bedeutet, dass BIBFRAME die Duplizierung von Informationen über mehrere Datensätze hinweg vermeiden kann. Wenn wir Werke von Goethe haben, brauchen wir den Namen des Autors nicht zu wiederholen, wenn wir Metadaten über jede einzelne Entität schreiben, solange die Beziehung zwischen den Werken und Goethe hergestellt ist, solange die Werke durch den Autor verbunden sind. Hierarchie ist auch vorhanden, solange wir zum Beispiel den Autor als Unterklasse des "Beiträgers" verstehen. Die Teile sind also nicht nur miteinander verbunden, sie haben auch eine bestimmte Rolle in der Beziehung.

**2 Records in Contexts (RiC)**

RiC ist in gewisser Weise ähnlich, da es ebenfalls darauf abzielt, eine besser vernetzte und detailliertere Beschreibung von Archiven zu liefern. Es macht Sinn, dass die Beziehungen in den Archiven noch wichtiger und komplexer sein können. Ausserdem sind die Kontexte, in denen bestimmte Records erstellt, benutzt und aufbewahrt wurden, wichtiger und oft hilfreich für das Verständnis der Records selbst (wieder die Bedeutung des Provinienzprinzips).

RiC erlaubt, auch anderen Beziehungen zwischen Unterlagen verschiedener Bestände zu folgen (auch in ISAAR (CPF) oder ISDF) aber neu ist die Remodellierung dieser Informationen von einem deskriptiven Text zu annotierten, maschinenlesbaren Metadaten (<a href="https://archivwelt.hypotheses.org/1982">Quelle</a>).

**3 Linked Open Usable Data (LOUD)**

Ein weiterer Schritt, wie der Name schon sagt, offene Daten, die ihre Nutzbarkeit betonen. Denn es ist nicht unbedingt hilfreich, wenn sie nur verfügbar sind. 

Das erinnert mich an ein Gespräch, das wir in einem der Kurse hatten, in dem wir darüber diskutierten, ob wir dafür oder dagegen sind, alle wissenschaftlichen Arbeiten kostenlos zur Verfügung zu stellen. Ich habe mich nur gefragt, ob das ausreicht. Wenn man:
- nicht an "freie" Daten herankommt, weil man keine Möglichkeit hat, "einfach" online zu gehen und sie auf seinen Computer herunterzuladen;
- aufgrund einer bestimmten Behinderung nicht lesen kann;
- aufgrund einer Sprachbarriere nicht verstehen kann;
- nicht fähig ist, sie zu verarbeiten, weil das zum Denken und Verstehen erforderliche Wissen fehlt;
- und schliesslich kann man sich nicht entscheiden, was man lesen soll. Ich möchte lieber die richtigen Daten zur richtigen Zeit haben, als ständig alles zur Verfügung zu haben.

 Als ich las und die Keynotes von Rob Sanderson für 2018 hörte, war ich angenehm überrascht, dass sie sich mit Fragen des Vertrauens und der Nützlichkeit von Inhalten für bestimmte Gruppen/Typen von Menschen befassen (<a href=" https://linked.art/loud/">Quelle<a>).

**OpenRefine und Wikidata**

Zuerst importierten wir die Daten, dann begannen wir mit dem Abgleich (reconciliation). Die Anreichung war der dritte Schritt. 

Es scheint ein fruchtloses Experiment zu sein, aber ich finde es toll, dass man z.B. Autoren nach beliebigen Eigenschaften/Merkmalen ordnen kann. Wie z.B. die Frisur. Ich könnte mir auch vorstellen, dies für eine zufällige Bibliotheksveranstaltung zu verwenden. Manchmal muss man etwas in Eile vorbereiten und unsere Bibliotheksbenutzer reagierten im Allgemeinen besser auf Veranstaltungen, die mehr waren als nur "berühmteste Schriftstellerinnen" ua. Ich kann mir vorstellen, dass eine Veranstaltung, bei der die Autoren nach der Art ihres Todes gruppiert werden, mit ein wenig Humor versehen, eine gute Möglichkeit wäre, Informationen einzubauen. 
Wie Aischylos, der starb, weil ihm eine Schildkröte auf den Kopf fiel. Und viele der berühmten Autoren sind angeblich vor Lachen gestorben. Wer hätte das gedacht. Hoffentlich haben sie nicht über die arme Schildkröte gelacht.

<img src="/BAIN_lerntagebuch/docs/assets/images//15_Screenshot_2024_06_6.png" alt="Screenshot Spass mit Open Refine">
 
