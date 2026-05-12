---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psi
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Geist"
---
# [Geist](3-Mechanics/CLI/bestiary/undead/geist-psi.md)
*Source: Plane Shift: Innistrad p. 19*  

Innistrad is filled with the ghosts of the human dead. These spirits, called geists, take many forms. Some are protective ancestors, some are simply lost between life and death, and others are vengeful creatures bent on resolving conflicts they couldn't in life. While Avacyn stood as guardian over Innistrad, she and the angels of Flight Alabaster ushered the spirits of the departed into the Æther, where they rejoined the essence of the plane. In her absence—and now her madness—many spirits cling to the world of the living, unable or unwilling to find their way to the Blessed Sleep.

Geists exist in the space between the material and immaterial realms. Although their nature and substance are fundamentally insubstantial, allowing them to pass through walls or disappear entirely from view, they can affect the material world in a variety of ways. Some can make themselves solid for a brief time, or can solidify parts of themselves or items they hold—typically long enough to slash open a throat with a weapon or claws. Others operate at the level of the mind, instilling deadly fear within the living or twisting their senses. Victims believe so strongly in the illusory harm being inflicted on them by a geist that they actually suffer injury. Some geists can affect temperatures, using cold to numb or freeze the living—particularly when humans get lost on the moors or wander too far into bogs. Some use psychokinetic power to wrap brambles, chains, spikes, or glass around themselves, then wield those objects against the living.

Geists have always been a presence on Innistrad. Some manifest on the plane only because of a grudge or regret powerful enough to disturb the Blessed Sleep of the body to which they were connected. Others linger because of a strong desire to protect their living kin, or because of some obsession forcing them to continue a duty they performed in life.

## Ghostly Possession

Most geists have the ability to take control of corporeal bodies, including those still inhabited by the living. To possess a living person, a geist must overpower its victim's will, making it much easier to inhabit a corpse or a zombie. As long as the possession lasts, the geist has complete control over a living victim, which is forced to watch its body act without any ability to stop it.

## Mana Connection

As creatures of pure spirit, geists are partially sustained by the mana that flows through the plane of Innistrad. Thus, each geist is closely associated with one or more colors of mana, and its nature and attitude are shaped by the characteristics of that mana. The effects of possession by a geist likewise depend on the geist:

- Most white-aligned geists are benevolent, sheltering spirits, and they generally possess the living for their own protection.  
- Blue-aligned geists are prone to performing repetitive actions—knocking, arranging things in patterns, stacking objects, making marks, and so on. When they possess the living, they often induce this same kind of obsessive behavior.  
- Black-aligned geists hate the living, hungering eternally for life, power, or the settling of a wicked grudge. The victims they possess are forced to commit terrible crimes of violence and murder, and are often left injured, permanently crippled, or dying. These geists might be represented by the [shadow](3-Mechanics/CLI/bestiary/undead/shadow.md), [specter](3-Mechanics/CLI/bestiary/undead/specter.md), [will-o'-wisp](3-Mechanics/CLI/bestiary/undead/will-o-wisp.md), or [wraith](3-Mechanics/CLI/bestiary/undead/wraith.md) statistics in the Monster Manual.  
- Human spirits motivated by fury sometimes return as red-aligned geists called [poltergeists](3-Mechanics/CLI/bestiary/undead/poltergeist.md). Use the [specter](3-Mechanics/CLI/bestiary/undead/specter.md) statistics from the Monster Manual with the [poltergeist](3-Mechanics/CLI/bestiary/undead/poltergeist.md) variant for these creatures.  
- Rarely, human spirits return as benevolent green-aligned geists. Similar to white geists, these spirits protect homes nestled in the forest and keep watch over orchards and groves.  

```statblock
"name": "Geist (PSI)"
"size": "Medium"
"type": "undead"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "45"
"hit_dice": "10d8"
"modifier": !!int "1"
"stats":
  - !!int "7"
  - !!int "13"
  - !!int "10"
  - !!int "10"
  - !!int "12"
  - !!int "17"
"speed": "0 ft., fly 40 ft."
"damage_resistances": "acid, fire, lightning, thunder, bludgeoning"
"damage_immunities": "cold, necrotic, poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 11"
"languages": "any languages it knew in life"
"cr": "4"
"traits":
  - "desc": "The geist can see 60 feet into the Ethereal Plane when it is on the Material\
      \ Plane, and vice versa."
    "name": "Ethereal Sight"
  - "desc": "The geist can move through other creatures and objects as if they were\
      \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
      \ an object."
    "name": "Incorporeal Movement"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target *Hit:* 17\
      \ (4d6 + 3) necrotic damage."
    "name": "Withering Touch"
  - "desc": "The geist enters the Ethereal Plane from the Material Plane, or vice\
      \ versa. It is visible on the Material Plane while it is in the Border Ethereal,\
      \ and vice versa, yet it can't affect or be affected by anything on the other\
      \ plane."
    "name": "Etherealness"
  - "desc": "One creature that the geist can see within 5 feet of it must succeed\
      \ on a DC 13 Charisma saving throw or be possessed by the geist; the geist then\
      \ disappears, and the target is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ and loses control of its body. The geist now controls the body but doesn't\
      \ deprive the target of awareness. The geist can't be targeted by any attack,\
      \ spell, or other effect, except ones that turn undead, and it retains its alignment,\
      \ Intelligence, Wisdom, Charisma, and immunity to being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ and [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened). It otherwise\
      \ uses the possessed target's statistics, but doesn't gain access to the target's\
      \ knowledge, class features, or proficiencies. The possession lasts until the\
      \ body drops to 0 hit points, the geist ends it as a bonus action, or the geist\
      \ is turned or forced out by an effect like the [dispel evil and good](3-Mechanics/CLI/spells/dispel-evil-and-good.md)\
      \ spell. When the possession ends, the geist reappears in an unoccupied space\
      \ within 5 feet of the body. The target is immune to this geist's Possession\
      \ for 24 hours after succeeding on the saving throw or after the possession\
      \ ends. The geist can instead target the corpse of a creature, effectively using\
      \ its own life force to animate the corpse as a zombie. The animated corpse\
      \ uses zombie statistics and returns to death if the geist ends the possession."
    "name": "Possession (Recharge 6)"
"source":
  - "PSI"
"image": "3-Mechanics/CLI/bestiary/undead/token/geist-psi.webp"
```
^statblock