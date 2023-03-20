[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AssetRegistry

# Class: AssetRegistry

[ue/ue](../modules/ue_ue.md).AssetRegistry

## Hierarchy

- [`Interface`](ue_ue.Interface.md)

  ↳ **`AssetRegistry`**

## Table of contents

### Constructors

- [constructor](ue_ue.AssetRegistry.md#constructor)

### Properties

- [\_\_tid\_AssetRegistry\_\_](ue_ue.AssetRegistry.md#__tid_assetregistry__)
- [\_\_tid\_Interface\_\_](ue_ue.AssetRegistry.md#__tid_interface__)
- [\_\_tid\_Object\_\_](ue_ue.AssetRegistry.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AssetRegistry.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AssetRegistry.md#executeubergraph)
- [GetAllAssets](ue_ue.AssetRegistry.md#getallassets)
- [GetAllCachedPaths](ue_ue.AssetRegistry.md#getallcachedpaths)
- [GetAssetByObjectPath](ue_ue.AssetRegistry.md#getassetbyobjectpath)
- [GetAssets](ue_ue.AssetRegistry.md#getassets)
- [GetAssetsByClass](ue_ue.AssetRegistry.md#getassetsbyclass)
- [GetAssetsByPackageName](ue_ue.AssetRegistry.md#getassetsbypackagename)
- [GetAssetsByPath](ue_ue.AssetRegistry.md#getassetsbypath)
- [GetClass](ue_ue.AssetRegistry.md#getclass)
- [GetName](ue_ue.AssetRegistry.md#getname)
- [GetOuter](ue_ue.AssetRegistry.md#getouter)
- [GetSubPaths](ue_ue.AssetRegistry.md#getsubpaths)
- [GetWorld](ue_ue.AssetRegistry.md#getworld)
- [HasAssets](ue_ue.AssetRegistry.md#hasassets)
- [IsLoadingAssets](ue_ue.AssetRegistry.md#isloadingassets)
- [K2\_GetDependencies](ue_ue.AssetRegistry.md#k2_getdependencies)
- [K2\_GetReferencers](ue_ue.AssetRegistry.md#k2_getreferencers)
- [PrioritizeSearchPath](ue_ue.AssetRegistry.md#prioritizesearchpath)
- [RunAssetsThroughFilter](ue_ue.AssetRegistry.md#runassetsthroughfilter)
- [ScanFilesSynchronous](ue_ue.AssetRegistry.md#scanfilessynchronous)
- [ScanModifiedAssetFiles](ue_ue.AssetRegistry.md#scanmodifiedassetfiles)
- [ScanPathsSynchronous](ue_ue.AssetRegistry.md#scanpathssynchronous)
- [SearchAllAssets](ue_ue.AssetRegistry.md#searchallassets)
- [UseFilterToExcludeAssets](ue_ue.AssetRegistry.md#usefiltertoexcludeassets)
- [Find](ue_ue.AssetRegistry.md#find)
- [Load](ue_ue.AssetRegistry.md#load)
- [StaticClass](ue_ue.AssetRegistry.md#staticclass)

## Constructors

### constructor

• **new AssetRegistry**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Interface](ue_ue.Interface.md).[constructor](ue_ue.Interface.md#constructor)

## Properties

### \_\_tid\_AssetRegistry\_\_

• **\_\_tid\_AssetRegistry\_\_**: `boolean`

___

### \_\_tid\_Interface\_\_

• **\_\_tid\_Interface\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Interface__](ue_ue.Interface.md#__tid_interface__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Object__](ue_ue.Interface.md#__tid_object__)

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

[Interface](ue_ue.Interface.md).[CreateDefaultSubobject](ue_ue.Interface.md#createdefaultsubobject)

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

[Interface](ue_ue.Interface.md).[ExecuteUbergraph](ue_ue.Interface.md#executeubergraph)

___

### GetAllAssets

▸ **GetAllAssets**(`OutAssetData`, `bIncludeOnlyOnDiskAssets?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutAssetData` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\>\> |
| `bIncludeOnlyOnDiskAssets?` | `boolean` |

#### Returns

`boolean`

___

### GetAllCachedPaths

▸ **GetAllCachedPaths**(`OutPathList`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutPathList` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

___

### GetAssetByObjectPath

▸ **GetAssetByObjectPath**(`ObjectPath`, `bIncludeOnlyOnDiskAssets?`): [`AssetData`](ue_ue.AssetData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ObjectPath` | `string` |
| `bIncludeOnlyOnDiskAssets?` | `boolean` |

#### Returns

[`AssetData`](ue_ue.AssetData.md)

___

### GetAssets

▸ **GetAssets**(`Filter`, `OutAssetData`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Filter` | [`ARFilter`](ue_ue.ARFilter.md) |
| `OutAssetData` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\>\> |

#### Returns

`boolean`

___

### GetAssetsByClass

▸ **GetAssetsByClass**(`ClassName`, `OutAssetData`, `bSearchSubClasses?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ClassName` | `string` |
| `OutAssetData` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\>\> |
| `bSearchSubClasses?` | `boolean` |

#### Returns

`boolean`

___

### GetAssetsByPackageName

▸ **GetAssetsByPackageName**(`PackageName`, `OutAssetData`, `bIncludeOnlyOnDiskAssets?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackageName` | `string` |
| `OutAssetData` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\>\> |
| `bIncludeOnlyOnDiskAssets?` | `boolean` |

#### Returns

`boolean`

___

### GetAssetsByPath

▸ **GetAssetsByPath**(`PackagePath`, `OutAssetData`, `bRecursive?`, `bIncludeOnlyOnDiskAssets?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackagePath` | `string` |
| `OutAssetData` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\>\> |
| `bRecursive?` | `boolean` |
| `bIncludeOnlyOnDiskAssets?` | `boolean` |

#### Returns

`boolean`

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetClass](ue_ue.Interface.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Interface](ue_ue.Interface.md).[GetName](ue_ue.Interface.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetOuter](ue_ue.Interface.md#getouter)

___

### GetSubPaths

▸ **GetSubPaths**(`InBasePath`, `OutPathList`, `bInRecurse`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBasePath` | `string` |
| `OutPathList` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |
| `bInRecurse` | `boolean` |

#### Returns

`void`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetWorld](ue_ue.Interface.md#getworld)

___

### HasAssets

▸ **HasAssets**(`PackagePath`, `bRecursive?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackagePath` | `string` |
| `bRecursive?` | `boolean` |

#### Returns

`boolean`

___

### IsLoadingAssets

▸ **IsLoadingAssets**(): `boolean`

#### Returns

`boolean`

___

### K2\_GetDependencies

▸ **K2_GetDependencies**(`PackageName`, `DependencyOptions`, `OutDependencies`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackageName` | `string` |
| `DependencyOptions` | [`AssetRegistryDependencyOptions`](ue_ue.AssetRegistryDependencyOptions.md) |
| `OutDependencies` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`boolean`

___

### K2\_GetReferencers

▸ **K2_GetReferencers**(`PackageName`, `ReferenceOptions`, `OutReferencers`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackageName` | `string` |
| `ReferenceOptions` | [`AssetRegistryDependencyOptions`](ue_ue.AssetRegistryDependencyOptions.md) |
| `OutReferencers` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`boolean`

___

### PrioritizeSearchPath

▸ **PrioritizeSearchPath**(`PathToPrioritize`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PathToPrioritize` | `string` |

#### Returns

`void`

___

### RunAssetsThroughFilter

▸ **RunAssetsThroughFilter**(`AssetDataList`, `Filter`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetDataList` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\>\> |
| `Filter` | [`ARFilter`](ue_ue.ARFilter.md) |

#### Returns

`void`

___

### ScanFilesSynchronous

▸ **ScanFilesSynchronous**(`InFilePaths`, `bForceRescan?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFilePaths` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `bForceRescan?` | `boolean` |

#### Returns

`void`

___

### ScanModifiedAssetFiles

▸ **ScanModifiedAssetFiles**(`InFilePaths`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFilePaths` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`void`

___

### ScanPathsSynchronous

▸ **ScanPathsSynchronous**(`InPaths`, `bForceRescan?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPaths` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `bForceRescan?` | `boolean` |

#### Returns

`void`

___

### SearchAllAssets

▸ **SearchAllAssets**(`bSynchronousSearch`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bSynchronousSearch` | `boolean` |

#### Returns

`void`

___

### UseFilterToExcludeAssets

▸ **UseFilterToExcludeAssets**(`AssetDataList`, `Filter`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetDataList` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\>\> |
| `Filter` | [`ARFilter`](ue_ue.ARFilter.md) |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AssetRegistry`](ue_ue.AssetRegistry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AssetRegistry`](ue_ue.AssetRegistry.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Find](ue_ue.Interface.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AssetRegistry`](ue_ue.AssetRegistry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AssetRegistry`](ue_ue.AssetRegistry.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Load](ue_ue.Interface.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Interface](ue_ue.Interface.md).[StaticClass](ue_ue.Interface.md#staticclass)
