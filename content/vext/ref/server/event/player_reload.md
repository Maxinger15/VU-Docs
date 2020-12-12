---
title: Player:Reload
---

> **Player:Reload**(player: [Player](/vext/ref/server/type/player), weaponName: string, position: [Vec3](/vext/ref/shared/type/vec3))

## Description 

- Gets fired each time a player is reloading.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |
| **weaponName** | string |  |
| **position** | [Vec3](/vext/ref/shared/type/vec3) |  |

## Example

```lua
Events:Subscribe('Player:Reload', function(player, weaponName, position)
    -- Do stuff here.
end)
```
