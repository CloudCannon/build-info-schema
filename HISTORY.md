# 0.0.3

Made the keys consistently snake_case. Keys are only prefixed with an underscore if part
of the configuration cascade (mostly).

- Added `_inputs`
- Added `_editables`
- Removed `_options`
- Removed `_comments`
- Rename `_collection_groups` to `collection_groups`
- Rename `_array_structures` to `_structures`
- Rename `collections-config` to `collections_config`
- Rename `base-url` to `base_url`
- Rename `_editor` to `editor`
- Rename `_source_editor` to `source_editor`
- Rename `_sort_key` to `sort_key` inside `collections_config`
- Rename `_subtext_key` to `subtext_key` inside `collections_config`
- Rename `_image_key` to `image_key` inside `collections_config`
- Rename `_image_size` to `image_size` inside `collections_config`
- Rename `_singular_name` to `singular_name` inside `collections_config`
- Rename `_singular_key` to `singular_key` inside `collections_config`
- Rename `_disable_add` to `disable_add` inside `collections_config`
- Rename `_icon` to `icon` inside `collections_config`
- Rename `_add_options` to `add_options` inside `collections_config`
- Fixed `generator` schema

# 0.0.0 - 0.0.2

- Initial schema
