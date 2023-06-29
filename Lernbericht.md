# Lern-Bericht
Gruppenname: Lemon
Joël Haldimann, Blentin Tosuni und Carina Sutter

## Einleitung

Wir haben in unserem Projekt eine Webseite über Zitate programmiert, welche man in einer Slideshow betrachten kann.

## Was habe ich gelernt?

Wir haben gelernt wie man mit HTML und CSS eine Slideshow auf einer Webseite programmiert

## Beschreibung

Die Slideshow ist eigentlich ein sehr breites Rechteck welches via Knöpfe so verschoben wird, dass man nur ein Bild sieht. Dass kann man mit einer Nav-Bar machen, so wie wir es gemacht haben oder mit Knöpfen. Um nur das einte Bild zu sehen macht man wenn man z.B. 5 Bilder will das Rechteck 500% Breit und die Bilder auf diesen Rechteck je 20% Breit. Sodass wenn man zum z.B. zweiten Bild scrollt man nur dieses sieht und nicht ein anderes. Um das Bild zu verschieben braucht man wie schon erwähnt eine Navbar, bei dieser ist es so, dass wenn man auf die zweite von fünf Tasten drückt sich das Rchteck um 20% nach links. 

```html
/*Code um das Rechteck zu verschieben*/

#r1:checked~.s1 {
    margin-left: 0;
}

#r2:checked~.s1 {
    margin-left: -20%;
}

#r3:checked~.s1 {
    margin-left: -40%;
}

#r4:checked~.s1 {
    margin-left: -60%;
}

#r5:checked~.s1 {
    margin-left: -80%;
}
```


https://github.com/Blentin05/LA_1600/assets/111045600/3ae2bed8-b9a5-472b-9261-da13bfe7c376


## Verifikation

Der Code zeigt wie das Rechteck verschoben wird, man macht es mir der Margin, dabei ist "s1" das Rechteck und r1-r5 sind die Knöpfe der Navbar, welche man auch im Video sehen kann. Neben diesem Code braucht es noch einige kleine weitere Codes aber diese sind nicht Funktional sonder Visuel.

Im Video sieht man wie das ganze Funktioniert, wenn man die Knöpfe drückt wird man zu einem anderen Bild verschoben.
# Reflektion zum Arbeitsprozess

+Wir hatten gute Code Ansätze welche nützlich für unsere Webseite war.

-Wir waren sehr unkoordiniert und so kam fast nichts zu stande.

**VBV**: 

Nächstes Mal sollten wir uns besser absprechen und zusammen arbeiten und nicht jeder für sich selbst.
