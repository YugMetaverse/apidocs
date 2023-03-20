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

## Properties

### ClearSceneMethod

• **ClearSceneMethod**: [`EClearSceneOptions`](../enums/ue_ue.EClearSceneOptions.md)

___

### CustomDepthStencil

• **CustomDepthStencil**: [`ECustomDepthStencil`](../enums/ue_ue.ECustomDepthStencil.md)

___

### DefaultBackBufferPixelFormat

• **DefaultBackBufferPixelFormat**: [`EDefaultBackBufferPixelFormat`](../enums/ue_ue.EDefaultBackBufferPixelFormat.md)

___

### DefaultFeatureAntiAliasing

• **DefaultFeatureAntiAliasing**: [`EAntiAliasingMethod`](../enums/ue_ue.EAntiAliasingMethod.md)

___

### DefaultFeatureAutoExposure

• **DefaultFeatureAutoExposure**: [`EAutoExposureMethodUI`](../enums/ue_ue.EAutoExposureMethodUI.md)

___

### DefaultLightUnits

• **DefaultLightUnits**: [`ELightUnits`](../enums/ue_ue.ELightUnits.md)

___

### EarlyZPass

• **EarlyZPass**: [`EEarlyZPass`](../enums/ue_ue.EEarlyZPass.md)

___

### GBufferFormat

• **GBufferFormat**: [`EGBufferFormat`](../enums/ue_ue.EGBufferFormat.md)

___

### GPUSimulationTextureSizeX

• **GPUSimulationTextureSizeX**: `number`

___

### GPUSimulationTextureSizeY

• **GPUSimulationTextureSizeY**: `number`

___

### MaxMobileCascades

• **MaxMobileCascades**: `number`

___

### MinScreenRadiusForCSMdepth

• **MinScreenRadiusForCSMdepth**: `number`

___

### MinScreenRadiusForEarlyZPass

• **MinScreenRadiusForEarlyZPass**: `number`

___

### MinScreenRadiusForLights

• **MinScreenRadiusForLights**: `number`

___

### MobileMSAASampleCount

• **MobileMSAASampleCount**: [`EMobileMSAASampleCount`](../enums/ue_ue.EMobileMSAASampleCount.md)

___

### MobileNumDynamicPointLights

• **MobileNumDynamicPointLights**: `number`

___

### ReflectionCaptureResolution

• **ReflectionCaptureResolution**: `number`

___

### ReflectionEnvironmentLightmapMixBasedOnRoughness

• **ReflectionEnvironmentLightmapMixBasedOnRoughness**: `boolean`

___

### SkinCacheSceneMemoryLimitInMB

• **SkinCacheSceneMemoryLimitInMB**: `number`

___

### TessellationAdaptivePixelsPerTriangle

• **TessellationAdaptivePixelsPerTriangle**: `number`

___

### TranslucentSortAxis

• **TranslucentSortAxis**: [`Vector`](ue_ue_s.Vector.md)

___

### TranslucentSortPolicy

• **TranslucentSortPolicy**: [`ETranslucentSortPolicy`](../enums/ue_ue.ETranslucentSortPolicy.md)

___

### VirtualTextureFeedbackFactor

• **VirtualTextureFeedbackFactor**: `number`

___

### VirtualTextureTileBorderSize

• **VirtualTextureTileBorderSize**: `number`

___

### VirtualTextureTileSize

• **VirtualTextureTileSize**: `number`

___

### WireframeCullThreshold

• **WireframeCullThreshold**: `number`

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

___

### \_\_tid\_RendererSettings\_\_

• **\_\_tid\_RendererSettings\_\_**: `boolean`

___

### bAllowStaticLighting

• **bAllowStaticLighting**: `boolean`

___

### bBasePassOutputsVelocity

• **bBasePassOutputsVelocity**: `boolean`

___

### bClearCoatEnableSecondNormal

• **bClearCoatEnableSecondNormal**: `boolean`

___

### bCompressMeshDistanceFields

• **bCompressMeshDistanceFields**: `boolean`

___

### bCustomDepthTaaJitter

• **bCustomDepthTaaJitter**: `boolean`

___

### bDBuffer

• **bDBuffer**: `boolean`

___

### bDefaultFeatureAmbientOcclusion

• **bDefaultFeatureAmbientOcclusion**: `boolean`

___

### bDefaultFeatureAmbientOcclusionStaticFraction

• **bDefaultFeatureAmbientOcclusionStaticFraction**: `boolean`

___

### bDefaultFeatureAutoExposure

• **bDefaultFeatureAutoExposure**: `boolean`

___

### bDefaultFeatureBloom

• **bDefaultFeatureBloom**: `boolean`

___

### bDefaultFeatureLensFlare

• **bDefaultFeatureLensFlare**: `boolean`

___

### bDefaultFeatureMotionBlur

• **bDefaultFeatureMotionBlur**: `boolean`

___

### bDefaultParticleCutouts

• **bDefaultParticleCutouts**: `boolean`

___

### bDiscardUnusedQualityLevels

• **bDiscardUnusedQualityLevels**: `boolean`

___

### bEarlyZPassOnlyMaterialMasking

• **bEarlyZPassOnlyMaterialMasking**: `boolean`

___

### bEightBitMeshDistanceFields

• **bEightBitMeshDistanceFields**: `boolean`

___

### bEnableAlphaChannelInPostProcessing

• **bEnableAlphaChannelInPostProcessing**: [`EAlphaChannelMode`](../enums/ue_ue.EAlphaChannelMode.md)

___

### bEnablePreExposureOnlyInTheEditor

• **bEnablePreExposureOnlyInTheEditor**: `boolean`

___

### bEnableRayTracing

• **bEnableRayTracing**: `boolean`

___

### bEnableRayTracingTextureLOD

• **bEnableRayTracingTextureLOD**: `boolean`

___

### bExtendDefaultLuminanceRangeInAutoExposureSettings

• **bExtendDefaultLuminanceRangeInAutoExposureSettings**: `boolean`

___

### bForwardShading

• **bForwardShading**: `boolean`

___

### bGPUSkinLimit2BoneInfluences

• **bGPUSkinLimit2BoneInfluences**: `boolean`

___

### bGenerateLandscapeGIData

• **bGenerateLandscapeGIData**: `boolean`

___

### bGenerateMeshDistanceFields

• **bGenerateMeshDistanceFields**: `boolean`

___

### bGlobalClipPlane

• **bGlobalClipPlane**: `boolean`

___

### bInstancedStereo

• **bInstancedStereo**: `boolean`

___

### bLPV

• **bLPV**: `boolean`

___

### bMobileAllowDistanceFieldShadows

• **bMobileAllowDistanceFieldShadows**: `boolean`

___

### bMobileAllowDitheredLODTransition

• **bMobileAllowDitheredLODTransition**: `boolean`

___

### bMobileAllowMovableDirectionalLights

• **bMobileAllowMovableDirectionalLights**: `boolean`

___

### bMobileAllowMovableSpotlights

• **bMobileAllowMovableSpotlights**: `boolean`

___

### bMobileAllowSoftwareOcclusionCulling

• **bMobileAllowSoftwareOcclusionCulling**: `boolean`

___

### bMobileDisableVertexFog

• **bMobileDisableVertexFog**: `boolean`

___

### bMobileDynamicPointLightsUseStaticBranch

• **bMobileDynamicPointLightsUseStaticBranch**: `boolean`

___

### bMobileEnableMovableLightCSMShaderCulling

• **bMobileEnableMovableLightCSMShaderCulling**: `boolean`

___

### bMobileEnableStaticAndCSMShadowReceivers

• **bMobileEnableStaticAndCSMShadowReceivers**: `boolean`

___

### bMobileHDR

• **bMobileHDR**: `boolean`

___

### bMobileMultiView

• **bMobileMultiView**: `boolean`

___

### bMobileMultiViewDirect

• **bMobileMultiViewDirect**: `boolean`

___

### bMobileUseHWsRGBEncoding

• **bMobileUseHWsRGBEncoding**: `boolean`

___

### bMobileUseLegacyShadingModel

• **bMobileUseLegacyShadingModel**: `boolean`

___

### bMultiView

• **bMultiView**: `boolean`

___

### bNvidiaAftermathEnabled

• **bNvidiaAftermathEnabled**: `boolean`

___

### bODSCapture

• **bODSCapture**: `boolean`

___

### bOcclusionCulling

• **bOcclusionCulling**: `boolean`

___

### bPrecomputedVisibilityWarning

• **bPrecomputedVisibilityWarning**: `boolean`

___

### bRenderUnbuiltPreviewShadowsInGame

• **bRenderUnbuiltPreviewShadowsInGame**: `boolean`

___

### bRoundRobinOcclusion

• **bRoundRobinOcclusion**: `boolean`

___

### bSSGI

• **bSSGI**: `boolean`

___

### bSelectiveBasePassOutputs

• **bSelectiveBasePassOutputs**: `boolean`

___

### bSeparateTranslucency

• **bSeparateTranslucency**: `boolean`

___

### bStencilForLODDither

• **bStencilForLODDither**: `boolean`

___

### bSupportAtmosphericFog

• **bSupportAtmosphericFog**: `boolean`

___

### bSupportDepthOnlyIndexBuffers

• **bSupportDepthOnlyIndexBuffers**: `boolean`

___

### bSupportLowQualityLightmaps

• **bSupportLowQualityLightmaps**: `boolean`

___

### bSupportMaterialLayers

• **bSupportMaterialLayers**: `boolean`

___

### bSupportPointLightWholeSceneShadows

• **bSupportPointLightWholeSceneShadows**: `boolean`

___

### bSupportReversedIndexBuffers

• **bSupportReversedIndexBuffers**: `boolean`

___

### bSupportSkinCacheShaders

• **bSupportSkinCacheShaders**: `boolean`

___

### bSupportSkyAtmosphere

• **bSupportSkyAtmosphere**: `boolean`

___

### bSupportSkyAtmosphereAffectsHeightFog

• **bSupportSkyAtmosphereAffectsHeightFog**: `boolean`

___

### bSupportStationarySkylight

• **bSupportStationarySkylight**: `boolean`

___

### bTemporalUpsampling

• **bTemporalUpsampling**: `boolean`

___

### bTextureStreaming

• **bTextureStreaming**: `boolean`

___

### bUseDXT5NormalMaps

• **bUseDXT5NormalMaps**: `boolean`

___

### bUseGPUMorphTargets

• **bUseGPUMorphTargets**: `boolean`

___

### bUseNormalMapsForStaticLighting

• **bUseNormalMapsForStaticLighting**: `boolean`

___

### bUsePreExposure

• **bUsePreExposure**: `boolean`

___

### bVertexFoggingForOpaque

• **bVertexFoggingForOpaque**: `boolean`

___

### bVirtualTextureEnableCompressCrunch

• **bVirtualTextureEnableCompressCrunch**: `boolean`

___

### bVirtualTextureEnableCompressZlib

• **bVirtualTextureEnableCompressZlib**: `boolean`

___

### bVirtualTexturedLightmaps

• **bVirtualTexturedLightmaps**: `boolean`

___

### bVirtualTextures

• **bVirtualTextures**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
