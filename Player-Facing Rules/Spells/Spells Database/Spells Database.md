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
    sortIndex: -1
    isSorted: false
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
    position: 6
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
  School:
    input: select
    accessorKey: School
    key: School
    id: School
    label: School
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: 0
    isSorted: true
    isSortedDesc: false
    options:
      - { label: "Aerophasia", value: "Aerophasia", color: "hsl(253, 95%, 90%)"}
      - { label: "Hydrophasia", value: "Hydrophasia", color: "hsl(36, 95%, 90%)"}
      - { label: "Terraphasia", value: "Terraphasia", color: "hsl(267, 95%, 90%)"}
      - { label: "Pyrophasia", value: "Pyrophasia", color: "hsl(149, 95%, 90%)"}
      - { label: "Technosophy", value: "Technosophy", color: "hsl(185, 95%, 90%)"}
      - { label: "Runeurgy", value: "Runeurgy", color: "hsl(50, 95%, 90%)"}
      - { label: "Somaphoresis", value: "Somaphoresis", color: "hsl(211, 95%, 90%)"}
      - { label: "Hemaphoresis", value: "Hemaphoresis", color: "hsl(309, 95%, 90%)"}
      - { label: "Glyphiamancy", value: "Glyphiamancy", color: "hsl(137, 95%, 90%)"}
      - { label: "Metallomancy", value: "Metallomancy", color: "hsl(278, 95%, 90%)"}
      - { label: "Electromancy", value: "Electromancy", color: "hsl(16, 95%, 90%)"}
      - { label: "Resonancia", value: "Resonancia", color: "hsl(97, 95%, 90%)"}
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
  Rank:
    input: text
    accessorKey: Rank
    key: Rank
    id: Rank
    label: Rank
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: 1
    isSorted: true
    isSortedDesc: false
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
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
      - { label: "Spell", value: "Spell", color: "hsl(139, 95%, 90%)"}
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
    id: Completed?
    label: Completed
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: 3
    isSorted: true
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
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: true
  group_folder_column: School
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
  current_row_template: Templates/Markdown Templates/Mage Templates/Spell Template.md
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