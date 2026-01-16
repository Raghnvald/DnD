---
obsidianUIMode: preview
cssclasses:
- json5e-spell
tags:
- ttrpg-cli/compendium/src/5e/egw
- ttrpg-cli/spell/level/8th-level
- ttrpg-cli/spell/school/conjuration
aliases:
- Reality Break
---
# Reality Break
*8th-level, Conjuration*  
![](/3-Mechanics/CLI/spells/img/reality-break.webp#right)

- **Casting time:** 1 Action
- **Range:** 60 feet
- **Components:** V, S, M (a crystal prism)
- **Duration:** Concentration, up to 1 minute

You shatter the barriers between realities and timelines, thrusting a creature into turmoil and madness. The target must succeed on a Wisdom saving throw, or it can't take reactions until the spell ends. The affected target must also roll a `dice:d10|noform|noparens|avg` (`d10`) at the start of each of its turns; the number rolled determines what happens to the target, as shown on the Reality Break Effects table.

At the end of each of its turns, the affected target can repeat the Wisdom saving throw, ending the spell on itself on a success.

**Reality Break Effects**

`dice: [](reality-break-egw.md#^reality-break-effects)`

| dice: d10 | Effect |
|-----------|--------|
| 1-2 | **Vision of the Far Realm.** The target takes `dice:6d12\|noform\|noparens\|avg` (`6d12`) psychic damage, and it is [stunned](/3-Mechanics/CLI/conditions.md#Stunned) until the end of the turn. |
| 3-5 | **Rending Rift.** The target must make a Dexterity saving throw, taking `dice:8d12\|noform\|noparens\|avg` (`8d12`) force damage on a failed save, or half as much damage on a successful one. |
| 6-8 | **Wormhole.** The target is teleported, along with everything it is wearing and carrying, up to 30 feet to an unoccupied space of your choice that you can see. The target also takes `dice:10d12\|noform\|noparens\|avg` (`10d12`) force damage and is knocked [prone](/3-Mechanics/CLI/conditions.md#Prone). |
| 9-10 | **Chill of the Dark Void.** The target takes `dice:10d12\|noform\|noparens\|avg` (`10d12`) cold damage, and it is [blinded](/3-Mechanics/CLI/conditions.md#Blinded) until the end of the turn. |
^reality-break-effects

*Source: Explorer's Guide to Wildemount p. 189*