---
title: "Logik"
output:
  html_document:
    keep_tex: yes
    theme: united
    toc: yes
  pdf_document:
    highlight: zenburn
    keep_tex: yes
    number_sections: yes
    toc: yes
---


#Logik

Die Basis der Logik sind Propositionen, sowie die Beziehung zwischen diesen. Also Sätze die entweder wahr oder falsch sind. 
Es gibt mehrere Anwendungen der puren Logik, also die Sätze sind andere, aber die benutze Basis der Logik bleibt gleich in den Bereichen.
Jeder dieser Bereiche benutzt unterschiedliche Sätze und verbindet diese mit Konnektoren um damit Bedeutungen aus dem jeweiligen Bereich zu kodierne. Diese Bereiche sind z.B.

* Informatik
* Elektrotechnik
* Linguistik
* Philosophie
* Mathematik


Mathematik hat beispielsweise solche Propositionen `4+5 > 3-4`.
In der Linguistik, sind die Sätze aus einer bestimmten Sprache.

Beziehungen (Relationen), die Propositionen verbinden und damit komplexere Propositionen bilden sind Funktionen wie:

* `und` -- konjunktion
* `oder` -- disjunktion
* `Konditional` 
* `Biconditional -- if and only if 
* `not` -- negation

# Formale Sprachen ( eine Sprache um Formen zu beschreiben)
Die Syntax oder die Symbole der Propsitionalen Sprache wird durch definieren einer formale Sprache aus Formeln erreicht.

Diese oben eingeführten Relationen, werden nun mit Symbolen representiert wodurch man komplexe Sätze einfacher darstellen kann. Diese Symbole sind Bestandteil einer Sprache.
Die Sprache besteht aus folgenden Bausteinen.

Die Sprache ist aus Formel gemacht. Was eine Formel ist, wird streng definiert.

* Atome -- einheiten die man nicht kleiner machen kann sind Formel
* Wenn A eine Formel ist, ist auch -A eine Formel
* Wenn A und B Formeln sind, dann sind auch (A&B), (AVB) (A-->B) Formeln
* Absolut nichts anderes ist eine Formel

Andere Strings aus diesen Symbolen sind keine Formeln und deshalb nicht wellformed.

#Formalisation (wie macht man aus natürlicher Sprache  in foramliserte Sprache übersetzen kann) 

Logik bildet die Grundlage zur Erstellung von formalen Sprachen.

Also kann man von einem Gegenstand( z.b. eine Sprache oder ein Modell) in eine formale Sprache übersetzen.

Durch diese Formalisierung erkennt man die Form die die natürliche Sprache hat oder dieser Gegenstand.

Was kann man mit formalen Sprachen ausdrücken?
Kann ich alles was ich mit der formalen Sprachen aussagen kann auch wirklich machen? oder gibt es ding die ich z.b mit einer Datenbank machen kann die ich nicht formalisieren kann?

So kann mit natürlichen Sprachen viel mehr ausdrücken als in formalen Sprachen, allerdings sind formale Sprachen eindeutiger.
Ein natürlich gesprochener mehrdeutiger Satz, kann durch zwei eindeutige formale Sätze ersetzt werden und damit die Mehrdeutigkeit beseitigen, oder aufzeigen.

# Interpretierung der formalen Sprache

Die Semantik der Propositionalen Logik wird durch das zuweisen von Wahrheitswerten zu Formeln festgelegt.

In nicht-klassischen Logiken, gibt es komplexere Semantiken als nur die Wahrheitswerte von wahr und falsch in der klassischen Logik

