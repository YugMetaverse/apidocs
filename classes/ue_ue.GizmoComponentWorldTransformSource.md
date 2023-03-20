[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GizmoComponentWorldTransformSource

# Class: GizmoComponentWorldTransformSource

[ue/ue](../modules/ue_ue.md).GizmoComponentWorldTransformSource

## Hierarchy

- [`GizmoBaseTransformSource`](ue_ue.GizmoBaseTransformSource.md)

  ↳ **`GizmoComponentWorldTransformSource`**

## Table of contents

### Constructors

- [constructor](ue_ue.GizmoComponentWorldTransformSource.md#constructor)

### Properties

- [Component](ue_ue.GizmoComponentWorldTransformSource.md#component)
- [\_\_tid\_GizmoBaseTransformSource\_\_](ue_ue.GizmoComponentWorldTransformSource.md#__tid_gizmobasetransformsource__)
- [\_\_tid\_GizmoComponentWorldTransformSource\_\_](ue_ue.GizmoComponentWorldTransformSource.md#__tid_gizmocomponentworldtransformsource__)
- [\_\_tid\_Object\_\_](ue_ue.GizmoComponentWorldTransformSource.md#__tid_object__)
- [bModifyComponentOnTransform](ue_ue.GizmoComponentWorldTransformSource.md#bmodifycomponentontransform)

### Methods

- [CreateDefaultSubobject](ue_ue.GizmoComponentWorldTransformSource.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GizmoComponentWorldTransformSource.md#executeubergraph)
- [GetClass](ue_ue.GizmoComponentWorldTransformSource.md#getclass)
- [GetName](ue_ue.GizmoComponentWorldTransformSource.md#getname)
- [GetOuter](ue_ue.GizmoComponentWorldTransformSource.md#getouter)
- [GetWorld](ue_ue.GizmoComponentWorldTransformSource.md#getworld)
- [Find](ue_ue.GizmoComponentWorldTransformSource.md#find)
- [Load](ue_ue.GizmoComponentWorldTransformSource.md#load)
- [StaticClass](ue_ue.GizmoComponentWorldTransformSource.md#staticclass)

## Constructors

### constructor

• **new GizmoComponentWorldTransformSource**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GizmoBaseTransformSource](ue_ue.GizmoBaseTransformSource.md).[constructor](ue_ue.GizmoBaseTransformSource.md#constructor)

## Properties

### Component

• **Component**: [`SceneComponent`](ue_ue.SceneComponent.md)

___

### \_\_tid\_GizmoBaseTransformSource\_\_

• **\_\_tid\_GizmoBaseTransformSource\_\_**: `boolean`

#### Inherited from

[GizmoBaseTransformSource](ue_ue.GizmoBaseTransformSource.md).[__tid_GizmoBaseTransformSource__](ue_ue.GizmoBaseTransformSource.md#__tid_gizmobasetransformsource__)

___

### \_\_tid\_GizmoComponentWorldTransformSource\_\_

• **\_\_tid\_GizmoComponentWorldTransformSource\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GizmoBaseTransformSource](ue_ue.GizmoBaseTransformSource.md).[__tid_Object__](ue_ue.GizmoBaseTransformSource.md#__tid_object__)

___

### bModifyComponentOnTransform

• **bModifyComponentOnTransform**: `boolean`

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

[GizmoBaseTransformSource](ue_ue.GizmoBaseTransformSource.md).[CreateDefaultSubobject](ue_ue.GizmoBaseTransformSource.md#createdefaultsubobject)

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

[GizmoBaseTransformSource](ue_ue.GizmoBaseTransformSource.md).[ExecuteUbergraph](ue_ue.GizmoBaseTransformSource.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GizmoBaseTransformSource](ue_ue.GizmoBaseTransformSource.md).[GetClass](ue_ue.GizmoBaseTransformSource.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GizmoBaseTransformSource](ue_ue.GizmoBaseTransformSource.md).[GetName](ue_ue.GizmoBaseTransformSource.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GizmoBaseTransformSource](ue_ue.GizmoBaseTransformSource.md).[GetOuter](ue_ue.GizmoBaseTransformSource.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GizmoBaseTransformSource](ue_ue.GizmoBaseTransformSource.md).[GetWorld](ue_ue.GizmoBaseTransformSource.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GizmoComponentWorldTransformSource`](ue_ue.GizmoComponentWorldTransformSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GizmoComponentWorldTransformSource`](ue_ue.GizmoComponentWorldTransformSource.md)

#### Overrides

[GizmoBaseTransformSource](ue_ue.GizmoBaseTransformSource.md).[Find](ue_ue.GizmoBaseTransformSource.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GizmoComponentWorldTransformSource`](ue_ue.GizmoComponentWorldTransformSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GizmoComponentWorldTransformSource`](ue_ue.GizmoComponentWorldTransformSource.md)

#### Overrides

[GizmoBaseTransformSource](ue_ue.GizmoBaseTransformSource.md).[Load](ue_ue.GizmoBaseTransformSource.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GizmoBaseTransformSource](ue_ue.GizmoBaseTransformSource.md).[StaticClass](ue_ue.GizmoBaseTransformSource.md#staticclass)
