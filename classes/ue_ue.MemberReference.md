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

#### Defined in

[ue/ue.d.ts:18808](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18808)

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

#### Defined in

[ue/ue.d.ts:18809](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18809)

## Properties

### MemberGuid

• **MemberGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:18813](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18813)

___

### MemberName

• **MemberName**: `string`

#### Defined in

[ue/ue.d.ts:18812](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18812)

___

### MemberParent

• **MemberParent**: [`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:18810](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18810)

___

### MemberScope

• **MemberScope**: `string`

#### Defined in

[ue/ue.d.ts:18811](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18811)

___

### \_\_tid\_MemberReference\_\_

• `Private` **\_\_tid\_MemberReference\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:18821](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18821)

___

### bSelfContext

• **bSelfContext**: `boolean`

#### Defined in

[ue/ue.d.ts:18814](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18814)

___

### bWasDeprecated

• **bWasDeprecated**: `boolean`

#### Defined in

[ue/ue.d.ts:18815](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18815)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:18819](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18819)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:18820](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18820)
