[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GizmoHandleMeshComponent

# Class: GizmoHandleMeshComponent

[ue/ue](../modules/ue_ue.md).GizmoHandleMeshComponent

## Hierarchy

- [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

  ↳ **`GizmoHandleMeshComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.GizmoHandleMeshComponent.md#constructor)

### Properties

- [AlwaysLoadOnClient](ue_ue.GizmoHandleMeshComponent.md#alwaysloadonclient)
- [AlwaysLoadOnServer](ue_ue.GizmoHandleMeshComponent.md#alwaysloadonserver)
- [AssetUserData](ue_ue.GizmoHandleMeshComponent.md#assetuserdata)
- [AttachChildren](ue_ue.GizmoHandleMeshComponent.md#attachchildren)
- [AttachParent](ue_ue.GizmoHandleMeshComponent.md#attachparent)
- [AttachSocketName](ue_ue.GizmoHandleMeshComponent.md#attachsocketname)
- [BodyInstance](ue_ue.GizmoHandleMeshComponent.md#bodyinstance)
- [BoundsScale](ue_ue.GizmoHandleMeshComponent.md#boundsscale)
- [CachedMaxDrawDistance](ue_ue.GizmoHandleMeshComponent.md#cachedmaxdrawdistance)
- [CanBeCharacterBase](ue_ue.GizmoHandleMeshComponent.md#canbecharacterbase)
- [CanCharacterStepUpOn](ue_ue.GizmoHandleMeshComponent.md#cancharacterstepupon)
- [CastShadow](ue_ue.GizmoHandleMeshComponent.md#castshadow)
- [ClientAttachedChildren](ue_ue.GizmoHandleMeshComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.GizmoHandleMeshComponent.md#componenttags)
- [ComponentVelocity](ue_ue.GizmoHandleMeshComponent.md#componentvelocity)
- [CreationMethod](ue_ue.GizmoHandleMeshComponent.md#creationmethod)
- [CustomDepthStencilValue](ue_ue.GizmoHandleMeshComponent.md#customdepthstencilvalue)
- [CustomDepthStencilWriteMask](ue_ue.GizmoHandleMeshComponent.md#customdepthstencilwritemask)
- [CustomPrimitiveData](ue_ue.GizmoHandleMeshComponent.md#customprimitivedata)
- [DepthPriorityGroup](ue_ue.GizmoHandleMeshComponent.md#depthprioritygroup)
- [DetailMode](ue_ue.GizmoHandleMeshComponent.md#detailmode)
- [DistanceFieldIndirectShadowMinVisibility](ue_ue.GizmoHandleMeshComponent.md#distancefieldindirectshadowminvisibility)
- [DistanceFieldSelfShadowBias](ue_ue.GizmoHandleMeshComponent.md#distancefieldselfshadowbias)
- [ExcludeForSpecificHLODLevels](ue_ue.GizmoHandleMeshComponent.md#excludeforspecifichlodlevels)
- [ForcedLodModel](ue_ue.GizmoHandleMeshComponent.md#forcedlodmodel)
- [IndirectLightingCacheQuality](ue_ue.GizmoHandleMeshComponent.md#indirectlightingcachequality)
- [IrrelevantLights](ue_ue.GizmoHandleMeshComponent.md#irrelevantlights)
- [LDMaxDrawDistance](ue_ue.GizmoHandleMeshComponent.md#ldmaxdrawdistance)
- [LODData](ue_ue.GizmoHandleMeshComponent.md#loddata)
- [LODParentPrimitive](ue_ue.GizmoHandleMeshComponent.md#lodparentprimitive)
- [LightingChannels](ue_ue.GizmoHandleMeshComponent.md#lightingchannels)
- [LightmapType](ue_ue.GizmoHandleMeshComponent.md#lightmaptype)
- [LightmassSettings](ue_ue.GizmoHandleMeshComponent.md#lightmasssettings)
- [LpvBiasMultiplier](ue_ue.GizmoHandleMeshComponent.md#lpvbiasmultiplier)
- [MaterialIndexPreview](ue_ue.GizmoHandleMeshComponent.md#materialindexpreview)
- [MaterialStreamingRelativeBoxes](ue_ue.GizmoHandleMeshComponent.md#materialstreamingrelativeboxes)
- [MinDrawDistance](ue_ue.GizmoHandleMeshComponent.md#mindrawdistance)
- [MinLOD](ue_ue.GizmoHandleMeshComponent.md#minlod)
- [Mobility](ue_ue.GizmoHandleMeshComponent.md#mobility)
- [MoveIgnoreActors](ue_ue.GizmoHandleMeshComponent.md#moveignoreactors)
- [MoveIgnoreComponents](ue_ue.GizmoHandleMeshComponent.md#moveignorecomponents)
- [OnBeginCursorOver](ue_ue.GizmoHandleMeshComponent.md#onbegincursorover)
- [OnClicked](ue_ue.GizmoHandleMeshComponent.md#onclicked)
- [OnComponentActivated](ue_ue.GizmoHandleMeshComponent.md#oncomponentactivated)
- [OnComponentBeginOverlap](ue_ue.GizmoHandleMeshComponent.md#oncomponentbeginoverlap)
- [OnComponentDeactivated](ue_ue.GizmoHandleMeshComponent.md#oncomponentdeactivated)
- [OnComponentEndOverlap](ue_ue.GizmoHandleMeshComponent.md#oncomponentendoverlap)
- [OnComponentHit](ue_ue.GizmoHandleMeshComponent.md#oncomponenthit)
- [OnComponentSleep](ue_ue.GizmoHandleMeshComponent.md#oncomponentsleep)
- [OnComponentWake](ue_ue.GizmoHandleMeshComponent.md#oncomponentwake)
- [OnEndCursorOver](ue_ue.GizmoHandleMeshComponent.md#onendcursorover)
- [OnInputTouchBegin](ue_ue.GizmoHandleMeshComponent.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.GizmoHandleMeshComponent.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.GizmoHandleMeshComponent.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.GizmoHandleMeshComponent.md#oninputtouchleave)
- [OnReleased](ue_ue.GizmoHandleMeshComponent.md#onreleased)
- [OverriddenLightMapRes](ue_ue.GizmoHandleMeshComponent.md#overriddenlightmapres)
- [OverrideMaterials](ue_ue.GizmoHandleMeshComponent.md#overridematerials)
- [PhysicsVolume](ue_ue.GizmoHandleMeshComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.GizmoHandleMeshComponent.md#physicsvolumechangeddelegate)
- [PreviousLODLevel](ue_ue.GizmoHandleMeshComponent.md#previouslodlevel)
- [PrimaryComponentTick](ue_ue.GizmoHandleMeshComponent.md#primarycomponenttick)
- [RelativeLocation](ue_ue.GizmoHandleMeshComponent.md#relativelocation)
- [RelativeRotation](ue_ue.GizmoHandleMeshComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.GizmoHandleMeshComponent.md#relativescale3d)
- [RuntimeVirtualTextures](ue_ue.GizmoHandleMeshComponent.md#runtimevirtualtextures)
- [SectionIndexPreview](ue_ue.GizmoHandleMeshComponent.md#sectionindexpreview)
- [SelectedEditorMaterial](ue_ue.GizmoHandleMeshComponent.md#selectededitormaterial)
- [SelectedEditorSection](ue_ue.GizmoHandleMeshComponent.md#selectededitorsection)
- [StaticMesh](ue_ue.GizmoHandleMeshComponent.md#staticmesh)
- [StaticMeshDerivedDataKey](ue_ue.GizmoHandleMeshComponent.md#staticmeshderiveddatakey)
- [StaticMeshImportVersion](ue_ue.GizmoHandleMeshComponent.md#staticmeshimportversion)
- [StreamingDistanceMultiplier](ue_ue.GizmoHandleMeshComponent.md#streamingdistancemultiplier)
- [StreamingTextureData](ue_ue.GizmoHandleMeshComponent.md#streamingtexturedata)
- [SubDivisionStepSize](ue_ue.GizmoHandleMeshComponent.md#subdivisionstepsize)
- [TranslucencySortPriority](ue_ue.GizmoHandleMeshComponent.md#translucencysortpriority)
- [UCSModifiedProperties](ue_ue.GizmoHandleMeshComponent.md#ucsmodifiedproperties)
- [ViewOwnerDepthPriorityGroup](ue_ue.GizmoHandleMeshComponent.md#viewownerdepthprioritygroup)
- [VirtualTextureCullMips](ue_ue.GizmoHandleMeshComponent.md#virtualtexturecullmips)
- [VirtualTextureLodBias](ue_ue.GizmoHandleMeshComponent.md#virtualtexturelodbias)
- [VirtualTextureMinCoverage](ue_ue.GizmoHandleMeshComponent.md#virtualtexturemincoverage)
- [VirtualTextureRenderPassType](ue_ue.GizmoHandleMeshComponent.md#virtualtexturerenderpasstype)
- [VisibilityId](ue_ue.GizmoHandleMeshComponent.md#visibilityid)
- [WireframeColorOverride](ue_ue.GizmoHandleMeshComponent.md#wireframecoloroverride)
- [\_\_tid\_ActorComponent\_\_](ue_ue.GizmoHandleMeshComponent.md#__tid_actorcomponent__)
- [\_\_tid\_GizmoHandleMeshComponent\_\_](ue_ue.GizmoHandleMeshComponent.md#__tid_gizmohandlemeshcomponent__)
- [\_\_tid\_MeshComponent\_\_](ue_ue.GizmoHandleMeshComponent.md#__tid_meshcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.GizmoHandleMeshComponent.md#__tid_object__)
- [\_\_tid\_PrimitiveComponent\_\_](ue_ue.GizmoHandleMeshComponent.md#__tid_primitivecomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.GizmoHandleMeshComponent.md#__tid_scenecomponent__)
- [\_\_tid\_StaticMeshComponent\_\_](ue_ue.GizmoHandleMeshComponent.md#__tid_staticmeshcomponent__)
- [bAbsoluteLocation](ue_ue.GizmoHandleMeshComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.GizmoHandleMeshComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.GizmoHandleMeshComponent.md#babsolutescale)
- [bAffectDistanceFieldLighting](ue_ue.GizmoHandleMeshComponent.md#baffectdistancefieldlighting)
- [bAffectDynamicIndirectLighting](ue_ue.GizmoHandleMeshComponent.md#baffectdynamicindirectlighting)
- [bAllowCullDistanceVolume](ue_ue.GizmoHandleMeshComponent.md#ballowculldistancevolume)
- [bAlwaysCreatePhysicsState](ue_ue.GizmoHandleMeshComponent.md#balwayscreatephysicsstate)
- [bApplyImpulseOnDamage](ue_ue.GizmoHandleMeshComponent.md#bapplyimpulseondamage)
- [bAutoActivate](ue_ue.GizmoHandleMeshComponent.md#bautoactivate)
- [bBatchImpostersAsInstances](ue_ue.GizmoHandleMeshComponent.md#bbatchimpostersasinstances)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.GizmoHandleMeshComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.GizmoHandleMeshComponent.md#bcaneveraffectnavigation)
- [bCastCinematicShadow](ue_ue.GizmoHandleMeshComponent.md#bcastcinematicshadow)
- [bCastDistanceFieldIndirectShadow](ue_ue.GizmoHandleMeshComponent.md#bcastdistancefieldindirectshadow)
- [bCastDynamicShadow](ue_ue.GizmoHandleMeshComponent.md#bcastdynamicshadow)
- [bCastFarShadow](ue_ue.GizmoHandleMeshComponent.md#bcastfarshadow)
- [bCastHiddenShadow](ue_ue.GizmoHandleMeshComponent.md#bcasthiddenshadow)
- [bCastInsetShadow](ue_ue.GizmoHandleMeshComponent.md#bcastinsetshadow)
- [bCastShadowAsTwoSided](ue_ue.GizmoHandleMeshComponent.md#bcastshadowastwosided)
- [bCastStaticShadow](ue_ue.GizmoHandleMeshComponent.md#bcaststaticshadow)
- [bCastVolumetricTranslucentShadow](ue_ue.GizmoHandleMeshComponent.md#bcastvolumetrictranslucentshadow)
- [bComponentToWorldUpdated](ue_ue.GizmoHandleMeshComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.GizmoHandleMeshComponent.md#bcreatedbyconstructionscript)
- [bCustomOverrideVertexColorPerLOD](ue_ue.GizmoHandleMeshComponent.md#bcustomoverridevertexcolorperlod)
- [bDisallowMeshPaintPerInstance](ue_ue.GizmoHandleMeshComponent.md#bdisallowmeshpaintperinstance)
- [bDisplayVertexColors](ue_ue.GizmoHandleMeshComponent.md#bdisplayvertexcolors)
- [bEditableWhenInherited](ue_ue.GizmoHandleMeshComponent.md#beditablewheninherited)
- [bEnableAutoLODGeneration](ue_ue.GizmoHandleMeshComponent.md#benableautolodgeneration)
- [bEnableMaterialParameterCaching](ue_ue.GizmoHandleMeshComponent.md#benablematerialparametercaching)
- [bEvaluateWorldPositionOffset](ue_ue.GizmoHandleMeshComponent.md#bevaluateworldpositionoffset)
- [bExcludeFromLightAttachmentGroup](ue_ue.GizmoHandleMeshComponent.md#bexcludefromlightattachmentgroup)
- [bForceMipStreaming](ue_ue.GizmoHandleMeshComponent.md#bforcemipstreaming)
- [bForceNavigationObstacle](ue_ue.GizmoHandleMeshComponent.md#bforcenavigationobstacle)
- [bGenerateOverlapEvents](ue_ue.GizmoHandleMeshComponent.md#bgenerateoverlapevents)
- [bHasCustomNavigableGeometry](ue_ue.GizmoHandleMeshComponent.md#bhascustomnavigablegeometry)
- [bHasMotionBlurVelocityMeshes](ue_ue.GizmoHandleMeshComponent.md#bhasmotionblurvelocitymeshes)
- [bHasPerInstanceHitProxies](ue_ue.GizmoHandleMeshComponent.md#bhasperinstancehitproxies)
- [bHiddenInGame](ue_ue.GizmoHandleMeshComponent.md#bhiddeningame)
- [bIgnoreInstanceForTextureStreaming](ue_ue.GizmoHandleMeshComponent.md#bignoreinstancefortexturestreaming)
- [bIgnoreRadialForce](ue_ue.GizmoHandleMeshComponent.md#bignoreradialforce)
- [bIgnoreRadialImpulse](ue_ue.GizmoHandleMeshComponent.md#bignoreradialimpulse)
- [bInstanceComponent](ue_ue.GizmoHandleMeshComponent.md#binstancecomponent)
- [bIsActive](ue_ue.GizmoHandleMeshComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.GizmoHandleMeshComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.GizmoHandleMeshComponent.md#bisvisualizationcomponent)
- [bLightAsIfStatic](ue_ue.GizmoHandleMeshComponent.md#blightasifstatic)
- [bLightAttachmentsAsGroup](ue_ue.GizmoHandleMeshComponent.md#blightattachmentsasgroup)
- [bMultiBodyOverlap](ue_ue.GizmoHandleMeshComponent.md#bmultibodyoverlap)
- [bNetAddressable](ue_ue.GizmoHandleMeshComponent.md#bnetaddressable)
- [bNeverDistanceCull](ue_ue.GizmoHandleMeshComponent.md#bneverdistancecull)
- [bOnlyOwnerSee](ue_ue.GizmoHandleMeshComponent.md#bonlyownersee)
- [bOverrideDistanceFieldSelfShadowBias](ue_ue.GizmoHandleMeshComponent.md#boverridedistancefieldselfshadowbias)
- [bOverrideLightMapRes](ue_ue.GizmoHandleMeshComponent.md#boverridelightmapres)
- [bOverrideMinLOD](ue_ue.GizmoHandleMeshComponent.md#boverrideminlod)
- [bOverrideNavigationExport](ue_ue.GizmoHandleMeshComponent.md#boverridenavigationexport)
- [bOverrideWireframeColor](ue_ue.GizmoHandleMeshComponent.md#boverridewireframecolor)
- [bOwnerNoSee](ue_ue.GizmoHandleMeshComponent.md#bownernosee)
- [bReceiveMobileCSMShadows](ue_ue.GizmoHandleMeshComponent.md#breceivemobilecsmshadows)
- [bReceivesDecals](ue_ue.GizmoHandleMeshComponent.md#breceivesdecals)
- [bRenderCustomDepth](ue_ue.GizmoHandleMeshComponent.md#brendercustomdepth)
- [bRenderInDepthPass](ue_ue.GizmoHandleMeshComponent.md#brenderindepthpass)
- [bRenderInMainPass](ue_ue.GizmoHandleMeshComponent.md#brenderinmainpass)
- [bReplicatePhysicsToAutonomousProxy](ue_ue.GizmoHandleMeshComponent.md#breplicatephysicstoautonomousproxy)
- [bReplicates](ue_ue.GizmoHandleMeshComponent.md#breplicates)
- [bReturnMaterialOnMove](ue_ue.GizmoHandleMeshComponent.md#breturnmaterialonmove)
- [bReverseCulling](ue_ue.GizmoHandleMeshComponent.md#breverseculling)
- [bSelectable](ue_ue.GizmoHandleMeshComponent.md#bselectable)
- [bSelfShadowOnly](ue_ue.GizmoHandleMeshComponent.md#bselfshadowonly)
- [bShouldBeAttached](ue_ue.GizmoHandleMeshComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.GizmoHandleMeshComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.GizmoHandleMeshComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.GizmoHandleMeshComponent.md#bshouldupdatephysicsvolume)
- [bSingleSampleShadowFromStationaryLights](ue_ue.GizmoHandleMeshComponent.md#bsinglesampleshadowfromstationarylights)
- [bTraceComplexOnMove](ue_ue.GizmoHandleMeshComponent.md#btracecomplexonmove)
- [bTreatAsBackgroundForOcclusion](ue_ue.GizmoHandleMeshComponent.md#btreatasbackgroundforocclusion)
- [bUseAsOccluder](ue_ue.GizmoHandleMeshComponent.md#buseasoccluder)
- [bUseAttachParentBound](ue_ue.GizmoHandleMeshComponent.md#buseattachparentbound)
- [bUseDefaultCollision](ue_ue.GizmoHandleMeshComponent.md#busedefaultcollision)
- [bUseEditorCompositing](ue_ue.GizmoHandleMeshComponent.md#buseeditorcompositing)
- [bUseMaxLODAsImposter](ue_ue.GizmoHandleMeshComponent.md#busemaxlodasimposter)
- [bUseSubDivisions](ue_ue.GizmoHandleMeshComponent.md#busesubdivisions)
- [bUseViewOwnerDepthPriorityGroup](ue_ue.GizmoHandleMeshComponent.md#buseviewownerdepthprioritygroup)
- [bVisible](ue_ue.GizmoHandleMeshComponent.md#bvisible)
- [bVisibleInRayTracing](ue_ue.GizmoHandleMeshComponent.md#bvisibleinraytracing)
- [bVisibleInReflectionCaptures](ue_ue.GizmoHandleMeshComponent.md#bvisibleinreflectioncaptures)
- [bVisualizeComponent](ue_ue.GizmoHandleMeshComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.GizmoHandleMeshComponent.md#activate)
- [AddAngularImpulse](ue_ue.GizmoHandleMeshComponent.md#addangularimpulse)
- [AddAngularImpulseInDegrees](ue_ue.GizmoHandleMeshComponent.md#addangularimpulseindegrees)
- [AddAngularImpulseInRadians](ue_ue.GizmoHandleMeshComponent.md#addangularimpulseinradians)
- [AddForce](ue_ue.GizmoHandleMeshComponent.md#addforce)
- [AddForceAtLocation](ue_ue.GizmoHandleMeshComponent.md#addforceatlocation)
- [AddForceAtLocationLocal](ue_ue.GizmoHandleMeshComponent.md#addforceatlocationlocal)
- [AddImpulse](ue_ue.GizmoHandleMeshComponent.md#addimpulse)
- [AddImpulseAtLocation](ue_ue.GizmoHandleMeshComponent.md#addimpulseatlocation)
- [AddRadialForce](ue_ue.GizmoHandleMeshComponent.md#addradialforce)
- [AddRadialImpulse](ue_ue.GizmoHandleMeshComponent.md#addradialimpulse)
- [AddTickPrerequisiteActor](ue_ue.GizmoHandleMeshComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.GizmoHandleMeshComponent.md#addtickprerequisitecomponent)
- [AddTorque](ue_ue.GizmoHandleMeshComponent.md#addtorque)
- [AddTorqueInDegrees](ue_ue.GizmoHandleMeshComponent.md#addtorqueindegrees)
- [AddTorqueInRadians](ue_ue.GizmoHandleMeshComponent.md#addtorqueinradians)
- [CanCharacterStepUp](ue_ue.GizmoHandleMeshComponent.md#cancharacterstepup)
- [ClearMoveIgnoreActors](ue_ue.GizmoHandleMeshComponent.md#clearmoveignoreactors)
- [ClearMoveIgnoreComponents](ue_ue.GizmoHandleMeshComponent.md#clearmoveignorecomponents)
- [ComponentHasTag](ue_ue.GizmoHandleMeshComponent.md#componenthastag)
- [CopyArrayOfMoveIgnoreActors](ue_ue.GizmoHandleMeshComponent.md#copyarrayofmoveignoreactors)
- [CopyArrayOfMoveIgnoreComponents](ue_ue.GizmoHandleMeshComponent.md#copyarrayofmoveignorecomponents)
- [CreateAndSetMaterialInstanceDynamic](ue_ue.GizmoHandleMeshComponent.md#createandsetmaterialinstancedynamic)
- [CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.GizmoHandleMeshComponent.md#createandsetmaterialinstancedynamicfrommaterial)
- [CreateDefaultSubobject](ue_ue.GizmoHandleMeshComponent.md#createdefaultsubobject)
- [CreateDynamicMaterialInstance](ue_ue.GizmoHandleMeshComponent.md#createdynamicmaterialinstance)
- [Deactivate](ue_ue.GizmoHandleMeshComponent.md#deactivate)
- [DetachFromParent](ue_ue.GizmoHandleMeshComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.GizmoHandleMeshComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.GizmoHandleMeshComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.GizmoHandleMeshComponent.md#getallsocketnames)
- [GetAngularDamping](ue_ue.GizmoHandleMeshComponent.md#getangulardamping)
- [GetAttachParent](ue_ue.GizmoHandleMeshComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.GizmoHandleMeshComponent.md#getattachsocketname)
- [GetCenterOfMass](ue_ue.GizmoHandleMeshComponent.md#getcenterofmass)
- [GetChildComponent](ue_ue.GizmoHandleMeshComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.GizmoHandleMeshComponent.md#getchildrencomponents)
- [GetClass](ue_ue.GizmoHandleMeshComponent.md#getclass)
- [GetClosestPointOnCollision](ue_ue.GizmoHandleMeshComponent.md#getclosestpointoncollision)
- [GetCollisionEnabled](ue_ue.GizmoHandleMeshComponent.md#getcollisionenabled)
- [GetCollisionObjectType](ue_ue.GizmoHandleMeshComponent.md#getcollisionobjecttype)
- [GetCollisionProfileName](ue_ue.GizmoHandleMeshComponent.md#getcollisionprofilename)
- [GetCollisionResponseToChannel](ue_ue.GizmoHandleMeshComponent.md#getcollisionresponsetochannel)
- [GetComponentTickInterval](ue_ue.GizmoHandleMeshComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.GizmoHandleMeshComponent.md#getcomponentvelocity)
- [GetForwardVector](ue_ue.GizmoHandleMeshComponent.md#getforwardvector)
- [GetGenerateOverlapEvents](ue_ue.GizmoHandleMeshComponent.md#getgenerateoverlapevents)
- [GetInertiaTensor](ue_ue.GizmoHandleMeshComponent.md#getinertiatensor)
- [GetLinearDamping](ue_ue.GizmoHandleMeshComponent.md#getlineardamping)
- [GetLocalBounds](ue_ue.GizmoHandleMeshComponent.md#getlocalbounds)
- [GetMass](ue_ue.GizmoHandleMeshComponent.md#getmass)
- [GetMassScale](ue_ue.GizmoHandleMeshComponent.md#getmassscale)
- [GetMaterial](ue_ue.GizmoHandleMeshComponent.md#getmaterial)
- [GetMaterialFromCollisionFaceIndex](ue_ue.GizmoHandleMeshComponent.md#getmaterialfromcollisionfaceindex)
- [GetMaterialIndex](ue_ue.GizmoHandleMeshComponent.md#getmaterialindex)
- [GetMaterialSlotNames](ue_ue.GizmoHandleMeshComponent.md#getmaterialslotnames)
- [GetMaterials](ue_ue.GizmoHandleMeshComponent.md#getmaterials)
- [GetName](ue_ue.GizmoHandleMeshComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.GizmoHandleMeshComponent.md#getnumchildrencomponents)
- [GetNumMaterials](ue_ue.GizmoHandleMeshComponent.md#getnummaterials)
- [GetOuter](ue_ue.GizmoHandleMeshComponent.md#getouter)
- [GetOverlappingActors](ue_ue.GizmoHandleMeshComponent.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.GizmoHandleMeshComponent.md#getoverlappingcomponents)
- [GetOwner](ue_ue.GizmoHandleMeshComponent.md#getowner)
- [GetParentComponents](ue_ue.GizmoHandleMeshComponent.md#getparentcomponents)
- [GetPhysicsAngularVelocity](ue_ue.GizmoHandleMeshComponent.md#getphysicsangularvelocity)
- [GetPhysicsAngularVelocityInDegrees](ue_ue.GizmoHandleMeshComponent.md#getphysicsangularvelocityindegrees)
- [GetPhysicsAngularVelocityInRadians](ue_ue.GizmoHandleMeshComponent.md#getphysicsangularvelocityinradians)
- [GetPhysicsLinearVelocity](ue_ue.GizmoHandleMeshComponent.md#getphysicslinearvelocity)
- [GetPhysicsLinearVelocityAtPoint](ue_ue.GizmoHandleMeshComponent.md#getphysicslinearvelocityatpoint)
- [GetPhysicsVolume](ue_ue.GizmoHandleMeshComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.GizmoHandleMeshComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.GizmoHandleMeshComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.GizmoHandleMeshComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.GizmoHandleMeshComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.GizmoHandleMeshComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.GizmoHandleMeshComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.GizmoHandleMeshComponent.md#getsockettransform)
- [GetUpVector](ue_ue.GizmoHandleMeshComponent.md#getupvector)
- [GetWalkableSlopeOverride](ue_ue.GizmoHandleMeshComponent.md#getwalkableslopeoverride)
- [GetWorld](ue_ue.GizmoHandleMeshComponent.md#getworld)
- [IgnoreActorWhenMoving](ue_ue.GizmoHandleMeshComponent.md#ignoreactorwhenmoving)
- [IgnoreComponentWhenMoving](ue_ue.GizmoHandleMeshComponent.md#ignorecomponentwhenmoving)
- [IsActive](ue_ue.GizmoHandleMeshComponent.md#isactive)
- [IsAnyRigidBodyAwake](ue_ue.GizmoHandleMeshComponent.md#isanyrigidbodyawake)
- [IsAnySimulatingPhysics](ue_ue.GizmoHandleMeshComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.GizmoHandleMeshComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.GizmoHandleMeshComponent.md#iscomponenttickenabled)
- [IsGravityEnabled](ue_ue.GizmoHandleMeshComponent.md#isgravityenabled)
- [IsMaterialSlotNameValid](ue_ue.GizmoHandleMeshComponent.md#ismaterialslotnamevalid)
- [IsOverlappingActor](ue_ue.GizmoHandleMeshComponent.md#isoverlappingactor)
- [IsOverlappingComponent](ue_ue.GizmoHandleMeshComponent.md#isoverlappingcomponent)
- [IsSimulatingPhysics](ue_ue.GizmoHandleMeshComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.GizmoHandleMeshComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.GizmoHandleMeshComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.GizmoHandleMeshComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.GizmoHandleMeshComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.GizmoHandleMeshComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.GizmoHandleMeshComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.GizmoHandleMeshComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.GizmoHandleMeshComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.GizmoHandleMeshComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.GizmoHandleMeshComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.GizmoHandleMeshComponent.md#k2_attachtocomponent)
- [K2\_BoxOverlapComponent](ue_ue.GizmoHandleMeshComponent.md#k2_boxoverlapcomponent)
- [K2\_DestroyComponent](ue_ue.GizmoHandleMeshComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.GizmoHandleMeshComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.GizmoHandleMeshComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.GizmoHandleMeshComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.GizmoHandleMeshComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.GizmoHandleMeshComponent.md#k2_getcomponenttoworld)
- [K2\_IsCollisionEnabled](ue_ue.GizmoHandleMeshComponent.md#k2_iscollisionenabled)
- [K2\_IsPhysicsCollisionEnabled](ue_ue.GizmoHandleMeshComponent.md#k2_isphysicscollisionenabled)
- [K2\_IsQueryCollisionEnabled](ue_ue.GizmoHandleMeshComponent.md#k2_isquerycollisionenabled)
- [K2\_LineTraceComponent](ue_ue.GizmoHandleMeshComponent.md#k2_linetracecomponent)
- [K2\_SetRelativeLocation](ue_ue.GizmoHandleMeshComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.GizmoHandleMeshComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.GizmoHandleMeshComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.GizmoHandleMeshComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.GizmoHandleMeshComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.GizmoHandleMeshComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.GizmoHandleMeshComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.GizmoHandleMeshComponent.md#k2_setworldtransform)
- [K2\_SphereOverlapComponent](ue_ue.GizmoHandleMeshComponent.md#k2_sphereoverlapcomponent)
- [K2\_SphereTraceComponent](ue_ue.GizmoHandleMeshComponent.md#k2_spheretracecomponent)
- [OnRep\_AttachChildren](ue_ue.GizmoHandleMeshComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.GizmoHandleMeshComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.GizmoHandleMeshComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.GizmoHandleMeshComponent.md#onrep_isactive)
- [OnRep\_StaticMesh](ue_ue.GizmoHandleMeshComponent.md#onrep_staticmesh)
- [OnRep\_Transform](ue_ue.GizmoHandleMeshComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.GizmoHandleMeshComponent.md#onrep_visibility)
- [PrestreamTextures](ue_ue.GizmoHandleMeshComponent.md#prestreamtextures)
- [PutRigidBodyToSleep](ue_ue.GizmoHandleMeshComponent.md#putrigidbodytosleep)
- [ReceiveBeginPlay](ue_ue.GizmoHandleMeshComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.GizmoHandleMeshComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.GizmoHandleMeshComponent.md#receivetick)
- [RegisterComponent](ue_ue.GizmoHandleMeshComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.GizmoHandleMeshComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.GizmoHandleMeshComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.GizmoHandleMeshComponent.md#resetrelativetransform)
- [ScaleByMomentOfInertia](ue_ue.GizmoHandleMeshComponent.md#scalebymomentofinertia)
- [SetAbsolute](ue_ue.GizmoHandleMeshComponent.md#setabsolute)
- [SetActive](ue_ue.GizmoHandleMeshComponent.md#setactive)
- [SetAllMassScale](ue_ue.GizmoHandleMeshComponent.md#setallmassscale)
- [SetAllPhysicsAngularVelocityInDegrees](ue_ue.GizmoHandleMeshComponent.md#setallphysicsangularvelocityindegrees)
- [SetAllPhysicsAngularVelocityInRadians](ue_ue.GizmoHandleMeshComponent.md#setallphysicsangularvelocityinradians)
- [SetAllPhysicsLinearVelocity](ue_ue.GizmoHandleMeshComponent.md#setallphysicslinearvelocity)
- [SetAllUseCCD](ue_ue.GizmoHandleMeshComponent.md#setalluseccd)
- [SetAngularDamping](ue_ue.GizmoHandleMeshComponent.md#setangulardamping)
- [SetAutoActivate](ue_ue.GizmoHandleMeshComponent.md#setautoactivate)
- [SetBoundsScale](ue_ue.GizmoHandleMeshComponent.md#setboundsscale)
- [SetCastInsetShadow](ue_ue.GizmoHandleMeshComponent.md#setcastinsetshadow)
- [SetCastShadow](ue_ue.GizmoHandleMeshComponent.md#setcastshadow)
- [SetCenterOfMass](ue_ue.GizmoHandleMeshComponent.md#setcenterofmass)
- [SetCollisionEnabled](ue_ue.GizmoHandleMeshComponent.md#setcollisionenabled)
- [SetCollisionObjectType](ue_ue.GizmoHandleMeshComponent.md#setcollisionobjecttype)
- [SetCollisionProfileName](ue_ue.GizmoHandleMeshComponent.md#setcollisionprofilename)
- [SetCollisionResponseToAllChannels](ue_ue.GizmoHandleMeshComponent.md#setcollisionresponsetoallchannels)
- [SetCollisionResponseToChannel](ue_ue.GizmoHandleMeshComponent.md#setcollisionresponsetochannel)
- [SetComponentTickEnabled](ue_ue.GizmoHandleMeshComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.GizmoHandleMeshComponent.md#setcomponenttickinterval)
- [SetConstraintMode](ue_ue.GizmoHandleMeshComponent.md#setconstraintmode)
- [SetCullDistance](ue_ue.GizmoHandleMeshComponent.md#setculldistance)
- [SetCustomDepthStencilValue](ue_ue.GizmoHandleMeshComponent.md#setcustomdepthstencilvalue)
- [SetCustomDepthStencilWriteMask](ue_ue.GizmoHandleMeshComponent.md#setcustomdepthstencilwritemask)
- [SetCustomPrimitiveDataFloat](ue_ue.GizmoHandleMeshComponent.md#setcustomprimitivedatafloat)
- [SetCustomPrimitiveDataVector2](ue_ue.GizmoHandleMeshComponent.md#setcustomprimitivedatavector2)
- [SetCustomPrimitiveDataVector3](ue_ue.GizmoHandleMeshComponent.md#setcustomprimitivedatavector3)
- [SetCustomPrimitiveDataVector4](ue_ue.GizmoHandleMeshComponent.md#setcustomprimitivedatavector4)
- [SetDistanceFieldSelfShadowBias](ue_ue.GizmoHandleMeshComponent.md#setdistancefieldselfshadowbias)
- [SetEnableGravity](ue_ue.GizmoHandleMeshComponent.md#setenablegravity)
- [SetExcludeFromLightAttachmentGroup](ue_ue.GizmoHandleMeshComponent.md#setexcludefromlightattachmentgroup)
- [SetForcedLodModel](ue_ue.GizmoHandleMeshComponent.md#setforcedlodmodel)
- [SetGenerateOverlapEvents](ue_ue.GizmoHandleMeshComponent.md#setgenerateoverlapevents)
- [SetHiddenInGame](ue_ue.GizmoHandleMeshComponent.md#sethiddeningame)
- [SetIsReplicated](ue_ue.GizmoHandleMeshComponent.md#setisreplicated)
- [SetLightAttachmentsAsGroup](ue_ue.GizmoHandleMeshComponent.md#setlightattachmentsasgroup)
- [SetLinearDamping](ue_ue.GizmoHandleMeshComponent.md#setlineardamping)
- [SetMassOverrideInKg](ue_ue.GizmoHandleMeshComponent.md#setmassoverrideinkg)
- [SetMassScale](ue_ue.GizmoHandleMeshComponent.md#setmassscale)
- [SetMaterial](ue_ue.GizmoHandleMeshComponent.md#setmaterial)
- [SetMaterialByName](ue_ue.GizmoHandleMeshComponent.md#setmaterialbyname)
- [SetMobility](ue_ue.GizmoHandleMeshComponent.md#setmobility)
- [SetNotifyRigidBodyCollision](ue_ue.GizmoHandleMeshComponent.md#setnotifyrigidbodycollision)
- [SetOnlyOwnerSee](ue_ue.GizmoHandleMeshComponent.md#setonlyownersee)
- [SetOwnerNoSee](ue_ue.GizmoHandleMeshComponent.md#setownernosee)
- [SetPhysMaterialOverride](ue_ue.GizmoHandleMeshComponent.md#setphysmaterialoverride)
- [SetPhysicsAngularVelocity](ue_ue.GizmoHandleMeshComponent.md#setphysicsangularvelocity)
- [SetPhysicsAngularVelocityInDegrees](ue_ue.GizmoHandleMeshComponent.md#setphysicsangularvelocityindegrees)
- [SetPhysicsAngularVelocityInRadians](ue_ue.GizmoHandleMeshComponent.md#setphysicsangularvelocityinradians)
- [SetPhysicsLinearVelocity](ue_ue.GizmoHandleMeshComponent.md#setphysicslinearvelocity)
- [SetPhysicsMaxAngularVelocity](ue_ue.GizmoHandleMeshComponent.md#setphysicsmaxangularvelocity)
- [SetPhysicsMaxAngularVelocityInDegrees](ue_ue.GizmoHandleMeshComponent.md#setphysicsmaxangularvelocityindegrees)
- [SetPhysicsMaxAngularVelocityInRadians](ue_ue.GizmoHandleMeshComponent.md#setphysicsmaxangularvelocityinradians)
- [SetReceivesDecals](ue_ue.GizmoHandleMeshComponent.md#setreceivesdecals)
- [SetRelativeScale3D](ue_ue.GizmoHandleMeshComponent.md#setrelativescale3d)
- [SetRenderCustomDepth](ue_ue.GizmoHandleMeshComponent.md#setrendercustomdepth)
- [SetRenderInMainPass](ue_ue.GizmoHandleMeshComponent.md#setrenderinmainpass)
- [SetReverseCulling](ue_ue.GizmoHandleMeshComponent.md#setreverseculling)
- [SetScalarParameterValueOnMaterials](ue_ue.GizmoHandleMeshComponent.md#setscalarparametervalueonmaterials)
- [SetShouldUpdatePhysicsVolume](ue_ue.GizmoHandleMeshComponent.md#setshouldupdatephysicsvolume)
- [SetSimulatePhysics](ue_ue.GizmoHandleMeshComponent.md#setsimulatephysics)
- [SetSingleSampleShadowFromStationaryLights](ue_ue.GizmoHandleMeshComponent.md#setsinglesampleshadowfromstationarylights)
- [SetStaticMesh](ue_ue.GizmoHandleMeshComponent.md#setstaticmesh)
- [SetTickGroup](ue_ue.GizmoHandleMeshComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.GizmoHandleMeshComponent.md#settickablewhenpaused)
- [SetTranslucentSortPriority](ue_ue.GizmoHandleMeshComponent.md#settranslucentsortpriority)
- [SetUseCCD](ue_ue.GizmoHandleMeshComponent.md#setuseccd)
- [SetVectorParameterValueOnMaterials](ue_ue.GizmoHandleMeshComponent.md#setvectorparametervalueonmaterials)
- [SetVisibility](ue_ue.GizmoHandleMeshComponent.md#setvisibility)
- [SetWalkableSlopeOverride](ue_ue.GizmoHandleMeshComponent.md#setwalkableslopeoverride)
- [SetWorldScale3D](ue_ue.GizmoHandleMeshComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.GizmoHandleMeshComponent.md#setupattachment)
- [SnapTo](ue_ue.GizmoHandleMeshComponent.md#snapto)
- [ToggleActive](ue_ue.GizmoHandleMeshComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.GizmoHandleMeshComponent.md#togglevisibility)
- [WakeAllRigidBodies](ue_ue.GizmoHandleMeshComponent.md#wakeallrigidbodies)
- [WakeRigidBody](ue_ue.GizmoHandleMeshComponent.md#wakerigidbody)
- [Find](ue_ue.GizmoHandleMeshComponent.md#find)
- [Load](ue_ue.GizmoHandleMeshComponent.md#load)
- [StaticClass](ue_ue.GizmoHandleMeshComponent.md#staticclass)

## Constructors

### constructor

• **new GizmoHandleMeshComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[constructor](ue_ue.StaticMeshComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:38054](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38054)

## Properties

### AlwaysLoadOnClient

• **AlwaysLoadOnClient**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AlwaysLoadOnClient](ue_ue.StaticMeshComponent.md#alwaysloadonclient)

#### Defined in

[ue/ue.d.ts:12608](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12608)

___

### AlwaysLoadOnServer

• **AlwaysLoadOnServer**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AlwaysLoadOnServer](ue_ue.StaticMeshComponent.md#alwaysloadonserver)

#### Defined in

[ue/ue.d.ts:12609](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12609)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AssetUserData](ue_ue.StaticMeshComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L291)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AttachChildren](ue_ue.StaticMeshComponent.md#attachchildren)

#### Defined in

[ue/ue.d.ts:12873](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12873)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AttachParent](ue_ue.StaticMeshComponent.md#attachparent)

#### Defined in

[ue/ue.d.ts:12871](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12871)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AttachSocketName](ue_ue.StaticMeshComponent.md#attachsocketname)

#### Defined in

[ue/ue.d.ts:12872](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12872)

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[BodyInstance](ue_ue.StaticMeshComponent.md#bodyinstance)

#### Defined in

[ue/ue.d.ts:12630](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12630)

___

### BoundsScale

• **BoundsScale**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[BoundsScale](ue_ue.StaticMeshComponent.md#boundsscale)

#### Defined in

[ue/ue.d.ts:12627](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12627)

___

### CachedMaxDrawDistance

• **CachedMaxDrawDistance**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CachedMaxDrawDistance](ue_ue.StaticMeshComponent.md#cachedmaxdrawdistance)

#### Defined in

[ue/ue.d.ts:12557](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12557)

___

### CanBeCharacterBase

• **CanBeCharacterBase**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CanBeCharacterBase](ue_ue.StaticMeshComponent.md#canbecharacterbase)

#### Defined in

[ue/ue.d.ts:12613](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12613)

___

### CanCharacterStepUpOn

• **CanCharacterStepUpOn**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CanCharacterStepUpOn](ue_ue.StaticMeshComponent.md#cancharacterstepupon)

#### Defined in

[ue/ue.d.ts:12614](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12614)

___

### CastShadow

• **CastShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CastShadow](ue_ue.StaticMeshComponent.md#castshadow)

#### Defined in

[ue/ue.d.ts:12587](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12587)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ClientAttachedChildren](ue_ue.StaticMeshComponent.md#clientattachedchildren)

#### Defined in

[ue/ue.d.ts:12874](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12874)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ComponentTags](ue_ue.StaticMeshComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L290)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ComponentVelocity](ue_ue.StaticMeshComponent.md#componentvelocity)

#### Defined in

[ue/ue.d.ts:12878](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12878)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CreationMethod](ue_ue.StaticMeshComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L302)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CustomDepthStencilValue](ue_ue.StaticMeshComponent.md#customdepthstencilvalue)

#### Defined in

[ue/ue.d.ts:12617](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12617)

___

### CustomDepthStencilWriteMask

• **CustomDepthStencilWriteMask**: [`ERendererStencilMask`](../enums/ue_ue.ERendererStencilMask.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CustomDepthStencilWriteMask](ue_ue.StaticMeshComponent.md#customdepthstencilwritemask)

#### Defined in

[ue/ue.d.ts:12616](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12616)

___

### CustomPrimitiveData

• **CustomPrimitiveData**: [`CustomPrimitiveData`](ue_ue.CustomPrimitiveData.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CustomPrimitiveData](ue_ue.StaticMeshComponent.md#customprimitivedata)

#### Defined in

[ue/ue.d.ts:12618](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12618)

___

### DepthPriorityGroup

• **DepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[DepthPriorityGroup](ue_ue.StaticMeshComponent.md#depthprioritygroup)

#### Defined in

[ue/ue.d.ts:12558](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12558)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[DetailMode](ue_ue.StaticMeshComponent.md#detailmode)

#### Defined in

[ue/ue.d.ts:12893](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12893)

___

### DistanceFieldIndirectShadowMinVisibility

• **DistanceFieldIndirectShadowMinVisibility**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[DistanceFieldIndirectShadowMinVisibility](ue_ue.StaticMeshComponent.md#distancefieldindirectshadowminvisibility)

#### Defined in

[ue/ue.d.ts:10614](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10614)

___

### DistanceFieldSelfShadowBias

• **DistanceFieldSelfShadowBias**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[DistanceFieldSelfShadowBias](ue_ue.StaticMeshComponent.md#distancefieldselfshadowbias)

#### Defined in

[ue/ue.d.ts:10615](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10615)

___

### ExcludeForSpecificHLODLevels

• **ExcludeForSpecificHLODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ExcludeForSpecificHLODLevels](ue_ue.StaticMeshComponent.md#excludeforspecifichlodlevels)

#### Defined in

[ue/ue.d.ts:12562](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12562)

___

### ForcedLodModel

• **ForcedLodModel**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ForcedLodModel](ue_ue.StaticMeshComponent.md#forcedlodmodel)

#### Defined in

[ue/ue.d.ts:10587](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10587)

___

### IndirectLightingCacheQuality

• **IndirectLightingCacheQuality**: [`EIndirectLightingCacheQuality`](../enums/ue_ue.EIndirectLightingCacheQuality.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IndirectLightingCacheQuality](ue_ue.StaticMeshComponent.md#indirectlightingcachequality)

#### Defined in

[ue/ue.d.ts:12560](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12560)

___

### IrrelevantLights

• **IrrelevantLights**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IrrelevantLights](ue_ue.StaticMeshComponent.md#irrelevantlights)

#### Defined in

[ue/ue.d.ts:10617](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10617)

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[LDMaxDrawDistance](ue_ue.StaticMeshComponent.md#ldmaxdrawdistance)

#### Defined in

[ue/ue.d.ts:12556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12556)

___

### LODData

• **LODData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticMeshComponentLODInfo`](ue_ue.StaticMeshComponentLODInfo.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[LODData](ue_ue.StaticMeshComponent.md#loddata)

#### Defined in

[ue/ue.d.ts:10618](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10618)

___

### LODParentPrimitive

• **LODParentPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[LODParentPrimitive](ue_ue.StaticMeshComponent.md#lodparentprimitive)

#### Defined in

[ue/ue.d.ts:12644](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12644)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[LightingChannels](ue_ue.StaticMeshComponent.md#lightingchannels)

#### Defined in

[ue/ue.d.ts:12615](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12615)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[LightmapType](ue_ue.StaticMeshComponent.md#lightmaptype)

#### Defined in

[ue/ue.d.ts:12561](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12561)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassPrimitiveSettings`](ue_ue.LightmassPrimitiveSettings.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[LightmassSettings](ue_ue.StaticMeshComponent.md#lightmasssettings)

#### Defined in

[ue/ue.d.ts:10622](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10622)

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[LpvBiasMultiplier](ue_ue.StaticMeshComponent.md#lpvbiasmultiplier)

#### Defined in

[ue/ue.d.ts:12626](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12626)

___

### MaterialIndexPreview

• **MaterialIndexPreview**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[MaterialIndexPreview](ue_ue.StaticMeshComponent.md#materialindexpreview)

#### Defined in

[ue/ue.d.ts:10597](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10597)

___

### MaterialStreamingRelativeBoxes

• **MaterialStreamingRelativeBoxes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[MaterialStreamingRelativeBoxes](ue_ue.StaticMeshComponent.md#materialstreamingrelativeboxes)

#### Defined in

[ue/ue.d.ts:10621](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10621)

___

### MinDrawDistance

• **MinDrawDistance**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[MinDrawDistance](ue_ue.StaticMeshComponent.md#mindrawdistance)

#### Defined in

[ue/ue.d.ts:12555](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12555)

___

### MinLOD

• **MinLOD**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[MinLOD](ue_ue.StaticMeshComponent.md#minlod)

#### Defined in

[ue/ue.d.ts:10589](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10589)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[Mobility](ue_ue.StaticMeshComponent.md#mobility)

#### Defined in

[ue/ue.d.ts:12892](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12892)

___

### MoveIgnoreActors

• **MoveIgnoreActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[MoveIgnoreActors](ue_ue.StaticMeshComponent.md#moveignoreactors)

#### Defined in

[ue/ue.d.ts:12628](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12628)

___

### MoveIgnoreComponents

• **MoveIgnoreComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[MoveIgnoreComponents](ue_ue.StaticMeshComponent.md#moveignorecomponents)

#### Defined in

[ue/ue.d.ts:12629](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12629)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnBeginCursorOver](ue_ue.StaticMeshComponent.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:12636](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12636)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnClicked](ue_ue.StaticMeshComponent.md#onclicked)

#### Defined in

[ue/ue.d.ts:12638](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12638)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnComponentActivated](ue_ue.StaticMeshComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L303)

___

### OnComponentBeginOverlap

• **OnComponentBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`, `bFromSweep`: `boolean`, `SweepResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnComponentBeginOverlap](ue_ue.StaticMeshComponent.md#oncomponentbeginoverlap)

#### Defined in

[ue/ue.d.ts:12632](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12632)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnComponentDeactivated](ue_ue.StaticMeshComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L304)

___

### OnComponentEndOverlap

• **OnComponentEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnComponentEndOverlap](ue_ue.StaticMeshComponent.md#oncomponentendoverlap)

#### Defined in

[ue/ue.d.ts:12633](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12633)

___

### OnComponentHit

• **OnComponentHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`HitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnComponentHit](ue_ue.StaticMeshComponent.md#oncomponenthit)

#### Defined in

[ue/ue.d.ts:12631](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12631)

___

### OnComponentSleep

• **OnComponentSleep**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SleepingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnComponentSleep](ue_ue.StaticMeshComponent.md#oncomponentsleep)

#### Defined in

[ue/ue.d.ts:12635](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12635)

___

### OnComponentWake

• **OnComponentWake**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`WakingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnComponentWake](ue_ue.StaticMeshComponent.md#oncomponentwake)

#### Defined in

[ue/ue.d.ts:12634](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12634)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnEndCursorOver](ue_ue.StaticMeshComponent.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:12637](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12637)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnInputTouchBegin](ue_ue.StaticMeshComponent.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:12640](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12640)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnInputTouchEnd](ue_ue.StaticMeshComponent.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:12641](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12641)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnInputTouchEnter](ue_ue.StaticMeshComponent.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:12642](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12642)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnInputTouchLeave](ue_ue.StaticMeshComponent.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:12643](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12643)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnReleased](ue_ue.StaticMeshComponent.md#onreleased)

#### Defined in

[ue/ue.d.ts:12639](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12639)

___

### OverriddenLightMapRes

• **OverriddenLightMapRes**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OverriddenLightMapRes](ue_ue.StaticMeshComponent.md#overriddenlightmapres)

#### Defined in

[ue/ue.d.ts:10613](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10613)

___

### OverrideMaterials

• **OverrideMaterials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OverrideMaterials](ue_ue.StaticMeshComponent.md#overridematerials)

#### Defined in

[ue/ue.d.ts:2296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2296)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[PhysicsVolume](ue_ue.StaticMeshComponent.md#physicsvolume)

#### Defined in

[ue/ue.d.ts:12870](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12870)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.StaticMeshComponent.md#physicsvolumechangeddelegate)

#### Defined in

[ue/ue.d.ts:12894](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12894)

___

### PreviousLODLevel

• **PreviousLODLevel**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[PreviousLODLevel](ue_ue.StaticMeshComponent.md#previouslodlevel)

#### Defined in

[ue/ue.d.ts:10588](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10588)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[PrimaryComponentTick](ue_ue.StaticMeshComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L289)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[RelativeLocation](ue_ue.StaticMeshComponent.md#relativelocation)

#### Defined in

[ue/ue.d.ts:12875](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12875)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[RelativeRotation](ue_ue.StaticMeshComponent.md#relativerotation)

#### Defined in

[ue/ue.d.ts:12876](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12876)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[RelativeScale3D](ue_ue.StaticMeshComponent.md#relativescale3d)

#### Defined in

[ue/ue.d.ts:12877](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12877)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[RuntimeVirtualTextures](ue_ue.StaticMeshComponent.md#runtimevirtualtextures)

#### Defined in

[ue/ue.d.ts:12621](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12621)

___

### SectionIndexPreview

• **SectionIndexPreview**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SectionIndexPreview](ue_ue.StaticMeshComponent.md#sectionindexpreview)

#### Defined in

[ue/ue.d.ts:10596](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10596)

___

### SelectedEditorMaterial

• **SelectedEditorMaterial**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SelectedEditorMaterial](ue_ue.StaticMeshComponent.md#selectededitormaterial)

#### Defined in

[ue/ue.d.ts:10595](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10595)

___

### SelectedEditorSection

• **SelectedEditorSection**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SelectedEditorSection](ue_ue.StaticMeshComponent.md#selectededitorsection)

#### Defined in

[ue/ue.d.ts:10594](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10594)

___

### StaticMesh

• **StaticMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[StaticMesh](ue_ue.StaticMeshComponent.md#staticmesh)

#### Defined in

[ue/ue.d.ts:10591](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10591)

___

### StaticMeshDerivedDataKey

• **StaticMeshDerivedDataKey**: `string`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[StaticMeshDerivedDataKey](ue_ue.StaticMeshComponent.md#staticmeshderiveddatakey)

#### Defined in

[ue/ue.d.ts:10620](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10620)

___

### StaticMeshImportVersion

• **StaticMeshImportVersion**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[StaticMeshImportVersion](ue_ue.StaticMeshComponent.md#staticmeshimportversion)

#### Defined in

[ue/ue.d.ts:10598](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10598)

___

### StreamingDistanceMultiplier

• **StreamingDistanceMultiplier**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[StreamingDistanceMultiplier](ue_ue.StaticMeshComponent.md#streamingdistancemultiplier)

#### Defined in

[ue/ue.d.ts:10616](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10616)

___

### StreamingTextureData

• **StreamingTextureData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StreamingTextureBuildInfo`](ue_ue.StreamingTextureBuildInfo.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[StreamingTextureData](ue_ue.StaticMeshComponent.md#streamingtexturedata)

#### Defined in

[ue/ue.d.ts:10619](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10619)

___

### SubDivisionStepSize

• **SubDivisionStepSize**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SubDivisionStepSize](ue_ue.StaticMeshComponent.md#subdivisionstepsize)

#### Defined in

[ue/ue.d.ts:10590](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10590)

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[TranslucencySortPriority](ue_ue.StaticMeshComponent.md#translucencysortpriority)

#### Defined in

[ue/ue.d.ts:12619](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12619)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[UCSModifiedProperties](ue_ue.StaticMeshComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L305)

___

### ViewOwnerDepthPriorityGroup

• **ViewOwnerDepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ViewOwnerDepthPriorityGroup](ue_ue.StaticMeshComponent.md#viewownerdepthprioritygroup)

#### Defined in

[ue/ue.d.ts:12559](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12559)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[VirtualTextureCullMips](ue_ue.StaticMeshComponent.md#virtualtexturecullmips)

#### Defined in

[ue/ue.d.ts:12623](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12623)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[VirtualTextureLodBias](ue_ue.StaticMeshComponent.md#virtualtexturelodbias)

#### Defined in

[ue/ue.d.ts:12622](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12622)

___

### VirtualTextureMinCoverage

• **VirtualTextureMinCoverage**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[VirtualTextureMinCoverage](ue_ue.StaticMeshComponent.md#virtualtexturemincoverage)

#### Defined in

[ue/ue.d.ts:12624](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12624)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[VirtualTextureRenderPassType](ue_ue.StaticMeshComponent.md#virtualtexturerenderpasstype)

#### Defined in

[ue/ue.d.ts:12625](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12625)

___

### VisibilityId

• **VisibilityId**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[VisibilityId](ue_ue.StaticMeshComponent.md#visibilityid)

#### Defined in

[ue/ue.d.ts:12620](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12620)

___

### WireframeColorOverride

• **WireframeColorOverride**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[WireframeColorOverride](ue_ue.StaticMeshComponent.md#wireframecoloroverride)

#### Defined in

[ue/ue.d.ts:10592](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10592)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[__tid_ActorComponent__](ue_ue.StaticMeshComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L336)

___

### \_\_tid\_GizmoHandleMeshComponent\_\_

• **\_\_tid\_GizmoHandleMeshComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:38059](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38059)

___

### \_\_tid\_MeshComponent\_\_

• **\_\_tid\_MeshComponent\_\_**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[__tid_MeshComponent__](ue_ue.StaticMeshComponent.md#__tid_meshcomponent__)

#### Defined in

[ue/ue.d.ts:2309](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2309)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[__tid_Object__](ue_ue.StaticMeshComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PrimitiveComponent\_\_

• **\_\_tid\_PrimitiveComponent\_\_**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[__tid_PrimitiveComponent__](ue_ue.StaticMeshComponent.md#__tid_primitivecomponent__)

#### Defined in

[ue/ue.d.ts:12761](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12761)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[__tid_SceneComponent__](ue_ue.StaticMeshComponent.md#__tid_scenecomponent__)

#### Defined in

[ue/ue.d.ts:12961](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12961)

___

### \_\_tid\_StaticMeshComponent\_\_

• **\_\_tid\_StaticMeshComponent\_\_**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[__tid_StaticMeshComponent__](ue_ue.StaticMeshComponent.md#__tid_staticmeshcomponent__)

#### Defined in

[ue/ue.d.ts:10633](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10633)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bAbsoluteLocation](ue_ue.StaticMeshComponent.md#babsolutelocation)

#### Defined in

[ue/ue.d.ts:12880](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12880)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bAbsoluteRotation](ue_ue.StaticMeshComponent.md#babsoluterotation)

#### Defined in

[ue/ue.d.ts:12881](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12881)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bAbsoluteScale](ue_ue.StaticMeshComponent.md#babsolutescale)

#### Defined in

[ue/ue.d.ts:12882](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12882)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bAffectDistanceFieldLighting](ue_ue.StaticMeshComponent.md#baffectdistancefieldlighting)

#### Defined in

[ue/ue.d.ts:12589](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12589)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bAffectDynamicIndirectLighting](ue_ue.StaticMeshComponent.md#baffectdynamicindirectlighting)

#### Defined in

[ue/ue.d.ts:12588](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12588)

___

### bAllowCullDistanceVolume

• **bAllowCullDistanceVolume**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bAllowCullDistanceVolume](ue_ue.StaticMeshComponent.md#ballowculldistancevolume)

#### Defined in

[ue/ue.d.ts:12573](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12573)

___

### bAlwaysCreatePhysicsState

• **bAlwaysCreatePhysicsState**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bAlwaysCreatePhysicsState](ue_ue.StaticMeshComponent.md#balwayscreatephysicsstate)

#### Defined in

[ue/ue.d.ts:12567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12567)

___

### bApplyImpulseOnDamage

• **bApplyImpulseOnDamage**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bApplyImpulseOnDamage](ue_ue.StaticMeshComponent.md#bapplyimpulseondamage)

#### Defined in

[ue/ue.d.ts:12606](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12606)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bAutoActivate](ue_ue.StaticMeshComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L296)

___

### bBatchImpostersAsInstances

• **bBatchImpostersAsInstances**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bBatchImpostersAsInstances](ue_ue.StaticMeshComponent.md#bbatchimpostersasinstances)

#### Defined in

[ue/ue.d.ts:12565](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12565)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.StaticMeshComponent.md#bboundschangetriggersstreamingdatarebuild)

#### Defined in

[ue/ue.d.ts:12889](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12889)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCanEverAffectNavigation](ue_ue.StaticMeshComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L299)

___

### bCastCinematicShadow

• **bCastCinematicShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastCinematicShadow](ue_ue.StaticMeshComponent.md#bcastcinematicshadow)

#### Defined in

[ue/ue.d.ts:12596](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12596)

___

### bCastDistanceFieldIndirectShadow

• **bCastDistanceFieldIndirectShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastDistanceFieldIndirectShadow](ue_ue.StaticMeshComponent.md#bcastdistancefieldindirectshadow)

#### Defined in

[ue/ue.d.ts:10606](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10606)

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastDynamicShadow](ue_ue.StaticMeshComponent.md#bcastdynamicshadow)

#### Defined in

[ue/ue.d.ts:12590](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12590)

___

### bCastFarShadow

• **bCastFarShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastFarShadow](ue_ue.StaticMeshComponent.md#bcastfarshadow)

#### Defined in

[ue/ue.d.ts:12594](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12594)

___

### bCastHiddenShadow

• **bCastHiddenShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastHiddenShadow](ue_ue.StaticMeshComponent.md#bcasthiddenshadow)

#### Defined in

[ue/ue.d.ts:12597](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12597)

___

### bCastInsetShadow

• **bCastInsetShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastInsetShadow](ue_ue.StaticMeshComponent.md#bcastinsetshadow)

#### Defined in

[ue/ue.d.ts:12595](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12595)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastShadowAsTwoSided](ue_ue.StaticMeshComponent.md#bcastshadowastwosided)

#### Defined in

[ue/ue.d.ts:12598](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12598)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastStaticShadow](ue_ue.StaticMeshComponent.md#bcaststaticshadow)

#### Defined in

[ue/ue.d.ts:12591](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12591)

___

### bCastVolumetricTranslucentShadow

• **bCastVolumetricTranslucentShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastVolumetricTranslucentShadow](ue_ue.StaticMeshComponent.md#bcastvolumetrictranslucentshadow)

#### Defined in

[ue/ue.d.ts:12592](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12592)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bComponentToWorldUpdated](ue_ue.StaticMeshComponent.md#bcomponenttoworldupdated)

#### Defined in

[ue/ue.d.ts:12879](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12879)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCreatedByConstructionScript](ue_ue.StaticMeshComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L294)

___

### bCustomOverrideVertexColorPerLOD

• **bCustomOverrideVertexColorPerLOD**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCustomOverrideVertexColorPerLOD](ue_ue.StaticMeshComponent.md#bcustomoverridevertexcolorperlod)

#### Defined in

[ue/ue.d.ts:10610](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10610)

___

### bDisallowMeshPaintPerInstance

• **bDisallowMeshPaintPerInstance**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bDisallowMeshPaintPerInstance](ue_ue.StaticMeshComponent.md#bdisallowmeshpaintperinstance)

#### Defined in

[ue/ue.d.ts:10603](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10603)

___

### bDisplayVertexColors

• **bDisplayVertexColors**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bDisplayVertexColors](ue_ue.StaticMeshComponent.md#bdisplayvertexcolors)

#### Defined in

[ue/ue.d.ts:10611](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10611)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bEditableWhenInherited](ue_ue.StaticMeshComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L298)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bEnableAutoLODGeneration](ue_ue.StaticMeshComponent.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:12563](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12563)

___

### bEnableMaterialParameterCaching

• **bEnableMaterialParameterCaching**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bEnableMaterialParameterCaching](ue_ue.StaticMeshComponent.md#benablematerialparametercaching)

#### Defined in

[ue/ue.d.ts:2297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2297)

___

### bEvaluateWorldPositionOffset

• **bEvaluateWorldPositionOffset**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bEvaluateWorldPositionOffset](ue_ue.StaticMeshComponent.md#bevaluateworldpositionoffset)

#### Defined in

[ue/ue.d.ts:10593](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10593)

___

### bExcludeFromLightAttachmentGroup

• **bExcludeFromLightAttachmentGroup**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bExcludeFromLightAttachmentGroup](ue_ue.StaticMeshComponent.md#bexcludefromlightattachmentgroup)

#### Defined in

[ue/ue.d.ts:12601](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12601)

___

### bForceMipStreaming

• **bForceMipStreaming**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bForceMipStreaming](ue_ue.StaticMeshComponent.md#bforcemipstreaming)

#### Defined in

[ue/ue.d.ts:12585](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12585)

___

### bForceNavigationObstacle

• **bForceNavigationObstacle**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bForceNavigationObstacle](ue_ue.StaticMeshComponent.md#bforcenavigationobstacle)

#### Defined in

[ue/ue.d.ts:10602](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10602)

___

### bGenerateOverlapEvents

• **bGenerateOverlapEvents**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bGenerateOverlapEvents](ue_ue.StaticMeshComponent.md#bgenerateoverlapevents)

#### Defined in

[ue/ue.d.ts:12568](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12568)

___

### bHasCustomNavigableGeometry

• **bHasCustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bHasCustomNavigableGeometry](ue_ue.StaticMeshComponent.md#bhascustomnavigablegeometry)

#### Defined in

[ue/ue.d.ts:12612](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12612)

___

### bHasMotionBlurVelocityMeshes

• **bHasMotionBlurVelocityMeshes**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bHasMotionBlurVelocityMeshes](ue_ue.StaticMeshComponent.md#bhasmotionblurvelocitymeshes)

#### Defined in

[ue/ue.d.ts:12574](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12574)

___

### bHasPerInstanceHitProxies

• **bHasPerInstanceHitProxies**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bHasPerInstanceHitProxies](ue_ue.StaticMeshComponent.md#bhasperinstancehitproxies)

#### Defined in

[ue/ue.d.ts:12586](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12586)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bHiddenInGame](ue_ue.StaticMeshComponent.md#bhiddeningame)

#### Defined in

[ue/ue.d.ts:12884](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12884)

___

### bIgnoreInstanceForTextureStreaming

• **bIgnoreInstanceForTextureStreaming**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bIgnoreInstanceForTextureStreaming](ue_ue.StaticMeshComponent.md#bignoreinstancefortexturestreaming)

#### Defined in

[ue/ue.d.ts:10604](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10604)

___

### bIgnoreRadialForce

• **bIgnoreRadialForce**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bIgnoreRadialForce](ue_ue.StaticMeshComponent.md#bignoreradialforce)

#### Defined in

[ue/ue.d.ts:12605](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12605)

___

### bIgnoreRadialImpulse

• **bIgnoreRadialImpulse**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bIgnoreRadialImpulse](ue_ue.StaticMeshComponent.md#bignoreradialimpulse)

#### Defined in

[ue/ue.d.ts:12604](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12604)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bInstanceComponent](ue_ue.StaticMeshComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bIsActive](ue_ue.StaticMeshComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bIsEditorOnly](ue_ue.StaticMeshComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bIsVisualizationComponent](ue_ue.StaticMeshComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L301)

___

### bLightAsIfStatic

• **bLightAsIfStatic**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bLightAsIfStatic](ue_ue.StaticMeshComponent.md#blightasifstatic)

#### Defined in

[ue/ue.d.ts:12599](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12599)

___

### bLightAttachmentsAsGroup

• **bLightAttachmentsAsGroup**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bLightAttachmentsAsGroup](ue_ue.StaticMeshComponent.md#blightattachmentsasgroup)

#### Defined in

[ue/ue.d.ts:12600](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12600)

___

### bMultiBodyOverlap

• **bMultiBodyOverlap**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bMultiBodyOverlap](ue_ue.StaticMeshComponent.md#bmultibodyoverlap)

#### Defined in

[ue/ue.d.ts:12569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12569)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bNetAddressable](ue_ue.StaticMeshComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L293)

___

### bNeverDistanceCull

• **bNeverDistanceCull**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bNeverDistanceCull](ue_ue.StaticMeshComponent.md#bneverdistancecull)

#### Defined in

[ue/ue.d.ts:12566](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12566)

___

### bOnlyOwnerSee

• **bOnlyOwnerSee**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bOnlyOwnerSee](ue_ue.StaticMeshComponent.md#bonlyownersee)

#### Defined in

[ue/ue.d.ts:12581](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12581)

___

### bOverrideDistanceFieldSelfShadowBias

• **bOverrideDistanceFieldSelfShadowBias**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bOverrideDistanceFieldSelfShadowBias](ue_ue.StaticMeshComponent.md#boverridedistancefieldselfshadowbias)

#### Defined in

[ue/ue.d.ts:10607](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10607)

___

### bOverrideLightMapRes

• **bOverrideLightMapRes**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bOverrideLightMapRes](ue_ue.StaticMeshComponent.md#boverridelightmapres)

#### Defined in

[ue/ue.d.ts:10605](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10605)

___

### bOverrideMinLOD

• **bOverrideMinLOD**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bOverrideMinLOD](ue_ue.StaticMeshComponent.md#boverrideminlod)

#### Defined in

[ue/ue.d.ts:10600](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10600)

___

### bOverrideNavigationExport

• **bOverrideNavigationExport**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bOverrideNavigationExport](ue_ue.StaticMeshComponent.md#boverridenavigationexport)

#### Defined in

[ue/ue.d.ts:10601](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10601)

___

### bOverrideWireframeColor

• **bOverrideWireframeColor**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bOverrideWireframeColor](ue_ue.StaticMeshComponent.md#boverridewireframecolor)

#### Defined in

[ue/ue.d.ts:10599](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10599)

___

### bOwnerNoSee

• **bOwnerNoSee**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bOwnerNoSee](ue_ue.StaticMeshComponent.md#bownernosee)

#### Defined in

[ue/ue.d.ts:12580](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12580)

___

### bReceiveMobileCSMShadows

• **bReceiveMobileCSMShadows**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bReceiveMobileCSMShadows](ue_ue.StaticMeshComponent.md#breceivemobilecsmshadows)

#### Defined in

[ue/ue.d.ts:12602](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12602)

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bReceivesDecals](ue_ue.StaticMeshComponent.md#breceivesdecals)

#### Defined in

[ue/ue.d.ts:12579](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12579)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bRenderCustomDepth](ue_ue.StaticMeshComponent.md#brendercustomdepth)

#### Defined in

[ue/ue.d.ts:12611](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12611)

___

### bRenderInDepthPass

• **bRenderInDepthPass**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bRenderInDepthPass](ue_ue.StaticMeshComponent.md#brenderindepthpass)

#### Defined in

[ue/ue.d.ts:12578](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12578)

___

### bRenderInMainPass

• **bRenderInMainPass**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bRenderInMainPass](ue_ue.StaticMeshComponent.md#brenderinmainpass)

#### Defined in

[ue/ue.d.ts:12577](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12577)

___

### bReplicatePhysicsToAutonomousProxy

• **bReplicatePhysicsToAutonomousProxy**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bReplicatePhysicsToAutonomousProxy](ue_ue.StaticMeshComponent.md#breplicatephysicstoautonomousproxy)

#### Defined in

[ue/ue.d.ts:12607](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12607)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bReplicates](ue_ue.StaticMeshComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L292)

___

### bReturnMaterialOnMove

• **bReturnMaterialOnMove**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bReturnMaterialOnMove](ue_ue.StaticMeshComponent.md#breturnmaterialonmove)

#### Defined in

[ue/ue.d.ts:12571](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12571)

___

### bReverseCulling

• **bReverseCulling**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bReverseCulling](ue_ue.StaticMeshComponent.md#breverseculling)

#### Defined in

[ue/ue.d.ts:10612](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10612)

___

### bSelectable

• **bSelectable**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bSelectable](ue_ue.StaticMeshComponent.md#bselectable)

#### Defined in

[ue/ue.d.ts:12584](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12584)

___

### bSelfShadowOnly

• **bSelfShadowOnly**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bSelfShadowOnly](ue_ue.StaticMeshComponent.md#bselfshadowonly)

#### Defined in

[ue/ue.d.ts:12593](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12593)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bShouldBeAttached](ue_ue.StaticMeshComponent.md#bshouldbeattached)

#### Defined in

[ue/ue.d.ts:12885](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12885)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.StaticMeshComponent.md#bshouldsnaplocationwhenattached)

#### Defined in

[ue/ue.d.ts:12886](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12886)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.StaticMeshComponent.md#bshouldsnaprotationwhenattached)

#### Defined in

[ue/ue.d.ts:12887](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12887)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.StaticMeshComponent.md#bshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12888](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12888)

___

### bSingleSampleShadowFromStationaryLights

• **bSingleSampleShadowFromStationaryLights**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bSingleSampleShadowFromStationaryLights](ue_ue.StaticMeshComponent.md#bsinglesampleshadowfromstationarylights)

#### Defined in

[ue/ue.d.ts:12603](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12603)

___

### bTraceComplexOnMove

• **bTraceComplexOnMove**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bTraceComplexOnMove](ue_ue.StaticMeshComponent.md#btracecomplexonmove)

#### Defined in

[ue/ue.d.ts:12570](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12570)

___

### bTreatAsBackgroundForOcclusion

• **bTreatAsBackgroundForOcclusion**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bTreatAsBackgroundForOcclusion](ue_ue.StaticMeshComponent.md#btreatasbackgroundforocclusion)

#### Defined in

[ue/ue.d.ts:12582](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12582)

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bUseAsOccluder](ue_ue.StaticMeshComponent.md#buseasoccluder)

#### Defined in

[ue/ue.d.ts:12583](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12583)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bUseAttachParentBound](ue_ue.StaticMeshComponent.md#buseattachparentbound)

#### Defined in

[ue/ue.d.ts:12890](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12890)

___

### bUseDefaultCollision

• **bUseDefaultCollision**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bUseDefaultCollision](ue_ue.StaticMeshComponent.md#busedefaultcollision)

#### Defined in

[ue/ue.d.ts:10609](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10609)

___

### bUseEditorCompositing

• **bUseEditorCompositing**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bUseEditorCompositing](ue_ue.StaticMeshComponent.md#buseeditorcompositing)

#### Defined in

[ue/ue.d.ts:12610](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12610)

___

### bUseMaxLODAsImposter

• **bUseMaxLODAsImposter**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bUseMaxLODAsImposter](ue_ue.StaticMeshComponent.md#busemaxlodasimposter)

#### Defined in

[ue/ue.d.ts:12564](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12564)

___

### bUseSubDivisions

• **bUseSubDivisions**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bUseSubDivisions](ue_ue.StaticMeshComponent.md#busesubdivisions)

#### Defined in

[ue/ue.d.ts:10608](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10608)

___

### bUseViewOwnerDepthPriorityGroup

• **bUseViewOwnerDepthPriorityGroup**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bUseViewOwnerDepthPriorityGroup](ue_ue.StaticMeshComponent.md#buseviewownerdepthprioritygroup)

#### Defined in

[ue/ue.d.ts:12572](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12572)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bVisible](ue_ue.StaticMeshComponent.md#bvisible)

#### Defined in

[ue/ue.d.ts:12883](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12883)

___

### bVisibleInRayTracing

• **bVisibleInRayTracing**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bVisibleInRayTracing](ue_ue.StaticMeshComponent.md#bvisibleinraytracing)

#### Defined in

[ue/ue.d.ts:12576](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12576)

___

### bVisibleInReflectionCaptures

• **bVisibleInReflectionCaptures**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bVisibleInReflectionCaptures](ue_ue.StaticMeshComponent.md#bvisibleinreflectioncaptures)

#### Defined in

[ue/ue.d.ts:12575](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12575)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bVisualizeComponent](ue_ue.StaticMeshComponent.md#bvisualizecomponent)

#### Defined in

[ue/ue.d.ts:12891](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12891)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[Activate](ue_ue.StaticMeshComponent.md#activate)

#### Defined in

[ue/ue.d.ts:306](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L306)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AddAngularImpulse](ue_ue.StaticMeshComponent.md#addangularimpulse)

#### Defined in

[ue/ue.d.ts:12645](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12645)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AddAngularImpulseInDegrees](ue_ue.StaticMeshComponent.md#addangularimpulseindegrees)

#### Defined in

[ue/ue.d.ts:12646](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12646)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AddAngularImpulseInRadians](ue_ue.StaticMeshComponent.md#addangularimpulseinradians)

#### Defined in

[ue/ue.d.ts:12647](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12647)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AddForce](ue_ue.StaticMeshComponent.md#addforce)

#### Defined in

[ue/ue.d.ts:12648](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12648)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AddForceAtLocation](ue_ue.StaticMeshComponent.md#addforceatlocation)

#### Defined in

[ue/ue.d.ts:12649](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12649)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AddForceAtLocationLocal](ue_ue.StaticMeshComponent.md#addforceatlocationlocal)

#### Defined in

[ue/ue.d.ts:12650](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12650)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AddImpulse](ue_ue.StaticMeshComponent.md#addimpulse)

#### Defined in

[ue/ue.d.ts:12651](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12651)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AddImpulseAtLocation](ue_ue.StaticMeshComponent.md#addimpulseatlocation)

#### Defined in

[ue/ue.d.ts:12652](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12652)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AddRadialForce](ue_ue.StaticMeshComponent.md#addradialforce)

#### Defined in

[ue/ue.d.ts:12653](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12653)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AddRadialImpulse](ue_ue.StaticMeshComponent.md#addradialimpulse)

#### Defined in

[ue/ue.d.ts:12654](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12654)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AddTickPrerequisiteActor](ue_ue.StaticMeshComponent.md#addtickprerequisiteactor)

#### Defined in

[ue/ue.d.ts:307](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L307)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AddTickPrerequisiteComponent](ue_ue.StaticMeshComponent.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:308](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L308)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AddTorque](ue_ue.StaticMeshComponent.md#addtorque)

#### Defined in

[ue/ue.d.ts:12655](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12655)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AddTorqueInDegrees](ue_ue.StaticMeshComponent.md#addtorqueindegrees)

#### Defined in

[ue/ue.d.ts:12656](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12656)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AddTorqueInRadians](ue_ue.StaticMeshComponent.md#addtorqueinradians)

#### Defined in

[ue/ue.d.ts:12657](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12657)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CanCharacterStepUp](ue_ue.StaticMeshComponent.md#cancharacterstepup)

#### Defined in

[ue/ue.d.ts:12658](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12658)

___

### ClearMoveIgnoreActors

▸ **ClearMoveIgnoreActors**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ClearMoveIgnoreActors](ue_ue.StaticMeshComponent.md#clearmoveignoreactors)

#### Defined in

[ue/ue.d.ts:12659](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12659)

___

### ClearMoveIgnoreComponents

▸ **ClearMoveIgnoreComponents**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ClearMoveIgnoreComponents](ue_ue.StaticMeshComponent.md#clearmoveignorecomponents)

#### Defined in

[ue/ue.d.ts:12660](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12660)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ComponentHasTag](ue_ue.StaticMeshComponent.md#componenthastag)

#### Defined in

[ue/ue.d.ts:309](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L309)

___

### CopyArrayOfMoveIgnoreActors

▸ **CopyArrayOfMoveIgnoreActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CopyArrayOfMoveIgnoreActors](ue_ue.StaticMeshComponent.md#copyarrayofmoveignoreactors)

#### Defined in

[ue/ue.d.ts:12661](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12661)

___

### CopyArrayOfMoveIgnoreComponents

▸ **CopyArrayOfMoveIgnoreComponents**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CopyArrayOfMoveIgnoreComponents](ue_ue.StaticMeshComponent.md#copyarrayofmoveignorecomponents)

#### Defined in

[ue/ue.d.ts:12662](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12662)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CreateAndSetMaterialInstanceDynamic](ue_ue.StaticMeshComponent.md#createandsetmaterialinstancedynamic)

#### Defined in

[ue/ue.d.ts:12663](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12663)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.StaticMeshComponent.md#createandsetmaterialinstancedynamicfrommaterial)

#### Defined in

[ue/ue.d.ts:12664](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12664)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CreateDefaultSubobject](ue_ue.StaticMeshComponent.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CreateDynamicMaterialInstance](ue_ue.StaticMeshComponent.md#createdynamicmaterialinstance)

#### Defined in

[ue/ue.d.ts:12665](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12665)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[Deactivate](ue_ue.StaticMeshComponent.md#deactivate)

#### Defined in

[ue/ue.d.ts:310](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L310)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[DetachFromParent](ue_ue.StaticMeshComponent.md#detachfromparent)

#### Defined in

[ue/ue.d.ts:12895](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12895)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[DoesSocketExist](ue_ue.StaticMeshComponent.md#doessocketexist)

#### Defined in

[ue/ue.d.ts:12896](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12896)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ExecuteUbergraph](ue_ue.StaticMeshComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetAllSocketNames](ue_ue.StaticMeshComponent.md#getallsocketnames)

#### Defined in

[ue/ue.d.ts:12897](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12897)

___

### GetAngularDamping

▸ **GetAngularDamping**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetAngularDamping](ue_ue.StaticMeshComponent.md#getangulardamping)

#### Defined in

[ue/ue.d.ts:12666](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12666)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetAttachParent](ue_ue.StaticMeshComponent.md#getattachparent)

#### Defined in

[ue/ue.d.ts:12898](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12898)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetAttachSocketName](ue_ue.StaticMeshComponent.md#getattachsocketname)

#### Defined in

[ue/ue.d.ts:12899](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12899)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetCenterOfMass](ue_ue.StaticMeshComponent.md#getcenterofmass)

#### Defined in

[ue/ue.d.ts:12667](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12667)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetChildComponent](ue_ue.StaticMeshComponent.md#getchildcomponent)

#### Defined in

[ue/ue.d.ts:12900](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12900)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetChildrenComponents](ue_ue.StaticMeshComponent.md#getchildrencomponents)

#### Defined in

[ue/ue.d.ts:12901](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12901)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetClass](ue_ue.StaticMeshComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetClosestPointOnCollision](ue_ue.StaticMeshComponent.md#getclosestpointoncollision)

#### Defined in

[ue/ue.d.ts:12668](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12668)

___

### GetCollisionEnabled

▸ **GetCollisionEnabled**(): [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Returns

[`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetCollisionEnabled](ue_ue.StaticMeshComponent.md#getcollisionenabled)

#### Defined in

[ue/ue.d.ts:12669](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12669)

___

### GetCollisionObjectType

▸ **GetCollisionObjectType**(): [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Returns

[`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetCollisionObjectType](ue_ue.StaticMeshComponent.md#getcollisionobjecttype)

#### Defined in

[ue/ue.d.ts:12670](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12670)

___

### GetCollisionProfileName

▸ **GetCollisionProfileName**(): `string`

#### Returns

`string`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetCollisionProfileName](ue_ue.StaticMeshComponent.md#getcollisionprofilename)

#### Defined in

[ue/ue.d.ts:12671](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12671)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetCollisionResponseToChannel](ue_ue.StaticMeshComponent.md#getcollisionresponsetochannel)

#### Defined in

[ue/ue.d.ts:12672](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12672)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetComponentTickInterval](ue_ue.StaticMeshComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L311)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetComponentVelocity](ue_ue.StaticMeshComponent.md#getcomponentvelocity)

#### Defined in

[ue/ue.d.ts:12902](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12902)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetForwardVector](ue_ue.StaticMeshComponent.md#getforwardvector)

#### Defined in

[ue/ue.d.ts:12903](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12903)

___

### GetGenerateOverlapEvents

▸ **GetGenerateOverlapEvents**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetGenerateOverlapEvents](ue_ue.StaticMeshComponent.md#getgenerateoverlapevents)

#### Defined in

[ue/ue.d.ts:12673](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12673)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetInertiaTensor](ue_ue.StaticMeshComponent.md#getinertiatensor)

#### Defined in

[ue/ue.d.ts:12674](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12674)

___

### GetLinearDamping

▸ **GetLinearDamping**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetLinearDamping](ue_ue.StaticMeshComponent.md#getlineardamping)

#### Defined in

[ue/ue.d.ts:12675](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12675)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetLocalBounds](ue_ue.StaticMeshComponent.md#getlocalbounds)

#### Defined in

[ue/ue.d.ts:10623](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10623)

___

### GetMass

▸ **GetMass**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetMass](ue_ue.StaticMeshComponent.md#getmass)

#### Defined in

[ue/ue.d.ts:12676](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12676)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetMassScale](ue_ue.StaticMeshComponent.md#getmassscale)

#### Defined in

[ue/ue.d.ts:12677](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12677)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetMaterial](ue_ue.StaticMeshComponent.md#getmaterial)

#### Defined in

[ue/ue.d.ts:12678](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12678)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetMaterialFromCollisionFaceIndex](ue_ue.StaticMeshComponent.md#getmaterialfromcollisionfaceindex)

#### Defined in

[ue/ue.d.ts:12679](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12679)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetMaterialIndex](ue_ue.StaticMeshComponent.md#getmaterialindex)

#### Defined in

[ue/ue.d.ts:2298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2298)

___

### GetMaterialSlotNames

▸ **GetMaterialSlotNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetMaterialSlotNames](ue_ue.StaticMeshComponent.md#getmaterialslotnames)

#### Defined in

[ue/ue.d.ts:2300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2300)

___

### GetMaterials

▸ **GetMaterials**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetMaterials](ue_ue.StaticMeshComponent.md#getmaterials)

#### Defined in

[ue/ue.d.ts:2299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2299)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetName](ue_ue.StaticMeshComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetNumChildrenComponents](ue_ue.StaticMeshComponent.md#getnumchildrencomponents)

#### Defined in

[ue/ue.d.ts:12904](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12904)

___

### GetNumMaterials

▸ **GetNumMaterials**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetNumMaterials](ue_ue.StaticMeshComponent.md#getnummaterials)

#### Defined in

[ue/ue.d.ts:12680](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12680)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetOuter](ue_ue.StaticMeshComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetOverlappingActors](ue_ue.StaticMeshComponent.md#getoverlappingactors)

#### Defined in

[ue/ue.d.ts:12681](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12681)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetOverlappingComponents](ue_ue.StaticMeshComponent.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:12682](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12682)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetOwner](ue_ue.StaticMeshComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L312)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetParentComponents](ue_ue.StaticMeshComponent.md#getparentcomponents)

#### Defined in

[ue/ue.d.ts:12905](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12905)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetPhysicsAngularVelocity](ue_ue.StaticMeshComponent.md#getphysicsangularvelocity)

#### Defined in

[ue/ue.d.ts:12683](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12683)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetPhysicsAngularVelocityInDegrees](ue_ue.StaticMeshComponent.md#getphysicsangularvelocityindegrees)

#### Defined in

[ue/ue.d.ts:12684](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12684)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetPhysicsAngularVelocityInRadians](ue_ue.StaticMeshComponent.md#getphysicsangularvelocityinradians)

#### Defined in

[ue/ue.d.ts:12685](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12685)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetPhysicsLinearVelocity](ue_ue.StaticMeshComponent.md#getphysicslinearvelocity)

#### Defined in

[ue/ue.d.ts:12686](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12686)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetPhysicsLinearVelocityAtPoint](ue_ue.StaticMeshComponent.md#getphysicslinearvelocityatpoint)

#### Defined in

[ue/ue.d.ts:12687](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12687)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetPhysicsVolume](ue_ue.StaticMeshComponent.md#getphysicsvolume)

#### Defined in

[ue/ue.d.ts:12906](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12906)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetRelativeTransform](ue_ue.StaticMeshComponent.md#getrelativetransform)

#### Defined in

[ue/ue.d.ts:12907](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12907)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetRightVector](ue_ue.StaticMeshComponent.md#getrightvector)

#### Defined in

[ue/ue.d.ts:12908](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12908)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.StaticMeshComponent.md#getshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12909](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12909)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetSocketLocation](ue_ue.StaticMeshComponent.md#getsocketlocation)

#### Defined in

[ue/ue.d.ts:12910](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12910)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetSocketQuaternion](ue_ue.StaticMeshComponent.md#getsocketquaternion)

#### Defined in

[ue/ue.d.ts:12911](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12911)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetSocketRotation](ue_ue.StaticMeshComponent.md#getsocketrotation)

#### Defined in

[ue/ue.d.ts:12912](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12912)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetSocketTransform](ue_ue.StaticMeshComponent.md#getsockettransform)

#### Defined in

[ue/ue.d.ts:12913](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12913)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetUpVector](ue_ue.StaticMeshComponent.md#getupvector)

#### Defined in

[ue/ue.d.ts:12914](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12914)

___

### GetWalkableSlopeOverride

▸ **GetWalkableSlopeOverride**(): [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Returns

[`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetWalkableSlopeOverride](ue_ue.StaticMeshComponent.md#getwalkableslopeoverride)

#### Defined in

[ue/ue.d.ts:12688](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12688)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetWorld](ue_ue.StaticMeshComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IgnoreActorWhenMoving](ue_ue.StaticMeshComponent.md#ignoreactorwhenmoving)

#### Defined in

[ue/ue.d.ts:12689](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12689)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IgnoreComponentWhenMoving](ue_ue.StaticMeshComponent.md#ignorecomponentwhenmoving)

#### Defined in

[ue/ue.d.ts:12690](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12690)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsActive](ue_ue.StaticMeshComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L313)

___

### IsAnyRigidBodyAwake

▸ **IsAnyRigidBodyAwake**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsAnyRigidBodyAwake](ue_ue.StaticMeshComponent.md#isanyrigidbodyawake)

#### Defined in

[ue/ue.d.ts:12691](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12691)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsAnySimulatingPhysics](ue_ue.StaticMeshComponent.md#isanysimulatingphysics)

#### Defined in

[ue/ue.d.ts:12915](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12915)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsBeingDestroyed](ue_ue.StaticMeshComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsComponentTickEnabled](ue_ue.StaticMeshComponent.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L315)

___

### IsGravityEnabled

▸ **IsGravityEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsGravityEnabled](ue_ue.StaticMeshComponent.md#isgravityenabled)

#### Defined in

[ue/ue.d.ts:12692](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12692)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsMaterialSlotNameValid](ue_ue.StaticMeshComponent.md#ismaterialslotnamevalid)

#### Defined in

[ue/ue.d.ts:2301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2301)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsOverlappingActor](ue_ue.StaticMeshComponent.md#isoverlappingactor)

#### Defined in

[ue/ue.d.ts:12693](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12693)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsOverlappingComponent](ue_ue.StaticMeshComponent.md#isoverlappingcomponent)

#### Defined in

[ue/ue.d.ts:12694](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12694)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsSimulatingPhysics](ue_ue.StaticMeshComponent.md#issimulatingphysics)

#### Defined in

[ue/ue.d.ts:12916](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12916)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsVisible](ue_ue.StaticMeshComponent.md#isvisible)

#### Defined in

[ue/ue.d.ts:12917](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12917)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_AddLocalOffset](ue_ue.StaticMeshComponent.md#k2_addlocaloffset)

#### Defined in

[ue/ue.d.ts:12918](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12918)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_AddLocalRotation](ue_ue.StaticMeshComponent.md#k2_addlocalrotation)

#### Defined in

[ue/ue.d.ts:12919](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12919)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_AddLocalTransform](ue_ue.StaticMeshComponent.md#k2_addlocaltransform)

#### Defined in

[ue/ue.d.ts:12920](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12920)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_AddRelativeLocation](ue_ue.StaticMeshComponent.md#k2_addrelativelocation)

#### Defined in

[ue/ue.d.ts:12921](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12921)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_AddRelativeRotation](ue_ue.StaticMeshComponent.md#k2_addrelativerotation)

#### Defined in

[ue/ue.d.ts:12922](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12922)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_AddWorldOffset](ue_ue.StaticMeshComponent.md#k2_addworldoffset)

#### Defined in

[ue/ue.d.ts:12923](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12923)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_AddWorldRotation](ue_ue.StaticMeshComponent.md#k2_addworldrotation)

#### Defined in

[ue/ue.d.ts:12924](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12924)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_AddWorldTransform](ue_ue.StaticMeshComponent.md#k2_addworldtransform)

#### Defined in

[ue/ue.d.ts:12925](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12925)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_AttachTo](ue_ue.StaticMeshComponent.md#k2_attachto)

#### Defined in

[ue/ue.d.ts:12926](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12926)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_AttachToComponent](ue_ue.StaticMeshComponent.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:12927](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12927)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_BoxOverlapComponent](ue_ue.StaticMeshComponent.md#k2_boxoverlapcomponent)

#### Defined in

[ue/ue.d.ts:12695](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12695)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_DestroyComponent](ue_ue.StaticMeshComponent.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L316)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_DetachFromComponent](ue_ue.StaticMeshComponent.md#k2_detachfromcomponent)

#### Defined in

[ue/ue.d.ts:12928](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12928)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_GetComponentLocation](ue_ue.StaticMeshComponent.md#k2_getcomponentlocation)

#### Defined in

[ue/ue.d.ts:12929](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12929)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_GetComponentRotation](ue_ue.StaticMeshComponent.md#k2_getcomponentrotation)

#### Defined in

[ue/ue.d.ts:12930](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12930)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_GetComponentScale](ue_ue.StaticMeshComponent.md#k2_getcomponentscale)

#### Defined in

[ue/ue.d.ts:12931](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12931)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_GetComponentToWorld](ue_ue.StaticMeshComponent.md#k2_getcomponenttoworld)

#### Defined in

[ue/ue.d.ts:12932](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12932)

___

### K2\_IsCollisionEnabled

▸ **K2_IsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_IsCollisionEnabled](ue_ue.StaticMeshComponent.md#k2_iscollisionenabled)

#### Defined in

[ue/ue.d.ts:12696](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12696)

___

### K2\_IsPhysicsCollisionEnabled

▸ **K2_IsPhysicsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_IsPhysicsCollisionEnabled](ue_ue.StaticMeshComponent.md#k2_isphysicscollisionenabled)

#### Defined in

[ue/ue.d.ts:12697](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12697)

___

### K2\_IsQueryCollisionEnabled

▸ **K2_IsQueryCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_IsQueryCollisionEnabled](ue_ue.StaticMeshComponent.md#k2_isquerycollisionenabled)

#### Defined in

[ue/ue.d.ts:12698](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12698)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_LineTraceComponent](ue_ue.StaticMeshComponent.md#k2_linetracecomponent)

#### Defined in

[ue/ue.d.ts:12699](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12699)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_SetRelativeLocation](ue_ue.StaticMeshComponent.md#k2_setrelativelocation)

#### Defined in

[ue/ue.d.ts:12933](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12933)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.StaticMeshComponent.md#k2_setrelativelocationandrotation)

#### Defined in

[ue/ue.d.ts:12934](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12934)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_SetRelativeRotation](ue_ue.StaticMeshComponent.md#k2_setrelativerotation)

#### Defined in

[ue/ue.d.ts:12935](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12935)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_SetRelativeTransform](ue_ue.StaticMeshComponent.md#k2_setrelativetransform)

#### Defined in

[ue/ue.d.ts:12936](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12936)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_SetWorldLocation](ue_ue.StaticMeshComponent.md#k2_setworldlocation)

#### Defined in

[ue/ue.d.ts:12937](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12937)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.StaticMeshComponent.md#k2_setworldlocationandrotation)

#### Defined in

[ue/ue.d.ts:12938](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12938)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_SetWorldRotation](ue_ue.StaticMeshComponent.md#k2_setworldrotation)

#### Defined in

[ue/ue.d.ts:12939](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12939)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_SetWorldTransform](ue_ue.StaticMeshComponent.md#k2_setworldtransform)

#### Defined in

[ue/ue.d.ts:12940](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12940)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_SphereOverlapComponent](ue_ue.StaticMeshComponent.md#k2_sphereoverlapcomponent)

#### Defined in

[ue/ue.d.ts:12700](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12700)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_SphereTraceComponent](ue_ue.StaticMeshComponent.md#k2_spheretracecomponent)

#### Defined in

[ue/ue.d.ts:12701](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12701)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnRep_AttachChildren](ue_ue.StaticMeshComponent.md#onrep_attachchildren)

#### Defined in

[ue/ue.d.ts:12941](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12941)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnRep_AttachParent](ue_ue.StaticMeshComponent.md#onrep_attachparent)

#### Defined in

[ue/ue.d.ts:12942](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12942)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnRep_AttachSocketName](ue_ue.StaticMeshComponent.md#onrep_attachsocketname)

#### Defined in

[ue/ue.d.ts:12943](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12943)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnRep_IsActive](ue_ue.StaticMeshComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L317)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnRep_StaticMesh](ue_ue.StaticMeshComponent.md#onrep_staticmesh)

#### Defined in

[ue/ue.d.ts:10624](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10624)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnRep_Transform](ue_ue.StaticMeshComponent.md#onrep_transform)

#### Defined in

[ue/ue.d.ts:12944](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12944)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnRep_Visibility](ue_ue.StaticMeshComponent.md#onrep_visibility)

#### Defined in

[ue/ue.d.ts:12945](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12945)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[PrestreamTextures](ue_ue.StaticMeshComponent.md#prestreamtextures)

#### Defined in

[ue/ue.d.ts:2302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2302)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[PutRigidBodyToSleep](ue_ue.StaticMeshComponent.md#putrigidbodytosleep)

#### Defined in

[ue/ue.d.ts:12702](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12702)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ReceiveBeginPlay](ue_ue.StaticMeshComponent.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:318](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L318)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ReceiveEndPlay](ue_ue.StaticMeshComponent.md#receiveendplay)

#### Defined in

[ue/ue.d.ts:319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L319)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ReceiveTick](ue_ue.StaticMeshComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[RegisterComponent](ue_ue.StaticMeshComponent.md#registercomponent)

#### Defined in

[ue/ue.d.ts:321](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L321)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[RemoveTickPrerequisiteActor](ue_ue.StaticMeshComponent.md#removetickprerequisiteactor)

#### Defined in

[ue/ue.d.ts:322](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L322)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.StaticMeshComponent.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L323)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ResetRelativeTransform](ue_ue.StaticMeshComponent.md#resetrelativetransform)

#### Defined in

[ue/ue.d.ts:12946](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12946)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ScaleByMomentOfInertia](ue_ue.StaticMeshComponent.md#scalebymomentofinertia)

#### Defined in

[ue/ue.d.ts:12703](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12703)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetAbsolute](ue_ue.StaticMeshComponent.md#setabsolute)

#### Defined in

[ue/ue.d.ts:12947](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12947)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetActive](ue_ue.StaticMeshComponent.md#setactive)

#### Defined in

[ue/ue.d.ts:324](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L324)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetAllMassScale](ue_ue.StaticMeshComponent.md#setallmassscale)

#### Defined in

[ue/ue.d.ts:12704](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12704)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetAllPhysicsAngularVelocityInDegrees](ue_ue.StaticMeshComponent.md#setallphysicsangularvelocityindegrees)

#### Defined in

[ue/ue.d.ts:12705](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12705)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetAllPhysicsAngularVelocityInRadians](ue_ue.StaticMeshComponent.md#setallphysicsangularvelocityinradians)

#### Defined in

[ue/ue.d.ts:12706](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12706)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetAllPhysicsLinearVelocity](ue_ue.StaticMeshComponent.md#setallphysicslinearvelocity)

#### Defined in

[ue/ue.d.ts:12707](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12707)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetAllUseCCD](ue_ue.StaticMeshComponent.md#setalluseccd)

#### Defined in

[ue/ue.d.ts:12708](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12708)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetAngularDamping](ue_ue.StaticMeshComponent.md#setangulardamping)

#### Defined in

[ue/ue.d.ts:12709](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12709)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetAutoActivate](ue_ue.StaticMeshComponent.md#setautoactivate)

#### Defined in

[ue/ue.d.ts:325](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L325)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetBoundsScale](ue_ue.StaticMeshComponent.md#setboundsscale)

#### Defined in

[ue/ue.d.ts:12710](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12710)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetCastInsetShadow](ue_ue.StaticMeshComponent.md#setcastinsetshadow)

#### Defined in

[ue/ue.d.ts:12711](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12711)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetCastShadow](ue_ue.StaticMeshComponent.md#setcastshadow)

#### Defined in

[ue/ue.d.ts:12712](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12712)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetCenterOfMass](ue_ue.StaticMeshComponent.md#setcenterofmass)

#### Defined in

[ue/ue.d.ts:12713](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12713)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetCollisionEnabled](ue_ue.StaticMeshComponent.md#setcollisionenabled)

#### Defined in

[ue/ue.d.ts:12714](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12714)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetCollisionObjectType](ue_ue.StaticMeshComponent.md#setcollisionobjecttype)

#### Defined in

[ue/ue.d.ts:12715](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12715)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetCollisionProfileName](ue_ue.StaticMeshComponent.md#setcollisionprofilename)

#### Defined in

[ue/ue.d.ts:12716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12716)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetCollisionResponseToAllChannels](ue_ue.StaticMeshComponent.md#setcollisionresponsetoallchannels)

#### Defined in

[ue/ue.d.ts:12717](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12717)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetCollisionResponseToChannel](ue_ue.StaticMeshComponent.md#setcollisionresponsetochannel)

#### Defined in

[ue/ue.d.ts:12718](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12718)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetComponentTickEnabled](ue_ue.StaticMeshComponent.md#setcomponenttickenabled)

#### Defined in

[ue/ue.d.ts:326](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L326)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetComponentTickInterval](ue_ue.StaticMeshComponent.md#setcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L327)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetConstraintMode](ue_ue.StaticMeshComponent.md#setconstraintmode)

#### Defined in

[ue/ue.d.ts:12719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12719)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetCullDistance](ue_ue.StaticMeshComponent.md#setculldistance)

#### Defined in

[ue/ue.d.ts:12720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12720)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetCustomDepthStencilValue](ue_ue.StaticMeshComponent.md#setcustomdepthstencilvalue)

#### Defined in

[ue/ue.d.ts:12721](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12721)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetCustomDepthStencilWriteMask](ue_ue.StaticMeshComponent.md#setcustomdepthstencilwritemask)

#### Defined in

[ue/ue.d.ts:12722](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12722)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetCustomPrimitiveDataFloat](ue_ue.StaticMeshComponent.md#setcustomprimitivedatafloat)

#### Defined in

[ue/ue.d.ts:12723](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12723)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetCustomPrimitiveDataVector2](ue_ue.StaticMeshComponent.md#setcustomprimitivedatavector2)

#### Defined in

[ue/ue.d.ts:12724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12724)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetCustomPrimitiveDataVector3](ue_ue.StaticMeshComponent.md#setcustomprimitivedatavector3)

#### Defined in

[ue/ue.d.ts:12725](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12725)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetCustomPrimitiveDataVector4](ue_ue.StaticMeshComponent.md#setcustomprimitivedatavector4)

#### Defined in

[ue/ue.d.ts:12726](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12726)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetDistanceFieldSelfShadowBias](ue_ue.StaticMeshComponent.md#setdistancefieldselfshadowbias)

#### Defined in

[ue/ue.d.ts:10625](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10625)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetEnableGravity](ue_ue.StaticMeshComponent.md#setenablegravity)

#### Defined in

[ue/ue.d.ts:12727](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12727)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetExcludeFromLightAttachmentGroup](ue_ue.StaticMeshComponent.md#setexcludefromlightattachmentgroup)

#### Defined in

[ue/ue.d.ts:12728](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12728)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetForcedLodModel](ue_ue.StaticMeshComponent.md#setforcedlodmodel)

#### Defined in

[ue/ue.d.ts:10626](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10626)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetGenerateOverlapEvents](ue_ue.StaticMeshComponent.md#setgenerateoverlapevents)

#### Defined in

[ue/ue.d.ts:12729](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12729)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetHiddenInGame](ue_ue.StaticMeshComponent.md#sethiddeningame)

#### Defined in

[ue/ue.d.ts:12948](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12948)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetIsReplicated](ue_ue.StaticMeshComponent.md#setisreplicated)

#### Defined in

[ue/ue.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L328)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetLightAttachmentsAsGroup](ue_ue.StaticMeshComponent.md#setlightattachmentsasgroup)

#### Defined in

[ue/ue.d.ts:12730](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12730)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetLinearDamping](ue_ue.StaticMeshComponent.md#setlineardamping)

#### Defined in

[ue/ue.d.ts:12731](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12731)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetMassOverrideInKg](ue_ue.StaticMeshComponent.md#setmassoverrideinkg)

#### Defined in

[ue/ue.d.ts:12732](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12732)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetMassScale](ue_ue.StaticMeshComponent.md#setmassscale)

#### Defined in

[ue/ue.d.ts:12733](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12733)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetMaterial](ue_ue.StaticMeshComponent.md#setmaterial)

#### Defined in

[ue/ue.d.ts:12734](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12734)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetMaterialByName](ue_ue.StaticMeshComponent.md#setmaterialbyname)

#### Defined in

[ue/ue.d.ts:12735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12735)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetMobility](ue_ue.StaticMeshComponent.md#setmobility)

#### Defined in

[ue/ue.d.ts:12949](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12949)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetNotifyRigidBodyCollision](ue_ue.StaticMeshComponent.md#setnotifyrigidbodycollision)

#### Defined in

[ue/ue.d.ts:12736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12736)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetOnlyOwnerSee](ue_ue.StaticMeshComponent.md#setonlyownersee)

#### Defined in

[ue/ue.d.ts:12737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12737)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetOwnerNoSee](ue_ue.StaticMeshComponent.md#setownernosee)

#### Defined in

[ue/ue.d.ts:12738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12738)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetPhysMaterialOverride](ue_ue.StaticMeshComponent.md#setphysmaterialoverride)

#### Defined in

[ue/ue.d.ts:12746](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12746)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetPhysicsAngularVelocity](ue_ue.StaticMeshComponent.md#setphysicsangularvelocity)

#### Defined in

[ue/ue.d.ts:12739](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12739)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetPhysicsAngularVelocityInDegrees](ue_ue.StaticMeshComponent.md#setphysicsangularvelocityindegrees)

#### Defined in

[ue/ue.d.ts:12740](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12740)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetPhysicsAngularVelocityInRadians](ue_ue.StaticMeshComponent.md#setphysicsangularvelocityinradians)

#### Defined in

[ue/ue.d.ts:12741](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12741)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetPhysicsLinearVelocity](ue_ue.StaticMeshComponent.md#setphysicslinearvelocity)

#### Defined in

[ue/ue.d.ts:12742](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12742)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetPhysicsMaxAngularVelocity](ue_ue.StaticMeshComponent.md#setphysicsmaxangularvelocity)

#### Defined in

[ue/ue.d.ts:12743](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12743)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetPhysicsMaxAngularVelocityInDegrees](ue_ue.StaticMeshComponent.md#setphysicsmaxangularvelocityindegrees)

#### Defined in

[ue/ue.d.ts:12744](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12744)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetPhysicsMaxAngularVelocityInRadians](ue_ue.StaticMeshComponent.md#setphysicsmaxangularvelocityinradians)

#### Defined in

[ue/ue.d.ts:12745](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12745)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetReceivesDecals](ue_ue.StaticMeshComponent.md#setreceivesdecals)

#### Defined in

[ue/ue.d.ts:12747](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12747)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetRelativeScale3D](ue_ue.StaticMeshComponent.md#setrelativescale3d)

#### Defined in

[ue/ue.d.ts:12950](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12950)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetRenderCustomDepth](ue_ue.StaticMeshComponent.md#setrendercustomdepth)

#### Defined in

[ue/ue.d.ts:12748](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12748)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetRenderInMainPass](ue_ue.StaticMeshComponent.md#setrenderinmainpass)

#### Defined in

[ue/ue.d.ts:12749](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12749)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetReverseCulling](ue_ue.StaticMeshComponent.md#setreverseculling)

#### Defined in

[ue/ue.d.ts:10627](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10627)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetScalarParameterValueOnMaterials](ue_ue.StaticMeshComponent.md#setscalarparametervalueonmaterials)

#### Defined in

[ue/ue.d.ts:2303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2303)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.StaticMeshComponent.md#setshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12951](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12951)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetSimulatePhysics](ue_ue.StaticMeshComponent.md#setsimulatephysics)

#### Defined in

[ue/ue.d.ts:12750](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12750)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetSingleSampleShadowFromStationaryLights](ue_ue.StaticMeshComponent.md#setsinglesampleshadowfromstationarylights)

#### Defined in

[ue/ue.d.ts:12751](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12751)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetStaticMesh](ue_ue.StaticMeshComponent.md#setstaticmesh)

#### Defined in

[ue/ue.d.ts:10628](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10628)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetTickGroup](ue_ue.StaticMeshComponent.md#settickgroup)

#### Defined in

[ue/ue.d.ts:330](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L330)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetTickableWhenPaused](ue_ue.StaticMeshComponent.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L329)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetTranslucentSortPriority](ue_ue.StaticMeshComponent.md#settranslucentsortpriority)

#### Defined in

[ue/ue.d.ts:12752](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12752)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetUseCCD](ue_ue.StaticMeshComponent.md#setuseccd)

#### Defined in

[ue/ue.d.ts:12753](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12753)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetVectorParameterValueOnMaterials](ue_ue.StaticMeshComponent.md#setvectorparametervalueonmaterials)

#### Defined in

[ue/ue.d.ts:2304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2304)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetVisibility](ue_ue.StaticMeshComponent.md#setvisibility)

#### Defined in

[ue/ue.d.ts:12953](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12953)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetWalkableSlopeOverride](ue_ue.StaticMeshComponent.md#setwalkableslopeoverride)

#### Defined in

[ue/ue.d.ts:12754](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12754)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetWorldScale3D](ue_ue.StaticMeshComponent.md#setworldscale3d)

#### Defined in

[ue/ue.d.ts:12954](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12954)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SetupAttachment](ue_ue.StaticMeshComponent.md#setupattachment)

#### Defined in

[ue/ue.d.ts:12952](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12952)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SnapTo](ue_ue.StaticMeshComponent.md#snapto)

#### Defined in

[ue/ue.d.ts:12955](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12955)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ToggleActive](ue_ue.StaticMeshComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L331)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ToggleVisibility](ue_ue.StaticMeshComponent.md#togglevisibility)

#### Defined in

[ue/ue.d.ts:12956](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12956)

___

### WakeAllRigidBodies

▸ **WakeAllRigidBodies**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[WakeAllRigidBodies](ue_ue.StaticMeshComponent.md#wakeallrigidbodies)

#### Defined in

[ue/ue.d.ts:12755](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12755)

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

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[WakeRigidBody](ue_ue.StaticMeshComponent.md#wakerigidbody)

#### Defined in

[ue/ue.d.ts:12756](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12756)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GizmoHandleMeshComponent`](ue_ue.GizmoHandleMeshComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GizmoHandleMeshComponent`](ue_ue.GizmoHandleMeshComponent.md)

#### Overrides

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[Find](ue_ue.StaticMeshComponent.md#find)

#### Defined in

[ue/ue.d.ts:38056](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38056)

___

### Load

▸ `Static` **Load**(`InName`): [`GizmoHandleMeshComponent`](ue_ue.GizmoHandleMeshComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GizmoHandleMeshComponent`](ue_ue.GizmoHandleMeshComponent.md)

#### Overrides

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[Load](ue_ue.StaticMeshComponent.md#load)

#### Defined in

[ue/ue.d.ts:38057](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38057)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[StaticClass](ue_ue.StaticMeshComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:38055](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38055)
