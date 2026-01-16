---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- new/compendium/src/5e/mcv2dc
- new/monster/cr/22
- new/monster/size/huge
- new/monster/type/dragon/adult-chromatic
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ember
---
# [Ember](3-Mechanics\CLI\bestiary\npc/ember-mcv2dc.md)
*Source: Monstrous Compendium Volume 2: Dragonlance Creatures p. 5*  

> [!quote]  
> 
> Emperor Ariakas,
> 
> Glory to the Dragon Queen's name! Our designs on Abanasinia unfold according to your plans. This is no thanks to the so-called "adviser" I've been saddled with, the dragon Ember. The beast is terrifying, both in might and cunning, but it undermines my every design and terrorizes my forces. It's too canny to be caught, but I'm certain some portion of the troops we've lost to Qualinesti ambushes in fact smolder in the wyrm's gut. It thinks I don't hear, but it whispers curses in reply to my every command. Were it not one of our queen's favored children, I would have replaced my bed linens with its hide.
> 
> I will complete our queen's work with the troops at my disposal, but when I return to Neraka, I would have this viper reassigned. I recommend to Icewall.
> 
> By Her Will, Verminaard
> 
> Highlord of the Red Dragon Army

Also known as Pyros, Ember is an imperious and ruthless red dragon who serves the Dragon Queen Takhisis. In his service to the Dragon Queen, Ember has taken on many roles at her behest—including that of a black-robed human member of the Mages of High Sorcery—but he is best known as the adviser of Dragon Highlord Verminaard, leader of the Red Dragon Army.

Empowered by Takhisis herself, Ember's innate fire can sear those nearby, and his breath weapon is a molten storm of ash and flame. In combat, Ember wears a set of magic plate armor that bolsters his already-impressive might, allowing him to annihilate entire cohorts with terrifying ease.

```statblock
"name": "Ember (MCV2DC)"
"size": "Huge"
"type": "dragon"
"subtype": "adult chromatic"
"alignment": "Chaotic Evil"
"ac": !!int "20"
"ac_class": "special equipment"
"hp": !!int "270"
"hit_dice": "20d12 + 140"
"modifier": !!int "0"
"stats":
  - !!int "28"
  - !!int "10"
  - !!int "25"
  - !!int "17"
  - !!int "14"
  - !!int "22"
"speed": "40 ft., climb 40 ft., fly 80 ft."
"saves":
  - "dexterity": !!int "7"
  - "constitution": !!int "14"
  - "wisdom": !!int "9"
  - "charisma": !!int "13"
"skillsaves":
  - "name": "Perception"
    "desc": "+16"
  - "name": "Religion"
    "desc": "+10"
  - "name": "Stealth"
    "desc": "+14"
"damage_immunities": "fire"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 26"
"languages": "Abyssal, Common, Draconic"
"cr": "22"
"traits":
  - "desc": "At the start of Ember's turn, Ember can force any number of creatures\
      \ of his choice within 10 feet of himself to make a DC 22 Constitution saving\
      \ throw. On a failed save, a creature takes 7 (2d6) fire damage and is frightened\
      \ of Ember until the start of its next turn."
    "name": "Calescent Aura"
  - "desc": "If Ember fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (5/Day)"
  - "desc": "In battle, Ember dons magical plate armor custom-forged for his use.\
      \ While wearing the armor, Ember adds his Charisma modifier to his weapon damage\
      \ rolls (included in the attack descriptions), and his AC can't be lower than\
      \ 20."
    "name": "Special Equipment"
"actions":
  - "desc": "Ember makes one Bite attack and two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +16 to hit, reach 10 ft., one target. *Hit:* 26\
      \ (2d10 + 15) piercing damage plus 13 (2d6 + 6) fire damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +16 to hit, reach 5 ft., one target. *Hit:* 22\
      \ (2d6 + 15) slashing damage."
    "name": "Claw"
  - "desc": "Ember exhales roiling flames and ash in a 90-foot cone. Each creature\
      \ in that area must make a DC 22 Dexterity saving throw. On a failed save, a\
      \ creature takes 56 (16d6) fire damage and is pushed up to 30 feet away from\
      \ Ember and knocked prone. On a successful save, a creature takes half as much\
      \ damage with no other effects. If a creature is reduced to 0 hit points by\
      \ this effect, the creature immediately dies, and its body is reduced to ash."
    "name": "Firestorm Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "Ember magically transforms into a vulture or a mage and retains his alignment,\
      \ damage immunities, hit points, and Hit Dice, as well as his Intelligence,\
      \ Wisdom, and Charisma scores. This transformation ends if Ember is reduced\
      \ to 0 hit points or if he uses another bonus action to end it."
    "name": "Alter Shape"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Ember can expend a use to take one of the following actions. Ember regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Ember moves up to 40 feet in a straight line toward one creature he can\
      \ see. This movement ignores opportunity attacks."
    "name": "Pursuit"
  - "desc": "Ember makes one Bite attack. If the attack hits, it deals an additional\
      \ 7 (2d6) fire damage."
    "name": "Searing Bite (Costs 2 Actions)"
"source":
  - "MCV2DC"
"image": "/3-Mechanics/CLI/bestiary/npc/token/ember-mcv2dc.webp"
```
^statblock