```statblock
statblock: true
name: Iarno "Glasstaff" Albreck
image: [[Iarno Glasstaff Albrek.webp]]
source: Phandelver & Below
size: Mittelgroß
type: Humanoid
alignment: Rechtschaffen böse
ac: 12
hp: 22
hit_dice: 5d8
speed: 9 Meter.
stats: [9, 14, 11, 17, 12, 11]
saves:
  - Intelligenz: 5
  - Weisheit: 3
skillsaves:
  - Arkane Kunde: 5
  - Geschichte: 5
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Wahrnehmung 11
languages: Drakonisch, Elfisch, Gemeinsprache, Zwergisch 
cr: 1
bestiary: true
traits:
  - name: Besondere Ausrüstung
    desc: "Glasstaff schwingt einen Stab der Verteidigung. Mit dem Stab in der Hand kann er eine Aktion verwenden, um den Zauber [[Magierrüstung.md|Magierrüstung]] zu wirken, und seine Reaktion nutzen, um den Zauber [[Schild.md|Schild]] zu wirken."
actions:
  - name: Mehrfachangriff
    desc: "Glasstab führt zwei Angriffe mit „Schockierender Stoß“ aus."
  - name: Schockierender Stoß
    desc: "Nahkampf- oder Fernkampf-Zauberangriff: +5 auf Treffer, Reichweite 1,5m. oder 36m., ein Ziel. Treffer: 6 (`1W6 + 3`) Blitzschaden."
    attack_bonus: 6
    damage_dice: 1d6
    damage_bonus: 3
spells:
  - "Glasstab wirkt einen der folgenden Zauber, die keine materiellen Komponenten benötigen und Intelligenz als Zauberfähigkeit verwenden (Zauberrettungswurf SG 13):"
  - Nach Belieben: [[light.md|Licht]], [[Magierhand.md|Magierhand]]
  - Je 1/Tag: [[Person-bezaubern|Person bezaubern]], [[Person-festhalten.md|Person festhalten]], [[Magisches Geschoss]]
bonus_actions:
  - name: Teleportieren (2/Tag)
    desc: "Glasstab teleportiert sich zusammen mit der Ausrüstung, die er trägt, auf magische Weise bis zu 9 Meter weit in einen unbesetzten Raum, den er sehen kann."
```