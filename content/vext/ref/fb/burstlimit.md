---
title: BurstLimit
---

## Summary

### Constructors

|  |
| --- |
| **[BurstLimit](#constructor-0)**() |
| **[BurstLimit](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "min" >}} | int |
| {{< prop "max" >}} | int |

### Methods

| Method | Returns |
| ------ | ------- |
| **[Clone](#clone)**() | [BurstLimit](/vext/ref/fb/burstlimit) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "BurstLimit" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### BurstLimit {#constructor-0}

> **BurstLimit**()

Creates a new [BurstLimit](/vext/ref/fb/burstlimit) frostbite instance.

### BurstLimit {#constructor-1}

> **BurstLimit**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [BurstLimit](/vext/ref/fb/burstlimit) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

## Properties

### {{% prop-heading "min" %}}

> **int**

### {{% prop-heading "max" %}}

> **int**

## Methods

### Clone {#clone}

> **Clone**(): [BurstLimit](/vext/ref/fb/burstlimit)

Creates a shallow-copy clone of this structure, which is essentially the equivalent of creating a new structure of the same type and assigning the values of this structure to all of its properties. Any properties that contain structure types (eg. [Vec3](/vext/ref/shared/type/vec3)) will be cloned when assigning, while properties that contain instance types (eg. [DataContainer](/vext/ref/shared/type/datacontainer)) will be referencing the same instance.

#### Returns

| Type | Description |
| ---- | ----------- |
| **[BurstLimit](/vext/ref/fb/burstlimit)** | The newly created structure. |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [BurstLimit](/vext/ref/fb/burstlimit) type.

