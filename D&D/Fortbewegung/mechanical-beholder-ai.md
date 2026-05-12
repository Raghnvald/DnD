---
obsidianUIMode: preview
cssclasses:
- json5e-vehicle
tags:
- ttrpg-cli/compendium/src/5e/ai
- ttrpg-cli/vehicle/size/huge
- ttrpg-cli/vehicle/terrain/air
- ttrpg-cli/vehicle/terrain/land
- ttrpg-cli/vehicle/terrain/sea
- ttrpg-cli/vehicle/type/ship
aliases:
- "Mechanical Beholder"
---
# Mechanical Beholder
*Source: Acquisitions Incorporated p. 219*  

*When you hear the mechanical beholder click to life, it sounds like death itself snapping its fingers.*

A mechanical beholder takes the form of an oversized eye tyrant whose central eye is a viewport window. Part conveyance, part laboratory, and part siege engine, the vehicle can transport up to six humanoids through any terrain or medium, including underwater and through solid stone. A complex and often dangerous manipulation of gears, levers, and buttons controlled the original mechanical beholders, but more recent models feature magical controls that respond to voice commands—though not always accurately.

## Equipment and Options

The mechanical beholder can be outfitted with a variety of sensors, probes, and gauges, allowing for functions as varied as determining alchemical composition, picking up on magical auras, or making masterfully dry martinis. Its range of armaments includes a disintegration ray modeled after that of its monstrous namesake (which for reasons of liability is advertised as being designed exclusively for waste removal). Portholes and hatches allow characters inside the beholder to make ranged and magical attacks from within it.

## Statblock

```ad-statblock
title: Mechanical Beholder
![](3-Mechanics/CLI/vehicles/token/mechanical-beholder-ai.webp#token)
*Huge vehicle (15 ft. by 15 ft.); land, sea, air*

- **Creature Capacity** 1 crew, 5 passengers
- **Cargo Capacity** crew and passengers' normal gear
- **Travel Pace** 3 miles per hour (72 miles per day)
- *Speed* 30 ft. ^[Based on _Special Travel Pace_, DMG p242]

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|12 (+1)|18 (+4)| 0 (-5)| 0 (-5)| 0 (-5)|

- **Damage Immunities** poison, psychic
- **Condition Immunities** blinded, charmed, deafened, exhaustion, frightened, incapacitated, paralyzed, petrified, poisoned, prone, stunned, unconscious

## Actions

On its turn the mechanical beholder can take 1 action. It cannot take any actions if it has no crew.

- **Eye Rays.** The mechanical beholder can use its eye ray tentacles.  
- **Move.** The mechanical beholder can use its helm to move using its magical propulsion unit.  

## Hull

- **Armor Class** 18
- **Hit Points** 200 (damage threshold 10)

## Control: Helm

- **Armor Class** 16
- **Hit Points** 25

Move up to the speed of the ship's magical propulsion unit, with one 90-degree turn. The helm can be attacked only if the hull has taken 100 or more damage. If the helm is destroyed, the mechanical beholder can't move.

## Movement: Magical Propulsion Unit

- **Armor Class** 16
- **Hit Points** 100; -5 ft. speed per 25 damage taken
- **Speed (magical)..** burrow 30 ft., fly 30 ft. (hover), swim 30 ft.

## Weapon: Eye Ray Tentacles (6)

- **Armor Class** 14
- **Hit Points** 50

*Magical Attack Roll:* The mechanical beholder shoots the following magical eye rays at up to three targets that would be visible to the crew and are within 120 feet of it.

- **Disintegration Ray.** If the target is a creature, it must succeed on a DC 15 Dexterity saving throw or take 18 (`4d8`) force damage. If this damage reduces the creature to 0 hit points, its body becomes a pile of fine gray dust. If the target is a Large or smaller nonmagical object or creation of magical force, it is disintegrated without a saving throw. If the target is a Huge or larger object or creation of magical force, this ray disintegrates a 10-foot cube of it.  

- **Enervation Ray.** The targeted creature must make a DC 15 Constitution saving throw, taking 18 (`4d8`) necrotic damage on a failed save, or half as much damage on a successful one.  

- **Paralyzing Ray.** The targeted creature must succeed on a DC 15 Constitution saving throw or be paralyzed for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.  
```
^statblock