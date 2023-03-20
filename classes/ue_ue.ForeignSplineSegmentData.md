[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ForeignSplineSegmentData

# Class: ForeignSplineSegmentData

[ue/ue](../modules/ue_ue.md).ForeignSplineSegmentData

## Table of contents

### Constructors

- [constructor](ue_ue.ForeignSplineSegmentData.md#constructor)

### Properties

- [Identifier](ue_ue.ForeignSplineSegmentData.md#identifier)
- [MeshComponents](ue_ue.ForeignSplineSegmentData.md#meshcomponents)
- [ModificationKey](ue_ue.ForeignSplineSegmentData.md#modificationkey)
- [\_\_tid\_ForeignSplineSegmentData\_\_](ue_ue.ForeignSplineSegmentData.md#__tid_foreignsplinesegmentdata__)

### Methods

- [StaticClass](ue_ue.ForeignSplineSegmentData.md#staticclass)
- [StaticStruct](ue_ue.ForeignSplineSegmentData.md#staticstruct)

## Constructors

### constructor

• **new ForeignSplineSegmentData**()

• **new ForeignSplineSegmentData**(`ModificationKey`, `MeshComponents`, `Identifier`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ModificationKey` | [`Guid`](ue_ue_s.Guid.md) |
| `MeshComponents` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SplineMeshComponent`](ue_ue.SplineMeshComponent.md)\> |
| `Identifier` | [`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`LandscapeSplineSegment`](ue_ue.LandscapeSplineSegment.md)\> |

## Properties

### Identifier

• **Identifier**: [`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`LandscapeSplineSegment`](ue_ue.LandscapeSplineSegment.md)\>

___

### MeshComponents

• **MeshComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SplineMeshComponent`](ue_ue.SplineMeshComponent.md)\>

___

### ModificationKey

• **ModificationKey**: [`Guid`](ue_ue_s.Guid.md)

___

### \_\_tid\_ForeignSplineSegmentData\_\_

• `Private` **\_\_tid\_ForeignSplineSegmentData\_\_**: `boolean`

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
