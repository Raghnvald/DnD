---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/11
  - Monster/Größe/Riesig
  - Monster/Typ/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Frost Giant of Evil Water
---
# [Frost Giant of Evil Water](3-Mechanics\CLI\bestiary\giant/frost-giant-of-evil-water-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 146*  

> [!quote] A quote from Bigby  
> 
> I learned enough about the Temple of Elemental Evil in my studies with Mordenkainen that I regard giants connected to the cult with a healthy amount of respect. When you combine a cultist's fanatical devotion with a giant's sheer power, the result can be horrifying.

Though primordials of frost and ice do exist (most notably Cryonax, who is sometimes considered almost the equal of the four Princes of Elemental Evil), frost giants who turn from the gods of the Ordning to embrace Elemental Evil are more likely to serve Olhydra, the Princess of Evil Water. To these giants, water is a cruel and destructive force that finds its ultimate expression in ice. These cultists of Evil Water often hide their allegiance as long as possible while urging their communities to ever increasing depths of cruelty and violence, but if the cultists' apostasy is revealed and they are exiled, they often end up as leaders of Olhydra's cults in colder regions.

Olhydra grants these frost giants the ability to breathe underwater, and they wield armor and weapons that reflect their commitment to the cult. Their armor is outfitted with enormous crossbows that can launch barbed harpoons, which the giants use to drag enemies into or through the water.

```statblock
"name": "Frost Giant of Evil Water (BGG)"
"size": "Huge"
"type": "giant"
"alignment": "typically  Neutral Evil"
"ac": !!int "16"
"ac_class": "[scale mail](/3-Mechanics/CLI/items/scale-mail-xphb.md)"
"hp": !!int "172"
"hit_dice": "15d12 + 75"
"modifier": !!int "3"
"stats":
  - !!int "23"
  - !!int "16"
  - !!int "21"
  - !!int "9"
  - !!int "14"
  - !!int "12"
"speed": "40 ft., swim 40 ft."
"saves":
  - "dexterity": !!int "7"
  - "constitution": !!int "9"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+10"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
"damage_immunities": "cold"
"senses": "passive Perception 16"
"languages": "Aquan, Common, Giant"
"cr": "11"
"traits":
  - "desc": "The giant can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "The giant makes two Battleaxe attacks and one Harpoon attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:* 19\
      \ (3d8 + 6) slashing damage, or 22 (3d10 + 6) slashing damage if used with two\
      \ hands, plus 7 (2d6) cold damage."
    "name": "Battleaxe"
  - "desc": "*Ranged Weapon Attack:* +7 to hit, range 50/200 ft., one creature. *Hit:*\
      \ 14 (2d10 + 3) piercing damage, and the target has the [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ condition (escape DC 16). While the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ this way, its speed isn't reduced, but it can't move farther from the giant.\
      \ The target takes 5 (1d10) slashing damage if it escapes from the grapple or\
      \ if it tries and fails. The giant can grapple only one target at a time with\
      \ its harpoon."
    "name": "Harpoon"
"bonus_actions":
  - "desc": "The giant pulls the target [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ by its Harpoon up to 20 feet toward itself."
    "name": "Reel In"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/giant/token/frost-giant-of-evil-water-bgg.webp"
```
^statblock