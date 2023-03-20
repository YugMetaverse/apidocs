[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FbxStaticMeshImportData

# Class: FbxStaticMeshImportData

[ue/ue](../modules/ue_ue.md).FbxStaticMeshImportData

## Hierarchy

- [`FbxMeshImportData`](ue_ue.FbxMeshImportData.md)

  ↳ **`FbxStaticMeshImportData`**

## Table of contents

### Constructors

- [constructor](ue_ue.FbxStaticMeshImportData.md#constructor)

### Properties

- [FbxSceneImportDataReference](ue_ue.FbxStaticMeshImportData.md#fbxsceneimportdatareference)
- [ImportMaterialOriginalNameData](ue_ue.FbxStaticMeshImportData.md#importmaterialoriginalnamedata)
- [ImportMeshLodData](ue_ue.FbxStaticMeshImportData.md#importmeshloddata)
- [ImportRotation](ue_ue.FbxStaticMeshImportData.md#importrotation)
- [ImportTranslation](ue_ue.FbxStaticMeshImportData.md#importtranslation)
- [ImportUniformScale](ue_ue.FbxStaticMeshImportData.md#importuniformscale)
- [NormalGenerationMethod](ue_ue.FbxStaticMeshImportData.md#normalgenerationmethod)
- [NormalImportMethod](ue_ue.FbxStaticMeshImportData.md#normalimportmethod)
- [SourceData](ue_ue.FbxStaticMeshImportData.md#sourcedata)
- [SourceFilePath](ue_ue.FbxStaticMeshImportData.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.FbxStaticMeshImportData.md#sourcefiletimestamp)
- [StaticMeshLODGroup](ue_ue.FbxStaticMeshImportData.md#staticmeshlodgroup)
- [VertexColorImportOption](ue_ue.FbxStaticMeshImportData.md#vertexcolorimportoption)
- [VertexOverrideColor](ue_ue.FbxStaticMeshImportData.md#vertexoverridecolor)
- [\_\_tid\_AssetImportData\_\_](ue_ue.FbxStaticMeshImportData.md#__tid_assetimportdata__)
- [\_\_tid\_FbxAssetImportData\_\_](ue_ue.FbxStaticMeshImportData.md#__tid_fbxassetimportdata__)
- [\_\_tid\_FbxMeshImportData\_\_](ue_ue.FbxStaticMeshImportData.md#__tid_fbxmeshimportdata__)
- [\_\_tid\_FbxStaticMeshImportData\_\_](ue_ue.FbxStaticMeshImportData.md#__tid_fbxstaticmeshimportdata__)
- [\_\_tid\_Object\_\_](ue_ue.FbxStaticMeshImportData.md#__tid_object__)
- [bAutoGenerateCollision](ue_ue.FbxStaticMeshImportData.md#bautogeneratecollision)
- [bBakePivotInVertex](ue_ue.FbxStaticMeshImportData.md#bbakepivotinvertex)
- [bBuildAdjacencyBuffer](ue_ue.FbxStaticMeshImportData.md#bbuildadjacencybuffer)
- [bBuildReversedIndexBuffer](ue_ue.FbxStaticMeshImportData.md#bbuildreversedindexbuffer)
- [bCombineMeshes](ue_ue.FbxStaticMeshImportData.md#bcombinemeshes)
- [bComputeWeightedNormals](ue_ue.FbxStaticMeshImportData.md#bcomputeweightednormals)
- [bConvertScene](ue_ue.FbxStaticMeshImportData.md#bconvertscene)
- [bConvertSceneUnit](ue_ue.FbxStaticMeshImportData.md#bconvertsceneunit)
- [bForceFrontXAxis](ue_ue.FbxStaticMeshImportData.md#bforcefrontxaxis)
- [bGenerateLightmapUVs](ue_ue.FbxStaticMeshImportData.md#bgeneratelightmapuvs)
- [bImportAsScene](ue_ue.FbxStaticMeshImportData.md#bimportasscene)
- [bImportMeshLODs](ue_ue.FbxStaticMeshImportData.md#bimportmeshlods)
- [bOneConvexHullPerUCX](ue_ue.FbxStaticMeshImportData.md#boneconvexhullperucx)
- [bRemoveDegenerates](ue_ue.FbxStaticMeshImportData.md#bremovedegenerates)
- [bReorderMaterialToFbxOrder](ue_ue.FbxStaticMeshImportData.md#breordermaterialtofbxorder)
- [bTransformVertexToAbsolute](ue_ue.FbxStaticMeshImportData.md#btransformvertextoabsolute)

### Methods

- [CreateDefaultSubobject](ue_ue.FbxStaticMeshImportData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FbxStaticMeshImportData.md#executeubergraph)
- [GetClass](ue_ue.FbxStaticMeshImportData.md#getclass)
- [GetName](ue_ue.FbxStaticMeshImportData.md#getname)
- [GetOuter](ue_ue.FbxStaticMeshImportData.md#getouter)
- [GetWorld](ue_ue.FbxStaticMeshImportData.md#getworld)
- [K2\_ExtractFilenames](ue_ue.FbxStaticMeshImportData.md#k2_extractfilenames)
- [K2\_GetFirstFilename](ue_ue.FbxStaticMeshImportData.md#k2_getfirstfilename)
- [Find](ue_ue.FbxStaticMeshImportData.md#find)
- [Load](ue_ue.FbxStaticMeshImportData.md#load)
- [StaticClass](ue_ue.FbxStaticMeshImportData.md#staticclass)

## Constructors

### constructor

• **new FbxStaticMeshImportData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[constructor](ue_ue.FbxMeshImportData.md#constructor)

#### Defined in

[ue/ue.d.ts:35226](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35226)

## Properties

### FbxSceneImportDataReference

• **FbxSceneImportDataReference**: [`FbxSceneImportData`](ue_ue.FbxSceneImportData.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[FbxSceneImportDataReference](ue_ue.FbxMeshImportData.md#fbxsceneimportdatareference)

#### Defined in

[ue/ue.d.ts:35129](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35129)

___

### ImportMaterialOriginalNameData

• **ImportMaterialOriginalNameData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[ImportMaterialOriginalNameData](ue_ue.FbxMeshImportData.md#importmaterialoriginalnamedata)

#### Defined in

[ue/ue.d.ts:35216](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35216)

___

### ImportMeshLodData

• **ImportMeshLodData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ImportMeshLodSectionsData`](ue_ue.ImportMeshLodSectionsData.md)\>

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[ImportMeshLodData](ue_ue.FbxMeshImportData.md#importmeshloddata)

#### Defined in

[ue/ue.d.ts:35217](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35217)

___

### ImportRotation

• **ImportRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[ImportRotation](ue_ue.FbxMeshImportData.md#importrotation)

#### Defined in

[ue/ue.d.ts:35123](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35123)

___

### ImportTranslation

• **ImportTranslation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[ImportTranslation](ue_ue.FbxMeshImportData.md#importtranslation)

#### Defined in

[ue/ue.d.ts:35122](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35122)

___

### ImportUniformScale

• **ImportUniformScale**: `number`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[ImportUniformScale](ue_ue.FbxMeshImportData.md#importuniformscale)

#### Defined in

[ue/ue.d.ts:35124](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35124)

___

### NormalGenerationMethod

• **NormalGenerationMethod**: [`EFBXNormalGenerationMethod`](../enums/ue_ue.EFBXNormalGenerationMethod.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[NormalGenerationMethod](ue_ue.FbxMeshImportData.md#normalgenerationmethod)

#### Defined in

[ue/ue.d.ts:35213](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35213)

___

### NormalImportMethod

• **NormalImportMethod**: [`EFBXNormalImportMethod`](../enums/ue_ue.EFBXNormalImportMethod.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[NormalImportMethod](ue_ue.FbxMeshImportData.md#normalimportmethod)

#### Defined in

[ue/ue.d.ts:35212](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35212)

___

### SourceData

• **SourceData**: [`AssetImportInfo`](ue_ue.AssetImportInfo.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[SourceData](ue_ue.FbxMeshImportData.md#sourcedata)

#### Defined in

[ue/ue.d.ts:38](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[SourceFilePath](ue_ue.FbxMeshImportData.md#sourcefilepath)

#### Defined in

[ue/ue.d.ts:36](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36)

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[SourceFileTimestamp](ue_ue.FbxMeshImportData.md#sourcefiletimestamp)

#### Defined in

[ue/ue.d.ts:37](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37)

___

### StaticMeshLODGroup

• **StaticMeshLODGroup**: `string`

#### Defined in

[ue/ue.d.ts:35227](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35227)

___

### VertexColorImportOption

• **VertexColorImportOption**: [`EVertexColorImportOption`](../enums/ue_ue.EVertexColorImportOption.md)

#### Defined in

[ue/ue.d.ts:35228](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35228)

___

### VertexOverrideColor

• **VertexOverrideColor**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:35229](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35229)

___

### \_\_tid\_AssetImportData\_\_

• **\_\_tid\_AssetImportData\_\_**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[__tid_AssetImportData__](ue_ue.FbxMeshImportData.md#__tid_assetimportdata__)

#### Defined in

[ue/ue.d.ts:45](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45)

___

### \_\_tid\_FbxAssetImportData\_\_

• **\_\_tid\_FbxAssetImportData\_\_**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[__tid_FbxAssetImportData__](ue_ue.FbxMeshImportData.md#__tid_fbxassetimportdata__)

#### Defined in

[ue/ue.d.ts:35134](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35134)

___

### \_\_tid\_FbxMeshImportData\_\_

• **\_\_tid\_FbxMeshImportData\_\_**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[__tid_FbxMeshImportData__](ue_ue.FbxMeshImportData.md#__tid_fbxmeshimportdata__)

#### Defined in

[ue/ue.d.ts:35222](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35222)

___

### \_\_tid\_FbxStaticMeshImportData\_\_

• **\_\_tid\_FbxStaticMeshImportData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:35241](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35241)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[__tid_Object__](ue_ue.FbxMeshImportData.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bAutoGenerateCollision

• **bAutoGenerateCollision**: `boolean`

#### Defined in

[ue/ue.d.ts:35235](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35235)

___

### bBakePivotInVertex

• **bBakePivotInVertex**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bBakePivotInVertex](ue_ue.FbxMeshImportData.md#bbakepivotinvertex)

#### Defined in

[ue/ue.d.ts:35210](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35210)

___

### bBuildAdjacencyBuffer

• **bBuildAdjacencyBuffer**: `boolean`

#### Defined in

[ue/ue.d.ts:35231](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35231)

___

### bBuildReversedIndexBuffer

• **bBuildReversedIndexBuffer**: `boolean`

#### Defined in

[ue/ue.d.ts:35232](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35232)

___

### bCombineMeshes

• **bCombineMeshes**: `boolean`

#### Defined in

[ue/ue.d.ts:35236](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35236)

___

### bComputeWeightedNormals

• **bComputeWeightedNormals**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bComputeWeightedNormals](ue_ue.FbxMeshImportData.md#bcomputeweightednormals)

#### Defined in

[ue/ue.d.ts:35214](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35214)

___

### bConvertScene

• **bConvertScene**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bConvertScene](ue_ue.FbxMeshImportData.md#bconvertscene)

#### Defined in

[ue/ue.d.ts:35125](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35125)

___

### bConvertSceneUnit

• **bConvertSceneUnit**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bConvertSceneUnit](ue_ue.FbxMeshImportData.md#bconvertsceneunit)

#### Defined in

[ue/ue.d.ts:35127](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35127)

___

### bForceFrontXAxis

• **bForceFrontXAxis**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bForceFrontXAxis](ue_ue.FbxMeshImportData.md#bforcefrontxaxis)

#### Defined in

[ue/ue.d.ts:35126](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35126)

___

### bGenerateLightmapUVs

• **bGenerateLightmapUVs**: `boolean`

#### Defined in

[ue/ue.d.ts:35233](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35233)

___

### bImportAsScene

• **bImportAsScene**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bImportAsScene](ue_ue.FbxMeshImportData.md#bimportasscene)

#### Defined in

[ue/ue.d.ts:35128](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35128)

___

### bImportMeshLODs

• **bImportMeshLODs**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bImportMeshLODs](ue_ue.FbxMeshImportData.md#bimportmeshlods)

#### Defined in

[ue/ue.d.ts:35211](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35211)

___

### bOneConvexHullPerUCX

• **bOneConvexHullPerUCX**: `boolean`

#### Defined in

[ue/ue.d.ts:35234](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35234)

___

### bRemoveDegenerates

• **bRemoveDegenerates**: `boolean`

#### Defined in

[ue/ue.d.ts:35230](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35230)

___

### bReorderMaterialToFbxOrder

• **bReorderMaterialToFbxOrder**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bReorderMaterialToFbxOrder](ue_ue.FbxMeshImportData.md#breordermaterialtofbxorder)

#### Defined in

[ue/ue.d.ts:35215](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35215)

___

### bTransformVertexToAbsolute

• **bTransformVertexToAbsolute**: `boolean`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[bTransformVertexToAbsolute](ue_ue.FbxMeshImportData.md#btransformvertextoabsolute)

#### Defined in

[ue/ue.d.ts:35209](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35209)

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

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[CreateDefaultSubobject](ue_ue.FbxMeshImportData.md#createdefaultsubobject)

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

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[ExecuteUbergraph](ue_ue.FbxMeshImportData.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[GetClass](ue_ue.FbxMeshImportData.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[GetName](ue_ue.FbxMeshImportData.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[GetOuter](ue_ue.FbxMeshImportData.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[GetWorld](ue_ue.FbxMeshImportData.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### K2\_ExtractFilenames

▸ **K2_ExtractFilenames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[K2_ExtractFilenames](ue_ue.FbxMeshImportData.md#k2_extractfilenames)

#### Defined in

[ue/ue.d.ts:39](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39)

___

### K2\_GetFirstFilename

▸ **K2_GetFirstFilename**(): `string`

#### Returns

`string`

#### Inherited from

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[K2_GetFirstFilename](ue_ue.FbxMeshImportData.md#k2_getfirstfilename)

#### Defined in

[ue/ue.d.ts:40](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L40)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FbxStaticMeshImportData`](ue_ue.FbxStaticMeshImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FbxStaticMeshImportData`](ue_ue.FbxStaticMeshImportData.md)

#### Overrides

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[Find](ue_ue.FbxMeshImportData.md#find)

#### Defined in

[ue/ue.d.ts:35238](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35238)

___

### Load

▸ `Static` **Load**(`InName`): [`FbxStaticMeshImportData`](ue_ue.FbxStaticMeshImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FbxStaticMeshImportData`](ue_ue.FbxStaticMeshImportData.md)

#### Overrides

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[Load](ue_ue.FbxMeshImportData.md#load)

#### Defined in

[ue/ue.d.ts:35239](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35239)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FbxMeshImportData](ue_ue.FbxMeshImportData.md).[StaticClass](ue_ue.FbxMeshImportData.md#staticclass)

#### Defined in

[ue/ue.d.ts:35237](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35237)
