[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GeometryCollection

# Class: GeometryCollection

[ue/ue](../modules/ue_ue.md).GeometryCollection

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`GeometryCollection`**

## Table of contents

### Constructors

- [constructor](ue_ue.GeometryCollection.md#constructor)

### Properties

- [BoneSelectedMaterialIndex](ue_ue.GeometryCollection.md#boneselectedmaterialindex)
- [CollisionObjectReductionPercentage](ue_ue.GeometryCollection.md#collisionobjectreductionpercentage)
- [CollisionParticlesFraction](ue_ue.GeometryCollection.md#collisionparticlesfraction)
- [CollisionType](ue_ue.GeometryCollection.md#collisiontype)
- [EnableRemovePiecesOnFracture](ue_ue.GeometryCollection.md#enableremovepiecesonfracture)
- [ImplicitType](ue_ue.GeometryCollection.md#implicittype)
- [Mass](ue_ue.GeometryCollection.md#mass)
- [Materials](ue_ue.GeometryCollection.md#materials)
- [MaxClusterLevelSetResolution](ue_ue.GeometryCollection.md#maxclusterlevelsetresolution)
- [MaxLevelSetResolution](ue_ue.GeometryCollection.md#maxlevelsetresolution)
- [MaximumCollisionParticles](ue_ue.GeometryCollection.md#maximumcollisionparticles)
- [MinClusterLevelSetResolution](ue_ue.GeometryCollection.md#minclusterlevelsetresolution)
- [MinLevelSetResolution](ue_ue.GeometryCollection.md#minlevelsetresolution)
- [MinimumMassClamp](ue_ue.GeometryCollection.md#minimummassclamp)
- [PersistentGuid](ue_ue.GeometryCollection.md#persistentguid)
- [RemoveOnFractureMaterials](ue_ue.GeometryCollection.md#removeonfracturematerials)
- [SizeSpecificData](ue_ue.GeometryCollection.md#sizespecificdata)
- [StateGuid](ue_ue.GeometryCollection.md#stateguid)
- [ThumbnailInfo](ue_ue.GeometryCollection.md#thumbnailinfo)
- [\_\_tid\_GeometryCollection\_\_](ue_ue.GeometryCollection.md#__tid_geometrycollection__)
- [\_\_tid\_Object\_\_](ue_ue.GeometryCollection.md#__tid_object__)
- [bMassAsDensity](ue_ue.GeometryCollection.md#bmassasdensity)

### Methods

- [CreateDefaultSubobject](ue_ue.GeometryCollection.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GeometryCollection.md#executeubergraph)
- [GetClass](ue_ue.GeometryCollection.md#getclass)
- [GetName](ue_ue.GeometryCollection.md#getname)
- [GetOuter](ue_ue.GeometryCollection.md#getouter)
- [GetWorld](ue_ue.GeometryCollection.md#getworld)
- [Find](ue_ue.GeometryCollection.md#find)
- [Load](ue_ue.GeometryCollection.md#load)
- [StaticClass](ue_ue.GeometryCollection.md#staticclass)

## Constructors

### constructor

• **new GeometryCollection**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### BoneSelectedMaterialIndex

• **BoneSelectedMaterialIndex**: `number`

___

### CollisionObjectReductionPercentage

• **CollisionObjectReductionPercentage**: `number`

___

### CollisionParticlesFraction

• **CollisionParticlesFraction**: `number`

___

### CollisionType

• **CollisionType**: [`ECollisionTypeEnum`](../enums/ue_ue.ECollisionTypeEnum.md)

___

### EnableRemovePiecesOnFracture

• **EnableRemovePiecesOnFracture**: `boolean`

___

### ImplicitType

• **ImplicitType**: [`EImplicitTypeEnum`](../enums/ue_ue.EImplicitTypeEnum.md)

___

### Mass

• **Mass**: `number`

___

### Materials

• **Materials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

___

### MaxClusterLevelSetResolution

• **MaxClusterLevelSetResolution**: `number`

___

### MaxLevelSetResolution

• **MaxLevelSetResolution**: `number`

___

### MaximumCollisionParticles

• **MaximumCollisionParticles**: `number`

___

### MinClusterLevelSetResolution

• **MinClusterLevelSetResolution**: `number`

___

### MinLevelSetResolution

• **MinLevelSetResolution**: `number`

___

### MinimumMassClamp

• **MinimumMassClamp**: `number`

___

### PersistentGuid

• **PersistentGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### RemoveOnFractureMaterials

• **RemoveOnFractureMaterials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

___

### SizeSpecificData

• **SizeSpecificData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GeometryCollectionSizeSpecificData`](ue_ue.GeometryCollectionSizeSpecificData.md)\>

___

### StateGuid

• **StateGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

___

### \_\_tid\_GeometryCollection\_\_

• **\_\_tid\_GeometryCollection\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bMassAsDensity

• **bMassAsDensity**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GeometryCollection`](ue_ue.GeometryCollection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GeometryCollection`](ue_ue.GeometryCollection.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GeometryCollection`](ue_ue.GeometryCollection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GeometryCollection`](ue_ue.GeometryCollection.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
