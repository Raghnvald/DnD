---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/3
  - Monster/Größe/Riesig
  - Monster/Typ/Fee
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Giant Ox
---
# [Giant Ox](3-Mechanics\CLI\bestiary\fey/giant-ox-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 152*  

Giant oxen labor as beasts of burden for giants of all kinds, pulling plows, hauling oversized carts, and performing similar tasks well suited to their tremendous strength. These cattle are covered in thick, shaggy hide, often in vibrant colors, such as sky blue or deep violet.

> [!quote] A quote from Bigby  
> 
> It's easy to get caught up in the wonders of giant-sized wildlife when you're wandering some pocket of a primeval world tucked away in a remote valley or demiplane somewhere. "Look, that goose laid a golden egg!" "Look, that ox is blue!" "Look, this ram's magic fleece is so soft!" Then a tick that's bigger than you tries to drain every drop of blood from your body. Nope, nope, nope. Time to go home.


```statblock
"name": "Giant Ox (BGG)"
"size": "Huge"
"type": "fey"
"alignment": "Unaligned"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "105"
"hit_dice": "10d12 + 40"
"modifier": !!int "0"
"stats":
  - !!int "22"
  - !!int "10"
  - !!int "19"
  - !!int "4"
  - !!int "11"
  - !!int "9"
"speed": "40 ft."
"senses": "passive Perception 10"
"languages": "understands Giant and Sylvan but can't speak"
"cr": "3"
"traits":
  - "desc": "The ox is considered to be one size larger for the purpose of determining\
      \ its carrying capacity."
    "name": "Beast of Burden"
"actions":
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:* 13\
      \ (2d6 + 6) piercing damage. If the ox moved at least 20 feet straight toward\
      \ the target immediately before the hit, the target takes an extra 7 (2d6) piercing\
      \ damage, and it must succeed on a DC 16 Strength saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition."
    "name": "Gore"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/fey/token/giant-ox-bgg.webp"
```
^statblock