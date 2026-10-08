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

**Game-Boy-Modus:** Standard ist auf allen Geräten die klassische Ansicht. Über den Button **Game-Boy-Modus**
lässt sich ein Handheld-Layout einschalten: im Hochformat oben der Bildschirm, unten Steuerkreuz (Kamera),
**A** = Mozartkugel werfen, **B** = Baileys rollt bzw. zurückdrängen, dazu Sound, Move und Pause.
Der Button **Klassisch** schaltet zurück; die Wahl merkt sich der Browser.

Moves: Hüftschwung, Klatschen, Pirouette, Disco-Finger, Salzburg-Hüpfer.
Joker **Sammi**, ein schwarzer Shih Tzu: Würde Bici Schaden nehmen, rennt er herbei und
bellt laut. Mit 50 % Chance verbellt er den Goblin und der Schaden fällt weg, sonst passiert nichts.

**Dev-Modus:** `?dev` an die Adresse hängen (z. B. `…/bici_in_salzburg/?dev`), dann gibt es oben
Buttons für +50 und +150 Punkte, um Welten und Level-ups direkt zu testen.

## Level

Alle 150 Punkte geht es automatisch in ein neues Level, und jedes Level macht die Goblins 10 % schneller.

| Level | ab Punkten | Ort |
|---|---|---|
| 1 | 0 | Residenzplatz |
| 2 | 150 | Festung Hohensalzburg: Burghof mit Linde und Brunnen, Alpen am Horizont |
| 3 | 300 | Mirabellgarten: Blumenbeete, Statuen, Blick auf die Festung |
| 4 | 450 | Weihnachtsmarkt am Residenzplatz: Schnee, Buden, Christbaum |
| 5 | 600 | Festung Hohenwerfen: Burg auf dem Felsen, Berge, kreisende Greifvögel |
| 6 | 750 | Salzburg Hauptbahnhof: Bahnsteig, Glasdach, Abfahrtstafel, durchfahrender Zug |
| 7 | 900 | Getreidegasse: Zunftschilder, Mozarts Geburtshaus |
| Finale | 1000 | Gaisberg-Gipfel: Siegestanz mit Feuerwerk über den Lichtern Salzburgs, dann Sieg |

- **Alle 50 Punkte** kommt **Joker Sammi** (und manchmal einfach, wenn er Lust hat) und erledigt einen Goblin.
  Wenn Bici Schaden nehmen würde, bellt er weiterhin mit 50 % Chance den Goblin weg.
- **Robi aus Beham** hilft ab 100 Punkten ebenfalls alle 50 Punkte.
- **Menei & Christine** sind ab 100 Punkten ein Perk: Er wird gespart und mit **C** (bzw. Perk-Knopf) eingesetzt,
  dann schreit Christine alle Goblins weg. Einen neuen Perk gibt es erst, wenn der alte ausgegeben ist:
  alle 100 Punkte, ab dem Mirabellgarten alle 50.
- **Baileys** (R): rollt; manchmal rollt er in Richtung der Goblins, walzt alle auf seiner Bahn platt,
  rollt hinaus und kommt zurück.

**Mama** kommt einmal pro Level auf ihrem E-Scooter (schlank, blond, Pferdeschwanz), sobald Kerstin die
Tanzfläche betritt: Kerstin bleibt stehen, die Bühne leert sich nicht weiter, Mama schimpft und schickt
Kerstin heim. Punkte gibt es dafür keine, die 10 Punkte bringt nur selbst Zurückdrängen.

Bici hat fünf Leben; bei null ist Game Over. Ebenso, wenn die Bühnen-Leiste leer ist.
**Der Alei** kommt oft (erstmals nach etwa 25 Sekunden, dann alle 12 bis 18 Sekunden) mit zwei Bier und torkelt
auf Bici zu („Bici, sauf ma oan!“). Zurückdrängen wie bei Kerstin gibt 10 Punkte; sind beide da, trifft K den, der
näher ist. Erreicht er Bici, stoßen sie an: Bici ist 5 Sekunden beschwipst, schwankt, und nur jeder 2. Wurf trifft.

**Fernkampf-Goblins** (jeder fünfte, lila Kapuze, orange Markierung): Sie bleiben in etwa 7 m Abstand stehen,
schleudern drei Steine (je ½ Leben, Sammi wehrt mit 50 % ab) und laufen dann wie normale Goblins auf Bici zu.
Mozartkugeln prallen an ihnen ab. Ist ein Fernkämpfer auf dem Platz, rollt **Baileys** mit **R** (oder Antippen
des Fernkämpfers) immer gezielt auf ihn zu und erwischt ihn sicher. Sammi, Robi und Christine erledigen sie ebenfalls.

Goblin = 1 Punkt, Kerstin oder Alei vertrieben = je 10 Punkte; sie kommt jedes Mal hartnäckiger zurück.
