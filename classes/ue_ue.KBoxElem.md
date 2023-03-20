[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / KBoxElem

# Class: KBoxElem

[ue/ue](../modules/ue_ue.md).KBoxElem

## Hierarchy

- [`KShapeElem`](ue_ue.KShapeElem.md)

  ↳ **`KBoxElem`**

## Table of contents

### Constructors

- [constructor](ue_ue.KBoxElem.md#constructor)

### Properties

- [Center](ue_ue.KBoxElem.md#center)
- [Name](ue_ue.KBoxElem.md#name)
- [Orientation](ue_ue.KBoxElem.md#orientation)
- [RestOffset](ue_ue.KBoxElem.md#restoffset)
- [Rotation](ue_ue.KBoxElem.md#rotation)
- [TM](ue_ue.KBoxElem.md#tm)
- [X](ue_ue.KBoxElem.md#x)
- [Y](ue_ue.KBoxElem.md#y)
- [Z](ue_ue.KBoxElem.md#z)
- [\_\_tid\_KBoxElem\_\_](ue_ue.KBoxElem.md#__tid_kboxelem__)
- [bContributeToMass](ue_ue.KBoxElem.md#bcontributetomass)

### Methods

- [StaticClass](ue_ue.KBoxElem.md#staticclass)
- [StaticStruct](ue_ue.KBoxElem.md#staticstruct)

## Constructors

### constructor

• **new KBoxElem**()

#### Overrides

[KShapeElem](ue_ue.KShapeElem.md).[constructor](ue_ue.KShapeElem.md#constructor)

• **new KBoxElem**(`TM`, `Orientation`, `Center`, `Rotation`, `X`, `Y`, `Z`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TM` | [`Matrix`](ue_ue.Matrix.md) |
| `Orientation` | [`Quat`](ue_ue_s.Quat.md) |
| `Center` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `X` | `number` |
| `Y` | `number` |
| `Z` | `number` |

#### Overrides

[KShapeElem](ue_ue.KShapeElem.md).[constructor](ue_ue.KShapeElem.md#constructor)

## Properties

### Center

• **Center**: [`Vector`](ue_ue_s.Vector.md)

___

### Name

• **Name**: `string`

#### Inherited from

[KShapeElem](ue_ue.KShapeElem.md).[Name](ue_ue.KShapeElem.md#name)

___

### Orientation

• **Orientation**: [`Quat`](ue_ue_s.Quat.md)

___

### RestOffset

• **RestOffset**: `number`

#### Inherited from

[KShapeElem](ue_ue.KShapeElem.md).[RestOffset](ue_ue.KShapeElem.md#restoffset)

___

### Rotation

• **Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### TM

• **TM**: [`Matrix`](ue_ue.Matrix.md)

___

### X

• **X**: `number`

___

### Y

• **Y**: `number`

___

### Z

• **Z**: `number`

___

### \_\_tid\_KBoxElem\_\_

• `Private` **\_\_tid\_KBoxElem\_\_**: `boolean`

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
