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

#### Defined in

[ue/ue.d.ts:21895](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21895)

## Properties

### \_\_tid\_AssetTagsSubsystem\_\_

• **\_\_tid\_AssetTagsSubsystem\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:21923](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21923)

___

### \_\_tid\_DynamicSubsystem\_\_

• **\_\_tid\_DynamicSubsystem\_\_**: `boolean`

#### Inherited from

[EngineSubsystem](ue_ue.EngineSubsystem.md).[__tid_DynamicSubsystem__](ue_ue.EngineSubsystem.md#__tid_dynamicsubsystem__)

#### Defined in

[ue/ue.d.ts:21573](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21573)

___

### \_\_tid\_EngineSubsystem\_\_

• **\_\_tid\_EngineSubsystem\_\_**: `boolean`

#### Inherited from

[EngineSubsystem](ue_ue.EngineSubsystem.md).[__tid_EngineSubsystem__](ue_ue.EngineSubsystem.md#__tid_enginesubsystem__)

#### Defined in

[ue/ue.d.ts:21890](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21890)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EngineSubsystem](ue_ue.EngineSubsystem.md).[__tid_Object__](ue_ue.EngineSubsystem.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_Subsystem\_\_

• **\_\_tid\_Subsystem\_\_**: `boolean`

#### Inherited from

[EngineSubsystem](ue_ue.EngineSubsystem.md).[__tid_Subsystem__](ue_ue.EngineSubsystem.md#__tid_subsystem__)

#### Defined in

[ue/ue.d.ts:21564](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21564)

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

#### Defined in

[ue/ue.d.ts:21897](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21897)

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

#### Defined in

[ue/ue.d.ts:21896](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21896)

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

#### Defined in

[ue/ue.d.ts:21899](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21899)

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

#### Defined in

[ue/ue.d.ts:21898](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21898)

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

#### Defined in

[ue/ue.d.ts:21901](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21901)

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

#### Defined in

[ue/ue.d.ts:21900](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21900)

___

### CollectionExists

▸ **CollectionExists**(`Name`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:21902](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21902)

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

#### Defined in

[ue/ue.d.ts:21903](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21903)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### DestroyCollection

▸ **DestroyCollection**(`Name`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:21904](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21904)

___

### EmptyCollection

▸ **EmptyCollection**(`Name`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:21905](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21905)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetAssetsInCollection

▸ **GetAssetsInCollection**(`Name`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\>

#### Defined in

[ue/ue.d.ts:21906](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21906)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EngineSubsystem](ue_ue.EngineSubsystem.md).[GetClass](ue_ue.EngineSubsystem.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetCollections

▸ **GetCollections**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:21907](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21907)

___

### GetCollectionsContainingAsset

▸ **GetCollectionsContainingAsset**(`AssetPathName`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetPathName` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:21908](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21908)

___

### GetCollectionsContainingAssetData

▸ **GetCollectionsContainingAssetData**(`AssetData`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetData` | [`AssetData`](ue_ue.AssetData.md) |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:21909](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21909)

___

### GetCollectionsContainingAssetPtr

▸ **GetCollectionsContainingAssetPtr**(`AssetPtr`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetPtr` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:21910](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21910)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EngineSubsystem](ue_ue.EngineSubsystem.md).[GetName](ue_ue.EngineSubsystem.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EngineSubsystem](ue_ue.EngineSubsystem.md).[GetOuter](ue_ue.EngineSubsystem.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EngineSubsystem](ue_ue.EngineSubsystem.md).[GetWorld](ue_ue.EngineSubsystem.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:21911](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21911)

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

#### Defined in

[ue/ue.d.ts:21912](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21912)

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

#### Defined in

[ue/ue.d.ts:21913](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21913)

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

#### Defined in

[ue/ue.d.ts:21914](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21914)

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

#### Defined in

[ue/ue.d.ts:21915](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21915)

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

#### Defined in

[ue/ue.d.ts:21916](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21916)

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

#### Defined in

[ue/ue.d.ts:21917](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21917)

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

#### Defined in

[ue/ue.d.ts:21918](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21918)

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

#### Defined in

[ue/ue.d.ts:21920](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21920)

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

#### Defined in

[ue/ue.d.ts:21921](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21921)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EngineSubsystem](ue_ue.EngineSubsystem.md).[StaticClass](ue_ue.EngineSubsystem.md#staticclass)

#### Defined in

[ue/ue.d.ts:21919](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21919)
