---
Bezeichnung: Untitled 1
---
# Untitled 1

```statblock
name: Mammoth
size: Huge
type: beast
alignment: Unaligned
ac: 13
ac_class: natural armor
hp: 126
hit_dice: 11d12 + 55
modifier: -1
stats:
  - 24
  - 9
  - 21
  - 3
  - 11
  - 6
speed: 40 ft.
senses: passive Perception 10
languages: ""
cr: "6"
traits:
  - desc: If the mammoth moves at least 20 feet straight toward a creature and then hits it with a gore attack on the same turn, that target must succeed on a DC 18 Strength saving throw or be knocked [prone](conditions.md#Prone). If the target is <STATBLOCK-MARKDOWN-LINK>/3-Mechanics/CLI/conditions.md#Prone|prone<STATBLOCK-MARKDOWN-LINK>, the mammoth can make one stomp attack against it as a bonus action.
    name: Trampling Charge
actions:
  - desc: "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:* 25 (4d8 + 7) piercing damage."
    name: Gore
  - desc: "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one <STATBLOCK-MARKDOWN-LINK>/3-Mechanics/CLI/conditions.md#Prone|prone<STATBLOCK-MARKDOWN-LINK> creature. *Hit:* 29 (4d10 + 7) bludgeoning damage."
    name: Stomp
source:
  - MM
image: beast/token/mammoth.webp
```