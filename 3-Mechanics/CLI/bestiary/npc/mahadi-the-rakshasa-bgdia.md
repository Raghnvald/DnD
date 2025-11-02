---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgdia
  - monster/cr/14
  - monster/size/medium
  - monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Mahadi the Rakshasa
---
# [Mahadi the Rakshasa](3-Mechanics\CLI\bestiary\npc/mahadi-the-rakshasa-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 127*  

Mahadi appears as a wealthy merchant lord. Though extremely powerful, Mahadi doesn't believe in taking unnecessary risks, particularly in the Nine Hells where he can be permanently slain. Mahadi acts as the eyes and ears of Asmodeus in Avernus. As a deal broker and moderator, he's privy to all manner of dealings that might otherwise escape the attention of his patron.

In his role as the master of the Wandering Emporium, Mahadi has received special dispensation from Asmodeus to travel freely between the Material Plane and the Nine Hells to operate his business, as well as to pursue information and broker contracts and other such arrangements as needed.

In addition to managing the Wandering Emporium, Mahadi is also the proprietor and host of Infernal Rapture, a restaurant and spa. Since the establishment exists within a demiplane, patrons can comfortably visit it at any time, even while the caravan is on the move. As long as they can pay for services rendered, guests need not fear being trapped within, since Mahadi is very serious about maintaining the contract between host and guest. Each guest must agree to this formal arrangement prior to gaining entrance.

Mahadi presents himself as a charismatic and gracious host. He makes each guest of Infernal Rapture feel as though they're the most important person in all the planes of existence, catering to their every whim and desire. While he is equally cordial to all guests of the Wandering Emporium, those entering his establishment fall under a special contract and therefore rank most highly in his esteem.

Of course, guests leaving Infernal Rapture are expected to pay their bills in full prior to departure. If a guest cannot pay for whatever reason, the contract they signed on entry clearly stipulates their soul is forfeit. They're required to pay off their debt through service. All such individuals fall under the effect of a geas cast as a 9th-level spell, which cannot be willingly broken by the affected individual until their debt is paid in full. What Mahadi does with such defaulters depends on their capabilities. Some become indentured servants, working at Infernal Rapture. If they possess a talent for sales, they might eventually obtain a business to run within the Wandering Emporium.

```statblock
"name": "Mahadi the Rakshasa (BGDIA)"
"size": "Medium"
"type": "fiend"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "23d8 + 92"
"modifier": !!int "4"
"stats":
  - !!int "14"
  - !!int "18"
  - !!int "18"
  - !!int "14"
  - !!int "18"
  - !!int "20"
"speed": "40 ft."
"saves":
  - "wisdom": !!int "9"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+7"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+10"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
"damage_vulnerabilities": "piercing from magic weapons wielded by good creatures"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 19"
"languages": "all (can read only), Common, Infernal"
"cr": "14"
"traits":
  - "desc": "Mahadi's innate spellcasting ability is Charisma (spell save DC 18, +9\
      \ to hit with spell attacks). He can innately cast the following spells, requiring\
      \ no material components:\n\n**At will:** [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
      \ [disguise self](/3-Mechanics/CLI/spells/disguise-self-xphb.md), [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md),\
      \ [minor illusion](/3-Mechanics/CLI/spells/minor-illusion-xphb.md)\n\n**3/day\
      \ each:** [charm person](/3-Mechanics/CLI/spells/charm-person-xphb.md), [detect\
      \ magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md), [dispel magic](/3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
      \ [hellish rebuke](/3-Mechanics/CLI/spells/hellish-rebuke-xphb.md), [invisibility](/3-Mechanics/CLI/spells/invisibility-xphb.md),\
      \ [major image](/3-Mechanics/CLI/spells/major-image-xphb.md), [speak with dead](/3-Mechanics/CLI/spells/speak-with-dead-xphb.md),\
      \ [suggestion](/3-Mechanics/CLI/spells/suggestion-xphb.md)\n\n**1/day each:**\
      \ [banishment](/3-Mechanics/CLI/spells/banishment-xphb.md), [demiplane](/3-Mechanics/CLI/spells/demiplane-xphb.md),\
      \ [dominate person](/3-Mechanics/CLI/spells/dominate-person-xphb.md), [fly](/3-Mechanics/CLI/spells/fly-xphb.md),\
      \ [forcecage](/3-Mechanics/CLI/spells/forcecage-xphb.md), [geas](/3-Mechanics/CLI/spells/geas-xphb.md),\
      \ [plane shift](/3-Mechanics/CLI/spells/plane-shift-xphb.md), [true seeing](/3-Mechanics/CLI/spells/true-seeing-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "Mahadi can't be affected or detected by spells of 6th level or lower\
      \ unless he wishes to be. He has advantage on saving throws against all other\
      \ spells and magical effects."
    "name": "Limited Magic Immunity"
  - "desc": "Mahadi's weapon attacks are magical."
    "name": "Magic Weapons"
"actions":
  - "desc": "Mahadi makes four claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 9 (2d6\
      \ + 2) slashing damage, and the target is cursed if it's a creature. The curse\
      \ takes effect whenever the target takes a short or long rest, filling the target's\
      \ thoughts with horrible images and dreams. The cursed target gains no benefit\
      \ from finishing a short or long rest. The curse lasts until it is lifted by\
      \ a [remove curse](/3-Mechanics/CLI/spells/remove-curse-xphb.md) spell or similar\
      \ magic."
    "name": "Claw"
  - "desc": "Mahadi summons Ilzabet, an erinyes bound to him by an infernal contract.\
      \ The erinyes appears in an unoccupied space within 60 feet of him, acts as\
      \ his ally, and can't summon other devils. The erinyes remains for 10 minutes\
      \ or until Mahadi dismisses it as an action. If the erinyes dies, Mahadi loses\
      \ this action option."
    "name": "Summon Erinyes (1/Day)"
"source":
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/npc/token/mahadi-the-rakshasa-bgdia.webp"
```
^statblock