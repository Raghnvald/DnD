---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psd
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Shalai"
---
# [Shalai](3-Mechanics/CLI/bestiary/npc/shalai-psd.md)
*Source: Plane Shift: Dominaria p. 9*  

The most visible and recognized symbols of the Church of Serra are her angels—both those that were personally created by Serra and those that appeared spontaneously in the Cathedral at Sursi. Some angels live contemplative lives within the cathedrals, but most are active defenders of the faith, protecting Serra's people across the world. Powerful angels often take responsibility for large regions of the world. Lyra, for example, stands as the protector of Benalia, and Shalai plays a similar role in Llanowar. Serra's angels are believed to hear prayers addressed to Serra, and they have an uncanny tendency to arrive exactly when they are needed.

Any of the angels in the "Monster Manual" can serve as [Serra angels](3-Mechanics/CLI/bestiary/celestial/serra-angel-psd.md). The [deva](3-Mechanics/CLI/bestiary/celestial/deva.md) represents the most common angels, while the [planetar](3-Mechanics/CLI/bestiary/celestial/planetar.md) and [solar](3-Mechanics/CLI/bestiary/celestial/solar.md) are appropriate for powerful angels such as [Lyra](3-Mechanics/CLI/bestiary/npc/lyra-psd.md) and [Shalai](3-Mechanics/CLI/bestiary/npc/shalai-psd.md).

```statblock
"name": "Shalai (PSD)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "243"
"hit_dice": "18d10 + 144"
"modifier": !!int "6"
"stats":
  - !!int "26"
  - !!int "22"
  - !!int "26"
  - !!int "25"
  - !!int "25"
  - !!int "30"
"speed": "50 ft., fly 150 ft."
"saves":
  - "intelligence": !!int "14"
  - "wisdom": !!int "14"
  - "charisma": !!int "17"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+14"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"gear":
  - "[greatsword](3-Mechanics/CLI/items/greatsword.md)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 24"
"languages": "all, telepathy 120 ft."
"cr": "21"
"traits":
  - "desc": "Shalai's spellcasting ability is Charisma (spell save DC 25). It can\
      \ innately cast the following spells, requiring no material components:\n\n\
      **At will:** [detect evil and good](3-Mechanics/CLI/spells/detect-evil-and-good.md),\
      \ [invisibility](3-Mechanics/CLI/spells/invisibility.md) (self only)\n\n**3/day\
      \ each:** [blade barrier](3-Mechanics/CLI/spells/blade-barrier.md), [dispel\
      \ evil and good](3-Mechanics/CLI/spells/dispel-evil-and-good.md), [resurrection](3-Mechanics/CLI/spells/resurrection.md)\n\
      \n**1/day each:** [commune](3-Mechanics/CLI/spells/commune.md), [control weather](3-Mechanics/CLI/spells/control-weather.md)"
    "name": "Innate Spellcasting"
  - "desc": "Shalai's weapon attacks are magical. When Shalai hits with any weapon,\
      \ the weapon deals an extra 6d8 radiant damage (included in the attack)."
    "name": "Angelic Weapons"
  - "desc": "Shalai knows if it hears a lie."
    "name": "Divine Awareness"
  - "desc": "Shalai has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Shalai makes two greatsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 5 ft., one target. *Hit:*\
      \ 22 (4d6 + 8) slashing damage plus 27 (6d8) radiant damage."
    "name": "Greatsword"
  - "desc": "*Ranged Weapon Attack:* +13 to hit, range 150/600 ft., one target.\
      \ *Hit:* 15 (2d8 + 6) piercing damage plus 27 (6d8) radiant damage. If the\
      \ target is a creature that has 100 hit points or fewer, it must succeed on\
      \ a DC 15 Constitution saving throw or die."
    "name": "Slaying Longbow"
  - "desc": "Shalai releases its greatsword to hover magically in an unoccupied space\
      \ within 5 feet of it. If Shalai can see the sword, Shalai can mentally command\
      \ it as a bonus action to fly up to 50 feet and either make one attack against\
      \ a target or return to Shalai's hands. If the hovering sword is targeted by\
      \ any effect, Shalai is considered to be holding it. The hovering sword falls\
      \ if Shalai dies."
    "name": "Flying Sword"
  - "desc": "Shalai touches another creature. The target magically regains 40 (8d8\
      \ + 4) hit points and is freed from any curse, disease, poison, blindness,\
      \ or deafness."
    "name": "Healing Touch (4/Day)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Shalai can expend a use to take one of the following actions. Shalai regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Shalai magically teleports, along with any equipment it is wearing or\
      \ carrying, up to 120 feet to an unoccupied space it can see."
    "name": "Teleport"
  - "desc": "Shalai emits magical, divine energy. Each creature of its choice in a\
      \ 10-foot radius must make a DC 23 Dexterity saving throw, taking 14 (4d6)\
      \ fire damage plus 14 (4d6) radiant damage on a failed save, or half as much\
      \ damage on a successful one."
    "name": "Searing Burst (Costs 2 Actions)"
  - "desc": "Shalai targets one creature it can see within 30 feet of it. If the target\
      \ can see it, the target must succeed on a DC 15 Constitution saving throw or\
      \ be [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded) until magic such\
      \ as the [lesser restoration](3-Mechanics/CLI/spells/lesser-restoration.md)\
      \ spell removes the blindness."
    "name": "Blinding Gaze (Costs 3 Actions)"
"source":
  - "PSD"
"image": "3-Mechanics/CLI/bestiary/npc/token/shalai-psd.webp"
```
^statblock