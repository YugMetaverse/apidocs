[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MemberReference

# Class: MemberReference

[ue/ue](../modules/ue_ue.md).MemberReference

## Table of contents

### Constructors

- [constructor](ue_ue.MemberReference.md#constructor)

### Properties

- [MemberGuid](ue_ue.MemberReference.md#memberguid)
- [MemberName](ue_ue.MemberReference.md#membername)
- [MemberParent](ue_ue.MemberReference.md#memberparent)
- [MemberScope](ue_ue.MemberReference.md#memberscope)
- [\_\_tid\_MemberReference\_\_](ue_ue.MemberReference.md#__tid_memberreference__)
- [bSelfContext](ue_ue.MemberReference.md#bselfcontext)
- [bWasDeprecated](ue_ue.MemberReference.md#bwasdeprecated)

### Methods

- [StaticClass](ue_ue.MemberReference.md#staticclass)
- [StaticStruct](ue_ue.MemberReference.md#staticstruct)

## Constructors

### constructor

• **new MemberReference**()

• **new MemberReference**(`MemberParent`, `MemberScope`, `MemberName`, `MemberGuid`, `bSelfContext`, `bWasDeprecated`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MemberParent` | [`Object`](ue_ue.Object.md) |
| `MemberScope` | `string` |
| `MemberName` | `string` |
| `MemberGuid` | [`Guid`](ue_ue_s.Guid.md) |
| `bSelfContext` | `boolean` |
| `bWasDeprecated` | `boolean` |

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

### MemberScope

• **MemberScope**: `string`

___

### \_\_tid\_MemberReference\_\_

• `Private` **\_\_tid\_MemberReference\_\_**: `boolean`

___

### bSelfContext

• **bSelfContext**: `boolean`

___

### bWasDeprecated

• **bWasDeprecated**: `boolean`

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
