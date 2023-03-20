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

#### Defined in

[ue/ue.d.ts:44553](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44553)

## Properties

### AlwaysLoadOnClient

• **AlwaysLoadOnClient**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AlwaysLoadOnClient](ue_ue.LandscapeHeightfieldCollisionComponent.md#alwaysloadonclient)

#### Defined in

[ue/ue.d.ts:12608](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12608)

___

### AlwaysLoadOnServer

• **AlwaysLoadOnServer**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AlwaysLoadOnServer](ue_ue.LandscapeHeightfieldCollisionComponent.md#alwaysloadonserver)

#### Defined in

[ue/ue.d.ts:12609](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12609)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AssetUserData](ue_ue.LandscapeHeightfieldCollisionComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L291)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AttachChildren](ue_ue.LandscapeHeightfieldCollisionComponent.md#attachchildren)

#### Defined in

[ue/ue.d.ts:12873](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12873)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AttachParent](ue_ue.LandscapeHeightfieldCollisionComponent.md#attachparent)

#### Defined in

[ue/ue.d.ts:12871](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12871)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AttachSocketName](ue_ue.LandscapeHeightfieldCollisionComponent.md#attachsocketname)

#### Defined in

[ue/ue.d.ts:12872](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12872)

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[BodyInstance](ue_ue.LandscapeHeightfieldCollisionComponent.md#bodyinstance)

#### Defined in

[ue/ue.d.ts:12630](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12630)

___

### BoundsScale

• **BoundsScale**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[BoundsScale](ue_ue.LandscapeHeightfieldCollisionComponent.md#boundsscale)

#### Defined in

[ue/ue.d.ts:12627](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12627)

___

### CachedLocalBox

• **CachedLocalBox**: [`Box`](ue_ue.Box.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CachedLocalBox](ue_ue.LandscapeHeightfieldCollisionComponent.md#cachedlocalbox)

#### Defined in

[ue/ue.d.ts:43886](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43886)

___

### CachedMaxDrawDistance

• **CachedMaxDrawDistance**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CachedMaxDrawDistance](ue_ue.LandscapeHeightfieldCollisionComponent.md#cachedmaxdrawdistance)

#### Defined in

[ue/ue.d.ts:12557](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12557)

___

### CanBeCharacterBase

• **CanBeCharacterBase**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CanBeCharacterBase](ue_ue.LandscapeHeightfieldCollisionComponent.md#canbecharacterbase)

#### Defined in

[ue/ue.d.ts:12613](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12613)

___

### CanCharacterStepUpOn

• **CanCharacterStepUpOn**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CanCharacterStepUpOn](ue_ue.LandscapeHeightfieldCollisionComponent.md#cancharacterstepupon)

#### Defined in

[ue/ue.d.ts:12614](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12614)

___

### CastShadow

• **CastShadow**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CastShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#castshadow)

#### Defined in

[ue/ue.d.ts:12587](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12587)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ClientAttachedChildren](ue_ue.LandscapeHeightfieldCollisionComponent.md#clientattachedchildren)

#### Defined in

[ue/ue.d.ts:12874](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12874)

___

### CollisionQuadFlags

• **CollisionQuadFlags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CollisionQuadFlags](ue_ue.LandscapeHeightfieldCollisionComponent.md#collisionquadflags)

#### Defined in

[ue/ue.d.ts:43884](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43884)

___

### CollisionScale

• **CollisionScale**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CollisionScale](ue_ue.LandscapeHeightfieldCollisionComponent.md#collisionscale)

#### Defined in

[ue/ue.d.ts:43882](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43882)

___

### CollisionSizeQuads

• **CollisionSizeQuads**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CollisionSizeQuads](ue_ue.LandscapeHeightfieldCollisionComponent.md#collisionsizequads)

#### Defined in

[ue/ue.d.ts:43881](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43881)

___

### ComponentLayerInfos

• **ComponentLayerInfos**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeLayerInfoObject`](ue_ue.LandscapeLayerInfoObject.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ComponentLayerInfos](ue_ue.LandscapeHeightfieldCollisionComponent.md#componentlayerinfos)

#### Defined in

[ue/ue.d.ts:43878](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43878)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ComponentTags](ue_ue.LandscapeHeightfieldCollisionComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L290)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ComponentVelocity](ue_ue.LandscapeHeightfieldCollisionComponent.md#componentvelocity)

#### Defined in

[ue/ue.d.ts:12878](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12878)

___

### CookedPhysicalMaterials

• **CookedPhysicalMaterials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CookedPhysicalMaterials](ue_ue.LandscapeHeightfieldCollisionComponent.md#cookedphysicalmaterials)

#### Defined in

[ue/ue.d.ts:43888](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43888)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CreationMethod](ue_ue.LandscapeHeightfieldCollisionComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L302)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CustomDepthStencilValue](ue_ue.LandscapeHeightfieldCollisionComponent.md#customdepthstencilvalue)

#### Defined in

[ue/ue.d.ts:12617](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12617)

___

### CustomDepthStencilWriteMask

• **CustomDepthStencilWriteMask**: [`ERendererStencilMask`](../enums/ue_ue.ERendererStencilMask.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CustomDepthStencilWriteMask](ue_ue.LandscapeHeightfieldCollisionComponent.md#customdepthstencilwritemask)

#### Defined in

[ue/ue.d.ts:12616](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12616)

___

### CustomPrimitiveData

• **CustomPrimitiveData**: [`CustomPrimitiveData`](ue_ue.CustomPrimitiveData.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CustomPrimitiveData](ue_ue.LandscapeHeightfieldCollisionComponent.md#customprimitivedata)

#### Defined in

[ue/ue.d.ts:12618](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12618)

___

### DepthPriorityGroup

• **DepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[DepthPriorityGroup](ue_ue.LandscapeHeightfieldCollisionComponent.md#depthprioritygroup)

#### Defined in

[ue/ue.d.ts:12558](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12558)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[DetailMode](ue_ue.LandscapeHeightfieldCollisionComponent.md#detailmode)

#### Defined in

[ue/ue.d.ts:12893](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12893)

___

### ExcludeForSpecificHLODLevels

• **ExcludeForSpecificHLODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ExcludeForSpecificHLODLevels](ue_ue.LandscapeHeightfieldCollisionComponent.md#excludeforspecifichlodlevels)

#### Defined in

[ue/ue.d.ts:12562](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12562)

___

### HeightfieldGuid

• **HeightfieldGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[HeightfieldGuid](ue_ue.LandscapeHeightfieldCollisionComponent.md#heightfieldguid)

#### Defined in

[ue/ue.d.ts:43885](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43885)

___

### IndirectLightingCacheQuality

• **IndirectLightingCacheQuality**: [`EIndirectLightingCacheQuality`](../enums/ue_ue.EIndirectLightingCacheQuality.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IndirectLightingCacheQuality](ue_ue.LandscapeHeightfieldCollisionComponent.md#indirectlightingcachequality)

#### Defined in

[ue/ue.d.ts:12560](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12560)

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[LDMaxDrawDistance](ue_ue.LandscapeHeightfieldCollisionComponent.md#ldmaxdrawdistance)

#### Defined in

[ue/ue.d.ts:12556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12556)

___

### LODParentPrimitive

• **LODParentPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[LODParentPrimitive](ue_ue.LandscapeHeightfieldCollisionComponent.md#lodparentprimitive)

#### Defined in

[ue/ue.d.ts:12644](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12644)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[LightingChannels](ue_ue.LandscapeHeightfieldCollisionComponent.md#lightingchannels)

#### Defined in

[ue/ue.d.ts:12615](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12615)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[LightmapType](ue_ue.LandscapeHeightfieldCollisionComponent.md#lightmaptype)

#### Defined in

[ue/ue.d.ts:12561](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12561)

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[LpvBiasMultiplier](ue_ue.LandscapeHeightfieldCollisionComponent.md#lpvbiasmultiplier)

#### Defined in

[ue/ue.d.ts:12626](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12626)

___

### MeshGuid

• **MeshGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:44554](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44554)

___

### MinDrawDistance

• **MinDrawDistance**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[MinDrawDistance](ue_ue.LandscapeHeightfieldCollisionComponent.md#mindrawdistance)

#### Defined in

[ue/ue.d.ts:12555](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12555)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[Mobility](ue_ue.LandscapeHeightfieldCollisionComponent.md#mobility)

#### Defined in

[ue/ue.d.ts:12892](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12892)

___

### MoveIgnoreActors

• **MoveIgnoreActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[MoveIgnoreActors](ue_ue.LandscapeHeightfieldCollisionComponent.md#moveignoreactors)

#### Defined in

[ue/ue.d.ts:12628](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12628)

___

### MoveIgnoreComponents

• **MoveIgnoreComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[MoveIgnoreComponents](ue_ue.LandscapeHeightfieldCollisionComponent.md#moveignorecomponents)

#### Defined in

[ue/ue.d.ts:12629](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12629)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnBeginCursorOver](ue_ue.LandscapeHeightfieldCollisionComponent.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:12636](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12636)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnClicked](ue_ue.LandscapeHeightfieldCollisionComponent.md#onclicked)

#### Defined in

[ue/ue.d.ts:12638](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12638)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnComponentActivated](ue_ue.LandscapeHeightfieldCollisionComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L303)

___

### OnComponentBeginOverlap

• **OnComponentBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`, `bFromSweep`: `boolean`, `SweepResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnComponentBeginOverlap](ue_ue.LandscapeHeightfieldCollisionComponent.md#oncomponentbeginoverlap)

#### Defined in

[ue/ue.d.ts:12632](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12632)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnComponentDeactivated](ue_ue.LandscapeHeightfieldCollisionComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L304)

___

### OnComponentEndOverlap

• **OnComponentEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnComponentEndOverlap](ue_ue.LandscapeHeightfieldCollisionComponent.md#oncomponentendoverlap)

#### Defined in

[ue/ue.d.ts:12633](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12633)

___

### OnComponentHit

• **OnComponentHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`HitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnComponentHit](ue_ue.LandscapeHeightfieldCollisionComponent.md#oncomponenthit)

#### Defined in

[ue/ue.d.ts:12631](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12631)

___

### OnComponentSleep

• **OnComponentSleep**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SleepingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnComponentSleep](ue_ue.LandscapeHeightfieldCollisionComponent.md#oncomponentsleep)

#### Defined in

[ue/ue.d.ts:12635](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12635)

___

### OnComponentWake

• **OnComponentWake**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`WakingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnComponentWake](ue_ue.LandscapeHeightfieldCollisionComponent.md#oncomponentwake)

#### Defined in

[ue/ue.d.ts:12634](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12634)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnEndCursorOver](ue_ue.LandscapeHeightfieldCollisionComponent.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:12637](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12637)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnInputTouchBegin](ue_ue.LandscapeHeightfieldCollisionComponent.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:12640](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12640)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnInputTouchEnd](ue_ue.LandscapeHeightfieldCollisionComponent.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:12641](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12641)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnInputTouchEnter](ue_ue.LandscapeHeightfieldCollisionComponent.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:12642](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12642)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnInputTouchLeave](ue_ue.LandscapeHeightfieldCollisionComponent.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:12643](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12643)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnReleased](ue_ue.LandscapeHeightfieldCollisionComponent.md#onreleased)

#### Defined in

[ue/ue.d.ts:12639](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12639)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[PhysicsVolume](ue_ue.LandscapeHeightfieldCollisionComponent.md#physicsvolume)

#### Defined in

[ue/ue.d.ts:12870](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12870)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.LandscapeHeightfieldCollisionComponent.md#physicsvolumechangeddelegate)

#### Defined in

[ue/ue.d.ts:12894](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12894)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[PrimaryComponentTick](ue_ue.LandscapeHeightfieldCollisionComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L289)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[RelativeLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#relativelocation)

#### Defined in

[ue/ue.d.ts:12875](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12875)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[RelativeRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#relativerotation)

#### Defined in

[ue/ue.d.ts:12876](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12876)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[RelativeScale3D](ue_ue.LandscapeHeightfieldCollisionComponent.md#relativescale3d)

#### Defined in

[ue/ue.d.ts:12877](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12877)

___

### RenderComponent

• **RenderComponent**: [`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`LandscapeComponent`](ue_ue.LandscapeComponent.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[RenderComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#rendercomponent)

#### Defined in

[ue/ue.d.ts:43887](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43887)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[RuntimeVirtualTextures](ue_ue.LandscapeHeightfieldCollisionComponent.md#runtimevirtualtextures)

#### Defined in

[ue/ue.d.ts:12621](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12621)

___

### SectionBaseX

• **SectionBaseX**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SectionBaseX](ue_ue.LandscapeHeightfieldCollisionComponent.md#sectionbasex)

#### Defined in

[ue/ue.d.ts:43879](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43879)

___

### SectionBaseY

• **SectionBaseY**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SectionBaseY](ue_ue.LandscapeHeightfieldCollisionComponent.md#sectionbasey)

#### Defined in

[ue/ue.d.ts:43880](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43880)

___

### SimpleCollisionSizeQuads

• **SimpleCollisionSizeQuads**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SimpleCollisionSizeQuads](ue_ue.LandscapeHeightfieldCollisionComponent.md#simplecollisionsizequads)

#### Defined in

[ue/ue.d.ts:43883](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43883)

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[TranslucencySortPriority](ue_ue.LandscapeHeightfieldCollisionComponent.md#translucencysortpriority)

#### Defined in

[ue/ue.d.ts:12619](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12619)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[UCSModifiedProperties](ue_ue.LandscapeHeightfieldCollisionComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L305)

___

### ViewOwnerDepthPriorityGroup

• **ViewOwnerDepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ViewOwnerDepthPriorityGroup](ue_ue.LandscapeHeightfieldCollisionComponent.md#viewownerdepthprioritygroup)

#### Defined in

[ue/ue.d.ts:12559](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12559)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[VirtualTextureCullMips](ue_ue.LandscapeHeightfieldCollisionComponent.md#virtualtexturecullmips)

#### Defined in

[ue/ue.d.ts:12623](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12623)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[VirtualTextureLodBias](ue_ue.LandscapeHeightfieldCollisionComponent.md#virtualtexturelodbias)

#### Defined in

[ue/ue.d.ts:12622](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12622)

___

### VirtualTextureMinCoverage

• **VirtualTextureMinCoverage**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[VirtualTextureMinCoverage](ue_ue.LandscapeHeightfieldCollisionComponent.md#virtualtexturemincoverage)

#### Defined in

[ue/ue.d.ts:12624](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12624)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[VirtualTextureRenderPassType](ue_ue.LandscapeHeightfieldCollisionComponent.md#virtualtexturerenderpasstype)

#### Defined in

[ue/ue.d.ts:12625](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12625)

___

### VisibilityId

• **VisibilityId**: `number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[VisibilityId](ue_ue.LandscapeHeightfieldCollisionComponent.md#visibilityid)

#### Defined in

[ue/ue.d.ts:12620](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12620)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[__tid_ActorComponent__](ue_ue.LandscapeHeightfieldCollisionComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L336)

___

### \_\_tid\_LandscapeHeightfieldCollisionComponent\_\_

• **\_\_tid\_LandscapeHeightfieldCollisionComponent\_\_**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[__tid_LandscapeHeightfieldCollisionComponent__](ue_ue.LandscapeHeightfieldCollisionComponent.md#__tid_landscapeheightfieldcollisioncomponent__)

#### Defined in

[ue/ue.d.ts:43894](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43894)

___

### \_\_tid\_LandscapeMeshCollisionComponent\_\_

• **\_\_tid\_LandscapeMeshCollisionComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:44559](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44559)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[__tid_Object__](ue_ue.LandscapeHeightfieldCollisionComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PrimitiveComponent\_\_

• **\_\_tid\_PrimitiveComponent\_\_**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[__tid_PrimitiveComponent__](ue_ue.LandscapeHeightfieldCollisionComponent.md#__tid_primitivecomponent__)

#### Defined in

[ue/ue.d.ts:12761](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12761)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[__tid_SceneComponent__](ue_ue.LandscapeHeightfieldCollisionComponent.md#__tid_scenecomponent__)

#### Defined in

[ue/ue.d.ts:12961](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12961)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bAbsoluteLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#babsolutelocation)

#### Defined in

[ue/ue.d.ts:12880](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12880)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bAbsoluteRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#babsoluterotation)

#### Defined in

[ue/ue.d.ts:12881](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12881)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bAbsoluteScale](ue_ue.LandscapeHeightfieldCollisionComponent.md#babsolutescale)

#### Defined in

[ue/ue.d.ts:12882](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12882)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bAffectDistanceFieldLighting](ue_ue.LandscapeHeightfieldCollisionComponent.md#baffectdistancefieldlighting)

#### Defined in

[ue/ue.d.ts:12589](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12589)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bAffectDynamicIndirectLighting](ue_ue.LandscapeHeightfieldCollisionComponent.md#baffectdynamicindirectlighting)

#### Defined in

[ue/ue.d.ts:12588](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12588)

___

### bAllowCullDistanceVolume

• **bAllowCullDistanceVolume**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bAllowCullDistanceVolume](ue_ue.LandscapeHeightfieldCollisionComponent.md#ballowculldistancevolume)

#### Defined in

[ue/ue.d.ts:12573](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12573)

___

### bAlwaysCreatePhysicsState

• **bAlwaysCreatePhysicsState**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bAlwaysCreatePhysicsState](ue_ue.LandscapeHeightfieldCollisionComponent.md#balwayscreatephysicsstate)

#### Defined in

[ue/ue.d.ts:12567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12567)

___

### bApplyImpulseOnDamage

• **bApplyImpulseOnDamage**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bApplyImpulseOnDamage](ue_ue.LandscapeHeightfieldCollisionComponent.md#bapplyimpulseondamage)

#### Defined in

[ue/ue.d.ts:12606](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12606)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bAutoActivate](ue_ue.LandscapeHeightfieldCollisionComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L296)

___

### bBatchImpostersAsInstances

• **bBatchImpostersAsInstances**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bBatchImpostersAsInstances](ue_ue.LandscapeHeightfieldCollisionComponent.md#bbatchimpostersasinstances)

#### Defined in

[ue/ue.d.ts:12565](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12565)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.LandscapeHeightfieldCollisionComponent.md#bboundschangetriggersstreamingdatarebuild)

#### Defined in

[ue/ue.d.ts:12889](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12889)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCanEverAffectNavigation](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L299)

___

### bCastCinematicShadow

• **bCastCinematicShadow**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCastCinematicShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcastcinematicshadow)

#### Defined in

[ue/ue.d.ts:12596](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12596)

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCastDynamicShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcastdynamicshadow)

#### Defined in

[ue/ue.d.ts:12590](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12590)

___

### bCastFarShadow

• **bCastFarShadow**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCastFarShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcastfarshadow)

#### Defined in

[ue/ue.d.ts:12594](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12594)

___

### bCastHiddenShadow

• **bCastHiddenShadow**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCastHiddenShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcasthiddenshadow)

#### Defined in

[ue/ue.d.ts:12597](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12597)

___

### bCastInsetShadow

• **bCastInsetShadow**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCastInsetShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcastinsetshadow)

#### Defined in

[ue/ue.d.ts:12595](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12595)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCastShadowAsTwoSided](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcastshadowastwosided)

#### Defined in

[ue/ue.d.ts:12598](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12598)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCastStaticShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcaststaticshadow)

#### Defined in

[ue/ue.d.ts:12591](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12591)

___

### bCastVolumetricTranslucentShadow

• **bCastVolumetricTranslucentShadow**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCastVolumetricTranslucentShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcastvolumetrictranslucentshadow)

#### Defined in

[ue/ue.d.ts:12592](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12592)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bComponentToWorldUpdated](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcomponenttoworldupdated)

#### Defined in

[ue/ue.d.ts:12879](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12879)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bCreatedByConstructionScript](ue_ue.LandscapeHeightfieldCollisionComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bEditableWhenInherited](ue_ue.LandscapeHeightfieldCollisionComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L298)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bEnableAutoLODGeneration](ue_ue.LandscapeHeightfieldCollisionComponent.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:12563](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12563)

___

### bExcludeFromLightAttachmentGroup

• **bExcludeFromLightAttachmentGroup**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bExcludeFromLightAttachmentGroup](ue_ue.LandscapeHeightfieldCollisionComponent.md#bexcludefromlightattachmentgroup)

#### Defined in

[ue/ue.d.ts:12601](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12601)

___

### bForceMipStreaming

• **bForceMipStreaming**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bForceMipStreaming](ue_ue.LandscapeHeightfieldCollisionComponent.md#bforcemipstreaming)

#### Defined in

[ue/ue.d.ts:12585](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12585)

___

### bGenerateOverlapEvents

• **bGenerateOverlapEvents**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bGenerateOverlapEvents](ue_ue.LandscapeHeightfieldCollisionComponent.md#bgenerateoverlapevents)

#### Defined in

[ue/ue.d.ts:12568](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12568)

___

### bHasCustomNavigableGeometry

• **bHasCustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bHasCustomNavigableGeometry](ue_ue.LandscapeHeightfieldCollisionComponent.md#bhascustomnavigablegeometry)

#### Defined in

[ue/ue.d.ts:12612](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12612)

___

### bHasMotionBlurVelocityMeshes

• **bHasMotionBlurVelocityMeshes**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bHasMotionBlurVelocityMeshes](ue_ue.LandscapeHeightfieldCollisionComponent.md#bhasmotionblurvelocitymeshes)

#### Defined in

[ue/ue.d.ts:12574](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12574)

___

### bHasPerInstanceHitProxies

• **bHasPerInstanceHitProxies**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bHasPerInstanceHitProxies](ue_ue.LandscapeHeightfieldCollisionComponent.md#bhasperinstancehitproxies)

#### Defined in

[ue/ue.d.ts:12586](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12586)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bHiddenInGame](ue_ue.LandscapeHeightfieldCollisionComponent.md#bhiddeningame)

#### Defined in

[ue/ue.d.ts:12884](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12884)

___

### bIgnoreRadialForce

• **bIgnoreRadialForce**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bIgnoreRadialForce](ue_ue.LandscapeHeightfieldCollisionComponent.md#bignoreradialforce)

#### Defined in

[ue/ue.d.ts:12605](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12605)

___

### bIgnoreRadialImpulse

• **bIgnoreRadialImpulse**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bIgnoreRadialImpulse](ue_ue.LandscapeHeightfieldCollisionComponent.md#bignoreradialimpulse)

#### Defined in

[ue/ue.d.ts:12604](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12604)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bInstanceComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bIsActive](ue_ue.LandscapeHeightfieldCollisionComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bIsEditorOnly](ue_ue.LandscapeHeightfieldCollisionComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bIsVisualizationComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L301)

___

### bLightAsIfStatic

• **bLightAsIfStatic**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bLightAsIfStatic](ue_ue.LandscapeHeightfieldCollisionComponent.md#blightasifstatic)

#### Defined in

[ue/ue.d.ts:12599](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12599)

___

### bLightAttachmentsAsGroup

• **bLightAttachmentsAsGroup**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bLightAttachmentsAsGroup](ue_ue.LandscapeHeightfieldCollisionComponent.md#blightattachmentsasgroup)

#### Defined in

[ue/ue.d.ts:12600](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12600)

___

### bMultiBodyOverlap

• **bMultiBodyOverlap**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bMultiBodyOverlap](ue_ue.LandscapeHeightfieldCollisionComponent.md#bmultibodyoverlap)

#### Defined in

[ue/ue.d.ts:12569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12569)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bNetAddressable](ue_ue.LandscapeHeightfieldCollisionComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L293)

___

### bNeverDistanceCull

• **bNeverDistanceCull**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bNeverDistanceCull](ue_ue.LandscapeHeightfieldCollisionComponent.md#bneverdistancecull)

#### Defined in

[ue/ue.d.ts:12566](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12566)

___

### bOnlyOwnerSee

• **bOnlyOwnerSee**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bOnlyOwnerSee](ue_ue.LandscapeHeightfieldCollisionComponent.md#bonlyownersee)

#### Defined in

[ue/ue.d.ts:12581](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12581)

___

### bOwnerNoSee

• **bOwnerNoSee**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bOwnerNoSee](ue_ue.LandscapeHeightfieldCollisionComponent.md#bownernosee)

#### Defined in

[ue/ue.d.ts:12580](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12580)

___

### bReceiveMobileCSMShadows

• **bReceiveMobileCSMShadows**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bReceiveMobileCSMShadows](ue_ue.LandscapeHeightfieldCollisionComponent.md#breceivemobilecsmshadows)

#### Defined in

[ue/ue.d.ts:12602](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12602)

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bReceivesDecals](ue_ue.LandscapeHeightfieldCollisionComponent.md#breceivesdecals)

#### Defined in

[ue/ue.d.ts:12579](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12579)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bRenderCustomDepth](ue_ue.LandscapeHeightfieldCollisionComponent.md#brendercustomdepth)

#### Defined in

[ue/ue.d.ts:12611](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12611)

___

### bRenderInDepthPass

• **bRenderInDepthPass**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bRenderInDepthPass](ue_ue.LandscapeHeightfieldCollisionComponent.md#brenderindepthpass)

#### Defined in

[ue/ue.d.ts:12578](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12578)

___

### bRenderInMainPass

• **bRenderInMainPass**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bRenderInMainPass](ue_ue.LandscapeHeightfieldCollisionComponent.md#brenderinmainpass)

#### Defined in

[ue/ue.d.ts:12577](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12577)

___

### bReplicatePhysicsToAutonomousProxy

• **bReplicatePhysicsToAutonomousProxy**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bReplicatePhysicsToAutonomousProxy](ue_ue.LandscapeHeightfieldCollisionComponent.md#breplicatephysicstoautonomousproxy)

#### Defined in

[ue/ue.d.ts:12607](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12607)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bReplicates](ue_ue.LandscapeHeightfieldCollisionComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L292)

___

### bReturnMaterialOnMove

• **bReturnMaterialOnMove**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bReturnMaterialOnMove](ue_ue.LandscapeHeightfieldCollisionComponent.md#breturnmaterialonmove)

#### Defined in

[ue/ue.d.ts:12571](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12571)

___

### bSelectable

• **bSelectable**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bSelectable](ue_ue.LandscapeHeightfieldCollisionComponent.md#bselectable)

#### Defined in

[ue/ue.d.ts:12584](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12584)

___

### bSelfShadowOnly

• **bSelfShadowOnly**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bSelfShadowOnly](ue_ue.LandscapeHeightfieldCollisionComponent.md#bselfshadowonly)

#### Defined in

[ue/ue.d.ts:12593](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12593)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bShouldBeAttached](ue_ue.LandscapeHeightfieldCollisionComponent.md#bshouldbeattached)

#### Defined in

[ue/ue.d.ts:12885](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12885)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.LandscapeHeightfieldCollisionComponent.md#bshouldsnaplocationwhenattached)

#### Defined in

[ue/ue.d.ts:12886](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12886)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.LandscapeHeightfieldCollisionComponent.md#bshouldsnaprotationwhenattached)

#### Defined in

[ue/ue.d.ts:12887](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12887)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.LandscapeHeightfieldCollisionComponent.md#bshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12888](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12888)

___

### bSingleSampleShadowFromStationaryLights

• **bSingleSampleShadowFromStationaryLights**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bSingleSampleShadowFromStationaryLights](ue_ue.LandscapeHeightfieldCollisionComponent.md#bsinglesampleshadowfromstationarylights)

#### Defined in

[ue/ue.d.ts:12603](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12603)

___

### bTraceComplexOnMove

• **bTraceComplexOnMove**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bTraceComplexOnMove](ue_ue.LandscapeHeightfieldCollisionComponent.md#btracecomplexonmove)

#### Defined in

[ue/ue.d.ts:12570](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12570)

___

### bTreatAsBackgroundForOcclusion

• **bTreatAsBackgroundForOcclusion**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bTreatAsBackgroundForOcclusion](ue_ue.LandscapeHeightfieldCollisionComponent.md#btreatasbackgroundforocclusion)

#### Defined in

[ue/ue.d.ts:12582](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12582)

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bUseAsOccluder](ue_ue.LandscapeHeightfieldCollisionComponent.md#buseasoccluder)

#### Defined in

[ue/ue.d.ts:12583](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12583)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bUseAttachParentBound](ue_ue.LandscapeHeightfieldCollisionComponent.md#buseattachparentbound)

#### Defined in

[ue/ue.d.ts:12890](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12890)

___

### bUseEditorCompositing

• **bUseEditorCompositing**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bUseEditorCompositing](ue_ue.LandscapeHeightfieldCollisionComponent.md#buseeditorcompositing)

#### Defined in

[ue/ue.d.ts:12610](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12610)

___

### bUseMaxLODAsImposter

• **bUseMaxLODAsImposter**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bUseMaxLODAsImposter](ue_ue.LandscapeHeightfieldCollisionComponent.md#busemaxlodasimposter)

#### Defined in

[ue/ue.d.ts:12564](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12564)

___

### bUseViewOwnerDepthPriorityGroup

• **bUseViewOwnerDepthPriorityGroup**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bUseViewOwnerDepthPriorityGroup](ue_ue.LandscapeHeightfieldCollisionComponent.md#buseviewownerdepthprioritygroup)

#### Defined in

[ue/ue.d.ts:12572](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12572)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bVisible](ue_ue.LandscapeHeightfieldCollisionComponent.md#bvisible)

#### Defined in

[ue/ue.d.ts:12883](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12883)

___

### bVisibleInRayTracing

• **bVisibleInRayTracing**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bVisibleInRayTracing](ue_ue.LandscapeHeightfieldCollisionComponent.md#bvisibleinraytracing)

#### Defined in

[ue/ue.d.ts:12576](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12576)

___

### bVisibleInReflectionCaptures

• **bVisibleInReflectionCaptures**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bVisibleInReflectionCaptures](ue_ue.LandscapeHeightfieldCollisionComponent.md#bvisibleinreflectioncaptures)

#### Defined in

[ue/ue.d.ts:12575](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12575)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[bVisualizeComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#bvisualizecomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[Activate](ue_ue.LandscapeHeightfieldCollisionComponent.md#activate)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddAngularImpulse](ue_ue.LandscapeHeightfieldCollisionComponent.md#addangularimpulse)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddAngularImpulseInDegrees](ue_ue.LandscapeHeightfieldCollisionComponent.md#addangularimpulseindegrees)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddAngularImpulseInRadians](ue_ue.LandscapeHeightfieldCollisionComponent.md#addangularimpulseinradians)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddForce](ue_ue.LandscapeHeightfieldCollisionComponent.md#addforce)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddForceAtLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#addforceatlocation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddForceAtLocationLocal](ue_ue.LandscapeHeightfieldCollisionComponent.md#addforceatlocationlocal)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddImpulse](ue_ue.LandscapeHeightfieldCollisionComponent.md#addimpulse)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddImpulseAtLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#addimpulseatlocation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddRadialForce](ue_ue.LandscapeHeightfieldCollisionComponent.md#addradialforce)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddRadialImpulse](ue_ue.LandscapeHeightfieldCollisionComponent.md#addradialimpulse)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddTickPrerequisiteActor](ue_ue.LandscapeHeightfieldCollisionComponent.md#addtickprerequisiteactor)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddTickPrerequisiteComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#addtickprerequisitecomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddTorque](ue_ue.LandscapeHeightfieldCollisionComponent.md#addtorque)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddTorqueInDegrees](ue_ue.LandscapeHeightfieldCollisionComponent.md#addtorqueindegrees)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[AddTorqueInRadians](ue_ue.LandscapeHeightfieldCollisionComponent.md#addtorqueinradians)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CanCharacterStepUp](ue_ue.LandscapeHeightfieldCollisionComponent.md#cancharacterstepup)

#### Defined in

[ue/ue.d.ts:12658](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12658)

___

### ClearMoveIgnoreActors

▸ **ClearMoveIgnoreActors**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ClearMoveIgnoreActors](ue_ue.LandscapeHeightfieldCollisionComponent.md#clearmoveignoreactors)

#### Defined in

[ue/ue.d.ts:12659](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12659)

___

### ClearMoveIgnoreComponents

▸ **ClearMoveIgnoreComponents**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ClearMoveIgnoreComponents](ue_ue.LandscapeHeightfieldCollisionComponent.md#clearmoveignorecomponents)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ComponentHasTag](ue_ue.LandscapeHeightfieldCollisionComponent.md#componenthastag)

#### Defined in

[ue/ue.d.ts:309](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L309)

___

### CopyArrayOfMoveIgnoreActors

▸ **CopyArrayOfMoveIgnoreActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CopyArrayOfMoveIgnoreActors](ue_ue.LandscapeHeightfieldCollisionComponent.md#copyarrayofmoveignoreactors)

#### Defined in

[ue/ue.d.ts:12661](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12661)

___

### CopyArrayOfMoveIgnoreComponents

▸ **CopyArrayOfMoveIgnoreComponents**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CopyArrayOfMoveIgnoreComponents](ue_ue.LandscapeHeightfieldCollisionComponent.md#copyarrayofmoveignorecomponents)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CreateAndSetMaterialInstanceDynamic](ue_ue.LandscapeHeightfieldCollisionComponent.md#createandsetmaterialinstancedynamic)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.LandscapeHeightfieldCollisionComponent.md#createandsetmaterialinstancedynamicfrommaterial)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CreateDefaultSubobject](ue_ue.LandscapeHeightfieldCollisionComponent.md#createdefaultsubobject)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[CreateDynamicMaterialInstance](ue_ue.LandscapeHeightfieldCollisionComponent.md#createdynamicmaterialinstance)

#### Defined in

[ue/ue.d.ts:12665](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12665)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[Deactivate](ue_ue.LandscapeHeightfieldCollisionComponent.md#deactivate)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[DetachFromParent](ue_ue.LandscapeHeightfieldCollisionComponent.md#detachfromparent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[DoesSocketExist](ue_ue.LandscapeHeightfieldCollisionComponent.md#doessocketexist)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ExecuteUbergraph](ue_ue.LandscapeHeightfieldCollisionComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetAllSocketNames](ue_ue.LandscapeHeightfieldCollisionComponent.md#getallsocketnames)

#### Defined in

[ue/ue.d.ts:12897](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12897)

___

### GetAngularDamping

▸ **GetAngularDamping**(): `number`

#### Returns

`number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetAngularDamping](ue_ue.LandscapeHeightfieldCollisionComponent.md#getangulardamping)

#### Defined in

[ue/ue.d.ts:12666](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12666)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetAttachParent](ue_ue.LandscapeHeightfieldCollisionComponent.md#getattachparent)

#### Defined in

[ue/ue.d.ts:12898](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12898)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetAttachSocketName](ue_ue.LandscapeHeightfieldCollisionComponent.md#getattachsocketname)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetCenterOfMass](ue_ue.LandscapeHeightfieldCollisionComponent.md#getcenterofmass)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetChildComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#getchildcomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetChildrenComponents](ue_ue.LandscapeHeightfieldCollisionComponent.md#getchildrencomponents)

#### Defined in

[ue/ue.d.ts:12901](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12901)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetClass](ue_ue.LandscapeHeightfieldCollisionComponent.md#getclass)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetClosestPointOnCollision](ue_ue.LandscapeHeightfieldCollisionComponent.md#getclosestpointoncollision)

#### Defined in

[ue/ue.d.ts:12668](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12668)

___

### GetCollisionEnabled

▸ **GetCollisionEnabled**(): [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Returns

[`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetCollisionEnabled](ue_ue.LandscapeHeightfieldCollisionComponent.md#getcollisionenabled)

#### Defined in

[ue/ue.d.ts:12669](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12669)

___

### GetCollisionObjectType

▸ **GetCollisionObjectType**(): [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Returns

[`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetCollisionObjectType](ue_ue.LandscapeHeightfieldCollisionComponent.md#getcollisionobjecttype)

#### Defined in

[ue/ue.d.ts:12670](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12670)

___

### GetCollisionProfileName

▸ **GetCollisionProfileName**(): `string`

#### Returns

`string`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetCollisionProfileName](ue_ue.LandscapeHeightfieldCollisionComponent.md#getcollisionprofilename)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetCollisionResponseToChannel](ue_ue.LandscapeHeightfieldCollisionComponent.md#getcollisionresponsetochannel)

#### Defined in

[ue/ue.d.ts:12672](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12672)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetComponentTickInterval](ue_ue.LandscapeHeightfieldCollisionComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L311)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetComponentVelocity](ue_ue.LandscapeHeightfieldCollisionComponent.md#getcomponentvelocity)

#### Defined in

[ue/ue.d.ts:12902](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12902)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetForwardVector](ue_ue.LandscapeHeightfieldCollisionComponent.md#getforwardvector)

#### Defined in

[ue/ue.d.ts:12903](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12903)

___

### GetGenerateOverlapEvents

▸ **GetGenerateOverlapEvents**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetGenerateOverlapEvents](ue_ue.LandscapeHeightfieldCollisionComponent.md#getgenerateoverlapevents)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetInertiaTensor](ue_ue.LandscapeHeightfieldCollisionComponent.md#getinertiatensor)

#### Defined in

[ue/ue.d.ts:12674](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12674)

___

### GetLinearDamping

▸ **GetLinearDamping**(): `number`

#### Returns

`number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetLinearDamping](ue_ue.LandscapeHeightfieldCollisionComponent.md#getlineardamping)

#### Defined in

[ue/ue.d.ts:12675](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12675)

___

### GetMass

▸ **GetMass**(): `number`

#### Returns

`number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetMass](ue_ue.LandscapeHeightfieldCollisionComponent.md#getmass)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetMassScale](ue_ue.LandscapeHeightfieldCollisionComponent.md#getmassscale)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetMaterial](ue_ue.LandscapeHeightfieldCollisionComponent.md#getmaterial)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetMaterialFromCollisionFaceIndex](ue_ue.LandscapeHeightfieldCollisionComponent.md#getmaterialfromcollisionfaceindex)

#### Defined in

[ue/ue.d.ts:12679](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12679)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetName](ue_ue.LandscapeHeightfieldCollisionComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetNumChildrenComponents](ue_ue.LandscapeHeightfieldCollisionComponent.md#getnumchildrencomponents)

#### Defined in

[ue/ue.d.ts:12904](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12904)

___

### GetNumMaterials

▸ **GetNumMaterials**(): `number`

#### Returns

`number`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetNumMaterials](ue_ue.LandscapeHeightfieldCollisionComponent.md#getnummaterials)

#### Defined in

[ue/ue.d.ts:12680](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12680)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetOuter](ue_ue.LandscapeHeightfieldCollisionComponent.md#getouter)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetOverlappingActors](ue_ue.LandscapeHeightfieldCollisionComponent.md#getoverlappingactors)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetOverlappingComponents](ue_ue.LandscapeHeightfieldCollisionComponent.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:12682](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12682)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetOwner](ue_ue.LandscapeHeightfieldCollisionComponent.md#getowner)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetParentComponents](ue_ue.LandscapeHeightfieldCollisionComponent.md#getparentcomponents)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetPhysicsAngularVelocity](ue_ue.LandscapeHeightfieldCollisionComponent.md#getphysicsangularvelocity)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetPhysicsAngularVelocityInDegrees](ue_ue.LandscapeHeightfieldCollisionComponent.md#getphysicsangularvelocityindegrees)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetPhysicsAngularVelocityInRadians](ue_ue.LandscapeHeightfieldCollisionComponent.md#getphysicsangularvelocityinradians)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetPhysicsLinearVelocity](ue_ue.LandscapeHeightfieldCollisionComponent.md#getphysicslinearvelocity)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetPhysicsLinearVelocityAtPoint](ue_ue.LandscapeHeightfieldCollisionComponent.md#getphysicslinearvelocityatpoint)

#### Defined in

[ue/ue.d.ts:12687](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12687)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetPhysicsVolume](ue_ue.LandscapeHeightfieldCollisionComponent.md#getphysicsvolume)

#### Defined in

[ue/ue.d.ts:12906](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12906)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetRelativeTransform](ue_ue.LandscapeHeightfieldCollisionComponent.md#getrelativetransform)

#### Defined in

[ue/ue.d.ts:12907](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12907)

___

### GetRenderComponent

▸ **GetRenderComponent**(): [`LandscapeComponent`](ue_ue.LandscapeComponent.md)

#### Returns

[`LandscapeComponent`](ue_ue.LandscapeComponent.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetRenderComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#getrendercomponent)

#### Defined in

[ue/ue.d.ts:43889](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43889)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetRightVector](ue_ue.LandscapeHeightfieldCollisionComponent.md#getrightvector)

#### Defined in

[ue/ue.d.ts:12908](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12908)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.LandscapeHeightfieldCollisionComponent.md#getshouldupdatephysicsvolume)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetSocketLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#getsocketlocation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetSocketQuaternion](ue_ue.LandscapeHeightfieldCollisionComponent.md#getsocketquaternion)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetSocketRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#getsocketrotation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetSocketTransform](ue_ue.LandscapeHeightfieldCollisionComponent.md#getsockettransform)

#### Defined in

[ue/ue.d.ts:12913](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12913)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetUpVector](ue_ue.LandscapeHeightfieldCollisionComponent.md#getupvector)

#### Defined in

[ue/ue.d.ts:12914](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12914)

___

### GetWalkableSlopeOverride

▸ **GetWalkableSlopeOverride**(): [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Returns

[`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetWalkableSlopeOverride](ue_ue.LandscapeHeightfieldCollisionComponent.md#getwalkableslopeoverride)

#### Defined in

[ue/ue.d.ts:12688](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12688)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[GetWorld](ue_ue.LandscapeHeightfieldCollisionComponent.md#getworld)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IgnoreActorWhenMoving](ue_ue.LandscapeHeightfieldCollisionComponent.md#ignoreactorwhenmoving)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IgnoreComponentWhenMoving](ue_ue.LandscapeHeightfieldCollisionComponent.md#ignorecomponentwhenmoving)

#### Defined in

[ue/ue.d.ts:12690](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12690)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsActive](ue_ue.LandscapeHeightfieldCollisionComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L313)

___

### IsAnyRigidBodyAwake

▸ **IsAnyRigidBodyAwake**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsAnyRigidBodyAwake](ue_ue.LandscapeHeightfieldCollisionComponent.md#isanyrigidbodyawake)

#### Defined in

[ue/ue.d.ts:12691](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12691)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsAnySimulatingPhysics](ue_ue.LandscapeHeightfieldCollisionComponent.md#isanysimulatingphysics)

#### Defined in

[ue/ue.d.ts:12915](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12915)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsBeingDestroyed](ue_ue.LandscapeHeightfieldCollisionComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsComponentTickEnabled](ue_ue.LandscapeHeightfieldCollisionComponent.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L315)

___

### IsGravityEnabled

▸ **IsGravityEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsGravityEnabled](ue_ue.LandscapeHeightfieldCollisionComponent.md#isgravityenabled)

#### Defined in

[ue/ue.d.ts:12692](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12692)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsOverlappingComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#isoverlappingcomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsSimulatingPhysics](ue_ue.LandscapeHeightfieldCollisionComponent.md#issimulatingphysics)

#### Defined in

[ue/ue.d.ts:12916](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12916)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[IsVisible](ue_ue.LandscapeHeightfieldCollisionComponent.md#isvisible)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AddLocalOffset](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_addlocaloffset)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AddLocalRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_addlocalrotation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AddLocalTransform](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_addlocaltransform)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AddRelativeLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_addrelativelocation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AddRelativeRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_addrelativerotation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AddWorldOffset](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_addworldoffset)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AddWorldRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_addworldrotation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AddWorldTransform](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_addworldtransform)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AttachTo](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_attachto)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_AttachToComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_attachtocomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_BoxOverlapComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_boxoverlapcomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_DestroyComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_destroycomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_DetachFromComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_detachfromcomponent)

#### Defined in

[ue/ue.d.ts:12928](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12928)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_GetComponentLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_getcomponentlocation)

#### Defined in

[ue/ue.d.ts:12929](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12929)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_GetComponentRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_getcomponentrotation)

#### Defined in

[ue/ue.d.ts:12930](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12930)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_GetComponentScale](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_getcomponentscale)

#### Defined in

[ue/ue.d.ts:12931](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12931)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_GetComponentToWorld](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_getcomponenttoworld)

#### Defined in

[ue/ue.d.ts:12932](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12932)

___

### K2\_IsCollisionEnabled

▸ **K2_IsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_IsCollisionEnabled](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_iscollisionenabled)

#### Defined in

[ue/ue.d.ts:12696](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12696)

___

### K2\_IsPhysicsCollisionEnabled

▸ **K2_IsPhysicsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_IsPhysicsCollisionEnabled](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_isphysicscollisionenabled)

#### Defined in

[ue/ue.d.ts:12697](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12697)

___

### K2\_IsQueryCollisionEnabled

▸ **K2_IsQueryCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_IsQueryCollisionEnabled](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_isquerycollisionenabled)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_LineTraceComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_linetracecomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SetRelativeLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_setrelativelocation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_setrelativelocationandrotation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SetRelativeRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_setrelativerotation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SetRelativeTransform](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_setrelativetransform)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SetWorldLocation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_setworldlocation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_setworldlocationandrotation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SetWorldRotation](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_setworldrotation)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SetWorldTransform](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_setworldtransform)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SphereOverlapComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_sphereoverlapcomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[K2_SphereTraceComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#k2_spheretracecomponent)

#### Defined in

[ue/ue.d.ts:12701](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12701)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnRep_AttachChildren](ue_ue.LandscapeHeightfieldCollisionComponent.md#onrep_attachchildren)

#### Defined in

[ue/ue.d.ts:12941](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12941)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnRep_AttachParent](ue_ue.LandscapeHeightfieldCollisionComponent.md#onrep_attachparent)

#### Defined in

[ue/ue.d.ts:12942](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12942)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnRep_AttachSocketName](ue_ue.LandscapeHeightfieldCollisionComponent.md#onrep_attachsocketname)

#### Defined in

[ue/ue.d.ts:12943](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12943)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnRep_IsActive](ue_ue.LandscapeHeightfieldCollisionComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L317)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnRep_Transform](ue_ue.LandscapeHeightfieldCollisionComponent.md#onrep_transform)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[OnRep_Visibility](ue_ue.LandscapeHeightfieldCollisionComponent.md#onrep_visibility)

#### Defined in

[ue/ue.d.ts:12945](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12945)

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

#### Defined in

[ue/ue.d.ts:12702](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12702)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ReceiveBeginPlay](ue_ue.LandscapeHeightfieldCollisionComponent.md#receivebeginplay)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ReceiveEndPlay](ue_ue.LandscapeHeightfieldCollisionComponent.md#receiveendplay)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ReceiveTick](ue_ue.LandscapeHeightfieldCollisionComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[RegisterComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#registercomponent)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[RemoveTickPrerequisiteActor](ue_ue.LandscapeHeightfieldCollisionComponent.md#removetickprerequisiteactor)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L323)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ResetRelativeTransform](ue_ue.LandscapeHeightfieldCollisionComponent.md#resetrelativetransform)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ScaleByMomentOfInertia](ue_ue.LandscapeHeightfieldCollisionComponent.md#scalebymomentofinertia)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetAbsolute](ue_ue.LandscapeHeightfieldCollisionComponent.md#setabsolute)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetActive](ue_ue.LandscapeHeightfieldCollisionComponent.md#setactive)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetAllMassScale](ue_ue.LandscapeHeightfieldCollisionComponent.md#setallmassscale)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetAllPhysicsAngularVelocityInDegrees](ue_ue.LandscapeHeightfieldCollisionComponent.md#setallphysicsangularvelocityindegrees)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetAllPhysicsAngularVelocityInRadians](ue_ue.LandscapeHeightfieldCollisionComponent.md#setallphysicsangularvelocityinradians)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetAllPhysicsLinearVelocity](ue_ue.LandscapeHeightfieldCollisionComponent.md#setallphysicslinearvelocity)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetAllUseCCD](ue_ue.LandscapeHeightfieldCollisionComponent.md#setalluseccd)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetAngularDamping](ue_ue.LandscapeHeightfieldCollisionComponent.md#setangulardamping)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetAutoActivate](ue_ue.LandscapeHeightfieldCollisionComponent.md#setautoactivate)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetBoundsScale](ue_ue.LandscapeHeightfieldCollisionComponent.md#setboundsscale)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCastInsetShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcastinsetshadow)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCastShadow](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcastshadow)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCenterOfMass](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcenterofmass)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCollisionEnabled](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcollisionenabled)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCollisionObjectType](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcollisionobjecttype)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCollisionProfileName](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcollisionprofilename)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCollisionResponseToAllChannels](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcollisionresponsetoallchannels)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCollisionResponseToChannel](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcollisionresponsetochannel)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetComponentTickEnabled](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcomponenttickenabled)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetComponentTickInterval](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcomponenttickinterval)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetConstraintMode](ue_ue.LandscapeHeightfieldCollisionComponent.md#setconstraintmode)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCullDistance](ue_ue.LandscapeHeightfieldCollisionComponent.md#setculldistance)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCustomDepthStencilValue](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcustomdepthstencilvalue)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCustomDepthStencilWriteMask](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcustomdepthstencilwritemask)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCustomPrimitiveDataFloat](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcustomprimitivedatafloat)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCustomPrimitiveDataVector2](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcustomprimitivedatavector2)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCustomPrimitiveDataVector3](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcustomprimitivedatavector3)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetCustomPrimitiveDataVector4](ue_ue.LandscapeHeightfieldCollisionComponent.md#setcustomprimitivedatavector4)

#### Defined in

[ue/ue.d.ts:12726](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12726)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetExcludeFromLightAttachmentGroup](ue_ue.LandscapeHeightfieldCollisionComponent.md#setexcludefromlightattachmentgroup)

#### Defined in

[ue/ue.d.ts:12728](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12728)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetHiddenInGame](ue_ue.LandscapeHeightfieldCollisionComponent.md#sethiddeningame)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetIsReplicated](ue_ue.LandscapeHeightfieldCollisionComponent.md#setisreplicated)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetLightAttachmentsAsGroup](ue_ue.LandscapeHeightfieldCollisionComponent.md#setlightattachmentsasgroup)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetLinearDamping](ue_ue.LandscapeHeightfieldCollisionComponent.md#setlineardamping)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetMassOverrideInKg](ue_ue.LandscapeHeightfieldCollisionComponent.md#setmassoverrideinkg)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetMassScale](ue_ue.LandscapeHeightfieldCollisionComponent.md#setmassscale)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetMaterial](ue_ue.LandscapeHeightfieldCollisionComponent.md#setmaterial)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetMaterialByName](ue_ue.LandscapeHeightfieldCollisionComponent.md#setmaterialbyname)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetMobility](ue_ue.LandscapeHeightfieldCollisionComponent.md#setmobility)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetNotifyRigidBodyCollision](ue_ue.LandscapeHeightfieldCollisionComponent.md#setnotifyrigidbodycollision)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetOnlyOwnerSee](ue_ue.LandscapeHeightfieldCollisionComponent.md#setonlyownersee)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetOwnerNoSee](ue_ue.LandscapeHeightfieldCollisionComponent.md#setownernosee)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetPhysMaterialOverride](ue_ue.LandscapeHeightfieldCollisionComponent.md#setphysmaterialoverride)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetPhysicsAngularVelocity](ue_ue.LandscapeHeightfieldCollisionComponent.md#setphysicsangularvelocity)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetPhysicsAngularVelocityInDegrees](ue_ue.LandscapeHeightfieldCollisionComponent.md#setphysicsangularvelocityindegrees)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetPhysicsAngularVelocityInRadians](ue_ue.LandscapeHeightfieldCollisionComponent.md#setphysicsangularvelocityinradians)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetPhysicsLinearVelocity](ue_ue.LandscapeHeightfieldCollisionComponent.md#setphysicslinearvelocity)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetPhysicsMaxAngularVelocity](ue_ue.LandscapeHeightfieldCollisionComponent.md#setphysicsmaxangularvelocity)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetPhysicsMaxAngularVelocityInDegrees](ue_ue.LandscapeHeightfieldCollisionComponent.md#setphysicsmaxangularvelocityindegrees)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetPhysicsMaxAngularVelocityInRadians](ue_ue.LandscapeHeightfieldCollisionComponent.md#setphysicsmaxangularvelocityinradians)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetReceivesDecals](ue_ue.LandscapeHeightfieldCollisionComponent.md#setreceivesdecals)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetRelativeScale3D](ue_ue.LandscapeHeightfieldCollisionComponent.md#setrelativescale3d)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetRenderCustomDepth](ue_ue.LandscapeHeightfieldCollisionComponent.md#setrendercustomdepth)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetRenderInMainPass](ue_ue.LandscapeHeightfieldCollisionComponent.md#setrenderinmainpass)

#### Defined in

[ue/ue.d.ts:12749](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12749)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetSimulatePhysics](ue_ue.LandscapeHeightfieldCollisionComponent.md#setsimulatephysics)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetSingleSampleShadowFromStationaryLights](ue_ue.LandscapeHeightfieldCollisionComponent.md#setsinglesampleshadowfromstationarylights)

#### Defined in

[ue/ue.d.ts:12751](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12751)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetTickableWhenPaused](ue_ue.LandscapeHeightfieldCollisionComponent.md#settickablewhenpaused)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetTranslucentSortPriority](ue_ue.LandscapeHeightfieldCollisionComponent.md#settranslucentsortpriority)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetUseCCD](ue_ue.LandscapeHeightfieldCollisionComponent.md#setuseccd)

#### Defined in

[ue/ue.d.ts:12753](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12753)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetWalkableSlopeOverride](ue_ue.LandscapeHeightfieldCollisionComponent.md#setwalkableslopeoverride)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetWorldScale3D](ue_ue.LandscapeHeightfieldCollisionComponent.md#setworldscale3d)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SetupAttachment](ue_ue.LandscapeHeightfieldCollisionComponent.md#setupattachment)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[SnapTo](ue_ue.LandscapeHeightfieldCollisionComponent.md#snapto)

#### Defined in

[ue/ue.d.ts:12955](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12955)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ToggleActive](ue_ue.LandscapeHeightfieldCollisionComponent.md#toggleactive)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[ToggleVisibility](ue_ue.LandscapeHeightfieldCollisionComponent.md#togglevisibility)

#### Defined in

[ue/ue.d.ts:12956](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12956)

___

### WakeAllRigidBodies

▸ **WakeAllRigidBodies**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[WakeAllRigidBodies](ue_ue.LandscapeHeightfieldCollisionComponent.md#wakeallrigidbodies)

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

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[WakeRigidBody](ue_ue.LandscapeHeightfieldCollisionComponent.md#wakerigidbody)

#### Defined in

[ue/ue.d.ts:12756](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12756)

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

#### Defined in

[ue/ue.d.ts:44556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44556)

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

#### Defined in

[ue/ue.d.ts:44557](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44557)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[LandscapeHeightfieldCollisionComponent](ue_ue.LandscapeHeightfieldCollisionComponent.md).[StaticClass](ue_ue.LandscapeHeightfieldCollisionComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:44555](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44555)
