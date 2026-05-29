---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Greater Tyrant Shadow
Kategorie: Aberration
Größe: Gigantisch
HG: 22
status: WIP
linter-yaml-title-alias: Greater Tyrant Shadow
tags:
  - Quelle/5e/coa
  - ttrpg-cli/monster/cr/22
  - ttrpg-cli/monster/size/gargantuan
  - ttrpg-cli/monster/type/aberration
aliases:
  - Greater Tyrant Shadow
---
# [Greater Tyrant Shadow](3-Mechanics/CLI/bestiary/aberration/greater-tyrant-shadow-coa.md)
*Source: Chains of Asmodeus p. 256*  

> [!quote] A quote from Unknown  
> 
> The nine hells can only dream of the perfect oppression which mortals bring upon each other.

Alongside devils and monsters, the Nine Hells have given birth to more nebulous threats. Even raw negative emotion can be personified in the darkest reaches of the lower planes. Congealing into a shape that knows only hunger and the need to hunt. It stalks those filled with fears and insecurities that they refuse to acknowledge.

## Bred from Denial

Tyrant shadows are a threat unique to the Nine Hells. Mortals in the Nine Hells dwell in agony and terror by definition. However, the life of a devil is seldom happier. The infernal hierarchy is harsh and those above constantly abuse the Fiends beneath them whilst fearing usurpation at every turn. In contrast to the unruly hosts of the Abyss, devils are never permitted to give vent to the bitterness that is their lot, bound to a show of discipline and obedience. This festering misery, given no other outlet, manifests as an independent creature that breaks from the devil who generated it to pursue its own malevolent life. Tyrant shadows most often appear as huge-mawed stalking reptiles made from writhing shadows, unless they take on specific forms to exploit the fears of their prey.

## Shifting Stalkers

Tyrant shadows are strongly attracted to the kind of suppressed negative emotions that gave rise to them. The minds of strong mortals valiantly enduring the horrors of the Nine Hells without complaint draw them from far away, and they hunger both for the flesh and the fear such prey generate. A truly satisfying feast for the tyrants must be prepared properly. They stalk their targets over long hours, telepathically sensing what is most feared and shifting their forms to provide glimpses and hints of terror wherever their target looks. Mortals who break easily, giving swift vent to their fear or flying into berserk rages, are of little interest to them. A fear that slowly erodes through its host's iron discipline is savored like a well-aged wine. For the same reason, they gleefully prey on middling and lesser devils whose lives are a constant battle between bitterness and discipline. Those few mortals who are so confident in themselves as to know no fear at all—the most focused of monks or blessed of paladins perhaps—are effectively invisible to tyrant shadows.

## Personal Nemeses

Every tyrant shadow was spawned from the resentful core of a particular devil before taking up its own existence, and the presence of "their" devil continues to sustain the tyrant. As the devil rises in the internal hierarchy, so the tyrant grows stronger. As the tyrant hunts and feasts, so the devil's inner bitterness grows, driving them to greater acts of evil, and thus leading to their advancement. Much as they might deny it, even the greatest of devils are consumed with negative emotions. Archdevils command whole planes yet hate and envy the gods. Somewhere perhaps even Asmodeus has a stalking shadow feeding his malice even as his great status empowers it.

## Greater Tyrant Shadow's Lair

A greater tyrant shadow's lair is always within a few miles of the devil that spawned it, which means that the tyrant shadow itself may often relocate, following the movements of its progenitor, even across the layers of the Nine Hells themselves. Of the lair specifically, the tyrant shadow generally selects a suitably cavernous locale, with deep shadows, perfect for skulking and ambushes. Eroded canyons, abandoned dwellings, and even deep forests, though rare in the Nine Hells, are also suitable locations.

```statblock
"name": "Greater Tyrant Shadow (CoA)"
"size": "Gargantuan"
"type": "aberration"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "372"
"hit_dice": "24d20 + 120"
"modifier": !!int "2"
"stats":
  - !!int "25"
  - !!int "15"
  - !!int "20"
  - !!int "24"
  - !!int "16"
  - !!int "22"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "14"
  - "wisdom": !!int "10"
"skillsaves":
  - "name": "Arcana"
    "desc": "+14"
  - "name": "Deception"
    "desc": "+20"
  - "name": "Perception"
    "desc": "+10"
  - "name": "Stealth"
    "desc": "+16"
"damage_resistances": "fire"
"damage_immunities": "necrotic; poison; psychic; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"condition_immunities": "blinded, charmed, frightened, poisoned"
"senses": "passive Perception 20"
"languages": "understands all, telepathy 300 ft."
"cr": "22"
"traits":
  - "desc": "The shadow uses telepathy to sense nearby creatures. The shadow can see\
      \ a creature if that creature has thoughts and is within the range of the shadow's\
      \ telepathy. The shadow can't see creatures immune to telepathy."
    "name": "Empath"
  - "desc": "The shadow was originally spawned from a specific devil and, if the shadow\
      \ is slain, it returns to life in 10 (1d20) days within 1 mile of that devil.\
      \ The shadow is killed permanently only if its progenitor devil is slain first."
    "name": "Undying Connection"
"actions":
  - "desc": "The shadow makes three Claw attacks. It can replace one of the attacks\
      \ with Shadows of Death (if available)."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 5 ft., one target. *Hit:*\
      \ 21 (4d6 + 7) necrotic damage, plus 10 (3d6) psychic damage."
    "name": "Claw"
  - "desc": "The shadow bends darkness around itself, and now has the invisible condition\
      \ for 1 minute. The invisibility ends if the shadow is subjected to a Daylight\
      \ spell or similar."
    "name": "Cloak of Shadows"
  - "desc": "The shadow attempts to form a link between itself and a creature it can\
      \ see. The target must make a DC 22 Intelligence saving throw, taking 26 (4d12)\
      \ psychic damage on a success. On a failed save, the creature and the shadow\
      \ are linked. While linked, every time the shadow is damaged, the creature takes\
      \ half of that damage as psychic damage. The creature may repeat the saving\
      \ throw at the end of each of its turns, taking 26 (4d12) psychic damage on\
      \ a failed save, or ending the effect on a successful one."
    "name": "Empathic Link"
  - "desc": "The shadow discharges inky-black shadows in a 90-foot-radius sphere around\
      \ itself. Creatures in the shadows must succeed on a DC 22 Wisdom saving throw\
      \ or take 36 (8d8) necrotic damage and have the frightened condition for 1\
      \ minute. A frightened creature may repeat the saving throw at the end of each\
      \ of its turns, ending the effect on a successful save, but taking the damage\
      \ again on a failed save."
    "name": "Shadows of Death (Recharge 5-6)"
"bonus_actions":
  - "desc": "The shadow transforms into a Beast, Humanoid or Fiend that it has an\
      \ Empathic Link with, or back into its true form. In a new form, the shadow\
      \ retains its alignment, hit points, hit dice, telepathy, and Intelligence,\
      \ Wisdom, and Charisma scores, as well as this action. Its statistics and capabilities\
      \ are otherwise replaced by those of the new form, except any class features,\
      \ lair actions, or legendary actions of that form."
    "name": "Change Shape"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), the greater tyrant shadow\
      \ can take one lair action to cause the following effect; it can't take the\
      \ same lair action two rounds in a row:\n\n- **Despair.** One creature within\
      \ 300 feet of the shadow must succeed on a DC 22 Charisma saving throw or be\
      \ overcome with despair and self-doubt. The creature has the stunned condition\
      \ for 1 minute. At the end of each of its turns, the creature can repeat the\
      \ saving throw, ending the effect on a success.  \n- **Renewal.** The shadow\
      \ recharges its Shadows of Death ability.  "
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the greater tyrant shadow can expend a use to take one of the following\
  \ actions. The greater tyrant shadow regains all expended uses at the start of each\
  \ of its turns."
"legendary_actions":
  - "desc": "The shadow surrounds itself in black mist, then teleports up to 60 feet\
      \ to an unoccupied space that it can see."
    "name": "Shadow Blink"
  - "desc": "The shadow uses its Change Shape ability."
    "name": "Shapeshift"
  - "desc": "*Ranged Spell Attack:* +14 to hit, range 300 ft., one target. *Hit:*\
      \ 23 (3d10 + 7) psychic damage."
    "name": "Mind Spike (Costs 2 Actions)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/aberration/token/greater-tyrant-shadow-coa.webp"
```
^statblock