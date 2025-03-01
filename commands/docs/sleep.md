---
title: sleep
categories: |
  platform
version: 0.84.0
platform: |
  Delay for a specified amount of time.
usage: |
  Delay for a specified amount of time.
---

# <code>{{ $frontmatter.title }}</code> for platform

<div class='command-title'>{{ $frontmatter.platform }}</div>

## Signature

```> sleep (duration) ...rest```

## Parameters

 -  `duration`: time to sleep
 -  `...rest`: additional time


## Input/output types:

| input   | output  |
| ------- | ------- |
| nothing | nothing |

## Examples

Sleep for 1sec
```shell
> sleep 1sec

```

Sleep for 3sec
```shell
> sleep 1sec 1sec 1sec

```

Send output after 1sec
```shell
> sleep 1sec; echo done

```
