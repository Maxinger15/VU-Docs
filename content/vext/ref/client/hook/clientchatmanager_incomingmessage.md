---
title: ClientChatManager:IncomingMessage
---

> **ClientChatManager:IncomingMessage**(message: string, playerId: int, recipientMask: int, channelId: [ChatChannelType](/vext/ref/fb/chatchanneltype), isSenderDead: bool)

## Description

- Fired when the client gets a new message in the chat

## Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **message** | string |  |
| **playerId** | int |  |
| **recipientMask** | int |  |
| **channelId** | [ChatChannelType](/vext/ref/fb/chatchanneltype) |  |
| **isSenderDead** | bool |  |

## Example

```lua
Hooks:Install('ClientChatManager:IncomingMessage', 1, function(hook, message, playerId, recipientMask, channelId, isSenderDead)
    -- Do stuff here.
end)
```
