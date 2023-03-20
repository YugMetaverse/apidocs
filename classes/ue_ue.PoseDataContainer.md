[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PoseDataContainer

# Class: PoseDataContainer

[ue/ue](../modules/ue_ue.md).PoseDataContainer

## Table of contents

### Constructors

- [constructor](ue_ue.PoseDataContainer.md#constructor)

### Properties

- [Curves](ue_ue.PoseDataContainer.md#curves)
- [PoseNames](ue_ue.PoseDataContainer.md#posenames)
- [Poses](ue_ue.PoseDataContainer.md#poses)
- [TrackMap](ue_ue.PoseDataContainer.md#trackmap)
- [Tracks](ue_ue.PoseDataContainer.md#tracks)
- [\_\_tid\_PoseDataContainer\_\_](ue_ue.PoseDataContainer.md#__tid_posedatacontainer__)

### Methods

- [StaticClass](ue_ue.PoseDataContainer.md#staticclass)
- [StaticStruct](ue_ue.PoseDataContainer.md#staticstruct)

## Constructors

### constructor

• **new PoseDataContainer**()

#### Defined in

[ue/ue.d.ts:2731](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2731)

• **new PoseDataContainer**(`PoseNames`, `Tracks`, `TrackMap`, `Poses`, `Curves`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PoseNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SmartName`](ue_ue.SmartName.md)\> |
| `Tracks` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `TrackMap` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `number`\> |
| `Poses` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseData`](ue_ue.PoseData.md)\> |
| `Curves` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimCurveBase`](ue_ue.AnimCurveBase.md)\> |

#### Defined in

[ue/ue.d.ts:2732](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2732)

## Properties

### Curves

• **Curves**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimCurveBase`](ue_ue.AnimCurveBase.md)\>

#### Defined in

[ue/ue.d.ts:2737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2737)

___

### PoseNames

• **PoseNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SmartName`](ue_ue.SmartName.md)\>

#### Defined in

[ue/ue.d.ts:2733](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2733)

___

### Poses

• **Poses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseData`](ue_ue.PoseData.md)\>

#### Defined in

[ue/ue.d.ts:2736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2736)

___

### TrackMap

• **TrackMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `number`\>

#### Defined in

[ue/ue.d.ts:2735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2735)

___

### Tracks

• **Tracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:2734](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2734)

___

### \_\_tid\_PoseDataContainer\_\_

• `Private` **\_\_tid\_PoseDataContainer\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:2743](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2743)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:2741](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2741)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:2742](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2742)
