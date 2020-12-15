---
title: Player:Respawn
---

> **Player:Respawn**(player: [Player](/vext/ref/client/type/player))

## Description

- Fired when the Player spawns

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
