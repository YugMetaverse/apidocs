[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / KSphylElem

# Class: KSphylElem

[ue/ue](../modules/ue_ue.md).KSphylElem

## Hierarchy

- [`KShapeElem`](ue_ue.KShapeElem.md)

  ↳ **`KSphylElem`**

## Table of contents

### Constructors

- [constructor](ue_ue.KSphylElem.md#constructor)

### Properties

- [Center](ue_ue.KSphylElem.md#center)
- [Length](ue_ue.KSphylElem.md#length)
- [Name](ue_ue.KSphylElem.md#name)
- [Orientation](ue_ue.KSphylElem.md#orientation)
- [Radius](ue_ue.KSphylElem.md#radius)
- [RestOffset](ue_ue.KSphylElem.md#restoffset)
- [Rotation](ue_ue.KSphylElem.md#rotation)
- [TM](ue_ue.KSphylElem.md#tm)
- [\_\_tid\_KSphylElem\_\_](ue_ue.KSphylElem.md#__tid_ksphylelem__)
- [bContributeToMass](ue_ue.KSphylElem.md#bcontributetomass)

### Methods

- [StaticClass](ue_ue.KSphylElem.md#staticclass)
- [StaticStruct](ue_ue.KSphylElem.md#staticstruct)

## Constructors

### constructor

• **new KSphylElem**()

#### Overrides

[KShapeElem](ue_ue.KShapeElem.md).[constructor](ue_ue.KShapeElem.md#constructor)

• **new KSphylElem**(`TM`, `Orientation`, `Center`, `Rotation`, `Radius`, `Length`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TM` | [`Matrix`](ue_ue.Matrix.md) |
| `Orientation` | [`Quat`](ue_ue_s.Quat.md) |
| `Center` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `Radius` | `number` |
| `Length` | `number` |

#### Overrides

[KShapeElem](ue_ue.KShapeElem.md).[constructor](ue_ue.KShapeElem.md#constructor)

## Properties

### Center

• **Center**: [`Vector`](ue_ue_s.Vector.md)

___

### Length

• **Length**: `number`

___

### Name

• **Name**: `string`

#### Inherited from

[KShapeElem](ue_ue.KShapeElem.md).[Name](ue_ue.KShapeElem.md#name)

___

### Orientation

• **Orientation**: [`Quat`](ue_ue_s.Quat.md)

___

### Radius

• **Radius**: `number`

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

### \_\_tid\_KSphylElem\_\_

• `Private` **\_\_tid\_KSphylElem\_\_**: `boolean`

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
