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

#### Defined in

[ue/ue.d.ts:29406](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29406)

## Properties

### AdditionalData

• **AdditionalData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DatasmithAdditionalData`](ue_ue.DatasmithAdditionalData.md)\>

#### Defined in

[ue/ue.d.ts:29408](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29408)

___

### AssetImportOptions

• **AssetImportOptions**: [`DatasmithAssetImportOptions`](ue_ue.DatasmithAssetImportOptions.md)

#### Defined in

[ue/ue.d.ts:29407](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29407)

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

### \_\_tid\_DatasmithAssetImportData\_\_

• **\_\_tid\_DatasmithAssetImportData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:29413](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29413)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[__tid_Object__](ue_ue.AssetImportData.md#__tid_object__)

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

#### Defined in

[ue/ue.d.ts:29410](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29410)

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

#### Defined in

[ue/ue.d.ts:29411](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29411)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[StaticClass](ue_ue.AssetImportData.md#staticclass)

#### Defined in

[ue/ue.d.ts:29409](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29409)
