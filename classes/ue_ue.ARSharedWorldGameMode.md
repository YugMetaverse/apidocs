[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARSharedWorldGameMode

# Class: ARSharedWorldGameMode

[ue/ue](../modules/ue_ue.md).ARSharedWorldGameMode

## Hierarchy

- [`GameMode`](ue_ue.GameMode.md)

  ↳ **`ARSharedWorldGameMode`**

## Table of contents

### Constructors

- [constructor](ue_ue.ARSharedWorldGameMode.md#constructor)

### Properties

- [ActorLabel](ue_ue.ARSharedWorldGameMode.md#actorlabel)
- [AttachmentReplication](ue_ue.ARSharedWorldGameMode.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.ARSharedWorldGameMode.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.ARSharedWorldGameMode.md#blueprintcreatedcomponents)
- [BufferSizePerChunk](ue_ue.ARSharedWorldGameMode.md#buffersizeperchunk)
- [Children](ue_ue.ARSharedWorldGameMode.md#children)
- [ControllingMatineeActors](ue_ue.ARSharedWorldGameMode.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.ARSharedWorldGameMode.md#customtimedilation)
- [DefaultPawnClass](ue_ue.ARSharedWorldGameMode.md#defaultpawnclass)
- [DefaultPlayerName](ue_ue.ARSharedWorldGameMode.md#defaultplayername)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.ARSharedWorldGameMode.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [EngineMessageClass](ue_ue.ARSharedWorldGameMode.md#enginemessageclass)
- [FolderPath](ue_ue.ARSharedWorldGameMode.md#folderpath)
- [GameSession](ue_ue.ARSharedWorldGameMode.md#gamesession)
- [GameSessionClass](ue_ue.ARSharedWorldGameMode.md#gamesessionclass)
- [GameState](ue_ue.ARSharedWorldGameMode.md#gamestate)
- [GameStateClass](ue_ue.ARSharedWorldGameMode.md#gamestateclass)
- [GroupActor](ue_ue.ARSharedWorldGameMode.md#groupactor)
- [HUDClass](ue_ue.ARSharedWorldGameMode.md#hudclass)
- [HiddenEditorViews](ue_ue.ARSharedWorldGameMode.md#hiddeneditorviews)
- [InactivePlayerArray](ue_ue.ARSharedWorldGameMode.md#inactiveplayerarray)
- [InactivePlayerStateLifeSpan](ue_ue.ARSharedWorldGameMode.md#inactiveplayerstatelifespan)
- [InitialLifeSpan](ue_ue.ARSharedWorldGameMode.md#initiallifespan)
- [InputComponent](ue_ue.ARSharedWorldGameMode.md#inputcomponent)
- [InputPriority](ue_ue.ARSharedWorldGameMode.md#inputpriority)
- [InstanceComponents](ue_ue.ARSharedWorldGameMode.md#instancecomponents)
- [Instigator](ue_ue.ARSharedWorldGameMode.md#instigator)
- [Layers](ue_ue.ARSharedWorldGameMode.md#layers)
- [MatchState](ue_ue.ARSharedWorldGameMode.md#matchstate)
- [MaxInactivePlayers](ue_ue.ARSharedWorldGameMode.md#maxinactiveplayers)
- [MinNetUpdateFrequency](ue_ue.ARSharedWorldGameMode.md#minnetupdatefrequency)
- [MinRespawnDelay](ue_ue.ARSharedWorldGameMode.md#minrespawndelay)
- [NetCullDistanceSquared](ue_ue.ARSharedWorldGameMode.md#netculldistancesquared)
- [NetDormancy](ue_ue.ARSharedWorldGameMode.md#netdormancy)
- [NetDriverName](ue_ue.ARSharedWorldGameMode.md#netdrivername)
- [NetPriority](ue_ue.ARSharedWorldGameMode.md#netpriority)
- [NetTag](ue_ue.ARSharedWorldGameMode.md#nettag)
- [NetUpdateFrequency](ue_ue.ARSharedWorldGameMode.md#netupdatefrequency)
- [NumBots](ue_ue.ARSharedWorldGameMode.md#numbots)
- [NumPlayers](ue_ue.ARSharedWorldGameMode.md#numplayers)
- [NumSpectators](ue_ue.ARSharedWorldGameMode.md#numspectators)
- [NumTravellingPlayers](ue_ue.ARSharedWorldGameMode.md#numtravellingplayers)
- [OnActorBeginOverlap](ue_ue.ARSharedWorldGameMode.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.ARSharedWorldGameMode.md#onactorendoverlap)
- [OnActorHit](ue_ue.ARSharedWorldGameMode.md#onactorhit)
- [OnBeginCursorOver](ue_ue.ARSharedWorldGameMode.md#onbegincursorover)
- [OnClicked](ue_ue.ARSharedWorldGameMode.md#onclicked)
- [OnDestroyed](ue_ue.ARSharedWorldGameMode.md#ondestroyed)
- [OnEndCursorOver](ue_ue.ARSharedWorldGameMode.md#onendcursorover)
- [OnEndPlay](ue_ue.ARSharedWorldGameMode.md#onendplay)
- [OnInputTouchBegin](ue_ue.ARSharedWorldGameMode.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.ARSharedWorldGameMode.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.ARSharedWorldGameMode.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.ARSharedWorldGameMode.md#oninputtouchleave)
- [OnReleased](ue_ue.ARSharedWorldGameMode.md#onreleased)
- [OnTakeAnyDamage](ue_ue.ARSharedWorldGameMode.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.ARSharedWorldGameMode.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.ARSharedWorldGameMode.md#ontakeradialdamage)
- [OptionsString](ue_ue.ARSharedWorldGameMode.md#optionsstring)
- [Owner](ue_ue.ARSharedWorldGameMode.md#owner)
- [ParentComponent](ue_ue.ARSharedWorldGameMode.md#parentcomponent)
- [ParentComponentActor](ue_ue.ARSharedWorldGameMode.md#parentcomponentactor)
- [PivotOffset](ue_ue.ARSharedWorldGameMode.md#pivotoffset)
- [PlayerControllerClass](ue_ue.ARSharedWorldGameMode.md#playercontrollerclass)
- [PlayerStateClass](ue_ue.ARSharedWorldGameMode.md#playerstateclass)
- [PrimaryActorTick](ue_ue.ARSharedWorldGameMode.md#primaryactortick)
- [RemoteRole](ue_ue.ARSharedWorldGameMode.md#remoterole)
- [ReplaySpectatorPlayerControllerClass](ue_ue.ARSharedWorldGameMode.md#replayspectatorplayercontrollerclass)
- [ReplicatedMovement](ue_ue.ARSharedWorldGameMode.md#replicatedmovement)
- [Role](ue_ue.ARSharedWorldGameMode.md#role)
- [RootComponent](ue_ue.ARSharedWorldGameMode.md#rootcomponent)
- [ServerStatReplicator](ue_ue.ARSharedWorldGameMode.md#serverstatreplicator)
- [ServerStatReplicatorClass](ue_ue.ARSharedWorldGameMode.md#serverstatreplicatorclass)
- [SpawnCollisionHandlingMethod](ue_ue.ARSharedWorldGameMode.md#spawncollisionhandlingmethod)
- [SpectatorClass](ue_ue.ARSharedWorldGameMode.md#spectatorclass)
- [SpriteComponent](ue_ue.ARSharedWorldGameMode.md#spritecomponent)
- [SpriteScale](ue_ue.ARSharedWorldGameMode.md#spritescale)
- [Tags](ue_ue.ARSharedWorldGameMode.md#tags)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.ARSharedWorldGameMode.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_ARSharedWorldGameMode\_\_](ue_ue.ARSharedWorldGameMode.md#__tid_arsharedworldgamemode__)
- [\_\_tid\_Actor\_\_](ue_ue.ARSharedWorldGameMode.md#__tid_actor__)
- [\_\_tid\_GameModeBase\_\_](ue_ue.ARSharedWorldGameMode.md#__tid_gamemodebase__)
- [\_\_tid\_GameMode\_\_](ue_ue.ARSharedWorldGameMode.md#__tid_gamemode__)
- [\_\_tid\_Info\_\_](ue_ue.ARSharedWorldGameMode.md#__tid_info__)
- [\_\_tid\_Object\_\_](ue_ue.ARSharedWorldGameMode.md#__tid_object__)
- [bActorEnableCollision](ue_ue.ARSharedWorldGameMode.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.ARSharedWorldGameMode.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.ARSharedWorldGameMode.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.ARSharedWorldGameMode.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.ARSharedWorldGameMode.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.ARSharedWorldGameMode.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.ARSharedWorldGameMode.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.ARSharedWorldGameMode.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.ARSharedWorldGameMode.md#bblockinput)
- [bCanBeDamaged](ue_ue.ARSharedWorldGameMode.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.ARSharedWorldGameMode.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.ARSharedWorldGameMode.md#bcollidewhenplacing)
- [bDelayedStart](ue_ue.ARSharedWorldGameMode.md#bdelayedstart)
- [bEditable](ue_ue.ARSharedWorldGameMode.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.ARSharedWorldGameMode.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.ARSharedWorldGameMode.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.ARSharedWorldGameMode.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.ARSharedWorldGameMode.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHandleDedicatedServerReplays](ue_ue.ARSharedWorldGameMode.md#bhandlededicatedserverreplays)
- [bHidden](ue_ue.ARSharedWorldGameMode.md#bhidden)
- [bHiddenEd](ue_ue.ARSharedWorldGameMode.md#bhiddened)
- [bHiddenEdLayer](ue_ue.ARSharedWorldGameMode.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.ARSharedWorldGameMode.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.ARSharedWorldGameMode.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.ARSharedWorldGameMode.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.ARSharedWorldGameMode.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.ARSharedWorldGameMode.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.ARSharedWorldGameMode.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.ARSharedWorldGameMode.md#blocklocation)
- [bNetLoadOnClient](ue_ue.ARSharedWorldGameMode.md#bnetloadonclient)
- [bNetStartup](ue_ue.ARSharedWorldGameMode.md#bnetstartup)
- [bNetTemporary](ue_ue.ARSharedWorldGameMode.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.ARSharedWorldGameMode.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.ARSharedWorldGameMode.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.ARSharedWorldGameMode.md#boptimizebpcomponentdata)
- [bPauseable](ue_ue.ARSharedWorldGameMode.md#bpauseable)
- [bRelevantForLevelBounds](ue_ue.ARSharedWorldGameMode.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.ARSharedWorldGameMode.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.ARSharedWorldGameMode.md#breplayrewindable)
- [bReplicateMovement](ue_ue.ARSharedWorldGameMode.md#breplicatemovement)
- [bReplicates](ue_ue.ARSharedWorldGameMode.md#breplicates)
- [bStartPlayersAsSpectators](ue_ue.ARSharedWorldGameMode.md#bstartplayersasspectators)
- [bTearOff](ue_ue.ARSharedWorldGameMode.md#btearoff)
- [bUseSeamlessTravel](ue_ue.ARSharedWorldGameMode.md#buseseamlesstravel)

### Methods

- [AbortMatch](ue_ue.ARSharedWorldGameMode.md#abortmatch)
- [ActorHasTag](ue_ue.ARSharedWorldGameMode.md#actorhastag)
- [AddComponent](ue_ue.ARSharedWorldGameMode.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.ARSharedWorldGameMode.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.ARSharedWorldGameMode.md#addtickprerequisitecomponent)
- [CanSpectate](ue_ue.ARSharedWorldGameMode.md#canspectate)
- [ChangeName](ue_ue.ARSharedWorldGameMode.md#changename)
- [ChoosePlayerStart](ue_ue.ARSharedWorldGameMode.md#chooseplayerstart)
- [CreateDefaultSubobject](ue_ue.ARSharedWorldGameMode.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.ARSharedWorldGameMode.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.ARSharedWorldGameMode.md#disableinput)
- [EnableInput](ue_ue.ARSharedWorldGameMode.md#enableinput)
- [EndMatch](ue_ue.ARSharedWorldGameMode.md#endmatch)
- [ExecuteUbergraph](ue_ue.ARSharedWorldGameMode.md#executeubergraph)
- [FindPlayerStart](ue_ue.ARSharedWorldGameMode.md#findplayerstart)
- [FlushNetDormancy](ue_ue.ARSharedWorldGameMode.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.ARSharedWorldGameMode.md#forcenetupdate)
- [GetARSharedWorldGameState](ue_ue.ARSharedWorldGameMode.md#getarsharedworldgamestate)
- [GetActorBounds](ue_ue.ARSharedWorldGameMode.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.ARSharedWorldGameMode.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.ARSharedWorldGameMode.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.ARSharedWorldGameMode.md#getactorforwardvector)
- [GetActorLabel](ue_ue.ARSharedWorldGameMode.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.ARSharedWorldGameMode.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.ARSharedWorldGameMode.md#getactorrightvector)
- [GetActorScale3D](ue_ue.ARSharedWorldGameMode.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.ARSharedWorldGameMode.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.ARSharedWorldGameMode.md#getactortimedilation)
- [GetActorUpVector](ue_ue.ARSharedWorldGameMode.md#getactorupvector)
- [GetAllChildActors](ue_ue.ARSharedWorldGameMode.md#getallchildactors)
- [GetAttachParentActor](ue_ue.ARSharedWorldGameMode.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.ARSharedWorldGameMode.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.ARSharedWorldGameMode.md#getattachedactors)
- [GetClass](ue_ue.ARSharedWorldGameMode.md#getclass)
- [GetComponentByClass](ue_ue.ARSharedWorldGameMode.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.ARSharedWorldGameMode.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.ARSharedWorldGameMode.md#getcomponentsbytag)
- [GetDefaultPawnClassForController](ue_ue.ARSharedWorldGameMode.md#getdefaultpawnclassforcontroller)
- [GetDistanceTo](ue_ue.ARSharedWorldGameMode.md#getdistanceto)
- [GetDotProductTo](ue_ue.ARSharedWorldGameMode.md#getdotproductto)
- [GetFolderPath](ue_ue.ARSharedWorldGameMode.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.ARSharedWorldGameMode.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.ARSharedWorldGameMode.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.ARSharedWorldGameMode.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.ARSharedWorldGameMode.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.ARSharedWorldGameMode.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.ARSharedWorldGameMode.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.ARSharedWorldGameMode.md#getinstigator)
- [GetInstigatorController](ue_ue.ARSharedWorldGameMode.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.ARSharedWorldGameMode.md#getlifespan)
- [GetLocalRole](ue_ue.ARSharedWorldGameMode.md#getlocalrole)
- [GetMatchState](ue_ue.ARSharedWorldGameMode.md#getmatchstate)
- [GetName](ue_ue.ARSharedWorldGameMode.md#getname)
- [GetNumPlayers](ue_ue.ARSharedWorldGameMode.md#getnumplayers)
- [GetNumSpectators](ue_ue.ARSharedWorldGameMode.md#getnumspectators)
- [GetOuter](ue_ue.ARSharedWorldGameMode.md#getouter)
- [GetOverlappingActors](ue_ue.ARSharedWorldGameMode.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.ARSharedWorldGameMode.md#getoverlappingcomponents)
- [GetOwner](ue_ue.ARSharedWorldGameMode.md#getowner)
- [GetParentActor](ue_ue.ARSharedWorldGameMode.md#getparentactor)
- [GetParentComponent](ue_ue.ARSharedWorldGameMode.md#getparentcomponent)
- [GetRemoteRole](ue_ue.ARSharedWorldGameMode.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.ARSharedWorldGameMode.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.ARSharedWorldGameMode.md#gettickablewhenpaused)
- [GetTransform](ue_ue.ARSharedWorldGameMode.md#gettransform)
- [GetVelocity](ue_ue.ARSharedWorldGameMode.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.ARSharedWorldGameMode.md#getverticaldistanceto)
- [GetWorld](ue_ue.ARSharedWorldGameMode.md#getworld)
- [HandleStartingNewPlayer](ue_ue.ARSharedWorldGameMode.md#handlestartingnewplayer)
- [HasAuthority](ue_ue.ARSharedWorldGameMode.md#hasauthority)
- [HasMatchEnded](ue_ue.ARSharedWorldGameMode.md#hasmatchended)
- [HasMatchStarted](ue_ue.ARSharedWorldGameMode.md#hasmatchstarted)
- [InitStartSpot](ue_ue.ARSharedWorldGameMode.md#initstartspot)
- [InitializeHUDForPlayer](ue_ue.ARSharedWorldGameMode.md#initializehudforplayer)
- [IsActorBeingDestroyed](ue_ue.ARSharedWorldGameMode.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.ARSharedWorldGameMode.md#isactortickenabled)
- [IsChildActor](ue_ue.ARSharedWorldGameMode.md#ischildactor)
- [IsEditable](ue_ue.ARSharedWorldGameMode.md#iseditable)
- [IsHiddenEd](ue_ue.ARSharedWorldGameMode.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.ARSharedWorldGameMode.md#ishiddenedatstartup)
- [IsMatchInProgress](ue_ue.ARSharedWorldGameMode.md#ismatchinprogress)
- [IsOverlappingActor](ue_ue.ARSharedWorldGameMode.md#isoverlappingactor)
- [IsSelectable](ue_ue.ARSharedWorldGameMode.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.ARSharedWorldGameMode.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.ARSharedWorldGameMode.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.ARSharedWorldGameMode.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.ARSharedWorldGameMode.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.ARSharedWorldGameMode.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.ARSharedWorldGameMode.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.ARSharedWorldGameMode.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.ARSharedWorldGameMode.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.ARSharedWorldGameMode.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.ARSharedWorldGameMode.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.ARSharedWorldGameMode.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.ARSharedWorldGameMode.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.ARSharedWorldGameMode.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.ARSharedWorldGameMode.md#k2_detachfromactor)
- [K2\_FindPlayerStart](ue_ue.ARSharedWorldGameMode.md#k2_findplayerstart)
- [K2\_GetActorLocation](ue_ue.ARSharedWorldGameMode.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.ARSharedWorldGameMode.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.ARSharedWorldGameMode.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.ARSharedWorldGameMode.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.ARSharedWorldGameMode.md#k2_onbecomeviewtarget)
- [K2\_OnChangeName](ue_ue.ARSharedWorldGameMode.md#k2_onchangename)
- [K2\_OnEndViewTarget](ue_ue.ARSharedWorldGameMode.md#k2_onendviewtarget)
- [K2\_OnLogout](ue_ue.ARSharedWorldGameMode.md#k2_onlogout)
- [K2\_OnReset](ue_ue.ARSharedWorldGameMode.md#k2_onreset)
- [K2\_OnRestartPlayer](ue_ue.ARSharedWorldGameMode.md#k2_onrestartplayer)
- [K2\_OnSetMatchState](ue_ue.ARSharedWorldGameMode.md#k2_onsetmatchstate)
- [K2\_OnSwapPlayerControllers](ue_ue.ARSharedWorldGameMode.md#k2_onswapplayercontrollers)
- [K2\_PostLogin](ue_ue.ARSharedWorldGameMode.md#k2_postlogin)
- [K2\_SetActorLocation](ue_ue.ARSharedWorldGameMode.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.ARSharedWorldGameMode.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.ARSharedWorldGameMode.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.ARSharedWorldGameMode.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.ARSharedWorldGameMode.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.ARSharedWorldGameMode.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.ARSharedWorldGameMode.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.ARSharedWorldGameMode.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.ARSharedWorldGameMode.md#makemidformaterial)
- [MakeNoise](ue_ue.ARSharedWorldGameMode.md#makenoise)
- [MustSpectate](ue_ue.ARSharedWorldGameMode.md#mustspectate)
- [OnRep\_AttachmentReplication](ue_ue.ARSharedWorldGameMode.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.ARSharedWorldGameMode.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.ARSharedWorldGameMode.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.ARSharedWorldGameMode.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.ARSharedWorldGameMode.md#onrep_replicatedmovement)
- [PlayerCanRestart](ue_ue.ARSharedWorldGameMode.md#playercanrestart)
- [PrestreamTextures](ue_ue.ARSharedWorldGameMode.md#prestreamtextures)
- [ReadyToEndMatch](ue_ue.ARSharedWorldGameMode.md#readytoendmatch)
- [ReadyToStartMatch](ue_ue.ARSharedWorldGameMode.md#readytostartmatch)
- [ReceiveActorBeginCursorOver](ue_ue.ARSharedWorldGameMode.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.ARSharedWorldGameMode.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.ARSharedWorldGameMode.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.ARSharedWorldGameMode.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.ARSharedWorldGameMode.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.ARSharedWorldGameMode.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.ARSharedWorldGameMode.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.ARSharedWorldGameMode.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.ARSharedWorldGameMode.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.ARSharedWorldGameMode.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.ARSharedWorldGameMode.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.ARSharedWorldGameMode.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.ARSharedWorldGameMode.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.ARSharedWorldGameMode.md#receiveendplay)
- [ReceiveHit](ue_ue.ARSharedWorldGameMode.md#receivehit)
- [ReceivePointDamage](ue_ue.ARSharedWorldGameMode.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.ARSharedWorldGameMode.md#receiveradialdamage)
- [ReceiveTick](ue_ue.ARSharedWorldGameMode.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.ARSharedWorldGameMode.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.ARSharedWorldGameMode.md#removetickprerequisitecomponent)
- [ResetLevel](ue_ue.ARSharedWorldGameMode.md#resetlevel)
- [RestartGame](ue_ue.ARSharedWorldGameMode.md#restartgame)
- [RestartPlayer](ue_ue.ARSharedWorldGameMode.md#restartplayer)
- [RestartPlayerAtPlayerStart](ue_ue.ARSharedWorldGameMode.md#restartplayeratplayerstart)
- [RestartPlayerAtTransform](ue_ue.ARSharedWorldGameMode.md#restartplayerattransform)
- [ReturnToMainMenuHost](ue_ue.ARSharedWorldGameMode.md#returntomainmenuhost)
- [Say](ue_ue.ARSharedWorldGameMode.md#say)
- [SetARSharedWorldData](ue_ue.ARSharedWorldGameMode.md#setarsharedworlddata)
- [SetARWorldSharingIsReady](ue_ue.ARSharedWorldGameMode.md#setarworldsharingisready)
- [SetActorEnableCollision](ue_ue.ARSharedWorldGameMode.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.ARSharedWorldGameMode.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.ARSharedWorldGameMode.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.ARSharedWorldGameMode.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.ARSharedWorldGameMode.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.ARSharedWorldGameMode.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.ARSharedWorldGameMode.md#setactortickinterval)
- [SetBandwidthLimit](ue_ue.ARSharedWorldGameMode.md#setbandwidthlimit)
- [SetFolderPath](ue_ue.ARSharedWorldGameMode.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.ARSharedWorldGameMode.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.ARSharedWorldGameMode.md#setlifespan)
- [SetNetDormancy](ue_ue.ARSharedWorldGameMode.md#setnetdormancy)
- [SetOwner](ue_ue.ARSharedWorldGameMode.md#setowner)
- [SetPreviewImageData](ue_ue.ARSharedWorldGameMode.md#setpreviewimagedata)
- [SetReplicateMovement](ue_ue.ARSharedWorldGameMode.md#setreplicatemovement)
- [SetReplicates](ue_ue.ARSharedWorldGameMode.md#setreplicates)
- [SetTickGroup](ue_ue.ARSharedWorldGameMode.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.ARSharedWorldGameMode.md#settickablewhenpaused)
- [ShouldReset](ue_ue.ARSharedWorldGameMode.md#shouldreset)
- [SnapRootComponentTo](ue_ue.ARSharedWorldGameMode.md#snaprootcomponentto)
- [SpawnDefaultPawnAtTransform](ue_ue.ARSharedWorldGameMode.md#spawndefaultpawnattransform)
- [SpawnDefaultPawnFor](ue_ue.ARSharedWorldGameMode.md#spawndefaultpawnfor)
- [StartMatch](ue_ue.ARSharedWorldGameMode.md#startmatch)
- [StartPlay](ue_ue.ARSharedWorldGameMode.md#startplay)
- [TearOff](ue_ue.ARSharedWorldGameMode.md#tearoff)
- [UserConstructionScript](ue_ue.ARSharedWorldGameMode.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.ARSharedWorldGameMode.md#wasrecentlyrendered)
- [Find](ue_ue.ARSharedWorldGameMode.md#find)
- [Load](ue_ue.ARSharedWorldGameMode.md#load)
- [StaticClass](ue_ue.ARSharedWorldGameMode.md#staticclass)

## Constructors

### constructor

• **new ARSharedWorldGameMode**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GameMode](ue_ue.GameMode.md).[constructor](ue_ue.GameMode.md#constructor)

#### Defined in

[ue/ue.d.ts:21328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21328)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ActorLabel](ue_ue.GameMode.md#actorlabel)

#### Defined in

[ue/ue.d.ts:13176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13176)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[AttachmentReplication](ue_ue.GameMode.md#attachmentreplication)

#### Defined in

[ue/ue.d.ts:13151](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13151)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[AutoReceiveInput](ue_ue.GameMode.md#autoreceiveinput)

#### Defined in

[ue/ue.d.ts:13157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13157)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[BlueprintCreatedComponents](ue_ue.GameMode.md#blueprintcreatedcomponents)

#### Defined in

[ue/ue.d.ts:13206](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13206)

___

### BufferSizePerChunk

• **BufferSizePerChunk**: `number`

#### Defined in

[ue/ue.d.ts:21329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21329)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[Children](ue_ue.GameMode.md#children)

#### Defined in

[ue/ue.d.ts:13166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13166)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ControllingMatineeActors](ue_ue.GameMode.md#controllingmatineeactors)

#### Defined in

[ue/ue.d.ts:13169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13169)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[CustomTimeDilation](ue_ue.GameMode.md#customtimedilation)

#### Defined in

[ue/ue.d.ts:13150](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13150)

___

### DefaultPawnClass

• **DefaultPawnClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[DefaultPawnClass](ue_ue.GameMode.md#defaultpawnclass)

#### Defined in

[ue/ue.d.ts:10017](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10017)

___

### DefaultPlayerName

• **DefaultPlayerName**: `string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[DefaultPlayerName](ue_ue.GameMode.md#defaultplayername)

#### Defined in

[ue/ue.d.ts:10024](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10024)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.GameMode.md#defaultupdateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13146](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13146)

___

### EngineMessageClass

• **EngineMessageClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[EngineMessageClass](ue_ue.GameMode.md#enginemessageclass)

#### Defined in

[ue/ue.d.ts:21273](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21273)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[FolderPath](ue_ue.GameMode.md#folderpath)

#### Defined in

[ue/ue.d.ts:13177](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13177)

___

### GameSession

• **GameSession**: [`GameSession`](ue_ue.GameSession.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GameSession](ue_ue.GameMode.md#gamesession)

#### Defined in

[ue/ue.d.ts:10021](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10021)

___

### GameSessionClass

• **GameSessionClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GameSessionClass](ue_ue.GameMode.md#gamesessionclass)

#### Defined in

[ue/ue.d.ts:10012](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10012)

___

### GameState

• **GameState**: [`GameStateBase`](ue_ue.GameStateBase.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GameState](ue_ue.GameMode.md#gamestate)

#### Defined in

[ue/ue.d.ts:10022](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10022)

___

### GameStateClass

• **GameStateClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GameStateClass](ue_ue.GameMode.md#gamestateclass)

#### Defined in

[ue/ue.d.ts:10013](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10013)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GroupActor](ue_ue.GameMode.md#groupactor)

#### Defined in

[ue/ue.d.ts:13173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13173)

___

### HUDClass

• **HUDClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[HUDClass](ue_ue.GameMode.md#hudclass)

#### Defined in

[ue/ue.d.ts:10016](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10016)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[HiddenEditorViews](ue_ue.GameMode.md#hiddeneditorviews)

#### Defined in

[ue/ue.d.ts:13175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13175)

___

### InactivePlayerArray

• **InactivePlayerArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PlayerState`](ue_ue.PlayerState.md)\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[InactivePlayerArray](ue_ue.GameMode.md#inactiveplayerarray)

#### Defined in

[ue/ue.d.ts:21274](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21274)

___

### InactivePlayerStateLifeSpan

• **InactivePlayerStateLifeSpan**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[InactivePlayerStateLifeSpan](ue_ue.GameMode.md#inactiveplayerstatelifespan)

#### Defined in

[ue/ue.d.ts:21275](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21275)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[InitialLifeSpan](ue_ue.GameMode.md#initiallifespan)

#### Defined in

[ue/ue.d.ts:13149](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13149)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[InputComponent](ue_ue.GameMode.md#inputcomponent)

#### Defined in

[ue/ue.d.ts:13159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13159)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[InputPriority](ue_ue.GameMode.md#inputpriority)

#### Defined in

[ue/ue.d.ts:13158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13158)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[InstanceComponents](ue_ue.GameMode.md#instancecomponents)

#### Defined in

[ue/ue.d.ts:13205](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13205)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[Instigator](ue_ue.GameMode.md#instigator)

#### Defined in

[ue/ue.d.ts:13165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13165)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[Layers](ue_ue.GameMode.md#layers)

#### Defined in

[ue/ue.d.ts:13170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13170)

___

### MatchState

• **MatchState**: `string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[MatchState](ue_ue.GameMode.md#matchstate)

#### Defined in

[ue/ue.d.ts:21266](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21266)

___

### MaxInactivePlayers

• **MaxInactivePlayers**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[MaxInactivePlayers](ue_ue.GameMode.md#maxinactiveplayers)

#### Defined in

[ue/ue.d.ts:21276](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21276)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[MinNetUpdateFrequency](ue_ue.GameMode.md#minnetupdatefrequency)

#### Defined in

[ue/ue.d.ts:13163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13163)

___

### MinRespawnDelay

• **MinRespawnDelay**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[MinRespawnDelay](ue_ue.GameMode.md#minrespawndelay)

#### Defined in

[ue/ue.d.ts:21271](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21271)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NetCullDistanceSquared](ue_ue.GameMode.md#netculldistancesquared)

#### Defined in

[ue/ue.d.ts:13160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13160)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NetDormancy](ue_ue.GameMode.md#netdormancy)

#### Defined in

[ue/ue.d.ts:13155](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13155)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NetDriverName](ue_ue.GameMode.md#netdrivername)

#### Defined in

[ue/ue.d.ts:13153](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13153)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NetPriority](ue_ue.GameMode.md#netpriority)

#### Defined in

[ue/ue.d.ts:13164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13164)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NetTag](ue_ue.GameMode.md#nettag)

#### Defined in

[ue/ue.d.ts:13161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13161)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NetUpdateFrequency](ue_ue.GameMode.md#netupdatefrequency)

#### Defined in

[ue/ue.d.ts:13162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13162)

___

### NumBots

• **NumBots**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NumBots](ue_ue.GameMode.md#numbots)

#### Defined in

[ue/ue.d.ts:21270](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21270)

___

### NumPlayers

• **NumPlayers**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NumPlayers](ue_ue.GameMode.md#numplayers)

#### Defined in

[ue/ue.d.ts:21269](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21269)

___

### NumSpectators

• **NumSpectators**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NumSpectators](ue_ue.GameMode.md#numspectators)

#### Defined in

[ue/ue.d.ts:21268](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21268)

___

### NumTravellingPlayers

• **NumTravellingPlayers**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NumTravellingPlayers](ue_ue.GameMode.md#numtravellingplayers)

#### Defined in

[ue/ue.d.ts:21272](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21272)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnActorBeginOverlap](ue_ue.GameMode.md#onactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13192](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13192)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnActorEndOverlap](ue_ue.GameMode.md#onactorendoverlap)

#### Defined in

[ue/ue.d.ts:13193](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13193)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnActorHit](ue_ue.GameMode.md#onactorhit)

#### Defined in

[ue/ue.d.ts:13202](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13202)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnBeginCursorOver](ue_ue.GameMode.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:13194](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13194)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnClicked](ue_ue.GameMode.md#onclicked)

#### Defined in

[ue/ue.d.ts:13196](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13196)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnDestroyed](ue_ue.GameMode.md#ondestroyed)

#### Defined in

[ue/ue.d.ts:13203](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13203)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnEndCursorOver](ue_ue.GameMode.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:13195](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13195)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnEndPlay](ue_ue.GameMode.md#onendplay)

#### Defined in

[ue/ue.d.ts:13204](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13204)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnInputTouchBegin](ue_ue.GameMode.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13198](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13198)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnInputTouchEnd](ue_ue.GameMode.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:13199](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13199)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnInputTouchEnter](ue_ue.GameMode.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:13200](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13200)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnInputTouchLeave](ue_ue.GameMode.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:13201](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13201)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnReleased](ue_ue.GameMode.md#onreleased)

#### Defined in

[ue/ue.d.ts:13197](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13197)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnTakeAnyDamage](ue_ue.GameMode.md#ontakeanydamage)

#### Defined in

[ue/ue.d.ts:13189](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13189)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnTakePointDamage](ue_ue.GameMode.md#ontakepointdamage)

#### Defined in

[ue/ue.d.ts:13190](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13190)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnTakeRadialDamage](ue_ue.GameMode.md#ontakeradialdamage)

#### Defined in

[ue/ue.d.ts:13191](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13191)

___

### OptionsString

• **OptionsString**: `string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OptionsString](ue_ue.GameMode.md#optionsstring)

#### Defined in

[ue/ue.d.ts:10011](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10011)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[Owner](ue_ue.GameMode.md#owner)

#### Defined in

[ue/ue.d.ts:13152](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13152)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ParentComponent](ue_ue.GameMode.md#parentcomponent)

#### Defined in

[ue/ue.d.ts:13172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13172)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ParentComponentActor](ue_ue.GameMode.md#parentcomponentactor)

#### Defined in

[ue/ue.d.ts:13171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13171)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[PivotOffset](ue_ue.GameMode.md#pivotoffset)

#### Defined in

[ue/ue.d.ts:13168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13168)

___

### PlayerControllerClass

• **PlayerControllerClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[PlayerControllerClass](ue_ue.GameMode.md#playercontrollerclass)

#### Defined in

[ue/ue.d.ts:10014](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10014)

___

### PlayerStateClass

• **PlayerStateClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[PlayerStateClass](ue_ue.GameMode.md#playerstateclass)

#### Defined in

[ue/ue.d.ts:10015](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10015)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[PrimaryActorTick](ue_ue.GameMode.md#primaryactortick)

#### Defined in

[ue/ue.d.ts:13115](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13115)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[RemoteRole](ue_ue.GameMode.md#remoterole)

#### Defined in

[ue/ue.d.ts:13147](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13147)

___

### ReplaySpectatorPlayerControllerClass

• **ReplaySpectatorPlayerControllerClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReplaySpectatorPlayerControllerClass](ue_ue.GameMode.md#replayspectatorplayercontrollerclass)

#### Defined in

[ue/ue.d.ts:10019](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10019)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReplicatedMovement](ue_ue.GameMode.md#replicatedmovement)

#### Defined in

[ue/ue.d.ts:13148](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13148)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[Role](ue_ue.GameMode.md#role)

#### Defined in

[ue/ue.d.ts:13154](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13154)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[RootComponent](ue_ue.GameMode.md#rootcomponent)

#### Defined in

[ue/ue.d.ts:13167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13167)

___

### ServerStatReplicator

• **ServerStatReplicator**: [`ServerStatReplicator`](ue_ue.ServerStatReplicator.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ServerStatReplicator](ue_ue.GameMode.md#serverstatreplicator)

#### Defined in

[ue/ue.d.ts:10023](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10023)

___

### ServerStatReplicatorClass

• **ServerStatReplicatorClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ServerStatReplicatorClass](ue_ue.GameMode.md#serverstatreplicatorclass)

#### Defined in

[ue/ue.d.ts:10020](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10020)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[SpawnCollisionHandlingMethod](ue_ue.GameMode.md#spawncollisionhandlingmethod)

#### Defined in

[ue/ue.d.ts:13156](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13156)

___

### SpectatorClass

• **SpectatorClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[SpectatorClass](ue_ue.GameMode.md#spectatorclass)

#### Defined in

[ue/ue.d.ts:10018](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10018)

___

### SpriteComponent

• **SpriteComponent**: [`BillboardComponent`](ue_ue.BillboardComponent.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[SpriteComponent](ue_ue.GameMode.md#spritecomponent)

#### Defined in

[ue/ue.d.ts:2215](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2215)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[SpriteScale](ue_ue.GameMode.md#spritescale)

#### Defined in

[ue/ue.d.ts:13174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13174)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[Tags](ue_ue.GameMode.md#tags)

#### Defined in

[ue/ue.d.ts:13188](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13188)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.GameMode.md#updateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13145](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13145)

___

### \_\_tid\_ARSharedWorldGameMode\_\_

• **\_\_tid\_ARSharedWorldGameMode\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:21338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21338)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[__tid_Actor__](ue_ue.GameMode.md#__tid_actor__)

#### Defined in

[ue/ue.d.ts:13348](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13348)

___

### \_\_tid\_GameModeBase\_\_

• **\_\_tid\_GameModeBase\_\_**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[__tid_GameModeBase__](ue_ue.GameMode.md#__tid_gamemodebase__)

#### Defined in

[ue/ue.d.ts:10060](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10060)

___

### \_\_tid\_GameMode\_\_

• **\_\_tid\_GameMode\_\_**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[__tid_GameMode__](ue_ue.GameMode.md#__tid_gamemode__)

#### Defined in

[ue/ue.d.ts:21294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21294)

___

### \_\_tid\_Info\_\_

• **\_\_tid\_Info\_\_**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[__tid_Info__](ue_ue.GameMode.md#__tid_info__)

#### Defined in

[ue/ue.d.ts:2220](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2220)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[__tid_Object__](ue_ue.GameMode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bActorEnableCollision](ue_ue.GameMode.md#bactorenablecollision)

#### Defined in

[ue/ue.d.ts:13143](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13143)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bActorIsBeingDestroyed](ue_ue.GameMode.md#bactorisbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13144](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13144)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bActorLabelEditable](ue_ue.GameMode.md#bactorlabeleditable)

#### Defined in

[ue/ue.d.ts:13183](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13183)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bActorSeamlessTraveled](ue_ue.GameMode.md#bactorseamlesstraveled)

#### Defined in

[ue/ue.d.ts:13139](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13139)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.GameMode.md#ballowreceivetickeventondedicatedserver)

#### Defined in

[ue/ue.d.ts:13142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13142)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bAllowTickBeforeBeginPlay](ue_ue.GameMode.md#ballowtickbeforebeginplay)

#### Defined in

[ue/ue.d.ts:13129](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13129)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bAlwaysRelevant](ue_ue.GameMode.md#balwaysrelevant)

#### Defined in

[ue/ue.d.ts:13120](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13120)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bAutoDestroyWhenFinished](ue_ue.GameMode.md#bautodestroywhenfinished)

#### Defined in

[ue/ue.d.ts:13130](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13130)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bBlockInput](ue_ue.GameMode.md#bblockinput)

#### Defined in

[ue/ue.d.ts:13131](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13131)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bCanBeDamaged](ue_ue.GameMode.md#bcanbedamaged)

#### Defined in

[ue/ue.d.ts:13132](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13132)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bCanBeInCluster](ue_ue.GameMode.md#bcanbeincluster)

#### Defined in

[ue/ue.d.ts:13141](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13141)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bCollideWhenPlacing](ue_ue.GameMode.md#bcollidewhenplacing)

#### Defined in

[ue/ue.d.ts:13133](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13133)

___

### bDelayedStart

• **bDelayedStart**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bDelayedStart](ue_ue.GameMode.md#bdelayedstart)

#### Defined in

[ue/ue.d.ts:21267](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21267)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bEditable](ue_ue.GameMode.md#beditable)

#### Defined in

[ue/ue.d.ts:13184](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13184)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bEnableAutoLODGeneration](ue_ue.GameMode.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:13137](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13137)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bExchangedRoles](ue_ue.GameMode.md#bexchangedroles)

#### Defined in

[ue/ue.d.ts:13123](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13123)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bFindCameraComponentWhenViewTarget](ue_ue.GameMode.md#bfindcameracomponentwhenviewtarget)

#### Defined in

[ue/ue.d.ts:13134](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13134)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.GameMode.md#bgenerateoverlapeventsduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13135](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13135)

___

### bHandleDedicatedServerReplays

• **bHandleDedicatedServerReplays**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bHandleDedicatedServerReplays](ue_ue.GameMode.md#bhandlededicatedserverreplays)

#### Defined in

[ue/ue.d.ts:21277](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21277)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bHidden](ue_ue.GameMode.md#bhidden)

#### Defined in

[ue/ue.d.ts:13116](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13116)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bHiddenEd](ue_ue.GameMode.md#bhiddened)

#### Defined in

[ue/ue.d.ts:13178](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13178)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bHiddenEdLayer](ue_ue.GameMode.md#bhiddenedlayer)

#### Defined in

[ue/ue.d.ts:13180](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13180)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bHiddenEdLevel](ue_ue.GameMode.md#bhiddenedlevel)

#### Defined in

[ue/ue.d.ts:13181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13181)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bHiddenEdTemporary](ue_ue.GameMode.md#bhiddenedtemporary)

#### Defined in

[ue/ue.d.ts:13187](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13187)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bIgnoresOriginShifting](ue_ue.GameMode.md#bignoresoriginshifting)

#### Defined in

[ue/ue.d.ts:13136](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13136)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bIsEditorOnlyActor](ue_ue.GameMode.md#biseditoronlyactor)

#### Defined in

[ue/ue.d.ts:13138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13138)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bIsEditorPreviewActor](ue_ue.GameMode.md#biseditorpreviewactor)

#### Defined in

[ue/ue.d.ts:13179](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13179)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bListedInSceneOutliner](ue_ue.GameMode.md#blistedinsceneoutliner)

#### Defined in

[ue/ue.d.ts:13185](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13185)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bLockLocation](ue_ue.GameMode.md#blocklocation)

#### Defined in

[ue/ue.d.ts:13182](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13182)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bNetLoadOnClient](ue_ue.GameMode.md#bnetloadonclient)

#### Defined in

[ue/ue.d.ts:13124](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13124)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bNetStartup](ue_ue.GameMode.md#bnetstartup)

#### Defined in

[ue/ue.d.ts:13118](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13118)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bNetTemporary](ue_ue.GameMode.md#bnettemporary)

#### Defined in

[ue/ue.d.ts:13117](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13117)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bNetUseOwnerRelevancy](ue_ue.GameMode.md#bnetuseownerrelevancy)

#### Defined in

[ue/ue.d.ts:13125](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13125)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bOnlyRelevantToOwner](ue_ue.GameMode.md#bonlyrelevanttoowner)

#### Defined in

[ue/ue.d.ts:13119](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13119)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bOptimizeBPComponentData](ue_ue.GameMode.md#boptimizebpcomponentdata)

#### Defined in

[ue/ue.d.ts:13186](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13186)

___

### bPauseable

• **bPauseable**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bPauseable](ue_ue.GameMode.md#bpauseable)

#### Defined in

[ue/ue.d.ts:10027](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10027)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bRelevantForLevelBounds](ue_ue.GameMode.md#brelevantforlevelbounds)

#### Defined in

[ue/ue.d.ts:13127](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13127)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bRelevantForNetworkReplays](ue_ue.GameMode.md#brelevantfornetworkreplays)

#### Defined in

[ue/ue.d.ts:13126](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13126)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bReplayRewindable](ue_ue.GameMode.md#breplayrewindable)

#### Defined in

[ue/ue.d.ts:13128](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13128)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bReplicateMovement](ue_ue.GameMode.md#breplicatemovement)

#### Defined in

[ue/ue.d.ts:13121](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13121)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bReplicates](ue_ue.GameMode.md#breplicates)

#### Defined in

[ue/ue.d.ts:13140](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13140)

___

### bStartPlayersAsSpectators

• **bStartPlayersAsSpectators**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bStartPlayersAsSpectators](ue_ue.GameMode.md#bstartplayersasspectators)

#### Defined in

[ue/ue.d.ts:10026](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10026)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bTearOff](ue_ue.GameMode.md#btearoff)

#### Defined in

[ue/ue.d.ts:13122](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13122)

___

### bUseSeamlessTravel

• **bUseSeamlessTravel**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bUseSeamlessTravel](ue_ue.GameMode.md#buseseamlesstravel)

#### Defined in

[ue/ue.d.ts:10025](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10025)

## Methods

### AbortMatch

▸ **AbortMatch**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[AbortMatch](ue_ue.GameMode.md#abortmatch)

#### Defined in

[ue/ue.d.ts:21278](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21278)

___

### ActorHasTag

▸ **ActorHasTag**(`Tag`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tag` | `string` |

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ActorHasTag](ue_ue.GameMode.md#actorhastag)

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

[GameMode](ue_ue.GameMode.md).[AddComponent](ue_ue.GameMode.md#addcomponent)

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

[GameMode](ue_ue.GameMode.md).[AddTickPrerequisiteActor](ue_ue.GameMode.md#addtickprerequisiteactor)

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

[GameMode](ue_ue.GameMode.md).[AddTickPrerequisiteComponent](ue_ue.GameMode.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13210](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13210)

___

### CanSpectate

▸ **CanSpectate**(`Viewer`, `ViewTarget`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Viewer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `ViewTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerState`](ue_ue.PlayerState.md)\> |

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[CanSpectate](ue_ue.GameMode.md#canspectate)

#### Defined in

[ue/ue.d.ts:10028](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10028)

___

### ChangeName

▸ **ChangeName**(`Controller`, `NewName`, `bNameChange`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Controller` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |
| `NewName` | `string` |
| `bNameChange` | `boolean` |

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ChangeName](ue_ue.GameMode.md#changename)

#### Defined in

[ue/ue.d.ts:10029](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10029)

___

### ChoosePlayerStart

▸ **ChoosePlayerStart**(`Player`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Player` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ChoosePlayerStart](ue_ue.GameMode.md#chooseplayerstart)

#### Defined in

[ue/ue.d.ts:10030](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10030)

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

[GameMode](ue_ue.GameMode.md).[CreateDefaultSubobject](ue_ue.GameMode.md#createdefaultsubobject)

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

[GameMode](ue_ue.GameMode.md).[DetachRootComponentFromParent](ue_ue.GameMode.md#detachrootcomponentfromparent)

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

[GameMode](ue_ue.GameMode.md).[DisableInput](ue_ue.GameMode.md#disableinput)

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

[GameMode](ue_ue.GameMode.md).[EnableInput](ue_ue.GameMode.md#enableinput)

#### Defined in

[ue/ue.d.ts:13213](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13213)

___

### EndMatch

▸ **EndMatch**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[EndMatch](ue_ue.GameMode.md#endmatch)

#### Defined in

[ue/ue.d.ts:21279](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21279)

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

[GameMode](ue_ue.GameMode.md).[ExecuteUbergraph](ue_ue.GameMode.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### FindPlayerStart

▸ **FindPlayerStart**(`Player`, `IncomingName`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Player` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |
| `IncomingName` | `string` |

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[FindPlayerStart](ue_ue.GameMode.md#findplayerstart)

#### Defined in

[ue/ue.d.ts:10031](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10031)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[FlushNetDormancy](ue_ue.GameMode.md#flushnetdormancy)

#### Defined in

[ue/ue.d.ts:13214](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13214)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ForceNetUpdate](ue_ue.GameMode.md#forcenetupdate)

#### Defined in

[ue/ue.d.ts:13215](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13215)

___

### GetARSharedWorldGameState

▸ **GetARSharedWorldGameState**(): [`ARSharedWorldGameState`](ue_ue.ARSharedWorldGameState.md)

#### Returns

[`ARSharedWorldGameState`](ue_ue.ARSharedWorldGameState.md)

#### Defined in

[ue/ue.d.ts:21330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21330)

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

[GameMode](ue_ue.GameMode.md).[GetActorBounds](ue_ue.GameMode.md#getactorbounds)

#### Defined in

[ue/ue.d.ts:13216](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13216)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorEnableCollision](ue_ue.GameMode.md#getactorenablecollision)

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

[GameMode](ue_ue.GameMode.md).[GetActorEyesViewPoint](ue_ue.GameMode.md#getactoreyesviewpoint)

#### Defined in

[ue/ue.d.ts:13218](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13218)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorForwardVector](ue_ue.GameMode.md#getactorforwardvector)

#### Defined in

[ue/ue.d.ts:13219](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13219)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorLabel](ue_ue.GameMode.md#getactorlabel)

#### Defined in

[ue/ue.d.ts:13220](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13220)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorRelativeScale3D](ue_ue.GameMode.md#getactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13221](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13221)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorRightVector](ue_ue.GameMode.md#getactorrightvector)

#### Defined in

[ue/ue.d.ts:13222](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13222)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorScale3D](ue_ue.GameMode.md#getactorscale3d)

#### Defined in

[ue/ue.d.ts:13223](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13223)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorTickInterval](ue_ue.GameMode.md#getactortickinterval)

#### Defined in

[ue/ue.d.ts:13224](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13224)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorTimeDilation](ue_ue.GameMode.md#getactortimedilation)

#### Defined in

[ue/ue.d.ts:13225](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13225)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorUpVector](ue_ue.GameMode.md#getactorupvector)

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

[GameMode](ue_ue.GameMode.md).[GetAllChildActors](ue_ue.GameMode.md#getallchildactors)

#### Defined in

[ue/ue.d.ts:13227](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13227)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetAttachParentActor](ue_ue.GameMode.md#getattachparentactor)

#### Defined in

[ue/ue.d.ts:13229](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13229)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetAttachParentSocketName](ue_ue.GameMode.md#getattachparentsocketname)

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

[GameMode](ue_ue.GameMode.md).[GetAttachedActors](ue_ue.GameMode.md#getattachedactors)

#### Defined in

[ue/ue.d.ts:13228](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13228)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetClass](ue_ue.GameMode.md#getclass)

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

[GameMode](ue_ue.GameMode.md).[GetComponentByClass](ue_ue.GameMode.md#getcomponentbyclass)

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

[GameMode](ue_ue.GameMode.md).[GetComponentsByInterface](ue_ue.GameMode.md#getcomponentsbyinterface)

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

[GameMode](ue_ue.GameMode.md).[GetComponentsByTag](ue_ue.GameMode.md#getcomponentsbytag)

#### Defined in

[ue/ue.d.ts:13233](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13233)

___

### GetDefaultPawnClassForController

▸ **GetDefaultPawnClassForController**(`InController`): [`Class`](ue_ue.Class.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetDefaultPawnClassForController](ue_ue.GameMode.md#getdefaultpawnclassforcontroller)

#### Defined in

[ue/ue.d.ts:10032](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10032)

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

[GameMode](ue_ue.GameMode.md).[GetDistanceTo](ue_ue.GameMode.md#getdistanceto)

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

[GameMode](ue_ue.GameMode.md).[GetDotProductTo](ue_ue.GameMode.md#getdotproductto)

#### Defined in

[ue/ue.d.ts:13235](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13235)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetFolderPath](ue_ue.GameMode.md#getfolderpath)

#### Defined in

[ue/ue.d.ts:13236](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13236)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetGameTimeSinceCreation](ue_ue.GameMode.md#getgametimesincecreation)

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

[GameMode](ue_ue.GameMode.md).[GetHorizontalDistanceTo](ue_ue.GameMode.md#gethorizontaldistanceto)

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

[GameMode](ue_ue.GameMode.md).[GetHorizontalDotProductTo](ue_ue.GameMode.md#gethorizontaldotproductto)

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

[GameMode](ue_ue.GameMode.md).[GetInputAxisKeyValue](ue_ue.GameMode.md#getinputaxiskeyvalue)

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

[GameMode](ue_ue.GameMode.md).[GetInputAxisValue](ue_ue.GameMode.md#getinputaxisvalue)

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

[GameMode](ue_ue.GameMode.md).[GetInputVectorAxisValue](ue_ue.GameMode.md#getinputvectoraxisvalue)

#### Defined in

[ue/ue.d.ts:13242](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13242)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetInstigator](ue_ue.GameMode.md#getinstigator)

#### Defined in

[ue/ue.d.ts:13243](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13243)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetInstigatorController](ue_ue.GameMode.md#getinstigatorcontroller)

#### Defined in

[ue/ue.d.ts:13244](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13244)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetLifeSpan](ue_ue.GameMode.md#getlifespan)

#### Defined in

[ue/ue.d.ts:13245](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13245)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetLocalRole](ue_ue.GameMode.md#getlocalrole)

#### Defined in

[ue/ue.d.ts:13246](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13246)

___

### GetMatchState

▸ **GetMatchState**(): `string`

#### Returns

`string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetMatchState](ue_ue.GameMode.md#getmatchstate)

#### Defined in

[ue/ue.d.ts:21280](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21280)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetName](ue_ue.GameMode.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetNumPlayers

▸ **GetNumPlayers**(): `number`

#### Returns

`number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetNumPlayers](ue_ue.GameMode.md#getnumplayers)

#### Defined in

[ue/ue.d.ts:10033](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10033)

___

### GetNumSpectators

▸ **GetNumSpectators**(): `number`

#### Returns

`number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetNumSpectators](ue_ue.GameMode.md#getnumspectators)

#### Defined in

[ue/ue.d.ts:10034](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10034)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetOuter](ue_ue.GameMode.md#getouter)

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

[GameMode](ue_ue.GameMode.md).[GetOverlappingActors](ue_ue.GameMode.md#getoverlappingactors)

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

[GameMode](ue_ue.GameMode.md).[GetOverlappingComponents](ue_ue.GameMode.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:13248](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13248)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetOwner](ue_ue.GameMode.md#getowner)

#### Defined in

[ue/ue.d.ts:13249](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13249)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetParentActor](ue_ue.GameMode.md#getparentactor)

#### Defined in

[ue/ue.d.ts:13250](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13250)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetParentComponent](ue_ue.GameMode.md#getparentcomponent)

#### Defined in

[ue/ue.d.ts:13251](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13251)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetRemoteRole](ue_ue.GameMode.md#getremoterole)

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

[GameMode](ue_ue.GameMode.md).[GetSquaredDistanceTo](ue_ue.GameMode.md#getsquareddistanceto)

#### Defined in

[ue/ue.d.ts:13253](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13253)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetTickableWhenPaused](ue_ue.GameMode.md#gettickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13254](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13254)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetTransform](ue_ue.GameMode.md#gettransform)

#### Defined in

[ue/ue.d.ts:13255](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13255)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetVelocity](ue_ue.GameMode.md#getvelocity)

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

[GameMode](ue_ue.GameMode.md).[GetVerticalDistanceTo](ue_ue.GameMode.md#getverticaldistanceto)

#### Defined in

[ue/ue.d.ts:13257](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13257)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetWorld](ue_ue.GameMode.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### HandleStartingNewPlayer

▸ **HandleStartingNewPlayer**(`NewPlayer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[HandleStartingNewPlayer](ue_ue.GameMode.md#handlestartingnewplayer)

#### Defined in

[ue/ue.d.ts:10035](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10035)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[HasAuthority](ue_ue.GameMode.md#hasauthority)

#### Defined in

[ue/ue.d.ts:13258](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13258)

___

### HasMatchEnded

▸ **HasMatchEnded**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[HasMatchEnded](ue_ue.GameMode.md#hasmatchended)

#### Defined in

[ue/ue.d.ts:21281](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21281)

___

### HasMatchStarted

▸ **HasMatchStarted**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[HasMatchStarted](ue_ue.GameMode.md#hasmatchstarted)

#### Defined in

[ue/ue.d.ts:10036](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10036)

___

### InitStartSpot

▸ **InitStartSpot**(`StartSpot`, `NewPlayer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StartSpot` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `NewPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[InitStartSpot](ue_ue.GameMode.md#initstartspot)

#### Defined in

[ue/ue.d.ts:10038](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10038)

___

### InitializeHUDForPlayer

▸ **InitializeHUDForPlayer**(`NewPlayer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[InitializeHUDForPlayer](ue_ue.GameMode.md#initializehudforplayer)

#### Defined in

[ue/ue.d.ts:10037](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10037)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[IsActorBeingDestroyed](ue_ue.GameMode.md#isactorbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13259](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13259)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[IsActorTickEnabled](ue_ue.GameMode.md#isactortickenabled)

#### Defined in

[ue/ue.d.ts:13260](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13260)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[IsChildActor](ue_ue.GameMode.md#ischildactor)

#### Defined in

[ue/ue.d.ts:13261](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13261)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[IsEditable](ue_ue.GameMode.md#iseditable)

#### Defined in

[ue/ue.d.ts:13262](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13262)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[IsHiddenEd](ue_ue.GameMode.md#ishiddened)

#### Defined in

[ue/ue.d.ts:13263](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13263)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[IsHiddenEdAtStartup](ue_ue.GameMode.md#ishiddenedatstartup)

#### Defined in

[ue/ue.d.ts:13264](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13264)

___

### IsMatchInProgress

▸ **IsMatchInProgress**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[IsMatchInProgress](ue_ue.GameMode.md#ismatchinprogress)

#### Defined in

[ue/ue.d.ts:21282](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21282)

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

[GameMode](ue_ue.GameMode.md).[IsOverlappingActor](ue_ue.GameMode.md#isoverlappingactor)

#### Defined in

[ue/ue.d.ts:13265](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13265)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[IsSelectable](ue_ue.GameMode.md#isselectable)

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

[GameMode](ue_ue.GameMode.md).[IsTemporarilyHiddenInEditor](ue_ue.GameMode.md#istemporarilyhiddenineditor)

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

[GameMode](ue_ue.GameMode.md).[K2_AddActorLocalOffset](ue_ue.GameMode.md#k2_addactorlocaloffset)

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

[GameMode](ue_ue.GameMode.md).[K2_AddActorLocalRotation](ue_ue.GameMode.md#k2_addactorlocalrotation)

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

[GameMode](ue_ue.GameMode.md).[K2_AddActorLocalTransform](ue_ue.GameMode.md#k2_addactorlocaltransform)

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

[GameMode](ue_ue.GameMode.md).[K2_AddActorWorldOffset](ue_ue.GameMode.md#k2_addactorworldoffset)

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

[GameMode](ue_ue.GameMode.md).[K2_AddActorWorldRotation](ue_ue.GameMode.md#k2_addactorworldrotation)

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

[GameMode](ue_ue.GameMode.md).[K2_AddActorWorldTransform](ue_ue.GameMode.md#k2_addactorworldtransform)

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

[GameMode](ue_ue.GameMode.md).[K2_AttachRootComponentTo](ue_ue.GameMode.md#k2_attachrootcomponentto)

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

[GameMode](ue_ue.GameMode.md).[K2_AttachRootComponentToActor](ue_ue.GameMode.md#k2_attachrootcomponenttoactor)

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

[GameMode](ue_ue.GameMode.md).[K2_AttachToActor](ue_ue.GameMode.md#k2_attachtoactor)

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

[GameMode](ue_ue.GameMode.md).[K2_AttachToComponent](ue_ue.GameMode.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:13277](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13277)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[K2_DestroyActor](ue_ue.GameMode.md#k2_destroyactor)

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

[GameMode](ue_ue.GameMode.md).[K2_DestroyComponent](ue_ue.GameMode.md#k2_destroycomponent)

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

[GameMode](ue_ue.GameMode.md).[K2_DetachFromActor](ue_ue.GameMode.md#k2_detachfromactor)

#### Defined in

[ue/ue.d.ts:13280](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13280)

___

### K2\_FindPlayerStart

▸ **K2_FindPlayerStart**(`Player`, `IncomingName?`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Player` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |
| `IncomingName?` | `string` |

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[K2_FindPlayerStart](ue_ue.GameMode.md#k2_findplayerstart)

#### Defined in

[ue/ue.d.ts:10039](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10039)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[K2_GetActorLocation](ue_ue.GameMode.md#k2_getactorlocation)

#### Defined in

[ue/ue.d.ts:13281](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13281)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[K2_GetActorRotation](ue_ue.GameMode.md#k2_getactorrotation)

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

[GameMode](ue_ue.GameMode.md).[K2_GetComponentsByClass](ue_ue.GameMode.md#k2_getcomponentsbyclass)

#### Defined in

[ue/ue.d.ts:13283](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13283)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[K2_GetRootComponent](ue_ue.GameMode.md#k2_getrootcomponent)

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

[GameMode](ue_ue.GameMode.md).[K2_OnBecomeViewTarget](ue_ue.GameMode.md#k2_onbecomeviewtarget)

#### Defined in

[ue/ue.d.ts:13285](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13285)

___

### K2\_OnChangeName

▸ **K2_OnChangeName**(`Other`, `NewName`, `bNameChange`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |
| `NewName` | `string` |
| `bNameChange` | `boolean` |

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[K2_OnChangeName](ue_ue.GameMode.md#k2_onchangename)

#### Defined in

[ue/ue.d.ts:10040](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10040)

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

[GameMode](ue_ue.GameMode.md).[K2_OnEndViewTarget](ue_ue.GameMode.md#k2_onendviewtarget)

#### Defined in

[ue/ue.d.ts:13286](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13286)

___

### K2\_OnLogout

▸ **K2_OnLogout**(`ExitingController`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ExitingController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[K2_OnLogout](ue_ue.GameMode.md#k2_onlogout)

#### Defined in

[ue/ue.d.ts:10041](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10041)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[K2_OnReset](ue_ue.GameMode.md#k2_onreset)

#### Defined in

[ue/ue.d.ts:13287](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13287)

___

### K2\_OnRestartPlayer

▸ **K2_OnRestartPlayer**(`NewPlayer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[K2_OnRestartPlayer](ue_ue.GameMode.md#k2_onrestartplayer)

#### Defined in

[ue/ue.d.ts:10042](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10042)

___

### K2\_OnSetMatchState

▸ **K2_OnSetMatchState**(`NewState`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewState` | `string` |

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[K2_OnSetMatchState](ue_ue.GameMode.md#k2_onsetmatchstate)

#### Defined in

[ue/ue.d.ts:21283](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21283)

___

### K2\_OnSwapPlayerControllers

▸ **K2_OnSwapPlayerControllers**(`OldPC`, `NewPC`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OldPC` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `NewPC` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[K2_OnSwapPlayerControllers](ue_ue.GameMode.md#k2_onswapplayercontrollers)

#### Defined in

[ue/ue.d.ts:10043](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10043)

___

### K2\_PostLogin

▸ **K2_PostLogin**(`NewPlayer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[K2_PostLogin](ue_ue.GameMode.md#k2_postlogin)

#### Defined in

[ue/ue.d.ts:10044](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10044)

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

[GameMode](ue_ue.GameMode.md).[K2_SetActorLocation](ue_ue.GameMode.md#k2_setactorlocation)

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

[GameMode](ue_ue.GameMode.md).[K2_SetActorLocationAndRotation](ue_ue.GameMode.md#k2_setactorlocationandrotation)

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

[GameMode](ue_ue.GameMode.md).[K2_SetActorRelativeLocation](ue_ue.GameMode.md#k2_setactorrelativelocation)

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

[GameMode](ue_ue.GameMode.md).[K2_SetActorRelativeRotation](ue_ue.GameMode.md#k2_setactorrelativerotation)

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

[GameMode](ue_ue.GameMode.md).[K2_SetActorRelativeTransform](ue_ue.GameMode.md#k2_setactorrelativetransform)

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

[GameMode](ue_ue.GameMode.md).[K2_SetActorRotation](ue_ue.GameMode.md#k2_setactorrotation)

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

[GameMode](ue_ue.GameMode.md).[K2_SetActorTransform](ue_ue.GameMode.md#k2_setactortransform)

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

[GameMode](ue_ue.GameMode.md).[K2_TeleportTo](ue_ue.GameMode.md#k2_teleportto)

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

[GameMode](ue_ue.GameMode.md).[MakeMIDForMaterial](ue_ue.GameMode.md#makemidformaterial)

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

[GameMode](ue_ue.GameMode.md).[MakeNoise](ue_ue.GameMode.md#makenoise)

#### Defined in

[ue/ue.d.ts:13297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13297)

___

### MustSpectate

▸ **MustSpectate**(`NewPlayerController`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[MustSpectate](ue_ue.GameMode.md#mustspectate)

#### Defined in

[ue/ue.d.ts:10045](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10045)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnRep_AttachmentReplication](ue_ue.GameMode.md#onrep_attachmentreplication)

#### Defined in

[ue/ue.d.ts:13298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13298)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnRep_Instigator](ue_ue.GameMode.md#onrep_instigator)

#### Defined in

[ue/ue.d.ts:13299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13299)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnRep_Owner](ue_ue.GameMode.md#onrep_owner)

#### Defined in

[ue/ue.d.ts:13300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13300)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnRep_ReplicateMovement](ue_ue.GameMode.md#onrep_replicatemovement)

#### Defined in

[ue/ue.d.ts:13302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13302)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnRep_ReplicatedMovement](ue_ue.GameMode.md#onrep_replicatedmovement)

#### Defined in

[ue/ue.d.ts:13301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13301)

___

### PlayerCanRestart

▸ **PlayerCanRestart**(`Player`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Player` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[PlayerCanRestart](ue_ue.GameMode.md#playercanrestart)

#### Defined in

[ue/ue.d.ts:10046](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10046)

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

[GameMode](ue_ue.GameMode.md).[PrestreamTextures](ue_ue.GameMode.md#prestreamtextures)

#### Defined in

[ue/ue.d.ts:13303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13303)

___

### ReadyToEndMatch

▸ **ReadyToEndMatch**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReadyToEndMatch](ue_ue.GameMode.md#readytoendmatch)

#### Defined in

[ue/ue.d.ts:21284](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21284)

___

### ReadyToStartMatch

▸ **ReadyToStartMatch**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReadyToStartMatch](ue_ue.GameMode.md#readytostartmatch)

#### Defined in

[ue/ue.d.ts:21285](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21285)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReceiveActorBeginCursorOver](ue_ue.GameMode.md#receiveactorbegincursorover)

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

[GameMode](ue_ue.GameMode.md).[ReceiveActorBeginOverlap](ue_ue.GameMode.md#receiveactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13305)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReceiveActorEndCursorOver](ue_ue.GameMode.md#receiveactorendcursorover)

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

[GameMode](ue_ue.GameMode.md).[ReceiveActorEndOverlap](ue_ue.GameMode.md#receiveactorendoverlap)

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

[GameMode](ue_ue.GameMode.md).[ReceiveActorOnClicked](ue_ue.GameMode.md#receiveactoronclicked)

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

[GameMode](ue_ue.GameMode.md).[ReceiveActorOnInputTouchBegin](ue_ue.GameMode.md#receiveactoroninputtouchbegin)

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

[GameMode](ue_ue.GameMode.md).[ReceiveActorOnInputTouchEnd](ue_ue.GameMode.md#receiveactoroninputtouchend)

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

[GameMode](ue_ue.GameMode.md).[ReceiveActorOnInputTouchEnter](ue_ue.GameMode.md#receiveactoroninputtouchenter)

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

[GameMode](ue_ue.GameMode.md).[ReceiveActorOnInputTouchLeave](ue_ue.GameMode.md#receiveactoroninputtouchleave)

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

[GameMode](ue_ue.GameMode.md).[ReceiveActorOnReleased](ue_ue.GameMode.md#receiveactoronreleased)

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

[GameMode](ue_ue.GameMode.md).[ReceiveAnyDamage](ue_ue.GameMode.md#receiveanydamage)

#### Defined in

[ue/ue.d.ts:13314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13314)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReceiveBeginPlay](ue_ue.GameMode.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:13315](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13315)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReceiveDestroyed](ue_ue.GameMode.md#receivedestroyed)

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

[GameMode](ue_ue.GameMode.md).[ReceiveEndPlay](ue_ue.GameMode.md#receiveendplay)

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

[GameMode](ue_ue.GameMode.md).[ReceiveHit](ue_ue.GameMode.md#receivehit)

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

[GameMode](ue_ue.GameMode.md).[ReceivePointDamage](ue_ue.GameMode.md#receivepointdamage)

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

[GameMode](ue_ue.GameMode.md).[ReceiveRadialDamage](ue_ue.GameMode.md#receiveradialdamage)

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

[GameMode](ue_ue.GameMode.md).[ReceiveTick](ue_ue.GameMode.md#receivetick)

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

[GameMode](ue_ue.GameMode.md).[RemoveTickPrerequisiteActor](ue_ue.GameMode.md#removetickprerequisiteactor)

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

[GameMode](ue_ue.GameMode.md).[RemoveTickPrerequisiteComponent](ue_ue.GameMode.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13323)

___

### ResetLevel

▸ **ResetLevel**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ResetLevel](ue_ue.GameMode.md#resetlevel)

#### Defined in

[ue/ue.d.ts:10047](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10047)

___

### RestartGame

▸ **RestartGame**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[RestartGame](ue_ue.GameMode.md#restartgame)

#### Defined in

[ue/ue.d.ts:21286](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21286)

___

### RestartPlayer

▸ **RestartPlayer**(`NewPlayer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[RestartPlayer](ue_ue.GameMode.md#restartplayer)

#### Defined in

[ue/ue.d.ts:10048](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10048)

___

### RestartPlayerAtPlayerStart

▸ **RestartPlayerAtPlayerStart**(`NewPlayer`, `StartSpot`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |
| `StartSpot` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[RestartPlayerAtPlayerStart](ue_ue.GameMode.md#restartplayeratplayerstart)

#### Defined in

[ue/ue.d.ts:10049](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10049)

___

### RestartPlayerAtTransform

▸ **RestartPlayerAtTransform**(`NewPlayer`, `SpawnTransform`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |
| `SpawnTransform` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[RestartPlayerAtTransform](ue_ue.GameMode.md#restartplayerattransform)

#### Defined in

[ue/ue.d.ts:10050](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10050)

___

### ReturnToMainMenuHost

▸ **ReturnToMainMenuHost**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReturnToMainMenuHost](ue_ue.GameMode.md#returntomainmenuhost)

#### Defined in

[ue/ue.d.ts:10051](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10051)

___

### Say

▸ **Say**(`Msg`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Msg` | `string` |

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[Say](ue_ue.GameMode.md#say)

#### Defined in

[ue/ue.d.ts:21287](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21287)

___

### SetARSharedWorldData

▸ **SetARSharedWorldData**(`ARWorldData`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ARWorldData` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21331)

___

### SetARWorldSharingIsReady

▸ **SetARWorldSharingIsReady**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21332)

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

[GameMode](ue_ue.GameMode.md).[SetActorEnableCollision](ue_ue.GameMode.md#setactorenablecollision)

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

[GameMode](ue_ue.GameMode.md).[SetActorHiddenInGame](ue_ue.GameMode.md#setactorhiddeningame)

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

[GameMode](ue_ue.GameMode.md).[SetActorLabel](ue_ue.GameMode.md#setactorlabel)

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

[GameMode](ue_ue.GameMode.md).[SetActorRelativeScale3D](ue_ue.GameMode.md#setactorrelativescale3d)

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

[GameMode](ue_ue.GameMode.md).[SetActorScale3D](ue_ue.GameMode.md#setactorscale3d)

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

[GameMode](ue_ue.GameMode.md).[SetActorTickEnabled](ue_ue.GameMode.md#setactortickenabled)

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

[GameMode](ue_ue.GameMode.md).[SetActorTickInterval](ue_ue.GameMode.md#setactortickinterval)

#### Defined in

[ue/ue.d.ts:13330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13330)

___

### SetBandwidthLimit

▸ **SetBandwidthLimit**(`AsyncIOBandwidthLimit`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AsyncIOBandwidthLimit` | `number` |

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[SetBandwidthLimit](ue_ue.GameMode.md#setbandwidthlimit)

#### Defined in

[ue/ue.d.ts:21288](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21288)

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

[GameMode](ue_ue.GameMode.md).[SetFolderPath](ue_ue.GameMode.md#setfolderpath)

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

[GameMode](ue_ue.GameMode.md).[SetIsTemporarilyHiddenInEditor](ue_ue.GameMode.md#setistemporarilyhiddenineditor)

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

[GameMode](ue_ue.GameMode.md).[SetLifeSpan](ue_ue.GameMode.md#setlifespan)

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

[GameMode](ue_ue.GameMode.md).[SetNetDormancy](ue_ue.GameMode.md#setnetdormancy)

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

[GameMode](ue_ue.GameMode.md).[SetOwner](ue_ue.GameMode.md#setowner)

#### Defined in

[ue/ue.d.ts:13335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13335)

___

### SetPreviewImageData

▸ **SetPreviewImageData**(`ImageData`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ImageData` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21333)

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

[GameMode](ue_ue.GameMode.md).[SetReplicateMovement](ue_ue.GameMode.md#setreplicatemovement)

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

[GameMode](ue_ue.GameMode.md).[SetReplicates](ue_ue.GameMode.md#setreplicates)

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

[GameMode](ue_ue.GameMode.md).[SetTickGroup](ue_ue.GameMode.md#settickgroup)

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

[GameMode](ue_ue.GameMode.md).[SetTickableWhenPaused](ue_ue.GameMode.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13338)

___

### ShouldReset

▸ **ShouldReset**(`ActorToReset`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActorToReset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ShouldReset](ue_ue.GameMode.md#shouldreset)

#### Defined in

[ue/ue.d.ts:10052](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10052)

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

[GameMode](ue_ue.GameMode.md).[SnapRootComponentTo](ue_ue.GameMode.md#snaprootcomponentto)

#### Defined in

[ue/ue.d.ts:13340](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13340)

___

### SpawnDefaultPawnAtTransform

▸ **SpawnDefaultPawnAtTransform**(`NewPlayer`, `SpawnTransform`): [`Pawn`](ue_ue.Pawn.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |
| `SpawnTransform` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[SpawnDefaultPawnAtTransform](ue_ue.GameMode.md#spawndefaultpawnattransform)

#### Defined in

[ue/ue.d.ts:10053](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10053)

___

### SpawnDefaultPawnFor

▸ **SpawnDefaultPawnFor**(`NewPlayer`, `StartSpot`): [`Pawn`](ue_ue.Pawn.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |
| `StartSpot` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[SpawnDefaultPawnFor](ue_ue.GameMode.md#spawndefaultpawnfor)

#### Defined in

[ue/ue.d.ts:10054](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10054)

___

### StartMatch

▸ **StartMatch**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[StartMatch](ue_ue.GameMode.md#startmatch)

#### Defined in

[ue/ue.d.ts:21289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21289)

___

### StartPlay

▸ **StartPlay**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[StartPlay](ue_ue.GameMode.md#startplay)

#### Defined in

[ue/ue.d.ts:10055](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10055)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[TearOff](ue_ue.GameMode.md#tearoff)

#### Defined in

[ue/ue.d.ts:13341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13341)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[UserConstructionScript](ue_ue.GameMode.md#userconstructionscript)

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

[GameMode](ue_ue.GameMode.md).[WasRecentlyRendered](ue_ue.GameMode.md#wasrecentlyrendered)

#### Defined in

[ue/ue.d.ts:13343](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13343)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARSharedWorldGameMode`](ue_ue.ARSharedWorldGameMode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARSharedWorldGameMode`](ue_ue.ARSharedWorldGameMode.md)

#### Overrides

[GameMode](ue_ue.GameMode.md).[Find](ue_ue.GameMode.md#find)

#### Defined in

[ue/ue.d.ts:21335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21335)

___

### Load

▸ `Static` **Load**(`InName`): [`ARSharedWorldGameMode`](ue_ue.ARSharedWorldGameMode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARSharedWorldGameMode`](ue_ue.ARSharedWorldGameMode.md)

#### Overrides

[GameMode](ue_ue.GameMode.md).[Load](ue_ue.GameMode.md#load)

#### Defined in

[ue/ue.d.ts:21336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21336)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameMode](ue_ue.GameMode.md).[StaticClass](ue_ue.GameMode.md#staticclass)

#### Defined in

[ue/ue.d.ts:21334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21334)
