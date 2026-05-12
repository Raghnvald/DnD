---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/aitfr-isf
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Malivar"
---
# [Malivar](3-Mechanics/CLI/bestiary/npc/malivar-aitfr-isf.md)
*Source: Adventures in the Forgotten Realms: In Scarlet Flames p. 12*  

Malivar Kresk is a Red Wizard of Thay, a conjurer, and recent apprentice to the treacherous Red Wizard named Morwena. Young, pale white, plain, and slender, Malivar usually hates his own appearance but hopes his red robes and smooth scalp give him a "lean and mean" look.

Now alone on his mission, Malivar doesn't hesitate to use or abuse the trust of others if it means he can get revenge, return to Thay alive, and report on Morwena's betrayal.

```statblock
"name": "Malivar (AitFR-ISF)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "40"
"hit_dice": "9d8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "12"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "6"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "Arcana"
    "desc": "+6"
  - "name": "History"
    "desc": "+6"
"gear":
  - "dagger"
"senses": "passive Perception 11"
"languages": "Common, Draconic, Ignan, Infernal"
"cr": "6"
"traits":
  - "desc": "Malivar is a 9th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 14, +6 to hit with spell attacks). He has the following wizard\
      \ spells prepared:\n\n**Cantrips (at will):** acid splash, mage hand, poison\
      \ spray, prestidigitation\n\n**1st level (4 slots):** mage armor, magic missile,\
      \ unseen servant*\n\n**2nd level (3 slots):** cloud of daggers*, misty step*,\
      \ web*\n\n**3rd level (3 slots):** fireball, thunder step*\n\n**4th level (3\
      \ slots):** Evard's black tentacles*, stoneskin\n\n**5th level (2 slots):**\
      \ cone of cold*, conjure elemental*\n\n*Conjuration spell of 1st level or higher"
    "name": "Spellcasting"
  - "desc": "As a bonus action, Malivar teleports up to 30 feet to an unoccupied space\
      \ that he can see.\n\nIf he instead chooses a space within range that is occupied\
      \ by a willing Small or Medium creature, they both teleport, swapping places."
    "name": "Benign Transportation (Recharges after Malivar Casts a Conjuration Spell\
      \ of 1st Level or Higher)"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "AitFR-ISF"
"image": "3-Mechanics/CLI/bestiary/npc/token/malivar-aitfr-isf.webp"
```
^statblock