---
title: Player:SetSquadLeader
---

> **Player:SetSquadLeader**(player: [Player](/vext/ref/client/type/player))

## Description

- Fired everytime a new squadleader is assigned

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/client/type/player) |  |

## Example

```lua
Events:Subscribe('Player:SetSquadLeader', function(player)
    -- Do stuff here.
end)
```
