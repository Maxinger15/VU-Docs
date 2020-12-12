---
title: Player:Joining
---

> **Player:Joining**(name: string, playerGuid: [Guid](/vext/ref/shared/type/guid), ipAddress: string, accountGuid: [Guid](/vext/ref/shared/type/guid))

## Description 

- Gets fired each time a player is joining.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **name** | string |  |
| **playerGuid** | [Guid](/vext/ref/shared/type/guid) |  |
| **ipAddress** | string |  |
| **accountGuid** | [Guid](/vext/ref/shared/type/guid) |  |

## Example

```lua
Events:Subscribe('Player:Joining', function(name, playerGuid, ipAddress, accountGuid)
    -- Do stuff here.
end)
```
