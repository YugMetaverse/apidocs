[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PhysicsAsset

# Class: PhysicsAsset

[ue/ue](../modules/ue_ue.md).PhysicsAsset

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PhysicsAsset`**

## Table of contents

### Constructors

- [constructor](ue_ue.PhysicsAsset.md#constructor)

### Properties

- [BodySetup](ue_ue.PhysicsAsset.md#bodysetup)
- [BoundsBodies](ue_ue.PhysicsAsset.md#boundsbodies)
- [ConstraintProfiles](ue_ue.PhysicsAsset.md#constraintprofiles)
- [ConstraintSetup](ue_ue.PhysicsAsset.md#constraintsetup)
- [CurrentConstraintProfileName](ue_ue.PhysicsAsset.md#currentconstraintprofilename)
- [CurrentPhysicalAnimationProfileName](ue_ue.PhysicsAsset.md#currentphysicalanimationprofilename)
- [DefaultSkelMesh](ue_ue.PhysicsAsset.md#defaultskelmesh)
- [PhysicalAnimationProfiles](ue_ue.PhysicsAsset.md#physicalanimationprofiles)
- [PreviewSkeletalMesh](ue_ue.PhysicsAsset.md#previewskeletalmesh)
- [SkeletalBodySetups](ue_ue.PhysicsAsset.md#skeletalbodysetups)
- [ThumbnailInfo](ue_ue.PhysicsAsset.md#thumbnailinfo)
- [\_\_tid\_Object\_\_](ue_ue.PhysicsAsset.md#__tid_object__)
- [\_\_tid\_PhysicsAsset\_\_](ue_ue.PhysicsAsset.md#__tid_physicsasset__)
- [bNotForDedicatedServer](ue_ue.PhysicsAsset.md#bnotfordedicatedserver)

### Methods

- [CreateDefaultSubobject](ue_ue.PhysicsAsset.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PhysicsAsset.md#executeubergraph)
- [GetClass](ue_ue.PhysicsAsset.md#getclass)
- [GetName](ue_ue.PhysicsAsset.md#getname)
- [GetOuter](ue_ue.PhysicsAsset.md#getouter)
- [GetWorld](ue_ue.PhysicsAsset.md#getworld)
- [Find](ue_ue.PhysicsAsset.md#find)
- [Load](ue_ue.PhysicsAsset.md#load)
- [StaticClass](ue_ue.PhysicsAsset.md#staticclass)

## Constructors

### constructor

• **new PhysicsAsset**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:3855](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3855)

## Properties

### BodySetup

• **BodySetup**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BodySetup`](ue_ue.BodySetup.md)\>

#### Defined in

[ue/ue.d.ts:3867](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3867)

___

### BoundsBodies

• **BoundsBodies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:3862](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3862)

___

### ConstraintProfiles

• **ConstraintProfiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:3859](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3859)

___

### ConstraintSetup

• **ConstraintSetup**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PhysicsConstraintTemplate`](ue_ue.PhysicsConstraintTemplate.md)\>

#### Defined in

[ue/ue.d.ts:3864](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3864)

___

### CurrentConstraintProfileName

• **CurrentConstraintProfileName**: `string`

#### Defined in

[ue/ue.d.ts:3861](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3861)

___

### CurrentPhysicalAnimationProfileName

• **CurrentPhysicalAnimationProfileName**: `string`

#### Defined in

[ue/ue.d.ts:3860](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3860)

___

### DefaultSkelMesh

• **DefaultSkelMesh**: [`SkeletalMesh`](ue_ue.SkeletalMesh.md)

#### Defined in

[ue/ue.d.ts:3856](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3856)

___

### PhysicalAnimationProfiles

• **PhysicalAnimationProfiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:3858](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3858)

___

### PreviewSkeletalMesh

• **PreviewSkeletalMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

#### Defined in

[ue/ue.d.ts:3857](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3857)

___

### SkeletalBodySetups

• **SkeletalBodySetups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SkeletalBodySetup`](ue_ue.SkeletalBodySetup.md)\>

#### Defined in

[ue/ue.d.ts:3863](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3863)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Defined in

[ue/ue.d.ts:3866](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3866)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PhysicsAsset\_\_

• **\_\_tid\_PhysicsAsset\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3872](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3872)

___

### bNotForDedicatedServer

• **bNotForDedicatedServer**: `boolean`

#### Defined in

[ue/ue.d.ts:3865](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3865)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PhysicsAsset`](ue_ue.PhysicsAsset.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PhysicsAsset`](ue_ue.PhysicsAsset.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:3869](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3869)

___

### Load

▸ `Static` **Load**(`InName`): [`PhysicsAsset`](ue_ue.PhysicsAsset.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PhysicsAsset`](ue_ue.PhysicsAsset.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:3870](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3870)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:3868](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3868)
