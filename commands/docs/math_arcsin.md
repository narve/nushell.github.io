---
title: math arcsin
categories: |
  math
version: 0.84.0
math: |
  Returns the arcsine of the number.
usage: |
  Returns the arcsine of the number.
---

# <code>{{ $frontmatter.title }}</code> for math

<div class='command-title'>{{ $frontmatter.math }}</div>

## Signature

```> math arcsin --degrees```

## Parameters

 -  `--degrees` `(-d)`: Return degrees instead of radians


## Input/output types:

| input        | output       |
| ------------ | ------------ |
| list\<number\> | list\<number\> |
| number       | number       |
## Examples

Get the arcsine of 1
```shell
> 1 | math arcsin
1.5707963267948966
```

Get the arcsine of 1 in degrees
```shell
> 1 | math arcsin -d
90
```


**Tips:** Command `math arcsin` was not included in the official binaries by default, you have to build it with `--features=extra` flag