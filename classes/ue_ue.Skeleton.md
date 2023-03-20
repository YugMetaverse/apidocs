[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Skeleton

# Class: Skeleton

[ue/ue](../modules/ue_ue.md).Skeleton

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`Skeleton`**

## Table of contents

### Constructors

- [constructor](ue_ue.Skeleton.md#constructor)

### Properties

- [AdditionalPreviewSkeletalMeshes](ue_ue.Skeleton.md#additionalpreviewskeletalmeshes)
- [AnimationNotifies](ue_ue.Skeleton.md#animationnotifies)
- [AssetUserData](ue_ue.Skeleton.md#assetuserdata)
- [BlendProfiles](ue_ue.Skeleton.md#blendprofiles)
- [BoneTree](ue_ue.Skeleton.md#bonetree)
- [PreviewAttachedAssetContainer](ue_ue.Skeleton.md#previewattachedassetcontainer)
- [PreviewSkeletalMesh](ue_ue.Skeleton.md#previewskeletalmesh)
- [RefLocalPoses](ue_ue.Skeleton.md#reflocalposes)
- [RigConfig](ue_ue.Skeleton.md#rigconfig)
- [SlotGroups](ue_ue.Skeleton.md#slotgroups)
- [SmartNames](ue_ue.Skeleton.md#smartnames)
- [Sockets](ue_ue.Skeleton.md#sockets)
- [VirtualBoneGuid](ue_ue.Skeleton.md#virtualboneguid)
- [VirtualBones](ue_ue.Skeleton.md#virtualbones)
- [\_\_tid\_Object\_\_](ue_ue.Skeleton.md#__tid_object__)
- [\_\_tid\_Skeleton\_\_](ue_ue.Skeleton.md#__tid_skeleton__)

### Methods

- [CreateDefaultSubobject](ue_ue.Skeleton.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Skeleton.md#executeubergraph)
- [GetClass](ue_ue.Skeleton.md#getclass)
- [GetName](ue_ue.Skeleton.md#getname)
- [GetOuter](ue_ue.Skeleton.md#getouter)
- [GetWorld](ue_ue.Skeleton.md#getworld)
- [Find](ue_ue.Skeleton.md#find)
- [Load](ue_ue.Skeleton.md#load)
- [StaticClass](ue_ue.Skeleton.md#staticclass)

## Constructors

### constructor

• **new Skeleton**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:2537](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2537)

## Properties

### AdditionalPreviewSkeletalMeshes

• **AdditionalPreviewSkeletalMeshes**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`DataAsset`](ue_ue.DataAsset.md)\>

#### Defined in

[ue/ue.d.ts:2547](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2547)

___

### AnimationNotifies

• **AnimationNotifies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:2549](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2549)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Defined in

[ue/ue.d.ts:2551](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2551)

___

### BlendProfiles

• **BlendProfiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlendProfile`](ue_ue.BlendProfile.md)\>

#### Defined in

[ue/ue.d.ts:2544](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2544)

___

### BoneTree

• **BoneTree**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneNode`](ue_ue.BoneNode.md)\>

#### Defined in

[ue/ue.d.ts:2538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2538)

___

### PreviewAttachedAssetContainer

• **PreviewAttachedAssetContainer**: [`PreviewAssetAttachContainer`](ue_ue.PreviewAssetAttachContainer.md)

#### Defined in

[ue/ue.d.ts:2550](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2550)

___

### PreviewSkeletalMesh

• **PreviewSkeletalMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

#### Defined in

[ue/ue.d.ts:2546](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2546)

___

### RefLocalPoses

• **RefLocalPoses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\>

#### Defined in

[ue/ue.d.ts:2539](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2539)

___

### RigConfig

• **RigConfig**: [`RigConfiguration`](ue_ue.RigConfiguration.md)

#### Defined in

[ue/ue.d.ts:2548](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2548)

___

### SlotGroups

• **SlotGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimSlotGroup`](ue_ue.AnimSlotGroup.md)\>

#### Defined in

[ue/ue.d.ts:2545](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2545)

___

### SmartNames

• **SmartNames**: [`SmartNameContainer`](ue_ue.SmartNameContainer.md)

#### Defined in

[ue/ue.d.ts:2543](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2543)

___

### Sockets

• **Sockets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SkeletalMeshSocket`](ue_ue.SkeletalMeshSocket.md)\>

#### Defined in

[ue/ue.d.ts:2542](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2542)

___

### VirtualBoneGuid

• **VirtualBoneGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:2540](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2540)

___

### VirtualBones

• **VirtualBones**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VirtualBone`](ue_ue.VirtualBone.md)\>

#### Defined in

[ue/ue.d.ts:2541](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2541)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_Skeleton\_\_

• **\_\_tid\_Skeleton\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:2556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2556)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Skeleton`](ue_ue.Skeleton.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Skeleton`](ue_ue.Skeleton.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:2553](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2553)

___

### Load

▸ `Static` **Load**(`InName`): [`Skeleton`](ue_ue.Skeleton.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Skeleton`](ue_ue.Skeleton.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:2554](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2554)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:2552](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2552)
