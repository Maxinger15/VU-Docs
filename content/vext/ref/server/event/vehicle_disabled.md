---
title: Vehicle:Disabled
---

> **Vehicle:Disabled**(vehicle: [Entity](/vext/ref/shared/type/entity))

## Description 

- Gets fired each time a vehicle gets disabled.
- Entitytype: VehicleEntity ([ControllableEntity](/vext/ref/server/controllableentity))

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **vehicle** | [Entity](/vext/ref/shared/type/entity) |  |

## Example

```lua
Events:Subscribe('Vehicle:Disabled', function(vehicle)
    -- Do stuff here.
end)
```
