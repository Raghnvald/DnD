---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hat-tg
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/paladin
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Xenk Yendar"
---
# [Xenk Yendar](3-Mechanics/CLI/bestiary/npc/xenk-yendar-hat-tg.md)
*Source: Honor Among Thieves: Thieves' Gallery*  

Raised in the nation of Thay, Xenk Yendar has sworn an oath of devotion to aid the innocent. Every inch the knight in shining armor, he thrives when inspiring goodness in his allies. The words "Neither virtue nor blade shall break" are etched in Celestial on the blade of his daggersword.

Xenk ages more slowly than a normal human, and with this gift comes the burden of perspective. His longevity has something to do with Szass Tam's nightmarish rise to power and Xenk's narrow escape from the lich.

Now based in Mornbryn's Shield, Xenk travels Faerûn in search of evil to thwart. He approaches problems with absolute seriousness of purpose—an outlook that clashes with Edgin's nonchalance.

```statblock
"name": "Xenk Yendar (HAT-TG)"
"size": "Medium"
"type": "humanoid"
"subtype": "paladin"
"alignment": "Lawful Good"
"ac": !!int "15"
"ac_class": "half plate"
"hp": !!int "157"
"hit_dice": "21d8 + 63"
"modifier": !!int "0"
"stats":
  - !!int "19"
  - !!int "11"
  - !!int "16"
  - !!int "14"
  - !!int "16"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "strength": !!int "8"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "Athletics"
    "desc": "+8"
  - "name": "History"
    "desc": "+6"
  - "name": "Insight"
    "desc": "+7"
  - "name": "Survival"
    "desc": "+7"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"gear":
  - "longsword"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Thayan, Undercommon"
"cr": "10"
"traits":
  - "desc": "Xenk and his allies within 10 feet of him have advantage on saving throws."
    "name": "Aura of Protection"
"actions":
  - "desc": "Xenk makes three Daggersword attacks and uses Daggersword Flourish. He\
      \ can replace Daggersword Flourish with Cleansing Touch if it's available."
    "name": "Multiattack"
  - "desc": "Choose the attack that corresponds to the daggersword's current form\
      \ (see Daggersword Shift below):"
    "name": "Daggersword"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with\
      \ two hands, plus 6 (1d12) radiant damage."
    "name": "Longsword"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d6 + 4) piercing damage plus 6 (1d12) radiant damage."
    "name": "Shortsword and Dagger"
  - "desc": "Choose the option that corresponds to the daggersword's current form\
      \ (see Daggersword Shift below):"
    "name": "Daggersword Flourish"
  - "desc": "Xenk magically detaches the longsword's blade from its hilt, launching\
      \ the blade at a creature he can see within 30 feet of himself. The target must\
      \ make a DC 16 Dexterity saving throw. On a failed save, the target is impaled\
      \ by the blade, taking 14 (3d6 + 4) piercing damage, and is knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \ At the end of the current turn, the blade magically reattaches to its hilt."
    "name": "Longsword"
  - "desc": "Xenk lashes out with both weapons. Each creature of his choice within\
      \ 10 feet of him must make a DC 16 Dexterity throw. On a failed save, the creature\
      \ takes 7 (2d6) piercing damage and has disadvantage on attack rolls until\
      \ the start of Xenk's next turn. On a successful save, the creature takes half\
      \ as much damage and suffers no other effect."
    "name": "Shortsword and Dagger"
  - "desc": "Xenk touches a creature within 5 feet of himself. The target magically\
      \ regains 27 (6d8) hit points and gains the benefit of a lesser restoration\
      \ spell."
    "name": "Cleansing Touch (1/Day)"
"bonus_actions":
  - "desc": "Xenk changes the form of his daggersword, choosing one of the following\
      \ forms: a longsword, or a shortsword in one hand and a dagger in the other."
    "name": "Daggersword Shift"
"source":
  - "HAT-TG"
"image": "3-Mechanics/CLI/bestiary/npc/token/xenk-yendar-hat-tg.webp"
```
^statblock