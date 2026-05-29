---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: The Lord of Blades
linter-yaml-title-alias: The Lord of Blades
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/18
  - Monster/Typ/Humanoid/warforged
  - Quelle/5e/erlw
aliases:
  - The Lord of Blades
---
# [The Lord of Blades](3-Mechanics\CLI\bestiary\npc/the-lord-of-blades-erlw.md)
*Source: Eberron: Rising from the Last War p. 300*  

The Lord of Blades is a warforged warlord who has broken all ties with his former masters. He has established a nation for his people deep in the Mournland, centered in a great fortress where warforged from all over Khorvaire can come and feel a sense of belonging. No one knows what the Lord of Blades plans for his followers, but many fear that he intends to build a legion of warforged zealots, primed to march from the Mournland to unleash destruction on their former masters.

Some tales assert that the Lord of Blades led the warforged armies of Cyre in the Last War. Others cast him as a newer warforged, perhaps the last to come out of the Cannith creation forges before the Thronehold Accords led to their dismantling. One story claims the Lord of Blades caused the destruction of Cyre and warns that he plans to repeat the Day of Mourning in each of the remaining Five Nations. Whatever the truth, he has become a beacon for warforged everywhere.

## Warforged Nature

The Lord of Blades doesn't require air, food, drink, or sleep.

```statblock
"name": "The Lord of Blades (ERLW)"
"size": "Medium"
"type": "humanoid"
"subtype": "warforged"
"alignment": "Lawful Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "23d8 + 92"
"modifier": !!int "2"
"stats":
  - !!int "20"
  - !!int "15"
  - !!int "18"
  - !!int "19"
  - !!int "17"
  - !!int "18"
"speed": "40 ft."
"saves":
  - "strength": !!int "11"
  - "constitution": !!int "10"
  - "intelligence": !!int "10"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "Arcana"
    "desc": "+10"
  - "name": "Athletics"
    "desc": "+11"
  - "name": "History"
    "desc": "+10"
  - "name": "Perception"
    "desc": "+9"
"damage_resistances": "necrotic, poison"
"condition_immunities": "charmed, exhaustion, frightened, disease"
"senses": "passive Perception 19"
"languages": "Common, Draconic, Dwarvish, Elvish"
"cr": "18"
"traits":
  - "desc": "The Lord of Blades is a 20th-level spellcaster. His spellcasting ability\
      \ is Intelligence (spell save DC 18, +10 to hit with spell attacks). He has\
      \ the following artificer spells prepared:\n\n**Cantrips (at will):** fire bolt\
      \ (see \"Actions\" below), mage hand, mending, prestidigitation\n\n**1st level\
      \ (4 slots):** expeditious retreat, sanctuary, thunderwave\n\n**2nd level (3\
      \ slots):** blur, heat metal, scorching ray, see invisibility\n\n**3rd level\
      \ (3 slots):** dispel magic, fly, haste\n\n**4th level (3 slots):** freedom\
      \ of movement, Mordenkainen's faithful hound\n\n**5th level (2 slots):** animate\
      \ objects, wall of force"
    "name": "Spellcasting"
  - "desc": "Any critical hit against the Lord of Blades becomes a normal hit."
    "name": "Adamantine Plating"
  - "desc": "A creature that grapples the Lord of Blades or is grappled by him takes\
      \ 13 (3d8) slashing damage. A creature takes 13 (3d8) slashing damage if it\
      \ starts its turn grappling or being grappled by the Lord of Blades."
    "name": "Bladed Armor"
  - "desc": "If the Lord of Blades moves at least 10 feet straight toward a target\
      \ and then hits it with his adamantine sixblade on the same turn, the target\
      \ takes an extra 11 (2d10) slashing damage. If the target is a creature, it\
      \ must succeed on a DC 19 Strength saving throw or be pushed up to 10 feet away\
      \ and knocked prone."
    "name": "Charge"
  - "desc": "The Lord of Blades has advantage on saving throws against being poisoned,\
      \ is immune to disease, and magic can't put him to sleep."
    "name": "Warforged Resilience"
"actions":
  - "desc": "The Lord of Blades makes three attacks: two with his adamantine sixblade\
      \ and one with his bladed wings."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target. *Hit:* 21\
      \ (3d10 + 5) slashing damage plus 7 (2d6) force damage."
    "name": "Adamantine Sixblade"
  - "desc": "*Melee  or Ranged Weapon Attack:* +11 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 8 (1d6 + 5) slashing damage."
    "name": "Bladed Wings"
  - "desc": "*Ranged Spell Attack:* +10 to hit, range 120 ft., one target. *Hit:*\
      \ 22 (4d10) fire damage."
    "name": "Fire Bolt (Cantrip)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, The Lord of Blades can expend a use to take one of the following actions.\
  \ The Lord of Blades regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The Lord of Blades makes one weapon attack."
    "name": "Attack"
  - "desc": "The Lord of Blades casts one of his cantrips."
    "name": "Cantrip"
  - "desc": "The Lord of Blades casts a spell of 2nd level or lower from his spell\
      \ list that takes 1 action to cast."
    "name": "Cast a Spell (Costs 2 Actions)"
  - "desc": "The Lord of Blades moves up to his speed without provoking opportunity\
      \ attacks, then makes one attack with his adamantine sixblade. He can make one\
      \ bladed wings attack against each creature he moves past."
    "name": "Blade Dash (Costs 3 Actions)"
"source":
  - "ERLW"
"image": "/3-Mechanics/CLI/bestiary/npc/token/the-lord-of-blades-erlw.webp"
```
^statblock