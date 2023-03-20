[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GameModeBase

# Class: GameModeBase

[ue/ue](../modules/ue_ue.md).GameModeBase

## Hierarchy

- [`Info`](ue_ue.Info.md)

  ↳ **`GameModeBase`**

  ↳↳ [`GameMode`](ue_ue.GameMode.md)

  ↳↳ [`FunctionalTestGameMode`](ue_ue.FunctionalTestGameMode.md)

  ↳↳ [`puerts_unreal_demoGameModeBase`](ue_ue.puerts_unreal_demoGameModeBase.md)

  ↳↳ [`TsTestGameMode_C`](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md)

## Table of contents

### Constructors

- [constructor](ue_ue.GameModeBase.md#constructor)

### Properties

- [ActorLabel](ue_ue.GameModeBase.md#actorlabel)
- [AttachmentReplication](ue_ue.GameModeBase.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.GameModeBase.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.GameModeBase.md#blueprintcreatedcomponents)
- [Children](ue_ue.GameModeBase.md#children)
- [ControllingMatineeActors](ue_ue.GameModeBase.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.GameModeBase.md#customtimedilation)
- [DefaultPawnClass](ue_ue.GameModeBase.md#defaultpawnclass)
- [DefaultPlayerName](ue_ue.GameModeBase.md#defaultplayername)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.GameModeBase.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.GameModeBase.md#folderpath)
- [GameSession](ue_ue.GameModeBase.md#gamesession)
- [GameSessionClass](ue_ue.GameModeBase.md#gamesessionclass)
- [GameState](ue_ue.GameModeBase.md#gamestate)
- [GameStateClass](ue_ue.GameModeBase.md#gamestateclass)
- [GroupActor](ue_ue.GameModeBase.md#groupactor)
- [HUDClass](ue_ue.GameModeBase.md#hudclass)
- [HiddenEditorViews](ue_ue.GameModeBase.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.GameModeBase.md#initiallifespan)
- [InputComponent](ue_ue.GameModeBase.md#inputcomponent)
- [InputPriority](ue_ue.GameModeBase.md#inputpriority)
- [InstanceComponents](ue_ue.GameModeBase.md#instancecomponents)
- [Instigator](ue_ue.GameModeBase.md#instigator)
- [Layers](ue_ue.GameModeBase.md#layers)
- [MinNetUpdateFrequency](ue_ue.GameModeBase.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.GameModeBase.md#netculldistancesquared)
- [NetDormancy](ue_ue.GameModeBase.md#netdormancy)
- [NetDriverName](ue_ue.GameModeBase.md#netdrivername)
- [NetPriority](ue_ue.GameModeBase.md#netpriority)
- [NetTag](ue_ue.GameModeBase.md#nettag)
- [NetUpdateFrequency](ue_ue.GameModeBase.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.GameModeBase.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.GameModeBase.md#onactorendoverlap)
- [OnActorHit](ue_ue.GameModeBase.md#onactorhit)
- [OnBeginCursorOver](ue_ue.GameModeBase.md#onbegincursorover)
- [OnClicked](ue_ue.GameModeBase.md#onclicked)
- [OnDestroyed](ue_ue.GameModeBase.md#ondestroyed)
- [OnEndCursorOver](ue_ue.GameModeBase.md#onendcursorover)
- [OnEndPlay](ue_ue.GameModeBase.md#onendplay)
- [OnInputTouchBegin](ue_ue.GameModeBase.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.GameModeBase.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.GameModeBase.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.GameModeBase.md#oninputtouchleave)
- [OnReleased](ue_ue.GameModeBase.md#onreleased)
- [OnTakeAnyDamage](ue_ue.GameModeBase.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.GameModeBase.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.GameModeBase.md#ontakeradialdamage)
- [OptionsString](ue_ue.GameModeBase.md#optionsstring)
- [Owner](ue_ue.GameModeBase.md#owner)
- [ParentComponent](ue_ue.GameModeBase.md#parentcomponent)
- [ParentComponentActor](ue_ue.GameModeBase.md#parentcomponentactor)
- [PivotOffset](ue_ue.GameModeBase.md#pivotoffset)
- [PlayerControllerClass](ue_ue.GameModeBase.md#playercontrollerclass)
- [PlayerStateClass](ue_ue.GameModeBase.md#playerstateclass)
- [PrimaryActorTick](ue_ue.GameModeBase.md#primaryactortick)
- [RemoteRole](ue_ue.GameModeBase.md#remoterole)
- [ReplaySpectatorPlayerControllerClass](ue_ue.GameModeBase.md#replayspectatorplayercontrollerclass)
- [ReplicatedMovement](ue_ue.GameModeBase.md#replicatedmovement)
- [Role](ue_ue.GameModeBase.md#role)
- [RootComponent](ue_ue.GameModeBase.md#rootcomponent)
- [ServerStatReplicator](ue_ue.GameModeBase.md#serverstatreplicator)
- [ServerStatReplicatorClass](ue_ue.GameModeBase.md#serverstatreplicatorclass)
- [SpawnCollisionHandlingMethod](ue_ue.GameModeBase.md#spawncollisionhandlingmethod)
- [SpectatorClass](ue_ue.GameModeBase.md#spectatorclass)
- [SpriteComponent](ue_ue.GameModeBase.md#spritecomponent)
- [SpriteScale](ue_ue.GameModeBase.md#spritescale)
- [Tags](ue_ue.GameModeBase.md#tags)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.GameModeBase.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.GameModeBase.md#__tid_actor__)
- [\_\_tid\_GameModeBase\_\_](ue_ue.GameModeBase.md#__tid_gamemodebase__)
- [\_\_tid\_Info\_\_](ue_ue.GameModeBase.md#__tid_info__)
- [\_\_tid\_Object\_\_](ue_ue.GameModeBase.md#__tid_object__)
- [bActorEnableCollision](ue_ue.GameModeBase.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.GameModeBase.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.GameModeBase.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.GameModeBase.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.GameModeBase.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.GameModeBase.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.GameModeBase.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.GameModeBase.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.GameModeBase.md#bblockinput)
- [bCanBeDamaged](ue_ue.GameModeBase.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.GameModeBase.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.GameModeBase.md#bcollidewhenplacing)
- [bEditable](ue_ue.GameModeBase.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.GameModeBase.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.GameModeBase.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.GameModeBase.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.GameModeBase.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.GameModeBase.md#bhidden)
- [bHiddenEd](ue_ue.GameModeBase.md#bhiddened)
- [bHiddenEdLayer](ue_ue.GameModeBase.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.GameModeBase.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.GameModeBase.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.GameModeBase.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.GameModeBase.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.GameModeBase.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.GameModeBase.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.GameModeBase.md#blocklocation)
- [bNetLoadOnClient](ue_ue.GameModeBase.md#bnetloadonclient)
- [bNetStartup](ue_ue.GameModeBase.md#bnetstartup)
- [bNetTemporary](ue_ue.GameModeBase.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.GameModeBase.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.GameModeBase.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.GameModeBase.md#boptimizebpcomponentdata)
- [bPauseable](ue_ue.GameModeBase.md#bpauseable)
- [bRelevantForLevelBounds](ue_ue.GameModeBase.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.GameModeBase.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.GameModeBase.md#breplayrewindable)
- [bReplicateMovement](ue_ue.GameModeBase.md#breplicatemovement)
- [bReplicates](ue_ue.GameModeBase.md#breplicates)
- [bStartPlayersAsSpectators](ue_ue.GameModeBase.md#bstartplayersasspectators)
- [bTearOff](ue_ue.GameModeBase.md#btearoff)
- [bUseSeamlessTravel](ue_ue.GameModeBase.md#buseseamlesstravel)

### Methods

- [ActorHasTag](ue_ue.GameModeBase.md#actorhastag)
- [AddComponent](ue_ue.GameModeBase.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.GameModeBase.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.GameModeBase.md#addtickprerequisitecomponent)
- [CanSpectate](ue_ue.GameModeBase.md#canspectate)
- [ChangeName](ue_ue.GameModeBase.md#changename)
- [ChoosePlayerStart](ue_ue.GameModeBase.md#chooseplayerstart)
- [CreateDefaultSubobject](ue_ue.GameModeBase.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.GameModeBase.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.GameModeBase.md#disableinput)
- [EnableInput](ue_ue.GameModeBase.md#enableinput)
- [ExecuteUbergraph](ue_ue.GameModeBase.md#executeubergraph)
- [FindPlayerStart](ue_ue.GameModeBase.md#findplayerstart)
- [FlushNetDormancy](ue_ue.GameModeBase.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.GameModeBase.md#forcenetupdate)
- [GetActorBounds](ue_ue.GameModeBase.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.GameModeBase.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.GameModeBase.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.GameModeBase.md#getactorforwardvector)
- [GetActorLabel](ue_ue.GameModeBase.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.GameModeBase.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.GameModeBase.md#getactorrightvector)
- [GetActorScale3D](ue_ue.GameModeBase.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.GameModeBase.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.GameModeBase.md#getactortimedilation)
- [GetActorUpVector](ue_ue.GameModeBase.md#getactorupvector)
- [GetAllChildActors](ue_ue.GameModeBase.md#getallchildactors)
- [GetAttachParentActor](ue_ue.GameModeBase.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.GameModeBase.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.GameModeBase.md#getattachedactors)
- [GetClass](ue_ue.GameModeBase.md#getclass)
- [GetComponentByClass](ue_ue.GameModeBase.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.GameModeBase.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.GameModeBase.md#getcomponentsbytag)
- [GetDefaultPawnClassForController](ue_ue.GameModeBase.md#getdefaultpawnclassforcontroller)
- [GetDistanceTo](ue_ue.GameModeBase.md#getdistanceto)
- [GetDotProductTo](ue_ue.GameModeBase.md#getdotproductto)
- [GetFolderPath](ue_ue.GameModeBase.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.GameModeBase.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.GameModeBase.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.GameModeBase.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.GameModeBase.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.GameModeBase.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.GameModeBase.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.GameModeBase.md#getinstigator)
- [GetInstigatorController](ue_ue.GameModeBase.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.GameModeBase.md#getlifespan)
- [GetLocalRole](ue_ue.GameModeBase.md#getlocalrole)
- [GetName](ue_ue.GameModeBase.md#getname)
- [GetNumPlayers](ue_ue.GameModeBase.md#getnumplayers)
- [GetNumSpectators](ue_ue.GameModeBase.md#getnumspectators)
- [GetOuter](ue_ue.GameModeBase.md#getouter)
- [GetOverlappingActors](ue_ue.GameModeBase.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.GameModeBase.md#getoverlappingcomponents)
- [GetOwner](ue_ue.GameModeBase.md#getowner)
- [GetParentActor](ue_ue.GameModeBase.md#getparentactor)
- [GetParentComponent](ue_ue.GameModeBase.md#getparentcomponent)
- [GetRemoteRole](ue_ue.GameModeBase.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.GameModeBase.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.GameModeBase.md#gettickablewhenpaused)
- [GetTransform](ue_ue.GameModeBase.md#gettransform)
- [GetVelocity](ue_ue.GameModeBase.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.GameModeBase.md#getverticaldistanceto)
- [GetWorld](ue_ue.GameModeBase.md#getworld)
- [HandleStartingNewPlayer](ue_ue.GameModeBase.md#handlestartingnewplayer)
- [HasAuthority](ue_ue.GameModeBase.md#hasauthority)
- [HasMatchStarted](ue_ue.GameModeBase.md#hasmatchstarted)
- [InitStartSpot](ue_ue.GameModeBase.md#initstartspot)
- [InitializeHUDForPlayer](ue_ue.GameModeBase.md#initializehudforplayer)
- [IsActorBeingDestroyed](ue_ue.GameModeBase.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.GameModeBase.md#isactortickenabled)
- [IsChildActor](ue_ue.GameModeBase.md#ischildactor)
- [IsEditable](ue_ue.GameModeBase.md#iseditable)
- [IsHiddenEd](ue_ue.GameModeBase.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.GameModeBase.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.GameModeBase.md#isoverlappingactor)
- [IsSelectable](ue_ue.GameModeBase.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.GameModeBase.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.GameModeBase.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.GameModeBase.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.GameModeBase.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.GameModeBase.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.GameModeBase.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.GameModeBase.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.GameModeBase.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.GameModeBase.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.GameModeBase.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.GameModeBase.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.GameModeBase.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.GameModeBase.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.GameModeBase.md#k2_detachfromactor)
- [K2\_FindPlayerStart](ue_ue.GameModeBase.md#k2_findplayerstart)
- [K2\_GetActorLocation](ue_ue.GameModeBase.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.GameModeBase.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.GameModeBase.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.GameModeBase.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.GameModeBase.md#k2_onbecomeviewtarget)
- [K2\_OnChangeName](ue_ue.GameModeBase.md#k2_onchangename)
- [K2\_OnEndViewTarget](ue_ue.GameModeBase.md#k2_onendviewtarget)
- [K2\_OnLogout](ue_ue.GameModeBase.md#k2_onlogout)
- [K2\_OnReset](ue_ue.GameModeBase.md#k2_onreset)
- [K2\_OnRestartPlayer](ue_ue.GameModeBase.md#k2_onrestartplayer)
- [K2\_OnSwapPlayerControllers](ue_ue.GameModeBase.md#k2_onswapplayercontrollers)
- [K2\_PostLogin](ue_ue.GameModeBase.md#k2_postlogin)
- [K2\_SetActorLocation](ue_ue.GameModeBase.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.GameModeBase.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.GameModeBase.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.GameModeBase.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.GameModeBase.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.GameModeBase.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.GameModeBase.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.GameModeBase.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.GameModeBase.md#makemidformaterial)
- [MakeNoise](ue_ue.GameModeBase.md#makenoise)
- [MustSpectate](ue_ue.GameModeBase.md#mustspectate)
- [OnRep\_AttachmentReplication](ue_ue.GameModeBase.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.GameModeBase.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.GameModeBase.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.GameModeBase.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.GameModeBase.md#onrep_replicatedmovement)
- [PlayerCanRestart](ue_ue.GameModeBase.md#playercanrestart)
- [PrestreamTextures](ue_ue.GameModeBase.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.GameModeBase.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.GameModeBase.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.GameModeBase.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.GameModeBase.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.GameModeBase.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.GameModeBase.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.GameModeBase.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.GameModeBase.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.GameModeBase.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.GameModeBase.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.GameModeBase.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.GameModeBase.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.GameModeBase.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.GameModeBase.md#receiveendplay)
- [ReceiveHit](ue_ue.GameModeBase.md#receivehit)
- [ReceivePointDamage](ue_ue.GameModeBase.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.GameModeBase.md#receiveradialdamage)
- [ReceiveTick](ue_ue.GameModeBase.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.GameModeBase.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.GameModeBase.md#removetickprerequisitecomponent)
- [ResetLevel](ue_ue.GameModeBase.md#resetlevel)
- [RestartPlayer](ue_ue.GameModeBase.md#restartplayer)
- [RestartPlayerAtPlayerStart](ue_ue.GameModeBase.md#restartplayeratplayerstart)
- [RestartPlayerAtTransform](ue_ue.GameModeBase.md#restartplayerattransform)
- [ReturnToMainMenuHost](ue_ue.GameModeBase.md#returntomainmenuhost)
- [SetActorEnableCollision](ue_ue.GameModeBase.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.GameModeBase.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.GameModeBase.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.GameModeBase.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.GameModeBase.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.GameModeBase.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.GameModeBase.md#setactortickinterval)
- [SetFolderPath](ue_ue.GameModeBase.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.GameModeBase.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.GameModeBase.md#setlifespan)
- [SetNetDormancy](ue_ue.GameModeBase.md#setnetdormancy)
- [SetOwner](ue_ue.GameModeBase.md#setowner)
- [SetReplicateMovement](ue_ue.GameModeBase.md#setreplicatemovement)
- [SetReplicates](ue_ue.GameModeBase.md#setreplicates)
- [SetTickGroup](ue_ue.GameModeBase.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.GameModeBase.md#settickablewhenpaused)
- [ShouldReset](ue_ue.GameModeBase.md#shouldreset)
- [SnapRootComponentTo](ue_ue.GameModeBase.md#snaprootcomponentto)
- [SpawnDefaultPawnAtTransform](ue_ue.GameModeBase.md#spawndefaultpawnattransform)
- [SpawnDefaultPawnFor](ue_ue.GameModeBase.md#spawndefaultpawnfor)
- [StartPlay](ue_ue.GameModeBase.md#startplay)
- [TearOff](ue_ue.GameModeBase.md#tearoff)
- [UserConstructionScript](ue_ue.GameModeBase.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.GameModeBase.md#wasrecentlyrendered)
- [Find](ue_ue.GameModeBase.md#find)
- [Load](ue_ue.GameModeBase.md#load)
- [StaticClass](ue_ue.GameModeBase.md#staticclass)

## Constructors

### constructor

• **new GameModeBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Info](ue_ue.Info.md).[constructor](ue_ue.Info.md#constructor)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[Info](ue_ue.Info.md).[ActorLabel](ue_ue.Info.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[Info](ue_ue.Info.md).[AttachmentReplication](ue_ue.Info.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[Info](ue_ue.Info.md).[AutoReceiveInput](ue_ue.Info.md#autoreceiveinput)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Info](ue_ue.Info.md).[BlueprintCreatedComponents](ue_ue.Info.md#blueprintcreatedcomponents)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Info](ue_ue.Info.md).[Children](ue_ue.Info.md#children)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[Info](ue_ue.Info.md).[ControllingMatineeActors](ue_ue.Info.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[Info](ue_ue.Info.md).[CustomTimeDilation](ue_ue.Info.md#customtimedilation)

___

### DefaultPawnClass

• **DefaultPawnClass**: [`Class`](ue_ue.Class.md)

___

### DefaultPlayerName

• **DefaultPlayerName**: `string`

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Info](ue_ue.Info.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.Info.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[Info](ue_ue.Info.md).[FolderPath](ue_ue.Info.md#folderpath)

___

### GameSession

• **GameSession**: [`GameSession`](ue_ue.GameSession.md)

___

### GameSessionClass

• **GameSessionClass**: [`Class`](ue_ue.Class.md)

___

### GameState

• **GameState**: [`GameStateBase`](ue_ue.GameStateBase.md)

___

### GameStateClass

• **GameStateClass**: [`Class`](ue_ue.Class.md)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Info](ue_ue.Info.md).[GroupActor](ue_ue.Info.md#groupactor)

___

### HUDClass

• **HUDClass**: [`Class`](ue_ue.Class.md)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[Info](ue_ue.Info.md).[HiddenEditorViews](ue_ue.Info.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[Info](ue_ue.Info.md).[InitialLifeSpan](ue_ue.Info.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[Info](ue_ue.Info.md).[InputComponent](ue_ue.Info.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[Info](ue_ue.Info.md).[InputPriority](ue_ue.Info.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Info](ue_ue.Info.md).[InstanceComponents](ue_ue.Info.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Info](ue_ue.Info.md).[Instigator](ue_ue.Info.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Info](ue_ue.Info.md).[Layers](ue_ue.Info.md#layers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[Info](ue_ue.Info.md).[MinNetUpdateFrequency](ue_ue.Info.md#minnetupdatefrequency)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[Info](ue_ue.Info.md).[NetCullDistanceSquared](ue_ue.Info.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[Info](ue_ue.Info.md).[NetDormancy](ue_ue.Info.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[Info](ue_ue.Info.md).[NetDriverName](ue_ue.Info.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[Info](ue_ue.Info.md).[NetPriority](ue_ue.Info.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[Info](ue_ue.Info.md).[NetTag](ue_ue.Info.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[Info](ue_ue.Info.md).[NetUpdateFrequency](ue_ue.Info.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Info](ue_ue.Info.md).[OnActorBeginOverlap](ue_ue.Info.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Info](ue_ue.Info.md).[OnActorEndOverlap](ue_ue.Info.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[Info](ue_ue.Info.md).[OnActorHit](ue_ue.Info.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Info](ue_ue.Info.md).[OnBeginCursorOver](ue_ue.Info.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Info](ue_ue.Info.md).[OnClicked](ue_ue.Info.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Info](ue_ue.Info.md).[OnDestroyed](ue_ue.Info.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Info](ue_ue.Info.md).[OnEndCursorOver](ue_ue.Info.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[Info](ue_ue.Info.md).[OnEndPlay](ue_ue.Info.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Info](ue_ue.Info.md).[OnInputTouchBegin](ue_ue.Info.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Info](ue_ue.Info.md).[OnInputTouchEnd](ue_ue.Info.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Info](ue_ue.Info.md).[OnInputTouchEnter](ue_ue.Info.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Info](ue_ue.Info.md).[OnInputTouchLeave](ue_ue.Info.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Info](ue_ue.Info.md).[OnReleased](ue_ue.Info.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Info](ue_ue.Info.md).[OnTakeAnyDamage](ue_ue.Info.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Info](ue_ue.Info.md).[OnTakePointDamage](ue_ue.Info.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Info](ue_ue.Info.md).[OnTakeRadialDamage](ue_ue.Info.md#ontakeradialdamage)

___

### OptionsString

• **OptionsString**: `string`

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Info](ue_ue.Info.md).[Owner](ue_ue.Info.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[Info](ue_ue.Info.md).[ParentComponent](ue_ue.Info.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Info](ue_ue.Info.md).[ParentComponentActor](ue_ue.Info.md#parentcomponentactor)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Info](ue_ue.Info.md).[PivotOffset](ue_ue.Info.md#pivotoffset)

___

### PlayerControllerClass

• **PlayerControllerClass**: [`Class`](ue_ue.Class.md)

___

### PlayerStateClass

• **PlayerStateClass**: [`Class`](ue_ue.Class.md)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[Info](ue_ue.Info.md).[PrimaryActorTick](ue_ue.Info.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Info](ue_ue.Info.md).[RemoteRole](ue_ue.Info.md#remoterole)

___

### ReplaySpectatorPlayerControllerClass

• **ReplaySpectatorPlayerControllerClass**: [`Class`](ue_ue.Class.md)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[Info](ue_ue.Info.md).[ReplicatedMovement](ue_ue.Info.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Info](ue_ue.Info.md).[Role](ue_ue.Info.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Info](ue_ue.Info.md).[RootComponent](ue_ue.Info.md#rootcomponent)

___

### ServerStatReplicator

• **ServerStatReplicator**: [`ServerStatReplicator`](ue_ue.ServerStatReplicator.md)

___

### ServerStatReplicatorClass

• **ServerStatReplicatorClass**: [`Class`](ue_ue.Class.md)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[Info](ue_ue.Info.md).[SpawnCollisionHandlingMethod](ue_ue.Info.md#spawncollisionhandlingmethod)

___

### SpectatorClass

• **SpectatorClass**: [`Class`](ue_ue.Class.md)

___

### SpriteComponent

• **SpriteComponent**: [`BillboardComponent`](ue_ue.BillboardComponent.md)

#### Inherited from

[Info](ue_ue.Info.md).[SpriteComponent](ue_ue.Info.md#spritecomponent)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[Info](ue_ue.Info.md).[SpriteScale](ue_ue.Info.md#spritescale)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Info](ue_ue.Info.md).[Tags](ue_ue.Info.md#tags)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Info](ue_ue.Info.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.Info.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[__tid_Actor__](ue_ue.Info.md#__tid_actor__)

___

### \_\_tid\_GameModeBase\_\_

• **\_\_tid\_GameModeBase\_\_**: `boolean`

___

### \_\_tid\_Info\_\_

• **\_\_tid\_Info\_\_**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[__tid_Info__](ue_ue.Info.md#__tid_info__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[__tid_Object__](ue_ue.Info.md#__tid_object__)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bActorEnableCollision](ue_ue.Info.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bActorIsBeingDestroyed](ue_ue.Info.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bActorLabelEditable](ue_ue.Info.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bActorSeamlessTraveled](ue_ue.Info.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.Info.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bAllowTickBeforeBeginPlay](ue_ue.Info.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bAlwaysRelevant](ue_ue.Info.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bAutoDestroyWhenFinished](ue_ue.Info.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bBlockInput](ue_ue.Info.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bCanBeDamaged](ue_ue.Info.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bCanBeInCluster](ue_ue.Info.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bCollideWhenPlacing](ue_ue.Info.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bEditable](ue_ue.Info.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bEnableAutoLODGeneration](ue_ue.Info.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bExchangedRoles](ue_ue.Info.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bFindCameraComponentWhenViewTarget](ue_ue.Info.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.Info.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bHidden](ue_ue.Info.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bHiddenEd](ue_ue.Info.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bHiddenEdLayer](ue_ue.Info.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bHiddenEdLevel](ue_ue.Info.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bHiddenEdTemporary](ue_ue.Info.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bIgnoresOriginShifting](ue_ue.Info.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bIsEditorOnlyActor](ue_ue.Info.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bIsEditorPreviewActor](ue_ue.Info.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bListedInSceneOutliner](ue_ue.Info.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bLockLocation](ue_ue.Info.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bNetLoadOnClient](ue_ue.Info.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bNetStartup](ue_ue.Info.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bNetTemporary](ue_ue.Info.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bNetUseOwnerRelevancy](ue_ue.Info.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bOnlyRelevantToOwner](ue_ue.Info.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bOptimizeBPComponentData](ue_ue.Info.md#boptimizebpcomponentdata)

___

### bPauseable

• **bPauseable**: `boolean`

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bRelevantForLevelBounds](ue_ue.Info.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bRelevantForNetworkReplays](ue_ue.Info.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bReplayRewindable](ue_ue.Info.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bReplicateMovement](ue_ue.Info.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bReplicates](ue_ue.Info.md#breplicates)

___

### bStartPlayersAsSpectators

• **bStartPlayersAsSpectators**: `boolean`

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bTearOff](ue_ue.Info.md#btearoff)

___

### bUseSeamlessTravel

• **bUseSeamlessTravel**: `boolean`

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

[Info](ue_ue.Info.md).[ActorHasTag](ue_ue.Info.md#actorhastag)

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

[Info](ue_ue.Info.md).[AddComponent](ue_ue.Info.md#addcomponent)

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

[Info](ue_ue.Info.md).[AddTickPrerequisiteActor](ue_ue.Info.md#addtickprerequisiteactor)

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

[Info](ue_ue.Info.md).[AddTickPrerequisiteComponent](ue_ue.Info.md#addtickprerequisitecomponent)

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

___

### ChoosePlayerStart

▸ **ChoosePlayerStart**(`Player`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Player` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |

#### Returns

[`Actor`](ue_ue.Actor.md)

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

[Info](ue_ue.Info.md).[CreateDefaultSubobject](ue_ue.Info.md#createdefaultsubobject)

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

[Info](ue_ue.Info.md).[DetachRootComponentFromParent](ue_ue.Info.md#detachrootcomponentfromparent)

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

[Info](ue_ue.Info.md).[DisableInput](ue_ue.Info.md#disableinput)

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

[Info](ue_ue.Info.md).[EnableInput](ue_ue.Info.md#enableinput)

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

[Info](ue_ue.Info.md).[ExecuteUbergraph](ue_ue.Info.md#executeubergraph)

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

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[Info](ue_ue.Info.md).[FlushNetDormancy](ue_ue.Info.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[Info](ue_ue.Info.md).[ForceNetUpdate](ue_ue.Info.md#forcenetupdate)

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

[Info](ue_ue.Info.md).[GetActorBounds](ue_ue.Info.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Info](ue_ue.Info.md).[GetActorEnableCollision](ue_ue.Info.md#getactorenablecollision)

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

[Info](ue_ue.Info.md).[GetActorEyesViewPoint](ue_ue.Info.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetActorForwardVector](ue_ue.Info.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[Info](ue_ue.Info.md).[GetActorLabel](ue_ue.Info.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetActorRelativeScale3D](ue_ue.Info.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetActorRightVector](ue_ue.Info.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetActorScale3D](ue_ue.Info.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[Info](ue_ue.Info.md).[GetActorTickInterval](ue_ue.Info.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[Info](ue_ue.Info.md).[GetActorTimeDilation](ue_ue.Info.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetActorUpVector](ue_ue.Info.md#getactorupvector)

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

[Info](ue_ue.Info.md).[GetAllChildActors](ue_ue.Info.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetAttachParentActor](ue_ue.Info.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[Info](ue_ue.Info.md).[GetAttachParentSocketName](ue_ue.Info.md#getattachparentsocketname)

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

[Info](ue_ue.Info.md).[GetAttachedActors](ue_ue.Info.md#getattachedactors)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetClass](ue_ue.Info.md#getclass)

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

[Info](ue_ue.Info.md).[GetComponentByClass](ue_ue.Info.md#getcomponentbyclass)

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

[Info](ue_ue.Info.md).[GetComponentsByInterface](ue_ue.Info.md#getcomponentsbyinterface)

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

[Info](ue_ue.Info.md).[GetComponentsByTag](ue_ue.Info.md#getcomponentsbytag)

___

### GetDefaultPawnClassForController

▸ **GetDefaultPawnClassForController**(`InController`): [`Class`](ue_ue.Class.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |

#### Returns

[`Class`](ue_ue.Class.md)

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

[Info](ue_ue.Info.md).[GetDistanceTo](ue_ue.Info.md#getdistanceto)

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

[Info](ue_ue.Info.md).[GetDotProductTo](ue_ue.Info.md#getdotproductto)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[Info](ue_ue.Info.md).[GetFolderPath](ue_ue.Info.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[Info](ue_ue.Info.md).[GetGameTimeSinceCreation](ue_ue.Info.md#getgametimesincecreation)

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

[Info](ue_ue.Info.md).[GetHorizontalDistanceTo](ue_ue.Info.md#gethorizontaldistanceto)

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

[Info](ue_ue.Info.md).[GetHorizontalDotProductTo](ue_ue.Info.md#gethorizontaldotproductto)

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

[Info](ue_ue.Info.md).[GetInputAxisKeyValue](ue_ue.Info.md#getinputaxiskeyvalue)

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

[Info](ue_ue.Info.md).[GetInputAxisValue](ue_ue.Info.md#getinputaxisvalue)

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

[Info](ue_ue.Info.md).[GetInputVectorAxisValue](ue_ue.Info.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetInstigator](ue_ue.Info.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetInstigatorController](ue_ue.Info.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[Info](ue_ue.Info.md).[GetLifeSpan](ue_ue.Info.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetLocalRole](ue_ue.Info.md#getlocalrole)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Info](ue_ue.Info.md).[GetName](ue_ue.Info.md#getname)

___

### GetNumPlayers

▸ **GetNumPlayers**(): `number`

#### Returns

`number`

___

### GetNumSpectators

▸ **GetNumSpectators**(): `number`

#### Returns

`number`

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetOuter](ue_ue.Info.md#getouter)

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

[Info](ue_ue.Info.md).[GetOverlappingActors](ue_ue.Info.md#getoverlappingactors)

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

[Info](ue_ue.Info.md).[GetOverlappingComponents](ue_ue.Info.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetOwner](ue_ue.Info.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetParentActor](ue_ue.Info.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetParentComponent](ue_ue.Info.md#getparentcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetRemoteRole](ue_ue.Info.md#getremoterole)

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

[Info](ue_ue.Info.md).[GetSquaredDistanceTo](ue_ue.Info.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Info](ue_ue.Info.md).[GetTickableWhenPaused](ue_ue.Info.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetTransform](ue_ue.Info.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetVelocity](ue_ue.Info.md#getvelocity)

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

[Info](ue_ue.Info.md).[GetVerticalDistanceTo](ue_ue.Info.md#getverticaldistanceto)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Info](ue_ue.Info.md).[GetWorld](ue_ue.Info.md#getworld)

___

### HandleStartingNewPlayer

▸ **HandleStartingNewPlayer**(`NewPlayer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Info](ue_ue.Info.md).[HasAuthority](ue_ue.Info.md#hasauthority)

___

### HasMatchStarted

▸ **HasMatchStarted**(): `boolean`

#### Returns

`boolean`

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

___

### InitializeHUDForPlayer

▸ **InitializeHUDForPlayer**(`NewPlayer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Info](ue_ue.Info.md).[IsActorBeingDestroyed](ue_ue.Info.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Info](ue_ue.Info.md).[IsActorTickEnabled](ue_ue.Info.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Info](ue_ue.Info.md).[IsChildActor](ue_ue.Info.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Info](ue_ue.Info.md).[IsEditable](ue_ue.Info.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Info](ue_ue.Info.md).[IsHiddenEd](ue_ue.Info.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Info](ue_ue.Info.md).[IsHiddenEdAtStartup](ue_ue.Info.md#ishiddenedatstartup)

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

[Info](ue_ue.Info.md).[IsOverlappingActor](ue_ue.Info.md#isoverlappingactor)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Info](ue_ue.Info.md).[IsSelectable](ue_ue.Info.md#isselectable)

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

[Info](ue_ue.Info.md).[IsTemporarilyHiddenInEditor](ue_ue.Info.md#istemporarilyhiddenineditor)

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

[Info](ue_ue.Info.md).[K2_AddActorLocalOffset](ue_ue.Info.md#k2_addactorlocaloffset)

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

[Info](ue_ue.Info.md).[K2_AddActorLocalRotation](ue_ue.Info.md#k2_addactorlocalrotation)

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

[Info](ue_ue.Info.md).[K2_AddActorLocalTransform](ue_ue.Info.md#k2_addactorlocaltransform)

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

[Info](ue_ue.Info.md).[K2_AddActorWorldOffset](ue_ue.Info.md#k2_addactorworldoffset)

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

[Info](ue_ue.Info.md).[K2_AddActorWorldRotation](ue_ue.Info.md#k2_addactorworldrotation)

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

[Info](ue_ue.Info.md).[K2_AddActorWorldTransform](ue_ue.Info.md#k2_addactorworldtransform)

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

[Info](ue_ue.Info.md).[K2_AttachRootComponentTo](ue_ue.Info.md#k2_attachrootcomponentto)

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

[Info](ue_ue.Info.md).[K2_AttachRootComponentToActor](ue_ue.Info.md#k2_attachrootcomponenttoactor)

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

[Info](ue_ue.Info.md).[K2_AttachToActor](ue_ue.Info.md#k2_attachtoactor)

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

[Info](ue_ue.Info.md).[K2_AttachToComponent](ue_ue.Info.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[Info](ue_ue.Info.md).[K2_DestroyActor](ue_ue.Info.md#k2_destroyactor)

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

[Info](ue_ue.Info.md).[K2_DestroyComponent](ue_ue.Info.md#k2_destroycomponent)

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

[Info](ue_ue.Info.md).[K2_DetachFromActor](ue_ue.Info.md#k2_detachfromactor)

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

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Info](ue_ue.Info.md).[K2_GetActorLocation](ue_ue.Info.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Info](ue_ue.Info.md).[K2_GetActorRotation](ue_ue.Info.md#k2_getactorrotation)

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

[Info](ue_ue.Info.md).[K2_GetComponentsByClass](ue_ue.Info.md#k2_getcomponentsbyclass)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Info](ue_ue.Info.md).[K2_GetRootComponent](ue_ue.Info.md#k2_getrootcomponent)

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

[Info](ue_ue.Info.md).[K2_OnBecomeViewTarget](ue_ue.Info.md#k2_onbecomeviewtarget)

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

[Info](ue_ue.Info.md).[K2_OnEndViewTarget](ue_ue.Info.md#k2_onendviewtarget)

___

### K2\_OnLogout

▸ **K2_OnLogout**(`ExitingController`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ExitingController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |

#### Returns

`void`

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[Info](ue_ue.Info.md).[K2_OnReset](ue_ue.Info.md#k2_onreset)

___

### K2\_OnRestartPlayer

▸ **K2_OnRestartPlayer**(`NewPlayer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |

#### Returns

`void`

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

___

### K2\_PostLogin

▸ **K2_PostLogin**(`NewPlayer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

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

[Info](ue_ue.Info.md).[K2_SetActorLocation](ue_ue.Info.md#k2_setactorlocation)

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

[Info](ue_ue.Info.md).[K2_SetActorLocationAndRotation](ue_ue.Info.md#k2_setactorlocationandrotation)

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

[Info](ue_ue.Info.md).[K2_SetActorRelativeLocation](ue_ue.Info.md#k2_setactorrelativelocation)

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

[Info](ue_ue.Info.md).[K2_SetActorRelativeRotation](ue_ue.Info.md#k2_setactorrelativerotation)

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

[Info](ue_ue.Info.md).[K2_SetActorRelativeTransform](ue_ue.Info.md#k2_setactorrelativetransform)

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

[Info](ue_ue.Info.md).[K2_SetActorRotation](ue_ue.Info.md#k2_setactorrotation)

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

[Info](ue_ue.Info.md).[K2_SetActorTransform](ue_ue.Info.md#k2_setactortransform)

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

[Info](ue_ue.Info.md).[K2_TeleportTo](ue_ue.Info.md#k2_teleportto)

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

[Info](ue_ue.Info.md).[MakeMIDForMaterial](ue_ue.Info.md#makemidformaterial)

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

[Info](ue_ue.Info.md).[MakeNoise](ue_ue.Info.md#makenoise)

___

### MustSpectate

▸ **MustSpectate**(`NewPlayerController`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`boolean`

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[Info](ue_ue.Info.md).[OnRep_AttachmentReplication](ue_ue.Info.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[Info](ue_ue.Info.md).[OnRep_Instigator](ue_ue.Info.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[Info](ue_ue.Info.md).[OnRep_Owner](ue_ue.Info.md#onrep_owner)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Info](ue_ue.Info.md).[OnRep_ReplicateMovement](ue_ue.Info.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Info](ue_ue.Info.md).[OnRep_ReplicatedMovement](ue_ue.Info.md#onrep_replicatedmovement)

___

### PlayerCanRestart

▸ **PlayerCanRestart**(`Player`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Player` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`boolean`

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

[Info](ue_ue.Info.md).[PrestreamTextures](ue_ue.Info.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Info](ue_ue.Info.md).[ReceiveActorBeginCursorOver](ue_ue.Info.md#receiveactorbegincursorover)

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

[Info](ue_ue.Info.md).[ReceiveActorBeginOverlap](ue_ue.Info.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Info](ue_ue.Info.md).[ReceiveActorEndCursorOver](ue_ue.Info.md#receiveactorendcursorover)

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

[Info](ue_ue.Info.md).[ReceiveActorEndOverlap](ue_ue.Info.md#receiveactorendoverlap)

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

[Info](ue_ue.Info.md).[ReceiveActorOnClicked](ue_ue.Info.md#receiveactoronclicked)

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

[Info](ue_ue.Info.md).[ReceiveActorOnInputTouchBegin](ue_ue.Info.md#receiveactoroninputtouchbegin)

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

[Info](ue_ue.Info.md).[ReceiveActorOnInputTouchEnd](ue_ue.Info.md#receiveactoroninputtouchend)

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

[Info](ue_ue.Info.md).[ReceiveActorOnInputTouchEnter](ue_ue.Info.md#receiveactoroninputtouchenter)

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

[Info](ue_ue.Info.md).[ReceiveActorOnInputTouchLeave](ue_ue.Info.md#receiveactoroninputtouchleave)

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

[Info](ue_ue.Info.md).[ReceiveActorOnReleased](ue_ue.Info.md#receiveactoronreleased)

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

[Info](ue_ue.Info.md).[ReceiveAnyDamage](ue_ue.Info.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[Info](ue_ue.Info.md).[ReceiveBeginPlay](ue_ue.Info.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[Info](ue_ue.Info.md).[ReceiveDestroyed](ue_ue.Info.md#receivedestroyed)

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

[Info](ue_ue.Info.md).[ReceiveEndPlay](ue_ue.Info.md#receiveendplay)

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

[Info](ue_ue.Info.md).[ReceiveHit](ue_ue.Info.md#receivehit)

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

[Info](ue_ue.Info.md).[ReceivePointDamage](ue_ue.Info.md#receivepointdamage)

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

[Info](ue_ue.Info.md).[ReceiveRadialDamage](ue_ue.Info.md#receiveradialdamage)

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

[Info](ue_ue.Info.md).[ReceiveTick](ue_ue.Info.md#receivetick)

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

[Info](ue_ue.Info.md).[RemoveTickPrerequisiteActor](ue_ue.Info.md#removetickprerequisiteactor)

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

[Info](ue_ue.Info.md).[RemoveTickPrerequisiteComponent](ue_ue.Info.md#removetickprerequisitecomponent)

___

### ResetLevel

▸ **ResetLevel**(): `void`

#### Returns

`void`

___

### RestartPlayer

▸ **RestartPlayer**(`NewPlayer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |

#### Returns

`void`

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

___

### ReturnToMainMenuHost

▸ **ReturnToMainMenuHost**(): `void`

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

[Info](ue_ue.Info.md).[SetActorEnableCollision](ue_ue.Info.md#setactorenablecollision)

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

[Info](ue_ue.Info.md).[SetActorHiddenInGame](ue_ue.Info.md#setactorhiddeningame)

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

[Info](ue_ue.Info.md).[SetActorLabel](ue_ue.Info.md#setactorlabel)

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

[Info](ue_ue.Info.md).[SetActorRelativeScale3D](ue_ue.Info.md#setactorrelativescale3d)

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

[Info](ue_ue.Info.md).[SetActorScale3D](ue_ue.Info.md#setactorscale3d)

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

[Info](ue_ue.Info.md).[SetActorTickEnabled](ue_ue.Info.md#setactortickenabled)

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

[Info](ue_ue.Info.md).[SetActorTickInterval](ue_ue.Info.md#setactortickinterval)

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

[Info](ue_ue.Info.md).[SetFolderPath](ue_ue.Info.md#setfolderpath)

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

[Info](ue_ue.Info.md).[SetIsTemporarilyHiddenInEditor](ue_ue.Info.md#setistemporarilyhiddenineditor)

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

[Info](ue_ue.Info.md).[SetLifeSpan](ue_ue.Info.md#setlifespan)

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

[Info](ue_ue.Info.md).[SetNetDormancy](ue_ue.Info.md#setnetdormancy)

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

[Info](ue_ue.Info.md).[SetOwner](ue_ue.Info.md#setowner)

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

[Info](ue_ue.Info.md).[SetReplicateMovement](ue_ue.Info.md#setreplicatemovement)

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

[Info](ue_ue.Info.md).[SetReplicates](ue_ue.Info.md#setreplicates)

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

[Info](ue_ue.Info.md).[SetTickGroup](ue_ue.Info.md#settickgroup)

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

[Info](ue_ue.Info.md).[SetTickableWhenPaused](ue_ue.Info.md#settickablewhenpaused)

___

### ShouldReset

▸ **ShouldReset**(`ActorToReset`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActorToReset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`boolean`

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

[Info](ue_ue.Info.md).[SnapRootComponentTo](ue_ue.Info.md#snaprootcomponentto)

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

___

### StartPlay

▸ **StartPlay**(): `void`

#### Returns

`void`

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[Info](ue_ue.Info.md).[TearOff](ue_ue.Info.md#tearoff)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[Info](ue_ue.Info.md).[UserConstructionScript](ue_ue.Info.md#userconstructionscript)

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

[Info](ue_ue.Info.md).[WasRecentlyRendered](ue_ue.Info.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GameModeBase`](ue_ue.GameModeBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GameModeBase`](ue_ue.GameModeBase.md)

#### Overrides

[Info](ue_ue.Info.md).[Find](ue_ue.Info.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GameModeBase`](ue_ue.GameModeBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GameModeBase`](ue_ue.GameModeBase.md)

#### Overrides

[Info](ue_ue.Info.md).[Load](ue_ue.Info.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Info](ue_ue.Info.md).[StaticClass](ue_ue.Info.md#staticclass)
