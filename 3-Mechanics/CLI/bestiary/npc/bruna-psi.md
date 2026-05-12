---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psi
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Bruna"
---
# [Bruna](3-Mechanics/CLI/bestiary/npc/bruna-psi.md)
*Source: Plane Shift: Innistrad p. 26*  

[Avacyn](3-Mechanics/CLI/bestiary/npc/avacyn-psi.md) was the archangel of Innistrad, revered across the plane as the source of hope, of protection, and of the Blessed Rest—a peaceful eternity of slumber in the grave. She offered the faithful magical wards against vampires and werewolves, a tranquil oblivion rather than the damned fate of a tormented spirit or undead abomination, and a distant hope that someday, their descendants might live in an Innistrad free from all the horrors of darkness.

Traditionally, three groups of angels known as flights or hosts served [Avacyn](3-Mechanics/CLI/bestiary/npc/avacyn-psi.md), each under the leadership of a lesser archangel.

## Flight Alabaster

The practical and sympathetic angels of Flight Alabaster were instrumental in maintaining Avacyn's wards against the supernatural evils of Innistrad. They preferred the use of spells to weapons, and engaged in battle only when they had exhausted other options. As a result, angels of other flights sometimes dismissed them as overly sentimental. Alabaster angels aided priests and cathars in maintaining the protective wards on city walls and at holy sites throughout the plane, and also aided Avacyn in conducting the spirits of the dead to their ultimate fate, dissolving into Innistrad's Æthereal essence. The leader of Flight Alabaster was [Bruna](3-Mechanics/CLI/bestiary/npc/bruna-psi.md), called the Light of Alabaster.

## Host of Herons

The Host of Herons comprised the angels of birth, rebirth, and purity, whose magic was said to ward humans against harm in life. This was always the smallest flight of angels, and its primary function was the scouting and tracking of werewolves and other marauding monsters. [Sigarda](3-Mechanics/CLI/bestiary/npc/sigarda-psi.md) led the Host of Herons, wielding a scythe shaped like the head of a heron.

## Flight Goldnight

Flight Goldnight was an army of soldier-angels focused on the martial strength of the church. These angels were characterized by pragmatism and strict observance of church law. They were strategists in battle and skillful leaders during armed conflicts, cultivating a martial mindset that made them more than willing to take up arms when the need arose. The leader of Flight Goldnight was [Gisela](3-Mechanics/CLI/bestiary/npc/gisela-psi.md), called the Blade of Goldnight or the Blade of the Church.

## The Madness of Avacyn

When the Eldrazi titan Emrakul first approached Innistrad, [Avacyn](3-Mechanics/CLI/bestiary/npc/avacyn-psi.md) perceived her influence as a contagion that must be expunged from the world. However, unable to identify the source of that contagion, [Avacyn](3-Mechanics/CLI/bestiary/npc/avacyn-psi.md) was driven mad, lashing out instead at every living thing. She led the angels in a vain effort to purge this corruption from the plane, viewing the humans they once protected as part of the maddening illness. The different flights of angels even began to war against each other, drastically reducing the number of angels on the plane.

Wielding fiery swords and clad in full armor, the soldier-angels of Flight Goldnight became the scourge of all mortal life on Innistrad. None could predict what would trigger their violent judgment or where they would strike next. The angels of Flight Alabaster had always been at the forefront of the church's efforts to root out and punish demon cultists, necromancers, and other heretics. With Emrakul's approach, they grew at least as mad as [Avacyn](3-Mechanics/CLI/bestiary/npc/avacyn-psi.md) herself. Their fervent obsession drove the forces of the Lunarch Inquisition, the church's efforts to root out sin among the human populace. The angels prodded the church to ever greater and more desperate action.

Amid the chaos, [Avacyn](3-Mechanics/CLI/bestiary/npc/avacyn-psi.md) created a new angelic flight to serve as her honor guard. Armed with moonsilver spears forged from shards of the broken Helvault, these angels of the Flight of Moonsilver served as sentries and guards at Thraben Cathedral, and flew alongside [Avacyn](3-Mechanics/CLI/bestiary/npc/avacyn-psi.md) into battle against any perceived threat to Innistrad.

Only [Sigarda](3-Mechanics/CLI/bestiary/npc/sigarda-psi.md) and the Host of Herons remained unaffected by Avacyn's madness, perhaps because they were the angels of purity. The survivors of this host retreated to their old haunt in Gavony's remote parish of Videns to maintain a safe distance from [Avacyn](3-Mechanics/CLI/bestiary/npc/avacyn-psi.md).

Angels that have gone mad can cast [flame strike](3-Mechanics/CLI/spells/flame-strike.md) once per day using their Innate Spellcasting trait. Additionally, the extra damage from their Angelic Weapons is half fire damage and half radiant damage.

```statblock
"name": "Bruna (PSI)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "16d10 + 112"
"modifier": !!int "5"
"stats":
  - !!int "24"
  - !!int "20"
  - !!int "24"
  - !!int "19"
  - !!int "22"
  - !!int "25"
"speed": "40 ft., fly 120 ft."
"saves":
  - "constitution": !!int "12"
  - "wisdom": !!int "11"
  - "charisma": !!int "12"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+11"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"gear":
  - "[greatsword](3-Mechanics/CLI/items/greatsword.md)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 21"
"languages": "all, telepathy 120 ft."
"cr": "16"
"traits":
  - "desc": "The Bruna's spellcasting ability is Charisma (spell save DC 20). The\
      \ Bruna can innately cast the following spells, requiring no material components:\n\
      \n**At will:** [detect evil and good](3-Mechanics/CLI/spells/detect-evil-and-good.md),\
      \ [invisibility](3-Mechanics/CLI/spells/invisibility.md) (self only), [protection\
      \ from evil and good](3-Mechanics/CLI/spells/protection-from-evil-and-good.md)\n\
      \n**3/day each:** [blade barrier](3-Mechanics/CLI/spells/blade-barrier.md),\
      \ [dispel evil and good](3-Mechanics/CLI/spells/dispel-evil-and-good.md), [flame\
      \ strike](3-Mechanics/CLI/spells/flame-strike.md), [raise dead](3-Mechanics/CLI/spells/raise-dead.md)\n\
      \n**1/day each:** [commune](3-Mechanics/CLI/spells/commune.md), [control weather](3-Mechanics/CLI/spells/control-weather.md),\
      \ [insect plague](3-Mechanics/CLI/spells/insect-plague.md), [dispel evil and\
      \ good](3-Mechanics/CLI/spells/dispel-evil-and-good.md)"
    "name": "Innate Spellcasting"
  - "desc": "The Bruna's weapon attacks are magical. When the Bruna hits with any\
      \ weapon, the weapon deals an extra 5d8 radiant damage (included in the attack)."
    "name": "Angelic Weapons"
  - "desc": "The Bruna knows if it hears a lie."
    "name": "Divine Awareness"
  - "desc": "The Bruna has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The Bruna makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:*\
      \ 21 (4d6 + 7) slashing damage plus 22 (5d8) radiant damage."
    "name": "Greatsword"
  - "desc": "The Bruna touches another creature. The target magically regains 30 (6d8\
      \ + 3) hit points and is freed from any curse, disease, poison, blindness,\
      \ or deafness."
    "name": "Healing Touch (4/Day)"
"source":
  - "PSI"
"image": "3-Mechanics/CLI/bestiary/npc/token/bruna-psi.webp"
```
^statblock