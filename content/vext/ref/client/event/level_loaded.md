---
title: Level:Loaded
---

> **Level:Loaded**(levelName: string, gameMode: string)

## Reasons
- All relevant partitions and assets loaded
## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **levelName** | string |  |
| **gameMode** | string |  |

## Example

```lua
Events:Subscribe('Level:Loaded', function(levelName, gameMode)
    -- Do stuff here.
end)
```
