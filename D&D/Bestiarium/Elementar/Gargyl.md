---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung: Gargyl
Typ: Elementar
Größe: Mittelgroß
HG: 2
status:
image: token/Gargyl.webp
tags:
  - Quelle/5e/mm
  - Monster/HG/2
  - Monster/Habitat/Unterreich
  - Monster/Habitat/Stadt
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Elementar
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Gargoyle
---
# [Gargoyle](3-Mechanics\CLI\bestiary\elemental/gargoyle.md)
*Source: Monster Manual p. 140. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

The inanimate gargoyles that perch atop great buildings are inspired by these malevolent creatures of elemental earth that resemble grotesque, fiendish statues. A gargoyle lurks among masonry and ruins, as still as any stone sculpture, and delights in the terror it creates when it breaks from its suspended pose, as well as the pain it inflicts on its victims.

## Animate Stone

Gargoyles cling to rocky cliffs and mountains, or roost on ledges in underground caves. They haunt city rooftops, perching vulture-like among the high stone arches and buttresses of castles and cathedrals, and they can hold themselves so still that they appear inanimate. Able to maintain this state for years, a gargoyle makes an ideal sentry.

## Deadly Reputation

Gargoyles have a reputation for cruelty. Statues carved into the likenesses of gargoyles appear in the architecture of countless cultures to frighten away trespassers. Although such sculptures are only decorative, real gargoyles can hide among them to ambush unsuspecting victims. A gargoyle might alleviate the tedium of its watch by catching and tormenting birds or rodents, but its long wait only increases its craving for harming sentient creatures.

## Cruel Servants

Gargoyles are easily inspired by the cunning of an intelligent master. They enjoy simple tasks such as guarding a master's home, torturing and killing interlopers, and anything else that involves minimum effort and maximum pain and carnage.

Gargoyles sometimes serve demons for their propensity for wanton chaos and destruction. Powerful spellcasters can also easily enlist gargoyle guardians to keep watch over their gates and walls. Gargoyles have the patience and fortitude of stone, and will serve even the cruelest master for years without complaint.

## Elemental Nature

A gargoyle doesn't require air, food, drink, or sleep.

> [!note] Shards of Elemental Evil
> 
> As Ogrémoch, the evil Prince of Elemental Earth, treads his stony realm, it leaves shards of broken rock in his wake. Imbued with slivers of sentience, these shards thrum with the essence of the elemental prince, growing over long years into vaguely humanoid rock formations that resolve at last into the hard, cruel shapes of gargoyles.
> 
> Ogrémoch doesn't create gargoyles deliberately, but they are a physical manifestation of his evil. Gargoyles are mockeries of the elemental air that Ogrémoch despises. They are heavy creatures of living stone, yet capable of flight. Like their creator, they possess a fundamental hatred for beings of elemental air, aarakocra in particular, and relish every opportunity to destroy such creatures.
> 
> On their home plane, gargoyles carve out earth motes that Ogrémoch hurtles into Aaqa, the domain of the aarakocra and the benevolent Wind Dukes the bird folk serve in the Elemental Plane of Air.
^shards-of-elemental-evil

```statblock
"name": "Gargoyle"
"size": "Medium"
"type": "elemental"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "52"
"hit_dice": "7d8 + 21"
"modifier": !!int "0"
"stats":
  - !!int "15"
  - !!int "11"
  - !!int "16"
  - !!int "6"
  - !!int "11"
  - !!int "7"
"speed": "30 ft., fly 60 ft."
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't adamantine"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 10"
"languages": "Terran"
"cr": "2"
"traits":
  - "desc": "While the gargoyle remains motionless, it is indistinguishable from an\
      \ inanimate statue."
    "name": "False Appearance"
"actions":
  - "desc": "The gargoyle makes two attacks: one with its bite and one with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) slashing damage."
    "name": "Claws"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/gargoyle.webp"
```
^statblock

## Environment

underdark, urban

# Gargyl (2014)
Die unbelebten Gargylen, die auf Gebäuden hocken, sind von diesen bösartigen Kreaturen der elementaren Erde inspiriert, die an groteske, teuflische Statuen erinnern. Ein Gargyl lauert zwischen Steinen und Ruinen, so regungslos wie jede Statue, und erfreut sich an dem Schrecken, den er auslöst, wenn er sich aus seiner Bewegungslosigkeit löst. Er genießt auch die Schmerzen, die er seinen Opfern zufügt.

$\quad$**_Belebter Stein._** Gargylen halten sich an felsigen Klippen und Bergen fest oder nisten auf Simsen in unterirdischen Höhlen. Sie suchen die Dächer von Städten heim und hocken wie Geier auf hohen steinernen Bögen und Zinnen von Burgen und Kathedralen, und sie können so regungslos bleiben, dass sie unbelebt erscheinen. Gargylen können für Jahre in diesem Zustand bleiben und sind somit perfekte Wächter.

$\quad$**_Tödlicher Ruf._** Gargylen haben den Ruf, grausam zu sein. Statuen, die Gargylen ähneln sollen, tauchen in der Architektur zahlloser Kulturen auf, um Eindringlinge zu verscheuchen. Auch wenn diese Statuen nur Dekoration sind, können sich echte Gargylen zwischen ihnen verstecken, um arglose Opfer zu überfallen. Ein Gargyl könnte seine Langeweile lindern, indem er Vögel und Nagetiere fängt und quält, doch erhöht die lange Wartezeit nur seinen Wunsch, denkenden Wesen Schmerzen zuzufügen.

$\quad$**_Grausame Diener._** Gargylen lassen sich leicht von der Gerissenheit eines intelligenten Meisters inspirieren. Sie enießen einfache Aufgaben, wie das Bewachen des Hauses ihres Meisters, das Foltern und Töten von Eindringlingen, und a lles, das wenig Mühe und maximalen Schmerz und Blutvergießen bedeutet.

$\quad$Gargylen dienen manchmal Dämonen, weil diese ebenfalls an willkürlichem Chaos und Zerstörung interessiert sind. Mächtige Zauberwirker können Gargylen ebenfalls verpflichten, um Tore und Mauern zu bewachen. Gargylen haben die Geduld und Belastbarkeit von Steinen und dienen sogar den grausamsten Meistern für Jahre, ohne sich zu beschweren.

$\quad$**_Elementare Natur._** Ein Gargyl braucht keine Luft, Nahrung, Wasser oder Schlaf.

>[!info] Bruchstücke des Elementaren Bösen
>Wenn Ogremoch, der böse Prinz der Elementaren Erde, durch sein steinernes Reich schreitet, lässt er eine Spur aus zerbrochenen Felsen zurück. Diese Scherben werden mit einem Bewusstseinsfragment erfüllt und beben mit der Essenz des Elementarprinzen. Im Lauf von langen Jahren wachsen sie zu vage humanoiden Felsformationen heran, die sich am Ende in der harten, grausamen Gestalt des Gargyls auflösen.
>
>Ogremoch erschafft die Gargylen nicht bewusst, aber sie sind eine körperliche Manifestation seiner Bosheit. Gargylen sind eine Verhöhnung der elementaren Luft, die Ogremoch verabscheut. Sie sind schwere Kreaturen aus lebendem Stein, aber doch können sie fliegen . Wie ihr Erschaffer haben sie einen fundamentalen Hass auf Wesen der elementaren Luft, besonders auf Aarakocra, und genießen jede Gelegenheit, solche Wesen zu zerstören.
>
>Auf ihrer Heimatebene graben die Gargylen Erdpartikel aus, die Ogremoch nach Aaqa schleudert, die Domäne der Aarakocra und der wohlwollenden Windherzöge, denen die Vogelmenschen in der Elementarebene der Luft folgen.

```statblock
statblock: true
name: Gargyl
layout: Basic 5e German Layout
image: [[Gargyle.webp]]
source: Monsterhandbuch 2014
size: Mittelgroß
type: Elementar
alignment: chaotisch böse
ac: 15
hp: 52
hit_dice: 7d8 + 21
speed: 9 Meter.
stats: [15, 11, 16, 6, 11, 7]
skillsaves:
  - Heimlichkeit: 6
damage_vulnerabilities: ""
damage_resistances: "Wucht-, Stich- und Hiebschaden durch nicht-magische Angriffe, wenn die Waffen nicht aus Adama nt bestehen"
damage_immunities: "Gift"
condition_immunities: "Bezaubert, Erschöpft, Vergiftet"
senses: Dunkelsicht 18 Meter, passive Wahrnehmung 10
languages: Terral
cr: 2
environment: Stadt, Unterreich
bestiary: true
traits:
  - name: Falsches Erscheinungsbild
    desc: "Wenn der Gargyl bewegungslos bleibt, ist er nicht von einer unbelebten Statue zu unterscheiden."
actions:
  - name: Mehrfachangriff
    desc: "Der Gargyl führt zwei Angriffe aus: einen mit seinem Biss und einen mit seinen Klauen"
  - name: Biss
    desc: "_Nahkampf-Waffenangriff:_ +2 auf Treffer, Reichweite 1,5 m, ein Ziel. _Treffer:_ 5 (`1W6+2`) Stichschaden."
    attack_bonus: 2
    damage_dice: 1d6
    damage_bonus: 2
  - name: Klauen
    desc: "_Nahkampf-Waffenangriff:_ +4, Reichweite 1,5m, ein Ziel. _Treffer:_ 5 (`1W6 + 2`) Hiebschaden."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
```