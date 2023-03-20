[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DatasmithStaticMeshImportData

# Class: DatasmithStaticMeshImportData

[ue/ue](../modules/ue_ue.md).DatasmithStaticMeshImportData

## Hierarchy

- [`DatasmithAssetImportData`](ue_ue.DatasmithAssetImportData.md)

  ↳ **`DatasmithStaticMeshImportData`**

  ↳↳ [`DatasmithStaticMeshCADImportData`](ue_ue.DatasmithStaticMeshCADImportData.md)

  ↳↳ [`DatasmithStaticMeshGLTFImportData`](ue_ue.DatasmithStaticMeshGLTFImportData.md)

  ↳↳ [`DatasmithStaticMeshIFCImportData`](ue_ue.DatasmithStaticMeshIFCImportData.md)

## Table of contents

### Constructors

- [constructor](ue_ue.DatasmithStaticMeshImportData.md#constructor)

### Properties

- [AdditionalData](ue_ue.DatasmithStaticMeshImportData.md#additionaldata)
- [AssetImportOptions](ue_ue.DatasmithStaticMeshImportData.md#assetimportoptions)
- [ImportOptions](ue_ue.DatasmithStaticMeshImportData.md#importoptions)
- [SourceData](ue_ue.DatasmithStaticMeshImportData.md#sourcedata)
- [SourceFilePath](ue_ue.DatasmithStaticMeshImportData.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.DatasmithStaticMeshImportData.md#sourcefiletimestamp)
- [\_\_tid\_AssetImportData\_\_](ue_ue.DatasmithStaticMeshImportData.md#__tid_assetimportdata__)
- [\_\_tid\_DatasmithAssetImportData\_\_](ue_ue.DatasmithStaticMeshImportData.md#__tid_datasmithassetimportdata__)
- [\_\_tid\_DatasmithStaticMeshImportData\_\_](ue_ue.DatasmithStaticMeshImportData.md#__tid_datasmithstaticmeshimportdata__)
- [\_\_tid\_Object\_\_](ue_ue.DatasmithStaticMeshImportData.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.DatasmithStaticMeshImportData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DatasmithStaticMeshImportData.md#executeubergraph)
- [GetClass](ue_ue.DatasmithStaticMeshImportData.md#getclass)
- [GetName](ue_ue.DatasmithStaticMeshImportData.md#getname)
- [GetOuter](ue_ue.DatasmithStaticMeshImportData.md#getouter)
- [GetWorld](ue_ue.DatasmithStaticMeshImportData.md#getworld)
- [K2\_ExtractFilenames](ue_ue.DatasmithStaticMeshImportData.md#k2_extractfilenames)
- [K2\_GetFirstFilename](ue_ue.DatasmithStaticMeshImportData.md#k2_getfirstfilename)
- [Find](ue_ue.DatasmithStaticMeshImportData.md#find)
- [Load](ue_ue.DatasmithStaticMeshImportData.md#load)
- [StaticClass](ue_ue.DatasmithStaticMeshImportData.md#staticclass)

## Constructors

### constructor

• **new DatasmithStaticMeshImportData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[constructor](ue_ue.DatasmithAssetImportData.md#constructor)

#### Defined in

[ue/ue.d.ts:30016](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30016)

## Properties

### AdditionalData

• **AdditionalData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DatasmithAdditionalData`](ue_ue.DatasmithAdditionalData.md)\>

#### Inherited from

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[AdditionalData](ue_ue.DatasmithAssetImportData.md#additionaldata)

#### Defined in

[ue/ue.d.ts:29408](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29408)

___

### AssetImportOptions

• **AssetImportOptions**: [`DatasmithAssetImportOptions`](ue_ue.DatasmithAssetImportOptions.md)

#### Inherited from

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[AssetImportOptions](ue_ue.DatasmithAssetImportData.md#assetimportoptions)

#### Defined in

[ue/ue.d.ts:29407](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29407)

___

### ImportOptions

• **ImportOptions**: [`DatasmithStaticMeshImportOptions`](ue_ue.DatasmithStaticMeshImportOptions.md)

#### Defined in

[ue/ue.d.ts:30017](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30017)

___

### SourceData

• **SourceData**: [`AssetImportInfo`](ue_ue.AssetImportInfo.md)

#### Inherited from

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[SourceData](ue_ue.DatasmithAssetImportData.md#sourcedata)

#### Defined in

[ue/ue.d.ts:38](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[SourceFilePath](ue_ue.DatasmithAssetImportData.md#sourcefilepath)

#### Defined in

[ue/ue.d.ts:36](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36)

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

#### Inherited from

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[SourceFileTimestamp](ue_ue.DatasmithAssetImportData.md#sourcefiletimestamp)

#### Defined in

[ue/ue.d.ts:37](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37)

___

### \_\_tid\_AssetImportData\_\_

• **\_\_tid\_AssetImportData\_\_**: `boolean`

#### Inherited from

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[__tid_AssetImportData__](ue_ue.DatasmithAssetImportData.md#__tid_assetimportdata__)

#### Defined in

[ue/ue.d.ts:45](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45)

___

### \_\_tid\_DatasmithAssetImportData\_\_

• **\_\_tid\_DatasmithAssetImportData\_\_**: `boolean`

#### Inherited from

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[__tid_DatasmithAssetImportData__](ue_ue.DatasmithAssetImportData.md#__tid_datasmithassetimportdata__)

#### Defined in

[ue/ue.d.ts:29413](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29413)

___

### \_\_tid\_DatasmithStaticMeshImportData\_\_

• **\_\_tid\_DatasmithStaticMeshImportData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:30022](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30022)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[__tid_Object__](ue_ue.DatasmithAssetImportData.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[CreateDefaultSubobject](ue_ue.DatasmithAssetImportData.md#createdefaultsubobject)

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

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[ExecuteUbergraph](ue_ue.DatasmithAssetImportData.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[GetClass](ue_ue.DatasmithAssetImportData.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[GetName](ue_ue.DatasmithAssetImportData.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[GetOuter](ue_ue.DatasmithAssetImportData.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[GetWorld](ue_ue.DatasmithAssetImportData.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### K2\_ExtractFilenames

▸ **K2_ExtractFilenames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[K2_ExtractFilenames](ue_ue.DatasmithAssetImportData.md#k2_extractfilenames)

#### Defined in

[ue/ue.d.ts:39](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39)

___

### K2\_GetFirstFilename

▸ **K2_GetFirstFilename**(): `string`

#### Returns

`string`

#### Inherited from

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[K2_GetFirstFilename](ue_ue.DatasmithAssetImportData.md#k2_getfirstfilename)

#### Defined in

[ue/ue.d.ts:40](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L40)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DatasmithStaticMeshImportData`](ue_ue.DatasmithStaticMeshImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DatasmithStaticMeshImportData`](ue_ue.DatasmithStaticMeshImportData.md)

#### Overrides

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[Find](ue_ue.DatasmithAssetImportData.md#find)

#### Defined in

[ue/ue.d.ts:30019](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30019)

___

### Load

▸ `Static` **Load**(`InName`): [`DatasmithStaticMeshImportData`](ue_ue.DatasmithStaticMeshImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DatasmithStaticMeshImportData`](ue_ue.DatasmithStaticMeshImportData.md)

#### Overrides

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[Load](ue_ue.DatasmithAssetImportData.md#load)

#### Defined in

[ue/ue.d.ts:30020](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30020)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DatasmithAssetImportData](ue_ue.DatasmithAssetImportData.md).[StaticClass](ue_ue.DatasmithAssetImportData.md#staticclass)

#### Defined in

[ue/ue.d.ts:30018](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30018)