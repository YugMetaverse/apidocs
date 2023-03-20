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

#### Defined in

[ue/ue.d.ts:37816](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37816)

## Properties

### CachedPolys

• **CachedPolys**: [`Polys`](ue_ue.Polys.md)

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[CachedPolys](ue_ue.GeomModifier_Triangulate.md#cachedpolys)

#### Defined in

[ue/ue.d.ts:37724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37724)

___

### Description

• **Description**: `string`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[Description](ue_ue.GeomModifier_Triangulate.md#description)

#### Defined in

[ue/ue.d.ts:37719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37719)

___

### Tooltip

• **Tooltip**: `string`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[Tooltip](ue_ue.GeomModifier_Triangulate.md#tooltip)

#### Defined in

[ue/ue.d.ts:37720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37720)

___

### \_\_tid\_GeomModifier\_Edit\_\_

• **\_\_tid\_GeomModifier\_Edit\_\_**: `boolean`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[__tid_GeomModifier_Edit__](ue_ue.GeomModifier_Triangulate.md#__tid_geommodifier_edit__)

#### Defined in

[ue/ue.d.ts:37738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37738)

___

### \_\_tid\_GeomModifier\_Optimize\_\_

• **\_\_tid\_GeomModifier\_Optimize\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:37821](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37821)

___

### \_\_tid\_GeomModifier\_Triangulate\_\_

• **\_\_tid\_GeomModifier\_Triangulate\_\_**: `boolean`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[__tid_GeomModifier_Triangulate__](ue_ue.GeomModifier_Triangulate.md#__tid_geommodifier_triangulate__)

#### Defined in

[ue/ue.d.ts:37812](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37812)

___

### \_\_tid\_GeomModifier\_\_

• **\_\_tid\_GeomModifier\_\_**: `boolean`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[__tid_GeomModifier__](ue_ue.GeomModifier_Triangulate.md#__tid_geommodifier__)

#### Defined in

[ue/ue.d.ts:37729](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37729)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[__tid_Object__](ue_ue.GeomModifier_Triangulate.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bInitialized

• **bInitialized**: `boolean`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[bInitialized](ue_ue.GeomModifier_Triangulate.md#binitialized)

#### Defined in

[ue/ue.d.ts:37722](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37722)

___

### bPendingPivotOffsetUpdate

• **bPendingPivotOffsetUpdate**: `boolean`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[bPendingPivotOffsetUpdate](ue_ue.GeomModifier_Triangulate.md#bpendingpivotoffsetupdate)

#### Defined in

[ue/ue.d.ts:37723](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37723)

___

### bPushButton

• **bPushButton**: `boolean`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[bPushButton](ue_ue.GeomModifier_Triangulate.md#bpushbutton)

#### Defined in

[ue/ue.d.ts:37721](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37721)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[GetClass](ue_ue.GeomModifier_Triangulate.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[GetName](ue_ue.GeomModifier_Triangulate.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[GetOuter](ue_ue.GeomModifier_Triangulate.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[GetWorld](ue_ue.GeomModifier_Triangulate.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:37818](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37818)

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

#### Defined in

[ue/ue.d.ts:37819](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37819)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GeomModifier_Triangulate](ue_ue.GeomModifier_Triangulate.md).[StaticClass](ue_ue.GeomModifier_Triangulate.md#staticclass)

#### Defined in

[ue/ue.d.ts:37817](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37817)
