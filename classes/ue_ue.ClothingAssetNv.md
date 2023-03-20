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

#### Defined in

[ue/ue.d.ts:27905](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27905)

## Properties

### AssetGuid

• **AssetGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[AssetGuid](ue_ue.ClothingAssetCommon.md#assetguid)

#### Defined in

[ue/ue.d.ts:3961](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3961)

___

### ClothConfig

• **ClothConfig**: [`ClothConfig`](ue_ue.ClothConfig.md)

#### Defined in

[ue/ue.d.ts:27906](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27906)

___

### ClothLodData

• **ClothLodData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothLODDataBase`](ue_ue.ClothLODDataBase.md)\>

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[ClothLodData](ue_ue.ClothingAssetCommon.md#clothloddata)

#### Defined in

[ue/ue.d.ts:27779](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27779)

___

### ClothSimConfig

• **ClothSimConfig**: [`ClothConfigBase`](ue_ue.ClothConfigBase.md)

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[ClothSimConfig](ue_ue.ClothingAssetCommon.md#clothsimconfig)

#### Defined in

[ue/ue.d.ts:27778](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27778)

___

### CustomData

• **CustomData**: [`ClothingAssetCustomData`](ue_ue.ClothingAssetCustomData.md)

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[CustomData](ue_ue.ClothingAssetCommon.md#customdata)

#### Defined in

[ue/ue.d.ts:27784](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27784)

___

### ImportedFilePath

• **ImportedFilePath**: `string`

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[ImportedFilePath](ue_ue.ClothingAssetCommon.md#importedfilepath)

#### Defined in

[ue/ue.d.ts:3960](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3960)

___

### LodData

• **LodData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothLODData`](ue_ue.ClothLODData.md)\>

#### Defined in

[ue/ue.d.ts:27907](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27907)

___

### LodMap

• **LodMap**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[LodMap](ue_ue.ClothingAssetCommon.md#lodmap)

#### Defined in

[ue/ue.d.ts:27780](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27780)

___

### PhysicsAsset

• **PhysicsAsset**: [`PhysicsAsset`](ue_ue.PhysicsAsset.md)

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[PhysicsAsset](ue_ue.ClothingAssetCommon.md#physicsasset)

#### Defined in

[ue/ue.d.ts:27777](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27777)

___

### ReferenceBoneIndex

• **ReferenceBoneIndex**: `number`

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[ReferenceBoneIndex](ue_ue.ClothingAssetCommon.md#referenceboneindex)

#### Defined in

[ue/ue.d.ts:27783](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27783)

___

### UsedBoneIndices

• **UsedBoneIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[UsedBoneIndices](ue_ue.ClothingAssetCommon.md#usedboneindices)

#### Defined in

[ue/ue.d.ts:27782](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27782)

___

### UsedBoneNames

• **UsedBoneNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[UsedBoneNames](ue_ue.ClothingAssetCommon.md#usedbonenames)

#### Defined in

[ue/ue.d.ts:27781](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27781)

___

### \_\_tid\_ClothingAssetBase\_\_

• **\_\_tid\_ClothingAssetBase\_\_**: `boolean`

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[__tid_ClothingAssetBase__](ue_ue.ClothingAssetCommon.md#__tid_clothingassetbase__)

#### Defined in

[ue/ue.d.ts:3966](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3966)

___

### \_\_tid\_ClothingAssetCommon\_\_

• **\_\_tid\_ClothingAssetCommon\_\_**: `boolean`

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[__tid_ClothingAssetCommon__](ue_ue.ClothingAssetCommon.md#__tid_clothingassetcommon__)

#### Defined in

[ue/ue.d.ts:27789](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27789)

___

### \_\_tid\_ClothingAssetNv\_\_

• **\_\_tid\_ClothingAssetNv\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:27912](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27912)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[__tid_Object__](ue_ue.ClothingAssetCommon.md#__tid_object__)

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

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[CreateDefaultSubobject](ue_ue.ClothingAssetCommon.md#createdefaultsubobject)

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

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[ExecuteUbergraph](ue_ue.ClothingAssetCommon.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[GetClass](ue_ue.ClothingAssetCommon.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[GetName](ue_ue.ClothingAssetCommon.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[GetOuter](ue_ue.ClothingAssetCommon.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[GetWorld](ue_ue.ClothingAssetCommon.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:27909](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27909)

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

#### Defined in

[ue/ue.d.ts:27910](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27910)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ClothingAssetCommon](ue_ue.ClothingAssetCommon.md).[StaticClass](ue_ue.ClothingAssetCommon.md#staticclass)

#### Defined in

[ue/ue.d.ts:27908](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27908)
