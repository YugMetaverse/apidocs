[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FbxMeshImportData

# Class: FbxMeshImportData

[ue/ue](../modules/ue_ue.md).FbxMeshImportData

## Hierarchy

- [`FbxAssetImportData`](ue_ue.FbxAssetImportData.md)

  ↳ **`FbxMeshImportData`**

  ↳↳ [`FbxStaticMeshImportData`](ue_ue.FbxStaticMeshImportData.md)

  ↳↳ [`FbxSkeletalMeshImportData`](ue_ue.FbxSkeletalMeshImportData.md)

## Table of contents

### Constructors

- [constructor](ue_ue.FbxMeshImportData.md#constructor)

### Properties

- [FbxSceneImportDataReference](ue_ue.FbxMeshImportData.md#fbxsceneimportdatareference)
- [ImportMaterialOriginalNameData](ue_ue.FbxMeshImportData.md#importmaterialoriginalnamedata)
- [ImportMeshLodData](ue_ue.FbxMeshImportData.md#importmeshloddata)
- [ImportRotation](ue_ue.FbxMeshImportData.md#importrotation)
- [ImportTranslation](ue_ue.FbxMeshImportData.md#importtranslation)
- [ImportUniformScale](ue_ue.FbxMeshImportData.md#importuniformscale)
- [NormalGenerationMethod](ue_ue.FbxMeshImportData.md#normalgenerationmethod)
- [NormalImportMethod](ue_ue.FbxMeshImportData.md#normalimportmethod)
- [SourceData](ue_ue.FbxMeshImportData.md#sourcedata)
- [SourceFilePath](ue_ue.FbxMeshImportData.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.FbxMeshImportData.md#sourcefiletimestamp)
- [\_\_tid\_AssetImportData\_\_](ue_ue.FbxMeshImportData.md#__tid_assetimportdata__)
- [\_\_tid\_FbxAssetImportData\_\_](ue_ue.FbxMeshImportData.md#__tid_fbxassetimportdata__)
- [\_\_tid\_FbxMeshImportData\_\_](ue_ue.FbxMeshImportData.md#__tid_fbxmeshimportdata__)
- [\_\_tid\_Object\_\_](ue_ue.FbxMeshImportData.md#__tid_object__)
- [bBakePivotInVertex](ue_ue.FbxMeshImportData.md#bbakepivotinvertex)
- [bComputeWeightedNormals](ue_ue.FbxMeshImportData.md#bcomputeweightednormals)
- [bConvertScene](ue_ue.FbxMeshImportData.md#bconvertscene)
- [bConvertSceneUnit](ue_ue.FbxMeshImportData.md#bconvertsceneunit)
- [bForceFrontXAxis](ue_ue.FbxMeshImportData.md#bforcefrontxaxis)
- [bImportAsScene](ue_ue.FbxMeshImportData.md#bimportasscene)
- [bImportMeshLODs](ue_ue.FbxMeshImportData.md#bimportmeshlods)
- [bReorderMaterialToFbxOrder](ue_ue.FbxMeshImportData.md#breordermaterialtofbxorder)
- [bTransformVertexToAbsolute](ue_ue.FbxMeshImportData.md#btransformvertextoabsolute)

### Methods

- [CreateDefaultSubobject](ue_ue.FbxMeshImportData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FbxMeshImportData.md#executeubergraph)
- [GetClass](ue_ue.FbxMeshImportData.md#getclass)
- [GetName](ue_ue.FbxMeshImportData.md#getname)
- [GetOuter](ue_ue.FbxMeshImportData.md#getouter)
- [GetWorld](ue_ue.FbxMeshImportData.md#getworld)
- [K2\_ExtractFilenames](ue_ue.FbxMeshImportData.md#k2_extractfilenames)
- [K2\_GetFirstFilename](ue_ue.FbxMeshImportData.md#k2_getfirstfilename)
- [Find](ue_ue.FbxMeshImportData.md#find)
- [Load](ue_ue.FbxMeshImportData.md#load)
- [StaticClass](ue_ue.FbxMeshImportData.md#staticclass)

## Constructors

### constructor

• **new FbxMeshImportData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[constructor](ue_ue.FbxAssetImportData.md#constructor)

#### Defined in

[ue/ue.d.ts:35208](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35208)

## Properties

### FbxSceneImportDataReference

• **FbxSceneImportDataReference**: [`FbxSceneImportData`](ue_ue.FbxSceneImportData.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[FbxSceneImportDataReference](ue_ue.FbxAssetImportData.md#fbxsceneimportdatareference)

#### Defined in

[ue/ue.d.ts:35129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35129)

___

### ImportMaterialOriginalNameData

• **ImportMaterialOriginalNameData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:35216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35216)

___

### ImportMeshLodData

• **ImportMeshLodData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ImportMeshLodSectionsData`](ue_ue.ImportMeshLodSectionsData.md)\>

#### Defined in

[ue/ue.d.ts:35217](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35217)

___

### ImportRotation

• **ImportRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[ImportRotation](ue_ue.FbxAssetImportData.md#importrotation)

#### Defined in

[ue/ue.d.ts:35123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35123)

___

### ImportTranslation

• **ImportTranslation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[ImportTranslation](ue_ue.FbxAssetImportData.md#importtranslation)

#### Defined in

[ue/ue.d.ts:35122](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35122)

___

### ImportUniformScale

• **ImportUniformScale**: `number`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[ImportUniformScale](ue_ue.FbxAssetImportData.md#importuniformscale)

#### Defined in

[ue/ue.d.ts:35124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35124)

___

### NormalGenerationMethod

• **NormalGenerationMethod**: [`EFBXNormalGenerationMethod`](../enums/ue_ue.EFBXNormalGenerationMethod.md)

#### Defined in

[ue/ue.d.ts:35213](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35213)

___

### NormalImportMethod

• **NormalImportMethod**: [`EFBXNormalImportMethod`](../enums/ue_ue.EFBXNormalImportMethod.md)

#### Defined in

[ue/ue.d.ts:35212](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35212)

___

### SourceData

• **SourceData**: [`AssetImportInfo`](ue_ue.AssetImportInfo.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[SourceData](ue_ue.FbxAssetImportData.md#sourcedata)

#### Defined in

[ue/ue.d.ts:38](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[SourceFilePath](ue_ue.FbxAssetImportData.md#sourcefilepath)

#### Defined in

[ue/ue.d.ts:36](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36)

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[SourceFileTimestamp](ue_ue.FbxAssetImportData.md#sourcefiletimestamp)

#### Defined in

[ue/ue.d.ts:37](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37)

___

### \_\_tid\_AssetImportData\_\_

• **\_\_tid\_AssetImportData\_\_**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[__tid_AssetImportData__](ue_ue.FbxAssetImportData.md#__tid_assetimportdata__)

#### Defined in

[ue/ue.d.ts:45](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45)

___

### \_\_tid\_FbxAssetImportData\_\_

• **\_\_tid\_FbxAssetImportData\_\_**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[__tid_FbxAssetImportData__](ue_ue.FbxAssetImportData.md#__tid_fbxassetimportdata__)

#### Defined in

[ue/ue.d.ts:35134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35134)

___

### \_\_tid\_FbxMeshImportData\_\_

• **\_\_tid\_FbxMeshImportData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:35222](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35222)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[__tid_Object__](ue_ue.FbxAssetImportData.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bBakePivotInVertex

• **bBakePivotInVertex**: `boolean`

#### Defined in

[ue/ue.d.ts:35210](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35210)

___

### bComputeWeightedNormals

• **bComputeWeightedNormals**: `boolean`

#### Defined in

[ue/ue.d.ts:35214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35214)

___

### bConvertScene

• **bConvertScene**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[bConvertScene](ue_ue.FbxAssetImportData.md#bconvertscene)

#### Defined in

[ue/ue.d.ts:35125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35125)

___

### bConvertSceneUnit

• **bConvertSceneUnit**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[bConvertSceneUnit](ue_ue.FbxAssetImportData.md#bconvertsceneunit)

#### Defined in

[ue/ue.d.ts:35127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35127)

___

### bForceFrontXAxis

• **bForceFrontXAxis**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[bForceFrontXAxis](ue_ue.FbxAssetImportData.md#bforcefrontxaxis)

#### Defined in

[ue/ue.d.ts:35126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35126)

___

### bImportAsScene

• **bImportAsScene**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[bImportAsScene](ue_ue.FbxAssetImportData.md#bimportasscene)

#### Defined in

[ue/ue.d.ts:35128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35128)

___

### bImportMeshLODs

• **bImportMeshLODs**: `boolean`

#### Defined in

[ue/ue.d.ts:35211](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35211)

___

### bReorderMaterialToFbxOrder

• **bReorderMaterialToFbxOrder**: `boolean`

#### Defined in

[ue/ue.d.ts:35215](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35215)

___

### bTransformVertexToAbsolute

• **bTransformVertexToAbsolute**: `boolean`

#### Defined in

[ue/ue.d.ts:35209](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35209)

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

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[CreateDefaultSubobject](ue_ue.FbxAssetImportData.md#createdefaultsubobject)

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

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[ExecuteUbergraph](ue_ue.FbxAssetImportData.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[GetClass](ue_ue.FbxAssetImportData.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[GetName](ue_ue.FbxAssetImportData.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[GetOuter](ue_ue.FbxAssetImportData.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[GetWorld](ue_ue.FbxAssetImportData.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### K2\_ExtractFilenames

▸ **K2_ExtractFilenames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[K2_ExtractFilenames](ue_ue.FbxAssetImportData.md#k2_extractfilenames)

#### Defined in

[ue/ue.d.ts:39](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39)

___

### K2\_GetFirstFilename

▸ **K2_GetFirstFilename**(): `string`

#### Returns

`string`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[K2_GetFirstFilename](ue_ue.FbxAssetImportData.md#k2_getfirstfilename)

#### Defined in

[ue/ue.d.ts:40](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FbxMeshImportData`](ue_ue.FbxMeshImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FbxMeshImportData`](ue_ue.FbxMeshImportData.md)

#### Overrides

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[Find](ue_ue.FbxAssetImportData.md#find)

#### Defined in

[ue/ue.d.ts:35219](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35219)

___

### Load

▸ `Static` **Load**(`InName`): [`FbxMeshImportData`](ue_ue.FbxMeshImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FbxMeshImportData`](ue_ue.FbxMeshImportData.md)

#### Overrides

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[Load](ue_ue.FbxAssetImportData.md#load)

#### Defined in

[ue/ue.d.ts:35220](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35220)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[StaticClass](ue_ue.FbxAssetImportData.md#staticclass)

#### Defined in

[ue/ue.d.ts:35218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35218)
