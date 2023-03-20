[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PaperTerrainSplineComponent

# Class: PaperTerrainSplineComponent

[ue/ue](../modules/ue_ue.md).PaperTerrainSplineComponent

## Hierarchy

- [`SplineComponent`](ue_ue.SplineComponent.md)

  ↳ **`PaperTerrainSplineComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.PaperTerrainSplineComponent.md#constructor)

### Properties

- [AlwaysLoadOnClient](ue_ue.PaperTerrainSplineComponent.md#alwaysloadonclient)
- [AlwaysLoadOnServer](ue_ue.PaperTerrainSplineComponent.md#alwaysloadonserver)
- [AssetUserData](ue_ue.PaperTerrainSplineComponent.md#assetuserdata)
- [AttachChildren](ue_ue.PaperTerrainSplineComponent.md#attachchildren)
- [AttachParent](ue_ue.PaperTerrainSplineComponent.md#attachparent)
- [AttachSocketName](ue_ue.PaperTerrainSplineComponent.md#attachsocketname)
- [BodyInstance](ue_ue.PaperTerrainSplineComponent.md#bodyinstance)
- [BoundsScale](ue_ue.PaperTerrainSplineComponent.md#boundsscale)
- [CachedMaxDrawDistance](ue_ue.PaperTerrainSplineComponent.md#cachedmaxdrawdistance)
- [CanBeCharacterBase](ue_ue.PaperTerrainSplineComponent.md#canbecharacterbase)
- [CanCharacterStepUpOn](ue_ue.PaperTerrainSplineComponent.md#cancharacterstepupon)
- [CastShadow](ue_ue.PaperTerrainSplineComponent.md#castshadow)
- [ClientAttachedChildren](ue_ue.PaperTerrainSplineComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.PaperTerrainSplineComponent.md#componenttags)
- [ComponentVelocity](ue_ue.PaperTerrainSplineComponent.md#componentvelocity)
- [CreationMethod](ue_ue.PaperTerrainSplineComponent.md#creationmethod)
- [CustomDepthStencilValue](ue_ue.PaperTerrainSplineComponent.md#customdepthstencilvalue)
- [CustomDepthStencilWriteMask](ue_ue.PaperTerrainSplineComponent.md#customdepthstencilwritemask)
- [CustomPrimitiveData](ue_ue.PaperTerrainSplineComponent.md#customprimitivedata)
- [DefaultUpVector](ue_ue.PaperTerrainSplineComponent.md#defaultupvector)
- [DepthPriorityGroup](ue_ue.PaperTerrainSplineComponent.md#depthprioritygroup)
- [DetailMode](ue_ue.PaperTerrainSplineComponent.md#detailmode)
- [Duration](ue_ue.PaperTerrainSplineComponent.md#duration)
- [EditorSelectedSplineSegmentColor](ue_ue.PaperTerrainSplineComponent.md#editorselectedsplinesegmentcolor)
- [EditorUnselectedSplineSegmentColor](ue_ue.PaperTerrainSplineComponent.md#editorunselectedsplinesegmentcolor)
- [ExcludeForSpecificHLODLevels](ue_ue.PaperTerrainSplineComponent.md#excludeforspecifichlodlevels)
- [IndirectLightingCacheQuality](ue_ue.PaperTerrainSplineComponent.md#indirectlightingcachequality)
- [LDMaxDrawDistance](ue_ue.PaperTerrainSplineComponent.md#ldmaxdrawdistance)
- [LODParentPrimitive](ue_ue.PaperTerrainSplineComponent.md#lodparentprimitive)
- [LightingChannels](ue_ue.PaperTerrainSplineComponent.md#lightingchannels)
- [LightmapType](ue_ue.PaperTerrainSplineComponent.md#lightmaptype)
- [LoopPosition](ue_ue.PaperTerrainSplineComponent.md#loopposition)
- [LpvBiasMultiplier](ue_ue.PaperTerrainSplineComponent.md#lpvbiasmultiplier)
- [MinDrawDistance](ue_ue.PaperTerrainSplineComponent.md#mindrawdistance)
- [Mobility](ue_ue.PaperTerrainSplineComponent.md#mobility)
- [MoveIgnoreActors](ue_ue.PaperTerrainSplineComponent.md#moveignoreactors)
- [MoveIgnoreComponents](ue_ue.PaperTerrainSplineComponent.md#moveignorecomponents)
- [OnBeginCursorOver](ue_ue.PaperTerrainSplineComponent.md#onbegincursorover)
- [OnClicked](ue_ue.PaperTerrainSplineComponent.md#onclicked)
- [OnComponentActivated](ue_ue.PaperTerrainSplineComponent.md#oncomponentactivated)
- [OnComponentBeginOverlap](ue_ue.PaperTerrainSplineComponent.md#oncomponentbeginoverlap)
- [OnComponentDeactivated](ue_ue.PaperTerrainSplineComponent.md#oncomponentdeactivated)
- [OnComponentEndOverlap](ue_ue.PaperTerrainSplineComponent.md#oncomponentendoverlap)
- [OnComponentHit](ue_ue.PaperTerrainSplineComponent.md#oncomponenthit)
- [OnComponentSleep](ue_ue.PaperTerrainSplineComponent.md#oncomponentsleep)
- [OnComponentWake](ue_ue.PaperTerrainSplineComponent.md#oncomponentwake)
- [OnEndCursorOver](ue_ue.PaperTerrainSplineComponent.md#onendcursorover)
- [OnInputTouchBegin](ue_ue.PaperTerrainSplineComponent.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.PaperTerrainSplineComponent.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.PaperTerrainSplineComponent.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.PaperTerrainSplineComponent.md#oninputtouchleave)
- [OnReleased](ue_ue.PaperTerrainSplineComponent.md#onreleased)
- [PhysicsVolume](ue_ue.PaperTerrainSplineComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.PaperTerrainSplineComponent.md#physicsvolumechangeddelegate)
- [PrimaryComponentTick](ue_ue.PaperTerrainSplineComponent.md#primarycomponenttick)
- [RelativeLocation](ue_ue.PaperTerrainSplineComponent.md#relativelocation)
- [RelativeRotation](ue_ue.PaperTerrainSplineComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.PaperTerrainSplineComponent.md#relativescale3d)
- [ReparamStepsPerSegment](ue_ue.PaperTerrainSplineComponent.md#reparamstepspersegment)
- [RuntimeVirtualTextures](ue_ue.PaperTerrainSplineComponent.md#runtimevirtualtextures)
- [ScaleVisualizationWidth](ue_ue.PaperTerrainSplineComponent.md#scalevisualizationwidth)
- [SplineCurves](ue_ue.PaperTerrainSplineComponent.md#splinecurves)
- [SplineInfo](ue_ue.PaperTerrainSplineComponent.md#splineinfo)
- [SplineReparamTable](ue_ue.PaperTerrainSplineComponent.md#splinereparamtable)
- [SplineRotInfo](ue_ue.PaperTerrainSplineComponent.md#splinerotinfo)
- [SplineScaleInfo](ue_ue.PaperTerrainSplineComponent.md#splinescaleinfo)
- [TranslucencySortPriority](ue_ue.PaperTerrainSplineComponent.md#translucencysortpriority)
- [UCSModifiedProperties](ue_ue.PaperTerrainSplineComponent.md#ucsmodifiedproperties)
- [ViewOwnerDepthPriorityGroup](ue_ue.PaperTerrainSplineComponent.md#viewownerdepthprioritygroup)
- [VirtualTextureCullMips](ue_ue.PaperTerrainSplineComponent.md#virtualtexturecullmips)
- [VirtualTextureLodBias](ue_ue.PaperTerrainSplineComponent.md#virtualtexturelodbias)
- [VirtualTextureMinCoverage](ue_ue.PaperTerrainSplineComponent.md#virtualtexturemincoverage)
- [VirtualTextureRenderPassType](ue_ue.PaperTerrainSplineComponent.md#virtualtexturerenderpasstype)
- [VisibilityId](ue_ue.PaperTerrainSplineComponent.md#visibilityid)
- [\_\_tid\_ActorComponent\_\_](ue_ue.PaperTerrainSplineComponent.md#__tid_actorcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.PaperTerrainSplineComponent.md#__tid_object__)
- [\_\_tid\_PaperTerrainSplineComponent\_\_](ue_ue.PaperTerrainSplineComponent.md#__tid_paperterrainsplinecomponent__)
- [\_\_tid\_PrimitiveComponent\_\_](ue_ue.PaperTerrainSplineComponent.md#__tid_primitivecomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.PaperTerrainSplineComponent.md#__tid_scenecomponent__)
- [\_\_tid\_SplineComponent\_\_](ue_ue.PaperTerrainSplineComponent.md#__tid_splinecomponent__)
- [bAbsoluteLocation](ue_ue.PaperTerrainSplineComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.PaperTerrainSplineComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.PaperTerrainSplineComponent.md#babsolutescale)
- [bAffectDistanceFieldLighting](ue_ue.PaperTerrainSplineComponent.md#baffectdistancefieldlighting)
- [bAffectDynamicIndirectLighting](ue_ue.PaperTerrainSplineComponent.md#baffectdynamicindirectlighting)
- [bAllowCullDistanceVolume](ue_ue.PaperTerrainSplineComponent.md#ballowculldistancevolume)
- [bAllowDiscontinuousSpline](ue_ue.PaperTerrainSplineComponent.md#ballowdiscontinuousspline)
- [bAllowSplineEditingPerInstance](ue_ue.PaperTerrainSplineComponent.md#ballowsplineeditingperinstance)
- [bAlwaysCreatePhysicsState](ue_ue.PaperTerrainSplineComponent.md#balwayscreatephysicsstate)
- [bApplyImpulseOnDamage](ue_ue.PaperTerrainSplineComponent.md#bapplyimpulseondamage)
- [bAutoActivate](ue_ue.PaperTerrainSplineComponent.md#bautoactivate)
- [bBatchImpostersAsInstances](ue_ue.PaperTerrainSplineComponent.md#bbatchimpostersasinstances)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.PaperTerrainSplineComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.PaperTerrainSplineComponent.md#bcaneveraffectnavigation)
- [bCastCinematicShadow](ue_ue.PaperTerrainSplineComponent.md#bcastcinematicshadow)
- [bCastDynamicShadow](ue_ue.PaperTerrainSplineComponent.md#bcastdynamicshadow)
- [bCastFarShadow](ue_ue.PaperTerrainSplineComponent.md#bcastfarshadow)
- [bCastHiddenShadow](ue_ue.PaperTerrainSplineComponent.md#bcasthiddenshadow)
- [bCastInsetShadow](ue_ue.PaperTerrainSplineComponent.md#bcastinsetshadow)
- [bCastShadowAsTwoSided](ue_ue.PaperTerrainSplineComponent.md#bcastshadowastwosided)
- [bCastStaticShadow](ue_ue.PaperTerrainSplineComponent.md#bcaststaticshadow)
- [bCastVolumetricTranslucentShadow](ue_ue.PaperTerrainSplineComponent.md#bcastvolumetrictranslucentshadow)
- [bClosedLoop](ue_ue.PaperTerrainSplineComponent.md#bclosedloop)
- [bComponentToWorldUpdated](ue_ue.PaperTerrainSplineComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.PaperTerrainSplineComponent.md#bcreatedbyconstructionscript)
- [bDrawDebug](ue_ue.PaperTerrainSplineComponent.md#bdrawdebug)
- [bEditableWhenInherited](ue_ue.PaperTerrainSplineComponent.md#beditablewheninherited)
- [bEnableAutoLODGeneration](ue_ue.PaperTerrainSplineComponent.md#benableautolodgeneration)
- [bExcludeFromLightAttachmentGroup](ue_ue.PaperTerrainSplineComponent.md#bexcludefromlightattachmentgroup)
- [bForceMipStreaming](ue_ue.PaperTerrainSplineComponent.md#bforcemipstreaming)
- [bGenerateOverlapEvents](ue_ue.PaperTerrainSplineComponent.md#bgenerateoverlapevents)
- [bHasCustomNavigableGeometry](ue_ue.PaperTerrainSplineComponent.md#bhascustomnavigablegeometry)
- [bHasMotionBlurVelocityMeshes](ue_ue.PaperTerrainSplineComponent.md#bhasmotionblurvelocitymeshes)
- [bHasPerInstanceHitProxies](ue_ue.PaperTerrainSplineComponent.md#bhasperinstancehitproxies)
- [bHiddenInGame](ue_ue.PaperTerrainSplineComponent.md#bhiddeningame)
- [bIgnoreRadialForce](ue_ue.PaperTerrainSplineComponent.md#bignoreradialforce)
- [bIgnoreRadialImpulse](ue_ue.PaperTerrainSplineComponent.md#bignoreradialimpulse)
- [bInputSplinePointsToConstructionScript](ue_ue.PaperTerrainSplineComponent.md#binputsplinepointstoconstructionscript)
- [bInstanceComponent](ue_ue.PaperTerrainSplineComponent.md#binstancecomponent)
- [bIsActive](ue_ue.PaperTerrainSplineComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.PaperTerrainSplineComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.PaperTerrainSplineComponent.md#bisvisualizationcomponent)
- [bLightAsIfStatic](ue_ue.PaperTerrainSplineComponent.md#blightasifstatic)
- [bLightAttachmentsAsGroup](ue_ue.PaperTerrainSplineComponent.md#blightattachmentsasgroup)
- [bLoopPositionOverride](ue_ue.PaperTerrainSplineComponent.md#blooppositionoverride)
- [bModifiedByConstructionScript](ue_ue.PaperTerrainSplineComponent.md#bmodifiedbyconstructionscript)
- [bMultiBodyOverlap](ue_ue.PaperTerrainSplineComponent.md#bmultibodyoverlap)
- [bNetAddressable](ue_ue.PaperTerrainSplineComponent.md#bnetaddressable)
- [bNeverDistanceCull](ue_ue.PaperTerrainSplineComponent.md#bneverdistancecull)
- [bOnlyOwnerSee](ue_ue.PaperTerrainSplineComponent.md#bonlyownersee)
- [bOwnerNoSee](ue_ue.PaperTerrainSplineComponent.md#bownernosee)
- [bReceiveMobileCSMShadows](ue_ue.PaperTerrainSplineComponent.md#breceivemobilecsmshadows)
- [bReceivesDecals](ue_ue.PaperTerrainSplineComponent.md#breceivesdecals)
- [bRenderCustomDepth](ue_ue.PaperTerrainSplineComponent.md#brendercustomdepth)
- [bRenderInDepthPass](ue_ue.PaperTerrainSplineComponent.md#brenderindepthpass)
- [bRenderInMainPass](ue_ue.PaperTerrainSplineComponent.md#brenderinmainpass)
- [bReplicatePhysicsToAutonomousProxy](ue_ue.PaperTerrainSplineComponent.md#breplicatephysicstoautonomousproxy)
- [bReplicates](ue_ue.PaperTerrainSplineComponent.md#breplicates)
- [bReturnMaterialOnMove](ue_ue.PaperTerrainSplineComponent.md#breturnmaterialonmove)
- [bSelectable](ue_ue.PaperTerrainSplineComponent.md#bselectable)
- [bSelfShadowOnly](ue_ue.PaperTerrainSplineComponent.md#bselfshadowonly)
- [bShouldBeAttached](ue_ue.PaperTerrainSplineComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.PaperTerrainSplineComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.PaperTerrainSplineComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.PaperTerrainSplineComponent.md#bshouldupdatephysicsvolume)
- [bShouldVisualizeScale](ue_ue.PaperTerrainSplineComponent.md#bshouldvisualizescale)
- [bSingleSampleShadowFromStationaryLights](ue_ue.PaperTerrainSplineComponent.md#bsinglesampleshadowfromstationarylights)
- [bSplineHasBeenEdited](ue_ue.PaperTerrainSplineComponent.md#bsplinehasbeenedited)
- [bStationaryEndpoints](ue_ue.PaperTerrainSplineComponent.md#bstationaryendpoints)
- [bTraceComplexOnMove](ue_ue.PaperTerrainSplineComponent.md#btracecomplexonmove)
- [bTreatAsBackgroundForOcclusion](ue_ue.PaperTerrainSplineComponent.md#btreatasbackgroundforocclusion)
- [bUseAsOccluder](ue_ue.PaperTerrainSplineComponent.md#buseasoccluder)
- [bUseAttachParentBound](ue_ue.PaperTerrainSplineComponent.md#buseattachparentbound)
- [bUseEditorCompositing](ue_ue.PaperTerrainSplineComponent.md#buseeditorcompositing)
- [bUseMaxLODAsImposter](ue_ue.PaperTerrainSplineComponent.md#busemaxlodasimposter)
- [bUseViewOwnerDepthPriorityGroup](ue_ue.PaperTerrainSplineComponent.md#buseviewownerdepthprioritygroup)
- [bVisible](ue_ue.PaperTerrainSplineComponent.md#bvisible)
- [bVisibleInRayTracing](ue_ue.PaperTerrainSplineComponent.md#bvisibleinraytracing)
- [bVisibleInReflectionCaptures](ue_ue.PaperTerrainSplineComponent.md#bvisibleinreflectioncaptures)
- [bVisualizeComponent](ue_ue.PaperTerrainSplineComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.PaperTerrainSplineComponent.md#activate)
- [AddAngularImpulse](ue_ue.PaperTerrainSplineComponent.md#addangularimpulse)
- [AddAngularImpulseInDegrees](ue_ue.PaperTerrainSplineComponent.md#addangularimpulseindegrees)
- [AddAngularImpulseInRadians](ue_ue.PaperTerrainSplineComponent.md#addangularimpulseinradians)
- [AddForce](ue_ue.PaperTerrainSplineComponent.md#addforce)
- [AddForceAtLocation](ue_ue.PaperTerrainSplineComponent.md#addforceatlocation)
- [AddForceAtLocationLocal](ue_ue.PaperTerrainSplineComponent.md#addforceatlocationlocal)
- [AddImpulse](ue_ue.PaperTerrainSplineComponent.md#addimpulse)
- [AddImpulseAtLocation](ue_ue.PaperTerrainSplineComponent.md#addimpulseatlocation)
- [AddPoint](ue_ue.PaperTerrainSplineComponent.md#addpoint)
- [AddPoints](ue_ue.PaperTerrainSplineComponent.md#addpoints)
- [AddRadialForce](ue_ue.PaperTerrainSplineComponent.md#addradialforce)
- [AddRadialImpulse](ue_ue.PaperTerrainSplineComponent.md#addradialimpulse)
- [AddSplineLocalPoint](ue_ue.PaperTerrainSplineComponent.md#addsplinelocalpoint)
- [AddSplinePoint](ue_ue.PaperTerrainSplineComponent.md#addsplinepoint)
- [AddSplinePointAtIndex](ue_ue.PaperTerrainSplineComponent.md#addsplinepointatindex)
- [AddSplineWorldPoint](ue_ue.PaperTerrainSplineComponent.md#addsplineworldpoint)
- [AddTickPrerequisiteActor](ue_ue.PaperTerrainSplineComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PaperTerrainSplineComponent.md#addtickprerequisitecomponent)
- [AddTorque](ue_ue.PaperTerrainSplineComponent.md#addtorque)
- [AddTorqueInDegrees](ue_ue.PaperTerrainSplineComponent.md#addtorqueindegrees)
- [AddTorqueInRadians](ue_ue.PaperTerrainSplineComponent.md#addtorqueinradians)
- [CanCharacterStepUp](ue_ue.PaperTerrainSplineComponent.md#cancharacterstepup)
- [ClearMoveIgnoreActors](ue_ue.PaperTerrainSplineComponent.md#clearmoveignoreactors)
- [ClearMoveIgnoreComponents](ue_ue.PaperTerrainSplineComponent.md#clearmoveignorecomponents)
- [ClearSplinePoints](ue_ue.PaperTerrainSplineComponent.md#clearsplinepoints)
- [ComponentHasTag](ue_ue.PaperTerrainSplineComponent.md#componenthastag)
- [CopyArrayOfMoveIgnoreActors](ue_ue.PaperTerrainSplineComponent.md#copyarrayofmoveignoreactors)
- [CopyArrayOfMoveIgnoreComponents](ue_ue.PaperTerrainSplineComponent.md#copyarrayofmoveignorecomponents)
- [CreateAndSetMaterialInstanceDynamic](ue_ue.PaperTerrainSplineComponent.md#createandsetmaterialinstancedynamic)
- [CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.PaperTerrainSplineComponent.md#createandsetmaterialinstancedynamicfrommaterial)
- [CreateDefaultSubobject](ue_ue.PaperTerrainSplineComponent.md#createdefaultsubobject)
- [CreateDynamicMaterialInstance](ue_ue.PaperTerrainSplineComponent.md#createdynamicmaterialinstance)
- [Deactivate](ue_ue.PaperTerrainSplineComponent.md#deactivate)
- [DetachFromParent](ue_ue.PaperTerrainSplineComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.PaperTerrainSplineComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.PaperTerrainSplineComponent.md#executeubergraph)
- [FindDirectionClosestToWorldLocation](ue_ue.PaperTerrainSplineComponent.md#finddirectionclosesttoworldlocation)
- [FindInputKeyClosestToWorldLocation](ue_ue.PaperTerrainSplineComponent.md#findinputkeyclosesttoworldlocation)
- [FindLocationClosestToWorldLocation](ue_ue.PaperTerrainSplineComponent.md#findlocationclosesttoworldlocation)
- [FindRightVectorClosestToWorldLocation](ue_ue.PaperTerrainSplineComponent.md#findrightvectorclosesttoworldlocation)
- [FindRollClosestToWorldLocation](ue_ue.PaperTerrainSplineComponent.md#findrollclosesttoworldlocation)
- [FindRotationClosestToWorldLocation](ue_ue.PaperTerrainSplineComponent.md#findrotationclosesttoworldlocation)
- [FindScaleClosestToWorldLocation](ue_ue.PaperTerrainSplineComponent.md#findscaleclosesttoworldlocation)
- [FindTangentClosestToWorldLocation](ue_ue.PaperTerrainSplineComponent.md#findtangentclosesttoworldlocation)
- [FindTransformClosestToWorldLocation](ue_ue.PaperTerrainSplineComponent.md#findtransformclosesttoworldlocation)
- [FindUpVectorClosestToWorldLocation](ue_ue.PaperTerrainSplineComponent.md#findupvectorclosesttoworldlocation)
- [GetAllSocketNames](ue_ue.PaperTerrainSplineComponent.md#getallsocketnames)
- [GetAngularDamping](ue_ue.PaperTerrainSplineComponent.md#getangulardamping)
- [GetArriveTangentAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#getarrivetangentatsplinepoint)
- [GetAttachParent](ue_ue.PaperTerrainSplineComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.PaperTerrainSplineComponent.md#getattachsocketname)
- [GetCenterOfMass](ue_ue.PaperTerrainSplineComponent.md#getcenterofmass)
- [GetChildComponent](ue_ue.PaperTerrainSplineComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.PaperTerrainSplineComponent.md#getchildrencomponents)
- [GetClass](ue_ue.PaperTerrainSplineComponent.md#getclass)
- [GetClosestPointOnCollision](ue_ue.PaperTerrainSplineComponent.md#getclosestpointoncollision)
- [GetCollisionEnabled](ue_ue.PaperTerrainSplineComponent.md#getcollisionenabled)
- [GetCollisionObjectType](ue_ue.PaperTerrainSplineComponent.md#getcollisionobjecttype)
- [GetCollisionProfileName](ue_ue.PaperTerrainSplineComponent.md#getcollisionprofilename)
- [GetCollisionResponseToChannel](ue_ue.PaperTerrainSplineComponent.md#getcollisionresponsetochannel)
- [GetComponentTickInterval](ue_ue.PaperTerrainSplineComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.PaperTerrainSplineComponent.md#getcomponentvelocity)
- [GetDefaultUpVector](ue_ue.PaperTerrainSplineComponent.md#getdefaultupvector)
- [GetDirectionAtDistanceAlongSpline](ue_ue.PaperTerrainSplineComponent.md#getdirectionatdistancealongspline)
- [GetDirectionAtSplineInputKey](ue_ue.PaperTerrainSplineComponent.md#getdirectionatsplineinputkey)
- [GetDirectionAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#getdirectionatsplinepoint)
- [GetDirectionAtTime](ue_ue.PaperTerrainSplineComponent.md#getdirectionattime)
- [GetDistanceAlongSplineAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#getdistancealongsplineatsplinepoint)
- [GetFloatPropertyAtSplineInputKey](ue_ue.PaperTerrainSplineComponent.md#getfloatpropertyatsplineinputkey)
- [GetFloatPropertyAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#getfloatpropertyatsplinepoint)
- [GetForwardVector](ue_ue.PaperTerrainSplineComponent.md#getforwardvector)
- [GetGenerateOverlapEvents](ue_ue.PaperTerrainSplineComponent.md#getgenerateoverlapevents)
- [GetInertiaTensor](ue_ue.PaperTerrainSplineComponent.md#getinertiatensor)
- [GetInputKeyAtDistanceAlongSpline](ue_ue.PaperTerrainSplineComponent.md#getinputkeyatdistancealongspline)
- [GetLeaveTangentAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#getleavetangentatsplinepoint)
- [GetLinearDamping](ue_ue.PaperTerrainSplineComponent.md#getlineardamping)
- [GetLocalLocationAndTangentAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#getlocallocationandtangentatsplinepoint)
- [GetLocationAndTangentAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#getlocationandtangentatsplinepoint)
- [GetLocationAtDistanceAlongSpline](ue_ue.PaperTerrainSplineComponent.md#getlocationatdistancealongspline)
- [GetLocationAtSplineInputKey](ue_ue.PaperTerrainSplineComponent.md#getlocationatsplineinputkey)
- [GetLocationAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#getlocationatsplinepoint)
- [GetLocationAtTime](ue_ue.PaperTerrainSplineComponent.md#getlocationattime)
- [GetMass](ue_ue.PaperTerrainSplineComponent.md#getmass)
- [GetMassScale](ue_ue.PaperTerrainSplineComponent.md#getmassscale)
- [GetMaterial](ue_ue.PaperTerrainSplineComponent.md#getmaterial)
- [GetMaterialFromCollisionFaceIndex](ue_ue.PaperTerrainSplineComponent.md#getmaterialfromcollisionfaceindex)
- [GetName](ue_ue.PaperTerrainSplineComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.PaperTerrainSplineComponent.md#getnumchildrencomponents)
- [GetNumMaterials](ue_ue.PaperTerrainSplineComponent.md#getnummaterials)
- [GetNumberOfSplinePoints](ue_ue.PaperTerrainSplineComponent.md#getnumberofsplinepoints)
- [GetNumberOfSplineSegments](ue_ue.PaperTerrainSplineComponent.md#getnumberofsplinesegments)
- [GetOuter](ue_ue.PaperTerrainSplineComponent.md#getouter)
- [GetOverlappingActors](ue_ue.PaperTerrainSplineComponent.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.PaperTerrainSplineComponent.md#getoverlappingcomponents)
- [GetOwner](ue_ue.PaperTerrainSplineComponent.md#getowner)
- [GetParentComponents](ue_ue.PaperTerrainSplineComponent.md#getparentcomponents)
- [GetPhysicsAngularVelocity](ue_ue.PaperTerrainSplineComponent.md#getphysicsangularvelocity)
- [GetPhysicsAngularVelocityInDegrees](ue_ue.PaperTerrainSplineComponent.md#getphysicsangularvelocityindegrees)
- [GetPhysicsAngularVelocityInRadians](ue_ue.PaperTerrainSplineComponent.md#getphysicsangularvelocityinradians)
- [GetPhysicsLinearVelocity](ue_ue.PaperTerrainSplineComponent.md#getphysicslinearvelocity)
- [GetPhysicsLinearVelocityAtPoint](ue_ue.PaperTerrainSplineComponent.md#getphysicslinearvelocityatpoint)
- [GetPhysicsVolume](ue_ue.PaperTerrainSplineComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.PaperTerrainSplineComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.PaperTerrainSplineComponent.md#getrightvector)
- [GetRightVectorAtDistanceAlongSpline](ue_ue.PaperTerrainSplineComponent.md#getrightvectoratdistancealongspline)
- [GetRightVectorAtSplineInputKey](ue_ue.PaperTerrainSplineComponent.md#getrightvectoratsplineinputkey)
- [GetRightVectorAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#getrightvectoratsplinepoint)
- [GetRightVectorAtTime](ue_ue.PaperTerrainSplineComponent.md#getrightvectorattime)
- [GetRollAtDistanceAlongSpline](ue_ue.PaperTerrainSplineComponent.md#getrollatdistancealongspline)
- [GetRollAtSplineInputKey](ue_ue.PaperTerrainSplineComponent.md#getrollatsplineinputkey)
- [GetRollAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#getrollatsplinepoint)
- [GetRollAtTime](ue_ue.PaperTerrainSplineComponent.md#getrollattime)
- [GetRotationAtDistanceAlongSpline](ue_ue.PaperTerrainSplineComponent.md#getrotationatdistancealongspline)
- [GetRotationAtSplineInputKey](ue_ue.PaperTerrainSplineComponent.md#getrotationatsplineinputkey)
- [GetRotationAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#getrotationatsplinepoint)
- [GetRotationAtTime](ue_ue.PaperTerrainSplineComponent.md#getrotationattime)
- [GetScaleAtDistanceAlongSpline](ue_ue.PaperTerrainSplineComponent.md#getscaleatdistancealongspline)
- [GetScaleAtSplineInputKey](ue_ue.PaperTerrainSplineComponent.md#getscaleatsplineinputkey)
- [GetScaleAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#getscaleatsplinepoint)
- [GetScaleAtTime](ue_ue.PaperTerrainSplineComponent.md#getscaleattime)
- [GetShouldUpdatePhysicsVolume](ue_ue.PaperTerrainSplineComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.PaperTerrainSplineComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.PaperTerrainSplineComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.PaperTerrainSplineComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.PaperTerrainSplineComponent.md#getsockettransform)
- [GetSplineLength](ue_ue.PaperTerrainSplineComponent.md#getsplinelength)
- [GetSplinePointType](ue_ue.PaperTerrainSplineComponent.md#getsplinepointtype)
- [GetTangentAtDistanceAlongSpline](ue_ue.PaperTerrainSplineComponent.md#gettangentatdistancealongspline)
- [GetTangentAtSplineInputKey](ue_ue.PaperTerrainSplineComponent.md#gettangentatsplineinputkey)
- [GetTangentAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#gettangentatsplinepoint)
- [GetTangentAtTime](ue_ue.PaperTerrainSplineComponent.md#gettangentattime)
- [GetTransformAtDistanceAlongSpline](ue_ue.PaperTerrainSplineComponent.md#gettransformatdistancealongspline)
- [GetTransformAtSplineInputKey](ue_ue.PaperTerrainSplineComponent.md#gettransformatsplineinputkey)
- [GetTransformAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#gettransformatsplinepoint)
- [GetTransformAtTime](ue_ue.PaperTerrainSplineComponent.md#gettransformattime)
- [GetUpVector](ue_ue.PaperTerrainSplineComponent.md#getupvector)
- [GetUpVectorAtDistanceAlongSpline](ue_ue.PaperTerrainSplineComponent.md#getupvectoratdistancealongspline)
- [GetUpVectorAtSplineInputKey](ue_ue.PaperTerrainSplineComponent.md#getupvectoratsplineinputkey)
- [GetUpVectorAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#getupvectoratsplinepoint)
- [GetUpVectorAtTime](ue_ue.PaperTerrainSplineComponent.md#getupvectorattime)
- [GetVectorPropertyAtSplineInputKey](ue_ue.PaperTerrainSplineComponent.md#getvectorpropertyatsplineinputkey)
- [GetVectorPropertyAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#getvectorpropertyatsplinepoint)
- [GetWalkableSlopeOverride](ue_ue.PaperTerrainSplineComponent.md#getwalkableslopeoverride)
- [GetWorld](ue_ue.PaperTerrainSplineComponent.md#getworld)
- [GetWorldDirectionAtDistanceAlongSpline](ue_ue.PaperTerrainSplineComponent.md#getworlddirectionatdistancealongspline)
- [GetWorldDirectionAtTime](ue_ue.PaperTerrainSplineComponent.md#getworlddirectionattime)
- [GetWorldLocationAtDistanceAlongSpline](ue_ue.PaperTerrainSplineComponent.md#getworldlocationatdistancealongspline)
- [GetWorldLocationAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#getworldlocationatsplinepoint)
- [GetWorldLocationAtTime](ue_ue.PaperTerrainSplineComponent.md#getworldlocationattime)
- [GetWorldRotationAtDistanceAlongSpline](ue_ue.PaperTerrainSplineComponent.md#getworldrotationatdistancealongspline)
- [GetWorldRotationAtTime](ue_ue.PaperTerrainSplineComponent.md#getworldrotationattime)
- [GetWorldTangentAtDistanceAlongSpline](ue_ue.PaperTerrainSplineComponent.md#getworldtangentatdistancealongspline)
- [IgnoreActorWhenMoving](ue_ue.PaperTerrainSplineComponent.md#ignoreactorwhenmoving)
- [IgnoreComponentWhenMoving](ue_ue.PaperTerrainSplineComponent.md#ignorecomponentwhenmoving)
- [IsActive](ue_ue.PaperTerrainSplineComponent.md#isactive)
- [IsAnyRigidBodyAwake](ue_ue.PaperTerrainSplineComponent.md#isanyrigidbodyawake)
- [IsAnySimulatingPhysics](ue_ue.PaperTerrainSplineComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.PaperTerrainSplineComponent.md#isbeingdestroyed)
- [IsClosedLoop](ue_ue.PaperTerrainSplineComponent.md#isclosedloop)
- [IsComponentTickEnabled](ue_ue.PaperTerrainSplineComponent.md#iscomponenttickenabled)
- [IsGravityEnabled](ue_ue.PaperTerrainSplineComponent.md#isgravityenabled)
- [IsOverlappingActor](ue_ue.PaperTerrainSplineComponent.md#isoverlappingactor)
- [IsOverlappingComponent](ue_ue.PaperTerrainSplineComponent.md#isoverlappingcomponent)
- [IsSimulatingPhysics](ue_ue.PaperTerrainSplineComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.PaperTerrainSplineComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.PaperTerrainSplineComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.PaperTerrainSplineComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.PaperTerrainSplineComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.PaperTerrainSplineComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.PaperTerrainSplineComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.PaperTerrainSplineComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.PaperTerrainSplineComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.PaperTerrainSplineComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.PaperTerrainSplineComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.PaperTerrainSplineComponent.md#k2_attachtocomponent)
- [K2\_BoxOverlapComponent](ue_ue.PaperTerrainSplineComponent.md#k2_boxoverlapcomponent)
- [K2\_DestroyComponent](ue_ue.PaperTerrainSplineComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.PaperTerrainSplineComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.PaperTerrainSplineComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.PaperTerrainSplineComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.PaperTerrainSplineComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.PaperTerrainSplineComponent.md#k2_getcomponenttoworld)
- [K2\_IsCollisionEnabled](ue_ue.PaperTerrainSplineComponent.md#k2_iscollisionenabled)
- [K2\_IsPhysicsCollisionEnabled](ue_ue.PaperTerrainSplineComponent.md#k2_isphysicscollisionenabled)
- [K2\_IsQueryCollisionEnabled](ue_ue.PaperTerrainSplineComponent.md#k2_isquerycollisionenabled)
- [K2\_LineTraceComponent](ue_ue.PaperTerrainSplineComponent.md#k2_linetracecomponent)
- [K2\_SetRelativeLocation](ue_ue.PaperTerrainSplineComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.PaperTerrainSplineComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.PaperTerrainSplineComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.PaperTerrainSplineComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.PaperTerrainSplineComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.PaperTerrainSplineComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.PaperTerrainSplineComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.PaperTerrainSplineComponent.md#k2_setworldtransform)
- [K2\_SphereOverlapComponent](ue_ue.PaperTerrainSplineComponent.md#k2_sphereoverlapcomponent)
- [K2\_SphereTraceComponent](ue_ue.PaperTerrainSplineComponent.md#k2_spheretracecomponent)
- [OnRep\_AttachChildren](ue_ue.PaperTerrainSplineComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.PaperTerrainSplineComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.PaperTerrainSplineComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.PaperTerrainSplineComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.PaperTerrainSplineComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.PaperTerrainSplineComponent.md#onrep_visibility)
- [PutRigidBodyToSleep](ue_ue.PaperTerrainSplineComponent.md#putrigidbodytosleep)
- [ReceiveBeginPlay](ue_ue.PaperTerrainSplineComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.PaperTerrainSplineComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.PaperTerrainSplineComponent.md#receivetick)
- [RegisterComponent](ue_ue.PaperTerrainSplineComponent.md#registercomponent)
- [RemoveSplinePoint](ue_ue.PaperTerrainSplineComponent.md#removesplinepoint)
- [RemoveTickPrerequisiteActor](ue_ue.PaperTerrainSplineComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PaperTerrainSplineComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.PaperTerrainSplineComponent.md#resetrelativetransform)
- [ScaleByMomentOfInertia](ue_ue.PaperTerrainSplineComponent.md#scalebymomentofinertia)
- [SetAbsolute](ue_ue.PaperTerrainSplineComponent.md#setabsolute)
- [SetActive](ue_ue.PaperTerrainSplineComponent.md#setactive)
- [SetAllMassScale](ue_ue.PaperTerrainSplineComponent.md#setallmassscale)
- [SetAllPhysicsAngularVelocityInDegrees](ue_ue.PaperTerrainSplineComponent.md#setallphysicsangularvelocityindegrees)
- [SetAllPhysicsAngularVelocityInRadians](ue_ue.PaperTerrainSplineComponent.md#setallphysicsangularvelocityinradians)
- [SetAllPhysicsLinearVelocity](ue_ue.PaperTerrainSplineComponent.md#setallphysicslinearvelocity)
- [SetAllUseCCD](ue_ue.PaperTerrainSplineComponent.md#setalluseccd)
- [SetAngularDamping](ue_ue.PaperTerrainSplineComponent.md#setangulardamping)
- [SetAutoActivate](ue_ue.PaperTerrainSplineComponent.md#setautoactivate)
- [SetBoundsScale](ue_ue.PaperTerrainSplineComponent.md#setboundsscale)
- [SetCastInsetShadow](ue_ue.PaperTerrainSplineComponent.md#setcastinsetshadow)
- [SetCastShadow](ue_ue.PaperTerrainSplineComponent.md#setcastshadow)
- [SetCenterOfMass](ue_ue.PaperTerrainSplineComponent.md#setcenterofmass)
- [SetClosedLoop](ue_ue.PaperTerrainSplineComponent.md#setclosedloop)
- [SetClosedLoopAtPosition](ue_ue.PaperTerrainSplineComponent.md#setclosedloopatposition)
- [SetCollisionEnabled](ue_ue.PaperTerrainSplineComponent.md#setcollisionenabled)
- [SetCollisionObjectType](ue_ue.PaperTerrainSplineComponent.md#setcollisionobjecttype)
- [SetCollisionProfileName](ue_ue.PaperTerrainSplineComponent.md#setcollisionprofilename)
- [SetCollisionResponseToAllChannels](ue_ue.PaperTerrainSplineComponent.md#setcollisionresponsetoallchannels)
- [SetCollisionResponseToChannel](ue_ue.PaperTerrainSplineComponent.md#setcollisionresponsetochannel)
- [SetComponentTickEnabled](ue_ue.PaperTerrainSplineComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.PaperTerrainSplineComponent.md#setcomponenttickinterval)
- [SetConstraintMode](ue_ue.PaperTerrainSplineComponent.md#setconstraintmode)
- [SetCullDistance](ue_ue.PaperTerrainSplineComponent.md#setculldistance)
- [SetCustomDepthStencilValue](ue_ue.PaperTerrainSplineComponent.md#setcustomdepthstencilvalue)
- [SetCustomDepthStencilWriteMask](ue_ue.PaperTerrainSplineComponent.md#setcustomdepthstencilwritemask)
- [SetCustomPrimitiveDataFloat](ue_ue.PaperTerrainSplineComponent.md#setcustomprimitivedatafloat)
- [SetCustomPrimitiveDataVector2](ue_ue.PaperTerrainSplineComponent.md#setcustomprimitivedatavector2)
- [SetCustomPrimitiveDataVector3](ue_ue.PaperTerrainSplineComponent.md#setcustomprimitivedatavector3)
- [SetCustomPrimitiveDataVector4](ue_ue.PaperTerrainSplineComponent.md#setcustomprimitivedatavector4)
- [SetDefaultUpVector](ue_ue.PaperTerrainSplineComponent.md#setdefaultupvector)
- [SetDrawDebug](ue_ue.PaperTerrainSplineComponent.md#setdrawdebug)
- [SetEnableGravity](ue_ue.PaperTerrainSplineComponent.md#setenablegravity)
- [SetExcludeFromLightAttachmentGroup](ue_ue.PaperTerrainSplineComponent.md#setexcludefromlightattachmentgroup)
- [SetGenerateOverlapEvents](ue_ue.PaperTerrainSplineComponent.md#setgenerateoverlapevents)
- [SetHiddenInGame](ue_ue.PaperTerrainSplineComponent.md#sethiddeningame)
- [SetIsReplicated](ue_ue.PaperTerrainSplineComponent.md#setisreplicated)
- [SetLightAttachmentsAsGroup](ue_ue.PaperTerrainSplineComponent.md#setlightattachmentsasgroup)
- [SetLinearDamping](ue_ue.PaperTerrainSplineComponent.md#setlineardamping)
- [SetLocationAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#setlocationatsplinepoint)
- [SetMassOverrideInKg](ue_ue.PaperTerrainSplineComponent.md#setmassoverrideinkg)
- [SetMassScale](ue_ue.PaperTerrainSplineComponent.md#setmassscale)
- [SetMaterial](ue_ue.PaperTerrainSplineComponent.md#setmaterial)
- [SetMaterialByName](ue_ue.PaperTerrainSplineComponent.md#setmaterialbyname)
- [SetMobility](ue_ue.PaperTerrainSplineComponent.md#setmobility)
- [SetNotifyRigidBodyCollision](ue_ue.PaperTerrainSplineComponent.md#setnotifyrigidbodycollision)
- [SetOnlyOwnerSee](ue_ue.PaperTerrainSplineComponent.md#setonlyownersee)
- [SetOwnerNoSee](ue_ue.PaperTerrainSplineComponent.md#setownernosee)
- [SetPhysMaterialOverride](ue_ue.PaperTerrainSplineComponent.md#setphysmaterialoverride)
- [SetPhysicsAngularVelocity](ue_ue.PaperTerrainSplineComponent.md#setphysicsangularvelocity)
- [SetPhysicsAngularVelocityInDegrees](ue_ue.PaperTerrainSplineComponent.md#setphysicsangularvelocityindegrees)
- [SetPhysicsAngularVelocityInRadians](ue_ue.PaperTerrainSplineComponent.md#setphysicsangularvelocityinradians)
- [SetPhysicsLinearVelocity](ue_ue.PaperTerrainSplineComponent.md#setphysicslinearvelocity)
- [SetPhysicsMaxAngularVelocity](ue_ue.PaperTerrainSplineComponent.md#setphysicsmaxangularvelocity)
- [SetPhysicsMaxAngularVelocityInDegrees](ue_ue.PaperTerrainSplineComponent.md#setphysicsmaxangularvelocityindegrees)
- [SetPhysicsMaxAngularVelocityInRadians](ue_ue.PaperTerrainSplineComponent.md#setphysicsmaxangularvelocityinradians)
- [SetReceivesDecals](ue_ue.PaperTerrainSplineComponent.md#setreceivesdecals)
- [SetRelativeScale3D](ue_ue.PaperTerrainSplineComponent.md#setrelativescale3d)
- [SetRenderCustomDepth](ue_ue.PaperTerrainSplineComponent.md#setrendercustomdepth)
- [SetRenderInMainPass](ue_ue.PaperTerrainSplineComponent.md#setrenderinmainpass)
- [SetSelectedSplineSegmentColor](ue_ue.PaperTerrainSplineComponent.md#setselectedsplinesegmentcolor)
- [SetShouldUpdatePhysicsVolume](ue_ue.PaperTerrainSplineComponent.md#setshouldupdatephysicsvolume)
- [SetSimulatePhysics](ue_ue.PaperTerrainSplineComponent.md#setsimulatephysics)
- [SetSingleSampleShadowFromStationaryLights](ue_ue.PaperTerrainSplineComponent.md#setsinglesampleshadowfromstationarylights)
- [SetSplineLocalPoints](ue_ue.PaperTerrainSplineComponent.md#setsplinelocalpoints)
- [SetSplinePointType](ue_ue.PaperTerrainSplineComponent.md#setsplinepointtype)
- [SetSplinePoints](ue_ue.PaperTerrainSplineComponent.md#setsplinepoints)
- [SetSplineWorldPoints](ue_ue.PaperTerrainSplineComponent.md#setsplineworldpoints)
- [SetTangentAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#settangentatsplinepoint)
- [SetTangentsAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#settangentsatsplinepoint)
- [SetTickGroup](ue_ue.PaperTerrainSplineComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PaperTerrainSplineComponent.md#settickablewhenpaused)
- [SetTranslucentSortPriority](ue_ue.PaperTerrainSplineComponent.md#settranslucentsortpriority)
- [SetUnselectedSplineSegmentColor](ue_ue.PaperTerrainSplineComponent.md#setunselectedsplinesegmentcolor)
- [SetUpVectorAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#setupvectoratsplinepoint)
- [SetUseCCD](ue_ue.PaperTerrainSplineComponent.md#setuseccd)
- [SetVisibility](ue_ue.PaperTerrainSplineComponent.md#setvisibility)
- [SetWalkableSlopeOverride](ue_ue.PaperTerrainSplineComponent.md#setwalkableslopeoverride)
- [SetWorldLocationAtSplinePoint](ue_ue.PaperTerrainSplineComponent.md#setworldlocationatsplinepoint)
- [SetWorldScale3D](ue_ue.PaperTerrainSplineComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.PaperTerrainSplineComponent.md#setupattachment)
- [SnapTo](ue_ue.PaperTerrainSplineComponent.md#snapto)
- [ToggleActive](ue_ue.PaperTerrainSplineComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.PaperTerrainSplineComponent.md#togglevisibility)
- [UpdateSpline](ue_ue.PaperTerrainSplineComponent.md#updatespline)
- [WakeAllRigidBodies](ue_ue.PaperTerrainSplineComponent.md#wakeallrigidbodies)
- [WakeRigidBody](ue_ue.PaperTerrainSplineComponent.md#wakerigidbody)
- [Find](ue_ue.PaperTerrainSplineComponent.md#find)
- [Load](ue_ue.PaperTerrainSplineComponent.md#load)
- [StaticClass](ue_ue.PaperTerrainSplineComponent.md#staticclass)

## Constructors

### constructor

• **new PaperTerrainSplineComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SplineComponent](ue_ue.SplineComponent.md).[constructor](ue_ue.SplineComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:54924](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54924)

## Properties

### AlwaysLoadOnClient

• **AlwaysLoadOnClient**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AlwaysLoadOnClient](ue_ue.SplineComponent.md#alwaysloadonclient)

#### Defined in

[ue/ue.d.ts:12608](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12608)

___

### AlwaysLoadOnServer

• **AlwaysLoadOnServer**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AlwaysLoadOnServer](ue_ue.SplineComponent.md#alwaysloadonserver)

#### Defined in

[ue/ue.d.ts:12609](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12609)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AssetUserData](ue_ue.SplineComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L291)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AttachChildren](ue_ue.SplineComponent.md#attachchildren)

#### Defined in

[ue/ue.d.ts:12873](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12873)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AttachParent](ue_ue.SplineComponent.md#attachparent)

#### Defined in

[ue/ue.d.ts:12871](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12871)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AttachSocketName](ue_ue.SplineComponent.md#attachsocketname)

#### Defined in

[ue/ue.d.ts:12872](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12872)

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[BodyInstance](ue_ue.SplineComponent.md#bodyinstance)

#### Defined in

[ue/ue.d.ts:12630](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12630)

___

### BoundsScale

• **BoundsScale**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[BoundsScale](ue_ue.SplineComponent.md#boundsscale)

#### Defined in

[ue/ue.d.ts:12627](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12627)

___

### CachedMaxDrawDistance

• **CachedMaxDrawDistance**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CachedMaxDrawDistance](ue_ue.SplineComponent.md#cachedmaxdrawdistance)

#### Defined in

[ue/ue.d.ts:12557](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12557)

___

### CanBeCharacterBase

• **CanBeCharacterBase**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CanBeCharacterBase](ue_ue.SplineComponent.md#canbecharacterbase)

#### Defined in

[ue/ue.d.ts:12613](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12613)

___

### CanCharacterStepUpOn

• **CanCharacterStepUpOn**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CanCharacterStepUpOn](ue_ue.SplineComponent.md#cancharacterstepupon)

#### Defined in

[ue/ue.d.ts:12614](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12614)

___

### CastShadow

• **CastShadow**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CastShadow](ue_ue.SplineComponent.md#castshadow)

#### Defined in

[ue/ue.d.ts:12587](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12587)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ClientAttachedChildren](ue_ue.SplineComponent.md#clientattachedchildren)

#### Defined in

[ue/ue.d.ts:12874](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12874)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ComponentTags](ue_ue.SplineComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L290)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ComponentVelocity](ue_ue.SplineComponent.md#componentvelocity)

#### Defined in

[ue/ue.d.ts:12878](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12878)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CreationMethod](ue_ue.SplineComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L302)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CustomDepthStencilValue](ue_ue.SplineComponent.md#customdepthstencilvalue)

#### Defined in

[ue/ue.d.ts:12617](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12617)

___

### CustomDepthStencilWriteMask

• **CustomDepthStencilWriteMask**: [`ERendererStencilMask`](../enums/ue_ue.ERendererStencilMask.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CustomDepthStencilWriteMask](ue_ue.SplineComponent.md#customdepthstencilwritemask)

#### Defined in

[ue/ue.d.ts:12616](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12616)

___

### CustomPrimitiveData

• **CustomPrimitiveData**: [`CustomPrimitiveData`](ue_ue.CustomPrimitiveData.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CustomPrimitiveData](ue_ue.SplineComponent.md#customprimitivedata)

#### Defined in

[ue/ue.d.ts:12618](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12618)

___

### DefaultUpVector

• **DefaultUpVector**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[DefaultUpVector](ue_ue.SplineComponent.md#defaultupvector)

#### Defined in

[ue/ue.d.ts:25930](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25930)

___

### DepthPriorityGroup

• **DepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[DepthPriorityGroup](ue_ue.SplineComponent.md#depthprioritygroup)

#### Defined in

[ue/ue.d.ts:12558](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12558)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[DetailMode](ue_ue.SplineComponent.md#detailmode)

#### Defined in

[ue/ue.d.ts:12893](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12893)

___

### Duration

• **Duration**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[Duration](ue_ue.SplineComponent.md#duration)

#### Defined in

[ue/ue.d.ts:25921](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25921)

___

### EditorSelectedSplineSegmentColor

• **EditorSelectedSplineSegmentColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[EditorSelectedSplineSegmentColor](ue_ue.SplineComponent.md#editorselectedsplinesegmentcolor)

#### Defined in

[ue/ue.d.ts:25932](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25932)

___

### EditorUnselectedSplineSegmentColor

• **EditorUnselectedSplineSegmentColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[EditorUnselectedSplineSegmentColor](ue_ue.SplineComponent.md#editorunselectedsplinesegmentcolor)

#### Defined in

[ue/ue.d.ts:25931](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25931)

___

### ExcludeForSpecificHLODLevels

• **ExcludeForSpecificHLODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ExcludeForSpecificHLODLevels](ue_ue.SplineComponent.md#excludeforspecifichlodlevels)

#### Defined in

[ue/ue.d.ts:12562](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12562)

___

### IndirectLightingCacheQuality

• **IndirectLightingCacheQuality**: [`EIndirectLightingCacheQuality`](../enums/ue_ue.EIndirectLightingCacheQuality.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IndirectLightingCacheQuality](ue_ue.SplineComponent.md#indirectlightingcachequality)

#### Defined in

[ue/ue.d.ts:12560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12560)

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[LDMaxDrawDistance](ue_ue.SplineComponent.md#ldmaxdrawdistance)

#### Defined in

[ue/ue.d.ts:12556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12556)

___

### LODParentPrimitive

• **LODParentPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[LODParentPrimitive](ue_ue.SplineComponent.md#lodparentprimitive)

#### Defined in

[ue/ue.d.ts:12644](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12644)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[LightingChannels](ue_ue.SplineComponent.md#lightingchannels)

#### Defined in

[ue/ue.d.ts:12615](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12615)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[LightmapType](ue_ue.SplineComponent.md#lightmaptype)

#### Defined in

[ue/ue.d.ts:12561](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12561)

___

### LoopPosition

• **LoopPosition**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[LoopPosition](ue_ue.SplineComponent.md#loopposition)

#### Defined in

[ue/ue.d.ts:25929](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25929)

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[LpvBiasMultiplier](ue_ue.SplineComponent.md#lpvbiasmultiplier)

#### Defined in

[ue/ue.d.ts:12626](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12626)

___

### MinDrawDistance

• **MinDrawDistance**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[MinDrawDistance](ue_ue.SplineComponent.md#mindrawdistance)

#### Defined in

[ue/ue.d.ts:12555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12555)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[Mobility](ue_ue.SplineComponent.md#mobility)

#### Defined in

[ue/ue.d.ts:12892](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12892)

___

### MoveIgnoreActors

• **MoveIgnoreActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[MoveIgnoreActors](ue_ue.SplineComponent.md#moveignoreactors)

#### Defined in

[ue/ue.d.ts:12628](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12628)

___

### MoveIgnoreComponents

• **MoveIgnoreComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[MoveIgnoreComponents](ue_ue.SplineComponent.md#moveignorecomponents)

#### Defined in

[ue/ue.d.ts:12629](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12629)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnBeginCursorOver](ue_ue.SplineComponent.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:12636](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12636)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnClicked](ue_ue.SplineComponent.md#onclicked)

#### Defined in

[ue/ue.d.ts:12638](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12638)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnComponentActivated](ue_ue.SplineComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L303)

___

### OnComponentBeginOverlap

• **OnComponentBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`, `bFromSweep`: `boolean`, `SweepResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnComponentBeginOverlap](ue_ue.SplineComponent.md#oncomponentbeginoverlap)

#### Defined in

[ue/ue.d.ts:12632](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12632)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnComponentDeactivated](ue_ue.SplineComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L304)

___

### OnComponentEndOverlap

• **OnComponentEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnComponentEndOverlap](ue_ue.SplineComponent.md#oncomponentendoverlap)

#### Defined in

[ue/ue.d.ts:12633](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12633)

___

### OnComponentHit

• **OnComponentHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`HitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnComponentHit](ue_ue.SplineComponent.md#oncomponenthit)

#### Defined in

[ue/ue.d.ts:12631](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12631)

___

### OnComponentSleep

• **OnComponentSleep**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SleepingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnComponentSleep](ue_ue.SplineComponent.md#oncomponentsleep)

#### Defined in

[ue/ue.d.ts:12635](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12635)

___

### OnComponentWake

• **OnComponentWake**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`WakingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnComponentWake](ue_ue.SplineComponent.md#oncomponentwake)

#### Defined in

[ue/ue.d.ts:12634](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12634)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnEndCursorOver](ue_ue.SplineComponent.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:12637](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12637)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnInputTouchBegin](ue_ue.SplineComponent.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:12640](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12640)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnInputTouchEnd](ue_ue.SplineComponent.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:12641](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12641)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnInputTouchEnter](ue_ue.SplineComponent.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:12642](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12642)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnInputTouchLeave](ue_ue.SplineComponent.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:12643](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12643)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnReleased](ue_ue.SplineComponent.md#onreleased)

#### Defined in

[ue/ue.d.ts:12639](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12639)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[PhysicsVolume](ue_ue.SplineComponent.md#physicsvolume)

#### Defined in

[ue/ue.d.ts:12870](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12870)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.SplineComponent.md#physicsvolumechangeddelegate)

#### Defined in

[ue/ue.d.ts:12894](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12894)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[PrimaryComponentTick](ue_ue.SplineComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L289)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[RelativeLocation](ue_ue.SplineComponent.md#relativelocation)

#### Defined in

[ue/ue.d.ts:12875](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12875)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[RelativeRotation](ue_ue.SplineComponent.md#relativerotation)

#### Defined in

[ue/ue.d.ts:12876](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12876)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[RelativeScale3D](ue_ue.SplineComponent.md#relativescale3d)

#### Defined in

[ue/ue.d.ts:12877](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12877)

___

### ReparamStepsPerSegment

• **ReparamStepsPerSegment**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ReparamStepsPerSegment](ue_ue.SplineComponent.md#reparamstepspersegment)

#### Defined in

[ue/ue.d.ts:25920](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25920)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[RuntimeVirtualTextures](ue_ue.SplineComponent.md#runtimevirtualtextures)

#### Defined in

[ue/ue.d.ts:12621](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12621)

___

### ScaleVisualizationWidth

• **ScaleVisualizationWidth**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ScaleVisualizationWidth](ue_ue.SplineComponent.md#scalevisualizationwidth)

#### Defined in

[ue/ue.d.ts:25935](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25935)

___

### SplineCurves

• **SplineCurves**: [`SplineCurves`](ue_ue.SplineCurves.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SplineCurves](ue_ue.SplineComponent.md#splinecurves)

#### Defined in

[ue/ue.d.ts:25914](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25914)

___

### SplineInfo

• **SplineInfo**: [`InterpCurveVector`](ue_ue.InterpCurveVector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SplineInfo](ue_ue.SplineComponent.md#splineinfo)

#### Defined in

[ue/ue.d.ts:25915](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25915)

___

### SplineReparamTable

• **SplineReparamTable**: [`InterpCurveFloat`](ue_ue.InterpCurveFloat.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SplineReparamTable](ue_ue.SplineComponent.md#splinereparamtable)

#### Defined in

[ue/ue.d.ts:25918](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25918)

___

### SplineRotInfo

• **SplineRotInfo**: [`InterpCurveQuat`](ue_ue.InterpCurveQuat.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SplineRotInfo](ue_ue.SplineComponent.md#splinerotinfo)

#### Defined in

[ue/ue.d.ts:25916](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25916)

___

### SplineScaleInfo

• **SplineScaleInfo**: [`InterpCurveVector`](ue_ue.InterpCurveVector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SplineScaleInfo](ue_ue.SplineComponent.md#splinescaleinfo)

#### Defined in

[ue/ue.d.ts:25917](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25917)

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[TranslucencySortPriority](ue_ue.SplineComponent.md#translucencysortpriority)

#### Defined in

[ue/ue.d.ts:12619](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12619)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[UCSModifiedProperties](ue_ue.SplineComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L305)

___

### ViewOwnerDepthPriorityGroup

• **ViewOwnerDepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ViewOwnerDepthPriorityGroup](ue_ue.SplineComponent.md#viewownerdepthprioritygroup)

#### Defined in

[ue/ue.d.ts:12559](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12559)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[VirtualTextureCullMips](ue_ue.SplineComponent.md#virtualtexturecullmips)

#### Defined in

[ue/ue.d.ts:12623](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12623)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[VirtualTextureLodBias](ue_ue.SplineComponent.md#virtualtexturelodbias)

#### Defined in

[ue/ue.d.ts:12622](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12622)

___

### VirtualTextureMinCoverage

• **VirtualTextureMinCoverage**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[VirtualTextureMinCoverage](ue_ue.SplineComponent.md#virtualtexturemincoverage)

#### Defined in

[ue/ue.d.ts:12624](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12624)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[VirtualTextureRenderPassType](ue_ue.SplineComponent.md#virtualtexturerenderpasstype)

#### Defined in

[ue/ue.d.ts:12625](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12625)

___

### VisibilityId

• **VisibilityId**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[VisibilityId](ue_ue.SplineComponent.md#visibilityid)

#### Defined in

[ue/ue.d.ts:12620](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12620)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[__tid_ActorComponent__](ue_ue.SplineComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L336)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[__tid_Object__](ue_ue.SplineComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PaperTerrainSplineComponent\_\_

• **\_\_tid\_PaperTerrainSplineComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:54929](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54929)

___

### \_\_tid\_PrimitiveComponent\_\_

• **\_\_tid\_PrimitiveComponent\_\_**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[__tid_PrimitiveComponent__](ue_ue.SplineComponent.md#__tid_primitivecomponent__)

#### Defined in

[ue/ue.d.ts:12761](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12761)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[__tid_SceneComponent__](ue_ue.SplineComponent.md#__tid_scenecomponent__)

#### Defined in

[ue/ue.d.ts:12961](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12961)

___

### \_\_tid\_SplineComponent\_\_

• **\_\_tid\_SplineComponent\_\_**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[__tid_SplineComponent__](ue_ue.SplineComponent.md#__tid_splinecomponent__)

#### Defined in

[ue/ue.d.ts:26034](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26034)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAbsoluteLocation](ue_ue.SplineComponent.md#babsolutelocation)

#### Defined in

[ue/ue.d.ts:12880](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12880)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAbsoluteRotation](ue_ue.SplineComponent.md#babsoluterotation)

#### Defined in

[ue/ue.d.ts:12881](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12881)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAbsoluteScale](ue_ue.SplineComponent.md#babsolutescale)

#### Defined in

[ue/ue.d.ts:12882](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12882)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAffectDistanceFieldLighting](ue_ue.SplineComponent.md#baffectdistancefieldlighting)

#### Defined in

[ue/ue.d.ts:12589](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12589)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAffectDynamicIndirectLighting](ue_ue.SplineComponent.md#baffectdynamicindirectlighting)

#### Defined in

[ue/ue.d.ts:12588](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12588)

___

### bAllowCullDistanceVolume

• **bAllowCullDistanceVolume**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAllowCullDistanceVolume](ue_ue.SplineComponent.md#ballowculldistancevolume)

#### Defined in

[ue/ue.d.ts:12573](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12573)

___

### bAllowDiscontinuousSpline

• **bAllowDiscontinuousSpline**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAllowDiscontinuousSpline](ue_ue.SplineComponent.md#ballowdiscontinuousspline)

#### Defined in

[ue/ue.d.ts:25933](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25933)

___

### bAllowSplineEditingPerInstance

• **bAllowSplineEditingPerInstance**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAllowSplineEditingPerInstance](ue_ue.SplineComponent.md#ballowsplineeditingperinstance)

#### Defined in

[ue/ue.d.ts:25919](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25919)

___

### bAlwaysCreatePhysicsState

• **bAlwaysCreatePhysicsState**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAlwaysCreatePhysicsState](ue_ue.SplineComponent.md#balwayscreatephysicsstate)

#### Defined in

[ue/ue.d.ts:12567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12567)

___

### bApplyImpulseOnDamage

• **bApplyImpulseOnDamage**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bApplyImpulseOnDamage](ue_ue.SplineComponent.md#bapplyimpulseondamage)

#### Defined in

[ue/ue.d.ts:12606](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12606)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAutoActivate](ue_ue.SplineComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L296)

___

### bBatchImpostersAsInstances

• **bBatchImpostersAsInstances**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bBatchImpostersAsInstances](ue_ue.SplineComponent.md#bbatchimpostersasinstances)

#### Defined in

[ue/ue.d.ts:12565](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12565)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.SplineComponent.md#bboundschangetriggersstreamingdatarebuild)

#### Defined in

[ue/ue.d.ts:12889](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12889)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCanEverAffectNavigation](ue_ue.SplineComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L299)

___

### bCastCinematicShadow

• **bCastCinematicShadow**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCastCinematicShadow](ue_ue.SplineComponent.md#bcastcinematicshadow)

#### Defined in

[ue/ue.d.ts:12596](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12596)

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCastDynamicShadow](ue_ue.SplineComponent.md#bcastdynamicshadow)

#### Defined in

[ue/ue.d.ts:12590](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12590)

___

### bCastFarShadow

• **bCastFarShadow**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCastFarShadow](ue_ue.SplineComponent.md#bcastfarshadow)

#### Defined in

[ue/ue.d.ts:12594](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12594)

___

### bCastHiddenShadow

• **bCastHiddenShadow**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCastHiddenShadow](ue_ue.SplineComponent.md#bcasthiddenshadow)

#### Defined in

[ue/ue.d.ts:12597](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12597)

___

### bCastInsetShadow

• **bCastInsetShadow**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCastInsetShadow](ue_ue.SplineComponent.md#bcastinsetshadow)

#### Defined in

[ue/ue.d.ts:12595](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12595)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCastShadowAsTwoSided](ue_ue.SplineComponent.md#bcastshadowastwosided)

#### Defined in

[ue/ue.d.ts:12598](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12598)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCastStaticShadow](ue_ue.SplineComponent.md#bcaststaticshadow)

#### Defined in

[ue/ue.d.ts:12591](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12591)

___

### bCastVolumetricTranslucentShadow

• **bCastVolumetricTranslucentShadow**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCastVolumetricTranslucentShadow](ue_ue.SplineComponent.md#bcastvolumetrictranslucentshadow)

#### Defined in

[ue/ue.d.ts:12592](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12592)

___

### bClosedLoop

• **bClosedLoop**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bClosedLoop](ue_ue.SplineComponent.md#bclosedloop)

#### Defined in

[ue/ue.d.ts:25927](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25927)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bComponentToWorldUpdated](ue_ue.SplineComponent.md#bcomponenttoworldupdated)

#### Defined in

[ue/ue.d.ts:12879](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12879)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCreatedByConstructionScript](ue_ue.SplineComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L294)

___

### bDrawDebug

• **bDrawDebug**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bDrawDebug](ue_ue.SplineComponent.md#bdrawdebug)

#### Defined in

[ue/ue.d.ts:25926](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25926)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bEditableWhenInherited](ue_ue.SplineComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L298)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bEnableAutoLODGeneration](ue_ue.SplineComponent.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:12563](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12563)

___

### bExcludeFromLightAttachmentGroup

• **bExcludeFromLightAttachmentGroup**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bExcludeFromLightAttachmentGroup](ue_ue.SplineComponent.md#bexcludefromlightattachmentgroup)

#### Defined in

[ue/ue.d.ts:12601](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12601)

___

### bForceMipStreaming

• **bForceMipStreaming**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bForceMipStreaming](ue_ue.SplineComponent.md#bforcemipstreaming)

#### Defined in

[ue/ue.d.ts:12585](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12585)

___

### bGenerateOverlapEvents

• **bGenerateOverlapEvents**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bGenerateOverlapEvents](ue_ue.SplineComponent.md#bgenerateoverlapevents)

#### Defined in

[ue/ue.d.ts:12568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12568)

___

### bHasCustomNavigableGeometry

• **bHasCustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bHasCustomNavigableGeometry](ue_ue.SplineComponent.md#bhascustomnavigablegeometry)

#### Defined in

[ue/ue.d.ts:12612](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12612)

___

### bHasMotionBlurVelocityMeshes

• **bHasMotionBlurVelocityMeshes**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bHasMotionBlurVelocityMeshes](ue_ue.SplineComponent.md#bhasmotionblurvelocitymeshes)

#### Defined in

[ue/ue.d.ts:12574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12574)

___

### bHasPerInstanceHitProxies

• **bHasPerInstanceHitProxies**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bHasPerInstanceHitProxies](ue_ue.SplineComponent.md#bhasperinstancehitproxies)

#### Defined in

[ue/ue.d.ts:12586](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12586)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bHiddenInGame](ue_ue.SplineComponent.md#bhiddeningame)

#### Defined in

[ue/ue.d.ts:12884](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12884)

___

### bIgnoreRadialForce

• **bIgnoreRadialForce**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bIgnoreRadialForce](ue_ue.SplineComponent.md#bignoreradialforce)

#### Defined in

[ue/ue.d.ts:12605](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12605)

___

### bIgnoreRadialImpulse

• **bIgnoreRadialImpulse**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bIgnoreRadialImpulse](ue_ue.SplineComponent.md#bignoreradialimpulse)

#### Defined in

[ue/ue.d.ts:12604](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12604)

___

### bInputSplinePointsToConstructionScript

• **bInputSplinePointsToConstructionScript**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bInputSplinePointsToConstructionScript](ue_ue.SplineComponent.md#binputsplinepointstoconstructionscript)

#### Defined in

[ue/ue.d.ts:25925](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25925)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bInstanceComponent](ue_ue.SplineComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bIsActive](ue_ue.SplineComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bIsEditorOnly](ue_ue.SplineComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bIsVisualizationComponent](ue_ue.SplineComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L301)

___

### bLightAsIfStatic

• **bLightAsIfStatic**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bLightAsIfStatic](ue_ue.SplineComponent.md#blightasifstatic)

#### Defined in

[ue/ue.d.ts:12599](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12599)

___

### bLightAttachmentsAsGroup

• **bLightAttachmentsAsGroup**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bLightAttachmentsAsGroup](ue_ue.SplineComponent.md#blightattachmentsasgroup)

#### Defined in

[ue/ue.d.ts:12600](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12600)

___

### bLoopPositionOverride

• **bLoopPositionOverride**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bLoopPositionOverride](ue_ue.SplineComponent.md#blooppositionoverride)

#### Defined in

[ue/ue.d.ts:25928](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25928)

___

### bModifiedByConstructionScript

• **bModifiedByConstructionScript**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bModifiedByConstructionScript](ue_ue.SplineComponent.md#bmodifiedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:25924](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25924)

___

### bMultiBodyOverlap

• **bMultiBodyOverlap**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bMultiBodyOverlap](ue_ue.SplineComponent.md#bmultibodyoverlap)

#### Defined in

[ue/ue.d.ts:12569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12569)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bNetAddressable](ue_ue.SplineComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L293)

___

### bNeverDistanceCull

• **bNeverDistanceCull**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bNeverDistanceCull](ue_ue.SplineComponent.md#bneverdistancecull)

#### Defined in

[ue/ue.d.ts:12566](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12566)

___

### bOnlyOwnerSee

• **bOnlyOwnerSee**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bOnlyOwnerSee](ue_ue.SplineComponent.md#bonlyownersee)

#### Defined in

[ue/ue.d.ts:12581](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12581)

___

### bOwnerNoSee

• **bOwnerNoSee**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bOwnerNoSee](ue_ue.SplineComponent.md#bownernosee)

#### Defined in

[ue/ue.d.ts:12580](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12580)

___

### bReceiveMobileCSMShadows

• **bReceiveMobileCSMShadows**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bReceiveMobileCSMShadows](ue_ue.SplineComponent.md#breceivemobilecsmshadows)

#### Defined in

[ue/ue.d.ts:12602](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12602)

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bReceivesDecals](ue_ue.SplineComponent.md#breceivesdecals)

#### Defined in

[ue/ue.d.ts:12579](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12579)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bRenderCustomDepth](ue_ue.SplineComponent.md#brendercustomdepth)

#### Defined in

[ue/ue.d.ts:12611](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12611)

___

### bRenderInDepthPass

• **bRenderInDepthPass**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bRenderInDepthPass](ue_ue.SplineComponent.md#brenderindepthpass)

#### Defined in

[ue/ue.d.ts:12578](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12578)

___

### bRenderInMainPass

• **bRenderInMainPass**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bRenderInMainPass](ue_ue.SplineComponent.md#brenderinmainpass)

#### Defined in

[ue/ue.d.ts:12577](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12577)

___

### bReplicatePhysicsToAutonomousProxy

• **bReplicatePhysicsToAutonomousProxy**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bReplicatePhysicsToAutonomousProxy](ue_ue.SplineComponent.md#breplicatephysicstoautonomousproxy)

#### Defined in

[ue/ue.d.ts:12607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12607)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bReplicates](ue_ue.SplineComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L292)

___

### bReturnMaterialOnMove

• **bReturnMaterialOnMove**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bReturnMaterialOnMove](ue_ue.SplineComponent.md#breturnmaterialonmove)

#### Defined in

[ue/ue.d.ts:12571](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12571)

___

### bSelectable

• **bSelectable**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bSelectable](ue_ue.SplineComponent.md#bselectable)

#### Defined in

[ue/ue.d.ts:12584](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12584)

___

### bSelfShadowOnly

• **bSelfShadowOnly**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bSelfShadowOnly](ue_ue.SplineComponent.md#bselfshadowonly)

#### Defined in

[ue/ue.d.ts:12593](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12593)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bShouldBeAttached](ue_ue.SplineComponent.md#bshouldbeattached)

#### Defined in

[ue/ue.d.ts:12885](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12885)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.SplineComponent.md#bshouldsnaplocationwhenattached)

#### Defined in

[ue/ue.d.ts:12886](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12886)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.SplineComponent.md#bshouldsnaprotationwhenattached)

#### Defined in

[ue/ue.d.ts:12887](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12887)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.SplineComponent.md#bshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12888](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12888)

___

### bShouldVisualizeScale

• **bShouldVisualizeScale**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bShouldVisualizeScale](ue_ue.SplineComponent.md#bshouldvisualizescale)

#### Defined in

[ue/ue.d.ts:25934](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25934)

___

### bSingleSampleShadowFromStationaryLights

• **bSingleSampleShadowFromStationaryLights**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bSingleSampleShadowFromStationaryLights](ue_ue.SplineComponent.md#bsinglesampleshadowfromstationarylights)

#### Defined in

[ue/ue.d.ts:12603](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12603)

___

### bSplineHasBeenEdited

• **bSplineHasBeenEdited**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bSplineHasBeenEdited](ue_ue.SplineComponent.md#bsplinehasbeenedited)

#### Defined in

[ue/ue.d.ts:25923](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25923)

___

### bStationaryEndpoints

• **bStationaryEndpoints**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bStationaryEndpoints](ue_ue.SplineComponent.md#bstationaryendpoints)

#### Defined in

[ue/ue.d.ts:25922](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25922)

___

### bTraceComplexOnMove

• **bTraceComplexOnMove**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bTraceComplexOnMove](ue_ue.SplineComponent.md#btracecomplexonmove)

#### Defined in

[ue/ue.d.ts:12570](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12570)

___

### bTreatAsBackgroundForOcclusion

• **bTreatAsBackgroundForOcclusion**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bTreatAsBackgroundForOcclusion](ue_ue.SplineComponent.md#btreatasbackgroundforocclusion)

#### Defined in

[ue/ue.d.ts:12582](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12582)

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bUseAsOccluder](ue_ue.SplineComponent.md#buseasoccluder)

#### Defined in

[ue/ue.d.ts:12583](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12583)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bUseAttachParentBound](ue_ue.SplineComponent.md#buseattachparentbound)

#### Defined in

[ue/ue.d.ts:12890](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12890)

___

### bUseEditorCompositing

• **bUseEditorCompositing**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bUseEditorCompositing](ue_ue.SplineComponent.md#buseeditorcompositing)

#### Defined in

[ue/ue.d.ts:12610](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12610)

___

### bUseMaxLODAsImposter

• **bUseMaxLODAsImposter**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bUseMaxLODAsImposter](ue_ue.SplineComponent.md#busemaxlodasimposter)

#### Defined in

[ue/ue.d.ts:12564](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12564)

___

### bUseViewOwnerDepthPriorityGroup

• **bUseViewOwnerDepthPriorityGroup**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bUseViewOwnerDepthPriorityGroup](ue_ue.SplineComponent.md#buseviewownerdepthprioritygroup)

#### Defined in

[ue/ue.d.ts:12572](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12572)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bVisible](ue_ue.SplineComponent.md#bvisible)

#### Defined in

[ue/ue.d.ts:12883](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12883)

___

### bVisibleInRayTracing

• **bVisibleInRayTracing**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bVisibleInRayTracing](ue_ue.SplineComponent.md#bvisibleinraytracing)

#### Defined in

[ue/ue.d.ts:12576](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12576)

___

### bVisibleInReflectionCaptures

• **bVisibleInReflectionCaptures**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bVisibleInReflectionCaptures](ue_ue.SplineComponent.md#bvisibleinreflectioncaptures)

#### Defined in

[ue/ue.d.ts:12575](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12575)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bVisualizeComponent](ue_ue.SplineComponent.md#bvisualizecomponent)

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

[SplineComponent](ue_ue.SplineComponent.md).[Activate](ue_ue.SplineComponent.md#activate)

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

[SplineComponent](ue_ue.SplineComponent.md).[AddAngularImpulse](ue_ue.SplineComponent.md#addangularimpulse)

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

[SplineComponent](ue_ue.SplineComponent.md).[AddAngularImpulseInDegrees](ue_ue.SplineComponent.md#addangularimpulseindegrees)

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

[SplineComponent](ue_ue.SplineComponent.md).[AddAngularImpulseInRadians](ue_ue.SplineComponent.md#addangularimpulseinradians)

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

[SplineComponent](ue_ue.SplineComponent.md).[AddForce](ue_ue.SplineComponent.md#addforce)

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

[SplineComponent](ue_ue.SplineComponent.md).[AddForceAtLocation](ue_ue.SplineComponent.md#addforceatlocation)

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

[SplineComponent](ue_ue.SplineComponent.md).[AddForceAtLocationLocal](ue_ue.SplineComponent.md#addforceatlocationlocal)

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

[SplineComponent](ue_ue.SplineComponent.md).[AddImpulse](ue_ue.SplineComponent.md#addimpulse)

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

[SplineComponent](ue_ue.SplineComponent.md).[AddImpulseAtLocation](ue_ue.SplineComponent.md#addimpulseatlocation)

#### Defined in

[ue/ue.d.ts:12652](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12652)

___

### AddPoint

▸ **AddPoint**(`Point`, `bUpdateSpline?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Point` | [`SplinePoint`](ue_ue.SplinePoint.md) |
| `bUpdateSpline?` | `boolean` |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AddPoint](ue_ue.SplineComponent.md#addpoint)

#### Defined in

[ue/ue.d.ts:25936](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25936)

___

### AddPoints

▸ **AddPoints**(`Points`, `bUpdateSpline?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Points` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SplinePoint`](ue_ue.SplinePoint.md)\> |
| `bUpdateSpline?` | `boolean` |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AddPoints](ue_ue.SplineComponent.md#addpoints)

#### Defined in

[ue/ue.d.ts:25937](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25937)

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

[SplineComponent](ue_ue.SplineComponent.md).[AddRadialForce](ue_ue.SplineComponent.md#addradialforce)

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

[SplineComponent](ue_ue.SplineComponent.md).[AddRadialImpulse](ue_ue.SplineComponent.md#addradialimpulse)

#### Defined in

[ue/ue.d.ts:12654](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12654)

___

### AddSplineLocalPoint

▸ **AddSplineLocalPoint**(`Position`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Position` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AddSplineLocalPoint](ue_ue.SplineComponent.md#addsplinelocalpoint)

#### Defined in

[ue/ue.d.ts:25938](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25938)

___

### AddSplinePoint

▸ **AddSplinePoint**(`Position`, `CoordinateSpace`, `bUpdateSpline?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Position` | [`Vector`](ue_ue_s.Vector.md) |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUpdateSpline?` | `boolean` |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AddSplinePoint](ue_ue.SplineComponent.md#addsplinepoint)

#### Defined in

[ue/ue.d.ts:25939](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25939)

___

### AddSplinePointAtIndex

▸ **AddSplinePointAtIndex**(`Position`, `Index`, `CoordinateSpace`, `bUpdateSpline?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Position` | [`Vector`](ue_ue_s.Vector.md) |
| `Index` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUpdateSpline?` | `boolean` |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AddSplinePointAtIndex](ue_ue.SplineComponent.md#addsplinepointatindex)

#### Defined in

[ue/ue.d.ts:25940](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25940)

___

### AddSplineWorldPoint

▸ **AddSplineWorldPoint**(`Position`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Position` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AddSplineWorldPoint](ue_ue.SplineComponent.md#addsplineworldpoint)

#### Defined in

[ue/ue.d.ts:25941](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25941)

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

[SplineComponent](ue_ue.SplineComponent.md).[AddTickPrerequisiteActor](ue_ue.SplineComponent.md#addtickprerequisiteactor)

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

[SplineComponent](ue_ue.SplineComponent.md).[AddTickPrerequisiteComponent](ue_ue.SplineComponent.md#addtickprerequisitecomponent)

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

[SplineComponent](ue_ue.SplineComponent.md).[AddTorque](ue_ue.SplineComponent.md#addtorque)

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

[SplineComponent](ue_ue.SplineComponent.md).[AddTorqueInDegrees](ue_ue.SplineComponent.md#addtorqueindegrees)

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

[SplineComponent](ue_ue.SplineComponent.md).[AddTorqueInRadians](ue_ue.SplineComponent.md#addtorqueinradians)

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

[SplineComponent](ue_ue.SplineComponent.md).[CanCharacterStepUp](ue_ue.SplineComponent.md#cancharacterstepup)

#### Defined in

[ue/ue.d.ts:12658](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12658)

___

### ClearMoveIgnoreActors

▸ **ClearMoveIgnoreActors**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ClearMoveIgnoreActors](ue_ue.SplineComponent.md#clearmoveignoreactors)

#### Defined in

[ue/ue.d.ts:12659](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12659)

___

### ClearMoveIgnoreComponents

▸ **ClearMoveIgnoreComponents**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ClearMoveIgnoreComponents](ue_ue.SplineComponent.md#clearmoveignorecomponents)

#### Defined in

[ue/ue.d.ts:12660](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12660)

___

### ClearSplinePoints

▸ **ClearSplinePoints**(`bUpdateSpline?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bUpdateSpline?` | `boolean` |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ClearSplinePoints](ue_ue.SplineComponent.md#clearsplinepoints)

#### Defined in

[ue/ue.d.ts:25942](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25942)

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

[SplineComponent](ue_ue.SplineComponent.md).[ComponentHasTag](ue_ue.SplineComponent.md#componenthastag)

#### Defined in

[ue/ue.d.ts:309](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L309)

___

### CopyArrayOfMoveIgnoreActors

▸ **CopyArrayOfMoveIgnoreActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CopyArrayOfMoveIgnoreActors](ue_ue.SplineComponent.md#copyarrayofmoveignoreactors)

#### Defined in

[ue/ue.d.ts:12661](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12661)

___

### CopyArrayOfMoveIgnoreComponents

▸ **CopyArrayOfMoveIgnoreComponents**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CopyArrayOfMoveIgnoreComponents](ue_ue.SplineComponent.md#copyarrayofmoveignorecomponents)

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

[SplineComponent](ue_ue.SplineComponent.md).[CreateAndSetMaterialInstanceDynamic](ue_ue.SplineComponent.md#createandsetmaterialinstancedynamic)

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

[SplineComponent](ue_ue.SplineComponent.md).[CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.SplineComponent.md#createandsetmaterialinstancedynamicfrommaterial)

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

[SplineComponent](ue_ue.SplineComponent.md).[CreateDefaultSubobject](ue_ue.SplineComponent.md#createdefaultsubobject)

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

[SplineComponent](ue_ue.SplineComponent.md).[CreateDynamicMaterialInstance](ue_ue.SplineComponent.md#createdynamicmaterialinstance)

#### Defined in

[ue/ue.d.ts:12665](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12665)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[Deactivate](ue_ue.SplineComponent.md#deactivate)

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

[SplineComponent](ue_ue.SplineComponent.md).[DetachFromParent](ue_ue.SplineComponent.md#detachfromparent)

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

[SplineComponent](ue_ue.SplineComponent.md).[DoesSocketExist](ue_ue.SplineComponent.md#doessocketexist)

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

[SplineComponent](ue_ue.SplineComponent.md).[ExecuteUbergraph](ue_ue.SplineComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### FindDirectionClosestToWorldLocation

▸ **FindDirectionClosestToWorldLocation**(`WorldLocation`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[FindDirectionClosestToWorldLocation](ue_ue.SplineComponent.md#finddirectionclosesttoworldlocation)

#### Defined in

[ue/ue.d.ts:25943](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25943)

___

### FindInputKeyClosestToWorldLocation

▸ **FindInputKeyClosestToWorldLocation**(`WorldLocation`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldLocation` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[FindInputKeyClosestToWorldLocation](ue_ue.SplineComponent.md#findinputkeyclosesttoworldlocation)

#### Defined in

[ue/ue.d.ts:25944](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25944)

___

### FindLocationClosestToWorldLocation

▸ **FindLocationClosestToWorldLocation**(`WorldLocation`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[FindLocationClosestToWorldLocation](ue_ue.SplineComponent.md#findlocationclosesttoworldlocation)

#### Defined in

[ue/ue.d.ts:25945](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25945)

___

### FindRightVectorClosestToWorldLocation

▸ **FindRightVectorClosestToWorldLocation**(`WorldLocation`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[FindRightVectorClosestToWorldLocation](ue_ue.SplineComponent.md#findrightvectorclosesttoworldlocation)

#### Defined in

[ue/ue.d.ts:25946](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25946)

___

### FindRollClosestToWorldLocation

▸ **FindRollClosestToWorldLocation**(`WorldLocation`, `CoordinateSpace`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[FindRollClosestToWorldLocation](ue_ue.SplineComponent.md#findrollclosesttoworldlocation)

#### Defined in

[ue/ue.d.ts:25947](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25947)

___

### FindRotationClosestToWorldLocation

▸ **FindRotationClosestToWorldLocation**(`WorldLocation`, `CoordinateSpace`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[FindRotationClosestToWorldLocation](ue_ue.SplineComponent.md#findrotationclosesttoworldlocation)

#### Defined in

[ue/ue.d.ts:25948](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25948)

___

### FindScaleClosestToWorldLocation

▸ **FindScaleClosestToWorldLocation**(`WorldLocation`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldLocation` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[FindScaleClosestToWorldLocation](ue_ue.SplineComponent.md#findscaleclosesttoworldlocation)

#### Defined in

[ue/ue.d.ts:25949](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25949)

___

### FindTangentClosestToWorldLocation

▸ **FindTangentClosestToWorldLocation**(`WorldLocation`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[FindTangentClosestToWorldLocation](ue_ue.SplineComponent.md#findtangentclosesttoworldlocation)

#### Defined in

[ue/ue.d.ts:25950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25950)

___

### FindTransformClosestToWorldLocation

▸ **FindTransformClosestToWorldLocation**(`WorldLocation`, `CoordinateSpace`, `bUseScale?`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUseScale?` | `boolean` |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[FindTransformClosestToWorldLocation](ue_ue.SplineComponent.md#findtransformclosesttoworldlocation)

#### Defined in

[ue/ue.d.ts:25951](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25951)

___

### FindUpVectorClosestToWorldLocation

▸ **FindUpVectorClosestToWorldLocation**(`WorldLocation`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[FindUpVectorClosestToWorldLocation](ue_ue.SplineComponent.md#findupvectorclosesttoworldlocation)

#### Defined in

[ue/ue.d.ts:25952](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25952)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetAllSocketNames](ue_ue.SplineComponent.md#getallsocketnames)

#### Defined in

[ue/ue.d.ts:12897](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12897)

___

### GetAngularDamping

▸ **GetAngularDamping**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetAngularDamping](ue_ue.SplineComponent.md#getangulardamping)

#### Defined in

[ue/ue.d.ts:12666](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12666)

___

### GetArriveTangentAtSplinePoint

▸ **GetArriveTangentAtSplinePoint**(`PointIndex`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetArriveTangentAtSplinePoint](ue_ue.SplineComponent.md#getarrivetangentatsplinepoint)

#### Defined in

[ue/ue.d.ts:25953](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25953)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetAttachParent](ue_ue.SplineComponent.md#getattachparent)

#### Defined in

[ue/ue.d.ts:12898](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12898)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetAttachSocketName](ue_ue.SplineComponent.md#getattachsocketname)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetCenterOfMass](ue_ue.SplineComponent.md#getcenterofmass)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetChildComponent](ue_ue.SplineComponent.md#getchildcomponent)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetChildrenComponents](ue_ue.SplineComponent.md#getchildrencomponents)

#### Defined in

[ue/ue.d.ts:12901](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12901)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetClass](ue_ue.SplineComponent.md#getclass)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetClosestPointOnCollision](ue_ue.SplineComponent.md#getclosestpointoncollision)

#### Defined in

[ue/ue.d.ts:12668](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12668)

___

### GetCollisionEnabled

▸ **GetCollisionEnabled**(): [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Returns

[`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetCollisionEnabled](ue_ue.SplineComponent.md#getcollisionenabled)

#### Defined in

[ue/ue.d.ts:12669](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12669)

___

### GetCollisionObjectType

▸ **GetCollisionObjectType**(): [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Returns

[`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetCollisionObjectType](ue_ue.SplineComponent.md#getcollisionobjecttype)

#### Defined in

[ue/ue.d.ts:12670](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12670)

___

### GetCollisionProfileName

▸ **GetCollisionProfileName**(): `string`

#### Returns

`string`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetCollisionProfileName](ue_ue.SplineComponent.md#getcollisionprofilename)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetCollisionResponseToChannel](ue_ue.SplineComponent.md#getcollisionresponsetochannel)

#### Defined in

[ue/ue.d.ts:12672](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12672)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetComponentTickInterval](ue_ue.SplineComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L311)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetComponentVelocity](ue_ue.SplineComponent.md#getcomponentvelocity)

#### Defined in

[ue/ue.d.ts:12902](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12902)

___

### GetDefaultUpVector

▸ **GetDefaultUpVector**(`CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetDefaultUpVector](ue_ue.SplineComponent.md#getdefaultupvector)

#### Defined in

[ue/ue.d.ts:25954](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25954)

___

### GetDirectionAtDistanceAlongSpline

▸ **GetDirectionAtDistanceAlongSpline**(`Distance`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Distance` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetDirectionAtDistanceAlongSpline](ue_ue.SplineComponent.md#getdirectionatdistancealongspline)

#### Defined in

[ue/ue.d.ts:25955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25955)

___

### GetDirectionAtSplineInputKey

▸ **GetDirectionAtSplineInputKey**(`InKey`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InKey` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetDirectionAtSplineInputKey](ue_ue.SplineComponent.md#getdirectionatsplineinputkey)

#### Defined in

[ue/ue.d.ts:25956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25956)

___

### GetDirectionAtSplinePoint

▸ **GetDirectionAtSplinePoint**(`PointIndex`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetDirectionAtSplinePoint](ue_ue.SplineComponent.md#getdirectionatsplinepoint)

#### Defined in

[ue/ue.d.ts:25957](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25957)

___

### GetDirectionAtTime

▸ **GetDirectionAtTime**(`Time`, `CoordinateSpace`, `bUseConstantVelocity?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUseConstantVelocity?` | `boolean` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetDirectionAtTime](ue_ue.SplineComponent.md#getdirectionattime)

#### Defined in

[ue/ue.d.ts:25958](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25958)

___

### GetDistanceAlongSplineAtSplinePoint

▸ **GetDistanceAlongSplineAtSplinePoint**(`PointIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetDistanceAlongSplineAtSplinePoint](ue_ue.SplineComponent.md#getdistancealongsplineatsplinepoint)

#### Defined in

[ue/ue.d.ts:25959](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25959)

___

### GetFloatPropertyAtSplineInputKey

▸ **GetFloatPropertyAtSplineInputKey**(`InKey`, `PropertyName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InKey` | `number` |
| `PropertyName` | `string` |

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetFloatPropertyAtSplineInputKey](ue_ue.SplineComponent.md#getfloatpropertyatsplineinputkey)

#### Defined in

[ue/ue.d.ts:25960](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25960)

___

### GetFloatPropertyAtSplinePoint

▸ **GetFloatPropertyAtSplinePoint**(`Index`, `PropertyName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |
| `PropertyName` | `string` |

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetFloatPropertyAtSplinePoint](ue_ue.SplineComponent.md#getfloatpropertyatsplinepoint)

#### Defined in

[ue/ue.d.ts:25961](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25961)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetForwardVector](ue_ue.SplineComponent.md#getforwardvector)

#### Defined in

[ue/ue.d.ts:12903](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12903)

___

### GetGenerateOverlapEvents

▸ **GetGenerateOverlapEvents**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetGenerateOverlapEvents](ue_ue.SplineComponent.md#getgenerateoverlapevents)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetInertiaTensor](ue_ue.SplineComponent.md#getinertiatensor)

#### Defined in

[ue/ue.d.ts:12674](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12674)

___

### GetInputKeyAtDistanceAlongSpline

▸ **GetInputKeyAtDistanceAlongSpline**(`Distance`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Distance` | `number` |

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetInputKeyAtDistanceAlongSpline](ue_ue.SplineComponent.md#getinputkeyatdistancealongspline)

#### Defined in

[ue/ue.d.ts:25962](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25962)

___

### GetLeaveTangentAtSplinePoint

▸ **GetLeaveTangentAtSplinePoint**(`PointIndex`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetLeaveTangentAtSplinePoint](ue_ue.SplineComponent.md#getleavetangentatsplinepoint)

#### Defined in

[ue/ue.d.ts:25963](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25963)

___

### GetLinearDamping

▸ **GetLinearDamping**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetLinearDamping](ue_ue.SplineComponent.md#getlineardamping)

#### Defined in

[ue/ue.d.ts:12675](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12675)

___

### GetLocalLocationAndTangentAtSplinePoint

▸ **GetLocalLocationAndTangentAtSplinePoint**(`PointIndex`, `LocalLocation`, `LocalTangent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `LocalLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `LocalTangent` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetLocalLocationAndTangentAtSplinePoint](ue_ue.SplineComponent.md#getlocallocationandtangentatsplinepoint)

#### Defined in

[ue/ue.d.ts:25964](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25964)

___

### GetLocationAndTangentAtSplinePoint

▸ **GetLocationAndTangentAtSplinePoint**(`PointIndex`, `Location`, `Tangent`, `CoordinateSpace`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `Location` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `Tangent` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetLocationAndTangentAtSplinePoint](ue_ue.SplineComponent.md#getlocationandtangentatsplinepoint)

#### Defined in

[ue/ue.d.ts:25965](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25965)

___

### GetLocationAtDistanceAlongSpline

▸ **GetLocationAtDistanceAlongSpline**(`Distance`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Distance` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetLocationAtDistanceAlongSpline](ue_ue.SplineComponent.md#getlocationatdistancealongspline)

#### Defined in

[ue/ue.d.ts:25966](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25966)

___

### GetLocationAtSplineInputKey

▸ **GetLocationAtSplineInputKey**(`InKey`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InKey` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetLocationAtSplineInputKey](ue_ue.SplineComponent.md#getlocationatsplineinputkey)

#### Defined in

[ue/ue.d.ts:25967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25967)

___

### GetLocationAtSplinePoint

▸ **GetLocationAtSplinePoint**(`PointIndex`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetLocationAtSplinePoint](ue_ue.SplineComponent.md#getlocationatsplinepoint)

#### Defined in

[ue/ue.d.ts:25968](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25968)

___

### GetLocationAtTime

▸ **GetLocationAtTime**(`Time`, `CoordinateSpace`, `bUseConstantVelocity?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUseConstantVelocity?` | `boolean` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetLocationAtTime](ue_ue.SplineComponent.md#getlocationattime)

#### Defined in

[ue/ue.d.ts:25969](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25969)

___

### GetMass

▸ **GetMass**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetMass](ue_ue.SplineComponent.md#getmass)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetMassScale](ue_ue.SplineComponent.md#getmassscale)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetMaterial](ue_ue.SplineComponent.md#getmaterial)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetMaterialFromCollisionFaceIndex](ue_ue.SplineComponent.md#getmaterialfromcollisionfaceindex)

#### Defined in

[ue/ue.d.ts:12679](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12679)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetName](ue_ue.SplineComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetNumChildrenComponents](ue_ue.SplineComponent.md#getnumchildrencomponents)

#### Defined in

[ue/ue.d.ts:12904](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12904)

___

### GetNumMaterials

▸ **GetNumMaterials**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetNumMaterials](ue_ue.SplineComponent.md#getnummaterials)

#### Defined in

[ue/ue.d.ts:12680](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12680)

___

### GetNumberOfSplinePoints

▸ **GetNumberOfSplinePoints**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetNumberOfSplinePoints](ue_ue.SplineComponent.md#getnumberofsplinepoints)

#### Defined in

[ue/ue.d.ts:25970](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25970)

___

### GetNumberOfSplineSegments

▸ **GetNumberOfSplineSegments**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetNumberOfSplineSegments](ue_ue.SplineComponent.md#getnumberofsplinesegments)

#### Defined in

[ue/ue.d.ts:25971](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25971)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetOuter](ue_ue.SplineComponent.md#getouter)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetOverlappingActors](ue_ue.SplineComponent.md#getoverlappingactors)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetOverlappingComponents](ue_ue.SplineComponent.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:12682](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12682)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetOwner](ue_ue.SplineComponent.md#getowner)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetParentComponents](ue_ue.SplineComponent.md#getparentcomponents)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetPhysicsAngularVelocity](ue_ue.SplineComponent.md#getphysicsangularvelocity)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetPhysicsAngularVelocityInDegrees](ue_ue.SplineComponent.md#getphysicsangularvelocityindegrees)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetPhysicsAngularVelocityInRadians](ue_ue.SplineComponent.md#getphysicsangularvelocityinradians)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetPhysicsLinearVelocity](ue_ue.SplineComponent.md#getphysicslinearvelocity)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetPhysicsLinearVelocityAtPoint](ue_ue.SplineComponent.md#getphysicslinearvelocityatpoint)

#### Defined in

[ue/ue.d.ts:12687](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12687)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetPhysicsVolume](ue_ue.SplineComponent.md#getphysicsvolume)

#### Defined in

[ue/ue.d.ts:12906](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12906)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetRelativeTransform](ue_ue.SplineComponent.md#getrelativetransform)

#### Defined in

[ue/ue.d.ts:12907](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12907)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetRightVector](ue_ue.SplineComponent.md#getrightvector)

#### Defined in

[ue/ue.d.ts:12908](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12908)

___

### GetRightVectorAtDistanceAlongSpline

▸ **GetRightVectorAtDistanceAlongSpline**(`Distance`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Distance` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetRightVectorAtDistanceAlongSpline](ue_ue.SplineComponent.md#getrightvectoratdistancealongspline)

#### Defined in

[ue/ue.d.ts:25972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25972)

___

### GetRightVectorAtSplineInputKey

▸ **GetRightVectorAtSplineInputKey**(`InKey`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InKey` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetRightVectorAtSplineInputKey](ue_ue.SplineComponent.md#getrightvectoratsplineinputkey)

#### Defined in

[ue/ue.d.ts:25973](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25973)

___

### GetRightVectorAtSplinePoint

▸ **GetRightVectorAtSplinePoint**(`PointIndex`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetRightVectorAtSplinePoint](ue_ue.SplineComponent.md#getrightvectoratsplinepoint)

#### Defined in

[ue/ue.d.ts:25974](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25974)

___

### GetRightVectorAtTime

▸ **GetRightVectorAtTime**(`Time`, `CoordinateSpace`, `bUseConstantVelocity?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUseConstantVelocity?` | `boolean` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetRightVectorAtTime](ue_ue.SplineComponent.md#getrightvectorattime)

#### Defined in

[ue/ue.d.ts:25975](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25975)

___

### GetRollAtDistanceAlongSpline

▸ **GetRollAtDistanceAlongSpline**(`Distance`, `CoordinateSpace`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Distance` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetRollAtDistanceAlongSpline](ue_ue.SplineComponent.md#getrollatdistancealongspline)

#### Defined in

[ue/ue.d.ts:25976](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25976)

___

### GetRollAtSplineInputKey

▸ **GetRollAtSplineInputKey**(`InKey`, `CoordinateSpace`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InKey` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetRollAtSplineInputKey](ue_ue.SplineComponent.md#getrollatsplineinputkey)

#### Defined in

[ue/ue.d.ts:25977](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25977)

___

### GetRollAtSplinePoint

▸ **GetRollAtSplinePoint**(`PointIndex`, `CoordinateSpace`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetRollAtSplinePoint](ue_ue.SplineComponent.md#getrollatsplinepoint)

#### Defined in

[ue/ue.d.ts:25978](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25978)

___

### GetRollAtTime

▸ **GetRollAtTime**(`Time`, `CoordinateSpace`, `bUseConstantVelocity?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUseConstantVelocity?` | `boolean` |

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetRollAtTime](ue_ue.SplineComponent.md#getrollattime)

#### Defined in

[ue/ue.d.ts:25979](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25979)

___

### GetRotationAtDistanceAlongSpline

▸ **GetRotationAtDistanceAlongSpline**(`Distance`, `CoordinateSpace`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Distance` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetRotationAtDistanceAlongSpline](ue_ue.SplineComponent.md#getrotationatdistancealongspline)

#### Defined in

[ue/ue.d.ts:25980](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25980)

___

### GetRotationAtSplineInputKey

▸ **GetRotationAtSplineInputKey**(`InKey`, `CoordinateSpace`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InKey` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetRotationAtSplineInputKey](ue_ue.SplineComponent.md#getrotationatsplineinputkey)

#### Defined in

[ue/ue.d.ts:25981](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25981)

___

### GetRotationAtSplinePoint

▸ **GetRotationAtSplinePoint**(`PointIndex`, `CoordinateSpace`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetRotationAtSplinePoint](ue_ue.SplineComponent.md#getrotationatsplinepoint)

#### Defined in

[ue/ue.d.ts:25982](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25982)

___

### GetRotationAtTime

▸ **GetRotationAtTime**(`Time`, `CoordinateSpace`, `bUseConstantVelocity?`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUseConstantVelocity?` | `boolean` |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetRotationAtTime](ue_ue.SplineComponent.md#getrotationattime)

#### Defined in

[ue/ue.d.ts:25983](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25983)

___

### GetScaleAtDistanceAlongSpline

▸ **GetScaleAtDistanceAlongSpline**(`Distance`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Distance` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetScaleAtDistanceAlongSpline](ue_ue.SplineComponent.md#getscaleatdistancealongspline)

#### Defined in

[ue/ue.d.ts:25984](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25984)

___

### GetScaleAtSplineInputKey

▸ **GetScaleAtSplineInputKey**(`InKey`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InKey` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetScaleAtSplineInputKey](ue_ue.SplineComponent.md#getscaleatsplineinputkey)

#### Defined in

[ue/ue.d.ts:25985](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25985)

___

### GetScaleAtSplinePoint

▸ **GetScaleAtSplinePoint**(`PointIndex`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetScaleAtSplinePoint](ue_ue.SplineComponent.md#getscaleatsplinepoint)

#### Defined in

[ue/ue.d.ts:25986](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25986)

___

### GetScaleAtTime

▸ **GetScaleAtTime**(`Time`, `bUseConstantVelocity?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | `number` |
| `bUseConstantVelocity?` | `boolean` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetScaleAtTime](ue_ue.SplineComponent.md#getscaleattime)

#### Defined in

[ue/ue.d.ts:25987](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25987)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.SplineComponent.md#getshouldupdatephysicsvolume)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetSocketLocation](ue_ue.SplineComponent.md#getsocketlocation)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetSocketQuaternion](ue_ue.SplineComponent.md#getsocketquaternion)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetSocketRotation](ue_ue.SplineComponent.md#getsocketrotation)

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

[SplineComponent](ue_ue.SplineComponent.md).[GetSocketTransform](ue_ue.SplineComponent.md#getsockettransform)

#### Defined in

[ue/ue.d.ts:12913](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12913)

___

### GetSplineLength

▸ **GetSplineLength**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetSplineLength](ue_ue.SplineComponent.md#getsplinelength)

#### Defined in

[ue/ue.d.ts:25988](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25988)

___

### GetSplinePointType

▸ **GetSplinePointType**(`PointIndex`): [`ESplinePointType`](../enums/ue_ue.ESplinePointType.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |

#### Returns

[`ESplinePointType`](../enums/ue_ue.ESplinePointType.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetSplinePointType](ue_ue.SplineComponent.md#getsplinepointtype)

#### Defined in

[ue/ue.d.ts:25989](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25989)

___

### GetTangentAtDistanceAlongSpline

▸ **GetTangentAtDistanceAlongSpline**(`Distance`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Distance` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetTangentAtDistanceAlongSpline](ue_ue.SplineComponent.md#gettangentatdistancealongspline)

#### Defined in

[ue/ue.d.ts:25990](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25990)

___

### GetTangentAtSplineInputKey

▸ **GetTangentAtSplineInputKey**(`InKey`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InKey` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetTangentAtSplineInputKey](ue_ue.SplineComponent.md#gettangentatsplineinputkey)

#### Defined in

[ue/ue.d.ts:25991](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25991)

___

### GetTangentAtSplinePoint

▸ **GetTangentAtSplinePoint**(`PointIndex`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetTangentAtSplinePoint](ue_ue.SplineComponent.md#gettangentatsplinepoint)

#### Defined in

[ue/ue.d.ts:25992](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25992)

___

### GetTangentAtTime

▸ **GetTangentAtTime**(`Time`, `CoordinateSpace`, `bUseConstantVelocity?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUseConstantVelocity?` | `boolean` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetTangentAtTime](ue_ue.SplineComponent.md#gettangentattime)

#### Defined in

[ue/ue.d.ts:25993](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25993)

___

### GetTransformAtDistanceAlongSpline

▸ **GetTransformAtDistanceAlongSpline**(`Distance`, `CoordinateSpace`, `bUseScale?`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Distance` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUseScale?` | `boolean` |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetTransformAtDistanceAlongSpline](ue_ue.SplineComponent.md#gettransformatdistancealongspline)

#### Defined in

[ue/ue.d.ts:25994](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25994)

___

### GetTransformAtSplineInputKey

▸ **GetTransformAtSplineInputKey**(`InKey`, `CoordinateSpace`, `bUseScale?`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InKey` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUseScale?` | `boolean` |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetTransformAtSplineInputKey](ue_ue.SplineComponent.md#gettransformatsplineinputkey)

#### Defined in

[ue/ue.d.ts:25995](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25995)

___

### GetTransformAtSplinePoint

▸ **GetTransformAtSplinePoint**(`PointIndex`, `CoordinateSpace`, `bUseScale?`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUseScale?` | `boolean` |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetTransformAtSplinePoint](ue_ue.SplineComponent.md#gettransformatsplinepoint)

#### Defined in

[ue/ue.d.ts:25996](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25996)

___

### GetTransformAtTime

▸ **GetTransformAtTime**(`Time`, `CoordinateSpace`, `bUseConstantVelocity?`, `bUseScale?`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUseConstantVelocity?` | `boolean` |
| `bUseScale?` | `boolean` |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetTransformAtTime](ue_ue.SplineComponent.md#gettransformattime)

#### Defined in

[ue/ue.d.ts:25997](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25997)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetUpVector](ue_ue.SplineComponent.md#getupvector)

#### Defined in

[ue/ue.d.ts:12914](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12914)

___

### GetUpVectorAtDistanceAlongSpline

▸ **GetUpVectorAtDistanceAlongSpline**(`Distance`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Distance` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetUpVectorAtDistanceAlongSpline](ue_ue.SplineComponent.md#getupvectoratdistancealongspline)

#### Defined in

[ue/ue.d.ts:25998](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25998)

___

### GetUpVectorAtSplineInputKey

▸ **GetUpVectorAtSplineInputKey**(`InKey`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InKey` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetUpVectorAtSplineInputKey](ue_ue.SplineComponent.md#getupvectoratsplineinputkey)

#### Defined in

[ue/ue.d.ts:25999](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25999)

___

### GetUpVectorAtSplinePoint

▸ **GetUpVectorAtSplinePoint**(`PointIndex`, `CoordinateSpace`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetUpVectorAtSplinePoint](ue_ue.SplineComponent.md#getupvectoratsplinepoint)

#### Defined in

[ue/ue.d.ts:26000](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26000)

___

### GetUpVectorAtTime

▸ **GetUpVectorAtTime**(`Time`, `CoordinateSpace`, `bUseConstantVelocity?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | `number` |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUseConstantVelocity?` | `boolean` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetUpVectorAtTime](ue_ue.SplineComponent.md#getupvectorattime)

#### Defined in

[ue/ue.d.ts:26001](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26001)

___

### GetVectorPropertyAtSplineInputKey

▸ **GetVectorPropertyAtSplineInputKey**(`InKey`, `PropertyName`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InKey` | `number` |
| `PropertyName` | `string` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetVectorPropertyAtSplineInputKey](ue_ue.SplineComponent.md#getvectorpropertyatsplineinputkey)

#### Defined in

[ue/ue.d.ts:26002](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26002)

___

### GetVectorPropertyAtSplinePoint

▸ **GetVectorPropertyAtSplinePoint**(`Index`, `PropertyName`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |
| `PropertyName` | `string` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetVectorPropertyAtSplinePoint](ue_ue.SplineComponent.md#getvectorpropertyatsplinepoint)

#### Defined in

[ue/ue.d.ts:26003](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26003)

___

### GetWalkableSlopeOverride

▸ **GetWalkableSlopeOverride**(): [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Returns

[`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetWalkableSlopeOverride](ue_ue.SplineComponent.md#getwalkableslopeoverride)

#### Defined in

[ue/ue.d.ts:12688](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12688)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetWorld](ue_ue.SplineComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### GetWorldDirectionAtDistanceAlongSpline

▸ **GetWorldDirectionAtDistanceAlongSpline**(`Distance`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Distance` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetWorldDirectionAtDistanceAlongSpline](ue_ue.SplineComponent.md#getworlddirectionatdistancealongspline)

#### Defined in

[ue/ue.d.ts:26004](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26004)

___

### GetWorldDirectionAtTime

▸ **GetWorldDirectionAtTime**(`Time`, `bUseConstantVelocity?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | `number` |
| `bUseConstantVelocity?` | `boolean` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetWorldDirectionAtTime](ue_ue.SplineComponent.md#getworlddirectionattime)

#### Defined in

[ue/ue.d.ts:26005](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26005)

___

### GetWorldLocationAtDistanceAlongSpline

▸ **GetWorldLocationAtDistanceAlongSpline**(`Distance`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Distance` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetWorldLocationAtDistanceAlongSpline](ue_ue.SplineComponent.md#getworldlocationatdistancealongspline)

#### Defined in

[ue/ue.d.ts:26006](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26006)

___

### GetWorldLocationAtSplinePoint

▸ **GetWorldLocationAtSplinePoint**(`PointIndex`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetWorldLocationAtSplinePoint](ue_ue.SplineComponent.md#getworldlocationatsplinepoint)

#### Defined in

[ue/ue.d.ts:26007](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26007)

___

### GetWorldLocationAtTime

▸ **GetWorldLocationAtTime**(`Time`, `bUseConstantVelocity?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | `number` |
| `bUseConstantVelocity?` | `boolean` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetWorldLocationAtTime](ue_ue.SplineComponent.md#getworldlocationattime)

#### Defined in

[ue/ue.d.ts:26008](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26008)

___

### GetWorldRotationAtDistanceAlongSpline

▸ **GetWorldRotationAtDistanceAlongSpline**(`Distance`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Distance` | `number` |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetWorldRotationAtDistanceAlongSpline](ue_ue.SplineComponent.md#getworldrotationatdistancealongspline)

#### Defined in

[ue/ue.d.ts:26009](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26009)

___

### GetWorldRotationAtTime

▸ **GetWorldRotationAtTime**(`Time`, `bUseConstantVelocity?`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | `number` |
| `bUseConstantVelocity?` | `boolean` |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetWorldRotationAtTime](ue_ue.SplineComponent.md#getworldrotationattime)

#### Defined in

[ue/ue.d.ts:26010](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26010)

___

### GetWorldTangentAtDistanceAlongSpline

▸ **GetWorldTangentAtDistanceAlongSpline**(`Distance`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Distance` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetWorldTangentAtDistanceAlongSpline](ue_ue.SplineComponent.md#getworldtangentatdistancealongspline)

#### Defined in

[ue/ue.d.ts:26011](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26011)

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

[SplineComponent](ue_ue.SplineComponent.md).[IgnoreActorWhenMoving](ue_ue.SplineComponent.md#ignoreactorwhenmoving)

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

[SplineComponent](ue_ue.SplineComponent.md).[IgnoreComponentWhenMoving](ue_ue.SplineComponent.md#ignorecomponentwhenmoving)

#### Defined in

[ue/ue.d.ts:12690](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12690)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IsActive](ue_ue.SplineComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L313)

___

### IsAnyRigidBodyAwake

▸ **IsAnyRigidBodyAwake**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IsAnyRigidBodyAwake](ue_ue.SplineComponent.md#isanyrigidbodyawake)

#### Defined in

[ue/ue.d.ts:12691](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12691)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IsAnySimulatingPhysics](ue_ue.SplineComponent.md#isanysimulatingphysics)

#### Defined in

[ue/ue.d.ts:12915](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12915)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IsBeingDestroyed](ue_ue.SplineComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L314)

___

### IsClosedLoop

▸ **IsClosedLoop**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IsClosedLoop](ue_ue.SplineComponent.md#isclosedloop)

#### Defined in

[ue/ue.d.ts:26012](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26012)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IsComponentTickEnabled](ue_ue.SplineComponent.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L315)

___

### IsGravityEnabled

▸ **IsGravityEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IsGravityEnabled](ue_ue.SplineComponent.md#isgravityenabled)

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

[SplineComponent](ue_ue.SplineComponent.md).[IsOverlappingActor](ue_ue.SplineComponent.md#isoverlappingactor)

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

[SplineComponent](ue_ue.SplineComponent.md).[IsOverlappingComponent](ue_ue.SplineComponent.md#isoverlappingcomponent)

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

[SplineComponent](ue_ue.SplineComponent.md).[IsSimulatingPhysics](ue_ue.SplineComponent.md#issimulatingphysics)

#### Defined in

[ue/ue.d.ts:12916](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12916)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IsVisible](ue_ue.SplineComponent.md#isvisible)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_AddLocalOffset](ue_ue.SplineComponent.md#k2_addlocaloffset)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_AddLocalRotation](ue_ue.SplineComponent.md#k2_addlocalrotation)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_AddLocalTransform](ue_ue.SplineComponent.md#k2_addlocaltransform)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_AddRelativeLocation](ue_ue.SplineComponent.md#k2_addrelativelocation)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_AddRelativeRotation](ue_ue.SplineComponent.md#k2_addrelativerotation)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_AddWorldOffset](ue_ue.SplineComponent.md#k2_addworldoffset)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_AddWorldRotation](ue_ue.SplineComponent.md#k2_addworldrotation)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_AddWorldTransform](ue_ue.SplineComponent.md#k2_addworldtransform)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_AttachTo](ue_ue.SplineComponent.md#k2_attachto)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_AttachToComponent](ue_ue.SplineComponent.md#k2_attachtocomponent)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_BoxOverlapComponent](ue_ue.SplineComponent.md#k2_boxoverlapcomponent)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_DestroyComponent](ue_ue.SplineComponent.md#k2_destroycomponent)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_DetachFromComponent](ue_ue.SplineComponent.md#k2_detachfromcomponent)

#### Defined in

[ue/ue.d.ts:12928](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12928)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[K2_GetComponentLocation](ue_ue.SplineComponent.md#k2_getcomponentlocation)

#### Defined in

[ue/ue.d.ts:12929](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12929)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[K2_GetComponentRotation](ue_ue.SplineComponent.md#k2_getcomponentrotation)

#### Defined in

[ue/ue.d.ts:12930](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12930)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[K2_GetComponentScale](ue_ue.SplineComponent.md#k2_getcomponentscale)

#### Defined in

[ue/ue.d.ts:12931](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12931)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[K2_GetComponentToWorld](ue_ue.SplineComponent.md#k2_getcomponenttoworld)

#### Defined in

[ue/ue.d.ts:12932](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12932)

___

### K2\_IsCollisionEnabled

▸ **K2_IsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[K2_IsCollisionEnabled](ue_ue.SplineComponent.md#k2_iscollisionenabled)

#### Defined in

[ue/ue.d.ts:12696](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12696)

___

### K2\_IsPhysicsCollisionEnabled

▸ **K2_IsPhysicsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[K2_IsPhysicsCollisionEnabled](ue_ue.SplineComponent.md#k2_isphysicscollisionenabled)

#### Defined in

[ue/ue.d.ts:12697](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12697)

___

### K2\_IsQueryCollisionEnabled

▸ **K2_IsQueryCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[K2_IsQueryCollisionEnabled](ue_ue.SplineComponent.md#k2_isquerycollisionenabled)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_LineTraceComponent](ue_ue.SplineComponent.md#k2_linetracecomponent)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_SetRelativeLocation](ue_ue.SplineComponent.md#k2_setrelativelocation)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.SplineComponent.md#k2_setrelativelocationandrotation)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_SetRelativeRotation](ue_ue.SplineComponent.md#k2_setrelativerotation)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_SetRelativeTransform](ue_ue.SplineComponent.md#k2_setrelativetransform)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_SetWorldLocation](ue_ue.SplineComponent.md#k2_setworldlocation)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.SplineComponent.md#k2_setworldlocationandrotation)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_SetWorldRotation](ue_ue.SplineComponent.md#k2_setworldrotation)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_SetWorldTransform](ue_ue.SplineComponent.md#k2_setworldtransform)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_SphereOverlapComponent](ue_ue.SplineComponent.md#k2_sphereoverlapcomponent)

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

[SplineComponent](ue_ue.SplineComponent.md).[K2_SphereTraceComponent](ue_ue.SplineComponent.md#k2_spheretracecomponent)

#### Defined in

[ue/ue.d.ts:12701](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12701)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnRep_AttachChildren](ue_ue.SplineComponent.md#onrep_attachchildren)

#### Defined in

[ue/ue.d.ts:12941](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12941)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnRep_AttachParent](ue_ue.SplineComponent.md#onrep_attachparent)

#### Defined in

[ue/ue.d.ts:12942](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12942)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnRep_AttachSocketName](ue_ue.SplineComponent.md#onrep_attachsocketname)

#### Defined in

[ue/ue.d.ts:12943](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12943)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnRep_IsActive](ue_ue.SplineComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L317)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnRep_Transform](ue_ue.SplineComponent.md#onrep_transform)

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

[SplineComponent](ue_ue.SplineComponent.md).[OnRep_Visibility](ue_ue.SplineComponent.md#onrep_visibility)

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

[SplineComponent](ue_ue.SplineComponent.md).[PutRigidBodyToSleep](ue_ue.SplineComponent.md#putrigidbodytosleep)

#### Defined in

[ue/ue.d.ts:12702](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12702)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ReceiveBeginPlay](ue_ue.SplineComponent.md#receivebeginplay)

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

[SplineComponent](ue_ue.SplineComponent.md).[ReceiveEndPlay](ue_ue.SplineComponent.md#receiveendplay)

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

[SplineComponent](ue_ue.SplineComponent.md).[ReceiveTick](ue_ue.SplineComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[RegisterComponent](ue_ue.SplineComponent.md#registercomponent)

#### Defined in

[ue/ue.d.ts:321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L321)

___

### RemoveSplinePoint

▸ **RemoveSplinePoint**(`Index`, `bUpdateSpline?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |
| `bUpdateSpline?` | `boolean` |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[RemoveSplinePoint](ue_ue.SplineComponent.md#removesplinepoint)

#### Defined in

[ue/ue.d.ts:26013](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26013)

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

[SplineComponent](ue_ue.SplineComponent.md).[RemoveTickPrerequisiteActor](ue_ue.SplineComponent.md#removetickprerequisiteactor)

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

[SplineComponent](ue_ue.SplineComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.SplineComponent.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L323)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ResetRelativeTransform](ue_ue.SplineComponent.md#resetrelativetransform)

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

[SplineComponent](ue_ue.SplineComponent.md).[ScaleByMomentOfInertia](ue_ue.SplineComponent.md#scalebymomentofinertia)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetAbsolute](ue_ue.SplineComponent.md#setabsolute)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetActive](ue_ue.SplineComponent.md#setactive)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetAllMassScale](ue_ue.SplineComponent.md#setallmassscale)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetAllPhysicsAngularVelocityInDegrees](ue_ue.SplineComponent.md#setallphysicsangularvelocityindegrees)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetAllPhysicsAngularVelocityInRadians](ue_ue.SplineComponent.md#setallphysicsangularvelocityinradians)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetAllPhysicsLinearVelocity](ue_ue.SplineComponent.md#setallphysicslinearvelocity)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetAllUseCCD](ue_ue.SplineComponent.md#setalluseccd)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetAngularDamping](ue_ue.SplineComponent.md#setangulardamping)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetAutoActivate](ue_ue.SplineComponent.md#setautoactivate)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetBoundsScale](ue_ue.SplineComponent.md#setboundsscale)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetCastInsetShadow](ue_ue.SplineComponent.md#setcastinsetshadow)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetCastShadow](ue_ue.SplineComponent.md#setcastshadow)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetCenterOfMass](ue_ue.SplineComponent.md#setcenterofmass)

#### Defined in

[ue/ue.d.ts:12713](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12713)

___

### SetClosedLoop

▸ **SetClosedLoop**(`bInClosedLoop`, `bUpdateSpline?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInClosedLoop` | `boolean` |
| `bUpdateSpline?` | `boolean` |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SetClosedLoop](ue_ue.SplineComponent.md#setclosedloop)

#### Defined in

[ue/ue.d.ts:26014](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26014)

___

### SetClosedLoopAtPosition

▸ **SetClosedLoopAtPosition**(`bInClosedLoop`, `Key`, `bUpdateSpline?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInClosedLoop` | `boolean` |
| `Key` | `number` |
| `bUpdateSpline?` | `boolean` |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SetClosedLoopAtPosition](ue_ue.SplineComponent.md#setclosedloopatposition)

#### Defined in

[ue/ue.d.ts:26015](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26015)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetCollisionEnabled](ue_ue.SplineComponent.md#setcollisionenabled)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetCollisionObjectType](ue_ue.SplineComponent.md#setcollisionobjecttype)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetCollisionProfileName](ue_ue.SplineComponent.md#setcollisionprofilename)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetCollisionResponseToAllChannels](ue_ue.SplineComponent.md#setcollisionresponsetoallchannels)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetCollisionResponseToChannel](ue_ue.SplineComponent.md#setcollisionresponsetochannel)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetComponentTickEnabled](ue_ue.SplineComponent.md#setcomponenttickenabled)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetComponentTickInterval](ue_ue.SplineComponent.md#setcomponenttickinterval)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetConstraintMode](ue_ue.SplineComponent.md#setconstraintmode)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetCullDistance](ue_ue.SplineComponent.md#setculldistance)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetCustomDepthStencilValue](ue_ue.SplineComponent.md#setcustomdepthstencilvalue)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetCustomDepthStencilWriteMask](ue_ue.SplineComponent.md#setcustomdepthstencilwritemask)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetCustomPrimitiveDataFloat](ue_ue.SplineComponent.md#setcustomprimitivedatafloat)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetCustomPrimitiveDataVector2](ue_ue.SplineComponent.md#setcustomprimitivedatavector2)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetCustomPrimitiveDataVector3](ue_ue.SplineComponent.md#setcustomprimitivedatavector3)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetCustomPrimitiveDataVector4](ue_ue.SplineComponent.md#setcustomprimitivedatavector4)

#### Defined in

[ue/ue.d.ts:12726](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12726)

___

### SetDefaultUpVector

▸ **SetDefaultUpVector**(`UpVector`, `CoordinateSpace`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `UpVector` | [`Vector`](ue_ue_s.Vector.md) |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SetDefaultUpVector](ue_ue.SplineComponent.md#setdefaultupvector)

#### Defined in

[ue/ue.d.ts:26016](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26016)

___

### SetDrawDebug

▸ **SetDrawDebug**(`bShow`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bShow` | `boolean` |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SetDrawDebug](ue_ue.SplineComponent.md#setdrawdebug)

#### Defined in

[ue/ue.d.ts:26017](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26017)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetEnableGravity](ue_ue.SplineComponent.md#setenablegravity)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetExcludeFromLightAttachmentGroup](ue_ue.SplineComponent.md#setexcludefromlightattachmentgroup)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetGenerateOverlapEvents](ue_ue.SplineComponent.md#setgenerateoverlapevents)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetHiddenInGame](ue_ue.SplineComponent.md#sethiddeningame)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetIsReplicated](ue_ue.SplineComponent.md#setisreplicated)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetLightAttachmentsAsGroup](ue_ue.SplineComponent.md#setlightattachmentsasgroup)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetLinearDamping](ue_ue.SplineComponent.md#setlineardamping)

#### Defined in

[ue/ue.d.ts:12731](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12731)

___

### SetLocationAtSplinePoint

▸ **SetLocationAtSplinePoint**(`PointIndex`, `InLocation`, `CoordinateSpace`, `bUpdateSpline?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `InLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUpdateSpline?` | `boolean` |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SetLocationAtSplinePoint](ue_ue.SplineComponent.md#setlocationatsplinepoint)

#### Defined in

[ue/ue.d.ts:26018](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26018)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetMassOverrideInKg](ue_ue.SplineComponent.md#setmassoverrideinkg)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetMassScale](ue_ue.SplineComponent.md#setmassscale)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetMaterial](ue_ue.SplineComponent.md#setmaterial)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetMaterialByName](ue_ue.SplineComponent.md#setmaterialbyname)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetMobility](ue_ue.SplineComponent.md#setmobility)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetNotifyRigidBodyCollision](ue_ue.SplineComponent.md#setnotifyrigidbodycollision)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetOnlyOwnerSee](ue_ue.SplineComponent.md#setonlyownersee)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetOwnerNoSee](ue_ue.SplineComponent.md#setownernosee)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetPhysMaterialOverride](ue_ue.SplineComponent.md#setphysmaterialoverride)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetPhysicsAngularVelocity](ue_ue.SplineComponent.md#setphysicsangularvelocity)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetPhysicsAngularVelocityInDegrees](ue_ue.SplineComponent.md#setphysicsangularvelocityindegrees)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetPhysicsAngularVelocityInRadians](ue_ue.SplineComponent.md#setphysicsangularvelocityinradians)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetPhysicsLinearVelocity](ue_ue.SplineComponent.md#setphysicslinearvelocity)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetPhysicsMaxAngularVelocity](ue_ue.SplineComponent.md#setphysicsmaxangularvelocity)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetPhysicsMaxAngularVelocityInDegrees](ue_ue.SplineComponent.md#setphysicsmaxangularvelocityindegrees)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetPhysicsMaxAngularVelocityInRadians](ue_ue.SplineComponent.md#setphysicsmaxangularvelocityinradians)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetReceivesDecals](ue_ue.SplineComponent.md#setreceivesdecals)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetRelativeScale3D](ue_ue.SplineComponent.md#setrelativescale3d)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetRenderCustomDepth](ue_ue.SplineComponent.md#setrendercustomdepth)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetRenderInMainPass](ue_ue.SplineComponent.md#setrenderinmainpass)

#### Defined in

[ue/ue.d.ts:12749](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12749)

___

### SetSelectedSplineSegmentColor

▸ **SetSelectedSplineSegmentColor**(`SegmentColor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SegmentColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SetSelectedSplineSegmentColor](ue_ue.SplineComponent.md#setselectedsplinesegmentcolor)

#### Defined in

[ue/ue.d.ts:26019](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26019)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.SplineComponent.md#setshouldupdatephysicsvolume)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetSimulatePhysics](ue_ue.SplineComponent.md#setsimulatephysics)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetSingleSampleShadowFromStationaryLights](ue_ue.SplineComponent.md#setsinglesampleshadowfromstationarylights)

#### Defined in

[ue/ue.d.ts:12751](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12751)

___

### SetSplineLocalPoints

▸ **SetSplineLocalPoints**(`Points`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Points` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SetSplineLocalPoints](ue_ue.SplineComponent.md#setsplinelocalpoints)

#### Defined in

[ue/ue.d.ts:26020](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26020)

___

### SetSplinePointType

▸ **SetSplinePointType**(`PointIndex`, `Type`, `bUpdateSpline?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `Type` | [`ESplinePointType`](../enums/ue_ue.ESplinePointType.md) |
| `bUpdateSpline?` | `boolean` |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SetSplinePointType](ue_ue.SplineComponent.md#setsplinepointtype)

#### Defined in

[ue/ue.d.ts:26022](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26022)

___

### SetSplinePoints

▸ **SetSplinePoints**(`Points`, `CoordinateSpace`, `bUpdateSpline?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Points` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUpdateSpline?` | `boolean` |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SetSplinePoints](ue_ue.SplineComponent.md#setsplinepoints)

#### Defined in

[ue/ue.d.ts:26021](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26021)

___

### SetSplineWorldPoints

▸ **SetSplineWorldPoints**(`Points`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Points` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SetSplineWorldPoints](ue_ue.SplineComponent.md#setsplineworldpoints)

#### Defined in

[ue/ue.d.ts:26023](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26023)

___

### SetTangentAtSplinePoint

▸ **SetTangentAtSplinePoint**(`PointIndex`, `InTangent`, `CoordinateSpace`, `bUpdateSpline?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `InTangent` | [`Vector`](ue_ue_s.Vector.md) |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUpdateSpline?` | `boolean` |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SetTangentAtSplinePoint](ue_ue.SplineComponent.md#settangentatsplinepoint)

#### Defined in

[ue/ue.d.ts:26024](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26024)

___

### SetTangentsAtSplinePoint

▸ **SetTangentsAtSplinePoint**(`PointIndex`, `InArriveTangent`, `InLeaveTangent`, `CoordinateSpace`, `bUpdateSpline?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `InArriveTangent` | [`Vector`](ue_ue_s.Vector.md) |
| `InLeaveTangent` | [`Vector`](ue_ue_s.Vector.md) |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUpdateSpline?` | `boolean` |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SetTangentsAtSplinePoint](ue_ue.SplineComponent.md#settangentsatsplinepoint)

#### Defined in

[ue/ue.d.ts:26025](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26025)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetTickGroup](ue_ue.SplineComponent.md#settickgroup)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetTickableWhenPaused](ue_ue.SplineComponent.md#settickablewhenpaused)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetTranslucentSortPriority](ue_ue.SplineComponent.md#settranslucentsortpriority)

#### Defined in

[ue/ue.d.ts:12752](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12752)

___

### SetUnselectedSplineSegmentColor

▸ **SetUnselectedSplineSegmentColor**(`SegmentColor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SegmentColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SetUnselectedSplineSegmentColor](ue_ue.SplineComponent.md#setunselectedsplinesegmentcolor)

#### Defined in

[ue/ue.d.ts:26026](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26026)

___

### SetUpVectorAtSplinePoint

▸ **SetUpVectorAtSplinePoint**(`PointIndex`, `InUpVector`, `CoordinateSpace`, `bUpdateSpline?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `InUpVector` | [`Vector`](ue_ue_s.Vector.md) |
| `CoordinateSpace` | [`ESplineCoordinateSpace`](../enums/ue_ue.ESplineCoordinateSpace.md) |
| `bUpdateSpline?` | `boolean` |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SetUpVectorAtSplinePoint](ue_ue.SplineComponent.md#setupvectoratsplinepoint)

#### Defined in

[ue/ue.d.ts:26027](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26027)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetUseCCD](ue_ue.SplineComponent.md#setuseccd)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetVisibility](ue_ue.SplineComponent.md#setvisibility)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetWalkableSlopeOverride](ue_ue.SplineComponent.md#setwalkableslopeoverride)

#### Defined in

[ue/ue.d.ts:12754](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12754)

___

### SetWorldLocationAtSplinePoint

▸ **SetWorldLocationAtSplinePoint**(`PointIndex`, `InLocation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointIndex` | `number` |
| `InLocation` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SetWorldLocationAtSplinePoint](ue_ue.SplineComponent.md#setworldlocationatsplinepoint)

#### Defined in

[ue/ue.d.ts:26028](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26028)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetWorldScale3D](ue_ue.SplineComponent.md#setworldscale3d)

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

[SplineComponent](ue_ue.SplineComponent.md).[SetupAttachment](ue_ue.SplineComponent.md#setupattachment)

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

[SplineComponent](ue_ue.SplineComponent.md).[SnapTo](ue_ue.SplineComponent.md#snapto)

#### Defined in

[ue/ue.d.ts:12955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12955)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ToggleActive](ue_ue.SplineComponent.md#toggleactive)

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

[SplineComponent](ue_ue.SplineComponent.md).[ToggleVisibility](ue_ue.SplineComponent.md#togglevisibility)

#### Defined in

[ue/ue.d.ts:12956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12956)

___

### UpdateSpline

▸ **UpdateSpline**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[UpdateSpline](ue_ue.SplineComponent.md#updatespline)

#### Defined in

[ue/ue.d.ts:26029](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26029)

___

### WakeAllRigidBodies

▸ **WakeAllRigidBodies**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[WakeAllRigidBodies](ue_ue.SplineComponent.md#wakeallrigidbodies)

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

[SplineComponent](ue_ue.SplineComponent.md).[WakeRigidBody](ue_ue.SplineComponent.md#wakerigidbody)

#### Defined in

[ue/ue.d.ts:12756](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12756)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PaperTerrainSplineComponent`](ue_ue.PaperTerrainSplineComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PaperTerrainSplineComponent`](ue_ue.PaperTerrainSplineComponent.md)

#### Overrides

[SplineComponent](ue_ue.SplineComponent.md).[Find](ue_ue.SplineComponent.md#find)

#### Defined in

[ue/ue.d.ts:54926](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54926)

___

### Load

▸ `Static` **Load**(`InName`): [`PaperTerrainSplineComponent`](ue_ue.PaperTerrainSplineComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PaperTerrainSplineComponent`](ue_ue.PaperTerrainSplineComponent.md)

#### Overrides

[SplineComponent](ue_ue.SplineComponent.md).[Load](ue_ue.SplineComponent.md#load)

#### Defined in

[ue/ue.d.ts:54927](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54927)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SplineComponent](ue_ue.SplineComponent.md).[StaticClass](ue_ue.SplineComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:54925](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54925)
