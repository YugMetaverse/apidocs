[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SpeedTreeImportData

# Class: SpeedTreeImportData

[ue/ue](../modules/ue_ue.md).SpeedTreeImportData

## Hierarchy

- [`AssetImportData`](ue_ue.AssetImportData.md)

  ↳ **`SpeedTreeImportData`**

## Table of contents

### Constructors

- [constructor](ue_ue.SpeedTreeImportData.md#constructor)

### Properties

- [ImportGeometryType](ue_ue.SpeedTreeImportData.md#importgeometrytype)
- [IncludeBranchSeamSmoothing](ue_ue.SpeedTreeImportData.md#includebranchseamsmoothing)
- [IncludeCollision](ue_ue.SpeedTreeImportData.md#includecollision)
- [IncludeColorAdjustment](ue_ue.SpeedTreeImportData.md#includecoloradjustment)
- [IncludeDetailMapCheck](ue_ue.SpeedTreeImportData.md#includedetailmapcheck)
- [IncludeNormalMapCheck](ue_ue.SpeedTreeImportData.md#includenormalmapcheck)
- [IncludeSmoothLODCheck](ue_ue.SpeedTreeImportData.md#includesmoothlodcheck)
- [IncludeSpecularMapCheck](ue_ue.SpeedTreeImportData.md#includespecularmapcheck)
- [IncludeSpeedTreeAO](ue_ue.SpeedTreeImportData.md#includespeedtreeao)
- [IncludeSubsurface](ue_ue.SpeedTreeImportData.md#includesubsurface)
- [IncludeVertexProcessingCheck](ue_ue.SpeedTreeImportData.md#includevertexprocessingcheck)
- [IncludeWindCheck](ue_ue.SpeedTreeImportData.md#includewindcheck)
- [LODType](ue_ue.SpeedTreeImportData.md#lodtype)
- [MakeMaterialsCheck](ue_ue.SpeedTreeImportData.md#makematerialscheck)
- [SourceData](ue_ue.SpeedTreeImportData.md#sourcedata)
- [SourceFilePath](ue_ue.SpeedTreeImportData.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.SpeedTreeImportData.md#sourcefiletimestamp)
- [TreeScale](ue_ue.SpeedTreeImportData.md#treescale)
- [\_\_tid\_AssetImportData\_\_](ue_ue.SpeedTreeImportData.md#__tid_assetimportdata__)
- [\_\_tid\_Object\_\_](ue_ue.SpeedTreeImportData.md#__tid_object__)
- [\_\_tid\_SpeedTreeImportData\_\_](ue_ue.SpeedTreeImportData.md#__tid_speedtreeimportdata__)

### Methods

- [CreateDefaultSubobject](ue_ue.SpeedTreeImportData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SpeedTreeImportData.md#executeubergraph)
- [GetClass](ue_ue.SpeedTreeImportData.md#getclass)
- [GetName](ue_ue.SpeedTreeImportData.md#getname)
- [GetOuter](ue_ue.SpeedTreeImportData.md#getouter)
- [GetWorld](ue_ue.SpeedTreeImportData.md#getworld)
- [K2\_ExtractFilenames](ue_ue.SpeedTreeImportData.md#k2_extractfilenames)
- [K2\_GetFirstFilename](ue_ue.SpeedTreeImportData.md#k2_getfirstfilename)
- [Find](ue_ue.SpeedTreeImportData.md#find)
- [Load](ue_ue.SpeedTreeImportData.md#load)
- [StaticClass](ue_ue.SpeedTreeImportData.md#staticclass)

## Constructors

### constructor

• **new SpeedTreeImportData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[constructor](ue_ue.AssetImportData.md#constructor)

#### Defined in

[ue/ue.d.ts:61851](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61851)

## Properties

### ImportGeometryType

• **ImportGeometryType**: [`EImportGeometryType`](../enums/ue_ue.EImportGeometryType.md)

#### Defined in

[ue/ue.d.ts:61853](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61853)

___

### IncludeBranchSeamSmoothing

• **IncludeBranchSeamSmoothing**: `boolean`

#### Defined in

[ue/ue.d.ts:61860](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61860)

___

### IncludeCollision

• **IncludeCollision**: `boolean`

#### Defined in

[ue/ue.d.ts:61855](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61855)

___

### IncludeColorAdjustment

• **IncludeColorAdjustment**: `boolean`

#### Defined in

[ue/ue.d.ts:61862](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61862)

___

### IncludeDetailMapCheck

• **IncludeDetailMapCheck**: `boolean`

#### Defined in

[ue/ue.d.ts:61858](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61858)

___

### IncludeNormalMapCheck

• **IncludeNormalMapCheck**: `boolean`

#### Defined in

[ue/ue.d.ts:61857](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61857)

___

### IncludeSmoothLODCheck

• **IncludeSmoothLODCheck**: `boolean`

#### Defined in

[ue/ue.d.ts:61866](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61866)

___

### IncludeSpecularMapCheck

• **IncludeSpecularMapCheck**: `boolean`

#### Defined in

[ue/ue.d.ts:61859](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61859)

___

### IncludeSpeedTreeAO

• **IncludeSpeedTreeAO**: `boolean`

#### Defined in

[ue/ue.d.ts:61861](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61861)

___

### IncludeSubsurface

• **IncludeSubsurface**: `boolean`

#### Defined in

[ue/ue.d.ts:61863](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61863)

___

### IncludeVertexProcessingCheck

• **IncludeVertexProcessingCheck**: `boolean`

#### Defined in

[ue/ue.d.ts:61864](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61864)

___

### IncludeWindCheck

• **IncludeWindCheck**: `boolean`

#### Defined in

[ue/ue.d.ts:61865](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61865)

___

### LODType

• **LODType**: [`EImportLODType`](../enums/ue_ue.EImportLODType.md)

#### Defined in

[ue/ue.d.ts:61854](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61854)

___

### MakeMaterialsCheck

• **MakeMaterialsCheck**: `boolean`

#### Defined in

[ue/ue.d.ts:61856](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61856)

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

### TreeScale

• **TreeScale**: `number`

#### Defined in

[ue/ue.d.ts:61852](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61852)

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

___

### \_\_tid\_SpeedTreeImportData\_\_

• **\_\_tid\_SpeedTreeImportData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:61871](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61871)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SpeedTreeImportData`](ue_ue.SpeedTreeImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SpeedTreeImportData`](ue_ue.SpeedTreeImportData.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[Find](ue_ue.AssetImportData.md#find)

#### Defined in

[ue/ue.d.ts:61868](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61868)

___

### Load

▸ `Static` **Load**(`InName`): [`SpeedTreeImportData`](ue_ue.SpeedTreeImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SpeedTreeImportData`](ue_ue.SpeedTreeImportData.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[Load](ue_ue.AssetImportData.md#load)

#### Defined in

[ue/ue.d.ts:61869](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61869)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AssetImportData](ue_ue.AssetImportData.md).[StaticClass](ue_ue.AssetImportData.md#staticclass)

#### Defined in

[ue/ue.d.ts:61867](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61867)
