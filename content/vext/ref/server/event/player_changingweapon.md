---
title: Player:ChangingWeapon
---

> **Player:ChangingWeapon**(player: [Player](/vext/ref/server/type/player))

## Description 

- Gets fired each time a player is changing the current active weapon slot.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |

## Example

```lua
Events:Subscribe('Player:ChangingWeapon', function(player)
    -- Do stuff here.
end)
```
