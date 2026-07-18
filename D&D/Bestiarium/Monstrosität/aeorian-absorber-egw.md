---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Aeorian Absorber
Kategorie: Monstrosität
Größe: Groß
HG: "10"
Habitat:
  - /
Status: WIP
linter-yaml-title-alias: Aeorian Absorber
tags:
  - Monster/Größe/Groß
  - Monster/HG/10
  - Monster/Typ/Monstrosität
  - Quelle/5e/egw
aliases:
  - Aeorian Absorber
image: token/aeorian-absorber-egw.webp
status: WIP
---
# [Aeorian Absorber](3-Mechanics\CLI\bestiary\monstrosity/aeorian-absorber-egw.md)
*Source: Explorer's Guide to Wildemount p. 283*  

Resembling some sort of canine or feline quadruped at a distance, the absorber's monstrous nature becomes quickly apparent as it closes in. Named for its ability to draw magical energy into its body, the absorber can release that energy in devastating blasts through its tail, whose eye is constantly on the lookout for prey.

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
"name": "Aeorian Absorber (EGW)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "171"
"hit_dice": "18d10 + 72"
"modifier": !!int "4"
"stats":
  - !!int "21"
  - !!int "18"
  - !!int "18"
  - !!int "6"
  - !!int "14"
  - !!int "8"
"speed": "40 ft."
"saves":
  - "wisdom": !!int "6"
  - "charisma": !!int "3"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+8"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+6"
"damage_immunities": "necrotic, radiant"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 16"
"languages": "understands Draconic but can't speak"
"cr": "10"
"traits":
  - "desc": "The absorber has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "If the absorber moves at least 20 feet straight toward a creature and\
      \ then hits its claws attack on the same turn, that target must succeed on a\
      \ DC 17 Strength saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone).\
      \ If the target is [prone](/3-Mechanics/CLI/conditions.md#Prone), the absorber\
      \ can make one bite attack against it as a bonus action."
    "name": "Pounce"
"actions":
  - "desc": "The absorber makes three attacks: one with its bite or Mind Bolt and\
      \ two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one creature. *Hit:* 10\
      \ (1d10 + 5) piercing damage plus 5 (1d10) force damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 8 (1d6\
      \ + 5) slashing damage plus 3 (1d6) force damage."
    "name": "Claws"
  - "desc": "*Ranged Spell Attack:* +8 to hit, range 120 ft., one creature. *Hit:*\
      \ 22 (4d10) psychic damage."
    "name": "Mind Bolt"
"reactions":
  - "desc": "When the absorber takes damage from a spell, the absorber takes only\
      \ half the triggering damage. If the spellcaster is within 60 feet of the absorber,\
      \ the absorber can force the caster to make a DC 16 Dexterity saving throw.\
      \ Unless the save succeeds, the caster takes the other half of the damage."
    "name": "Tail Ray"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/aeorian-absorber-egw.webp"
```
^statblock