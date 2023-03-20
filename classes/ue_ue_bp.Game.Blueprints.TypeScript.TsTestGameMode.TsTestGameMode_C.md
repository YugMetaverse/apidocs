[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue\_bp](../modules/ue_ue_bp.md) / [Game](../modules/ue_ue_bp.Game.md) / [Blueprints](../modules/ue_ue_bp.Game.Blueprints.md) / [TypeScript](../modules/ue_ue_bp.Game.Blueprints.TypeScript.md) / [TsTestGameMode](../modules/ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.md) / TsTestGameMode\_C

# Class: TsTestGameMode\_C

[TypeScript](../modules/ue_ue_bp.Game.Blueprints.TypeScript.md).[TsTestGameMode](../modules/ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.md).TsTestGameMode_C

## Hierarchy

- [`GameModeBase`](ue_ue.GameModeBase.md)

  ↳ **`TsTestGameMode_C`**

## Table of contents

### Constructors

- [constructor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#constructor)

### Properties

- [ActorLabel](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#actorlabel)
- [AttachmentReplication](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#attachmentreplication)
- [AutoReceiveInput](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#blueprintcreatedcomponents)
- [Children](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#children)
- [ControllingMatineeActors](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#customtimedilation)
- [DefaultPawnClass](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#defaultpawnclass)
- [DefaultPlayerName](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#defaultplayername)
- [DefaultSceneRoot](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#defaultsceneroot)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#folderpath)
- [GameSession](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#gamesession)
- [GameSessionClass](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#gamesessionclass)
- [GameState](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#gamestate)
- [GameStateClass](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#gamestateclass)
- [GroupActor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#groupactor)
- [HUDClass](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#hudclass)
- [HiddenEditorViews](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#initiallifespan)
- [InputComponent](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#inputcomponent)
- [InputPriority](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#inputpriority)
- [InstanceComponents](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#instancecomponents)
- [Instigator](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#instigator)
- [Layers](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#layers)
- [MinNetUpdateFrequency](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#netculldistancesquared)
- [NetDormancy](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#netdormancy)
- [NetDriverName](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#netdrivername)
- [NetPriority](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#netpriority)
- [NetTag](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#nettag)
- [NetUpdateFrequency](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#onactorendoverlap)
- [OnActorHit](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#onactorhit)
- [OnBeginCursorOver](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#onbegincursorover)
- [OnClicked](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#onclicked)
- [OnDestroyed](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#ondestroyed)
- [OnEndCursorOver](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#onendcursorover)
- [OnEndPlay](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#onendplay)
- [OnInputTouchBegin](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#oninputtouchleave)
- [OnReleased](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#onreleased)
- [OnTakeAnyDamage](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#ontakeradialdamage)
- [OptionsString](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#optionsstring)
- [Owner](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#owner)
- [ParentComponent](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#parentcomponent)
- [ParentComponentActor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#parentcomponentactor)
- [PivotOffset](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#pivotoffset)
- [PlayerControllerClass](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#playercontrollerclass)
- [PlayerStateClass](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#playerstateclass)
- [PrimaryActorTick](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#primaryactortick)
- [RemoteRole](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#remoterole)
- [ReplaySpectatorPlayerControllerClass](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#replayspectatorplayercontrollerclass)
- [ReplicatedMovement](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#replicatedmovement)
- [Role](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#role)
- [RootComponent](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#rootcomponent)
- [ServerStatReplicator](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#serverstatreplicator)
- [ServerStatReplicatorClass](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#serverstatreplicatorclass)
- [SpawnCollisionHandlingMethod](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#spawncollisionhandlingmethod)
- [SpectatorClass](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#spectatorclass)
- [SpriteComponent](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#spritecomponent)
- [SpriteScale](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#spritescale)
- [Tags](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#tags)
- [UberGraphFrame](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#ubergraphframe)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#__tid_actor__)
- [\_\_tid\_GameModeBase\_\_](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#__tid_gamemodebase__)
- [\_\_tid\_Info\_\_](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#__tid_info__)
- [\_\_tid\_Object\_\_](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#__tid_object__)
- [\_\_tid\_TsTestGameMode\_C\_\_](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#__tid_tstestgamemode_c__)
- [bActorEnableCollision](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bblockinput)
- [bCanBeDamaged](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bcollidewhenplacing)
- [bEditable](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#beditable)
- [bEnableAutoLODGeneration](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bhidden)
- [bHiddenEd](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bhiddened)
- [bHiddenEdLayer](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#blocklocation)
- [bNetLoadOnClient](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bnetloadonclient)
- [bNetStartup](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bnetstartup)
- [bNetTemporary](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#boptimizebpcomponentdata)
- [bPauseable](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bpauseable)
- [bRelevantForLevelBounds](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#breplayrewindable)
- [bReplicateMovement](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#breplicatemovement)
- [bReplicates](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#breplicates)
- [bStartPlayersAsSpectators](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#bstartplayersasspectators)
- [bTearOff](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#btearoff)
- [bUseSeamlessTravel](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#buseseamlesstravel)

### Methods

- [ActorHasTag](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#actorhastag)
- [AddComponent](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#addtickprerequisitecomponent)
- [CanSpectate](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#canspectate)
- [ChangeName](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#changename)
- [ChoosePlayerStart](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#chooseplayerstart)
- [CreateDefaultSubobject](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#disableinput)
- [EnableInput](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#enableinput)
- [ExecuteUbergraph](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#executeubergraph)
- [ExecuteUbergraph\_TsTestGameMode](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#executeubergraph_tstestgamemode)
- [FindPlayerStart](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#findplayerstart)
- [FlushNetDormancy](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#forcenetupdate)
- [GetActorBounds](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getactorbounds)
- [GetActorEnableCollision](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getactorforwardvector)
- [GetActorLabel](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getactorrightvector)
- [GetActorScale3D](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getactorscale3d)
- [GetActorTickInterval](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getactortimedilation)
- [GetActorUpVector](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getactorupvector)
- [GetAllChildActors](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getallchildactors)
- [GetAttachParentActor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getattachedactors)
- [GetClass](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getclass)
- [GetComponentByClass](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getcomponentsbytag)
- [GetDefaultPawnClassForController](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getdefaultpawnclassforcontroller)
- [GetDistanceTo](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getdistanceto)
- [GetDotProductTo](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getdotproductto)
- [GetFolderPath](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getinstigator)
- [GetInstigatorController](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getlifespan)
- [GetLocalRole](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getlocalrole)
- [GetName](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getname)
- [GetNumPlayers](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getnumplayers)
- [GetNumSpectators](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getnumspectators)
- [GetOuter](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getouter)
- [GetOverlappingActors](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getoverlappingcomponents)
- [GetOwner](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getowner)
- [GetParentActor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getparentactor)
- [GetParentComponent](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getparentcomponent)
- [GetRemoteRole](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#gettickablewhenpaused)
- [GetTransform](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#gettransform)
- [GetVelocity](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getverticaldistanceto)
- [GetWorld](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#getworld)
- [HandleStartingNewPlayer](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#handlestartingnewplayer)
- [HasAuthority](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#hasauthority)
- [HasMatchStarted](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#hasmatchstarted)
- [InitStartSpot](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#initstartspot)
- [InitializeHUDForPlayer](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#initializehudforplayer)
- [IsActorBeingDestroyed](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#isactortickenabled)
- [IsChildActor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#ischildactor)
- [IsEditable](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#iseditable)
- [IsHiddenEd](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#isoverlappingactor)
- [IsSelectable](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_detachfromactor)
- [K2\_FindPlayerStart](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_findplayerstart)
- [K2\_GetActorLocation](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_onbecomeviewtarget)
- [K2\_OnChangeName](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_onchangename)
- [K2\_OnEndViewTarget](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_onendviewtarget)
- [K2\_OnLogout](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_onlogout)
- [K2\_OnReset](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_onreset)
- [K2\_OnRestartPlayer](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_onrestartplayer)
- [K2\_OnSwapPlayerControllers](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_onswapplayercontrollers)
- [K2\_PostLogin](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_postlogin)
- [K2\_SetActorLocation](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#makemidformaterial)
- [MakeNoise](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#makenoise)
- [MustSpectate](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#mustspectate)
- [OnRep\_AttachmentReplication](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#onrep_instigator)
- [OnRep\_Owner](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#onrep_replicatedmovement)
- [PlayerCanRestart](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#playercanrestart)
- [PrestreamTextures](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receiveendplay)
- [ReceiveHit](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receivehit)
- [ReceivePointDamage](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receiveradialdamage)
- [ReceiveTick](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#removetickprerequisitecomponent)
- [ResetLevel](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#resetlevel)
- [RestartPlayer](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#restartplayer)
- [RestartPlayerAtPlayerStart](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#restartplayeratplayerstart)
- [RestartPlayerAtTransform](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#restartplayerattransform)
- [ReturnToMainMenuHost](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#returntomainmenuhost)
- [SetActorEnableCollision](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#setactorhiddeningame)
- [SetActorLabel](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#setactortickenabled)
- [SetActorTickInterval](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#setactortickinterval)
- [SetFolderPath](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#setlifespan)
- [SetNetDormancy](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#setnetdormancy)
- [SetOwner](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#setowner)
- [SetReplicateMovement](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#setreplicatemovement)
- [SetReplicates](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#setreplicates)
- [SetTickGroup](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#settickgroup)
- [SetTickableWhenPaused](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#settickablewhenpaused)
- [ShouldReset](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#shouldreset)
- [SnapRootComponentTo](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#snaprootcomponentto)
- [SpawnDefaultPawnAtTransform](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#spawndefaultpawnattransform)
- [SpawnDefaultPawnFor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#spawndefaultpawnfor)
- [StartPlay](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#startplay)
- [TearOff](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#tearoff)
- [UserConstructionScript](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#wasrecentlyrendered)
- [Find](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#find)
- [Load](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#load)
- [StaticClass](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md#staticclass)

## Constructors

### constructor

• **new TsTestGameMode_C**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GameModeBase](ue_ue.GameModeBase.md).[constructor](ue_ue.GameModeBase.md#constructor)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[ActorLabel](ue_ue.GameModeBase.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[AttachmentReplication](ue_ue.GameModeBase.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[AutoReceiveInput](ue_ue.GameModeBase.md#autoreceiveinput)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[BlueprintCreatedComponents](ue_ue.GameModeBase.md#blueprintcreatedcomponents)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[Children](ue_ue.GameModeBase.md#children)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[ControllingMatineeActors](ue_ue.GameModeBase.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[CustomTimeDilation](ue_ue.GameModeBase.md#customtimedilation)

___

### DefaultPawnClass

• **DefaultPawnClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[DefaultPawnClass](ue_ue.GameModeBase.md#defaultpawnclass)

___

### DefaultPlayerName

• **DefaultPlayerName**: `string`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[DefaultPlayerName](ue_ue.GameModeBase.md#defaultplayername)

___

### DefaultSceneRoot

• **DefaultSceneRoot**: [`SceneComponent`](ue_ue.SceneComponent.md)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.GameModeBase.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[FolderPath](ue_ue.GameModeBase.md#folderpath)

___

### GameSession

• **GameSession**: [`GameSession`](ue_ue.GameSession.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GameSession](ue_ue.GameModeBase.md#gamesession)

___

### GameSessionClass

• **GameSessionClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GameSessionClass](ue_ue.GameModeBase.md#gamesessionclass)

___

### GameState

• **GameState**: [`GameStateBase`](ue_ue.GameStateBase.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GameState](ue_ue.GameModeBase.md#gamestate)

___

### GameStateClass

• **GameStateClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GameStateClass](ue_ue.GameModeBase.md#gamestateclass)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GroupActor](ue_ue.GameModeBase.md#groupactor)

___

### HUDClass

• **HUDClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[HUDClass](ue_ue.GameModeBase.md#hudclass)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[HiddenEditorViews](ue_ue.GameModeBase.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[InitialLifeSpan](ue_ue.GameModeBase.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[InputComponent](ue_ue.GameModeBase.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[InputPriority](ue_ue.GameModeBase.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[InstanceComponents](ue_ue.GameModeBase.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[Instigator](ue_ue.GameModeBase.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[Layers](ue_ue.GameModeBase.md#layers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[MinNetUpdateFrequency](ue_ue.GameModeBase.md#minnetupdatefrequency)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[NetCullDistanceSquared](ue_ue.GameModeBase.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[NetDormancy](ue_ue.GameModeBase.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[NetDriverName](ue_ue.GameModeBase.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[NetPriority](ue_ue.GameModeBase.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[NetTag](ue_ue.GameModeBase.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[NetUpdateFrequency](ue_ue.GameModeBase.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnActorBeginOverlap](ue_ue.GameModeBase.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnActorEndOverlap](ue_ue.GameModeBase.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnActorHit](ue_ue.GameModeBase.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnBeginCursorOver](ue_ue.GameModeBase.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnClicked](ue_ue.GameModeBase.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnDestroyed](ue_ue.GameModeBase.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnEndCursorOver](ue_ue.GameModeBase.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnEndPlay](ue_ue.GameModeBase.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnInputTouchBegin](ue_ue.GameModeBase.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnInputTouchEnd](ue_ue.GameModeBase.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnInputTouchEnter](ue_ue.GameModeBase.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnInputTouchLeave](ue_ue.GameModeBase.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnReleased](ue_ue.GameModeBase.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnTakeAnyDamage](ue_ue.GameModeBase.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnTakePointDamage](ue_ue.GameModeBase.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnTakeRadialDamage](ue_ue.GameModeBase.md#ontakeradialdamage)

___

### OptionsString

• **OptionsString**: `string`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OptionsString](ue_ue.GameModeBase.md#optionsstring)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[Owner](ue_ue.GameModeBase.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[ParentComponent](ue_ue.GameModeBase.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[ParentComponentActor](ue_ue.GameModeBase.md#parentcomponentactor)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[PivotOffset](ue_ue.GameModeBase.md#pivotoffset)

___

### PlayerControllerClass

• **PlayerControllerClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[PlayerControllerClass](ue_ue.GameModeBase.md#playercontrollerclass)

___

### PlayerStateClass

• **PlayerStateClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[PlayerStateClass](ue_ue.GameModeBase.md#playerstateclass)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[PrimaryActorTick](ue_ue.GameModeBase.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[RemoteRole](ue_ue.GameModeBase.md#remoterole)

___

### ReplaySpectatorPlayerControllerClass

• **ReplaySpectatorPlayerControllerClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[ReplaySpectatorPlayerControllerClass](ue_ue.GameModeBase.md#replayspectatorplayercontrollerclass)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[ReplicatedMovement](ue_ue.GameModeBase.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[Role](ue_ue.GameModeBase.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[RootComponent](ue_ue.GameModeBase.md#rootcomponent)

___

### ServerStatReplicator

• **ServerStatReplicator**: [`ServerStatReplicator`](ue_ue.ServerStatReplicator.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[ServerStatReplicator](ue_ue.GameModeBase.md#serverstatreplicator)

___

### ServerStatReplicatorClass

• **ServerStatReplicatorClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[ServerStatReplicatorClass](ue_ue.GameModeBase.md#serverstatreplicatorclass)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[SpawnCollisionHandlingMethod](ue_ue.GameModeBase.md#spawncollisionhandlingmethod)

___

### SpectatorClass

• **SpectatorClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[SpectatorClass](ue_ue.GameModeBase.md#spectatorclass)

___

### SpriteComponent

• **SpriteComponent**: [`BillboardComponent`](ue_ue.BillboardComponent.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[SpriteComponent](ue_ue.GameModeBase.md#spritecomponent)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[SpriteScale](ue_ue.GameModeBase.md#spritescale)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[Tags](ue_ue.GameModeBase.md#tags)

___

### UberGraphFrame

• **UberGraphFrame**: [`PointerToUberGraphFrame`](ue_ue.PointerToUberGraphFrame.md)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.GameModeBase.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[__tid_Actor__](ue_ue.GameModeBase.md#__tid_actor__)

___

### \_\_tid\_GameModeBase\_\_

• **\_\_tid\_GameModeBase\_\_**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[__tid_GameModeBase__](ue_ue.GameModeBase.md#__tid_gamemodebase__)

___

### \_\_tid\_Info\_\_

• **\_\_tid\_Info\_\_**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[__tid_Info__](ue_ue.GameModeBase.md#__tid_info__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[__tid_Object__](ue_ue.GameModeBase.md#__tid_object__)

___

### \_\_tid\_TsTestGameMode\_C\_\_

• **\_\_tid\_TsTestGameMode\_C\_\_**: `boolean`

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bActorEnableCollision](ue_ue.GameModeBase.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bActorIsBeingDestroyed](ue_ue.GameModeBase.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bActorLabelEditable](ue_ue.GameModeBase.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bActorSeamlessTraveled](ue_ue.GameModeBase.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.GameModeBase.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bAllowTickBeforeBeginPlay](ue_ue.GameModeBase.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bAlwaysRelevant](ue_ue.GameModeBase.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bAutoDestroyWhenFinished](ue_ue.GameModeBase.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bBlockInput](ue_ue.GameModeBase.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bCanBeDamaged](ue_ue.GameModeBase.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bCanBeInCluster](ue_ue.GameModeBase.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bCollideWhenPlacing](ue_ue.GameModeBase.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bEditable](ue_ue.GameModeBase.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bEnableAutoLODGeneration](ue_ue.GameModeBase.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bExchangedRoles](ue_ue.GameModeBase.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bFindCameraComponentWhenViewTarget](ue_ue.GameModeBase.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.GameModeBase.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bHidden](ue_ue.GameModeBase.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bHiddenEd](ue_ue.GameModeBase.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bHiddenEdLayer](ue_ue.GameModeBase.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bHiddenEdLevel](ue_ue.GameModeBase.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bHiddenEdTemporary](ue_ue.GameModeBase.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bIgnoresOriginShifting](ue_ue.GameModeBase.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bIsEditorOnlyActor](ue_ue.GameModeBase.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bIsEditorPreviewActor](ue_ue.GameModeBase.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bListedInSceneOutliner](ue_ue.GameModeBase.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bLockLocation](ue_ue.GameModeBase.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bNetLoadOnClient](ue_ue.GameModeBase.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bNetStartup](ue_ue.GameModeBase.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bNetTemporary](ue_ue.GameModeBase.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bNetUseOwnerRelevancy](ue_ue.GameModeBase.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bOnlyRelevantToOwner](ue_ue.GameModeBase.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bOptimizeBPComponentData](ue_ue.GameModeBase.md#boptimizebpcomponentdata)

___

### bPauseable

• **bPauseable**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bPauseable](ue_ue.GameModeBase.md#bpauseable)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bRelevantForLevelBounds](ue_ue.GameModeBase.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bRelevantForNetworkReplays](ue_ue.GameModeBase.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bReplayRewindable](ue_ue.GameModeBase.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bReplicateMovement](ue_ue.GameModeBase.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bReplicates](ue_ue.GameModeBase.md#breplicates)

___

### bStartPlayersAsSpectators

• **bStartPlayersAsSpectators**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bStartPlayersAsSpectators](ue_ue.GameModeBase.md#bstartplayersasspectators)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bTearOff](ue_ue.GameModeBase.md#btearoff)

___

### bUseSeamlessTravel

• **bUseSeamlessTravel**: `boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[bUseSeamlessTravel](ue_ue.GameModeBase.md#buseseamlesstravel)

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

[GameModeBase](ue_ue.GameModeBase.md).[ActorHasTag](ue_ue.GameModeBase.md#actorhastag)

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

[GameModeBase](ue_ue.GameModeBase.md).[AddComponent](ue_ue.GameModeBase.md#addcomponent)

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

[GameModeBase](ue_ue.GameModeBase.md).[AddTickPrerequisiteActor](ue_ue.GameModeBase.md#addtickprerequisiteactor)

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

[GameModeBase](ue_ue.GameModeBase.md).[AddTickPrerequisiteComponent](ue_ue.GameModeBase.md#addtickprerequisitecomponent)

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

[GameModeBase](ue_ue.GameModeBase.md).[CanSpectate](ue_ue.GameModeBase.md#canspectate)

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

[GameModeBase](ue_ue.GameModeBase.md).[ChangeName](ue_ue.GameModeBase.md#changename)

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

[GameModeBase](ue_ue.GameModeBase.md).[ChoosePlayerStart](ue_ue.GameModeBase.md#chooseplayerstart)

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

[GameModeBase](ue_ue.GameModeBase.md).[CreateDefaultSubobject](ue_ue.GameModeBase.md#createdefaultsubobject)

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

[GameModeBase](ue_ue.GameModeBase.md).[DetachRootComponentFromParent](ue_ue.GameModeBase.md#detachrootcomponentfromparent)

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

[GameModeBase](ue_ue.GameModeBase.md).[DisableInput](ue_ue.GameModeBase.md#disableinput)

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

[GameModeBase](ue_ue.GameModeBase.md).[EnableInput](ue_ue.GameModeBase.md#enableinput)

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

[GameModeBase](ue_ue.GameModeBase.md).[ExecuteUbergraph](ue_ue.GameModeBase.md#executeubergraph)

___

### ExecuteUbergraph\_TsTestGameMode

▸ **ExecuteUbergraph_TsTestGameMode**(`EntryPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryPoint` | `number` |

#### Returns

`void`

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

[GameModeBase](ue_ue.GameModeBase.md).[FindPlayerStart](ue_ue.GameModeBase.md#findplayerstart)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[FlushNetDormancy](ue_ue.GameModeBase.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[ForceNetUpdate](ue_ue.GameModeBase.md#forcenetupdate)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetActorBounds](ue_ue.GameModeBase.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetActorEnableCollision](ue_ue.GameModeBase.md#getactorenablecollision)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetActorEyesViewPoint](ue_ue.GameModeBase.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetActorForwardVector](ue_ue.GameModeBase.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetActorLabel](ue_ue.GameModeBase.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetActorRelativeScale3D](ue_ue.GameModeBase.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetActorRightVector](ue_ue.GameModeBase.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetActorScale3D](ue_ue.GameModeBase.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetActorTickInterval](ue_ue.GameModeBase.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetActorTimeDilation](ue_ue.GameModeBase.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetActorUpVector](ue_ue.GameModeBase.md#getactorupvector)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetAllChildActors](ue_ue.GameModeBase.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetAttachParentActor](ue_ue.GameModeBase.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetAttachParentSocketName](ue_ue.GameModeBase.md#getattachparentsocketname)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetAttachedActors](ue_ue.GameModeBase.md#getattachedactors)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetClass](ue_ue.GameModeBase.md#getclass)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetComponentByClass](ue_ue.GameModeBase.md#getcomponentbyclass)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetComponentsByInterface](ue_ue.GameModeBase.md#getcomponentsbyinterface)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetComponentsByTag](ue_ue.GameModeBase.md#getcomponentsbytag)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetDefaultPawnClassForController](ue_ue.GameModeBase.md#getdefaultpawnclassforcontroller)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetDistanceTo](ue_ue.GameModeBase.md#getdistanceto)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetDotProductTo](ue_ue.GameModeBase.md#getdotproductto)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetFolderPath](ue_ue.GameModeBase.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetGameTimeSinceCreation](ue_ue.GameModeBase.md#getgametimesincecreation)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetHorizontalDistanceTo](ue_ue.GameModeBase.md#gethorizontaldistanceto)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetHorizontalDotProductTo](ue_ue.GameModeBase.md#gethorizontaldotproductto)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetInputAxisKeyValue](ue_ue.GameModeBase.md#getinputaxiskeyvalue)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetInputAxisValue](ue_ue.GameModeBase.md#getinputaxisvalue)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetInputVectorAxisValue](ue_ue.GameModeBase.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetInstigator](ue_ue.GameModeBase.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetInstigatorController](ue_ue.GameModeBase.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetLifeSpan](ue_ue.GameModeBase.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetLocalRole](ue_ue.GameModeBase.md#getlocalrole)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetName](ue_ue.GameModeBase.md#getname)

___

### GetNumPlayers

▸ **GetNumPlayers**(): `number`

#### Returns

`number`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetNumPlayers](ue_ue.GameModeBase.md#getnumplayers)

___

### GetNumSpectators

▸ **GetNumSpectators**(): `number`

#### Returns

`number`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetNumSpectators](ue_ue.GameModeBase.md#getnumspectators)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetOuter](ue_ue.GameModeBase.md#getouter)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetOverlappingActors](ue_ue.GameModeBase.md#getoverlappingactors)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetOverlappingComponents](ue_ue.GameModeBase.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetOwner](ue_ue.GameModeBase.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetParentActor](ue_ue.GameModeBase.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetParentComponent](ue_ue.GameModeBase.md#getparentcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetRemoteRole](ue_ue.GameModeBase.md#getremoterole)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetSquaredDistanceTo](ue_ue.GameModeBase.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetTickableWhenPaused](ue_ue.GameModeBase.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetTransform](ue_ue.GameModeBase.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetVelocity](ue_ue.GameModeBase.md#getvelocity)

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

[GameModeBase](ue_ue.GameModeBase.md).[GetVerticalDistanceTo](ue_ue.GameModeBase.md#getverticaldistanceto)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[GetWorld](ue_ue.GameModeBase.md#getworld)

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

[GameModeBase](ue_ue.GameModeBase.md).[HandleStartingNewPlayer](ue_ue.GameModeBase.md#handlestartingnewplayer)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[HasAuthority](ue_ue.GameModeBase.md#hasauthority)

___

### HasMatchStarted

▸ **HasMatchStarted**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[HasMatchStarted](ue_ue.GameModeBase.md#hasmatchstarted)

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

[GameModeBase](ue_ue.GameModeBase.md).[InitStartSpot](ue_ue.GameModeBase.md#initstartspot)

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

[GameModeBase](ue_ue.GameModeBase.md).[InitializeHUDForPlayer](ue_ue.GameModeBase.md#initializehudforplayer)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[IsActorBeingDestroyed](ue_ue.GameModeBase.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[IsActorTickEnabled](ue_ue.GameModeBase.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[IsChildActor](ue_ue.GameModeBase.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[IsEditable](ue_ue.GameModeBase.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[IsHiddenEd](ue_ue.GameModeBase.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[IsHiddenEdAtStartup](ue_ue.GameModeBase.md#ishiddenedatstartup)

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

[GameModeBase](ue_ue.GameModeBase.md).[IsOverlappingActor](ue_ue.GameModeBase.md#isoverlappingactor)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[IsSelectable](ue_ue.GameModeBase.md#isselectable)

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

[GameModeBase](ue_ue.GameModeBase.md).[IsTemporarilyHiddenInEditor](ue_ue.GameModeBase.md#istemporarilyhiddenineditor)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_AddActorLocalOffset](ue_ue.GameModeBase.md#k2_addactorlocaloffset)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_AddActorLocalRotation](ue_ue.GameModeBase.md#k2_addactorlocalrotation)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_AddActorLocalTransform](ue_ue.GameModeBase.md#k2_addactorlocaltransform)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_AddActorWorldOffset](ue_ue.GameModeBase.md#k2_addactorworldoffset)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_AddActorWorldRotation](ue_ue.GameModeBase.md#k2_addactorworldrotation)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_AddActorWorldTransform](ue_ue.GameModeBase.md#k2_addactorworldtransform)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_AttachRootComponentTo](ue_ue.GameModeBase.md#k2_attachrootcomponentto)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_AttachRootComponentToActor](ue_ue.GameModeBase.md#k2_attachrootcomponenttoactor)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_AttachToActor](ue_ue.GameModeBase.md#k2_attachtoactor)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_AttachToComponent](ue_ue.GameModeBase.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[K2_DestroyActor](ue_ue.GameModeBase.md#k2_destroyactor)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_DestroyComponent](ue_ue.GameModeBase.md#k2_destroycomponent)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_DetachFromActor](ue_ue.GameModeBase.md#k2_detachfromactor)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_FindPlayerStart](ue_ue.GameModeBase.md#k2_findplayerstart)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[K2_GetActorLocation](ue_ue.GameModeBase.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[K2_GetActorRotation](ue_ue.GameModeBase.md#k2_getactorrotation)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_GetComponentsByClass](ue_ue.GameModeBase.md#k2_getcomponentsbyclass)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[K2_GetRootComponent](ue_ue.GameModeBase.md#k2_getrootcomponent)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_OnBecomeViewTarget](ue_ue.GameModeBase.md#k2_onbecomeviewtarget)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_OnChangeName](ue_ue.GameModeBase.md#k2_onchangename)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_OnEndViewTarget](ue_ue.GameModeBase.md#k2_onendviewtarget)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_OnLogout](ue_ue.GameModeBase.md#k2_onlogout)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[K2_OnReset](ue_ue.GameModeBase.md#k2_onreset)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_OnRestartPlayer](ue_ue.GameModeBase.md#k2_onrestartplayer)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_OnSwapPlayerControllers](ue_ue.GameModeBase.md#k2_onswapplayercontrollers)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_PostLogin](ue_ue.GameModeBase.md#k2_postlogin)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_SetActorLocation](ue_ue.GameModeBase.md#k2_setactorlocation)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_SetActorLocationAndRotation](ue_ue.GameModeBase.md#k2_setactorlocationandrotation)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_SetActorRelativeLocation](ue_ue.GameModeBase.md#k2_setactorrelativelocation)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_SetActorRelativeRotation](ue_ue.GameModeBase.md#k2_setactorrelativerotation)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_SetActorRelativeTransform](ue_ue.GameModeBase.md#k2_setactorrelativetransform)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_SetActorRotation](ue_ue.GameModeBase.md#k2_setactorrotation)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_SetActorTransform](ue_ue.GameModeBase.md#k2_setactortransform)

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

[GameModeBase](ue_ue.GameModeBase.md).[K2_TeleportTo](ue_ue.GameModeBase.md#k2_teleportto)

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

[GameModeBase](ue_ue.GameModeBase.md).[MakeMIDForMaterial](ue_ue.GameModeBase.md#makemidformaterial)

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

[GameModeBase](ue_ue.GameModeBase.md).[MakeNoise](ue_ue.GameModeBase.md#makenoise)

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

[GameModeBase](ue_ue.GameModeBase.md).[MustSpectate](ue_ue.GameModeBase.md#mustspectate)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnRep_AttachmentReplication](ue_ue.GameModeBase.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnRep_Instigator](ue_ue.GameModeBase.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnRep_Owner](ue_ue.GameModeBase.md#onrep_owner)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnRep_ReplicateMovement](ue_ue.GameModeBase.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[OnRep_ReplicatedMovement](ue_ue.GameModeBase.md#onrep_replicatedmovement)

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

[GameModeBase](ue_ue.GameModeBase.md).[PlayerCanRestart](ue_ue.GameModeBase.md#playercanrestart)

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

[GameModeBase](ue_ue.GameModeBase.md).[PrestreamTextures](ue_ue.GameModeBase.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[ReceiveActorBeginCursorOver](ue_ue.GameModeBase.md#receiveactorbegincursorover)

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

[GameModeBase](ue_ue.GameModeBase.md).[ReceiveActorBeginOverlap](ue_ue.GameModeBase.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[ReceiveActorEndCursorOver](ue_ue.GameModeBase.md#receiveactorendcursorover)

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

[GameModeBase](ue_ue.GameModeBase.md).[ReceiveActorEndOverlap](ue_ue.GameModeBase.md#receiveactorendoverlap)

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

[GameModeBase](ue_ue.GameModeBase.md).[ReceiveActorOnClicked](ue_ue.GameModeBase.md#receiveactoronclicked)

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

[GameModeBase](ue_ue.GameModeBase.md).[ReceiveActorOnInputTouchBegin](ue_ue.GameModeBase.md#receiveactoroninputtouchbegin)

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

[GameModeBase](ue_ue.GameModeBase.md).[ReceiveActorOnInputTouchEnd](ue_ue.GameModeBase.md#receiveactoroninputtouchend)

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

[GameModeBase](ue_ue.GameModeBase.md).[ReceiveActorOnInputTouchEnter](ue_ue.GameModeBase.md#receiveactoroninputtouchenter)

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

[GameModeBase](ue_ue.GameModeBase.md).[ReceiveActorOnInputTouchLeave](ue_ue.GameModeBase.md#receiveactoroninputtouchleave)

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

[GameModeBase](ue_ue.GameModeBase.md).[ReceiveActorOnReleased](ue_ue.GameModeBase.md#receiveactoronreleased)

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

[GameModeBase](ue_ue.GameModeBase.md).[ReceiveAnyDamage](ue_ue.GameModeBase.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Overrides

[GameModeBase](ue_ue.GameModeBase.md).[ReceiveBeginPlay](ue_ue.GameModeBase.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[ReceiveDestroyed](ue_ue.GameModeBase.md#receivedestroyed)

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

[GameModeBase](ue_ue.GameModeBase.md).[ReceiveEndPlay](ue_ue.GameModeBase.md#receiveendplay)

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

[GameModeBase](ue_ue.GameModeBase.md).[ReceiveHit](ue_ue.GameModeBase.md#receivehit)

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

[GameModeBase](ue_ue.GameModeBase.md).[ReceivePointDamage](ue_ue.GameModeBase.md#receivepointdamage)

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

[GameModeBase](ue_ue.GameModeBase.md).[ReceiveRadialDamage](ue_ue.GameModeBase.md#receiveradialdamage)

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

[GameModeBase](ue_ue.GameModeBase.md).[ReceiveTick](ue_ue.GameModeBase.md#receivetick)

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

[GameModeBase](ue_ue.GameModeBase.md).[RemoveTickPrerequisiteActor](ue_ue.GameModeBase.md#removetickprerequisiteactor)

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

[GameModeBase](ue_ue.GameModeBase.md).[RemoveTickPrerequisiteComponent](ue_ue.GameModeBase.md#removetickprerequisitecomponent)

___

### ResetLevel

▸ **ResetLevel**(): `void`

#### Returns

`void`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[ResetLevel](ue_ue.GameModeBase.md#resetlevel)

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

[GameModeBase](ue_ue.GameModeBase.md).[RestartPlayer](ue_ue.GameModeBase.md#restartplayer)

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

[GameModeBase](ue_ue.GameModeBase.md).[RestartPlayerAtPlayerStart](ue_ue.GameModeBase.md#restartplayeratplayerstart)

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

[GameModeBase](ue_ue.GameModeBase.md).[RestartPlayerAtTransform](ue_ue.GameModeBase.md#restartplayerattransform)

___

### ReturnToMainMenuHost

▸ **ReturnToMainMenuHost**(): `void`

#### Returns

`void`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[ReturnToMainMenuHost](ue_ue.GameModeBase.md#returntomainmenuhost)

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

[GameModeBase](ue_ue.GameModeBase.md).[SetActorEnableCollision](ue_ue.GameModeBase.md#setactorenablecollision)

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

[GameModeBase](ue_ue.GameModeBase.md).[SetActorHiddenInGame](ue_ue.GameModeBase.md#setactorhiddeningame)

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

[GameModeBase](ue_ue.GameModeBase.md).[SetActorLabel](ue_ue.GameModeBase.md#setactorlabel)

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

[GameModeBase](ue_ue.GameModeBase.md).[SetActorRelativeScale3D](ue_ue.GameModeBase.md#setactorrelativescale3d)

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

[GameModeBase](ue_ue.GameModeBase.md).[SetActorScale3D](ue_ue.GameModeBase.md#setactorscale3d)

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

[GameModeBase](ue_ue.GameModeBase.md).[SetActorTickEnabled](ue_ue.GameModeBase.md#setactortickenabled)

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

[GameModeBase](ue_ue.GameModeBase.md).[SetActorTickInterval](ue_ue.GameModeBase.md#setactortickinterval)

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

[GameModeBase](ue_ue.GameModeBase.md).[SetFolderPath](ue_ue.GameModeBase.md#setfolderpath)

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

[GameModeBase](ue_ue.GameModeBase.md).[SetIsTemporarilyHiddenInEditor](ue_ue.GameModeBase.md#setistemporarilyhiddenineditor)

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

[GameModeBase](ue_ue.GameModeBase.md).[SetLifeSpan](ue_ue.GameModeBase.md#setlifespan)

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

[GameModeBase](ue_ue.GameModeBase.md).[SetNetDormancy](ue_ue.GameModeBase.md#setnetdormancy)

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

[GameModeBase](ue_ue.GameModeBase.md).[SetOwner](ue_ue.GameModeBase.md#setowner)

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

[GameModeBase](ue_ue.GameModeBase.md).[SetReplicateMovement](ue_ue.GameModeBase.md#setreplicatemovement)

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

[GameModeBase](ue_ue.GameModeBase.md).[SetReplicates](ue_ue.GameModeBase.md#setreplicates)

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

[GameModeBase](ue_ue.GameModeBase.md).[SetTickGroup](ue_ue.GameModeBase.md#settickgroup)

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

[GameModeBase](ue_ue.GameModeBase.md).[SetTickableWhenPaused](ue_ue.GameModeBase.md#settickablewhenpaused)

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

[GameModeBase](ue_ue.GameModeBase.md).[ShouldReset](ue_ue.GameModeBase.md#shouldreset)

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

[GameModeBase](ue_ue.GameModeBase.md).[SnapRootComponentTo](ue_ue.GameModeBase.md#snaprootcomponentto)

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

[GameModeBase](ue_ue.GameModeBase.md).[SpawnDefaultPawnAtTransform](ue_ue.GameModeBase.md#spawndefaultpawnattransform)

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

[GameModeBase](ue_ue.GameModeBase.md).[SpawnDefaultPawnFor](ue_ue.GameModeBase.md#spawndefaultpawnfor)

___

### StartPlay

▸ **StartPlay**(): `void`

#### Returns

`void`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[StartPlay](ue_ue.GameModeBase.md#startplay)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[TearOff](ue_ue.GameModeBase.md#tearoff)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[GameModeBase](ue_ue.GameModeBase.md).[UserConstructionScript](ue_ue.GameModeBase.md#userconstructionscript)

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

[GameModeBase](ue_ue.GameModeBase.md).[WasRecentlyRendered](ue_ue.GameModeBase.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TsTestGameMode_C`](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TsTestGameMode_C`](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md)

#### Overrides

[GameModeBase](ue_ue.GameModeBase.md).[Find](ue_ue.GameModeBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TsTestGameMode_C`](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TsTestGameMode_C`](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameMode.TsTestGameMode_C.md)

#### Overrides

[GameModeBase](ue_ue.GameModeBase.md).[Load](ue_ue.GameModeBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameModeBase](ue_ue.GameModeBase.md).[StaticClass](ue_ue.GameModeBase.md#staticclass)
