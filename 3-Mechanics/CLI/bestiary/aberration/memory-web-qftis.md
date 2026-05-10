---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Memory Web"
---
# [Memory Web](3-Mechanics/CLI/bestiary/aberration/memory-web-qftis.md)
*Source: Quests from the Infinite Staircase p. 208*  

A memory web is a living web that resembles an ordinary web spun by an ettercap, a giant spider, or another oversized arachnid. Memory webs lie in ambush draped over plant life, wrapped around corpses, or stuck to ossuaries in dark catacombs.

Memory webs feed on memories and require daily sustenance. When a memory web's prey draws close, the web springs at the creature and wraps it in sticky, cord-like fibers. The web then drains its victim's memories, sapping the creature's life force in the process. A memory web can continue to feed on a corpse's memories for days after its death.

If a memory web is slain, any memories it consumed over the last day are discharged from its body in a telepathic deluge. Some of these memories lodge themselves in the minds of nearby creatures as dreamlike recollections, potentially spurring their inheritors to action. The Memory Web Memories table presents adventure seeds that might be released by a slain memory web.

| dice: d4 | Memory |
|----------|--------|
| 1 | The location of a powerful magic item |
| 2 | A secret betrayal by a beloved public figure |
| 3 | The details of an unfinished quest |
| 4 | A revelation about an impending upheaval |
^memory

```statblock
"name": "Memory Web (QftIS)"
"size": "Large"
"type": "aberration"
"alignment": "typically  Neutral Evil"
"ac": !!int "14"
"hp": !!int "39"
"hit_dice": "6d10 + 6"
"modifier": !!int "4"
"stats":
  - !!int "16"
  - !!int "18"
  - !!int "13"
  - !!int "14"
  - !!int "14"
  - !!int "3"
"speed": "40 ft., climb 40 ft."
"damage_resistances": "fire"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (can't\
  \ see beyond this radius), passive Perception 12"
"languages": ""
"cr": "4"
"traits":
  - "desc": "While it is grappling a creature, the memory web takes only half the\
      \ damage dealt to it, and the creature [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by the web takes the other half."
    "name": "Damage Transfer"
  - "desc": "If the memory web is motionless at the start of combat, it has advantage\
      \ on its initiative roll. Moreover, if a creature hasn't observed the memory\
      \ web move or act, that creature must succeed on a DC 18 Intelligence ([Investigation](3-Mechanics/CLI/rules/skills.md#Investigation))\
      \ check to discern that the memory web is animate."
    "name": "False Appearance"
  - "desc": "When the memory web is reduced to 0 hit points, it discharges any memories\
      \ it consumed over the past 24 hours in a telepathic deluge. Hazy, dreamlike\
      \ visions of these discharged memories lodge in the minds of creatures up to\
      \ 120 feet from the memory web."
    "name": "Memory Flood"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one Large or smaller\
      \ creature. *Hit:* The target has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition (escape DC 13). Until this grapple ends, the target has the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ condition and takes 7 (1d8 + 3) bludgeoning damage at the start of each\
      \ of its turns. The memory web can grapple only one creature at a time."
    "name": "Ensnare"
"bonus_actions":
  - "desc": "The memory web targets one creature [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by it. The target must make a DC 12 Intelligence saving throw. Constructs,\
      \ Oozes, Plants, and Undead succeed on the save automatically. On a failed save,\
      \ the target takes 5 (2d4) psychic damage and becomes memory drained until\
      \ it finishes a long rest or the memory web is destroyed.\n\nWhile memory drained,\
      \ the target must roll a d4 each time it makes an ability check or attack\
      \ roll, subtracting the d4 roll from it. Each time the target is memory drained\
      \ beyond the first, the die size increases by one: the d4 becomes a d6,\
      \ the d6 becomes a d8, and so on until the die becomes a d20, at which\
      \ point the target has the [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
      \ condition for 1 hour. If a memory drained creature is the target of the Greater\
      \ Restoration or [Heal](3-Mechanics/CLI/spells/heal.md) spell, the memory drained\
      \ effect ends on it. On a successful save, the target takes half as much damage\
      \ only."
    "name": "Drain Memories"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/aberration/token/memory-web-qftis.webp"
```
^statblock