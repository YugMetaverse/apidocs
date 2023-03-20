[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ChangeVertexInstancesForPolygon

# Class: ChangeVertexInstancesForPolygon

[ue/ue](../modules/ue_ue.md).ChangeVertexInstancesForPolygon

## Table of contents

### Constructors

- [constructor](ue_ue.ChangeVertexInstancesForPolygon.md#constructor)

### Properties

- [PerimeterVertexIndicesAndInstanceIDs](ue_ue.ChangeVertexInstancesForPolygon.md#perimetervertexindicesandinstanceids)
- [PolygonID](ue_ue.ChangeVertexInstancesForPolygon.md#polygonid)
- [VertexIndicesAndInstanceIDsForEachHole](ue_ue.ChangeVertexInstancesForPolygon.md#vertexindicesandinstanceidsforeachhole)
- [\_\_tid\_ChangeVertexInstancesForPolygon\_\_](ue_ue.ChangeVertexInstancesForPolygon.md#__tid_changevertexinstancesforpolygon__)

### Methods

- [StaticClass](ue_ue.ChangeVertexInstancesForPolygon.md#staticclass)
- [StaticStruct](ue_ue.ChangeVertexInstancesForPolygon.md#staticstruct)

## Constructors

### constructor

• **new ChangeVertexInstancesForPolygon**()

• **new ChangeVertexInstancesForPolygon**(`PolygonID`, `PerimeterVertexIndicesAndInstanceIDs`, `VertexIndicesAndInstanceIDsForEachHole`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `PerimeterVertexIndicesAndInstanceIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexIndexAndInstanceID`](ue_ue.VertexIndexAndInstanceID.md)\> |
| `VertexIndicesAndInstanceIDsForEachHole` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexInstancesForPolygonHole`](ue_ue.VertexInstancesForPolygonHole.md)\> |

## Properties

### PerimeterVertexIndicesAndInstanceIDs

• **PerimeterVertexIndicesAndInstanceIDs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexIndexAndInstanceID`](ue_ue.VertexIndexAndInstanceID.md)\>

___

### PolygonID

• **PolygonID**: [`PolygonID`](ue_ue.PolygonID.md)

___

### VertexIndicesAndInstanceIDsForEachHole

• **VertexIndicesAndInstanceIDsForEachHole**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexInstancesForPolygonHole`](ue_ue.VertexInstancesForPolygonHole.md)\>

___

### \_\_tid\_ChangeVertexInstancesForPolygon\_\_

• `Private` **\_\_tid\_ChangeVertexInstancesForPolygon\_\_**: `boolean`

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
