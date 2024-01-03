---
Armor: Mobile
Mounts: Primary, Aux
Computation: 4
Engineering: 2
Structure: 1
Tags:
  - Shell
---
# `=this.file.name` Shell 
***Requirements:*** *[[Logistical Controller]] Pilot Role*

In order to control the pace of battle, the Wire Runner shell employs a powerful lock-out subroutine.

>[!info] ## Mechanics 
|                   |                     |
|:-----------------:|:-------------------:|
|  **Armor Type**   |    `=this.Armor`    |
| **Weapon Mounts** |   `=this.Mounts`    |
|   *Attributes*    |                     |
|   **Structure**   |  `=this.Structure`  |
|  **Engineering**  | `=this.Engineering` |
|  **Computation**  | `=this.Computation` |

>[!column]+ ***Intrinsic and Intrinsic Upgrades*** 
> 
>> [!metadata] *Basic Intrinsic:* Weapon Mount Lock-Out Sub-Routine `=[[Dev Helpers]].one-action`
>> *This is the Shell's Intrinsic Ability*
>> 
>> 
>> *Frequency: Once Per Round*
>> - - -
>>Select a Metal within Sensors range, then make a [[Hacking]] contest against their **Computation**. On a success, the next time they take the Attack action, you select which mount they fire from. On a failure, you instead select one of their mounts. They cannot use the selected mount until the end of your next turn. 
>
>> [!metadata] *Advanced Enhancement*
>> *When this part is upgraded to Advanced, your Metal's Intrinsic Ability gains this enhancement.*
>
>> [!metadata] *Ethereal Enhancement*
>>*When this part is upgraded to Ethereal, your Metal's Intrinsic Ability gains this enhancement.*
>
>> [!metadata] *Divine Enhancement*
>>*When this part is upgraded to Divine, your Metal's Intrinsic Ability gains this enhancement.*