[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AssetImportData

# Class: AssetImportData

[ue/ue](../modules/ue_ue.md).AssetImportData

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AssetImportData`**

  ↳↳ [`AbcAssetImportData`](ue_ue.AbcAssetImportData.md)

  ↳↳ [`DatasmithAssetImportData`](ue_ue.DatasmithAssetImportData.md)

  ↳↳ [`DatasmithSceneImportData`](ue_ue.DatasmithSceneImportData.md)

  ↳↳ [`FbxAssetImportData`](ue_ue.FbxAssetImportData.md)

  ↳↳ [`SpeedTreeImportData`](ue_ue.SpeedTreeImportData.md)

  ↳↳ [`TileMapAssetImportData`](ue_ue.TileMapAssetImportData.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AssetImportData.md#constructor)

### Properties

- [SourceData](ue_ue.AssetImportData.md#sourcedata)
- [SourceFilePath](ue_ue.AssetImportData.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.AssetImportData.md#sourcefiletimestamp)
- [\_\_tid\_AssetImportData\_\_](ue_ue.AssetImportData.md#__tid_assetimportdata__)
- [\_\_tid\_Object\_\_](ue_ue.AssetImportData.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AssetImportData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AssetImportData.md#executeubergraph)
- [GetClass](ue_ue.AssetImportData.md#getclass)
- [GetName](ue_ue.AssetImportData.md#getname)
- [GetOuter](ue_ue.AssetImportData.md#getouter)
- [GetWorld](ue_ue.AssetImportData.md#getworld)
- [K2\_ExtractFilenames](ue_ue.AssetImportData.md#k2_extractfilenames)
- [K2\_GetFirstFilename](ue_ue.AssetImportData.md#k2_getfirstfilename)
- [Find](ue_ue.AssetImportData.md#find)
- [Load](ue_ue.AssetImportData.md#load)
- [StaticClass](ue_ue.AssetImportData.md#staticclass)

## Constructors

### constructor

• **new AssetImportData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### SourceData

• **SourceData**: [`AssetImportInfo`](ue_ue.AssetImportInfo.md)

___

### SourceFilePath

• **SourceFilePath**: `string`

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

___

### \_\_tid\_AssetImportData\_\_

• **\_\_tid\_AssetImportData\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### K2\_ExtractFilenames

▸ **K2_ExtractFilenames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### K2\_GetFirstFilename

▸ **K2_GetFirstFilename**(): `string`

#### Returns

`string`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AssetImportData`](ue_ue.AssetImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AssetImportData`](ue_ue.AssetImportData.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AssetImportData`](ue_ue.AssetImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AssetImportData`](ue_ue.AssetImportData.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
