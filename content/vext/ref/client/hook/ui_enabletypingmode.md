---
title: UI:EnableTypingMode
---

> **UI:EnableTypingMode**(enable: bool)

## Description

- Triggered when the keyboard input should be recognized as text

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **enable** | bool |  |

## Example

```lua
Hooks:Install('UI:EnableTypingMode', 1, function(hook, enable)
    -- Do stuff here.
end)
```
