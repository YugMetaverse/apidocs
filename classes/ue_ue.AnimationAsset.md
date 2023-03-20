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

#### Defined in

[ue/ue.d.ts:2761](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2761)

## Properties

### AssetMappingTable

• **AssetMappingTable**: [`AssetMappingTable`](ue_ue.AssetMappingTable.md)

#### Defined in

[ue/ue.d.ts:2766](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2766)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Defined in

[ue/ue.d.ts:2767](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2767)

___

### ChildrenAssets

• **ChildrenAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationAsset`](ue_ue.AnimationAsset.md)\>

#### Defined in

[ue/ue.d.ts:2765](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2765)

___

### MetaData

• **MetaData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\>

#### Defined in

[ue/ue.d.ts:2763](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2763)

___

### ParentAsset

• **ParentAsset**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Defined in

[ue/ue.d.ts:2764](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2764)

___

### PreviewPoseAsset

• **PreviewPoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

#### Defined in

[ue/ue.d.ts:2769](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2769)

___

### PreviewSkeletalMesh

• **PreviewSkeletalMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

#### Defined in

[ue/ue.d.ts:2770](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2770)

___

### Skeleton

• **Skeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Defined in

[ue/ue.d.ts:2762](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2762)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Defined in

[ue/ue.d.ts:2768](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2768)

___

### \_\_tid\_AnimationAsset\_\_

• **\_\_tid\_AnimationAsset\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:2775](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2775)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:2772](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2772)

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

#### Defined in

[ue/ue.d.ts:2773](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2773)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:2771](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2771)