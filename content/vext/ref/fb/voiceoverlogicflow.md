---
title: VoiceOverLogicFlow
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                   | Description                                                                                                                 |
| ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| VoiceOverLogicFlow()                                                          | Create a new instance of this container type.                                                                               |
| VoiceOverLogicFlow(VoiceOverLogicFlow other)                                  | Create a reference copy of an instance of the same type.                                                                    |
| VoiceOverLogicFlow([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [VoiceOverLogicFlow](VoiceOverLogicFlow). |

## Properties

| Name   | Type                                         | Description |
| ------ | -------------------------------------------- | ----------- |
| name   | string                                       |             |
| group  | [VoiceOverGroup](VoiceOverGroup)             |             |
| locals | [VoiceOverValue](VoiceOverValue)\[\]         |             |
| roots  | [VoiceOverEventNode](VoiceOverEventNode)\[\] |             |

## Methods

| Type                                     | Name            | Parameters                                     |
| ---------------------------------------- | --------------- | ---------------------------------------------- |
| [VoiceOverLogicFlow](VoiceOverLogicFlow) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [VoiceOverLogicFlow](VoiceOverLogicFlow) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |