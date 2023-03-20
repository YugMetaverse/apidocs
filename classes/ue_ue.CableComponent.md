[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CableComponent

# Class: CableComponent

[ue/ue](../modules/ue_ue.md).CableComponent

## Hierarchy

- [`MeshComponent`](ue_ue.MeshComponent.md)

  ↳ **`CableComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.CableComponent.md#constructor)

### Properties

- [AlwaysLoadOnClient](ue_ue.CableComponent.md#alwaysloadonclient)
- [AlwaysLoadOnServer](ue_ue.CableComponent.md#alwaysloadonserver)
- [AssetUserData](ue_ue.CableComponent.md#assetuserdata)
- [AttachChildren](ue_ue.CableComponent.md#attachchildren)
- [AttachEndTo](ue_ue.CableComponent.md#attachendto)
- [AttachEndToSocketName](ue_ue.CableComponent.md#attachendtosocketname)
- [AttachParent](ue_ue.CableComponent.md#attachparent)
- [AttachSocketName](ue_ue.CableComponent.md#attachsocketname)
- [BodyInstance](ue_ue.CableComponent.md#bodyinstance)
- [BoundsScale](ue_ue.CableComponent.md#boundsscale)
- [CableForce](ue_ue.CableComponent.md#cableforce)
- [CableGravityScale](ue_ue.CableComponent.md#cablegravityscale)
- [CableLength](ue_ue.CableComponent.md#cablelength)
- [CableWidth](ue_ue.CableComponent.md#cablewidth)
- [CachedMaxDrawDistance](ue_ue.CableComponent.md#cachedmaxdrawdistance)
- [CanBeCharacterBase](ue_ue.CableComponent.md#canbecharacterbase)
- [CanCharacterStepUpOn](ue_ue.CableComponent.md#cancharacterstepupon)
- [CastShadow](ue_ue.CableComponent.md#castshadow)
- [ClientAttachedChildren](ue_ue.CableComponent.md#clientattachedchildren)
- [CollisionFriction](ue_ue.CableComponent.md#collisionfriction)
- [ComponentTags](ue_ue.CableComponent.md#componenttags)
- [ComponentVelocity](ue_ue.CableComponent.md#componentvelocity)
- [CreationMethod](ue_ue.CableComponent.md#creationmethod)
- [CustomDepthStencilValue](ue_ue.CableComponent.md#customdepthstencilvalue)
- [CustomDepthStencilWriteMask](ue_ue.CableComponent.md#customdepthstencilwritemask)
- [CustomPrimitiveData](ue_ue.CableComponent.md#customprimitivedata)
- [DepthPriorityGroup](ue_ue.CableComponent.md#depthprioritygroup)
- [DetailMode](ue_ue.CableComponent.md#detailmode)
- [EndLocation](ue_ue.CableComponent.md#endlocation)
- [ExcludeForSpecificHLODLevels](ue_ue.CableComponent.md#excludeforspecifichlodlevels)
- [IndirectLightingCacheQuality](ue_ue.CableComponent.md#indirectlightingcachequality)
- [LDMaxDrawDistance](ue_ue.CableComponent.md#ldmaxdrawdistance)
- [LODParentPrimitive](ue_ue.CableComponent.md#lodparentprimitive)
- [LightingChannels](ue_ue.CableComponent.md#lightingchannels)
- [LightmapType](ue_ue.CableComponent.md#lightmaptype)
- [LpvBiasMultiplier](ue_ue.CableComponent.md#lpvbiasmultiplier)
- [MinDrawDistance](ue_ue.CableComponent.md#mindrawdistance)
- [Mobility](ue_ue.CableComponent.md#mobility)
- [MoveIgnoreActors](ue_ue.CableComponent.md#moveignoreactors)
- [MoveIgnoreComponents](ue_ue.CableComponent.md#moveignorecomponents)
- [NumSegments](ue_ue.CableComponent.md#numsegments)
- [NumSides](ue_ue.CableComponent.md#numsides)
- [OnBeginCursorOver](ue_ue.CableComponent.md#onbegincursorover)
- [OnClicked](ue_ue.CableComponent.md#onclicked)
- [OnComponentActivated](ue_ue.CableComponent.md#oncomponentactivated)
- [OnComponentBeginOverlap](ue_ue.CableComponent.md#oncomponentbeginoverlap)
- [OnComponentDeactivated](ue_ue.CableComponent.md#oncomponentdeactivated)
- [OnComponentEndOverlap](ue_ue.CableComponent.md#oncomponentendoverlap)
- [OnComponentHit](ue_ue.CableComponent.md#oncomponenthit)
- [OnComponentSleep](ue_ue.CableComponent.md#oncomponentsleep)
- [OnComponentWake](ue_ue.CableComponent.md#oncomponentwake)
- [OnEndCursorOver](ue_ue.CableComponent.md#onendcursorover)
- [OnInputTouchBegin](ue_ue.CableComponent.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.CableComponent.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.CableComponent.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.CableComponent.md#oninputtouchleave)
- [OnReleased](ue_ue.CableComponent.md#onreleased)
- [OverrideMaterials](ue_ue.CableComponent.md#overridematerials)
- [PhysicsVolume](ue_ue.CableComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.CableComponent.md#physicsvolumechangeddelegate)
- [PrimaryComponentTick](ue_ue.CableComponent.md#primarycomponenttick)
- [RelativeLocation](ue_ue.CableComponent.md#relativelocation)
- [RelativeRotation](ue_ue.CableComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.CableComponent.md#relativescale3d)
- [RuntimeVirtualTextures](ue_ue.CableComponent.md#runtimevirtualtextures)
- [SolverIterations](ue_ue.CableComponent.md#solveriterations)
- [SubstepTime](ue_ue.CableComponent.md#substeptime)
- [TileMaterial](ue_ue.CableComponent.md#tilematerial)
- [TranslucencySortPriority](ue_ue.CableComponent.md#translucencysortpriority)
- [UCSModifiedProperties](ue_ue.CableComponent.md#ucsmodifiedproperties)
- [ViewOwnerDepthPriorityGroup](ue_ue.CableComponent.md#viewownerdepthprioritygroup)
- [VirtualTextureCullMips](ue_ue.CableComponent.md#virtualtexturecullmips)
- [VirtualTextureLodBias](ue_ue.CableComponent.md#virtualtexturelodbias)
- [VirtualTextureMinCoverage](ue_ue.CableComponent.md#virtualtexturemincoverage)
- [VirtualTextureRenderPassType](ue_ue.CableComponent.md#virtualtexturerenderpasstype)
- [VisibilityId](ue_ue.CableComponent.md#visibilityid)
- [\_\_tid\_ActorComponent\_\_](ue_ue.CableComponent.md#__tid_actorcomponent__)
- [\_\_tid\_CableComponent\_\_](ue_ue.CableComponent.md#__tid_cablecomponent__)
- [\_\_tid\_MeshComponent\_\_](ue_ue.CableComponent.md#__tid_meshcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.CableComponent.md#__tid_object__)
- [\_\_tid\_PrimitiveComponent\_\_](ue_ue.CableComponent.md#__tid_primitivecomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.CableComponent.md#__tid_scenecomponent__)
- [bAbsoluteLocation](ue_ue.CableComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.CableComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.CableComponent.md#babsolutescale)
- [bAffectDistanceFieldLighting](ue_ue.CableComponent.md#baffectdistancefieldlighting)
- [bAffectDynamicIndirectLighting](ue_ue.CableComponent.md#baffectdynamicindirectlighting)
- [bAllowCullDistanceVolume](ue_ue.CableComponent.md#ballowculldistancevolume)
- [bAlwaysCreatePhysicsState](ue_ue.CableComponent.md#balwayscreatephysicsstate)
- [bApplyImpulseOnDamage](ue_ue.CableComponent.md#bapplyimpulseondamage)
- [bAttachEnd](ue_ue.CableComponent.md#battachend)
- [bAttachStart](ue_ue.CableComponent.md#battachstart)
- [bAutoActivate](ue_ue.CableComponent.md#bautoactivate)
- [bBatchImpostersAsInstances](ue_ue.CableComponent.md#bbatchimpostersasinstances)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.CableComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.CableComponent.md#bcaneveraffectnavigation)
- [bCastCinematicShadow](ue_ue.CableComponent.md#bcastcinematicshadow)
- [bCastDynamicShadow](ue_ue.CableComponent.md#bcastdynamicshadow)
- [bCastFarShadow](ue_ue.CableComponent.md#bcastfarshadow)
- [bCastHiddenShadow](ue_ue.CableComponent.md#bcasthiddenshadow)
- [bCastInsetShadow](ue_ue.CableComponent.md#bcastinsetshadow)
- [bCastShadowAsTwoSided](ue_ue.CableComponent.md#bcastshadowastwosided)
- [bCastStaticShadow](ue_ue.CableComponent.md#bcaststaticshadow)
- [bCastVolumetricTranslucentShadow](ue_ue.CableComponent.md#bcastvolumetrictranslucentshadow)
- [bComponentToWorldUpdated](ue_ue.CableComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.CableComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.CableComponent.md#beditablewheninherited)
- [bEnableAutoLODGeneration](ue_ue.CableComponent.md#benableautolodgeneration)
- [bEnableCollision](ue_ue.CableComponent.md#benablecollision)
- [bEnableMaterialParameterCaching](ue_ue.CableComponent.md#benablematerialparametercaching)
- [bEnableStiffness](ue_ue.CableComponent.md#benablestiffness)
- [bExcludeFromLightAttachmentGroup](ue_ue.CableComponent.md#bexcludefromlightattachmentgroup)
- [bForceMipStreaming](ue_ue.CableComponent.md#bforcemipstreaming)
- [bGenerateOverlapEvents](ue_ue.CableComponent.md#bgenerateoverlapevents)
- [bHasCustomNavigableGeometry](ue_ue.CableComponent.md#bhascustomnavigablegeometry)
- [bHasMotionBlurVelocityMeshes](ue_ue.CableComponent.md#bhasmotionblurvelocitymeshes)
- [bHasPerInstanceHitProxies](ue_ue.CableComponent.md#bhasperinstancehitproxies)
- [bHiddenInGame](ue_ue.CableComponent.md#bhiddeningame)
- [bIgnoreRadialForce](ue_ue.CableComponent.md#bignoreradialforce)
- [bIgnoreRadialImpulse](ue_ue.CableComponent.md#bignoreradialimpulse)
- [bInstanceComponent](ue_ue.CableComponent.md#binstancecomponent)
- [bIsActive](ue_ue.CableComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.CableComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.CableComponent.md#bisvisualizationcomponent)
- [bLightAsIfStatic](ue_ue.CableComponent.md#blightasifstatic)
- [bLightAttachmentsAsGroup](ue_ue.CableComponent.md#blightattachmentsasgroup)
- [bMultiBodyOverlap](ue_ue.CableComponent.md#bmultibodyoverlap)
- [bNetAddressable](ue_ue.CableComponent.md#bnetaddressable)
- [bNeverDistanceCull](ue_ue.CableComponent.md#bneverdistancecull)
- [bOnlyOwnerSee](ue_ue.CableComponent.md#bonlyownersee)
- [bOwnerNoSee](ue_ue.CableComponent.md#bownernosee)
- [bReceiveMobileCSMShadows](ue_ue.CableComponent.md#breceivemobilecsmshadows)
- [bReceivesDecals](ue_ue.CableComponent.md#breceivesdecals)
- [bRenderCustomDepth](ue_ue.CableComponent.md#brendercustomdepth)
- [bRenderInDepthPass](ue_ue.CableComponent.md#brenderindepthpass)
- [bRenderInMainPass](ue_ue.CableComponent.md#brenderinmainpass)
- [bReplicatePhysicsToAutonomousProxy](ue_ue.CableComponent.md#breplicatephysicstoautonomousproxy)
- [bReplicates](ue_ue.CableComponent.md#breplicates)
- [bReturnMaterialOnMove](ue_ue.CableComponent.md#breturnmaterialonmove)
- [bSelectable](ue_ue.CableComponent.md#bselectable)
- [bSelfShadowOnly](ue_ue.CableComponent.md#bselfshadowonly)
- [bShouldBeAttached](ue_ue.CableComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.CableComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.CableComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.CableComponent.md#bshouldupdatephysicsvolume)
- [bSingleSampleShadowFromStationaryLights](ue_ue.CableComponent.md#bsinglesampleshadowfromstationarylights)
- [bTraceComplexOnMove](ue_ue.CableComponent.md#btracecomplexonmove)
- [bTreatAsBackgroundForOcclusion](ue_ue.CableComponent.md#btreatasbackgroundforocclusion)
- [bUseAsOccluder](ue_ue.CableComponent.md#buseasoccluder)
- [bUseAttachParentBound](ue_ue.CableComponent.md#buseattachparentbound)
- [bUseEditorCompositing](ue_ue.CableComponent.md#buseeditorcompositing)
- [bUseMaxLODAsImposter](ue_ue.CableComponent.md#busemaxlodasimposter)
- [bUseViewOwnerDepthPriorityGroup](ue_ue.CableComponent.md#buseviewownerdepthprioritygroup)
- [bVisible](ue_ue.CableComponent.md#bvisible)
- [bVisibleInRayTracing](ue_ue.CableComponent.md#bvisibleinraytracing)
- [bVisibleInReflectionCaptures](ue_ue.CableComponent.md#bvisibleinreflectioncaptures)
- [bVisualizeComponent](ue_ue.CableComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.CableComponent.md#activate)
- [AddAngularImpulse](ue_ue.CableComponent.md#addangularimpulse)
- [AddAngularImpulseInDegrees](ue_ue.CableComponent.md#addangularimpulseindegrees)
- [AddAngularImpulseInRadians](ue_ue.CableComponent.md#addangularimpulseinradians)
- [AddForce](ue_ue.CableComponent.md#addforce)
- [AddForceAtLocation](ue_ue.CableComponent.md#addforceatlocation)
- [AddForceAtLocationLocal](ue_ue.CableComponent.md#addforceatlocationlocal)
- [AddImpulse](ue_ue.CableComponent.md#addimpulse)
- [AddImpulseAtLocation](ue_ue.CableComponent.md#addimpulseatlocation)
- [AddRadialForce](ue_ue.CableComponent.md#addradialforce)
- [AddRadialImpulse](ue_ue.CableComponent.md#addradialimpulse)
- [AddTickPrerequisiteActor](ue_ue.CableComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.CableComponent.md#addtickprerequisitecomponent)
- [AddTorque](ue_ue.CableComponent.md#addtorque)
- [AddTorqueInDegrees](ue_ue.CableComponent.md#addtorqueindegrees)
- [AddTorqueInRadians](ue_ue.CableComponent.md#addtorqueinradians)
- [CanCharacterStepUp](ue_ue.CableComponent.md#cancharacterstepup)
- [ClearMoveIgnoreActors](ue_ue.CableComponent.md#clearmoveignoreactors)
- [ClearMoveIgnoreComponents](ue_ue.CableComponent.md#clearmoveignorecomponents)
- [ComponentHasTag](ue_ue.CableComponent.md#componenthastag)
- [CopyArrayOfMoveIgnoreActors](ue_ue.CableComponent.md#copyarrayofmoveignoreactors)
- [CopyArrayOfMoveIgnoreComponents](ue_ue.CableComponent.md#copyarrayofmoveignorecomponents)
- [CreateAndSetMaterialInstanceDynamic](ue_ue.CableComponent.md#createandsetmaterialinstancedynamic)
- [CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.CableComponent.md#createandsetmaterialinstancedynamicfrommaterial)
- [CreateDefaultSubobject](ue_ue.CableComponent.md#createdefaultsubobject)
- [CreateDynamicMaterialInstance](ue_ue.CableComponent.md#createdynamicmaterialinstance)
- [Deactivate](ue_ue.CableComponent.md#deactivate)
- [DetachFromParent](ue_ue.CableComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.CableComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.CableComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.CableComponent.md#getallsocketnames)
- [GetAngularDamping](ue_ue.CableComponent.md#getangulardamping)
- [GetAttachParent](ue_ue.CableComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.CableComponent.md#getattachsocketname)
- [GetAttachedActor](ue_ue.CableComponent.md#getattachedactor)
- [GetAttachedComponent](ue_ue.CableComponent.md#getattachedcomponent)
- [GetCableParticleLocations](ue_ue.CableComponent.md#getcableparticlelocations)
- [GetCenterOfMass](ue_ue.CableComponent.md#getcenterofmass)
- [GetChildComponent](ue_ue.CableComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.CableComponent.md#getchildrencomponents)
- [GetClass](ue_ue.CableComponent.md#getclass)
- [GetClosestPointOnCollision](ue_ue.CableComponent.md#getclosestpointoncollision)
- [GetCollisionEnabled](ue_ue.CableComponent.md#getcollisionenabled)
- [GetCollisionObjectType](ue_ue.CableComponent.md#getcollisionobjecttype)
- [GetCollisionProfileName](ue_ue.CableComponent.md#getcollisionprofilename)
- [GetCollisionResponseToChannel](ue_ue.CableComponent.md#getcollisionresponsetochannel)
- [GetComponentTickInterval](ue_ue.CableComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.CableComponent.md#getcomponentvelocity)
- [GetForwardVector](ue_ue.CableComponent.md#getforwardvector)
- [GetGenerateOverlapEvents](ue_ue.CableComponent.md#getgenerateoverlapevents)
- [GetInertiaTensor](ue_ue.CableComponent.md#getinertiatensor)
- [GetLinearDamping](ue_ue.CableComponent.md#getlineardamping)
- [GetMass](ue_ue.CableComponent.md#getmass)
- [GetMassScale](ue_ue.CableComponent.md#getmassscale)
- [GetMaterial](ue_ue.CableComponent.md#getmaterial)
- [GetMaterialFromCollisionFaceIndex](ue_ue.CableComponent.md#getmaterialfromcollisionfaceindex)
- [GetMaterialIndex](ue_ue.CableComponent.md#getmaterialindex)
- [GetMaterialSlotNames](ue_ue.CableComponent.md#getmaterialslotnames)
- [GetMaterials](ue_ue.CableComponent.md#getmaterials)
- [GetName](ue_ue.CableComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.CableComponent.md#getnumchildrencomponents)
- [GetNumMaterials](ue_ue.CableComponent.md#getnummaterials)
- [GetOuter](ue_ue.CableComponent.md#getouter)
- [GetOverlappingActors](ue_ue.CableComponent.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.CableComponent.md#getoverlappingcomponents)
- [GetOwner](ue_ue.CableComponent.md#getowner)
- [GetParentComponents](ue_ue.CableComponent.md#getparentcomponents)
- [GetPhysicsAngularVelocity](ue_ue.CableComponent.md#getphysicsangularvelocity)
- [GetPhysicsAngularVelocityInDegrees](ue_ue.CableComponent.md#getphysicsangularvelocityindegrees)
- [GetPhysicsAngularVelocityInRadians](ue_ue.CableComponent.md#getphysicsangularvelocityinradians)
- [GetPhysicsLinearVelocity](ue_ue.CableComponent.md#getphysicslinearvelocity)
- [GetPhysicsLinearVelocityAtPoint](ue_ue.CableComponent.md#getphysicslinearvelocityatpoint)
- [GetPhysicsVolume](ue_ue.CableComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.CableComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.CableComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.CableComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.CableComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.CableComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.CableComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.CableComponent.md#getsockettransform)
- [GetUpVector](ue_ue.CableComponent.md#getupvector)
- [GetWalkableSlopeOverride](ue_ue.CableComponent.md#getwalkableslopeoverride)
- [GetWorld](ue_ue.CableComponent.md#getworld)
- [IgnoreActorWhenMoving](ue_ue.CableComponent.md#ignoreactorwhenmoving)
- [IgnoreComponentWhenMoving](ue_ue.CableComponent.md#ignorecomponentwhenmoving)
- [IsActive](ue_ue.CableComponent.md#isactive)
- [IsAnyRigidBodyAwake](ue_ue.CableComponent.md#isanyrigidbodyawake)
- [IsAnySimulatingPhysics](ue_ue.CableComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.CableComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.CableComponent.md#iscomponenttickenabled)
- [IsGravityEnabled](ue_ue.CableComponent.md#isgravityenabled)
- [IsMaterialSlotNameValid](ue_ue.CableComponent.md#ismaterialslotnamevalid)
- [IsOverlappingActor](ue_ue.CableComponent.md#isoverlappingactor)
- [IsOverlappingComponent](ue_ue.CableComponent.md#isoverlappingcomponent)
- [IsSimulatingPhysics](ue_ue.CableComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.CableComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.CableComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.CableComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.CableComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.CableComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.CableComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.CableComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.CableComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.CableComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.CableComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.CableComponent.md#k2_attachtocomponent)
- [K2\_BoxOverlapComponent](ue_ue.CableComponent.md#k2_boxoverlapcomponent)
- [K2\_DestroyComponent](ue_ue.CableComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.CableComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.CableComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.CableComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.CableComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.CableComponent.md#k2_getcomponenttoworld)
- [K2\_IsCollisionEnabled](ue_ue.CableComponent.md#k2_iscollisionenabled)
- [K2\_IsPhysicsCollisionEnabled](ue_ue.CableComponent.md#k2_isphysicscollisionenabled)
- [K2\_IsQueryCollisionEnabled](ue_ue.CableComponent.md#k2_isquerycollisionenabled)
- [K2\_LineTraceComponent](ue_ue.CableComponent.md#k2_linetracecomponent)
- [K2\_SetRelativeLocation](ue_ue.CableComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.CableComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.CableComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.CableComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.CableComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.CableComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.CableComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.CableComponent.md#k2_setworldtransform)
- [K2\_SphereOverlapComponent](ue_ue.CableComponent.md#k2_sphereoverlapcomponent)
- [K2\_SphereTraceComponent](ue_ue.CableComponent.md#k2_spheretracecomponent)
- [OnRep\_AttachChildren](ue_ue.CableComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.CableComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.CableComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.CableComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.CableComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.CableComponent.md#onrep_visibility)
- [PrestreamTextures](ue_ue.CableComponent.md#prestreamtextures)
- [PutRigidBodyToSleep](ue_ue.CableComponent.md#putrigidbodytosleep)
- [ReceiveBeginPlay](ue_ue.CableComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.CableComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.CableComponent.md#receivetick)
- [RegisterComponent](ue_ue.CableComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.CableComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.CableComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.CableComponent.md#resetrelativetransform)
- [ScaleByMomentOfInertia](ue_ue.CableComponent.md#scalebymomentofinertia)
- [SetAbsolute](ue_ue.CableComponent.md#setabsolute)
- [SetActive](ue_ue.CableComponent.md#setactive)
- [SetAllMassScale](ue_ue.CableComponent.md#setallmassscale)
- [SetAllPhysicsAngularVelocityInDegrees](ue_ue.CableComponent.md#setallphysicsangularvelocityindegrees)
- [SetAllPhysicsAngularVelocityInRadians](ue_ue.CableComponent.md#setallphysicsangularvelocityinradians)
- [SetAllPhysicsLinearVelocity](ue_ue.CableComponent.md#setallphysicslinearvelocity)
- [SetAllUseCCD](ue_ue.CableComponent.md#setalluseccd)
- [SetAngularDamping](ue_ue.CableComponent.md#setangulardamping)
- [SetAttachEndTo](ue_ue.CableComponent.md#setattachendto)
- [SetAttachEndToComponent](ue_ue.CableComponent.md#setattachendtocomponent)
- [SetAutoActivate](ue_ue.CableComponent.md#setautoactivate)
- [SetBoundsScale](ue_ue.CableComponent.md#setboundsscale)
- [SetCastInsetShadow](ue_ue.CableComponent.md#setcastinsetshadow)
- [SetCastShadow](ue_ue.CableComponent.md#setcastshadow)
- [SetCenterOfMass](ue_ue.CableComponent.md#setcenterofmass)
- [SetCollisionEnabled](ue_ue.CableComponent.md#setcollisionenabled)
- [SetCollisionObjectType](ue_ue.CableComponent.md#setcollisionobjecttype)
- [SetCollisionProfileName](ue_ue.CableComponent.md#setcollisionprofilename)
- [SetCollisionResponseToAllChannels](ue_ue.CableComponent.md#setcollisionresponsetoallchannels)
- [SetCollisionResponseToChannel](ue_ue.CableComponent.md#setcollisionresponsetochannel)
- [SetComponentTickEnabled](ue_ue.CableComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.CableComponent.md#setcomponenttickinterval)
- [SetConstraintMode](ue_ue.CableComponent.md#setconstraintmode)
- [SetCullDistance](ue_ue.CableComponent.md#setculldistance)
- [SetCustomDepthStencilValue](ue_ue.CableComponent.md#setcustomdepthstencilvalue)
- [SetCustomDepthStencilWriteMask](ue_ue.CableComponent.md#setcustomdepthstencilwritemask)
- [SetCustomPrimitiveDataFloat](ue_ue.CableComponent.md#setcustomprimitivedatafloat)
- [SetCustomPrimitiveDataVector2](ue_ue.CableComponent.md#setcustomprimitivedatavector2)
- [SetCustomPrimitiveDataVector3](ue_ue.CableComponent.md#setcustomprimitivedatavector3)
- [SetCustomPrimitiveDataVector4](ue_ue.CableComponent.md#setcustomprimitivedatavector4)
- [SetEnableGravity](ue_ue.CableComponent.md#setenablegravity)
- [SetExcludeFromLightAttachmentGroup](ue_ue.CableComponent.md#setexcludefromlightattachmentgroup)
- [SetGenerateOverlapEvents](ue_ue.CableComponent.md#setgenerateoverlapevents)
- [SetHiddenInGame](ue_ue.CableComponent.md#sethiddeningame)
- [SetIsReplicated](ue_ue.CableComponent.md#setisreplicated)
- [SetLightAttachmentsAsGroup](ue_ue.CableComponent.md#setlightattachmentsasgroup)
- [SetLinearDamping](ue_ue.CableComponent.md#setlineardamping)
- [SetMassOverrideInKg](ue_ue.CableComponent.md#setmassoverrideinkg)
- [SetMassScale](ue_ue.CableComponent.md#setmassscale)
- [SetMaterial](ue_ue.CableComponent.md#setmaterial)
- [SetMaterialByName](ue_ue.CableComponent.md#setmaterialbyname)
- [SetMobility](ue_ue.CableComponent.md#setmobility)
- [SetNotifyRigidBodyCollision](ue_ue.CableComponent.md#setnotifyrigidbodycollision)
- [SetOnlyOwnerSee](ue_ue.CableComponent.md#setonlyownersee)
- [SetOwnerNoSee](ue_ue.CableComponent.md#setownernosee)
- [SetPhysMaterialOverride](ue_ue.CableComponent.md#setphysmaterialoverride)
- [SetPhysicsAngularVelocity](ue_ue.CableComponent.md#setphysicsangularvelocity)
- [SetPhysicsAngularVelocityInDegrees](ue_ue.CableComponent.md#setphysicsangularvelocityindegrees)
- [SetPhysicsAngularVelocityInRadians](ue_ue.CableComponent.md#setphysicsangularvelocityinradians)
- [SetPhysicsLinearVelocity](ue_ue.CableComponent.md#setphysicslinearvelocity)
- [SetPhysicsMaxAngularVelocity](ue_ue.CableComponent.md#setphysicsmaxangularvelocity)
- [SetPhysicsMaxAngularVelocityInDegrees](ue_ue.CableComponent.md#setphysicsmaxangularvelocityindegrees)
- [SetPhysicsMaxAngularVelocityInRadians](ue_ue.CableComponent.md#setphysicsmaxangularvelocityinradians)
- [SetReceivesDecals](ue_ue.CableComponent.md#setreceivesdecals)
- [SetRelativeScale3D](ue_ue.CableComponent.md#setrelativescale3d)
- [SetRenderCustomDepth](ue_ue.CableComponent.md#setrendercustomdepth)
- [SetRenderInMainPass](ue_ue.CableComponent.md#setrenderinmainpass)
- [SetScalarParameterValueOnMaterials](ue_ue.CableComponent.md#setscalarparametervalueonmaterials)
- [SetShouldUpdatePhysicsVolume](ue_ue.CableComponent.md#setshouldupdatephysicsvolume)
- [SetSimulatePhysics](ue_ue.CableComponent.md#setsimulatephysics)
- [SetSingleSampleShadowFromStationaryLights](ue_ue.CableComponent.md#setsinglesampleshadowfromstationarylights)
- [SetTickGroup](ue_ue.CableComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.CableComponent.md#settickablewhenpaused)
- [SetTranslucentSortPriority](ue_ue.CableComponent.md#settranslucentsortpriority)
- [SetUseCCD](ue_ue.CableComponent.md#setuseccd)
- [SetVectorParameterValueOnMaterials](ue_ue.CableComponent.md#setvectorparametervalueonmaterials)
- [SetVisibility](ue_ue.CableComponent.md#setvisibility)
- [SetWalkableSlopeOverride](ue_ue.CableComponent.md#setwalkableslopeoverride)
- [SetWorldScale3D](ue_ue.CableComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.CableComponent.md#setupattachment)
- [SnapTo](ue_ue.CableComponent.md#snapto)
- [ToggleActive](ue_ue.CableComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.CableComponent.md#togglevisibility)
- [WakeAllRigidBodies](ue_ue.CableComponent.md#wakeallrigidbodies)
- [WakeRigidBody](ue_ue.CableComponent.md#wakerigidbody)
- [Find](ue_ue.CableComponent.md#find)
- [Load](ue_ue.CableComponent.md#load)
- [StaticClass](ue_ue.CableComponent.md#staticclass)

## Constructors

### constructor

• **new CableComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MeshComponent](ue_ue.MeshComponent.md).[constructor](ue_ue.MeshComponent.md#constructor)

## Properties

### AlwaysLoadOnClient

• **AlwaysLoadOnClient**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[AlwaysLoadOnClient](ue_ue.MeshComponent.md#alwaysloadonclient)

___

### AlwaysLoadOnServer

• **AlwaysLoadOnServer**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[AlwaysLoadOnServer](ue_ue.MeshComponent.md#alwaysloadonserver)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[AssetUserData](ue_ue.MeshComponent.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[AttachChildren](ue_ue.MeshComponent.md#attachchildren)

___

### AttachEndTo

• **AttachEndTo**: [`ComponentReference`](ue_ue.ComponentReference.md)

___

### AttachEndToSocketName

• **AttachEndToSocketName**: `string`

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[AttachParent](ue_ue.MeshComponent.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[AttachSocketName](ue_ue.MeshComponent.md#attachsocketname)

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[BodyInstance](ue_ue.MeshComponent.md#bodyinstance)

___

### BoundsScale

• **BoundsScale**: `number`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[BoundsScale](ue_ue.MeshComponent.md#boundsscale)

___

### CableForce

• **CableForce**: [`Vector`](ue_ue_s.Vector.md)

___

### CableGravityScale

• **CableGravityScale**: `number`

___

### CableLength

• **CableLength**: `number`

___

### CableWidth

• **CableWidth**: `number`

___

### CachedMaxDrawDistance

• **CachedMaxDrawDistance**: `number`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[CachedMaxDrawDistance](ue_ue.MeshComponent.md#cachedmaxdrawdistance)

___

### CanBeCharacterBase

• **CanBeCharacterBase**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[CanBeCharacterBase](ue_ue.MeshComponent.md#canbecharacterbase)

___

### CanCharacterStepUpOn

• **CanCharacterStepUpOn**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[CanCharacterStepUpOn](ue_ue.MeshComponent.md#cancharacterstepupon)

___

### CastShadow

• **CastShadow**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[CastShadow](ue_ue.MeshComponent.md#castshadow)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[ClientAttachedChildren](ue_ue.MeshComponent.md#clientattachedchildren)

___

### CollisionFriction

• **CollisionFriction**: `number`

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[ComponentTags](ue_ue.MeshComponent.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[ComponentVelocity](ue_ue.MeshComponent.md#componentvelocity)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[CreationMethod](ue_ue.MeshComponent.md#creationmethod)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[CustomDepthStencilValue](ue_ue.MeshComponent.md#customdepthstencilvalue)

___

### CustomDepthStencilWriteMask

• **CustomDepthStencilWriteMask**: [`ERendererStencilMask`](../enums/ue_ue.ERendererStencilMask.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[CustomDepthStencilWriteMask](ue_ue.MeshComponent.md#customdepthstencilwritemask)

___

### CustomPrimitiveData

• **CustomPrimitiveData**: [`CustomPrimitiveData`](ue_ue.CustomPrimitiveData.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[CustomPrimitiveData](ue_ue.MeshComponent.md#customprimitivedata)

___

### DepthPriorityGroup

• **DepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[DepthPriorityGroup](ue_ue.MeshComponent.md#depthprioritygroup)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[DetailMode](ue_ue.MeshComponent.md#detailmode)

___

### EndLocation

• **EndLocation**: [`Vector`](ue_ue_s.Vector.md)

___

### ExcludeForSpecificHLODLevels

• **ExcludeForSpecificHLODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[ExcludeForSpecificHLODLevels](ue_ue.MeshComponent.md#excludeforspecifichlodlevels)

___

### IndirectLightingCacheQuality

• **IndirectLightingCacheQuality**: [`EIndirectLightingCacheQuality`](../enums/ue_ue.EIndirectLightingCacheQuality.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[IndirectLightingCacheQuality](ue_ue.MeshComponent.md#indirectlightingcachequality)

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[LDMaxDrawDistance](ue_ue.MeshComponent.md#ldmaxdrawdistance)

___

### LODParentPrimitive

• **LODParentPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[LODParentPrimitive](ue_ue.MeshComponent.md#lodparentprimitive)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[LightingChannels](ue_ue.MeshComponent.md#lightingchannels)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[LightmapType](ue_ue.MeshComponent.md#lightmaptype)

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[LpvBiasMultiplier](ue_ue.MeshComponent.md#lpvbiasmultiplier)

___

### MinDrawDistance

• **MinDrawDistance**: `number`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[MinDrawDistance](ue_ue.MeshComponent.md#mindrawdistance)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[Mobility](ue_ue.MeshComponent.md#mobility)

___

### MoveIgnoreActors

• **MoveIgnoreActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[MoveIgnoreActors](ue_ue.MeshComponent.md#moveignoreactors)

___

### MoveIgnoreComponents

• **MoveIgnoreComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[MoveIgnoreComponents](ue_ue.MeshComponent.md#moveignorecomponents)

___

### NumSegments

• **NumSegments**: `number`

___

### NumSides

• **NumSides**: `number`

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnBeginCursorOver](ue_ue.MeshComponent.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnClicked](ue_ue.MeshComponent.md#onclicked)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnComponentActivated](ue_ue.MeshComponent.md#oncomponentactivated)

___

### OnComponentBeginOverlap

• **OnComponentBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`, `bFromSweep`: `boolean`, `SweepResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnComponentBeginOverlap](ue_ue.MeshComponent.md#oncomponentbeginoverlap)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnComponentDeactivated](ue_ue.MeshComponent.md#oncomponentdeactivated)

___

### OnComponentEndOverlap

• **OnComponentEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`) => `void`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnComponentEndOverlap](ue_ue.MeshComponent.md#oncomponentendoverlap)

___

### OnComponentHit

• **OnComponentHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`HitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnComponentHit](ue_ue.MeshComponent.md#oncomponenthit)

___

### OnComponentSleep

• **OnComponentSleep**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SleepingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnComponentSleep](ue_ue.MeshComponent.md#oncomponentsleep)

___

### OnComponentWake

• **OnComponentWake**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`WakingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnComponentWake](ue_ue.MeshComponent.md#oncomponentwake)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnEndCursorOver](ue_ue.MeshComponent.md#onendcursorover)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnInputTouchBegin](ue_ue.MeshComponent.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnInputTouchEnd](ue_ue.MeshComponent.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnInputTouchEnter](ue_ue.MeshComponent.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnInputTouchLeave](ue_ue.MeshComponent.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnReleased](ue_ue.MeshComponent.md#onreleased)

___

### OverrideMaterials

• **OverrideMaterials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OverrideMaterials](ue_ue.MeshComponent.md#overridematerials)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[PhysicsVolume](ue_ue.MeshComponent.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.MeshComponent.md#physicsvolumechangeddelegate)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[PrimaryComponentTick](ue_ue.MeshComponent.md#primarycomponenttick)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[RelativeLocation](ue_ue.MeshComponent.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[RelativeRotation](ue_ue.MeshComponent.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[RelativeScale3D](ue_ue.MeshComponent.md#relativescale3d)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[RuntimeVirtualTextures](ue_ue.MeshComponent.md#runtimevirtualtextures)

___

### SolverIterations

• **SolverIterations**: `number`

___

### SubstepTime

• **SubstepTime**: `number`

___

### TileMaterial

• **TileMaterial**: `number`

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[TranslucencySortPriority](ue_ue.MeshComponent.md#translucencysortpriority)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[UCSModifiedProperties](ue_ue.MeshComponent.md#ucsmodifiedproperties)

___

### ViewOwnerDepthPriorityGroup

• **ViewOwnerDepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[ViewOwnerDepthPriorityGroup](ue_ue.MeshComponent.md#viewownerdepthprioritygroup)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[VirtualTextureCullMips](ue_ue.MeshComponent.md#virtualtexturecullmips)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[VirtualTextureLodBias](ue_ue.MeshComponent.md#virtualtexturelodbias)

___

### VirtualTextureMinCoverage

• **VirtualTextureMinCoverage**: `number`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[VirtualTextureMinCoverage](ue_ue.MeshComponent.md#virtualtexturemincoverage)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[VirtualTextureRenderPassType](ue_ue.MeshComponent.md#virtualtexturerenderpasstype)

___

### VisibilityId

• **VisibilityId**: `number`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[VisibilityId](ue_ue.MeshComponent.md#visibilityid)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[__tid_ActorComponent__](ue_ue.MeshComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_CableComponent\_\_

• **\_\_tid\_CableComponent\_\_**: `boolean`

___

### \_\_tid\_MeshComponent\_\_

• **\_\_tid\_MeshComponent\_\_**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[__tid_MeshComponent__](ue_ue.MeshComponent.md#__tid_meshcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[__tid_Object__](ue_ue.MeshComponent.md#__tid_object__)

___

### \_\_tid\_PrimitiveComponent\_\_

• **\_\_tid\_PrimitiveComponent\_\_**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[__tid_PrimitiveComponent__](ue_ue.MeshComponent.md#__tid_primitivecomponent__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[__tid_SceneComponent__](ue_ue.MeshComponent.md#__tid_scenecomponent__)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bAbsoluteLocation](ue_ue.MeshComponent.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bAbsoluteRotation](ue_ue.MeshComponent.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bAbsoluteScale](ue_ue.MeshComponent.md#babsolutescale)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bAffectDistanceFieldLighting](ue_ue.MeshComponent.md#baffectdistancefieldlighting)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bAffectDynamicIndirectLighting](ue_ue.MeshComponent.md#baffectdynamicindirectlighting)

___

### bAllowCullDistanceVolume

• **bAllowCullDistanceVolume**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bAllowCullDistanceVolume](ue_ue.MeshComponent.md#ballowculldistancevolume)

___

### bAlwaysCreatePhysicsState

• **bAlwaysCreatePhysicsState**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bAlwaysCreatePhysicsState](ue_ue.MeshComponent.md#balwayscreatephysicsstate)

___

### bApplyImpulseOnDamage

• **bApplyImpulseOnDamage**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bApplyImpulseOnDamage](ue_ue.MeshComponent.md#bapplyimpulseondamage)

___

### bAttachEnd

• **bAttachEnd**: `boolean`

___

### bAttachStart

• **bAttachStart**: `boolean`

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bAutoActivate](ue_ue.MeshComponent.md#bautoactivate)

___

### bBatchImpostersAsInstances

• **bBatchImpostersAsInstances**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bBatchImpostersAsInstances](ue_ue.MeshComponent.md#bbatchimpostersasinstances)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.MeshComponent.md#bboundschangetriggersstreamingdatarebuild)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bCanEverAffectNavigation](ue_ue.MeshComponent.md#bcaneveraffectnavigation)

___

### bCastCinematicShadow

• **bCastCinematicShadow**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bCastCinematicShadow](ue_ue.MeshComponent.md#bcastcinematicshadow)

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bCastDynamicShadow](ue_ue.MeshComponent.md#bcastdynamicshadow)

___

### bCastFarShadow

• **bCastFarShadow**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bCastFarShadow](ue_ue.MeshComponent.md#bcastfarshadow)

___

### bCastHiddenShadow

• **bCastHiddenShadow**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bCastHiddenShadow](ue_ue.MeshComponent.md#bcasthiddenshadow)

___

### bCastInsetShadow

• **bCastInsetShadow**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bCastInsetShadow](ue_ue.MeshComponent.md#bcastinsetshadow)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bCastShadowAsTwoSided](ue_ue.MeshComponent.md#bcastshadowastwosided)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bCastStaticShadow](ue_ue.MeshComponent.md#bcaststaticshadow)

___

### bCastVolumetricTranslucentShadow

• **bCastVolumetricTranslucentShadow**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bCastVolumetricTranslucentShadow](ue_ue.MeshComponent.md#bcastvolumetrictranslucentshadow)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bComponentToWorldUpdated](ue_ue.MeshComponent.md#bcomponenttoworldupdated)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bCreatedByConstructionScript](ue_ue.MeshComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bEditableWhenInherited](ue_ue.MeshComponent.md#beditablewheninherited)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bEnableAutoLODGeneration](ue_ue.MeshComponent.md#benableautolodgeneration)

___

### bEnableCollision

• **bEnableCollision**: `boolean`

___

### bEnableMaterialParameterCaching

• **bEnableMaterialParameterCaching**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bEnableMaterialParameterCaching](ue_ue.MeshComponent.md#benablematerialparametercaching)

___

### bEnableStiffness

• **bEnableStiffness**: `boolean`

___

### bExcludeFromLightAttachmentGroup

• **bExcludeFromLightAttachmentGroup**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bExcludeFromLightAttachmentGroup](ue_ue.MeshComponent.md#bexcludefromlightattachmentgroup)

___

### bForceMipStreaming

• **bForceMipStreaming**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bForceMipStreaming](ue_ue.MeshComponent.md#bforcemipstreaming)

___

### bGenerateOverlapEvents

• **bGenerateOverlapEvents**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bGenerateOverlapEvents](ue_ue.MeshComponent.md#bgenerateoverlapevents)

___

### bHasCustomNavigableGeometry

• **bHasCustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bHasCustomNavigableGeometry](ue_ue.MeshComponent.md#bhascustomnavigablegeometry)

___

### bHasMotionBlurVelocityMeshes

• **bHasMotionBlurVelocityMeshes**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bHasMotionBlurVelocityMeshes](ue_ue.MeshComponent.md#bhasmotionblurvelocitymeshes)

___

### bHasPerInstanceHitProxies

• **bHasPerInstanceHitProxies**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bHasPerInstanceHitProxies](ue_ue.MeshComponent.md#bhasperinstancehitproxies)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bHiddenInGame](ue_ue.MeshComponent.md#bhiddeningame)

___

### bIgnoreRadialForce

• **bIgnoreRadialForce**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bIgnoreRadialForce](ue_ue.MeshComponent.md#bignoreradialforce)

___

### bIgnoreRadialImpulse

• **bIgnoreRadialImpulse**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bIgnoreRadialImpulse](ue_ue.MeshComponent.md#bignoreradialimpulse)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bInstanceComponent](ue_ue.MeshComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bIsActive](ue_ue.MeshComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bIsEditorOnly](ue_ue.MeshComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bIsVisualizationComponent](ue_ue.MeshComponent.md#bisvisualizationcomponent)

___

### bLightAsIfStatic

• **bLightAsIfStatic**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bLightAsIfStatic](ue_ue.MeshComponent.md#blightasifstatic)

___

### bLightAttachmentsAsGroup

• **bLightAttachmentsAsGroup**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bLightAttachmentsAsGroup](ue_ue.MeshComponent.md#blightattachmentsasgroup)

___

### bMultiBodyOverlap

• **bMultiBodyOverlap**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bMultiBodyOverlap](ue_ue.MeshComponent.md#bmultibodyoverlap)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bNetAddressable](ue_ue.MeshComponent.md#bnetaddressable)

___

### bNeverDistanceCull

• **bNeverDistanceCull**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bNeverDistanceCull](ue_ue.MeshComponent.md#bneverdistancecull)

___

### bOnlyOwnerSee

• **bOnlyOwnerSee**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bOnlyOwnerSee](ue_ue.MeshComponent.md#bonlyownersee)

___

### bOwnerNoSee

• **bOwnerNoSee**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bOwnerNoSee](ue_ue.MeshComponent.md#bownernosee)

___

### bReceiveMobileCSMShadows

• **bReceiveMobileCSMShadows**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bReceiveMobileCSMShadows](ue_ue.MeshComponent.md#breceivemobilecsmshadows)

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bReceivesDecals](ue_ue.MeshComponent.md#breceivesdecals)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bRenderCustomDepth](ue_ue.MeshComponent.md#brendercustomdepth)

___

### bRenderInDepthPass

• **bRenderInDepthPass**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bRenderInDepthPass](ue_ue.MeshComponent.md#brenderindepthpass)

___

### bRenderInMainPass

• **bRenderInMainPass**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bRenderInMainPass](ue_ue.MeshComponent.md#brenderinmainpass)

___

### bReplicatePhysicsToAutonomousProxy

• **bReplicatePhysicsToAutonomousProxy**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bReplicatePhysicsToAutonomousProxy](ue_ue.MeshComponent.md#breplicatephysicstoautonomousproxy)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bReplicates](ue_ue.MeshComponent.md#breplicates)

___

### bReturnMaterialOnMove

• **bReturnMaterialOnMove**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bReturnMaterialOnMove](ue_ue.MeshComponent.md#breturnmaterialonmove)

___

### bSelectable

• **bSelectable**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bSelectable](ue_ue.MeshComponent.md#bselectable)

___

### bSelfShadowOnly

• **bSelfShadowOnly**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bSelfShadowOnly](ue_ue.MeshComponent.md#bselfshadowonly)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bShouldBeAttached](ue_ue.MeshComponent.md#bshouldbeattached)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.MeshComponent.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.MeshComponent.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.MeshComponent.md#bshouldupdatephysicsvolume)

___

### bSingleSampleShadowFromStationaryLights

• **bSingleSampleShadowFromStationaryLights**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bSingleSampleShadowFromStationaryLights](ue_ue.MeshComponent.md#bsinglesampleshadowfromstationarylights)

___

### bTraceComplexOnMove

• **bTraceComplexOnMove**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bTraceComplexOnMove](ue_ue.MeshComponent.md#btracecomplexonmove)

___

### bTreatAsBackgroundForOcclusion

• **bTreatAsBackgroundForOcclusion**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bTreatAsBackgroundForOcclusion](ue_ue.MeshComponent.md#btreatasbackgroundforocclusion)

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bUseAsOccluder](ue_ue.MeshComponent.md#buseasoccluder)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bUseAttachParentBound](ue_ue.MeshComponent.md#buseattachparentbound)

___

### bUseEditorCompositing

• **bUseEditorCompositing**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bUseEditorCompositing](ue_ue.MeshComponent.md#buseeditorcompositing)

___

### bUseMaxLODAsImposter

• **bUseMaxLODAsImposter**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bUseMaxLODAsImposter](ue_ue.MeshComponent.md#busemaxlodasimposter)

___

### bUseViewOwnerDepthPriorityGroup

• **bUseViewOwnerDepthPriorityGroup**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bUseViewOwnerDepthPriorityGroup](ue_ue.MeshComponent.md#buseviewownerdepthprioritygroup)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bVisible](ue_ue.MeshComponent.md#bvisible)

___

### bVisibleInRayTracing

• **bVisibleInRayTracing**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bVisibleInRayTracing](ue_ue.MeshComponent.md#bvisibleinraytracing)

___

### bVisibleInReflectionCaptures

• **bVisibleInReflectionCaptures**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bVisibleInReflectionCaptures](ue_ue.MeshComponent.md#bvisibleinreflectioncaptures)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[bVisualizeComponent](ue_ue.MeshComponent.md#bvisualizecomponent)

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

[MeshComponent](ue_ue.MeshComponent.md).[Activate](ue_ue.MeshComponent.md#activate)

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

[MeshComponent](ue_ue.MeshComponent.md).[AddAngularImpulse](ue_ue.MeshComponent.md#addangularimpulse)

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

[MeshComponent](ue_ue.MeshComponent.md).[AddAngularImpulseInDegrees](ue_ue.MeshComponent.md#addangularimpulseindegrees)

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

[MeshComponent](ue_ue.MeshComponent.md).[AddAngularImpulseInRadians](ue_ue.MeshComponent.md#addangularimpulseinradians)

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

[MeshComponent](ue_ue.MeshComponent.md).[AddForce](ue_ue.MeshComponent.md#addforce)

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

[MeshComponent](ue_ue.MeshComponent.md).[AddForceAtLocation](ue_ue.MeshComponent.md#addforceatlocation)

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

[MeshComponent](ue_ue.MeshComponent.md).[AddForceAtLocationLocal](ue_ue.MeshComponent.md#addforceatlocationlocal)

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

[MeshComponent](ue_ue.MeshComponent.md).[AddImpulse](ue_ue.MeshComponent.md#addimpulse)

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

[MeshComponent](ue_ue.MeshComponent.md).[AddImpulseAtLocation](ue_ue.MeshComponent.md#addimpulseatlocation)

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

[MeshComponent](ue_ue.MeshComponent.md).[AddRadialForce](ue_ue.MeshComponent.md#addradialforce)

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

[MeshComponent](ue_ue.MeshComponent.md).[AddRadialImpulse](ue_ue.MeshComponent.md#addradialimpulse)

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

[MeshComponent](ue_ue.MeshComponent.md).[AddTickPrerequisiteActor](ue_ue.MeshComponent.md#addtickprerequisiteactor)

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

[MeshComponent](ue_ue.MeshComponent.md).[AddTickPrerequisiteComponent](ue_ue.MeshComponent.md#addtickprerequisitecomponent)

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

[MeshComponent](ue_ue.MeshComponent.md).[AddTorque](ue_ue.MeshComponent.md#addtorque)

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

[MeshComponent](ue_ue.MeshComponent.md).[AddTorqueInDegrees](ue_ue.MeshComponent.md#addtorqueindegrees)

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

[MeshComponent](ue_ue.MeshComponent.md).[AddTorqueInRadians](ue_ue.MeshComponent.md#addtorqueinradians)

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

[MeshComponent](ue_ue.MeshComponent.md).[CanCharacterStepUp](ue_ue.MeshComponent.md#cancharacterstepup)

___

### ClearMoveIgnoreActors

▸ **ClearMoveIgnoreActors**(): `void`

#### Returns

`void`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[ClearMoveIgnoreActors](ue_ue.MeshComponent.md#clearmoveignoreactors)

___

### ClearMoveIgnoreComponents

▸ **ClearMoveIgnoreComponents**(): `void`

#### Returns

`void`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[ClearMoveIgnoreComponents](ue_ue.MeshComponent.md#clearmoveignorecomponents)

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

[MeshComponent](ue_ue.MeshComponent.md).[ComponentHasTag](ue_ue.MeshComponent.md#componenthastag)

___

### CopyArrayOfMoveIgnoreActors

▸ **CopyArrayOfMoveIgnoreActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[CopyArrayOfMoveIgnoreActors](ue_ue.MeshComponent.md#copyarrayofmoveignoreactors)

___

### CopyArrayOfMoveIgnoreComponents

▸ **CopyArrayOfMoveIgnoreComponents**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[CopyArrayOfMoveIgnoreComponents](ue_ue.MeshComponent.md#copyarrayofmoveignorecomponents)

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

[MeshComponent](ue_ue.MeshComponent.md).[CreateAndSetMaterialInstanceDynamic](ue_ue.MeshComponent.md#createandsetmaterialinstancedynamic)

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

[MeshComponent](ue_ue.MeshComponent.md).[CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.MeshComponent.md#createandsetmaterialinstancedynamicfrommaterial)

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

[MeshComponent](ue_ue.MeshComponent.md).[CreateDefaultSubobject](ue_ue.MeshComponent.md#createdefaultsubobject)

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

[MeshComponent](ue_ue.MeshComponent.md).[CreateDynamicMaterialInstance](ue_ue.MeshComponent.md#createdynamicmaterialinstance)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[Deactivate](ue_ue.MeshComponent.md#deactivate)

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

[MeshComponent](ue_ue.MeshComponent.md).[DetachFromParent](ue_ue.MeshComponent.md#detachfromparent)

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

[MeshComponent](ue_ue.MeshComponent.md).[DoesSocketExist](ue_ue.MeshComponent.md#doessocketexist)

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

[MeshComponent](ue_ue.MeshComponent.md).[ExecuteUbergraph](ue_ue.MeshComponent.md#executeubergraph)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetAllSocketNames](ue_ue.MeshComponent.md#getallsocketnames)

___

### GetAngularDamping

▸ **GetAngularDamping**(): `number`

#### Returns

`number`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetAngularDamping](ue_ue.MeshComponent.md#getangulardamping)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetAttachParent](ue_ue.MeshComponent.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetAttachSocketName](ue_ue.MeshComponent.md#getattachsocketname)

___

### GetAttachedActor

▸ **GetAttachedActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

___

### GetAttachedComponent

▸ **GetAttachedComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

___

### GetCableParticleLocations

▸ **GetCableParticleLocations**(`Locations`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Locations` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |

#### Returns

`void`

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

[MeshComponent](ue_ue.MeshComponent.md).[GetCenterOfMass](ue_ue.MeshComponent.md#getcenterofmass)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetChildComponent](ue_ue.MeshComponent.md#getchildcomponent)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetChildrenComponents](ue_ue.MeshComponent.md#getchildrencomponents)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetClass](ue_ue.MeshComponent.md#getclass)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetClosestPointOnCollision](ue_ue.MeshComponent.md#getclosestpointoncollision)

___

### GetCollisionEnabled

▸ **GetCollisionEnabled**(): [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Returns

[`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetCollisionEnabled](ue_ue.MeshComponent.md#getcollisionenabled)

___

### GetCollisionObjectType

▸ **GetCollisionObjectType**(): [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Returns

[`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetCollisionObjectType](ue_ue.MeshComponent.md#getcollisionobjecttype)

___

### GetCollisionProfileName

▸ **GetCollisionProfileName**(): `string`

#### Returns

`string`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetCollisionProfileName](ue_ue.MeshComponent.md#getcollisionprofilename)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetCollisionResponseToChannel](ue_ue.MeshComponent.md#getcollisionresponsetochannel)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetComponentTickInterval](ue_ue.MeshComponent.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetComponentVelocity](ue_ue.MeshComponent.md#getcomponentvelocity)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetForwardVector](ue_ue.MeshComponent.md#getforwardvector)

___

### GetGenerateOverlapEvents

▸ **GetGenerateOverlapEvents**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetGenerateOverlapEvents](ue_ue.MeshComponent.md#getgenerateoverlapevents)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetInertiaTensor](ue_ue.MeshComponent.md#getinertiatensor)

___

### GetLinearDamping

▸ **GetLinearDamping**(): `number`

#### Returns

`number`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetLinearDamping](ue_ue.MeshComponent.md#getlineardamping)

___

### GetMass

▸ **GetMass**(): `number`

#### Returns

`number`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetMass](ue_ue.MeshComponent.md#getmass)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetMassScale](ue_ue.MeshComponent.md#getmassscale)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetMaterial](ue_ue.MeshComponent.md#getmaterial)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetMaterialFromCollisionFaceIndex](ue_ue.MeshComponent.md#getmaterialfromcollisionfaceindex)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetMaterialIndex](ue_ue.MeshComponent.md#getmaterialindex)

___

### GetMaterialSlotNames

▸ **GetMaterialSlotNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetMaterialSlotNames](ue_ue.MeshComponent.md#getmaterialslotnames)

___

### GetMaterials

▸ **GetMaterials**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetMaterials](ue_ue.MeshComponent.md#getmaterials)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetName](ue_ue.MeshComponent.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetNumChildrenComponents](ue_ue.MeshComponent.md#getnumchildrencomponents)

___

### GetNumMaterials

▸ **GetNumMaterials**(): `number`

#### Returns

`number`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetNumMaterials](ue_ue.MeshComponent.md#getnummaterials)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetOuter](ue_ue.MeshComponent.md#getouter)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetOverlappingActors](ue_ue.MeshComponent.md#getoverlappingactors)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetOverlappingComponents](ue_ue.MeshComponent.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetOwner](ue_ue.MeshComponent.md#getowner)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetParentComponents](ue_ue.MeshComponent.md#getparentcomponents)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetPhysicsAngularVelocity](ue_ue.MeshComponent.md#getphysicsangularvelocity)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetPhysicsAngularVelocityInDegrees](ue_ue.MeshComponent.md#getphysicsangularvelocityindegrees)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetPhysicsAngularVelocityInRadians](ue_ue.MeshComponent.md#getphysicsangularvelocityinradians)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetPhysicsLinearVelocity](ue_ue.MeshComponent.md#getphysicslinearvelocity)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetPhysicsLinearVelocityAtPoint](ue_ue.MeshComponent.md#getphysicslinearvelocityatpoint)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetPhysicsVolume](ue_ue.MeshComponent.md#getphysicsvolume)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetRelativeTransform](ue_ue.MeshComponent.md#getrelativetransform)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetRightVector](ue_ue.MeshComponent.md#getrightvector)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.MeshComponent.md#getshouldupdatephysicsvolume)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetSocketLocation](ue_ue.MeshComponent.md#getsocketlocation)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetSocketQuaternion](ue_ue.MeshComponent.md#getsocketquaternion)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetSocketRotation](ue_ue.MeshComponent.md#getsocketrotation)

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

[MeshComponent](ue_ue.MeshComponent.md).[GetSocketTransform](ue_ue.MeshComponent.md#getsockettransform)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetUpVector](ue_ue.MeshComponent.md#getupvector)

___

### GetWalkableSlopeOverride

▸ **GetWalkableSlopeOverride**(): [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Returns

[`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetWalkableSlopeOverride](ue_ue.MeshComponent.md#getwalkableslopeoverride)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[GetWorld](ue_ue.MeshComponent.md#getworld)

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

[MeshComponent](ue_ue.MeshComponent.md).[IgnoreActorWhenMoving](ue_ue.MeshComponent.md#ignoreactorwhenmoving)

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

[MeshComponent](ue_ue.MeshComponent.md).[IgnoreComponentWhenMoving](ue_ue.MeshComponent.md#ignorecomponentwhenmoving)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[IsActive](ue_ue.MeshComponent.md#isactive)

___

### IsAnyRigidBodyAwake

▸ **IsAnyRigidBodyAwake**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[IsAnyRigidBodyAwake](ue_ue.MeshComponent.md#isanyrigidbodyawake)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[IsAnySimulatingPhysics](ue_ue.MeshComponent.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[IsBeingDestroyed](ue_ue.MeshComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[IsComponentTickEnabled](ue_ue.MeshComponent.md#iscomponenttickenabled)

___

### IsGravityEnabled

▸ **IsGravityEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[IsGravityEnabled](ue_ue.MeshComponent.md#isgravityenabled)

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

[MeshComponent](ue_ue.MeshComponent.md).[IsMaterialSlotNameValid](ue_ue.MeshComponent.md#ismaterialslotnamevalid)

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

[MeshComponent](ue_ue.MeshComponent.md).[IsOverlappingActor](ue_ue.MeshComponent.md#isoverlappingactor)

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

[MeshComponent](ue_ue.MeshComponent.md).[IsOverlappingComponent](ue_ue.MeshComponent.md#isoverlappingcomponent)

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

[MeshComponent](ue_ue.MeshComponent.md).[IsSimulatingPhysics](ue_ue.MeshComponent.md#issimulatingphysics)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[IsVisible](ue_ue.MeshComponent.md#isvisible)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_AddLocalOffset](ue_ue.MeshComponent.md#k2_addlocaloffset)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_AddLocalRotation](ue_ue.MeshComponent.md#k2_addlocalrotation)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_AddLocalTransform](ue_ue.MeshComponent.md#k2_addlocaltransform)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_AddRelativeLocation](ue_ue.MeshComponent.md#k2_addrelativelocation)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_AddRelativeRotation](ue_ue.MeshComponent.md#k2_addrelativerotation)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_AddWorldOffset](ue_ue.MeshComponent.md#k2_addworldoffset)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_AddWorldRotation](ue_ue.MeshComponent.md#k2_addworldrotation)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_AddWorldTransform](ue_ue.MeshComponent.md#k2_addworldtransform)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_AttachTo](ue_ue.MeshComponent.md#k2_attachto)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_AttachToComponent](ue_ue.MeshComponent.md#k2_attachtocomponent)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_BoxOverlapComponent](ue_ue.MeshComponent.md#k2_boxoverlapcomponent)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_DestroyComponent](ue_ue.MeshComponent.md#k2_destroycomponent)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_DetachFromComponent](ue_ue.MeshComponent.md#k2_detachfromcomponent)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[K2_GetComponentLocation](ue_ue.MeshComponent.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[K2_GetComponentRotation](ue_ue.MeshComponent.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[K2_GetComponentScale](ue_ue.MeshComponent.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[K2_GetComponentToWorld](ue_ue.MeshComponent.md#k2_getcomponenttoworld)

___

### K2\_IsCollisionEnabled

▸ **K2_IsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[K2_IsCollisionEnabled](ue_ue.MeshComponent.md#k2_iscollisionenabled)

___

### K2\_IsPhysicsCollisionEnabled

▸ **K2_IsPhysicsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[K2_IsPhysicsCollisionEnabled](ue_ue.MeshComponent.md#k2_isphysicscollisionenabled)

___

### K2\_IsQueryCollisionEnabled

▸ **K2_IsQueryCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[K2_IsQueryCollisionEnabled](ue_ue.MeshComponent.md#k2_isquerycollisionenabled)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_LineTraceComponent](ue_ue.MeshComponent.md#k2_linetracecomponent)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_SetRelativeLocation](ue_ue.MeshComponent.md#k2_setrelativelocation)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.MeshComponent.md#k2_setrelativelocationandrotation)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_SetRelativeRotation](ue_ue.MeshComponent.md#k2_setrelativerotation)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_SetRelativeTransform](ue_ue.MeshComponent.md#k2_setrelativetransform)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_SetWorldLocation](ue_ue.MeshComponent.md#k2_setworldlocation)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.MeshComponent.md#k2_setworldlocationandrotation)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_SetWorldRotation](ue_ue.MeshComponent.md#k2_setworldrotation)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_SetWorldTransform](ue_ue.MeshComponent.md#k2_setworldtransform)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_SphereOverlapComponent](ue_ue.MeshComponent.md#k2_sphereoverlapcomponent)

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

[MeshComponent](ue_ue.MeshComponent.md).[K2_SphereTraceComponent](ue_ue.MeshComponent.md#k2_spheretracecomponent)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnRep_AttachChildren](ue_ue.MeshComponent.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnRep_AttachParent](ue_ue.MeshComponent.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnRep_AttachSocketName](ue_ue.MeshComponent.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnRep_IsActive](ue_ue.MeshComponent.md#onrep_isactive)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[OnRep_Transform](ue_ue.MeshComponent.md#onrep_transform)

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

[MeshComponent](ue_ue.MeshComponent.md).[OnRep_Visibility](ue_ue.MeshComponent.md#onrep_visibility)

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

[MeshComponent](ue_ue.MeshComponent.md).[PrestreamTextures](ue_ue.MeshComponent.md#prestreamtextures)

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

[MeshComponent](ue_ue.MeshComponent.md).[PutRigidBodyToSleep](ue_ue.MeshComponent.md#putrigidbodytosleep)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[ReceiveBeginPlay](ue_ue.MeshComponent.md#receivebeginplay)

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

[MeshComponent](ue_ue.MeshComponent.md).[ReceiveEndPlay](ue_ue.MeshComponent.md#receiveendplay)

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

[MeshComponent](ue_ue.MeshComponent.md).[ReceiveTick](ue_ue.MeshComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[RegisterComponent](ue_ue.MeshComponent.md#registercomponent)

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

[MeshComponent](ue_ue.MeshComponent.md).[RemoveTickPrerequisiteActor](ue_ue.MeshComponent.md#removetickprerequisiteactor)

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

[MeshComponent](ue_ue.MeshComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.MeshComponent.md#removetickprerequisitecomponent)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[ResetRelativeTransform](ue_ue.MeshComponent.md#resetrelativetransform)

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

[MeshComponent](ue_ue.MeshComponent.md).[ScaleByMomentOfInertia](ue_ue.MeshComponent.md#scalebymomentofinertia)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetAbsolute](ue_ue.MeshComponent.md#setabsolute)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetActive](ue_ue.MeshComponent.md#setactive)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetAllMassScale](ue_ue.MeshComponent.md#setallmassscale)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetAllPhysicsAngularVelocityInDegrees](ue_ue.MeshComponent.md#setallphysicsangularvelocityindegrees)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetAllPhysicsAngularVelocityInRadians](ue_ue.MeshComponent.md#setallphysicsangularvelocityinradians)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetAllPhysicsLinearVelocity](ue_ue.MeshComponent.md#setallphysicslinearvelocity)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetAllUseCCD](ue_ue.MeshComponent.md#setalluseccd)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetAngularDamping](ue_ue.MeshComponent.md#setangulardamping)

___

### SetAttachEndTo

▸ **SetAttachEndTo**(`Actor`, `ComponentProperty`, `SocketName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `ComponentProperty` | `string` |
| `SocketName?` | `string` |

#### Returns

`void`

___

### SetAttachEndToComponent

▸ **SetAttachEndToComponent**(`Component`, `SocketName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Component` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `SocketName?` | `string` |

#### Returns

`void`

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

[MeshComponent](ue_ue.MeshComponent.md).[SetAutoActivate](ue_ue.MeshComponent.md#setautoactivate)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetBoundsScale](ue_ue.MeshComponent.md#setboundsscale)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetCastInsetShadow](ue_ue.MeshComponent.md#setcastinsetshadow)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetCastShadow](ue_ue.MeshComponent.md#setcastshadow)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetCenterOfMass](ue_ue.MeshComponent.md#setcenterofmass)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetCollisionEnabled](ue_ue.MeshComponent.md#setcollisionenabled)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetCollisionObjectType](ue_ue.MeshComponent.md#setcollisionobjecttype)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetCollisionProfileName](ue_ue.MeshComponent.md#setcollisionprofilename)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetCollisionResponseToAllChannels](ue_ue.MeshComponent.md#setcollisionresponsetoallchannels)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetCollisionResponseToChannel](ue_ue.MeshComponent.md#setcollisionresponsetochannel)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetComponentTickEnabled](ue_ue.MeshComponent.md#setcomponenttickenabled)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetComponentTickInterval](ue_ue.MeshComponent.md#setcomponenttickinterval)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetConstraintMode](ue_ue.MeshComponent.md#setconstraintmode)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetCullDistance](ue_ue.MeshComponent.md#setculldistance)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetCustomDepthStencilValue](ue_ue.MeshComponent.md#setcustomdepthstencilvalue)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetCustomDepthStencilWriteMask](ue_ue.MeshComponent.md#setcustomdepthstencilwritemask)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetCustomPrimitiveDataFloat](ue_ue.MeshComponent.md#setcustomprimitivedatafloat)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetCustomPrimitiveDataVector2](ue_ue.MeshComponent.md#setcustomprimitivedatavector2)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetCustomPrimitiveDataVector3](ue_ue.MeshComponent.md#setcustomprimitivedatavector3)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetCustomPrimitiveDataVector4](ue_ue.MeshComponent.md#setcustomprimitivedatavector4)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetEnableGravity](ue_ue.MeshComponent.md#setenablegravity)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetExcludeFromLightAttachmentGroup](ue_ue.MeshComponent.md#setexcludefromlightattachmentgroup)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetGenerateOverlapEvents](ue_ue.MeshComponent.md#setgenerateoverlapevents)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetHiddenInGame](ue_ue.MeshComponent.md#sethiddeningame)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetIsReplicated](ue_ue.MeshComponent.md#setisreplicated)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetLightAttachmentsAsGroup](ue_ue.MeshComponent.md#setlightattachmentsasgroup)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetLinearDamping](ue_ue.MeshComponent.md#setlineardamping)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetMassOverrideInKg](ue_ue.MeshComponent.md#setmassoverrideinkg)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetMassScale](ue_ue.MeshComponent.md#setmassscale)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetMaterial](ue_ue.MeshComponent.md#setmaterial)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetMaterialByName](ue_ue.MeshComponent.md#setmaterialbyname)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetMobility](ue_ue.MeshComponent.md#setmobility)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetNotifyRigidBodyCollision](ue_ue.MeshComponent.md#setnotifyrigidbodycollision)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetOnlyOwnerSee](ue_ue.MeshComponent.md#setonlyownersee)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetOwnerNoSee](ue_ue.MeshComponent.md#setownernosee)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetPhysMaterialOverride](ue_ue.MeshComponent.md#setphysmaterialoverride)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetPhysicsAngularVelocity](ue_ue.MeshComponent.md#setphysicsangularvelocity)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetPhysicsAngularVelocityInDegrees](ue_ue.MeshComponent.md#setphysicsangularvelocityindegrees)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetPhysicsAngularVelocityInRadians](ue_ue.MeshComponent.md#setphysicsangularvelocityinradians)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetPhysicsLinearVelocity](ue_ue.MeshComponent.md#setphysicslinearvelocity)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetPhysicsMaxAngularVelocity](ue_ue.MeshComponent.md#setphysicsmaxangularvelocity)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetPhysicsMaxAngularVelocityInDegrees](ue_ue.MeshComponent.md#setphysicsmaxangularvelocityindegrees)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetPhysicsMaxAngularVelocityInRadians](ue_ue.MeshComponent.md#setphysicsmaxangularvelocityinradians)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetReceivesDecals](ue_ue.MeshComponent.md#setreceivesdecals)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetRelativeScale3D](ue_ue.MeshComponent.md#setrelativescale3d)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetRenderCustomDepth](ue_ue.MeshComponent.md#setrendercustomdepth)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetRenderInMainPass](ue_ue.MeshComponent.md#setrenderinmainpass)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetScalarParameterValueOnMaterials](ue_ue.MeshComponent.md#setscalarparametervalueonmaterials)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.MeshComponent.md#setshouldupdatephysicsvolume)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetSimulatePhysics](ue_ue.MeshComponent.md#setsimulatephysics)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetSingleSampleShadowFromStationaryLights](ue_ue.MeshComponent.md#setsinglesampleshadowfromstationarylights)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetTickGroup](ue_ue.MeshComponent.md#settickgroup)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetTickableWhenPaused](ue_ue.MeshComponent.md#settickablewhenpaused)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetTranslucentSortPriority](ue_ue.MeshComponent.md#settranslucentsortpriority)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetUseCCD](ue_ue.MeshComponent.md#setuseccd)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetVectorParameterValueOnMaterials](ue_ue.MeshComponent.md#setvectorparametervalueonmaterials)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetVisibility](ue_ue.MeshComponent.md#setvisibility)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetWalkableSlopeOverride](ue_ue.MeshComponent.md#setwalkableslopeoverride)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetWorldScale3D](ue_ue.MeshComponent.md#setworldscale3d)

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

[MeshComponent](ue_ue.MeshComponent.md).[SetupAttachment](ue_ue.MeshComponent.md#setupattachment)

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

[MeshComponent](ue_ue.MeshComponent.md).[SnapTo](ue_ue.MeshComponent.md#snapto)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[ToggleActive](ue_ue.MeshComponent.md#toggleactive)

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

[MeshComponent](ue_ue.MeshComponent.md).[ToggleVisibility](ue_ue.MeshComponent.md#togglevisibility)

___

### WakeAllRigidBodies

▸ **WakeAllRigidBodies**(): `void`

#### Returns

`void`

#### Inherited from

[MeshComponent](ue_ue.MeshComponent.md).[WakeAllRigidBodies](ue_ue.MeshComponent.md#wakeallrigidbodies)

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

[MeshComponent](ue_ue.MeshComponent.md).[WakeRigidBody](ue_ue.MeshComponent.md#wakerigidbody)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CableComponent`](ue_ue.CableComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CableComponent`](ue_ue.CableComponent.md)

#### Overrides

[MeshComponent](ue_ue.MeshComponent.md).[Find](ue_ue.MeshComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`CableComponent`](ue_ue.CableComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CableComponent`](ue_ue.CableComponent.md)

#### Overrides

[MeshComponent](ue_ue.MeshComponent.md).[Load](ue_ue.MeshComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MeshComponent](ue_ue.MeshComponent.md).[StaticClass](ue_ue.MeshComponent.md#staticclass)
