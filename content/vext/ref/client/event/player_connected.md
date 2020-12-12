---
title: Player:Connected
---

> **Player:Connected**(player: [Player](/vext/ref/client/type/player))
## Reasons
- Player connected to the server
- Server is leaving pre-round and reloads the match
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
