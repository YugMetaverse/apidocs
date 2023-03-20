[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / RealCurve

# Class: RealCurve

[ue/ue](../modules/ue_ue.md).RealCurve

## Hierarchy

- [`IndexedCurve`](ue_ue.IndexedCurve.md)

  ↳ **`RealCurve`**

  ↳↳ [`RichCurve`](ue_ue.RichCurve.md)

## Table of contents

### Constructors

- [constructor](ue_ue.RealCurve.md#constructor)

### Properties

- [DefaultValue](ue_ue.RealCurve.md#defaultvalue)
- [KeyHandlesToIndices](ue_ue.RealCurve.md#keyhandlestoindices)
- [PostInfinityExtrap](ue_ue.RealCurve.md#postinfinityextrap)
- [PreInfinityExtrap](ue_ue.RealCurve.md#preinfinityextrap)
- [\_\_tid\_RealCurve\_\_](ue_ue.RealCurve.md#__tid_realcurve__)

### Methods

- [StaticClass](ue_ue.RealCurve.md#staticclass)
- [StaticStruct](ue_ue.RealCurve.md#staticstruct)

## Constructors

### constructor

• **new RealCurve**()

#### Overrides

[IndexedCurve](ue_ue.IndexedCurve.md).[constructor](ue_ue.IndexedCurve.md#constructor)

• **new RealCurve**(`DefaultValue`, `PreInfinityExtrap`, `PostInfinityExtrap`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `DefaultValue` | `number` |
| `PreInfinityExtrap` | [`ERichCurveExtrapolation`](../enums/ue_ue.ERichCurveExtrapolation.md) |
| `PostInfinityExtrap` | [`ERichCurveExtrapolation`](../enums/ue_ue.ERichCurveExtrapolation.md) |

#### Overrides

[IndexedCurve](ue_ue.IndexedCurve.md).[constructor](ue_ue.IndexedCurve.md#constructor)

## Properties

### DefaultValue

• **DefaultValue**: `number`

___

### KeyHandlesToIndices

• **KeyHandlesToIndices**: [`KeyHandleMap`](ue_ue.KeyHandleMap.md)

#### Inherited from

[IndexedCurve](ue_ue.IndexedCurve.md).[KeyHandlesToIndices](ue_ue.IndexedCurve.md#keyhandlestoindices)

___

### PostInfinityExtrap

• **PostInfinityExtrap**: [`ERichCurveExtrapolation`](../enums/ue_ue.ERichCurveExtrapolation.md)

___

### PreInfinityExtrap

• **PreInfinityExtrap**: [`ERichCurveExtrapolation`](../enums/ue_ue.ERichCurveExtrapolation.md)

___

### \_\_tid\_RealCurve\_\_

• `Private` **\_\_tid\_RealCurve\_\_**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[IndexedCurve](ue_ue.IndexedCurve.md).[StaticClass](ue_ue.IndexedCurve.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[IndexedCurve](ue_ue.IndexedCurve.md).[StaticStruct](ue_ue.IndexedCurve.md#staticstruct)
