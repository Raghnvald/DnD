---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- Monster/HG/18
- Monster/Größe/Groß
- Monster/Typ/Fee
statblock: inline
statblock-link: "#^statblock"
aliases:
- Trostani
---
# [Trostani](3-Mechanics\CLI\bestiary\npc/trostani-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 252*  

The Selesnya guildmaster is an amalgamation of three dryads in body, will, and soul. Each dryad's body extends from a central trunk, so while they possess independent minds, they share a single name-Trostani and a single life force. Usually Trostani communicates the will of the Worldsoul with one voice, but she retains three distinct personalities that embody the three parts of the Selesnyan ideal: order, life, and harmony. In the midst of increasing tensions on Ravnica, the three personalities have recently been at odds over how best to navigate the conclave through such difficult times.

Trostani spends most of her time in the towering tree of Vitu-Ghazi, the Selesnya guildhall. There she communes with Mat'Selesnya and with the dryads who lead individual Selesnya communities across Ravnica.

```statblock
"name": "Trostani (GGR)"
"size": "Large"
"type": "fey"
"alignment": "Neutral Good"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "252"
"hit_dice": "24d10 + 120"
"modifier": !!int "2"
"stats":
  - !!int "19"
  - !!int "14"
  - !!int "20"
  - !!int "16"
  - !!int "30"
  - !!int "25"
"speed": "30 ft."
"saves":
  - "constitution": !!int "11"
  - "wisdom": !!int "16"
  - "charisma": !!int "13"
"skillsaves":
  - "name": "Arcana"
    "desc": "+9"
  - "name": "Insight"
    "desc": "+16"
  - "name": "Nature"
    "desc": "+9"
  - "name": "Perception"
    "desc": "+16"
  - "name": "Persuasion"
    "desc": "+13"
"condition_immunities": "charmed, grappled"
"senses": "darkvision 120 ft., passive Perception 26"
"languages": "Common, Druidic, Elvish, Sylvan"
"cr": "18"
"traits":
  - "desc": "Trostani's innate spellcasting ability is Wisdom (spell save DC 24).\
      \ She can innately cast the following spells, requiring no material components:\n\
      \n**At will:** dispel magic, druidcraft\n\n**3/day each:** bless, conjure animals,\
      \ giant insect, moonbeam, plant growth, spike growth, suggestion\n\n**1/day\
      \ each:** conjure fey, mass cure wounds"
    "name": "Innate Spellcasting"
  - "desc": "If Trostani fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Trostani has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Trostani's weapon attacks are magical."
    "name": "Magic Weapons"
  - "desc": "Trostani can communicate with beasts and plants as if they shared a language."
    "name": "Speak with Beasts and Plants"
  - "desc": "Once on her turn, Trostani can use 10 feet of her movement to step magically\
      \ into one living tree within her reach and emerge from a second living tree\
      \ within 60 feet of the first tree, appearing in an unoccupied space within\
      \ 5 feet of the second tree. Both trees must be Large or bigger."
    "name": "Tree Stride"
"actions":
  - "desc": "Trostani takes three actions: she uses Constrict and Touch of Order,\
      \ and she casts a spell with a casting time of 1 action."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 5 ft., one creature. *Hit:*\
      \ 15 (3d6 + 5) bludgeoning damage, and the target is grappled (escape DC 19).\
      \ Until this grapple ends, the target is restrained. Trostani can grapple no\
      \ more than three targets at a time."
    "name": "Constrict"
  - "desc": "*Melee Spell Attack:* +16 to hit, reach 5 ft., one creature. *Hit:* 23\
      \ (3d8 + 10) radiant damage, and Trostani can choose one magic item she can\
      \ see in the target's possession. Unless it's an artifact, the item's magic\
      \ is suppressed until the start of Trostani's next turn."
    "name": "Touch of Order"
  - "desc": "Trostani conjures a momentary whirl of branches and vines at a point\
      \ she can see within 60 feet of her. Each creature in a 30-foot cube on that\
      \ point must make a DC 24 Dexterity saving throw, taking 21 (6d6) bludgeoning\
      \ damage and 21 (6d6) slashing damage on a failed save, or half as much damage\
      \ on a successful one."
    "name": "Wrath of Mat'Selesnya (Recharge 5-6)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Trostani can expend a use to take one of the following actions. Trostani\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Trostani makes one melee attack, with advantage on the attack roll."
    "name": "Voice of Harmony"
  - "desc": "Trostani bestows 20 temporary hit points on another creature she can\
      \ see within 120 feet of her."
    "name": "Voice of Life"
  - "desc": "Trostani casts dispel magic."
    "name": "Voice of Order"
  - "desc": "Trostani casts suggestion. This counts as one of her daily uses of the\
      \ spell."
    "name": "Chorus of the Conclave (Costs 2 Actions)"
  - "desc": "Trostani animates one or two trees she can see within 120 feet of her,\
      \ causing them to uproot themselves and become awakened trees (see the Monster\
      \ Manual for their stat blocks) for 1 minute or until Trostani uses a bonus\
      \ action to end the effect. These trees understand Druidic and obey Trostani's\
      \ spoken commands, but can't speak. If she issues no commands to them, the trees\
      \ do nothing but follow her and take the Dodge action."
    "name": "Awaken Grove Guardians (Costs 3 Actions)"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/npc/token/trostani-ggr.webp"
```
^statblock