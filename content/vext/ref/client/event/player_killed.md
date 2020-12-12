---
title: Player:Killed
---

> **Player:Killed**(player: [Player](/vext/ref/client/type/player))

## Reasons
- Revive time is over and so player is save dead

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/client/type/player) |  |

## Example

```lua
Events:Subscribe('Player:Killed', function(player)
    -- Do stuff here.
end)
```
