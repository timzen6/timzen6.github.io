---
layout: draft
title: Data Science im Alltag
short: hacking-cert-long
language: german
---

## Einleitung

Als Data Scientist nutzen wir in unserem Beruf einen großen Werkzeugkasten, um allerhand Probleme zu lösen. 
Eine wichtige Zutat sind immer die Daten. Mal mehr, mal weniger Daten und oft in unterschiedlicher Qualität.
In vielen Fällen gibt es eher zu viel als zu wenig Daten und es gilt Signal von Rauschen zu trennen.

Als Data Scientist ist es oft unserer vordefiniere Rolle dafür zu argumentieren, mehr oder bessere Daten in Entscheidungsprozesse miteinfließen zu lassen. Doch folgen wir selbst unserem eigenen Rat?
Sicher nicht immer und ich glaube das ist an vielen Stellen auch gut so.
Vermutlich werden nicht alle Entscheidungen durch Daten besser. 
Aber können Daten auch helfen Entscheidungen im "echten Leben" zu treffen oder zumindest die Entscheidungen transpartenter machen? 

Dieser Frage bin ich Letztens im Selbstversuch nachgegangen.
Es ging, um die Frage, wie viel ich für eine Azure Zertifikatsprüfung lernen sollte?
Ich finde das Beispiel ziemlich passend, weil es sich auf viele Prüfungsvorbereitungen verallgemeinern lässt.
Üblicherweise, war mein Vorgehen für Prüfungen immer, ich lerne so viel bis ich mich gut vorbereitet fühle. In der Regel, war das meistens eigentlich zu viel der Vorbereitung.
Vielleicht kann ein Daten-insprierter Ansatz helfen, den Tradeoff zu optimieren.


## Problemstellung: Wie viel lernen ist genug?


Die Kernfrage ist also, wie viel muss ich lernen um die Prüfung relativ sicher zu bestehen.
Es liegen auch erstmal keine relevanten Daten vor, um die Frage zu beantworten.
Im ersten Schritt gilt es also Daten zu sammeln.
Zum Glück ist es in diesem Fall relativ einfach gewesen an Porbeaufgaben zu kommen.
Meiner Erfahung aus Schule, Uni und anderen Prüfungssituationen, ist das aber gar kein unwahrscheinliches Szenario.
Natürlich kann man jetzt so lange lernen bis man den gesamten Katalog an Probeaufgaben lösen kann.
Das wäre in dem Fall recht zeitaufwändig gewesen und vermutlich auch unnötig.
Bei den meisten Prüfungen, wie hier auch, muss man ja nicht alles wissen, um zu bestehen.
In dem konkreten Fall hatte der Satz an Probeaufgaben etwa 400 Fragen und war in 5 Bereiche aufgeteilt.


Im ersten Schritt habe ich daraus Stichproben, quasi Probeprüfungen, mit jetzt 20-30 Fragen gesamplet.
Die vorgeschlagenen Fragen habe ich dann versucht zu beantworten und mir meine Ergebnisse in einer Excel-Tabelle notiert. Genauer gesagt, wie viele Punkte die Aufgabe gab, wie viele dieser Punkte ich erreicht hätte. Da nicht immer klar war, was überhaupt die richtige Lösung auf die jeweilige Frage war, habe ich in einem zusätzlichen Feld notiert, ob ich mir bei der Auswertung unsicher war.

Hier ein Beispiel: 
![](/assets/images/hacking-cert/excel-example.png)


Die gesammelten Daten lassen sich dafür nutzen verschiedene Fragen zu beantworten. Folgenden Aspekte waren für mich interessant:

1. Auf welchem Level ist mein aktueller Kentnissstand? Wie wahrscheinlich ist es die Prüfung Stand jetzt zu bestehen?
2. Wo sind bei mir noch Wissenslücken? Helfen mir die Probefragen diese Lücken auszubessern?

Konzeptionell sind diese beiden Fragestellungen zu trennen, weil sie für die Modellierung aus Data Science Sicht unterschiedliche Implikationen haben.
Im ersten Teil geht man davon aus, dass es einen konstanten aber unbekannten Kentnissstand gibt, den es mehr oder weniger genau zu messen gilt.
Das ist eine eher idealisierte Annahme, die eine einfache Auswertung ermöglicht.

Realistischer ist wahrscheinlich eher der Fall, dass man von Fragebogen zu Fragebogen etwas besser wird. Insbesondere wenn man zu Fragen, die einem schwer gefallen sind, Zusatzinformationen recherchiert bevor man sich an den nächsten Testfragebogen macht.

## Die ersten Daten sind da: Was nun?

Nach den ersten paar Probedurchläufen ergibt sich langsam ein belastbares Bild. Eine genaue Auswertung findet sich weiter unten.
Aber auch ohne aufwändigere Auswertung lassen sich schon sindvolle Metriken laufend berechnen.

Um eine Idee von der eigenen Performance zu bekommen war für mich sowohl die gemittelte Punktzahl über alle und die letzten N (mit N=1,3 oder 5) Fragebögen hilfreich.
Außerdem haben mir auch die Metriken für die Fragen gruppiert nach Kategorie geholfen systematische Lücken zu erkennen.

**Bild ??**

Neben den Performance Metriken habe ich zudem noch die Abdeckung im Bezug auf dem Gesamtfragenkatalog im Blick behalten. Also z.B. wie viel Prozent des Fragenkatalogs mindestens einmal abgefragt wurde oder wie viel Prozent des Fragenkatalogs mindestens einmal komplett richtig beantwortet wurde.

## Optimierte Vorschläge

## Die Prüfung

## Genauere Auswertung

## Allgemeineres + Lessons learnt


