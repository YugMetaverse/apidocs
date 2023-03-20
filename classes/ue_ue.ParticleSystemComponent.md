[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleSystemComponent

# Class: ParticleSystemComponent

[ue/ue](../modules/ue_ue.md).ParticleSystemComponent

## Hierarchy

- [`FXSystemComponent`](ue_ue.FXSystemComponent.md)

  ↳ **`ParticleSystemComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleSystemComponent.md#constructor)

### Properties

- [AlwaysLoadOnClient](ue_ue.ParticleSystemComponent.md#alwaysloadonclient)
- [AlwaysLoadOnServer](ue_ue.ParticleSystemComponent.md#alwaysloadonserver)
- [AssetUserData](ue_ue.ParticleSystemComponent.md#assetuserdata)
- [AttachChildren](ue_ue.ParticleSystemComponent.md#attachchildren)
- [AttachParent](ue_ue.ParticleSystemComponent.md#attachparent)
- [AttachSocketName](ue_ue.ParticleSystemComponent.md#attachsocketname)
- [AutoAttachLocationRule](ue_ue.ParticleSystemComponent.md#autoattachlocationrule)
- [AutoAttachLocationType](ue_ue.ParticleSystemComponent.md#autoattachlocationtype)
- [AutoAttachParent](ue_ue.ParticleSystemComponent.md#autoattachparent)
- [AutoAttachRotationRule](ue_ue.ParticleSystemComponent.md#autoattachrotationrule)
- [AutoAttachScaleRule](ue_ue.ParticleSystemComponent.md#autoattachscalerule)
- [AutoAttachSocketName](ue_ue.ParticleSystemComponent.md#autoattachsocketname)
- [BodyInstance](ue_ue.ParticleSystemComponent.md#bodyinstance)
- [BoundsScale](ue_ue.ParticleSystemComponent.md#boundsscale)
- [CachedMaxDrawDistance](ue_ue.ParticleSystemComponent.md#cachedmaxdrawdistance)
- [CanBeCharacterBase](ue_ue.ParticleSystemComponent.md#canbecharacterbase)
- [CanCharacterStepUpOn](ue_ue.ParticleSystemComponent.md#cancharacterstepupon)
- [CastShadow](ue_ue.ParticleSystemComponent.md#castshadow)
- [ClientAttachedChildren](ue_ue.ParticleSystemComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.ParticleSystemComponent.md#componenttags)
- [ComponentVelocity](ue_ue.ParticleSystemComponent.md#componentvelocity)
- [CreationMethod](ue_ue.ParticleSystemComponent.md#creationmethod)
- [CustomDepthStencilValue](ue_ue.ParticleSystemComponent.md#customdepthstencilvalue)
- [CustomDepthStencilWriteMask](ue_ue.ParticleSystemComponent.md#customdepthstencilwritemask)
- [CustomPrimitiveData](ue_ue.ParticleSystemComponent.md#customprimitivedata)
- [CustomTimeDilation](ue_ue.ParticleSystemComponent.md#customtimedilation)
- [DepthPriorityGroup](ue_ue.ParticleSystemComponent.md#depthprioritygroup)
- [DetailMode](ue_ue.ParticleSystemComponent.md#detailmode)
- [EditorDetailMode](ue_ue.ParticleSystemComponent.md#editordetailmode)
- [EditorLODLevel](ue_ue.ParticleSystemComponent.md#editorlodlevel)
- [EmitterMaterials](ue_ue.ParticleSystemComponent.md#emittermaterials)
- [ExcludeForSpecificHLODLevels](ue_ue.ParticleSystemComponent.md#excludeforspecifichlodlevels)
- [IndirectLightingCacheQuality](ue_ue.ParticleSystemComponent.md#indirectlightingcachequality)
- [InstanceParameters](ue_ue.ParticleSystemComponent.md#instanceparameters)
- [LDMaxDrawDistance](ue_ue.ParticleSystemComponent.md#ldmaxdrawdistance)
- [LODMethod](ue_ue.ParticleSystemComponent.md#lodmethod)
- [LODParentPrimitive](ue_ue.ParticleSystemComponent.md#lodparentprimitive)
- [LightingChannels](ue_ue.ParticleSystemComponent.md#lightingchannels)
- [LightmapType](ue_ue.ParticleSystemComponent.md#lightmaptype)
- [LpvBiasMultiplier](ue_ue.ParticleSystemComponent.md#lpvbiasmultiplier)
- [MaxTimeBeforeForceUpdateTransform](ue_ue.ParticleSystemComponent.md#maxtimebeforeforceupdatetransform)
- [MinDrawDistance](ue_ue.ParticleSystemComponent.md#mindrawdistance)
- [Mobility](ue_ue.ParticleSystemComponent.md#mobility)
- [MoveIgnoreActors](ue_ue.ParticleSystemComponent.md#moveignoreactors)
- [MoveIgnoreComponents](ue_ue.ParticleSystemComponent.md#moveignorecomponents)
- [OldPosition](ue_ue.ParticleSystemComponent.md#oldposition)
- [OnBeginCursorOver](ue_ue.ParticleSystemComponent.md#onbegincursorover)
- [OnClicked](ue_ue.ParticleSystemComponent.md#onclicked)
- [OnComponentActivated](ue_ue.ParticleSystemComponent.md#oncomponentactivated)
- [OnComponentBeginOverlap](ue_ue.ParticleSystemComponent.md#oncomponentbeginoverlap)
- [OnComponentDeactivated](ue_ue.ParticleSystemComponent.md#oncomponentdeactivated)
- [OnComponentEndOverlap](ue_ue.ParticleSystemComponent.md#oncomponentendoverlap)
- [OnComponentHit](ue_ue.ParticleSystemComponent.md#oncomponenthit)
- [OnComponentSleep](ue_ue.ParticleSystemComponent.md#oncomponentsleep)
- [OnComponentWake](ue_ue.ParticleSystemComponent.md#oncomponentwake)
- [OnEndCursorOver](ue_ue.ParticleSystemComponent.md#onendcursorover)
- [OnInputTouchBegin](ue_ue.ParticleSystemComponent.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.ParticleSystemComponent.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.ParticleSystemComponent.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.ParticleSystemComponent.md#oninputtouchleave)
- [OnParticleBurst](ue_ue.ParticleSystemComponent.md#onparticleburst)
- [OnParticleCollide](ue_ue.ParticleSystemComponent.md#onparticlecollide)
- [OnParticleDeath](ue_ue.ParticleSystemComponent.md#onparticledeath)
- [OnParticleSpawn](ue_ue.ParticleSystemComponent.md#onparticlespawn)
- [OnReleased](ue_ue.ParticleSystemComponent.md#onreleased)
- [OnSystemFinished](ue_ue.ParticleSystemComponent.md#onsystemfinished)
- [PartSysVelocity](ue_ue.ParticleSystemComponent.md#partsysvelocity)
- [PhysicsVolume](ue_ue.ParticleSystemComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.ParticleSystemComponent.md#physicsvolumechangeddelegate)
- [PrimaryComponentTick](ue_ue.ParticleSystemComponent.md#primarycomponenttick)
- [RelativeLocation](ue_ue.ParticleSystemComponent.md#relativelocation)
- [RelativeRotation](ue_ue.ParticleSystemComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.ParticleSystemComponent.md#relativescale3d)
- [ReplayClips](ue_ue.ParticleSystemComponent.md#replayclips)
- [RequiredSignificance](ue_ue.ParticleSystemComponent.md#requiredsignificance)
- [RuntimeVirtualTextures](ue_ue.ParticleSystemComponent.md#runtimevirtualtextures)
- [SecondsBeforeInactive](ue_ue.ParticleSystemComponent.md#secondsbeforeinactive)
- [SkelMeshComponents](ue_ue.ParticleSystemComponent.md#skelmeshcomponents)
- [Template](ue_ue.ParticleSystemComponent.md#template)
- [TranslucencySortPriority](ue_ue.ParticleSystemComponent.md#translucencysortpriority)
- [UCSModifiedProperties](ue_ue.ParticleSystemComponent.md#ucsmodifiedproperties)
- [ViewOwnerDepthPriorityGroup](ue_ue.ParticleSystemComponent.md#viewownerdepthprioritygroup)
- [VirtualTextureCullMips](ue_ue.ParticleSystemComponent.md#virtualtexturecullmips)
- [VirtualTextureLodBias](ue_ue.ParticleSystemComponent.md#virtualtexturelodbias)
- [VirtualTextureMinCoverage](ue_ue.ParticleSystemComponent.md#virtualtexturemincoverage)
- [VirtualTextureRenderPassType](ue_ue.ParticleSystemComponent.md#virtualtexturerenderpasstype)
- [VisibilityId](ue_ue.ParticleSystemComponent.md#visibilityid)
- [WarmupTickRate](ue_ue.ParticleSystemComponent.md#warmuptickrate)
- [WarmupTime](ue_ue.ParticleSystemComponent.md#warmuptime)
- [\_\_tid\_ActorComponent\_\_](ue_ue.ParticleSystemComponent.md#__tid_actorcomponent__)
- [\_\_tid\_FXSystemComponent\_\_](ue_ue.ParticleSystemComponent.md#__tid_fxsystemcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.ParticleSystemComponent.md#__tid_object__)
- [\_\_tid\_ParticleSystemComponent\_\_](ue_ue.ParticleSystemComponent.md#__tid_particlesystemcomponent__)
- [\_\_tid\_PrimitiveComponent\_\_](ue_ue.ParticleSystemComponent.md#__tid_primitivecomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.ParticleSystemComponent.md#__tid_scenecomponent__)
- [bAbsoluteLocation](ue_ue.ParticleSystemComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.ParticleSystemComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.ParticleSystemComponent.md#babsolutescale)
- [bAffectDistanceFieldLighting](ue_ue.ParticleSystemComponent.md#baffectdistancefieldlighting)
- [bAffectDynamicIndirectLighting](ue_ue.ParticleSystemComponent.md#baffectdynamicindirectlighting)
- [bAllowCullDistanceVolume](ue_ue.ParticleSystemComponent.md#ballowculldistancevolume)
- [bAllowRecycling](ue_ue.ParticleSystemComponent.md#ballowrecycling)
- [bAlwaysCreatePhysicsState](ue_ue.ParticleSystemComponent.md#balwayscreatephysicsstate)
- [bApplyImpulseOnDamage](ue_ue.ParticleSystemComponent.md#bapplyimpulseondamage)
- [bAutoActivate](ue_ue.ParticleSystemComponent.md#bautoactivate)
- [bAutoManageAttachment](ue_ue.ParticleSystemComponent.md#bautomanageattachment)
- [bBatchImpostersAsInstances](ue_ue.ParticleSystemComponent.md#bbatchimpostersasinstances)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.ParticleSystemComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.ParticleSystemComponent.md#bcaneveraffectnavigation)
- [bCastCinematicShadow](ue_ue.ParticleSystemComponent.md#bcastcinematicshadow)
- [bCastDynamicShadow](ue_ue.ParticleSystemComponent.md#bcastdynamicshadow)
- [bCastFarShadow](ue_ue.ParticleSystemComponent.md#bcastfarshadow)
- [bCastHiddenShadow](ue_ue.ParticleSystemComponent.md#bcasthiddenshadow)
- [bCastInsetShadow](ue_ue.ParticleSystemComponent.md#bcastinsetshadow)
- [bCastShadowAsTwoSided](ue_ue.ParticleSystemComponent.md#bcastshadowastwosided)
- [bCastStaticShadow](ue_ue.ParticleSystemComponent.md#bcaststaticshadow)
- [bCastVolumetricTranslucentShadow](ue_ue.ParticleSystemComponent.md#bcastvolumetrictranslucentshadow)
- [bComponentToWorldUpdated](ue_ue.ParticleSystemComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.ParticleSystemComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.ParticleSystemComponent.md#beditablewheninherited)
- [bEnableAutoLODGeneration](ue_ue.ParticleSystemComponent.md#benableautolodgeneration)
- [bExcludeFromLightAttachmentGroup](ue_ue.ParticleSystemComponent.md#bexcludefromlightattachmentgroup)
- [bForceMipStreaming](ue_ue.ParticleSystemComponent.md#bforcemipstreaming)
- [bGenerateOverlapEvents](ue_ue.ParticleSystemComponent.md#bgenerateoverlapevents)
- [bHasCustomNavigableGeometry](ue_ue.ParticleSystemComponent.md#bhascustomnavigablegeometry)
- [bHasMotionBlurVelocityMeshes](ue_ue.ParticleSystemComponent.md#bhasmotionblurvelocitymeshes)
- [bHasPerInstanceHitProxies](ue_ue.ParticleSystemComponent.md#bhasperinstancehitproxies)
- [bHiddenInGame](ue_ue.ParticleSystemComponent.md#bhiddeningame)
- [bIgnoreRadialForce](ue_ue.ParticleSystemComponent.md#bignoreradialforce)
- [bIgnoreRadialImpulse](ue_ue.ParticleSystemComponent.md#bignoreradialimpulse)
- [bInstanceComponent](ue_ue.ParticleSystemComponent.md#binstancecomponent)
- [bIsActive](ue_ue.ParticleSystemComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.ParticleSystemComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.ParticleSystemComponent.md#bisvisualizationcomponent)
- [bLightAsIfStatic](ue_ue.ParticleSystemComponent.md#blightasifstatic)
- [bLightAttachmentsAsGroup](ue_ue.ParticleSystemComponent.md#blightattachmentsasgroup)
- [bMultiBodyOverlap](ue_ue.ParticleSystemComponent.md#bmultibodyoverlap)
- [bNetAddressable](ue_ue.ParticleSystemComponent.md#bnetaddressable)
- [bNeverDistanceCull](ue_ue.ParticleSystemComponent.md#bneverdistancecull)
- [bOnlyOwnerSee](ue_ue.ParticleSystemComponent.md#bonlyownersee)
- [bOverrideLODMethod](ue_ue.ParticleSystemComponent.md#boverridelodmethod)
- [bOwnerNoSee](ue_ue.ParticleSystemComponent.md#bownernosee)
- [bReceiveMobileCSMShadows](ue_ue.ParticleSystemComponent.md#breceivemobilecsmshadows)
- [bReceivesDecals](ue_ue.ParticleSystemComponent.md#breceivesdecals)
- [bRenderCustomDepth](ue_ue.ParticleSystemComponent.md#brendercustomdepth)
- [bRenderInDepthPass](ue_ue.ParticleSystemComponent.md#brenderindepthpass)
- [bRenderInMainPass](ue_ue.ParticleSystemComponent.md#brenderinmainpass)
- [bReplicatePhysicsToAutonomousProxy](ue_ue.ParticleSystemComponent.md#breplicatephysicstoautonomousproxy)
- [bReplicates](ue_ue.ParticleSystemComponent.md#breplicates)
- [bResetOnDetach](ue_ue.ParticleSystemComponent.md#bresetondetach)
- [bReturnMaterialOnMove](ue_ue.ParticleSystemComponent.md#breturnmaterialonmove)
- [bSelectable](ue_ue.ParticleSystemComponent.md#bselectable)
- [bSelfShadowOnly](ue_ue.ParticleSystemComponent.md#bselfshadowonly)
- [bShouldBeAttached](ue_ue.ParticleSystemComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.ParticleSystemComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.ParticleSystemComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.ParticleSystemComponent.md#bshouldupdatephysicsvolume)
- [bSingleSampleShadowFromStationaryLights](ue_ue.ParticleSystemComponent.md#bsinglesampleshadowfromstationarylights)
- [bSkipUpdateDynamicDataDuringTick](ue_ue.ParticleSystemComponent.md#bskipupdatedynamicdataduringtick)
- [bTraceComplexOnMove](ue_ue.ParticleSystemComponent.md#btracecomplexonmove)
- [bTreatAsBackgroundForOcclusion](ue_ue.ParticleSystemComponent.md#btreatasbackgroundforocclusion)
- [bUpdateOnDedicatedServer](ue_ue.ParticleSystemComponent.md#bupdateondedicatedserver)
- [bUseAsOccluder](ue_ue.ParticleSystemComponent.md#buseasoccluder)
- [bUseAttachParentBound](ue_ue.ParticleSystemComponent.md#buseattachparentbound)
- [bUseEditorCompositing](ue_ue.ParticleSystemComponent.md#buseeditorcompositing)
- [bUseMaxLODAsImposter](ue_ue.ParticleSystemComponent.md#busemaxlodasimposter)
- [bUseViewOwnerDepthPriorityGroup](ue_ue.ParticleSystemComponent.md#buseviewownerdepthprioritygroup)
- [bVisible](ue_ue.ParticleSystemComponent.md#bvisible)
- [bVisibleInRayTracing](ue_ue.ParticleSystemComponent.md#bvisibleinraytracing)
- [bVisibleInReflectionCaptures](ue_ue.ParticleSystemComponent.md#bvisibleinreflectioncaptures)
- [bVisualizeComponent](ue_ue.ParticleSystemComponent.md#bvisualizecomponent)
- [bWarmingUp](ue_ue.ParticleSystemComponent.md#bwarmingup)

### Methods

- [Activate](ue_ue.ParticleSystemComponent.md#activate)
- [AddAngularImpulse](ue_ue.ParticleSystemComponent.md#addangularimpulse)
- [AddAngularImpulseInDegrees](ue_ue.ParticleSystemComponent.md#addangularimpulseindegrees)
- [AddAngularImpulseInRadians](ue_ue.ParticleSystemComponent.md#addangularimpulseinradians)
- [AddForce](ue_ue.ParticleSystemComponent.md#addforce)
- [AddForceAtLocation](ue_ue.ParticleSystemComponent.md#addforceatlocation)
- [AddForceAtLocationLocal](ue_ue.ParticleSystemComponent.md#addforceatlocationlocal)
- [AddImpulse](ue_ue.ParticleSystemComponent.md#addimpulse)
- [AddImpulseAtLocation](ue_ue.ParticleSystemComponent.md#addimpulseatlocation)
- [AddRadialForce](ue_ue.ParticleSystemComponent.md#addradialforce)
- [AddRadialImpulse](ue_ue.ParticleSystemComponent.md#addradialimpulse)
- [AddTickPrerequisiteActor](ue_ue.ParticleSystemComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.ParticleSystemComponent.md#addtickprerequisitecomponent)
- [AddTorque](ue_ue.ParticleSystemComponent.md#addtorque)
- [AddTorqueInDegrees](ue_ue.ParticleSystemComponent.md#addtorqueindegrees)
- [AddTorqueInRadians](ue_ue.ParticleSystemComponent.md#addtorqueinradians)
- [BeginTrails](ue_ue.ParticleSystemComponent.md#begintrails)
- [CanCharacterStepUp](ue_ue.ParticleSystemComponent.md#cancharacterstepup)
- [ClearMoveIgnoreActors](ue_ue.ParticleSystemComponent.md#clearmoveignoreactors)
- [ClearMoveIgnoreComponents](ue_ue.ParticleSystemComponent.md#clearmoveignorecomponents)
- [ComponentHasTag](ue_ue.ParticleSystemComponent.md#componenthastag)
- [CopyArrayOfMoveIgnoreActors](ue_ue.ParticleSystemComponent.md#copyarrayofmoveignoreactors)
- [CopyArrayOfMoveIgnoreComponents](ue_ue.ParticleSystemComponent.md#copyarrayofmoveignorecomponents)
- [CreateAndSetMaterialInstanceDynamic](ue_ue.ParticleSystemComponent.md#createandsetmaterialinstancedynamic)
- [CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.ParticleSystemComponent.md#createandsetmaterialinstancedynamicfrommaterial)
- [CreateDefaultSubobject](ue_ue.ParticleSystemComponent.md#createdefaultsubobject)
- [CreateDynamicMaterialInstance](ue_ue.ParticleSystemComponent.md#createdynamicmaterialinstance)
- [CreateNamedDynamicMaterialInstance](ue_ue.ParticleSystemComponent.md#createnameddynamicmaterialinstance)
- [Deactivate](ue_ue.ParticleSystemComponent.md#deactivate)
- [DetachFromParent](ue_ue.ParticleSystemComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.ParticleSystemComponent.md#doessocketexist)
- [EndTrails](ue_ue.ParticleSystemComponent.md#endtrails)
- [ExecuteUbergraph](ue_ue.ParticleSystemComponent.md#executeubergraph)
- [GenerateParticleEvent](ue_ue.ParticleSystemComponent.md#generateparticleevent)
- [GetAllSocketNames](ue_ue.ParticleSystemComponent.md#getallsocketnames)
- [GetAngularDamping](ue_ue.ParticleSystemComponent.md#getangulardamping)
- [GetAttachParent](ue_ue.ParticleSystemComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.ParticleSystemComponent.md#getattachsocketname)
- [GetBeamEndPoint](ue_ue.ParticleSystemComponent.md#getbeamendpoint)
- [GetBeamSourcePoint](ue_ue.ParticleSystemComponent.md#getbeamsourcepoint)
- [GetBeamSourceStrength](ue_ue.ParticleSystemComponent.md#getbeamsourcestrength)
- [GetBeamSourceTangent](ue_ue.ParticleSystemComponent.md#getbeamsourcetangent)
- [GetBeamTargetPoint](ue_ue.ParticleSystemComponent.md#getbeamtargetpoint)
- [GetBeamTargetStrength](ue_ue.ParticleSystemComponent.md#getbeamtargetstrength)
- [GetBeamTargetTangent](ue_ue.ParticleSystemComponent.md#getbeamtargettangent)
- [GetCenterOfMass](ue_ue.ParticleSystemComponent.md#getcenterofmass)
- [GetChildComponent](ue_ue.ParticleSystemComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.ParticleSystemComponent.md#getchildrencomponents)
- [GetClass](ue_ue.ParticleSystemComponent.md#getclass)
- [GetClosestPointOnCollision](ue_ue.ParticleSystemComponent.md#getclosestpointoncollision)
- [GetCollisionEnabled](ue_ue.ParticleSystemComponent.md#getcollisionenabled)
- [GetCollisionObjectType](ue_ue.ParticleSystemComponent.md#getcollisionobjecttype)
- [GetCollisionProfileName](ue_ue.ParticleSystemComponent.md#getcollisionprofilename)
- [GetCollisionResponseToChannel](ue_ue.ParticleSystemComponent.md#getcollisionresponsetochannel)
- [GetComponentTickInterval](ue_ue.ParticleSystemComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.ParticleSystemComponent.md#getcomponentvelocity)
- [GetFXSystemAsset](ue_ue.ParticleSystemComponent.md#getfxsystemasset)
- [GetForwardVector](ue_ue.ParticleSystemComponent.md#getforwardvector)
- [GetGenerateOverlapEvents](ue_ue.ParticleSystemComponent.md#getgenerateoverlapevents)
- [GetInertiaTensor](ue_ue.ParticleSystemComponent.md#getinertiatensor)
- [GetLinearDamping](ue_ue.ParticleSystemComponent.md#getlineardamping)
- [GetMass](ue_ue.ParticleSystemComponent.md#getmass)
- [GetMassScale](ue_ue.ParticleSystemComponent.md#getmassscale)
- [GetMaterial](ue_ue.ParticleSystemComponent.md#getmaterial)
- [GetMaterialFromCollisionFaceIndex](ue_ue.ParticleSystemComponent.md#getmaterialfromcollisionfaceindex)
- [GetName](ue_ue.ParticleSystemComponent.md#getname)
- [GetNamedMaterial](ue_ue.ParticleSystemComponent.md#getnamedmaterial)
- [GetNumActiveParticles](ue_ue.ParticleSystemComponent.md#getnumactiveparticles)
- [GetNumChildrenComponents](ue_ue.ParticleSystemComponent.md#getnumchildrencomponents)
- [GetNumMaterials](ue_ue.ParticleSystemComponent.md#getnummaterials)
- [GetOuter](ue_ue.ParticleSystemComponent.md#getouter)
- [GetOverlappingActors](ue_ue.ParticleSystemComponent.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.ParticleSystemComponent.md#getoverlappingcomponents)
- [GetOwner](ue_ue.ParticleSystemComponent.md#getowner)
- [GetParentComponents](ue_ue.ParticleSystemComponent.md#getparentcomponents)
- [GetPhysicsAngularVelocity](ue_ue.ParticleSystemComponent.md#getphysicsangularvelocity)
- [GetPhysicsAngularVelocityInDegrees](ue_ue.ParticleSystemComponent.md#getphysicsangularvelocityindegrees)
- [GetPhysicsAngularVelocityInRadians](ue_ue.ParticleSystemComponent.md#getphysicsangularvelocityinradians)
- [GetPhysicsLinearVelocity](ue_ue.ParticleSystemComponent.md#getphysicslinearvelocity)
- [GetPhysicsLinearVelocityAtPoint](ue_ue.ParticleSystemComponent.md#getphysicslinearvelocityatpoint)
- [GetPhysicsVolume](ue_ue.ParticleSystemComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.ParticleSystemComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.ParticleSystemComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.ParticleSystemComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.ParticleSystemComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.ParticleSystemComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.ParticleSystemComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.ParticleSystemComponent.md#getsockettransform)
- [GetUpVector](ue_ue.ParticleSystemComponent.md#getupvector)
- [GetWalkableSlopeOverride](ue_ue.ParticleSystemComponent.md#getwalkableslopeoverride)
- [GetWorld](ue_ue.ParticleSystemComponent.md#getworld)
- [IgnoreActorWhenMoving](ue_ue.ParticleSystemComponent.md#ignoreactorwhenmoving)
- [IgnoreComponentWhenMoving](ue_ue.ParticleSystemComponent.md#ignorecomponentwhenmoving)
- [IsActive](ue_ue.ParticleSystemComponent.md#isactive)
- [IsAnyRigidBodyAwake](ue_ue.ParticleSystemComponent.md#isanyrigidbodyawake)
- [IsAnySimulatingPhysics](ue_ue.ParticleSystemComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.ParticleSystemComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.ParticleSystemComponent.md#iscomponenttickenabled)
- [IsGravityEnabled](ue_ue.ParticleSystemComponent.md#isgravityenabled)
- [IsOverlappingActor](ue_ue.ParticleSystemComponent.md#isoverlappingactor)
- [IsOverlappingComponent](ue_ue.ParticleSystemComponent.md#isoverlappingcomponent)
- [IsSimulatingPhysics](ue_ue.ParticleSystemComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.ParticleSystemComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.ParticleSystemComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.ParticleSystemComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.ParticleSystemComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.ParticleSystemComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.ParticleSystemComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.ParticleSystemComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.ParticleSystemComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.ParticleSystemComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.ParticleSystemComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.ParticleSystemComponent.md#k2_attachtocomponent)
- [K2\_BoxOverlapComponent](ue_ue.ParticleSystemComponent.md#k2_boxoverlapcomponent)
- [K2\_DestroyComponent](ue_ue.ParticleSystemComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.ParticleSystemComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.ParticleSystemComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.ParticleSystemComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.ParticleSystemComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.ParticleSystemComponent.md#k2_getcomponenttoworld)
- [K2\_IsCollisionEnabled](ue_ue.ParticleSystemComponent.md#k2_iscollisionenabled)
- [K2\_IsPhysicsCollisionEnabled](ue_ue.ParticleSystemComponent.md#k2_isphysicscollisionenabled)
- [K2\_IsQueryCollisionEnabled](ue_ue.ParticleSystemComponent.md#k2_isquerycollisionenabled)
- [K2\_LineTraceComponent](ue_ue.ParticleSystemComponent.md#k2_linetracecomponent)
- [K2\_SetRelativeLocation](ue_ue.ParticleSystemComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.ParticleSystemComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.ParticleSystemComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.ParticleSystemComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.ParticleSystemComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.ParticleSystemComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.ParticleSystemComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.ParticleSystemComponent.md#k2_setworldtransform)
- [K2\_SphereOverlapComponent](ue_ue.ParticleSystemComponent.md#k2_sphereoverlapcomponent)
- [K2\_SphereTraceComponent](ue_ue.ParticleSystemComponent.md#k2_spheretracecomponent)
- [OnRep\_AttachChildren](ue_ue.ParticleSystemComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.ParticleSystemComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.ParticleSystemComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.ParticleSystemComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.ParticleSystemComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.ParticleSystemComponent.md#onrep_visibility)
- [PutRigidBodyToSleep](ue_ue.ParticleSystemComponent.md#putrigidbodytosleep)
- [ReceiveBeginPlay](ue_ue.ParticleSystemComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.ParticleSystemComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.ParticleSystemComponent.md#receivetick)
- [RegisterComponent](ue_ue.ParticleSystemComponent.md#registercomponent)
- [ReleaseToPool](ue_ue.ParticleSystemComponent.md#releasetopool)
- [RemoveTickPrerequisiteActor](ue_ue.ParticleSystemComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.ParticleSystemComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.ParticleSystemComponent.md#resetrelativetransform)
- [ScaleByMomentOfInertia](ue_ue.ParticleSystemComponent.md#scalebymomentofinertia)
- [SetAbsolute](ue_ue.ParticleSystemComponent.md#setabsolute)
- [SetActive](ue_ue.ParticleSystemComponent.md#setactive)
- [SetActorParameter](ue_ue.ParticleSystemComponent.md#setactorparameter)
- [SetAllMassScale](ue_ue.ParticleSystemComponent.md#setallmassscale)
- [SetAllPhysicsAngularVelocityInDegrees](ue_ue.ParticleSystemComponent.md#setallphysicsangularvelocityindegrees)
- [SetAllPhysicsAngularVelocityInRadians](ue_ue.ParticleSystemComponent.md#setallphysicsangularvelocityinradians)
- [SetAllPhysicsLinearVelocity](ue_ue.ParticleSystemComponent.md#setallphysicslinearvelocity)
- [SetAllUseCCD](ue_ue.ParticleSystemComponent.md#setalluseccd)
- [SetAngularDamping](ue_ue.ParticleSystemComponent.md#setangulardamping)
- [SetAutoActivate](ue_ue.ParticleSystemComponent.md#setautoactivate)
- [SetAutoAttachParams](ue_ue.ParticleSystemComponent.md#setautoattachparams)
- [SetAutoAttachmentParameters](ue_ue.ParticleSystemComponent.md#setautoattachmentparameters)
- [SetBeamEndPoint](ue_ue.ParticleSystemComponent.md#setbeamendpoint)
- [SetBeamSourcePoint](ue_ue.ParticleSystemComponent.md#setbeamsourcepoint)
- [SetBeamSourceStrength](ue_ue.ParticleSystemComponent.md#setbeamsourcestrength)
- [SetBeamSourceTangent](ue_ue.ParticleSystemComponent.md#setbeamsourcetangent)
- [SetBeamTargetPoint](ue_ue.ParticleSystemComponent.md#setbeamtargetpoint)
- [SetBeamTargetStrength](ue_ue.ParticleSystemComponent.md#setbeamtargetstrength)
- [SetBeamTargetTangent](ue_ue.ParticleSystemComponent.md#setbeamtargettangent)
- [SetBoundsScale](ue_ue.ParticleSystemComponent.md#setboundsscale)
- [SetCastInsetShadow](ue_ue.ParticleSystemComponent.md#setcastinsetshadow)
- [SetCastShadow](ue_ue.ParticleSystemComponent.md#setcastshadow)
- [SetCenterOfMass](ue_ue.ParticleSystemComponent.md#setcenterofmass)
- [SetCollisionEnabled](ue_ue.ParticleSystemComponent.md#setcollisionenabled)
- [SetCollisionObjectType](ue_ue.ParticleSystemComponent.md#setcollisionobjecttype)
- [SetCollisionProfileName](ue_ue.ParticleSystemComponent.md#setcollisionprofilename)
- [SetCollisionResponseToAllChannels](ue_ue.ParticleSystemComponent.md#setcollisionresponsetoallchannels)
- [SetCollisionResponseToChannel](ue_ue.ParticleSystemComponent.md#setcollisionresponsetochannel)
- [SetColorParameter](ue_ue.ParticleSystemComponent.md#setcolorparameter)
- [SetComponentTickEnabled](ue_ue.ParticleSystemComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.ParticleSystemComponent.md#setcomponenttickinterval)
- [SetConstraintMode](ue_ue.ParticleSystemComponent.md#setconstraintmode)
- [SetCullDistance](ue_ue.ParticleSystemComponent.md#setculldistance)
- [SetCustomDepthStencilValue](ue_ue.ParticleSystemComponent.md#setcustomdepthstencilvalue)
- [SetCustomDepthStencilWriteMask](ue_ue.ParticleSystemComponent.md#setcustomdepthstencilwritemask)
- [SetCustomPrimitiveDataFloat](ue_ue.ParticleSystemComponent.md#setcustomprimitivedatafloat)
- [SetCustomPrimitiveDataVector2](ue_ue.ParticleSystemComponent.md#setcustomprimitivedatavector2)
- [SetCustomPrimitiveDataVector3](ue_ue.ParticleSystemComponent.md#setcustomprimitivedatavector3)
- [SetCustomPrimitiveDataVector4](ue_ue.ParticleSystemComponent.md#setcustomprimitivedatavector4)
- [SetEmitterEnable](ue_ue.ParticleSystemComponent.md#setemitterenable)
- [SetEnableGravity](ue_ue.ParticleSystemComponent.md#setenablegravity)
- [SetExcludeFromLightAttachmentGroup](ue_ue.ParticleSystemComponent.md#setexcludefromlightattachmentgroup)
- [SetFloatParameter](ue_ue.ParticleSystemComponent.md#setfloatparameter)
- [SetGenerateOverlapEvents](ue_ue.ParticleSystemComponent.md#setgenerateoverlapevents)
- [SetHiddenInGame](ue_ue.ParticleSystemComponent.md#sethiddeningame)
- [SetIsReplicated](ue_ue.ParticleSystemComponent.md#setisreplicated)
- [SetLightAttachmentsAsGroup](ue_ue.ParticleSystemComponent.md#setlightattachmentsasgroup)
- [SetLinearDamping](ue_ue.ParticleSystemComponent.md#setlineardamping)
- [SetMassOverrideInKg](ue_ue.ParticleSystemComponent.md#setmassoverrideinkg)
- [SetMassScale](ue_ue.ParticleSystemComponent.md#setmassscale)
- [SetMaterial](ue_ue.ParticleSystemComponent.md#setmaterial)
- [SetMaterialByName](ue_ue.ParticleSystemComponent.md#setmaterialbyname)
- [SetMaterialParameter](ue_ue.ParticleSystemComponent.md#setmaterialparameter)
- [SetMobility](ue_ue.ParticleSystemComponent.md#setmobility)
- [SetNotifyRigidBodyCollision](ue_ue.ParticleSystemComponent.md#setnotifyrigidbodycollision)
- [SetOnlyOwnerSee](ue_ue.ParticleSystemComponent.md#setonlyownersee)
- [SetOwnerNoSee](ue_ue.ParticleSystemComponent.md#setownernosee)
- [SetPhysMaterialOverride](ue_ue.ParticleSystemComponent.md#setphysmaterialoverride)
- [SetPhysicsAngularVelocity](ue_ue.ParticleSystemComponent.md#setphysicsangularvelocity)
- [SetPhysicsAngularVelocityInDegrees](ue_ue.ParticleSystemComponent.md#setphysicsangularvelocityindegrees)
- [SetPhysicsAngularVelocityInRadians](ue_ue.ParticleSystemComponent.md#setphysicsangularvelocityinradians)
- [SetPhysicsLinearVelocity](ue_ue.ParticleSystemComponent.md#setphysicslinearvelocity)
- [SetPhysicsMaxAngularVelocity](ue_ue.ParticleSystemComponent.md#setphysicsmaxangularvelocity)
- [SetPhysicsMaxAngularVelocityInDegrees](ue_ue.ParticleSystemComponent.md#setphysicsmaxangularvelocityindegrees)
- [SetPhysicsMaxAngularVelocityInRadians](ue_ue.ParticleSystemComponent.md#setphysicsmaxangularvelocityinradians)
- [SetReceivesDecals](ue_ue.ParticleSystemComponent.md#setreceivesdecals)
- [SetRelativeScale3D](ue_ue.ParticleSystemComponent.md#setrelativescale3d)
- [SetRenderCustomDepth](ue_ue.ParticleSystemComponent.md#setrendercustomdepth)
- [SetRenderInMainPass](ue_ue.ParticleSystemComponent.md#setrenderinmainpass)
- [SetShouldUpdatePhysicsVolume](ue_ue.ParticleSystemComponent.md#setshouldupdatephysicsvolume)
- [SetSimulatePhysics](ue_ue.ParticleSystemComponent.md#setsimulatephysics)
- [SetSingleSampleShadowFromStationaryLights](ue_ue.ParticleSystemComponent.md#setsinglesampleshadowfromstationarylights)
- [SetTemplate](ue_ue.ParticleSystemComponent.md#settemplate)
- [SetTickGroup](ue_ue.ParticleSystemComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.ParticleSystemComponent.md#settickablewhenpaused)
- [SetTrailSourceData](ue_ue.ParticleSystemComponent.md#settrailsourcedata)
- [SetTranslucentSortPriority](ue_ue.ParticleSystemComponent.md#settranslucentsortpriority)
- [SetUseAutoManageAttachment](ue_ue.ParticleSystemComponent.md#setuseautomanageattachment)
- [SetUseCCD](ue_ue.ParticleSystemComponent.md#setuseccd)
- [SetVectorParameter](ue_ue.ParticleSystemComponent.md#setvectorparameter)
- [SetVisibility](ue_ue.ParticleSystemComponent.md#setvisibility)
- [SetWalkableSlopeOverride](ue_ue.ParticleSystemComponent.md#setwalkableslopeoverride)
- [SetWorldScale3D](ue_ue.ParticleSystemComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.ParticleSystemComponent.md#setupattachment)
- [SnapTo](ue_ue.ParticleSystemComponent.md#snapto)
- [ToggleActive](ue_ue.ParticleSystemComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.ParticleSystemComponent.md#togglevisibility)
- [WakeAllRigidBodies](ue_ue.ParticleSystemComponent.md#wakeallrigidbodies)
- [WakeRigidBody](ue_ue.ParticleSystemComponent.md#wakerigidbody)
- [Find](ue_ue.ParticleSystemComponent.md#find)
- [Load](ue_ue.ParticleSystemComponent.md#load)
- [StaticClass](ue_ue.ParticleSystemComponent.md#staticclass)

## Constructors

### constructor

• **new ParticleSystemComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FXSystemComponent](ue_ue.FXSystemComponent.md).[constructor](ue_ue.FXSystemComponent.md#constructor)

## Properties

### AlwaysLoadOnClient

• **AlwaysLoadOnClient**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AlwaysLoadOnClient](ue_ue.FXSystemComponent.md#alwaysloadonclient)

___

### AlwaysLoadOnServer

• **AlwaysLoadOnServer**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AlwaysLoadOnServer](ue_ue.FXSystemComponent.md#alwaysloadonserver)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AssetUserData](ue_ue.FXSystemComponent.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AttachChildren](ue_ue.FXSystemComponent.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AttachParent](ue_ue.FXSystemComponent.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AttachSocketName](ue_ue.FXSystemComponent.md#attachsocketname)

___

### AutoAttachLocationRule

• **AutoAttachLocationRule**: [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md)

___

### AutoAttachLocationType

• **AutoAttachLocationType**: [`EAttachLocation`](../enums/ue_ue.EAttachLocation.md)

___

### AutoAttachParent

• **AutoAttachParent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

___

### AutoAttachRotationRule

• **AutoAttachRotationRule**: [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md)

___

### AutoAttachScaleRule

• **AutoAttachScaleRule**: [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md)

___

### AutoAttachSocketName

• **AutoAttachSocketName**: `string`

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[BodyInstance](ue_ue.FXSystemComponent.md#bodyinstance)

___

### BoundsScale

• **BoundsScale**: `number`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[BoundsScale](ue_ue.FXSystemComponent.md#boundsscale)

___

### CachedMaxDrawDistance

• **CachedMaxDrawDistance**: `number`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[CachedMaxDrawDistance](ue_ue.FXSystemComponent.md#cachedmaxdrawdistance)

___

### CanBeCharacterBase

• **CanBeCharacterBase**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[CanBeCharacterBase](ue_ue.FXSystemComponent.md#canbecharacterbase)

___

### CanCharacterStepUpOn

• **CanCharacterStepUpOn**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[CanCharacterStepUpOn](ue_ue.FXSystemComponent.md#cancharacterstepupon)

___

### CastShadow

• **CastShadow**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[CastShadow](ue_ue.FXSystemComponent.md#castshadow)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[ClientAttachedChildren](ue_ue.FXSystemComponent.md#clientattachedchildren)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[ComponentTags](ue_ue.FXSystemComponent.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[ComponentVelocity](ue_ue.FXSystemComponent.md#componentvelocity)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[CreationMethod](ue_ue.FXSystemComponent.md#creationmethod)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[CustomDepthStencilValue](ue_ue.FXSystemComponent.md#customdepthstencilvalue)

___

### CustomDepthStencilWriteMask

• **CustomDepthStencilWriteMask**: [`ERendererStencilMask`](../enums/ue_ue.ERendererStencilMask.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[CustomDepthStencilWriteMask](ue_ue.FXSystemComponent.md#customdepthstencilwritemask)

___

### CustomPrimitiveData

• **CustomPrimitiveData**: [`CustomPrimitiveData`](ue_ue.CustomPrimitiveData.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[CustomPrimitiveData](ue_ue.FXSystemComponent.md#customprimitivedata)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

___

### DepthPriorityGroup

• **DepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[DepthPriorityGroup](ue_ue.FXSystemComponent.md#depthprioritygroup)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[DetailMode](ue_ue.FXSystemComponent.md#detailmode)

___

### EditorDetailMode

• **EditorDetailMode**: `number`

___

### EditorLODLevel

• **EditorLODLevel**: `number`

___

### EmitterMaterials

• **EmitterMaterials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

___

### ExcludeForSpecificHLODLevels

• **ExcludeForSpecificHLODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[ExcludeForSpecificHLODLevels](ue_ue.FXSystemComponent.md#excludeforspecifichlodlevels)

___

### IndirectLightingCacheQuality

• **IndirectLightingCacheQuality**: [`EIndirectLightingCacheQuality`](../enums/ue_ue.EIndirectLightingCacheQuality.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[IndirectLightingCacheQuality](ue_ue.FXSystemComponent.md#indirectlightingcachequality)

___

### InstanceParameters

• **InstanceParameters**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleSysParam`](ue_ue.ParticleSysParam.md)\>

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[LDMaxDrawDistance](ue_ue.FXSystemComponent.md#ldmaxdrawdistance)

___

### LODMethod

• **LODMethod**: [`ParticleSystemLODMethod`](../enums/ue_ue.ParticleSystemLODMethod.md)

___

### LODParentPrimitive

• **LODParentPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[LODParentPrimitive](ue_ue.FXSystemComponent.md#lodparentprimitive)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[LightingChannels](ue_ue.FXSystemComponent.md#lightingchannels)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[LightmapType](ue_ue.FXSystemComponent.md#lightmaptype)

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[LpvBiasMultiplier](ue_ue.FXSystemComponent.md#lpvbiasmultiplier)

___

### MaxTimeBeforeForceUpdateTransform

• **MaxTimeBeforeForceUpdateTransform**: `number`

___

### MinDrawDistance

• **MinDrawDistance**: `number`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[MinDrawDistance](ue_ue.FXSystemComponent.md#mindrawdistance)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[Mobility](ue_ue.FXSystemComponent.md#mobility)

___

### MoveIgnoreActors

• **MoveIgnoreActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[MoveIgnoreActors](ue_ue.FXSystemComponent.md#moveignoreactors)

___

### MoveIgnoreComponents

• **MoveIgnoreComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[MoveIgnoreComponents](ue_ue.FXSystemComponent.md#moveignorecomponents)

___

### OldPosition

• **OldPosition**: [`Vector`](ue_ue_s.Vector.md)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnBeginCursorOver](ue_ue.FXSystemComponent.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnClicked](ue_ue.FXSystemComponent.md#onclicked)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnComponentActivated](ue_ue.FXSystemComponent.md#oncomponentactivated)

___

### OnComponentBeginOverlap

• **OnComponentBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`, `bFromSweep`: `boolean`, `SweepResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnComponentBeginOverlap](ue_ue.FXSystemComponent.md#oncomponentbeginoverlap)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnComponentDeactivated](ue_ue.FXSystemComponent.md#oncomponentdeactivated)

___

### OnComponentEndOverlap

• **OnComponentEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`) => `void`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnComponentEndOverlap](ue_ue.FXSystemComponent.md#oncomponentendoverlap)

___

### OnComponentHit

• **OnComponentHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`HitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnComponentHit](ue_ue.FXSystemComponent.md#oncomponenthit)

___

### OnComponentSleep

• **OnComponentSleep**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SleepingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnComponentSleep](ue_ue.FXSystemComponent.md#oncomponentsleep)

___

### OnComponentWake

• **OnComponentWake**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`WakingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnComponentWake](ue_ue.FXSystemComponent.md#oncomponentwake)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnEndCursorOver](ue_ue.FXSystemComponent.md#onendcursorover)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnInputTouchBegin](ue_ue.FXSystemComponent.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnInputTouchEnd](ue_ue.FXSystemComponent.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnInputTouchEnter](ue_ue.FXSystemComponent.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnInputTouchLeave](ue_ue.FXSystemComponent.md#oninputtouchleave)

___

### OnParticleBurst

• **OnParticleBurst**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`EventName`: `string`, `EmitterTime`: `number`, `ParticleCount`: `number`) => `void`\>

___

### OnParticleCollide

• **OnParticleCollide**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`EventName`: `string`, `EmitterTime`: `number`, `ParticleTime`: `number`, `Location`: [`Vector`](ue_ue_s.Vector.md), `Velocity`: [`Vector`](ue_ue_s.Vector.md), `Direction`: [`Vector`](ue_ue_s.Vector.md), `Normal`: [`Vector`](ue_ue_s.Vector.md), `BoneName`: `string`, `PhysMat`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)\>) => `void`\>

___

### OnParticleDeath

• **OnParticleDeath**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`EventName`: `string`, `EmitterTime`: `number`, `ParticleTime`: `number`, `Location`: [`Vector`](ue_ue_s.Vector.md), `Velocity`: [`Vector`](ue_ue_s.Vector.md), `Direction`: [`Vector`](ue_ue_s.Vector.md)) => `void`\>

___

### OnParticleSpawn

• **OnParticleSpawn**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`EventName`: `string`, `EmitterTime`: `number`, `Location`: [`Vector`](ue_ue_s.Vector.md), `Velocity`: [`Vector`](ue_ue_s.Vector.md)) => `void`\>

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnReleased](ue_ue.FXSystemComponent.md#onreleased)

___

### OnSystemFinished

• **OnSystemFinished**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`PSystem`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)\>) => `void`\>

___

### PartSysVelocity

• **PartSysVelocity**: [`Vector`](ue_ue_s.Vector.md)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[PhysicsVolume](ue_ue.FXSystemComponent.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.FXSystemComponent.md#physicsvolumechangeddelegate)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[PrimaryComponentTick](ue_ue.FXSystemComponent.md#primarycomponenttick)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[RelativeLocation](ue_ue.FXSystemComponent.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[RelativeRotation](ue_ue.FXSystemComponent.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[RelativeScale3D](ue_ue.FXSystemComponent.md#relativescale3d)

___

### ReplayClips

• **ReplayClips**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleSystemReplay`](ue_ue.ParticleSystemReplay.md)\>

___

### RequiredSignificance

• **RequiredSignificance**: [`EParticleSignificanceLevel`](../enums/ue_ue.EParticleSignificanceLevel.md)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[RuntimeVirtualTextures](ue_ue.FXSystemComponent.md#runtimevirtualtextures)

___

### SecondsBeforeInactive

• **SecondsBeforeInactive**: `number`

___

### SkelMeshComponents

• **SkelMeshComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)\>

___

### Template

• **Template**: [`ParticleSystem`](ue_ue.ParticleSystem.md)

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[TranslucencySortPriority](ue_ue.FXSystemComponent.md#translucencysortpriority)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[UCSModifiedProperties](ue_ue.FXSystemComponent.md#ucsmodifiedproperties)

___

### ViewOwnerDepthPriorityGroup

• **ViewOwnerDepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[ViewOwnerDepthPriorityGroup](ue_ue.FXSystemComponent.md#viewownerdepthprioritygroup)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[VirtualTextureCullMips](ue_ue.FXSystemComponent.md#virtualtexturecullmips)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[VirtualTextureLodBias](ue_ue.FXSystemComponent.md#virtualtexturelodbias)

___

### VirtualTextureMinCoverage

• **VirtualTextureMinCoverage**: `number`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[VirtualTextureMinCoverage](ue_ue.FXSystemComponent.md#virtualtexturemincoverage)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[VirtualTextureRenderPassType](ue_ue.FXSystemComponent.md#virtualtexturerenderpasstype)

___

### VisibilityId

• **VisibilityId**: `number`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[VisibilityId](ue_ue.FXSystemComponent.md#visibilityid)

___

### WarmupTickRate

• **WarmupTickRate**: `number`

___

### WarmupTime

• **WarmupTime**: `number`

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[__tid_ActorComponent__](ue_ue.FXSystemComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_FXSystemComponent\_\_

• **\_\_tid\_FXSystemComponent\_\_**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[__tid_FXSystemComponent__](ue_ue.FXSystemComponent.md#__tid_fxsystemcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[__tid_Object__](ue_ue.FXSystemComponent.md#__tid_object__)

___

### \_\_tid\_ParticleSystemComponent\_\_

• **\_\_tid\_ParticleSystemComponent\_\_**: `boolean`

___

### \_\_tid\_PrimitiveComponent\_\_

• **\_\_tid\_PrimitiveComponent\_\_**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[__tid_PrimitiveComponent__](ue_ue.FXSystemComponent.md#__tid_primitivecomponent__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[__tid_SceneComponent__](ue_ue.FXSystemComponent.md#__tid_scenecomponent__)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bAbsoluteLocation](ue_ue.FXSystemComponent.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bAbsoluteRotation](ue_ue.FXSystemComponent.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bAbsoluteScale](ue_ue.FXSystemComponent.md#babsolutescale)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bAffectDistanceFieldLighting](ue_ue.FXSystemComponent.md#baffectdistancefieldlighting)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bAffectDynamicIndirectLighting](ue_ue.FXSystemComponent.md#baffectdynamicindirectlighting)

___

### bAllowCullDistanceVolume

• **bAllowCullDistanceVolume**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bAllowCullDistanceVolume](ue_ue.FXSystemComponent.md#ballowculldistancevolume)

___

### bAllowRecycling

• **bAllowRecycling**: `boolean`

___

### bAlwaysCreatePhysicsState

• **bAlwaysCreatePhysicsState**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bAlwaysCreatePhysicsState](ue_ue.FXSystemComponent.md#balwayscreatephysicsstate)

___

### bApplyImpulseOnDamage

• **bApplyImpulseOnDamage**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bApplyImpulseOnDamage](ue_ue.FXSystemComponent.md#bapplyimpulseondamage)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bAutoActivate](ue_ue.FXSystemComponent.md#bautoactivate)

___

### bAutoManageAttachment

• **bAutoManageAttachment**: `boolean`

___

### bBatchImpostersAsInstances

• **bBatchImpostersAsInstances**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bBatchImpostersAsInstances](ue_ue.FXSystemComponent.md#bbatchimpostersasinstances)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.FXSystemComponent.md#bboundschangetriggersstreamingdatarebuild)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bCanEverAffectNavigation](ue_ue.FXSystemComponent.md#bcaneveraffectnavigation)

___

### bCastCinematicShadow

• **bCastCinematicShadow**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bCastCinematicShadow](ue_ue.FXSystemComponent.md#bcastcinematicshadow)

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bCastDynamicShadow](ue_ue.FXSystemComponent.md#bcastdynamicshadow)

___

### bCastFarShadow

• **bCastFarShadow**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bCastFarShadow](ue_ue.FXSystemComponent.md#bcastfarshadow)

___

### bCastHiddenShadow

• **bCastHiddenShadow**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bCastHiddenShadow](ue_ue.FXSystemComponent.md#bcasthiddenshadow)

___

### bCastInsetShadow

• **bCastInsetShadow**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bCastInsetShadow](ue_ue.FXSystemComponent.md#bcastinsetshadow)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bCastShadowAsTwoSided](ue_ue.FXSystemComponent.md#bcastshadowastwosided)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bCastStaticShadow](ue_ue.FXSystemComponent.md#bcaststaticshadow)

___

### bCastVolumetricTranslucentShadow

• **bCastVolumetricTranslucentShadow**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bCastVolumetricTranslucentShadow](ue_ue.FXSystemComponent.md#bcastvolumetrictranslucentshadow)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bComponentToWorldUpdated](ue_ue.FXSystemComponent.md#bcomponenttoworldupdated)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bCreatedByConstructionScript](ue_ue.FXSystemComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bEditableWhenInherited](ue_ue.FXSystemComponent.md#beditablewheninherited)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bEnableAutoLODGeneration](ue_ue.FXSystemComponent.md#benableautolodgeneration)

___

### bExcludeFromLightAttachmentGroup

• **bExcludeFromLightAttachmentGroup**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bExcludeFromLightAttachmentGroup](ue_ue.FXSystemComponent.md#bexcludefromlightattachmentgroup)

___

### bForceMipStreaming

• **bForceMipStreaming**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bForceMipStreaming](ue_ue.FXSystemComponent.md#bforcemipstreaming)

___

### bGenerateOverlapEvents

• **bGenerateOverlapEvents**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bGenerateOverlapEvents](ue_ue.FXSystemComponent.md#bgenerateoverlapevents)

___

### bHasCustomNavigableGeometry

• **bHasCustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bHasCustomNavigableGeometry](ue_ue.FXSystemComponent.md#bhascustomnavigablegeometry)

___

### bHasMotionBlurVelocityMeshes

• **bHasMotionBlurVelocityMeshes**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bHasMotionBlurVelocityMeshes](ue_ue.FXSystemComponent.md#bhasmotionblurvelocitymeshes)

___

### bHasPerInstanceHitProxies

• **bHasPerInstanceHitProxies**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bHasPerInstanceHitProxies](ue_ue.FXSystemComponent.md#bhasperinstancehitproxies)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bHiddenInGame](ue_ue.FXSystemComponent.md#bhiddeningame)

___

### bIgnoreRadialForce

• **bIgnoreRadialForce**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bIgnoreRadialForce](ue_ue.FXSystemComponent.md#bignoreradialforce)

___

### bIgnoreRadialImpulse

• **bIgnoreRadialImpulse**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bIgnoreRadialImpulse](ue_ue.FXSystemComponent.md#bignoreradialimpulse)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bInstanceComponent](ue_ue.FXSystemComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bIsActive](ue_ue.FXSystemComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bIsEditorOnly](ue_ue.FXSystemComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bIsVisualizationComponent](ue_ue.FXSystemComponent.md#bisvisualizationcomponent)

___

### bLightAsIfStatic

• **bLightAsIfStatic**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bLightAsIfStatic](ue_ue.FXSystemComponent.md#blightasifstatic)

___

### bLightAttachmentsAsGroup

• **bLightAttachmentsAsGroup**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bLightAttachmentsAsGroup](ue_ue.FXSystemComponent.md#blightattachmentsasgroup)

___

### bMultiBodyOverlap

• **bMultiBodyOverlap**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bMultiBodyOverlap](ue_ue.FXSystemComponent.md#bmultibodyoverlap)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bNetAddressable](ue_ue.FXSystemComponent.md#bnetaddressable)

___

### bNeverDistanceCull

• **bNeverDistanceCull**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bNeverDistanceCull](ue_ue.FXSystemComponent.md#bneverdistancecull)

___

### bOnlyOwnerSee

• **bOnlyOwnerSee**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bOnlyOwnerSee](ue_ue.FXSystemComponent.md#bonlyownersee)

___

### bOverrideLODMethod

• **bOverrideLODMethod**: `boolean`

___

### bOwnerNoSee

• **bOwnerNoSee**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bOwnerNoSee](ue_ue.FXSystemComponent.md#bownernosee)

___

### bReceiveMobileCSMShadows

• **bReceiveMobileCSMShadows**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bReceiveMobileCSMShadows](ue_ue.FXSystemComponent.md#breceivemobilecsmshadows)

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bReceivesDecals](ue_ue.FXSystemComponent.md#breceivesdecals)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bRenderCustomDepth](ue_ue.FXSystemComponent.md#brendercustomdepth)

___

### bRenderInDepthPass

• **bRenderInDepthPass**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bRenderInDepthPass](ue_ue.FXSystemComponent.md#brenderindepthpass)

___

### bRenderInMainPass

• **bRenderInMainPass**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bRenderInMainPass](ue_ue.FXSystemComponent.md#brenderinmainpass)

___

### bReplicatePhysicsToAutonomousProxy

• **bReplicatePhysicsToAutonomousProxy**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bReplicatePhysicsToAutonomousProxy](ue_ue.FXSystemComponent.md#breplicatephysicstoautonomousproxy)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bReplicates](ue_ue.FXSystemComponent.md#breplicates)

___

### bResetOnDetach

• **bResetOnDetach**: `boolean`

___

### bReturnMaterialOnMove

• **bReturnMaterialOnMove**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bReturnMaterialOnMove](ue_ue.FXSystemComponent.md#breturnmaterialonmove)

___

### bSelectable

• **bSelectable**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bSelectable](ue_ue.FXSystemComponent.md#bselectable)

___

### bSelfShadowOnly

• **bSelfShadowOnly**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bSelfShadowOnly](ue_ue.FXSystemComponent.md#bselfshadowonly)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bShouldBeAttached](ue_ue.FXSystemComponent.md#bshouldbeattached)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.FXSystemComponent.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.FXSystemComponent.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.FXSystemComponent.md#bshouldupdatephysicsvolume)

___

### bSingleSampleShadowFromStationaryLights

• **bSingleSampleShadowFromStationaryLights**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bSingleSampleShadowFromStationaryLights](ue_ue.FXSystemComponent.md#bsinglesampleshadowfromstationarylights)

___

### bSkipUpdateDynamicDataDuringTick

• **bSkipUpdateDynamicDataDuringTick**: `boolean`

___

### bTraceComplexOnMove

• **bTraceComplexOnMove**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bTraceComplexOnMove](ue_ue.FXSystemComponent.md#btracecomplexonmove)

___

### bTreatAsBackgroundForOcclusion

• **bTreatAsBackgroundForOcclusion**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bTreatAsBackgroundForOcclusion](ue_ue.FXSystemComponent.md#btreatasbackgroundforocclusion)

___

### bUpdateOnDedicatedServer

• **bUpdateOnDedicatedServer**: `boolean`

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bUseAsOccluder](ue_ue.FXSystemComponent.md#buseasoccluder)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bUseAttachParentBound](ue_ue.FXSystemComponent.md#buseattachparentbound)

___

### bUseEditorCompositing

• **bUseEditorCompositing**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bUseEditorCompositing](ue_ue.FXSystemComponent.md#buseeditorcompositing)

___

### bUseMaxLODAsImposter

• **bUseMaxLODAsImposter**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bUseMaxLODAsImposter](ue_ue.FXSystemComponent.md#busemaxlodasimposter)

___

### bUseViewOwnerDepthPriorityGroup

• **bUseViewOwnerDepthPriorityGroup**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bUseViewOwnerDepthPriorityGroup](ue_ue.FXSystemComponent.md#buseviewownerdepthprioritygroup)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bVisible](ue_ue.FXSystemComponent.md#bvisible)

___

### bVisibleInRayTracing

• **bVisibleInRayTracing**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bVisibleInRayTracing](ue_ue.FXSystemComponent.md#bvisibleinraytracing)

___

### bVisibleInReflectionCaptures

• **bVisibleInReflectionCaptures**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bVisibleInReflectionCaptures](ue_ue.FXSystemComponent.md#bvisibleinreflectioncaptures)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[bVisualizeComponent](ue_ue.FXSystemComponent.md#bvisualizecomponent)

___

### bWarmingUp

• **bWarmingUp**: `boolean`

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[Activate](ue_ue.FXSystemComponent.md#activate)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AddAngularImpulse](ue_ue.FXSystemComponent.md#addangularimpulse)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AddAngularImpulseInDegrees](ue_ue.FXSystemComponent.md#addangularimpulseindegrees)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AddAngularImpulseInRadians](ue_ue.FXSystemComponent.md#addangularimpulseinradians)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AddForce](ue_ue.FXSystemComponent.md#addforce)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AddForceAtLocation](ue_ue.FXSystemComponent.md#addforceatlocation)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AddForceAtLocationLocal](ue_ue.FXSystemComponent.md#addforceatlocationlocal)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AddImpulse](ue_ue.FXSystemComponent.md#addimpulse)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AddImpulseAtLocation](ue_ue.FXSystemComponent.md#addimpulseatlocation)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AddRadialForce](ue_ue.FXSystemComponent.md#addradialforce)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AddRadialImpulse](ue_ue.FXSystemComponent.md#addradialimpulse)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AddTickPrerequisiteActor](ue_ue.FXSystemComponent.md#addtickprerequisiteactor)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AddTickPrerequisiteComponent](ue_ue.FXSystemComponent.md#addtickprerequisitecomponent)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AddTorque](ue_ue.FXSystemComponent.md#addtorque)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AddTorqueInDegrees](ue_ue.FXSystemComponent.md#addtorqueindegrees)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[AddTorqueInRadians](ue_ue.FXSystemComponent.md#addtorqueinradians)

___

### BeginTrails

▸ **BeginTrails**(`InFirstSocketName`, `InSecondSocketName`, `InWidthMode`, `InWidth`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFirstSocketName` | `string` |
| `InSecondSocketName` | `string` |
| `InWidthMode` | [`ETrailWidthMode`](../enums/ue_ue.ETrailWidthMode.md) |
| `InWidth` | `number` |

#### Returns

`void`

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[CanCharacterStepUp](ue_ue.FXSystemComponent.md#cancharacterstepup)

___

### ClearMoveIgnoreActors

▸ **ClearMoveIgnoreActors**(): `void`

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[ClearMoveIgnoreActors](ue_ue.FXSystemComponent.md#clearmoveignoreactors)

___

### ClearMoveIgnoreComponents

▸ **ClearMoveIgnoreComponents**(): `void`

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[ClearMoveIgnoreComponents](ue_ue.FXSystemComponent.md#clearmoveignorecomponents)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[ComponentHasTag](ue_ue.FXSystemComponent.md#componenthastag)

___

### CopyArrayOfMoveIgnoreActors

▸ **CopyArrayOfMoveIgnoreActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[CopyArrayOfMoveIgnoreActors](ue_ue.FXSystemComponent.md#copyarrayofmoveignoreactors)

___

### CopyArrayOfMoveIgnoreComponents

▸ **CopyArrayOfMoveIgnoreComponents**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[CopyArrayOfMoveIgnoreComponents](ue_ue.FXSystemComponent.md#copyarrayofmoveignorecomponents)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[CreateAndSetMaterialInstanceDynamic](ue_ue.FXSystemComponent.md#createandsetmaterialinstancedynamic)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.FXSystemComponent.md#createandsetmaterialinstancedynamicfrommaterial)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[CreateDefaultSubobject](ue_ue.FXSystemComponent.md#createdefaultsubobject)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[CreateDynamicMaterialInstance](ue_ue.FXSystemComponent.md#createdynamicmaterialinstance)

___

### CreateNamedDynamicMaterialInstance

▸ **CreateNamedDynamicMaterialInstance**(`InName`, `SourceMaterial?`): [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |
| `SourceMaterial?` | [`MaterialInterface`](ue_ue.MaterialInterface.md) |

#### Returns

[`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[Deactivate](ue_ue.FXSystemComponent.md#deactivate)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[DetachFromParent](ue_ue.FXSystemComponent.md#detachfromparent)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[DoesSocketExist](ue_ue.FXSystemComponent.md#doessocketexist)

___

### EndTrails

▸ **EndTrails**(): `void`

#### Returns

`void`

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[ExecuteUbergraph](ue_ue.FXSystemComponent.md#executeubergraph)

___

### GenerateParticleEvent

▸ **GenerateParticleEvent**(`InEventName`, `InEmitterTime`, `InLocation`, `InDirection`, `InVelocity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InEventName` | `string` |
| `InEmitterTime` | `number` |
| `InLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `InDirection` | [`Vector`](ue_ue_s.Vector.md) |
| `InVelocity` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetAllSocketNames](ue_ue.FXSystemComponent.md#getallsocketnames)

___

### GetAngularDamping

▸ **GetAngularDamping**(): `number`

#### Returns

`number`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetAngularDamping](ue_ue.FXSystemComponent.md#getangulardamping)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetAttachParent](ue_ue.FXSystemComponent.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetAttachSocketName](ue_ue.FXSystemComponent.md#getattachsocketname)

___

### GetBeamEndPoint

▸ **GetBeamEndPoint**(`EmitterIndex`, `OutEndPoint`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EmitterIndex` | `number` |
| `OutEndPoint` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`boolean`

___

### GetBeamSourcePoint

▸ **GetBeamSourcePoint**(`EmitterIndex`, `SourceIndex`, `OutSourcePoint`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EmitterIndex` | `number` |
| `SourceIndex` | `number` |
| `OutSourcePoint` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`boolean`

___

### GetBeamSourceStrength

▸ **GetBeamSourceStrength**(`EmitterIndex`, `SourceIndex`, `OutSourceStrength`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EmitterIndex` | `number` |
| `SourceIndex` | `number` |
| `OutSourceStrength` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`boolean`

___

### GetBeamSourceTangent

▸ **GetBeamSourceTangent**(`EmitterIndex`, `SourceIndex`, `OutTangentPoint`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EmitterIndex` | `number` |
| `SourceIndex` | `number` |
| `OutTangentPoint` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`boolean`

___

### GetBeamTargetPoint

▸ **GetBeamTargetPoint**(`EmitterIndex`, `TargetIndex`, `OutTargetPoint`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EmitterIndex` | `number` |
| `TargetIndex` | `number` |
| `OutTargetPoint` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`boolean`

___

### GetBeamTargetStrength

▸ **GetBeamTargetStrength**(`EmitterIndex`, `TargetIndex`, `OutTargetStrength`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EmitterIndex` | `number` |
| `TargetIndex` | `number` |
| `OutTargetStrength` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`boolean`

___

### GetBeamTargetTangent

▸ **GetBeamTargetTangent**(`EmitterIndex`, `TargetIndex`, `OutTangentPoint`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EmitterIndex` | `number` |
| `TargetIndex` | `number` |
| `OutTangentPoint` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`boolean`

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetCenterOfMass](ue_ue.FXSystemComponent.md#getcenterofmass)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetChildComponent](ue_ue.FXSystemComponent.md#getchildcomponent)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetChildrenComponents](ue_ue.FXSystemComponent.md#getchildrencomponents)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetClass](ue_ue.FXSystemComponent.md#getclass)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetClosestPointOnCollision](ue_ue.FXSystemComponent.md#getclosestpointoncollision)

___

### GetCollisionEnabled

▸ **GetCollisionEnabled**(): [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Returns

[`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetCollisionEnabled](ue_ue.FXSystemComponent.md#getcollisionenabled)

___

### GetCollisionObjectType

▸ **GetCollisionObjectType**(): [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Returns

[`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetCollisionObjectType](ue_ue.FXSystemComponent.md#getcollisionobjecttype)

___

### GetCollisionProfileName

▸ **GetCollisionProfileName**(): `string`

#### Returns

`string`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetCollisionProfileName](ue_ue.FXSystemComponent.md#getcollisionprofilename)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetCollisionResponseToChannel](ue_ue.FXSystemComponent.md#getcollisionresponsetochannel)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetComponentTickInterval](ue_ue.FXSystemComponent.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetComponentVelocity](ue_ue.FXSystemComponent.md#getcomponentvelocity)

___

### GetFXSystemAsset

▸ **GetFXSystemAsset**(): [`FXSystemAsset`](ue_ue.FXSystemAsset.md)

#### Returns

[`FXSystemAsset`](ue_ue.FXSystemAsset.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetFXSystemAsset](ue_ue.FXSystemComponent.md#getfxsystemasset)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetForwardVector](ue_ue.FXSystemComponent.md#getforwardvector)

___

### GetGenerateOverlapEvents

▸ **GetGenerateOverlapEvents**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetGenerateOverlapEvents](ue_ue.FXSystemComponent.md#getgenerateoverlapevents)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetInertiaTensor](ue_ue.FXSystemComponent.md#getinertiatensor)

___

### GetLinearDamping

▸ **GetLinearDamping**(): `number`

#### Returns

`number`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetLinearDamping](ue_ue.FXSystemComponent.md#getlineardamping)

___

### GetMass

▸ **GetMass**(): `number`

#### Returns

`number`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetMass](ue_ue.FXSystemComponent.md#getmass)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetMassScale](ue_ue.FXSystemComponent.md#getmassscale)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetMaterial](ue_ue.FXSystemComponent.md#getmaterial)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetMaterialFromCollisionFaceIndex](ue_ue.FXSystemComponent.md#getmaterialfromcollisionfaceindex)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetName](ue_ue.FXSystemComponent.md#getname)

___

### GetNamedMaterial

▸ **GetNamedMaterial**(`InName`): [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### GetNumActiveParticles

▸ **GetNumActiveParticles**(): `number`

#### Returns

`number`

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetNumChildrenComponents](ue_ue.FXSystemComponent.md#getnumchildrencomponents)

___

### GetNumMaterials

▸ **GetNumMaterials**(): `number`

#### Returns

`number`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetNumMaterials](ue_ue.FXSystemComponent.md#getnummaterials)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetOuter](ue_ue.FXSystemComponent.md#getouter)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetOverlappingActors](ue_ue.FXSystemComponent.md#getoverlappingactors)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetOverlappingComponents](ue_ue.FXSystemComponent.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetOwner](ue_ue.FXSystemComponent.md#getowner)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetParentComponents](ue_ue.FXSystemComponent.md#getparentcomponents)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetPhysicsAngularVelocity](ue_ue.FXSystemComponent.md#getphysicsangularvelocity)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetPhysicsAngularVelocityInDegrees](ue_ue.FXSystemComponent.md#getphysicsangularvelocityindegrees)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetPhysicsAngularVelocityInRadians](ue_ue.FXSystemComponent.md#getphysicsangularvelocityinradians)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetPhysicsLinearVelocity](ue_ue.FXSystemComponent.md#getphysicslinearvelocity)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetPhysicsLinearVelocityAtPoint](ue_ue.FXSystemComponent.md#getphysicslinearvelocityatpoint)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetPhysicsVolume](ue_ue.FXSystemComponent.md#getphysicsvolume)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetRelativeTransform](ue_ue.FXSystemComponent.md#getrelativetransform)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetRightVector](ue_ue.FXSystemComponent.md#getrightvector)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.FXSystemComponent.md#getshouldupdatephysicsvolume)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetSocketLocation](ue_ue.FXSystemComponent.md#getsocketlocation)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetSocketQuaternion](ue_ue.FXSystemComponent.md#getsocketquaternion)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetSocketRotation](ue_ue.FXSystemComponent.md#getsocketrotation)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetSocketTransform](ue_ue.FXSystemComponent.md#getsockettransform)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetUpVector](ue_ue.FXSystemComponent.md#getupvector)

___

### GetWalkableSlopeOverride

▸ **GetWalkableSlopeOverride**(): [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Returns

[`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetWalkableSlopeOverride](ue_ue.FXSystemComponent.md#getwalkableslopeoverride)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[GetWorld](ue_ue.FXSystemComponent.md#getworld)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[IgnoreActorWhenMoving](ue_ue.FXSystemComponent.md#ignoreactorwhenmoving)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[IgnoreComponentWhenMoving](ue_ue.FXSystemComponent.md#ignorecomponentwhenmoving)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[IsActive](ue_ue.FXSystemComponent.md#isactive)

___

### IsAnyRigidBodyAwake

▸ **IsAnyRigidBodyAwake**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[IsAnyRigidBodyAwake](ue_ue.FXSystemComponent.md#isanyrigidbodyawake)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[IsAnySimulatingPhysics](ue_ue.FXSystemComponent.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[IsBeingDestroyed](ue_ue.FXSystemComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[IsComponentTickEnabled](ue_ue.FXSystemComponent.md#iscomponenttickenabled)

___

### IsGravityEnabled

▸ **IsGravityEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[IsGravityEnabled](ue_ue.FXSystemComponent.md#isgravityenabled)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[IsOverlappingActor](ue_ue.FXSystemComponent.md#isoverlappingactor)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[IsOverlappingComponent](ue_ue.FXSystemComponent.md#isoverlappingcomponent)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[IsSimulatingPhysics](ue_ue.FXSystemComponent.md#issimulatingphysics)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[IsVisible](ue_ue.FXSystemComponent.md#isvisible)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_AddLocalOffset](ue_ue.FXSystemComponent.md#k2_addlocaloffset)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_AddLocalRotation](ue_ue.FXSystemComponent.md#k2_addlocalrotation)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_AddLocalTransform](ue_ue.FXSystemComponent.md#k2_addlocaltransform)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_AddRelativeLocation](ue_ue.FXSystemComponent.md#k2_addrelativelocation)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_AddRelativeRotation](ue_ue.FXSystemComponent.md#k2_addrelativerotation)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_AddWorldOffset](ue_ue.FXSystemComponent.md#k2_addworldoffset)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_AddWorldRotation](ue_ue.FXSystemComponent.md#k2_addworldrotation)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_AddWorldTransform](ue_ue.FXSystemComponent.md#k2_addworldtransform)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_AttachTo](ue_ue.FXSystemComponent.md#k2_attachto)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_AttachToComponent](ue_ue.FXSystemComponent.md#k2_attachtocomponent)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_BoxOverlapComponent](ue_ue.FXSystemComponent.md#k2_boxoverlapcomponent)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_DestroyComponent](ue_ue.FXSystemComponent.md#k2_destroycomponent)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_DetachFromComponent](ue_ue.FXSystemComponent.md#k2_detachfromcomponent)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_GetComponentLocation](ue_ue.FXSystemComponent.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_GetComponentRotation](ue_ue.FXSystemComponent.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_GetComponentScale](ue_ue.FXSystemComponent.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_GetComponentToWorld](ue_ue.FXSystemComponent.md#k2_getcomponenttoworld)

___

### K2\_IsCollisionEnabled

▸ **K2_IsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_IsCollisionEnabled](ue_ue.FXSystemComponent.md#k2_iscollisionenabled)

___

### K2\_IsPhysicsCollisionEnabled

▸ **K2_IsPhysicsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_IsPhysicsCollisionEnabled](ue_ue.FXSystemComponent.md#k2_isphysicscollisionenabled)

___

### K2\_IsQueryCollisionEnabled

▸ **K2_IsQueryCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_IsQueryCollisionEnabled](ue_ue.FXSystemComponent.md#k2_isquerycollisionenabled)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_LineTraceComponent](ue_ue.FXSystemComponent.md#k2_linetracecomponent)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_SetRelativeLocation](ue_ue.FXSystemComponent.md#k2_setrelativelocation)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.FXSystemComponent.md#k2_setrelativelocationandrotation)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_SetRelativeRotation](ue_ue.FXSystemComponent.md#k2_setrelativerotation)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_SetRelativeTransform](ue_ue.FXSystemComponent.md#k2_setrelativetransform)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_SetWorldLocation](ue_ue.FXSystemComponent.md#k2_setworldlocation)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.FXSystemComponent.md#k2_setworldlocationandrotation)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_SetWorldRotation](ue_ue.FXSystemComponent.md#k2_setworldrotation)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_SetWorldTransform](ue_ue.FXSystemComponent.md#k2_setworldtransform)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_SphereOverlapComponent](ue_ue.FXSystemComponent.md#k2_sphereoverlapcomponent)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[K2_SphereTraceComponent](ue_ue.FXSystemComponent.md#k2_spheretracecomponent)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnRep_AttachChildren](ue_ue.FXSystemComponent.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnRep_AttachParent](ue_ue.FXSystemComponent.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnRep_AttachSocketName](ue_ue.FXSystemComponent.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnRep_IsActive](ue_ue.FXSystemComponent.md#onrep_isactive)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnRep_Transform](ue_ue.FXSystemComponent.md#onrep_transform)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[OnRep_Visibility](ue_ue.FXSystemComponent.md#onrep_visibility)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[PutRigidBodyToSleep](ue_ue.FXSystemComponent.md#putrigidbodytosleep)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[ReceiveBeginPlay](ue_ue.FXSystemComponent.md#receivebeginplay)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[ReceiveEndPlay](ue_ue.FXSystemComponent.md#receiveendplay)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[ReceiveTick](ue_ue.FXSystemComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[RegisterComponent](ue_ue.FXSystemComponent.md#registercomponent)

___

### ReleaseToPool

▸ **ReleaseToPool**(): `void`

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[ReleaseToPool](ue_ue.FXSystemComponent.md#releasetopool)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[RemoveTickPrerequisiteActor](ue_ue.FXSystemComponent.md#removetickprerequisiteactor)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.FXSystemComponent.md#removetickprerequisitecomponent)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[ResetRelativeTransform](ue_ue.FXSystemComponent.md#resetrelativetransform)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[ScaleByMomentOfInertia](ue_ue.FXSystemComponent.md#scalebymomentofinertia)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetAbsolute](ue_ue.FXSystemComponent.md#setabsolute)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetActive](ue_ue.FXSystemComponent.md#setactive)

___

### SetActorParameter

▸ **SetActorParameter**(`ParameterName`, `Param`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `Param` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetActorParameter](ue_ue.FXSystemComponent.md#setactorparameter)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetAllMassScale](ue_ue.FXSystemComponent.md#setallmassscale)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetAllPhysicsAngularVelocityInDegrees](ue_ue.FXSystemComponent.md#setallphysicsangularvelocityindegrees)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetAllPhysicsAngularVelocityInRadians](ue_ue.FXSystemComponent.md#setallphysicsangularvelocityinradians)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetAllPhysicsLinearVelocity](ue_ue.FXSystemComponent.md#setallphysicslinearvelocity)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetAllUseCCD](ue_ue.FXSystemComponent.md#setalluseccd)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetAngularDamping](ue_ue.FXSystemComponent.md#setangulardamping)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetAutoActivate](ue_ue.FXSystemComponent.md#setautoactivate)

___

### SetAutoAttachParams

▸ **SetAutoAttachParams**(`Parent`, `SocketName?`, `LocationType?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Parent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `SocketName?` | `string` |
| `LocationType?` | [`EAttachLocation`](../enums/ue_ue.EAttachLocation.md) |

#### Returns

`void`

___

### SetAutoAttachmentParameters

▸ **SetAutoAttachmentParameters**(`Parent`, `SocketName`, `LocationRule`, `RotationRule`, `ScaleRule`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Parent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `SocketName` | `string` |
| `LocationRule` | [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md) |
| `RotationRule` | [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md) |
| `ScaleRule` | [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md) |

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetAutoAttachmentParameters](ue_ue.FXSystemComponent.md#setautoattachmentparameters)

___

### SetBeamEndPoint

▸ **SetBeamEndPoint**(`EmitterIndex`, `NewEndPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EmitterIndex` | `number` |
| `NewEndPoint` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### SetBeamSourcePoint

▸ **SetBeamSourcePoint**(`EmitterIndex`, `NewSourcePoint`, `SourceIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EmitterIndex` | `number` |
| `NewSourcePoint` | [`Vector`](ue_ue_s.Vector.md) |
| `SourceIndex` | `number` |

#### Returns

`void`

___

### SetBeamSourceStrength

▸ **SetBeamSourceStrength**(`EmitterIndex`, `NewSourceStrength`, `SourceIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EmitterIndex` | `number` |
| `NewSourceStrength` | `number` |
| `SourceIndex` | `number` |

#### Returns

`void`

___

### SetBeamSourceTangent

▸ **SetBeamSourceTangent**(`EmitterIndex`, `NewTangentPoint`, `SourceIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EmitterIndex` | `number` |
| `NewTangentPoint` | [`Vector`](ue_ue_s.Vector.md) |
| `SourceIndex` | `number` |

#### Returns

`void`

___

### SetBeamTargetPoint

▸ **SetBeamTargetPoint**(`EmitterIndex`, `NewTargetPoint`, `TargetIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EmitterIndex` | `number` |
| `NewTargetPoint` | [`Vector`](ue_ue_s.Vector.md) |
| `TargetIndex` | `number` |

#### Returns

`void`

___

### SetBeamTargetStrength

▸ **SetBeamTargetStrength**(`EmitterIndex`, `NewTargetStrength`, `TargetIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EmitterIndex` | `number` |
| `NewTargetStrength` | `number` |
| `TargetIndex` | `number` |

#### Returns

`void`

___

### SetBeamTargetTangent

▸ **SetBeamTargetTangent**(`EmitterIndex`, `NewTangentPoint`, `TargetIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EmitterIndex` | `number` |
| `NewTangentPoint` | [`Vector`](ue_ue_s.Vector.md) |
| `TargetIndex` | `number` |

#### Returns

`void`

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetBoundsScale](ue_ue.FXSystemComponent.md#setboundsscale)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetCastInsetShadow](ue_ue.FXSystemComponent.md#setcastinsetshadow)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetCastShadow](ue_ue.FXSystemComponent.md#setcastshadow)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetCenterOfMass](ue_ue.FXSystemComponent.md#setcenterofmass)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetCollisionEnabled](ue_ue.FXSystemComponent.md#setcollisionenabled)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetCollisionObjectType](ue_ue.FXSystemComponent.md#setcollisionobjecttype)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetCollisionProfileName](ue_ue.FXSystemComponent.md#setcollisionprofilename)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetCollisionResponseToAllChannels](ue_ue.FXSystemComponent.md#setcollisionresponsetoallchannels)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetCollisionResponseToChannel](ue_ue.FXSystemComponent.md#setcollisionresponsetochannel)

___

### SetColorParameter

▸ **SetColorParameter**(`ParameterName`, `Param`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `Param` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetColorParameter](ue_ue.FXSystemComponent.md#setcolorparameter)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetComponentTickEnabled](ue_ue.FXSystemComponent.md#setcomponenttickenabled)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetComponentTickInterval](ue_ue.FXSystemComponent.md#setcomponenttickinterval)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetConstraintMode](ue_ue.FXSystemComponent.md#setconstraintmode)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetCullDistance](ue_ue.FXSystemComponent.md#setculldistance)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetCustomDepthStencilValue](ue_ue.FXSystemComponent.md#setcustomdepthstencilvalue)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetCustomDepthStencilWriteMask](ue_ue.FXSystemComponent.md#setcustomdepthstencilwritemask)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetCustomPrimitiveDataFloat](ue_ue.FXSystemComponent.md#setcustomprimitivedatafloat)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetCustomPrimitiveDataVector2](ue_ue.FXSystemComponent.md#setcustomprimitivedatavector2)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetCustomPrimitiveDataVector3](ue_ue.FXSystemComponent.md#setcustomprimitivedatavector3)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetCustomPrimitiveDataVector4](ue_ue.FXSystemComponent.md#setcustomprimitivedatavector4)

___

### SetEmitterEnable

▸ **SetEmitterEnable**(`EmitterName`, `bNewEnableState`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EmitterName` | `string` |
| `bNewEnableState` | `boolean` |

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetEmitterEnable](ue_ue.FXSystemComponent.md#setemitterenable)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetEnableGravity](ue_ue.FXSystemComponent.md#setenablegravity)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetExcludeFromLightAttachmentGroup](ue_ue.FXSystemComponent.md#setexcludefromlightattachmentgroup)

___

### SetFloatParameter

▸ **SetFloatParameter**(`ParameterName`, `Param`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `Param` | `number` |

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetFloatParameter](ue_ue.FXSystemComponent.md#setfloatparameter)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetGenerateOverlapEvents](ue_ue.FXSystemComponent.md#setgenerateoverlapevents)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetHiddenInGame](ue_ue.FXSystemComponent.md#sethiddeningame)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetIsReplicated](ue_ue.FXSystemComponent.md#setisreplicated)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetLightAttachmentsAsGroup](ue_ue.FXSystemComponent.md#setlightattachmentsasgroup)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetLinearDamping](ue_ue.FXSystemComponent.md#setlineardamping)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetMassOverrideInKg](ue_ue.FXSystemComponent.md#setmassoverrideinkg)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetMassScale](ue_ue.FXSystemComponent.md#setmassscale)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetMaterial](ue_ue.FXSystemComponent.md#setmaterial)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetMaterialByName](ue_ue.FXSystemComponent.md#setmaterialbyname)

___

### SetMaterialParameter

▸ **SetMaterialParameter**(`ParameterName`, `Param`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `Param` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |

#### Returns

`void`

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetMobility](ue_ue.FXSystemComponent.md#setmobility)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetNotifyRigidBodyCollision](ue_ue.FXSystemComponent.md#setnotifyrigidbodycollision)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetOnlyOwnerSee](ue_ue.FXSystemComponent.md#setonlyownersee)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetOwnerNoSee](ue_ue.FXSystemComponent.md#setownernosee)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetPhysMaterialOverride](ue_ue.FXSystemComponent.md#setphysmaterialoverride)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetPhysicsAngularVelocity](ue_ue.FXSystemComponent.md#setphysicsangularvelocity)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetPhysicsAngularVelocityInDegrees](ue_ue.FXSystemComponent.md#setphysicsangularvelocityindegrees)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetPhysicsAngularVelocityInRadians](ue_ue.FXSystemComponent.md#setphysicsangularvelocityinradians)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetPhysicsLinearVelocity](ue_ue.FXSystemComponent.md#setphysicslinearvelocity)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetPhysicsMaxAngularVelocity](ue_ue.FXSystemComponent.md#setphysicsmaxangularvelocity)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetPhysicsMaxAngularVelocityInDegrees](ue_ue.FXSystemComponent.md#setphysicsmaxangularvelocityindegrees)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetPhysicsMaxAngularVelocityInRadians](ue_ue.FXSystemComponent.md#setphysicsmaxangularvelocityinradians)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetReceivesDecals](ue_ue.FXSystemComponent.md#setreceivesdecals)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetRelativeScale3D](ue_ue.FXSystemComponent.md#setrelativescale3d)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetRenderCustomDepth](ue_ue.FXSystemComponent.md#setrendercustomdepth)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetRenderInMainPass](ue_ue.FXSystemComponent.md#setrenderinmainpass)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.FXSystemComponent.md#setshouldupdatephysicsvolume)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetSimulatePhysics](ue_ue.FXSystemComponent.md#setsimulatephysics)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetSingleSampleShadowFromStationaryLights](ue_ue.FXSystemComponent.md#setsinglesampleshadowfromstationarylights)

___

### SetTemplate

▸ **SetTemplate**(`NewTemplate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTemplate` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ParticleSystem`](ue_ue.ParticleSystem.md)\> |

#### Returns

`void`

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetTickGroup](ue_ue.FXSystemComponent.md#settickgroup)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetTickableWhenPaused](ue_ue.FXSystemComponent.md#settickablewhenpaused)

___

### SetTrailSourceData

▸ **SetTrailSourceData**(`InFirstSocketName`, `InSecondSocketName`, `InWidthMode`, `InWidth`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFirstSocketName` | `string` |
| `InSecondSocketName` | `string` |
| `InWidthMode` | [`ETrailWidthMode`](../enums/ue_ue.ETrailWidthMode.md) |
| `InWidth` | `number` |

#### Returns

`void`

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetTranslucentSortPriority](ue_ue.FXSystemComponent.md#settranslucentsortpriority)

___

### SetUseAutoManageAttachment

▸ **SetUseAutoManageAttachment**(`bAutoManage`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bAutoManage` | `boolean` |

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetUseAutoManageAttachment](ue_ue.FXSystemComponent.md#setuseautomanageattachment)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetUseCCD](ue_ue.FXSystemComponent.md#setuseccd)

___

### SetVectorParameter

▸ **SetVectorParameter**(`ParameterName`, `Param`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `Param` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetVectorParameter](ue_ue.FXSystemComponent.md#setvectorparameter)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetVisibility](ue_ue.FXSystemComponent.md#setvisibility)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetWalkableSlopeOverride](ue_ue.FXSystemComponent.md#setwalkableslopeoverride)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetWorldScale3D](ue_ue.FXSystemComponent.md#setworldscale3d)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SetupAttachment](ue_ue.FXSystemComponent.md#setupattachment)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[SnapTo](ue_ue.FXSystemComponent.md#snapto)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[ToggleActive](ue_ue.FXSystemComponent.md#toggleactive)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[ToggleVisibility](ue_ue.FXSystemComponent.md#togglevisibility)

___

### WakeAllRigidBodies

▸ **WakeAllRigidBodies**(): `void`

#### Returns

`void`

#### Inherited from

[FXSystemComponent](ue_ue.FXSystemComponent.md).[WakeAllRigidBodies](ue_ue.FXSystemComponent.md#wakeallrigidbodies)

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

[FXSystemComponent](ue_ue.FXSystemComponent.md).[WakeRigidBody](ue_ue.FXSystemComponent.md#wakerigidbody)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)

#### Overrides

[FXSystemComponent](ue_ue.FXSystemComponent.md).[Find](ue_ue.FXSystemComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)

#### Overrides

[FXSystemComponent](ue_ue.FXSystemComponent.md).[Load](ue_ue.FXSystemComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FXSystemComponent](ue_ue.FXSystemComponent.md).[StaticClass](ue_ue.FXSystemComponent.md#staticclass)
