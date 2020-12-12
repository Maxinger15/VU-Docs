---
title: Player:ReviveAccepted
---

> **Player:ReviveAccepted**(player: [Player](/vext/ref/server/type/player), reviver: [Player](/vext/ref/server/type/player) \| nil)

## Description 

- Gets fired each time a player accepts a revive.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |
| **reviver** | [Player](/vext/ref/server/type/player) \| nil |  |

## Example

```lua
Events:Subscribe('Player:ReviveAccepted', function(player, reviver)
    -- Do stuff here.
end)
```
