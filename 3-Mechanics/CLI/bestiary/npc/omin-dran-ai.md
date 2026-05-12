---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ai
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/half-elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Omin Dran"
---
# [Omin Dran](3-Mechanics/CLI/bestiary/npc/omin-dran-ai.md)
*Source: Acquisitions Incorporated p. 196*  

> [!quote]  
> 
> My duty, first and foremost, is to my shareholders. And I am the only shareholder.

Ominifis Hereward Dran spent his formative years in the small way-stop of Red Larch, where his mother, Prophetess, ran a popular inn and restaurant. In the brief periods of respite afforded by working the family business, Omin and his sisters, Auspicia and Portentia, were wont to wander the hills and trails around town, dreaming of adventure. But adventure of the wrong kind came calling for the trio one day, when an underground ruin they had often explored-actually a creature called the Wandering Crypt-took Auspicia from the world.

Omin Dran built the organization called Acquisitions Incorporated to facilitate and expand his quest to find his true sister, at least in part. For despite his unprecedented success in establishing the market for franchised adventuring across the Sword Coast and beyond, Omin's full measure eludes most people. He is known to be a worshiper of Tymora, ruthless in matters of business, feckless in matters of love, and hopeless in games of chance. Omin is also often accused of being one of the Masked Lords of Waterdeep, though this bit of fancy earns little more than a chuckle in response. And even if the rumor were true, Omin would never leverage such a position for greater financial gain and power. Because that would be wrong...

```statblock
"name": "Omin Dran (AI)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf"
"alignment": "Lawful Neutral"
"ac": !!int "18"
"ac_class": "plate armor"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "-1"
"stats":
  - !!int "16"
  - !!int "8"
  - !!int "14"
  - !!int "11"
  - !!int "18"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "7"
  - "charisma": !!int "4"
"skillsaves":
  - "name": "Deception"
    "desc": "+4"
  - "name": "Insight"
    "desc": "+7"
  - "name": "Intimidation"
    "desc": "+4"
  - "name": "Medicine"
    "desc": "+7"
  - "name": "Perception"
    "desc": "+7"
  - "name": "Persuasion"
    "desc": "+4"
"gear":
  - "maul"
"senses": "darkvision 60 ft., passive Perception 17"
"languages": "Common, Dwarvish, Elvish, Goblin"
"cr": "5"
"traits":
  - "desc": "Omin is a 9th-level spellcaster. His spellcasting ability is Wisdom (spell\
      \ save DC 15, +7 to hit with spell attacks). He has the following cleric spells\
      \ prepared:\n\n**Cantrips (at will):** guidance, sacred flame, spare the dying,\
      \ thaumaturgy\n\n**1st level (4 slots):** bless, command, divine favor, shield\
      \ of faith\n\n**2nd level (3 slots):** enhance ability, hold person, magic weapon,\
      \ silence, spiritual weapon\n\n**3rd level (3 slots):** beacon of hope, crusader's\
      \ mantle, dispel magic, mass healing word, spirit guardians\n\n**4th level (3\
      \ slots):** death ward, freedom of movement, locate creature, stoneskin\n\n\
      **5th level (1 slots):** dispel evil and good, flame strike, hold monster, greater\
      \ restoration, legend lore"
    "name": "Spellcasting"
  - "desc": "Once on each of his turns when he hits a creature with a weapon attack,\
      \ Omin can cause the attack to deal an extra 4 (1d8) damage of the same type\
      \ dealt by the weapon."
    "name": "Divine Strike"
  - "desc": "Omin has advantage on saving throws against being charmed, and magic\
      \ can't put him to sleep."
    "name": "Fey Ancestry"
"actions":
  - "desc": "Omin makes two attacks with his maul."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) bludgeoning damage."
    "name": "Maul"
"reactions":
  - "desc": "When a creature within 30 feet of Omin makes an attack roll, but before\
      \ learning whether it hits or misses, Omin can grant the creature a +10 bonus\
      \ to that roll."
    "name": "War God's Blessing (Recharges after a Short or Long Rest)"
"source":
  - "AI"
"image": "3-Mechanics/CLI/bestiary/npc/token/omin-dran-ai.webp"
```
^statblock