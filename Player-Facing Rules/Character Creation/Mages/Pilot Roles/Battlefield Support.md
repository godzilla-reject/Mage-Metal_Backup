---
cssclasses:
  - dashboard
newColumn3:
  - Role
Attribute: Any
Armor: Infiltrator
Armor_Training: Trained
Weapon_Degree: Simple
Weapon_Type: Ranged
Weapon_Training: Expert
Skill: Arcanology
Skill_1: Medicine
Spell_1: "[[Patch-Up]]"
Skill_2: Mundocraft
Spell_2: "[[Eunard's Portable Cover]]"
Spec_1: Medical
Spec_2: Barricadier
---
# Role: `=this.file.name`
Supports use buffs and healing to help allies survive the battle, as well as deal more damage. 
- - -
>[!info] ### `=this.file.name` Role Mechanics
> **Attribute Boost:** `=this.Attribute`
> **Armor Proficiency :** `=this.Armor` (`=this.Armor_Training`)
> **Weapon Proficiency:** `=this.Weapon_Degree` `=this.Weapon_Type` (`=this.Weapon_Training`)
> **Role Skill:** `=link(this.Skill)`

## When you select  this Role,  select  a  Specialization. 
>[!column]+ ***Role Specialization : `=this.Spec_1`*** 
>>[!info] ### `=this.Spec_1` Mechanics
>Medical Supports specialize in healing and repair on the battlefield. 
> **Specialty Skill:** `=link(this.Skill_1)`
> **Starting Spell:** `=this.Spell_1`
> 
>> [!metadata] *Trained Perk: Resplendent Life*
>> *When you become Trained in this Role, you gain the following benefits.*
>> You gain a +3 magical bonus to healing you do to allies who are [[Bloodied]]. Additionally, you can pay for up to half of an ally's spell's mana cost. Doing so costs your reaction. 
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this Role, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this Rolel, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this Role, you gain the following benefits.*

OR

>[!column]+ ***Role Specialization : `=this.Spec_2`*** 
>>[!info|left] ### `=this.Spec_2` Mechanics
>>Barricadier Supports generate cover and utilize perfect positioning to create advantageous situations for their allies.  
> **Specialty Skill:** `=link(this.Skill_2)`
> **Starting Spell:** `=this.Spell_2`
> 
>> [!metadata] *Trained Perk: Reinforced Constructs*
>> *When you become Trained in this Role, you gain the following benefits.*
>> Constructs you create (such as via spells with the [[Construct]] trait) gain a +2 bonus to Toughness and cannot be pierced. Additionally, you can pay for up to half of an ally's spell's mana cost. Doing so costs your reaction. 
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this Role, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this Rolel, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this Role, you gain the following benefits.*