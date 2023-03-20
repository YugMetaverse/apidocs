[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DatasmithSceneImportData

# Class: DatasmithSceneImportData

[ue/ue](../modules/ue_ue.md).DatasmithSceneImportData

## Hierarchy

- [`AssetImportData`](ue_ue.AssetImportData.md)

  ↳ **`DatasmithSceneImportData`**

  ↳↳ [`DatasmithCADImportSceneData`](ue_ue.DatasmithCADImportSceneData.md)

  ↳↳ [`DatasmithFBXSceneImportData`](ue_ue.DatasmithFBXSceneImportData.md)

  ↳↳ [`DatasmithGLTFSceneImportData`](ue_ue.DatasmithGLTFSceneImportData.md)

  ↳↳ [`DatasmithIFCSceneImportData`](ue_ue.DatasmithIFCSceneImportData.md)

  ↳↳ [`DatasmithMDLSceneImportData`](ue_ue.DatasmithMDLSceneImportData.md)

  ↳↳ [`DatasmithTranslatedSceneImportData`](ue_ue.DatasmithTranslatedSceneImportData.md)

## Table of contents

### Constructors

- [constructor](ue_ue.DatasmithSceneImportData.md#constructor)

### Properties

- [BaseOptions](ue_ue.DatasmithSceneImportData.md#baseoptions)
- [SourceData](ue_ue.DatasmithSceneImportData.md#sourcedata)
- [SourceFilePath](ue_ue.DatasmithSceneImportData.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.DatasmithSceneImportData.md#sourcefiletimestamp)
- [\_\_tid\_AssetImportData\_\_](ue_ue.DatasmithSceneImportData.md#__tid_assetimportdata__)
- [\_\_tid\_DatasmithSceneImportData\_\_](ue_ue.DatasmithSceneImportData.md#__tid_datasmithsceneimportdata__)
- [\_\_tid\_Object\_\_](ue_ue.DatasmithSceneImportData.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.DatasmithSceneImportData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DatasmithSceneImportData.md#executeubergraph)
- [GetClass](ue_ue.DatasmithSceneImportData.md#getclass)
- [GetName](ue_ue.DatasmithSceneImportData.md#getname)
- [GetOuter](ue_ue.DatasmithSceneImportData.md#getouter)
- [GetWorld](ue_ue.DatasmithSceneImportData.md#getworld)
- [K2\_ExtractFilenames](ue_ue.DatasmithSceneImportData.md#k2_extractfilenames)
- [K2\_GetFirstFilename](ue_ue.DatasmithSceneImportData.md#k2_getfirstfilename)
- [Find](ue_ue.DatasmithSceneImportData.md#find)
- [Load](ue_ue.DatasmithSceneImportData.md#load)
- [StaticClass](ue_ue.DatasmithSceneImportData.md#staticclass)

## Constructors

### constructor

• **new DatasmithSceneImportData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[constructor](ue_ue.AssetImportData.md#constructor)

## Properties

### BaseOptions

• **BaseOptions**: [`DatasmithImportBaseOptions`](ue_ue.DatasmithImportBaseOptions.md)

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

### \_\_tid\_DatasmithSceneImportData\_\_

• **\_\_tid\_DatasmithSceneImportData\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DatasmithSceneImportData`](ue_ue.DatasmithSceneImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DatasmithSceneImportData`](ue_ue.DatasmithSceneImportData.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[Find](ue_ue.AssetImportData.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DatasmithSceneImportData`](ue_ue.DatasmithSceneImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DatasmithSceneImportData`](ue_ue.DatasmithSceneImportData.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[Load](ue_ue.AssetImportData.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[StaticClass](ue_ue.AssetImportData.md#staticclass)
