---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Kobold Inventor
Status: WIP
linter-yaml-title-alias: Kobold Inventor
tags:
  - Monster/Größe/Klein
  - Monster/Habitat/Berg
  - Monster/Habitat/Hügel
  - Monster/Habitat/Stadt
  - Monster/Habitat/Unterreich
  - Monster/Habitat/Wald
  - Monster/HG/1-4
  - Monster/Typ/Humanoid/kobold
  - Quelle/5e/vgm
aliases:
  - Kobold Inventor
---
# [Kobold Inventor](3-Mechanics\CLI\bestiary\humanoid/kobold-inventor-vgm.md)
*Source: Volo's Guide to Monsters p. 166, Tomb of Annihilation*  

A kobold inventor, crafty and with quick hands, builds improvised weapons in the hope of gaining some new advantage in combat. An inventor captures bugs, scoops up exotic dungeon slimes, and claims the best stolen goods as ingredients in its experiments. Its creations are sometimes comical in appearance, but-like kobolds' traps-they work a lot better than their materials would suggest.

## Good While They Last

An inventor's new weapons last for only one or two attacks before they break, but might be surprisingly effective in the meantime. Most inventors are skilled enough that their improvised weapons don't backfire on them, but other users might not be so lucky. The weapons don't have to be lethal-in many cases one serves its purpose if it distracts, scares, or confuses a creature long enough for other kobolds to kill the enemy. In any particular encounter, an inventor usually has one or two improvised weapons at its disposal.

> [!quote] A quote from Volo  
> 
> Never make the mistake of thinking kobolds are stupid or backward just because they're small. Size has nothing to do with it.

```statblock
"name": "Kobold Inventor (VGM)"
"size": "Small"
"type": "humanoid"
"subtype": "kobold"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "13"
"hit_dice": "3d6 + 3"
"modifier": !!int "2"
"stats":
  - !!int "7"
  - !!int "15"
  - !!int "12"
  - !!int "8"
  - !!int "7"
  - !!int "8"
"speed": "30 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+0"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Draconic"
"cr": "1/4"
"traits":
  - "desc": "While in sunlight, the kobold has disadvantage on attack rolls, as well\
      \ as on Wisdom (Perception) checks that rely on sight."
    "name": "Sunlight Sensitivity"
  - "desc": "The kobold has advantage on an attack roll against a creature if at least\
      \ one of the kobold's allies is within 5 feet of the creature and the ally isn't\
      \ incapacitated."
    "name": "Pack Tactics"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 30/120 ft., one target. *Hit:*\
      \ 4 (1d4 + 2) bludgeoning damage."
    "name": "Sling"
  - "desc": "The kobold uses one of the following options (roll a d8 or choose one);\
      \ the kobold can use each one no more than once per day:\n\n- **1. Acid.** The\
      \ kobold hurls a flask of acid. *Ranged Weapon Attack:* +4 to hit, range 5/20\
      \ ft., one target. *Hit:* 7 (2d6) acid damage.  \n- **2. Alchemist's fire.**\
      \ The kobold throws a flask of alchemist's fire. *Ranged Weapon Attack:* +4\
      \ to hit, range 5/20 ft., one target. *Hit:* 2 (1d4) fire damage at the start\
      \ of each of the target's turns. A creature can end this damage by using its\
      \ action to make a DC 10 Dexterity check to extinguish the flames.  \n- **3.\
      \ Basket of Centipedes.** The kobold throws a small basket into a 5-foot-square\
      \ space within 20 feet of it. A swarm of insects (centipedes) with 11 hit points\
      \ emerges from the basket and rolls initiative. At the end of each of the swarm's\
      \ turns, there's a 50 percent chance that the swarm disperses.  \n- **4. Green\
      \ Slime Pot.** The kobold throws a clay pot full of green slime at the target,\
      \ and it breaks open on impact. *Ranged Weapon Attack:* +4 to hit, range 5/20\
      \ ft., one target. *Hit:* The target is covered in a patch of green slime (see\
      \ chapter 5 of the Dungeon Master's Guide). Miss: A patch of green slime covers\
      \ a randomly determined 5-foot-square section of wall or floor within 5 feet\
      \ of the target.  \n- **5. Rot Grub Pot.** The kobold throws a clay pot into\
      \ a 5-foot-square space within 20 feet of it, and it breaks open on impact.\
      \ A swarm of rot grubs (see appendix A) emerges from the shattered pot and remains\
      \ a hazard in that square.  \n- **6. Scorpion on a Stick.** The kobold makes\
      \ a melee attack with a scorpion tied to the end of a 5-foot-long pole. *Melee\
      \ Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 1 piercing damage,\
      \ and the target must make a DC 9 Constitution saving throw, taking 4 (1d8)\
      \ poison damage on a failed save, or half as much damage on a successful one.\
      \  \n- **7. Skunk in a Cage.** The kobold releases a skunk into an unoccupied\
      \ space within 5 feet of it. The skunk has a walking speed of 20 feet, AC 10,\
      \ 1 hit point, and no effective attacks. It rolls initiative and, on its turn,\
      \ uses its action to spray musk at a random creature within 5 feet of it. The\
      \ target must make a DC 9 Constitution saving throw. On a failed save, the target\
      \ retches and can't take actions for 1 minute. The target can repeat the saving\
      \ throw at the end of each of its turns, ending the effect on itself on a success.\
      \ A creature that doesn't need to breathe or is immune to poison automatically\
      \ succeeds on the saving throw. Once the skunk has sprayed its musk, it can't\
      \ do so again until it finishes a short or long rest.  \n- **8. Wasp Nest in\
      \ a Bag.** The kobold throws a small bag into a 5-foot-square space within 20\
      \ feet of it. A swarm of insects (wasps) with 11 hit points emerges from the\
      \ bag and rolls initiative. At the end of each of the swarm's turns, there's\
      \ a 50 percent chance that the swarm disperses.  "
    "name": "Weapon Invention"
"source":
  - "VGM"
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/kobold-inventor-vgm.webp"
```
^statblock

## Environment

underdark, mountain, forest, hill, urban