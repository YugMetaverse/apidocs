[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VREditorWidgetComponent

# Class: VREditorWidgetComponent

[ue/ue](../modules/ue_ue.md).VREditorWidgetComponent

## Hierarchy

- [`WidgetComponent`](ue_ue.WidgetComponent.md)

  ↳ **`VREditorWidgetComponent`**

  ↳↳ [`VREditorCameraWidgetComponent`](ue_ue.VREditorCameraWidgetComponent.md)

## Table of contents

### Constructors

- [constructor](ue_ue.VREditorWidgetComponent.md#constructor)

### Properties

- [AlwaysLoadOnClient](ue_ue.VREditorWidgetComponent.md#alwaysloadonclient)
- [AlwaysLoadOnServer](ue_ue.VREditorWidgetComponent.md#alwaysloadonserver)
- [AssetUserData](ue_ue.VREditorWidgetComponent.md#assetuserdata)
- [AttachChildren](ue_ue.VREditorWidgetComponent.md#attachchildren)
- [AttachParent](ue_ue.VREditorWidgetComponent.md#attachparent)
- [AttachSocketName](ue_ue.VREditorWidgetComponent.md#attachsocketname)
- [BackgroundColor](ue_ue.VREditorWidgetComponent.md#backgroundcolor)
- [BlendMode](ue_ue.VREditorWidgetComponent.md#blendmode)
- [BodyInstance](ue_ue.VREditorWidgetComponent.md#bodyinstance)
- [BodySetup](ue_ue.VREditorWidgetComponent.md#bodysetup)
- [BoundsScale](ue_ue.VREditorWidgetComponent.md#boundsscale)
- [CachedMaxDrawDistance](ue_ue.VREditorWidgetComponent.md#cachedmaxdrawdistance)
- [CanBeCharacterBase](ue_ue.VREditorWidgetComponent.md#canbecharacterbase)
- [CanCharacterStepUpOn](ue_ue.VREditorWidgetComponent.md#cancharacterstepupon)
- [CastShadow](ue_ue.VREditorWidgetComponent.md#castshadow)
- [ClientAttachedChildren](ue_ue.VREditorWidgetComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.VREditorWidgetComponent.md#componenttags)
- [ComponentVelocity](ue_ue.VREditorWidgetComponent.md#componentvelocity)
- [CreationMethod](ue_ue.VREditorWidgetComponent.md#creationmethod)
- [CurrentDrawSize](ue_ue.VREditorWidgetComponent.md#currentdrawsize)
- [CustomDepthStencilValue](ue_ue.VREditorWidgetComponent.md#customdepthstencilvalue)
- [CustomDepthStencilWriteMask](ue_ue.VREditorWidgetComponent.md#customdepthstencilwritemask)
- [CustomPrimitiveData](ue_ue.VREditorWidgetComponent.md#customprimitivedata)
- [CylinderArcAngle](ue_ue.VREditorWidgetComponent.md#cylinderarcangle)
- [DepthPriorityGroup](ue_ue.VREditorWidgetComponent.md#depthprioritygroup)
- [DetailMode](ue_ue.VREditorWidgetComponent.md#detailmode)
- [DrawSize](ue_ue.VREditorWidgetComponent.md#drawsize)
- [DrawingPolicy](ue_ue.VREditorWidgetComponent.md#drawingpolicy)
- [ExcludeForSpecificHLODLevels](ue_ue.VREditorWidgetComponent.md#excludeforspecifichlodlevels)
- [GeometryMode](ue_ue.VREditorWidgetComponent.md#geometrymode)
- [IndirectLightingCacheQuality](ue_ue.VREditorWidgetComponent.md#indirectlightingcachequality)
- [LDMaxDrawDistance](ue_ue.VREditorWidgetComponent.md#ldmaxdrawdistance)
- [LODParentPrimitive](ue_ue.VREditorWidgetComponent.md#lodparentprimitive)
- [LayerZOrder](ue_ue.VREditorWidgetComponent.md#layerzorder)
- [LightingChannels](ue_ue.VREditorWidgetComponent.md#lightingchannels)
- [LightmapType](ue_ue.VREditorWidgetComponent.md#lightmaptype)
- [LpvBiasMultiplier](ue_ue.VREditorWidgetComponent.md#lpvbiasmultiplier)
- [MaskedMaterial](ue_ue.VREditorWidgetComponent.md#maskedmaterial)
- [MaskedMaterial\_OneSided](ue_ue.VREditorWidgetComponent.md#maskedmaterial_onesided)
- [MaterialInstance](ue_ue.VREditorWidgetComponent.md#materialinstance)
- [MinDrawDistance](ue_ue.VREditorWidgetComponent.md#mindrawdistance)
- [Mobility](ue_ue.VREditorWidgetComponent.md#mobility)
- [MoveIgnoreActors](ue_ue.VREditorWidgetComponent.md#moveignoreactors)
- [MoveIgnoreComponents](ue_ue.VREditorWidgetComponent.md#moveignorecomponents)
- [OnBeginCursorOver](ue_ue.VREditorWidgetComponent.md#onbegincursorover)
- [OnClicked](ue_ue.VREditorWidgetComponent.md#onclicked)
- [OnComponentActivated](ue_ue.VREditorWidgetComponent.md#oncomponentactivated)
- [OnComponentBeginOverlap](ue_ue.VREditorWidgetComponent.md#oncomponentbeginoverlap)
- [OnComponentDeactivated](ue_ue.VREditorWidgetComponent.md#oncomponentdeactivated)
- [OnComponentEndOverlap](ue_ue.VREditorWidgetComponent.md#oncomponentendoverlap)
- [OnComponentHit](ue_ue.VREditorWidgetComponent.md#oncomponenthit)
- [OnComponentSleep](ue_ue.VREditorWidgetComponent.md#oncomponentsleep)
- [OnComponentWake](ue_ue.VREditorWidgetComponent.md#oncomponentwake)
- [OnEndCursorOver](ue_ue.VREditorWidgetComponent.md#onendcursorover)
- [OnInputTouchBegin](ue_ue.VREditorWidgetComponent.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.VREditorWidgetComponent.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.VREditorWidgetComponent.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.VREditorWidgetComponent.md#oninputtouchleave)
- [OnReleased](ue_ue.VREditorWidgetComponent.md#onreleased)
- [OpacityFromTexture](ue_ue.VREditorWidgetComponent.md#opacityfromtexture)
- [OpaqueMaterial](ue_ue.VREditorWidgetComponent.md#opaquematerial)
- [OpaqueMaterial\_OneSided](ue_ue.VREditorWidgetComponent.md#opaquematerial_onesided)
- [OverrideMaterials](ue_ue.VREditorWidgetComponent.md#overridematerials)
- [OwnerPlayer](ue_ue.VREditorWidgetComponent.md#ownerplayer)
- [PhysicsVolume](ue_ue.VREditorWidgetComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.VREditorWidgetComponent.md#physicsvolumechangeddelegate)
- [Pivot](ue_ue.VREditorWidgetComponent.md#pivot)
- [PrimaryComponentTick](ue_ue.VREditorWidgetComponent.md#primarycomponenttick)
- [RedrawTime](ue_ue.VREditorWidgetComponent.md#redrawtime)
- [RelativeLocation](ue_ue.VREditorWidgetComponent.md#relativelocation)
- [RelativeRotation](ue_ue.VREditorWidgetComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.VREditorWidgetComponent.md#relativescale3d)
- [RenderTarget](ue_ue.VREditorWidgetComponent.md#rendertarget)
- [RuntimeVirtualTextures](ue_ue.VREditorWidgetComponent.md#runtimevirtualtextures)
- [SharedLayerName](ue_ue.VREditorWidgetComponent.md#sharedlayername)
- [Space](ue_ue.VREditorWidgetComponent.md#space)
- [TickWhenOffscreen](ue_ue.VREditorWidgetComponent.md#tickwhenoffscreen)
- [TimingPolicy](ue_ue.VREditorWidgetComponent.md#timingpolicy)
- [TintColorAndOpacity](ue_ue.VREditorWidgetComponent.md#tintcolorandopacity)
- [TranslucencySortPriority](ue_ue.VREditorWidgetComponent.md#translucencysortpriority)
- [TranslucentMaterial](ue_ue.VREditorWidgetComponent.md#translucentmaterial)
- [TranslucentMaterial\_OneSided](ue_ue.VREditorWidgetComponent.md#translucentmaterial_onesided)
- [UCSModifiedProperties](ue_ue.VREditorWidgetComponent.md#ucsmodifiedproperties)
- [ViewOwnerDepthPriorityGroup](ue_ue.VREditorWidgetComponent.md#viewownerdepthprioritygroup)
- [VirtualTextureCullMips](ue_ue.VREditorWidgetComponent.md#virtualtexturecullmips)
- [VirtualTextureLodBias](ue_ue.VREditorWidgetComponent.md#virtualtexturelodbias)
- [VirtualTextureMinCoverage](ue_ue.VREditorWidgetComponent.md#virtualtexturemincoverage)
- [VirtualTextureRenderPassType](ue_ue.VREditorWidgetComponent.md#virtualtexturerenderpasstype)
- [VisibilityId](ue_ue.VREditorWidgetComponent.md#visibilityid)
- [Widget](ue_ue.VREditorWidgetComponent.md#widget)
- [WidgetClass](ue_ue.VREditorWidgetComponent.md#widgetclass)
- [WindowVisibility](ue_ue.VREditorWidgetComponent.md#windowvisibility)
- [\_\_tid\_ActorComponent\_\_](ue_ue.VREditorWidgetComponent.md#__tid_actorcomponent__)
- [\_\_tid\_MeshComponent\_\_](ue_ue.VREditorWidgetComponent.md#__tid_meshcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.VREditorWidgetComponent.md#__tid_object__)
- [\_\_tid\_PrimitiveComponent\_\_](ue_ue.VREditorWidgetComponent.md#__tid_primitivecomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.VREditorWidgetComponent.md#__tid_scenecomponent__)
- [\_\_tid\_VREditorWidgetComponent\_\_](ue_ue.VREditorWidgetComponent.md#__tid_vreditorwidgetcomponent__)
- [\_\_tid\_WidgetComponent\_\_](ue_ue.VREditorWidgetComponent.md#__tid_widgetcomponent__)
- [bAbsoluteLocation](ue_ue.VREditorWidgetComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.VREditorWidgetComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.VREditorWidgetComponent.md#babsolutescale)
- [bAddedToScreen](ue_ue.VREditorWidgetComponent.md#baddedtoscreen)
- [bAffectDistanceFieldLighting](ue_ue.VREditorWidgetComponent.md#baffectdistancefieldlighting)
- [bAffectDynamicIndirectLighting](ue_ue.VREditorWidgetComponent.md#baffectdynamicindirectlighting)
- [bAllowCullDistanceVolume](ue_ue.VREditorWidgetComponent.md#ballowculldistancevolume)
- [bAlwaysCreatePhysicsState](ue_ue.VREditorWidgetComponent.md#balwayscreatephysicsstate)
- [bApplyGammaCorrection](ue_ue.VREditorWidgetComponent.md#bapplygammacorrection)
- [bApplyImpulseOnDamage](ue_ue.VREditorWidgetComponent.md#bapplyimpulseondamage)
- [bAutoActivate](ue_ue.VREditorWidgetComponent.md#bautoactivate)
- [bBatchImpostersAsInstances](ue_ue.VREditorWidgetComponent.md#bbatchimpostersasinstances)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.VREditorWidgetComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.VREditorWidgetComponent.md#bcaneveraffectnavigation)
- [bCastCinematicShadow](ue_ue.VREditorWidgetComponent.md#bcastcinematicshadow)
- [bCastDynamicShadow](ue_ue.VREditorWidgetComponent.md#bcastdynamicshadow)
- [bCastFarShadow](ue_ue.VREditorWidgetComponent.md#bcastfarshadow)
- [bCastHiddenShadow](ue_ue.VREditorWidgetComponent.md#bcasthiddenshadow)
- [bCastInsetShadow](ue_ue.VREditorWidgetComponent.md#bcastinsetshadow)
- [bCastShadowAsTwoSided](ue_ue.VREditorWidgetComponent.md#bcastshadowastwosided)
- [bCastStaticShadow](ue_ue.VREditorWidgetComponent.md#bcaststaticshadow)
- [bCastVolumetricTranslucentShadow](ue_ue.VREditorWidgetComponent.md#bcastvolumetrictranslucentshadow)
- [bComponentToWorldUpdated](ue_ue.VREditorWidgetComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.VREditorWidgetComponent.md#bcreatedbyconstructionscript)
- [bDrawAtDesiredSize](ue_ue.VREditorWidgetComponent.md#bdrawatdesiredsize)
- [bEditTimeUsable](ue_ue.VREditorWidgetComponent.md#bedittimeusable)
- [bEditableWhenInherited](ue_ue.VREditorWidgetComponent.md#beditablewheninherited)
- [bEnableAutoLODGeneration](ue_ue.VREditorWidgetComponent.md#benableautolodgeneration)
- [bEnableMaterialParameterCaching](ue_ue.VREditorWidgetComponent.md#benablematerialparametercaching)
- [bExcludeFromLightAttachmentGroup](ue_ue.VREditorWidgetComponent.md#bexcludefromlightattachmentgroup)
- [bForceMipStreaming](ue_ue.VREditorWidgetComponent.md#bforcemipstreaming)
- [bGenerateOverlapEvents](ue_ue.VREditorWidgetComponent.md#bgenerateoverlapevents)
- [bHasCustomNavigableGeometry](ue_ue.VREditorWidgetComponent.md#bhascustomnavigablegeometry)
- [bHasEverDrawn](ue_ue.VREditorWidgetComponent.md#bhaseverdrawn)
- [bHasMotionBlurVelocityMeshes](ue_ue.VREditorWidgetComponent.md#bhasmotionblurvelocitymeshes)
- [bHasPerInstanceHitProxies](ue_ue.VREditorWidgetComponent.md#bhasperinstancehitproxies)
- [bHiddenInGame](ue_ue.VREditorWidgetComponent.md#bhiddeningame)
- [bIgnoreRadialForce](ue_ue.VREditorWidgetComponent.md#bignoreradialforce)
- [bIgnoreRadialImpulse](ue_ue.VREditorWidgetComponent.md#bignoreradialimpulse)
- [bInstanceComponent](ue_ue.VREditorWidgetComponent.md#binstancecomponent)
- [bIsActive](ue_ue.VREditorWidgetComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.VREditorWidgetComponent.md#biseditoronly)
- [bIsHovering](ue_ue.VREditorWidgetComponent.md#bishovering)
- [bIsTwoSided](ue_ue.VREditorWidgetComponent.md#bistwosided)
- [bIsVisualizationComponent](ue_ue.VREditorWidgetComponent.md#bisvisualizationcomponent)
- [bLightAsIfStatic](ue_ue.VREditorWidgetComponent.md#blightasifstatic)
- [bLightAttachmentsAsGroup](ue_ue.VREditorWidgetComponent.md#blightattachmentsasgroup)
- [bManuallyRedraw](ue_ue.VREditorWidgetComponent.md#bmanuallyredraw)
- [bMultiBodyOverlap](ue_ue.VREditorWidgetComponent.md#bmultibodyoverlap)
- [bNetAddressable](ue_ue.VREditorWidgetComponent.md#bnetaddressable)
- [bNeverDistanceCull](ue_ue.VREditorWidgetComponent.md#bneverdistancecull)
- [bOnlyOwnerSee](ue_ue.VREditorWidgetComponent.md#bonlyownersee)
- [bOwnerNoSee](ue_ue.VREditorWidgetComponent.md#bownernosee)
- [bReceiveHardwareInput](ue_ue.VREditorWidgetComponent.md#breceivehardwareinput)
- [bReceiveMobileCSMShadows](ue_ue.VREditorWidgetComponent.md#breceivemobilecsmshadows)
- [bReceivesDecals](ue_ue.VREditorWidgetComponent.md#breceivesdecals)
- [bRedrawRequested](ue_ue.VREditorWidgetComponent.md#bredrawrequested)
- [bRenderCustomDepth](ue_ue.VREditorWidgetComponent.md#brendercustomdepth)
- [bRenderInDepthPass](ue_ue.VREditorWidgetComponent.md#brenderindepthpass)
- [bRenderInMainPass](ue_ue.VREditorWidgetComponent.md#brenderinmainpass)
- [bReplicatePhysicsToAutonomousProxy](ue_ue.VREditorWidgetComponent.md#breplicatephysicstoautonomousproxy)
- [bReplicates](ue_ue.VREditorWidgetComponent.md#breplicates)
- [bReturnMaterialOnMove](ue_ue.VREditorWidgetComponent.md#breturnmaterialonmove)
- [bSelectable](ue_ue.VREditorWidgetComponent.md#bselectable)
- [bSelfShadowOnly](ue_ue.VREditorWidgetComponent.md#bselfshadowonly)
- [bShouldBeAttached](ue_ue.VREditorWidgetComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.VREditorWidgetComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.VREditorWidgetComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.VREditorWidgetComponent.md#bshouldupdatephysicsvolume)
- [bSingleSampleShadowFromStationaryLights](ue_ue.VREditorWidgetComponent.md#bsinglesampleshadowfromstationarylights)
- [bTraceComplexOnMove](ue_ue.VREditorWidgetComponent.md#btracecomplexonmove)
- [bTreatAsBackgroundForOcclusion](ue_ue.VREditorWidgetComponent.md#btreatasbackgroundforocclusion)
- [bUseAsOccluder](ue_ue.VREditorWidgetComponent.md#buseasoccluder)
- [bUseAttachParentBound](ue_ue.VREditorWidgetComponent.md#buseattachparentbound)
- [bUseEditorCompositing](ue_ue.VREditorWidgetComponent.md#buseeditorcompositing)
- [bUseMaxLODAsImposter](ue_ue.VREditorWidgetComponent.md#busemaxlodasimposter)
- [bUseViewOwnerDepthPriorityGroup](ue_ue.VREditorWidgetComponent.md#buseviewownerdepthprioritygroup)
- [bVisible](ue_ue.VREditorWidgetComponent.md#bvisible)
- [bVisibleInRayTracing](ue_ue.VREditorWidgetComponent.md#bvisibleinraytracing)
- [bVisibleInReflectionCaptures](ue_ue.VREditorWidgetComponent.md#bvisibleinreflectioncaptures)
- [bVisualizeComponent](ue_ue.VREditorWidgetComponent.md#bvisualizecomponent)
- [bWindowFocusable](ue_ue.VREditorWidgetComponent.md#bwindowfocusable)

### Methods

- [Activate](ue_ue.VREditorWidgetComponent.md#activate)
- [AddAngularImpulse](ue_ue.VREditorWidgetComponent.md#addangularimpulse)
- [AddAngularImpulseInDegrees](ue_ue.VREditorWidgetComponent.md#addangularimpulseindegrees)
- [AddAngularImpulseInRadians](ue_ue.VREditorWidgetComponent.md#addangularimpulseinradians)
- [AddForce](ue_ue.VREditorWidgetComponent.md#addforce)
- [AddForceAtLocation](ue_ue.VREditorWidgetComponent.md#addforceatlocation)
- [AddForceAtLocationLocal](ue_ue.VREditorWidgetComponent.md#addforceatlocationlocal)
- [AddImpulse](ue_ue.VREditorWidgetComponent.md#addimpulse)
- [AddImpulseAtLocation](ue_ue.VREditorWidgetComponent.md#addimpulseatlocation)
- [AddRadialForce](ue_ue.VREditorWidgetComponent.md#addradialforce)
- [AddRadialImpulse](ue_ue.VREditorWidgetComponent.md#addradialimpulse)
- [AddTickPrerequisiteActor](ue_ue.VREditorWidgetComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.VREditorWidgetComponent.md#addtickprerequisitecomponent)
- [AddTorque](ue_ue.VREditorWidgetComponent.md#addtorque)
- [AddTorqueInDegrees](ue_ue.VREditorWidgetComponent.md#addtorqueindegrees)
- [AddTorqueInRadians](ue_ue.VREditorWidgetComponent.md#addtorqueinradians)
- [CanCharacterStepUp](ue_ue.VREditorWidgetComponent.md#cancharacterstepup)
- [ClearMoveIgnoreActors](ue_ue.VREditorWidgetComponent.md#clearmoveignoreactors)
- [ClearMoveIgnoreComponents](ue_ue.VREditorWidgetComponent.md#clearmoveignorecomponents)
- [ComponentHasTag](ue_ue.VREditorWidgetComponent.md#componenthastag)
- [CopyArrayOfMoveIgnoreActors](ue_ue.VREditorWidgetComponent.md#copyarrayofmoveignoreactors)
- [CopyArrayOfMoveIgnoreComponents](ue_ue.VREditorWidgetComponent.md#copyarrayofmoveignorecomponents)
- [CreateAndSetMaterialInstanceDynamic](ue_ue.VREditorWidgetComponent.md#createandsetmaterialinstancedynamic)
- [CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.VREditorWidgetComponent.md#createandsetmaterialinstancedynamicfrommaterial)
- [CreateDefaultSubobject](ue_ue.VREditorWidgetComponent.md#createdefaultsubobject)
- [CreateDynamicMaterialInstance](ue_ue.VREditorWidgetComponent.md#createdynamicmaterialinstance)
- [Deactivate](ue_ue.VREditorWidgetComponent.md#deactivate)
- [DetachFromParent](ue_ue.VREditorWidgetComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.VREditorWidgetComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.VREditorWidgetComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.VREditorWidgetComponent.md#getallsocketnames)
- [GetAngularDamping](ue_ue.VREditorWidgetComponent.md#getangulardamping)
- [GetAttachParent](ue_ue.VREditorWidgetComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.VREditorWidgetComponent.md#getattachsocketname)
- [GetCenterOfMass](ue_ue.VREditorWidgetComponent.md#getcenterofmass)
- [GetChildComponent](ue_ue.VREditorWidgetComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.VREditorWidgetComponent.md#getchildrencomponents)
- [GetClass](ue_ue.VREditorWidgetComponent.md#getclass)
- [GetClosestPointOnCollision](ue_ue.VREditorWidgetComponent.md#getclosestpointoncollision)
- [GetCollisionEnabled](ue_ue.VREditorWidgetComponent.md#getcollisionenabled)
- [GetCollisionObjectType](ue_ue.VREditorWidgetComponent.md#getcollisionobjecttype)
- [GetCollisionProfileName](ue_ue.VREditorWidgetComponent.md#getcollisionprofilename)
- [GetCollisionResponseToChannel](ue_ue.VREditorWidgetComponent.md#getcollisionresponsetochannel)
- [GetComponentTickInterval](ue_ue.VREditorWidgetComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.VREditorWidgetComponent.md#getcomponentvelocity)
- [GetCurrentDrawSize](ue_ue.VREditorWidgetComponent.md#getcurrentdrawsize)
- [GetCylinderArcAngle](ue_ue.VREditorWidgetComponent.md#getcylinderarcangle)
- [GetDrawAtDesiredSize](ue_ue.VREditorWidgetComponent.md#getdrawatdesiredsize)
- [GetDrawSize](ue_ue.VREditorWidgetComponent.md#getdrawsize)
- [GetForwardVector](ue_ue.VREditorWidgetComponent.md#getforwardvector)
- [GetGenerateOverlapEvents](ue_ue.VREditorWidgetComponent.md#getgenerateoverlapevents)
- [GetGeometryMode](ue_ue.VREditorWidgetComponent.md#getgeometrymode)
- [GetInertiaTensor](ue_ue.VREditorWidgetComponent.md#getinertiatensor)
- [GetLinearDamping](ue_ue.VREditorWidgetComponent.md#getlineardamping)
- [GetManuallyRedraw](ue_ue.VREditorWidgetComponent.md#getmanuallyredraw)
- [GetMass](ue_ue.VREditorWidgetComponent.md#getmass)
- [GetMassScale](ue_ue.VREditorWidgetComponent.md#getmassscale)
- [GetMaterial](ue_ue.VREditorWidgetComponent.md#getmaterial)
- [GetMaterialFromCollisionFaceIndex](ue_ue.VREditorWidgetComponent.md#getmaterialfromcollisionfaceindex)
- [GetMaterialIndex](ue_ue.VREditorWidgetComponent.md#getmaterialindex)
- [GetMaterialInstance](ue_ue.VREditorWidgetComponent.md#getmaterialinstance)
- [GetMaterialSlotNames](ue_ue.VREditorWidgetComponent.md#getmaterialslotnames)
- [GetMaterials](ue_ue.VREditorWidgetComponent.md#getmaterials)
- [GetName](ue_ue.VREditorWidgetComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.VREditorWidgetComponent.md#getnumchildrencomponents)
- [GetNumMaterials](ue_ue.VREditorWidgetComponent.md#getnummaterials)
- [GetOuter](ue_ue.VREditorWidgetComponent.md#getouter)
- [GetOverlappingActors](ue_ue.VREditorWidgetComponent.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.VREditorWidgetComponent.md#getoverlappingcomponents)
- [GetOwner](ue_ue.VREditorWidgetComponent.md#getowner)
- [GetOwnerPlayer](ue_ue.VREditorWidgetComponent.md#getownerplayer)
- [GetParentComponents](ue_ue.VREditorWidgetComponent.md#getparentcomponents)
- [GetPhysicsAngularVelocity](ue_ue.VREditorWidgetComponent.md#getphysicsangularvelocity)
- [GetPhysicsAngularVelocityInDegrees](ue_ue.VREditorWidgetComponent.md#getphysicsangularvelocityindegrees)
- [GetPhysicsAngularVelocityInRadians](ue_ue.VREditorWidgetComponent.md#getphysicsangularvelocityinradians)
- [GetPhysicsLinearVelocity](ue_ue.VREditorWidgetComponent.md#getphysicslinearvelocity)
- [GetPhysicsLinearVelocityAtPoint](ue_ue.VREditorWidgetComponent.md#getphysicslinearvelocityatpoint)
- [GetPhysicsVolume](ue_ue.VREditorWidgetComponent.md#getphysicsvolume)
- [GetPivot](ue_ue.VREditorWidgetComponent.md#getpivot)
- [GetRedrawTime](ue_ue.VREditorWidgetComponent.md#getredrawtime)
- [GetRelativeTransform](ue_ue.VREditorWidgetComponent.md#getrelativetransform)
- [GetRenderTarget](ue_ue.VREditorWidgetComponent.md#getrendertarget)
- [GetRightVector](ue_ue.VREditorWidgetComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.VREditorWidgetComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.VREditorWidgetComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.VREditorWidgetComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.VREditorWidgetComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.VREditorWidgetComponent.md#getsockettransform)
- [GetTickWhenOffscreen](ue_ue.VREditorWidgetComponent.md#gettickwhenoffscreen)
- [GetTwoSided](ue_ue.VREditorWidgetComponent.md#gettwosided)
- [GetUpVector](ue_ue.VREditorWidgetComponent.md#getupvector)
- [GetUserWidgetObject](ue_ue.VREditorWidgetComponent.md#getuserwidgetobject)
- [GetWalkableSlopeOverride](ue_ue.VREditorWidgetComponent.md#getwalkableslopeoverride)
- [GetWidgetSpace](ue_ue.VREditorWidgetComponent.md#getwidgetspace)
- [GetWindowFocusable](ue_ue.VREditorWidgetComponent.md#getwindowfocusable)
- [GetWindowVisiblility](ue_ue.VREditorWidgetComponent.md#getwindowvisiblility)
- [GetWorld](ue_ue.VREditorWidgetComponent.md#getworld)
- [IgnoreActorWhenMoving](ue_ue.VREditorWidgetComponent.md#ignoreactorwhenmoving)
- [IgnoreComponentWhenMoving](ue_ue.VREditorWidgetComponent.md#ignorecomponentwhenmoving)
- [IsActive](ue_ue.VREditorWidgetComponent.md#isactive)
- [IsAnyRigidBodyAwake](ue_ue.VREditorWidgetComponent.md#isanyrigidbodyawake)
- [IsAnySimulatingPhysics](ue_ue.VREditorWidgetComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.VREditorWidgetComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.VREditorWidgetComponent.md#iscomponenttickenabled)
- [IsGravityEnabled](ue_ue.VREditorWidgetComponent.md#isgravityenabled)
- [IsMaterialSlotNameValid](ue_ue.VREditorWidgetComponent.md#ismaterialslotnamevalid)
- [IsOverlappingActor](ue_ue.VREditorWidgetComponent.md#isoverlappingactor)
- [IsOverlappingComponent](ue_ue.VREditorWidgetComponent.md#isoverlappingcomponent)
- [IsSimulatingPhysics](ue_ue.VREditorWidgetComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.VREditorWidgetComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.VREditorWidgetComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.VREditorWidgetComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.VREditorWidgetComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.VREditorWidgetComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.VREditorWidgetComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.VREditorWidgetComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.VREditorWidgetComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.VREditorWidgetComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.VREditorWidgetComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.VREditorWidgetComponent.md#k2_attachtocomponent)
- [K2\_BoxOverlapComponent](ue_ue.VREditorWidgetComponent.md#k2_boxoverlapcomponent)
- [K2\_DestroyComponent](ue_ue.VREditorWidgetComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.VREditorWidgetComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.VREditorWidgetComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.VREditorWidgetComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.VREditorWidgetComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.VREditorWidgetComponent.md#k2_getcomponenttoworld)
- [K2\_IsCollisionEnabled](ue_ue.VREditorWidgetComponent.md#k2_iscollisionenabled)
- [K2\_IsPhysicsCollisionEnabled](ue_ue.VREditorWidgetComponent.md#k2_isphysicscollisionenabled)
- [K2\_IsQueryCollisionEnabled](ue_ue.VREditorWidgetComponent.md#k2_isquerycollisionenabled)
- [K2\_LineTraceComponent](ue_ue.VREditorWidgetComponent.md#k2_linetracecomponent)
- [K2\_SetRelativeLocation](ue_ue.VREditorWidgetComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.VREditorWidgetComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.VREditorWidgetComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.VREditorWidgetComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.VREditorWidgetComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.VREditorWidgetComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.VREditorWidgetComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.VREditorWidgetComponent.md#k2_setworldtransform)
- [K2\_SphereOverlapComponent](ue_ue.VREditorWidgetComponent.md#k2_sphereoverlapcomponent)
- [K2\_SphereTraceComponent](ue_ue.VREditorWidgetComponent.md#k2_spheretracecomponent)
- [OnRep\_AttachChildren](ue_ue.VREditorWidgetComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.VREditorWidgetComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.VREditorWidgetComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.VREditorWidgetComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.VREditorWidgetComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.VREditorWidgetComponent.md#onrep_visibility)
- [PrestreamTextures](ue_ue.VREditorWidgetComponent.md#prestreamtextures)
- [PutRigidBodyToSleep](ue_ue.VREditorWidgetComponent.md#putrigidbodytosleep)
- [ReceiveBeginPlay](ue_ue.VREditorWidgetComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.VREditorWidgetComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.VREditorWidgetComponent.md#receivetick)
- [RegisterComponent](ue_ue.VREditorWidgetComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.VREditorWidgetComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.VREditorWidgetComponent.md#removetickprerequisitecomponent)
- [RequestRedraw](ue_ue.VREditorWidgetComponent.md#requestredraw)
- [ResetRelativeTransform](ue_ue.VREditorWidgetComponent.md#resetrelativetransform)
- [ScaleByMomentOfInertia](ue_ue.VREditorWidgetComponent.md#scalebymomentofinertia)
- [SetAbsolute](ue_ue.VREditorWidgetComponent.md#setabsolute)
- [SetActive](ue_ue.VREditorWidgetComponent.md#setactive)
- [SetAllMassScale](ue_ue.VREditorWidgetComponent.md#setallmassscale)
- [SetAllPhysicsAngularVelocityInDegrees](ue_ue.VREditorWidgetComponent.md#setallphysicsangularvelocityindegrees)
- [SetAllPhysicsAngularVelocityInRadians](ue_ue.VREditorWidgetComponent.md#setallphysicsangularvelocityinradians)
- [SetAllPhysicsLinearVelocity](ue_ue.VREditorWidgetComponent.md#setallphysicslinearvelocity)
- [SetAllUseCCD](ue_ue.VREditorWidgetComponent.md#setalluseccd)
- [SetAngularDamping](ue_ue.VREditorWidgetComponent.md#setangulardamping)
- [SetAutoActivate](ue_ue.VREditorWidgetComponent.md#setautoactivate)
- [SetBackgroundColor](ue_ue.VREditorWidgetComponent.md#setbackgroundcolor)
- [SetBoundsScale](ue_ue.VREditorWidgetComponent.md#setboundsscale)
- [SetCastInsetShadow](ue_ue.VREditorWidgetComponent.md#setcastinsetshadow)
- [SetCastShadow](ue_ue.VREditorWidgetComponent.md#setcastshadow)
- [SetCenterOfMass](ue_ue.VREditorWidgetComponent.md#setcenterofmass)
- [SetCollisionEnabled](ue_ue.VREditorWidgetComponent.md#setcollisionenabled)
- [SetCollisionObjectType](ue_ue.VREditorWidgetComponent.md#setcollisionobjecttype)
- [SetCollisionProfileName](ue_ue.VREditorWidgetComponent.md#setcollisionprofilename)
- [SetCollisionResponseToAllChannels](ue_ue.VREditorWidgetComponent.md#setcollisionresponsetoallchannels)
- [SetCollisionResponseToChannel](ue_ue.VREditorWidgetComponent.md#setcollisionresponsetochannel)
- [SetComponentTickEnabled](ue_ue.VREditorWidgetComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.VREditorWidgetComponent.md#setcomponenttickinterval)
- [SetConstraintMode](ue_ue.VREditorWidgetComponent.md#setconstraintmode)
- [SetCullDistance](ue_ue.VREditorWidgetComponent.md#setculldistance)
- [SetCustomDepthStencilValue](ue_ue.VREditorWidgetComponent.md#setcustomdepthstencilvalue)
- [SetCustomDepthStencilWriteMask](ue_ue.VREditorWidgetComponent.md#setcustomdepthstencilwritemask)
- [SetCustomPrimitiveDataFloat](ue_ue.VREditorWidgetComponent.md#setcustomprimitivedatafloat)
- [SetCustomPrimitiveDataVector2](ue_ue.VREditorWidgetComponent.md#setcustomprimitivedatavector2)
- [SetCustomPrimitiveDataVector3](ue_ue.VREditorWidgetComponent.md#setcustomprimitivedatavector3)
- [SetCustomPrimitiveDataVector4](ue_ue.VREditorWidgetComponent.md#setcustomprimitivedatavector4)
- [SetCylinderArcAngle](ue_ue.VREditorWidgetComponent.md#setcylinderarcangle)
- [SetDrawAtDesiredSize](ue_ue.VREditorWidgetComponent.md#setdrawatdesiredsize)
- [SetDrawSize](ue_ue.VREditorWidgetComponent.md#setdrawsize)
- [SetEnableGravity](ue_ue.VREditorWidgetComponent.md#setenablegravity)
- [SetExcludeFromLightAttachmentGroup](ue_ue.VREditorWidgetComponent.md#setexcludefromlightattachmentgroup)
- [SetGenerateOverlapEvents](ue_ue.VREditorWidgetComponent.md#setgenerateoverlapevents)
- [SetGeometryMode](ue_ue.VREditorWidgetComponent.md#setgeometrymode)
- [SetHiddenInGame](ue_ue.VREditorWidgetComponent.md#sethiddeningame)
- [SetIsReplicated](ue_ue.VREditorWidgetComponent.md#setisreplicated)
- [SetLightAttachmentsAsGroup](ue_ue.VREditorWidgetComponent.md#setlightattachmentsasgroup)
- [SetLinearDamping](ue_ue.VREditorWidgetComponent.md#setlineardamping)
- [SetManuallyRedraw](ue_ue.VREditorWidgetComponent.md#setmanuallyredraw)
- [SetMassOverrideInKg](ue_ue.VREditorWidgetComponent.md#setmassoverrideinkg)
- [SetMassScale](ue_ue.VREditorWidgetComponent.md#setmassscale)
- [SetMaterial](ue_ue.VREditorWidgetComponent.md#setmaterial)
- [SetMaterialByName](ue_ue.VREditorWidgetComponent.md#setmaterialbyname)
- [SetMobility](ue_ue.VREditorWidgetComponent.md#setmobility)
- [SetNotifyRigidBodyCollision](ue_ue.VREditorWidgetComponent.md#setnotifyrigidbodycollision)
- [SetOnlyOwnerSee](ue_ue.VREditorWidgetComponent.md#setonlyownersee)
- [SetOwnerNoSee](ue_ue.VREditorWidgetComponent.md#setownernosee)
- [SetOwnerPlayer](ue_ue.VREditorWidgetComponent.md#setownerplayer)
- [SetPhysMaterialOverride](ue_ue.VREditorWidgetComponent.md#setphysmaterialoverride)
- [SetPhysicsAngularVelocity](ue_ue.VREditorWidgetComponent.md#setphysicsangularvelocity)
- [SetPhysicsAngularVelocityInDegrees](ue_ue.VREditorWidgetComponent.md#setphysicsangularvelocityindegrees)
- [SetPhysicsAngularVelocityInRadians](ue_ue.VREditorWidgetComponent.md#setphysicsangularvelocityinradians)
- [SetPhysicsLinearVelocity](ue_ue.VREditorWidgetComponent.md#setphysicslinearvelocity)
- [SetPhysicsMaxAngularVelocity](ue_ue.VREditorWidgetComponent.md#setphysicsmaxangularvelocity)
- [SetPhysicsMaxAngularVelocityInDegrees](ue_ue.VREditorWidgetComponent.md#setphysicsmaxangularvelocityindegrees)
- [SetPhysicsMaxAngularVelocityInRadians](ue_ue.VREditorWidgetComponent.md#setphysicsmaxangularvelocityinradians)
- [SetPivot](ue_ue.VREditorWidgetComponent.md#setpivot)
- [SetReceivesDecals](ue_ue.VREditorWidgetComponent.md#setreceivesdecals)
- [SetRedrawTime](ue_ue.VREditorWidgetComponent.md#setredrawtime)
- [SetRelativeScale3D](ue_ue.VREditorWidgetComponent.md#setrelativescale3d)
- [SetRenderCustomDepth](ue_ue.VREditorWidgetComponent.md#setrendercustomdepth)
- [SetRenderInMainPass](ue_ue.VREditorWidgetComponent.md#setrenderinmainpass)
- [SetScalarParameterValueOnMaterials](ue_ue.VREditorWidgetComponent.md#setscalarparametervalueonmaterials)
- [SetShouldUpdatePhysicsVolume](ue_ue.VREditorWidgetComponent.md#setshouldupdatephysicsvolume)
- [SetSimulatePhysics](ue_ue.VREditorWidgetComponent.md#setsimulatephysics)
- [SetSingleSampleShadowFromStationaryLights](ue_ue.VREditorWidgetComponent.md#setsinglesampleshadowfromstationarylights)
- [SetTickGroup](ue_ue.VREditorWidgetComponent.md#settickgroup)
- [SetTickWhenOffscreen](ue_ue.VREditorWidgetComponent.md#settickwhenoffscreen)
- [SetTickableWhenPaused](ue_ue.VREditorWidgetComponent.md#settickablewhenpaused)
- [SetTintColorAndOpacity](ue_ue.VREditorWidgetComponent.md#settintcolorandopacity)
- [SetTranslucentSortPriority](ue_ue.VREditorWidgetComponent.md#settranslucentsortpriority)
- [SetTwoSided](ue_ue.VREditorWidgetComponent.md#settwosided)
- [SetUseCCD](ue_ue.VREditorWidgetComponent.md#setuseccd)
- [SetVectorParameterValueOnMaterials](ue_ue.VREditorWidgetComponent.md#setvectorparametervalueonmaterials)
- [SetVisibility](ue_ue.VREditorWidgetComponent.md#setvisibility)
- [SetWalkableSlopeOverride](ue_ue.VREditorWidgetComponent.md#setwalkableslopeoverride)
- [SetWidget](ue_ue.VREditorWidgetComponent.md#setwidget)
- [SetWidgetSpace](ue_ue.VREditorWidgetComponent.md#setwidgetspace)
- [SetWindowFocusable](ue_ue.VREditorWidgetComponent.md#setwindowfocusable)
- [SetWindowVisibility](ue_ue.VREditorWidgetComponent.md#setwindowvisibility)
- [SetWorldScale3D](ue_ue.VREditorWidgetComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.VREditorWidgetComponent.md#setupattachment)
- [SnapTo](ue_ue.VREditorWidgetComponent.md#snapto)
- [ToggleActive](ue_ue.VREditorWidgetComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.VREditorWidgetComponent.md#togglevisibility)
- [WakeAllRigidBodies](ue_ue.VREditorWidgetComponent.md#wakeallrigidbodies)
- [WakeRigidBody](ue_ue.VREditorWidgetComponent.md#wakerigidbody)
- [Find](ue_ue.VREditorWidgetComponent.md#find)
- [Load](ue_ue.VREditorWidgetComponent.md#load)
- [StaticClass](ue_ue.VREditorWidgetComponent.md#staticclass)

## Constructors

### constructor

• **new VREditorWidgetComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[WidgetComponent](ue_ue.WidgetComponent.md).[constructor](ue_ue.WidgetComponent.md#constructor)

## Properties

### AlwaysLoadOnClient

• **AlwaysLoadOnClient**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[AlwaysLoadOnClient](ue_ue.WidgetComponent.md#alwaysloadonclient)

___

### AlwaysLoadOnServer

• **AlwaysLoadOnServer**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[AlwaysLoadOnServer](ue_ue.WidgetComponent.md#alwaysloadonserver)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[AssetUserData](ue_ue.WidgetComponent.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[AttachChildren](ue_ue.WidgetComponent.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[AttachParent](ue_ue.WidgetComponent.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[AttachSocketName](ue_ue.WidgetComponent.md#attachsocketname)

___

### BackgroundColor

• **BackgroundColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[BackgroundColor](ue_ue.WidgetComponent.md#backgroundcolor)

___

### BlendMode

• **BlendMode**: [`EWidgetBlendMode`](../enums/ue_ue.EWidgetBlendMode.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[BlendMode](ue_ue.WidgetComponent.md#blendmode)

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[BodyInstance](ue_ue.WidgetComponent.md#bodyinstance)

___

### BodySetup

• **BodySetup**: [`BodySetup`](ue_ue.BodySetup.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[BodySetup](ue_ue.WidgetComponent.md#bodysetup)

___

### BoundsScale

• **BoundsScale**: `number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[BoundsScale](ue_ue.WidgetComponent.md#boundsscale)

___

### CachedMaxDrawDistance

• **CachedMaxDrawDistance**: `number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[CachedMaxDrawDistance](ue_ue.WidgetComponent.md#cachedmaxdrawdistance)

___

### CanBeCharacterBase

• **CanBeCharacterBase**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[CanBeCharacterBase](ue_ue.WidgetComponent.md#canbecharacterbase)

___

### CanCharacterStepUpOn

• **CanCharacterStepUpOn**: [`ECanBeCharacterBase`](../enums/ue_ue.ECanBeCharacterBase.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[CanCharacterStepUpOn](ue_ue.WidgetComponent.md#cancharacterstepupon)

___

### CastShadow

• **CastShadow**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[CastShadow](ue_ue.WidgetComponent.md#castshadow)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[ClientAttachedChildren](ue_ue.WidgetComponent.md#clientattachedchildren)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[ComponentTags](ue_ue.WidgetComponent.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[ComponentVelocity](ue_ue.WidgetComponent.md#componentvelocity)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[CreationMethod](ue_ue.WidgetComponent.md#creationmethod)

___

### CurrentDrawSize

• **CurrentDrawSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[CurrentDrawSize](ue_ue.WidgetComponent.md#currentdrawsize)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[CustomDepthStencilValue](ue_ue.WidgetComponent.md#customdepthstencilvalue)

___

### CustomDepthStencilWriteMask

• **CustomDepthStencilWriteMask**: [`ERendererStencilMask`](../enums/ue_ue.ERendererStencilMask.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[CustomDepthStencilWriteMask](ue_ue.WidgetComponent.md#customdepthstencilwritemask)

___

### CustomPrimitiveData

• **CustomPrimitiveData**: [`CustomPrimitiveData`](ue_ue.CustomPrimitiveData.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[CustomPrimitiveData](ue_ue.WidgetComponent.md#customprimitivedata)

___

### CylinderArcAngle

• **CylinderArcAngle**: `number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[CylinderArcAngle](ue_ue.WidgetComponent.md#cylinderarcangle)

___

### DepthPriorityGroup

• **DepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[DepthPriorityGroup](ue_ue.WidgetComponent.md#depthprioritygroup)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[DetailMode](ue_ue.WidgetComponent.md#detailmode)

___

### DrawSize

• **DrawSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[DrawSize](ue_ue.WidgetComponent.md#drawsize)

___

### DrawingPolicy

• **DrawingPolicy**: [`EVREditorWidgetDrawingPolicy`](../enums/ue_ue.EVREditorWidgetDrawingPolicy.md)

___

### ExcludeForSpecificHLODLevels

• **ExcludeForSpecificHLODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[ExcludeForSpecificHLODLevels](ue_ue.WidgetComponent.md#excludeforspecifichlodlevels)

___

### GeometryMode

• **GeometryMode**: [`EWidgetGeometryMode`](../enums/ue_ue.EWidgetGeometryMode.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GeometryMode](ue_ue.WidgetComponent.md#geometrymode)

___

### IndirectLightingCacheQuality

• **IndirectLightingCacheQuality**: [`EIndirectLightingCacheQuality`](../enums/ue_ue.EIndirectLightingCacheQuality.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[IndirectLightingCacheQuality](ue_ue.WidgetComponent.md#indirectlightingcachequality)

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[LDMaxDrawDistance](ue_ue.WidgetComponent.md#ldmaxdrawdistance)

___

### LODParentPrimitive

• **LODParentPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[LODParentPrimitive](ue_ue.WidgetComponent.md#lodparentprimitive)

___

### LayerZOrder

• **LayerZOrder**: `number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[LayerZOrder](ue_ue.WidgetComponent.md#layerzorder)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[LightingChannels](ue_ue.WidgetComponent.md#lightingchannels)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[LightmapType](ue_ue.WidgetComponent.md#lightmaptype)

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[LpvBiasMultiplier](ue_ue.WidgetComponent.md#lpvbiasmultiplier)

___

### MaskedMaterial

• **MaskedMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[MaskedMaterial](ue_ue.WidgetComponent.md#maskedmaterial)

___

### MaskedMaterial\_OneSided

• **MaskedMaterial\_OneSided**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[MaskedMaterial_OneSided](ue_ue.WidgetComponent.md#maskedmaterial_onesided)

___

### MaterialInstance

• **MaterialInstance**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[MaterialInstance](ue_ue.WidgetComponent.md#materialinstance)

___

### MinDrawDistance

• **MinDrawDistance**: `number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[MinDrawDistance](ue_ue.WidgetComponent.md#mindrawdistance)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[Mobility](ue_ue.WidgetComponent.md#mobility)

___

### MoveIgnoreActors

• **MoveIgnoreActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[MoveIgnoreActors](ue_ue.WidgetComponent.md#moveignoreactors)

___

### MoveIgnoreComponents

• **MoveIgnoreComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[MoveIgnoreComponents](ue_ue.WidgetComponent.md#moveignorecomponents)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnBeginCursorOver](ue_ue.WidgetComponent.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnClicked](ue_ue.WidgetComponent.md#onclicked)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnComponentActivated](ue_ue.WidgetComponent.md#oncomponentactivated)

___

### OnComponentBeginOverlap

• **OnComponentBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`, `bFromSweep`: `boolean`, `SweepResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnComponentBeginOverlap](ue_ue.WidgetComponent.md#oncomponentbeginoverlap)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnComponentDeactivated](ue_ue.WidgetComponent.md#oncomponentdeactivated)

___

### OnComponentEndOverlap

• **OnComponentEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherBodyIndex`: `number`) => `void`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnComponentEndOverlap](ue_ue.WidgetComponent.md#oncomponentendoverlap)

___

### OnComponentHit

• **OnComponentHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`HitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherComp`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnComponentHit](ue_ue.WidgetComponent.md#oncomponenthit)

___

### OnComponentSleep

• **OnComponentSleep**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SleepingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnComponentSleep](ue_ue.WidgetComponent.md#oncomponentsleep)

___

### OnComponentWake

• **OnComponentWake**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`WakingComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`) => `void`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnComponentWake](ue_ue.WidgetComponent.md#oncomponentwake)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnEndCursorOver](ue_ue.WidgetComponent.md#onendcursorover)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnInputTouchBegin](ue_ue.WidgetComponent.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnInputTouchEnd](ue_ue.WidgetComponent.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnInputTouchEnter](ue_ue.WidgetComponent.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnInputTouchLeave](ue_ue.WidgetComponent.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnReleased](ue_ue.WidgetComponent.md#onreleased)

___

### OpacityFromTexture

• **OpacityFromTexture**: `number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OpacityFromTexture](ue_ue.WidgetComponent.md#opacityfromtexture)

___

### OpaqueMaterial

• **OpaqueMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OpaqueMaterial](ue_ue.WidgetComponent.md#opaquematerial)

___

### OpaqueMaterial\_OneSided

• **OpaqueMaterial\_OneSided**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OpaqueMaterial_OneSided](ue_ue.WidgetComponent.md#opaquematerial_onesided)

___

### OverrideMaterials

• **OverrideMaterials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OverrideMaterials](ue_ue.WidgetComponent.md#overridematerials)

___

### OwnerPlayer

• **OwnerPlayer**: [`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OwnerPlayer](ue_ue.WidgetComponent.md#ownerplayer)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[PhysicsVolume](ue_ue.WidgetComponent.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.WidgetComponent.md#physicsvolumechangeddelegate)

___

### Pivot

• **Pivot**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[Pivot](ue_ue.WidgetComponent.md#pivot)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[PrimaryComponentTick](ue_ue.WidgetComponent.md#primarycomponenttick)

___

### RedrawTime

• **RedrawTime**: `number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[RedrawTime](ue_ue.WidgetComponent.md#redrawtime)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[RelativeLocation](ue_ue.WidgetComponent.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[RelativeRotation](ue_ue.WidgetComponent.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[RelativeScale3D](ue_ue.WidgetComponent.md#relativescale3d)

___

### RenderTarget

• **RenderTarget**: [`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[RenderTarget](ue_ue.WidgetComponent.md#rendertarget)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[RuntimeVirtualTextures](ue_ue.WidgetComponent.md#runtimevirtualtextures)

___

### SharedLayerName

• **SharedLayerName**: `string`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[SharedLayerName](ue_ue.WidgetComponent.md#sharedlayername)

___

### Space

• **Space**: [`EWidgetSpace`](../enums/ue_ue.EWidgetSpace.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[Space](ue_ue.WidgetComponent.md#space)

___

### TickWhenOffscreen

• **TickWhenOffscreen**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[TickWhenOffscreen](ue_ue.WidgetComponent.md#tickwhenoffscreen)

___

### TimingPolicy

• **TimingPolicy**: [`EWidgetTimingPolicy`](../enums/ue_ue.EWidgetTimingPolicy.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[TimingPolicy](ue_ue.WidgetComponent.md#timingpolicy)

___

### TintColorAndOpacity

• **TintColorAndOpacity**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[TintColorAndOpacity](ue_ue.WidgetComponent.md#tintcolorandopacity)

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[TranslucencySortPriority](ue_ue.WidgetComponent.md#translucencysortpriority)

___

### TranslucentMaterial

• **TranslucentMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[TranslucentMaterial](ue_ue.WidgetComponent.md#translucentmaterial)

___

### TranslucentMaterial\_OneSided

• **TranslucentMaterial\_OneSided**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[TranslucentMaterial_OneSided](ue_ue.WidgetComponent.md#translucentmaterial_onesided)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[UCSModifiedProperties](ue_ue.WidgetComponent.md#ucsmodifiedproperties)

___

### ViewOwnerDepthPriorityGroup

• **ViewOwnerDepthPriorityGroup**: [`ESceneDepthPriorityGroup`](../enums/ue_ue.ESceneDepthPriorityGroup.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[ViewOwnerDepthPriorityGroup](ue_ue.WidgetComponent.md#viewownerdepthprioritygroup)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[VirtualTextureCullMips](ue_ue.WidgetComponent.md#virtualtexturecullmips)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[VirtualTextureLodBias](ue_ue.WidgetComponent.md#virtualtexturelodbias)

___

### VirtualTextureMinCoverage

• **VirtualTextureMinCoverage**: `number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[VirtualTextureMinCoverage](ue_ue.WidgetComponent.md#virtualtexturemincoverage)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[VirtualTextureRenderPassType](ue_ue.WidgetComponent.md#virtualtexturerenderpasstype)

___

### VisibilityId

• **VisibilityId**: `number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[VisibilityId](ue_ue.WidgetComponent.md#visibilityid)

___

### Widget

• **Widget**: [`UserWidget`](ue_ue.UserWidget.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[Widget](ue_ue.WidgetComponent.md#widget)

___

### WidgetClass

• **WidgetClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[WidgetClass](ue_ue.WidgetComponent.md#widgetclass)

___

### WindowVisibility

• **WindowVisibility**: [`EWindowVisibility`](../enums/ue_ue.EWindowVisibility.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[WindowVisibility](ue_ue.WidgetComponent.md#windowvisibility)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[__tid_ActorComponent__](ue_ue.WidgetComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_MeshComponent\_\_

• **\_\_tid\_MeshComponent\_\_**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[__tid_MeshComponent__](ue_ue.WidgetComponent.md#__tid_meshcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[__tid_Object__](ue_ue.WidgetComponent.md#__tid_object__)

___

### \_\_tid\_PrimitiveComponent\_\_

• **\_\_tid\_PrimitiveComponent\_\_**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[__tid_PrimitiveComponent__](ue_ue.WidgetComponent.md#__tid_primitivecomponent__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[__tid_SceneComponent__](ue_ue.WidgetComponent.md#__tid_scenecomponent__)

___

### \_\_tid\_VREditorWidgetComponent\_\_

• **\_\_tid\_VREditorWidgetComponent\_\_**: `boolean`

___

### \_\_tid\_WidgetComponent\_\_

• **\_\_tid\_WidgetComponent\_\_**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[__tid_WidgetComponent__](ue_ue.WidgetComponent.md#__tid_widgetcomponent__)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bAbsoluteLocation](ue_ue.WidgetComponent.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bAbsoluteRotation](ue_ue.WidgetComponent.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bAbsoluteScale](ue_ue.WidgetComponent.md#babsolutescale)

___

### bAddedToScreen

• **bAddedToScreen**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bAddedToScreen](ue_ue.WidgetComponent.md#baddedtoscreen)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bAffectDistanceFieldLighting](ue_ue.WidgetComponent.md#baffectdistancefieldlighting)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bAffectDynamicIndirectLighting](ue_ue.WidgetComponent.md#baffectdynamicindirectlighting)

___

### bAllowCullDistanceVolume

• **bAllowCullDistanceVolume**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bAllowCullDistanceVolume](ue_ue.WidgetComponent.md#ballowculldistancevolume)

___

### bAlwaysCreatePhysicsState

• **bAlwaysCreatePhysicsState**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bAlwaysCreatePhysicsState](ue_ue.WidgetComponent.md#balwayscreatephysicsstate)

___

### bApplyGammaCorrection

• **bApplyGammaCorrection**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bApplyGammaCorrection](ue_ue.WidgetComponent.md#bapplygammacorrection)

___

### bApplyImpulseOnDamage

• **bApplyImpulseOnDamage**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bApplyImpulseOnDamage](ue_ue.WidgetComponent.md#bapplyimpulseondamage)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bAutoActivate](ue_ue.WidgetComponent.md#bautoactivate)

___

### bBatchImpostersAsInstances

• **bBatchImpostersAsInstances**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bBatchImpostersAsInstances](ue_ue.WidgetComponent.md#bbatchimpostersasinstances)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.WidgetComponent.md#bboundschangetriggersstreamingdatarebuild)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bCanEverAffectNavigation](ue_ue.WidgetComponent.md#bcaneveraffectnavigation)

___

### bCastCinematicShadow

• **bCastCinematicShadow**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bCastCinematicShadow](ue_ue.WidgetComponent.md#bcastcinematicshadow)

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bCastDynamicShadow](ue_ue.WidgetComponent.md#bcastdynamicshadow)

___

### bCastFarShadow

• **bCastFarShadow**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bCastFarShadow](ue_ue.WidgetComponent.md#bcastfarshadow)

___

### bCastHiddenShadow

• **bCastHiddenShadow**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bCastHiddenShadow](ue_ue.WidgetComponent.md#bcasthiddenshadow)

___

### bCastInsetShadow

• **bCastInsetShadow**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bCastInsetShadow](ue_ue.WidgetComponent.md#bcastinsetshadow)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bCastShadowAsTwoSided](ue_ue.WidgetComponent.md#bcastshadowastwosided)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bCastStaticShadow](ue_ue.WidgetComponent.md#bcaststaticshadow)

___

### bCastVolumetricTranslucentShadow

• **bCastVolumetricTranslucentShadow**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bCastVolumetricTranslucentShadow](ue_ue.WidgetComponent.md#bcastvolumetrictranslucentshadow)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bComponentToWorldUpdated](ue_ue.WidgetComponent.md#bcomponenttoworldupdated)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bCreatedByConstructionScript](ue_ue.WidgetComponent.md#bcreatedbyconstructionscript)

___

### bDrawAtDesiredSize

• **bDrawAtDesiredSize**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bDrawAtDesiredSize](ue_ue.WidgetComponent.md#bdrawatdesiredsize)

___

### bEditTimeUsable

• **bEditTimeUsable**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bEditTimeUsable](ue_ue.WidgetComponent.md#bedittimeusable)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bEditableWhenInherited](ue_ue.WidgetComponent.md#beditablewheninherited)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bEnableAutoLODGeneration](ue_ue.WidgetComponent.md#benableautolodgeneration)

___

### bEnableMaterialParameterCaching

• **bEnableMaterialParameterCaching**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bEnableMaterialParameterCaching](ue_ue.WidgetComponent.md#benablematerialparametercaching)

___

### bExcludeFromLightAttachmentGroup

• **bExcludeFromLightAttachmentGroup**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bExcludeFromLightAttachmentGroup](ue_ue.WidgetComponent.md#bexcludefromlightattachmentgroup)

___

### bForceMipStreaming

• **bForceMipStreaming**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bForceMipStreaming](ue_ue.WidgetComponent.md#bforcemipstreaming)

___

### bGenerateOverlapEvents

• **bGenerateOverlapEvents**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bGenerateOverlapEvents](ue_ue.WidgetComponent.md#bgenerateoverlapevents)

___

### bHasCustomNavigableGeometry

• **bHasCustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bHasCustomNavigableGeometry](ue_ue.WidgetComponent.md#bhascustomnavigablegeometry)

___

### bHasEverDrawn

• **bHasEverDrawn**: `boolean`

___

### bHasMotionBlurVelocityMeshes

• **bHasMotionBlurVelocityMeshes**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bHasMotionBlurVelocityMeshes](ue_ue.WidgetComponent.md#bhasmotionblurvelocitymeshes)

___

### bHasPerInstanceHitProxies

• **bHasPerInstanceHitProxies**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bHasPerInstanceHitProxies](ue_ue.WidgetComponent.md#bhasperinstancehitproxies)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bHiddenInGame](ue_ue.WidgetComponent.md#bhiddeningame)

___

### bIgnoreRadialForce

• **bIgnoreRadialForce**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bIgnoreRadialForce](ue_ue.WidgetComponent.md#bignoreradialforce)

___

### bIgnoreRadialImpulse

• **bIgnoreRadialImpulse**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bIgnoreRadialImpulse](ue_ue.WidgetComponent.md#bignoreradialimpulse)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bInstanceComponent](ue_ue.WidgetComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bIsActive](ue_ue.WidgetComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bIsEditorOnly](ue_ue.WidgetComponent.md#biseditoronly)

___

### bIsHovering

• **bIsHovering**: `boolean`

___

### bIsTwoSided

• **bIsTwoSided**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bIsTwoSided](ue_ue.WidgetComponent.md#bistwosided)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bIsVisualizationComponent](ue_ue.WidgetComponent.md#bisvisualizationcomponent)

___

### bLightAsIfStatic

• **bLightAsIfStatic**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bLightAsIfStatic](ue_ue.WidgetComponent.md#blightasifstatic)

___

### bLightAttachmentsAsGroup

• **bLightAttachmentsAsGroup**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bLightAttachmentsAsGroup](ue_ue.WidgetComponent.md#blightattachmentsasgroup)

___

### bManuallyRedraw

• **bManuallyRedraw**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bManuallyRedraw](ue_ue.WidgetComponent.md#bmanuallyredraw)

___

### bMultiBodyOverlap

• **bMultiBodyOverlap**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bMultiBodyOverlap](ue_ue.WidgetComponent.md#bmultibodyoverlap)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bNetAddressable](ue_ue.WidgetComponent.md#bnetaddressable)

___

### bNeverDistanceCull

• **bNeverDistanceCull**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bNeverDistanceCull](ue_ue.WidgetComponent.md#bneverdistancecull)

___

### bOnlyOwnerSee

• **bOnlyOwnerSee**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bOnlyOwnerSee](ue_ue.WidgetComponent.md#bonlyownersee)

___

### bOwnerNoSee

• **bOwnerNoSee**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bOwnerNoSee](ue_ue.WidgetComponent.md#bownernosee)

___

### bReceiveHardwareInput

• **bReceiveHardwareInput**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bReceiveHardwareInput](ue_ue.WidgetComponent.md#breceivehardwareinput)

___

### bReceiveMobileCSMShadows

• **bReceiveMobileCSMShadows**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bReceiveMobileCSMShadows](ue_ue.WidgetComponent.md#breceivemobilecsmshadows)

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bReceivesDecals](ue_ue.WidgetComponent.md#breceivesdecals)

___

### bRedrawRequested

• **bRedrawRequested**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bRedrawRequested](ue_ue.WidgetComponent.md#bredrawrequested)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bRenderCustomDepth](ue_ue.WidgetComponent.md#brendercustomdepth)

___

### bRenderInDepthPass

• **bRenderInDepthPass**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bRenderInDepthPass](ue_ue.WidgetComponent.md#brenderindepthpass)

___

### bRenderInMainPass

• **bRenderInMainPass**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bRenderInMainPass](ue_ue.WidgetComponent.md#brenderinmainpass)

___

### bReplicatePhysicsToAutonomousProxy

• **bReplicatePhysicsToAutonomousProxy**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bReplicatePhysicsToAutonomousProxy](ue_ue.WidgetComponent.md#breplicatephysicstoautonomousproxy)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bReplicates](ue_ue.WidgetComponent.md#breplicates)

___

### bReturnMaterialOnMove

• **bReturnMaterialOnMove**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bReturnMaterialOnMove](ue_ue.WidgetComponent.md#breturnmaterialonmove)

___

### bSelectable

• **bSelectable**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bSelectable](ue_ue.WidgetComponent.md#bselectable)

___

### bSelfShadowOnly

• **bSelfShadowOnly**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bSelfShadowOnly](ue_ue.WidgetComponent.md#bselfshadowonly)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bShouldBeAttached](ue_ue.WidgetComponent.md#bshouldbeattached)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.WidgetComponent.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.WidgetComponent.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.WidgetComponent.md#bshouldupdatephysicsvolume)

___

### bSingleSampleShadowFromStationaryLights

• **bSingleSampleShadowFromStationaryLights**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bSingleSampleShadowFromStationaryLights](ue_ue.WidgetComponent.md#bsinglesampleshadowfromstationarylights)

___

### bTraceComplexOnMove

• **bTraceComplexOnMove**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bTraceComplexOnMove](ue_ue.WidgetComponent.md#btracecomplexonmove)

___

### bTreatAsBackgroundForOcclusion

• **bTreatAsBackgroundForOcclusion**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bTreatAsBackgroundForOcclusion](ue_ue.WidgetComponent.md#btreatasbackgroundforocclusion)

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bUseAsOccluder](ue_ue.WidgetComponent.md#buseasoccluder)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bUseAttachParentBound](ue_ue.WidgetComponent.md#buseattachparentbound)

___

### bUseEditorCompositing

• **bUseEditorCompositing**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bUseEditorCompositing](ue_ue.WidgetComponent.md#buseeditorcompositing)

___

### bUseMaxLODAsImposter

• **bUseMaxLODAsImposter**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bUseMaxLODAsImposter](ue_ue.WidgetComponent.md#busemaxlodasimposter)

___

### bUseViewOwnerDepthPriorityGroup

• **bUseViewOwnerDepthPriorityGroup**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bUseViewOwnerDepthPriorityGroup](ue_ue.WidgetComponent.md#buseviewownerdepthprioritygroup)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bVisible](ue_ue.WidgetComponent.md#bvisible)

___

### bVisibleInRayTracing

• **bVisibleInRayTracing**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bVisibleInRayTracing](ue_ue.WidgetComponent.md#bvisibleinraytracing)

___

### bVisibleInReflectionCaptures

• **bVisibleInReflectionCaptures**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bVisibleInReflectionCaptures](ue_ue.WidgetComponent.md#bvisibleinreflectioncaptures)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bVisualizeComponent](ue_ue.WidgetComponent.md#bvisualizecomponent)

___

### bWindowFocusable

• **bWindowFocusable**: `boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[bWindowFocusable](ue_ue.WidgetComponent.md#bwindowfocusable)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[Activate](ue_ue.WidgetComponent.md#activate)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[AddAngularImpulse](ue_ue.WidgetComponent.md#addangularimpulse)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[AddAngularImpulseInDegrees](ue_ue.WidgetComponent.md#addangularimpulseindegrees)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[AddAngularImpulseInRadians](ue_ue.WidgetComponent.md#addangularimpulseinradians)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[AddForce](ue_ue.WidgetComponent.md#addforce)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[AddForceAtLocation](ue_ue.WidgetComponent.md#addforceatlocation)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[AddForceAtLocationLocal](ue_ue.WidgetComponent.md#addforceatlocationlocal)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[AddImpulse](ue_ue.WidgetComponent.md#addimpulse)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[AddImpulseAtLocation](ue_ue.WidgetComponent.md#addimpulseatlocation)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[AddRadialForce](ue_ue.WidgetComponent.md#addradialforce)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[AddRadialImpulse](ue_ue.WidgetComponent.md#addradialimpulse)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[AddTickPrerequisiteActor](ue_ue.WidgetComponent.md#addtickprerequisiteactor)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[AddTickPrerequisiteComponent](ue_ue.WidgetComponent.md#addtickprerequisitecomponent)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[AddTorque](ue_ue.WidgetComponent.md#addtorque)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[AddTorqueInDegrees](ue_ue.WidgetComponent.md#addtorqueindegrees)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[AddTorqueInRadians](ue_ue.WidgetComponent.md#addtorqueinradians)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[CanCharacterStepUp](ue_ue.WidgetComponent.md#cancharacterstepup)

___

### ClearMoveIgnoreActors

▸ **ClearMoveIgnoreActors**(): `void`

#### Returns

`void`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[ClearMoveIgnoreActors](ue_ue.WidgetComponent.md#clearmoveignoreactors)

___

### ClearMoveIgnoreComponents

▸ **ClearMoveIgnoreComponents**(): `void`

#### Returns

`void`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[ClearMoveIgnoreComponents](ue_ue.WidgetComponent.md#clearmoveignorecomponents)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[ComponentHasTag](ue_ue.WidgetComponent.md#componenthastag)

___

### CopyArrayOfMoveIgnoreActors

▸ **CopyArrayOfMoveIgnoreActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[CopyArrayOfMoveIgnoreActors](ue_ue.WidgetComponent.md#copyarrayofmoveignoreactors)

___

### CopyArrayOfMoveIgnoreComponents

▸ **CopyArrayOfMoveIgnoreComponents**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[CopyArrayOfMoveIgnoreComponents](ue_ue.WidgetComponent.md#copyarrayofmoveignorecomponents)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[CreateAndSetMaterialInstanceDynamic](ue_ue.WidgetComponent.md#createandsetmaterialinstancedynamic)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[CreateAndSetMaterialInstanceDynamicFromMaterial](ue_ue.WidgetComponent.md#createandsetmaterialinstancedynamicfrommaterial)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[CreateDefaultSubobject](ue_ue.WidgetComponent.md#createdefaultsubobject)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[CreateDynamicMaterialInstance](ue_ue.WidgetComponent.md#createdynamicmaterialinstance)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[Deactivate](ue_ue.WidgetComponent.md#deactivate)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[DetachFromParent](ue_ue.WidgetComponent.md#detachfromparent)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[DoesSocketExist](ue_ue.WidgetComponent.md#doessocketexist)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[ExecuteUbergraph](ue_ue.WidgetComponent.md#executeubergraph)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetAllSocketNames](ue_ue.WidgetComponent.md#getallsocketnames)

___

### GetAngularDamping

▸ **GetAngularDamping**(): `number`

#### Returns

`number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetAngularDamping](ue_ue.WidgetComponent.md#getangulardamping)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetAttachParent](ue_ue.WidgetComponent.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetAttachSocketName](ue_ue.WidgetComponent.md#getattachsocketname)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetCenterOfMass](ue_ue.WidgetComponent.md#getcenterofmass)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetChildComponent](ue_ue.WidgetComponent.md#getchildcomponent)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetChildrenComponents](ue_ue.WidgetComponent.md#getchildrencomponents)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetClass](ue_ue.WidgetComponent.md#getclass)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetClosestPointOnCollision](ue_ue.WidgetComponent.md#getclosestpointoncollision)

___

### GetCollisionEnabled

▸ **GetCollisionEnabled**(): [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Returns

[`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetCollisionEnabled](ue_ue.WidgetComponent.md#getcollisionenabled)

___

### GetCollisionObjectType

▸ **GetCollisionObjectType**(): [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Returns

[`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetCollisionObjectType](ue_ue.WidgetComponent.md#getcollisionobjecttype)

___

### GetCollisionProfileName

▸ **GetCollisionProfileName**(): `string`

#### Returns

`string`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetCollisionProfileName](ue_ue.WidgetComponent.md#getcollisionprofilename)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetCollisionResponseToChannel](ue_ue.WidgetComponent.md#getcollisionresponsetochannel)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetComponentTickInterval](ue_ue.WidgetComponent.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetComponentVelocity](ue_ue.WidgetComponent.md#getcomponentvelocity)

___

### GetCurrentDrawSize

▸ **GetCurrentDrawSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetCurrentDrawSize](ue_ue.WidgetComponent.md#getcurrentdrawsize)

___

### GetCylinderArcAngle

▸ **GetCylinderArcAngle**(): `number`

#### Returns

`number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetCylinderArcAngle](ue_ue.WidgetComponent.md#getcylinderarcangle)

___

### GetDrawAtDesiredSize

▸ **GetDrawAtDesiredSize**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetDrawAtDesiredSize](ue_ue.WidgetComponent.md#getdrawatdesiredsize)

___

### GetDrawSize

▸ **GetDrawSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetDrawSize](ue_ue.WidgetComponent.md#getdrawsize)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetForwardVector](ue_ue.WidgetComponent.md#getforwardvector)

___

### GetGenerateOverlapEvents

▸ **GetGenerateOverlapEvents**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetGenerateOverlapEvents](ue_ue.WidgetComponent.md#getgenerateoverlapevents)

___

### GetGeometryMode

▸ **GetGeometryMode**(): [`EWidgetGeometryMode`](../enums/ue_ue.EWidgetGeometryMode.md)

#### Returns

[`EWidgetGeometryMode`](../enums/ue_ue.EWidgetGeometryMode.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetGeometryMode](ue_ue.WidgetComponent.md#getgeometrymode)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetInertiaTensor](ue_ue.WidgetComponent.md#getinertiatensor)

___

### GetLinearDamping

▸ **GetLinearDamping**(): `number`

#### Returns

`number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetLinearDamping](ue_ue.WidgetComponent.md#getlineardamping)

___

### GetManuallyRedraw

▸ **GetManuallyRedraw**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetManuallyRedraw](ue_ue.WidgetComponent.md#getmanuallyredraw)

___

### GetMass

▸ **GetMass**(): `number`

#### Returns

`number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetMass](ue_ue.WidgetComponent.md#getmass)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetMassScale](ue_ue.WidgetComponent.md#getmassscale)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetMaterial](ue_ue.WidgetComponent.md#getmaterial)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetMaterialFromCollisionFaceIndex](ue_ue.WidgetComponent.md#getmaterialfromcollisionfaceindex)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetMaterialIndex](ue_ue.WidgetComponent.md#getmaterialindex)

___

### GetMaterialInstance

▸ **GetMaterialInstance**(): [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Returns

[`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetMaterialInstance](ue_ue.WidgetComponent.md#getmaterialinstance)

___

### GetMaterialSlotNames

▸ **GetMaterialSlotNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetMaterialSlotNames](ue_ue.WidgetComponent.md#getmaterialslotnames)

___

### GetMaterials

▸ **GetMaterials**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetMaterials](ue_ue.WidgetComponent.md#getmaterials)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetName](ue_ue.WidgetComponent.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetNumChildrenComponents](ue_ue.WidgetComponent.md#getnumchildrencomponents)

___

### GetNumMaterials

▸ **GetNumMaterials**(): `number`

#### Returns

`number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetNumMaterials](ue_ue.WidgetComponent.md#getnummaterials)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetOuter](ue_ue.WidgetComponent.md#getouter)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetOverlappingActors](ue_ue.WidgetComponent.md#getoverlappingactors)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetOverlappingComponents](ue_ue.WidgetComponent.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetOwner](ue_ue.WidgetComponent.md#getowner)

___

### GetOwnerPlayer

▸ **GetOwnerPlayer**(): [`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Returns

[`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetOwnerPlayer](ue_ue.WidgetComponent.md#getownerplayer)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetParentComponents](ue_ue.WidgetComponent.md#getparentcomponents)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetPhysicsAngularVelocity](ue_ue.WidgetComponent.md#getphysicsangularvelocity)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetPhysicsAngularVelocityInDegrees](ue_ue.WidgetComponent.md#getphysicsangularvelocityindegrees)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetPhysicsAngularVelocityInRadians](ue_ue.WidgetComponent.md#getphysicsangularvelocityinradians)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetPhysicsLinearVelocity](ue_ue.WidgetComponent.md#getphysicslinearvelocity)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetPhysicsLinearVelocityAtPoint](ue_ue.WidgetComponent.md#getphysicslinearvelocityatpoint)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetPhysicsVolume](ue_ue.WidgetComponent.md#getphysicsvolume)

___

### GetPivot

▸ **GetPivot**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetPivot](ue_ue.WidgetComponent.md#getpivot)

___

### GetRedrawTime

▸ **GetRedrawTime**(): `number`

#### Returns

`number`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetRedrawTime](ue_ue.WidgetComponent.md#getredrawtime)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetRelativeTransform](ue_ue.WidgetComponent.md#getrelativetransform)

___

### GetRenderTarget

▸ **GetRenderTarget**(): [`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)

#### Returns

[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetRenderTarget](ue_ue.WidgetComponent.md#getrendertarget)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetRightVector](ue_ue.WidgetComponent.md#getrightvector)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.WidgetComponent.md#getshouldupdatephysicsvolume)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetSocketLocation](ue_ue.WidgetComponent.md#getsocketlocation)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetSocketQuaternion](ue_ue.WidgetComponent.md#getsocketquaternion)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetSocketRotation](ue_ue.WidgetComponent.md#getsocketrotation)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[GetSocketTransform](ue_ue.WidgetComponent.md#getsockettransform)

___

### GetTickWhenOffscreen

▸ **GetTickWhenOffscreen**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetTickWhenOffscreen](ue_ue.WidgetComponent.md#gettickwhenoffscreen)

___

### GetTwoSided

▸ **GetTwoSided**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetTwoSided](ue_ue.WidgetComponent.md#gettwosided)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetUpVector](ue_ue.WidgetComponent.md#getupvector)

___

### GetUserWidgetObject

▸ **GetUserWidgetObject**(): [`UserWidget`](ue_ue.UserWidget.md)

#### Returns

[`UserWidget`](ue_ue.UserWidget.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetUserWidgetObject](ue_ue.WidgetComponent.md#getuserwidgetobject)

___

### GetWalkableSlopeOverride

▸ **GetWalkableSlopeOverride**(): [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Returns

[`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetWalkableSlopeOverride](ue_ue.WidgetComponent.md#getwalkableslopeoverride)

___

### GetWidgetSpace

▸ **GetWidgetSpace**(): [`EWidgetSpace`](../enums/ue_ue.EWidgetSpace.md)

#### Returns

[`EWidgetSpace`](../enums/ue_ue.EWidgetSpace.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetWidgetSpace](ue_ue.WidgetComponent.md#getwidgetspace)

___

### GetWindowFocusable

▸ **GetWindowFocusable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetWindowFocusable](ue_ue.WidgetComponent.md#getwindowfocusable)

___

### GetWindowVisiblility

▸ **GetWindowVisiblility**(): [`EWindowVisibility`](../enums/ue_ue.EWindowVisibility.md)

#### Returns

[`EWindowVisibility`](../enums/ue_ue.EWindowVisibility.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetWindowVisiblility](ue_ue.WidgetComponent.md#getwindowvisiblility)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[GetWorld](ue_ue.WidgetComponent.md#getworld)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[IgnoreActorWhenMoving](ue_ue.WidgetComponent.md#ignoreactorwhenmoving)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[IgnoreComponentWhenMoving](ue_ue.WidgetComponent.md#ignorecomponentwhenmoving)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[IsActive](ue_ue.WidgetComponent.md#isactive)

___

### IsAnyRigidBodyAwake

▸ **IsAnyRigidBodyAwake**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[IsAnyRigidBodyAwake](ue_ue.WidgetComponent.md#isanyrigidbodyawake)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[IsAnySimulatingPhysics](ue_ue.WidgetComponent.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[IsBeingDestroyed](ue_ue.WidgetComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[IsComponentTickEnabled](ue_ue.WidgetComponent.md#iscomponenttickenabled)

___

### IsGravityEnabled

▸ **IsGravityEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[IsGravityEnabled](ue_ue.WidgetComponent.md#isgravityenabled)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[IsMaterialSlotNameValid](ue_ue.WidgetComponent.md#ismaterialslotnamevalid)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[IsOverlappingActor](ue_ue.WidgetComponent.md#isoverlappingactor)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[IsOverlappingComponent](ue_ue.WidgetComponent.md#isoverlappingcomponent)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[IsSimulatingPhysics](ue_ue.WidgetComponent.md#issimulatingphysics)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[IsVisible](ue_ue.WidgetComponent.md#isvisible)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_AddLocalOffset](ue_ue.WidgetComponent.md#k2_addlocaloffset)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_AddLocalRotation](ue_ue.WidgetComponent.md#k2_addlocalrotation)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_AddLocalTransform](ue_ue.WidgetComponent.md#k2_addlocaltransform)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_AddRelativeLocation](ue_ue.WidgetComponent.md#k2_addrelativelocation)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_AddRelativeRotation](ue_ue.WidgetComponent.md#k2_addrelativerotation)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_AddWorldOffset](ue_ue.WidgetComponent.md#k2_addworldoffset)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_AddWorldRotation](ue_ue.WidgetComponent.md#k2_addworldrotation)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_AddWorldTransform](ue_ue.WidgetComponent.md#k2_addworldtransform)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_AttachTo](ue_ue.WidgetComponent.md#k2_attachto)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_AttachToComponent](ue_ue.WidgetComponent.md#k2_attachtocomponent)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_BoxOverlapComponent](ue_ue.WidgetComponent.md#k2_boxoverlapcomponent)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_DestroyComponent](ue_ue.WidgetComponent.md#k2_destroycomponent)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_DetachFromComponent](ue_ue.WidgetComponent.md#k2_detachfromcomponent)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_GetComponentLocation](ue_ue.WidgetComponent.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_GetComponentRotation](ue_ue.WidgetComponent.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_GetComponentScale](ue_ue.WidgetComponent.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_GetComponentToWorld](ue_ue.WidgetComponent.md#k2_getcomponenttoworld)

___

### K2\_IsCollisionEnabled

▸ **K2_IsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_IsCollisionEnabled](ue_ue.WidgetComponent.md#k2_iscollisionenabled)

___

### K2\_IsPhysicsCollisionEnabled

▸ **K2_IsPhysicsCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_IsPhysicsCollisionEnabled](ue_ue.WidgetComponent.md#k2_isphysicscollisionenabled)

___

### K2\_IsQueryCollisionEnabled

▸ **K2_IsQueryCollisionEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_IsQueryCollisionEnabled](ue_ue.WidgetComponent.md#k2_isquerycollisionenabled)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_LineTraceComponent](ue_ue.WidgetComponent.md#k2_linetracecomponent)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_SetRelativeLocation](ue_ue.WidgetComponent.md#k2_setrelativelocation)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.WidgetComponent.md#k2_setrelativelocationandrotation)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_SetRelativeRotation](ue_ue.WidgetComponent.md#k2_setrelativerotation)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_SetRelativeTransform](ue_ue.WidgetComponent.md#k2_setrelativetransform)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_SetWorldLocation](ue_ue.WidgetComponent.md#k2_setworldlocation)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.WidgetComponent.md#k2_setworldlocationandrotation)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_SetWorldRotation](ue_ue.WidgetComponent.md#k2_setworldrotation)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_SetWorldTransform](ue_ue.WidgetComponent.md#k2_setworldtransform)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_SphereOverlapComponent](ue_ue.WidgetComponent.md#k2_sphereoverlapcomponent)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[K2_SphereTraceComponent](ue_ue.WidgetComponent.md#k2_spheretracecomponent)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnRep_AttachChildren](ue_ue.WidgetComponent.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnRep_AttachParent](ue_ue.WidgetComponent.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnRep_AttachSocketName](ue_ue.WidgetComponent.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnRep_IsActive](ue_ue.WidgetComponent.md#onrep_isactive)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[OnRep_Transform](ue_ue.WidgetComponent.md#onrep_transform)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[OnRep_Visibility](ue_ue.WidgetComponent.md#onrep_visibility)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[PrestreamTextures](ue_ue.WidgetComponent.md#prestreamtextures)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[PutRigidBodyToSleep](ue_ue.WidgetComponent.md#putrigidbodytosleep)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[ReceiveBeginPlay](ue_ue.WidgetComponent.md#receivebeginplay)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[ReceiveEndPlay](ue_ue.WidgetComponent.md#receiveendplay)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[ReceiveTick](ue_ue.WidgetComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[RegisterComponent](ue_ue.WidgetComponent.md#registercomponent)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[RemoveTickPrerequisiteActor](ue_ue.WidgetComponent.md#removetickprerequisiteactor)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.WidgetComponent.md#removetickprerequisitecomponent)

___

### RequestRedraw

▸ **RequestRedraw**(): `void`

#### Returns

`void`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[RequestRedraw](ue_ue.WidgetComponent.md#requestredraw)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[ResetRelativeTransform](ue_ue.WidgetComponent.md#resetrelativetransform)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[ScaleByMomentOfInertia](ue_ue.WidgetComponent.md#scalebymomentofinertia)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetAbsolute](ue_ue.WidgetComponent.md#setabsolute)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetActive](ue_ue.WidgetComponent.md#setactive)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetAllMassScale](ue_ue.WidgetComponent.md#setallmassscale)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetAllPhysicsAngularVelocityInDegrees](ue_ue.WidgetComponent.md#setallphysicsangularvelocityindegrees)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetAllPhysicsAngularVelocityInRadians](ue_ue.WidgetComponent.md#setallphysicsangularvelocityinradians)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetAllPhysicsLinearVelocity](ue_ue.WidgetComponent.md#setallphysicslinearvelocity)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetAllUseCCD](ue_ue.WidgetComponent.md#setalluseccd)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetAngularDamping](ue_ue.WidgetComponent.md#setangulardamping)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetAutoActivate](ue_ue.WidgetComponent.md#setautoactivate)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetBackgroundColor](ue_ue.WidgetComponent.md#setbackgroundcolor)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetBoundsScale](ue_ue.WidgetComponent.md#setboundsscale)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetCastInsetShadow](ue_ue.WidgetComponent.md#setcastinsetshadow)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetCastShadow](ue_ue.WidgetComponent.md#setcastshadow)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetCenterOfMass](ue_ue.WidgetComponent.md#setcenterofmass)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetCollisionEnabled](ue_ue.WidgetComponent.md#setcollisionenabled)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetCollisionObjectType](ue_ue.WidgetComponent.md#setcollisionobjecttype)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetCollisionProfileName](ue_ue.WidgetComponent.md#setcollisionprofilename)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetCollisionResponseToAllChannels](ue_ue.WidgetComponent.md#setcollisionresponsetoallchannels)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetCollisionResponseToChannel](ue_ue.WidgetComponent.md#setcollisionresponsetochannel)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetComponentTickEnabled](ue_ue.WidgetComponent.md#setcomponenttickenabled)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetComponentTickInterval](ue_ue.WidgetComponent.md#setcomponenttickinterval)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetConstraintMode](ue_ue.WidgetComponent.md#setconstraintmode)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetCullDistance](ue_ue.WidgetComponent.md#setculldistance)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetCustomDepthStencilValue](ue_ue.WidgetComponent.md#setcustomdepthstencilvalue)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetCustomDepthStencilWriteMask](ue_ue.WidgetComponent.md#setcustomdepthstencilwritemask)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetCustomPrimitiveDataFloat](ue_ue.WidgetComponent.md#setcustomprimitivedatafloat)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetCustomPrimitiveDataVector2](ue_ue.WidgetComponent.md#setcustomprimitivedatavector2)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetCustomPrimitiveDataVector3](ue_ue.WidgetComponent.md#setcustomprimitivedatavector3)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetCustomPrimitiveDataVector4](ue_ue.WidgetComponent.md#setcustomprimitivedatavector4)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetCylinderArcAngle](ue_ue.WidgetComponent.md#setcylinderarcangle)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetDrawAtDesiredSize](ue_ue.WidgetComponent.md#setdrawatdesiredsize)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetDrawSize](ue_ue.WidgetComponent.md#setdrawsize)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetEnableGravity](ue_ue.WidgetComponent.md#setenablegravity)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetExcludeFromLightAttachmentGroup](ue_ue.WidgetComponent.md#setexcludefromlightattachmentgroup)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetGenerateOverlapEvents](ue_ue.WidgetComponent.md#setgenerateoverlapevents)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetGeometryMode](ue_ue.WidgetComponent.md#setgeometrymode)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetHiddenInGame](ue_ue.WidgetComponent.md#sethiddeningame)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetIsReplicated](ue_ue.WidgetComponent.md#setisreplicated)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetLightAttachmentsAsGroup](ue_ue.WidgetComponent.md#setlightattachmentsasgroup)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetLinearDamping](ue_ue.WidgetComponent.md#setlineardamping)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetManuallyRedraw](ue_ue.WidgetComponent.md#setmanuallyredraw)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetMassOverrideInKg](ue_ue.WidgetComponent.md#setmassoverrideinkg)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetMassScale](ue_ue.WidgetComponent.md#setmassscale)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetMaterial](ue_ue.WidgetComponent.md#setmaterial)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetMaterialByName](ue_ue.WidgetComponent.md#setmaterialbyname)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetMobility](ue_ue.WidgetComponent.md#setmobility)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetNotifyRigidBodyCollision](ue_ue.WidgetComponent.md#setnotifyrigidbodycollision)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetOnlyOwnerSee](ue_ue.WidgetComponent.md#setonlyownersee)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetOwnerNoSee](ue_ue.WidgetComponent.md#setownernosee)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetOwnerPlayer](ue_ue.WidgetComponent.md#setownerplayer)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetPhysMaterialOverride](ue_ue.WidgetComponent.md#setphysmaterialoverride)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetPhysicsAngularVelocity](ue_ue.WidgetComponent.md#setphysicsangularvelocity)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetPhysicsAngularVelocityInDegrees](ue_ue.WidgetComponent.md#setphysicsangularvelocityindegrees)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetPhysicsAngularVelocityInRadians](ue_ue.WidgetComponent.md#setphysicsangularvelocityinradians)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetPhysicsLinearVelocity](ue_ue.WidgetComponent.md#setphysicslinearvelocity)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetPhysicsMaxAngularVelocity](ue_ue.WidgetComponent.md#setphysicsmaxangularvelocity)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetPhysicsMaxAngularVelocityInDegrees](ue_ue.WidgetComponent.md#setphysicsmaxangularvelocityindegrees)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetPhysicsMaxAngularVelocityInRadians](ue_ue.WidgetComponent.md#setphysicsmaxangularvelocityinradians)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetPivot](ue_ue.WidgetComponent.md#setpivot)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetReceivesDecals](ue_ue.WidgetComponent.md#setreceivesdecals)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetRedrawTime](ue_ue.WidgetComponent.md#setredrawtime)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetRelativeScale3D](ue_ue.WidgetComponent.md#setrelativescale3d)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetRenderCustomDepth](ue_ue.WidgetComponent.md#setrendercustomdepth)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetRenderInMainPass](ue_ue.WidgetComponent.md#setrenderinmainpass)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetScalarParameterValueOnMaterials](ue_ue.WidgetComponent.md#setscalarparametervalueonmaterials)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.WidgetComponent.md#setshouldupdatephysicsvolume)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetSimulatePhysics](ue_ue.WidgetComponent.md#setsimulatephysics)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetSingleSampleShadowFromStationaryLights](ue_ue.WidgetComponent.md#setsinglesampleshadowfromstationarylights)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetTickGroup](ue_ue.WidgetComponent.md#settickgroup)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetTickWhenOffscreen](ue_ue.WidgetComponent.md#settickwhenoffscreen)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetTickableWhenPaused](ue_ue.WidgetComponent.md#settickablewhenpaused)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetTintColorAndOpacity](ue_ue.WidgetComponent.md#settintcolorandopacity)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetTranslucentSortPriority](ue_ue.WidgetComponent.md#settranslucentsortpriority)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetTwoSided](ue_ue.WidgetComponent.md#settwosided)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetUseCCD](ue_ue.WidgetComponent.md#setuseccd)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetVectorParameterValueOnMaterials](ue_ue.WidgetComponent.md#setvectorparametervalueonmaterials)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetVisibility](ue_ue.WidgetComponent.md#setvisibility)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetWalkableSlopeOverride](ue_ue.WidgetComponent.md#setwalkableslopeoverride)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetWidget](ue_ue.WidgetComponent.md#setwidget)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetWidgetSpace](ue_ue.WidgetComponent.md#setwidgetspace)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetWindowFocusable](ue_ue.WidgetComponent.md#setwindowfocusable)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetWindowVisibility](ue_ue.WidgetComponent.md#setwindowvisibility)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetWorldScale3D](ue_ue.WidgetComponent.md#setworldscale3d)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SetupAttachment](ue_ue.WidgetComponent.md#setupattachment)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[SnapTo](ue_ue.WidgetComponent.md#snapto)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[ToggleActive](ue_ue.WidgetComponent.md#toggleactive)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[ToggleVisibility](ue_ue.WidgetComponent.md#togglevisibility)

___

### WakeAllRigidBodies

▸ **WakeAllRigidBodies**(): `void`

#### Returns

`void`

#### Inherited from

[WidgetComponent](ue_ue.WidgetComponent.md).[WakeAllRigidBodies](ue_ue.WidgetComponent.md#wakeallrigidbodies)

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

[WidgetComponent](ue_ue.WidgetComponent.md).[WakeRigidBody](ue_ue.WidgetComponent.md#wakerigidbody)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VREditorWidgetComponent`](ue_ue.VREditorWidgetComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VREditorWidgetComponent`](ue_ue.VREditorWidgetComponent.md)

#### Overrides

[WidgetComponent](ue_ue.WidgetComponent.md).[Find](ue_ue.WidgetComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`VREditorWidgetComponent`](ue_ue.VREditorWidgetComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VREditorWidgetComponent`](ue_ue.VREditorWidgetComponent.md)

#### Overrides

[WidgetComponent](ue_ue.WidgetComponent.md).[Load](ue_ue.WidgetComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[WidgetComponent](ue_ue.WidgetComponent.md).[StaticClass](ue_ue.WidgetComponent.md#staticclass)
