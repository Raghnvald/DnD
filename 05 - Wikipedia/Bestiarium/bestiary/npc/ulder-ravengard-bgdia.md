---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgdia
  - Monster/cr/5
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Ulder Ravengard
---
# [Ulder Ravengard](3-Mechanics\CLI\bestiary\npc/ulder-ravengard-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 70*  

Ulder Ravengard is a fearless soldier who rose up through the ranks of the Flaming Fist to become its supreme marshal. Ravengard used his military position and influence to secure for himself a seat on the Council of Four. Following the deaths of two council members amid a cloud of corruption and scandal, he persuaded the Parliament of Peers to back his election to grand duke.

Upon ascending to the highest position in the city government, Ravengard refused to relinquish command of the Flaming Fist, making him the most powerful figure in the city by far. This decision has not endeared him to anyone, but Ravengard could care less about his popularity. His only concerns are the stability and prosperity of Baldur's Gate, and he doesn't trust any of the other dukes or anyone in the Parliament of Peers to put the city's interests before their own.

Ravengard rose to grand duke on a platform largely backed by idealistic commoners and enemies of the other established dukes. While he won election handily, Ravengard has struggled in performing his duties, finding his hands tied at every turn by both overt and [invisible](/3-Mechanics/CLI/conditions.md#Invisible) bureaucracy. Despite this, he's been a voice of reason and common sense on the Council of Four—if not the egalitarianism some hoped. He's also proven largely resistant to scandal and corruption, though many of his fellow dukes and those in the Parliament of Peers still regularly outmaneuver him politically. One of his only obvious pleasures remains the surprise inspections he regularly visits upon the troops at Wyrm's Rock.

Ravengard was recently tricked into attending a diplomatic summit in Elturel, unaware that his political enemies in Baldur's Gate orchestrated this meeting in a fiendish plot to remove him from power. In his absence, the Flaming Fist is leaderless, the council rudderless.

```statblock
"name": "Ulder Ravengard (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral"
"ac": !!int "20"
"ac_class": "[plate armor](/3-Mechanics/CLI/items/plate-armor-xphb.md), [shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "14"
  - !!int "16"
  - !!int "11"
  - !!int "10"
  - !!int "17"
"speed": "25 ft."
"saves":
  - "constitution": !!int "6"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+6"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": "Common"
"cr": "5"
"actions":
  - "desc": "Ulder makes three melee attacks, only one of which can be with his shield."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8\
      \ + 4) slashing damage, or 9 (1d10 + 4) slashing damage when used with two hands."
    "name": "+1 Longsword"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one creature. *Hit:* 6\
      \ (1d6 + 3) bludgeoning damage, and Ulder pushes the target 5 feet away from\
      \ him. Ulder then enters the space vacated by the target. If the target is pushed\
      \ to within 5 feet of a creature friendly to Ulder, the target provokes an opportunity\
      \ attack from that creature."
    "name": "Shield"
"reactions":
  - "desc": "If an enemy within 5 feet of Ulder attacks a target other than him, Ulder\
      \ can make a melee attack against that enemy."
    "name": "Guardian Strike"
"source":
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/npc/token/ulder-ravengard-bgdia.webp"
```
^statblock