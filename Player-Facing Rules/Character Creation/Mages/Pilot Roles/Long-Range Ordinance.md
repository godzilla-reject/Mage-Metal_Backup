---
cssclasses:
  - dashboard
newColumn3:
  - Role
Attribute: Reflex
Armor: Infiltrator
Armor_Training: Trained
Weapon_Degree: Advanced
Weapon_Type: Ranged
Weapon_Training: Trained
Spec_1: Sniper
Spec_2: Heavy Artillery
Spell_1: "[[Sniper's Mark]]"
Spell_2: "[[Cedrik's Mini-Many-Minefield]]"
Skill: Stealth
Skill_1: Stealth
Skill_2: Acrobatics
---
# Role: `=this.file.name`
Those in the Long-Range Ordinance role act as the heavy firepower of their team, either shutting down key chokes or unleashing devastating damage with high-powered weaponry. While powerful, they are nearly defenseless due to the amount of accommodation needed for such extreme firepower.
- - -
>[!info] ### `=this.file.name` Role Mechanics
> **Attribute Boost:** `=this.Attribute`
> **Armor Proficiency :** `=this.Armor` (`=this.Armor_Training`)
> **Weapon Proficiency:** `=this.Weapon_Degree` `=this.Weapon_Type` (`=this.Weapon_Training`)
> **Role Skill:** `link(this.Skill)`

## When you select  this Role,  select  a  Specialization. 
>[!column]+ ***Role Specialization : `=this.Spec_1`*** 
>>[!info] ### `=this.Spec_1` Mechanics
> Snipers are ingle-target annihilators; they hide and wait, allowing their teammates to set up the perfect kill-shot.
> **Specialty Skill:** `=this.Skill_1`
> **Starting Spell:** `=this.Spell_1`
> 
>> [!metadata] *Trained Perk: Critical Reload*
>> *When you become Trained in this Role, you gain the following benefits.*
>> Whenever you score a critical hit with a weapon you are trained in, you can reload that weapon as a free action. If it has any heat accumulated, you vent it off as part of this reload. Additionally, you ignore up to -4 in range penalties.
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
>Artillerists deliver high-yield payloads of powerful explosive magic and area-denying weaponry. If you need a chokepoint held, these are the pilots for you.
> **Specialty Skill:** `=this.Skill_2`
> **Starting Spell:** `=this.Spell_2`
> 
>> [!metadata] *Trained Perk: Delayed Payload Delivery*
>> *When you become Trained in this Role, you gain the following benefits.*
>> You can choose to delay the detonation of any spell or weapon you use with the [[Area]] trait by one round. When delayed this way, it deals an additional die of damage when it does detonate. Additionally, you ignore up to -4 in range penalties.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this Role, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this Rolel, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this Role, you gain the following benefits.*