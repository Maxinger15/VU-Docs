---
title: Soldier:Spawn
---

> **Soldier:Spawn**(soldier: [SoldierEntity](/vext/ref/client/type/soldierentity))

## Description

- Fired when the Player spawns

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **soldier** | [SoldierEntity](/vext/ref/client/type/soldierentity) |  |

## Example

```lua
Events:Subscribe('Soldier:Spawn', function(soldier)
    -- Do stuff here.
end)
```
