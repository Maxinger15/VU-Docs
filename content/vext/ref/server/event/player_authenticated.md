---
title: Player:Authenticated
---

> **Player:Authenticated**(player: [Player](/vext/ref/server/type/player))

## Description 

- Gets fired each time a player is authenticated after joining.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |

## Example

```lua
Events:Subscribe('Player:Authenticated', function(player)
    -- Do stuff here.
end)
```
