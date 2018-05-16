---
layout: post
title:  "Spanneisen fräsen"
date:   2018-05-16 19:32:35 +0200
categories: general 
---
Beim letzten Montagstreffen haben wir für die CNC-Fräse ein paar Spanneisen (oder auch Spannpratzen) gefräst. Die Funktion dieser Teile ist es Werkstücke sicher auf dem Frästisch zu befestigen. Hier ein Bild eines kommerziellen Produkts im Einsatz:

![Spanneisen](https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/Spanneisen.jpg/1200px-Spanneisen.jpg) (Von <a href="//commons.wikimedia.org/wiki/User:Ussschrotti" title="User:Ussschrotti">Ussschrotti</a>, <a href="http://creativecommons.org/licenses/by-sa/3.0/" title="Creative Commons Attribution-Share Alike 3.0">CC BY-SA 3.0</a>, <a href="https://commons.wikimedia.org/w/index.php?curid=1372027">Link</a>)

Als Material kommen Alureste von Thomas zum Einsatz (Legierung unbekannt). Hier kommt die Wirkelfräsfunktion von Estlcam zum Einsatz. Die Vorwärtsbewegung wird dabei mit einer Kreisbewegung überlagert. Damit sind auch auf unserer weichen Maschine relativ schnelle Fräsungen möglich. 

Folgende Parameter wurden verwendet:
* Fräser: 1/8" (3,175mm) Zweischneider
* Drehzahl: Maximal (ca. 29000 rpm)
* Tiefenzustellung: 3.33mm
* Vorschub: 1000mm/min
* Eintauchgeschwindigkeit: 800mm/min (zu hoch!)
* Wirbelzustellung: 5%
* Schmier-/Kühlmittel: Spiritus
* Materialdicke: 10mm

Damit lies sich ganz ordentlich arbeiten. Gefühlt ist bei Tiefenzustellung und Vorschub sogar noch Luft nach oben. Beim Vorschub muss beachtet werden, dass der effektive Vorschub durch die Wirbelbewegung deutlich kleiner ist. Dennoch ist diese Methode deutlich schneller als das klassische Fräsen und dabei auch noch schonend für den Fräser. Normalerweise hätte man auf unserer Maschine vermutlich nur 0.5mm Tiefenzustellung nutzen können. Somit wären die ersten 0.5mm des Fräsers 20x belastet worden und der Rest nie. Jetzt wurden die Schneiden nur 3x, dafür aber auf wesentlich größerer Länge belastet. Der Fräser hält etwa 7x so lang (wenn ihn vorher keiner abbricht). 

Ein Problem war die Eintauchgeschwindigkeit. Mit 800mm/min war sie viel zu hoch gewählt. Das hat man richtig gehört und der Fräser ist an der Eintauchstelle auch deutlich (~0.5mm) verlaufen.

So und jetzt zum interessanten Teil: Videos

 <video width="740" height="416" controls>
  <source src="/assets/spanneisen1.webm" type="video/webm">
Your browser does not support the video tag.
</video> 

 <video width="740" height="416" controls>
  <source src="/assets/spanneisen2.webm" type="video/webm">
Your browser does not support the video tag.
</video> 
