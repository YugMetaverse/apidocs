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

#### Defined in

[ue/ue.d.ts:3425](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3425)

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

#### Defined in

[ue/ue.d.ts:3426](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3426)

## Properties

### Center

• **Center**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:3429](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3429)

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

[ue/ue.d.ts:3428](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3428)

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

[ue/ue.d.ts:3430](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3430)

___

### TM

• **TM**: [`Matrix`](ue_ue.Matrix.md)

#### Defined in

[ue/ue.d.ts:3427](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3427)

___

### X

• **X**: `number`

#### Defined in

[ue/ue.d.ts:3431](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3431)

___

### Y

• **Y**: `number`

#### Defined in

[ue/ue.d.ts:3432](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3432)

___

### Z

• **Z**: `number`

#### Defined in

[ue/ue.d.ts:3433](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3433)

___

### \_\_tid\_KBoxElem\_\_

• `Private` **\_\_tid\_KBoxElem\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3439](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3439)

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

[ue/ue.d.ts:3437](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3437)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[KShapeElem](ue_ue.KShapeElem.md).[StaticStruct](ue_ue.KShapeElem.md#staticstruct)

#### Defined in

[ue/ue.d.ts:3438](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3438)
