[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TileMapAssetImportData

# Class: TileMapAssetImportData

[ue/ue](../modules/ue_ue.md).TileMapAssetImportData

## Hierarchy

- [`AssetImportData`](ue_ue.AssetImportData.md)

  ↳ **`TileMapAssetImportData`**

## Table of contents

### Constructors

- [constructor](ue_ue.TileMapAssetImportData.md#constructor)

### Properties

- [SourceData](ue_ue.TileMapAssetImportData.md#sourcedata)
- [SourceFilePath](ue_ue.TileMapAssetImportData.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.TileMapAssetImportData.md#sourcefiletimestamp)
- [TileSetMap](ue_ue.TileMapAssetImportData.md#tilesetmap)
- [\_\_tid\_AssetImportData\_\_](ue_ue.TileMapAssetImportData.md#__tid_assetimportdata__)
- [\_\_tid\_Object\_\_](ue_ue.TileMapAssetImportData.md#__tid_object__)
- [\_\_tid\_TileMapAssetImportData\_\_](ue_ue.TileMapAssetImportData.md#__tid_tilemapassetimportdata__)

### Methods

- [CreateDefaultSubobject](ue_ue.TileMapAssetImportData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TileMapAssetImportData.md#executeubergraph)
- [GetClass](ue_ue.TileMapAssetImportData.md#getclass)
- [GetName](ue_ue.TileMapAssetImportData.md#getname)
- [GetOuter](ue_ue.TileMapAssetImportData.md#getouter)
- [GetWorld](ue_ue.TileMapAssetImportData.md#getworld)
- [K2\_ExtractFilenames](ue_ue.TileMapAssetImportData.md#k2_extractfilenames)
- [K2\_GetFirstFilename](ue_ue.TileMapAssetImportData.md#k2_getfirstfilename)
- [Find](ue_ue.TileMapAssetImportData.md#find)
- [Load](ue_ue.TileMapAssetImportData.md#load)
- [StaticClass](ue_ue.TileMapAssetImportData.md#staticclass)

## Constructors

### constructor

• **new TileMapAssetImportData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[constructor](ue_ue.AssetImportData.md#constructor)

#### Defined in

[ue/ue.d.ts:63457](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63457)

## Properties

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

### TileSetMap

• **TileSetMap**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TileSetImportMapping`](ue_ue.TileSetImportMapping.md)\>

#### Defined in

[ue/ue.d.ts:63458](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63458)

___

### \_\_tid\_AssetImportData\_\_

• **\_\_tid\_AssetImportData\_\_**: `boolean`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[__tid_AssetImportData__](ue_ue.AssetImportData.md#__tid_assetimportdata__)

#### Defined in

[ue/ue.d.ts:45](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[__tid_Object__](ue_ue.AssetImportData.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_TileMapAssetImportData\_\_

• **\_\_tid\_TileMapAssetImportData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:63463](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63463)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TileMapAssetImportData`](ue_ue.TileMapAssetImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TileMapAssetImportData`](ue_ue.TileMapAssetImportData.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[Find](ue_ue.AssetImportData.md#find)

#### Defined in

[ue/ue.d.ts:63460](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63460)

___

### Load

▸ `Static` **Load**(`InName`): [`TileMapAssetImportData`](ue_ue.TileMapAssetImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TileMapAssetImportData`](ue_ue.TileMapAssetImportData.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[Load](ue_ue.AssetImportData.md#load)

#### Defined in

[ue/ue.d.ts:63461](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63461)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[StaticClass](ue_ue.AssetImportData.md#staticclass)

#### Defined in

[ue/ue.d.ts:63459](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63459)
