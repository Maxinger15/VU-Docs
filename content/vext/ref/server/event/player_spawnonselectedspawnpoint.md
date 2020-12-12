---
title: Player:SpawnOnSelectedSpawnPoint
---

> **Player:SpawnOnSelectedSpawnPoint**(player: [Player](/vext/ref/server/type/player))

## Description 

- Gets fired each time a player spawns on a selected spawn point.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |

## Example

```lua
Events:Subscribe('Player:SpawnOnSelectedSpawnPoint', function(player)
    -- Do stuff here.
end)
```
