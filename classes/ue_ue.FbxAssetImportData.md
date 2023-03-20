[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FbxAssetImportData

# Class: FbxAssetImportData

[ue/ue](../modules/ue_ue.md).FbxAssetImportData

## Hierarchy

- [`AssetImportData`](ue_ue.AssetImportData.md)

  ↳ **`FbxAssetImportData`**

  ↳↳ [`FbxAnimSequenceImportData`](ue_ue.FbxAnimSequenceImportData.md)

  ↳↳ [`FbxMeshImportData`](ue_ue.FbxMeshImportData.md)

  ↳↳ [`FbxTextureImportData`](ue_ue.FbxTextureImportData.md)

## Table of contents

### Constructors

- [constructor](ue_ue.FbxAssetImportData.md#constructor)

### Properties

- [FbxSceneImportDataReference](ue_ue.FbxAssetImportData.md#fbxsceneimportdatareference)
- [ImportRotation](ue_ue.FbxAssetImportData.md#importrotation)
- [ImportTranslation](ue_ue.FbxAssetImportData.md#importtranslation)
- [ImportUniformScale](ue_ue.FbxAssetImportData.md#importuniformscale)
- [SourceData](ue_ue.FbxAssetImportData.md#sourcedata)
- [SourceFilePath](ue_ue.FbxAssetImportData.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.FbxAssetImportData.md#sourcefiletimestamp)
- [\_\_tid\_AssetImportData\_\_](ue_ue.FbxAssetImportData.md#__tid_assetimportdata__)
- [\_\_tid\_FbxAssetImportData\_\_](ue_ue.FbxAssetImportData.md#__tid_fbxassetimportdata__)
- [\_\_tid\_Object\_\_](ue_ue.FbxAssetImportData.md#__tid_object__)
- [bConvertScene](ue_ue.FbxAssetImportData.md#bconvertscene)
- [bConvertSceneUnit](ue_ue.FbxAssetImportData.md#bconvertsceneunit)
- [bForceFrontXAxis](ue_ue.FbxAssetImportData.md#bforcefrontxaxis)
- [bImportAsScene](ue_ue.FbxAssetImportData.md#bimportasscene)

### Methods

- [CreateDefaultSubobject](ue_ue.FbxAssetImportData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FbxAssetImportData.md#executeubergraph)
- [GetClass](ue_ue.FbxAssetImportData.md#getclass)
- [GetName](ue_ue.FbxAssetImportData.md#getname)
- [GetOuter](ue_ue.FbxAssetImportData.md#getouter)
- [GetWorld](ue_ue.FbxAssetImportData.md#getworld)
- [K2\_ExtractFilenames](ue_ue.FbxAssetImportData.md#k2_extractfilenames)
- [K2\_GetFirstFilename](ue_ue.FbxAssetImportData.md#k2_getfirstfilename)
- [Find](ue_ue.FbxAssetImportData.md#find)
- [Load](ue_ue.FbxAssetImportData.md#load)
- [StaticClass](ue_ue.FbxAssetImportData.md#staticclass)

## Constructors

### constructor

• **new FbxAssetImportData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[constructor](ue_ue.AssetImportData.md#constructor)

## Properties

### FbxSceneImportDataReference

• **FbxSceneImportDataReference**: [`FbxSceneImportData`](ue_ue.FbxSceneImportData.md)

___

### ImportRotation

• **ImportRotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### ImportTranslation

• **ImportTranslation**: [`Vector`](ue_ue_s.Vector.md)

___

### ImportUniformScale

• **ImportUniformScale**: `number`

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

### \_\_tid\_FbxAssetImportData\_\_

• **\_\_tid\_FbxAssetImportData\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[__tid_Object__](ue_ue.AssetImportData.md#__tid_object__)

___

### bConvertScene

• **bConvertScene**: `boolean`

___

### bConvertSceneUnit

• **bConvertSceneUnit**: `boolean`

___

### bForceFrontXAxis

• **bForceFrontXAxis**: `boolean`

___

### bImportAsScene

• **bImportAsScene**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FbxAssetImportData`](ue_ue.FbxAssetImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FbxAssetImportData`](ue_ue.FbxAssetImportData.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[Find](ue_ue.AssetImportData.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`FbxAssetImportData`](ue_ue.FbxAssetImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FbxAssetImportData`](ue_ue.FbxAssetImportData.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[Load](ue_ue.AssetImportData.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[StaticClass](ue_ue.AssetImportData.md#staticclass)
