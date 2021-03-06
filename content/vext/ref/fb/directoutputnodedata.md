---
title: DirectOutputNodeData
---

Inherits from [OutputNodeData](/vext/ref/fb/outputnodedata)

## Summary

### Constructors

|  |
| --- |
| **[DirectOutputNodeData](#constructor-0)**() |
| **[DirectOutputNodeData](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[DirectOutputNodeData](#constructor-2)**(other: [OutputNodeData](/vext/ref/fb/outputnodedata)) |
| **[DirectOutputNodeData](#constructor-3)**(other: [AudioGraphNodeData](/vext/ref/fb/audiographnodedata)) |
| **[DirectOutputNodeData](#constructor-4)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "DirectOutputNodeData" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### DirectOutputNodeData {#constructor-0}

> **DirectOutputNodeData**()

Creates a new [DirectOutputNodeData](/vext/ref/fb/directoutputnodedata) frostbite instance.

### DirectOutputNodeData {#constructor-1}

> **DirectOutputNodeData**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [DirectOutputNodeData](/vext/ref/fb/directoutputnodedata) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### DirectOutputNodeData {#constructor-2}

> **DirectOutputNodeData**(other: [OutputNodeData](/vext/ref/fb/outputnodedata))

Casts an instance of type [OutputNodeData](/vext/ref/fb/outputnodedata) to [DirectOutputNodeData](/vext/ref/fb/directoutputnodedata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [OutputNodeData](/vext/ref/fb/outputnodedata) | The instance to cast to [DirectOutputNodeData](/vext/ref/fb/directoutputnodedata). |

### DirectOutputNodeData {#constructor-3}

> **DirectOutputNodeData**(other: [AudioGraphNodeData](/vext/ref/fb/audiographnodedata))

Casts an instance of type [AudioGraphNodeData](/vext/ref/fb/audiographnodedata) to [DirectOutputNodeData](/vext/ref/fb/directoutputnodedata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [AudioGraphNodeData](/vext/ref/fb/audiographnodedata) | The instance to cast to [DirectOutputNodeData](/vext/ref/fb/directoutputnodedata). |

### DirectOutputNodeData {#constructor-4}

> **DirectOutputNodeData**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [DirectOutputNodeData](/vext/ref/fb/directoutputnodedata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [DirectOutputNodeData](/vext/ref/fb/directoutputnodedata). |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [DirectOutputNodeData](/vext/ref/fb/directoutputnodedata) type.

