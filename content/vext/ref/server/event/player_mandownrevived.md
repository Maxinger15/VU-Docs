---
title: Player:ManDownRevived
---

> **Player:ManDownRevived**(player: [Player](/vext/ref/server/type/player), reviver: [Player](/vext/ref/server/type/player) \| nil, isAdrenalineRevive: bool)

## Description 

- Gets fired each time a player is in an interactiveManDown state and gets revived.
- Default revive style for Coop. Doesn't get fired in default multiplayer.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |
| **reviver** | [Player](/vext/ref/server/type/player) \| nil |  |
| **isAdrenalineRevive** | bool |  |

## Example

```lua
Events:Subscribe('Player:ManDownRevived', function(player, reviver, isAdrenalineRevive)
    -- Do stuff here.
end)
```
