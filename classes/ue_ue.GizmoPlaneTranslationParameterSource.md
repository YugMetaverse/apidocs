[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GizmoPlaneTranslationParameterSource

# Class: GizmoPlaneTranslationParameterSource

[ue/ue](../modules/ue_ue.md).GizmoPlaneTranslationParameterSource

## Hierarchy

- [`GizmoBaseVec2ParameterSource`](ue_ue.GizmoBaseVec2ParameterSource.md)

  ↳ **`GizmoPlaneTranslationParameterSource`**

## Table of contents

### Constructors

- [constructor](ue_ue.GizmoPlaneTranslationParameterSource.md#constructor)

### Properties

- [AxisSource](ue_ue.GizmoPlaneTranslationParameterSource.md#axissource)
- [CurTranslationAxisX](ue_ue.GizmoPlaneTranslationParameterSource.md#curtranslationaxisx)
- [CurTranslationAxisY](ue_ue.GizmoPlaneTranslationParameterSource.md#curtranslationaxisy)
- [CurTranslationNormal](ue_ue.GizmoPlaneTranslationParameterSource.md#curtranslationnormal)
- [CurTranslationOrigin](ue_ue.GizmoPlaneTranslationParameterSource.md#curtranslationorigin)
- [InitialTransform](ue_ue.GizmoPlaneTranslationParameterSource.md#initialtransform)
- [LastChange](ue_ue.GizmoPlaneTranslationParameterSource.md#lastchange)
- [Parameter](ue_ue.GizmoPlaneTranslationParameterSource.md#parameter)
- [TransformSource](ue_ue.GizmoPlaneTranslationParameterSource.md#transformsource)
- [\_\_tid\_GizmoBaseVec2ParameterSource\_\_](ue_ue.GizmoPlaneTranslationParameterSource.md#__tid_gizmobasevec2parametersource__)
- [\_\_tid\_GizmoPlaneTranslationParameterSource\_\_](ue_ue.GizmoPlaneTranslationParameterSource.md#__tid_gizmoplanetranslationparametersource__)
- [\_\_tid\_Object\_\_](ue_ue.GizmoPlaneTranslationParameterSource.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.GizmoPlaneTranslationParameterSource.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GizmoPlaneTranslationParameterSource.md#executeubergraph)
- [GetClass](ue_ue.GizmoPlaneTranslationParameterSource.md#getclass)
- [GetName](ue_ue.GizmoPlaneTranslationParameterSource.md#getname)
- [GetOuter](ue_ue.GizmoPlaneTranslationParameterSource.md#getouter)
- [GetWorld](ue_ue.GizmoPlaneTranslationParameterSource.md#getworld)
- [Find](ue_ue.GizmoPlaneTranslationParameterSource.md#find)
- [Load](ue_ue.GizmoPlaneTranslationParameterSource.md#load)
- [StaticClass](ue_ue.GizmoPlaneTranslationParameterSource.md#staticclass)

## Constructors

### constructor

• **new GizmoPlaneTranslationParameterSource**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GizmoBaseVec2ParameterSource](ue_ue.GizmoBaseVec2ParameterSource.md).[constructor](ue_ue.GizmoBaseVec2ParameterSource.md#constructor)

## Properties

### AxisSource

• **AxisSource**: [`GizmoAxisSource`](ue_ue.GizmoAxisSource.md)

___

### CurTranslationAxisX

• **CurTranslationAxisX**: [`Vector`](ue_ue_s.Vector.md)

___

### CurTranslationAxisY

• **CurTranslationAxisY**: [`Vector`](ue_ue_s.Vector.md)

___

### CurTranslationNormal

• **CurTranslationNormal**: [`Vector`](ue_ue_s.Vector.md)

___

### CurTranslationOrigin

• **CurTranslationOrigin**: [`Vector`](ue_ue_s.Vector.md)

___

### InitialTransform

• **InitialTransform**: [`Transform`](ue_ue_s.Transform.md)

___

### LastChange

• **LastChange**: [`GizmoVec2ParameterChange`](ue_ue.GizmoVec2ParameterChange.md)

___

### Parameter

• **Parameter**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### TransformSource

• **TransformSource**: [`GizmoTransformSource`](ue_ue.GizmoTransformSource.md)

___

### \_\_tid\_GizmoBaseVec2ParameterSource\_\_

• **\_\_tid\_GizmoBaseVec2ParameterSource\_\_**: `boolean`

#### Inherited from

[GizmoBaseVec2ParameterSource](ue_ue.GizmoBaseVec2ParameterSource.md).[__tid_GizmoBaseVec2ParameterSource__](ue_ue.GizmoBaseVec2ParameterSource.md#__tid_gizmobasevec2parametersource__)

___

### \_\_tid\_GizmoPlaneTranslationParameterSource\_\_

• **\_\_tid\_GizmoPlaneTranslationParameterSource\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GizmoBaseVec2ParameterSource](ue_ue.GizmoBaseVec2ParameterSource.md).[__tid_Object__](ue_ue.GizmoBaseVec2ParameterSource.md#__tid_object__)

## Methods

### CreateDefaultSubobject

▸ **CreateDefaultSubobject**(`p0`, `p1`, `p2`, `p3`, `p4`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `string` |
| `p1` | [`Class`](ue_ue.Class.md) |
| `p2` | [`Class`](ue_ue.Class.md) |
| `p3` | `boolean` |
| `p4` | `boolean` |

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GizmoBaseVec2ParameterSource](ue_ue.GizmoBaseVec2ParameterSource.md).[CreateDefaultSubobject](ue_ue.GizmoBaseVec2ParameterSource.md#createdefaultsubobject)

___

### ExecuteUbergraph

▸ **ExecuteUbergraph**(`EntryPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryPoint` | `number` |

#### Returns

`void`

#### Inherited from

[GizmoBaseVec2ParameterSource](ue_ue.GizmoBaseVec2ParameterSource.md).[ExecuteUbergraph](ue_ue.GizmoBaseVec2ParameterSource.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GizmoBaseVec2ParameterSource](ue_ue.GizmoBaseVec2ParameterSource.md).[GetClass](ue_ue.GizmoBaseVec2ParameterSource.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GizmoBaseVec2ParameterSource](ue_ue.GizmoBaseVec2ParameterSource.md).[GetName](ue_ue.GizmoBaseVec2ParameterSource.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GizmoBaseVec2ParameterSource](ue_ue.GizmoBaseVec2ParameterSource.md).[GetOuter](ue_ue.GizmoBaseVec2ParameterSource.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GizmoBaseVec2ParameterSource](ue_ue.GizmoBaseVec2ParameterSource.md).[GetWorld](ue_ue.GizmoBaseVec2ParameterSource.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GizmoPlaneTranslationParameterSource`](ue_ue.GizmoPlaneTranslationParameterSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GizmoPlaneTranslationParameterSource`](ue_ue.GizmoPlaneTranslationParameterSource.md)

#### Overrides

[GizmoBaseVec2ParameterSource](ue_ue.GizmoBaseVec2ParameterSource.md).[Find](ue_ue.GizmoBaseVec2ParameterSource.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GizmoPlaneTranslationParameterSource`](ue_ue.GizmoPlaneTranslationParameterSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GizmoPlaneTranslationParameterSource`](ue_ue.GizmoPlaneTranslationParameterSource.md)

#### Overrides

[GizmoBaseVec2ParameterSource](ue_ue.GizmoBaseVec2ParameterSource.md).[Load](ue_ue.GizmoBaseVec2ParameterSource.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GizmoBaseVec2ParameterSource](ue_ue.GizmoBaseVec2ParameterSource.md).[StaticClass](ue_ue.GizmoBaseVec2ParameterSource.md#staticclass)
