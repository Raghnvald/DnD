---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Aerisi Kalinoth"
---
# [Aerisi Kalinoth](3-Mechanics/CLI/bestiary/npc/aerisi-kalinoth-pota.md)
*Source: Princes of the Apocalypse p. 192*  

Aerisi Kalinoth is the air prophet of the Elder Elemental Eye and leader of the Cult of the Howling Hatred. Tall and slender, with dark hair and (illusory) feathered wings that gently fan the air, Aerisi Kalinoth speaks to her people in a whisper that belies her violent temper, which reveals itself whenever she is denied.

Aerisi was a sheltered moon elf princess named Dara Algwynenn Kalinoth who grew up in a remote Faerie realm. Her parents had wished to protect her from the harsh realities of the world, but they only succeeded in spoiling her. When they tried to discipline their wilful daughter, she used the power of elemental air against them. Soon after, her dreams led her to the ancient dwarven ruins where the spear Windvane awaited her.

Dara changed her name to Aerisi and pretended to be an avariel (winged elf) princess like the ones from her storybooks. Then Aerisi used her talents for enchantment magic to sway mortals into joining her cult. She has convinced all her followers that she is in fact an avariel, and believes it herself even though she must cast [seeming](3-Mechanics/CLI/spells/seeming.md) each day to "reveal" her wings.

Aerisi is prone to deluded flights of fancy and impulsive decadence. She sees herself as a beautiful, fierce, and just ruler who wields elemental power because she deserves it.

## In the Air Node

When danger threatens the Temple of Howling Hatred, Aerisi retreats to the Howling Caves, the air node. Within this node, Aerisi gains one additional use of her Legendary Resistance trait.

```statblock
"name": "Aerisi Kalinoth (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "16 with [mage armor](3-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"modifier": !!int "3"
"stats":
  - !!int "8"
  - !!int "16"
  - !!int "12"
  - !!int "17"
  - !!int "10"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+6"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
"damage_resistances": "lightning"
"gear":
  - "[windvane](3-Mechanics/CLI/items/windvane-pota.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "Auran, Common, Elvish"
"cr": "7"
"traits":
  - "desc": "Aerisi is a 12th-level spellcaster. Her spellcasting ability is Intelligence\
      \ (spell save DC 14, +6 to hit with spell attacks). Aerisi has the following\
      \ wizard spells prepared:\n\n**Cantrips (at will):** gust, [mage hand](3-Mechanics/CLI/spells/mage-hand.md),\
      \ [message](3-Mechanics/CLI/spells/message.md), [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md),\
      \ [ray of frost](3-Mechanics/CLI/spells/ray-of-frost.md), [shocking grasp](3-Mechanics/CLI/spells/shocking-grasp.md)\n\
      \n**1st level (4 slots):** [charm person](3-Mechanics/CLI/spells/charm-person.md),\
      \ [feather fall](3-Mechanics/CLI/spells/feather-fall.md), [mage armor](3-Mechanics/CLI/spells/mage-armor.md),\
      \ [thunderwave](3-Mechanics/CLI/spells/thunderwave.md)\n\n**2nd level (3 slots):**\
      \ dust devil, [gust of wind](3-Mechanics/CLI/spells/gust-of-wind.md), [invisibility](3-Mechanics/CLI/spells/invisibility.md)\n\
      \n**3rd level (3 slots):** [fly](3-Mechanics/CLI/spells/fly.md), [gaseous form](3-Mechanics/CLI/spells/gaseous-form.md),\
      \ [lightning bolt](3-Mechanics/CLI/spells/lightning-bolt.md)\n\n**4th level\
      \ (3 slots):** [ice storm](3-Mechanics/CLI/spells/ice-storm.md), storm sphere\n\
      \n**5th level (2 slots):** [cloudkill](3-Mechanics/CLI/spells/cloudkill.md),\
      \ [seeming](3-Mechanics/CLI/spells/seeming.md) (cast each day)\n\n**6th level\
      \ (1 slots):** [chain lightning](3-Mechanics/CLI/spells/chain-lightning.md)"
    "name": "Spellcasting"
  - "desc": "Aerisi has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
      \ and magic can't put her to sleep."
    "name": "Fey Ancestry"
  - "desc": "When Aerisi drops to 0 hit points, her body disappears in a howling whirlwind\
      \ that disperses quickly and harmlessly. Anything she is wearing or carrying\
      \ is left behind."
    "name": "Howling Defeat"
  - "desc": "If Aerisi fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (2/Day)"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +9 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 9 (1d6 + 6) piercing damage, or 10 (1d8 + 6) piercing\
      \ damage if used with two hands to make a melee attack, plus 3 (1d6) lightning\
      \ damage."
    "name": "Windvane"
"lair_actions":
  - "desc": "If Aerisi is in the air node while [Yan-C-Bin](3-Mechanics/CLI/bestiary/npc/yan-c-bin-pota.md)\
      \ isn't, Aerisi can take lair actions. On initiative count 20 (losing initiative\
      \ ties), Aerisi uses a lair action to cast one of her spells, up to 3rd level,\
      \ without using components or a spell slot. She can't cast the same spell two\
      \ rounds in a row, although she can continue to concentrate on a spell she previously\
      \ cast using a lair action. Aerisi can take no other lair actions while [concentrating](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on a spell cast as a lair action.\n\nIf Aerisi casts [invisibility](3-Mechanics/CLI/spells/invisibility.md)\
      \ using this lair action, she also draws the power of the air node into herself.\
      \ By doing so, she regains 15 (3d8 + 2) hit points."
    "name": ""
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/aerisi-kalinoth-pota.webp"
```
^statblock