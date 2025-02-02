## Weaponry 
### Reading a Weapon Entry
### Weapon Groups
### Weapon Design
#### Weapon Design Points System
In order to maintain a semblance of balance between each weapon, *Mages* uses a "points" system. Each component of a weapon (such as damage die size and traits) has an internal "point" value that is used to determine the "worth" of that component. 
##### Starting Point
Each weapon starts at a 1d6 damage die, as a Simple, 1-Handed weapon, and 1 free point.
##### Weapon Flaws
Weapons then gain extra points via taking on "flaws", which are priced at different rates. These points are presented below:

|        Flaw        |                          Details                           |                         Points                          |
|:------------------:|:----------------------------------------------------------:|:-------------------------------------------------------:|
|      Loading       | Determines how many actions it takes to reload the weapon. |               3 points per reload action.               |
|      2 Handed      |     Increases how many hands the weapon takes to use.      |             6 points (3 for ranged weapons)             |
|       Volley       |   Gives the weapon a *further* minimum effective range.    |            3 points per each range increment            |
|     Expensive      |                  Increases weapon's cost.                  | 2 points per x1 to base cost (2 for x2, 4 for x3, ect.) |
|       Heavy        |                  Increases Heft of weapon                  |      2 points, 1.5x.                                                   |
| Increased Training |           Increases the proficiency tier needed.           |             4 for martial, 6 for advanced.              |

Once the weapon's flaws have been chose, the final pool of points for the weapon to buy its "boons" is complete.
#### Weapon Boons
Weapons can then spend their points on boons, which define the weapon's characteristics. 

|          Lesser (1 point)           |      Greater (2 Points)       |         Major (3 Points)          |
|:-----------------------------------:|:-----------------------------:|:---------------------------------:|
|            [[Graceful]]             |         [[Forceful]]          |             [[Reach]]             |
|           [[Integrated]]            | [[Repeating]](per extra shot) |           [[Critical]]            |
|              [[Dual]]               |  [[Capacity]] (per 2 shots.)  |   [[Flurry]] (per extra attack)   |
|        [[Thrown]] (per 4 sp)        |          [[Channel]]          |         [[High-Powered]]          |
|          [[Anti-Ablative]]          |         [[Parrying]]          |             [[Area]]              |
|  [[Reliable]] (Ranged, per 1 die.)  |        [[Devastating]]        | [[Reliable]]  (Melee, per 1 die.) |
| [[Scatter]] (1 point per die size.) |                               |                                   |

#### Finishing Up
## Armor 
### Overview 
Armor in `=[[Dev Helpers]].game-full` is integral to every character; every mage, no matter how reliant on magic, will encounter a situation (such as a gun) where a simple ward might not stop them from being damaged (such as when shot at, with a gun.) In these cases, even the lightest armor might be enough to save the Mage-Pilot's life. In order to determine what armor set is right for your Mage-Pilot, you'll need to know how to read an entry, which is explained below. 

### Reading an Armor Entry 
Armor is presented, much like everthing else, in a stat block. This example shows the structure of the block and how to read it.

> [!info]- Example Armor Entry
> # Armor Name
> ###### Armor Information
|                   |                           |
|:-----------------:|:-------------------------:|
|   **Price**     |     This gives the price of the armor set, in units.           |
|  **Armor Category**   |    This denotes what proficiency governs the armor.       |
|    **Armor Group**    |       This details the material of the armor, which determines the armor's Specialization Effect. |
|  **Toughness Bonus**  | This is the *untyped* bonus to Toughness the armor grants. |
|   **Check Penalty**   |  This is the penalty the armor imposes on any [[Character Mechanics Overview#Reflex\|Reflex]] and/or [[Character Mechanics Overview#Potential\|Potential]] checks made while wearing it.  |
| **Armor Requirement** |   If the wearer meets the requirement(s) listed here, they reduce the Check Penalty by half.  |
|    **Armor Heft**     |     This is how much the armor weighs when *not* equipped.     |
|      Traits       |        These are the traits that the armor has.                    |
> ###### *Description*


### Types of Armor 
In `=[[Dev Helpers]].game-short`, there are three types of armor, each of which is governed by their own proficiencies. These three armor types are ordered in terms of how "heavy" the armor is, as in how much mobility is sacrificed for protection, or vice versa if you want to view it that way. 

Each armor's proficiency perks are copied here for reference, and can originally be found in the [[Character Mechanics Overview]].
#### Infiltrator
This is the lightest form of armor in the game, and compromises nearly entirely on protection in order to allow the wearer high levels of casting flexibility and stealth. 
###### Infiltrator Armor Example
![[Syn-theather]]
###### Infiltrator Armor Perks
![[Character Mechanics Overview#^059684]]
#### Mobile
Mobile armor is the middle ground between the light Infiltrator and the heavy Powered armors. It allows the wearer to locomote easily but also remain protected from lighter attacks and weapons fire.
###### Mobile Armor Example
![[Filament Scalemail]]
###### Mobile Armor Perks
![[Character Mechanics Overview#^85f3b3]]
#### Powered 
The heaviest of the armor types, Powered armor can turn the wearer into a walking tank, although readily compromising their stealth and spellcasting capabilities due to the amount of material present.
###### Powered Armor  Example
![[Carbon Alloy Plate]]
###### Powered Armor Perks
![[Character Mechanics Overview#^83a377]]
### Shields 
In `=[[Dev Helpers]].game-short`, shields work a little differently from other pieces of armor; below is an example of a shield.
![[Heater]]

A shield has an armor type, which is typically only interacted with by feats. Shields are instead typically governed by the [[Block]] skill instead of their respective armor proficiency. 

Shields also have a set of unique statistics: *protection*, *barrier*, and *recharge*.
##### Protection 
This statistic denotes the Toughness bonus granted by the shield while it is Raised. See the [[Block#^7506d9|Raise Shield]] action for more details. It also acts as the Toughness of the shield's Health, or *barrier.*
##### Barrier 
The *barrier* statistic of a shield is its "Health" value; it is a pool of points that represent the durability of the shield, and takes damage instead of the wielder if any makes it through their Toughness. A shield's barrier also has the Resistances listed in the shield's equipment entry. Once a shield reaches 0 barrier, it is disabled; it cannot be Raised or otherwise used, and confers no benefits until it is *recharged*. 
##### Recharge 
This statistic denotes how many Interact actions must be taken in order to restore the barrier. Once Recharged, the shield can be used for actions that require one and can confer its benefits. 
##### Armor Design
***Segment In Progress***
## Gear
### Gear Design
***Segment In Progress***
## Consumables 
### Consumable Design
***Segment In Progress***
## Equipment Durability and You
All equipment has a durability that can be divided up into four stages:
- *Working Order* — The equipment works as intended and has no issues.
- *Minor Damage* — The equipment has sustained some damage that slightly impacts its effectiveness. Its user suffers a -1 equipment penalty to any check involving the item (this penalty also applies to Toughness if it is armor.) If it is a ranged weapon, critical failures on attack rolls cause it to *jam*, rendering it unusable until a single action is used to clear it. 
- *Major Damage* — The equipment is on the verge of failure. Its user suffers a -3 equipment penalty to any check involving the item (this penalty also applies to Toughness if it is armor.) If it is a ranged weapon, failures on attack rolls cause it to *jam*, rendering it unusable until a single action is used to clear it, and on a critical failure, the user must make a TN 12 flat check. On a failure, the weapon is destroyed. If it is a melee weapon, on *any* attack, regardless of outcome, the user must make a TN 12 flat check. On a failure, the weapon is destroyed.
- *Destroyed* — The equipment is completely unusable and must be replaced. 

A single piece of equipment can sustain two “hits” of damage before progressing to the next durability stage. Some items, such as glassware and pottery, break in one hit. These rules are meant to be a guideline, as equipment durability is not intended to be a prevalent issue for players. These rules are presented for niche cases, arguments, and revenge purposes.