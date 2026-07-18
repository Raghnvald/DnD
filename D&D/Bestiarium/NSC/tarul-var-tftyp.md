---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Tarul Var
Status: WIP
linter-yaml-title-alias: Tarul Var
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/13
  - Monster/Typ/Untote
  - Quelle/5e/tftyp
aliases:
  - Tarul Var
---
# [Tarul Var](3-Mechanics\CLI\bestiary\npc/tarul-var-tftyp.md)
*Source: Tales from the Yawning Portal p. 244*  

After failing in an earlier task for the Red Wizards, the lich Tarul Var is sequestered within the Doomvault (Dead in Thay), where he tries to avoid the attention of Szass Tam. Interlopers who discover his quarters are set upon by the lich and his dread warrior guards, but if Var is brought to the brink of death, he might bargain for a chance to escape the dungeon.

## Undead Nature

A lich doesn't require air, food, drink, or sleep.

```statblock
"name": "Tarul Var (TftYP)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "105"
"hit_dice": "14d8 + 42"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "16"
  - !!int "19"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "constitution": !!int "8"
  - "intelligence": !!int "9"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "Arcana"
    "desc": "+9"
  - "name": "History"
    "desc": "+9"
  - "name": "Insight"
    "desc": "+7"
  - "name": "Perception"
    "desc": "+7"
"damage_resistances": "cold; lightning; necrotic; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, poisoned"
"senses": "darkvision 60 ft., passive Perception 17"
"languages": "Abyssal, Common, Infernal, Primordial, Thayan"
"cr": "13"
"traits":
  - "desc": "Var is a 12th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 17, +9 to hit with spell attacks). He has the following wizard\
      \ spells prepared:\n\n*Conjuration spell of 1st level or higher\n\n**Cantrips\
      \ (at will):** fire bolt, mage hand, minor illusion, prestidigitation, ray of\
      \ frost\n\n**1st level (4 slots):** detect magic, magic missile, shield, unseen\
      \ servant*\n\n**2nd level (3 slots):** detect thoughts, flaming sphere*, mirror\
      \ image, scorching ray\n\n**3rd level (3 slots):** counterspell, dispel magic,\
      \ fireball\n\n**4th level (3 slots):** dimension door*, Evard's black tentacles*\n\
      \n**5th level (3 slots):** cloudkill*, scrying\n\n**6th level (1 slots):** circle\
      \ of death"
    "name": "Spellcasting"
  - "desc": "While Var is concentrating on a conjuration spell, his concentration\
      \ can't be broken as a result of taking damage."
    "name": "Focused Conjuration"
  - "desc": "If Var fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "If Var is destroyed but his phylactery remains intact, Var gains a new\
      \ body in 1d10 days, regaining all his hit points and becoming active again.\
      \ The new body appears within 5 feet of the phylactery."
    "name": "Rejuvenation"
  - "desc": "Var has advantage on saving throws against any effect that turns undead."
    "name": "Turn Resistance"
"actions":
  - "desc": "*Melee Spell Attack:* +9 to hit, reach 5 ft., one creature. *Hit:* 10\
      \ (3d6) cold damage. The target must succeed on a DC 17 Constitution saving\
      \ throw or be paralyzed for 1 minute. The target can repeat the saving throw\
      \ at the end of each of its turns, ending the effect on itself on a success."
    "name": "Paralyzing Touch"
  - "desc": "Var teleports up to 30 feet to an unoccupied space he can see. Alternatively,\
      \ he can choose a space within range that is occupied by a Small or Medium creature.\
      \ If that creature is willing, both creatures teleport, swapping places. Var\
      \ can use this feature again only after he finishes a long rest or casts a conjuration\
      \ spell of 1st level or higher."
    "name": "Benign Transposition"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Tarul can expend a use to take one of the following actions. Tarul regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Var casts a cantrip."
    "name": "Cantrip"
  - "desc": "Var uses Paralyzing Touch."
    "name": "Paralyzing Touch (Costs 2 Actions)"
  - "desc": "Var fixes his gaze on one creature he can see within 10 feet of him.\
      \ The target must succeed on a DC 17 Wisdom saving throw against this magic\
      \ or become frightened for 1 minute. The frightened target can repeat the saving\
      \ throw at the end of each of its turns, ending the effect on itself on a success.\
      \ If a target's saving throw is successful or the effect ends for it, the target\
      \ is immune to Var's gaze for the next 24 hours."
    "name": "Frightening Gaze (Costs 2 Actions)"
"source":
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/npc/token/tarul-var-tftyp.webp"
```
^statblock