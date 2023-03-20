[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GeomModifier\_Optimize

# Class: GeomModifier\_Optimize

[ue/ue](../modules/ue_ue.md).GeomModifier_Optimize

## Hierarchy

- [`GeomModifier_Triangulate`](ue_ue.GeomModifier_Triangulate.md)

  ↳ **`GeomModifier_Optimize`**

## Table of contents

### Constructors

- [constructor](ue_ue.GeomModifier_Optimize.md#constructor)

### Properties

- [CachedPolys](ue_ue.GeomModifier_Optimize.md#cachedpolys)
- [Description](ue_ue.GeomModifier_Optimize.md#description)
- [Tooltip](ue_ue.GeomModifier_Optimize.md#tooltip)
- [\_\_tid\_GeomModifier\_Edit\_\_](ue_ue.GeomModifier_Optimize.md#__tid_geommodifier_edit__)
- [\_\_tid\_GeomModifier\_Optimize\_\_](ue_ue.GeomModifier_Optimize.md#__tid_geommodifier_optimize__)
- [\_\_tid\_GeomModifier\_Triangulate\_\_](ue_ue.GeomModifier_Optimize.md#__tid_geommodifier_triangulate__)
- [\_\_tid\_GeomModifier\_\_](ue_ue.GeomModifier_Optimize.md#__tid_geommodifier__)
- [\_\_tid\_Object\_\_](ue_ue.GeomModifier_Optimize.md#__tid_object__)
- [bInitialized](ue_ue.GeomModifier_Optimize.md#binitialized)
- [bPendingPivotOffsetUpdate](ue_ue.GeomModifier_Optimize.md#bpendingpivotoffsetupdate)
- [bPushButton](ue_ue.GeomModifier_Optimize.md#bpushbutton)

### Methods

- [CreateDefaultSubobject](ue_ue.GeomModifier_Optimize.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GeomModifier_Optimize.md#executeubergraph)
- [GetClass](ue_ue.GeomModifier_Optimize.md#getclass)
- [GetName](ue_ue.GeomModifier_Optimize.md#getname)
- [GetOuter](ue_ue.GeomModifier_Optimize.md#getouter)
- [GetWorld](ue_ue.GeomModifier_Optimize.md#getworld)
- [Find](ue_ue.GeomModifier_Optimize.md#find)
- [Load](ue_ue.GeomModifier_Optimize.md#load)
- [StaticClass](ue_ue.GeomModifier_Optimize.md#staticclass)

## Constructors

### constructor

• **new GeomModifier_Optimize**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[constructor](ue_ue.GeomModifier_Triangulate.md#constructor)

## Properties

### CachedPolys

• **CachedPolys**: [`Polys`](ue_ue.Polys.md)

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[CachedPolys](ue_ue.GeomModifier_Triangulate.md#cachedpolys)

___

### Description

• **Description**: `string`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[Description](ue_ue.GeomModifier_Triangulate.md#description)

___

### Tooltip

• **Tooltip**: `string`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[Tooltip](ue_ue.GeomModifier_Triangulate.md#tooltip)

___

### \_\_tid\_GeomModifier\_Edit\_\_

• **\_\_tid\_GeomModifier\_Edit\_\_**: `boolean`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[__tid_GeomModifier_Edit__](ue_ue.GeomModifier_Triangulate.md#__tid_geommodifier_edit__)

___

### \_\_tid\_GeomModifier\_Optimize\_\_

• **\_\_tid\_GeomModifier\_Optimize\_\_**: `boolean`

___

### \_\_tid\_GeomModifier\_Triangulate\_\_

• **\_\_tid\_GeomModifier\_Triangulate\_\_**: `boolean`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[__tid_GeomModifier_Triangulate__](ue_ue.GeomModifier_Triangulate.md#__tid_geommodifier_triangulate__)

___

### \_\_tid\_GeomModifier\_\_

• **\_\_tid\_GeomModifier\_\_**: `boolean`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[__tid_GeomModifier__](ue_ue.GeomModifier_Triangulate.md#__tid_geommodifier__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[__tid_Object__](ue_ue.GeomModifier_Triangulate.md#__tid_object__)

___

### bInitialized

• **bInitialized**: `boolean`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[bInitialized](ue_ue.GeomModifier_Triangulate.md#binitialized)

___

### bPendingPivotOffsetUpdate

• **bPendingPivotOffsetUpdate**: `boolean`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[bPendingPivotOffsetUpdate](ue_ue.GeomModifier_Triangulate.md#bpendingpivotoffsetupdate)

___

### bPushButton

• **bPushButton**: `boolean`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[bPushButton](ue_ue.GeomModifier_Triangulate.md#bpushbutton)

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

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[CreateDefaultSubobject](ue_ue.GeomModifier_Triangulate.md#createdefaultsubobject)

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

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[ExecuteUbergraph](ue_ue.GeomModifier_Triangulate.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[GetClass](ue_ue.GeomModifier_Triangulate.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[GetName](ue_ue.GeomModifier_Triangulate.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[GetOuter](ue_ue.GeomModifier_Triangulate.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[GetWorld](ue_ue.GeomModifier_Triangulate.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GeomModifier_Optimize`](ue_ue.GeomModifier_Optimize.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GeomModifier_Optimize`](ue_ue.GeomModifier_Optimize.md)

#### Overrides

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[Find](ue_ue.GeomModifier_Triangulate.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GeomModifier_Optimize`](ue_ue.GeomModifier_Optimize.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GeomModifier_Optimize`](ue_ue.GeomModifier_Optimize.md)

#### Overrides

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[Load](ue_ue.GeomModifier_Triangulate.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[StaticClass](ue_ue.GeomModifier_Triangulate.md#staticclass)
