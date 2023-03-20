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

#### Defined in

[ue/ue.d.ts:43619](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43619)

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

#### Defined in

[ue/ue.d.ts:43620](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43620)

## Properties

### CenterAdjust

• **CenterAdjust**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:43624](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43624)

___

### ForwardAxis

• **ForwardAxis**: [`ESplineMeshAxis`](../enums/ue_ue.ESplineMeshAxis.md)

#### Defined in

[ue/ue.d.ts:43628](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43628)

___

### MaterialOverrides

• **MaterialOverrides**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Defined in

[ue/ue.d.ts:43622](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43622)

___

### Mesh

• **Mesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:43621](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43621)

___

### Orientation

• **Orientation**: [`LandscapeSplineMeshOrientation`](../enums/ue_ue.LandscapeSplineMeshOrientation.md)

#### Defined in

[ue/ue.d.ts:43627](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43627)

___

### Scale

• **Scale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:43626](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43626)

___

### UpAxis

• **UpAxis**: [`ESplineMeshAxis`](../enums/ue_ue.ESplineMeshAxis.md)

#### Defined in

[ue/ue.d.ts:43629](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43629)

___

### \_\_tid\_LandscapeSplineMeshEntry\_\_

• `Private` **\_\_tid\_LandscapeSplineMeshEntry\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:43635](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43635)

___

### bCenterH

• **bCenterH**: `boolean`

#### Defined in

[ue/ue.d.ts:43623](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43623)

___

### bScaleToWidth

• **bScaleToWidth**: `boolean`

#### Defined in

[ue/ue.d.ts:43625](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43625)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:43633](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43633)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:43634](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43634)
