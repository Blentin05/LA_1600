# Lern-Bericht
Lemon, Joël Haldimann, Blentin Tosuni und Carina Sutter

## Einleitung

Wir haben in unserem Projekt eine Webseite über Zitate programmiert.

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





* Ein deutliches, aussagekräftiges Bild oder eine kommentierte Bildschirm-Aufnahme
* Ein gut dokumentierter Code-Fetzen
* Ein Link zu einem *selbst aufgenommenen* youtube-Video oder `.gif`.

## Verifikation

✍️ Erklären Sie kurz und bündig, inwiefern die von Ihnen verwendeten Medien zeigen, was Sie gelernt haben.

# Reflektion zum Arbeitsprozess

👍 Überlegen Sie sich jeweils etwas, was gut an Ihrer Arbeit lief; 

👎 und etwas, was nicht gut lief.

**VBV**: ✍️ Formulieren Sie davon ausgehend einen *handelbaren* Verbesserungsvorschlag.
