---
title: Player:EnteredCapturePoint
---

> **Player:EnteredCapturePoint**(player: [Player](/vext/ref/server/type/player), capturePoint: [Entity](/vext/ref/shared/type/entity))

## Description 

- Gets fired each time a player enters a capture point area.
- Entitytype: [CapturePointEntity](/vext/ref/server/type/capturepointentity)

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |
| **capturePoint** | [Entity](/vext/ref/shared/type/entity) |  |

## Example

```lua
Events:Subscribe('Player:EnteredCapturePoint', function(player, capturePoint)
    -- Do stuff here.
end)
```
