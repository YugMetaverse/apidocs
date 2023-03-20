[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARSharedWorldGameState

# Class: ARSharedWorldGameState

[ue/ue](../modules/ue_ue.md).ARSharedWorldGameState

## Hierarchy

- [`GameState`](ue_ue.GameState.md)

  ↳ **`ARSharedWorldGameState`**

## Table of contents

### Constructors

- [constructor](ue_ue.ARSharedWorldGameState.md#constructor)

### Properties

- [ARWorldBytesDelivered](ue_ue.ARSharedWorldGameState.md#arworldbytesdelivered)
- [ARWorldBytesTotal](ue_ue.ARSharedWorldGameState.md#arworldbytestotal)
- [ARWorldData](ue_ue.ARSharedWorldGameState.md#arworlddata)
- [ActorLabel](ue_ue.ARSharedWorldGameState.md#actorlabel)
- [AttachmentReplication](ue_ue.ARSharedWorldGameState.md#attachmentreplication)
- [AuthorityGameMode](ue_ue.ARSharedWorldGameState.md#authoritygamemode)
- [AutoReceiveInput](ue_ue.ARSharedWorldGameState.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.ARSharedWorldGameState.md#blueprintcreatedcomponents)
- [Children](ue_ue.ARSharedWorldGameState.md#children)
- [ControllingMatineeActors](ue_ue.ARSharedWorldGameState.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.ARSharedWorldGameState.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.ARSharedWorldGameState.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [ElapsedTime](ue_ue.ARSharedWorldGameState.md#elapsedtime)
- [FolderPath](ue_ue.ARSharedWorldGameState.md#folderpath)
- [GameModeClass](ue_ue.ARSharedWorldGameState.md#gamemodeclass)
- [GroupActor](ue_ue.ARSharedWorldGameState.md#groupactor)
- [HiddenEditorViews](ue_ue.ARSharedWorldGameState.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.ARSharedWorldGameState.md#initiallifespan)
- [InputComponent](ue_ue.ARSharedWorldGameState.md#inputcomponent)
- [InputPriority](ue_ue.ARSharedWorldGameState.md#inputpriority)
- [InstanceComponents](ue_ue.ARSharedWorldGameState.md#instancecomponents)
- [Instigator](ue_ue.ARSharedWorldGameState.md#instigator)
- [Layers](ue_ue.ARSharedWorldGameState.md#layers)
- [MatchState](ue_ue.ARSharedWorldGameState.md#matchstate)
- [MinNetUpdateFrequency](ue_ue.ARSharedWorldGameState.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.ARSharedWorldGameState.md#netculldistancesquared)
- [NetDormancy](ue_ue.ARSharedWorldGameState.md#netdormancy)
- [NetDriverName](ue_ue.ARSharedWorldGameState.md#netdrivername)
- [NetPriority](ue_ue.ARSharedWorldGameState.md#netpriority)
- [NetTag](ue_ue.ARSharedWorldGameState.md#nettag)
- [NetUpdateFrequency](ue_ue.ARSharedWorldGameState.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.ARSharedWorldGameState.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.ARSharedWorldGameState.md#onactorendoverlap)
- [OnActorHit](ue_ue.ARSharedWorldGameState.md#onactorhit)
- [OnBeginCursorOver](ue_ue.ARSharedWorldGameState.md#onbegincursorover)
- [OnClicked](ue_ue.ARSharedWorldGameState.md#onclicked)
- [OnDestroyed](ue_ue.ARSharedWorldGameState.md#ondestroyed)
- [OnEndCursorOver](ue_ue.ARSharedWorldGameState.md#onendcursorover)
- [OnEndPlay](ue_ue.ARSharedWorldGameState.md#onendplay)
- [OnInputTouchBegin](ue_ue.ARSharedWorldGameState.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.ARSharedWorldGameState.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.ARSharedWorldGameState.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.ARSharedWorldGameState.md#oninputtouchleave)
- [OnReleased](ue_ue.ARSharedWorldGameState.md#onreleased)
- [OnTakeAnyDamage](ue_ue.ARSharedWorldGameState.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.ARSharedWorldGameState.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.ARSharedWorldGameState.md#ontakeradialdamage)
- [Owner](ue_ue.ARSharedWorldGameState.md#owner)
- [ParentComponent](ue_ue.ARSharedWorldGameState.md#parentcomponent)
- [ParentComponentActor](ue_ue.ARSharedWorldGameState.md#parentcomponentactor)
- [PivotOffset](ue_ue.ARSharedWorldGameState.md#pivotoffset)
- [PlayerArray](ue_ue.ARSharedWorldGameState.md#playerarray)
- [PreviewImageBytesDelivered](ue_ue.ARSharedWorldGameState.md#previewimagebytesdelivered)
- [PreviewImageBytesTotal](ue_ue.ARSharedWorldGameState.md#previewimagebytestotal)
- [PreviewImageData](ue_ue.ARSharedWorldGameState.md#previewimagedata)
- [PreviousMatchState](ue_ue.ARSharedWorldGameState.md#previousmatchstate)
- [PrimaryActorTick](ue_ue.ARSharedWorldGameState.md#primaryactortick)
- [RemoteRole](ue_ue.ARSharedWorldGameState.md#remoterole)
- [ReplicatedMovement](ue_ue.ARSharedWorldGameState.md#replicatedmovement)
- [ReplicatedWorldTimeSeconds](ue_ue.ARSharedWorldGameState.md#replicatedworldtimeseconds)
- [Role](ue_ue.ARSharedWorldGameState.md#role)
- [RootComponent](ue_ue.ARSharedWorldGameState.md#rootcomponent)
- [ServerWorldTimeSecondsDelta](ue_ue.ARSharedWorldGameState.md#serverworldtimesecondsdelta)
- [ServerWorldTimeSecondsUpdateFrequency](ue_ue.ARSharedWorldGameState.md#serverworldtimesecondsupdatefrequency)
- [SpawnCollisionHandlingMethod](ue_ue.ARSharedWorldGameState.md#spawncollisionhandlingmethod)
- [SpectatorClass](ue_ue.ARSharedWorldGameState.md#spectatorclass)
- [SpriteComponent](ue_ue.ARSharedWorldGameState.md#spritecomponent)
- [SpriteScale](ue_ue.ARSharedWorldGameState.md#spritescale)
- [Tags](ue_ue.ARSharedWorldGameState.md#tags)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.ARSharedWorldGameState.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_ARSharedWorldGameState\_\_](ue_ue.ARSharedWorldGameState.md#__tid_arsharedworldgamestate__)
- [\_\_tid\_Actor\_\_](ue_ue.ARSharedWorldGameState.md#__tid_actor__)
- [\_\_tid\_GameStateBase\_\_](ue_ue.ARSharedWorldGameState.md#__tid_gamestatebase__)
- [\_\_tid\_GameState\_\_](ue_ue.ARSharedWorldGameState.md#__tid_gamestate__)
- [\_\_tid\_Info\_\_](ue_ue.ARSharedWorldGameState.md#__tid_info__)
- [\_\_tid\_Object\_\_](ue_ue.ARSharedWorldGameState.md#__tid_object__)
- [bActorEnableCollision](ue_ue.ARSharedWorldGameState.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.ARSharedWorldGameState.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.ARSharedWorldGameState.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.ARSharedWorldGameState.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.ARSharedWorldGameState.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.ARSharedWorldGameState.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.ARSharedWorldGameState.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.ARSharedWorldGameState.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.ARSharedWorldGameState.md#bblockinput)
- [bCanBeDamaged](ue_ue.ARSharedWorldGameState.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.ARSharedWorldGameState.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.ARSharedWorldGameState.md#bcollidewhenplacing)
- [bEditable](ue_ue.ARSharedWorldGameState.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.ARSharedWorldGameState.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.ARSharedWorldGameState.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.ARSharedWorldGameState.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.ARSharedWorldGameState.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.ARSharedWorldGameState.md#bhidden)
- [bHiddenEd](ue_ue.ARSharedWorldGameState.md#bhiddened)
- [bHiddenEdLayer](ue_ue.ARSharedWorldGameState.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.ARSharedWorldGameState.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.ARSharedWorldGameState.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.ARSharedWorldGameState.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.ARSharedWorldGameState.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.ARSharedWorldGameState.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.ARSharedWorldGameState.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.ARSharedWorldGameState.md#blocklocation)
- [bNetLoadOnClient](ue_ue.ARSharedWorldGameState.md#bnetloadonclient)
- [bNetStartup](ue_ue.ARSharedWorldGameState.md#bnetstartup)
- [bNetTemporary](ue_ue.ARSharedWorldGameState.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.ARSharedWorldGameState.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.ARSharedWorldGameState.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.ARSharedWorldGameState.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.ARSharedWorldGameState.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.ARSharedWorldGameState.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.ARSharedWorldGameState.md#breplayrewindable)
- [bReplicateMovement](ue_ue.ARSharedWorldGameState.md#breplicatemovement)
- [bReplicatedHasBegunPlay](ue_ue.ARSharedWorldGameState.md#breplicatedhasbegunplay)
- [bReplicates](ue_ue.ARSharedWorldGameState.md#breplicates)
- [bTearOff](ue_ue.ARSharedWorldGameState.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.ARSharedWorldGameState.md#actorhastag)
- [AddComponent](ue_ue.ARSharedWorldGameState.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.ARSharedWorldGameState.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.ARSharedWorldGameState.md#addtickprerequisitecomponent)
- [CreateDefaultSubobject](ue_ue.ARSharedWorldGameState.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.ARSharedWorldGameState.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.ARSharedWorldGameState.md#disableinput)
- [EnableInput](ue_ue.ARSharedWorldGameState.md#enableinput)
- [ExecuteUbergraph](ue_ue.ARSharedWorldGameState.md#executeubergraph)
- [FlushNetDormancy](ue_ue.ARSharedWorldGameState.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.ARSharedWorldGameState.md#forcenetupdate)
- [GetActorBounds](ue_ue.ARSharedWorldGameState.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.ARSharedWorldGameState.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.ARSharedWorldGameState.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.ARSharedWorldGameState.md#getactorforwardvector)
- [GetActorLabel](ue_ue.ARSharedWorldGameState.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.ARSharedWorldGameState.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.ARSharedWorldGameState.md#getactorrightvector)
- [GetActorScale3D](ue_ue.ARSharedWorldGameState.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.ARSharedWorldGameState.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.ARSharedWorldGameState.md#getactortimedilation)
- [GetActorUpVector](ue_ue.ARSharedWorldGameState.md#getactorupvector)
- [GetAllChildActors](ue_ue.ARSharedWorldGameState.md#getallchildactors)
- [GetAttachParentActor](ue_ue.ARSharedWorldGameState.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.ARSharedWorldGameState.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.ARSharedWorldGameState.md#getattachedactors)
- [GetClass](ue_ue.ARSharedWorldGameState.md#getclass)
- [GetComponentByClass](ue_ue.ARSharedWorldGameState.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.ARSharedWorldGameState.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.ARSharedWorldGameState.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.ARSharedWorldGameState.md#getdistanceto)
- [GetDotProductTo](ue_ue.ARSharedWorldGameState.md#getdotproductto)
- [GetFolderPath](ue_ue.ARSharedWorldGameState.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.ARSharedWorldGameState.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.ARSharedWorldGameState.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.ARSharedWorldGameState.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.ARSharedWorldGameState.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.ARSharedWorldGameState.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.ARSharedWorldGameState.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.ARSharedWorldGameState.md#getinstigator)
- [GetInstigatorController](ue_ue.ARSharedWorldGameState.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.ARSharedWorldGameState.md#getlifespan)
- [GetLocalRole](ue_ue.ARSharedWorldGameState.md#getlocalrole)
- [GetName](ue_ue.ARSharedWorldGameState.md#getname)
- [GetOuter](ue_ue.ARSharedWorldGameState.md#getouter)
- [GetOverlappingActors](ue_ue.ARSharedWorldGameState.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.ARSharedWorldGameState.md#getoverlappingcomponents)
- [GetOwner](ue_ue.ARSharedWorldGameState.md#getowner)
- [GetParentActor](ue_ue.ARSharedWorldGameState.md#getparentactor)
- [GetParentComponent](ue_ue.ARSharedWorldGameState.md#getparentcomponent)
- [GetPlayerRespawnDelay](ue_ue.ARSharedWorldGameState.md#getplayerrespawndelay)
- [GetPlayerStartTime](ue_ue.ARSharedWorldGameState.md#getplayerstarttime)
- [GetRemoteRole](ue_ue.ARSharedWorldGameState.md#getremoterole)
- [GetServerWorldTimeSeconds](ue_ue.ARSharedWorldGameState.md#getserverworldtimeseconds)
- [GetSquaredDistanceTo](ue_ue.ARSharedWorldGameState.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.ARSharedWorldGameState.md#gettickablewhenpaused)
- [GetTransform](ue_ue.ARSharedWorldGameState.md#gettransform)
- [GetVelocity](ue_ue.ARSharedWorldGameState.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.ARSharedWorldGameState.md#getverticaldistanceto)
- [GetWorld](ue_ue.ARSharedWorldGameState.md#getworld)
- [HasAuthority](ue_ue.ARSharedWorldGameState.md#hasauthority)
- [HasBegunPlay](ue_ue.ARSharedWorldGameState.md#hasbegunplay)
- [HasMatchStarted](ue_ue.ARSharedWorldGameState.md#hasmatchstarted)
- [IsActorBeingDestroyed](ue_ue.ARSharedWorldGameState.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.ARSharedWorldGameState.md#isactortickenabled)
- [IsChildActor](ue_ue.ARSharedWorldGameState.md#ischildactor)
- [IsEditable](ue_ue.ARSharedWorldGameState.md#iseditable)
- [IsHiddenEd](ue_ue.ARSharedWorldGameState.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.ARSharedWorldGameState.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.ARSharedWorldGameState.md#isoverlappingactor)
- [IsSelectable](ue_ue.ARSharedWorldGameState.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.ARSharedWorldGameState.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.ARSharedWorldGameState.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.ARSharedWorldGameState.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.ARSharedWorldGameState.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.ARSharedWorldGameState.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.ARSharedWorldGameState.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.ARSharedWorldGameState.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.ARSharedWorldGameState.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.ARSharedWorldGameState.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.ARSharedWorldGameState.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.ARSharedWorldGameState.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.ARSharedWorldGameState.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.ARSharedWorldGameState.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.ARSharedWorldGameState.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.ARSharedWorldGameState.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.ARSharedWorldGameState.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.ARSharedWorldGameState.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.ARSharedWorldGameState.md#k2_getrootcomponent)
- [K2\_OnARWorldMapIsReady](ue_ue.ARSharedWorldGameState.md#k2_onarworldmapisready)
- [K2\_OnBecomeViewTarget](ue_ue.ARSharedWorldGameState.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.ARSharedWorldGameState.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.ARSharedWorldGameState.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.ARSharedWorldGameState.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.ARSharedWorldGameState.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.ARSharedWorldGameState.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.ARSharedWorldGameState.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.ARSharedWorldGameState.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.ARSharedWorldGameState.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.ARSharedWorldGameState.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.ARSharedWorldGameState.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.ARSharedWorldGameState.md#makemidformaterial)
- [MakeNoise](ue_ue.ARSharedWorldGameState.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.ARSharedWorldGameState.md#onrep_attachmentreplication)
- [OnRep\_ElapsedTime](ue_ue.ARSharedWorldGameState.md#onrep_elapsedtime)
- [OnRep\_GameModeClass](ue_ue.ARSharedWorldGameState.md#onrep_gamemodeclass)
- [OnRep\_Instigator](ue_ue.ARSharedWorldGameState.md#onrep_instigator)
- [OnRep\_MatchState](ue_ue.ARSharedWorldGameState.md#onrep_matchstate)
- [OnRep\_Owner](ue_ue.ARSharedWorldGameState.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.ARSharedWorldGameState.md#onrep_replicatemovement)
- [OnRep\_ReplicatedHasBegunPlay](ue_ue.ARSharedWorldGameState.md#onrep_replicatedhasbegunplay)
- [OnRep\_ReplicatedMovement](ue_ue.ARSharedWorldGameState.md#onrep_replicatedmovement)
- [OnRep\_ReplicatedWorldTimeSeconds](ue_ue.ARSharedWorldGameState.md#onrep_replicatedworldtimeseconds)
- [OnRep\_SpectatorClass](ue_ue.ARSharedWorldGameState.md#onrep_spectatorclass)
- [PrestreamTextures](ue_ue.ARSharedWorldGameState.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.ARSharedWorldGameState.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.ARSharedWorldGameState.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.ARSharedWorldGameState.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.ARSharedWorldGameState.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.ARSharedWorldGameState.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.ARSharedWorldGameState.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.ARSharedWorldGameState.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.ARSharedWorldGameState.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.ARSharedWorldGameState.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.ARSharedWorldGameState.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.ARSharedWorldGameState.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.ARSharedWorldGameState.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.ARSharedWorldGameState.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.ARSharedWorldGameState.md#receiveendplay)
- [ReceiveHit](ue_ue.ARSharedWorldGameState.md#receivehit)
- [ReceivePointDamage](ue_ue.ARSharedWorldGameState.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.ARSharedWorldGameState.md#receiveradialdamage)
- [ReceiveTick](ue_ue.ARSharedWorldGameState.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.ARSharedWorldGameState.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.ARSharedWorldGameState.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.ARSharedWorldGameState.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.ARSharedWorldGameState.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.ARSharedWorldGameState.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.ARSharedWorldGameState.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.ARSharedWorldGameState.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.ARSharedWorldGameState.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.ARSharedWorldGameState.md#setactortickinterval)
- [SetFolderPath](ue_ue.ARSharedWorldGameState.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.ARSharedWorldGameState.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.ARSharedWorldGameState.md#setlifespan)
- [SetNetDormancy](ue_ue.ARSharedWorldGameState.md#setnetdormancy)
- [SetOwner](ue_ue.ARSharedWorldGameState.md#setowner)
- [SetReplicateMovement](ue_ue.ARSharedWorldGameState.md#setreplicatemovement)
- [SetReplicates](ue_ue.ARSharedWorldGameState.md#setreplicates)
- [SetTickGroup](ue_ue.ARSharedWorldGameState.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.ARSharedWorldGameState.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.ARSharedWorldGameState.md#snaprootcomponentto)
- [TearOff](ue_ue.ARSharedWorldGameState.md#tearoff)
- [UserConstructionScript](ue_ue.ARSharedWorldGameState.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.ARSharedWorldGameState.md#wasrecentlyrendered)
- [Find](ue_ue.ARSharedWorldGameState.md#find)
- [Load](ue_ue.ARSharedWorldGameState.md#load)
- [StaticClass](ue_ue.ARSharedWorldGameState.md#staticclass)

## Constructors

### constructor

• **new ARSharedWorldGameState**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GameState](ue_ue.GameState.md).[constructor](ue_ue.GameState.md#constructor)

## Properties

### ARWorldBytesDelivered

• **ARWorldBytesDelivered**: `number`

___

### ARWorldBytesTotal

• **ARWorldBytesTotal**: `number`

___

### ARWorldData

• **ARWorldData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[GameState](ue_ue.GameState.md).[ActorLabel](ue_ue.GameState.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[AttachmentReplication](ue_ue.GameState.md#attachmentreplication)

___

### AuthorityGameMode

• **AuthorityGameMode**: [`GameModeBase`](ue_ue.GameModeBase.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[AuthorityGameMode](ue_ue.GameState.md#authoritygamemode)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[AutoReceiveInput](ue_ue.GameState.md#autoreceiveinput)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[GameState](ue_ue.GameState.md).[BlueprintCreatedComponents](ue_ue.GameState.md#blueprintcreatedcomponents)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[GameState](ue_ue.GameState.md).[Children](ue_ue.GameState.md#children)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[GameState](ue_ue.GameState.md).[ControllingMatineeActors](ue_ue.GameState.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[CustomTimeDilation](ue_ue.GameState.md#customtimedilation)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.GameState.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### ElapsedTime

• **ElapsedTime**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[ElapsedTime](ue_ue.GameState.md#elapsedtime)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[GameState](ue_ue.GameState.md).[FolderPath](ue_ue.GameState.md#folderpath)

___

### GameModeClass

• **GameModeClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GameModeClass](ue_ue.GameState.md#gamemodeclass)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GroupActor](ue_ue.GameState.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[GameState](ue_ue.GameState.md).[HiddenEditorViews](ue_ue.GameState.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[InitialLifeSpan](ue_ue.GameState.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[InputComponent](ue_ue.GameState.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[InputPriority](ue_ue.GameState.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[GameState](ue_ue.GameState.md).[InstanceComponents](ue_ue.GameState.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[Instigator](ue_ue.GameState.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[Layers](ue_ue.GameState.md#layers)

___

### MatchState

• **MatchState**: `string`

#### Inherited from

[GameState](ue_ue.GameState.md).[MatchState](ue_ue.GameState.md#matchstate)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[MinNetUpdateFrequency](ue_ue.GameState.md#minnetupdatefrequency)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[NetCullDistanceSquared](ue_ue.GameState.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[NetDormancy](ue_ue.GameState.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[GameState](ue_ue.GameState.md).[NetDriverName](ue_ue.GameState.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[NetPriority](ue_ue.GameState.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[NetTag](ue_ue.GameState.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[NetUpdateFrequency](ue_ue.GameState.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnActorBeginOverlap](ue_ue.GameState.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnActorEndOverlap](ue_ue.GameState.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnActorHit](ue_ue.GameState.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnBeginCursorOver](ue_ue.GameState.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnClicked](ue_ue.GameState.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnDestroyed](ue_ue.GameState.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnEndCursorOver](ue_ue.GameState.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnEndPlay](ue_ue.GameState.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnInputTouchBegin](ue_ue.GameState.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnInputTouchEnd](ue_ue.GameState.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnInputTouchEnter](ue_ue.GameState.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnInputTouchLeave](ue_ue.GameState.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnReleased](ue_ue.GameState.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnTakeAnyDamage](ue_ue.GameState.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnTakePointDamage](ue_ue.GameState.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnTakeRadialDamage](ue_ue.GameState.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[Owner](ue_ue.GameState.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[GameState](ue_ue.GameState.md).[ParentComponent](ue_ue.GameState.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[GameState](ue_ue.GameState.md).[ParentComponentActor](ue_ue.GameState.md#parentcomponentactor)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[PivotOffset](ue_ue.GameState.md#pivotoffset)

___

### PlayerArray

• **PlayerArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PlayerState`](ue_ue.PlayerState.md)\>

#### Inherited from

[GameState](ue_ue.GameState.md).[PlayerArray](ue_ue.GameState.md#playerarray)

___

### PreviewImageBytesDelivered

• **PreviewImageBytesDelivered**: `number`

___

### PreviewImageBytesTotal

• **PreviewImageBytesTotal**: `number`

___

### PreviewImageData

• **PreviewImageData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### PreviousMatchState

• **PreviousMatchState**: `string`

#### Inherited from

[GameState](ue_ue.GameState.md).[PreviousMatchState](ue_ue.GameState.md#previousmatchstate)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[PrimaryActorTick](ue_ue.GameState.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[RemoteRole](ue_ue.GameState.md#remoterole)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[ReplicatedMovement](ue_ue.GameState.md#replicatedmovement)

___

### ReplicatedWorldTimeSeconds

• **ReplicatedWorldTimeSeconds**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[ReplicatedWorldTimeSeconds](ue_ue.GameState.md#replicatedworldtimeseconds)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[Role](ue_ue.GameState.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[RootComponent](ue_ue.GameState.md#rootcomponent)

___

### ServerWorldTimeSecondsDelta

• **ServerWorldTimeSecondsDelta**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[ServerWorldTimeSecondsDelta](ue_ue.GameState.md#serverworldtimesecondsdelta)

___

### ServerWorldTimeSecondsUpdateFrequency

• **ServerWorldTimeSecondsUpdateFrequency**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[ServerWorldTimeSecondsUpdateFrequency](ue_ue.GameState.md#serverworldtimesecondsupdatefrequency)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[SpawnCollisionHandlingMethod](ue_ue.GameState.md#spawncollisionhandlingmethod)

___

### SpectatorClass

• **SpectatorClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[SpectatorClass](ue_ue.GameState.md#spectatorclass)

___

### SpriteComponent

• **SpriteComponent**: [`BillboardComponent`](ue_ue.BillboardComponent.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[SpriteComponent](ue_ue.GameState.md#spritecomponent)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[SpriteScale](ue_ue.GameState.md#spritescale)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[Tags](ue_ue.GameState.md#tags)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.GameState.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_ARSharedWorldGameState\_\_

• **\_\_tid\_ARSharedWorldGameState\_\_**: `boolean`

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[__tid_Actor__](ue_ue.GameState.md#__tid_actor__)

___

### \_\_tid\_GameStateBase\_\_

• **\_\_tid\_GameStateBase\_\_**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[__tid_GameStateBase__](ue_ue.GameState.md#__tid_gamestatebase__)

___

### \_\_tid\_GameState\_\_

• **\_\_tid\_GameState\_\_**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[__tid_GameState__](ue_ue.GameState.md#__tid_gamestate__)

___

### \_\_tid\_Info\_\_

• **\_\_tid\_Info\_\_**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[__tid_Info__](ue_ue.GameState.md#__tid_info__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[__tid_Object__](ue_ue.GameState.md#__tid_object__)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bActorEnableCollision](ue_ue.GameState.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bActorIsBeingDestroyed](ue_ue.GameState.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bActorLabelEditable](ue_ue.GameState.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bActorSeamlessTraveled](ue_ue.GameState.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.GameState.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bAllowTickBeforeBeginPlay](ue_ue.GameState.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bAlwaysRelevant](ue_ue.GameState.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bAutoDestroyWhenFinished](ue_ue.GameState.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bBlockInput](ue_ue.GameState.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bCanBeDamaged](ue_ue.GameState.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bCanBeInCluster](ue_ue.GameState.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bCollideWhenPlacing](ue_ue.GameState.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bEditable](ue_ue.GameState.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bEnableAutoLODGeneration](ue_ue.GameState.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bExchangedRoles](ue_ue.GameState.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bFindCameraComponentWhenViewTarget](ue_ue.GameState.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.GameState.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bHidden](ue_ue.GameState.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bHiddenEd](ue_ue.GameState.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bHiddenEdLayer](ue_ue.GameState.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bHiddenEdLevel](ue_ue.GameState.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bHiddenEdTemporary](ue_ue.GameState.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bIgnoresOriginShifting](ue_ue.GameState.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bIsEditorOnlyActor](ue_ue.GameState.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bIsEditorPreviewActor](ue_ue.GameState.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bListedInSceneOutliner](ue_ue.GameState.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bLockLocation](ue_ue.GameState.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bNetLoadOnClient](ue_ue.GameState.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bNetStartup](ue_ue.GameState.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bNetTemporary](ue_ue.GameState.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bNetUseOwnerRelevancy](ue_ue.GameState.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bOnlyRelevantToOwner](ue_ue.GameState.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bOptimizeBPComponentData](ue_ue.GameState.md#boptimizebpcomponentdata)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bRelevantForLevelBounds](ue_ue.GameState.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bRelevantForNetworkReplays](ue_ue.GameState.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bReplayRewindable](ue_ue.GameState.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bReplicateMovement](ue_ue.GameState.md#breplicatemovement)

___

### bReplicatedHasBegunPlay

• **bReplicatedHasBegunPlay**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bReplicatedHasBegunPlay](ue_ue.GameState.md#breplicatedhasbegunplay)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bReplicates](ue_ue.GameState.md#breplicates)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bTearOff](ue_ue.GameState.md#btearoff)

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

[GameState](ue_ue.GameState.md).[ActorHasTag](ue_ue.GameState.md#actorhastag)

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

[GameState](ue_ue.GameState.md).[AddComponent](ue_ue.GameState.md#addcomponent)

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

[GameState](ue_ue.GameState.md).[AddTickPrerequisiteActor](ue_ue.GameState.md#addtickprerequisiteactor)

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

[GameState](ue_ue.GameState.md).[AddTickPrerequisiteComponent](ue_ue.GameState.md#addtickprerequisitecomponent)

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

[GameState](ue_ue.GameState.md).[CreateDefaultSubobject](ue_ue.GameState.md#createdefaultsubobject)

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

[GameState](ue_ue.GameState.md).[DetachRootComponentFromParent](ue_ue.GameState.md#detachrootcomponentfromparent)

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

[GameState](ue_ue.GameState.md).[DisableInput](ue_ue.GameState.md#disableinput)

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

[GameState](ue_ue.GameState.md).[EnableInput](ue_ue.GameState.md#enableinput)

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

[GameState](ue_ue.GameState.md).[ExecuteUbergraph](ue_ue.GameState.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[FlushNetDormancy](ue_ue.GameState.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[ForceNetUpdate](ue_ue.GameState.md#forcenetupdate)

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

[GameState](ue_ue.GameState.md).[GetActorBounds](ue_ue.GameState.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorEnableCollision](ue_ue.GameState.md#getactorenablecollision)

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

[GameState](ue_ue.GameState.md).[GetActorEyesViewPoint](ue_ue.GameState.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorForwardVector](ue_ue.GameState.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorLabel](ue_ue.GameState.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorRelativeScale3D](ue_ue.GameState.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorRightVector](ue_ue.GameState.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorScale3D](ue_ue.GameState.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorTickInterval](ue_ue.GameState.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorTimeDilation](ue_ue.GameState.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorUpVector](ue_ue.GameState.md#getactorupvector)

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

[GameState](ue_ue.GameState.md).[GetAllChildActors](ue_ue.GameState.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetAttachParentActor](ue_ue.GameState.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetAttachParentSocketName](ue_ue.GameState.md#getattachparentsocketname)

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

[GameState](ue_ue.GameState.md).[GetAttachedActors](ue_ue.GameState.md#getattachedactors)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetClass](ue_ue.GameState.md#getclass)

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

[GameState](ue_ue.GameState.md).[GetComponentByClass](ue_ue.GameState.md#getcomponentbyclass)

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

[GameState](ue_ue.GameState.md).[GetComponentsByInterface](ue_ue.GameState.md#getcomponentsbyinterface)

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

[GameState](ue_ue.GameState.md).[GetComponentsByTag](ue_ue.GameState.md#getcomponentsbytag)

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

[GameState](ue_ue.GameState.md).[GetDistanceTo](ue_ue.GameState.md#getdistanceto)

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

[GameState](ue_ue.GameState.md).[GetDotProductTo](ue_ue.GameState.md#getdotproductto)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetFolderPath](ue_ue.GameState.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetGameTimeSinceCreation](ue_ue.GameState.md#getgametimesincecreation)

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

[GameState](ue_ue.GameState.md).[GetHorizontalDistanceTo](ue_ue.GameState.md#gethorizontaldistanceto)

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

[GameState](ue_ue.GameState.md).[GetHorizontalDotProductTo](ue_ue.GameState.md#gethorizontaldotproductto)

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

[GameState](ue_ue.GameState.md).[GetInputAxisKeyValue](ue_ue.GameState.md#getinputaxiskeyvalue)

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

[GameState](ue_ue.GameState.md).[GetInputAxisValue](ue_ue.GameState.md#getinputaxisvalue)

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

[GameState](ue_ue.GameState.md).[GetInputVectorAxisValue](ue_ue.GameState.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetInstigator](ue_ue.GameState.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetInstigatorController](ue_ue.GameState.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetLifeSpan](ue_ue.GameState.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetLocalRole](ue_ue.GameState.md#getlocalrole)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetName](ue_ue.GameState.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetOuter](ue_ue.GameState.md#getouter)

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

[GameState](ue_ue.GameState.md).[GetOverlappingActors](ue_ue.GameState.md#getoverlappingactors)

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

[GameState](ue_ue.GameState.md).[GetOverlappingComponents](ue_ue.GameState.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetOwner](ue_ue.GameState.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetParentActor](ue_ue.GameState.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetParentComponent](ue_ue.GameState.md#getparentcomponent)

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

[GameState](ue_ue.GameState.md).[GetPlayerRespawnDelay](ue_ue.GameState.md#getplayerrespawndelay)

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

[GameState](ue_ue.GameState.md).[GetPlayerStartTime](ue_ue.GameState.md#getplayerstarttime)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetRemoteRole](ue_ue.GameState.md#getremoterole)

___

### GetServerWorldTimeSeconds

▸ **GetServerWorldTimeSeconds**(): `number`

#### Returns

`number`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetServerWorldTimeSeconds](ue_ue.GameState.md#getserverworldtimeseconds)

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

[GameState](ue_ue.GameState.md).[GetSquaredDistanceTo](ue_ue.GameState.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetTickableWhenPaused](ue_ue.GameState.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetTransform](ue_ue.GameState.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetVelocity](ue_ue.GameState.md#getvelocity)

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

[GameState](ue_ue.GameState.md).[GetVerticalDistanceTo](ue_ue.GameState.md#getverticaldistanceto)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetWorld](ue_ue.GameState.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[HasAuthority](ue_ue.GameState.md#hasauthority)

___

### HasBegunPlay

▸ **HasBegunPlay**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[HasBegunPlay](ue_ue.GameState.md#hasbegunplay)

___

### HasMatchStarted

▸ **HasMatchStarted**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[HasMatchStarted](ue_ue.GameState.md#hasmatchstarted)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[IsActorBeingDestroyed](ue_ue.GameState.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[IsActorTickEnabled](ue_ue.GameState.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[IsChildActor](ue_ue.GameState.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[IsEditable](ue_ue.GameState.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[IsHiddenEd](ue_ue.GameState.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[IsHiddenEdAtStartup](ue_ue.GameState.md#ishiddenedatstartup)

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

[GameState](ue_ue.GameState.md).[IsOverlappingActor](ue_ue.GameState.md#isoverlappingactor)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[IsSelectable](ue_ue.GameState.md#isselectable)

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

[GameState](ue_ue.GameState.md).[IsTemporarilyHiddenInEditor](ue_ue.GameState.md#istemporarilyhiddenineditor)

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

[GameState](ue_ue.GameState.md).[K2_AddActorLocalOffset](ue_ue.GameState.md#k2_addactorlocaloffset)

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

[GameState](ue_ue.GameState.md).[K2_AddActorLocalRotation](ue_ue.GameState.md#k2_addactorlocalrotation)

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

[GameState](ue_ue.GameState.md).[K2_AddActorLocalTransform](ue_ue.GameState.md#k2_addactorlocaltransform)

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

[GameState](ue_ue.GameState.md).[K2_AddActorWorldOffset](ue_ue.GameState.md#k2_addactorworldoffset)

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

[GameState](ue_ue.GameState.md).[K2_AddActorWorldRotation](ue_ue.GameState.md#k2_addactorworldrotation)

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

[GameState](ue_ue.GameState.md).[K2_AddActorWorldTransform](ue_ue.GameState.md#k2_addactorworldtransform)

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

[GameState](ue_ue.GameState.md).[K2_AttachRootComponentTo](ue_ue.GameState.md#k2_attachrootcomponentto)

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

[GameState](ue_ue.GameState.md).[K2_AttachRootComponentToActor](ue_ue.GameState.md#k2_attachrootcomponenttoactor)

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

[GameState](ue_ue.GameState.md).[K2_AttachToActor](ue_ue.GameState.md#k2_attachtoactor)

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

[GameState](ue_ue.GameState.md).[K2_AttachToComponent](ue_ue.GameState.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[K2_DestroyActor](ue_ue.GameState.md#k2_destroyactor)

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

[GameState](ue_ue.GameState.md).[K2_DestroyComponent](ue_ue.GameState.md#k2_destroycomponent)

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

[GameState](ue_ue.GameState.md).[K2_DetachFromActor](ue_ue.GameState.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[K2_GetActorLocation](ue_ue.GameState.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[K2_GetActorRotation](ue_ue.GameState.md#k2_getactorrotation)

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

[GameState](ue_ue.GameState.md).[K2_GetComponentsByClass](ue_ue.GameState.md#k2_getcomponentsbyclass)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[K2_GetRootComponent](ue_ue.GameState.md#k2_getrootcomponent)

___

### K2\_OnARWorldMapIsReady

▸ **K2_OnARWorldMapIsReady**(): `void`

#### Returns

`void`

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

[GameState](ue_ue.GameState.md).[K2_OnBecomeViewTarget](ue_ue.GameState.md#k2_onbecomeviewtarget)

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

[GameState](ue_ue.GameState.md).[K2_OnEndViewTarget](ue_ue.GameState.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[K2_OnReset](ue_ue.GameState.md#k2_onreset)

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

[GameState](ue_ue.GameState.md).[K2_SetActorLocation](ue_ue.GameState.md#k2_setactorlocation)

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

[GameState](ue_ue.GameState.md).[K2_SetActorLocationAndRotation](ue_ue.GameState.md#k2_setactorlocationandrotation)

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

[GameState](ue_ue.GameState.md).[K2_SetActorRelativeLocation](ue_ue.GameState.md#k2_setactorrelativelocation)

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

[GameState](ue_ue.GameState.md).[K2_SetActorRelativeRotation](ue_ue.GameState.md#k2_setactorrelativerotation)

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

[GameState](ue_ue.GameState.md).[K2_SetActorRelativeTransform](ue_ue.GameState.md#k2_setactorrelativetransform)

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

[GameState](ue_ue.GameState.md).[K2_SetActorRotation](ue_ue.GameState.md#k2_setactorrotation)

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

[GameState](ue_ue.GameState.md).[K2_SetActorTransform](ue_ue.GameState.md#k2_setactortransform)

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

[GameState](ue_ue.GameState.md).[K2_TeleportTo](ue_ue.GameState.md#k2_teleportto)

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

[GameState](ue_ue.GameState.md).[MakeMIDForMaterial](ue_ue.GameState.md#makemidformaterial)

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

[GameState](ue_ue.GameState.md).[MakeNoise](ue_ue.GameState.md#makenoise)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_AttachmentReplication](ue_ue.GameState.md#onrep_attachmentreplication)

___

### OnRep\_ElapsedTime

▸ **OnRep_ElapsedTime**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_ElapsedTime](ue_ue.GameState.md#onrep_elapsedtime)

___

### OnRep\_GameModeClass

▸ **OnRep_GameModeClass**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_GameModeClass](ue_ue.GameState.md#onrep_gamemodeclass)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_Instigator](ue_ue.GameState.md#onrep_instigator)

___

### OnRep\_MatchState

▸ **OnRep_MatchState**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_MatchState](ue_ue.GameState.md#onrep_matchstate)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_Owner](ue_ue.GameState.md#onrep_owner)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_ReplicateMovement](ue_ue.GameState.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedHasBegunPlay

▸ **OnRep_ReplicatedHasBegunPlay**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_ReplicatedHasBegunPlay](ue_ue.GameState.md#onrep_replicatedhasbegunplay)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_ReplicatedMovement](ue_ue.GameState.md#onrep_replicatedmovement)

___

### OnRep\_ReplicatedWorldTimeSeconds

▸ **OnRep_ReplicatedWorldTimeSeconds**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_ReplicatedWorldTimeSeconds](ue_ue.GameState.md#onrep_replicatedworldtimeseconds)

___

### OnRep\_SpectatorClass

▸ **OnRep_SpectatorClass**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_SpectatorClass](ue_ue.GameState.md#onrep_spectatorclass)

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

[GameState](ue_ue.GameState.md).[PrestreamTextures](ue_ue.GameState.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[ReceiveActorBeginCursorOver](ue_ue.GameState.md#receiveactorbegincursorover)

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

[GameState](ue_ue.GameState.md).[ReceiveActorBeginOverlap](ue_ue.GameState.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[ReceiveActorEndCursorOver](ue_ue.GameState.md#receiveactorendcursorover)

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

[GameState](ue_ue.GameState.md).[ReceiveActorEndOverlap](ue_ue.GameState.md#receiveactorendoverlap)

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

[GameState](ue_ue.GameState.md).[ReceiveActorOnClicked](ue_ue.GameState.md#receiveactoronclicked)

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

[GameState](ue_ue.GameState.md).[ReceiveActorOnInputTouchBegin](ue_ue.GameState.md#receiveactoroninputtouchbegin)

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

[GameState](ue_ue.GameState.md).[ReceiveActorOnInputTouchEnd](ue_ue.GameState.md#receiveactoroninputtouchend)

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

[GameState](ue_ue.GameState.md).[ReceiveActorOnInputTouchEnter](ue_ue.GameState.md#receiveactoroninputtouchenter)

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

[GameState](ue_ue.GameState.md).[ReceiveActorOnInputTouchLeave](ue_ue.GameState.md#receiveactoroninputtouchleave)

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

[GameState](ue_ue.GameState.md).[ReceiveActorOnReleased](ue_ue.GameState.md#receiveactoronreleased)

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

[GameState](ue_ue.GameState.md).[ReceiveAnyDamage](ue_ue.GameState.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[ReceiveBeginPlay](ue_ue.GameState.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[ReceiveDestroyed](ue_ue.GameState.md#receivedestroyed)

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

[GameState](ue_ue.GameState.md).[ReceiveEndPlay](ue_ue.GameState.md#receiveendplay)

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

[GameState](ue_ue.GameState.md).[ReceiveHit](ue_ue.GameState.md#receivehit)

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

[GameState](ue_ue.GameState.md).[ReceivePointDamage](ue_ue.GameState.md#receivepointdamage)

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

[GameState](ue_ue.GameState.md).[ReceiveRadialDamage](ue_ue.GameState.md#receiveradialdamage)

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

[GameState](ue_ue.GameState.md).[ReceiveTick](ue_ue.GameState.md#receivetick)

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

[GameState](ue_ue.GameState.md).[RemoveTickPrerequisiteActor](ue_ue.GameState.md#removetickprerequisiteactor)

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

[GameState](ue_ue.GameState.md).[RemoveTickPrerequisiteComponent](ue_ue.GameState.md#removetickprerequisitecomponent)

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

[GameState](ue_ue.GameState.md).[SetActorEnableCollision](ue_ue.GameState.md#setactorenablecollision)

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

[GameState](ue_ue.GameState.md).[SetActorHiddenInGame](ue_ue.GameState.md#setactorhiddeningame)

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

[GameState](ue_ue.GameState.md).[SetActorLabel](ue_ue.GameState.md#setactorlabel)

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

[GameState](ue_ue.GameState.md).[SetActorRelativeScale3D](ue_ue.GameState.md#setactorrelativescale3d)

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

[GameState](ue_ue.GameState.md).[SetActorScale3D](ue_ue.GameState.md#setactorscale3d)

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

[GameState](ue_ue.GameState.md).[SetActorTickEnabled](ue_ue.GameState.md#setactortickenabled)

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

[GameState](ue_ue.GameState.md).[SetActorTickInterval](ue_ue.GameState.md#setactortickinterval)

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

[GameState](ue_ue.GameState.md).[SetFolderPath](ue_ue.GameState.md#setfolderpath)

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

[GameState](ue_ue.GameState.md).[SetIsTemporarilyHiddenInEditor](ue_ue.GameState.md#setistemporarilyhiddenineditor)

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

[GameState](ue_ue.GameState.md).[SetLifeSpan](ue_ue.GameState.md#setlifespan)

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

[GameState](ue_ue.GameState.md).[SetNetDormancy](ue_ue.GameState.md#setnetdormancy)

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

[GameState](ue_ue.GameState.md).[SetOwner](ue_ue.GameState.md#setowner)

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

[GameState](ue_ue.GameState.md).[SetReplicateMovement](ue_ue.GameState.md#setreplicatemovement)

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

[GameState](ue_ue.GameState.md).[SetReplicates](ue_ue.GameState.md#setreplicates)

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

[GameState](ue_ue.GameState.md).[SetTickGroup](ue_ue.GameState.md#settickgroup)

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

[GameState](ue_ue.GameState.md).[SetTickableWhenPaused](ue_ue.GameState.md#settickablewhenpaused)

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

[GameState](ue_ue.GameState.md).[SnapRootComponentTo](ue_ue.GameState.md#snaprootcomponentto)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[TearOff](ue_ue.GameState.md#tearoff)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[UserConstructionScript](ue_ue.GameState.md#userconstructionscript)

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

[GameState](ue_ue.GameState.md).[WasRecentlyRendered](ue_ue.GameState.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARSharedWorldGameState`](ue_ue.ARSharedWorldGameState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARSharedWorldGameState`](ue_ue.ARSharedWorldGameState.md)

#### Overrides

[GameState](ue_ue.GameState.md).[Find](ue_ue.GameState.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ARSharedWorldGameState`](ue_ue.ARSharedWorldGameState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARSharedWorldGameState`](ue_ue.ARSharedWorldGameState.md)

#### Overrides

[GameState](ue_ue.GameState.md).[Load](ue_ue.GameState.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameState](ue_ue.GameState.md).[StaticClass](ue_ue.GameState.md#staticclass)
