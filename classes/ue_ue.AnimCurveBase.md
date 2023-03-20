[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimCurveBase

# Class: AnimCurveBase

[ue/ue](../modules/ue_ue.md).AnimCurveBase

## Hierarchy

- **`AnimCurveBase`**

  ↳ [`FloatCurve`](ue_ue.FloatCurve.md)

  ↳ [`VectorCurve`](ue_ue.VectorCurve.md)

  ↳ [`TransformCurve`](ue_ue.TransformCurve.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimCurveBase.md#constructor)

### Properties

- [CurveTypeFlags](ue_ue.AnimCurveBase.md#curvetypeflags)
- [LastObservedName](ue_ue.AnimCurveBase.md#lastobservedname)
- [Name](ue_ue.AnimCurveBase.md#name)
- [\_\_tid\_AnimCurveBase\_\_](ue_ue.AnimCurveBase.md#__tid_animcurvebase__)

### Methods

- [StaticClass](ue_ue.AnimCurveBase.md#staticclass)
- [StaticStruct](ue_ue.AnimCurveBase.md#staticstruct)

## Constructors

### constructor

• **new AnimCurveBase**()

• **new AnimCurveBase**(`LastObservedName`, `Name`, `CurveTypeFlags`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `LastObservedName` | `string` |
| `Name` | [`SmartName`](ue_ue.SmartName.md) |
| `CurveTypeFlags` | `number` |

## Properties

### CurveTypeFlags

• **CurveTypeFlags**: `number`

___

### LastObservedName

• **LastObservedName**: `string`

___

### Name

• **Name**: [`SmartName`](ue_ue.SmartName.md)

___

### \_\_tid\_AnimCurveBase\_\_

• `Private` **\_\_tid\_AnimCurveBase\_\_**: `boolean`

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
