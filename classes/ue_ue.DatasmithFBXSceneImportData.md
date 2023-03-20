[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DatasmithFBXSceneImportData

# Class: DatasmithFBXSceneImportData

[ue/ue](../modules/ue_ue.md).DatasmithFBXSceneImportData

## Hierarchy

- [`DatasmithSceneImportData`](ue_ue.DatasmithSceneImportData.md)

  ↳ **`DatasmithFBXSceneImportData`**

  ↳↳ [`DatasmithDeltaGenSceneImportData`](ue_ue.DatasmithDeltaGenSceneImportData.md)

  ↳↳ [`DatasmithVREDSceneImportData`](ue_ue.DatasmithVREDSceneImportData.md)

## Table of contents

### Constructors

- [constructor](ue_ue.DatasmithFBXSceneImportData.md#constructor)

### Properties

- [BaseOptions](ue_ue.DatasmithFBXSceneImportData.md#baseoptions)
- [IntermediateSerialization](ue_ue.DatasmithFBXSceneImportData.md#intermediateserialization)
- [SourceData](ue_ue.DatasmithFBXSceneImportData.md#sourcedata)
- [SourceFilePath](ue_ue.DatasmithFBXSceneImportData.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.DatasmithFBXSceneImportData.md#sourcefiletimestamp)
- [TexturesDir](ue_ue.DatasmithFBXSceneImportData.md#texturesdir)
- [\_\_tid\_AssetImportData\_\_](ue_ue.DatasmithFBXSceneImportData.md#__tid_assetimportdata__)
- [\_\_tid\_DatasmithFBXSceneImportData\_\_](ue_ue.DatasmithFBXSceneImportData.md#__tid_datasmithfbxsceneimportdata__)
- [\_\_tid\_DatasmithSceneImportData\_\_](ue_ue.DatasmithFBXSceneImportData.md#__tid_datasmithsceneimportdata__)
- [\_\_tid\_Object\_\_](ue_ue.DatasmithFBXSceneImportData.md#__tid_object__)
- [bColorizeMaterials](ue_ue.DatasmithFBXSceneImportData.md#bcolorizematerials)
- [bGenerateLightmapUVs](ue_ue.DatasmithFBXSceneImportData.md#bgeneratelightmapuvs)

### Methods

- [CreateDefaultSubobject](ue_ue.DatasmithFBXSceneImportData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DatasmithFBXSceneImportData.md#executeubergraph)
- [GetClass](ue_ue.DatasmithFBXSceneImportData.md#getclass)
- [GetName](ue_ue.DatasmithFBXSceneImportData.md#getname)
- [GetOuter](ue_ue.DatasmithFBXSceneImportData.md#getouter)
- [GetWorld](ue_ue.DatasmithFBXSceneImportData.md#getworld)
- [K2\_ExtractFilenames](ue_ue.DatasmithFBXSceneImportData.md#k2_extractfilenames)
- [K2\_GetFirstFilename](ue_ue.DatasmithFBXSceneImportData.md#k2_getfirstfilename)
- [Find](ue_ue.DatasmithFBXSceneImportData.md#find)
- [Load](ue_ue.DatasmithFBXSceneImportData.md#load)
- [StaticClass](ue_ue.DatasmithFBXSceneImportData.md#staticclass)

## Constructors

### constructor

• **new DatasmithFBXSceneImportData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[constructor](ue_ue.DatasmithSceneImportData.md#constructor)

#### Defined in

[ue/ue.d.ts:29647](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29647)

## Properties

### BaseOptions

• **BaseOptions**: [`DatasmithImportBaseOptions`](ue_ue.DatasmithImportBaseOptions.md)

#### Inherited from

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[BaseOptions](ue_ue.DatasmithSceneImportData.md#baseoptions)

#### Defined in

[ue/ue.d.ts:29466](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29466)

___

### IntermediateSerialization

• **IntermediateSerialization**: `number`

#### Defined in

[ue/ue.d.ts:29650](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29650)

___

### SourceData

• **SourceData**: [`AssetImportInfo`](ue_ue.AssetImportInfo.md)

#### Inherited from

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[SourceData](ue_ue.DatasmithSceneImportData.md#sourcedata)

#### Defined in

[ue/ue.d.ts:38](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[SourceFilePath](ue_ue.DatasmithSceneImportData.md#sourcefilepath)

#### Defined in

[ue/ue.d.ts:36](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36)

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

#### Inherited from

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[SourceFileTimestamp](ue_ue.DatasmithSceneImportData.md#sourcefiletimestamp)

#### Defined in

[ue/ue.d.ts:37](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37)

___

### TexturesDir

• **TexturesDir**: `string`

#### Defined in

[ue/ue.d.ts:29649](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29649)

___

### \_\_tid\_AssetImportData\_\_

• **\_\_tid\_AssetImportData\_\_**: `boolean`

#### Inherited from

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[__tid_AssetImportData__](ue_ue.DatasmithSceneImportData.md#__tid_assetimportdata__)

#### Defined in

[ue/ue.d.ts:45](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45)

___

### \_\_tid\_DatasmithFBXSceneImportData\_\_

• **\_\_tid\_DatasmithFBXSceneImportData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:29656](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29656)

___

### \_\_tid\_DatasmithSceneImportData\_\_

• **\_\_tid\_DatasmithSceneImportData\_\_**: `boolean`

#### Inherited from

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[__tid_DatasmithSceneImportData__](ue_ue.DatasmithSceneImportData.md#__tid_datasmithsceneimportdata__)

#### Defined in

[ue/ue.d.ts:29471](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29471)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[__tid_Object__](ue_ue.DatasmithSceneImportData.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bColorizeMaterials

• **bColorizeMaterials**: `boolean`

#### Defined in

[ue/ue.d.ts:29651](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29651)

___

### bGenerateLightmapUVs

• **bGenerateLightmapUVs**: `boolean`

#### Defined in

[ue/ue.d.ts:29648](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29648)

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

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[CreateDefaultSubobject](ue_ue.DatasmithSceneImportData.md#createdefaultsubobject)

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

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[ExecuteUbergraph](ue_ue.DatasmithSceneImportData.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[GetClass](ue_ue.DatasmithSceneImportData.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[GetName](ue_ue.DatasmithSceneImportData.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[GetOuter](ue_ue.DatasmithSceneImportData.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[GetWorld](ue_ue.DatasmithSceneImportData.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### K2\_ExtractFilenames

▸ **K2_ExtractFilenames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[K2_ExtractFilenames](ue_ue.DatasmithSceneImportData.md#k2_extractfilenames)

#### Defined in

[ue/ue.d.ts:39](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39)

___

### K2\_GetFirstFilename

▸ **K2_GetFirstFilename**(): `string`

#### Returns

`string`

#### Inherited from

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[K2_GetFirstFilename](ue_ue.DatasmithSceneImportData.md#k2_getfirstfilename)

#### Defined in

[ue/ue.d.ts:40](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L40)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DatasmithFBXSceneImportData`](ue_ue.DatasmithFBXSceneImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DatasmithFBXSceneImportData`](ue_ue.DatasmithFBXSceneImportData.md)

#### Overrides

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[Find](ue_ue.DatasmithSceneImportData.md#find)

#### Defined in

[ue/ue.d.ts:29653](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29653)

___

### Load

▸ `Static` **Load**(`InName`): [`DatasmithFBXSceneImportData`](ue_ue.DatasmithFBXSceneImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DatasmithFBXSceneImportData`](ue_ue.DatasmithFBXSceneImportData.md)

#### Overrides

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[Load](ue_ue.DatasmithSceneImportData.md#load)

#### Defined in

[ue/ue.d.ts:29654](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29654)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DatasmithSceneImportData](ue_ue.DatasmithSceneImportData.md).[StaticClass](ue_ue.DatasmithSceneImportData.md#staticclass)

#### Defined in

[ue/ue.d.ts:29652](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29652)