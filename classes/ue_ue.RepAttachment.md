[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / RepAttachment

# Class: RepAttachment

[ue/ue](../modules/ue_ue.md).RepAttachment

## Table of contents

### Constructors

- [constructor](ue_ue.RepAttachment.md#constructor)

### Properties

- [AttachComponent](ue_ue.RepAttachment.md#attachcomponent)
- [AttachParent](ue_ue.RepAttachment.md#attachparent)
- [AttachSocket](ue_ue.RepAttachment.md#attachsocket)
- [LocationOffset](ue_ue.RepAttachment.md#locationoffset)
- [RelativeScale3D](ue_ue.RepAttachment.md#relativescale3d)
- [RotationOffset](ue_ue.RepAttachment.md#rotationoffset)
- [\_\_tid\_RepAttachment\_\_](ue_ue.RepAttachment.md#__tid_repattachment__)

### Methods

- [StaticClass](ue_ue.RepAttachment.md#staticclass)
- [StaticStruct](ue_ue.RepAttachment.md#staticstruct)

## Constructors

### constructor

• **new RepAttachment**()

• **new RepAttachment**(`AttachParent`, `LocationOffset`, `RelativeScale3D`, `RotationOffset`, `AttachSocket`, `AttachComponent`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `AttachParent` | [`Actor`](ue_ue.Actor.md) |
| `LocationOffset` | [`Vector_NetQuantize100`](ue_ue.Vector_NetQuantize100.md) |
| `RelativeScale3D` | [`Vector_NetQuantize100`](ue_ue.Vector_NetQuantize100.md) |
| `RotationOffset` | [`Rotator`](ue_ue_s.Rotator.md) |
| `AttachSocket` | `string` |
| `AttachComponent` | [`SceneComponent`](ue_ue.SceneComponent.md) |

## Properties

### AttachComponent

• **AttachComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

___

### AttachParent

• **AttachParent**: [`Actor`](ue_ue.Actor.md)

___

### AttachSocket

• **AttachSocket**: `string`

___

### LocationOffset

• **LocationOffset**: [`Vector_NetQuantize100`](ue_ue.Vector_NetQuantize100.md)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector_NetQuantize100`](ue_ue.Vector_NetQuantize100.md)

___

### RotationOffset

• **RotationOffset**: [`Rotator`](ue_ue_s.Rotator.md)

___

### \_\_tid\_RepAttachment\_\_

• `Private` **\_\_tid\_RepAttachment\_\_**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
