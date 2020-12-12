---
title: Player:ReviveRefused
---

> **Player:ReviveRefused**(player: [Player](/vext/ref/server/type/player))

## Description 

- Gets fired each time a player refuses a revive (or gets killed before accepting the revive).

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |

## Example

```lua
Events:Subscribe('Player:ReviveRefused', function(player)
    -- Do stuff here.
end)
```
