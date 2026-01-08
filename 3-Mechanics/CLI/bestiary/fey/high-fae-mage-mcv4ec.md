---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mcv4ec
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey/sorcerer
statblock: inline
statblock-link: "#^statblock"
aliases:
- High Fae Mage
---
# [High Fae Mage](3-Mechanics\CLI\bestiary\fey/high-fae-mage-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

High fae mages are some of the mightiest magic users among the faeries of Eldraine. These skilled spellcasters have mastered the arcane art of dealmaking among the fae, magically negotiating themselves advantages in battle.

Like many high fae, these mages draw power from the latent energy found throughout the wilds of Eldraine. However, high fae mages also form strong bonds with the elemental powers of Eldraine, allowing the mages to call on forces like the eastern wind or the fiery hearth.

> [!quote] A quote from Chulane, Teller of Tales  
> 
> The high fae are capable of magic that would make even the great Gadwick himself seem little more than a clumsy apprentice.

## High Fae

Ageless and inhuman, high fae are the oldest creatures in Eldraine, embodying the natural splendor and danger of the wilderness. High fae have no regard for mortal values of honor and law, but they nonetheless operate under inviolable rules of their own: gifts must always be repaid, promises must be honored, and outright lies must never be spoken (though misdirection and riddles are always welcome). To amuse themselves over the long centuries of their lives, high fae frequently engage in deceptions and other complex games of wits against one another.

Most high fae remain secluded deep within the wilds of Eldraine. They draw power from motes of light found throughout the wilds, and they use their innate illusory magic to power and embellish their various weapons.

The high fae are ruled by Talion, the Kindly Lord. Talion is as strange, ancient, and fickle as the wilds of Eldraine, and the Kindly Lord demands fealty and respect from followers. Despite having an austere demeanor, the Kindly Lord is also known for following mysterious whims, journeying to the farthest reaches of Eldraine out of an insatiable curiosity.

```statblock
"name": "High Fae Mage (MCV4EC)"
"size": "Medium"
"type": "fey"
"subtype": "sorcerer"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "17 with mage armor"
"hp": !!int "148"
"hit_dice": "27d8 + 27"
"modifier": !!int "4"
"stats":
  - !!int "11"
  - !!int "18"
  - !!int "12"
  - !!int "17"
  - !!int "15"
  - !!int "24"
"speed": "30 ft., fly 30 ft. (hover)"
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "6"
  - "charisma": !!int "11"
"skillsaves":
  - "name": "Arcana"
    "desc": "+11"
  - "name": "Investigation"
    "desc": "+7"
  - "name": "Nature"
    "desc": "+7"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Sylvan"
"cr": "12"
"traits":
  - "desc": "The high fae has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The high fae makes two Elemental Strike attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +11 to hit, reach 5 ft. or range 60\
      \ ft., one target. *Hit:* 18 (2d10 + 7) acid, cold, fire, force, lightning,\
      \ or thunder damage (the high fae's choice)."
    "name": "Elemental Strike"
  - "desc": "The high fae enacts a magical bargain, siphoning energy from its opponents\
      \ to heal its wounds. The high fae targets up to three creatures it can see\
      \ within 60 feet of itself. Each target must make a DC 19 Constitution saving\
      \ throw, taking 26 (4d12) necrotic damage on a failed save, or half as much\
      \ damage on a successful one. The high fae then regains 30 hit points."
    "name": "Negotiate Life (Recharge 5-6)"
  - "desc": "The high fae casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 19):\n\
      \n**At will:** dancing lights, detect magic, druidcraft, mage armor (self only)\n\
      \n**2/day each:** faerie fire, gust of wind, mirror image"
    "name": "Spellcasting"
"reactions":
  - "desc": "The high fae interrupts a creature it can see that is casting a spell\
      \ with verbal, somatic, or material components. The caster takes 10 (3d6) psychic\
      \ damage and must make a DC 19 Charisma saving throw. On a failed save, the\
      \ spell fails and has no effect, but the spell slot used to cast it is not expended."
    "name": "Fae Counterspell"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/fey/token/high-fae-mage-mcv4ec.webp"
```
^statblock