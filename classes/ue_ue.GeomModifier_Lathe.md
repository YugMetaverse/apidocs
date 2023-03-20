[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GeomModifier\_Lathe

# Class: GeomModifier\_Lathe

[ue/ue](../modules/ue_ue.md).GeomModifier_Lathe

## Hierarchy

- [`GeomModifier_Edit`](ue_ue.GeomModifier_Edit.md)

  ↳ **`GeomModifier_Lathe`**

## Table of contents

### Constructors

- [constructor](ue_ue.GeomModifier_Lathe.md#constructor)

### Properties

- [AlignToSide](ue_ue.GeomModifier_Lathe.md#aligntoside)
- [Axis](ue_ue.GeomModifier_Lathe.md#axis)
- [CachedPolys](ue_ue.GeomModifier_Lathe.md#cachedpolys)
- [Description](ue_ue.GeomModifier_Lathe.md#description)
- [Segments](ue_ue.GeomModifier_Lathe.md#segments)
- [Tooltip](ue_ue.GeomModifier_Lathe.md#tooltip)
- [TotalSegments](ue_ue.GeomModifier_Lathe.md#totalsegments)
- [\_\_tid\_GeomModifier\_Edit\_\_](ue_ue.GeomModifier_Lathe.md#__tid_geommodifier_edit__)
- [\_\_tid\_GeomModifier\_Lathe\_\_](ue_ue.GeomModifier_Lathe.md#__tid_geommodifier_lathe__)
- [\_\_tid\_GeomModifier\_\_](ue_ue.GeomModifier_Lathe.md#__tid_geommodifier__)
- [\_\_tid\_Object\_\_](ue_ue.GeomModifier_Lathe.md#__tid_object__)
- [bInitialized](ue_ue.GeomModifier_Lathe.md#binitialized)
- [bPendingPivotOffsetUpdate](ue_ue.GeomModifier_Lathe.md#bpendingpivotoffsetupdate)
- [bPushButton](ue_ue.GeomModifier_Lathe.md#bpushbutton)

### Methods

- [CreateDefaultSubobject](ue_ue.GeomModifier_Lathe.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GeomModifier_Lathe.md#executeubergraph)
- [GetClass](ue_ue.GeomModifier_Lathe.md#getclass)
- [GetName](ue_ue.GeomModifier_Lathe.md#getname)
- [GetOuter](ue_ue.GeomModifier_Lathe.md#getouter)
- [GetWorld](ue_ue.GeomModifier_Lathe.md#getworld)
- [Find](ue_ue.GeomModifier_Lathe.md#find)
- [Load](ue_ue.GeomModifier_Lathe.md#load)
- [StaticClass](ue_ue.GeomModifier_Lathe.md#staticclass)

## Constructors

### constructor

• **new GeomModifier_Lathe**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[constructor](ue_ue.GeomModifier_Edit.md#constructor)

#### Defined in

[ue/ue.d.ts:37794](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37794)

## Properties

### AlignToSide

• **AlignToSide**: `boolean`

#### Defined in

[ue/ue.d.ts:37797](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37797)

___

### Axis

• **Axis**: [`EAxis`](../enums/ue_ue.EAxis.md)

#### Defined in

[ue/ue.d.ts:37798](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37798)

___

### CachedPolys

• **CachedPolys**: [`Polys`](ue_ue.Polys.md)

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[CachedPolys](ue_ue.GeomModifier_Edit.md#cachedpolys)

#### Defined in

[ue/ue.d.ts:37724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37724)

___

### Description

• **Description**: `string`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[Description](ue_ue.GeomModifier_Edit.md#description)

#### Defined in

[ue/ue.d.ts:37719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37719)

___

### Segments

• **Segments**: `number`

#### Defined in

[ue/ue.d.ts:37796](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37796)

___

### Tooltip

• **Tooltip**: `string`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[Tooltip](ue_ue.GeomModifier_Edit.md#tooltip)

#### Defined in

[ue/ue.d.ts:37720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37720)

___

### TotalSegments

• **TotalSegments**: `number`

#### Defined in

[ue/ue.d.ts:37795](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37795)

___

### \_\_tid\_GeomModifier\_Edit\_\_

• **\_\_tid\_GeomModifier\_Edit\_\_**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[__tid_GeomModifier_Edit__](ue_ue.GeomModifier_Edit.md#__tid_geommodifier_edit__)

#### Defined in

[ue/ue.d.ts:37738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37738)

___

### \_\_tid\_GeomModifier\_Lathe\_\_

• **\_\_tid\_GeomModifier\_Lathe\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:37803](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37803)

___

### \_\_tid\_GeomModifier\_\_

• **\_\_tid\_GeomModifier\_\_**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[__tid_GeomModifier__](ue_ue.GeomModifier_Edit.md#__tid_geommodifier__)

#### Defined in

[ue/ue.d.ts:37729](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37729)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[__tid_Object__](ue_ue.GeomModifier_Edit.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bInitialized

• **bInitialized**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[bInitialized](ue_ue.GeomModifier_Edit.md#binitialized)

#### Defined in

[ue/ue.d.ts:37722](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37722)

___

### bPendingPivotOffsetUpdate

• **bPendingPivotOffsetUpdate**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[bPendingPivotOffsetUpdate](ue_ue.GeomModifier_Edit.md#bpendingpivotoffsetupdate)

#### Defined in

[ue/ue.d.ts:37723](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37723)

___

### bPushButton

• **bPushButton**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[bPushButton](ue_ue.GeomModifier_Edit.md#bpushbutton)

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

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[CreateDefaultSubobject](ue_ue.GeomModifier_Edit.md#createdefaultsubobject)

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

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[ExecuteUbergraph](ue_ue.GeomModifier_Edit.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[GetClass](ue_ue.GeomModifier_Edit.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[GetName](ue_ue.GeomModifier_Edit.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[GetOuter](ue_ue.GeomModifier_Edit.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[GetWorld](ue_ue.GeomModifier_Edit.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GeomModifier_Lathe`](ue_ue.GeomModifier_Lathe.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GeomModifier_Lathe`](ue_ue.GeomModifier_Lathe.md)

#### Overrides

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[Find](ue_ue.GeomModifier_Edit.md#find)

#### Defined in

[ue/ue.d.ts:37800](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37800)

___

### Load

▸ `Static` **Load**(`InName`): [`GeomModifier_Lathe`](ue_ue.GeomModifier_Lathe.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GeomModifier_Lathe`](ue_ue.GeomModifier_Lathe.md)

#### Overrides

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[Load](ue_ue.GeomModifier_Edit.md#load)

#### Defined in

[ue/ue.d.ts:37801](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37801)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[StaticClass](ue_ue.GeomModifier_Edit.md#staticclass)

#### Defined in

[ue/ue.d.ts:37799](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37799)
