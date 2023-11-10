---
cssclasses:
  - dashboard
newColumn3:
  - Role
Attribute: Unsorted
Armor: 
Armor_Training:
Weapon_Degree:
Weapon_Type:
Weapon_Training:
Skill:
Skill_1:
Spell_1:
Skill_2:
Spell_2:
Spec_1:
Spec_2:
---
# Role: `=this.file.name`

- - -
>[!info] ### `=this.file.name` Role Mechanics
> **Attribute Boost:** `=this.Attribute`
> **Armor Proficiency :** `=this.Armor` (`=this.Armor_Training`)
> **Weapon Proficiency:** `=this.Weapon_Degree` `=this.Weapon_Type` (`=this.Weapon_Training`)
> **Role Skill:** `=link(this.Skill)`

## When you select  this Role,  select  a  Specialization. 
>[!column]+ ***Role Specialization : `=this.Spec_1`*** 
>>[!info] ### `=this.Spec_1` Mechanics
> **Specialty Skill:** `=link(this.Skill_1)`
> **Starting Spell:** `=this.Spell_1`
> 
>> [!metadata] *Trained Perk:*
>> *When you become Trained in this Role, you gain the following benefits.*
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
> **Specialty Skill:** `=link(this.Skill_2)`
> **Starting Spell:** `=this.Spell_2`
> 
>> [!metadata] *Trained Perk:*
>> *When you become Trained in this Role, you gain the following benefits.*
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this Role, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this Rolel, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this Role, you gain the following benefits.*