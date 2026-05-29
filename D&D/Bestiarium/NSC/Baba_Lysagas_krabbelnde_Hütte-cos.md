---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: "Baba Lysaga's Creeping Hut"
linter-yaml-title-alias: "Baba Lysaga's Creeping Hut"
tags:
  - Monster/Größe/Gigantisch
  - Monster/HG/11
  - Monster/Typ/Konstrukt
  - Quelle/5e/cos
aliases:
  - "Baba Lysaga's Creeping Hut"
  - Baba Lysaga's Creeping Hut
---
# [Baba Lysaga's Creeping Hut](3-Mechanics\CLI\bestiary\npc/baba-lysagas-creeping-hut-cos.md)
*Source: Curse of Strahd p. 226*  

Baba Lysaga built a hut atop the rotting stump of a giant tree that was felled long ago. It was only after she embedded a magic gemstone in the hut that the whole thing was imbued with a semblance of life. When she wills it to do so, the hut pulls its gigantic roots free of the earth and shambles around like a spidery behemoth, shaking the ground with every step. The hut attacks with its flailing and stomping roots. It can also use its roots to fling large rocks.

## Hut Interior

The hut is a 15-foot-square, ramshackle wooden building with a gently sloping thatch roof. Its furnishings have been bolted to the floor, since the hut lurches from side to side when it walks.

## Heart of the Hut

The gemstone that has given life to Baba Lysaga's hut was previously buried in the Wizard of Wines vineyard. The gem was one of three imbued with life-giving magic that made the grapevines in the vineyard healthier, guaranteeing the finest wines. Baba Lysaga stole one of the gems and perverted its magic, using it instead to animate her wooden hut.

Removing the gem from the hut renders the hut [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated). That task is easier said than done, however. The glowing green gem is contained in a cavity in the stump, beneath the rotted floorboards of the hut. The floorboards can be ripped up with a successful DC 14 Strength check or smashed by dealing 10 damage to them. Once the floorboards are out of the way, a creature can reach into the cavity and snatch the gem. But if someone attempts this while the hut is alive, the cavity sprouts wooden teeth, becoming a mouth that bites anything that tries to remove the gem; a creature trying to remove the gem must make a DC 20 Dexterity saving throw. On a successful save, the creature claims the stone without getting bitten. On a failed save, the creature is bitten for 10 (`3d6`) piercing damage and fails to obtain the gem.

```statblock
"name": "Baba Lysaga's Creeping Hut (CoS)"
"size": "Gargantuan"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "263"
"hit_dice": "17d20 + 85"
"modifier": !!int "-2"
"stats":
  - !!int "26"
  - !!int "7"
  - !!int "20"
  - !!int "1"
  - !!int "3"
  - !!int "3"
"speed": "30 ft."
"saves":
  - "constitution": !!int "9"
  - "wisdom": !!int "0"
  - "charisma": !!int "0"
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
  \ [deafened](/3-Mechanics/CLI/conditions.md#Deafened), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 120 ft. (blind beyond\
  \ this radius), passive Perception 6"
"languages": ""
"cr": "11"
"traits":
  - "desc": "An animated object doesn't require air, food, drink, or sleep.\n\nThe\
      \ magic that animates an object is dispelled when the construct drops to 0 hit\
      \ points. An animated object reduced to 0 hit points becomes inanimate and is\
      \ too damaged to be of much use or value to anyone."
    "name": "Constructed Nature"
  - "desc": "The hut is [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ while the magic gem that animates it is in the area of an [antimagic field](/3-Mechanics/CLI/spells/antimagic-field-xphb.md).\
      \ If targeted by [dispel magic](/3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
      \ the hut must succeed on a Constitution saving throw against the caster's spell\
      \ save DC or fall [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)\
      \ for 1 minute."
    "name": "Antimagic Susceptibility"
  - "desc": "The hut deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The hut makes three attacks with its roots. It can replace one of these\
      \ attacks with a rock attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 60 ft., one target. *Hit:* 30\
      \ (4d10 + 8) bludgeoning damage."
    "name": "Root"
  - "desc": "*Ranged Weapon Attack:* +12 to hit, range 120 ft., one target. *Hit:*\
      \ 21 (3d8 + 8) bludgeoning damage."
    "name": "Rock"
"source":
  - "CoS"
"image": "/3-Mechanics/CLI/bestiary/npc/token/baba-lysagas-creeping-hut-cos.webp"
```
^statblock

# Baba Lysagas krabbelnde Hütte
Baba Lysaga hat eine Hütte auf einem verrotteten Stumpf eines riesigen Baums gebaut, der vor langer Zeit gefällt wurde. Als sie einen magischen Edelstein in die Hütte einbettete, wurde das ganze Ding mit einer Art Leben erfüllt. Wenn sie es ihr befiehlt, zieht die Hütte ihre gigantischen Wurzeln aus der Erde heraus und schlurft herum, wie ein spinnenartiges Ungetüm, das bei jedem Schritt den Erdboden erzittern lässt. Die Hütte attackiert mit ihren peitschenden und stampfenden Wurzeln. Sie kann ihre Wurzeln auch benutzen, um große Felsbrocken zu schleudern.
$\quad$ **_Hütteninneres._** Die Hütte ist ein 7,50m im Quadrat messendes wackeliges Holzgebäude mit einem sanft ansteigenden Reetdach. Das Mobiliar ist mit Bolzen am Boden befestigt, da die Hütte von einer Seite zur anderen schwankt, wenn sie läuft.
$\quad$ **_Herz der Hütte._** Der Edelstein, der Baba Lysagas Hütte zum Leben erweckt hat, war zuvor im Weinmagier-Weinberg vergraben. Das Juwel war eines von dreien, die mit lebensspendender Magie durchsetzt waren, welche die Weinstücke im Weinberg gesünder machte und die besten Weine garantierten. Baba Lysaga stahl eines der Juwelen, pervertierte seine Magie und nutzte sie stattdessen, um ihre Holzhütte zu beleben.
$\quad$ Wird das Juwel aus der Hütte entfernt, wird die Hütte kampfunfähig. Dieses Vorhaben ist jedoch leichter gesagt, als getan. Das glühende grüne Juwel ist in einem Hohlraum im Stumpf untergebracht, unter den morschen Bodendielen der Hütte. Die Dielen können mit einem gelungenen Stärkewurf gegen SG 14 herausgerissen oder zerschmettert werden, wenn man ihnen 10 Schaden zufügt. Sobald die Bodendielen aus dem Weg sind, kann eine Kreatur in den Hohlraum greifen und sich das Juwel schnappen. Aber wenn jemand dies versucht, solangedie Hütte noch lebt, wachsen dem Hohlraum Holzzähne und er wird ein Maul, das alles beißt, was das Juwel zu entfernen versucht; eine Kreatur die versucht das Juwel zu entfernen, muss einen Geschicklichkeits-Rettungswurf gegen SG 20 ablegen. Bei einem gelungenen Rettungswurf bemächtigt sich die Kreatur des Steins, ohne gebissen zu werden. Bei einem misslungenen Rettungswurf wird die Kreatur mit 10 (`dice: 3d6`) Stichschaden gebissen und versagt dabei, das Juwel zu beschaffen.

```statblock
statblock: true
name: Baba Lysagas krabbelnde Hütte
source: Fluch des Strahd
size: Gigantisch
type: Konstrukt
alignment: gesinnungslos
ac: 16
hp: 263
hit_dice: 7d20 +85
speed: 9 Meter.
stats: [26, 7, 20, 1, 3, 3]
saves:
  - STR: +0
  - GES: +0
  - KON: +9
  - INT: +0
  - WEI: +0
  - CHA: +0
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: "Gift, psychisch"
condition_immunities: "Bezaubert, blind, erschöpft, gelähmt, liegend, taub, verängstigt, versteinert"
senses: Blindsicht 36 Meter (über diesen Radius hinaus blind), passive Wahrnehmung 6
languages: -
cr: 11
bestiary: true
traits:
  - name: Antimagische Empfindlichkeit
    desc: Die Hütte wird kampfunfähig, wenn sich das magische Juwel, welches sie belebt, im Bereich eines _Antimagischen Feldes_ befindet. Wenn die Hütte Ziel von _Magie bannen_ wird, muss sie einen Konstitutions-Rettungswurf gegen den Zauberrettungswurf-SG des Zauberwirkers ablegen, um nicht für 1 Minute bewusstlos zu werden.
    attack_bonus: 0
  - name: Belagerungsmonster
    desc: Die Hütte verursacht doppelten Schaden gegen Gegenstände und Bauwerke.
    attack_bonus: 0
actions:
  - name: Mehrfachangriff
    desc: "Die Hütte führt drei Angriffe mit ihren Wurzeln aus. Sie kann einen dieser Angriffe durch einen Fels-Angriff ersetzen."
  - name: Wurzel
    desc: "_Nahkampf-Waffenangriff_: +12 zum Treffen, Reichweite 18m, ein Ziel. Treffer: 30 (4W10 + 8) Wuchtschaden."
    attack_bonus: 12
    damage_dice: 4d10
    damage_bonus: 8
  - name: Fels
    desc: "_Fernkampf-Waffenangriff_: +12 zum Treffen, Reichweite 36m, ein Ziel. Treffer: 21 (3W8 + 8) Wuchtschaden."
    attack_bonus: 12
    damage_dice: 3d8
    damage_bonus: 8
```