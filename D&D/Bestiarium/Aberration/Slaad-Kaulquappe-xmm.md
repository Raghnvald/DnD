---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung: Slaad-Kaulquappe
Typ: Aberration
Größe: Winzig
HG: 1/8
Habitat: Planar (Limbo)
status: WIP
image: 
tags:
  - Quelle/5e/xmm
  - Monster/HG/1-8
  - Monster/Habitat/limbo
  - Monster/Habitat/planar
  - Monster/Größe/Winzig
  - Monster/Typ/Aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Slaad Tadpole
---
# [Slaad Tadpole](3-Mechanics\CLI\bestiary\aberration/slaad-tadpole-xmm.md)
*Source: Monster Manual (2024) p. 284, Player's Handbook (2024) p. 357. Available in the Free Rules (2024)*  

Slaad tadpoles are ravenous, newborn slaadi. They hatch from eggs implanted into living hosts by red slaadi, but they also appear in great numbers in Limbo and other chaotic realms. Under most conditions, a slaad tadpole transforms into a blue slaad—or a green slaad if its host was able to cast spells of level 3 or higher—within `2d12` hours of hatching.

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
"name": "Slaad Tadpole (XMM)"
"size": "Tiny"
"type": "aberration"
"alignment": "Chaotic Neutral"
"ac": !!int "12"
"hp": !!int "7"
"hit_dice": "3d4"
"modifier": !!int "2"
"stats":
  - !!int "7"
  - !!int "15"
  - !!int "10"
  - !!int "3"
  - !!int "5"
  - !!int "3"
"speed": "30 ft., burrow 10 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 7"
"languages": "understands Slaad but can't speak"
"cr": "1/8"
"traits":
  - "desc": "The slaad has [Advantage](/3-Mechanics/CLI/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage."
    "name": "Bite"
"source":
  - "XMM"
  - "XPHB"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/slaad-tadpole-xmm.webp"
```
^statblock

## Environment

planar, limbo

--- 

# Slaad-Kaulquappe
_Chaosgezüchtete Horden des Limbo_

>**Habitat:** Planar (Limbo)
>**Beute:** Alles

Unberechenbare Slaadi verschlingen und vermehren sich im ständig wechselnden Chaos von Limbo. Diese krötenähnlichen, außereuropäischen Wesen verkörpern die unendliche Potenzialität ihrer heimatlichen Ebene der Existenz. Obwohl die Slaadi nicht von Natur aus böse sind, sind ihre Triebe wild und oft zerstörerisch. Viele werden dazu getrieben, sich durch übernatürliche Prozesse fortzupflanzen. Leider sind diese Prozesse in der Regel tödlich für andere Kreaturen.

Slaadi haben keine formelle Gesellschaft. Vielmehr dominieren die starken Slaadi die schwächeren. Blaue und rote Slaadi wüten in Limbo und dringen auf Anweisung der grünen Slaadi in andere Welten vor. Mächtigere Slaadi haben Verbindungen zum Quellstein, einer Quelle chaotischer Magie, aus der die ersten Slaadi hervorgegangen sind. Der Quellstein ist tief in Limbo verborgen, und Legenden verbinden seinen Ursprung mit dem Modron-Oberherrn Primus oder den ruinösen Slaad-Lords wie Ssendam, dem goldenen amöboiden Schrecken, und Ygorl, dem geflügelten Skelett. Diese Slaad-Lords und andere planen, Slaadi über das Multiversum zu verbreiten.

>[!info] Slaad-Kontrolljuwelen
>Ein Slaad, der aus dem Laichstein geboren wird, hat einen magischen Kontrollstein in seinem Kopf. Wenn eine Kreatur den Edelstein für sich beansprucht, ist der Slaad verzaubert und gehorcht dem Träger des Edelsteins. Der Slaad hört auf, verzaubert zu sein, wenn er vom Träger des Edelsteins oder von dessen Verbündeten verletzt wird oder wenn der Edelstein an den Slaad zurückgegeben wird. Ein Großer Wiederherstellungszauber, der auf einen Slaad gewirkt wird, zerstört den Edelstein, und der Slaad ist nicht mehr verzaubert. Man kann den Kontrolledelstein eines Slaads mit einem Wunsch- oder Gefangenschaftszauber erhalten. Wenn der Slaad seinen Schutzwurf gegen die Gefangenschaft nicht besteht, erhält der Zaubernde den Edelstein, und der Slaad ist nicht gefangen. Der Kontroll-Edelstein eines entmündigten Slaads kann entfernt werden, indem er 1 Minute braucht und eine DC 20 Weisheit (Medizin) Probe besteht. Wird diese Prüfung nicht bestanden, erleidet der Slaad 22 (4d10) durchbohrenden Schaden.

>[!quote] Jebeel Sloom, Reiseführer zur Ebene des Limbos
Wenn du gegen einen Slaad kämpfst und verlierst, ist die Geschichte zu Ende. Wenn du gegen einen Slaad kämpfst und gewinnst, stehen tausend andere Schlange, um zu beweisen, dass sie härter sind.

## Slaad-Kaulquappe
Slaad-Larven sind gefräßige, neugeborene Slaadi. Sie schlüpfen aus Eiern, die von roten Slaadi in lebende Wirte eingepflanzt wurden, aber sie kommen auch in großer Zahl in Limbo und anderen chaotischen Reichen vor. Unter den meisten Bedingungen verwandelt sich eine Slaad-Larve innerhalb von `2d12` Stunden nach dem Schlüpfen in einen blauen Slaad - oder einen grünen Slaad, wenn ihr Wirt in der Lage war, Zauber der Stufe 3 oder höher zu wirken.

![](Slaad-Tadpole-2024.webp)