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
    position: 10
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
  Attribute:
    input: select
    accessorKey: Attribute
    key: Attribute
    id: Attribute
    label: Attribute
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Any", value: "Any", color: "hsl(85, 95%, 90%)"}
      - { label: "Reflex", value: "Reflex", color: "hsl(293, 95%, 90%)"}
      - { label: "Power", value: "Power", color: "hsl(181, 95%, 90%)"}
      - { label: "Body", value: "Body", color: "hsl(140, 95%, 90%)"}
      - { label: "Mind", value: "Mind", color: "hsl(174, 95%, 90%)"}
      - { label: "Potential", value: "Potential", color: "hsl(220, 95%, 90%)"}
      - { label: "Tenacity", value: "Tenacity", color: "hsl(318, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Option1:
    input: text
    accessorKey: Option1
    key: Option1
    id: Option1
    label: Option1
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
  Option2:
    input: text
    accessorKey: Option2
    key: Option2
    id: Option2
    label: Option2
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
  Option3:
    input: text
    accessorKey: Option3
    key: Option3
    id: Option3
    label: Option3
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
  Category:
    input: select
    accessorKey: Category
    key: Category
    id: Category
    label: Category
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Solar_Hegemony", value: "Solar_Hegemony", color: "hsl(291, 95%, 90%)"}
      - { label: "Andromedian_Federation", value: "Andromedian_Federation", color: "hsl(336, 95%, 90%)"}
      - { label: "Outer_Banks_Empire", value: "Outer_Banks_Empire", color: "hsl(65, 95%, 90%)"}
      - { label: "Beneficial", value: "Beneficial", color: "hsl(264, 95%, 90%)"}
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
  Size:
    input: number
    accessorKey: Size
    key: Size
    id: Size
    label: Size
    position: 5
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
      footer_type: none
      persist_changes: false
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: true
  group_folder_column: Category
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
  current_row_template: Templates/Markdown Templates/Mage Templates/Species Template.md
  pagination_size: 10
  font_size: 16
  enable_js_formulas: true
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