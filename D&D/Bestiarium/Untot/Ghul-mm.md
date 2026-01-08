---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung:
Typ: Untoter
Größe: Mittelgroß
HG: 1
Habitat:
  - Stadt
  - Sumpf
  - Unterreich
status: WIP
image:
tags:
  - Quelle/5e/mm
  - Monster/Typ/Untote
  - Monster/Größe/Mittelgroß
  - Monster/HG/1
  - Monster/Habitat/Stadt
  - Monster/Habitat/Sumpf
  - Monster/Habitat/Unterreich
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Ghoul
---
# [Ghoul](3-Mechanics\CLI\bestiary\undead/ghoul.md)
*Source: Monster Manual p. 148. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

Ghouls roam the night in packs, driven by an insatiable hunger for humanoid flesh.

## Devourers of Flesh

Like maggots or carrion beetles, ghouls thrive in places rank with decay and death. A ghoul haunts a place where it can gorge on dead flesh and decomposing organs. When it can't feed on the dead, it pursues living creatures and attempts to make corpses of them. Though they gain no nourishment from the corpses they devour, ghouls are driven by an unending hunger that compels them to consume. A ghoul's undead flesh never rots, and this monster can persist in a crypt or tomb for untold ages without feeding.

## Abyssal Origins

Ghouls trace their origins to the Abyss. Doresain, the first of their kind, was an elf worshiper of Orcus. Turning against his own people, he feasted on humanoid flesh to honor the Demon Prince of Undeath. As a reward for his service, Orcus transformed Doresain into the first ghoul. Doresain served Orcus faithfully in the Abyss, creating ghouls from the demon lord's other servants until an incursion by Yeenoghu, the demonic Gnoll Lord, robbed Doresain of his abyssal domain. When Orcus would not intervene on his behalf, Doresain turned to the elf gods for salvation, and they took pity on him and helped him escape certain destruction. Since then, elves have been immune to the ghouls' paralytic touch.

## Ghasts

Orcus sometimes infuses a ghoul with a stronger dose of abyssal energy, making a ghast. Whereas ghouls are little more than savage beasts, a ghast is cunning and can inspire a pack of ghouls to follow its commands.

```statblock
name: Ghul
image: token/ghoul.webp
source: Monsterhandbuch 2014
size: Mittelgroß
type: Untoter
alignment: chaotisch böse
ac: !!int "12"
hp: !!int "22"
hit_dice: "5d8"
modifier: !!int "2"
stats:
  - !!int "13"
  - !!int "15"
  - !!int "10"
  - !!int "7"
  - !!int "10"
  - !!int "6"
spee": "9 Meter"
damage_immunities: "Gift"
condition_immunities: "Bezaubert, Erschöpft, Vergiftet"
senses: "Dunkelsicht 18 Meter, passive Wahrnehmung 10"
languages: "Gemeinsprache"
cr: "1"
actions:
  - name: Biss
    desc: "Nahkampfwaffenangriff: +2 auf Treffer, Reichweite 1,5 m, eine Kreatur. Treffer: 9 (`2W6+2`) Stichschaden."
  - name: Klauen
    desc: "Nahkampfwaffenangriff: +4 auf Treffer, Reichweite 1,5 m, ein Ziel. Treffer: 7 (`2W4+2`) Hiebschaden. Falls das Ziel eine Kreatur ist, aber kein Elf oder Untoter, muss es einen Konstitutions-Rettungswurf (SG 10) bestehen, um nicht eine Minute lang gelähmt zu werden. Das Ziel kann den Rettungswurf am Ende jedes seiner Züge wiederholen und den Effekt bei einem Erfolg beenden."
```
^statblock

## Environment

underdark, swamp, urban