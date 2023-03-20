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

#### Defined in

[ue/ue.d.ts:2701](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2701)

• **new PoseData**(`SourceLocalSpacePose`, `SourceCurveData`, `LocalSpacePose`, `TrackToBufferIndex`, `CurveData`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceLocalSpacePose` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\> |
| `SourceCurveData` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `LocalSpacePose` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\> |
| `TrackToBufferIndex` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, `number`\> |
| `CurveData` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Defined in

[ue/ue.d.ts:2702](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2702)

## Properties

### CurveData

• **CurveData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:2707](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2707)

___

### LocalSpacePose

• **LocalSpacePose**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\>

#### Defined in

[ue/ue.d.ts:2705](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2705)

___

### SourceCurveData

• **SourceCurveData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:2704](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2704)

___

### SourceLocalSpacePose

• **SourceLocalSpacePose**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\>

#### Defined in

[ue/ue.d.ts:2703](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2703)

___

### TrackToBufferIndex

• **TrackToBufferIndex**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, `number`\>

#### Defined in

[ue/ue.d.ts:2706](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2706)

___

### \_\_tid\_PoseData\_\_

• `Private` **\_\_tid\_PoseData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:2713](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2713)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:2711](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2711)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:2712](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2712)
