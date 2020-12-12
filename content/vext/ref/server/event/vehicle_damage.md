---
title: Vehicle:Damage
---

> **Vehicle:Damage**(vehicle: [Entity](/vext/ref/shared/type/entity), damage: float, info: [DamageGiverInfo](/vext/ref/server/type/damagegiverinfo) \| nil)

## Description 

- Gets fired each time a vehicle gets damaged.
- Entitytype: VehicleEntity ([ControllableEntity](/vext/ref/server/controllableentity))

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **vehicle** | [Entity](/vext/ref/shared/type/entity) |  |
| **damage** | float |  |
| **info** | [DamageGiverInfo](/vext/ref/server/type/damagegiverinfo) \| nil |  |

## Example

```lua
Events:Subscribe('Vehicle:Damage', function(vehicle, damage, info)
    -- Do stuff here.
end)
```
