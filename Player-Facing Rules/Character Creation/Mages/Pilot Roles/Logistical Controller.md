---
cssclasses:
  - dashboard
newColumn3:
  - Role
Attribute: Mind
Armor: Mobile
Armor_Training: Trained
Weapon_Degree: Martial
Weapon_Type: Melee
Weapon_Training: Expert
Skill: Meta-Magic
Skill_1: Artifice
Skill_2: Meta-Magic
Spec_1: Engineer
Spell_1: "[[Auto-Shot Turret]]"
Spec_2: Disruptor
Spell_2: "[[Arcane Surge]]"
---
# Role: `=this.file.name`
Logistical Controllers do just that: control the pace of the battle, lest it be by locking down key points or locking foes out of their most powerful abilities.
- - -
>[!info] ### `=this.file.name` Role Mechanics
> **Attribute Boost:** `=this.Attribute`
> **Armor Proficiency :** `=this.Armor` (`=this.Armor_Training`)
> **Weapon Proficiency:** `=this.Weapon_Degree` `=this.Weapon_Type` (`=this.Weapon_Training`)
> **Role Skill:** `=link(this.Skill)`

## When you select  this Role,  select  a  Specialization. 
>[!column]+ ***Role Specialization : `=this.Spec_1`*** 
>>[!info] ### `=this.Spec_1` Mechanics
>Engineer Controllers create minions and other constructs to control the pace of encounters.
> **Specialty Skill:** `=link(this.Skill_1)`
> **Starting Spell:** `=this.Spell_1`
> 
>> [!metadata] *Trained Perk: Construct Spell-Origination Disjunction*
>> *When you become Trained in this Role, you gain the following benefits.*
>> You can treat Constructs you summon as the origin point of spells you cast for the purposes of range and line of sight. Additionally, allies within 12 spaces of you gain a +1 magical bonus to Move, while enemies suffer a -1 magical penalty to Move.
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
>Disruptor Controllers attack the enemies directly in order to lock them out of their most powerful abilities. 
> **Specialty Skill:** `=link(this.Skill_2)`
> **Starting Spell:** `=this.Spell_2`
> 
>> [!metadata] *Trained Perk: Electro-Neural Dissipation*
>> *When you become Trained in this Role, you gain the following benefits.*
>> Shocked enemies have a -2 to rolls against any of your spells or effects that require a **Mind** check. Additionally, allies within 12 spaces of you gain a +1 magical bonus to Move, while enemies suffer a -1 magical penalty to Move.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this Role, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this Rolel, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this Role, you gain the following benefits.*