---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdmm
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Berlain Shadowdusk"
---
# [Berlain Shadowdusk](3-Mechanics/CLI/bestiary/npc/berlain-shadowdusk-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 283*  

A little over a year ago, Berlain and her brother Korva briefly entered the Far Realm, whereupon they became fused into a single physical form. This merging obliterated most of Korva's body and personality, leaving Berlain with an extra mouth and an extra set of arms that once belonged to her brother. She also inherited a few of his internal organs and personality traits. She can speak using one or both of her mouths.

Berlain has dirty blonde hair, piercing dark eyes, and two mouths where one would normally be—one below the other, canted at an angle. Sprouting from her misshapen shoulders are two pairs of arms—her original limbs above those of her brother. She wears a poorly stitched robe made from other garments and designed to fit her mutated form.

```statblock
"name": "Berlain Shadowdusk (WDMM)"
"size": "Medium"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "99"
"hit_dice": "18d8 + 18"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "12"
  - !!int "20"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "9"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+13"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+13"
"damage_resistances": "damage from spells; nonmagical bludgeoning, piercing, slashing\
  \ (from stoneskin)"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger-xphb.md)"
"senses": "passive Perception 12"
"languages": "Common, Deep Speech, Grell, Undercommon"
"cr": "12"
"traits":
  - "desc": "Berlain is an 18th-level spellcaster. Her spellcasting ability is Intelligence\
      \ (spell save DC 17, +9 to hit with spell attacks). Berlain can cast [disguise\
      \ self](3-Mechanics/CLI/spells/disguise-self-xphb.md) and invisibility at will\
      \ and has the following wizard spells prepared:\n\n**Cantrips (at will):** [fire\
      \ bolt](3-Mechanics/CLI/spells/fire-bolt-xphb.md), [light](3-Mechanics/CLI/spells/light-xphb.md),\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand-xphb.md), [prestidigitation](3-Mechanics/CLI/spells/prestidigitation-xphb.md),\
      \ [shocking grasp](3-Mechanics/CLI/spells/shocking-grasp-xphb.md)\n\n**1st level\
      \ (4 slots):** [detect magic](3-Mechanics/CLI/spells/detect-magic-xphb.md),\
      \ [identify](3-Mechanics/CLI/spells/identify-xphb.md), [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md)*,\
      \ [magic missile](3-Mechanics/CLI/spells/magic-missile-xphb.md)\n\n**2nd level\
      \ (3 slots):** [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
      \ [mirror image](3-Mechanics/CLI/spells/mirror-image-xphb.md), [misty step](3-Mechanics/CLI/spells/misty-step-xphb.md)\n\
      \n**3rd level (3 slots):** [counterspell](3-Mechanics/CLI/spells/counterspell-xphb.md),\
      \ [fly](3-Mechanics/CLI/spells/fly-xphb.md), [lightning bolt](3-Mechanics/CLI/spells/lightning-bolt-xphb.md)\n\
      \n**4th level (3 slots):** [polymorph](3-Mechanics/CLI/spells/polymorph-xphb.md),\
      \ [fire shield](3-Mechanics/CLI/spells/fire-shield-xphb.md), [stoneskin](3-Mechanics/CLI/spells/stoneskin-xphb.md)*\n\
      \n**5th level (3 slots):** [cone of cold](3-Mechanics/CLI/spells/cone-of-cold-xphb.md),\
      \ [scrying](3-Mechanics/CLI/spells/scrying-xphb.md), [wall of force](3-Mechanics/CLI/spells/wall-of-force-xphb.md)\n\
      \n**6th level (1 slots):** [globe of invulnerability](3-Mechanics/CLI/spells/globe-of-invulnerability-xphb.md)\n\
      \n**7th level (1 slots):** [teleport](3-Mechanics/CLI/spells/teleport-xphb.md)\n\
      \n**8th level (1 slots):** [mind blank](3-Mechanics/CLI/spells/mind-blank-xphb.md)*\n\
      \n**9th level (1 slots):** [time stop](3-Mechanics/CLI/spells/time-stop-xphb.md)\n\
      \n*Berlain casts these spells on herself before combat."
    "name": "Spellcasting"
  - "desc": "Berlain has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"bonus_actions":
  - "desc": "As a bonus action, Berlain can use her extra mouth and arms to cast any\
      \ cantrip she has prepared."
    "name": "Fused Form"
"source":
  - "WDMM"
"image": "3-Mechanics/CLI/bestiary/npc/token/berlain-shadowdusk-wdmm.webp"
```
^statblock