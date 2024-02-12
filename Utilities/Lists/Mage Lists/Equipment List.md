---
tags: [list]
---
# Weaponry List
```dataview
TABLE type AS Type, category AS Category, row.group AS Group, damage_die AS "Damage Die", damage_type as "Damage Type"
FROM #Weapon
SORT category OR row.group ASC 
```
# Armor List
```dataview
TABLE category AS "Category", row.group AS Group, toughness_bonus AS "Toughness Bonus", check_penalty AS "Check Penalty"
FROM #Armor
```
# General Equipment
```dataview
LIST rows.file.link
FROM #Equipment
SORT completed ASC
GROUP BY type
```