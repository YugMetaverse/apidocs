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

#### Defined in

[ue/ue.d.ts:1410](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1410)

## Properties

### AllowTranslucentCustomDepthWrites

• **AllowTranslucentCustomDepthWrites**: `boolean`

#### Defined in

[ue/ue.d.ts:1498](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1498)

___

### AmbientOcclusion

• **AmbientOcclusion**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1437](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1437)

___

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[AssetImportData](ue_ue.MaterialInterface.md#assetimportdata)

#### Defined in

[ue/ue.d.ts:1556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1556)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[AssetUserData](ue_ue.MaterialInterface.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:1550](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1550)

___

### BaseColor

• **BaseColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1414](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1414)

___

### BlendMode

• **BlendMode**: [`EBlendMode`](../enums/ue_ue.EBlendMode.md)

#### Defined in

[ue/ue.d.ts:1423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1423)

___

### BlendableLocation

• **BlendableLocation**: [`EBlendableLocation`](../enums/ue_ue.EBlendableLocation.md)

#### Defined in

[ue/ue.d.ts:1522](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1522)

___

### BlendableOutputAlpha

• **BlendableOutputAlpha**: `boolean`

#### Defined in

[ue/ue.d.ts:1523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1523)

___

### BlendablePriority

• **BlendablePriority**: `number`

#### Defined in

[ue/ue.d.ts:1528](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1528)

___

### CachedQualityLevelsUsed

• **CachedQualityLevelsUsed**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\>

#### Defined in

[ue/ue.d.ts:1533](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1533)

___

### ClearCoat

• **ClearCoat**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1435](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1435)

___

### ClearCoatRoughness

• **ClearCoatRoughness**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1436](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1436)

___

### CustomizedUVs

• **CustomizedUVs**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`Vector2MaterialInput`](ue_ue.Vector2MaterialInput.md)\>

#### Defined in

[ue/ue.d.ts:1439](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1439)

___

### D3D11TessellationMode

• **D3D11TessellationMode**: [`EMaterialTessellationMode`](../enums/ue_ue.EMaterialTessellationMode.md)

#### Defined in

[ue/ue.d.ts:1495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1495)

___

### DecalBlendMode

• **DecalBlendMode**: [`EDecalBlendMode`](../enums/ue_ue.EDecalBlendMode.md)

#### Defined in

[ue/ue.d.ts:1424](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1424)

___

### DiffuseColor

• **DiffuseColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1412](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1412)

___

### DitherOpacityMask

• **DitherOpacityMask**: `boolean`

#### Defined in

[ue/ue.d.ts:1449](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1449)

___

### DitheredLODTransition

• **DitheredLODTransition**: `boolean`

#### Defined in

[ue/ue.d.ts:1448](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1448)

___

### EditorComments

• **EditorComments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialExpressionComment`](ue_ue.MaterialExpressionComment.md)\>

#### Defined in

[ue/ue.d.ts:1506](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1506)

___

### EditorPitch

• **EditorPitch**: `number`

#### Defined in

[ue/ue.d.ts:1503](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1503)

___

### EditorX

• **EditorX**: `number`

#### Defined in

[ue/ue.d.ts:1501](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1501)

___

### EditorY

• **EditorY**: `number`

#### Defined in

[ue/ue.d.ts:1502](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1502)

___

### EditorYaw

• **EditorYaw**: `number`

#### Defined in

[ue/ue.d.ts:1504](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1504)

___

### EmissiveColor

• **EmissiveColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1419](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1419)

___

### ExpressionTextureReferences

• **ExpressionTextureReferences**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:1534](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1534)

___

### Expressions

• **Expressions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialExpression`](ue_ue.MaterialExpression.md)\>

#### Defined in

[ue/ue.d.ts:1505](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1505)

___

### LayerParameterExpansion

• **LayerParameterExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[LayerParameterExpansion](ue_ue.MaterialInterface.md#layerparameterexpansion)

#### Defined in

[ue/ue.d.ts:1554](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1554)

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[LightingGuid](ue_ue.MaterialInterface.md#lightingguid)

#### Defined in

[ue/ue.d.ts:1557](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1557)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassMaterialInterfaceSettings`](ue_ue.LightmassMaterialInterfaceSettings.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[LightmassSettings](ue_ue.MaterialInterface.md#lightmasssettings)

#### Defined in

[ue/ue.d.ts:1546](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1546)

___

### MaterialAttributes

• **MaterialAttributes**: [`MaterialAttributesInput`](ue_ue.MaterialAttributesInput.md)

#### Defined in

[ue/ue.d.ts:1440](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1440)

___

### MaterialDecalResponse

• **MaterialDecalResponse**: [`EMaterialDecalResponse`](../enums/ue_ue.EMaterialDecalResponse.md)

#### Defined in

[ue/ue.d.ts:1425](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1425)

___

### MaterialDomain

• **MaterialDomain**: [`EMaterialDomain`](../enums/ue_ue.EMaterialDomain.md)

#### Defined in

[ue/ue.d.ts:1422](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1422)

___

### MaterialFunctionInfos

• **MaterialFunctionInfos**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialFunctionInfo`](ue_ue.MaterialFunctionInfo.md)\>

#### Defined in

[ue/ue.d.ts:1508](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1508)

___

### MaterialParameterCollectionInfos

• **MaterialParameterCollectionInfos**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialParameterCollectionInfo`](ue_ue.MaterialParameterCollectionInfo.md)\>

#### Defined in

[ue/ue.d.ts:1509](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1509)

___

### MaxDisplacement

• **MaxDisplacement**: `number`

#### Defined in

[ue/ue.d.ts:1532](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1532)

___

### Metallic

• **Metallic**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1415](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1415)

___

### Normal

• **Normal**: [`VectorMaterialInput`](ue_ue.VectorMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1418)

___

### NumCustomizedUVs

• **NumCustomizedUVs**: `number`

#### Defined in

[ue/ue.d.ts:1453](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1453)

___

### Opacity

• **Opacity**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1420](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1420)

___

### OpacityMask

• **OpacityMask**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1421](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1421)

___

### OpacityMaskClipValue

• **OpacityMaskClipValue**: `number`

#### Defined in

[ue/ue.d.ts:1430](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1430)

___

### ParameterGroupData

• **ParameterGroupData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParameterGroupData`](ue_ue.ParameterGroupData.md)\>

#### Defined in

[ue/ue.d.ts:1507](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1507)

___

### ParameterOverviewExpansion

• **ParameterOverviewExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[ParameterOverviewExpansion](ue_ue.MaterialInterface.md#parameteroverviewexpansion)

#### Defined in

[ue/ue.d.ts:1555](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1555)

___

### PhysMaterial

• **PhysMaterial**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Defined in

[ue/ue.d.ts:1411](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1411)

___

### PixelDepthOffset

• **PixelDepthOffset**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1441](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1441)

___

### PreviewMesh

• **PreviewMesh**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[PreviewMesh](ue_ue.MaterialInterface.md#previewmesh)

#### Defined in

[ue/ue.d.ts:1552](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1552)

___

### ReferencedTextureGuids

• **ReferencedTextureGuids**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

#### Defined in

[ue/ue.d.ts:1535](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1535)

___

### Refraction

• **Refraction**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1438](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1438)

___

### RefractionDepthBias

• **RefractionDepthBias**: `number`

#### Defined in

[ue/ue.d.ts:1530](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1530)

___

### RefractionMode

• **RefractionMode**: [`ERefractionMode`](../enums/ue_ue.ERefractionMode.md)

#### Defined in

[ue/ue.d.ts:1527](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1527)

___

### Roughness

• **Roughness**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1417](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1417)

___

### ShadingModel

• **ShadingModel**: [`EMaterialShadingModel`](../enums/ue_ue.EMaterialShadingModel.md)

#### Defined in

[ue/ue.d.ts:1426](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1426)

___

### ShadingModelFromMaterialExpression

• **ShadingModelFromMaterialExpression**: [`ShadingModelMaterialInput`](ue_ue.ShadingModelMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1442](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1442)

___

### ShadingModels

• **ShadingModels**: [`MaterialShadingModelField`](ue_ue.MaterialShadingModelField.md)

#### Defined in

[ue/ue.d.ts:1428](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1428)

___

### Specular

• **Specular**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1416](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1416)

___

### SpecularColor

• **SpecularColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1413](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1413)

___

### StateId

• **StateId**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:1531](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1531)

___

### StencilCompare

• **StencilCompare**: [`EMaterialStencilCompare`](../enums/ue_ue.EMaterialStencilCompare.md)

#### Defined in

[ue/ue.d.ts:1525](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1525)

___

### StencilRefValue

• **StencilRefValue**: `number`

#### Defined in

[ue/ue.d.ts:1526](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1526)

___

### SubsurfaceColor

• **SubsurfaceColor**: [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1434](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1434)

___

### SubsurfaceProfile

• **SubsurfaceProfile**: [`SubsurfaceProfile`](ue_ue.SubsurfaceProfile.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[SubsurfaceProfile](ue_ue.MaterialInterface.md#subsurfaceprofile)

#### Defined in

[ue/ue.d.ts:1545](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1545)

___

### TessellationMultiplier

• **TessellationMultiplier**: [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1433](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1433)

___

### TextureStreamingData

• **TextureStreamingData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[TextureStreamingData](ue_ue.MaterialInterface.md#texturestreamingdata)

#### Defined in

[ue/ue.d.ts:1549](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1549)

___

### TextureStreamingDataMissingEntries

• **TextureStreamingDataMissingEntries**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[TextureStreamingDataMissingEntries](ue_ue.MaterialInterface.md#texturestreamingdatamissingentries)

#### Defined in

[ue/ue.d.ts:1551](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1551)

___

### TextureStreamingDataVersion

• **TextureStreamingDataVersion**: `number`

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[TextureStreamingDataVersion](ue_ue.MaterialInterface.md#texturestreamingdataversion)

#### Defined in

[ue/ue.d.ts:1548](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1548)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[ThumbnailInfo](ue_ue.MaterialInterface.md#thumbnailinfo)

#### Defined in

[ue/ue.d.ts:1553](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1553)

___

### TranslucencyDirectionalLightingIntensity

• **TranslucencyDirectionalLightingIntensity**: `number`

#### Defined in

[ue/ue.d.ts:1454](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1454)

___

### TranslucencyLightingMode

• **TranslucencyLightingMode**: [`ETranslucencyLightingMode`](../enums/ue_ue.ETranslucencyLightingMode.md)

#### Defined in

[ue/ue.d.ts:1451](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1451)

___

### TranslucentBackscatteringExponent

• **TranslucentBackscatteringExponent**: `number`

#### Defined in

[ue/ue.d.ts:1459](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1459)

___

### TranslucentMultipleScatteringExtinction

• **TranslucentMultipleScatteringExtinction**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:1460](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1460)

___

### TranslucentSelfShadowDensityScale

• **TranslucentSelfShadowDensityScale**: `number`

#### Defined in

[ue/ue.d.ts:1456](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1456)

___

### TranslucentSelfShadowSecondDensityScale

• **TranslucentSelfShadowSecondDensityScale**: `number`

#### Defined in

[ue/ue.d.ts:1457](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1457)

___

### TranslucentSelfShadowSecondOpacity

• **TranslucentSelfShadowSecondOpacity**: `number`

#### Defined in

[ue/ue.d.ts:1458](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1458)

___

### TranslucentShadowDensityScale

• **TranslucentShadowDensityScale**: `number`

#### Defined in

[ue/ue.d.ts:1455](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1455)

___

### TranslucentShadowStartOffset

• **TranslucentShadowStartOffset**: `number`

#### Defined in

[ue/ue.d.ts:1461](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1461)

___

### TwoSided

• **TwoSided**: `boolean`

#### Defined in

[ue/ue.d.ts:1447](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1447)

___

### UsageFlagWarnings

• **UsageFlagWarnings**: `number`

#### Defined in

[ue/ue.d.ts:1529](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1529)

___

### UsedShadingModels

• **UsedShadingModels**: `string`

#### Defined in

[ue/ue.d.ts:1429](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1429)

___

### Wireframe

• **Wireframe**: `boolean`

#### Defined in

[ue/ue.d.ts:1499](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1499)

___

### WorldDisplacement

• **WorldDisplacement**: [`VectorMaterialInput`](ue_ue.VectorMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1432](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1432)

___

### WorldPositionOffset

• **WorldPositionOffset**: [`VectorMaterialInput`](ue_ue.VectorMaterialInput.md)

#### Defined in

[ue/ue.d.ts:1431](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1431)

___

### \_\_tid\_MaterialInterface\_\_

• **\_\_tid\_MaterialInterface\_\_**: `boolean`

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[__tid_MaterialInterface__](ue_ue.MaterialInterface.md#__tid_materialinterface__)

#### Defined in

[ue/ue.d.ts:1565](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1565)

___

### \_\_tid\_Material\_\_

• **\_\_tid\_Material\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:1540](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1540)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[__tid_Object__](ue_ue.MaterialInterface.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAllowDevelopmentShaderCompile

• **bAllowDevelopmentShaderCompile**: `boolean`

#### Defined in

[ue/ue.d.ts:1520](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1520)

___

### bAllowNegativeEmissiveColor

• **bAllowNegativeEmissiveColor**: `boolean`

#### Defined in

[ue/ue.d.ts:1450](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1450)

___

### bAutomaticallySetUsageInEditor

• **bAutomaticallySetUsageInEditor**: `boolean`

#### Defined in

[ue/ue.d.ts:1488](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1488)

___

### bBlockGI

• **bBlockGI**: `boolean`

#### Defined in

[ue/ue.d.ts:1467](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1467)

___

### bCanMaskedBeAssumedOpaque

• **bCanMaskedBeAssumedOpaque**: `boolean`

#### Defined in

[ue/ue.d.ts:1510](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1510)

___

### bCastDynamicShadowAsMasked

• **bCastDynamicShadowAsMasked**: `boolean`

#### Defined in

[ue/ue.d.ts:1427](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1427)

___

### bCastRayTracedShadows

• **bCastRayTracedShadows**: `boolean`

#### Defined in

[ue/ue.d.ts:1515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1515)

___

### bComputeFogPerPixel

• **bComputeFogPerPixel**: `boolean`

#### Defined in

[ue/ue.d.ts:1518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1518)

___

### bContactShadows

• **bContactShadows**: `boolean`

#### Defined in

[ue/ue.d.ts:1446](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1446)

___

### bDisableDepthTest

• **bDisableDepthTest**: `boolean`

#### Defined in

[ue/ue.d.ts:1462](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1462)

___

### bEnableAdaptiveTessellation

• **bEnableAdaptiveTessellation**: `boolean`

#### Defined in

[ue/ue.d.ts:1497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1497)

___

### bEnableCrackFreeDisplacement

• **bEnableCrackFreeDisplacement**: `boolean`

#### Defined in

[ue/ue.d.ts:1496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1496)

___

### bEnableMobileSeparateTranslucency

• **bEnableMobileSeparateTranslucency**: `boolean`

#### Defined in

[ue/ue.d.ts:1452](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1452)

___

### bEnableResponsiveAA

• **bEnableResponsiveAA**: `boolean`

#### Defined in

[ue/ue.d.ts:1444](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1444)

___

### bEnableSeparateTranslucency

• **bEnableSeparateTranslucency**: `boolean`

#### Defined in

[ue/ue.d.ts:1443](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1443)

___

### bEnableStencilTest

• **bEnableStencilTest**: `boolean`

#### Defined in

[ue/ue.d.ts:1524](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1524)

___

### bFullyRough

• **bFullyRough**: `boolean`

#### Defined in

[ue/ue.d.ts:1489](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1489)

___

### bGenerateSphericalParticleNormals

• **bGenerateSphericalParticleNormals**: `boolean`

#### Defined in

[ue/ue.d.ts:1464](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1464)

___

### bIsFunctionPreviewMaterial

• **bIsFunctionPreviewMaterial**: `boolean`

#### Defined in

[ue/ue.d.ts:1513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1513)

___

### bIsMasked

• **bIsMasked**: `boolean`

#### Defined in

[ue/ue.d.ts:1511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1511)

___

### bIsMaterialEditorStatsMaterial

• **bIsMaterialEditorStatsMaterial**: `boolean`

#### Defined in

[ue/ue.d.ts:1521](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1521)

___

### bIsPreviewMaterial

• **bIsPreviewMaterial**: `boolean`

#### Defined in

[ue/ue.d.ts:1512](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1512)

___

### bIsSky

• **bIsSky**: `boolean`

#### Defined in

[ue/ue.d.ts:1517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1517)

___

### bNormalCurvatureToRoughness

• **bNormalCurvatureToRoughness**: `boolean`

#### Defined in

[ue/ue.d.ts:1494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1494)

___

### bOutputTranslucentVelocity

• **bOutputTranslucentVelocity**: `boolean`

#### Defined in

[ue/ue.d.ts:1519](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1519)

___

### bOutputVelocityOnBasePass

• **bOutputVelocityOnBasePass**: `boolean`

#### Defined in

[ue/ue.d.ts:1500](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1500)

___

### bScreenSpaceReflections

• **bScreenSpaceReflections**: `boolean`

#### Defined in

[ue/ue.d.ts:1445](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1445)

___

### bTangentSpaceNormal

• **bTangentSpaceNormal**: `boolean`

#### Defined in

[ue/ue.d.ts:1465](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1465)

___

### bTextureStreamingDataSorted

• **bTextureStreamingDataSorted**: `boolean`

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[bTextureStreamingDataSorted](ue_ue.MaterialInterface.md#btexturestreamingdatasorted)

#### Defined in

[ue/ue.d.ts:1547](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1547)

___

### bUseEmissiveForDynamicAreaLighting

• **bUseEmissiveForDynamicAreaLighting**: `boolean`

#### Defined in

[ue/ue.d.ts:1466](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1466)

___

### bUseFullPrecision

• **bUseFullPrecision**: `boolean`

#### Defined in

[ue/ue.d.ts:1490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1490)

___

### bUseHQForwardReflections

• **bUseHQForwardReflections**: `boolean`

#### Defined in

[ue/ue.d.ts:1492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1492)

___

### bUseLightmapDirectionality

• **bUseLightmapDirectionality**: `boolean`

#### Defined in

[ue/ue.d.ts:1491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1491)

___

### bUseMaterialAttributes

• **bUseMaterialAttributes**: `boolean`

#### Defined in

[ue/ue.d.ts:1514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1514)

___

### bUsePlanarForwardReflections

• **bUsePlanarForwardReflections**: `boolean`

#### Defined in

[ue/ue.d.ts:1493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1493)

___

### bUseTranslucencyVertexFog

• **bUseTranslucencyVertexFog**: `boolean`

#### Defined in

[ue/ue.d.ts:1516](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1516)

___

### bUsedAsSpecialEngineMaterial

• **bUsedAsSpecialEngineMaterial**: `boolean`

#### Defined in

[ue/ue.d.ts:1468](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1468)

___

### bUsedWithBeamTrails

• **bUsedWithBeamTrails**: `boolean`

#### Defined in

[ue/ue.d.ts:1472](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1472)

___

### bUsedWithClothing

• **bUsedWithClothing**: `boolean`

#### Defined in

[ue/ue.d.ts:1484](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1484)

___

### bUsedWithEditorCompositing

• **bUsedWithEditorCompositing**: `boolean`

#### Defined in

[ue/ue.d.ts:1470](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1470)

___

### bUsedWithGeometryCache

• **bUsedWithGeometryCache**: `boolean`

#### Defined in

[ue/ue.d.ts:1477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1477)

___

### bUsedWithGeometryCollections

• **bUsedWithGeometryCollections**: `boolean`

#### Defined in

[ue/ue.d.ts:1482](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1482)

___

### bUsedWithHairStrands

• **bUsedWithHairStrands**: `boolean`

#### Defined in

[ue/ue.d.ts:1486](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1486)

___

### bUsedWithInstancedStaticMeshes

• **bUsedWithInstancedStaticMeshes**: `boolean`

#### Defined in

[ue/ue.d.ts:1481](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1481)

___

### bUsedWithMeshParticles

• **bUsedWithMeshParticles**: `boolean`

#### Defined in

[ue/ue.d.ts:1473](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1473)

___

### bUsedWithMorphTargets

• **bUsedWithMorphTargets**: `boolean`

#### Defined in

[ue/ue.d.ts:1479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1479)

___

### bUsedWithNiagaraMeshParticles

• **bUsedWithNiagaraMeshParticles**: `boolean`

#### Defined in

[ue/ue.d.ts:1476](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1476)

___

### bUsedWithNiagaraRibbons

• **bUsedWithNiagaraRibbons**: `boolean`

#### Defined in

[ue/ue.d.ts:1475](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1475)

___

### bUsedWithNiagaraSprites

• **bUsedWithNiagaraSprites**: `boolean`

#### Defined in

[ue/ue.d.ts:1474](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1474)

___

### bUsedWithParticleSprites

• **bUsedWithParticleSprites**: `boolean`

#### Defined in

[ue/ue.d.ts:1471](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1471)

___

### bUsedWithSkeletalMesh

• **bUsedWithSkeletalMesh**: `boolean`

#### Defined in

[ue/ue.d.ts:1469](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1469)

___

### bUsedWithSplineMeshes

• **bUsedWithSplineMeshes**: `boolean`

#### Defined in

[ue/ue.d.ts:1480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1480)

___

### bUsedWithStaticLighting

• **bUsedWithStaticLighting**: `boolean`

#### Defined in

[ue/ue.d.ts:1478](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1478)

___

### bUsedWithUI

• **bUsedWithUI**: `boolean`

#### Defined in

[ue/ue.d.ts:1487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1487)

___

### bUsedWithWater

• **bUsedWithWater**: `boolean`

#### Defined in

[ue/ue.d.ts:1485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1485)

___

### bUsesDistortion

• **bUsesDistortion**: `boolean`

#### Defined in

[ue/ue.d.ts:1483](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1483)

___

### bWriteOnlyAlpha

• **bWriteOnlyAlpha**: `boolean`

#### Defined in

[ue/ue.d.ts:1463](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1463)

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

[MaterialInterface](ue_ue.MaterialInterface.md).[ExecuteUbergraph](ue_ue.MaterialInterface.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetBaseMaterial

▸ **GetBaseMaterial**(): [`Material`](ue_ue.Material.md)

#### Returns

[`Material`](ue_ue.Material.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetBaseMaterial](ue_ue.MaterialInterface.md#getbasematerial)

#### Defined in

[ue/ue.d.ts:1558](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1558)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetClass](ue_ue.MaterialInterface.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetName](ue_ue.MaterialInterface.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetOuter](ue_ue.MaterialInterface.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetPhysicalMaterial

▸ **GetPhysicalMaterial**(): [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Returns

[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetPhysicalMaterial](ue_ue.MaterialInterface.md#getphysicalmaterial)

#### Defined in

[ue/ue.d.ts:1559](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1559)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetWorld](ue_ue.MaterialInterface.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:1560](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1560)

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

#### Defined in

[ue/ue.d.ts:1537](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1537)

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

#### Defined in

[ue/ue.d.ts:1538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1538)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialInterface](ue_ue.MaterialInterface.md).[StaticClass](ue_ue.MaterialInterface.md#staticclass)

#### Defined in

[ue/ue.d.ts:1536](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1536)
