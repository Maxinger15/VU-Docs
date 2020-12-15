---
title: Input:PreUpdate
---

> **Input:PreUpdate**(cache: [ConceptCache](/vext/ref/client/type/conceptcache), deltaTime: float)

## Description

- Gives access to player based informations like if the player is running, shooting ect.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **cache** | [ConceptCache](/vext/ref/client/type/conceptcache) |  |
| **deltaTime** | float |  |

## Example

```lua
Hooks:Install('Input:PreUpdate', 1, function(hook, cache, deltaTime)
    -- Do stuff here.
end)
```
