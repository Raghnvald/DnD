---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mm
  - Monster/HG/12
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Unhold/yugoloth
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Arcanaloth
Kategorie: Unhold
Größe: Mittelgroß
HG: 12
Habitat: Planar
status: completed
image: pictures/arcanaloth-2024.webp
aliases:
  - Arcanaloth
---
# [Arcanaloth](3-Mechanics\CLI\bestiary\fiend/arcanaloth.md)
*Source: Monster Manual p. 313*  

Arcanaloths are sly, jackal-headed beings with humanoid bodies, but they can employ magic to take any humanoid form. They do so to gain the trust of creatures with whom they negotiate, replacing jackal snarls with winsome smiles. Regardless of its chosen form, an arcanaloth appears well groomed, clothing itself in fine robes. Highly intelligent spellcasters who hunger for knowledge and power, arcanaloths command units of lesser yugoloths and maintain the contracts, records, and accounts of their kind.

Arcanaloths speak and write all languages, making them cunning diplomats and negotiators. An arcanaloth properly paid can broker treaties or alliances with subtlety and finesse, just as an arcanaloth who changes sides can easily turn the best-laid peace talks into all-out war. What the fiend demands in exchange for its time and talent is information, as well as powerful magic items that it can trade for even more information.

## Yugoloths

Yugoloths are fickle fiends that inhabit the planes of Acheron, Gehenna, Hades, and Carceri. They act as mercenaries and are notorious for their shifting loyalties. They are the embodiments of avarice. Before serving under anyone's banner, a yugoloth asks the only question on its mind: *What's in it for me?*

### Spawn of Gehenna

The first yugoloths were created by a sisterhood of night hags on Gehenna. It is widely believed that Asmodeus, Lord of the Nine Hells, commissioned the work, in the hope of creating an army of fiends that were not bound to the Nine Hells. In the course of making this new army, the hags crafted four magic tomes and recorded the true names of every yugoloth they created, save one, the General of Gehenna. These tomes were called the Books of Keeping. Since knowing a fiend's true name grants power over it, the hags used the books to ensure the yugoloths' loyalty. They also used the books to capture the true names of other fiends that crossed them. It is rumored that the Books of Keeping contain the true names of a few demon lords and archdevils as well.

Petty jealousies and endless bickering caused the sisterhood to dissolve, and in the ensuing power grab, the Books of Keeping were lost or stolen. No longer indentured to anyone, the yugoloths gained independence, and they now offer their services to the highest bidder.

### Fiendish Mercenaries

Summoned yugoloths demand much for their time and loyalty. Whatever promises a yugoloth makes are quickly broken when a better opportunity presents itself. Unlike demons, yugoloths can be reasoned with, but unlike devils, they are rarely true to their word.

Yugoloths can be found anywhere, but the high cost of maintaining a yugoloth army's loyalty typically exceeds what any warlord on the Material Plane can pay. Being self-serving creatures, yugoloths quarrel among themselves constantly. A yugoloth army is more organized than a ravening horde of demons, but far less orderly and regimented than a legion of devils. Without a powerful leader to keep them in line, yugoloths fight simply to indulge their violent predilections, and only as long as it benefits them to do so.

### Back to Gehenna

When a yugoloth dies, it dissolves into a pool of ichor and reforms at full strength on the Bleak Eternity of Gehenna. Only on its native plane can a yugoloth be destroyed permanently. A yugoloth knows this and acts accordingly. When summoned to other planes, a yugoloth fights without concern for its own well-being. On Gehenna, it is more apt to retreat or plead for mercy if its demise seems imminent.

When a yugoloth is permanently destroyed, its name vanishes from every Book of Keeping. If a yugoloth is re-created by way of an unholy ritual requiring the expenditure of souls, its name reappears in the books.

### The Books of Keeping

When all four copies of the Books of Keeping disappeared, Asmodeus and the night hags lost control of their yugoloth creations. Each Book of Keeping still exists, drifting from plane to plane, where the brave and the foolish occasionally stumble upon them. A yugoloth summoned using its true name, as inscribed in the Books of Keeping, is forced to serve its summoner obediently. The yugoloth hates being controlled in this manner and isn't shy about making its displeasure known. Like a petulant child, it will follow its instructions to the letter while looking for opportunities to misinterpret them.

### The General of Gehenna

Somewhere in the brimstone wastes of Gehenna, there roams an ultroloth so strong that none contests his power: the General of Gehenna. Many yugoloths search for this great general in the hope of serving with him. They believe that service with the General of Gehenna grants power and prestige among lower planar entities.

Whatever the case, no fiend finds the General unless the General desires it. His personal name is unknown, and even the Books of Keeping contain no mention of this powerful, thoroughly evil entity.

> [!note] Variant: Yugoloth Summoning
> 
> Some yugoloths can have an action option that allows them to summon other yugoloths.
> 
> **Summon Yugoloth (1/Day).** The yugoloth chooses what to summon and attempts a magical summoning.
> 
> - An arcanaloth has a 40 percent chance of summoning one arcanaloth.  
> - A mezzoloth has a 30 percent chance of summoning one mezzoloth.  
> - A nycaloth has a 50 percent chance of summoning `1d4` mezzoloths or one nycaloth.  
> - An ultroloth has a 50 percent chance of summoning `1d6` mezzoloths, `1d4` nycaloths, or one ultroloth.  
> 
> A summoned yugoloth appears in an unoccupied space within 60 feet of its summoner, does as it pleases (unless its summoner is an ultroloth, in which case it acts as an ally of its summoner), and can't summon other yugoloths. The summoned yugoloth remains for l minute, until it or its summoner dies, or until its summoner takes a bonus action to dismiss it
^variant-yugoloth-summoning

> [!quote] A quote from Shemeshka the Marauder  
> 
> Power. We all crave it, but only a select few of us deserve it.


```statblock
"name": "Arcanaloth"
"size": "Medium"
"type": "fiend"
"subtype": "yugoloth"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "104"
"hit_dice": "16d8 + 32"
"modifier": !!int "1"
"stats":
  - !!int "17"
  - !!int "12"
  - !!int "14"
  - !!int "20"
  - !!int "16"
  - !!int "17"
"speed": "30 ft., fly 30 ft."
"saves":
  - "dexterity": !!int "5"
  - "intelligence": !!int "9"
  - "wisdom": !!int "7"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+13"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+11"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+11"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "acid, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 17"
"languages": "all, telepathy 120 ft."
"cr": "12"
"traits":
  - "desc": "The arcanaloth is a 16th-level spellcaster. Its spellcasting ability\
      \ is Intelligence (spell save DC 17, +9 to hit with spell attacks). The arcanaloth\
      \ has the following wizard spells prepared:\n\n**Cantrips (at will):** [fire\
      \ bolt](/3-Mechanics/CLI/spells/fire-bolt.md), [mage hand](/3-Mechanics/CLI/spells/mage-hand.md),\
      \ [minor illusion](/3-Mechanics/CLI/spells/minor-illusion.md), [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation.md)\n\
      \n**1st level (4 slots):** [detect magic](/3-Mechanics/CLI/spells/detect-magic.md),\
      \ [identify](/3-Mechanics/CLI/spells/identify.md), [shield](/3-Mechanics/CLI/spells/shield.md),\
      \ [Tenser's floating disk](/3-Mechanics/CLI/spells/tensers-floating-disk.md)\n\
      \n**2nd level (3 slots):** [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts.md),\
      \ [mirror image](/3-Mechanics/CLI/spells/mirror-image.md), [phantasmal force](/3-Mechanics/CLI/spells/phantasmal-force.md),\
      \ [suggestion](/3-Mechanics/CLI/spells/suggestion.md)\n\n**3rd level (3 slots):**\
      \ [counterspell](/3-Mechanics/CLI/spells/counterspell.md), [fear](/3-Mechanics/CLI/spells/fear.md),\
      \ [fireball](/3-Mechanics/CLI/spells/fireball.md)\n\n**4th level (3 slots):**\
      \ [banishment](/3-Mechanics/CLI/spells/banishment.md), [dimension door](/3-Mechanics/CLI/spells/dimension-door.md)\n\
      \n**5th level (2 slots):** [contact other plane](/3-Mechanics/CLI/spells/contact-other-plane.md),\
      \ [hold monster](/3-Mechanics/CLI/spells/hold-monster.md)\n\n**6th level (1\
      \ slots):** [chain lightning](/3-Mechanics/CLI/spells/chain-lightning.md)\n\n\
      **7th level (1 slots):** [finger of death](/3-Mechanics/CLI/spells/finger-of-death.md)\n\
      \n**8th level (1 slots):** [mind blank](/3-Mechanics/CLI/spells/mind-blank.md)"
    "name": "Spellcasting"
  - "desc": "The arcanaloth's innate spellcasting ability is Charisma (spell save\
      \ DC 15). The arcanaloth can innately cast the following spells, requiring no\
      \ material components:\n\n**At will:** [alter self](/3-Mechanics/CLI/spells/alter-self.md),\
      \ [darkness](/3-Mechanics/CLI/spells/darkness.md), [heat metal](/3-Mechanics/CLI/spells/heat-metal.md),\
      \ [invisibility](/3-Mechanics/CLI/spells/invisibility.md) (self only), [magic\
      \ missile](/3-Mechanics/CLI/spells/magic-missile.md)"
    "name": "Innate Spellcasting"
  - "desc": "The arcanaloth has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The arcanaloth's weapon attacks are magical."
    "name": "Magic Weapons"
"actions":
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 8 (2d4\
      \ + 3) slashing damage. The target must make a DC 14 Constitution saving throw,\
      \ taking 10 (3d6) poison damage on a failed save, or half as much damage on\
      \ a successful one."
    "name": "Claws"
  - "desc": "The arcanaloth magically teleports, along with any equipment it is wearing\
      \ or carrying, up to 60 feet to an unoccupied space it can see."
    "name": "Teleport"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/arcanaloth.webp"
```
^statblock

# Arcanaloth (2014)
Arcanaloths sind schlaue, schakalköpfige Wesen mit humanoiden Körpern, die jedoch durch Magie jede humanoide Gestalt annehmen können. Sie tun dies, um das Vertrauen von Kreaturen zu gewinnen, mit denen sie verhandeln, und ersetzen das Schakalknurren durch ein gewinnendes Lächeln.

Unabhängig von seiner gewählten Form erscheint ein Arcanaloth stets gepflegt und trägt ein feines Gewand. Als hochintelligente Zauberwirker, die nach Wissen und Macht hungern, befehligen Arcanaloths Einheiten kleinerer Yugoloths und führen die Verträge, Aufzeichnungen und Konten ihrer Art.

Arcanaloths sprechen und schreiben alle Sprachen, was sie zu geschickten Diplomaten und Verhandlungsführern macht. Ein gut bezahlter Arcanaloth kann mit Raffinesse und Feingefühl Verträge oder Bündnisse aushandeln, während ein Arcanaloth, der die Seiten wechselt, die besten Friedensverhandlungen leicht in einen totalen Krieg verwandeln kann. Als Gegenleistung für seine Zeit und sein Talent verlangt der Unhold Informationen sowie mächtige magische Gegenstände, die er gegen noch mehr Informationen eintauschen kann.

```statblock
name: Arcanaloth (2014)
size: Mittelgroß
source: Monsterhandbuch 2014
type: Unhold
subtype: (Yugoloth)
alignment: Neutral Böse
ac: 17
hp: 104
hit_dice: 16d8 + 32
speed: 9 Meter, 9 Meter Fliegen.
stats: [17, 12, 14, 20, 16, 17]
saves:
  - STR: +0
  - GES: +5
  - KON: +0
  - INT: +9
  - WEI: +7
  - CHA: +7
skillsaves:
  - Arkane Kunde: 13
  - Motiv erkennen: 9
  - Täuschung: 9
  - Wahrnehmung: 7
damage_vulnerabilities: ""
damage_resistances: "Blitz, Feuer, Kälte, Hieb-, Stich- und Wuchtschaden von nicht-magischen Angriffen"
damage_immunities: "Gift, Säure"
condition_immunities: "[[Anhang PH-A#Bezaubert|Bezaubert]], [[Anhang PH-A#Vergiftet|Vergiftet]]"
senses: [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Wahrer Blick|Wahrer Blick]] 36 Meter, passive Wahrnehmung 17
languages: Alle, telepathisch 36 Meter
cr: 12
bestiary: true
traits:
  - name: Angeborenes Zauberwirken.
    desc: "Das Attribut zum Wirken angeborener Zauber des Arcanaloths ist Charisma (Zauberrettung SG 15). Der Arcanaloth kann von Natur aus die folgenden Zauber wirken, wobei er keine Komponenten benötigt: <br><br> **Beliebig oft:** [Gestalt verändern](Gestalt-verändern.md), [Dunkelheit](Dunkelheit.md), [[Magisches Geschoss]], [Metall erhitzen](Metall-erhitzen.md), [Unsichtbarkeit](Unsichtbarkeit.md) (nur selbst)"
  - name: Magische Resistenz.
    desc: "Der Arcanaloth ist bei Rettungswürfen gegen Zauber und andere magische Effekte im Vorteil."
  - name: Magische Waffe.
    desc: "Waffen, welche der Arcanaloth trägt, sind magisch."
actions:
  - name: Klauen.
    desc: "_Nahkampfangriff_: +7 zum Treffen, Reichweite 1,5m, ein Ziel. _Treffer_: 8 (2d4 + 3) Hiebschaden. Dem Ziel muss ein Konstitutions-Rettungswurf SG 14 gelingen, oder erleidet 10 (3d6) Giftschaden bei einem misslungenen Rettungswurf, oder die Hälfte bei einem erfolgreichen."
    attack_bonus: 7
    damage_dice: 2d4
    damage_bonus: 3
  - name: Teleportation
    desc: "Der Arcanaloth teleportiert sich bis zu 9m an einen freien Ort, welchen er sehen kann."
spells:
  - "Der Arcanaloth ist ein Zauberwirker der 16. Stufe. Sein Attribut zum Zauberwirken ist Intelligenz (Zauberrettungswurf-SG 17, +9 zum Treffen mit Zauberangriffen). Der Arcanaloth hat die folgenden Magierzaubersprüche vorbereitet:"
  - "Zaubertricks (beliebig oft): [Einfache Illusion](Einfache-Illusion.md), [Feuerpfeil](Feuerpfeil.md), [Magierhand](Magierhand.md), [Taschenspielerei](Taschenspielerei.md)"
  - "Zaubergrad 1 (4 Plätze): [Identifizieren](Identifizieren.md), [Magie entdecken](Magie-entdecken.md), [Schild](Zauber/Schild.md), [Tensers Schwebende Scheibe](Tensers-Schwebende-Scheibe.md)"
  - "Zaubergrad 2 (3 Plätze): [Einflüsterung](Einflüsterung.md), [Gedanken wahrnehmen](Gedanken-wahrnehmen.md), [Macht der Vorstellungskraft](Macht-der-Vorstellungskraft.md), [Spiegelbilder](Spiegelbilder.md)"
  - "Zaubergrad 3 (3 Plätze): [Feuerball](Feuerball.md), [Furcht](Furcht.md), [Gegenzauber](Gegenzauber)"
  - "Zaubergrad 4 (3 Plätze): [Dimensionstür](Dimensionstür.md), [Verbannung](Verbannung.md)"
  - "Zaubergrad 5 (2 Plätze): [Kontakt zu anderen Ebenen](Kontakt-zu-anderen-Ebenen.md), [Monster festhalten](Monster-festhalten.md)"
  - "Zaubergrad 6 (1 Platz): [Kugelblitz](Kugelblitz.md)"
  - "Zaubergrad 7 (1 Platz): [Finger des Todes](Finger-des-Todes.md)"
  - "Zaubergrad 8 (1 Platz): [Gedankenleere](Gedankenleere.md)"
```