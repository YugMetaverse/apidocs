[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / KConvexElem

# Class: KConvexElem

[ue/ue](../modules/ue_ue.md).KConvexElem

## Hierarchy

- [`KShapeElem`](ue_ue.KShapeElem.md)

  ↳ **`KConvexElem`**

## Table of contents

### Constructors

- [constructor](ue_ue.KConvexElem.md#constructor)

### Properties

- [ElemBox](ue_ue.KConvexElem.md#elembox)
- [Name](ue_ue.KConvexElem.md#name)
- [RestOffset](ue_ue.KConvexElem.md#restoffset)
- [Transform](ue_ue.KConvexElem.md#transform)
- [VertexData](ue_ue.KConvexElem.md#vertexdata)
- [\_\_tid\_KConvexElem\_\_](ue_ue.KConvexElem.md#__tid_kconvexelem__)
- [bContributeToMass](ue_ue.KConvexElem.md#bcontributetomass)

### Methods

- [StaticClass](ue_ue.KConvexElem.md#staticclass)
- [StaticStruct](ue_ue.KConvexElem.md#staticstruct)

## Constructors

### constructor

• **new KConvexElem**()

#### Overrides

[KShapeElem](ue_ue.KShapeElem.md).[constructor](ue_ue.KShapeElem.md#constructor)

• **new KConvexElem**(`VertexData`, `ElemBox`, `Transform`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexData` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `ElemBox` | [`Box`](ue_ue.Box.md) |
| `Transform` | [`Transform`](ue_ue_s.Transform.md) |

#### Overrides

[KShapeElem](ue_ue.KShapeElem.md).[constructor](ue_ue.KShapeElem.md#constructor)

## Properties

### ElemBox

• **ElemBox**: [`Box`](ue_ue.Box.md)

___

### Name

• **Name**: `string`

#### Inherited from

[KShapeElem](ue_ue.KShapeElem.md).[Name](ue_ue.KShapeElem.md#name)

___

### RestOffset

• **RestOffset**: `number`

#### Inherited from

[KShapeElem](ue_ue.KShapeElem.md).[RestOffset](ue_ue.KShapeElem.md#restoffset)

___

### Transform

• **Transform**: [`Transform`](ue_ue_s.Transform.md)

___

### VertexData

• **VertexData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

___

### \_\_tid\_KConvexElem\_\_

• `Private` **\_\_tid\_KConvexElem\_\_**: `boolean`

___

### bContributeToMass

• **bContributeToMass**: `boolean`

#### Inherited from

[KShapeElem](ue_ue.KShapeElem.md).[bContributeToMass](ue_ue.KShapeElem.md#bcontributetomass)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[KShapeElem](ue_ue.KShapeElem.md).[StaticClass](ue_ue.KShapeElem.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[KShapeElem](ue_ue.KShapeElem.md).[StaticStruct](ue_ue.KShapeElem.md#staticstruct)
