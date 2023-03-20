[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VREditorCameraWidgetComponent

# Class: VREditorCameraWidgetComponent

[ue/ue](../modules/ue_ue.md).VREditorCameraWidgetComponent

## Hierarchy

- [`VREditorWidgetComponent`](ue_ue.VREditorWidgetComponent.md)

  ↳ **`VREditorCameraWidgetComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.VREditorCameraWidgetComponent.md#constructor)

### Properties

- [AlwaysLoadOnClient](ue_ue.VREditorCameraWidgetComponent.md#alwaysloadonclient)
- [AlwaysLoadOnServer](ue_ue.VREditorCameraWidgetComponent.md#alwaysloadonserver)
- [AssetUserData](ue_ue.VREditorCameraWidgetComponent.md#assetuserdata)
- [AttachChildren](ue_ue.VREditorCameraWidgetComponent.md#attachchildren)
- [AttachParent](ue_ue.VREditorCameraWidgetComponent.md#attachparent)
- [AttachSocketName](ue_ue.VREditorCameraWidgetComponent.md#attachsocketname)
- [BackgroundColor](ue_ue.VREditorCameraWidgetComponent.md#backgroundcolor)
- [BlendMode](ue_ue.VREditorCameraWidgetComponent.md#blendmode)
- [BodyInstance](ue_ue.VREditorCameraWidgetComponent.md#bodyinstance)
- [BodySetup](ue_ue.VREditorCameraWidgetComponent.md#bodysetup)
- [BoundsScale](ue_ue.VREditorCameraWidgetComponent.md#boundsscale)
- [CachedMaxDrawDistance](ue_ue.VREditorCameraWidgetComponent.md#cachedmaxdrawdistance)
- [CanBeCharacterBase](ue_ue.VREditorCameraWidgetComponent.md#canbecharacterbase)
- [CanCharacterStepUpOn](ue_ue.VREditorCameraWidgetComponent.md#cancharacterstepupon)
- [CastShadow](ue_ue.VREditorCameraWidgetComponent.md#castshadow)
- [ClientAttachedChildren](ue_ue.VREditorCameraWidgetComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.VREditorCameraWidgetComponent.md#componenttags)
- [ComponentVelocity](ue_ue.VREditorCameraWidgetComponent.md#componentvelocity)
- [CreationMethod](ue_ue.VREditorCameraWidgetComponent.md#creationmethod)
- [CurrentDrawSize](ue_ue.VREditorCameraWidgetComponent.md#currentdrawsize)
- [CustomDepthStencilValue](ue_ue.VREditorCameraWidgetComponent.md#customdepthstencilvalue)
- [CustomDepthStencilWriteMask](ue_ue.VREditorCameraWidgetComponent.md#customdepthstencilwritemask)
- [CustomPrimitiveData](ue_ue.VREditorCameraWidgetComponent.md#customprimitivedata)
- [CylinderArcAngle](ue_ue.VREditorCameraWidgetComponent.md#cylinderarcangle)
- [DepthPriorityGroup](ue_ue.VREditorCameraWidgetComponent.md#depthprioritygroup)
- [DetailMode](ue_ue.VREditorCameraWidgetComponent.md#detailmode)
- [DrawSize](ue_ue.VREditorCameraWidgetComponent.md#drawsize)
- [DrawingPolicy](ue_ue.VREditorCameraWidgetComponent.md#drawingpolicy)
- [ExcludeForSpecificHLODLevels](ue_ue.VREditorCameraWidgetComponent.md#excludeforspecifichlodlevels)
- [GeometryMode](ue_ue.VREditorCameraWidgetComponent.md#geometrymode)
- [IndirectLightingCacheQuality](ue_ue.VREditorCameraWidgetComponent.md#indirectlightingcachequality)
- [LDMaxDrawDistance](ue_ue.VREditorCameraWidgetComponent.md#ldmaxdrawdistance)
- [LODParentPrimitive](ue_ue.VREditorCameraWidgetComponent.md#lodparentprimitive)
- [LayerZOrder](ue_ue.VREditorCameraWidgetComponent.md#layerzorder)
- [LightingChannels](ue_ue.VREditorCameraWidgetComponent.md#lightingchannels)
- [LightmapType](ue_ue.VREditorCameraWidgetComponent.md#lightmaptype)
- [LpvBiasMultiplier](ue_ue.VREditorCameraWidgetComponent.md#lpvbiasmultiplier)
- [MaskedMaterial](ue_ue.VREditorCameraWidgetComponent.md#maskedmaterial)
- [MaskedMaterial\_OneSided](ue_ue.VREditorCameraWidgetComponent.md#maskedmaterial_onesided)
- [MaterialInstance](ue_ue.VREditorCameraWidgetComponent.md#materialinstance)
- [MinDrawDistance](ue_ue.VREditorCameraWidgetComponent.md#mindrawdistance)
- [Mobility](ue_ue.VREditorCameraWidgetComponent.md#mobility)
- [MoveIgnoreActors](ue_ue.VREditorCameraWidgetComponent.md#moveignoreactors)
- [MoveIgnoreComponents](ue_ue.VREditorCameraWidgetComponent.md#moveignorecomponents)
- [OnBeginCursorOver](ue_ue.VREditorCameraWidgetComponent.md#onbegincursorover)
- [OnClicked](ue_ue.VREditorCameraWidgetComponent.md#onclicked)
- [OnComponentActivated](ue_ue.VREditorCameraWidgetComponent.md#oncomponentactivated)
- [OnComponentBeginOverlap](ue_ue.VREditorCameraWidgetComponent.md#oncomponentbeginoverlap)
- [OnComponentDeactivated](ue_ue.VREditorCameraWidgetComponent.md#oncomponentdeactivated)
- [OnComponentEndOverlap](ue_ue.VREditorCameraWidgetComponent.md#oncomponentendoverlap)
- [OnComponentHit](ue_ue.VREditorCameraWidgetComponent.md#oncomponenthit)
- [OnComponentSleep](ue_ue.VREditorCameraWidgetComponent.md#oncomponentsleep)
- [OnComponentWake](ue_ue.VREditorCameraWidgetComponent.md#oncomponentwake)
- [OnEndCursorOver](ue_ue.VREditorCameraWidgetComponent.md#onendcursorover)
- [OnInputTouchBegin](ue_ue.VREditorCameraWidgetComponent.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.VREditorCameraWidgetComponent.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.VREditorCameraWidgetComponent.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.VREditorCameraWidgetComponent.md#oninputtouchleave)
- [OnReleased](ue_ue.VREditorCameraWidgetComponent.md#onreleased)
- [OpacityFromTexture](ue_ue.VREditorCameraWidgetComponent.md#opacityfromtexture)
- [OpaqueMaterial](ue_ue.VREditorCameraWidgetComponent.md#opaquematerial)
- [OpaqueMaterial\_OneSided](ue_ue.VREditorCameraWidgetComponent.md#opaquematerial_onesided)
- [OverrideMaterials](ue_ue.VREditorCameraWidgetComponent.md#overridematerials)
- [OwnerPlayer](ue_ue.VREditorCameraWidgetComponent.md#ownerplayer)
- [PhysicsVolume](ue_ue.VREditorCameraWidgetComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.VREditorCameraWidgetComponent.md#physicsvolumechangeddelegate)
- [Pivot](ue_ue.VREditorCameraWidgetComponent.md#pivot)
- [PrimaryComponentTick](ue_ue.VREditorCameraWidgetComponent.md#primarycomponenttick)
- [RedrawTime](ue_ue.VREditorCameraWidgetComponent.md#redrawtime)
- [RelativeLocation](ue_ue.VREditorCameraWidgetComponent.md#relativelocation)
- [RelativeRotation](ue_ue.VREditorCameraWidgetComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.VREditorCameraWidgetComponent.md#relativescale3d)
- [RenderTarget](ue_ue.VREditorCameraWidgetComponent.md#rendertarget)
- [RuntimeVirtualTextures](ue_ue.VREditorCameraWidgetComponent.md#runtimevirtualtextures)
- [SharedLayerName](ue_ue.VREditorCameraWidgetComponent.md#sharedlayername)
- [Space](ue_ue.VREditorCameraWidgetComponent.md#space)
- [TickWhenOffscreen](ue_ue.VREditorCameraWidgetComponent.md#tickwhenoffscreen)
- [TimingPolicy](ue_ue.VREditorCameraWidgetComponent.md#timingpolicy)
- [TintColorAndOpacity](ue_ue.VREditorCameraWidgetComponent.md#tintcolorandopacity)
- [TranslucencySortPriority](ue_ue.VREditorCameraWidgetComponent.md#translucencysortpriority)
- [TranslucentMaterial](ue_ue.VREditorCameraWidgetComponent.md#translucentmaterial)
- [TranslucentMaterial\_OneSided](ue_ue.VREditorCameraWidgetComponent.md#translucentmaterial_onesided)
- [UCSModifiedProperties](ue_ue.VREditorCameraWidgetComponent.md#ucsmodifiedproperties)
- [ViewOwnerDepthPriorityGroup](ue_ue.VREditorCameraWidgetComponent.md#viewownerdepthprioritygroup)
- [VirtualTextureCullMips](ue_ue.VREditorCameraWidgetComponent.md#virtualtexturecullmips)
- [VirtualTextureLodBias](ue_ue.VREditorCameraWidgetComponent.md#virtualtexturelodbias)
- [VirtualTextureMinCoverage](ue_ue.VREditorCameraWidgetComponent.md#virtualtexturemincoverage)
- [VirtualTextureRenderPassType](ue_ue.VREditorCameraWidgetComponent.md#virtualtexturerenderpasstype)
- [VisibilityId](ue_ue.VREditorCameraWidgetComponent.md#visibilityid)
- [Widget](ue_ue.VREditorCameraWidgetComponent.md#widget)
- [WidgetClass](ue_ue.VREditorCameraWidgetComponent.md#widgetclass)
- [WindowVisibility](ue_ue.VREditorCameraWidgetComponent.md#windowvisibility)
- [\_\_tid\_ActorComponent\_\_](ue_ue.VREditorCameraWidgetComponent.md#__tid_actorcomponent__)
- [\_\_tid\_MeshComponent\_\_](ue_ue.VREditorCameraWidgetComponent.md#__tid_meshcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.VREditorCameraWidgetComponent.md#__tid_object__)
- [\_\_tid\_PrimitiveComponent\_\_](ue_ue.VREditorCameraWidgetComponent.md#__tid_primitivecomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.VREditorCameraWidgetComponent.md#__tid_scenecomponent__)
- [\_\_tid\_VREditorCameraWidgetComponent\_\_](ue_ue.VREditorCameraWidgetComponent.md#__tid_vreditorcamerawidgetcomponent__)
- [\_\_tid\_VREditorWidgetComponent\_\_](ue_ue.VREditorCameraWidgetComponent.md#__tid_vreditorwidgetcomponent__)
- [\_\_tid\_WidgetComponent\_\_](ue_ue.VREditorCameraWidgetComponent.md#__tid_widgetcomponent__)
- [bAbsoluteLocation](ue_ue.VREditorCameraWidgetComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.VREditorCameraWidgetComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.VREditorCameraWidgetComponent.md#babsolutescale)
- [bAddedToScreen](ue_ue.VREditorCameraWidgetComponent.md#baddedtoscreen)
- [bAffectDistanceFieldLighting](ue_ue.VREditorCameraWidgetComponent.md#baffectdistancefieldlighting)
- [bAffectDynamicIndirectLighting](ue_ue.VREditorCameraWidgetComponent.md#baffectdynamicindirectlighting)
- [bAllowCullDistanceVolume](ue_ue.VREditorCameraWidgetComponent.md#ballowculldistancevolume)
- [bAlwaysCreatePhysicsState](ue_ue.VREditorCameraWidgetComponent.md#balwayscreatephysicsstate)
- [bApplyGammaCorrection](ue_ue.VREditorCameraWidgetComponent.md#bapplygammacorrection)
- [bApplyImpulseOnDamage](ue_ue.VREditorCameraWidgetComponent.md#bapplyimpulseondamage)
- [bAutoActivate](ue_ue.VREditorCameraWidgetComponent.md#bautoactivate)
- [bBatchImpostersAsInstances](ue_ue.VREditorCameraWidgetComponent.md#bbatchimpostersasinstances)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.VREditorCameraWidgetComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.VREditorCameraWidgetComponent.md#bcaneveraffectnavigation)
- [bCastCinematicShadow](ue_ue.VREditorCameraWidgetComponent.md#bcastcinematicshadow)
- [bCastDynamicShadow](ue_ue.VREditorCameraWidgetComponent.md#bcastdynamicshadow)
- [bCastFarShadow](ue_ue.VREditorCameraWidgetComponent.md#bcastfarshadow)
- [bCastHiddenShadow](ue_ue.VREditorCameraWidgetComponent.md#bcasthiddenshadow)
- [bCastInsetShadow](ue_ue.VREditorCameraWidgetComponent.md#bcastinsetshadow)
- [bCastShadowAsTwoSided](ue_ue.VREditorCameraWidgetComponent.md#bcastshadowastwosided)
- [bCastStaticShadow](ue_ue.VREditorCameraWidgetComponent.md#bcaststaticshadow)
- [bCastVolumetricTranslucentShadow](ue_ue.VREditorCameraWidgetComponent.md#bcastvolumetrictranslucentshadow)
- [bComponentToWorldUpdated](ue_ue.VREditorCameraWidgetComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.VREditorCameraWidgetComponent.md#bcreatedbyconstructionscript)
- [bDrawAtDesiredSize](ue_ue.VREditorCameraWidgetComponent.md#bdrawatdesiredsize)
- [bEditTimeUsable](ue_ue.VREditorCameraWidgetComponent.md#bedittimeusable)
- [bEditableWhenInherited](ue_ue.VREditorCameraWidgetComponent.md#beditablewheninherited)
- [bEnableAutoLODGeneration](ue_ue.VREditorCameraWidgetComponent.md#benableautolodgeneration)
- [bEnableMaterialParameterCaching](ue_ue.VREditorCameraWidgetComponent.md#benablematerialparametercaching)
- [bExcludeFromLightAttachmentGroup](ue_ue.VREditorCameraWidgetComponent.md#bexcludefromlightattachmentgroup)
- [bForceMipStreaming](ue_ue.VREditorCameraWidgetComponent.md#bforcemipstreaming)
- [bGenerateOverlapEvents](ue_ue.VREditorCameraWidgetComponent.md#bgenerateoverlapevents)
- [bHasCustomNavigableGeometry](ue_ue.VREditorCameraWidgetComponent.md#bhascustomnavigablegeometry)
- [bHasEverDrawn](ue_ue.VREditorCameraWidgetComponent.md#bhaseverdrawn)
- [bHasMotionBlurVelocityMeshes](ue_ue.VREditorCameraWidgetComponent.md#bhasmotionblurvelocitymeshes)
- [bHasPerInstanceHitProxies](ue_ue.VREditorCameraWidgetComponent.md#bhasperinstancehitproxies)
- [bHiddenInGame](ue_ue.VREditorCameraWidgetComponent.md#bhiddeningame)
- [bIgnoreRadialForce](ue_ue.VREditorCameraWidgetComponent.md#bignoreradialforce)
- [bIgnoreRadialImpulse](ue_ue.VREditorCameraWidgetComponent.md#bignoreradialimpulse)
- [bInstanceComponent](ue_ue.VREditorCameraWidgetComponent.md#binstancecomponent)
- [bIsActive](ue_ue.VREditorCameraWidgetComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.VREditorCameraWidgetComponent.md#biseditoronly)
- [bIsHovering](ue_ue.VREditorCameraWidgetComponent.md#bishovering)
- [bIsTwoSided](ue_ue.VREditorCameraWidgetComponent.md#bistwosided)
- [bIsVisualizationComponent](ue_ue.VREditorCameraWidgetComponent.md#bisvisualizationcomponent)
- [bLightAsIfStatic](ue_ue.VREditorCameraWidgetComponent.md#blightasifstatic)
- [bLightAttachmentsAsGroup](ue_ue.VREditorCameraWidgetComponent.md#blightattachmentsasgroup)
- [bManuallyRedraw](ue_ue.VREditorCameraWidgetComponent.md#bmanuallyredraw)
- [bMultiBodyOverlap](ue_ue.VREditorCameraWidgetComponent.md#bmultibodyoverlap)
- [bNetAddressable](ue_ue.VREditorCameraWidgetComponent.md#bnetaddressable)
- [bNeverDistanceCull](ue_ue.VREditorCameraWidgetComponent.md#bneverdistancecull)
- [bOnlyOwnerSee](ue_ue.VREditorCameraWidgetComponent.md#bonlyownersee)
- [bOwnerNoSee](ue_ue.VREditorCameraWidgetComponent.md#bownernosee)
- [bReceiveHardwareInput](ue_ue.VREditorCameraWidgetComponent.md#breceivehardwareinput)
- [bReceiveMobileCSMShadows](ue_ue.VREditorCameraWidgetComponent.md#breceivemobilecsmshadows)
- [bReceivesDecals](ue_ue.VREditorCameraWidgetComponent.md#breceivesdecals)
- [bRedrawRequested](ue_ue.VREditorCameraWidgetComponent.md#bredrawrequested)
- [bRenderCustomDepth](ue_ue.VREditorCameraWidgetComponent.md#brendercustomdepth)
- [bRenderInDepthPass](ue_ue.VREditorCameraWidgetComponent.md#brenderindepthpass)
- [bRenderInMainPass](ue_ue.VREditorCameraWidgetComponent.md#brenderinmainpass)
- [bReplicatePhysicsToAutonomousProxy](ue_ue.VREditorCameraWidgetComponent.md#breplicatephysicstoautonomousproxy)
- [bReplicates](ue_ue.VREditorCameraWidgetComponent.md#breplicates)
- [bReturnMaterialOnMove](ue_ue.VREditorCameraWidgetComponent.md#breturnmaterialonmove)
- [bSelectable](ue_ue.VREditorCameraWidgetComponent.md#bselectable)
- [bSelfShadowOnly](ue_ue.VREditorCameraWidgetComponent.md#bselfshadowonly)
- [bShouldBeAttached](ue_ue.VREditorCameraWidgetComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.VREditorCameraWidgetComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.VREditorCameraWidgetComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.VREditorCameraWidgetComponent.md#bshouldupdatephysicsvolume)
- [bSingleSampleShadowFromStationaryLights](ue_ue.VREditorCameraWidgetComponent.md#bsinglesampleshadowfromstationarylights)
- [bTraceComplexOnMove](ue_ue.VREditorCameraWidgetComponent.md#btracecomplexonmove)
- [bTreatAsBackgroundForOcclusion](ue_ue.VREditorCameraWidgetComponent.md#btreatasbackgroundforocclusion)
- [bUseAsOccluder](ue_ue.VREditorCameraWidgetComponent.md#buseasoccluder)
- [bUseAttachParentBound](ue_ue.VREditorCameraWidgetComponent.md#buseattachparentbound)
- [bUseEditorCompositing](ue_ue.VREditorCameraWidgetComponent.md#buseeditorcompositing)
- [bUseMaxLODAsImposter](ue_ue.VREditorCameraWidgetComponent.md#busemaxlodasimposter)
- [bUseViewOwnerDepthPriorityGroup](ue_ue.VREditorCameraWidgetComponent.md#buseviewownerdepthprioritygroup)
- [bVisible](ue_ue.VREditorCameraWidgetComponent.md#bvisible)
- [bVisibleInRayTracing](ue_ue.VREditorCameraWidgetComponent.md#bvisibleinraytracing)
- [bVisibleInReflectionCaptures](ue_ue.VREditorCameraWidgetComponent.md#bvisibleinreflectioncaptures)
- [bVisualizeComponent](ue_ue.VREditorCameraWidgetComponent.md#bvisualizecomponent)
- [bWindowFocusable](ue_ue.VREditorCameraWidgetComponent.md#bwindowfocusable)

### Methods

- [Activate](ue_ue.VREditorCameraWidgetComponent.md#activate)
- [AddAngularImpulse](ue_ue.VREditorCameraWidgetComponent.md#addangularimpulse)
- [AddAngularImpulseInDegrees](ue_ue.VREditorCameraWidgetComponent.md#addangularimpulseindegrees)
- [AddAngularImpulseInRadians](ue_ue.VREditorCameraWidgetComponent.md#addangularimpulseinradians)
- [AddForce](ue_ue.VREditorCameraWidgetComponent.md#addforce)
- [AddForceAtLocation](ue_ue.VREditorCameraWidgetComponent.md#addforceatlocation)
- [AddForceAtLocationLocal](ue_ue.VREditorCameraWidgetComponent.md#addforceatlocationlocal)
- [AddImpulse](ue_ue.VREditorCameraWidgetComponent.md#addimpulse)
- [AddImpulseAtLocation](ue_ue.VREditorCameraWidgetComponent.md#addimpulseatlocation)
- [AddRadialForce](ue_ue.VREditorCameraWidgetComponent.md#addradialforce)
- [AddRadialImpulse](ue_ue.VREditorCameraWidgetComponent.md#addradialimpulse)
- [AddTickPrerequisiteActor](ue_ue.VREditorCameraWidgetComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.VREditorCameraWidgetComponent.md#addtickprerequisitecomponent)
- [AddTorque](ue_ue.VREditorCameraWidgetComponent.md#addtorque)
- [AddTorqueInDegrees](ue_ue.VREditorCameraWidgetComponent.md#addtorqueindegrees)
- [AddTorqueInRadians](ue_ue.VREditorCameraWidgetComponent.md#addtorqueinradians)
- [CanCharacterStepUp](ue_ue.VREditorCameraWidgetComponent.md#cancharacterstepup)
- [ClearMoveIgnoreActors](ue_ue.VREditorCameraWidgetComponent.md#clearmoveignoreactors)
- [ClearMoveIgnoreComponents](ue_ue.VREditorCameraWidgetComponent.md#clearmoveignorecomponents)
- [ComponentHasTag](ue_ue.VREditorCameraWidgetComponent.md#componenthastag)
- [CopyArrayOfMoveIgnoreActors](ue_ue.VREditorCameraWidgetComponent.md#copyarrayofmoveignoreactors)
- [CopyArrayOfMoveIgnoreComponents](ue_ue.VREditorCameraWidgetComponent.md#copyarrayofmoveignorecomponents)
- [CreateAndSetMaterialInstanceDynamic](ue_ue.VREditorCameraWidgetComponent.md#createandsetmaterialinstancedynamic)
- [CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.VREditorCameraWidgetComponent.md#createandsetmaterialinstancedynamicfrommaterial)
- [CreateDefaultSubobject](ue_ue.VREditorCameraWidgetComponent.md#createdefaultsubobject)
- [CreateDynamicMaterialInstance](ue_ue.VREditorCameraWidgetComponent.md#createdynamicmaterialinstance)
- [Deactivate](ue_ue.VREditorCameraWidgetComponent.md#deactivate)
- [DetachFromParent](ue_ue.VREditorCameraWidgetComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.VREditorCameraWidgetComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.VREditorCameraWidgetComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.VREditorCameraWidgetComponent.md#getallsocketnames)
- [GetAngularDamping](ue_ue.VREditorCameraWidgetComponent.md#getangulardamping)
- [GetAttachParent](ue_ue.VREditorCameraWidgetComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.VREditorCameraWidgetComponent.md#getattachsocketname)
- [GetCenterOfMass](ue_ue.VREditorCameraWidgetComponent.md#getcenterofmass)
- [GetChildComponent](ue_ue.VREditorCameraWidgetComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.VREditorCameraWidgetComponent.md#getchildrencomponents)
- [GetClass](ue_ue.VREditorCameraWidgetComponent.md#getclass)
- [GetClosestPointOnCollision](ue_ue.VREditorCameraWidgetComponent.md#getclosestpointoncollision)
- [GetCollisionEnabled](ue_ue.VREditorCameraWidgetComponent.md#getcollisionenabled)
- [GetCollisionObjectType](ue_ue.VREditorCameraWidgetComponent.md#getcollisionobjecttype)
- [GetCollisionProfileName](ue_ue.VREditorCameraWidgetComponent.md#getcollisionprofilename)
- [GetCollisionResponseToChannel](ue_ue.VREditorCameraWidgetComponent.md#getcollisionresponsetochannel)
- [GetComponentTickInterval](ue_ue.VREditorCameraWidgetComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.VREditorCameraWidgetComponent.md#getcomponentvelocity)
- [GetCurrentDrawSize](ue_ue.VREditorCameraWidgetComponent.md#getcurrentdrawsize)
- [GetCylinderArcAngle](ue_ue.VREditorCameraWidgetComponent.md#getcylinderarcangle)
- [GetDrawAtDesiredSize](ue_ue.VREditorCameraWidgetComponent.md#getdrawatdesiredsize)
- [GetDrawSize](ue_ue.VREditorCameraWidgetComponent.md#getdrawsize)
- [GetForwardVector](ue_ue.VREditorCameraWidgetComponent.md#getforwardvector)
- [GetGenerateOverlapEvents](ue_ue.VREditorCameraWidgetComponent.md#getgenerateoverlapevents)
- [GetGeometryMode](ue_ue.VREditorCameraWidgetComponent.md#getgeometrymode)
- [GetInertiaTensor](ue_ue.VREditorCameraWidgetComponent.md#getinertiatensor)
- [GetLinearDamping](ue_ue.VREditorCameraWidgetComponent.md#getlineardamping)
- [GetManuallyRedraw](ue_ue.VREditorCameraWidgetComponent.md#getmanuallyredraw)
- [GetMass](ue_ue.VREditorCameraWidgetComponent.md#getmass)
- [GetMassScale](ue_ue.VREditorCameraWidgetComponent.md#getmassscale)
- [GetMaterial](ue_ue.VREditorCameraWidgetComponent.md#getmaterial)
- [GetMaterialFromCollisionFaceIndex](ue_ue.VREditorCameraWidgetComponent.md#getmaterialfromcollisionfaceindex)
- [GetMaterialIndex](ue_ue.VREditorCameraWidgetComponent.md#getmaterialindex)
- [GetMaterialInstance](ue_ue.VREditorCameraWidgetComponent.md#getmaterialinstance)
- [GetMaterialSlotNames](ue_ue.VREditorCameraWidgetComponent.md#getmaterialslotnames)
- [GetMaterials](ue_ue.VREditorCameraWidgetComponent.md#getmaterials)
- [GetName](ue_ue.VREditorCameraWidgetComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.VREditorCameraWidgetComponent.md#getnumchildrencomponents)
- [GetNumMaterials](ue_ue.VREditorCameraWidgetComponent.md#getnummaterials)
- [GetOuter](ue_ue.VREditorCameraWidgetComponent.md#getouter)
- [GetOverlappingActors](ue_ue.VREditorCameraWidgetComponent.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.VREditorCameraWidgetComponent.md#getoverlappingcomponents)
- [GetOwner](ue_ue.VREditorCameraWidgetComponent.md#getowner)
- [GetOwnerPlayer](ue_ue.VREditorCameraWidgetComponent.md#getownerplayer)
- [GetParentComponents](ue_ue.VREditorCameraWidgetComponent.md#getparentcomponents)
- [GetPhysicsAngularVelocity](ue_ue.VREditorCameraWidgetComponent.md#getphysicsangularvelocity)
- [GetPhysicsAngularVelocityInDegrees](ue_ue.VREditorCameraWidgetComponent.md#getphysicsangularvelocityindegrees)
- [GetPhysicsAngularVelocityInRadians](ue_ue.VREditorCameraWidgetComponent.md#getphysicsangularvelocityinradians)
- [GetPhysicsLinearVelocity](ue_ue.VREditorCameraWidgetComponent.md#getphysicslinearvelocity)
- [GetPhysicsLinearVelocityAtPoint](ue_ue.VREditorCameraWidgetComponent.md#getphysicslinearvelocityatpoint)
- [GetPhysicsVolume](ue_ue.VREditorCameraWidgetComponent.md#getphysicsvolume)
- [GetPivot](ue_ue.VREditorCameraWidgetComponent.md#getpivot)
- [GetRedrawTime](ue_ue.VREditorCameraWidgetComponent.md#getredrawtime)
- [GetRelativeTransform](ue_ue.VREditorCameraWidgetComponent.md#getrelativetransform)
- [GetRenderTarget](ue_ue.VREditorCameraWidgetComponent.md#getrendertarget)
- [GetRightVector](ue_ue.VREditorCameraWidgetComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.VREditorCameraWidgetComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.VREditorCameraWidgetComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.VREditorCameraWidgetComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.VREditorCameraWidgetComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.VREditorCameraWidgetComponent.md#getsockettransform)
- [GetTickWhenOffscreen](ue_ue.VREditorCameraWidgetComponent.md#gettickwhenoffscreen)
- [GetTwoSided](ue_ue.VREditorCameraWidgetComponent.md#gettwosided)
- [GetUpVector](ue_ue.VREditorCameraWidgetComponent.md#getupvector)
- [GetUserWidgetObject](ue_ue.VREditorCameraWidgetComponent.md#getuserwidgetobject)
- [GetWalkableSlopeOverride](ue_ue.VREditorCameraWidgetComponent.md#getwalkableslopeoverride)
- [GetWidgetSpace](ue_ue.VREditorCameraWidgetComponent.md#getwidgetspace)
- [GetWindowFocusable](ue_ue.VREditorCameraWidgetComponent.md#getwindowfocusable)
- [GetWindowVisiblility](ue_ue.VREditorCameraWidgetComponent.md#getwindowvisiblility)
- [GetWorld](ue_ue.VREditorCameraWidgetComponent.md#getworld)
- [IgnoreActorWhenMoving](ue_ue.VREditorCameraWidgetComponent.md#ignoreactorwhenmoving)
- [IgnoreComponentWhenMoving](ue_ue.VREditorCameraWidgetComponent.md#ignorecomponentwhenmoving)
- [IsActive](ue_ue.VREditorCameraWidgetComponent.md#isactive)
- [IsAnyRigidBodyAwake](ue_ue.VREditorCameraWidgetComponent.md#isanyrigidbodyawake)
- [IsAnySimulatingPhysics](ue_ue.VREditorCameraWidgetComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.VREditorCameraWidgetComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.VREditorCameraWidgetComponent.md#iscomponenttickenabled)
- [IsGravityEnabled](ue_ue.VREditorCameraWidgetComponent.md#isgravityenabled)
- [IsMaterialSlotNameValid](ue_ue.VREditorCameraWidgetComponent.md#ismaterialslotnamevalid)
- [IsOverlappingActor](ue_ue.VREditorCameraWidgetComponent.md#isoverlappingactor)
- [IsOverlappingComponent](ue_ue.VREditorCameraWidgetComponent.md#isoverlappingcomponent)
- [IsSimulatingPhysics](ue_ue.VREditorCameraWidgetComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.VREditorCameraWidgetComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.VREditorCameraWidgetComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.VREditorCameraWidgetComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.VREditorCameraWidgetComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.VREditorCameraWidgetComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.VREditorCameraWidgetComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.VREditorCameraWidgetComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.VREditorCameraWidgetComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.VREditorCameraWidgetComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.VREditorCameraWidgetComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.VREditorCameraWidgetComponent.md#k2_attachtocomponent)
- [K2\_BoxOverlapComponent](ue_ue.VREditorCameraWidgetComponent.md#k2_boxoverlapcomponent)
- [K2\_DestroyComponent](ue_ue.VREditorCameraWidgetComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.VREditorCameraWidgetComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.VREditorCameraWidgetComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.VREditorCameraWidgetComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.VREditorCameraWidgetComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.VREditorCameraWidgetComponent.md#k2_getcomponenttoworld)
- [K2\_IsCollisionEnabled](ue_ue.VREditorCameraWidgetComponent.md#k2_iscollisionenabled)
- [K2\_IsPhysicsCollisionEnabled](ue_ue.VREditorCameraWidgetComponent.md#k2_isphysicscollisionenabled)
- [K2\_IsQueryCollisionEnabled](ue_ue.VREditorCameraWidgetComponent.md#k2_isquerycollisionenabled)
- [K2\_LineTraceComponent](ue_ue.VREditorCameraWidgetComponent.md#k2_linetracecomponent)
- [K2\_SetRelativeLocation](ue_ue.VREditorCameraWidgetComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.VREditorCameraWidgetComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.VREditorCameraWidgetComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.VREditorCameraWidgetComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.VREditorCameraWidgetComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.VREditorCameraWidgetComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.VREditorCameraWidgetComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.VREditorCameraWidgetComponent.md#k2_setworldtransform)
- [K2\_SphereOverlapComponent](ue_ue.VREditorCameraWidgetComponent.md#k2_sphereoverlapcomponent)
- [K2\_SphereTraceComponent](ue_ue.VREditorCameraWidgetComponent.md#k2_spheretracecomponent)
- [OnRep\_AttachChildren](ue_ue.VREditorCameraWidgetComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.VREditorCameraWidgetComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.VREditorCameraWidgetComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.VREditorCameraWidgetComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.VREditorCameraWidgetComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.VREditorCameraWidgetComponent.md#onrep_visibility)
- [PrestreamTextures](ue_ue.VREditorCameraWidgetComponent.md#prestreamtextures)
- [PutRigidBodyToSleep](ue_ue.VREditorCameraWidgetComponent.md#putrigidbodytosleep)
- [ReceiveBeginPlay](ue_ue.VREditorCameraWidgetComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.VREditorCameraWidgetComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.VREditorCameraWidgetComponent.md#receivetick)
- [RegisterComponent](ue_ue.VREditorCameraWidgetComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.VREditorCameraWidgetComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.VREditorCameraWidgetComponent.md#removetickprerequisitecomponent)
- [RequestRedraw](ue_ue.VREditorCameraWidgetComponent.md#requestredraw)
- [ResetRelativeTransform](ue_ue.VREditorCameraWidgetComponent.md#resetrelativetransform)
- [ScaleByMomentOfInertia](ue_ue.VREditorCameraWidgetComponent.md#scalebymomentofinertia)
- [SetAbsolute](ue_ue.VREditorCameraWidgetComponent.md#setabsolute)
- [SetActive](ue_ue.VREditorCameraWidgetComponent.md#setactive)
- [SetAllMassScale](ue_ue.VREditorCameraWidgetComponent.md#setallmassscale)
- [SetAllPhysicsAngularVelocityInDegrees](ue_ue.VREditorCameraWidgetComponent.md#setallphysicsangularvelocityindegrees)
- [SetAllPhysicsAngularVelocityInRadians](ue_ue.VREditorCameraWidgetComponent.md#setallphysicsangularvelocityinradians)
- [SetAllPhysicsLinearVelocity](ue_ue.VREditorCameraWidgetComponent.md#setallphysicslinearvelocity)
- [SetAllUseCCD](ue_ue.VREditorCameraWidgetComponent.md#setalluseccd)
- [SetAngularDamping](ue_ue.VREditorCameraWidgetComponent.md#setangulardamping)
- [SetAutoActivate](ue_ue.VREditorCameraWidgetComponent.md#setautoactivate)
- [SetBackgroundColor](ue_ue.VREditorCameraWidgetComponent.md#setbackgroundcolor)
- [SetBoundsScale](ue_ue.VREditorCameraWidgetComponent.md#setboundsscale)
- [SetCastInsetShadow](ue_ue.VREditorCameraWidgetComponent.md#setcastinsetshadow)
- [SetCastShadow](ue_ue.VREditorCameraWidgetComponent.md#setcastshadow)
- [SetCenterOfMass](ue_ue.VREditorCameraWidgetComponent.md#setcenterofmass)
- [SetCollisionEnabled](ue_ue.VREditorCameraWidgetComponent.md#setcollisionenabled)
- [SetCollisionObjectType](ue_ue.VREditorCameraWidgetComponent.md#setcollisionobjecttype)
- [SetCollisionProfileName](ue_ue.VREditorCameraWidgetComponent.md#setcollisionprofilename)
- [SetCollisionResponseToAllChannels](ue_ue.VREditorCameraWidgetComponent.md#setcollisionresponsetoallchannels)
- [SetCollisionResponseToChannel](ue_ue.VREditorCameraWidgetComponent.md#setcollisionresponsetochannel)
- [SetComponentTickEnabled](ue_ue.VREditorCameraWidgetComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.VREditorCameraWidgetComponent.md#setcomponenttickinterval)
- [SetConstraintMode](ue_ue.VREditorCameraWidgetComponent.md#setconstraintmode)
- [SetCullDistance](ue_ue.VREditorCameraWidgetComponent.md#setculldistance)
- [SetCustomDepthStencilValue](ue_ue.VREditorCameraWidgetComponent.md#setcustomdepthstencilvalue)
- [SetCustomDepthStencilWriteMask](ue_ue.VREditorCameraWidgetComponent.md#setcustomdepthstencilwritemask)
- [SetCustomPrimitiveDataFloat](ue_ue.VREditorCameraWidgetComponent.md#setcustomprimitivedatafloat)
- [SetCustomPrimitiveDataVector2](ue_ue.VREditorCameraWidgetComponent.md#setcustomprimitivedatavector2)
- [SetCustomPrimitiveDataVector3](ue_ue.VREditorCameraWidgetComponent.md#setcustomprimitivedatavector3)
- [SetCustomPrimitiveDataVector4](ue_ue.VREditorCameraWidgetComponent.md#setcustomprimitivedatavector4)
- [SetCylinderArcAngle](ue_ue.VREditorCameraWidgetComponent.md#setcylinderarcangle)
- [SetDrawAtDesiredSize](ue_ue.VREditorCameraWidgetComponent.md#setdrawatdesiredsize)
- [SetDrawSize](ue_ue.VREditorCameraWidgetComponent.md#setdrawsize)
- [SetEnableGravity](ue_ue.VREditorCameraWidgetComponent.md#setenablegravity)
- [SetExcludeFromLightAttachmentGroup](ue_ue.VREditorCameraWidgetComponent.md#setexcludefromlightattachmentgroup)
- [SetGenerateOverlapEvents](ue_ue.VREditorCameraWidgetComponent.md#setgenerateoverlapevents)
- [SetGeometryMode](ue_ue.VREditorCameraWidgetComponent.md#setgeometrymode)
- [SetHiddenInGame](ue_ue.VREditorCameraWidgetComponent.md#sethiddeningame)
- [SetIsReplicated](ue_ue.VREditorCameraWidgetComponent.md#setisreplicated)
- [SetLightAttachmentsAsGroup](ue_ue.VREditorCameraWidgetComponent.md#setlightattachmentsasgroup)
- [SetLinearDamping](ue_ue.VREditorCameraWidgetComponent.md#setlineardamping)
- [SetManuallyRedraw](ue_ue.VREditorCameraWidgetComponent.md#setmanuallyredraw)
- [SetMassOverrideInKg](ue_ue.VREditorCameraWidgetComponent.md#setmassoverrideinkg)
- [SetMassScale](ue_ue.VREditorCameraWidgetComponent.md#setmassscale)
- [SetMaterial](ue_ue.VREditorCameraWidgetComponent.md#setmaterial)
- [SetMaterialByName](ue_ue.VREditorCameraWidgetComponent.md#setmaterialbyname)
- [SetMobility](ue_ue.VREditorCameraWidgetComponent.md#setmobility)
- [SetNotifyRigidBodyCollision](ue_ue.VREditorCameraWidgetComponent.md#setnotifyrigidbodycollision)
- [SetOnlyOwnerSee](ue_ue.VREditorCameraWidgetComponent.md#setonlyownersee)
- [SetOwnerNoSee](ue_ue.VREditorCameraWidgetComponent.md#setownernosee)
- [SetOwnerPlayer](ue_ue.VREditorCameraWidgetComponent.md#setownerplayer)
- [SetPhysMaterialOverride](ue_ue.VREditorCameraWidgetComponent.md#setphysmaterialoverride)
- [SetPhysicsAngularVelocity](ue_ue.VREditorCameraWidgetComponent.md#setphysicsangularvelocity)
- [SetPhysicsAngularVelocityInDegrees](ue_ue.VREditorCameraWidgetComponent.md#setphysicsangularvelocityindegrees)
- [SetPhysicsAngularVelocityInRadians](ue_ue.VREditorCameraWidgetComponent.md#setphysicsangularvelocityinradians)
- [SetPhysicsLinearVelocity](ue_ue.VREditorCameraWidgetComponent.md#setphysicslinearvelocity)
- [SetPhysicsMaxAngularVelocity](ue_ue.VREditorCameraWidgetComponent.md#setphysicsmaxangularvelocity)
- [SetPhysicsMaxAngularVelocityInDegrees](ue_ue.VREditorCameraWidgetComponent.md#setphysicsmaxangularvelocityindegrees)
- [SetPhysicsMaxAngularVelocityInRadians](ue_ue.VREditorCameraWidgetComponent.md#setphysicsmaxangularvelocityinradians)
- [SetPivot](ue_ue.VREditorCameraWidgetComponent.md#setpivot)
- [SetReceivesDecals](ue_ue.VREditorCameraWidgetComponent.md#setreceivesdecals)
- [SetRedrawTime](ue_ue.VREditorCameraWidgetComponent.md#setredrawtime)
- [SetRelativeScale3D](ue_ue.VREditorCameraWidgetComponent.md#setrelativescale3d)
- [SetRenderCustomDepth](ue_ue.VREditorCameraWidgetComponent.md#setrendercustomdepth)
- [SetRenderInMainPass](ue_ue.VREditorCameraWidgetComponent.md#setrenderinmainpass)
- [SetScalarParameterValueOnMaterials](ue_ue.VREditorCameraWidgetComponent.md#setscalarparametervalueonmaterials)
- [SetShouldUpdatePhysicsVolume](ue_ue.VREditorCameraWidgetComponent.md#setshouldupdatephysicsvolume)
- [SetSimulatePhysics](ue_ue.VREditorCameraWidgetComponent.md#setsimulatephysics)
- [SetSingleSampleShadowFromStationaryLights](ue_ue.VREditorCameraWidgetComponent.md#setsinglesampleshadowfromstationarylights)
- [SetTickGroup](ue_ue.VREditorCameraWidgetComponent.md#settickgroup)
- [SetTickWhenOffscreen](ue_ue.VREditorCameraWidgetComponent.md#settickwhenoffscreen)
- [SetTickableWhenPaused](ue_ue.VREditorCameraWidgetComponent.md#settickablewhenpaused)
- [SetTintColorAndOpacity](ue_ue.VREditorCameraWidgetComponent.md#settintcolorandopacity)
- [SetTranslucentSortPriority](ue_ue.VREditorCameraWidgetComponent.md#settranslucentsortpriority)
- [SetTwoSided](ue_ue.VREditorCameraWidgetComponent.md#settwosided)
- [SetUseCCD](ue_ue.VREditorCameraWidgetComponent.md#setuseccd)
- [SetVectorParameterValueOnMaterials](ue_ue.VREditorCameraWidgetComponent.md#setvectorparametervalueonmaterials)
- [SetVisibility](ue_ue.VREditorCameraWidgetComponent.md#setvisibility)
- [SetWalkableSlopeOverride](ue_ue.VREditorCameraWidgetComponent.md#setwalkableslopeoverride)
- [SetWidget](ue_ue.VREditorCameraWidgetComponent.md#setwidget)
- [SetWidgetSpace](ue_ue.VREditorCameraWidgetComponent.md#setwidgetspace)
- [SetWindowFocusable](ue_ue.VREditorCameraWidgetComponent.md#setwindowfocusable)
- [SetWindowVisibility](ue_ue.VREditorCameraWidgetComponent.md#setwindowvisibility)
- [SetWorldScale3D](ue_ue.VREditorCameraWidgetComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.VREditorCameraWidgetComponent.md#setupattachment)
- [SnapTo](ue_ue.VREditorCameraWidgetComponent.md#snapto)
- [ToggleActive](ue_ue.VREditorCameraWidgetComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.VREditorCameraWidgetComponent.md#togglevisibility)
- [WakeAllRigidBodies](ue_ue.VREditorCameraWidgetComponent.md#wakeallrigidbodies)
- [WakeRigidBody](ue_ue.VREditorCameraWidgetComponent.md#wakerigidbody)
- [Find](ue_ue.VREditorCameraWidgetComponent.md#find)
- [Load](ue_ue.VREditorCameraWidgetComponent.md#load)
- [StaticClass](ue_ue.VREditorCameraWidgetComponent.md#staticclass)

## Constructors

### constructor

• **new VREditorCameraWidgetComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[constructor](ue_ue.VREditorWidgetComponent.md#constructor)

## Properties

### AlwaysLoadOnClient

• **AlwaysLoadOnClient**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AlwaysLoadOnClient](ue_ue.VREditorWidgetComponent.md#alwaysloadonclient)

___

### AlwaysLoadOnServer

• **AlwaysLoadOnServer**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AlwaysLoadOnServer](ue_ue.VREditorWidgetComponent.md#alwaysloadonserver)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AssetUserData](ue_ue.VREditorWidgetComponent.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AttachChildren](ue_ue.VREditorWidgetComponent.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AttachParent](ue_ue.VREditorWidgetComponent.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AttachSocketName](ue_ue.VREditorWidgetComponent.md#attachsocketname)

___

### BackgroundColor

• **BackgroundColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[BackgroundColor](ue_ue.VREditorWidgetComponent.md#backgroundcolor)

___

### BlendMode

• **BlendMode**: [`EWidgetBlendMode`](../enums/ue_ue.EWidgetBlendMode.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[BlendMode](ue_ue.VREditorWidgetComponent.md#blendmode)

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[BodyInstance](ue_ue.VREditorWidgetComponent.md#bodyinstance)

___

### BodySetup

• **BodySetup**: [`BodySetup`](ue_ue.BodySetup.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[BodySetup](ue_ue.VREditorWidgetComponent.md#bodysetup)

___

### BoundsScale

• **BoundsScale**: `number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[BoundsScale](ue_ue.VREditorWidgetComponent.md#boundsscale)

___

### CachedMaxDrawDistance

• **CachedMaxDrawDistance**: `number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[CachedMaxDrawDistance](ue_ue.VREditorWidgetComponent.md#cachedmaxdrawdistance)

___

### CanBeCharacterBase

• **CanBeCharacterBase**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[CanBeCharacterBase](ue_ue.VREditorWidgetComponent.md#canbecharacterbase)

___

### CanCharacterStepUpOn

• **CanCharacterStepUpOn**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[CanCharacterStepUpOn](ue_ue.VREditorWidgetComponent.md#cancharacterstepupon)

___

### CastShadow

• **CastShadow**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[CastShadow](ue_ue.VREditorWidgetComponent.md#castshadow)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[ClientAttachedChildren](ue_ue.VREditorWidgetComponent.md#clientattachedchildren)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[ComponentTags](ue_ue.VREditorWidgetComponent.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[ComponentVelocity](ue_ue.VREditorWidgetComponent.md#componentvelocity)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[CreationMethod](ue_ue.VREditorWidgetComponent.md#creationmethod)

___

### CurrentDrawSize

• **CurrentDrawSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[CurrentDrawSize](ue_ue.VREditorWidgetComponent.md#currentdrawsize)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[CustomDepthStencilValue](ue_ue.VREditorWidgetComponent.md#customdepthstencilvalue)

___

### CustomDepthStencilWriteMask

• **CustomDepthStencilWriteMask**: [`ERendererStencilMask`](../enums/ue_ue.ERendererStencilMask.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[CustomDepthStencilWriteMask](ue_ue.VREditorWidgetComponent.md#customdepthstencilwritemask)

___

### CustomPrimitiveData

• **CustomPrimitiveData**: [`CustomPrimitiveData`](ue_ue.CustomPrimitiveData.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[CustomPrimitiveData](ue_ue.VREditorWidgetComponent.md#customprimitivedata)

___

### CylinderArcAngle

• **CylinderArcAngle**: `number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[CylinderArcAngle](ue_ue.VREditorWidgetComponent.md#cylinderarcangle)

___

### DepthPriorityGroup

• **DepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[DepthPriorityGroup](ue_ue.VREditorWidgetComponent.md#depthprioritygroup)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[DetailMode](ue_ue.VREditorWidgetComponent.md#detailmode)

___

### DrawSize

• **DrawSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[DrawSize](ue_ue.VREditorWidgetComponent.md#drawsize)

___

### DrawingPolicy

• **DrawingPolicy**: [`EVREditorWidgetDrawingPolicy`](../enums/ue_ue.EVREditorWidgetDrawingPolicy.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[DrawingPolicy](ue_ue.VREditorWidgetComponent.md#drawingpolicy)

___

### ExcludeForSpecificHLODLevels

• **ExcludeForSpecificHLODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[ExcludeForSpecificHLODLevels](ue_ue.VREditorWidgetComponent.md#excludeforspecifichlodlevels)

___

### GeometryMode

• **GeometryMode**: [`EWidgetGeometryMode`](../enums/ue_ue.EWidgetGeometryMode.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GeometryMode](ue_ue.VREditorWidgetComponent.md#geometrymode)

___

### IndirectLightingCacheQuality

• **IndirectLightingCacheQuality**: [`EIndirectLightingCacheQuality`](../enums/ue_ue.EIndirectLightingCacheQuality.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[IndirectLightingCacheQuality](ue_ue.VREditorWidgetComponent.md#indirectlightingcachequality)

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[LDMaxDrawDistance](ue_ue.VREditorWidgetComponent.md#ldmaxdrawdistance)

___

### LODParentPrimitive

• **LODParentPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[LODParentPrimitive](ue_ue.VREditorWidgetComponent.md#lodparentprimitive)

___

### LayerZOrder

• **LayerZOrder**: `number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[LayerZOrder](ue_ue.VREditorWidgetComponent.md#layerzorder)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[LightingChannels](ue_ue.VREditorWidgetComponent.md#lightingchannels)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[LightmapType](ue_ue.VREditorWidgetComponent.md#lightmaptype)

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[LpvBiasMultiplier](ue_ue.VREditorWidgetComponent.md#lpvbiasmultiplier)

___

### MaskedMaterial

• **MaskedMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[MaskedMaterial](ue_ue.VREditorWidgetComponent.md#maskedmaterial)

___

### MaskedMaterial\_OneSided

• **MaskedMaterial\_OneSided**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[MaskedMaterial_OneSided](ue_ue.VREditorWidgetComponent.md#maskedmaterial_onesided)

___

### MaterialInstance

• **MaterialInstance**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[MaterialInstance](ue_ue.VREditorWidgetComponent.md#materialinstance)

___

### MinDrawDistance

• **MinDrawDistance**: `number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[MinDrawDistance](ue_ue.VREditorWidgetComponent.md#mindrawdistance)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[Mobility](ue_ue.VREditorWidgetComponent.md#mobility)

___

### MoveIgnoreActors

• **MoveIgnoreActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[MoveIgnoreActors](ue_ue.VREditorWidgetComponent.md#moveignoreactors)

___

### MoveIgnoreComponents

• **MoveIgnoreComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[MoveIgnoreComponents](ue_ue.VREditorWidgetComponent.md#moveignorecomponents)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnBeginCursorOver](ue_ue.VREditorWidgetComponent.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnClicked](ue_ue.VREditorWidgetComponent.md#onclicked)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnComponentActivated](ue_ue.VREditorWidgetComponent.md#oncomponentactivated)

___

### OnComponentBeginOverlap

• **OnComponentBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`, `bFromSweep`: `boolean`, `SweepResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnComponentBeginOverlap](ue_ue.VREditorWidgetComponent.md#oncomponentbeginoverlap)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnComponentDeactivated](ue_ue.VREditorWidgetComponent.md#oncomponentdeactivated)

___

### OnComponentEndOverlap

• **OnComponentEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`) => `void`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnComponentEndOverlap](ue_ue.VREditorWidgetComponent.md#oncomponentendoverlap)

___

### OnComponentHit

• **OnComponentHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`HitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnComponentHit](ue_ue.VREditorWidgetComponent.md#oncomponenthit)

___

### OnComponentSleep

• **OnComponentSleep**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SleepingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnComponentSleep](ue_ue.VREditorWidgetComponent.md#oncomponentsleep)

___

### OnComponentWake

• **OnComponentWake**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`WakingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnComponentWake](ue_ue.VREditorWidgetComponent.md#oncomponentwake)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnEndCursorOver](ue_ue.VREditorWidgetComponent.md#onendcursorover)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnInputTouchBegin](ue_ue.VREditorWidgetComponent.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnInputTouchEnd](ue_ue.VREditorWidgetComponent.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnInputTouchEnter](ue_ue.VREditorWidgetComponent.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnInputTouchLeave](ue_ue.VREditorWidgetComponent.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnReleased](ue_ue.VREditorWidgetComponent.md#onreleased)

___

### OpacityFromTexture

• **OpacityFromTexture**: `number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OpacityFromTexture](ue_ue.VREditorWidgetComponent.md#opacityfromtexture)

___

### OpaqueMaterial

• **OpaqueMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OpaqueMaterial](ue_ue.VREditorWidgetComponent.md#opaquematerial)

___

### OpaqueMaterial\_OneSided

• **OpaqueMaterial\_OneSided**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OpaqueMaterial_OneSided](ue_ue.VREditorWidgetComponent.md#opaquematerial_onesided)

___

### OverrideMaterials

• **OverrideMaterials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OverrideMaterials](ue_ue.VREditorWidgetComponent.md#overridematerials)

___

### OwnerPlayer

• **OwnerPlayer**: [`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OwnerPlayer](ue_ue.VREditorWidgetComponent.md#ownerplayer)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[PhysicsVolume](ue_ue.VREditorWidgetComponent.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.VREditorWidgetComponent.md#physicsvolumechangeddelegate)

___

### Pivot

• **Pivot**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[Pivot](ue_ue.VREditorWidgetComponent.md#pivot)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[PrimaryComponentTick](ue_ue.VREditorWidgetComponent.md#primarycomponenttick)

___

### RedrawTime

• **RedrawTime**: `number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[RedrawTime](ue_ue.VREditorWidgetComponent.md#redrawtime)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[RelativeLocation](ue_ue.VREditorWidgetComponent.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[RelativeRotation](ue_ue.VREditorWidgetComponent.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[RelativeScale3D](ue_ue.VREditorWidgetComponent.md#relativescale3d)

___

### RenderTarget

• **RenderTarget**: [`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[RenderTarget](ue_ue.VREditorWidgetComponent.md#rendertarget)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[RuntimeVirtualTextures](ue_ue.VREditorWidgetComponent.md#runtimevirtualtextures)

___

### SharedLayerName

• **SharedLayerName**: `string`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SharedLayerName](ue_ue.VREditorWidgetComponent.md#sharedlayername)

___

### Space

• **Space**: [`EWidgetSpace`](../enums/ue_ue.EWidgetSpace.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[Space](ue_ue.VREditorWidgetComponent.md#space)

___

### TickWhenOffscreen

• **TickWhenOffscreen**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[TickWhenOffscreen](ue_ue.VREditorWidgetComponent.md#tickwhenoffscreen)

___

### TimingPolicy

• **TimingPolicy**: [`EWidgetTimingPolicy`](../enums/ue_ue.EWidgetTimingPolicy.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[TimingPolicy](ue_ue.VREditorWidgetComponent.md#timingpolicy)

___

### TintColorAndOpacity

• **TintColorAndOpacity**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[TintColorAndOpacity](ue_ue.VREditorWidgetComponent.md#tintcolorandopacity)

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[TranslucencySortPriority](ue_ue.VREditorWidgetComponent.md#translucencysortpriority)

___

### TranslucentMaterial

• **TranslucentMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[TranslucentMaterial](ue_ue.VREditorWidgetComponent.md#translucentmaterial)

___

### TranslucentMaterial\_OneSided

• **TranslucentMaterial\_OneSided**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[TranslucentMaterial_OneSided](ue_ue.VREditorWidgetComponent.md#translucentmaterial_onesided)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[UCSModifiedProperties](ue_ue.VREditorWidgetComponent.md#ucsmodifiedproperties)

___

### ViewOwnerDepthPriorityGroup

• **ViewOwnerDepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[ViewOwnerDepthPriorityGroup](ue_ue.VREditorWidgetComponent.md#viewownerdepthprioritygroup)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[VirtualTextureCullMips](ue_ue.VREditorWidgetComponent.md#virtualtexturecullmips)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[VirtualTextureLodBias](ue_ue.VREditorWidgetComponent.md#virtualtexturelodbias)

___

### VirtualTextureMinCoverage

• **VirtualTextureMinCoverage**: `number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[VirtualTextureMinCoverage](ue_ue.VREditorWidgetComponent.md#virtualtexturemincoverage)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[VirtualTextureRenderPassType](ue_ue.VREditorWidgetComponent.md#virtualtexturerenderpasstype)

___

### VisibilityId

• **VisibilityId**: `number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[VisibilityId](ue_ue.VREditorWidgetComponent.md#visibilityid)

___

### Widget

• **Widget**: [`UserWidget`](ue_ue.UserWidget.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[Widget](ue_ue.VREditorWidgetComponent.md#widget)

___

### WidgetClass

• **WidgetClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[WidgetClass](ue_ue.VREditorWidgetComponent.md#widgetclass)

___

### WindowVisibility

• **WindowVisibility**: [`EWindowVisibility`](../enums/ue_ue.EWindowVisibility.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[WindowVisibility](ue_ue.VREditorWidgetComponent.md#windowvisibility)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[__tid_ActorComponent__](ue_ue.VREditorWidgetComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_MeshComponent\_\_

• **\_\_tid\_MeshComponent\_\_**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[__tid_MeshComponent__](ue_ue.VREditorWidgetComponent.md#__tid_meshcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[__tid_Object__](ue_ue.VREditorWidgetComponent.md#__tid_object__)

___

### \_\_tid\_PrimitiveComponent\_\_

• **\_\_tid\_PrimitiveComponent\_\_**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[__tid_PrimitiveComponent__](ue_ue.VREditorWidgetComponent.md#__tid_primitivecomponent__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[__tid_SceneComponent__](ue_ue.VREditorWidgetComponent.md#__tid_scenecomponent__)

___

### \_\_tid\_VREditorCameraWidgetComponent\_\_

• **\_\_tid\_VREditorCameraWidgetComponent\_\_**: `boolean`

___

### \_\_tid\_VREditorWidgetComponent\_\_

• **\_\_tid\_VREditorWidgetComponent\_\_**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[__tid_VREditorWidgetComponent__](ue_ue.VREditorWidgetComponent.md#__tid_vreditorwidgetcomponent__)

___

### \_\_tid\_WidgetComponent\_\_

• **\_\_tid\_WidgetComponent\_\_**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[__tid_WidgetComponent__](ue_ue.VREditorWidgetComponent.md#__tid_widgetcomponent__)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bAbsoluteLocation](ue_ue.VREditorWidgetComponent.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bAbsoluteRotation](ue_ue.VREditorWidgetComponent.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bAbsoluteScale](ue_ue.VREditorWidgetComponent.md#babsolutescale)

___

### bAddedToScreen

• **bAddedToScreen**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bAddedToScreen](ue_ue.VREditorWidgetComponent.md#baddedtoscreen)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bAffectDistanceFieldLighting](ue_ue.VREditorWidgetComponent.md#baffectdistancefieldlighting)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bAffectDynamicIndirectLighting](ue_ue.VREditorWidgetComponent.md#baffectdynamicindirectlighting)

___

### bAllowCullDistanceVolume

• **bAllowCullDistanceVolume**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bAllowCullDistanceVolume](ue_ue.VREditorWidgetComponent.md#ballowculldistancevolume)

___

### bAlwaysCreatePhysicsState

• **bAlwaysCreatePhysicsState**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bAlwaysCreatePhysicsState](ue_ue.VREditorWidgetComponent.md#balwayscreatephysicsstate)

___

### bApplyGammaCorrection

• **bApplyGammaCorrection**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bApplyGammaCorrection](ue_ue.VREditorWidgetComponent.md#bapplygammacorrection)

___

### bApplyImpulseOnDamage

• **bApplyImpulseOnDamage**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bApplyImpulseOnDamage](ue_ue.VREditorWidgetComponent.md#bapplyimpulseondamage)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bAutoActivate](ue_ue.VREditorWidgetComponent.md#bautoactivate)

___

### bBatchImpostersAsInstances

• **bBatchImpostersAsInstances**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bBatchImpostersAsInstances](ue_ue.VREditorWidgetComponent.md#bbatchimpostersasinstances)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.VREditorWidgetComponent.md#bboundschangetriggersstreamingdatarebuild)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bCanEverAffectNavigation](ue_ue.VREditorWidgetComponent.md#bcaneveraffectnavigation)

___

### bCastCinematicShadow

• **bCastCinematicShadow**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bCastCinematicShadow](ue_ue.VREditorWidgetComponent.md#bcastcinematicshadow)

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bCastDynamicShadow](ue_ue.VREditorWidgetComponent.md#bcastdynamicshadow)

___

### bCastFarShadow

• **bCastFarShadow**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bCastFarShadow](ue_ue.VREditorWidgetComponent.md#bcastfarshadow)

___

### bCastHiddenShadow

• **bCastHiddenShadow**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bCastHiddenShadow](ue_ue.VREditorWidgetComponent.md#bcasthiddenshadow)

___

### bCastInsetShadow

• **bCastInsetShadow**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bCastInsetShadow](ue_ue.VREditorWidgetComponent.md#bcastinsetshadow)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bCastShadowAsTwoSided](ue_ue.VREditorWidgetComponent.md#bcastshadowastwosided)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bCastStaticShadow](ue_ue.VREditorWidgetComponent.md#bcaststaticshadow)

___

### bCastVolumetricTranslucentShadow

• **bCastVolumetricTranslucentShadow**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bCastVolumetricTranslucentShadow](ue_ue.VREditorWidgetComponent.md#bcastvolumetrictranslucentshadow)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bComponentToWorldUpdated](ue_ue.VREditorWidgetComponent.md#bcomponenttoworldupdated)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bCreatedByConstructionScript](ue_ue.VREditorWidgetComponent.md#bcreatedbyconstructionscript)

___

### bDrawAtDesiredSize

• **bDrawAtDesiredSize**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bDrawAtDesiredSize](ue_ue.VREditorWidgetComponent.md#bdrawatdesiredsize)

___

### bEditTimeUsable

• **bEditTimeUsable**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bEditTimeUsable](ue_ue.VREditorWidgetComponent.md#bedittimeusable)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bEditableWhenInherited](ue_ue.VREditorWidgetComponent.md#beditablewheninherited)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bEnableAutoLODGeneration](ue_ue.VREditorWidgetComponent.md#benableautolodgeneration)

___

### bEnableMaterialParameterCaching

• **bEnableMaterialParameterCaching**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bEnableMaterialParameterCaching](ue_ue.VREditorWidgetComponent.md#benablematerialparametercaching)

___

### bExcludeFromLightAttachmentGroup

• **bExcludeFromLightAttachmentGroup**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bExcludeFromLightAttachmentGroup](ue_ue.VREditorWidgetComponent.md#bexcludefromlightattachmentgroup)

___

### bForceMipStreaming

• **bForceMipStreaming**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bForceMipStreaming](ue_ue.VREditorWidgetComponent.md#bforcemipstreaming)

___

### bGenerateOverlapEvents

• **bGenerateOverlapEvents**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bGenerateOverlapEvents](ue_ue.VREditorWidgetComponent.md#bgenerateoverlapevents)

___

### bHasCustomNavigableGeometry

• **bHasCustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bHasCustomNavigableGeometry](ue_ue.VREditorWidgetComponent.md#bhascustomnavigablegeometry)

___

### bHasEverDrawn

• **bHasEverDrawn**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bHasEverDrawn](ue_ue.VREditorWidgetComponent.md#bhaseverdrawn)

___

### bHasMotionBlurVelocityMeshes

• **bHasMotionBlurVelocityMeshes**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bHasMotionBlurVelocityMeshes](ue_ue.VREditorWidgetComponent.md#bhasmotionblurvelocitymeshes)

___

### bHasPerInstanceHitProxies

• **bHasPerInstanceHitProxies**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bHasPerInstanceHitProxies](ue_ue.VREditorWidgetComponent.md#bhasperinstancehitproxies)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bHiddenInGame](ue_ue.VREditorWidgetComponent.md#bhiddeningame)

___

### bIgnoreRadialForce

• **bIgnoreRadialForce**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bIgnoreRadialForce](ue_ue.VREditorWidgetComponent.md#bignoreradialforce)

___

### bIgnoreRadialImpulse

• **bIgnoreRadialImpulse**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bIgnoreRadialImpulse](ue_ue.VREditorWidgetComponent.md#bignoreradialimpulse)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bInstanceComponent](ue_ue.VREditorWidgetComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bIsActive](ue_ue.VREditorWidgetComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bIsEditorOnly](ue_ue.VREditorWidgetComponent.md#biseditoronly)

___

### bIsHovering

• **bIsHovering**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bIsHovering](ue_ue.VREditorWidgetComponent.md#bishovering)

___

### bIsTwoSided

• **bIsTwoSided**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bIsTwoSided](ue_ue.VREditorWidgetComponent.md#bistwosided)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bIsVisualizationComponent](ue_ue.VREditorWidgetComponent.md#bisvisualizationcomponent)

___

### bLightAsIfStatic

• **bLightAsIfStatic**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bLightAsIfStatic](ue_ue.VREditorWidgetComponent.md#blightasifstatic)

___

### bLightAttachmentsAsGroup

• **bLightAttachmentsAsGroup**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bLightAttachmentsAsGroup](ue_ue.VREditorWidgetComponent.md#blightattachmentsasgroup)

___

### bManuallyRedraw

• **bManuallyRedraw**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bManuallyRedraw](ue_ue.VREditorWidgetComponent.md#bmanuallyredraw)

___

### bMultiBodyOverlap

• **bMultiBodyOverlap**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bMultiBodyOverlap](ue_ue.VREditorWidgetComponent.md#bmultibodyoverlap)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bNetAddressable](ue_ue.VREditorWidgetComponent.md#bnetaddressable)

___

### bNeverDistanceCull

• **bNeverDistanceCull**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bNeverDistanceCull](ue_ue.VREditorWidgetComponent.md#bneverdistancecull)

___

### bOnlyOwnerSee

• **bOnlyOwnerSee**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bOnlyOwnerSee](ue_ue.VREditorWidgetComponent.md#bonlyownersee)

___

### bOwnerNoSee

• **bOwnerNoSee**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bOwnerNoSee](ue_ue.VREditorWidgetComponent.md#bownernosee)

___

### bReceiveHardwareInput

• **bReceiveHardwareInput**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bReceiveHardwareInput](ue_ue.VREditorWidgetComponent.md#breceivehardwareinput)

___

### bReceiveMobileCSMShadows

• **bReceiveMobileCSMShadows**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bReceiveMobileCSMShadows](ue_ue.VREditorWidgetComponent.md#breceivemobilecsmshadows)

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bReceivesDecals](ue_ue.VREditorWidgetComponent.md#breceivesdecals)

___

### bRedrawRequested

• **bRedrawRequested**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bRedrawRequested](ue_ue.VREditorWidgetComponent.md#bredrawrequested)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bRenderCustomDepth](ue_ue.VREditorWidgetComponent.md#brendercustomdepth)

___

### bRenderInDepthPass

• **bRenderInDepthPass**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bRenderInDepthPass](ue_ue.VREditorWidgetComponent.md#brenderindepthpass)

___

### bRenderInMainPass

• **bRenderInMainPass**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bRenderInMainPass](ue_ue.VREditorWidgetComponent.md#brenderinmainpass)

___

### bReplicatePhysicsToAutonomousProxy

• **bReplicatePhysicsToAutonomousProxy**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bReplicatePhysicsToAutonomousProxy](ue_ue.VREditorWidgetComponent.md#breplicatephysicstoautonomousproxy)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bReplicates](ue_ue.VREditorWidgetComponent.md#breplicates)

___

### bReturnMaterialOnMove

• **bReturnMaterialOnMove**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bReturnMaterialOnMove](ue_ue.VREditorWidgetComponent.md#breturnmaterialonmove)

___

### bSelectable

• **bSelectable**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bSelectable](ue_ue.VREditorWidgetComponent.md#bselectable)

___

### bSelfShadowOnly

• **bSelfShadowOnly**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bSelfShadowOnly](ue_ue.VREditorWidgetComponent.md#bselfshadowonly)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bShouldBeAttached](ue_ue.VREditorWidgetComponent.md#bshouldbeattached)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.VREditorWidgetComponent.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.VREditorWidgetComponent.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.VREditorWidgetComponent.md#bshouldupdatephysicsvolume)

___

### bSingleSampleShadowFromStationaryLights

• **bSingleSampleShadowFromStationaryLights**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bSingleSampleShadowFromStationaryLights](ue_ue.VREditorWidgetComponent.md#bsinglesampleshadowfromstationarylights)

___

### bTraceComplexOnMove

• **bTraceComplexOnMove**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bTraceComplexOnMove](ue_ue.VREditorWidgetComponent.md#btracecomplexonmove)

___

### bTreatAsBackgroundForOcclusion

• **bTreatAsBackgroundForOcclusion**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bTreatAsBackgroundForOcclusion](ue_ue.VREditorWidgetComponent.md#btreatasbackgroundforocclusion)

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bUseAsOccluder](ue_ue.VREditorWidgetComponent.md#buseasoccluder)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bUseAttachParentBound](ue_ue.VREditorWidgetComponent.md#buseattachparentbound)

___

### bUseEditorCompositing

• **bUseEditorCompositing**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bUseEditorCompositing](ue_ue.VREditorWidgetComponent.md#buseeditorcompositing)

___

### bUseMaxLODAsImposter

• **bUseMaxLODAsImposter**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bUseMaxLODAsImposter](ue_ue.VREditorWidgetComponent.md#busemaxlodasimposter)

___

### bUseViewOwnerDepthPriorityGroup

• **bUseViewOwnerDepthPriorityGroup**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bUseViewOwnerDepthPriorityGroup](ue_ue.VREditorWidgetComponent.md#buseviewownerdepthprioritygroup)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bVisible](ue_ue.VREditorWidgetComponent.md#bvisible)

___

### bVisibleInRayTracing

• **bVisibleInRayTracing**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bVisibleInRayTracing](ue_ue.VREditorWidgetComponent.md#bvisibleinraytracing)

___

### bVisibleInReflectionCaptures

• **bVisibleInReflectionCaptures**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bVisibleInReflectionCaptures](ue_ue.VREditorWidgetComponent.md#bvisibleinreflectioncaptures)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bVisualizeComponent](ue_ue.VREditorWidgetComponent.md#bvisualizecomponent)

___

### bWindowFocusable

• **bWindowFocusable**: `boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[bWindowFocusable](ue_ue.VREditorWidgetComponent.md#bwindowfocusable)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[Activate](ue_ue.VREditorWidgetComponent.md#activate)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AddAngularImpulse](ue_ue.VREditorWidgetComponent.md#addangularimpulse)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AddAngularImpulseInDegrees](ue_ue.VREditorWidgetComponent.md#addangularimpulseindegrees)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AddAngularImpulseInRadians](ue_ue.VREditorWidgetComponent.md#addangularimpulseinradians)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AddForce](ue_ue.VREditorWidgetComponent.md#addforce)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AddForceAtLocation](ue_ue.VREditorWidgetComponent.md#addforceatlocation)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AddForceAtLocationLocal](ue_ue.VREditorWidgetComponent.md#addforceatlocationlocal)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AddImpulse](ue_ue.VREditorWidgetComponent.md#addimpulse)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AddImpulseAtLocation](ue_ue.VREditorWidgetComponent.md#addimpulseatlocation)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AddRadialForce](ue_ue.VREditorWidgetComponent.md#addradialforce)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AddRadialImpulse](ue_ue.VREditorWidgetComponent.md#addradialimpulse)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AddTickPrerequisiteActor](ue_ue.VREditorWidgetComponent.md#addtickprerequisiteactor)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AddTickPrerequisiteComponent](ue_ue.VREditorWidgetComponent.md#addtickprerequisitecomponent)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AddTorque](ue_ue.VREditorWidgetComponent.md#addtorque)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AddTorqueInDegrees](ue_ue.VREditorWidgetComponent.md#addtorqueindegrees)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[AddTorqueInRadians](ue_ue.VREditorWidgetComponent.md#addtorqueinradians)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[CanCharacterStepUp](ue_ue.VREditorWidgetComponent.md#cancharacterstepup)

___

### ClearMoveIgnoreActors

▸ **ClearMoveIgnoreActors**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[ClearMoveIgnoreActors](ue_ue.VREditorWidgetComponent.md#clearmoveignoreactors)

___

### ClearMoveIgnoreComponents

▸ **ClearMoveIgnoreComponents**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[ClearMoveIgnoreComponents](ue_ue.VREditorWidgetComponent.md#clearmoveignorecomponents)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[ComponentHasTag](ue_ue.VREditorWidgetComponent.md#componenthastag)

___

### CopyArrayOfMoveIgnoreActors

▸ **CopyArrayOfMoveIgnoreActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[CopyArrayOfMoveIgnoreActors](ue_ue.VREditorWidgetComponent.md#copyarrayofmoveignoreactors)

___

### CopyArrayOfMoveIgnoreComponents

▸ **CopyArrayOfMoveIgnoreComponents**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[CopyArrayOfMoveIgnoreComponents](ue_ue.VREditorWidgetComponent.md#copyarrayofmoveignorecomponents)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[CreateAndSetMaterialInstanceDynamic](ue_ue.VREditorWidgetComponent.md#createandsetmaterialinstancedynamic)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.VREditorWidgetComponent.md#createandsetmaterialinstancedynamicfrommaterial)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[CreateDefaultSubobject](ue_ue.VREditorWidgetComponent.md#createdefaultsubobject)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[CreateDynamicMaterialInstance](ue_ue.VREditorWidgetComponent.md#createdynamicmaterialinstance)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[Deactivate](ue_ue.VREditorWidgetComponent.md#deactivate)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[DetachFromParent](ue_ue.VREditorWidgetComponent.md#detachfromparent)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[DoesSocketExist](ue_ue.VREditorWidgetComponent.md#doessocketexist)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[ExecuteUbergraph](ue_ue.VREditorWidgetComponent.md#executeubergraph)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetAllSocketNames](ue_ue.VREditorWidgetComponent.md#getallsocketnames)

___

### GetAngularDamping

▸ **GetAngularDamping**(): `number`

#### Returns

`number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetAngularDamping](ue_ue.VREditorWidgetComponent.md#getangulardamping)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetAttachParent](ue_ue.VREditorWidgetComponent.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetAttachSocketName](ue_ue.VREditorWidgetComponent.md#getattachsocketname)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetCenterOfMass](ue_ue.VREditorWidgetComponent.md#getcenterofmass)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetChildComponent](ue_ue.VREditorWidgetComponent.md#getchildcomponent)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetChildrenComponents](ue_ue.VREditorWidgetComponent.md#getchildrencomponents)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetClass](ue_ue.VREditorWidgetComponent.md#getclass)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetClosestPointOnCollision](ue_ue.VREditorWidgetComponent.md#getclosestpointoncollision)

___

### GetCollisionEnabled

▸ **GetCollisionEnabled**(): [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Returns

[`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetCollisionEnabled](ue_ue.VREditorWidgetComponent.md#getcollisionenabled)

___

### GetCollisionObjectType

▸ **GetCollisionObjectType**(): [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Returns

[`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetCollisionObjectType](ue_ue.VREditorWidgetComponent.md#getcollisionobjecttype)

___

### GetCollisionProfileName

▸ **GetCollisionProfileName**(): `string`

#### Returns

`string`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetCollisionProfileName](ue_ue.VREditorWidgetComponent.md#getcollisionprofilename)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetCollisionResponseToChannel](ue_ue.VREditorWidgetComponent.md#getcollisionresponsetochannel)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetComponentTickInterval](ue_ue.VREditorWidgetComponent.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetComponentVelocity](ue_ue.VREditorWidgetComponent.md#getcomponentvelocity)

___

### GetCurrentDrawSize

▸ **GetCurrentDrawSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetCurrentDrawSize](ue_ue.VREditorWidgetComponent.md#getcurrentdrawsize)

___

### GetCylinderArcAngle

▸ **GetCylinderArcAngle**(): `number`

#### Returns

`number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetCylinderArcAngle](ue_ue.VREditorWidgetComponent.md#getcylinderarcangle)

___

### GetDrawAtDesiredSize

▸ **GetDrawAtDesiredSize**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetDrawAtDesiredSize](ue_ue.VREditorWidgetComponent.md#getdrawatdesiredsize)

___

### GetDrawSize

▸ **GetDrawSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetDrawSize](ue_ue.VREditorWidgetComponent.md#getdrawsize)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetForwardVector](ue_ue.VREditorWidgetComponent.md#getforwardvector)

___

### GetGenerateOverlapEvents

▸ **GetGenerateOverlapEvents**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetGenerateOverlapEvents](ue_ue.VREditorWidgetComponent.md#getgenerateoverlapevents)

___

### GetGeometryMode

▸ **GetGeometryMode**(): [`EWidgetGeometryMode`](../enums/ue_ue.EWidgetGeometryMode.md)

#### Returns

[`EWidgetGeometryMode`](../enums/ue_ue.EWidgetGeometryMode.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetGeometryMode](ue_ue.VREditorWidgetComponent.md#getgeometrymode)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetInertiaTensor](ue_ue.VREditorWidgetComponent.md#getinertiatensor)

___

### GetLinearDamping

▸ **GetLinearDamping**(): `number`

#### Returns

`number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetLinearDamping](ue_ue.VREditorWidgetComponent.md#getlineardamping)

___

### GetManuallyRedraw

▸ **GetManuallyRedraw**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetManuallyRedraw](ue_ue.VREditorWidgetComponent.md#getmanuallyredraw)

___

### GetMass

▸ **GetMass**(): `number`

#### Returns

`number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetMass](ue_ue.VREditorWidgetComponent.md#getmass)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetMassScale](ue_ue.VREditorWidgetComponent.md#getmassscale)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetMaterial](ue_ue.VREditorWidgetComponent.md#getmaterial)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetMaterialFromCollisionFaceIndex](ue_ue.VREditorWidgetComponent.md#getmaterialfromcollisionfaceindex)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetMaterialIndex](ue_ue.VREditorWidgetComponent.md#getmaterialindex)

___

### GetMaterialInstance

▸ **GetMaterialInstance**(): [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Returns

[`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetMaterialInstance](ue_ue.VREditorWidgetComponent.md#getmaterialinstance)

___

### GetMaterialSlotNames

▸ **GetMaterialSlotNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetMaterialSlotNames](ue_ue.VREditorWidgetComponent.md#getmaterialslotnames)

___

### GetMaterials

▸ **GetMaterials**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetMaterials](ue_ue.VREditorWidgetComponent.md#getmaterials)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetName](ue_ue.VREditorWidgetComponent.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetNumChildrenComponents](ue_ue.VREditorWidgetComponent.md#getnumchildrencomponents)

___

### GetNumMaterials

▸ **GetNumMaterials**(): `number`

#### Returns

`number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetNumMaterials](ue_ue.VREditorWidgetComponent.md#getnummaterials)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetOuter](ue_ue.VREditorWidgetComponent.md#getouter)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetOverlappingActors](ue_ue.VREditorWidgetComponent.md#getoverlappingactors)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetOverlappingComponents](ue_ue.VREditorWidgetComponent.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetOwner](ue_ue.VREditorWidgetComponent.md#getowner)

___

### GetOwnerPlayer

▸ **GetOwnerPlayer**(): [`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Returns

[`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetOwnerPlayer](ue_ue.VREditorWidgetComponent.md#getownerplayer)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetParentComponents](ue_ue.VREditorWidgetComponent.md#getparentcomponents)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetPhysicsAngularVelocity](ue_ue.VREditorWidgetComponent.md#getphysicsangularvelocity)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetPhysicsAngularVelocityInDegrees](ue_ue.VREditorWidgetComponent.md#getphysicsangularvelocityindegrees)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetPhysicsAngularVelocityInRadians](ue_ue.VREditorWidgetComponent.md#getphysicsangularvelocityinradians)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetPhysicsLinearVelocity](ue_ue.VREditorWidgetComponent.md#getphysicslinearvelocity)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetPhysicsLinearVelocityAtPoint](ue_ue.VREditorWidgetComponent.md#getphysicslinearvelocityatpoint)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetPhysicsVolume](ue_ue.VREditorWidgetComponent.md#getphysicsvolume)

___

### GetPivot

▸ **GetPivot**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetPivot](ue_ue.VREditorWidgetComponent.md#getpivot)

___

### GetRedrawTime

▸ **GetRedrawTime**(): `number`

#### Returns

`number`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetRedrawTime](ue_ue.VREditorWidgetComponent.md#getredrawtime)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetRelativeTransform](ue_ue.VREditorWidgetComponent.md#getrelativetransform)

___

### GetRenderTarget

▸ **GetRenderTarget**(): [`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)

#### Returns

[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetRenderTarget](ue_ue.VREditorWidgetComponent.md#getrendertarget)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetRightVector](ue_ue.VREditorWidgetComponent.md#getrightvector)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.VREditorWidgetComponent.md#getshouldupdatephysicsvolume)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetSocketLocation](ue_ue.VREditorWidgetComponent.md#getsocketlocation)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetSocketQuaternion](ue_ue.VREditorWidgetComponent.md#getsocketquaternion)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetSocketRotation](ue_ue.VREditorWidgetComponent.md#getsocketrotation)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetSocketTransform](ue_ue.VREditorWidgetComponent.md#getsockettransform)

___

### GetTickWhenOffscreen

▸ **GetTickWhenOffscreen**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetTickWhenOffscreen](ue_ue.VREditorWidgetComponent.md#gettickwhenoffscreen)

___

### GetTwoSided

▸ **GetTwoSided**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetTwoSided](ue_ue.VREditorWidgetComponent.md#gettwosided)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetUpVector](ue_ue.VREditorWidgetComponent.md#getupvector)

___

### GetUserWidgetObject

▸ **GetUserWidgetObject**(): [`UserWidget`](ue_ue.UserWidget.md)

#### Returns

[`UserWidget`](ue_ue.UserWidget.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetUserWidgetObject](ue_ue.VREditorWidgetComponent.md#getuserwidgetobject)

___

### GetWalkableSlopeOverride

▸ **GetWalkableSlopeOverride**(): [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Returns

[`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetWalkableSlopeOverride](ue_ue.VREditorWidgetComponent.md#getwalkableslopeoverride)

___

### GetWidgetSpace

▸ **GetWidgetSpace**(): [`EWidgetSpace`](../enums/ue_ue.EWidgetSpace.md)

#### Returns

[`EWidgetSpace`](../enums/ue_ue.EWidgetSpace.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetWidgetSpace](ue_ue.VREditorWidgetComponent.md#getwidgetspace)

___

### GetWindowFocusable

▸ **GetWindowFocusable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetWindowFocusable](ue_ue.VREditorWidgetComponent.md#getwindowfocusable)

___

### GetWindowVisiblility

▸ **GetWindowVisiblility**(): [`EWindowVisibility`](../enums/ue_ue.EWindowVisibility.md)

#### Returns

[`EWindowVisibility`](../enums/ue_ue.EWindowVisibility.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetWindowVisiblility](ue_ue.VREditorWidgetComponent.md#getwindowvisiblility)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[GetWorld](ue_ue.VREditorWidgetComponent.md#getworld)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[IgnoreActorWhenMoving](ue_ue.VREditorWidgetComponent.md#ignoreactorwhenmoving)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[IgnoreComponentWhenMoving](ue_ue.VREditorWidgetComponent.md#ignorecomponentwhenmoving)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[IsActive](ue_ue.VREditorWidgetComponent.md#isactive)

___

### IsAnyRigidBodyAwake

▸ **IsAnyRigidBodyAwake**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[IsAnyRigidBodyAwake](ue_ue.VREditorWidgetComponent.md#isanyrigidbodyawake)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[IsAnySimulatingPhysics](ue_ue.VREditorWidgetComponent.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[IsBeingDestroyed](ue_ue.VREditorWidgetComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[IsComponentTickEnabled](ue_ue.VREditorWidgetComponent.md#iscomponenttickenabled)

___

### IsGravityEnabled

▸ **IsGravityEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[IsGravityEnabled](ue_ue.VREditorWidgetComponent.md#isgravityenabled)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[IsMaterialSlotNameValid](ue_ue.VREditorWidgetComponent.md#ismaterialslotnamevalid)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[IsOverlappingActor](ue_ue.VREditorWidgetComponent.md#isoverlappingactor)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[IsOverlappingComponent](ue_ue.VREditorWidgetComponent.md#isoverlappingcomponent)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[IsSimulatingPhysics](ue_ue.VREditorWidgetComponent.md#issimulatingphysics)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[IsVisible](ue_ue.VREditorWidgetComponent.md#isvisible)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_AddLocalOffset](ue_ue.VREditorWidgetComponent.md#k2_addlocaloffset)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_AddLocalRotation](ue_ue.VREditorWidgetComponent.md#k2_addlocalrotation)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_AddLocalTransform](ue_ue.VREditorWidgetComponent.md#k2_addlocaltransform)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_AddRelativeLocation](ue_ue.VREditorWidgetComponent.md#k2_addrelativelocation)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_AddRelativeRotation](ue_ue.VREditorWidgetComponent.md#k2_addrelativerotation)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_AddWorldOffset](ue_ue.VREditorWidgetComponent.md#k2_addworldoffset)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_AddWorldRotation](ue_ue.VREditorWidgetComponent.md#k2_addworldrotation)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_AddWorldTransform](ue_ue.VREditorWidgetComponent.md#k2_addworldtransform)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_AttachTo](ue_ue.VREditorWidgetComponent.md#k2_attachto)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_AttachToComponent](ue_ue.VREditorWidgetComponent.md#k2_attachtocomponent)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_BoxOverlapComponent](ue_ue.VREditorWidgetComponent.md#k2_boxoverlapcomponent)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_DestroyComponent](ue_ue.VREditorWidgetComponent.md#k2_destroycomponent)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_DetachFromComponent](ue_ue.VREditorWidgetComponent.md#k2_detachfromcomponent)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_GetComponentLocation](ue_ue.VREditorWidgetComponent.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_GetComponentRotation](ue_ue.VREditorWidgetComponent.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_GetComponentScale](ue_ue.VREditorWidgetComponent.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_GetComponentToWorld](ue_ue.VREditorWidgetComponent.md#k2_getcomponenttoworld)

___

### K2\_IsCollisionEnabled

▸ **K2_IsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_IsCollisionEnabled](ue_ue.VREditorWidgetComponent.md#k2_iscollisionenabled)

___

### K2\_IsPhysicsCollisionEnabled

▸ **K2_IsPhysicsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_IsPhysicsCollisionEnabled](ue_ue.VREditorWidgetComponent.md#k2_isphysicscollisionenabled)

___

### K2\_IsQueryCollisionEnabled

▸ **K2_IsQueryCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_IsQueryCollisionEnabled](ue_ue.VREditorWidgetComponent.md#k2_isquerycollisionenabled)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_LineTraceComponent](ue_ue.VREditorWidgetComponent.md#k2_linetracecomponent)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_SetRelativeLocation](ue_ue.VREditorWidgetComponent.md#k2_setrelativelocation)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.VREditorWidgetComponent.md#k2_setrelativelocationandrotation)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_SetRelativeRotation](ue_ue.VREditorWidgetComponent.md#k2_setrelativerotation)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_SetRelativeTransform](ue_ue.VREditorWidgetComponent.md#k2_setrelativetransform)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_SetWorldLocation](ue_ue.VREditorWidgetComponent.md#k2_setworldlocation)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.VREditorWidgetComponent.md#k2_setworldlocationandrotation)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_SetWorldRotation](ue_ue.VREditorWidgetComponent.md#k2_setworldrotation)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_SetWorldTransform](ue_ue.VREditorWidgetComponent.md#k2_setworldtransform)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_SphereOverlapComponent](ue_ue.VREditorWidgetComponent.md#k2_sphereoverlapcomponent)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[K2_SphereTraceComponent](ue_ue.VREditorWidgetComponent.md#k2_spheretracecomponent)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnRep_AttachChildren](ue_ue.VREditorWidgetComponent.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnRep_AttachParent](ue_ue.VREditorWidgetComponent.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnRep_AttachSocketName](ue_ue.VREditorWidgetComponent.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnRep_IsActive](ue_ue.VREditorWidgetComponent.md#onrep_isactive)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnRep_Transform](ue_ue.VREditorWidgetComponent.md#onrep_transform)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[OnRep_Visibility](ue_ue.VREditorWidgetComponent.md#onrep_visibility)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[PrestreamTextures](ue_ue.VREditorWidgetComponent.md#prestreamtextures)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[PutRigidBodyToSleep](ue_ue.VREditorWidgetComponent.md#putrigidbodytosleep)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[ReceiveBeginPlay](ue_ue.VREditorWidgetComponent.md#receivebeginplay)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[ReceiveEndPlay](ue_ue.VREditorWidgetComponent.md#receiveendplay)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[ReceiveTick](ue_ue.VREditorWidgetComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[RegisterComponent](ue_ue.VREditorWidgetComponent.md#registercomponent)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[RemoveTickPrerequisiteActor](ue_ue.VREditorWidgetComponent.md#removetickprerequisiteactor)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.VREditorWidgetComponent.md#removetickprerequisitecomponent)

___

### RequestRedraw

▸ **RequestRedraw**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[RequestRedraw](ue_ue.VREditorWidgetComponent.md#requestredraw)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[ResetRelativeTransform](ue_ue.VREditorWidgetComponent.md#resetrelativetransform)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[ScaleByMomentOfInertia](ue_ue.VREditorWidgetComponent.md#scalebymomentofinertia)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetAbsolute](ue_ue.VREditorWidgetComponent.md#setabsolute)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetActive](ue_ue.VREditorWidgetComponent.md#setactive)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetAllMassScale](ue_ue.VREditorWidgetComponent.md#setallmassscale)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetAllPhysicsAngularVelocityInDegrees](ue_ue.VREditorWidgetComponent.md#setallphysicsangularvelocityindegrees)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetAllPhysicsAngularVelocityInRadians](ue_ue.VREditorWidgetComponent.md#setallphysicsangularvelocityinradians)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetAllPhysicsLinearVelocity](ue_ue.VREditorWidgetComponent.md#setallphysicslinearvelocity)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetAllUseCCD](ue_ue.VREditorWidgetComponent.md#setalluseccd)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetAngularDamping](ue_ue.VREditorWidgetComponent.md#setangulardamping)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetAutoActivate](ue_ue.VREditorWidgetComponent.md#setautoactivate)

___

### SetBackgroundColor

▸ **SetBackgroundColor**(`NewBackgroundColor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewBackgroundColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetBackgroundColor](ue_ue.VREditorWidgetComponent.md#setbackgroundcolor)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetBoundsScale](ue_ue.VREditorWidgetComponent.md#setboundsscale)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetCastInsetShadow](ue_ue.VREditorWidgetComponent.md#setcastinsetshadow)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetCastShadow](ue_ue.VREditorWidgetComponent.md#setcastshadow)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetCenterOfMass](ue_ue.VREditorWidgetComponent.md#setcenterofmass)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetCollisionEnabled](ue_ue.VREditorWidgetComponent.md#setcollisionenabled)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetCollisionObjectType](ue_ue.VREditorWidgetComponent.md#setcollisionobjecttype)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetCollisionProfileName](ue_ue.VREditorWidgetComponent.md#setcollisionprofilename)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetCollisionResponseToAllChannels](ue_ue.VREditorWidgetComponent.md#setcollisionresponsetoallchannels)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetCollisionResponseToChannel](ue_ue.VREditorWidgetComponent.md#setcollisionresponsetochannel)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetComponentTickEnabled](ue_ue.VREditorWidgetComponent.md#setcomponenttickenabled)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetComponentTickInterval](ue_ue.VREditorWidgetComponent.md#setcomponenttickinterval)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetConstraintMode](ue_ue.VREditorWidgetComponent.md#setconstraintmode)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetCullDistance](ue_ue.VREditorWidgetComponent.md#setculldistance)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetCustomDepthStencilValue](ue_ue.VREditorWidgetComponent.md#setcustomdepthstencilvalue)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetCustomDepthStencilWriteMask](ue_ue.VREditorWidgetComponent.md#setcustomdepthstencilwritemask)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetCustomPrimitiveDataFloat](ue_ue.VREditorWidgetComponent.md#setcustomprimitivedatafloat)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetCustomPrimitiveDataVector2](ue_ue.VREditorWidgetComponent.md#setcustomprimitivedatavector2)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetCustomPrimitiveDataVector3](ue_ue.VREditorWidgetComponent.md#setcustomprimitivedatavector3)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetCustomPrimitiveDataVector4](ue_ue.VREditorWidgetComponent.md#setcustomprimitivedatavector4)

___

### SetCylinderArcAngle

▸ **SetCylinderArcAngle**(`InCylinderArcAngle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InCylinderArcAngle` | `number` |

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetCylinderArcAngle](ue_ue.VREditorWidgetComponent.md#setcylinderarcangle)

___

### SetDrawAtDesiredSize

▸ **SetDrawAtDesiredSize**(`bInDrawAtDesiredSize`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInDrawAtDesiredSize` | `boolean` |

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetDrawAtDesiredSize](ue_ue.VREditorWidgetComponent.md#setdrawatdesiredsize)

___

### SetDrawSize

▸ **SetDrawSize**(`Size`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Size` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetDrawSize](ue_ue.VREditorWidgetComponent.md#setdrawsize)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetEnableGravity](ue_ue.VREditorWidgetComponent.md#setenablegravity)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetExcludeFromLightAttachmentGroup](ue_ue.VREditorWidgetComponent.md#setexcludefromlightattachmentgroup)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetGenerateOverlapEvents](ue_ue.VREditorWidgetComponent.md#setgenerateoverlapevents)

___

### SetGeometryMode

▸ **SetGeometryMode**(`InGeometryMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InGeometryMode` | [`EWidgetGeometryMode`](../enums/ue_ue.EWidgetGeometryMode.md) |

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetGeometryMode](ue_ue.VREditorWidgetComponent.md#setgeometrymode)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetHiddenInGame](ue_ue.VREditorWidgetComponent.md#sethiddeningame)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetIsReplicated](ue_ue.VREditorWidgetComponent.md#setisreplicated)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetLightAttachmentsAsGroup](ue_ue.VREditorWidgetComponent.md#setlightattachmentsasgroup)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetLinearDamping](ue_ue.VREditorWidgetComponent.md#setlineardamping)

___

### SetManuallyRedraw

▸ **SetManuallyRedraw**(`bUseManualRedraw`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bUseManualRedraw` | `boolean` |

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetManuallyRedraw](ue_ue.VREditorWidgetComponent.md#setmanuallyredraw)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetMassOverrideInKg](ue_ue.VREditorWidgetComponent.md#setmassoverrideinkg)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetMassScale](ue_ue.VREditorWidgetComponent.md#setmassscale)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetMaterial](ue_ue.VREditorWidgetComponent.md#setmaterial)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetMaterialByName](ue_ue.VREditorWidgetComponent.md#setmaterialbyname)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetMobility](ue_ue.VREditorWidgetComponent.md#setmobility)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetNotifyRigidBodyCollision](ue_ue.VREditorWidgetComponent.md#setnotifyrigidbodycollision)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetOnlyOwnerSee](ue_ue.VREditorWidgetComponent.md#setonlyownersee)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetOwnerNoSee](ue_ue.VREditorWidgetComponent.md#setownernosee)

___

### SetOwnerPlayer

▸ **SetOwnerPlayer**(`LocalPlayer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LocalPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`LocalPlayer`](ue_ue.LocalPlayer.md)\> |

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetOwnerPlayer](ue_ue.VREditorWidgetComponent.md#setownerplayer)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetPhysMaterialOverride](ue_ue.VREditorWidgetComponent.md#setphysmaterialoverride)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetPhysicsAngularVelocity](ue_ue.VREditorWidgetComponent.md#setphysicsangularvelocity)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetPhysicsAngularVelocityInDegrees](ue_ue.VREditorWidgetComponent.md#setphysicsangularvelocityindegrees)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetPhysicsAngularVelocityInRadians](ue_ue.VREditorWidgetComponent.md#setphysicsangularvelocityinradians)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetPhysicsLinearVelocity](ue_ue.VREditorWidgetComponent.md#setphysicslinearvelocity)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetPhysicsMaxAngularVelocity](ue_ue.VREditorWidgetComponent.md#setphysicsmaxangularvelocity)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetPhysicsMaxAngularVelocityInDegrees](ue_ue.VREditorWidgetComponent.md#setphysicsmaxangularvelocityindegrees)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetPhysicsMaxAngularVelocityInRadians](ue_ue.VREditorWidgetComponent.md#setphysicsmaxangularvelocityinradians)

___

### SetPivot

▸ **SetPivot**(`InPivot`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPivot` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetPivot](ue_ue.VREditorWidgetComponent.md#setpivot)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetReceivesDecals](ue_ue.VREditorWidgetComponent.md#setreceivesdecals)

___

### SetRedrawTime

▸ **SetRedrawTime**(`InRedrawTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRedrawTime` | `number` |

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetRedrawTime](ue_ue.VREditorWidgetComponent.md#setredrawtime)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetRelativeScale3D](ue_ue.VREditorWidgetComponent.md#setrelativescale3d)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetRenderCustomDepth](ue_ue.VREditorWidgetComponent.md#setrendercustomdepth)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetRenderInMainPass](ue_ue.VREditorWidgetComponent.md#setrenderinmainpass)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetScalarParameterValueOnMaterials](ue_ue.VREditorWidgetComponent.md#setscalarparametervalueonmaterials)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.VREditorWidgetComponent.md#setshouldupdatephysicsvolume)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetSimulatePhysics](ue_ue.VREditorWidgetComponent.md#setsimulatephysics)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetSingleSampleShadowFromStationaryLights](ue_ue.VREditorWidgetComponent.md#setsinglesampleshadowfromstationarylights)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetTickGroup](ue_ue.VREditorWidgetComponent.md#settickgroup)

___

### SetTickWhenOffscreen

▸ **SetTickWhenOffscreen**(`bWantTickWhenOffscreen`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bWantTickWhenOffscreen` | `boolean` |

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetTickWhenOffscreen](ue_ue.VREditorWidgetComponent.md#settickwhenoffscreen)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetTickableWhenPaused](ue_ue.VREditorWidgetComponent.md#settickablewhenpaused)

___

### SetTintColorAndOpacity

▸ **SetTintColorAndOpacity**(`NewTintColorAndOpacity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTintColorAndOpacity` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetTintColorAndOpacity](ue_ue.VREditorWidgetComponent.md#settintcolorandopacity)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetTranslucentSortPriority](ue_ue.VREditorWidgetComponent.md#settranslucentsortpriority)

___

### SetTwoSided

▸ **SetTwoSided**(`bWantTwoSided`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bWantTwoSided` | `boolean` |

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetTwoSided](ue_ue.VREditorWidgetComponent.md#settwosided)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetUseCCD](ue_ue.VREditorWidgetComponent.md#setuseccd)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetVectorParameterValueOnMaterials](ue_ue.VREditorWidgetComponent.md#setvectorparametervalueonmaterials)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetVisibility](ue_ue.VREditorWidgetComponent.md#setvisibility)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetWalkableSlopeOverride](ue_ue.VREditorWidgetComponent.md#setwalkableslopeoverride)

___

### SetWidget

▸ **SetWidget**(`Widget`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\> |

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetWidget](ue_ue.VREditorWidgetComponent.md#setwidget)

___

### SetWidgetSpace

▸ **SetWidgetSpace**(`NewSpace`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewSpace` | [`EWidgetSpace`](../enums/ue_ue.EWidgetSpace.md) |

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetWidgetSpace](ue_ue.VREditorWidgetComponent.md#setwidgetspace)

___

### SetWindowFocusable

▸ **SetWindowFocusable**(`bInWindowFocusable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInWindowFocusable` | `boolean` |

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetWindowFocusable](ue_ue.VREditorWidgetComponent.md#setwindowfocusable)

___

### SetWindowVisibility

▸ **SetWindowVisibility**(`InVisibility`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVisibility` | [`EWindowVisibility`](../enums/ue_ue.EWindowVisibility.md) |

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetWindowVisibility](ue_ue.VREditorWidgetComponent.md#setwindowvisibility)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetWorldScale3D](ue_ue.VREditorWidgetComponent.md#setworldscale3d)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SetupAttachment](ue_ue.VREditorWidgetComponent.md#setupattachment)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[SnapTo](ue_ue.VREditorWidgetComponent.md#snapto)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[ToggleActive](ue_ue.VREditorWidgetComponent.md#toggleactive)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[ToggleVisibility](ue_ue.VREditorWidgetComponent.md#togglevisibility)

___

### WakeAllRigidBodies

▸ **WakeAllRigidBodies**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[WakeAllRigidBodies](ue_ue.VREditorWidgetComponent.md#wakeallrigidbodies)

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

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[WakeRigidBody](ue_ue.VREditorWidgetComponent.md#wakerigidbody)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VREditorCameraWidgetComponent`](ue_ue.VREditorCameraWidgetComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VREditorCameraWidgetComponent`](ue_ue.VREditorCameraWidgetComponent.md)

#### Overrides

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[Find](ue_ue.VREditorWidgetComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`VREditorCameraWidgetComponent`](ue_ue.VREditorCameraWidgetComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VREditorCameraWidgetComponent`](ue_ue.VREditorCameraWidgetComponent.md)

#### Overrides

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[Load](ue_ue.VREditorWidgetComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[VREditorWidgetComponent](ue_ue.VREditorWidgetComponent.md).[StaticClass](ue_ue.VREditorWidgetComponent.md#staticclass)
