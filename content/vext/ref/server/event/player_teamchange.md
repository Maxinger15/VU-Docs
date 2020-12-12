---
title: Player:TeamChange
---

> **Player:TeamChange**(player: [Player](/vext/ref/server/type/player), team: [TeamId](/vext/ref/fb/teamid), squad: [SquadId](/vext/ref/fb/squadid))

## Description 

- Gets fired each time a player changes the team.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |
| **team** | [TeamId](/vext/ref/fb/teamid) |  |
| **squad** | [SquadId](/vext/ref/fb/squadid) |  |

## Example

```lua
Events:Subscribe('Player:TeamChange', function(player, team, squad)
    -- Do stuff here.
end)
```
