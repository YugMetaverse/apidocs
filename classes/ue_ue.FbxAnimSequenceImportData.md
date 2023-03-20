[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FbxAnimSequenceImportData

# Class: FbxAnimSequenceImportData

[ue/ue](../modules/ue_ue.md).FbxAnimSequenceImportData

## Hierarchy

- [`FbxAssetImportData`](ue_ue.FbxAssetImportData.md)

  ↳ **`FbxAnimSequenceImportData`**

## Table of contents

### Constructors

- [constructor](ue_ue.FbxAnimSequenceImportData.md#constructor)

### Properties

- [AnimationLength](ue_ue.FbxAnimSequenceImportData.md#animationlength)
- [CustomSampleRate](ue_ue.FbxAnimSequenceImportData.md#customsamplerate)
- [EndFrame](ue_ue.FbxAnimSequenceImportData.md#endframe)
- [FbxSceneImportDataReference](ue_ue.FbxAnimSequenceImportData.md#fbxsceneimportdatareference)
- [FrameImportRange](ue_ue.FbxAnimSequenceImportData.md#frameimportrange)
- [ImportRotation](ue_ue.FbxAnimSequenceImportData.md#importrotation)
- [ImportTranslation](ue_ue.FbxAnimSequenceImportData.md#importtranslation)
- [ImportUniformScale](ue_ue.FbxAnimSequenceImportData.md#importuniformscale)
- [MaterialCurveSuffixes](ue_ue.FbxAnimSequenceImportData.md#materialcurvesuffixes)
- [SourceAnimationName](ue_ue.FbxAnimSequenceImportData.md#sourceanimationname)
- [SourceData](ue_ue.FbxAnimSequenceImportData.md#sourcedata)
- [SourceFilePath](ue_ue.FbxAnimSequenceImportData.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.FbxAnimSequenceImportData.md#sourcefiletimestamp)
- [StartFrame](ue_ue.FbxAnimSequenceImportData.md#startframe)
- [\_\_tid\_AssetImportData\_\_](ue_ue.FbxAnimSequenceImportData.md#__tid_assetimportdata__)
- [\_\_tid\_FbxAnimSequenceImportData\_\_](ue_ue.FbxAnimSequenceImportData.md#__tid_fbxanimsequenceimportdata__)
- [\_\_tid\_FbxAssetImportData\_\_](ue_ue.FbxAnimSequenceImportData.md#__tid_fbxassetimportdata__)
- [\_\_tid\_Object\_\_](ue_ue.FbxAnimSequenceImportData.md#__tid_object__)
- [bConvertScene](ue_ue.FbxAnimSequenceImportData.md#bconvertscene)
- [bConvertSceneUnit](ue_ue.FbxAnimSequenceImportData.md#bconvertsceneunit)
- [bDeleteExistingCustomAttributeCurves](ue_ue.FbxAnimSequenceImportData.md#bdeleteexistingcustomattributecurves)
- [bDeleteExistingMorphTargetCurves](ue_ue.FbxAnimSequenceImportData.md#bdeleteexistingmorphtargetcurves)
- [bDoNotImportCurveWithZero](ue_ue.FbxAnimSequenceImportData.md#bdonotimportcurvewithzero)
- [bForceFrontXAxis](ue_ue.FbxAnimSequenceImportData.md#bforcefrontxaxis)
- [bImportAsScene](ue_ue.FbxAnimSequenceImportData.md#bimportasscene)
- [bImportBoneTracks](ue_ue.FbxAnimSequenceImportData.md#bimportbonetracks)
- [bImportCustomAttribute](ue_ue.FbxAnimSequenceImportData.md#bimportcustomattribute)
- [bImportMeshesInBoneHierarchy](ue_ue.FbxAnimSequenceImportData.md#bimportmeshesinbonehierarchy)
- [bPreserveLocalTransform](ue_ue.FbxAnimSequenceImportData.md#bpreservelocaltransform)
- [bRemoveRedundantKeys](ue_ue.FbxAnimSequenceImportData.md#bremoveredundantkeys)
- [bSetMaterialDriveParameterOnCustomAttribute](ue_ue.FbxAnimSequenceImportData.md#bsetmaterialdriveparameteroncustomattribute)
- [bUseDefaultSampleRate](ue_ue.FbxAnimSequenceImportData.md#busedefaultsamplerate)

### Methods

- [CreateDefaultSubobject](ue_ue.FbxAnimSequenceImportData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FbxAnimSequenceImportData.md#executeubergraph)
- [GetClass](ue_ue.FbxAnimSequenceImportData.md#getclass)
- [GetName](ue_ue.FbxAnimSequenceImportData.md#getname)
- [GetOuter](ue_ue.FbxAnimSequenceImportData.md#getouter)
- [GetWorld](ue_ue.FbxAnimSequenceImportData.md#getworld)
- [K2\_ExtractFilenames](ue_ue.FbxAnimSequenceImportData.md#k2_extractfilenames)
- [K2\_GetFirstFilename](ue_ue.FbxAnimSequenceImportData.md#k2_getfirstfilename)
- [Find](ue_ue.FbxAnimSequenceImportData.md#find)
- [Load](ue_ue.FbxAnimSequenceImportData.md#load)
- [StaticClass](ue_ue.FbxAnimSequenceImportData.md#staticclass)

## Constructors

### constructor

• **new FbxAnimSequenceImportData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[constructor](ue_ue.FbxAssetImportData.md#constructor)

## Properties

### AnimationLength

• **AnimationLength**: [`EFBXAnimationLengthImportType`](../enums/ue_ue.EFBXAnimationLengthImportType.md)

___

### CustomSampleRate

• **CustomSampleRate**: `number`

___

### EndFrame

• **EndFrame**: `number`

___

### FbxSceneImportDataReference

• **FbxSceneImportDataReference**: [`FbxSceneImportData`](ue_ue.FbxSceneImportData.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[FbxSceneImportDataReference](ue_ue.FbxAssetImportData.md#fbxsceneimportdatareference)

___

### FrameImportRange

• **FrameImportRange**: [`Int32Interval`](ue_ue.Int32Interval.md)

___

### ImportRotation

• **ImportRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[ImportRotation](ue_ue.FbxAssetImportData.md#importrotation)

___

### ImportTranslation

• **ImportTranslation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[ImportTranslation](ue_ue.FbxAssetImportData.md#importtranslation)

___

### ImportUniformScale

• **ImportUniformScale**: `number`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[ImportUniformScale](ue_ue.FbxAssetImportData.md#importuniformscale)

___

### MaterialCurveSuffixes

• **MaterialCurveSuffixes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### SourceAnimationName

• **SourceAnimationName**: `string`

___

### SourceData

• **SourceData**: [`AssetImportInfo`](ue_ue.AssetImportInfo.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[SourceData](ue_ue.FbxAssetImportData.md#sourcedata)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[SourceFilePath](ue_ue.FbxAssetImportData.md#sourcefilepath)

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[SourceFileTimestamp](ue_ue.FbxAssetImportData.md#sourcefiletimestamp)

___

### StartFrame

• **StartFrame**: `number`

___

### \_\_tid\_AssetImportData\_\_

• **\_\_tid\_AssetImportData\_\_**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[__tid_AssetImportData__](ue_ue.FbxAssetImportData.md#__tid_assetimportdata__)

___

### \_\_tid\_FbxAnimSequenceImportData\_\_

• **\_\_tid\_FbxAnimSequenceImportData\_\_**: `boolean`

___

### \_\_tid\_FbxAssetImportData\_\_

• **\_\_tid\_FbxAssetImportData\_\_**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[__tid_FbxAssetImportData__](ue_ue.FbxAssetImportData.md#__tid_fbxassetimportdata__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[__tid_Object__](ue_ue.FbxAssetImportData.md#__tid_object__)

___

### bConvertScene

• **bConvertScene**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[bConvertScene](ue_ue.FbxAssetImportData.md#bconvertscene)

___

### bConvertSceneUnit

• **bConvertSceneUnit**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[bConvertSceneUnit](ue_ue.FbxAssetImportData.md#bconvertsceneunit)

___

### bDeleteExistingCustomAttributeCurves

• **bDeleteExistingCustomAttributeCurves**: `boolean`

___

### bDeleteExistingMorphTargetCurves

• **bDeleteExistingMorphTargetCurves**: `boolean`

___

### bDoNotImportCurveWithZero

• **bDoNotImportCurveWithZero**: `boolean`

___

### bForceFrontXAxis

• **bForceFrontXAxis**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[bForceFrontXAxis](ue_ue.FbxAssetImportData.md#bforcefrontxaxis)

___

### bImportAsScene

• **bImportAsScene**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[bImportAsScene](ue_ue.FbxAssetImportData.md#bimportasscene)

___

### bImportBoneTracks

• **bImportBoneTracks**: `boolean`

___

### bImportCustomAttribute

• **bImportCustomAttribute**: `boolean`

___

### bImportMeshesInBoneHierarchy

• **bImportMeshesInBoneHierarchy**: `boolean`

___

### bPreserveLocalTransform

• **bPreserveLocalTransform**: `boolean`

___

### bRemoveRedundantKeys

• **bRemoveRedundantKeys**: `boolean`

___

### bSetMaterialDriveParameterOnCustomAttribute

• **bSetMaterialDriveParameterOnCustomAttribute**: `boolean`

___

### bUseDefaultSampleRate

• **bUseDefaultSampleRate**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[GetClass](ue_ue.FbxAssetImportData.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[GetName](ue_ue.FbxAssetImportData.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[GetOuter](ue_ue.FbxAssetImportData.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[GetWorld](ue_ue.FbxAssetImportData.md#getworld)

___

### K2\_ExtractFilenames

▸ **K2_ExtractFilenames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[K2_ExtractFilenames](ue_ue.FbxAssetImportData.md#k2_extractfilenames)

___

### K2\_GetFirstFilename

▸ **K2_GetFirstFilename**(): `string`

#### Returns

`string`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[K2_GetFirstFilename](ue_ue.FbxAssetImportData.md#k2_getfirstfilename)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FbxAnimSequenceImportData`](ue_ue.FbxAnimSequenceImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FbxAnimSequenceImportData`](ue_ue.FbxAnimSequenceImportData.md)

#### Overrides

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[Find](ue_ue.FbxAssetImportData.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`FbxAnimSequenceImportData`](ue_ue.FbxAnimSequenceImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FbxAnimSequenceImportData`](ue_ue.FbxAnimSequenceImportData.md)

#### Overrides

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[Load](ue_ue.FbxAssetImportData.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[StaticClass](ue_ue.FbxAssetImportData.md#staticclass)
