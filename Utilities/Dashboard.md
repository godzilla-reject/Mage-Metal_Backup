---
cssclasses:
  - dashboard
tags:
---
# To-Do List
---
```tasks
tags include todo
sort by priority
```

# Databases
- - -
```dataview

LIST rows.file.link

FROM #database

SORT file.name ASC

```
- - -
- ### Recent 
	- `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(4).file.link)`
- ### Stats
	- Notes:  `$=dv.pages().length`
---
- # Content Generation
	- ### General 
```button
name New Trait
type note(NewTrait, split) template
action Trait Template
templater true
color red
```
^button-NewTrait
```button
name New Condition
type note(NewCondition, split) template
action Condition Template
templater true
color red
```
^button-NewCondition