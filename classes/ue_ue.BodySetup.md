[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BodySetup

# Class: BodySetup

[ue/ue](../modules/ue_ue.md).BodySetup

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`BodySetup`**

  ↳↳ [`SkeletalBodySetup`](ue_ue.SkeletalBodySetup.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BodySetup.md#constructor)

### Properties

- [AggGeom](ue_ue.BodySetup.md#agggeom)
- [BoneName](ue_ue.BodySetup.md#bonename)
- [BuildScale](ue_ue.BodySetup.md#buildscale)
- [BuildScale3D](ue_ue.BodySetup.md#buildscale3d)
- [CollisionReponse](ue_ue.BodySetup.md#collisionreponse)
- [CollisionTraceFlag](ue_ue.BodySetup.md#collisiontraceflag)
- [DefaultInstance](ue_ue.BodySetup.md#defaultinstance)
- [PhysMaterial](ue_ue.BodySetup.md#physmaterial)
- [PhysicsType](ue_ue.BodySetup.md#physicstype)
- [WalkableSlopeOverride](ue_ue.BodySetup.md#walkableslopeoverride)
- [\_\_tid\_BodySetup\_\_](ue_ue.BodySetup.md#__tid_bodysetup__)
- [\_\_tid\_Object\_\_](ue_ue.BodySetup.md#__tid_object__)
- [bAlwaysFullAnimWeight](ue_ue.BodySetup.md#balwaysfullanimweight)
- [bConsiderForBounds](ue_ue.BodySetup.md#bconsiderforbounds)
- [bDoubleSidedGeometry](ue_ue.BodySetup.md#bdoublesidedgeometry)
- [bGenerateMirroredCollision](ue_ue.BodySetup.md#bgeneratemirroredcollision)
- [bGenerateNonMirroredCollision](ue_ue.BodySetup.md#bgeneratenonmirroredcollision)
- [bMeshCollideAll](ue_ue.BodySetup.md#bmeshcollideall)
- [bSharedCookedData](ue_ue.BodySetup.md#bsharedcookeddata)

### Methods

- [CreateDefaultSubobject](ue_ue.BodySetup.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BodySetup.md#executeubergraph)
- [GetClass](ue_ue.BodySetup.md#getclass)
- [GetName](ue_ue.BodySetup.md#getname)
- [GetOuter](ue_ue.BodySetup.md#getouter)
- [GetWorld](ue_ue.BodySetup.md#getworld)
- [Find](ue_ue.BodySetup.md#find)
- [Load](ue_ue.BodySetup.md#load)
- [StaticClass](ue_ue.BodySetup.md#staticclass)

## Constructors

### constructor

• **new BodySetup**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AggGeom

• **AggGeom**: [`KAggregateGeom`](ue_ue.KAggregateGeom.md)

___

### BoneName

• **BoneName**: `string`

___

### BuildScale

• **BuildScale**: `number`

___

### BuildScale3D

• **BuildScale3D**: [`Vector`](ue_ue_s.Vector.md)

___

### CollisionReponse

• **CollisionReponse**: [`EBodyCollisionResponse`](../enums/ue_ue.EBodyCollisionResponse.md)

___

### CollisionTraceFlag

• **CollisionTraceFlag**: [`ECollisionTraceFlag`](../enums/ue_ue.ECollisionTraceFlag.md)

___

### DefaultInstance

• **DefaultInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

___

### PhysMaterial

• **PhysMaterial**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

___

### PhysicsType

• **PhysicsType**: [`EPhysicsType`](../enums/ue_ue.EPhysicsType.md)

___

### WalkableSlopeOverride

• **WalkableSlopeOverride**: [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

___

### \_\_tid\_BodySetup\_\_

• **\_\_tid\_BodySetup\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bAlwaysFullAnimWeight

• **bAlwaysFullAnimWeight**: `boolean`

___

### bConsiderForBounds

• **bConsiderForBounds**: `boolean`

___

### bDoubleSidedGeometry

• **bDoubleSidedGeometry**: `boolean`

___

### bGenerateMirroredCollision

• **bGenerateMirroredCollision**: `boolean`

___

### bGenerateNonMirroredCollision

• **bGenerateNonMirroredCollision**: `boolean`

___

### bMeshCollideAll

• **bMeshCollideAll**: `boolean`

___

### bSharedCookedData

• **bSharedCookedData**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BodySetup`](ue_ue.BodySetup.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BodySetup`](ue_ue.BodySetup.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BodySetup`](ue_ue.BodySetup.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BodySetup`](ue_ue.BodySetup.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
