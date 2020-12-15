---
title: Client:UpdateInput
---

> **Client:UpdateInput**(deltaTime: float)

## Description

- Fired when the player object of the local user updates

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **deltaTime** | float |  |

## Example

```lua
Events:Subscribe('Client:UpdateInput', function(deltaTime)
    -- Do stuff here.
end)
```
