---
title: Player:SuppressedEnemy
---

> **Player:SuppressedEnemy**(player: [Player](/vext/ref/server/type/player), enemy: [Player](/vext/ref/server/type/player))

## Description 

- Gets fired each time a player suppressed an enemy.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |
| **enemy** | [Player](/vext/ref/server/type/player) |  |

## Example

```lua
Events:Subscribe('Player:SuppressedEnemy', function(player, enemy)
    -- Do stuff here.
end)
```
