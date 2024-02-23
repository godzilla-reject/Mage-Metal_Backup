---
cssclasses:
  - dashboard
Attribute: Body
Armor: Power
Armor_Training: Expert
Weapon_Degree: Simple
Weapon_Type: Melee
Weapon_Training: Trained
Skill: Athletics
Spec_1: Bastion
Skill_1: Initimidation
Spell_1: "[[Shield Crush]]"
Spec_2: Juggernaut
Skill_2: Athletics
Spell_2: "[[Blood Cry]]"
Tags:
  - Role
---
# Role: `=this.file.name`
The Vanguards take to the frontlines, using their extreme defenses to tank damage, make distance, and create chances for their allies.
- - -
>[!info] ### `=this.file.name` Role Mechanics
> **Attribute Boost:** `=this.Attribute`
> **Armor Proficiency :** `=this.Armor` (`=this.Armor_Training`)
> 
> **Weapon Proficiency:** `=this.Weapon_Degree` `=this.Weapon_Type` (`=this.Weapon_Training`)
> 
> **Role Skill:** `=link(this.Skill)`

## When you select  this Role,  select  a  Specialization. 
>[!column]+ ***Role Specialization : `=this.Spec_1`*** 
>>[!info] ### `=this.Spec_1` Mechanics
>Bastions are the living shield of their groups, using massive armor and powerful shields to stop damage before it ever has the chance to wound them and their allies. 
> **Specialty Skill:** `=link(this.Skill_1)`
> **Starting Spell:** `=this.Spell_1`
> 
>> [!metadata] *Trained Perk: Living Shield*
>> *When you become Trained in this Role, you gain the following benefits.*
>> You gain resistance to physical damage. Additionally, you roll with favor against any check that would move you by force with favor.
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
>Juggernauts are beacons of light in the dark of the battlefield; using powerful war-cries, these front-liners burn their own life to stoke the fires of their allies. 
> **Specialty Skill:** `=link(this.Skill_2)`
> **Starting Spell:** `=this.Spell_2`
> 
>> [!metadata] *Trained Perk: Unyielding*
>> *When you become Trained in this Role, you gain the following benefits.*
>> You gain an additional 5 Health at character creation, and any time you would increase your max Health, you gain an additional +3 Health. Additionally, you roll with favor against any check that would move you by force.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this Role, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this Rolel, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this Role, you gain the following benefits.*