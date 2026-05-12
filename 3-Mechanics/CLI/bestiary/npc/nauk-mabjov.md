---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/half-orc
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Nauk"
---
# [Nauk](3-Mechanics/CLI/bestiary/npc/nauk-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 54*  

Nauk is a half-orc warrior and senior member of the Flaming Fist in Baldur's Gate. He is also one of Faerûn's most notorious arms dealers. Nauk feeds the flames of civil strife in other nations, usually by providing assassins, mercenaries or magic. When outright war breaks out, the Flaming Fist is ready to offer their services for a hefty profit.

Nauk is one of the most well-connected members of the Flaming Fist. He has contacts and friends in almost every nation and city state in western Faerûn. Some of these come from his younger years as an adventurer, while others have been made through his arms deals.

Nauk is not above getting his hands dirty and has earned his nickname—the Bag Man. Sometimes his customers renege on a deal or are unable to pay for the services that he has provided. When this happens, Nauk enjoys making an object lesson out of the poor fool. Depending on who needs to be punished, Nauk either shows up with a small band of the Flaming Fist's hardest veterans or with a small army. No matter who he arrives with, Nauk always takes the lead.

Nauk dresses in full battle gear, even when just sitting down for a discussion with a possible client. This is because what he wears and wields are examples of what he can provide to a potential customer. This includes adamantine plate armor, multiple enchanted weapons and a dozen potions and other minor magic items. If he needs to convince a client of the effectiveness of what he has to sell, he will offer to fight the best warrior they can send at him.

## Nauk as a Contact

Nauk is the primary contact for members of the Flaming Fist at low levels. Magic items can be purchased from Nauk. He specializes in selling potions.

**Potions Available from Nauk**

| Potions | Required Level | Cost |
|---------|----------------|------|
| Potion of healing | 1 | 40 gp |
| Potion of climbing | 1 | 40 gp |
| Potion of healing—greater | 3 | 250 gp |
| Potion of fire breath | 3 | 250 gp |
| Potion of resistance | 3 | 250 gp |
| Potion of hill giant strength | 3 | 250 gp |
| Potion of water breathing | 3 | 200 gp |
| Potion of frost giant strength | 5 | 750 gp |
| Potion of heroism | 5 | 750 gp |
^potions-available-from-nauk

```statblock
"name": "Nauk (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-orc"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[plate](3-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "170"
"hit_dice": "20d8 + 80"
"modifier": !!int "1"
"stats":
  - !!int "20"
  - !!int "12"
  - !!int "18"
  - !!int "10"
  - !!int "12"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "strength": !!int "9"
  - "dexterity": !!int "5"
  - "constitution": !!int "8"
"skillsaves":
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+10"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+6"
"gear":
  - "[heavy crossbow](3-Mechanics/CLI/items/heavy-crossbow.md)"
"senses": "passive Perception 11"
"languages": "Common, Goblin, Orc, Undercommon"
"cr": "9"
"traits":
  - "desc": "When Nauk uses the Imbibe Potion action more than once in an hour, roll\
      \ 1d4 for what happens:\n\n- 1. The potion works normally.  \n- 2. The potion\
      \ works normally. In addition, Nauk turns [invisible](3-Mechanics/CLI/rules/conditions.md#Invisible)\
      \ for 1 minute or until Nauk attacks or casts a spell.  \n- 3. The potion has\
      \ no effect.  \n- 4. Instead of the normal effect, the potion causes fire to\
      \ explode out of Nauk's mouth in a 15 foot cone. Nauk and any creature in the\
      \ cone take 21 (6d6) fire damage.  "
    "name": "Potion Mishap"
  - "desc": "When Nauk is reduced to 0 hit points but not killed outright, he can\
      \ drop to 1 hit point instead. He can't use this feature again for 24 hours"
    "name": "Relentless"
  - "desc": "Nauk wears adamantine plate armor. He wields a +1 maul and a +1 heavy\
      \ crossbow which is already factored into his stats. He has 2 potions of resistance\
      \ (cold), 2 potions of resistance (fire), 2 potions of resistance (lightning).\
      \ He has 2 potions of heroism and 4 potions of superior healing."
    "name": "Special Items"
"actions":
  - "desc": "Nauk makes three Magic Maul attacks. Nauk may substitute one of those\
      \ attacks for the Imbibe Potion action."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one creature. *Hit:*\
      \ 13 (2d6 + 6) bludgeoning damage."
    "name": "Magic Maul"
  - "desc": "*Ranged Weapon Attack:* +6 to hit, ranged 100/400 ft., one target.\
      \ *Hit:* 7 (1d10 + 2) piercing damage."
    "name": "Heavy Crossbow"
  - "desc": "Nauk drinks a potion from the following list:\n\n- Potion of heroism:\
      \ Nauk gains 10 temporary hit points for 1 hour. For the same duration, Nauk\
      \ is under the effect of the [bless](3-Mechanics/CLI/spells/bless.md) spell\
      \ (no [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration) required).\
      \  \n- Potion of resistance: Nauk gains resistance from one damage type for\
      \ 1 hour. Nauk chooses from one of these damage types: cold, fire, lightning.\
      \  \n- Potion of superior healing: Nauk regains 28 hit points.  "
    "name": "Imbibe Potion"
"reactions":
  - "desc": "Nauk adds 4 to his AC against one melee attack that would hit him. To\
      \ do so, Nauk must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/nauk-mabjov.webp"
```
^statblock