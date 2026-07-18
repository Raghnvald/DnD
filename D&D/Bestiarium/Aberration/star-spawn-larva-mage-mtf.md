---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Star Spawn Larva Mage
Kategorie: Aberration
Größe: Mittelgroß
HG: 16
Status: WIP
linter-yaml-title-alias: Star Spawn Larva Mage
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Berg
  - Monster/HG/16
  - Monster/Typ/aberration
  - Quelle/5e/mtf
aliases:
  - Star Spawn Larva Mage
status: WIP
---
# [Star Spawn Larva Mage](3-Mechanics\CLI\bestiary\aberration/star-spawn-larva-mage-mtf.md)
*Source: Mordenkainen's Tome of Foes p. 235, Waterdeep: Dungeon of the Mad Mage*  

A larva mage is a nightmarish combination of a mortal body and otherworldly substance. When a powerful cultist of a wormlike entity such as Kyuss or Kezef—usually a warlock or other spellcaster—contacts the comet-borne emissary of an Elder Evil, the emissary can merge with a mortal consciousness to create a larva mage. None of the original cultist's personality survives the transformation, so what emerges is wholly alien.

## Star Spawn

> [!quote] A quote from Mordenkainen  
> 
> Stars don't spawn these creatures. Such beautiful lights shouldn't be blamed for such balefulness.

The Material Plane represents only one small part of the multiverse. Beyond the best-known planes of existence lie realms that are lethal to mortal life. Some are so hostile that even a moment's contact with such a place is enough to plunge a mortal mind into madness. Yet beings do exist that are native to these realms: beings that are eternally hungering, searching, warring, sometimes dreaming. These Elder Evils are far older than most of the mortal races and always horrific to humanoid minds.

However much they might desire to enter and dominate the Material Plane, the Elder Evils are unable or unwilling to leave their realms. Some are imprisoned in their dimensions by external forces, some are inextricably bound to their home realities, and others simply can't find any way out.

### Heralds of Doom

The creatures known as star spawn are the heralds, servants, foot soldiers, and lieutenants of the Elder Evils, capable of taking on forms that can journey to the Material Plane. They arrive most often in the wake of a comet—or perhaps such a phenomenon merely signals that star spawn are in the vicinity and available for communication. When the signs are right, warlocks and cultists hasten to gather together, read aloud their blasphemous texts, and conduct the mind-searing rituals that guide the blazing star spawn into the world.

> [!quote] A quote from Mordenkainen  
> 
> The cultists who blaspheme reality by calling out to Elder Evils often speak of a Far Realm from which these entities hail. In truth, there is no one place or space from which they come. There is the multiverse of things that are, and there is the multiverse of things that shouldn't be.

### Elder Evil Blessings

Disciples of certain Elder Evils can bestow supernatural gifts on those who serve that cult, including star spawn. The following powers are unique to specific cults; typically a creature has only one.

- Cult of Atropus, the World Born Dead  
- Cult of Borem, of the Lake of Boiling Mud  
- Cult of Haask, the Voice of Hargut  
- Cult of Tharizdun, the Chained God  
- Cult of Tyranthraxus, the Flamed One  

```statblock
"name": "Star Spawn Larva Mage (MTF)"
"size": "Medium"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "168"
"hit_dice": "16d8 + 96"
"modifier": !!int "1"
"stats":
  - !!int "17"
  - !!int "12"
  - !!int "23"
  - !!int "18"
  - !!int "12"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "6"
  - "wisdom": !!int "6"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "Perception"
    "desc": "+6"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "psychic"
"condition_immunities": "charmed, frightened, paralyzed, petrified, poisoned, restrained"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Deep Speech"
"cr": "16"
"traits":
  - "desc": "The larva mage's innate spellcasting ability is Charisma (spell save\
      \ DC 16, +8 to hit with spell attacks). It can innately cast the following spells,\
      \ requiring no material components:\n\n**At will:** eldritch blast*, minor illusion\n\
      \n**3/day:** dominate monster\n\n**1/day:** circle of death\n\n*3 beams, +3\
      \ bonus to each damage roll"
    "name": "Innate Spellcasting"
  - "desc": "When the larva mage is reduced to 0 hit points, it breaks apart into\
      \ a [swarm of insects](/3-Mechanics/CLI/bestiary/beast/swarm-of-insects.md)\
      \ in the same space. Unless the swarm is destroyed, the larva mage reforms from\
      \ it 24 hours later."
    "name": "Return to Worms"
"actions":
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:* 7\
      \ (1d8 + 3) bludgeoning damage, and the target must succeed on a DC 19 Constitution\
      \ saving throw or be poisoned until the end of its next turn."
    "name": "Slam"
  - "desc": "Each creature other than a star spawn within 10 feet of the larva mage\
      \ must make a DC 19 Dexterity saving throw. On a failure the target takes 22\
      \ (5d8) necrotic damage and is blinded and restrained by masses of swarming\
      \ worms. The affected creature takes 22 (5d8) necrotic damage at the start of\
      \ each of the larva mage's turns. The creature can repeat the saving throw at\
      \ the end of each of its turns, ending the effect on itself on a success."
    "name": "Plague of Worms (Recharge 6)"
"reactions":
  - "desc": "When a creature within 20 feet of the larva mage fails a saving throw,\
      \ the larva mage gains 10 temporary hit points."
    "name": "Feed on Weakness"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the star spawn larva mage can expend a use to take one of the following\
  \ actions. The star spawn larva mage regains all expended uses at the start of each\
  \ of its turns."
"legendary_actions":
  - "desc": "The larva mage casts one cantrip."
    "name": "Cantrip (Costs 2 Actions)"
  - "desc": "The larva mage makes one slam attack."
    "name": "Slam (Costs 2 Actions)"
  - "desc": "Each creature restrained by the larva mage's Plague of Worms takes 13\
      \ (3d8) necrotic damage, and the larva mage gains 6 temporary hit points."
    "name": "Feed (Costs 3 Actions)"
"source":
  - "MTF"
  - "WDMM"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/star-spawn-larva-mage-mtf.webp"
```
^statblock

## Environment

mountain