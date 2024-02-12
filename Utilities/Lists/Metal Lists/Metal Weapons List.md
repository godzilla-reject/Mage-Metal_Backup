---
tags: [list]
---
```dataview
TABLE type AS Type, category AS Category, row.group AS Group, mount AS Mount, damage_die AS "Damage Die", damage_type AS "Damage Type" 
FROM #Metal AND #Weapon
SORT category DESC 
```