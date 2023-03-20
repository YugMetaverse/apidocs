[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SimpleMemberReference

# Class: SimpleMemberReference

[ue/ue](../modules/ue_ue.md).SimpleMemberReference

## Table of contents

### Constructors

- [constructor](ue_ue.SimpleMemberReference.md#constructor)

### Properties

- [MemberGuid](ue_ue.SimpleMemberReference.md#memberguid)
- [MemberName](ue_ue.SimpleMemberReference.md#membername)
- [MemberParent](ue_ue.SimpleMemberReference.md#memberparent)
- [\_\_tid\_SimpleMemberReference\_\_](ue_ue.SimpleMemberReference.md#__tid_simplememberreference__)

### Methods

- [StaticClass](ue_ue.SimpleMemberReference.md#staticclass)
- [StaticStruct](ue_ue.SimpleMemberReference.md#staticstruct)

## Constructors

### constructor

• **new SimpleMemberReference**()

• **new SimpleMemberReference**(`MemberParent`, `MemberName`, `MemberGuid`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MemberParent` | [`Object`](ue_ue.Object.md) |
| `MemberName` | `string` |
| `MemberGuid` | [`Guid`](ue_ue_s.Guid.md) |

## Properties

### MemberGuid

• **MemberGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### MemberName

• **MemberName**: `string`

___

### MemberParent

• **MemberParent**: [`Object`](ue_ue.Object.md)

___

### \_\_tid\_SimpleMemberReference\_\_

• `Private` **\_\_tid\_SimpleMemberReference\_\_**: `boolean`

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
