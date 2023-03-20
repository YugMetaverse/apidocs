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

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ActorLabel](ue_ue.GameMode.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[AttachmentReplication](ue_ue.GameMode.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[AutoReceiveInput](ue_ue.GameMode.md#autoreceiveinput)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[BlueprintCreatedComponents](ue_ue.GameMode.md#blueprintcreatedcomponents)

___

### BufferSizePerChunk

• **BufferSizePerChunk**: `number`

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[Children](ue_ue.GameMode.md#children)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ControllingMatineeActors](ue_ue.GameMode.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[CustomTimeDilation](ue_ue.GameMode.md#customtimedilation)

___

### DefaultPawnClass

• **DefaultPawnClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[DefaultPawnClass](ue_ue.GameMode.md#defaultpawnclass)

___

### DefaultPlayerName

• **DefaultPlayerName**: `string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[DefaultPlayerName](ue_ue.GameMode.md#defaultplayername)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.GameMode.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### EngineMessageClass

• **EngineMessageClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[EngineMessageClass](ue_ue.GameMode.md#enginemessageclass)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[FolderPath](ue_ue.GameMode.md#folderpath)

___

### GameSession

• **GameSession**: [`GameSession`](ue_ue.GameSession.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GameSession](ue_ue.GameMode.md#gamesession)

___

### GameSessionClass

• **GameSessionClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GameSessionClass](ue_ue.GameMode.md#gamesessionclass)

___

### GameState

• **GameState**: [`GameStateBase`](ue_ue.GameStateBase.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GameState](ue_ue.GameMode.md#gamestate)

___

### GameStateClass

• **GameStateClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GameStateClass](ue_ue.GameMode.md#gamestateclass)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GroupActor](ue_ue.GameMode.md#groupactor)

___

### HUDClass

• **HUDClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[HUDClass](ue_ue.GameMode.md#hudclass)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[HiddenEditorViews](ue_ue.GameMode.md#hiddeneditorviews)

___

### InactivePlayerArray

• **InactivePlayerArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PlayerState`](ue_ue.PlayerState.md)\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[InactivePlayerArray](ue_ue.GameMode.md#inactiveplayerarray)

___

### InactivePlayerStateLifeSpan

• **InactivePlayerStateLifeSpan**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[InactivePlayerStateLifeSpan](ue_ue.GameMode.md#inactiveplayerstatelifespan)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[InitialLifeSpan](ue_ue.GameMode.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[InputComponent](ue_ue.GameMode.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[InputPriority](ue_ue.GameMode.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[InstanceComponents](ue_ue.GameMode.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[Instigator](ue_ue.GameMode.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[Layers](ue_ue.GameMode.md#layers)

___

### MatchState

• **MatchState**: `string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[MatchState](ue_ue.GameMode.md#matchstate)

___

### MaxInactivePlayers

• **MaxInactivePlayers**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[MaxInactivePlayers](ue_ue.GameMode.md#maxinactiveplayers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[MinNetUpdateFrequency](ue_ue.GameMode.md#minnetupdatefrequency)

___

### MinRespawnDelay

• **MinRespawnDelay**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[MinRespawnDelay](ue_ue.GameMode.md#minrespawndelay)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NetCullDistanceSquared](ue_ue.GameMode.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NetDormancy](ue_ue.GameMode.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NetDriverName](ue_ue.GameMode.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NetPriority](ue_ue.GameMode.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NetTag](ue_ue.GameMode.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NetUpdateFrequency](ue_ue.GameMode.md#netupdatefrequency)

___

### NumBots

• **NumBots**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NumBots](ue_ue.GameMode.md#numbots)

___

### NumPlayers

• **NumPlayers**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NumPlayers](ue_ue.GameMode.md#numplayers)

___

### NumSpectators

• **NumSpectators**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NumSpectators](ue_ue.GameMode.md#numspectators)

___

### NumTravellingPlayers

• **NumTravellingPlayers**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[NumTravellingPlayers](ue_ue.GameMode.md#numtravellingplayers)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnActorBeginOverlap](ue_ue.GameMode.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnActorEndOverlap](ue_ue.GameMode.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnActorHit](ue_ue.GameMode.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnBeginCursorOver](ue_ue.GameMode.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnClicked](ue_ue.GameMode.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnDestroyed](ue_ue.GameMode.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnEndCursorOver](ue_ue.GameMode.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnEndPlay](ue_ue.GameMode.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnInputTouchBegin](ue_ue.GameMode.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnInputTouchEnd](ue_ue.GameMode.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnInputTouchEnter](ue_ue.GameMode.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnInputTouchLeave](ue_ue.GameMode.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnReleased](ue_ue.GameMode.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnTakeAnyDamage](ue_ue.GameMode.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnTakePointDamage](ue_ue.GameMode.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnTakeRadialDamage](ue_ue.GameMode.md#ontakeradialdamage)

___

### OptionsString

• **OptionsString**: `string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OptionsString](ue_ue.GameMode.md#optionsstring)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[Owner](ue_ue.GameMode.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ParentComponent](ue_ue.GameMode.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ParentComponentActor](ue_ue.GameMode.md#parentcomponentactor)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[PivotOffset](ue_ue.GameMode.md#pivotoffset)

___

### PlayerControllerClass

• **PlayerControllerClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[PlayerControllerClass](ue_ue.GameMode.md#playercontrollerclass)

___

### PlayerStateClass

• **PlayerStateClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[PlayerStateClass](ue_ue.GameMode.md#playerstateclass)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[PrimaryActorTick](ue_ue.GameMode.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[RemoteRole](ue_ue.GameMode.md#remoterole)

___

### ReplaySpectatorPlayerControllerClass

• **ReplaySpectatorPlayerControllerClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReplaySpectatorPlayerControllerClass](ue_ue.GameMode.md#replayspectatorplayercontrollerclass)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReplicatedMovement](ue_ue.GameMode.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[Role](ue_ue.GameMode.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[RootComponent](ue_ue.GameMode.md#rootcomponent)

___

### ServerStatReplicator

• **ServerStatReplicator**: [`ServerStatReplicator`](ue_ue.ServerStatReplicator.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ServerStatReplicator](ue_ue.GameMode.md#serverstatreplicator)

___

### ServerStatReplicatorClass

• **ServerStatReplicatorClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ServerStatReplicatorClass](ue_ue.GameMode.md#serverstatreplicatorclass)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[SpawnCollisionHandlingMethod](ue_ue.GameMode.md#spawncollisionhandlingmethod)

___

### SpectatorClass

• **SpectatorClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[SpectatorClass](ue_ue.GameMode.md#spectatorclass)

___

### SpriteComponent

• **SpriteComponent**: [`BillboardComponent`](ue_ue.BillboardComponent.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[SpriteComponent](ue_ue.GameMode.md#spritecomponent)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[SpriteScale](ue_ue.GameMode.md#spritescale)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GameMode](ue_ue.GameMode.md).[Tags](ue_ue.GameMode.md#tags)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.GameMode.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_ARSharedWorldGameMode\_\_

• **\_\_tid\_ARSharedWorldGameMode\_\_**: `boolean`

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[__tid_Actor__](ue_ue.GameMode.md#__tid_actor__)

___

### \_\_tid\_GameModeBase\_\_

• **\_\_tid\_GameModeBase\_\_**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[__tid_GameModeBase__](ue_ue.GameMode.md#__tid_gamemodebase__)

___

### \_\_tid\_GameMode\_\_

• **\_\_tid\_GameMode\_\_**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[__tid_GameMode__](ue_ue.GameMode.md#__tid_gamemode__)

___

### \_\_tid\_Info\_\_

• **\_\_tid\_Info\_\_**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[__tid_Info__](ue_ue.GameMode.md#__tid_info__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[__tid_Object__](ue_ue.GameMode.md#__tid_object__)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bActorEnableCollision](ue_ue.GameMode.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bActorIsBeingDestroyed](ue_ue.GameMode.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bActorLabelEditable](ue_ue.GameMode.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bActorSeamlessTraveled](ue_ue.GameMode.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.GameMode.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bAllowTickBeforeBeginPlay](ue_ue.GameMode.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bAlwaysRelevant](ue_ue.GameMode.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bAutoDestroyWhenFinished](ue_ue.GameMode.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bBlockInput](ue_ue.GameMode.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bCanBeDamaged](ue_ue.GameMode.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bCanBeInCluster](ue_ue.GameMode.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bCollideWhenPlacing](ue_ue.GameMode.md#bcollidewhenplacing)

___

### bDelayedStart

• **bDelayedStart**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bDelayedStart](ue_ue.GameMode.md#bdelayedstart)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bEditable](ue_ue.GameMode.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bEnableAutoLODGeneration](ue_ue.GameMode.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bExchangedRoles](ue_ue.GameMode.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bFindCameraComponentWhenViewTarget](ue_ue.GameMode.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.GameMode.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHandleDedicatedServerReplays

• **bHandleDedicatedServerReplays**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bHandleDedicatedServerReplays](ue_ue.GameMode.md#bhandlededicatedserverreplays)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bHidden](ue_ue.GameMode.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bHiddenEd](ue_ue.GameMode.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bHiddenEdLayer](ue_ue.GameMode.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bHiddenEdLevel](ue_ue.GameMode.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bHiddenEdTemporary](ue_ue.GameMode.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bIgnoresOriginShifting](ue_ue.GameMode.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bIsEditorOnlyActor](ue_ue.GameMode.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bIsEditorPreviewActor](ue_ue.GameMode.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bListedInSceneOutliner](ue_ue.GameMode.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bLockLocation](ue_ue.GameMode.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bNetLoadOnClient](ue_ue.GameMode.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bNetStartup](ue_ue.GameMode.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bNetTemporary](ue_ue.GameMode.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bNetUseOwnerRelevancy](ue_ue.GameMode.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bOnlyRelevantToOwner](ue_ue.GameMode.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bOptimizeBPComponentData](ue_ue.GameMode.md#boptimizebpcomponentdata)

___

### bPauseable

• **bPauseable**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bPauseable](ue_ue.GameMode.md#bpauseable)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bRelevantForLevelBounds](ue_ue.GameMode.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bRelevantForNetworkReplays](ue_ue.GameMode.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bReplayRewindable](ue_ue.GameMode.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bReplicateMovement](ue_ue.GameMode.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bReplicates](ue_ue.GameMode.md#breplicates)

___

### bStartPlayersAsSpectators

• **bStartPlayersAsSpectators**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bStartPlayersAsSpectators](ue_ue.GameMode.md#bstartplayersasspectators)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bTearOff](ue_ue.GameMode.md#btearoff)

___

### bUseSeamlessTravel

• **bUseSeamlessTravel**: `boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[bUseSeamlessTravel](ue_ue.GameMode.md#buseseamlesstravel)

## Methods

### AbortMatch

▸ **AbortMatch**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[AbortMatch](ue_ue.GameMode.md#abortmatch)

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

___

### EndMatch

▸ **EndMatch**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[EndMatch](ue_ue.GameMode.md#endmatch)

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

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[FlushNetDormancy](ue_ue.GameMode.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ForceNetUpdate](ue_ue.GameMode.md#forcenetupdate)

___

### GetARSharedWorldGameState

▸ **GetARSharedWorldGameState**(): [`ARSharedWorldGameState`](ue_ue.ARSharedWorldGameState.md)

#### Returns

[`ARSharedWorldGameState`](ue_ue.ARSharedWorldGameState.md)

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

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorEnableCollision](ue_ue.GameMode.md#getactorenablecollision)

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

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorForwardVector](ue_ue.GameMode.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorLabel](ue_ue.GameMode.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorRelativeScale3D](ue_ue.GameMode.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorRightVector](ue_ue.GameMode.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorScale3D](ue_ue.GameMode.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorTickInterval](ue_ue.GameMode.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorTimeDilation](ue_ue.GameMode.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetActorUpVector](ue_ue.GameMode.md#getactorupvector)

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

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetAttachParentActor](ue_ue.GameMode.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetAttachParentSocketName](ue_ue.GameMode.md#getattachparentsocketname)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetClass](ue_ue.GameMode.md#getclass)

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

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetFolderPath](ue_ue.GameMode.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetGameTimeSinceCreation](ue_ue.GameMode.md#getgametimesincecreation)

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

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetInstigator](ue_ue.GameMode.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetInstigatorController](ue_ue.GameMode.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetLifeSpan](ue_ue.GameMode.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetLocalRole](ue_ue.GameMode.md#getlocalrole)

___

### GetMatchState

▸ **GetMatchState**(): `string`

#### Returns

`string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetMatchState](ue_ue.GameMode.md#getmatchstate)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetName](ue_ue.GameMode.md#getname)

___

### GetNumPlayers

▸ **GetNumPlayers**(): `number`

#### Returns

`number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetNumPlayers](ue_ue.GameMode.md#getnumplayers)

___

### GetNumSpectators

▸ **GetNumSpectators**(): `number`

#### Returns

`number`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetNumSpectators](ue_ue.GameMode.md#getnumspectators)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetOuter](ue_ue.GameMode.md#getouter)

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

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetOwner](ue_ue.GameMode.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetParentActor](ue_ue.GameMode.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetParentComponent](ue_ue.GameMode.md#getparentcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetRemoteRole](ue_ue.GameMode.md#getremoterole)

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

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetTickableWhenPaused](ue_ue.GameMode.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetTransform](ue_ue.GameMode.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetVelocity](ue_ue.GameMode.md#getvelocity)

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

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[GetWorld](ue_ue.GameMode.md#getworld)

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

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[HasAuthority](ue_ue.GameMode.md#hasauthority)

___

### HasMatchEnded

▸ **HasMatchEnded**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[HasMatchEnded](ue_ue.GameMode.md#hasmatchended)

___

### HasMatchStarted

▸ **HasMatchStarted**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[HasMatchStarted](ue_ue.GameMode.md#hasmatchstarted)

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

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[IsActorBeingDestroyed](ue_ue.GameMode.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[IsActorTickEnabled](ue_ue.GameMode.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[IsChildActor](ue_ue.GameMode.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[IsEditable](ue_ue.GameMode.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[IsHiddenEd](ue_ue.GameMode.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[IsHiddenEdAtStartup](ue_ue.GameMode.md#ishiddenedatstartup)

___

### IsMatchInProgress

▸ **IsMatchInProgress**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[IsMatchInProgress](ue_ue.GameMode.md#ismatchinprogress)

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

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[IsSelectable](ue_ue.GameMode.md#isselectable)

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

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[K2_DestroyActor](ue_ue.GameMode.md#k2_destroyactor)

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

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[K2_GetActorLocation](ue_ue.GameMode.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[K2_GetActorRotation](ue_ue.GameMode.md#k2_getactorrotation)

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

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[GameMode](ue_ue.GameMode.md).[K2_GetRootComponent](ue_ue.GameMode.md#k2_getrootcomponent)

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

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[K2_OnReset](ue_ue.GameMode.md#k2_onreset)

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

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnRep_AttachmentReplication](ue_ue.GameMode.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnRep_Instigator](ue_ue.GameMode.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnRep_Owner](ue_ue.GameMode.md#onrep_owner)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnRep_ReplicateMovement](ue_ue.GameMode.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[OnRep_ReplicatedMovement](ue_ue.GameMode.md#onrep_replicatedmovement)

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

___

### ReadyToEndMatch

▸ **ReadyToEndMatch**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReadyToEndMatch](ue_ue.GameMode.md#readytoendmatch)

___

### ReadyToStartMatch

▸ **ReadyToStartMatch**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReadyToStartMatch](ue_ue.GameMode.md#readytostartmatch)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReceiveActorBeginCursorOver](ue_ue.GameMode.md#receiveactorbegincursorover)

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

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReceiveActorEndCursorOver](ue_ue.GameMode.md#receiveactorendcursorover)

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

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReceiveBeginPlay](ue_ue.GameMode.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReceiveDestroyed](ue_ue.GameMode.md#receivedestroyed)

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

___

### ResetLevel

▸ **ResetLevel**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ResetLevel](ue_ue.GameMode.md#resetlevel)

___

### RestartGame

▸ **RestartGame**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[RestartGame](ue_ue.GameMode.md#restartgame)

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

___

### ReturnToMainMenuHost

▸ **ReturnToMainMenuHost**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[ReturnToMainMenuHost](ue_ue.GameMode.md#returntomainmenuhost)

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

___

### SetARSharedWorldData

▸ **SetARSharedWorldData**(`ARWorldData`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ARWorldData` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`void`

___

### SetARWorldSharingIsReady

▸ **SetARWorldSharingIsReady**(): `void`

#### Returns

`void`

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

___

### SetPreviewImageData

▸ **SetPreviewImageData**(`ImageData`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ImageData` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`void`

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

___

### StartMatch

▸ **StartMatch**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[StartMatch](ue_ue.GameMode.md#startmatch)

___

### StartPlay

▸ **StartPlay**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[StartPlay](ue_ue.GameMode.md#startplay)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[TearOff](ue_ue.GameMode.md#tearoff)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[GameMode](ue_ue.GameMode.md).[UserConstructionScript](ue_ue.GameMode.md#userconstructionscript)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameMode](ue_ue.GameMode.md).[StaticClass](ue_ue.GameMode.md#staticclass)
