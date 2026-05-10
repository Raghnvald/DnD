---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Wasserelementar
Kategorie: Elementar
Größe: Groß
HG: 5
Habitat:
  - Küste
  - Sumpf
  - Unterwasser
image: Elementar/img/marid.webp
tags:
  - Monster/Größe/Groß
  - Monster/Habitat/Küste
  - Monster/Habitat/Sumpf
  - Monster/Habitat/Unterwasser
  - Monster/HG/5
  - Monster/Typ/Elementar
  - Quelle/5e/mm
aliases:
  - Water Elemental
---
# Wasserelementar
*Quelle: Monsterhandbuch S. 109. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span> und dem Grundregelwerk (2014)*  

Ein Wasserelementar ist eine ansteigende Welle, die sich über den Boden wälzt und in größeren Gewässern fast unsichtbar wird. Er umschlingt Kreaturen, die in seinem Weg stehen, und füllt ihre Münder und Lungen so mühelos, wie er Flammen erstickt.

## Elementare

Elementare sind Inkarnationen der Elemente, aus denen das Universum besteht: Erde, Feuer, Luft und Wasser. Auch wenn sie auf ihrer eigenen Existenzebene wenig mehr als belebte Energie sind, können sie doch von Zauberwirkern und mächtigen Wesen gerufen werden, um eine Gestalt anzunehmen und Aufgaben zu erfüllen.

### Lebende Elemente

Auf ihrer Heimatebene sind Elementare nur körperlose Lebenskraft. Ihr dumpfes Bewusstsein manifestiert nur dann eine physische Gestalt, wenn es durch die Macht der Magie fokussiert wird. Ein wilder Geist der elementaren Macht hat keinen Wunsch, außer sich durch das Element seiner Heimatebene zu bewegen. Wie die Tiere der Materiellen Ebene haben diese Elementargeister keine Gesellschaft oder Kultur und wenig Bewusstsein für ihr Selbst.

### Von Magie gerufen

Bestimmte Zauber und magische Gegenstände können einen Elementar beschwören, indem sie ihn von den Inneren Ebenen auf die Materielle Ebene rufen. Elementare haben eine instinktive Abneigung dagegen, von ihrer Heimatebene gerufen und zum Dienst gezwungen zu werden. Eine Kreatur, die einen Elementar beschwört, muss ihren Willen nutzen, um ihn zu beherrschen.

### Gebunden und geformt

Mächtige Magie kann einen Elementargeist in eine materielle Schablone binden, die eine bestimmte Verwendung und Funktion bestimmt. Unsichtbare Pirscher sind Luftelementare, die in eine bestimmte Gestalt gebunden sind, so wie Wasserelementare in Wassergeister geformt werden können.

Die Stärke der Magie und Materialien, die einen Elementar binden, bestimmt, wie gut der Elementar in einer gebundenen Form funktioniert. Golems sind Elementargeister, die in physische Formen gebunden sind, aber schwächere Materialien wie Fleisch und Lehm können die elementare Macht nicht ausreichend binden. Robuste Materialien wie Stein und Eisen erfordern stärkere Magie, die den Elementar aber auch sicherer binden kann.

### Elementare Natur

Ein Elementar braucht keine Luft, Nahrung, Wasser oder Schlaf.

```statblock
name: Wasserelementar
size: Groß
type: Elementar
alignment: Neutral
ac: 14
ac_class: natürliche Rüstung
hp: 114
hit_dice: 12d10 + 48
modifier: 2
stats:
  - 18
  - 14
  - 18
  - 5
  - 10
  - 8
speed: 9 m, schwimmen 27 m
damage_resistances: Säure; Wucht-, Stich- und Hiebschaden durch nichtmagische Angriffe
damage_immunities: Gift
condition_immunities: <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Bewusstlos|Bewusstlos<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Erschöpfung|erschöpft<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Festgesetzt|festgesetzt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Gelähmt|gelähmt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Gepackt|gepackt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Liegend|liegend<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Vergiftet|vergiftet<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Versteinert|versteinert<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 m, passive Wahrnehmung 10
languages: Aqual
cr: "5"
traits:
  - desc: The elemental can enter a hostile creature's space and stop there. It can move through a space as narrow as 1 inch wide without squeezing.
    name: Water Form
  - desc: If the elemental takes cold damage, it partially freezes; its speed is reduced by 20 feet until the end of its next turn.
    name: Freeze
actions:
  - desc: The elemental makes two slam attacks.
    name: Multiattack
  - desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage."
    name: Slam
  - desc: |-
      Each creature in the elemental's space must make a DC 15 Strength saving throw. On a failure, a target takes 13 (2d8 + 4) bludgeoning damage. If it is Large or smaller, it is also <STATBLOCK-MARKDOWN-LINK>/3-Mechanics/CLI/conditions.md#Grappled|grappled<STATBLOCK-MARKDOWN-LINK> (escape DC 14). Until this grapple ends, the target is <STATBLOCK-MARKDOWN-LINK>/3-Mechanics/CLI/conditions.md#Restrained|restrained<STATBLOCK-MARKDOWN-LINK> and unable to breathe unless it can breathe water. If the saving throw is successful, the target is pushed out of the elemental's space.

      The elemental can grapple one Large creature or up to two Medium or smaller creatures at one time. At the start of each of the elemental's turns, each target <STATBLOCK-MARKDOWN-LINK>/3-Mechanics/CLI/conditions.md#Grappled|grappled<STATBLOCK-MARKDOWN-LINK> by it takes 13 (2d8 + 4) bludgeoning damage. A creature within 5 feet of the elemental can pull a creature or object out of it by taking an action to make a DC 14 Strength check and succeeding.
    name: Whelm (Recharge 4-6)
source:
  - MM
image: /3-Mechanics/CLI/bestiary/elemental/token/water-elemental.webp
mtime: 1778409079021
path: D&D/Bestiarium/Elementar/Wasserelementar-mm.md
```

---

```statblock
"name": "Water Elemental"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "114"
"hit_dice": "12d10 + 48"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "18"
  - !!int "5"
  - !!int "10"
  - !!int "8"
"speed": "30 ft., swim 90 ft."
"damage_resistances": "acid; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone), [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
  \ [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 10"
"languages": "Aquan"
"cr": "5"
"traits":
  - "desc": "The elemental can enter a hostile creature's space and stop there. It\
      \ can move through a space as narrow as 1 inch wide without squeezing."
    "name": "Water Form"
  - "desc": "If the elemental takes cold damage, it partially freezes; its speed is\
      \ reduced by 20 feet until the end of its next turn."
    "name": "Freeze"
"actions":
  - "desc": "The elemental makes two slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d8 + 4) bludgeoning damage."
    "name": "Slam"
  - "desc": "Each creature in the elemental's space must make a DC 15 Strength saving\
      \ throw. On a failure, a target takes 13 (2d8 + 4) bludgeoning damage. If it\
      \ is Large or smaller, it is also [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 14). Until this grapple ends, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ and unable to breathe unless it can breathe water. If the saving throw is\
      \ successful, the target is pushed out of the elemental's space.\n\nThe elemental\
      \ can grapple one Large creature or up to two Medium or smaller creatures at\
      \ one time. At the start of each of the elemental's turns, each target [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ by it takes 13 (2d8 + 4) bludgeoning damage. A creature within 5 feet of the\
      \ elemental can pull a creature or object out of it by taking an action to make\
      \ a DC 14 Strength check and succeeding."
    "name": "Whelm (Recharge 4-6)"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/water-elemental.webp"
```
^statblock

## Environment

underwater, swamp, coastal