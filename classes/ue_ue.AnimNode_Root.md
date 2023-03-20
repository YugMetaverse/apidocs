[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_Root

# Class: AnimNode\_Root

[ue/ue](../modules/ue_ue.md).AnimNode_Root

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_Root`**

  ↳↳ [`AnimNode_StateResult`](ue_ue.AnimNode_StateResult.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_Root.md#constructor)

### Properties

- [Group](ue_ue.AnimNode_Root.md#group)
- [Name](ue_ue.AnimNode_Root.md#name)
- [Result](ue_ue.AnimNode_Root.md#result)
- [\_\_tid\_AnimNode\_Root\_\_](ue_ue.AnimNode_Root.md#__tid_animnode_root__)

### Methods

- [StaticClass](ue_ue.AnimNode_Root.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_Root.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_Root**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

• **new AnimNode_Root**(`Result`, `Name`, `Group`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Result` | [`PoseLink`](ue_ue.PoseLink.md) |
| `Name` | `string` |
| `Group` | `string` |

#### Overrides

UE.AnimNode\_Base.constructor

## Properties

### Group

• **Group**: `string`

___

### Name

• **Name**: `string`

___

### Result

• **Result**: [`PoseLink`](ue_ue.PoseLink.md)

___

### \_\_tid\_AnimNode\_Root\_\_

• `Private` **\_\_tid\_AnimNode\_Root\_\_**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticClass](ue_ue.AnimNode_Base.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)
