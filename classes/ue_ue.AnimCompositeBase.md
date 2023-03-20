[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimCompositeBase

# Class: AnimCompositeBase

[ue/ue](../modules/ue_ue.md).AnimCompositeBase

## Hierarchy

- [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)

  ↳ **`AnimCompositeBase`**

  ↳↳ [`AnimMontage`](ue_ue.AnimMontage.md)

  ↳↳ [`AnimComposite`](ue_ue.AnimComposite.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimCompositeBase.md#constructor)

### Properties

- [AnimNotifyTracks](ue_ue.AnimCompositeBase.md#animnotifytracks)
- [AssetMappingTable](ue_ue.AnimCompositeBase.md#assetmappingtable)
- [AssetUserData](ue_ue.AnimCompositeBase.md#assetuserdata)
- [ChildrenAssets](ue_ue.AnimCompositeBase.md#childrenassets)
- [MetaData](ue_ue.AnimCompositeBase.md#metadata)
- [Notifies](ue_ue.AnimCompositeBase.md#notifies)
- [ParentAsset](ue_ue.AnimCompositeBase.md#parentasset)
- [PreviewPoseAsset](ue_ue.AnimCompositeBase.md#previewposeasset)
- [PreviewSkeletalMesh](ue_ue.AnimCompositeBase.md#previewskeletalmesh)
- [RateScale](ue_ue.AnimCompositeBase.md#ratescale)
- [RawCurveData](ue_ue.AnimCompositeBase.md#rawcurvedata)
- [SequenceLength](ue_ue.AnimCompositeBase.md#sequencelength)
- [Skeleton](ue_ue.AnimCompositeBase.md#skeleton)
- [ThumbnailInfo](ue_ue.AnimCompositeBase.md#thumbnailinfo)
- [\_\_tid\_AnimCompositeBase\_\_](ue_ue.AnimCompositeBase.md#__tid_animcompositebase__)
- [\_\_tid\_AnimSequenceBase\_\_](ue_ue.AnimCompositeBase.md#__tid_animsequencebase__)
- [\_\_tid\_AnimationAsset\_\_](ue_ue.AnimCompositeBase.md#__tid_animationasset__)
- [\_\_tid\_Object\_\_](ue_ue.AnimCompositeBase.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimCompositeBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimCompositeBase.md#executeubergraph)
- [GetClass](ue_ue.AnimCompositeBase.md#getclass)
- [GetName](ue_ue.AnimCompositeBase.md#getname)
- [GetOuter](ue_ue.AnimCompositeBase.md#getouter)
- [GetPlayLength](ue_ue.AnimCompositeBase.md#getplaylength)
- [GetWorld](ue_ue.AnimCompositeBase.md#getworld)
- [Find](ue_ue.AnimCompositeBase.md#find)
- [Load](ue_ue.AnimCompositeBase.md#load)
- [StaticClass](ue_ue.AnimCompositeBase.md#staticclass)

## Constructors

### constructor

• **new AnimCompositeBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[constructor](ue_ue.AnimSequenceBase.md#constructor)

#### Defined in

[ue/ue.d.ts:2779](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2779)

## Properties

### AnimNotifyTracks

• **AnimNotifyTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyTrack`](ue_ue.AnimNotifyTrack.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[AnimNotifyTracks](ue_ue.AnimSequenceBase.md#animnotifytracks)

#### Defined in

[ue/ue.d.ts:3134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3134)

___

### AssetMappingTable

• **AssetMappingTable**: [`AssetMappingTable`](ue_ue.AssetMappingTable.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[AssetMappingTable](ue_ue.AnimSequenceBase.md#assetmappingtable)

#### Defined in

[ue/ue.d.ts:2766](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2766)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[AssetUserData](ue_ue.AnimSequenceBase.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:2767](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2767)

___

### ChildrenAssets

• **ChildrenAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationAsset`](ue_ue.AnimationAsset.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[ChildrenAssets](ue_ue.AnimSequenceBase.md#childrenassets)

#### Defined in

[ue/ue.d.ts:2765](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2765)

___

### MetaData

• **MetaData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[MetaData](ue_ue.AnimSequenceBase.md#metadata)

#### Defined in

[ue/ue.d.ts:2763](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2763)

___

### Notifies

• **Notifies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[Notifies](ue_ue.AnimSequenceBase.md#notifies)

#### Defined in

[ue/ue.d.ts:3130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3130)

___

### ParentAsset

• **ParentAsset**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[ParentAsset](ue_ue.AnimSequenceBase.md#parentasset)

#### Defined in

[ue/ue.d.ts:2764](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2764)

___

### PreviewPoseAsset

• **PreviewPoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[PreviewPoseAsset](ue_ue.AnimSequenceBase.md#previewposeasset)

#### Defined in

[ue/ue.d.ts:2769](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2769)

___

### PreviewSkeletalMesh

• **PreviewSkeletalMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[PreviewSkeletalMesh](ue_ue.AnimSequenceBase.md#previewskeletalmesh)

#### Defined in

[ue/ue.d.ts:2770](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2770)

___

### RateScale

• **RateScale**: `number`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[RateScale](ue_ue.AnimSequenceBase.md#ratescale)

#### Defined in

[ue/ue.d.ts:3132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3132)

___

### RawCurveData

• **RawCurveData**: [`RawCurveTracks`](ue_ue.RawCurveTracks.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[RawCurveData](ue_ue.AnimSequenceBase.md#rawcurvedata)

#### Defined in

[ue/ue.d.ts:3133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3133)

___

### SequenceLength

• **SequenceLength**: `number`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[SequenceLength](ue_ue.AnimSequenceBase.md#sequencelength)

#### Defined in

[ue/ue.d.ts:3131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3131)

___

### Skeleton

• **Skeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[Skeleton](ue_ue.AnimSequenceBase.md#skeleton)

#### Defined in

[ue/ue.d.ts:2762](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2762)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[ThumbnailInfo](ue_ue.AnimSequenceBase.md#thumbnailinfo)

#### Defined in

[ue/ue.d.ts:2768](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2768)

___

### \_\_tid\_AnimCompositeBase\_\_

• **\_\_tid\_AnimCompositeBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:2784](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2784)

___

### \_\_tid\_AnimSequenceBase\_\_

• **\_\_tid\_AnimSequenceBase\_\_**: `boolean`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[__tid_AnimSequenceBase__](ue_ue.AnimSequenceBase.md#__tid_animsequencebase__)

#### Defined in

[ue/ue.d.ts:3140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3140)

___

### \_\_tid\_AnimationAsset\_\_

• **\_\_tid\_AnimationAsset\_\_**: `boolean`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[__tid_AnimationAsset__](ue_ue.AnimSequenceBase.md#__tid_animationasset__)

#### Defined in

[ue/ue.d.ts:2775](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2775)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[__tid_Object__](ue_ue.AnimSequenceBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[CreateDefaultSubobject](ue_ue.AnimSequenceBase.md#createdefaultsubobject)

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

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[ExecuteUbergraph](ue_ue.AnimSequenceBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[GetClass](ue_ue.AnimSequenceBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[GetName](ue_ue.AnimSequenceBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[GetOuter](ue_ue.AnimSequenceBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetPlayLength

▸ **GetPlayLength**(): `number`

#### Returns

`number`

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[GetPlayLength](ue_ue.AnimSequenceBase.md#getplaylength)

#### Defined in

[ue/ue.d.ts:3135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3135)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[GetWorld](ue_ue.AnimSequenceBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimCompositeBase`](ue_ue.AnimCompositeBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimCompositeBase`](ue_ue.AnimCompositeBase.md)

#### Overrides

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[Find](ue_ue.AnimSequenceBase.md#find)

#### Defined in

[ue/ue.d.ts:2781](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2781)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimCompositeBase`](ue_ue.AnimCompositeBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimCompositeBase`](ue_ue.AnimCompositeBase.md)

#### Overrides

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[Load](ue_ue.AnimSequenceBase.md#load)

#### Defined in

[ue/ue.d.ts:2782](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2782)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimSequenceBase](ue_ue.AnimSequenceBase.md).[StaticClass](ue_ue.AnimSequenceBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:2780](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2780)
