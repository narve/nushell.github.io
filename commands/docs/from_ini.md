---
title: from ini
categories: |
  formats
version: 0.84.0
formats: |
  Parse text as .ini and create table.
usage: |
  Parse text as .ini and create table.
---

# <code>{{ $frontmatter.title }}</code> for formats

<div class='command-title'>{{ $frontmatter.formats }}</div>

## Signature

```> from ini ```


## Input/output types:

| input  | output |
| ------ | ------ |
| string | record |

## Examples

Converts ini formatted string to record
```shell
> '[foo]
a=1
b=2' | from ini
╭─────┬───────────╮
│     │ ╭───┬───╮ │
│ foo │ │ a │ 1 │ │
│     │ │ b │ 2 │ │
│     │ ╰───┴───╯ │
╰─────┴───────────╯
```
