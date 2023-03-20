[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PreviewMaterial

# Class: PreviewMaterial

[ue/ue](../modules/ue_ue.md).PreviewMaterial

## Hierarchy

- [`Material`](ue_ue.Material.md)

  ↳ **`PreviewMaterial`**

## Table of contents

### Constructors

- [constructor](ue_ue.PreviewMaterial.md#constructor)

### Properties

- [AllowTranslucentCustomDepthWrites](ue_ue.PreviewMaterial.md#allowtranslucentcustomdepthwrites)
- [AmbientOcclusion](ue_ue.PreviewMaterial.md#ambientocclusion)
- [AssetImportData](ue_ue.PreviewMaterial.md#assetimportdata)
- [AssetUserData](ue_ue.PreviewMaterial.md#assetuserdata)
- [BaseColor](ue_ue.PreviewMaterial.md#basecolor)
- [BlendMode](ue_ue.PreviewMaterial.md#blendmode)
- [BlendableLocation](ue_ue.PreviewMaterial.md#blendablelocation)
- [BlendableOutputAlpha](ue_ue.PreviewMaterial.md#blendableoutputalpha)
- [BlendablePriority](ue_ue.PreviewMaterial.md#blendablepriority)
- [CachedQualityLevelsUsed](ue_ue.PreviewMaterial.md#cachedqualitylevelsused)
- [ClearCoat](ue_ue.PreviewMaterial.md#clearcoat)
- [ClearCoatRoughness](ue_ue.PreviewMaterial.md#clearcoatroughness)
- [CustomizedUVs](ue_ue.PreviewMaterial.md#customizeduvs)
- [D3D11TessellationMode](ue_ue.PreviewMaterial.md#d3d11tessellationmode)
- [DecalBlendMode](ue_ue.PreviewMaterial.md#decalblendmode)
- [DiffuseColor](ue_ue.PreviewMaterial.md#diffusecolor)
- [DitherOpacityMask](ue_ue.PreviewMaterial.md#ditheropacitymask)
- [DitheredLODTransition](ue_ue.PreviewMaterial.md#ditheredlodtransition)
- [EditorComments](ue_ue.PreviewMaterial.md#editorcomments)
- [EditorPitch](ue_ue.PreviewMaterial.md#editorpitch)
- [EditorX](ue_ue.PreviewMaterial.md#editorx)
- [EditorY](ue_ue.PreviewMaterial.md#editory)
- [EditorYaw](ue_ue.PreviewMaterial.md#editoryaw)
- [EmissiveColor](ue_ue.PreviewMaterial.md#emissivecolor)
- [ExpressionTextureReferences](ue_ue.PreviewMaterial.md#expressiontexturereferences)
- [Expressions](ue_ue.PreviewMaterial.md#expressions)
- [LayerParameterExpansion](ue_ue.PreviewMaterial.md#layerparameterexpansion)
- [LightingGuid](ue_ue.PreviewMaterial.md#lightingguid)
- [LightmassSettings](ue_ue.PreviewMaterial.md#lightmasssettings)
- [MaterialAttributes](ue_ue.PreviewMaterial.md#materialattributes)
- [MaterialDecalResponse](ue_ue.PreviewMaterial.md#materialdecalresponse)
- [MaterialDomain](ue_ue.PreviewMaterial.md#materialdomain)
- [MaterialFunctionInfos](ue_ue.PreviewMaterial.md#materialfunctioninfos)
- [MaterialParameterCollectionInfos](ue_ue.PreviewMaterial.md#materialparametercollectioninfos)
- [MaxDisplacement](ue_ue.PreviewMaterial.md#maxdisplacement)
- [Metallic](ue_ue.PreviewMaterial.md#metallic)
- [Normal](ue_ue.PreviewMaterial.md#normal)
- [NumCustomizedUVs](ue_ue.PreviewMaterial.md#numcustomizeduvs)
- [Opacity](ue_ue.PreviewMaterial.md#opacity)
- [OpacityMask](ue_ue.PreviewMaterial.md#opacitymask)
- [OpacityMaskClipValue](ue_ue.PreviewMaterial.md#opacitymaskclipvalue)
- [ParameterGroupData](ue_ue.PreviewMaterial.md#parametergroupdata)
- [ParameterOverviewExpansion](ue_ue.PreviewMaterial.md#parameteroverviewexpansion)
- [PhysMaterial](ue_ue.PreviewMaterial.md#physmaterial)
- [PixelDepthOffset](ue_ue.PreviewMaterial.md#pixeldepthoffset)
- [PreviewMesh](ue_ue.PreviewMaterial.md#previewmesh)
- [ReferencedTextureGuids](ue_ue.PreviewMaterial.md#referencedtextureguids)
- [Refraction](ue_ue.PreviewMaterial.md#refraction)
- [RefractionDepthBias](ue_ue.PreviewMaterial.md#refractiondepthbias)
- [RefractionMode](ue_ue.PreviewMaterial.md#refractionmode)
- [Roughness](ue_ue.PreviewMaterial.md#roughness)
- [ShadingModel](ue_ue.PreviewMaterial.md#shadingmodel)
- [ShadingModelFromMaterialExpression](ue_ue.PreviewMaterial.md#shadingmodelfrommaterialexpression)
- [ShadingModels](ue_ue.PreviewMaterial.md#shadingmodels)
- [Specular](ue_ue.PreviewMaterial.md#specular)
- [SpecularColor](ue_ue.PreviewMaterial.md#specularcolor)
- [StateId](ue_ue.PreviewMaterial.md#stateid)
- [StencilCompare](ue_ue.PreviewMaterial.md#stencilcompare)
- [StencilRefValue](ue_ue.PreviewMaterial.md#stencilrefvalue)
- [SubsurfaceColor](ue_ue.PreviewMaterial.md#subsurfacecolor)
- [SubsurfaceProfile](ue_ue.PreviewMaterial.md#subsurfaceprofile)
- [TessellationMultiplier](ue_ue.PreviewMaterial.md#tessellationmultiplier)
- [TextureStreamingData](ue_ue.PreviewMaterial.md#texturestreamingdata)
- [TextureStreamingDataMissingEntries](ue_ue.PreviewMaterial.md#texturestreamingdatamissingentries)
- [TextureStreamingDataVersion](ue_ue.PreviewMaterial.md#texturestreamingdataversion)
- [ThumbnailInfo](ue_ue.PreviewMaterial.md#thumbnailinfo)
- [TranslucencyDirectionalLightingIntensity](ue_ue.PreviewMaterial.md#translucencydirectionallightingintensity)
- [TranslucencyLightingMode](ue_ue.PreviewMaterial.md#translucencylightingmode)
- [TranslucentBackscatteringExponent](ue_ue.PreviewMaterial.md#translucentbackscatteringexponent)
- [TranslucentMultipleScatteringExtinction](ue_ue.PreviewMaterial.md#translucentmultiplescatteringextinction)
- [TranslucentSelfShadowDensityScale](ue_ue.PreviewMaterial.md#translucentselfshadowdensityscale)
- [TranslucentSelfShadowSecondDensityScale](ue_ue.PreviewMaterial.md#translucentselfshadowseconddensityscale)
- [TranslucentSelfShadowSecondOpacity](ue_ue.PreviewMaterial.md#translucentselfshadowsecondopacity)
- [TranslucentShadowDensityScale](ue_ue.PreviewMaterial.md#translucentshadowdensityscale)
- [TranslucentShadowStartOffset](ue_ue.PreviewMaterial.md#translucentshadowstartoffset)
- [TwoSided](ue_ue.PreviewMaterial.md#twosided)
- [UsageFlagWarnings](ue_ue.PreviewMaterial.md#usageflagwarnings)
- [UsedShadingModels](ue_ue.PreviewMaterial.md#usedshadingmodels)
- [Wireframe](ue_ue.PreviewMaterial.md#wireframe)
- [WorldDisplacement](ue_ue.PreviewMaterial.md#worlddisplacement)
- [WorldPositionOffset](ue_ue.PreviewMaterial.md#worldpositionoffset)
- [\_\_tid\_MaterialInterface\_\_](ue_ue.PreviewMaterial.md#__tid_materialinterface__)
- [\_\_tid\_Material\_\_](ue_ue.PreviewMaterial.md#__tid_material__)
- [\_\_tid\_Object\_\_](ue_ue.PreviewMaterial.md#__tid_object__)
- [\_\_tid\_PreviewMaterial\_\_](ue_ue.PreviewMaterial.md#__tid_previewmaterial__)
- [bAllowDevelopmentShaderCompile](ue_ue.PreviewMaterial.md#ballowdevelopmentshadercompile)
- [bAllowNegativeEmissiveColor](ue_ue.PreviewMaterial.md#ballownegativeemissivecolor)
- [bAutomaticallySetUsageInEditor](ue_ue.PreviewMaterial.md#bautomaticallysetusageineditor)
- [bBlockGI](ue_ue.PreviewMaterial.md#bblockgi)
- [bCanMaskedBeAssumedOpaque](ue_ue.PreviewMaterial.md#bcanmaskedbeassumedopaque)
- [bCastDynamicShadowAsMasked](ue_ue.PreviewMaterial.md#bcastdynamicshadowasmasked)
- [bCastRayTracedShadows](ue_ue.PreviewMaterial.md#bcastraytracedshadows)
- [bComputeFogPerPixel](ue_ue.PreviewMaterial.md#bcomputefogperpixel)
- [bContactShadows](ue_ue.PreviewMaterial.md#bcontactshadows)
- [bDisableDepthTest](ue_ue.PreviewMaterial.md#bdisabledepthtest)
- [bEnableAdaptiveTessellation](ue_ue.PreviewMaterial.md#benableadaptivetessellation)
- [bEnableCrackFreeDisplacement](ue_ue.PreviewMaterial.md#benablecrackfreedisplacement)
- [bEnableMobileSeparateTranslucency](ue_ue.PreviewMaterial.md#benablemobileseparatetranslucency)
- [bEnableResponsiveAA](ue_ue.PreviewMaterial.md#benableresponsiveaa)
- [bEnableSeparateTranslucency](ue_ue.PreviewMaterial.md#benableseparatetranslucency)
- [bEnableStencilTest](ue_ue.PreviewMaterial.md#benablestenciltest)
- [bFullyRough](ue_ue.PreviewMaterial.md#bfullyrough)
- [bGenerateSphericalParticleNormals](ue_ue.PreviewMaterial.md#bgeneratesphericalparticlenormals)
- [bIsFunctionPreviewMaterial](ue_ue.PreviewMaterial.md#bisfunctionpreviewmaterial)
- [bIsMasked](ue_ue.PreviewMaterial.md#bismasked)
- [bIsMaterialEditorStatsMaterial](ue_ue.PreviewMaterial.md#bismaterialeditorstatsmaterial)
- [bIsPreviewMaterial](ue_ue.PreviewMaterial.md#bispreviewmaterial)
- [bIsSky](ue_ue.PreviewMaterial.md#bissky)
- [bNormalCurvatureToRoughness](ue_ue.PreviewMaterial.md#bnormalcurvaturetoroughness)
- [bOutputTranslucentVelocity](ue_ue.PreviewMaterial.md#boutputtranslucentvelocity)
- [bOutputVelocityOnBasePass](ue_ue.PreviewMaterial.md#boutputvelocityonbasepass)
- [bScreenSpaceReflections](ue_ue.PreviewMaterial.md#bscreenspacereflections)
- [bTangentSpaceNormal](ue_ue.PreviewMaterial.md#btangentspacenormal)
- [bTextureStreamingDataSorted](ue_ue.PreviewMaterial.md#btexturestreamingdatasorted)
- [bUseEmissiveForDynamicAreaLighting](ue_ue.PreviewMaterial.md#buseemissivefordynamicarealighting)
- [bUseFullPrecision](ue_ue.PreviewMaterial.md#busefullprecision)
- [bUseHQForwardReflections](ue_ue.PreviewMaterial.md#busehqforwardreflections)
- [bUseLightmapDirectionality](ue_ue.PreviewMaterial.md#buselightmapdirectionality)
- [bUseMaterialAttributes](ue_ue.PreviewMaterial.md#busematerialattributes)
- [bUsePlanarForwardReflections](ue_ue.PreviewMaterial.md#buseplanarforwardreflections)
- [bUseTranslucencyVertexFog](ue_ue.PreviewMaterial.md#busetranslucencyvertexfog)
- [bUsedAsSpecialEngineMaterial](ue_ue.PreviewMaterial.md#busedasspecialenginematerial)
- [bUsedWithBeamTrails](ue_ue.PreviewMaterial.md#busedwithbeamtrails)
- [bUsedWithClothing](ue_ue.PreviewMaterial.md#busedwithclothing)
- [bUsedWithEditorCompositing](ue_ue.PreviewMaterial.md#busedwitheditorcompositing)
- [bUsedWithGeometryCache](ue_ue.PreviewMaterial.md#busedwithgeometrycache)
- [bUsedWithGeometryCollections](ue_ue.PreviewMaterial.md#busedwithgeometrycollections)
- [bUsedWithHairStrands](ue_ue.PreviewMaterial.md#busedwithhairstrands)
- [bUsedWithInstancedStaticMeshes](ue_ue.PreviewMaterial.md#busedwithinstancedstaticmeshes)
- [bUsedWithMeshParticles](ue_ue.PreviewMaterial.md#busedwithmeshparticles)
- [bUsedWithMorphTargets](ue_ue.PreviewMaterial.md#busedwithmorphtargets)
- [bUsedWithNiagaraMeshParticles](ue_ue.PreviewMaterial.md#busedwithniagarameshparticles)
- [bUsedWithNiagaraRibbons](ue_ue.PreviewMaterial.md#busedwithniagararibbons)
- [bUsedWithNiagaraSprites](ue_ue.PreviewMaterial.md#busedwithniagarasprites)
- [bUsedWithParticleSprites](ue_ue.PreviewMaterial.md#busedwithparticlesprites)
- [bUsedWithSkeletalMesh](ue_ue.PreviewMaterial.md#busedwithskeletalmesh)
- [bUsedWithSplineMeshes](ue_ue.PreviewMaterial.md#busedwithsplinemeshes)
- [bUsedWithStaticLighting](ue_ue.PreviewMaterial.md#busedwithstaticlighting)
- [bUsedWithUI](ue_ue.PreviewMaterial.md#busedwithui)
- [bUsedWithWater](ue_ue.PreviewMaterial.md#busedwithwater)
- [bUsesDistortion](ue_ue.PreviewMaterial.md#busesdistortion)
- [bWriteOnlyAlpha](ue_ue.PreviewMaterial.md#bwriteonlyalpha)

### Methods

- [CreateDefaultSubobject](ue_ue.PreviewMaterial.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PreviewMaterial.md#executeubergraph)
- [GetBaseMaterial](ue_ue.PreviewMaterial.md#getbasematerial)
- [GetClass](ue_ue.PreviewMaterial.md#getclass)
- [GetName](ue_ue.PreviewMaterial.md#getname)
- [GetOuter](ue_ue.PreviewMaterial.md#getouter)
- [GetPhysicalMaterial](ue_ue.PreviewMaterial.md#getphysicalmaterial)
- [GetWorld](ue_ue.PreviewMaterial.md#getworld)
- [SetForceMipLevelsToBeResident](ue_ue.PreviewMaterial.md#setforcemiplevelstoberesident)
- [Find](ue_ue.PreviewMaterial.md#find)
- [Load](ue_ue.PreviewMaterial.md#load)
- [StaticClass](ue_ue.PreviewMaterial.md#staticclass)

## Constructors

### constructor

• **new PreviewMaterial**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Material](ue_ue.Material.md).[constructor](ue_ue.Material.md#constructor)

#### Defined in

[ue/ue.d.ts:58325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58325)

## Properties

### AllowTranslucentCustomDepthWrites

• **AllowTranslucentCustomDepthWrites**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[AllowTranslucentCustomDepthWrites](ue_ue.Material.md#allowtranslucentcustomdepthwrites)

#### Defined in

[ue/ue.d.ts:1498](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1498)

___

### AmbientOcclusion

• **AmbientOcclusion**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[AmbientOcclusion](ue_ue.Material.md#ambientocclusion)

#### Defined in

[ue/ue.d.ts:1437](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1437)

___

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[Material](ue_ue.Material.md).[AssetImportData](ue_ue.Material.md#assetimportdata)

#### Defined in

[ue/ue.d.ts:1556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1556)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[AssetUserData](ue_ue.Material.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:1550](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1550)

___

### BaseColor

• **BaseColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[BaseColor](ue_ue.Material.md#basecolor)

#### Defined in

[ue/ue.d.ts:1414](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1414)

___

### BlendMode

• **BlendMode**: [`EBlendMode`](../enums/ue_ue.EBlendMode.md)

#### Inherited from

[Material](ue_ue.Material.md).[BlendMode](ue_ue.Material.md#blendmode)

#### Defined in

[ue/ue.d.ts:1423](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1423)

___

### BlendableLocation

• **BlendableLocation**: [`EBlendableLocation`](../enums/ue_ue.EBlendableLocation.md)

#### Inherited from

[Material](ue_ue.Material.md).[BlendableLocation](ue_ue.Material.md#blendablelocation)

#### Defined in

[ue/ue.d.ts:1522](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1522)

___

### BlendableOutputAlpha

• **BlendableOutputAlpha**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[BlendableOutputAlpha](ue_ue.Material.md#blendableoutputalpha)

#### Defined in

[ue/ue.d.ts:1523](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1523)

___

### BlendablePriority

• **BlendablePriority**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[BlendablePriority](ue_ue.Material.md#blendablepriority)

#### Defined in

[ue/ue.d.ts:1528](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1528)

___

### CachedQualityLevelsUsed

• **CachedQualityLevelsUsed**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\>

#### Inherited from

[Material](ue_ue.Material.md).[CachedQualityLevelsUsed](ue_ue.Material.md#cachedqualitylevelsused)

#### Defined in

[ue/ue.d.ts:1533](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1533)

___

### ClearCoat

• **ClearCoat**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[ClearCoat](ue_ue.Material.md#clearcoat)

#### Defined in

[ue/ue.d.ts:1435](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1435)

___

### ClearCoatRoughness

• **ClearCoatRoughness**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[ClearCoatRoughness](ue_ue.Material.md#clearcoatroughness)

#### Defined in

[ue/ue.d.ts:1436](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1436)

___

### CustomizedUVs

• **CustomizedUVs**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`Vector2MaterialInput`](ue_ue.Vector2MaterialInput.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[CustomizedUVs](ue_ue.Material.md#customizeduvs)

#### Defined in

[ue/ue.d.ts:1439](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1439)

___

### D3D11TessellationMode

• **D3D11TessellationMode**: [`EMaterialTessellationMode`](../enums/ue_ue.EMaterialTessellationMode.md)

#### Inherited from

[Material](ue_ue.Material.md).[D3D11TessellationMode](ue_ue.Material.md#d3d11tessellationmode)

#### Defined in

[ue/ue.d.ts:1495](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1495)

___

### DecalBlendMode

• **DecalBlendMode**: [`EDecalBlendMode`](../enums/ue_ue.EDecalBlendMode.md)

#### Inherited from

[Material](ue_ue.Material.md).[DecalBlendMode](ue_ue.Material.md#decalblendmode)

#### Defined in

[ue/ue.d.ts:1424](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1424)

___

### DiffuseColor

• **DiffuseColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[DiffuseColor](ue_ue.Material.md#diffusecolor)

#### Defined in

[ue/ue.d.ts:1412](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1412)

___

### DitherOpacityMask

• **DitherOpacityMask**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[DitherOpacityMask](ue_ue.Material.md#ditheropacitymask)

#### Defined in

[ue/ue.d.ts:1449](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1449)

___

### DitheredLODTransition

• **DitheredLODTransition**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[DitheredLODTransition](ue_ue.Material.md#ditheredlodtransition)

#### Defined in

[ue/ue.d.ts:1448](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1448)

___

### EditorComments

• **EditorComments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialExpressionComment`](ue_ue.MaterialExpressionComment.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[EditorComments](ue_ue.Material.md#editorcomments)

#### Defined in

[ue/ue.d.ts:1506](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1506)

___

### EditorPitch

• **EditorPitch**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[EditorPitch](ue_ue.Material.md#editorpitch)

#### Defined in

[ue/ue.d.ts:1503](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1503)

___

### EditorX

• **EditorX**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[EditorX](ue_ue.Material.md#editorx)

#### Defined in

[ue/ue.d.ts:1501](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1501)

___

### EditorY

• **EditorY**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[EditorY](ue_ue.Material.md#editory)

#### Defined in

[ue/ue.d.ts:1502](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1502)

___

### EditorYaw

• **EditorYaw**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[EditorYaw](ue_ue.Material.md#editoryaw)

#### Defined in

[ue/ue.d.ts:1504](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1504)

___

### EmissiveColor

• **EmissiveColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[EmissiveColor](ue_ue.Material.md#emissivecolor)

#### Defined in

[ue/ue.d.ts:1419](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1419)

___

### ExpressionTextureReferences

• **ExpressionTextureReferences**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[ExpressionTextureReferences](ue_ue.Material.md#expressiontexturereferences)

#### Defined in

[ue/ue.d.ts:1534](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1534)

___

### Expressions

• **Expressions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialExpression`](ue_ue.MaterialExpression.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[Expressions](ue_ue.Material.md#expressions)

#### Defined in

[ue/ue.d.ts:1505](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1505)

___

### LayerParameterExpansion

• **LayerParameterExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

#### Inherited from

[Material](ue_ue.Material.md).[LayerParameterExpansion](ue_ue.Material.md#layerparameterexpansion)

#### Defined in

[ue/ue.d.ts:1554](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1554)

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[Material](ue_ue.Material.md).[LightingGuid](ue_ue.Material.md#lightingguid)

#### Defined in

[ue/ue.d.ts:1557](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1557)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassMaterialInterfaceSettings`](ue_ue.LightmassMaterialInterfaceSettings.md)

#### Inherited from

[Material](ue_ue.Material.md).[LightmassSettings](ue_ue.Material.md#lightmasssettings)

#### Defined in

[ue/ue.d.ts:1546](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1546)

___

### MaterialAttributes

• **MaterialAttributes**: [`MaterialAttributesInput`](ue_ue.MaterialAttributesInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[MaterialAttributes](ue_ue.Material.md#materialattributes)

#### Defined in

[ue/ue.d.ts:1440](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1440)

___

### MaterialDecalResponse

• **MaterialDecalResponse**: [`EMaterialDecalResponse`](../enums/ue_ue.EMaterialDecalResponse.md)

#### Inherited from

[Material](ue_ue.Material.md).[MaterialDecalResponse](ue_ue.Material.md#materialdecalresponse)

#### Defined in

[ue/ue.d.ts:1425](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1425)

___

### MaterialDomain

• **MaterialDomain**: [`EMaterialDomain`](../enums/ue_ue.EMaterialDomain.md)

#### Inherited from

[Material](ue_ue.Material.md).[MaterialDomain](ue_ue.Material.md#materialdomain)

#### Defined in

[ue/ue.d.ts:1422](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1422)

___

### MaterialFunctionInfos

• **MaterialFunctionInfos**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialFunctionInfo`](ue_ue.MaterialFunctionInfo.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[MaterialFunctionInfos](ue_ue.Material.md#materialfunctioninfos)

#### Defined in

[ue/ue.d.ts:1508](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1508)

___

### MaterialParameterCollectionInfos

• **MaterialParameterCollectionInfos**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialParameterCollectionInfo`](ue_ue.MaterialParameterCollectionInfo.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[MaterialParameterCollectionInfos](ue_ue.Material.md#materialparametercollectioninfos)

#### Defined in

[ue/ue.d.ts:1509](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1509)

___

### MaxDisplacement

• **MaxDisplacement**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[MaxDisplacement](ue_ue.Material.md#maxdisplacement)

#### Defined in

[ue/ue.d.ts:1532](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1532)

___

### Metallic

• **Metallic**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[Metallic](ue_ue.Material.md#metallic)

#### Defined in

[ue/ue.d.ts:1415](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1415)

___

### Normal

• **Normal**: [`VectorMaterialInput`](ue_ue.VectorMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[Normal](ue_ue.Material.md#normal)

#### Defined in

[ue/ue.d.ts:1418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1418)

___

### NumCustomizedUVs

• **NumCustomizedUVs**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[NumCustomizedUVs](ue_ue.Material.md#numcustomizeduvs)

#### Defined in

[ue/ue.d.ts:1453](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1453)

___

### Opacity

• **Opacity**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[Opacity](ue_ue.Material.md#opacity)

#### Defined in

[ue/ue.d.ts:1420](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1420)

___

### OpacityMask

• **OpacityMask**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[OpacityMask](ue_ue.Material.md#opacitymask)

#### Defined in

[ue/ue.d.ts:1421](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1421)

___

### OpacityMaskClipValue

• **OpacityMaskClipValue**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[OpacityMaskClipValue](ue_ue.Material.md#opacitymaskclipvalue)

#### Defined in

[ue/ue.d.ts:1430](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1430)

___

### ParameterGroupData

• **ParameterGroupData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParameterGroupData`](ue_ue.ParameterGroupData.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[ParameterGroupData](ue_ue.Material.md#parametergroupdata)

#### Defined in

[ue/ue.d.ts:1507](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1507)

___

### ParameterOverviewExpansion

• **ParameterOverviewExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

#### Inherited from

[Material](ue_ue.Material.md).[ParameterOverviewExpansion](ue_ue.Material.md#parameteroverviewexpansion)

#### Defined in

[ue/ue.d.ts:1555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1555)

___

### PhysMaterial

• **PhysMaterial**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Inherited from

[Material](ue_ue.Material.md).[PhysMaterial](ue_ue.Material.md#physmaterial)

#### Defined in

[ue/ue.d.ts:1411](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1411)

___

### PixelDepthOffset

• **PixelDepthOffset**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[PixelDepthOffset](ue_ue.Material.md#pixeldepthoffset)

#### Defined in

[ue/ue.d.ts:1441](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1441)

___

### PreviewMesh

• **PreviewMesh**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Material](ue_ue.Material.md).[PreviewMesh](ue_ue.Material.md#previewmesh)

#### Defined in

[ue/ue.d.ts:1552](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1552)

___

### ReferencedTextureGuids

• **ReferencedTextureGuids**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[ReferencedTextureGuids](ue_ue.Material.md#referencedtextureguids)

#### Defined in

[ue/ue.d.ts:1535](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1535)

___

### Refraction

• **Refraction**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[Refraction](ue_ue.Material.md#refraction)

#### Defined in

[ue/ue.d.ts:1438](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1438)

___

### RefractionDepthBias

• **RefractionDepthBias**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[RefractionDepthBias](ue_ue.Material.md#refractiondepthbias)

#### Defined in

[ue/ue.d.ts:1530](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1530)

___

### RefractionMode

• **RefractionMode**: [`ERefractionMode`](../enums/ue_ue.ERefractionMode.md)

#### Inherited from

[Material](ue_ue.Material.md).[RefractionMode](ue_ue.Material.md#refractionmode)

#### Defined in

[ue/ue.d.ts:1527](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1527)

___

### Roughness

• **Roughness**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[Roughness](ue_ue.Material.md#roughness)

#### Defined in

[ue/ue.d.ts:1417](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1417)

___

### ShadingModel

• **ShadingModel**: [`EMaterialShadingModel`](../enums/ue_ue.EMaterialShadingModel.md)

#### Inherited from

[Material](ue_ue.Material.md).[ShadingModel](ue_ue.Material.md#shadingmodel)

#### Defined in

[ue/ue.d.ts:1426](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1426)

___

### ShadingModelFromMaterialExpression

• **ShadingModelFromMaterialExpression**: [`ShadingModelMaterialInput`](ue_ue.ShadingModelMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[ShadingModelFromMaterialExpression](ue_ue.Material.md#shadingmodelfrommaterialexpression)

#### Defined in

[ue/ue.d.ts:1442](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1442)

___

### ShadingModels

• **ShadingModels**: [`MaterialShadingModelField`](ue_ue.MaterialShadingModelField.md)

#### Inherited from

[Material](ue_ue.Material.md).[ShadingModels](ue_ue.Material.md#shadingmodels)

#### Defined in

[ue/ue.d.ts:1428](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1428)

___

### Specular

• **Specular**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[Specular](ue_ue.Material.md#specular)

#### Defined in

[ue/ue.d.ts:1416](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1416)

___

### SpecularColor

• **SpecularColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[SpecularColor](ue_ue.Material.md#specularcolor)

#### Defined in

[ue/ue.d.ts:1413](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1413)

___

### StateId

• **StateId**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[Material](ue_ue.Material.md).[StateId](ue_ue.Material.md#stateid)

#### Defined in

[ue/ue.d.ts:1531](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1531)

___

### StencilCompare

• **StencilCompare**: [`EMaterialStencilCompare`](../enums/ue_ue.EMaterialStencilCompare.md)

#### Inherited from

[Material](ue_ue.Material.md).[StencilCompare](ue_ue.Material.md#stencilcompare)

#### Defined in

[ue/ue.d.ts:1525](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1525)

___

### StencilRefValue

• **StencilRefValue**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[StencilRefValue](ue_ue.Material.md#stencilrefvalue)

#### Defined in

[ue/ue.d.ts:1526](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1526)

___

### SubsurfaceColor

• **SubsurfaceColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[SubsurfaceColor](ue_ue.Material.md#subsurfacecolor)

#### Defined in

[ue/ue.d.ts:1434](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1434)

___

### SubsurfaceProfile

• **SubsurfaceProfile**: [`SubsurfaceProfile`](ue_ue.SubsurfaceProfile.md)

#### Inherited from

[Material](ue_ue.Material.md).[SubsurfaceProfile](ue_ue.Material.md#subsurfaceprofile)

#### Defined in

[ue/ue.d.ts:1545](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1545)

___

### TessellationMultiplier

• **TessellationMultiplier**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[TessellationMultiplier](ue_ue.Material.md#tessellationmultiplier)

#### Defined in

[ue/ue.d.ts:1433](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1433)

___

### TextureStreamingData

• **TextureStreamingData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[TextureStreamingData](ue_ue.Material.md#texturestreamingdata)

#### Defined in

[ue/ue.d.ts:1549](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1549)

___

### TextureStreamingDataMissingEntries

• **TextureStreamingDataMissingEntries**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[TextureStreamingDataMissingEntries](ue_ue.Material.md#texturestreamingdatamissingentries)

#### Defined in

[ue/ue.d.ts:1551](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1551)

___

### TextureStreamingDataVersion

• **TextureStreamingDataVersion**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[TextureStreamingDataVersion](ue_ue.Material.md#texturestreamingdataversion)

#### Defined in

[ue/ue.d.ts:1548](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1548)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[Material](ue_ue.Material.md).[ThumbnailInfo](ue_ue.Material.md#thumbnailinfo)

#### Defined in

[ue/ue.d.ts:1553](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1553)

___

### TranslucencyDirectionalLightingIntensity

• **TranslucencyDirectionalLightingIntensity**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[TranslucencyDirectionalLightingIntensity](ue_ue.Material.md#translucencydirectionallightingintensity)

#### Defined in

[ue/ue.d.ts:1454](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1454)

___

### TranslucencyLightingMode

• **TranslucencyLightingMode**: [`ETranslucencyLightingMode`](../enums/ue_ue.ETranslucencyLightingMode.md)

#### Inherited from

[Material](ue_ue.Material.md).[TranslucencyLightingMode](ue_ue.Material.md#translucencylightingmode)

#### Defined in

[ue/ue.d.ts:1451](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1451)

___

### TranslucentBackscatteringExponent

• **TranslucentBackscatteringExponent**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[TranslucentBackscatteringExponent](ue_ue.Material.md#translucentbackscatteringexponent)

#### Defined in

[ue/ue.d.ts:1459](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1459)

___

### TranslucentMultipleScatteringExtinction

• **TranslucentMultipleScatteringExtinction**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[Material](ue_ue.Material.md).[TranslucentMultipleScatteringExtinction](ue_ue.Material.md#translucentmultiplescatteringextinction)

#### Defined in

[ue/ue.d.ts:1460](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1460)

___

### TranslucentSelfShadowDensityScale

• **TranslucentSelfShadowDensityScale**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[TranslucentSelfShadowDensityScale](ue_ue.Material.md#translucentselfshadowdensityscale)

#### Defined in

[ue/ue.d.ts:1456](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1456)

___

### TranslucentSelfShadowSecondDensityScale

• **TranslucentSelfShadowSecondDensityScale**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[TranslucentSelfShadowSecondDensityScale](ue_ue.Material.md#translucentselfshadowseconddensityscale)

#### Defined in

[ue/ue.d.ts:1457](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1457)

___

### TranslucentSelfShadowSecondOpacity

• **TranslucentSelfShadowSecondOpacity**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[TranslucentSelfShadowSecondOpacity](ue_ue.Material.md#translucentselfshadowsecondopacity)

#### Defined in

[ue/ue.d.ts:1458](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1458)

___

### TranslucentShadowDensityScale

• **TranslucentShadowDensityScale**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[TranslucentShadowDensityScale](ue_ue.Material.md#translucentshadowdensityscale)

#### Defined in

[ue/ue.d.ts:1455](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1455)

___

### TranslucentShadowStartOffset

• **TranslucentShadowStartOffset**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[TranslucentShadowStartOffset](ue_ue.Material.md#translucentshadowstartoffset)

#### Defined in

[ue/ue.d.ts:1461](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1461)

___

### TwoSided

• **TwoSided**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[TwoSided](ue_ue.Material.md#twosided)

#### Defined in

[ue/ue.d.ts:1447](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1447)

___

### UsageFlagWarnings

• **UsageFlagWarnings**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[UsageFlagWarnings](ue_ue.Material.md#usageflagwarnings)

#### Defined in

[ue/ue.d.ts:1529](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1529)

___

### UsedShadingModels

• **UsedShadingModels**: `string`

#### Inherited from

[Material](ue_ue.Material.md).[UsedShadingModels](ue_ue.Material.md#usedshadingmodels)

#### Defined in

[ue/ue.d.ts:1429](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1429)

___

### Wireframe

• **Wireframe**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[Wireframe](ue_ue.Material.md#wireframe)

#### Defined in

[ue/ue.d.ts:1499](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1499)

___

### WorldDisplacement

• **WorldDisplacement**: [`VectorMaterialInput`](ue_ue.VectorMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[WorldDisplacement](ue_ue.Material.md#worlddisplacement)

#### Defined in

[ue/ue.d.ts:1432](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1432)

___

### WorldPositionOffset

• **WorldPositionOffset**: [`VectorMaterialInput`](ue_ue.VectorMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[WorldPositionOffset](ue_ue.Material.md#worldpositionoffset)

#### Defined in

[ue/ue.d.ts:1431](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1431)

___

### \_\_tid\_MaterialInterface\_\_

• **\_\_tid\_MaterialInterface\_\_**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[__tid_MaterialInterface__](ue_ue.Material.md#__tid_materialinterface__)

#### Defined in

[ue/ue.d.ts:1565](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1565)

___

### \_\_tid\_Material\_\_

• **\_\_tid\_Material\_\_**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[__tid_Material__](ue_ue.Material.md#__tid_material__)

#### Defined in

[ue/ue.d.ts:1540](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1540)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[__tid_Object__](ue_ue.Material.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PreviewMaterial\_\_

• **\_\_tid\_PreviewMaterial\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:58330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58330)

___

### bAllowDevelopmentShaderCompile

• **bAllowDevelopmentShaderCompile**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bAllowDevelopmentShaderCompile](ue_ue.Material.md#ballowdevelopmentshadercompile)

#### Defined in

[ue/ue.d.ts:1520](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1520)

___

### bAllowNegativeEmissiveColor

• **bAllowNegativeEmissiveColor**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bAllowNegativeEmissiveColor](ue_ue.Material.md#ballownegativeemissivecolor)

#### Defined in

[ue/ue.d.ts:1450](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1450)

___

### bAutomaticallySetUsageInEditor

• **bAutomaticallySetUsageInEditor**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bAutomaticallySetUsageInEditor](ue_ue.Material.md#bautomaticallysetusageineditor)

#### Defined in

[ue/ue.d.ts:1488](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1488)

___

### bBlockGI

• **bBlockGI**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bBlockGI](ue_ue.Material.md#bblockgi)

#### Defined in

[ue/ue.d.ts:1467](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1467)

___

### bCanMaskedBeAssumedOpaque

• **bCanMaskedBeAssumedOpaque**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bCanMaskedBeAssumedOpaque](ue_ue.Material.md#bcanmaskedbeassumedopaque)

#### Defined in

[ue/ue.d.ts:1510](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1510)

___

### bCastDynamicShadowAsMasked

• **bCastDynamicShadowAsMasked**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bCastDynamicShadowAsMasked](ue_ue.Material.md#bcastdynamicshadowasmasked)

#### Defined in

[ue/ue.d.ts:1427](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1427)

___

### bCastRayTracedShadows

• **bCastRayTracedShadows**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bCastRayTracedShadows](ue_ue.Material.md#bcastraytracedshadows)

#### Defined in

[ue/ue.d.ts:1515](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1515)

___

### bComputeFogPerPixel

• **bComputeFogPerPixel**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bComputeFogPerPixel](ue_ue.Material.md#bcomputefogperpixel)

#### Defined in

[ue/ue.d.ts:1518](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1518)

___

### bContactShadows

• **bContactShadows**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bContactShadows](ue_ue.Material.md#bcontactshadows)

#### Defined in

[ue/ue.d.ts:1446](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1446)

___

### bDisableDepthTest

• **bDisableDepthTest**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bDisableDepthTest](ue_ue.Material.md#bdisabledepthtest)

#### Defined in

[ue/ue.d.ts:1462](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1462)

___

### bEnableAdaptiveTessellation

• **bEnableAdaptiveTessellation**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bEnableAdaptiveTessellation](ue_ue.Material.md#benableadaptivetessellation)

#### Defined in

[ue/ue.d.ts:1497](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1497)

___

### bEnableCrackFreeDisplacement

• **bEnableCrackFreeDisplacement**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bEnableCrackFreeDisplacement](ue_ue.Material.md#benablecrackfreedisplacement)

#### Defined in

[ue/ue.d.ts:1496](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1496)

___

### bEnableMobileSeparateTranslucency

• **bEnableMobileSeparateTranslucency**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bEnableMobileSeparateTranslucency](ue_ue.Material.md#benablemobileseparatetranslucency)

#### Defined in

[ue/ue.d.ts:1452](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1452)

___

### bEnableResponsiveAA

• **bEnableResponsiveAA**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bEnableResponsiveAA](ue_ue.Material.md#benableresponsiveaa)

#### Defined in

[ue/ue.d.ts:1444](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1444)

___

### bEnableSeparateTranslucency

• **bEnableSeparateTranslucency**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bEnableSeparateTranslucency](ue_ue.Material.md#benableseparatetranslucency)

#### Defined in

[ue/ue.d.ts:1443](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1443)

___

### bEnableStencilTest

• **bEnableStencilTest**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bEnableStencilTest](ue_ue.Material.md#benablestenciltest)

#### Defined in

[ue/ue.d.ts:1524](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1524)

___

### bFullyRough

• **bFullyRough**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bFullyRough](ue_ue.Material.md#bfullyrough)

#### Defined in

[ue/ue.d.ts:1489](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1489)

___

### bGenerateSphericalParticleNormals

• **bGenerateSphericalParticleNormals**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bGenerateSphericalParticleNormals](ue_ue.Material.md#bgeneratesphericalparticlenormals)

#### Defined in

[ue/ue.d.ts:1464](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1464)

___

### bIsFunctionPreviewMaterial

• **bIsFunctionPreviewMaterial**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bIsFunctionPreviewMaterial](ue_ue.Material.md#bisfunctionpreviewmaterial)

#### Defined in

[ue/ue.d.ts:1513](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1513)

___

### bIsMasked

• **bIsMasked**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bIsMasked](ue_ue.Material.md#bismasked)

#### Defined in

[ue/ue.d.ts:1511](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1511)

___

### bIsMaterialEditorStatsMaterial

• **bIsMaterialEditorStatsMaterial**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bIsMaterialEditorStatsMaterial](ue_ue.Material.md#bismaterialeditorstatsmaterial)

#### Defined in

[ue/ue.d.ts:1521](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1521)

___

### bIsPreviewMaterial

• **bIsPreviewMaterial**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bIsPreviewMaterial](ue_ue.Material.md#bispreviewmaterial)

#### Defined in

[ue/ue.d.ts:1512](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1512)

___

### bIsSky

• **bIsSky**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bIsSky](ue_ue.Material.md#bissky)

#### Defined in

[ue/ue.d.ts:1517](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1517)

___

### bNormalCurvatureToRoughness

• **bNormalCurvatureToRoughness**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bNormalCurvatureToRoughness](ue_ue.Material.md#bnormalcurvaturetoroughness)

#### Defined in

[ue/ue.d.ts:1494](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1494)

___

### bOutputTranslucentVelocity

• **bOutputTranslucentVelocity**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bOutputTranslucentVelocity](ue_ue.Material.md#boutputtranslucentvelocity)

#### Defined in

[ue/ue.d.ts:1519](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1519)

___

### bOutputVelocityOnBasePass

• **bOutputVelocityOnBasePass**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bOutputVelocityOnBasePass](ue_ue.Material.md#boutputvelocityonbasepass)

#### Defined in

[ue/ue.d.ts:1500](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1500)

___

### bScreenSpaceReflections

• **bScreenSpaceReflections**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bScreenSpaceReflections](ue_ue.Material.md#bscreenspacereflections)

#### Defined in

[ue/ue.d.ts:1445](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1445)

___

### bTangentSpaceNormal

• **bTangentSpaceNormal**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bTangentSpaceNormal](ue_ue.Material.md#btangentspacenormal)

#### Defined in

[ue/ue.d.ts:1465](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1465)

___

### bTextureStreamingDataSorted

• **bTextureStreamingDataSorted**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bTextureStreamingDataSorted](ue_ue.Material.md#btexturestreamingdatasorted)

#### Defined in

[ue/ue.d.ts:1547](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1547)

___

### bUseEmissiveForDynamicAreaLighting

• **bUseEmissiveForDynamicAreaLighting**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUseEmissiveForDynamicAreaLighting](ue_ue.Material.md#buseemissivefordynamicarealighting)

#### Defined in

[ue/ue.d.ts:1466](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1466)

___

### bUseFullPrecision

• **bUseFullPrecision**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUseFullPrecision](ue_ue.Material.md#busefullprecision)

#### Defined in

[ue/ue.d.ts:1490](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1490)

___

### bUseHQForwardReflections

• **bUseHQForwardReflections**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUseHQForwardReflections](ue_ue.Material.md#busehqforwardreflections)

#### Defined in

[ue/ue.d.ts:1492](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1492)

___

### bUseLightmapDirectionality

• **bUseLightmapDirectionality**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUseLightmapDirectionality](ue_ue.Material.md#buselightmapdirectionality)

#### Defined in

[ue/ue.d.ts:1491](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1491)

___

### bUseMaterialAttributes

• **bUseMaterialAttributes**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUseMaterialAttributes](ue_ue.Material.md#busematerialattributes)

#### Defined in

[ue/ue.d.ts:1514](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1514)

___

### bUsePlanarForwardReflections

• **bUsePlanarForwardReflections**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsePlanarForwardReflections](ue_ue.Material.md#buseplanarforwardreflections)

#### Defined in

[ue/ue.d.ts:1493](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1493)

___

### bUseTranslucencyVertexFog

• **bUseTranslucencyVertexFog**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUseTranslucencyVertexFog](ue_ue.Material.md#busetranslucencyvertexfog)

#### Defined in

[ue/ue.d.ts:1516](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1516)

___

### bUsedAsSpecialEngineMaterial

• **bUsedAsSpecialEngineMaterial**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedAsSpecialEngineMaterial](ue_ue.Material.md#busedasspecialenginematerial)

#### Defined in

[ue/ue.d.ts:1468](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1468)

___

### bUsedWithBeamTrails

• **bUsedWithBeamTrails**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithBeamTrails](ue_ue.Material.md#busedwithbeamtrails)

#### Defined in

[ue/ue.d.ts:1472](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1472)

___

### bUsedWithClothing

• **bUsedWithClothing**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithClothing](ue_ue.Material.md#busedwithclothing)

#### Defined in

[ue/ue.d.ts:1484](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1484)

___

### bUsedWithEditorCompositing

• **bUsedWithEditorCompositing**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithEditorCompositing](ue_ue.Material.md#busedwitheditorcompositing)

#### Defined in

[ue/ue.d.ts:1470](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1470)

___

### bUsedWithGeometryCache

• **bUsedWithGeometryCache**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithGeometryCache](ue_ue.Material.md#busedwithgeometrycache)

#### Defined in

[ue/ue.d.ts:1477](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1477)

___

### bUsedWithGeometryCollections

• **bUsedWithGeometryCollections**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithGeometryCollections](ue_ue.Material.md#busedwithgeometrycollections)

#### Defined in

[ue/ue.d.ts:1482](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1482)

___

### bUsedWithHairStrands

• **bUsedWithHairStrands**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithHairStrands](ue_ue.Material.md#busedwithhairstrands)

#### Defined in

[ue/ue.d.ts:1486](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1486)

___

### bUsedWithInstancedStaticMeshes

• **bUsedWithInstancedStaticMeshes**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithInstancedStaticMeshes](ue_ue.Material.md#busedwithinstancedstaticmeshes)

#### Defined in

[ue/ue.d.ts:1481](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1481)

___

### bUsedWithMeshParticles

• **bUsedWithMeshParticles**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithMeshParticles](ue_ue.Material.md#busedwithmeshparticles)

#### Defined in

[ue/ue.d.ts:1473](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1473)

___

### bUsedWithMorphTargets

• **bUsedWithMorphTargets**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithMorphTargets](ue_ue.Material.md#busedwithmorphtargets)

#### Defined in

[ue/ue.d.ts:1479](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1479)

___

### bUsedWithNiagaraMeshParticles

• **bUsedWithNiagaraMeshParticles**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithNiagaraMeshParticles](ue_ue.Material.md#busedwithniagarameshparticles)

#### Defined in

[ue/ue.d.ts:1476](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1476)

___

### bUsedWithNiagaraRibbons

• **bUsedWithNiagaraRibbons**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithNiagaraRibbons](ue_ue.Material.md#busedwithniagararibbons)

#### Defined in

[ue/ue.d.ts:1475](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1475)

___

### bUsedWithNiagaraSprites

• **bUsedWithNiagaraSprites**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithNiagaraSprites](ue_ue.Material.md#busedwithniagarasprites)

#### Defined in

[ue/ue.d.ts:1474](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1474)

___

### bUsedWithParticleSprites

• **bUsedWithParticleSprites**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithParticleSprites](ue_ue.Material.md#busedwithparticlesprites)

#### Defined in

[ue/ue.d.ts:1471](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1471)

___

### bUsedWithSkeletalMesh

• **bUsedWithSkeletalMesh**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithSkeletalMesh](ue_ue.Material.md#busedwithskeletalmesh)

#### Defined in

[ue/ue.d.ts:1469](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1469)

___

### bUsedWithSplineMeshes

• **bUsedWithSplineMeshes**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithSplineMeshes](ue_ue.Material.md#busedwithsplinemeshes)

#### Defined in

[ue/ue.d.ts:1480](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1480)

___

### bUsedWithStaticLighting

• **bUsedWithStaticLighting**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithStaticLighting](ue_ue.Material.md#busedwithstaticlighting)

#### Defined in

[ue/ue.d.ts:1478](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1478)

___

### bUsedWithUI

• **bUsedWithUI**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithUI](ue_ue.Material.md#busedwithui)

#### Defined in

[ue/ue.d.ts:1487](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1487)

___

### bUsedWithWater

• **bUsedWithWater**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithWater](ue_ue.Material.md#busedwithwater)

#### Defined in

[ue/ue.d.ts:1485](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1485)

___

### bUsesDistortion

• **bUsesDistortion**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsesDistortion](ue_ue.Material.md#busesdistortion)

#### Defined in

[ue/ue.d.ts:1483](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1483)

___

### bWriteOnlyAlpha

• **bWriteOnlyAlpha**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bWriteOnlyAlpha](ue_ue.Material.md#bwriteonlyalpha)

#### Defined in

[ue/ue.d.ts:1463](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1463)

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

[Material](ue_ue.Material.md).[CreateDefaultSubobject](ue_ue.Material.md#createdefaultsubobject)

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

[Material](ue_ue.Material.md).[ExecuteUbergraph](ue_ue.Material.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetBaseMaterial

▸ **GetBaseMaterial**(): [`Material`](ue_ue.Material.md)

#### Returns

[`Material`](ue_ue.Material.md)

#### Inherited from

[Material](ue_ue.Material.md).[GetBaseMaterial](ue_ue.Material.md#getbasematerial)

#### Defined in

[ue/ue.d.ts:1558](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1558)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Material](ue_ue.Material.md).[GetClass](ue_ue.Material.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Material](ue_ue.Material.md).[GetName](ue_ue.Material.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Material](ue_ue.Material.md).[GetOuter](ue_ue.Material.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetPhysicalMaterial

▸ **GetPhysicalMaterial**(): [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Returns

[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Inherited from

[Material](ue_ue.Material.md).[GetPhysicalMaterial](ue_ue.Material.md#getphysicalmaterial)

#### Defined in

[ue/ue.d.ts:1559](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1559)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Material](ue_ue.Material.md).[GetWorld](ue_ue.Material.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### SetForceMipLevelsToBeResident

▸ **SetForceMipLevelsToBeResident**(`OverrideForceMiplevelsToBeResident`, `bForceMiplevelsToBeResidentValue`, `ForceDuration`, `CinematicTextureGroups?`, `bFastResponse?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OverrideForceMiplevelsToBeResident` | `boolean` |
| `bForceMiplevelsToBeResidentValue` | `boolean` |
| `ForceDuration` | `number` |
| `CinematicTextureGroups?` | `number` |
| `bFastResponse?` | `boolean` |

#### Returns

`void`

#### Inherited from

[Material](ue_ue.Material.md).[SetForceMipLevelsToBeResident](ue_ue.Material.md#setforcemiplevelstoberesident)

#### Defined in

[ue/ue.d.ts:1560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1560)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PreviewMaterial`](ue_ue.PreviewMaterial.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PreviewMaterial`](ue_ue.PreviewMaterial.md)

#### Overrides

[Material](ue_ue.Material.md).[Find](ue_ue.Material.md#find)

#### Defined in

[ue/ue.d.ts:58327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58327)

___

### Load

▸ `Static` **Load**(`InName`): [`PreviewMaterial`](ue_ue.PreviewMaterial.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PreviewMaterial`](ue_ue.PreviewMaterial.md)

#### Overrides

[Material](ue_ue.Material.md).[Load](ue_ue.Material.md#load)

#### Defined in

[ue/ue.d.ts:58328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58328)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Material](ue_ue.Material.md).[StaticClass](ue_ue.Material.md#staticclass)

#### Defined in

[ue/ue.d.ts:58326](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58326)
