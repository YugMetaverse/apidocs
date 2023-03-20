[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_PoseSnapshot

# Class: AnimNode\_PoseSnapshot

[ue/ue](../modules/ue_ue.md).AnimNode_PoseSnapshot

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_PoseSnapshot`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_PoseSnapshot.md#constructor)

### Properties

- [Mode](ue_ue.AnimNode_PoseSnapshot.md#mode)
- [Snapshot](ue_ue.AnimNode_PoseSnapshot.md#snapshot)
- [SnapshotName](ue_ue.AnimNode_PoseSnapshot.md#snapshotname)
- [\_\_tid\_AnimNode\_PoseSnapshot\_\_](ue_ue.AnimNode_PoseSnapshot.md#__tid_animnode_posesnapshot__)

### Methods

- [StaticClass](ue_ue.AnimNode_PoseSnapshot.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_PoseSnapshot.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_PoseSnapshot**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

• **new AnimNode_PoseSnapshot**(`SnapshotName`, `Snapshot`, `Mode`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SnapshotName` | `string` |
| `Snapshot` | [`PoseSnapshot`](ue_ue.PoseSnapshot.md) |
| `Mode` | [`ESnapshotSourceMode`](../enums/ue_ue.ESnapshotSourceMode.md) |

#### Overrides

UE.AnimNode\_Base.constructor

## Properties

### Mode

• **Mode**: [`ESnapshotSourceMode`](../enums/ue_ue.ESnapshotSourceMode.md)

___

### Snapshot

• **Snapshot**: [`PoseSnapshot`](ue_ue.PoseSnapshot.md)

___

### SnapshotName

• **SnapshotName**: `string`

___

### \_\_tid\_AnimNode\_PoseSnapshot\_\_

• `Private` **\_\_tid\_AnimNode\_PoseSnapshot\_\_**: `boolean`

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
