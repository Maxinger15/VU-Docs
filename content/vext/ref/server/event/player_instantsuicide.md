---
title: Player:InstantSuicide
---

> **Player:InstantSuicide**(player: [Player](/vext/ref/server/type/player))

## Description 

- Gets fired each time a player suicides.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |

## Example

```lua
Events:Subscribe('Player:InstantSuicide', function(player)
    -- Do stuff here.
end)
```
