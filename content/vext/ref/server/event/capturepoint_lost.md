---
title: CapturePoint:Lost
---

> **CapturePoint:Lost**(capturePoint: [Entity](/vext/ref/shared/type/entity))

## Description

- Gets fired each time a capture point is lost/ neutralized.
- Entitytype: [CapturePointEntity](/vext/ref/server/type/capturepointentity)

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **capturePoint** | [Entity](/vext/ref/shared/type/entity) |  |

## Example

```lua
Events:Subscribe('CapturePoint:Lost', function(capturePoint)
    -- Do stuff here.
end)
```
