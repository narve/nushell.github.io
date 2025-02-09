---
title: dfr to-arrow
categories: |
  dataframe
version: 0.84.0
dataframe: |
  Saves dataframe to arrow file.
usage: |
  Saves dataframe to arrow file.
---

# <code>{{ $frontmatter.title }}</code> for dataframe

<div class='command-title'>{{ $frontmatter.dataframe }}</div>

## Signature

```> dfr to-arrow (file)```

## Parameters

 -  `file`: file path to save dataframe


## Input/output types:

| input | output |
| ----- | ------ |
| any   | any    |

## Examples

Saves dataframe to arrow file
```shell
> [[a b]; [1 2] [3 4]] | dfr into-df | dfr to-arrow test.arrow

```


**Tips:** Dataframe commands were not shipped in the official binaries by default, you have to build it with `--features=dataframe` flag