[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AbcAssetImportData

# Class: AbcAssetImportData

[ue/ue](../modules/ue_ue.md).AbcAssetImportData

## Hierarchy

- [`AssetImportData`](ue_ue.AssetImportData.md)

  ↳ **`AbcAssetImportData`**

## Table of contents

### Constructors

- [constructor](ue_ue.AbcAssetImportData.md#constructor)

### Properties

- [SamplingSettings](ue_ue.AbcAssetImportData.md#samplingsettings)
- [SourceData](ue_ue.AbcAssetImportData.md#sourcedata)
- [SourceFilePath](ue_ue.AbcAssetImportData.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.AbcAssetImportData.md#sourcefiletimestamp)
- [TrackNames](ue_ue.AbcAssetImportData.md#tracknames)
- [\_\_tid\_AbcAssetImportData\_\_](ue_ue.AbcAssetImportData.md#__tid_abcassetimportdata__)
- [\_\_tid\_AssetImportData\_\_](ue_ue.AbcAssetImportData.md#__tid_assetimportdata__)
- [\_\_tid\_Object\_\_](ue_ue.AbcAssetImportData.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AbcAssetImportData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AbcAssetImportData.md#executeubergraph)
- [GetClass](ue_ue.AbcAssetImportData.md#getclass)
- [GetName](ue_ue.AbcAssetImportData.md#getname)
- [GetOuter](ue_ue.AbcAssetImportData.md#getouter)
- [GetWorld](ue_ue.AbcAssetImportData.md#getworld)
- [K2\_ExtractFilenames](ue_ue.AbcAssetImportData.md#k2_extractfilenames)
- [K2\_GetFirstFilename](ue_ue.AbcAssetImportData.md#k2_getfirstfilename)
- [Find](ue_ue.AbcAssetImportData.md#find)
- [Load](ue_ue.AbcAssetImportData.md#load)
- [StaticClass](ue_ue.AbcAssetImportData.md#staticclass)

## Constructors

### constructor

• **new AbcAssetImportData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[constructor](ue_ue.AssetImportData.md#constructor)

#### Defined in

[ue/ue.d.ts:67](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L67)

## Properties

### SamplingSettings

• **SamplingSettings**: [`AbcSamplingSettings`](ue_ue.AbcSamplingSettings.md)

#### Defined in

[ue/ue.d.ts:69](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L69)

___

### SourceData

• **SourceData**: [`AssetImportInfo`](ue_ue.AssetImportInfo.md)

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[SourceData](ue_ue.AssetImportData.md#sourcedata)

#### Defined in

[ue/ue.d.ts:38](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[SourceFilePath](ue_ue.AssetImportData.md#sourcefilepath)

#### Defined in

[ue/ue.d.ts:36](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36)

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[SourceFileTimestamp](ue_ue.AssetImportData.md#sourcefiletimestamp)

#### Defined in

[ue/ue.d.ts:37](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37)

___

### TrackNames

• **TrackNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:68](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L68)

___

### \_\_tid\_AbcAssetImportData\_\_

• **\_\_tid\_AbcAssetImportData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:74](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L74)

___

### \_\_tid\_AssetImportData\_\_

• **\_\_tid\_AssetImportData\_\_**: `boolean`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[__tid_AssetImportData__](ue_ue.AssetImportData.md#__tid_assetimportdata__)

#### Defined in

[ue/ue.d.ts:45](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[__tid_Object__](ue_ue.AssetImportData.md#__tid_object__)

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

[AssetImportData](ue_ue.AssetImportData.md).[CreateDefaultSubobject](ue_ue.AssetImportData.md#createdefaultsubobject)

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

[AssetImportData](ue_ue.AssetImportData.md).[ExecuteUbergraph](ue_ue.AssetImportData.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[GetClass](ue_ue.AssetImportData.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[GetName](ue_ue.AssetImportData.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[GetOuter](ue_ue.AssetImportData.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[GetWorld](ue_ue.AssetImportData.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### K2\_ExtractFilenames

▸ **K2_ExtractFilenames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[K2_ExtractFilenames](ue_ue.AssetImportData.md#k2_extractfilenames)

#### Defined in

[ue/ue.d.ts:39](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39)

___

### K2\_GetFirstFilename

▸ **K2_GetFirstFilename**(): `string`

#### Returns

`string`

#### Inherited from

[AssetImportData](ue_ue.AssetImportData.md).[K2_GetFirstFilename](ue_ue.AssetImportData.md#k2_getfirstfilename)

#### Defined in

[ue/ue.d.ts:40](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L40)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AbcAssetImportData`](ue_ue.AbcAssetImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AbcAssetImportData`](ue_ue.AbcAssetImportData.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[Find](ue_ue.AssetImportData.md#find)

#### Defined in

[ue/ue.d.ts:71](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L71)

___

### Load

▸ `Static` **Load**(`InName`): [`AbcAssetImportData`](ue_ue.AbcAssetImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AbcAssetImportData`](ue_ue.AbcAssetImportData.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[Load](ue_ue.AssetImportData.md#load)

#### Defined in

[ue/ue.d.ts:72](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L72)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[StaticClass](ue_ue.AssetImportData.md#staticclass)

#### Defined in

[ue/ue.d.ts:70](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L70)
