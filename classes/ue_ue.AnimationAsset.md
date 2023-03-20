[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimationAsset

# Class: AnimationAsset

[ue/ue](../modules/ue_ue.md).AnimationAsset

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AnimationAsset`**

  ↳↳ [`PoseAsset`](ue_ue.PoseAsset.md)

  ↳↳ [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)

  ↳↳ [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimationAsset.md#constructor)

### Properties

- [AssetMappingTable](ue_ue.AnimationAsset.md#assetmappingtable)
- [AssetUserData](ue_ue.AnimationAsset.md#assetuserdata)
- [ChildrenAssets](ue_ue.AnimationAsset.md#childrenassets)
- [MetaData](ue_ue.AnimationAsset.md#metadata)
- [ParentAsset](ue_ue.AnimationAsset.md#parentasset)
- [PreviewPoseAsset](ue_ue.AnimationAsset.md#previewposeasset)
- [PreviewSkeletalMesh](ue_ue.AnimationAsset.md#previewskeletalmesh)
- [Skeleton](ue_ue.AnimationAsset.md#skeleton)
- [ThumbnailInfo](ue_ue.AnimationAsset.md#thumbnailinfo)
- [\_\_tid\_AnimationAsset\_\_](ue_ue.AnimationAsset.md#__tid_animationasset__)
- [\_\_tid\_Object\_\_](ue_ue.AnimationAsset.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimationAsset.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimationAsset.md#executeubergraph)
- [GetClass](ue_ue.AnimationAsset.md#getclass)
- [GetName](ue_ue.AnimationAsset.md#getname)
- [GetOuter](ue_ue.AnimationAsset.md#getouter)
- [GetWorld](ue_ue.AnimationAsset.md#getworld)
- [Find](ue_ue.AnimationAsset.md#find)
- [Load](ue_ue.AnimationAsset.md#load)
- [StaticClass](ue_ue.AnimationAsset.md#staticclass)

## Constructors

### constructor

• **new AnimationAsset**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AssetMappingTable

• **AssetMappingTable**: [`AssetMappingTable`](ue_ue.AssetMappingTable.md)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

___

### ChildrenAssets

• **ChildrenAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationAsset`](ue_ue.AnimationAsset.md)\>

___

### MetaData

• **MetaData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\>

___

### ParentAsset

• **ParentAsset**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

___

### PreviewPoseAsset

• **PreviewPoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

___

### PreviewSkeletalMesh

• **PreviewSkeletalMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

___

### Skeleton

• **Skeleton**: [`Skeleton`](ue_ue.Skeleton.md)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

___

### \_\_tid\_AnimationAsset\_\_

• **\_\_tid\_AnimationAsset\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
