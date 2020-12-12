---
title: Player:Respawn
---

> **Player:Respawn**(player: [Player](/vext/ref/client/type/player))

## Action
- Player respawns
## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/client/type/player) |  |

## Example

```lua
Events:Subscribe('Player:Respawn', function(player)
    -- Do stuff here.
end)
```
