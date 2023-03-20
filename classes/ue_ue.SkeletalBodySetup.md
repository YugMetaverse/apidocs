[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SkeletalBodySetup

# Class: SkeletalBodySetup

[ue/ue](../modules/ue_ue.md).SkeletalBodySetup

## Hierarchy

- [`BodySetup`](ue_ue.BodySetup.md)

  ↳ **`SkeletalBodySetup`**

## Table of contents

### Constructors

- [constructor](ue_ue.SkeletalBodySetup.md#constructor)

### Properties

- [AggGeom](ue_ue.SkeletalBodySetup.md#agggeom)
- [BoneName](ue_ue.SkeletalBodySetup.md#bonename)
- [BuildScale](ue_ue.SkeletalBodySetup.md#buildscale)
- [BuildScale3D](ue_ue.SkeletalBodySetup.md#buildscale3d)
- [CollisionReponse](ue_ue.SkeletalBodySetup.md#collisionreponse)
- [CollisionTraceFlag](ue_ue.SkeletalBodySetup.md#collisiontraceflag)
- [CurrentPhysicalAnimationProfile](ue_ue.SkeletalBodySetup.md#currentphysicalanimationprofile)
- [DefaultInstance](ue_ue.SkeletalBodySetup.md#defaultinstance)
- [PhysMaterial](ue_ue.SkeletalBodySetup.md#physmaterial)
- [PhysicalAnimationData](ue_ue.SkeletalBodySetup.md#physicalanimationdata)
- [PhysicsType](ue_ue.SkeletalBodySetup.md#physicstype)
- [WalkableSlopeOverride](ue_ue.SkeletalBodySetup.md#walkableslopeoverride)
- [\_\_tid\_BodySetup\_\_](ue_ue.SkeletalBodySetup.md#__tid_bodysetup__)
- [\_\_tid\_Object\_\_](ue_ue.SkeletalBodySetup.md#__tid_object__)
- [\_\_tid\_SkeletalBodySetup\_\_](ue_ue.SkeletalBodySetup.md#__tid_skeletalbodysetup__)
- [bAlwaysFullAnimWeight](ue_ue.SkeletalBodySetup.md#balwaysfullanimweight)
- [bConsiderForBounds](ue_ue.SkeletalBodySetup.md#bconsiderforbounds)
- [bDoubleSidedGeometry](ue_ue.SkeletalBodySetup.md#bdoublesidedgeometry)
- [bGenerateMirroredCollision](ue_ue.SkeletalBodySetup.md#bgeneratemirroredcollision)
- [bGenerateNonMirroredCollision](ue_ue.SkeletalBodySetup.md#bgeneratenonmirroredcollision)
- [bMeshCollideAll](ue_ue.SkeletalBodySetup.md#bmeshcollideall)
- [bSharedCookedData](ue_ue.SkeletalBodySetup.md#bsharedcookeddata)
- [bSkipScaleFromAnimation](ue_ue.SkeletalBodySetup.md#bskipscalefromanimation)

### Methods

- [CreateDefaultSubobject](ue_ue.SkeletalBodySetup.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SkeletalBodySetup.md#executeubergraph)
- [GetClass](ue_ue.SkeletalBodySetup.md#getclass)
- [GetName](ue_ue.SkeletalBodySetup.md#getname)
- [GetOuter](ue_ue.SkeletalBodySetup.md#getouter)
- [GetWorld](ue_ue.SkeletalBodySetup.md#getworld)
- [Find](ue_ue.SkeletalBodySetup.md#find)
- [Load](ue_ue.SkeletalBodySetup.md#load)
- [StaticClass](ue_ue.SkeletalBodySetup.md#staticclass)

## Constructors

### constructor

• **new SkeletalBodySetup**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BodySetup](ue_ue.BodySetup.md).[constructor](ue_ue.BodySetup.md#constructor)

## Properties

### AggGeom

• **AggGeom**: [`KAggregateGeom`](ue_ue.KAggregateGeom.md)

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[AggGeom](ue_ue.BodySetup.md#agggeom)

___

### BoneName

• **BoneName**: `string`

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[BoneName](ue_ue.BodySetup.md#bonename)

___

### BuildScale

• **BuildScale**: `number`

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[BuildScale](ue_ue.BodySetup.md#buildscale)

___

### BuildScale3D

• **BuildScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[BuildScale3D](ue_ue.BodySetup.md#buildscale3d)

___

### CollisionReponse

• **CollisionReponse**: [`EBodyCollisionResponse`](../enums/ue_ue.EBodyCollisionResponse.md)

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[CollisionReponse](ue_ue.BodySetup.md#collisionreponse)

___

### CollisionTraceFlag

• **CollisionTraceFlag**: [`ECollisionTraceFlag`](../enums/ue_ue.ECollisionTraceFlag.md)

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[CollisionTraceFlag](ue_ue.BodySetup.md#collisiontraceflag)

___

### CurrentPhysicalAnimationProfile

• **CurrentPhysicalAnimationProfile**: [`PhysicalAnimationProfile`](ue_ue.PhysicalAnimationProfile.md)

___

### DefaultInstance

• **DefaultInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[DefaultInstance](ue_ue.BodySetup.md#defaultinstance)

___

### PhysMaterial

• **PhysMaterial**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[PhysMaterial](ue_ue.BodySetup.md#physmaterial)

___

### PhysicalAnimationData

• **PhysicalAnimationData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PhysicalAnimationProfile`](ue_ue.PhysicalAnimationProfile.md)\>

___

### PhysicsType

• **PhysicsType**: [`EPhysicsType`](../enums/ue_ue.EPhysicsType.md)

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[PhysicsType](ue_ue.BodySetup.md#physicstype)

___

### WalkableSlopeOverride

• **WalkableSlopeOverride**: [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[WalkableSlopeOverride](ue_ue.BodySetup.md#walkableslopeoverride)

___

### \_\_tid\_BodySetup\_\_

• **\_\_tid\_BodySetup\_\_**: `boolean`

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[__tid_BodySetup__](ue_ue.BodySetup.md#__tid_bodysetup__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[__tid_Object__](ue_ue.BodySetup.md#__tid_object__)

___

### \_\_tid\_SkeletalBodySetup\_\_

• **\_\_tid\_SkeletalBodySetup\_\_**: `boolean`

___

### bAlwaysFullAnimWeight

• **bAlwaysFullAnimWeight**: `boolean`

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[bAlwaysFullAnimWeight](ue_ue.BodySetup.md#balwaysfullanimweight)

___

### bConsiderForBounds

• **bConsiderForBounds**: `boolean`

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[bConsiderForBounds](ue_ue.BodySetup.md#bconsiderforbounds)

___

### bDoubleSidedGeometry

• **bDoubleSidedGeometry**: `boolean`

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[bDoubleSidedGeometry](ue_ue.BodySetup.md#bdoublesidedgeometry)

___

### bGenerateMirroredCollision

• **bGenerateMirroredCollision**: `boolean`

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[bGenerateMirroredCollision](ue_ue.BodySetup.md#bgeneratemirroredcollision)

___

### bGenerateNonMirroredCollision

• **bGenerateNonMirroredCollision**: `boolean`

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[bGenerateNonMirroredCollision](ue_ue.BodySetup.md#bgeneratenonmirroredcollision)

___

### bMeshCollideAll

• **bMeshCollideAll**: `boolean`

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[bMeshCollideAll](ue_ue.BodySetup.md#bmeshcollideall)

___

### bSharedCookedData

• **bSharedCookedData**: `boolean`

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[bSharedCookedData](ue_ue.BodySetup.md#bsharedcookeddata)

___

### bSkipScaleFromAnimation

• **bSkipScaleFromAnimation**: `boolean`

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

[BodySetup](ue_ue.BodySetup.md).[CreateDefaultSubobject](ue_ue.BodySetup.md#createdefaultsubobject)

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

[BodySetup](ue_ue.BodySetup.md).[ExecuteUbergraph](ue_ue.BodySetup.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[GetClass](ue_ue.BodySetup.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[GetName](ue_ue.BodySetup.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[GetOuter](ue_ue.BodySetup.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BodySetup](ue_ue.BodySetup.md).[GetWorld](ue_ue.BodySetup.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SkeletalBodySetup`](ue_ue.SkeletalBodySetup.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SkeletalBodySetup`](ue_ue.SkeletalBodySetup.md)

#### Overrides

[BodySetup](ue_ue.BodySetup.md).[Find](ue_ue.BodySetup.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SkeletalBodySetup`](ue_ue.SkeletalBodySetup.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SkeletalBodySetup`](ue_ue.SkeletalBodySetup.md)

#### Overrides

[BodySetup](ue_ue.BodySetup.md).[Load](ue_ue.BodySetup.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BodySetup](ue_ue.BodySetup.md).[StaticClass](ue_ue.BodySetup.md#staticclass)
