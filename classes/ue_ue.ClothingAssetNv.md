[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ClothingAssetNv

# Class: ClothingAssetNv

[ue/ue](../modules/ue_ue.md).ClothingAssetNv

## Hierarchy

- [`ClothingAssetCommon`](ue_ue.ClothingAssetCommon.md)

  ↳ **`ClothingAssetNv`**

## Table of contents

### Constructors

- [constructor](ue_ue.ClothingAssetNv.md#constructor)

### Properties

- [AssetGuid](ue_ue.ClothingAssetNv.md#assetguid)
- [ClothConfig](ue_ue.ClothingAssetNv.md#clothconfig)
- [ClothLodData](ue_ue.ClothingAssetNv.md#clothloddata)
- [ClothSimConfig](ue_ue.ClothingAssetNv.md#clothsimconfig)
- [CustomData](ue_ue.ClothingAssetNv.md#customdata)
- [ImportedFilePath](ue_ue.ClothingAssetNv.md#importedfilepath)
- [LodData](ue_ue.ClothingAssetNv.md#loddata)
- [LodMap](ue_ue.ClothingAssetNv.md#lodmap)
- [PhysicsAsset](ue_ue.ClothingAssetNv.md#physicsasset)
- [ReferenceBoneIndex](ue_ue.ClothingAssetNv.md#referenceboneindex)
- [UsedBoneIndices](ue_ue.ClothingAssetNv.md#usedboneindices)
- [UsedBoneNames](ue_ue.ClothingAssetNv.md#usedbonenames)
- [\_\_tid\_ClothingAssetBase\_\_](ue_ue.ClothingAssetNv.md#__tid_clothingassetbase__)
- [\_\_tid\_ClothingAssetCommon\_\_](ue_ue.ClothingAssetNv.md#__tid_clothingassetcommon__)
- [\_\_tid\_ClothingAssetNv\_\_](ue_ue.ClothingAssetNv.md#__tid_clothingassetnv__)
- [\_\_tid\_Object\_\_](ue_ue.ClothingAssetNv.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ClothingAssetNv.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ClothingAssetNv.md#executeubergraph)
- [GetClass](ue_ue.ClothingAssetNv.md#getclass)
- [GetName](ue_ue.ClothingAssetNv.md#getname)
- [GetOuter](ue_ue.ClothingAssetNv.md#getouter)
- [GetWorld](ue_ue.ClothingAssetNv.md#getworld)
- [Find](ue_ue.ClothingAssetNv.md#find)
- [Load](ue_ue.ClothingAssetNv.md#load)
- [StaticClass](ue_ue.ClothingAssetNv.md#staticclass)

## Constructors

### constructor

• **new ClothingAssetNv**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[constructor](ue_ue.ClothingAssetCommon.md#constructor)

## Properties

### AssetGuid

• **AssetGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[AssetGuid](ue_ue.ClothingAssetCommon.md#assetguid)

___

### ClothConfig

• **ClothConfig**: [`ClothConfig`](ue_ue.ClothConfig.md)

___

### ClothLodData

• **ClothLodData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothLODDataBase`](ue_ue.ClothLODDataBase.md)\>

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[ClothLodData](ue_ue.ClothingAssetCommon.md#clothloddata)

___

### ClothSimConfig

• **ClothSimConfig**: [`ClothConfigBase`](ue_ue.ClothConfigBase.md)

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[ClothSimConfig](ue_ue.ClothingAssetCommon.md#clothsimconfig)

___

### CustomData

• **CustomData**: [`ClothingAssetCustomData`](ue_ue.ClothingAssetCustomData.md)

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[CustomData](ue_ue.ClothingAssetCommon.md#customdata)

___

### ImportedFilePath

• **ImportedFilePath**: `string`

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[ImportedFilePath](ue_ue.ClothingAssetCommon.md#importedfilepath)

___

### LodData

• **LodData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothLODData`](ue_ue.ClothLODData.md)\>

___

### LodMap

• **LodMap**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[LodMap](ue_ue.ClothingAssetCommon.md#lodmap)

___

### PhysicsAsset

• **PhysicsAsset**: [`PhysicsAsset`](ue_ue.PhysicsAsset.md)

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[PhysicsAsset](ue_ue.ClothingAssetCommon.md#physicsasset)

___

### ReferenceBoneIndex

• **ReferenceBoneIndex**: `number`

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[ReferenceBoneIndex](ue_ue.ClothingAssetCommon.md#referenceboneindex)

___

### UsedBoneIndices

• **UsedBoneIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[UsedBoneIndices](ue_ue.ClothingAssetCommon.md#usedboneindices)

___

### UsedBoneNames

• **UsedBoneNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[UsedBoneNames](ue_ue.ClothingAssetCommon.md#usedbonenames)

___

### \_\_tid\_ClothingAssetBase\_\_

• **\_\_tid\_ClothingAssetBase\_\_**: `boolean`

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[__tid_ClothingAssetBase__](ue_ue.ClothingAssetCommon.md#__tid_clothingassetbase__)

___

### \_\_tid\_ClothingAssetCommon\_\_

• **\_\_tid\_ClothingAssetCommon\_\_**: `boolean`

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[__tid_ClothingAssetCommon__](ue_ue.ClothingAssetCommon.md#__tid_clothingassetcommon__)

___

### \_\_tid\_ClothingAssetNv\_\_

• **\_\_tid\_ClothingAssetNv\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[__tid_Object__](ue_ue.ClothingAssetCommon.md#__tid_object__)

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

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[CreateDefaultSubobject](ue_ue.ClothingAssetCommon.md#createdefaultsubobject)

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

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[ExecuteUbergraph](ue_ue.ClothingAssetCommon.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[GetClass](ue_ue.ClothingAssetCommon.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[GetName](ue_ue.ClothingAssetCommon.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[GetOuter](ue_ue.ClothingAssetCommon.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[GetWorld](ue_ue.ClothingAssetCommon.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ClothingAssetNv`](ue_ue.ClothingAssetNv.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ClothingAssetNv`](ue_ue.ClothingAssetNv.md)

#### Overrides

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[Find](ue_ue.ClothingAssetCommon.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ClothingAssetNv`](ue_ue.ClothingAssetNv.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ClothingAssetNv`](ue_ue.ClothingAssetNv.md)

#### Overrides

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[Load](ue_ue.ClothingAssetCommon.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[StaticClass](ue_ue.ClothingAssetCommon.md#staticclass)
