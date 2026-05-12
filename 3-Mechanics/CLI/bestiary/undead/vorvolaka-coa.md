---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Vorvolaka"
---
# [Vorvolaka](3-Mechanics/CLI/bestiary/undead/vorvolaka-coa.md)
*Source: Chains of Asmodeus p. 258*  

There are always mortals who believe they can outwit the powers of the Nine Hells. One strategy is for a powerful evil creature to pledge its soul to the inferno, then seek the eternal unlife of a vampire to cheat the devils of their prize. The devils, of course, have seen it all before. Specialist teams hunt down the offenders and haul them to the Nine Hells where they're reshaped into vorvolakas, forever hungry for mortal blood in an underworld where such a commodity is vanishingly rare.

## The Ever-Hungry

A mockery of their original form, vorvolakas appear like vast tusked bats with a humanoid twist to their forms. Some faint semblance of their original features can just be discerned in their new bestial visage, just as an echo of their memories and personality persists in their fractured minds. They're almost never still or silent, shrieking out their gnawing hunger in their keening voices, jittering and clawing at one another, or circling like vultures across the brazen skies of the Nine Hells. Even as normal vampires are driven by their appetites, transformation into a vorvolaka increases that appetite a hundredfold, but the blood of mortals remains the only meal that sates them for even a moment. Seeing haughty vampires turned into ravenous monsters by their constant unfulfillable hunger is a torment that devils find highly amusing.

## Hell's Sentries

Many powerful devils—especially in the upper layers of Avernus and Dis—keep dovecotes of starving vorvolakas, tolerating their noise and squabbling in exchange for the chief service they provide. The creatures can scent the blood of mortals from miles away, flying into a frenzy at the first hint of a living being. Sometimes the monsters are kept caged, simply serving as a warning system so devils know that mortals are about. More often they're released into the skies to track down the intruders, with infernal huntsmen following in their wake to pick up the pieces.

## Frenzied Hunters

When they find living prey the vorvolakas descend in great squalling flocks, desperate to rend the mortals open and glut themselves on blood. They use their hooked claws and tusks to rip away armor and open up their prey, attacking with utter disregard for their own safety. Their flesh regenerates from most wounds—or else they would tear one another to pieces in their agony—and their hunger is such that only those of strongest faith can hold them back with prayer and holy symbol. Their screaming cries rend the ears of listeners, not only physically painful but imprinting the creatures' deep misery on all who hear. So evident is the despair of the creatures, their horror at their own tormented state, that those who have fought them and survived find themselves more moved to pity than any other emotion.

```statblock
"name": "Vorvolaka (CoA)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "190"
"hit_dice": "20d8 + 100"
"modifier": !!int "4"
"stats":
  - !!int "15"
  - !!int "19"
  - !!int "21"
  - !!int "8"
  - !!int "13"
  - !!int "16"
"speed": "20 ft., fly 50 ft."
"saves":
  - "constitution": !!int "10"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "Insight"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+11"
  - "name": "Religion"
    "desc": "+4"
  - "name": "Survival"
    "desc": "+6"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "necrotic"
"condition_immunities": "charmed, exhaustion, paralyzed"
"senses": "darkvision 120 ft., passive Perception 21"
"languages": "the languages it knew in life"
"cr": "14"
"traits":
  - "desc": "Any hostile creature that starts its turn within 20 feet of the vorvolaka\
      \ must succeed on a DC 18 Wisdom saving throw or have frightened condition until\
      \ the start of the creature's next turn. If a creature's saving throw is successful,\
      \ they're immune to the vorvolaka's Fear Aura for the next 24 hours. This ability\
      \ does not function if the vorvolaka is unconscious."
    "name": "Fear Aura"
  - "desc": "The vorvolaka has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The vorvolaka regains 15 hit points at the start of its turn if it has\
      \ at least 1 hit point. If the vorvolaka takes radiant damage, this trait doesn't\
      \ function at the start of the vorvolaka's next turn."
    "name": "Regeneration"
"actions":
  - "desc": "The vorvolaka makes two Talon attacks. It can replace one of the attacks\
      \ with Rend Armor (if available)."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 22\
      \ (4d8 + 4) piercing damage plus 14 (4d6) necrotic damage."
    "name": "Talon"
  - "desc": "The vorvolaka makes a Talon attack against a creature. On a hit, the\
      \ creature's AC is reduced by 2 for 1 minute. Creatures not wearing armor are\
      \ immune to this effect, and the total reduction can't bring a creature below\
      \ an AC of 10."
    "name": "Rend Armor (Recharge 4-6)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/undead/token/vorvolaka-coa.webp"
```
^statblock