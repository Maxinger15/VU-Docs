---
title: Player:KitPickup
---

> **Player:KitPickup**(player: [Player](/vext/ref/server/type/player), newCustomization: [DataContainer](/vext/ref/shared/type/datacontainer))

## Description 

- Gets fired each time a player picks a kit up.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |
| **newCustomization** | [DataContainer](/vext/ref/shared/type/datacontainer) |  |

## Example

```lua
Events:Subscribe('Player:KitPickup', function(player, newCustomization)
    -- Do stuff here.
end)
```
