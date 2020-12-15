---
title: Player:Connected
---

> **Player:Connected**(player: [Player](/vext/ref/client/type/player))
## Description 

- Gets fired when a player connected to the server

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/client/type/player) |  |

## Example

```lua
Events:Subscribe('Player:Connected', function(player)
    -- Do stuff here.
end)
```
