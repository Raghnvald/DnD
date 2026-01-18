---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mcv3mc
  - Monster/HG/19
  - Monster/Größe/Gigantisch
  - Monster/Typ/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Ender Dragon
---
# [Ender Dragon](3-Mechanics\CLI\bestiary\dragon/ender-dragon-mcv3mc.md)
*Source: Monstrous Compendium Volume 3: Minecraft Creatures p. 5*  

The mighty Ender Dragon is one of a kind—a vast, flying creature with void-black scales and purple eyes. It soars above the central island of the End. No one can say whether it is a guardian or a prisoner of the End, but either way, the Ender Dragon challenges anyone who enters its domain.

The Ender Dragon buffets enemies with great wings, engulfs foes with its gaseous breath weapon, and delivers crushing bites with its powerful jaws. Its hide is strong enough to deflect all but the deadliest weapons.

> [!note] End Crystals
> 
> The Ender Dragon has a special relationship with the ten 40-foot-tall obsidian towers scattered around the central island of the End. At the top of each tower is an End crystal that sends a beam of healing energy to the Ender Dragon when it flies nearby. If slain, the Ender Dragon can be brought back to life by placing four End crystals on the portal that leads back to the Overworld.
> 
> **Crystal Healing.** When the Ender Dragon ends its turn within 60 feet of an End crystal, the crystal emits a healing beam that causes the dragon to regain 20 hit points. The dragon can benefit from such healing only once per turn.
> 
> **Crystal Statistics.** An End crystal is a Large object that has Armor Class 11; 30 hit points; vulnerability to bludgeoning and thunder damage; resistance to piercing and slashing damage; and immunity to poison and psychic damage. When a crystal is destroyed, it explodes in a 20-foot-radius sphere of destructive energy. Any creature in that area must make a DC 15 Dexterity saving throw, taking `dice:6d6|noform|noparens|avg|text(21)` (`6d6`) force damage on a failed save, or half as much damage on a successful one.
^end-crystals

```statblock
"name": "Ender Dragon (MCV3MC)"
"size": "Gargantuan"
"type": "dragon"
"alignment": "Chaotic Evil"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "350"
"hit_dice": "20d20 + 140"
"modifier": !!int "2"
"stats":
  - !!int "27"
  - !!int "14"
  - !!int "25"
  - !!int "10"
  - !!int "15"
  - !!int "19"
"speed": "30 ft., fly 120 ft."
"saves":
  - "constitution": !!int "13"
  - "intelligence": !!int "6"
  - "wisdom": !!int "8"
"skillsaves":
  - "name": "Perception"
    "desc": "+14"
  - "name": "Stealth"
    "desc": "+8"
"damage_resistances": "fire"
"damage_immunities": "necrotic"
"condition_immunities": "charmed, frightened"
"senses": "darkvision 240 ft., passive Perception 24"
"languages": "Draconic"
"cr": "19"
"traits":
  - "desc": "When the Ender Dragon drops to 0 hit points, it radiates beams of purple\
      \ light and then disappears, leaving behind an inert, jet-black dragon egg worth\
      \ 5,000 gp."
    "name": "Dragon Egg"
  - "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day)"
"actions":
  - "desc": "The dragon makes one Bite attack and uses Beating Wings."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit; reach 15 ft., one target. *Hit:* 18\
      \ (3d6 + 8) piercing damage plus 7 (2d6) necrotic damage."
    "name": "Bite"
  - "desc": "The dragon beats its great wings. Each creature within 15 feet of the\
      \ dragon must succeed on a DC 21 Dexterity saving throw or take 10 (1d4 + 8)\
      \ bludgeoning damage, be pushed 10 feet away from the dragon, and have the prone\
      \ condition."
    "name": "Beating Wings"
  - "desc": "The dragon exhales putrid gas in a 60-foot cone. Each creature in that\
      \ area must make a DC 21 Constitution saving throw, taking 52 (15d6) necrotic\
      \ damage on a failed save, or half as much damage on a successful one. The dragon\
      \ then chooses a point it can see where the cone makes contact with the ground.\
      \ That point becomes the center of a 10-foot-high, 10-foot-radius cylinder of\
      \ lingering gas that disappears at the start of the dragon's next turn. Any\
      \ creature that starts its turn in the cylinder takes 10 (3d6) necrotic damage."
    "name": "Harmful Breath (Recharge 5-6)"
"source":
  - "MCV3MC"
"image": "/3-Mechanics/CLI/bestiary/dragon/token/ender-dragon-mcv3mc.webp"
```
^statblock