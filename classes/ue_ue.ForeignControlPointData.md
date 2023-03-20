[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ForeignControlPointData

# Class: ForeignControlPointData

[ue/ue](../modules/ue_ue.md).ForeignControlPointData

## Table of contents

### Constructors

- [constructor](ue_ue.ForeignControlPointData.md#constructor)

### Properties

- [Identifier](ue_ue.ForeignControlPointData.md#identifier)
- [MeshComponent](ue_ue.ForeignControlPointData.md#meshcomponent)
- [ModificationKey](ue_ue.ForeignControlPointData.md#modificationkey)
- [\_\_tid\_ForeignControlPointData\_\_](ue_ue.ForeignControlPointData.md#__tid_foreigncontrolpointdata__)

### Methods

- [StaticClass](ue_ue.ForeignControlPointData.md#staticclass)
- [StaticStruct](ue_ue.ForeignControlPointData.md#staticstruct)

## Constructors

### constructor

• **new ForeignControlPointData**()

• **new ForeignControlPointData**(`ModificationKey`, `MeshComponent`, `Identifier`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ModificationKey` | [`Guid`](ue_ue_s.Guid.md) |
| `MeshComponent` | [`ControlPointMeshComponent`](ue_ue.ControlPointMeshComponent.md) |
| `Identifier` | [`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`LandscapeSplineControlPoint`](ue_ue.LandscapeSplineControlPoint.md)\> |

## Properties

### Identifier

• **Identifier**: [`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`LandscapeSplineControlPoint`](ue_ue.LandscapeSplineControlPoint.md)\>

___

### MeshComponent

• **MeshComponent**: [`ControlPointMeshComponent`](ue_ue.ControlPointMeshComponent.md)

___

### ModificationKey

• **ModificationKey**: [`Guid`](ue_ue_s.Guid.md)

___

### \_\_tid\_ForeignControlPointData\_\_

• `Private` **\_\_tid\_ForeignControlPointData\_\_**: `boolean`

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
