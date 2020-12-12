---
title: Player:Destroyed
---

> **Player:Destroyed**(player: [Player](/vext/ref/server/type/player))

## Description 

- Gets fired each time a player is destroyed.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |

## Example

```lua
Events:Subscribe('Player:Destroyed', function(player)
    -- Do stuff here.
end)
```
