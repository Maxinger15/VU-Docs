---
title: UI:CreateAction
---

> **UI:CreateAction**(action: [UIAction](/vext/ref/shared/type/uiaction))

## Description

- Gives access to the [UIActions](/vext/ref/shared/type/uiaction)

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **action** | [UIAction](/vext/ref/shared/type/uiaction) |  |

## Example

```lua
Hooks:Install('UI:CreateAction', 1, function(hook, action)
    -- Do stuff here.
end)
```
