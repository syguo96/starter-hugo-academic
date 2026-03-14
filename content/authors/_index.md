---
cms_exclude: true

# ... existing fields like title, widget ...
widget: about
active: true

design:
  columns: '1'

# To publish author profile pages, remove all of the `_build` and `cascade` settings below.
_build:
  render: never
cascade:
  _build:
    render: never
    list: always
---
