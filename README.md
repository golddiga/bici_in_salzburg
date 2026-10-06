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
| P / Esc / Pause-Button | Pause an/aus (auch automatisch beim Tab-Wechsel) |

Moves: Hüftschwung, Klatschen, Pirouette, Disco-Finger, Salzburg-Hüpfer.
Joker **Sammi**, ein schwarz-weißer Shih Tzu: Würde Bici Schaden nehmen, rennt er herbei und
bellt laut. Mit 50 % Chance verbellt er den Goblin und der Schaden fällt weg, sonst passiert nichts.

**Level-ups:** Alle 50 Punkte steigt das Level, die Goblins werden schneller, und **Robi aus Beham**
kommt angerannt und erledigt einen der vorhandenen Goblins.
Alle 100 Punkte kommt außerdem **Menei mit seiner Christine**: Christine schreit so laut, dass
alle Goblins auf dem Platz sofort sterben.

Bici hat fünf Leben; bei null ist Game Over. Ebenso, wenn die Bühnen-Leiste leer ist.
Goblin = 1 Punkt, Kerstin vertrieben = 5 Punkte; sie kommt jedes Mal hartnäckiger zurück.
