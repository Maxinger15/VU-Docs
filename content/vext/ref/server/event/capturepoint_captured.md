---
title: CapturePoint:Captured
---

> **CapturePoint:Captured**(capturePoint: [Entity](/vext/ref/shared/type/entity))

## Description

- Gets fired each time a capture point is captured.
- Entitytype: [CapturePointEntity](/vext/ref/server/type/capturepointentity)

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **capturePoint** | [Entity](/vext/ref/shared/type/entity) | |

## Example

```lua
Events:Subscribe('CapturePoint:Captured', function(capturePoint)
    -- Do stuff here.
end)
```
