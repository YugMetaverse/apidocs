[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ControlPointMeshComponent

# Class: ControlPointMeshComponent

[ue/ue](../modules/ue_ue.md).ControlPointMeshComponent

## Hierarchy

- [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

  ↳ **`ControlPointMeshComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.ControlPointMeshComponent.md#constructor)

### Properties

- [AlwaysLoadOnClient](ue_ue.ControlPointMeshComponent.md#alwaysloadonclient)
- [AlwaysLoadOnServer](ue_ue.ControlPointMeshComponent.md#alwaysloadonserver)
- [AssetUserData](ue_ue.ControlPointMeshComponent.md#assetuserdata)
- [AttachChildren](ue_ue.ControlPointMeshComponent.md#attachchildren)
- [AttachParent](ue_ue.ControlPointMeshComponent.md#attachparent)
- [AttachSocketName](ue_ue.ControlPointMeshComponent.md#attachsocketname)
- [BodyInstance](ue_ue.ControlPointMeshComponent.md#bodyinstance)
- [BoundsScale](ue_ue.ControlPointMeshComponent.md#boundsscale)
- [CachedMaxDrawDistance](ue_ue.ControlPointMeshComponent.md#cachedmaxdrawdistance)
- [CanBeCharacterBase](ue_ue.ControlPointMeshComponent.md#canbecharacterbase)
- [CanCharacterStepUpOn](ue_ue.ControlPointMeshComponent.md#cancharacterstepupon)
- [CastShadow](ue_ue.ControlPointMeshComponent.md#castshadow)
- [ClientAttachedChildren](ue_ue.ControlPointMeshComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.ControlPointMeshComponent.md#componenttags)
- [ComponentVelocity](ue_ue.ControlPointMeshComponent.md#componentvelocity)
- [CreationMethod](ue_ue.ControlPointMeshComponent.md#creationmethod)
- [CustomDepthStencilValue](ue_ue.ControlPointMeshComponent.md#customdepthstencilvalue)
- [CustomDepthStencilWriteMask](ue_ue.ControlPointMeshComponent.md#customdepthstencilwritemask)
- [CustomPrimitiveData](ue_ue.ControlPointMeshComponent.md#customprimitivedata)
- [DepthPriorityGroup](ue_ue.ControlPointMeshComponent.md#depthprioritygroup)
- [DetailMode](ue_ue.ControlPointMeshComponent.md#detailmode)
- [DistanceFieldIndirectShadowMinVisibility](ue_ue.ControlPointMeshComponent.md#distancefieldindirectshadowminvisibility)
- [DistanceFieldSelfShadowBias](ue_ue.ControlPointMeshComponent.md#distancefieldselfshadowbias)
- [ExcludeForSpecificHLODLevels](ue_ue.ControlPointMeshComponent.md#excludeforspecifichlodlevels)
- [ForcedLodModel](ue_ue.ControlPointMeshComponent.md#forcedlodmodel)
- [IndirectLightingCacheQuality](ue_ue.ControlPointMeshComponent.md#indirectlightingcachequality)
- [IrrelevantLights](ue_ue.ControlPointMeshComponent.md#irrelevantlights)
- [LDMaxDrawDistance](ue_ue.ControlPointMeshComponent.md#ldmaxdrawdistance)
- [LODData](ue_ue.ControlPointMeshComponent.md#loddata)
- [LODParentPrimitive](ue_ue.ControlPointMeshComponent.md#lodparentprimitive)
- [LightingChannels](ue_ue.ControlPointMeshComponent.md#lightingchannels)
- [LightmapType](ue_ue.ControlPointMeshComponent.md#lightmaptype)
- [LightmassSettings](ue_ue.ControlPointMeshComponent.md#lightmasssettings)
- [LpvBiasMultiplier](ue_ue.ControlPointMeshComponent.md#lpvbiasmultiplier)
- [MaterialIndexPreview](ue_ue.ControlPointMeshComponent.md#materialindexpreview)
- [MaterialStreamingRelativeBoxes](ue_ue.ControlPointMeshComponent.md#materialstreamingrelativeboxes)
- [MinDrawDistance](ue_ue.ControlPointMeshComponent.md#mindrawdistance)
- [MinLOD](ue_ue.ControlPointMeshComponent.md#minlod)
- [Mobility](ue_ue.ControlPointMeshComponent.md#mobility)
- [MoveIgnoreActors](ue_ue.ControlPointMeshComponent.md#moveignoreactors)
- [MoveIgnoreComponents](ue_ue.ControlPointMeshComponent.md#moveignorecomponents)
- [OnBeginCursorOver](ue_ue.ControlPointMeshComponent.md#onbegincursorover)
- [OnClicked](ue_ue.ControlPointMeshComponent.md#onclicked)
- [OnComponentActivated](ue_ue.ControlPointMeshComponent.md#oncomponentactivated)
- [OnComponentBeginOverlap](ue_ue.ControlPointMeshComponent.md#oncomponentbeginoverlap)
- [OnComponentDeactivated](ue_ue.ControlPointMeshComponent.md#oncomponentdeactivated)
- [OnComponentEndOverlap](ue_ue.ControlPointMeshComponent.md#oncomponentendoverlap)
- [OnComponentHit](ue_ue.ControlPointMeshComponent.md#oncomponenthit)
- [OnComponentSleep](ue_ue.ControlPointMeshComponent.md#oncomponentsleep)
- [OnComponentWake](ue_ue.ControlPointMeshComponent.md#oncomponentwake)
- [OnEndCursorOver](ue_ue.ControlPointMeshComponent.md#onendcursorover)
- [OnInputTouchBegin](ue_ue.ControlPointMeshComponent.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.ControlPointMeshComponent.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.ControlPointMeshComponent.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.ControlPointMeshComponent.md#oninputtouchleave)
- [OnReleased](ue_ue.ControlPointMeshComponent.md#onreleased)
- [OverriddenLightMapRes](ue_ue.ControlPointMeshComponent.md#overriddenlightmapres)
- [OverrideMaterials](ue_ue.ControlPointMeshComponent.md#overridematerials)
- [PhysicsVolume](ue_ue.ControlPointMeshComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.ControlPointMeshComponent.md#physicsvolumechangeddelegate)
- [PreviousLODLevel](ue_ue.ControlPointMeshComponent.md#previouslodlevel)
- [PrimaryComponentTick](ue_ue.ControlPointMeshComponent.md#primarycomponenttick)
- [RelativeLocation](ue_ue.ControlPointMeshComponent.md#relativelocation)
- [RelativeRotation](ue_ue.ControlPointMeshComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.ControlPointMeshComponent.md#relativescale3d)
- [RuntimeVirtualTextures](ue_ue.ControlPointMeshComponent.md#runtimevirtualtextures)
- [SectionIndexPreview](ue_ue.ControlPointMeshComponent.md#sectionindexpreview)
- [SelectedEditorMaterial](ue_ue.ControlPointMeshComponent.md#selectededitormaterial)
- [SelectedEditorSection](ue_ue.ControlPointMeshComponent.md#selectededitorsection)
- [StaticMesh](ue_ue.ControlPointMeshComponent.md#staticmesh)
- [StaticMeshDerivedDataKey](ue_ue.ControlPointMeshComponent.md#staticmeshderiveddatakey)
- [StaticMeshImportVersion](ue_ue.ControlPointMeshComponent.md#staticmeshimportversion)
- [StreamingDistanceMultiplier](ue_ue.ControlPointMeshComponent.md#streamingdistancemultiplier)
- [StreamingTextureData](ue_ue.ControlPointMeshComponent.md#streamingtexturedata)
- [SubDivisionStepSize](ue_ue.ControlPointMeshComponent.md#subdivisionstepsize)
- [TranslucencySortPriority](ue_ue.ControlPointMeshComponent.md#translucencysortpriority)
- [UCSModifiedProperties](ue_ue.ControlPointMeshComponent.md#ucsmodifiedproperties)
- [ViewOwnerDepthPriorityGroup](ue_ue.ControlPointMeshComponent.md#viewownerdepthprioritygroup)
- [VirtualTextureCullMips](ue_ue.ControlPointMeshComponent.md#virtualtexturecullmips)
- [VirtualTextureLodBias](ue_ue.ControlPointMeshComponent.md#virtualtexturelodbias)
- [VirtualTextureMainPassMaxDrawDistance](ue_ue.ControlPointMeshComponent.md#virtualtexturemainpassmaxdrawdistance)
- [VirtualTextureMinCoverage](ue_ue.ControlPointMeshComponent.md#virtualtexturemincoverage)
- [VirtualTextureRenderPassType](ue_ue.ControlPointMeshComponent.md#virtualtexturerenderpasstype)
- [VisibilityId](ue_ue.ControlPointMeshComponent.md#visibilityid)
- [WireframeColorOverride](ue_ue.ControlPointMeshComponent.md#wireframecoloroverride)
- [\_\_tid\_ActorComponent\_\_](ue_ue.ControlPointMeshComponent.md#__tid_actorcomponent__)
- [\_\_tid\_ControlPointMeshComponent\_\_](ue_ue.ControlPointMeshComponent.md#__tid_controlpointmeshcomponent__)
- [\_\_tid\_MeshComponent\_\_](ue_ue.ControlPointMeshComponent.md#__tid_meshcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.ControlPointMeshComponent.md#__tid_object__)
- [\_\_tid\_PrimitiveComponent\_\_](ue_ue.ControlPointMeshComponent.md#__tid_primitivecomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.ControlPointMeshComponent.md#__tid_scenecomponent__)
- [\_\_tid\_StaticMeshComponent\_\_](ue_ue.ControlPointMeshComponent.md#__tid_staticmeshcomponent__)
- [bAbsoluteLocation](ue_ue.ControlPointMeshComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.ControlPointMeshComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.ControlPointMeshComponent.md#babsolutescale)
- [bAffectDistanceFieldLighting](ue_ue.ControlPointMeshComponent.md#baffectdistancefieldlighting)
- [bAffectDynamicIndirectLighting](ue_ue.ControlPointMeshComponent.md#baffectdynamicindirectlighting)
- [bAllowCullDistanceVolume](ue_ue.ControlPointMeshComponent.md#ballowculldistancevolume)
- [bAlwaysCreatePhysicsState](ue_ue.ControlPointMeshComponent.md#balwayscreatephysicsstate)
- [bApplyImpulseOnDamage](ue_ue.ControlPointMeshComponent.md#bapplyimpulseondamage)
- [bAutoActivate](ue_ue.ControlPointMeshComponent.md#bautoactivate)
- [bBatchImpostersAsInstances](ue_ue.ControlPointMeshComponent.md#bbatchimpostersasinstances)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.ControlPointMeshComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.ControlPointMeshComponent.md#bcaneveraffectnavigation)
- [bCastCinematicShadow](ue_ue.ControlPointMeshComponent.md#bcastcinematicshadow)
- [bCastDistanceFieldIndirectShadow](ue_ue.ControlPointMeshComponent.md#bcastdistancefieldindirectshadow)
- [bCastDynamicShadow](ue_ue.ControlPointMeshComponent.md#bcastdynamicshadow)
- [bCastFarShadow](ue_ue.ControlPointMeshComponent.md#bcastfarshadow)
- [bCastHiddenShadow](ue_ue.ControlPointMeshComponent.md#bcasthiddenshadow)
- [bCastInsetShadow](ue_ue.ControlPointMeshComponent.md#bcastinsetshadow)
- [bCastShadowAsTwoSided](ue_ue.ControlPointMeshComponent.md#bcastshadowastwosided)
- [bCastStaticShadow](ue_ue.ControlPointMeshComponent.md#bcaststaticshadow)
- [bCastVolumetricTranslucentShadow](ue_ue.ControlPointMeshComponent.md#bcastvolumetrictranslucentshadow)
- [bComponentToWorldUpdated](ue_ue.ControlPointMeshComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.ControlPointMeshComponent.md#bcreatedbyconstructionscript)
- [bCustomOverrideVertexColorPerLOD](ue_ue.ControlPointMeshComponent.md#bcustomoverridevertexcolorperlod)
- [bDisallowMeshPaintPerInstance](ue_ue.ControlPointMeshComponent.md#bdisallowmeshpaintperinstance)
- [bDisplayVertexColors](ue_ue.ControlPointMeshComponent.md#bdisplayvertexcolors)
- [bEditableWhenInherited](ue_ue.ControlPointMeshComponent.md#beditablewheninherited)
- [bEnableAutoLODGeneration](ue_ue.ControlPointMeshComponent.md#benableautolodgeneration)
- [bEnableMaterialParameterCaching](ue_ue.ControlPointMeshComponent.md#benablematerialparametercaching)
- [bEvaluateWorldPositionOffset](ue_ue.ControlPointMeshComponent.md#bevaluateworldpositionoffset)
- [bExcludeFromLightAttachmentGroup](ue_ue.ControlPointMeshComponent.md#bexcludefromlightattachmentgroup)
- [bForceMipStreaming](ue_ue.ControlPointMeshComponent.md#bforcemipstreaming)
- [bForceNavigationObstacle](ue_ue.ControlPointMeshComponent.md#bforcenavigationobstacle)
- [bGenerateOverlapEvents](ue_ue.ControlPointMeshComponent.md#bgenerateoverlapevents)
- [bHasCustomNavigableGeometry](ue_ue.ControlPointMeshComponent.md#bhascustomnavigablegeometry)
- [bHasMotionBlurVelocityMeshes](ue_ue.ControlPointMeshComponent.md#bhasmotionblurvelocitymeshes)
- [bHasPerInstanceHitProxies](ue_ue.ControlPointMeshComponent.md#bhasperinstancehitproxies)
- [bHiddenInGame](ue_ue.ControlPointMeshComponent.md#bhiddeningame)
- [bIgnoreInstanceForTextureStreaming](ue_ue.ControlPointMeshComponent.md#bignoreinstancefortexturestreaming)
- [bIgnoreRadialForce](ue_ue.ControlPointMeshComponent.md#bignoreradialforce)
- [bIgnoreRadialImpulse](ue_ue.ControlPointMeshComponent.md#bignoreradialimpulse)
- [bInstanceComponent](ue_ue.ControlPointMeshComponent.md#binstancecomponent)
- [bIsActive](ue_ue.ControlPointMeshComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.ControlPointMeshComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.ControlPointMeshComponent.md#bisvisualizationcomponent)
- [bLightAsIfStatic](ue_ue.ControlPointMeshComponent.md#blightasifstatic)
- [bLightAttachmentsAsGroup](ue_ue.ControlPointMeshComponent.md#blightattachmentsasgroup)
- [bMultiBodyOverlap](ue_ue.ControlPointMeshComponent.md#bmultibodyoverlap)
- [bNetAddressable](ue_ue.ControlPointMeshComponent.md#bnetaddressable)
- [bNeverDistanceCull](ue_ue.ControlPointMeshComponent.md#bneverdistancecull)
- [bOnlyOwnerSee](ue_ue.ControlPointMeshComponent.md#bonlyownersee)
- [bOverrideDistanceFieldSelfShadowBias](ue_ue.ControlPointMeshComponent.md#boverridedistancefieldselfshadowbias)
- [bOverrideLightMapRes](ue_ue.ControlPointMeshComponent.md#boverridelightmapres)
- [bOverrideMinLOD](ue_ue.ControlPointMeshComponent.md#boverrideminlod)
- [bOverrideNavigationExport](ue_ue.ControlPointMeshComponent.md#boverridenavigationexport)
- [bOverrideWireframeColor](ue_ue.ControlPointMeshComponent.md#boverridewireframecolor)
- [bOwnerNoSee](ue_ue.ControlPointMeshComponent.md#bownernosee)
- [bReceiveMobileCSMShadows](ue_ue.ControlPointMeshComponent.md#breceivemobilecsmshadows)
- [bReceivesDecals](ue_ue.ControlPointMeshComponent.md#breceivesdecals)
- [bRenderCustomDepth](ue_ue.ControlPointMeshComponent.md#brendercustomdepth)
- [bRenderInDepthPass](ue_ue.ControlPointMeshComponent.md#brenderindepthpass)
- [bRenderInMainPass](ue_ue.ControlPointMeshComponent.md#brenderinmainpass)
- [bReplicatePhysicsToAutonomousProxy](ue_ue.ControlPointMeshComponent.md#breplicatephysicstoautonomousproxy)
- [bReplicates](ue_ue.ControlPointMeshComponent.md#breplicates)
- [bReturnMaterialOnMove](ue_ue.ControlPointMeshComponent.md#breturnmaterialonmove)
- [bReverseCulling](ue_ue.ControlPointMeshComponent.md#breverseculling)
- [bSelectable](ue_ue.ControlPointMeshComponent.md#bselectable)
- [bSelected](ue_ue.ControlPointMeshComponent.md#bselected)
- [bSelfShadowOnly](ue_ue.ControlPointMeshComponent.md#bselfshadowonly)
- [bShouldBeAttached](ue_ue.ControlPointMeshComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.ControlPointMeshComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.ControlPointMeshComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.ControlPointMeshComponent.md#bshouldupdatephysicsvolume)
- [bSingleSampleShadowFromStationaryLights](ue_ue.ControlPointMeshComponent.md#bsinglesampleshadowfromstationarylights)
- [bTraceComplexOnMove](ue_ue.ControlPointMeshComponent.md#btracecomplexonmove)
- [bTreatAsBackgroundForOcclusion](ue_ue.ControlPointMeshComponent.md#btreatasbackgroundforocclusion)
- [bUseAsOccluder](ue_ue.ControlPointMeshComponent.md#buseasoccluder)
- [bUseAttachParentBound](ue_ue.ControlPointMeshComponent.md#buseattachparentbound)
- [bUseDefaultCollision](ue_ue.ControlPointMeshComponent.md#busedefaultcollision)
- [bUseEditorCompositing](ue_ue.ControlPointMeshComponent.md#buseeditorcompositing)
- [bUseMaxLODAsImposter](ue_ue.ControlPointMeshComponent.md#busemaxlodasimposter)
- [bUseSubDivisions](ue_ue.ControlPointMeshComponent.md#busesubdivisions)
- [bUseViewOwnerDepthPriorityGroup](ue_ue.ControlPointMeshComponent.md#buseviewownerdepthprioritygroup)
- [bVisible](ue_ue.ControlPointMeshComponent.md#bvisible)
- [bVisibleInRayTracing](ue_ue.ControlPointMeshComponent.md#bvisibleinraytracing)
- [bVisibleInReflectionCaptures](ue_ue.ControlPointMeshComponent.md#bvisibleinreflectioncaptures)
- [bVisualizeComponent](ue_ue.ControlPointMeshComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.ControlPointMeshComponent.md#activate)
- [AddAngularImpulse](ue_ue.ControlPointMeshComponent.md#addangularimpulse)
- [AddAngularImpulseInDegrees](ue_ue.ControlPointMeshComponent.md#addangularimpulseindegrees)
- [AddAngularImpulseInRadians](ue_ue.ControlPointMeshComponent.md#addangularimpulseinradians)
- [AddForce](ue_ue.ControlPointMeshComponent.md#addforce)
- [AddForceAtLocation](ue_ue.ControlPointMeshComponent.md#addforceatlocation)
- [AddForceAtLocationLocal](ue_ue.ControlPointMeshComponent.md#addforceatlocationlocal)
- [AddImpulse](ue_ue.ControlPointMeshComponent.md#addimpulse)
- [AddImpulseAtLocation](ue_ue.ControlPointMeshComponent.md#addimpulseatlocation)
- [AddRadialForce](ue_ue.ControlPointMeshComponent.md#addradialforce)
- [AddRadialImpulse](ue_ue.ControlPointMeshComponent.md#addradialimpulse)
- [AddTickPrerequisiteActor](ue_ue.ControlPointMeshComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.ControlPointMeshComponent.md#addtickprerequisitecomponent)
- [AddTorque](ue_ue.ControlPointMeshComponent.md#addtorque)
- [AddTorqueInDegrees](ue_ue.ControlPointMeshComponent.md#addtorqueindegrees)
- [AddTorqueInRadians](ue_ue.ControlPointMeshComponent.md#addtorqueinradians)
- [CanCharacterStepUp](ue_ue.ControlPointMeshComponent.md#cancharacterstepup)
- [ClearMoveIgnoreActors](ue_ue.ControlPointMeshComponent.md#clearmoveignoreactors)
- [ClearMoveIgnoreComponents](ue_ue.ControlPointMeshComponent.md#clearmoveignorecomponents)
- [ComponentHasTag](ue_ue.ControlPointMeshComponent.md#componenthastag)
- [CopyArrayOfMoveIgnoreActors](ue_ue.ControlPointMeshComponent.md#copyarrayofmoveignoreactors)
- [CopyArrayOfMoveIgnoreComponents](ue_ue.ControlPointMeshComponent.md#copyarrayofmoveignorecomponents)
- [CreateAndSetMaterialInstanceDynamic](ue_ue.ControlPointMeshComponent.md#createandsetmaterialinstancedynamic)
- [CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.ControlPointMeshComponent.md#createandsetmaterialinstancedynamicfrommaterial)
- [CreateDefaultSubobject](ue_ue.ControlPointMeshComponent.md#createdefaultsubobject)
- [CreateDynamicMaterialInstance](ue_ue.ControlPointMeshComponent.md#createdynamicmaterialinstance)
- [Deactivate](ue_ue.ControlPointMeshComponent.md#deactivate)
- [DetachFromParent](ue_ue.ControlPointMeshComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.ControlPointMeshComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.ControlPointMeshComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.ControlPointMeshComponent.md#getallsocketnames)
- [GetAngularDamping](ue_ue.ControlPointMeshComponent.md#getangulardamping)
- [GetAttachParent](ue_ue.ControlPointMeshComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.ControlPointMeshComponent.md#getattachsocketname)
- [GetCenterOfMass](ue_ue.ControlPointMeshComponent.md#getcenterofmass)
- [GetChildComponent](ue_ue.ControlPointMeshComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.ControlPointMeshComponent.md#getchildrencomponents)
- [GetClass](ue_ue.ControlPointMeshComponent.md#getclass)
- [GetClosestPointOnCollision](ue_ue.ControlPointMeshComponent.md#getclosestpointoncollision)
- [GetCollisionEnabled](ue_ue.ControlPointMeshComponent.md#getcollisionenabled)
- [GetCollisionObjectType](ue_ue.ControlPointMeshComponent.md#getcollisionobjecttype)
- [GetCollisionProfileName](ue_ue.ControlPointMeshComponent.md#getcollisionprofilename)
- [GetCollisionResponseToChannel](ue_ue.ControlPointMeshComponent.md#getcollisionresponsetochannel)
- [GetComponentTickInterval](ue_ue.ControlPointMeshComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.ControlPointMeshComponent.md#getcomponentvelocity)
- [GetForwardVector](ue_ue.ControlPointMeshComponent.md#getforwardvector)
- [GetGenerateOverlapEvents](ue_ue.ControlPointMeshComponent.md#getgenerateoverlapevents)
- [GetInertiaTensor](ue_ue.ControlPointMeshComponent.md#getinertiatensor)
- [GetLinearDamping](ue_ue.ControlPointMeshComponent.md#getlineardamping)
- [GetLocalBounds](ue_ue.ControlPointMeshComponent.md#getlocalbounds)
- [GetMass](ue_ue.ControlPointMeshComponent.md#getmass)
- [GetMassScale](ue_ue.ControlPointMeshComponent.md#getmassscale)
- [GetMaterial](ue_ue.ControlPointMeshComponent.md#getmaterial)
- [GetMaterialFromCollisionFaceIndex](ue_ue.ControlPointMeshComponent.md#getmaterialfromcollisionfaceindex)
- [GetMaterialIndex](ue_ue.ControlPointMeshComponent.md#getmaterialindex)
- [GetMaterialSlotNames](ue_ue.ControlPointMeshComponent.md#getmaterialslotnames)
- [GetMaterials](ue_ue.ControlPointMeshComponent.md#getmaterials)
- [GetName](ue_ue.ControlPointMeshComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.ControlPointMeshComponent.md#getnumchildrencomponents)
- [GetNumMaterials](ue_ue.ControlPointMeshComponent.md#getnummaterials)
- [GetOuter](ue_ue.ControlPointMeshComponent.md#getouter)
- [GetOverlappingActors](ue_ue.ControlPointMeshComponent.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.ControlPointMeshComponent.md#getoverlappingcomponents)
- [GetOwner](ue_ue.ControlPointMeshComponent.md#getowner)
- [GetParentComponents](ue_ue.ControlPointMeshComponent.md#getparentcomponents)
- [GetPhysicsAngularVelocity](ue_ue.ControlPointMeshComponent.md#getphysicsangularvelocity)
- [GetPhysicsAngularVelocityInDegrees](ue_ue.ControlPointMeshComponent.md#getphysicsangularvelocityindegrees)
- [GetPhysicsAngularVelocityInRadians](ue_ue.ControlPointMeshComponent.md#getphysicsangularvelocityinradians)
- [GetPhysicsLinearVelocity](ue_ue.ControlPointMeshComponent.md#getphysicslinearvelocity)
- [GetPhysicsLinearVelocityAtPoint](ue_ue.ControlPointMeshComponent.md#getphysicslinearvelocityatpoint)
- [GetPhysicsVolume](ue_ue.ControlPointMeshComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.ControlPointMeshComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.ControlPointMeshComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.ControlPointMeshComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.ControlPointMeshComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.ControlPointMeshComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.ControlPointMeshComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.ControlPointMeshComponent.md#getsockettransform)
- [GetUpVector](ue_ue.ControlPointMeshComponent.md#getupvector)
- [GetWalkableSlopeOverride](ue_ue.ControlPointMeshComponent.md#getwalkableslopeoverride)
- [GetWorld](ue_ue.ControlPointMeshComponent.md#getworld)
- [IgnoreActorWhenMoving](ue_ue.ControlPointMeshComponent.md#ignoreactorwhenmoving)
- [IgnoreComponentWhenMoving](ue_ue.ControlPointMeshComponent.md#ignorecomponentwhenmoving)
- [IsActive](ue_ue.ControlPointMeshComponent.md#isactive)
- [IsAnyRigidBodyAwake](ue_ue.ControlPointMeshComponent.md#isanyrigidbodyawake)
- [IsAnySimulatingPhysics](ue_ue.ControlPointMeshComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.ControlPointMeshComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.ControlPointMeshComponent.md#iscomponenttickenabled)
- [IsGravityEnabled](ue_ue.ControlPointMeshComponent.md#isgravityenabled)
- [IsMaterialSlotNameValid](ue_ue.ControlPointMeshComponent.md#ismaterialslotnamevalid)
- [IsOverlappingActor](ue_ue.ControlPointMeshComponent.md#isoverlappingactor)
- [IsOverlappingComponent](ue_ue.ControlPointMeshComponent.md#isoverlappingcomponent)
- [IsSimulatingPhysics](ue_ue.ControlPointMeshComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.ControlPointMeshComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.ControlPointMeshComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.ControlPointMeshComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.ControlPointMeshComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.ControlPointMeshComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.ControlPointMeshComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.ControlPointMeshComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.ControlPointMeshComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.ControlPointMeshComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.ControlPointMeshComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.ControlPointMeshComponent.md#k2_attachtocomponent)
- [K2\_BoxOverlapComponent](ue_ue.ControlPointMeshComponent.md#k2_boxoverlapcomponent)
- [K2\_DestroyComponent](ue_ue.ControlPointMeshComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.ControlPointMeshComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.ControlPointMeshComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.ControlPointMeshComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.ControlPointMeshComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.ControlPointMeshComponent.md#k2_getcomponenttoworld)
- [K2\_IsCollisionEnabled](ue_ue.ControlPointMeshComponent.md#k2_iscollisionenabled)
- [K2\_IsPhysicsCollisionEnabled](ue_ue.ControlPointMeshComponent.md#k2_isphysicscollisionenabled)
- [K2\_IsQueryCollisionEnabled](ue_ue.ControlPointMeshComponent.md#k2_isquerycollisionenabled)
- [K2\_LineTraceComponent](ue_ue.ControlPointMeshComponent.md#k2_linetracecomponent)
- [K2\_SetRelativeLocation](ue_ue.ControlPointMeshComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.ControlPointMeshComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.ControlPointMeshComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.ControlPointMeshComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.ControlPointMeshComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.ControlPointMeshComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.ControlPointMeshComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.ControlPointMeshComponent.md#k2_setworldtransform)
- [K2\_SphereOverlapComponent](ue_ue.ControlPointMeshComponent.md#k2_sphereoverlapcomponent)
- [K2\_SphereTraceComponent](ue_ue.ControlPointMeshComponent.md#k2_spheretracecomponent)
- [OnRep\_AttachChildren](ue_ue.ControlPointMeshComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.ControlPointMeshComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.ControlPointMeshComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.ControlPointMeshComponent.md#onrep_isactive)
- [OnRep\_StaticMesh](ue_ue.ControlPointMeshComponent.md#onrep_staticmesh)
- [OnRep\_Transform](ue_ue.ControlPointMeshComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.ControlPointMeshComponent.md#onrep_visibility)
- [PrestreamTextures](ue_ue.ControlPointMeshComponent.md#prestreamtextures)
- [PutRigidBodyToSleep](ue_ue.ControlPointMeshComponent.md#putrigidbodytosleep)
- [ReceiveBeginPlay](ue_ue.ControlPointMeshComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.ControlPointMeshComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.ControlPointMeshComponent.md#receivetick)
- [RegisterComponent](ue_ue.ControlPointMeshComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.ControlPointMeshComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.ControlPointMeshComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.ControlPointMeshComponent.md#resetrelativetransform)
- [ScaleByMomentOfInertia](ue_ue.ControlPointMeshComponent.md#scalebymomentofinertia)
- [SetAbsolute](ue_ue.ControlPointMeshComponent.md#setabsolute)
- [SetActive](ue_ue.ControlPointMeshComponent.md#setactive)
- [SetAllMassScale](ue_ue.ControlPointMeshComponent.md#setallmassscale)
- [SetAllPhysicsAngularVelocityInDegrees](ue_ue.ControlPointMeshComponent.md#setallphysicsangularvelocityindegrees)
- [SetAllPhysicsAngularVelocityInRadians](ue_ue.ControlPointMeshComponent.md#setallphysicsangularvelocityinradians)
- [SetAllPhysicsLinearVelocity](ue_ue.ControlPointMeshComponent.md#setallphysicslinearvelocity)
- [SetAllUseCCD](ue_ue.ControlPointMeshComponent.md#setalluseccd)
- [SetAngularDamping](ue_ue.ControlPointMeshComponent.md#setangulardamping)
- [SetAutoActivate](ue_ue.ControlPointMeshComponent.md#setautoactivate)
- [SetBoundsScale](ue_ue.ControlPointMeshComponent.md#setboundsscale)
- [SetCastInsetShadow](ue_ue.ControlPointMeshComponent.md#setcastinsetshadow)
- [SetCastShadow](ue_ue.ControlPointMeshComponent.md#setcastshadow)
- [SetCenterOfMass](ue_ue.ControlPointMeshComponent.md#setcenterofmass)
- [SetCollisionEnabled](ue_ue.ControlPointMeshComponent.md#setcollisionenabled)
- [SetCollisionObjectType](ue_ue.ControlPointMeshComponent.md#setcollisionobjecttype)
- [SetCollisionProfileName](ue_ue.ControlPointMeshComponent.md#setcollisionprofilename)
- [SetCollisionResponseToAllChannels](ue_ue.ControlPointMeshComponent.md#setcollisionresponsetoallchannels)
- [SetCollisionResponseToChannel](ue_ue.ControlPointMeshComponent.md#setcollisionresponsetochannel)
- [SetComponentTickEnabled](ue_ue.ControlPointMeshComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.ControlPointMeshComponent.md#setcomponenttickinterval)
- [SetConstraintMode](ue_ue.ControlPointMeshComponent.md#setconstraintmode)
- [SetCullDistance](ue_ue.ControlPointMeshComponent.md#setculldistance)
- [SetCustomDepthStencilValue](ue_ue.ControlPointMeshComponent.md#setcustomdepthstencilvalue)
- [SetCustomDepthStencilWriteMask](ue_ue.ControlPointMeshComponent.md#setcustomdepthstencilwritemask)
- [SetCustomPrimitiveDataFloat](ue_ue.ControlPointMeshComponent.md#setcustomprimitivedatafloat)
- [SetCustomPrimitiveDataVector2](ue_ue.ControlPointMeshComponent.md#setcustomprimitivedatavector2)
- [SetCustomPrimitiveDataVector3](ue_ue.ControlPointMeshComponent.md#setcustomprimitivedatavector3)
- [SetCustomPrimitiveDataVector4](ue_ue.ControlPointMeshComponent.md#setcustomprimitivedatavector4)
- [SetDistanceFieldSelfShadowBias](ue_ue.ControlPointMeshComponent.md#setdistancefieldselfshadowbias)
- [SetEnableGravity](ue_ue.ControlPointMeshComponent.md#setenablegravity)
- [SetExcludeFromLightAttachmentGroup](ue_ue.ControlPointMeshComponent.md#setexcludefromlightattachmentgroup)
- [SetForcedLodModel](ue_ue.ControlPointMeshComponent.md#setforcedlodmodel)
- [SetGenerateOverlapEvents](ue_ue.ControlPointMeshComponent.md#setgenerateoverlapevents)
- [SetHiddenInGame](ue_ue.ControlPointMeshComponent.md#sethiddeningame)
- [SetIsReplicated](ue_ue.ControlPointMeshComponent.md#setisreplicated)
- [SetLightAttachmentsAsGroup](ue_ue.ControlPointMeshComponent.md#setlightattachmentsasgroup)
- [SetLinearDamping](ue_ue.ControlPointMeshComponent.md#setlineardamping)
- [SetMassOverrideInKg](ue_ue.ControlPointMeshComponent.md#setmassoverrideinkg)
- [SetMassScale](ue_ue.ControlPointMeshComponent.md#setmassscale)
- [SetMaterial](ue_ue.ControlPointMeshComponent.md#setmaterial)
- [SetMaterialByName](ue_ue.ControlPointMeshComponent.md#setmaterialbyname)
- [SetMobility](ue_ue.ControlPointMeshComponent.md#setmobility)
- [SetNotifyRigidBodyCollision](ue_ue.ControlPointMeshComponent.md#setnotifyrigidbodycollision)
- [SetOnlyOwnerSee](ue_ue.ControlPointMeshComponent.md#setonlyownersee)
- [SetOwnerNoSee](ue_ue.ControlPointMeshComponent.md#setownernosee)
- [SetPhysMaterialOverride](ue_ue.ControlPointMeshComponent.md#setphysmaterialoverride)
- [SetPhysicsAngularVelocity](ue_ue.ControlPointMeshComponent.md#setphysicsangularvelocity)
- [SetPhysicsAngularVelocityInDegrees](ue_ue.ControlPointMeshComponent.md#setphysicsangularvelocityindegrees)
- [SetPhysicsAngularVelocityInRadians](ue_ue.ControlPointMeshComponent.md#setphysicsangularvelocityinradians)
- [SetPhysicsLinearVelocity](ue_ue.ControlPointMeshComponent.md#setphysicslinearvelocity)
- [SetPhysicsMaxAngularVelocity](ue_ue.ControlPointMeshComponent.md#setphysicsmaxangularvelocity)
- [SetPhysicsMaxAngularVelocityInDegrees](ue_ue.ControlPointMeshComponent.md#setphysicsmaxangularvelocityindegrees)
- [SetPhysicsMaxAngularVelocityInRadians](ue_ue.ControlPointMeshComponent.md#setphysicsmaxangularvelocityinradians)
- [SetReceivesDecals](ue_ue.ControlPointMeshComponent.md#setreceivesdecals)
- [SetRelativeScale3D](ue_ue.ControlPointMeshComponent.md#setrelativescale3d)
- [SetRenderCustomDepth](ue_ue.ControlPointMeshComponent.md#setrendercustomdepth)
- [SetRenderInMainPass](ue_ue.ControlPointMeshComponent.md#setrenderinmainpass)
- [SetReverseCulling](ue_ue.ControlPointMeshComponent.md#setreverseculling)
- [SetScalarParameterValueOnMaterials](ue_ue.ControlPointMeshComponent.md#setscalarparametervalueonmaterials)
- [SetShouldUpdatePhysicsVolume](ue_ue.ControlPointMeshComponent.md#setshouldupdatephysicsvolume)
- [SetSimulatePhysics](ue_ue.ControlPointMeshComponent.md#setsimulatephysics)
- [SetSingleSampleShadowFromStationaryLights](ue_ue.ControlPointMeshComponent.md#setsinglesampleshadowfromstationarylights)
- [SetStaticMesh](ue_ue.ControlPointMeshComponent.md#setstaticmesh)
- [SetTickGroup](ue_ue.ControlPointMeshComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.ControlPointMeshComponent.md#settickablewhenpaused)
- [SetTranslucentSortPriority](ue_ue.ControlPointMeshComponent.md#settranslucentsortpriority)
- [SetUseCCD](ue_ue.ControlPointMeshComponent.md#setuseccd)
- [SetVectorParameterValueOnMaterials](ue_ue.ControlPointMeshComponent.md#setvectorparametervalueonmaterials)
- [SetVisibility](ue_ue.ControlPointMeshComponent.md#setvisibility)
- [SetWalkableSlopeOverride](ue_ue.ControlPointMeshComponent.md#setwalkableslopeoverride)
- [SetWorldScale3D](ue_ue.ControlPointMeshComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.ControlPointMeshComponent.md#setupattachment)
- [SnapTo](ue_ue.ControlPointMeshComponent.md#snapto)
- [ToggleActive](ue_ue.ControlPointMeshComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.ControlPointMeshComponent.md#togglevisibility)
- [WakeAllRigidBodies](ue_ue.ControlPointMeshComponent.md#wakeallrigidbodies)
- [WakeRigidBody](ue_ue.ControlPointMeshComponent.md#wakerigidbody)
- [Find](ue_ue.ControlPointMeshComponent.md#find)
- [Load](ue_ue.ControlPointMeshComponent.md#load)
- [StaticClass](ue_ue.ControlPointMeshComponent.md#staticclass)

## Constructors

### constructor

• **new ControlPointMeshComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[constructor](ue_ue.StaticMeshComponent.md#constructor)

## Properties

### AlwaysLoadOnClient

• **AlwaysLoadOnClient**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AlwaysLoadOnClient](ue_ue.StaticMeshComponent.md#alwaysloadonclient)

___

### AlwaysLoadOnServer

• **AlwaysLoadOnServer**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AlwaysLoadOnServer](ue_ue.StaticMeshComponent.md#alwaysloadonserver)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AssetUserData](ue_ue.StaticMeshComponent.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AttachChildren](ue_ue.StaticMeshComponent.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AttachParent](ue_ue.StaticMeshComponent.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[AttachSocketName](ue_ue.StaticMeshComponent.md#attachsocketname)

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[BodyInstance](ue_ue.StaticMeshComponent.md#bodyinstance)

___

### BoundsScale

• **BoundsScale**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[BoundsScale](ue_ue.StaticMeshComponent.md#boundsscale)

___

### CachedMaxDrawDistance

• **CachedMaxDrawDistance**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CachedMaxDrawDistance](ue_ue.StaticMeshComponent.md#cachedmaxdrawdistance)

___

### CanBeCharacterBase

• **CanBeCharacterBase**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CanBeCharacterBase](ue_ue.StaticMeshComponent.md#canbecharacterbase)

___

### CanCharacterStepUpOn

• **CanCharacterStepUpOn**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CanCharacterStepUpOn](ue_ue.StaticMeshComponent.md#cancharacterstepupon)

___

### CastShadow

• **CastShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CastShadow](ue_ue.StaticMeshComponent.md#castshadow)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ClientAttachedChildren](ue_ue.StaticMeshComponent.md#clientattachedchildren)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ComponentTags](ue_ue.StaticMeshComponent.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ComponentVelocity](ue_ue.StaticMeshComponent.md#componentvelocity)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CreationMethod](ue_ue.StaticMeshComponent.md#creationmethod)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CustomDepthStencilValue](ue_ue.StaticMeshComponent.md#customdepthstencilvalue)

___

### CustomDepthStencilWriteMask

• **CustomDepthStencilWriteMask**: [`ERendererStencilMask`](../enums/ue_ue.ERendererStencilMask.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CustomDepthStencilWriteMask](ue_ue.StaticMeshComponent.md#customdepthstencilwritemask)

___

### CustomPrimitiveData

• **CustomPrimitiveData**: [`CustomPrimitiveData`](ue_ue.CustomPrimitiveData.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CustomPrimitiveData](ue_ue.StaticMeshComponent.md#customprimitivedata)

___

### DepthPriorityGroup

• **DepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[DepthPriorityGroup](ue_ue.StaticMeshComponent.md#depthprioritygroup)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[DetailMode](ue_ue.StaticMeshComponent.md#detailmode)

___

### DistanceFieldIndirectShadowMinVisibility

• **DistanceFieldIndirectShadowMinVisibility**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[DistanceFieldIndirectShadowMinVisibility](ue_ue.StaticMeshComponent.md#distancefieldindirectshadowminvisibility)

___

### DistanceFieldSelfShadowBias

• **DistanceFieldSelfShadowBias**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[DistanceFieldSelfShadowBias](ue_ue.StaticMeshComponent.md#distancefieldselfshadowbias)

___

### ExcludeForSpecificHLODLevels

• **ExcludeForSpecificHLODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ExcludeForSpecificHLODLevels](ue_ue.StaticMeshComponent.md#excludeforspecifichlodlevels)

___

### ForcedLodModel

• **ForcedLodModel**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ForcedLodModel](ue_ue.StaticMeshComponent.md#forcedlodmodel)

___

### IndirectLightingCacheQuality

• **IndirectLightingCacheQuality**: [`EIndirectLightingCacheQuality`](../enums/ue_ue.EIndirectLightingCacheQuality.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IndirectLightingCacheQuality](ue_ue.StaticMeshComponent.md#indirectlightingcachequality)

___

### IrrelevantLights

• **IrrelevantLights**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IrrelevantLights](ue_ue.StaticMeshComponent.md#irrelevantlights)

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[LDMaxDrawDistance](ue_ue.StaticMeshComponent.md#ldmaxdrawdistance)

___

### LODData

• **LODData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticMeshComponentLODInfo`](ue_ue.StaticMeshComponentLODInfo.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[LODData](ue_ue.StaticMeshComponent.md#loddata)

___

### LODParentPrimitive

• **LODParentPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[LODParentPrimitive](ue_ue.StaticMeshComponent.md#lodparentprimitive)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[LightingChannels](ue_ue.StaticMeshComponent.md#lightingchannels)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[LightmapType](ue_ue.StaticMeshComponent.md#lightmaptype)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassPrimitiveSettings`](ue_ue.LightmassPrimitiveSettings.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[LightmassSettings](ue_ue.StaticMeshComponent.md#lightmasssettings)

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[LpvBiasMultiplier](ue_ue.StaticMeshComponent.md#lpvbiasmultiplier)

___

### MaterialIndexPreview

• **MaterialIndexPreview**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[MaterialIndexPreview](ue_ue.StaticMeshComponent.md#materialindexpreview)

___

### MaterialStreamingRelativeBoxes

• **MaterialStreamingRelativeBoxes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[MaterialStreamingRelativeBoxes](ue_ue.StaticMeshComponent.md#materialstreamingrelativeboxes)

___

### MinDrawDistance

• **MinDrawDistance**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[MinDrawDistance](ue_ue.StaticMeshComponent.md#mindrawdistance)

___

### MinLOD

• **MinLOD**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[MinLOD](ue_ue.StaticMeshComponent.md#minlod)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[Mobility](ue_ue.StaticMeshComponent.md#mobility)

___

### MoveIgnoreActors

• **MoveIgnoreActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[MoveIgnoreActors](ue_ue.StaticMeshComponent.md#moveignoreactors)

___

### MoveIgnoreComponents

• **MoveIgnoreComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[MoveIgnoreComponents](ue_ue.StaticMeshComponent.md#moveignorecomponents)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnBeginCursorOver](ue_ue.StaticMeshComponent.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnClicked](ue_ue.StaticMeshComponent.md#onclicked)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnComponentActivated](ue_ue.StaticMeshComponent.md#oncomponentactivated)

___

### OnComponentBeginOverlap

• **OnComponentBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`, `bFromSweep`: `boolean`, `SweepResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnComponentBeginOverlap](ue_ue.StaticMeshComponent.md#oncomponentbeginoverlap)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnComponentDeactivated](ue_ue.StaticMeshComponent.md#oncomponentdeactivated)

___

### OnComponentEndOverlap

• **OnComponentEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnComponentEndOverlap](ue_ue.StaticMeshComponent.md#oncomponentendoverlap)

___

### OnComponentHit

• **OnComponentHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`HitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnComponentHit](ue_ue.StaticMeshComponent.md#oncomponenthit)

___

### OnComponentSleep

• **OnComponentSleep**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SleepingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnComponentSleep](ue_ue.StaticMeshComponent.md#oncomponentsleep)

___

### OnComponentWake

• **OnComponentWake**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`WakingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnComponentWake](ue_ue.StaticMeshComponent.md#oncomponentwake)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnEndCursorOver](ue_ue.StaticMeshComponent.md#onendcursorover)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnInputTouchBegin](ue_ue.StaticMeshComponent.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnInputTouchEnd](ue_ue.StaticMeshComponent.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnInputTouchEnter](ue_ue.StaticMeshComponent.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnInputTouchLeave](ue_ue.StaticMeshComponent.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnReleased](ue_ue.StaticMeshComponent.md#onreleased)

___

### OverriddenLightMapRes

• **OverriddenLightMapRes**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OverriddenLightMapRes](ue_ue.StaticMeshComponent.md#overriddenlightmapres)

___

### OverrideMaterials

• **OverrideMaterials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OverrideMaterials](ue_ue.StaticMeshComponent.md#overridematerials)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[PhysicsVolume](ue_ue.StaticMeshComponent.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.StaticMeshComponent.md#physicsvolumechangeddelegate)

___

### PreviousLODLevel

• **PreviousLODLevel**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[PreviousLODLevel](ue_ue.StaticMeshComponent.md#previouslodlevel)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[PrimaryComponentTick](ue_ue.StaticMeshComponent.md#primarycomponenttick)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[RelativeLocation](ue_ue.StaticMeshComponent.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[RelativeRotation](ue_ue.StaticMeshComponent.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[RelativeScale3D](ue_ue.StaticMeshComponent.md#relativescale3d)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[RuntimeVirtualTextures](ue_ue.StaticMeshComponent.md#runtimevirtualtextures)

___

### SectionIndexPreview

• **SectionIndexPreview**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SectionIndexPreview](ue_ue.StaticMeshComponent.md#sectionindexpreview)

___

### SelectedEditorMaterial

• **SelectedEditorMaterial**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SelectedEditorMaterial](ue_ue.StaticMeshComponent.md#selectededitormaterial)

___

### SelectedEditorSection

• **SelectedEditorSection**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SelectedEditorSection](ue_ue.StaticMeshComponent.md#selectededitorsection)

___

### StaticMesh

• **StaticMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[StaticMesh](ue_ue.StaticMeshComponent.md#staticmesh)

___

### StaticMeshDerivedDataKey

• **StaticMeshDerivedDataKey**: `string`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[StaticMeshDerivedDataKey](ue_ue.StaticMeshComponent.md#staticmeshderiveddatakey)

___

### StaticMeshImportVersion

• **StaticMeshImportVersion**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[StaticMeshImportVersion](ue_ue.StaticMeshComponent.md#staticmeshimportversion)

___

### StreamingDistanceMultiplier

• **StreamingDistanceMultiplier**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[StreamingDistanceMultiplier](ue_ue.StaticMeshComponent.md#streamingdistancemultiplier)

___

### StreamingTextureData

• **StreamingTextureData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StreamingTextureBuildInfo`](ue_ue.StreamingTextureBuildInfo.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[StreamingTextureData](ue_ue.StaticMeshComponent.md#streamingtexturedata)

___

### SubDivisionStepSize

• **SubDivisionStepSize**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[SubDivisionStepSize](ue_ue.StaticMeshComponent.md#subdivisionstepsize)

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[TranslucencySortPriority](ue_ue.StaticMeshComponent.md#translucencysortpriority)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[UCSModifiedProperties](ue_ue.StaticMeshComponent.md#ucsmodifiedproperties)

___

### ViewOwnerDepthPriorityGroup

• **ViewOwnerDepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ViewOwnerDepthPriorityGroup](ue_ue.StaticMeshComponent.md#viewownerdepthprioritygroup)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[VirtualTextureCullMips](ue_ue.StaticMeshComponent.md#virtualtexturecullmips)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[VirtualTextureLodBias](ue_ue.StaticMeshComponent.md#virtualtexturelodbias)

___

### VirtualTextureMainPassMaxDrawDistance

• **VirtualTextureMainPassMaxDrawDistance**: `number`

___

### VirtualTextureMinCoverage

• **VirtualTextureMinCoverage**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[VirtualTextureMinCoverage](ue_ue.StaticMeshComponent.md#virtualtexturemincoverage)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[VirtualTextureRenderPassType](ue_ue.StaticMeshComponent.md#virtualtexturerenderpasstype)

___

### VisibilityId

• **VisibilityId**: `number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[VisibilityId](ue_ue.StaticMeshComponent.md#visibilityid)

___

### WireframeColorOverride

• **WireframeColorOverride**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[WireframeColorOverride](ue_ue.StaticMeshComponent.md#wireframecoloroverride)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[__tid_ActorComponent__](ue_ue.StaticMeshComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_ControlPointMeshComponent\_\_

• **\_\_tid\_ControlPointMeshComponent\_\_**: `boolean`

___

### \_\_tid\_MeshComponent\_\_

• **\_\_tid\_MeshComponent\_\_**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[__tid_MeshComponent__](ue_ue.StaticMeshComponent.md#__tid_meshcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[__tid_Object__](ue_ue.StaticMeshComponent.md#__tid_object__)

___

### \_\_tid\_PrimitiveComponent\_\_

• **\_\_tid\_PrimitiveComponent\_\_**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[__tid_PrimitiveComponent__](ue_ue.StaticMeshComponent.md#__tid_primitivecomponent__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[__tid_SceneComponent__](ue_ue.StaticMeshComponent.md#__tid_scenecomponent__)

___

### \_\_tid\_StaticMeshComponent\_\_

• **\_\_tid\_StaticMeshComponent\_\_**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[__tid_StaticMeshComponent__](ue_ue.StaticMeshComponent.md#__tid_staticmeshcomponent__)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bAbsoluteLocation](ue_ue.StaticMeshComponent.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bAbsoluteRotation](ue_ue.StaticMeshComponent.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bAbsoluteScale](ue_ue.StaticMeshComponent.md#babsolutescale)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bAffectDistanceFieldLighting](ue_ue.StaticMeshComponent.md#baffectdistancefieldlighting)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bAffectDynamicIndirectLighting](ue_ue.StaticMeshComponent.md#baffectdynamicindirectlighting)

___

### bAllowCullDistanceVolume

• **bAllowCullDistanceVolume**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bAllowCullDistanceVolume](ue_ue.StaticMeshComponent.md#ballowculldistancevolume)

___

### bAlwaysCreatePhysicsState

• **bAlwaysCreatePhysicsState**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bAlwaysCreatePhysicsState](ue_ue.StaticMeshComponent.md#balwayscreatephysicsstate)

___

### bApplyImpulseOnDamage

• **bApplyImpulseOnDamage**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bApplyImpulseOnDamage](ue_ue.StaticMeshComponent.md#bapplyimpulseondamage)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bAutoActivate](ue_ue.StaticMeshComponent.md#bautoactivate)

___

### bBatchImpostersAsInstances

• **bBatchImpostersAsInstances**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bBatchImpostersAsInstances](ue_ue.StaticMeshComponent.md#bbatchimpostersasinstances)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.StaticMeshComponent.md#bboundschangetriggersstreamingdatarebuild)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCanEverAffectNavigation](ue_ue.StaticMeshComponent.md#bcaneveraffectnavigation)

___

### bCastCinematicShadow

• **bCastCinematicShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastCinematicShadow](ue_ue.StaticMeshComponent.md#bcastcinematicshadow)

___

### bCastDistanceFieldIndirectShadow

• **bCastDistanceFieldIndirectShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastDistanceFieldIndirectShadow](ue_ue.StaticMeshComponent.md#bcastdistancefieldindirectshadow)

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastDynamicShadow](ue_ue.StaticMeshComponent.md#bcastdynamicshadow)

___

### bCastFarShadow

• **bCastFarShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastFarShadow](ue_ue.StaticMeshComponent.md#bcastfarshadow)

___

### bCastHiddenShadow

• **bCastHiddenShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastHiddenShadow](ue_ue.StaticMeshComponent.md#bcasthiddenshadow)

___

### bCastInsetShadow

• **bCastInsetShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastInsetShadow](ue_ue.StaticMeshComponent.md#bcastinsetshadow)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastShadowAsTwoSided](ue_ue.StaticMeshComponent.md#bcastshadowastwosided)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastStaticShadow](ue_ue.StaticMeshComponent.md#bcaststaticshadow)

___

### bCastVolumetricTranslucentShadow

• **bCastVolumetricTranslucentShadow**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCastVolumetricTranslucentShadow](ue_ue.StaticMeshComponent.md#bcastvolumetrictranslucentshadow)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bComponentToWorldUpdated](ue_ue.StaticMeshComponent.md#bcomponenttoworldupdated)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCreatedByConstructionScript](ue_ue.StaticMeshComponent.md#bcreatedbyconstructionscript)

___

### bCustomOverrideVertexColorPerLOD

• **bCustomOverrideVertexColorPerLOD**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bCustomOverrideVertexColorPerLOD](ue_ue.StaticMeshComponent.md#bcustomoverridevertexcolorperlod)

___

### bDisallowMeshPaintPerInstance

• **bDisallowMeshPaintPerInstance**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bDisallowMeshPaintPerInstance](ue_ue.StaticMeshComponent.md#bdisallowmeshpaintperinstance)

___

### bDisplayVertexColors

• **bDisplayVertexColors**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bDisplayVertexColors](ue_ue.StaticMeshComponent.md#bdisplayvertexcolors)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bEditableWhenInherited](ue_ue.StaticMeshComponent.md#beditablewheninherited)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bEnableAutoLODGeneration](ue_ue.StaticMeshComponent.md#benableautolodgeneration)

___

### bEnableMaterialParameterCaching

• **bEnableMaterialParameterCaching**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bEnableMaterialParameterCaching](ue_ue.StaticMeshComponent.md#benablematerialparametercaching)

___

### bEvaluateWorldPositionOffset

• **bEvaluateWorldPositionOffset**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bEvaluateWorldPositionOffset](ue_ue.StaticMeshComponent.md#bevaluateworldpositionoffset)

___

### bExcludeFromLightAttachmentGroup

• **bExcludeFromLightAttachmentGroup**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bExcludeFromLightAttachmentGroup](ue_ue.StaticMeshComponent.md#bexcludefromlightattachmentgroup)

___

### bForceMipStreaming

• **bForceMipStreaming**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bForceMipStreaming](ue_ue.StaticMeshComponent.md#bforcemipstreaming)

___

### bForceNavigationObstacle

• **bForceNavigationObstacle**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bForceNavigationObstacle](ue_ue.StaticMeshComponent.md#bforcenavigationobstacle)

___

### bGenerateOverlapEvents

• **bGenerateOverlapEvents**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bGenerateOverlapEvents](ue_ue.StaticMeshComponent.md#bgenerateoverlapevents)

___

### bHasCustomNavigableGeometry

• **bHasCustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bHasCustomNavigableGeometry](ue_ue.StaticMeshComponent.md#bhascustomnavigablegeometry)

___

### bHasMotionBlurVelocityMeshes

• **bHasMotionBlurVelocityMeshes**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bHasMotionBlurVelocityMeshes](ue_ue.StaticMeshComponent.md#bhasmotionblurvelocitymeshes)

___

### bHasPerInstanceHitProxies

• **bHasPerInstanceHitProxies**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bHasPerInstanceHitProxies](ue_ue.StaticMeshComponent.md#bhasperinstancehitproxies)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bHiddenInGame](ue_ue.StaticMeshComponent.md#bhiddeningame)

___

### bIgnoreInstanceForTextureStreaming

• **bIgnoreInstanceForTextureStreaming**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bIgnoreInstanceForTextureStreaming](ue_ue.StaticMeshComponent.md#bignoreinstancefortexturestreaming)

___

### bIgnoreRadialForce

• **bIgnoreRadialForce**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bIgnoreRadialForce](ue_ue.StaticMeshComponent.md#bignoreradialforce)

___

### bIgnoreRadialImpulse

• **bIgnoreRadialImpulse**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bIgnoreRadialImpulse](ue_ue.StaticMeshComponent.md#bignoreradialimpulse)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bInstanceComponent](ue_ue.StaticMeshComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bIsActive](ue_ue.StaticMeshComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bIsEditorOnly](ue_ue.StaticMeshComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bIsVisualizationComponent](ue_ue.StaticMeshComponent.md#bisvisualizationcomponent)

___

### bLightAsIfStatic

• **bLightAsIfStatic**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bLightAsIfStatic](ue_ue.StaticMeshComponent.md#blightasifstatic)

___

### bLightAttachmentsAsGroup

• **bLightAttachmentsAsGroup**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bLightAttachmentsAsGroup](ue_ue.StaticMeshComponent.md#blightattachmentsasgroup)

___

### bMultiBodyOverlap

• **bMultiBodyOverlap**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bMultiBodyOverlap](ue_ue.StaticMeshComponent.md#bmultibodyoverlap)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bNetAddressable](ue_ue.StaticMeshComponent.md#bnetaddressable)

___

### bNeverDistanceCull

• **bNeverDistanceCull**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bNeverDistanceCull](ue_ue.StaticMeshComponent.md#bneverdistancecull)

___

### bOnlyOwnerSee

• **bOnlyOwnerSee**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bOnlyOwnerSee](ue_ue.StaticMeshComponent.md#bonlyownersee)

___

### bOverrideDistanceFieldSelfShadowBias

• **bOverrideDistanceFieldSelfShadowBias**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bOverrideDistanceFieldSelfShadowBias](ue_ue.StaticMeshComponent.md#boverridedistancefieldselfshadowbias)

___

### bOverrideLightMapRes

• **bOverrideLightMapRes**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bOverrideLightMapRes](ue_ue.StaticMeshComponent.md#boverridelightmapres)

___

### bOverrideMinLOD

• **bOverrideMinLOD**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bOverrideMinLOD](ue_ue.StaticMeshComponent.md#boverrideminlod)

___

### bOverrideNavigationExport

• **bOverrideNavigationExport**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bOverrideNavigationExport](ue_ue.StaticMeshComponent.md#boverridenavigationexport)

___

### bOverrideWireframeColor

• **bOverrideWireframeColor**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bOverrideWireframeColor](ue_ue.StaticMeshComponent.md#boverridewireframecolor)

___

### bOwnerNoSee

• **bOwnerNoSee**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bOwnerNoSee](ue_ue.StaticMeshComponent.md#bownernosee)

___

### bReceiveMobileCSMShadows

• **bReceiveMobileCSMShadows**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bReceiveMobileCSMShadows](ue_ue.StaticMeshComponent.md#breceivemobilecsmshadows)

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bReceivesDecals](ue_ue.StaticMeshComponent.md#breceivesdecals)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bRenderCustomDepth](ue_ue.StaticMeshComponent.md#brendercustomdepth)

___

### bRenderInDepthPass

• **bRenderInDepthPass**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bRenderInDepthPass](ue_ue.StaticMeshComponent.md#brenderindepthpass)

___

### bRenderInMainPass

• **bRenderInMainPass**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bRenderInMainPass](ue_ue.StaticMeshComponent.md#brenderinmainpass)

___

### bReplicatePhysicsToAutonomousProxy

• **bReplicatePhysicsToAutonomousProxy**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bReplicatePhysicsToAutonomousProxy](ue_ue.StaticMeshComponent.md#breplicatephysicstoautonomousproxy)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bReplicates](ue_ue.StaticMeshComponent.md#breplicates)

___

### bReturnMaterialOnMove

• **bReturnMaterialOnMove**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bReturnMaterialOnMove](ue_ue.StaticMeshComponent.md#breturnmaterialonmove)

___

### bReverseCulling

• **bReverseCulling**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bReverseCulling](ue_ue.StaticMeshComponent.md#breverseculling)

___

### bSelectable

• **bSelectable**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bSelectable](ue_ue.StaticMeshComponent.md#bselectable)

___

### bSelected

• **bSelected**: `boolean`

___

### bSelfShadowOnly

• **bSelfShadowOnly**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bSelfShadowOnly](ue_ue.StaticMeshComponent.md#bselfshadowonly)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bShouldBeAttached](ue_ue.StaticMeshComponent.md#bshouldbeattached)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.StaticMeshComponent.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.StaticMeshComponent.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.StaticMeshComponent.md#bshouldupdatephysicsvolume)

___

### bSingleSampleShadowFromStationaryLights

• **bSingleSampleShadowFromStationaryLights**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bSingleSampleShadowFromStationaryLights](ue_ue.StaticMeshComponent.md#bsinglesampleshadowfromstationarylights)

___

### bTraceComplexOnMove

• **bTraceComplexOnMove**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bTraceComplexOnMove](ue_ue.StaticMeshComponent.md#btracecomplexonmove)

___

### bTreatAsBackgroundForOcclusion

• **bTreatAsBackgroundForOcclusion**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bTreatAsBackgroundForOcclusion](ue_ue.StaticMeshComponent.md#btreatasbackgroundforocclusion)

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bUseAsOccluder](ue_ue.StaticMeshComponent.md#buseasoccluder)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bUseAttachParentBound](ue_ue.StaticMeshComponent.md#buseattachparentbound)

___

### bUseDefaultCollision

• **bUseDefaultCollision**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bUseDefaultCollision](ue_ue.StaticMeshComponent.md#busedefaultcollision)

___

### bUseEditorCompositing

• **bUseEditorCompositing**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bUseEditorCompositing](ue_ue.StaticMeshComponent.md#buseeditorcompositing)

___

### bUseMaxLODAsImposter

• **bUseMaxLODAsImposter**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bUseMaxLODAsImposter](ue_ue.StaticMeshComponent.md#busemaxlodasimposter)

___

### bUseSubDivisions

• **bUseSubDivisions**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bUseSubDivisions](ue_ue.StaticMeshComponent.md#busesubdivisions)

___

### bUseViewOwnerDepthPriorityGroup

• **bUseViewOwnerDepthPriorityGroup**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bUseViewOwnerDepthPriorityGroup](ue_ue.StaticMeshComponent.md#buseviewownerdepthprioritygroup)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bVisible](ue_ue.StaticMeshComponent.md#bvisible)

___

### bVisibleInRayTracing

• **bVisibleInRayTracing**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bVisibleInRayTracing](ue_ue.StaticMeshComponent.md#bvisibleinraytracing)

___

### bVisibleInReflectionCaptures

• **bVisibleInReflectionCaptures**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bVisibleInReflectionCaptures](ue_ue.StaticMeshComponent.md#bvisibleinreflectioncaptures)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[bVisualizeComponent](ue_ue.StaticMeshComponent.md#bvisualizecomponent)

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

___

### ClearMoveIgnoreActors

▸ **ClearMoveIgnoreActors**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ClearMoveIgnoreActors](ue_ue.StaticMeshComponent.md#clearmoveignoreactors)

___

### ClearMoveIgnoreComponents

▸ **ClearMoveIgnoreComponents**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ClearMoveIgnoreComponents](ue_ue.StaticMeshComponent.md#clearmoveignorecomponents)

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

___

### CopyArrayOfMoveIgnoreActors

▸ **CopyArrayOfMoveIgnoreActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CopyArrayOfMoveIgnoreActors](ue_ue.StaticMeshComponent.md#copyarrayofmoveignoreactors)

___

### CopyArrayOfMoveIgnoreComponents

▸ **CopyArrayOfMoveIgnoreComponents**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[CopyArrayOfMoveIgnoreComponents](ue_ue.StaticMeshComponent.md#copyarrayofmoveignorecomponents)

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

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[Deactivate](ue_ue.StaticMeshComponent.md#deactivate)

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

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetAllSocketNames](ue_ue.StaticMeshComponent.md#getallsocketnames)

___

### GetAngularDamping

▸ **GetAngularDamping**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetAngularDamping](ue_ue.StaticMeshComponent.md#getangulardamping)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetAttachParent](ue_ue.StaticMeshComponent.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetAttachSocketName](ue_ue.StaticMeshComponent.md#getattachsocketname)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetClass](ue_ue.StaticMeshComponent.md#getclass)

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

___

### GetCollisionEnabled

▸ **GetCollisionEnabled**(): [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Returns

[`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetCollisionEnabled](ue_ue.StaticMeshComponent.md#getcollisionenabled)

___

### GetCollisionObjectType

▸ **GetCollisionObjectType**(): [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Returns

[`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetCollisionObjectType](ue_ue.StaticMeshComponent.md#getcollisionobjecttype)

___

### GetCollisionProfileName

▸ **GetCollisionProfileName**(): `string`

#### Returns

`string`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetCollisionProfileName](ue_ue.StaticMeshComponent.md#getcollisionprofilename)

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

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetComponentTickInterval](ue_ue.StaticMeshComponent.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetComponentVelocity](ue_ue.StaticMeshComponent.md#getcomponentvelocity)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetForwardVector](ue_ue.StaticMeshComponent.md#getforwardvector)

___

### GetGenerateOverlapEvents

▸ **GetGenerateOverlapEvents**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetGenerateOverlapEvents](ue_ue.StaticMeshComponent.md#getgenerateoverlapevents)

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

___

### GetLinearDamping

▸ **GetLinearDamping**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetLinearDamping](ue_ue.StaticMeshComponent.md#getlineardamping)

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

___

### GetMass

▸ **GetMass**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetMass](ue_ue.StaticMeshComponent.md#getmass)

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

___

### GetMaterialSlotNames

▸ **GetMaterialSlotNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetMaterialSlotNames](ue_ue.StaticMeshComponent.md#getmaterialslotnames)

___

### GetMaterials

▸ **GetMaterials**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetMaterials](ue_ue.StaticMeshComponent.md#getmaterials)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetName](ue_ue.StaticMeshComponent.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetNumChildrenComponents](ue_ue.StaticMeshComponent.md#getnumchildrencomponents)

___

### GetNumMaterials

▸ **GetNumMaterials**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetNumMaterials](ue_ue.StaticMeshComponent.md#getnummaterials)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetOuter](ue_ue.StaticMeshComponent.md#getouter)

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

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetOwner](ue_ue.StaticMeshComponent.md#getowner)

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

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetPhysicsVolume](ue_ue.StaticMeshComponent.md#getphysicsvolume)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetRelativeTransform](ue_ue.StaticMeshComponent.md#getrelativetransform)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetRightVector](ue_ue.StaticMeshComponent.md#getrightvector)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.StaticMeshComponent.md#getshouldupdatephysicsvolume)

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

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetUpVector](ue_ue.StaticMeshComponent.md#getupvector)

___

### GetWalkableSlopeOverride

▸ **GetWalkableSlopeOverride**(): [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Returns

[`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetWalkableSlopeOverride](ue_ue.StaticMeshComponent.md#getwalkableslopeoverride)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[GetWorld](ue_ue.StaticMeshComponent.md#getworld)

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

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsActive](ue_ue.StaticMeshComponent.md#isactive)

___

### IsAnyRigidBodyAwake

▸ **IsAnyRigidBodyAwake**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsAnyRigidBodyAwake](ue_ue.StaticMeshComponent.md#isanyrigidbodyawake)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsAnySimulatingPhysics](ue_ue.StaticMeshComponent.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsBeingDestroyed](ue_ue.StaticMeshComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsComponentTickEnabled](ue_ue.StaticMeshComponent.md#iscomponenttickenabled)

___

### IsGravityEnabled

▸ **IsGravityEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsGravityEnabled](ue_ue.StaticMeshComponent.md#isgravityenabled)

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

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[IsVisible](ue_ue.StaticMeshComponent.md#isvisible)

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

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_GetComponentLocation](ue_ue.StaticMeshComponent.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_GetComponentRotation](ue_ue.StaticMeshComponent.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_GetComponentScale](ue_ue.StaticMeshComponent.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_GetComponentToWorld](ue_ue.StaticMeshComponent.md#k2_getcomponenttoworld)

___

### K2\_IsCollisionEnabled

▸ **K2_IsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_IsCollisionEnabled](ue_ue.StaticMeshComponent.md#k2_iscollisionenabled)

___

### K2\_IsPhysicsCollisionEnabled

▸ **K2_IsPhysicsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_IsPhysicsCollisionEnabled](ue_ue.StaticMeshComponent.md#k2_isphysicscollisionenabled)

___

### K2\_IsQueryCollisionEnabled

▸ **K2_IsQueryCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[K2_IsQueryCollisionEnabled](ue_ue.StaticMeshComponent.md#k2_isquerycollisionenabled)

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

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnRep_AttachChildren](ue_ue.StaticMeshComponent.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnRep_AttachParent](ue_ue.StaticMeshComponent.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnRep_AttachSocketName](ue_ue.StaticMeshComponent.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnRep_IsActive](ue_ue.StaticMeshComponent.md#onrep_isactive)

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

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[OnRep_Transform](ue_ue.StaticMeshComponent.md#onrep_transform)

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

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ReceiveBeginPlay](ue_ue.StaticMeshComponent.md#receivebeginplay)

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

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[RegisterComponent](ue_ue.StaticMeshComponent.md#registercomponent)

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

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ResetRelativeTransform](ue_ue.StaticMeshComponent.md#resetrelativetransform)

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

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[ToggleActive](ue_ue.StaticMeshComponent.md#toggleactive)

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

___

### WakeAllRigidBodies

▸ **WakeAllRigidBodies**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[WakeAllRigidBodies](ue_ue.StaticMeshComponent.md#wakeallrigidbodies)

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

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ControlPointMeshComponent`](ue_ue.ControlPointMeshComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ControlPointMeshComponent`](ue_ue.ControlPointMeshComponent.md)

#### Overrides

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[Find](ue_ue.StaticMeshComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ControlPointMeshComponent`](ue_ue.ControlPointMeshComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ControlPointMeshComponent`](ue_ue.ControlPointMeshComponent.md)

#### Overrides

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[Load](ue_ue.StaticMeshComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[StaticMeshComponent](ue_ue.StaticMeshComponent.md).[StaticClass](ue_ue.StaticMeshComponent.md#staticclass)
