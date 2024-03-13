---
Tier: 0
Heft: 1
Price: 0.5
Type: Ammunition
Completed: true
Tags:
  - Equipment
---
> [!infobox|left]+ Equipment Entry
> # `=this.file.name`
> ###### Equipment Information
|            |                               |
|:----------:|:-----------------------------:|
| **Price**  |       `=this.Price` un.       |
|  **Type**  |         `=this.Type`          |
|  **Tier**  |         `=this.Tier`          |
| **Usage**  | Loaded into a relevant weapon |
|  **Heft**  |       `=this.Heft` lbs        |
| **Traits** |               -               |
> ###### *Description*
> Laser weapons require batteries to function, and the colloquial name that has been adapted for these batteries is a "charge" due to holding enough power to discharge most weapons once. These small power cells come in packs of 12. 
> ##### Related Weapons
> ```dataview
> LIST 
> FROM [[]]
> WHERE file.name != "Equipment Appendix"
> SORT file.name ASC
> ```
