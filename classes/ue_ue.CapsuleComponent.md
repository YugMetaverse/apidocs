[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CapsuleComponent

# Class: CapsuleComponent

[ue/ue](../modules/ue_ue.md).CapsuleComponent

## Hierarchy

- [`ShapeComponent`](ue_ue.ShapeComponent.md)

  ↳ **`CapsuleComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.CapsuleComponent.md#constructor)

### Properties

- [AlwaysLoadOnClient](ue_ue.CapsuleComponent.md#alwaysloadonclient)
- [AlwaysLoadOnServer](ue_ue.CapsuleComponent.md#alwaysloadonserver)
- [AreaClass](ue_ue.CapsuleComponent.md#areaclass)
- [AssetUserData](ue_ue.CapsuleComponent.md#assetuserdata)
- [AttachChildren](ue_ue.CapsuleComponent.md#attachchildren)
- [AttachParent](ue_ue.CapsuleComponent.md#attachparent)
- [AttachSocketName](ue_ue.CapsuleComponent.md#attachsocketname)
- [BodyInstance](ue_ue.CapsuleComponent.md#bodyinstance)
- [BoundsScale](ue_ue.CapsuleComponent.md#boundsscale)
- [CachedMaxDrawDistance](ue_ue.CapsuleComponent.md#cachedmaxdrawdistance)
- [CanBeCharacterBase](ue_ue.CapsuleComponent.md#canbecharacterbase)
- [CanCharacterStepUpOn](ue_ue.CapsuleComponent.md#cancharacterstepupon)
- [CapsuleHalfHeight](ue_ue.CapsuleComponent.md#capsulehalfheight)
- [CapsuleHeight](ue_ue.CapsuleComponent.md#capsuleheight)
- [CapsuleRadius](ue_ue.CapsuleComponent.md#capsuleradius)
- [CastShadow](ue_ue.CapsuleComponent.md#castshadow)
- [ClientAttachedChildren](ue_ue.CapsuleComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.CapsuleComponent.md#componenttags)
- [ComponentVelocity](ue_ue.CapsuleComponent.md#componentvelocity)
- [CreationMethod](ue_ue.CapsuleComponent.md#creationmethod)
- [CustomDepthStencilValue](ue_ue.CapsuleComponent.md#customdepthstencilvalue)
- [CustomDepthStencilWriteMask](ue_ue.CapsuleComponent.md#customdepthstencilwritemask)
- [CustomPrimitiveData](ue_ue.CapsuleComponent.md#customprimitivedata)
- [DepthPriorityGroup](ue_ue.CapsuleComponent.md#depthprioritygroup)
- [DetailMode](ue_ue.CapsuleComponent.md#detailmode)
- [ExcludeForSpecificHLODLevels](ue_ue.CapsuleComponent.md#excludeforspecifichlodlevels)
- [IndirectLightingCacheQuality](ue_ue.CapsuleComponent.md#indirectlightingcachequality)
- [LDMaxDrawDistance](ue_ue.CapsuleComponent.md#ldmaxdrawdistance)
- [LODParentPrimitive](ue_ue.CapsuleComponent.md#lodparentprimitive)
- [LightingChannels](ue_ue.CapsuleComponent.md#lightingchannels)
- [LightmapType](ue_ue.CapsuleComponent.md#lightmaptype)
- [LpvBiasMultiplier](ue_ue.CapsuleComponent.md#lpvbiasmultiplier)
- [MinDrawDistance](ue_ue.CapsuleComponent.md#mindrawdistance)
- [Mobility](ue_ue.CapsuleComponent.md#mobility)
- [MoveIgnoreActors](ue_ue.CapsuleComponent.md#moveignoreactors)
- [MoveIgnoreComponents](ue_ue.CapsuleComponent.md#moveignorecomponents)
- [OnBeginCursorOver](ue_ue.CapsuleComponent.md#onbegincursorover)
- [OnClicked](ue_ue.CapsuleComponent.md#onclicked)
- [OnComponentActivated](ue_ue.CapsuleComponent.md#oncomponentactivated)
- [OnComponentBeginOverlap](ue_ue.CapsuleComponent.md#oncomponentbeginoverlap)
- [OnComponentDeactivated](ue_ue.CapsuleComponent.md#oncomponentdeactivated)
- [OnComponentEndOverlap](ue_ue.CapsuleComponent.md#oncomponentendoverlap)
- [OnComponentHit](ue_ue.CapsuleComponent.md#oncomponenthit)
- [OnComponentSleep](ue_ue.CapsuleComponent.md#oncomponentsleep)
- [OnComponentWake](ue_ue.CapsuleComponent.md#oncomponentwake)
- [OnEndCursorOver](ue_ue.CapsuleComponent.md#onendcursorover)
- [OnInputTouchBegin](ue_ue.CapsuleComponent.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.CapsuleComponent.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.CapsuleComponent.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.CapsuleComponent.md#oninputtouchleave)
- [OnReleased](ue_ue.CapsuleComponent.md#onreleased)
- [PhysicsVolume](ue_ue.CapsuleComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.CapsuleComponent.md#physicsvolumechangeddelegate)
- [PrimaryComponentTick](ue_ue.CapsuleComponent.md#primarycomponenttick)
- [RelativeLocation](ue_ue.CapsuleComponent.md#relativelocation)
- [RelativeRotation](ue_ue.CapsuleComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.CapsuleComponent.md#relativescale3d)
- [RuntimeVirtualTextures](ue_ue.CapsuleComponent.md#runtimevirtualtextures)
- [ShapeBodySetup](ue_ue.CapsuleComponent.md#shapebodysetup)
- [ShapeColor](ue_ue.CapsuleComponent.md#shapecolor)
- [TranslucencySortPriority](ue_ue.CapsuleComponent.md#translucencysortpriority)
- [UCSModifiedProperties](ue_ue.CapsuleComponent.md#ucsmodifiedproperties)
- [ViewOwnerDepthPriorityGroup](ue_ue.CapsuleComponent.md#viewownerdepthprioritygroup)
- [VirtualTextureCullMips](ue_ue.CapsuleComponent.md#virtualtexturecullmips)
- [VirtualTextureLodBias](ue_ue.CapsuleComponent.md#virtualtexturelodbias)
- [VirtualTextureMinCoverage](ue_ue.CapsuleComponent.md#virtualtexturemincoverage)
- [VirtualTextureRenderPassType](ue_ue.CapsuleComponent.md#virtualtexturerenderpasstype)
- [VisibilityId](ue_ue.CapsuleComponent.md#visibilityid)
- [\_\_tid\_ActorComponent\_\_](ue_ue.CapsuleComponent.md#__tid_actorcomponent__)
- [\_\_tid\_CapsuleComponent\_\_](ue_ue.CapsuleComponent.md#__tid_capsulecomponent__)
- [\_\_tid\_Object\_\_](ue_ue.CapsuleComponent.md#__tid_object__)
- [\_\_tid\_PrimitiveComponent\_\_](ue_ue.CapsuleComponent.md#__tid_primitivecomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.CapsuleComponent.md#__tid_scenecomponent__)
- [\_\_tid\_ShapeComponent\_\_](ue_ue.CapsuleComponent.md#__tid_shapecomponent__)
- [bAbsoluteLocation](ue_ue.CapsuleComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.CapsuleComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.CapsuleComponent.md#babsolutescale)
- [bAffectDistanceFieldLighting](ue_ue.CapsuleComponent.md#baffectdistancefieldlighting)
- [bAffectDynamicIndirectLighting](ue_ue.CapsuleComponent.md#baffectdynamicindirectlighting)
- [bAllowCullDistanceVolume](ue_ue.CapsuleComponent.md#ballowculldistancevolume)
- [bAlwaysCreatePhysicsState](ue_ue.CapsuleComponent.md#balwayscreatephysicsstate)
- [bApplyImpulseOnDamage](ue_ue.CapsuleComponent.md#bapplyimpulseondamage)
- [bAutoActivate](ue_ue.CapsuleComponent.md#bautoactivate)
- [bBatchImpostersAsInstances](ue_ue.CapsuleComponent.md#bbatchimpostersasinstances)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.CapsuleComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.CapsuleComponent.md#bcaneveraffectnavigation)
- [bCastCinematicShadow](ue_ue.CapsuleComponent.md#bcastcinematicshadow)
- [bCastDynamicShadow](ue_ue.CapsuleComponent.md#bcastdynamicshadow)
- [bCastFarShadow](ue_ue.CapsuleComponent.md#bcastfarshadow)
- [bCastHiddenShadow](ue_ue.CapsuleComponent.md#bcasthiddenshadow)
- [bCastInsetShadow](ue_ue.CapsuleComponent.md#bcastinsetshadow)
- [bCastShadowAsTwoSided](ue_ue.CapsuleComponent.md#bcastshadowastwosided)
- [bCastStaticShadow](ue_ue.CapsuleComponent.md#bcaststaticshadow)
- [bCastVolumetricTranslucentShadow](ue_ue.CapsuleComponent.md#bcastvolumetrictranslucentshadow)
- [bComponentToWorldUpdated](ue_ue.CapsuleComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.CapsuleComponent.md#bcreatedbyconstructionscript)
- [bDrawOnlyIfSelected](ue_ue.CapsuleComponent.md#bdrawonlyifselected)
- [bDynamicObstacle](ue_ue.CapsuleComponent.md#bdynamicobstacle)
- [bEditableWhenInherited](ue_ue.CapsuleComponent.md#beditablewheninherited)
- [bEnableAutoLODGeneration](ue_ue.CapsuleComponent.md#benableautolodgeneration)
- [bExcludeFromLightAttachmentGroup](ue_ue.CapsuleComponent.md#bexcludefromlightattachmentgroup)
- [bForceMipStreaming](ue_ue.CapsuleComponent.md#bforcemipstreaming)
- [bGenerateOverlapEvents](ue_ue.CapsuleComponent.md#bgenerateoverlapevents)
- [bHasCustomNavigableGeometry](ue_ue.CapsuleComponent.md#bhascustomnavigablegeometry)
- [bHasMotionBlurVelocityMeshes](ue_ue.CapsuleComponent.md#bhasmotionblurvelocitymeshes)
- [bHasPerInstanceHitProxies](ue_ue.CapsuleComponent.md#bhasperinstancehitproxies)
- [bHiddenInGame](ue_ue.CapsuleComponent.md#bhiddeningame)
- [bIgnoreRadialForce](ue_ue.CapsuleComponent.md#bignoreradialforce)
- [bIgnoreRadialImpulse](ue_ue.CapsuleComponent.md#bignoreradialimpulse)
- [bInstanceComponent](ue_ue.CapsuleComponent.md#binstancecomponent)
- [bIsActive](ue_ue.CapsuleComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.CapsuleComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.CapsuleComponent.md#bisvisualizationcomponent)
- [bLightAsIfStatic](ue_ue.CapsuleComponent.md#blightasifstatic)
- [bLightAttachmentsAsGroup](ue_ue.CapsuleComponent.md#blightattachmentsasgroup)
- [bMultiBodyOverlap](ue_ue.CapsuleComponent.md#bmultibodyoverlap)
- [bNetAddressable](ue_ue.CapsuleComponent.md#bnetaddressable)
- [bNeverDistanceCull](ue_ue.CapsuleComponent.md#bneverdistancecull)
- [bOnlyOwnerSee](ue_ue.CapsuleComponent.md#bonlyownersee)
- [bOwnerNoSee](ue_ue.CapsuleComponent.md#bownernosee)
- [bReceiveMobileCSMShadows](ue_ue.CapsuleComponent.md#breceivemobilecsmshadows)
- [bReceivesDecals](ue_ue.CapsuleComponent.md#breceivesdecals)
- [bRenderCustomDepth](ue_ue.CapsuleComponent.md#brendercustomdepth)
- [bRenderInDepthPass](ue_ue.CapsuleComponent.md#brenderindepthpass)
- [bRenderInMainPass](ue_ue.CapsuleComponent.md#brenderinmainpass)
- [bReplicatePhysicsToAutonomousProxy](ue_ue.CapsuleComponent.md#breplicatephysicstoautonomousproxy)
- [bReplicates](ue_ue.CapsuleComponent.md#breplicates)
- [bReturnMaterialOnMove](ue_ue.CapsuleComponent.md#breturnmaterialonmove)
- [bSelectable](ue_ue.CapsuleComponent.md#bselectable)
- [bSelfShadowOnly](ue_ue.CapsuleComponent.md#bselfshadowonly)
- [bShouldBeAttached](ue_ue.CapsuleComponent.md#bshouldbeattached)
- [bShouldCollideWhenPlacing](ue_ue.CapsuleComponent.md#bshouldcollidewhenplacing)
- [bShouldSnapLocationWhenAttached](ue_ue.CapsuleComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.CapsuleComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.CapsuleComponent.md#bshouldupdatephysicsvolume)
- [bSingleSampleShadowFromStationaryLights](ue_ue.CapsuleComponent.md#bsinglesampleshadowfromstationarylights)
- [bTraceComplexOnMove](ue_ue.CapsuleComponent.md#btracecomplexonmove)
- [bTreatAsBackgroundForOcclusion](ue_ue.CapsuleComponent.md#btreatasbackgroundforocclusion)
- [bUseAsOccluder](ue_ue.CapsuleComponent.md#buseasoccluder)
- [bUseAttachParentBound](ue_ue.CapsuleComponent.md#buseattachparentbound)
- [bUseEditorCompositing](ue_ue.CapsuleComponent.md#buseeditorcompositing)
- [bUseMaxLODAsImposter](ue_ue.CapsuleComponent.md#busemaxlodasimposter)
- [bUseViewOwnerDepthPriorityGroup](ue_ue.CapsuleComponent.md#buseviewownerdepthprioritygroup)
- [bVisible](ue_ue.CapsuleComponent.md#bvisible)
- [bVisibleInRayTracing](ue_ue.CapsuleComponent.md#bvisibleinraytracing)
- [bVisibleInReflectionCaptures](ue_ue.CapsuleComponent.md#bvisibleinreflectioncaptures)
- [bVisualizeComponent](ue_ue.CapsuleComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.CapsuleComponent.md#activate)
- [AddAngularImpulse](ue_ue.CapsuleComponent.md#addangularimpulse)
- [AddAngularImpulseInDegrees](ue_ue.CapsuleComponent.md#addangularimpulseindegrees)
- [AddAngularImpulseInRadians](ue_ue.CapsuleComponent.md#addangularimpulseinradians)
- [AddForce](ue_ue.CapsuleComponent.md#addforce)
- [AddForceAtLocation](ue_ue.CapsuleComponent.md#addforceatlocation)
- [AddForceAtLocationLocal](ue_ue.CapsuleComponent.md#addforceatlocationlocal)
- [AddImpulse](ue_ue.CapsuleComponent.md#addimpulse)
- [AddImpulseAtLocation](ue_ue.CapsuleComponent.md#addimpulseatlocation)
- [AddRadialForce](ue_ue.CapsuleComponent.md#addradialforce)
- [AddRadialImpulse](ue_ue.CapsuleComponent.md#addradialimpulse)
- [AddTickPrerequisiteActor](ue_ue.CapsuleComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.CapsuleComponent.md#addtickprerequisitecomponent)
- [AddTorque](ue_ue.CapsuleComponent.md#addtorque)
- [AddTorqueInDegrees](ue_ue.CapsuleComponent.md#addtorqueindegrees)
- [AddTorqueInRadians](ue_ue.CapsuleComponent.md#addtorqueinradians)
- [CanCharacterStepUp](ue_ue.CapsuleComponent.md#cancharacterstepup)
- [ClearMoveIgnoreActors](ue_ue.CapsuleComponent.md#clearmoveignoreactors)
- [ClearMoveIgnoreComponents](ue_ue.CapsuleComponent.md#clearmoveignorecomponents)
- [ComponentHasTag](ue_ue.CapsuleComponent.md#componenthastag)
- [CopyArrayOfMoveIgnoreActors](ue_ue.CapsuleComponent.md#copyarrayofmoveignoreactors)
- [CopyArrayOfMoveIgnoreComponents](ue_ue.CapsuleComponent.md#copyarrayofmoveignorecomponents)
- [CreateAndSetMaterialInstanceDynamic](ue_ue.CapsuleComponent.md#createandsetmaterialinstancedynamic)
- [CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.CapsuleComponent.md#createandsetmaterialinstancedynamicfrommaterial)
- [CreateDefaultSubobject](ue_ue.CapsuleComponent.md#createdefaultsubobject)
- [CreateDynamicMaterialInstance](ue_ue.CapsuleComponent.md#createdynamicmaterialinstance)
- [Deactivate](ue_ue.CapsuleComponent.md#deactivate)
- [DetachFromParent](ue_ue.CapsuleComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.CapsuleComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.CapsuleComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.CapsuleComponent.md#getallsocketnames)
- [GetAngularDamping](ue_ue.CapsuleComponent.md#getangulardamping)
- [GetAttachParent](ue_ue.CapsuleComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.CapsuleComponent.md#getattachsocketname)
- [GetCenterOfMass](ue_ue.CapsuleComponent.md#getcenterofmass)
- [GetChildComponent](ue_ue.CapsuleComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.CapsuleComponent.md#getchildrencomponents)
- [GetClass](ue_ue.CapsuleComponent.md#getclass)
- [GetClosestPointOnCollision](ue_ue.CapsuleComponent.md#getclosestpointoncollision)
- [GetCollisionEnabled](ue_ue.CapsuleComponent.md#getcollisionenabled)
- [GetCollisionObjectType](ue_ue.CapsuleComponent.md#getcollisionobjecttype)
- [GetCollisionProfileName](ue_ue.CapsuleComponent.md#getcollisionprofilename)
- [GetCollisionResponseToChannel](ue_ue.CapsuleComponent.md#getcollisionresponsetochannel)
- [GetComponentTickInterval](ue_ue.CapsuleComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.CapsuleComponent.md#getcomponentvelocity)
- [GetForwardVector](ue_ue.CapsuleComponent.md#getforwardvector)
- [GetGenerateOverlapEvents](ue_ue.CapsuleComponent.md#getgenerateoverlapevents)
- [GetInertiaTensor](ue_ue.CapsuleComponent.md#getinertiatensor)
- [GetLinearDamping](ue_ue.CapsuleComponent.md#getlineardamping)
- [GetMass](ue_ue.CapsuleComponent.md#getmass)
- [GetMassScale](ue_ue.CapsuleComponent.md#getmassscale)
- [GetMaterial](ue_ue.CapsuleComponent.md#getmaterial)
- [GetMaterialFromCollisionFaceIndex](ue_ue.CapsuleComponent.md#getmaterialfromcollisionfaceindex)
- [GetName](ue_ue.CapsuleComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.CapsuleComponent.md#getnumchildrencomponents)
- [GetNumMaterials](ue_ue.CapsuleComponent.md#getnummaterials)
- [GetOuter](ue_ue.CapsuleComponent.md#getouter)
- [GetOverlappingActors](ue_ue.CapsuleComponent.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.CapsuleComponent.md#getoverlappingcomponents)
- [GetOwner](ue_ue.CapsuleComponent.md#getowner)
- [GetParentComponents](ue_ue.CapsuleComponent.md#getparentcomponents)
- [GetPhysicsAngularVelocity](ue_ue.CapsuleComponent.md#getphysicsangularvelocity)
- [GetPhysicsAngularVelocityInDegrees](ue_ue.CapsuleComponent.md#getphysicsangularvelocityindegrees)
- [GetPhysicsAngularVelocityInRadians](ue_ue.CapsuleComponent.md#getphysicsangularvelocityinradians)
- [GetPhysicsLinearVelocity](ue_ue.CapsuleComponent.md#getphysicslinearvelocity)
- [GetPhysicsLinearVelocityAtPoint](ue_ue.CapsuleComponent.md#getphysicslinearvelocityatpoint)
- [GetPhysicsVolume](ue_ue.CapsuleComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.CapsuleComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.CapsuleComponent.md#getrightvector)
- [GetScaledCapsuleHalfHeight](ue_ue.CapsuleComponent.md#getscaledcapsulehalfheight)
- [GetScaledCapsuleHalfHeight\_WithoutHemisphere](ue_ue.CapsuleComponent.md#getscaledcapsulehalfheight_withouthemisphere)
- [GetScaledCapsuleRadius](ue_ue.CapsuleComponent.md#getscaledcapsuleradius)
- [GetScaledCapsuleSize](ue_ue.CapsuleComponent.md#getscaledcapsulesize)
- [GetScaledCapsuleSize\_WithoutHemisphere](ue_ue.CapsuleComponent.md#getscaledcapsulesize_withouthemisphere)
- [GetShapeScale](ue_ue.CapsuleComponent.md#getshapescale)
- [GetShouldUpdatePhysicsVolume](ue_ue.CapsuleComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.CapsuleComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.CapsuleComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.CapsuleComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.CapsuleComponent.md#getsockettransform)
- [GetUnscaledCapsuleHalfHeight](ue_ue.CapsuleComponent.md#getunscaledcapsulehalfheight)
- [GetUnscaledCapsuleHalfHeight\_WithoutHemisphere](ue_ue.CapsuleComponent.md#getunscaledcapsulehalfheight_withouthemisphere)
- [GetUnscaledCapsuleRadius](ue_ue.CapsuleComponent.md#getunscaledcapsuleradius)
- [GetUnscaledCapsuleSize](ue_ue.CapsuleComponent.md#getunscaledcapsulesize)
- [GetUnscaledCapsuleSize\_WithoutHemisphere](ue_ue.CapsuleComponent.md#getunscaledcapsulesize_withouthemisphere)
- [GetUpVector](ue_ue.CapsuleComponent.md#getupvector)
- [GetWalkableSlopeOverride](ue_ue.CapsuleComponent.md#getwalkableslopeoverride)
- [GetWorld](ue_ue.CapsuleComponent.md#getworld)
- [IgnoreActorWhenMoving](ue_ue.CapsuleComponent.md#ignoreactorwhenmoving)
- [IgnoreComponentWhenMoving](ue_ue.CapsuleComponent.md#ignorecomponentwhenmoving)
- [IsActive](ue_ue.CapsuleComponent.md#isactive)
- [IsAnyRigidBodyAwake](ue_ue.CapsuleComponent.md#isanyrigidbodyawake)
- [IsAnySimulatingPhysics](ue_ue.CapsuleComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.CapsuleComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.CapsuleComponent.md#iscomponenttickenabled)
- [IsGravityEnabled](ue_ue.CapsuleComponent.md#isgravityenabled)
- [IsOverlappingActor](ue_ue.CapsuleComponent.md#isoverlappingactor)
- [IsOverlappingComponent](ue_ue.CapsuleComponent.md#isoverlappingcomponent)
- [IsSimulatingPhysics](ue_ue.CapsuleComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.CapsuleComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.CapsuleComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.CapsuleComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.CapsuleComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.CapsuleComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.CapsuleComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.CapsuleComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.CapsuleComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.CapsuleComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.CapsuleComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.CapsuleComponent.md#k2_attachtocomponent)
- [K2\_BoxOverlapComponent](ue_ue.CapsuleComponent.md#k2_boxoverlapcomponent)
- [K2\_DestroyComponent](ue_ue.CapsuleComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.CapsuleComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.CapsuleComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.CapsuleComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.CapsuleComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.CapsuleComponent.md#k2_getcomponenttoworld)
- [K2\_IsCollisionEnabled](ue_ue.CapsuleComponent.md#k2_iscollisionenabled)
- [K2\_IsPhysicsCollisionEnabled](ue_ue.CapsuleComponent.md#k2_isphysicscollisionenabled)
- [K2\_IsQueryCollisionEnabled](ue_ue.CapsuleComponent.md#k2_isquerycollisionenabled)
- [K2\_LineTraceComponent](ue_ue.CapsuleComponent.md#k2_linetracecomponent)
- [K2\_SetRelativeLocation](ue_ue.CapsuleComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.CapsuleComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.CapsuleComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.CapsuleComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.CapsuleComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.CapsuleComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.CapsuleComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.CapsuleComponent.md#k2_setworldtransform)
- [K2\_SphereOverlapComponent](ue_ue.CapsuleComponent.md#k2_sphereoverlapcomponent)
- [K2\_SphereTraceComponent](ue_ue.CapsuleComponent.md#k2_spheretracecomponent)
- [OnRep\_AttachChildren](ue_ue.CapsuleComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.CapsuleComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.CapsuleComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.CapsuleComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.CapsuleComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.CapsuleComponent.md#onrep_visibility)
- [PutRigidBodyToSleep](ue_ue.CapsuleComponent.md#putrigidbodytosleep)
- [ReceiveBeginPlay](ue_ue.CapsuleComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.CapsuleComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.CapsuleComponent.md#receivetick)
- [RegisterComponent](ue_ue.CapsuleComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.CapsuleComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.CapsuleComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.CapsuleComponent.md#resetrelativetransform)
- [ScaleByMomentOfInertia](ue_ue.CapsuleComponent.md#scalebymomentofinertia)
- [SetAbsolute](ue_ue.CapsuleComponent.md#setabsolute)
- [SetActive](ue_ue.CapsuleComponent.md#setactive)
- [SetAllMassScale](ue_ue.CapsuleComponent.md#setallmassscale)
- [SetAllPhysicsAngularVelocityInDegrees](ue_ue.CapsuleComponent.md#setallphysicsangularvelocityindegrees)
- [SetAllPhysicsAngularVelocityInRadians](ue_ue.CapsuleComponent.md#setallphysicsangularvelocityinradians)
- [SetAllPhysicsLinearVelocity](ue_ue.CapsuleComponent.md#setallphysicslinearvelocity)
- [SetAllUseCCD](ue_ue.CapsuleComponent.md#setalluseccd)
- [SetAngularDamping](ue_ue.CapsuleComponent.md#setangulardamping)
- [SetAutoActivate](ue_ue.CapsuleComponent.md#setautoactivate)
- [SetBoundsScale](ue_ue.CapsuleComponent.md#setboundsscale)
- [SetCapsuleHalfHeight](ue_ue.CapsuleComponent.md#setcapsulehalfheight)
- [SetCapsuleRadius](ue_ue.CapsuleComponent.md#setcapsuleradius)
- [SetCapsuleSize](ue_ue.CapsuleComponent.md#setcapsulesize)
- [SetCastInsetShadow](ue_ue.CapsuleComponent.md#setcastinsetshadow)
- [SetCastShadow](ue_ue.CapsuleComponent.md#setcastshadow)
- [SetCenterOfMass](ue_ue.CapsuleComponent.md#setcenterofmass)
- [SetCollisionEnabled](ue_ue.CapsuleComponent.md#setcollisionenabled)
- [SetCollisionObjectType](ue_ue.CapsuleComponent.md#setcollisionobjecttype)
- [SetCollisionProfileName](ue_ue.CapsuleComponent.md#setcollisionprofilename)
- [SetCollisionResponseToAllChannels](ue_ue.CapsuleComponent.md#setcollisionresponsetoallchannels)
- [SetCollisionResponseToChannel](ue_ue.CapsuleComponent.md#setcollisionresponsetochannel)
- [SetComponentTickEnabled](ue_ue.CapsuleComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.CapsuleComponent.md#setcomponenttickinterval)
- [SetConstraintMode](ue_ue.CapsuleComponent.md#setconstraintmode)
- [SetCullDistance](ue_ue.CapsuleComponent.md#setculldistance)
- [SetCustomDepthStencilValue](ue_ue.CapsuleComponent.md#setcustomdepthstencilvalue)
- [SetCustomDepthStencilWriteMask](ue_ue.CapsuleComponent.md#setcustomdepthstencilwritemask)
- [SetCustomPrimitiveDataFloat](ue_ue.CapsuleComponent.md#setcustomprimitivedatafloat)
- [SetCustomPrimitiveDataVector2](ue_ue.CapsuleComponent.md#setcustomprimitivedatavector2)
- [SetCustomPrimitiveDataVector3](ue_ue.CapsuleComponent.md#setcustomprimitivedatavector3)
- [SetCustomPrimitiveDataVector4](ue_ue.CapsuleComponent.md#setcustomprimitivedatavector4)
- [SetEnableGravity](ue_ue.CapsuleComponent.md#setenablegravity)
- [SetExcludeFromLightAttachmentGroup](ue_ue.CapsuleComponent.md#setexcludefromlightattachmentgroup)
- [SetGenerateOverlapEvents](ue_ue.CapsuleComponent.md#setgenerateoverlapevents)
- [SetHiddenInGame](ue_ue.CapsuleComponent.md#sethiddeningame)
- [SetIsReplicated](ue_ue.CapsuleComponent.md#setisreplicated)
- [SetLightAttachmentsAsGroup](ue_ue.CapsuleComponent.md#setlightattachmentsasgroup)
- [SetLinearDamping](ue_ue.CapsuleComponent.md#setlineardamping)
- [SetMassOverrideInKg](ue_ue.CapsuleComponent.md#setmassoverrideinkg)
- [SetMassScale](ue_ue.CapsuleComponent.md#setmassscale)
- [SetMaterial](ue_ue.CapsuleComponent.md#setmaterial)
- [SetMaterialByName](ue_ue.CapsuleComponent.md#setmaterialbyname)
- [SetMobility](ue_ue.CapsuleComponent.md#setmobility)
- [SetNotifyRigidBodyCollision](ue_ue.CapsuleComponent.md#setnotifyrigidbodycollision)
- [SetOnlyOwnerSee](ue_ue.CapsuleComponent.md#setonlyownersee)
- [SetOwnerNoSee](ue_ue.CapsuleComponent.md#setownernosee)
- [SetPhysMaterialOverride](ue_ue.CapsuleComponent.md#setphysmaterialoverride)
- [SetPhysicsAngularVelocity](ue_ue.CapsuleComponent.md#setphysicsangularvelocity)
- [SetPhysicsAngularVelocityInDegrees](ue_ue.CapsuleComponent.md#setphysicsangularvelocityindegrees)
- [SetPhysicsAngularVelocityInRadians](ue_ue.CapsuleComponent.md#setphysicsangularvelocityinradians)
- [SetPhysicsLinearVelocity](ue_ue.CapsuleComponent.md#setphysicslinearvelocity)
- [SetPhysicsMaxAngularVelocity](ue_ue.CapsuleComponent.md#setphysicsmaxangularvelocity)
- [SetPhysicsMaxAngularVelocityInDegrees](ue_ue.CapsuleComponent.md#setphysicsmaxangularvelocityindegrees)
- [SetPhysicsMaxAngularVelocityInRadians](ue_ue.CapsuleComponent.md#setphysicsmaxangularvelocityinradians)
- [SetReceivesDecals](ue_ue.CapsuleComponent.md#setreceivesdecals)
- [SetRelativeScale3D](ue_ue.CapsuleComponent.md#setrelativescale3d)
- [SetRenderCustomDepth](ue_ue.CapsuleComponent.md#setrendercustomdepth)
- [SetRenderInMainPass](ue_ue.CapsuleComponent.md#setrenderinmainpass)
- [SetShouldUpdatePhysicsVolume](ue_ue.CapsuleComponent.md#setshouldupdatephysicsvolume)
- [SetSimulatePhysics](ue_ue.CapsuleComponent.md#setsimulatephysics)
- [SetSingleSampleShadowFromStationaryLights](ue_ue.CapsuleComponent.md#setsinglesampleshadowfromstationarylights)
- [SetTickGroup](ue_ue.CapsuleComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.CapsuleComponent.md#settickablewhenpaused)
- [SetTranslucentSortPriority](ue_ue.CapsuleComponent.md#settranslucentsortpriority)
- [SetUseCCD](ue_ue.CapsuleComponent.md#setuseccd)
- [SetVisibility](ue_ue.CapsuleComponent.md#setvisibility)
- [SetWalkableSlopeOverride](ue_ue.CapsuleComponent.md#setwalkableslopeoverride)
- [SetWorldScale3D](ue_ue.CapsuleComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.CapsuleComponent.md#setupattachment)
- [SnapTo](ue_ue.CapsuleComponent.md#snapto)
- [ToggleActive](ue_ue.CapsuleComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.CapsuleComponent.md#togglevisibility)
- [WakeAllRigidBodies](ue_ue.CapsuleComponent.md#wakeallrigidbodies)
- [WakeRigidBody](ue_ue.CapsuleComponent.md#wakerigidbody)
- [Find](ue_ue.CapsuleComponent.md#find)
- [Load](ue_ue.CapsuleComponent.md#load)
- [StaticClass](ue_ue.CapsuleComponent.md#staticclass)

## Constructors

### constructor

• **new CapsuleComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ShapeComponent](ue_ue.ShapeComponent.md).[constructor](ue_ue.ShapeComponent.md#constructor)

## Properties

### AlwaysLoadOnClient

• **AlwaysLoadOnClient**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[AlwaysLoadOnClient](ue_ue.ShapeComponent.md#alwaysloadonclient)

___

### AlwaysLoadOnServer

• **AlwaysLoadOnServer**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[AlwaysLoadOnServer](ue_ue.ShapeComponent.md#alwaysloadonserver)

___

### AreaClass

• **AreaClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[AreaClass](ue_ue.ShapeComponent.md#areaclass)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[AssetUserData](ue_ue.ShapeComponent.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[AttachChildren](ue_ue.ShapeComponent.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[AttachParent](ue_ue.ShapeComponent.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[AttachSocketName](ue_ue.ShapeComponent.md#attachsocketname)

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[BodyInstance](ue_ue.ShapeComponent.md#bodyinstance)

___

### BoundsScale

• **BoundsScale**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[BoundsScale](ue_ue.ShapeComponent.md#boundsscale)

___

### CachedMaxDrawDistance

• **CachedMaxDrawDistance**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CachedMaxDrawDistance](ue_ue.ShapeComponent.md#cachedmaxdrawdistance)

___

### CanBeCharacterBase

• **CanBeCharacterBase**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CanBeCharacterBase](ue_ue.ShapeComponent.md#canbecharacterbase)

___

### CanCharacterStepUpOn

• **CanCharacterStepUpOn**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CanCharacterStepUpOn](ue_ue.ShapeComponent.md#cancharacterstepupon)

___

### CapsuleHalfHeight

• **CapsuleHalfHeight**: `number`

___

### CapsuleHeight

• **CapsuleHeight**: `number`

___

### CapsuleRadius

• **CapsuleRadius**: `number`

___

### CastShadow

• **CastShadow**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CastShadow](ue_ue.ShapeComponent.md#castshadow)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ClientAttachedChildren](ue_ue.ShapeComponent.md#clientattachedchildren)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ComponentTags](ue_ue.ShapeComponent.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ComponentVelocity](ue_ue.ShapeComponent.md#componentvelocity)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CreationMethod](ue_ue.ShapeComponent.md#creationmethod)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CustomDepthStencilValue](ue_ue.ShapeComponent.md#customdepthstencilvalue)

___

### CustomDepthStencilWriteMask

• **CustomDepthStencilWriteMask**: [`ERendererStencilMask`](../enums/ue_ue.ERendererStencilMask.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CustomDepthStencilWriteMask](ue_ue.ShapeComponent.md#customdepthstencilwritemask)

___

### CustomPrimitiveData

• **CustomPrimitiveData**: [`CustomPrimitiveData`](ue_ue.CustomPrimitiveData.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CustomPrimitiveData](ue_ue.ShapeComponent.md#customprimitivedata)

___

### DepthPriorityGroup

• **DepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[DepthPriorityGroup](ue_ue.ShapeComponent.md#depthprioritygroup)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[DetailMode](ue_ue.ShapeComponent.md#detailmode)

___

### ExcludeForSpecificHLODLevels

• **ExcludeForSpecificHLODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ExcludeForSpecificHLODLevels](ue_ue.ShapeComponent.md#excludeforspecifichlodlevels)

___

### IndirectLightingCacheQuality

• **IndirectLightingCacheQuality**: [`EIndirectLightingCacheQuality`](../enums/ue_ue.EIndirectLightingCacheQuality.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[IndirectLightingCacheQuality](ue_ue.ShapeComponent.md#indirectlightingcachequality)

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[LDMaxDrawDistance](ue_ue.ShapeComponent.md#ldmaxdrawdistance)

___

### LODParentPrimitive

• **LODParentPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[LODParentPrimitive](ue_ue.ShapeComponent.md#lodparentprimitive)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[LightingChannels](ue_ue.ShapeComponent.md#lightingchannels)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[LightmapType](ue_ue.ShapeComponent.md#lightmaptype)

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[LpvBiasMultiplier](ue_ue.ShapeComponent.md#lpvbiasmultiplier)

___

### MinDrawDistance

• **MinDrawDistance**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[MinDrawDistance](ue_ue.ShapeComponent.md#mindrawdistance)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[Mobility](ue_ue.ShapeComponent.md#mobility)

___

### MoveIgnoreActors

• **MoveIgnoreActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[MoveIgnoreActors](ue_ue.ShapeComponent.md#moveignoreactors)

___

### MoveIgnoreComponents

• **MoveIgnoreComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[MoveIgnoreComponents](ue_ue.ShapeComponent.md#moveignorecomponents)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnBeginCursorOver](ue_ue.ShapeComponent.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnClicked](ue_ue.ShapeComponent.md#onclicked)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnComponentActivated](ue_ue.ShapeComponent.md#oncomponentactivated)

___

### OnComponentBeginOverlap

• **OnComponentBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`, `bFromSweep`: `boolean`, `SweepResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnComponentBeginOverlap](ue_ue.ShapeComponent.md#oncomponentbeginoverlap)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnComponentDeactivated](ue_ue.ShapeComponent.md#oncomponentdeactivated)

___

### OnComponentEndOverlap

• **OnComponentEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnComponentEndOverlap](ue_ue.ShapeComponent.md#oncomponentendoverlap)

___

### OnComponentHit

• **OnComponentHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`HitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnComponentHit](ue_ue.ShapeComponent.md#oncomponenthit)

___

### OnComponentSleep

• **OnComponentSleep**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SleepingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnComponentSleep](ue_ue.ShapeComponent.md#oncomponentsleep)

___

### OnComponentWake

• **OnComponentWake**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`WakingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnComponentWake](ue_ue.ShapeComponent.md#oncomponentwake)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnEndCursorOver](ue_ue.ShapeComponent.md#onendcursorover)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnInputTouchBegin](ue_ue.ShapeComponent.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnInputTouchEnd](ue_ue.ShapeComponent.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnInputTouchEnter](ue_ue.ShapeComponent.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnInputTouchLeave](ue_ue.ShapeComponent.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnReleased](ue_ue.ShapeComponent.md#onreleased)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[PhysicsVolume](ue_ue.ShapeComponent.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.ShapeComponent.md#physicsvolumechangeddelegate)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[PrimaryComponentTick](ue_ue.ShapeComponent.md#primarycomponenttick)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[RelativeLocation](ue_ue.ShapeComponent.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[RelativeRotation](ue_ue.ShapeComponent.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[RelativeScale3D](ue_ue.ShapeComponent.md#relativescale3d)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[RuntimeVirtualTextures](ue_ue.ShapeComponent.md#runtimevirtualtextures)

___

### ShapeBodySetup

• **ShapeBodySetup**: [`BodySetup`](ue_ue.BodySetup.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ShapeBodySetup](ue_ue.ShapeComponent.md#shapebodysetup)

___

### ShapeColor

• **ShapeColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ShapeColor](ue_ue.ShapeComponent.md#shapecolor)

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[TranslucencySortPriority](ue_ue.ShapeComponent.md#translucencysortpriority)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[UCSModifiedProperties](ue_ue.ShapeComponent.md#ucsmodifiedproperties)

___

### ViewOwnerDepthPriorityGroup

• **ViewOwnerDepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ViewOwnerDepthPriorityGroup](ue_ue.ShapeComponent.md#viewownerdepthprioritygroup)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[VirtualTextureCullMips](ue_ue.ShapeComponent.md#virtualtexturecullmips)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[VirtualTextureLodBias](ue_ue.ShapeComponent.md#virtualtexturelodbias)

___

### VirtualTextureMinCoverage

• **VirtualTextureMinCoverage**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[VirtualTextureMinCoverage](ue_ue.ShapeComponent.md#virtualtexturemincoverage)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[VirtualTextureRenderPassType](ue_ue.ShapeComponent.md#virtualtexturerenderpasstype)

___

### VisibilityId

• **VisibilityId**: `number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[VisibilityId](ue_ue.ShapeComponent.md#visibilityid)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[__tid_ActorComponent__](ue_ue.ShapeComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_CapsuleComponent\_\_

• **\_\_tid\_CapsuleComponent\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[__tid_Object__](ue_ue.ShapeComponent.md#__tid_object__)

___

### \_\_tid\_PrimitiveComponent\_\_

• **\_\_tid\_PrimitiveComponent\_\_**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[__tid_PrimitiveComponent__](ue_ue.ShapeComponent.md#__tid_primitivecomponent__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[__tid_SceneComponent__](ue_ue.ShapeComponent.md#__tid_scenecomponent__)

___

### \_\_tid\_ShapeComponent\_\_

• **\_\_tid\_ShapeComponent\_\_**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[__tid_ShapeComponent__](ue_ue.ShapeComponent.md#__tid_shapecomponent__)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bAbsoluteLocation](ue_ue.ShapeComponent.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bAbsoluteRotation](ue_ue.ShapeComponent.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bAbsoluteScale](ue_ue.ShapeComponent.md#babsolutescale)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bAffectDistanceFieldLighting](ue_ue.ShapeComponent.md#baffectdistancefieldlighting)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bAffectDynamicIndirectLighting](ue_ue.ShapeComponent.md#baffectdynamicindirectlighting)

___

### bAllowCullDistanceVolume

• **bAllowCullDistanceVolume**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bAllowCullDistanceVolume](ue_ue.ShapeComponent.md#ballowculldistancevolume)

___

### bAlwaysCreatePhysicsState

• **bAlwaysCreatePhysicsState**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bAlwaysCreatePhysicsState](ue_ue.ShapeComponent.md#balwayscreatephysicsstate)

___

### bApplyImpulseOnDamage

• **bApplyImpulseOnDamage**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bApplyImpulseOnDamage](ue_ue.ShapeComponent.md#bapplyimpulseondamage)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bAutoActivate](ue_ue.ShapeComponent.md#bautoactivate)

___

### bBatchImpostersAsInstances

• **bBatchImpostersAsInstances**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bBatchImpostersAsInstances](ue_ue.ShapeComponent.md#bbatchimpostersasinstances)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.ShapeComponent.md#bboundschangetriggersstreamingdatarebuild)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCanEverAffectNavigation](ue_ue.ShapeComponent.md#bcaneveraffectnavigation)

___

### bCastCinematicShadow

• **bCastCinematicShadow**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCastCinematicShadow](ue_ue.ShapeComponent.md#bcastcinematicshadow)

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCastDynamicShadow](ue_ue.ShapeComponent.md#bcastdynamicshadow)

___

### bCastFarShadow

• **bCastFarShadow**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCastFarShadow](ue_ue.ShapeComponent.md#bcastfarshadow)

___

### bCastHiddenShadow

• **bCastHiddenShadow**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCastHiddenShadow](ue_ue.ShapeComponent.md#bcasthiddenshadow)

___

### bCastInsetShadow

• **bCastInsetShadow**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCastInsetShadow](ue_ue.ShapeComponent.md#bcastinsetshadow)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCastShadowAsTwoSided](ue_ue.ShapeComponent.md#bcastshadowastwosided)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCastStaticShadow](ue_ue.ShapeComponent.md#bcaststaticshadow)

___

### bCastVolumetricTranslucentShadow

• **bCastVolumetricTranslucentShadow**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCastVolumetricTranslucentShadow](ue_ue.ShapeComponent.md#bcastvolumetrictranslucentshadow)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bComponentToWorldUpdated](ue_ue.ShapeComponent.md#bcomponenttoworldupdated)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bCreatedByConstructionScript](ue_ue.ShapeComponent.md#bcreatedbyconstructionscript)

___

### bDrawOnlyIfSelected

• **bDrawOnlyIfSelected**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bDrawOnlyIfSelected](ue_ue.ShapeComponent.md#bdrawonlyifselected)

___

### bDynamicObstacle

• **bDynamicObstacle**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bDynamicObstacle](ue_ue.ShapeComponent.md#bdynamicobstacle)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bEditableWhenInherited](ue_ue.ShapeComponent.md#beditablewheninherited)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bEnableAutoLODGeneration](ue_ue.ShapeComponent.md#benableautolodgeneration)

___

### bExcludeFromLightAttachmentGroup

• **bExcludeFromLightAttachmentGroup**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bExcludeFromLightAttachmentGroup](ue_ue.ShapeComponent.md#bexcludefromlightattachmentgroup)

___

### bForceMipStreaming

• **bForceMipStreaming**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bForceMipStreaming](ue_ue.ShapeComponent.md#bforcemipstreaming)

___

### bGenerateOverlapEvents

• **bGenerateOverlapEvents**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bGenerateOverlapEvents](ue_ue.ShapeComponent.md#bgenerateoverlapevents)

___

### bHasCustomNavigableGeometry

• **bHasCustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bHasCustomNavigableGeometry](ue_ue.ShapeComponent.md#bhascustomnavigablegeometry)

___

### bHasMotionBlurVelocityMeshes

• **bHasMotionBlurVelocityMeshes**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bHasMotionBlurVelocityMeshes](ue_ue.ShapeComponent.md#bhasmotionblurvelocitymeshes)

___

### bHasPerInstanceHitProxies

• **bHasPerInstanceHitProxies**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bHasPerInstanceHitProxies](ue_ue.ShapeComponent.md#bhasperinstancehitproxies)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bHiddenInGame](ue_ue.ShapeComponent.md#bhiddeningame)

___

### bIgnoreRadialForce

• **bIgnoreRadialForce**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bIgnoreRadialForce](ue_ue.ShapeComponent.md#bignoreradialforce)

___

### bIgnoreRadialImpulse

• **bIgnoreRadialImpulse**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bIgnoreRadialImpulse](ue_ue.ShapeComponent.md#bignoreradialimpulse)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bInstanceComponent](ue_ue.ShapeComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bIsActive](ue_ue.ShapeComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bIsEditorOnly](ue_ue.ShapeComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bIsVisualizationComponent](ue_ue.ShapeComponent.md#bisvisualizationcomponent)

___

### bLightAsIfStatic

• **bLightAsIfStatic**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bLightAsIfStatic](ue_ue.ShapeComponent.md#blightasifstatic)

___

### bLightAttachmentsAsGroup

• **bLightAttachmentsAsGroup**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bLightAttachmentsAsGroup](ue_ue.ShapeComponent.md#blightattachmentsasgroup)

___

### bMultiBodyOverlap

• **bMultiBodyOverlap**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bMultiBodyOverlap](ue_ue.ShapeComponent.md#bmultibodyoverlap)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bNetAddressable](ue_ue.ShapeComponent.md#bnetaddressable)

___

### bNeverDistanceCull

• **bNeverDistanceCull**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bNeverDistanceCull](ue_ue.ShapeComponent.md#bneverdistancecull)

___

### bOnlyOwnerSee

• **bOnlyOwnerSee**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bOnlyOwnerSee](ue_ue.ShapeComponent.md#bonlyownersee)

___

### bOwnerNoSee

• **bOwnerNoSee**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bOwnerNoSee](ue_ue.ShapeComponent.md#bownernosee)

___

### bReceiveMobileCSMShadows

• **bReceiveMobileCSMShadows**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bReceiveMobileCSMShadows](ue_ue.ShapeComponent.md#breceivemobilecsmshadows)

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bReceivesDecals](ue_ue.ShapeComponent.md#breceivesdecals)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bRenderCustomDepth](ue_ue.ShapeComponent.md#brendercustomdepth)

___

### bRenderInDepthPass

• **bRenderInDepthPass**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bRenderInDepthPass](ue_ue.ShapeComponent.md#brenderindepthpass)

___

### bRenderInMainPass

• **bRenderInMainPass**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bRenderInMainPass](ue_ue.ShapeComponent.md#brenderinmainpass)

___

### bReplicatePhysicsToAutonomousProxy

• **bReplicatePhysicsToAutonomousProxy**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bReplicatePhysicsToAutonomousProxy](ue_ue.ShapeComponent.md#breplicatephysicstoautonomousproxy)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bReplicates](ue_ue.ShapeComponent.md#breplicates)

___

### bReturnMaterialOnMove

• **bReturnMaterialOnMove**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bReturnMaterialOnMove](ue_ue.ShapeComponent.md#breturnmaterialonmove)

___

### bSelectable

• **bSelectable**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bSelectable](ue_ue.ShapeComponent.md#bselectable)

___

### bSelfShadowOnly

• **bSelfShadowOnly**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bSelfShadowOnly](ue_ue.ShapeComponent.md#bselfshadowonly)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bShouldBeAttached](ue_ue.ShapeComponent.md#bshouldbeattached)

___

### bShouldCollideWhenPlacing

• **bShouldCollideWhenPlacing**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bShouldCollideWhenPlacing](ue_ue.ShapeComponent.md#bshouldcollidewhenplacing)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.ShapeComponent.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.ShapeComponent.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.ShapeComponent.md#bshouldupdatephysicsvolume)

___

### bSingleSampleShadowFromStationaryLights

• **bSingleSampleShadowFromStationaryLights**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bSingleSampleShadowFromStationaryLights](ue_ue.ShapeComponent.md#bsinglesampleshadowfromstationarylights)

___

### bTraceComplexOnMove

• **bTraceComplexOnMove**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bTraceComplexOnMove](ue_ue.ShapeComponent.md#btracecomplexonmove)

___

### bTreatAsBackgroundForOcclusion

• **bTreatAsBackgroundForOcclusion**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bTreatAsBackgroundForOcclusion](ue_ue.ShapeComponent.md#btreatasbackgroundforocclusion)

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bUseAsOccluder](ue_ue.ShapeComponent.md#buseasoccluder)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bUseAttachParentBound](ue_ue.ShapeComponent.md#buseattachparentbound)

___

### bUseEditorCompositing

• **bUseEditorCompositing**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bUseEditorCompositing](ue_ue.ShapeComponent.md#buseeditorcompositing)

___

### bUseMaxLODAsImposter

• **bUseMaxLODAsImposter**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bUseMaxLODAsImposter](ue_ue.ShapeComponent.md#busemaxlodasimposter)

___

### bUseViewOwnerDepthPriorityGroup

• **bUseViewOwnerDepthPriorityGroup**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bUseViewOwnerDepthPriorityGroup](ue_ue.ShapeComponent.md#buseviewownerdepthprioritygroup)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bVisible](ue_ue.ShapeComponent.md#bvisible)

___

### bVisibleInRayTracing

• **bVisibleInRayTracing**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bVisibleInRayTracing](ue_ue.ShapeComponent.md#bvisibleinraytracing)

___

### bVisibleInReflectionCaptures

• **bVisibleInReflectionCaptures**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bVisibleInReflectionCaptures](ue_ue.ShapeComponent.md#bvisibleinreflectioncaptures)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[bVisualizeComponent](ue_ue.ShapeComponent.md#bvisualizecomponent)

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

___

### ClearMoveIgnoreActors

▸ **ClearMoveIgnoreActors**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ClearMoveIgnoreActors](ue_ue.ShapeComponent.md#clearmoveignoreactors)

___

### ClearMoveIgnoreComponents

▸ **ClearMoveIgnoreComponents**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ClearMoveIgnoreComponents](ue_ue.ShapeComponent.md#clearmoveignorecomponents)

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

___

### CopyArrayOfMoveIgnoreActors

▸ **CopyArrayOfMoveIgnoreActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CopyArrayOfMoveIgnoreActors](ue_ue.ShapeComponent.md#copyarrayofmoveignoreactors)

___

### CopyArrayOfMoveIgnoreComponents

▸ **CopyArrayOfMoveIgnoreComponents**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[CopyArrayOfMoveIgnoreComponents](ue_ue.ShapeComponent.md#copyarrayofmoveignorecomponents)

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

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[Deactivate](ue_ue.ShapeComponent.md#deactivate)

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

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetAllSocketNames](ue_ue.ShapeComponent.md#getallsocketnames)

___

### GetAngularDamping

▸ **GetAngularDamping**(): `number`

#### Returns

`number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetAngularDamping](ue_ue.ShapeComponent.md#getangulardamping)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetAttachParent](ue_ue.ShapeComponent.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetAttachSocketName](ue_ue.ShapeComponent.md#getattachsocketname)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetClass](ue_ue.ShapeComponent.md#getclass)

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

___

### GetCollisionEnabled

▸ **GetCollisionEnabled**(): [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Returns

[`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetCollisionEnabled](ue_ue.ShapeComponent.md#getcollisionenabled)

___

### GetCollisionObjectType

▸ **GetCollisionObjectType**(): [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Returns

[`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetCollisionObjectType](ue_ue.ShapeComponent.md#getcollisionobjecttype)

___

### GetCollisionProfileName

▸ **GetCollisionProfileName**(): `string`

#### Returns

`string`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetCollisionProfileName](ue_ue.ShapeComponent.md#getcollisionprofilename)

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

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetComponentTickInterval](ue_ue.ShapeComponent.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetComponentVelocity](ue_ue.ShapeComponent.md#getcomponentvelocity)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetForwardVector](ue_ue.ShapeComponent.md#getforwardvector)

___

### GetGenerateOverlapEvents

▸ **GetGenerateOverlapEvents**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetGenerateOverlapEvents](ue_ue.ShapeComponent.md#getgenerateoverlapevents)

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

___

### GetLinearDamping

▸ **GetLinearDamping**(): `number`

#### Returns

`number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetLinearDamping](ue_ue.ShapeComponent.md#getlineardamping)

___

### GetMass

▸ **GetMass**(): `number`

#### Returns

`number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetMass](ue_ue.ShapeComponent.md#getmass)

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

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetName](ue_ue.ShapeComponent.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetNumChildrenComponents](ue_ue.ShapeComponent.md#getnumchildrencomponents)

___

### GetNumMaterials

▸ **GetNumMaterials**(): `number`

#### Returns

`number`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetNumMaterials](ue_ue.ShapeComponent.md#getnummaterials)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetOuter](ue_ue.ShapeComponent.md#getouter)

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

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetOwner](ue_ue.ShapeComponent.md#getowner)

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

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetPhysicsVolume](ue_ue.ShapeComponent.md#getphysicsvolume)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetRelativeTransform](ue_ue.ShapeComponent.md#getrelativetransform)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetRightVector](ue_ue.ShapeComponent.md#getrightvector)

___

### GetScaledCapsuleHalfHeight

▸ **GetScaledCapsuleHalfHeight**(): `number`

#### Returns

`number`

___

### GetScaledCapsuleHalfHeight\_WithoutHemisphere

▸ **GetScaledCapsuleHalfHeight_WithoutHemisphere**(): `number`

#### Returns

`number`

___

### GetScaledCapsuleRadius

▸ **GetScaledCapsuleRadius**(): `number`

#### Returns

`number`

___

### GetScaledCapsuleSize

▸ **GetScaledCapsuleSize**(`OutRadius`, `OutHalfHeight`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutRadius` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `OutHalfHeight` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

___

### GetScaledCapsuleSize\_WithoutHemisphere

▸ **GetScaledCapsuleSize_WithoutHemisphere**(`OutRadius`, `OutHalfHeightWithoutHemisphere`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutRadius` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `OutHalfHeightWithoutHemisphere` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

___

### GetShapeScale

▸ **GetShapeScale**(): `number`

#### Returns

`number`

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.ShapeComponent.md#getshouldupdatephysicsvolume)

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

___

### GetUnscaledCapsuleHalfHeight

▸ **GetUnscaledCapsuleHalfHeight**(): `number`

#### Returns

`number`

___

### GetUnscaledCapsuleHalfHeight\_WithoutHemisphere

▸ **GetUnscaledCapsuleHalfHeight_WithoutHemisphere**(): `number`

#### Returns

`number`

___

### GetUnscaledCapsuleRadius

▸ **GetUnscaledCapsuleRadius**(): `number`

#### Returns

`number`

___

### GetUnscaledCapsuleSize

▸ **GetUnscaledCapsuleSize**(`OutRadius`, `OutHalfHeight`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutRadius` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `OutHalfHeight` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

___

### GetUnscaledCapsuleSize\_WithoutHemisphere

▸ **GetUnscaledCapsuleSize_WithoutHemisphere**(`OutRadius`, `OutHalfHeightWithoutHemisphere`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutRadius` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `OutHalfHeightWithoutHemisphere` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetUpVector](ue_ue.ShapeComponent.md#getupvector)

___

### GetWalkableSlopeOverride

▸ **GetWalkableSlopeOverride**(): [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Returns

[`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetWalkableSlopeOverride](ue_ue.ShapeComponent.md#getwalkableslopeoverride)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[GetWorld](ue_ue.ShapeComponent.md#getworld)

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

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[IsActive](ue_ue.ShapeComponent.md#isactive)

___

### IsAnyRigidBodyAwake

▸ **IsAnyRigidBodyAwake**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[IsAnyRigidBodyAwake](ue_ue.ShapeComponent.md#isanyrigidbodyawake)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[IsAnySimulatingPhysics](ue_ue.ShapeComponent.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[IsBeingDestroyed](ue_ue.ShapeComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[IsComponentTickEnabled](ue_ue.ShapeComponent.md#iscomponenttickenabled)

___

### IsGravityEnabled

▸ **IsGravityEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[IsGravityEnabled](ue_ue.ShapeComponent.md#isgravityenabled)

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

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[IsVisible](ue_ue.ShapeComponent.md#isvisible)

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

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_GetComponentLocation](ue_ue.ShapeComponent.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_GetComponentRotation](ue_ue.ShapeComponent.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_GetComponentScale](ue_ue.ShapeComponent.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_GetComponentToWorld](ue_ue.ShapeComponent.md#k2_getcomponenttoworld)

___

### K2\_IsCollisionEnabled

▸ **K2_IsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_IsCollisionEnabled](ue_ue.ShapeComponent.md#k2_iscollisionenabled)

___

### K2\_IsPhysicsCollisionEnabled

▸ **K2_IsPhysicsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_IsPhysicsCollisionEnabled](ue_ue.ShapeComponent.md#k2_isphysicscollisionenabled)

___

### K2\_IsQueryCollisionEnabled

▸ **K2_IsQueryCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[K2_IsQueryCollisionEnabled](ue_ue.ShapeComponent.md#k2_isquerycollisionenabled)

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

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnRep_AttachChildren](ue_ue.ShapeComponent.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnRep_AttachParent](ue_ue.ShapeComponent.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnRep_AttachSocketName](ue_ue.ShapeComponent.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnRep_IsActive](ue_ue.ShapeComponent.md#onrep_isactive)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[OnRep_Transform](ue_ue.ShapeComponent.md#onrep_transform)

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

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ReceiveBeginPlay](ue_ue.ShapeComponent.md#receivebeginplay)

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

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[RegisterComponent](ue_ue.ShapeComponent.md#registercomponent)

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

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ResetRelativeTransform](ue_ue.ShapeComponent.md#resetrelativetransform)

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

___

### SetCapsuleHalfHeight

▸ **SetCapsuleHalfHeight**(`HalfHeight`, `bUpdateOverlaps?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `HalfHeight` | `number` |
| `bUpdateOverlaps?` | `boolean` |

#### Returns

`void`

___

### SetCapsuleRadius

▸ **SetCapsuleRadius**(`Radius`, `bUpdateOverlaps?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Radius` | `number` |
| `bUpdateOverlaps?` | `boolean` |

#### Returns

`void`

___

### SetCapsuleSize

▸ **SetCapsuleSize**(`InRadius`, `InHalfHeight`, `bUpdateOverlaps?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRadius` | `number` |
| `InHalfHeight` | `number` |
| `bUpdateOverlaps?` | `boolean` |

#### Returns

`void`

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

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[ToggleActive](ue_ue.ShapeComponent.md#toggleactive)

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

___

### WakeAllRigidBodies

▸ **WakeAllRigidBodies**(): `void`

#### Returns

`void`

#### Inherited from

[ShapeComponent](ue_ue.ShapeComponent.md).[WakeAllRigidBodies](ue_ue.ShapeComponent.md#wakeallrigidbodies)

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

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CapsuleComponent`](ue_ue.CapsuleComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CapsuleComponent`](ue_ue.CapsuleComponent.md)

#### Overrides

[ShapeComponent](ue_ue.ShapeComponent.md).[Find](ue_ue.ShapeComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`CapsuleComponent`](ue_ue.CapsuleComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CapsuleComponent`](ue_ue.CapsuleComponent.md)

#### Overrides

[ShapeComponent](ue_ue.ShapeComponent.md).[Load](ue_ue.ShapeComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ShapeComponent](ue_ue.ShapeComponent.md).[StaticClass](ue_ue.ShapeComponent.md#staticclass)
