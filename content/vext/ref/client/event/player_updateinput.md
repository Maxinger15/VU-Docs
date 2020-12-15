---
title: Player:UpdateInput
---

> **Player:UpdateInput**(player: [Player](/vext/ref/client/type/player), deltaTime: float)

## Description

- Fired when a player object updates

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/client/type/player) |  |
| **deltaTime** | float |  |

## Example

```lua
Events:Subscribe('Player:UpdateInput', function(player, deltaTime)
    -- Do stuff here.
end)
```
