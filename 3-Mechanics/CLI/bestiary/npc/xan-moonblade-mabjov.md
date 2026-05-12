---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Xan Moonblade"
---
# [Xan Moonblade](3-Mechanics/CLI/bestiary/npc/xan-moonblade-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 38*  

Xan is an elven bladesinger raised in the city of Evereska, one of the largest elven enclaves left in Faerûn, its population size second only to that of the island nation of Evermeet. With its name meaning "fortress home" in elvish, Evereska has remained hidden within the Western Heartlands for millennia. This secrecy is the major reason why the city remains as one of the last major elven enclaves in the North, whereas most others have fallen to outsiders. Because of this, Evereska is sometimes called the Last City.

Xan splits his time between his home city and the fortress library of Candlekeep. He originally encountered the monks of Candlekeep when he traveled with the Bhaalspawn, Abdel Adrian. Since then, he has found the library a comfortable second home with aims that are often aligned with that of Evereska.

Xan is one of the Blessed of Corellon and has changed gender many times over his life. His ability to change gender after an elven trance is something that he uses often, and it is usually his mercurial moods that will determine his choice.

Xan wields a moonblade forged by the smiths of Myth Drannor. Each moonblade is unique, with Xan's taking the form of a longsword wreathed in magical blue flames. Although such weapons are normally passed along elven bloodlines, Xan's sword appears specifically bound to him. Xan desires to eventually leave the mortal world and journey to Evermeet, but before he does that, he wants to find a worthy heir to his moonblade.

## Xan as a Contact

Xan is available as a contact at 9th level. Xan is able to give you access to the rarest books in Candlekeep. It is important to note that the cost of obtaining a Manual of Golems does not cover the cost of constructing the golem.

**Xan's Books and Scrolls for Sale**

| Books and Scrolls | Required Level | Cost |
|-------------------|----------------|------|
| Spell scroll—5th level spells from wizard list | 9 | 2,000 gp |
| Spell scroll—6th level spells from wizard list | 12 | 4,000 gp |
| Spell scroll—7th level spells from wizard list | 12 | 7,500 gp |
| Manual of bodily health | 15 | 30,000 gp |
| Manual of gainful exercise | 15 | 30,000 gp |
| Manual of golems—clay | 12 | 5,000 gp |
| Manual of golems—flesh | 9 | 5,000 gp |
| Manual of golems—iron | 16 | 10,000 gp |
| Manual of golems—stone | 14 | 10,000 gp |
| Manual of quickness of action | 15 | 30,000 gp |
| Tome of clear thought | 15 | 30,000 gp |
| Tome of leadership and influence | 15 | 30,000 gp |
| Tome of understanding | 15 | 30,000 gp |
^xans-books-and-scrolls-for-sale

```statblock
"name": "Xan Moonblade (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Lawful Neutral"
"ac": !!int "13"
"ac_class": "16 with [mage armor](3-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "112"
"hit_dice": "25d8"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "11"
  - !!int "17"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "6"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+9"
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+6"
  - "name": "[Performance](3-Mechanics/CLI/rules/skills.md#Performance)"
    "desc": "+6"
"gear":
  - "moonblade"
"senses": "passive Perception 11"
"languages": "Common, Elvish"
"cr": "8"
"traits":
  - "desc": "When Xan casts hideous laughter, hold person, or suggestion, the target\
      \ has disadvantage on the saving throw."
    "name": "Enchanter"
  - "desc": "Xan has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
      \ and magic can't put Xan to sleep."
    "name": "Fey Ancestry"
  - "desc": "Xan wields a Moonblade. The Moonblade has a +3 bonus to attack and damage\
      \ rolls (already factored into Xan's attacks) and has the finesse property."
    "name": "Special Equipment"
"actions":
  - "desc": "Xan makes three Moonblade attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (1d8 + 6) slashing damage or 11 (1d10 + 6) slashing damage if wielded\
      \ with two hands, plus 7 (2d6) cold or fire damage (Xan's choice)."
    "name": "Moonblade"
  - "desc": "Xan casts one of the following spells using Intelligence as the spellcasting\
      \ ability (spell save DC 14):\n\n**At will:** [acid splash](3-Mechanics/CLI/spells/acid-splash.md),\
      \ [light](3-Mechanics/CLI/spells/light.md), [mage armor](3-Mechanics/CLI/spells/mage-armor.md),\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md)\n\
      \n**2/day each:** [detect magic](3-Mechanics/CLI/spells/detect-magic.md), [Tasha's\
      \ hideous laughter](3-Mechanics/CLI/spells/tashas-hideous-laughter.md), [misty\
      \ step](3-Mechanics/CLI/spells/misty-step.md), [shield](3-Mechanics/CLI/spells/shield.md),\
      \ [suggestion](3-Mechanics/CLI/spells/suggestion.md)\n\n**1/day each:** [counterspell](3-Mechanics/CLI/spells/counterspell.md),\
      \ [fly](3-Mechanics/CLI/spells/fly.md), [greater invisibility](3-Mechanics/CLI/spells/greater-invisibility.md),\
      \ [hold person](3-Mechanics/CLI/spells/hold-person.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Xan can use a bonus action to start a bladesong. His bladesong lasts\
      \ for 1 minute. While using bladesong his movement increases to 40 ft., he gains\
      \ a +3 bonus to his AC and he gains a +3 bonus to all [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ checks."
    "name": "Bladesong (1/Day)"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/xan-moonblade-mabjov.webp"
```
^statblock