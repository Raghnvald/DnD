---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - monster/cr/4
  - monster/size/small
  - monster/type/aberration/goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Goblin Psi Commander
---
# [Goblin Psi Commander](3-Mechanics\CLI\bestiary\aberration/goblin-psi-commander-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 216*  

Goblin psi commanders are among the few psionic goblins who manage to fully control the power within themselves. Awakened to the total breadth of their psionic abilities, goblin psi commanders wield blades of pure psychic energy. They can throw barriers of mental force while toppling foes with a single, mind-splitting burst.

## Psionic Goblins

The specifics of how a psionic goblin comes to exist vary. Some are born, changed by energy leaking from the Far Realm. Others transform themselves with their psionic power or enter into agreements with other Aberrations, which help them transform in return for their service as shock troops. Regardless, the result is the same: a goblin with unnatural and barely contained psychic power.

Psionic goblins often struggle to handle the turbulent psychic energy within their minds and bodies. Those psionic goblins who learn how to safely tap into this psychic power are formidable forces in combat. Psionic goblins often augment their martial skills with telekinesis, and stealthy squads of psionic goblin warriors can communicate via telepathy, making them excellent infiltrators and ambushers.

```statblock
"name": "Goblin Psi Commander (PaBTSO)"
"size": "Small"
"type": "aberration"
"subtype": "goblinoid"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[studded leather armor](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "58"
"hit_dice": "13d6 + 13"
"modifier": !!int "4"
"stats":
  - !!int "12"
  - !!int "19"
  - !!int "13"
  - !!int "17"
  - !!int "15"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+8"
"damage_resistances": "psychic"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 12"
"languages": "Common, Goblin, telepathy 60 ft."
"cr": "4"
"traits":
  - "desc": "When the goblin dies, its pent-up mental energy explodes in a psychic\
      \ blast. Each creature within 5 feet of it must succeed on a DC 13 Intelligence\
      \ saving throw or take 10 (4d4) psychic damage."
    "name": "Mental Burst"
  - "desc": "The goblin has advantage on saving throws against effects that would\
      \ make it have the [charmed](/3-Mechanics/CLI/conditions.md#Charmed) or [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ conditions."
    "name": "Mental Fortitude"
"actions":
  - "desc": "The goblin makes three Psychic Blade attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 60\
      \ ft., one creature. *Hit:* 11 (2d6 + 4) psychic damage, and the target must\
      \ subtract 1d4 from the next attack roll or saving throw it makes before the\
      \ end of the goblin's next turn."
    "name": "Psychic Blade"
  - "desc": "The goblin unleashes a 30-foot-radius sphere of psychic energy, centered\
      \ on a point the goblin can see within 60 feet of itself. Each creature in that\
      \ area must make a DC 13 Intelligence saving throw. On a failed save, a creature\
      \ takes 14 (4d6) psychic damage and has the [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ condition until the end of the goblin's next turn. On a successful save, a\
      \ creature takes half as much damage only."
    "name": "Synaptic Rend (Recharge 5-6)"
  - "desc": "The goblin casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 13):\n\n\
      **At will:** [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md) (the hand\
      \ is invisible), [minor illusion](/3-Mechanics/CLI/spells/minor-illusion-xphb.md)\n\
      \n**1/day each:** [charm person](/3-Mechanics/CLI/spells/charm-person-xphb.md),\
      \ [dissonant whispers](/3-Mechanics/CLI/spells/dissonant-whispers-xphb.md),\
      \ [telekinesis](/3-Mechanics/CLI/spells/telekinesis-xphb.md)"
    "name": "Spellcasting (Psionics)"
"bonus_actions":
  - "desc": "The goblin takes the Disengage or Hide action."
    "name": "Nimble Escape"
"reactions":
  - "desc": "When the goblin or one of its allies within 15 feet of it is hit by an\
      \ attack roll, the goblin conjures a shield of force. The target of the attack\
      \ gains a +3 bonus to its AC against the triggering attack roll, potentially\
      \ causing it to miss."
    "name": "Psionic Shield"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/goblin-psi-commander-pabtso.webp"
```
^statblock