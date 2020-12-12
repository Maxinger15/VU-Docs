---
title: Player:KickedFromSquad
---

> **Player:KickedFromSquad**(player: [Player](/vext/ref/server/type/player), squad: [SquadId](/vext/ref/fb/squadid))

## Description 

- Gets fired each time a player is kicked from squad.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |
| **squad** | [SquadId](/vext/ref/fb/squadid) |  |

## Example

```lua
Events:Subscribe('Player:KickedFromSquad', function(player, squad)
    -- Do stuff here.
end)
```
