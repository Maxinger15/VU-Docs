---
title: Vehicle:Enter
---

> **Vehicle:Enter**(vehicle: [Entity](/vext/ref/shared/type/entity), player: [Player](/vext/ref/server/type/player))

## Description 

- Gets fired each time a player enters a vehicle.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **vehicle** | [Entity](/vext/ref/shared/type/entity) |  |
| **player** | [Player](/vext/ref/server/type/player) |  |

## Example

```lua
Events:Subscribe('Vehicle:Enter', function(vehicle, player)
    -- Do stuff here.
end)
```
