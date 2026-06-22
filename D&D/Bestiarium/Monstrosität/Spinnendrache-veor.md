---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Spiderdragon
Image: token/spiderdragon-veor.webp
status: WIP
linter-yaml-title-alias: Spiderdragon
tags:
  - Monster/Größe/Riesig
  - Monster/HG/11
  - Monster/Typ/Monstrosität
  - Quelle/5e/veor
aliases:
  - Spiderdragon
---
# [Spiderdragon](3-Mechanics\CLI\bestiary\monstrosity/spiderdragon-veor.md)
*Source: Vecna: Eve of Ruin p. 233*  

Jene schrecklichen Kreaturen, die als Spinnendrachen bekannt sind, wurden zuerst in den tiefsten Tiefen des Unterreichs gefunden. Sie stammen von Nestlingen schwarzer Drachen ab, die sich ausschließlich von Spinnen ernähren. Obwohl Spinnendrachen nicht im Abyss oder von Lolths Anhängern erschaffen wurden, behaupten diese, Spinnendrachen seien ein Geschenk ihrer Gottheit, da sie in den Gegenden des Unterreichs am häufigsten anzutreffen sind, die Lolths Anhänger als die ihren beanspruchen. Die Anhänger setzen Spinnendrachen oft als Wächter ein oder behandeln sie als geschätzte Gäste. Die Kreaturen sind zwar nicht so mächtig wie ihre Ahnen, die schwarzen Drachen, aber mit ihren selbstsüchtigen Forderungen verzehren sie dennoch häufig sämtliche Ressourcen einer Enklave. 

Spinnendrachen bauen sich keine Horte, sondern weben mächtige Netze und fressen Unmengen von Beute, ehe sie das Interesse an einer Gegend verlieren und weiterziehen, egal, wie sehr sie hofiert wurden. Im Gegensatz zu schwarzen Drachen sind Spinnendrachen nicht allzu schlau. Dennoch begreifen einige Exemplare, was sie den Anhängern von Lolth bedeuten, und nutzen diese Position so lange wie möglich aus. 

```statblock
"name": "Spiderdragon (VEoR)"
"size": "Huge"
"type": "monstrosity"
"alignment": "typically  Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "152"
"hit_dice": "16d12 + 48"
"modifier": !!int "4"
"stats":
  - !!int "21"
  - !!int "18"
  - !!int "16"
  - !!int "7"
  - !!int "14"
  - !!int "18"
"speed": "50 ft., climb 60 ft."
"saves":
  - "strength": !!int "9"
  - "dexterity": !!int "8"
"skillsaves":
  - "name": "Intimidation"
    "desc": "+8"
  - "name": "Perception"
    "desc": "+6"
"damage_resistances": "poison, psychic"
"senses": "darkvision 90 ft., passive Perception 16"
"languages": "Abyssal, Draconic, Undercommon"
"cr": "11"
"traits":
  - "desc": "The spiderdragon has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The spiderdragon can climb difficult surfaces, including upside down\
      \ on ceilings, without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "The spiderdragon ignores movement restrictions caused by webbing."
    "name": "Web Walker"
"actions":
  - "desc": "The spiderdragon makes one Bite attack and two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target. *Hit:* 10\
      \ (1d10 + 5) piercing damage plus 13 (2d12) poison damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d6 + 5) slashing damage."
    "name": "Claw"
  - "desc": "The spiderdragon exhales venomous spiderlings in a 30-foot cone. Each\
      \ creature in that area must make a DC 15 Dexterity saving throw, taking 33\
      \ (6d10) piercing damage and 33 (6d10) poison damage on a failed save or half\
      \ as much damage on a successful one."
    "name": "Spiderling Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "The spiderdragon spins a 30-foot cube of strong, sticky webbing in an\
      \ area adjacent to itself. The webbing lasts for 1 minute, is difficult terrain,\
      \ and lightly obscures its area. A creature that starts its turn in the webbing\
      \ or enters the webbing for the first time on its turn must succeed on a DC\
      \ 15 Dexterity saving throw or have the restrained condition while in the web.\
      \ As an action, a creature can free itself or another creature from the web\
      \ by succeeding on a DC 15 Strength check.\n\nA 5-foot cube of the web is destroyed\
      \ if it takes at least 10 acid, fire, or slashing damage on a single turn."
    "name": "Stifling Webs (Recharge 5-6)"
"source":
  - "VEoR"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/spiderdragon-veor.webp"
```
^statblock

> [!statblock] Spinnendrache
> ![[token/spiderdragon-veor.webp|right|100]]
> *Riesige Monstrosität, typischerweise Chaotisch Böse*
> 
> - **Rüstungsklasse** 17 (natürliche Rüstung)
> - **Trefferpunkte** 152 (`16d12 + 48`)
> - **Bewegungsrate** 15 Meter, Klettern 18 Meter
> 
> |STR|GES|KON|INT|WEI|CHA|
> |:---:|:---:|:---:|:---:|:---:|:---:|
> | 21 (+5)|18 (+4)|16 (+3)|7 (-2)|14 (+2)|18 (+4)|
> 
> - **Rettungswürfe** STR +9, GES +8
> - **Fertigkeiten** [[Fertigkeiten-phb#Einschüchtern|Einschüchtern]] +8, [[Fertigkeiten-phb#Wahrnehmung|Wahrnehmung]] +6
> - **Schadensresistenzen** Gift, Psychisch
> - **Schadensimmunitäten** -
> - **Zustandsimmunitäten** -
> - **Sinne** [[Sinne-phb#Dunkelsicht|Dunkelsicht]] 27 Meter, passive Wahrnehmung 16
> - **Sprachen** Abyssisch, Drakonisch, Gemeinsprache der Unterreiche
> - **Herausforderungsgrad** 11 (7.200 EP)
> - **Übungsbonus** +4
> 
> ## Merkmale
> 
> ***Magieresistenz.*** Der Spinnendrache ist bei Rettungswürfen gegen Zauber und andere magische Effekte im Vorteil.
> 
> ***Netzwandler.*** Der Spinnendrache ignoriert Bewegungseinschränkungen, die durch Netze verursacht werden.
> 
> ***Spinnenklettern.*** Der Spinnendrache kann ohne Attributswürfe schwierige Oberflächen erklimmen und sich kopfüber an Decken entlang bewegen. 
> 
> ## Aktionen
> 
> ***Mehrfachangriff.*** Der Spinnendrache führt einen Biss-Angriff und zwei Klaue-Angriffe durch.
> 
> ***Biss.*** *Nahkampf-Waffenangriff:* +9 zum Treffen, Reichweite 3 Meter, ein Ziel. *Treffer:* 10 (`1d10 + 5`) Stichschaden plus 13 (`2d12`) Giftschaden.
> 
> ***Klaue.*** *Nahkampf-Waffenangriff:* +9 zum Treffen, Reichweite 1,5 Meter, ein Ziel. *Treffer:* 12 (`2W6 + 5`) Hiebschaden.
> 
> ***Spinnling-Odem (Aufladung 5–6).*** Der Spinnendrache atmet in einem Kegel von neun Metern giftige Spinnlinge aus. Jede Kreatur in diesem Bereich muss einen `SG-15-Geschicklichkeits-Rettungswurf` ausführen. Scheitert der Wurf, so erleidet sie 33 (`6d10`) Stichschaden und 33 (`6d10`) Giftschaden, anderenfalls die Hälfte. 
> 
> ## Bonusaktionen
> 
> ***Erstickende Netze (Aufladung 5–6).*** Der Spinnendrache spinnt einen Würfel von neun Metern Kantenlänge aus starken, klebrigen Netzen in einem Bereich neben sich. Die Netze bleiben eine Minute lang bestehen, sind schwieriges Gelände und verschleiern diesen Bereich leicht. Eine Kreatur, die ihren Zug im Netz beginnt oder das Netz in ihrem Zug erstmals betritt, muss einen `SG-15-Geschicklichkeits-Rettungswurf` bestehen, oder sie ist festgesetzt, solange sie sich im Netz aufhält. Eine Kreatur kann als Aktion sich selbst oder eine andere Kreatur aus dem Netz befreien, sofern sie einen `SG-15-Stärkewurf` besteht. 
> Ein Würfel von 1,5 Metern Kantenlänge des Netzes wird zerstört, wenn es mindestens 10 Feuer-, Hieb- oder Säureschaden in einem einzigen Zug erleidet.