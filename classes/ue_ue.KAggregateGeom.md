[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / KAggregateGeom

# Class: KAggregateGeom

[ue/ue](../modules/ue_ue.md).KAggregateGeom

## Table of contents

### Constructors

- [constructor](ue_ue.KAggregateGeom.md#constructor)

### Properties

- [BoxElems](ue_ue.KAggregateGeom.md#boxelems)
- [ConvexElems](ue_ue.KAggregateGeom.md#convexelems)
- [SphereElems](ue_ue.KAggregateGeom.md#sphereelems)
- [SphylElems](ue_ue.KAggregateGeom.md#sphylelems)
- [TaperedCapsuleElems](ue_ue.KAggregateGeom.md#taperedcapsuleelems)
- [\_\_tid\_KAggregateGeom\_\_](ue_ue.KAggregateGeom.md#__tid_kaggregategeom__)

### Methods

- [StaticClass](ue_ue.KAggregateGeom.md#staticclass)
- [StaticStruct](ue_ue.KAggregateGeom.md#staticstruct)

## Constructors

### constructor

• **new KAggregateGeom**()

• **new KAggregateGeom**(`SphereElems`, `BoxElems`, `SphylElems`, `ConvexElems`, `TaperedCapsuleElems`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SphereElems` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`KSphereElem`](ue_ue.KSphereElem.md)\> |
| `BoxElems` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`KBoxElem`](ue_ue.KBoxElem.md)\> |
| `SphylElems` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`KSphylElem`](ue_ue.KSphylElem.md)\> |
| `ConvexElems` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`KConvexElem`](ue_ue.KConvexElem.md)\> |
| `TaperedCapsuleElems` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`KTaperedCapsuleElem`](ue_ue.KTaperedCapsuleElem.md)\> |

## Properties

### BoxElems

• **BoxElems**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`KBoxElem`](ue_ue.KBoxElem.md)\>

___

### ConvexElems

• **ConvexElems**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`KConvexElem`](ue_ue.KConvexElem.md)\>

___

### SphereElems

• **SphereElems**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`KSphereElem`](ue_ue.KSphereElem.md)\>

___

### SphylElems

• **SphylElems**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`KSphylElem`](ue_ue.KSphylElem.md)\>

___

### TaperedCapsuleElems

• **TaperedCapsuleElems**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`KTaperedCapsuleElem`](ue_ue.KTaperedCapsuleElem.md)\>

___

### \_\_tid\_KAggregateGeom\_\_

• `Private` **\_\_tid\_KAggregateGeom\_\_**: `boolean`

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
