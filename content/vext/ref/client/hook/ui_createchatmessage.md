---
title: UI:CreateChatMessage
---

> **UI:CreateChatMessage**(message: string, channelId: [ChatChannelType](/vext/ref/fb/chatchanneltype), playerId: int, recipientMask: int, isSenderDead: bool)

## Description

- Access to a new chat message.


## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **message** | string |  |
| **channelId** | [ChatChannelType](/vext/ref/fb/chatchanneltype) |  |
| **playerId** | int |  |
| **recipientMask** | int |  |
| **isSenderDead** | bool |  |

## Example

```lua
Hooks:Install('UI:CreateChatMessage', 1, function(hook, message, channelId, playerId, recipientMask, isSenderDead)
    -- Do stuff here.
end)
```
