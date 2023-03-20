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

## Properties

### AlwaysLoadOnClient

• **AlwaysLoadOnClient**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AlwaysLoadOnClient](ue_ue.SplineComponent.md#alwaysloadonclient)

___

### AlwaysLoadOnServer

• **AlwaysLoadOnServer**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AlwaysLoadOnServer](ue_ue.SplineComponent.md#alwaysloadonserver)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AssetUserData](ue_ue.SplineComponent.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AttachChildren](ue_ue.SplineComponent.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AttachParent](ue_ue.SplineComponent.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[AttachSocketName](ue_ue.SplineComponent.md#attachsocketname)

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[BodyInstance](ue_ue.SplineComponent.md#bodyinstance)

___

### BoundsScale

• **BoundsScale**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[BoundsScale](ue_ue.SplineComponent.md#boundsscale)

___

### CachedMaxDrawDistance

• **CachedMaxDrawDistance**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CachedMaxDrawDistance](ue_ue.SplineComponent.md#cachedmaxdrawdistance)

___

### CanBeCharacterBase

• **CanBeCharacterBase**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CanBeCharacterBase](ue_ue.SplineComponent.md#canbecharacterbase)

___

### CanCharacterStepUpOn

• **CanCharacterStepUpOn**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CanCharacterStepUpOn](ue_ue.SplineComponent.md#cancharacterstepupon)

___

### CastShadow

• **CastShadow**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CastShadow](ue_ue.SplineComponent.md#castshadow)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ClientAttachedChildren](ue_ue.SplineComponent.md#clientattachedchildren)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ComponentTags](ue_ue.SplineComponent.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ComponentVelocity](ue_ue.SplineComponent.md#componentvelocity)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CreationMethod](ue_ue.SplineComponent.md#creationmethod)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CustomDepthStencilValue](ue_ue.SplineComponent.md#customdepthstencilvalue)

___

### CustomDepthStencilWriteMask

• **CustomDepthStencilWriteMask**: [`ERendererStencilMask`](../enums/ue_ue.ERendererStencilMask.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CustomDepthStencilWriteMask](ue_ue.SplineComponent.md#customdepthstencilwritemask)

___

### CustomPrimitiveData

• **CustomPrimitiveData**: [`CustomPrimitiveData`](ue_ue.CustomPrimitiveData.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CustomPrimitiveData](ue_ue.SplineComponent.md#customprimitivedata)

___

### DefaultUpVector

• **DefaultUpVector**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[DefaultUpVector](ue_ue.SplineComponent.md#defaultupvector)

___

### DepthPriorityGroup

• **DepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[DepthPriorityGroup](ue_ue.SplineComponent.md#depthprioritygroup)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[DetailMode](ue_ue.SplineComponent.md#detailmode)

___

### Duration

• **Duration**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[Duration](ue_ue.SplineComponent.md#duration)

___

### EditorSelectedSplineSegmentColor

• **EditorSelectedSplineSegmentColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[EditorSelectedSplineSegmentColor](ue_ue.SplineComponent.md#editorselectedsplinesegmentcolor)

___

### EditorUnselectedSplineSegmentColor

• **EditorUnselectedSplineSegmentColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[EditorUnselectedSplineSegmentColor](ue_ue.SplineComponent.md#editorunselectedsplinesegmentcolor)

___

### ExcludeForSpecificHLODLevels

• **ExcludeForSpecificHLODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ExcludeForSpecificHLODLevels](ue_ue.SplineComponent.md#excludeforspecifichlodlevels)

___

### IndirectLightingCacheQuality

• **IndirectLightingCacheQuality**: [`EIndirectLightingCacheQuality`](../enums/ue_ue.EIndirectLightingCacheQuality.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IndirectLightingCacheQuality](ue_ue.SplineComponent.md#indirectlightingcachequality)

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[LDMaxDrawDistance](ue_ue.SplineComponent.md#ldmaxdrawdistance)

___

### LODParentPrimitive

• **LODParentPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[LODParentPrimitive](ue_ue.SplineComponent.md#lodparentprimitive)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[LightingChannels](ue_ue.SplineComponent.md#lightingchannels)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[LightmapType](ue_ue.SplineComponent.md#lightmaptype)

___

### LoopPosition

• **LoopPosition**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[LoopPosition](ue_ue.SplineComponent.md#loopposition)

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[LpvBiasMultiplier](ue_ue.SplineComponent.md#lpvbiasmultiplier)

___

### MinDrawDistance

• **MinDrawDistance**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[MinDrawDistance](ue_ue.SplineComponent.md#mindrawdistance)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[Mobility](ue_ue.SplineComponent.md#mobility)

___

### MoveIgnoreActors

• **MoveIgnoreActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[MoveIgnoreActors](ue_ue.SplineComponent.md#moveignoreactors)

___

### MoveIgnoreComponents

• **MoveIgnoreComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[MoveIgnoreComponents](ue_ue.SplineComponent.md#moveignorecomponents)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnBeginCursorOver](ue_ue.SplineComponent.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnClicked](ue_ue.SplineComponent.md#onclicked)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnComponentActivated](ue_ue.SplineComponent.md#oncomponentactivated)

___

### OnComponentBeginOverlap

• **OnComponentBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`, `bFromSweep`: `boolean`, `SweepResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnComponentBeginOverlap](ue_ue.SplineComponent.md#oncomponentbeginoverlap)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnComponentDeactivated](ue_ue.SplineComponent.md#oncomponentdeactivated)

___

### OnComponentEndOverlap

• **OnComponentEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnComponentEndOverlap](ue_ue.SplineComponent.md#oncomponentendoverlap)

___

### OnComponentHit

• **OnComponentHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`HitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnComponentHit](ue_ue.SplineComponent.md#oncomponenthit)

___

### OnComponentSleep

• **OnComponentSleep**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SleepingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnComponentSleep](ue_ue.SplineComponent.md#oncomponentsleep)

___

### OnComponentWake

• **OnComponentWake**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`WakingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnComponentWake](ue_ue.SplineComponent.md#oncomponentwake)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnEndCursorOver](ue_ue.SplineComponent.md#onendcursorover)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnInputTouchBegin](ue_ue.SplineComponent.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnInputTouchEnd](ue_ue.SplineComponent.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnInputTouchEnter](ue_ue.SplineComponent.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnInputTouchLeave](ue_ue.SplineComponent.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnReleased](ue_ue.SplineComponent.md#onreleased)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[PhysicsVolume](ue_ue.SplineComponent.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.SplineComponent.md#physicsvolumechangeddelegate)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[PrimaryComponentTick](ue_ue.SplineComponent.md#primarycomponenttick)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[RelativeLocation](ue_ue.SplineComponent.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[RelativeRotation](ue_ue.SplineComponent.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[RelativeScale3D](ue_ue.SplineComponent.md#relativescale3d)

___

### ReparamStepsPerSegment

• **ReparamStepsPerSegment**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ReparamStepsPerSegment](ue_ue.SplineComponent.md#reparamstepspersegment)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[RuntimeVirtualTextures](ue_ue.SplineComponent.md#runtimevirtualtextures)

___

### ScaleVisualizationWidth

• **ScaleVisualizationWidth**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ScaleVisualizationWidth](ue_ue.SplineComponent.md#scalevisualizationwidth)

___

### SplineCurves

• **SplineCurves**: [`SplineCurves`](ue_ue.SplineCurves.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SplineCurves](ue_ue.SplineComponent.md#splinecurves)

___

### SplineInfo

• **SplineInfo**: [`InterpCurveVector`](ue_ue.InterpCurveVector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SplineInfo](ue_ue.SplineComponent.md#splineinfo)

___

### SplineReparamTable

• **SplineReparamTable**: [`InterpCurveFloat`](ue_ue.InterpCurveFloat.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SplineReparamTable](ue_ue.SplineComponent.md#splinereparamtable)

___

### SplineRotInfo

• **SplineRotInfo**: [`InterpCurveQuat`](ue_ue.InterpCurveQuat.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SplineRotInfo](ue_ue.SplineComponent.md#splinerotinfo)

___

### SplineScaleInfo

• **SplineScaleInfo**: [`InterpCurveVector`](ue_ue.InterpCurveVector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[SplineScaleInfo](ue_ue.SplineComponent.md#splinescaleinfo)

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[TranslucencySortPriority](ue_ue.SplineComponent.md#translucencysortpriority)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[UCSModifiedProperties](ue_ue.SplineComponent.md#ucsmodifiedproperties)

___

### ViewOwnerDepthPriorityGroup

• **ViewOwnerDepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ViewOwnerDepthPriorityGroup](ue_ue.SplineComponent.md#viewownerdepthprioritygroup)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[VirtualTextureCullMips](ue_ue.SplineComponent.md#virtualtexturecullmips)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[VirtualTextureLodBias](ue_ue.SplineComponent.md#virtualtexturelodbias)

___

### VirtualTextureMinCoverage

• **VirtualTextureMinCoverage**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[VirtualTextureMinCoverage](ue_ue.SplineComponent.md#virtualtexturemincoverage)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[VirtualTextureRenderPassType](ue_ue.SplineComponent.md#virtualtexturerenderpasstype)

___

### VisibilityId

• **VisibilityId**: `number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[VisibilityId](ue_ue.SplineComponent.md#visibilityid)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[__tid_ActorComponent__](ue_ue.SplineComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[__tid_Object__](ue_ue.SplineComponent.md#__tid_object__)

___

### \_\_tid\_PaperTerrainSplineComponent\_\_

• **\_\_tid\_PaperTerrainSplineComponent\_\_**: `boolean`

___

### \_\_tid\_PrimitiveComponent\_\_

• **\_\_tid\_PrimitiveComponent\_\_**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[__tid_PrimitiveComponent__](ue_ue.SplineComponent.md#__tid_primitivecomponent__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[__tid_SceneComponent__](ue_ue.SplineComponent.md#__tid_scenecomponent__)

___

### \_\_tid\_SplineComponent\_\_

• **\_\_tid\_SplineComponent\_\_**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[__tid_SplineComponent__](ue_ue.SplineComponent.md#__tid_splinecomponent__)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAbsoluteLocation](ue_ue.SplineComponent.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAbsoluteRotation](ue_ue.SplineComponent.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAbsoluteScale](ue_ue.SplineComponent.md#babsolutescale)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAffectDistanceFieldLighting](ue_ue.SplineComponent.md#baffectdistancefieldlighting)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAffectDynamicIndirectLighting](ue_ue.SplineComponent.md#baffectdynamicindirectlighting)

___

### bAllowCullDistanceVolume

• **bAllowCullDistanceVolume**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAllowCullDistanceVolume](ue_ue.SplineComponent.md#ballowculldistancevolume)

___

### bAllowDiscontinuousSpline

• **bAllowDiscontinuousSpline**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAllowDiscontinuousSpline](ue_ue.SplineComponent.md#ballowdiscontinuousspline)

___

### bAllowSplineEditingPerInstance

• **bAllowSplineEditingPerInstance**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAllowSplineEditingPerInstance](ue_ue.SplineComponent.md#ballowsplineeditingperinstance)

___

### bAlwaysCreatePhysicsState

• **bAlwaysCreatePhysicsState**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAlwaysCreatePhysicsState](ue_ue.SplineComponent.md#balwayscreatephysicsstate)

___

### bApplyImpulseOnDamage

• **bApplyImpulseOnDamage**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bApplyImpulseOnDamage](ue_ue.SplineComponent.md#bapplyimpulseondamage)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bAutoActivate](ue_ue.SplineComponent.md#bautoactivate)

___

### bBatchImpostersAsInstances

• **bBatchImpostersAsInstances**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bBatchImpostersAsInstances](ue_ue.SplineComponent.md#bbatchimpostersasinstances)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.SplineComponent.md#bboundschangetriggersstreamingdatarebuild)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCanEverAffectNavigation](ue_ue.SplineComponent.md#bcaneveraffectnavigation)

___

### bCastCinematicShadow

• **bCastCinematicShadow**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCastCinematicShadow](ue_ue.SplineComponent.md#bcastcinematicshadow)

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCastDynamicShadow](ue_ue.SplineComponent.md#bcastdynamicshadow)

___

### bCastFarShadow

• **bCastFarShadow**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCastFarShadow](ue_ue.SplineComponent.md#bcastfarshadow)

___

### bCastHiddenShadow

• **bCastHiddenShadow**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCastHiddenShadow](ue_ue.SplineComponent.md#bcasthiddenshadow)

___

### bCastInsetShadow

• **bCastInsetShadow**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCastInsetShadow](ue_ue.SplineComponent.md#bcastinsetshadow)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCastShadowAsTwoSided](ue_ue.SplineComponent.md#bcastshadowastwosided)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCastStaticShadow](ue_ue.SplineComponent.md#bcaststaticshadow)

___

### bCastVolumetricTranslucentShadow

• **bCastVolumetricTranslucentShadow**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCastVolumetricTranslucentShadow](ue_ue.SplineComponent.md#bcastvolumetrictranslucentshadow)

___

### bClosedLoop

• **bClosedLoop**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bClosedLoop](ue_ue.SplineComponent.md#bclosedloop)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bComponentToWorldUpdated](ue_ue.SplineComponent.md#bcomponenttoworldupdated)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bCreatedByConstructionScript](ue_ue.SplineComponent.md#bcreatedbyconstructionscript)

___

### bDrawDebug

• **bDrawDebug**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bDrawDebug](ue_ue.SplineComponent.md#bdrawdebug)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bEditableWhenInherited](ue_ue.SplineComponent.md#beditablewheninherited)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bEnableAutoLODGeneration](ue_ue.SplineComponent.md#benableautolodgeneration)

___

### bExcludeFromLightAttachmentGroup

• **bExcludeFromLightAttachmentGroup**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bExcludeFromLightAttachmentGroup](ue_ue.SplineComponent.md#bexcludefromlightattachmentgroup)

___

### bForceMipStreaming

• **bForceMipStreaming**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bForceMipStreaming](ue_ue.SplineComponent.md#bforcemipstreaming)

___

### bGenerateOverlapEvents

• **bGenerateOverlapEvents**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bGenerateOverlapEvents](ue_ue.SplineComponent.md#bgenerateoverlapevents)

___

### bHasCustomNavigableGeometry

• **bHasCustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bHasCustomNavigableGeometry](ue_ue.SplineComponent.md#bhascustomnavigablegeometry)

___

### bHasMotionBlurVelocityMeshes

• **bHasMotionBlurVelocityMeshes**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bHasMotionBlurVelocityMeshes](ue_ue.SplineComponent.md#bhasmotionblurvelocitymeshes)

___

### bHasPerInstanceHitProxies

• **bHasPerInstanceHitProxies**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bHasPerInstanceHitProxies](ue_ue.SplineComponent.md#bhasperinstancehitproxies)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bHiddenInGame](ue_ue.SplineComponent.md#bhiddeningame)

___

### bIgnoreRadialForce

• **bIgnoreRadialForce**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bIgnoreRadialForce](ue_ue.SplineComponent.md#bignoreradialforce)

___

### bIgnoreRadialImpulse

• **bIgnoreRadialImpulse**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bIgnoreRadialImpulse](ue_ue.SplineComponent.md#bignoreradialimpulse)

___

### bInputSplinePointsToConstructionScript

• **bInputSplinePointsToConstructionScript**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bInputSplinePointsToConstructionScript](ue_ue.SplineComponent.md#binputsplinepointstoconstructionscript)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bInstanceComponent](ue_ue.SplineComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bIsActive](ue_ue.SplineComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bIsEditorOnly](ue_ue.SplineComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bIsVisualizationComponent](ue_ue.SplineComponent.md#bisvisualizationcomponent)

___

### bLightAsIfStatic

• **bLightAsIfStatic**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bLightAsIfStatic](ue_ue.SplineComponent.md#blightasifstatic)

___

### bLightAttachmentsAsGroup

• **bLightAttachmentsAsGroup**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bLightAttachmentsAsGroup](ue_ue.SplineComponent.md#blightattachmentsasgroup)

___

### bLoopPositionOverride

• **bLoopPositionOverride**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bLoopPositionOverride](ue_ue.SplineComponent.md#blooppositionoverride)

___

### bModifiedByConstructionScript

• **bModifiedByConstructionScript**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bModifiedByConstructionScript](ue_ue.SplineComponent.md#bmodifiedbyconstructionscript)

___

### bMultiBodyOverlap

• **bMultiBodyOverlap**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bMultiBodyOverlap](ue_ue.SplineComponent.md#bmultibodyoverlap)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bNetAddressable](ue_ue.SplineComponent.md#bnetaddressable)

___

### bNeverDistanceCull

• **bNeverDistanceCull**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bNeverDistanceCull](ue_ue.SplineComponent.md#bneverdistancecull)

___

### bOnlyOwnerSee

• **bOnlyOwnerSee**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bOnlyOwnerSee](ue_ue.SplineComponent.md#bonlyownersee)

___

### bOwnerNoSee

• **bOwnerNoSee**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bOwnerNoSee](ue_ue.SplineComponent.md#bownernosee)

___

### bReceiveMobileCSMShadows

• **bReceiveMobileCSMShadows**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bReceiveMobileCSMShadows](ue_ue.SplineComponent.md#breceivemobilecsmshadows)

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bReceivesDecals](ue_ue.SplineComponent.md#breceivesdecals)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bRenderCustomDepth](ue_ue.SplineComponent.md#brendercustomdepth)

___

### bRenderInDepthPass

• **bRenderInDepthPass**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bRenderInDepthPass](ue_ue.SplineComponent.md#brenderindepthpass)

___

### bRenderInMainPass

• **bRenderInMainPass**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bRenderInMainPass](ue_ue.SplineComponent.md#brenderinmainpass)

___

### bReplicatePhysicsToAutonomousProxy

• **bReplicatePhysicsToAutonomousProxy**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bReplicatePhysicsToAutonomousProxy](ue_ue.SplineComponent.md#breplicatephysicstoautonomousproxy)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bReplicates](ue_ue.SplineComponent.md#breplicates)

___

### bReturnMaterialOnMove

• **bReturnMaterialOnMove**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bReturnMaterialOnMove](ue_ue.SplineComponent.md#breturnmaterialonmove)

___

### bSelectable

• **bSelectable**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bSelectable](ue_ue.SplineComponent.md#bselectable)

___

### bSelfShadowOnly

• **bSelfShadowOnly**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bSelfShadowOnly](ue_ue.SplineComponent.md#bselfshadowonly)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bShouldBeAttached](ue_ue.SplineComponent.md#bshouldbeattached)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.SplineComponent.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.SplineComponent.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.SplineComponent.md#bshouldupdatephysicsvolume)

___

### bShouldVisualizeScale

• **bShouldVisualizeScale**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bShouldVisualizeScale](ue_ue.SplineComponent.md#bshouldvisualizescale)

___

### bSingleSampleShadowFromStationaryLights

• **bSingleSampleShadowFromStationaryLights**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bSingleSampleShadowFromStationaryLights](ue_ue.SplineComponent.md#bsinglesampleshadowfromstationarylights)

___

### bSplineHasBeenEdited

• **bSplineHasBeenEdited**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bSplineHasBeenEdited](ue_ue.SplineComponent.md#bsplinehasbeenedited)

___

### bStationaryEndpoints

• **bStationaryEndpoints**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bStationaryEndpoints](ue_ue.SplineComponent.md#bstationaryendpoints)

___

### bTraceComplexOnMove

• **bTraceComplexOnMove**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bTraceComplexOnMove](ue_ue.SplineComponent.md#btracecomplexonmove)

___

### bTreatAsBackgroundForOcclusion

• **bTreatAsBackgroundForOcclusion**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bTreatAsBackgroundForOcclusion](ue_ue.SplineComponent.md#btreatasbackgroundforocclusion)

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bUseAsOccluder](ue_ue.SplineComponent.md#buseasoccluder)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bUseAttachParentBound](ue_ue.SplineComponent.md#buseattachparentbound)

___

### bUseEditorCompositing

• **bUseEditorCompositing**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bUseEditorCompositing](ue_ue.SplineComponent.md#buseeditorcompositing)

___

### bUseMaxLODAsImposter

• **bUseMaxLODAsImposter**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bUseMaxLODAsImposter](ue_ue.SplineComponent.md#busemaxlodasimposter)

___

### bUseViewOwnerDepthPriorityGroup

• **bUseViewOwnerDepthPriorityGroup**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bUseViewOwnerDepthPriorityGroup](ue_ue.SplineComponent.md#buseviewownerdepthprioritygroup)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bVisible](ue_ue.SplineComponent.md#bvisible)

___

### bVisibleInRayTracing

• **bVisibleInRayTracing**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bVisibleInRayTracing](ue_ue.SplineComponent.md#bvisibleinraytracing)

___

### bVisibleInReflectionCaptures

• **bVisibleInReflectionCaptures**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bVisibleInReflectionCaptures](ue_ue.SplineComponent.md#bvisibleinreflectioncaptures)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[bVisualizeComponent](ue_ue.SplineComponent.md#bvisualizecomponent)

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

___

### ClearMoveIgnoreActors

▸ **ClearMoveIgnoreActors**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ClearMoveIgnoreActors](ue_ue.SplineComponent.md#clearmoveignoreactors)

___

### ClearMoveIgnoreComponents

▸ **ClearMoveIgnoreComponents**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ClearMoveIgnoreComponents](ue_ue.SplineComponent.md#clearmoveignorecomponents)

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

___

### CopyArrayOfMoveIgnoreActors

▸ **CopyArrayOfMoveIgnoreActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CopyArrayOfMoveIgnoreActors](ue_ue.SplineComponent.md#copyarrayofmoveignoreactors)

___

### CopyArrayOfMoveIgnoreComponents

▸ **CopyArrayOfMoveIgnoreComponents**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[CopyArrayOfMoveIgnoreComponents](ue_ue.SplineComponent.md#copyarrayofmoveignorecomponents)

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

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[Deactivate](ue_ue.SplineComponent.md#deactivate)

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

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetAllSocketNames](ue_ue.SplineComponent.md#getallsocketnames)

___

### GetAngularDamping

▸ **GetAngularDamping**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetAngularDamping](ue_ue.SplineComponent.md#getangulardamping)

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

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetAttachParent](ue_ue.SplineComponent.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetAttachSocketName](ue_ue.SplineComponent.md#getattachsocketname)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetClass](ue_ue.SplineComponent.md#getclass)

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

___

### GetCollisionEnabled

▸ **GetCollisionEnabled**(): [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Returns

[`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetCollisionEnabled](ue_ue.SplineComponent.md#getcollisionenabled)

___

### GetCollisionObjectType

▸ **GetCollisionObjectType**(): [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Returns

[`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetCollisionObjectType](ue_ue.SplineComponent.md#getcollisionobjecttype)

___

### GetCollisionProfileName

▸ **GetCollisionProfileName**(): `string`

#### Returns

`string`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetCollisionProfileName](ue_ue.SplineComponent.md#getcollisionprofilename)

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

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetComponentTickInterval](ue_ue.SplineComponent.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetComponentVelocity](ue_ue.SplineComponent.md#getcomponentvelocity)

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

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetForwardVector](ue_ue.SplineComponent.md#getforwardvector)

___

### GetGenerateOverlapEvents

▸ **GetGenerateOverlapEvents**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetGenerateOverlapEvents](ue_ue.SplineComponent.md#getgenerateoverlapevents)

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

___

### GetLinearDamping

▸ **GetLinearDamping**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetLinearDamping](ue_ue.SplineComponent.md#getlineardamping)

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

___

### GetMass

▸ **GetMass**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetMass](ue_ue.SplineComponent.md#getmass)

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

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetName](ue_ue.SplineComponent.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetNumChildrenComponents](ue_ue.SplineComponent.md#getnumchildrencomponents)

___

### GetNumMaterials

▸ **GetNumMaterials**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetNumMaterials](ue_ue.SplineComponent.md#getnummaterials)

___

### GetNumberOfSplinePoints

▸ **GetNumberOfSplinePoints**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetNumberOfSplinePoints](ue_ue.SplineComponent.md#getnumberofsplinepoints)

___

### GetNumberOfSplineSegments

▸ **GetNumberOfSplineSegments**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetNumberOfSplineSegments](ue_ue.SplineComponent.md#getnumberofsplinesegments)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetOuter](ue_ue.SplineComponent.md#getouter)

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

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetOwner](ue_ue.SplineComponent.md#getowner)

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

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetPhysicsVolume](ue_ue.SplineComponent.md#getphysicsvolume)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetRelativeTransform](ue_ue.SplineComponent.md#getrelativetransform)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetRightVector](ue_ue.SplineComponent.md#getrightvector)

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

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.SplineComponent.md#getshouldupdatephysicsvolume)

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

___

### GetSplineLength

▸ **GetSplineLength**(): `number`

#### Returns

`number`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetSplineLength](ue_ue.SplineComponent.md#getsplinelength)

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

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetUpVector](ue_ue.SplineComponent.md#getupvector)

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

___

### GetWalkableSlopeOverride

▸ **GetWalkableSlopeOverride**(): [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Returns

[`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetWalkableSlopeOverride](ue_ue.SplineComponent.md#getwalkableslopeoverride)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[GetWorld](ue_ue.SplineComponent.md#getworld)

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

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IsActive](ue_ue.SplineComponent.md#isactive)

___

### IsAnyRigidBodyAwake

▸ **IsAnyRigidBodyAwake**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IsAnyRigidBodyAwake](ue_ue.SplineComponent.md#isanyrigidbodyawake)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IsAnySimulatingPhysics](ue_ue.SplineComponent.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IsBeingDestroyed](ue_ue.SplineComponent.md#isbeingdestroyed)

___

### IsClosedLoop

▸ **IsClosedLoop**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IsClosedLoop](ue_ue.SplineComponent.md#isclosedloop)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IsComponentTickEnabled](ue_ue.SplineComponent.md#iscomponenttickenabled)

___

### IsGravityEnabled

▸ **IsGravityEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IsGravityEnabled](ue_ue.SplineComponent.md#isgravityenabled)

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

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[IsVisible](ue_ue.SplineComponent.md#isvisible)

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

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[K2_GetComponentLocation](ue_ue.SplineComponent.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[K2_GetComponentRotation](ue_ue.SplineComponent.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[K2_GetComponentScale](ue_ue.SplineComponent.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[K2_GetComponentToWorld](ue_ue.SplineComponent.md#k2_getcomponenttoworld)

___

### K2\_IsCollisionEnabled

▸ **K2_IsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[K2_IsCollisionEnabled](ue_ue.SplineComponent.md#k2_iscollisionenabled)

___

### K2\_IsPhysicsCollisionEnabled

▸ **K2_IsPhysicsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[K2_IsPhysicsCollisionEnabled](ue_ue.SplineComponent.md#k2_isphysicscollisionenabled)

___

### K2\_IsQueryCollisionEnabled

▸ **K2_IsQueryCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[K2_IsQueryCollisionEnabled](ue_ue.SplineComponent.md#k2_isquerycollisionenabled)

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

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnRep_AttachChildren](ue_ue.SplineComponent.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnRep_AttachParent](ue_ue.SplineComponent.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnRep_AttachSocketName](ue_ue.SplineComponent.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnRep_IsActive](ue_ue.SplineComponent.md#onrep_isactive)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[OnRep_Transform](ue_ue.SplineComponent.md#onrep_transform)

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

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ReceiveBeginPlay](ue_ue.SplineComponent.md#receivebeginplay)

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

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[RegisterComponent](ue_ue.SplineComponent.md#registercomponent)

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

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ResetRelativeTransform](ue_ue.SplineComponent.md#resetrelativetransform)

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

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[ToggleActive](ue_ue.SplineComponent.md#toggleactive)

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

___

### UpdateSpline

▸ **UpdateSpline**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[UpdateSpline](ue_ue.SplineComponent.md#updatespline)

___

### WakeAllRigidBodies

▸ **WakeAllRigidBodies**(): `void`

#### Returns

`void`

#### Inherited from

[SplineComponent](ue_ue.SplineComponent.md).[WakeAllRigidBodies](ue_ue.SplineComponent.md#wakeallrigidbodies)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SplineComponent](ue_ue.SplineComponent.md).[StaticClass](ue_ue.SplineComponent.md#staticclass)
