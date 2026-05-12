---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/tiefling
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Vanifer"
---
# [Vanifer](3-Mechanics/CLI/bestiary/npc/vanifer-pota.md)
*Source: Princes of the Apocalypse p. 203*  

Vanifer's rough childhood has hardened her heart against others. The world is a corrupt, painful place, she thinks, and deserving of a fiery end. For years, she was a dancer and concubine in a pasha's court in Calimshan. Later, she took up the mantle of prophet when she found Tinderstrike, and the same ruthless ambition and practiced manipulation that enabled her to escape a life of servitude serves her well as the head of a growing cult.

For Vanifer, battle is best observed at a distance. She prefers to hurl destructive magic from afar. Those who challenge Vanifer in melee learn a painful lesson, as she and Tinderstrike make a formidable pair.

In the Fire Node

When enemies threaten the Temple of Eternal Flame, Vanifer withdraws to the Weeping Colossus, the fire node. Within this node, Vanifer gains one additional use of her Legendary Resistance trait.

```statblock
"name": "Vanifer (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "tiefling"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "17"
  - !!int "12"
  - !!int "13"
  - !!int "19"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+8"
  - "name": "[Performance](3-Mechanics/CLI/rules/skills.md#Performance)"
    "desc": "+8"
"damage_immunities": "fire"
"gear":
  - "[tinderstrike](3-Mechanics/CLI/items/tinderstrike-pota.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 11"
"languages": "Common, Ignan, Infernal"
"cr": "9"
"traits":
  - "desc": "Vanifer is a 10th-level spellcaster. Her spellcasting ability is Charisma\
      \ (spell save DC 16, +8 to hit with spell attacks). Vanifer knows the following\
      \ sorcerer spells:\n\n**Cantrips (at will):** [chill touch](3-Mechanics/CLI/spells/chill-touch.md),\
      \ [fire bolt](3-Mechanics/CLI/spells/fire-bolt.md), [friends](3-Mechanics/CLI/spells/friends.md),\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand.md), [message](3-Mechanics/CLI/spells/message.md),\
      \ [produce flame](3-Mechanics/CLI/spells/produce-flame.md), [thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy.md)\n\
      \n**1st level (4 slots):** [burning hands](3-Mechanics/CLI/spells/burning-hands.md),\
      \ [chromatic orb](3-Mechanics/CLI/spells/chromatic-orb.md), [hellish rebuke](3-Mechanics/CLI/spells/hellish-rebuke.md),\
      \ [shield](3-Mechanics/CLI/spells/shield.md)\n\n**2nd level (3 slots):** [darkness](3-Mechanics/CLI/spells/darkness.md),\
      \ [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts.md), [misty step](3-Mechanics/CLI/spells/misty-step.md),\
      \ [scorching ray](3-Mechanics/CLI/spells/scorching-ray.md)\n\n**3rd level (3\
      \ slots):** [counterspell](3-Mechanics/CLI/spells/counterspell.md), [fireball](3-Mechanics/CLI/spells/fireball.md),\
      \ [hypnotic pattern](3-Mechanics/CLI/spells/hypnotic-pattern.md)\n\n**4th level\
      \ (3 slots):** [wall of fire](3-Mechanics/CLI/spells/wall-of-fire.md)\n\n**5th\
      \ level (2 slots):** [dominate person](3-Mechanics/CLI/spells/dominate-person.md)"
    "name": "Spellcasting"
  - "desc": "When Vanifer drops to 0 hit points, her body is consumed in a flash of\
      \ fire and smoke. Anything she was wearing or carrying is left behind among\
      \ ashes."
    "name": "Funeral Pyre"
  - "desc": "If Vanifer fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (2/Day)"
"actions":
  - "desc": "Vanifer makes two attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +9 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 7 (1d4 + 5) piercing damage plus 7 (2d6) fire\
      \ damage."
    "name": "Tinderstrike"
"lair_actions":
  - "desc": "If Vanifer is in the fire node while [Imix](3-Mechanics/CLI/bestiary/npc/imix-pota.md)\
      \ isn't, the tiefling can take lair actions. On initiative count 20 (losing\
      \ initiative ties), Vanifer uses a lair action to cast one of her spells, up\
      \ to 3rd level, without using components or a spell slot. She can't cast the\
      \ same spell two rounds in a row, although she can continue to concentrate on\
      \ a spell she previously cast using a lair action. Vanifer can take no other\
      \ lair actions while [concentrating](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on a spell cast as a lair action. Her favorite use of this capability is casting\
      \ [fireball](3-Mechanics/CLI/spells/fireball.md) or [hypnotic pattern](3-Mechanics/CLI/spells/hypnotic-pattern.md).\n\
      \nIf Vanifer casts [misty step](3-Mechanics/CLI/spells/misty-step.md) using\
      \ this lair action, she also draws the power of the fire node into herself.\
      \ By doing so, she regains 15 (3d8 + 2) hit points."
    "name": ""
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/vanifer-pota.webp"
```
^statblock