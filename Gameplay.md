# Gameplay
```table-of-contents
title: 
style: nestedList # TOC style (nestedList|nestedOrderedList|inlineFirstLevel)
minLevel: 0 # Include headings from the specified level
maxLevel: 0 # Include headings up to the specified level
includeLinks: true # Make headings clickable
debugInConsole: false # Print debug info in Obsidian console
```
## Rolling the Dice

### Canceling
If a check has both **Advantage** and **Disadvantage** count up the number of each.  If there are more advantages, the roll is made at **Advantage**.  If there are more disadvantages, the roll is made at **Disadvantage**.  If they are equal, the roll is made normally.

## Luck Tokens
Each PC may have a number of luck tokens equal to 1/2 their character's level, rounded down.

## Time

### Real Time
We will not be using real time.

### Turns and Rounds
There are two types of Turns and two types of Rounds: Combat and Crawling.

Combat Turns and Rounds occur during combat or any other scenario where every second counts.  A full Round of combat takes approximately 6 seconds.

Crawling Turns and Rounds occur outside of combat when crawling a dungeon or similar location.  A full Crawling Round takes approximately 6 minutes.

## Turn Order

### Initiative
Initiative is re-rolled at the start of each Combat or any other scenario in which strict time-keeping is required (such as trying to escape a flooding room).

### Freeform Mode
This will be the norm outside of combat.  Rather than adhering to strict initiative outside of combat and combat-like scenarios, players will be able to act in whatever order they wish during a Crawling Turn.  The only restriction is that each player only gets to declare a single course of action (moving, searching, picking a lock, etc).

## Crawling

### Vision
Areas outside of a light source's illumination, but within Near of its edge, are considered Dim Lighting.  Outside of that, it is total darkeness.

### Light Sources
Torches last for up to one hour (10 Crawling Rounds).
Lanterns and candles last for up to one watch (4 hours or 40 Crawling Rounds).

### Dim Lighting
This is a new level of lighting between fully lit and total darkness.  Creatures without either low-light vision or darkvision have **disadvantage** on tasks requiring sight. Both creatures with low-light vision and darkvision are unimpaired by dim lighting.  Dim lighting is not **deadly** like total darkness.

### Movement

#### Falling
Falling from a height onto a hard surface inflicts blunt damage onto the falling creature.  The following table denotes how much damage a creature takes when falling from a given height, as well as how long that fall will take.

| Time   | Velocity | Dist    | Damage | Notes             |
|-------:|---------:|--------:|-------:|:------------------|
| 0.40s  | 10fps    | 3ft     | 1d6    |                   |
| 0.60s  | 20fps    | 6ft     | 2d6    |                   |
| 0.90s  | 30fps    | 13ft    | 3d6    |                   |
| 1.20s  | 40fps    | 23ft    | 4d6    |                   |
| 1.60s  | 50fps    | 41ft    | 5d6    |                   |
| 1.90s  | 60fps    | 58ft    | 6d6    |                   |
| 2.20s  | 70fps    | 77ft    | 7d6    |                   |
| 2.60s  | 80fps    | 108ft   | 8d6    |                   |
| 3.00s  | 90fps    | 144ft   | 9d6    |                   |
| 3.40s  | 100fps   | 185ft   | 10d6   |                   |
| 3.80s  | 110fps   | 231ft   | 11d6   |                   |
| 4.30s  | 120fps   | 296ft   | 12d6   |                   |
| 4.80s  | 130fps   | 369ft   | 13d6   |                   |
| 5.40s  | 140fps   | 467ft   | 14d6   |                   |
| 6.00s  | 150fps   | 576ft   | 15d6   | 1 Round           |
| 7.00s  | 160fps   | 784ft   | 16d6   |                   |
| 8.20s  | 170fps   | 1,076ft | 17d6   |                   |
| 10.00s | 180fps   | 1,600ft | 18d6   |                   |
| 15.60s | 190fps   | 3,894ft | 19d6   | Terminal Velocity |

#### Moving Through
Moving through an ally counts as rough terrain.

Moving through an enemy requires a **contested** STR or DEX check vs. the target's choice of STR or DEX.  It is also treated as rough terrain.

#### Swimming
Characters failing a swim check will begin drowning.  If they had a chance to draw a breath, a character can hold their breath for a number of minutes equal to their Constitution Modifier (minimum of 30 seconds).  If they did not get the chance to draw a breath, halve this time.  Each round after this time passes, the character will gain 1d4 levels of Exhaustion.

### Conditions
See the [Conditions](Conditions.md) document.

## Resting
After an 8-hour rest, regain the following:
- 1 level of Exhaustion
- CON score in HP
- 1 point of stat damage for each damaged stat

### Safe Haven
A Safe Haven is defined as any location where characters can rest with no fear of danger nor any need to set up a watch.  Typically this is a friendly town, keep or the like where the characters have access to good food and warm beds. The GM will let the players know when their characters have encountered a Safe Haven.

Certain activities (such as practicing a craft, healing under medical care, and so forth) can only be undertaken when in a safe haven.

## Stealth and Surprise

### Hiding and Sneaking
The target number of the stealth check is the WIS of any opposed creatures.  This check is always rolled in secret by the GM.

## Combat

### Actions
**Melee Attack** - Attacks with Finesse weapons may use DEX in place of STR if the attacker wishes.

**Ranged Attack** - Attacks with thrown weapons may use STR in place of DEX if the attacker wishes.

### Damage
**Critical Hit** - Instead of doubling the damage dice, the attack does it's normal damage plus the max it could roll on the damage dice.  *For example, if a sword normally does 1d8+2 damage, it will do 1d8 + 2 + 8 damage on a critical hit.*

### Death
Instead of using the described **Death Timer**, in order to keep things more unpredictable, we will be using a Countdown Pool mechanic called a **Death Pool**.  For a pool of six sided dice equal to the characters CON Modifier plus their WIS Modifier.  If this total is 0 or less, use a pool size of 1.  At the end of each of the character's turns, they roll this pool of dice and remove any dice that come up as a "1".  Once the pool is empty, the character dies.

If the character takes a hit while dying, one die is removed from the pool automatically and immediately.  If the hit is a critical hit, two dice are removed.

The rules for **stabilizing** are as given in the core rulebook.

## Overland Travel

### Light
When outside at night time, in a heavy fog, or under a very dense canopy, the light level is reduced to Dim.  On a moonless or heavily overcast night, or if two of the previous factors are combined (night + dense canopy), the light level is reduced to full Dark.

### Travel per Day
**Forced Marches** (traveling more than 8 hours in a day) require a CON check starting at difficulty 12.  This check must be made at the beginning of each hour of travel, and the difficulty increases by +3 per consecutive hour of travel.  When a check is failed, the character in question gains +1 level of Exhaustion.  Once level 6 Exhaustion is reached, forced marching is no longer possible.

### Crossing Hexes

| Method            | Time per 6-mile Hex |
|:------------------|:--------------------|
| Walking           | 4 hours             |
| Mounted           | 2 hours             |
| Sailing           | 1 hour              |
| Difficult Terrain | 2x normal           |
| Arduous Terrain   | 4x normal           |

The given speed for sailing movement is assuming travel with the wind/current.  If sailing perpendicular to the wind/current, treat as Difficult Terrain.  If sailing against the wind/current, treat as Arduous terrain.

### Food and Water
Going for more than a day without food or water incurs significant penalties.  Any character going more than a day without food will gain 1 level of [Exhaustion](#Exhaustion) per day and they cannot recover levels of exhaustion until they get a meal.  Any character going more than a day without water will gain 1 level of Exhaustion per Watch (4 hours) after that first day and cannot recover any levels of exhaustion until they get water.

During travel, once per day, the party may make an INT check (difficulty dependent on terrain) to forage for 1d4 rations.  This may not be done during a Forced March.

## Downtime
See the [Downtime](Downtime.md) document.