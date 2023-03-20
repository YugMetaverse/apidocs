[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LandscapeEditorObject

# Class: LandscapeEditorObject

[ue/ue](../modules/ue_ue.md).LandscapeEditorObject

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LandscapeEditorObject`**

## Table of contents

### Constructors

- [constructor](ue_ue.LandscapeEditorObject.md#constructor)

### Properties

- [AlphaBrushPanU](ue_ue.LandscapeEditorObject.md#alphabrushpanu)
- [AlphaBrushPanV](ue_ue.LandscapeEditorObject.md#alphabrushpanv)
- [AlphaBrushRotation](ue_ue.LandscapeEditorObject.md#alphabrushrotation)
- [AlphaBrushScale](ue_ue.LandscapeEditorObject.md#alphabrushscale)
- [AlphaTexture](ue_ue.LandscapeEditorObject.md#alphatexture)
- [AlphaTextureChannel](ue_ue.LandscapeEditorObject.md#alphatexturechannel)
- [AlphaTextureData](ue_ue.LandscapeEditorObject.md#alphatexturedata)
- [AlphaTextureSizeX](ue_ue.LandscapeEditorObject.md#alphatexturesizex)
- [AlphaTextureSizeY](ue_ue.LandscapeEditorObject.md#alphatexturesizey)
- [BlueprintBrush](ue_ue.LandscapeEditorObject.md#blueprintbrush)
- [BrushComponentSize](ue_ue.LandscapeEditorObject.md#brushcomponentsize)
- [BrushFalloff](ue_ue.LandscapeEditorObject.md#brushfalloff)
- [BrushRadius](ue_ue.LandscapeEditorObject.md#brushradius)
- [CurrentLayerIndex](ue_ue.LandscapeEditorObject.md#currentlayerindex)
- [DetailScale](ue_ue.LandscapeEditorObject.md#detailscale)
- [ErodeIterationNum](ue_ue.LandscapeEditorObject.md#erodeiterationnum)
- [ErodeSurfaceThickness](ue_ue.LandscapeEditorObject.md#erodesurfacethickness)
- [ErodeThresh](ue_ue.LandscapeEditorObject.md#erodethresh)
- [ErosionNoiseMode](ue_ue.LandscapeEditorObject.md#erosionnoisemode)
- [ErosionNoiseScale](ue_ue.LandscapeEditorObject.md#erosionnoisescale)
- [FlattenEyeDropperModeDesiredTarget](ue_ue.LandscapeEditorObject.md#flatteneyedroppermodedesiredtarget)
- [FlattenMode](ue_ue.LandscapeEditorObject.md#flattenmode)
- [FlattenTarget](ue_ue.LandscapeEditorObject.md#flattentarget)
- [GizmoHeightmapFilenameString](ue_ue.LandscapeEditorObject.md#gizmoheightmapfilenamestring)
- [GizmoImportLayers](ue_ue.LandscapeEditorObject.md#gizmoimportlayers)
- [GizmoImportSize](ue_ue.LandscapeEditorObject.md#gizmoimportsize)
- [HErodeIterationNum](ue_ue.LandscapeEditorObject.md#herodeiterationnum)
- [HErosionDetailScale](ue_ue.LandscapeEditorObject.md#herosiondetailscale)
- [ImportLandscape\_AlphamapType](ue_ue.LandscapeEditorObject.md#importlandscape_alphamaptype)
- [ImportLandscape\_Data](ue_ue.LandscapeEditorObject.md#importlandscape_data)
- [ImportLandscape\_Height](ue_ue.LandscapeEditorObject.md#importlandscape_height)
- [ImportLandscape\_HeightmapErrorMessage](ue_ue.LandscapeEditorObject.md#importlandscape_heightmaperrormessage)
- [ImportLandscape\_HeightmapFilename](ue_ue.LandscapeEditorObject.md#importlandscape_heightmapfilename)
- [ImportLandscape\_HeightmapImportResult](ue_ue.LandscapeEditorObject.md#importlandscape_heightmapimportresult)
- [ImportLandscape\_Layers](ue_ue.LandscapeEditorObject.md#importlandscape_layers)
- [ImportLandscape\_Width](ue_ue.LandscapeEditorObject.md#importlandscape_width)
- [MaximumValueRadius](ue_ue.LandscapeEditorObject.md#maximumvalueradius)
- [MirrorOp](ue_ue.LandscapeEditorObject.md#mirrorop)
- [MirrorPoint](ue_ue.LandscapeEditorObject.md#mirrorpoint)
- [MirrorSmoothingWidth](ue_ue.LandscapeEditorObject.md#mirrorsmoothingwidth)
- [NewLandscape\_ComponentCount](ue_ue.LandscapeEditorObject.md#newlandscape_componentcount)
- [NewLandscape\_Location](ue_ue.LandscapeEditorObject.md#newlandscape_location)
- [NewLandscape\_Material](ue_ue.LandscapeEditorObject.md#newlandscape_material)
- [NewLandscape\_QuadsPerSection](ue_ue.LandscapeEditorObject.md#newlandscape_quadspersection)
- [NewLandscape\_Rotation](ue_ue.LandscapeEditorObject.md#newlandscape_rotation)
- [NewLandscape\_Scale](ue_ue.LandscapeEditorObject.md#newlandscape_scale)
- [NewLandscape\_SectionsPerComponent](ue_ue.LandscapeEditorObject.md#newlandscape_sectionspercomponent)
- [NoiseMode](ue_ue.LandscapeEditorObject.md#noisemode)
- [NoiseScale](ue_ue.LandscapeEditorObject.md#noisescale)
- [PaintingRestriction](ue_ue.LandscapeEditorObject.md#paintingrestriction)
- [PasteMode](ue_ue.LandscapeEditorObject.md#pastemode)
- [RainAmount](ue_ue.LandscapeEditorObject.md#rainamount)
- [RainDistMode](ue_ue.LandscapeEditorObject.md#raindistmode)
- [RainDistScale](ue_ue.LandscapeEditorObject.md#raindistscale)
- [RampSideFalloff](ue_ue.LandscapeEditorObject.md#rampsidefalloff)
- [RampWidth](ue_ue.LandscapeEditorObject.md#rampwidth)
- [ResizeLandscape\_ComponentCount](ue_ue.LandscapeEditorObject.md#resizelandscape_componentcount)
- [ResizeLandscape\_ConvertMode](ue_ue.LandscapeEditorObject.md#resizelandscape_convertmode)
- [ResizeLandscape\_QuadsPerSection](ue_ue.LandscapeEditorObject.md#resizelandscape_quadspersection)
- [ResizeLandscape\_SectionsPerComponent](ue_ue.LandscapeEditorObject.md#resizelandscape_sectionspercomponent)
- [SedimentCapacity](ue_ue.LandscapeEditorObject.md#sedimentcapacity)
- [ShowUnusedLayers](ue_ue.LandscapeEditorObject.md#showunusedlayers)
- [SmoothFilterKernelSize](ue_ue.LandscapeEditorObject.md#smoothfilterkernelsize)
- [TargetDisplayOrder](ue_ue.LandscapeEditorObject.md#targetdisplayorder)
- [TerraceInterval](ue_ue.LandscapeEditorObject.md#terraceinterval)
- [TerraceSmooth](ue_ue.LandscapeEditorObject.md#terracesmooth)
- [ToolStrength](ue_ue.LandscapeEditorObject.md#toolstrength)
- [WeightTargetValue](ue_ue.LandscapeEditorObject.md#weighttargetvalue)
- [WorldSpacePatternBrushSettings](ue_ue.LandscapeEditorObject.md#worldspacepatternbrushsettings)
- [\_\_tid\_LandscapeEditorObject\_\_](ue_ue.LandscapeEditorObject.md#__tid_landscapeeditorobject__)
- [\_\_tid\_Object\_\_](ue_ue.LandscapeEditorObject.md#__tid_object__)
- [bAlphaBrushAutoRotate](ue_ue.LandscapeEditorObject.md#balphabrushautorotate)
- [bApplyToAllTargets](ue_ue.LandscapeEditorObject.md#bapplytoalltargets)
- [bCanHaveLayersContent](ue_ue.LandscapeEditorObject.md#bcanhavelayerscontent)
- [bCombinedLayersOperation](ue_ue.LandscapeEditorObject.md#bcombinedlayersoperation)
- [bDetailSmooth](ue_ue.LandscapeEditorObject.md#bdetailsmooth)
- [bFlattenEyeDropperModeActivated](ue_ue.LandscapeEditorObject.md#bflatteneyedroppermodeactivated)
- [bHErosionDetailSmooth](ue_ue.LandscapeEditorObject.md#bherosiondetailsmooth)
- [bPickValuePerApply](ue_ue.LandscapeEditorObject.md#bpickvalueperapply)
- [bShowFlattenTargetPreview](ue_ue.LandscapeEditorObject.md#bshowflattentargetpreview)
- [bSmoothGizmoBrush](ue_ue.LandscapeEditorObject.md#bsmoothgizmobrush)
- [bSnapGizmo](ue_ue.LandscapeEditorObject.md#bsnapgizmo)
- [bUseClayBrush](ue_ue.LandscapeEditorObject.md#buseclaybrush)
- [bUseFlattenTarget](ue_ue.LandscapeEditorObject.md#buseflattentarget)
- [bUseNegativeMask](ue_ue.LandscapeEditorObject.md#busenegativemask)
- [bUseSelectedRegion](ue_ue.LandscapeEditorObject.md#buseselectedregion)
- [bUseSlopeFlatten](ue_ue.LandscapeEditorObject.md#buseslopeflatten)
- [bUseWeightTargetValue](ue_ue.LandscapeEditorObject.md#buseweighttargetvalue)
- [bUseWorldSpacePatternBrush](ue_ue.LandscapeEditorObject.md#buseworldspacepatternbrush)

### Methods

- [CreateDefaultSubobject](ue_ue.LandscapeEditorObject.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LandscapeEditorObject.md#executeubergraph)
- [GetClass](ue_ue.LandscapeEditorObject.md#getclass)
- [GetName](ue_ue.LandscapeEditorObject.md#getname)
- [GetOuter](ue_ue.LandscapeEditorObject.md#getouter)
- [GetWorld](ue_ue.LandscapeEditorObject.md#getworld)
- [Find](ue_ue.LandscapeEditorObject.md#find)
- [Load](ue_ue.LandscapeEditorObject.md#load)
- [StaticClass](ue_ue.LandscapeEditorObject.md#staticclass)

## Constructors

### constructor

• **new LandscapeEditorObject**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AlphaBrushPanU

• **AlphaBrushPanU**: `number`

___

### AlphaBrushPanV

• **AlphaBrushPanV**: `number`

___

### AlphaBrushRotation

• **AlphaBrushRotation**: `number`

___

### AlphaBrushScale

• **AlphaBrushScale**: `number`

___

### AlphaTexture

• **AlphaTexture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### AlphaTextureChannel

• **AlphaTextureChannel**: [`EColorChannel`](../enums/ue_ue.EColorChannel.md)

___

### AlphaTextureData

• **AlphaTextureData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### AlphaTextureSizeX

• **AlphaTextureSizeX**: `number`

___

### AlphaTextureSizeY

• **AlphaTextureSizeY**: `number`

___

### BlueprintBrush

• **BlueprintBrush**: [`Class`](ue_ue.Class.md)

___

### BrushComponentSize

• **BrushComponentSize**: `number`

___

### BrushFalloff

• **BrushFalloff**: `number`

___

### BrushRadius

• **BrushRadius**: `number`

___

### CurrentLayerIndex

• **CurrentLayerIndex**: `number`

___

### DetailScale

• **DetailScale**: `number`

___

### ErodeIterationNum

• **ErodeIterationNum**: `number`

___

### ErodeSurfaceThickness

• **ErodeSurfaceThickness**: `number`

___

### ErodeThresh

• **ErodeThresh**: `number`

___

### ErosionNoiseMode

• **ErosionNoiseMode**: [`ELandscapeToolErosionMode`](../enums/ue_ue.ELandscapeToolErosionMode.md)

___

### ErosionNoiseScale

• **ErosionNoiseScale**: `number`

___

### FlattenEyeDropperModeDesiredTarget

• **FlattenEyeDropperModeDesiredTarget**: `number`

___

### FlattenMode

• **FlattenMode**: [`ELandscapeToolFlattenMode`](../enums/ue_ue.ELandscapeToolFlattenMode.md)

___

### FlattenTarget

• **FlattenTarget**: `number`

___

### GizmoHeightmapFilenameString

• **GizmoHeightmapFilenameString**: `string`

___

### GizmoImportLayers

• **GizmoImportLayers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GizmoImportLayer`](ue_ue.GizmoImportLayer.md)\>

___

### GizmoImportSize

• **GizmoImportSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### HErodeIterationNum

• **HErodeIterationNum**: `number`

___

### HErosionDetailScale

• **HErosionDetailScale**: `number`

___

### ImportLandscape\_AlphamapType

• **ImportLandscape\_AlphamapType**: [`ELandscapeImportAlphamapType`](../enums/ue_ue.ELandscapeImportAlphamapType.md)

___

### ImportLandscape\_Data

• **ImportLandscape\_Data**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### ImportLandscape\_Height

• **ImportLandscape\_Height**: `number`

___

### ImportLandscape\_HeightmapErrorMessage

• **ImportLandscape\_HeightmapErrorMessage**: `string`

___

### ImportLandscape\_HeightmapFilename

• **ImportLandscape\_HeightmapFilename**: `string`

___

### ImportLandscape\_HeightmapImportResult

• **ImportLandscape\_HeightmapImportResult**: [`ELandscapeImportResult`](../enums/ue_ue.ELandscapeImportResult.md)

___

### ImportLandscape\_Layers

• **ImportLandscape\_Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeImportLayer`](ue_ue.LandscapeImportLayer.md)\>

___

### ImportLandscape\_Width

• **ImportLandscape\_Width**: `number`

___

### MaximumValueRadius

• **MaximumValueRadius**: `number`

___

### MirrorOp

• **MirrorOp**: [`ELandscapeMirrorOperation`](../enums/ue_ue.ELandscapeMirrorOperation.md)

___

### MirrorPoint

• **MirrorPoint**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### MirrorSmoothingWidth

• **MirrorSmoothingWidth**: `number`

___

### NewLandscape\_ComponentCount

• **NewLandscape\_ComponentCount**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### NewLandscape\_Location

• **NewLandscape\_Location**: [`Vector`](ue_ue_s.Vector.md)

___

### NewLandscape\_Material

• **NewLandscape\_Material**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

___

### NewLandscape\_QuadsPerSection

• **NewLandscape\_QuadsPerSection**: `number`

___

### NewLandscape\_Rotation

• **NewLandscape\_Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### NewLandscape\_Scale

• **NewLandscape\_Scale**: [`Vector`](ue_ue_s.Vector.md)

___

### NewLandscape\_SectionsPerComponent

• **NewLandscape\_SectionsPerComponent**: `number`

___

### NoiseMode

• **NoiseMode**: [`ELandscapeToolNoiseMode`](../enums/ue_ue.ELandscapeToolNoiseMode.md)

___

### NoiseScale

• **NoiseScale**: `number`

___

### PaintingRestriction

• **PaintingRestriction**: [`ELandscapeLayerPaintingRestriction`](../enums/ue_ue.ELandscapeLayerPaintingRestriction.md)

___

### PasteMode

• **PasteMode**: [`ELandscapeToolPasteMode`](../enums/ue_ue.ELandscapeToolPasteMode.md)

___

### RainAmount

• **RainAmount**: `number`

___

### RainDistMode

• **RainDistMode**: [`ELandscapeToolHydroErosionMode`](../enums/ue_ue.ELandscapeToolHydroErosionMode.md)

___

### RainDistScale

• **RainDistScale**: `number`

___

### RampSideFalloff

• **RampSideFalloff**: `number`

___

### RampWidth

• **RampWidth**: `number`

___

### ResizeLandscape\_ComponentCount

• **ResizeLandscape\_ComponentCount**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### ResizeLandscape\_ConvertMode

• **ResizeLandscape\_ConvertMode**: [`ELandscapeConvertMode`](../enums/ue_ue.ELandscapeConvertMode.md)

___

### ResizeLandscape\_QuadsPerSection

• **ResizeLandscape\_QuadsPerSection**: `number`

___

### ResizeLandscape\_SectionsPerComponent

• **ResizeLandscape\_SectionsPerComponent**: `number`

___

### SedimentCapacity

• **SedimentCapacity**: `number`

___

### ShowUnusedLayers

• **ShowUnusedLayers**: `boolean`

___

### SmoothFilterKernelSize

• **SmoothFilterKernelSize**: `number`

___

### TargetDisplayOrder

• **TargetDisplayOrder**: [`ELandscapeLayerDisplayMode`](../enums/ue_ue.ELandscapeLayerDisplayMode.md)

___

### TerraceInterval

• **TerraceInterval**: `number`

___

### TerraceSmooth

• **TerraceSmooth**: `number`

___

### ToolStrength

• **ToolStrength**: `number`

___

### WeightTargetValue

• **WeightTargetValue**: `number`

___

### WorldSpacePatternBrushSettings

• **WorldSpacePatternBrushSettings**: [`LandscapePatternBrushWorldSpaceSettings`](ue_ue.LandscapePatternBrushWorldSpaceSettings.md)

___

### \_\_tid\_LandscapeEditorObject\_\_

• **\_\_tid\_LandscapeEditorObject\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bAlphaBrushAutoRotate

• **bAlphaBrushAutoRotate**: `boolean`

___

### bApplyToAllTargets

• **bApplyToAllTargets**: `boolean`

___

### bCanHaveLayersContent

• **bCanHaveLayersContent**: `boolean`

___

### bCombinedLayersOperation

• **bCombinedLayersOperation**: `boolean`

___

### bDetailSmooth

• **bDetailSmooth**: `boolean`

___

### bFlattenEyeDropperModeActivated

• **bFlattenEyeDropperModeActivated**: `boolean`

___

### bHErosionDetailSmooth

• **bHErosionDetailSmooth**: `boolean`

___

### bPickValuePerApply

• **bPickValuePerApply**: `boolean`

___

### bShowFlattenTargetPreview

• **bShowFlattenTargetPreview**: `boolean`

___

### bSmoothGizmoBrush

• **bSmoothGizmoBrush**: `boolean`

___

### bSnapGizmo

• **bSnapGizmo**: `boolean`

___

### bUseClayBrush

• **bUseClayBrush**: `boolean`

___

### bUseFlattenTarget

• **bUseFlattenTarget**: `boolean`

___

### bUseNegativeMask

• **bUseNegativeMask**: `boolean`

___

### bUseSelectedRegion

• **bUseSelectedRegion**: `boolean`

___

### bUseSlopeFlatten

• **bUseSlopeFlatten**: `boolean`

___

### bUseWeightTargetValue

• **bUseWeightTargetValue**: `boolean`

___

### bUseWorldSpacePatternBrush

• **bUseWorldSpacePatternBrush**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LandscapeEditorObject`](ue_ue.LandscapeEditorObject.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LandscapeEditorObject`](ue_ue.LandscapeEditorObject.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LandscapeEditorObject`](ue_ue.LandscapeEditorObject.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LandscapeEditorObject`](ue_ue.LandscapeEditorObject.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
