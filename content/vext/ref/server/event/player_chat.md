---
title: Player:Chat
---

> **Player:Chat**(player: [Player](/vext/ref/server/type/player), recipientMask: int, message: string)

## Description 

- Gets fired each time a player is sending a message in chat.

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **player** | [Player](/vext/ref/server/type/player) |  |
| **recipientMask** | int |  |
| **message** | string |  |

## Example

```lua
Events:Subscribe('Player:Chat', function(player, recipientMask, message)
    -- Do stuff here.
end)
```
