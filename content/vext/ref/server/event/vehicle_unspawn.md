---
title: Vehicle:Unspawn
---

> **Vehicle:Unspawn**(vehicle: [Entity](/vext/ref/shared/type/entity))

## Description 

- Gets fired each time a vehicle unspawns.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **vehicle** | [Entity](/vext/ref/shared/type/entity) |  |

## Example

```lua
Events:Subscribe('Vehicle:Unspawn', function(vehicle)
    -- Do stuff here.
end)
```
