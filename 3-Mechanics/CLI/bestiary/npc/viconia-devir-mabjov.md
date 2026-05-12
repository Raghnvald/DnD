---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/drow-elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Viconia DeVir"
---
# [Viconia DeVir](3-Mechanics/CLI/bestiary/npc/viconia-devir-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 126*  

> [!quote] A quote from MINSC & BOO!  
> 
> Me and Boo can attest that Viconia never helped us write the chapter about Ust Natha.

Viconia DeVir is an exiled drow cleric in the service of Shar, goddess of darkness and loss. Once a loyal priestess of Lolth in the great drow city of Menzoberranzan, Viconia and House DeVir first lost the Spider Queen's favor when she refused to sacrifice an infant, an act she saw as pointless. In a desperate attempt to appease Lolth, her own mother arranged for Viconia to be sacrificed herself. She was saved by her devoted brother, Valas, who freed her and slew their mother in the process. For this crime, Valas was transformed into a drider, a monstrous centaur-like creature with a drow torso grafted onto the body of an immense spider. These events contributed to the once great House DeVir's destruction at the hands of House Do'Urden nearly a century ago.

Viconia fled Menzoberranzan and soon left the Underdark altogether to evade retribution from Lolth's minions. Stripped of most of her spellcasting abilities, she eventually found solace and newfound power in the worship of Shar, an ancient deity outside the Dark Seldarine. Like Lolth, Shar is a cruel goddess who values strength and duplicity.

Viconia has now lived apart from drow society for almost a century. During that time, she traveled with the Bhaalspawn Abdel Adrian, but eventually their relationship soured. In recent years, Shar has directed her to work with elemental cults that worship the Elder Elemental Eye. Viconia has faithfully carried out her goddesses wishes, which has often put her into conflict with surface organizations such as the Lord's Alliance or the Harpers.

When not working with cults of elemental evil, Viconia travels the Underdark looking for fellow outcasts. She has put together a motley band including a pair of driders named Cackle and Backle and a deep spider that she has raised since she saved it from being eaten by its mother. She also rides an achaierai that lost the rest of its flock to a war band of dwarves.

```statblock
"name": "Viconia DeVir (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "Drow elf"
"alignment": "Neutral Evil"
"ac": !!int "21"
"ac_class": "cloak of protection, [plate](3-Mechanics/CLI/items/plate-armor.md), [shield](3-Mechanics/CLI/items/shield.md)"
"hp": !!int "135"
"hit_dice": "30d8"
"modifier": !!int "2"
"stats":
  - !!int "25"
  - !!int "14"
  - !!int "10"
  - !!int "14"
  - !!int "20"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "constitution": !!int "5"
  - "wisdom": !!int "10"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+10"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+7"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+12"
"damage_resistances": "necrotic"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 15"
"languages": "Celestial, Common, Elvish"
"cr": "13"
"traits":
  - "desc": "Viconia has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
      \ and magic can't put Viconia to sleep."
    "name": "Fey Ancestry"
  - "desc": "While in dim light or darkness, Viconia has resistance to damage that\
      \ isn't force, psychic, or radiant."
    "name": "Living Shadow"
  - "desc": "Viconia wears a belt of giant strength (fire) and a cloak of protection\
      \ and wields a +3 mace. Without the belt, her strength is 12 and her speed is\
      \ reduced to 20 ft."
    "name": "Special Equipment"
  - "desc": "While in sunlight, Viconia has disadvantage on attack rolls, as well\
      \ as on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception)) checks\
      \ that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "Viconia attacks twice with her Magic Mace and uses her Spellcasting action."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 5 ft., one target. *Hit:*\
      \ 13 (1d6 + 10) bludgeoning damage plus 9 (2d8) necrotic damage."
    "name": "Magic Mace"
  - "desc": "Each creature in a 10-foot-radius, 40-foot-high cylinder centered on\
      \ a point within 60 feet must make a DC 18 Dexterity saving throw. A creature\
      \ takes 28 (8d6) fire damage plus 28 (8d6) radiant damage on a failed save,\
      \ or half as much damage on a successful one."
    "name": "Sacred Cleansing (Recharge 4-6)"
  - "desc": "Viconia casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 18):\n\n**At will:** [dancing lights](3-Mechanics/CLI/spells/dancing-lights.md),\
      \ [light](3-Mechanics/CLI/spells/light.md), [sanctuary](3-Mechanics/CLI/spells/sanctuary.md),\
      \ [thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy.md)\n\n**2/day each:** [cure\
      \ wounds](3-Mechanics/CLI/spells/cure-wounds.md), [death ward](3-Mechanics/CLI/spells/death-ward.md),\
      \ [lesser restoration](3-Mechanics/CLI/spells/lesser-restoration.md)\n\n**1/day\
      \ each:** [darkness](3-Mechanics/CLI/spells/darkness.md), [divine word](3-Mechanics/CLI/spells/divine-word.md),\
      \ [faerie fire](3-Mechanics/CLI/spells/faerie-fire.md), [holy aura](3-Mechanics/CLI/spells/holy-aura.md)"
    "name": "Spellcasting"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/viconia-devir-mabjov.webp"
```
^statblock