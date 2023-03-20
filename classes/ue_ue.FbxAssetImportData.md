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

#### Defined in

[ue/ue.d.ts:35121](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35121)

## Properties

### FbxSceneImportDataReference

• **FbxSceneImportDataReference**: [`FbxSceneImportData`](ue_ue.FbxSceneImportData.md)

#### Defined in

[ue/ue.d.ts:35129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35129)

___

### ImportRotation

• **ImportRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:35123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35123)

___

### ImportTranslation

• **ImportTranslation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:35122](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35122)

___

### ImportUniformScale

• **ImportUniformScale**: `number`

#### Defined in

[ue/ue.d.ts:35124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35124)

___

### SourceData

• **SourceData**: [`AssetImportInfo`](ue_ue.AssetImportInfo.md)

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[SourceData](ue_ue.AssetImportData.md#sourcedata)

#### Defined in

[ue/ue.d.ts:38](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[SourceFilePath](ue_ue.AssetImportData.md#sourcefilepath)

#### Defined in

[ue/ue.d.ts:36](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36)

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[SourceFileTimestamp](ue_ue.AssetImportData.md#sourcefiletimestamp)

#### Defined in

[ue/ue.d.ts:37](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37)

___

### \_\_tid\_AssetImportData\_\_

• **\_\_tid\_AssetImportData\_\_**: `boolean`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[__tid_AssetImportData__](ue_ue.AssetImportData.md#__tid_assetimportdata__)

#### Defined in

[ue/ue.d.ts:45](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45)

___

### \_\_tid\_FbxAssetImportData\_\_

• **\_\_tid\_FbxAssetImportData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:35134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35134)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[__tid_Object__](ue_ue.AssetImportData.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bConvertScene

• **bConvertScene**: `boolean`

#### Defined in

[ue/ue.d.ts:35125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35125)

___

### bConvertSceneUnit

• **bConvertSceneUnit**: `boolean`

#### Defined in

[ue/ue.d.ts:35127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35127)

___

### bForceFrontXAxis

• **bForceFrontXAxis**: `boolean`

#### Defined in

[ue/ue.d.ts:35126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35126)

___

### bImportAsScene

• **bImportAsScene**: `boolean`

#### Defined in

[ue/ue.d.ts:35128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35128)

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

[AssetImportData](ue_ue.AssetImportData.md).[ExecuteUbergraph](ue_ue.AssetImportData.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[GetClass](ue_ue.AssetImportData.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[GetName](ue_ue.AssetImportData.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[GetOuter](ue_ue.AssetImportData.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[GetWorld](ue_ue.AssetImportData.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### K2\_ExtractFilenames

▸ **K2_ExtractFilenames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[K2_ExtractFilenames](ue_ue.AssetImportData.md#k2_extractfilenames)

#### Defined in

[ue/ue.d.ts:39](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39)

___

### K2\_GetFirstFilename

▸ **K2_GetFirstFilename**(): `string`

#### Returns

`string`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[K2_GetFirstFilename](ue_ue.AssetImportData.md#k2_getfirstfilename)

#### Defined in

[ue/ue.d.ts:40](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40)

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

#### Defined in

[ue/ue.d.ts:35131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35131)

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

#### Defined in

[ue/ue.d.ts:35132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35132)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[StaticClass](ue_ue.AssetImportData.md#staticclass)

#### Defined in

[ue/ue.d.ts:35130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35130)
