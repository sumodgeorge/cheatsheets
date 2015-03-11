---
title: Vim-Unite
layout: default
---

### Usage

    :Unite file
    :Unite file_rec/async:!
    :Unite tag
    :Unite buffer

### Sources

- `file/new`
- `file/async`
- `file_rec/async`
- `file_rec/git`
- `buffer`
- `buffer_tab` (current tab only)
- `tab`
- `register`
- `bookmark`
- `source`

### Options

- `-start-insert`
- `-no-quit`
- `-winheight=10`
- `-quick-match`   - select by pressing asdf keys
- `-winwidth=40`   - use with vertical
- `-no-split`      - open in current buffer
- `-auto-preview`  - great for outline
- `-vertical`      - open as sidebar
- `-here`          - in this buffer