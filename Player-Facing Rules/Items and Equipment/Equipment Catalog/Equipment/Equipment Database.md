---
database-plugin: basic
tags:
  - database
---

```yaml:dbfolder
name: new database
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
    sortIndex: 1
    isSorted: true
    isSortedDesc: false
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
    position: 9
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
    position: 8
    isHidden: false
    sortIndex: -1
    isSorted: false
    isSortedDesc: true
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Completed:
    input: checkbox
    accessorKey: Completed
    key: Completed
    id: Completed
    label: Completed
    position: 2
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
  Heft:
    input: number
    accessorKey: Heft
    key: Heft
    id: Heft
    label: Heft
    position: 7
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
  Tier:
    input: number
    accessorKey: Tier
    key: Tier
    id: Tier
    label: Tier
    position: 6
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
  Type:
    input: select
    accessorKey: Type
    key: Type
    id: Type
    label: Type
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: -1
    isSorted: false
    isSortedDesc: false
    options:
      - { label: "Adventuring", value: "Adventuring", color: "hsl(132, 95%, 90%)"}
      - { label: "Consumable", value: "Consumable", color: "hsl(21, 95%, 90%)"}
      - { label: "Ammunition", value: "Ammunition", color: "hsl(140, 95%, 90%)"}
      - { label: "Utility", value: "Utility", color: "hsl(96, 95%, 90%)"}
      - { label: "Storage", value: "Storage", color: "hsl(91, 95%, 90%)"}
      - { label: "Clothing", value: "Clothing", color: "hsl(324, 95%, 90%)"}
      - { label: "Cybernetic", value: "Cybernetic", color: "hsl(195, 95%, 90%)"}
      - { label: "Maginetic", value: "Maginetic", color: "hsl(119, 95%, 90%)"}
      - { label: "Software", value: "Software", color: "hsl(78, 95%, 90%)"}
      - { label: "Computer", value: "Computer", color: "hsl(238, 95%, 90%)"}
      - { label: "Kit", value: "Kit", color: "hsl(27, 95%, 90%)"}
      - { label: "Shield", value: "Shield", color: "hsl(151, 95%, 90%)"}
      - { label: "Traversal", value: "Traversal", color: "hsl(214, 95%, 90%)"}
      - { label: "Catalyst", value: "Catalyst", color: "hsl(318, 95%, 90%)"}
      - { label: "Resonator", value: "Resonator", color: "hsl(338, 95%, 90%)"}
      - { label: "Grimoire", value: "Grimoire", color: "hsl(100, 95%, 90%)"}
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
  Tags:
    input: tags
    accessorKey: Tags
    key: Tags
    id: Tags
    label: Tags
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Equipment", value: "Equipment", color: "hsl(13, 95%, 90%)"}
      - { label: "reword", value: "reword", color: "hsl(76, 95%, 90%)"}
      - { label: "rename", value: "rename", color: "hsl(213, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: true
  group_folder_column: Type
  remove_empty_folders: true
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
  current_row_template: Templates/Markdown Templates/Mage Templates/New Equipment Template.md
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