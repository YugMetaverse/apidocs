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

#### Defined in

[ue/ue.d.ts:3509](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3509)

## Properties

### AggGeom

• **AggGeom**: [`KAggregateGeom`](ue_ue.KAggregateGeom.md)

#### Defined in

[ue/ue.d.ts:3510](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3510)

___

### BoneName

• **BoneName**: `string`

#### Defined in

[ue/ue.d.ts:3511](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3511)

___

### BuildScale

• **BuildScale**: `number`

#### Defined in

[ue/ue.d.ts:3524](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3524)

___

### BuildScale3D

• **BuildScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:3526](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3526)

___

### CollisionReponse

• **CollisionReponse**: [`EBodyCollisionResponse`](../enums/ue_ue.EBodyCollisionResponse.md)

#### Defined in

[ue/ue.d.ts:3520](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3520)

___

### CollisionTraceFlag

• **CollisionTraceFlag**: [`ECollisionTraceFlag`](../enums/ue_ue.ECollisionTraceFlag.md)

#### Defined in

[ue/ue.d.ts:3521](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3521)

___

### DefaultInstance

• **DefaultInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Defined in

[ue/ue.d.ts:3525](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3525)

___

### PhysMaterial

• **PhysMaterial**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Defined in

[ue/ue.d.ts:3522](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3522)

___

### PhysicsType

• **PhysicsType**: [`EPhysicsType`](../enums/ue_ue.EPhysicsType.md)

#### Defined in

[ue/ue.d.ts:3512](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3512)

___

### WalkableSlopeOverride

• **WalkableSlopeOverride**: [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Defined in

[ue/ue.d.ts:3523](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3523)

___

### \_\_tid\_BodySetup\_\_

• **\_\_tid\_BodySetup\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3531](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3531)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bAlwaysFullAnimWeight

• **bAlwaysFullAnimWeight**: `boolean`

#### Defined in

[ue/ue.d.ts:3513](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3513)

___

### bConsiderForBounds

• **bConsiderForBounds**: `boolean`

#### Defined in

[ue/ue.d.ts:3514](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3514)

___

### bDoubleSidedGeometry

• **bDoubleSidedGeometry**: `boolean`

#### Defined in

[ue/ue.d.ts:3516](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3516)

___

### bGenerateMirroredCollision

• **bGenerateMirroredCollision**: `boolean`

#### Defined in

[ue/ue.d.ts:3519](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3519)

___

### bGenerateNonMirroredCollision

• **bGenerateNonMirroredCollision**: `boolean`

#### Defined in

[ue/ue.d.ts:3517](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3517)

___

### bMeshCollideAll

• **bMeshCollideAll**: `boolean`

#### Defined in

[ue/ue.d.ts:3515](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3515)

___

### bSharedCookedData

• **bSharedCookedData**: `boolean`

#### Defined in

[ue/ue.d.ts:3518](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3518)

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

#### Defined in

[ue/ue.d.ts:3528](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3528)

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

#### Defined in

[ue/ue.d.ts:3529](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3529)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:3527](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3527)
