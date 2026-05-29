---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Abberanter Eiferer
Kategorie: Aberration
Größe: Mittelgroß
HG: 8
Habitat:
  - /
Image: token/aberrant-zealot-pabtso.webp
status: WIP
linter-yaml-title-alias: Abberanter Eiferer
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/8
  - Monster/Typ/Aberration
  - Quelle/5e/pabtso
aliases:
  - Abberanter Eiferer
  - Aberrant Zealot
---
# Abberanter Eiferer
*Source: Phandelver and Below: The Shattered Obelisk p. 203*  

Aberrant zealots are cultists who have reached out to the powers of the Far Realm—only for something to reach back. Steeped in strange energy, aberrant zealots borrow their vicious might from the monstrous entities that inhabit that fell plane.

```statblock
"name": "Abnormaler Eiferer (PaBTSO)"
"size": "Mittelgroß"
"type": "Aberration"
"alignment": "normalerweise Chaotic Böse"
"ac": !!int "16"
"ac_class": "[Beschlagene Lederrüstung](Gegenstände/studded-leather-armor-xphb.md)"
"hp": !!int "93"
"hit_dice": "17d8 + 17"
"modifier": !!int "4"
"stats":
  - !!int "15"
  - !!int "18"
  - !!int "12"
  - !!int "13"
  - !!int "8"
  - !!int "19"
"speed": "9 Meter"
"saves":
  - "Geschicklichkeit": !!int "7"
  - "Charisma": !!int "7"
"skillsaves":
  - "name": "[Wahrnehmung](skills.md#Perception)"
    "desc": "+5"
"damage_resistances": "Psychisch"
"condition_immunities": "[Blind](conditions.md#Blinded), [Verzaubert](conditions.md#Charmed),\
  \ [Verängstigt](conditions.md#Frightened), [Gepackt](conditions.md#Grappled),\
  \ [Festgesetzt](conditions.md#Restrained)"
"senses": "[Dunkelsicht](senses.md#Darkvision) 60 ft., [Wahrer Blick](senses.md#Truesight) 3 Meter, passive Wahrnehmung 15"
"languages": "Gemeinsprache, Tiefensprache"
"cr": "8"
"traits":
  - "name": "Aberrant Form"
    "desc": "The zealot exudes the chaos of the Far Realm. Any non-Aberration creature that starts its turn within 5 feet of the zealot must succeed on a DC 15 Wisdom saving throw or take 7 (2d6) psychic damage."
  - "name": "Weirdly Pliable"
    "desc": "The zealot, along with any equipment it is wearing or carrying, is unnaturally flexible. The zealot can move through any space as narrow as 1 inch without squeezing."
"actions":
  - "name": "Multiattack"
    "desc": "The zealot makes one Psychic Rend attack and two Shortsword attacks."
  - "name": "Psychic Rend"
    "desc": "*Melee  or Ranged Spell Attack:* +7 to hit, reach 15 ft. or range 120 ft., one target. *Hit:* 14 (3d6 + 4) psychic damage, and the target must succeed on a DC 15 Wisdom saving throw or have the [stunned](conditions.md#Stunned) condition until the start of the zealot's next turn."
  - "name": "Shortsword"
    "desc": "*Melee Weapon Attack:* +7 to hit, reach 15 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 7 (2d6) psychic damage."
  - "desc": "The zealot casts one of the following spells, requiring no components and using Charisma as the spellcasting ability (spell save DC 15):\n\n**At will:** [Gedanken wahrnehmen](Zauber/Gedanken-wahrnehmen-xphb.md), [Einfache Illusion](Zauber/Einfache-Illusion-xphb.md)\n\n**1/day each:** [Arkanes Tor](Zauber/Arkanes-Tor-xphb.md), [Hunger von Hadar](Zauber/Hunger-von-Hadar-xphb.md)"
    "name": "Spellcasting (Psionics)"
"bonus_actions":
  - "desc": "The zealot teleports, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 120 feet of itself, leaving a churning void in the space it left. Immediately after it teleports, each creature within 30 feet of the void other than the zealot must make a DC 15 Strength saving throw. On a failed save, a creature takes 18 (4d8) force damage and is pulled to the unoccupied space closest to the void. On a successful save, the creature takes half as much damage only. The void then disappears."
    "name": "Void Warp (Recharge 5-6)"
"source":
  - "PaBTSO"
"image": "aberration/token/aberrant-zealot-pabtso.webp"
```
^statblock

---

```statblock
name: Abnormaler Eiferer (PaBTSO)
size: Mittelgroß
type: Aberration
alignment: normalerweise Chaotic Böse
ac: 16
ac_class: <STATBLOCK-MARKDOWN-LINK>Gegenstände/studded-leather-armor-xphb.md|Beschlagene Lederrüstung<STATBLOCK-MARKDOWN-LINK>
hp: 93
hit_dice: 17d8 + 17
modifier: 4
stats:
  - 15
  - 18
  - 12
  - 13
  - 8
  - 19
speed: 9 Meter
saves:
  - Geschicklichkeit: 7
  - Charisma: 7
skillsaves:
  - name: <STATBLOCK-MARKDOWN-LINK>skills.md#Perception|Wahrnehmung<STATBLOCK-MARKDOWN-LINK>
    desc: "+5"
damage_resistances: Psychisch
condition_immunities: <STATBLOCK-MARKDOWN-LINK>conditions.md#Blinded|Blind<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>conditions.md#Charmed|Verzaubert<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>conditions.md#Frightened|Verängstigt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>conditions.md#Grappled|Gepackt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>conditions.md#Restrained|Festgesetzt<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>senses.md#Darkvision|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 60 ft., <STATBLOCK-MARKDOWN-LINK>senses.md#Truesight|Wahrer Blick<STATBLOCK-MARKDOWN-LINK> 3 Meter, passive Wahrnehmung 15
languages: Gemeinsprache, Tiefensprache
cr: "8"
traits:
  - name: Aberrant Form
    desc: The zealot exudes the chaos of the Far Realm. Any non-Aberration creature that starts its turn within 5 feet of the zealot must succeed on a DC 15 Wisdom saving throw or take 7 (2d6) psychic damage.
  - name: Weirdly Pliable
    desc: The zealot, along with any equipment it is wearing or carrying, is unnaturally flexible. The zealot can move through any space as narrow as 1 inch without squeezing.
actions:
  - name: Multiattack
    desc: The zealot makes one Psychic Rend attack and two Shortsword attacks.
  - name: Psychic Rend
    desc: "*Melee  or Ranged Spell Attack:* +7 to hit, reach 15 ft. or range 120 ft., one target. *Hit:* 14 (3d6 + 4) psychic damage, and the target must succeed on a DC 15 Wisdom saving throw or have the <STATBLOCK-MARKDOWN-LINK>conditions.md#Stunned|stunned<STATBLOCK-MARKDOWN-LINK> condition until the start of the zealot's next turn."
  - name: Shortsword
    desc: "*Melee Weapon Attack:* +7 to hit, reach 15 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 7 (2d6) psychic damage."
  - desc: |-
      The zealot casts one of the following spells, requiring no components and using Charisma as the spellcasting ability (spell save DC 15):

      **At will:** <STATBLOCK-MARKDOWN-LINK>Zauber/Gedanken-wahrnehmen-xphb.md|Gedanken wahrnehmen<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zauber/Einfache-Illusion-xphb.md|Einfache Illusion<STATBLOCK-MARKDOWN-LINK>

      **1/day each:** <STATBLOCK-MARKDOWN-LINK>Zauber/Arkanes-Tor-xphb.md|Arkanes Tor<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zauber/Hunger-von-Hadar-xphb.md|Hunger von Hadar<STATBLOCK-MARKDOWN-LINK>
    name: Spellcasting (Psionics)
bonus_actions:
  - desc: The zealot teleports, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 120 feet of itself, leaving a churning void in the space it left. Immediately after it teleports, each creature within 30 feet of the void other than the zealot must make a DC 15 Strength saving throw. On a failed save, a creature takes 18 (4d8) force damage and is pulled to the unoccupied space closest to the void. On a successful save, the creature takes half as much damage only. The void then disappears.
    name: Void Warp (Recharge 5-6)
source:
  - PaBTSO
image: aberration/token/aberrant-zealot-pabtso.webp
mtime: 1763643288992
path: D&D/05 - Wikipedia/Bestiarium/bestiary/aberration/Abnormaler Eiferer-pabtso.md
```