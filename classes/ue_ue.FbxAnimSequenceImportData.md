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

#### Defined in

[ue/ue.d.ts:35151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35151)

## Properties

### AnimationLength

• **AnimationLength**: [`EFBXAnimationLengthImportType`](../enums/ue_ue.EFBXAnimationLengthImportType.md)

#### Defined in

[ue/ue.d.ts:35153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35153)

___

### CustomSampleRate

• **CustomSampleRate**: `number`

#### Defined in

[ue/ue.d.ts:35158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35158)

___

### EndFrame

• **EndFrame**: `number`

#### Defined in

[ue/ue.d.ts:35155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35155)

___

### FbxSceneImportDataReference

• **FbxSceneImportDataReference**: [`FbxSceneImportData`](ue_ue.FbxSceneImportData.md)

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[FbxSceneImportDataReference](ue_ue.FbxAssetImportData.md#fbxsceneimportdatareference)

#### Defined in

[ue/ue.d.ts:35129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35129)

___

### FrameImportRange

• **FrameImportRange**: [`Int32Interval`](ue_ue.Int32Interval.md)

#### Defined in

[ue/ue.d.ts:35156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35156)

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

### MaterialCurveSuffixes

• **MaterialCurveSuffixes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:35164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35164)

___

### SourceAnimationName

• **SourceAnimationName**: `string`

#### Defined in

[ue/ue.d.ts:35159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35159)

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

### StartFrame

• **StartFrame**: `number`

#### Defined in

[ue/ue.d.ts:35154](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35154)

___

### \_\_tid\_AssetImportData\_\_

• **\_\_tid\_AssetImportData\_\_**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[__tid_AssetImportData__](ue_ue.FbxAssetImportData.md#__tid_assetimportdata__)

#### Defined in

[ue/ue.d.ts:45](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45)

___

### \_\_tid\_FbxAnimSequenceImportData\_\_

• **\_\_tid\_FbxAnimSequenceImportData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:35173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35173)

___

### \_\_tid\_FbxAssetImportData\_\_

• **\_\_tid\_FbxAssetImportData\_\_**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[__tid_FbxAssetImportData__](ue_ue.FbxAssetImportData.md#__tid_fbxassetimportdata__)

#### Defined in

[ue/ue.d.ts:35134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35134)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[__tid_Object__](ue_ue.FbxAssetImportData.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

### bDeleteExistingCustomAttributeCurves

• **bDeleteExistingCustomAttributeCurves**: `boolean`

#### Defined in

[ue/ue.d.ts:35161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35161)

___

### bDeleteExistingMorphTargetCurves

• **bDeleteExistingMorphTargetCurves**: `boolean`

#### Defined in

[ue/ue.d.ts:35166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35166)

___

### bDoNotImportCurveWithZero

• **bDoNotImportCurveWithZero**: `boolean`

#### Defined in

[ue/ue.d.ts:35167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35167)

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

### bImportBoneTracks

• **bImportBoneTracks**: `boolean`

#### Defined in

[ue/ue.d.ts:35162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35162)

___

### bImportCustomAttribute

• **bImportCustomAttribute**: `boolean`

#### Defined in

[ue/ue.d.ts:35160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35160)

___

### bImportMeshesInBoneHierarchy

• **bImportMeshesInBoneHierarchy**: `boolean`

#### Defined in

[ue/ue.d.ts:35152](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35152)

___

### bPreserveLocalTransform

• **bPreserveLocalTransform**: `boolean`

#### Defined in

[ue/ue.d.ts:35168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35168)

___

### bRemoveRedundantKeys

• **bRemoveRedundantKeys**: `boolean`

#### Defined in

[ue/ue.d.ts:35165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35165)

___

### bSetMaterialDriveParameterOnCustomAttribute

• **bSetMaterialDriveParameterOnCustomAttribute**: `boolean`

#### Defined in

[ue/ue.d.ts:35163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35163)

___

### bUseDefaultSampleRate

• **bUseDefaultSampleRate**: `boolean`

#### Defined in

[ue/ue.d.ts:35157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35157)

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

#### Defined in

[ue/ue.d.ts:35170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35170)

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

#### Defined in

[ue/ue.d.ts:35171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35171)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FbxAssetImportData](ue_ue.FbxAssetImportData.md).[StaticClass](ue_ue.FbxAssetImportData.md#staticclass)

#### Defined in

[ue/ue.d.ts:35169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35169)
