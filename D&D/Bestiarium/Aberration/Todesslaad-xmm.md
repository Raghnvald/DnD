---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Death Slaad
Typ: Aberration (Gestaltwandler)
Größe: Mittelgroß
HG: 10
Habitat: Planar (LimbosWenn))
image: 
status: WIP
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/limbo
  - Monster/Habitat/planar
  - Monster/HG/10
  - Monster/Typ/Aberration
  - Quelle/5e/xmm
aliases:
  - Death Slaad
linter-yaml-title-alias: Death Slaad
---
# [Death Slaad](3-Mechanics\CLI\bestiary\aberration/death-slaad-xmm.md)
*Source: Monster Manual (2024) p. 287*  

Slaad lords create death slaadi by infusing gray slaadi with a portion of their chaotic energy. When groups of slaadi act deliberately, death slaadi are often behind their designs.

## Slaadi

*Chaos-Spawned Hordes of Limbo*

- **Habitat.** Planar (Limbo)  
- **Treasure.** Any  

Unpredictable slaadi devour and multiply across the Ever-Changing Chaos of Limbo. These toad-like, extraplanar beings embody the endless potentiality of their home plane of existence. While slaadi aren't inherently evil, their impulses are wild and often destructive. Many are driven to propagate through supernatural processes. Unfortunately, these processes typically are fatal for other creatures.

Slaadi have no formal society. Rather, strong slaadi dominate weaker ones. Blue and red slaadi rampage across Limbo and spill into other worlds at the direction of green slaadi. More powerful slaadi have connections to the Spawning Stone, a source of chaotic magic from which the first slaadi originated. The Spawning Stone is hidden deep within Limbo, and legends tie its origins to the modron overlord Primus or the ruinous slaad lords, such as Ssendam, the golden amoeboid terror, and Ygorl, the winged skeleton. These slaad lords and others plot to spread slaadi across the multiverse.

> [!note] Slaad Control Gems
> 
> A slaad born from the Spawning Stone has a magical control gem embedded in its head. If a creature claims the gem, the slaad has the [Charmed](/3-Mechanics/CLI/conditions.md#Charmed) condition and obeys the gem's bearer. The slaad ceases to be [Charmed](/3-Mechanics/CLI/conditions.md#Charmed) if it is harmed by the gem's bearer or the bearer's allies or if the gem is returned to the slaad. A [Greater Restoration](/3-Mechanics/CLI/spells/greater-restoration-xphb.md) spell cast on a slaad destroys the gem, and the slaad ceases to be [Charmed](/3-Mechanics/CLI/conditions.md#Charmed).
> 
> One can obtain a slaad's control gem using a [Wish](/3-Mechanics/CLI/spells/wish-xphb.md) or [Imprisonment](/3-Mechanics/CLI/spells/imprisonment-xphb.md) spell. If the slaad fails its saving throw against [Imprisonment](/3-Mechanics/CLI/spells/imprisonment-xphb.md), the caster gains the gem, and the slaad isn't imprisoned. An [Incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated) slaad's control gem can be removed by spending 1 minute and succeeding on a DC 20 Wisdom ([Medicine](/3-Mechanics/CLI/skills.md#Medicine)) check. Failing this check deals 22 (`4d10`) Piercing damage to the slaad.
^slaad-control-gems

> [!quote] A quote from Jebeel Sloom  
> 
> Fight a slaad and lose, the story's over. Fight a slaad and win, there's a thousand more standing in line just to prove they're tougher.

```statblock
"name": "Death Slaad (XMM)"
"size": "Medium"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"hp": !!int "178"
"hit_dice": "21d8 + 84"
"modifier": !!int "10"
"stats":
  - !!int "20"
  - !!int "15"
  - !!int "19"
  - !!int "15"
  - !!int "10"
  - !!int "19"
"speed": "40 ft."
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+8"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., [darkvision](/3-Mechanics/CLI/senses.md#Darkvision)\
  \ 60 ft., passive Perception 18"
"languages": "Common, Slaad; telepathy 60 ft."
"cr": "10"
"traits":
  - "desc": "The slaad has [Advantage](/3-Mechanics/CLI/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The slaad regains 10 [Hit Points](/3-Mechanics/CLI/variant-rules/hit-points-xphb.md)\
      \ at the start of each of its turns if it has at least 1 [Hit Point](/3-Mechanics/CLI/variant-rules/hit-points-xphb.md)."
    "name": "Regeneration"
"actions":
  - "desc": "The slaad makes two Chaos Blade attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 10 ft. *Hit:* 11 (1d12 + 5) Slashing damage\
      \ plus 10 (3d6) Necrotic damage. Until the start of the slaad's next turn, the\
      \ target has a condition determined by rolling 1d4: on a 1, [Charmed](/3-Mechanics/CLI/conditions.md#Charmed);\
      \ on a 2, [Frightened](/3-Mechanics/CLI/conditions.md#Frightened); on a 3, [Poisoned](/3-Mechanics/CLI/conditions.md#Poisoned);\
      \ or on a 4, [Incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)."
    "name": "Chaos Blade"
  - "desc": "The slaad casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 16):\n\n**At\
      \ will:** [Detect Magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md), [Detect\
      \ Thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md), [Invisibility](/3-Mechanics/CLI/spells/invisibility-xphb.md)\
      \ (self only), [Mage Hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md), [Major\
      \ Image](/3-Mechanics/CLI/spells/major-image-xphb.md)\n\n**1/day each:** [Blight](/3-Mechanics/CLI/spells/blight-xphb.md)\
      \ (level 8 version), [Cloudkill](/3-Mechanics/CLI/spells/cloudkill-xphb.md)\
      \ (level 6 version), [Fly](/3-Mechanics/CLI/spells/fly-xphb.md), [Plane Shift](/3-Mechanics/CLI/spells/plane-shift-xphb.md),\
      \ [Tongues](/3-Mechanics/CLI/spells/tongues-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The slaad shape-shifts into a Small or Medium Humanoid, or it returns\
      \ to its true form. Other than its size, its game statistics are the same in\
      \ each form. Any equipment it is wearing or carrying isn't transformed."
    "name": "Shape-Shift"
"source":
  - "XMM"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/death-slaad-xmm.webp"
```
^statblock

## Environment

planar, limbo

---

#  Todesslaad
_Chaosgezüchtete Horden des Limbo_

>**Habitat:** Planar (Limbo)
>**Beute:** Alles

Unberechenbare Slaadi verschlingen und vermehren sich im ständig wechselnden Chaos von Limbo. Diese krötenähnlichen, außereuropäischen Wesen verkörpern die unendliche Potenzialität ihrer heimatlichen Ebene der Existenz. Obwohl die Slaadi nicht von Natur aus böse sind, sind ihre Triebe wild und oft zerstörerisch. Viele werden dazu getrieben, sich durch übernatürliche Prozesse fortzupflanzen. Leider sind diese Prozesse in der Regel tödlich für andere Kreaturen.

Slaadi haben keine formelle Gesellschaft. Vielmehr dominieren die starken Slaadi die schwächeren. Blaue und rote Slaadi wüten in Limbo und dringen auf Anweisung der grünen Slaadi in andere Welten vor. Mächtigere Slaadi haben Verbindungen zum Quellstein, einer Quelle chaotischer Magie, aus der die ersten Slaadi hervorgegangen sind. Der Quellstein ist tief in Limbo verborgen, und Legenden verbinden seinen Ursprung mit dem Modron-Oberherrn Primus oder den ruinösen Slaad-Lords wie Ssendam, dem goldenen amöboiden Schrecken, und Ygorl, dem geflügelten Skelett. Diese Slaad-Lords und andere planen, Slaadi über das Multiversum zu verbreiten.

>[!info] Slaad-Kontrolljuwelen
>Ein Slaad, der aus dem Laichstein geboren wird, hat einen magischen Kontrollstein in seinem Kopf. Wenn eine Kreatur den Edelstein für sich beansprucht, ist der Slaad verzaubert und gehorcht dem Träger des Edelsteins. Der Slaad hört auf, verzaubert zu sein, wenn er vom Träger des Edelsteins oder von dessen Verbündeten verletzt wird oder wenn der Edelstein an den Slaad zurückgegeben wird. Ein Großer Wiederherstellungszauber, der auf einen Slaad gewirkt wird, zerstört den Edelstein, und der Slaad ist nicht mehr verzaubert. Man kann den Kontrolledelstein eines Slaads mit einem Wunsch- oder Gefangenschaftszauber erhalten. Wenn der Slaad seinen Schutzwurf gegen die Gefangenschaft nicht besteht, erhält der Zaubernde den Edelstein, und der Slaad ist nicht gefangen. Der Kontroll-Edelstein eines entmündigten Slaads kann entfernt werden, indem er 1 Minute braucht und eine DC 20 Weisheit (Medizin) Probe besteht. Wird diese Prüfung nicht bestanden, erleidet der Slaad 22 (4d10) durchbohrenden Schaden.

>[!quote] Jebeel Sloom, Reiseführer zur Ebene des Limbos
>Wenn du gegen einen Slaad kämpfst und verlierst, ist die Geschichte zu Ende. Wenn du gegen einen Slaad kämpfst und gewinnst, stehen tausend andere Schlange, um zu beweisen, dass sie härter sind.

## Todesslaad
Slaad-Lords erschaffen Todesslaadi, indem sie graue Slaadi mit einem Teil ihrer chaotischen Energie infundieren. Wenn Gruppen von Slaadi vorsätzlich handeln, stecken oft Todesslaadi hinter ihren Plänen.

![](Death-Slaad-2024.webp)

```statblock
name: Todesslaad (2024)
image: pictures/death-slaad-2024.webp
source: Monsterhandbuch 2024
size: Mittelgroß
type: Aberration
alignment: Chaotisch Böse
ac: 18
hp: 178
hit_dice: 21d8 + 84
ini: +10 (20)
speed: 12 Meter
stats: [20, 15, 19, 15, 10, 19]
saves:
  - STR: +5
  - GES: +2
  - KON: +4
  - INT: +2
  - WEI: +0
  - CHA: +4
skillsaves:
  - Arkane Kunde: 6
  - Wahrnehmung: 8
damage_vulnerabilities: ""
damage_resistances: "Blitz, Feuer, Kälte, Säure, Schall"
damage_immunities: ""
condition_immunities: ""
gear: ""
senses: [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Blindsicht|Blindsicht]] 18 Meter, [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Dunkelsicht|Dunkelsicht]] 18 Meter, passive Wahrnehmung 18
languages: Gemeinsprache, Slaad; telepatisch 18 Meter
cr: 10
bestiary: true
traits:
  - name: Magische Resistenz.
    desc: "Der Slaad ist bei Rettungswürfen gegen Zauber und andere magische Effekte im Vorteil."
  - name: Regeneration.
    desc: "Der Slaad erhält zu Beginn seines Zuges 20 TP zurück, wenn er zum Beginn seines Zuges mindestens 1 Trefferpunkt besitzt."
actions:
  - name: Mehrfachangriff.
    desc: "Der Slaad führt zwei Chaosklingen-Angriffe aus."
  - name: Chaosklinge.
    desc: "_Nahkampfangriffswurf:_ +9, Reichweite 3m. _Treffer:_ 11 (1d12 + 5) Hiebschaden plus 10 (3d6) nekrotischer Schaden. Bis zum Beginn des nächsten Zuges des Slaad leidet das Ziel unter einem der folgenden Zustände, die durch den Wurf eines d4 bestimmt werden: 1: [[Anhang PH-A#Bezaubert|Bezaubert]], 2: [[Anhang PH-A#Kampfunfähig|Kampfunfähig]], 3: [[Anhang PH-A#Verängstigt|Verängstigt]], 4: [[Anhang PH-A#Vergiftet|Vergiftet]]"
    attack_bonus: 9
    damage_dice: 1d12
    damage_bonus: 5
  - name: Zauberwirken.
    desc: "Der Slaad wirkt einen der folgenden Zauber, ohne Komponenten zu benötigen. Seine Zauberfertigkeit ist Charisma (Zauber-Rettungswurf SG 16):"
  - name: Beliebig oft
    desc: "[Gedanken wahrnehmen](Gedanken-wahrnehmen.md), [Mächtiges Trugbild](Mächtiges-Trugbild.md) [Magie entdecken](Magie-entdecken.md), [Magierhand](Magierhand.md), [Unsichtbarkeit](Unsichtbarkeit.md) (nur selbst)"
  - name: je 1-mal täglich.
    desc: "[Dürre](Dürre.md) (Zaubergrad 8), [Ebenenwechsel](Ebenenwechsel.md), [Fliegen](Zauber/Fliegen.md), [Todeswolke](Todeswolke.md) (Zaubergrad 6), [Zungen](Zungen.md)"
bonus_actions:
  - name: Gestaltwandeln.
    desc: "Der Slaad verwandelt sich in einen kleinen oder mittelgroßen Humanoiden oder er kehrt in seine wahre Gestalt zurück. Abgesehen von ihrer Größe sind ihre Spielstatistiken in jeder Form gleich. Jegliche Ausrüstung, die er trägt, wird nicht transformiert."
```