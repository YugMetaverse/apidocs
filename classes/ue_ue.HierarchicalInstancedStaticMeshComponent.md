[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / HierarchicalInstancedStaticMeshComponent

# Class: HierarchicalInstancedStaticMeshComponent

[ue/ue](../modules/ue_ue.md).HierarchicalInstancedStaticMeshComponent

## Hierarchy

- [`InstancedStaticMeshComponent`](ue_ue.InstancedStaticMeshComponent.md)

  ↳ **`HierarchicalInstancedStaticMeshComponent`**

  ↳↳ [`FoliageInstancedStaticMeshComponent`](ue_ue.FoliageInstancedStaticMeshComponent.md)

## Table of contents

### Constructors

- [constructor](ue_ue.HierarchicalInstancedStaticMeshComponent.md#constructor)

### Properties

- [AlwaysLoadOnClient](ue_ue.HierarchicalInstancedStaticMeshComponent.md#alwaysloadonclient)
- [AlwaysLoadOnServer](ue_ue.HierarchicalInstancedStaticMeshComponent.md#alwaysloadonserver)
- [AssetUserData](ue_ue.HierarchicalInstancedStaticMeshComponent.md#assetuserdata)
- [AttachChildren](ue_ue.HierarchicalInstancedStaticMeshComponent.md#attachchildren)
- [AttachParent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#attachparent)
- [AttachSocketName](ue_ue.HierarchicalInstancedStaticMeshComponent.md#attachsocketname)
- [BodyInstance](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bodyinstance)
- [BoundsScale](ue_ue.HierarchicalInstancedStaticMeshComponent.md#boundsscale)
- [BuiltInstanceBounds](ue_ue.HierarchicalInstancedStaticMeshComponent.md#builtinstancebounds)
- [CacheMeshExtendedBounds](ue_ue.HierarchicalInstancedStaticMeshComponent.md#cachemeshextendedbounds)
- [CachedMappings](ue_ue.HierarchicalInstancedStaticMeshComponent.md#cachedmappings)
- [CachedMaxDrawDistance](ue_ue.HierarchicalInstancedStaticMeshComponent.md#cachedmaxdrawdistance)
- [CanBeCharacterBase](ue_ue.HierarchicalInstancedStaticMeshComponent.md#canbecharacterbase)
- [CanCharacterStepUpOn](ue_ue.HierarchicalInstancedStaticMeshComponent.md#cancharacterstepupon)
- [CastShadow](ue_ue.HierarchicalInstancedStaticMeshComponent.md#castshadow)
- [ClientAttachedChildren](ue_ue.HierarchicalInstancedStaticMeshComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.HierarchicalInstancedStaticMeshComponent.md#componenttags)
- [ComponentVelocity](ue_ue.HierarchicalInstancedStaticMeshComponent.md#componentvelocity)
- [CreationMethod](ue_ue.HierarchicalInstancedStaticMeshComponent.md#creationmethod)
- [CustomDepthStencilValue](ue_ue.HierarchicalInstancedStaticMeshComponent.md#customdepthstencilvalue)
- [CustomDepthStencilWriteMask](ue_ue.HierarchicalInstancedStaticMeshComponent.md#customdepthstencilwritemask)
- [CustomPrimitiveData](ue_ue.HierarchicalInstancedStaticMeshComponent.md#customprimitivedata)
- [DepthPriorityGroup](ue_ue.HierarchicalInstancedStaticMeshComponent.md#depthprioritygroup)
- [DetailMode](ue_ue.HierarchicalInstancedStaticMeshComponent.md#detailmode)
- [DistanceFieldIndirectShadowMinVisibility](ue_ue.HierarchicalInstancedStaticMeshComponent.md#distancefieldindirectshadowminvisibility)
- [DistanceFieldSelfShadowBias](ue_ue.HierarchicalInstancedStaticMeshComponent.md#distancefieldselfshadowbias)
- [ExcludeForSpecificHLODLevels](ue_ue.HierarchicalInstancedStaticMeshComponent.md#excludeforspecifichlodlevels)
- [ForcedLodModel](ue_ue.HierarchicalInstancedStaticMeshComponent.md#forcedlodmodel)
- [IndirectLightingCacheQuality](ue_ue.HierarchicalInstancedStaticMeshComponent.md#indirectlightingcachequality)
- [InstanceCountToRender](ue_ue.HierarchicalInstancedStaticMeshComponent.md#instancecounttorender)
- [InstanceEndCullDistance](ue_ue.HierarchicalInstancedStaticMeshComponent.md#instanceendculldistance)
- [InstanceReorderTable](ue_ue.HierarchicalInstancedStaticMeshComponent.md#instancereordertable)
- [InstanceStartCullDistance](ue_ue.HierarchicalInstancedStaticMeshComponent.md#instancestartculldistance)
- [InstancingRandomSeed](ue_ue.HierarchicalInstancedStaticMeshComponent.md#instancingrandomseed)
- [IrrelevantLights](ue_ue.HierarchicalInstancedStaticMeshComponent.md#irrelevantlights)
- [LDMaxDrawDistance](ue_ue.HierarchicalInstancedStaticMeshComponent.md#ldmaxdrawdistance)
- [LODData](ue_ue.HierarchicalInstancedStaticMeshComponent.md#loddata)
- [LODParentPrimitive](ue_ue.HierarchicalInstancedStaticMeshComponent.md#lodparentprimitive)
- [LightingChannels](ue_ue.HierarchicalInstancedStaticMeshComponent.md#lightingchannels)
- [LightmapType](ue_ue.HierarchicalInstancedStaticMeshComponent.md#lightmaptype)
- [LightmassSettings](ue_ue.HierarchicalInstancedStaticMeshComponent.md#lightmasssettings)
- [LpvBiasMultiplier](ue_ue.HierarchicalInstancedStaticMeshComponent.md#lpvbiasmultiplier)
- [MaterialIndexPreview](ue_ue.HierarchicalInstancedStaticMeshComponent.md#materialindexpreview)
- [MaterialStreamingRelativeBoxes](ue_ue.HierarchicalInstancedStaticMeshComponent.md#materialstreamingrelativeboxes)
- [MinDrawDistance](ue_ue.HierarchicalInstancedStaticMeshComponent.md#mindrawdistance)
- [MinLOD](ue_ue.HierarchicalInstancedStaticMeshComponent.md#minlod)
- [Mobility](ue_ue.HierarchicalInstancedStaticMeshComponent.md#mobility)
- [MoveIgnoreActors](ue_ue.HierarchicalInstancedStaticMeshComponent.md#moveignoreactors)
- [MoveIgnoreComponents](ue_ue.HierarchicalInstancedStaticMeshComponent.md#moveignorecomponents)
- [NumBuiltInstances](ue_ue.HierarchicalInstancedStaticMeshComponent.md#numbuiltinstances)
- [NumPendingLightmaps](ue_ue.HierarchicalInstancedStaticMeshComponent.md#numpendinglightmaps)
- [OcclusionLayerNumNodes](ue_ue.HierarchicalInstancedStaticMeshComponent.md#occlusionlayernumnodes)
- [OnBeginCursorOver](ue_ue.HierarchicalInstancedStaticMeshComponent.md#onbegincursorover)
- [OnClicked](ue_ue.HierarchicalInstancedStaticMeshComponent.md#onclicked)
- [OnComponentActivated](ue_ue.HierarchicalInstancedStaticMeshComponent.md#oncomponentactivated)
- [OnComponentBeginOverlap](ue_ue.HierarchicalInstancedStaticMeshComponent.md#oncomponentbeginoverlap)
- [OnComponentDeactivated](ue_ue.HierarchicalInstancedStaticMeshComponent.md#oncomponentdeactivated)
- [OnComponentEndOverlap](ue_ue.HierarchicalInstancedStaticMeshComponent.md#oncomponentendoverlap)
- [OnComponentHit](ue_ue.HierarchicalInstancedStaticMeshComponent.md#oncomponenthit)
- [OnComponentSleep](ue_ue.HierarchicalInstancedStaticMeshComponent.md#oncomponentsleep)
- [OnComponentWake](ue_ue.HierarchicalInstancedStaticMeshComponent.md#oncomponentwake)
- [OnEndCursorOver](ue_ue.HierarchicalInstancedStaticMeshComponent.md#onendcursorover)
- [OnInputTouchBegin](ue_ue.HierarchicalInstancedStaticMeshComponent.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.HierarchicalInstancedStaticMeshComponent.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.HierarchicalInstancedStaticMeshComponent.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.HierarchicalInstancedStaticMeshComponent.md#oninputtouchleave)
- [OnReleased](ue_ue.HierarchicalInstancedStaticMeshComponent.md#onreleased)
- [OverriddenLightMapRes](ue_ue.HierarchicalInstancedStaticMeshComponent.md#overriddenlightmapres)
- [OverrideMaterials](ue_ue.HierarchicalInstancedStaticMeshComponent.md#overridematerials)
- [PerInstanceSMData](ue_ue.HierarchicalInstancedStaticMeshComponent.md#perinstancesmdata)
- [PhysicsVolume](ue_ue.HierarchicalInstancedStaticMeshComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.HierarchicalInstancedStaticMeshComponent.md#physicsvolumechangeddelegate)
- [PreviousLODLevel](ue_ue.HierarchicalInstancedStaticMeshComponent.md#previouslodlevel)
- [PrimaryComponentTick](ue_ue.HierarchicalInstancedStaticMeshComponent.md#primarycomponenttick)
- [RelativeLocation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#relativelocation)
- [RelativeRotation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.HierarchicalInstancedStaticMeshComponent.md#relativescale3d)
- [RuntimeVirtualTextures](ue_ue.HierarchicalInstancedStaticMeshComponent.md#runtimevirtualtextures)
- [SectionIndexPreview](ue_ue.HierarchicalInstancedStaticMeshComponent.md#sectionindexpreview)
- [SelectedEditorMaterial](ue_ue.HierarchicalInstancedStaticMeshComponent.md#selectededitormaterial)
- [SelectedEditorSection](ue_ue.HierarchicalInstancedStaticMeshComponent.md#selectededitorsection)
- [SortedInstances](ue_ue.HierarchicalInstancedStaticMeshComponent.md#sortedinstances)
- [StaticMesh](ue_ue.HierarchicalInstancedStaticMeshComponent.md#staticmesh)
- [StaticMeshDerivedDataKey](ue_ue.HierarchicalInstancedStaticMeshComponent.md#staticmeshderiveddatakey)
- [StaticMeshImportVersion](ue_ue.HierarchicalInstancedStaticMeshComponent.md#staticmeshimportversion)
- [StreamingDistanceMultiplier](ue_ue.HierarchicalInstancedStaticMeshComponent.md#streamingdistancemultiplier)
- [StreamingTextureData](ue_ue.HierarchicalInstancedStaticMeshComponent.md#streamingtexturedata)
- [SubDivisionStepSize](ue_ue.HierarchicalInstancedStaticMeshComponent.md#subdivisionstepsize)
- [TranslucencySortPriority](ue_ue.HierarchicalInstancedStaticMeshComponent.md#translucencysortpriority)
- [UCSModifiedProperties](ue_ue.HierarchicalInstancedStaticMeshComponent.md#ucsmodifiedproperties)
- [UnbuiltInstanceBounds](ue_ue.HierarchicalInstancedStaticMeshComponent.md#unbuiltinstancebounds)
- [UnbuiltInstanceBoundsList](ue_ue.HierarchicalInstancedStaticMeshComponent.md#unbuiltinstanceboundslist)
- [ViewOwnerDepthPriorityGroup](ue_ue.HierarchicalInstancedStaticMeshComponent.md#viewownerdepthprioritygroup)
- [VirtualTextureCullMips](ue_ue.HierarchicalInstancedStaticMeshComponent.md#virtualtexturecullmips)
- [VirtualTextureLodBias](ue_ue.HierarchicalInstancedStaticMeshComponent.md#virtualtexturelodbias)
- [VirtualTextureMinCoverage](ue_ue.HierarchicalInstancedStaticMeshComponent.md#virtualtexturemincoverage)
- [VirtualTextureRenderPassType](ue_ue.HierarchicalInstancedStaticMeshComponent.md#virtualtexturerenderpasstype)
- [VisibilityId](ue_ue.HierarchicalInstancedStaticMeshComponent.md#visibilityid)
- [WireframeColorOverride](ue_ue.HierarchicalInstancedStaticMeshComponent.md#wireframecoloroverride)
- [\_\_tid\_ActorComponent\_\_](ue_ue.HierarchicalInstancedStaticMeshComponent.md#__tid_actorcomponent__)
- [\_\_tid\_HierarchicalInstancedStaticMeshComponent\_\_](ue_ue.HierarchicalInstancedStaticMeshComponent.md#__tid_hierarchicalinstancedstaticmeshcomponent__)
- [\_\_tid\_InstancedStaticMeshComponent\_\_](ue_ue.HierarchicalInstancedStaticMeshComponent.md#__tid_instancedstaticmeshcomponent__)
- [\_\_tid\_MeshComponent\_\_](ue_ue.HierarchicalInstancedStaticMeshComponent.md#__tid_meshcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.HierarchicalInstancedStaticMeshComponent.md#__tid_object__)
- [\_\_tid\_PrimitiveComponent\_\_](ue_ue.HierarchicalInstancedStaticMeshComponent.md#__tid_primitivecomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.HierarchicalInstancedStaticMeshComponent.md#__tid_scenecomponent__)
- [\_\_tid\_StaticMeshComponent\_\_](ue_ue.HierarchicalInstancedStaticMeshComponent.md#__tid_staticmeshcomponent__)
- [bAbsoluteLocation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.HierarchicalInstancedStaticMeshComponent.md#babsolutescale)
- [bAffectDistanceFieldLighting](ue_ue.HierarchicalInstancedStaticMeshComponent.md#baffectdistancefieldlighting)
- [bAffectDynamicIndirectLighting](ue_ue.HierarchicalInstancedStaticMeshComponent.md#baffectdynamicindirectlighting)
- [bAllowCullDistanceVolume](ue_ue.HierarchicalInstancedStaticMeshComponent.md#ballowculldistancevolume)
- [bAlwaysCreatePhysicsState](ue_ue.HierarchicalInstancedStaticMeshComponent.md#balwayscreatephysicsstate)
- [bApplyImpulseOnDamage](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bapplyimpulseondamage)
- [bAutoActivate](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bautoactivate)
- [bBatchImpostersAsInstances](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bbatchimpostersasinstances)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bcaneveraffectnavigation)
- [bCastCinematicShadow](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bcastcinematicshadow)
- [bCastDistanceFieldIndirectShadow](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bcastdistancefieldindirectshadow)
- [bCastDynamicShadow](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bcastdynamicshadow)
- [bCastFarShadow](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bcastfarshadow)
- [bCastHiddenShadow](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bcasthiddenshadow)
- [bCastInsetShadow](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bcastinsetshadow)
- [bCastShadowAsTwoSided](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bcastshadowastwosided)
- [bCastStaticShadow](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bcaststaticshadow)
- [bCastVolumetricTranslucentShadow](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bcastvolumetrictranslucentshadow)
- [bComponentToWorldUpdated](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bcreatedbyconstructionscript)
- [bCustomOverrideVertexColorPerLOD](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bcustomoverridevertexcolorperlod)
- [bDisableCollision](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bdisablecollision)
- [bDisallowMeshPaintPerInstance](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bdisallowmeshpaintperinstance)
- [bDisplayVertexColors](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bdisplayvertexcolors)
- [bEditableWhenInherited](ue_ue.HierarchicalInstancedStaticMeshComponent.md#beditablewheninherited)
- [bEnableAutoLODGeneration](ue_ue.HierarchicalInstancedStaticMeshComponent.md#benableautolodgeneration)
- [bEnableDensityScaling](ue_ue.HierarchicalInstancedStaticMeshComponent.md#benabledensityscaling)
- [bEnableMaterialParameterCaching](ue_ue.HierarchicalInstancedStaticMeshComponent.md#benablematerialparametercaching)
- [bEvaluateWorldPositionOffset](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bevaluateworldpositionoffset)
- [bExcludeFromLightAttachmentGroup](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bexcludefromlightattachmentgroup)
- [bForceMipStreaming](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bforcemipstreaming)
- [bForceNavigationObstacle](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bforcenavigationobstacle)
- [bGenerateOverlapEvents](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bgenerateoverlapevents)
- [bHasCustomNavigableGeometry](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bhascustomnavigablegeometry)
- [bHasMotionBlurVelocityMeshes](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bhasmotionblurvelocitymeshes)
- [bHasPerInstanceHitProxies](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bhasperinstancehitproxies)
- [bHiddenInGame](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bhiddeningame)
- [bIgnoreInstanceForTextureStreaming](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bignoreinstancefortexturestreaming)
- [bIgnoreRadialForce](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bignoreradialforce)
- [bIgnoreRadialImpulse](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bignoreradialimpulse)
- [bInstanceComponent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#binstancecomponent)
- [bIsActive](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.HierarchicalInstancedStaticMeshComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bisvisualizationcomponent)
- [bLightAsIfStatic](ue_ue.HierarchicalInstancedStaticMeshComponent.md#blightasifstatic)
- [bLightAttachmentsAsGroup](ue_ue.HierarchicalInstancedStaticMeshComponent.md#blightattachmentsasgroup)
- [bMultiBodyOverlap](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bmultibodyoverlap)
- [bNetAddressable](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bnetaddressable)
- [bNeverDistanceCull](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bneverdistancecull)
- [bOnlyOwnerSee](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bonlyownersee)
- [bOverrideDistanceFieldSelfShadowBias](ue_ue.HierarchicalInstancedStaticMeshComponent.md#boverridedistancefieldselfshadowbias)
- [bOverrideLightMapRes](ue_ue.HierarchicalInstancedStaticMeshComponent.md#boverridelightmapres)
- [bOverrideMinLOD](ue_ue.HierarchicalInstancedStaticMeshComponent.md#boverrideminlod)
- [bOverrideNavigationExport](ue_ue.HierarchicalInstancedStaticMeshComponent.md#boverridenavigationexport)
- [bOverrideWireframeColor](ue_ue.HierarchicalInstancedStaticMeshComponent.md#boverridewireframecolor)
- [bOwnerNoSee](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bownernosee)
- [bReceiveMobileCSMShadows](ue_ue.HierarchicalInstancedStaticMeshComponent.md#breceivemobilecsmshadows)
- [bReceivesDecals](ue_ue.HierarchicalInstancedStaticMeshComponent.md#breceivesdecals)
- [bRenderCustomDepth](ue_ue.HierarchicalInstancedStaticMeshComponent.md#brendercustomdepth)
- [bRenderInDepthPass](ue_ue.HierarchicalInstancedStaticMeshComponent.md#brenderindepthpass)
- [bRenderInMainPass](ue_ue.HierarchicalInstancedStaticMeshComponent.md#brenderinmainpass)
- [bReplicatePhysicsToAutonomousProxy](ue_ue.HierarchicalInstancedStaticMeshComponent.md#breplicatephysicstoautonomousproxy)
- [bReplicates](ue_ue.HierarchicalInstancedStaticMeshComponent.md#breplicates)
- [bReturnMaterialOnMove](ue_ue.HierarchicalInstancedStaticMeshComponent.md#breturnmaterialonmove)
- [bReverseCulling](ue_ue.HierarchicalInstancedStaticMeshComponent.md#breverseculling)
- [bSelectable](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bselectable)
- [bSelfShadowOnly](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bselfshadowonly)
- [bShouldBeAttached](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bshouldupdatephysicsvolume)
- [bSingleSampleShadowFromStationaryLights](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bsinglesampleshadowfromstationarylights)
- [bTraceComplexOnMove](ue_ue.HierarchicalInstancedStaticMeshComponent.md#btracecomplexonmove)
- [bTreatAsBackgroundForOcclusion](ue_ue.HierarchicalInstancedStaticMeshComponent.md#btreatasbackgroundforocclusion)
- [bUseAsOccluder](ue_ue.HierarchicalInstancedStaticMeshComponent.md#buseasoccluder)
- [bUseAttachParentBound](ue_ue.HierarchicalInstancedStaticMeshComponent.md#buseattachparentbound)
- [bUseDefaultCollision](ue_ue.HierarchicalInstancedStaticMeshComponent.md#busedefaultcollision)
- [bUseEditorCompositing](ue_ue.HierarchicalInstancedStaticMeshComponent.md#buseeditorcompositing)
- [bUseMaxLODAsImposter](ue_ue.HierarchicalInstancedStaticMeshComponent.md#busemaxlodasimposter)
- [bUseSubDivisions](ue_ue.HierarchicalInstancedStaticMeshComponent.md#busesubdivisions)
- [bUseViewOwnerDepthPriorityGroup](ue_ue.HierarchicalInstancedStaticMeshComponent.md#buseviewownerdepthprioritygroup)
- [bVisible](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bvisible)
- [bVisibleInRayTracing](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bvisibleinraytracing)
- [bVisibleInReflectionCaptures](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bvisibleinreflectioncaptures)
- [bVisualizeComponent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.HierarchicalInstancedStaticMeshComponent.md#activate)
- [AddAngularImpulse](ue_ue.HierarchicalInstancedStaticMeshComponent.md#addangularimpulse)
- [AddAngularImpulseInDegrees](ue_ue.HierarchicalInstancedStaticMeshComponent.md#addangularimpulseindegrees)
- [AddAngularImpulseInRadians](ue_ue.HierarchicalInstancedStaticMeshComponent.md#addangularimpulseinradians)
- [AddForce](ue_ue.HierarchicalInstancedStaticMeshComponent.md#addforce)
- [AddForceAtLocation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#addforceatlocation)
- [AddForceAtLocationLocal](ue_ue.HierarchicalInstancedStaticMeshComponent.md#addforceatlocationlocal)
- [AddImpulse](ue_ue.HierarchicalInstancedStaticMeshComponent.md#addimpulse)
- [AddImpulseAtLocation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#addimpulseatlocation)
- [AddInstance](ue_ue.HierarchicalInstancedStaticMeshComponent.md#addinstance)
- [AddInstanceWorldSpace](ue_ue.HierarchicalInstancedStaticMeshComponent.md#addinstanceworldspace)
- [AddRadialForce](ue_ue.HierarchicalInstancedStaticMeshComponent.md#addradialforce)
- [AddRadialImpulse](ue_ue.HierarchicalInstancedStaticMeshComponent.md#addradialimpulse)
- [AddTickPrerequisiteActor](ue_ue.HierarchicalInstancedStaticMeshComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#addtickprerequisitecomponent)
- [AddTorque](ue_ue.HierarchicalInstancedStaticMeshComponent.md#addtorque)
- [AddTorqueInDegrees](ue_ue.HierarchicalInstancedStaticMeshComponent.md#addtorqueindegrees)
- [AddTorqueInRadians](ue_ue.HierarchicalInstancedStaticMeshComponent.md#addtorqueinradians)
- [BatchUpdateInstancesTransform](ue_ue.HierarchicalInstancedStaticMeshComponent.md#batchupdateinstancestransform)
- [BatchUpdateInstancesTransforms](ue_ue.HierarchicalInstancedStaticMeshComponent.md#batchupdateinstancestransforms)
- [CanCharacterStepUp](ue_ue.HierarchicalInstancedStaticMeshComponent.md#cancharacterstepup)
- [ClearInstances](ue_ue.HierarchicalInstancedStaticMeshComponent.md#clearinstances)
- [ClearMoveIgnoreActors](ue_ue.HierarchicalInstancedStaticMeshComponent.md#clearmoveignoreactors)
- [ClearMoveIgnoreComponents](ue_ue.HierarchicalInstancedStaticMeshComponent.md#clearmoveignorecomponents)
- [ComponentHasTag](ue_ue.HierarchicalInstancedStaticMeshComponent.md#componenthastag)
- [CopyArrayOfMoveIgnoreActors](ue_ue.HierarchicalInstancedStaticMeshComponent.md#copyarrayofmoveignoreactors)
- [CopyArrayOfMoveIgnoreComponents](ue_ue.HierarchicalInstancedStaticMeshComponent.md#copyarrayofmoveignorecomponents)
- [CreateAndSetMaterialInstanceDynamic](ue_ue.HierarchicalInstancedStaticMeshComponent.md#createandsetmaterialinstancedynamic)
- [CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.HierarchicalInstancedStaticMeshComponent.md#createandsetmaterialinstancedynamicfrommaterial)
- [CreateDefaultSubobject](ue_ue.HierarchicalInstancedStaticMeshComponent.md#createdefaultsubobject)
- [CreateDynamicMaterialInstance](ue_ue.HierarchicalInstancedStaticMeshComponent.md#createdynamicmaterialinstance)
- [Deactivate](ue_ue.HierarchicalInstancedStaticMeshComponent.md#deactivate)
- [DetachFromParent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.HierarchicalInstancedStaticMeshComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.HierarchicalInstancedStaticMeshComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getallsocketnames)
- [GetAngularDamping](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getangulardamping)
- [GetAttachParent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getattachsocketname)
- [GetCenterOfMass](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getcenterofmass)
- [GetChildComponent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getchildrencomponents)
- [GetClass](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getclass)
- [GetClosestPointOnCollision](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getclosestpointoncollision)
- [GetCollisionEnabled](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getcollisionenabled)
- [GetCollisionObjectType](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getcollisionobjecttype)
- [GetCollisionProfileName](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getcollisionprofilename)
- [GetCollisionResponseToChannel](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getcollisionresponsetochannel)
- [GetComponentTickInterval](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getcomponentvelocity)
- [GetForwardVector](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getforwardvector)
- [GetGenerateOverlapEvents](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getgenerateoverlapevents)
- [GetInertiaTensor](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getinertiatensor)
- [GetInstanceCount](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getinstancecount)
- [GetInstanceTransform](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getinstancetransform)
- [GetInstancesOverlappingBox](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getinstancesoverlappingbox)
- [GetInstancesOverlappingSphere](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getinstancesoverlappingsphere)
- [GetLinearDamping](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getlineardamping)
- [GetLocalBounds](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getlocalbounds)
- [GetMass](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getmass)
- [GetMassScale](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getmassscale)
- [GetMaterial](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getmaterial)
- [GetMaterialFromCollisionFaceIndex](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getmaterialfromcollisionfaceindex)
- [GetMaterialIndex](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getmaterialindex)
- [GetMaterialSlotNames](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getmaterialslotnames)
- [GetMaterials](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getmaterials)
- [GetName](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getnumchildrencomponents)
- [GetNumMaterials](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getnummaterials)
- [GetOuter](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getouter)
- [GetOverlappingActors](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getoverlappingcomponents)
- [GetOwner](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getowner)
- [GetParentComponents](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getparentcomponents)
- [GetPhysicsAngularVelocity](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getphysicsangularvelocity)
- [GetPhysicsAngularVelocityInDegrees](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getphysicsangularvelocityindegrees)
- [GetPhysicsAngularVelocityInRadians](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getphysicsangularvelocityinradians)
- [GetPhysicsLinearVelocity](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getphysicslinearvelocity)
- [GetPhysicsLinearVelocityAtPoint](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getphysicslinearvelocityatpoint)
- [GetPhysicsVolume](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getsockettransform)
- [GetUpVector](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getupvector)
- [GetWalkableSlopeOverride](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getwalkableslopeoverride)
- [GetWorld](ue_ue.HierarchicalInstancedStaticMeshComponent.md#getworld)
- [IgnoreActorWhenMoving](ue_ue.HierarchicalInstancedStaticMeshComponent.md#ignoreactorwhenmoving)
- [IgnoreComponentWhenMoving](ue_ue.HierarchicalInstancedStaticMeshComponent.md#ignorecomponentwhenmoving)
- [IsActive](ue_ue.HierarchicalInstancedStaticMeshComponent.md#isactive)
- [IsAnyRigidBodyAwake](ue_ue.HierarchicalInstancedStaticMeshComponent.md#isanyrigidbodyawake)
- [IsAnySimulatingPhysics](ue_ue.HierarchicalInstancedStaticMeshComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.HierarchicalInstancedStaticMeshComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.HierarchicalInstancedStaticMeshComponent.md#iscomponenttickenabled)
- [IsGravityEnabled](ue_ue.HierarchicalInstancedStaticMeshComponent.md#isgravityenabled)
- [IsMaterialSlotNameValid](ue_ue.HierarchicalInstancedStaticMeshComponent.md#ismaterialslotnamevalid)
- [IsOverlappingActor](ue_ue.HierarchicalInstancedStaticMeshComponent.md#isoverlappingactor)
- [IsOverlappingComponent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#isoverlappingcomponent)
- [IsSimulatingPhysics](ue_ue.HierarchicalInstancedStaticMeshComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.HierarchicalInstancedStaticMeshComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_attachtocomponent)
- [K2\_BoxOverlapComponent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_boxoverlapcomponent)
- [K2\_DestroyComponent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_getcomponenttoworld)
- [K2\_IsCollisionEnabled](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_iscollisionenabled)
- [K2\_IsPhysicsCollisionEnabled](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_isphysicscollisionenabled)
- [K2\_IsQueryCollisionEnabled](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_isquerycollisionenabled)
- [K2\_LineTraceComponent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_linetracecomponent)
- [K2\_SetRelativeLocation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_setworldtransform)
- [K2\_SphereOverlapComponent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_sphereoverlapcomponent)
- [K2\_SphereTraceComponent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#k2_spheretracecomponent)
- [OnRep\_AttachChildren](ue_ue.HierarchicalInstancedStaticMeshComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.HierarchicalInstancedStaticMeshComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.HierarchicalInstancedStaticMeshComponent.md#onrep_isactive)
- [OnRep\_StaticMesh](ue_ue.HierarchicalInstancedStaticMeshComponent.md#onrep_staticmesh)
- [OnRep\_Transform](ue_ue.HierarchicalInstancedStaticMeshComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.HierarchicalInstancedStaticMeshComponent.md#onrep_visibility)
- [PrestreamTextures](ue_ue.HierarchicalInstancedStaticMeshComponent.md#prestreamtextures)
- [PutRigidBodyToSleep](ue_ue.HierarchicalInstancedStaticMeshComponent.md#putrigidbodytosleep)
- [ReceiveBeginPlay](ue_ue.HierarchicalInstancedStaticMeshComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.HierarchicalInstancedStaticMeshComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.HierarchicalInstancedStaticMeshComponent.md#receivetick)
- [RegisterComponent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#registercomponent)
- [RemoveInstance](ue_ue.HierarchicalInstancedStaticMeshComponent.md#removeinstance)
- [RemoveInstances](ue_ue.HierarchicalInstancedStaticMeshComponent.md#removeinstances)
- [RemoveTickPrerequisiteActor](ue_ue.HierarchicalInstancedStaticMeshComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.HierarchicalInstancedStaticMeshComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.HierarchicalInstancedStaticMeshComponent.md#resetrelativetransform)
- [ScaleByMomentOfInertia](ue_ue.HierarchicalInstancedStaticMeshComponent.md#scalebymomentofinertia)
- [SetAbsolute](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setabsolute)
- [SetActive](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setactive)
- [SetAllMassScale](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setallmassscale)
- [SetAllPhysicsAngularVelocityInDegrees](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setallphysicsangularvelocityindegrees)
- [SetAllPhysicsAngularVelocityInRadians](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setallphysicsangularvelocityinradians)
- [SetAllPhysicsLinearVelocity](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setallphysicslinearvelocity)
- [SetAllUseCCD](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setalluseccd)
- [SetAngularDamping](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setangulardamping)
- [SetAutoActivate](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setautoactivate)
- [SetBoundsScale](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setboundsscale)
- [SetCastInsetShadow](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setcastinsetshadow)
- [SetCastShadow](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setcastshadow)
- [SetCenterOfMass](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setcenterofmass)
- [SetCollisionEnabled](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setcollisionenabled)
- [SetCollisionObjectType](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setcollisionobjecttype)
- [SetCollisionProfileName](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setcollisionprofilename)
- [SetCollisionResponseToAllChannels](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setcollisionresponsetoallchannels)
- [SetCollisionResponseToChannel](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setcollisionresponsetochannel)
- [SetComponentTickEnabled](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setcomponenttickinterval)
- [SetConstraintMode](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setconstraintmode)
- [SetCullDistance](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setculldistance)
- [SetCullDistances](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setculldistances)
- [SetCustomDepthStencilValue](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setcustomdepthstencilvalue)
- [SetCustomDepthStencilWriteMask](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setcustomdepthstencilwritemask)
- [SetCustomPrimitiveDataFloat](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setcustomprimitivedatafloat)
- [SetCustomPrimitiveDataVector2](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setcustomprimitivedatavector2)
- [SetCustomPrimitiveDataVector3](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setcustomprimitivedatavector3)
- [SetCustomPrimitiveDataVector4](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setcustomprimitivedatavector4)
- [SetDistanceFieldSelfShadowBias](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setdistancefieldselfshadowbias)
- [SetEnableGravity](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setenablegravity)
- [SetExcludeFromLightAttachmentGroup](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setexcludefromlightattachmentgroup)
- [SetForcedLodModel](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setforcedlodmodel)
- [SetGenerateOverlapEvents](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setgenerateoverlapevents)
- [SetHiddenInGame](ue_ue.HierarchicalInstancedStaticMeshComponent.md#sethiddeningame)
- [SetIsReplicated](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setisreplicated)
- [SetLightAttachmentsAsGroup](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setlightattachmentsasgroup)
- [SetLinearDamping](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setlineardamping)
- [SetMassOverrideInKg](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setmassoverrideinkg)
- [SetMassScale](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setmassscale)
- [SetMaterial](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setmaterial)
- [SetMaterialByName](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setmaterialbyname)
- [SetMobility](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setmobility)
- [SetNotifyRigidBodyCollision](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setnotifyrigidbodycollision)
- [SetOnlyOwnerSee](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setonlyownersee)
- [SetOwnerNoSee](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setownernosee)
- [SetPhysMaterialOverride](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setphysmaterialoverride)
- [SetPhysicsAngularVelocity](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setphysicsangularvelocity)
- [SetPhysicsAngularVelocityInDegrees](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setphysicsangularvelocityindegrees)
- [SetPhysicsAngularVelocityInRadians](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setphysicsangularvelocityinradians)
- [SetPhysicsLinearVelocity](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setphysicslinearvelocity)
- [SetPhysicsMaxAngularVelocity](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setphysicsmaxangularvelocity)
- [SetPhysicsMaxAngularVelocityInDegrees](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setphysicsmaxangularvelocityindegrees)
- [SetPhysicsMaxAngularVelocityInRadians](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setphysicsmaxangularvelocityinradians)
- [SetReceivesDecals](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setreceivesdecals)
- [SetRelativeScale3D](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setrelativescale3d)
- [SetRenderCustomDepth](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setrendercustomdepth)
- [SetRenderInMainPass](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setrenderinmainpass)
- [SetReverseCulling](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setreverseculling)
- [SetScalarParameterValueOnMaterials](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setscalarparametervalueonmaterials)
- [SetShouldUpdatePhysicsVolume](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setshouldupdatephysicsvolume)
- [SetSimulatePhysics](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setsimulatephysics)
- [SetSingleSampleShadowFromStationaryLights](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setsinglesampleshadowfromstationarylights)
- [SetStaticMesh](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setstaticmesh)
- [SetTickGroup](ue_ue.HierarchicalInstancedStaticMeshComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.HierarchicalInstancedStaticMeshComponent.md#settickablewhenpaused)
- [SetTranslucentSortPriority](ue_ue.HierarchicalInstancedStaticMeshComponent.md#settranslucentsortpriority)
- [SetUseCCD](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setuseccd)
- [SetVectorParameterValueOnMaterials](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setvectorparametervalueonmaterials)
- [SetVisibility](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setvisibility)
- [SetWalkableSlopeOverride](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setwalkableslopeoverride)
- [SetWorldScale3D](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.HierarchicalInstancedStaticMeshComponent.md#setupattachment)
- [SnapTo](ue_ue.HierarchicalInstancedStaticMeshComponent.md#snapto)
- [ToggleActive](ue_ue.HierarchicalInstancedStaticMeshComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.HierarchicalInstancedStaticMeshComponent.md#togglevisibility)
- [UpdateInstanceTransform](ue_ue.HierarchicalInstancedStaticMeshComponent.md#updateinstancetransform)
- [WakeAllRigidBodies](ue_ue.HierarchicalInstancedStaticMeshComponent.md#wakeallrigidbodies)
- [WakeRigidBody](ue_ue.HierarchicalInstancedStaticMeshComponent.md#wakerigidbody)
- [Find](ue_ue.HierarchicalInstancedStaticMeshComponent.md#find)
- [Load](ue_ue.HierarchicalInstancedStaticMeshComponent.md#load)
- [StaticClass](ue_ue.HierarchicalInstancedStaticMeshComponent.md#staticclass)

## Constructors

### constructor

• **new HierarchicalInstancedStaticMeshComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[constructor](ue_ue.InstancedStaticMeshComponent.md#constructor)

## Properties

### AlwaysLoadOnClient

• **AlwaysLoadOnClient**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AlwaysLoadOnClient](ue_ue.InstancedStaticMeshComponent.md#alwaysloadonclient)

___

### AlwaysLoadOnServer

• **AlwaysLoadOnServer**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AlwaysLoadOnServer](ue_ue.InstancedStaticMeshComponent.md#alwaysloadonserver)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AssetUserData](ue_ue.InstancedStaticMeshComponent.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AttachChildren](ue_ue.InstancedStaticMeshComponent.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AttachParent](ue_ue.InstancedStaticMeshComponent.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AttachSocketName](ue_ue.InstancedStaticMeshComponent.md#attachsocketname)

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[BodyInstance](ue_ue.InstancedStaticMeshComponent.md#bodyinstance)

___

### BoundsScale

• **BoundsScale**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[BoundsScale](ue_ue.InstancedStaticMeshComponent.md#boundsscale)

___

### BuiltInstanceBounds

• **BuiltInstanceBounds**: [`Box`](ue_ue.Box.md)

___

### CacheMeshExtendedBounds

• **CacheMeshExtendedBounds**: [`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

___

### CachedMappings

• **CachedMappings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InstancedStaticMeshMappingInfo`](ue_ue.InstancedStaticMeshMappingInfo.md)\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[CachedMappings](ue_ue.InstancedStaticMeshComponent.md#cachedmappings)

___

### CachedMaxDrawDistance

• **CachedMaxDrawDistance**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[CachedMaxDrawDistance](ue_ue.InstancedStaticMeshComponent.md#cachedmaxdrawdistance)

___

### CanBeCharacterBase

• **CanBeCharacterBase**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[CanBeCharacterBase](ue_ue.InstancedStaticMeshComponent.md#canbecharacterbase)

___

### CanCharacterStepUpOn

• **CanCharacterStepUpOn**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[CanCharacterStepUpOn](ue_ue.InstancedStaticMeshComponent.md#cancharacterstepupon)

___

### CastShadow

• **CastShadow**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[CastShadow](ue_ue.InstancedStaticMeshComponent.md#castshadow)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ClientAttachedChildren](ue_ue.InstancedStaticMeshComponent.md#clientattachedchildren)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ComponentTags](ue_ue.InstancedStaticMeshComponent.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ComponentVelocity](ue_ue.InstancedStaticMeshComponent.md#componentvelocity)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[CreationMethod](ue_ue.InstancedStaticMeshComponent.md#creationmethod)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[CustomDepthStencilValue](ue_ue.InstancedStaticMeshComponent.md#customdepthstencilvalue)

___

### CustomDepthStencilWriteMask

• **CustomDepthStencilWriteMask**: [`ERendererStencilMask`](../enums/ue_ue.ERendererStencilMask.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[CustomDepthStencilWriteMask](ue_ue.InstancedStaticMeshComponent.md#customdepthstencilwritemask)

___

### CustomPrimitiveData

• **CustomPrimitiveData**: [`CustomPrimitiveData`](ue_ue.CustomPrimitiveData.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[CustomPrimitiveData](ue_ue.InstancedStaticMeshComponent.md#customprimitivedata)

___

### DepthPriorityGroup

• **DepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[DepthPriorityGroup](ue_ue.InstancedStaticMeshComponent.md#depthprioritygroup)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[DetailMode](ue_ue.InstancedStaticMeshComponent.md#detailmode)

___

### DistanceFieldIndirectShadowMinVisibility

• **DistanceFieldIndirectShadowMinVisibility**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[DistanceFieldIndirectShadowMinVisibility](ue_ue.InstancedStaticMeshComponent.md#distancefieldindirectshadowminvisibility)

___

### DistanceFieldSelfShadowBias

• **DistanceFieldSelfShadowBias**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[DistanceFieldSelfShadowBias](ue_ue.InstancedStaticMeshComponent.md#distancefieldselfshadowbias)

___

### ExcludeForSpecificHLODLevels

• **ExcludeForSpecificHLODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ExcludeForSpecificHLODLevels](ue_ue.InstancedStaticMeshComponent.md#excludeforspecifichlodlevels)

___

### ForcedLodModel

• **ForcedLodModel**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ForcedLodModel](ue_ue.InstancedStaticMeshComponent.md#forcedlodmodel)

___

### IndirectLightingCacheQuality

• **IndirectLightingCacheQuality**: [`EIndirectLightingCacheQuality`](../enums/ue_ue.EIndirectLightingCacheQuality.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[IndirectLightingCacheQuality](ue_ue.InstancedStaticMeshComponent.md#indirectlightingcachequality)

___

### InstanceCountToRender

• **InstanceCountToRender**: `number`

___

### InstanceEndCullDistance

• **InstanceEndCullDistance**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[InstanceEndCullDistance](ue_ue.InstancedStaticMeshComponent.md#instanceendculldistance)

___

### InstanceReorderTable

• **InstanceReorderTable**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[InstanceReorderTable](ue_ue.InstancedStaticMeshComponent.md#instancereordertable)

___

### InstanceStartCullDistance

• **InstanceStartCullDistance**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[InstanceStartCullDistance](ue_ue.InstancedStaticMeshComponent.md#instancestartculldistance)

___

### InstancingRandomSeed

• **InstancingRandomSeed**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[InstancingRandomSeed](ue_ue.InstancedStaticMeshComponent.md#instancingrandomseed)

___

### IrrelevantLights

• **IrrelevantLights**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[IrrelevantLights](ue_ue.InstancedStaticMeshComponent.md#irrelevantlights)

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[LDMaxDrawDistance](ue_ue.InstancedStaticMeshComponent.md#ldmaxdrawdistance)

___

### LODData

• **LODData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticMeshComponentLODInfo`](ue_ue.StaticMeshComponentLODInfo.md)\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[LODData](ue_ue.InstancedStaticMeshComponent.md#loddata)

___

### LODParentPrimitive

• **LODParentPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[LODParentPrimitive](ue_ue.InstancedStaticMeshComponent.md#lodparentprimitive)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[LightingChannels](ue_ue.InstancedStaticMeshComponent.md#lightingchannels)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[LightmapType](ue_ue.InstancedStaticMeshComponent.md#lightmaptype)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassPrimitiveSettings`](ue_ue.LightmassPrimitiveSettings.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[LightmassSettings](ue_ue.InstancedStaticMeshComponent.md#lightmasssettings)

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[LpvBiasMultiplier](ue_ue.InstancedStaticMeshComponent.md#lpvbiasmultiplier)

___

### MaterialIndexPreview

• **MaterialIndexPreview**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[MaterialIndexPreview](ue_ue.InstancedStaticMeshComponent.md#materialindexpreview)

___

### MaterialStreamingRelativeBoxes

• **MaterialStreamingRelativeBoxes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[MaterialStreamingRelativeBoxes](ue_ue.InstancedStaticMeshComponent.md#materialstreamingrelativeboxes)

___

### MinDrawDistance

• **MinDrawDistance**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[MinDrawDistance](ue_ue.InstancedStaticMeshComponent.md#mindrawdistance)

___

### MinLOD

• **MinLOD**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[MinLOD](ue_ue.InstancedStaticMeshComponent.md#minlod)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[Mobility](ue_ue.InstancedStaticMeshComponent.md#mobility)

___

### MoveIgnoreActors

• **MoveIgnoreActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[MoveIgnoreActors](ue_ue.InstancedStaticMeshComponent.md#moveignoreactors)

___

### MoveIgnoreComponents

• **MoveIgnoreComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[MoveIgnoreComponents](ue_ue.InstancedStaticMeshComponent.md#moveignorecomponents)

___

### NumBuiltInstances

• **NumBuiltInstances**: `number`

___

### NumPendingLightmaps

• **NumPendingLightmaps**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[NumPendingLightmaps](ue_ue.InstancedStaticMeshComponent.md#numpendinglightmaps)

___

### OcclusionLayerNumNodes

• **OcclusionLayerNumNodes**: `number`

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnBeginCursorOver](ue_ue.InstancedStaticMeshComponent.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnClicked](ue_ue.InstancedStaticMeshComponent.md#onclicked)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnComponentActivated](ue_ue.InstancedStaticMeshComponent.md#oncomponentactivated)

___

### OnComponentBeginOverlap

• **OnComponentBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`, `bFromSweep`: `boolean`, `SweepResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnComponentBeginOverlap](ue_ue.InstancedStaticMeshComponent.md#oncomponentbeginoverlap)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnComponentDeactivated](ue_ue.InstancedStaticMeshComponent.md#oncomponentdeactivated)

___

### OnComponentEndOverlap

• **OnComponentEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`) => `void`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnComponentEndOverlap](ue_ue.InstancedStaticMeshComponent.md#oncomponentendoverlap)

___

### OnComponentHit

• **OnComponentHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`HitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnComponentHit](ue_ue.InstancedStaticMeshComponent.md#oncomponenthit)

___

### OnComponentSleep

• **OnComponentSleep**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SleepingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnComponentSleep](ue_ue.InstancedStaticMeshComponent.md#oncomponentsleep)

___

### OnComponentWake

• **OnComponentWake**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`WakingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnComponentWake](ue_ue.InstancedStaticMeshComponent.md#oncomponentwake)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnEndCursorOver](ue_ue.InstancedStaticMeshComponent.md#onendcursorover)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnInputTouchBegin](ue_ue.InstancedStaticMeshComponent.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnInputTouchEnd](ue_ue.InstancedStaticMeshComponent.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnInputTouchEnter](ue_ue.InstancedStaticMeshComponent.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnInputTouchLeave](ue_ue.InstancedStaticMeshComponent.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnReleased](ue_ue.InstancedStaticMeshComponent.md#onreleased)

___

### OverriddenLightMapRes

• **OverriddenLightMapRes**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OverriddenLightMapRes](ue_ue.InstancedStaticMeshComponent.md#overriddenlightmapres)

___

### OverrideMaterials

• **OverrideMaterials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OverrideMaterials](ue_ue.InstancedStaticMeshComponent.md#overridematerials)

___

### PerInstanceSMData

• **PerInstanceSMData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InstancedStaticMeshInstanceData`](ue_ue.InstancedStaticMeshInstanceData.md)\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[PerInstanceSMData](ue_ue.InstancedStaticMeshComponent.md#perinstancesmdata)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[PhysicsVolume](ue_ue.InstancedStaticMeshComponent.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.InstancedStaticMeshComponent.md#physicsvolumechangeddelegate)

___

### PreviousLODLevel

• **PreviousLODLevel**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[PreviousLODLevel](ue_ue.InstancedStaticMeshComponent.md#previouslodlevel)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[PrimaryComponentTick](ue_ue.InstancedStaticMeshComponent.md#primarycomponenttick)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[RelativeLocation](ue_ue.InstancedStaticMeshComponent.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[RelativeRotation](ue_ue.InstancedStaticMeshComponent.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[RelativeScale3D](ue_ue.InstancedStaticMeshComponent.md#relativescale3d)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[RuntimeVirtualTextures](ue_ue.InstancedStaticMeshComponent.md#runtimevirtualtextures)

___

### SectionIndexPreview

• **SectionIndexPreview**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SectionIndexPreview](ue_ue.InstancedStaticMeshComponent.md#sectionindexpreview)

___

### SelectedEditorMaterial

• **SelectedEditorMaterial**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SelectedEditorMaterial](ue_ue.InstancedStaticMeshComponent.md#selectededitormaterial)

___

### SelectedEditorSection

• **SelectedEditorSection**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SelectedEditorSection](ue_ue.InstancedStaticMeshComponent.md#selectededitorsection)

___

### SortedInstances

• **SortedInstances**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### StaticMesh

• **StaticMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[StaticMesh](ue_ue.InstancedStaticMeshComponent.md#staticmesh)

___

### StaticMeshDerivedDataKey

• **StaticMeshDerivedDataKey**: `string`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[StaticMeshDerivedDataKey](ue_ue.InstancedStaticMeshComponent.md#staticmeshderiveddatakey)

___

### StaticMeshImportVersion

• **StaticMeshImportVersion**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[StaticMeshImportVersion](ue_ue.InstancedStaticMeshComponent.md#staticmeshimportversion)

___

### StreamingDistanceMultiplier

• **StreamingDistanceMultiplier**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[StreamingDistanceMultiplier](ue_ue.InstancedStaticMeshComponent.md#streamingdistancemultiplier)

___

### StreamingTextureData

• **StreamingTextureData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StreamingTextureBuildInfo`](ue_ue.StreamingTextureBuildInfo.md)\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[StreamingTextureData](ue_ue.InstancedStaticMeshComponent.md#streamingtexturedata)

___

### SubDivisionStepSize

• **SubDivisionStepSize**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SubDivisionStepSize](ue_ue.InstancedStaticMeshComponent.md#subdivisionstepsize)

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[TranslucencySortPriority](ue_ue.InstancedStaticMeshComponent.md#translucencysortpriority)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[UCSModifiedProperties](ue_ue.InstancedStaticMeshComponent.md#ucsmodifiedproperties)

___

### UnbuiltInstanceBounds

• **UnbuiltInstanceBounds**: [`Box`](ue_ue.Box.md)

___

### UnbuiltInstanceBoundsList

• **UnbuiltInstanceBoundsList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Box`](ue_ue.Box.md)\>

___

### ViewOwnerDepthPriorityGroup

• **ViewOwnerDepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ViewOwnerDepthPriorityGroup](ue_ue.InstancedStaticMeshComponent.md#viewownerdepthprioritygroup)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[VirtualTextureCullMips](ue_ue.InstancedStaticMeshComponent.md#virtualtexturecullmips)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[VirtualTextureLodBias](ue_ue.InstancedStaticMeshComponent.md#virtualtexturelodbias)

___

### VirtualTextureMinCoverage

• **VirtualTextureMinCoverage**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[VirtualTextureMinCoverage](ue_ue.InstancedStaticMeshComponent.md#virtualtexturemincoverage)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[VirtualTextureRenderPassType](ue_ue.InstancedStaticMeshComponent.md#virtualtexturerenderpasstype)

___

### VisibilityId

• **VisibilityId**: `number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[VisibilityId](ue_ue.InstancedStaticMeshComponent.md#visibilityid)

___

### WireframeColorOverride

• **WireframeColorOverride**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[WireframeColorOverride](ue_ue.InstancedStaticMeshComponent.md#wireframecoloroverride)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[__tid_ActorComponent__](ue_ue.InstancedStaticMeshComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_HierarchicalInstancedStaticMeshComponent\_\_

• **\_\_tid\_HierarchicalInstancedStaticMeshComponent\_\_**: `boolean`

___

### \_\_tid\_InstancedStaticMeshComponent\_\_

• **\_\_tid\_InstancedStaticMeshComponent\_\_**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[__tid_InstancedStaticMeshComponent__](ue_ue.InstancedStaticMeshComponent.md#__tid_instancedstaticmeshcomponent__)

___

### \_\_tid\_MeshComponent\_\_

• **\_\_tid\_MeshComponent\_\_**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[__tid_MeshComponent__](ue_ue.InstancedStaticMeshComponent.md#__tid_meshcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[__tid_Object__](ue_ue.InstancedStaticMeshComponent.md#__tid_object__)

___

### \_\_tid\_PrimitiveComponent\_\_

• **\_\_tid\_PrimitiveComponent\_\_**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[__tid_PrimitiveComponent__](ue_ue.InstancedStaticMeshComponent.md#__tid_primitivecomponent__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[__tid_SceneComponent__](ue_ue.InstancedStaticMeshComponent.md#__tid_scenecomponent__)

___

### \_\_tid\_StaticMeshComponent\_\_

• **\_\_tid\_StaticMeshComponent\_\_**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[__tid_StaticMeshComponent__](ue_ue.InstancedStaticMeshComponent.md#__tid_staticmeshcomponent__)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bAbsoluteLocation](ue_ue.InstancedStaticMeshComponent.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bAbsoluteRotation](ue_ue.InstancedStaticMeshComponent.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bAbsoluteScale](ue_ue.InstancedStaticMeshComponent.md#babsolutescale)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bAffectDistanceFieldLighting](ue_ue.InstancedStaticMeshComponent.md#baffectdistancefieldlighting)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bAffectDynamicIndirectLighting](ue_ue.InstancedStaticMeshComponent.md#baffectdynamicindirectlighting)

___

### bAllowCullDistanceVolume

• **bAllowCullDistanceVolume**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bAllowCullDistanceVolume](ue_ue.InstancedStaticMeshComponent.md#ballowculldistancevolume)

___

### bAlwaysCreatePhysicsState

• **bAlwaysCreatePhysicsState**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bAlwaysCreatePhysicsState](ue_ue.InstancedStaticMeshComponent.md#balwayscreatephysicsstate)

___

### bApplyImpulseOnDamage

• **bApplyImpulseOnDamage**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bApplyImpulseOnDamage](ue_ue.InstancedStaticMeshComponent.md#bapplyimpulseondamage)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bAutoActivate](ue_ue.InstancedStaticMeshComponent.md#bautoactivate)

___

### bBatchImpostersAsInstances

• **bBatchImpostersAsInstances**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bBatchImpostersAsInstances](ue_ue.InstancedStaticMeshComponent.md#bbatchimpostersasinstances)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.InstancedStaticMeshComponent.md#bboundschangetriggersstreamingdatarebuild)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bCanEverAffectNavigation](ue_ue.InstancedStaticMeshComponent.md#bcaneveraffectnavigation)

___

### bCastCinematicShadow

• **bCastCinematicShadow**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bCastCinematicShadow](ue_ue.InstancedStaticMeshComponent.md#bcastcinematicshadow)

___

### bCastDistanceFieldIndirectShadow

• **bCastDistanceFieldIndirectShadow**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bCastDistanceFieldIndirectShadow](ue_ue.InstancedStaticMeshComponent.md#bcastdistancefieldindirectshadow)

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bCastDynamicShadow](ue_ue.InstancedStaticMeshComponent.md#bcastdynamicshadow)

___

### bCastFarShadow

• **bCastFarShadow**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bCastFarShadow](ue_ue.InstancedStaticMeshComponent.md#bcastfarshadow)

___

### bCastHiddenShadow

• **bCastHiddenShadow**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bCastHiddenShadow](ue_ue.InstancedStaticMeshComponent.md#bcasthiddenshadow)

___

### bCastInsetShadow

• **bCastInsetShadow**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bCastInsetShadow](ue_ue.InstancedStaticMeshComponent.md#bcastinsetshadow)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bCastShadowAsTwoSided](ue_ue.InstancedStaticMeshComponent.md#bcastshadowastwosided)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bCastStaticShadow](ue_ue.InstancedStaticMeshComponent.md#bcaststaticshadow)

___

### bCastVolumetricTranslucentShadow

• **bCastVolumetricTranslucentShadow**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bCastVolumetricTranslucentShadow](ue_ue.InstancedStaticMeshComponent.md#bcastvolumetrictranslucentshadow)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bComponentToWorldUpdated](ue_ue.InstancedStaticMeshComponent.md#bcomponenttoworldupdated)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bCreatedByConstructionScript](ue_ue.InstancedStaticMeshComponent.md#bcreatedbyconstructionscript)

___

### bCustomOverrideVertexColorPerLOD

• **bCustomOverrideVertexColorPerLOD**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bCustomOverrideVertexColorPerLOD](ue_ue.InstancedStaticMeshComponent.md#bcustomoverridevertexcolorperlod)

___

### bDisableCollision

• **bDisableCollision**: `boolean`

___

### bDisallowMeshPaintPerInstance

• **bDisallowMeshPaintPerInstance**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bDisallowMeshPaintPerInstance](ue_ue.InstancedStaticMeshComponent.md#bdisallowmeshpaintperinstance)

___

### bDisplayVertexColors

• **bDisplayVertexColors**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bDisplayVertexColors](ue_ue.InstancedStaticMeshComponent.md#bdisplayvertexcolors)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bEditableWhenInherited](ue_ue.InstancedStaticMeshComponent.md#beditablewheninherited)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bEnableAutoLODGeneration](ue_ue.InstancedStaticMeshComponent.md#benableautolodgeneration)

___

### bEnableDensityScaling

• **bEnableDensityScaling**: `boolean`

___

### bEnableMaterialParameterCaching

• **bEnableMaterialParameterCaching**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bEnableMaterialParameterCaching](ue_ue.InstancedStaticMeshComponent.md#benablematerialparametercaching)

___

### bEvaluateWorldPositionOffset

• **bEvaluateWorldPositionOffset**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bEvaluateWorldPositionOffset](ue_ue.InstancedStaticMeshComponent.md#bevaluateworldpositionoffset)

___

### bExcludeFromLightAttachmentGroup

• **bExcludeFromLightAttachmentGroup**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bExcludeFromLightAttachmentGroup](ue_ue.InstancedStaticMeshComponent.md#bexcludefromlightattachmentgroup)

___

### bForceMipStreaming

• **bForceMipStreaming**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bForceMipStreaming](ue_ue.InstancedStaticMeshComponent.md#bforcemipstreaming)

___

### bForceNavigationObstacle

• **bForceNavigationObstacle**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bForceNavigationObstacle](ue_ue.InstancedStaticMeshComponent.md#bforcenavigationobstacle)

___

### bGenerateOverlapEvents

• **bGenerateOverlapEvents**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bGenerateOverlapEvents](ue_ue.InstancedStaticMeshComponent.md#bgenerateoverlapevents)

___

### bHasCustomNavigableGeometry

• **bHasCustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bHasCustomNavigableGeometry](ue_ue.InstancedStaticMeshComponent.md#bhascustomnavigablegeometry)

___

### bHasMotionBlurVelocityMeshes

• **bHasMotionBlurVelocityMeshes**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bHasMotionBlurVelocityMeshes](ue_ue.InstancedStaticMeshComponent.md#bhasmotionblurvelocitymeshes)

___

### bHasPerInstanceHitProxies

• **bHasPerInstanceHitProxies**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bHasPerInstanceHitProxies](ue_ue.InstancedStaticMeshComponent.md#bhasperinstancehitproxies)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bHiddenInGame](ue_ue.InstancedStaticMeshComponent.md#bhiddeningame)

___

### bIgnoreInstanceForTextureStreaming

• **bIgnoreInstanceForTextureStreaming**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bIgnoreInstanceForTextureStreaming](ue_ue.InstancedStaticMeshComponent.md#bignoreinstancefortexturestreaming)

___

### bIgnoreRadialForce

• **bIgnoreRadialForce**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bIgnoreRadialForce](ue_ue.InstancedStaticMeshComponent.md#bignoreradialforce)

___

### bIgnoreRadialImpulse

• **bIgnoreRadialImpulse**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bIgnoreRadialImpulse](ue_ue.InstancedStaticMeshComponent.md#bignoreradialimpulse)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bInstanceComponent](ue_ue.InstancedStaticMeshComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bIsActive](ue_ue.InstancedStaticMeshComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bIsEditorOnly](ue_ue.InstancedStaticMeshComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bIsVisualizationComponent](ue_ue.InstancedStaticMeshComponent.md#bisvisualizationcomponent)

___

### bLightAsIfStatic

• **bLightAsIfStatic**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bLightAsIfStatic](ue_ue.InstancedStaticMeshComponent.md#blightasifstatic)

___

### bLightAttachmentsAsGroup

• **bLightAttachmentsAsGroup**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bLightAttachmentsAsGroup](ue_ue.InstancedStaticMeshComponent.md#blightattachmentsasgroup)

___

### bMultiBodyOverlap

• **bMultiBodyOverlap**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bMultiBodyOverlap](ue_ue.InstancedStaticMeshComponent.md#bmultibodyoverlap)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bNetAddressable](ue_ue.InstancedStaticMeshComponent.md#bnetaddressable)

___

### bNeverDistanceCull

• **bNeverDistanceCull**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bNeverDistanceCull](ue_ue.InstancedStaticMeshComponent.md#bneverdistancecull)

___

### bOnlyOwnerSee

• **bOnlyOwnerSee**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bOnlyOwnerSee](ue_ue.InstancedStaticMeshComponent.md#bonlyownersee)

___

### bOverrideDistanceFieldSelfShadowBias

• **bOverrideDistanceFieldSelfShadowBias**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bOverrideDistanceFieldSelfShadowBias](ue_ue.InstancedStaticMeshComponent.md#boverridedistancefieldselfshadowbias)

___

### bOverrideLightMapRes

• **bOverrideLightMapRes**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bOverrideLightMapRes](ue_ue.InstancedStaticMeshComponent.md#boverridelightmapres)

___

### bOverrideMinLOD

• **bOverrideMinLOD**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bOverrideMinLOD](ue_ue.InstancedStaticMeshComponent.md#boverrideminlod)

___

### bOverrideNavigationExport

• **bOverrideNavigationExport**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bOverrideNavigationExport](ue_ue.InstancedStaticMeshComponent.md#boverridenavigationexport)

___

### bOverrideWireframeColor

• **bOverrideWireframeColor**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bOverrideWireframeColor](ue_ue.InstancedStaticMeshComponent.md#boverridewireframecolor)

___

### bOwnerNoSee

• **bOwnerNoSee**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bOwnerNoSee](ue_ue.InstancedStaticMeshComponent.md#bownernosee)

___

### bReceiveMobileCSMShadows

• **bReceiveMobileCSMShadows**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bReceiveMobileCSMShadows](ue_ue.InstancedStaticMeshComponent.md#breceivemobilecsmshadows)

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bReceivesDecals](ue_ue.InstancedStaticMeshComponent.md#breceivesdecals)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bRenderCustomDepth](ue_ue.InstancedStaticMeshComponent.md#brendercustomdepth)

___

### bRenderInDepthPass

• **bRenderInDepthPass**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bRenderInDepthPass](ue_ue.InstancedStaticMeshComponent.md#brenderindepthpass)

___

### bRenderInMainPass

• **bRenderInMainPass**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bRenderInMainPass](ue_ue.InstancedStaticMeshComponent.md#brenderinmainpass)

___

### bReplicatePhysicsToAutonomousProxy

• **bReplicatePhysicsToAutonomousProxy**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bReplicatePhysicsToAutonomousProxy](ue_ue.InstancedStaticMeshComponent.md#breplicatephysicstoautonomousproxy)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bReplicates](ue_ue.InstancedStaticMeshComponent.md#breplicates)

___

### bReturnMaterialOnMove

• **bReturnMaterialOnMove**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bReturnMaterialOnMove](ue_ue.InstancedStaticMeshComponent.md#breturnmaterialonmove)

___

### bReverseCulling

• **bReverseCulling**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bReverseCulling](ue_ue.InstancedStaticMeshComponent.md#breverseculling)

___

### bSelectable

• **bSelectable**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bSelectable](ue_ue.InstancedStaticMeshComponent.md#bselectable)

___

### bSelfShadowOnly

• **bSelfShadowOnly**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bSelfShadowOnly](ue_ue.InstancedStaticMeshComponent.md#bselfshadowonly)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bShouldBeAttached](ue_ue.InstancedStaticMeshComponent.md#bshouldbeattached)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.InstancedStaticMeshComponent.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.InstancedStaticMeshComponent.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.InstancedStaticMeshComponent.md#bshouldupdatephysicsvolume)

___

### bSingleSampleShadowFromStationaryLights

• **bSingleSampleShadowFromStationaryLights**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bSingleSampleShadowFromStationaryLights](ue_ue.InstancedStaticMeshComponent.md#bsinglesampleshadowfromstationarylights)

___

### bTraceComplexOnMove

• **bTraceComplexOnMove**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bTraceComplexOnMove](ue_ue.InstancedStaticMeshComponent.md#btracecomplexonmove)

___

### bTreatAsBackgroundForOcclusion

• **bTreatAsBackgroundForOcclusion**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bTreatAsBackgroundForOcclusion](ue_ue.InstancedStaticMeshComponent.md#btreatasbackgroundforocclusion)

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bUseAsOccluder](ue_ue.InstancedStaticMeshComponent.md#buseasoccluder)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bUseAttachParentBound](ue_ue.InstancedStaticMeshComponent.md#buseattachparentbound)

___

### bUseDefaultCollision

• **bUseDefaultCollision**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bUseDefaultCollision](ue_ue.InstancedStaticMeshComponent.md#busedefaultcollision)

___

### bUseEditorCompositing

• **bUseEditorCompositing**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bUseEditorCompositing](ue_ue.InstancedStaticMeshComponent.md#buseeditorcompositing)

___

### bUseMaxLODAsImposter

• **bUseMaxLODAsImposter**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bUseMaxLODAsImposter](ue_ue.InstancedStaticMeshComponent.md#busemaxlodasimposter)

___

### bUseSubDivisions

• **bUseSubDivisions**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bUseSubDivisions](ue_ue.InstancedStaticMeshComponent.md#busesubdivisions)

___

### bUseViewOwnerDepthPriorityGroup

• **bUseViewOwnerDepthPriorityGroup**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bUseViewOwnerDepthPriorityGroup](ue_ue.InstancedStaticMeshComponent.md#buseviewownerdepthprioritygroup)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bVisible](ue_ue.InstancedStaticMeshComponent.md#bvisible)

___

### bVisibleInRayTracing

• **bVisibleInRayTracing**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bVisibleInRayTracing](ue_ue.InstancedStaticMeshComponent.md#bvisibleinraytracing)

___

### bVisibleInReflectionCaptures

• **bVisibleInReflectionCaptures**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bVisibleInReflectionCaptures](ue_ue.InstancedStaticMeshComponent.md#bvisibleinreflectioncaptures)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[bVisualizeComponent](ue_ue.InstancedStaticMeshComponent.md#bvisualizecomponent)

## Methods

### Activate

▸ **Activate**(`bReset?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bReset?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[Activate](ue_ue.InstancedStaticMeshComponent.md#activate)

___

### AddAngularImpulse

▸ **AddAngularImpulse**(`Impulse`, `BoneName?`, `bVelChange?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Impulse` | [`Vector`](ue_ue_s.Vector.md) |
| `BoneName?` | `string` |
| `bVelChange?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AddAngularImpulse](ue_ue.InstancedStaticMeshComponent.md#addangularimpulse)

___

### AddAngularImpulseInDegrees

▸ **AddAngularImpulseInDegrees**(`Impulse`, `BoneName?`, `bVelChange?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Impulse` | [`Vector`](ue_ue_s.Vector.md) |
| `BoneName?` | `string` |
| `bVelChange?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AddAngularImpulseInDegrees](ue_ue.InstancedStaticMeshComponent.md#addangularimpulseindegrees)

___

### AddAngularImpulseInRadians

▸ **AddAngularImpulseInRadians**(`Impulse`, `BoneName?`, `bVelChange?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Impulse` | [`Vector`](ue_ue_s.Vector.md) |
| `BoneName?` | `string` |
| `bVelChange?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AddAngularImpulseInRadians](ue_ue.InstancedStaticMeshComponent.md#addangularimpulseinradians)

___

### AddForce

▸ **AddForce**(`Force`, `BoneName?`, `bAccelChange?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Force` | [`Vector`](ue_ue_s.Vector.md) |
| `BoneName?` | `string` |
| `bAccelChange?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AddForce](ue_ue.InstancedStaticMeshComponent.md#addforce)

___

### AddForceAtLocation

▸ **AddForceAtLocation**(`Force`, `Location`, `BoneName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Force` | [`Vector`](ue_ue_s.Vector.md) |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `BoneName?` | `string` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AddForceAtLocation](ue_ue.InstancedStaticMeshComponent.md#addforceatlocation)

___

### AddForceAtLocationLocal

▸ **AddForceAtLocationLocal**(`Force`, `Location`, `BoneName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Force` | [`Vector`](ue_ue_s.Vector.md) |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `BoneName?` | `string` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AddForceAtLocationLocal](ue_ue.InstancedStaticMeshComponent.md#addforceatlocationlocal)

___

### AddImpulse

▸ **AddImpulse**(`Impulse`, `BoneName?`, `bVelChange?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Impulse` | [`Vector`](ue_ue_s.Vector.md) |
| `BoneName?` | `string` |
| `bVelChange?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AddImpulse](ue_ue.InstancedStaticMeshComponent.md#addimpulse)

___

### AddImpulseAtLocation

▸ **AddImpulseAtLocation**(`Impulse`, `Location`, `BoneName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Impulse` | [`Vector`](ue_ue_s.Vector.md) |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `BoneName?` | `string` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AddImpulseAtLocation](ue_ue.InstancedStaticMeshComponent.md#addimpulseatlocation)

___

### AddInstance

▸ **AddInstance**(`InstanceTransform`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InstanceTransform` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AddInstance](ue_ue.InstancedStaticMeshComponent.md#addinstance)

___

### AddInstanceWorldSpace

▸ **AddInstanceWorldSpace**(`WorldTransform`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldTransform` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AddInstanceWorldSpace](ue_ue.InstancedStaticMeshComponent.md#addinstanceworldspace)

___

### AddRadialForce

▸ **AddRadialForce**(`Origin`, `Radius`, `Strength`, `Falloff`, `bAccelChange?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Origin` | [`Vector`](ue_ue_s.Vector.md) |
| `Radius` | `number` |
| `Strength` | `number` |
| `Falloff` | [`ERadialImpulseFalloff`](../enums/ue_ue.ERadialImpulseFalloff.md) |
| `bAccelChange?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AddRadialForce](ue_ue.InstancedStaticMeshComponent.md#addradialforce)

___

### AddRadialImpulse

▸ **AddRadialImpulse**(`Origin`, `Radius`, `Strength`, `Falloff`, `bVelChange?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Origin` | [`Vector`](ue_ue_s.Vector.md) |
| `Radius` | `number` |
| `Strength` | `number` |
| `Falloff` | [`ERadialImpulseFalloff`](../enums/ue_ue.ERadialImpulseFalloff.md) |
| `bVelChange?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AddRadialImpulse](ue_ue.InstancedStaticMeshComponent.md#addradialimpulse)

___

### AddTickPrerequisiteActor

▸ **AddTickPrerequisiteActor**(`PrerequisiteActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AddTickPrerequisiteActor](ue_ue.InstancedStaticMeshComponent.md#addtickprerequisiteactor)

___

### AddTickPrerequisiteComponent

▸ **AddTickPrerequisiteComponent**(`PrerequisiteComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\> |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AddTickPrerequisiteComponent](ue_ue.InstancedStaticMeshComponent.md#addtickprerequisitecomponent)

___

### AddTorque

▸ **AddTorque**(`Torque`, `BoneName?`, `bAccelChange?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Torque` | [`Vector`](ue_ue_s.Vector.md) |
| `BoneName?` | `string` |
| `bAccelChange?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AddTorque](ue_ue.InstancedStaticMeshComponent.md#addtorque)

___

### AddTorqueInDegrees

▸ **AddTorqueInDegrees**(`Torque`, `BoneName?`, `bAccelChange?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Torque` | [`Vector`](ue_ue_s.Vector.md) |
| `BoneName?` | `string` |
| `bAccelChange?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AddTorqueInDegrees](ue_ue.InstancedStaticMeshComponent.md#addtorqueindegrees)

___

### AddTorqueInRadians

▸ **AddTorqueInRadians**(`Torque`, `BoneName?`, `bAccelChange?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Torque` | [`Vector`](ue_ue_s.Vector.md) |
| `BoneName?` | `string` |
| `bAccelChange?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[AddTorqueInRadians](ue_ue.InstancedStaticMeshComponent.md#addtorqueinradians)

___

### BatchUpdateInstancesTransform

▸ **BatchUpdateInstancesTransform**(`StartInstanceIndex`, `NumInstances`, `NewInstancesTransform`, `bWorldSpace?`, `bMarkRenderStateDirty?`, `bTeleport?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StartInstanceIndex` | `number` |
| `NumInstances` | `number` |
| `NewInstancesTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `bWorldSpace?` | `boolean` |
| `bMarkRenderStateDirty?` | `boolean` |
| `bTeleport?` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[BatchUpdateInstancesTransform](ue_ue.InstancedStaticMeshComponent.md#batchupdateinstancestransform)

___

### BatchUpdateInstancesTransforms

▸ **BatchUpdateInstancesTransforms**(`StartInstanceIndex`, `NewInstancesTransforms`, `bWorldSpace?`, `bMarkRenderStateDirty?`, `bTeleport?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StartInstanceIndex` | `number` |
| `NewInstancesTransforms` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\> |
| `bWorldSpace?` | `boolean` |
| `bMarkRenderStateDirty?` | `boolean` |
| `bTeleport?` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[BatchUpdateInstancesTransforms](ue_ue.InstancedStaticMeshComponent.md#batchupdateinstancestransforms)

___

### CanCharacterStepUp

▸ **CanCharacterStepUp**(`Pawn`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Pawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[CanCharacterStepUp](ue_ue.InstancedStaticMeshComponent.md#cancharacterstepup)

___

### ClearInstances

▸ **ClearInstances**(): `void`

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ClearInstances](ue_ue.InstancedStaticMeshComponent.md#clearinstances)

___

### ClearMoveIgnoreActors

▸ **ClearMoveIgnoreActors**(): `void`

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ClearMoveIgnoreActors](ue_ue.InstancedStaticMeshComponent.md#clearmoveignoreactors)

___

### ClearMoveIgnoreComponents

▸ **ClearMoveIgnoreComponents**(): `void`

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ClearMoveIgnoreComponents](ue_ue.InstancedStaticMeshComponent.md#clearmoveignorecomponents)

___

### ComponentHasTag

▸ **ComponentHasTag**(`Tag`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tag` | `string` |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ComponentHasTag](ue_ue.InstancedStaticMeshComponent.md#componenthastag)

___

### CopyArrayOfMoveIgnoreActors

▸ **CopyArrayOfMoveIgnoreActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[CopyArrayOfMoveIgnoreActors](ue_ue.InstancedStaticMeshComponent.md#copyarrayofmoveignoreactors)

___

### CopyArrayOfMoveIgnoreComponents

▸ **CopyArrayOfMoveIgnoreComponents**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[CopyArrayOfMoveIgnoreComponents](ue_ue.InstancedStaticMeshComponent.md#copyarrayofmoveignorecomponents)

___

### CreateAndSetMaterialInstanceDynamic

▸ **CreateAndSetMaterialInstanceDynamic**(`ElementIndex`): [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ElementIndex` | `number` |

#### Returns

[`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[CreateAndSetMaterialInstanceDynamic](ue_ue.InstancedStaticMeshComponent.md#createandsetmaterialinstancedynamic)

___

### CreateAndSetMaterialInstanceDynamicFromMaterial

▸ **CreateAndSetMaterialInstanceDynamicFromMaterial**(`ElementIndex`, `Parent`): [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ElementIndex` | `number` |
| `Parent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |

#### Returns

[`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.InstancedStaticMeshComponent.md#createandsetmaterialinstancedynamicfrommaterial)

___

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

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[CreateDefaultSubobject](ue_ue.InstancedStaticMeshComponent.md#createdefaultsubobject)

___

### CreateDynamicMaterialInstance

▸ **CreateDynamicMaterialInstance**(`ElementIndex`, `SourceMaterial?`, `OptionalName?`): [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ElementIndex` | `number` |
| `SourceMaterial?` | [`MaterialInterface`](ue_ue.MaterialInterface.md) |
| `OptionalName?` | `string` |

#### Returns

[`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[CreateDynamicMaterialInstance](ue_ue.InstancedStaticMeshComponent.md#createdynamicmaterialinstance)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[Deactivate](ue_ue.InstancedStaticMeshComponent.md#deactivate)

___

### DetachFromParent

▸ **DetachFromParent**(`bMaintainWorldPosition?`, `bCallModify?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bMaintainWorldPosition?` | `boolean` |
| `bCallModify?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[DetachFromParent](ue_ue.InstancedStaticMeshComponent.md#detachfromparent)

___

### DoesSocketExist

▸ **DoesSocketExist**(`InSocketName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSocketName` | `string` |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[DoesSocketExist](ue_ue.InstancedStaticMeshComponent.md#doessocketexist)

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

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ExecuteUbergraph](ue_ue.InstancedStaticMeshComponent.md#executeubergraph)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetAllSocketNames](ue_ue.InstancedStaticMeshComponent.md#getallsocketnames)

___

### GetAngularDamping

▸ **GetAngularDamping**(): `number`

#### Returns

`number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetAngularDamping](ue_ue.InstancedStaticMeshComponent.md#getangulardamping)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetAttachParent](ue_ue.InstancedStaticMeshComponent.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetAttachSocketName](ue_ue.InstancedStaticMeshComponent.md#getattachsocketname)

___

### GetCenterOfMass

▸ **GetCenterOfMass**(`BoneName?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName?` | `string` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetCenterOfMass](ue_ue.InstancedStaticMeshComponent.md#getcenterofmass)

___

### GetChildComponent

▸ **GetChildComponent**(`ChildIndex`): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ChildIndex` | `number` |

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetChildComponent](ue_ue.InstancedStaticMeshComponent.md#getchildcomponent)

___

### GetChildrenComponents

▸ **GetChildrenComponents**(`bIncludeAllDescendants`, `Children`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIncludeAllDescendants` | `boolean` |
| `Children` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>\> |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetChildrenComponents](ue_ue.InstancedStaticMeshComponent.md#getchildrencomponents)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetClass](ue_ue.InstancedStaticMeshComponent.md#getclass)

___

### GetClosestPointOnCollision

▸ **GetClosestPointOnCollision**(`Point`, `OutPointOnBody`, `BoneName?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Point` | [`Vector`](ue_ue_s.Vector.md) |
| `OutPointOnBody` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `BoneName?` | `string` |

#### Returns

`number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetClosestPointOnCollision](ue_ue.InstancedStaticMeshComponent.md#getclosestpointoncollision)

___

### GetCollisionEnabled

▸ **GetCollisionEnabled**(): [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Returns

[`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetCollisionEnabled](ue_ue.InstancedStaticMeshComponent.md#getcollisionenabled)

___

### GetCollisionObjectType

▸ **GetCollisionObjectType**(): [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Returns

[`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetCollisionObjectType](ue_ue.InstancedStaticMeshComponent.md#getcollisionobjecttype)

___

### GetCollisionProfileName

▸ **GetCollisionProfileName**(): `string`

#### Returns

`string`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetCollisionProfileName](ue_ue.InstancedStaticMeshComponent.md#getcollisionprofilename)

___

### GetCollisionResponseToChannel

▸ **GetCollisionResponseToChannel**(`Channel`): [`ECollisionResponse`](../enums/ue_ue.ECollisionResponse.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Channel` | [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md) |

#### Returns

[`ECollisionResponse`](../enums/ue_ue.ECollisionResponse.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetCollisionResponseToChannel](ue_ue.InstancedStaticMeshComponent.md#getcollisionresponsetochannel)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetComponentTickInterval](ue_ue.InstancedStaticMeshComponent.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetComponentVelocity](ue_ue.InstancedStaticMeshComponent.md#getcomponentvelocity)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetForwardVector](ue_ue.InstancedStaticMeshComponent.md#getforwardvector)

___

### GetGenerateOverlapEvents

▸ **GetGenerateOverlapEvents**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetGenerateOverlapEvents](ue_ue.InstancedStaticMeshComponent.md#getgenerateoverlapevents)

___

### GetInertiaTensor

▸ **GetInertiaTensor**(`BoneName?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName?` | `string` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetInertiaTensor](ue_ue.InstancedStaticMeshComponent.md#getinertiatensor)

___

### GetInstanceCount

▸ **GetInstanceCount**(): `number`

#### Returns

`number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetInstanceCount](ue_ue.InstancedStaticMeshComponent.md#getinstancecount)

___

### GetInstanceTransform

▸ **GetInstanceTransform**(`InstanceIndex`, `OutInstanceTransform`, `bWorldSpace?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InstanceIndex` | `number` |
| `OutInstanceTransform` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Transform`](ue_ue_s.Transform.md)\> |
| `bWorldSpace?` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetInstanceTransform](ue_ue.InstancedStaticMeshComponent.md#getinstancetransform)

___

### GetInstancesOverlappingBox

▸ **GetInstancesOverlappingBox**(`Box`, `bBoxInWorldSpace?`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Box` | [`Box`](ue_ue.Box.md) |
| `bBoxInWorldSpace?` | `boolean` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetInstancesOverlappingBox](ue_ue.InstancedStaticMeshComponent.md#getinstancesoverlappingbox)

___

### GetInstancesOverlappingSphere

▸ **GetInstancesOverlappingSphere**(`Center`, `Radius`, `bSphereInWorldSpace?`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Center` | [`Vector`](ue_ue_s.Vector.md) |
| `Radius` | `number` |
| `bSphereInWorldSpace?` | `boolean` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetInstancesOverlappingSphere](ue_ue.InstancedStaticMeshComponent.md#getinstancesoverlappingsphere)

___

### GetLinearDamping

▸ **GetLinearDamping**(): `number`

#### Returns

`number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetLinearDamping](ue_ue.InstancedStaticMeshComponent.md#getlineardamping)

___

### GetLocalBounds

▸ **GetLocalBounds**(`Min`, `Max`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Min` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `Max` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetLocalBounds](ue_ue.InstancedStaticMeshComponent.md#getlocalbounds)

___

### GetMass

▸ **GetMass**(): `number`

#### Returns

`number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetMass](ue_ue.InstancedStaticMeshComponent.md#getmass)

___

### GetMassScale

▸ **GetMassScale**(`BoneName?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName?` | `string` |

#### Returns

`number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetMassScale](ue_ue.InstancedStaticMeshComponent.md#getmassscale)

___

### GetMaterial

▸ **GetMaterial**(`ElementIndex`): [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ElementIndex` | `number` |

#### Returns

[`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetMaterial](ue_ue.InstancedStaticMeshComponent.md#getmaterial)

___

### GetMaterialFromCollisionFaceIndex

▸ **GetMaterialFromCollisionFaceIndex**(`FaceIndex`, `SectionIndex`): [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `FaceIndex` | `number` |
| `SectionIndex` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

[`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetMaterialFromCollisionFaceIndex](ue_ue.InstancedStaticMeshComponent.md#getmaterialfromcollisionfaceindex)

___

### GetMaterialIndex

▸ **GetMaterialIndex**(`MaterialSlotName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialSlotName` | `string` |

#### Returns

`number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetMaterialIndex](ue_ue.InstancedStaticMeshComponent.md#getmaterialindex)

___

### GetMaterialSlotNames

▸ **GetMaterialSlotNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetMaterialSlotNames](ue_ue.InstancedStaticMeshComponent.md#getmaterialslotnames)

___

### GetMaterials

▸ **GetMaterials**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetMaterials](ue_ue.InstancedStaticMeshComponent.md#getmaterials)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetName](ue_ue.InstancedStaticMeshComponent.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetNumChildrenComponents](ue_ue.InstancedStaticMeshComponent.md#getnumchildrencomponents)

___

### GetNumMaterials

▸ **GetNumMaterials**(): `number`

#### Returns

`number`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetNumMaterials](ue_ue.InstancedStaticMeshComponent.md#getnummaterials)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetOuter](ue_ue.InstancedStaticMeshComponent.md#getouter)

___

### GetOverlappingActors

▸ **GetOverlappingActors**(`OverlappingActors`, `ClassFilter?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OverlappingActors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |
| `ClassFilter?` | [`Class`](ue_ue.Class.md) |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetOverlappingActors](ue_ue.InstancedStaticMeshComponent.md#getoverlappingactors)

___

### GetOverlappingComponents

▸ **GetOverlappingComponents**(`OutOverlappingComponents`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutOverlappingComponents` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>\> |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetOverlappingComponents](ue_ue.InstancedStaticMeshComponent.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetOwner](ue_ue.InstancedStaticMeshComponent.md#getowner)

___

### GetParentComponents

▸ **GetParentComponents**(`Parents`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Parents` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>\> |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetParentComponents](ue_ue.InstancedStaticMeshComponent.md#getparentcomponents)

___

### GetPhysicsAngularVelocity

▸ **GetPhysicsAngularVelocity**(`BoneName?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName?` | `string` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetPhysicsAngularVelocity](ue_ue.InstancedStaticMeshComponent.md#getphysicsangularvelocity)

___

### GetPhysicsAngularVelocityInDegrees

▸ **GetPhysicsAngularVelocityInDegrees**(`BoneName?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName?` | `string` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetPhysicsAngularVelocityInDegrees](ue_ue.InstancedStaticMeshComponent.md#getphysicsangularvelocityindegrees)

___

### GetPhysicsAngularVelocityInRadians

▸ **GetPhysicsAngularVelocityInRadians**(`BoneName?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName?` | `string` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetPhysicsAngularVelocityInRadians](ue_ue.InstancedStaticMeshComponent.md#getphysicsangularvelocityinradians)

___

### GetPhysicsLinearVelocity

▸ **GetPhysicsLinearVelocity**(`BoneName?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName?` | `string` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetPhysicsLinearVelocity](ue_ue.InstancedStaticMeshComponent.md#getphysicslinearvelocity)

___

### GetPhysicsLinearVelocityAtPoint

▸ **GetPhysicsLinearVelocityAtPoint**(`Point`, `BoneName?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Point` | [`Vector`](ue_ue_s.Vector.md) |
| `BoneName?` | `string` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetPhysicsLinearVelocityAtPoint](ue_ue.InstancedStaticMeshComponent.md#getphysicslinearvelocityatpoint)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetPhysicsVolume](ue_ue.InstancedStaticMeshComponent.md#getphysicsvolume)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetRelativeTransform](ue_ue.InstancedStaticMeshComponent.md#getrelativetransform)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetRightVector](ue_ue.InstancedStaticMeshComponent.md#getrightvector)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.InstancedStaticMeshComponent.md#getshouldupdatephysicsvolume)

___

### GetSocketLocation

▸ **GetSocketLocation**(`InSocketName`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSocketName` | `string` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetSocketLocation](ue_ue.InstancedStaticMeshComponent.md#getsocketlocation)

___

### GetSocketQuaternion

▸ **GetSocketQuaternion**(`InSocketName`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSocketName` | `string` |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetSocketQuaternion](ue_ue.InstancedStaticMeshComponent.md#getsocketquaternion)

___

### GetSocketRotation

▸ **GetSocketRotation**(`InSocketName`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSocketName` | `string` |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetSocketRotation](ue_ue.InstancedStaticMeshComponent.md#getsocketrotation)

___

### GetSocketTransform

▸ **GetSocketTransform**(`InSocketName`, `TransformSpace?`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSocketName` | `string` |
| `TransformSpace?` | [`ERelativeTransformSpace`](../enums/ue_ue.ERelativeTransformSpace.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetSocketTransform](ue_ue.InstancedStaticMeshComponent.md#getsockettransform)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetUpVector](ue_ue.InstancedStaticMeshComponent.md#getupvector)

___

### GetWalkableSlopeOverride

▸ **GetWalkableSlopeOverride**(): [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Returns

[`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetWalkableSlopeOverride](ue_ue.InstancedStaticMeshComponent.md#getwalkableslopeoverride)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[GetWorld](ue_ue.InstancedStaticMeshComponent.md#getworld)

___

### IgnoreActorWhenMoving

▸ **IgnoreActorWhenMoving**(`Actor`, `bShouldIgnore`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `bShouldIgnore` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[IgnoreActorWhenMoving](ue_ue.InstancedStaticMeshComponent.md#ignoreactorwhenmoving)

___

### IgnoreComponentWhenMoving

▸ **IgnoreComponentWhenMoving**(`Component`, `bShouldIgnore`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Component` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `bShouldIgnore` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[IgnoreComponentWhenMoving](ue_ue.InstancedStaticMeshComponent.md#ignorecomponentwhenmoving)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[IsActive](ue_ue.InstancedStaticMeshComponent.md#isactive)

___

### IsAnyRigidBodyAwake

▸ **IsAnyRigidBodyAwake**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[IsAnyRigidBodyAwake](ue_ue.InstancedStaticMeshComponent.md#isanyrigidbodyawake)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[IsAnySimulatingPhysics](ue_ue.InstancedStaticMeshComponent.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[IsBeingDestroyed](ue_ue.InstancedStaticMeshComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[IsComponentTickEnabled](ue_ue.InstancedStaticMeshComponent.md#iscomponenttickenabled)

___

### IsGravityEnabled

▸ **IsGravityEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[IsGravityEnabled](ue_ue.InstancedStaticMeshComponent.md#isgravityenabled)

___

### IsMaterialSlotNameValid

▸ **IsMaterialSlotNameValid**(`MaterialSlotName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialSlotName` | `string` |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[IsMaterialSlotNameValid](ue_ue.InstancedStaticMeshComponent.md#ismaterialslotnamevalid)

___

### IsOverlappingActor

▸ **IsOverlappingActor**(`Other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[IsOverlappingActor](ue_ue.InstancedStaticMeshComponent.md#isoverlappingactor)

___

### IsOverlappingComponent

▸ **IsOverlappingComponent**(`OtherComp`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherComp` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[IsOverlappingComponent](ue_ue.InstancedStaticMeshComponent.md#isoverlappingcomponent)

___

### IsSimulatingPhysics

▸ **IsSimulatingPhysics**(`BoneName?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName?` | `string` |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[IsSimulatingPhysics](ue_ue.InstancedStaticMeshComponent.md#issimulatingphysics)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[IsVisible](ue_ue.InstancedStaticMeshComponent.md#isvisible)

___

### K2\_AddLocalOffset

▸ **K2_AddLocalOffset**(`DeltaLocation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_AddLocalOffset](ue_ue.InstancedStaticMeshComponent.md#k2_addlocaloffset)

___

### K2\_AddLocalRotation

▸ **K2_AddLocalRotation**(`DeltaRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_AddLocalRotation](ue_ue.InstancedStaticMeshComponent.md#k2_addlocalrotation)

___

### K2\_AddLocalTransform

▸ **K2_AddLocalTransform**(`DeltaTransform`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_AddLocalTransform](ue_ue.InstancedStaticMeshComponent.md#k2_addlocaltransform)

___

### K2\_AddRelativeLocation

▸ **K2_AddRelativeLocation**(`DeltaLocation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_AddRelativeLocation](ue_ue.InstancedStaticMeshComponent.md#k2_addrelativelocation)

___

### K2\_AddRelativeRotation

▸ **K2_AddRelativeRotation**(`DeltaRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_AddRelativeRotation](ue_ue.InstancedStaticMeshComponent.md#k2_addrelativerotation)

___

### K2\_AddWorldOffset

▸ **K2_AddWorldOffset**(`DeltaLocation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_AddWorldOffset](ue_ue.InstancedStaticMeshComponent.md#k2_addworldoffset)

___

### K2\_AddWorldRotation

▸ **K2_AddWorldRotation**(`DeltaRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_AddWorldRotation](ue_ue.InstancedStaticMeshComponent.md#k2_addworldrotation)

___

### K2\_AddWorldTransform

▸ **K2_AddWorldTransform**(`DeltaTransform`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_AddWorldTransform](ue_ue.InstancedStaticMeshComponent.md#k2_addworldtransform)

___

### K2\_AttachTo

▸ **K2_AttachTo**(`InParent`, `InSocketName?`, `AttachType?`, `bWeldSimulatedBodies?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InParent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `InSocketName?` | `string` |
| `AttachType?` | [`EAttachLocation`](../enums/ue_ue.EAttachLocation.md) |
| `bWeldSimulatedBodies?` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_AttachTo](ue_ue.InstancedStaticMeshComponent.md#k2_attachto)

___

### K2\_AttachToComponent

▸ **K2_AttachToComponent**(`Parent`, `SocketName`, `LocationRule`, `RotationRule`, `ScaleRule`, `bWeldSimulatedBodies`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Parent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `SocketName` | `string` |
| `LocationRule` | [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md) |
| `RotationRule` | [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md) |
| `ScaleRule` | [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md) |
| `bWeldSimulatedBodies` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_AttachToComponent](ue_ue.InstancedStaticMeshComponent.md#k2_attachtocomponent)

___

### K2\_BoxOverlapComponent

▸ **K2_BoxOverlapComponent**(`InBoxCentre`, `InBox`, `bTraceComplex`, `bShowTrace`, `bPersistentShowTrace`, `HitLocation`, `HitNormal`, `BoneName`, `OutHit`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBoxCentre` | [`Vector`](ue_ue_s.Vector.md) |
| `InBox` | [`Box`](ue_ue.Box.md) |
| `bTraceComplex` | `boolean` |
| `bShowTrace` | `boolean` |
| `bPersistentShowTrace` | `boolean` |
| `HitLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `HitNormal` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `BoneName` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `OutHit` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_BoxOverlapComponent](ue_ue.InstancedStaticMeshComponent.md#k2_boxoverlapcomponent)

___

### K2\_DestroyComponent

▸ **K2_DestroyComponent**(`Object`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Object` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_DestroyComponent](ue_ue.InstancedStaticMeshComponent.md#k2_destroycomponent)

___

### K2\_DetachFromComponent

▸ **K2_DetachFromComponent**(`LocationRule?`, `RotationRule?`, `ScaleRule?`, `bCallModify?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LocationRule?` | [`EDetachmentRule`](../enums/ue_ue.EDetachmentRule.md) |
| `RotationRule?` | [`EDetachmentRule`](../enums/ue_ue.EDetachmentRule.md) |
| `ScaleRule?` | [`EDetachmentRule`](../enums/ue_ue.EDetachmentRule.md) |
| `bCallModify?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_DetachFromComponent](ue_ue.InstancedStaticMeshComponent.md#k2_detachfromcomponent)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_GetComponentLocation](ue_ue.InstancedStaticMeshComponent.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_GetComponentRotation](ue_ue.InstancedStaticMeshComponent.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_GetComponentScale](ue_ue.InstancedStaticMeshComponent.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_GetComponentToWorld](ue_ue.InstancedStaticMeshComponent.md#k2_getcomponenttoworld)

___

### K2\_IsCollisionEnabled

▸ **K2_IsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_IsCollisionEnabled](ue_ue.InstancedStaticMeshComponent.md#k2_iscollisionenabled)

___

### K2\_IsPhysicsCollisionEnabled

▸ **K2_IsPhysicsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_IsPhysicsCollisionEnabled](ue_ue.InstancedStaticMeshComponent.md#k2_isphysicscollisionenabled)

___

### K2\_IsQueryCollisionEnabled

▸ **K2_IsQueryCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_IsQueryCollisionEnabled](ue_ue.InstancedStaticMeshComponent.md#k2_isquerycollisionenabled)

___

### K2\_LineTraceComponent

▸ **K2_LineTraceComponent**(`TraceStart`, `TraceEnd`, `bTraceComplex`, `bShowTrace`, `bPersistentShowTrace`, `HitLocation`, `HitNormal`, `BoneName`, `OutHit`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TraceStart` | [`Vector`](ue_ue_s.Vector.md) |
| `TraceEnd` | [`Vector`](ue_ue_s.Vector.md) |
| `bTraceComplex` | `boolean` |
| `bShowTrace` | `boolean` |
| `bPersistentShowTrace` | `boolean` |
| `HitLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `HitNormal` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `BoneName` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `OutHit` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_LineTraceComponent](ue_ue.InstancedStaticMeshComponent.md#k2_linetracecomponent)

___

### K2\_SetRelativeLocation

▸ **K2_SetRelativeLocation**(`NewLocation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_SetRelativeLocation](ue_ue.InstancedStaticMeshComponent.md#k2_setrelativelocation)

___

### K2\_SetRelativeLocationAndRotation

▸ **K2_SetRelativeLocationAndRotation**(`NewLocation`, `NewRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.InstancedStaticMeshComponent.md#k2_setrelativelocationandrotation)

___

### K2\_SetRelativeRotation

▸ **K2_SetRelativeRotation**(`NewRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_SetRelativeRotation](ue_ue.InstancedStaticMeshComponent.md#k2_setrelativerotation)

___

### K2\_SetRelativeTransform

▸ **K2_SetRelativeTransform**(`NewTransform`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_SetRelativeTransform](ue_ue.InstancedStaticMeshComponent.md#k2_setrelativetransform)

___

### K2\_SetWorldLocation

▸ **K2_SetWorldLocation**(`NewLocation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_SetWorldLocation](ue_ue.InstancedStaticMeshComponent.md#k2_setworldlocation)

___

### K2\_SetWorldLocationAndRotation

▸ **K2_SetWorldLocationAndRotation**(`NewLocation`, `NewRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.InstancedStaticMeshComponent.md#k2_setworldlocationandrotation)

___

### K2\_SetWorldRotation

▸ **K2_SetWorldRotation**(`NewRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_SetWorldRotation](ue_ue.InstancedStaticMeshComponent.md#k2_setworldrotation)

___

### K2\_SetWorldTransform

▸ **K2_SetWorldTransform**(`NewTransform`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_SetWorldTransform](ue_ue.InstancedStaticMeshComponent.md#k2_setworldtransform)

___

### K2\_SphereOverlapComponent

▸ **K2_SphereOverlapComponent**(`InSphereCentre`, `InSphereRadius`, `bTraceComplex`, `bShowTrace`, `bPersistentShowTrace`, `HitLocation`, `HitNormal`, `BoneName`, `OutHit`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSphereCentre` | [`Vector`](ue_ue_s.Vector.md) |
| `InSphereRadius` | `number` |
| `bTraceComplex` | `boolean` |
| `bShowTrace` | `boolean` |
| `bPersistentShowTrace` | `boolean` |
| `HitLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `HitNormal` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `BoneName` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `OutHit` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_SphereOverlapComponent](ue_ue.InstancedStaticMeshComponent.md#k2_sphereoverlapcomponent)

___

### K2\_SphereTraceComponent

▸ **K2_SphereTraceComponent**(`TraceStart`, `TraceEnd`, `SphereRadius`, `bTraceComplex`, `bShowTrace`, `bPersistentShowTrace`, `HitLocation`, `HitNormal`, `BoneName`, `OutHit`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TraceStart` | [`Vector`](ue_ue_s.Vector.md) |
| `TraceEnd` | [`Vector`](ue_ue_s.Vector.md) |
| `SphereRadius` | `number` |
| `bTraceComplex` | `boolean` |
| `bShowTrace` | `boolean` |
| `bPersistentShowTrace` | `boolean` |
| `HitLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `HitNormal` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `BoneName` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `OutHit` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[K2_SphereTraceComponent](ue_ue.InstancedStaticMeshComponent.md#k2_spheretracecomponent)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnRep_AttachChildren](ue_ue.InstancedStaticMeshComponent.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnRep_AttachParent](ue_ue.InstancedStaticMeshComponent.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnRep_AttachSocketName](ue_ue.InstancedStaticMeshComponent.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnRep_IsActive](ue_ue.InstancedStaticMeshComponent.md#onrep_isactive)

___

### OnRep\_StaticMesh

▸ **OnRep_StaticMesh**(`OldStaticMesh`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OldStaticMesh` | [`$Nullable`](../modules/puerts.md#$nullable)<[`StaticMesh`](ue_ue.StaticMesh.md)\> |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnRep_StaticMesh](ue_ue.InstancedStaticMeshComponent.md#onrep_staticmesh)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnRep_Transform](ue_ue.InstancedStaticMeshComponent.md#onrep_transform)

___

### OnRep\_Visibility

▸ **OnRep_Visibility**(`OldValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OldValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[OnRep_Visibility](ue_ue.InstancedStaticMeshComponent.md#onrep_visibility)

___

### PrestreamTextures

▸ **PrestreamTextures**(`Seconds`, `bPrioritizeCharacterTextures`, `CinematicTextureGroups?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Seconds` | `number` |
| `bPrioritizeCharacterTextures` | `boolean` |
| `CinematicTextureGroups?` | `number` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[PrestreamTextures](ue_ue.InstancedStaticMeshComponent.md#prestreamtextures)

___

### PutRigidBodyToSleep

▸ **PutRigidBodyToSleep**(`BoneName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName?` | `string` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[PutRigidBodyToSleep](ue_ue.InstancedStaticMeshComponent.md#putrigidbodytosleep)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ReceiveBeginPlay](ue_ue.InstancedStaticMeshComponent.md#receivebeginplay)

___

### ReceiveEndPlay

▸ **ReceiveEndPlay**(`EndPlayReason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EndPlayReason` | [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md) |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ReceiveEndPlay](ue_ue.InstancedStaticMeshComponent.md#receiveendplay)

___

### ReceiveTick

▸ **ReceiveTick**(`DeltaSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaSeconds` | `number` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ReceiveTick](ue_ue.InstancedStaticMeshComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[RegisterComponent](ue_ue.InstancedStaticMeshComponent.md#registercomponent)

___

### RemoveInstance

▸ **RemoveInstance**(`InstanceIndex`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InstanceIndex` | `number` |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[RemoveInstance](ue_ue.InstancedStaticMeshComponent.md#removeinstance)

___

### RemoveInstances

▸ **RemoveInstances**(`InstancesToRemove`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InstancesToRemove` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`boolean`

___

### RemoveTickPrerequisiteActor

▸ **RemoveTickPrerequisiteActor**(`PrerequisiteActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[RemoveTickPrerequisiteActor](ue_ue.InstancedStaticMeshComponent.md#removetickprerequisiteactor)

___

### RemoveTickPrerequisiteComponent

▸ **RemoveTickPrerequisiteComponent**(`PrerequisiteComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\> |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.InstancedStaticMeshComponent.md#removetickprerequisitecomponent)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ResetRelativeTransform](ue_ue.InstancedStaticMeshComponent.md#resetrelativetransform)

___

### ScaleByMomentOfInertia

▸ **ScaleByMomentOfInertia**(`InputVector`, `BoneName?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InputVector` | [`Vector`](ue_ue_s.Vector.md) |
| `BoneName?` | `string` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ScaleByMomentOfInertia](ue_ue.InstancedStaticMeshComponent.md#scalebymomentofinertia)

___

### SetAbsolute

▸ **SetAbsolute**(`bNewAbsoluteLocation?`, `bNewAbsoluteRotation?`, `bNewAbsoluteScale?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewAbsoluteLocation?` | `boolean` |
| `bNewAbsoluteRotation?` | `boolean` |
| `bNewAbsoluteScale?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetAbsolute](ue_ue.InstancedStaticMeshComponent.md#setabsolute)

___

### SetActive

▸ **SetActive**(`bNewActive`, `bReset?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewActive` | `boolean` |
| `bReset?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetActive](ue_ue.InstancedStaticMeshComponent.md#setactive)

___

### SetAllMassScale

▸ **SetAllMassScale**(`InMassScale?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InMassScale?` | `number` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetAllMassScale](ue_ue.InstancedStaticMeshComponent.md#setallmassscale)

___

### SetAllPhysicsAngularVelocityInDegrees

▸ **SetAllPhysicsAngularVelocityInDegrees**(`NewAngVel`, `bAddToCurrent?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAngVel` | [`Vector`](ue_ue_s.Vector.md) |
| `bAddToCurrent?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetAllPhysicsAngularVelocityInDegrees](ue_ue.InstancedStaticMeshComponent.md#setallphysicsangularvelocityindegrees)

___

### SetAllPhysicsAngularVelocityInRadians

▸ **SetAllPhysicsAngularVelocityInRadians**(`NewAngVel`, `bAddToCurrent?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAngVel` | [`Vector`](ue_ue_s.Vector.md) |
| `bAddToCurrent?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetAllPhysicsAngularVelocityInRadians](ue_ue.InstancedStaticMeshComponent.md#setallphysicsangularvelocityinradians)

___

### SetAllPhysicsLinearVelocity

▸ **SetAllPhysicsLinearVelocity**(`NewVel`, `bAddToCurrent?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewVel` | [`Vector`](ue_ue_s.Vector.md) |
| `bAddToCurrent?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetAllPhysicsLinearVelocity](ue_ue.InstancedStaticMeshComponent.md#setallphysicslinearvelocity)

___

### SetAllUseCCD

▸ **SetAllUseCCD**(`InUseCCD`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InUseCCD` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetAllUseCCD](ue_ue.InstancedStaticMeshComponent.md#setalluseccd)

___

### SetAngularDamping

▸ **SetAngularDamping**(`InDamping`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InDamping` | `number` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetAngularDamping](ue_ue.InstancedStaticMeshComponent.md#setangulardamping)

___

### SetAutoActivate

▸ **SetAutoActivate**(`bNewAutoActivate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewAutoActivate` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetAutoActivate](ue_ue.InstancedStaticMeshComponent.md#setautoactivate)

___

### SetBoundsScale

▸ **SetBoundsScale**(`NewBoundsScale?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewBoundsScale?` | `number` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetBoundsScale](ue_ue.InstancedStaticMeshComponent.md#setboundsscale)

___

### SetCastInsetShadow

▸ **SetCastInsetShadow**(`bInCastInsetShadow`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInCastInsetShadow` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetCastInsetShadow](ue_ue.InstancedStaticMeshComponent.md#setcastinsetshadow)

___

### SetCastShadow

▸ **SetCastShadow**(`NewCastShadow`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewCastShadow` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetCastShadow](ue_ue.InstancedStaticMeshComponent.md#setcastshadow)

___

### SetCenterOfMass

▸ **SetCenterOfMass**(`CenterOfMassOffset`, `BoneName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `CenterOfMassOffset` | [`Vector`](ue_ue_s.Vector.md) |
| `BoneName?` | `string` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetCenterOfMass](ue_ue.InstancedStaticMeshComponent.md#setcenterofmass)

___

### SetCollisionEnabled

▸ **SetCollisionEnabled**(`NewType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewType` | [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md) |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetCollisionEnabled](ue_ue.InstancedStaticMeshComponent.md#setcollisionenabled)

___

### SetCollisionObjectType

▸ **SetCollisionObjectType**(`Channel`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Channel` | [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md) |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetCollisionObjectType](ue_ue.InstancedStaticMeshComponent.md#setcollisionobjecttype)

___

### SetCollisionProfileName

▸ **SetCollisionProfileName**(`InCollisionProfileName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InCollisionProfileName` | `string` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetCollisionProfileName](ue_ue.InstancedStaticMeshComponent.md#setcollisionprofilename)

___

### SetCollisionResponseToAllChannels

▸ **SetCollisionResponseToAllChannels**(`NewResponse`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewResponse` | [`ECollisionResponse`](../enums/ue_ue.ECollisionResponse.md) |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetCollisionResponseToAllChannels](ue_ue.InstancedStaticMeshComponent.md#setcollisionresponsetoallchannels)

___

### SetCollisionResponseToChannel

▸ **SetCollisionResponseToChannel**(`Channel`, `NewResponse`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Channel` | [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md) |
| `NewResponse` | [`ECollisionResponse`](../enums/ue_ue.ECollisionResponse.md) |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetCollisionResponseToChannel](ue_ue.InstancedStaticMeshComponent.md#setcollisionresponsetochannel)

___

### SetComponentTickEnabled

▸ **SetComponentTickEnabled**(`bEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnabled` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetComponentTickEnabled](ue_ue.InstancedStaticMeshComponent.md#setcomponenttickenabled)

___

### SetComponentTickInterval

▸ **SetComponentTickInterval**(`TickInterval`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TickInterval` | `number` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetComponentTickInterval](ue_ue.InstancedStaticMeshComponent.md#setcomponenttickinterval)

___

### SetConstraintMode

▸ **SetConstraintMode**(`ConstraintMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ConstraintMode` | [`EDOFMode`](../enums/ue_ue.EDOFMode.md) |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetConstraintMode](ue_ue.InstancedStaticMeshComponent.md#setconstraintmode)

___

### SetCullDistance

▸ **SetCullDistance**(`NewCullDistance`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewCullDistance` | `number` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetCullDistance](ue_ue.InstancedStaticMeshComponent.md#setculldistance)

___

### SetCullDistances

▸ **SetCullDistances**(`StartCullDistance`, `EndCullDistance`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StartCullDistance` | `number` |
| `EndCullDistance` | `number` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetCullDistances](ue_ue.InstancedStaticMeshComponent.md#setculldistances)

___

### SetCustomDepthStencilValue

▸ **SetCustomDepthStencilValue**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetCustomDepthStencilValue](ue_ue.InstancedStaticMeshComponent.md#setcustomdepthstencilvalue)

___

### SetCustomDepthStencilWriteMask

▸ **SetCustomDepthStencilWriteMask**(`WriteMaskBit`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WriteMaskBit` | [`ERendererStencilMask`](../enums/ue_ue.ERendererStencilMask.md) |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetCustomDepthStencilWriteMask](ue_ue.InstancedStaticMeshComponent.md#setcustomdepthstencilwritemask)

___

### SetCustomPrimitiveDataFloat

▸ **SetCustomPrimitiveDataFloat**(`DataIndex`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DataIndex` | `number` |
| `Value` | `number` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetCustomPrimitiveDataFloat](ue_ue.InstancedStaticMeshComponent.md#setcustomprimitivedatafloat)

___

### SetCustomPrimitiveDataVector2

▸ **SetCustomPrimitiveDataVector2**(`DataIndex`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DataIndex` | `number` |
| `Value` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetCustomPrimitiveDataVector2](ue_ue.InstancedStaticMeshComponent.md#setcustomprimitivedatavector2)

___

### SetCustomPrimitiveDataVector3

▸ **SetCustomPrimitiveDataVector3**(`DataIndex`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DataIndex` | `number` |
| `Value` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetCustomPrimitiveDataVector3](ue_ue.InstancedStaticMeshComponent.md#setcustomprimitivedatavector3)

___

### SetCustomPrimitiveDataVector4

▸ **SetCustomPrimitiveDataVector4**(`DataIndex`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DataIndex` | `number` |
| `Value` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetCustomPrimitiveDataVector4](ue_ue.InstancedStaticMeshComponent.md#setcustomprimitivedatavector4)

___

### SetDistanceFieldSelfShadowBias

▸ **SetDistanceFieldSelfShadowBias**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetDistanceFieldSelfShadowBias](ue_ue.InstancedStaticMeshComponent.md#setdistancefieldselfshadowbias)

___

### SetEnableGravity

▸ **SetEnableGravity**(`bGravityEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bGravityEnabled` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetEnableGravity](ue_ue.InstancedStaticMeshComponent.md#setenablegravity)

___

### SetExcludeFromLightAttachmentGroup

▸ **SetExcludeFromLightAttachmentGroup**(`bInExcludeFromLightAttachmentGroup`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInExcludeFromLightAttachmentGroup` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetExcludeFromLightAttachmentGroup](ue_ue.InstancedStaticMeshComponent.md#setexcludefromlightattachmentgroup)

___

### SetForcedLodModel

▸ **SetForcedLodModel**(`NewForcedLodModel`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewForcedLodModel` | `number` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetForcedLodModel](ue_ue.InstancedStaticMeshComponent.md#setforcedlodmodel)

___

### SetGenerateOverlapEvents

▸ **SetGenerateOverlapEvents**(`bInGenerateOverlapEvents`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInGenerateOverlapEvents` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetGenerateOverlapEvents](ue_ue.InstancedStaticMeshComponent.md#setgenerateoverlapevents)

___

### SetHiddenInGame

▸ **SetHiddenInGame**(`NewHidden`, `bPropagateToChildren?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewHidden` | `boolean` |
| `bPropagateToChildren?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetHiddenInGame](ue_ue.InstancedStaticMeshComponent.md#sethiddeningame)

___

### SetIsReplicated

▸ **SetIsReplicated**(`ShouldReplicate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ShouldReplicate` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetIsReplicated](ue_ue.InstancedStaticMeshComponent.md#setisreplicated)

___

### SetLightAttachmentsAsGroup

▸ **SetLightAttachmentsAsGroup**(`bInLightAttachmentsAsGroup`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInLightAttachmentsAsGroup` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetLightAttachmentsAsGroup](ue_ue.InstancedStaticMeshComponent.md#setlightattachmentsasgroup)

___

### SetLinearDamping

▸ **SetLinearDamping**(`InDamping`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InDamping` | `number` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetLinearDamping](ue_ue.InstancedStaticMeshComponent.md#setlineardamping)

___

### SetMassOverrideInKg

▸ **SetMassOverrideInKg**(`BoneName?`, `MassInKg?`, `bOverrideMass?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName?` | `string` |
| `MassInKg?` | `number` |
| `bOverrideMass?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetMassOverrideInKg](ue_ue.InstancedStaticMeshComponent.md#setmassoverrideinkg)

___

### SetMassScale

▸ **SetMassScale**(`BoneName?`, `InMassScale?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName?` | `string` |
| `InMassScale?` | `number` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetMassScale](ue_ue.InstancedStaticMeshComponent.md#setmassscale)

___

### SetMaterial

▸ **SetMaterial**(`ElementIndex`, `Material`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ElementIndex` | `number` |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetMaterial](ue_ue.InstancedStaticMeshComponent.md#setmaterial)

___

### SetMaterialByName

▸ **SetMaterialByName**(`MaterialSlotName`, `Material`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialSlotName` | `string` |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetMaterialByName](ue_ue.InstancedStaticMeshComponent.md#setmaterialbyname)

___

### SetMobility

▸ **SetMobility**(`NewMobility`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMobility` | [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md) |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetMobility](ue_ue.InstancedStaticMeshComponent.md#setmobility)

___

### SetNotifyRigidBodyCollision

▸ **SetNotifyRigidBodyCollision**(`bNewNotifyRigidBodyCollision`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewNotifyRigidBodyCollision` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetNotifyRigidBodyCollision](ue_ue.InstancedStaticMeshComponent.md#setnotifyrigidbodycollision)

___

### SetOnlyOwnerSee

▸ **SetOnlyOwnerSee**(`bNewOnlyOwnerSee`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewOnlyOwnerSee` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetOnlyOwnerSee](ue_ue.InstancedStaticMeshComponent.md#setonlyownersee)

___

### SetOwnerNoSee

▸ **SetOwnerNoSee**(`bNewOwnerNoSee`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewOwnerNoSee` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetOwnerNoSee](ue_ue.InstancedStaticMeshComponent.md#setownernosee)

___

### SetPhysMaterialOverride

▸ **SetPhysMaterialOverride**(`NewPhysMaterial`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPhysMaterial` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)\> |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetPhysMaterialOverride](ue_ue.InstancedStaticMeshComponent.md#setphysmaterialoverride)

___

### SetPhysicsAngularVelocity

▸ **SetPhysicsAngularVelocity**(`NewAngVel`, `bAddToCurrent?`, `BoneName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAngVel` | [`Vector`](ue_ue_s.Vector.md) |
| `bAddToCurrent?` | `boolean` |
| `BoneName?` | `string` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetPhysicsAngularVelocity](ue_ue.InstancedStaticMeshComponent.md#setphysicsangularvelocity)

___

### SetPhysicsAngularVelocityInDegrees

▸ **SetPhysicsAngularVelocityInDegrees**(`NewAngVel`, `bAddToCurrent?`, `BoneName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAngVel` | [`Vector`](ue_ue_s.Vector.md) |
| `bAddToCurrent?` | `boolean` |
| `BoneName?` | `string` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetPhysicsAngularVelocityInDegrees](ue_ue.InstancedStaticMeshComponent.md#setphysicsangularvelocityindegrees)

___

### SetPhysicsAngularVelocityInRadians

▸ **SetPhysicsAngularVelocityInRadians**(`NewAngVel`, `bAddToCurrent?`, `BoneName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAngVel` | [`Vector`](ue_ue_s.Vector.md) |
| `bAddToCurrent?` | `boolean` |
| `BoneName?` | `string` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetPhysicsAngularVelocityInRadians](ue_ue.InstancedStaticMeshComponent.md#setphysicsangularvelocityinradians)

___

### SetPhysicsLinearVelocity

▸ **SetPhysicsLinearVelocity**(`NewVel`, `bAddToCurrent?`, `BoneName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewVel` | [`Vector`](ue_ue_s.Vector.md) |
| `bAddToCurrent?` | `boolean` |
| `BoneName?` | `string` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetPhysicsLinearVelocity](ue_ue.InstancedStaticMeshComponent.md#setphysicslinearvelocity)

___

### SetPhysicsMaxAngularVelocity

▸ **SetPhysicsMaxAngularVelocity**(`NewMaxAngVel`, `bAddToCurrent?`, `BoneName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMaxAngVel` | `number` |
| `bAddToCurrent?` | `boolean` |
| `BoneName?` | `string` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetPhysicsMaxAngularVelocity](ue_ue.InstancedStaticMeshComponent.md#setphysicsmaxangularvelocity)

___

### SetPhysicsMaxAngularVelocityInDegrees

▸ **SetPhysicsMaxAngularVelocityInDegrees**(`NewMaxAngVel`, `bAddToCurrent?`, `BoneName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMaxAngVel` | `number` |
| `bAddToCurrent?` | `boolean` |
| `BoneName?` | `string` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetPhysicsMaxAngularVelocityInDegrees](ue_ue.InstancedStaticMeshComponent.md#setphysicsmaxangularvelocityindegrees)

___

### SetPhysicsMaxAngularVelocityInRadians

▸ **SetPhysicsMaxAngularVelocityInRadians**(`NewMaxAngVel`, `bAddToCurrent?`, `BoneName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMaxAngVel` | `number` |
| `bAddToCurrent?` | `boolean` |
| `BoneName?` | `string` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetPhysicsMaxAngularVelocityInRadians](ue_ue.InstancedStaticMeshComponent.md#setphysicsmaxangularvelocityinradians)

___

### SetReceivesDecals

▸ **SetReceivesDecals**(`bNewReceivesDecals`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewReceivesDecals` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetReceivesDecals](ue_ue.InstancedStaticMeshComponent.md#setreceivesdecals)

___

### SetRelativeScale3D

▸ **SetRelativeScale3D**(`NewScale3D`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScale3D` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetRelativeScale3D](ue_ue.InstancedStaticMeshComponent.md#setrelativescale3d)

___

### SetRenderCustomDepth

▸ **SetRenderCustomDepth**(`bValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetRenderCustomDepth](ue_ue.InstancedStaticMeshComponent.md#setrendercustomdepth)

___

### SetRenderInMainPass

▸ **SetRenderInMainPass**(`bValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetRenderInMainPass](ue_ue.InstancedStaticMeshComponent.md#setrenderinmainpass)

___

### SetReverseCulling

▸ **SetReverseCulling**(`ReverseCulling`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ReverseCulling` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetReverseCulling](ue_ue.InstancedStaticMeshComponent.md#setreverseculling)

___

### SetScalarParameterValueOnMaterials

▸ **SetScalarParameterValueOnMaterials**(`ParameterName`, `ParameterValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `ParameterValue` | `number` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetScalarParameterValueOnMaterials](ue_ue.InstancedStaticMeshComponent.md#setscalarparametervalueonmaterials)

___

### SetShouldUpdatePhysicsVolume

▸ **SetShouldUpdatePhysicsVolume**(`bInShouldUpdatePhysicsVolume`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInShouldUpdatePhysicsVolume` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.InstancedStaticMeshComponent.md#setshouldupdatephysicsvolume)

___

### SetSimulatePhysics

▸ **SetSimulatePhysics**(`bSimulate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bSimulate` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetSimulatePhysics](ue_ue.InstancedStaticMeshComponent.md#setsimulatephysics)

___

### SetSingleSampleShadowFromStationaryLights

▸ **SetSingleSampleShadowFromStationaryLights**(`bNewSingleSampleShadowFromStationaryLights`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewSingleSampleShadowFromStationaryLights` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetSingleSampleShadowFromStationaryLights](ue_ue.InstancedStaticMeshComponent.md#setsinglesampleshadowfromstationarylights)

___

### SetStaticMesh

▸ **SetStaticMesh**(`NewMesh`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMesh` | [`$Nullable`](../modules/puerts.md#$nullable)<[`StaticMesh`](ue_ue.StaticMesh.md)\> |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetStaticMesh](ue_ue.InstancedStaticMeshComponent.md#setstaticmesh)

___

### SetTickGroup

▸ **SetTickGroup**(`NewTickGroup`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTickGroup` | [`ETickingGroup`](../enums/ue_ue.ETickingGroup.md) |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetTickGroup](ue_ue.InstancedStaticMeshComponent.md#settickgroup)

___

### SetTickableWhenPaused

▸ **SetTickableWhenPaused**(`bTickableWhenPaused`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bTickableWhenPaused` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetTickableWhenPaused](ue_ue.InstancedStaticMeshComponent.md#settickablewhenpaused)

___

### SetTranslucentSortPriority

▸ **SetTranslucentSortPriority**(`NewTranslucentSortPriority`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTranslucentSortPriority` | `number` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetTranslucentSortPriority](ue_ue.InstancedStaticMeshComponent.md#settranslucentsortpriority)

___

### SetUseCCD

▸ **SetUseCCD**(`InUseCCD`, `BoneName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InUseCCD` | `boolean` |
| `BoneName?` | `string` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetUseCCD](ue_ue.InstancedStaticMeshComponent.md#setuseccd)

___

### SetVectorParameterValueOnMaterials

▸ **SetVectorParameterValueOnMaterials**(`ParameterName`, `ParameterValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `ParameterValue` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetVectorParameterValueOnMaterials](ue_ue.InstancedStaticMeshComponent.md#setvectorparametervalueonmaterials)

___

### SetVisibility

▸ **SetVisibility**(`bNewVisibility`, `bPropagateToChildren?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewVisibility` | `boolean` |
| `bPropagateToChildren?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetVisibility](ue_ue.InstancedStaticMeshComponent.md#setvisibility)

___

### SetWalkableSlopeOverride

▸ **SetWalkableSlopeOverride**(`NewOverride`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewOverride` | [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md) |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetWalkableSlopeOverride](ue_ue.InstancedStaticMeshComponent.md#setwalkableslopeoverride)

___

### SetWorldScale3D

▸ **SetWorldScale3D**(`NewScale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScale` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetWorldScale3D](ue_ue.InstancedStaticMeshComponent.md#setworldscale3d)

___

### SetupAttachment

▸ **SetupAttachment**(`p0`, `p1`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`SceneComponent`](ue_ue.SceneComponent.md) |
| `p1` | `string` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SetupAttachment](ue_ue.InstancedStaticMeshComponent.md#setupattachment)

___

### SnapTo

▸ **SnapTo**(`InParent`, `InSocketName?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InParent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `InSocketName?` | `string` |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[SnapTo](ue_ue.InstancedStaticMeshComponent.md#snapto)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ToggleActive](ue_ue.InstancedStaticMeshComponent.md#toggleactive)

___

### ToggleVisibility

▸ **ToggleVisibility**(`bPropagateToChildren?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bPropagateToChildren?` | `boolean` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[ToggleVisibility](ue_ue.InstancedStaticMeshComponent.md#togglevisibility)

___

### UpdateInstanceTransform

▸ **UpdateInstanceTransform**(`InstanceIndex`, `NewInstanceTransform`, `bWorldSpace?`, `bMarkRenderStateDirty?`, `bTeleport?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InstanceIndex` | `number` |
| `NewInstanceTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `bWorldSpace?` | `boolean` |
| `bMarkRenderStateDirty?` | `boolean` |
| `bTeleport?` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[UpdateInstanceTransform](ue_ue.InstancedStaticMeshComponent.md#updateinstancetransform)

___

### WakeAllRigidBodies

▸ **WakeAllRigidBodies**(): `void`

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[WakeAllRigidBodies](ue_ue.InstancedStaticMeshComponent.md#wakeallrigidbodies)

___

### WakeRigidBody

▸ **WakeRigidBody**(`BoneName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName?` | `string` |

#### Returns

`void`

#### Inherited from

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[WakeRigidBody](ue_ue.InstancedStaticMeshComponent.md#wakerigidbody)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`HierarchicalInstancedStaticMeshComponent`](ue_ue.HierarchicalInstancedStaticMeshComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`HierarchicalInstancedStaticMeshComponent`](ue_ue.HierarchicalInstancedStaticMeshComponent.md)

#### Overrides

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[Find](ue_ue.InstancedStaticMeshComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`HierarchicalInstancedStaticMeshComponent`](ue_ue.HierarchicalInstancedStaticMeshComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`HierarchicalInstancedStaticMeshComponent`](ue_ue.HierarchicalInstancedStaticMeshComponent.md)

#### Overrides

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[Load](ue_ue.InstancedStaticMeshComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InstancedStaticMeshComponent](ue_ue.InstancedStaticMeshComponent.md).[StaticClass](ue_ue.InstancedStaticMeshComponent.md#staticclass)
