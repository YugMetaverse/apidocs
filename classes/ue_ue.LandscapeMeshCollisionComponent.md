[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LandscapeMeshCollisionComponent

# Class: LandscapeMeshCollisionComponent

[ue/ue](../modules/ue_ue.md).LandscapeMeshCollisionComponent

## Hierarchy

- [`LandscapeHeightfieldCollisionComponent`](ue_ue.LandscapeHeightfieldCollisionComponent.md)

  ↳ **`LandscapeMeshCollisionComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.LandscapeMeshCollisionComponent.md#constructor)

### Properties

- [AlwaysLoadOnClient](ue_ue.LandscapeMeshCollisionComponent.md#alwaysloadonclient)
- [AlwaysLoadOnServer](ue_ue.LandscapeMeshCollisionComponent.md#alwaysloadonserver)
- [AssetUserData](ue_ue.LandscapeMeshCollisionComponent.md#assetuserdata)
- [AttachChildren](ue_ue.LandscapeMeshCollisionComponent.md#attachchildren)
- [AttachParent](ue_ue.LandscapeMeshCollisionComponent.md#attachparent)
- [AttachSocketName](ue_ue.LandscapeMeshCollisionComponent.md#attachsocketname)
- [BodyInstance](ue_ue.LandscapeMeshCollisionComponent.md#bodyinstance)
- [BoundsScale](ue_ue.LandscapeMeshCollisionComponent.md#boundsscale)
- [CachedLocalBox](ue_ue.LandscapeMeshCollisionComponent.md#cachedlocalbox)
- [CachedMaxDrawDistance](ue_ue.LandscapeMeshCollisionComponent.md#cachedmaxdrawdistance)
- [CanBeCharacterBase](ue_ue.LandscapeMeshCollisionComponent.md#canbecharacterbase)
- [CanCharacterStepUpOn](ue_ue.LandscapeMeshCollisionComponent.md#cancharacterstepupon)
- [CastShadow](ue_ue.LandscapeMeshCollisionComponent.md#castshadow)
- [ClientAttachedChildren](ue_ue.LandscapeMeshCollisionComponent.md#clientattachedchildren)
- [CollisionQuadFlags](ue_ue.LandscapeMeshCollisionComponent.md#collisionquadflags)
- [CollisionScale](ue_ue.LandscapeMeshCollisionComponent.md#collisionscale)
- [CollisionSizeQuads](ue_ue.LandscapeMeshCollisionComponent.md#collisionsizequads)
- [ComponentLayerInfos](ue_ue.LandscapeMeshCollisionComponent.md#componentlayerinfos)
- [ComponentTags](ue_ue.LandscapeMeshCollisionComponent.md#componenttags)
- [ComponentVelocity](ue_ue.LandscapeMeshCollisionComponent.md#componentvelocity)
- [CookedPhysicalMaterials](ue_ue.LandscapeMeshCollisionComponent.md#cookedphysicalmaterials)
- [CreationMethod](ue_ue.LandscapeMeshCollisionComponent.md#creationmethod)
- [CustomDepthStencilValue](ue_ue.LandscapeMeshCollisionComponent.md#customdepthstencilvalue)
- [CustomDepthStencilWriteMask](ue_ue.LandscapeMeshCollisionComponent.md#customdepthstencilwritemask)
- [CustomPrimitiveData](ue_ue.LandscapeMeshCollisionComponent.md#customprimitivedata)
- [DepthPriorityGroup](ue_ue.LandscapeMeshCollisionComponent.md#depthprioritygroup)
- [DetailMode](ue_ue.LandscapeMeshCollisionComponent.md#detailmode)
- [ExcludeForSpecificHLODLevels](ue_ue.LandscapeMeshCollisionComponent.md#excludeforspecifichlodlevels)
- [HeightfieldGuid](ue_ue.LandscapeMeshCollisionComponent.md#heightfieldguid)
- [IndirectLightingCacheQuality](ue_ue.LandscapeMeshCollisionComponent.md#indirectlightingcachequality)
- [LDMaxDrawDistance](ue_ue.LandscapeMeshCollisionComponent.md#ldmaxdrawdistance)
- [LODParentPrimitive](ue_ue.LandscapeMeshCollisionComponent.md#lodparentprimitive)
- [LightingChannels](ue_ue.LandscapeMeshCollisionComponent.md#lightingchannels)
- [LightmapType](ue_ue.LandscapeMeshCollisionComponent.md#lightmaptype)
- [LpvBiasMultiplier](ue_ue.LandscapeMeshCollisionComponent.md#lpvbiasmultiplier)
- [MeshGuid](ue_ue.LandscapeMeshCollisionComponent.md#meshguid)
- [MinDrawDistance](ue_ue.LandscapeMeshCollisionComponent.md#mindrawdistance)
- [Mobility](ue_ue.LandscapeMeshCollisionComponent.md#mobility)
- [MoveIgnoreActors](ue_ue.LandscapeMeshCollisionComponent.md#moveignoreactors)
- [MoveIgnoreComponents](ue_ue.LandscapeMeshCollisionComponent.md#moveignorecomponents)
- [OnBeginCursorOver](ue_ue.LandscapeMeshCollisionComponent.md#onbegincursorover)
- [OnClicked](ue_ue.LandscapeMeshCollisionComponent.md#onclicked)
- [OnComponentActivated](ue_ue.LandscapeMeshCollisionComponent.md#oncomponentactivated)
- [OnComponentBeginOverlap](ue_ue.LandscapeMeshCollisionComponent.md#oncomponentbeginoverlap)
- [OnComponentDeactivated](ue_ue.LandscapeMeshCollisionComponent.md#oncomponentdeactivated)
- [OnComponentEndOverlap](ue_ue.LandscapeMeshCollisionComponent.md#oncomponentendoverlap)
- [OnComponentHit](ue_ue.LandscapeMeshCollisionComponent.md#oncomponenthit)
- [OnComponentSleep](ue_ue.LandscapeMeshCollisionComponent.md#oncomponentsleep)
- [OnComponentWake](ue_ue.LandscapeMeshCollisionComponent.md#oncomponentwake)
- [OnEndCursorOver](ue_ue.LandscapeMeshCollisionComponent.md#onendcursorover)
- [OnInputTouchBegin](ue_ue.LandscapeMeshCollisionComponent.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.LandscapeMeshCollisionComponent.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.LandscapeMeshCollisionComponent.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.LandscapeMeshCollisionComponent.md#oninputtouchleave)
- [OnReleased](ue_ue.LandscapeMeshCollisionComponent.md#onreleased)
- [PhysicsVolume](ue_ue.LandscapeMeshCollisionComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.LandscapeMeshCollisionComponent.md#physicsvolumechangeddelegate)
- [PrimaryComponentTick](ue_ue.LandscapeMeshCollisionComponent.md#primarycomponenttick)
- [RelativeLocation](ue_ue.LandscapeMeshCollisionComponent.md#relativelocation)
- [RelativeRotation](ue_ue.LandscapeMeshCollisionComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.LandscapeMeshCollisionComponent.md#relativescale3d)
- [RenderComponent](ue_ue.LandscapeMeshCollisionComponent.md#rendercomponent)
- [RuntimeVirtualTextures](ue_ue.LandscapeMeshCollisionComponent.md#runtimevirtualtextures)
- [SectionBaseX](ue_ue.LandscapeMeshCollisionComponent.md#sectionbasex)
- [SectionBaseY](ue_ue.LandscapeMeshCollisionComponent.md#sectionbasey)
- [SimpleCollisionSizeQuads](ue_ue.LandscapeMeshCollisionComponent.md#simplecollisionsizequads)
- [TranslucencySortPriority](ue_ue.LandscapeMeshCollisionComponent.md#translucencysortpriority)
- [UCSModifiedProperties](ue_ue.LandscapeMeshCollisionComponent.md#ucsmodifiedproperties)
- [ViewOwnerDepthPriorityGroup](ue_ue.LandscapeMeshCollisionComponent.md#viewownerdepthprioritygroup)
- [VirtualTextureCullMips](ue_ue.LandscapeMeshCollisionComponent.md#virtualtexturecullmips)
- [VirtualTextureLodBias](ue_ue.LandscapeMeshCollisionComponent.md#virtualtexturelodbias)
- [VirtualTextureMinCoverage](ue_ue.LandscapeMeshCollisionComponent.md#virtualtexturemincoverage)
- [VirtualTextureRenderPassType](ue_ue.LandscapeMeshCollisionComponent.md#virtualtexturerenderpasstype)
- [VisibilityId](ue_ue.LandscapeMeshCollisionComponent.md#visibilityid)
- [\_\_tid\_ActorComponent\_\_](ue_ue.LandscapeMeshCollisionComponent.md#__tid_actorcomponent__)
- [\_\_tid\_LandscapeHeightfieldCollisionComponent\_\_](ue_ue.LandscapeMeshCollisionComponent.md#__tid_landscapeheightfieldcollisioncomponent__)
- [\_\_tid\_LandscapeMeshCollisionComponent\_\_](ue_ue.LandscapeMeshCollisionComponent.md#__tid_landscapemeshcollisioncomponent__)
- [\_\_tid\_Object\_\_](ue_ue.LandscapeMeshCollisionComponent.md#__tid_object__)
- [\_\_tid\_PrimitiveComponent\_\_](ue_ue.LandscapeMeshCollisionComponent.md#__tid_primitivecomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.LandscapeMeshCollisionComponent.md#__tid_scenecomponent__)
- [bAbsoluteLocation](ue_ue.LandscapeMeshCollisionComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.LandscapeMeshCollisionComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.LandscapeMeshCollisionComponent.md#babsolutescale)
- [bAffectDistanceFieldLighting](ue_ue.LandscapeMeshCollisionComponent.md#baffectdistancefieldlighting)
- [bAffectDynamicIndirectLighting](ue_ue.LandscapeMeshCollisionComponent.md#baffectdynamicindirectlighting)
- [bAllowCullDistanceVolume](ue_ue.LandscapeMeshCollisionComponent.md#ballowculldistancevolume)
- [bAlwaysCreatePhysicsState](ue_ue.LandscapeMeshCollisionComponent.md#balwayscreatephysicsstate)
- [bApplyImpulseOnDamage](ue_ue.LandscapeMeshCollisionComponent.md#bapplyimpulseondamage)
- [bAutoActivate](ue_ue.LandscapeMeshCollisionComponent.md#bautoactivate)
- [bBatchImpostersAsInstances](ue_ue.LandscapeMeshCollisionComponent.md#bbatchimpostersasinstances)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.LandscapeMeshCollisionComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.LandscapeMeshCollisionComponent.md#bcaneveraffectnavigation)
- [bCastCinematicShadow](ue_ue.LandscapeMeshCollisionComponent.md#bcastcinematicshadow)
- [bCastDynamicShadow](ue_ue.LandscapeMeshCollisionComponent.md#bcastdynamicshadow)
- [bCastFarShadow](ue_ue.LandscapeMeshCollisionComponent.md#bcastfarshadow)
- [bCastHiddenShadow](ue_ue.LandscapeMeshCollisionComponent.md#bcasthiddenshadow)
- [bCastInsetShadow](ue_ue.LandscapeMeshCollisionComponent.md#bcastinsetshadow)
- [bCastShadowAsTwoSided](ue_ue.LandscapeMeshCollisionComponent.md#bcastshadowastwosided)
- [bCastStaticShadow](ue_ue.LandscapeMeshCollisionComponent.md#bcaststaticshadow)
- [bCastVolumetricTranslucentShadow](ue_ue.LandscapeMeshCollisionComponent.md#bcastvolumetrictranslucentshadow)
- [bComponentToWorldUpdated](ue_ue.LandscapeMeshCollisionComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.LandscapeMeshCollisionComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.LandscapeMeshCollisionComponent.md#beditablewheninherited)
- [bEnableAutoLODGeneration](ue_ue.LandscapeMeshCollisionComponent.md#benableautolodgeneration)
- [bExcludeFromLightAttachmentGroup](ue_ue.LandscapeMeshCollisionComponent.md#bexcludefromlightattachmentgroup)
- [bForceMipStreaming](ue_ue.LandscapeMeshCollisionComponent.md#bforcemipstreaming)
- [bGenerateOverlapEvents](ue_ue.LandscapeMeshCollisionComponent.md#bgenerateoverlapevents)
- [bHasCustomNavigableGeometry](ue_ue.LandscapeMeshCollisionComponent.md#bhascustomnavigablegeometry)
- [bHasMotionBlurVelocityMeshes](ue_ue.LandscapeMeshCollisionComponent.md#bhasmotionblurvelocitymeshes)
- [bHasPerInstanceHitProxies](ue_ue.LandscapeMeshCollisionComponent.md#bhasperinstancehitproxies)
- [bHiddenInGame](ue_ue.LandscapeMeshCollisionComponent.md#bhiddeningame)
- [bIgnoreRadialForce](ue_ue.LandscapeMeshCollisionComponent.md#bignoreradialforce)
- [bIgnoreRadialImpulse](ue_ue.LandscapeMeshCollisionComponent.md#bignoreradialimpulse)
- [bInstanceComponent](ue_ue.LandscapeMeshCollisionComponent.md#binstancecomponent)
- [bIsActive](ue_ue.LandscapeMeshCollisionComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.LandscapeMeshCollisionComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.LandscapeMeshCollisionComponent.md#bisvisualizationcomponent)
- [bLightAsIfStatic](ue_ue.LandscapeMeshCollisionComponent.md#blightasifstatic)
- [bLightAttachmentsAsGroup](ue_ue.LandscapeMeshCollisionComponent.md#blightattachmentsasgroup)
- [bMultiBodyOverlap](ue_ue.LandscapeMeshCollisionComponent.md#bmultibodyoverlap)
- [bNetAddressable](ue_ue.LandscapeMeshCollisionComponent.md#bnetaddressable)
- [bNeverDistanceCull](ue_ue.LandscapeMeshCollisionComponent.md#bneverdistancecull)
- [bOnlyOwnerSee](ue_ue.LandscapeMeshCollisionComponent.md#bonlyownersee)
- [bOwnerNoSee](ue_ue.LandscapeMeshCollisionComponent.md#bownernosee)
- [bReceiveMobileCSMShadows](ue_ue.LandscapeMeshCollisionComponent.md#breceivemobilecsmshadows)
- [bReceivesDecals](ue_ue.LandscapeMeshCollisionComponent.md#breceivesdecals)
- [bRenderCustomDepth](ue_ue.LandscapeMeshCollisionComponent.md#brendercustomdepth)
- [bRenderInDepthPass](ue_ue.LandscapeMeshCollisionComponent.md#brenderindepthpass)
- [bRenderInMainPass](ue_ue.LandscapeMeshCollisionComponent.md#brenderinmainpass)
- [bReplicatePhysicsToAutonomousProxy](ue_ue.LandscapeMeshCollisionComponent.md#breplicatephysicstoautonomousproxy)
- [bReplicates](ue_ue.LandscapeMeshCollisionComponent.md#breplicates)
- [bReturnMaterialOnMove](ue_ue.LandscapeMeshCollisionComponent.md#breturnmaterialonmove)
- [bSelectable](ue_ue.LandscapeMeshCollisionComponent.md#bselectable)
- [bSelfShadowOnly](ue_ue.LandscapeMeshCollisionComponent.md#bselfshadowonly)
- [bShouldBeAttached](ue_ue.LandscapeMeshCollisionComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.LandscapeMeshCollisionComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.LandscapeMeshCollisionComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.LandscapeMeshCollisionComponent.md#bshouldupdatephysicsvolume)
- [bSingleSampleShadowFromStationaryLights](ue_ue.LandscapeMeshCollisionComponent.md#bsinglesampleshadowfromstationarylights)
- [bTraceComplexOnMove](ue_ue.LandscapeMeshCollisionComponent.md#btracecomplexonmove)
- [bTreatAsBackgroundForOcclusion](ue_ue.LandscapeMeshCollisionComponent.md#btreatasbackgroundforocclusion)
- [bUseAsOccluder](ue_ue.LandscapeMeshCollisionComponent.md#buseasoccluder)
- [bUseAttachParentBound](ue_ue.LandscapeMeshCollisionComponent.md#buseattachparentbound)
- [bUseEditorCompositing](ue_ue.LandscapeMeshCollisionComponent.md#buseeditorcompositing)
- [bUseMaxLODAsImposter](ue_ue.LandscapeMeshCollisionComponent.md#busemaxlodasimposter)
- [bUseViewOwnerDepthPriorityGroup](ue_ue.LandscapeMeshCollisionComponent.md#buseviewownerdepthprioritygroup)
- [bVisible](ue_ue.LandscapeMeshCollisionComponent.md#bvisible)
- [bVisibleInRayTracing](ue_ue.LandscapeMeshCollisionComponent.md#bvisibleinraytracing)
- [bVisibleInReflectionCaptures](ue_ue.LandscapeMeshCollisionComponent.md#bvisibleinreflectioncaptures)
- [bVisualizeComponent](ue_ue.LandscapeMeshCollisionComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.LandscapeMeshCollisionComponent.md#activate)
- [AddAngularImpulse](ue_ue.LandscapeMeshCollisionComponent.md#addangularimpulse)
- [AddAngularImpulseInDegrees](ue_ue.LandscapeMeshCollisionComponent.md#addangularimpulseindegrees)
- [AddAngularImpulseInRadians](ue_ue.LandscapeMeshCollisionComponent.md#addangularimpulseinradians)
- [AddForce](ue_ue.LandscapeMeshCollisionComponent.md#addforce)
- [AddForceAtLocation](ue_ue.LandscapeMeshCollisionComponent.md#addforceatlocation)
- [AddForceAtLocationLocal](ue_ue.LandscapeMeshCollisionComponent.md#addforceatlocationlocal)
- [AddImpulse](ue_ue.LandscapeMeshCollisionComponent.md#addimpulse)
- [AddImpulseAtLocation](ue_ue.LandscapeMeshCollisionComponent.md#addimpulseatlocation)
- [AddRadialForce](ue_ue.LandscapeMeshCollisionComponent.md#addradialforce)
- [AddRadialImpulse](ue_ue.LandscapeMeshCollisionComponent.md#addradialimpulse)
- [AddTickPrerequisiteActor](ue_ue.LandscapeMeshCollisionComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.LandscapeMeshCollisionComponent.md#addtickprerequisitecomponent)
- [AddTorque](ue_ue.LandscapeMeshCollisionComponent.md#addtorque)
- [AddTorqueInDegrees](ue_ue.LandscapeMeshCollisionComponent.md#addtorqueindegrees)
- [AddTorqueInRadians](ue_ue.LandscapeMeshCollisionComponent.md#addtorqueinradians)
- [CanCharacterStepUp](ue_ue.LandscapeMeshCollisionComponent.md#cancharacterstepup)
- [ClearMoveIgnoreActors](ue_ue.LandscapeMeshCollisionComponent.md#clearmoveignoreactors)
- [ClearMoveIgnoreComponents](ue_ue.LandscapeMeshCollisionComponent.md#clearmoveignorecomponents)
- [ComponentHasTag](ue_ue.LandscapeMeshCollisionComponent.md#componenthastag)
- [CopyArrayOfMoveIgnoreActors](ue_ue.LandscapeMeshCollisionComponent.md#copyarrayofmoveignoreactors)
- [CopyArrayOfMoveIgnoreComponents](ue_ue.LandscapeMeshCollisionComponent.md#copyarrayofmoveignorecomponents)
- [CreateAndSetMaterialInstanceDynamic](ue_ue.LandscapeMeshCollisionComponent.md#createandsetmaterialinstancedynamic)
- [CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.LandscapeMeshCollisionComponent.md#createandsetmaterialinstancedynamicfrommaterial)
- [CreateDefaultSubobject](ue_ue.LandscapeMeshCollisionComponent.md#createdefaultsubobject)
- [CreateDynamicMaterialInstance](ue_ue.LandscapeMeshCollisionComponent.md#createdynamicmaterialinstance)
- [Deactivate](ue_ue.LandscapeMeshCollisionComponent.md#deactivate)
- [DetachFromParent](ue_ue.LandscapeMeshCollisionComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.LandscapeMeshCollisionComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.LandscapeMeshCollisionComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.LandscapeMeshCollisionComponent.md#getallsocketnames)
- [GetAngularDamping](ue_ue.LandscapeMeshCollisionComponent.md#getangulardamping)
- [GetAttachParent](ue_ue.LandscapeMeshCollisionComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.LandscapeMeshCollisionComponent.md#getattachsocketname)
- [GetCenterOfMass](ue_ue.LandscapeMeshCollisionComponent.md#getcenterofmass)
- [GetChildComponent](ue_ue.LandscapeMeshCollisionComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.LandscapeMeshCollisionComponent.md#getchildrencomponents)
- [GetClass](ue_ue.LandscapeMeshCollisionComponent.md#getclass)
- [GetClosestPointOnCollision](ue_ue.LandscapeMeshCollisionComponent.md#getclosestpointoncollision)
- [GetCollisionEnabled](ue_ue.LandscapeMeshCollisionComponent.md#getcollisionenabled)
- [GetCollisionObjectType](ue_ue.LandscapeMeshCollisionComponent.md#getcollisionobjecttype)
- [GetCollisionProfileName](ue_ue.LandscapeMeshCollisionComponent.md#getcollisionprofilename)
- [GetCollisionResponseToChannel](ue_ue.LandscapeMeshCollisionComponent.md#getcollisionresponsetochannel)
- [GetComponentTickInterval](ue_ue.LandscapeMeshCollisionComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.LandscapeMeshCollisionComponent.md#getcomponentvelocity)
- [GetForwardVector](ue_ue.LandscapeMeshCollisionComponent.md#getforwardvector)
- [GetGenerateOverlapEvents](ue_ue.LandscapeMeshCollisionComponent.md#getgenerateoverlapevents)
- [GetInertiaTensor](ue_ue.LandscapeMeshCollisionComponent.md#getinertiatensor)
- [GetLinearDamping](ue_ue.LandscapeMeshCollisionComponent.md#getlineardamping)
- [GetMass](ue_ue.LandscapeMeshCollisionComponent.md#getmass)
- [GetMassScale](ue_ue.LandscapeMeshCollisionComponent.md#getmassscale)
- [GetMaterial](ue_ue.LandscapeMeshCollisionComponent.md#getmaterial)
- [GetMaterialFromCollisionFaceIndex](ue_ue.LandscapeMeshCollisionComponent.md#getmaterialfromcollisionfaceindex)
- [GetName](ue_ue.LandscapeMeshCollisionComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.LandscapeMeshCollisionComponent.md#getnumchildrencomponents)
- [GetNumMaterials](ue_ue.LandscapeMeshCollisionComponent.md#getnummaterials)
- [GetOuter](ue_ue.LandscapeMeshCollisionComponent.md#getouter)
- [GetOverlappingActors](ue_ue.LandscapeMeshCollisionComponent.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.LandscapeMeshCollisionComponent.md#getoverlappingcomponents)
- [GetOwner](ue_ue.LandscapeMeshCollisionComponent.md#getowner)
- [GetParentComponents](ue_ue.LandscapeMeshCollisionComponent.md#getparentcomponents)
- [GetPhysicsAngularVelocity](ue_ue.LandscapeMeshCollisionComponent.md#getphysicsangularvelocity)
- [GetPhysicsAngularVelocityInDegrees](ue_ue.LandscapeMeshCollisionComponent.md#getphysicsangularvelocityindegrees)
- [GetPhysicsAngularVelocityInRadians](ue_ue.LandscapeMeshCollisionComponent.md#getphysicsangularvelocityinradians)
- [GetPhysicsLinearVelocity](ue_ue.LandscapeMeshCollisionComponent.md#getphysicslinearvelocity)
- [GetPhysicsLinearVelocityAtPoint](ue_ue.LandscapeMeshCollisionComponent.md#getphysicslinearvelocityatpoint)
- [GetPhysicsVolume](ue_ue.LandscapeMeshCollisionComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.LandscapeMeshCollisionComponent.md#getrelativetransform)
- [GetRenderComponent](ue_ue.LandscapeMeshCollisionComponent.md#getrendercomponent)
- [GetRightVector](ue_ue.LandscapeMeshCollisionComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.LandscapeMeshCollisionComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.LandscapeMeshCollisionComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.LandscapeMeshCollisionComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.LandscapeMeshCollisionComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.LandscapeMeshCollisionComponent.md#getsockettransform)
- [GetUpVector](ue_ue.LandscapeMeshCollisionComponent.md#getupvector)
- [GetWalkableSlopeOverride](ue_ue.LandscapeMeshCollisionComponent.md#getwalkableslopeoverride)
- [GetWorld](ue_ue.LandscapeMeshCollisionComponent.md#getworld)
- [IgnoreActorWhenMoving](ue_ue.LandscapeMeshCollisionComponent.md#ignoreactorwhenmoving)
- [IgnoreComponentWhenMoving](ue_ue.LandscapeMeshCollisionComponent.md#ignorecomponentwhenmoving)
- [IsActive](ue_ue.LandscapeMeshCollisionComponent.md#isactive)
- [IsAnyRigidBodyAwake](ue_ue.LandscapeMeshCollisionComponent.md#isanyrigidbodyawake)
- [IsAnySimulatingPhysics](ue_ue.LandscapeMeshCollisionComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.LandscapeMeshCollisionComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.LandscapeMeshCollisionComponent.md#iscomponenttickenabled)
- [IsGravityEnabled](ue_ue.LandscapeMeshCollisionComponent.md#isgravityenabled)
- [IsOverlappingActor](ue_ue.LandscapeMeshCollisionComponent.md#isoverlappingactor)
- [IsOverlappingComponent](ue_ue.LandscapeMeshCollisionComponent.md#isoverlappingcomponent)
- [IsSimulatingPhysics](ue_ue.LandscapeMeshCollisionComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.LandscapeMeshCollisionComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.LandscapeMeshCollisionComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.LandscapeMeshCollisionComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.LandscapeMeshCollisionComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.LandscapeMeshCollisionComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.LandscapeMeshCollisionComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.LandscapeMeshCollisionComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.LandscapeMeshCollisionComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.LandscapeMeshCollisionComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.LandscapeMeshCollisionComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.LandscapeMeshCollisionComponent.md#k2_attachtocomponent)
- [K2\_BoxOverlapComponent](ue_ue.LandscapeMeshCollisionComponent.md#k2_boxoverlapcomponent)
- [K2\_DestroyComponent](ue_ue.LandscapeMeshCollisionComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.LandscapeMeshCollisionComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.LandscapeMeshCollisionComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.LandscapeMeshCollisionComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.LandscapeMeshCollisionComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.LandscapeMeshCollisionComponent.md#k2_getcomponenttoworld)
- [K2\_IsCollisionEnabled](ue_ue.LandscapeMeshCollisionComponent.md#k2_iscollisionenabled)
- [K2\_IsPhysicsCollisionEnabled](ue_ue.LandscapeMeshCollisionComponent.md#k2_isphysicscollisionenabled)
- [K2\_IsQueryCollisionEnabled](ue_ue.LandscapeMeshCollisionComponent.md#k2_isquerycollisionenabled)
- [K2\_LineTraceComponent](ue_ue.LandscapeMeshCollisionComponent.md#k2_linetracecomponent)
- [K2\_SetRelativeLocation](ue_ue.LandscapeMeshCollisionComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.LandscapeMeshCollisionComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.LandscapeMeshCollisionComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.LandscapeMeshCollisionComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.LandscapeMeshCollisionComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.LandscapeMeshCollisionComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.LandscapeMeshCollisionComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.LandscapeMeshCollisionComponent.md#k2_setworldtransform)
- [K2\_SphereOverlapComponent](ue_ue.LandscapeMeshCollisionComponent.md#k2_sphereoverlapcomponent)
- [K2\_SphereTraceComponent](ue_ue.LandscapeMeshCollisionComponent.md#k2_spheretracecomponent)
- [OnRep\_AttachChildren](ue_ue.LandscapeMeshCollisionComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.LandscapeMeshCollisionComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.LandscapeMeshCollisionComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.LandscapeMeshCollisionComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.LandscapeMeshCollisionComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.LandscapeMeshCollisionComponent.md#onrep_visibility)
- [PutRigidBodyToSleep](ue_ue.LandscapeMeshCollisionComponent.md#putrigidbodytosleep)
- [ReceiveBeginPlay](ue_ue.LandscapeMeshCollisionComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.LandscapeMeshCollisionComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.LandscapeMeshCollisionComponent.md#receivetick)
- [RegisterComponent](ue_ue.LandscapeMeshCollisionComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.LandscapeMeshCollisionComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.LandscapeMeshCollisionComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.LandscapeMeshCollisionComponent.md#resetrelativetransform)
- [ScaleByMomentOfInertia](ue_ue.LandscapeMeshCollisionComponent.md#scalebymomentofinertia)
- [SetAbsolute](ue_ue.LandscapeMeshCollisionComponent.md#setabsolute)
- [SetActive](ue_ue.LandscapeMeshCollisionComponent.md#setactive)
- [SetAllMassScale](ue_ue.LandscapeMeshCollisionComponent.md#setallmassscale)
- [SetAllPhysicsAngularVelocityInDegrees](ue_ue.LandscapeMeshCollisionComponent.md#setallphysicsangularvelocityindegrees)
- [SetAllPhysicsAngularVelocityInRadians](ue_ue.LandscapeMeshCollisionComponent.md#setallphysicsangularvelocityinradians)
- [SetAllPhysicsLinearVelocity](ue_ue.LandscapeMeshCollisionComponent.md#setallphysicslinearvelocity)
- [SetAllUseCCD](ue_ue.LandscapeMeshCollisionComponent.md#setalluseccd)
- [SetAngularDamping](ue_ue.LandscapeMeshCollisionComponent.md#setangulardamping)
- [SetAutoActivate](ue_ue.LandscapeMeshCollisionComponent.md#setautoactivate)
- [SetBoundsScale](ue_ue.LandscapeMeshCollisionComponent.md#setboundsscale)
- [SetCastInsetShadow](ue_ue.LandscapeMeshCollisionComponent.md#setcastinsetshadow)
- [SetCastShadow](ue_ue.LandscapeMeshCollisionComponent.md#setcastshadow)
- [SetCenterOfMass](ue_ue.LandscapeMeshCollisionComponent.md#setcenterofmass)
- [SetCollisionEnabled](ue_ue.LandscapeMeshCollisionComponent.md#setcollisionenabled)
- [SetCollisionObjectType](ue_ue.LandscapeMeshCollisionComponent.md#setcollisionobjecttype)
- [SetCollisionProfileName](ue_ue.LandscapeMeshCollisionComponent.md#setcollisionprofilename)
- [SetCollisionResponseToAllChannels](ue_ue.LandscapeMeshCollisionComponent.md#setcollisionresponsetoallchannels)
- [SetCollisionResponseToChannel](ue_ue.LandscapeMeshCollisionComponent.md#setcollisionresponsetochannel)
- [SetComponentTickEnabled](ue_ue.LandscapeMeshCollisionComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.LandscapeMeshCollisionComponent.md#setcomponenttickinterval)
- [SetConstraintMode](ue_ue.LandscapeMeshCollisionComponent.md#setconstraintmode)
- [SetCullDistance](ue_ue.LandscapeMeshCollisionComponent.md#setculldistance)
- [SetCustomDepthStencilValue](ue_ue.LandscapeMeshCollisionComponent.md#setcustomdepthstencilvalue)
- [SetCustomDepthStencilWriteMask](ue_ue.LandscapeMeshCollisionComponent.md#setcustomdepthstencilwritemask)
- [SetCustomPrimitiveDataFloat](ue_ue.LandscapeMeshCollisionComponent.md#setcustomprimitivedatafloat)
- [SetCustomPrimitiveDataVector2](ue_ue.LandscapeMeshCollisionComponent.md#setcustomprimitivedatavector2)
- [SetCustomPrimitiveDataVector3](ue_ue.LandscapeMeshCollisionComponent.md#setcustomprimitivedatavector3)
- [SetCustomPrimitiveDataVector4](ue_ue.LandscapeMeshCollisionComponent.md#setcustomprimitivedatavector4)
- [SetEnableGravity](ue_ue.LandscapeMeshCollisionComponent.md#setenablegravity)
- [SetExcludeFromLightAttachmentGroup](ue_ue.LandscapeMeshCollisionComponent.md#setexcludefromlightattachmentgroup)
- [SetGenerateOverlapEvents](ue_ue.LandscapeMeshCollisionComponent.md#setgenerateoverlapevents)
- [SetHiddenInGame](ue_ue.LandscapeMeshCollisionComponent.md#sethiddeningame)
- [SetIsReplicated](ue_ue.LandscapeMeshCollisionComponent.md#setisreplicated)
- [SetLightAttachmentsAsGroup](ue_ue.LandscapeMeshCollisionComponent.md#setlightattachmentsasgroup)
- [SetLinearDamping](ue_ue.LandscapeMeshCollisionComponent.md#setlineardamping)
- [SetMassOverrideInKg](ue_ue.LandscapeMeshCollisionComponent.md#setmassoverrideinkg)
- [SetMassScale](ue_ue.LandscapeMeshCollisionComponent.md#setmassscale)
- [SetMaterial](ue_ue.LandscapeMeshCollisionComponent.md#setmaterial)
- [SetMaterialByName](ue_ue.LandscapeMeshCollisionComponent.md#setmaterialbyname)
- [SetMobility](ue_ue.LandscapeMeshCollisionComponent.md#setmobility)
- [SetNotifyRigidBodyCollision](ue_ue.LandscapeMeshCollisionComponent.md#setnotifyrigidbodycollision)
- [SetOnlyOwnerSee](ue_ue.LandscapeMeshCollisionComponent.md#setonlyownersee)
- [SetOwnerNoSee](ue_ue.LandscapeMeshCollisionComponent.md#setownernosee)
- [SetPhysMaterialOverride](ue_ue.LandscapeMeshCollisionComponent.md#setphysmaterialoverride)
- [SetPhysicsAngularVelocity](ue_ue.LandscapeMeshCollisionComponent.md#setphysicsangularvelocity)
- [SetPhysicsAngularVelocityInDegrees](ue_ue.LandscapeMeshCollisionComponent.md#setphysicsangularvelocityindegrees)
- [SetPhysicsAngularVelocityInRadians](ue_ue.LandscapeMeshCollisionComponent.md#setphysicsangularvelocityinradians)
- [SetPhysicsLinearVelocity](ue_ue.LandscapeMeshCollisionComponent.md#setphysicslinearvelocity)
- [SetPhysicsMaxAngularVelocity](ue_ue.LandscapeMeshCollisionComponent.md#setphysicsmaxangularvelocity)
- [SetPhysicsMaxAngularVelocityInDegrees](ue_ue.LandscapeMeshCollisionComponent.md#setphysicsmaxangularvelocityindegrees)
- [SetPhysicsMaxAngularVelocityInRadians](ue_ue.LandscapeMeshCollisionComponent.md#setphysicsmaxangularvelocityinradians)
- [SetReceivesDecals](ue_ue.LandscapeMeshCollisionComponent.md#setreceivesdecals)
- [SetRelativeScale3D](ue_ue.LandscapeMeshCollisionComponent.md#setrelativescale3d)
- [SetRenderCustomDepth](ue_ue.LandscapeMeshCollisionComponent.md#setrendercustomdepth)
- [SetRenderInMainPass](ue_ue.LandscapeMeshCollisionComponent.md#setrenderinmainpass)
- [SetShouldUpdatePhysicsVolume](ue_ue.LandscapeMeshCollisionComponent.md#setshouldupdatephysicsvolume)
- [SetSimulatePhysics](ue_ue.LandscapeMeshCollisionComponent.md#setsimulatephysics)
- [SetSingleSampleShadowFromStationaryLights](ue_ue.LandscapeMeshCollisionComponent.md#setsinglesampleshadowfromstationarylights)
- [SetTickGroup](ue_ue.LandscapeMeshCollisionComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.LandscapeMeshCollisionComponent.md#settickablewhenpaused)
- [SetTranslucentSortPriority](ue_ue.LandscapeMeshCollisionComponent.md#settranslucentsortpriority)
- [SetUseCCD](ue_ue.LandscapeMeshCollisionComponent.md#setuseccd)
- [SetVisibility](ue_ue.LandscapeMeshCollisionComponent.md#setvisibility)
- [SetWalkableSlopeOverride](ue_ue.LandscapeMeshCollisionComponent.md#setwalkableslopeoverride)
- [SetWorldScale3D](ue_ue.LandscapeMeshCollisionComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.LandscapeMeshCollisionComponent.md#setupattachment)
- [SnapTo](ue_ue.LandscapeMeshCollisionComponent.md#snapto)
- [ToggleActive](ue_ue.LandscapeMeshCollisionComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.LandscapeMeshCollisionComponent.md#togglevisibility)
- [WakeAllRigidBodies](ue_ue.LandscapeMeshCollisionComponent.md#wakeallrigidbodies)
- [WakeRigidBody](ue_ue.LandscapeMeshCollisionComponent.md#wakerigidbody)
- [Find](ue_ue.LandscapeMeshCollisionComponent.md#find)
- [Load](ue_ue.LandscapeMeshCollisionComponent.md#load)
- [StaticClass](ue_ue.LandscapeMeshCollisionComponent.md#staticclass)

## Constructors

### constructor

• **new LandscapeMeshCollisionComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[constructor](ue_ue.LandscapeHeightfieldCollisionComponent.md#constructor)

## Properties

### AlwaysLoadOnClient

• **AlwaysLoadOnClient**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AlwaysLoadOnClient](ue_ue.LandscapeHeightfieldCollisionComponent.md#alwaysloadonclient)

___

### AlwaysLoadOnServer

• **AlwaysLoadOnServer**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AlwaysLoadOnServer](ue_ue.LandscapeHeightfieldCollisionComponent.md#alwaysloadonserver)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AssetUserData](ue_ue.LandscapeHeightfieldCollisionComponent.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AttachChildren](ue_ue.LandscapeHeightfieldCollisionComponent.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AttachParent](ue_ue.LandscapeHeightfieldCollisionComponent.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AttachSocketName](ue_ue.LandscapeHeightfieldCollisionComponent.md#attachsocketname)

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[BodyInstance](ue_ue.LandscapeHeightfieldCollisionComponent.md#bodyinstance)

___

### BoundsScale

• **BoundsScale**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[BoundsScale](ue_ue.LandscapeHeightfieldCollisionComponent.md#boundsscale)

___

### CachedLocalBox

• **CachedLocalBox**: [`Box`](ue_ue.Box.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CachedLocalBox](ue_ue.LandscapeHeightfieldCollisionComponent.md#cachedlocalbox)

___

### CachedMaxDrawDistance

• **CachedMaxDrawDistance**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CachedMaxDrawDistance](ue_ue.LandscapeHeightfieldCollisionComponent.md#cachedmaxdrawdistance)

___

### CanBeCharacterBase

• **CanBeCharacterBase**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CanBeCharacterBase](ue_ue.LandscapeHeightfieldCollisionComponent.md#canbecharacterbase)

___

### CanCharacterStepUpOn

• **CanCharacterStepUpOn**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CanCharacterStepUpOn](ue_ue.LandscapeHeightfieldCollisionComponent.md#cancharacterstepupon)

___

### CastShadow

• **CastShadow**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CastShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#castshadow)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ClientAttachedChildren](ue_ue.LandscapeHeightfieldCollisionComponent.md#clientattachedchildren)

___

### CollisionQuadFlags

• **CollisionQuadFlags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CollisionQuadFlags](ue_ue.LandscapeHeightfieldCollisionComponent.md#collisionquadflags)

___

### CollisionScale

• **CollisionScale**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CollisionScale](ue_ue.LandscapeHeightfieldCollisionComponent.md#collisionscale)

___

### CollisionSizeQuads

• **CollisionSizeQuads**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CollisionSizeQuads](ue_ue.LandscapeHeightfieldCollisionComponent.md#collisionsizequads)

___

### ComponentLayerInfos

• **ComponentLayerInfos**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeLayerInfoObject`](ue_ue.LandscapeLayerInfoObject.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ComponentLayerInfos](ue_ue.LandscapeHeightfieldCollisionComponent.md#componentlayerinfos)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ComponentTags](ue_ue.LandscapeHeightfieldCollisionComponent.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ComponentVelocity](ue_ue.LandscapeHeightfieldCollisionComponent.md#componentvelocity)

___

### CookedPhysicalMaterials

• **CookedPhysicalMaterials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CookedPhysicalMaterials](ue_ue.LandscapeHeightfieldCollisionComponent.md#cookedphysicalmaterials)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CreationMethod](ue_ue.LandscapeHeightfieldCollisionComponent.md#creationmethod)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CustomDepthStencilValue](ue_ue.LandscapeHeightfieldCollisionComponent.md#customdepthstencilvalue)

___

### CustomDepthStencilWriteMask

• **CustomDepthStencilWriteMask**: [`ERendererStencilMask`](../enums/ue_ue.ERendererStencilMask.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CustomDepthStencilWriteMask](ue_ue.LandscapeHeightfieldCollisionComponent.md#customdepthstencilwritemask)

___

### CustomPrimitiveData

• **CustomPrimitiveData**: [`CustomPrimitiveData`](ue_ue.CustomPrimitiveData.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CustomPrimitiveData](ue_ue.LandscapeHeightfieldCollisionComponent.md#customprimitivedata)

___

### DepthPriorityGroup

• **DepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[DepthPriorityGroup](ue_ue.LandscapeHeightfieldCollisionComponent.md#depthprioritygroup)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[DetailMode](ue_ue.LandscapeHeightfieldCollisionComponent.md#detailmode)

___

### ExcludeForSpecificHLODLevels

• **ExcludeForSpecificHLODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ExcludeForSpecificHLODLevels](ue_ue.LandscapeHeightfieldCollisionComponent.md#excludeforspecifichlodlevels)

___

### HeightfieldGuid

• **HeightfieldGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[HeightfieldGuid](ue_ue.LandscapeHeightfieldCollisionComponent.md#heightfieldguid)

___

### IndirectLightingCacheQuality

• **IndirectLightingCacheQuality**: [`EIndirectLightingCacheQuality`](../enums/ue_ue.EIndirectLightingCacheQuality.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IndirectLightingCacheQuality](ue_ue.LandscapeHeightfieldCollisionComponent.md#indirectlightingcachequality)

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[LDMaxDrawDistance](ue_ue.LandscapeHeightfieldCollisionComponent.md#ldmaxdrawdistance)

___

### LODParentPrimitive

• **LODParentPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[LODParentPrimitive](ue_ue.LandscapeHeightfieldCollisionComponent.md#lodparentprimitive)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[LightingChannels](ue_ue.LandscapeHeightfieldCollisionComponent.md#lightingchannels)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[LightmapType](ue_ue.LandscapeHeightfieldCollisionComponent.md#lightmaptype)

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[LpvBiasMultiplier](ue_ue.LandscapeHeightfieldCollisionComponent.md#lpvbiasmultiplier)

___

### MeshGuid

• **MeshGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### MinDrawDistance

• **MinDrawDistance**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[MinDrawDistance](ue_ue.LandscapeHeightfieldCollisionComponent.md#mindrawdistance)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[Mobility](ue_ue.LandscapeHeightfieldCollisionComponent.md#mobility)

___

### MoveIgnoreActors

• **MoveIgnoreActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[MoveIgnoreActors](ue_ue.LandscapeHeightfieldCollisionComponent.md#moveignoreactors)

___

### MoveIgnoreComponents

• **MoveIgnoreComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[MoveIgnoreComponents](ue_ue.LandscapeHeightfieldCollisionComponent.md#moveignorecomponents)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnBeginCursorOver](ue_ue.LandscapeHeightfieldCollisionComponent.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnClicked](ue_ue.LandscapeHeightfieldCollisionComponent.md#onclicked)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnComponentActivated](ue_ue.LandscapeHeightfieldCollisionComponent.md#oncomponentactivated)

___

### OnComponentBeginOverlap

• **OnComponentBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`, `bFromSweep`: `boolean`, `SweepResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnComponentBeginOverlap](ue_ue.LandscapeHeightfieldCollisionComponent.md#oncomponentbeginoverlap)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnComponentDeactivated](ue_ue.LandscapeHeightfieldCollisionComponent.md#oncomponentdeactivated)

___

### OnComponentEndOverlap

• **OnComponentEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnComponentEndOverlap](ue_ue.LandscapeHeightfieldCollisionComponent.md#oncomponentendoverlap)

___

### OnComponentHit

• **OnComponentHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`HitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnComponentHit](ue_ue.LandscapeHeightfieldCollisionComponent.md#oncomponenthit)

___

### OnComponentSleep

• **OnComponentSleep**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SleepingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnComponentSleep](ue_ue.LandscapeHeightfieldCollisionComponent.md#oncomponentsleep)

___

### OnComponentWake

• **OnComponentWake**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`WakingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnComponentWake](ue_ue.LandscapeHeightfieldCollisionComponent.md#oncomponentwake)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnEndCursorOver](ue_ue.LandscapeHeightfieldCollisionComponent.md#onendcursorover)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnInputTouchBegin](ue_ue.LandscapeHeightfieldCollisionComponent.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnInputTouchEnd](ue_ue.LandscapeHeightfieldCollisionComponent.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnInputTouchEnter](ue_ue.LandscapeHeightfieldCollisionComponent.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnInputTouchLeave](ue_ue.LandscapeHeightfieldCollisionComponent.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnReleased](ue_ue.LandscapeHeightfieldCollisionComponent.md#onreleased)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[PhysicsVolume](ue_ue.LandscapeHeightfieldCollisionComponent.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.LandscapeHeightfieldCollisionComponent.md#physicsvolumechangeddelegate)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[PrimaryComponentTick](ue_ue.LandscapeHeightfieldCollisionComponent.md#primarycomponenttick)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[RelativeLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[RelativeRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[RelativeScale3D](ue_ue.LandscapeHeightfieldCollisionComponent.md#relativescale3d)

___

### RenderComponent

• **RenderComponent**: [`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`LandscapeComponent`](ue_ue.LandscapeComponent.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[RenderComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#rendercomponent)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[RuntimeVirtualTextures](ue_ue.LandscapeHeightfieldCollisionComponent.md#runtimevirtualtextures)

___

### SectionBaseX

• **SectionBaseX**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SectionBaseX](ue_ue.LandscapeHeightfieldCollisionComponent.md#sectionbasex)

___

### SectionBaseY

• **SectionBaseY**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SectionBaseY](ue_ue.LandscapeHeightfieldCollisionComponent.md#sectionbasey)

___

### SimpleCollisionSizeQuads

• **SimpleCollisionSizeQuads**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SimpleCollisionSizeQuads](ue_ue.LandscapeHeightfieldCollisionComponent.md#simplecollisionsizequads)

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[TranslucencySortPriority](ue_ue.LandscapeHeightfieldCollisionComponent.md#translucencysortpriority)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[UCSModifiedProperties](ue_ue.LandscapeHeightfieldCollisionComponent.md#ucsmodifiedproperties)

___

### ViewOwnerDepthPriorityGroup

• **ViewOwnerDepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ViewOwnerDepthPriorityGroup](ue_ue.LandscapeHeightfieldCollisionComponent.md#viewownerdepthprioritygroup)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[VirtualTextureCullMips](ue_ue.LandscapeHeightfieldCollisionComponent.md#virtualtexturecullmips)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[VirtualTextureLodBias](ue_ue.LandscapeHeightfieldCollisionComponent.md#virtualtexturelodbias)

___

### VirtualTextureMinCoverage

• **VirtualTextureMinCoverage**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[VirtualTextureMinCoverage](ue_ue.LandscapeHeightfieldCollisionComponent.md#virtualtexturemincoverage)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[VirtualTextureRenderPassType](ue_ue.LandscapeHeightfieldCollisionComponent.md#virtualtexturerenderpasstype)

___

### VisibilityId

• **VisibilityId**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[VisibilityId](ue_ue.LandscapeHeightfieldCollisionComponent.md#visibilityid)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[__tid_ActorComponent__](ue_ue.LandscapeHeightfieldCollisionComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_LandscapeHeightfieldCollisionComponent\_\_

• **\_\_tid\_LandscapeHeightfieldCollisionComponent\_\_**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[__tid_LandscapeHeightfieldCollisionComponent__](ue_ue.LandscapeHeightfieldCollisionComponent.md#__tid_landscapeheightfieldcollisioncomponent__)

___

### \_\_tid\_LandscapeMeshCollisionComponent\_\_

• **\_\_tid\_LandscapeMeshCollisionComponent\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[__tid_Object__](ue_ue.LandscapeHeightfieldCollisionComponent.md#__tid_object__)

___

### \_\_tid\_PrimitiveComponent\_\_

• **\_\_tid\_PrimitiveComponent\_\_**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[__tid_PrimitiveComponent__](ue_ue.LandscapeHeightfieldCollisionComponent.md#__tid_primitivecomponent__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[__tid_SceneComponent__](ue_ue.LandscapeHeightfieldCollisionComponent.md#__tid_scenecomponent__)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bAbsoluteLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bAbsoluteRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bAbsoluteScale](ue_ue.LandscapeHeightfieldCollisionComponent.md#babsolutescale)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bAffectDistanceFieldLighting](ue_ue.LandscapeHeightfieldCollisionComponent.md#baffectdistancefieldlighting)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bAffectDynamicIndirectLighting](ue_ue.LandscapeHeightfieldCollisionComponent.md#baffectdynamicindirectlighting)

___

### bAllowCullDistanceVolume

• **bAllowCullDistanceVolume**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bAllowCullDistanceVolume](ue_ue.LandscapeHeightfieldCollisionComponent.md#ballowculldistancevolume)

___

### bAlwaysCreatePhysicsState

• **bAlwaysCreatePhysicsState**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bAlwaysCreatePhysicsState](ue_ue.LandscapeHeightfieldCollisionComponent.md#balwayscreatephysicsstate)

___

### bApplyImpulseOnDamage

• **bApplyImpulseOnDamage**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bApplyImpulseOnDamage](ue_ue.LandscapeHeightfieldCollisionComponent.md#bapplyimpulseondamage)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bAutoActivate](ue_ue.LandscapeHeightfieldCollisionComponent.md#bautoactivate)

___

### bBatchImpostersAsInstances

• **bBatchImpostersAsInstances**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bBatchImpostersAsInstances](ue_ue.LandscapeHeightfieldCollisionComponent.md#bbatchimpostersasinstances)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.LandscapeHeightfieldCollisionComponent.md#bboundschangetriggersstreamingdatarebuild)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCanEverAffectNavigation](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcaneveraffectnavigation)

___

### bCastCinematicShadow

• **bCastCinematicShadow**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCastCinematicShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcastcinematicshadow)

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCastDynamicShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcastdynamicshadow)

___

### bCastFarShadow

• **bCastFarShadow**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCastFarShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcastfarshadow)

___

### bCastHiddenShadow

• **bCastHiddenShadow**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCastHiddenShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcasthiddenshadow)

___

### bCastInsetShadow

• **bCastInsetShadow**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCastInsetShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcastinsetshadow)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCastShadowAsTwoSided](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcastshadowastwosided)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCastStaticShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcaststaticshadow)

___

### bCastVolumetricTranslucentShadow

• **bCastVolumetricTranslucentShadow**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCastVolumetricTranslucentShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcastvolumetrictranslucentshadow)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bComponentToWorldUpdated](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcomponenttoworldupdated)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCreatedByConstructionScript](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bEditableWhenInherited](ue_ue.LandscapeHeightfieldCollisionComponent.md#beditablewheninherited)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bEnableAutoLODGeneration](ue_ue.LandscapeHeightfieldCollisionComponent.md#benableautolodgeneration)

___

### bExcludeFromLightAttachmentGroup

• **bExcludeFromLightAttachmentGroup**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bExcludeFromLightAttachmentGroup](ue_ue.LandscapeHeightfieldCollisionComponent.md#bexcludefromlightattachmentgroup)

___

### bForceMipStreaming

• **bForceMipStreaming**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bForceMipStreaming](ue_ue.LandscapeHeightfieldCollisionComponent.md#bforcemipstreaming)

___

### bGenerateOverlapEvents

• **bGenerateOverlapEvents**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bGenerateOverlapEvents](ue_ue.LandscapeHeightfieldCollisionComponent.md#bgenerateoverlapevents)

___

### bHasCustomNavigableGeometry

• **bHasCustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bHasCustomNavigableGeometry](ue_ue.LandscapeHeightfieldCollisionComponent.md#bhascustomnavigablegeometry)

___

### bHasMotionBlurVelocityMeshes

• **bHasMotionBlurVelocityMeshes**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bHasMotionBlurVelocityMeshes](ue_ue.LandscapeHeightfieldCollisionComponent.md#bhasmotionblurvelocitymeshes)

___

### bHasPerInstanceHitProxies

• **bHasPerInstanceHitProxies**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bHasPerInstanceHitProxies](ue_ue.LandscapeHeightfieldCollisionComponent.md#bhasperinstancehitproxies)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bHiddenInGame](ue_ue.LandscapeHeightfieldCollisionComponent.md#bhiddeningame)

___

### bIgnoreRadialForce

• **bIgnoreRadialForce**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bIgnoreRadialForce](ue_ue.LandscapeHeightfieldCollisionComponent.md#bignoreradialforce)

___

### bIgnoreRadialImpulse

• **bIgnoreRadialImpulse**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bIgnoreRadialImpulse](ue_ue.LandscapeHeightfieldCollisionComponent.md#bignoreradialimpulse)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bInstanceComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bIsActive](ue_ue.LandscapeHeightfieldCollisionComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bIsEditorOnly](ue_ue.LandscapeHeightfieldCollisionComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bIsVisualizationComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#bisvisualizationcomponent)

___

### bLightAsIfStatic

• **bLightAsIfStatic**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bLightAsIfStatic](ue_ue.LandscapeHeightfieldCollisionComponent.md#blightasifstatic)

___

### bLightAttachmentsAsGroup

• **bLightAttachmentsAsGroup**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bLightAttachmentsAsGroup](ue_ue.LandscapeHeightfieldCollisionComponent.md#blightattachmentsasgroup)

___

### bMultiBodyOverlap

• **bMultiBodyOverlap**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bMultiBodyOverlap](ue_ue.LandscapeHeightfieldCollisionComponent.md#bmultibodyoverlap)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bNetAddressable](ue_ue.LandscapeHeightfieldCollisionComponent.md#bnetaddressable)

___

### bNeverDistanceCull

• **bNeverDistanceCull**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bNeverDistanceCull](ue_ue.LandscapeHeightfieldCollisionComponent.md#bneverdistancecull)

___

### bOnlyOwnerSee

• **bOnlyOwnerSee**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bOnlyOwnerSee](ue_ue.LandscapeHeightfieldCollisionComponent.md#bonlyownersee)

___

### bOwnerNoSee

• **bOwnerNoSee**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bOwnerNoSee](ue_ue.LandscapeHeightfieldCollisionComponent.md#bownernosee)

___

### bReceiveMobileCSMShadows

• **bReceiveMobileCSMShadows**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bReceiveMobileCSMShadows](ue_ue.LandscapeHeightfieldCollisionComponent.md#breceivemobilecsmshadows)

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bReceivesDecals](ue_ue.LandscapeHeightfieldCollisionComponent.md#breceivesdecals)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bRenderCustomDepth](ue_ue.LandscapeHeightfieldCollisionComponent.md#brendercustomdepth)

___

### bRenderInDepthPass

• **bRenderInDepthPass**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bRenderInDepthPass](ue_ue.LandscapeHeightfieldCollisionComponent.md#brenderindepthpass)

___

### bRenderInMainPass

• **bRenderInMainPass**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bRenderInMainPass](ue_ue.LandscapeHeightfieldCollisionComponent.md#brenderinmainpass)

___

### bReplicatePhysicsToAutonomousProxy

• **bReplicatePhysicsToAutonomousProxy**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bReplicatePhysicsToAutonomousProxy](ue_ue.LandscapeHeightfieldCollisionComponent.md#breplicatephysicstoautonomousproxy)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bReplicates](ue_ue.LandscapeHeightfieldCollisionComponent.md#breplicates)

___

### bReturnMaterialOnMove

• **bReturnMaterialOnMove**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bReturnMaterialOnMove](ue_ue.LandscapeHeightfieldCollisionComponent.md#breturnmaterialonmove)

___

### bSelectable

• **bSelectable**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bSelectable](ue_ue.LandscapeHeightfieldCollisionComponent.md#bselectable)

___

### bSelfShadowOnly

• **bSelfShadowOnly**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bSelfShadowOnly](ue_ue.LandscapeHeightfieldCollisionComponent.md#bselfshadowonly)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bShouldBeAttached](ue_ue.LandscapeHeightfieldCollisionComponent.md#bshouldbeattached)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.LandscapeHeightfieldCollisionComponent.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.LandscapeHeightfieldCollisionComponent.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.LandscapeHeightfieldCollisionComponent.md#bshouldupdatephysicsvolume)

___

### bSingleSampleShadowFromStationaryLights

• **bSingleSampleShadowFromStationaryLights**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bSingleSampleShadowFromStationaryLights](ue_ue.LandscapeHeightfieldCollisionComponent.md#bsinglesampleshadowfromstationarylights)

___

### bTraceComplexOnMove

• **bTraceComplexOnMove**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bTraceComplexOnMove](ue_ue.LandscapeHeightfieldCollisionComponent.md#btracecomplexonmove)

___

### bTreatAsBackgroundForOcclusion

• **bTreatAsBackgroundForOcclusion**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bTreatAsBackgroundForOcclusion](ue_ue.LandscapeHeightfieldCollisionComponent.md#btreatasbackgroundforocclusion)

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bUseAsOccluder](ue_ue.LandscapeHeightfieldCollisionComponent.md#buseasoccluder)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bUseAttachParentBound](ue_ue.LandscapeHeightfieldCollisionComponent.md#buseattachparentbound)

___

### bUseEditorCompositing

• **bUseEditorCompositing**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bUseEditorCompositing](ue_ue.LandscapeHeightfieldCollisionComponent.md#buseeditorcompositing)

___

### bUseMaxLODAsImposter

• **bUseMaxLODAsImposter**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bUseMaxLODAsImposter](ue_ue.LandscapeHeightfieldCollisionComponent.md#busemaxlodasimposter)

___

### bUseViewOwnerDepthPriorityGroup

• **bUseViewOwnerDepthPriorityGroup**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bUseViewOwnerDepthPriorityGroup](ue_ue.LandscapeHeightfieldCollisionComponent.md#buseviewownerdepthprioritygroup)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bVisible](ue_ue.LandscapeHeightfieldCollisionComponent.md#bvisible)

___

### bVisibleInRayTracing

• **bVisibleInRayTracing**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bVisibleInRayTracing](ue_ue.LandscapeHeightfieldCollisionComponent.md#bvisibleinraytracing)

___

### bVisibleInReflectionCaptures

• **bVisibleInReflectionCaptures**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bVisibleInReflectionCaptures](ue_ue.LandscapeHeightfieldCollisionComponent.md#bvisibleinreflectioncaptures)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bVisualizeComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#bvisualizecomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[Activate](ue_ue.LandscapeHeightfieldCollisionComponent.md#activate)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddAngularImpulse](ue_ue.LandscapeHeightfieldCollisionComponent.md#addangularimpulse)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddAngularImpulseInDegrees](ue_ue.LandscapeHeightfieldCollisionComponent.md#addangularimpulseindegrees)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddAngularImpulseInRadians](ue_ue.LandscapeHeightfieldCollisionComponent.md#addangularimpulseinradians)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddForce](ue_ue.LandscapeHeightfieldCollisionComponent.md#addforce)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddForceAtLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#addforceatlocation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddForceAtLocationLocal](ue_ue.LandscapeHeightfieldCollisionComponent.md#addforceatlocationlocal)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddImpulse](ue_ue.LandscapeHeightfieldCollisionComponent.md#addimpulse)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddImpulseAtLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#addimpulseatlocation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddRadialForce](ue_ue.LandscapeHeightfieldCollisionComponent.md#addradialforce)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddRadialImpulse](ue_ue.LandscapeHeightfieldCollisionComponent.md#addradialimpulse)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddTickPrerequisiteActor](ue_ue.LandscapeHeightfieldCollisionComponent.md#addtickprerequisiteactor)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddTickPrerequisiteComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#addtickprerequisitecomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddTorque](ue_ue.LandscapeHeightfieldCollisionComponent.md#addtorque)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddTorqueInDegrees](ue_ue.LandscapeHeightfieldCollisionComponent.md#addtorqueindegrees)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddTorqueInRadians](ue_ue.LandscapeHeightfieldCollisionComponent.md#addtorqueinradians)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CanCharacterStepUp](ue_ue.LandscapeHeightfieldCollisionComponent.md#cancharacterstepup)

___

### ClearMoveIgnoreActors

▸ **ClearMoveIgnoreActors**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ClearMoveIgnoreActors](ue_ue.LandscapeHeightfieldCollisionComponent.md#clearmoveignoreactors)

___

### ClearMoveIgnoreComponents

▸ **ClearMoveIgnoreComponents**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ClearMoveIgnoreComponents](ue_ue.LandscapeHeightfieldCollisionComponent.md#clearmoveignorecomponents)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ComponentHasTag](ue_ue.LandscapeHeightfieldCollisionComponent.md#componenthastag)

___

### CopyArrayOfMoveIgnoreActors

▸ **CopyArrayOfMoveIgnoreActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CopyArrayOfMoveIgnoreActors](ue_ue.LandscapeHeightfieldCollisionComponent.md#copyarrayofmoveignoreactors)

___

### CopyArrayOfMoveIgnoreComponents

▸ **CopyArrayOfMoveIgnoreComponents**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CopyArrayOfMoveIgnoreComponents](ue_ue.LandscapeHeightfieldCollisionComponent.md#copyarrayofmoveignorecomponents)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CreateAndSetMaterialInstanceDynamic](ue_ue.LandscapeHeightfieldCollisionComponent.md#createandsetmaterialinstancedynamic)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.LandscapeHeightfieldCollisionComponent.md#createandsetmaterialinstancedynamicfrommaterial)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CreateDefaultSubobject](ue_ue.LandscapeHeightfieldCollisionComponent.md#createdefaultsubobject)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CreateDynamicMaterialInstance](ue_ue.LandscapeHeightfieldCollisionComponent.md#createdynamicmaterialinstance)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[Deactivate](ue_ue.LandscapeHeightfieldCollisionComponent.md#deactivate)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[DetachFromParent](ue_ue.LandscapeHeightfieldCollisionComponent.md#detachfromparent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[DoesSocketExist](ue_ue.LandscapeHeightfieldCollisionComponent.md#doessocketexist)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ExecuteUbergraph](ue_ue.LandscapeHeightfieldCollisionComponent.md#executeubergraph)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetAllSocketNames](ue_ue.LandscapeHeightfieldCollisionComponent.md#getallsocketnames)

___

### GetAngularDamping

▸ **GetAngularDamping**(): `number`

#### Returns

`number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetAngularDamping](ue_ue.LandscapeHeightfieldCollisionComponent.md#getangulardamping)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetAttachParent](ue_ue.LandscapeHeightfieldCollisionComponent.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetAttachSocketName](ue_ue.LandscapeHeightfieldCollisionComponent.md#getattachsocketname)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetCenterOfMass](ue_ue.LandscapeHeightfieldCollisionComponent.md#getcenterofmass)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetChildComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#getchildcomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetChildrenComponents](ue_ue.LandscapeHeightfieldCollisionComponent.md#getchildrencomponents)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetClass](ue_ue.LandscapeHeightfieldCollisionComponent.md#getclass)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetClosestPointOnCollision](ue_ue.LandscapeHeightfieldCollisionComponent.md#getclosestpointoncollision)

___

### GetCollisionEnabled

▸ **GetCollisionEnabled**(): [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Returns

[`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetCollisionEnabled](ue_ue.LandscapeHeightfieldCollisionComponent.md#getcollisionenabled)

___

### GetCollisionObjectType

▸ **GetCollisionObjectType**(): [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Returns

[`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetCollisionObjectType](ue_ue.LandscapeHeightfieldCollisionComponent.md#getcollisionobjecttype)

___

### GetCollisionProfileName

▸ **GetCollisionProfileName**(): `string`

#### Returns

`string`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetCollisionProfileName](ue_ue.LandscapeHeightfieldCollisionComponent.md#getcollisionprofilename)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetCollisionResponseToChannel](ue_ue.LandscapeHeightfieldCollisionComponent.md#getcollisionresponsetochannel)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetComponentTickInterval](ue_ue.LandscapeHeightfieldCollisionComponent.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetComponentVelocity](ue_ue.LandscapeHeightfieldCollisionComponent.md#getcomponentvelocity)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetForwardVector](ue_ue.LandscapeHeightfieldCollisionComponent.md#getforwardvector)

___

### GetGenerateOverlapEvents

▸ **GetGenerateOverlapEvents**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetGenerateOverlapEvents](ue_ue.LandscapeHeightfieldCollisionComponent.md#getgenerateoverlapevents)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetInertiaTensor](ue_ue.LandscapeHeightfieldCollisionComponent.md#getinertiatensor)

___

### GetLinearDamping

▸ **GetLinearDamping**(): `number`

#### Returns

`number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetLinearDamping](ue_ue.LandscapeHeightfieldCollisionComponent.md#getlineardamping)

___

### GetMass

▸ **GetMass**(): `number`

#### Returns

`number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetMass](ue_ue.LandscapeHeightfieldCollisionComponent.md#getmass)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetMassScale](ue_ue.LandscapeHeightfieldCollisionComponent.md#getmassscale)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetMaterial](ue_ue.LandscapeHeightfieldCollisionComponent.md#getmaterial)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetMaterialFromCollisionFaceIndex](ue_ue.LandscapeHeightfieldCollisionComponent.md#getmaterialfromcollisionfaceindex)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetName](ue_ue.LandscapeHeightfieldCollisionComponent.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetNumChildrenComponents](ue_ue.LandscapeHeightfieldCollisionComponent.md#getnumchildrencomponents)

___

### GetNumMaterials

▸ **GetNumMaterials**(): `number`

#### Returns

`number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetNumMaterials](ue_ue.LandscapeHeightfieldCollisionComponent.md#getnummaterials)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetOuter](ue_ue.LandscapeHeightfieldCollisionComponent.md#getouter)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetOverlappingActors](ue_ue.LandscapeHeightfieldCollisionComponent.md#getoverlappingactors)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetOverlappingComponents](ue_ue.LandscapeHeightfieldCollisionComponent.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetOwner](ue_ue.LandscapeHeightfieldCollisionComponent.md#getowner)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetParentComponents](ue_ue.LandscapeHeightfieldCollisionComponent.md#getparentcomponents)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetPhysicsAngularVelocity](ue_ue.LandscapeHeightfieldCollisionComponent.md#getphysicsangularvelocity)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetPhysicsAngularVelocityInDegrees](ue_ue.LandscapeHeightfieldCollisionComponent.md#getphysicsangularvelocityindegrees)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetPhysicsAngularVelocityInRadians](ue_ue.LandscapeHeightfieldCollisionComponent.md#getphysicsangularvelocityinradians)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetPhysicsLinearVelocity](ue_ue.LandscapeHeightfieldCollisionComponent.md#getphysicslinearvelocity)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetPhysicsLinearVelocityAtPoint](ue_ue.LandscapeHeightfieldCollisionComponent.md#getphysicslinearvelocityatpoint)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetPhysicsVolume](ue_ue.LandscapeHeightfieldCollisionComponent.md#getphysicsvolume)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetRelativeTransform](ue_ue.LandscapeHeightfieldCollisionComponent.md#getrelativetransform)

___

### GetRenderComponent

▸ **GetRenderComponent**(): [`LandscapeComponent`](ue_ue.LandscapeComponent.md)

#### Returns

[`LandscapeComponent`](ue_ue.LandscapeComponent.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetRenderComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#getrendercomponent)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetRightVector](ue_ue.LandscapeHeightfieldCollisionComponent.md#getrightvector)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.LandscapeHeightfieldCollisionComponent.md#getshouldupdatephysicsvolume)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetSocketLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#getsocketlocation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetSocketQuaternion](ue_ue.LandscapeHeightfieldCollisionComponent.md#getsocketquaternion)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetSocketRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#getsocketrotation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetSocketTransform](ue_ue.LandscapeHeightfieldCollisionComponent.md#getsockettransform)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetUpVector](ue_ue.LandscapeHeightfieldCollisionComponent.md#getupvector)

___

### GetWalkableSlopeOverride

▸ **GetWalkableSlopeOverride**(): [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Returns

[`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetWalkableSlopeOverride](ue_ue.LandscapeHeightfieldCollisionComponent.md#getwalkableslopeoverride)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetWorld](ue_ue.LandscapeHeightfieldCollisionComponent.md#getworld)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IgnoreActorWhenMoving](ue_ue.LandscapeHeightfieldCollisionComponent.md#ignoreactorwhenmoving)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IgnoreComponentWhenMoving](ue_ue.LandscapeHeightfieldCollisionComponent.md#ignorecomponentwhenmoving)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsActive](ue_ue.LandscapeHeightfieldCollisionComponent.md#isactive)

___

### IsAnyRigidBodyAwake

▸ **IsAnyRigidBodyAwake**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsAnyRigidBodyAwake](ue_ue.LandscapeHeightfieldCollisionComponent.md#isanyrigidbodyawake)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsAnySimulatingPhysics](ue_ue.LandscapeHeightfieldCollisionComponent.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsBeingDestroyed](ue_ue.LandscapeHeightfieldCollisionComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsComponentTickEnabled](ue_ue.LandscapeHeightfieldCollisionComponent.md#iscomponenttickenabled)

___

### IsGravityEnabled

▸ **IsGravityEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsGravityEnabled](ue_ue.LandscapeHeightfieldCollisionComponent.md#isgravityenabled)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsOverlappingActor](ue_ue.LandscapeHeightfieldCollisionComponent.md#isoverlappingactor)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsOverlappingComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#isoverlappingcomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsSimulatingPhysics](ue_ue.LandscapeHeightfieldCollisionComponent.md#issimulatingphysics)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsVisible](ue_ue.LandscapeHeightfieldCollisionComponent.md#isvisible)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AddLocalOffset](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_addlocaloffset)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AddLocalRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_addlocalrotation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AddLocalTransform](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_addlocaltransform)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AddRelativeLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_addrelativelocation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AddRelativeRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_addrelativerotation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AddWorldOffset](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_addworldoffset)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AddWorldRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_addworldrotation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AddWorldTransform](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_addworldtransform)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AttachTo](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_attachto)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AttachToComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_attachtocomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_BoxOverlapComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_boxoverlapcomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_DestroyComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_destroycomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_DetachFromComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_detachfromcomponent)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_GetComponentLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_GetComponentRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_GetComponentScale](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_GetComponentToWorld](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_getcomponenttoworld)

___

### K2\_IsCollisionEnabled

▸ **K2_IsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_IsCollisionEnabled](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_iscollisionenabled)

___

### K2\_IsPhysicsCollisionEnabled

▸ **K2_IsPhysicsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_IsPhysicsCollisionEnabled](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_isphysicscollisionenabled)

___

### K2\_IsQueryCollisionEnabled

▸ **K2_IsQueryCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_IsQueryCollisionEnabled](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_isquerycollisionenabled)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_LineTraceComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_linetracecomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SetRelativeLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_setrelativelocation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_setrelativelocationandrotation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SetRelativeRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_setrelativerotation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SetRelativeTransform](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_setrelativetransform)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SetWorldLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_setworldlocation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_setworldlocationandrotation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SetWorldRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_setworldrotation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SetWorldTransform](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_setworldtransform)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SphereOverlapComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_sphereoverlapcomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SphereTraceComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_spheretracecomponent)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnRep_AttachChildren](ue_ue.LandscapeHeightfieldCollisionComponent.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnRep_AttachParent](ue_ue.LandscapeHeightfieldCollisionComponent.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnRep_AttachSocketName](ue_ue.LandscapeHeightfieldCollisionComponent.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnRep_IsActive](ue_ue.LandscapeHeightfieldCollisionComponent.md#onrep_isactive)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnRep_Transform](ue_ue.LandscapeHeightfieldCollisionComponent.md#onrep_transform)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnRep_Visibility](ue_ue.LandscapeHeightfieldCollisionComponent.md#onrep_visibility)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[PutRigidBodyToSleep](ue_ue.LandscapeHeightfieldCollisionComponent.md#putrigidbodytosleep)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ReceiveBeginPlay](ue_ue.LandscapeHeightfieldCollisionComponent.md#receivebeginplay)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ReceiveEndPlay](ue_ue.LandscapeHeightfieldCollisionComponent.md#receiveendplay)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ReceiveTick](ue_ue.LandscapeHeightfieldCollisionComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[RegisterComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#registercomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[RemoveTickPrerequisiteActor](ue_ue.LandscapeHeightfieldCollisionComponent.md#removetickprerequisiteactor)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#removetickprerequisitecomponent)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ResetRelativeTransform](ue_ue.LandscapeHeightfieldCollisionComponent.md#resetrelativetransform)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ScaleByMomentOfInertia](ue_ue.LandscapeHeightfieldCollisionComponent.md#scalebymomentofinertia)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetAbsolute](ue_ue.LandscapeHeightfieldCollisionComponent.md#setabsolute)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetActive](ue_ue.LandscapeHeightfieldCollisionComponent.md#setactive)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetAllMassScale](ue_ue.LandscapeHeightfieldCollisionComponent.md#setallmassscale)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetAllPhysicsAngularVelocityInDegrees](ue_ue.LandscapeHeightfieldCollisionComponent.md#setallphysicsangularvelocityindegrees)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetAllPhysicsAngularVelocityInRadians](ue_ue.LandscapeHeightfieldCollisionComponent.md#setallphysicsangularvelocityinradians)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetAllPhysicsLinearVelocity](ue_ue.LandscapeHeightfieldCollisionComponent.md#setallphysicslinearvelocity)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetAllUseCCD](ue_ue.LandscapeHeightfieldCollisionComponent.md#setalluseccd)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetAngularDamping](ue_ue.LandscapeHeightfieldCollisionComponent.md#setangulardamping)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetAutoActivate](ue_ue.LandscapeHeightfieldCollisionComponent.md#setautoactivate)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetBoundsScale](ue_ue.LandscapeHeightfieldCollisionComponent.md#setboundsscale)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCastInsetShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcastinsetshadow)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCastShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcastshadow)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCenterOfMass](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcenterofmass)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCollisionEnabled](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcollisionenabled)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCollisionObjectType](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcollisionobjecttype)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCollisionProfileName](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcollisionprofilename)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCollisionResponseToAllChannels](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcollisionresponsetoallchannels)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCollisionResponseToChannel](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcollisionresponsetochannel)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetComponentTickEnabled](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcomponenttickenabled)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetComponentTickInterval](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcomponenttickinterval)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetConstraintMode](ue_ue.LandscapeHeightfieldCollisionComponent.md#setconstraintmode)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCullDistance](ue_ue.LandscapeHeightfieldCollisionComponent.md#setculldistance)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCustomDepthStencilValue](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcustomdepthstencilvalue)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCustomDepthStencilWriteMask](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcustomdepthstencilwritemask)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCustomPrimitiveDataFloat](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcustomprimitivedatafloat)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCustomPrimitiveDataVector2](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcustomprimitivedatavector2)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCustomPrimitiveDataVector3](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcustomprimitivedatavector3)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCustomPrimitiveDataVector4](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcustomprimitivedatavector4)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetEnableGravity](ue_ue.LandscapeHeightfieldCollisionComponent.md#setenablegravity)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetExcludeFromLightAttachmentGroup](ue_ue.LandscapeHeightfieldCollisionComponent.md#setexcludefromlightattachmentgroup)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetGenerateOverlapEvents](ue_ue.LandscapeHeightfieldCollisionComponent.md#setgenerateoverlapevents)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetHiddenInGame](ue_ue.LandscapeHeightfieldCollisionComponent.md#sethiddeningame)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetIsReplicated](ue_ue.LandscapeHeightfieldCollisionComponent.md#setisreplicated)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetLightAttachmentsAsGroup](ue_ue.LandscapeHeightfieldCollisionComponent.md#setlightattachmentsasgroup)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetLinearDamping](ue_ue.LandscapeHeightfieldCollisionComponent.md#setlineardamping)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetMassOverrideInKg](ue_ue.LandscapeHeightfieldCollisionComponent.md#setmassoverrideinkg)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetMassScale](ue_ue.LandscapeHeightfieldCollisionComponent.md#setmassscale)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetMaterial](ue_ue.LandscapeHeightfieldCollisionComponent.md#setmaterial)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetMaterialByName](ue_ue.LandscapeHeightfieldCollisionComponent.md#setmaterialbyname)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetMobility](ue_ue.LandscapeHeightfieldCollisionComponent.md#setmobility)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetNotifyRigidBodyCollision](ue_ue.LandscapeHeightfieldCollisionComponent.md#setnotifyrigidbodycollision)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetOnlyOwnerSee](ue_ue.LandscapeHeightfieldCollisionComponent.md#setonlyownersee)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetOwnerNoSee](ue_ue.LandscapeHeightfieldCollisionComponent.md#setownernosee)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetPhysMaterialOverride](ue_ue.LandscapeHeightfieldCollisionComponent.md#setphysmaterialoverride)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetPhysicsAngularVelocity](ue_ue.LandscapeHeightfieldCollisionComponent.md#setphysicsangularvelocity)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetPhysicsAngularVelocityInDegrees](ue_ue.LandscapeHeightfieldCollisionComponent.md#setphysicsangularvelocityindegrees)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetPhysicsAngularVelocityInRadians](ue_ue.LandscapeHeightfieldCollisionComponent.md#setphysicsangularvelocityinradians)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetPhysicsLinearVelocity](ue_ue.LandscapeHeightfieldCollisionComponent.md#setphysicslinearvelocity)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetPhysicsMaxAngularVelocity](ue_ue.LandscapeHeightfieldCollisionComponent.md#setphysicsmaxangularvelocity)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetPhysicsMaxAngularVelocityInDegrees](ue_ue.LandscapeHeightfieldCollisionComponent.md#setphysicsmaxangularvelocityindegrees)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetPhysicsMaxAngularVelocityInRadians](ue_ue.LandscapeHeightfieldCollisionComponent.md#setphysicsmaxangularvelocityinradians)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetReceivesDecals](ue_ue.LandscapeHeightfieldCollisionComponent.md#setreceivesdecals)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetRelativeScale3D](ue_ue.LandscapeHeightfieldCollisionComponent.md#setrelativescale3d)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetRenderCustomDepth](ue_ue.LandscapeHeightfieldCollisionComponent.md#setrendercustomdepth)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetRenderInMainPass](ue_ue.LandscapeHeightfieldCollisionComponent.md#setrenderinmainpass)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.LandscapeHeightfieldCollisionComponent.md#setshouldupdatephysicsvolume)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetSimulatePhysics](ue_ue.LandscapeHeightfieldCollisionComponent.md#setsimulatephysics)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetSingleSampleShadowFromStationaryLights](ue_ue.LandscapeHeightfieldCollisionComponent.md#setsinglesampleshadowfromstationarylights)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetTickGroup](ue_ue.LandscapeHeightfieldCollisionComponent.md#settickgroup)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetTickableWhenPaused](ue_ue.LandscapeHeightfieldCollisionComponent.md#settickablewhenpaused)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetTranslucentSortPriority](ue_ue.LandscapeHeightfieldCollisionComponent.md#settranslucentsortpriority)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetUseCCD](ue_ue.LandscapeHeightfieldCollisionComponent.md#setuseccd)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetVisibility](ue_ue.LandscapeHeightfieldCollisionComponent.md#setvisibility)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetWalkableSlopeOverride](ue_ue.LandscapeHeightfieldCollisionComponent.md#setwalkableslopeoverride)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetWorldScale3D](ue_ue.LandscapeHeightfieldCollisionComponent.md#setworldscale3d)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetupAttachment](ue_ue.LandscapeHeightfieldCollisionComponent.md#setupattachment)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SnapTo](ue_ue.LandscapeHeightfieldCollisionComponent.md#snapto)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ToggleActive](ue_ue.LandscapeHeightfieldCollisionComponent.md#toggleactive)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ToggleVisibility](ue_ue.LandscapeHeightfieldCollisionComponent.md#togglevisibility)

___

### WakeAllRigidBodies

▸ **WakeAllRigidBodies**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[WakeAllRigidBodies](ue_ue.LandscapeHeightfieldCollisionComponent.md#wakeallrigidbodies)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[WakeRigidBody](ue_ue.LandscapeHeightfieldCollisionComponent.md#wakerigidbody)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LandscapeMeshCollisionComponent`](ue_ue.LandscapeMeshCollisionComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LandscapeMeshCollisionComponent`](ue_ue.LandscapeMeshCollisionComponent.md)

#### Overrides

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[Find](ue_ue.LandscapeHeightfieldCollisionComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LandscapeMeshCollisionComponent`](ue_ue.LandscapeMeshCollisionComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LandscapeMeshCollisionComponent`](ue_ue.LandscapeMeshCollisionComponent.md)

#### Overrides

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[Load](ue_ue.LandscapeHeightfieldCollisionComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[StaticClass](ue_ue.LandscapeHeightfieldCollisionComponent.md#staticclass)
