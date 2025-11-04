---
cssclasses:
  - json5e-monster
prefer-view:
  - edit-source read
status:
tags:
  - Monster/Größe/Riesig
  - Habitat/Planar/Untere Ebenen
  - Quelle/5e/Monster_Manual
  - Monster/Typ/Unhold/Dämon
aliases:
  - Balor
link:
type:
  - creature
Typ: Unhold
---
# Balor
*Source: SRD / Basic Rules*  

```statblock
name: Balor
size: Riesig
source: SRD / Basic Rules
type: Dämon
subtype: ""
alignment: Chaotisch Böse
ac: 19
hp: 262
hit_dice: 21d12 + 126
speed: 40 Meter, Fliegen 80 Meter
stats: [26, 15, 22, 20, 16, 22]
saves:
  - STR: +14
  - KON: +12
  - WEI: +9
  - CHA: +12
skillsaves: []
damage_vulnerabilities: ""
damage_resistances: "Kälte; Blitz; Hieb‑, Stich‑ und Wuchtschaden von nichtmagischen Angriffen"
damage_immunities: "Feuer, Gift"
condition_immunities: "Vergiftet"
senses: "Wahrer Blick 120 Meter, passive Wahrnehmung 13"
languages: "Abyssisch, telepathisch 120 Meter"
cr: 19
bestiary: true
traits:
  - name: Death Throes.
    desc: "Wenn der Balor stirbt, explodiert er. Jede Kreatur im Umkreis von 30 ft. muss einen Geschicklichkeits‑Rettungswurf (SG 20) machen. Bei einem Fehlversuch erleidet sie 70 (20d6) Feuerschaden, bei Erfolg die Hälfte. Die Explosion entzündet brennbare Objekte, die nicht getragen werden, und zerstört die Waffen des Balors."
  - name: Fire Aura.
    desc: "Zu Beginn jedes Zuges des Balors erleidet jede Kreatur innerhalb von 5 ft. 10 (3d6) Feuerschaden. Flammenempfindliche Gegenstände in der Aura entzünden sich. Ein Wesen, das den Balor berührt oder ihn im Nahkampf angreift, erleidet ebenfalls 10 (3d6) Feuerschaden."
  - name: Magic Resistance.
    desc: "Der Balor hat Vorteil bei Rettungswürfen gegen Zauber und andere magische Effekte."
  - name: Magic Weapons.
    desc: "Die Waffenangriffe des Balors gelten als magisch."
actions:
  - name: Multiattack.
    desc: "Der Balor führt zwei Angriffe aus: einen mit seinem Langschwert und einen mit seiner Peitsche."
  - name: Longsword.
    desc: "_Nahkampfangriff_: +14 zum Treffen, Reichweite 10 ft., ein Ziel. _Treffer_: 21 (3d8 + 8) Hiebschaden plus 13 (3d8) Blitzschaden. Bei einem kritischen Treffer werden die Schadenswürfel dreimal statt zweimal geworfen."
    attack_bonus: 14
    damage_dice: 3d8
    damage_bonus: 8
  - name: Whip.
    desc: "_Nahkampfangriff_: +14 zum Treffen, Reichweite 30 ft., ein Ziel. _Treffer_: 15 (2d6 + 8) Hiebschaden plus 10 (3d6) Feuerschaden. Das Ziel muss einen Stärke‑Rettungswurf (SG 20) bestehen, sonst wird es bis zu 25 ft. zum Balor gezogen."
    attack_bonus: 14
    damage_dice: 2d6
    damage_bonus: 8
  - name: Teleport.
    desc: "Der Balor teleportiert sich magisch zusammen mit seiner Ausrüstung bis zu 120 ft. zu einem unbesetzten Ort, den er sehen kann."
```