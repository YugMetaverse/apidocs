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

#### Defined in

[ue/ue.d.ts:44296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44296)

## Properties

### AlphaBrushPanU

• **AlphaBrushPanU**: `number`

#### Defined in

[ue/ue.d.ts:44370](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44370)

___

### AlphaBrushPanV

• **AlphaBrushPanV**: `number`

#### Defined in

[ue/ue.d.ts:44371](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44371)

___

### AlphaBrushRotation

• **AlphaBrushRotation**: `number`

#### Defined in

[ue/ue.d.ts:44369](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44369)

___

### AlphaBrushScale

• **AlphaBrushScale**: `number`

#### Defined in

[ue/ue.d.ts:44367](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44367)

___

### AlphaTexture

• **AlphaTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:44374](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44374)

___

### AlphaTextureChannel

• **AlphaTextureChannel**: [`EColorChannel`](../enums/ue_ue.EColorChannel.md)

#### Defined in

[ue/ue.d.ts:44375](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44375)

___

### AlphaTextureData

• **AlphaTextureData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:44378](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44378)

___

### AlphaTextureSizeX

• **AlphaTextureSizeX**: `number`

#### Defined in

[ue/ue.d.ts:44376](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44376)

___

### AlphaTextureSizeY

• **AlphaTextureSizeY**: `number`

#### Defined in

[ue/ue.d.ts:44377](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44377)

___

### BlueprintBrush

• **BlueprintBrush**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:44343](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44343)

___

### BrushComponentSize

• **BrushComponentSize**: `number`

#### Defined in

[ue/ue.d.ts:44379](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44379)

___

### BrushFalloff

• **BrushFalloff**: `number`

#### Defined in

[ue/ue.d.ts:44365](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44365)

___

### BrushRadius

• **BrushRadius**: `number`

#### Defined in

[ue/ue.d.ts:44364](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44364)

___

### CurrentLayerIndex

• **CurrentLayerIndex**: `number`

#### Defined in

[ue/ue.d.ts:44383](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44383)

___

### DetailScale

• **DetailScale**: `number`

#### Defined in

[ue/ue.d.ts:44316](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44316)

___

### ErodeIterationNum

• **ErodeIterationNum**: `number`

#### Defined in

[ue/ue.d.ts:44319](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44319)

___

### ErodeSurfaceThickness

• **ErodeSurfaceThickness**: `number`

#### Defined in

[ue/ue.d.ts:44318](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44318)

___

### ErodeThresh

• **ErodeThresh**: `number`

#### Defined in

[ue/ue.d.ts:44317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44317)

___

### ErosionNoiseMode

• **ErosionNoiseMode**: [`ELandscapeToolErosionMode`](../enums/ue_ue.ELandscapeToolErosionMode.md)

#### Defined in

[ue/ue.d.ts:44320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44320)

___

### ErosionNoiseScale

• **ErosionNoiseScale**: `number`

#### Defined in

[ue/ue.d.ts:44321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44321)

___

### FlattenEyeDropperModeDesiredTarget

• **FlattenEyeDropperModeDesiredTarget**: `number`

#### Defined in

[ue/ue.d.ts:44311](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44311)

___

### FlattenMode

• **FlattenMode**: [`ELandscapeToolFlattenMode`](../enums/ue_ue.ELandscapeToolFlattenMode.md)

#### Defined in

[ue/ue.d.ts:44302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44302)

___

### FlattenTarget

• **FlattenTarget**: `number`

#### Defined in

[ue/ue.d.ts:44306](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44306)

___

### GizmoHeightmapFilenameString

• **GizmoHeightmapFilenameString**: `string`

#### Defined in

[ue/ue.d.ts:44337](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44337)

___

### GizmoImportLayers

• **GizmoImportLayers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GizmoImportLayer`](ue_ue.GizmoImportLayer.md)\>

#### Defined in

[ue/ue.d.ts:44339](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44339)

___

### GizmoImportSize

• **GizmoImportSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:44338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44338)

___

### HErodeIterationNum

• **HErodeIterationNum**: `number`

#### Defined in

[ue/ue.d.ts:44324](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44324)

___

### HErosionDetailScale

• **HErosionDetailScale**: `number`

#### Defined in

[ue/ue.d.ts:44328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44328)

___

### ImportLandscape\_AlphamapType

• **ImportLandscape\_AlphamapType**: [`ELandscapeImportAlphamapType`](../enums/ue_ue.ELandscapeImportAlphamapType.md)

#### Defined in

[ue/ue.d.ts:44362](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44362)

___

### ImportLandscape\_Data

• **ImportLandscape\_Data**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:44360](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44360)

___

### ImportLandscape\_Height

• **ImportLandscape\_Height**: `number`

#### Defined in

[ue/ue.d.ts:44359](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44359)

___

### ImportLandscape\_HeightmapErrorMessage

• **ImportLandscape\_HeightmapErrorMessage**: `string`

#### Defined in

[ue/ue.d.ts:44356](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44356)

___

### ImportLandscape\_HeightmapFilename

• **ImportLandscape\_HeightmapFilename**: `string`

#### Defined in

[ue/ue.d.ts:44357](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44357)

___

### ImportLandscape\_HeightmapImportResult

• **ImportLandscape\_HeightmapImportResult**: [`ELandscapeImportResult`](../enums/ue_ue.ELandscapeImportResult.md)

#### Defined in

[ue/ue.d.ts:44355](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44355)

___

### ImportLandscape\_Layers

• **ImportLandscape\_Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeImportLayer`](ue_ue.LandscapeImportLayer.md)\>

#### Defined in

[ue/ue.d.ts:44363](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44363)

___

### ImportLandscape\_Width

• **ImportLandscape\_Width**: `number`

#### Defined in

[ue/ue.d.ts:44358](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44358)

___

### MaximumValueRadius

• **MaximumValueRadius**: `number`

#### Defined in

[ue/ue.d.ts:44300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44300)

___

### MirrorOp

• **MirrorOp**: [`ELandscapeMirrorOperation`](../enums/ue_ue.ELandscapeMirrorOperation.md)

#### Defined in

[ue/ue.d.ts:44341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44341)

___

### MirrorPoint

• **MirrorPoint**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:44340](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44340)

___

### MirrorSmoothingWidth

• **MirrorSmoothingWidth**: `number`

#### Defined in

[ue/ue.d.ts:44342](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44342)

___

### NewLandscape\_ComponentCount

• **NewLandscape\_ComponentCount**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:44351](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44351)

___

### NewLandscape\_Location

• **NewLandscape\_Location**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:44352](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44352)

___

### NewLandscape\_Material

• **NewLandscape\_Material**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Defined in

[ue/ue.d.ts:44348](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44348)

___

### NewLandscape\_QuadsPerSection

• **NewLandscape\_QuadsPerSection**: `number`

#### Defined in

[ue/ue.d.ts:44349](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44349)

___

### NewLandscape\_Rotation

• **NewLandscape\_Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:44353](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44353)

___

### NewLandscape\_Scale

• **NewLandscape\_Scale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:44354](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44354)

___

### NewLandscape\_SectionsPerComponent

• **NewLandscape\_SectionsPerComponent**: `number`

#### Defined in

[ue/ue.d.ts:44350](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44350)

___

### NoiseMode

• **NoiseMode**: [`ELandscapeToolNoiseMode`](../enums/ue_ue.ELandscapeToolNoiseMode.md)

#### Defined in

[ue/ue.d.ts:44329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44329)

___

### NoiseScale

• **NoiseScale**: `number`

#### Defined in

[ue/ue.d.ts:44330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44330)

___

### PaintingRestriction

• **PaintingRestriction**: [`ELandscapeLayerPaintingRestriction`](../enums/ue_ue.ELandscapeLayerPaintingRestriction.md)

#### Defined in

[ue/ue.d.ts:44380](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44380)

___

### PasteMode

• **PasteMode**: [`ELandscapeToolPasteMode`](../enums/ue_ue.ELandscapeToolPasteMode.md)

#### Defined in

[ue/ue.d.ts:44333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44333)

___

### RainAmount

• **RainAmount**: `number`

#### Defined in

[ue/ue.d.ts:44322](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44322)

___

### RainDistMode

• **RainDistMode**: [`ELandscapeToolHydroErosionMode`](../enums/ue_ue.ELandscapeToolHydroErosionMode.md)

#### Defined in

[ue/ue.d.ts:44325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44325)

___

### RainDistScale

• **RainDistScale**: `number`

#### Defined in

[ue/ue.d.ts:44326](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44326)

___

### RampSideFalloff

• **RampSideFalloff**: `number`

#### Defined in

[ue/ue.d.ts:44313](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44313)

___

### RampWidth

• **RampWidth**: `number`

#### Defined in

[ue/ue.d.ts:44312](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44312)

___

### ResizeLandscape\_ComponentCount

• **ResizeLandscape\_ComponentCount**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:44346](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44346)

___

### ResizeLandscape\_ConvertMode

• **ResizeLandscape\_ConvertMode**: [`ELandscapeConvertMode`](../enums/ue_ue.ELandscapeConvertMode.md)

#### Defined in

[ue/ue.d.ts:44347](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44347)

___

### ResizeLandscape\_QuadsPerSection

• **ResizeLandscape\_QuadsPerSection**: `number`

#### Defined in

[ue/ue.d.ts:44344](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44344)

___

### ResizeLandscape\_SectionsPerComponent

• **ResizeLandscape\_SectionsPerComponent**: `number`

#### Defined in

[ue/ue.d.ts:44345](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44345)

___

### SedimentCapacity

• **SedimentCapacity**: `number`

#### Defined in

[ue/ue.d.ts:44323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44323)

___

### ShowUnusedLayers

• **ShowUnusedLayers**: `boolean`

#### Defined in

[ue/ue.d.ts:44382](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44382)

___

### SmoothFilterKernelSize

• **SmoothFilterKernelSize**: `number`

#### Defined in

[ue/ue.d.ts:44314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44314)

___

### TargetDisplayOrder

• **TargetDisplayOrder**: [`ELandscapeLayerDisplayMode`](../enums/ue_ue.ELandscapeLayerDisplayMode.md)

#### Defined in

[ue/ue.d.ts:44381](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44381)

___

### TerraceInterval

• **TerraceInterval**: `number`

#### Defined in

[ue/ue.d.ts:44308](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44308)

___

### TerraceSmooth

• **TerraceSmooth**: `number`

#### Defined in

[ue/ue.d.ts:44309](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44309)

___

### ToolStrength

• **ToolStrength**: `number`

#### Defined in

[ue/ue.d.ts:44297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44297)

___

### WeightTargetValue

• **WeightTargetValue**: `number`

#### Defined in

[ue/ue.d.ts:44299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44299)

___

### WorldSpacePatternBrushSettings

• **WorldSpacePatternBrushSettings**: [`LandscapePatternBrushWorldSpaceSettings`](ue_ue.LandscapePatternBrushWorldSpaceSettings.md)

#### Defined in

[ue/ue.d.ts:44373](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44373)

___

### \_\_tid\_LandscapeEditorObject\_\_

• **\_\_tid\_LandscapeEditorObject\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:44388](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44388)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bAlphaBrushAutoRotate

• **bAlphaBrushAutoRotate**: `boolean`

#### Defined in

[ue/ue.d.ts:44368](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44368)

___

### bApplyToAllTargets

• **bApplyToAllTargets**: `boolean`

#### Defined in

[ue/ue.d.ts:44334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44334)

___

### bCanHaveLayersContent

• **bCanHaveLayersContent**: `boolean`

#### Defined in

[ue/ue.d.ts:44361](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44361)

___

### bCombinedLayersOperation

• **bCombinedLayersOperation**: `boolean`

#### Defined in

[ue/ue.d.ts:44301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44301)

___

### bDetailSmooth

• **bDetailSmooth**: `boolean`

#### Defined in

[ue/ue.d.ts:44315](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44315)

___

### bFlattenEyeDropperModeActivated

• **bFlattenEyeDropperModeActivated**: `boolean`

#### Defined in

[ue/ue.d.ts:44310](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44310)

___

### bHErosionDetailSmooth

• **bHErosionDetailSmooth**: `boolean`

#### Defined in

[ue/ue.d.ts:44327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44327)

___

### bPickValuePerApply

• **bPickValuePerApply**: `boolean`

#### Defined in

[ue/ue.d.ts:44304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44304)

___

### bShowFlattenTargetPreview

• **bShowFlattenTargetPreview**: `boolean`

#### Defined in

[ue/ue.d.ts:44307](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44307)

___

### bSmoothGizmoBrush

• **bSmoothGizmoBrush**: `boolean`

#### Defined in

[ue/ue.d.ts:44336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44336)

___

### bSnapGizmo

• **bSnapGizmo**: `boolean`

#### Defined in

[ue/ue.d.ts:44335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44335)

___

### bUseClayBrush

• **bUseClayBrush**: `boolean`

#### Defined in

[ue/ue.d.ts:44366](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44366)

___

### bUseFlattenTarget

• **bUseFlattenTarget**: `boolean`

#### Defined in

[ue/ue.d.ts:44305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44305)

___

### bUseNegativeMask

• **bUseNegativeMask**: `boolean`

#### Defined in

[ue/ue.d.ts:44332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44332)

___

### bUseSelectedRegion

• **bUseSelectedRegion**: `boolean`

#### Defined in

[ue/ue.d.ts:44331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44331)

___

### bUseSlopeFlatten

• **bUseSlopeFlatten**: `boolean`

#### Defined in

[ue/ue.d.ts:44303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44303)

___

### bUseWeightTargetValue

• **bUseWeightTargetValue**: `boolean`

#### Defined in

[ue/ue.d.ts:44298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44298)

___

### bUseWorldSpacePatternBrush

• **bUseWorldSpacePatternBrush**: `boolean`

#### Defined in

[ue/ue.d.ts:44372](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44372)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:44385](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44385)

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

#### Defined in

[ue/ue.d.ts:44386](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44386)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:44384](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44384)
