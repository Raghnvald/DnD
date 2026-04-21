---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Nereid
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/2
  - Monster/Typ/Fee
  - Quelle/5e/tftyp
aliases:
  - Nereid
---
# [Nereid](3-Mechanics\CLI\bestiary\fey/nereid-tftyp.md)
*Source: Tales from the Yawning Portal p. 240*  

One of the most inviting locations in the Hidden Shrine of Tamoachan is a gently illuminated pool of water, beside which sits a lovely being singing a pleasant tune. The figure is a nereid—a fey water creature that can shape its environment to suit its needs. Whether male or female, a nereid bears an otherworldly beauty.

```statblock
"name": "Nereid (TftYP)"
"size": "Medium"
"type": "fey"
"alignment": "Any Chaotic alignment"
"ac": !!int "13"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "17"
  - !!int "12"
  - !!int "13"
  - !!int "14"
  - !!int "16"
"speed": "30 ft., swim 60 ft."
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+5"
  - "name": "Nature"
    "desc": "+3"
  - "name": "Stealth"
    "desc": "+5"
  - "name": "Survival"
    "desc": "+4"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Aquan, Common, Elvish, Sylvan"
"cr": "2"
"traits":
  - "desc": "The nereid can breathe air and water."
    "name": "Amphibious"
  - "desc": "If immersed in water, the nereid can make itself invisible as a bonus\
      \ action. It remains invisible until it leaves the water, ends the invisibility\
      \ as a bonus action, or dies."
    "name": "Aquatic Invisibility"
  - "desc": "The nereid wears a mantle of silky cloth the color of sea foam, which\
      \ holds the creature's spirit. The mantle has an AC and hit points equal to\
      \ that of the nereid, but the garment can't be directly harmed while the nereid\
      \ wears it. If the mantle is destroyed, the nereid becomes poisoned and dies\
      \ within 1 hour. A nereid is willing to do anything in its power to recover\
      \ the mantle if it is stolen, including serving the thief."
    "name": "Mantle Dependent"
  - "desc": "The nereid can cast control water at will, requiring no components. Its\
      \ spellcasting ability for it is Charisma. This use of the spell has a range\
      \ of 30 feet and can affect a cube of water no larger than 30 feet on a side."
    "name": "Shape Water"
  - "desc": "The nereid can comprehend and verbally communicate with beasts."
    "name": "Speak With Animals"
"actions":
  - "desc": "*Melee  or Ranged Spell Attack:* +5 to hit, reach 5 ft. or range 30 ft.,\
      \ one target. *Hit:* 16 (2d12 + 3) acid damage, and the target is blinded until\
      \ the start of the nereid's next turn."
    "name": "Blinding Acid"
  - "desc": "The nereid touches one creature it can see within 5 feet of it. The target\
      \ must succeed on a DC 13 Constitution saving throw or take 22 (3d12 + 3) acid\
      \ damage. On a failure, it also runs out of breath and can't speak for 1 minute.\
      \ At the end of each of its turns, it can repeat the save, ending the effect\
      \ on itself on a success."
    "name": "Drowning Kiss (Recharge 5-6)"
  - "desc": "The nereid causes a 5-foot cube of water within 60 feet of it to take\
      \ a shape of its choice and strike one target it can see within 5 feet of that\
      \ water. The target must make a DC 13 Strength saving throw. On a failed save,\
      \ it takes 17 (4d6 + 3) bludgeoning damage, and if it is a Large or smaller\
      \ creature, it is pushed up to 15 feet in a straight line or is knocked prone\
      \ (nereid's choice). On a successful save, the target takes half as much damage\
      \ and isn't pushed or knocked prone."
    "name": "Water Lash"
"source":
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/fey/token/nereid-tftyp.webp"
```
^statblock