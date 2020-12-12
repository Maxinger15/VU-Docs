---
title: Player:Resupply
---

> **Player:Resupply**(player: [Player](/vext/ref/server/type/player), givenMagsCount: int, supplier: [Player](/vext/ref/server/type/player) \| nil)

## Description 

- Gets fired each time a player gets resupply.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |
| **givenMagsCount** | int |  |
| **supplier** | [Player](/vext/ref/server/type/player) \| nil |  |

## Example

```lua
Events:Subscribe('Player:Resupply', function(player, givenMagsCount, supplier)
    -- Do stuff here.
end)
```
