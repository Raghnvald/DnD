---
cssclasses:
  - json5e-monster
tags:
  - Monster/Größe/Riesig
  - Monster/Habitat/Wald
  - Quelle/5e/cos
  - Monster/Typ/Pflanze
aliases:
  - Tree Blight
---
# Baumplage
Plagen sind böse, wandelnde Pflanzenkreaturen, und eine Baumplage ist eine besonders große Unterart. Sie sieht aus wie ein toter Baum oder Baumhirte, 10 m groß, mit schwammigem, holzigen Fleisch, dornigen Ästen und gummiartigen Wurzeln, die sie hinter sich herzieht. Sie hat Blut statt Harz und ist derart von Blut durchtränkt, dass sie nicht leicht Feuer fängt.
$\quad$ **_Brutaler Fleischfresser._** Eine Baumplage ernährt sich von warmblütiger Beute und zieht perverses Vergnügen aus dem Verursachen von Blutbädern. Sie schlägt mit ihren schweren Ästen zu und quetscht Beute mit ihren Wurzeln zu Tode. Sie kann ihr klaffendes, zahnbewehrtes Maul öffnen und eine zwischen ihren Wurzeln gefangene Kreatur beißen. Die Wurzeln einer Baumplage können abgetrennt werden, obwohl das Abschneiden der Plage keinen Schaden verursacht.
$\quad$ **_Plagenfeindseligkeit._** Eine Baumplage wird oft an der Seite anderer Arten von Plagen kämpfen, aber sie hasst andere Baumplagen und wird sie bei der geringsten Chance attackieren. Baumplagen hassen auch Baumhirten, und das Gefühl beruht auf Gegenseitigkeit.

```statblock
statblock: true
name: Baumplage
image: 
source: Fluch des Strahd
size: Riesig
type: Pflanze
alignment: Neutral Böse
ac: 15
hp: 149
hit_dice: 13d12 + 65
speed: 9 Meter.
stats: [23, 10, 20, 6, 10, 3]
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: "Blind, Taub"
senses: Blindsicht 18 m (über diesen Radius hinaus blind), passive Wahrnehmung 13
languages: versteht Gemeinsprache und Druidisch, kann aber nicht sprechen
cr: 7
bestiary: true
traits:
  - name: Falsches Erscheinungsbild.
    desc: "Solange die Plage bewegungslos bleibt, ist sie nicht von einem toten Baum zu unterscheiden."
  - name: Belagerungsmonster.
    desc: "Die Plage verursacht doppelten Schaden gegen Gegenstände und Bauwerke"
actions:
  - name: Mehrfachangriff
    desc: "Die Plage führt vier Angriffe aus: zwei mit ihren Ästen und zwei mit ihren Greifwurzeln. Wenn sie einen Charakter gepackt hat, kann die Plage auch als Bonusaktion einen Biss-Angriff gegen dieses Ziel ausführen."
  - name: Ast
    desc: "_Nahkampf-Waffenangriff:_ +9 zum Treffen, Reichweite 4,50 m, ein Ziel. _Treffer:_ 16 (`3W6 + 6`) Wuchtschaden."
    attack_bonus: 9
    damage_dice: 3d6
    damage_bonus: 6
  - name: Biss
    desc: "_Nahkampf-Waffenangriff:_ +9 zum Treffen , Reichweite 1,50 m, ein Ziel. _Treffer:_ 19 (`3W8 + 6`) Stichschaden."
    attack_bonus: 9
    damage_dice: 3d8
    damage_bonus: 6
  - name: Greifwurzel.
    desc: "_Nahkampf-Waffenangriff:_ +9 zum Treffen, Reichweite 4,50 m, eine nicht von der Plage gepackte Kreatur. _Treffer:_ Das Ziel wird gepackt (Rettungswurf zum Entkommen SG 15). Bis der Haltegriff endet, erleidet das Ziel 9 (`1W6 + 6`) Wuchtschaden zu Beginn jeder seiner Runden. Die Wurzel hat RK 15 und kann ab- getrennt werden, indem ihr auf einmal 6 Hiebschaden oder mehr zugefügt werden. Wird die Wurzel abgetrennt, verletzt das die Plage nicht, beendet aber den Haltegriff."
    attack_bonus: 9
    damage_dice: 3d8
    damage_bonus: 6
```