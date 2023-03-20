[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PoseAsset

# Class: PoseAsset

[ue/ue](../modules/ue_ue.md).PoseAsset

## Hierarchy

- [`AnimationAsset`](ue_ue.AnimationAsset.md)

  ↳ **`PoseAsset`**

## Table of contents

### Constructors

- [constructor](ue_ue.PoseAsset.md#constructor)

### Properties

- [AssetMappingTable](ue_ue.PoseAsset.md#assetmappingtable)
- [AssetUserData](ue_ue.PoseAsset.md#assetuserdata)
- [BasePoseIndex](ue_ue.PoseAsset.md#baseposeindex)
- [ChildrenAssets](ue_ue.PoseAsset.md#childrenassets)
- [MetaData](ue_ue.PoseAsset.md#metadata)
- [ParentAsset](ue_ue.PoseAsset.md#parentasset)
- [PoseContainer](ue_ue.PoseAsset.md#posecontainer)
- [PreviewPoseAsset](ue_ue.PoseAsset.md#previewposeasset)
- [PreviewSkeletalMesh](ue_ue.PoseAsset.md#previewskeletalmesh)
- [RetargetSource](ue_ue.PoseAsset.md#retargetsource)
- [Skeleton](ue_ue.PoseAsset.md#skeleton)
- [SourceAnimation](ue_ue.PoseAsset.md#sourceanimation)
- [ThumbnailInfo](ue_ue.PoseAsset.md#thumbnailinfo)
- [\_\_tid\_AnimationAsset\_\_](ue_ue.PoseAsset.md#__tid_animationasset__)
- [\_\_tid\_Object\_\_](ue_ue.PoseAsset.md#__tid_object__)
- [\_\_tid\_PoseAsset\_\_](ue_ue.PoseAsset.md#__tid_poseasset__)
- [bAdditivePose](ue_ue.PoseAsset.md#badditivepose)

### Methods

- [CreateDefaultSubobject](ue_ue.PoseAsset.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PoseAsset.md#executeubergraph)
- [GetClass](ue_ue.PoseAsset.md#getclass)
- [GetName](ue_ue.PoseAsset.md#getname)
- [GetOuter](ue_ue.PoseAsset.md#getouter)
- [GetWorld](ue_ue.PoseAsset.md#getworld)
- [Find](ue_ue.PoseAsset.md#find)
- [Load](ue_ue.PoseAsset.md#load)
- [StaticClass](ue_ue.PoseAsset.md#staticclass)

## Constructors

### constructor

• **new PoseAsset**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimationAsset](ue_ue.AnimationAsset.md).[constructor](ue_ue.AnimationAsset.md#constructor)

## Properties

### AssetMappingTable

• **AssetMappingTable**: [`AssetMappingTable`](ue_ue.AssetMappingTable.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[AssetMappingTable](ue_ue.AnimationAsset.md#assetmappingtable)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[AssetUserData](ue_ue.AnimationAsset.md#assetuserdata)

___

### BasePoseIndex

• **BasePoseIndex**: `number`

___

### ChildrenAssets

• **ChildrenAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationAsset`](ue_ue.AnimationAsset.md)\>

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[ChildrenAssets](ue_ue.AnimationAsset.md#childrenassets)

___

### MetaData

• **MetaData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\>

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[MetaData](ue_ue.AnimationAsset.md#metadata)

___

### ParentAsset

• **ParentAsset**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[ParentAsset](ue_ue.AnimationAsset.md#parentasset)

___

### PoseContainer

• **PoseContainer**: [`PoseDataContainer`](ue_ue.PoseDataContainer.md)

___

### PreviewPoseAsset

• **PreviewPoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[PreviewPoseAsset](ue_ue.AnimationAsset.md#previewposeasset)

___

### PreviewSkeletalMesh

• **PreviewSkeletalMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[PreviewSkeletalMesh](ue_ue.AnimationAsset.md#previewskeletalmesh)

___

### RetargetSource

• **RetargetSource**: `string`

___

### Skeleton

• **Skeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[Skeleton](ue_ue.AnimationAsset.md#skeleton)

___

### SourceAnimation

• **SourceAnimation**: [`AnimSequence`](ue_ue.AnimSequence.md)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[ThumbnailInfo](ue_ue.AnimationAsset.md#thumbnailinfo)

___

### \_\_tid\_AnimationAsset\_\_

• **\_\_tid\_AnimationAsset\_\_**: `boolean`

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[__tid_AnimationAsset__](ue_ue.AnimationAsset.md#__tid_animationasset__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[__tid_Object__](ue_ue.AnimationAsset.md#__tid_object__)

___

### \_\_tid\_PoseAsset\_\_

• **\_\_tid\_PoseAsset\_\_**: `boolean`

___

### bAdditivePose

• **bAdditivePose**: `boolean`

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

[AnimationAsset](ue_ue.AnimationAsset.md).[CreateDefaultSubobject](ue_ue.AnimationAsset.md#createdefaultsubobject)

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

[AnimationAsset](ue_ue.AnimationAsset.md).[ExecuteUbergraph](ue_ue.AnimationAsset.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[GetClass](ue_ue.AnimationAsset.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[GetName](ue_ue.AnimationAsset.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[GetOuter](ue_ue.AnimationAsset.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimationAsset](ue_ue.AnimationAsset.md).[GetWorld](ue_ue.AnimationAsset.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PoseAsset`](ue_ue.PoseAsset.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PoseAsset`](ue_ue.PoseAsset.md)

#### Overrides

[AnimationAsset](ue_ue.AnimationAsset.md).[Find](ue_ue.AnimationAsset.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PoseAsset`](ue_ue.PoseAsset.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PoseAsset`](ue_ue.PoseAsset.md)

#### Overrides

[AnimationAsset](ue_ue.AnimationAsset.md).[Load](ue_ue.AnimationAsset.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimationAsset](ue_ue.AnimationAsset.md).[StaticClass](ue_ue.AnimationAsset.md#staticclass)
