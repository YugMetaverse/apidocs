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

• **new TransformCurve**(`TranslationCurve`, `RotationCurve`, `ScaleCurve`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TranslationCurve` | [`VectorCurve`](ue_ue.VectorCurve.md) |
| `RotationCurve` | [`VectorCurve`](ue_ue.VectorCurve.md) |
| `ScaleCurve` | [`VectorCurve`](ue_ue.VectorCurve.md) |

#### Overrides

[AnimCurveBase](ue_ue.AnimCurveBase.md).[constructor](ue_ue.AnimCurveBase.md#constructor)

## Properties

### CurveTypeFlags

• **CurveTypeFlags**: `number`

#### Inherited from

[AnimCurveBase](ue_ue.AnimCurveBase.md).[CurveTypeFlags](ue_ue.AnimCurveBase.md#curvetypeflags)

___

### LastObservedName

• **LastObservedName**: `string`

#### Inherited from

[AnimCurveBase](ue_ue.AnimCurveBase.md).[LastObservedName](ue_ue.AnimCurveBase.md#lastobservedname)

___

### Name

• **Name**: [`SmartName`](ue_ue.SmartName.md)

#### Inherited from

[AnimCurveBase](ue_ue.AnimCurveBase.md).[Name](ue_ue.AnimCurveBase.md#name)

___

### RotationCurve

• **RotationCurve**: [`VectorCurve`](ue_ue.VectorCurve.md)

___

### ScaleCurve

• **ScaleCurve**: [`VectorCurve`](ue_ue.VectorCurve.md)

___

### TranslationCurve

• **TranslationCurve**: [`VectorCurve`](ue_ue.VectorCurve.md)

___

### \_\_tid\_TransformCurve\_\_

• `Private` **\_\_tid\_TransformCurve\_\_**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimCurveBase](ue_ue.AnimCurveBase.md).[StaticClass](ue_ue.AnimCurveBase.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimCurveBase](ue_ue.AnimCurveBase.md).[StaticStruct](ue_ue.AnimCurveBase.md#staticstruct)
