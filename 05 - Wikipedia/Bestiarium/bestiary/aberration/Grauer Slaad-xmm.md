---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/xmm
  - Monster/HG/9
  - Monster/Habitat/limbo
  - Monster/Habitat/planar
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Gray Slaad
---
# Grauer Slaad
*Source: Monster Manual (2024) p. 286*  

Graue Slaadi entstehen aus grünen Slaadi, die durch den Laichstein oder Slaad-Lords transformiert wurden. Sie erforschen die Ebenen auf der Suche nach humanoiden Gemeinschaften, die sie in der Nähe der planaren Pfade überfallen.

## Slaadi
_Chaosgezüchtete Horden des Limbo_

>**Habitat:** Planar (Limbo)
>**Beute:** Alles

Unberechenbare Slaadi verschlingen und vermehren sich im ständig wechselnden Chaos von Limbo. Diese krötenähnlichen, außereuropäischen Wesen verkörpern die unendliche Potenzialität ihrer heimatlichen Ebene der Existenz. Obwohl die Slaadi nicht von Natur aus böse sind, sind ihre Triebe wild und oft zerstörerisch. Viele werden dazu getrieben, sich durch übernatürliche Prozesse fortzupflanzen. Leider sind diese Prozesse in der Regel tödlich für andere Kreaturen.

Slaadi haben keine formelle Gesellschaft. Vielmehr dominieren die starken Slaadi die schwächeren. Blaue und rote Slaadi wüten in Limbo und dringen auf Anweisung der grünen Slaadi in andere Welten vor. Mächtigere Slaadi haben Verbindungen zum Quellstein, einer Quelle chaotischer Magie, aus der die ersten Slaadi hervorgegangen sind. Der Quellstein ist tief in Limbo verborgen, und Legenden verbinden seinen Ursprung mit dem Modron-Oberherrn Primus oder den ruinösen Slaad-Lords wie Ssendam, dem goldenen amöboiden Schrecken, und Ygorl, dem geflügelten Skelett. Diese Slaad-Lords und andere planen, Slaadi über das Multiversum zu verbreiten.

>[!info] Slaad-Kontrolljuwelen
>Ein Slaad, der aus dem Laichstein geboren wird, hat einen magischen Kontrollstein in seinem Kopf. Wenn eine Kreatur den Edelstein für sich beansprucht, ist der Slaad verzaubert und gehorcht dem Träger des Edelsteins. Der Slaad hört auf, verzaubert zu sein, wenn er vom Träger des Edelsteins oder von dessen Verbündeten verletzt wird oder wenn der Edelstein an den Slaad zurückgegeben wird. Ein Großer Wiederherstellungszauber, der auf einen Slaad gewirkt wird, zerstört den Edelstein, und der Slaad ist nicht mehr verzaubert. Man kann den Kontrolledelstein eines Slaads mit einem Wunsch- oder Gefangenschaftszauber erhalten. Wenn der Slaad seinen Schutzwurf gegen die Gefangenschaft nicht besteht, erhält der Zaubernde den Edelstein, und der Slaad ist nicht gefangen. Der Kontroll-Edelstein eines entmündigten Slaads kann entfernt werden, indem er 1 Minute braucht und eine DC 20 Weisheit (Medizin) Probe besteht. Wird diese Prüfung nicht bestanden, erleidet der Slaad 22 (4d10) durchbohrenden Schaden.
^slaad-control-gems

>[!quote] Jebeel Sloom, Reiseführer zur Ebene des Limbos
>Wenn du gegen einen Slaad kämpfst und verlierst, ist die Geschichte zu Ende. Wenn du gegen einen Slaad kämpfst und gewinnst, stehen tausend andere Schlange, um zu beweisen, dass sie härter sind.

---

```statblock
"name": "Gray Slaad (XMM)"
"size": "Medium"
"type": "aberration"
"alignment": "Chaotic Neutral"
"ac": !!int "18"
"hp": !!int "150"
"hit_dice": "20d8 + 60"
"modifier": !!int "7"
"stats":
  - !!int "19"
  - !!int "17"
  - !!int "16"
  - !!int "13"
  - !!int "8"
  - !!int "18"
"speed": "40 ft."
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., [darkvision](/3-Mechanics/CLI/senses.md#Darkvision)\
  \ 60 ft., passive Perception 17"
"languages": "Common, Slaad; telepathy 60 ft."
"cr": "9"
"traits":
  - "desc": "The slaad has [Advantage](/3-Mechanics/CLI/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The slaad regains 10 [Hit Points](/3-Mechanics/CLI/variant-rules/hit-points-xphb.md)\
      \ at the start of each of its turns if it has at least 1 [Hit Point](/3-Mechanics/CLI/variant-rules/hit-points-xphb.md)."
    "name": "Regeneration"
"actions":
  - "desc": "The slaad makes two Chaos Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +8, reach 10 ft. *Hit:* 9 (1d10 + 4) Slashing damage\
      \ plus 11 (2d10) Necrotic damage. Until the start of the slaad's next turn,\
      \ the target has a condition determined by rolling 1d4: on a 1, [Charmed](/3-Mechanics/CLI/conditions.md#Charmed);\
      \ on a 2, [Frightened](/3-Mechanics/CLI/conditions.md#Frightened); on a 3, [Poisoned](/3-Mechanics/CLI/conditions.md#Poisoned);\
      \ or on a 4, [Incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)."
    "name": "Chaos Claw"
  - "desc": "The slaad casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 16):\n\n**At\
      \ will:** [Detect Magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md), [Detect\
      \ Thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md), [Invisibility](/3-Mechanics/CLI/spells/invisibility-xphb.md)\
      \ (self only), [Mage Hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md), [Major\
      \ Image](/3-Mechanics/CLI/spells/major-image-xphb.md)\n\n**1/day each:** [Cloudkill](/3-Mechanics/CLI/spells/cloudkill-xphb.md),\
      \ [Fly](/3-Mechanics/CLI/spells/fly-xphb.md), [Plane Shift](/3-Mechanics/CLI/spells/plane-shift-xphb.md)\
      \ (self only), [Tongues](/3-Mechanics/CLI/spells/tongues-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The slaad shape-shifts into a Small or Medium Humanoid, or it returns\
      \ to its true form. Other than its size, its game statistics are the same in\
      \ each form. Any equipment it is wearing or carrying isn't transformed."
    "name": "Shape-Shift"
"source":
  - "XMM"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/gray-slaad-xmm.webp"
```
^statblock

## Environment

planar, limbo