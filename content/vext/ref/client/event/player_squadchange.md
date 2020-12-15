---
title: Player:SquadChange
---

> **Player:SquadChange**(player: [Player](/vext/ref/client/type/player), squad: [SquadId](/vext/ref/fb/squadid))

## Description

- Fired when a player changed his squad

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/client/type/player) |  |
| **squad** | [SquadId](/vext/ref/fb/squadid) |  |

## Example

```lua
Events:Subscribe('Player:SquadChange', function(player, squad)
    -- Do stuff here.
end)
```
