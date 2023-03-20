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

## Properties

### AllowTranslucentCustomDepthWrites

• **AllowTranslucentCustomDepthWrites**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[AllowTranslucentCustomDepthWrites](ue_ue.Material.md#allowtranslucentcustomdepthwrites)

___

### AmbientOcclusion

• **AmbientOcclusion**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[AmbientOcclusion](ue_ue.Material.md#ambientocclusion)

___

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[Material](ue_ue.Material.md).[AssetImportData](ue_ue.Material.md#assetimportdata)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[AssetUserData](ue_ue.Material.md#assetuserdata)

___

### BaseColor

• **BaseColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[BaseColor](ue_ue.Material.md#basecolor)

___

### BlendMode

• **BlendMode**: [`EBlendMode`](../enums/ue_ue.EBlendMode.md)

#### Inherited from

[Material](ue_ue.Material.md).[BlendMode](ue_ue.Material.md#blendmode)

___

### BlendableLocation

• **BlendableLocation**: [`EBlendableLocation`](../enums/ue_ue.EBlendableLocation.md)

#### Inherited from

[Material](ue_ue.Material.md).[BlendableLocation](ue_ue.Material.md#blendablelocation)

___

### BlendableOutputAlpha

• **BlendableOutputAlpha**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[BlendableOutputAlpha](ue_ue.Material.md#blendableoutputalpha)

___

### BlendablePriority

• **BlendablePriority**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[BlendablePriority](ue_ue.Material.md#blendablepriority)

___

### CachedQualityLevelsUsed

• **CachedQualityLevelsUsed**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\>

#### Inherited from

[Material](ue_ue.Material.md).[CachedQualityLevelsUsed](ue_ue.Material.md#cachedqualitylevelsused)

___

### ClearCoat

• **ClearCoat**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[ClearCoat](ue_ue.Material.md#clearcoat)

___

### ClearCoatRoughness

• **ClearCoatRoughness**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[ClearCoatRoughness](ue_ue.Material.md#clearcoatroughness)

___

### CustomizedUVs

• **CustomizedUVs**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`Vector2MaterialInput`](ue_ue.Vector2MaterialInput.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[CustomizedUVs](ue_ue.Material.md#customizeduvs)

___

### D3D11TessellationMode

• **D3D11TessellationMode**: [`EMaterialTessellationMode`](../enums/ue_ue.EMaterialTessellationMode.md)

#### Inherited from

[Material](ue_ue.Material.md).[D3D11TessellationMode](ue_ue.Material.md#d3d11tessellationmode)

___

### DecalBlendMode

• **DecalBlendMode**: [`EDecalBlendMode`](../enums/ue_ue.EDecalBlendMode.md)

#### Inherited from

[Material](ue_ue.Material.md).[DecalBlendMode](ue_ue.Material.md#decalblendmode)

___

### DiffuseColor

• **DiffuseColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[DiffuseColor](ue_ue.Material.md#diffusecolor)

___

### DitherOpacityMask

• **DitherOpacityMask**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[DitherOpacityMask](ue_ue.Material.md#ditheropacitymask)

___

### DitheredLODTransition

• **DitheredLODTransition**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[DitheredLODTransition](ue_ue.Material.md#ditheredlodtransition)

___

### EditorComments

• **EditorComments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialExpressionComment`](ue_ue.MaterialExpressionComment.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[EditorComments](ue_ue.Material.md#editorcomments)

___

### EditorPitch

• **EditorPitch**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[EditorPitch](ue_ue.Material.md#editorpitch)

___

### EditorX

• **EditorX**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[EditorX](ue_ue.Material.md#editorx)

___

### EditorY

• **EditorY**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[EditorY](ue_ue.Material.md#editory)

___

### EditorYaw

• **EditorYaw**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[EditorYaw](ue_ue.Material.md#editoryaw)

___

### EmissiveColor

• **EmissiveColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[EmissiveColor](ue_ue.Material.md#emissivecolor)

___

### ExpressionTextureReferences

• **ExpressionTextureReferences**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[ExpressionTextureReferences](ue_ue.Material.md#expressiontexturereferences)

___

### Expressions

• **Expressions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialExpression`](ue_ue.MaterialExpression.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[Expressions](ue_ue.Material.md#expressions)

___

### LayerParameterExpansion

• **LayerParameterExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

#### Inherited from

[Material](ue_ue.Material.md).[LayerParameterExpansion](ue_ue.Material.md#layerparameterexpansion)

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[Material](ue_ue.Material.md).[LightingGuid](ue_ue.Material.md#lightingguid)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassMaterialInterfaceSettings`](ue_ue.LightmassMaterialInterfaceSettings.md)

#### Inherited from

[Material](ue_ue.Material.md).[LightmassSettings](ue_ue.Material.md#lightmasssettings)

___

### MaterialAttributes

• **MaterialAttributes**: [`MaterialAttributesInput`](ue_ue.MaterialAttributesInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[MaterialAttributes](ue_ue.Material.md#materialattributes)

___

### MaterialDecalResponse

• **MaterialDecalResponse**: [`EMaterialDecalResponse`](../enums/ue_ue.EMaterialDecalResponse.md)

#### Inherited from

[Material](ue_ue.Material.md).[MaterialDecalResponse](ue_ue.Material.md#materialdecalresponse)

___

### MaterialDomain

• **MaterialDomain**: [`EMaterialDomain`](../enums/ue_ue.EMaterialDomain.md)

#### Inherited from

[Material](ue_ue.Material.md).[MaterialDomain](ue_ue.Material.md#materialdomain)

___

### MaterialFunctionInfos

• **MaterialFunctionInfos**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialFunctionInfo`](ue_ue.MaterialFunctionInfo.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[MaterialFunctionInfos](ue_ue.Material.md#materialfunctioninfos)

___

### MaterialParameterCollectionInfos

• **MaterialParameterCollectionInfos**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialParameterCollectionInfo`](ue_ue.MaterialParameterCollectionInfo.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[MaterialParameterCollectionInfos](ue_ue.Material.md#materialparametercollectioninfos)

___

### MaxDisplacement

• **MaxDisplacement**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[MaxDisplacement](ue_ue.Material.md#maxdisplacement)

___

### Metallic

• **Metallic**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[Metallic](ue_ue.Material.md#metallic)

___

### Normal

• **Normal**: [`VectorMaterialInput`](ue_ue.VectorMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[Normal](ue_ue.Material.md#normal)

___

### NumCustomizedUVs

• **NumCustomizedUVs**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[NumCustomizedUVs](ue_ue.Material.md#numcustomizeduvs)

___

### Opacity

• **Opacity**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[Opacity](ue_ue.Material.md#opacity)

___

### OpacityMask

• **OpacityMask**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[OpacityMask](ue_ue.Material.md#opacitymask)

___

### OpacityMaskClipValue

• **OpacityMaskClipValue**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[OpacityMaskClipValue](ue_ue.Material.md#opacitymaskclipvalue)

___

### ParameterGroupData

• **ParameterGroupData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParameterGroupData`](ue_ue.ParameterGroupData.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[ParameterGroupData](ue_ue.Material.md#parametergroupdata)

___

### ParameterOverviewExpansion

• **ParameterOverviewExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

#### Inherited from

[Material](ue_ue.Material.md).[ParameterOverviewExpansion](ue_ue.Material.md#parameteroverviewexpansion)

___

### PhysMaterial

• **PhysMaterial**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Inherited from

[Material](ue_ue.Material.md).[PhysMaterial](ue_ue.Material.md#physmaterial)

___

### PixelDepthOffset

• **PixelDepthOffset**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[PixelDepthOffset](ue_ue.Material.md#pixeldepthoffset)

___

### PreviewMesh

• **PreviewMesh**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Material](ue_ue.Material.md).[PreviewMesh](ue_ue.Material.md#previewmesh)

___

### ReferencedTextureGuids

• **ReferencedTextureGuids**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[ReferencedTextureGuids](ue_ue.Material.md#referencedtextureguids)

___

### Refraction

• **Refraction**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[Refraction](ue_ue.Material.md#refraction)

___

### RefractionDepthBias

• **RefractionDepthBias**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[RefractionDepthBias](ue_ue.Material.md#refractiondepthbias)

___

### RefractionMode

• **RefractionMode**: [`ERefractionMode`](../enums/ue_ue.ERefractionMode.md)

#### Inherited from

[Material](ue_ue.Material.md).[RefractionMode](ue_ue.Material.md#refractionmode)

___

### Roughness

• **Roughness**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[Roughness](ue_ue.Material.md#roughness)

___

### ShadingModel

• **ShadingModel**: [`EMaterialShadingModel`](../enums/ue_ue.EMaterialShadingModel.md)

#### Inherited from

[Material](ue_ue.Material.md).[ShadingModel](ue_ue.Material.md#shadingmodel)

___

### ShadingModelFromMaterialExpression

• **ShadingModelFromMaterialExpression**: [`ShadingModelMaterialInput`](ue_ue.ShadingModelMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[ShadingModelFromMaterialExpression](ue_ue.Material.md#shadingmodelfrommaterialexpression)

___

### ShadingModels

• **ShadingModels**: [`MaterialShadingModelField`](ue_ue.MaterialShadingModelField.md)

#### Inherited from

[Material](ue_ue.Material.md).[ShadingModels](ue_ue.Material.md#shadingmodels)

___

### Specular

• **Specular**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[Specular](ue_ue.Material.md#specular)

___

### SpecularColor

• **SpecularColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[SpecularColor](ue_ue.Material.md#specularcolor)

___

### StateId

• **StateId**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[Material](ue_ue.Material.md).[StateId](ue_ue.Material.md#stateid)

___

### StencilCompare

• **StencilCompare**: [`EMaterialStencilCompare`](../enums/ue_ue.EMaterialStencilCompare.md)

#### Inherited from

[Material](ue_ue.Material.md).[StencilCompare](ue_ue.Material.md#stencilcompare)

___

### StencilRefValue

• **StencilRefValue**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[StencilRefValue](ue_ue.Material.md#stencilrefvalue)

___

### SubsurfaceColor

• **SubsurfaceColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[SubsurfaceColor](ue_ue.Material.md#subsurfacecolor)

___

### SubsurfaceProfile

• **SubsurfaceProfile**: [`SubsurfaceProfile`](ue_ue.SubsurfaceProfile.md)

#### Inherited from

[Material](ue_ue.Material.md).[SubsurfaceProfile](ue_ue.Material.md#subsurfaceprofile)

___

### TessellationMultiplier

• **TessellationMultiplier**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[TessellationMultiplier](ue_ue.Material.md#tessellationmultiplier)

___

### TextureStreamingData

• **TextureStreamingData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[TextureStreamingData](ue_ue.Material.md#texturestreamingdata)

___

### TextureStreamingDataMissingEntries

• **TextureStreamingDataMissingEntries**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

#### Inherited from

[Material](ue_ue.Material.md).[TextureStreamingDataMissingEntries](ue_ue.Material.md#texturestreamingdatamissingentries)

___

### TextureStreamingDataVersion

• **TextureStreamingDataVersion**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[TextureStreamingDataVersion](ue_ue.Material.md#texturestreamingdataversion)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[Material](ue_ue.Material.md).[ThumbnailInfo](ue_ue.Material.md#thumbnailinfo)

___

### TranslucencyDirectionalLightingIntensity

• **TranslucencyDirectionalLightingIntensity**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[TranslucencyDirectionalLightingIntensity](ue_ue.Material.md#translucencydirectionallightingintensity)

___

### TranslucencyLightingMode

• **TranslucencyLightingMode**: [`ETranslucencyLightingMode`](../enums/ue_ue.ETranslucencyLightingMode.md)

#### Inherited from

[Material](ue_ue.Material.md).[TranslucencyLightingMode](ue_ue.Material.md#translucencylightingmode)

___

### TranslucentBackscatteringExponent

• **TranslucentBackscatteringExponent**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[TranslucentBackscatteringExponent](ue_ue.Material.md#translucentbackscatteringexponent)

___

### TranslucentMultipleScatteringExtinction

• **TranslucentMultipleScatteringExtinction**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[Material](ue_ue.Material.md).[TranslucentMultipleScatteringExtinction](ue_ue.Material.md#translucentmultiplescatteringextinction)

___

### TranslucentSelfShadowDensityScale

• **TranslucentSelfShadowDensityScale**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[TranslucentSelfShadowDensityScale](ue_ue.Material.md#translucentselfshadowdensityscale)

___

### TranslucentSelfShadowSecondDensityScale

• **TranslucentSelfShadowSecondDensityScale**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[TranslucentSelfShadowSecondDensityScale](ue_ue.Material.md#translucentselfshadowseconddensityscale)

___

### TranslucentSelfShadowSecondOpacity

• **TranslucentSelfShadowSecondOpacity**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[TranslucentSelfShadowSecondOpacity](ue_ue.Material.md#translucentselfshadowsecondopacity)

___

### TranslucentShadowDensityScale

• **TranslucentShadowDensityScale**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[TranslucentShadowDensityScale](ue_ue.Material.md#translucentshadowdensityscale)

___

### TranslucentShadowStartOffset

• **TranslucentShadowStartOffset**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[TranslucentShadowStartOffset](ue_ue.Material.md#translucentshadowstartoffset)

___

### TwoSided

• **TwoSided**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[TwoSided](ue_ue.Material.md#twosided)

___

### UsageFlagWarnings

• **UsageFlagWarnings**: `number`

#### Inherited from

[Material](ue_ue.Material.md).[UsageFlagWarnings](ue_ue.Material.md#usageflagwarnings)

___

### UsedShadingModels

• **UsedShadingModels**: `string`

#### Inherited from

[Material](ue_ue.Material.md).[UsedShadingModels](ue_ue.Material.md#usedshadingmodels)

___

### Wireframe

• **Wireframe**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[Wireframe](ue_ue.Material.md#wireframe)

___

### WorldDisplacement

• **WorldDisplacement**: [`VectorMaterialInput`](ue_ue.VectorMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[WorldDisplacement](ue_ue.Material.md#worlddisplacement)

___

### WorldPositionOffset

• **WorldPositionOffset**: [`VectorMaterialInput`](ue_ue.VectorMaterialInput.md)

#### Inherited from

[Material](ue_ue.Material.md).[WorldPositionOffset](ue_ue.Material.md#worldpositionoffset)

___

### \_\_tid\_MaterialInterface\_\_

• **\_\_tid\_MaterialInterface\_\_**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[__tid_MaterialInterface__](ue_ue.Material.md#__tid_materialinterface__)

___

### \_\_tid\_Material\_\_

• **\_\_tid\_Material\_\_**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[__tid_Material__](ue_ue.Material.md#__tid_material__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[__tid_Object__](ue_ue.Material.md#__tid_object__)

___

### \_\_tid\_PreviewMaterial\_\_

• **\_\_tid\_PreviewMaterial\_\_**: `boolean`

___

### bAllowDevelopmentShaderCompile

• **bAllowDevelopmentShaderCompile**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bAllowDevelopmentShaderCompile](ue_ue.Material.md#ballowdevelopmentshadercompile)

___

### bAllowNegativeEmissiveColor

• **bAllowNegativeEmissiveColor**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bAllowNegativeEmissiveColor](ue_ue.Material.md#ballownegativeemissivecolor)

___

### bAutomaticallySetUsageInEditor

• **bAutomaticallySetUsageInEditor**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bAutomaticallySetUsageInEditor](ue_ue.Material.md#bautomaticallysetusageineditor)

___

### bBlockGI

• **bBlockGI**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bBlockGI](ue_ue.Material.md#bblockgi)

___

### bCanMaskedBeAssumedOpaque

• **bCanMaskedBeAssumedOpaque**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bCanMaskedBeAssumedOpaque](ue_ue.Material.md#bcanmaskedbeassumedopaque)

___

### bCastDynamicShadowAsMasked

• **bCastDynamicShadowAsMasked**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bCastDynamicShadowAsMasked](ue_ue.Material.md#bcastdynamicshadowasmasked)

___

### bCastRayTracedShadows

• **bCastRayTracedShadows**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bCastRayTracedShadows](ue_ue.Material.md#bcastraytracedshadows)

___

### bComputeFogPerPixel

• **bComputeFogPerPixel**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bComputeFogPerPixel](ue_ue.Material.md#bcomputefogperpixel)

___

### bContactShadows

• **bContactShadows**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bContactShadows](ue_ue.Material.md#bcontactshadows)

___

### bDisableDepthTest

• **bDisableDepthTest**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bDisableDepthTest](ue_ue.Material.md#bdisabledepthtest)

___

### bEnableAdaptiveTessellation

• **bEnableAdaptiveTessellation**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bEnableAdaptiveTessellation](ue_ue.Material.md#benableadaptivetessellation)

___

### bEnableCrackFreeDisplacement

• **bEnableCrackFreeDisplacement**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bEnableCrackFreeDisplacement](ue_ue.Material.md#benablecrackfreedisplacement)

___

### bEnableMobileSeparateTranslucency

• **bEnableMobileSeparateTranslucency**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bEnableMobileSeparateTranslucency](ue_ue.Material.md#benablemobileseparatetranslucency)

___

### bEnableResponsiveAA

• **bEnableResponsiveAA**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bEnableResponsiveAA](ue_ue.Material.md#benableresponsiveaa)

___

### bEnableSeparateTranslucency

• **bEnableSeparateTranslucency**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bEnableSeparateTranslucency](ue_ue.Material.md#benableseparatetranslucency)

___

### bEnableStencilTest

• **bEnableStencilTest**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bEnableStencilTest](ue_ue.Material.md#benablestenciltest)

___

### bFullyRough

• **bFullyRough**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bFullyRough](ue_ue.Material.md#bfullyrough)

___

### bGenerateSphericalParticleNormals

• **bGenerateSphericalParticleNormals**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bGenerateSphericalParticleNormals](ue_ue.Material.md#bgeneratesphericalparticlenormals)

___

### bIsFunctionPreviewMaterial

• **bIsFunctionPreviewMaterial**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bIsFunctionPreviewMaterial](ue_ue.Material.md#bisfunctionpreviewmaterial)

___

### bIsMasked

• **bIsMasked**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bIsMasked](ue_ue.Material.md#bismasked)

___

### bIsMaterialEditorStatsMaterial

• **bIsMaterialEditorStatsMaterial**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bIsMaterialEditorStatsMaterial](ue_ue.Material.md#bismaterialeditorstatsmaterial)

___

### bIsPreviewMaterial

• **bIsPreviewMaterial**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bIsPreviewMaterial](ue_ue.Material.md#bispreviewmaterial)

___

### bIsSky

• **bIsSky**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bIsSky](ue_ue.Material.md#bissky)

___

### bNormalCurvatureToRoughness

• **bNormalCurvatureToRoughness**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bNormalCurvatureToRoughness](ue_ue.Material.md#bnormalcurvaturetoroughness)

___

### bOutputTranslucentVelocity

• **bOutputTranslucentVelocity**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bOutputTranslucentVelocity](ue_ue.Material.md#boutputtranslucentvelocity)

___

### bOutputVelocityOnBasePass

• **bOutputVelocityOnBasePass**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bOutputVelocityOnBasePass](ue_ue.Material.md#boutputvelocityonbasepass)

___

### bScreenSpaceReflections

• **bScreenSpaceReflections**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bScreenSpaceReflections](ue_ue.Material.md#bscreenspacereflections)

___

### bTangentSpaceNormal

• **bTangentSpaceNormal**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bTangentSpaceNormal](ue_ue.Material.md#btangentspacenormal)

___

### bTextureStreamingDataSorted

• **bTextureStreamingDataSorted**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bTextureStreamingDataSorted](ue_ue.Material.md#btexturestreamingdatasorted)

___

### bUseEmissiveForDynamicAreaLighting

• **bUseEmissiveForDynamicAreaLighting**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUseEmissiveForDynamicAreaLighting](ue_ue.Material.md#buseemissivefordynamicarealighting)

___

### bUseFullPrecision

• **bUseFullPrecision**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUseFullPrecision](ue_ue.Material.md#busefullprecision)

___

### bUseHQForwardReflections

• **bUseHQForwardReflections**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUseHQForwardReflections](ue_ue.Material.md#busehqforwardreflections)

___

### bUseLightmapDirectionality

• **bUseLightmapDirectionality**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUseLightmapDirectionality](ue_ue.Material.md#buselightmapdirectionality)

___

### bUseMaterialAttributes

• **bUseMaterialAttributes**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUseMaterialAttributes](ue_ue.Material.md#busematerialattributes)

___

### bUsePlanarForwardReflections

• **bUsePlanarForwardReflections**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsePlanarForwardReflections](ue_ue.Material.md#buseplanarforwardreflections)

___

### bUseTranslucencyVertexFog

• **bUseTranslucencyVertexFog**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUseTranslucencyVertexFog](ue_ue.Material.md#busetranslucencyvertexfog)

___

### bUsedAsSpecialEngineMaterial

• **bUsedAsSpecialEngineMaterial**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedAsSpecialEngineMaterial](ue_ue.Material.md#busedasspecialenginematerial)

___

### bUsedWithBeamTrails

• **bUsedWithBeamTrails**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithBeamTrails](ue_ue.Material.md#busedwithbeamtrails)

___

### bUsedWithClothing

• **bUsedWithClothing**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithClothing](ue_ue.Material.md#busedwithclothing)

___

### bUsedWithEditorCompositing

• **bUsedWithEditorCompositing**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithEditorCompositing](ue_ue.Material.md#busedwitheditorcompositing)

___

### bUsedWithGeometryCache

• **bUsedWithGeometryCache**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithGeometryCache](ue_ue.Material.md#busedwithgeometrycache)

___

### bUsedWithGeometryCollections

• **bUsedWithGeometryCollections**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithGeometryCollections](ue_ue.Material.md#busedwithgeometrycollections)

___

### bUsedWithHairStrands

• **bUsedWithHairStrands**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithHairStrands](ue_ue.Material.md#busedwithhairstrands)

___

### bUsedWithInstancedStaticMeshes

• **bUsedWithInstancedStaticMeshes**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithInstancedStaticMeshes](ue_ue.Material.md#busedwithinstancedstaticmeshes)

___

### bUsedWithMeshParticles

• **bUsedWithMeshParticles**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithMeshParticles](ue_ue.Material.md#busedwithmeshparticles)

___

### bUsedWithMorphTargets

• **bUsedWithMorphTargets**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithMorphTargets](ue_ue.Material.md#busedwithmorphtargets)

___

### bUsedWithNiagaraMeshParticles

• **bUsedWithNiagaraMeshParticles**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithNiagaraMeshParticles](ue_ue.Material.md#busedwithniagarameshparticles)

___

### bUsedWithNiagaraRibbons

• **bUsedWithNiagaraRibbons**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithNiagaraRibbons](ue_ue.Material.md#busedwithniagararibbons)

___

### bUsedWithNiagaraSprites

• **bUsedWithNiagaraSprites**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithNiagaraSprites](ue_ue.Material.md#busedwithniagarasprites)

___

### bUsedWithParticleSprites

• **bUsedWithParticleSprites**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithParticleSprites](ue_ue.Material.md#busedwithparticlesprites)

___

### bUsedWithSkeletalMesh

• **bUsedWithSkeletalMesh**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithSkeletalMesh](ue_ue.Material.md#busedwithskeletalmesh)

___

### bUsedWithSplineMeshes

• **bUsedWithSplineMeshes**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithSplineMeshes](ue_ue.Material.md#busedwithsplinemeshes)

___

### bUsedWithStaticLighting

• **bUsedWithStaticLighting**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithStaticLighting](ue_ue.Material.md#busedwithstaticlighting)

___

### bUsedWithUI

• **bUsedWithUI**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithUI](ue_ue.Material.md#busedwithui)

___

### bUsedWithWater

• **bUsedWithWater**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsedWithWater](ue_ue.Material.md#busedwithwater)

___

### bUsesDistortion

• **bUsesDistortion**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bUsesDistortion](ue_ue.Material.md#busesdistortion)

___

### bWriteOnlyAlpha

• **bWriteOnlyAlpha**: `boolean`

#### Inherited from

[Material](ue_ue.Material.md).[bWriteOnlyAlpha](ue_ue.Material.md#bwriteonlyalpha)

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

___

### GetBaseMaterial

▸ **GetBaseMaterial**(): [`Material`](ue_ue.Material.md)

#### Returns

[`Material`](ue_ue.Material.md)

#### Inherited from

[Material](ue_ue.Material.md).[GetBaseMaterial](ue_ue.Material.md#getbasematerial)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Material](ue_ue.Material.md).[GetClass](ue_ue.Material.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Material](ue_ue.Material.md).[GetName](ue_ue.Material.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Material](ue_ue.Material.md).[GetOuter](ue_ue.Material.md#getouter)

___

### GetPhysicalMaterial

▸ **GetPhysicalMaterial**(): [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Returns

[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Inherited from

[Material](ue_ue.Material.md).[GetPhysicalMaterial](ue_ue.Material.md#getphysicalmaterial)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Material](ue_ue.Material.md).[GetWorld](ue_ue.Material.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Material](ue_ue.Material.md).[StaticClass](ue_ue.Material.md#staticclass)
