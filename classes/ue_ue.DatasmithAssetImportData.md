[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DatasmithAssetImportData

# Class: DatasmithAssetImportData

[ue/ue](../modules/ue_ue.md).DatasmithAssetImportData

## Hierarchy

- [`AssetImportData`](ue_ue.AssetImportData.md)

  ↳ **`DatasmithAssetImportData`**

  ↳↳ [`DatasmithDeltaGenAssetImportData`](ue_ue.DatasmithDeltaGenAssetImportData.md)

  ↳↳ [`DatasmithStaticMeshImportData`](ue_ue.DatasmithStaticMeshImportData.md)

  ↳↳ [`DatasmithVREDAssetImportData`](ue_ue.DatasmithVREDAssetImportData.md)

## Table of contents

### Constructors

- [constructor](ue_ue.DatasmithAssetImportData.md#constructor)

### Properties

- [AdditionalData](ue_ue.DatasmithAssetImportData.md#additionaldata)
- [AssetImportOptions](ue_ue.DatasmithAssetImportData.md#assetimportoptions)
- [SourceData](ue_ue.DatasmithAssetImportData.md#sourcedata)
- [SourceFilePath](ue_ue.DatasmithAssetImportData.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.DatasmithAssetImportData.md#sourcefiletimestamp)
- [\_\_tid\_AssetImportData\_\_](ue_ue.DatasmithAssetImportData.md#__tid_assetimportdata__)
- [\_\_tid\_DatasmithAssetImportData\_\_](ue_ue.DatasmithAssetImportData.md#__tid_datasmithassetimportdata__)
- [\_\_tid\_Object\_\_](ue_ue.DatasmithAssetImportData.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.DatasmithAssetImportData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DatasmithAssetImportData.md#executeubergraph)
- [GetClass](ue_ue.DatasmithAssetImportData.md#getclass)
- [GetName](ue_ue.DatasmithAssetImportData.md#getname)
- [GetOuter](ue_ue.DatasmithAssetImportData.md#getouter)
- [GetWorld](ue_ue.DatasmithAssetImportData.md#getworld)
- [K2\_ExtractFilenames](ue_ue.DatasmithAssetImportData.md#k2_extractfilenames)
- [K2\_GetFirstFilename](ue_ue.DatasmithAssetImportData.md#k2_getfirstfilename)
- [Find](ue_ue.DatasmithAssetImportData.md#find)
- [Load](ue_ue.DatasmithAssetImportData.md#load)
- [StaticClass](ue_ue.DatasmithAssetImportData.md#staticclass)

## Constructors

### constructor

• **new DatasmithAssetImportData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[constructor](ue_ue.AssetImportData.md#constructor)

## Properties

### AdditionalData

• **AdditionalData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DatasmithAdditionalData`](ue_ue.DatasmithAdditionalData.md)\>

___

### AssetImportOptions

• **AssetImportOptions**: [`DatasmithAssetImportOptions`](ue_ue.DatasmithAssetImportOptions.md)

___

### SourceData

• **SourceData**: [`AssetImportInfo`](ue_ue.AssetImportInfo.md)

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[SourceData](ue_ue.AssetImportData.md#sourcedata)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[SourceFilePath](ue_ue.AssetImportData.md#sourcefilepath)

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[SourceFileTimestamp](ue_ue.AssetImportData.md#sourcefiletimestamp)

___

### \_\_tid\_AssetImportData\_\_

• **\_\_tid\_AssetImportData\_\_**: `boolean`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[__tid_AssetImportData__](ue_ue.AssetImportData.md#__tid_assetimportdata__)

___

### \_\_tid\_DatasmithAssetImportData\_\_

• **\_\_tid\_DatasmithAssetImportData\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[__tid_Object__](ue_ue.AssetImportData.md#__tid_object__)

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

[AssetImportData](ue_ue.AssetImportData.md).[CreateDefaultSubobject](ue_ue.AssetImportData.md#createdefaultsubobject)

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

[AssetImportData](ue_ue.AssetImportData.md).[ExecuteUbergraph](ue_ue.AssetImportData.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[GetClass](ue_ue.AssetImportData.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[GetName](ue_ue.AssetImportData.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[GetOuter](ue_ue.AssetImportData.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[GetWorld](ue_ue.AssetImportData.md#getworld)

___

### K2\_ExtractFilenames

▸ **K2_ExtractFilenames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[K2_ExtractFilenames](ue_ue.AssetImportData.md#k2_extractfilenames)

___

### K2\_GetFirstFilename

▸ **K2_GetFirstFilename**(): `string`

#### Returns

`string`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[K2_GetFirstFilename](ue_ue.AssetImportData.md#k2_getfirstfilename)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DatasmithAssetImportData`](ue_ue.DatasmithAssetImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DatasmithAssetImportData`](ue_ue.DatasmithAssetImportData.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[Find](ue_ue.AssetImportData.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DatasmithAssetImportData`](ue_ue.DatasmithAssetImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DatasmithAssetImportData`](ue_ue.DatasmithAssetImportData.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[Load](ue_ue.AssetImportData.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[StaticClass](ue_ue.AssetImportData.md#staticclass)
