---
cssclasses: 
- json5e-monster
prefer-view: 
- edit-source read
type: 
- creature
tags: 
- Quelle/5e/Monster_Manual
- Typ/Unhold/Teufel
- Größe/Mittelgroß
- Habitat/Planar/Neun-Höllen
aliases: 
- Erinyes
link:
status:
order:
parent:
---
# Erinyes
*Source: SRD / Basic Rules*  

> [!statblock] Erinyes
> ![](compendium/bestiary/fiend/token/erinyes.png#token)
> *Medium fiend (devil), Lawful Evil*
> 
> - **Armor Class** 18  ([plate armor](compendium/items/plate-armor.md))
> - **Hit Points** 153 (`18d8 + 72`)
> - **Speed** 30 ft., fly 60 ft.
> 
> |STR|DEX|CON|INT|WIS|CHA|
> |:---:|:---:|:---:|:---:|:---:|:---:|
> |18 (+4)|16 (+3)|18 (+4)|14 (+2)|14 (+2)|18 (+4)|
> 
> - **Proficiency Bonus** +4
> - **Saving Throws** Dexterity +7, Constitution +8, Wisdom +6, Charisma +8
> - **Skills** ⏤
> - **Senses** truesight 120 ft., passive Perception 12
> - **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
> - **Damage Immunities** fire, poison
> - **Condition Immunities** poisoned
> - **Languages** Infernal, telepathy 120 ft.
> - **Challenge** 12
> 
> ## Traits
> 
> ***Hellish Weapons.*** The erinyes's weapon attacks are magical and deal an extra 13 (`3d8`) poison damage on a hit (included in the attacks).
> 
> ***Magic Resistance.*** The erinyes has advantage on saving throws against spells and other magical effects.
> 
> ## Actions
> 
> ***Multiattack.*** The erinyes makes three attacks.
> 
> ***Longsword.*** *Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 8 (`1d8 + 4`) slashing damage, or 9 (`1d10 + 4`) slashing damage if used with two hands, plus 13 (`3d8`) poison damage.
> 
> ***Longbow.*** *Ranged Weapon Attack:* +7 to hit, range 150/600 ft., one target. *Hit:* 7 (`1d8 + 3`) piercing damage plus 13 (`3d8`) poison damage, and the target must succeed on a DC 14 Constitution saving throw or be [poisoned](rules/conditions.md#poisoned). The poison lasts until it is removed by the [lesser restoration](compendium/spells/lesser-restoration.md) spell or similar magic.
> 
> ## Reactions
> 
> ***Parry.*** The erinyes adds 4 to its AC against one melee attack that would hit it. To do so, the erinyes must see the attacker and be wielding a melee weapon.

^statblock

```statblock
name: Erinyes
size: Mittelgroß
source: SRD / Basic Rules
type: Teufel
subtype: ""
alignment: Rechtschaffen Böse
ac: 18
hp: 153
hit_dice: 18d8 + 72
speed: 9 Meter, Fliegen 18 Meter
stats: [18, 16, 18, 14, 14, 18]
saves:
  - DEX: +7
  - KON: +8
  - WEI: +6
  - CHA: +8
skillsaves: []
damage_vulnerabilities: ""
damage_resistances: "Kälte; Hieb‑, Stich‑ und Wuchtschaden von nichtmagischen Angriffen, die nicht versilbert sind"
damage_immunities: "Feuer, Gift"
condition_immunities: "Vergiftet"
senses: "Wahrer Blick 120 Fuß, passive Wahrnehmung 12"
languages: "Infernal, telepathisch 120 Fuß"
cr: 12
bestiary: true
traits:
  - name: Hellish Weapons.
    desc: "Die Waffenangriffe der Erinyes gelten als magisch und fügen zusätzlich 13 (3d8) Giftschaden zu (im Angriff enthalten)."
  - name: Magic Resistance.
    desc: "Die Erinyes hat Vorteil bei Rettungswürfen gegen Zauber und andere magische Effekte."
actions:
  - name: Multiattack.
    desc: "Die Erinyes führt drei Angriffe aus."
  - name: Longsword.
    desc: "_Nahkampfangriff_: +8 zum Treffen, Reichweite 5 ft., ein Ziel. _Treffer_: 8 (1d8 + 4) Hiebschaden (oder 9 (1d10 + 4) bei zweihändigem Gebrauch) plus 13 (3d8) Giftschaden."
    attack_bonus: 8
    damage_dice: 1d8
    damage_bonus: 4
  - name: Longbow.
    desc: "_Fernkampfangriff_: +7 zum Treffen, Reichweite 150/600 ft., ein Ziel. _Treffer_: 7 (1d8 + 3) Stichschaden plus 13 (3d8) Giftschaden. Das Ziel muss einen Konstitutions-Rettungswurf (SG 14) bestehen, sonst ist es vergiftet."
    attack_bonus: 7
    damage_dice: 1d8
    damage_bonus: 3
reactions:
  - name: Parry.
    desc: "Die Erinyes addiert 4 zu ihrem AC gegen einen Nahkampfangriff, der sie treffen würde. Sie muss den Angreifer sehen und eine Nahkampfwaffe führen."
```