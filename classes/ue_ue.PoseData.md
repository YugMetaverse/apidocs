[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PoseData

# Class: PoseData

[ue/ue](../modules/ue_ue.md).PoseData

## Table of contents

### Constructors

- [constructor](ue_ue.PoseData.md#constructor)

### Properties

- [CurveData](ue_ue.PoseData.md#curvedata)
- [LocalSpacePose](ue_ue.PoseData.md#localspacepose)
- [SourceCurveData](ue_ue.PoseData.md#sourcecurvedata)
- [SourceLocalSpacePose](ue_ue.PoseData.md#sourcelocalspacepose)
- [TrackToBufferIndex](ue_ue.PoseData.md#tracktobufferindex)
- [\_\_tid\_PoseData\_\_](ue_ue.PoseData.md#__tid_posedata__)

### Methods

- [StaticClass](ue_ue.PoseData.md#staticclass)
- [StaticStruct](ue_ue.PoseData.md#staticstruct)

## Constructors

### constructor

• **new PoseData**()

• **new PoseData**(`SourceLocalSpacePose`, `SourceCurveData`, `LocalSpacePose`, `TrackToBufferIndex`, `CurveData`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceLocalSpacePose` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\> |
| `SourceCurveData` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `LocalSpacePose` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\> |
| `TrackToBufferIndex` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, `number`\> |
| `CurveData` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

## Properties

### CurveData

• **CurveData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### LocalSpacePose

• **LocalSpacePose**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\>

___

### SourceCurveData

• **SourceCurveData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### SourceLocalSpacePose

• **SourceLocalSpacePose**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\>

___

### TrackToBufferIndex

• **TrackToBufferIndex**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, `number`\>

___

### \_\_tid\_PoseData\_\_

• `Private` **\_\_tid\_PoseData\_\_**: `boolean`

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
