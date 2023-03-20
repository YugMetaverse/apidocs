[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TextRenderComponent

# Class: TextRenderComponent

[ue/ue](../modules/ue_ue.md).TextRenderComponent

## Hierarchy

- [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

  ↳ **`TextRenderComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.TextRenderComponent.md#constructor)

### Properties

- [AlwaysLoadOnClient](ue_ue.TextRenderComponent.md#alwaysloadonclient)
- [AlwaysLoadOnServer](ue_ue.TextRenderComponent.md#alwaysloadonserver)
- [AssetUserData](ue_ue.TextRenderComponent.md#assetuserdata)
- [AttachChildren](ue_ue.TextRenderComponent.md#attachchildren)
- [AttachParent](ue_ue.TextRenderComponent.md#attachparent)
- [AttachSocketName](ue_ue.TextRenderComponent.md#attachsocketname)
- [BodyInstance](ue_ue.TextRenderComponent.md#bodyinstance)
- [BoundsScale](ue_ue.TextRenderComponent.md#boundsscale)
- [CachedMaxDrawDistance](ue_ue.TextRenderComponent.md#cachedmaxdrawdistance)
- [CanBeCharacterBase](ue_ue.TextRenderComponent.md#canbecharacterbase)
- [CanCharacterStepUpOn](ue_ue.TextRenderComponent.md#cancharacterstepupon)
- [CastShadow](ue_ue.TextRenderComponent.md#castshadow)
- [ClientAttachedChildren](ue_ue.TextRenderComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.TextRenderComponent.md#componenttags)
- [ComponentVelocity](ue_ue.TextRenderComponent.md#componentvelocity)
- [CreationMethod](ue_ue.TextRenderComponent.md#creationmethod)
- [CustomDepthStencilValue](ue_ue.TextRenderComponent.md#customdepthstencilvalue)
- [CustomDepthStencilWriteMask](ue_ue.TextRenderComponent.md#customdepthstencilwritemask)
- [CustomPrimitiveData](ue_ue.TextRenderComponent.md#customprimitivedata)
- [DepthPriorityGroup](ue_ue.TextRenderComponent.md#depthprioritygroup)
- [DetailMode](ue_ue.TextRenderComponent.md#detailmode)
- [ExcludeForSpecificHLODLevels](ue_ue.TextRenderComponent.md#excludeforspecifichlodlevels)
- [Font](ue_ue.TextRenderComponent.md#font)
- [HorizSpacingAdjust](ue_ue.TextRenderComponent.md#horizspacingadjust)
- [HorizontalAlignment](ue_ue.TextRenderComponent.md#horizontalalignment)
- [IndirectLightingCacheQuality](ue_ue.TextRenderComponent.md#indirectlightingcachequality)
- [InvDefaultSize](ue_ue.TextRenderComponent.md#invdefaultsize)
- [LDMaxDrawDistance](ue_ue.TextRenderComponent.md#ldmaxdrawdistance)
- [LODParentPrimitive](ue_ue.TextRenderComponent.md#lodparentprimitive)
- [LightingChannels](ue_ue.TextRenderComponent.md#lightingchannels)
- [LightmapType](ue_ue.TextRenderComponent.md#lightmaptype)
- [LpvBiasMultiplier](ue_ue.TextRenderComponent.md#lpvbiasmultiplier)
- [MinDrawDistance](ue_ue.TextRenderComponent.md#mindrawdistance)
- [Mobility](ue_ue.TextRenderComponent.md#mobility)
- [MoveIgnoreActors](ue_ue.TextRenderComponent.md#moveignoreactors)
- [MoveIgnoreComponents](ue_ue.TextRenderComponent.md#moveignorecomponents)
- [OnBeginCursorOver](ue_ue.TextRenderComponent.md#onbegincursorover)
- [OnClicked](ue_ue.TextRenderComponent.md#onclicked)
- [OnComponentActivated](ue_ue.TextRenderComponent.md#oncomponentactivated)
- [OnComponentBeginOverlap](ue_ue.TextRenderComponent.md#oncomponentbeginoverlap)
- [OnComponentDeactivated](ue_ue.TextRenderComponent.md#oncomponentdeactivated)
- [OnComponentEndOverlap](ue_ue.TextRenderComponent.md#oncomponentendoverlap)
- [OnComponentHit](ue_ue.TextRenderComponent.md#oncomponenthit)
- [OnComponentSleep](ue_ue.TextRenderComponent.md#oncomponentsleep)
- [OnComponentWake](ue_ue.TextRenderComponent.md#oncomponentwake)
- [OnEndCursorOver](ue_ue.TextRenderComponent.md#onendcursorover)
- [OnInputTouchBegin](ue_ue.TextRenderComponent.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.TextRenderComponent.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.TextRenderComponent.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.TextRenderComponent.md#oninputtouchleave)
- [OnReleased](ue_ue.TextRenderComponent.md#onreleased)
- [PhysicsVolume](ue_ue.TextRenderComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.TextRenderComponent.md#physicsvolumechangeddelegate)
- [PrimaryComponentTick](ue_ue.TextRenderComponent.md#primarycomponenttick)
- [RelativeLocation](ue_ue.TextRenderComponent.md#relativelocation)
- [RelativeRotation](ue_ue.TextRenderComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.TextRenderComponent.md#relativescale3d)
- [RuntimeVirtualTextures](ue_ue.TextRenderComponent.md#runtimevirtualtextures)
- [Text](ue_ue.TextRenderComponent.md#text)
- [TextMaterial](ue_ue.TextRenderComponent.md#textmaterial)
- [TextRenderColor](ue_ue.TextRenderComponent.md#textrendercolor)
- [TranslucencySortPriority](ue_ue.TextRenderComponent.md#translucencysortpriority)
- [UCSModifiedProperties](ue_ue.TextRenderComponent.md#ucsmodifiedproperties)
- [VertSpacingAdjust](ue_ue.TextRenderComponent.md#vertspacingadjust)
- [VerticalAlignment](ue_ue.TextRenderComponent.md#verticalalignment)
- [ViewOwnerDepthPriorityGroup](ue_ue.TextRenderComponent.md#viewownerdepthprioritygroup)
- [VirtualTextureCullMips](ue_ue.TextRenderComponent.md#virtualtexturecullmips)
- [VirtualTextureLodBias](ue_ue.TextRenderComponent.md#virtualtexturelodbias)
- [VirtualTextureMinCoverage](ue_ue.TextRenderComponent.md#virtualtexturemincoverage)
- [VirtualTextureRenderPassType](ue_ue.TextRenderComponent.md#virtualtexturerenderpasstype)
- [VisibilityId](ue_ue.TextRenderComponent.md#visibilityid)
- [WorldSize](ue_ue.TextRenderComponent.md#worldsize)
- [XScale](ue_ue.TextRenderComponent.md#xscale)
- [YScale](ue_ue.TextRenderComponent.md#yscale)
- [\_\_tid\_ActorComponent\_\_](ue_ue.TextRenderComponent.md#__tid_actorcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.TextRenderComponent.md#__tid_object__)
- [\_\_tid\_PrimitiveComponent\_\_](ue_ue.TextRenderComponent.md#__tid_primitivecomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.TextRenderComponent.md#__tid_scenecomponent__)
- [\_\_tid\_TextRenderComponent\_\_](ue_ue.TextRenderComponent.md#__tid_textrendercomponent__)
- [bAbsoluteLocation](ue_ue.TextRenderComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.TextRenderComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.TextRenderComponent.md#babsolutescale)
- [bAffectDistanceFieldLighting](ue_ue.TextRenderComponent.md#baffectdistancefieldlighting)
- [bAffectDynamicIndirectLighting](ue_ue.TextRenderComponent.md#baffectdynamicindirectlighting)
- [bAllowCullDistanceVolume](ue_ue.TextRenderComponent.md#ballowculldistancevolume)
- [bAlwaysCreatePhysicsState](ue_ue.TextRenderComponent.md#balwayscreatephysicsstate)
- [bAlwaysRenderAsText](ue_ue.TextRenderComponent.md#balwaysrenderastext)
- [bApplyImpulseOnDamage](ue_ue.TextRenderComponent.md#bapplyimpulseondamage)
- [bAutoActivate](ue_ue.TextRenderComponent.md#bautoactivate)
- [bBatchImpostersAsInstances](ue_ue.TextRenderComponent.md#bbatchimpostersasinstances)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.TextRenderComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.TextRenderComponent.md#bcaneveraffectnavigation)
- [bCastCinematicShadow](ue_ue.TextRenderComponent.md#bcastcinematicshadow)
- [bCastDynamicShadow](ue_ue.TextRenderComponent.md#bcastdynamicshadow)
- [bCastFarShadow](ue_ue.TextRenderComponent.md#bcastfarshadow)
- [bCastHiddenShadow](ue_ue.TextRenderComponent.md#bcasthiddenshadow)
- [bCastInsetShadow](ue_ue.TextRenderComponent.md#bcastinsetshadow)
- [bCastShadowAsTwoSided](ue_ue.TextRenderComponent.md#bcastshadowastwosided)
- [bCastStaticShadow](ue_ue.TextRenderComponent.md#bcaststaticshadow)
- [bCastVolumetricTranslucentShadow](ue_ue.TextRenderComponent.md#bcastvolumetrictranslucentshadow)
- [bComponentToWorldUpdated](ue_ue.TextRenderComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.TextRenderComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.TextRenderComponent.md#beditablewheninherited)
- [bEnableAutoLODGeneration](ue_ue.TextRenderComponent.md#benableautolodgeneration)
- [bExcludeFromLightAttachmentGroup](ue_ue.TextRenderComponent.md#bexcludefromlightattachmentgroup)
- [bForceMipStreaming](ue_ue.TextRenderComponent.md#bforcemipstreaming)
- [bGenerateOverlapEvents](ue_ue.TextRenderComponent.md#bgenerateoverlapevents)
- [bHasCustomNavigableGeometry](ue_ue.TextRenderComponent.md#bhascustomnavigablegeometry)
- [bHasMotionBlurVelocityMeshes](ue_ue.TextRenderComponent.md#bhasmotionblurvelocitymeshes)
- [bHasPerInstanceHitProxies](ue_ue.TextRenderComponent.md#bhasperinstancehitproxies)
- [bHiddenInGame](ue_ue.TextRenderComponent.md#bhiddeningame)
- [bIgnoreRadialForce](ue_ue.TextRenderComponent.md#bignoreradialforce)
- [bIgnoreRadialImpulse](ue_ue.TextRenderComponent.md#bignoreradialimpulse)
- [bInstanceComponent](ue_ue.TextRenderComponent.md#binstancecomponent)
- [bIsActive](ue_ue.TextRenderComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.TextRenderComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.TextRenderComponent.md#bisvisualizationcomponent)
- [bLightAsIfStatic](ue_ue.TextRenderComponent.md#blightasifstatic)
- [bLightAttachmentsAsGroup](ue_ue.TextRenderComponent.md#blightattachmentsasgroup)
- [bMultiBodyOverlap](ue_ue.TextRenderComponent.md#bmultibodyoverlap)
- [bNetAddressable](ue_ue.TextRenderComponent.md#bnetaddressable)
- [bNeverDistanceCull](ue_ue.TextRenderComponent.md#bneverdistancecull)
- [bOnlyOwnerSee](ue_ue.TextRenderComponent.md#bonlyownersee)
- [bOwnerNoSee](ue_ue.TextRenderComponent.md#bownernosee)
- [bReceiveMobileCSMShadows](ue_ue.TextRenderComponent.md#breceivemobilecsmshadows)
- [bReceivesDecals](ue_ue.TextRenderComponent.md#breceivesdecals)
- [bRenderCustomDepth](ue_ue.TextRenderComponent.md#brendercustomdepth)
- [bRenderInDepthPass](ue_ue.TextRenderComponent.md#brenderindepthpass)
- [bRenderInMainPass](ue_ue.TextRenderComponent.md#brenderinmainpass)
- [bReplicatePhysicsToAutonomousProxy](ue_ue.TextRenderComponent.md#breplicatephysicstoautonomousproxy)
- [bReplicates](ue_ue.TextRenderComponent.md#breplicates)
- [bReturnMaterialOnMove](ue_ue.TextRenderComponent.md#breturnmaterialonmove)
- [bSelectable](ue_ue.TextRenderComponent.md#bselectable)
- [bSelfShadowOnly](ue_ue.TextRenderComponent.md#bselfshadowonly)
- [bShouldBeAttached](ue_ue.TextRenderComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.TextRenderComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.TextRenderComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.TextRenderComponent.md#bshouldupdatephysicsvolume)
- [bSingleSampleShadowFromStationaryLights](ue_ue.TextRenderComponent.md#bsinglesampleshadowfromstationarylights)
- [bTraceComplexOnMove](ue_ue.TextRenderComponent.md#btracecomplexonmove)
- [bTreatAsBackgroundForOcclusion](ue_ue.TextRenderComponent.md#btreatasbackgroundforocclusion)
- [bUseAsOccluder](ue_ue.TextRenderComponent.md#buseasoccluder)
- [bUseAttachParentBound](ue_ue.TextRenderComponent.md#buseattachparentbound)
- [bUseEditorCompositing](ue_ue.TextRenderComponent.md#buseeditorcompositing)
- [bUseMaxLODAsImposter](ue_ue.TextRenderComponent.md#busemaxlodasimposter)
- [bUseViewOwnerDepthPriorityGroup](ue_ue.TextRenderComponent.md#buseviewownerdepthprioritygroup)
- [bVisible](ue_ue.TextRenderComponent.md#bvisible)
- [bVisibleInRayTracing](ue_ue.TextRenderComponent.md#bvisibleinraytracing)
- [bVisibleInReflectionCaptures](ue_ue.TextRenderComponent.md#bvisibleinreflectioncaptures)
- [bVisualizeComponent](ue_ue.TextRenderComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.TextRenderComponent.md#activate)
- [AddAngularImpulse](ue_ue.TextRenderComponent.md#addangularimpulse)
- [AddAngularImpulseInDegrees](ue_ue.TextRenderComponent.md#addangularimpulseindegrees)
- [AddAngularImpulseInRadians](ue_ue.TextRenderComponent.md#addangularimpulseinradians)
- [AddForce](ue_ue.TextRenderComponent.md#addforce)
- [AddForceAtLocation](ue_ue.TextRenderComponent.md#addforceatlocation)
- [AddForceAtLocationLocal](ue_ue.TextRenderComponent.md#addforceatlocationlocal)
- [AddImpulse](ue_ue.TextRenderComponent.md#addimpulse)
- [AddImpulseAtLocation](ue_ue.TextRenderComponent.md#addimpulseatlocation)
- [AddRadialForce](ue_ue.TextRenderComponent.md#addradialforce)
- [AddRadialImpulse](ue_ue.TextRenderComponent.md#addradialimpulse)
- [AddTickPrerequisiteActor](ue_ue.TextRenderComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.TextRenderComponent.md#addtickprerequisitecomponent)
- [AddTorque](ue_ue.TextRenderComponent.md#addtorque)
- [AddTorqueInDegrees](ue_ue.TextRenderComponent.md#addtorqueindegrees)
- [AddTorqueInRadians](ue_ue.TextRenderComponent.md#addtorqueinradians)
- [CanCharacterStepUp](ue_ue.TextRenderComponent.md#cancharacterstepup)
- [ClearMoveIgnoreActors](ue_ue.TextRenderComponent.md#clearmoveignoreactors)
- [ClearMoveIgnoreComponents](ue_ue.TextRenderComponent.md#clearmoveignorecomponents)
- [ComponentHasTag](ue_ue.TextRenderComponent.md#componenthastag)
- [CopyArrayOfMoveIgnoreActors](ue_ue.TextRenderComponent.md#copyarrayofmoveignoreactors)
- [CopyArrayOfMoveIgnoreComponents](ue_ue.TextRenderComponent.md#copyarrayofmoveignorecomponents)
- [CreateAndSetMaterialInstanceDynamic](ue_ue.TextRenderComponent.md#createandsetmaterialinstancedynamic)
- [CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.TextRenderComponent.md#createandsetmaterialinstancedynamicfrommaterial)
- [CreateDefaultSubobject](ue_ue.TextRenderComponent.md#createdefaultsubobject)
- [CreateDynamicMaterialInstance](ue_ue.TextRenderComponent.md#createdynamicmaterialinstance)
- [Deactivate](ue_ue.TextRenderComponent.md#deactivate)
- [DetachFromParent](ue_ue.TextRenderComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.TextRenderComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.TextRenderComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.TextRenderComponent.md#getallsocketnames)
- [GetAngularDamping](ue_ue.TextRenderComponent.md#getangulardamping)
- [GetAttachParent](ue_ue.TextRenderComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.TextRenderComponent.md#getattachsocketname)
- [GetCenterOfMass](ue_ue.TextRenderComponent.md#getcenterofmass)
- [GetChildComponent](ue_ue.TextRenderComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.TextRenderComponent.md#getchildrencomponents)
- [GetClass](ue_ue.TextRenderComponent.md#getclass)
- [GetClosestPointOnCollision](ue_ue.TextRenderComponent.md#getclosestpointoncollision)
- [GetCollisionEnabled](ue_ue.TextRenderComponent.md#getcollisionenabled)
- [GetCollisionObjectType](ue_ue.TextRenderComponent.md#getcollisionobjecttype)
- [GetCollisionProfileName](ue_ue.TextRenderComponent.md#getcollisionprofilename)
- [GetCollisionResponseToChannel](ue_ue.TextRenderComponent.md#getcollisionresponsetochannel)
- [GetComponentTickInterval](ue_ue.TextRenderComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.TextRenderComponent.md#getcomponentvelocity)
- [GetForwardVector](ue_ue.TextRenderComponent.md#getforwardvector)
- [GetGenerateOverlapEvents](ue_ue.TextRenderComponent.md#getgenerateoverlapevents)
- [GetInertiaTensor](ue_ue.TextRenderComponent.md#getinertiatensor)
- [GetLinearDamping](ue_ue.TextRenderComponent.md#getlineardamping)
- [GetMass](ue_ue.TextRenderComponent.md#getmass)
- [GetMassScale](ue_ue.TextRenderComponent.md#getmassscale)
- [GetMaterial](ue_ue.TextRenderComponent.md#getmaterial)
- [GetMaterialFromCollisionFaceIndex](ue_ue.TextRenderComponent.md#getmaterialfromcollisionfaceindex)
- [GetName](ue_ue.TextRenderComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.TextRenderComponent.md#getnumchildrencomponents)
- [GetNumMaterials](ue_ue.TextRenderComponent.md#getnummaterials)
- [GetOuter](ue_ue.TextRenderComponent.md#getouter)
- [GetOverlappingActors](ue_ue.TextRenderComponent.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.TextRenderComponent.md#getoverlappingcomponents)
- [GetOwner](ue_ue.TextRenderComponent.md#getowner)
- [GetParentComponents](ue_ue.TextRenderComponent.md#getparentcomponents)
- [GetPhysicsAngularVelocity](ue_ue.TextRenderComponent.md#getphysicsangularvelocity)
- [GetPhysicsAngularVelocityInDegrees](ue_ue.TextRenderComponent.md#getphysicsangularvelocityindegrees)
- [GetPhysicsAngularVelocityInRadians](ue_ue.TextRenderComponent.md#getphysicsangularvelocityinradians)
- [GetPhysicsLinearVelocity](ue_ue.TextRenderComponent.md#getphysicslinearvelocity)
- [GetPhysicsLinearVelocityAtPoint](ue_ue.TextRenderComponent.md#getphysicslinearvelocityatpoint)
- [GetPhysicsVolume](ue_ue.TextRenderComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.TextRenderComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.TextRenderComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.TextRenderComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.TextRenderComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.TextRenderComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.TextRenderComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.TextRenderComponent.md#getsockettransform)
- [GetTextLocalSize](ue_ue.TextRenderComponent.md#gettextlocalsize)
- [GetTextWorldSize](ue_ue.TextRenderComponent.md#gettextworldsize)
- [GetUpVector](ue_ue.TextRenderComponent.md#getupvector)
- [GetWalkableSlopeOverride](ue_ue.TextRenderComponent.md#getwalkableslopeoverride)
- [GetWorld](ue_ue.TextRenderComponent.md#getworld)
- [IgnoreActorWhenMoving](ue_ue.TextRenderComponent.md#ignoreactorwhenmoving)
- [IgnoreComponentWhenMoving](ue_ue.TextRenderComponent.md#ignorecomponentwhenmoving)
- [IsActive](ue_ue.TextRenderComponent.md#isactive)
- [IsAnyRigidBodyAwake](ue_ue.TextRenderComponent.md#isanyrigidbodyawake)
- [IsAnySimulatingPhysics](ue_ue.TextRenderComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.TextRenderComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.TextRenderComponent.md#iscomponenttickenabled)
- [IsGravityEnabled](ue_ue.TextRenderComponent.md#isgravityenabled)
- [IsOverlappingActor](ue_ue.TextRenderComponent.md#isoverlappingactor)
- [IsOverlappingComponent](ue_ue.TextRenderComponent.md#isoverlappingcomponent)
- [IsSimulatingPhysics](ue_ue.TextRenderComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.TextRenderComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.TextRenderComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.TextRenderComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.TextRenderComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.TextRenderComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.TextRenderComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.TextRenderComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.TextRenderComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.TextRenderComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.TextRenderComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.TextRenderComponent.md#k2_attachtocomponent)
- [K2\_BoxOverlapComponent](ue_ue.TextRenderComponent.md#k2_boxoverlapcomponent)
- [K2\_DestroyComponent](ue_ue.TextRenderComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.TextRenderComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.TextRenderComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.TextRenderComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.TextRenderComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.TextRenderComponent.md#k2_getcomponenttoworld)
- [K2\_IsCollisionEnabled](ue_ue.TextRenderComponent.md#k2_iscollisionenabled)
- [K2\_IsPhysicsCollisionEnabled](ue_ue.TextRenderComponent.md#k2_isphysicscollisionenabled)
- [K2\_IsQueryCollisionEnabled](ue_ue.TextRenderComponent.md#k2_isquerycollisionenabled)
- [K2\_LineTraceComponent](ue_ue.TextRenderComponent.md#k2_linetracecomponent)
- [K2\_SetRelativeLocation](ue_ue.TextRenderComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.TextRenderComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.TextRenderComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.TextRenderComponent.md#k2_setrelativetransform)
- [K2\_SetText](ue_ue.TextRenderComponent.md#k2_settext)
- [K2\_SetWorldLocation](ue_ue.TextRenderComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.TextRenderComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.TextRenderComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.TextRenderComponent.md#k2_setworldtransform)
- [K2\_SphereOverlapComponent](ue_ue.TextRenderComponent.md#k2_sphereoverlapcomponent)
- [K2\_SphereTraceComponent](ue_ue.TextRenderComponent.md#k2_spheretracecomponent)
- [OnRep\_AttachChildren](ue_ue.TextRenderComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.TextRenderComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.TextRenderComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.TextRenderComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.TextRenderComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.TextRenderComponent.md#onrep_visibility)
- [PutRigidBodyToSleep](ue_ue.TextRenderComponent.md#putrigidbodytosleep)
- [ReceiveBeginPlay](ue_ue.TextRenderComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.TextRenderComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.TextRenderComponent.md#receivetick)
- [RegisterComponent](ue_ue.TextRenderComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.TextRenderComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.TextRenderComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.TextRenderComponent.md#resetrelativetransform)
- [ScaleByMomentOfInertia](ue_ue.TextRenderComponent.md#scalebymomentofinertia)
- [SetAbsolute](ue_ue.TextRenderComponent.md#setabsolute)
- [SetActive](ue_ue.TextRenderComponent.md#setactive)
- [SetAllMassScale](ue_ue.TextRenderComponent.md#setallmassscale)
- [SetAllPhysicsAngularVelocityInDegrees](ue_ue.TextRenderComponent.md#setallphysicsangularvelocityindegrees)
- [SetAllPhysicsAngularVelocityInRadians](ue_ue.TextRenderComponent.md#setallphysicsangularvelocityinradians)
- [SetAllPhysicsLinearVelocity](ue_ue.TextRenderComponent.md#setallphysicslinearvelocity)
- [SetAllUseCCD](ue_ue.TextRenderComponent.md#setalluseccd)
- [SetAngularDamping](ue_ue.TextRenderComponent.md#setangulardamping)
- [SetAutoActivate](ue_ue.TextRenderComponent.md#setautoactivate)
- [SetBoundsScale](ue_ue.TextRenderComponent.md#setboundsscale)
- [SetCastInsetShadow](ue_ue.TextRenderComponent.md#setcastinsetshadow)
- [SetCastShadow](ue_ue.TextRenderComponent.md#setcastshadow)
- [SetCenterOfMass](ue_ue.TextRenderComponent.md#setcenterofmass)
- [SetCollisionEnabled](ue_ue.TextRenderComponent.md#setcollisionenabled)
- [SetCollisionObjectType](ue_ue.TextRenderComponent.md#setcollisionobjecttype)
- [SetCollisionProfileName](ue_ue.TextRenderComponent.md#setcollisionprofilename)
- [SetCollisionResponseToAllChannels](ue_ue.TextRenderComponent.md#setcollisionresponsetoallchannels)
- [SetCollisionResponseToChannel](ue_ue.TextRenderComponent.md#setcollisionresponsetochannel)
- [SetComponentTickEnabled](ue_ue.TextRenderComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.TextRenderComponent.md#setcomponenttickinterval)
- [SetConstraintMode](ue_ue.TextRenderComponent.md#setconstraintmode)
- [SetCullDistance](ue_ue.TextRenderComponent.md#setculldistance)
- [SetCustomDepthStencilValue](ue_ue.TextRenderComponent.md#setcustomdepthstencilvalue)
- [SetCustomDepthStencilWriteMask](ue_ue.TextRenderComponent.md#setcustomdepthstencilwritemask)
- [SetCustomPrimitiveDataFloat](ue_ue.TextRenderComponent.md#setcustomprimitivedatafloat)
- [SetCustomPrimitiveDataVector2](ue_ue.TextRenderComponent.md#setcustomprimitivedatavector2)
- [SetCustomPrimitiveDataVector3](ue_ue.TextRenderComponent.md#setcustomprimitivedatavector3)
- [SetCustomPrimitiveDataVector4](ue_ue.TextRenderComponent.md#setcustomprimitivedatavector4)
- [SetEnableGravity](ue_ue.TextRenderComponent.md#setenablegravity)
- [SetExcludeFromLightAttachmentGroup](ue_ue.TextRenderComponent.md#setexcludefromlightattachmentgroup)
- [SetFont](ue_ue.TextRenderComponent.md#setfont)
- [SetGenerateOverlapEvents](ue_ue.TextRenderComponent.md#setgenerateoverlapevents)
- [SetHiddenInGame](ue_ue.TextRenderComponent.md#sethiddeningame)
- [SetHorizSpacingAdjust](ue_ue.TextRenderComponent.md#sethorizspacingadjust)
- [SetHorizontalAlignment](ue_ue.TextRenderComponent.md#sethorizontalalignment)
- [SetIsReplicated](ue_ue.TextRenderComponent.md#setisreplicated)
- [SetLightAttachmentsAsGroup](ue_ue.TextRenderComponent.md#setlightattachmentsasgroup)
- [SetLinearDamping](ue_ue.TextRenderComponent.md#setlineardamping)
- [SetMassOverrideInKg](ue_ue.TextRenderComponent.md#setmassoverrideinkg)
- [SetMassScale](ue_ue.TextRenderComponent.md#setmassscale)
- [SetMaterial](ue_ue.TextRenderComponent.md#setmaterial)
- [SetMaterialByName](ue_ue.TextRenderComponent.md#setmaterialbyname)
- [SetMobility](ue_ue.TextRenderComponent.md#setmobility)
- [SetNotifyRigidBodyCollision](ue_ue.TextRenderComponent.md#setnotifyrigidbodycollision)
- [SetOnlyOwnerSee](ue_ue.TextRenderComponent.md#setonlyownersee)
- [SetOwnerNoSee](ue_ue.TextRenderComponent.md#setownernosee)
- [SetPhysMaterialOverride](ue_ue.TextRenderComponent.md#setphysmaterialoverride)
- [SetPhysicsAngularVelocity](ue_ue.TextRenderComponent.md#setphysicsangularvelocity)
- [SetPhysicsAngularVelocityInDegrees](ue_ue.TextRenderComponent.md#setphysicsangularvelocityindegrees)
- [SetPhysicsAngularVelocityInRadians](ue_ue.TextRenderComponent.md#setphysicsangularvelocityinradians)
- [SetPhysicsLinearVelocity](ue_ue.TextRenderComponent.md#setphysicslinearvelocity)
- [SetPhysicsMaxAngularVelocity](ue_ue.TextRenderComponent.md#setphysicsmaxangularvelocity)
- [SetPhysicsMaxAngularVelocityInDegrees](ue_ue.TextRenderComponent.md#setphysicsmaxangularvelocityindegrees)
- [SetPhysicsMaxAngularVelocityInRadians](ue_ue.TextRenderComponent.md#setphysicsmaxangularvelocityinradians)
- [SetReceivesDecals](ue_ue.TextRenderComponent.md#setreceivesdecals)
- [SetRelativeScale3D](ue_ue.TextRenderComponent.md#setrelativescale3d)
- [SetRenderCustomDepth](ue_ue.TextRenderComponent.md#setrendercustomdepth)
- [SetRenderInMainPass](ue_ue.TextRenderComponent.md#setrenderinmainpass)
- [SetShouldUpdatePhysicsVolume](ue_ue.TextRenderComponent.md#setshouldupdatephysicsvolume)
- [SetSimulatePhysics](ue_ue.TextRenderComponent.md#setsimulatephysics)
- [SetSingleSampleShadowFromStationaryLights](ue_ue.TextRenderComponent.md#setsinglesampleshadowfromstationarylights)
- [SetText](ue_ue.TextRenderComponent.md#settext)
- [SetTextMaterial](ue_ue.TextRenderComponent.md#settextmaterial)
- [SetTextRenderColor](ue_ue.TextRenderComponent.md#settextrendercolor)
- [SetTickGroup](ue_ue.TextRenderComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.TextRenderComponent.md#settickablewhenpaused)
- [SetTranslucentSortPriority](ue_ue.TextRenderComponent.md#settranslucentsortpriority)
- [SetUseCCD](ue_ue.TextRenderComponent.md#setuseccd)
- [SetVertSpacingAdjust](ue_ue.TextRenderComponent.md#setvertspacingadjust)
- [SetVerticalAlignment](ue_ue.TextRenderComponent.md#setverticalalignment)
- [SetVisibility](ue_ue.TextRenderComponent.md#setvisibility)
- [SetWalkableSlopeOverride](ue_ue.TextRenderComponent.md#setwalkableslopeoverride)
- [SetWorldScale3D](ue_ue.TextRenderComponent.md#setworldscale3d)
- [SetWorldSize](ue_ue.TextRenderComponent.md#setworldsize)
- [SetXScale](ue_ue.TextRenderComponent.md#setxscale)
- [SetYScale](ue_ue.TextRenderComponent.md#setyscale)
- [SetupAttachment](ue_ue.TextRenderComponent.md#setupattachment)
- [SnapTo](ue_ue.TextRenderComponent.md#snapto)
- [ToggleActive](ue_ue.TextRenderComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.TextRenderComponent.md#togglevisibility)
- [WakeAllRigidBodies](ue_ue.TextRenderComponent.md#wakeallrigidbodies)
- [WakeRigidBody](ue_ue.TextRenderComponent.md#wakerigidbody)
- [Find](ue_ue.TextRenderComponent.md#find)
- [Load](ue_ue.TextRenderComponent.md#load)
- [StaticClass](ue_ue.TextRenderComponent.md#staticclass)

## Constructors

### constructor

• **new TextRenderComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[constructor](ue_ue.PrimitiveComponent.md#constructor)

## Properties

### AlwaysLoadOnClient

• **AlwaysLoadOnClient**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AlwaysLoadOnClient](ue_ue.PrimitiveComponent.md#alwaysloadonclient)

___

### AlwaysLoadOnServer

• **AlwaysLoadOnServer**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AlwaysLoadOnServer](ue_ue.PrimitiveComponent.md#alwaysloadonserver)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AssetUserData](ue_ue.PrimitiveComponent.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AttachChildren](ue_ue.PrimitiveComponent.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AttachParent](ue_ue.PrimitiveComponent.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AttachSocketName](ue_ue.PrimitiveComponent.md#attachsocketname)

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[BodyInstance](ue_ue.PrimitiveComponent.md#bodyinstance)

___

### BoundsScale

• **BoundsScale**: `number`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[BoundsScale](ue_ue.PrimitiveComponent.md#boundsscale)

___

### CachedMaxDrawDistance

• **CachedMaxDrawDistance**: `number`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[CachedMaxDrawDistance](ue_ue.PrimitiveComponent.md#cachedmaxdrawdistance)

___

### CanBeCharacterBase

• **CanBeCharacterBase**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[CanBeCharacterBase](ue_ue.PrimitiveComponent.md#canbecharacterbase)

___

### CanCharacterStepUpOn

• **CanCharacterStepUpOn**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[CanCharacterStepUpOn](ue_ue.PrimitiveComponent.md#cancharacterstepupon)

___

### CastShadow

• **CastShadow**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[CastShadow](ue_ue.PrimitiveComponent.md#castshadow)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[ClientAttachedChildren](ue_ue.PrimitiveComponent.md#clientattachedchildren)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[ComponentTags](ue_ue.PrimitiveComponent.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[ComponentVelocity](ue_ue.PrimitiveComponent.md#componentvelocity)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[CreationMethod](ue_ue.PrimitiveComponent.md#creationmethod)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[CustomDepthStencilValue](ue_ue.PrimitiveComponent.md#customdepthstencilvalue)

___

### CustomDepthStencilWriteMask

• **CustomDepthStencilWriteMask**: [`ERendererStencilMask`](../enums/ue_ue.ERendererStencilMask.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[CustomDepthStencilWriteMask](ue_ue.PrimitiveComponent.md#customdepthstencilwritemask)

___

### CustomPrimitiveData

• **CustomPrimitiveData**: [`CustomPrimitiveData`](ue_ue.CustomPrimitiveData.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[CustomPrimitiveData](ue_ue.PrimitiveComponent.md#customprimitivedata)

___

### DepthPriorityGroup

• **DepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[DepthPriorityGroup](ue_ue.PrimitiveComponent.md#depthprioritygroup)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[DetailMode](ue_ue.PrimitiveComponent.md#detailmode)

___

### ExcludeForSpecificHLODLevels

• **ExcludeForSpecificHLODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[ExcludeForSpecificHLODLevels](ue_ue.PrimitiveComponent.md#excludeforspecifichlodlevels)

___

### Font

• **Font**: [`Font`](ue_ue.Font.md)

___

### HorizSpacingAdjust

• **HorizSpacingAdjust**: `number`

___

### HorizontalAlignment

• **HorizontalAlignment**: [`EHorizTextAligment`](../enums/ue_ue.EHorizTextAligment.md)

___

### IndirectLightingCacheQuality

• **IndirectLightingCacheQuality**: [`EIndirectLightingCacheQuality`](../enums/ue_ue.EIndirectLightingCacheQuality.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[IndirectLightingCacheQuality](ue_ue.PrimitiveComponent.md#indirectlightingcachequality)

___

### InvDefaultSize

• **InvDefaultSize**: `number`

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[LDMaxDrawDistance](ue_ue.PrimitiveComponent.md#ldmaxdrawdistance)

___

### LODParentPrimitive

• **LODParentPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[LODParentPrimitive](ue_ue.PrimitiveComponent.md#lodparentprimitive)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[LightingChannels](ue_ue.PrimitiveComponent.md#lightingchannels)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[LightmapType](ue_ue.PrimitiveComponent.md#lightmaptype)

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[LpvBiasMultiplier](ue_ue.PrimitiveComponent.md#lpvbiasmultiplier)

___

### MinDrawDistance

• **MinDrawDistance**: `number`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[MinDrawDistance](ue_ue.PrimitiveComponent.md#mindrawdistance)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[Mobility](ue_ue.PrimitiveComponent.md#mobility)

___

### MoveIgnoreActors

• **MoveIgnoreActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[MoveIgnoreActors](ue_ue.PrimitiveComponent.md#moveignoreactors)

___

### MoveIgnoreComponents

• **MoveIgnoreComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[MoveIgnoreComponents](ue_ue.PrimitiveComponent.md#moveignorecomponents)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnBeginCursorOver](ue_ue.PrimitiveComponent.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnClicked](ue_ue.PrimitiveComponent.md#onclicked)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnComponentActivated](ue_ue.PrimitiveComponent.md#oncomponentactivated)

___

### OnComponentBeginOverlap

• **OnComponentBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`, `bFromSweep`: `boolean`, `SweepResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnComponentBeginOverlap](ue_ue.PrimitiveComponent.md#oncomponentbeginoverlap)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnComponentDeactivated](ue_ue.PrimitiveComponent.md#oncomponentdeactivated)

___

### OnComponentEndOverlap

• **OnComponentEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`) => `void`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnComponentEndOverlap](ue_ue.PrimitiveComponent.md#oncomponentendoverlap)

___

### OnComponentHit

• **OnComponentHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`HitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnComponentHit](ue_ue.PrimitiveComponent.md#oncomponenthit)

___

### OnComponentSleep

• **OnComponentSleep**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SleepingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnComponentSleep](ue_ue.PrimitiveComponent.md#oncomponentsleep)

___

### OnComponentWake

• **OnComponentWake**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`WakingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnComponentWake](ue_ue.PrimitiveComponent.md#oncomponentwake)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnEndCursorOver](ue_ue.PrimitiveComponent.md#onendcursorover)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnInputTouchBegin](ue_ue.PrimitiveComponent.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnInputTouchEnd](ue_ue.PrimitiveComponent.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnInputTouchEnter](ue_ue.PrimitiveComponent.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnInputTouchLeave](ue_ue.PrimitiveComponent.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnReleased](ue_ue.PrimitiveComponent.md#onreleased)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[PhysicsVolume](ue_ue.PrimitiveComponent.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.PrimitiveComponent.md#physicsvolumechangeddelegate)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[PrimaryComponentTick](ue_ue.PrimitiveComponent.md#primarycomponenttick)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[RelativeLocation](ue_ue.PrimitiveComponent.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[RelativeRotation](ue_ue.PrimitiveComponent.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[RelativeScale3D](ue_ue.PrimitiveComponent.md#relativescale3d)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[RuntimeVirtualTextures](ue_ue.PrimitiveComponent.md#runtimevirtualtextures)

___

### Text

• **Text**: `string`

___

### TextMaterial

• **TextMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### TextRenderColor

• **TextRenderColor**: [`Color`](ue_ue_s.Color.md)

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[TranslucencySortPriority](ue_ue.PrimitiveComponent.md#translucencysortpriority)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[UCSModifiedProperties](ue_ue.PrimitiveComponent.md#ucsmodifiedproperties)

___

### VertSpacingAdjust

• **VertSpacingAdjust**: `number`

___

### VerticalAlignment

• **VerticalAlignment**: [`EVerticalTextAligment`](../enums/ue_ue.EVerticalTextAligment.md)

___

### ViewOwnerDepthPriorityGroup

• **ViewOwnerDepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[ViewOwnerDepthPriorityGroup](ue_ue.PrimitiveComponent.md#viewownerdepthprioritygroup)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[VirtualTextureCullMips](ue_ue.PrimitiveComponent.md#virtualtexturecullmips)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[VirtualTextureLodBias](ue_ue.PrimitiveComponent.md#virtualtexturelodbias)

___

### VirtualTextureMinCoverage

• **VirtualTextureMinCoverage**: `number`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[VirtualTextureMinCoverage](ue_ue.PrimitiveComponent.md#virtualtexturemincoverage)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[VirtualTextureRenderPassType](ue_ue.PrimitiveComponent.md#virtualtexturerenderpasstype)

___

### VisibilityId

• **VisibilityId**: `number`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[VisibilityId](ue_ue.PrimitiveComponent.md#visibilityid)

___

### WorldSize

• **WorldSize**: `number`

___

### XScale

• **XScale**: `number`

___

### YScale

• **YScale**: `number`

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[__tid_ActorComponent__](ue_ue.PrimitiveComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[__tid_Object__](ue_ue.PrimitiveComponent.md#__tid_object__)

___

### \_\_tid\_PrimitiveComponent\_\_

• **\_\_tid\_PrimitiveComponent\_\_**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[__tid_PrimitiveComponent__](ue_ue.PrimitiveComponent.md#__tid_primitivecomponent__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[__tid_SceneComponent__](ue_ue.PrimitiveComponent.md#__tid_scenecomponent__)

___

### \_\_tid\_TextRenderComponent\_\_

• **\_\_tid\_TextRenderComponent\_\_**: `boolean`

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bAbsoluteLocation](ue_ue.PrimitiveComponent.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bAbsoluteRotation](ue_ue.PrimitiveComponent.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bAbsoluteScale](ue_ue.PrimitiveComponent.md#babsolutescale)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bAffectDistanceFieldLighting](ue_ue.PrimitiveComponent.md#baffectdistancefieldlighting)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bAffectDynamicIndirectLighting](ue_ue.PrimitiveComponent.md#baffectdynamicindirectlighting)

___

### bAllowCullDistanceVolume

• **bAllowCullDistanceVolume**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bAllowCullDistanceVolume](ue_ue.PrimitiveComponent.md#ballowculldistancevolume)

___

### bAlwaysCreatePhysicsState

• **bAlwaysCreatePhysicsState**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bAlwaysCreatePhysicsState](ue_ue.PrimitiveComponent.md#balwayscreatephysicsstate)

___

### bAlwaysRenderAsText

• **bAlwaysRenderAsText**: `boolean`

___

### bApplyImpulseOnDamage

• **bApplyImpulseOnDamage**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bApplyImpulseOnDamage](ue_ue.PrimitiveComponent.md#bapplyimpulseondamage)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bAutoActivate](ue_ue.PrimitiveComponent.md#bautoactivate)

___

### bBatchImpostersAsInstances

• **bBatchImpostersAsInstances**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bBatchImpostersAsInstances](ue_ue.PrimitiveComponent.md#bbatchimpostersasinstances)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.PrimitiveComponent.md#bboundschangetriggersstreamingdatarebuild)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bCanEverAffectNavigation](ue_ue.PrimitiveComponent.md#bcaneveraffectnavigation)

___

### bCastCinematicShadow

• **bCastCinematicShadow**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bCastCinematicShadow](ue_ue.PrimitiveComponent.md#bcastcinematicshadow)

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bCastDynamicShadow](ue_ue.PrimitiveComponent.md#bcastdynamicshadow)

___

### bCastFarShadow

• **bCastFarShadow**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bCastFarShadow](ue_ue.PrimitiveComponent.md#bcastfarshadow)

___

### bCastHiddenShadow

• **bCastHiddenShadow**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bCastHiddenShadow](ue_ue.PrimitiveComponent.md#bcasthiddenshadow)

___

### bCastInsetShadow

• **bCastInsetShadow**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bCastInsetShadow](ue_ue.PrimitiveComponent.md#bcastinsetshadow)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bCastShadowAsTwoSided](ue_ue.PrimitiveComponent.md#bcastshadowastwosided)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bCastStaticShadow](ue_ue.PrimitiveComponent.md#bcaststaticshadow)

___

### bCastVolumetricTranslucentShadow

• **bCastVolumetricTranslucentShadow**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bCastVolumetricTranslucentShadow](ue_ue.PrimitiveComponent.md#bcastvolumetrictranslucentshadow)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bComponentToWorldUpdated](ue_ue.PrimitiveComponent.md#bcomponenttoworldupdated)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bCreatedByConstructionScript](ue_ue.PrimitiveComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bEditableWhenInherited](ue_ue.PrimitiveComponent.md#beditablewheninherited)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bEnableAutoLODGeneration](ue_ue.PrimitiveComponent.md#benableautolodgeneration)

___

### bExcludeFromLightAttachmentGroup

• **bExcludeFromLightAttachmentGroup**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bExcludeFromLightAttachmentGroup](ue_ue.PrimitiveComponent.md#bexcludefromlightattachmentgroup)

___

### bForceMipStreaming

• **bForceMipStreaming**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bForceMipStreaming](ue_ue.PrimitiveComponent.md#bforcemipstreaming)

___

### bGenerateOverlapEvents

• **bGenerateOverlapEvents**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bGenerateOverlapEvents](ue_ue.PrimitiveComponent.md#bgenerateoverlapevents)

___

### bHasCustomNavigableGeometry

• **bHasCustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bHasCustomNavigableGeometry](ue_ue.PrimitiveComponent.md#bhascustomnavigablegeometry)

___

### bHasMotionBlurVelocityMeshes

• **bHasMotionBlurVelocityMeshes**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bHasMotionBlurVelocityMeshes](ue_ue.PrimitiveComponent.md#bhasmotionblurvelocitymeshes)

___

### bHasPerInstanceHitProxies

• **bHasPerInstanceHitProxies**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bHasPerInstanceHitProxies](ue_ue.PrimitiveComponent.md#bhasperinstancehitproxies)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bHiddenInGame](ue_ue.PrimitiveComponent.md#bhiddeningame)

___

### bIgnoreRadialForce

• **bIgnoreRadialForce**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bIgnoreRadialForce](ue_ue.PrimitiveComponent.md#bignoreradialforce)

___

### bIgnoreRadialImpulse

• **bIgnoreRadialImpulse**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bIgnoreRadialImpulse](ue_ue.PrimitiveComponent.md#bignoreradialimpulse)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bInstanceComponent](ue_ue.PrimitiveComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bIsActive](ue_ue.PrimitiveComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bIsEditorOnly](ue_ue.PrimitiveComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bIsVisualizationComponent](ue_ue.PrimitiveComponent.md#bisvisualizationcomponent)

___

### bLightAsIfStatic

• **bLightAsIfStatic**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bLightAsIfStatic](ue_ue.PrimitiveComponent.md#blightasifstatic)

___

### bLightAttachmentsAsGroup

• **bLightAttachmentsAsGroup**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bLightAttachmentsAsGroup](ue_ue.PrimitiveComponent.md#blightattachmentsasgroup)

___

### bMultiBodyOverlap

• **bMultiBodyOverlap**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bMultiBodyOverlap](ue_ue.PrimitiveComponent.md#bmultibodyoverlap)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bNetAddressable](ue_ue.PrimitiveComponent.md#bnetaddressable)

___

### bNeverDistanceCull

• **bNeverDistanceCull**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bNeverDistanceCull](ue_ue.PrimitiveComponent.md#bneverdistancecull)

___

### bOnlyOwnerSee

• **bOnlyOwnerSee**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bOnlyOwnerSee](ue_ue.PrimitiveComponent.md#bonlyownersee)

___

### bOwnerNoSee

• **bOwnerNoSee**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bOwnerNoSee](ue_ue.PrimitiveComponent.md#bownernosee)

___

### bReceiveMobileCSMShadows

• **bReceiveMobileCSMShadows**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bReceiveMobileCSMShadows](ue_ue.PrimitiveComponent.md#breceivemobilecsmshadows)

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bReceivesDecals](ue_ue.PrimitiveComponent.md#breceivesdecals)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bRenderCustomDepth](ue_ue.PrimitiveComponent.md#brendercustomdepth)

___

### bRenderInDepthPass

• **bRenderInDepthPass**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bRenderInDepthPass](ue_ue.PrimitiveComponent.md#brenderindepthpass)

___

### bRenderInMainPass

• **bRenderInMainPass**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bRenderInMainPass](ue_ue.PrimitiveComponent.md#brenderinmainpass)

___

### bReplicatePhysicsToAutonomousProxy

• **bReplicatePhysicsToAutonomousProxy**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bReplicatePhysicsToAutonomousProxy](ue_ue.PrimitiveComponent.md#breplicatephysicstoautonomousproxy)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bReplicates](ue_ue.PrimitiveComponent.md#breplicates)

___

### bReturnMaterialOnMove

• **bReturnMaterialOnMove**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bReturnMaterialOnMove](ue_ue.PrimitiveComponent.md#breturnmaterialonmove)

___

### bSelectable

• **bSelectable**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bSelectable](ue_ue.PrimitiveComponent.md#bselectable)

___

### bSelfShadowOnly

• **bSelfShadowOnly**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bSelfShadowOnly](ue_ue.PrimitiveComponent.md#bselfshadowonly)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bShouldBeAttached](ue_ue.PrimitiveComponent.md#bshouldbeattached)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.PrimitiveComponent.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.PrimitiveComponent.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.PrimitiveComponent.md#bshouldupdatephysicsvolume)

___

### bSingleSampleShadowFromStationaryLights

• **bSingleSampleShadowFromStationaryLights**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bSingleSampleShadowFromStationaryLights](ue_ue.PrimitiveComponent.md#bsinglesampleshadowfromstationarylights)

___

### bTraceComplexOnMove

• **bTraceComplexOnMove**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bTraceComplexOnMove](ue_ue.PrimitiveComponent.md#btracecomplexonmove)

___

### bTreatAsBackgroundForOcclusion

• **bTreatAsBackgroundForOcclusion**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bTreatAsBackgroundForOcclusion](ue_ue.PrimitiveComponent.md#btreatasbackgroundforocclusion)

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bUseAsOccluder](ue_ue.PrimitiveComponent.md#buseasoccluder)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bUseAttachParentBound](ue_ue.PrimitiveComponent.md#buseattachparentbound)

___

### bUseEditorCompositing

• **bUseEditorCompositing**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bUseEditorCompositing](ue_ue.PrimitiveComponent.md#buseeditorcompositing)

___

### bUseMaxLODAsImposter

• **bUseMaxLODAsImposter**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bUseMaxLODAsImposter](ue_ue.PrimitiveComponent.md#busemaxlodasimposter)

___

### bUseViewOwnerDepthPriorityGroup

• **bUseViewOwnerDepthPriorityGroup**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bUseViewOwnerDepthPriorityGroup](ue_ue.PrimitiveComponent.md#buseviewownerdepthprioritygroup)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bVisible](ue_ue.PrimitiveComponent.md#bvisible)

___

### bVisibleInRayTracing

• **bVisibleInRayTracing**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bVisibleInRayTracing](ue_ue.PrimitiveComponent.md#bvisibleinraytracing)

___

### bVisibleInReflectionCaptures

• **bVisibleInReflectionCaptures**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bVisibleInReflectionCaptures](ue_ue.PrimitiveComponent.md#bvisibleinreflectioncaptures)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[bVisualizeComponent](ue_ue.PrimitiveComponent.md#bvisualizecomponent)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[Activate](ue_ue.PrimitiveComponent.md#activate)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AddAngularImpulse](ue_ue.PrimitiveComponent.md#addangularimpulse)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AddAngularImpulseInDegrees](ue_ue.PrimitiveComponent.md#addangularimpulseindegrees)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AddAngularImpulseInRadians](ue_ue.PrimitiveComponent.md#addangularimpulseinradians)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AddForce](ue_ue.PrimitiveComponent.md#addforce)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AddForceAtLocation](ue_ue.PrimitiveComponent.md#addforceatlocation)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AddForceAtLocationLocal](ue_ue.PrimitiveComponent.md#addforceatlocationlocal)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AddImpulse](ue_ue.PrimitiveComponent.md#addimpulse)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AddImpulseAtLocation](ue_ue.PrimitiveComponent.md#addimpulseatlocation)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AddRadialForce](ue_ue.PrimitiveComponent.md#addradialforce)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AddRadialImpulse](ue_ue.PrimitiveComponent.md#addradialimpulse)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AddTickPrerequisiteActor](ue_ue.PrimitiveComponent.md#addtickprerequisiteactor)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AddTickPrerequisiteComponent](ue_ue.PrimitiveComponent.md#addtickprerequisitecomponent)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AddTorque](ue_ue.PrimitiveComponent.md#addtorque)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AddTorqueInDegrees](ue_ue.PrimitiveComponent.md#addtorqueindegrees)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[AddTorqueInRadians](ue_ue.PrimitiveComponent.md#addtorqueinradians)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[CanCharacterStepUp](ue_ue.PrimitiveComponent.md#cancharacterstepup)

___

### ClearMoveIgnoreActors

▸ **ClearMoveIgnoreActors**(): `void`

#### Returns

`void`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[ClearMoveIgnoreActors](ue_ue.PrimitiveComponent.md#clearmoveignoreactors)

___

### ClearMoveIgnoreComponents

▸ **ClearMoveIgnoreComponents**(): `void`

#### Returns

`void`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[ClearMoveIgnoreComponents](ue_ue.PrimitiveComponent.md#clearmoveignorecomponents)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[ComponentHasTag](ue_ue.PrimitiveComponent.md#componenthastag)

___

### CopyArrayOfMoveIgnoreActors

▸ **CopyArrayOfMoveIgnoreActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[CopyArrayOfMoveIgnoreActors](ue_ue.PrimitiveComponent.md#copyarrayofmoveignoreactors)

___

### CopyArrayOfMoveIgnoreComponents

▸ **CopyArrayOfMoveIgnoreComponents**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[CopyArrayOfMoveIgnoreComponents](ue_ue.PrimitiveComponent.md#copyarrayofmoveignorecomponents)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[CreateAndSetMaterialInstanceDynamic](ue_ue.PrimitiveComponent.md#createandsetmaterialinstancedynamic)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.PrimitiveComponent.md#createandsetmaterialinstancedynamicfrommaterial)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[CreateDefaultSubobject](ue_ue.PrimitiveComponent.md#createdefaultsubobject)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[CreateDynamicMaterialInstance](ue_ue.PrimitiveComponent.md#createdynamicmaterialinstance)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[Deactivate](ue_ue.PrimitiveComponent.md#deactivate)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[DetachFromParent](ue_ue.PrimitiveComponent.md#detachfromparent)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[DoesSocketExist](ue_ue.PrimitiveComponent.md#doessocketexist)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[ExecuteUbergraph](ue_ue.PrimitiveComponent.md#executeubergraph)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetAllSocketNames](ue_ue.PrimitiveComponent.md#getallsocketnames)

___

### GetAngularDamping

▸ **GetAngularDamping**(): `number`

#### Returns

`number`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetAngularDamping](ue_ue.PrimitiveComponent.md#getangulardamping)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetAttachParent](ue_ue.PrimitiveComponent.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetAttachSocketName](ue_ue.PrimitiveComponent.md#getattachsocketname)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetCenterOfMass](ue_ue.PrimitiveComponent.md#getcenterofmass)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetChildComponent](ue_ue.PrimitiveComponent.md#getchildcomponent)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetChildrenComponents](ue_ue.PrimitiveComponent.md#getchildrencomponents)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetClass](ue_ue.PrimitiveComponent.md#getclass)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetClosestPointOnCollision](ue_ue.PrimitiveComponent.md#getclosestpointoncollision)

___

### GetCollisionEnabled

▸ **GetCollisionEnabled**(): [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Returns

[`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetCollisionEnabled](ue_ue.PrimitiveComponent.md#getcollisionenabled)

___

### GetCollisionObjectType

▸ **GetCollisionObjectType**(): [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Returns

[`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetCollisionObjectType](ue_ue.PrimitiveComponent.md#getcollisionobjecttype)

___

### GetCollisionProfileName

▸ **GetCollisionProfileName**(): `string`

#### Returns

`string`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetCollisionProfileName](ue_ue.PrimitiveComponent.md#getcollisionprofilename)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetCollisionResponseToChannel](ue_ue.PrimitiveComponent.md#getcollisionresponsetochannel)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetComponentTickInterval](ue_ue.PrimitiveComponent.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetComponentVelocity](ue_ue.PrimitiveComponent.md#getcomponentvelocity)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetForwardVector](ue_ue.PrimitiveComponent.md#getforwardvector)

___

### GetGenerateOverlapEvents

▸ **GetGenerateOverlapEvents**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetGenerateOverlapEvents](ue_ue.PrimitiveComponent.md#getgenerateoverlapevents)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetInertiaTensor](ue_ue.PrimitiveComponent.md#getinertiatensor)

___

### GetLinearDamping

▸ **GetLinearDamping**(): `number`

#### Returns

`number`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetLinearDamping](ue_ue.PrimitiveComponent.md#getlineardamping)

___

### GetMass

▸ **GetMass**(): `number`

#### Returns

`number`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetMass](ue_ue.PrimitiveComponent.md#getmass)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetMassScale](ue_ue.PrimitiveComponent.md#getmassscale)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetMaterial](ue_ue.PrimitiveComponent.md#getmaterial)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetMaterialFromCollisionFaceIndex](ue_ue.PrimitiveComponent.md#getmaterialfromcollisionfaceindex)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetName](ue_ue.PrimitiveComponent.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetNumChildrenComponents](ue_ue.PrimitiveComponent.md#getnumchildrencomponents)

___

### GetNumMaterials

▸ **GetNumMaterials**(): `number`

#### Returns

`number`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetNumMaterials](ue_ue.PrimitiveComponent.md#getnummaterials)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetOuter](ue_ue.PrimitiveComponent.md#getouter)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetOverlappingActors](ue_ue.PrimitiveComponent.md#getoverlappingactors)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetOverlappingComponents](ue_ue.PrimitiveComponent.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetOwner](ue_ue.PrimitiveComponent.md#getowner)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetParentComponents](ue_ue.PrimitiveComponent.md#getparentcomponents)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetPhysicsAngularVelocity](ue_ue.PrimitiveComponent.md#getphysicsangularvelocity)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetPhysicsAngularVelocityInDegrees](ue_ue.PrimitiveComponent.md#getphysicsangularvelocityindegrees)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetPhysicsAngularVelocityInRadians](ue_ue.PrimitiveComponent.md#getphysicsangularvelocityinradians)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetPhysicsLinearVelocity](ue_ue.PrimitiveComponent.md#getphysicslinearvelocity)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetPhysicsLinearVelocityAtPoint](ue_ue.PrimitiveComponent.md#getphysicslinearvelocityatpoint)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetPhysicsVolume](ue_ue.PrimitiveComponent.md#getphysicsvolume)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetRelativeTransform](ue_ue.PrimitiveComponent.md#getrelativetransform)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetRightVector](ue_ue.PrimitiveComponent.md#getrightvector)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.PrimitiveComponent.md#getshouldupdatephysicsvolume)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetSocketLocation](ue_ue.PrimitiveComponent.md#getsocketlocation)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetSocketQuaternion](ue_ue.PrimitiveComponent.md#getsocketquaternion)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetSocketRotation](ue_ue.PrimitiveComponent.md#getsocketrotation)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetSocketTransform](ue_ue.PrimitiveComponent.md#getsockettransform)

___

### GetTextLocalSize

▸ **GetTextLocalSize**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetTextWorldSize

▸ **GetTextWorldSize**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetUpVector](ue_ue.PrimitiveComponent.md#getupvector)

___

### GetWalkableSlopeOverride

▸ **GetWalkableSlopeOverride**(): [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Returns

[`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetWalkableSlopeOverride](ue_ue.PrimitiveComponent.md#getwalkableslopeoverride)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[GetWorld](ue_ue.PrimitiveComponent.md#getworld)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[IgnoreActorWhenMoving](ue_ue.PrimitiveComponent.md#ignoreactorwhenmoving)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[IgnoreComponentWhenMoving](ue_ue.PrimitiveComponent.md#ignorecomponentwhenmoving)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[IsActive](ue_ue.PrimitiveComponent.md#isactive)

___

### IsAnyRigidBodyAwake

▸ **IsAnyRigidBodyAwake**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[IsAnyRigidBodyAwake](ue_ue.PrimitiveComponent.md#isanyrigidbodyawake)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[IsAnySimulatingPhysics](ue_ue.PrimitiveComponent.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[IsBeingDestroyed](ue_ue.PrimitiveComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[IsComponentTickEnabled](ue_ue.PrimitiveComponent.md#iscomponenttickenabled)

___

### IsGravityEnabled

▸ **IsGravityEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[IsGravityEnabled](ue_ue.PrimitiveComponent.md#isgravityenabled)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[IsOverlappingActor](ue_ue.PrimitiveComponent.md#isoverlappingactor)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[IsOverlappingComponent](ue_ue.PrimitiveComponent.md#isoverlappingcomponent)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[IsSimulatingPhysics](ue_ue.PrimitiveComponent.md#issimulatingphysics)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[IsVisible](ue_ue.PrimitiveComponent.md#isvisible)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_AddLocalOffset](ue_ue.PrimitiveComponent.md#k2_addlocaloffset)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_AddLocalRotation](ue_ue.PrimitiveComponent.md#k2_addlocalrotation)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_AddLocalTransform](ue_ue.PrimitiveComponent.md#k2_addlocaltransform)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_AddRelativeLocation](ue_ue.PrimitiveComponent.md#k2_addrelativelocation)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_AddRelativeRotation](ue_ue.PrimitiveComponent.md#k2_addrelativerotation)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_AddWorldOffset](ue_ue.PrimitiveComponent.md#k2_addworldoffset)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_AddWorldRotation](ue_ue.PrimitiveComponent.md#k2_addworldrotation)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_AddWorldTransform](ue_ue.PrimitiveComponent.md#k2_addworldtransform)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_AttachTo](ue_ue.PrimitiveComponent.md#k2_attachto)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_AttachToComponent](ue_ue.PrimitiveComponent.md#k2_attachtocomponent)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_BoxOverlapComponent](ue_ue.PrimitiveComponent.md#k2_boxoverlapcomponent)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_DestroyComponent](ue_ue.PrimitiveComponent.md#k2_destroycomponent)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_DetachFromComponent](ue_ue.PrimitiveComponent.md#k2_detachfromcomponent)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_GetComponentLocation](ue_ue.PrimitiveComponent.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_GetComponentRotation](ue_ue.PrimitiveComponent.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_GetComponentScale](ue_ue.PrimitiveComponent.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_GetComponentToWorld](ue_ue.PrimitiveComponent.md#k2_getcomponenttoworld)

___

### K2\_IsCollisionEnabled

▸ **K2_IsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_IsCollisionEnabled](ue_ue.PrimitiveComponent.md#k2_iscollisionenabled)

___

### K2\_IsPhysicsCollisionEnabled

▸ **K2_IsPhysicsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_IsPhysicsCollisionEnabled](ue_ue.PrimitiveComponent.md#k2_isphysicscollisionenabled)

___

### K2\_IsQueryCollisionEnabled

▸ **K2_IsQueryCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_IsQueryCollisionEnabled](ue_ue.PrimitiveComponent.md#k2_isquerycollisionenabled)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_LineTraceComponent](ue_ue.PrimitiveComponent.md#k2_linetracecomponent)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_SetRelativeLocation](ue_ue.PrimitiveComponent.md#k2_setrelativelocation)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.PrimitiveComponent.md#k2_setrelativelocationandrotation)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_SetRelativeRotation](ue_ue.PrimitiveComponent.md#k2_setrelativerotation)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_SetRelativeTransform](ue_ue.PrimitiveComponent.md#k2_setrelativetransform)

___

### K2\_SetText

▸ **K2_SetText**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `string` |

#### Returns

`void`

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_SetWorldLocation](ue_ue.PrimitiveComponent.md#k2_setworldlocation)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.PrimitiveComponent.md#k2_setworldlocationandrotation)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_SetWorldRotation](ue_ue.PrimitiveComponent.md#k2_setworldrotation)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_SetWorldTransform](ue_ue.PrimitiveComponent.md#k2_setworldtransform)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_SphereOverlapComponent](ue_ue.PrimitiveComponent.md#k2_sphereoverlapcomponent)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[K2_SphereTraceComponent](ue_ue.PrimitiveComponent.md#k2_spheretracecomponent)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnRep_AttachChildren](ue_ue.PrimitiveComponent.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnRep_AttachParent](ue_ue.PrimitiveComponent.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnRep_AttachSocketName](ue_ue.PrimitiveComponent.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnRep_IsActive](ue_ue.PrimitiveComponent.md#onrep_isactive)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnRep_Transform](ue_ue.PrimitiveComponent.md#onrep_transform)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[OnRep_Visibility](ue_ue.PrimitiveComponent.md#onrep_visibility)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[PutRigidBodyToSleep](ue_ue.PrimitiveComponent.md#putrigidbodytosleep)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[ReceiveBeginPlay](ue_ue.PrimitiveComponent.md#receivebeginplay)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[ReceiveEndPlay](ue_ue.PrimitiveComponent.md#receiveendplay)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[ReceiveTick](ue_ue.PrimitiveComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[RegisterComponent](ue_ue.PrimitiveComponent.md#registercomponent)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[RemoveTickPrerequisiteActor](ue_ue.PrimitiveComponent.md#removetickprerequisiteactor)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.PrimitiveComponent.md#removetickprerequisitecomponent)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[ResetRelativeTransform](ue_ue.PrimitiveComponent.md#resetrelativetransform)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[ScaleByMomentOfInertia](ue_ue.PrimitiveComponent.md#scalebymomentofinertia)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetAbsolute](ue_ue.PrimitiveComponent.md#setabsolute)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetActive](ue_ue.PrimitiveComponent.md#setactive)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetAllMassScale](ue_ue.PrimitiveComponent.md#setallmassscale)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetAllPhysicsAngularVelocityInDegrees](ue_ue.PrimitiveComponent.md#setallphysicsangularvelocityindegrees)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetAllPhysicsAngularVelocityInRadians](ue_ue.PrimitiveComponent.md#setallphysicsangularvelocityinradians)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetAllPhysicsLinearVelocity](ue_ue.PrimitiveComponent.md#setallphysicslinearvelocity)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetAllUseCCD](ue_ue.PrimitiveComponent.md#setalluseccd)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetAngularDamping](ue_ue.PrimitiveComponent.md#setangulardamping)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetAutoActivate](ue_ue.PrimitiveComponent.md#setautoactivate)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetBoundsScale](ue_ue.PrimitiveComponent.md#setboundsscale)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetCastInsetShadow](ue_ue.PrimitiveComponent.md#setcastinsetshadow)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetCastShadow](ue_ue.PrimitiveComponent.md#setcastshadow)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetCenterOfMass](ue_ue.PrimitiveComponent.md#setcenterofmass)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetCollisionEnabled](ue_ue.PrimitiveComponent.md#setcollisionenabled)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetCollisionObjectType](ue_ue.PrimitiveComponent.md#setcollisionobjecttype)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetCollisionProfileName](ue_ue.PrimitiveComponent.md#setcollisionprofilename)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetCollisionResponseToAllChannels](ue_ue.PrimitiveComponent.md#setcollisionresponsetoallchannels)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetCollisionResponseToChannel](ue_ue.PrimitiveComponent.md#setcollisionresponsetochannel)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetComponentTickEnabled](ue_ue.PrimitiveComponent.md#setcomponenttickenabled)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetComponentTickInterval](ue_ue.PrimitiveComponent.md#setcomponenttickinterval)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetConstraintMode](ue_ue.PrimitiveComponent.md#setconstraintmode)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetCullDistance](ue_ue.PrimitiveComponent.md#setculldistance)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetCustomDepthStencilValue](ue_ue.PrimitiveComponent.md#setcustomdepthstencilvalue)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetCustomDepthStencilWriteMask](ue_ue.PrimitiveComponent.md#setcustomdepthstencilwritemask)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetCustomPrimitiveDataFloat](ue_ue.PrimitiveComponent.md#setcustomprimitivedatafloat)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetCustomPrimitiveDataVector2](ue_ue.PrimitiveComponent.md#setcustomprimitivedatavector2)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetCustomPrimitiveDataVector3](ue_ue.PrimitiveComponent.md#setcustomprimitivedatavector3)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetCustomPrimitiveDataVector4](ue_ue.PrimitiveComponent.md#setcustomprimitivedatavector4)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetEnableGravity](ue_ue.PrimitiveComponent.md#setenablegravity)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetExcludeFromLightAttachmentGroup](ue_ue.PrimitiveComponent.md#setexcludefromlightattachmentgroup)

___

### SetFont

▸ **SetFont**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Font`](ue_ue.Font.md)\> |

#### Returns

`void`

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetGenerateOverlapEvents](ue_ue.PrimitiveComponent.md#setgenerateoverlapevents)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetHiddenInGame](ue_ue.PrimitiveComponent.md#sethiddeningame)

___

### SetHorizSpacingAdjust

▸ **SetHorizSpacingAdjust**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

___

### SetHorizontalAlignment

▸ **SetHorizontalAlignment**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | [`EHorizTextAligment`](../enums/ue_ue.EHorizTextAligment.md) |

#### Returns

`void`

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetIsReplicated](ue_ue.PrimitiveComponent.md#setisreplicated)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetLightAttachmentsAsGroup](ue_ue.PrimitiveComponent.md#setlightattachmentsasgroup)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetLinearDamping](ue_ue.PrimitiveComponent.md#setlineardamping)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetMassOverrideInKg](ue_ue.PrimitiveComponent.md#setmassoverrideinkg)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetMassScale](ue_ue.PrimitiveComponent.md#setmassscale)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetMaterial](ue_ue.PrimitiveComponent.md#setmaterial)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetMaterialByName](ue_ue.PrimitiveComponent.md#setmaterialbyname)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetMobility](ue_ue.PrimitiveComponent.md#setmobility)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetNotifyRigidBodyCollision](ue_ue.PrimitiveComponent.md#setnotifyrigidbodycollision)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetOnlyOwnerSee](ue_ue.PrimitiveComponent.md#setonlyownersee)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetOwnerNoSee](ue_ue.PrimitiveComponent.md#setownernosee)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetPhysMaterialOverride](ue_ue.PrimitiveComponent.md#setphysmaterialoverride)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetPhysicsAngularVelocity](ue_ue.PrimitiveComponent.md#setphysicsangularvelocity)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetPhysicsAngularVelocityInDegrees](ue_ue.PrimitiveComponent.md#setphysicsangularvelocityindegrees)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetPhysicsAngularVelocityInRadians](ue_ue.PrimitiveComponent.md#setphysicsangularvelocityinradians)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetPhysicsLinearVelocity](ue_ue.PrimitiveComponent.md#setphysicslinearvelocity)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetPhysicsMaxAngularVelocity](ue_ue.PrimitiveComponent.md#setphysicsmaxangularvelocity)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetPhysicsMaxAngularVelocityInDegrees](ue_ue.PrimitiveComponent.md#setphysicsmaxangularvelocityindegrees)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetPhysicsMaxAngularVelocityInRadians](ue_ue.PrimitiveComponent.md#setphysicsmaxangularvelocityinradians)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetReceivesDecals](ue_ue.PrimitiveComponent.md#setreceivesdecals)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetRelativeScale3D](ue_ue.PrimitiveComponent.md#setrelativescale3d)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetRenderCustomDepth](ue_ue.PrimitiveComponent.md#setrendercustomdepth)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetRenderInMainPass](ue_ue.PrimitiveComponent.md#setrenderinmainpass)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.PrimitiveComponent.md#setshouldupdatephysicsvolume)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetSimulatePhysics](ue_ue.PrimitiveComponent.md#setsimulatephysics)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetSingleSampleShadowFromStationaryLights](ue_ue.PrimitiveComponent.md#setsinglesampleshadowfromstationarylights)

___

### SetText

▸ **SetText**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `string` |

#### Returns

`void`

___

### SetTextMaterial

▸ **SetTextMaterial**(`Material`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |

#### Returns

`void`

___

### SetTextRenderColor

▸ **SetTextRenderColor**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | [`Color`](ue_ue_s.Color.md) |

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetTickGroup](ue_ue.PrimitiveComponent.md#settickgroup)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetTickableWhenPaused](ue_ue.PrimitiveComponent.md#settickablewhenpaused)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetTranslucentSortPriority](ue_ue.PrimitiveComponent.md#settranslucentsortpriority)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetUseCCD](ue_ue.PrimitiveComponent.md#setuseccd)

___

### SetVertSpacingAdjust

▸ **SetVertSpacingAdjust**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

___

### SetVerticalAlignment

▸ **SetVerticalAlignment**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | [`EVerticalTextAligment`](../enums/ue_ue.EVerticalTextAligment.md) |

#### Returns

`void`

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetVisibility](ue_ue.PrimitiveComponent.md#setvisibility)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetWalkableSlopeOverride](ue_ue.PrimitiveComponent.md#setwalkableslopeoverride)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetWorldScale3D](ue_ue.PrimitiveComponent.md#setworldscale3d)

___

### SetWorldSize

▸ **SetWorldSize**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

___

### SetXScale

▸ **SetXScale**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

___

### SetYScale

▸ **SetYScale**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SetupAttachment](ue_ue.PrimitiveComponent.md#setupattachment)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[SnapTo](ue_ue.PrimitiveComponent.md#snapto)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[ToggleActive](ue_ue.PrimitiveComponent.md#toggleactive)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[ToggleVisibility](ue_ue.PrimitiveComponent.md#togglevisibility)

___

### WakeAllRigidBodies

▸ **WakeAllRigidBodies**(): `void`

#### Returns

`void`

#### Inherited from

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[WakeAllRigidBodies](ue_ue.PrimitiveComponent.md#wakeallrigidbodies)

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

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[WakeRigidBody](ue_ue.PrimitiveComponent.md#wakerigidbody)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TextRenderComponent`](ue_ue.TextRenderComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TextRenderComponent`](ue_ue.TextRenderComponent.md)

#### Overrides

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[Find](ue_ue.PrimitiveComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TextRenderComponent`](ue_ue.TextRenderComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TextRenderComponent`](ue_ue.TextRenderComponent.md)

#### Overrides

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[Load](ue_ue.PrimitiveComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PrimitiveComponent](ue_ue.PrimitiveComponent.md).[StaticClass](ue_ue.PrimitiveComponent.md#staticclass)
