[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TransformCurve

# Class: TransformCurve

[ue/ue](../modules/ue_ue.md).TransformCurve

## Hierarchy

- [`AnimCurveBase`](ue_ue.AnimCurveBase.md)

  ↳ **`TransformCurve`**

## Table of contents

### Constructors

- [constructor](ue_ue.TransformCurve.md#constructor)

### Properties

- [CurveTypeFlags](ue_ue.TransformCurve.md#curvetypeflags)
- [LastObservedName](ue_ue.TransformCurve.md#lastobservedname)
- [Name](ue_ue.TransformCurve.md#name)
- [RotationCurve](ue_ue.TransformCurve.md#rotationcurve)
- [ScaleCurve](ue_ue.TransformCurve.md#scalecurve)
- [TranslationCurve](ue_ue.TransformCurve.md#translationcurve)
- [\_\_tid\_TransformCurve\_\_](ue_ue.TransformCurve.md#__tid_transformcurve__)

### Methods

- [StaticClass](ue_ue.TransformCurve.md#staticclass)
- [StaticStruct](ue_ue.TransformCurve.md#staticstruct)

## Constructors

### constructor

• **new TransformCurve**()

#### Overrides

[AnimCurveBase](ue_ue.AnimCurveBase.md).[constructor](ue_ue.AnimCurveBase.md#constructor)

#### Defined in

[ue/ue.d.ts:3088](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3088)

• **new TransformCurve**(`TranslationCurve`, `RotationCurve`, `ScaleCurve`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TranslationCurve` | [`VectorCurve`](ue_ue.VectorCurve.md) |
| `RotationCurve` | [`VectorCurve`](ue_ue.VectorCurve.md) |
| `ScaleCurve` | [`VectorCurve`](ue_ue.VectorCurve.md) |

#### Overrides

[AnimCurveBase](ue_ue.AnimCurveBase.md).[constructor](ue_ue.AnimCurveBase.md#constructor)

#### Defined in

[ue/ue.d.ts:3089](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3089)

## Properties

### CurveTypeFlags

• **CurveTypeFlags**: `number`

#### Inherited from

[AnimCurveBase](ue_ue.AnimCurveBase.md).[CurveTypeFlags](ue_ue.AnimCurveBase.md#curvetypeflags)

#### Defined in

[ue/ue.d.ts:2721](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2721)

___

### LastObservedName

• **LastObservedName**: `string`

#### Inherited from

[AnimCurveBase](ue_ue.AnimCurveBase.md).[LastObservedName](ue_ue.AnimCurveBase.md#lastobservedname)

#### Defined in

[ue/ue.d.ts:2719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2719)

___

### Name

• **Name**: [`SmartName`](ue_ue.SmartName.md)

#### Inherited from

[AnimCurveBase](ue_ue.AnimCurveBase.md).[Name](ue_ue.AnimCurveBase.md#name)

#### Defined in

[ue/ue.d.ts:2720](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2720)

___

### RotationCurve

• **RotationCurve**: [`VectorCurve`](ue_ue.VectorCurve.md)

#### Defined in

[ue/ue.d.ts:3091](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3091)

___

### ScaleCurve

• **ScaleCurve**: [`VectorCurve`](ue_ue.VectorCurve.md)

#### Defined in

[ue/ue.d.ts:3092](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3092)

___

### TranslationCurve

• **TranslationCurve**: [`VectorCurve`](ue_ue.VectorCurve.md)

#### Defined in

[ue/ue.d.ts:3090](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3090)

___

### \_\_tid\_TransformCurve\_\_

• `Private` **\_\_tid\_TransformCurve\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3098](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3098)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimCurveBase](ue_ue.AnimCurveBase.md).[StaticClass](ue_ue.AnimCurveBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:3096](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3096)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimCurveBase](ue_ue.AnimCurveBase.md).[StaticStruct](ue_ue.AnimCurveBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:3097](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3097)
