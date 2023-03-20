[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PoseableMeshComponent

# Class: PoseableMeshComponent

[ue/ue](../modules/ue_ue.md).PoseableMeshComponent

## Hierarchy

- [`SkinnedMeshComponent`](ue_ue.SkinnedMeshComponent.md)

  ↳ **`PoseableMeshComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.PoseableMeshComponent.md#constructor)

### Properties

- [AlwaysLoadOnClient](ue_ue.PoseableMeshComponent.md#alwaysloadonclient)
- [AlwaysLoadOnServer](ue_ue.PoseableMeshComponent.md#alwaysloadonserver)
- [AssetUserData](ue_ue.PoseableMeshComponent.md#assetuserdata)
- [AttachChildren](ue_ue.PoseableMeshComponent.md#attachchildren)
- [AttachParent](ue_ue.PoseableMeshComponent.md#attachparent)
- [AttachSocketName](ue_ue.PoseableMeshComponent.md#attachsocketname)
- [BodyInstance](ue_ue.PoseableMeshComponent.md#bodyinstance)
- [BoundsScale](ue_ue.PoseableMeshComponent.md#boundsscale)
- [CachedMaxDrawDistance](ue_ue.PoseableMeshComponent.md#cachedmaxdrawdistance)
- [CachedWorldSpaceBounds](ue_ue.PoseableMeshComponent.md#cachedworldspacebounds)
- [CachedWorldToLocalTransform](ue_ue.PoseableMeshComponent.md#cachedworldtolocaltransform)
- [CanBeCharacterBase](ue_ue.PoseableMeshComponent.md#canbecharacterbase)
- [CanCharacterStepUpOn](ue_ue.PoseableMeshComponent.md#cancharacterstepupon)
- [CapsuleIndirectShadowMinVisibility](ue_ue.PoseableMeshComponent.md#capsuleindirectshadowminvisibility)
- [CastShadow](ue_ue.PoseableMeshComponent.md#castshadow)
- [ClientAttachedChildren](ue_ue.PoseableMeshComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.PoseableMeshComponent.md#componenttags)
- [ComponentVelocity](ue_ue.PoseableMeshComponent.md#componentvelocity)
- [CreationMethod](ue_ue.PoseableMeshComponent.md#creationmethod)
- [CustomDepthStencilValue](ue_ue.PoseableMeshComponent.md#customdepthstencilvalue)
- [CustomDepthStencilWriteMask](ue_ue.PoseableMeshComponent.md#customdepthstencilwritemask)
- [CustomPrimitiveData](ue_ue.PoseableMeshComponent.md#customprimitivedata)
- [DepthPriorityGroup](ue_ue.PoseableMeshComponent.md#depthprioritygroup)
- [DetailMode](ue_ue.PoseableMeshComponent.md#detailmode)
- [ExcludeForSpecificHLODLevels](ue_ue.PoseableMeshComponent.md#excludeforspecifichlodlevels)
- [ForcedLodModel](ue_ue.PoseableMeshComponent.md#forcedlodmodel)
- [IndirectLightingCacheQuality](ue_ue.PoseableMeshComponent.md#indirectlightingcachequality)
- [LDMaxDrawDistance](ue_ue.PoseableMeshComponent.md#ldmaxdrawdistance)
- [LODInfo](ue_ue.PoseableMeshComponent.md#lodinfo)
- [LODParentPrimitive](ue_ue.PoseableMeshComponent.md#lodparentprimitive)
- [LightingChannels](ue_ue.PoseableMeshComponent.md#lightingchannels)
- [LightmapType](ue_ue.PoseableMeshComponent.md#lightmaptype)
- [LpvBiasMultiplier](ue_ue.PoseableMeshComponent.md#lpvbiasmultiplier)
- [MasterPoseComponent](ue_ue.PoseableMeshComponent.md#masterposecomponent)
- [MinDrawDistance](ue_ue.PoseableMeshComponent.md#mindrawdistance)
- [MinLodModel](ue_ue.PoseableMeshComponent.md#minlodmodel)
- [Mobility](ue_ue.PoseableMeshComponent.md#mobility)
- [MoveIgnoreActors](ue_ue.PoseableMeshComponent.md#moveignoreactors)
- [MoveIgnoreComponents](ue_ue.PoseableMeshComponent.md#moveignorecomponents)
- [OnBeginCursorOver](ue_ue.PoseableMeshComponent.md#onbegincursorover)
- [OnClicked](ue_ue.PoseableMeshComponent.md#onclicked)
- [OnComponentActivated](ue_ue.PoseableMeshComponent.md#oncomponentactivated)
- [OnComponentBeginOverlap](ue_ue.PoseableMeshComponent.md#oncomponentbeginoverlap)
- [OnComponentDeactivated](ue_ue.PoseableMeshComponent.md#oncomponentdeactivated)
- [OnComponentEndOverlap](ue_ue.PoseableMeshComponent.md#oncomponentendoverlap)
- [OnComponentHit](ue_ue.PoseableMeshComponent.md#oncomponenthit)
- [OnComponentSleep](ue_ue.PoseableMeshComponent.md#oncomponentsleep)
- [OnComponentWake](ue_ue.PoseableMeshComponent.md#oncomponentwake)
- [OnEndCursorOver](ue_ue.PoseableMeshComponent.md#onendcursorover)
- [OnInputTouchBegin](ue_ue.PoseableMeshComponent.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.PoseableMeshComponent.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.PoseableMeshComponent.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.PoseableMeshComponent.md#oninputtouchleave)
- [OnReleased](ue_ue.PoseableMeshComponent.md#onreleased)
- [OverrideMaterials](ue_ue.PoseableMeshComponent.md#overridematerials)
- [PhysicsAssetOverride](ue_ue.PoseableMeshComponent.md#physicsassetoverride)
- [PhysicsVolume](ue_ue.PoseableMeshComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.PoseableMeshComponent.md#physicsvolumechangeddelegate)
- [PrimaryComponentTick](ue_ue.PoseableMeshComponent.md#primarycomponenttick)
- [RelativeLocation](ue_ue.PoseableMeshComponent.md#relativelocation)
- [RelativeRotation](ue_ue.PoseableMeshComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.PoseableMeshComponent.md#relativescale3d)
- [RuntimeVirtualTextures](ue_ue.PoseableMeshComponent.md#runtimevirtualtextures)
- [SkeletalMesh](ue_ue.PoseableMeshComponent.md#skeletalmesh)
- [StreamingDistanceMultiplier](ue_ue.PoseableMeshComponent.md#streamingdistancemultiplier)
- [TranslucencySortPriority](ue_ue.PoseableMeshComponent.md#translucencysortpriority)
- [UCSModifiedProperties](ue_ue.PoseableMeshComponent.md#ucsmodifiedproperties)
- [ViewOwnerDepthPriorityGroup](ue_ue.PoseableMeshComponent.md#viewownerdepthprioritygroup)
- [VirtualTextureCullMips](ue_ue.PoseableMeshComponent.md#virtualtexturecullmips)
- [VirtualTextureLodBias](ue_ue.PoseableMeshComponent.md#virtualtexturelodbias)
- [VirtualTextureMinCoverage](ue_ue.PoseableMeshComponent.md#virtualtexturemincoverage)
- [VirtualTextureRenderPassType](ue_ue.PoseableMeshComponent.md#virtualtexturerenderpasstype)
- [VisibilityBasedAnimTickOption](ue_ue.PoseableMeshComponent.md#visibilitybasedanimtickoption)
- [VisibilityId](ue_ue.PoseableMeshComponent.md#visibilityid)
- [WireframeColor](ue_ue.PoseableMeshComponent.md#wireframecolor)
- [\_\_tid\_ActorComponent\_\_](ue_ue.PoseableMeshComponent.md#__tid_actorcomponent__)
- [\_\_tid\_MeshComponent\_\_](ue_ue.PoseableMeshComponent.md#__tid_meshcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.PoseableMeshComponent.md#__tid_object__)
- [\_\_tid\_PoseableMeshComponent\_\_](ue_ue.PoseableMeshComponent.md#__tid_poseablemeshcomponent__)
- [\_\_tid\_PrimitiveComponent\_\_](ue_ue.PoseableMeshComponent.md#__tid_primitivecomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.PoseableMeshComponent.md#__tid_scenecomponent__)
- [\_\_tid\_SkinnedMeshComponent\_\_](ue_ue.PoseableMeshComponent.md#__tid_skinnedmeshcomponent__)
- [bAbsoluteLocation](ue_ue.PoseableMeshComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.PoseableMeshComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.PoseableMeshComponent.md#babsolutescale)
- [bAffectDistanceFieldLighting](ue_ue.PoseableMeshComponent.md#baffectdistancefieldlighting)
- [bAffectDynamicIndirectLighting](ue_ue.PoseableMeshComponent.md#baffectdynamicindirectlighting)
- [bAllowCullDistanceVolume](ue_ue.PoseableMeshComponent.md#ballowculldistancevolume)
- [bAlwaysCreatePhysicsState](ue_ue.PoseableMeshComponent.md#balwayscreatephysicsstate)
- [bApplyImpulseOnDamage](ue_ue.PoseableMeshComponent.md#bapplyimpulseondamage)
- [bAutoActivate](ue_ue.PoseableMeshComponent.md#bautoactivate)
- [bBatchImpostersAsInstances](ue_ue.PoseableMeshComponent.md#bbatchimpostersasinstances)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.PoseableMeshComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCPUSkinning](ue_ue.PoseableMeshComponent.md#bcpuskinning)
- [bCachedLocalBoundsUpToDate](ue_ue.PoseableMeshComponent.md#bcachedlocalboundsuptodate)
- [bCanEverAffectNavigation](ue_ue.PoseableMeshComponent.md#bcaneveraffectnavigation)
- [bCanHighlightSelectedSections](ue_ue.PoseableMeshComponent.md#bcanhighlightselectedsections)
- [bCastCapsuleDirectShadow](ue_ue.PoseableMeshComponent.md#bcastcapsuledirectshadow)
- [bCastCapsuleIndirectShadow](ue_ue.PoseableMeshComponent.md#bcastcapsuleindirectshadow)
- [bCastCinematicShadow](ue_ue.PoseableMeshComponent.md#bcastcinematicshadow)
- [bCastDynamicShadow](ue_ue.PoseableMeshComponent.md#bcastdynamicshadow)
- [bCastFarShadow](ue_ue.PoseableMeshComponent.md#bcastfarshadow)
- [bCastHiddenShadow](ue_ue.PoseableMeshComponent.md#bcasthiddenshadow)
- [bCastInsetShadow](ue_ue.PoseableMeshComponent.md#bcastinsetshadow)
- [bCastShadowAsTwoSided](ue_ue.PoseableMeshComponent.md#bcastshadowastwosided)
- [bCastStaticShadow](ue_ue.PoseableMeshComponent.md#bcaststaticshadow)
- [bCastVolumetricTranslucentShadow](ue_ue.PoseableMeshComponent.md#bcastvolumetrictranslucentshadow)
- [bComponentToWorldUpdated](ue_ue.PoseableMeshComponent.md#bcomponenttoworldupdated)
- [bComponentUseFixedSkelBounds](ue_ue.PoseableMeshComponent.md#bcomponentusefixedskelbounds)
- [bConsiderAllBodiesForBounds](ue_ue.PoseableMeshComponent.md#bconsiderallbodiesforbounds)
- [bCreatedByConstructionScript](ue_ue.PoseableMeshComponent.md#bcreatedbyconstructionscript)
- [bDisableMorphTarget](ue_ue.PoseableMeshComponent.md#bdisablemorphtarget)
- [bDisplayBones](ue_ue.PoseableMeshComponent.md#bdisplaybones)
- [bDisplayDebugUpdateRateOptimizations](ue_ue.PoseableMeshComponent.md#bdisplaydebugupdaterateoptimizations)
- [bEditableWhenInherited](ue_ue.PoseableMeshComponent.md#beditablewheninherited)
- [bEnableAutoLODGeneration](ue_ue.PoseableMeshComponent.md#benableautolodgeneration)
- [bEnableMaterialParameterCaching](ue_ue.PoseableMeshComponent.md#benablematerialparametercaching)
- [bEnableUpdateRateOptimizations](ue_ue.PoseableMeshComponent.md#benableupdaterateoptimizations)
- [bExcludeFromLightAttachmentGroup](ue_ue.PoseableMeshComponent.md#bexcludefromlightattachmentgroup)
- [bForceMeshObjectUpdate](ue_ue.PoseableMeshComponent.md#bforcemeshobjectupdate)
- [bForceMipStreaming](ue_ue.PoseableMeshComponent.md#bforcemipstreaming)
- [bForceWireframe](ue_ue.PoseableMeshComponent.md#bforcewireframe)
- [bGenerateOverlapEvents](ue_ue.PoseableMeshComponent.md#bgenerateoverlapevents)
- [bHasCustomNavigableGeometry](ue_ue.PoseableMeshComponent.md#bhascustomnavigablegeometry)
- [bHasMotionBlurVelocityMeshes](ue_ue.PoseableMeshComponent.md#bhasmotionblurvelocitymeshes)
- [bHasPerInstanceHitProxies](ue_ue.PoseableMeshComponent.md#bhasperinstancehitproxies)
- [bHiddenInGame](ue_ue.PoseableMeshComponent.md#bhiddeningame)
- [bHideSkin](ue_ue.PoseableMeshComponent.md#bhideskin)
- [bIgnoreMasterPoseComponentLOD](ue_ue.PoseableMeshComponent.md#bignoremasterposecomponentlod)
- [bIgnoreRadialForce](ue_ue.PoseableMeshComponent.md#bignoreradialforce)
- [bIgnoreRadialImpulse](ue_ue.PoseableMeshComponent.md#bignoreradialimpulse)
- [bInstanceComponent](ue_ue.PoseableMeshComponent.md#binstancecomponent)
- [bIsActive](ue_ue.PoseableMeshComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.PoseableMeshComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.PoseableMeshComponent.md#bisvisualizationcomponent)
- [bLightAsIfStatic](ue_ue.PoseableMeshComponent.md#blightasifstatic)
- [bLightAttachmentsAsGroup](ue_ue.PoseableMeshComponent.md#blightattachmentsasgroup)
- [bMultiBodyOverlap](ue_ue.PoseableMeshComponent.md#bmultibodyoverlap)
- [bNetAddressable](ue_ue.PoseableMeshComponent.md#bnetaddressable)
- [bNeverDistanceCull](ue_ue.PoseableMeshComponent.md#bneverdistancecull)
- [bOnlyOwnerSee](ue_ue.PoseableMeshComponent.md#bonlyownersee)
- [bOverrideMinLod](ue_ue.PoseableMeshComponent.md#boverrideminlod)
- [bOwnerNoSee](ue_ue.PoseableMeshComponent.md#bownernosee)
- [bPerBoneMotionBlur](ue_ue.PoseableMeshComponent.md#bperbonemotionblur)
- [bReceiveMobileCSMShadows](ue_ue.PoseableMeshComponent.md#breceivemobilecsmshadows)
- [bReceivesDecals](ue_ue.PoseableMeshComponent.md#breceivesdecals)
- [bRecentlyRendered](ue_ue.PoseableMeshComponent.md#brecentlyrendered)
- [bRenderCustomDepth](ue_ue.PoseableMeshComponent.md#brendercustomdepth)
- [bRenderInDepthPass](ue_ue.PoseableMeshComponent.md#brenderindepthpass)
- [bRenderInMainPass](ue_ue.PoseableMeshComponent.md#brenderinmainpass)
- [bRenderStatic](ue_ue.PoseableMeshComponent.md#brenderstatic)
- [bReplicatePhysicsToAutonomousProxy](ue_ue.PoseableMeshComponent.md#breplicatephysicstoautonomousproxy)
- [bReplicates](ue_ue.PoseableMeshComponent.md#breplicates)
- [bReturnMaterialOnMove](ue_ue.PoseableMeshComponent.md#breturnmaterialonmove)
- [bSelectable](ue_ue.PoseableMeshComponent.md#bselectable)
- [bSelfShadowOnly](ue_ue.PoseableMeshComponent.md#bselfshadowonly)
- [bShouldBeAttached](ue_ue.PoseableMeshComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.PoseableMeshComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.PoseableMeshComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.PoseableMeshComponent.md#bshouldupdatephysicsvolume)
- [bSingleSampleShadowFromStationaryLights](ue_ue.PoseableMeshComponent.md#bsinglesampleshadowfromstationarylights)
- [bSyncAttachParentLOD](ue_ue.PoseableMeshComponent.md#bsyncattachparentlod)
- [bTraceComplexOnMove](ue_ue.PoseableMeshComponent.md#btracecomplexonmove)
- [bTreatAsBackgroundForOcclusion](ue_ue.PoseableMeshComponent.md#btreatasbackgroundforocclusion)
- [bUseAsOccluder](ue_ue.PoseableMeshComponent.md#buseasoccluder)
- [bUseAttachParentBound](ue_ue.PoseableMeshComponent.md#buseattachparentbound)
- [bUseBoundsFromMasterPoseComponent](ue_ue.PoseableMeshComponent.md#buseboundsfrommasterposecomponent)
- [bUseEditorCompositing](ue_ue.PoseableMeshComponent.md#buseeditorcompositing)
- [bUseMaxLODAsImposter](ue_ue.PoseableMeshComponent.md#busemaxlodasimposter)
- [bUseViewOwnerDepthPriorityGroup](ue_ue.PoseableMeshComponent.md#buseviewownerdepthprioritygroup)
- [bVisible](ue_ue.PoseableMeshComponent.md#bvisible)
- [bVisibleInRayTracing](ue_ue.PoseableMeshComponent.md#bvisibleinraytracing)
- [bVisibleInReflectionCaptures](ue_ue.PoseableMeshComponent.md#bvisibleinreflectioncaptures)
- [bVisualizeComponent](ue_ue.PoseableMeshComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.PoseableMeshComponent.md#activate)
- [AddAngularImpulse](ue_ue.PoseableMeshComponent.md#addangularimpulse)
- [AddAngularImpulseInDegrees](ue_ue.PoseableMeshComponent.md#addangularimpulseindegrees)
- [AddAngularImpulseInRadians](ue_ue.PoseableMeshComponent.md#addangularimpulseinradians)
- [AddForce](ue_ue.PoseableMeshComponent.md#addforce)
- [AddForceAtLocation](ue_ue.PoseableMeshComponent.md#addforceatlocation)
- [AddForceAtLocationLocal](ue_ue.PoseableMeshComponent.md#addforceatlocationlocal)
- [AddImpulse](ue_ue.PoseableMeshComponent.md#addimpulse)
- [AddImpulseAtLocation](ue_ue.PoseableMeshComponent.md#addimpulseatlocation)
- [AddRadialForce](ue_ue.PoseableMeshComponent.md#addradialforce)
- [AddRadialImpulse](ue_ue.PoseableMeshComponent.md#addradialimpulse)
- [AddTickPrerequisiteActor](ue_ue.PoseableMeshComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PoseableMeshComponent.md#addtickprerequisitecomponent)
- [AddTorque](ue_ue.PoseableMeshComponent.md#addtorque)
- [AddTorqueInDegrees](ue_ue.PoseableMeshComponent.md#addtorqueindegrees)
- [AddTorqueInRadians](ue_ue.PoseableMeshComponent.md#addtorqueinradians)
- [BoneIsChildOf](ue_ue.PoseableMeshComponent.md#boneischildof)
- [CanCharacterStepUp](ue_ue.PoseableMeshComponent.md#cancharacterstepup)
- [ClearMoveIgnoreActors](ue_ue.PoseableMeshComponent.md#clearmoveignoreactors)
- [ClearMoveIgnoreComponents](ue_ue.PoseableMeshComponent.md#clearmoveignorecomponents)
- [ClearSkinWeightOverride](ue_ue.PoseableMeshComponent.md#clearskinweightoverride)
- [ClearSkinWeightProfile](ue_ue.PoseableMeshComponent.md#clearskinweightprofile)
- [ClearVertexColorOverride](ue_ue.PoseableMeshComponent.md#clearvertexcoloroverride)
- [ComponentHasTag](ue_ue.PoseableMeshComponent.md#componenthastag)
- [CopyArrayOfMoveIgnoreActors](ue_ue.PoseableMeshComponent.md#copyarrayofmoveignoreactors)
- [CopyArrayOfMoveIgnoreComponents](ue_ue.PoseableMeshComponent.md#copyarrayofmoveignorecomponents)
- [CopyPoseFromSkeletalComponent](ue_ue.PoseableMeshComponent.md#copyposefromskeletalcomponent)
- [CreateAndSetMaterialInstanceDynamic](ue_ue.PoseableMeshComponent.md#createandsetmaterialinstancedynamic)
- [CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.PoseableMeshComponent.md#createandsetmaterialinstancedynamicfrommaterial)
- [CreateDefaultSubobject](ue_ue.PoseableMeshComponent.md#createdefaultsubobject)
- [CreateDynamicMaterialInstance](ue_ue.PoseableMeshComponent.md#createdynamicmaterialinstance)
- [Deactivate](ue_ue.PoseableMeshComponent.md#deactivate)
- [DetachFromParent](ue_ue.PoseableMeshComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.PoseableMeshComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.PoseableMeshComponent.md#executeubergraph)
- [FindClosestBone\_K2](ue_ue.PoseableMeshComponent.md#findclosestbone_k2)
- [GetAllSocketNames](ue_ue.PoseableMeshComponent.md#getallsocketnames)
- [GetAngularDamping](ue_ue.PoseableMeshComponent.md#getangulardamping)
- [GetAttachParent](ue_ue.PoseableMeshComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.PoseableMeshComponent.md#getattachsocketname)
- [GetBoneIndex](ue_ue.PoseableMeshComponent.md#getboneindex)
- [GetBoneLocationByName](ue_ue.PoseableMeshComponent.md#getbonelocationbyname)
- [GetBoneName](ue_ue.PoseableMeshComponent.md#getbonename)
- [GetBoneRotationByName](ue_ue.PoseableMeshComponent.md#getbonerotationbyname)
- [GetBoneScaleByName](ue_ue.PoseableMeshComponent.md#getbonescalebyname)
- [GetBoneTransformByName](ue_ue.PoseableMeshComponent.md#getbonetransformbyname)
- [GetCenterOfMass](ue_ue.PoseableMeshComponent.md#getcenterofmass)
- [GetChildComponent](ue_ue.PoseableMeshComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.PoseableMeshComponent.md#getchildrencomponents)
- [GetClass](ue_ue.PoseableMeshComponent.md#getclass)
- [GetClosestPointOnCollision](ue_ue.PoseableMeshComponent.md#getclosestpointoncollision)
- [GetCollisionEnabled](ue_ue.PoseableMeshComponent.md#getcollisionenabled)
- [GetCollisionObjectType](ue_ue.PoseableMeshComponent.md#getcollisionobjecttype)
- [GetCollisionProfileName](ue_ue.PoseableMeshComponent.md#getcollisionprofilename)
- [GetCollisionResponseToChannel](ue_ue.PoseableMeshComponent.md#getcollisionresponsetochannel)
- [GetComponentTickInterval](ue_ue.PoseableMeshComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.PoseableMeshComponent.md#getcomponentvelocity)
- [GetCurrentSkinWeightProfileName](ue_ue.PoseableMeshComponent.md#getcurrentskinweightprofilename)
- [GetDeltaTransformFromRefPose](ue_ue.PoseableMeshComponent.md#getdeltatransformfromrefpose)
- [GetForcedLOD](ue_ue.PoseableMeshComponent.md#getforcedlod)
- [GetForwardVector](ue_ue.PoseableMeshComponent.md#getforwardvector)
- [GetGenerateOverlapEvents](ue_ue.PoseableMeshComponent.md#getgenerateoverlapevents)
- [GetInertiaTensor](ue_ue.PoseableMeshComponent.md#getinertiatensor)
- [GetLinearDamping](ue_ue.PoseableMeshComponent.md#getlineardamping)
- [GetMass](ue_ue.PoseableMeshComponent.md#getmass)
- [GetMassScale](ue_ue.PoseableMeshComponent.md#getmassscale)
- [GetMaterial](ue_ue.PoseableMeshComponent.md#getmaterial)
- [GetMaterialFromCollisionFaceIndex](ue_ue.PoseableMeshComponent.md#getmaterialfromcollisionfaceindex)
- [GetMaterialIndex](ue_ue.PoseableMeshComponent.md#getmaterialindex)
- [GetMaterialSlotNames](ue_ue.PoseableMeshComponent.md#getmaterialslotnames)
- [GetMaterials](ue_ue.PoseableMeshComponent.md#getmaterials)
- [GetName](ue_ue.PoseableMeshComponent.md#getname)
- [GetNumBones](ue_ue.PoseableMeshComponent.md#getnumbones)
- [GetNumChildrenComponents](ue_ue.PoseableMeshComponent.md#getnumchildrencomponents)
- [GetNumLODs](ue_ue.PoseableMeshComponent.md#getnumlods)
- [GetNumMaterials](ue_ue.PoseableMeshComponent.md#getnummaterials)
- [GetOuter](ue_ue.PoseableMeshComponent.md#getouter)
- [GetOverlappingActors](ue_ue.PoseableMeshComponent.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.PoseableMeshComponent.md#getoverlappingcomponents)
- [GetOwner](ue_ue.PoseableMeshComponent.md#getowner)
- [GetParentBone](ue_ue.PoseableMeshComponent.md#getparentbone)
- [GetParentComponents](ue_ue.PoseableMeshComponent.md#getparentcomponents)
- [GetPhysicsAngularVelocity](ue_ue.PoseableMeshComponent.md#getphysicsangularvelocity)
- [GetPhysicsAngularVelocityInDegrees](ue_ue.PoseableMeshComponent.md#getphysicsangularvelocityindegrees)
- [GetPhysicsAngularVelocityInRadians](ue_ue.PoseableMeshComponent.md#getphysicsangularvelocityinradians)
- [GetPhysicsLinearVelocity](ue_ue.PoseableMeshComponent.md#getphysicslinearvelocity)
- [GetPhysicsLinearVelocityAtPoint](ue_ue.PoseableMeshComponent.md#getphysicslinearvelocityatpoint)
- [GetPhysicsVolume](ue_ue.PoseableMeshComponent.md#getphysicsvolume)
- [GetRefPosePosition](ue_ue.PoseableMeshComponent.md#getrefposeposition)
- [GetRelativeTransform](ue_ue.PoseableMeshComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.PoseableMeshComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.PoseableMeshComponent.md#getshouldupdatephysicsvolume)
- [GetSocketBoneName](ue_ue.PoseableMeshComponent.md#getsocketbonename)
- [GetSocketLocation](ue_ue.PoseableMeshComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.PoseableMeshComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.PoseableMeshComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.PoseableMeshComponent.md#getsockettransform)
- [GetTwistAndSwingAngleOfDeltaRotationFromRefPose](ue_ue.PoseableMeshComponent.md#gettwistandswingangleofdeltarotationfromrefpose)
- [GetUpVector](ue_ue.PoseableMeshComponent.md#getupvector)
- [GetWalkableSlopeOverride](ue_ue.PoseableMeshComponent.md#getwalkableslopeoverride)
- [GetWorld](ue_ue.PoseableMeshComponent.md#getworld)
- [HideBoneByName](ue_ue.PoseableMeshComponent.md#hidebonebyname)
- [IgnoreActorWhenMoving](ue_ue.PoseableMeshComponent.md#ignoreactorwhenmoving)
- [IgnoreComponentWhenMoving](ue_ue.PoseableMeshComponent.md#ignorecomponentwhenmoving)
- [IsActive](ue_ue.PoseableMeshComponent.md#isactive)
- [IsAnyRigidBodyAwake](ue_ue.PoseableMeshComponent.md#isanyrigidbodyawake)
- [IsAnySimulatingPhysics](ue_ue.PoseableMeshComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.PoseableMeshComponent.md#isbeingdestroyed)
- [IsBoneHiddenByName](ue_ue.PoseableMeshComponent.md#isbonehiddenbyname)
- [IsComponentTickEnabled](ue_ue.PoseableMeshComponent.md#iscomponenttickenabled)
- [IsGravityEnabled](ue_ue.PoseableMeshComponent.md#isgravityenabled)
- [IsMaterialSectionShown](ue_ue.PoseableMeshComponent.md#ismaterialsectionshown)
- [IsMaterialSlotNameValid](ue_ue.PoseableMeshComponent.md#ismaterialslotnamevalid)
- [IsOverlappingActor](ue_ue.PoseableMeshComponent.md#isoverlappingactor)
- [IsOverlappingComponent](ue_ue.PoseableMeshComponent.md#isoverlappingcomponent)
- [IsSimulatingPhysics](ue_ue.PoseableMeshComponent.md#issimulatingphysics)
- [IsUsingSkinWeightProfile](ue_ue.PoseableMeshComponent.md#isusingskinweightprofile)
- [IsVisible](ue_ue.PoseableMeshComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.PoseableMeshComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.PoseableMeshComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.PoseableMeshComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.PoseableMeshComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.PoseableMeshComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.PoseableMeshComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.PoseableMeshComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.PoseableMeshComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.PoseableMeshComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.PoseableMeshComponent.md#k2_attachtocomponent)
- [K2\_BoxOverlapComponent](ue_ue.PoseableMeshComponent.md#k2_boxoverlapcomponent)
- [K2\_DestroyComponent](ue_ue.PoseableMeshComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.PoseableMeshComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.PoseableMeshComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.PoseableMeshComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.PoseableMeshComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.PoseableMeshComponent.md#k2_getcomponenttoworld)
- [K2\_IsCollisionEnabled](ue_ue.PoseableMeshComponent.md#k2_iscollisionenabled)
- [K2\_IsPhysicsCollisionEnabled](ue_ue.PoseableMeshComponent.md#k2_isphysicscollisionenabled)
- [K2\_IsQueryCollisionEnabled](ue_ue.PoseableMeshComponent.md#k2_isquerycollisionenabled)
- [K2\_LineTraceComponent](ue_ue.PoseableMeshComponent.md#k2_linetracecomponent)
- [K2\_SetRelativeLocation](ue_ue.PoseableMeshComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.PoseableMeshComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.PoseableMeshComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.PoseableMeshComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.PoseableMeshComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.PoseableMeshComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.PoseableMeshComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.PoseableMeshComponent.md#k2_setworldtransform)
- [K2\_SphereOverlapComponent](ue_ue.PoseableMeshComponent.md#k2_sphereoverlapcomponent)
- [K2\_SphereTraceComponent](ue_ue.PoseableMeshComponent.md#k2_spheretracecomponent)
- [OnRep\_AttachChildren](ue_ue.PoseableMeshComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.PoseableMeshComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.PoseableMeshComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.PoseableMeshComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.PoseableMeshComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.PoseableMeshComponent.md#onrep_visibility)
- [PrestreamTextures](ue_ue.PoseableMeshComponent.md#prestreamtextures)
- [PutRigidBodyToSleep](ue_ue.PoseableMeshComponent.md#putrigidbodytosleep)
- [ReceiveBeginPlay](ue_ue.PoseableMeshComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.PoseableMeshComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.PoseableMeshComponent.md#receivetick)
- [RegisterComponent](ue_ue.PoseableMeshComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.PoseableMeshComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PoseableMeshComponent.md#removetickprerequisitecomponent)
- [ResetBoneTransformByName](ue_ue.PoseableMeshComponent.md#resetbonetransformbyname)
- [ResetRelativeTransform](ue_ue.PoseableMeshComponent.md#resetrelativetransform)
- [ScaleByMomentOfInertia](ue_ue.PoseableMeshComponent.md#scalebymomentofinertia)
- [SetAbsolute](ue_ue.PoseableMeshComponent.md#setabsolute)
- [SetActive](ue_ue.PoseableMeshComponent.md#setactive)
- [SetAllMassScale](ue_ue.PoseableMeshComponent.md#setallmassscale)
- [SetAllPhysicsAngularVelocityInDegrees](ue_ue.PoseableMeshComponent.md#setallphysicsangularvelocityindegrees)
- [SetAllPhysicsAngularVelocityInRadians](ue_ue.PoseableMeshComponent.md#setallphysicsangularvelocityinradians)
- [SetAllPhysicsLinearVelocity](ue_ue.PoseableMeshComponent.md#setallphysicslinearvelocity)
- [SetAllUseCCD](ue_ue.PoseableMeshComponent.md#setalluseccd)
- [SetAngularDamping](ue_ue.PoseableMeshComponent.md#setangulardamping)
- [SetAutoActivate](ue_ue.PoseableMeshComponent.md#setautoactivate)
- [SetBoneLocationByName](ue_ue.PoseableMeshComponent.md#setbonelocationbyname)
- [SetBoneRotationByName](ue_ue.PoseableMeshComponent.md#setbonerotationbyname)
- [SetBoneScaleByName](ue_ue.PoseableMeshComponent.md#setbonescalebyname)
- [SetBoneTransformByName](ue_ue.PoseableMeshComponent.md#setbonetransformbyname)
- [SetBoundsScale](ue_ue.PoseableMeshComponent.md#setboundsscale)
- [SetCapsuleIndirectShadowMinVisibility](ue_ue.PoseableMeshComponent.md#setcapsuleindirectshadowminvisibility)
- [SetCastCapsuleDirectShadow](ue_ue.PoseableMeshComponent.md#setcastcapsuledirectshadow)
- [SetCastCapsuleIndirectShadow](ue_ue.PoseableMeshComponent.md#setcastcapsuleindirectshadow)
- [SetCastInsetShadow](ue_ue.PoseableMeshComponent.md#setcastinsetshadow)
- [SetCastShadow](ue_ue.PoseableMeshComponent.md#setcastshadow)
- [SetCenterOfMass](ue_ue.PoseableMeshComponent.md#setcenterofmass)
- [SetCollisionEnabled](ue_ue.PoseableMeshComponent.md#setcollisionenabled)
- [SetCollisionObjectType](ue_ue.PoseableMeshComponent.md#setcollisionobjecttype)
- [SetCollisionProfileName](ue_ue.PoseableMeshComponent.md#setcollisionprofilename)
- [SetCollisionResponseToAllChannels](ue_ue.PoseableMeshComponent.md#setcollisionresponsetoallchannels)
- [SetCollisionResponseToChannel](ue_ue.PoseableMeshComponent.md#setcollisionresponsetochannel)
- [SetComponentTickEnabled](ue_ue.PoseableMeshComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.PoseableMeshComponent.md#setcomponenttickinterval)
- [SetConstraintMode](ue_ue.PoseableMeshComponent.md#setconstraintmode)
- [SetCullDistance](ue_ue.PoseableMeshComponent.md#setculldistance)
- [SetCustomDepthStencilValue](ue_ue.PoseableMeshComponent.md#setcustomdepthstencilvalue)
- [SetCustomDepthStencilWriteMask](ue_ue.PoseableMeshComponent.md#setcustomdepthstencilwritemask)
- [SetCustomPrimitiveDataFloat](ue_ue.PoseableMeshComponent.md#setcustomprimitivedatafloat)
- [SetCustomPrimitiveDataVector2](ue_ue.PoseableMeshComponent.md#setcustomprimitivedatavector2)
- [SetCustomPrimitiveDataVector3](ue_ue.PoseableMeshComponent.md#setcustomprimitivedatavector3)
- [SetCustomPrimitiveDataVector4](ue_ue.PoseableMeshComponent.md#setcustomprimitivedatavector4)
- [SetEnableGravity](ue_ue.PoseableMeshComponent.md#setenablegravity)
- [SetExcludeFromLightAttachmentGroup](ue_ue.PoseableMeshComponent.md#setexcludefromlightattachmentgroup)
- [SetForcedLOD](ue_ue.PoseableMeshComponent.md#setforcedlod)
- [SetGenerateOverlapEvents](ue_ue.PoseableMeshComponent.md#setgenerateoverlapevents)
- [SetHiddenInGame](ue_ue.PoseableMeshComponent.md#sethiddeningame)
- [SetIsReplicated](ue_ue.PoseableMeshComponent.md#setisreplicated)
- [SetLightAttachmentsAsGroup](ue_ue.PoseableMeshComponent.md#setlightattachmentsasgroup)
- [SetLinearDamping](ue_ue.PoseableMeshComponent.md#setlineardamping)
- [SetMassOverrideInKg](ue_ue.PoseableMeshComponent.md#setmassoverrideinkg)
- [SetMassScale](ue_ue.PoseableMeshComponent.md#setmassscale)
- [SetMasterPoseComponent](ue_ue.PoseableMeshComponent.md#setmasterposecomponent)
- [SetMaterial](ue_ue.PoseableMeshComponent.md#setmaterial)
- [SetMaterialByName](ue_ue.PoseableMeshComponent.md#setmaterialbyname)
- [SetMinLOD](ue_ue.PoseableMeshComponent.md#setminlod)
- [SetMobility](ue_ue.PoseableMeshComponent.md#setmobility)
- [SetNotifyRigidBodyCollision](ue_ue.PoseableMeshComponent.md#setnotifyrigidbodycollision)
- [SetOnlyOwnerSee](ue_ue.PoseableMeshComponent.md#setonlyownersee)
- [SetOwnerNoSee](ue_ue.PoseableMeshComponent.md#setownernosee)
- [SetPhysMaterialOverride](ue_ue.PoseableMeshComponent.md#setphysmaterialoverride)
- [SetPhysicsAngularVelocity](ue_ue.PoseableMeshComponent.md#setphysicsangularvelocity)
- [SetPhysicsAngularVelocityInDegrees](ue_ue.PoseableMeshComponent.md#setphysicsangularvelocityindegrees)
- [SetPhysicsAngularVelocityInRadians](ue_ue.PoseableMeshComponent.md#setphysicsangularvelocityinradians)
- [SetPhysicsAsset](ue_ue.PoseableMeshComponent.md#setphysicsasset)
- [SetPhysicsLinearVelocity](ue_ue.PoseableMeshComponent.md#setphysicslinearvelocity)
- [SetPhysicsMaxAngularVelocity](ue_ue.PoseableMeshComponent.md#setphysicsmaxangularvelocity)
- [SetPhysicsMaxAngularVelocityInDegrees](ue_ue.PoseableMeshComponent.md#setphysicsmaxangularvelocityindegrees)
- [SetPhysicsMaxAngularVelocityInRadians](ue_ue.PoseableMeshComponent.md#setphysicsmaxangularvelocityinradians)
- [SetReceivesDecals](ue_ue.PoseableMeshComponent.md#setreceivesdecals)
- [SetRelativeScale3D](ue_ue.PoseableMeshComponent.md#setrelativescale3d)
- [SetRenderCustomDepth](ue_ue.PoseableMeshComponent.md#setrendercustomdepth)
- [SetRenderInMainPass](ue_ue.PoseableMeshComponent.md#setrenderinmainpass)
- [SetRenderStatic](ue_ue.PoseableMeshComponent.md#setrenderstatic)
- [SetScalarParameterValueOnMaterials](ue_ue.PoseableMeshComponent.md#setscalarparametervalueonmaterials)
- [SetShouldUpdatePhysicsVolume](ue_ue.PoseableMeshComponent.md#setshouldupdatephysicsvolume)
- [SetSimulatePhysics](ue_ue.PoseableMeshComponent.md#setsimulatephysics)
- [SetSingleSampleShadowFromStationaryLights](ue_ue.PoseableMeshComponent.md#setsinglesampleshadowfromstationarylights)
- [SetSkeletalMesh](ue_ue.PoseableMeshComponent.md#setskeletalmesh)
- [SetSkinWeightOverride](ue_ue.PoseableMeshComponent.md#setskinweightoverride)
- [SetSkinWeightProfile](ue_ue.PoseableMeshComponent.md#setskinweightprofile)
- [SetTickGroup](ue_ue.PoseableMeshComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PoseableMeshComponent.md#settickablewhenpaused)
- [SetTranslucentSortPriority](ue_ue.PoseableMeshComponent.md#settranslucentsortpriority)
- [SetUseCCD](ue_ue.PoseableMeshComponent.md#setuseccd)
- [SetVectorParameterValueOnMaterials](ue_ue.PoseableMeshComponent.md#setvectorparametervalueonmaterials)
- [SetVertexColorOverride\_LinearColor](ue_ue.PoseableMeshComponent.md#setvertexcoloroverride_linearcolor)
- [SetVisibility](ue_ue.PoseableMeshComponent.md#setvisibility)
- [SetWalkableSlopeOverride](ue_ue.PoseableMeshComponent.md#setwalkableslopeoverride)
- [SetWorldScale3D](ue_ue.PoseableMeshComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.PoseableMeshComponent.md#setupattachment)
- [ShowAllMaterialSections](ue_ue.PoseableMeshComponent.md#showallmaterialsections)
- [ShowMaterialSection](ue_ue.PoseableMeshComponent.md#showmaterialsection)
- [SnapTo](ue_ue.PoseableMeshComponent.md#snapto)
- [ToggleActive](ue_ue.PoseableMeshComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.PoseableMeshComponent.md#togglevisibility)
- [TransformFromBoneSpace](ue_ue.PoseableMeshComponent.md#transformfrombonespace)
- [TransformToBoneSpace](ue_ue.PoseableMeshComponent.md#transformtobonespace)
- [UnHideBoneByName](ue_ue.PoseableMeshComponent.md#unhidebonebyname)
- [UnloadSkinWeightProfile](ue_ue.PoseableMeshComponent.md#unloadskinweightprofile)
- [WakeAllRigidBodies](ue_ue.PoseableMeshComponent.md#wakeallrigidbodies)
- [WakeRigidBody](ue_ue.PoseableMeshComponent.md#wakerigidbody)
- [Find](ue_ue.PoseableMeshComponent.md#find)
- [Load](ue_ue.PoseableMeshComponent.md#load)
- [StaticClass](ue_ue.PoseableMeshComponent.md#staticclass)

## Constructors

### constructor

• **new PoseableMeshComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[constructor](ue_ue.SkinnedMeshComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:58231](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58231)

## Properties

### AlwaysLoadOnClient

• **AlwaysLoadOnClient**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AlwaysLoadOnClient](ue_ue.SkinnedMeshComponent.md#alwaysloadonclient)

#### Defined in

[ue/ue.d.ts:12608](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12608)

___

### AlwaysLoadOnServer

• **AlwaysLoadOnServer**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AlwaysLoadOnServer](ue_ue.SkinnedMeshComponent.md#alwaysloadonserver)

#### Defined in

[ue/ue.d.ts:12609](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12609)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AssetUserData](ue_ue.SkinnedMeshComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L291)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AttachChildren](ue_ue.SkinnedMeshComponent.md#attachchildren)

#### Defined in

[ue/ue.d.ts:12873](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12873)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AttachParent](ue_ue.SkinnedMeshComponent.md#attachparent)

#### Defined in

[ue/ue.d.ts:12871](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12871)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AttachSocketName](ue_ue.SkinnedMeshComponent.md#attachsocketname)

#### Defined in

[ue/ue.d.ts:12872](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12872)

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[BodyInstance](ue_ue.SkinnedMeshComponent.md#bodyinstance)

#### Defined in

[ue/ue.d.ts:12630](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12630)

___

### BoundsScale

• **BoundsScale**: `number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[BoundsScale](ue_ue.SkinnedMeshComponent.md#boundsscale)

#### Defined in

[ue/ue.d.ts:12627](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12627)

___

### CachedMaxDrawDistance

• **CachedMaxDrawDistance**: `number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CachedMaxDrawDistance](ue_ue.SkinnedMeshComponent.md#cachedmaxdrawdistance)

#### Defined in

[ue/ue.d.ts:12557](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12557)

___

### CachedWorldSpaceBounds

• **CachedWorldSpaceBounds**: [`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CachedWorldSpaceBounds](ue_ue.SkinnedMeshComponent.md#cachedworldspacebounds)

#### Defined in

[ue/ue.d.ts:4647](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4647)

___

### CachedWorldToLocalTransform

• **CachedWorldToLocalTransform**: [`Matrix`](ue_ue.Matrix.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CachedWorldToLocalTransform](ue_ue.SkinnedMeshComponent.md#cachedworldtolocaltransform)

#### Defined in

[ue/ue.d.ts:4648](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4648)

___

### CanBeCharacterBase

• **CanBeCharacterBase**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CanBeCharacterBase](ue_ue.SkinnedMeshComponent.md#canbecharacterbase)

#### Defined in

[ue/ue.d.ts:12613](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12613)

___

### CanCharacterStepUpOn

• **CanCharacterStepUpOn**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CanCharacterStepUpOn](ue_ue.SkinnedMeshComponent.md#cancharacterstepupon)

#### Defined in

[ue/ue.d.ts:12614](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12614)

___

### CapsuleIndirectShadowMinVisibility

• **CapsuleIndirectShadowMinVisibility**: `number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CapsuleIndirectShadowMinVisibility](ue_ue.SkinnedMeshComponent.md#capsuleindirectshadowminvisibility)

#### Defined in

[ue/ue.d.ts:4646](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4646)

___

### CastShadow

• **CastShadow**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CastShadow](ue_ue.SkinnedMeshComponent.md#castshadow)

#### Defined in

[ue/ue.d.ts:12587](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12587)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ClientAttachedChildren](ue_ue.SkinnedMeshComponent.md#clientattachedchildren)

#### Defined in

[ue/ue.d.ts:12874](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12874)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ComponentTags](ue_ue.SkinnedMeshComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L290)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ComponentVelocity](ue_ue.SkinnedMeshComponent.md#componentvelocity)

#### Defined in

[ue/ue.d.ts:12878](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12878)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CreationMethod](ue_ue.SkinnedMeshComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L302)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CustomDepthStencilValue](ue_ue.SkinnedMeshComponent.md#customdepthstencilvalue)

#### Defined in

[ue/ue.d.ts:12617](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12617)

___

### CustomDepthStencilWriteMask

• **CustomDepthStencilWriteMask**: [`ERendererStencilMask`](../enums/ue_ue.ERendererStencilMask.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CustomDepthStencilWriteMask](ue_ue.SkinnedMeshComponent.md#customdepthstencilwritemask)

#### Defined in

[ue/ue.d.ts:12616](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12616)

___

### CustomPrimitiveData

• **CustomPrimitiveData**: [`CustomPrimitiveData`](ue_ue.CustomPrimitiveData.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CustomPrimitiveData](ue_ue.SkinnedMeshComponent.md#customprimitivedata)

#### Defined in

[ue/ue.d.ts:12618](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12618)

___

### DepthPriorityGroup

• **DepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[DepthPriorityGroup](ue_ue.SkinnedMeshComponent.md#depthprioritygroup)

#### Defined in

[ue/ue.d.ts:12558](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12558)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[DetailMode](ue_ue.SkinnedMeshComponent.md#detailmode)

#### Defined in

[ue/ue.d.ts:12893](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12893)

___

### ExcludeForSpecificHLODLevels

• **ExcludeForSpecificHLODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ExcludeForSpecificHLODLevels](ue_ue.SkinnedMeshComponent.md#excludeforspecifichlodlevels)

#### Defined in

[ue/ue.d.ts:12562](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12562)

___

### ForcedLodModel

• **ForcedLodModel**: `number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ForcedLodModel](ue_ue.SkinnedMeshComponent.md#forcedlodmodel)

#### Defined in

[ue/ue.d.ts:4620](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4620)

___

### IndirectLightingCacheQuality

• **IndirectLightingCacheQuality**: [`EIndirectLightingCacheQuality`](../enums/ue_ue.EIndirectLightingCacheQuality.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[IndirectLightingCacheQuality](ue_ue.SkinnedMeshComponent.md#indirectlightingcachequality)

#### Defined in

[ue/ue.d.ts:12560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12560)

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[LDMaxDrawDistance](ue_ue.SkinnedMeshComponent.md#ldmaxdrawdistance)

#### Defined in

[ue/ue.d.ts:12556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12556)

___

### LODInfo

• **LODInfo**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SkelMeshComponentLODInfo`](ue_ue.SkelMeshComponentLODInfo.md)\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[LODInfo](ue_ue.SkinnedMeshComponent.md#lodinfo)

#### Defined in

[ue/ue.d.ts:4623](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4623)

___

### LODParentPrimitive

• **LODParentPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[LODParentPrimitive](ue_ue.SkinnedMeshComponent.md#lodparentprimitive)

#### Defined in

[ue/ue.d.ts:12644](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12644)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[LightingChannels](ue_ue.SkinnedMeshComponent.md#lightingchannels)

#### Defined in

[ue/ue.d.ts:12615](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12615)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[LightmapType](ue_ue.SkinnedMeshComponent.md#lightmaptype)

#### Defined in

[ue/ue.d.ts:12561](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12561)

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[LpvBiasMultiplier](ue_ue.SkinnedMeshComponent.md#lpvbiasmultiplier)

#### Defined in

[ue/ue.d.ts:12626](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12626)

___

### MasterPoseComponent

• **MasterPoseComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`SkinnedMeshComponent`](ue_ue.SkinnedMeshComponent.md)\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[MasterPoseComponent](ue_ue.SkinnedMeshComponent.md#masterposecomponent)

#### Defined in

[ue/ue.d.ts:4617](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4617)

___

### MinDrawDistance

• **MinDrawDistance**: `number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[MinDrawDistance](ue_ue.SkinnedMeshComponent.md#mindrawdistance)

#### Defined in

[ue/ue.d.ts:12555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12555)

___

### MinLodModel

• **MinLodModel**: `number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[MinLodModel](ue_ue.SkinnedMeshComponent.md#minlodmodel)

#### Defined in

[ue/ue.d.ts:4621](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4621)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[Mobility](ue_ue.SkinnedMeshComponent.md#mobility)

#### Defined in

[ue/ue.d.ts:12892](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12892)

___

### MoveIgnoreActors

• **MoveIgnoreActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[MoveIgnoreActors](ue_ue.SkinnedMeshComponent.md#moveignoreactors)

#### Defined in

[ue/ue.d.ts:12628](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12628)

___

### MoveIgnoreComponents

• **MoveIgnoreComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[MoveIgnoreComponents](ue_ue.SkinnedMeshComponent.md#moveignorecomponents)

#### Defined in

[ue/ue.d.ts:12629](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12629)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnBeginCursorOver](ue_ue.SkinnedMeshComponent.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:12636](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12636)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnClicked](ue_ue.SkinnedMeshComponent.md#onclicked)

#### Defined in

[ue/ue.d.ts:12638](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12638)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnComponentActivated](ue_ue.SkinnedMeshComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L303)

___

### OnComponentBeginOverlap

• **OnComponentBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`, `bFromSweep`: `boolean`, `SweepResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnComponentBeginOverlap](ue_ue.SkinnedMeshComponent.md#oncomponentbeginoverlap)

#### Defined in

[ue/ue.d.ts:12632](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12632)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnComponentDeactivated](ue_ue.SkinnedMeshComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L304)

___

### OnComponentEndOverlap

• **OnComponentEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`) => `void`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnComponentEndOverlap](ue_ue.SkinnedMeshComponent.md#oncomponentendoverlap)

#### Defined in

[ue/ue.d.ts:12633](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12633)

___

### OnComponentHit

• **OnComponentHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`HitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnComponentHit](ue_ue.SkinnedMeshComponent.md#oncomponenthit)

#### Defined in

[ue/ue.d.ts:12631](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12631)

___

### OnComponentSleep

• **OnComponentSleep**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SleepingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnComponentSleep](ue_ue.SkinnedMeshComponent.md#oncomponentsleep)

#### Defined in

[ue/ue.d.ts:12635](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12635)

___

### OnComponentWake

• **OnComponentWake**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`WakingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnComponentWake](ue_ue.SkinnedMeshComponent.md#oncomponentwake)

#### Defined in

[ue/ue.d.ts:12634](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12634)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnEndCursorOver](ue_ue.SkinnedMeshComponent.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:12637](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12637)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnInputTouchBegin](ue_ue.SkinnedMeshComponent.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:12640](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12640)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnInputTouchEnd](ue_ue.SkinnedMeshComponent.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:12641](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12641)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnInputTouchEnter](ue_ue.SkinnedMeshComponent.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:12642](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12642)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnInputTouchLeave](ue_ue.SkinnedMeshComponent.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:12643](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12643)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnReleased](ue_ue.SkinnedMeshComponent.md#onreleased)

#### Defined in

[ue/ue.d.ts:12639](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12639)

___

### OverrideMaterials

• **OverrideMaterials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OverrideMaterials](ue_ue.SkinnedMeshComponent.md#overridematerials)

#### Defined in

[ue/ue.d.ts:2296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2296)

___

### PhysicsAssetOverride

• **PhysicsAssetOverride**: [`PhysicsAsset`](ue_ue.PhysicsAsset.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[PhysicsAssetOverride](ue_ue.SkinnedMeshComponent.md#physicsassetoverride)

#### Defined in

[ue/ue.d.ts:4619](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4619)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[PhysicsVolume](ue_ue.SkinnedMeshComponent.md#physicsvolume)

#### Defined in

[ue/ue.d.ts:12870](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12870)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.SkinnedMeshComponent.md#physicsvolumechangeddelegate)

#### Defined in

[ue/ue.d.ts:12894](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12894)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[PrimaryComponentTick](ue_ue.SkinnedMeshComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L289)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[RelativeLocation](ue_ue.SkinnedMeshComponent.md#relativelocation)

#### Defined in

[ue/ue.d.ts:12875](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12875)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[RelativeRotation](ue_ue.SkinnedMeshComponent.md#relativerotation)

#### Defined in

[ue/ue.d.ts:12876](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12876)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[RelativeScale3D](ue_ue.SkinnedMeshComponent.md#relativescale3d)

#### Defined in

[ue/ue.d.ts:12877](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12877)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[RuntimeVirtualTextures](ue_ue.SkinnedMeshComponent.md#runtimevirtualtextures)

#### Defined in

[ue/ue.d.ts:12621](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12621)

___

### SkeletalMesh

• **SkeletalMesh**: [`SkeletalMesh`](ue_ue.SkeletalMesh.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SkeletalMesh](ue_ue.SkinnedMeshComponent.md#skeletalmesh)

#### Defined in

[ue/ue.d.ts:4616](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4616)

___

### StreamingDistanceMultiplier

• **StreamingDistanceMultiplier**: `number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[StreamingDistanceMultiplier](ue_ue.SkinnedMeshComponent.md#streamingdistancemultiplier)

#### Defined in

[ue/ue.d.ts:4622](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4622)

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[TranslucencySortPriority](ue_ue.SkinnedMeshComponent.md#translucencysortpriority)

#### Defined in

[ue/ue.d.ts:12619](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12619)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[UCSModifiedProperties](ue_ue.SkinnedMeshComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L305)

___

### ViewOwnerDepthPriorityGroup

• **ViewOwnerDepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ViewOwnerDepthPriorityGroup](ue_ue.SkinnedMeshComponent.md#viewownerdepthprioritygroup)

#### Defined in

[ue/ue.d.ts:12559](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12559)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[VirtualTextureCullMips](ue_ue.SkinnedMeshComponent.md#virtualtexturecullmips)

#### Defined in

[ue/ue.d.ts:12623](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12623)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[VirtualTextureLodBias](ue_ue.SkinnedMeshComponent.md#virtualtexturelodbias)

#### Defined in

[ue/ue.d.ts:12622](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12622)

___

### VirtualTextureMinCoverage

• **VirtualTextureMinCoverage**: `number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[VirtualTextureMinCoverage](ue_ue.SkinnedMeshComponent.md#virtualtexturemincoverage)

#### Defined in

[ue/ue.d.ts:12624](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12624)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[VirtualTextureRenderPassType](ue_ue.SkinnedMeshComponent.md#virtualtexturerenderpasstype)

#### Defined in

[ue/ue.d.ts:12625](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12625)

___

### VisibilityBasedAnimTickOption

• **VisibilityBasedAnimTickOption**: [`EVisibilityBasedAnimTickOption`](../enums/ue_ue.EVisibilityBasedAnimTickOption.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[VisibilityBasedAnimTickOption](ue_ue.SkinnedMeshComponent.md#visibilitybasedanimtickoption)

#### Defined in

[ue/ue.d.ts:4624](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4624)

___

### VisibilityId

• **VisibilityId**: `number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[VisibilityId](ue_ue.SkinnedMeshComponent.md#visibilityid)

#### Defined in

[ue/ue.d.ts:12620](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12620)

___

### WireframeColor

• **WireframeColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[WireframeColor](ue_ue.SkinnedMeshComponent.md#wireframecolor)

#### Defined in

[ue/ue.d.ts:4618](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4618)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[__tid_ActorComponent__](ue_ue.SkinnedMeshComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L336)

___

### \_\_tid\_MeshComponent\_\_

• **\_\_tid\_MeshComponent\_\_**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[__tid_MeshComponent__](ue_ue.SkinnedMeshComponent.md#__tid_meshcomponent__)

#### Defined in

[ue/ue.d.ts:2309](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2309)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[__tid_Object__](ue_ue.SkinnedMeshComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PoseableMeshComponent\_\_

• **\_\_tid\_PoseableMeshComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:58246](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58246)

___

### \_\_tid\_PrimitiveComponent\_\_

• **\_\_tid\_PrimitiveComponent\_\_**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[__tid_PrimitiveComponent__](ue_ue.SkinnedMeshComponent.md#__tid_primitivecomponent__)

#### Defined in

[ue/ue.d.ts:12761](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12761)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[__tid_SceneComponent__](ue_ue.SkinnedMeshComponent.md#__tid_scenecomponent__)

#### Defined in

[ue/ue.d.ts:12961](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12961)

___

### \_\_tid\_SkinnedMeshComponent\_\_

• **\_\_tid\_SkinnedMeshComponent\_\_**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[__tid_SkinnedMeshComponent__](ue_ue.SkinnedMeshComponent.md#__tid_skinnedmeshcomponent__)

#### Defined in

[ue/ue.d.ts:4691](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4691)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bAbsoluteLocation](ue_ue.SkinnedMeshComponent.md#babsolutelocation)

#### Defined in

[ue/ue.d.ts:12880](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12880)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bAbsoluteRotation](ue_ue.SkinnedMeshComponent.md#babsoluterotation)

#### Defined in

[ue/ue.d.ts:12881](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12881)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bAbsoluteScale](ue_ue.SkinnedMeshComponent.md#babsolutescale)

#### Defined in

[ue/ue.d.ts:12882](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12882)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bAffectDistanceFieldLighting](ue_ue.SkinnedMeshComponent.md#baffectdistancefieldlighting)

#### Defined in

[ue/ue.d.ts:12589](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12589)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bAffectDynamicIndirectLighting](ue_ue.SkinnedMeshComponent.md#baffectdynamicindirectlighting)

#### Defined in

[ue/ue.d.ts:12588](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12588)

___

### bAllowCullDistanceVolume

• **bAllowCullDistanceVolume**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bAllowCullDistanceVolume](ue_ue.SkinnedMeshComponent.md#ballowculldistancevolume)

#### Defined in

[ue/ue.d.ts:12573](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12573)

___

### bAlwaysCreatePhysicsState

• **bAlwaysCreatePhysicsState**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bAlwaysCreatePhysicsState](ue_ue.SkinnedMeshComponent.md#balwayscreatephysicsstate)

#### Defined in

[ue/ue.d.ts:12567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12567)

___

### bApplyImpulseOnDamage

• **bApplyImpulseOnDamage**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bApplyImpulseOnDamage](ue_ue.SkinnedMeshComponent.md#bapplyimpulseondamage)

#### Defined in

[ue/ue.d.ts:12606](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12606)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bAutoActivate](ue_ue.SkinnedMeshComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L296)

___

### bBatchImpostersAsInstances

• **bBatchImpostersAsInstances**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bBatchImpostersAsInstances](ue_ue.SkinnedMeshComponent.md#bbatchimpostersasinstances)

#### Defined in

[ue/ue.d.ts:12565](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12565)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.SkinnedMeshComponent.md#bboundschangetriggersstreamingdatarebuild)

#### Defined in

[ue/ue.d.ts:12889](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12889)

___

### bCPUSkinning

• **bCPUSkinning**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bCPUSkinning](ue_ue.SkinnedMeshComponent.md#bcpuskinning)

#### Defined in

[ue/ue.d.ts:4639](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4639)

___

### bCachedLocalBoundsUpToDate

• **bCachedLocalBoundsUpToDate**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bCachedLocalBoundsUpToDate](ue_ue.SkinnedMeshComponent.md#bcachedlocalboundsuptodate)

#### Defined in

[ue/ue.d.ts:4644](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4644)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bCanEverAffectNavigation](ue_ue.SkinnedMeshComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L299)

___

### bCanHighlightSelectedSections

• **bCanHighlightSelectedSections**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bCanHighlightSelectedSections](ue_ue.SkinnedMeshComponent.md#bcanhighlightselectedsections)

#### Defined in

[ue/ue.d.ts:4635](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4635)

___

### bCastCapsuleDirectShadow

• **bCastCapsuleDirectShadow**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bCastCapsuleDirectShadow](ue_ue.SkinnedMeshComponent.md#bcastcapsuledirectshadow)

#### Defined in

[ue/ue.d.ts:4637](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4637)

___

### bCastCapsuleIndirectShadow

• **bCastCapsuleIndirectShadow**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bCastCapsuleIndirectShadow](ue_ue.SkinnedMeshComponent.md#bcastcapsuleindirectshadow)

#### Defined in

[ue/ue.d.ts:4638](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4638)

___

### bCastCinematicShadow

• **bCastCinematicShadow**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bCastCinematicShadow](ue_ue.SkinnedMeshComponent.md#bcastcinematicshadow)

#### Defined in

[ue/ue.d.ts:12596](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12596)

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bCastDynamicShadow](ue_ue.SkinnedMeshComponent.md#bcastdynamicshadow)

#### Defined in

[ue/ue.d.ts:12590](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12590)

___

### bCastFarShadow

• **bCastFarShadow**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bCastFarShadow](ue_ue.SkinnedMeshComponent.md#bcastfarshadow)

#### Defined in

[ue/ue.d.ts:12594](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12594)

___

### bCastHiddenShadow

• **bCastHiddenShadow**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bCastHiddenShadow](ue_ue.SkinnedMeshComponent.md#bcasthiddenshadow)

#### Defined in

[ue/ue.d.ts:12597](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12597)

___

### bCastInsetShadow

• **bCastInsetShadow**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bCastInsetShadow](ue_ue.SkinnedMeshComponent.md#bcastinsetshadow)

#### Defined in

[ue/ue.d.ts:12595](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12595)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bCastShadowAsTwoSided](ue_ue.SkinnedMeshComponent.md#bcastshadowastwosided)

#### Defined in

[ue/ue.d.ts:12598](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12598)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bCastStaticShadow](ue_ue.SkinnedMeshComponent.md#bcaststaticshadow)

#### Defined in

[ue/ue.d.ts:12591](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12591)

___

### bCastVolumetricTranslucentShadow

• **bCastVolumetricTranslucentShadow**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bCastVolumetricTranslucentShadow](ue_ue.SkinnedMeshComponent.md#bcastvolumetrictranslucentshadow)

#### Defined in

[ue/ue.d.ts:12592](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12592)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bComponentToWorldUpdated](ue_ue.SkinnedMeshComponent.md#bcomponenttoworldupdated)

#### Defined in

[ue/ue.d.ts:12879](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12879)

___

### bComponentUseFixedSkelBounds

• **bComponentUseFixedSkelBounds**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bComponentUseFixedSkelBounds](ue_ue.SkinnedMeshComponent.md#bcomponentusefixedskelbounds)

#### Defined in

[ue/ue.d.ts:4632](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4632)

___

### bConsiderAllBodiesForBounds

• **bConsiderAllBodiesForBounds**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bConsiderAllBodiesForBounds](ue_ue.SkinnedMeshComponent.md#bconsiderallbodiesforbounds)

#### Defined in

[ue/ue.d.ts:4633](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4633)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bCreatedByConstructionScript](ue_ue.SkinnedMeshComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L294)

___

### bDisableMorphTarget

• **bDisableMorphTarget**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bDisableMorphTarget](ue_ue.SkinnedMeshComponent.md#bdisablemorphtarget)

#### Defined in

[ue/ue.d.ts:4629](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4629)

___

### bDisplayBones

• **bDisplayBones**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bDisplayBones](ue_ue.SkinnedMeshComponent.md#bdisplaybones)

#### Defined in

[ue/ue.d.ts:4628](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4628)

___

### bDisplayDebugUpdateRateOptimizations

• **bDisplayDebugUpdateRateOptimizations**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bDisplayDebugUpdateRateOptimizations](ue_ue.SkinnedMeshComponent.md#bdisplaydebugupdaterateoptimizations)

#### Defined in

[ue/ue.d.ts:4641](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4641)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bEditableWhenInherited](ue_ue.SkinnedMeshComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L298)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bEnableAutoLODGeneration](ue_ue.SkinnedMeshComponent.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:12563](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12563)

___

### bEnableMaterialParameterCaching

• **bEnableMaterialParameterCaching**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bEnableMaterialParameterCaching](ue_ue.SkinnedMeshComponent.md#benablematerialparametercaching)

#### Defined in

[ue/ue.d.ts:2297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2297)

___

### bEnableUpdateRateOptimizations

• **bEnableUpdateRateOptimizations**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bEnableUpdateRateOptimizations](ue_ue.SkinnedMeshComponent.md#benableupdaterateoptimizations)

#### Defined in

[ue/ue.d.ts:4640](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4640)

___

### bExcludeFromLightAttachmentGroup

• **bExcludeFromLightAttachmentGroup**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bExcludeFromLightAttachmentGroup](ue_ue.SkinnedMeshComponent.md#bexcludefromlightattachmentgroup)

#### Defined in

[ue/ue.d.ts:12601](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12601)

___

### bForceMeshObjectUpdate

• **bForceMeshObjectUpdate**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bForceMeshObjectUpdate](ue_ue.SkinnedMeshComponent.md#bforcemeshobjectupdate)

#### Defined in

[ue/ue.d.ts:4645](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4645)

___

### bForceMipStreaming

• **bForceMipStreaming**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bForceMipStreaming](ue_ue.SkinnedMeshComponent.md#bforcemipstreaming)

#### Defined in

[ue/ue.d.ts:12585](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12585)

___

### bForceWireframe

• **bForceWireframe**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bForceWireframe](ue_ue.SkinnedMeshComponent.md#bforcewireframe)

#### Defined in

[ue/ue.d.ts:4627](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4627)

___

### bGenerateOverlapEvents

• **bGenerateOverlapEvents**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bGenerateOverlapEvents](ue_ue.SkinnedMeshComponent.md#bgenerateoverlapevents)

#### Defined in

[ue/ue.d.ts:12568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12568)

___

### bHasCustomNavigableGeometry

• **bHasCustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bHasCustomNavigableGeometry](ue_ue.SkinnedMeshComponent.md#bhascustomnavigablegeometry)

#### Defined in

[ue/ue.d.ts:12612](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12612)

___

### bHasMotionBlurVelocityMeshes

• **bHasMotionBlurVelocityMeshes**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bHasMotionBlurVelocityMeshes](ue_ue.SkinnedMeshComponent.md#bhasmotionblurvelocitymeshes)

#### Defined in

[ue/ue.d.ts:12574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12574)

___

### bHasPerInstanceHitProxies

• **bHasPerInstanceHitProxies**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bHasPerInstanceHitProxies](ue_ue.SkinnedMeshComponent.md#bhasperinstancehitproxies)

#### Defined in

[ue/ue.d.ts:12586](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12586)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bHiddenInGame](ue_ue.SkinnedMeshComponent.md#bhiddeningame)

#### Defined in

[ue/ue.d.ts:12884](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12884)

___

### bHideSkin

• **bHideSkin**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bHideSkin](ue_ue.SkinnedMeshComponent.md#bhideskin)

#### Defined in

[ue/ue.d.ts:4630](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4630)

___

### bIgnoreMasterPoseComponentLOD

• **bIgnoreMasterPoseComponentLOD**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bIgnoreMasterPoseComponentLOD](ue_ue.SkinnedMeshComponent.md#bignoremasterposecomponentlod)

#### Defined in

[ue/ue.d.ts:4643](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4643)

___

### bIgnoreRadialForce

• **bIgnoreRadialForce**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bIgnoreRadialForce](ue_ue.SkinnedMeshComponent.md#bignoreradialforce)

#### Defined in

[ue/ue.d.ts:12605](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12605)

___

### bIgnoreRadialImpulse

• **bIgnoreRadialImpulse**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bIgnoreRadialImpulse](ue_ue.SkinnedMeshComponent.md#bignoreradialimpulse)

#### Defined in

[ue/ue.d.ts:12604](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12604)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bInstanceComponent](ue_ue.SkinnedMeshComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bIsActive](ue_ue.SkinnedMeshComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bIsEditorOnly](ue_ue.SkinnedMeshComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bIsVisualizationComponent](ue_ue.SkinnedMeshComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L301)

___

### bLightAsIfStatic

• **bLightAsIfStatic**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bLightAsIfStatic](ue_ue.SkinnedMeshComponent.md#blightasifstatic)

#### Defined in

[ue/ue.d.ts:12599](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12599)

___

### bLightAttachmentsAsGroup

• **bLightAttachmentsAsGroup**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bLightAttachmentsAsGroup](ue_ue.SkinnedMeshComponent.md#blightattachmentsasgroup)

#### Defined in

[ue/ue.d.ts:12600](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12600)

___

### bMultiBodyOverlap

• **bMultiBodyOverlap**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bMultiBodyOverlap](ue_ue.SkinnedMeshComponent.md#bmultibodyoverlap)

#### Defined in

[ue/ue.d.ts:12569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12569)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bNetAddressable](ue_ue.SkinnedMeshComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L293)

___

### bNeverDistanceCull

• **bNeverDistanceCull**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bNeverDistanceCull](ue_ue.SkinnedMeshComponent.md#bneverdistancecull)

#### Defined in

[ue/ue.d.ts:12566](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12566)

___

### bOnlyOwnerSee

• **bOnlyOwnerSee**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bOnlyOwnerSee](ue_ue.SkinnedMeshComponent.md#bonlyownersee)

#### Defined in

[ue/ue.d.ts:12581](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12581)

___

### bOverrideMinLod

• **bOverrideMinLod**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bOverrideMinLod](ue_ue.SkinnedMeshComponent.md#boverrideminlod)

#### Defined in

[ue/ue.d.ts:4625](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4625)

___

### bOwnerNoSee

• **bOwnerNoSee**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bOwnerNoSee](ue_ue.SkinnedMeshComponent.md#bownernosee)

#### Defined in

[ue/ue.d.ts:12580](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12580)

___

### bPerBoneMotionBlur

• **bPerBoneMotionBlur**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bPerBoneMotionBlur](ue_ue.SkinnedMeshComponent.md#bperbonemotionblur)

#### Defined in

[ue/ue.d.ts:4631](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4631)

___

### bReceiveMobileCSMShadows

• **bReceiveMobileCSMShadows**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bReceiveMobileCSMShadows](ue_ue.SkinnedMeshComponent.md#breceivemobilecsmshadows)

#### Defined in

[ue/ue.d.ts:12602](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12602)

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bReceivesDecals](ue_ue.SkinnedMeshComponent.md#breceivesdecals)

#### Defined in

[ue/ue.d.ts:12579](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12579)

___

### bRecentlyRendered

• **bRecentlyRendered**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bRecentlyRendered](ue_ue.SkinnedMeshComponent.md#brecentlyrendered)

#### Defined in

[ue/ue.d.ts:4636](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4636)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bRenderCustomDepth](ue_ue.SkinnedMeshComponent.md#brendercustomdepth)

#### Defined in

[ue/ue.d.ts:12611](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12611)

___

### bRenderInDepthPass

• **bRenderInDepthPass**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bRenderInDepthPass](ue_ue.SkinnedMeshComponent.md#brenderindepthpass)

#### Defined in

[ue/ue.d.ts:12578](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12578)

___

### bRenderInMainPass

• **bRenderInMainPass**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bRenderInMainPass](ue_ue.SkinnedMeshComponent.md#brenderinmainpass)

#### Defined in

[ue/ue.d.ts:12577](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12577)

___

### bRenderStatic

• **bRenderStatic**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bRenderStatic](ue_ue.SkinnedMeshComponent.md#brenderstatic)

#### Defined in

[ue/ue.d.ts:4642](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4642)

___

### bReplicatePhysicsToAutonomousProxy

• **bReplicatePhysicsToAutonomousProxy**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bReplicatePhysicsToAutonomousProxy](ue_ue.SkinnedMeshComponent.md#breplicatephysicstoautonomousproxy)

#### Defined in

[ue/ue.d.ts:12607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12607)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bReplicates](ue_ue.SkinnedMeshComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L292)

___

### bReturnMaterialOnMove

• **bReturnMaterialOnMove**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bReturnMaterialOnMove](ue_ue.SkinnedMeshComponent.md#breturnmaterialonmove)

#### Defined in

[ue/ue.d.ts:12571](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12571)

___

### bSelectable

• **bSelectable**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bSelectable](ue_ue.SkinnedMeshComponent.md#bselectable)

#### Defined in

[ue/ue.d.ts:12584](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12584)

___

### bSelfShadowOnly

• **bSelfShadowOnly**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bSelfShadowOnly](ue_ue.SkinnedMeshComponent.md#bselfshadowonly)

#### Defined in

[ue/ue.d.ts:12593](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12593)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bShouldBeAttached](ue_ue.SkinnedMeshComponent.md#bshouldbeattached)

#### Defined in

[ue/ue.d.ts:12885](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12885)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.SkinnedMeshComponent.md#bshouldsnaplocationwhenattached)

#### Defined in

[ue/ue.d.ts:12886](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12886)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.SkinnedMeshComponent.md#bshouldsnaprotationwhenattached)

#### Defined in

[ue/ue.d.ts:12887](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12887)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.SkinnedMeshComponent.md#bshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12888](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12888)

___

### bSingleSampleShadowFromStationaryLights

• **bSingleSampleShadowFromStationaryLights**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bSingleSampleShadowFromStationaryLights](ue_ue.SkinnedMeshComponent.md#bsinglesampleshadowfromstationarylights)

#### Defined in

[ue/ue.d.ts:12603](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12603)

___

### bSyncAttachParentLOD

• **bSyncAttachParentLOD**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bSyncAttachParentLOD](ue_ue.SkinnedMeshComponent.md#bsyncattachparentlod)

#### Defined in

[ue/ue.d.ts:4634](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4634)

___

### bTraceComplexOnMove

• **bTraceComplexOnMove**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bTraceComplexOnMove](ue_ue.SkinnedMeshComponent.md#btracecomplexonmove)

#### Defined in

[ue/ue.d.ts:12570](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12570)

___

### bTreatAsBackgroundForOcclusion

• **bTreatAsBackgroundForOcclusion**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bTreatAsBackgroundForOcclusion](ue_ue.SkinnedMeshComponent.md#btreatasbackgroundforocclusion)

#### Defined in

[ue/ue.d.ts:12582](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12582)

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bUseAsOccluder](ue_ue.SkinnedMeshComponent.md#buseasoccluder)

#### Defined in

[ue/ue.d.ts:12583](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12583)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bUseAttachParentBound](ue_ue.SkinnedMeshComponent.md#buseattachparentbound)

#### Defined in

[ue/ue.d.ts:12890](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12890)

___

### bUseBoundsFromMasterPoseComponent

• **bUseBoundsFromMasterPoseComponent**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bUseBoundsFromMasterPoseComponent](ue_ue.SkinnedMeshComponent.md#buseboundsfrommasterposecomponent)

#### Defined in

[ue/ue.d.ts:4626](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4626)

___

### bUseEditorCompositing

• **bUseEditorCompositing**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bUseEditorCompositing](ue_ue.SkinnedMeshComponent.md#buseeditorcompositing)

#### Defined in

[ue/ue.d.ts:12610](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12610)

___

### bUseMaxLODAsImposter

• **bUseMaxLODAsImposter**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bUseMaxLODAsImposter](ue_ue.SkinnedMeshComponent.md#busemaxlodasimposter)

#### Defined in

[ue/ue.d.ts:12564](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12564)

___

### bUseViewOwnerDepthPriorityGroup

• **bUseViewOwnerDepthPriorityGroup**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bUseViewOwnerDepthPriorityGroup](ue_ue.SkinnedMeshComponent.md#buseviewownerdepthprioritygroup)

#### Defined in

[ue/ue.d.ts:12572](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12572)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bVisible](ue_ue.SkinnedMeshComponent.md#bvisible)

#### Defined in

[ue/ue.d.ts:12883](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12883)

___

### bVisibleInRayTracing

• **bVisibleInRayTracing**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bVisibleInRayTracing](ue_ue.SkinnedMeshComponent.md#bvisibleinraytracing)

#### Defined in

[ue/ue.d.ts:12576](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12576)

___

### bVisibleInReflectionCaptures

• **bVisibleInReflectionCaptures**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bVisibleInReflectionCaptures](ue_ue.SkinnedMeshComponent.md#bvisibleinreflectioncaptures)

#### Defined in

[ue/ue.d.ts:12575](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12575)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[bVisualizeComponent](ue_ue.SkinnedMeshComponent.md#bvisualizecomponent)

#### Defined in

[ue/ue.d.ts:12891](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12891)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[Activate](ue_ue.SkinnedMeshComponent.md#activate)

#### Defined in

[ue/ue.d.ts:306](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L306)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AddAngularImpulse](ue_ue.SkinnedMeshComponent.md#addangularimpulse)

#### Defined in

[ue/ue.d.ts:12645](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12645)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AddAngularImpulseInDegrees](ue_ue.SkinnedMeshComponent.md#addangularimpulseindegrees)

#### Defined in

[ue/ue.d.ts:12646](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12646)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AddAngularImpulseInRadians](ue_ue.SkinnedMeshComponent.md#addangularimpulseinradians)

#### Defined in

[ue/ue.d.ts:12647](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12647)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AddForce](ue_ue.SkinnedMeshComponent.md#addforce)

#### Defined in

[ue/ue.d.ts:12648](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12648)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AddForceAtLocation](ue_ue.SkinnedMeshComponent.md#addforceatlocation)

#### Defined in

[ue/ue.d.ts:12649](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12649)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AddForceAtLocationLocal](ue_ue.SkinnedMeshComponent.md#addforceatlocationlocal)

#### Defined in

[ue/ue.d.ts:12650](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12650)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AddImpulse](ue_ue.SkinnedMeshComponent.md#addimpulse)

#### Defined in

[ue/ue.d.ts:12651](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12651)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AddImpulseAtLocation](ue_ue.SkinnedMeshComponent.md#addimpulseatlocation)

#### Defined in

[ue/ue.d.ts:12652](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12652)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AddRadialForce](ue_ue.SkinnedMeshComponent.md#addradialforce)

#### Defined in

[ue/ue.d.ts:12653](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12653)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AddRadialImpulse](ue_ue.SkinnedMeshComponent.md#addradialimpulse)

#### Defined in

[ue/ue.d.ts:12654](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12654)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AddTickPrerequisiteActor](ue_ue.SkinnedMeshComponent.md#addtickprerequisiteactor)

#### Defined in

[ue/ue.d.ts:307](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L307)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AddTickPrerequisiteComponent](ue_ue.SkinnedMeshComponent.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:308](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L308)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AddTorque](ue_ue.SkinnedMeshComponent.md#addtorque)

#### Defined in

[ue/ue.d.ts:12655](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12655)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AddTorqueInDegrees](ue_ue.SkinnedMeshComponent.md#addtorqueindegrees)

#### Defined in

[ue/ue.d.ts:12656](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12656)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[AddTorqueInRadians](ue_ue.SkinnedMeshComponent.md#addtorqueinradians)

#### Defined in

[ue/ue.d.ts:12657](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12657)

___

### BoneIsChildOf

▸ **BoneIsChildOf**(`BoneName`, `ParentBoneName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |
| `ParentBoneName` | `string` |

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[BoneIsChildOf](ue_ue.SkinnedMeshComponent.md#boneischildof)

#### Defined in

[ue/ue.d.ts:4649](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4649)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CanCharacterStepUp](ue_ue.SkinnedMeshComponent.md#cancharacterstepup)

#### Defined in

[ue/ue.d.ts:12658](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12658)

___

### ClearMoveIgnoreActors

▸ **ClearMoveIgnoreActors**(): `void`

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ClearMoveIgnoreActors](ue_ue.SkinnedMeshComponent.md#clearmoveignoreactors)

#### Defined in

[ue/ue.d.ts:12659](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12659)

___

### ClearMoveIgnoreComponents

▸ **ClearMoveIgnoreComponents**(): `void`

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ClearMoveIgnoreComponents](ue_ue.SkinnedMeshComponent.md#clearmoveignorecomponents)

#### Defined in

[ue/ue.d.ts:12660](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12660)

___

### ClearSkinWeightOverride

▸ **ClearSkinWeightOverride**(`LODIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LODIndex` | `number` |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ClearSkinWeightOverride](ue_ue.SkinnedMeshComponent.md#clearskinweightoverride)

#### Defined in

[ue/ue.d.ts:4650](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4650)

___

### ClearSkinWeightProfile

▸ **ClearSkinWeightProfile**(): `void`

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ClearSkinWeightProfile](ue_ue.SkinnedMeshComponent.md#clearskinweightprofile)

#### Defined in

[ue/ue.d.ts:4651](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4651)

___

### ClearVertexColorOverride

▸ **ClearVertexColorOverride**(`LODIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LODIndex` | `number` |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ClearVertexColorOverride](ue_ue.SkinnedMeshComponent.md#clearvertexcoloroverride)

#### Defined in

[ue/ue.d.ts:4652](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4652)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ComponentHasTag](ue_ue.SkinnedMeshComponent.md#componenthastag)

#### Defined in

[ue/ue.d.ts:309](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L309)

___

### CopyArrayOfMoveIgnoreActors

▸ **CopyArrayOfMoveIgnoreActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CopyArrayOfMoveIgnoreActors](ue_ue.SkinnedMeshComponent.md#copyarrayofmoveignoreactors)

#### Defined in

[ue/ue.d.ts:12661](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12661)

___

### CopyArrayOfMoveIgnoreComponents

▸ **CopyArrayOfMoveIgnoreComponents**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CopyArrayOfMoveIgnoreComponents](ue_ue.SkinnedMeshComponent.md#copyarrayofmoveignorecomponents)

#### Defined in

[ue/ue.d.ts:12662](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12662)

___

### CopyPoseFromSkeletalComponent

▸ **CopyPoseFromSkeletalComponent**(`InComponentToCopy`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InComponentToCopy` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58232](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58232)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CreateAndSetMaterialInstanceDynamic](ue_ue.SkinnedMeshComponent.md#createandsetmaterialinstancedynamic)

#### Defined in

[ue/ue.d.ts:12663](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12663)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.SkinnedMeshComponent.md#createandsetmaterialinstancedynamicfrommaterial)

#### Defined in

[ue/ue.d.ts:12664](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12664)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CreateDefaultSubobject](ue_ue.SkinnedMeshComponent.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[CreateDynamicMaterialInstance](ue_ue.SkinnedMeshComponent.md#createdynamicmaterialinstance)

#### Defined in

[ue/ue.d.ts:12665](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12665)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[Deactivate](ue_ue.SkinnedMeshComponent.md#deactivate)

#### Defined in

[ue/ue.d.ts:310](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L310)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[DetachFromParent](ue_ue.SkinnedMeshComponent.md#detachfromparent)

#### Defined in

[ue/ue.d.ts:12895](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12895)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[DoesSocketExist](ue_ue.SkinnedMeshComponent.md#doessocketexist)

#### Defined in

[ue/ue.d.ts:12896](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12896)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ExecuteUbergraph](ue_ue.SkinnedMeshComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### FindClosestBone\_K2

▸ **FindClosestBone_K2**(`TestLocation`, `BoneLocation`, `IgnoreScale?`, `bRequirePhysicsAsset?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TestLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `BoneLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `IgnoreScale?` | `number` |
| `bRequirePhysicsAsset?` | `boolean` |

#### Returns

`string`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[FindClosestBone_K2](ue_ue.SkinnedMeshComponent.md#findclosestbone_k2)

#### Defined in

[ue/ue.d.ts:4653](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4653)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetAllSocketNames](ue_ue.SkinnedMeshComponent.md#getallsocketnames)

#### Defined in

[ue/ue.d.ts:12897](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12897)

___

### GetAngularDamping

▸ **GetAngularDamping**(): `number`

#### Returns

`number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetAngularDamping](ue_ue.SkinnedMeshComponent.md#getangulardamping)

#### Defined in

[ue/ue.d.ts:12666](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12666)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetAttachParent](ue_ue.SkinnedMeshComponent.md#getattachparent)

#### Defined in

[ue/ue.d.ts:12898](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12898)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetAttachSocketName](ue_ue.SkinnedMeshComponent.md#getattachsocketname)

#### Defined in

[ue/ue.d.ts:12899](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12899)

___

### GetBoneIndex

▸ **GetBoneIndex**(`BoneName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |

#### Returns

`number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetBoneIndex](ue_ue.SkinnedMeshComponent.md#getboneindex)

#### Defined in

[ue/ue.d.ts:4654](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4654)

___

### GetBoneLocationByName

▸ **GetBoneLocationByName**(`BoneName`, `BoneSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |
| `BoneSpace` | [`EBoneSpaces`](../enums/ue_ue.EBoneSpaces.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:58233](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58233)

___

### GetBoneName

▸ **GetBoneName**(`BoneIndex`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneIndex` | `number` |

#### Returns

`string`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetBoneName](ue_ue.SkinnedMeshComponent.md#getbonename)

#### Defined in

[ue/ue.d.ts:4655](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4655)

___

### GetBoneRotationByName

▸ **GetBoneRotationByName**(`BoneName`, `BoneSpace`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |
| `BoneSpace` | [`EBoneSpaces`](../enums/ue_ue.EBoneSpaces.md) |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:58234](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58234)

___

### GetBoneScaleByName

▸ **GetBoneScaleByName**(`BoneName`, `BoneSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |
| `BoneSpace` | [`EBoneSpaces`](../enums/ue_ue.EBoneSpaces.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:58235](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58235)

___

### GetBoneTransformByName

▸ **GetBoneTransformByName**(`BoneName`, `BoneSpace`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |
| `BoneSpace` | [`EBoneSpaces`](../enums/ue_ue.EBoneSpaces.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:58236](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58236)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetCenterOfMass](ue_ue.SkinnedMeshComponent.md#getcenterofmass)

#### Defined in

[ue/ue.d.ts:12667](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12667)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetChildComponent](ue_ue.SkinnedMeshComponent.md#getchildcomponent)

#### Defined in

[ue/ue.d.ts:12900](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12900)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetChildrenComponents](ue_ue.SkinnedMeshComponent.md#getchildrencomponents)

#### Defined in

[ue/ue.d.ts:12901](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12901)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetClass](ue_ue.SkinnedMeshComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetClosestPointOnCollision](ue_ue.SkinnedMeshComponent.md#getclosestpointoncollision)

#### Defined in

[ue/ue.d.ts:12668](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12668)

___

### GetCollisionEnabled

▸ **GetCollisionEnabled**(): [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Returns

[`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetCollisionEnabled](ue_ue.SkinnedMeshComponent.md#getcollisionenabled)

#### Defined in

[ue/ue.d.ts:12669](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12669)

___

### GetCollisionObjectType

▸ **GetCollisionObjectType**(): [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Returns

[`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetCollisionObjectType](ue_ue.SkinnedMeshComponent.md#getcollisionobjecttype)

#### Defined in

[ue/ue.d.ts:12670](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12670)

___

### GetCollisionProfileName

▸ **GetCollisionProfileName**(): `string`

#### Returns

`string`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetCollisionProfileName](ue_ue.SkinnedMeshComponent.md#getcollisionprofilename)

#### Defined in

[ue/ue.d.ts:12671](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12671)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetCollisionResponseToChannel](ue_ue.SkinnedMeshComponent.md#getcollisionresponsetochannel)

#### Defined in

[ue/ue.d.ts:12672](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12672)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetComponentTickInterval](ue_ue.SkinnedMeshComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L311)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetComponentVelocity](ue_ue.SkinnedMeshComponent.md#getcomponentvelocity)

#### Defined in

[ue/ue.d.ts:12902](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12902)

___

### GetCurrentSkinWeightProfileName

▸ **GetCurrentSkinWeightProfileName**(): `string`

#### Returns

`string`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetCurrentSkinWeightProfileName](ue_ue.SkinnedMeshComponent.md#getcurrentskinweightprofilename)

#### Defined in

[ue/ue.d.ts:4656](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4656)

___

### GetDeltaTransformFromRefPose

▸ **GetDeltaTransformFromRefPose**(`BoneName`, `BaseName?`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |
| `BaseName?` | `string` |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetDeltaTransformFromRefPose](ue_ue.SkinnedMeshComponent.md#getdeltatransformfromrefpose)

#### Defined in

[ue/ue.d.ts:4657](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4657)

___

### GetForcedLOD

▸ **GetForcedLOD**(): `number`

#### Returns

`number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetForcedLOD](ue_ue.SkinnedMeshComponent.md#getforcedlod)

#### Defined in

[ue/ue.d.ts:4658](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4658)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetForwardVector](ue_ue.SkinnedMeshComponent.md#getforwardvector)

#### Defined in

[ue/ue.d.ts:12903](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12903)

___

### GetGenerateOverlapEvents

▸ **GetGenerateOverlapEvents**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetGenerateOverlapEvents](ue_ue.SkinnedMeshComponent.md#getgenerateoverlapevents)

#### Defined in

[ue/ue.d.ts:12673](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12673)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetInertiaTensor](ue_ue.SkinnedMeshComponent.md#getinertiatensor)

#### Defined in

[ue/ue.d.ts:12674](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12674)

___

### GetLinearDamping

▸ **GetLinearDamping**(): `number`

#### Returns

`number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetLinearDamping](ue_ue.SkinnedMeshComponent.md#getlineardamping)

#### Defined in

[ue/ue.d.ts:12675](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12675)

___

### GetMass

▸ **GetMass**(): `number`

#### Returns

`number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetMass](ue_ue.SkinnedMeshComponent.md#getmass)

#### Defined in

[ue/ue.d.ts:12676](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12676)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetMassScale](ue_ue.SkinnedMeshComponent.md#getmassscale)

#### Defined in

[ue/ue.d.ts:12677](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12677)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetMaterial](ue_ue.SkinnedMeshComponent.md#getmaterial)

#### Defined in

[ue/ue.d.ts:12678](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12678)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetMaterialFromCollisionFaceIndex](ue_ue.SkinnedMeshComponent.md#getmaterialfromcollisionfaceindex)

#### Defined in

[ue/ue.d.ts:12679](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12679)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetMaterialIndex](ue_ue.SkinnedMeshComponent.md#getmaterialindex)

#### Defined in

[ue/ue.d.ts:2298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2298)

___

### GetMaterialSlotNames

▸ **GetMaterialSlotNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetMaterialSlotNames](ue_ue.SkinnedMeshComponent.md#getmaterialslotnames)

#### Defined in

[ue/ue.d.ts:2300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2300)

___

### GetMaterials

▸ **GetMaterials**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetMaterials](ue_ue.SkinnedMeshComponent.md#getmaterials)

#### Defined in

[ue/ue.d.ts:2299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2299)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetName](ue_ue.SkinnedMeshComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetNumBones

▸ **GetNumBones**(): `number`

#### Returns

`number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetNumBones](ue_ue.SkinnedMeshComponent.md#getnumbones)

#### Defined in

[ue/ue.d.ts:4659](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4659)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetNumChildrenComponents](ue_ue.SkinnedMeshComponent.md#getnumchildrencomponents)

#### Defined in

[ue/ue.d.ts:12904](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12904)

___

### GetNumLODs

▸ **GetNumLODs**(): `number`

#### Returns

`number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetNumLODs](ue_ue.SkinnedMeshComponent.md#getnumlods)

#### Defined in

[ue/ue.d.ts:4660](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4660)

___

### GetNumMaterials

▸ **GetNumMaterials**(): `number`

#### Returns

`number`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetNumMaterials](ue_ue.SkinnedMeshComponent.md#getnummaterials)

#### Defined in

[ue/ue.d.ts:12680](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12680)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetOuter](ue_ue.SkinnedMeshComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetOverlappingActors](ue_ue.SkinnedMeshComponent.md#getoverlappingactors)

#### Defined in

[ue/ue.d.ts:12681](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12681)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetOverlappingComponents](ue_ue.SkinnedMeshComponent.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:12682](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12682)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetOwner](ue_ue.SkinnedMeshComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L312)

___

### GetParentBone

▸ **GetParentBone**(`BoneName`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |

#### Returns

`string`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetParentBone](ue_ue.SkinnedMeshComponent.md#getparentbone)

#### Defined in

[ue/ue.d.ts:4661](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4661)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetParentComponents](ue_ue.SkinnedMeshComponent.md#getparentcomponents)

#### Defined in

[ue/ue.d.ts:12905](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12905)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetPhysicsAngularVelocity](ue_ue.SkinnedMeshComponent.md#getphysicsangularvelocity)

#### Defined in

[ue/ue.d.ts:12683](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12683)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetPhysicsAngularVelocityInDegrees](ue_ue.SkinnedMeshComponent.md#getphysicsangularvelocityindegrees)

#### Defined in

[ue/ue.d.ts:12684](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12684)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetPhysicsAngularVelocityInRadians](ue_ue.SkinnedMeshComponent.md#getphysicsangularvelocityinradians)

#### Defined in

[ue/ue.d.ts:12685](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12685)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetPhysicsLinearVelocity](ue_ue.SkinnedMeshComponent.md#getphysicslinearvelocity)

#### Defined in

[ue/ue.d.ts:12686](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12686)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetPhysicsLinearVelocityAtPoint](ue_ue.SkinnedMeshComponent.md#getphysicslinearvelocityatpoint)

#### Defined in

[ue/ue.d.ts:12687](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12687)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetPhysicsVolume](ue_ue.SkinnedMeshComponent.md#getphysicsvolume)

#### Defined in

[ue/ue.d.ts:12906](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12906)

___

### GetRefPosePosition

▸ **GetRefPosePosition**(`BoneIndex`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneIndex` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetRefPosePosition](ue_ue.SkinnedMeshComponent.md#getrefposeposition)

#### Defined in

[ue/ue.d.ts:4662](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4662)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetRelativeTransform](ue_ue.SkinnedMeshComponent.md#getrelativetransform)

#### Defined in

[ue/ue.d.ts:12907](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12907)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetRightVector](ue_ue.SkinnedMeshComponent.md#getrightvector)

#### Defined in

[ue/ue.d.ts:12908](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12908)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.SkinnedMeshComponent.md#getshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12909](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12909)

___

### GetSocketBoneName

▸ **GetSocketBoneName**(`InSocketName`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSocketName` | `string` |

#### Returns

`string`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetSocketBoneName](ue_ue.SkinnedMeshComponent.md#getsocketbonename)

#### Defined in

[ue/ue.d.ts:4663](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4663)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetSocketLocation](ue_ue.SkinnedMeshComponent.md#getsocketlocation)

#### Defined in

[ue/ue.d.ts:12910](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12910)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetSocketQuaternion](ue_ue.SkinnedMeshComponent.md#getsocketquaternion)

#### Defined in

[ue/ue.d.ts:12911](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12911)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetSocketRotation](ue_ue.SkinnedMeshComponent.md#getsocketrotation)

#### Defined in

[ue/ue.d.ts:12912](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12912)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetSocketTransform](ue_ue.SkinnedMeshComponent.md#getsockettransform)

#### Defined in

[ue/ue.d.ts:12913](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12913)

___

### GetTwistAndSwingAngleOfDeltaRotationFromRefPose

▸ **GetTwistAndSwingAngleOfDeltaRotationFromRefPose**(`BoneName`, `OutTwistAngle`, `OutSwingAngle`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |
| `OutTwistAngle` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `OutSwingAngle` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetTwistAndSwingAngleOfDeltaRotationFromRefPose](ue_ue.SkinnedMeshComponent.md#gettwistandswingangleofdeltarotationfromrefpose)

#### Defined in

[ue/ue.d.ts:4664](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4664)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetUpVector](ue_ue.SkinnedMeshComponent.md#getupvector)

#### Defined in

[ue/ue.d.ts:12914](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12914)

___

### GetWalkableSlopeOverride

▸ **GetWalkableSlopeOverride**(): [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Returns

[`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetWalkableSlopeOverride](ue_ue.SkinnedMeshComponent.md#getwalkableslopeoverride)

#### Defined in

[ue/ue.d.ts:12688](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12688)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[GetWorld](ue_ue.SkinnedMeshComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### HideBoneByName

▸ **HideBoneByName**(`BoneName`, `PhysBodyOption`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |
| `PhysBodyOption` | [`EPhysBodyOp`](../enums/ue_ue.EPhysBodyOp.md) |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[HideBoneByName](ue_ue.SkinnedMeshComponent.md#hidebonebyname)

#### Defined in

[ue/ue.d.ts:4665](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4665)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[IgnoreActorWhenMoving](ue_ue.SkinnedMeshComponent.md#ignoreactorwhenmoving)

#### Defined in

[ue/ue.d.ts:12689](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12689)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[IgnoreComponentWhenMoving](ue_ue.SkinnedMeshComponent.md#ignorecomponentwhenmoving)

#### Defined in

[ue/ue.d.ts:12690](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12690)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[IsActive](ue_ue.SkinnedMeshComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L313)

___

### IsAnyRigidBodyAwake

▸ **IsAnyRigidBodyAwake**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[IsAnyRigidBodyAwake](ue_ue.SkinnedMeshComponent.md#isanyrigidbodyawake)

#### Defined in

[ue/ue.d.ts:12691](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12691)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[IsAnySimulatingPhysics](ue_ue.SkinnedMeshComponent.md#isanysimulatingphysics)

#### Defined in

[ue/ue.d.ts:12915](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12915)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[IsBeingDestroyed](ue_ue.SkinnedMeshComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L314)

___

### IsBoneHiddenByName

▸ **IsBoneHiddenByName**(`BoneName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[IsBoneHiddenByName](ue_ue.SkinnedMeshComponent.md#isbonehiddenbyname)

#### Defined in

[ue/ue.d.ts:4666](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4666)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[IsComponentTickEnabled](ue_ue.SkinnedMeshComponent.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L315)

___

### IsGravityEnabled

▸ **IsGravityEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[IsGravityEnabled](ue_ue.SkinnedMeshComponent.md#isgravityenabled)

#### Defined in

[ue/ue.d.ts:12692](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12692)

___

### IsMaterialSectionShown

▸ **IsMaterialSectionShown**(`MaterialID`, `LODIndex`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialID` | `number` |
| `LODIndex` | `number` |

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[IsMaterialSectionShown](ue_ue.SkinnedMeshComponent.md#ismaterialsectionshown)

#### Defined in

[ue/ue.d.ts:4667](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4667)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[IsMaterialSlotNameValid](ue_ue.SkinnedMeshComponent.md#ismaterialslotnamevalid)

#### Defined in

[ue/ue.d.ts:2301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2301)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[IsOverlappingActor](ue_ue.SkinnedMeshComponent.md#isoverlappingactor)

#### Defined in

[ue/ue.d.ts:12693](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12693)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[IsOverlappingComponent](ue_ue.SkinnedMeshComponent.md#isoverlappingcomponent)

#### Defined in

[ue/ue.d.ts:12694](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12694)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[IsSimulatingPhysics](ue_ue.SkinnedMeshComponent.md#issimulatingphysics)

#### Defined in

[ue/ue.d.ts:12916](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12916)

___

### IsUsingSkinWeightProfile

▸ **IsUsingSkinWeightProfile**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[IsUsingSkinWeightProfile](ue_ue.SkinnedMeshComponent.md#isusingskinweightprofile)

#### Defined in

[ue/ue.d.ts:4668](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4668)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[IsVisible](ue_ue.SkinnedMeshComponent.md#isvisible)

#### Defined in

[ue/ue.d.ts:12917](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12917)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_AddLocalOffset](ue_ue.SkinnedMeshComponent.md#k2_addlocaloffset)

#### Defined in

[ue/ue.d.ts:12918](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12918)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_AddLocalRotation](ue_ue.SkinnedMeshComponent.md#k2_addlocalrotation)

#### Defined in

[ue/ue.d.ts:12919](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12919)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_AddLocalTransform](ue_ue.SkinnedMeshComponent.md#k2_addlocaltransform)

#### Defined in

[ue/ue.d.ts:12920](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12920)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_AddRelativeLocation](ue_ue.SkinnedMeshComponent.md#k2_addrelativelocation)

#### Defined in

[ue/ue.d.ts:12921](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12921)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_AddRelativeRotation](ue_ue.SkinnedMeshComponent.md#k2_addrelativerotation)

#### Defined in

[ue/ue.d.ts:12922](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12922)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_AddWorldOffset](ue_ue.SkinnedMeshComponent.md#k2_addworldoffset)

#### Defined in

[ue/ue.d.ts:12923](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12923)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_AddWorldRotation](ue_ue.SkinnedMeshComponent.md#k2_addworldrotation)

#### Defined in

[ue/ue.d.ts:12924](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12924)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_AddWorldTransform](ue_ue.SkinnedMeshComponent.md#k2_addworldtransform)

#### Defined in

[ue/ue.d.ts:12925](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12925)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_AttachTo](ue_ue.SkinnedMeshComponent.md#k2_attachto)

#### Defined in

[ue/ue.d.ts:12926](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12926)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_AttachToComponent](ue_ue.SkinnedMeshComponent.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:12927](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12927)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_BoxOverlapComponent](ue_ue.SkinnedMeshComponent.md#k2_boxoverlapcomponent)

#### Defined in

[ue/ue.d.ts:12695](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12695)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_DestroyComponent](ue_ue.SkinnedMeshComponent.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L316)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_DetachFromComponent](ue_ue.SkinnedMeshComponent.md#k2_detachfromcomponent)

#### Defined in

[ue/ue.d.ts:12928](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12928)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_GetComponentLocation](ue_ue.SkinnedMeshComponent.md#k2_getcomponentlocation)

#### Defined in

[ue/ue.d.ts:12929](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12929)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_GetComponentRotation](ue_ue.SkinnedMeshComponent.md#k2_getcomponentrotation)

#### Defined in

[ue/ue.d.ts:12930](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12930)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_GetComponentScale](ue_ue.SkinnedMeshComponent.md#k2_getcomponentscale)

#### Defined in

[ue/ue.d.ts:12931](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12931)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_GetComponentToWorld](ue_ue.SkinnedMeshComponent.md#k2_getcomponenttoworld)

#### Defined in

[ue/ue.d.ts:12932](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12932)

___

### K2\_IsCollisionEnabled

▸ **K2_IsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_IsCollisionEnabled](ue_ue.SkinnedMeshComponent.md#k2_iscollisionenabled)

#### Defined in

[ue/ue.d.ts:12696](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12696)

___

### K2\_IsPhysicsCollisionEnabled

▸ **K2_IsPhysicsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_IsPhysicsCollisionEnabled](ue_ue.SkinnedMeshComponent.md#k2_isphysicscollisionenabled)

#### Defined in

[ue/ue.d.ts:12697](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12697)

___

### K2\_IsQueryCollisionEnabled

▸ **K2_IsQueryCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_IsQueryCollisionEnabled](ue_ue.SkinnedMeshComponent.md#k2_isquerycollisionenabled)

#### Defined in

[ue/ue.d.ts:12698](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12698)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_LineTraceComponent](ue_ue.SkinnedMeshComponent.md#k2_linetracecomponent)

#### Defined in

[ue/ue.d.ts:12699](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12699)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_SetRelativeLocation](ue_ue.SkinnedMeshComponent.md#k2_setrelativelocation)

#### Defined in

[ue/ue.d.ts:12933](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12933)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.SkinnedMeshComponent.md#k2_setrelativelocationandrotation)

#### Defined in

[ue/ue.d.ts:12934](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12934)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_SetRelativeRotation](ue_ue.SkinnedMeshComponent.md#k2_setrelativerotation)

#### Defined in

[ue/ue.d.ts:12935](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12935)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_SetRelativeTransform](ue_ue.SkinnedMeshComponent.md#k2_setrelativetransform)

#### Defined in

[ue/ue.d.ts:12936](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12936)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_SetWorldLocation](ue_ue.SkinnedMeshComponent.md#k2_setworldlocation)

#### Defined in

[ue/ue.d.ts:12937](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12937)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.SkinnedMeshComponent.md#k2_setworldlocationandrotation)

#### Defined in

[ue/ue.d.ts:12938](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12938)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_SetWorldRotation](ue_ue.SkinnedMeshComponent.md#k2_setworldrotation)

#### Defined in

[ue/ue.d.ts:12939](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12939)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_SetWorldTransform](ue_ue.SkinnedMeshComponent.md#k2_setworldtransform)

#### Defined in

[ue/ue.d.ts:12940](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12940)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_SphereOverlapComponent](ue_ue.SkinnedMeshComponent.md#k2_sphereoverlapcomponent)

#### Defined in

[ue/ue.d.ts:12700](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12700)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[K2_SphereTraceComponent](ue_ue.SkinnedMeshComponent.md#k2_spheretracecomponent)

#### Defined in

[ue/ue.d.ts:12701](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12701)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnRep_AttachChildren](ue_ue.SkinnedMeshComponent.md#onrep_attachchildren)

#### Defined in

[ue/ue.d.ts:12941](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12941)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnRep_AttachParent](ue_ue.SkinnedMeshComponent.md#onrep_attachparent)

#### Defined in

[ue/ue.d.ts:12942](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12942)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnRep_AttachSocketName](ue_ue.SkinnedMeshComponent.md#onrep_attachsocketname)

#### Defined in

[ue/ue.d.ts:12943](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12943)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnRep_IsActive](ue_ue.SkinnedMeshComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L317)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnRep_Transform](ue_ue.SkinnedMeshComponent.md#onrep_transform)

#### Defined in

[ue/ue.d.ts:12944](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12944)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[OnRep_Visibility](ue_ue.SkinnedMeshComponent.md#onrep_visibility)

#### Defined in

[ue/ue.d.ts:12945](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12945)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[PrestreamTextures](ue_ue.SkinnedMeshComponent.md#prestreamtextures)

#### Defined in

[ue/ue.d.ts:2302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2302)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[PutRigidBodyToSleep](ue_ue.SkinnedMeshComponent.md#putrigidbodytosleep)

#### Defined in

[ue/ue.d.ts:12702](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12702)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ReceiveBeginPlay](ue_ue.SkinnedMeshComponent.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:318](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L318)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ReceiveEndPlay](ue_ue.SkinnedMeshComponent.md#receiveendplay)

#### Defined in

[ue/ue.d.ts:319](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L319)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ReceiveTick](ue_ue.SkinnedMeshComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[RegisterComponent](ue_ue.SkinnedMeshComponent.md#registercomponent)

#### Defined in

[ue/ue.d.ts:321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L321)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[RemoveTickPrerequisiteActor](ue_ue.SkinnedMeshComponent.md#removetickprerequisiteactor)

#### Defined in

[ue/ue.d.ts:322](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L322)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.SkinnedMeshComponent.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L323)

___

### ResetBoneTransformByName

▸ **ResetBoneTransformByName**(`BoneName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58237](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58237)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ResetRelativeTransform](ue_ue.SkinnedMeshComponent.md#resetrelativetransform)

#### Defined in

[ue/ue.d.ts:12946](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12946)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ScaleByMomentOfInertia](ue_ue.SkinnedMeshComponent.md#scalebymomentofinertia)

#### Defined in

[ue/ue.d.ts:12703](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12703)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetAbsolute](ue_ue.SkinnedMeshComponent.md#setabsolute)

#### Defined in

[ue/ue.d.ts:12947](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12947)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetActive](ue_ue.SkinnedMeshComponent.md#setactive)

#### Defined in

[ue/ue.d.ts:324](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L324)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetAllMassScale](ue_ue.SkinnedMeshComponent.md#setallmassscale)

#### Defined in

[ue/ue.d.ts:12704](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12704)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetAllPhysicsAngularVelocityInDegrees](ue_ue.SkinnedMeshComponent.md#setallphysicsangularvelocityindegrees)

#### Defined in

[ue/ue.d.ts:12705](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12705)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetAllPhysicsAngularVelocityInRadians](ue_ue.SkinnedMeshComponent.md#setallphysicsangularvelocityinradians)

#### Defined in

[ue/ue.d.ts:12706](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12706)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetAllPhysicsLinearVelocity](ue_ue.SkinnedMeshComponent.md#setallphysicslinearvelocity)

#### Defined in

[ue/ue.d.ts:12707](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12707)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetAllUseCCD](ue_ue.SkinnedMeshComponent.md#setalluseccd)

#### Defined in

[ue/ue.d.ts:12708](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12708)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetAngularDamping](ue_ue.SkinnedMeshComponent.md#setangulardamping)

#### Defined in

[ue/ue.d.ts:12709](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12709)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetAutoActivate](ue_ue.SkinnedMeshComponent.md#setautoactivate)

#### Defined in

[ue/ue.d.ts:325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L325)

___

### SetBoneLocationByName

▸ **SetBoneLocationByName**(`BoneName`, `InLocation`, `BoneSpace`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |
| `InLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `BoneSpace` | [`EBoneSpaces`](../enums/ue_ue.EBoneSpaces.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58238](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58238)

___

### SetBoneRotationByName

▸ **SetBoneRotationByName**(`BoneName`, `InRotation`, `BoneSpace`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |
| `InRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `BoneSpace` | [`EBoneSpaces`](../enums/ue_ue.EBoneSpaces.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58239](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58239)

___

### SetBoneScaleByName

▸ **SetBoneScaleByName**(`BoneName`, `InScale3D`, `BoneSpace`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |
| `InScale3D` | [`Vector`](ue_ue_s.Vector.md) |
| `BoneSpace` | [`EBoneSpaces`](../enums/ue_ue.EBoneSpaces.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58240](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58240)

___

### SetBoneTransformByName

▸ **SetBoneTransformByName**(`BoneName`, `InTransform`, `BoneSpace`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |
| `InTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `BoneSpace` | [`EBoneSpaces`](../enums/ue_ue.EBoneSpaces.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58241](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58241)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetBoundsScale](ue_ue.SkinnedMeshComponent.md#setboundsscale)

#### Defined in

[ue/ue.d.ts:12710](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12710)

___

### SetCapsuleIndirectShadowMinVisibility

▸ **SetCapsuleIndirectShadowMinVisibility**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCapsuleIndirectShadowMinVisibility](ue_ue.SkinnedMeshComponent.md#setcapsuleindirectshadowminvisibility)

#### Defined in

[ue/ue.d.ts:4669](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4669)

___

### SetCastCapsuleDirectShadow

▸ **SetCastCapsuleDirectShadow**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCastCapsuleDirectShadow](ue_ue.SkinnedMeshComponent.md#setcastcapsuledirectshadow)

#### Defined in

[ue/ue.d.ts:4670](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4670)

___

### SetCastCapsuleIndirectShadow

▸ **SetCastCapsuleIndirectShadow**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCastCapsuleIndirectShadow](ue_ue.SkinnedMeshComponent.md#setcastcapsuleindirectshadow)

#### Defined in

[ue/ue.d.ts:4671](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4671)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCastInsetShadow](ue_ue.SkinnedMeshComponent.md#setcastinsetshadow)

#### Defined in

[ue/ue.d.ts:12711](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12711)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCastShadow](ue_ue.SkinnedMeshComponent.md#setcastshadow)

#### Defined in

[ue/ue.d.ts:12712](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12712)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCenterOfMass](ue_ue.SkinnedMeshComponent.md#setcenterofmass)

#### Defined in

[ue/ue.d.ts:12713](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12713)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCollisionEnabled](ue_ue.SkinnedMeshComponent.md#setcollisionenabled)

#### Defined in

[ue/ue.d.ts:12714](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12714)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCollisionObjectType](ue_ue.SkinnedMeshComponent.md#setcollisionobjecttype)

#### Defined in

[ue/ue.d.ts:12715](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12715)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCollisionProfileName](ue_ue.SkinnedMeshComponent.md#setcollisionprofilename)

#### Defined in

[ue/ue.d.ts:12716](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12716)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCollisionResponseToAllChannels](ue_ue.SkinnedMeshComponent.md#setcollisionresponsetoallchannels)

#### Defined in

[ue/ue.d.ts:12717](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12717)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCollisionResponseToChannel](ue_ue.SkinnedMeshComponent.md#setcollisionresponsetochannel)

#### Defined in

[ue/ue.d.ts:12718](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12718)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetComponentTickEnabled](ue_ue.SkinnedMeshComponent.md#setcomponenttickenabled)

#### Defined in

[ue/ue.d.ts:326](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L326)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetComponentTickInterval](ue_ue.SkinnedMeshComponent.md#setcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L327)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetConstraintMode](ue_ue.SkinnedMeshComponent.md#setconstraintmode)

#### Defined in

[ue/ue.d.ts:12719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12719)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCullDistance](ue_ue.SkinnedMeshComponent.md#setculldistance)

#### Defined in

[ue/ue.d.ts:12720](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12720)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCustomDepthStencilValue](ue_ue.SkinnedMeshComponent.md#setcustomdepthstencilvalue)

#### Defined in

[ue/ue.d.ts:12721](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12721)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCustomDepthStencilWriteMask](ue_ue.SkinnedMeshComponent.md#setcustomdepthstencilwritemask)

#### Defined in

[ue/ue.d.ts:12722](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12722)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCustomPrimitiveDataFloat](ue_ue.SkinnedMeshComponent.md#setcustomprimitivedatafloat)

#### Defined in

[ue/ue.d.ts:12723](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12723)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCustomPrimitiveDataVector2](ue_ue.SkinnedMeshComponent.md#setcustomprimitivedatavector2)

#### Defined in

[ue/ue.d.ts:12724](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12724)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCustomPrimitiveDataVector3](ue_ue.SkinnedMeshComponent.md#setcustomprimitivedatavector3)

#### Defined in

[ue/ue.d.ts:12725](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12725)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetCustomPrimitiveDataVector4](ue_ue.SkinnedMeshComponent.md#setcustomprimitivedatavector4)

#### Defined in

[ue/ue.d.ts:12726](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12726)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetEnableGravity](ue_ue.SkinnedMeshComponent.md#setenablegravity)

#### Defined in

[ue/ue.d.ts:12727](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12727)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetExcludeFromLightAttachmentGroup](ue_ue.SkinnedMeshComponent.md#setexcludefromlightattachmentgroup)

#### Defined in

[ue/ue.d.ts:12728](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12728)

___

### SetForcedLOD

▸ **SetForcedLOD**(`InNewForcedLOD`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InNewForcedLOD` | `number` |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetForcedLOD](ue_ue.SkinnedMeshComponent.md#setforcedlod)

#### Defined in

[ue/ue.d.ts:4672](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4672)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetGenerateOverlapEvents](ue_ue.SkinnedMeshComponent.md#setgenerateoverlapevents)

#### Defined in

[ue/ue.d.ts:12729](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12729)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetHiddenInGame](ue_ue.SkinnedMeshComponent.md#sethiddeningame)

#### Defined in

[ue/ue.d.ts:12948](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12948)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetIsReplicated](ue_ue.SkinnedMeshComponent.md#setisreplicated)

#### Defined in

[ue/ue.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L328)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetLightAttachmentsAsGroup](ue_ue.SkinnedMeshComponent.md#setlightattachmentsasgroup)

#### Defined in

[ue/ue.d.ts:12730](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12730)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetLinearDamping](ue_ue.SkinnedMeshComponent.md#setlineardamping)

#### Defined in

[ue/ue.d.ts:12731](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12731)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetMassOverrideInKg](ue_ue.SkinnedMeshComponent.md#setmassoverrideinkg)

#### Defined in

[ue/ue.d.ts:12732](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12732)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetMassScale](ue_ue.SkinnedMeshComponent.md#setmassscale)

#### Defined in

[ue/ue.d.ts:12733](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12733)

___

### SetMasterPoseComponent

▸ **SetMasterPoseComponent**(`NewMasterBoneComponent`, `bForceUpdate?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMasterBoneComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SkinnedMeshComponent`](ue_ue.SkinnedMeshComponent.md)\> |
| `bForceUpdate?` | `boolean` |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetMasterPoseComponent](ue_ue.SkinnedMeshComponent.md#setmasterposecomponent)

#### Defined in

[ue/ue.d.ts:4673](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4673)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetMaterial](ue_ue.SkinnedMeshComponent.md#setmaterial)

#### Defined in

[ue/ue.d.ts:12734](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12734)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetMaterialByName](ue_ue.SkinnedMeshComponent.md#setmaterialbyname)

#### Defined in

[ue/ue.d.ts:12735](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12735)

___

### SetMinLOD

▸ **SetMinLOD**(`InNewMinLOD`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InNewMinLOD` | `number` |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetMinLOD](ue_ue.SkinnedMeshComponent.md#setminlod)

#### Defined in

[ue/ue.d.ts:4674](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4674)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetMobility](ue_ue.SkinnedMeshComponent.md#setmobility)

#### Defined in

[ue/ue.d.ts:12949](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12949)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetNotifyRigidBodyCollision](ue_ue.SkinnedMeshComponent.md#setnotifyrigidbodycollision)

#### Defined in

[ue/ue.d.ts:12736](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12736)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetOnlyOwnerSee](ue_ue.SkinnedMeshComponent.md#setonlyownersee)

#### Defined in

[ue/ue.d.ts:12737](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12737)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetOwnerNoSee](ue_ue.SkinnedMeshComponent.md#setownernosee)

#### Defined in

[ue/ue.d.ts:12738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12738)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetPhysMaterialOverride](ue_ue.SkinnedMeshComponent.md#setphysmaterialoverride)

#### Defined in

[ue/ue.d.ts:12746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12746)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetPhysicsAngularVelocity](ue_ue.SkinnedMeshComponent.md#setphysicsangularvelocity)

#### Defined in

[ue/ue.d.ts:12739](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12739)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetPhysicsAngularVelocityInDegrees](ue_ue.SkinnedMeshComponent.md#setphysicsangularvelocityindegrees)

#### Defined in

[ue/ue.d.ts:12740](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12740)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetPhysicsAngularVelocityInRadians](ue_ue.SkinnedMeshComponent.md#setphysicsangularvelocityinradians)

#### Defined in

[ue/ue.d.ts:12741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12741)

___

### SetPhysicsAsset

▸ **SetPhysicsAsset**(`NewPhysicsAsset`, `bForceReInit?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPhysicsAsset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsAsset`](ue_ue.PhysicsAsset.md)\> |
| `bForceReInit?` | `boolean` |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetPhysicsAsset](ue_ue.SkinnedMeshComponent.md#setphysicsasset)

#### Defined in

[ue/ue.d.ts:4675](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4675)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetPhysicsLinearVelocity](ue_ue.SkinnedMeshComponent.md#setphysicslinearvelocity)

#### Defined in

[ue/ue.d.ts:12742](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12742)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetPhysicsMaxAngularVelocity](ue_ue.SkinnedMeshComponent.md#setphysicsmaxangularvelocity)

#### Defined in

[ue/ue.d.ts:12743](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12743)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetPhysicsMaxAngularVelocityInDegrees](ue_ue.SkinnedMeshComponent.md#setphysicsmaxangularvelocityindegrees)

#### Defined in

[ue/ue.d.ts:12744](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12744)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetPhysicsMaxAngularVelocityInRadians](ue_ue.SkinnedMeshComponent.md#setphysicsmaxangularvelocityinradians)

#### Defined in

[ue/ue.d.ts:12745](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12745)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetReceivesDecals](ue_ue.SkinnedMeshComponent.md#setreceivesdecals)

#### Defined in

[ue/ue.d.ts:12747](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12747)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetRelativeScale3D](ue_ue.SkinnedMeshComponent.md#setrelativescale3d)

#### Defined in

[ue/ue.d.ts:12950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12950)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetRenderCustomDepth](ue_ue.SkinnedMeshComponent.md#setrendercustomdepth)

#### Defined in

[ue/ue.d.ts:12748](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12748)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetRenderInMainPass](ue_ue.SkinnedMeshComponent.md#setrenderinmainpass)

#### Defined in

[ue/ue.d.ts:12749](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12749)

___

### SetRenderStatic

▸ **SetRenderStatic**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetRenderStatic](ue_ue.SkinnedMeshComponent.md#setrenderstatic)

#### Defined in

[ue/ue.d.ts:4676](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4676)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetScalarParameterValueOnMaterials](ue_ue.SkinnedMeshComponent.md#setscalarparametervalueonmaterials)

#### Defined in

[ue/ue.d.ts:2303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2303)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.SkinnedMeshComponent.md#setshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12951](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12951)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetSimulatePhysics](ue_ue.SkinnedMeshComponent.md#setsimulatephysics)

#### Defined in

[ue/ue.d.ts:12750](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12750)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetSingleSampleShadowFromStationaryLights](ue_ue.SkinnedMeshComponent.md#setsinglesampleshadowfromstationarylights)

#### Defined in

[ue/ue.d.ts:12751](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12751)

___

### SetSkeletalMesh

▸ **SetSkeletalMesh**(`NewMesh`, `bReinitPose?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMesh` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\> |
| `bReinitPose?` | `boolean` |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetSkeletalMesh](ue_ue.SkinnedMeshComponent.md#setskeletalmesh)

#### Defined in

[ue/ue.d.ts:4677](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4677)

___

### SetSkinWeightOverride

▸ **SetSkinWeightOverride**(`LODIndex`, `SkinWeights`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LODIndex` | `number` |
| `SkinWeights` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SkelMeshSkinWeightInfo`](ue_ue.SkelMeshSkinWeightInfo.md)\> |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetSkinWeightOverride](ue_ue.SkinnedMeshComponent.md#setskinweightoverride)

#### Defined in

[ue/ue.d.ts:4678](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4678)

___

### SetSkinWeightProfile

▸ **SetSkinWeightProfile**(`InProfileName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InProfileName` | `string` |

#### Returns

`boolean`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetSkinWeightProfile](ue_ue.SkinnedMeshComponent.md#setskinweightprofile)

#### Defined in

[ue/ue.d.ts:4679](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4679)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetTickGroup](ue_ue.SkinnedMeshComponent.md#settickgroup)

#### Defined in

[ue/ue.d.ts:330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L330)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetTickableWhenPaused](ue_ue.SkinnedMeshComponent.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L329)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetTranslucentSortPriority](ue_ue.SkinnedMeshComponent.md#settranslucentsortpriority)

#### Defined in

[ue/ue.d.ts:12752](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12752)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetUseCCD](ue_ue.SkinnedMeshComponent.md#setuseccd)

#### Defined in

[ue/ue.d.ts:12753](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12753)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetVectorParameterValueOnMaterials](ue_ue.SkinnedMeshComponent.md#setvectorparametervalueonmaterials)

#### Defined in

[ue/ue.d.ts:2304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2304)

___

### SetVertexColorOverride\_LinearColor

▸ **SetVertexColorOverride_LinearColor**(`LODIndex`, `VertexColors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LODIndex` | `number` |
| `VertexColors` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\> |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetVertexColorOverride_LinearColor](ue_ue.SkinnedMeshComponent.md#setvertexcoloroverride_linearcolor)

#### Defined in

[ue/ue.d.ts:4680](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4680)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetVisibility](ue_ue.SkinnedMeshComponent.md#setvisibility)

#### Defined in

[ue/ue.d.ts:12953](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12953)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetWalkableSlopeOverride](ue_ue.SkinnedMeshComponent.md#setwalkableslopeoverride)

#### Defined in

[ue/ue.d.ts:12754](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12754)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetWorldScale3D](ue_ue.SkinnedMeshComponent.md#setworldscale3d)

#### Defined in

[ue/ue.d.ts:12954](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12954)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SetupAttachment](ue_ue.SkinnedMeshComponent.md#setupattachment)

#### Defined in

[ue/ue.d.ts:12952](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12952)

___

### ShowAllMaterialSections

▸ **ShowAllMaterialSections**(`LODIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LODIndex` | `number` |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ShowAllMaterialSections](ue_ue.SkinnedMeshComponent.md#showallmaterialsections)

#### Defined in

[ue/ue.d.ts:4681](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4681)

___

### ShowMaterialSection

▸ **ShowMaterialSection**(`MaterialID`, `SectionIndex`, `bShow`, `LODIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialID` | `number` |
| `SectionIndex` | `number` |
| `bShow` | `boolean` |
| `LODIndex` | `number` |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ShowMaterialSection](ue_ue.SkinnedMeshComponent.md#showmaterialsection)

#### Defined in

[ue/ue.d.ts:4682](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4682)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[SnapTo](ue_ue.SkinnedMeshComponent.md#snapto)

#### Defined in

[ue/ue.d.ts:12955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12955)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ToggleActive](ue_ue.SkinnedMeshComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L331)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[ToggleVisibility](ue_ue.SkinnedMeshComponent.md#togglevisibility)

#### Defined in

[ue/ue.d.ts:12956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12956)

___

### TransformFromBoneSpace

▸ **TransformFromBoneSpace**(`BoneName`, `InPosition`, `InRotation`, `OutPosition`, `OutRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |
| `InPosition` | [`Vector`](ue_ue_s.Vector.md) |
| `InRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `OutPosition` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `OutRotation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[TransformFromBoneSpace](ue_ue.SkinnedMeshComponent.md#transformfrombonespace)

#### Defined in

[ue/ue.d.ts:4683](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4683)

___

### TransformToBoneSpace

▸ **TransformToBoneSpace**(`BoneName`, `InPosition`, `InRotation`, `OutPosition`, `OutRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |
| `InPosition` | [`Vector`](ue_ue_s.Vector.md) |
| `InRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `OutPosition` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `OutRotation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[TransformToBoneSpace](ue_ue.SkinnedMeshComponent.md#transformtobonespace)

#### Defined in

[ue/ue.d.ts:4684](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4684)

___

### UnHideBoneByName

▸ **UnHideBoneByName**(`BoneName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName` | `string` |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[UnHideBoneByName](ue_ue.SkinnedMeshComponent.md#unhidebonebyname)

#### Defined in

[ue/ue.d.ts:4685](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4685)

___

### UnloadSkinWeightProfile

▸ **UnloadSkinWeightProfile**(`InProfileName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InProfileName` | `string` |

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[UnloadSkinWeightProfile](ue_ue.SkinnedMeshComponent.md#unloadskinweightprofile)

#### Defined in

[ue/ue.d.ts:4686](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4686)

___

### WakeAllRigidBodies

▸ **WakeAllRigidBodies**(): `void`

#### Returns

`void`

#### Inherited from

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[WakeAllRigidBodies](ue_ue.SkinnedMeshComponent.md#wakeallrigidbodies)

#### Defined in

[ue/ue.d.ts:12755](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12755)

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

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[WakeRigidBody](ue_ue.SkinnedMeshComponent.md#wakerigidbody)

#### Defined in

[ue/ue.d.ts:12756](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12756)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PoseableMeshComponent`](ue_ue.PoseableMeshComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PoseableMeshComponent`](ue_ue.PoseableMeshComponent.md)

#### Overrides

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[Find](ue_ue.SkinnedMeshComponent.md#find)

#### Defined in

[ue/ue.d.ts:58243](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58243)

___

### Load

▸ `Static` **Load**(`InName`): [`PoseableMeshComponent`](ue_ue.PoseableMeshComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PoseableMeshComponent`](ue_ue.PoseableMeshComponent.md)

#### Overrides

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[Load](ue_ue.SkinnedMeshComponent.md#load)

#### Defined in

[ue/ue.d.ts:58244](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58244)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SkinnedMeshComponent](ue_ue.SkinnedMeshComponent.md).[StaticClass](ue_ue.SkinnedMeshComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:58242](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58242)
