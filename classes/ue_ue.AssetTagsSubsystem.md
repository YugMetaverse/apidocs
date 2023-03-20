[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AssetTagsSubsystem

# Class: AssetTagsSubsystem

[ue/ue](../modules/ue_ue.md).AssetTagsSubsystem

## Hierarchy

- [`EngineSubsystem`](ue_ue.EngineSubsystem.md)

  ↳ **`AssetTagsSubsystem`**

## Table of contents

### Constructors

- [constructor](ue_ue.AssetTagsSubsystem.md#constructor)

### Properties

- [\_\_tid\_AssetTagsSubsystem\_\_](ue_ue.AssetTagsSubsystem.md#__tid_assettagssubsystem__)
- [\_\_tid\_DynamicSubsystem\_\_](ue_ue.AssetTagsSubsystem.md#__tid_dynamicsubsystem__)
- [\_\_tid\_EngineSubsystem\_\_](ue_ue.AssetTagsSubsystem.md#__tid_enginesubsystem__)
- [\_\_tid\_Object\_\_](ue_ue.AssetTagsSubsystem.md#__tid_object__)
- [\_\_tid\_Subsystem\_\_](ue_ue.AssetTagsSubsystem.md#__tid_subsystem__)

### Methods

- [AddAssetDataToCollection](ue_ue.AssetTagsSubsystem.md#addassetdatatocollection)
- [AddAssetDatasToCollection](ue_ue.AssetTagsSubsystem.md#addassetdatastocollection)
- [AddAssetPtrToCollection](ue_ue.AssetTagsSubsystem.md#addassetptrtocollection)
- [AddAssetPtrsToCollection](ue_ue.AssetTagsSubsystem.md#addassetptrstocollection)
- [AddAssetToCollection](ue_ue.AssetTagsSubsystem.md#addassettocollection)
- [AddAssetsToCollection](ue_ue.AssetTagsSubsystem.md#addassetstocollection)
- [CollectionExists](ue_ue.AssetTagsSubsystem.md#collectionexists)
- [CreateCollection](ue_ue.AssetTagsSubsystem.md#createcollection)
- [CreateDefaultSubobject](ue_ue.AssetTagsSubsystem.md#createdefaultsubobject)
- [DestroyCollection](ue_ue.AssetTagsSubsystem.md#destroycollection)
- [EmptyCollection](ue_ue.AssetTagsSubsystem.md#emptycollection)
- [ExecuteUbergraph](ue_ue.AssetTagsSubsystem.md#executeubergraph)
- [GetAssetsInCollection](ue_ue.AssetTagsSubsystem.md#getassetsincollection)
- [GetClass](ue_ue.AssetTagsSubsystem.md#getclass)
- [GetCollections](ue_ue.AssetTagsSubsystem.md#getcollections)
- [GetCollectionsContainingAsset](ue_ue.AssetTagsSubsystem.md#getcollectionscontainingasset)
- [GetCollectionsContainingAssetData](ue_ue.AssetTagsSubsystem.md#getcollectionscontainingassetdata)
- [GetCollectionsContainingAssetPtr](ue_ue.AssetTagsSubsystem.md#getcollectionscontainingassetptr)
- [GetName](ue_ue.AssetTagsSubsystem.md#getname)
- [GetOuter](ue_ue.AssetTagsSubsystem.md#getouter)
- [GetWorld](ue_ue.AssetTagsSubsystem.md#getworld)
- [RemoveAssetDataFromCollection](ue_ue.AssetTagsSubsystem.md#removeassetdatafromcollection)
- [RemoveAssetDatasFromCollection](ue_ue.AssetTagsSubsystem.md#removeassetdatasfromcollection)
- [RemoveAssetFromCollection](ue_ue.AssetTagsSubsystem.md#removeassetfromcollection)
- [RemoveAssetPtrFromCollection](ue_ue.AssetTagsSubsystem.md#removeassetptrfromcollection)
- [RemoveAssetPtrsFromCollection](ue_ue.AssetTagsSubsystem.md#removeassetptrsfromcollection)
- [RemoveAssetsFromCollection](ue_ue.AssetTagsSubsystem.md#removeassetsfromcollection)
- [RenameCollection](ue_ue.AssetTagsSubsystem.md#renamecollection)
- [ReparentCollection](ue_ue.AssetTagsSubsystem.md#reparentcollection)
- [Find](ue_ue.AssetTagsSubsystem.md#find)
- [Load](ue_ue.AssetTagsSubsystem.md#load)
- [StaticClass](ue_ue.AssetTagsSubsystem.md#staticclass)

## Constructors

### constructor

• **new AssetTagsSubsystem**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EngineSubsystem](ue_ue.EngineSubsystem.md).[constructor](ue_ue.EngineSubsystem.md#constructor)

## Properties

### \_\_tid\_AssetTagsSubsystem\_\_

• **\_\_tid\_AssetTagsSubsystem\_\_**: `boolean`

___

### \_\_tid\_DynamicSubsystem\_\_

• **\_\_tid\_DynamicSubsystem\_\_**: `boolean`

#### Inherited from

[EngineSubsystem](ue_ue.EngineSubsystem.md).[__tid_DynamicSubsystem__](ue_ue.EngineSubsystem.md#__tid_dynamicsubsystem__)

___

### \_\_tid\_EngineSubsystem\_\_

• **\_\_tid\_EngineSubsystem\_\_**: `boolean`

#### Inherited from

[EngineSubsystem](ue_ue.EngineSubsystem.md).[__tid_EngineSubsystem__](ue_ue.EngineSubsystem.md#__tid_enginesubsystem__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EngineSubsystem](ue_ue.EngineSubsystem.md).[__tid_Object__](ue_ue.EngineSubsystem.md#__tid_object__)

___

### \_\_tid\_Subsystem\_\_

• **\_\_tid\_Subsystem\_\_**: `boolean`

#### Inherited from

[EngineSubsystem](ue_ue.EngineSubsystem.md).[__tid_Subsystem__](ue_ue.EngineSubsystem.md#__tid_subsystem__)

## Methods

### AddAssetDataToCollection

▸ **AddAssetDataToCollection**(`Name`, `AssetData`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `AssetData` | [`AssetData`](ue_ue.AssetData.md) |

#### Returns

`boolean`

___

### AddAssetDatasToCollection

▸ **AddAssetDatasToCollection**(`Name`, `AssetDatas`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `AssetDatas` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\> |

#### Returns

`boolean`

___

### AddAssetPtrToCollection

▸ **AddAssetPtrToCollection**(`Name`, `AssetPtr`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `AssetPtr` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`boolean`

___

### AddAssetPtrsToCollection

▸ **AddAssetPtrsToCollection**(`Name`, `AssetPtrs`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `AssetPtrs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`boolean`

___

### AddAssetToCollection

▸ **AddAssetToCollection**(`Name`, `AssetPathName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `AssetPathName` | `string` |

#### Returns

`boolean`

___

### AddAssetsToCollection

▸ **AddAssetsToCollection**(`Name`, `AssetPathNames`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `AssetPathNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`boolean`

___

### CollectionExists

▸ **CollectionExists**(`Name`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |

#### Returns

`boolean`

___

### CreateCollection

▸ **CreateCollection**(`Name`, `ShareType`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `ShareType` | [`ECollectionScriptingShareType`](../enums/ue_ue.ECollectionScriptingShareType.md) |

#### Returns

`boolean`

___

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

[EngineSubsystem](ue_ue.EngineSubsystem.md).[CreateDefaultSubobject](ue_ue.EngineSubsystem.md#createdefaultsubobject)

___

### DestroyCollection

▸ **DestroyCollection**(`Name`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |

#### Returns

`boolean`

___

### EmptyCollection

▸ **EmptyCollection**(`Name`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |

#### Returns

`boolean`

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

[EngineSubsystem](ue_ue.EngineSubsystem.md).[ExecuteUbergraph](ue_ue.EngineSubsystem.md#executeubergraph)

___

### GetAssetsInCollection

▸ **GetAssetsInCollection**(`Name`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\>

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EngineSubsystem](ue_ue.EngineSubsystem.md).[GetClass](ue_ue.EngineSubsystem.md#getclass)

___

### GetCollections

▸ **GetCollections**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### GetCollectionsContainingAsset

▸ **GetCollectionsContainingAsset**(`AssetPathName`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetPathName` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### GetCollectionsContainingAssetData

▸ **GetCollectionsContainingAssetData**(`AssetData`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetData` | [`AssetData`](ue_ue.AssetData.md) |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### GetCollectionsContainingAssetPtr

▸ **GetCollectionsContainingAssetPtr**(`AssetPtr`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetPtr` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EngineSubsystem](ue_ue.EngineSubsystem.md).[GetName](ue_ue.EngineSubsystem.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EngineSubsystem](ue_ue.EngineSubsystem.md).[GetOuter](ue_ue.EngineSubsystem.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EngineSubsystem](ue_ue.EngineSubsystem.md).[GetWorld](ue_ue.EngineSubsystem.md#getworld)

___

### RemoveAssetDataFromCollection

▸ **RemoveAssetDataFromCollection**(`Name`, `AssetData`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `AssetData` | [`AssetData`](ue_ue.AssetData.md) |

#### Returns

`boolean`

___

### RemoveAssetDatasFromCollection

▸ **RemoveAssetDatasFromCollection**(`Name`, `AssetDatas`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `AssetDatas` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\> |

#### Returns

`boolean`

___

### RemoveAssetFromCollection

▸ **RemoveAssetFromCollection**(`Name`, `AssetPathName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `AssetPathName` | `string` |

#### Returns

`boolean`

___

### RemoveAssetPtrFromCollection

▸ **RemoveAssetPtrFromCollection**(`Name`, `AssetPtr`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `AssetPtr` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`boolean`

___

### RemoveAssetPtrsFromCollection

▸ **RemoveAssetPtrsFromCollection**(`Name`, `AssetPtrs`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `AssetPtrs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`boolean`

___

### RemoveAssetsFromCollection

▸ **RemoveAssetsFromCollection**(`Name`, `AssetPathNames`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `AssetPathNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`boolean`

___

### RenameCollection

▸ **RenameCollection**(`Name`, `NewName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `NewName` | `string` |

#### Returns

`boolean`

___

### ReparentCollection

▸ **ReparentCollection**(`Name`, `NewParentName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `NewParentName` | `string` |

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AssetTagsSubsystem`](ue_ue.AssetTagsSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AssetTagsSubsystem`](ue_ue.AssetTagsSubsystem.md)

#### Overrides

[EngineSubsystem](ue_ue.EngineSubsystem.md).[Find](ue_ue.EngineSubsystem.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AssetTagsSubsystem`](ue_ue.AssetTagsSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AssetTagsSubsystem`](ue_ue.AssetTagsSubsystem.md)

#### Overrides

[EngineSubsystem](ue_ue.EngineSubsystem.md).[Load](ue_ue.EngineSubsystem.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EngineSubsystem](ue_ue.EngineSubsystem.md).[StaticClass](ue_ue.EngineSubsystem.md#staticclass)
