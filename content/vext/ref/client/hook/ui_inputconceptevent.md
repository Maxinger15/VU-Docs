---
title: UI:InputConceptEvent
---

> **UI:InputConceptEvent**(eventType: [UIInputActionEventType](/vext/ref/fb/uiinputactioneventtype), action: [UIInputAction](/vext/ref/fb/uiinputaction))

## Description

- Triggered everytime a key state is changed. 
- Not for all keys available.
- Mostly for inputs for UI interactions.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **eventType** | [UIInputActionEventType](/vext/ref/fb/uiinputactioneventtype) |  |
| **action** | [UIInputAction](/vext/ref/fb/uiinputaction) |  |

## Example

```lua
Hooks:Install('UI:InputConceptEvent', 1, function(hook, eventType, action)
    -- Do stuff here.
end)
```
