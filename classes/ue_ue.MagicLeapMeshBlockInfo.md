[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MagicLeapMeshBlockInfo

# Class: MagicLeapMeshBlockInfo

[ue/ue](../modules/ue_ue.md).MagicLeapMeshBlockInfo

## Table of contents

### Constructors

- [constructor](ue_ue.MagicLeapMeshBlockInfo.md#constructor)

### Properties

- [BlockDimensions](ue_ue.MagicLeapMeshBlockInfo.md#blockdimensions)
- [BlockID](ue_ue.MagicLeapMeshBlockInfo.md#blockid)
- [BlockOrientation](ue_ue.MagicLeapMeshBlockInfo.md#blockorientation)
- [BlockPosition](ue_ue.MagicLeapMeshBlockInfo.md#blockposition)
- [BlockState](ue_ue.MagicLeapMeshBlockInfo.md#blockstate)
- [Timestamp](ue_ue.MagicLeapMeshBlockInfo.md#timestamp)
- [\_\_tid\_MagicLeapMeshBlockInfo\_\_](ue_ue.MagicLeapMeshBlockInfo.md#__tid_magicleapmeshblockinfo__)

### Methods

- [StaticClass](ue_ue.MagicLeapMeshBlockInfo.md#staticclass)
- [StaticStruct](ue_ue.MagicLeapMeshBlockInfo.md#staticstruct)

## Constructors

### constructor

• **new MagicLeapMeshBlockInfo**()

• **new MagicLeapMeshBlockInfo**(`BlockID`, `BlockPosition`, `BlockOrientation`, `BlockDimensions`, `Timestamp`, `BlockState`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BlockID` | [`Guid`](ue_ue_s.Guid.md) |
| `BlockPosition` | [`Vector`](ue_ue_s.Vector.md) |
| `BlockOrientation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `BlockDimensions` | [`Vector`](ue_ue_s.Vector.md) |
| `Timestamp` | [`Timespan`](ue_ue.Timespan.md) |
| `BlockState` | [`EMagicLeapMeshState`](../enums/ue_ue.EMagicLeapMeshState.md) |

## Properties

### BlockDimensions

• **BlockDimensions**: [`Vector`](ue_ue_s.Vector.md)

___

### BlockID

• **BlockID**: [`Guid`](ue_ue_s.Guid.md)

___

### BlockOrientation

• **BlockOrientation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### BlockPosition

• **BlockPosition**: [`Vector`](ue_ue_s.Vector.md)

___

### BlockState

• **BlockState**: [`EMagicLeapMeshState`](../enums/ue_ue.EMagicLeapMeshState.md)

___

### Timestamp

• **Timestamp**: [`Timespan`](ue_ue.Timespan.md)

___

### \_\_tid\_MagicLeapMeshBlockInfo\_\_

• `Private` **\_\_tid\_MagicLeapMeshBlockInfo\_\_**: `boolean`

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
