[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GizmoRectangleComponent

# Class: GizmoRectangleComponent

[ue/ue](../modules/ue_ue.md).GizmoRectangleComponent

## Hierarchy

- [`GizmoBaseComponent`](ue_ue.GizmoBaseComponent.md)

  ↳ **`GizmoRectangleComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.GizmoRectangleComponent.md#constructor)

### Properties

- [AlwaysLoadOnClient](ue_ue.GizmoRectangleComponent.md#alwaysloadonclient)
- [AlwaysLoadOnServer](ue_ue.GizmoRectangleComponent.md#alwaysloadonserver)
- [AssetUserData](ue_ue.GizmoRectangleComponent.md#assetuserdata)
- [AttachChildren](ue_ue.GizmoRectangleComponent.md#attachchildren)
- [AttachParent](ue_ue.GizmoRectangleComponent.md#attachparent)
- [AttachSocketName](ue_ue.GizmoRectangleComponent.md#attachsocketname)
- [BodyInstance](ue_ue.GizmoRectangleComponent.md#bodyinstance)
- [BoundsScale](ue_ue.GizmoRectangleComponent.md#boundsscale)
- [CachedMaxDrawDistance](ue_ue.GizmoRectangleComponent.md#cachedmaxdrawdistance)
- [CanBeCharacterBase](ue_ue.GizmoRectangleComponent.md#canbecharacterbase)
- [CanCharacterStepUpOn](ue_ue.GizmoRectangleComponent.md#cancharacterstepupon)
- [CastShadow](ue_ue.GizmoRectangleComponent.md#castshadow)
- [ClientAttachedChildren](ue_ue.GizmoRectangleComponent.md#clientattachedchildren)
- [Color](ue_ue.GizmoRectangleComponent.md#color)
- [ComponentTags](ue_ue.GizmoRectangleComponent.md#componenttags)
- [ComponentVelocity](ue_ue.GizmoRectangleComponent.md#componentvelocity)
- [CreationMethod](ue_ue.GizmoRectangleComponent.md#creationmethod)
- [CustomDepthStencilValue](ue_ue.GizmoRectangleComponent.md#customdepthstencilvalue)
- [CustomDepthStencilWriteMask](ue_ue.GizmoRectangleComponent.md#customdepthstencilwritemask)
- [CustomPrimitiveData](ue_ue.GizmoRectangleComponent.md#customprimitivedata)
- [DepthPriorityGroup](ue_ue.GizmoRectangleComponent.md#depthprioritygroup)
- [DetailMode](ue_ue.GizmoRectangleComponent.md#detailmode)
- [DirectionX](ue_ue.GizmoRectangleComponent.md#directionx)
- [DirectionY](ue_ue.GizmoRectangleComponent.md#directiony)
- [ExcludeForSpecificHLODLevels](ue_ue.GizmoRectangleComponent.md#excludeforspecifichlodlevels)
- [HoverSizeMultiplier](ue_ue.GizmoRectangleComponent.md#hoversizemultiplier)
- [IndirectLightingCacheQuality](ue_ue.GizmoRectangleComponent.md#indirectlightingcachequality)
- [LDMaxDrawDistance](ue_ue.GizmoRectangleComponent.md#ldmaxdrawdistance)
- [LODParentPrimitive](ue_ue.GizmoRectangleComponent.md#lodparentprimitive)
- [LengthX](ue_ue.GizmoRectangleComponent.md#lengthx)
- [LengthY](ue_ue.GizmoRectangleComponent.md#lengthy)
- [LightingChannels](ue_ue.GizmoRectangleComponent.md#lightingchannels)
- [LightmapType](ue_ue.GizmoRectangleComponent.md#lightmaptype)
- [LpvBiasMultiplier](ue_ue.GizmoRectangleComponent.md#lpvbiasmultiplier)
- [MinDrawDistance](ue_ue.GizmoRectangleComponent.md#mindrawdistance)
- [Mobility](ue_ue.GizmoRectangleComponent.md#mobility)
- [MoveIgnoreActors](ue_ue.GizmoRectangleComponent.md#moveignoreactors)
- [MoveIgnoreComponents](ue_ue.GizmoRectangleComponent.md#moveignorecomponents)
- [OffsetX](ue_ue.GizmoRectangleComponent.md#offsetx)
- [OffsetY](ue_ue.GizmoRectangleComponent.md#offsety)
- [OnBeginCursorOver](ue_ue.GizmoRectangleComponent.md#onbegincursorover)
- [OnClicked](ue_ue.GizmoRectangleComponent.md#onclicked)
- [OnComponentActivated](ue_ue.GizmoRectangleComponent.md#oncomponentactivated)
- [OnComponentBeginOverlap](ue_ue.GizmoRectangleComponent.md#oncomponentbeginoverlap)
- [OnComponentDeactivated](ue_ue.GizmoRectangleComponent.md#oncomponentdeactivated)
- [OnComponentEndOverlap](ue_ue.GizmoRectangleComponent.md#oncomponentendoverlap)
- [OnComponentHit](ue_ue.GizmoRectangleComponent.md#oncomponenthit)
- [OnComponentSleep](ue_ue.GizmoRectangleComponent.md#oncomponentsleep)
- [OnComponentWake](ue_ue.GizmoRectangleComponent.md#oncomponentwake)
- [OnEndCursorOver](ue_ue.GizmoRectangleComponent.md#onendcursorover)
- [OnInputTouchBegin](ue_ue.GizmoRectangleComponent.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.GizmoRectangleComponent.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.GizmoRectangleComponent.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.GizmoRectangleComponent.md#oninputtouchleave)
- [OnReleased](ue_ue.GizmoRectangleComponent.md#onreleased)
- [PhysicsVolume](ue_ue.GizmoRectangleComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.GizmoRectangleComponent.md#physicsvolumechangeddelegate)
- [PixelHitDistanceThreshold](ue_ue.GizmoRectangleComponent.md#pixelhitdistancethreshold)
- [PrimaryComponentTick](ue_ue.GizmoRectangleComponent.md#primarycomponenttick)
- [RelativeLocation](ue_ue.GizmoRectangleComponent.md#relativelocation)
- [RelativeRotation](ue_ue.GizmoRectangleComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.GizmoRectangleComponent.md#relativescale3d)
- [RuntimeVirtualTextures](ue_ue.GizmoRectangleComponent.md#runtimevirtualtextures)
- [Thickness](ue_ue.GizmoRectangleComponent.md#thickness)
- [TranslucencySortPriority](ue_ue.GizmoRectangleComponent.md#translucencysortpriority)
- [UCSModifiedProperties](ue_ue.GizmoRectangleComponent.md#ucsmodifiedproperties)
- [ViewOwnerDepthPriorityGroup](ue_ue.GizmoRectangleComponent.md#viewownerdepthprioritygroup)
- [VirtualTextureCullMips](ue_ue.GizmoRectangleComponent.md#virtualtexturecullmips)
- [VirtualTextureLodBias](ue_ue.GizmoRectangleComponent.md#virtualtexturelodbias)
- [VirtualTextureMinCoverage](ue_ue.GizmoRectangleComponent.md#virtualtexturemincoverage)
- [VirtualTextureRenderPassType](ue_ue.GizmoRectangleComponent.md#virtualtexturerenderpasstype)
- [VisibilityId](ue_ue.GizmoRectangleComponent.md#visibilityid)
- [\_\_tid\_ActorComponent\_\_](ue_ue.GizmoRectangleComponent.md#__tid_actorcomponent__)
- [\_\_tid\_GizmoBaseComponent\_\_](ue_ue.GizmoRectangleComponent.md#__tid_gizmobasecomponent__)
- [\_\_tid\_GizmoRectangleComponent\_\_](ue_ue.GizmoRectangleComponent.md#__tid_gizmorectanglecomponent__)
- [\_\_tid\_Object\_\_](ue_ue.GizmoRectangleComponent.md#__tid_object__)
- [\_\_tid\_PrimitiveComponent\_\_](ue_ue.GizmoRectangleComponent.md#__tid_primitivecomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.GizmoRectangleComponent.md#__tid_scenecomponent__)
- [bAbsoluteLocation](ue_ue.GizmoRectangleComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.GizmoRectangleComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.GizmoRectangleComponent.md#babsolutescale)
- [bAffectDistanceFieldLighting](ue_ue.GizmoRectangleComponent.md#baffectdistancefieldlighting)
- [bAffectDynamicIndirectLighting](ue_ue.GizmoRectangleComponent.md#baffectdynamicindirectlighting)
- [bAllowCullDistanceVolume](ue_ue.GizmoRectangleComponent.md#ballowculldistancevolume)
- [bAlwaysCreatePhysicsState](ue_ue.GizmoRectangleComponent.md#balwayscreatephysicsstate)
- [bApplyImpulseOnDamage](ue_ue.GizmoRectangleComponent.md#bapplyimpulseondamage)
- [bAutoActivate](ue_ue.GizmoRectangleComponent.md#bautoactivate)
- [bBatchImpostersAsInstances](ue_ue.GizmoRectangleComponent.md#bbatchimpostersasinstances)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.GizmoRectangleComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.GizmoRectangleComponent.md#bcaneveraffectnavigation)
- [bCastCinematicShadow](ue_ue.GizmoRectangleComponent.md#bcastcinematicshadow)
- [bCastDynamicShadow](ue_ue.GizmoRectangleComponent.md#bcastdynamicshadow)
- [bCastFarShadow](ue_ue.GizmoRectangleComponent.md#bcastfarshadow)
- [bCastHiddenShadow](ue_ue.GizmoRectangleComponent.md#bcasthiddenshadow)
- [bCastInsetShadow](ue_ue.GizmoRectangleComponent.md#bcastinsetshadow)
- [bCastShadowAsTwoSided](ue_ue.GizmoRectangleComponent.md#bcastshadowastwosided)
- [bCastStaticShadow](ue_ue.GizmoRectangleComponent.md#bcaststaticshadow)
- [bCastVolumetricTranslucentShadow](ue_ue.GizmoRectangleComponent.md#bcastvolumetrictranslucentshadow)
- [bComponentToWorldUpdated](ue_ue.GizmoRectangleComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.GizmoRectangleComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.GizmoRectangleComponent.md#beditablewheninherited)
- [bEnableAutoLODGeneration](ue_ue.GizmoRectangleComponent.md#benableautolodgeneration)
- [bExcludeFromLightAttachmentGroup](ue_ue.GizmoRectangleComponent.md#bexcludefromlightattachmentgroup)
- [bForceMipStreaming](ue_ue.GizmoRectangleComponent.md#bforcemipstreaming)
- [bGenerateOverlapEvents](ue_ue.GizmoRectangleComponent.md#bgenerateoverlapevents)
- [bHasCustomNavigableGeometry](ue_ue.GizmoRectangleComponent.md#bhascustomnavigablegeometry)
- [bHasMotionBlurVelocityMeshes](ue_ue.GizmoRectangleComponent.md#bhasmotionblurvelocitymeshes)
- [bHasPerInstanceHitProxies](ue_ue.GizmoRectangleComponent.md#bhasperinstancehitproxies)
- [bHiddenInGame](ue_ue.GizmoRectangleComponent.md#bhiddeningame)
- [bIgnoreRadialForce](ue_ue.GizmoRectangleComponent.md#bignoreradialforce)
- [bIgnoreRadialImpulse](ue_ue.GizmoRectangleComponent.md#bignoreradialimpulse)
- [bInstanceComponent](ue_ue.GizmoRectangleComponent.md#binstancecomponent)
- [bIsActive](ue_ue.GizmoRectangleComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.GizmoRectangleComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.GizmoRectangleComponent.md#bisvisualizationcomponent)
- [bLightAsIfStatic](ue_ue.GizmoRectangleComponent.md#blightasifstatic)
- [bLightAttachmentsAsGroup](ue_ue.GizmoRectangleComponent.md#blightattachmentsasgroup)
- [bMultiBodyOverlap](ue_ue.GizmoRectangleComponent.md#bmultibodyoverlap)
- [bNetAddressable](ue_ue.GizmoRectangleComponent.md#bnetaddressable)
- [bNeverDistanceCull](ue_ue.GizmoRectangleComponent.md#bneverdistancecull)
- [bOnlyOwnerSee](ue_ue.GizmoRectangleComponent.md#bonlyownersee)
- [bOwnerNoSee](ue_ue.GizmoRectangleComponent.md#bownernosee)
- [bReceiveMobileCSMShadows](ue_ue.GizmoRectangleComponent.md#breceivemobilecsmshadows)
- [bReceivesDecals](ue_ue.GizmoRectangleComponent.md#breceivesdecals)
- [bRenderCustomDepth](ue_ue.GizmoRectangleComponent.md#brendercustomdepth)
- [bRenderInDepthPass](ue_ue.GizmoRectangleComponent.md#brenderindepthpass)
- [bRenderInMainPass](ue_ue.GizmoRectangleComponent.md#brenderinmainpass)
- [bReplicatePhysicsToAutonomousProxy](ue_ue.GizmoRectangleComponent.md#breplicatephysicstoautonomousproxy)
- [bReplicates](ue_ue.GizmoRectangleComponent.md#breplicates)
- [bReturnMaterialOnMove](ue_ue.GizmoRectangleComponent.md#breturnmaterialonmove)
- [bSelectable](ue_ue.GizmoRectangleComponent.md#bselectable)
- [bSelfShadowOnly](ue_ue.GizmoRectangleComponent.md#bselfshadowonly)
- [bShouldBeAttached](ue_ue.GizmoRectangleComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.GizmoRectangleComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.GizmoRectangleComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.GizmoRectangleComponent.md#bshouldupdatephysicsvolume)
- [bSingleSampleShadowFromStationaryLights](ue_ue.GizmoRectangleComponent.md#bsinglesampleshadowfromstationarylights)
- [bTraceComplexOnMove](ue_ue.GizmoRectangleComponent.md#btracecomplexonmove)
- [bTreatAsBackgroundForOcclusion](ue_ue.GizmoRectangleComponent.md#btreatasbackgroundforocclusion)
- [bUseAsOccluder](ue_ue.GizmoRectangleComponent.md#buseasoccluder)
- [bUseAttachParentBound](ue_ue.GizmoRectangleComponent.md#buseattachparentbound)
- [bUseEditorCompositing](ue_ue.GizmoRectangleComponent.md#buseeditorcompositing)
- [bUseMaxLODAsImposter](ue_ue.GizmoRectangleComponent.md#busemaxlodasimposter)
- [bUseViewOwnerDepthPriorityGroup](ue_ue.GizmoRectangleComponent.md#buseviewownerdepthprioritygroup)
- [bVisible](ue_ue.GizmoRectangleComponent.md#bvisible)
- [bVisibleInRayTracing](ue_ue.GizmoRectangleComponent.md#bvisibleinraytracing)
- [bVisibleInReflectionCaptures](ue_ue.GizmoRectangleComponent.md#bvisibleinreflectioncaptures)
- [bVisualizeComponent](ue_ue.GizmoRectangleComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.GizmoRectangleComponent.md#activate)
- [AddAngularImpulse](ue_ue.GizmoRectangleComponent.md#addangularimpulse)
- [AddAngularImpulseInDegrees](ue_ue.GizmoRectangleComponent.md#addangularimpulseindegrees)
- [AddAngularImpulseInRadians](ue_ue.GizmoRectangleComponent.md#addangularimpulseinradians)
- [AddForce](ue_ue.GizmoRectangleComponent.md#addforce)
- [AddForceAtLocation](ue_ue.GizmoRectangleComponent.md#addforceatlocation)
- [AddForceAtLocationLocal](ue_ue.GizmoRectangleComponent.md#addforceatlocationlocal)
- [AddImpulse](ue_ue.GizmoRectangleComponent.md#addimpulse)
- [AddImpulseAtLocation](ue_ue.GizmoRectangleComponent.md#addimpulseatlocation)
- [AddRadialForce](ue_ue.GizmoRectangleComponent.md#addradialforce)
- [AddRadialImpulse](ue_ue.GizmoRectangleComponent.md#addradialimpulse)
- [AddTickPrerequisiteActor](ue_ue.GizmoRectangleComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.GizmoRectangleComponent.md#addtickprerequisitecomponent)
- [AddTorque](ue_ue.GizmoRectangleComponent.md#addtorque)
- [AddTorqueInDegrees](ue_ue.GizmoRectangleComponent.md#addtorqueindegrees)
- [AddTorqueInRadians](ue_ue.GizmoRectangleComponent.md#addtorqueinradians)
- [CanCharacterStepUp](ue_ue.GizmoRectangleComponent.md#cancharacterstepup)
- [ClearMoveIgnoreActors](ue_ue.GizmoRectangleComponent.md#clearmoveignoreactors)
- [ClearMoveIgnoreComponents](ue_ue.GizmoRectangleComponent.md#clearmoveignorecomponents)
- [ComponentHasTag](ue_ue.GizmoRectangleComponent.md#componenthastag)
- [CopyArrayOfMoveIgnoreActors](ue_ue.GizmoRectangleComponent.md#copyarrayofmoveignoreactors)
- [CopyArrayOfMoveIgnoreComponents](ue_ue.GizmoRectangleComponent.md#copyarrayofmoveignorecomponents)
- [CreateAndSetMaterialInstanceDynamic](ue_ue.GizmoRectangleComponent.md#createandsetmaterialinstancedynamic)
- [CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.GizmoRectangleComponent.md#createandsetmaterialinstancedynamicfrommaterial)
- [CreateDefaultSubobject](ue_ue.GizmoRectangleComponent.md#createdefaultsubobject)
- [CreateDynamicMaterialInstance](ue_ue.GizmoRectangleComponent.md#createdynamicmaterialinstance)
- [Deactivate](ue_ue.GizmoRectangleComponent.md#deactivate)
- [DetachFromParent](ue_ue.GizmoRectangleComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.GizmoRectangleComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.GizmoRectangleComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.GizmoRectangleComponent.md#getallsocketnames)
- [GetAngularDamping](ue_ue.GizmoRectangleComponent.md#getangulardamping)
- [GetAttachParent](ue_ue.GizmoRectangleComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.GizmoRectangleComponent.md#getattachsocketname)
- [GetCenterOfMass](ue_ue.GizmoRectangleComponent.md#getcenterofmass)
- [GetChildComponent](ue_ue.GizmoRectangleComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.GizmoRectangleComponent.md#getchildrencomponents)
- [GetClass](ue_ue.GizmoRectangleComponent.md#getclass)
- [GetClosestPointOnCollision](ue_ue.GizmoRectangleComponent.md#getclosestpointoncollision)
- [GetCollisionEnabled](ue_ue.GizmoRectangleComponent.md#getcollisionenabled)
- [GetCollisionObjectType](ue_ue.GizmoRectangleComponent.md#getcollisionobjecttype)
- [GetCollisionProfileName](ue_ue.GizmoRectangleComponent.md#getcollisionprofilename)
- [GetCollisionResponseToChannel](ue_ue.GizmoRectangleComponent.md#getcollisionresponsetochannel)
- [GetComponentTickInterval](ue_ue.GizmoRectangleComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.GizmoRectangleComponent.md#getcomponentvelocity)
- [GetForwardVector](ue_ue.GizmoRectangleComponent.md#getforwardvector)
- [GetGenerateOverlapEvents](ue_ue.GizmoRectangleComponent.md#getgenerateoverlapevents)
- [GetInertiaTensor](ue_ue.GizmoRectangleComponent.md#getinertiatensor)
- [GetLinearDamping](ue_ue.GizmoRectangleComponent.md#getlineardamping)
- [GetMass](ue_ue.GizmoRectangleComponent.md#getmass)
- [GetMassScale](ue_ue.GizmoRectangleComponent.md#getmassscale)
- [GetMaterial](ue_ue.GizmoRectangleComponent.md#getmaterial)
- [GetMaterialFromCollisionFaceIndex](ue_ue.GizmoRectangleComponent.md#getmaterialfromcollisionfaceindex)
- [GetName](ue_ue.GizmoRectangleComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.GizmoRectangleComponent.md#getnumchildrencomponents)
- [GetNumMaterials](ue_ue.GizmoRectangleComponent.md#getnummaterials)
- [GetOuter](ue_ue.GizmoRectangleComponent.md#getouter)
- [GetOverlappingActors](ue_ue.GizmoRectangleComponent.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.GizmoRectangleComponent.md#getoverlappingcomponents)
- [GetOwner](ue_ue.GizmoRectangleComponent.md#getowner)
- [GetParentComponents](ue_ue.GizmoRectangleComponent.md#getparentcomponents)
- [GetPhysicsAngularVelocity](ue_ue.GizmoRectangleComponent.md#getphysicsangularvelocity)
- [GetPhysicsAngularVelocityInDegrees](ue_ue.GizmoRectangleComponent.md#getphysicsangularvelocityindegrees)
- [GetPhysicsAngularVelocityInRadians](ue_ue.GizmoRectangleComponent.md#getphysicsangularvelocityinradians)
- [GetPhysicsLinearVelocity](ue_ue.GizmoRectangleComponent.md#getphysicslinearvelocity)
- [GetPhysicsLinearVelocityAtPoint](ue_ue.GizmoRectangleComponent.md#getphysicslinearvelocityatpoint)
- [GetPhysicsVolume](ue_ue.GizmoRectangleComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.GizmoRectangleComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.GizmoRectangleComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.GizmoRectangleComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.GizmoRectangleComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.GizmoRectangleComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.GizmoRectangleComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.GizmoRectangleComponent.md#getsockettransform)
- [GetUpVector](ue_ue.GizmoRectangleComponent.md#getupvector)
- [GetWalkableSlopeOverride](ue_ue.GizmoRectangleComponent.md#getwalkableslopeoverride)
- [GetWorld](ue_ue.GizmoRectangleComponent.md#getworld)
- [IgnoreActorWhenMoving](ue_ue.GizmoRectangleComponent.md#ignoreactorwhenmoving)
- [IgnoreComponentWhenMoving](ue_ue.GizmoRectangleComponent.md#ignorecomponentwhenmoving)
- [IsActive](ue_ue.GizmoRectangleComponent.md#isactive)
- [IsAnyRigidBodyAwake](ue_ue.GizmoRectangleComponent.md#isanyrigidbodyawake)
- [IsAnySimulatingPhysics](ue_ue.GizmoRectangleComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.GizmoRectangleComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.GizmoRectangleComponent.md#iscomponenttickenabled)
- [IsGravityEnabled](ue_ue.GizmoRectangleComponent.md#isgravityenabled)
- [IsOverlappingActor](ue_ue.GizmoRectangleComponent.md#isoverlappingactor)
- [IsOverlappingComponent](ue_ue.GizmoRectangleComponent.md#isoverlappingcomponent)
- [IsSimulatingPhysics](ue_ue.GizmoRectangleComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.GizmoRectangleComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.GizmoRectangleComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.GizmoRectangleComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.GizmoRectangleComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.GizmoRectangleComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.GizmoRectangleComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.GizmoRectangleComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.GizmoRectangleComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.GizmoRectangleComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.GizmoRectangleComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.GizmoRectangleComponent.md#k2_attachtocomponent)
- [K2\_BoxOverlapComponent](ue_ue.GizmoRectangleComponent.md#k2_boxoverlapcomponent)
- [K2\_DestroyComponent](ue_ue.GizmoRectangleComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.GizmoRectangleComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.GizmoRectangleComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.GizmoRectangleComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.GizmoRectangleComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.GizmoRectangleComponent.md#k2_getcomponenttoworld)
- [K2\_IsCollisionEnabled](ue_ue.GizmoRectangleComponent.md#k2_iscollisionenabled)
- [K2\_IsPhysicsCollisionEnabled](ue_ue.GizmoRectangleComponent.md#k2_isphysicscollisionenabled)
- [K2\_IsQueryCollisionEnabled](ue_ue.GizmoRectangleComponent.md#k2_isquerycollisionenabled)
- [K2\_LineTraceComponent](ue_ue.GizmoRectangleComponent.md#k2_linetracecomponent)
- [K2\_SetRelativeLocation](ue_ue.GizmoRectangleComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.GizmoRectangleComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.GizmoRectangleComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.GizmoRectangleComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.GizmoRectangleComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.GizmoRectangleComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.GizmoRectangleComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.GizmoRectangleComponent.md#k2_setworldtransform)
- [K2\_SphereOverlapComponent](ue_ue.GizmoRectangleComponent.md#k2_sphereoverlapcomponent)
- [K2\_SphereTraceComponent](ue_ue.GizmoRectangleComponent.md#k2_spheretracecomponent)
- [OnRep\_AttachChildren](ue_ue.GizmoRectangleComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.GizmoRectangleComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.GizmoRectangleComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.GizmoRectangleComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.GizmoRectangleComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.GizmoRectangleComponent.md#onrep_visibility)
- [PutRigidBodyToSleep](ue_ue.GizmoRectangleComponent.md#putrigidbodytosleep)
- [ReceiveBeginPlay](ue_ue.GizmoRectangleComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.GizmoRectangleComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.GizmoRectangleComponent.md#receivetick)
- [RegisterComponent](ue_ue.GizmoRectangleComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.GizmoRectangleComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.GizmoRectangleComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.GizmoRectangleComponent.md#resetrelativetransform)
- [ScaleByMomentOfInertia](ue_ue.GizmoRectangleComponent.md#scalebymomentofinertia)
- [SetAbsolute](ue_ue.GizmoRectangleComponent.md#setabsolute)
- [SetActive](ue_ue.GizmoRectangleComponent.md#setactive)
- [SetAllMassScale](ue_ue.GizmoRectangleComponent.md#setallmassscale)
- [SetAllPhysicsAngularVelocityInDegrees](ue_ue.GizmoRectangleComponent.md#setallphysicsangularvelocityindegrees)
- [SetAllPhysicsAngularVelocityInRadians](ue_ue.GizmoRectangleComponent.md#setallphysicsangularvelocityinradians)
- [SetAllPhysicsLinearVelocity](ue_ue.GizmoRectangleComponent.md#setallphysicslinearvelocity)
- [SetAllUseCCD](ue_ue.GizmoRectangleComponent.md#setalluseccd)
- [SetAngularDamping](ue_ue.GizmoRectangleComponent.md#setangulardamping)
- [SetAutoActivate](ue_ue.GizmoRectangleComponent.md#setautoactivate)
- [SetBoundsScale](ue_ue.GizmoRectangleComponent.md#setboundsscale)
- [SetCastInsetShadow](ue_ue.GizmoRectangleComponent.md#setcastinsetshadow)
- [SetCastShadow](ue_ue.GizmoRectangleComponent.md#setcastshadow)
- [SetCenterOfMass](ue_ue.GizmoRectangleComponent.md#setcenterofmass)
- [SetCollisionEnabled](ue_ue.GizmoRectangleComponent.md#setcollisionenabled)
- [SetCollisionObjectType](ue_ue.GizmoRectangleComponent.md#setcollisionobjecttype)
- [SetCollisionProfileName](ue_ue.GizmoRectangleComponent.md#setcollisionprofilename)
- [SetCollisionResponseToAllChannels](ue_ue.GizmoRectangleComponent.md#setcollisionresponsetoallchannels)
- [SetCollisionResponseToChannel](ue_ue.GizmoRectangleComponent.md#setcollisionresponsetochannel)
- [SetComponentTickEnabled](ue_ue.GizmoRectangleComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.GizmoRectangleComponent.md#setcomponenttickinterval)
- [SetConstraintMode](ue_ue.GizmoRectangleComponent.md#setconstraintmode)
- [SetCullDistance](ue_ue.GizmoRectangleComponent.md#setculldistance)
- [SetCustomDepthStencilValue](ue_ue.GizmoRectangleComponent.md#setcustomdepthstencilvalue)
- [SetCustomDepthStencilWriteMask](ue_ue.GizmoRectangleComponent.md#setcustomdepthstencilwritemask)
- [SetCustomPrimitiveDataFloat](ue_ue.GizmoRectangleComponent.md#setcustomprimitivedatafloat)
- [SetCustomPrimitiveDataVector2](ue_ue.GizmoRectangleComponent.md#setcustomprimitivedatavector2)
- [SetCustomPrimitiveDataVector3](ue_ue.GizmoRectangleComponent.md#setcustomprimitivedatavector3)
- [SetCustomPrimitiveDataVector4](ue_ue.GizmoRectangleComponent.md#setcustomprimitivedatavector4)
- [SetEnableGravity](ue_ue.GizmoRectangleComponent.md#setenablegravity)
- [SetExcludeFromLightAttachmentGroup](ue_ue.GizmoRectangleComponent.md#setexcludefromlightattachmentgroup)
- [SetGenerateOverlapEvents](ue_ue.GizmoRectangleComponent.md#setgenerateoverlapevents)
- [SetHiddenInGame](ue_ue.GizmoRectangleComponent.md#sethiddeningame)
- [SetIsReplicated](ue_ue.GizmoRectangleComponent.md#setisreplicated)
- [SetLightAttachmentsAsGroup](ue_ue.GizmoRectangleComponent.md#setlightattachmentsasgroup)
- [SetLinearDamping](ue_ue.GizmoRectangleComponent.md#setlineardamping)
- [SetMassOverrideInKg](ue_ue.GizmoRectangleComponent.md#setmassoverrideinkg)
- [SetMassScale](ue_ue.GizmoRectangleComponent.md#setmassscale)
- [SetMaterial](ue_ue.GizmoRectangleComponent.md#setmaterial)
- [SetMaterialByName](ue_ue.GizmoRectangleComponent.md#setmaterialbyname)
- [SetMobility](ue_ue.GizmoRectangleComponent.md#setmobility)
- [SetNotifyRigidBodyCollision](ue_ue.GizmoRectangleComponent.md#setnotifyrigidbodycollision)
- [SetOnlyOwnerSee](ue_ue.GizmoRectangleComponent.md#setonlyownersee)
- [SetOwnerNoSee](ue_ue.GizmoRectangleComponent.md#setownernosee)
- [SetPhysMaterialOverride](ue_ue.GizmoRectangleComponent.md#setphysmaterialoverride)
- [SetPhysicsAngularVelocity](ue_ue.GizmoRectangleComponent.md#setphysicsangularvelocity)
- [SetPhysicsAngularVelocityInDegrees](ue_ue.GizmoRectangleComponent.md#setphysicsangularvelocityindegrees)
- [SetPhysicsAngularVelocityInRadians](ue_ue.GizmoRectangleComponent.md#setphysicsangularvelocityinradians)
- [SetPhysicsLinearVelocity](ue_ue.GizmoRectangleComponent.md#setphysicslinearvelocity)
- [SetPhysicsMaxAngularVelocity](ue_ue.GizmoRectangleComponent.md#setphysicsmaxangularvelocity)
- [SetPhysicsMaxAngularVelocityInDegrees](ue_ue.GizmoRectangleComponent.md#setphysicsmaxangularvelocityindegrees)
- [SetPhysicsMaxAngularVelocityInRadians](ue_ue.GizmoRectangleComponent.md#setphysicsmaxangularvelocityinradians)
- [SetReceivesDecals](ue_ue.GizmoRectangleComponent.md#setreceivesdecals)
- [SetRelativeScale3D](ue_ue.GizmoRectangleComponent.md#setrelativescale3d)
- [SetRenderCustomDepth](ue_ue.GizmoRectangleComponent.md#setrendercustomdepth)
- [SetRenderInMainPass](ue_ue.GizmoRectangleComponent.md#setrenderinmainpass)
- [SetShouldUpdatePhysicsVolume](ue_ue.GizmoRectangleComponent.md#setshouldupdatephysicsvolume)
- [SetSimulatePhysics](ue_ue.GizmoRectangleComponent.md#setsimulatephysics)
- [SetSingleSampleShadowFromStationaryLights](ue_ue.GizmoRectangleComponent.md#setsinglesampleshadowfromstationarylights)
- [SetTickGroup](ue_ue.GizmoRectangleComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.GizmoRectangleComponent.md#settickablewhenpaused)
- [SetTranslucentSortPriority](ue_ue.GizmoRectangleComponent.md#settranslucentsortpriority)
- [SetUseCCD](ue_ue.GizmoRectangleComponent.md#setuseccd)
- [SetVisibility](ue_ue.GizmoRectangleComponent.md#setvisibility)
- [SetWalkableSlopeOverride](ue_ue.GizmoRectangleComponent.md#setwalkableslopeoverride)
- [SetWorldScale3D](ue_ue.GizmoRectangleComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.GizmoRectangleComponent.md#setupattachment)
- [SnapTo](ue_ue.GizmoRectangleComponent.md#snapto)
- [ToggleActive](ue_ue.GizmoRectangleComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.GizmoRectangleComponent.md#togglevisibility)
- [UpdateHoverState](ue_ue.GizmoRectangleComponent.md#updatehoverstate)
- [UpdateWorldLocalState](ue_ue.GizmoRectangleComponent.md#updateworldlocalstate)
- [WakeAllRigidBodies](ue_ue.GizmoRectangleComponent.md#wakeallrigidbodies)
- [WakeRigidBody](ue_ue.GizmoRectangleComponent.md#wakerigidbody)
- [Find](ue_ue.GizmoRectangleComponent.md#find)
- [Load](ue_ue.GizmoRectangleComponent.md#load)
- [StaticClass](ue_ue.GizmoRectangleComponent.md#staticclass)

## Constructors

### constructor

• **new GizmoRectangleComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[constructor](ue_ue.GizmoBaseComponent.md#constructor)

## Properties

### AlwaysLoadOnClient

• **AlwaysLoadOnClient**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AlwaysLoadOnClient](ue_ue.GizmoBaseComponent.md#alwaysloadonclient)

___

### AlwaysLoadOnServer

• **AlwaysLoadOnServer**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AlwaysLoadOnServer](ue_ue.GizmoBaseComponent.md#alwaysloadonserver)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AssetUserData](ue_ue.GizmoBaseComponent.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AttachChildren](ue_ue.GizmoBaseComponent.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AttachParent](ue_ue.GizmoBaseComponent.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AttachSocketName](ue_ue.GizmoBaseComponent.md#attachsocketname)

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[BodyInstance](ue_ue.GizmoBaseComponent.md#bodyinstance)

___

### BoundsScale

• **BoundsScale**: `number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[BoundsScale](ue_ue.GizmoBaseComponent.md#boundsscale)

___

### CachedMaxDrawDistance

• **CachedMaxDrawDistance**: `number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[CachedMaxDrawDistance](ue_ue.GizmoBaseComponent.md#cachedmaxdrawdistance)

___

### CanBeCharacterBase

• **CanBeCharacterBase**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[CanBeCharacterBase](ue_ue.GizmoBaseComponent.md#canbecharacterbase)

___

### CanCharacterStepUpOn

• **CanCharacterStepUpOn**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[CanCharacterStepUpOn](ue_ue.GizmoBaseComponent.md#cancharacterstepupon)

___

### CastShadow

• **CastShadow**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[CastShadow](ue_ue.GizmoBaseComponent.md#castshadow)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[ClientAttachedChildren](ue_ue.GizmoBaseComponent.md#clientattachedchildren)

___

### Color

• **Color**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[Color](ue_ue.GizmoBaseComponent.md#color)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[ComponentTags](ue_ue.GizmoBaseComponent.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[ComponentVelocity](ue_ue.GizmoBaseComponent.md#componentvelocity)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[CreationMethod](ue_ue.GizmoBaseComponent.md#creationmethod)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[CustomDepthStencilValue](ue_ue.GizmoBaseComponent.md#customdepthstencilvalue)

___

### CustomDepthStencilWriteMask

• **CustomDepthStencilWriteMask**: [`ERendererStencilMask`](../enums/ue_ue.ERendererStencilMask.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[CustomDepthStencilWriteMask](ue_ue.GizmoBaseComponent.md#customdepthstencilwritemask)

___

### CustomPrimitiveData

• **CustomPrimitiveData**: [`CustomPrimitiveData`](ue_ue.CustomPrimitiveData.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[CustomPrimitiveData](ue_ue.GizmoBaseComponent.md#customprimitivedata)

___

### DepthPriorityGroup

• **DepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[DepthPriorityGroup](ue_ue.GizmoBaseComponent.md#depthprioritygroup)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[DetailMode](ue_ue.GizmoBaseComponent.md#detailmode)

___

### DirectionX

• **DirectionX**: [`Vector`](ue_ue_s.Vector.md)

___

### DirectionY

• **DirectionY**: [`Vector`](ue_ue_s.Vector.md)

___

### ExcludeForSpecificHLODLevels

• **ExcludeForSpecificHLODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[ExcludeForSpecificHLODLevels](ue_ue.GizmoBaseComponent.md#excludeforspecifichlodlevels)

___

### HoverSizeMultiplier

• **HoverSizeMultiplier**: `number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[HoverSizeMultiplier](ue_ue.GizmoBaseComponent.md#hoversizemultiplier)

___

### IndirectLightingCacheQuality

• **IndirectLightingCacheQuality**: [`EIndirectLightingCacheQuality`](../enums/ue_ue.EIndirectLightingCacheQuality.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[IndirectLightingCacheQuality](ue_ue.GizmoBaseComponent.md#indirectlightingcachequality)

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[LDMaxDrawDistance](ue_ue.GizmoBaseComponent.md#ldmaxdrawdistance)

___

### LODParentPrimitive

• **LODParentPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[LODParentPrimitive](ue_ue.GizmoBaseComponent.md#lodparentprimitive)

___

### LengthX

• **LengthX**: `number`

___

### LengthY

• **LengthY**: `number`

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[LightingChannels](ue_ue.GizmoBaseComponent.md#lightingchannels)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[LightmapType](ue_ue.GizmoBaseComponent.md#lightmaptype)

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[LpvBiasMultiplier](ue_ue.GizmoBaseComponent.md#lpvbiasmultiplier)

___

### MinDrawDistance

• **MinDrawDistance**: `number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[MinDrawDistance](ue_ue.GizmoBaseComponent.md#mindrawdistance)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[Mobility](ue_ue.GizmoBaseComponent.md#mobility)

___

### MoveIgnoreActors

• **MoveIgnoreActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[MoveIgnoreActors](ue_ue.GizmoBaseComponent.md#moveignoreactors)

___

### MoveIgnoreComponents

• **MoveIgnoreComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[MoveIgnoreComponents](ue_ue.GizmoBaseComponent.md#moveignorecomponents)

___

### OffsetX

• **OffsetX**: `number`

___

### OffsetY

• **OffsetY**: `number`

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnBeginCursorOver](ue_ue.GizmoBaseComponent.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnClicked](ue_ue.GizmoBaseComponent.md#onclicked)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnComponentActivated](ue_ue.GizmoBaseComponent.md#oncomponentactivated)

___

### OnComponentBeginOverlap

• **OnComponentBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`, `bFromSweep`: `boolean`, `SweepResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnComponentBeginOverlap](ue_ue.GizmoBaseComponent.md#oncomponentbeginoverlap)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnComponentDeactivated](ue_ue.GizmoBaseComponent.md#oncomponentdeactivated)

___

### OnComponentEndOverlap

• **OnComponentEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`) => `void`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnComponentEndOverlap](ue_ue.GizmoBaseComponent.md#oncomponentendoverlap)

___

### OnComponentHit

• **OnComponentHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`HitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnComponentHit](ue_ue.GizmoBaseComponent.md#oncomponenthit)

___

### OnComponentSleep

• **OnComponentSleep**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SleepingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnComponentSleep](ue_ue.GizmoBaseComponent.md#oncomponentsleep)

___

### OnComponentWake

• **OnComponentWake**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`WakingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnComponentWake](ue_ue.GizmoBaseComponent.md#oncomponentwake)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnEndCursorOver](ue_ue.GizmoBaseComponent.md#onendcursorover)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnInputTouchBegin](ue_ue.GizmoBaseComponent.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnInputTouchEnd](ue_ue.GizmoBaseComponent.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnInputTouchEnter](ue_ue.GizmoBaseComponent.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnInputTouchLeave](ue_ue.GizmoBaseComponent.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnReleased](ue_ue.GizmoBaseComponent.md#onreleased)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[PhysicsVolume](ue_ue.GizmoBaseComponent.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.GizmoBaseComponent.md#physicsvolumechangeddelegate)

___

### PixelHitDistanceThreshold

• **PixelHitDistanceThreshold**: `number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[PixelHitDistanceThreshold](ue_ue.GizmoBaseComponent.md#pixelhitdistancethreshold)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[PrimaryComponentTick](ue_ue.GizmoBaseComponent.md#primarycomponenttick)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[RelativeLocation](ue_ue.GizmoBaseComponent.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[RelativeRotation](ue_ue.GizmoBaseComponent.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[RelativeScale3D](ue_ue.GizmoBaseComponent.md#relativescale3d)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[RuntimeVirtualTextures](ue_ue.GizmoBaseComponent.md#runtimevirtualtextures)

___

### Thickness

• **Thickness**: `number`

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[TranslucencySortPriority](ue_ue.GizmoBaseComponent.md#translucencysortpriority)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[UCSModifiedProperties](ue_ue.GizmoBaseComponent.md#ucsmodifiedproperties)

___

### ViewOwnerDepthPriorityGroup

• **ViewOwnerDepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[ViewOwnerDepthPriorityGroup](ue_ue.GizmoBaseComponent.md#viewownerdepthprioritygroup)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[VirtualTextureCullMips](ue_ue.GizmoBaseComponent.md#virtualtexturecullmips)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[VirtualTextureLodBias](ue_ue.GizmoBaseComponent.md#virtualtexturelodbias)

___

### VirtualTextureMinCoverage

• **VirtualTextureMinCoverage**: `number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[VirtualTextureMinCoverage](ue_ue.GizmoBaseComponent.md#virtualtexturemincoverage)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[VirtualTextureRenderPassType](ue_ue.GizmoBaseComponent.md#virtualtexturerenderpasstype)

___

### VisibilityId

• **VisibilityId**: `number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[VisibilityId](ue_ue.GizmoBaseComponent.md#visibilityid)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[__tid_ActorComponent__](ue_ue.GizmoBaseComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_GizmoBaseComponent\_\_

• **\_\_tid\_GizmoBaseComponent\_\_**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[__tid_GizmoBaseComponent__](ue_ue.GizmoBaseComponent.md#__tid_gizmobasecomponent__)

___

### \_\_tid\_GizmoRectangleComponent\_\_

• **\_\_tid\_GizmoRectangleComponent\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[__tid_Object__](ue_ue.GizmoBaseComponent.md#__tid_object__)

___

### \_\_tid\_PrimitiveComponent\_\_

• **\_\_tid\_PrimitiveComponent\_\_**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[__tid_PrimitiveComponent__](ue_ue.GizmoBaseComponent.md#__tid_primitivecomponent__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[__tid_SceneComponent__](ue_ue.GizmoBaseComponent.md#__tid_scenecomponent__)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bAbsoluteLocation](ue_ue.GizmoBaseComponent.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bAbsoluteRotation](ue_ue.GizmoBaseComponent.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bAbsoluteScale](ue_ue.GizmoBaseComponent.md#babsolutescale)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bAffectDistanceFieldLighting](ue_ue.GizmoBaseComponent.md#baffectdistancefieldlighting)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bAffectDynamicIndirectLighting](ue_ue.GizmoBaseComponent.md#baffectdynamicindirectlighting)

___

### bAllowCullDistanceVolume

• **bAllowCullDistanceVolume**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bAllowCullDistanceVolume](ue_ue.GizmoBaseComponent.md#ballowculldistancevolume)

___

### bAlwaysCreatePhysicsState

• **bAlwaysCreatePhysicsState**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bAlwaysCreatePhysicsState](ue_ue.GizmoBaseComponent.md#balwayscreatephysicsstate)

___

### bApplyImpulseOnDamage

• **bApplyImpulseOnDamage**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bApplyImpulseOnDamage](ue_ue.GizmoBaseComponent.md#bapplyimpulseondamage)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bAutoActivate](ue_ue.GizmoBaseComponent.md#bautoactivate)

___

### bBatchImpostersAsInstances

• **bBatchImpostersAsInstances**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bBatchImpostersAsInstances](ue_ue.GizmoBaseComponent.md#bbatchimpostersasinstances)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.GizmoBaseComponent.md#bboundschangetriggersstreamingdatarebuild)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bCanEverAffectNavigation](ue_ue.GizmoBaseComponent.md#bcaneveraffectnavigation)

___

### bCastCinematicShadow

• **bCastCinematicShadow**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bCastCinematicShadow](ue_ue.GizmoBaseComponent.md#bcastcinematicshadow)

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bCastDynamicShadow](ue_ue.GizmoBaseComponent.md#bcastdynamicshadow)

___

### bCastFarShadow

• **bCastFarShadow**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bCastFarShadow](ue_ue.GizmoBaseComponent.md#bcastfarshadow)

___

### bCastHiddenShadow

• **bCastHiddenShadow**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bCastHiddenShadow](ue_ue.GizmoBaseComponent.md#bcasthiddenshadow)

___

### bCastInsetShadow

• **bCastInsetShadow**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bCastInsetShadow](ue_ue.GizmoBaseComponent.md#bcastinsetshadow)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bCastShadowAsTwoSided](ue_ue.GizmoBaseComponent.md#bcastshadowastwosided)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bCastStaticShadow](ue_ue.GizmoBaseComponent.md#bcaststaticshadow)

___

### bCastVolumetricTranslucentShadow

• **bCastVolumetricTranslucentShadow**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bCastVolumetricTranslucentShadow](ue_ue.GizmoBaseComponent.md#bcastvolumetrictranslucentshadow)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bComponentToWorldUpdated](ue_ue.GizmoBaseComponent.md#bcomponenttoworldupdated)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bCreatedByConstructionScript](ue_ue.GizmoBaseComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bEditableWhenInherited](ue_ue.GizmoBaseComponent.md#beditablewheninherited)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bEnableAutoLODGeneration](ue_ue.GizmoBaseComponent.md#benableautolodgeneration)

___

### bExcludeFromLightAttachmentGroup

• **bExcludeFromLightAttachmentGroup**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bExcludeFromLightAttachmentGroup](ue_ue.GizmoBaseComponent.md#bexcludefromlightattachmentgroup)

___

### bForceMipStreaming

• **bForceMipStreaming**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bForceMipStreaming](ue_ue.GizmoBaseComponent.md#bforcemipstreaming)

___

### bGenerateOverlapEvents

• **bGenerateOverlapEvents**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bGenerateOverlapEvents](ue_ue.GizmoBaseComponent.md#bgenerateoverlapevents)

___

### bHasCustomNavigableGeometry

• **bHasCustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bHasCustomNavigableGeometry](ue_ue.GizmoBaseComponent.md#bhascustomnavigablegeometry)

___

### bHasMotionBlurVelocityMeshes

• **bHasMotionBlurVelocityMeshes**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bHasMotionBlurVelocityMeshes](ue_ue.GizmoBaseComponent.md#bhasmotionblurvelocitymeshes)

___

### bHasPerInstanceHitProxies

• **bHasPerInstanceHitProxies**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bHasPerInstanceHitProxies](ue_ue.GizmoBaseComponent.md#bhasperinstancehitproxies)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bHiddenInGame](ue_ue.GizmoBaseComponent.md#bhiddeningame)

___

### bIgnoreRadialForce

• **bIgnoreRadialForce**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bIgnoreRadialForce](ue_ue.GizmoBaseComponent.md#bignoreradialforce)

___

### bIgnoreRadialImpulse

• **bIgnoreRadialImpulse**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bIgnoreRadialImpulse](ue_ue.GizmoBaseComponent.md#bignoreradialimpulse)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bInstanceComponent](ue_ue.GizmoBaseComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bIsActive](ue_ue.GizmoBaseComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bIsEditorOnly](ue_ue.GizmoBaseComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bIsVisualizationComponent](ue_ue.GizmoBaseComponent.md#bisvisualizationcomponent)

___

### bLightAsIfStatic

• **bLightAsIfStatic**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bLightAsIfStatic](ue_ue.GizmoBaseComponent.md#blightasifstatic)

___

### bLightAttachmentsAsGroup

• **bLightAttachmentsAsGroup**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bLightAttachmentsAsGroup](ue_ue.GizmoBaseComponent.md#blightattachmentsasgroup)

___

### bMultiBodyOverlap

• **bMultiBodyOverlap**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bMultiBodyOverlap](ue_ue.GizmoBaseComponent.md#bmultibodyoverlap)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bNetAddressable](ue_ue.GizmoBaseComponent.md#bnetaddressable)

___

### bNeverDistanceCull

• **bNeverDistanceCull**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bNeverDistanceCull](ue_ue.GizmoBaseComponent.md#bneverdistancecull)

___

### bOnlyOwnerSee

• **bOnlyOwnerSee**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bOnlyOwnerSee](ue_ue.GizmoBaseComponent.md#bonlyownersee)

___

### bOwnerNoSee

• **bOwnerNoSee**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bOwnerNoSee](ue_ue.GizmoBaseComponent.md#bownernosee)

___

### bReceiveMobileCSMShadows

• **bReceiveMobileCSMShadows**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bReceiveMobileCSMShadows](ue_ue.GizmoBaseComponent.md#breceivemobilecsmshadows)

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bReceivesDecals](ue_ue.GizmoBaseComponent.md#breceivesdecals)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bRenderCustomDepth](ue_ue.GizmoBaseComponent.md#brendercustomdepth)

___

### bRenderInDepthPass

• **bRenderInDepthPass**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bRenderInDepthPass](ue_ue.GizmoBaseComponent.md#brenderindepthpass)

___

### bRenderInMainPass

• **bRenderInMainPass**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bRenderInMainPass](ue_ue.GizmoBaseComponent.md#brenderinmainpass)

___

### bReplicatePhysicsToAutonomousProxy

• **bReplicatePhysicsToAutonomousProxy**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bReplicatePhysicsToAutonomousProxy](ue_ue.GizmoBaseComponent.md#breplicatephysicstoautonomousproxy)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bReplicates](ue_ue.GizmoBaseComponent.md#breplicates)

___

### bReturnMaterialOnMove

• **bReturnMaterialOnMove**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bReturnMaterialOnMove](ue_ue.GizmoBaseComponent.md#breturnmaterialonmove)

___

### bSelectable

• **bSelectable**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bSelectable](ue_ue.GizmoBaseComponent.md#bselectable)

___

### bSelfShadowOnly

• **bSelfShadowOnly**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bSelfShadowOnly](ue_ue.GizmoBaseComponent.md#bselfshadowonly)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bShouldBeAttached](ue_ue.GizmoBaseComponent.md#bshouldbeattached)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.GizmoBaseComponent.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.GizmoBaseComponent.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.GizmoBaseComponent.md#bshouldupdatephysicsvolume)

___

### bSingleSampleShadowFromStationaryLights

• **bSingleSampleShadowFromStationaryLights**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bSingleSampleShadowFromStationaryLights](ue_ue.GizmoBaseComponent.md#bsinglesampleshadowfromstationarylights)

___

### bTraceComplexOnMove

• **bTraceComplexOnMove**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bTraceComplexOnMove](ue_ue.GizmoBaseComponent.md#btracecomplexonmove)

___

### bTreatAsBackgroundForOcclusion

• **bTreatAsBackgroundForOcclusion**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bTreatAsBackgroundForOcclusion](ue_ue.GizmoBaseComponent.md#btreatasbackgroundforocclusion)

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bUseAsOccluder](ue_ue.GizmoBaseComponent.md#buseasoccluder)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bUseAttachParentBound](ue_ue.GizmoBaseComponent.md#buseattachparentbound)

___

### bUseEditorCompositing

• **bUseEditorCompositing**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bUseEditorCompositing](ue_ue.GizmoBaseComponent.md#buseeditorcompositing)

___

### bUseMaxLODAsImposter

• **bUseMaxLODAsImposter**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bUseMaxLODAsImposter](ue_ue.GizmoBaseComponent.md#busemaxlodasimposter)

___

### bUseViewOwnerDepthPriorityGroup

• **bUseViewOwnerDepthPriorityGroup**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bUseViewOwnerDepthPriorityGroup](ue_ue.GizmoBaseComponent.md#buseviewownerdepthprioritygroup)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bVisible](ue_ue.GizmoBaseComponent.md#bvisible)

___

### bVisibleInRayTracing

• **bVisibleInRayTracing**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bVisibleInRayTracing](ue_ue.GizmoBaseComponent.md#bvisibleinraytracing)

___

### bVisibleInReflectionCaptures

• **bVisibleInReflectionCaptures**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bVisibleInReflectionCaptures](ue_ue.GizmoBaseComponent.md#bvisibleinreflectioncaptures)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[bVisualizeComponent](ue_ue.GizmoBaseComponent.md#bvisualizecomponent)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[Activate](ue_ue.GizmoBaseComponent.md#activate)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AddAngularImpulse](ue_ue.GizmoBaseComponent.md#addangularimpulse)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AddAngularImpulseInDegrees](ue_ue.GizmoBaseComponent.md#addangularimpulseindegrees)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AddAngularImpulseInRadians](ue_ue.GizmoBaseComponent.md#addangularimpulseinradians)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AddForce](ue_ue.GizmoBaseComponent.md#addforce)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AddForceAtLocation](ue_ue.GizmoBaseComponent.md#addforceatlocation)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AddForceAtLocationLocal](ue_ue.GizmoBaseComponent.md#addforceatlocationlocal)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AddImpulse](ue_ue.GizmoBaseComponent.md#addimpulse)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AddImpulseAtLocation](ue_ue.GizmoBaseComponent.md#addimpulseatlocation)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AddRadialForce](ue_ue.GizmoBaseComponent.md#addradialforce)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AddRadialImpulse](ue_ue.GizmoBaseComponent.md#addradialimpulse)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AddTickPrerequisiteActor](ue_ue.GizmoBaseComponent.md#addtickprerequisiteactor)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AddTickPrerequisiteComponent](ue_ue.GizmoBaseComponent.md#addtickprerequisitecomponent)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AddTorque](ue_ue.GizmoBaseComponent.md#addtorque)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AddTorqueInDegrees](ue_ue.GizmoBaseComponent.md#addtorqueindegrees)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[AddTorqueInRadians](ue_ue.GizmoBaseComponent.md#addtorqueinradians)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[CanCharacterStepUp](ue_ue.GizmoBaseComponent.md#cancharacterstepup)

___

### ClearMoveIgnoreActors

▸ **ClearMoveIgnoreActors**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[ClearMoveIgnoreActors](ue_ue.GizmoBaseComponent.md#clearmoveignoreactors)

___

### ClearMoveIgnoreComponents

▸ **ClearMoveIgnoreComponents**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[ClearMoveIgnoreComponents](ue_ue.GizmoBaseComponent.md#clearmoveignorecomponents)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[ComponentHasTag](ue_ue.GizmoBaseComponent.md#componenthastag)

___

### CopyArrayOfMoveIgnoreActors

▸ **CopyArrayOfMoveIgnoreActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[CopyArrayOfMoveIgnoreActors](ue_ue.GizmoBaseComponent.md#copyarrayofmoveignoreactors)

___

### CopyArrayOfMoveIgnoreComponents

▸ **CopyArrayOfMoveIgnoreComponents**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[CopyArrayOfMoveIgnoreComponents](ue_ue.GizmoBaseComponent.md#copyarrayofmoveignorecomponents)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[CreateAndSetMaterialInstanceDynamic](ue_ue.GizmoBaseComponent.md#createandsetmaterialinstancedynamic)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.GizmoBaseComponent.md#createandsetmaterialinstancedynamicfrommaterial)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[CreateDefaultSubobject](ue_ue.GizmoBaseComponent.md#createdefaultsubobject)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[CreateDynamicMaterialInstance](ue_ue.GizmoBaseComponent.md#createdynamicmaterialinstance)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[Deactivate](ue_ue.GizmoBaseComponent.md#deactivate)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[DetachFromParent](ue_ue.GizmoBaseComponent.md#detachfromparent)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[DoesSocketExist](ue_ue.GizmoBaseComponent.md#doessocketexist)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[ExecuteUbergraph](ue_ue.GizmoBaseComponent.md#executeubergraph)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetAllSocketNames](ue_ue.GizmoBaseComponent.md#getallsocketnames)

___

### GetAngularDamping

▸ **GetAngularDamping**(): `number`

#### Returns

`number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetAngularDamping](ue_ue.GizmoBaseComponent.md#getangulardamping)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetAttachParent](ue_ue.GizmoBaseComponent.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetAttachSocketName](ue_ue.GizmoBaseComponent.md#getattachsocketname)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetCenterOfMass](ue_ue.GizmoBaseComponent.md#getcenterofmass)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetChildComponent](ue_ue.GizmoBaseComponent.md#getchildcomponent)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetChildrenComponents](ue_ue.GizmoBaseComponent.md#getchildrencomponents)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetClass](ue_ue.GizmoBaseComponent.md#getclass)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetClosestPointOnCollision](ue_ue.GizmoBaseComponent.md#getclosestpointoncollision)

___

### GetCollisionEnabled

▸ **GetCollisionEnabled**(): [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Returns

[`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetCollisionEnabled](ue_ue.GizmoBaseComponent.md#getcollisionenabled)

___

### GetCollisionObjectType

▸ **GetCollisionObjectType**(): [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Returns

[`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetCollisionObjectType](ue_ue.GizmoBaseComponent.md#getcollisionobjecttype)

___

### GetCollisionProfileName

▸ **GetCollisionProfileName**(): `string`

#### Returns

`string`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetCollisionProfileName](ue_ue.GizmoBaseComponent.md#getcollisionprofilename)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetCollisionResponseToChannel](ue_ue.GizmoBaseComponent.md#getcollisionresponsetochannel)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetComponentTickInterval](ue_ue.GizmoBaseComponent.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetComponentVelocity](ue_ue.GizmoBaseComponent.md#getcomponentvelocity)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetForwardVector](ue_ue.GizmoBaseComponent.md#getforwardvector)

___

### GetGenerateOverlapEvents

▸ **GetGenerateOverlapEvents**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetGenerateOverlapEvents](ue_ue.GizmoBaseComponent.md#getgenerateoverlapevents)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetInertiaTensor](ue_ue.GizmoBaseComponent.md#getinertiatensor)

___

### GetLinearDamping

▸ **GetLinearDamping**(): `number`

#### Returns

`number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetLinearDamping](ue_ue.GizmoBaseComponent.md#getlineardamping)

___

### GetMass

▸ **GetMass**(): `number`

#### Returns

`number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetMass](ue_ue.GizmoBaseComponent.md#getmass)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetMassScale](ue_ue.GizmoBaseComponent.md#getmassscale)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetMaterial](ue_ue.GizmoBaseComponent.md#getmaterial)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetMaterialFromCollisionFaceIndex](ue_ue.GizmoBaseComponent.md#getmaterialfromcollisionfaceindex)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetName](ue_ue.GizmoBaseComponent.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetNumChildrenComponents](ue_ue.GizmoBaseComponent.md#getnumchildrencomponents)

___

### GetNumMaterials

▸ **GetNumMaterials**(): `number`

#### Returns

`number`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetNumMaterials](ue_ue.GizmoBaseComponent.md#getnummaterials)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetOuter](ue_ue.GizmoBaseComponent.md#getouter)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetOverlappingActors](ue_ue.GizmoBaseComponent.md#getoverlappingactors)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetOverlappingComponents](ue_ue.GizmoBaseComponent.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetOwner](ue_ue.GizmoBaseComponent.md#getowner)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetParentComponents](ue_ue.GizmoBaseComponent.md#getparentcomponents)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetPhysicsAngularVelocity](ue_ue.GizmoBaseComponent.md#getphysicsangularvelocity)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetPhysicsAngularVelocityInDegrees](ue_ue.GizmoBaseComponent.md#getphysicsangularvelocityindegrees)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetPhysicsAngularVelocityInRadians](ue_ue.GizmoBaseComponent.md#getphysicsangularvelocityinradians)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetPhysicsLinearVelocity](ue_ue.GizmoBaseComponent.md#getphysicslinearvelocity)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetPhysicsLinearVelocityAtPoint](ue_ue.GizmoBaseComponent.md#getphysicslinearvelocityatpoint)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetPhysicsVolume](ue_ue.GizmoBaseComponent.md#getphysicsvolume)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetRelativeTransform](ue_ue.GizmoBaseComponent.md#getrelativetransform)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetRightVector](ue_ue.GizmoBaseComponent.md#getrightvector)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.GizmoBaseComponent.md#getshouldupdatephysicsvolume)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetSocketLocation](ue_ue.GizmoBaseComponent.md#getsocketlocation)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetSocketQuaternion](ue_ue.GizmoBaseComponent.md#getsocketquaternion)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetSocketRotation](ue_ue.GizmoBaseComponent.md#getsocketrotation)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetSocketTransform](ue_ue.GizmoBaseComponent.md#getsockettransform)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetUpVector](ue_ue.GizmoBaseComponent.md#getupvector)

___

### GetWalkableSlopeOverride

▸ **GetWalkableSlopeOverride**(): [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Returns

[`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetWalkableSlopeOverride](ue_ue.GizmoBaseComponent.md#getwalkableslopeoverride)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[GetWorld](ue_ue.GizmoBaseComponent.md#getworld)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[IgnoreActorWhenMoving](ue_ue.GizmoBaseComponent.md#ignoreactorwhenmoving)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[IgnoreComponentWhenMoving](ue_ue.GizmoBaseComponent.md#ignorecomponentwhenmoving)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[IsActive](ue_ue.GizmoBaseComponent.md#isactive)

___

### IsAnyRigidBodyAwake

▸ **IsAnyRigidBodyAwake**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[IsAnyRigidBodyAwake](ue_ue.GizmoBaseComponent.md#isanyrigidbodyawake)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[IsAnySimulatingPhysics](ue_ue.GizmoBaseComponent.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[IsBeingDestroyed](ue_ue.GizmoBaseComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[IsComponentTickEnabled](ue_ue.GizmoBaseComponent.md#iscomponenttickenabled)

___

### IsGravityEnabled

▸ **IsGravityEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[IsGravityEnabled](ue_ue.GizmoBaseComponent.md#isgravityenabled)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[IsOverlappingActor](ue_ue.GizmoBaseComponent.md#isoverlappingactor)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[IsOverlappingComponent](ue_ue.GizmoBaseComponent.md#isoverlappingcomponent)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[IsSimulatingPhysics](ue_ue.GizmoBaseComponent.md#issimulatingphysics)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[IsVisible](ue_ue.GizmoBaseComponent.md#isvisible)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_AddLocalOffset](ue_ue.GizmoBaseComponent.md#k2_addlocaloffset)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_AddLocalRotation](ue_ue.GizmoBaseComponent.md#k2_addlocalrotation)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_AddLocalTransform](ue_ue.GizmoBaseComponent.md#k2_addlocaltransform)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_AddRelativeLocation](ue_ue.GizmoBaseComponent.md#k2_addrelativelocation)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_AddRelativeRotation](ue_ue.GizmoBaseComponent.md#k2_addrelativerotation)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_AddWorldOffset](ue_ue.GizmoBaseComponent.md#k2_addworldoffset)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_AddWorldRotation](ue_ue.GizmoBaseComponent.md#k2_addworldrotation)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_AddWorldTransform](ue_ue.GizmoBaseComponent.md#k2_addworldtransform)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_AttachTo](ue_ue.GizmoBaseComponent.md#k2_attachto)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_AttachToComponent](ue_ue.GizmoBaseComponent.md#k2_attachtocomponent)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_BoxOverlapComponent](ue_ue.GizmoBaseComponent.md#k2_boxoverlapcomponent)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_DestroyComponent](ue_ue.GizmoBaseComponent.md#k2_destroycomponent)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_DetachFromComponent](ue_ue.GizmoBaseComponent.md#k2_detachfromcomponent)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_GetComponentLocation](ue_ue.GizmoBaseComponent.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_GetComponentRotation](ue_ue.GizmoBaseComponent.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_GetComponentScale](ue_ue.GizmoBaseComponent.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_GetComponentToWorld](ue_ue.GizmoBaseComponent.md#k2_getcomponenttoworld)

___

### K2\_IsCollisionEnabled

▸ **K2_IsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_IsCollisionEnabled](ue_ue.GizmoBaseComponent.md#k2_iscollisionenabled)

___

### K2\_IsPhysicsCollisionEnabled

▸ **K2_IsPhysicsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_IsPhysicsCollisionEnabled](ue_ue.GizmoBaseComponent.md#k2_isphysicscollisionenabled)

___

### K2\_IsQueryCollisionEnabled

▸ **K2_IsQueryCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_IsQueryCollisionEnabled](ue_ue.GizmoBaseComponent.md#k2_isquerycollisionenabled)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_LineTraceComponent](ue_ue.GizmoBaseComponent.md#k2_linetracecomponent)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_SetRelativeLocation](ue_ue.GizmoBaseComponent.md#k2_setrelativelocation)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.GizmoBaseComponent.md#k2_setrelativelocationandrotation)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_SetRelativeRotation](ue_ue.GizmoBaseComponent.md#k2_setrelativerotation)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_SetRelativeTransform](ue_ue.GizmoBaseComponent.md#k2_setrelativetransform)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_SetWorldLocation](ue_ue.GizmoBaseComponent.md#k2_setworldlocation)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.GizmoBaseComponent.md#k2_setworldlocationandrotation)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_SetWorldRotation](ue_ue.GizmoBaseComponent.md#k2_setworldrotation)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_SetWorldTransform](ue_ue.GizmoBaseComponent.md#k2_setworldtransform)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_SphereOverlapComponent](ue_ue.GizmoBaseComponent.md#k2_sphereoverlapcomponent)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[K2_SphereTraceComponent](ue_ue.GizmoBaseComponent.md#k2_spheretracecomponent)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnRep_AttachChildren](ue_ue.GizmoBaseComponent.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnRep_AttachParent](ue_ue.GizmoBaseComponent.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnRep_AttachSocketName](ue_ue.GizmoBaseComponent.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnRep_IsActive](ue_ue.GizmoBaseComponent.md#onrep_isactive)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnRep_Transform](ue_ue.GizmoBaseComponent.md#onrep_transform)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[OnRep_Visibility](ue_ue.GizmoBaseComponent.md#onrep_visibility)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[PutRigidBodyToSleep](ue_ue.GizmoBaseComponent.md#putrigidbodytosleep)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[ReceiveBeginPlay](ue_ue.GizmoBaseComponent.md#receivebeginplay)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[ReceiveEndPlay](ue_ue.GizmoBaseComponent.md#receiveendplay)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[ReceiveTick](ue_ue.GizmoBaseComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[RegisterComponent](ue_ue.GizmoBaseComponent.md#registercomponent)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[RemoveTickPrerequisiteActor](ue_ue.GizmoBaseComponent.md#removetickprerequisiteactor)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.GizmoBaseComponent.md#removetickprerequisitecomponent)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[ResetRelativeTransform](ue_ue.GizmoBaseComponent.md#resetrelativetransform)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[ScaleByMomentOfInertia](ue_ue.GizmoBaseComponent.md#scalebymomentofinertia)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetAbsolute](ue_ue.GizmoBaseComponent.md#setabsolute)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetActive](ue_ue.GizmoBaseComponent.md#setactive)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetAllMassScale](ue_ue.GizmoBaseComponent.md#setallmassscale)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetAllPhysicsAngularVelocityInDegrees](ue_ue.GizmoBaseComponent.md#setallphysicsangularvelocityindegrees)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetAllPhysicsAngularVelocityInRadians](ue_ue.GizmoBaseComponent.md#setallphysicsangularvelocityinradians)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetAllPhysicsLinearVelocity](ue_ue.GizmoBaseComponent.md#setallphysicslinearvelocity)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetAllUseCCD](ue_ue.GizmoBaseComponent.md#setalluseccd)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetAngularDamping](ue_ue.GizmoBaseComponent.md#setangulardamping)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetAutoActivate](ue_ue.GizmoBaseComponent.md#setautoactivate)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetBoundsScale](ue_ue.GizmoBaseComponent.md#setboundsscale)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetCastInsetShadow](ue_ue.GizmoBaseComponent.md#setcastinsetshadow)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetCastShadow](ue_ue.GizmoBaseComponent.md#setcastshadow)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetCenterOfMass](ue_ue.GizmoBaseComponent.md#setcenterofmass)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetCollisionEnabled](ue_ue.GizmoBaseComponent.md#setcollisionenabled)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetCollisionObjectType](ue_ue.GizmoBaseComponent.md#setcollisionobjecttype)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetCollisionProfileName](ue_ue.GizmoBaseComponent.md#setcollisionprofilename)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetCollisionResponseToAllChannels](ue_ue.GizmoBaseComponent.md#setcollisionresponsetoallchannels)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetCollisionResponseToChannel](ue_ue.GizmoBaseComponent.md#setcollisionresponsetochannel)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetComponentTickEnabled](ue_ue.GizmoBaseComponent.md#setcomponenttickenabled)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetComponentTickInterval](ue_ue.GizmoBaseComponent.md#setcomponenttickinterval)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetConstraintMode](ue_ue.GizmoBaseComponent.md#setconstraintmode)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetCullDistance](ue_ue.GizmoBaseComponent.md#setculldistance)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetCustomDepthStencilValue](ue_ue.GizmoBaseComponent.md#setcustomdepthstencilvalue)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetCustomDepthStencilWriteMask](ue_ue.GizmoBaseComponent.md#setcustomdepthstencilwritemask)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetCustomPrimitiveDataFloat](ue_ue.GizmoBaseComponent.md#setcustomprimitivedatafloat)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetCustomPrimitiveDataVector2](ue_ue.GizmoBaseComponent.md#setcustomprimitivedatavector2)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetCustomPrimitiveDataVector3](ue_ue.GizmoBaseComponent.md#setcustomprimitivedatavector3)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetCustomPrimitiveDataVector4](ue_ue.GizmoBaseComponent.md#setcustomprimitivedatavector4)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetEnableGravity](ue_ue.GizmoBaseComponent.md#setenablegravity)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetExcludeFromLightAttachmentGroup](ue_ue.GizmoBaseComponent.md#setexcludefromlightattachmentgroup)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetGenerateOverlapEvents](ue_ue.GizmoBaseComponent.md#setgenerateoverlapevents)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetHiddenInGame](ue_ue.GizmoBaseComponent.md#sethiddeningame)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetIsReplicated](ue_ue.GizmoBaseComponent.md#setisreplicated)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetLightAttachmentsAsGroup](ue_ue.GizmoBaseComponent.md#setlightattachmentsasgroup)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetLinearDamping](ue_ue.GizmoBaseComponent.md#setlineardamping)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetMassOverrideInKg](ue_ue.GizmoBaseComponent.md#setmassoverrideinkg)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetMassScale](ue_ue.GizmoBaseComponent.md#setmassscale)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetMaterial](ue_ue.GizmoBaseComponent.md#setmaterial)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetMaterialByName](ue_ue.GizmoBaseComponent.md#setmaterialbyname)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetMobility](ue_ue.GizmoBaseComponent.md#setmobility)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetNotifyRigidBodyCollision](ue_ue.GizmoBaseComponent.md#setnotifyrigidbodycollision)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetOnlyOwnerSee](ue_ue.GizmoBaseComponent.md#setonlyownersee)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetOwnerNoSee](ue_ue.GizmoBaseComponent.md#setownernosee)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetPhysMaterialOverride](ue_ue.GizmoBaseComponent.md#setphysmaterialoverride)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetPhysicsAngularVelocity](ue_ue.GizmoBaseComponent.md#setphysicsangularvelocity)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetPhysicsAngularVelocityInDegrees](ue_ue.GizmoBaseComponent.md#setphysicsangularvelocityindegrees)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetPhysicsAngularVelocityInRadians](ue_ue.GizmoBaseComponent.md#setphysicsangularvelocityinradians)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetPhysicsLinearVelocity](ue_ue.GizmoBaseComponent.md#setphysicslinearvelocity)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetPhysicsMaxAngularVelocity](ue_ue.GizmoBaseComponent.md#setphysicsmaxangularvelocity)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetPhysicsMaxAngularVelocityInDegrees](ue_ue.GizmoBaseComponent.md#setphysicsmaxangularvelocityindegrees)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetPhysicsMaxAngularVelocityInRadians](ue_ue.GizmoBaseComponent.md#setphysicsmaxangularvelocityinradians)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetReceivesDecals](ue_ue.GizmoBaseComponent.md#setreceivesdecals)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetRelativeScale3D](ue_ue.GizmoBaseComponent.md#setrelativescale3d)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetRenderCustomDepth](ue_ue.GizmoBaseComponent.md#setrendercustomdepth)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetRenderInMainPass](ue_ue.GizmoBaseComponent.md#setrenderinmainpass)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.GizmoBaseComponent.md#setshouldupdatephysicsvolume)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetSimulatePhysics](ue_ue.GizmoBaseComponent.md#setsimulatephysics)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetSingleSampleShadowFromStationaryLights](ue_ue.GizmoBaseComponent.md#setsinglesampleshadowfromstationarylights)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetTickGroup](ue_ue.GizmoBaseComponent.md#settickgroup)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetTickableWhenPaused](ue_ue.GizmoBaseComponent.md#settickablewhenpaused)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetTranslucentSortPriority](ue_ue.GizmoBaseComponent.md#settranslucentsortpriority)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetUseCCD](ue_ue.GizmoBaseComponent.md#setuseccd)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetVisibility](ue_ue.GizmoBaseComponent.md#setvisibility)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetWalkableSlopeOverride](ue_ue.GizmoBaseComponent.md#setwalkableslopeoverride)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetWorldScale3D](ue_ue.GizmoBaseComponent.md#setworldscale3d)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SetupAttachment](ue_ue.GizmoBaseComponent.md#setupattachment)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[SnapTo](ue_ue.GizmoBaseComponent.md#snapto)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[ToggleActive](ue_ue.GizmoBaseComponent.md#toggleactive)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[ToggleVisibility](ue_ue.GizmoBaseComponent.md#togglevisibility)

___

### UpdateHoverState

▸ **UpdateHoverState**(`bHoveringIn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bHoveringIn` | `boolean` |

#### Returns

`void`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[UpdateHoverState](ue_ue.GizmoBaseComponent.md#updatehoverstate)

___

### UpdateWorldLocalState

▸ **UpdateWorldLocalState**(`bWorldIn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bWorldIn` | `boolean` |

#### Returns

`void`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[UpdateWorldLocalState](ue_ue.GizmoBaseComponent.md#updateworldlocalstate)

___

### WakeAllRigidBodies

▸ **WakeAllRigidBodies**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[WakeAllRigidBodies](ue_ue.GizmoBaseComponent.md#wakeallrigidbodies)

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

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[WakeRigidBody](ue_ue.GizmoBaseComponent.md#wakerigidbody)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GizmoRectangleComponent`](ue_ue.GizmoRectangleComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GizmoRectangleComponent`](ue_ue.GizmoRectangleComponent.md)

#### Overrides

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[Find](ue_ue.GizmoBaseComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GizmoRectangleComponent`](ue_ue.GizmoRectangleComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GizmoRectangleComponent`](ue_ue.GizmoRectangleComponent.md)

#### Overrides

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[Load](ue_ue.GizmoBaseComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GizmoBaseComponent](ue_ue.GizmoBaseComponent.md).[StaticClass](ue_ue.GizmoBaseComponent.md#staticclass)
