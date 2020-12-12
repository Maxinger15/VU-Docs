---
title: Player:Left
---

> **Player:Left**(player: [Player](/vext/ref/server/type/player))

## Description 

- Gets fired each time a player left.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |

## Example

```lua
Events:Subscribe('Player:Left', function(player)
    -- Do stuff here.
end)
```
