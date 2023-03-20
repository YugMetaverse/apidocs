[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ForeignWorldSplineData

# Class: ForeignWorldSplineData

[ue/ue](../modules/ue_ue.md).ForeignWorldSplineData

## Table of contents

### Constructors

- [constructor](ue_ue.ForeignWorldSplineData.md#constructor)

### Properties

- [ForeignControlPointData](ue_ue.ForeignWorldSplineData.md#foreigncontrolpointdata)
- [ForeignControlPointDataMap](ue_ue.ForeignWorldSplineData.md#foreigncontrolpointdatamap)
- [ForeignSplineSegmentData](ue_ue.ForeignWorldSplineData.md#foreignsplinesegmentdata)
- [ForeignSplineSegmentDataMap](ue_ue.ForeignWorldSplineData.md#foreignsplinesegmentdatamap)
- [\_\_tid\_ForeignWorldSplineData\_\_](ue_ue.ForeignWorldSplineData.md#__tid_foreignworldsplinedata__)

### Methods

- [StaticClass](ue_ue.ForeignWorldSplineData.md#staticclass)
- [StaticStruct](ue_ue.ForeignWorldSplineData.md#staticstruct)

## Constructors

### constructor

• **new ForeignWorldSplineData**()

• **new ForeignWorldSplineData**(`ForeignControlPointDataMap`, `ForeignControlPointData`, `ForeignSplineSegmentDataMap`, `ForeignSplineSegmentData`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ForeignControlPointDataMap` | [`TMap`](../interfaces/ue_puerts.TMap.md)<[`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`LandscapeSplineControlPoint`](ue_ue.LandscapeSplineControlPoint.md)\>, [`ForeignControlPointData`](ue_ue.ForeignControlPointData.md)\> |
| `ForeignControlPointData` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ForeignControlPointData`](ue_ue.ForeignControlPointData.md)\> |
| `ForeignSplineSegmentDataMap` | [`TMap`](../interfaces/ue_puerts.TMap.md)<[`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`LandscapeSplineSegment`](ue_ue.LandscapeSplineSegment.md)\>, [`ForeignSplineSegmentData`](ue_ue.ForeignSplineSegmentData.md)\> |
| `ForeignSplineSegmentData` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ForeignSplineSegmentData`](ue_ue.ForeignSplineSegmentData.md)\> |

## Properties

### ForeignControlPointData

• **ForeignControlPointData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ForeignControlPointData`](ue_ue.ForeignControlPointData.md)\>

___

### ForeignControlPointDataMap

• **ForeignControlPointDataMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`LandscapeSplineControlPoint`](ue_ue.LandscapeSplineControlPoint.md)\>, [`ForeignControlPointData`](ue_ue.ForeignControlPointData.md)\>

___

### ForeignSplineSegmentData

• **ForeignSplineSegmentData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ForeignSplineSegmentData`](ue_ue.ForeignSplineSegmentData.md)\>

___

### ForeignSplineSegmentDataMap

• **ForeignSplineSegmentDataMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`LandscapeSplineSegment`](ue_ue.LandscapeSplineSegment.md)\>, [`ForeignSplineSegmentData`](ue_ue.ForeignSplineSegmentData.md)\>

___

### \_\_tid\_ForeignWorldSplineData\_\_

• `Private` **\_\_tid\_ForeignWorldSplineData\_\_**: `boolean`

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
