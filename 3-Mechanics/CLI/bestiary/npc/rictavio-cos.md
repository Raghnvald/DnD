---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/cos
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Rictavio"
---
# [Rictavio](3-Mechanics/CLI/bestiary/npc/rictavio-cos.md)
*Source: Curse of Strahd p. 238*  

Several months ago, a colorfully dressed half-elf bard came to Barovia in a carnival wagon, with a pet monkey on his shoulder. He took over an abandoned tower on Lake Baratok before rolling into the town of Vallaki several months later. Claiming to be a carnival ringmaster in search of new actors, he began regaling locals with tales of distant lands.

## Monster Hunter

The half-elf ringmaster is, in fact, a legendary human vampire hunter named Rudolph van Richten. Van Richten's tale is a sad one. A scholar and doctor from a land called Darkon, he married his childhood sweetheart, Ingrid, and together they had a son, Erasmus. When he was fourteen, Erasmus was stolen away by Vistani and sold to a vampire named Baron Metus to be used as a companion. By the time van Richten found his son, it was too late: the baron had already transformed Erasmus into a vampire spawn. Erasmus begged his father to end his suffering, which van Richten did by pounding a wooden stake through his son's chest. Baron Metus avenged that deed by killing van Richten's wife, and van Richten has lived with the horror of his family's destruction ever since. After destroying Baron Metus in turn, van Richten sought revenge against the Vistani and took up a life of hunting evil monsters.

## The Waiting Game

Van Richten isn't a young man anymore. He knows his road is coming to an end, but his work isn't done. He has come to Barovia to kill Strahd von Zarovich, the greatest vampire of them all. Van Richten has studied Strahd for years and knows he can't hope to best the vampire in a straight-up confrontation: he must wait for the right moment to strike. He has good evidence to suggest that Strahd periodically hibernates in his coffin, sometimes for years, when all is quiet in the realm. While he bides his time, van Richten hides in plain sight with the aid of a hat of disguise, his thoughts protected by a ring of mind shielding. He is trying to learn more about the Keepers of the Feather - a society of wereravens that oppose Strahd - while trying not to expose the secret society to their mutual enemy. He thinks the wereravens might prove helpful when the time comes. Van Richten also wants to take out as many of Strahd's spies as he can, starting with evil Vistani.

### Man with a Plan

Van Richten doesn't know that his former protégé, a good-aligned Vistana named Ezmerelda d'Avenir, has come to Barovia looking for him. He taught her many of his monster-hunting techniques, but she doesn't know all of his tricks and disguises. So far, their paths haven't crossed. In the event that van Richten becomes aware of Ezmerelda's presence, he does his utmost to protect her without putting his own plans in jeopardy. If he can manipulate a party of adventurers into keeping an eye on her, he will do so.

Van Richten works alone. A curse placed on him long ago by a Vistani seer brings doom to those he befriends. Furthermore, he believes too much is at stake to risk exposure. Consequently, if he thinks he's in danger of being unmasked, he retreats to his tower (see chapter 11) or some other quiet corner of Strahd's domain.

## Rictavio's Traits

### Ideal

"Evil cannot go unchallenged."

### Bond

"To protect those I love, I must keep them distant and hidden from my enemies."

### Flaw

"I am cursed. Thus, I will never have peace."

```statblock
"name": "Rictavio (CoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Good"
"ac": !!int "12"
"ac_class": "leather armor"
"hp": !!int "77"
"hit_dice": "14d8 + 14"
"modifier": !!int "1"
"stats":
  - !!int "9"
  - !!int "12"
  - !!int "13"
  - !!int "16"
  - !!int "18"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "constitution": !!int "4"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "Arcana"
    "desc": "+9"
  - "name": "Insight"
    "desc": "+7"
  - "name": "Medicine"
    "desc": "+7"
  - "name": "Perception"
    "desc": "+7"
  - "name": "Religion"
    "desc": "+6"
  - "name": "Sleight of Hand"
    "desc": "+4"
"senses": "passive Perception 17"
"languages": "Abyssal, Common, Elvish, Infernal"
"cr": "5"
"traits":
  - "desc": "Rictavio is a 9th-level spellcaster. His spellcasting ability is Wisdom\
      \ (spell save DC 15, +7 to hit with spell attacks). Rictavio has the following\
      \ cleric spells prepared:\n\n**Cantrips (at will):** guidance, light, mending,\
      \ thaumaturgy\n\n**1st level (4 slots):** cure wounds, detect evil and good,\
      \ protection from evil and good, sanctuary\n\n**2nd level (3 slots):** augury,\
      \ lesser restoration, protection from poison\n\n**3rd level (3 slots):** magic\
      \ circle, remove curse, speak with dead\n\n**4th level (3 slots):** death ward,\
      \ freedom of movement\n\n**5th level (1 slots):** dispel evil and good"
    "name": "Spellcasting"
  - "desc": "In addition to his sword cane, Rictavio wears a [hat of disguise](3-Mechanics/CLI/items/hat-of-disguise.md)\
      \ and a [ring of mind shielding](3-Mechanics/CLI/items/ring-of-mind-shielding.md),\
      \ and he carries a [spell scroll](3-Mechanics/CLI/items/spell-scroll-5th-level.md)\
      \ of raise dead."
    "name": "Special Equipment"
  - "desc": "When Rictavio hits an undead with a weapon attack, the undead takes an\
      \ extra 10 (3d6) damage of the weapon's type."
    "name": "Undead Slayer"
"actions":
  - "desc": "Rictavio makes two attacks with his sword cane."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4\
      \ (1d6 + 1) bludgeoning damage (wooden cane) or piercing damage (silvered\
      \ sword)."
    "name": "Sword Cane"
"source":
  - "CoS"
"image": "3-Mechanics/CLI/bestiary/npc/token/rictavio-cos.webp"
```
^statblock