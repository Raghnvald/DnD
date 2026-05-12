---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Tasha the Witch
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/19
  - Monster/Typ/Humanoid/human
  - Monster/Typ/Humanoid/wizard
  - Quelle/5e/veor
aliases:
  - Tasha the Witch
linter-yaml-title-alias: Tasha the Witch
---
# Tasha the Witch
*Quelle: Vecna: Vorabend der Verdammnis S. 250*  

Tasha schlug den Pfad zu wahrer Größe ein, als sie von der Erzvettel Baba Yaga adoptiert und Natasha genannt wurde. Tasha erschuf zahlreiche Zauber, darunter Tashas fürchterlicher Lachanfall, und ihre magischen Ambitionen brachten sie in Kontakt mit Dämonen und Dämonenfürsten, die sie sich unterwarf und gegen ihre Feinde einsetzte. Auf der materiellen Ebene wurde sie als Iggwilv die Hexenkönigin bekannt und schrieb das Dämonomikon von Jggwilv, die umfangreichste aller Abhandlungen über den Abyss und seine dämonischen Bewohner. In den vergangenen Jahren hat sich Tasha ins Feywild zurückgezogen, unglaubliche Macht erlangt und sich allmählich in ein Feenwesen verwandelt. So ist Tasha zu Zybilna geworden, Erzfee der Domäne Prismeer. 

## Dem Ruf gefolgt

Als Zybilna von Alustriel Silberhand gerufen wurde, um gegen Vecna zu kämpfen, wurde die Erzfee jedoch dringend in Prismeer gebraucht. Als Kompromiss und zu Ehren von Tashas Freundschaft mit Alustriel schickte Zybilna eine vergangene Version von sich zu Alustriel. Die Tasha im Abenteuer ist eine mächtige Magierin, doch noch keine Hexenkönigin und auch keine Erzfee. 

```statblock
"name": "Tasha the Witch (VEoR)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, wizard"
"alignment": "Chaotic Neutral"
"ac": !!int "19"
"ac_class": "robe of the archmagi"
"hp": !!int "210"
"hit_dice": "28d8 + 84"
"modifier": !!int "4"
"stats":
  - !!int "10"
  - !!int "18"
  - !!int "17"
  - !!int "23"
  - !!int "12"
  - !!int "22"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "12"
  - "wisdom": !!int "7"
  - "charisma": !!int "12"
"skillsaves":
  - "name": "Arcana"
    "desc": "+18"
  - "name": "History"
    "desc": "+12"
  - "name": "Persuasion"
    "desc": "+12"
"condition_immunities": "charmed, frightened"
"senses": "passive Perception 11"
"languages": "Abyssal, Celestial, Common, Draconic, Elvish, Infernal, Sylvan"
"cr": "19"
"traits":
  - "desc": "If Tasha fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Tasha has advantage on saving throws against spells and other magical\
      \ effects. (This trait is bestowed by her Robe of the Archmagi.)"
    "name": "Magic Resistance"
  - "desc": "Tasha wears a Robe of the Archmagi."
    "name": "Special Equipment"
"actions":
  - "desc": "Tasha makes two Caustic Blast attacks and uses Psychic Whip once."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +14 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 21 (6d4 + 6) acid damage."
    "name": "Caustic Blast"
  - "desc": "Tasha psychically lashes out at one creature she can see within 90 feet\
      \ of herself. The target must make a DC 20 Intelligence saving throw. On a failed\
      \ save, the target takes 21 (6d6) psychic damage and has the stunned condition\
      \ until the start of Tasha's next turn. On a successful save, the target takes\
      \ half as much damage only."
    "name": "Psychic Whip"
  - "desc": "Tasha casts one of the following spells, using Intelligence as the spellcasting\
      \ ability (spell save DC 22, +14 to hit with spell attacks):\n\n**At will:**\
      \ Detect Magic, Disguise Self, Dispel Magic, Light, Mage Hand, Message, Prestidigitation,\
      \ Tasha's Hideous Laughter\n\n**2/day:** Polymorph\n\n**1/day each:** Maze,\
      \ Telekinesis"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "For 1 minute, Tasha gains a flying speed of 30 feet, is immune to poison\
      \ damage and the poisoned condition, and has advantage on attack rolls against\
      \ any creature that doesn't have all its hit points. These benefits end early\
      \ if Tasha has the incapacitated condition or if she uses another bonus action\
      \ to dismiss them."
    "name": "Abyssal Visage (2/Day)"
"reactions":
  - "desc": "Immediately after Tasha takes damage, she unleashes arcane energy in\
      \ a 10-foot-radius sphere centered on herself. All other creatures in that area\
      \ must make a DC 20 Dexterity saving throw, taking 19 (3d12) lightning damage\
      \ on a failed save or half as much damage on a successful one. Tasha then teleports,\
      \ along with any equipment she is wearing or carrying, to an unoccupied space\
      \ she can see within 60 feet of herself."
    "name": "Arcane Rebuff"
"source":
  - "VEoR"
"image": "/3-Mechanics/CLI/bestiary/npc/token/tasha-the-witch-veor.webp"
```
^statblock