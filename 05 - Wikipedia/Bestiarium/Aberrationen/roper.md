---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- Quelle/5e/MM
- Habitat/Unterreich
- Größe/Groß
- Typ/Monstrosität
aliases: ["Roper"]
---
# Roper
*Source: SRD / Basic Rules*  

> [!statblock] Roper
> ![](compendium/bestiary/monstrosity/token/roper.png#token)
> *Large monstrosity, Neutral Evil*
> 
> - **Armor Class** 20  (natural armor)
> - **Hit Points** 93 (`11d10 + 33`)
> - **Speed** 10 ft., climb 10 ft.
> 
> |STR|DEX|CON|INT|WIS|CHA|
> |:---:|:---:|:---:|:---:|:---:|:---:|
> |18 (+4)| 8 (-1)|17 (+3)| 7 (-2)|16 (+3)| 6 (-2)|
> 
> - **Proficiency Bonus** +3
> - **Saving Throws** ⏤
> - **Skills** Perception +6, Stealth +5
> - **Senses** darkvision 60 ft., passive Perception 16
> 
> - **Languages** —
> - **Challenge** 5
> 
> ## Traits
> 
> ***False Appearance.*** While the roper remains motionless, it is indistinguishable from a normal cave formation, such as a stalagmite.
> 
> ***Grasping Tendrils.*** The roper can have up to six tendrils at a time. Each tendril can be attacked (AC 20; 10 hit points; immunity to poison and psychic damage). Destroying a tendril deals no damage to the roper, which can extrude a replacement tendril on its next turn. A tendril can also be broken if a creature takes an action and succeeds on a DC 15 Strength check against it.
> 
> ***Spider Climb.*** The roper can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.
> 
> ## Actions
> 
> ***Multiattack.*** The roper makes four attacks with its tendrils, uses Reel, and makes one attack with its bite.
> 
> ***Bite.*** *Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 22 (`4d8 + 4`) piercing damage.
> 
> ***Tendril.*** *Melee Weapon Attack:* +7 to hit, reach 50 ft., one creature. *Hit:* The target is [grappled](rules/conditions.md#grappled) (escape DC 15). Until the grapple ends, the target is [restrained](rules/conditions.md#restrained) and has disadvantage on Strength checks and Strength saving throws, and the roper can't use the same tendril on another target.
> 
> ***Reel.*** The roper pulls each creature [grappled](rules/conditions.md#grappled) by it up to 25 feet straight toward it.

^statblock

## Environment

underdark

```statblock
layout: Basic 5e Layout
name: Roper
size: Groß
source: SRD / Basic Rules
type: Monstrosität
subtype: ""
alignment: Neutral Böse
ac: 20
hp: 93
hit_dice: 11d10 + 33
speed: 10 ft., Klettern 10 ft.
stats: [18, 8, 17, 7, 16, 6]
saves:
  - STR: +0
  - GES: +0
  - KON: +0
  - INT: +0
  - WEI: +0
  - CHA: +0
skillsaves:
  - Wahrnehmung: +6
  - Verstohlenheit: +5
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: Dunkelsicht 60 ft., passive Wahrnehmung 16
languages: —
cr: 5
bestiary: true
traits:
  - name: False Appearance.
    desc: "Während der Roper unbewegt bleibt, ist er nicht von einer normalen Höhlenformation (z. B. einer Stalagmit) zu unterscheiden."
  - name: Grasping Tendrils.
    desc: "Der Roper kann bis zu sechs Tentakel gleichzeitig haben. Jeder Tentakel hat AC 20 und 10 Trefferpunkte; er ist immun gegen Gift‑ und Psychoschaden. Das Zerstören eines Tentakels richtet dem Roper keinen Schaden zu; er kann in seinem nächsten Zug einen Ersatz‑Tentakel ausfahren. Ein Tentakel kann auch gebrochen werden, wenn eine Kreatur eine Aktion nutzt und dabei eine Stärkeprobe (SG 15) besteht."
  - name: Spider Climb.
    desc: "Der Roper kann schwierige Oberflächen, einschließlich Decken, ohne Probe erklimmen."
actions:
  - name: Multiattack.
    desc: "Der Roper führt vier Angriffe mit seinen Tentakeln aus, benutzt Reel und führt anschließend einen Bissangriff aus."
  - name: Bite.
    desc: "_Nahkampfangriff_: +7 zum Treffen, Reichweite 5 ft., ein Ziel. _Treffer_: 22 (4d8+4) Stichschaden."
    attack_bonus: 7
    damage_dice: 4d8
    damage_bonus: 4
  - name: Tendril.
    desc: "_Fernkampfangriff_: +7 zum Treffen, Reichweite 50 ft., ein Ziel. _Treffer_: Das Ziel wird gefesselt (Flucht‑SG 15). Solange die Fesselung anhält, ist das Ziel gefesselt, hat Nachteil bei Stärke‑Proben und -Rettungswürfen und der Roper kann denselben Tentakel nicht auf ein anderes Ziel richten."
    attack_bonus: 7
    damage_dice: ""
    damage_bonus: ""
  - name: Reel.
    desc: "Der Roper zieht jede gefesselte Kreatur bis zu 25 ft. gerade zu sich hin."
```