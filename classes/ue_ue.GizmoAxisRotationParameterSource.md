[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GizmoAxisRotationParameterSource

# Class: GizmoAxisRotationParameterSource

[ue/ue](../modules/ue_ue.md).GizmoAxisRotationParameterSource

## Hierarchy

- [`GizmoBaseFloatParameterSource`](ue_ue.GizmoBaseFloatParameterSource.md)

  ↳ **`GizmoAxisRotationParameterSource`**

## Table of contents

### Constructors

- [constructor](ue_ue.GizmoAxisRotationParameterSource.md#constructor)

### Properties

- [Angle](ue_ue.GizmoAxisRotationParameterSource.md#angle)
- [AxisSource](ue_ue.GizmoAxisRotationParameterSource.md#axissource)
- [CurRotationAxis](ue_ue.GizmoAxisRotationParameterSource.md#currotationaxis)
- [CurRotationOrigin](ue_ue.GizmoAxisRotationParameterSource.md#currotationorigin)
- [InitialTransform](ue_ue.GizmoAxisRotationParameterSource.md#initialtransform)
- [LastChange](ue_ue.GizmoAxisRotationParameterSource.md#lastchange)
- [TransformSource](ue_ue.GizmoAxisRotationParameterSource.md#transformsource)
- [\_\_tid\_GizmoAxisRotationParameterSource\_\_](ue_ue.GizmoAxisRotationParameterSource.md#__tid_gizmoaxisrotationparametersource__)
- [\_\_tid\_GizmoBaseFloatParameterSource\_\_](ue_ue.GizmoAxisRotationParameterSource.md#__tid_gizmobasefloatparametersource__)
- [\_\_tid\_Object\_\_](ue_ue.GizmoAxisRotationParameterSource.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.GizmoAxisRotationParameterSource.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GizmoAxisRotationParameterSource.md#executeubergraph)
- [GetClass](ue_ue.GizmoAxisRotationParameterSource.md#getclass)
- [GetName](ue_ue.GizmoAxisRotationParameterSource.md#getname)
- [GetOuter](ue_ue.GizmoAxisRotationParameterSource.md#getouter)
- [GetWorld](ue_ue.GizmoAxisRotationParameterSource.md#getworld)
- [Find](ue_ue.GizmoAxisRotationParameterSource.md#find)
- [Load](ue_ue.GizmoAxisRotationParameterSource.md#load)
- [StaticClass](ue_ue.GizmoAxisRotationParameterSource.md#staticclass)

## Constructors

### constructor

• **new GizmoAxisRotationParameterSource**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GizmoBaseFloatParameterSource](ue_ue.GizmoBaseFloatParameterSource.md).[constructor](ue_ue.GizmoBaseFloatParameterSource.md#constructor)

## Properties

### Angle

• **Angle**: `number`

___

### AxisSource

• **AxisSource**: [`GizmoAxisSource`](ue_ue.GizmoAxisSource.md)

___

### CurRotationAxis

• **CurRotationAxis**: [`Vector`](ue_ue_s.Vector.md)

___

### CurRotationOrigin

• **CurRotationOrigin**: [`Vector`](ue_ue_s.Vector.md)

___

### InitialTransform

• **InitialTransform**: [`Transform`](ue_ue_s.Transform.md)

___

### LastChange

• **LastChange**: [`GizmoFloatParameterChange`](ue_ue.GizmoFloatParameterChange.md)

___

### TransformSource

• **TransformSource**: [`GizmoTransformSource`](ue_ue.GizmoTransformSource.md)

___

### \_\_tid\_GizmoAxisRotationParameterSource\_\_

• **\_\_tid\_GizmoAxisRotationParameterSource\_\_**: `boolean`

___

### \_\_tid\_GizmoBaseFloatParameterSource\_\_

• **\_\_tid\_GizmoBaseFloatParameterSource\_\_**: `boolean`

#### Inherited from

[GizmoBaseFloatParameterSource](ue_ue.GizmoBaseFloatParameterSource.md).[__tid_GizmoBaseFloatParameterSource__](ue_ue.GizmoBaseFloatParameterSource.md#__tid_gizmobasefloatparametersource__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GizmoBaseFloatParameterSource](ue_ue.GizmoBaseFloatParameterSource.md).[__tid_Object__](ue_ue.GizmoBaseFloatParameterSource.md#__tid_object__)

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

[GizmoBaseFloatParameterSource](ue_ue.GizmoBaseFloatParameterSource.md).[CreateDefaultSubobject](ue_ue.GizmoBaseFloatParameterSource.md#createdefaultsubobject)

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

[GizmoBaseFloatParameterSource](ue_ue.GizmoBaseFloatParameterSource.md).[ExecuteUbergraph](ue_ue.GizmoBaseFloatParameterSource.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GizmoBaseFloatParameterSource](ue_ue.GizmoBaseFloatParameterSource.md).[GetClass](ue_ue.GizmoBaseFloatParameterSource.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GizmoBaseFloatParameterSource](ue_ue.GizmoBaseFloatParameterSource.md).[GetName](ue_ue.GizmoBaseFloatParameterSource.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GizmoBaseFloatParameterSource](ue_ue.GizmoBaseFloatParameterSource.md).[GetOuter](ue_ue.GizmoBaseFloatParameterSource.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GizmoBaseFloatParameterSource](ue_ue.GizmoBaseFloatParameterSource.md).[GetWorld](ue_ue.GizmoBaseFloatParameterSource.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GizmoAxisRotationParameterSource`](ue_ue.GizmoAxisRotationParameterSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GizmoAxisRotationParameterSource`](ue_ue.GizmoAxisRotationParameterSource.md)

#### Overrides

[GizmoBaseFloatParameterSource](ue_ue.GizmoBaseFloatParameterSource.md).[Find](ue_ue.GizmoBaseFloatParameterSource.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GizmoAxisRotationParameterSource`](ue_ue.GizmoAxisRotationParameterSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GizmoAxisRotationParameterSource`](ue_ue.GizmoAxisRotationParameterSource.md)

#### Overrides

[GizmoBaseFloatParameterSource](ue_ue.GizmoBaseFloatParameterSource.md).[Load](ue_ue.GizmoBaseFloatParameterSource.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GizmoBaseFloatParameterSource](ue_ue.GizmoBaseFloatParameterSource.md).[StaticClass](ue_ue.GizmoBaseFloatParameterSource.md#staticclass)
