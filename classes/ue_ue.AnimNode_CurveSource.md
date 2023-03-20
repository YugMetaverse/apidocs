[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_CurveSource

# Class: AnimNode\_CurveSource

[ue/ue](../modules/ue_ue.md).AnimNode_CurveSource

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_CurveSource`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_CurveSource.md#constructor)

### Properties

- [Alpha](ue_ue.AnimNode_CurveSource.md#alpha)
- [CurveSource](ue_ue.AnimNode_CurveSource.md#curvesource)
- [SourceBinding](ue_ue.AnimNode_CurveSource.md#sourcebinding)
- [SourcePose](ue_ue.AnimNode_CurveSource.md#sourcepose)
- [\_\_tid\_AnimNode\_CurveSource\_\_](ue_ue.AnimNode_CurveSource.md#__tid_animnode_curvesource__)

### Methods

- [StaticClass](ue_ue.AnimNode_CurveSource.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_CurveSource.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_CurveSource**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

• **new AnimNode_CurveSource**(`SourcePose`, `SourceBinding`, `Alpha`, `CurveSource`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourcePose` | [`PoseLink`](ue_ue.PoseLink.md) |
| `SourceBinding` | `string` |
| `Alpha` | `number` |
| `CurveSource` | [`CurveSourceInterface`](ue_ue.CurveSourceInterface.md) |

#### Overrides

UE.AnimNode\_Base.constructor

## Properties

### Alpha

• **Alpha**: `number`

___

### CurveSource

• **CurveSource**: [`CurveSourceInterface`](ue_ue.CurveSourceInterface.md)

___

### SourceBinding

• **SourceBinding**: `string`

___

### SourcePose

• **SourcePose**: [`PoseLink`](ue_ue.PoseLink.md)

___

### \_\_tid\_AnimNode\_CurveSource\_\_

• `Private` **\_\_tid\_AnimNode\_CurveSource\_\_**: `boolean`

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
