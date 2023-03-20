[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ClothingAssetCommon

# Class: ClothingAssetCommon

[ue/ue](../modules/ue_ue.md).ClothingAssetCommon

## Hierarchy

- [`ClothingAssetBase`](ue_ue.ClothingAssetBase.md)

  ↳ **`ClothingAssetCommon`**

  ↳↳ [`ClothingAssetNv`](ue_ue.ClothingAssetNv.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ClothingAssetCommon.md#constructor)

### Properties

- [AssetGuid](ue_ue.ClothingAssetCommon.md#assetguid)
- [ClothLodData](ue_ue.ClothingAssetCommon.md#clothloddata)
- [ClothSimConfig](ue_ue.ClothingAssetCommon.md#clothsimconfig)
- [CustomData](ue_ue.ClothingAssetCommon.md#customdata)
- [ImportedFilePath](ue_ue.ClothingAssetCommon.md#importedfilepath)
- [LodMap](ue_ue.ClothingAssetCommon.md#lodmap)
- [PhysicsAsset](ue_ue.ClothingAssetCommon.md#physicsasset)
- [ReferenceBoneIndex](ue_ue.ClothingAssetCommon.md#referenceboneindex)
- [UsedBoneIndices](ue_ue.ClothingAssetCommon.md#usedboneindices)
- [UsedBoneNames](ue_ue.ClothingAssetCommon.md#usedbonenames)
- [\_\_tid\_ClothingAssetBase\_\_](ue_ue.ClothingAssetCommon.md#__tid_clothingassetbase__)
- [\_\_tid\_ClothingAssetCommon\_\_](ue_ue.ClothingAssetCommon.md#__tid_clothingassetcommon__)
- [\_\_tid\_Object\_\_](ue_ue.ClothingAssetCommon.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ClothingAssetCommon.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ClothingAssetCommon.md#executeubergraph)
- [GetClass](ue_ue.ClothingAssetCommon.md#getclass)
- [GetName](ue_ue.ClothingAssetCommon.md#getname)
- [GetOuter](ue_ue.ClothingAssetCommon.md#getouter)
- [GetWorld](ue_ue.ClothingAssetCommon.md#getworld)
- [Find](ue_ue.ClothingAssetCommon.md#find)
- [Load](ue_ue.ClothingAssetCommon.md#load)
- [StaticClass](ue_ue.ClothingAssetCommon.md#staticclass)

## Constructors

### constructor

• **new ClothingAssetCommon**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ClothingAssetBase](ue_ue.ClothingAssetBase.md).[constructor](ue_ue.ClothingAssetBase.md#constructor)

#### Defined in

[ue/ue.d.ts:27776](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27776)

## Properties

### AssetGuid

• **AssetGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[ClothingAssetBase](ue_ue.ClothingAssetBase.md).[AssetGuid](ue_ue.ClothingAssetBase.md#assetguid)

#### Defined in

[ue/ue.d.ts:3961](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3961)

___

### ClothLodData

• **ClothLodData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothLODDataBase`](ue_ue.ClothLODDataBase.md)\>

#### Defined in

[ue/ue.d.ts:27779](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27779)

___

### ClothSimConfig

• **ClothSimConfig**: [`ClothConfigBase`](ue_ue.ClothConfigBase.md)

#### Defined in

[ue/ue.d.ts:27778](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27778)

___

### CustomData

• **CustomData**: [`ClothingAssetCustomData`](ue_ue.ClothingAssetCustomData.md)

#### Defined in

[ue/ue.d.ts:27784](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27784)

___

### ImportedFilePath

• **ImportedFilePath**: `string`

#### Inherited from

[ClothingAssetBase](ue_ue.ClothingAssetBase.md).[ImportedFilePath](ue_ue.ClothingAssetBase.md#importedfilepath)

#### Defined in

[ue/ue.d.ts:3960](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3960)

___

### LodMap

• **LodMap**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:27780](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27780)

___

### PhysicsAsset

• **PhysicsAsset**: [`PhysicsAsset`](ue_ue.PhysicsAsset.md)

#### Defined in

[ue/ue.d.ts:27777](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27777)

___

### ReferenceBoneIndex

• **ReferenceBoneIndex**: `number`

#### Defined in

[ue/ue.d.ts:27783](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27783)

___

### UsedBoneIndices

• **UsedBoneIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:27782](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27782)

___

### UsedBoneNames

• **UsedBoneNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:27781](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27781)

___

### \_\_tid\_ClothingAssetBase\_\_

• **\_\_tid\_ClothingAssetBase\_\_**: `boolean`

#### Inherited from

[ClothingAssetBase](ue_ue.ClothingAssetBase.md).[__tid_ClothingAssetBase__](ue_ue.ClothingAssetBase.md#__tid_clothingassetbase__)

#### Defined in

[ue/ue.d.ts:3966](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3966)

___

### \_\_tid\_ClothingAssetCommon\_\_

• **\_\_tid\_ClothingAssetCommon\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:27789](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27789)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ClothingAssetBase](ue_ue.ClothingAssetBase.md).[__tid_Object__](ue_ue.ClothingAssetBase.md#__tid_object__)

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

[ClothingAssetBase](ue_ue.ClothingAssetBase.md).[CreateDefaultSubobject](ue_ue.ClothingAssetBase.md#createdefaultsubobject)

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

[ClothingAssetBase](ue_ue.ClothingAssetBase.md).[ExecuteUbergraph](ue_ue.ClothingAssetBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ClothingAssetBase](ue_ue.ClothingAssetBase.md).[GetClass](ue_ue.ClothingAssetBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ClothingAssetBase](ue_ue.ClothingAssetBase.md).[GetName](ue_ue.ClothingAssetBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ClothingAssetBase](ue_ue.ClothingAssetBase.md).[GetOuter](ue_ue.ClothingAssetBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ClothingAssetBase](ue_ue.ClothingAssetBase.md).[GetWorld](ue_ue.ClothingAssetBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ClothingAssetCommon`](ue_ue.ClothingAssetCommon.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ClothingAssetCommon`](ue_ue.ClothingAssetCommon.md)

#### Overrides

[ClothingAssetBase](ue_ue.ClothingAssetBase.md).[Find](ue_ue.ClothingAssetBase.md#find)

#### Defined in

[ue/ue.d.ts:27786](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27786)

___

### Load

▸ `Static` **Load**(`InName`): [`ClothingAssetCommon`](ue_ue.ClothingAssetCommon.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ClothingAssetCommon`](ue_ue.ClothingAssetCommon.md)

#### Overrides

[ClothingAssetBase](ue_ue.ClothingAssetBase.md).[Load](ue_ue.ClothingAssetBase.md#load)

#### Defined in

[ue/ue.d.ts:27787](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27787)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ClothingAssetBase](ue_ue.ClothingAssetBase.md).[StaticClass](ue_ue.ClothingAssetBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:27785](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27785)
