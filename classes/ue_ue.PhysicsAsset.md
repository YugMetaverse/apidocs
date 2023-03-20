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

## Properties

### BodySetup

• **BodySetup**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BodySetup`](ue_ue.BodySetup.md)\>

___

### BoundsBodies

• **BoundsBodies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### ConstraintProfiles

• **ConstraintProfiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ConstraintSetup

• **ConstraintSetup**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PhysicsConstraintTemplate`](ue_ue.PhysicsConstraintTemplate.md)\>

___

### CurrentConstraintProfileName

• **CurrentConstraintProfileName**: `string`

___

### CurrentPhysicalAnimationProfileName

• **CurrentPhysicalAnimationProfileName**: `string`

___

### DefaultSkelMesh

• **DefaultSkelMesh**: [`SkeletalMesh`](ue_ue.SkeletalMesh.md)

___

### PhysicalAnimationProfiles

• **PhysicalAnimationProfiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### PreviewSkeletalMesh

• **PreviewSkeletalMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

___

### SkeletalBodySetups

• **SkeletalBodySetups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SkeletalBodySetup`](ue_ue.SkeletalBodySetup.md)\>

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PhysicsAsset\_\_

• **\_\_tid\_PhysicsAsset\_\_**: `boolean`

___

### bNotForDedicatedServer

• **bNotForDedicatedServer**: `boolean`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
