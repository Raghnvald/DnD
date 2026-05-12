---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/18
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead/wizard
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Zlan"
---
# [Zlan](3-Mechanics/CLI/bestiary/npc/zlan-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 287*  

## Zlan

*Scheming Lich in a Monstrous, Frozen Form*

Zlan is a horrid, icy amalgamation of the seven liches who created the Artifact *Crenshinibon*, better known as the *Crystal Shard*. Zlan Clervish was one of those seven liches, and that lich's will predominates in the fused entity. All seven bodies are frozen together with ice and black crystal called chardalyn, fragments of the shattered *Crystal Shard*.

Zlan has leveraged its connection with the shattered Artifact to psychically infest chardalyn, using the crystalline material to observe enemies and warp minds.

## History

Seven powerful liches from other worlds came together to create the *Crystal Shard* millennia ago. Although the liches were jealous and suspicious of each other, their combined power was sufficient to create the sentient Artifact. The *Crystal Shard* absorbed its creators' minds, which resonated within the crystal of the *Crystal Shard* thereafter. When the *Crystal Shard* was destroyed, its fragments, called chardalyn, still echoed with its creators' malevolent minds. Fragments of ice and chardalyn drew together around the remains of the seven liches, creating an amalgamated form.

Zlan is the foremost mind among the liches and controls the body, The other liches rage and scheme about being subsidiary to someone they once considered both a rival and an equal. The Zlan Liches table gives a brief description of each component.

| Name | History |
|------|---------|
| Argent Black | Emerged from the Negative Plane, fed on hate and darkness |
| Fetchigrol | Abused authority as a spiritual leader to trade souls for power |
| First Grandfather Wu | Unleashed a magical contagion that killed a world of billions |
| Solmé of Gharr | Devoured the souls of children to occupy their bodies |
| Vaeristhelph Rex | Seized power as a wizard-king, traded his throne for lichdom |
| Vlad Xil Haerven | Wallowed in greed and traded lives for wealth |
| Zlan Clervish | Currently in control, aims to expose hidden horrors and ruins beneath Icewind Dale |
^name-history

## Personality

Zlan has an affinity for enchantment and corrupting minds. During the time he was working to create the *Crystal Shard*, Zlan was a devotee of a god of darkness, confusion, and pain. Zlan likes to subtly twist minds to confusion and paranoia and doesn't take direct action when an oblique or hidden action will suffice. Its plans always contain fallbacks and contingencies. One of these contingencies—one the other liches who constitute its new form failed to foresee—was to assume control of the other liches if the *Crystal Shard* was destroyed and created the multi-lich entity.

Zlan schemes about how to restore and control the *Crystal Shard*'s power through the accumulation of chardalyn from across Icewind Dale. Zlan's affinity with chardalyn allows it to access information across the region and use chardalyn to corrupt those who could prove useful.

Zlan's current plan is to heat Icewind Dale from below, warming the Underdark to melt its ice and release aberrant terrors from frozen stasis. This melting also exposes ancient sites containing power Zlan needs to enforce its wicked will on the region.

```statblock
"name": "Zlan (FRAiF)"
"size": "Huge"
"type": "undead"
"subtype": "wizard"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"hp": !!int "199"
"hit_dice": "19d12 + 76"
"modifier": !!int "7"
"stats":
  - !!int "20"
  - !!int "12"
  - !!int "19"
  - !!int "21"
  - !!int "18"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "7"
  - "constitution": !!int "10"
  - "intelligence": !!int "11"
  - "wisdom": !!int "10"
"skillsaves":
  - "name": "Arcana"
    "desc": "+17"
  - "name": "History"
    "desc": "+11"
  - "name": "Perception"
    "desc": "+10"
"damage_resistances": "lightning, necrotic"
"damage_immunities": "cold, poison"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, poisoned"
"senses": "Truesight 120 ft., passive Perception 20"
"languages": "all"
"cr": "18"
"traits":
  - "desc": "Zlan senses the emotions of anyone touching a piece of chardalyn within\
      \ 100 miles of itself."
    "name": "Chardalyn Sense"
  - "desc": "If Zlan fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Zlan has <span title=\"Player's Handbook (2024)\">Advantage</span> on\
      \ saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "If Zlan dies within 100 miles of a piece of chardalyn at least 4 inches\
      \ long, it re-forms from that piece of chardalyn in 1d10 days, regaining all\
      \ its <span title=\"Player's Handbook (2024)\">Hit Points</span>. The new body\
      \ appears in the unoccupied space nearest to the piece of chardalyn, and another\
      \ lich's mind in the body seizes psychic control of the body."
    "name": "Next of the Seven (6/Year)"
"actions":
  - "desc": "Zlan makes three attacks, using Slam or Bewildering Bolt in any combination.\
      \ It can replace two attacks with a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +11, reach 10 ft. *Hit:* 12 (3d4 + 5) Bludgeoning\
      \ damage plus 22 (4d10) Necrotic damage."
    "name": "Slam"
  - "desc": "*Ranged Attack Roll:* +11, range 120 ft. *Hit:* 27 (4d10 + 5) Psychic\
      \ damage, and the target has the Charmed condition until the end of its next\
      \ turn."
    "name": "Bewildering Bolt"
  - "desc": "Zlan casts one of the following spells, requiring no Material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 19):\n\n\
      **At will:** Detect Magic, Detect Thoughts, Dispel Magic, Mage Hand, Message\n\
      \n**2/day each:** Dimension Door, Fly, Scrying\n\n**1/day each:** Befuddlement,\
      \ Disintegrate"
    "name": "Spellcasting"
"reactions":
  - "desc": "Zlan casts Counterspell in response to the spell's trigger, using the\
      \ same spellcasting ability as Spellcasting.\n"
    "name": "Counterspell"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Zlan can expend a use to take one of the following actions. Zlan regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Zlan makes one Slam or Bewildering Bolt attack."
    "name": "Retaliation"
  - "desc": "*Wisdom Saving Throw:* DC 19, one creature Zlan can see within 30 feet\
      \ (with <span title=\"Player's Handbook (2024)\">Disadvantage</span> if the\
      \ target is holding or wearing chardalyn). *Failure:* 27 (6d8) Psychic damage\
      \ and the target has the Charmed condition for 1 minute or until Zlan dies.\
      \ While Charmed, the target doesn't act as an ally to any creature. *Success:*\
      \ Half damage only. *Failure or Success:* Zlan can't take this action again\
      \ until the start of its next turn."
    "name": "Stoke Paranoia"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/npc/token/zlan-fraif.webp"
```
^statblock