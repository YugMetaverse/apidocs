[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SphereComponent

# Class: SphereComponent

[ue/ue](../modules/ue_ue.md).SphereComponent

## Hierarchy

- [`ShapeComponent`](ue_ue.ShapeComponent.md)

  ↳ **`SphereComponent`**

  ↳↳ [`DrawSphereComponent`](ue_ue.DrawSphereComponent.md)

## Table of contents

### Constructors

- [constructor](ue_ue.SphereComponent.md#constructor)

### Properties

- [AlwaysLoadOnClient](ue_ue.SphereComponent.md#alwaysloadonclient)
- [AlwaysLoadOnServer](ue_ue.SphereComponent.md#alwaysloadonserver)
- [AreaClass](ue_ue.SphereComponent.md#areaclass)
- [AssetUserData](ue_ue.SphereComponent.md#assetuserdata)
- [AttachChildren](ue_ue.SphereComponent.md#attachchildren)
- [AttachParent](ue_ue.SphereComponent.md#attachparent)
- [AttachSocketName](ue_ue.SphereComponent.md#attachsocketname)
- [BodyInstance](ue_ue.SphereComponent.md#bodyinstance)
- [BoundsScale](ue_ue.SphereComponent.md#boundsscale)
- [CachedMaxDrawDistance](ue_ue.SphereComponent.md#cachedmaxdrawdistance)
- [CanBeCharacterBase](ue_ue.SphereComponent.md#canbecharacterbase)
- [CanCharacterStepUpOn](ue_ue.SphereComponent.md#cancharacterstepupon)
- [CastShadow](ue_ue.SphereComponent.md#castshadow)
- [ClientAttachedChildren](ue_ue.SphereComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.SphereComponent.md#componenttags)
- [ComponentVelocity](ue_ue.SphereComponent.md#componentvelocity)
- [CreationMethod](ue_ue.SphereComponent.md#creationmethod)
- [CustomDepthStencilValue](ue_ue.SphereComponent.md#customdepthstencilvalue)
- [CustomDepthStencilWriteMask](ue_ue.SphereComponent.md#customdepthstencilwritemask)
- [CustomPrimitiveData](ue_ue.SphereComponent.md#customprimitivedata)
- [DepthPriorityGroup](ue_ue.SphereComponent.md#depthprioritygroup)
- [DetailMode](ue_ue.SphereComponent.md#detailmode)
- [ExcludeForSpecificHLODLevels](ue_ue.SphereComponent.md#excludeforspecifichlodlevels)
- [IndirectLightingCacheQuality](ue_ue.SphereComponent.md#indirectlightingcachequality)
- [LDMaxDrawDistance](ue_ue.SphereComponent.md#ldmaxdrawdistance)
- [LODParentPrimitive](ue_ue.SphereComponent.md#lodparentprimitive)
- [LightingChannels](ue_ue.SphereComponent.md#lightingchannels)
- [LightmapType](ue_ue.SphereComponent.md#lightmaptype)
- [LpvBiasMultiplier](ue_ue.SphereComponent.md#lpvbiasmultiplier)
- [MinDrawDistance](ue_ue.SphereComponent.md#mindrawdistance)
- [Mobility](ue_ue.SphereComponent.md#mobility)
- [MoveIgnoreActors](ue_ue.SphereComponent.md#moveignoreactors)
- [MoveIgnoreComponents](ue_ue.SphereComponent.md#moveignorecomponents)
- [OnBeginCursorOver](ue_ue.SphereComponent.md#onbegincursorover)
- [OnClicked](ue_ue.SphereComponent.md#onclicked)
- [OnComponentActivated](ue_ue.SphereComponent.md#oncomponentactivated)
- [OnComponentBeginOverlap](ue_ue.SphereComponent.md#oncomponentbeginoverlap)
- [OnComponentDeactivated](ue_ue.SphereComponent.md#oncomponentdeactivated)
- [OnComponentEndOverlap](ue_ue.SphereComponent.md#oncomponentendoverlap)
- [OnComponentHit](ue_ue.SphereComponent.md#oncomponenthit)
- [OnComponentSleep](ue_ue.SphereComponent.md#oncomponentsleep)
- [OnComponentWake](ue_ue.SphereComponent.md#oncomponentwake)
- [OnEndCursorOver](ue_ue.SphereComponent.md#onendcursorover)
- [OnInputTouchBegin](ue_ue.SphereComponent.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.SphereComponent.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.SphereComponent.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.SphereComponent.md#oninputtouchleave)
- [OnReleased](ue_ue.SphereComponent.md#onreleased)
- [PhysicsVolume](ue_ue.SphereComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.SphereComponent.md#physicsvolumechangeddelegate)
- [PrimaryComponentTick](ue_ue.SphereComponent.md#primarycomponenttick)
- [RelativeLocation](ue_ue.SphereComponent.md#relativelocation)
- [RelativeRotation](ue_ue.SphereComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.SphereComponent.md#relativescale3d)
- [RuntimeVirtualTextures](ue_ue.SphereComponent.md#runtimevirtualtextures)
- [ShapeBodySetup](ue_ue.SphereComponent.md#shapebodysetup)
- [ShapeColor](ue_ue.SphereComponent.md#shapecolor)
- [SphereRadius](ue_ue.SphereComponent.md#sphereradius)
- [TranslucencySortPriority](ue_ue.SphereComponent.md#translucencysortpriority)
- [UCSModifiedProperties](ue_ue.SphereComponent.md#ucsmodifiedproperties)
- [ViewOwnerDepthPriorityGroup](ue_ue.SphereComponent.md#viewownerdepthprioritygroup)
- [VirtualTextureCullMips](ue_ue.SphereComponent.md#virtualtexturecullmips)
- [VirtualTextureLodBias](ue_ue.SphereComponent.md#virtualtexturelodbias)
- [VirtualTextureMinCoverage](ue_ue.SphereComponent.md#virtualtexturemincoverage)
- [VirtualTextureRenderPassType](ue_ue.SphereComponent.md#virtualtexturerenderpasstype)
- [VisibilityId](ue_ue.SphereComponent.md#visibilityid)
- [\_\_tid\_ActorComponent\_\_](ue_ue.SphereComponent.md#__tid_actorcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.SphereComponent.md#__tid_object__)
- [\_\_tid\_PrimitiveComponent\_\_](ue_ue.SphereComponent.md#__tid_primitivecomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.SphereComponent.md#__tid_scenecomponent__)
- [\_\_tid\_ShapeComponent\_\_](ue_ue.SphereComponent.md#__tid_shapecomponent__)
- [\_\_tid\_SphereComponent\_\_](ue_ue.SphereComponent.md#__tid_spherecomponent__)
- [bAbsoluteLocation](ue_ue.SphereComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.SphereComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.SphereComponent.md#babsolutescale)
- [bAffectDistanceFieldLighting](ue_ue.SphereComponent.md#baffectdistancefieldlighting)
- [bAffectDynamicIndirectLighting](ue_ue.SphereComponent.md#baffectdynamicindirectlighting)
- [bAllowCullDistanceVolume](ue_ue.SphereComponent.md#ballowculldistancevolume)
- [bAlwaysCreatePhysicsState](ue_ue.SphereComponent.md#balwayscreatephysicsstate)
- [bApplyImpulseOnDamage](ue_ue.SphereComponent.md#bapplyimpulseondamage)
- [bAutoActivate](ue_ue.SphereComponent.md#bautoactivate)
- [bBatchImpostersAsInstances](ue_ue.SphereComponent.md#bbatchimpostersasinstances)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.SphereComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.SphereComponent.md#bcaneveraffectnavigation)
- [bCastCinematicShadow](ue_ue.SphereComponent.md#bcastcinematicshadow)
- [bCastDynamicShadow](ue_ue.SphereComponent.md#bcastdynamicshadow)
- [bCastFarShadow](ue_ue.SphereComponent.md#bcastfarshadow)
- [bCastHiddenShadow](ue_ue.SphereComponent.md#bcasthiddenshadow)
- [bCastInsetShadow](ue_ue.SphereComponent.md#bcastinsetshadow)
- [bCastShadowAsTwoSided](ue_ue.SphereComponent.md#bcastshadowastwosided)
- [bCastStaticShadow](ue_ue.SphereComponent.md#bcaststaticshadow)
- [bCastVolumetricTranslucentShadow](ue_ue.SphereComponent.md#bcastvolumetrictranslucentshadow)
- [bComponentToWorldUpdated](ue_ue.SphereComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.SphereComponent.md#bcreatedbyconstructionscript)
- [bDrawOnlyIfSelected](ue_ue.SphereComponent.md#bdrawonlyifselected)
- [bDynamicObstacle](ue_ue.SphereComponent.md#bdynamicobstacle)
- [bEditableWhenInherited](ue_ue.SphereComponent.md#beditablewheninherited)
- [bEnableAutoLODGeneration](ue_ue.SphereComponent.md#benableautolodgeneration)
- [bExcludeFromLightAttachmentGroup](ue_ue.SphereComponent.md#bexcludefromlightattachmentgroup)
- [bForceMipStreaming](ue_ue.SphereComponent.md#bforcemipstreaming)
- [bGenerateOverlapEvents](ue_ue.SphereComponent.md#bgenerateoverlapevents)
- [bHasCustomNavigableGeometry](ue_ue.SphereComponent.md#bhascustomnavigablegeometry)
- [bHasMotionBlurVelocityMeshes](ue_ue.SphereComponent.md#bhasmotionblurvelocitymeshes)
- [bHasPerInstanceHitProxies](ue_ue.SphereComponent.md#bhasperinstancehitproxies)
- [bHiddenInGame](ue_ue.SphereComponent.md#bhiddeningame)
- [bIgnoreRadialForce](ue_ue.SphereComponent.md#bignoreradialforce)
- [bIgnoreRadialImpulse](ue_ue.SphereComponent.md#bignoreradialimpulse)
- [bInstanceComponent](ue_ue.SphereComponent.md#binstancecomponent)
- [bIsActive](ue_ue.SphereComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.SphereComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.SphereComponent.md#bisvisualizationcomponent)
- [bLightAsIfStatic](ue_ue.SphereComponent.md#blightasifstatic)
- [bLightAttachmentsAsGroup](ue_ue.SphereComponent.md#blightattachmentsasgroup)
- [bMultiBodyOverlap](ue_ue.SphereComponent.md#bmultibodyoverlap)
- [bNetAddressable](ue_ue.SphereComponent.md#bnetaddressable)
- [bNeverDistanceCull](ue_ue.SphereComponent.md#bneverdistancecull)
- [bOnlyOwnerSee](ue_ue.SphereComponent.md#bonlyownersee)
- [bOwnerNoSee](ue_ue.SphereComponent.md#bownernosee)
- [bReceiveMobileCSMShadows](ue_ue.SphereComponent.md#breceivemobilecsmshadows)
- [bReceivesDecals](ue_ue.SphereComponent.md#breceivesdecals)
- [bRenderCustomDepth](ue_ue.SphereComponent.md#brendercustomdepth)
- [bRenderInDepthPass](ue_ue.SphereComponent.md#brenderindepthpass)
- [bRenderInMainPass](ue_ue.SphereComponent.md#brenderinmainpass)
- [bReplicatePhysicsToAutonomousProxy](ue_ue.SphereComponent.md#breplicatephysicstoautonomousproxy)
- [bReplicates](ue_ue.SphereComponent.md#breplicates)
- [bReturnMaterialOnMove](ue_ue.SphereComponent.md#breturnmaterialonmove)
- [bSelectable](ue_ue.SphereComponent.md#bselectable)
- [bSelfShadowOnly](ue_ue.SphereComponent.md#bselfshadowonly)
- [bShouldBeAttached](ue_ue.SphereComponent.md#bshouldbeattached)
- [bShouldCollideWhenPlacing](ue_ue.SphereComponent.md#bshouldcollidewhenplacing)
- [bShouldSnapLocationWhenAttached](ue_ue.SphereComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.SphereComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.SphereComponent.md#bshouldupdatephysicsvolume)
- [bSingleSampleShadowFromStationaryLights](ue_ue.SphereComponent.md#bsinglesampleshadowfromstationarylights)
- [bTraceComplexOnMove](ue_ue.SphereComponent.md#btracecomplexonmove)
- [bTreatAsBackgroundForOcclusion](ue_ue.SphereComponent.md#btreatasbackgroundforocclusion)
- [bUseAsOccluder](ue_ue.SphereComponent.md#buseasoccluder)
- [bUseAttachParentBound](ue_ue.SphereComponent.md#buseattachparentbound)
- [bUseEditorCompositing](ue_ue.SphereComponent.md#buseeditorcompositing)
- [bUseMaxLODAsImposter](ue_ue.SphereComponent.md#busemaxlodasimposter)
- [bUseViewOwnerDepthPriorityGroup](ue_ue.SphereComponent.md#buseviewownerdepthprioritygroup)
- [bVisible](ue_ue.SphereComponent.md#bvisible)
- [bVisibleInRayTracing](ue_ue.SphereComponent.md#bvisibleinraytracing)
- [bVisibleInReflectionCaptures](ue_ue.SphereComponent.md#bvisibleinreflectioncaptures)
- [bVisualizeComponent](ue_ue.SphereComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.SphereComponent.md#activate)
- [AddAngularImpulse](ue_ue.SphereComponent.md#addangularimpulse)
- [AddAngularImpulseInDegrees](ue_ue.SphereComponent.md#addangularimpulseindegrees)
- [AddAngularImpulseInRadians](ue_ue.SphereComponent.md#addangularimpulseinradians)
- [AddForce](ue_ue.SphereComponent.md#addforce)
- [AddForceAtLocation](ue_ue.SphereComponent.md#addforceatlocation)
- [AddForceAtLocationLocal](ue_ue.SphereComponent.md#addforceatlocationlocal)
- [AddImpulse](ue_ue.SphereComponent.md#addimpulse)
- [AddImpulseAtLocation](ue_ue.SphereComponent.md#addimpulseatlocation)
- [AddRadialForce](ue_ue.SphereComponent.md#addradialforce)
- [AddRadialImpulse](ue_ue.SphereComponent.md#addradialimpulse)
- [AddTickPrerequisiteActor](ue_ue.SphereComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.SphereComponent.md#addtickprerequisitecomponent)
- [AddTorque](ue_ue.SphereComponent.md#addtorque)
- [AddTorqueInDegrees](ue_ue.SphereComponent.md#addtorqueindegrees)
- [AddTorqueInRadians](ue_ue.SphereComponent.md#addtorqueinradians)
- [CanCharacterStepUp](ue_ue.SphereComponent.md#cancharacterstepup)
- [ClearMoveIgnoreActors](ue_ue.SphereComponent.md#clearmoveignoreactors)
- [ClearMoveIgnoreComponents](ue_ue.SphereComponent.md#clearmoveignorecomponents)
- [ComponentHasTag](ue_ue.SphereComponent.md#componenthastag)
- [CopyArrayOfMoveIgnoreActors](ue_ue.SphereComponent.md#copyarrayofmoveignoreactors)
- [CopyArrayOfMoveIgnoreComponents](ue_ue.SphereComponent.md#copyarrayofmoveignorecomponents)
- [CreateAndSetMaterialInstanceDynamic](ue_ue.SphereComponent.md#createandsetmaterialinstancedynamic)
- [CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.SphereComponent.md#createandsetmaterialinstancedynamicfrommaterial)
- [CreateDefaultSubobject](ue_ue.SphereComponent.md#createdefaultsubobject)
- [CreateDynamicMaterialInstance](ue_ue.SphereComponent.md#createdynamicmaterialinstance)
- [Deactivate](ue_ue.SphereComponent.md#deactivate)
- [DetachFromParent](ue_ue.SphereComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.SphereComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.SphereComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.SphereComponent.md#getallsocketnames)
- [GetAngularDamping](ue_ue.SphereComponent.md#getangulardamping)
- [GetAttachParent](ue_ue.SphereComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.SphereComponent.md#getattachsocketname)
- [GetCenterOfMass](ue_ue.SphereComponent.md#getcenterofmass)
- [GetChildComponent](ue_ue.SphereComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.SphereComponent.md#getchildrencomponents)
- [GetClass](ue_ue.SphereComponent.md#getclass)
- [GetClosestPointOnCollision](ue_ue.SphereComponent.md#getclosestpointoncollision)
- [GetCollisionEnabled](ue_ue.SphereComponent.md#getcollisionenabled)
- [GetCollisionObjectType](ue_ue.SphereComponent.md#getcollisionobjecttype)
- [GetCollisionProfileName](ue_ue.SphereComponent.md#getcollisionprofilename)
- [GetCollisionResponseToChannel](ue_ue.SphereComponent.md#getcollisionresponsetochannel)
- [GetComponentTickInterval](ue_ue.SphereComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.SphereComponent.md#getcomponentvelocity)
- [GetForwardVector](ue_ue.SphereComponent.md#getforwardvector)
- [GetGenerateOverlapEvents](ue_ue.SphereComponent.md#getgenerateoverlapevents)
- [GetInertiaTensor](ue_ue.SphereComponent.md#getinertiatensor)
- [GetLinearDamping](ue_ue.SphereComponent.md#getlineardamping)
- [GetMass](ue_ue.SphereComponent.md#getmass)
- [GetMassScale](ue_ue.SphereComponent.md#getmassscale)
- [GetMaterial](ue_ue.SphereComponent.md#getmaterial)
- [GetMaterialFromCollisionFaceIndex](ue_ue.SphereComponent.md#getmaterialfromcollisionfaceindex)
- [GetName](ue_ue.SphereComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.SphereComponent.md#getnumchildrencomponents)
- [GetNumMaterials](ue_ue.SphereComponent.md#getnummaterials)
- [GetOuter](ue_ue.SphereComponent.md#getouter)
- [GetOverlappingActors](ue_ue.SphereComponent.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.SphereComponent.md#getoverlappingcomponents)
- [GetOwner](ue_ue.SphereComponent.md#getowner)
- [GetParentComponents](ue_ue.SphereComponent.md#getparentcomponents)
- [GetPhysicsAngularVelocity](ue_ue.SphereComponent.md#getphysicsangularvelocity)
- [GetPhysicsAngularVelocityInDegrees](ue_ue.SphereComponent.md#getphysicsangularvelocityindegrees)
- [GetPhysicsAngularVelocityInRadians](ue_ue.SphereComponent.md#getphysicsangularvelocityinradians)
- [GetPhysicsLinearVelocity](ue_ue.SphereComponent.md#getphysicslinearvelocity)
- [GetPhysicsLinearVelocityAtPoint](ue_ue.SphereComponent.md#getphysicslinearvelocityatpoint)
- [GetPhysicsVolume](ue_ue.SphereComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.SphereComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.SphereComponent.md#getrightvector)
- [GetScaledSphereRadius](ue_ue.SphereComponent.md#getscaledsphereradius)
- [GetShapeScale](ue_ue.SphereComponent.md#getshapescale)
- [GetShouldUpdatePhysicsVolume](ue_ue.SphereComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.SphereComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.SphereComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.SphereComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.SphereComponent.md#getsockettransform)
- [GetUnscaledSphereRadius](ue_ue.SphereComponent.md#getunscaledsphereradius)
- [GetUpVector](ue_ue.SphereComponent.md#getupvector)
- [GetWalkableSlopeOverride](ue_ue.SphereComponent.md#getwalkableslopeoverride)
- [GetWorld](ue_ue.SphereComponent.md#getworld)
- [IgnoreActorWhenMoving](ue_ue.SphereComponent.md#ignoreactorwhenmoving)
- [IgnoreComponentWhenMoving](ue_ue.SphereComponent.md#ignorecomponentwhenmoving)
- [IsActive](ue_ue.SphereComponent.md#isactive)
- [IsAnyRigidBodyAwake](ue_ue.SphereComponent.md#isanyrigidbodyawake)
- [IsAnySimulatingPhysics](ue_ue.SphereComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.SphereComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.SphereComponent.md#iscomponenttickenabled)
- [IsGravityEnabled](ue_ue.SphereComponent.md#isgravityenabled)
- [IsOverlappingActor](ue_ue.SphereComponent.md#isoverlappingactor)
- [IsOverlappingComponent](ue_ue.SphereComponent.md#isoverlappingcomponent)
- [IsSimulatingPhysics](ue_ue.SphereComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.SphereComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.SphereComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.SphereComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.SphereComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.SphereComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.SphereComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.SphereComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.SphereComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.SphereComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.SphereComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.SphereComponent.md#k2_attachtocomponent)
- [K2\_BoxOverlapComponent](ue_ue.SphereComponent.md#k2_boxoverlapcomponent)
- [K2\_DestroyComponent](ue_ue.SphereComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.SphereComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.SphereComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.SphereComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.SphereComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.SphereComponent.md#k2_getcomponenttoworld)
- [K2\_IsCollisionEnabled](ue_ue.SphereComponent.md#k2_iscollisionenabled)
- [K2\_IsPhysicsCollisionEnabled](ue_ue.SphereComponent.md#k2_isphysicscollisionenabled)
- [K2\_IsQueryCollisionEnabled](ue_ue.SphereComponent.md#k2_isquerycollisionenabled)
- [K2\_LineTraceComponent](ue_ue.SphereComponent.md#k2_linetracecomponent)
- [K2\_SetRelativeLocation](ue_ue.SphereComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.SphereComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.SphereComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.SphereComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.SphereComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.SphereComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.SphereComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.SphereComponent.md#k2_setworldtransform)
- [K2\_SphereOverlapComponent](ue_ue.SphereComponent.md#k2_sphereoverlapcomponent)
- [K2\_SphereTraceComponent](ue_ue.SphereComponent.md#k2_spheretracecomponent)
- [OnRep\_AttachChildren](ue_ue.SphereComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.SphereComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.SphereComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.SphereComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.SphereComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.SphereComponent.md#onrep_visibility)
- [PutRigidBodyToSleep](ue_ue.SphereComponent.md#putrigidbodytosleep)
- [ReceiveBeginPlay](ue_ue.SphereComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.SphereComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.SphereComponent.md#receivetick)
- [RegisterComponent](ue_ue.SphereComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.SphereComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.SphereComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.SphereComponent.md#resetrelativetransform)
- [ScaleByMomentOfInertia](ue_ue.SphereComponent.md#scalebymomentofinertia)
- [SetAbsolute](ue_ue.SphereComponent.md#setabsolute)
- [SetActive](ue_ue.SphereComponent.md#setactive)
- [SetAllMassScale](ue_ue.SphereComponent.md#setallmassscale)
- [SetAllPhysicsAngularVelocityInDegrees](ue_ue.SphereComponent.md#setallphysicsangularvelocityindegrees)
- [SetAllPhysicsAngularVelocityInRadians](ue_ue.SphereComponent.md#setallphysicsangularvelocityinradians)
- [SetAllPhysicsLinearVelocity](ue_ue.SphereComponent.md#setallphysicslinearvelocity)
- [SetAllUseCCD](ue_ue.SphereComponent.md#setalluseccd)
- [SetAngularDamping](ue_ue.SphereComponent.md#setangulardamping)
- [SetAutoActivate](ue_ue.SphereComponent.md#setautoactivate)
- [SetBoundsScale](ue_ue.SphereComponent.md#setboundsscale)
- [SetCastInsetShadow](ue_ue.SphereComponent.md#setcastinsetshadow)
- [SetCastShadow](ue_ue.SphereComponent.md#setcastshadow)
- [SetCenterOfMass](ue_ue.SphereComponent.md#setcenterofmass)
- [SetCollisionEnabled](ue_ue.SphereComponent.md#setcollisionenabled)
- [SetCollisionObjectType](ue_ue.SphereComponent.md#setcollisionobjecttype)
- [SetCollisionProfileName](ue_ue.SphereComponent.md#setcollisionprofilename)
- [SetCollisionResponseToAllChannels](ue_ue.SphereComponent.md#setcollisionresponsetoallchannels)
- [SetCollisionResponseToChannel](ue_ue.SphereComponent.md#setcollisionresponsetochannel)
- [SetComponentTickEnabled](ue_ue.SphereComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.SphereComponent.md#setcomponenttickinterval)
- [SetConstraintMode](ue_ue.SphereComponent.md#setconstraintmode)
- [SetCullDistance](ue_ue.SphereComponent.md#setculldistance)
- [SetCustomDepthStencilValue](ue_ue.SphereComponent.md#setcustomdepthstencilvalue)
- [SetCustomDepthStencilWriteMask](ue_ue.SphereComponent.md#setcustomdepthstencilwritemask)
- [SetCustomPrimitiveDataFloat](ue_ue.SphereComponent.md#setcustomprimitivedatafloat)
- [SetCustomPrimitiveDataVector2](ue_ue.SphereComponent.md#setcustomprimitivedatavector2)
- [SetCustomPrimitiveDataVector3](ue_ue.SphereComponent.md#setcustomprimitivedatavector3)
- [SetCustomPrimitiveDataVector4](ue_ue.SphereComponent.md#setcustomprimitivedatavector4)
- [SetEnableGravity](ue_ue.SphereComponent.md#setenablegravity)
- [SetExcludeFromLightAttachmentGroup](ue_ue.SphereComponent.md#setexcludefromlightattachmentgroup)
- [SetGenerateOverlapEvents](ue_ue.SphereComponent.md#setgenerateoverlapevents)
- [SetHiddenInGame](ue_ue.SphereComponent.md#sethiddeningame)
- [SetIsReplicated](ue_ue.SphereComponent.md#setisreplicated)
- [SetLightAttachmentsAsGroup](ue_ue.SphereComponent.md#setlightattachmentsasgroup)
- [SetLinearDamping](ue_ue.SphereComponent.md#setlineardamping)
- [SetMassOverrideInKg](ue_ue.SphereComponent.md#setmassoverrideinkg)
- [SetMassScale](ue_ue.SphereComponent.md#setmassscale)
- [SetMaterial](ue_ue.SphereComponent.md#setmaterial)
- [SetMaterialByName](ue_ue.SphereComponent.md#setmaterialbyname)
- [SetMobility](ue_ue.SphereComponent.md#setmobility)
- [SetNotifyRigidBodyCollision](ue_ue.SphereComponent.md#setnotifyrigidbodycollision)
- [SetOnlyOwnerSee](ue_ue.SphereComponent.md#setonlyownersee)
- [SetOwnerNoSee](ue_ue.SphereComponent.md#setownernosee)
- [SetPhysMaterialOverride](ue_ue.SphereComponent.md#setphysmaterialoverride)
- [SetPhysicsAngularVelocity](ue_ue.SphereComponent.md#setphysicsangularvelocity)
- [SetPhysicsAngularVelocityInDegrees](ue_ue.SphereComponent.md#setphysicsangularvelocityindegrees)
- [SetPhysicsAngularVelocityInRadians](ue_ue.SphereComponent.md#setphysicsangularvelocityinradians)
- [SetPhysicsLinearVelocity](ue_ue.SphereComponent.md#setphysicslinearvelocity)
- [SetPhysicsMaxAngularVelocity](ue_ue.SphereComponent.md#setphysicsmaxangularvelocity)
- [SetPhysicsMaxAngularVelocityInDegrees](ue_ue.SphereComponent.md#setphysicsmaxangularvelocityindegrees)
- [SetPhysicsMaxAngularVelocityInRadians](ue_ue.SphereComponent.md#setphysicsmaxangularvelocityinradians)
- [SetReceivesDecals](ue_ue.SphereComponent.md#setreceivesdecals)
- [SetRelativeScale3D](ue_ue.SphereComponent.md#setrelativescale3d)
- [SetRenderCustomDepth](ue_ue.SphereComponent.md#setrendercustomdepth)
- [SetRenderInMainPass](ue_ue.SphereComponent.md#setrenderinmainpass)
- [SetShouldUpdatePhysicsVolume](ue_ue.SphereComponent.md#setshouldupdatephysicsvolume)
- [SetSimulatePhysics](ue_ue.SphereComponent.md#setsimulatephysics)
- [SetSingleSampleShadowFromStationaryLights](ue_ue.SphereComponent.md#setsinglesampleshadowfromstationarylights)
- [SetSphereRadius](ue_ue.SphereComponent.md#setsphereradius)
- [SetTickGroup](ue_ue.SphereComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.SphereComponent.md#settickablewhenpaused)
- [SetTranslucentSortPriority](ue_ue.SphereComponent.md#settranslucentsortpriority)
- [SetUseCCD](ue_ue.SphereComponent.md#setuseccd)
- [SetVisibility](ue_ue.SphereComponent.md#setvisibility)
- [SetWalkableSlopeOverride](ue_ue.SphereComponent.md#setwalkableslopeoverride)
- [SetWorldScale3D](ue_ue.SphereComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.SphereComponent.md#setupattachment)
- [SnapTo](ue_ue.SphereComponent.md#snapto)
- [ToggleActive](ue_ue.SphereComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.SphereComponent.md#togglevisibility)
- [WakeAllRigidBodies](ue_ue.SphereComponent.md#wakeallrigidbodies)
- [WakeRigidBody](ue_ue.SphereComponent.md#wakerigidbody)
- [Find](ue_ue.SphereComponent.md#find)
- [Load](ue_ue.SphereComponent.md#load)
- [StaticClass](ue_ue.SphereComponent.md#staticclass)

## Constructors

### constructor

• **new SphereComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ShapeComponent](ue_ue.ShapeComponent.md).[constructor](ue_ue.ShapeComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:10528](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10528)

## Properties

### AlwaysLoadOnClient

• **AlwaysLoadOnClient**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[AlwaysLoadOnClient](ue_ue.ShapeComponent.md#alwaysloadonclient)

#### Defined in

[ue/ue.d.ts:12608](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12608)

___

### AlwaysLoadOnServer

• **AlwaysLoadOnServer**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[AlwaysLoadOnServer](ue_ue.ShapeComponent.md#alwaysloadonserver)

#### Defined in

[ue/ue.d.ts:12609](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12609)

___

### AreaClass

• **AreaClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[AreaClass](ue_ue.ShapeComponent.md#areaclass)

#### Defined in

[ue/ue.d.ts:5833](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5833)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[AssetUserData](ue_ue.ShapeComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L291)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[AttachChildren](ue_ue.ShapeComponent.md#attachchildren)

#### Defined in

[ue/ue.d.ts:12873](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12873)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[AttachParent](ue_ue.ShapeComponent.md#attachparent)

#### Defined in

[ue/ue.d.ts:12871](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12871)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[AttachSocketName](ue_ue.ShapeComponent.md#attachsocketname)

#### Defined in

[ue/ue.d.ts:12872](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12872)

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[BodyInstance](ue_ue.ShapeComponent.md#bodyinstance)

#### Defined in

[ue/ue.d.ts:12630](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12630)

___

### BoundsScale

• **BoundsScale**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[BoundsScale](ue_ue.ShapeComponent.md#boundsscale)

#### Defined in

[ue/ue.d.ts:12627](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12627)

___

### CachedMaxDrawDistance

• **CachedMaxDrawDistance**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CachedMaxDrawDistance](ue_ue.ShapeComponent.md#cachedmaxdrawdistance)

#### Defined in

[ue/ue.d.ts:12557](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12557)

___

### CanBeCharacterBase

• **CanBeCharacterBase**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CanBeCharacterBase](ue_ue.ShapeComponent.md#canbecharacterbase)

#### Defined in

[ue/ue.d.ts:12613](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12613)

___

### CanCharacterStepUpOn

• **CanCharacterStepUpOn**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CanCharacterStepUpOn](ue_ue.ShapeComponent.md#cancharacterstepupon)

#### Defined in

[ue/ue.d.ts:12614](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12614)

___

### CastShadow

• **CastShadow**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CastShadow](ue_ue.ShapeComponent.md#castshadow)

#### Defined in

[ue/ue.d.ts:12587](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12587)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ClientAttachedChildren](ue_ue.ShapeComponent.md#clientattachedchildren)

#### Defined in

[ue/ue.d.ts:12874](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12874)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ComponentTags](ue_ue.ShapeComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L290)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ComponentVelocity](ue_ue.ShapeComponent.md#componentvelocity)

#### Defined in

[ue/ue.d.ts:12878](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12878)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CreationMethod](ue_ue.ShapeComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L302)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CustomDepthStencilValue](ue_ue.ShapeComponent.md#customdepthstencilvalue)

#### Defined in

[ue/ue.d.ts:12617](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12617)

___

### CustomDepthStencilWriteMask

• **CustomDepthStencilWriteMask**: [`ERendererStencilMask`](../enums/ue_ue.ERendererStencilMask.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CustomDepthStencilWriteMask](ue_ue.ShapeComponent.md#customdepthstencilwritemask)

#### Defined in

[ue/ue.d.ts:12616](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12616)

___

### CustomPrimitiveData

• **CustomPrimitiveData**: [`CustomPrimitiveData`](ue_ue.CustomPrimitiveData.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CustomPrimitiveData](ue_ue.ShapeComponent.md#customprimitivedata)

#### Defined in

[ue/ue.d.ts:12618](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12618)

___

### DepthPriorityGroup

• **DepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[DepthPriorityGroup](ue_ue.ShapeComponent.md#depthprioritygroup)

#### Defined in

[ue/ue.d.ts:12558](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12558)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[DetailMode](ue_ue.ShapeComponent.md#detailmode)

#### Defined in

[ue/ue.d.ts:12893](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12893)

___

### ExcludeForSpecificHLODLevels

• **ExcludeForSpecificHLODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ExcludeForSpecificHLODLevels](ue_ue.ShapeComponent.md#excludeforspecifichlodlevels)

#### Defined in

[ue/ue.d.ts:12562](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12562)

___

### IndirectLightingCacheQuality

• **IndirectLightingCacheQuality**: [`EIndirectLightingCacheQuality`](../enums/ue_ue.EIndirectLightingCacheQuality.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[IndirectLightingCacheQuality](ue_ue.ShapeComponent.md#indirectlightingcachequality)

#### Defined in

[ue/ue.d.ts:12560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12560)

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[LDMaxDrawDistance](ue_ue.ShapeComponent.md#ldmaxdrawdistance)

#### Defined in

[ue/ue.d.ts:12556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12556)

___

### LODParentPrimitive

• **LODParentPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[LODParentPrimitive](ue_ue.ShapeComponent.md#lodparentprimitive)

#### Defined in

[ue/ue.d.ts:12644](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12644)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[LightingChannels](ue_ue.ShapeComponent.md#lightingchannels)

#### Defined in

[ue/ue.d.ts:12615](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12615)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[LightmapType](ue_ue.ShapeComponent.md#lightmaptype)

#### Defined in

[ue/ue.d.ts:12561](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12561)

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[LpvBiasMultiplier](ue_ue.ShapeComponent.md#lpvbiasmultiplier)

#### Defined in

[ue/ue.d.ts:12626](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12626)

___

### MinDrawDistance

• **MinDrawDistance**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[MinDrawDistance](ue_ue.ShapeComponent.md#mindrawdistance)

#### Defined in

[ue/ue.d.ts:12555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12555)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[Mobility](ue_ue.ShapeComponent.md#mobility)

#### Defined in

[ue/ue.d.ts:12892](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12892)

___

### MoveIgnoreActors

• **MoveIgnoreActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[MoveIgnoreActors](ue_ue.ShapeComponent.md#moveignoreactors)

#### Defined in

[ue/ue.d.ts:12628](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12628)

___

### MoveIgnoreComponents

• **MoveIgnoreComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[MoveIgnoreComponents](ue_ue.ShapeComponent.md#moveignorecomponents)

#### Defined in

[ue/ue.d.ts:12629](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12629)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnBeginCursorOver](ue_ue.ShapeComponent.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:12636](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12636)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnClicked](ue_ue.ShapeComponent.md#onclicked)

#### Defined in

[ue/ue.d.ts:12638](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12638)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnComponentActivated](ue_ue.ShapeComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L303)

___

### OnComponentBeginOverlap

• **OnComponentBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`, `bFromSweep`: `boolean`, `SweepResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnComponentBeginOverlap](ue_ue.ShapeComponent.md#oncomponentbeginoverlap)

#### Defined in

[ue/ue.d.ts:12632](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12632)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnComponentDeactivated](ue_ue.ShapeComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L304)

___

### OnComponentEndOverlap

• **OnComponentEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnComponentEndOverlap](ue_ue.ShapeComponent.md#oncomponentendoverlap)

#### Defined in

[ue/ue.d.ts:12633](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12633)

___

### OnComponentHit

• **OnComponentHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`HitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnComponentHit](ue_ue.ShapeComponent.md#oncomponenthit)

#### Defined in

[ue/ue.d.ts:12631](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12631)

___

### OnComponentSleep

• **OnComponentSleep**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SleepingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnComponentSleep](ue_ue.ShapeComponent.md#oncomponentsleep)

#### Defined in

[ue/ue.d.ts:12635](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12635)

___

### OnComponentWake

• **OnComponentWake**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`WakingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnComponentWake](ue_ue.ShapeComponent.md#oncomponentwake)

#### Defined in

[ue/ue.d.ts:12634](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12634)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnEndCursorOver](ue_ue.ShapeComponent.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:12637](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12637)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnInputTouchBegin](ue_ue.ShapeComponent.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:12640](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12640)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnInputTouchEnd](ue_ue.ShapeComponent.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:12641](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12641)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnInputTouchEnter](ue_ue.ShapeComponent.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:12642](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12642)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnInputTouchLeave](ue_ue.ShapeComponent.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:12643](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12643)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnReleased](ue_ue.ShapeComponent.md#onreleased)

#### Defined in

[ue/ue.d.ts:12639](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12639)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[PhysicsVolume](ue_ue.ShapeComponent.md#physicsvolume)

#### Defined in

[ue/ue.d.ts:12870](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12870)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.ShapeComponent.md#physicsvolumechangeddelegate)

#### Defined in

[ue/ue.d.ts:12894](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12894)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[PrimaryComponentTick](ue_ue.ShapeComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L289)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[RelativeLocation](ue_ue.ShapeComponent.md#relativelocation)

#### Defined in

[ue/ue.d.ts:12875](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12875)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[RelativeRotation](ue_ue.ShapeComponent.md#relativerotation)

#### Defined in

[ue/ue.d.ts:12876](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12876)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[RelativeScale3D](ue_ue.ShapeComponent.md#relativescale3d)

#### Defined in

[ue/ue.d.ts:12877](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12877)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[RuntimeVirtualTextures](ue_ue.ShapeComponent.md#runtimevirtualtextures)

#### Defined in

[ue/ue.d.ts:12621](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12621)

___

### ShapeBodySetup

• **ShapeBodySetup**: [`BodySetup`](ue_ue.BodySetup.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ShapeBodySetup](ue_ue.ShapeComponent.md#shapebodysetup)

#### Defined in

[ue/ue.d.ts:5832](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5832)

___

### ShapeColor

• **ShapeColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ShapeColor](ue_ue.ShapeComponent.md#shapecolor)

#### Defined in

[ue/ue.d.ts:5834](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5834)

___

### SphereRadius

• **SphereRadius**: `number`

#### Defined in

[ue/ue.d.ts:10529](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10529)

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[TranslucencySortPriority](ue_ue.ShapeComponent.md#translucencysortpriority)

#### Defined in

[ue/ue.d.ts:12619](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12619)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[UCSModifiedProperties](ue_ue.ShapeComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L305)

___

### ViewOwnerDepthPriorityGroup

• **ViewOwnerDepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ViewOwnerDepthPriorityGroup](ue_ue.ShapeComponent.md#viewownerdepthprioritygroup)

#### Defined in

[ue/ue.d.ts:12559](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12559)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[VirtualTextureCullMips](ue_ue.ShapeComponent.md#virtualtexturecullmips)

#### Defined in

[ue/ue.d.ts:12623](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12623)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[VirtualTextureLodBias](ue_ue.ShapeComponent.md#virtualtexturelodbias)

#### Defined in

[ue/ue.d.ts:12622](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12622)

___

### VirtualTextureMinCoverage

• **VirtualTextureMinCoverage**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[VirtualTextureMinCoverage](ue_ue.ShapeComponent.md#virtualtexturemincoverage)

#### Defined in

[ue/ue.d.ts:12624](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12624)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[VirtualTextureRenderPassType](ue_ue.ShapeComponent.md#virtualtexturerenderpasstype)

#### Defined in

[ue/ue.d.ts:12625](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12625)

___

### VisibilityId

• **VisibilityId**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[VisibilityId](ue_ue.ShapeComponent.md#visibilityid)

#### Defined in

[ue/ue.d.ts:12620](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12620)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[__tid_ActorComponent__](ue_ue.ShapeComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L336)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[__tid_Object__](ue_ue.ShapeComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PrimitiveComponent\_\_

• **\_\_tid\_PrimitiveComponent\_\_**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[__tid_PrimitiveComponent__](ue_ue.ShapeComponent.md#__tid_primitivecomponent__)

#### Defined in

[ue/ue.d.ts:12761](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12761)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[__tid_SceneComponent__](ue_ue.ShapeComponent.md#__tid_scenecomponent__)

#### Defined in

[ue/ue.d.ts:12961](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12961)

___

### \_\_tid\_ShapeComponent\_\_

• **\_\_tid\_ShapeComponent\_\_**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[__tid_ShapeComponent__](ue_ue.ShapeComponent.md#__tid_shapecomponent__)

#### Defined in

[ue/ue.d.ts:5842](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5842)

___

### \_\_tid\_SphereComponent\_\_

• **\_\_tid\_SphereComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:10538](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10538)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bAbsoluteLocation](ue_ue.ShapeComponent.md#babsolutelocation)

#### Defined in

[ue/ue.d.ts:12880](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12880)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bAbsoluteRotation](ue_ue.ShapeComponent.md#babsoluterotation)

#### Defined in

[ue/ue.d.ts:12881](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12881)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bAbsoluteScale](ue_ue.ShapeComponent.md#babsolutescale)

#### Defined in

[ue/ue.d.ts:12882](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12882)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bAffectDistanceFieldLighting](ue_ue.ShapeComponent.md#baffectdistancefieldlighting)

#### Defined in

[ue/ue.d.ts:12589](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12589)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bAffectDynamicIndirectLighting](ue_ue.ShapeComponent.md#baffectdynamicindirectlighting)

#### Defined in

[ue/ue.d.ts:12588](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12588)

___

### bAllowCullDistanceVolume

• **bAllowCullDistanceVolume**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bAllowCullDistanceVolume](ue_ue.ShapeComponent.md#ballowculldistancevolume)

#### Defined in

[ue/ue.d.ts:12573](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12573)

___

### bAlwaysCreatePhysicsState

• **bAlwaysCreatePhysicsState**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bAlwaysCreatePhysicsState](ue_ue.ShapeComponent.md#balwayscreatephysicsstate)

#### Defined in

[ue/ue.d.ts:12567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12567)

___

### bApplyImpulseOnDamage

• **bApplyImpulseOnDamage**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bApplyImpulseOnDamage](ue_ue.ShapeComponent.md#bapplyimpulseondamage)

#### Defined in

[ue/ue.d.ts:12606](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12606)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bAutoActivate](ue_ue.ShapeComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L296)

___

### bBatchImpostersAsInstances

• **bBatchImpostersAsInstances**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bBatchImpostersAsInstances](ue_ue.ShapeComponent.md#bbatchimpostersasinstances)

#### Defined in

[ue/ue.d.ts:12565](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12565)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.ShapeComponent.md#bboundschangetriggersstreamingdatarebuild)

#### Defined in

[ue/ue.d.ts:12889](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12889)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCanEverAffectNavigation](ue_ue.ShapeComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L299)

___

### bCastCinematicShadow

• **bCastCinematicShadow**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCastCinematicShadow](ue_ue.ShapeComponent.md#bcastcinematicshadow)

#### Defined in

[ue/ue.d.ts:12596](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12596)

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCastDynamicShadow](ue_ue.ShapeComponent.md#bcastdynamicshadow)

#### Defined in

[ue/ue.d.ts:12590](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12590)

___

### bCastFarShadow

• **bCastFarShadow**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCastFarShadow](ue_ue.ShapeComponent.md#bcastfarshadow)

#### Defined in

[ue/ue.d.ts:12594](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12594)

___

### bCastHiddenShadow

• **bCastHiddenShadow**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCastHiddenShadow](ue_ue.ShapeComponent.md#bcasthiddenshadow)

#### Defined in

[ue/ue.d.ts:12597](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12597)

___

### bCastInsetShadow

• **bCastInsetShadow**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCastInsetShadow](ue_ue.ShapeComponent.md#bcastinsetshadow)

#### Defined in

[ue/ue.d.ts:12595](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12595)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCastShadowAsTwoSided](ue_ue.ShapeComponent.md#bcastshadowastwosided)

#### Defined in

[ue/ue.d.ts:12598](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12598)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCastStaticShadow](ue_ue.ShapeComponent.md#bcaststaticshadow)

#### Defined in

[ue/ue.d.ts:12591](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12591)

___

### bCastVolumetricTranslucentShadow

• **bCastVolumetricTranslucentShadow**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCastVolumetricTranslucentShadow](ue_ue.ShapeComponent.md#bcastvolumetrictranslucentshadow)

#### Defined in

[ue/ue.d.ts:12592](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12592)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bComponentToWorldUpdated](ue_ue.ShapeComponent.md#bcomponenttoworldupdated)

#### Defined in

[ue/ue.d.ts:12879](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12879)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCreatedByConstructionScript](ue_ue.ShapeComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L294)

___

### bDrawOnlyIfSelected

• **bDrawOnlyIfSelected**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bDrawOnlyIfSelected](ue_ue.ShapeComponent.md#bdrawonlyifselected)

#### Defined in

[ue/ue.d.ts:5835](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5835)

___

### bDynamicObstacle

• **bDynamicObstacle**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bDynamicObstacle](ue_ue.ShapeComponent.md#bdynamicobstacle)

#### Defined in

[ue/ue.d.ts:5837](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5837)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bEditableWhenInherited](ue_ue.ShapeComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L298)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bEnableAutoLODGeneration](ue_ue.ShapeComponent.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:12563](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12563)

___

### bExcludeFromLightAttachmentGroup

• **bExcludeFromLightAttachmentGroup**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bExcludeFromLightAttachmentGroup](ue_ue.ShapeComponent.md#bexcludefromlightattachmentgroup)

#### Defined in

[ue/ue.d.ts:12601](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12601)

___

### bForceMipStreaming

• **bForceMipStreaming**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bForceMipStreaming](ue_ue.ShapeComponent.md#bforcemipstreaming)

#### Defined in

[ue/ue.d.ts:12585](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12585)

___

### bGenerateOverlapEvents

• **bGenerateOverlapEvents**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bGenerateOverlapEvents](ue_ue.ShapeComponent.md#bgenerateoverlapevents)

#### Defined in

[ue/ue.d.ts:12568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12568)

___

### bHasCustomNavigableGeometry

• **bHasCustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bHasCustomNavigableGeometry](ue_ue.ShapeComponent.md#bhascustomnavigablegeometry)

#### Defined in

[ue/ue.d.ts:12612](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12612)

___

### bHasMotionBlurVelocityMeshes

• **bHasMotionBlurVelocityMeshes**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bHasMotionBlurVelocityMeshes](ue_ue.ShapeComponent.md#bhasmotionblurvelocitymeshes)

#### Defined in

[ue/ue.d.ts:12574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12574)

___

### bHasPerInstanceHitProxies

• **bHasPerInstanceHitProxies**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bHasPerInstanceHitProxies](ue_ue.ShapeComponent.md#bhasperinstancehitproxies)

#### Defined in

[ue/ue.d.ts:12586](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12586)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bHiddenInGame](ue_ue.ShapeComponent.md#bhiddeningame)

#### Defined in

[ue/ue.d.ts:12884](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12884)

___

### bIgnoreRadialForce

• **bIgnoreRadialForce**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bIgnoreRadialForce](ue_ue.ShapeComponent.md#bignoreradialforce)

#### Defined in

[ue/ue.d.ts:12605](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12605)

___

### bIgnoreRadialImpulse

• **bIgnoreRadialImpulse**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bIgnoreRadialImpulse](ue_ue.ShapeComponent.md#bignoreradialimpulse)

#### Defined in

[ue/ue.d.ts:12604](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12604)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bInstanceComponent](ue_ue.ShapeComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bIsActive](ue_ue.ShapeComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bIsEditorOnly](ue_ue.ShapeComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bIsVisualizationComponent](ue_ue.ShapeComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L301)

___

### bLightAsIfStatic

• **bLightAsIfStatic**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bLightAsIfStatic](ue_ue.ShapeComponent.md#blightasifstatic)

#### Defined in

[ue/ue.d.ts:12599](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12599)

___

### bLightAttachmentsAsGroup

• **bLightAttachmentsAsGroup**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bLightAttachmentsAsGroup](ue_ue.ShapeComponent.md#blightattachmentsasgroup)

#### Defined in

[ue/ue.d.ts:12600](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12600)

___

### bMultiBodyOverlap

• **bMultiBodyOverlap**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bMultiBodyOverlap](ue_ue.ShapeComponent.md#bmultibodyoverlap)

#### Defined in

[ue/ue.d.ts:12569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12569)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bNetAddressable](ue_ue.ShapeComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L293)

___

### bNeverDistanceCull

• **bNeverDistanceCull**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bNeverDistanceCull](ue_ue.ShapeComponent.md#bneverdistancecull)

#### Defined in

[ue/ue.d.ts:12566](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12566)

___

### bOnlyOwnerSee

• **bOnlyOwnerSee**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bOnlyOwnerSee](ue_ue.ShapeComponent.md#bonlyownersee)

#### Defined in

[ue/ue.d.ts:12581](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12581)

___

### bOwnerNoSee

• **bOwnerNoSee**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bOwnerNoSee](ue_ue.ShapeComponent.md#bownernosee)

#### Defined in

[ue/ue.d.ts:12580](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12580)

___

### bReceiveMobileCSMShadows

• **bReceiveMobileCSMShadows**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bReceiveMobileCSMShadows](ue_ue.ShapeComponent.md#breceivemobilecsmshadows)

#### Defined in

[ue/ue.d.ts:12602](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12602)

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bReceivesDecals](ue_ue.ShapeComponent.md#breceivesdecals)

#### Defined in

[ue/ue.d.ts:12579](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12579)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bRenderCustomDepth](ue_ue.ShapeComponent.md#brendercustomdepth)

#### Defined in

[ue/ue.d.ts:12611](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12611)

___

### bRenderInDepthPass

• **bRenderInDepthPass**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bRenderInDepthPass](ue_ue.ShapeComponent.md#brenderindepthpass)

#### Defined in

[ue/ue.d.ts:12578](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12578)

___

### bRenderInMainPass

• **bRenderInMainPass**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bRenderInMainPass](ue_ue.ShapeComponent.md#brenderinmainpass)

#### Defined in

[ue/ue.d.ts:12577](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12577)

___

### bReplicatePhysicsToAutonomousProxy

• **bReplicatePhysicsToAutonomousProxy**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bReplicatePhysicsToAutonomousProxy](ue_ue.ShapeComponent.md#breplicatephysicstoautonomousproxy)

#### Defined in

[ue/ue.d.ts:12607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12607)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bReplicates](ue_ue.ShapeComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L292)

___

### bReturnMaterialOnMove

• **bReturnMaterialOnMove**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bReturnMaterialOnMove](ue_ue.ShapeComponent.md#breturnmaterialonmove)

#### Defined in

[ue/ue.d.ts:12571](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12571)

___

### bSelectable

• **bSelectable**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bSelectable](ue_ue.ShapeComponent.md#bselectable)

#### Defined in

[ue/ue.d.ts:12584](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12584)

___

### bSelfShadowOnly

• **bSelfShadowOnly**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bSelfShadowOnly](ue_ue.ShapeComponent.md#bselfshadowonly)

#### Defined in

[ue/ue.d.ts:12593](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12593)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bShouldBeAttached](ue_ue.ShapeComponent.md#bshouldbeattached)

#### Defined in

[ue/ue.d.ts:12885](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12885)

___

### bShouldCollideWhenPlacing

• **bShouldCollideWhenPlacing**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bShouldCollideWhenPlacing](ue_ue.ShapeComponent.md#bshouldcollidewhenplacing)

#### Defined in

[ue/ue.d.ts:5836](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5836)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.ShapeComponent.md#bshouldsnaplocationwhenattached)

#### Defined in

[ue/ue.d.ts:12886](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12886)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.ShapeComponent.md#bshouldsnaprotationwhenattached)

#### Defined in

[ue/ue.d.ts:12887](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12887)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.ShapeComponent.md#bshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12888](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12888)

___

### bSingleSampleShadowFromStationaryLights

• **bSingleSampleShadowFromStationaryLights**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bSingleSampleShadowFromStationaryLights](ue_ue.ShapeComponent.md#bsinglesampleshadowfromstationarylights)

#### Defined in

[ue/ue.d.ts:12603](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12603)

___

### bTraceComplexOnMove

• **bTraceComplexOnMove**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bTraceComplexOnMove](ue_ue.ShapeComponent.md#btracecomplexonmove)

#### Defined in

[ue/ue.d.ts:12570](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12570)

___

### bTreatAsBackgroundForOcclusion

• **bTreatAsBackgroundForOcclusion**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bTreatAsBackgroundForOcclusion](ue_ue.ShapeComponent.md#btreatasbackgroundforocclusion)

#### Defined in

[ue/ue.d.ts:12582](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12582)

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bUseAsOccluder](ue_ue.ShapeComponent.md#buseasoccluder)

#### Defined in

[ue/ue.d.ts:12583](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12583)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bUseAttachParentBound](ue_ue.ShapeComponent.md#buseattachparentbound)

#### Defined in

[ue/ue.d.ts:12890](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12890)

___

### bUseEditorCompositing

• **bUseEditorCompositing**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bUseEditorCompositing](ue_ue.ShapeComponent.md#buseeditorcompositing)

#### Defined in

[ue/ue.d.ts:12610](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12610)

___

### bUseMaxLODAsImposter

• **bUseMaxLODAsImposter**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bUseMaxLODAsImposter](ue_ue.ShapeComponent.md#busemaxlodasimposter)

#### Defined in

[ue/ue.d.ts:12564](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12564)

___

### bUseViewOwnerDepthPriorityGroup

• **bUseViewOwnerDepthPriorityGroup**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bUseViewOwnerDepthPriorityGroup](ue_ue.ShapeComponent.md#buseviewownerdepthprioritygroup)

#### Defined in

[ue/ue.d.ts:12572](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12572)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bVisible](ue_ue.ShapeComponent.md#bvisible)

#### Defined in

[ue/ue.d.ts:12883](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12883)

___

### bVisibleInRayTracing

• **bVisibleInRayTracing**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bVisibleInRayTracing](ue_ue.ShapeComponent.md#bvisibleinraytracing)

#### Defined in

[ue/ue.d.ts:12576](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12576)

___

### bVisibleInReflectionCaptures

• **bVisibleInReflectionCaptures**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bVisibleInReflectionCaptures](ue_ue.ShapeComponent.md#bvisibleinreflectioncaptures)

#### Defined in

[ue/ue.d.ts:12575](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12575)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bVisualizeComponent](ue_ue.ShapeComponent.md#bvisualizecomponent)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[Activate](ue_ue.ShapeComponent.md#activate)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[AddAngularImpulse](ue_ue.ShapeComponent.md#addangularimpulse)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[AddAngularImpulseInDegrees](ue_ue.ShapeComponent.md#addangularimpulseindegrees)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[AddAngularImpulseInRadians](ue_ue.ShapeComponent.md#addangularimpulseinradians)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[AddForce](ue_ue.ShapeComponent.md#addforce)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[AddForceAtLocation](ue_ue.ShapeComponent.md#addforceatlocation)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[AddForceAtLocationLocal](ue_ue.ShapeComponent.md#addforceatlocationlocal)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[AddImpulse](ue_ue.ShapeComponent.md#addimpulse)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[AddImpulseAtLocation](ue_ue.ShapeComponent.md#addimpulseatlocation)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[AddRadialForce](ue_ue.ShapeComponent.md#addradialforce)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[AddRadialImpulse](ue_ue.ShapeComponent.md#addradialimpulse)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[AddTickPrerequisiteActor](ue_ue.ShapeComponent.md#addtickprerequisiteactor)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[AddTickPrerequisiteComponent](ue_ue.ShapeComponent.md#addtickprerequisitecomponent)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[AddTorque](ue_ue.ShapeComponent.md#addtorque)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[AddTorqueInDegrees](ue_ue.ShapeComponent.md#addtorqueindegrees)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[AddTorqueInRadians](ue_ue.ShapeComponent.md#addtorqueinradians)

#### Defined in

[ue/ue.d.ts:12657](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12657)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[CanCharacterStepUp](ue_ue.ShapeComponent.md#cancharacterstepup)

#### Defined in

[ue/ue.d.ts:12658](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12658)

___

### ClearMoveIgnoreActors

▸ **ClearMoveIgnoreActors**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ClearMoveIgnoreActors](ue_ue.ShapeComponent.md#clearmoveignoreactors)

#### Defined in

[ue/ue.d.ts:12659](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12659)

___

### ClearMoveIgnoreComponents

▸ **ClearMoveIgnoreComponents**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ClearMoveIgnoreComponents](ue_ue.ShapeComponent.md#clearmoveignorecomponents)

#### Defined in

[ue/ue.d.ts:12660](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12660)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[ComponentHasTag](ue_ue.ShapeComponent.md#componenthastag)

#### Defined in

[ue/ue.d.ts:309](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L309)

___

### CopyArrayOfMoveIgnoreActors

▸ **CopyArrayOfMoveIgnoreActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CopyArrayOfMoveIgnoreActors](ue_ue.ShapeComponent.md#copyarrayofmoveignoreactors)

#### Defined in

[ue/ue.d.ts:12661](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12661)

___

### CopyArrayOfMoveIgnoreComponents

▸ **CopyArrayOfMoveIgnoreComponents**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CopyArrayOfMoveIgnoreComponents](ue_ue.ShapeComponent.md#copyarrayofmoveignorecomponents)

#### Defined in

[ue/ue.d.ts:12662](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12662)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[CreateAndSetMaterialInstanceDynamic](ue_ue.ShapeComponent.md#createandsetmaterialinstancedynamic)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.ShapeComponent.md#createandsetmaterialinstancedynamicfrommaterial)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[CreateDefaultSubobject](ue_ue.ShapeComponent.md#createdefaultsubobject)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[CreateDynamicMaterialInstance](ue_ue.ShapeComponent.md#createdynamicmaterialinstance)

#### Defined in

[ue/ue.d.ts:12665](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12665)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[Deactivate](ue_ue.ShapeComponent.md#deactivate)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[DetachFromParent](ue_ue.ShapeComponent.md#detachfromparent)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[DoesSocketExist](ue_ue.ShapeComponent.md#doessocketexist)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[ExecuteUbergraph](ue_ue.ShapeComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetAllSocketNames](ue_ue.ShapeComponent.md#getallsocketnames)

#### Defined in

[ue/ue.d.ts:12897](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12897)

___

### GetAngularDamping

▸ **GetAngularDamping**(): `number`

#### Returns

`number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetAngularDamping](ue_ue.ShapeComponent.md#getangulardamping)

#### Defined in

[ue/ue.d.ts:12666](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12666)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetAttachParent](ue_ue.ShapeComponent.md#getattachparent)

#### Defined in

[ue/ue.d.ts:12898](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12898)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetAttachSocketName](ue_ue.ShapeComponent.md#getattachsocketname)

#### Defined in

[ue/ue.d.ts:12899](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12899)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetCenterOfMass](ue_ue.ShapeComponent.md#getcenterofmass)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetChildComponent](ue_ue.ShapeComponent.md#getchildcomponent)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetChildrenComponents](ue_ue.ShapeComponent.md#getchildrencomponents)

#### Defined in

[ue/ue.d.ts:12901](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12901)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetClass](ue_ue.ShapeComponent.md#getclass)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetClosestPointOnCollision](ue_ue.ShapeComponent.md#getclosestpointoncollision)

#### Defined in

[ue/ue.d.ts:12668](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12668)

___

### GetCollisionEnabled

▸ **GetCollisionEnabled**(): [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Returns

[`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetCollisionEnabled](ue_ue.ShapeComponent.md#getcollisionenabled)

#### Defined in

[ue/ue.d.ts:12669](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12669)

___

### GetCollisionObjectType

▸ **GetCollisionObjectType**(): [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Returns

[`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetCollisionObjectType](ue_ue.ShapeComponent.md#getcollisionobjecttype)

#### Defined in

[ue/ue.d.ts:12670](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12670)

___

### GetCollisionProfileName

▸ **GetCollisionProfileName**(): `string`

#### Returns

`string`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetCollisionProfileName](ue_ue.ShapeComponent.md#getcollisionprofilename)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetCollisionResponseToChannel](ue_ue.ShapeComponent.md#getcollisionresponsetochannel)

#### Defined in

[ue/ue.d.ts:12672](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12672)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetComponentTickInterval](ue_ue.ShapeComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L311)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetComponentVelocity](ue_ue.ShapeComponent.md#getcomponentvelocity)

#### Defined in

[ue/ue.d.ts:12902](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12902)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetForwardVector](ue_ue.ShapeComponent.md#getforwardvector)

#### Defined in

[ue/ue.d.ts:12903](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12903)

___

### GetGenerateOverlapEvents

▸ **GetGenerateOverlapEvents**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetGenerateOverlapEvents](ue_ue.ShapeComponent.md#getgenerateoverlapevents)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetInertiaTensor](ue_ue.ShapeComponent.md#getinertiatensor)

#### Defined in

[ue/ue.d.ts:12674](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12674)

___

### GetLinearDamping

▸ **GetLinearDamping**(): `number`

#### Returns

`number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetLinearDamping](ue_ue.ShapeComponent.md#getlineardamping)

#### Defined in

[ue/ue.d.ts:12675](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12675)

___

### GetMass

▸ **GetMass**(): `number`

#### Returns

`number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetMass](ue_ue.ShapeComponent.md#getmass)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetMassScale](ue_ue.ShapeComponent.md#getmassscale)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetMaterial](ue_ue.ShapeComponent.md#getmaterial)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetMaterialFromCollisionFaceIndex](ue_ue.ShapeComponent.md#getmaterialfromcollisionfaceindex)

#### Defined in

[ue/ue.d.ts:12679](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12679)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetName](ue_ue.ShapeComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetNumChildrenComponents](ue_ue.ShapeComponent.md#getnumchildrencomponents)

#### Defined in

[ue/ue.d.ts:12904](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12904)

___

### GetNumMaterials

▸ **GetNumMaterials**(): `number`

#### Returns

`number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetNumMaterials](ue_ue.ShapeComponent.md#getnummaterials)

#### Defined in

[ue/ue.d.ts:12680](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12680)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetOuter](ue_ue.ShapeComponent.md#getouter)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetOverlappingActors](ue_ue.ShapeComponent.md#getoverlappingactors)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetOverlappingComponents](ue_ue.ShapeComponent.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:12682](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12682)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetOwner](ue_ue.ShapeComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L312)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetParentComponents](ue_ue.ShapeComponent.md#getparentcomponents)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetPhysicsAngularVelocity](ue_ue.ShapeComponent.md#getphysicsangularvelocity)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetPhysicsAngularVelocityInDegrees](ue_ue.ShapeComponent.md#getphysicsangularvelocityindegrees)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetPhysicsAngularVelocityInRadians](ue_ue.ShapeComponent.md#getphysicsangularvelocityinradians)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetPhysicsLinearVelocity](ue_ue.ShapeComponent.md#getphysicslinearvelocity)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetPhysicsLinearVelocityAtPoint](ue_ue.ShapeComponent.md#getphysicslinearvelocityatpoint)

#### Defined in

[ue/ue.d.ts:12687](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12687)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetPhysicsVolume](ue_ue.ShapeComponent.md#getphysicsvolume)

#### Defined in

[ue/ue.d.ts:12906](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12906)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetRelativeTransform](ue_ue.ShapeComponent.md#getrelativetransform)

#### Defined in

[ue/ue.d.ts:12907](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12907)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetRightVector](ue_ue.ShapeComponent.md#getrightvector)

#### Defined in

[ue/ue.d.ts:12908](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12908)

___

### GetScaledSphereRadius

▸ **GetScaledSphereRadius**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:10530](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10530)

___

### GetShapeScale

▸ **GetShapeScale**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:10531](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10531)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.ShapeComponent.md#getshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12909](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12909)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetSocketLocation](ue_ue.ShapeComponent.md#getsocketlocation)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetSocketQuaternion](ue_ue.ShapeComponent.md#getsocketquaternion)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetSocketRotation](ue_ue.ShapeComponent.md#getsocketrotation)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[GetSocketTransform](ue_ue.ShapeComponent.md#getsockettransform)

#### Defined in

[ue/ue.d.ts:12913](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12913)

___

### GetUnscaledSphereRadius

▸ **GetUnscaledSphereRadius**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:10532](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10532)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetUpVector](ue_ue.ShapeComponent.md#getupvector)

#### Defined in

[ue/ue.d.ts:12914](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12914)

___

### GetWalkableSlopeOverride

▸ **GetWalkableSlopeOverride**(): [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Returns

[`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetWalkableSlopeOverride](ue_ue.ShapeComponent.md#getwalkableslopeoverride)

#### Defined in

[ue/ue.d.ts:12688](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12688)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetWorld](ue_ue.ShapeComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[IgnoreActorWhenMoving](ue_ue.ShapeComponent.md#ignoreactorwhenmoving)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[IgnoreComponentWhenMoving](ue_ue.ShapeComponent.md#ignorecomponentwhenmoving)

#### Defined in

[ue/ue.d.ts:12690](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12690)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[IsActive](ue_ue.ShapeComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L313)

___

### IsAnyRigidBodyAwake

▸ **IsAnyRigidBodyAwake**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[IsAnyRigidBodyAwake](ue_ue.ShapeComponent.md#isanyrigidbodyawake)

#### Defined in

[ue/ue.d.ts:12691](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12691)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[IsAnySimulatingPhysics](ue_ue.ShapeComponent.md#isanysimulatingphysics)

#### Defined in

[ue/ue.d.ts:12915](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12915)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[IsBeingDestroyed](ue_ue.ShapeComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[IsComponentTickEnabled](ue_ue.ShapeComponent.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L315)

___

### IsGravityEnabled

▸ **IsGravityEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[IsGravityEnabled](ue_ue.ShapeComponent.md#isgravityenabled)

#### Defined in

[ue/ue.d.ts:12692](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12692)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[IsOverlappingActor](ue_ue.ShapeComponent.md#isoverlappingactor)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[IsOverlappingComponent](ue_ue.ShapeComponent.md#isoverlappingcomponent)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[IsSimulatingPhysics](ue_ue.ShapeComponent.md#issimulatingphysics)

#### Defined in

[ue/ue.d.ts:12916](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12916)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[IsVisible](ue_ue.ShapeComponent.md#isvisible)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_AddLocalOffset](ue_ue.ShapeComponent.md#k2_addlocaloffset)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_AddLocalRotation](ue_ue.ShapeComponent.md#k2_addlocalrotation)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_AddLocalTransform](ue_ue.ShapeComponent.md#k2_addlocaltransform)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_AddRelativeLocation](ue_ue.ShapeComponent.md#k2_addrelativelocation)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_AddRelativeRotation](ue_ue.ShapeComponent.md#k2_addrelativerotation)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_AddWorldOffset](ue_ue.ShapeComponent.md#k2_addworldoffset)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_AddWorldRotation](ue_ue.ShapeComponent.md#k2_addworldrotation)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_AddWorldTransform](ue_ue.ShapeComponent.md#k2_addworldtransform)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_AttachTo](ue_ue.ShapeComponent.md#k2_attachto)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_AttachToComponent](ue_ue.ShapeComponent.md#k2_attachtocomponent)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_BoxOverlapComponent](ue_ue.ShapeComponent.md#k2_boxoverlapcomponent)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_DestroyComponent](ue_ue.ShapeComponent.md#k2_destroycomponent)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_DetachFromComponent](ue_ue.ShapeComponent.md#k2_detachfromcomponent)

#### Defined in

[ue/ue.d.ts:12928](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12928)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_GetComponentLocation](ue_ue.ShapeComponent.md#k2_getcomponentlocation)

#### Defined in

[ue/ue.d.ts:12929](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12929)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_GetComponentRotation](ue_ue.ShapeComponent.md#k2_getcomponentrotation)

#### Defined in

[ue/ue.d.ts:12930](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12930)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_GetComponentScale](ue_ue.ShapeComponent.md#k2_getcomponentscale)

#### Defined in

[ue/ue.d.ts:12931](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12931)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_GetComponentToWorld](ue_ue.ShapeComponent.md#k2_getcomponenttoworld)

#### Defined in

[ue/ue.d.ts:12932](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12932)

___

### K2\_IsCollisionEnabled

▸ **K2_IsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_IsCollisionEnabled](ue_ue.ShapeComponent.md#k2_iscollisionenabled)

#### Defined in

[ue/ue.d.ts:12696](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12696)

___

### K2\_IsPhysicsCollisionEnabled

▸ **K2_IsPhysicsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_IsPhysicsCollisionEnabled](ue_ue.ShapeComponent.md#k2_isphysicscollisionenabled)

#### Defined in

[ue/ue.d.ts:12697](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12697)

___

### K2\_IsQueryCollisionEnabled

▸ **K2_IsQueryCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_IsQueryCollisionEnabled](ue_ue.ShapeComponent.md#k2_isquerycollisionenabled)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_LineTraceComponent](ue_ue.ShapeComponent.md#k2_linetracecomponent)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_SetRelativeLocation](ue_ue.ShapeComponent.md#k2_setrelativelocation)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.ShapeComponent.md#k2_setrelativelocationandrotation)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_SetRelativeRotation](ue_ue.ShapeComponent.md#k2_setrelativerotation)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_SetRelativeTransform](ue_ue.ShapeComponent.md#k2_setrelativetransform)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_SetWorldLocation](ue_ue.ShapeComponent.md#k2_setworldlocation)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.ShapeComponent.md#k2_setworldlocationandrotation)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_SetWorldRotation](ue_ue.ShapeComponent.md#k2_setworldrotation)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_SetWorldTransform](ue_ue.ShapeComponent.md#k2_setworldtransform)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_SphereOverlapComponent](ue_ue.ShapeComponent.md#k2_sphereoverlapcomponent)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_SphereTraceComponent](ue_ue.ShapeComponent.md#k2_spheretracecomponent)

#### Defined in

[ue/ue.d.ts:12701](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12701)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnRep_AttachChildren](ue_ue.ShapeComponent.md#onrep_attachchildren)

#### Defined in

[ue/ue.d.ts:12941](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12941)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnRep_AttachParent](ue_ue.ShapeComponent.md#onrep_attachparent)

#### Defined in

[ue/ue.d.ts:12942](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12942)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnRep_AttachSocketName](ue_ue.ShapeComponent.md#onrep_attachsocketname)

#### Defined in

[ue/ue.d.ts:12943](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12943)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnRep_IsActive](ue_ue.ShapeComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L317)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnRep_Transform](ue_ue.ShapeComponent.md#onrep_transform)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[OnRep_Visibility](ue_ue.ShapeComponent.md#onrep_visibility)

#### Defined in

[ue/ue.d.ts:12945](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12945)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[PutRigidBodyToSleep](ue_ue.ShapeComponent.md#putrigidbodytosleep)

#### Defined in

[ue/ue.d.ts:12702](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12702)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ReceiveBeginPlay](ue_ue.ShapeComponent.md#receivebeginplay)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[ReceiveEndPlay](ue_ue.ShapeComponent.md#receiveendplay)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[ReceiveTick](ue_ue.ShapeComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[RegisterComponent](ue_ue.ShapeComponent.md#registercomponent)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[RemoveTickPrerequisiteActor](ue_ue.ShapeComponent.md#removetickprerequisiteactor)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.ShapeComponent.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L323)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ResetRelativeTransform](ue_ue.ShapeComponent.md#resetrelativetransform)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[ScaleByMomentOfInertia](ue_ue.ShapeComponent.md#scalebymomentofinertia)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetAbsolute](ue_ue.ShapeComponent.md#setabsolute)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetActive](ue_ue.ShapeComponent.md#setactive)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetAllMassScale](ue_ue.ShapeComponent.md#setallmassscale)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetAllPhysicsAngularVelocityInDegrees](ue_ue.ShapeComponent.md#setallphysicsangularvelocityindegrees)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetAllPhysicsAngularVelocityInRadians](ue_ue.ShapeComponent.md#setallphysicsangularvelocityinradians)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetAllPhysicsLinearVelocity](ue_ue.ShapeComponent.md#setallphysicslinearvelocity)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetAllUseCCD](ue_ue.ShapeComponent.md#setalluseccd)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetAngularDamping](ue_ue.ShapeComponent.md#setangulardamping)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetAutoActivate](ue_ue.ShapeComponent.md#setautoactivate)

#### Defined in

[ue/ue.d.ts:325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L325)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetBoundsScale](ue_ue.ShapeComponent.md#setboundsscale)

#### Defined in

[ue/ue.d.ts:12710](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12710)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetCastInsetShadow](ue_ue.ShapeComponent.md#setcastinsetshadow)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetCastShadow](ue_ue.ShapeComponent.md#setcastshadow)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetCenterOfMass](ue_ue.ShapeComponent.md#setcenterofmass)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetCollisionEnabled](ue_ue.ShapeComponent.md#setcollisionenabled)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetCollisionObjectType](ue_ue.ShapeComponent.md#setcollisionobjecttype)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetCollisionProfileName](ue_ue.ShapeComponent.md#setcollisionprofilename)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetCollisionResponseToAllChannels](ue_ue.ShapeComponent.md#setcollisionresponsetoallchannels)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetCollisionResponseToChannel](ue_ue.ShapeComponent.md#setcollisionresponsetochannel)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetComponentTickEnabled](ue_ue.ShapeComponent.md#setcomponenttickenabled)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetComponentTickInterval](ue_ue.ShapeComponent.md#setcomponenttickinterval)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetConstraintMode](ue_ue.ShapeComponent.md#setconstraintmode)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetCullDistance](ue_ue.ShapeComponent.md#setculldistance)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetCustomDepthStencilValue](ue_ue.ShapeComponent.md#setcustomdepthstencilvalue)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetCustomDepthStencilWriteMask](ue_ue.ShapeComponent.md#setcustomdepthstencilwritemask)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetCustomPrimitiveDataFloat](ue_ue.ShapeComponent.md#setcustomprimitivedatafloat)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetCustomPrimitiveDataVector2](ue_ue.ShapeComponent.md#setcustomprimitivedatavector2)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetCustomPrimitiveDataVector3](ue_ue.ShapeComponent.md#setcustomprimitivedatavector3)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetCustomPrimitiveDataVector4](ue_ue.ShapeComponent.md#setcustomprimitivedatavector4)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetEnableGravity](ue_ue.ShapeComponent.md#setenablegravity)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetExcludeFromLightAttachmentGroup](ue_ue.ShapeComponent.md#setexcludefromlightattachmentgroup)

#### Defined in

[ue/ue.d.ts:12728](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12728)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetGenerateOverlapEvents](ue_ue.ShapeComponent.md#setgenerateoverlapevents)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetHiddenInGame](ue_ue.ShapeComponent.md#sethiddeningame)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetIsReplicated](ue_ue.ShapeComponent.md#setisreplicated)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetLightAttachmentsAsGroup](ue_ue.ShapeComponent.md#setlightattachmentsasgroup)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetLinearDamping](ue_ue.ShapeComponent.md#setlineardamping)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetMassOverrideInKg](ue_ue.ShapeComponent.md#setmassoverrideinkg)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetMassScale](ue_ue.ShapeComponent.md#setmassscale)

#### Defined in

[ue/ue.d.ts:12733](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12733)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetMaterial](ue_ue.ShapeComponent.md#setmaterial)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetMaterialByName](ue_ue.ShapeComponent.md#setmaterialbyname)

#### Defined in

[ue/ue.d.ts:12735](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12735)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetMobility](ue_ue.ShapeComponent.md#setmobility)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetNotifyRigidBodyCollision](ue_ue.ShapeComponent.md#setnotifyrigidbodycollision)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetOnlyOwnerSee](ue_ue.ShapeComponent.md#setonlyownersee)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetOwnerNoSee](ue_ue.ShapeComponent.md#setownernosee)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetPhysMaterialOverride](ue_ue.ShapeComponent.md#setphysmaterialoverride)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetPhysicsAngularVelocity](ue_ue.ShapeComponent.md#setphysicsangularvelocity)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetPhysicsAngularVelocityInDegrees](ue_ue.ShapeComponent.md#setphysicsangularvelocityindegrees)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetPhysicsAngularVelocityInRadians](ue_ue.ShapeComponent.md#setphysicsangularvelocityinradians)

#### Defined in

[ue/ue.d.ts:12741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12741)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetPhysicsLinearVelocity](ue_ue.ShapeComponent.md#setphysicslinearvelocity)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetPhysicsMaxAngularVelocity](ue_ue.ShapeComponent.md#setphysicsmaxangularvelocity)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetPhysicsMaxAngularVelocityInDegrees](ue_ue.ShapeComponent.md#setphysicsmaxangularvelocityindegrees)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetPhysicsMaxAngularVelocityInRadians](ue_ue.ShapeComponent.md#setphysicsmaxangularvelocityinradians)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetReceivesDecals](ue_ue.ShapeComponent.md#setreceivesdecals)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetRelativeScale3D](ue_ue.ShapeComponent.md#setrelativescale3d)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetRenderCustomDepth](ue_ue.ShapeComponent.md#setrendercustomdepth)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetRenderInMainPass](ue_ue.ShapeComponent.md#setrenderinmainpass)

#### Defined in

[ue/ue.d.ts:12749](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12749)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.ShapeComponent.md#setshouldupdatephysicsvolume)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetSimulatePhysics](ue_ue.ShapeComponent.md#setsimulatephysics)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetSingleSampleShadowFromStationaryLights](ue_ue.ShapeComponent.md#setsinglesampleshadowfromstationarylights)

#### Defined in

[ue/ue.d.ts:12751](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12751)

___

### SetSphereRadius

▸ **SetSphereRadius**(`InSphereRadius`, `bUpdateOverlaps?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSphereRadius` | `number` |
| `bUpdateOverlaps?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:10533](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10533)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetTickGroup](ue_ue.ShapeComponent.md#settickgroup)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetTickableWhenPaused](ue_ue.ShapeComponent.md#settickablewhenpaused)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetTranslucentSortPriority](ue_ue.ShapeComponent.md#settranslucentsortpriority)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetUseCCD](ue_ue.ShapeComponent.md#setuseccd)

#### Defined in

[ue/ue.d.ts:12753](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12753)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetVisibility](ue_ue.ShapeComponent.md#setvisibility)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetWalkableSlopeOverride](ue_ue.ShapeComponent.md#setwalkableslopeoverride)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetWorldScale3D](ue_ue.ShapeComponent.md#setworldscale3d)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SetupAttachment](ue_ue.ShapeComponent.md#setupattachment)

#### Defined in

[ue/ue.d.ts:12952](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12952)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[SnapTo](ue_ue.ShapeComponent.md#snapto)

#### Defined in

[ue/ue.d.ts:12955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12955)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ToggleActive](ue_ue.ShapeComponent.md#toggleactive)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[ToggleVisibility](ue_ue.ShapeComponent.md#togglevisibility)

#### Defined in

[ue/ue.d.ts:12956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12956)

___

### WakeAllRigidBodies

▸ **WakeAllRigidBodies**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[WakeAllRigidBodies](ue_ue.ShapeComponent.md#wakeallrigidbodies)

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

[ShapeComponent](ue_ue.ShapeComponent.md).[WakeRigidBody](ue_ue.ShapeComponent.md#wakerigidbody)

#### Defined in

[ue/ue.d.ts:12756](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12756)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SphereComponent`](ue_ue.SphereComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SphereComponent`](ue_ue.SphereComponent.md)

#### Overrides

[ShapeComponent](ue_ue.ShapeComponent.md).[Find](ue_ue.ShapeComponent.md#find)

#### Defined in

[ue/ue.d.ts:10535](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10535)

___

### Load

▸ `Static` **Load**(`InName`): [`SphereComponent`](ue_ue.SphereComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SphereComponent`](ue_ue.SphereComponent.md)

#### Overrides

[ShapeComponent](ue_ue.ShapeComponent.md).[Load](ue_ue.ShapeComponent.md#load)

#### Defined in

[ue/ue.d.ts:10536](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10536)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ShapeComponent](ue_ue.ShapeComponent.md).[StaticClass](ue_ue.ShapeComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:10534](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10534)
