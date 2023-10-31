---
cssclasses:
  - dashboard
Attribute: Power
newColumn3:
  - Role
Armor: Mobile
Armor_Training: Trained
Weapon_Degree: Martial
Weapon_Type: Ranged
Weapon_Training: Trained
Skill: Survivalism
Spec_1: Scout
Skill_1: Survivalism
Spell_1: "[[Retrace]]"
Spec_2: Hunter
Skill_2: Stealth
Spell_2: "[[Predator's Sight]]"
---
# Role: `=this.file.name`
Guerilla Specialists gather information, scout out battles, and recon for potential hostiles. Boasting good mobility, as well as evasion, Guerillas stay out of the fray to take others out with speed.
- - -
>[!info] ### `=this.file.name` Role Mechanics
> **Attribute Boost:** `=this.Attribute`
> **Armor Proficiency :** `=this.Armor` (`=this.Armor_Training`)
> **Weapon Proficiency:**  `=this.Weapon_Degree` `=this.Weapon_Type` (`=this.Weapon_Training`) *and* Simple Melee (Trained)
> **Role Skill:** `=link(this.Skill)`

## When you select  this Role,  select  a  Specialization. 
>[!column]+ ***Role Specialization : `=this.Spec_1`*** 
>>[!info] ### `=this.Spec_1` Mechanics
>Scouts get ahead of their allies, using information gathered from the shadows to help them line up the perfect ambush.
> **Specialty Skill:** `=link(this.Skill_1)`
> **Starting Spell:** `=this.Spell_1`
> 
>> [!metadata] *Trained Perk: Scouting Communications*
>> *When you become Trained in this Role, you gain the following benefits.*
>> You can double the range of any spell you cast with the [[Communication]] trait. Additionally, whenever you reduce a foes to 0 Health, you heal for a number of Health equal to your level.
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
>Hunters slink through the edge of the tree-line, taking out key targets with speed before the main engagement begins.
> **Specialty Skill:** `=link(this.Skill_2)`
> **Starting Spell:** `=this.Spell_2`
> 
>> [!metadata] *Trained Perk: Predation*
>> *When you become Trained in this Role, you gain the following benefits.*
>> You gain a +2 Space bonus to reach with any melee attack, as long you would lose the [[Hidden]] condition as apart of that attack. Additionally, whenever you reduce a foes to 0 Health, you heal for a number of Health equal to your level.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this Role, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this Rolel, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this Role, you gain the following benefits.*