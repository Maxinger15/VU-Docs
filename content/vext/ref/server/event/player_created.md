---
title: Player:Created
---

> **Player:Created**(player: [Player](/vext/ref/server/type/player))

## Description 

- Gets fired each time a player is created.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |

## Example

```lua
Events:Subscribe('Player:Created', function(player)
    -- Do stuff here.
end)
```
