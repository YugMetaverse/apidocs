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

#### Defined in

[ue/ue.d.ts:21312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21312)

## Properties

### ARWorldBytesDelivered

• **ARWorldBytesDelivered**: `number`

#### Defined in

[ue/ue.d.ts:21318](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21318)

___

### ARWorldBytesTotal

• **ARWorldBytesTotal**: `number`

#### Defined in

[ue/ue.d.ts:21316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21316)

___

### ARWorldData

• **ARWorldData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:21314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21314)

___

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[GameState](ue_ue.GameState.md).[ActorLabel](ue_ue.GameState.md#actorlabel)

#### Defined in

[ue/ue.d.ts:13176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13176)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[AttachmentReplication](ue_ue.GameState.md#attachmentreplication)

#### Defined in

[ue/ue.d.ts:13151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13151)

___

### AuthorityGameMode

• **AuthorityGameMode**: [`GameModeBase`](ue_ue.GameModeBase.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[AuthorityGameMode](ue_ue.GameState.md#authoritygamemode)

#### Defined in

[ue/ue.d.ts:9927](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9927)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[AutoReceiveInput](ue_ue.GameState.md#autoreceiveinput)

#### Defined in

[ue/ue.d.ts:13157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13157)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[GameState](ue_ue.GameState.md).[BlueprintCreatedComponents](ue_ue.GameState.md#blueprintcreatedcomponents)

#### Defined in

[ue/ue.d.ts:13206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13206)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[GameState](ue_ue.GameState.md).[Children](ue_ue.GameState.md#children)

#### Defined in

[ue/ue.d.ts:13166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13166)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[GameState](ue_ue.GameState.md).[ControllingMatineeActors](ue_ue.GameState.md#controllingmatineeactors)

#### Defined in

[ue/ue.d.ts:13169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13169)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[CustomTimeDilation](ue_ue.GameState.md#customtimedilation)

#### Defined in

[ue/ue.d.ts:13150](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13150)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.GameState.md#defaultupdateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13146](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13146)

___

### ElapsedTime

• **ElapsedTime**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[ElapsedTime](ue_ue.GameState.md#elapsedtime)

#### Defined in

[ue/ue.d.ts:21301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21301)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[GameState](ue_ue.GameState.md).[FolderPath](ue_ue.GameState.md#folderpath)

#### Defined in

[ue/ue.d.ts:13177](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13177)

___

### GameModeClass

• **GameModeClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GameModeClass](ue_ue.GameState.md#gamemodeclass)

#### Defined in

[ue/ue.d.ts:9926](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9926)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GroupActor](ue_ue.GameState.md#groupactor)

#### Defined in

[ue/ue.d.ts:13173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13173)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[GameState](ue_ue.GameState.md).[HiddenEditorViews](ue_ue.GameState.md#hiddeneditorviews)

#### Defined in

[ue/ue.d.ts:13175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13175)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[InitialLifeSpan](ue_ue.GameState.md#initiallifespan)

#### Defined in

[ue/ue.d.ts:13149](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13149)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[InputComponent](ue_ue.GameState.md#inputcomponent)

#### Defined in

[ue/ue.d.ts:13159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13159)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[InputPriority](ue_ue.GameState.md#inputpriority)

#### Defined in

[ue/ue.d.ts:13158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13158)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[GameState](ue_ue.GameState.md).[InstanceComponents](ue_ue.GameState.md#instancecomponents)

#### Defined in

[ue/ue.d.ts:13205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13205)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[Instigator](ue_ue.GameState.md#instigator)

#### Defined in

[ue/ue.d.ts:13165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13165)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[Layers](ue_ue.GameState.md#layers)

#### Defined in

[ue/ue.d.ts:13170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13170)

___

### MatchState

• **MatchState**: `string`

#### Inherited from

[GameState](ue_ue.GameState.md).[MatchState](ue_ue.GameState.md#matchstate)

#### Defined in

[ue/ue.d.ts:21299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21299)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[MinNetUpdateFrequency](ue_ue.GameState.md#minnetupdatefrequency)

#### Defined in

[ue/ue.d.ts:13163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13163)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[NetCullDistanceSquared](ue_ue.GameState.md#netculldistancesquared)

#### Defined in

[ue/ue.d.ts:13160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13160)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[NetDormancy](ue_ue.GameState.md#netdormancy)

#### Defined in

[ue/ue.d.ts:13155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13155)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[GameState](ue_ue.GameState.md).[NetDriverName](ue_ue.GameState.md#netdrivername)

#### Defined in

[ue/ue.d.ts:13153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13153)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[NetPriority](ue_ue.GameState.md#netpriority)

#### Defined in

[ue/ue.d.ts:13164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13164)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[NetTag](ue_ue.GameState.md#nettag)

#### Defined in

[ue/ue.d.ts:13161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13161)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[NetUpdateFrequency](ue_ue.GameState.md#netupdatefrequency)

#### Defined in

[ue/ue.d.ts:13162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13162)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnActorBeginOverlap](ue_ue.GameState.md#onactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13192)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnActorEndOverlap](ue_ue.GameState.md#onactorendoverlap)

#### Defined in

[ue/ue.d.ts:13193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13193)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnActorHit](ue_ue.GameState.md#onactorhit)

#### Defined in

[ue/ue.d.ts:13202](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13202)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnBeginCursorOver](ue_ue.GameState.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:13194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13194)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnClicked](ue_ue.GameState.md#onclicked)

#### Defined in

[ue/ue.d.ts:13196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13196)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnDestroyed](ue_ue.GameState.md#ondestroyed)

#### Defined in

[ue/ue.d.ts:13203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13203)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnEndCursorOver](ue_ue.GameState.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:13195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13195)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnEndPlay](ue_ue.GameState.md#onendplay)

#### Defined in

[ue/ue.d.ts:13204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13204)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnInputTouchBegin](ue_ue.GameState.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13198)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnInputTouchEnd](ue_ue.GameState.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:13199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13199)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnInputTouchEnter](ue_ue.GameState.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:13200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13200)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnInputTouchLeave](ue_ue.GameState.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:13201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13201)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnReleased](ue_ue.GameState.md#onreleased)

#### Defined in

[ue/ue.d.ts:13197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13197)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnTakeAnyDamage](ue_ue.GameState.md#ontakeanydamage)

#### Defined in

[ue/ue.d.ts:13189](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13189)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnTakePointDamage](ue_ue.GameState.md#ontakepointdamage)

#### Defined in

[ue/ue.d.ts:13190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13190)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[OnTakeRadialDamage](ue_ue.GameState.md#ontakeradialdamage)

#### Defined in

[ue/ue.d.ts:13191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13191)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[Owner](ue_ue.GameState.md#owner)

#### Defined in

[ue/ue.d.ts:13152](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13152)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[GameState](ue_ue.GameState.md).[ParentComponent](ue_ue.GameState.md#parentcomponent)

#### Defined in

[ue/ue.d.ts:13172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13172)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[GameState](ue_ue.GameState.md).[ParentComponentActor](ue_ue.GameState.md#parentcomponentactor)

#### Defined in

[ue/ue.d.ts:13171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13171)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[PivotOffset](ue_ue.GameState.md#pivotoffset)

#### Defined in

[ue/ue.d.ts:13168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13168)

___

### PlayerArray

• **PlayerArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PlayerState`](ue_ue.PlayerState.md)\>

#### Inherited from

[GameState](ue_ue.GameState.md).[PlayerArray](ue_ue.GameState.md#playerarray)

#### Defined in

[ue/ue.d.ts:9929](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9929)

___

### PreviewImageBytesDelivered

• **PreviewImageBytesDelivered**: `number`

#### Defined in

[ue/ue.d.ts:21317](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21317)

___

### PreviewImageBytesTotal

• **PreviewImageBytesTotal**: `number`

#### Defined in

[ue/ue.d.ts:21315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21315)

___

### PreviewImageData

• **PreviewImageData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:21313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21313)

___

### PreviousMatchState

• **PreviousMatchState**: `string`

#### Inherited from

[GameState](ue_ue.GameState.md).[PreviousMatchState](ue_ue.GameState.md#previousmatchstate)

#### Defined in

[ue/ue.d.ts:21300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21300)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[PrimaryActorTick](ue_ue.GameState.md#primaryactortick)

#### Defined in

[ue/ue.d.ts:13115](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13115)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[RemoteRole](ue_ue.GameState.md#remoterole)

#### Defined in

[ue/ue.d.ts:13147](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13147)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[ReplicatedMovement](ue_ue.GameState.md#replicatedmovement)

#### Defined in

[ue/ue.d.ts:13148](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13148)

___

### ReplicatedWorldTimeSeconds

• **ReplicatedWorldTimeSeconds**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[ReplicatedWorldTimeSeconds](ue_ue.GameState.md#replicatedworldtimeseconds)

#### Defined in

[ue/ue.d.ts:9931](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9931)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[Role](ue_ue.GameState.md#role)

#### Defined in

[ue/ue.d.ts:13154](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13154)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[RootComponent](ue_ue.GameState.md#rootcomponent)

#### Defined in

[ue/ue.d.ts:13167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13167)

___

### ServerWorldTimeSecondsDelta

• **ServerWorldTimeSecondsDelta**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[ServerWorldTimeSecondsDelta](ue_ue.GameState.md#serverworldtimesecondsdelta)

#### Defined in

[ue/ue.d.ts:9932](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9932)

___

### ServerWorldTimeSecondsUpdateFrequency

• **ServerWorldTimeSecondsUpdateFrequency**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[ServerWorldTimeSecondsUpdateFrequency](ue_ue.GameState.md#serverworldtimesecondsupdatefrequency)

#### Defined in

[ue/ue.d.ts:9933](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9933)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[SpawnCollisionHandlingMethod](ue_ue.GameState.md#spawncollisionhandlingmethod)

#### Defined in

[ue/ue.d.ts:13156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13156)

___

### SpectatorClass

• **SpectatorClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[SpectatorClass](ue_ue.GameState.md#spectatorclass)

#### Defined in

[ue/ue.d.ts:9928](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9928)

___

### SpriteComponent

• **SpriteComponent**: [`BillboardComponent`](ue_ue.BillboardComponent.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[SpriteComponent](ue_ue.GameState.md#spritecomponent)

#### Defined in

[ue/ue.d.ts:2215](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2215)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[GameState](ue_ue.GameState.md).[SpriteScale](ue_ue.GameState.md#spritescale)

#### Defined in

[ue/ue.d.ts:13174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13174)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GameState](ue_ue.GameState.md).[Tags](ue_ue.GameState.md#tags)

#### Defined in

[ue/ue.d.ts:13188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13188)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.GameState.md#updateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13145](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13145)

___

### \_\_tid\_ARSharedWorldGameState\_\_

• **\_\_tid\_ARSharedWorldGameState\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:21324](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21324)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[__tid_Actor__](ue_ue.GameState.md#__tid_actor__)

#### Defined in

[ue/ue.d.ts:13348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13348)

___

### \_\_tid\_GameStateBase\_\_

• **\_\_tid\_GameStateBase\_\_**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[__tid_GameStateBase__](ue_ue.GameState.md#__tid_gamestatebase__)

#### Defined in

[ue/ue.d.ts:9947](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9947)

___

### \_\_tid\_GameState\_\_

• **\_\_tid\_GameState\_\_**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[__tid_GameState__](ue_ue.GameState.md#__tid_gamestate__)

#### Defined in

[ue/ue.d.ts:21308](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21308)

___

### \_\_tid\_Info\_\_

• **\_\_tid\_Info\_\_**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[__tid_Info__](ue_ue.GameState.md#__tid_info__)

#### Defined in

[ue/ue.d.ts:2220](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2220)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[__tid_Object__](ue_ue.GameState.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bActorEnableCollision](ue_ue.GameState.md#bactorenablecollision)

#### Defined in

[ue/ue.d.ts:13143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13143)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bActorIsBeingDestroyed](ue_ue.GameState.md#bactorisbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13144](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13144)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bActorLabelEditable](ue_ue.GameState.md#bactorlabeleditable)

#### Defined in

[ue/ue.d.ts:13183](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13183)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bActorSeamlessTraveled](ue_ue.GameState.md#bactorseamlesstraveled)

#### Defined in

[ue/ue.d.ts:13139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13139)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.GameState.md#ballowreceivetickeventondedicatedserver)

#### Defined in

[ue/ue.d.ts:13142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13142)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bAllowTickBeforeBeginPlay](ue_ue.GameState.md#ballowtickbeforebeginplay)

#### Defined in

[ue/ue.d.ts:13129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13129)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bAlwaysRelevant](ue_ue.GameState.md#balwaysrelevant)

#### Defined in

[ue/ue.d.ts:13120](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13120)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bAutoDestroyWhenFinished](ue_ue.GameState.md#bautodestroywhenfinished)

#### Defined in

[ue/ue.d.ts:13130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13130)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bBlockInput](ue_ue.GameState.md#bblockinput)

#### Defined in

[ue/ue.d.ts:13131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13131)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bCanBeDamaged](ue_ue.GameState.md#bcanbedamaged)

#### Defined in

[ue/ue.d.ts:13132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13132)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bCanBeInCluster](ue_ue.GameState.md#bcanbeincluster)

#### Defined in

[ue/ue.d.ts:13141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13141)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bCollideWhenPlacing](ue_ue.GameState.md#bcollidewhenplacing)

#### Defined in

[ue/ue.d.ts:13133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13133)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bEditable](ue_ue.GameState.md#beditable)

#### Defined in

[ue/ue.d.ts:13184](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13184)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bEnableAutoLODGeneration](ue_ue.GameState.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:13137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13137)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bExchangedRoles](ue_ue.GameState.md#bexchangedroles)

#### Defined in

[ue/ue.d.ts:13123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13123)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bFindCameraComponentWhenViewTarget](ue_ue.GameState.md#bfindcameracomponentwhenviewtarget)

#### Defined in

[ue/ue.d.ts:13134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13134)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.GameState.md#bgenerateoverlapeventsduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13135)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bHidden](ue_ue.GameState.md#bhidden)

#### Defined in

[ue/ue.d.ts:13116](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13116)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bHiddenEd](ue_ue.GameState.md#bhiddened)

#### Defined in

[ue/ue.d.ts:13178](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13178)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bHiddenEdLayer](ue_ue.GameState.md#bhiddenedlayer)

#### Defined in

[ue/ue.d.ts:13180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13180)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bHiddenEdLevel](ue_ue.GameState.md#bhiddenedlevel)

#### Defined in

[ue/ue.d.ts:13181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13181)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bHiddenEdTemporary](ue_ue.GameState.md#bhiddenedtemporary)

#### Defined in

[ue/ue.d.ts:13187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13187)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bIgnoresOriginShifting](ue_ue.GameState.md#bignoresoriginshifting)

#### Defined in

[ue/ue.d.ts:13136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13136)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bIsEditorOnlyActor](ue_ue.GameState.md#biseditoronlyactor)

#### Defined in

[ue/ue.d.ts:13138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13138)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bIsEditorPreviewActor](ue_ue.GameState.md#biseditorpreviewactor)

#### Defined in

[ue/ue.d.ts:13179](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13179)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bListedInSceneOutliner](ue_ue.GameState.md#blistedinsceneoutliner)

#### Defined in

[ue/ue.d.ts:13185](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13185)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bLockLocation](ue_ue.GameState.md#blocklocation)

#### Defined in

[ue/ue.d.ts:13182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13182)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bNetLoadOnClient](ue_ue.GameState.md#bnetloadonclient)

#### Defined in

[ue/ue.d.ts:13124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13124)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bNetStartup](ue_ue.GameState.md#bnetstartup)

#### Defined in

[ue/ue.d.ts:13118](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13118)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bNetTemporary](ue_ue.GameState.md#bnettemporary)

#### Defined in

[ue/ue.d.ts:13117](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13117)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bNetUseOwnerRelevancy](ue_ue.GameState.md#bnetuseownerrelevancy)

#### Defined in

[ue/ue.d.ts:13125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13125)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bOnlyRelevantToOwner](ue_ue.GameState.md#bonlyrelevanttoowner)

#### Defined in

[ue/ue.d.ts:13119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13119)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bOptimizeBPComponentData](ue_ue.GameState.md#boptimizebpcomponentdata)

#### Defined in

[ue/ue.d.ts:13186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13186)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bRelevantForLevelBounds](ue_ue.GameState.md#brelevantforlevelbounds)

#### Defined in

[ue/ue.d.ts:13127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13127)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bRelevantForNetworkReplays](ue_ue.GameState.md#brelevantfornetworkreplays)

#### Defined in

[ue/ue.d.ts:13126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13126)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bReplayRewindable](ue_ue.GameState.md#breplayrewindable)

#### Defined in

[ue/ue.d.ts:13128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13128)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bReplicateMovement](ue_ue.GameState.md#breplicatemovement)

#### Defined in

[ue/ue.d.ts:13121](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13121)

___

### bReplicatedHasBegunPlay

• **bReplicatedHasBegunPlay**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bReplicatedHasBegunPlay](ue_ue.GameState.md#breplicatedhasbegunplay)

#### Defined in

[ue/ue.d.ts:9930](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9930)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bReplicates](ue_ue.GameState.md#breplicates)

#### Defined in

[ue/ue.d.ts:13140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13140)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[bTearOff](ue_ue.GameState.md#btearoff)

#### Defined in

[ue/ue.d.ts:13122](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13122)

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

[GameState](ue_ue.GameState.md).[AddComponent](ue_ue.GameState.md#addcomponent)

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

[GameState](ue_ue.GameState.md).[AddTickPrerequisiteActor](ue_ue.GameState.md#addtickprerequisiteactor)

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

[GameState](ue_ue.GameState.md).[AddTickPrerequisiteComponent](ue_ue.GameState.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13210](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13210)

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

[GameState](ue_ue.GameState.md).[DetachRootComponentFromParent](ue_ue.GameState.md#detachrootcomponentfromparent)

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

[GameState](ue_ue.GameState.md).[DisableInput](ue_ue.GameState.md#disableinput)

#### Defined in

[ue/ue.d.ts:13212](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13212)

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

[GameState](ue_ue.GameState.md).[ExecuteUbergraph](ue_ue.GameState.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[FlushNetDormancy](ue_ue.GameState.md#flushnetdormancy)

#### Defined in

[ue/ue.d.ts:13214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13214)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[ForceNetUpdate](ue_ue.GameState.md#forcenetupdate)

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

[GameState](ue_ue.GameState.md).[GetActorBounds](ue_ue.GameState.md#getactorbounds)

#### Defined in

[ue/ue.d.ts:13216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13216)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorEnableCollision](ue_ue.GameState.md#getactorenablecollision)

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

[GameState](ue_ue.GameState.md).[GetActorEyesViewPoint](ue_ue.GameState.md#getactoreyesviewpoint)

#### Defined in

[ue/ue.d.ts:13218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13218)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorForwardVector](ue_ue.GameState.md#getactorforwardvector)

#### Defined in

[ue/ue.d.ts:13219](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13219)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorLabel](ue_ue.GameState.md#getactorlabel)

#### Defined in

[ue/ue.d.ts:13220](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13220)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorRelativeScale3D](ue_ue.GameState.md#getactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13221](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13221)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorRightVector](ue_ue.GameState.md#getactorrightvector)

#### Defined in

[ue/ue.d.ts:13222](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13222)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorScale3D](ue_ue.GameState.md#getactorscale3d)

#### Defined in

[ue/ue.d.ts:13223](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13223)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorTickInterval](ue_ue.GameState.md#getactortickinterval)

#### Defined in

[ue/ue.d.ts:13224](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13224)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorTimeDilation](ue_ue.GameState.md#getactortimedilation)

#### Defined in

[ue/ue.d.ts:13225](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13225)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetActorUpVector](ue_ue.GameState.md#getactorupvector)

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

[GameState](ue_ue.GameState.md).[GetAllChildActors](ue_ue.GameState.md#getallchildactors)

#### Defined in

[ue/ue.d.ts:13227](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13227)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetAttachParentActor](ue_ue.GameState.md#getattachparentactor)

#### Defined in

[ue/ue.d.ts:13229](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13229)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetAttachParentSocketName](ue_ue.GameState.md#getattachparentsocketname)

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

[GameState](ue_ue.GameState.md).[GetAttachedActors](ue_ue.GameState.md#getattachedactors)

#### Defined in

[ue/ue.d.ts:13228](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13228)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetClass](ue_ue.GameState.md#getclass)

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

[GameState](ue_ue.GameState.md).[GetComponentByClass](ue_ue.GameState.md#getcomponentbyclass)

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

[GameState](ue_ue.GameState.md).[GetComponentsByInterface](ue_ue.GameState.md#getcomponentsbyinterface)

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

[GameState](ue_ue.GameState.md).[GetComponentsByTag](ue_ue.GameState.md#getcomponentsbytag)

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

[GameState](ue_ue.GameState.md).[GetDistanceTo](ue_ue.GameState.md#getdistanceto)

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

[GameState](ue_ue.GameState.md).[GetDotProductTo](ue_ue.GameState.md#getdotproductto)

#### Defined in

[ue/ue.d.ts:13235](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13235)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetFolderPath](ue_ue.GameState.md#getfolderpath)

#### Defined in

[ue/ue.d.ts:13236](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13236)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetGameTimeSinceCreation](ue_ue.GameState.md#getgametimesincecreation)

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

[GameState](ue_ue.GameState.md).[GetHorizontalDistanceTo](ue_ue.GameState.md#gethorizontaldistanceto)

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

[GameState](ue_ue.GameState.md).[GetHorizontalDotProductTo](ue_ue.GameState.md#gethorizontaldotproductto)

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

[GameState](ue_ue.GameState.md).[GetInputAxisKeyValue](ue_ue.GameState.md#getinputaxiskeyvalue)

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

[GameState](ue_ue.GameState.md).[GetInputAxisValue](ue_ue.GameState.md#getinputaxisvalue)

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

[GameState](ue_ue.GameState.md).[GetInputVectorAxisValue](ue_ue.GameState.md#getinputvectoraxisvalue)

#### Defined in

[ue/ue.d.ts:13242](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13242)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetInstigator](ue_ue.GameState.md#getinstigator)

#### Defined in

[ue/ue.d.ts:13243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13243)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetInstigatorController](ue_ue.GameState.md#getinstigatorcontroller)

#### Defined in

[ue/ue.d.ts:13244](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13244)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetLifeSpan](ue_ue.GameState.md#getlifespan)

#### Defined in

[ue/ue.d.ts:13245](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13245)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetLocalRole](ue_ue.GameState.md#getlocalrole)

#### Defined in

[ue/ue.d.ts:13246](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13246)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetName](ue_ue.GameState.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetOuter](ue_ue.GameState.md#getouter)

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

[GameState](ue_ue.GameState.md).[GetOverlappingActors](ue_ue.GameState.md#getoverlappingactors)

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

[GameState](ue_ue.GameState.md).[GetOverlappingComponents](ue_ue.GameState.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:13248](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13248)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetOwner](ue_ue.GameState.md#getowner)

#### Defined in

[ue/ue.d.ts:13249](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13249)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetParentActor](ue_ue.GameState.md#getparentactor)

#### Defined in

[ue/ue.d.ts:13250](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13250)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetParentComponent](ue_ue.GameState.md#getparentcomponent)

#### Defined in

[ue/ue.d.ts:13251](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13251)

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

#### Defined in

[ue/ue.d.ts:9934](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9934)

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

#### Defined in

[ue/ue.d.ts:9935](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9935)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetRemoteRole](ue_ue.GameState.md#getremoterole)

#### Defined in

[ue/ue.d.ts:13252](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13252)

___

### GetServerWorldTimeSeconds

▸ **GetServerWorldTimeSeconds**(): `number`

#### Returns

`number`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetServerWorldTimeSeconds](ue_ue.GameState.md#getserverworldtimeseconds)

#### Defined in

[ue/ue.d.ts:9936](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9936)

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

#### Defined in

[ue/ue.d.ts:13253](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13253)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[GetTickableWhenPaused](ue_ue.GameState.md#gettickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13254](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13254)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetTransform](ue_ue.GameState.md#gettransform)

#### Defined in

[ue/ue.d.ts:13255](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13255)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetVelocity](ue_ue.GameState.md#getvelocity)

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

[GameState](ue_ue.GameState.md).[GetVerticalDistanceTo](ue_ue.GameState.md#getverticaldistanceto)

#### Defined in

[ue/ue.d.ts:13257](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13257)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[GetWorld](ue_ue.GameState.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[HasAuthority](ue_ue.GameState.md#hasauthority)

#### Defined in

[ue/ue.d.ts:13258](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13258)

___

### HasBegunPlay

▸ **HasBegunPlay**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[HasBegunPlay](ue_ue.GameState.md#hasbegunplay)

#### Defined in

[ue/ue.d.ts:9937](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9937)

___

### HasMatchStarted

▸ **HasMatchStarted**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[HasMatchStarted](ue_ue.GameState.md#hasmatchstarted)

#### Defined in

[ue/ue.d.ts:9938](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9938)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[IsActorBeingDestroyed](ue_ue.GameState.md#isactorbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13259](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13259)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[IsActorTickEnabled](ue_ue.GameState.md#isactortickenabled)

#### Defined in

[ue/ue.d.ts:13260](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13260)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[IsChildActor](ue_ue.GameState.md#ischildactor)

#### Defined in

[ue/ue.d.ts:13261](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13261)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[IsEditable](ue_ue.GameState.md#iseditable)

#### Defined in

[ue/ue.d.ts:13262](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13262)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[IsHiddenEd](ue_ue.GameState.md#ishiddened)

#### Defined in

[ue/ue.d.ts:13263](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13263)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[IsHiddenEdAtStartup](ue_ue.GameState.md#ishiddenedatstartup)

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

[GameState](ue_ue.GameState.md).[IsOverlappingActor](ue_ue.GameState.md#isoverlappingactor)

#### Defined in

[ue/ue.d.ts:13265](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13265)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameState](ue_ue.GameState.md).[IsSelectable](ue_ue.GameState.md#isselectable)

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

[GameState](ue_ue.GameState.md).[IsTemporarilyHiddenInEditor](ue_ue.GameState.md#istemporarilyhiddenineditor)

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

[GameState](ue_ue.GameState.md).[K2_AddActorLocalOffset](ue_ue.GameState.md#k2_addactorlocaloffset)

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

[GameState](ue_ue.GameState.md).[K2_AddActorLocalRotation](ue_ue.GameState.md#k2_addactorlocalrotation)

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

[GameState](ue_ue.GameState.md).[K2_AddActorLocalTransform](ue_ue.GameState.md#k2_addactorlocaltransform)

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

[GameState](ue_ue.GameState.md).[K2_AddActorWorldOffset](ue_ue.GameState.md#k2_addactorworldoffset)

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

[GameState](ue_ue.GameState.md).[K2_AddActorWorldRotation](ue_ue.GameState.md#k2_addactorworldrotation)

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

[GameState](ue_ue.GameState.md).[K2_AddActorWorldTransform](ue_ue.GameState.md#k2_addactorworldtransform)

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

[GameState](ue_ue.GameState.md).[K2_AttachRootComponentTo](ue_ue.GameState.md#k2_attachrootcomponentto)

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

[GameState](ue_ue.GameState.md).[K2_AttachRootComponentToActor](ue_ue.GameState.md#k2_attachrootcomponenttoactor)

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

[GameState](ue_ue.GameState.md).[K2_AttachToActor](ue_ue.GameState.md#k2_attachtoactor)

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

[GameState](ue_ue.GameState.md).[K2_AttachToComponent](ue_ue.GameState.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:13277](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13277)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[K2_DestroyActor](ue_ue.GameState.md#k2_destroyactor)

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

[GameState](ue_ue.GameState.md).[K2_DestroyComponent](ue_ue.GameState.md#k2_destroycomponent)

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

[GameState](ue_ue.GameState.md).[K2_DetachFromActor](ue_ue.GameState.md#k2_detachfromactor)

#### Defined in

[ue/ue.d.ts:13280](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13280)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[K2_GetActorLocation](ue_ue.GameState.md#k2_getactorlocation)

#### Defined in

[ue/ue.d.ts:13281](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13281)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[K2_GetActorRotation](ue_ue.GameState.md#k2_getactorrotation)

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

[GameState](ue_ue.GameState.md).[K2_GetComponentsByClass](ue_ue.GameState.md#k2_getcomponentsbyclass)

#### Defined in

[ue/ue.d.ts:13283](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13283)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[GameState](ue_ue.GameState.md).[K2_GetRootComponent](ue_ue.GameState.md#k2_getrootcomponent)

#### Defined in

[ue/ue.d.ts:13284](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13284)

___

### K2\_OnARWorldMapIsReady

▸ **K2_OnARWorldMapIsReady**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21319)

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

[GameState](ue_ue.GameState.md).[K2_OnEndViewTarget](ue_ue.GameState.md#k2_onendviewtarget)

#### Defined in

[ue/ue.d.ts:13286](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13286)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[K2_OnReset](ue_ue.GameState.md#k2_onreset)

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

[GameState](ue_ue.GameState.md).[K2_SetActorLocation](ue_ue.GameState.md#k2_setactorlocation)

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

[GameState](ue_ue.GameState.md).[K2_SetActorLocationAndRotation](ue_ue.GameState.md#k2_setactorlocationandrotation)

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

[GameState](ue_ue.GameState.md).[K2_SetActorRelativeLocation](ue_ue.GameState.md#k2_setactorrelativelocation)

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

[GameState](ue_ue.GameState.md).[K2_SetActorRelativeRotation](ue_ue.GameState.md#k2_setactorrelativerotation)

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

[GameState](ue_ue.GameState.md).[K2_SetActorRelativeTransform](ue_ue.GameState.md#k2_setactorrelativetransform)

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

[GameState](ue_ue.GameState.md).[K2_SetActorRotation](ue_ue.GameState.md#k2_setactorrotation)

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

[GameState](ue_ue.GameState.md).[K2_SetActorTransform](ue_ue.GameState.md#k2_setactortransform)

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

[GameState](ue_ue.GameState.md).[K2_TeleportTo](ue_ue.GameState.md#k2_teleportto)

#### Defined in

[ue/ue.d.ts:13295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13295)

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

[GameState](ue_ue.GameState.md).[MakeNoise](ue_ue.GameState.md#makenoise)

#### Defined in

[ue/ue.d.ts:13297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13297)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_AttachmentReplication](ue_ue.GameState.md#onrep_attachmentreplication)

#### Defined in

[ue/ue.d.ts:13298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13298)

___

### OnRep\_ElapsedTime

▸ **OnRep_ElapsedTime**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_ElapsedTime](ue_ue.GameState.md#onrep_elapsedtime)

#### Defined in

[ue/ue.d.ts:21302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21302)

___

### OnRep\_GameModeClass

▸ **OnRep_GameModeClass**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_GameModeClass](ue_ue.GameState.md#onrep_gamemodeclass)

#### Defined in

[ue/ue.d.ts:9939](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9939)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_Instigator](ue_ue.GameState.md#onrep_instigator)

#### Defined in

[ue/ue.d.ts:13299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13299)

___

### OnRep\_MatchState

▸ **OnRep_MatchState**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_MatchState](ue_ue.GameState.md#onrep_matchstate)

#### Defined in

[ue/ue.d.ts:21303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21303)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_Owner](ue_ue.GameState.md#onrep_owner)

#### Defined in

[ue/ue.d.ts:13300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13300)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_ReplicateMovement](ue_ue.GameState.md#onrep_replicatemovement)

#### Defined in

[ue/ue.d.ts:13302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13302)

___

### OnRep\_ReplicatedHasBegunPlay

▸ **OnRep_ReplicatedHasBegunPlay**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_ReplicatedHasBegunPlay](ue_ue.GameState.md#onrep_replicatedhasbegunplay)

#### Defined in

[ue/ue.d.ts:9940](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9940)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_ReplicatedMovement](ue_ue.GameState.md#onrep_replicatedmovement)

#### Defined in

[ue/ue.d.ts:13301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13301)

___

### OnRep\_ReplicatedWorldTimeSeconds

▸ **OnRep_ReplicatedWorldTimeSeconds**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_ReplicatedWorldTimeSeconds](ue_ue.GameState.md#onrep_replicatedworldtimeseconds)

#### Defined in

[ue/ue.d.ts:9941](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9941)

___

### OnRep\_SpectatorClass

▸ **OnRep_SpectatorClass**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[OnRep_SpectatorClass](ue_ue.GameState.md#onrep_spectatorclass)

#### Defined in

[ue/ue.d.ts:9942](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9942)

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

#### Defined in

[ue/ue.d.ts:13303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13303)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[ReceiveActorBeginCursorOver](ue_ue.GameState.md#receiveactorbegincursorover)

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

[GameState](ue_ue.GameState.md).[ReceiveActorBeginOverlap](ue_ue.GameState.md#receiveactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13305)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[ReceiveActorEndCursorOver](ue_ue.GameState.md#receiveactorendcursorover)

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

[GameState](ue_ue.GameState.md).[ReceiveActorEndOverlap](ue_ue.GameState.md#receiveactorendoverlap)

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

[GameState](ue_ue.GameState.md).[ReceiveActorOnClicked](ue_ue.GameState.md#receiveactoronclicked)

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

[GameState](ue_ue.GameState.md).[ReceiveActorOnInputTouchBegin](ue_ue.GameState.md#receiveactoroninputtouchbegin)

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

[GameState](ue_ue.GameState.md).[ReceiveActorOnInputTouchEnd](ue_ue.GameState.md#receiveactoroninputtouchend)

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

[GameState](ue_ue.GameState.md).[ReceiveActorOnInputTouchEnter](ue_ue.GameState.md#receiveactoroninputtouchenter)

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

[GameState](ue_ue.GameState.md).[ReceiveActorOnInputTouchLeave](ue_ue.GameState.md#receiveactoroninputtouchleave)

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

[GameState](ue_ue.GameState.md).[ReceiveActorOnReleased](ue_ue.GameState.md#receiveactoronreleased)

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

[GameState](ue_ue.GameState.md).[ReceiveAnyDamage](ue_ue.GameState.md#receiveanydamage)

#### Defined in

[ue/ue.d.ts:13314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13314)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[ReceiveBeginPlay](ue_ue.GameState.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:13315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13315)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[ReceiveDestroyed](ue_ue.GameState.md#receivedestroyed)

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

[GameState](ue_ue.GameState.md).[ReceiveEndPlay](ue_ue.GameState.md#receiveendplay)

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

[GameState](ue_ue.GameState.md).[ReceiveHit](ue_ue.GameState.md#receivehit)

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

[GameState](ue_ue.GameState.md).[ReceivePointDamage](ue_ue.GameState.md#receivepointdamage)

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

[GameState](ue_ue.GameState.md).[ReceiveRadialDamage](ue_ue.GameState.md#receiveradialdamage)

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

[GameState](ue_ue.GameState.md).[ReceiveTick](ue_ue.GameState.md#receivetick)

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

[GameState](ue_ue.GameState.md).[RemoveTickPrerequisiteActor](ue_ue.GameState.md#removetickprerequisiteactor)

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

[GameState](ue_ue.GameState.md).[RemoveTickPrerequisiteComponent](ue_ue.GameState.md#removetickprerequisitecomponent)

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

[GameState](ue_ue.GameState.md).[SetActorEnableCollision](ue_ue.GameState.md#setactorenablecollision)

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

[GameState](ue_ue.GameState.md).[SetActorHiddenInGame](ue_ue.GameState.md#setactorhiddeningame)

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

[GameState](ue_ue.GameState.md).[SetActorLabel](ue_ue.GameState.md#setactorlabel)

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

[GameState](ue_ue.GameState.md).[SetActorRelativeScale3D](ue_ue.GameState.md#setactorrelativescale3d)

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

[GameState](ue_ue.GameState.md).[SetActorScale3D](ue_ue.GameState.md#setactorscale3d)

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

[GameState](ue_ue.GameState.md).[SetActorTickEnabled](ue_ue.GameState.md#setactortickenabled)

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

[GameState](ue_ue.GameState.md).[SetActorTickInterval](ue_ue.GameState.md#setactortickinterval)

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

[GameState](ue_ue.GameState.md).[SetFolderPath](ue_ue.GameState.md#setfolderpath)

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

[GameState](ue_ue.GameState.md).[SetIsTemporarilyHiddenInEditor](ue_ue.GameState.md#setistemporarilyhiddenineditor)

#### Defined in

[ue/ue.d.ts:13332](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13332)

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

[GameState](ue_ue.GameState.md).[SetNetDormancy](ue_ue.GameState.md#setnetdormancy)

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

[GameState](ue_ue.GameState.md).[SetOwner](ue_ue.GameState.md#setowner)

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

[GameState](ue_ue.GameState.md).[SetReplicateMovement](ue_ue.GameState.md#setreplicatemovement)

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

[GameState](ue_ue.GameState.md).[SetReplicates](ue_ue.GameState.md#setreplicates)

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

[GameState](ue_ue.GameState.md).[SetTickGroup](ue_ue.GameState.md#settickgroup)

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

[GameState](ue_ue.GameState.md).[SetTickableWhenPaused](ue_ue.GameState.md#settickablewhenpaused)

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

[GameState](ue_ue.GameState.md).[SnapRootComponentTo](ue_ue.GameState.md#snaprootcomponentto)

#### Defined in

[ue/ue.d.ts:13340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13340)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[TearOff](ue_ue.GameState.md#tearoff)

#### Defined in

[ue/ue.d.ts:13341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13341)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[GameState](ue_ue.GameState.md).[UserConstructionScript](ue_ue.GameState.md#userconstructionscript)

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

[GameState](ue_ue.GameState.md).[WasRecentlyRendered](ue_ue.GameState.md#wasrecentlyrendered)

#### Defined in

[ue/ue.d.ts:13343](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13343)

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

#### Defined in

[ue/ue.d.ts:21321](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21321)

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

#### Defined in

[ue/ue.d.ts:21322](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21322)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameState](ue_ue.GameState.md).[StaticClass](ue_ue.GameState.md#staticclass)

#### Defined in

[ue/ue.d.ts:21320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21320)
