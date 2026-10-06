# Bici in Salzburg

3D-Gameplay-Preview im Browser: Bici und ihr Terrier Bob tanzen nachts auf dem
Salzburger Residenzplatz, vor Dom, Residenzbrunnen und Festung Hohensalzburg.
Alle fünf Sekunden kommen drei Goblins, die Bici mit Mozartkugeln abwehrt.
Und immer wieder taucht Bicis rothaarige Schwester Kerstin mit ihrem Dackel auf und will die Tanzfläche übernehmen:
steht sie im Kreis, leert sich die Bühnen-Leiste. Bici muss sie zurückdrängen.

## Starten

`index.html` im Browser öffnen. Keine Installation, keine Build-Schritte;
three.js (r128) kommt vom CDN.

## Steuerung

| Eingabe | Wirkung |
|---|---|
| Goblin antippen / F | Mozartkugel werfen |
| Ziehen / Mausrad | Kamera drehen / zoomen |
| Leertaste | nächster Tanz-Move |
| Kerstin antippen / K | Kerstin zurückdrängen |
| R | Bob macht eine Rolle |
| M | Sound an/aus |

Moves: Hüftschwung, Klatschen, Pirouette, Disco-Finger, Salzburg-Hüpfer.
Bici hat fünf Leben; bei null ist Game Over. Ebenso, wenn die Bühnen-Leiste leer ist.
Goblin = 1 Punkt, Kerstin vertrieben = 5 Punkte; sie kommt jedes Mal hartnäckiger zurück.
