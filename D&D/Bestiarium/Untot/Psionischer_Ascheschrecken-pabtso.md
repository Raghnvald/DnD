---
prefer-view: edit-source read
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Psionischer Ascheschrecken
Typ: Untoter
Größe: Mittelgroß
HG: 7
Habitat:
  - /
image: token/psionic-ashenwight-pabtso.webp
status: WIP
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/7
  - Monster/Typ/Untote
  - Quelle/5e/pabtso
aliases:
  - Psionischer Ascheschrecken
  - Psionic Ashenwight
linter-yaml-title-alias: Psionischer Ascheschrecken
---
# Psionischer Ascheschrecken
*Quelle: Die Tiefen von Phandelver: Der zersplitterte Obelisk S. 204*  

Wenn ein Ascheschrecken in der Nähe einer Kristallader entsteht, die mit aberranter Energie erfüllt ist, oder wenn ein Ascheschrecken sich länger in einem Bereich voller finsterer Magie aufhält, kann er psionische Fähigkeiten entwickeln. Ein psionischer Ascheschrecken ist deutlich intelligenter als andere Ascheschrecken. Allerdings ist das daraus entstehende Bewusstsein neu und hat keinerlei Verbindung zum Bewusstsein, das der Ascheschrecken hatte, als er noch am Leben war.

Manche psionische Ascheschrecken widmen ihr Dasein der Rekonstruktion ihres früheren Lebens, andere streben danach, anderen Ascheschrecken zu dieser neuen psionischen Kraft zu verhelfen.

## Ascheschrecken

Wenn ein von Grausamkeit und Wut erfüllter Humanoide in einem Bereich stirbt, der vom Fernen Reich korrumpiert ist, ersteht die Kreatur manchmal als Ascheschrecken wieder auf. Die Haut dieser schrecklichen Untoten ist ausgetrocknet und in ihren Augen leuchtet oft eine außerweltliche Macht.

```statblock
name: Psionischer Ascheschrecken
image: token/psionic-ashenwight-pabtso.webp
source: PaBTSO
size: Mittelgroß
type: Untoter
alignment: normalerweise  Neutral
ac: 16
ac_class: natürliche Rüstung
hp: 78
hit_dice: 12d8 + 24
modifier: 1
stats:
  - 19
  - 13
  - 15
  - 17
  - 14
  - 6
speed: 7,5 m
saves:
  - Str: 7
  - Kon: 5
  - Int: 6
  - Wei: 5
damage_resistances: Gift, Nekrotisch, Psychisch
condition_immunities: Bewusstlos, Bezaubert, Erschöpft, Gelähmt, Verängstigt, Vergiftet
senses: passive Wahrnehmung 12
languages: Versteht alle zu Lebzeiten bekannten Sprachen, aber kann nicht sprechen, Telepathie auf 36 m
cr: 7
actions:
  - name: Mehrfachangriff
    desc: Der Ascheschrecken führt zwei Nekrotischer-Splitter-Angriffe aus. Er setzt auch seine Psionische Krone ein, falls sie verfügbar ist.
  - name: Nekrotischer Splitter
    desc: "*Melee  or Ranged Weapon Attack:* +7 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 9 (2d8) necrotic damage. If the target is a creature, it has disadvantage on the next attack roll it makes before the end of its next turn."
  - name: Psionische Krone (Aufladung 5-6)
    desc: The ashenwight wreathes the head of a creature it can see within 60 feet of itself with a crown of jagged, spectral crystals. The target must succeed on a DC 14 Wisdom saving throw or have the <STATBLOCK-MARKDOWN-LINK>/3-Mechanics/CLI/conditions.md#Charmed|charmed<STATBLOCK-MARKDOWN-LINK> condition for 1 minute. While <STATBLOCK-MARKDOWN-LINK>/3-Mechanics/CLI/conditions.md#Charmed|charmed<STATBLOCK-MARKDOWN-LINK> in this way, the target's thoughts are sluggish; it can't take reactions, its speed is halved, and it takes 9 (2d8) psychic damage at the start of each of its turns. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
  - name: Zauberwirken (Psionik)
    desc: |-
      The ashenwight casts one of the following spells, requiring no spellcasting components and using Intelligence as the spellcasting ability (spell save DC 14):

      **At will:** <STATBLOCK-MARKDOWN-LINK>/3-Mechanics/CLI/spells/mage-hand-xphb.md|mage hand<STATBLOCK-MARKDOWN-LINK> (the hand is invisible)

      **1/day:** <STATBLOCK-MARKDOWN-LINK>/3-Mechanics/CLI/spells/calm-emotions-xphb.md|calm emotions<STATBLOCK-MARKDOWN-LINK>
```
^statblock