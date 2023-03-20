[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GeomModifier\_Edit

# Class: GeomModifier\_Edit

[ue/ue](../modules/ue_ue.md).GeomModifier_Edit

## Hierarchy

- [`GeomModifier`](ue_ue.GeomModifier.md)

  ↳ **`GeomModifier_Edit`**

  ↳↳ [`GeomModifier_Clip`](ue_ue.GeomModifier_Clip.md)

  ↳↳ [`GeomModifier_Create`](ue_ue.GeomModifier_Create.md)

  ↳↳ [`GeomModifier_Delete`](ue_ue.GeomModifier_Delete.md)

  ↳↳ [`GeomModifier_Extrude`](ue_ue.GeomModifier_Extrude.md)

  ↳↳ [`GeomModifier_Flip`](ue_ue.GeomModifier_Flip.md)

  ↳↳ [`GeomModifier_Lathe`](ue_ue.GeomModifier_Lathe.md)

  ↳↳ [`GeomModifier_Triangulate`](ue_ue.GeomModifier_Triangulate.md)

  ↳↳ [`GeomModifier_Pen`](ue_ue.GeomModifier_Pen.md)

  ↳↳ [`GeomModifier_Split`](ue_ue.GeomModifier_Split.md)

  ↳↳ [`GeomModifier_Turn`](ue_ue.GeomModifier_Turn.md)

  ↳↳ [`GeomModifier_Weld`](ue_ue.GeomModifier_Weld.md)

## Table of contents

### Constructors

- [constructor](ue_ue.GeomModifier_Edit.md#constructor)

### Properties

- [CachedPolys](ue_ue.GeomModifier_Edit.md#cachedpolys)
- [Description](ue_ue.GeomModifier_Edit.md#description)
- [Tooltip](ue_ue.GeomModifier_Edit.md#tooltip)
- [\_\_tid\_GeomModifier\_Edit\_\_](ue_ue.GeomModifier_Edit.md#__tid_geommodifier_edit__)
- [\_\_tid\_GeomModifier\_\_](ue_ue.GeomModifier_Edit.md#__tid_geommodifier__)
- [\_\_tid\_Object\_\_](ue_ue.GeomModifier_Edit.md#__tid_object__)
- [bInitialized](ue_ue.GeomModifier_Edit.md#binitialized)
- [bPendingPivotOffsetUpdate](ue_ue.GeomModifier_Edit.md#bpendingpivotoffsetupdate)
- [bPushButton](ue_ue.GeomModifier_Edit.md#bpushbutton)

### Methods

- [CreateDefaultSubobject](ue_ue.GeomModifier_Edit.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GeomModifier_Edit.md#executeubergraph)
- [GetClass](ue_ue.GeomModifier_Edit.md#getclass)
- [GetName](ue_ue.GeomModifier_Edit.md#getname)
- [GetOuter](ue_ue.GeomModifier_Edit.md#getouter)
- [GetWorld](ue_ue.GeomModifier_Edit.md#getworld)
- [Find](ue_ue.GeomModifier_Edit.md#find)
- [Load](ue_ue.GeomModifier_Edit.md#load)
- [StaticClass](ue_ue.GeomModifier_Edit.md#staticclass)

## Constructors

### constructor

• **new GeomModifier_Edit**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GeomModifier](ue_ue.GeomModifier.md).[constructor](ue_ue.GeomModifier.md#constructor)

#### Defined in

[ue/ue.d.ts:37733](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37733)

## Properties

### CachedPolys

• **CachedPolys**: [`Polys`](ue_ue.Polys.md)

#### Inherited from

[GeomModifier](ue_ue.GeomModifier.md).[CachedPolys](ue_ue.GeomModifier.md#cachedpolys)

#### Defined in

[ue/ue.d.ts:37724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37724)

___

### Description

• **Description**: `string`

#### Inherited from

[GeomModifier](ue_ue.GeomModifier.md).[Description](ue_ue.GeomModifier.md#description)

#### Defined in

[ue/ue.d.ts:37719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37719)

___

### Tooltip

• **Tooltip**: `string`

#### Inherited from

[GeomModifier](ue_ue.GeomModifier.md).[Tooltip](ue_ue.GeomModifier.md#tooltip)

#### Defined in

[ue/ue.d.ts:37720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37720)

___

### \_\_tid\_GeomModifier\_Edit\_\_

• **\_\_tid\_GeomModifier\_Edit\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:37738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37738)

___

### \_\_tid\_GeomModifier\_\_

• **\_\_tid\_GeomModifier\_\_**: `boolean`

#### Inherited from

[GeomModifier](ue_ue.GeomModifier.md).[__tid_GeomModifier__](ue_ue.GeomModifier.md#__tid_geommodifier__)

#### Defined in

[ue/ue.d.ts:37729](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37729)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GeomModifier](ue_ue.GeomModifier.md).[__tid_Object__](ue_ue.GeomModifier.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bInitialized

• **bInitialized**: `boolean`

#### Inherited from

[GeomModifier](ue_ue.GeomModifier.md).[bInitialized](ue_ue.GeomModifier.md#binitialized)

#### Defined in

[ue/ue.d.ts:37722](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37722)

___

### bPendingPivotOffsetUpdate

• **bPendingPivotOffsetUpdate**: `boolean`

#### Inherited from

[GeomModifier](ue_ue.GeomModifier.md).[bPendingPivotOffsetUpdate](ue_ue.GeomModifier.md#bpendingpivotoffsetupdate)

#### Defined in

[ue/ue.d.ts:37723](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37723)

___

### bPushButton

• **bPushButton**: `boolean`

#### Inherited from

[GeomModifier](ue_ue.GeomModifier.md).[bPushButton](ue_ue.GeomModifier.md#bpushbutton)

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

[GeomModifier](ue_ue.GeomModifier.md).[CreateDefaultSubobject](ue_ue.GeomModifier.md#createdefaultsubobject)

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

[GeomModifier](ue_ue.GeomModifier.md).[ExecuteUbergraph](ue_ue.GeomModifier.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GeomModifier](ue_ue.GeomModifier.md).[GetClass](ue_ue.GeomModifier.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GeomModifier](ue_ue.GeomModifier.md).[GetName](ue_ue.GeomModifier.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GeomModifier](ue_ue.GeomModifier.md).[GetOuter](ue_ue.GeomModifier.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GeomModifier](ue_ue.GeomModifier.md).[GetWorld](ue_ue.GeomModifier.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GeomModifier_Edit`](ue_ue.GeomModifier_Edit.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GeomModifier_Edit`](ue_ue.GeomModifier_Edit.md)

#### Overrides

[GeomModifier](ue_ue.GeomModifier.md).[Find](ue_ue.GeomModifier.md#find)

#### Defined in

[ue/ue.d.ts:37735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37735)

___

### Load

▸ `Static` **Load**(`InName`): [`GeomModifier_Edit`](ue_ue.GeomModifier_Edit.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GeomModifier_Edit`](ue_ue.GeomModifier_Edit.md)

#### Overrides

[GeomModifier](ue_ue.GeomModifier.md).[Load](ue_ue.GeomModifier.md#load)

#### Defined in

[ue/ue.d.ts:37736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37736)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GeomModifier](ue_ue.GeomModifier.md).[StaticClass](ue_ue.GeomModifier.md#staticclass)

#### Defined in

[ue/ue.d.ts:37734](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37734)
