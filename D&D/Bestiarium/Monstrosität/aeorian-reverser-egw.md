---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Aeorian Reverser
Kategorie: Monstrosität
Größe: Groß
HG: "8"
Habitat:
  - /
status: WIP
tags:
  - Monster/Größe/Groß
  - Monster/HG/8
  - Monster/Typ/Monstrosität
  - Quelle/5e/egw
aliases:
  - Aeorian Reverser
---
# [Aeorian Reverser](3-Mechanics\CLI\bestiary\monstrosity/aeorian-reverser-egw.md)
*Source: Explorer's Guide to Wildemount p. 284*  

A reverser is a terrible foe in melee, laying into other creatures with teeth and claw. But the chaos it imposes is more fearful by far, as its enemies' healing magic are unraveled and turned against them.

Brought to life by mages in the flying city of Aeor during the Age of Arcanum, Aeorian hunters were created to take on angels, demons, devils, fey, and the gods themselves. When Aeor crashed into Eiselcross, many of these magically mutated monstrosities survived, and they now stalk Aeor's ruins and the islands' icy wastes.

## Created by Experimentation

Aeorian hunters were created through arcane experimentation on beasts and humanoids—both captives and volunteers. These experiments resulted in monstrosities with brightly colored flesh and the power to resist and destroy Aeor's enemies. It is theorized that the mages of Aeor must have possessed some means of controlling their monstrous soldiers, but no such device has yet been found in the wastes of Eiselcross. Draconic was the language used by these mages to train and bind the Aeorian hunters, and the hunters retain an understanding of this language even though they can't speak it.

### Madness through Immortality

Aeorian hunters do not age. As such, the lust for violence their creators instilled in their minds has grown ravenous after centuries without war. Most immediately attack any creature they see.

#### Never Harm Another Hunter

Though they crave violence, Aeorian hunters have never been seen attacking each other. Most scholars believe that Aeor's mages must have enchanted this behavior into them, given the cost in gold and magic required to create each hunter. Some adventurers in Eiselcross boast about sneaking past Aeorian hunters using disguises or illusions to mimic a hunter's form, but these are most likely tall tales.

#### Ageless Memories

Each Aeorian hunter has perfect recall of every experience since the moment of its creation. Their limited intellects and desire for violence prevent them from effectively communicating, but each hunter holds a wealth of knowledge—often including the location of rare Aeorian relics—inside its mind.

#### Perfect Soldiers

Aeorian hunters don't require food or drink.

```statblock
"name": "Aeorian Reverser (EGW)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "133"
"hit_dice": "14d10 + 56"
"modifier": !!int "3"
"stats":
  - !!int "21"
  - !!int "16"
  - !!int "18"
  - !!int "6"
  - !!int "14"
  - !!int "8"
"speed": "40 ft., climb 40 ft."
"saves":
  - "wisdom": !!int "5"
  - "charisma": !!int "2"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+5"
"damage_immunities": "necrotic, radiant"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 15"
"languages": "understands Draconic but can't speak"
"cr": "8"
"traits":
  - "desc": "The reverser has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The reverser makes three attacks: one with its bite and two with its\
      \ claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, range 5 ft., one creature. *Hit:* 11\
      \ (1d12 + 5) piercing damage plus 6 (1d12) force damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 8 (1d6\
      \ + 5) slashing damage plus 7 (2d6) force damage."
    "name": "Claws"
"reactions":
  - "desc": "When a creature the reverser can see within 30 feet of it regains hit\
      \ points, the reverser reduces the number of hit points regained to 0, and the\
      \ reverser deals 13 (3d8) force damage to the creature."
    "name": "Reversal"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/aeorian-reverser-egw.webp"
```
^statblock