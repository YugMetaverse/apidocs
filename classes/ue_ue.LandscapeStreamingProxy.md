[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LandscapeStreamingProxy

# Class: LandscapeStreamingProxy

[ue/ue](../modules/ue_ue.md).LandscapeStreamingProxy

## Hierarchy

- [`LandscapeProxy`](ue_ue.LandscapeProxy.md)

  ↳ **`LandscapeStreamingProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.LandscapeStreamingProxy.md#constructor)

### Properties

- [ActorLabel](ue_ue.LandscapeStreamingProxy.md#actorlabel)
- [AttachmentReplication](ue_ue.LandscapeStreamingProxy.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.LandscapeStreamingProxy.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.LandscapeStreamingProxy.md#blueprintcreatedcomponents)
- [BodyInstance](ue_ue.LandscapeStreamingProxy.md#bodyinstance)
- [Children](ue_ue.LandscapeStreamingProxy.md#children)
- [CollisionComponents](ue_ue.LandscapeStreamingProxy.md#collisioncomponents)
- [CollisionMipLevel](ue_ue.LandscapeStreamingProxy.md#collisionmiplevel)
- [CollisionThickness](ue_ue.LandscapeStreamingProxy.md#collisionthickness)
- [ComponentScreenSizeToUseSubSections](ue_ue.LandscapeStreamingProxy.md#componentscreensizetousesubsections)
- [ComponentSizeQuads](ue_ue.LandscapeStreamingProxy.md#componentsizequads)
- [ControllingMatineeActors](ue_ue.LandscapeStreamingProxy.md#controllingmatineeactors)
- [CustomDepthStencilValue](ue_ue.LandscapeStreamingProxy.md#customdepthstencilvalue)
- [CustomTimeDilation](ue_ue.LandscapeStreamingProxy.md#customtimedilation)
- [DefaultPhysMaterial](ue_ue.LandscapeStreamingProxy.md#defaultphysmaterial)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.LandscapeStreamingProxy.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [EditorCachedLayerInfos](ue_ue.LandscapeStreamingProxy.md#editorcachedlayerinfos)
- [EditorLayerSettings](ue_ue.LandscapeStreamingProxy.md#editorlayersettings)
- [ExportLOD](ue_ue.LandscapeStreamingProxy.md#exportlod)
- [FolderPath](ue_ue.LandscapeStreamingProxy.md#folderpath)
- [FoliageComponents](ue_ue.LandscapeStreamingProxy.md#foliagecomponents)
- [GroupActor](ue_ue.LandscapeStreamingProxy.md#groupactor)
- [HiddenEditorViews](ue_ue.LandscapeStreamingProxy.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.LandscapeStreamingProxy.md#initiallifespan)
- [InputComponent](ue_ue.LandscapeStreamingProxy.md#inputcomponent)
- [InputPriority](ue_ue.LandscapeStreamingProxy.md#inputpriority)
- [InstanceComponents](ue_ue.LandscapeStreamingProxy.md#instancecomponents)
- [Instigator](ue_ue.LandscapeStreamingProxy.md#instigator)
- [LDMaxDrawDistance](ue_ue.LandscapeStreamingProxy.md#ldmaxdrawdistance)
- [LOD0DistributionSetting](ue_ue.LandscapeStreamingProxy.md#lod0distributionsetting)
- [LOD0ScreenSize](ue_ue.LandscapeStreamingProxy.md#lod0screensize)
- [LODDistanceFactor](ue_ue.LandscapeStreamingProxy.md#loddistancefactor)
- [LODDistributionSetting](ue_ue.LandscapeStreamingProxy.md#loddistributionsetting)
- [LODFalloff](ue_ue.LandscapeStreamingProxy.md#lodfalloff)
- [LandscapeActor](ue_ue.LandscapeStreamingProxy.md#landscapeactor)
- [LandscapeComponents](ue_ue.LandscapeStreamingProxy.md#landscapecomponents)
- [LandscapeGuid](ue_ue.LandscapeStreamingProxy.md#landscapeguid)
- [LandscapeHoleMaterial](ue_ue.LandscapeStreamingProxy.md#landscapeholematerial)
- [LandscapeMaterial](ue_ue.LandscapeStreamingProxy.md#landscapematerial)
- [LandscapeMaterialsOverride](ue_ue.LandscapeStreamingProxy.md#landscapematerialsoverride)
- [LandscapeSectionOffset](ue_ue.LandscapeStreamingProxy.md#landscapesectionoffset)
- [Layers](ue_ue.LandscapeStreamingProxy.md#layers)
- [LightingChannels](ue_ue.LandscapeStreamingProxy.md#lightingchannels)
- [LightmassSettings](ue_ue.LandscapeStreamingProxy.md#lightmasssettings)
- [MaxLODLevel](ue_ue.LandscapeStreamingProxy.md#maxlodlevel)
- [MaxPaintedLayersPerComponent](ue_ue.LandscapeStreamingProxy.md#maxpaintedlayerspercomponent)
- [MinNetUpdateFrequency](ue_ue.LandscapeStreamingProxy.md#minnetupdatefrequency)
- [NavigationGeometryGatheringMode](ue_ue.LandscapeStreamingProxy.md#navigationgeometrygatheringmode)
- [NegativeZBoundsExtension](ue_ue.LandscapeStreamingProxy.md#negativezboundsextension)
- [NetCullDistanceSquared](ue_ue.LandscapeStreamingProxy.md#netculldistancesquared)
- [NetDormancy](ue_ue.LandscapeStreamingProxy.md#netdormancy)
- [NetDriverName](ue_ue.LandscapeStreamingProxy.md#netdrivername)
- [NetPriority](ue_ue.LandscapeStreamingProxy.md#netpriority)
- [NetTag](ue_ue.LandscapeStreamingProxy.md#nettag)
- [NetUpdateFrequency](ue_ue.LandscapeStreamingProxy.md#netupdatefrequency)
- [NumSubsections](ue_ue.LandscapeStreamingProxy.md#numsubsections)
- [OccluderGeometryLOD](ue_ue.LandscapeStreamingProxy.md#occludergeometrylod)
- [OnActorBeginOverlap](ue_ue.LandscapeStreamingProxy.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.LandscapeStreamingProxy.md#onactorendoverlap)
- [OnActorHit](ue_ue.LandscapeStreamingProxy.md#onactorhit)
- [OnBeginCursorOver](ue_ue.LandscapeStreamingProxy.md#onbegincursorover)
- [OnClicked](ue_ue.LandscapeStreamingProxy.md#onclicked)
- [OnDestroyed](ue_ue.LandscapeStreamingProxy.md#ondestroyed)
- [OnEndCursorOver](ue_ue.LandscapeStreamingProxy.md#onendcursorover)
- [OnEndPlay](ue_ue.LandscapeStreamingProxy.md#onendplay)
- [OnInputTouchBegin](ue_ue.LandscapeStreamingProxy.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.LandscapeStreamingProxy.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.LandscapeStreamingProxy.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.LandscapeStreamingProxy.md#oninputtouchleave)
- [OnReleased](ue_ue.LandscapeStreamingProxy.md#onreleased)
- [OnTakeAnyDamage](ue_ue.LandscapeStreamingProxy.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.LandscapeStreamingProxy.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.LandscapeStreamingProxy.md#ontakeradialdamage)
- [Owner](ue_ue.LandscapeStreamingProxy.md#owner)
- [ParentComponent](ue_ue.LandscapeStreamingProxy.md#parentcomponent)
- [ParentComponentActor](ue_ue.LandscapeStreamingProxy.md#parentcomponentactor)
- [PivotOffset](ue_ue.LandscapeStreamingProxy.md#pivotoffset)
- [PositiveZBoundsExtension](ue_ue.LandscapeStreamingProxy.md#positivezboundsextension)
- [PreEditLandscapeHoleMaterial](ue_ue.LandscapeStreamingProxy.md#preeditlandscapeholematerial)
- [PreEditLandscapeMaterial](ue_ue.LandscapeStreamingProxy.md#preeditlandscapematerial)
- [PreEditLandscapeMaterialsOverride](ue_ue.LandscapeStreamingProxy.md#preeditlandscapematerialsoverride)
- [PrimaryActorTick](ue_ue.LandscapeStreamingProxy.md#primaryactortick)
- [ReimportHeightmapFilePath](ue_ue.LandscapeStreamingProxy.md#reimportheightmapfilepath)
- [RemoteRole](ue_ue.LandscapeStreamingProxy.md#remoterole)
- [ReplicatedMovement](ue_ue.LandscapeStreamingProxy.md#replicatedmovement)
- [Role](ue_ue.LandscapeStreamingProxy.md#role)
- [RootComponent](ue_ue.LandscapeStreamingProxy.md#rootcomponent)
- [RuntimeVirtualTextures](ue_ue.LandscapeStreamingProxy.md#runtimevirtualtextures)
- [SimpleCollisionMipLevel](ue_ue.LandscapeStreamingProxy.md#simplecollisionmiplevel)
- [SpawnCollisionHandlingMethod](ue_ue.LandscapeStreamingProxy.md#spawncollisionhandlingmethod)
- [SplineComponent](ue_ue.LandscapeStreamingProxy.md#splinecomponent)
- [SpriteScale](ue_ue.LandscapeStreamingProxy.md#spritescale)
- [StaticLightingLOD](ue_ue.LandscapeStreamingProxy.md#staticlightinglod)
- [StaticLightingResolution](ue_ue.LandscapeStreamingProxy.md#staticlightingresolution)
- [StreamingDistanceMultiplier](ue_ue.LandscapeStreamingProxy.md#streamingdistancemultiplier)
- [SubsectionSizeQuads](ue_ue.LandscapeStreamingProxy.md#subsectionsizequads)
- [Tags](ue_ue.LandscapeStreamingProxy.md#tags)
- [TargetDisplayOrder](ue_ue.LandscapeStreamingProxy.md#targetdisplayorder)
- [TargetDisplayOrderList](ue_ue.LandscapeStreamingProxy.md#targetdisplayorderlist)
- [TessellationComponentScreenSize](ue_ue.LandscapeStreamingProxy.md#tessellationcomponentscreensize)
- [TessellationComponentScreenSizeFalloff](ue_ue.LandscapeStreamingProxy.md#tessellationcomponentscreensizefalloff)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.LandscapeStreamingProxy.md#updateoverlapsmethodduringlevelstreaming)
- [UseTessellationComponentScreenSizeFalloff](ue_ue.LandscapeStreamingProxy.md#usetessellationcomponentscreensizefalloff)
- [VirtualTextureLodBias](ue_ue.LandscapeStreamingProxy.md#virtualtexturelodbias)
- [VirtualTextureNumLods](ue_ue.LandscapeStreamingProxy.md#virtualtexturenumlods)
- [VirtualTextureRenderPassType](ue_ue.LandscapeStreamingProxy.md#virtualtexturerenderpasstype)
- [WeightmapUsageMap](ue_ue.LandscapeStreamingProxy.md#weightmapusagemap)
- [\_\_tid\_Actor\_\_](ue_ue.LandscapeStreamingProxy.md#__tid_actor__)
- [\_\_tid\_LandscapeProxy\_\_](ue_ue.LandscapeStreamingProxy.md#__tid_landscapeproxy__)
- [\_\_tid\_LandscapeStreamingProxy\_\_](ue_ue.LandscapeStreamingProxy.md#__tid_landscapestreamingproxy__)
- [\_\_tid\_Object\_\_](ue_ue.LandscapeStreamingProxy.md#__tid_object__)
- [bActorEnableCollision](ue_ue.LandscapeStreamingProxy.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.LandscapeStreamingProxy.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.LandscapeStreamingProxy.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.LandscapeStreamingProxy.md#bactorseamlesstraveled)
- [bAffectDistanceFieldLighting](ue_ue.LandscapeStreamingProxy.md#baffectdistancefieldlighting)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.LandscapeStreamingProxy.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.LandscapeStreamingProxy.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.LandscapeStreamingProxy.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.LandscapeStreamingProxy.md#bautodestroywhenfinished)
- [bBakeMaterialPositionOffsetIntoCollision](ue_ue.LandscapeStreamingProxy.md#bbakematerialpositionoffsetintocollision)
- [bBlockInput](ue_ue.LandscapeStreamingProxy.md#bblockinput)
- [bCanBeDamaged](ue_ue.LandscapeStreamingProxy.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.LandscapeStreamingProxy.md#bcanbeincluster)
- [bCastFarShadow](ue_ue.LandscapeStreamingProxy.md#bcastfarshadow)
- [bCastShadowAsTwoSided](ue_ue.LandscapeStreamingProxy.md#bcastshadowastwosided)
- [bCastStaticShadow](ue_ue.LandscapeStreamingProxy.md#bcaststaticshadow)
- [bCollideWhenPlacing](ue_ue.LandscapeStreamingProxy.md#bcollidewhenplacing)
- [bEditable](ue_ue.LandscapeStreamingProxy.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.LandscapeStreamingProxy.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.LandscapeStreamingProxy.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.LandscapeStreamingProxy.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEvents](ue_ue.LandscapeStreamingProxy.md#bgenerateoverlapevents)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.LandscapeStreamingProxy.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHasLandscapeGrass](ue_ue.LandscapeStreamingProxy.md#bhaslandscapegrass)
- [bHasLayersContent](ue_ue.LandscapeStreamingProxy.md#bhaslayerscontent)
- [bHidden](ue_ue.LandscapeStreamingProxy.md#bhidden)
- [bHiddenEd](ue_ue.LandscapeStreamingProxy.md#bhiddened)
- [bHiddenEdLayer](ue_ue.LandscapeStreamingProxy.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.LandscapeStreamingProxy.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.LandscapeStreamingProxy.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.LandscapeStreamingProxy.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.LandscapeStreamingProxy.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.LandscapeStreamingProxy.md#biseditorpreviewactor)
- [bIsMovingToLevel](ue_ue.LandscapeStreamingProxy.md#bismovingtolevel)
- [bIsPerformingInteractiveActionOnLandscapeMaterialOverride](ue_ue.LandscapeStreamingProxy.md#bisperforminginteractiveactiononlandscapematerialoverride)
- [bListedInSceneOutliner](ue_ue.LandscapeStreamingProxy.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.LandscapeStreamingProxy.md#blocklocation)
- [bNetLoadOnClient](ue_ue.LandscapeStreamingProxy.md#bnetloadonclient)
- [bNetStartup](ue_ue.LandscapeStreamingProxy.md#bnetstartup)
- [bNetTemporary](ue_ue.LandscapeStreamingProxy.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.LandscapeStreamingProxy.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.LandscapeStreamingProxy.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.LandscapeStreamingProxy.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.LandscapeStreamingProxy.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.LandscapeStreamingProxy.md#brelevantfornetworkreplays)
- [bRenderCustomDepth](ue_ue.LandscapeStreamingProxy.md#brendercustomdepth)
- [bReplayRewindable](ue_ue.LandscapeStreamingProxy.md#breplayrewindable)
- [bReplicateMovement](ue_ue.LandscapeStreamingProxy.md#breplicatemovement)
- [bReplicates](ue_ue.LandscapeStreamingProxy.md#breplicates)
- [bTearOff](ue_ue.LandscapeStreamingProxy.md#btearoff)
- [bUseDynamicMaterialInstance](ue_ue.LandscapeStreamingProxy.md#busedynamicmaterialinstance)
- [bUseLandscapeForCullingInvisibleHLODVertices](ue_ue.LandscapeStreamingProxy.md#buselandscapeforcullinginvisiblehlodvertices)
- [bUseMaterialPositionOffsetInStaticLighting](ue_ue.LandscapeStreamingProxy.md#busematerialpositionoffsetinstaticlighting)
- [bUsedForNavigation](ue_ue.LandscapeStreamingProxy.md#busedfornavigation)

### Methods

- [ActorHasTag](ue_ue.LandscapeStreamingProxy.md#actorhastag)
- [AddComponent](ue_ue.LandscapeStreamingProxy.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.LandscapeStreamingProxy.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.LandscapeStreamingProxy.md#addtickprerequisitecomponent)
- [ChangeComponentScreenSizeToUseSubSections](ue_ue.LandscapeStreamingProxy.md#changecomponentscreensizetousesubsections)
- [ChangeLODDistanceFactor](ue_ue.LandscapeStreamingProxy.md#changeloddistancefactor)
- [ChangeTessellationComponentScreenSize](ue_ue.LandscapeStreamingProxy.md#changetessellationcomponentscreensize)
- [ChangeTessellationComponentScreenSizeFalloff](ue_ue.LandscapeStreamingProxy.md#changetessellationcomponentscreensizefalloff)
- [ChangeUseTessellationComponentScreenSizeFalloff](ue_ue.LandscapeStreamingProxy.md#changeusetessellationcomponentscreensizefalloff)
- [CreateDefaultSubobject](ue_ue.LandscapeStreamingProxy.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.LandscapeStreamingProxy.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.LandscapeStreamingProxy.md#disableinput)
- [EditorApplySpline](ue_ue.LandscapeStreamingProxy.md#editorapplyspline)
- [EditorSetLandscapeMaterial](ue_ue.LandscapeStreamingProxy.md#editorsetlandscapematerial)
- [EnableInput](ue_ue.LandscapeStreamingProxy.md#enableinput)
- [ExecuteUbergraph](ue_ue.LandscapeStreamingProxy.md#executeubergraph)
- [FlushNetDormancy](ue_ue.LandscapeStreamingProxy.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.LandscapeStreamingProxy.md#forcenetupdate)
- [GetActorBounds](ue_ue.LandscapeStreamingProxy.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.LandscapeStreamingProxy.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.LandscapeStreamingProxy.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.LandscapeStreamingProxy.md#getactorforwardvector)
- [GetActorLabel](ue_ue.LandscapeStreamingProxy.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.LandscapeStreamingProxy.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.LandscapeStreamingProxy.md#getactorrightvector)
- [GetActorScale3D](ue_ue.LandscapeStreamingProxy.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.LandscapeStreamingProxy.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.LandscapeStreamingProxy.md#getactortimedilation)
- [GetActorUpVector](ue_ue.LandscapeStreamingProxy.md#getactorupvector)
- [GetAllChildActors](ue_ue.LandscapeStreamingProxy.md#getallchildactors)
- [GetAttachParentActor](ue_ue.LandscapeStreamingProxy.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.LandscapeStreamingProxy.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.LandscapeStreamingProxy.md#getattachedactors)
- [GetClass](ue_ue.LandscapeStreamingProxy.md#getclass)
- [GetComponentByClass](ue_ue.LandscapeStreamingProxy.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.LandscapeStreamingProxy.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.LandscapeStreamingProxy.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.LandscapeStreamingProxy.md#getdistanceto)
- [GetDotProductTo](ue_ue.LandscapeStreamingProxy.md#getdotproductto)
- [GetFolderPath](ue_ue.LandscapeStreamingProxy.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.LandscapeStreamingProxy.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.LandscapeStreamingProxy.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.LandscapeStreamingProxy.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.LandscapeStreamingProxy.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.LandscapeStreamingProxy.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.LandscapeStreamingProxy.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.LandscapeStreamingProxy.md#getinstigator)
- [GetInstigatorController](ue_ue.LandscapeStreamingProxy.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.LandscapeStreamingProxy.md#getlifespan)
- [GetLocalRole](ue_ue.LandscapeStreamingProxy.md#getlocalrole)
- [GetName](ue_ue.LandscapeStreamingProxy.md#getname)
- [GetOuter](ue_ue.LandscapeStreamingProxy.md#getouter)
- [GetOverlappingActors](ue_ue.LandscapeStreamingProxy.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.LandscapeStreamingProxy.md#getoverlappingcomponents)
- [GetOwner](ue_ue.LandscapeStreamingProxy.md#getowner)
- [GetParentActor](ue_ue.LandscapeStreamingProxy.md#getparentactor)
- [GetParentComponent](ue_ue.LandscapeStreamingProxy.md#getparentcomponent)
- [GetRemoteRole](ue_ue.LandscapeStreamingProxy.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.LandscapeStreamingProxy.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.LandscapeStreamingProxy.md#gettickablewhenpaused)
- [GetTransform](ue_ue.LandscapeStreamingProxy.md#gettransform)
- [GetVelocity](ue_ue.LandscapeStreamingProxy.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.LandscapeStreamingProxy.md#getverticaldistanceto)
- [GetWorld](ue_ue.LandscapeStreamingProxy.md#getworld)
- [HasAuthority](ue_ue.LandscapeStreamingProxy.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.LandscapeStreamingProxy.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.LandscapeStreamingProxy.md#isactortickenabled)
- [IsChildActor](ue_ue.LandscapeStreamingProxy.md#ischildactor)
- [IsEditable](ue_ue.LandscapeStreamingProxy.md#iseditable)
- [IsHiddenEd](ue_ue.LandscapeStreamingProxy.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.LandscapeStreamingProxy.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.LandscapeStreamingProxy.md#isoverlappingactor)
- [IsSelectable](ue_ue.LandscapeStreamingProxy.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.LandscapeStreamingProxy.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.LandscapeStreamingProxy.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.LandscapeStreamingProxy.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.LandscapeStreamingProxy.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.LandscapeStreamingProxy.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.LandscapeStreamingProxy.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.LandscapeStreamingProxy.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.LandscapeStreamingProxy.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.LandscapeStreamingProxy.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.LandscapeStreamingProxy.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.LandscapeStreamingProxy.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.LandscapeStreamingProxy.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.LandscapeStreamingProxy.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.LandscapeStreamingProxy.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.LandscapeStreamingProxy.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.LandscapeStreamingProxy.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.LandscapeStreamingProxy.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.LandscapeStreamingProxy.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.LandscapeStreamingProxy.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.LandscapeStreamingProxy.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.LandscapeStreamingProxy.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.LandscapeStreamingProxy.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.LandscapeStreamingProxy.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.LandscapeStreamingProxy.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.LandscapeStreamingProxy.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.LandscapeStreamingProxy.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.LandscapeStreamingProxy.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.LandscapeStreamingProxy.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.LandscapeStreamingProxy.md#k2_teleportto)
- [LandscapeExportHeightmapToRenderTarget](ue_ue.LandscapeStreamingProxy.md#landscapeexportheightmaptorendertarget)
- [LandscapeExportWeightmapToRenderTarget](ue_ue.LandscapeStreamingProxy.md#landscapeexportweightmaptorendertarget)
- [LandscapeImportHeightmapFromRenderTarget](ue_ue.LandscapeStreamingProxy.md#landscapeimportheightmapfromrendertarget)
- [LandscapeImportWeightmapFromRenderTarget](ue_ue.LandscapeStreamingProxy.md#landscapeimportweightmapfromrendertarget)
- [MakeMIDForMaterial](ue_ue.LandscapeStreamingProxy.md#makemidformaterial)
- [MakeNoise](ue_ue.LandscapeStreamingProxy.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.LandscapeStreamingProxy.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.LandscapeStreamingProxy.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.LandscapeStreamingProxy.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.LandscapeStreamingProxy.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.LandscapeStreamingProxy.md#onrep_replicatedmovement)
- [PrestreamTextures](ue_ue.LandscapeStreamingProxy.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.LandscapeStreamingProxy.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.LandscapeStreamingProxy.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.LandscapeStreamingProxy.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.LandscapeStreamingProxy.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.LandscapeStreamingProxy.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.LandscapeStreamingProxy.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.LandscapeStreamingProxy.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.LandscapeStreamingProxy.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.LandscapeStreamingProxy.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.LandscapeStreamingProxy.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.LandscapeStreamingProxy.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.LandscapeStreamingProxy.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.LandscapeStreamingProxy.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.LandscapeStreamingProxy.md#receiveendplay)
- [ReceiveHit](ue_ue.LandscapeStreamingProxy.md#receivehit)
- [ReceivePointDamage](ue_ue.LandscapeStreamingProxy.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.LandscapeStreamingProxy.md#receiveradialdamage)
- [ReceiveTick](ue_ue.LandscapeStreamingProxy.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.LandscapeStreamingProxy.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.LandscapeStreamingProxy.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.LandscapeStreamingProxy.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.LandscapeStreamingProxy.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.LandscapeStreamingProxy.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.LandscapeStreamingProxy.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.LandscapeStreamingProxy.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.LandscapeStreamingProxy.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.LandscapeStreamingProxy.md#setactortickinterval)
- [SetFolderPath](ue_ue.LandscapeStreamingProxy.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.LandscapeStreamingProxy.md#setistemporarilyhiddenineditor)
- [SetLandscapeMaterialScalarParameterValue](ue_ue.LandscapeStreamingProxy.md#setlandscapematerialscalarparametervalue)
- [SetLandscapeMaterialTextureParameterValue](ue_ue.LandscapeStreamingProxy.md#setlandscapematerialtextureparametervalue)
- [SetLandscapeMaterialVectorParameterValue](ue_ue.LandscapeStreamingProxy.md#setlandscapematerialvectorparametervalue)
- [SetLifeSpan](ue_ue.LandscapeStreamingProxy.md#setlifespan)
- [SetNetDormancy](ue_ue.LandscapeStreamingProxy.md#setnetdormancy)
- [SetOwner](ue_ue.LandscapeStreamingProxy.md#setowner)
- [SetReplicateMovement](ue_ue.LandscapeStreamingProxy.md#setreplicatemovement)
- [SetReplicates](ue_ue.LandscapeStreamingProxy.md#setreplicates)
- [SetTickGroup](ue_ue.LandscapeStreamingProxy.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.LandscapeStreamingProxy.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.LandscapeStreamingProxy.md#snaprootcomponentto)
- [TearOff](ue_ue.LandscapeStreamingProxy.md#tearoff)
- [UserConstructionScript](ue_ue.LandscapeStreamingProxy.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.LandscapeStreamingProxy.md#wasrecentlyrendered)
- [Find](ue_ue.LandscapeStreamingProxy.md#find)
- [Load](ue_ue.LandscapeStreamingProxy.md#load)
- [StaticClass](ue_ue.LandscapeStreamingProxy.md#staticclass)

## Constructors

### constructor

• **new LandscapeStreamingProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[LandscapeProxy](ue_ue.LandscapeProxy.md).[constructor](ue_ue.LandscapeProxy.md#constructor)

#### Defined in

[ue/ue.d.ts:44409](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44409)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ActorLabel](ue_ue.LandscapeProxy.md#actorlabel)

#### Defined in

[ue/ue.d.ts:13176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13176)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[AttachmentReplication](ue_ue.LandscapeProxy.md#attachmentreplication)

#### Defined in

[ue/ue.d.ts:13151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13151)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[AutoReceiveInput](ue_ue.LandscapeProxy.md#autoreceiveinput)

#### Defined in

[ue/ue.d.ts:13157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13157)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[BlueprintCreatedComponents](ue_ue.LandscapeProxy.md#blueprintcreatedcomponents)

#### Defined in

[ue/ue.d.ts:13206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13206)

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[BodyInstance](ue_ue.LandscapeProxy.md#bodyinstance)

#### Defined in

[ue/ue.d.ts:44110](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44110)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[Children](ue_ue.LandscapeProxy.md#children)

#### Defined in

[ue/ue.d.ts:13166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13166)

___

### CollisionComponents

• **CollisionComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeHeightfieldCollisionComponent`](ue_ue.LandscapeHeightfieldCollisionComponent.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[CollisionComponents](ue_ue.LandscapeProxy.md#collisioncomponents)

#### Defined in

[ue/ue.d.ts:44092](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44092)

___

### CollisionMipLevel

• **CollisionMipLevel**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[CollisionMipLevel](ue_ue.LandscapeProxy.md#collisionmiplevel)

#### Defined in

[ue/ue.d.ts:44107](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44107)

___

### CollisionThickness

• **CollisionThickness**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[CollisionThickness](ue_ue.LandscapeProxy.md#collisionthickness)

#### Defined in

[ue/ue.d.ts:44109](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44109)

___

### ComponentScreenSizeToUseSubSections

• **ComponentScreenSizeToUseSubSections**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ComponentScreenSizeToUseSubSections](ue_ue.LandscapeProxy.md#componentscreensizetousesubsections)

#### Defined in

[ue/ue.d.ts:44064](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44064)

___

### ComponentSizeQuads

• **ComponentSizeQuads**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ComponentSizeQuads](ue_ue.LandscapeProxy.md#componentsizequads)

#### Defined in

[ue/ue.d.ts:44116](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44116)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ControllingMatineeActors](ue_ue.LandscapeProxy.md#controllingmatineeactors)

#### Defined in

[ue/ue.d.ts:13169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13169)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[CustomDepthStencilValue](ue_ue.LandscapeProxy.md#customdepthstencilvalue)

#### Defined in

[ue/ue.d.ts:44103](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44103)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[CustomTimeDilation](ue_ue.LandscapeProxy.md#customtimedilation)

#### Defined in

[ue/ue.d.ts:13150](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13150)

___

### DefaultPhysMaterial

• **DefaultPhysMaterial**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[DefaultPhysMaterial](ue_ue.LandscapeProxy.md#defaultphysmaterial)

#### Defined in

[ue/ue.d.ts:44076](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44076)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.LandscapeProxy.md#defaultupdateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13146](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13146)

___

### EditorCachedLayerInfos

• **EditorCachedLayerInfos**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeLayerInfoObject`](ue_ue.LandscapeLayerInfoObject.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[EditorCachedLayerInfos](ue_ue.LandscapeProxy.md#editorcachedlayerinfos)

#### Defined in

[ue/ue.d.ts:44113](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44113)

___

### EditorLayerSettings

• **EditorLayerSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeEditorLayerSettings`](ue_ue.LandscapeEditorLayerSettings.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[EditorLayerSettings](ue_ue.LandscapeProxy.md#editorlayersettings)

#### Defined in

[ue/ue.d.ts:44115](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44115)

___

### ExportLOD

• **ExportLOD**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ExportLOD](ue_ue.LandscapeProxy.md#exportlod)

#### Defined in

[ue/ue.d.ts:44072](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44072)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[FolderPath](ue_ue.LandscapeProxy.md#folderpath)

#### Defined in

[ue/ue.d.ts:13177](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13177)

___

### FoliageComponents

• **FoliageComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`HierarchicalInstancedStaticMeshComponent`](ue_ue.HierarchicalInstancedStaticMeshComponent.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[FoliageComponents](ue_ue.LandscapeProxy.md#foliagecomponents)

#### Defined in

[ue/ue.d.ts:44093](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44093)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GroupActor](ue_ue.LandscapeProxy.md#groupactor)

#### Defined in

[ue/ue.d.ts:13173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13173)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[HiddenEditorViews](ue_ue.LandscapeProxy.md#hiddeneditorviews)

#### Defined in

[ue/ue.d.ts:13175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13175)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[InitialLifeSpan](ue_ue.LandscapeProxy.md#initiallifespan)

#### Defined in

[ue/ue.d.ts:13149](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13149)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[InputComponent](ue_ue.LandscapeProxy.md#inputcomponent)

#### Defined in

[ue/ue.d.ts:13159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13159)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[InputPriority](ue_ue.LandscapeProxy.md#inputpriority)

#### Defined in

[ue/ue.d.ts:13158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13158)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[InstanceComponents](ue_ue.LandscapeProxy.md#instancecomponents)

#### Defined in

[ue/ue.d.ts:13205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13205)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[Instigator](ue_ue.LandscapeProxy.md#instigator)

#### Defined in

[ue/ue.d.ts:13165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13165)

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LDMaxDrawDistance](ue_ue.LandscapeProxy.md#ldmaxdrawdistance)

#### Defined in

[ue/ue.d.ts:44104](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44104)

___

### LOD0DistributionSetting

• **LOD0DistributionSetting**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LOD0DistributionSetting](ue_ue.LandscapeProxy.md#lod0distributionsetting)

#### Defined in

[ue/ue.d.ts:44066](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44066)

___

### LOD0ScreenSize

• **LOD0ScreenSize**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LOD0ScreenSize](ue_ue.LandscapeProxy.md#lod0screensize)

#### Defined in

[ue/ue.d.ts:44065](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44065)

___

### LODDistanceFactor

• **LODDistanceFactor**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LODDistanceFactor](ue_ue.LandscapeProxy.md#loddistancefactor)

#### Defined in

[ue/ue.d.ts:44062](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44062)

___

### LODDistributionSetting

• **LODDistributionSetting**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LODDistributionSetting](ue_ue.LandscapeProxy.md#loddistributionsetting)

#### Defined in

[ue/ue.d.ts:44067](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44067)

___

### LODFalloff

• **LODFalloff**: [`ELandscapeLODFalloff`](../enums/ue_ue.ELandscapeLODFalloff.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LODFalloff](ue_ue.LandscapeProxy.md#lodfalloff)

#### Defined in

[ue/ue.d.ts:44063](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44063)

___

### LandscapeActor

• **LandscapeActor**: [`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`Landscape`](ue_ue.Landscape.md)\>

#### Defined in

[ue/ue.d.ts:44410](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44410)

___

### LandscapeComponents

• **LandscapeComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeComponent`](ue_ue.LandscapeComponent.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LandscapeComponents](ue_ue.LandscapeProxy.md#landscapecomponents)

#### Defined in

[ue/ue.d.ts:44091](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44091)

___

### LandscapeGuid

• **LandscapeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LandscapeGuid](ue_ue.LandscapeProxy.md#landscapeguid)

#### Defined in

[ue/ue.d.ts:44059](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44059)

___

### LandscapeHoleMaterial

• **LandscapeHoleMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LandscapeHoleMaterial](ue_ue.LandscapeProxy.md#landscapeholematerial)

#### Defined in

[ue/ue.d.ts:44079](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44079)

___

### LandscapeMaterial

• **LandscapeMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LandscapeMaterial](ue_ue.LandscapeProxy.md#landscapematerial)

#### Defined in

[ue/ue.d.ts:44078](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44078)

___

### LandscapeMaterialsOverride

• **LandscapeMaterialsOverride**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeProxyMaterialOverride`](ue_ue.LandscapeProxyMaterialOverride.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LandscapeMaterialsOverride](ue_ue.LandscapeProxy.md#landscapematerialsoverride)

#### Defined in

[ue/ue.d.ts:44080](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44080)

___

### LandscapeSectionOffset

• **LandscapeSectionOffset**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LandscapeSectionOffset](ue_ue.LandscapeProxy.md#landscapesectionoffset)

#### Defined in

[ue/ue.d.ts:44060](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44060)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[Layers](ue_ue.LandscapeProxy.md#layers)

#### Defined in

[ue/ue.d.ts:13170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13170)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LightingChannels](ue_ue.LandscapeProxy.md#lightingchannels)

#### Defined in

[ue/ue.d.ts:44100](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44100)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassPrimitiveSettings`](ue_ue.LightmassPrimitiveSettings.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LightmassSettings](ue_ue.LandscapeProxy.md#lightmasssettings)

#### Defined in

[ue/ue.d.ts:44106](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44106)

___

### MaxLODLevel

• **MaxLODLevel**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[MaxLODLevel](ue_ue.LandscapeProxy.md#maxlodlevel)

#### Defined in

[ue/ue.d.ts:44061](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44061)

___

### MaxPaintedLayersPerComponent

• **MaxPaintedLayersPerComponent**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[MaxPaintedLayersPerComponent](ue_ue.LandscapeProxy.md#maxpaintedlayerspercomponent)

#### Defined in

[ue/ue.d.ts:44122](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44122)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[MinNetUpdateFrequency](ue_ue.LandscapeProxy.md#minnetupdatefrequency)

#### Defined in

[ue/ue.d.ts:13163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13163)

___

### NavigationGeometryGatheringMode

• **NavigationGeometryGatheringMode**: [`ENavDataGatheringMode`](../enums/ue_ue.ENavDataGatheringMode.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[NavigationGeometryGatheringMode](ue_ue.LandscapeProxy.md#navigationgeometrygatheringmode)

#### Defined in

[ue/ue.d.ts:44121](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44121)

___

### NegativeZBoundsExtension

• **NegativeZBoundsExtension**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[NegativeZBoundsExtension](ue_ue.LandscapeProxy.md#negativezboundsextension)

#### Defined in

[ue/ue.d.ts:44089](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44089)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[NetCullDistanceSquared](ue_ue.LandscapeProxy.md#netculldistancesquared)

#### Defined in

[ue/ue.d.ts:13160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13160)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[NetDormancy](ue_ue.LandscapeProxy.md#netdormancy)

#### Defined in

[ue/ue.d.ts:13155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13155)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[NetDriverName](ue_ue.LandscapeProxy.md#netdrivername)

#### Defined in

[ue/ue.d.ts:13153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13153)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[NetPriority](ue_ue.LandscapeProxy.md#netpriority)

#### Defined in

[ue/ue.d.ts:13164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13164)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[NetTag](ue_ue.LandscapeProxy.md#nettag)

#### Defined in

[ue/ue.d.ts:13161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13161)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[NetUpdateFrequency](ue_ue.LandscapeProxy.md#netupdatefrequency)

#### Defined in

[ue/ue.d.ts:13162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13162)

___

### NumSubsections

• **NumSubsections**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[NumSubsections](ue_ue.LandscapeProxy.md#numsubsections)

#### Defined in

[ue/ue.d.ts:44118](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44118)

___

### OccluderGeometryLOD

• **OccluderGeometryLOD**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OccluderGeometryLOD](ue_ue.LandscapeProxy.md#occludergeometrylod)

#### Defined in

[ue/ue.d.ts:44071](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44071)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnActorBeginOverlap](ue_ue.LandscapeProxy.md#onactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13192)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnActorEndOverlap](ue_ue.LandscapeProxy.md#onactorendoverlap)

#### Defined in

[ue/ue.d.ts:13193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13193)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnActorHit](ue_ue.LandscapeProxy.md#onactorhit)

#### Defined in

[ue/ue.d.ts:13202](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13202)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnBeginCursorOver](ue_ue.LandscapeProxy.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:13194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13194)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnClicked](ue_ue.LandscapeProxy.md#onclicked)

#### Defined in

[ue/ue.d.ts:13196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13196)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnDestroyed](ue_ue.LandscapeProxy.md#ondestroyed)

#### Defined in

[ue/ue.d.ts:13203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13203)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnEndCursorOver](ue_ue.LandscapeProxy.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:13195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13195)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnEndPlay](ue_ue.LandscapeProxy.md#onendplay)

#### Defined in

[ue/ue.d.ts:13204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13204)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnInputTouchBegin](ue_ue.LandscapeProxy.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13198)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnInputTouchEnd](ue_ue.LandscapeProxy.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:13199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13199)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnInputTouchEnter](ue_ue.LandscapeProxy.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:13200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13200)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnInputTouchLeave](ue_ue.LandscapeProxy.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:13201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13201)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnReleased](ue_ue.LandscapeProxy.md#onreleased)

#### Defined in

[ue/ue.d.ts:13197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13197)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnTakeAnyDamage](ue_ue.LandscapeProxy.md#ontakeanydamage)

#### Defined in

[ue/ue.d.ts:13189](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13189)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnTakePointDamage](ue_ue.LandscapeProxy.md#ontakepointdamage)

#### Defined in

[ue/ue.d.ts:13190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13190)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnTakeRadialDamage](ue_ue.LandscapeProxy.md#ontakeradialdamage)

#### Defined in

[ue/ue.d.ts:13191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13191)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[Owner](ue_ue.LandscapeProxy.md#owner)

#### Defined in

[ue/ue.d.ts:13152](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13152)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ParentComponent](ue_ue.LandscapeProxy.md#parentcomponent)

#### Defined in

[ue/ue.d.ts:13172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13172)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ParentComponentActor](ue_ue.LandscapeProxy.md#parentcomponentactor)

#### Defined in

[ue/ue.d.ts:13171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13171)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[PivotOffset](ue_ue.LandscapeProxy.md#pivotoffset)

#### Defined in

[ue/ue.d.ts:13168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13168)

___

### PositiveZBoundsExtension

• **PositiveZBoundsExtension**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[PositiveZBoundsExtension](ue_ue.LandscapeProxy.md#positivezboundsextension)

#### Defined in

[ue/ue.d.ts:44090](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44090)

___

### PreEditLandscapeHoleMaterial

• **PreEditLandscapeHoleMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[PreEditLandscapeHoleMaterial](ue_ue.LandscapeProxy.md#preeditlandscapeholematerial)

#### Defined in

[ue/ue.d.ts:44082](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44082)

___

### PreEditLandscapeMaterial

• **PreEditLandscapeMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[PreEditLandscapeMaterial](ue_ue.LandscapeProxy.md#preeditlandscapematerial)

#### Defined in

[ue/ue.d.ts:44081](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44081)

___

### PreEditLandscapeMaterialsOverride

• **PreEditLandscapeMaterialsOverride**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeProxyMaterialOverride`](ue_ue.LandscapeProxyMaterialOverride.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[PreEditLandscapeMaterialsOverride](ue_ue.LandscapeProxy.md#preeditlandscapematerialsoverride)

#### Defined in

[ue/ue.d.ts:44083](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44083)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[PrimaryActorTick](ue_ue.LandscapeProxy.md#primaryactortick)

#### Defined in

[ue/ue.d.ts:13115](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13115)

___

### ReimportHeightmapFilePath

• **ReimportHeightmapFilePath**: `string`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReimportHeightmapFilePath](ue_ue.LandscapeProxy.md#reimportheightmapfilepath)

#### Defined in

[ue/ue.d.ts:44114](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44114)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[RemoteRole](ue_ue.LandscapeProxy.md#remoterole)

#### Defined in

[ue/ue.d.ts:13147](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13147)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReplicatedMovement](ue_ue.LandscapeProxy.md#replicatedmovement)

#### Defined in

[ue/ue.d.ts:13148](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13148)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[Role](ue_ue.LandscapeProxy.md#role)

#### Defined in

[ue/ue.d.ts:13154](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13154)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[RootComponent](ue_ue.LandscapeProxy.md#rootcomponent)

#### Defined in

[ue/ue.d.ts:13167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13167)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[RuntimeVirtualTextures](ue_ue.LandscapeProxy.md#runtimevirtualtextures)

#### Defined in

[ue/ue.d.ts:44085](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44085)

___

### SimpleCollisionMipLevel

• **SimpleCollisionMipLevel**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SimpleCollisionMipLevel](ue_ue.LandscapeProxy.md#simplecollisionmiplevel)

#### Defined in

[ue/ue.d.ts:44108](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44108)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SpawnCollisionHandlingMethod](ue_ue.LandscapeProxy.md#spawncollisionhandlingmethod)

#### Defined in

[ue/ue.d.ts:13156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13156)

___

### SplineComponent

• **SplineComponent**: [`LandscapeSplinesComponent`](ue_ue.LandscapeSplinesComponent.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SplineComponent](ue_ue.LandscapeProxy.md#splinecomponent)

#### Defined in

[ue/ue.d.ts:44058](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44058)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SpriteScale](ue_ue.LandscapeProxy.md#spritescale)

#### Defined in

[ue/ue.d.ts:13174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13174)

___

### StaticLightingLOD

• **StaticLightingLOD**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[StaticLightingLOD](ue_ue.LandscapeProxy.md#staticlightinglod)

#### Defined in

[ue/ue.d.ts:44075](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44075)

___

### StaticLightingResolution

• **StaticLightingResolution**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[StaticLightingResolution](ue_ue.LandscapeProxy.md#staticlightingresolution)

#### Defined in

[ue/ue.d.ts:44095](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44095)

___

### StreamingDistanceMultiplier

• **StreamingDistanceMultiplier**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[StreamingDistanceMultiplier](ue_ue.LandscapeProxy.md#streamingdistancemultiplier)

#### Defined in

[ue/ue.d.ts:44077](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44077)

___

### SubsectionSizeQuads

• **SubsectionSizeQuads**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SubsectionSizeQuads](ue_ue.LandscapeProxy.md#subsectionsizequads)

#### Defined in

[ue/ue.d.ts:44117](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44117)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[Tags](ue_ue.LandscapeProxy.md#tags)

#### Defined in

[ue/ue.d.ts:13188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13188)

___

### TargetDisplayOrder

• **TargetDisplayOrder**: [`ELandscapeLayerDisplayMode`](../enums/ue_ue.ELandscapeLayerDisplayMode.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[TargetDisplayOrder](ue_ue.LandscapeProxy.md#targetdisplayorder)

#### Defined in

[ue/ue.d.ts:44074](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44074)

___

### TargetDisplayOrderList

• **TargetDisplayOrderList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[TargetDisplayOrderList](ue_ue.LandscapeProxy.md#targetdisplayorderlist)

#### Defined in

[ue/ue.d.ts:44073](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44073)

___

### TessellationComponentScreenSize

• **TessellationComponentScreenSize**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[TessellationComponentScreenSize](ue_ue.LandscapeProxy.md#tessellationcomponentscreensize)

#### Defined in

[ue/ue.d.ts:44068](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44068)

___

### TessellationComponentScreenSizeFalloff

• **TessellationComponentScreenSizeFalloff**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[TessellationComponentScreenSizeFalloff](ue_ue.LandscapeProxy.md#tessellationcomponentscreensizefalloff)

#### Defined in

[ue/ue.d.ts:44070](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44070)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.LandscapeProxy.md#updateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13145](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13145)

___

### UseTessellationComponentScreenSizeFalloff

• **UseTessellationComponentScreenSizeFalloff**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[UseTessellationComponentScreenSizeFalloff](ue_ue.LandscapeProxy.md#usetessellationcomponentscreensizefalloff)

#### Defined in

[ue/ue.d.ts:44069](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44069)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[VirtualTextureLodBias](ue_ue.LandscapeProxy.md#virtualtexturelodbias)

#### Defined in

[ue/ue.d.ts:44087](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44087)

___

### VirtualTextureNumLods

• **VirtualTextureNumLods**: `number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[VirtualTextureNumLods](ue_ue.LandscapeProxy.md#virtualtexturenumlods)

#### Defined in

[ue/ue.d.ts:44086](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44086)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[VirtualTextureRenderPassType](ue_ue.LandscapeProxy.md#virtualtexturerenderpasstype)

#### Defined in

[ue/ue.d.ts:44088](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44088)

___

### WeightmapUsageMap

• **WeightmapUsageMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Texture2D`](ue_ue.Texture2D.md), [`LandscapeWeightmapUsage`](ue_ue.LandscapeWeightmapUsage.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[WeightmapUsageMap](ue_ue.LandscapeProxy.md#weightmapusagemap)

#### Defined in

[ue/ue.d.ts:44125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44125)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[__tid_Actor__](ue_ue.LandscapeProxy.md#__tid_actor__)

#### Defined in

[ue/ue.d.ts:13348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13348)

___

### \_\_tid\_LandscapeProxy\_\_

• **\_\_tid\_LandscapeProxy\_\_**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[__tid_LandscapeProxy__](ue_ue.LandscapeProxy.md#__tid_landscapeproxy__)

#### Defined in

[ue/ue.d.ts:44144](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44144)

___

### \_\_tid\_LandscapeStreamingProxy\_\_

• **\_\_tid\_LandscapeStreamingProxy\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:44415](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44415)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[__tid_Object__](ue_ue.LandscapeProxy.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bActorEnableCollision](ue_ue.LandscapeProxy.md#bactorenablecollision)

#### Defined in

[ue/ue.d.ts:13143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13143)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bActorIsBeingDestroyed](ue_ue.LandscapeProxy.md#bactorisbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13144](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13144)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bActorLabelEditable](ue_ue.LandscapeProxy.md#bactorlabeleditable)

#### Defined in

[ue/ue.d.ts:13183](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13183)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bActorSeamlessTraveled](ue_ue.LandscapeProxy.md#bactorseamlesstraveled)

#### Defined in

[ue/ue.d.ts:13139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13139)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bAffectDistanceFieldLighting](ue_ue.LandscapeProxy.md#baffectdistancefieldlighting)

#### Defined in

[ue/ue.d.ts:44099](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44099)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.LandscapeProxy.md#ballowreceivetickeventondedicatedserver)

#### Defined in

[ue/ue.d.ts:13142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13142)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bAllowTickBeforeBeginPlay](ue_ue.LandscapeProxy.md#ballowtickbeforebeginplay)

#### Defined in

[ue/ue.d.ts:13129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13129)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bAlwaysRelevant](ue_ue.LandscapeProxy.md#balwaysrelevant)

#### Defined in

[ue/ue.d.ts:13120](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13120)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bAutoDestroyWhenFinished](ue_ue.LandscapeProxy.md#bautodestroywhenfinished)

#### Defined in

[ue/ue.d.ts:13130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13130)

___

### bBakeMaterialPositionOffsetIntoCollision

• **bBakeMaterialPositionOffsetIntoCollision**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bBakeMaterialPositionOffsetIntoCollision](ue_ue.LandscapeProxy.md#bbakematerialpositionoffsetintocollision)

#### Defined in

[ue/ue.d.ts:44112](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44112)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bBlockInput](ue_ue.LandscapeProxy.md#bblockinput)

#### Defined in

[ue/ue.d.ts:13131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13131)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bCanBeDamaged](ue_ue.LandscapeProxy.md#bcanbedamaged)

#### Defined in

[ue/ue.d.ts:13132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13132)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bCanBeInCluster](ue_ue.LandscapeProxy.md#bcanbeincluster)

#### Defined in

[ue/ue.d.ts:13141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13141)

___

### bCastFarShadow

• **bCastFarShadow**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bCastFarShadow](ue_ue.LandscapeProxy.md#bcastfarshadow)

#### Defined in

[ue/ue.d.ts:44098](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44098)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bCastShadowAsTwoSided](ue_ue.LandscapeProxy.md#bcastshadowastwosided)

#### Defined in

[ue/ue.d.ts:44097](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44097)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bCastStaticShadow](ue_ue.LandscapeProxy.md#bcaststaticshadow)

#### Defined in

[ue/ue.d.ts:44096](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44096)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bCollideWhenPlacing](ue_ue.LandscapeProxy.md#bcollidewhenplacing)

#### Defined in

[ue/ue.d.ts:13133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13133)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bEditable](ue_ue.LandscapeProxy.md#beditable)

#### Defined in

[ue/ue.d.ts:13184](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13184)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bEnableAutoLODGeneration](ue_ue.LandscapeProxy.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:13137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13137)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bExchangedRoles](ue_ue.LandscapeProxy.md#bexchangedroles)

#### Defined in

[ue/ue.d.ts:13123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13123)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bFindCameraComponentWhenViewTarget](ue_ue.LandscapeProxy.md#bfindcameracomponentwhenviewtarget)

#### Defined in

[ue/ue.d.ts:13134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13134)

___

### bGenerateOverlapEvents

• **bGenerateOverlapEvents**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bGenerateOverlapEvents](ue_ue.LandscapeProxy.md#bgenerateoverlapevents)

#### Defined in

[ue/ue.d.ts:44111](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44111)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.LandscapeProxy.md#bgenerateoverlapeventsduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13135)

___

### bHasLandscapeGrass

• **bHasLandscapeGrass**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bHasLandscapeGrass](ue_ue.LandscapeProxy.md#bhaslandscapegrass)

#### Defined in

[ue/ue.d.ts:44094](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44094)

___

### bHasLayersContent

• **bHasLayersContent**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bHasLayersContent](ue_ue.LandscapeProxy.md#bhaslayerscontent)

#### Defined in

[ue/ue.d.ts:44124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44124)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bHidden](ue_ue.LandscapeProxy.md#bhidden)

#### Defined in

[ue/ue.d.ts:13116](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13116)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bHiddenEd](ue_ue.LandscapeProxy.md#bhiddened)

#### Defined in

[ue/ue.d.ts:13178](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13178)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bHiddenEdLayer](ue_ue.LandscapeProxy.md#bhiddenedlayer)

#### Defined in

[ue/ue.d.ts:13180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13180)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bHiddenEdLevel](ue_ue.LandscapeProxy.md#bhiddenedlevel)

#### Defined in

[ue/ue.d.ts:13181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13181)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bHiddenEdTemporary](ue_ue.LandscapeProxy.md#bhiddenedtemporary)

#### Defined in

[ue/ue.d.ts:13187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13187)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bIgnoresOriginShifting](ue_ue.LandscapeProxy.md#bignoresoriginshifting)

#### Defined in

[ue/ue.d.ts:13136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13136)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bIsEditorOnlyActor](ue_ue.LandscapeProxy.md#biseditoronlyactor)

#### Defined in

[ue/ue.d.ts:13138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13138)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bIsEditorPreviewActor](ue_ue.LandscapeProxy.md#biseditorpreviewactor)

#### Defined in

[ue/ue.d.ts:13179](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13179)

___

### bIsMovingToLevel

• **bIsMovingToLevel**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bIsMovingToLevel](ue_ue.LandscapeProxy.md#bismovingtolevel)

#### Defined in

[ue/ue.d.ts:44105](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44105)

___

### bIsPerformingInteractiveActionOnLandscapeMaterialOverride

• **bIsPerformingInteractiveActionOnLandscapeMaterialOverride**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bIsPerformingInteractiveActionOnLandscapeMaterialOverride](ue_ue.LandscapeProxy.md#bisperforminginteractiveactiononlandscapematerialoverride)

#### Defined in

[ue/ue.d.ts:44084](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44084)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bListedInSceneOutliner](ue_ue.LandscapeProxy.md#blistedinsceneoutliner)

#### Defined in

[ue/ue.d.ts:13185](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13185)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bLockLocation](ue_ue.LandscapeProxy.md#blocklocation)

#### Defined in

[ue/ue.d.ts:13182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13182)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bNetLoadOnClient](ue_ue.LandscapeProxy.md#bnetloadonclient)

#### Defined in

[ue/ue.d.ts:13124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13124)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bNetStartup](ue_ue.LandscapeProxy.md#bnetstartup)

#### Defined in

[ue/ue.d.ts:13118](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13118)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bNetTemporary](ue_ue.LandscapeProxy.md#bnettemporary)

#### Defined in

[ue/ue.d.ts:13117](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13117)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bNetUseOwnerRelevancy](ue_ue.LandscapeProxy.md#bnetuseownerrelevancy)

#### Defined in

[ue/ue.d.ts:13125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13125)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bOnlyRelevantToOwner](ue_ue.LandscapeProxy.md#bonlyrelevanttoowner)

#### Defined in

[ue/ue.d.ts:13119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13119)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bOptimizeBPComponentData](ue_ue.LandscapeProxy.md#boptimizebpcomponentdata)

#### Defined in

[ue/ue.d.ts:13186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13186)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bRelevantForLevelBounds](ue_ue.LandscapeProxy.md#brelevantforlevelbounds)

#### Defined in

[ue/ue.d.ts:13127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13127)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bRelevantForNetworkReplays](ue_ue.LandscapeProxy.md#brelevantfornetworkreplays)

#### Defined in

[ue/ue.d.ts:13126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13126)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bRenderCustomDepth](ue_ue.LandscapeProxy.md#brendercustomdepth)

#### Defined in

[ue/ue.d.ts:44102](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44102)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bReplayRewindable](ue_ue.LandscapeProxy.md#breplayrewindable)

#### Defined in

[ue/ue.d.ts:13128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13128)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bReplicateMovement](ue_ue.LandscapeProxy.md#breplicatemovement)

#### Defined in

[ue/ue.d.ts:13121](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13121)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bReplicates](ue_ue.LandscapeProxy.md#breplicates)

#### Defined in

[ue/ue.d.ts:13140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13140)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bTearOff](ue_ue.LandscapeProxy.md#btearoff)

#### Defined in

[ue/ue.d.ts:13122](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13122)

___

### bUseDynamicMaterialInstance

• **bUseDynamicMaterialInstance**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bUseDynamicMaterialInstance](ue_ue.LandscapeProxy.md#busedynamicmaterialinstance)

#### Defined in

[ue/ue.d.ts:44120](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44120)

___

### bUseLandscapeForCullingInvisibleHLODVertices

• **bUseLandscapeForCullingInvisibleHLODVertices**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bUseLandscapeForCullingInvisibleHLODVertices](ue_ue.LandscapeProxy.md#buselandscapeforcullinginvisiblehlodvertices)

#### Defined in

[ue/ue.d.ts:44123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44123)

___

### bUseMaterialPositionOffsetInStaticLighting

• **bUseMaterialPositionOffsetInStaticLighting**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bUseMaterialPositionOffsetInStaticLighting](ue_ue.LandscapeProxy.md#busematerialpositionoffsetinstaticlighting)

#### Defined in

[ue/ue.d.ts:44101](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44101)

___

### bUsedForNavigation

• **bUsedForNavigation**: `boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[bUsedForNavigation](ue_ue.LandscapeProxy.md#busedfornavigation)

#### Defined in

[ue/ue.d.ts:44119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44119)

## Methods

### ActorHasTag

▸ **ActorHasTag**(`Tag`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tag` | `string` |

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ActorHasTag](ue_ue.LandscapeProxy.md#actorhastag)

#### Defined in

[ue/ue.d.ts:13207](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13207)

___

### AddComponent

▸ **AddComponent**(`TemplateName`, `bManualAttachment`, `RelativeTransform`, `ComponentTemplateContext`): [`ActorComponent`](ue_ue.ActorComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TemplateName` | `string` |
| `bManualAttachment` | `boolean` |
| `RelativeTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `ComponentTemplateContext` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`ActorComponent`](ue_ue.ActorComponent.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[AddComponent](ue_ue.LandscapeProxy.md#addcomponent)

#### Defined in

[ue/ue.d.ts:13208](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13208)

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[AddTickPrerequisiteActor](ue_ue.LandscapeProxy.md#addtickprerequisiteactor)

#### Defined in

[ue/ue.d.ts:13209](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13209)

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[AddTickPrerequisiteComponent](ue_ue.LandscapeProxy.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13210](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13210)

___

### ChangeComponentScreenSizeToUseSubSections

▸ **ChangeComponentScreenSizeToUseSubSections**(`InComponentScreenSizeToUseSubSections`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InComponentScreenSizeToUseSubSections` | `number` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ChangeComponentScreenSizeToUseSubSections](ue_ue.LandscapeProxy.md#changecomponentscreensizetousesubsections)

#### Defined in

[ue/ue.d.ts:44126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44126)

___

### ChangeLODDistanceFactor

▸ **ChangeLODDistanceFactor**(`InLODDistanceFactor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLODDistanceFactor` | `number` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ChangeLODDistanceFactor](ue_ue.LandscapeProxy.md#changeloddistancefactor)

#### Defined in

[ue/ue.d.ts:44127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44127)

___

### ChangeTessellationComponentScreenSize

▸ **ChangeTessellationComponentScreenSize**(`InTessellationComponentScreenSize`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTessellationComponentScreenSize` | `number` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ChangeTessellationComponentScreenSize](ue_ue.LandscapeProxy.md#changetessellationcomponentscreensize)

#### Defined in

[ue/ue.d.ts:44128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44128)

___

### ChangeTessellationComponentScreenSizeFalloff

▸ **ChangeTessellationComponentScreenSizeFalloff**(`InUseTessellationComponentScreenSizeFalloff`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InUseTessellationComponentScreenSizeFalloff` | `number` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ChangeTessellationComponentScreenSizeFalloff](ue_ue.LandscapeProxy.md#changetessellationcomponentscreensizefalloff)

#### Defined in

[ue/ue.d.ts:44129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44129)

___

### ChangeUseTessellationComponentScreenSizeFalloff

▸ **ChangeUseTessellationComponentScreenSizeFalloff**(`InComponentScreenSizeToUseSubSections`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InComponentScreenSizeToUseSubSections` | `boolean` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ChangeUseTessellationComponentScreenSizeFalloff](ue_ue.LandscapeProxy.md#changeusetessellationcomponentscreensizefalloff)

#### Defined in

[ue/ue.d.ts:44130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44130)

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[CreateDefaultSubobject](ue_ue.LandscapeProxy.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### DetachRootComponentFromParent

▸ **DetachRootComponentFromParent**(`bMaintainWorldPosition?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bMaintainWorldPosition?` | `boolean` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[DetachRootComponentFromParent](ue_ue.LandscapeProxy.md#detachrootcomponentfromparent)

#### Defined in

[ue/ue.d.ts:13211](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13211)

___

### DisableInput

▸ **DisableInput**(`PlayerController`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[DisableInput](ue_ue.LandscapeProxy.md#disableinput)

#### Defined in

[ue/ue.d.ts:13212](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13212)

___

### EditorApplySpline

▸ **EditorApplySpline**(`InSplineComponent`, `StartWidth?`, `EndWidth?`, `StartSideFalloff?`, `EndSideFalloff?`, `StartRoll?`, `EndRoll?`, `NumSubdivisions?`, `bRaiseHeights?`, `bLowerHeights?`, `PaintLayer?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSplineComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SplineComponent`](ue_ue.SplineComponent.md)\> |
| `StartWidth?` | `number` |
| `EndWidth?` | `number` |
| `StartSideFalloff?` | `number` |
| `EndSideFalloff?` | `number` |
| `StartRoll?` | `number` |
| `EndRoll?` | `number` |
| `NumSubdivisions?` | `number` |
| `bRaiseHeights?` | `boolean` |
| `bLowerHeights?` | `boolean` |
| `PaintLayer?` | [`LandscapeLayerInfoObject`](ue_ue.LandscapeLayerInfoObject.md) |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[EditorApplySpline](ue_ue.LandscapeProxy.md#editorapplyspline)

#### Defined in

[ue/ue.d.ts:44131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44131)

___

### EditorSetLandscapeMaterial

▸ **EditorSetLandscapeMaterial**(`NewLandscapeMaterial`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLandscapeMaterial` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[EditorSetLandscapeMaterial](ue_ue.LandscapeProxy.md#editorsetlandscapematerial)

#### Defined in

[ue/ue.d.ts:44132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44132)

___

### EnableInput

▸ **EnableInput**(`PlayerController`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[EnableInput](ue_ue.LandscapeProxy.md#enableinput)

#### Defined in

[ue/ue.d.ts:13213](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13213)

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ExecuteUbergraph](ue_ue.LandscapeProxy.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[FlushNetDormancy](ue_ue.LandscapeProxy.md#flushnetdormancy)

#### Defined in

[ue/ue.d.ts:13214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13214)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ForceNetUpdate](ue_ue.LandscapeProxy.md#forcenetupdate)

#### Defined in

[ue/ue.d.ts:13215](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13215)

___

### GetActorBounds

▸ **GetActorBounds**(`bOnlyCollidingComponents`, `Origin`, `BoxExtent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bOnlyCollidingComponents` | `boolean` |
| `Origin` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `BoxExtent` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetActorBounds](ue_ue.LandscapeProxy.md#getactorbounds)

#### Defined in

[ue/ue.d.ts:13216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13216)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetActorEnableCollision](ue_ue.LandscapeProxy.md#getactorenablecollision)

#### Defined in

[ue/ue.d.ts:13217](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13217)

___

### GetActorEyesViewPoint

▸ **GetActorEyesViewPoint**(`OutLocation`, `OutRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `OutRotation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetActorEyesViewPoint](ue_ue.LandscapeProxy.md#getactoreyesviewpoint)

#### Defined in

[ue/ue.d.ts:13218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13218)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetActorForwardVector](ue_ue.LandscapeProxy.md#getactorforwardvector)

#### Defined in

[ue/ue.d.ts:13219](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13219)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetActorLabel](ue_ue.LandscapeProxy.md#getactorlabel)

#### Defined in

[ue/ue.d.ts:13220](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13220)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetActorRelativeScale3D](ue_ue.LandscapeProxy.md#getactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13221](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13221)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetActorRightVector](ue_ue.LandscapeProxy.md#getactorrightvector)

#### Defined in

[ue/ue.d.ts:13222](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13222)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetActorScale3D](ue_ue.LandscapeProxy.md#getactorscale3d)

#### Defined in

[ue/ue.d.ts:13223](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13223)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetActorTickInterval](ue_ue.LandscapeProxy.md#getactortickinterval)

#### Defined in

[ue/ue.d.ts:13224](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13224)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetActorTimeDilation](ue_ue.LandscapeProxy.md#getactortimedilation)

#### Defined in

[ue/ue.d.ts:13225](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13225)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetActorUpVector](ue_ue.LandscapeProxy.md#getactorupvector)

#### Defined in

[ue/ue.d.ts:13226](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13226)

___

### GetAllChildActors

▸ **GetAllChildActors**(`ChildActors`, `bIncludeDescendants?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ChildActors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |
| `bIncludeDescendants?` | `boolean` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetAllChildActors](ue_ue.LandscapeProxy.md#getallchildactors)

#### Defined in

[ue/ue.d.ts:13227](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13227)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetAttachParentActor](ue_ue.LandscapeProxy.md#getattachparentactor)

#### Defined in

[ue/ue.d.ts:13229](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13229)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetAttachParentSocketName](ue_ue.LandscapeProxy.md#getattachparentsocketname)

#### Defined in

[ue/ue.d.ts:13230](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13230)

___

### GetAttachedActors

▸ **GetAttachedActors**(`OutActors`, `bResetArray?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutActors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |
| `bResetArray?` | `boolean` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetAttachedActors](ue_ue.LandscapeProxy.md#getattachedactors)

#### Defined in

[ue/ue.d.ts:13228](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13228)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetClass](ue_ue.LandscapeProxy.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetComponentByClass

▸ **GetComponentByClass**(`ComponentClass`): [`ActorComponent`](ue_ue.ActorComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ComponentClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`ActorComponent`](ue_ue.ActorComponent.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetComponentByClass](ue_ue.LandscapeProxy.md#getcomponentbyclass)

#### Defined in

[ue/ue.d.ts:13231](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13231)

___

### GetComponentsByInterface

▸ **GetComponentsByInterface**(`Interface`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Interface` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetComponentsByInterface](ue_ue.LandscapeProxy.md#getcomponentsbyinterface)

#### Defined in

[ue/ue.d.ts:13232](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13232)

___

### GetComponentsByTag

▸ **GetComponentsByTag**(`ComponentClass`, `Tag`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ComponentClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `Tag` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetComponentsByTag](ue_ue.LandscapeProxy.md#getcomponentsbytag)

#### Defined in

[ue/ue.d.ts:13233](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13233)

___

### GetDistanceTo

▸ **GetDistanceTo**(`OtherActor`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetDistanceTo](ue_ue.LandscapeProxy.md#getdistanceto)

#### Defined in

[ue/ue.d.ts:13234](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13234)

___

### GetDotProductTo

▸ **GetDotProductTo**(`OtherActor`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetDotProductTo](ue_ue.LandscapeProxy.md#getdotproductto)

#### Defined in

[ue/ue.d.ts:13235](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13235)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetFolderPath](ue_ue.LandscapeProxy.md#getfolderpath)

#### Defined in

[ue/ue.d.ts:13236](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13236)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetGameTimeSinceCreation](ue_ue.LandscapeProxy.md#getgametimesincecreation)

#### Defined in

[ue/ue.d.ts:13237](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13237)

___

### GetHorizontalDistanceTo

▸ **GetHorizontalDistanceTo**(`OtherActor`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetHorizontalDistanceTo](ue_ue.LandscapeProxy.md#gethorizontaldistanceto)

#### Defined in

[ue/ue.d.ts:13238](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13238)

___

### GetHorizontalDotProductTo

▸ **GetHorizontalDotProductTo**(`OtherActor`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetHorizontalDotProductTo](ue_ue.LandscapeProxy.md#gethorizontaldotproductto)

#### Defined in

[ue/ue.d.ts:13239](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13239)

___

### GetInputAxisKeyValue

▸ **GetInputAxisKeyValue**(`InputAxisKey`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InputAxisKey` | [`Key`](ue_ue.Key.md) |

#### Returns

`number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetInputAxisKeyValue](ue_ue.LandscapeProxy.md#getinputaxiskeyvalue)

#### Defined in

[ue/ue.d.ts:13240](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13240)

___

### GetInputAxisValue

▸ **GetInputAxisValue**(`InputAxisName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InputAxisName` | `string` |

#### Returns

`number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetInputAxisValue](ue_ue.LandscapeProxy.md#getinputaxisvalue)

#### Defined in

[ue/ue.d.ts:13241](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13241)

___

### GetInputVectorAxisValue

▸ **GetInputVectorAxisValue**(`InputAxisKey`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InputAxisKey` | [`Key`](ue_ue.Key.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetInputVectorAxisValue](ue_ue.LandscapeProxy.md#getinputvectoraxisvalue)

#### Defined in

[ue/ue.d.ts:13242](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13242)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetInstigator](ue_ue.LandscapeProxy.md#getinstigator)

#### Defined in

[ue/ue.d.ts:13243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13243)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetInstigatorController](ue_ue.LandscapeProxy.md#getinstigatorcontroller)

#### Defined in

[ue/ue.d.ts:13244](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13244)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetLifeSpan](ue_ue.LandscapeProxy.md#getlifespan)

#### Defined in

[ue/ue.d.ts:13245](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13245)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetLocalRole](ue_ue.LandscapeProxy.md#getlocalrole)

#### Defined in

[ue/ue.d.ts:13246](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13246)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetName](ue_ue.LandscapeProxy.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetOuter](ue_ue.LandscapeProxy.md#getouter)

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetOverlappingActors](ue_ue.LandscapeProxy.md#getoverlappingactors)

#### Defined in

[ue/ue.d.ts:13247](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13247)

___

### GetOverlappingComponents

▸ **GetOverlappingComponents**(`OverlappingComponents`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OverlappingComponents` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>\> |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetOverlappingComponents](ue_ue.LandscapeProxy.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:13248](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13248)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetOwner](ue_ue.LandscapeProxy.md#getowner)

#### Defined in

[ue/ue.d.ts:13249](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13249)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetParentActor](ue_ue.LandscapeProxy.md#getparentactor)

#### Defined in

[ue/ue.d.ts:13250](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13250)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetParentComponent](ue_ue.LandscapeProxy.md#getparentcomponent)

#### Defined in

[ue/ue.d.ts:13251](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13251)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetRemoteRole](ue_ue.LandscapeProxy.md#getremoterole)

#### Defined in

[ue/ue.d.ts:13252](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13252)

___

### GetSquaredDistanceTo

▸ **GetSquaredDistanceTo**(`OtherActor`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetSquaredDistanceTo](ue_ue.LandscapeProxy.md#getsquareddistanceto)

#### Defined in

[ue/ue.d.ts:13253](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13253)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetTickableWhenPaused](ue_ue.LandscapeProxy.md#gettickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13254](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13254)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetTransform](ue_ue.LandscapeProxy.md#gettransform)

#### Defined in

[ue/ue.d.ts:13255](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13255)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetVelocity](ue_ue.LandscapeProxy.md#getvelocity)

#### Defined in

[ue/ue.d.ts:13256](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13256)

___

### GetVerticalDistanceTo

▸ **GetVerticalDistanceTo**(`OtherActor`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`number`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetVerticalDistanceTo](ue_ue.LandscapeProxy.md#getverticaldistanceto)

#### Defined in

[ue/ue.d.ts:13257](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13257)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[GetWorld](ue_ue.LandscapeProxy.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[HasAuthority](ue_ue.LandscapeProxy.md#hasauthority)

#### Defined in

[ue/ue.d.ts:13258](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13258)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[IsActorBeingDestroyed](ue_ue.LandscapeProxy.md#isactorbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13259](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13259)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[IsActorTickEnabled](ue_ue.LandscapeProxy.md#isactortickenabled)

#### Defined in

[ue/ue.d.ts:13260](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13260)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[IsChildActor](ue_ue.LandscapeProxy.md#ischildactor)

#### Defined in

[ue/ue.d.ts:13261](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13261)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[IsEditable](ue_ue.LandscapeProxy.md#iseditable)

#### Defined in

[ue/ue.d.ts:13262](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13262)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[IsHiddenEd](ue_ue.LandscapeProxy.md#ishiddened)

#### Defined in

[ue/ue.d.ts:13263](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13263)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[IsHiddenEdAtStartup](ue_ue.LandscapeProxy.md#ishiddenedatstartup)

#### Defined in

[ue/ue.d.ts:13264](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13264)

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[IsOverlappingActor](ue_ue.LandscapeProxy.md#isoverlappingactor)

#### Defined in

[ue/ue.d.ts:13265](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13265)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[IsSelectable](ue_ue.LandscapeProxy.md#isselectable)

#### Defined in

[ue/ue.d.ts:13266](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13266)

___

### IsTemporarilyHiddenInEditor

▸ **IsTemporarilyHiddenInEditor**(`bIncludeParent?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIncludeParent?` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[IsTemporarilyHiddenInEditor](ue_ue.LandscapeProxy.md#istemporarilyhiddenineditor)

#### Defined in

[ue/ue.d.ts:13267](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13267)

___

### K2\_AddActorLocalOffset

▸ **K2_AddActorLocalOffset**(`DeltaLocation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_AddActorLocalOffset](ue_ue.LandscapeProxy.md#k2_addactorlocaloffset)

#### Defined in

[ue/ue.d.ts:13268](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13268)

___

### K2\_AddActorLocalRotation

▸ **K2_AddActorLocalRotation**(`DeltaRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_AddActorLocalRotation](ue_ue.LandscapeProxy.md#k2_addactorlocalrotation)

#### Defined in

[ue/ue.d.ts:13269](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13269)

___

### K2\_AddActorLocalTransform

▸ **K2_AddActorLocalTransform**(`NewTransform`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_AddActorLocalTransform](ue_ue.LandscapeProxy.md#k2_addactorlocaltransform)

#### Defined in

[ue/ue.d.ts:13270](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13270)

___

### K2\_AddActorWorldOffset

▸ **K2_AddActorWorldOffset**(`DeltaLocation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_AddActorWorldOffset](ue_ue.LandscapeProxy.md#k2_addactorworldoffset)

#### Defined in

[ue/ue.d.ts:13271](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13271)

___

### K2\_AddActorWorldRotation

▸ **K2_AddActorWorldRotation**(`DeltaRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_AddActorWorldRotation](ue_ue.LandscapeProxy.md#k2_addactorworldrotation)

#### Defined in

[ue/ue.d.ts:13272](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13272)

___

### K2\_AddActorWorldTransform

▸ **K2_AddActorWorldTransform**(`DeltaTransform`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_AddActorWorldTransform](ue_ue.LandscapeProxy.md#k2_addactorworldtransform)

#### Defined in

[ue/ue.d.ts:13273](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13273)

___

### K2\_AttachRootComponentTo

▸ **K2_AttachRootComponentTo**(`InParent`, `InSocketName?`, `AttachLocationType?`, `bWeldSimulatedBodies?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InParent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `InSocketName?` | `string` |
| `AttachLocationType?` | [`EAttachLocation`](../enums/ue_ue.EAttachLocation.md) |
| `bWeldSimulatedBodies?` | `boolean` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_AttachRootComponentTo](ue_ue.LandscapeProxy.md#k2_attachrootcomponentto)

#### Defined in

[ue/ue.d.ts:13274](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13274)

___

### K2\_AttachRootComponentToActor

▸ **K2_AttachRootComponentToActor**(`InParentActor`, `InSocketName?`, `AttachLocationType?`, `bWeldSimulatedBodies?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InParentActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `InSocketName?` | `string` |
| `AttachLocationType?` | [`EAttachLocation`](../enums/ue_ue.EAttachLocation.md) |
| `bWeldSimulatedBodies?` | `boolean` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_AttachRootComponentToActor](ue_ue.LandscapeProxy.md#k2_attachrootcomponenttoactor)

#### Defined in

[ue/ue.d.ts:13275](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13275)

___

### K2\_AttachToActor

▸ **K2_AttachToActor**(`ParentActor`, `SocketName`, `LocationRule`, `RotationRule`, `ScaleRule`, `bWeldSimulatedBodies`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParentActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `SocketName` | `string` |
| `LocationRule` | [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md) |
| `RotationRule` | [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md) |
| `ScaleRule` | [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md) |
| `bWeldSimulatedBodies` | `boolean` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_AttachToActor](ue_ue.LandscapeProxy.md#k2_attachtoactor)

#### Defined in

[ue/ue.d.ts:13276](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13276)

___

### K2\_AttachToComponent

▸ **K2_AttachToComponent**(`Parent`, `SocketName`, `LocationRule`, `RotationRule`, `ScaleRule`, `bWeldSimulatedBodies`): `void`

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

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_AttachToComponent](ue_ue.LandscapeProxy.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:13277](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13277)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_DestroyActor](ue_ue.LandscapeProxy.md#k2_destroyactor)

#### Defined in

[ue/ue.d.ts:13278](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13278)

___

### K2\_DestroyComponent

▸ **K2_DestroyComponent**(`Component`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Component` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\> |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_DestroyComponent](ue_ue.LandscapeProxy.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:13279](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13279)

___

### K2\_DetachFromActor

▸ **K2_DetachFromActor**(`LocationRule?`, `RotationRule?`, `ScaleRule?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LocationRule?` | [`EDetachmentRule`](../enums/ue_ue.EDetachmentRule.md) |
| `RotationRule?` | [`EDetachmentRule`](../enums/ue_ue.EDetachmentRule.md) |
| `ScaleRule?` | [`EDetachmentRule`](../enums/ue_ue.EDetachmentRule.md) |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_DetachFromActor](ue_ue.LandscapeProxy.md#k2_detachfromactor)

#### Defined in

[ue/ue.d.ts:13280](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13280)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_GetActorLocation](ue_ue.LandscapeProxy.md#k2_getactorlocation)

#### Defined in

[ue/ue.d.ts:13281](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13281)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_GetActorRotation](ue_ue.LandscapeProxy.md#k2_getactorrotation)

#### Defined in

[ue/ue.d.ts:13282](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13282)

___

### K2\_GetComponentsByClass

▸ **K2_GetComponentsByClass**(`ComponentClass`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ComponentClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_GetComponentsByClass](ue_ue.LandscapeProxy.md#k2_getcomponentsbyclass)

#### Defined in

[ue/ue.d.ts:13283](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13283)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_GetRootComponent](ue_ue.LandscapeProxy.md#k2_getrootcomponent)

#### Defined in

[ue/ue.d.ts:13284](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13284)

___

### K2\_OnBecomeViewTarget

▸ **K2_OnBecomeViewTarget**(`PC`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PC` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_OnBecomeViewTarget](ue_ue.LandscapeProxy.md#k2_onbecomeviewtarget)

#### Defined in

[ue/ue.d.ts:13285](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13285)

___

### K2\_OnEndViewTarget

▸ **K2_OnEndViewTarget**(`PC`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PC` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_OnEndViewTarget](ue_ue.LandscapeProxy.md#k2_onendviewtarget)

#### Defined in

[ue/ue.d.ts:13286](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13286)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_OnReset](ue_ue.LandscapeProxy.md#k2_onreset)

#### Defined in

[ue/ue.d.ts:13287](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13287)

___

### K2\_SetActorLocation

▸ **K2_SetActorLocation**(`NewLocation`, `bSweep`, `SweepHitResult`, `bTeleport`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_SetActorLocation](ue_ue.LandscapeProxy.md#k2_setactorlocation)

#### Defined in

[ue/ue.d.ts:13288](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13288)

___

### K2\_SetActorLocationAndRotation

▸ **K2_SetActorLocationAndRotation**(`NewLocation`, `NewRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_SetActorLocationAndRotation](ue_ue.LandscapeProxy.md#k2_setactorlocationandrotation)

#### Defined in

[ue/ue.d.ts:13289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13289)

___

### K2\_SetActorRelativeLocation

▸ **K2_SetActorRelativeLocation**(`NewRelativeLocation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRelativeLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_SetActorRelativeLocation](ue_ue.LandscapeProxy.md#k2_setactorrelativelocation)

#### Defined in

[ue/ue.d.ts:13290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13290)

___

### K2\_SetActorRelativeRotation

▸ **K2_SetActorRelativeRotation**(`NewRelativeRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRelativeRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_SetActorRelativeRotation](ue_ue.LandscapeProxy.md#k2_setactorrelativerotation)

#### Defined in

[ue/ue.d.ts:13291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13291)

___

### K2\_SetActorRelativeTransform

▸ **K2_SetActorRelativeTransform**(`NewRelativeTransform`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRelativeTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_SetActorRelativeTransform](ue_ue.LandscapeProxy.md#k2_setactorrelativetransform)

#### Defined in

[ue/ue.d.ts:13292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13292)

___

### K2\_SetActorRotation

▸ **K2_SetActorRotation**(`NewRotation`, `bTeleportPhysics`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bTeleportPhysics` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_SetActorRotation](ue_ue.LandscapeProxy.md#k2_setactorrotation)

#### Defined in

[ue/ue.d.ts:13293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13293)

___

### K2\_SetActorTransform

▸ **K2_SetActorTransform**(`NewTransform`, `bSweep`, `SweepHitResult`, `bTeleport`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_SetActorTransform](ue_ue.LandscapeProxy.md#k2_setactortransform)

#### Defined in

[ue/ue.d.ts:13294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13294)

___

### K2\_TeleportTo

▸ **K2_TeleportTo**(`DestLocation`, `DestRotation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DestLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `DestRotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[K2_TeleportTo](ue_ue.LandscapeProxy.md#k2_teleportto)

#### Defined in

[ue/ue.d.ts:13295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13295)

___

### LandscapeExportHeightmapToRenderTarget

▸ **LandscapeExportHeightmapToRenderTarget**(`InRenderTarget`, `InExportHeightIntoRGChannel?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRenderTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)\> |
| `InExportHeightIntoRGChannel?` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LandscapeExportHeightmapToRenderTarget](ue_ue.LandscapeProxy.md#landscapeexportheightmaptorendertarget)

#### Defined in

[ue/ue.d.ts:44133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44133)

___

### LandscapeExportWeightmapToRenderTarget

▸ **LandscapeExportWeightmapToRenderTarget**(`InRenderTarget`, `InLayerName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRenderTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)\> |
| `InLayerName` | `string` |

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LandscapeExportWeightmapToRenderTarget](ue_ue.LandscapeProxy.md#landscapeexportweightmaptorendertarget)

#### Defined in

[ue/ue.d.ts:44134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44134)

___

### LandscapeImportHeightmapFromRenderTarget

▸ **LandscapeImportHeightmapFromRenderTarget**(`InRenderTarget`, `InImportHeightFromRGChannel?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRenderTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)\> |
| `InImportHeightFromRGChannel?` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LandscapeImportHeightmapFromRenderTarget](ue_ue.LandscapeProxy.md#landscapeimportheightmapfromrendertarget)

#### Defined in

[ue/ue.d.ts:44135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44135)

___

### LandscapeImportWeightmapFromRenderTarget

▸ **LandscapeImportWeightmapFromRenderTarget**(`InRenderTarget`, `InLayerName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRenderTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)\> |
| `InLayerName` | `string` |

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[LandscapeImportWeightmapFromRenderTarget](ue_ue.LandscapeProxy.md#landscapeimportweightmapfromrendertarget)

#### Defined in

[ue/ue.d.ts:44136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44136)

___

### MakeMIDForMaterial

▸ **MakeMIDForMaterial**(`Parent`): [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Parent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |

#### Returns

[`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[MakeMIDForMaterial](ue_ue.LandscapeProxy.md#makemidformaterial)

#### Defined in

[ue/ue.d.ts:13296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13296)

___

### MakeNoise

▸ **MakeNoise**(`Loudness?`, `NoiseInstigator?`, `NoiseLocation?`, `MaxRange?`, `Tag?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Loudness?` | `number` |
| `NoiseInstigator?` | [`Pawn`](ue_ue.Pawn.md) |
| `NoiseLocation?` | [`Vector`](ue_ue_s.Vector.md) |
| `MaxRange?` | `number` |
| `Tag?` | `string` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[MakeNoise](ue_ue.LandscapeProxy.md#makenoise)

#### Defined in

[ue/ue.d.ts:13297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13297)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnRep_AttachmentReplication](ue_ue.LandscapeProxy.md#onrep_attachmentreplication)

#### Defined in

[ue/ue.d.ts:13298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13298)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnRep_Instigator](ue_ue.LandscapeProxy.md#onrep_instigator)

#### Defined in

[ue/ue.d.ts:13299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13299)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnRep_Owner](ue_ue.LandscapeProxy.md#onrep_owner)

#### Defined in

[ue/ue.d.ts:13300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13300)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnRep_ReplicateMovement](ue_ue.LandscapeProxy.md#onrep_replicatemovement)

#### Defined in

[ue/ue.d.ts:13302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13302)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[OnRep_ReplicatedMovement](ue_ue.LandscapeProxy.md#onrep_replicatedmovement)

#### Defined in

[ue/ue.d.ts:13301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13301)

___

### PrestreamTextures

▸ **PrestreamTextures**(`Seconds`, `bEnableStreaming`, `CinematicTextureGroups?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Seconds` | `number` |
| `bEnableStreaming` | `boolean` |
| `CinematicTextureGroups?` | `number` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[PrestreamTextures](ue_ue.LandscapeProxy.md#prestreamtextures)

#### Defined in

[ue/ue.d.ts:13303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13303)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceiveActorBeginCursorOver](ue_ue.LandscapeProxy.md#receiveactorbegincursorover)

#### Defined in

[ue/ue.d.ts:13304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13304)

___

### ReceiveActorBeginOverlap

▸ **ReceiveActorBeginOverlap**(`OtherActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceiveActorBeginOverlap](ue_ue.LandscapeProxy.md#receiveactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13305)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceiveActorEndCursorOver](ue_ue.LandscapeProxy.md#receiveactorendcursorover)

#### Defined in

[ue/ue.d.ts:13306](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13306)

___

### ReceiveActorEndOverlap

▸ **ReceiveActorEndOverlap**(`OtherActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceiveActorEndOverlap](ue_ue.LandscapeProxy.md#receiveactorendoverlap)

#### Defined in

[ue/ue.d.ts:13307](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13307)

___

### ReceiveActorOnClicked

▸ **ReceiveActorOnClicked**(`ButtonPressed`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ButtonPressed` | [`Key`](ue_ue.Key.md) |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceiveActorOnClicked](ue_ue.LandscapeProxy.md#receiveactoronclicked)

#### Defined in

[ue/ue.d.ts:13308](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13308)

___

### ReceiveActorOnInputTouchBegin

▸ **ReceiveActorOnInputTouchBegin**(`FingerIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FingerIndex` | [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md) |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceiveActorOnInputTouchBegin](ue_ue.LandscapeProxy.md#receiveactoroninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13309](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13309)

___

### ReceiveActorOnInputTouchEnd

▸ **ReceiveActorOnInputTouchEnd**(`FingerIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FingerIndex` | [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md) |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceiveActorOnInputTouchEnd](ue_ue.LandscapeProxy.md#receiveactoroninputtouchend)

#### Defined in

[ue/ue.d.ts:13310](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13310)

___

### ReceiveActorOnInputTouchEnter

▸ **ReceiveActorOnInputTouchEnter**(`FingerIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FingerIndex` | [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md) |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceiveActorOnInputTouchEnter](ue_ue.LandscapeProxy.md#receiveactoroninputtouchenter)

#### Defined in

[ue/ue.d.ts:13311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13311)

___

### ReceiveActorOnInputTouchLeave

▸ **ReceiveActorOnInputTouchLeave**(`FingerIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FingerIndex` | [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md) |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceiveActorOnInputTouchLeave](ue_ue.LandscapeProxy.md#receiveactoroninputtouchleave)

#### Defined in

[ue/ue.d.ts:13312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13312)

___

### ReceiveActorOnReleased

▸ **ReceiveActorOnReleased**(`ButtonReleased`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ButtonReleased` | [`Key`](ue_ue.Key.md) |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceiveActorOnReleased](ue_ue.LandscapeProxy.md#receiveactoronreleased)

#### Defined in

[ue/ue.d.ts:13313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13313)

___

### ReceiveAnyDamage

▸ **ReceiveAnyDamage**(`Damage`, `DamageType`, `InstigatedBy`, `DamageCauser`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Damage` | `number` |
| `DamageType` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\> |
| `InstigatedBy` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |
| `DamageCauser` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceiveAnyDamage](ue_ue.LandscapeProxy.md#receiveanydamage)

#### Defined in

[ue/ue.d.ts:13314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13314)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceiveBeginPlay](ue_ue.LandscapeProxy.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:13315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13315)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceiveDestroyed](ue_ue.LandscapeProxy.md#receivedestroyed)

#### Defined in

[ue/ue.d.ts:13316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13316)

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceiveEndPlay](ue_ue.LandscapeProxy.md#receiveendplay)

#### Defined in

[ue/ue.d.ts:13317](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13317)

___

### ReceiveHit

▸ **ReceiveHit**(`MyComp`, `Other`, `OtherComp`, `bSelfMoved`, `HitLocation`, `HitNormal`, `NormalImpulse`, `Hit`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyComp` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `Other` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `OtherComp` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `bSelfMoved` | `boolean` |
| `HitLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `HitNormal` | [`Vector`](ue_ue_s.Vector.md) |
| `NormalImpulse` | [`Vector`](ue_ue_s.Vector.md) |
| `Hit` | [`HitResult`](ue_ue.HitResult.md) |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceiveHit](ue_ue.LandscapeProxy.md#receivehit)

#### Defined in

[ue/ue.d.ts:13318](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13318)

___

### ReceivePointDamage

▸ **ReceivePointDamage**(`Damage`, `DamageType`, `HitLocation`, `HitNormal`, `HitComponent`, `BoneName`, `ShotFromDirection`, `InstigatedBy`, `DamageCauser`, `HitInfo`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Damage` | `number` |
| `DamageType` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\> |
| `HitLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `HitNormal` | [`Vector`](ue_ue_s.Vector.md) |
| `HitComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `BoneName` | `string` |
| `ShotFromDirection` | [`Vector`](ue_ue_s.Vector.md) |
| `InstigatedBy` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |
| `DamageCauser` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `HitInfo` | [`HitResult`](ue_ue.HitResult.md) |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceivePointDamage](ue_ue.LandscapeProxy.md#receivepointdamage)

#### Defined in

[ue/ue.d.ts:13319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13319)

___

### ReceiveRadialDamage

▸ **ReceiveRadialDamage**(`DamageReceived`, `DamageType`, `Origin`, `HitInfo`, `InstigatedBy`, `DamageCauser`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DamageReceived` | `number` |
| `DamageType` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\> |
| `Origin` | [`Vector`](ue_ue_s.Vector.md) |
| `HitInfo` | [`HitResult`](ue_ue.HitResult.md) |
| `InstigatedBy` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |
| `DamageCauser` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceiveRadialDamage](ue_ue.LandscapeProxy.md#receiveradialdamage)

#### Defined in

[ue/ue.d.ts:13320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13320)

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[ReceiveTick](ue_ue.LandscapeProxy.md#receivetick)

#### Defined in

[ue/ue.d.ts:13321](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13321)

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[RemoveTickPrerequisiteActor](ue_ue.LandscapeProxy.md#removetickprerequisiteactor)

#### Defined in

[ue/ue.d.ts:13322](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13322)

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[RemoveTickPrerequisiteComponent](ue_ue.LandscapeProxy.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13323](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13323)

___

### SetActorEnableCollision

▸ **SetActorEnableCollision**(`bNewActorEnableCollision`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewActorEnableCollision` | `boolean` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetActorEnableCollision](ue_ue.LandscapeProxy.md#setactorenablecollision)

#### Defined in

[ue/ue.d.ts:13324](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13324)

___

### SetActorHiddenInGame

▸ **SetActorHiddenInGame**(`bNewHidden`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewHidden` | `boolean` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetActorHiddenInGame](ue_ue.LandscapeProxy.md#setactorhiddeningame)

#### Defined in

[ue/ue.d.ts:13325](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13325)

___

### SetActorLabel

▸ **SetActorLabel**(`NewActorLabel`, `bMarkDirty?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewActorLabel` | `string` |
| `bMarkDirty?` | `boolean` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetActorLabel](ue_ue.LandscapeProxy.md#setactorlabel)

#### Defined in

[ue/ue.d.ts:13326](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13326)

___

### SetActorRelativeScale3D

▸ **SetActorRelativeScale3D**(`NewRelativeScale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRelativeScale` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetActorRelativeScale3D](ue_ue.LandscapeProxy.md#setactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13327](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13327)

___

### SetActorScale3D

▸ **SetActorScale3D**(`NewScale3D`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScale3D` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetActorScale3D](ue_ue.LandscapeProxy.md#setactorscale3d)

#### Defined in

[ue/ue.d.ts:13328](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13328)

___

### SetActorTickEnabled

▸ **SetActorTickEnabled**(`bEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnabled` | `boolean` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetActorTickEnabled](ue_ue.LandscapeProxy.md#setactortickenabled)

#### Defined in

[ue/ue.d.ts:13329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13329)

___

### SetActorTickInterval

▸ **SetActorTickInterval**(`TickInterval`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TickInterval` | `number` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetActorTickInterval](ue_ue.LandscapeProxy.md#setactortickinterval)

#### Defined in

[ue/ue.d.ts:13330](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13330)

___

### SetFolderPath

▸ **SetFolderPath**(`NewFolderPath`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewFolderPath` | `string` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetFolderPath](ue_ue.LandscapeProxy.md#setfolderpath)

#### Defined in

[ue/ue.d.ts:13331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13331)

___

### SetIsTemporarilyHiddenInEditor

▸ **SetIsTemporarilyHiddenInEditor**(`bIsHidden`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIsHidden` | `boolean` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetIsTemporarilyHiddenInEditor](ue_ue.LandscapeProxy.md#setistemporarilyhiddenineditor)

#### Defined in

[ue/ue.d.ts:13332](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13332)

___

### SetLandscapeMaterialScalarParameterValue

▸ **SetLandscapeMaterialScalarParameterValue**(`ParameterName`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `Value` | `number` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetLandscapeMaterialScalarParameterValue](ue_ue.LandscapeProxy.md#setlandscapematerialscalarparametervalue)

#### Defined in

[ue/ue.d.ts:44137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44137)

___

### SetLandscapeMaterialTextureParameterValue

▸ **SetLandscapeMaterialTextureParameterValue**(`ParameterName`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `Value` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetLandscapeMaterialTextureParameterValue](ue_ue.LandscapeProxy.md#setlandscapematerialtextureparametervalue)

#### Defined in

[ue/ue.d.ts:44138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44138)

___

### SetLandscapeMaterialVectorParameterValue

▸ **SetLandscapeMaterialVectorParameterValue**(`ParameterName`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `Value` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetLandscapeMaterialVectorParameterValue](ue_ue.LandscapeProxy.md#setlandscapematerialvectorparametervalue)

#### Defined in

[ue/ue.d.ts:44139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44139)

___

### SetLifeSpan

▸ **SetLifeSpan**(`InLifespan`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLifespan` | `number` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetLifeSpan](ue_ue.LandscapeProxy.md#setlifespan)

#### Defined in

[ue/ue.d.ts:13333](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13333)

___

### SetNetDormancy

▸ **SetNetDormancy**(`NewDormancy`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewDormancy` | [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md) |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetNetDormancy](ue_ue.LandscapeProxy.md#setnetdormancy)

#### Defined in

[ue/ue.d.ts:13334](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13334)

___

### SetOwner

▸ **SetOwner**(`NewOwner`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetOwner](ue_ue.LandscapeProxy.md#setowner)

#### Defined in

[ue/ue.d.ts:13335](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13335)

___

### SetReplicateMovement

▸ **SetReplicateMovement**(`bInReplicateMovement`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInReplicateMovement` | `boolean` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetReplicateMovement](ue_ue.LandscapeProxy.md#setreplicatemovement)

#### Defined in

[ue/ue.d.ts:13336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13336)

___

### SetReplicates

▸ **SetReplicates**(`bInReplicates`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInReplicates` | `boolean` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetReplicates](ue_ue.LandscapeProxy.md#setreplicates)

#### Defined in

[ue/ue.d.ts:13337](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13337)

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetTickGroup](ue_ue.LandscapeProxy.md#settickgroup)

#### Defined in

[ue/ue.d.ts:13339](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13339)

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

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SetTickableWhenPaused](ue_ue.LandscapeProxy.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13338](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13338)

___

### SnapRootComponentTo

▸ **SnapRootComponentTo**(`InParentActor`, `InSocketName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InParentActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `InSocketName` | `string` |

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[SnapRootComponentTo](ue_ue.LandscapeProxy.md#snaprootcomponentto)

#### Defined in

[ue/ue.d.ts:13340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13340)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[TearOff](ue_ue.LandscapeProxy.md#tearoff)

#### Defined in

[ue/ue.d.ts:13341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13341)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[UserConstructionScript](ue_ue.LandscapeProxy.md#userconstructionscript)

#### Defined in

[ue/ue.d.ts:13342](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13342)

___

### WasRecentlyRendered

▸ **WasRecentlyRendered**(`Tolerance?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance?` | `number` |

#### Returns

`boolean`

#### Inherited from

[LandscapeProxy](ue_ue.LandscapeProxy.md).[WasRecentlyRendered](ue_ue.LandscapeProxy.md#wasrecentlyrendered)

#### Defined in

[ue/ue.d.ts:13343](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13343)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LandscapeStreamingProxy`](ue_ue.LandscapeStreamingProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LandscapeStreamingProxy`](ue_ue.LandscapeStreamingProxy.md)

#### Overrides

[LandscapeProxy](ue_ue.LandscapeProxy.md).[Find](ue_ue.LandscapeProxy.md#find)

#### Defined in

[ue/ue.d.ts:44412](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44412)

___

### Load

▸ `Static` **Load**(`InName`): [`LandscapeStreamingProxy`](ue_ue.LandscapeStreamingProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LandscapeStreamingProxy`](ue_ue.LandscapeStreamingProxy.md)

#### Overrides

[LandscapeProxy](ue_ue.LandscapeProxy.md).[Load](ue_ue.LandscapeProxy.md#load)

#### Defined in

[ue/ue.d.ts:44413](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44413)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[LandscapeProxy](ue_ue.LandscapeProxy.md).[StaticClass](ue_ue.LandscapeProxy.md#staticclass)

#### Defined in

[ue/ue.d.ts:44411](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44411)
