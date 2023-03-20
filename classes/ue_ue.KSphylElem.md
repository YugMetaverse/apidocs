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

#### Defined in

[ue/ue.d.ts:3443](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3443)

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

#### Defined in

[ue/ue.d.ts:3444](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3444)

## Properties

### Center

• **Center**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:3447](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3447)

___

### Length

• **Length**: `number`

#### Defined in

[ue/ue.d.ts:3450](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3450)

___

### Name

• **Name**: `string`

#### Inherited from

[KShapeElem](ue_ue.KShapeElem.md).[Name](ue_ue.KShapeElem.md#name)

#### Defined in

[ue/ue.d.ts:3373](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3373)

___

### Orientation

• **Orientation**: [`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue.d.ts:3446](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3446)

___

### Radius

• **Radius**: `number`

#### Defined in

[ue/ue.d.ts:3449](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3449)

___

### RestOffset

• **RestOffset**: `number`

#### Inherited from

[KShapeElem](ue_ue.KShapeElem.md).[RestOffset](ue_ue.KShapeElem.md#restoffset)

#### Defined in

[ue/ue.d.ts:3372](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3372)

___

### Rotation

• **Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:3448](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3448)

___

### TM

• **TM**: [`Matrix`](ue_ue.Matrix.md)

#### Defined in

[ue/ue.d.ts:3445](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3445)

___

### \_\_tid\_KSphylElem\_\_

• `Private` **\_\_tid\_KSphylElem\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3456](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3456)

___

### bContributeToMass

• **bContributeToMass**: `boolean`

#### Inherited from

[KShapeElem](ue_ue.KShapeElem.md).[bContributeToMass](ue_ue.KShapeElem.md#bcontributetomass)

#### Defined in

[ue/ue.d.ts:3374](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3374)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[KShapeElem](ue_ue.KShapeElem.md).[StaticClass](ue_ue.KShapeElem.md#staticclass)

#### Defined in

[ue/ue.d.ts:3454](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3454)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[KShapeElem](ue_ue.KShapeElem.md).[StaticStruct](ue_ue.KShapeElem.md#staticstruct)

#### Defined in

[ue/ue.d.ts:3455](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3455)
