---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Crawling Claw
tags:
  - Monster/Größe/Winzig
  - Monster/HG/0
  - Monster/Typ/Untote
  - Quelle/5e/mm
aliases:
  - Crawling Claw
linter-yaml-title-alias: Crawling Claw
---
# [Crawling Claw](3-Mechanics\CLI\bestiary\undead/crawling-claw.md)
*Source: Monster Manual p. 44*  

Crawling claws are the severed hands of murderers animated by dark magic so that they can go on killing. Wizards and warlocks of a dark bent use crawling claws as extra hands in their labors.

## Magical Origins

Through dark necromantic rituals, the life force of a murderer is bound to its severed hand, haunting and animating it. If a dead murderer's spirit already manifests as another undead creature, if the murderer is raised from death, or if the spirit has long passed on to another plane, the ritual fails.

The ritual invoked to create a crawling claw works best with a hand recently severed from a murderer. To this end, ritualists and their servants frequent public executions to gain possession of suitable hands, or make bargains with assassins and torturers.

## Creator's Control

A crawling claw can't be turned, nor can it be controlled by spells that control undead. These foul monsters are entirely bound to the will of their creator, which can concentrate on a claw in sight to mentally command its every action. If the crawling claw's creator doesn't command it, the claw follows its last command to the best of its ability.

Commands given to a crawling claw must be simple. A claw can't be tasked with finding and killing a particular person, because its limited senses and intelligence prevent it from tracking and picking out specific individuals. However, a command to kill all creatures in a particular locale works. A crawling claw can easily feel out the contours of keys and doorknobs, crawling from room to room on a blind killing spree.

## Malign Intelligence

A crawling claw possesses little of the intellect and memories of the individual of which it was once a living part. The hate, jealousy, or greed that drove that person to murder lingers on, however, amplified by the claw's torturous fragmented state. Left to its own devices, a crawling claw imitates and recreates the same murderous acts it committed in life.

## Living Claws

If a crawling claw is animated from the severed hand of a still-living murderer, the ritual binds the claw to the murderer's soul. The disembodied hand can then return to its former limb, its undead flesh knitting to the living arm from which it was severed.

Made whole again, the murderer acts as though the hand had never been severed and the ritual had never taken place. When the crawling claw separates again, the living body falls into a coma. Destroying the crawling claw while it is away from the body kills the murderer. However, killing the murderer has no effect on the crawling claw.

## Undead Nature

A crawling claw doesn't require air, food, drink, or sleep.

> [!quote] A quote from Evangeliza Lavain, necromancer  
> 
> Makes you wonder what can be done with all those other murderer parts, doesn't it?

```statblock
"name": "Crawling Claw"
"size": "Tiny"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "2"
"hit_dice": "1d4"
"modifier": !!int "2"
"stats":
  - !!int "13"
  - !!int "14"
  - !!int "11"
  - !!int "5"
  - !!int "10"
  - !!int "4"
"speed": "20 ft., climb 20 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 30 ft. (blind beyond\
  \ this radius), passive Perception 10"
"languages": "understands Common but can't speak"
"cr": "0"
"traits":
  - "desc": "The claw is immune to effects that turn undead."
    "name": "Turn Immunity"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4\
      \ + 1) bludgeoning or slashing damage (claw's choice)."
    "name": "Claw"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/undead/token/crawling-claw.webp"
```
^statblock

Krabbelnde Klauen sind die abgetrennten Hände von Mördern, die mit dunkler Magie belebt worden sind, sodass sie weiter morden können. Dunkle Magier und Paktierer verwenden Krabbelnde Klauen als zusätzliche Hände in ihren Laboren

$\quad$**_Magische Herkunft._** Durch dunkle nekromantische Rituale wird die Lebenskraft eines Mörders an seine abgetrennte Hand gebunden, sodass sie heimgesucht und belebt wird. Wenn der Geist eines toten Mörders sich bereits als andere untote Kreatur manifestiert, wenn der Mörder von den Toten erhoben worden ist oder wenn der Geist schon längst auf eine andere Ebene gewechselt ist, dann misslingt das Ritual.

Das Ritual, das zur Erschaffung einer Krabbelnden Klaue verwendet wird, funktioni~rt am besten mit einer Hand, die einem Mörder gerade eben erst abgetrennt worden ist. Zu diesem Zweck besuchen Ritualisten und ihre Diener öffentliche Hinrichtungen, um passende Hände in ihren Besitz zu bekommen, oder sie schließen Abkommen mit Meuchelmördern und Folterknechten.

$\quad$**_Kontrolle des Erschaffers._** Eine Krabbelnde Klaue kann nicht vertrieben werden und kann auch nicht von Zaubern kontrolliert werden, die Untote beherrschen. Diese verderbten Monster unterstehen vollständig dem Willen ihres Erschaffers, der sich auf eine Klaue in seinem Sichtbereich konzentrieren kann, um geistig jede ihrer Handlungen zu befehligen. Wenn der Erschaffer einer Krabbelnden Klaue sie nicht befehligt, dann folgt die Klaue weiterhin ihrem letzten Befehl, so gut sie es kann.

$\quad$Befehle an eine Krabbelnde Klaue müssen simpel sein. Eine Klaue kann nicht die Aufgabe erhalten, eine bestimmte Person zu finden und zu töten, weil ihre beschränkten Sinne und Intelligenz verhindern, dass sie bestimmte individuelle Ziele ausfindig macht und auswählt. Ein Befehl, Kreaturen an einem bestimmten Ort zu töten, funktioniert allerdings. Eine Krabbelnde Klaue kann problemlos die Umrisse von Schlüsseln und Türknäufen ertasten und in einer blinden Mordserie von Raum zu Raum krabbeln.

$\quad$**_Bösartige Intelligenz._** Eine Krabbelnde Klaue hat wenig von der Intelligenz und den Erinnerungen der Person, von der sie einst ein lebender Teil war. Der Hass, die Eifersucht oder Gier, die die Person zum Mörder gemacht haben, sind allerdings noch immer präsent, verstärkt durch den quälend fragmentierten Zustand der Klaue.

$\quad$Wenn sie sich selbst überlassen wird, imitiert und kopiert die Krabbelnde Klaue die gleichen Mordtaten, die sie im Leben begangen hat.

$\quad$**_Lebende Klaue._** Wenn eine Krabbelnde Klaue aus der abgetrennten Hand eines noch lebenden Mörders erschaffen wird, bindet das Ritual die Klaue an die Seele des Mörders. Die körperlose Hand kann zu ihrem früheren Stumpf zurückkehren. Ihr untotes Fleisch verbindet sich wieder mit dem lebenden Arm, von dem sie abgetrennt worden ist.

$\quad$Wenn der Mörder auf diese Weise wiederhergestellt wird, handelt er, als sei seine Hand niemals abgetrennt worden und als hätte das Ritual niemals stattgefunden. Wenn sich die Krabbelnde Klaue wieder löst, fällt der lebende Körper ins Koma. Die Krabbelnde Klaue zu zerstören, während sie vom Körper abgetrennt ist, tötet den Mörder. Den Mörder zu töten hat allerdings keine Auswirkungen auf die Krabbelnde Klaue.

$\quad$**_Untote Natur._** Eine Krabbelnde Klaue braucht weder Nahrung noch Wasser oder Schlaf.

```statblock
name: Krabbelnde Klaue (2014)
layout: Basic 5e German Layout
image: 
source: Monsterhandbuch 2014
size: Winzig
type: Untoter
alignment: Neutral Böse
ac: 12
hp: 2
hit_dice: 1d4
speed: 9 Meter.
stats: [13, 14, 11, 5, 10, 4]
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: "Gift"
condition_immunities: "Bezaubert, Erschöpft, Vergifter"
senses: [[01. Grundregelwerk 2014/08-Abenteuersuche#Lichtverhältnisse und Sicht|Blindsicht]] 9 Meter (über diesen Radius hinaus blind, passive Wahrnehmung 10
languages: versteht die Gemeinsprache, kann aber nicht sprechen
cr: 0
bestiary: true
traits:
  - name: Immun gegen Vertreibung
    desc: "Die Klaue ist immun gegen die Auswirkungen von Untote vertreiben"
actions:
  - name: Klauen
    desc: "_Nahkampf-Waffenangriff:_ +3, Reichweite 1,5m, ein Ziel. _Treffer:_ 3 (`1W4 + 1`) Wucht- oder Hiebschaden (Entscheidung der Klaue)."
    attack_bonus: 3
    damage_dice: 1d4
    damage_bonus: 1
```