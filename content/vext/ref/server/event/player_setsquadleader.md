---
title: Player:SetSquadLeader
---

> **Player:SetSquadLeader**(player: [Player](/vext/ref/server/type/player))

## Description 

- Gets fired each time a player is set to squad leader.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |

## Example

```lua
Events:Subscribe('Player:SetSquadLeader', function(player)
    -- Do stuff here.
end)
```
