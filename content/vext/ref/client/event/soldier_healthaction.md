---
title: Soldier:HealthAction
---

> **Soldier:HealthAction**(soldier: [SoldierEntity](/vext/ref/client/type/soldierentity), action: [HealthStateAction](/vext/ref/shared/type/healthstateaction))

## Description

- Fired each time the player gets into a new health state [HealthStateAction](/vext/ref/shared/type/healthstateaction)

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **soldier** | [SoldierEntity](/vext/ref/client/type/soldierentity) |  |
| **action** | [HealthStateAction](/vext/ref/shared/type/healthstateaction) |  |

## Example

```lua
Events:Subscribe('Soldier:HealthAction', function(soldier, action)
    -- Do stuff here.
end)
```
