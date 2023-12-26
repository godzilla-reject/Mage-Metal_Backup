---
database-plugin: basic
tags:
  - database
---

```yaml:dbfolder
name: Role Database
description: new description
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 1
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  __created__:
    key: __created__
    id: __created__
    input: metadata_time
    label: Created
    accessorKey: __created__
    isMetadata: true
    isDragDisabled: false
    skipPersist: false
    csvCandidate: true
    position: 17
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  __modified__:
    key: __modified__
    id: __modified__
    input: metadata_time
    label: Modified
    accessorKey: __modified__
    isMetadata: true
    isDragDisabled: false
    skipPersist: false
    csvCandidate: true
    position: 16
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  newColumn3:
    input: tags
    accessorKey: newColumn3
    key: newColumn3
    id: newColumn3
    label: Tags
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Role", value: "Role", color: "hsl(76, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Armor:
    input: select
    accessorKey: Armor
    key: Armor
    id: Armor
    label: Armor
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Infiltrator", value: "Infiltrator", color: "hsl(35,89%,33%)"}
      - { label: "Mobile", value: "Mobile", color: "hsl(113,75%,45%)"}
      - { label: "Power", value: "Power", color: "hsl(0,82%,47%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  Attribute:
    input: select
    accessorKey: Attribute
    key: Attribute
    id: Attribute
    label: Attribute
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Reflex", value: "Reflex", color: "hsl(138,100%,50%)"}
      - { label: "Power", value: "Power", color: "hsl(351,83%,45%)"}
      - { label: "Body", value: "Body", color: "hsl(32,80%,30%)"}
      - { label: "Any", value: "Any", color: "hsl(299, 95%, 90%)"}
      - { label: "Mind", value: "Mind", color: "hsl(6, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  Spec_1:
    input: text
    accessorKey: Spec_1
    key: Spec_1
    id: Spec_1
    label: Spec_1
    position: 10
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Spec_2:
    input: text
    accessorKey: Spec_2
    key: Spec_2
    id: Spec_2
    label: Spec_2
    position: 13
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Spell_1:
    input: text
    accessorKey: Spell_1
    key: Spell_1
    id: Spell_1
    label: Spell_1
    position: 12
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Spell_2:
    input: text
    accessorKey: Spell_2
    key: Spell_2
    id: Spell_2
    label: Spell_2
    position: 15
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Weapon_Degree:
    input: select
    accessorKey: Weapon_Degree
    key: Weapon_Degree
    id: Weapon_Degree
    label: Weapon_Degree
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Advanced", value: "Advanced", color: "hsl(351,100%,50%)"}
      - { label: "Martial", value: "Martial", color: "hsl(230,94%,48%)"}
      - { label: "Simple", value: "Simple", color: "hsl(142,83%,47%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  Weapon_Type:
    input: select
    accessorKey: Weapon_Type
    key: Weapon_Type
    id: Weapon_Type
    label: Weapon_Type
    position: 7
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Ranged", value: "Ranged", color: "hsl(108, 95%, 90%)"}
      - { label: "Melee", value: "Melee", color: "hsl(174, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Armor_Training:
    input: select
    accessorKey: Armor_Training
    key: Armor_Training
    id: Armor_Training
    label: Armor_Training
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Trained", value: "Trained", color: "hsl(0,0%,100%)"}
      - { label: "Expert", value: "Expert", color: "hsl(222, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  Weapon_Training:
    input: select
    accessorKey: Weapon_Training
    key: Weapon_Training
    id: Weapon_Training
    label: Weapon_Training
    position: 8
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Trained", value: "Trained", color: "hsl(154, 95%, 90%)"}
      - { label: "Expert", value: "Expert", color: "hsl(172, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Skill:
    input: select
    accessorKey: Skill
    key: Skill
    id: Skill_1
    label: Skill
    position: 9
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Stealth", value: "Stealth", color: "hsl(55, 95%, 90%)"}
      - { label: "Survivalism", value: "Survivalism", color: "hsl(343, 95%, 90%)"}
      - { label: "Athletics", value: "Athletics", color: "hsl(265, 95%, 90%)"}
      - { label: "Arcanology", value: "Arcanology", color: "hsl(208, 95%, 90%)"}
      - { label: "Meta-Magic", value: "Meta-Magic", color: "hsl(242, 95%, 90%)"}
      - { label: "Sneak", value: "Sneak", color: "hsl(85, 95%, 90%)"}
      - { label: "Sneakery", value: "Sneakery", color: "hsl(93, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  Skill_1:
    input: select
    accessorKey: Skill_1
    key: Skill_1
    id: Skill_2
    label: Skill_1
    position: 11
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Stealth", value: "Stealth", color: "hsl(75, 95%, 90%)"}
      - { label: "Survivalism", value: "Survivalism", color: "hsl(198, 95%, 90%)"}
      - { label: "Intimidation", value: "Intimidation", color: "hsl(272, 95%, 90%)"}
      - { label: "Initimidation", value: "Initimidation", color: "hsl(83, 95%, 90%)"}
      - { label: "Medicine", value: "Medicine", color: "hsl(227, 95%, 90%)"}
      - { label: "Artificing", value: "Artificing", color: "hsl(338, 95%, 90%)"}
      - { label: "Sneak", value: "Sneak", color: "hsl(216, 95%, 90%)"}
      - { label: "Artifice", value: "Artifice", color: "hsl(133, 95%, 90%)"}
      - { label: "Sneakery", value: "Sneakery", color: "hsl(188, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  Skill_2:
    input: select
    accessorKey: Skill_2
    key: Skill_2
    id: Skill_3
    label: Skill_2
    position: 14
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Acrobatics", value: "Acrobatics", color: "hsl(139, 95%, 90%)"}
      - { label: "Stealth", value: "Stealth", color: "hsl(347, 95%, 90%)"}
      - { label: "Athletics", value: "Athletics", color: "hsl(265, 95%, 90%)"}
      - { label: "Arcanology", value: "Arcanology", color: "hsl(188, 95%, 90%)"}
      - { label: "Mundocraft", value: "Mundocraft", color: "hsl(71, 95%, 90%)"}
      - { label: "Meta-Magic", value: "Meta-Magic", color: "hsl(13, 95%, 90%)"}
      - { label: "Sneak", value: "Sneak", color: "hsl(237, 95%, 90%)"}
      - { label: "Sneakery", value: "Sneakery", color: "hsl(44, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: true
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: true
  hoist_files_with_empty_attributes: true
  show_metadata_created: true
  show_metadata_modified: true
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: false
  source_data: current_folder
  source_form_result: 
  source_destination_path: /
  row_templates_folder: /
  current_row_template: Templates/Markdown Templates/Mage Templates/Pilot Role Template.md
  pagination_size: 10
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```