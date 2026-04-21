---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Knight of Eldraine
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/3
  - Monster/Typ/Humanoid/human
  - Quelle/5e/mcv4ec
aliases:
  - Knight of Eldraine
---
# [Knight of Eldraine](3-Mechanics\CLI\bestiary\humanoid/knight-of-eldraine-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

The realm of Eldraine once consisted of five knightly courts: Ardenvale, Embereth, Garenbrig, Locthwain, and Vantress. In ancient times, the courts were established around five relics of tremendous magical power and unknown origin. Each relic is a magical embodiment of one of the five virtues the knights of the realm hold as standards of excellence.

The recent invasion of nightmarish creatures called Phyrexians devastated the courts, with much of the surviving populace fleeing into the wilds. A young prince, Will Kenrith, does his best to reunite the shattered realm, but a return to its former glory seems far off.

Even in the shattered remnants of the realm, knighthood is among the highest honors one can receive. Knights of the realm, who are all addressed with the honorific "Syr," are revered as champions, heroes, and paragons of virtue. They have many responsibilities, from protecting townsfolk to embarking on adventures in the wilds. Knights are often equipped with fine armor and weapons, and they ride noble steeds of various species—including griffons in Ardenvale, giant owls in Vantress, and giant ravens (use the giant vulture stat block) in Locthwain. Some knights also wield powerful magic drawn from the relics of their respective courts.

In the wake of the Phyrexian invasion, whole orders of knights have journeyed deep into the wilds, searching for a magical remedy to restore the kingdom to its former glory, or seeking to help travelers and remote communities beset by troubles.

Achieving knighthood in one of the courts requires a quest that proves one's excellence in that court's virtue. In some courts, the final step to becoming a knight involves being judged by that court's relic. Each court believes the virtue associated with its own relic is paramount, though not in lieu of the others. A knight of Embereth admires courage above all else but still looks down on the disloyal or ignorant, even though loyalty and knowledge are virtues championed by other courts.

Knights of Eldraine channel their devotion to the virtues of the realm into magical power that infuses their attacks. Most knights deal extra radiant damage with these attacks, but some knights might deal damage of a different type, such as fire (for knights of Embereth) or necrotic (for knights of Locthwain).

> [!note] The Verdant Order
> 
> In the wake of the Phyrexian invasion, knights from all five courts of Eldraine have joined to form a new organization, the Verdant Order. These knights renounced their oaths in favor of a new one, swearing to protect the last part of their world untouched by war: the wildest parts of Eldraine. To that end, they patrol the forests along the Boundary Lands, turning back loggers and hunters—by force if necessary.
> 
> Though they've renounced their former oaths, the knights of the Verdant Order retain their focus on the five virtues of the courts, so their Knightly Virtue trait remains unchanged.
^the-verdant-order

```statblock
"name": "Knight of Eldraine (MCV4EC)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Any alignment"
"ac": !!int "20"
"ac_class": "plate, shield"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "13"
  - !!int "11"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "constitution": !!int "4"
  - "wisdom": !!int "2"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "3"
"traits":
  - "desc": "The knight has one of the following traits, depending on the court it\
      \ serves:\n\n- **Courage (Embereth).** The knight has advantage on Wisdom checks\
      \ and Wisdom saving throws.  \n- **Knowledge (Vantress).** The knight has advantage\
      \ on Intelligence checks and Intelligence saving throws.  \n- **Loyalty (Ardenvale).**\
      \ The knight has advantage on Charisma checks and Charisma saving throws.  \n\
      - **Persistence (Locthwain).** The knight has advantage on Constitution saving\
      \ throws.  \n- **Strength (Garenbrig).** The knight has advantage on Strength\
      \ checks and Strength saving throws.  "
    "name": "Knightly Virtue"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 10 ft., one target. *Hit:* 9\
      \ (1d12 + 3) piercing damage plus 9 (2d8) radiant damage."
    "name": "Lance"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8\
      \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands,\
      \ plus 9 (2d8) radiant damage."
    "name": "Longsword"
  - "desc": "*Ranged Weapon Attack:* +3 to hit, range 100/400 ft., one target. *Hit:*\
      \ 6 (1d10 + 1) piercing damage plus 9 (2d8) radiant damage."
    "name": "Heavy Crossbow"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/knight-of-eldraine-mcv4ec.webp"
```
^statblock