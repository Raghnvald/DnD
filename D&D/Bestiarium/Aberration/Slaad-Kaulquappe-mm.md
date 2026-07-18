---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Slaad-Kaulquappe
Kategorie: Aberration
Größe: Winzig
HG: 1/8
Status: WIP
linter-yaml-title-alias: Slaad-Kaulquappe
tags:
  - Monster/Größe/Winzig
  - Monster/HG/1-8
  - Monster/Typ/Aberration
  - Quelle/5e/mm
aliases:
  - Slaad-Kaulquappe
status: WIP
---
# Slaad-Kaulquappe
*Quelle: Monsterhandbuch S. 258*  

## Slaadi

Im Immerwandelnden Chaos des Limbus treiben Stücke von Wäldern und Wiesen, zerstörten Burgen und isolierten Inseln durch einen Tumult von Feuer, Wasser, Erde und Wind. Die wichtigsten Bewohner dieser lebensfeindlichen Ebene sind die krötenartigen Slaadi. Slaadi sind undiszipliniert und haben keine formelle Hierarchie, doch schwächere Slaadi gehorchen den stärkeren, wenn ihnen mit Auslöschung gedroht wird.

### Der Brutstein

Vor langer Zeit erschuf Primus, Gebieter der Modrons, einen gigantischen, geometrisch komplexen Stein, der von der Macht des Gesetzes erfüllt war. Er warf diesen in den Limbus, im Glauben, dass der Stein Ordnung ins Chaos bringen und die Ausbreitung des Chaos auf andere Ebenen verhindern würde. Als die Macht des Steins wuchs, wurde es für Kreaturen mit geordnetem Geist, wie Modrons und Githzerai, möglich, Enklaven im Limbus zu erschaffen. Allerdings hatte Primus' Schöpfung eine unvorhergesehene Nebenwirkung: die chaotische Energie, die vom Stein absorbiert wurde, erschuf die Monster, die heute als Slaadi bekannt sind. Gelehrte bezeichnen Primus' gewaltige Schöpfung aus diesem Grund als den Brutstein. Die Slaadi löschten jede Modron-Enklave im Limbus aus. Als Kreaturen des absoluten Chaos verabscheuen Slaadi Modrons und greifen sie an, wenn sie sie erblicken. Nichtsdestotrotz steht Primus zu seiner Schöpfung und sieht die Slaadi entweder nicht als Bedrohung oder ignoriert sie.

### Geburt und Verwandlung

Slaadi haben einen grauenvollen Fortpflanzungszyklus. Slaadi vermehren sich, indem sie entweder Eier in humanoide Wirte einpflanzen oder sie mit einer verwandelnden Krankheit anstecken, die als Chaosphage bekannt ist. Jede Farbe der Slaadi vermehrt oder verwandelt sich auf andere Weise. Rote Slaadi bringen blaue und grüne Slaadi hervor, und die blauen Slaadi erschaffen rote und grüne Slaadi.Jeder grüne Slaad durchläuft einen lebenslangen Zyklus der Verwandlung in die mächtigeren grauen Slaadi und Todesslaadi. Bei jeder Verwandlung behält der Slaad seine Erinnerungen.

### Gestaltwandler

Einige Slaadi können sich in die humanoiden Kreaturen verwandeln, aus denen sie ursprünglich hervorgegangen sind. Diese Slaadi kehren auf die Materielle Ebene zurück, um in der Gestalt ihres ehemaligen Selbst für Chaos zu sorgen.

> [!note] Variante: Slaadi-Kontrolljuwelen
> 
> Wenn ein Slaad aus dem Brutstein geboren wird, implantiert der Stein auf magische Weise ein Fragment seiner Selbst im Gehirn des Slaad. Dieses Fragment nimmt die Gestalt eines magischen Juwels an, das ungefähr die Größe und Form der Faust eines menschlichen Kindes hat. Das Juwel hat die gleiche Farbe wie der Slaad. Eine andere Kreatur kann Magie verwenden, um das Juwel herauszuziehen und es verwenden, um den Slaad zu unterwerfen. Der Slaad muss demjenigen gehorchen, der das Juwel in Besitz hat. Wenn das Juwel des Slaad zerstört wird, kann der Slaad nicht mehr auf diese Weise kontrolliert werden. Ein Slaad, der auf andere Weise als aus einem Brutstein geboren wird, hat kein Juwel in seinem Gehirn, doch er erhält eines, wenn er jemals in Kontakt mit dem Brutstein kommt. Slaadi im Limbus werden vom Brutstein angelockt, sodass die meisten von ihnen irgendwann ein Juwel besitzen. Ein Slaad mit einem Kontrolljuwel im Gehirn hat das folgende zusätzliche Merkmal.
> 
> **Kontrolljuwel.** In das Gehirn des Slaad ist ein magisches Kontrolljuwel eingesetzt. Der Slaad muss demjenigen gehorchen, der das Juwel in seinem Besitz hat, und kann nicht [[Zustände-phb#Bezaubert|bezaubert]] werden, solange er auf diese Weise kontrolliert wird. Bestimmte Zauber können verwendet werden, um das Juwel zu erlangen. Wenn der Slaad seinen Rettungswurf gegen [[Einkerkerung-phb|Einkerkerung]] nicht schafft, kann der Zauber das Juwel in die offene Handfläche des Zauberwirkers übertragen anstatt den Slaad einzuschließen. Ein [[Wunsch-phb|Wunsch]]-Zauber, der in der Präsenz des Slaad gewirkt wird, kann so formuliert werden, dass der Zauberwirker das Juwel erhält.
> 
> Der Zauber [[Vollständige_Genesung-phb|Vollständige Genesung]], wenn er auf den Slaad gewirkt wird, zerstört das Juwel, ohne dem Slaad zu schaden.
> 
> Jemand mit Übung in Weisheit ([[Fertigkeiten-phb#Heilkunde|Heilkunde]]) kann das Juwel aus einem [[Zustände-phb#Kampfunfähig|kampfunfähigen]] Slaad entfernen. Jeder Versuch erfordert 1 Minute ununterbrochener Arbeit und einen erfolgreichen Wurf auf Weisheit ([[Fertigkeiten-phb#Heilkunde|Heilkunde]]) gegen SG 20. Jeder misslungene Versuch fügt dem Slaad 22 (`4d10`) Psychischen Schaden zu.
^variant-slaad-control-gems

> [!quote]  
> 
> In das Gehirn eines Slaad ist ein magisches Juwel eingesetzt. Wenn du es erlangst, kannst du den Slaad kontrollieren.

```statblock
"name": "Slaad Tadpole"
"size": "Tiny"
"type": "aberration"
"alignment": "Chaotic Neutral"
"ac": !!int "12"
"hp": !!int "10"
"hit_dice": "4d4"
"modifier": !!int "2"
"stats":
  - !!int "7"
  - !!int "15"
  - !!int "10"
  - !!int "3"
  - !!int "5"
  - !!int "3"
"speed": "30 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 7"
"languages": "understands Slaad but can't speak"
"cr": "1/8"
"traits":
  - "desc": "The slaad has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4\
      \ + 2) piercing damage."
    "name": "Bite"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/slaad-tadpole.webp"
```
^statblock