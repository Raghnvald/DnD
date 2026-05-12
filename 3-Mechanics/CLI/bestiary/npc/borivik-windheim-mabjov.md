---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Borivik Windheim"
---
# [Borivik Windheim](3-Mechanics/CLI/bestiary/npc/borivik-windheim-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 56*  

Borovik Windheim is a skilled ranger and undead hunter originally from the distant lands of Oerth. He was a scout for the ancient Order of the Heart. Long ago, Borovik was leading a small band of the Order of the Heart when a strange mist rose and carried them to the Shadowfell. One by one, the horrors of that land took Borovik's companions, until Borovik was the lone survivor. Borovik blamed himself for the deaths of so many of his close friends, but he never succumbed to despair.

Borovik's will to survive allowed him to cease being the hunted and instead become the hunter. He learned everything he could in a land overrun with undead and aberrations of nature. During his time in the Shadowfell he became a master at hunting and killing undead. He even was mentored by the famous vampire hunter, Rudolph Van Richten. He also forged a friendship with two men who would become his closest companions, Lothar an Uthgardt barbarian and Viktor a holy warrior.

Borovik comes across as eccentric and strange to those that don't know him well. At times, Borovik will have one sided conversations with his long dead companions from the Order of the Heart. It is a coping mechanism that he learned during his time in the Shadowfell and also a way for him to keep their memory alive.

With the help of his companion Lothar, Borivik escaped the Shadowfell to the world of Faerûn. There he came into contact with the Flaming Fist. They helped him recover from the horrors he had endured in the Shadowfell and in recompense, Borivik became one of their most ardent supporters.

Borivik's weapon of choice is a heavy crossbow. He carries with him a wide array of ammunition and other paraphernalia designed to kill all kinds of monsters with a focus on items that can be used on denizens of the Shadowfell. He is willing to share his experience in fighting the undead with any who express interest.

## Borivik as a Contact

Borivik becomes available as a contact for the Flaming Fist at 7th level.

**Ammunition Available from Nauk**

| Ammunition | Required Level | Cost |
|------------|----------------|------|
| Ammunition, +1 | 1 | 50 gp per ammunition |
| Antitoxin | 1 | 30 gp |
| Holy water | 1 | 10 gp |
| Ammunition, +2 | 9 | 200 gp per ammunition |
| Oil of slipperiness | 9 | 250 gp |
| Dust of disappearance | 9 | 300 gp |
| Dust of dryness | 9 | 200 gp |
| Ring of resistance—necrotic | 9 | 1000 gp |
| Ammunition, +3 | 12 | 1000 gp per ammunition |
| Arrow/bolt of undead slaying | 14 | 5000 gp per ammunition |
^ammunition-available-from-nauk

```statblock
"name": "Borivik Windheim (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Good"
"ac": !!int "17"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "195"
"hit_dice": "30d8 + 60"
"modifier": !!int "5"
"stats":
  - !!int "11"
  - !!int "20"
  - !!int "14"
  - !!int "11"
  - !!int "16"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "9"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Nature](3-Mechanics/CLI/rules/skills.md#Nature)"
    "desc": "+8"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+11"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+13"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+11"
"gear":
  - "[heavy crossbow](3-Mechanics/CLI/items/heavy-crossbow.md)"
  - "[shortsword](3-Mechanics/CLI/items/shortsword.md)"
"senses": "passive Perception 21"
"languages": "Common, Elvish, Sylvan"
"cr": "10"
"traits":
  - "desc": "Borivik has a half-dozen bolts of undead slaying. If he strikes an Undead\
      \ creature with one of these magic bolts, it must make a DC 17 Constitution\
      \ saving throw, taking an extra 33 (6d10) piercing damage on a failed save,\
      \ or half as much extra damage on a successful one."
    "name": "Bolts of Undead Slaying"
"actions":
  - "desc": "Borivik makes two Shortsword attacks or two Heavy Crossbow attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d6 + 5) piercing damage."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +9 to hit, ranged 100/400 ft., one target.\
      \ *Hit:* 10 (1d10 + 5) piercing damage."
    "name": "Heavy Crossbow"
  - "desc": "Borivik casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 15):\n\n**At will:** [ensnaring strike](3-Mechanics/CLI/spells/ensnaring-strike.md),\
      \ [speak with animals](3-Mechanics/CLI/spells/speak-with-animals.md)\n\n**2/day\
      \ each:** [cordon of arrows](3-Mechanics/CLI/spells/cordon-of-arrows.md), [daylight](3-Mechanics/CLI/spells/daylight.md),\
      \ [lesser restoration](3-Mechanics/CLI/spells/lesser-restoration.md), [nondetection](3-Mechanics/CLI/spells/nondetection.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Borivik adds 1d10 to his next attack or damage roll with his Heavy\
      \ Crossbow attack."
    "name": "Crossbow Expert"
  - "desc": "Borivik can take the [Disengage](3-Mechanics/CLI/rules/actions.md#Disengage)\
      \ or [Hide](3-Mechanics/CLI/rules/actions.md#Hide) action."
    "name": "Nimble Escape"
"reactions":
  - "desc": "When Borivik takes acid, cold, fire, lightning, or thunder damage, he\
      \ gains immunity to that damage type until the start of his next turn. Also,\
      \ the first time he hits with a Shortsword attack on his next turn, the target\
      \ takes an extra 10 (3d6) of the triggering damage type."
    "name": "Enduring Response"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/borivik-windheim-mabjov.webp"
```
^statblock