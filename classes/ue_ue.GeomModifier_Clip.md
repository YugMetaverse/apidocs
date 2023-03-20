[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GeomModifier\_Clip

# Class: GeomModifier\_Clip

[ue/ue](../modules/ue_ue.md).GeomModifier_Clip

## Hierarchy

- [`GeomModifier_Edit`](ue_ue.GeomModifier_Edit.md)

  ↳ **`GeomModifier_Clip`**

## Table of contents

### Constructors

- [constructor](ue_ue.GeomModifier_Clip.md#constructor)

### Properties

- [CachedPolys](ue_ue.GeomModifier_Clip.md#cachedpolys)
- [ClipMarkers](ue_ue.GeomModifier_Clip.md#clipmarkers)
- [Description](ue_ue.GeomModifier_Clip.md#description)
- [SnappedMouseWorldSpacePos](ue_ue.GeomModifier_Clip.md#snappedmouseworldspacepos)
- [Tooltip](ue_ue.GeomModifier_Clip.md#tooltip)
- [\_\_tid\_GeomModifier\_Clip\_\_](ue_ue.GeomModifier_Clip.md#__tid_geommodifier_clip__)
- [\_\_tid\_GeomModifier\_Edit\_\_](ue_ue.GeomModifier_Clip.md#__tid_geommodifier_edit__)
- [\_\_tid\_GeomModifier\_\_](ue_ue.GeomModifier_Clip.md#__tid_geommodifier__)
- [\_\_tid\_Object\_\_](ue_ue.GeomModifier_Clip.md#__tid_object__)
- [bFlipNormal](ue_ue.GeomModifier_Clip.md#bflipnormal)
- [bInitialized](ue_ue.GeomModifier_Clip.md#binitialized)
- [bPendingPivotOffsetUpdate](ue_ue.GeomModifier_Clip.md#bpendingpivotoffsetupdate)
- [bPushButton](ue_ue.GeomModifier_Clip.md#bpushbutton)
- [bSplit](ue_ue.GeomModifier_Clip.md#bsplit)

### Methods

- [CreateDefaultSubobject](ue_ue.GeomModifier_Clip.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GeomModifier_Clip.md#executeubergraph)
- [GetClass](ue_ue.GeomModifier_Clip.md#getclass)
- [GetName](ue_ue.GeomModifier_Clip.md#getname)
- [GetOuter](ue_ue.GeomModifier_Clip.md#getouter)
- [GetWorld](ue_ue.GeomModifier_Clip.md#getworld)
- [Find](ue_ue.GeomModifier_Clip.md#find)
- [Load](ue_ue.GeomModifier_Clip.md#load)
- [StaticClass](ue_ue.GeomModifier_Clip.md#staticclass)

## Constructors

### constructor

• **new GeomModifier_Clip**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[constructor](ue_ue.GeomModifier_Edit.md#constructor)

## Properties

### CachedPolys

• **CachedPolys**: [`Polys`](ue_ue.Polys.md)

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[CachedPolys](ue_ue.GeomModifier_Edit.md#cachedpolys)

___

### ClipMarkers

• **ClipMarkers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

___

### Description

• **Description**: `string`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[Description](ue_ue.GeomModifier_Edit.md#description)

___

### SnappedMouseWorldSpacePos

• **SnappedMouseWorldSpacePos**: [`Vector`](ue_ue_s.Vector.md)

___

### Tooltip

• **Tooltip**: `string`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[Tooltip](ue_ue.GeomModifier_Edit.md#tooltip)

___

### \_\_tid\_GeomModifier\_Clip\_\_

• **\_\_tid\_GeomModifier\_Clip\_\_**: `boolean`

___

### \_\_tid\_GeomModifier\_Edit\_\_

• **\_\_tid\_GeomModifier\_Edit\_\_**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[__tid_GeomModifier_Edit__](ue_ue.GeomModifier_Edit.md#__tid_geommodifier_edit__)

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

### bFlipNormal

• **bFlipNormal**: `boolean`

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

___

### bSplit

• **bSplit**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GeomModifier_Clip`](ue_ue.GeomModifier_Clip.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GeomModifier_Clip`](ue_ue.GeomModifier_Clip.md)

#### Overrides

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[Find](ue_ue.GeomModifier_Edit.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GeomModifier_Clip`](ue_ue.GeomModifier_Clip.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GeomModifier_Clip`](ue_ue.GeomModifier_Clip.md)

#### Overrides

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[Load](ue_ue.GeomModifier_Edit.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[StaticClass](ue_ue.GeomModifier_Edit.md#staticclass)
