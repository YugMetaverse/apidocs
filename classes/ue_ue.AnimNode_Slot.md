[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_Slot

# Class: AnimNode\_Slot

[ue/ue](../modules/ue_ue.md).AnimNode_Slot

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_Slot`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_Slot.md#constructor)

### Properties

- [SlotName](ue_ue.AnimNode_Slot.md#slotname)
- [Source](ue_ue.AnimNode_Slot.md#source)
- [\_\_tid\_AnimNode\_Slot\_\_](ue_ue.AnimNode_Slot.md#__tid_animnode_slot__)
- [bAlwaysUpdateSourcePose](ue_ue.AnimNode_Slot.md#balwaysupdatesourcepose)

### Methods

- [StaticClass](ue_ue.AnimNode_Slot.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_Slot.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_Slot**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

• **new AnimNode_Slot**(`Source`, `SlotName`, `bAlwaysUpdateSourcePose`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Source` | [`PoseLink`](ue_ue.PoseLink.md) |
| `SlotName` | `string` |
| `bAlwaysUpdateSourcePose` | `boolean` |

#### Overrides

UE.AnimNode\_Base.constructor

## Properties

### SlotName

• **SlotName**: `string`

___

### Source

• **Source**: [`PoseLink`](ue_ue.PoseLink.md)

___

### \_\_tid\_AnimNode\_Slot\_\_

• `Private` **\_\_tid\_AnimNode\_Slot\_\_**: `boolean`

___

### bAlwaysUpdateSourcePose

• **bAlwaysUpdateSourcePose**: `boolean`

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
