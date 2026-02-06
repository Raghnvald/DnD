---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/vgm
  - Monster/HG/4
  - Monster/Habitat/Wüste
  - Monster/Habitat/Wald
  - Monster/Habitat/Unterreich
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Monstrosität/shapechanger
  - Monster/Typ/Monstrosität/yuan-ti
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Yuan-ti Nightmare Speaker
---
# [Yuan-ti Nightmare Speaker](3-Mechanics\CLI\bestiary\monstrosity/yuan-ti-nightmare-speaker-vgm.md)
*Source: Volo's Guide to Monsters p. 205, Tomb of Annihilation*  

Yuan-ti malisons who become priestly devotees of a particular god-be it Sseth, Dendar the Night Serpent, or Merrshaulk-often rise through the ranks to become spiritual leaders among the serpent folk. These priests perform sacrificial rites to appease their vile gods.

## Yuan-ti Nightmare Speaker

Nightmare speakers are female yuan-ti malison priests that make a pact with the Dendar the Night Serpent to feed their deity the fears and nightmares of their victims in exchange for power in the mortal world. The priestesses receive nightmarish visions from Dendar, which they interpret as prophecies, and then use their magic and influence to make these visions come true.

The cruelest of all yuan-ti, nightmare speakers revel in torturing prisoners and slaves, leaving them in a constant state of fear and dread. They prefer to terrify rather than kill their opponents. They manipulate humanoid communities for the purpose of acquiring more victims, and enjoy the company of undead.

This malison is the type that has a human head and upper body with a serpentine lower body instead of legs.

> [!quote] A quote from Volo  
> 
> I'm the explorer who likes to travel on roads and spend my evenings in cozy inns, not hacking through jungles or trudging across deserts through blinding sand to learn the secrets of the serpent folk. I've met a few purebloods and broodguards in my day, but if I had met a yuan-ti pit master, I'm quite sure I'd not be here to tell the tale!

> [!quote] A quote from Elminster  
> 
> Ye almost certainly would not.


```statblock
"name": "Yuan-ti Nightmare Speaker (VGM)"
"size": "Medium"
"type": "monstrosity"
"subtype": "shapechanger, yuan-ti"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "71"
"hit_dice": "13d8 + 13"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "13"
  - !!int "14"
  - !!int "12"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "3"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "Deception"
    "desc": "+5"
  - "name": "Stealth"
    "desc": "+4"
"damage_immunities": "poison"
"condition_immunities": "poisoned"
"senses": "darkvision 120 ft. (penetrates magical darkness), passive Perception 11"
"languages": "Abyssal, Common, Draconic"
"cr": "4"
"traits":
  - "desc": "The yuan-ti is a 6th-level spellcaster. Its spellcasting ability is Charisma\
      \ (spell save DC 13, +5 to hit with spell attacks). It regains its expended\
      \ spell slots when it finishes a short or long rest. It knows the following\
      \ warlock spells:\n\n**Cantrips (at will):** chill touch, eldritch blast (range\
      \ 300 ft., +3 bonus to each damage roll), mage hand, message, poison spray,\
      \ prestidigitation\n\n**1st-3rd level (2 slots):** arms of Hadar, darkness,\
      \ fear, hex, hold person, hunger of Hadar, witch bolt"
    "name": "Spellcasting (Yuan-ti Form Only)"
  - "desc": "The yuan-ti's innate spellcasting ability is Charisma (spell save DC\
      \ 13). The yuan-ti can innately cast the following spells, requiring no material\
      \ components:\n\n**At will:** animal friendship (snakes only)\n\n**3/day:**\
      \ suggestion"
    "name": "Innate Spellcasting (Yuan-ti Form Only)"
  - "desc": "The yuan-ti can use its action to polymorph into a Medium snake or back\
      \ into its true form. Its statistics are the same in each form. Any equipment\
      \ it is wearing or carrying isn't transformed. If it dies, it stays in its current\
      \ form."
    "name": "Shapechanger"
  - "desc": "The first time the yuan-ti hits with a melee attack on its turn, it can\
      \ deal an extra 16 (3d10) necrotic damage to the target."
    "name": "Death Fangs (2/Day)"
  - "desc": "The yuan-ti has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The yuan-ti makes one constrict attack and one scimitar attack."
    "name": "Multiattack (Yuan-ti Form Only)"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 10 ft., one target. *Hit:* 10\
      \ (2d6 + 3) bludgeoning damage, and the target is grappled (escape DC 14) if\
      \ it is a Large or smaller creature. Until this grapple ends, the target is\
      \ restrained, and the yuan-ti can't constrict another target."
    "name": "Constrict"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6\
      \ + 3) slashing damage."
    "name": "Scimitar (Yuan-ti Form Only)"
  - "desc": "The yuan-ti taps into the nightmares of a creature it can see within\
      \ 60 feet of it and creates an illusory, immobile manifestation of the creature's\
      \ deepest fears, visible only to that creature. The target must make a DC 13\
      \ Intelligence saving throw. On a failed save, the target takes 11 (2d10) psychic\
      \ damage and is frightened of the manifestation, believing it to be real. The\
      \ yuan-ti must concentrate to maintain the illusion (as if concentrating on\
      \ a spell), which lasts for up to 1 minute and can't be harmed. The target can\
      \ repeat the saving throw at the end of each of its turns, ending the illusion\
      \ on a success, or taking 11 (2d10) psychic damage on a failure."
    "name": "Invoke Nightmare (Recharges after a Short or Long Rest)"
"source":
  - "VGM"
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/yuan-ti-nightmare-speaker-vgm.webp"
```
^statblock

## Environment

underdark, forest, desert