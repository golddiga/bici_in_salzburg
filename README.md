# Bici in Salzburg

3D-Gameplay-Preview im Browser: Bici und ihr Terrier Baileys tanzen nachts auf dem
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
| R | Baileys macht eine Rolle |
| C | Perk einsetzen: Menei & Christine |
| M | Sound an/aus |
| P / Esc / Pause-Button | Pause an/aus (auch automatisch beim Tab-Wechsel) |

**Game-Boy-Modus:** Auf Handys und Tablets startet das Spiel als Handheld: im Hochformat oben der Bildschirm,
unten Steuerkreuz (Kamera drehen/zoomen), **A** = Mozartkugel werfen, **B** = Baileys rollt bzw. Kerstin zurückdrängen
(leuchtet, sobald sie kommt), dazu Sound, Move und Pause. Im Querformat liegen die Tasten am Rand über der Szene.
Der Button **Klassisch / Game-Boy-Modus** schaltet jederzeit um; die Wahl merkt sich der Browser.
Pfeiltasten drehen und zoomen die Kamera auch am Desktop.

Moves: Hüftschwung, Klatschen, Pirouette, Disco-Finger, Salzburg-Hüpfer.
Joker **Sammi**, ein schwarz-weißer Shih Tzu: Würde Bici Schaden nehmen, rennt er herbei und
bellt laut. Mit 50 % Chance verbellt er den Goblin und der Schaden fällt weg, sonst passiert nichts.

## Welten und Level

| Punkte | Welt | Besonderheit |
|---|---|---|
| 0–149 | Residenzplatz | Start |
| 150–299 | Festung Hohensalzburg | Burghof mit Linde und Brunnen, Alpen am Horizont |
| 300–499 | Mirabellgarten | alles 20 % schneller, Blick auf die Festung |
| 500 | Sieg | Gewinn-Bildschirm |

- **Alle 50 Punkte** steigt das Level; die Goblins werden je Level 10 % schneller.
- **Joker Sammi** kommt bei jedem Level-up (und manchmal einfach, wenn er Lust hat) und erledigt einen Goblin.
  Wenn Bici Schaden nehmen würde, bellt er weiterhin mit 50 % Chance den Goblin weg.
- **Robi aus Beham** hilft ab Level 3 bei jedem Level-up.
- **Menei & Christine** sind ab 100 Punkten ein Perk: Er wird gespart und mit **C** (bzw. Perk-Knopf) eingesetzt,
  dann schreit Christine alle Goblins weg. Einen neuen Perk gibt es erst, wenn der alte ausgegeben ist:
  alle 100 Punkte, im Mirabellgarten alle 50.
- **Baileys** (R): rollt; manchmal rollt er in Richtung der Goblins, walzt alle auf seiner Bahn platt,
  rollt hinaus und kommt zurück.

Bici hat fünf Leben; bei null ist Game Over. Ebenso, wenn die Bühnen-Leiste leer ist.
Goblin = 1 Punkt, Kerstin vertrieben = 5 Punkte; sie kommt jedes Mal hartnäckiger zurück.
