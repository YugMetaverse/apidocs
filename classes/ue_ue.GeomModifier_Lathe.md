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

## Properties

### AlignToSide

• **AlignToSide**: `boolean`

___

### Axis

• **Axis**: [`EAxis`](../enums/ue_ue.EAxis.md)

___

### CachedPolys

• **CachedPolys**: [`Polys`](ue_ue.Polys.md)

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[CachedPolys](ue_ue.GeomModifier_Edit.md#cachedpolys)

___

### Description

• **Description**: `string`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[Description](ue_ue.GeomModifier_Edit.md#description)

___

### Segments

• **Segments**: `number`

___

### Tooltip

• **Tooltip**: `string`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[Tooltip](ue_ue.GeomModifier_Edit.md#tooltip)

___

### TotalSegments

• **TotalSegments**: `number`

___

### \_\_tid\_GeomModifier\_Edit\_\_

• **\_\_tid\_GeomModifier\_Edit\_\_**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[__tid_GeomModifier_Edit__](ue_ue.GeomModifier_Edit.md#__tid_geommodifier_edit__)

___

### \_\_tid\_GeomModifier\_Lathe\_\_

• **\_\_tid\_GeomModifier\_Lathe\_\_**: `boolean`

___

### \_\_tid\_GeomModifier\_\_

• **\_\_tid\_GeomModifier\_\_**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[__tid_GeomModifier__](ue_ue.GeomModifier_Edit.md#__tid_geommodifier__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[__tid_Object__](ue_ue.GeomModifier_Edit.md#__tid_object__)

___

### bInitialized

• **bInitialized**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[bInitialized](ue_ue.GeomModifier_Edit.md#binitialized)

___

### bPendingPivotOffsetUpdate

• **bPendingPivotOffsetUpdate**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[bPendingPivotOffsetUpdate](ue_ue.GeomModifier_Edit.md#bpendingpivotoffsetupdate)

___

### bPushButton

• **bPushButton**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[bPushButton](ue_ue.GeomModifier_Edit.md#bpushbutton)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[GetClass](ue_ue.GeomModifier_Edit.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[GetName](ue_ue.GeomModifier_Edit.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[GetOuter](ue_ue.GeomModifier_Edit.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[GetWorld](ue_ue.GeomModifier_Edit.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[StaticClass](ue_ue.GeomModifier_Edit.md#staticclass)
