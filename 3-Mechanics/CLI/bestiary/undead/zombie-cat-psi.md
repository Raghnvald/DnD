---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psi
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Zombie Cat"
---
# [Zombie Cat](3-Mechanics/CLI/bestiary/undead/zombie-cat-psi.md)
*Source: Plane Shift: Innistrad p. 17*  

Ghoulcallers are necromancers—mages who use black mana to call forth the dead from graveyards. These risen dead are called ghouls, or the unhallowed. The ghoulcaller fills the fragile mind of his or her creation with a single driving purpose, which the ghoul carries out to the best of its ability using whatever skills it has. The result is a grotesque parody of life: risen blacksmiths attempting to "reforge" their opponents, fallen warriors rasping incoherent battle cries, undead murderers reawakening their deadly slyness, and fallen mages trying to weave spells that often result in some horrible distortion of their original purpose.

The clergy of Avacyn perform rituals on the final resting places of the dead to ensure the Blessed Sleep, but during Avacyn's time in the Helvault, ghoulcallers had an easier time in their work. In this present age of Avacyn's madness, not only are necromancers easily able to plunder the graves of the fallen, but ghouls seem to arise spontaneously from graves across Innistrad.

The [zombies](3-Mechanics/CLI/bestiary/undead/zombie.md) in the *Monster Manual* describe the most common ghouls of Innistrad. More powerful necromancers might raise unhallowed dead with the statistics of [ghasts](3-Mechanics/CLI/bestiary/undead/ghast.md), [ghouls](3-Mechanics/CLI/bestiary/undead/ghoul.md), [mummies](3-Mechanics/CLI/bestiary/undead/mummy.md), or [wights](3-Mechanics/CLI/bestiary/undead/wight.md).

Ghouls also include zombie animals, often animated by necromancers to serve as familiars—most commonly [cats](3-Mechanics/CLI/bestiary/undead/zombie-cat-psi.md), [rats](3-Mechanics/CLI/bestiary/undead/zombie-rat-psi.md), and [snakes](3-Mechanics/CLI/bestiary/undead/zombie-snake-psi.md). These creatures have the statistics of the small animals in the *Monster Manual*, with the addition of the zombie's Undead Fortitude trait.

```statblock
"name": "Zombie Cat (PSI)"
"size": "Tiny"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "2"
"hit_dice": "1d4"
"modifier": !!int "2"
"stats":
  - !!int "3"
  - !!int "15"
  - !!int "10"
  - !!int "3"
  - !!int "12"
  - !!int "7"
"speed": "40 ft., climb 30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"senses": "passive Perception 13"
"languages": ""
"cr": "0"
"traits":
  - "desc": "If damage reduces the cat to 0 hit points, it must make a Constitution\
      \ saving throw with a DC of 5 + the damage taken, unless the damage is radiant\
      \ or from a critical hit. On a success, the cat drops to 1 hit point instead."
    "name": "Undead Fortitude"
"actions":
  - "desc": "*Melee Weapon Attack:* +0 to hit, reach 5 ft., one target. *Hit:* 1\
      \ slashing damage."
    "name": "Claws"
"source":
  - "PSI"
"image": "3-Mechanics/CLI/bestiary/undead/token/zombie-cat-psi.webp"
```
^statblock