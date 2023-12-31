---
Category: Physical
Attribute: Body
cssclasses: []
Tags:
  - Skills
Completed: true
---
# Skill Description-`=this.file.name`
**Athletics** governs feats of physical prowess and bodily performance. **Athletics** can also be used in place of a **Power** check when attempting to escape a Grapple. 
>[!info| clear no-i] `=this.file.name` Mechanics
>**Category:**  `=this.Category`   
>**Attribute:** `=this.Attribute`
- - -
# Skill Actions
#### Untrained Actions
These actions can be performed without any training in `=this.file.name `; they are available to any character. 
>[!info]+ ##### Jump `=[[Dev Helpers]].one-action`
>[[Modal]]
>- - -
>**Limit:** You can only take this action at the **end** of your normal Move.
>When you take this action, choose one of the following modes: 
>- High Jump: At the end of your Move, you jump vertically. Make an **Athletics** check. You leap upwards 1 space, plus 1 more space for each 4 margins of success. (For example, a result of 10 on an **Athletics** skill of 18 would allow you to ascend 3 spaces.) On a failure, you leap upward only 1 space, and on a critical failure, you fall prone in the space you ended your move in.
>- Far Jump: At the end of your Move, you jump horizontally. Make an **Athletics** check. You leap forwards 3 spaces, plus 1 more space for
each 2 margins of success. On a failure, you leap forward 1 space, and on a critical failure, you fall prone in the space you ended your move in.

> [!note]+ ##### Force Open ●
>
>- - -
> You use your body weight to attempt to open a locked door, chest, or other such impedance. Make an **Athletics** check with a difficulty penalty equal to the Difficulty Rating of the lock or barricade. On a success, you break open the lock or barricade. On a critical failure, the lock or barricade is jammed shut, increasing the Difficulty Rating by one stage and preventing Lockpicking (if its a lock.)


>[!info]+ ##### Climb ●
>[[Move]]
>- - -
>**Limit:** You have at least one hand free.
> You move across or about an incline. Make an **Athletics** check, with a modifier, based on circumstance, determined by your GM. 
>- **Success**: You move 1 space in a direction of your choosing, plus 1 more space for each 2 margins of success, up to your Speed.
>- **Failure**: You move 1 space in a direction of your GM's choosing.
>- **Critical Failure**: You fall.

#### Trained Actions
These actions can be performed by characters who are *Trained* in `=this.file.name`; they are not available to characters with lesser training.
> [!note]+ ##### Shove ●
>[[Attack]]
>- - -
>**Limit:** You have at least one hand free. Your target cannot be more than one size larger than you.
>
> You push a creature or object out of the way. Make an **Athletics** contest with the target. On a 
> - **Critical Success**: As success, but for each 2 margins of success instead.
> - **Success**: You displace the target 1 space backward, plus 1 more for each 4 margins of success. You may Move up to the same amount of spaces, but you must end this Move closer to the target.
> - **Critical Failure**: You trip and fall [[Prone]].

> [!note]+ ##### Grapple ●
>[[Attack]]
>- - -
>**Limit:** You have at least one hand free, or your target is [[Restrained]] by you. Your target cannot be more than one size larger than you.
>
> You attempt to grab ahold of a creature or object using your free hand. Make an **Athletics** contest with the target. If you attempt to Grapple a creature you already have Restrained, you do not need a free hand.
> - **Success**: Your target is Restrained by you, or, if they already were, they become [[Immobilized]] as well. This lasts until the end of your next turn, unless you Move or the target can Escape.
> - **Failure**: You fail to grab your target.
> - **Critical Failure**: You fail to grab your target. If your target was a creature, it can grab you, as if it succeeded using this action, or trip you, causing you to fall [[Prone]].

- - -
# Perks
>> [!info|text-Center clear]+  Trained Perk: Rough-Housing
>> *When you become Trained in `=this.file.name`, if you have aptitude in it, you gain the following benefits.*
>> 
>> Your athletic ability allows you to deal minor damage when grappling. Targets of your Shoves or Grapples take crushing damage equal to your Melee Damage Bonus when you successfully perform either of the aforementioned actions. 

>> [!info|text-Center clear]+ Expertise Perk: Heavy-Hauler
>> *When you become an Expert in `=this.file.name`, if you have aptitude in it, you gain the following benefits.*
>> 
>> You are well-fit to carry great amounts for grand distances. You treat your Power attribute as 4 higher for the sake of determining Carry Weight.

>> [!info|text-Center clear]+ Masterful Perk: Extraordinary Physique  
>> *When you become a Master in `=this.file.name`, if you have aptitude in it, you gain the following benefits.*
>> 
>> Your body is masterfully crafted after ages of hard work and dedication. Add 2 to your Power, Body and Tenacity Attributes, re-calculating your Statistics as necessary.  

>> [!info|text-Center clear]+ Legendary Perk: Pheidippidian Stamina
>> *When you become a Legend in `=this.file.name`, if you have aptitude in it, you gain the following benefits.*
>> 
>> You have stamina like that of the Heroes of the Old World. You are immune to becoming [[Fatigued]] or [[Exhausted]].