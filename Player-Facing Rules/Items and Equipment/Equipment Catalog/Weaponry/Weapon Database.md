---
database-plugin: basic
tags:
  - database
---

```yaml:dbfolder
name: Weapon Database
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
  Tags:
    input: tags
    accessorKey: Tags
    key: Tags
    id: Tags
    label: Tags
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Weapon", value: "Weapon", color: "hsl(355, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Type:
    input: select
    accessorKey: Type
    key: Type
    id: Type
    label: Type
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: 1
    isSorted: true
    isSortedDesc: false
    options:
      - { label: "Melee", value: "Melee", color: "hsl(0,91%,48%)"}
      - { label: "Ranged", value: "Ranged", color: "hsl(96,100%,45%)"}
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
  Group:
    input: select
    accessorKey: Group
    key: Group
    id: Group
    label: Group
    position: 7
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Brawling", value: "Brawling", color: "hsl(229, 95%, 90%)"}
      - { label: "Long Guns", value: "Long Guns", color: "hsl(210, 95%, 90%)"}
      - { label: "Bows", value: "Bows", color: "hsl(88, 95%, 90%)"}
      - { label: "Daggers", value: "Daggers", color: "hsl(256, 95%, 90%)"}
      - { label: "Sword", value: "Sword", color: "hsl(179, 95%, 90%)"}
      - { label: "Axe", value: "Axe", color: "hsl(189, 95%, 90%)"}
      - { label: "Handguns", value: "Handguns", color: "hsl(291, 95%, 90%)"}
      - { label: "Spell", value: "Spell", color: "hsl(339, 95%, 90%)"}
      - { label: "Unsorted", value: "Unsorted", color: "hsl(115, 95%, 90%)"}
      - { label: "Tome", value: "Tome", color: "hsl(156, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Category:
    input: select
    accessorKey: Category
    key: Category
    id: Category
    label: Category
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: 2
    isSorted: true
    isSortedDesc: true
    options:
      - { label: "Simple", value: "Simple", color: "hsl(214, 95%, 90%)"}
      - { label: "Martial", value: "Martial", color: "hsl(227, 95%, 90%)"}
      - { label: "Advanced", value: "Advanced", color: "hsl(253, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
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
    position: 13
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
    position: 12
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
  Handed-ness:
    input: number
    accessorKey: Handed-ness
    key: Handed-ness
    id: Handed-ness
    label: Handed-ness
    position: 8
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
  Heft:
    input: number
    accessorKey: Heft
    key: Heft
    id: Heft
    label: Heft
    position: 11
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
  Price:
    input: number
    accessorKey: Price
    key: Price
    id: Price
    label: Price
    position: 4
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
  Damage_Type:
    input: select
    accessorKey: Damage_Type
    key: Damage_Type
    id: Damage_Type
    label: Damage Type
    position: 10
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "crushing", value: "crushing", color: "hsl(256, 95%, 90%)"}
      - { label: "fire", value: "fire", color: "hsl(12, 95%, 90%)"}
      - { label: "electric", value: "electric", color: "hsl(178, 95%, 90%)"}
      - { label: "piercing", value: "piercing", color: "hsl(231, 95%, 90%)"}
      - { label: "cutting", value: "cutting", color: "hsl(327, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Damage_Die:
    input: select
    accessorKey: Damage_Die
    key: Damage_Die
    id: Damage
    label: Damage Die
    position: 9
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "1d4", value: "1d4", color: "hsl(0,0%,0%)"}
      - { label: "1d8", value: "1d8", color: "hsl(0,0%,0%)"}
      - { label: "1d6", value: "1d6", color: "hsl(0,0%,0%)"}
      - { label: "1d10", value: "1d10", color: "hsl(0,0%,0%)"}
      - { label: "1d12", value: "1d12", color: "hsl(0,0%,0%)"}
      - { label: "1", value: "1", color: "hsl(0,0%,0%)"}
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
  Completed:
    input: checkbox
    accessorKey: Completed
    key: Completed
    id: Completed
    label: Completed
    position: 3
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
      footer_type: percent_filled
      persist_changes: false
      footer_formula: 
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: true
  group_folder_column: Group
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
  current_row_template: Templates/Markdown Templates/Mage Templates/Weapon Template.md
  pagination_size: 10
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: true
  implementation: default
filters:
  enabled: false
  conditions:
```