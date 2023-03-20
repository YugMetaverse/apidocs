[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GeomModifier

# Class: GeomModifier

[ue/ue](../modules/ue_ue.md).GeomModifier

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`GeomModifier`**

  ↳↳ [`GeomModifier_Edit`](ue_ue.GeomModifier_Edit.md)

## Table of contents

### Constructors

- [constructor](ue_ue.GeomModifier.md#constructor)

### Properties

- [CachedPolys](ue_ue.GeomModifier.md#cachedpolys)
- [Description](ue_ue.GeomModifier.md#description)
- [Tooltip](ue_ue.GeomModifier.md#tooltip)
- [\_\_tid\_GeomModifier\_\_](ue_ue.GeomModifier.md#__tid_geommodifier__)
- [\_\_tid\_Object\_\_](ue_ue.GeomModifier.md#__tid_object__)
- [bInitialized](ue_ue.GeomModifier.md#binitialized)
- [bPendingPivotOffsetUpdate](ue_ue.GeomModifier.md#bpendingpivotoffsetupdate)
- [bPushButton](ue_ue.GeomModifier.md#bpushbutton)

### Methods

- [CreateDefaultSubobject](ue_ue.GeomModifier.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GeomModifier.md#executeubergraph)
- [GetClass](ue_ue.GeomModifier.md#getclass)
- [GetName](ue_ue.GeomModifier.md#getname)
- [GetOuter](ue_ue.GeomModifier.md#getouter)
- [GetWorld](ue_ue.GeomModifier.md#getworld)
- [Find](ue_ue.GeomModifier.md#find)
- [Load](ue_ue.GeomModifier.md#load)
- [StaticClass](ue_ue.GeomModifier.md#staticclass)

## Constructors

### constructor

• **new GeomModifier**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### CachedPolys

• **CachedPolys**: [`Polys`](ue_ue.Polys.md)

___

### Description

• **Description**: `string`

___

### Tooltip

• **Tooltip**: `string`

___

### \_\_tid\_GeomModifier\_\_

• **\_\_tid\_GeomModifier\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bInitialized

• **bInitialized**: `boolean`

___

### bPendingPivotOffsetUpdate

• **bPendingPivotOffsetUpdate**: `boolean`

___

### bPushButton

• **bPushButton**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GeomModifier`](ue_ue.GeomModifier.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GeomModifier`](ue_ue.GeomModifier.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GeomModifier`](ue_ue.GeomModifier.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GeomModifier`](ue_ue.GeomModifier.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
