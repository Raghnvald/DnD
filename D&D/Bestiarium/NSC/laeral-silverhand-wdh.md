---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Laeral Silverhand
linter-yaml-title-alias: Laeral Silverhand
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/17
  - Monster/Typ/Humanoid/Mensch
  - Quelle/5e/wdh
aliases:
  - Laeral Silverhand
---
# [Laeral Silverhand](3-Mechanics\CLI\bestiary\npc/laeral-silverhand-wdh.md)
*Source: Waterdeep: Dragon Heist p. 207*  

Anamanué Laeral Silverhand was born in the Year of the Cowl (765 DR), the fifth of seven daughters of the goddess Mystra. Each of the Seven Sisters is a powerful and ageless beauty with a penchant for arcane magic.

Long ago, Laeral ruled a kingdom called Stornanter and held the title of Witch-Queen of the North. After that, she led a band of adventurers called the Nine. She met and married Khelben Arunsun, who would later become the Blackstaff, the Lord Mage of Waterdeep. After Khelben died, Laeral retired from public life. She resurfaced after the Spellplague and the Sundering, weakened by Mystra's death, rebirth, and withdrawal from the world.

Laeral's magic isn't as great as it once was, though she does her utmost to hide this fact. Only Elminster, her trusted friend and advisor, knows the extent of her decline. Despite her diminished abilities, Laeral remains a formidable, clear-headed wizard with plenty of magic at her disposal.

A few years ago, Dagult Neverember was ousted as Open Lord of Waterdeep. Laeral reluctantly stepped into the vacancy at the request of the Masked Lords, and has served as Waterdeep's Open Lord ever since. Initially overwhelmed by the demands of the nobles and guildmasters, she has settled nicely into her new role. She uses her magic sparingly and relies on trusted advisors and deputies. As time allows, she likes to venture outside the Palace of Waterdeep in disguise, just to clear her head or check up on old friends (and enemies).

Laeral's relationship with Vajra Safahr, the current Blackstaff, has its challenges. For one thing, Laeral is much older, much wiser, and much more powerful than Vajra, whom she views as an insecure child. In addition, Vajra wields the Blackstaff, which has Khelben Arunsun's soul and the souls of all the other Blackstaffs bound inside it. Laeral covets the staff, because it contains all that's left of her husband. Not surprisingly, the two mages avoid each other as much as possible.

In times of great need, Laeral can command Vajra to unleash Force Grey. Until that order is given, Force Grey isn't allowed to conduct operations in Waterdeep, though Laeral's spies tell her that Vajra has secretly activated members of the elite order and sent them on a number of unauthorized missions. Laeral is reluctant to confront Vajra on the matter, and rationalizes her inaction by framing it as a test of Vajra's competence.

```statblock
"name": "Laeral Silverhand (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Good"
"ac": !!int "18"
"ac_class": "robe of the archmagi"
"hp": !!int "228"
"hit_dice": "24d8 + 120"
"modifier": !!int "3"
"stats":
  - !!int "13"
  - !!int "17"
  - !!int "20"
  - !!int "20"
  - !!int "20"
  - !!int "19"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "11"
  - "wisdom": !!int "11"
"skillsaves":
  - "name": "Arcana"
    "desc": "+17"
  - "name": "History"
    "desc": "+17"
  - "name": "Insight"
    "desc": "+11"
  - "name": "Perception"
    "desc": "+11"
  - "name": "Persuasion"
    "desc": "+10"
"damage_resistances": "fire"
"damage_immunities": "poison"
"condition_immunities": "poisoned"
"senses": "truesight 60 ft., passive Perception 21"
"languages": "Common, Draconic, Dwarvish, Elvish, Giant, Infernal"
"cr": "17"
"traits":
  - "desc": "Laeral is a 19th-level spellcaster. Her spellcasting ability is Intelligence\
      \ (spell save DC 21, +13 to hit with spell attacks). Laeral has the following\
      \ wizard spells prepared:\n\n**Cantrips (at will):** light, mage hand, minor\
      \ illusion, prestidigitation, ray of frost\n\n**1st level:** detect magic, disguise\
      \ self, magic missile, shield\n\n**2nd level:** detect thoughts, invisibility,\
      \ misty step\n\n**3rd level (3 slots):** counterspell, fly, sending, tongues\n\
      \n**4th level (3 slots):** banishment, greater invisibility, Otiluke's resilient\
      \ sphere\n\n**5th level (3 slots):** cone of cold, geas, Rary's telepathic bond\n\
      \n**6th level (2 slots):** globe of invulnerability, mass suggestion\n\n**7th\
      \ level (1 slots):** prismatic spray, teleport\n\n**8th level (1 slots):** feeblemind,\
      \ power word stun\n\n**9th level (1 slots):** time stop"
    "name": "Spellcasting"
  - "desc": "Laeral wears a white robe of the archmagi (accounted for in her statistics).\
      \ She wields a flame tongue longsword."
    "name": "Special Equipment"
  - "desc": "While wearing her robe of the archmagi, Laeral has advantage on saving\
      \ throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Laeral makes three attacks with her silver hair and flame tongue, in\
      \ any combination. She can cast one of her cantrips or 1st-level spells before\
      \ or after making these attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (2d6) force damage, and the target must succeed on a DC 19 Constitution saving\
      \ throw or be paralyzed for 1 minute. The target can repeat the saving throw\
      \ at the end of each of its turns, ending the effect on itself on a success."
    "name": "Silver Hair"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 5 (1d8\
      \ + 1) slashing damage plus 7 (2d6) fire damage, or 6 (1d10 + 1) slashing damage\
      \ plus 7 (2d6) fire damage when used with two hands."
    "name": "Flame Tongue"
  - "desc": "Magical, heatless, silver fire harmlessly erupts from Laeral and surrounds\
      \ her until she is incapacitated or until she uses an action to quench it. She\
      \ gains one of the following benefits of her choice, which lasts until the silver\
      \ fire ends:\n\n- She can breathe underwater.  \n- She can survive without food\
      \ and water.  \n- She is immune to magic that would ascertain her thoughts,\
      \ truthfulness, alignment, or creature type.  \n- She gains resistance to cold\
      \ damage, and she is unharmed by temperatures as low as -50 degrees Fahrenheit.\
      \  \n\nWhile the silver fire is present, she has the following additional action\
      \ options:\n\n- Cast the cure wounds spell. The target regains 1d8 + 5 hit points.\
      \ After Laeral takes this action, roll a d6. On a roll of 1, the silver fire\
      \ disappears.  \n- Cast the revivify spell without material components. After\
      \ Laeral takes this action, roll a d6. On a roll of 1-2, the silver fire disappears.\
      \  \n- Release a 60-foot line of silver fire that is 5 feet wide or a 30-foot\
      \ cone of silver fire. Objects in the area that aren't being worn or carried\
      \ take 26 (4d12) fire damage. Each creature in the area must succeed on a DC\
      \ 21 Dexterity saving throw, taking 26 (4d12) fire damage on a failed save,\
      \ or half as much damage on a successful one. After Laeral takes this action,\
      \ roll a d6. On a roll of 1-3, the silver fire disappears.  "
    "name": "Spellfire (Recharges after a Long Rest)"
"source":
  - "WDH"
"image": "/3-Mechanics/CLI/bestiary/npc/token/laeral-silverhand-wdh.webp"
```
^statblock