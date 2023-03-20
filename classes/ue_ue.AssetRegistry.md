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

#### Defined in

[ue/ue.d.ts:21804](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21804)

## Properties

### \_\_tid\_AssetRegistry\_\_

• **\_\_tid\_AssetRegistry\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:21828](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21828)

___

### \_\_tid\_Interface\_\_

• **\_\_tid\_Interface\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Interface__](ue_ue.Interface.md#__tid_interface__)

#### Defined in

[ue/ue.d.ts:8142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8142)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Object__](ue_ue.Interface.md#__tid_object__)

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

[Interface](ue_ue.Interface.md).[CreateDefaultSubobject](ue_ue.Interface.md#createdefaultsubobject)

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

[Interface](ue_ue.Interface.md).[ExecuteUbergraph](ue_ue.Interface.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

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

#### Defined in

[ue/ue.d.ts:21805](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21805)

___

### GetAllCachedPaths

▸ **GetAllCachedPaths**(`OutPathList`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutPathList` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21806](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21806)

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

#### Defined in

[ue/ue.d.ts:21807](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21807)

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

#### Defined in

[ue/ue.d.ts:21808](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21808)

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

#### Defined in

[ue/ue.d.ts:21809](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21809)

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

#### Defined in

[ue/ue.d.ts:21810](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21810)

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

#### Defined in

[ue/ue.d.ts:21811](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21811)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetClass](ue_ue.Interface.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Interface](ue_ue.Interface.md).[GetName](ue_ue.Interface.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetOuter](ue_ue.Interface.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

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

#### Defined in

[ue/ue.d.ts:21812](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21812)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetWorld](ue_ue.Interface.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:21813](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21813)

___

### IsLoadingAssets

▸ **IsLoadingAssets**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:21814](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21814)

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

#### Defined in

[ue/ue.d.ts:21815](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21815)

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

#### Defined in

[ue/ue.d.ts:21816](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21816)

___

### PrioritizeSearchPath

▸ **PrioritizeSearchPath**(`PathToPrioritize`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PathToPrioritize` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21817](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21817)

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

#### Defined in

[ue/ue.d.ts:21818](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21818)

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

#### Defined in

[ue/ue.d.ts:21819](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21819)

___

### ScanModifiedAssetFiles

▸ **ScanModifiedAssetFiles**(`InFilePaths`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFilePaths` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21820](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21820)

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

#### Defined in

[ue/ue.d.ts:21821](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21821)

___

### SearchAllAssets

▸ **SearchAllAssets**(`bSynchronousSearch`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bSynchronousSearch` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21822](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21822)

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

#### Defined in

[ue/ue.d.ts:21823](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21823)

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

#### Defined in

[ue/ue.d.ts:21825](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21825)

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

#### Defined in

[ue/ue.d.ts:21826](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21826)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Interface](ue_ue.Interface.md).[StaticClass](ue_ue.Interface.md#staticclass)

#### Defined in

[ue/ue.d.ts:21824](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21824)
