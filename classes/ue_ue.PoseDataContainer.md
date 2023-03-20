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

• **new PoseDataContainer**(`PoseNames`, `Tracks`, `TrackMap`, `Poses`, `Curves`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PoseNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SmartName`](ue_ue.SmartName.md)\> |
| `Tracks` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `TrackMap` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `number`\> |
| `Poses` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseData`](ue_ue.PoseData.md)\> |
| `Curves` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimCurveBase`](ue_ue.AnimCurveBase.md)\> |

## Properties

### Curves

• **Curves**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimCurveBase`](ue_ue.AnimCurveBase.md)\>

___

### PoseNames

• **PoseNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SmartName`](ue_ue.SmartName.md)\>

___

### Poses

• **Poses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseData`](ue_ue.PoseData.md)\>

___

### TrackMap

• **TrackMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `number`\>

___

### Tracks

• **Tracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### \_\_tid\_PoseDataContainer\_\_

• `Private` **\_\_tid\_PoseDataContainer\_\_**: `boolean`

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
