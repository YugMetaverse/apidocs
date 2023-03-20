[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / RecastNavMesh

# Class: RecastNavMesh

[ue/ue](../modules/ue_ue.md).RecastNavMesh

## Hierarchy

- [`NavigationData`](ue_ue.NavigationData.md)

  ↳ **`RecastNavMesh`**

## Table of contents

### Constructors

- [constructor](ue_ue.RecastNavMesh.md#constructor)

### Properties

- [ActorLabel](ue_ue.RecastNavMesh.md#actorlabel)
- [AgentHeight](ue_ue.RecastNavMesh.md#agentheight)
- [AgentMaxHeight](ue_ue.RecastNavMesh.md#agentmaxheight)
- [AgentMaxSlope](ue_ue.RecastNavMesh.md#agentmaxslope)
- [AgentMaxStepHeight](ue_ue.RecastNavMesh.md#agentmaxstepheight)
- [AgentRadius](ue_ue.RecastNavMesh.md#agentradius)
- [AttachmentReplication](ue_ue.RecastNavMesh.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.RecastNavMesh.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.RecastNavMesh.md#blueprintcreatedcomponents)
- [CellHeight](ue_ue.RecastNavMesh.md#cellheight)
- [CellSize](ue_ue.RecastNavMesh.md#cellsize)
- [Children](ue_ue.RecastNavMesh.md#children)
- [ControllingMatineeActors](ue_ue.RecastNavMesh.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.RecastNavMesh.md#customtimedilation)
- [DataVersion](ue_ue.RecastNavMesh.md#dataversion)
- [DefaultDrawDistance](ue_ue.RecastNavMesh.md#defaultdrawdistance)
- [DefaultMaxHierarchicalSearchNodes](ue_ue.RecastNavMesh.md#defaultmaxhierarchicalsearchnodes)
- [DefaultMaxSearchNodes](ue_ue.RecastNavMesh.md#defaultmaxsearchnodes)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.RecastNavMesh.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [DrawOffset](ue_ue.RecastNavMesh.md#drawoffset)
- [FolderPath](ue_ue.RecastNavMesh.md#folderpath)
- [GroupActor](ue_ue.RecastNavMesh.md#groupactor)
- [HeuristicScale](ue_ue.RecastNavMesh.md#heuristicscale)
- [HiddenEditorViews](ue_ue.RecastNavMesh.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.RecastNavMesh.md#initiallifespan)
- [InputComponent](ue_ue.RecastNavMesh.md#inputcomponent)
- [InputPriority](ue_ue.RecastNavMesh.md#inputpriority)
- [InstanceComponents](ue_ue.RecastNavMesh.md#instancecomponents)
- [Instigator](ue_ue.RecastNavMesh.md#instigator)
- [LayerChunkSplits](ue_ue.RecastNavMesh.md#layerchunksplits)
- [LayerPartitioning](ue_ue.RecastNavMesh.md#layerpartitioning)
- [Layers](ue_ue.RecastNavMesh.md#layers)
- [MaxSimplificationError](ue_ue.RecastNavMesh.md#maxsimplificationerror)
- [MaxSimultaneousTileGenerationJobsCount](ue_ue.RecastNavMesh.md#maxsimultaneoustilegenerationjobscount)
- [MergeRegionSize](ue_ue.RecastNavMesh.md#mergeregionsize)
- [MinNetUpdateFrequency](ue_ue.RecastNavMesh.md#minnetupdatefrequency)
- [MinRegionArea](ue_ue.RecastNavMesh.md#minregionarea)
- [NavDataConfig](ue_ue.RecastNavMesh.md#navdataconfig)
- [NavMeshOriginOffset](ue_ue.RecastNavMesh.md#navmeshoriginoffset)
- [NetCullDistanceSquared](ue_ue.RecastNavMesh.md#netculldistancesquared)
- [NetDormancy](ue_ue.RecastNavMesh.md#netdormancy)
- [NetDriverName](ue_ue.RecastNavMesh.md#netdrivername)
- [NetPriority](ue_ue.RecastNavMesh.md#netpriority)
- [NetTag](ue_ue.RecastNavMesh.md#nettag)
- [NetUpdateFrequency](ue_ue.RecastNavMesh.md#netupdatefrequency)
- [ObservedPathsTickInterval](ue_ue.RecastNavMesh.md#observedpathstickinterval)
- [OnActorBeginOverlap](ue_ue.RecastNavMesh.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.RecastNavMesh.md#onactorendoverlap)
- [OnActorHit](ue_ue.RecastNavMesh.md#onactorhit)
- [OnBeginCursorOver](ue_ue.RecastNavMesh.md#onbegincursorover)
- [OnClicked](ue_ue.RecastNavMesh.md#onclicked)
- [OnDestroyed](ue_ue.RecastNavMesh.md#ondestroyed)
- [OnEndCursorOver](ue_ue.RecastNavMesh.md#onendcursorover)
- [OnEndPlay](ue_ue.RecastNavMesh.md#onendplay)
- [OnInputTouchBegin](ue_ue.RecastNavMesh.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.RecastNavMesh.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.RecastNavMesh.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.RecastNavMesh.md#oninputtouchleave)
- [OnReleased](ue_ue.RecastNavMesh.md#onreleased)
- [OnTakeAnyDamage](ue_ue.RecastNavMesh.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.RecastNavMesh.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.RecastNavMesh.md#ontakeradialdamage)
- [Owner](ue_ue.RecastNavMesh.md#owner)
- [ParentComponent](ue_ue.RecastNavMesh.md#parentcomponent)
- [ParentComponentActor](ue_ue.RecastNavMesh.md#parentcomponentactor)
- [PivotOffset](ue_ue.RecastNavMesh.md#pivotoffset)
- [PolyRefNavPolyBits](ue_ue.RecastNavMesh.md#polyrefnavpolybits)
- [PolyRefSaltBits](ue_ue.RecastNavMesh.md#polyrefsaltbits)
- [PolyRefTileBits](ue_ue.RecastNavMesh.md#polyreftilebits)
- [PrimaryActorTick](ue_ue.RecastNavMesh.md#primaryactortick)
- [RegionChunkSplits](ue_ue.RecastNavMesh.md#regionchunksplits)
- [RegionPartitioning](ue_ue.RecastNavMesh.md#regionpartitioning)
- [RemoteRole](ue_ue.RecastNavMesh.md#remoterole)
- [RenderingComp](ue_ue.RecastNavMesh.md#renderingcomp)
- [ReplicatedMovement](ue_ue.RecastNavMesh.md#replicatedmovement)
- [Role](ue_ue.RecastNavMesh.md#role)
- [RootComponent](ue_ue.RecastNavMesh.md#rootcomponent)
- [RuntimeGeneration](ue_ue.RecastNavMesh.md#runtimegeneration)
- [SpawnCollisionHandlingMethod](ue_ue.RecastNavMesh.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.RecastNavMesh.md#spritescale)
- [SupportedAreas](ue_ue.RecastNavMesh.md#supportedareas)
- [Tags](ue_ue.RecastNavMesh.md#tags)
- [TileNumberHardLimit](ue_ue.RecastNavMesh.md#tilenumberhardlimit)
- [TilePoolSize](ue_ue.RecastNavMesh.md#tilepoolsize)
- [TileSetUpdateInterval](ue_ue.RecastNavMesh.md#tilesetupdateinterval)
- [TileSizeUU](ue_ue.RecastNavMesh.md#tilesizeuu)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.RecastNavMesh.md#updateoverlapsmethodduringlevelstreaming)
- [VerticalDeviationFromGroundCompensation](ue_ue.RecastNavMesh.md#verticaldeviationfromgroundcompensation)
- [\_\_tid\_Actor\_\_](ue_ue.RecastNavMesh.md#__tid_actor__)
- [\_\_tid\_NavigationData\_\_](ue_ue.RecastNavMesh.md#__tid_navigationdata__)
- [\_\_tid\_Object\_\_](ue_ue.RecastNavMesh.md#__tid_object__)
- [\_\_tid\_RecastNavMesh\_\_](ue_ue.RecastNavMesh.md#__tid_recastnavmesh__)
- [bActorEnableCollision](ue_ue.RecastNavMesh.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.RecastNavMesh.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.RecastNavMesh.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.RecastNavMesh.md#bactorseamlesstraveled)
- [bAllowNavLinkAsPathEnd](ue_ue.RecastNavMesh.md#ballownavlinkaspathend)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.RecastNavMesh.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.RecastNavMesh.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.RecastNavMesh.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.RecastNavMesh.md#bautodestroywhenfinished)
- [bAutoDestroyWhenNoNavigation](ue_ue.RecastNavMesh.md#bautodestroywhennonavigation)
- [bBlockInput](ue_ue.RecastNavMesh.md#bblockinput)
- [bCanBeDamaged](ue_ue.RecastNavMesh.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.RecastNavMesh.md#bcanbeincluster)
- [bCanBeMainNavData](ue_ue.RecastNavMesh.md#bcanbemainnavdata)
- [bCanSpawnOnRebuild](ue_ue.RecastNavMesh.md#bcanspawnonrebuild)
- [bCollideWhenPlacing](ue_ue.RecastNavMesh.md#bcollidewhenplacing)
- [bDistinctlyDrawTilesBeingBuilt](ue_ue.RecastNavMesh.md#bdistinctlydrawtilesbeingbuilt)
- [bDoFullyAsyncNavDataGathering](ue_ue.RecastNavMesh.md#bdofullyasyncnavdatagathering)
- [bDrawClusters](ue_ue.RecastNavMesh.md#bdrawclusters)
- [bDrawDefaultPolygonCost](ue_ue.RecastNavMesh.md#bdrawdefaultpolygoncost)
- [bDrawFailedNavLinks](ue_ue.RecastNavMesh.md#bdrawfailednavlinks)
- [bDrawFilledPolys](ue_ue.RecastNavMesh.md#bdrawfilledpolys)
- [bDrawLabelsOnPathNodes](ue_ue.RecastNavMesh.md#bdrawlabelsonpathnodes)
- [bDrawMarkedForbiddenPolys](ue_ue.RecastNavMesh.md#bdrawmarkedforbiddenpolys)
- [bDrawNavLinks](ue_ue.RecastNavMesh.md#bdrawnavlinks)
- [bDrawNavMesh](ue_ue.RecastNavMesh.md#bdrawnavmesh)
- [bDrawNavMeshEdges](ue_ue.RecastNavMesh.md#bdrawnavmeshedges)
- [bDrawOctree](ue_ue.RecastNavMesh.md#bdrawoctree)
- [bDrawOctreeDetails](ue_ue.RecastNavMesh.md#bdrawoctreedetails)
- [bDrawPathCollidingGeometry](ue_ue.RecastNavMesh.md#bdrawpathcollidinggeometry)
- [bDrawPolyEdges](ue_ue.RecastNavMesh.md#bdrawpolyedges)
- [bDrawPolygonLabels](ue_ue.RecastNavMesh.md#bdrawpolygonlabels)
- [bDrawTileBounds](ue_ue.RecastNavMesh.md#bdrawtilebounds)
- [bDrawTileLabels](ue_ue.RecastNavMesh.md#bdrawtilelabels)
- [bDrawTriangleEdges](ue_ue.RecastNavMesh.md#bdrawtriangleedges)
- [bEditable](ue_ue.RecastNavMesh.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.RecastNavMesh.md#benableautolodgeneration)
- [bEnableDrawing](ue_ue.RecastNavMesh.md#benabledrawing)
- [bExchangedRoles](ue_ue.RecastNavMesh.md#bexchangedroles)
- [bFilterLowSpanFromTileCache](ue_ue.RecastNavMesh.md#bfilterlowspanfromtilecache)
- [bFilterLowSpanSequences](ue_ue.RecastNavMesh.md#bfilterlowspansequences)
- [bFindCameraComponentWhenViewTarget](ue_ue.RecastNavMesh.md#bfindcameracomponentwhenviewtarget)
- [bFixedTilePoolSize](ue_ue.RecastNavMesh.md#bfixedtilepoolsize)
- [bForceRebuildOnLoad](ue_ue.RecastNavMesh.md#bforcerebuildonload)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.RecastNavMesh.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.RecastNavMesh.md#bhidden)
- [bHiddenEd](ue_ue.RecastNavMesh.md#bhiddened)
- [bHiddenEdLayer](ue_ue.RecastNavMesh.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.RecastNavMesh.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.RecastNavMesh.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.RecastNavMesh.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.RecastNavMesh.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.RecastNavMesh.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.RecastNavMesh.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.RecastNavMesh.md#blocklocation)
- [bMarkLowHeightAreas](ue_ue.RecastNavMesh.md#bmarklowheightareas)
- [bNetLoadOnClient](ue_ue.RecastNavMesh.md#bnetloadonclient)
- [bNetStartup](ue_ue.RecastNavMesh.md#bnetstartup)
- [bNetTemporary](ue_ue.RecastNavMesh.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.RecastNavMesh.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.RecastNavMesh.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.RecastNavMesh.md#boptimizebpcomponentdata)
- [bPerformVoxelFiltering](ue_ue.RecastNavMesh.md#bperformvoxelfiltering)
- [bRebuildAtRuntime](ue_ue.RecastNavMesh.md#brebuildatruntime)
- [bRelevantForLevelBounds](ue_ue.RecastNavMesh.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.RecastNavMesh.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.RecastNavMesh.md#breplayrewindable)
- [bReplicateMovement](ue_ue.RecastNavMesh.md#breplicatemovement)
- [bReplicates](ue_ue.RecastNavMesh.md#breplicates)
- [bSortNavigationAreasByCost](ue_ue.RecastNavMesh.md#bsortnavigationareasbycost)
- [bStoreEmptyTileLayers](ue_ue.RecastNavMesh.md#bstoreemptytilelayers)
- [bTearOff](ue_ue.RecastNavMesh.md#btearoff)
- [bUseBetterOffsetsFromCorners](ue_ue.RecastNavMesh.md#busebetteroffsetsfromcorners)
- [bUseVirtualFilters](ue_ue.RecastNavMesh.md#busevirtualfilters)
- [bUseVoxelCache](ue_ue.RecastNavMesh.md#busevoxelcache)

### Methods

- [ActorHasTag](ue_ue.RecastNavMesh.md#actorhastag)
- [AddComponent](ue_ue.RecastNavMesh.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.RecastNavMesh.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.RecastNavMesh.md#addtickprerequisitecomponent)
- [CreateDefaultSubobject](ue_ue.RecastNavMesh.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.RecastNavMesh.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.RecastNavMesh.md#disableinput)
- [EnableInput](ue_ue.RecastNavMesh.md#enableinput)
- [ExecuteUbergraph](ue_ue.RecastNavMesh.md#executeubergraph)
- [FlushNetDormancy](ue_ue.RecastNavMesh.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.RecastNavMesh.md#forcenetupdate)
- [GetActorBounds](ue_ue.RecastNavMesh.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.RecastNavMesh.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.RecastNavMesh.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.RecastNavMesh.md#getactorforwardvector)
- [GetActorLabel](ue_ue.RecastNavMesh.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.RecastNavMesh.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.RecastNavMesh.md#getactorrightvector)
- [GetActorScale3D](ue_ue.RecastNavMesh.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.RecastNavMesh.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.RecastNavMesh.md#getactortimedilation)
- [GetActorUpVector](ue_ue.RecastNavMesh.md#getactorupvector)
- [GetAllChildActors](ue_ue.RecastNavMesh.md#getallchildactors)
- [GetAttachParentActor](ue_ue.RecastNavMesh.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.RecastNavMesh.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.RecastNavMesh.md#getattachedactors)
- [GetClass](ue_ue.RecastNavMesh.md#getclass)
- [GetComponentByClass](ue_ue.RecastNavMesh.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.RecastNavMesh.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.RecastNavMesh.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.RecastNavMesh.md#getdistanceto)
- [GetDotProductTo](ue_ue.RecastNavMesh.md#getdotproductto)
- [GetFolderPath](ue_ue.RecastNavMesh.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.RecastNavMesh.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.RecastNavMesh.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.RecastNavMesh.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.RecastNavMesh.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.RecastNavMesh.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.RecastNavMesh.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.RecastNavMesh.md#getinstigator)
- [GetInstigatorController](ue_ue.RecastNavMesh.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.RecastNavMesh.md#getlifespan)
- [GetLocalRole](ue_ue.RecastNavMesh.md#getlocalrole)
- [GetName](ue_ue.RecastNavMesh.md#getname)
- [GetOuter](ue_ue.RecastNavMesh.md#getouter)
- [GetOverlappingActors](ue_ue.RecastNavMesh.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.RecastNavMesh.md#getoverlappingcomponents)
- [GetOwner](ue_ue.RecastNavMesh.md#getowner)
- [GetParentActor](ue_ue.RecastNavMesh.md#getparentactor)
- [GetParentComponent](ue_ue.RecastNavMesh.md#getparentcomponent)
- [GetRemoteRole](ue_ue.RecastNavMesh.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.RecastNavMesh.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.RecastNavMesh.md#gettickablewhenpaused)
- [GetTransform](ue_ue.RecastNavMesh.md#gettransform)
- [GetVelocity](ue_ue.RecastNavMesh.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.RecastNavMesh.md#getverticaldistanceto)
- [GetWorld](ue_ue.RecastNavMesh.md#getworld)
- [HasAuthority](ue_ue.RecastNavMesh.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.RecastNavMesh.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.RecastNavMesh.md#isactortickenabled)
- [IsChildActor](ue_ue.RecastNavMesh.md#ischildactor)
- [IsEditable](ue_ue.RecastNavMesh.md#iseditable)
- [IsHiddenEd](ue_ue.RecastNavMesh.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.RecastNavMesh.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.RecastNavMesh.md#isoverlappingactor)
- [IsSelectable](ue_ue.RecastNavMesh.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.RecastNavMesh.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.RecastNavMesh.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.RecastNavMesh.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.RecastNavMesh.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.RecastNavMesh.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.RecastNavMesh.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.RecastNavMesh.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.RecastNavMesh.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.RecastNavMesh.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.RecastNavMesh.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.RecastNavMesh.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.RecastNavMesh.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.RecastNavMesh.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.RecastNavMesh.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.RecastNavMesh.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.RecastNavMesh.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.RecastNavMesh.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.RecastNavMesh.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.RecastNavMesh.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.RecastNavMesh.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.RecastNavMesh.md#k2_onreset)
- [K2\_ReplaceAreaInTileBounds](ue_ue.RecastNavMesh.md#k2_replaceareaintilebounds)
- [K2\_SetActorLocation](ue_ue.RecastNavMesh.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.RecastNavMesh.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.RecastNavMesh.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.RecastNavMesh.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.RecastNavMesh.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.RecastNavMesh.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.RecastNavMesh.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.RecastNavMesh.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.RecastNavMesh.md#makemidformaterial)
- [MakeNoise](ue_ue.RecastNavMesh.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.RecastNavMesh.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.RecastNavMesh.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.RecastNavMesh.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.RecastNavMesh.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.RecastNavMesh.md#onrep_replicatedmovement)
- [PrestreamTextures](ue_ue.RecastNavMesh.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.RecastNavMesh.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.RecastNavMesh.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.RecastNavMesh.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.RecastNavMesh.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.RecastNavMesh.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.RecastNavMesh.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.RecastNavMesh.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.RecastNavMesh.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.RecastNavMesh.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.RecastNavMesh.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.RecastNavMesh.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.RecastNavMesh.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.RecastNavMesh.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.RecastNavMesh.md#receiveendplay)
- [ReceiveHit](ue_ue.RecastNavMesh.md#receivehit)
- [ReceivePointDamage](ue_ue.RecastNavMesh.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.RecastNavMesh.md#receiveradialdamage)
- [ReceiveTick](ue_ue.RecastNavMesh.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.RecastNavMesh.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.RecastNavMesh.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.RecastNavMesh.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.RecastNavMesh.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.RecastNavMesh.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.RecastNavMesh.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.RecastNavMesh.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.RecastNavMesh.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.RecastNavMesh.md#setactortickinterval)
- [SetFolderPath](ue_ue.RecastNavMesh.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.RecastNavMesh.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.RecastNavMesh.md#setlifespan)
- [SetNetDormancy](ue_ue.RecastNavMesh.md#setnetdormancy)
- [SetOwner](ue_ue.RecastNavMesh.md#setowner)
- [SetReplicateMovement](ue_ue.RecastNavMesh.md#setreplicatemovement)
- [SetReplicates](ue_ue.RecastNavMesh.md#setreplicates)
- [SetTickGroup](ue_ue.RecastNavMesh.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.RecastNavMesh.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.RecastNavMesh.md#snaprootcomponentto)
- [TearOff](ue_ue.RecastNavMesh.md#tearoff)
- [UserConstructionScript](ue_ue.RecastNavMesh.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.RecastNavMesh.md#wasrecentlyrendered)
- [Find](ue_ue.RecastNavMesh.md#find)
- [Load](ue_ue.RecastNavMesh.md#load)
- [StaticClass](ue_ue.RecastNavMesh.md#staticclass)

## Constructors

### constructor

• **new RecastNavMesh**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[NavigationData](ue_ue.NavigationData.md).[constructor](ue_ue.NavigationData.md#constructor)

#### Defined in

[ue/ue.d.ts:59113](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59113)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ActorLabel](ue_ue.NavigationData.md#actorlabel)

#### Defined in

[ue/ue.d.ts:13176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13176)

___

### AgentHeight

• **AgentHeight**: `number`

#### Defined in

[ue/ue.d.ts:59139](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59139)

___

### AgentMaxHeight

• **AgentMaxHeight**: `number`

#### Defined in

[ue/ue.d.ts:59140](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59140)

___

### AgentMaxSlope

• **AgentMaxSlope**: `number`

#### Defined in

[ue/ue.d.ts:59141](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59141)

___

### AgentMaxStepHeight

• **AgentMaxStepHeight**: `number`

#### Defined in

[ue/ue.d.ts:59142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59142)

___

### AgentRadius

• **AgentRadius**: `number`

#### Defined in

[ue/ue.d.ts:59138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59138)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[AttachmentReplication](ue_ue.NavigationData.md#attachmentreplication)

#### Defined in

[ue/ue.d.ts:13151](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13151)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[AutoReceiveInput](ue_ue.NavigationData.md#autoreceiveinput)

#### Defined in

[ue/ue.d.ts:13157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13157)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[BlueprintCreatedComponents](ue_ue.NavigationData.md#blueprintcreatedcomponents)

#### Defined in

[ue/ue.d.ts:13206](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13206)

___

### CellHeight

• **CellHeight**: `number`

#### Defined in

[ue/ue.d.ts:59137](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59137)

___

### CellSize

• **CellSize**: `number`

#### Defined in

[ue/ue.d.ts:59136](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59136)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[Children](ue_ue.NavigationData.md#children)

#### Defined in

[ue/ue.d.ts:13166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13166)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ControllingMatineeActors](ue_ue.NavigationData.md#controllingmatineeactors)

#### Defined in

[ue/ue.d.ts:13169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13169)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[CustomTimeDilation](ue_ue.NavigationData.md#customtimedilation)

#### Defined in

[ue/ue.d.ts:13150](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13150)

___

### DataVersion

• **DataVersion**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[DataVersion](ue_ue.NavigationData.md#dataversion)

#### Defined in

[ue/ue.d.ts:13394](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13394)

___

### DefaultDrawDistance

• **DefaultDrawDistance**: `number`

#### Defined in

[ue/ue.d.ts:59152](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59152)

___

### DefaultMaxHierarchicalSearchNodes

• **DefaultMaxHierarchicalSearchNodes**: `number`

#### Defined in

[ue/ue.d.ts:59154](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59154)

___

### DefaultMaxSearchNodes

• **DefaultMaxSearchNodes**: `number`

#### Defined in

[ue/ue.d.ts:59153](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59153)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.NavigationData.md#defaultupdateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13146](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13146)

___

### DrawOffset

• **DrawOffset**: `number`

#### Defined in

[ue/ue.d.ts:59132](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59132)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[FolderPath](ue_ue.NavigationData.md#folderpath)

#### Defined in

[ue/ue.d.ts:13177](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13177)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GroupActor](ue_ue.NavigationData.md#groupactor)

#### Defined in

[ue/ue.d.ts:13173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13173)

___

### HeuristicScale

• **HeuristicScale**: `number`

#### Defined in

[ue/ue.d.ts:59171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59171)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[HiddenEditorViews](ue_ue.NavigationData.md#hiddeneditorviews)

#### Defined in

[ue/ue.d.ts:13175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13175)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[InitialLifeSpan](ue_ue.NavigationData.md#initiallifespan)

#### Defined in

[ue/ue.d.ts:13149](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13149)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[InputComponent](ue_ue.NavigationData.md#inputcomponent)

#### Defined in

[ue/ue.d.ts:13159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13159)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[InputPriority](ue_ue.NavigationData.md#inputpriority)

#### Defined in

[ue/ue.d.ts:13158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13158)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[InstanceComponents](ue_ue.NavigationData.md#instancecomponents)

#### Defined in

[ue/ue.d.ts:13205](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13205)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[Instigator](ue_ue.NavigationData.md#instigator)

#### Defined in

[ue/ue.d.ts:13165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13165)

___

### LayerChunkSplits

• **LayerChunkSplits**: `number`

#### Defined in

[ue/ue.d.ts:59158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59158)

___

### LayerPartitioning

• **LayerPartitioning**: [`ERecastPartitioning`](../enums/ue_ue.ERecastPartitioning.md)

#### Defined in

[ue/ue.d.ts:59156](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59156)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[Layers](ue_ue.NavigationData.md#layers)

#### Defined in

[ue/ue.d.ts:13170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13170)

___

### MaxSimplificationError

• **MaxSimplificationError**: `number`

#### Defined in

[ue/ue.d.ts:59145](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59145)

___

### MaxSimultaneousTileGenerationJobsCount

• **MaxSimultaneousTileGenerationJobsCount**: `number`

#### Defined in

[ue/ue.d.ts:59146](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59146)

___

### MergeRegionSize

• **MergeRegionSize**: `number`

#### Defined in

[ue/ue.d.ts:59144](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59144)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[MinNetUpdateFrequency](ue_ue.NavigationData.md#minnetupdatefrequency)

#### Defined in

[ue/ue.d.ts:13163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13163)

___

### MinRegionArea

• **MinRegionArea**: `number`

#### Defined in

[ue/ue.d.ts:59143](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59143)

___

### NavDataConfig

• **NavDataConfig**: [`NavDataConfig`](ue_ue.NavDataConfig.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[NavDataConfig](ue_ue.NavigationData.md#navdataconfig)

#### Defined in

[ue/ue.d.ts:13385](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13385)

___

### NavMeshOriginOffset

• **NavMeshOriginOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:59151](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59151)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[NetCullDistanceSquared](ue_ue.NavigationData.md#netculldistancesquared)

#### Defined in

[ue/ue.d.ts:13160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13160)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[NetDormancy](ue_ue.NavigationData.md#netdormancy)

#### Defined in

[ue/ue.d.ts:13155](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13155)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[NetDriverName](ue_ue.NavigationData.md#netdrivername)

#### Defined in

[ue/ue.d.ts:13153](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13153)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[NetPriority](ue_ue.NavigationData.md#netpriority)

#### Defined in

[ue/ue.d.ts:13164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13164)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[NetTag](ue_ue.NavigationData.md#nettag)

#### Defined in

[ue/ue.d.ts:13161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13161)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[NetUpdateFrequency](ue_ue.NavigationData.md#netupdatefrequency)

#### Defined in

[ue/ue.d.ts:13162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13162)

___

### ObservedPathsTickInterval

• **ObservedPathsTickInterval**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ObservedPathsTickInterval](ue_ue.NavigationData.md#observedpathstickinterval)

#### Defined in

[ue/ue.d.ts:13393](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13393)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnActorBeginOverlap](ue_ue.NavigationData.md#onactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13192](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13192)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnActorEndOverlap](ue_ue.NavigationData.md#onactorendoverlap)

#### Defined in

[ue/ue.d.ts:13193](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13193)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnActorHit](ue_ue.NavigationData.md#onactorhit)

#### Defined in

[ue/ue.d.ts:13202](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13202)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnBeginCursorOver](ue_ue.NavigationData.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:13194](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13194)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnClicked](ue_ue.NavigationData.md#onclicked)

#### Defined in

[ue/ue.d.ts:13196](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13196)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnDestroyed](ue_ue.NavigationData.md#ondestroyed)

#### Defined in

[ue/ue.d.ts:13203](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13203)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnEndCursorOver](ue_ue.NavigationData.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:13195](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13195)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnEndPlay](ue_ue.NavigationData.md#onendplay)

#### Defined in

[ue/ue.d.ts:13204](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13204)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnInputTouchBegin](ue_ue.NavigationData.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13198](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13198)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnInputTouchEnd](ue_ue.NavigationData.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:13199](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13199)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnInputTouchEnter](ue_ue.NavigationData.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:13200](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13200)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnInputTouchLeave](ue_ue.NavigationData.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:13201](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13201)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnReleased](ue_ue.NavigationData.md#onreleased)

#### Defined in

[ue/ue.d.ts:13197](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13197)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnTakeAnyDamage](ue_ue.NavigationData.md#ontakeanydamage)

#### Defined in

[ue/ue.d.ts:13189](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13189)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnTakePointDamage](ue_ue.NavigationData.md#ontakepointdamage)

#### Defined in

[ue/ue.d.ts:13190](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13190)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnTakeRadialDamage](ue_ue.NavigationData.md#ontakeradialdamage)

#### Defined in

[ue/ue.d.ts:13191](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13191)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[Owner](ue_ue.NavigationData.md#owner)

#### Defined in

[ue/ue.d.ts:13152](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13152)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ParentComponent](ue_ue.NavigationData.md#parentcomponent)

#### Defined in

[ue/ue.d.ts:13172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13172)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ParentComponentActor](ue_ue.NavigationData.md#parentcomponentactor)

#### Defined in

[ue/ue.d.ts:13171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13171)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[PivotOffset](ue_ue.NavigationData.md#pivotoffset)

#### Defined in

[ue/ue.d.ts:13168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13168)

___

### PolyRefNavPolyBits

• **PolyRefNavPolyBits**: `number`

#### Defined in

[ue/ue.d.ts:59149](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59149)

___

### PolyRefSaltBits

• **PolyRefSaltBits**: `number`

#### Defined in

[ue/ue.d.ts:59150](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59150)

___

### PolyRefTileBits

• **PolyRefTileBits**: `number`

#### Defined in

[ue/ue.d.ts:59148](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59148)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[PrimaryActorTick](ue_ue.NavigationData.md#primaryactortick)

#### Defined in

[ue/ue.d.ts:13115](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13115)

___

### RegionChunkSplits

• **RegionChunkSplits**: `number`

#### Defined in

[ue/ue.d.ts:59157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59157)

___

### RegionPartitioning

• **RegionPartitioning**: [`ERecastPartitioning`](../enums/ue_ue.ERecastPartitioning.md)

#### Defined in

[ue/ue.d.ts:59155](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59155)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[RemoteRole](ue_ue.NavigationData.md#remoterole)

#### Defined in

[ue/ue.d.ts:13147](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13147)

___

### RenderingComp

• **RenderingComp**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[RenderingComp](ue_ue.NavigationData.md#renderingcomp)

#### Defined in

[ue/ue.d.ts:13384](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13384)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ReplicatedMovement](ue_ue.NavigationData.md#replicatedmovement)

#### Defined in

[ue/ue.d.ts:13148](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13148)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[Role](ue_ue.NavigationData.md#role)

#### Defined in

[ue/ue.d.ts:13154](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13154)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[RootComponent](ue_ue.NavigationData.md#rootcomponent)

#### Defined in

[ue/ue.d.ts:13167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13167)

___

### RuntimeGeneration

• **RuntimeGeneration**: [`ERuntimeGenerationType`](../enums/ue_ue.ERuntimeGenerationType.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[RuntimeGeneration](ue_ue.NavigationData.md#runtimegeneration)

#### Defined in

[ue/ue.d.ts:13392](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13392)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[SpawnCollisionHandlingMethod](ue_ue.NavigationData.md#spawncollisionhandlingmethod)

#### Defined in

[ue/ue.d.ts:13156](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13156)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[SpriteScale](ue_ue.NavigationData.md#spritescale)

#### Defined in

[ue/ue.d.ts:13174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13174)

___

### SupportedAreas

• **SupportedAreas**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SupportedAreaData`](ue_ue.SupportedAreaData.md)\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[SupportedAreas](ue_ue.NavigationData.md#supportedareas)

#### Defined in

[ue/ue.d.ts:13395](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13395)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[Tags](ue_ue.NavigationData.md#tags)

#### Defined in

[ue/ue.d.ts:13188](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13188)

___

### TileNumberHardLimit

• **TileNumberHardLimit**: `number`

#### Defined in

[ue/ue.d.ts:59147](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59147)

___

### TilePoolSize

• **TilePoolSize**: `number`

#### Defined in

[ue/ue.d.ts:59134](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59134)

___

### TileSetUpdateInterval

• **TileSetUpdateInterval**: `number`

#### Defined in

[ue/ue.d.ts:59170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59170)

___

### TileSizeUU

• **TileSizeUU**: `number`

#### Defined in

[ue/ue.d.ts:59135](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59135)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.NavigationData.md#updateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13145](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13145)

___

### VerticalDeviationFromGroundCompensation

• **VerticalDeviationFromGroundCompensation**: `number`

#### Defined in

[ue/ue.d.ts:59172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59172)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[__tid_Actor__](ue_ue.NavigationData.md#__tid_actor__)

#### Defined in

[ue/ue.d.ts:13348](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13348)

___

### \_\_tid\_NavigationData\_\_

• **\_\_tid\_NavigationData\_\_**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[__tid_NavigationData__](ue_ue.NavigationData.md#__tid_navigationdata__)

#### Defined in

[ue/ue.d.ts:13400](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13400)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[__tid_Object__](ue_ue.NavigationData.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_RecastNavMesh\_\_

• **\_\_tid\_RecastNavMesh\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:59178](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59178)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bActorEnableCollision](ue_ue.NavigationData.md#bactorenablecollision)

#### Defined in

[ue/ue.d.ts:13143](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13143)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bActorIsBeingDestroyed](ue_ue.NavigationData.md#bactorisbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13144](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13144)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bActorLabelEditable](ue_ue.NavigationData.md#bactorlabeleditable)

#### Defined in

[ue/ue.d.ts:13183](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13183)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bActorSeamlessTraveled](ue_ue.NavigationData.md#bactorseamlesstraveled)

#### Defined in

[ue/ue.d.ts:13139](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13139)

___

### bAllowNavLinkAsPathEnd

• **bAllowNavLinkAsPathEnd**: `boolean`

#### Defined in

[ue/ue.d.ts:59168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59168)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.NavigationData.md#ballowreceivetickeventondedicatedserver)

#### Defined in

[ue/ue.d.ts:13142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13142)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bAllowTickBeforeBeginPlay](ue_ue.NavigationData.md#ballowtickbeforebeginplay)

#### Defined in

[ue/ue.d.ts:13129](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13129)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bAlwaysRelevant](ue_ue.NavigationData.md#balwaysrelevant)

#### Defined in

[ue/ue.d.ts:13120](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13120)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bAutoDestroyWhenFinished](ue_ue.NavigationData.md#bautodestroywhenfinished)

#### Defined in

[ue/ue.d.ts:13130](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13130)

___

### bAutoDestroyWhenNoNavigation

• **bAutoDestroyWhenNoNavigation**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bAutoDestroyWhenNoNavigation](ue_ue.NavigationData.md#bautodestroywhennonavigation)

#### Defined in

[ue/ue.d.ts:13388](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13388)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bBlockInput](ue_ue.NavigationData.md#bblockinput)

#### Defined in

[ue/ue.d.ts:13131](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13131)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bCanBeDamaged](ue_ue.NavigationData.md#bcanbedamaged)

#### Defined in

[ue/ue.d.ts:13132](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13132)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bCanBeInCluster](ue_ue.NavigationData.md#bcanbeincluster)

#### Defined in

[ue/ue.d.ts:13141](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13141)

___

### bCanBeMainNavData

• **bCanBeMainNavData**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bCanBeMainNavData](ue_ue.NavigationData.md#bcanbemainnavdata)

#### Defined in

[ue/ue.d.ts:13389](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13389)

___

### bCanSpawnOnRebuild

• **bCanSpawnOnRebuild**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bCanSpawnOnRebuild](ue_ue.NavigationData.md#bcanspawnonrebuild)

#### Defined in

[ue/ue.d.ts:13390](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13390)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bCollideWhenPlacing](ue_ue.NavigationData.md#bcollidewhenplacing)

#### Defined in

[ue/ue.d.ts:13133](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13133)

___

### bDistinctlyDrawTilesBeingBuilt

• **bDistinctlyDrawTilesBeingBuilt**: `boolean`

#### Defined in

[ue/ue.d.ts:59130](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59130)

___

### bDoFullyAsyncNavDataGathering

• **bDoFullyAsyncNavDataGathering**: `boolean`

#### Defined in

[ue/ue.d.ts:59164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59164)

___

### bDrawClusters

• **bDrawClusters**: `boolean`

#### Defined in

[ue/ue.d.ts:59126](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59126)

___

### bDrawDefaultPolygonCost

• **bDrawDefaultPolygonCost**: `boolean`

#### Defined in

[ue/ue.d.ts:59122](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59122)

___

### bDrawFailedNavLinks

• **bDrawFailedNavLinks**: `boolean`

#### Defined in

[ue/ue.d.ts:59125](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59125)

___

### bDrawFilledPolys

• **bDrawFilledPolys**: `boolean`

#### Defined in

[ue/ue.d.ts:59116](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59116)

___

### bDrawLabelsOnPathNodes

• **bDrawLabelsOnPathNodes**: `boolean`

#### Defined in

[ue/ue.d.ts:59123](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59123)

___

### bDrawMarkedForbiddenPolys

• **bDrawMarkedForbiddenPolys**: `boolean`

#### Defined in

[ue/ue.d.ts:59129](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59129)

___

### bDrawNavLinks

• **bDrawNavLinks**: `boolean`

#### Defined in

[ue/ue.d.ts:59124](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59124)

___

### bDrawNavMesh

• **bDrawNavMesh**: `boolean`

#### Defined in

[ue/ue.d.ts:59131](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59131)

___

### bDrawNavMeshEdges

• **bDrawNavMeshEdges**: `boolean`

#### Defined in

[ue/ue.d.ts:59117](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59117)

___

### bDrawOctree

• **bDrawOctree**: `boolean`

#### Defined in

[ue/ue.d.ts:59127](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59127)

___

### bDrawOctreeDetails

• **bDrawOctreeDetails**: `boolean`

#### Defined in

[ue/ue.d.ts:59128](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59128)

___

### bDrawPathCollidingGeometry

• **bDrawPathCollidingGeometry**: `boolean`

#### Defined in

[ue/ue.d.ts:59119](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59119)

___

### bDrawPolyEdges

• **bDrawPolyEdges**: `boolean`

#### Defined in

[ue/ue.d.ts:59115](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59115)

___

### bDrawPolygonLabels

• **bDrawPolygonLabels**: `boolean`

#### Defined in

[ue/ue.d.ts:59121](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59121)

___

### bDrawTileBounds

• **bDrawTileBounds**: `boolean`

#### Defined in

[ue/ue.d.ts:59118](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59118)

___

### bDrawTileLabels

• **bDrawTileLabels**: `boolean`

#### Defined in

[ue/ue.d.ts:59120](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59120)

___

### bDrawTriangleEdges

• **bDrawTriangleEdges**: `boolean`

#### Defined in

[ue/ue.d.ts:59114](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59114)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bEditable](ue_ue.NavigationData.md#beditable)

#### Defined in

[ue/ue.d.ts:13184](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13184)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bEnableAutoLODGeneration](ue_ue.NavigationData.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:13137](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13137)

___

### bEnableDrawing

• **bEnableDrawing**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bEnableDrawing](ue_ue.NavigationData.md#benabledrawing)

#### Defined in

[ue/ue.d.ts:13386](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13386)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bExchangedRoles](ue_ue.NavigationData.md#bexchangedroles)

#### Defined in

[ue/ue.d.ts:13123](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13123)

___

### bFilterLowSpanFromTileCache

• **bFilterLowSpanFromTileCache**: `boolean`

#### Defined in

[ue/ue.d.ts:59163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59163)

___

### bFilterLowSpanSequences

• **bFilterLowSpanSequences**: `boolean`

#### Defined in

[ue/ue.d.ts:59162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59162)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bFindCameraComponentWhenViewTarget](ue_ue.NavigationData.md#bfindcameracomponentwhenviewtarget)

#### Defined in

[ue/ue.d.ts:13134](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13134)

___

### bFixedTilePoolSize

• **bFixedTilePoolSize**: `boolean`

#### Defined in

[ue/ue.d.ts:59133](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59133)

___

### bForceRebuildOnLoad

• **bForceRebuildOnLoad**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bForceRebuildOnLoad](ue_ue.NavigationData.md#bforcerebuildonload)

#### Defined in

[ue/ue.d.ts:13387](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13387)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.NavigationData.md#bgenerateoverlapeventsduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13135](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13135)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bHidden](ue_ue.NavigationData.md#bhidden)

#### Defined in

[ue/ue.d.ts:13116](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13116)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bHiddenEd](ue_ue.NavigationData.md#bhiddened)

#### Defined in

[ue/ue.d.ts:13178](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13178)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bHiddenEdLayer](ue_ue.NavigationData.md#bhiddenedlayer)

#### Defined in

[ue/ue.d.ts:13180](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13180)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bHiddenEdLevel](ue_ue.NavigationData.md#bhiddenedlevel)

#### Defined in

[ue/ue.d.ts:13181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13181)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bHiddenEdTemporary](ue_ue.NavigationData.md#bhiddenedtemporary)

#### Defined in

[ue/ue.d.ts:13187](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13187)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bIgnoresOriginShifting](ue_ue.NavigationData.md#bignoresoriginshifting)

#### Defined in

[ue/ue.d.ts:13136](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13136)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bIsEditorOnlyActor](ue_ue.NavigationData.md#biseditoronlyactor)

#### Defined in

[ue/ue.d.ts:13138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13138)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bIsEditorPreviewActor](ue_ue.NavigationData.md#biseditorpreviewactor)

#### Defined in

[ue/ue.d.ts:13179](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13179)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bListedInSceneOutliner](ue_ue.NavigationData.md#blistedinsceneoutliner)

#### Defined in

[ue/ue.d.ts:13185](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13185)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bLockLocation](ue_ue.NavigationData.md#blocklocation)

#### Defined in

[ue/ue.d.ts:13182](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13182)

___

### bMarkLowHeightAreas

• **bMarkLowHeightAreas**: `boolean`

#### Defined in

[ue/ue.d.ts:59161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59161)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bNetLoadOnClient](ue_ue.NavigationData.md#bnetloadonclient)

#### Defined in

[ue/ue.d.ts:13124](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13124)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bNetStartup](ue_ue.NavigationData.md#bnetstartup)

#### Defined in

[ue/ue.d.ts:13118](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13118)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bNetTemporary](ue_ue.NavigationData.md#bnettemporary)

#### Defined in

[ue/ue.d.ts:13117](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13117)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bNetUseOwnerRelevancy](ue_ue.NavigationData.md#bnetuseownerrelevancy)

#### Defined in

[ue/ue.d.ts:13125](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13125)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bOnlyRelevantToOwner](ue_ue.NavigationData.md#bonlyrelevanttoowner)

#### Defined in

[ue/ue.d.ts:13119](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13119)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bOptimizeBPComponentData](ue_ue.NavigationData.md#boptimizebpcomponentdata)

#### Defined in

[ue/ue.d.ts:13186](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13186)

___

### bPerformVoxelFiltering

• **bPerformVoxelFiltering**: `boolean`

#### Defined in

[ue/ue.d.ts:59160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59160)

___

### bRebuildAtRuntime

• **bRebuildAtRuntime**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bRebuildAtRuntime](ue_ue.NavigationData.md#brebuildatruntime)

#### Defined in

[ue/ue.d.ts:13391](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13391)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bRelevantForLevelBounds](ue_ue.NavigationData.md#brelevantforlevelbounds)

#### Defined in

[ue/ue.d.ts:13127](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13127)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bRelevantForNetworkReplays](ue_ue.NavigationData.md#brelevantfornetworkreplays)

#### Defined in

[ue/ue.d.ts:13126](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13126)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bReplayRewindable](ue_ue.NavigationData.md#breplayrewindable)

#### Defined in

[ue/ue.d.ts:13128](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13128)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bReplicateMovement](ue_ue.NavigationData.md#breplicatemovement)

#### Defined in

[ue/ue.d.ts:13121](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13121)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bReplicates](ue_ue.NavigationData.md#breplicates)

#### Defined in

[ue/ue.d.ts:13140](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13140)

___

### bSortNavigationAreasByCost

• **bSortNavigationAreasByCost**: `boolean`

#### Defined in

[ue/ue.d.ts:59159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59159)

___

### bStoreEmptyTileLayers

• **bStoreEmptyTileLayers**: `boolean`

#### Defined in

[ue/ue.d.ts:59166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59166)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bTearOff](ue_ue.NavigationData.md#btearoff)

#### Defined in

[ue/ue.d.ts:13122](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13122)

___

### bUseBetterOffsetsFromCorners

• **bUseBetterOffsetsFromCorners**: `boolean`

#### Defined in

[ue/ue.d.ts:59165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59165)

___

### bUseVirtualFilters

• **bUseVirtualFilters**: `boolean`

#### Defined in

[ue/ue.d.ts:59167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59167)

___

### bUseVoxelCache

• **bUseVoxelCache**: `boolean`

#### Defined in

[ue/ue.d.ts:59169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59169)

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

[NavigationData](ue_ue.NavigationData.md).[ActorHasTag](ue_ue.NavigationData.md#actorhastag)

#### Defined in

[ue/ue.d.ts:13207](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13207)

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

[NavigationData](ue_ue.NavigationData.md).[AddComponent](ue_ue.NavigationData.md#addcomponent)

#### Defined in

[ue/ue.d.ts:13208](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13208)

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

[NavigationData](ue_ue.NavigationData.md).[AddTickPrerequisiteActor](ue_ue.NavigationData.md#addtickprerequisiteactor)

#### Defined in

[ue/ue.d.ts:13209](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13209)

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

[NavigationData](ue_ue.NavigationData.md).[AddTickPrerequisiteComponent](ue_ue.NavigationData.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13210](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13210)

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

[NavigationData](ue_ue.NavigationData.md).[CreateDefaultSubobject](ue_ue.NavigationData.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[NavigationData](ue_ue.NavigationData.md).[DetachRootComponentFromParent](ue_ue.NavigationData.md#detachrootcomponentfromparent)

#### Defined in

[ue/ue.d.ts:13211](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13211)

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

[NavigationData](ue_ue.NavigationData.md).[DisableInput](ue_ue.NavigationData.md#disableinput)

#### Defined in

[ue/ue.d.ts:13212](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13212)

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

[NavigationData](ue_ue.NavigationData.md).[EnableInput](ue_ue.NavigationData.md#enableinput)

#### Defined in

[ue/ue.d.ts:13213](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13213)

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

[NavigationData](ue_ue.NavigationData.md).[ExecuteUbergraph](ue_ue.NavigationData.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[FlushNetDormancy](ue_ue.NavigationData.md#flushnetdormancy)

#### Defined in

[ue/ue.d.ts:13214](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13214)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ForceNetUpdate](ue_ue.NavigationData.md#forcenetupdate)

#### Defined in

[ue/ue.d.ts:13215](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13215)

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

[NavigationData](ue_ue.NavigationData.md).[GetActorBounds](ue_ue.NavigationData.md#getactorbounds)

#### Defined in

[ue/ue.d.ts:13216](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13216)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorEnableCollision](ue_ue.NavigationData.md#getactorenablecollision)

#### Defined in

[ue/ue.d.ts:13217](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13217)

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

[NavigationData](ue_ue.NavigationData.md).[GetActorEyesViewPoint](ue_ue.NavigationData.md#getactoreyesviewpoint)

#### Defined in

[ue/ue.d.ts:13218](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13218)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorForwardVector](ue_ue.NavigationData.md#getactorforwardvector)

#### Defined in

[ue/ue.d.ts:13219](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13219)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorLabel](ue_ue.NavigationData.md#getactorlabel)

#### Defined in

[ue/ue.d.ts:13220](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13220)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorRelativeScale3D](ue_ue.NavigationData.md#getactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13221](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13221)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorRightVector](ue_ue.NavigationData.md#getactorrightvector)

#### Defined in

[ue/ue.d.ts:13222](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13222)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorScale3D](ue_ue.NavigationData.md#getactorscale3d)

#### Defined in

[ue/ue.d.ts:13223](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13223)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorTickInterval](ue_ue.NavigationData.md#getactortickinterval)

#### Defined in

[ue/ue.d.ts:13224](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13224)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorTimeDilation](ue_ue.NavigationData.md#getactortimedilation)

#### Defined in

[ue/ue.d.ts:13225](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13225)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorUpVector](ue_ue.NavigationData.md#getactorupvector)

#### Defined in

[ue/ue.d.ts:13226](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13226)

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

[NavigationData](ue_ue.NavigationData.md).[GetAllChildActors](ue_ue.NavigationData.md#getallchildactors)

#### Defined in

[ue/ue.d.ts:13227](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13227)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetAttachParentActor](ue_ue.NavigationData.md#getattachparentactor)

#### Defined in

[ue/ue.d.ts:13229](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13229)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetAttachParentSocketName](ue_ue.NavigationData.md#getattachparentsocketname)

#### Defined in

[ue/ue.d.ts:13230](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13230)

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

[NavigationData](ue_ue.NavigationData.md).[GetAttachedActors](ue_ue.NavigationData.md#getattachedactors)

#### Defined in

[ue/ue.d.ts:13228](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13228)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetClass](ue_ue.NavigationData.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

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

[NavigationData](ue_ue.NavigationData.md).[GetComponentByClass](ue_ue.NavigationData.md#getcomponentbyclass)

#### Defined in

[ue/ue.d.ts:13231](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13231)

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

[NavigationData](ue_ue.NavigationData.md).[GetComponentsByInterface](ue_ue.NavigationData.md#getcomponentsbyinterface)

#### Defined in

[ue/ue.d.ts:13232](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13232)

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

[NavigationData](ue_ue.NavigationData.md).[GetComponentsByTag](ue_ue.NavigationData.md#getcomponentsbytag)

#### Defined in

[ue/ue.d.ts:13233](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13233)

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

[NavigationData](ue_ue.NavigationData.md).[GetDistanceTo](ue_ue.NavigationData.md#getdistanceto)

#### Defined in

[ue/ue.d.ts:13234](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13234)

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

[NavigationData](ue_ue.NavigationData.md).[GetDotProductTo](ue_ue.NavigationData.md#getdotproductto)

#### Defined in

[ue/ue.d.ts:13235](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13235)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetFolderPath](ue_ue.NavigationData.md#getfolderpath)

#### Defined in

[ue/ue.d.ts:13236](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13236)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetGameTimeSinceCreation](ue_ue.NavigationData.md#getgametimesincecreation)

#### Defined in

[ue/ue.d.ts:13237](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13237)

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

[NavigationData](ue_ue.NavigationData.md).[GetHorizontalDistanceTo](ue_ue.NavigationData.md#gethorizontaldistanceto)

#### Defined in

[ue/ue.d.ts:13238](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13238)

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

[NavigationData](ue_ue.NavigationData.md).[GetHorizontalDotProductTo](ue_ue.NavigationData.md#gethorizontaldotproductto)

#### Defined in

[ue/ue.d.ts:13239](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13239)

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

[NavigationData](ue_ue.NavigationData.md).[GetInputAxisKeyValue](ue_ue.NavigationData.md#getinputaxiskeyvalue)

#### Defined in

[ue/ue.d.ts:13240](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13240)

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

[NavigationData](ue_ue.NavigationData.md).[GetInputAxisValue](ue_ue.NavigationData.md#getinputaxisvalue)

#### Defined in

[ue/ue.d.ts:13241](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13241)

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

[NavigationData](ue_ue.NavigationData.md).[GetInputVectorAxisValue](ue_ue.NavigationData.md#getinputvectoraxisvalue)

#### Defined in

[ue/ue.d.ts:13242](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13242)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetInstigator](ue_ue.NavigationData.md#getinstigator)

#### Defined in

[ue/ue.d.ts:13243](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13243)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetInstigatorController](ue_ue.NavigationData.md#getinstigatorcontroller)

#### Defined in

[ue/ue.d.ts:13244](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13244)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetLifeSpan](ue_ue.NavigationData.md#getlifespan)

#### Defined in

[ue/ue.d.ts:13245](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13245)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetLocalRole](ue_ue.NavigationData.md#getlocalrole)

#### Defined in

[ue/ue.d.ts:13246](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13246)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetName](ue_ue.NavigationData.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetOuter](ue_ue.NavigationData.md#getouter)

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

[NavigationData](ue_ue.NavigationData.md).[GetOverlappingActors](ue_ue.NavigationData.md#getoverlappingactors)

#### Defined in

[ue/ue.d.ts:13247](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13247)

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

[NavigationData](ue_ue.NavigationData.md).[GetOverlappingComponents](ue_ue.NavigationData.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:13248](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13248)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetOwner](ue_ue.NavigationData.md#getowner)

#### Defined in

[ue/ue.d.ts:13249](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13249)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetParentActor](ue_ue.NavigationData.md#getparentactor)

#### Defined in

[ue/ue.d.ts:13250](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13250)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetParentComponent](ue_ue.NavigationData.md#getparentcomponent)

#### Defined in

[ue/ue.d.ts:13251](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13251)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetRemoteRole](ue_ue.NavigationData.md#getremoterole)

#### Defined in

[ue/ue.d.ts:13252](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13252)

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

[NavigationData](ue_ue.NavigationData.md).[GetSquaredDistanceTo](ue_ue.NavigationData.md#getsquareddistanceto)

#### Defined in

[ue/ue.d.ts:13253](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13253)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetTickableWhenPaused](ue_ue.NavigationData.md#gettickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13254](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13254)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetTransform](ue_ue.NavigationData.md#gettransform)

#### Defined in

[ue/ue.d.ts:13255](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13255)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetVelocity](ue_ue.NavigationData.md#getvelocity)

#### Defined in

[ue/ue.d.ts:13256](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13256)

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

[NavigationData](ue_ue.NavigationData.md).[GetVerticalDistanceTo](ue_ue.NavigationData.md#getverticaldistanceto)

#### Defined in

[ue/ue.d.ts:13257](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13257)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetWorld](ue_ue.NavigationData.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[HasAuthority](ue_ue.NavigationData.md#hasauthority)

#### Defined in

[ue/ue.d.ts:13258](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13258)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[IsActorBeingDestroyed](ue_ue.NavigationData.md#isactorbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13259](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13259)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[IsActorTickEnabled](ue_ue.NavigationData.md#isactortickenabled)

#### Defined in

[ue/ue.d.ts:13260](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13260)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[IsChildActor](ue_ue.NavigationData.md#ischildactor)

#### Defined in

[ue/ue.d.ts:13261](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13261)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[IsEditable](ue_ue.NavigationData.md#iseditable)

#### Defined in

[ue/ue.d.ts:13262](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13262)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[IsHiddenEd](ue_ue.NavigationData.md#ishiddened)

#### Defined in

[ue/ue.d.ts:13263](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13263)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[IsHiddenEdAtStartup](ue_ue.NavigationData.md#ishiddenedatstartup)

#### Defined in

[ue/ue.d.ts:13264](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13264)

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

[NavigationData](ue_ue.NavigationData.md).[IsOverlappingActor](ue_ue.NavigationData.md#isoverlappingactor)

#### Defined in

[ue/ue.d.ts:13265](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13265)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[IsSelectable](ue_ue.NavigationData.md#isselectable)

#### Defined in

[ue/ue.d.ts:13266](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13266)

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

[NavigationData](ue_ue.NavigationData.md).[IsTemporarilyHiddenInEditor](ue_ue.NavigationData.md#istemporarilyhiddenineditor)

#### Defined in

[ue/ue.d.ts:13267](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13267)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AddActorLocalOffset](ue_ue.NavigationData.md#k2_addactorlocaloffset)

#### Defined in

[ue/ue.d.ts:13268](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13268)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AddActorLocalRotation](ue_ue.NavigationData.md#k2_addactorlocalrotation)

#### Defined in

[ue/ue.d.ts:13269](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13269)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AddActorLocalTransform](ue_ue.NavigationData.md#k2_addactorlocaltransform)

#### Defined in

[ue/ue.d.ts:13270](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13270)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AddActorWorldOffset](ue_ue.NavigationData.md#k2_addactorworldoffset)

#### Defined in

[ue/ue.d.ts:13271](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13271)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AddActorWorldRotation](ue_ue.NavigationData.md#k2_addactorworldrotation)

#### Defined in

[ue/ue.d.ts:13272](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13272)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AddActorWorldTransform](ue_ue.NavigationData.md#k2_addactorworldtransform)

#### Defined in

[ue/ue.d.ts:13273](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13273)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AttachRootComponentTo](ue_ue.NavigationData.md#k2_attachrootcomponentto)

#### Defined in

[ue/ue.d.ts:13274](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13274)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AttachRootComponentToActor](ue_ue.NavigationData.md#k2_attachrootcomponenttoactor)

#### Defined in

[ue/ue.d.ts:13275](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13275)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AttachToActor](ue_ue.NavigationData.md#k2_attachtoactor)

#### Defined in

[ue/ue.d.ts:13276](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13276)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AttachToComponent](ue_ue.NavigationData.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:13277](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13277)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[K2_DestroyActor](ue_ue.NavigationData.md#k2_destroyactor)

#### Defined in

[ue/ue.d.ts:13278](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13278)

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

[NavigationData](ue_ue.NavigationData.md).[K2_DestroyComponent](ue_ue.NavigationData.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:13279](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13279)

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

[NavigationData](ue_ue.NavigationData.md).[K2_DetachFromActor](ue_ue.NavigationData.md#k2_detachfromactor)

#### Defined in

[ue/ue.d.ts:13280](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13280)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[K2_GetActorLocation](ue_ue.NavigationData.md#k2_getactorlocation)

#### Defined in

[ue/ue.d.ts:13281](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13281)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[K2_GetActorRotation](ue_ue.NavigationData.md#k2_getactorrotation)

#### Defined in

[ue/ue.d.ts:13282](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13282)

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

[NavigationData](ue_ue.NavigationData.md).[K2_GetComponentsByClass](ue_ue.NavigationData.md#k2_getcomponentsbyclass)

#### Defined in

[ue/ue.d.ts:13283](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13283)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[K2_GetRootComponent](ue_ue.NavigationData.md#k2_getrootcomponent)

#### Defined in

[ue/ue.d.ts:13284](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13284)

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

[NavigationData](ue_ue.NavigationData.md).[K2_OnBecomeViewTarget](ue_ue.NavigationData.md#k2_onbecomeviewtarget)

#### Defined in

[ue/ue.d.ts:13285](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13285)

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

[NavigationData](ue_ue.NavigationData.md).[K2_OnEndViewTarget](ue_ue.NavigationData.md#k2_onendviewtarget)

#### Defined in

[ue/ue.d.ts:13286](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13286)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[K2_OnReset](ue_ue.NavigationData.md#k2_onreset)

#### Defined in

[ue/ue.d.ts:13287](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13287)

___

### K2\_ReplaceAreaInTileBounds

▸ **K2_ReplaceAreaInTileBounds**(`Bounds`, `OldArea`, `NewArea`, `ReplaceLinks?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Bounds` | [`Box`](ue_ue.Box.md) |
| `OldArea` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `NewArea` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `ReplaceLinks?` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:59173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59173)

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

[NavigationData](ue_ue.NavigationData.md).[K2_SetActorLocation](ue_ue.NavigationData.md#k2_setactorlocation)

#### Defined in

[ue/ue.d.ts:13288](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13288)

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

[NavigationData](ue_ue.NavigationData.md).[K2_SetActorLocationAndRotation](ue_ue.NavigationData.md#k2_setactorlocationandrotation)

#### Defined in

[ue/ue.d.ts:13289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13289)

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

[NavigationData](ue_ue.NavigationData.md).[K2_SetActorRelativeLocation](ue_ue.NavigationData.md#k2_setactorrelativelocation)

#### Defined in

[ue/ue.d.ts:13290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13290)

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

[NavigationData](ue_ue.NavigationData.md).[K2_SetActorRelativeRotation](ue_ue.NavigationData.md#k2_setactorrelativerotation)

#### Defined in

[ue/ue.d.ts:13291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13291)

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

[NavigationData](ue_ue.NavigationData.md).[K2_SetActorRelativeTransform](ue_ue.NavigationData.md#k2_setactorrelativetransform)

#### Defined in

[ue/ue.d.ts:13292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13292)

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

[NavigationData](ue_ue.NavigationData.md).[K2_SetActorRotation](ue_ue.NavigationData.md#k2_setactorrotation)

#### Defined in

[ue/ue.d.ts:13293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13293)

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

[NavigationData](ue_ue.NavigationData.md).[K2_SetActorTransform](ue_ue.NavigationData.md#k2_setactortransform)

#### Defined in

[ue/ue.d.ts:13294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13294)

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

[NavigationData](ue_ue.NavigationData.md).[K2_TeleportTo](ue_ue.NavigationData.md#k2_teleportto)

#### Defined in

[ue/ue.d.ts:13295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13295)

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

[NavigationData](ue_ue.NavigationData.md).[MakeMIDForMaterial](ue_ue.NavigationData.md#makemidformaterial)

#### Defined in

[ue/ue.d.ts:13296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13296)

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

[NavigationData](ue_ue.NavigationData.md).[MakeNoise](ue_ue.NavigationData.md#makenoise)

#### Defined in

[ue/ue.d.ts:13297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13297)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnRep_AttachmentReplication](ue_ue.NavigationData.md#onrep_attachmentreplication)

#### Defined in

[ue/ue.d.ts:13298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13298)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnRep_Instigator](ue_ue.NavigationData.md#onrep_instigator)

#### Defined in

[ue/ue.d.ts:13299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13299)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnRep_Owner](ue_ue.NavigationData.md#onrep_owner)

#### Defined in

[ue/ue.d.ts:13300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13300)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnRep_ReplicateMovement](ue_ue.NavigationData.md#onrep_replicatemovement)

#### Defined in

[ue/ue.d.ts:13302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13302)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnRep_ReplicatedMovement](ue_ue.NavigationData.md#onrep_replicatedmovement)

#### Defined in

[ue/ue.d.ts:13301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13301)

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

[NavigationData](ue_ue.NavigationData.md).[PrestreamTextures](ue_ue.NavigationData.md#prestreamtextures)

#### Defined in

[ue/ue.d.ts:13303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13303)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorBeginCursorOver](ue_ue.NavigationData.md#receiveactorbegincursorover)

#### Defined in

[ue/ue.d.ts:13304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13304)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorBeginOverlap](ue_ue.NavigationData.md#receiveactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13305)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorEndCursorOver](ue_ue.NavigationData.md#receiveactorendcursorover)

#### Defined in

[ue/ue.d.ts:13306](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13306)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorEndOverlap](ue_ue.NavigationData.md#receiveactorendoverlap)

#### Defined in

[ue/ue.d.ts:13307](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13307)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorOnClicked](ue_ue.NavigationData.md#receiveactoronclicked)

#### Defined in

[ue/ue.d.ts:13308](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13308)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorOnInputTouchBegin](ue_ue.NavigationData.md#receiveactoroninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13309](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13309)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorOnInputTouchEnd](ue_ue.NavigationData.md#receiveactoroninputtouchend)

#### Defined in

[ue/ue.d.ts:13310](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13310)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorOnInputTouchEnter](ue_ue.NavigationData.md#receiveactoroninputtouchenter)

#### Defined in

[ue/ue.d.ts:13311](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13311)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorOnInputTouchLeave](ue_ue.NavigationData.md#receiveactoroninputtouchleave)

#### Defined in

[ue/ue.d.ts:13312](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13312)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorOnReleased](ue_ue.NavigationData.md#receiveactoronreleased)

#### Defined in

[ue/ue.d.ts:13313](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13313)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveAnyDamage](ue_ue.NavigationData.md#receiveanydamage)

#### Defined in

[ue/ue.d.ts:13314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13314)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ReceiveBeginPlay](ue_ue.NavigationData.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:13315](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13315)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ReceiveDestroyed](ue_ue.NavigationData.md#receivedestroyed)

#### Defined in

[ue/ue.d.ts:13316](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13316)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveEndPlay](ue_ue.NavigationData.md#receiveendplay)

#### Defined in

[ue/ue.d.ts:13317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13317)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveHit](ue_ue.NavigationData.md#receivehit)

#### Defined in

[ue/ue.d.ts:13318](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13318)

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

[NavigationData](ue_ue.NavigationData.md).[ReceivePointDamage](ue_ue.NavigationData.md#receivepointdamage)

#### Defined in

[ue/ue.d.ts:13319](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13319)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveRadialDamage](ue_ue.NavigationData.md#receiveradialdamage)

#### Defined in

[ue/ue.d.ts:13320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13320)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveTick](ue_ue.NavigationData.md#receivetick)

#### Defined in

[ue/ue.d.ts:13321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13321)

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

[NavigationData](ue_ue.NavigationData.md).[RemoveTickPrerequisiteActor](ue_ue.NavigationData.md#removetickprerequisiteactor)

#### Defined in

[ue/ue.d.ts:13322](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13322)

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

[NavigationData](ue_ue.NavigationData.md).[RemoveTickPrerequisiteComponent](ue_ue.NavigationData.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13323)

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

[NavigationData](ue_ue.NavigationData.md).[SetActorEnableCollision](ue_ue.NavigationData.md#setactorenablecollision)

#### Defined in

[ue/ue.d.ts:13324](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13324)

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

[NavigationData](ue_ue.NavigationData.md).[SetActorHiddenInGame](ue_ue.NavigationData.md#setactorhiddeningame)

#### Defined in

[ue/ue.d.ts:13325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13325)

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

[NavigationData](ue_ue.NavigationData.md).[SetActorLabel](ue_ue.NavigationData.md#setactorlabel)

#### Defined in

[ue/ue.d.ts:13326](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13326)

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

[NavigationData](ue_ue.NavigationData.md).[SetActorRelativeScale3D](ue_ue.NavigationData.md#setactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13327)

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

[NavigationData](ue_ue.NavigationData.md).[SetActorScale3D](ue_ue.NavigationData.md#setactorscale3d)

#### Defined in

[ue/ue.d.ts:13328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13328)

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

[NavigationData](ue_ue.NavigationData.md).[SetActorTickEnabled](ue_ue.NavigationData.md#setactortickenabled)

#### Defined in

[ue/ue.d.ts:13329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13329)

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

[NavigationData](ue_ue.NavigationData.md).[SetActorTickInterval](ue_ue.NavigationData.md#setactortickinterval)

#### Defined in

[ue/ue.d.ts:13330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13330)

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

[NavigationData](ue_ue.NavigationData.md).[SetFolderPath](ue_ue.NavigationData.md#setfolderpath)

#### Defined in

[ue/ue.d.ts:13331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13331)

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

[NavigationData](ue_ue.NavigationData.md).[SetIsTemporarilyHiddenInEditor](ue_ue.NavigationData.md#setistemporarilyhiddenineditor)

#### Defined in

[ue/ue.d.ts:13332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13332)

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

[NavigationData](ue_ue.NavigationData.md).[SetLifeSpan](ue_ue.NavigationData.md#setlifespan)

#### Defined in

[ue/ue.d.ts:13333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13333)

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

[NavigationData](ue_ue.NavigationData.md).[SetNetDormancy](ue_ue.NavigationData.md#setnetdormancy)

#### Defined in

[ue/ue.d.ts:13334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13334)

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

[NavigationData](ue_ue.NavigationData.md).[SetOwner](ue_ue.NavigationData.md#setowner)

#### Defined in

[ue/ue.d.ts:13335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13335)

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

[NavigationData](ue_ue.NavigationData.md).[SetReplicateMovement](ue_ue.NavigationData.md#setreplicatemovement)

#### Defined in

[ue/ue.d.ts:13336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13336)

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

[NavigationData](ue_ue.NavigationData.md).[SetReplicates](ue_ue.NavigationData.md#setreplicates)

#### Defined in

[ue/ue.d.ts:13337](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13337)

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

[NavigationData](ue_ue.NavigationData.md).[SetTickGroup](ue_ue.NavigationData.md#settickgroup)

#### Defined in

[ue/ue.d.ts:13339](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13339)

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

[NavigationData](ue_ue.NavigationData.md).[SetTickableWhenPaused](ue_ue.NavigationData.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13338)

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

[NavigationData](ue_ue.NavigationData.md).[SnapRootComponentTo](ue_ue.NavigationData.md#snaprootcomponentto)

#### Defined in

[ue/ue.d.ts:13340](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13340)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[TearOff](ue_ue.NavigationData.md#tearoff)

#### Defined in

[ue/ue.d.ts:13341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13341)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[UserConstructionScript](ue_ue.NavigationData.md#userconstructionscript)

#### Defined in

[ue/ue.d.ts:13342](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13342)

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

[NavigationData](ue_ue.NavigationData.md).[WasRecentlyRendered](ue_ue.NavigationData.md#wasrecentlyrendered)

#### Defined in

[ue/ue.d.ts:13343](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13343)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`RecastNavMesh`](ue_ue.RecastNavMesh.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`RecastNavMesh`](ue_ue.RecastNavMesh.md)

#### Overrides

[NavigationData](ue_ue.NavigationData.md).[Find](ue_ue.NavigationData.md#find)

#### Defined in

[ue/ue.d.ts:59175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59175)

___

### Load

▸ `Static` **Load**(`InName`): [`RecastNavMesh`](ue_ue.RecastNavMesh.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`RecastNavMesh`](ue_ue.RecastNavMesh.md)

#### Overrides

[NavigationData](ue_ue.NavigationData.md).[Load](ue_ue.NavigationData.md#load)

#### Defined in

[ue/ue.d.ts:59176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59176)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[NavigationData](ue_ue.NavigationData.md).[StaticClass](ue_ue.NavigationData.md#staticclass)

#### Defined in

[ue/ue.d.ts:59174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59174)