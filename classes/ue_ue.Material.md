[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Material

# Class: Material

[ue/ue](../modules/ue_ue.md).Material

## Hierarchy

- [`MaterialInterface`](ue_ue.MaterialInterface.md)

  ↳ **`Material`**

  ↳↳ [`PreviewMaterial`](ue_ue.PreviewMaterial.md)

## Table of contents

### Constructors

- [constructor](ue_ue.Material.md#constructor)

### Properties

- [AllowTranslucentCustomDepthWrites](ue_ue.Material.md#allowtranslucentcustomdepthwrites)
- [AmbientOcclusion](ue_ue.Material.md#ambientocclusion)
- [AssetImportData](ue_ue.Material.md#assetimportdata)
- [AssetUserData](ue_ue.Material.md#assetuserdata)
- [BaseColor](ue_ue.Material.md#basecolor)
- [BlendMode](ue_ue.Material.md#blendmode)
- [BlendableLocation](ue_ue.Material.md#blendablelocation)
- [BlendableOutputAlpha](ue_ue.Material.md#blendableoutputalpha)
- [BlendablePriority](ue_ue.Material.md#blendablepriority)
- [CachedQualityLevelsUsed](ue_ue.Material.md#cachedqualitylevelsused)
- [ClearCoat](ue_ue.Material.md#clearcoat)
- [ClearCoatRoughness](ue_ue.Material.md#clearcoatroughness)
- [CustomizedUVs](ue_ue.Material.md#customizeduvs)
- [D3D11TessellationMode](ue_ue.Material.md#d3d11tessellationmode)
- [DecalBlendMode](ue_ue.Material.md#decalblendmode)
- [DiffuseColor](ue_ue.Material.md#diffusecolor)
- [DitherOpacityMask](ue_ue.Material.md#ditheropacitymask)
- [DitheredLODTransition](ue_ue.Material.md#ditheredlodtransition)
- [EditorComments](ue_ue.Material.md#editorcomments)
- [EditorPitch](ue_ue.Material.md#editorpitch)
- [EditorX](ue_ue.Material.md#editorx)
- [EditorY](ue_ue.Material.md#editory)
- [EditorYaw](ue_ue.Material.md#editoryaw)
- [EmissiveColor](ue_ue.Material.md#emissivecolor)
- [ExpressionTextureReferences](ue_ue.Material.md#expressiontexturereferences)
- [Expressions](ue_ue.Material.md#expressions)
- [LayerParameterExpansion](ue_ue.Material.md#layerparameterexpansion)
- [LightingGuid](ue_ue.Material.md#lightingguid)
- [LightmassSettings](ue_ue.Material.md#lightmasssettings)
- [MaterialAttributes](ue_ue.Material.md#materialattributes)
- [MaterialDecalResponse](ue_ue.Material.md#materialdecalresponse)
- [MaterialDomain](ue_ue.Material.md#materialdomain)
- [MaterialFunctionInfos](ue_ue.Material.md#materialfunctioninfos)
- [MaterialParameterCollectionInfos](ue_ue.Material.md#materialparametercollectioninfos)
- [MaxDisplacement](ue_ue.Material.md#maxdisplacement)
- [Metallic](ue_ue.Material.md#metallic)
- [Normal](ue_ue.Material.md#normal)
- [NumCustomizedUVs](ue_ue.Material.md#numcustomizeduvs)
- [Opacity](ue_ue.Material.md#opacity)
- [OpacityMask](ue_ue.Material.md#opacitymask)
- [OpacityMaskClipValue](ue_ue.Material.md#opacitymaskclipvalue)
- [ParameterGroupData](ue_ue.Material.md#parametergroupdata)
- [ParameterOverviewExpansion](ue_ue.Material.md#parameteroverviewexpansion)
- [PhysMaterial](ue_ue.Material.md#physmaterial)
- [PixelDepthOffset](ue_ue.Material.md#pixeldepthoffset)
- [PreviewMesh](ue_ue.Material.md#previewmesh)
- [ReferencedTextureGuids](ue_ue.Material.md#referencedtextureguids)
- [Refraction](ue_ue.Material.md#refraction)
- [RefractionDepthBias](ue_ue.Material.md#refractiondepthbias)
- [RefractionMode](ue_ue.Material.md#refractionmode)
- [Roughness](ue_ue.Material.md#roughness)
- [ShadingModel](ue_ue.Material.md#shadingmodel)
- [ShadingModelFromMaterialExpression](ue_ue.Material.md#shadingmodelfrommaterialexpression)
- [ShadingModels](ue_ue.Material.md#shadingmodels)
- [Specular](ue_ue.Material.md#specular)
- [SpecularColor](ue_ue.Material.md#specularcolor)
- [StateId](ue_ue.Material.md#stateid)
- [StencilCompare](ue_ue.Material.md#stencilcompare)
- [StencilRefValue](ue_ue.Material.md#stencilrefvalue)
- [SubsurfaceColor](ue_ue.Material.md#subsurfacecolor)
- [SubsurfaceProfile](ue_ue.Material.md#subsurfaceprofile)
- [TessellationMultiplier](ue_ue.Material.md#tessellationmultiplier)
- [TextureStreamingData](ue_ue.Material.md#texturestreamingdata)
- [TextureStreamingDataMissingEntries](ue_ue.Material.md#texturestreamingdatamissingentries)
- [TextureStreamingDataVersion](ue_ue.Material.md#texturestreamingdataversion)
- [ThumbnailInfo](ue_ue.Material.md#thumbnailinfo)
- [TranslucencyDirectionalLightingIntensity](ue_ue.Material.md#translucencydirectionallightingintensity)
- [TranslucencyLightingMode](ue_ue.Material.md#translucencylightingmode)
- [TranslucentBackscatteringExponent](ue_ue.Material.md#translucentbackscatteringexponent)
- [TranslucentMultipleScatteringExtinction](ue_ue.Material.md#translucentmultiplescatteringextinction)
- [TranslucentSelfShadowDensityScale](ue_ue.Material.md#translucentselfshadowdensityscale)
- [TranslucentSelfShadowSecondDensityScale](ue_ue.Material.md#translucentselfshadowseconddensityscale)
- [TranslucentSelfShadowSecondOpacity](ue_ue.Material.md#translucentselfshadowsecondopacity)
- [TranslucentShadowDensityScale](ue_ue.Material.md#translucentshadowdensityscale)
- [TranslucentShadowStartOffset](ue_ue.Material.md#translucentshadowstartoffset)
- [TwoSided](ue_ue.Material.md#twosided)
- [UsageFlagWarnings](ue_ue.Material.md#usageflagwarnings)
- [UsedShadingModels](ue_ue.Material.md#usedshadingmodels)
- [Wireframe](ue_ue.Material.md#wireframe)
- [WorldDisplacement](ue_ue.Material.md#worlddisplacement)
- [WorldPositionOffset](ue_ue.Material.md#worldpositionoffset)
- [\_\_tid\_MaterialInterface\_\_](ue_ue.Material.md#__tid_materialinterface__)
- [\_\_tid\_Material\_\_](ue_ue.Material.md#__tid_material__)
- [\_\_tid\_Object\_\_](ue_ue.Material.md#__tid_object__)
- [bAllowDevelopmentShaderCompile](ue_ue.Material.md#ballowdevelopmentshadercompile)
- [bAllowNegativeEmissiveColor](ue_ue.Material.md#ballownegativeemissivecolor)
- [bAutomaticallySetUsageInEditor](ue_ue.Material.md#bautomaticallysetusageineditor)
- [bBlockGI](ue_ue.Material.md#bblockgi)
- [bCanMaskedBeAssumedOpaque](ue_ue.Material.md#bcanmaskedbeassumedopaque)
- [bCastDynamicShadowAsMasked](ue_ue.Material.md#bcastdynamicshadowasmasked)
- [bCastRayTracedShadows](ue_ue.Material.md#bcastraytracedshadows)
- [bComputeFogPerPixel](ue_ue.Material.md#bcomputefogperpixel)
- [bContactShadows](ue_ue.Material.md#bcontactshadows)
- [bDisableDepthTest](ue_ue.Material.md#bdisabledepthtest)
- [bEnableAdaptiveTessellation](ue_ue.Material.md#benableadaptivetessellation)
- [bEnableCrackFreeDisplacement](ue_ue.Material.md#benablecrackfreedisplacement)
- [bEnableMobileSeparateTranslucency](ue_ue.Material.md#benablemobileseparatetranslucency)
- [bEnableResponsiveAA](ue_ue.Material.md#benableresponsiveaa)
- [bEnableSeparateTranslucency](ue_ue.Material.md#benableseparatetranslucency)
- [bEnableStencilTest](ue_ue.Material.md#benablestenciltest)
- [bFullyRough](ue_ue.Material.md#bfullyrough)
- [bGenerateSphericalParticleNormals](ue_ue.Material.md#bgeneratesphericalparticlenormals)
- [bIsFunctionPreviewMaterial](ue_ue.Material.md#bisfunctionpreviewmaterial)
- [bIsMasked](ue_ue.Material.md#bismasked)
- [bIsMaterialEditorStatsMaterial](ue_ue.Material.md#bismaterialeditorstatsmaterial)
- [bIsPreviewMaterial](ue_ue.Material.md#bispreviewmaterial)
- [bIsSky](ue_ue.Material.md#bissky)
- [bNormalCurvatureToRoughness](ue_ue.Material.md#bnormalcurvaturetoroughness)
- [bOutputTranslucentVelocity](ue_ue.Material.md#boutputtranslucentvelocity)
- [bOutputVelocityOnBasePass](ue_ue.Material.md#boutputvelocityonbasepass)
- [bScreenSpaceReflections](ue_ue.Material.md#bscreenspacereflections)
- [bTangentSpaceNormal](ue_ue.Material.md#btangentspacenormal)
- [bTextureStreamingDataSorted](ue_ue.Material.md#btexturestreamingdatasorted)
- [bUseEmissiveForDynamicAreaLighting](ue_ue.Material.md#buseemissivefordynamicarealighting)
- [bUseFullPrecision](ue_ue.Material.md#busefullprecision)
- [bUseHQForwardReflections](ue_ue.Material.md#busehqforwardreflections)
- [bUseLightmapDirectionality](ue_ue.Material.md#buselightmapdirectionality)
- [bUseMaterialAttributes](ue_ue.Material.md#busematerialattributes)
- [bUsePlanarForwardReflections](ue_ue.Material.md#buseplanarforwardreflections)
- [bUseTranslucencyVertexFog](ue_ue.Material.md#busetranslucencyvertexfog)
- [bUsedAsSpecialEngineMaterial](ue_ue.Material.md#busedasspecialenginematerial)
- [bUsedWithBeamTrails](ue_ue.Material.md#busedwithbeamtrails)
- [bUsedWithClothing](ue_ue.Material.md#busedwithclothing)
- [bUsedWithEditorCompositing](ue_ue.Material.md#busedwitheditorcompositing)
- [bUsedWithGeometryCache](ue_ue.Material.md#busedwithgeometrycache)
- [bUsedWithGeometryCollections](ue_ue.Material.md#busedwithgeometrycollections)
- [bUsedWithHairStrands](ue_ue.Material.md#busedwithhairstrands)
- [bUsedWithInstancedStaticMeshes](ue_ue.Material.md#busedwithinstancedstaticmeshes)
- [bUsedWithMeshParticles](ue_ue.Material.md#busedwithmeshparticles)
- [bUsedWithMorphTargets](ue_ue.Material.md#busedwithmorphtargets)
- [bUsedWithNiagaraMeshParticles](ue_ue.Material.md#busedwithniagarameshparticles)
- [bUsedWithNiagaraRibbons](ue_ue.Material.md#busedwithniagararibbons)
- [bUsedWithNiagaraSprites](ue_ue.Material.md#busedwithniagarasprites)
- [bUsedWithParticleSprites](ue_ue.Material.md#busedwithparticlesprites)
- [bUsedWithSkeletalMesh](ue_ue.Material.md#busedwithskeletalmesh)
- [bUsedWithSplineMeshes](ue_ue.Material.md#busedwithsplinemeshes)
- [bUsedWithStaticLighting](ue_ue.Material.md#busedwithstaticlighting)
- [bUsedWithUI](ue_ue.Material.md#busedwithui)
- [bUsedWithWater](ue_ue.Material.md#busedwithwater)
- [bUsesDistortion](ue_ue.Material.md#busesdistortion)
- [bWriteOnlyAlpha](ue_ue.Material.md#bwriteonlyalpha)

### Methods

- [CreateDefaultSubobject](ue_ue.Material.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Material.md#executeubergraph)
- [GetBaseMaterial](ue_ue.Material.md#getbasematerial)
- [GetClass](ue_ue.Material.md#getclass)
- [GetName](ue_ue.Material.md#getname)
- [GetOuter](ue_ue.Material.md#getouter)
- [GetPhysicalMaterial](ue_ue.Material.md#getphysicalmaterial)
- [GetWorld](ue_ue.Material.md#getworld)
- [SetForceMipLevelsToBeResident](ue_ue.Material.md#setforcemiplevelstoberesident)
- [Find](ue_ue.Material.md#find)
- [Load](ue_ue.Material.md#load)
- [StaticClass](ue_ue.Material.md#staticclass)

## Constructors

### constructor

• **new Material**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MaterialInterface](ue_ue.MaterialInterface.md).[constructor](ue_ue.MaterialInterface.md#constructor)

## Properties

### AllowTranslucentCustomDepthWrites

• **AllowTranslucentCustomDepthWrites**: `boolean`

___

### AmbientOcclusion

• **AmbientOcclusion**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

___

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[AssetImportData](ue_ue.MaterialInterface.md#assetimportdata)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[AssetUserData](ue_ue.MaterialInterface.md#assetuserdata)

___

### BaseColor

• **BaseColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

___

### BlendMode

• **BlendMode**: [`EBlendMode`](../enums/ue_ue.EBlendMode.md)

___

### BlendableLocation

• **BlendableLocation**: [`EBlendableLocation`](../enums/ue_ue.EBlendableLocation.md)

___

### BlendableOutputAlpha

• **BlendableOutputAlpha**: `boolean`

___

### BlendablePriority

• **BlendablePriority**: `number`

___

### CachedQualityLevelsUsed

• **CachedQualityLevelsUsed**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\>

___

### ClearCoat

• **ClearCoat**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

___

### ClearCoatRoughness

• **ClearCoatRoughness**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

___

### CustomizedUVs

• **CustomizedUVs**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`Vector2MaterialInput`](ue_ue.Vector2MaterialInput.md)\>

___

### D3D11TessellationMode

• **D3D11TessellationMode**: [`EMaterialTessellationMode`](../enums/ue_ue.EMaterialTessellationMode.md)

___

### DecalBlendMode

• **DecalBlendMode**: [`EDecalBlendMode`](../enums/ue_ue.EDecalBlendMode.md)

___

### DiffuseColor

• **DiffuseColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

___

### DitherOpacityMask

• **DitherOpacityMask**: `boolean`

___

### DitheredLODTransition

• **DitheredLODTransition**: `boolean`

___

### EditorComments

• **EditorComments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialExpressionComment`](ue_ue.MaterialExpressionComment.md)\>

___

### EditorPitch

• **EditorPitch**: `number`

___

### EditorX

• **EditorX**: `number`

___

### EditorY

• **EditorY**: `number`

___

### EditorYaw

• **EditorYaw**: `number`

___

### EmissiveColor

• **EmissiveColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

___

### ExpressionTextureReferences

• **ExpressionTextureReferences**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

___

### Expressions

• **Expressions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialExpression`](ue_ue.MaterialExpression.md)\>

___

### LayerParameterExpansion

• **LayerParameterExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[LayerParameterExpansion](ue_ue.MaterialInterface.md#layerparameterexpansion)

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[LightingGuid](ue_ue.MaterialInterface.md#lightingguid)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassMaterialInterfaceSettings`](ue_ue.LightmassMaterialInterfaceSettings.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[LightmassSettings](ue_ue.MaterialInterface.md#lightmasssettings)

___

### MaterialAttributes

• **MaterialAttributes**: [`MaterialAttributesInput`](ue_ue.MaterialAttributesInput.md)

___

### MaterialDecalResponse

• **MaterialDecalResponse**: [`EMaterialDecalResponse`](../enums/ue_ue.EMaterialDecalResponse.md)

___

### MaterialDomain

• **MaterialDomain**: [`EMaterialDomain`](../enums/ue_ue.EMaterialDomain.md)

___

### MaterialFunctionInfos

• **MaterialFunctionInfos**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialFunctionInfo`](ue_ue.MaterialFunctionInfo.md)\>

___

### MaterialParameterCollectionInfos

• **MaterialParameterCollectionInfos**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialParameterCollectionInfo`](ue_ue.MaterialParameterCollectionInfo.md)\>

___

### MaxDisplacement

• **MaxDisplacement**: `number`

___

### Metallic

• **Metallic**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

___

### Normal

• **Normal**: [`VectorMaterialInput`](ue_ue.VectorMaterialInput.md)

___

### NumCustomizedUVs

• **NumCustomizedUVs**: `number`

___

### Opacity

• **Opacity**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

___

### OpacityMask

• **OpacityMask**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

___

### OpacityMaskClipValue

• **OpacityMaskClipValue**: `number`

___

### ParameterGroupData

• **ParameterGroupData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParameterGroupData`](ue_ue.ParameterGroupData.md)\>

___

### ParameterOverviewExpansion

• **ParameterOverviewExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[ParameterOverviewExpansion](ue_ue.MaterialInterface.md#parameteroverviewexpansion)

___

### PhysMaterial

• **PhysMaterial**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

___

### PixelDepthOffset

• **PixelDepthOffset**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

___

### PreviewMesh

• **PreviewMesh**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[PreviewMesh](ue_ue.MaterialInterface.md#previewmesh)

___

### ReferencedTextureGuids

• **ReferencedTextureGuids**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

___

### Refraction

• **Refraction**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

___

### RefractionDepthBias

• **RefractionDepthBias**: `number`

___

### RefractionMode

• **RefractionMode**: [`ERefractionMode`](../enums/ue_ue.ERefractionMode.md)

___

### Roughness

• **Roughness**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

___

### ShadingModel

• **ShadingModel**: [`EMaterialShadingModel`](../enums/ue_ue.EMaterialShadingModel.md)

___

### ShadingModelFromMaterialExpression

• **ShadingModelFromMaterialExpression**: [`ShadingModelMaterialInput`](ue_ue.ShadingModelMaterialInput.md)

___

### ShadingModels

• **ShadingModels**: [`MaterialShadingModelField`](ue_ue.MaterialShadingModelField.md)

___

### Specular

• **Specular**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

___

### SpecularColor

• **SpecularColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

___

### StateId

• **StateId**: [`Guid`](ue_ue_s.Guid.md)

___

### StencilCompare

• **StencilCompare**: [`EMaterialStencilCompare`](../enums/ue_ue.EMaterialStencilCompare.md)

___

### StencilRefValue

• **StencilRefValue**: `number`

___

### SubsurfaceColor

• **SubsurfaceColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

___

### SubsurfaceProfile

• **SubsurfaceProfile**: [`SubsurfaceProfile`](ue_ue.SubsurfaceProfile.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[SubsurfaceProfile](ue_ue.MaterialInterface.md#subsurfaceprofile)

___

### TessellationMultiplier

• **TessellationMultiplier**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

___

### TextureStreamingData

• **TextureStreamingData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[TextureStreamingData](ue_ue.MaterialInterface.md#texturestreamingdata)

___

### TextureStreamingDataMissingEntries

• **TextureStreamingDataMissingEntries**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[TextureStreamingDataMissingEntries](ue_ue.MaterialInterface.md#texturestreamingdatamissingentries)

___

### TextureStreamingDataVersion

• **TextureStreamingDataVersion**: `number`

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[TextureStreamingDataVersion](ue_ue.MaterialInterface.md#texturestreamingdataversion)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[ThumbnailInfo](ue_ue.MaterialInterface.md#thumbnailinfo)

___

### TranslucencyDirectionalLightingIntensity

• **TranslucencyDirectionalLightingIntensity**: `number`

___

### TranslucencyLightingMode

• **TranslucencyLightingMode**: [`ETranslucencyLightingMode`](../enums/ue_ue.ETranslucencyLightingMode.md)

___

### TranslucentBackscatteringExponent

• **TranslucentBackscatteringExponent**: `number`

___

### TranslucentMultipleScatteringExtinction

• **TranslucentMultipleScatteringExtinction**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### TranslucentSelfShadowDensityScale

• **TranslucentSelfShadowDensityScale**: `number`

___

### TranslucentSelfShadowSecondDensityScale

• **TranslucentSelfShadowSecondDensityScale**: `number`

___

### TranslucentSelfShadowSecondOpacity

• **TranslucentSelfShadowSecondOpacity**: `number`

___

### TranslucentShadowDensityScale

• **TranslucentShadowDensityScale**: `number`

___

### TranslucentShadowStartOffset

• **TranslucentShadowStartOffset**: `number`

___

### TwoSided

• **TwoSided**: `boolean`

___

### UsageFlagWarnings

• **UsageFlagWarnings**: `number`

___

### UsedShadingModels

• **UsedShadingModels**: `string`

___

### Wireframe

• **Wireframe**: `boolean`

___

### WorldDisplacement

• **WorldDisplacement**: [`VectorMaterialInput`](ue_ue.VectorMaterialInput.md)

___

### WorldPositionOffset

• **WorldPositionOffset**: [`VectorMaterialInput`](ue_ue.VectorMaterialInput.md)

___

### \_\_tid\_MaterialInterface\_\_

• **\_\_tid\_MaterialInterface\_\_**: `boolean`

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[__tid_MaterialInterface__](ue_ue.MaterialInterface.md#__tid_materialinterface__)

___

### \_\_tid\_Material\_\_

• **\_\_tid\_Material\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[__tid_Object__](ue_ue.MaterialInterface.md#__tid_object__)

___

### bAllowDevelopmentShaderCompile

• **bAllowDevelopmentShaderCompile**: `boolean`

___

### bAllowNegativeEmissiveColor

• **bAllowNegativeEmissiveColor**: `boolean`

___

### bAutomaticallySetUsageInEditor

• **bAutomaticallySetUsageInEditor**: `boolean`

___

### bBlockGI

• **bBlockGI**: `boolean`

___

### bCanMaskedBeAssumedOpaque

• **bCanMaskedBeAssumedOpaque**: `boolean`

___

### bCastDynamicShadowAsMasked

• **bCastDynamicShadowAsMasked**: `boolean`

___

### bCastRayTracedShadows

• **bCastRayTracedShadows**: `boolean`

___

### bComputeFogPerPixel

• **bComputeFogPerPixel**: `boolean`

___

### bContactShadows

• **bContactShadows**: `boolean`

___

### bDisableDepthTest

• **bDisableDepthTest**: `boolean`

___

### bEnableAdaptiveTessellation

• **bEnableAdaptiveTessellation**: `boolean`

___

### bEnableCrackFreeDisplacement

• **bEnableCrackFreeDisplacement**: `boolean`

___

### bEnableMobileSeparateTranslucency

• **bEnableMobileSeparateTranslucency**: `boolean`

___

### bEnableResponsiveAA

• **bEnableResponsiveAA**: `boolean`

___

### bEnableSeparateTranslucency

• **bEnableSeparateTranslucency**: `boolean`

___

### bEnableStencilTest

• **bEnableStencilTest**: `boolean`

___

### bFullyRough

• **bFullyRough**: `boolean`

___

### bGenerateSphericalParticleNormals

• **bGenerateSphericalParticleNormals**: `boolean`

___

### bIsFunctionPreviewMaterial

• **bIsFunctionPreviewMaterial**: `boolean`

___

### bIsMasked

• **bIsMasked**: `boolean`

___

### bIsMaterialEditorStatsMaterial

• **bIsMaterialEditorStatsMaterial**: `boolean`

___

### bIsPreviewMaterial

• **bIsPreviewMaterial**: `boolean`

___

### bIsSky

• **bIsSky**: `boolean`

___

### bNormalCurvatureToRoughness

• **bNormalCurvatureToRoughness**: `boolean`

___

### bOutputTranslucentVelocity

• **bOutputTranslucentVelocity**: `boolean`

___

### bOutputVelocityOnBasePass

• **bOutputVelocityOnBasePass**: `boolean`

___

### bScreenSpaceReflections

• **bScreenSpaceReflections**: `boolean`

___

### bTangentSpaceNormal

• **bTangentSpaceNormal**: `boolean`

___

### bTextureStreamingDataSorted

• **bTextureStreamingDataSorted**: `boolean`

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[bTextureStreamingDataSorted](ue_ue.MaterialInterface.md#btexturestreamingdatasorted)

___

### bUseEmissiveForDynamicAreaLighting

• **bUseEmissiveForDynamicAreaLighting**: `boolean`

___

### bUseFullPrecision

• **bUseFullPrecision**: `boolean`

___

### bUseHQForwardReflections

• **bUseHQForwardReflections**: `boolean`

___

### bUseLightmapDirectionality

• **bUseLightmapDirectionality**: `boolean`

___

### bUseMaterialAttributes

• **bUseMaterialAttributes**: `boolean`

___

### bUsePlanarForwardReflections

• **bUsePlanarForwardReflections**: `boolean`

___

### bUseTranslucencyVertexFog

• **bUseTranslucencyVertexFog**: `boolean`

___

### bUsedAsSpecialEngineMaterial

• **bUsedAsSpecialEngineMaterial**: `boolean`

___

### bUsedWithBeamTrails

• **bUsedWithBeamTrails**: `boolean`

___

### bUsedWithClothing

• **bUsedWithClothing**: `boolean`

___

### bUsedWithEditorCompositing

• **bUsedWithEditorCompositing**: `boolean`

___

### bUsedWithGeometryCache

• **bUsedWithGeometryCache**: `boolean`

___

### bUsedWithGeometryCollections

• **bUsedWithGeometryCollections**: `boolean`

___

### bUsedWithHairStrands

• **bUsedWithHairStrands**: `boolean`

___

### bUsedWithInstancedStaticMeshes

• **bUsedWithInstancedStaticMeshes**: `boolean`

___

### bUsedWithMeshParticles

• **bUsedWithMeshParticles**: `boolean`

___

### bUsedWithMorphTargets

• **bUsedWithMorphTargets**: `boolean`

___

### bUsedWithNiagaraMeshParticles

• **bUsedWithNiagaraMeshParticles**: `boolean`

___

### bUsedWithNiagaraRibbons

• **bUsedWithNiagaraRibbons**: `boolean`

___

### bUsedWithNiagaraSprites

• **bUsedWithNiagaraSprites**: `boolean`

___

### bUsedWithParticleSprites

• **bUsedWithParticleSprites**: `boolean`

___

### bUsedWithSkeletalMesh

• **bUsedWithSkeletalMesh**: `boolean`

___

### bUsedWithSplineMeshes

• **bUsedWithSplineMeshes**: `boolean`

___

### bUsedWithStaticLighting

• **bUsedWithStaticLighting**: `boolean`

___

### bUsedWithUI

• **bUsedWithUI**: `boolean`

___

### bUsedWithWater

• **bUsedWithWater**: `boolean`

___

### bUsesDistortion

• **bUsesDistortion**: `boolean`

___

### bWriteOnlyAlpha

• **bWriteOnlyAlpha**: `boolean`

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

[MaterialInterface](ue_ue.MaterialInterface.md).[CreateDefaultSubobject](ue_ue.MaterialInterface.md#createdefaultsubobject)

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

[MaterialInterface](ue_ue.MaterialInterface.md).[ExecuteUbergraph](ue_ue.MaterialInterface.md#executeubergraph)

___

### GetBaseMaterial

▸ **GetBaseMaterial**(): [`Material`](ue_ue.Material.md)

#### Returns

[`Material`](ue_ue.Material.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetBaseMaterial](ue_ue.MaterialInterface.md#getbasematerial)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetClass](ue_ue.MaterialInterface.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetName](ue_ue.MaterialInterface.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetOuter](ue_ue.MaterialInterface.md#getouter)

___

### GetPhysicalMaterial

▸ **GetPhysicalMaterial**(): [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Returns

[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetPhysicalMaterial](ue_ue.MaterialInterface.md#getphysicalmaterial)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetWorld](ue_ue.MaterialInterface.md#getworld)

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

[MaterialInterface](ue_ue.MaterialInterface.md).[SetForceMipLevelsToBeResident](ue_ue.MaterialInterface.md#setforcemiplevelstoberesident)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Material`](ue_ue.Material.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Material`](ue_ue.Material.md)

#### Overrides

[MaterialInterface](ue_ue.MaterialInterface.md).[Find](ue_ue.MaterialInterface.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`Material`](ue_ue.Material.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Material`](ue_ue.Material.md)

#### Overrides

[MaterialInterface](ue_ue.MaterialInterface.md).[Load](ue_ue.MaterialInterface.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialInterface](ue_ue.MaterialInterface.md).[StaticClass](ue_ue.MaterialInterface.md#staticclass)
