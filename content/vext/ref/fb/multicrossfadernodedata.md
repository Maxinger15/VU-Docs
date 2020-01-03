---
title: MultiCrossfaderNodeData
---
### Base Classes

[AudioGraphNodeData](AudioGraphNodeData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                        | Description                                                                                                                           |
| ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| MultiCrossfaderNodeData()                                                          | Create a new instance of this container type.                                                                                         |
| MultiCrossfaderNodeData(MultiCrossfaderNodeData other)                             | Create a reference copy of an instance of the same type.                                                                              |
| MultiCrossfaderNodeData([AudioGraphNodeData](AudioGraphNodeData) other)            | Upcast an instance of type [AudioGraphNodeData](AudioGraphNodeData) to [MultiCrossfaderNodeData](MultiCrossfaderNodeData).            |
| MultiCrossfaderNodeData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [MultiCrossfaderNodeData](MultiCrossfaderNodeData). |

## Properties

| Name             | Type                                             | Description |
| ---------------- | ------------------------------------------------ | ----------- |
| crossfaderGroups | [MultiCrossfaderGroup](MultiCrossfaderGroup)\[\] |             |
| start            | [AudioGraphNodePort](AudioGraphNodePort)         |             |
| stop             | [AudioGraphNodePort](AudioGraphNodePort)         |             |
| control          | [AudioGraphNodePort](AudioGraphNodePort)         |             |
| lockControlValue | bool                                             |             |

## Methods

| Type                                               | Name            | Parameters                                     |
| -------------------------------------------------- | --------------- | ---------------------------------------------- |
| [MultiCrossfaderNodeData](MultiCrossfaderNodeData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [MultiCrossfaderNodeData](MultiCrossfaderNodeData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |