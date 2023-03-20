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

## Properties

### AdditionalPreviewSkeletalMeshes

• **AdditionalPreviewSkeletalMeshes**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`DataAsset`](ue_ue.DataAsset.md)\>

___

### AnimationNotifies

• **AnimationNotifies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

___

### BlendProfiles

• **BlendProfiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlendProfile`](ue_ue.BlendProfile.md)\>

___

### BoneTree

• **BoneTree**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneNode`](ue_ue.BoneNode.md)\>

___

### PreviewAttachedAssetContainer

• **PreviewAttachedAssetContainer**: [`PreviewAssetAttachContainer`](ue_ue.PreviewAssetAttachContainer.md)

___

### PreviewSkeletalMesh

• **PreviewSkeletalMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

___

### RefLocalPoses

• **RefLocalPoses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\>

___

### RigConfig

• **RigConfig**: [`RigConfiguration`](ue_ue.RigConfiguration.md)

___

### SlotGroups

• **SlotGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimSlotGroup`](ue_ue.AnimSlotGroup.md)\>

___

### SmartNames

• **SmartNames**: [`SmartNameContainer`](ue_ue.SmartNameContainer.md)

___

### Sockets

• **Sockets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SkeletalMeshSocket`](ue_ue.SkeletalMeshSocket.md)\>

___

### VirtualBoneGuid

• **VirtualBoneGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### VirtualBones

• **VirtualBones**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VirtualBone`](ue_ue.VirtualBone.md)\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_Skeleton\_\_

• **\_\_tid\_Skeleton\_\_**: `boolean`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
