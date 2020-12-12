---
title: Vehicle:SpawnDone
---

> **Vehicle:SpawnDone**(vehicle: [Entity](/vext/ref/shared/type/entity))

## Description 

- Gets fired each time a vehicle spawns.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **vehicle** | [Entity](/vext/ref/shared/type/entity) |  |

## Example

```lua
Events:Subscribe('Vehicle:SpawnDone', function(vehicle)
    -- Do stuff here.
end)
```
