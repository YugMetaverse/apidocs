[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / RendererSettings

# Class: RendererSettings

[ue/ue](../modules/ue_ue.md).RendererSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`RendererSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.RendererSettings.md#constructor)

### Properties

- [ClearSceneMethod](ue_ue.RendererSettings.md#clearscenemethod)
- [CustomDepthStencil](ue_ue.RendererSettings.md#customdepthstencil)
- [DefaultBackBufferPixelFormat](ue_ue.RendererSettings.md#defaultbackbufferpixelformat)
- [DefaultFeatureAntiAliasing](ue_ue.RendererSettings.md#defaultfeatureantialiasing)
- [DefaultFeatureAutoExposure](ue_ue.RendererSettings.md#defaultfeatureautoexposure)
- [DefaultLightUnits](ue_ue.RendererSettings.md#defaultlightunits)
- [EarlyZPass](ue_ue.RendererSettings.md#earlyzpass)
- [GBufferFormat](ue_ue.RendererSettings.md#gbufferformat)
- [GPUSimulationTextureSizeX](ue_ue.RendererSettings.md#gpusimulationtexturesizex)
- [GPUSimulationTextureSizeY](ue_ue.RendererSettings.md#gpusimulationtexturesizey)
- [MaxMobileCascades](ue_ue.RendererSettings.md#maxmobilecascades)
- [MinScreenRadiusForCSMdepth](ue_ue.RendererSettings.md#minscreenradiusforcsmdepth)
- [MinScreenRadiusForEarlyZPass](ue_ue.RendererSettings.md#minscreenradiusforearlyzpass)
- [MinScreenRadiusForLights](ue_ue.RendererSettings.md#minscreenradiusforlights)
- [MobileMSAASampleCount](ue_ue.RendererSettings.md#mobilemsaasamplecount)
- [MobileNumDynamicPointLights](ue_ue.RendererSettings.md#mobilenumdynamicpointlights)
- [ReflectionCaptureResolution](ue_ue.RendererSettings.md#reflectioncaptureresolution)
- [ReflectionEnvironmentLightmapMixBasedOnRoughness](ue_ue.RendererSettings.md#reflectionenvironmentlightmapmixbasedonroughness)
- [SkinCacheSceneMemoryLimitInMB](ue_ue.RendererSettings.md#skincachescenememorylimitinmb)
- [TessellationAdaptivePixelsPerTriangle](ue_ue.RendererSettings.md#tessellationadaptivepixelspertriangle)
- [TranslucentSortAxis](ue_ue.RendererSettings.md#translucentsortaxis)
- [TranslucentSortPolicy](ue_ue.RendererSettings.md#translucentsortpolicy)
- [VirtualTextureFeedbackFactor](ue_ue.RendererSettings.md#virtualtexturefeedbackfactor)
- [VirtualTextureTileBorderSize](ue_ue.RendererSettings.md#virtualtexturetilebordersize)
- [VirtualTextureTileSize](ue_ue.RendererSettings.md#virtualtexturetilesize)
- [WireframeCullThreshold](ue_ue.RendererSettings.md#wireframecullthreshold)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.RendererSettings.md#__tid_developersettings__)
- [\_\_tid\_Object\_\_](ue_ue.RendererSettings.md#__tid_object__)
- [\_\_tid\_RendererSettings\_\_](ue_ue.RendererSettings.md#__tid_renderersettings__)
- [bAllowStaticLighting](ue_ue.RendererSettings.md#ballowstaticlighting)
- [bBasePassOutputsVelocity](ue_ue.RendererSettings.md#bbasepassoutputsvelocity)
- [bClearCoatEnableSecondNormal](ue_ue.RendererSettings.md#bclearcoatenablesecondnormal)
- [bCompressMeshDistanceFields](ue_ue.RendererSettings.md#bcompressmeshdistancefields)
- [bCustomDepthTaaJitter](ue_ue.RendererSettings.md#bcustomdepthtaajitter)
- [bDBuffer](ue_ue.RendererSettings.md#bdbuffer)
- [bDefaultFeatureAmbientOcclusion](ue_ue.RendererSettings.md#bdefaultfeatureambientocclusion)
- [bDefaultFeatureAmbientOcclusionStaticFraction](ue_ue.RendererSettings.md#bdefaultfeatureambientocclusionstaticfraction)
- [bDefaultFeatureAutoExposure](ue_ue.RendererSettings.md#bdefaultfeatureautoexposure)
- [bDefaultFeatureBloom](ue_ue.RendererSettings.md#bdefaultfeaturebloom)
- [bDefaultFeatureLensFlare](ue_ue.RendererSettings.md#bdefaultfeaturelensflare)
- [bDefaultFeatureMotionBlur](ue_ue.RendererSettings.md#bdefaultfeaturemotionblur)
- [bDefaultParticleCutouts](ue_ue.RendererSettings.md#bdefaultparticlecutouts)
- [bDiscardUnusedQualityLevels](ue_ue.RendererSettings.md#bdiscardunusedqualitylevels)
- [bEarlyZPassOnlyMaterialMasking](ue_ue.RendererSettings.md#bearlyzpassonlymaterialmasking)
- [bEightBitMeshDistanceFields](ue_ue.RendererSettings.md#beightbitmeshdistancefields)
- [bEnableAlphaChannelInPostProcessing](ue_ue.RendererSettings.md#benablealphachannelinpostprocessing)
- [bEnablePreExposureOnlyInTheEditor](ue_ue.RendererSettings.md#benablepreexposureonlyintheeditor)
- [bEnableRayTracing](ue_ue.RendererSettings.md#benableraytracing)
- [bEnableRayTracingTextureLOD](ue_ue.RendererSettings.md#benableraytracingtexturelod)
- [bExtendDefaultLuminanceRangeInAutoExposureSettings](ue_ue.RendererSettings.md#bextenddefaultluminancerangeinautoexposuresettings)
- [bForwardShading](ue_ue.RendererSettings.md#bforwardshading)
- [bGPUSkinLimit2BoneInfluences](ue_ue.RendererSettings.md#bgpuskinlimit2boneinfluences)
- [bGenerateLandscapeGIData](ue_ue.RendererSettings.md#bgeneratelandscapegidata)
- [bGenerateMeshDistanceFields](ue_ue.RendererSettings.md#bgeneratemeshdistancefields)
- [bGlobalClipPlane](ue_ue.RendererSettings.md#bglobalclipplane)
- [bInstancedStereo](ue_ue.RendererSettings.md#binstancedstereo)
- [bLPV](ue_ue.RendererSettings.md#blpv)
- [bMobileAllowDistanceFieldShadows](ue_ue.RendererSettings.md#bmobileallowdistancefieldshadows)
- [bMobileAllowDitheredLODTransition](ue_ue.RendererSettings.md#bmobileallowditheredlodtransition)
- [bMobileAllowMovableDirectionalLights](ue_ue.RendererSettings.md#bmobileallowmovabledirectionallights)
- [bMobileAllowMovableSpotlights](ue_ue.RendererSettings.md#bmobileallowmovablespotlights)
- [bMobileAllowSoftwareOcclusionCulling](ue_ue.RendererSettings.md#bmobileallowsoftwareocclusionculling)
- [bMobileDisableVertexFog](ue_ue.RendererSettings.md#bmobiledisablevertexfog)
- [bMobileDynamicPointLightsUseStaticBranch](ue_ue.RendererSettings.md#bmobiledynamicpointlightsusestaticbranch)
- [bMobileEnableMovableLightCSMShaderCulling](ue_ue.RendererSettings.md#bmobileenablemovablelightcsmshaderculling)
- [bMobileEnableStaticAndCSMShadowReceivers](ue_ue.RendererSettings.md#bmobileenablestaticandcsmshadowreceivers)
- [bMobileHDR](ue_ue.RendererSettings.md#bmobilehdr)
- [bMobileMultiView](ue_ue.RendererSettings.md#bmobilemultiview)
- [bMobileMultiViewDirect](ue_ue.RendererSettings.md#bmobilemultiviewdirect)
- [bMobileUseHWsRGBEncoding](ue_ue.RendererSettings.md#bmobileusehwsrgbencoding)
- [bMobileUseLegacyShadingModel](ue_ue.RendererSettings.md#bmobileuselegacyshadingmodel)
- [bMultiView](ue_ue.RendererSettings.md#bmultiview)
- [bNvidiaAftermathEnabled](ue_ue.RendererSettings.md#bnvidiaaftermathenabled)
- [bODSCapture](ue_ue.RendererSettings.md#bodscapture)
- [bOcclusionCulling](ue_ue.RendererSettings.md#bocclusionculling)
- [bPrecomputedVisibilityWarning](ue_ue.RendererSettings.md#bprecomputedvisibilitywarning)
- [bRenderUnbuiltPreviewShadowsInGame](ue_ue.RendererSettings.md#brenderunbuiltpreviewshadowsingame)
- [bRoundRobinOcclusion](ue_ue.RendererSettings.md#broundrobinocclusion)
- [bSSGI](ue_ue.RendererSettings.md#bssgi)
- [bSelectiveBasePassOutputs](ue_ue.RendererSettings.md#bselectivebasepassoutputs)
- [bSeparateTranslucency](ue_ue.RendererSettings.md#bseparatetranslucency)
- [bStencilForLODDither](ue_ue.RendererSettings.md#bstencilforloddither)
- [bSupportAtmosphericFog](ue_ue.RendererSettings.md#bsupportatmosphericfog)
- [bSupportDepthOnlyIndexBuffers](ue_ue.RendererSettings.md#bsupportdepthonlyindexbuffers)
- [bSupportLowQualityLightmaps](ue_ue.RendererSettings.md#bsupportlowqualitylightmaps)
- [bSupportMaterialLayers](ue_ue.RendererSettings.md#bsupportmateriallayers)
- [bSupportPointLightWholeSceneShadows](ue_ue.RendererSettings.md#bsupportpointlightwholesceneshadows)
- [bSupportReversedIndexBuffers](ue_ue.RendererSettings.md#bsupportreversedindexbuffers)
- [bSupportSkinCacheShaders](ue_ue.RendererSettings.md#bsupportskincacheshaders)
- [bSupportSkyAtmosphere](ue_ue.RendererSettings.md#bsupportskyatmosphere)
- [bSupportSkyAtmosphereAffectsHeightFog](ue_ue.RendererSettings.md#bsupportskyatmosphereaffectsheightfog)
- [bSupportStationarySkylight](ue_ue.RendererSettings.md#bsupportstationaryskylight)
- [bTemporalUpsampling](ue_ue.RendererSettings.md#btemporalupsampling)
- [bTextureStreaming](ue_ue.RendererSettings.md#btexturestreaming)
- [bUseDXT5NormalMaps](ue_ue.RendererSettings.md#busedxt5normalmaps)
- [bUseGPUMorphTargets](ue_ue.RendererSettings.md#busegpumorphtargets)
- [bUseNormalMapsForStaticLighting](ue_ue.RendererSettings.md#busenormalmapsforstaticlighting)
- [bUsePreExposure](ue_ue.RendererSettings.md#busepreexposure)
- [bVertexFoggingForOpaque](ue_ue.RendererSettings.md#bvertexfoggingforopaque)
- [bVirtualTextureEnableCompressCrunch](ue_ue.RendererSettings.md#bvirtualtextureenablecompresscrunch)
- [bVirtualTextureEnableCompressZlib](ue_ue.RendererSettings.md#bvirtualtextureenablecompresszlib)
- [bVirtualTexturedLightmaps](ue_ue.RendererSettings.md#bvirtualtexturedlightmaps)
- [bVirtualTextures](ue_ue.RendererSettings.md#bvirtualtextures)

### Methods

- [CreateDefaultSubobject](ue_ue.RendererSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.RendererSettings.md#executeubergraph)
- [GetClass](ue_ue.RendererSettings.md#getclass)
- [GetName](ue_ue.RendererSettings.md#getname)
- [GetOuter](ue_ue.RendererSettings.md#getouter)
- [GetWorld](ue_ue.RendererSettings.md#getworld)
- [Find](ue_ue.RendererSettings.md#find)
- [Load](ue_ue.RendererSettings.md#load)
- [StaticClass](ue_ue.RendererSettings.md#staticclass)

## Constructors

### constructor

• **new RendererSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

#### Defined in

[ue/ue.d.ts:59444](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59444)

## Properties

### ClearSceneMethod

• **ClearSceneMethod**: [`EClearSceneOptions`](../enums/ue_ue.EClearSceneOptions.md)

#### Defined in

[ue/ue.d.ts:59506](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59506)

___

### CustomDepthStencil

• **CustomDepthStencil**: [`ECustomDepthStencil`](../enums/ue_ue.ECustomDepthStencil.md)

#### Defined in

[ue/ue.d.ts:59483](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59483)

___

### DefaultBackBufferPixelFormat

• **DefaultBackBufferPixelFormat**: [`EDefaultBackBufferPixelFormat`](../enums/ue_ue.EDefaultBackBufferPixelFormat.md)

#### Defined in

[ue/ue.d.ts:59500](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59500)

___

### DefaultFeatureAntiAliasing

• **DefaultFeatureAntiAliasing**: [`EAntiAliasingMethod`](../enums/ue_ue.EAntiAliasingMethod.md)

#### Defined in

[ue/ue.d.ts:59498](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59498)

___

### DefaultFeatureAutoExposure

• **DefaultFeatureAutoExposure**: [`EAutoExposureMethodUI`](../enums/ue_ue.EAutoExposureMethodUI.md)

#### Defined in

[ue/ue.d.ts:59490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59490)

___

### DefaultLightUnits

• **DefaultLightUnits**: [`ELightUnits`](../enums/ue_ue.ELightUnits.md)

#### Defined in

[ue/ue.d.ts:59499](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59499)

___

### EarlyZPass

• **EarlyZPass**: [`EEarlyZPass`](../enums/ue_ue.EEarlyZPass.md)

#### Defined in

[ue/ue.d.ts:59503](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59503)

___

### GBufferFormat

• **GBufferFormat**: [`EGBufferFormat`](../enums/ue_ue.EGBufferFormat.md)

#### Defined in

[ue/ue.d.ts:59513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59513)

___

### GPUSimulationTextureSizeX

• **GPUSimulationTextureSizeX**: `number`

#### Defined in

[ue/ue.d.ts:59510](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59510)

___

### GPUSimulationTextureSizeY

• **GPUSimulationTextureSizeY**: `number`

#### Defined in

[ue/ue.d.ts:59511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59511)

___

### MaxMobileCascades

• **MaxMobileCascades**: `number`

#### Defined in

[ue/ue.d.ts:59447](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59447)

___

### MinScreenRadiusForCSMdepth

• **MinScreenRadiusForCSMdepth**: `number`

#### Defined in

[ue/ue.d.ts:59457](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59457)

___

### MinScreenRadiusForEarlyZPass

• **MinScreenRadiusForEarlyZPass**: `number`

#### Defined in

[ue/ue.d.ts:59456](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59456)

___

### MinScreenRadiusForLights

• **MinScreenRadiusForLights**: `number`

#### Defined in

[ue/ue.d.ts:59455](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59455)

___

### MobileMSAASampleCount

• **MobileMSAASampleCount**: [`EMobileMSAASampleCount`](../enums/ue_ue.EMobileMSAASampleCount.md)

#### Defined in

[ue/ue.d.ts:59448](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59448)

___

### MobileNumDynamicPointLights

• **MobileNumDynamicPointLights**: `number`

#### Defined in

[ue/ue.d.ts:59536](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59536)

___

### ReflectionCaptureResolution

• **ReflectionCaptureResolution**: `number`

#### Defined in

[ue/ue.d.ts:59469](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59469)

___

### ReflectionEnvironmentLightmapMixBasedOnRoughness

• **ReflectionEnvironmentLightmapMixBasedOnRoughness**: `boolean`

#### Defined in

[ue/ue.d.ts:59470](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59470)

___

### SkinCacheSceneMemoryLimitInMB

• **SkinCacheSceneMemoryLimitInMB**: `number`

#### Defined in

[ue/ue.d.ts:59539](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59539)

___

### TessellationAdaptivePixelsPerTriangle

• **TessellationAdaptivePixelsPerTriangle**: `number`

#### Defined in

[ue/ue.d.ts:59479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59479)

___

### TranslucentSortAxis

• **TranslucentSortAxis**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:59482](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59482)

___

### TranslucentSortPolicy

• **TranslucentSortPolicy**: [`ETranslucentSortPolicy`](../enums/ue_ue.ETranslucentSortPolicy.md)

#### Defined in

[ue/ue.d.ts:59481](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59481)

___

### VirtualTextureFeedbackFactor

• **VirtualTextureFeedbackFactor**: `number`

#### Defined in

[ue/ue.d.ts:59465](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59465)

___

### VirtualTextureTileBorderSize

• **VirtualTextureTileBorderSize**: `number`

#### Defined in

[ue/ue.d.ts:59464](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59464)

___

### VirtualTextureTileSize

• **VirtualTextureTileSize**: `number`

#### Defined in

[ue/ue.d.ts:59463](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59463)

___

### WireframeCullThreshold

• **WireframeCullThreshold**: `number`

#### Defined in

[ue/ue.d.ts:59522](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59522)

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

#### Defined in

[ue/ue.d.ts:16950](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16950)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_RendererSettings\_\_

• **\_\_tid\_RendererSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:59549](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59549)

___

### bAllowStaticLighting

• **bAllowStaticLighting**: `boolean`

#### Defined in

[ue/ue.d.ts:59473](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59473)

___

### bBasePassOutputsVelocity

• **bBasePassOutputsVelocity**: `boolean`

#### Defined in

[ue/ue.d.ts:59507](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59507)

___

### bClearCoatEnableSecondNormal

• **bClearCoatEnableSecondNormal**: `boolean`

#### Defined in

[ue/ue.d.ts:59468](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59468)

___

### bCompressMeshDistanceFields

• **bCompressMeshDistanceFields**: `boolean`

#### Defined in

[ue/ue.d.ts:59478](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59478)

___

### bCustomDepthTaaJitter

• **bCustomDepthTaaJitter**: `boolean`

#### Defined in

[ue/ue.d.ts:59484](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59484)

___

### bDBuffer

• **bDBuffer**: `boolean`

#### Defined in

[ue/ue.d.ts:59505](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59505)

___

### bDefaultFeatureAmbientOcclusion

• **bDefaultFeatureAmbientOcclusion**: `boolean`

#### Defined in

[ue/ue.d.ts:59487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59487)

___

### bDefaultFeatureAmbientOcclusionStaticFraction

• **bDefaultFeatureAmbientOcclusionStaticFraction**: `boolean`

#### Defined in

[ue/ue.d.ts:59488](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59488)

___

### bDefaultFeatureAutoExposure

• **bDefaultFeatureAutoExposure**: `boolean`

#### Defined in

[ue/ue.d.ts:59489](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59489)

___

### bDefaultFeatureBloom

• **bDefaultFeatureBloom**: `boolean`

#### Defined in

[ue/ue.d.ts:59486](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59486)

___

### bDefaultFeatureLensFlare

• **bDefaultFeatureLensFlare**: `boolean`

#### Defined in

[ue/ue.d.ts:59495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59495)

___

### bDefaultFeatureMotionBlur

• **bDefaultFeatureMotionBlur**: `boolean`

#### Defined in

[ue/ue.d.ts:59494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59494)

___

### bDefaultParticleCutouts

• **bDefaultParticleCutouts**: `boolean`

#### Defined in

[ue/ue.d.ts:59509](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59509)

___

### bDiscardUnusedQualityLevels

• **bDiscardUnusedQualityLevels**: `boolean`

#### Defined in

[ue/ue.d.ts:59453](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59453)

___

### bEarlyZPassOnlyMaterialMasking

• **bEarlyZPassOnlyMaterialMasking**: `boolean`

#### Defined in

[ue/ue.d.ts:59504](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59504)

___

### bEightBitMeshDistanceFields

• **bEightBitMeshDistanceFields**: `boolean`

#### Defined in

[ue/ue.d.ts:59476](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59476)

___

### bEnableAlphaChannelInPostProcessing

• **bEnableAlphaChannelInPostProcessing**: [`EAlphaChannelMode`](../enums/ue_ue.EAlphaChannelMode.md)

#### Defined in

[ue/ue.d.ts:59485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59485)

___

### bEnablePreExposureOnlyInTheEditor

• **bEnablePreExposureOnlyInTheEditor**: `boolean`

#### Defined in

[ue/ue.d.ts:59493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59493)

___

### bEnableRayTracing

• **bEnableRayTracing**: `boolean`

#### Defined in

[ue/ue.d.ts:59523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59523)

___

### bEnableRayTracingTextureLOD

• **bEnableRayTracingTextureLOD**: `boolean`

#### Defined in

[ue/ue.d.ts:59524](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59524)

___

### bExtendDefaultLuminanceRangeInAutoExposureSettings

• **bExtendDefaultLuminanceRangeInAutoExposureSettings**: `boolean`

#### Defined in

[ue/ue.d.ts:59491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59491)

___

### bForwardShading

• **bForwardShading**: `boolean`

#### Defined in

[ue/ue.d.ts:59471](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59471)

___

### bGPUSkinLimit2BoneInfluences

• **bGPUSkinLimit2BoneInfluences**: `boolean`

#### Defined in

[ue/ue.d.ts:59540](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59540)

___

### bGenerateLandscapeGIData

• **bGenerateLandscapeGIData**: `boolean`

#### Defined in

[ue/ue.d.ts:59477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59477)

___

### bGenerateMeshDistanceFields

• **bGenerateMeshDistanceFields**: `boolean`

#### Defined in

[ue/ue.d.ts:59475](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59475)

___

### bGlobalClipPlane

• **bGlobalClipPlane**: `boolean`

#### Defined in

[ue/ue.d.ts:59512](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59512)

___

### bInstancedStereo

• **bInstancedStereo**: `boolean`

#### Defined in

[ue/ue.d.ts:59516](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59516)

___

### bLPV

• **bLPV**: `boolean`

#### Defined in

[ue/ue.d.ts:59544](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59544)

___

### bMobileAllowDistanceFieldShadows

• **bMobileAllowDistanceFieldShadows**: `boolean`

#### Defined in

[ue/ue.d.ts:59534](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59534)

___

### bMobileAllowDitheredLODTransition

• **bMobileAllowDitheredLODTransition**: `boolean`

#### Defined in

[ue/ue.d.ts:59451](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59451)

___

### bMobileAllowMovableDirectionalLights

• **bMobileAllowMovableDirectionalLights**: `boolean`

#### Defined in

[ue/ue.d.ts:59535](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59535)

___

### bMobileAllowMovableSpotlights

• **bMobileAllowMovableSpotlights**: `boolean`

#### Defined in

[ue/ue.d.ts:59538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59538)

___

### bMobileAllowSoftwareOcclusionCulling

• **bMobileAllowSoftwareOcclusionCulling**: `boolean`

#### Defined in

[ue/ue.d.ts:59452](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59452)

___

### bMobileDisableVertexFog

• **bMobileDisableVertexFog**: `boolean`

#### Defined in

[ue/ue.d.ts:59446](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59446)

___

### bMobileDynamicPointLightsUseStaticBranch

• **bMobileDynamicPointLightsUseStaticBranch**: `boolean`

#### Defined in

[ue/ue.d.ts:59537](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59537)

___

### bMobileEnableMovableLightCSMShaderCulling

• **bMobileEnableMovableLightCSMShaderCulling**: `boolean`

#### Defined in

[ue/ue.d.ts:59533](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59533)

___

### bMobileEnableStaticAndCSMShadowReceivers

• **bMobileEnableStaticAndCSMShadowReceivers**: `boolean`

#### Defined in

[ue/ue.d.ts:59532](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59532)

___

### bMobileHDR

• **bMobileHDR**: `boolean`

#### Defined in

[ue/ue.d.ts:59445](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59445)

___

### bMobileMultiView

• **bMobileMultiView**: `boolean`

#### Defined in

[ue/ue.d.ts:59518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59518)

___

### bMobileMultiViewDirect

• **bMobileMultiViewDirect**: `boolean`

#### Defined in

[ue/ue.d.ts:59519](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59519)

___

### bMobileUseHWsRGBEncoding

• **bMobileUseHWsRGBEncoding**: `boolean`

#### Defined in

[ue/ue.d.ts:59450](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59450)

___

### bMobileUseLegacyShadingModel

• **bMobileUseLegacyShadingModel**: `boolean`

#### Defined in

[ue/ue.d.ts:59449](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59449)

___

### bMultiView

• **bMultiView**: `boolean`

#### Defined in

[ue/ue.d.ts:59517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59517)

___

### bNvidiaAftermathEnabled

• **bNvidiaAftermathEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:59515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59515)

___

### bODSCapture

• **bODSCapture**: `boolean`

#### Defined in

[ue/ue.d.ts:59521](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59521)

___

### bOcclusionCulling

• **bOcclusionCulling**: `boolean`

#### Defined in

[ue/ue.d.ts:59454](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59454)

___

### bPrecomputedVisibilityWarning

• **bPrecomputedVisibilityWarning**: `boolean`

#### Defined in

[ue/ue.d.ts:59458](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59458)

___

### bRenderUnbuiltPreviewShadowsInGame

• **bRenderUnbuiltPreviewShadowsInGame**: `boolean`

#### Defined in

[ue/ue.d.ts:59501](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59501)

___

### bRoundRobinOcclusion

• **bRoundRobinOcclusion**: `boolean`

#### Defined in

[ue/ue.d.ts:59520](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59520)

___

### bSSGI

• **bSSGI**: `boolean`

#### Defined in

[ue/ue.d.ts:59497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59497)

___

### bSelectiveBasePassOutputs

• **bSelectiveBasePassOutputs**: `boolean`

#### Defined in

[ue/ue.d.ts:59508](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59508)

___

### bSeparateTranslucency

• **bSeparateTranslucency**: `boolean`

#### Defined in

[ue/ue.d.ts:59480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59480)

___

### bStencilForLODDither

• **bStencilForLODDither**: `boolean`

#### Defined in

[ue/ue.d.ts:59502](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59502)

___

### bSupportAtmosphericFog

• **bSupportAtmosphericFog**: `boolean`

#### Defined in

[ue/ue.d.ts:59528](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59528)

___

### bSupportDepthOnlyIndexBuffers

• **bSupportDepthOnlyIndexBuffers**: `boolean`

#### Defined in

[ue/ue.d.ts:59541](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59541)

___

### bSupportLowQualityLightmaps

• **bSupportLowQualityLightmaps**: `boolean`

#### Defined in

[ue/ue.d.ts:59526](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59526)

___

### bSupportMaterialLayers

• **bSupportMaterialLayers**: `boolean`

#### Defined in

[ue/ue.d.ts:59543](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59543)

___

### bSupportPointLightWholeSceneShadows

• **bSupportPointLightWholeSceneShadows**: `boolean`

#### Defined in

[ue/ue.d.ts:59527](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59527)

___

### bSupportReversedIndexBuffers

• **bSupportReversedIndexBuffers**: `boolean`

#### Defined in

[ue/ue.d.ts:59542](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59542)

___

### bSupportSkinCacheShaders

• **bSupportSkinCacheShaders**: `boolean`

#### Defined in

[ue/ue.d.ts:59531](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59531)

___

### bSupportSkyAtmosphere

• **bSupportSkyAtmosphere**: `boolean`

#### Defined in

[ue/ue.d.ts:59529](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59529)

___

### bSupportSkyAtmosphereAffectsHeightFog

• **bSupportSkyAtmosphereAffectsHeightFog**: `boolean`

#### Defined in

[ue/ue.d.ts:59530](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59530)

___

### bSupportStationarySkylight

• **bSupportStationarySkylight**: `boolean`

#### Defined in

[ue/ue.d.ts:59525](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59525)

___

### bTemporalUpsampling

• **bTemporalUpsampling**: `boolean`

#### Defined in

[ue/ue.d.ts:59496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59496)

___

### bTextureStreaming

• **bTextureStreaming**: `boolean`

#### Defined in

[ue/ue.d.ts:59459](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59459)

___

### bUseDXT5NormalMaps

• **bUseDXT5NormalMaps**: `boolean`

#### Defined in

[ue/ue.d.ts:59460](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59460)

___

### bUseGPUMorphTargets

• **bUseGPUMorphTargets**: `boolean`

#### Defined in

[ue/ue.d.ts:59514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59514)

___

### bUseNormalMapsForStaticLighting

• **bUseNormalMapsForStaticLighting**: `boolean`

#### Defined in

[ue/ue.d.ts:59474](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59474)

___

### bUsePreExposure

• **bUsePreExposure**: `boolean`

#### Defined in

[ue/ue.d.ts:59492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59492)

___

### bVertexFoggingForOpaque

• **bVertexFoggingForOpaque**: `boolean`

#### Defined in

[ue/ue.d.ts:59472](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59472)

___

### bVirtualTextureEnableCompressCrunch

• **bVirtualTextureEnableCompressCrunch**: `boolean`

#### Defined in

[ue/ue.d.ts:59467](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59467)

___

### bVirtualTextureEnableCompressZlib

• **bVirtualTextureEnableCompressZlib**: `boolean`

#### Defined in

[ue/ue.d.ts:59466](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59466)

___

### bVirtualTexturedLightmaps

• **bVirtualTexturedLightmaps**: `boolean`

#### Defined in

[ue/ue.d.ts:59462](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59462)

___

### bVirtualTextures

• **bVirtualTextures**: `boolean`

#### Defined in

[ue/ue.d.ts:59461](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59461)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[CreateDefaultSubobject](ue_ue.DeveloperSettings.md#createdefaultsubobject)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`RendererSettings`](ue_ue.RendererSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`RendererSettings`](ue_ue.RendererSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

#### Defined in

[ue/ue.d.ts:59546](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59546)

___

### Load

▸ `Static` **Load**(`InName`): [`RendererSettings`](ue_ue.RendererSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`RendererSettings`](ue_ue.RendererSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

#### Defined in

[ue/ue.d.ts:59547](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59547)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)

#### Defined in

[ue/ue.d.ts:59545](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59545)
