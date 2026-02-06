---
prefer-view: edit-source read
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Strahd von Zarovich
Kategorie: Untoter (Gestaltwandler)
Größe: Mittelgroß
HG: 15
Habitat:
  - Stadt
image:
status: completed
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/15
  - Monster/Typ/Untote/shapechanger
  - Quelle/5e/cos
aliases:
  - Strahd von Zarovich
linter-yaml-title-alias: Strahd von Zarovich
---
# Strahd von Zarovich
*Quellen: Fluch des Strahd S. 240*  

Mit seinem scharfen Geist und düsteren Herzen ist Strahd von Zarowitsch ein äußerst schwieriger Gegner. Mit und Leben über alle Maßen sind an ihn verlorengegangen. Lies Kapitel 1 „In die Nebel", noch einmal, um seine Persönlichkeit und Ziele zu verstehen.

$\quad$ Obwohl man Strahd fast überall in seiner Domäne begegnen kann, treffen die Abenteurer dem Vampir immer an den von den Tarokka-Karten geweissagten Orten (siehe Kapitel 1), solange er nicht in sein Grabmal in den Katakomben von Burg Ravenloft gezwungen wurde.

## Strahds Taktiken
Weil sich das ganze Abenteuer um Strahd dreht, solltest du ihn auf clevere Weise spielen und alles dafür tun, ihn für die Spielercharaktere zu einem furchteinflößenden und listigen Gegner zu machen.

$\quad$ Wenn du eine Begegnung mit Strahd leitest, behalte die folgenden Tatsachen im Hinterkopf:

- Strahd greift im vorteilhaftesten Moment an und aus der vorteilhaftesten Position.
- Strahd weiß, wenn er sich übernommen hat. Wenn er beginnt, mehr Schaden zu erleiden, als er regenerieren kann, bewegt er sich aus der Reichweite von Nahkämpfern und Zauberwirkern heraus oder fliegt davon (und benutzt dabei herbeigerufene Wölfe oder Schwärme von Fledermäusen oder Ratten, um seinen Rückzug zu decken).
- Strahd beobachtet die Charaktere um herauszufinden, wer von ihnen am leichtesten beeinflusst werden kann und versucht dann, Charaktere mit niedrigen Weisheitswerten zu bezaubern und sie als Hörige zu benutzen. Zumindest kann er einem bezauberten Charakter befehlen, ihn gegen andere Mitglieder der Abenteurergruppe zu beschützen.

## Die Schergen des Vampirs
Wann immer Strahd an einen Ort außer seinem Grabmal oder dem beim Kartenlesen angegebenen Ort erscheint, würfle mit einem `W20` und schlage in der Tabelle Strahds Schergen nach, um festzustellen, ob und welche Kreaturen ihn begleiten.

## Strahds Diener

`dice: [](Strahd-von-Zarowitsch-cos.md#^Strahds-Schergen)`

| W20   | Kreaturen                                                            |
| ----- | -------------------------------------------------------------------- |
| 1-3   | `dice: 1d4 + 2` [Schreckenswölfe](Schreckenswolf-mm.md)                 |
| 4-6   | `dice: 1d6 + 3` [Ghule](Ghul-old.md)                                     |
| 7-9   | `dice: 1d4 + 2` [Strahdzombies](Strahdzombie.md)                     |
| 10-12 | `dice: 2d4` [Schwärme von Fledermäusen](Schwarm%20von%20Fledermäusen.md) |
| 13-15 | `dice: 1d4 + 1` [Vampirbrut](D&D/05%20-%20Wikipedia/Bestiarium/U-V/Vampirbrut.md)                          |
| 16-18 | `dice: 3d6` [Wölfe](D&D/05%20-%20Wikipedia/Bestiarium/W-X/Wolf.md)                                         |
| 19-20 | keine                                                                | 
^Strahds-Schergen

$\quad$ Wenn die Charaktere sich in einer Wohnstatt befinden, brechen Strahds Kreaturen durch Türen und Fenster, kriechen aus der Erde hervor oder gleiten den Kamin herunter um die Charaktere zu erreichen. Die Vampirbrut (alles, was von einer von Strahds vor langer Zeit besiegten Abenteuergruppe übrig ist) kann den Aufenthaltsort der Charaktere nicht betreten, solange sie nicht hereingebeten wird.

## Herz des Kummers

Strahd kann es sich leisten, forsch bei seinen Taktiken zu sein, denn er besitzt zusätzlichen Schutz in der Form eines riesigen Kristallherzens, das in der Burg Ravenloft verborgen liegt.

$\quad$ Jeder Schaden, den Strahd erleidet, wird auf das Herz des Kummers übertragen (siehe [[04. Kapitel - Burg Ravenloft#K20 Herz des Leidens|Kapitel 4, Bereich K20]]). Wenn das Herz Schaden absorbiert, der seine Trefferpunkte auf 0 reduziert, wird es zerstört und Strahd erleidet etwaigen übrigen Schaden. Das Herz des Kummers hat 50 Trefferpunkte und wird bis zu dieser Zahl an Trefferpunkten zu jedem Morgengrauen wiederhergestellt, vorausgesetzt, dass ihm mindestens 1 Trefferpunkt verbleibt. Strahd kann seine Verbindung mit dem Herz des Kummers als eine Bonusaktion während seines Zuges unterbrechen, so dass es nicht länger den Strahd zugefügten Schaden absorbiert. Strahd kann seine Verbindung mit dem Herz des Kummers als eine Bonusaktion während seines Zuges wiederherstellen, aber nur, während er sich in der Burg Ravenloft befindet.

$\quad$ Der Effekt des Schutzes, den das Herz des Kummers bietet, kann erschreckend zu beobachten sein, da Strahd zugefügter Schaden schnell wiederhergestellt wird. Zum Beispiel könnte  ein kritischer Treffer Strahds Kiefer ausrenken, aber nur für einen Moment: dann renkt sich der Kiefer des Vampirs schnell wieder ein.

$\quad$ Die Fähigkeit des Herzens des Kummers, Schaden zu absorbieren, wird unterdrückt, wenn es oder Strahd sich vollständig in einem _[[Antimagisches-Feld|Antimagischen Feld]]_ befindet.

```statblock
"name": "Strahd von Zarovich (CoS)"
"size": "Medium"
"type": "undead"
"subtype": "shapechanger"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "144"
"hit_dice": "17d8 + 68"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "18"
  - !!int "18"
  - !!int "20"
  - !!int "15"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "9"
  - "wisdom": !!int "7"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+15"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+12"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+10"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+14"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 22"
"languages": "Abyssal, Common, Draconic, Elvish, Giant, Infernal"
"cr": "15"
"traits":
  - "desc": "Strahd is a 9th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 18, +10 to hit with spell attacks). He has the following wizard\
      \ spells prepared:\n\n**Cantrips (at will):** [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md),\
      \ [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation-xphb.md), [ray\
      \ of frost](/3-Mechanics/CLI/spells/ray-of-frost-xphb.md)\n\n**1st level (4\
      \ slots):** [comprehend languages](/3-Mechanics/CLI/spells/comprehend-languages-xphb.md),\
      \ [fog cloud](/3-Mechanics/CLI/spells/fog-cloud-xphb.md), [sleep](/3-Mechanics/CLI/spells/sleep-xphb.md)\n\
      \n**2nd level (3 slots):** [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
      \ [gust of wind](/3-Mechanics/CLI/spells/gust-of-wind-xphb.md), [mirror image](/3-Mechanics/CLI/spells/mirror-image-xphb.md)\n\
      \n**3rd level (3 slots):** [animate dead](/3-Mechanics/CLI/spells/animate-dead-xphb.md),\
      \ [fireball](/3-Mechanics/CLI/spells/fireball-xphb.md), [nondetection](/3-Mechanics/CLI/spells/nondetection-xphb.md)\n\
      \n**4th level (3 slots):** [blight](/3-Mechanics/CLI/spells/blight-xphb.md),\
      \ [greater invisibility](/3-Mechanics/CLI/spells/greater-invisibility-xphb.md),\
      \ [polymorph](/3-Mechanics/CLI/spells/polymorph-xphb.md)\n\n**5th level (1 slots):**\
      \ [animate objects](/3-Mechanics/CLI/spells/animate-objects-xphb.md), [scrying](/3-Mechanics/CLI/spells/scrying-xphb.md)"
    "name": "Spellcasting"
  - "desc": "If Strahd isn't in running water or sunlight, he can use his action to\
      \ polymorph into a Tiny bat, a Medium wolf, or a Medium cloud of mist, or back\
      \ into his true form.\n\nWhile in bat or wolf form, Strahd can't speak. In bat\
      \ form, his walking speed is 5 feet, and he has a flying speed of 30 feet. In\
      \ wolf form, his walking speed is 40 feet. His statistics, other than his size\
      \ and speed, are unchanged. Anything he is wearing transforms with him, but\
      \ nothing he is carrying does. He reverts to his true form if he dies.\n\nWhile\
      \ in mist form, Strahd can't take any actions, speak, or manipulate objects.\
      \ He is weightless, has a flying speed of 20 feet, can hover, and can enter\
      \ a hostile creature's space and stop there. In addition, if air can pass through\
      \ a space, the mist can do so without squeezing, and he can't pass through water.\
      \ He has advantage on Strength, Dexterity, and Constitution saving throws, and\
      \ he is immune to all nonmagical damage, except the damage he takes from sunlight."
    "name": "Shapechanger"
  - "desc": "If Strahd fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "When Strahd drops to 0 hit points outside his coffin, he transforms into\
      \ a cloud of mist (as in the Shapechanger trait) instead of falling [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious),\
      \ provided that he isn't in running water or sunlight. If he can't transform,\
      \ he is destroyed.\n\nWhile he has 0 hit points in mist form, he can't revert\
      \ to his vampire form, and he must reach his coffin within 2 hours or be destroyed.\
      \ Once in his coffin, he reverts to his vampire form. He is then [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed)\
      \ until he regains at least 1 hit point. After 1 hour in his coffin with 0 hit\
      \ points, he regains 1 hit point."
    "name": "Misty Escape"
  - "desc": "Strahd regains 20 hit points at the start of his turn if he has at least\
      \ 1 hit point and isn't in running water or sunlight. If he takes radiant damage\
      \ or damage from holy water, this trait doesn't function at the start of his\
      \ next turn."
    "name": "Regeneration"
  - "desc": "Strahd can climb difficult surfaces, including upside down on ceilings,\
      \ without having to make an ability check."
    "name": "Spider Climb"
  - "desc": "Strahd has the following flaws:\n\n- **Forbiddance.** He can't enter\
      \ a residence without an invitation from one of the occupants.  \n- **Harmed\
      \ by Running Water.** He takes 20 acid damage if he ends his turn in running\
      \ water.  \n- **Stake to the Heart.** If a piercing weapon made of wood is driven\
      \ into his heart while he is [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ in his coffin, he is [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed)\
      \ until the stake is removed.  \n- **Sunlight Hypersensitivity.** While in sunlight,\
      \ Strahd takes 20 radiant damage at the start of his turn, and he has disadvantage\
      \ on attack rolls and ability checks  "
    "name": "Vampire Weaknesses"
"actions":
  - "desc": "Strahd makes two attacks, only one of which can be a bite attack."
    "name": "Multiattack (Vampire Form Only)"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 8 (1d8\
      \ + 4) slashing damage, plus 14 (4d6) necrotic damage. If the target is a creature,\
      \ Strahd can grapple it (escape DC 18) instead of dealing the slashing damage."
    "name": "Unarmed Strike (Vampire or Wolf Form Only)"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one willing creature,\
      \ or a creature that is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ by Strahd, [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated),\
      \ or [restrained](/3-Mechanics/CLI/conditions.md#Restrained). *Hit:* 7 (1d6\
      \ + 4) piercing damage plus 10 (3d6) necrotic damage. The target's hit point\
      \ maximum is reduced by an amount equal to the necrotic damage taken, and Strahd\
      \ regains hit points equal to that amount. The reduction lasts until the target\
      \ finishes a long rest. The target dies if its hit point maximum is reduced\
      \ to 0. A humanoid slain in this way and then buried in the ground rises the\
      \ following night as a [vampire spawn](/3-Mechanics/CLI/bestiary/undead/vampire-spawn-xmm.md)\
      \ under Strahd's control."
    "name": "Bite"
  - "desc": "Strahd targets one humanoid he can see within 30 feet of him. If the\
      \ target can see Strahd, the target must succeed on a DC 17 Wisdom saving throw\
      \ against this magic or be [charmed](/3-Mechanics/CLI/conditions.md#Charmed).\
      \ The [charmed](/3-Mechanics/CLI/conditions.md#Charmed) target regards Strahd\
      \ as a trusted friend to be heeded and protected. The target isn't under Strahd's\
      \ control, but it takes Strahd's requests and actions in the most favorable\
      \ way and lets Strahd bite it.\n\nEach time Strahd or his companions do anything\
      \ harmful to the target, it can repeat the saving throw, ending the effect on\
      \ itself on a success. Otherwise, the effect lasts 24 hours or until Strahd\
      \ is destroyed, is on a different plane of existence than the target, or takes\
      \ a bonus action to end the effect."
    "name": "Charm"
  - "desc": "Strahd magically calls 2d4 [swarms of bats](/3-Mechanics/CLI/bestiary/beast/swarm-of-bats-xmm.md)\
      \ or [swarms of rats](/3-Mechanics/CLI/bestiary/beast/swarm-of-rats-xmm.md),\
      \ provided that the sun isn't up. While outdoors, Strahd can call 3d6 [wolves](/3-Mechanics/CLI/bestiary/beast/wolf-xmm.md)\
      \ instead. The called creatures arrive in 1d4 rounds, acting as allies of Strahd\
      \ and obeying his spoken commands. The beasts remain for 1 hour, until Strahd\
      \ dies, or until he dismisses them as a bonus action."
    "name": "Children of the Night (1/Day)"
"lair_actions":
  - "desc": "While Strahd is in Castle Ravenloft, he can take lair actions as long\
      \ as he isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated).\n\
      \nOn initiative count 20 (losing initiative ties), Strahd can take one of the\
      \ following lair action options, or forgo using any of them in that round:\n\
      \n- Until initiative count 20 of the next round, Strahd can pass through solid\
      \ walls, doors, ceilings, and floors as if they weren't there.  \n- Strahd targets\
      \ any number of doors and windows that he can see, causing each one to either\
      \ open or close as he wishes. Closed doors can be magically locked (needing\
      \ a successful DC 20 Strength check to force open) until Strahd chooses to end\
      \ the effect, or until Strahd uses this lair action again.  \n- Strahd summons\
      \ the angry spirit of one who has died in the castle. The apparition appears\
      \ next to a hostile creature that Strahd can see, makes an attack against that\
      \ creature, and then disappears. The apparition has the statistics of a [specter](/3-Mechanics/CLI/bestiary/undead/specter-xmm.md).\
      \  \n- Strahd targets one Medium or smaller creature that casts a shadow. The\
      \ target's shadow must be visible to Strahd and within 30 feet of him. If the\
      \ target fails a DC 17 Charisma saving throw, its shadow detaches from it and\
      \ becomes a [shadow](/3-Mechanics/CLI/bestiary/undead/shadow-xmm.md) that obeys\
      \ Strahd's commands, acting on initiative count 20. A [greater restoration](/3-Mechanics/CLI/spells/greater-restoration-xphb.md)\
      \ spell or a [remove curse](/3-Mechanics/CLI/spells/remove-curse-xphb.md) spell\
      \ cast on the target restores its natural shadow, but only if its undead shadow\
      \ has been destroyed.  "
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Strahd can expend a use to take one of the following actions. Strahd regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Strahd moves up to his speed without provoking opportunity attacks."
    "name": "Move"
  - "desc": "Strahd makes one unarmed strike."
    "name": "Unarmed Strike"
  - "desc": "Strahd makes one bite attack."
    "name": "Bite (Costs 2 Actions)"
"source":
  - "CoS"
"image": "/3-Mechanics/CLI/bestiary/npc/token/strahd-von-zarovich-cos.webp"
```
^statblock

---

```statblock
statblock: true
name: Strahd von Zarowitsch
image: [[count_strahd_von_zarovich_token.webp]]
source: Fluch des Strahd
size: Mittelgroß
type: Untoter
subtype: Gestaltwandler
alignment: rechtschaffen böse
ac: 16
hp: 144
hit_dice: 17d8 + 68
speed: 9 Meter.
stats: [18, 18, 18, 20, 15, 18]
saves:
  - STR: +0
  - GES: +9
  - KON: +0
  - INT: +0
  - WEI: +7
  - CHA: +9
skillsaves:
  - Arkane Kunde: +15
  - Heimlichkeit: +14
  - Religion: +10
  - Wahrnehmung: +12
damage_vulnerabilities: ""
damage_resistances: "Nekrotisch, Hieb-, Stich- und Wuchtschaden von nicht-magischen Angriffen"
damage_immunities: ""
condition_immunities: "Bezaubert, blind, erschöpft, gelähmt, liegend, taub, verängstigt, versteinert"
senses: Dunkelsicht 36 Meter, passive Wahrnehmung 22
languages: Abyssisch, Drakonisch, Elfisch, Gemeinsprache, Infernalisch, Riesisch
cr: 15
bestiary: true
traits:
  - name: Gestaltwandler
    desc: "Wenn Strahd sich nicht in fließendem Wasser oder im Sonnenlicht befindet, kann er sich als Aktion in eine winzige Fledermaus, einen mittelgroßen Wolf oder eine mittelgroße Nebelwolke verwandeln oder seine wahre Gestalt annehmen. <br> In Fledermaus- oder Wolfsgestalt kann Strahd nicht sprechen. Als Fledermaus beträgt seine Bewegungsrate 1,5m und er hat eine Flug-Bewegungsrate von 9m. In Wolfsgestalt hat er eine Bewegungsrate von 12m. Seine Spielwerte, abgesehen von seiner Größe und Bewegungsrate, bleiben unverändert. Alles, was er am Körper trägt, verwandelt sich mit, doch nichts, was er in der Hand hält. Wenn er stirbt, nimmt er seine wahre Gestalt an. <br> Solange Strahd eine Nebelgestalt hat, kann er keine Aktionen ausführen, nicht sprechen und keine Gegenstände beeinflussen. Er ist gewichtslos, hat eine Flug-Bewegungsrate von 6m, kann schweben und den Bereich einer feindlichen Kreatur betreten und dort anhalten. Wenn außerdem Luft durch einen Bereich dringen kann, kann der Nebel dies auch, ohne sich quetschen zu müssen. Er kann kein Wasser durchringen. Er hat einen Vorteil bei Rettungswürfen auf Stärke, Geschicklichkeit und Konstitution und ist immun gegen jeden nicht-magischen Schaden, abgesehen von Sonnenlichtschaden."
    attack_bonus: 0
  - name: Legendäre Resistenz (3/Tag)
    desc: Wenn Strahd einen Rettungswurf nicht schafft, kann er sich stattdessen entscheiden, ihn zu schaffen.
    attack_bonus: 0
  - name: Nebliges Entkommen
    desc: Wenn er außerhalb seines Sargs auf 0 Trefferpunkte fällt, verwandelt sich Strahd in eine Nebelwolke (wie beim Merkmal Gestaltwandler) anstatt das Bewusstsein zu verlieren, vorausgesetzt, er ist weder im Sonnenlicht noch in fließendem Wasser. Wenn er sich nicht verwandeln kann, wird er zerstört. <br> Solange er in Nebelgestalt 0 TP besitzt, kann er nicht seine Vampirgestalt annehmen, und er muss seinen Sarg innerhalb von 2 Stunden erreichen, sonst wird er zerstört. Sobald er seine Ruhestätte erreicht hat, nimmt er wieder seine Vampirgestalt an. Er ist dann gelähmt, bis er mindestens 1 Trefferpunkt zurückerhält. Nachdem er 1 Stunde mit 0 Trefferpunkten in seiner Ruhestätte verbracht hat, erhält er 1 TP zurück.
    attack_bonus: 0
  - name: Regeneration
    desc: Strahd erhält zu Beginn seines Zuges 20 TP zurück, wenn er mindestens 1 Trefferpunkt besitzt und sich nicht im Sonnenlicht oder in fließendem Wasser befindet. Wenn er gleißenden Schaden oder Schaden durch Weihwasser erleidet, funktioniert dieses Merkmal zu Beginn des nächsten Zugs des Vampirs nicht.
    attack_bonus: 0
  - name: Spinnenklettern
    desc: Strahd kann an schwierigen Oberflächen klettern, auch kopfüber an der Decke, ohne Attributswürfe ablegen zu müssen.
    attack_bonus: 0
  - name: Vampirschwächen
    desc: "Der Vampir hat die folgenden Nachteile: <br> _Verbot._ Er kann keinen Wohnsitz betreten, ohne eine Einladung von einem der Bewohner erhalten zu haben. <br> _Verletzt durch fließendes Wasser._ Der vampir erleidet 20 Säureschaden, wenn er seinen Zug in fließendem Wasser beendet. <br> _Pflock ins Herz._ Wenn eine Stichwaffe aus Holz ins Herz des Vampirs getrieben wird, solange der Vampir sich in seinem Sarg befindet und kampfunfähig ist, wird er gelähmt, bis der Pflock entfernt wird. <br> _Hyperempfindlich gegenüber Sonnenlicht._ Der vampir erleidet 20 Punkte gleißenden Schaden, wenn er seinen Zug im Sonnenlicht beginnt. Solange er sich im Sonnenlicht befindet, erleidet er einen Nachteil auf Angriffswürfe und Attributswürfe."
    attack_bonus: 0
spells:
  - "Strahd ist ein Zauberwirker der 9. Stufe (Attribut Intelligenz, Zauberrettungswurf-SG 18, +10 zum Treffen mit Zauberangriffen). Strahd hat die folgenden Magierzaubersprüche vorbereitet:"
  - Zaubertricks (beliebig oft): [Kältestrahl](Kältestrahl.md), [Magierhand](Magierhand.md), [Taschenspielerei](Taschenspielerei.md)
  - Zaubergrad 1 (4 Plätze): [Nebelwolke](Nebelwolke.md), [Schlaf](Schlaf.md), [Sprachen verstehen](Sprachen-verstehen.md)
  - Zaubergrad 2 (3 Plätze): [Gedanken wahrnehmen](Gedanken-wahrnehmen.md), [Spiegelbilder](Spiegelbilder.md), [Windstoß](Windstoß.md)
  - Zaubergrad 3 (3 Plätze): [Feuerball](Feuerball.md), [Tote beleben](Tote-beleben.md), [Unauffindbarkeit](Unauffindbarkeit.md)
  - Zaubergrad 4 (3 Plätze): [Dürre](Dürre.md), [Mächtige Unsichtbarkeit](Mächtige-Unsichtbarkeit.md), [Verwandlung](Verwandlung.md)
  - Zaubergrad 5 (1 Platz): [Ausspähung](Ausspähung.md), [Gegenstände beleben](Gegenstände-beleben.md)
actions:
  - name: Mehrfachangriff (nur Vampirgestalt)
    desc: "Strahd führt zwei Angriffe aus, von denen nur eine ein Biss-Angriff sein kann."
  - name: Waffenloser Angriff (nur Vampir- und Wolfsgestalt)
    desc: "_Nahkampf-Waffenangriff_: +9 auf Treffer, Reichweite 1,5m, ein Ziel. _Treffer_: 8 (`1W8 + 4`) Hiebschaden plus 14 nekrotischer Schaden. Wenn das Ziel eine Kreatur ist, kann Strahd sie packen (SG 18 zum Entkommen), anstatt den Hiebschaden zu verursachen."
    attack_bonus: 9
    damage_dice: 1d8
    damage_bonus: 4
  - name: Biss
    desc: "_Nahkampf-Waffenangriff_: +9 zum Treffen, 1,5m, eine bereitwillige Kreatur oder eine Kreatur, die Strahd gepackt hat, die kampfunfähig oder festgesetzt ist. _Treffer_: 7 (`1W6` + 4) Stichschaden plus 10 (`3W6`) nekrotischer Schaden. Die maximalen Trefferpunkte des Ziels werden um den nekrotischen Schaden verringert und  der Vampir erhält die gleiche Menge an Trefferpunkten zurück. Diese Verringerung hält an, bis das Ziel eine lange Rast abschließt. Das Ziel stirb, wenn dieser Effekt es auf 0 maximale Trefferpunkte reduziert. Ein Humanoider, der auf diese Weise getötet wirdund dann in der Erde begraben wird, erhebt sich in der folgenden Nacht als Vampirbrut unter Strahds Kontrolle."
    attack_bonus: 7
    damage_dice: 1d6
    damage_bonus: 4
  - name: Bezaubern
    desc: "Strahd wählt einen Humanoiden innerhalb von 9m um sich aus, den er sehen kann. Wenn das Ziel Strahd sehen kann, muss es gegen diese Magie einen Weisheits-Rettungswurf gegen SG 17 ablegen, um nicht bezaubert zu werden. Das bezauberte Ziel betrachtet Strahd als Freund, dem es vertraut, auf den es hören sollte und der beschützt werden muss. Auch wenn das Ziel nicht unter Strahds Kontrolle steht, deutet es die Forderungen und Taten Strahds so wohlwollend wie es kann und lässt sich von Strahd beißen. <br> Immer wenn Strahd oder die Gefährten des Vampirs etwas tun, das dem Ziel schadet, kann es den Rettungswurf wuederholen und den Effekt auf sich selbst bei einem Erfolg beenden. Ansonsten hält der Effekt für 24 Stunden an, bis Strahd zerstört wird, sich auf einer anderen Existentebene als das Ziel befindet, oder eine Bonusaktion nutzt, um den Effekt zu beenden"
  - name: Kinder der Nacht (1/Tag)
    desc: "Der Vampir ruft auf magische Weise `2W4` [Schwärme von Fledermäusen](Schwarm-von-Fledermäusen.md) oder [Schwärme von Ratten](Schwarm-von-Ratten.md), vorausgesetzt die Sonne steht nicht am Himmel. Solange sich Strahd im Freien befindet, kann er stattdessen `3W6` [Wölfe](Wolf.md) rufen. Die gerufenen Kreaturen treffen innerhalb von `1W4` Runden ein, dienen als Verbündete Strahds und gehorchen seinen gesprochenen Befehlen. Die Tiere bleiben für 1 Stunde, bis Strahd stirbt oder bis er sie als seine Bonusaktion entlässt."
legendary_description: Strahd kann 3 legendäre Aktionen durchführen und aus den untenstehenden Optionen auswählen. Er kann nur eine legendäre Aktionsoption auf einmal verwenden, und nur am Ende eines Zuges einer anderen Kreatur. Strahd erhält verbrauchte legendäre Aktionen zu Beginn seines Zuges zurück.
legendary_actions:
  - name: Bewegung
    desc: Strahd bewegt sich bis zu seiner Bewegungsrate weit, ohne Gelegenheitsangriffe zu provozieren.
  - name: Waffenloser Angriff
    desc: Strahd führt einen Waffenlosen Angriff aus.
  - name: Biss (kostet 2 Aktionen)
    desc: Der Vampir führt einen Biss-Angriff aus.
```