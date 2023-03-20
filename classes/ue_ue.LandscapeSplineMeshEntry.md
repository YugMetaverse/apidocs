[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LandscapeSplineMeshEntry

# Class: LandscapeSplineMeshEntry

[ue/ue](../modules/ue_ue.md).LandscapeSplineMeshEntry

## Table of contents

### Constructors

- [constructor](ue_ue.LandscapeSplineMeshEntry.md#constructor)

### Properties

- [CenterAdjust](ue_ue.LandscapeSplineMeshEntry.md#centeradjust)
- [ForwardAxis](ue_ue.LandscapeSplineMeshEntry.md#forwardaxis)
- [MaterialOverrides](ue_ue.LandscapeSplineMeshEntry.md#materialoverrides)
- [Mesh](ue_ue.LandscapeSplineMeshEntry.md#mesh)
- [Orientation](ue_ue.LandscapeSplineMeshEntry.md#orientation)
- [Scale](ue_ue.LandscapeSplineMeshEntry.md#scale)
- [UpAxis](ue_ue.LandscapeSplineMeshEntry.md#upaxis)
- [\_\_tid\_LandscapeSplineMeshEntry\_\_](ue_ue.LandscapeSplineMeshEntry.md#__tid_landscapesplinemeshentry__)
- [bCenterH](ue_ue.LandscapeSplineMeshEntry.md#bcenterh)
- [bScaleToWidth](ue_ue.LandscapeSplineMeshEntry.md#bscaletowidth)

### Methods

- [StaticClass](ue_ue.LandscapeSplineMeshEntry.md#staticclass)
- [StaticStruct](ue_ue.LandscapeSplineMeshEntry.md#staticstruct)

## Constructors

### constructor

• **new LandscapeSplineMeshEntry**()

• **new LandscapeSplineMeshEntry**(`Mesh`, `MaterialOverrides`, `bCenterH`, `CenterAdjust`, `bScaleToWidth`, `Scale`, `Orientation`, `ForwardAxis`, `UpAxis`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Mesh` | [`StaticMesh`](ue_ue.StaticMesh.md) |
| `MaterialOverrides` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `bCenterH` | `boolean` |
| `CenterAdjust` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `bScaleToWidth` | `boolean` |
| `Scale` | [`Vector`](ue_ue_s.Vector.md) |
| `Orientation` | [`LandscapeSplineMeshOrientation`](../enums/ue_ue.LandscapeSplineMeshOrientation.md) |
| `ForwardAxis` | [`ESplineMeshAxis`](../enums/ue_ue.ESplineMeshAxis.md) |
| `UpAxis` | [`ESplineMeshAxis`](../enums/ue_ue.ESplineMeshAxis.md) |

## Properties

### CenterAdjust

• **CenterAdjust**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### ForwardAxis

• **ForwardAxis**: [`ESplineMeshAxis`](../enums/ue_ue.ESplineMeshAxis.md)

___

### MaterialOverrides

• **MaterialOverrides**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

___

### Mesh

• **Mesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### Orientation

• **Orientation**: [`LandscapeSplineMeshOrientation`](../enums/ue_ue.LandscapeSplineMeshOrientation.md)

___

### Scale

• **Scale**: [`Vector`](ue_ue_s.Vector.md)

___

### UpAxis

• **UpAxis**: [`ESplineMeshAxis`](../enums/ue_ue.ESplineMeshAxis.md)

___

### \_\_tid\_LandscapeSplineMeshEntry\_\_

• `Private` **\_\_tid\_LandscapeSplineMeshEntry\_\_**: `boolean`

___

### bCenterH

• **bCenterH**: `boolean`

___

### bScaleToWidth

• **bScaleToWidth**: `boolean`

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
