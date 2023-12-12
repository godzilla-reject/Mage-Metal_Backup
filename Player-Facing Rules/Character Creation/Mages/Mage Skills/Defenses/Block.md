---
Category: Defenses
Attribute: Power
Tags:
  - Skills
Completed: true
---
# Skill Description-`=this.file.name`
Notes:
- Cannot be used against Ranged attacks (until Master, and then still has high penalties.)
- Want to encourage Dodging for ranged, Blocking for melee, and Pain-Tol for both.

This skill is a measure of how good one can wield a shield, block attacks, and parry oncoming blows. 
>[!info| clear no-i] `=this.file.name` Mechanics
>**Category** | `=this.Category`   
>**Attribute**| `=this.Attribute`
- - -
# Skill Actions
#### Untrained Actions
These actions can be performed without any training in `=this.file.name `; they are available to any character. 
> [!note]+ ##### Raise Shield ●
>
>- - -
>  ***Limit:*** You have a shield equipped. 
>  You engage the barrier of your shield. While your shield is Raised, you gain the stacking equipment bonus to Toughness listed in the shield's Protection. Your shield remains raised until its barrier is depleted or the end of your next turn. 
^7506d9

> [!note]+ ##### Shield Block ◌
>
>- - -
>  ***Limit:*** Your shield is Raised.
>  ***Trigger:*** You are targeted with a melee attack that does not deal **true** damage  
>  You put your shield in the way of an attack, blocking the damage. Your shield prevents an amount of damage equal to its Protection, and then takes the remainder of the damage (adjusted by its Resistances). If there is any damage remaining, the shield is deactivated and you take that damage. 

^c76e50

#### Trained Actions
These actions can be performed by characters who are *Trained* in `=this.file.name`; they are not available to characters with lesser training.
> [!note]+ ##### Parry ○
>
>- - -
>  ***Limit:*** Your shield is Raised; or, you have a melee weapon with the [[Parrying]] trait.
>  ***Trigger:*** You are targeted with a melee attack that does not deal **true** damage.
>  You swing your shield against the direction of the triggering melee attack, attempting to deflect it. Make a **Block** check, with a -5 penalty if you have already attempted a Parry this turn. On a success, you deflect the blow, taking no damage. On a failure, you block the attack as normal, and on a critical failure, you fail to block the attack, taking damage as normal. 

^8affcc

#### Expert Actions
These actions can be performed by characters who are *Experts* in `=this.file.name`; they are not available to characters with lesser training.
> [!note]+ ##### Reactive Shielding ◌
>
>- - -
> ***Limit:*** You have a shield equipped. 
> ***Trigger:*** You are targeted with a melee attack that does not deal **true** damage.
> You reflexively snap your shield up and into place to block an attack. You immediately [[Block#^7506d9\|Raise Shield]] and then [[Block#^c76e50\|Shield Block]] against the triggering attack. 

> [!note]+ ##### Riposte ◌
>
>- - -
> ***Trigger:*** You successfully [[Block#^8affcc\|Parry]] a melee attack.
> You use the opportunity gained by parrying to inflict a devastating blow. Make a melee attack against the creature you Parried, rolling damage twice and taking the higher of the two results. 

- - -
# Perks
>> [!info|text-Center clear]+ Trained Perk: Steel-Clad Defender
>> *When you become Trained in `=this.file.name`, if you have aptitude in it, you gain the following benefits.*
>> 
>> Increase the Protection value of shields you wield by 2, and increase their Barrier value by 6.

>> [!info|text-Center clear]+ Expertise Perk: Rapid Recharger
>> *When you become an Expert in `=this.file.name`, if you have aptitude in it, you gain the following benefits.*
>> 
>> Increase the Protection value of shields you wield by 1, and increase their Barrier value by 3. Additionally, lower the number of actions required to Recharge the shields you wield by 1 action. 

>> [!info|text-Center clear]+ Masterful Perk: Flycatcher
>> *When you become a Master in `=this.file.name`, if you have aptitude in it, you gain the following benefits.*
>> 
>> Increase the Protection value of shields you wield by 1, and increase their Barrier value by 3. Additionally, you have learned to swat projectiles out of air. You can now use Block skill actions against ranged attacks as well, with a -6 penalty. 

>> [!info|text-Center clear]+ Legendary Perk: Unbreakable Defender
>> *When you become a Legend in `=this.file.name`, if you have aptitude in it, you gain the following benefits.*
>> 
>> Increase the Protection value of shields you wield by 1, and increase their Barrier value by 3. Additionally, shields you wield become immune to **Physical** damage, and Resistant to two other damage types of your choice (it cannot be **true**.)