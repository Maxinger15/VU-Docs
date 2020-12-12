---
title: Level:Loaded
---

> **Level:Loaded**(levelName: string, gameMode: string, round: int, roundsPerMap: int)

## Description

- Gets fired each time a Level is loaded.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **levelName** | string |  |
| **gameMode** | string |  |
| **round** | int |  |
| **roundsPerMap** | int |  |

## Example

```lua
Events:Subscribe('Level:Loaded', function(levelName, gameMode, round, roundsPerMap)
    -- Do stuff here.
end)
```
