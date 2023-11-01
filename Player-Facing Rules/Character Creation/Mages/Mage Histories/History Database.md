---

database-plugin: basic
tags: database
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
    sortIndex: -1
    isSorted: false
    isSortedDesc: true
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
    position: 8
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
    position: 7
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
  Wealth:
    input: select
    accessorKey: Wealth
    key: Wealth
    id: Wealth
    label: Wealth
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: 0
    isSorted: true
    isSortedDesc: true
    options:
      - { label: "Poor", value: "Poor", color: "hsl(129, 95%, 90%)"}
      - { label: "Moderate", value: "Moderate", color: "hsl(129, 95%, 90%)"}
      - { label: "High", value: "High", color: "hsl(270, 95%, 90%)"}
      - { label: "Extreme", value: "Extreme", color: "hsl(226, 95%, 90%)"}
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
  Perk:
    input: text
    accessorKey: Perk
    key: Perk
    id: Perk
    label: Perk
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
  Boost:
    input: select
    accessorKey: Boost
    key: Boost
    id: Attribute
    label: Attribute
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Power", value: "Power", color: "hsl(260, 95%, 90%)"}
      - { label: "Body", value: "Body", color: "hsl(311, 95%, 90%)"}
      - { label: "Reflex", value: "Reflex", color: "hsl(252, 95%, 90%)"}
      - { label: "Mind", value: "Mind", color: "hsl(8, 95%, 90%)"}
      - { label: "Potential", value: "Potential", color: "hsl(203, 95%, 90%)"}
      - { label: "Tenacity", value: "Tenacity", color: "hsl(242, 95%, 90%)"}
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
  group_folder_column: Wealth
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
  row_templates_folder: Templates
  current_row_template: Templates/Markdown Templates/Mage Templates/History Template.md
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