---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psi
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Keeper of the Feather"
---
# [Keeper of the Feather](3-Mechanics/CLI/bestiary/humanoid/keeper-of-the-feather-psi.md)
*Source: Plane Shift: Innistrad p. 40*  

```statblock
"name": "Keeper of the Feather (PSI)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, shapechanger"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "31"
"hit_dice": "7d8"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "15"
  - !!int "11"
  - !!int "13"
  - !!int "15"
  - !!int "14"
"speed": "30 ft. (fly 50 ft. in raven and hybrid forms)"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
"gear":
  - "[hand crossbow](3-Mechanics/CLI/items/hand-crossbow.md)"
  - "[shortsword](3-Mechanics/CLI/items/shortsword.md)"
"senses": "passive Perception 16"
"languages": "Common (can't speak in raven form)"
"cr": "2"
"traits":
  - "desc": "The keeper is a 4th-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 12, +4 to hit with spell attacks). It has the following druid\
      \ spells prepared:\n\n**Cantrips (at will):** [druidcraft](3-Mechanics/CLI/spells/druidcraft.md),\
      \ [produce flame](3-Mechanics/CLI/spells/produce-flame.md), [shillelagh](3-Mechanics/CLI/spells/shillelagh.md)\n\
      \n**1st level (4 slots):** [entangle](3-Mechanics/CLI/spells/entangle.md), [longstrider](3-Mechanics/CLI/spells/longstrider.md),\
      \ [speak with animals](3-Mechanics/CLI/spells/speak-with-animals.md), [thunderwave](3-Mechanics/CLI/spells/thunderwave.md)\n\
      \n**2nd level (3 slots):** [animal messenger](3-Mechanics/CLI/spells/animal-messenger.md),\
      \ [barkskin](3-Mechanics/CLI/spells/barkskin.md)"
    "name": "Spellcasting"
  - "desc": "The keeper can use its action to polymorph into a raven-humanoid hybrid\
      \ or into a raven, or back into its human form. Its statistics, other than its\
      \ size, are the same in each form. Any equipment it is wearing or carrying isn't\
      \ transformed. It reverts to its human form if it dies."
    "name": "Shapechanger"
  - "desc": "The keeper can mimic simple sounds it has heard, such as a person whispering,\
      \ a baby crying, or an animal chittering. A creature that hears the sounds can\
      \ tell they are imitations with a successful DC 10 Wisdom ([Insight](3-Mechanics/CLI/rules/skills.md#Insight))\
      \ check."
    "name": "Mimicry"
  - "desc": "The keeper regains 10 hit points at the start of its turn. If the keeper\
      \ takes damage from a silvered weapon or a spell, this trait doesn't function\
      \ at the start of the keeper's next turn. The keeper dies only if it starts\
      \ its turn with 0 hit points and doesn't regenerate."
    "name": "Regeneration"
"actions":
  - "desc": "The keeper makes two weapon attacks, one of which can be with its hand\
      \ crossbow."
    "name": "Multiattack (Human or Hybrid Form Only)"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 1\
      \ piercing damage in raven form, or 4 (1d4 + 2) piercing damage in hybrid\
      \ form."
    "name": "Beak (Raven or Hybrid Form Only)"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage."
    "name": "Shortsword (Human or Hybrid Form Only)"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 30/120 ft., one target. *Hit:*\
      \ 5 (1d6 + 2) piercing damage."
    "name": "Hand Crossbow (Human or Hybrid Form Only)"
"source":
  - "PSI"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/keeper-of-the-feather-psi.webp"
```
^statblock