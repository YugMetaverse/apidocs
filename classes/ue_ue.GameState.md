[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GameState

# Class: GameState

[ue/ue](../modules/ue_ue.md).GameState

## Hierarchy

- [`GameStateBase`](ue_ue.GameStateBase.md)

  ↳ **`GameState`**

  ↳↳ [`ARSharedWorldGameState`](ue_ue.ARSharedWorldGameState.md)

## Table of contents

### Constructors

- [constructor](ue_ue.GameState.md#constructor)

### Properties

- [ActorLabel](ue_ue.GameState.md#actorlabel)
- [AttachmentReplication](ue_ue.GameState.md#attachmentreplication)
- [AuthorityGameMode](ue_ue.GameState.md#authoritygamemode)
- [AutoReceiveInput](ue_ue.GameState.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.GameState.md#blueprintcreatedcomponents)
- [Children](ue_ue.GameState.md#children)
- [ControllingMatineeActors](ue_ue.GameState.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.GameState.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.GameState.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [ElapsedTime](ue_ue.GameState.md#elapsedtime)
- [FolderPath](ue_ue.GameState.md#folderpath)
- [GameModeClass](ue_ue.GameState.md#gamemodeclass)
- [GroupActor](ue_ue.GameState.md#groupactor)
- [HiddenEditorViews](ue_ue.GameState.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.GameState.md#initiallifespan)
- [InputComponent](ue_ue.GameState.md#inputcomponent)
- [InputPriority](ue_ue.GameState.md#inputpriority)
- [InstanceComponents](ue_ue.GameState.md#instancecomponents)
- [Instigator](ue_ue.GameState.md#instigator)
- [Layers](ue_ue.GameState.md#layers)
- [MatchState](ue_ue.GameState.md#matchstate)
- [MinNetUpdateFrequency](ue_ue.GameState.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.GameState.md#netculldistancesquared)
- [NetDormancy](ue_ue.GameState.md#netdormancy)
- [NetDriverName](ue_ue.GameState.md#netdrivername)
- [NetPriority](ue_ue.GameState.md#netpriority)
- [NetTag](ue_ue.GameState.md#nettag)
- [NetUpdateFrequency](ue_ue.GameState.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.GameState.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.GameState.md#onactorendoverlap)
- [OnActorHit](ue_ue.GameState.md#onactorhit)
- [OnBeginCursorOver](ue_ue.GameState.md#onbegincursorover)
- [OnClicked](ue_ue.GameState.md#onclicked)
- [OnDestroyed](ue_ue.GameState.md#ondestroyed)
- [OnEndCursorOver](ue_ue.GameState.md#onendcursorover)
- [OnEndPlay](ue_ue.GameState.md#onendplay)
- [OnInputTouchBegin](ue_ue.GameState.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.GameState.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.GameState.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.GameState.md#oninputtouchleave)
- [OnReleased](ue_ue.GameState.md#onreleased)
- [OnTakeAnyDamage](ue_ue.GameState.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.GameState.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.GameState.md#ontakeradialdamage)
- [Owner](ue_ue.GameState.md#owner)
- [ParentComponent](ue_ue.GameState.md#parentcomponent)
- [ParentComponentActor](ue_ue.GameState.md#parentcomponentactor)
- [PivotOffset](ue_ue.GameState.md#pivotoffset)
- [PlayerArray](ue_ue.GameState.md#playerarray)
- [PreviousMatchState](ue_ue.GameState.md#previousmatchstate)
- [PrimaryActorTick](ue_ue.GameState.md#primaryactortick)
- [RemoteRole](ue_ue.GameState.md#remoterole)
- [ReplicatedMovement](ue_ue.GameState.md#replicatedmovement)
- [ReplicatedWorldTimeSeconds](ue_ue.GameState.md#replicatedworldtimeseconds)
- [Role](ue_ue.GameState.md#role)
- [RootComponent](ue_ue.GameState.md#rootcomponent)
- [ServerWorldTimeSecondsDelta](ue_ue.GameState.md#serverworldtimesecondsdelta)
- [ServerWorldTimeSecondsUpdateFrequency](ue_ue.GameState.md#serverworldtimesecondsupdatefrequency)
- [SpawnCollisionHandlingMethod](ue_ue.GameState.md#spawncollisionhandlingmethod)
- [SpectatorClass](ue_ue.GameState.md#spectatorclass)
- [SpriteComponent](ue_ue.GameState.md#spritecomponent)
- [SpriteScale](ue_ue.GameState.md#spritescale)
- [Tags](ue_ue.GameState.md#tags)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.GameState.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.GameState.md#__tid_actor__)
- [\_\_tid\_GameStateBase\_\_](ue_ue.GameState.md#__tid_gamestatebase__)
- [\_\_tid\_GameState\_\_](ue_ue.GameState.md#__tid_gamestate__)
- [\_\_tid\_Info\_\_](ue_ue.GameState.md#__tid_info__)
- [\_\_tid\_Object\_\_](ue_ue.GameState.md#__tid_object__)
- [bActorEnableCollision](ue_ue.GameState.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.GameState.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.GameState.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.GameState.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.GameState.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.GameState.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.GameState.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.GameState.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.GameState.md#bblockinput)
- [bCanBeDamaged](ue_ue.GameState.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.GameState.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.GameState.md#bcollidewhenplacing)
- [bEditable](ue_ue.GameState.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.GameState.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.GameState.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.GameState.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.GameState.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.GameState.md#bhidden)
- [bHiddenEd](ue_ue.GameState.md#bhiddened)
- [bHiddenEdLayer](ue_ue.GameState.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.GameState.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.GameState.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.GameState.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.GameState.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.GameState.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.GameState.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.GameState.md#blocklocation)
- [bNetLoadOnClient](ue_ue.GameState.md#bnetloadonclient)
- [bNetStartup](ue_ue.GameState.md#bnetstartup)
- [bNetTemporary](ue_ue.GameState.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.GameState.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.GameState.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.GameState.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.GameState.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.GameState.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.GameState.md#breplayrewindable)
- [bReplicateMovement](ue_ue.GameState.md#breplicatemovement)
- [bReplicatedHasBegunPlay](ue_ue.GameState.md#breplicatedhasbegunplay)
- [bReplicates](ue_ue.GameState.md#breplicates)
- [bTearOff](ue_ue.GameState.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.GameState.md#actorhastag)
- [AddComponent](ue_ue.GameState.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.GameState.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.GameState.md#addtickprerequisitecomponent)
- [CreateDefaultSubobject](ue_ue.GameState.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.GameState.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.GameState.md#disableinput)
- [EnableInput](ue_ue.GameState.md#enableinput)
- [ExecuteUbergraph](ue_ue.GameState.md#executeubergraph)
- [FlushNetDormancy](ue_ue.GameState.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.GameState.md#forcenetupdate)
- [GetActorBounds](ue_ue.GameState.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.GameState.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.GameState.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.GameState.md#getactorforwardvector)
- [GetActorLabel](ue_ue.GameState.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.GameState.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.GameState.md#getactorrightvector)
- [GetActorScale3D](ue_ue.GameState.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.GameState.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.GameState.md#getactortimedilation)
- [GetActorUpVector](ue_ue.GameState.md#getactorupvector)
- [GetAllChildActors](ue_ue.GameState.md#getallchildactors)
- [GetAttachParentActor](ue_ue.GameState.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.GameState.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.GameState.md#getattachedactors)
- [GetClass](ue_ue.GameState.md#getclass)
- [GetComponentByClass](ue_ue.GameState.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.GameState.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.GameState.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.GameState.md#getdistanceto)
- [GetDotProductTo](ue_ue.GameState.md#getdotproductto)
- [GetFolderPath](ue_ue.GameState.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.GameState.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.GameState.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.GameState.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.GameState.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.GameState.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.GameState.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.GameState.md#getinstigator)
- [GetInstigatorController](ue_ue.GameState.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.GameState.md#getlifespan)
- [GetLocalRole](ue_ue.GameState.md#getlocalrole)
- [GetName](ue_ue.GameState.md#getname)
- [GetOuter](ue_ue.GameState.md#getouter)
- [GetOverlappingActors](ue_ue.GameState.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.GameState.md#getoverlappingcomponents)
- [GetOwner](ue_ue.GameState.md#getowner)
- [GetParentActor](ue_ue.GameState.md#getparentactor)
- [GetParentComponent](ue_ue.GameState.md#getparentcomponent)
- [GetPlayerRespawnDelay](ue_ue.GameState.md#getplayerrespawndelay)
- [GetPlayerStartTime](ue_ue.GameState.md#getplayerstarttime)
- [GetRemoteRole](ue_ue.GameState.md#getremoterole)
- [GetServerWorldTimeSeconds](ue_ue.GameState.md#getserverworldtimeseconds)
- [GetSquaredDistanceTo](ue_ue.GameState.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.GameState.md#gettickablewhenpaused)
- [GetTransform](ue_ue.GameState.md#gettransform)
- [GetVelocity](ue_ue.GameState.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.GameState.md#getverticaldistanceto)
- [GetWorld](ue_ue.GameState.md#getworld)
- [HasAuthority](ue_ue.GameState.md#hasauthority)
- [HasBegunPlay](ue_ue.GameState.md#hasbegunplay)
- [HasMatchStarted](ue_ue.GameState.md#hasmatchstarted)
- [IsActorBeingDestroyed](ue_ue.GameState.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.GameState.md#isactortickenabled)
- [IsChildActor](ue_ue.GameState.md#ischildactor)
- [IsEditable](ue_ue.GameState.md#iseditable)
- [IsHiddenEd](ue_ue.GameState.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.GameState.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.GameState.md#isoverlappingactor)
- [IsSelectable](ue_ue.GameState.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.GameState.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.GameState.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.GameState.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.GameState.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.GameState.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.GameState.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.GameState.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.GameState.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.GameState.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.GameState.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.GameState.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.GameState.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.GameState.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.GameState.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.GameState.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.GameState.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.GameState.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.GameState.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.GameState.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.GameState.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.GameState.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.GameState.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.GameState.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.GameState.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.GameState.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.GameState.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.GameState.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.GameState.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.GameState.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.GameState.md#makemidformaterial)
- [MakeNoise](ue_ue.GameState.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.GameState.md#onrep_attachmentreplication)
- [OnRep\_ElapsedTime](ue_ue.GameState.md#onrep_elapsedtime)
- [OnRep\_GameModeClass](ue_ue.GameState.md#onrep_gamemodeclass)
- [OnRep\_Instigator](ue_ue.GameState.md#onrep_instigator)
- [OnRep\_MatchState](ue_ue.GameState.md#onrep_matchstate)
- [OnRep\_Owner](ue_ue.GameState.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.GameState.md#onrep_replicatemovement)
- [OnRep\_ReplicatedHasBegunPlay](ue_ue.GameState.md#onrep_replicatedhasbegunplay)
- [OnRep\_ReplicatedMovement](ue_ue.GameState.md#onrep_replicatedmovement)
- [OnRep\_ReplicatedWorldTimeSeconds](ue_ue.GameState.md#onrep_replicatedworldtimeseconds)
- [OnRep\_SpectatorClass](ue_ue.GameState.md#onrep_spectatorclass)
- [PrestreamTextures](ue_ue.GameState.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.GameState.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.GameState.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.GameState.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.GameState.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.GameState.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.GameState.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.GameState.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.GameState.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.GameState.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.GameState.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.GameState.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.GameState.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.GameState.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.GameState.md#receiveendplay)
- [ReceiveHit](ue_ue.GameState.md#receivehit)
- [ReceivePointDamage](ue_ue.GameState.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.GameState.md#receiveradialdamage)
- [ReceiveTick](ue_ue.GameState.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.GameState.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.GameState.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.GameState.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.GameState.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.GameState.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.GameState.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.GameState.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.GameState.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.GameState.md#setactortickinterval)
- [SetFolderPath](ue_ue.GameState.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.GameState.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.GameState.md#setlifespan)
- [SetNetDormancy](ue_ue.GameState.md#setnetdormancy)
- [SetOwner](ue_ue.GameState.md#setowner)
- [SetReplicateMovement](ue_ue.GameState.md#setreplicatemovement)
- [SetReplicates](ue_ue.GameState.md#setreplicates)
- [SetTickGroup](ue_ue.GameState.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.GameState.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.GameState.md#snaprootcomponentto)
- [TearOff](ue_ue.GameState.md#tearoff)
- [UserConstructionScript](ue_ue.GameState.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.GameState.md#wasrecentlyrendered)
- [Find](ue_ue.GameState.md#find)
- [Load](ue_ue.GameState.md#load)
- [StaticClass](ue_ue.GameState.md#staticclass)

## Constructors

### constructor

• **new GameState**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GameStateBase](ue_ue.GameStateBase.md).[constructor](ue_ue.GameStateBase.md#constructor)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[ActorLabel](ue_ue.GameStateBase.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[AttachmentReplication](ue_ue.GameStateBase.md#attachmentreplication)

___

### AuthorityGameMode

• **AuthorityGameMode**: [`GameModeBase`](ue_ue.GameModeBase.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[AuthorityGameMode](ue_ue.GameStateBase.md#authoritygamemode)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[AutoReceiveInput](ue_ue.GameStateBase.md#autoreceiveinput)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[BlueprintCreatedComponents](ue_ue.GameStateBase.md#blueprintcreatedcomponents)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[Children](ue_ue.GameStateBase.md#children)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[ControllingMatineeActors](ue_ue.GameStateBase.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[CustomTimeDilation](ue_ue.GameStateBase.md#customtimedilation)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.GameStateBase.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### ElapsedTime

• **ElapsedTime**: `number`

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[FolderPath](ue_ue.GameStateBase.md#folderpath)

___

### GameModeClass

• **GameModeClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GameModeClass](ue_ue.GameStateBase.md#gamemodeclass)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GroupActor](ue_ue.GameStateBase.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[HiddenEditorViews](ue_ue.GameStateBase.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[InitialLifeSpan](ue_ue.GameStateBase.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[InputComponent](ue_ue.GameStateBase.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[InputPriority](ue_ue.GameStateBase.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[InstanceComponents](ue_ue.GameStateBase.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[Instigator](ue_ue.GameStateBase.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[Layers](ue_ue.GameStateBase.md#layers)

___

### MatchState

• **MatchState**: `string`

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[MinNetUpdateFrequency](ue_ue.GameStateBase.md#minnetupdatefrequency)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[NetCullDistanceSquared](ue_ue.GameStateBase.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[NetDormancy](ue_ue.GameStateBase.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[NetDriverName](ue_ue.GameStateBase.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[NetPriority](ue_ue.GameStateBase.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[NetTag](ue_ue.GameStateBase.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[NetUpdateFrequency](ue_ue.GameStateBase.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnActorBeginOverlap](ue_ue.GameStateBase.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnActorEndOverlap](ue_ue.GameStateBase.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnActorHit](ue_ue.GameStateBase.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnBeginCursorOver](ue_ue.GameStateBase.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnClicked](ue_ue.GameStateBase.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnDestroyed](ue_ue.GameStateBase.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnEndCursorOver](ue_ue.GameStateBase.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnEndPlay](ue_ue.GameStateBase.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnInputTouchBegin](ue_ue.GameStateBase.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnInputTouchEnd](ue_ue.GameStateBase.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnInputTouchEnter](ue_ue.GameStateBase.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnInputTouchLeave](ue_ue.GameStateBase.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnReleased](ue_ue.GameStateBase.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnTakeAnyDamage](ue_ue.GameStateBase.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnTakePointDamage](ue_ue.GameStateBase.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnTakeRadialDamage](ue_ue.GameStateBase.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[Owner](ue_ue.GameStateBase.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[ParentComponent](ue_ue.GameStateBase.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[ParentComponentActor](ue_ue.GameStateBase.md#parentcomponentactor)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[PivotOffset](ue_ue.GameStateBase.md#pivotoffset)

___

### PlayerArray

• **PlayerArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PlayerState`](ue_ue.PlayerState.md)\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[PlayerArray](ue_ue.GameStateBase.md#playerarray)

___

### PreviousMatchState

• **PreviousMatchState**: `string`

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[PrimaryActorTick](ue_ue.GameStateBase.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[RemoteRole](ue_ue.GameStateBase.md#remoterole)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[ReplicatedMovement](ue_ue.GameStateBase.md#replicatedmovement)

___

### ReplicatedWorldTimeSeconds

• **ReplicatedWorldTimeSeconds**: `number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[ReplicatedWorldTimeSeconds](ue_ue.GameStateBase.md#replicatedworldtimeseconds)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[Role](ue_ue.GameStateBase.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[RootComponent](ue_ue.GameStateBase.md#rootcomponent)

___

### ServerWorldTimeSecondsDelta

• **ServerWorldTimeSecondsDelta**: `number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[ServerWorldTimeSecondsDelta](ue_ue.GameStateBase.md#serverworldtimesecondsdelta)

___

### ServerWorldTimeSecondsUpdateFrequency

• **ServerWorldTimeSecondsUpdateFrequency**: `number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[ServerWorldTimeSecondsUpdateFrequency](ue_ue.GameStateBase.md#serverworldtimesecondsupdatefrequency)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[SpawnCollisionHandlingMethod](ue_ue.GameStateBase.md#spawncollisionhandlingmethod)

___

### SpectatorClass

• **SpectatorClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[SpectatorClass](ue_ue.GameStateBase.md#spectatorclass)

___

### SpriteComponent

• **SpriteComponent**: [`BillboardComponent`](ue_ue.BillboardComponent.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[SpriteComponent](ue_ue.GameStateBase.md#spritecomponent)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[SpriteScale](ue_ue.GameStateBase.md#spritescale)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[Tags](ue_ue.GameStateBase.md#tags)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.GameStateBase.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[__tid_Actor__](ue_ue.GameStateBase.md#__tid_actor__)

___

### \_\_tid\_GameStateBase\_\_

• **\_\_tid\_GameStateBase\_\_**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[__tid_GameStateBase__](ue_ue.GameStateBase.md#__tid_gamestatebase__)

___

### \_\_tid\_GameState\_\_

• **\_\_tid\_GameState\_\_**: `boolean`

___

### \_\_tid\_Info\_\_

• **\_\_tid\_Info\_\_**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[__tid_Info__](ue_ue.GameStateBase.md#__tid_info__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[__tid_Object__](ue_ue.GameStateBase.md#__tid_object__)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bActorEnableCollision](ue_ue.GameStateBase.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bActorIsBeingDestroyed](ue_ue.GameStateBase.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bActorLabelEditable](ue_ue.GameStateBase.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bActorSeamlessTraveled](ue_ue.GameStateBase.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.GameStateBase.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bAllowTickBeforeBeginPlay](ue_ue.GameStateBase.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bAlwaysRelevant](ue_ue.GameStateBase.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bAutoDestroyWhenFinished](ue_ue.GameStateBase.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bBlockInput](ue_ue.GameStateBase.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bCanBeDamaged](ue_ue.GameStateBase.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bCanBeInCluster](ue_ue.GameStateBase.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bCollideWhenPlacing](ue_ue.GameStateBase.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bEditable](ue_ue.GameStateBase.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bEnableAutoLODGeneration](ue_ue.GameStateBase.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bExchangedRoles](ue_ue.GameStateBase.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bFindCameraComponentWhenViewTarget](ue_ue.GameStateBase.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.GameStateBase.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bHidden](ue_ue.GameStateBase.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bHiddenEd](ue_ue.GameStateBase.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bHiddenEdLayer](ue_ue.GameStateBase.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bHiddenEdLevel](ue_ue.GameStateBase.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bHiddenEdTemporary](ue_ue.GameStateBase.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bIgnoresOriginShifting](ue_ue.GameStateBase.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bIsEditorOnlyActor](ue_ue.GameStateBase.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bIsEditorPreviewActor](ue_ue.GameStateBase.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bListedInSceneOutliner](ue_ue.GameStateBase.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bLockLocation](ue_ue.GameStateBase.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bNetLoadOnClient](ue_ue.GameStateBase.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bNetStartup](ue_ue.GameStateBase.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bNetTemporary](ue_ue.GameStateBase.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bNetUseOwnerRelevancy](ue_ue.GameStateBase.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bOnlyRelevantToOwner](ue_ue.GameStateBase.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bOptimizeBPComponentData](ue_ue.GameStateBase.md#boptimizebpcomponentdata)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bRelevantForLevelBounds](ue_ue.GameStateBase.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bRelevantForNetworkReplays](ue_ue.GameStateBase.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bReplayRewindable](ue_ue.GameStateBase.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bReplicateMovement](ue_ue.GameStateBase.md#breplicatemovement)

___

### bReplicatedHasBegunPlay

• **bReplicatedHasBegunPlay**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bReplicatedHasBegunPlay](ue_ue.GameStateBase.md#breplicatedhasbegunplay)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bReplicates](ue_ue.GameStateBase.md#breplicates)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[bTearOff](ue_ue.GameStateBase.md#btearoff)

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

[GameStateBase](ue_ue.GameStateBase.md).[ActorHasTag](ue_ue.GameStateBase.md#actorhastag)

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

[GameStateBase](ue_ue.GameStateBase.md).[AddComponent](ue_ue.GameStateBase.md#addcomponent)

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

[GameStateBase](ue_ue.GameStateBase.md).[AddTickPrerequisiteActor](ue_ue.GameStateBase.md#addtickprerequisiteactor)

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

[GameStateBase](ue_ue.GameStateBase.md).[AddTickPrerequisiteComponent](ue_ue.GameStateBase.md#addtickprerequisitecomponent)

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

[GameStateBase](ue_ue.GameStateBase.md).[CreateDefaultSubobject](ue_ue.GameStateBase.md#createdefaultsubobject)

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

[GameStateBase](ue_ue.GameStateBase.md).[DetachRootComponentFromParent](ue_ue.GameStateBase.md#detachrootcomponentfromparent)

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

[GameStateBase](ue_ue.GameStateBase.md).[DisableInput](ue_ue.GameStateBase.md#disableinput)

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

[GameStateBase](ue_ue.GameStateBase.md).[EnableInput](ue_ue.GameStateBase.md#enableinput)

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

[GameStateBase](ue_ue.GameStateBase.md).[ExecuteUbergraph](ue_ue.GameStateBase.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[FlushNetDormancy](ue_ue.GameStateBase.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[ForceNetUpdate](ue_ue.GameStateBase.md#forcenetupdate)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetActorBounds](ue_ue.GameStateBase.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetActorEnableCollision](ue_ue.GameStateBase.md#getactorenablecollision)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetActorEyesViewPoint](ue_ue.GameStateBase.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetActorForwardVector](ue_ue.GameStateBase.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetActorLabel](ue_ue.GameStateBase.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetActorRelativeScale3D](ue_ue.GameStateBase.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetActorRightVector](ue_ue.GameStateBase.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetActorScale3D](ue_ue.GameStateBase.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetActorTickInterval](ue_ue.GameStateBase.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetActorTimeDilation](ue_ue.GameStateBase.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetActorUpVector](ue_ue.GameStateBase.md#getactorupvector)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetAllChildActors](ue_ue.GameStateBase.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetAttachParentActor](ue_ue.GameStateBase.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetAttachParentSocketName](ue_ue.GameStateBase.md#getattachparentsocketname)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetAttachedActors](ue_ue.GameStateBase.md#getattachedactors)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetClass](ue_ue.GameStateBase.md#getclass)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetComponentByClass](ue_ue.GameStateBase.md#getcomponentbyclass)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetComponentsByInterface](ue_ue.GameStateBase.md#getcomponentsbyinterface)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetComponentsByTag](ue_ue.GameStateBase.md#getcomponentsbytag)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetDistanceTo](ue_ue.GameStateBase.md#getdistanceto)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetDotProductTo](ue_ue.GameStateBase.md#getdotproductto)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetFolderPath](ue_ue.GameStateBase.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetGameTimeSinceCreation](ue_ue.GameStateBase.md#getgametimesincecreation)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetHorizontalDistanceTo](ue_ue.GameStateBase.md#gethorizontaldistanceto)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetHorizontalDotProductTo](ue_ue.GameStateBase.md#gethorizontaldotproductto)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetInputAxisKeyValue](ue_ue.GameStateBase.md#getinputaxiskeyvalue)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetInputAxisValue](ue_ue.GameStateBase.md#getinputaxisvalue)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetInputVectorAxisValue](ue_ue.GameStateBase.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetInstigator](ue_ue.GameStateBase.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetInstigatorController](ue_ue.GameStateBase.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetLifeSpan](ue_ue.GameStateBase.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetLocalRole](ue_ue.GameStateBase.md#getlocalrole)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetName](ue_ue.GameStateBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetOuter](ue_ue.GameStateBase.md#getouter)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetOverlappingActors](ue_ue.GameStateBase.md#getoverlappingactors)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetOverlappingComponents](ue_ue.GameStateBase.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetOwner](ue_ue.GameStateBase.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetParentActor](ue_ue.GameStateBase.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetParentComponent](ue_ue.GameStateBase.md#getparentcomponent)

___

### GetPlayerRespawnDelay

▸ **GetPlayerRespawnDelay**(`Controller`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Controller` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |

#### Returns

`number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetPlayerRespawnDelay](ue_ue.GameStateBase.md#getplayerrespawndelay)

___

### GetPlayerStartTime

▸ **GetPlayerStartTime**(`Controller`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Controller` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |

#### Returns

`number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetPlayerStartTime](ue_ue.GameStateBase.md#getplayerstarttime)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetRemoteRole](ue_ue.GameStateBase.md#getremoterole)

___

### GetServerWorldTimeSeconds

▸ **GetServerWorldTimeSeconds**(): `number`

#### Returns

`number`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetServerWorldTimeSeconds](ue_ue.GameStateBase.md#getserverworldtimeseconds)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetSquaredDistanceTo](ue_ue.GameStateBase.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetTickableWhenPaused](ue_ue.GameStateBase.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetTransform](ue_ue.GameStateBase.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetVelocity](ue_ue.GameStateBase.md#getvelocity)

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

[GameStateBase](ue_ue.GameStateBase.md).[GetVerticalDistanceTo](ue_ue.GameStateBase.md#getverticaldistanceto)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[GetWorld](ue_ue.GameStateBase.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[HasAuthority](ue_ue.GameStateBase.md#hasauthority)

___

### HasBegunPlay

▸ **HasBegunPlay**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[HasBegunPlay](ue_ue.GameStateBase.md#hasbegunplay)

___

### HasMatchStarted

▸ **HasMatchStarted**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[HasMatchStarted](ue_ue.GameStateBase.md#hasmatchstarted)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[IsActorBeingDestroyed](ue_ue.GameStateBase.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[IsActorTickEnabled](ue_ue.GameStateBase.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[IsChildActor](ue_ue.GameStateBase.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[IsEditable](ue_ue.GameStateBase.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[IsHiddenEd](ue_ue.GameStateBase.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[IsHiddenEdAtStartup](ue_ue.GameStateBase.md#ishiddenedatstartup)

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

[GameStateBase](ue_ue.GameStateBase.md).[IsOverlappingActor](ue_ue.GameStateBase.md#isoverlappingactor)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[IsSelectable](ue_ue.GameStateBase.md#isselectable)

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

[GameStateBase](ue_ue.GameStateBase.md).[IsTemporarilyHiddenInEditor](ue_ue.GameStateBase.md#istemporarilyhiddenineditor)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_AddActorLocalOffset](ue_ue.GameStateBase.md#k2_addactorlocaloffset)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_AddActorLocalRotation](ue_ue.GameStateBase.md#k2_addactorlocalrotation)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_AddActorLocalTransform](ue_ue.GameStateBase.md#k2_addactorlocaltransform)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_AddActorWorldOffset](ue_ue.GameStateBase.md#k2_addactorworldoffset)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_AddActorWorldRotation](ue_ue.GameStateBase.md#k2_addactorworldrotation)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_AddActorWorldTransform](ue_ue.GameStateBase.md#k2_addactorworldtransform)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_AttachRootComponentTo](ue_ue.GameStateBase.md#k2_attachrootcomponentto)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_AttachRootComponentToActor](ue_ue.GameStateBase.md#k2_attachrootcomponenttoactor)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_AttachToActor](ue_ue.GameStateBase.md#k2_attachtoactor)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_AttachToComponent](ue_ue.GameStateBase.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[K2_DestroyActor](ue_ue.GameStateBase.md#k2_destroyactor)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_DestroyComponent](ue_ue.GameStateBase.md#k2_destroycomponent)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_DetachFromActor](ue_ue.GameStateBase.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[K2_GetActorLocation](ue_ue.GameStateBase.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[K2_GetActorRotation](ue_ue.GameStateBase.md#k2_getactorrotation)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_GetComponentsByClass](ue_ue.GameStateBase.md#k2_getcomponentsbyclass)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[K2_GetRootComponent](ue_ue.GameStateBase.md#k2_getrootcomponent)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_OnBecomeViewTarget](ue_ue.GameStateBase.md#k2_onbecomeviewtarget)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_OnEndViewTarget](ue_ue.GameStateBase.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[K2_OnReset](ue_ue.GameStateBase.md#k2_onreset)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_SetActorLocation](ue_ue.GameStateBase.md#k2_setactorlocation)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_SetActorLocationAndRotation](ue_ue.GameStateBase.md#k2_setactorlocationandrotation)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_SetActorRelativeLocation](ue_ue.GameStateBase.md#k2_setactorrelativelocation)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_SetActorRelativeRotation](ue_ue.GameStateBase.md#k2_setactorrelativerotation)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_SetActorRelativeTransform](ue_ue.GameStateBase.md#k2_setactorrelativetransform)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_SetActorRotation](ue_ue.GameStateBase.md#k2_setactorrotation)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_SetActorTransform](ue_ue.GameStateBase.md#k2_setactortransform)

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

[GameStateBase](ue_ue.GameStateBase.md).[K2_TeleportTo](ue_ue.GameStateBase.md#k2_teleportto)

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

[GameStateBase](ue_ue.GameStateBase.md).[MakeMIDForMaterial](ue_ue.GameStateBase.md#makemidformaterial)

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

[GameStateBase](ue_ue.GameStateBase.md).[MakeNoise](ue_ue.GameStateBase.md#makenoise)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnRep_AttachmentReplication](ue_ue.GameStateBase.md#onrep_attachmentreplication)

___

### OnRep\_ElapsedTime

▸ **OnRep_ElapsedTime**(): `void`

#### Returns

`void`

___

### OnRep\_GameModeClass

▸ **OnRep_GameModeClass**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnRep_GameModeClass](ue_ue.GameStateBase.md#onrep_gamemodeclass)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnRep_Instigator](ue_ue.GameStateBase.md#onrep_instigator)

___

### OnRep\_MatchState

▸ **OnRep_MatchState**(): `void`

#### Returns

`void`

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnRep_Owner](ue_ue.GameStateBase.md#onrep_owner)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnRep_ReplicateMovement](ue_ue.GameStateBase.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedHasBegunPlay

▸ **OnRep_ReplicatedHasBegunPlay**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnRep_ReplicatedHasBegunPlay](ue_ue.GameStateBase.md#onrep_replicatedhasbegunplay)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnRep_ReplicatedMovement](ue_ue.GameStateBase.md#onrep_replicatedmovement)

___

### OnRep\_ReplicatedWorldTimeSeconds

▸ **OnRep_ReplicatedWorldTimeSeconds**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnRep_ReplicatedWorldTimeSeconds](ue_ue.GameStateBase.md#onrep_replicatedworldtimeseconds)

___

### OnRep\_SpectatorClass

▸ **OnRep_SpectatorClass**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[OnRep_SpectatorClass](ue_ue.GameStateBase.md#onrep_spectatorclass)

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

[GameStateBase](ue_ue.GameStateBase.md).[PrestreamTextures](ue_ue.GameStateBase.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[ReceiveActorBeginCursorOver](ue_ue.GameStateBase.md#receiveactorbegincursorover)

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

[GameStateBase](ue_ue.GameStateBase.md).[ReceiveActorBeginOverlap](ue_ue.GameStateBase.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[ReceiveActorEndCursorOver](ue_ue.GameStateBase.md#receiveactorendcursorover)

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

[GameStateBase](ue_ue.GameStateBase.md).[ReceiveActorEndOverlap](ue_ue.GameStateBase.md#receiveactorendoverlap)

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

[GameStateBase](ue_ue.GameStateBase.md).[ReceiveActorOnClicked](ue_ue.GameStateBase.md#receiveactoronclicked)

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

[GameStateBase](ue_ue.GameStateBase.md).[ReceiveActorOnInputTouchBegin](ue_ue.GameStateBase.md#receiveactoroninputtouchbegin)

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

[GameStateBase](ue_ue.GameStateBase.md).[ReceiveActorOnInputTouchEnd](ue_ue.GameStateBase.md#receiveactoroninputtouchend)

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

[GameStateBase](ue_ue.GameStateBase.md).[ReceiveActorOnInputTouchEnter](ue_ue.GameStateBase.md#receiveactoroninputtouchenter)

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

[GameStateBase](ue_ue.GameStateBase.md).[ReceiveActorOnInputTouchLeave](ue_ue.GameStateBase.md#receiveactoroninputtouchleave)

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

[GameStateBase](ue_ue.GameStateBase.md).[ReceiveActorOnReleased](ue_ue.GameStateBase.md#receiveactoronreleased)

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

[GameStateBase](ue_ue.GameStateBase.md).[ReceiveAnyDamage](ue_ue.GameStateBase.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[ReceiveBeginPlay](ue_ue.GameStateBase.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[ReceiveDestroyed](ue_ue.GameStateBase.md#receivedestroyed)

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

[GameStateBase](ue_ue.GameStateBase.md).[ReceiveEndPlay](ue_ue.GameStateBase.md#receiveendplay)

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

[GameStateBase](ue_ue.GameStateBase.md).[ReceiveHit](ue_ue.GameStateBase.md#receivehit)

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

[GameStateBase](ue_ue.GameStateBase.md).[ReceivePointDamage](ue_ue.GameStateBase.md#receivepointdamage)

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

[GameStateBase](ue_ue.GameStateBase.md).[ReceiveRadialDamage](ue_ue.GameStateBase.md#receiveradialdamage)

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

[GameStateBase](ue_ue.GameStateBase.md).[ReceiveTick](ue_ue.GameStateBase.md#receivetick)

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

[GameStateBase](ue_ue.GameStateBase.md).[RemoveTickPrerequisiteActor](ue_ue.GameStateBase.md#removetickprerequisiteactor)

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

[GameStateBase](ue_ue.GameStateBase.md).[RemoveTickPrerequisiteComponent](ue_ue.GameStateBase.md#removetickprerequisitecomponent)

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

[GameStateBase](ue_ue.GameStateBase.md).[SetActorEnableCollision](ue_ue.GameStateBase.md#setactorenablecollision)

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

[GameStateBase](ue_ue.GameStateBase.md).[SetActorHiddenInGame](ue_ue.GameStateBase.md#setactorhiddeningame)

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

[GameStateBase](ue_ue.GameStateBase.md).[SetActorLabel](ue_ue.GameStateBase.md#setactorlabel)

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

[GameStateBase](ue_ue.GameStateBase.md).[SetActorRelativeScale3D](ue_ue.GameStateBase.md#setactorrelativescale3d)

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

[GameStateBase](ue_ue.GameStateBase.md).[SetActorScale3D](ue_ue.GameStateBase.md#setactorscale3d)

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

[GameStateBase](ue_ue.GameStateBase.md).[SetActorTickEnabled](ue_ue.GameStateBase.md#setactortickenabled)

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

[GameStateBase](ue_ue.GameStateBase.md).[SetActorTickInterval](ue_ue.GameStateBase.md#setactortickinterval)

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

[GameStateBase](ue_ue.GameStateBase.md).[SetFolderPath](ue_ue.GameStateBase.md#setfolderpath)

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

[GameStateBase](ue_ue.GameStateBase.md).[SetIsTemporarilyHiddenInEditor](ue_ue.GameStateBase.md#setistemporarilyhiddenineditor)

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

[GameStateBase](ue_ue.GameStateBase.md).[SetLifeSpan](ue_ue.GameStateBase.md#setlifespan)

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

[GameStateBase](ue_ue.GameStateBase.md).[SetNetDormancy](ue_ue.GameStateBase.md#setnetdormancy)

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

[GameStateBase](ue_ue.GameStateBase.md).[SetOwner](ue_ue.GameStateBase.md#setowner)

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

[GameStateBase](ue_ue.GameStateBase.md).[SetReplicateMovement](ue_ue.GameStateBase.md#setreplicatemovement)

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

[GameStateBase](ue_ue.GameStateBase.md).[SetReplicates](ue_ue.GameStateBase.md#setreplicates)

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

[GameStateBase](ue_ue.GameStateBase.md).[SetTickGroup](ue_ue.GameStateBase.md#settickgroup)

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

[GameStateBase](ue_ue.GameStateBase.md).[SetTickableWhenPaused](ue_ue.GameStateBase.md#settickablewhenpaused)

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

[GameStateBase](ue_ue.GameStateBase.md).[SnapRootComponentTo](ue_ue.GameStateBase.md#snaprootcomponentto)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[TearOff](ue_ue.GameStateBase.md#tearoff)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[GameStateBase](ue_ue.GameStateBase.md).[UserConstructionScript](ue_ue.GameStateBase.md#userconstructionscript)

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

[GameStateBase](ue_ue.GameStateBase.md).[WasRecentlyRendered](ue_ue.GameStateBase.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GameState`](ue_ue.GameState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GameState`](ue_ue.GameState.md)

#### Overrides

[GameStateBase](ue_ue.GameStateBase.md).[Find](ue_ue.GameStateBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GameState`](ue_ue.GameState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GameState`](ue_ue.GameState.md)

#### Overrides

[GameStateBase](ue_ue.GameStateBase.md).[Load](ue_ue.GameStateBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameStateBase](ue_ue.GameStateBase.md).[StaticClass](ue_ue.GameStateBase.md#staticclass)
