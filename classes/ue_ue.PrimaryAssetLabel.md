[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PrimaryAssetLabel

# Class: PrimaryAssetLabel

[ue/ue](../modules/ue_ue.md).PrimaryAssetLabel

## Hierarchy

- [`PrimaryDataAsset`](ue_ue.PrimaryDataAsset.md)

  ↳ **`PrimaryAssetLabel`**

## Table of contents

### Constructors

- [constructor](ue_ue.PrimaryAssetLabel.md#constructor)

### Properties

- [AssetBundleData](ue_ue.PrimaryAssetLabel.md#assetbundledata)
- [AssetCollection](ue_ue.PrimaryAssetLabel.md#assetcollection)
- [ExplicitAssets](ue_ue.PrimaryAssetLabel.md#explicitassets)
- [ExplicitBlueprints](ue_ue.PrimaryAssetLabel.md#explicitblueprints)
- [NativeClass](ue_ue.PrimaryAssetLabel.md#nativeclass)
- [Rules](ue_ue.PrimaryAssetLabel.md#rules)
- [\_\_tid\_DataAsset\_\_](ue_ue.PrimaryAssetLabel.md#__tid_dataasset__)
- [\_\_tid\_Object\_\_](ue_ue.PrimaryAssetLabel.md#__tid_object__)
- [\_\_tid\_PrimaryAssetLabel\_\_](ue_ue.PrimaryAssetLabel.md#__tid_primaryassetlabel__)
- [\_\_tid\_PrimaryDataAsset\_\_](ue_ue.PrimaryAssetLabel.md#__tid_primarydataasset__)
- [bIsRuntimeLabel](ue_ue.PrimaryAssetLabel.md#bisruntimelabel)
- [bLabelAssetsInMyDirectory](ue_ue.PrimaryAssetLabel.md#blabelassetsinmydirectory)

### Methods

- [CreateDefaultSubobject](ue_ue.PrimaryAssetLabel.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PrimaryAssetLabel.md#executeubergraph)
- [GetClass](ue_ue.PrimaryAssetLabel.md#getclass)
- [GetName](ue_ue.PrimaryAssetLabel.md#getname)
- [GetOuter](ue_ue.PrimaryAssetLabel.md#getouter)
- [GetWorld](ue_ue.PrimaryAssetLabel.md#getworld)
- [Find](ue_ue.PrimaryAssetLabel.md#find)
- [Load](ue_ue.PrimaryAssetLabel.md#load)
- [StaticClass](ue_ue.PrimaryAssetLabel.md#staticclass)

## Constructors

### constructor

• **new PrimaryAssetLabel**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PrimaryDataAsset](ue_ue.PrimaryDataAsset.md).[constructor](ue_ue.PrimaryDataAsset.md#constructor)

## Properties

### AssetBundleData

• **AssetBundleData**: [`AssetBundleData`](ue_ue.AssetBundleData.md)

#### Inherited from

[PrimaryDataAsset](ue_ue.PrimaryDataAsset.md).[AssetBundleData](ue_ue.PrimaryDataAsset.md#assetbundledata)

___

### AssetCollection

• **AssetCollection**: [`CollectionReference`](ue_ue.CollectionReference.md)

___

### ExplicitAssets

• **ExplicitAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`Object`](ue_ue.Object.md)\>\>

___

### ExplicitBlueprints

• **ExplicitBlueprints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TSoftClassPtr`](../modules/ue_puerts.md#tsoftclassptr)<[`Object`](ue_ue.Object.md)\>\>

___

### NativeClass

• **NativeClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[PrimaryDataAsset](ue_ue.PrimaryDataAsset.md).[NativeClass](ue_ue.PrimaryDataAsset.md#nativeclass)

___

### Rules

• **Rules**: [`PrimaryAssetRules`](ue_ue.PrimaryAssetRules.md)

___

### \_\_tid\_DataAsset\_\_

• **\_\_tid\_DataAsset\_\_**: `boolean`

#### Inherited from

[PrimaryDataAsset](ue_ue.PrimaryDataAsset.md).[__tid_DataAsset__](ue_ue.PrimaryDataAsset.md#__tid_dataasset__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PrimaryDataAsset](ue_ue.PrimaryDataAsset.md).[__tid_Object__](ue_ue.PrimaryDataAsset.md#__tid_object__)

___

### \_\_tid\_PrimaryAssetLabel\_\_

• **\_\_tid\_PrimaryAssetLabel\_\_**: `boolean`

___

### \_\_tid\_PrimaryDataAsset\_\_

• **\_\_tid\_PrimaryDataAsset\_\_**: `boolean`

#### Inherited from

[PrimaryDataAsset](ue_ue.PrimaryDataAsset.md).[__tid_PrimaryDataAsset__](ue_ue.PrimaryDataAsset.md#__tid_primarydataasset__)

___

### bIsRuntimeLabel

• **bIsRuntimeLabel**: `boolean`

___

### bLabelAssetsInMyDirectory

• **bLabelAssetsInMyDirectory**: `boolean`

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

[PrimaryDataAsset](ue_ue.PrimaryDataAsset.md).[CreateDefaultSubobject](ue_ue.PrimaryDataAsset.md#createdefaultsubobject)

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

[PrimaryDataAsset](ue_ue.PrimaryDataAsset.md).[ExecuteUbergraph](ue_ue.PrimaryDataAsset.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PrimaryDataAsset](ue_ue.PrimaryDataAsset.md).[GetClass](ue_ue.PrimaryDataAsset.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PrimaryDataAsset](ue_ue.PrimaryDataAsset.md).[GetName](ue_ue.PrimaryDataAsset.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PrimaryDataAsset](ue_ue.PrimaryDataAsset.md).[GetOuter](ue_ue.PrimaryDataAsset.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PrimaryDataAsset](ue_ue.PrimaryDataAsset.md).[GetWorld](ue_ue.PrimaryDataAsset.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PrimaryAssetLabel`](ue_ue.PrimaryAssetLabel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PrimaryAssetLabel`](ue_ue.PrimaryAssetLabel.md)

#### Overrides

[PrimaryDataAsset](ue_ue.PrimaryDataAsset.md).[Find](ue_ue.PrimaryDataAsset.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PrimaryAssetLabel`](ue_ue.PrimaryAssetLabel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PrimaryAssetLabel`](ue_ue.PrimaryAssetLabel.md)

#### Overrides

[PrimaryDataAsset](ue_ue.PrimaryDataAsset.md).[Load](ue_ue.PrimaryDataAsset.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PrimaryDataAsset](ue_ue.PrimaryDataAsset.md).[StaticClass](ue_ue.PrimaryDataAsset.md#staticclass)
