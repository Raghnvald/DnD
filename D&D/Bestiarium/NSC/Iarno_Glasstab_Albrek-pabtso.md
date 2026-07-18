---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: 'Iarno "Glasstab" Albrek'
Image: token/iarno-glasstaff-albrek-pabtso.webp
Status: WIP
linter-yaml-title-alias: 'Iarno "Glasstab" Albrek'
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/1
  - Monster/Typ/Humanoid/Magier
  - Monster/Typ/Humanoid/Mensch
  - Quelle/5e/pabtso
aliases:
  - 'Iarno "Glasstab" Albrek'
---
# Iarno "Glasstab" Albrek
*Source: Phandelver and Below: The Shattered Obelisk p. 43*  

A former member of the Lords' Alliance, Glasstaff seized an opportunity in Phandalin to line his own pockets. Originally tasked with setting up a constabulary, he instead assembled a group of outlaws and local ruffians to secure his own position in town.

Glasstaff puts on airs of gentility and courteous manners, addressing his bandits and ruffians as "my good fellows," and referring to sordid acts such as kidnapping or arson as "that unpleasant little business" or "those unfortunate events." He may refer to the characters as his "honored guests," and expresses regret that he cannot provide suitable entertainment for the occasion of their visit. Beneath his genteel demeanor, however, Glasstaff is just as violent and arrogant as any of the Redbrands.

```statblock
"name": "Iarno \"Glasstab\" Albrek (PaBTSO)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, wizard"
"alignment": "Lawful Evil"
"ac": !!int "12"
"ac_class": "16 with [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md) and\
  \ [staff of defense](/3-Mechanics/CLI/items/staff-of-defense-pabtso.md)"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+5"
"senses": "passive Perception 11"
"languages": "Common, Draconic, Dwarvish, Elvish"
"cr": "1"
"traits":
  - "desc": "Glasstaff wields a [staff of defense](/3-Mechanics/CLI/items/staff-of-defense-pabtso.md)\
      \ (see appendix B). With the staff in hand, he can use an action to cast the\
      \ [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md) spell and use his\
      \ reaction to cast the [shield](/3-Mechanics/CLI/spells/shield-xphb.md) spell."
    "name": "Special Equipment"
"actions":
  - "desc": "Glasstaff makes two Shocking Burst attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +5 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 6 (1d6 + 3) lightning damage."
    "name": "Shocking Burst"
  - "desc": "Glasstaff casts one of the following spells, requiring no material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 13):\n\n\
      **At will:** [light](/3-Mechanics/CLI/spells/light-xphb.md), [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md)\n\
      \n**1/day each:** [charm person](/3-Mechanics/CLI/spells/charm-person-xphb.md),\
      \ [hold person](/3-Mechanics/CLI/spells/hold-person-xphb.md), [magic missile](/3-Mechanics/CLI/spells/magic-missile-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Glasstaff magically teleports, along with any equipment he is wearing\
      \ or carrying, up to 30 feet to an unoccupied space he can see."
    "name": "Teleport (2/Day)"
"source":
  - "PaBTSO"
"image": "npc/token/iarno-glasstaff-albrek-pabtso.webp"
```
^statblock

```statblock
statblock: true
name: Iarno "Glasstaff" Albreck
image: [[Iarno Glasstaff Albrek.webp]]
source: Phandelver & Below
size: Mittelgroß
type: Humanoid
alignment: Rechtschaffen böse
ac: 12
hp: 22
hit_dice: 5d8
speed: 9 Meter.
stats: [9, 14, 11, 17, 12, 11]
saves:
  - Intelligenz: 5
  - Weisheit: 3
skillsaves:
  - Arkane Kunde: 5
  - Geschichte: 5
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Wahrnehmung 11
languages: Drakonisch, Elfisch, Gemeinsprache, Zwergisch 
cr: 1
bestiary: true
traits:
  - name: Besondere Ausrüstung
    desc: "Glasstaff schwingt einen Stab der Verteidigung. Mit dem Stab in der Hand kann er eine Aktion verwenden, um den Zauber [[Magierrüstung.md|Magierrüstung]] zu wirken, und seine Reaktion nutzen, um den Zauber [[Schild.md|Schild]] zu wirken."
actions:
  - name: Mehrfachangriff
    desc: "Glasstab führt zwei Angriffe mit „Schockierender Stoß“ aus."
  - name: Schockierender Stoß
    desc: "Nahkampf- oder Fernkampf-Zauberangriff: +5 auf Treffer, Reichweite 1,5m. oder 36m., ein Ziel. Treffer: 6 (`1W6 + 3`) Blitzschaden."
    attack_bonus: 6
    damage_dice: 1d6
    damage_bonus: 3
spells:
  - "Glasstab wirkt einen der folgenden Zauber, die keine materiellen Komponenten benötigen und Intelligenz als Zauberfähigkeit verwenden (Zauberrettungswurf SG 13):"
  - Nach Belieben: [[light.md|Licht]], [[Magierhand.md|Magierhand]]
  - Je 1/Tag: [[Person-bezaubern|Person bezaubern]], [[Person-festhalten.md|Person festhalten]], [[Magisches Geschoss]]
bonus_actions:
  - name: Teleportieren (2/Tag)
    desc: "Glasstab teleportiert sich zusammen mit der Ausrüstung, die er trägt, auf magische Weise bis zu 9 Meter weit in einen unbesetzten Raum, den er sehen kann."
```