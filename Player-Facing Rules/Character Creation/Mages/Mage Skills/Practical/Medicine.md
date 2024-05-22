---
Category: Practical
Attribute: Mind
Tags:
  - Skills
Completed: false
---
# Skill Description-`=this.file.name`

>[!info| clear no-i] `=this.file.name` Mechanics
>**Category:** `=this.Category`   
>**Attribute:** `=this.Attribute`
---
# Skill Actions
#### Untrained Actions
These actions can be performed without any training in `=this.file.name `; they are available to any character. 
> [!note] ##### Estimate Health ●
>[[Secret]]
>- - -
> With a quick assessment, you attempt to deduce the current status of a combatant or ally. Choose a creature you can see and are aware of, then make a standard-difficulty *secret* **Medicine** check, or easy-difficulty if the target is [[Bloodied]].
> 
> **Critical Success** You learn the target’s current, *exact*, Health.
> **Success** You learn a rough estimate of the targe’s current Health.
> **Failure** You learn nothing new about the target.
> **Critical Failure** You make an unreliable judgement about the target. The GM may give you false information. 

#### Trained Actions
These actions can be performed by characters who are *Trained* in `=this.file.name`; they are not available to characters with lesser training.
> [!note] #####  First Aid (●)
> [[Manipulate]], [[Requirement\|Requires Tools]]
>- - -
> You attempt to perform first aid on a creature adjacent to you that is in a death spiral or [[Bleeding]]. If a creature is both in a death spiral and bleeding, you must choose which of these conditions you are attempting to treat. You can attempt to administer First Aid again to remedy the other effect, regardless of outcome.
> - **Stabilize the Dying**— Make a standard-difficulty **Medicine** check on a creature that is in a death spiral, with a difficulty penalty equal to two times the current stage of the spiral (-2 if stage 1, -4 if stage 2, etc..)
> - **Staunch Bleeding**— Make a standard-difficulty **Medicine** check on a [[Bleeding]] creature, with a difficulty penalty equal to the average value of the die of the creature’s Bleeding condition (for example, a -5 on a d10.) 
> 
> **Success** If you are attempting to stabilize , the target exits their death spiral, falling [[Unconscious]]at 0 Health. If you’re trying to staunch bleeding, the target immediately ends their [[Bleeding]] condition.
> **Critical Failure** If you were trying to stabilize a dying creature, the target advances their death spiral by one stage. If you were attempting to staunch bleeding, the target immediately takes its current Bleeding damage.

^47b51e

> [!note]+ ##### Treat Wounds 
>[[Exploration]], [[Healing]], [[Manipulate]], [[Requirement\|Requires Tools]]
>- - -
> You spend 10 minutes treating the injuries of one living creature (this can include yourself.) Creatures can only benefit from Treat Wounds once per hour (from any source.)
> 
> In order to treat wounds, make a standard-difficulty **Medicine** check on the creature, with a difficulty penalty given by your GM based on circumstance. If you’re an Expert, you can instead make a hard-difficulty check, and if you’re a Master, you can instead make a very hard-difficulty check. Finally, if you’re a Legend, you can make an impossible-difficulty check. 
> 
> **Critical Success** As success, but double the total healing
> **Success** The target regains Health based on the difficulty of the check. See the chart below. 
> **Critical Failure** The target takes 1d8 damage.
>
| Difficulty | Healing |
|:----------:|:-------:|
|    Easy    |  1d6+4  |
|    Hard    |  2d6+8  |
| Very Hard  | 3d6+16  |
| impossible | 4d6+32  |
>

> [!note]+ ##### Treat Poison ●
>[[Manipulate]]
>- - -
> You spend at least 8 hours caring for a diseased creature. Make a **Medicine** check with a difficulty of the poison’s difficulty rating. Afterwards, you cannot try again until after the creature’s next contest against the poison.
> 
> **Critical Success** You grant the creature a +4 circumstance bonus to its next check against the poison.
> **Success** You grant the creature a +2 circumstance bonus to its next check against the poison.
> **Critical Failure** You fail, your efforts causing the creature to suffer a -2 circumstance penalty to its next check against the poison.

#### Expert Actions
These actions can be performed by characters who are *Experts* in `=this.file.name`; they are not available to characters with lesser training.
> [!note] ##### Battlefield Reprieve ●●
>[[Healing]], [[Manipulate]], [[Requirement\|Requires Tools]]
>- - -
>  You can patch allies up, even in combat. You use Treat Wounds, and then the target becomes immune to your Battlefield Reprieve for 24 hours. This does *not* make them immune to Treat Wounds, however. 

> [!note]+ ##### Treat Disease
>[[Downtime]], [[Manipulate]]
>- - -
> You spend at least 8 hours caring for a diseased creature. Make a **Medicine** check with a difficulty of the disease’s difficulty rating. Afterwards, you cannot try again until after the creature’s next contest against the disease.
> 
> **Critical Success** You grant the creature a +4 circumstance bonus to its next check against the disease.
> **Success** You grant the creature a +2 circumstance bonus to its next check against the disease.
> **Critical Failure** You fail, your efforts causing the creature to suffer a -2 circumstance penalty to its next check against the disease.

#### Master Actions
These actions can be performed by characters who are *Masters* in `=this.file.name`; they are not available to characters with lesser training.
> [!note] ##### Resuscitation ●●
>[[Healing]], [[Manipulate]], [[Requirement\|Requires Tools]]
>- - -
>You attempt to resuscitate the recently deceased. Make a very hard-difficult **Medicine** check against a dead creature that has been dead for no longer than 1 minute. On a success, the target returns to life, [[Unconscious]] with 1 Health.

- - -
# Perks
>> [!info|text-Center clear]+ Trained Perk: Ward Healer
>> *When you become Trained in `=this.file.name`, if you have aptitude in it, you gain the following benefits.*
>> You are accustomed giving round-the-clock care to multiple patients. When you use Treat Disease or Treat Wounds, you can treat up to two targets, four if you’re a Master in Medicine, and eight if you’re a Legend in it.
>> 
>> Additionally, as long as you succeed, your patients become immune to Treat Wounds for only 10 minutes instead of 1 hour. 

>> [!info|text-Center clear]+ Expertise Perk: Laws of Leyless Healing
>> *When you become an Expert in `=this.file.name`, if you have aptitude in it, you gain the following benefits.*
>> You follow the Laws of Leyless Healing, which mandates one heal only through physical, non-magical means. 
>> 
>> Increase the die size of all non-magical healing you receive and give by one step, but decrease the die size of all magical healing you receive and give by one step as well. 
>> 
>> Additionally, targets of your Battlefield Reprieve become temporarily immune for only 1 hour, instead of one day.  

>> [!info|text-Center clear]+ Masterful Perk: Embrace Mortality
>> *When you become a Master in `=this.file.name`, if you have aptitude in it, you gain the following benefits.*
>> You do your best work when your patient is untainted by magical healing. If the target of your Treat Wounds has not received magical healing within the last 24 hours, any success you make is a critical success instead.

>> [!info|text-Center clear]+ Legendary Perk: 
>> *When you become a Legend in `=this.file.name`, if you have aptitude in it, you gain the following benefits.*
>> 