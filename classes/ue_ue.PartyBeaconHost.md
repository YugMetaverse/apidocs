[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PartyBeaconHost

# Class: PartyBeaconHost

[ue/ue](../modules/ue_ue.md).PartyBeaconHost

## Hierarchy

- [`OnlineBeaconHostObject`](ue_ue.OnlineBeaconHostObject.md)

  ↳ **`PartyBeaconHost`**

## Table of contents

### Constructors

- [constructor](ue_ue.PartyBeaconHost.md#constructor)

### Properties

- [ActorLabel](ue_ue.PartyBeaconHost.md#actorlabel)
- [AttachmentReplication](ue_ue.PartyBeaconHost.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.PartyBeaconHost.md#autoreceiveinput)
- [BeaconTypeName](ue_ue.PartyBeaconHost.md#beacontypename)
- [BlueprintCreatedComponents](ue_ue.PartyBeaconHost.md#blueprintcreatedcomponents)
- [Children](ue_ue.PartyBeaconHost.md#children)
- [ClientActors](ue_ue.PartyBeaconHost.md#clientactors)
- [ClientBeaconActorClass](ue_ue.PartyBeaconHost.md#clientbeaconactorclass)
- [ControllingMatineeActors](ue_ue.PartyBeaconHost.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.PartyBeaconHost.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.PartyBeaconHost.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.PartyBeaconHost.md#folderpath)
- [GroupActor](ue_ue.PartyBeaconHost.md#groupactor)
- [HiddenEditorViews](ue_ue.PartyBeaconHost.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.PartyBeaconHost.md#initiallifespan)
- [InputComponent](ue_ue.PartyBeaconHost.md#inputcomponent)
- [InputPriority](ue_ue.PartyBeaconHost.md#inputpriority)
- [InstanceComponents](ue_ue.PartyBeaconHost.md#instancecomponents)
- [Instigator](ue_ue.PartyBeaconHost.md#instigator)
- [Layers](ue_ue.PartyBeaconHost.md#layers)
- [MinNetUpdateFrequency](ue_ue.PartyBeaconHost.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.PartyBeaconHost.md#netculldistancesquared)
- [NetDormancy](ue_ue.PartyBeaconHost.md#netdormancy)
- [NetDriverName](ue_ue.PartyBeaconHost.md#netdrivername)
- [NetPriority](ue_ue.PartyBeaconHost.md#netpriority)
- [NetTag](ue_ue.PartyBeaconHost.md#nettag)
- [NetUpdateFrequency](ue_ue.PartyBeaconHost.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.PartyBeaconHost.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.PartyBeaconHost.md#onactorendoverlap)
- [OnActorHit](ue_ue.PartyBeaconHost.md#onactorhit)
- [OnBeginCursorOver](ue_ue.PartyBeaconHost.md#onbegincursorover)
- [OnClicked](ue_ue.PartyBeaconHost.md#onclicked)
- [OnDestroyed](ue_ue.PartyBeaconHost.md#ondestroyed)
- [OnEndCursorOver](ue_ue.PartyBeaconHost.md#onendcursorover)
- [OnEndPlay](ue_ue.PartyBeaconHost.md#onendplay)
- [OnInputTouchBegin](ue_ue.PartyBeaconHost.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.PartyBeaconHost.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.PartyBeaconHost.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.PartyBeaconHost.md#oninputtouchleave)
- [OnReleased](ue_ue.PartyBeaconHost.md#onreleased)
- [OnTakeAnyDamage](ue_ue.PartyBeaconHost.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.PartyBeaconHost.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.PartyBeaconHost.md#ontakeradialdamage)
- [Owner](ue_ue.PartyBeaconHost.md#owner)
- [ParentComponent](ue_ue.PartyBeaconHost.md#parentcomponent)
- [ParentComponentActor](ue_ue.PartyBeaconHost.md#parentcomponentactor)
- [PivotOffset](ue_ue.PartyBeaconHost.md#pivotoffset)
- [PrimaryActorTick](ue_ue.PartyBeaconHost.md#primaryactortick)
- [RemoteRole](ue_ue.PartyBeaconHost.md#remoterole)
- [ReplicatedMovement](ue_ue.PartyBeaconHost.md#replicatedmovement)
- [Role](ue_ue.PartyBeaconHost.md#role)
- [RootComponent](ue_ue.PartyBeaconHost.md#rootcomponent)
- [SessionTimeoutSecs](ue_ue.PartyBeaconHost.md#sessiontimeoutsecs)
- [SpawnCollisionHandlingMethod](ue_ue.PartyBeaconHost.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.PartyBeaconHost.md#spritescale)
- [State](ue_ue.PartyBeaconHost.md#state)
- [Tags](ue_ue.PartyBeaconHost.md#tags)
- [TravelSessionTimeoutSecs](ue_ue.PartyBeaconHost.md#travelsessiontimeoutsecs)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.PartyBeaconHost.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.PartyBeaconHost.md#__tid_actor__)
- [\_\_tid\_Object\_\_](ue_ue.PartyBeaconHost.md#__tid_object__)
- [\_\_tid\_OnlineBeaconHostObject\_\_](ue_ue.PartyBeaconHost.md#__tid_onlinebeaconhostobject__)
- [\_\_tid\_PartyBeaconHost\_\_](ue_ue.PartyBeaconHost.md#__tid_partybeaconhost__)
- [bActorEnableCollision](ue_ue.PartyBeaconHost.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.PartyBeaconHost.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.PartyBeaconHost.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.PartyBeaconHost.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.PartyBeaconHost.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.PartyBeaconHost.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.PartyBeaconHost.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.PartyBeaconHost.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.PartyBeaconHost.md#bblockinput)
- [bCanBeDamaged](ue_ue.PartyBeaconHost.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.PartyBeaconHost.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.PartyBeaconHost.md#bcollidewhenplacing)
- [bEditable](ue_ue.PartyBeaconHost.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.PartyBeaconHost.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.PartyBeaconHost.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.PartyBeaconHost.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.PartyBeaconHost.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.PartyBeaconHost.md#bhidden)
- [bHiddenEd](ue_ue.PartyBeaconHost.md#bhiddened)
- [bHiddenEdLayer](ue_ue.PartyBeaconHost.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.PartyBeaconHost.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.PartyBeaconHost.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.PartyBeaconHost.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.PartyBeaconHost.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.PartyBeaconHost.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.PartyBeaconHost.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.PartyBeaconHost.md#blocklocation)
- [bLogoutOnSessionTimeout](ue_ue.PartyBeaconHost.md#blogoutonsessiontimeout)
- [bNetLoadOnClient](ue_ue.PartyBeaconHost.md#bnetloadonclient)
- [bNetStartup](ue_ue.PartyBeaconHost.md#bnetstartup)
- [bNetTemporary](ue_ue.PartyBeaconHost.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.PartyBeaconHost.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.PartyBeaconHost.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.PartyBeaconHost.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.PartyBeaconHost.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.PartyBeaconHost.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.PartyBeaconHost.md#breplayrewindable)
- [bReplicateMovement](ue_ue.PartyBeaconHost.md#breplicatemovement)
- [bReplicates](ue_ue.PartyBeaconHost.md#breplicates)
- [bTearOff](ue_ue.PartyBeaconHost.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.PartyBeaconHost.md#actorhastag)
- [AddComponent](ue_ue.PartyBeaconHost.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.PartyBeaconHost.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PartyBeaconHost.md#addtickprerequisitecomponent)
- [CreateDefaultSubobject](ue_ue.PartyBeaconHost.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.PartyBeaconHost.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.PartyBeaconHost.md#disableinput)
- [EnableInput](ue_ue.PartyBeaconHost.md#enableinput)
- [ExecuteUbergraph](ue_ue.PartyBeaconHost.md#executeubergraph)
- [FlushNetDormancy](ue_ue.PartyBeaconHost.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.PartyBeaconHost.md#forcenetupdate)
- [GetActorBounds](ue_ue.PartyBeaconHost.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.PartyBeaconHost.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.PartyBeaconHost.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.PartyBeaconHost.md#getactorforwardvector)
- [GetActorLabel](ue_ue.PartyBeaconHost.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.PartyBeaconHost.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.PartyBeaconHost.md#getactorrightvector)
- [GetActorScale3D](ue_ue.PartyBeaconHost.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.PartyBeaconHost.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.PartyBeaconHost.md#getactortimedilation)
- [GetActorUpVector](ue_ue.PartyBeaconHost.md#getactorupvector)
- [GetAllChildActors](ue_ue.PartyBeaconHost.md#getallchildactors)
- [GetAttachParentActor](ue_ue.PartyBeaconHost.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.PartyBeaconHost.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.PartyBeaconHost.md#getattachedactors)
- [GetClass](ue_ue.PartyBeaconHost.md#getclass)
- [GetComponentByClass](ue_ue.PartyBeaconHost.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.PartyBeaconHost.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.PartyBeaconHost.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.PartyBeaconHost.md#getdistanceto)
- [GetDotProductTo](ue_ue.PartyBeaconHost.md#getdotproductto)
- [GetFolderPath](ue_ue.PartyBeaconHost.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.PartyBeaconHost.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.PartyBeaconHost.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.PartyBeaconHost.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.PartyBeaconHost.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.PartyBeaconHost.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.PartyBeaconHost.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.PartyBeaconHost.md#getinstigator)
- [GetInstigatorController](ue_ue.PartyBeaconHost.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.PartyBeaconHost.md#getlifespan)
- [GetLocalRole](ue_ue.PartyBeaconHost.md#getlocalrole)
- [GetName](ue_ue.PartyBeaconHost.md#getname)
- [GetOuter](ue_ue.PartyBeaconHost.md#getouter)
- [GetOverlappingActors](ue_ue.PartyBeaconHost.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.PartyBeaconHost.md#getoverlappingcomponents)
- [GetOwner](ue_ue.PartyBeaconHost.md#getowner)
- [GetParentActor](ue_ue.PartyBeaconHost.md#getparentactor)
- [GetParentComponent](ue_ue.PartyBeaconHost.md#getparentcomponent)
- [GetRemoteRole](ue_ue.PartyBeaconHost.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.PartyBeaconHost.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.PartyBeaconHost.md#gettickablewhenpaused)
- [GetTransform](ue_ue.PartyBeaconHost.md#gettransform)
- [GetVelocity](ue_ue.PartyBeaconHost.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.PartyBeaconHost.md#getverticaldistanceto)
- [GetWorld](ue_ue.PartyBeaconHost.md#getworld)
- [HasAuthority](ue_ue.PartyBeaconHost.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.PartyBeaconHost.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.PartyBeaconHost.md#isactortickenabled)
- [IsChildActor](ue_ue.PartyBeaconHost.md#ischildactor)
- [IsEditable](ue_ue.PartyBeaconHost.md#iseditable)
- [IsHiddenEd](ue_ue.PartyBeaconHost.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.PartyBeaconHost.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.PartyBeaconHost.md#isoverlappingactor)
- [IsSelectable](ue_ue.PartyBeaconHost.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.PartyBeaconHost.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.PartyBeaconHost.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.PartyBeaconHost.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.PartyBeaconHost.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.PartyBeaconHost.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.PartyBeaconHost.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.PartyBeaconHost.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.PartyBeaconHost.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.PartyBeaconHost.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.PartyBeaconHost.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.PartyBeaconHost.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.PartyBeaconHost.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.PartyBeaconHost.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.PartyBeaconHost.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.PartyBeaconHost.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.PartyBeaconHost.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.PartyBeaconHost.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.PartyBeaconHost.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.PartyBeaconHost.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.PartyBeaconHost.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.PartyBeaconHost.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.PartyBeaconHost.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.PartyBeaconHost.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.PartyBeaconHost.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.PartyBeaconHost.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.PartyBeaconHost.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.PartyBeaconHost.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.PartyBeaconHost.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.PartyBeaconHost.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.PartyBeaconHost.md#makemidformaterial)
- [MakeNoise](ue_ue.PartyBeaconHost.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.PartyBeaconHost.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.PartyBeaconHost.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.PartyBeaconHost.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.PartyBeaconHost.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.PartyBeaconHost.md#onrep_replicatedmovement)
- [PrestreamTextures](ue_ue.PartyBeaconHost.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.PartyBeaconHost.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.PartyBeaconHost.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.PartyBeaconHost.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.PartyBeaconHost.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.PartyBeaconHost.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.PartyBeaconHost.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.PartyBeaconHost.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.PartyBeaconHost.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.PartyBeaconHost.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.PartyBeaconHost.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.PartyBeaconHost.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.PartyBeaconHost.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.PartyBeaconHost.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.PartyBeaconHost.md#receiveendplay)
- [ReceiveHit](ue_ue.PartyBeaconHost.md#receivehit)
- [ReceivePointDamage](ue_ue.PartyBeaconHost.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.PartyBeaconHost.md#receiveradialdamage)
- [ReceiveTick](ue_ue.PartyBeaconHost.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.PartyBeaconHost.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PartyBeaconHost.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.PartyBeaconHost.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.PartyBeaconHost.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.PartyBeaconHost.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.PartyBeaconHost.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.PartyBeaconHost.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.PartyBeaconHost.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.PartyBeaconHost.md#setactortickinterval)
- [SetFolderPath](ue_ue.PartyBeaconHost.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.PartyBeaconHost.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.PartyBeaconHost.md#setlifespan)
- [SetNetDormancy](ue_ue.PartyBeaconHost.md#setnetdormancy)
- [SetOwner](ue_ue.PartyBeaconHost.md#setowner)
- [SetReplicateMovement](ue_ue.PartyBeaconHost.md#setreplicatemovement)
- [SetReplicates](ue_ue.PartyBeaconHost.md#setreplicates)
- [SetTickGroup](ue_ue.PartyBeaconHost.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PartyBeaconHost.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.PartyBeaconHost.md#snaprootcomponentto)
- [TearOff](ue_ue.PartyBeaconHost.md#tearoff)
- [UserConstructionScript](ue_ue.PartyBeaconHost.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.PartyBeaconHost.md#wasrecentlyrendered)
- [Find](ue_ue.PartyBeaconHost.md#find)
- [Load](ue_ue.PartyBeaconHost.md#load)
- [StaticClass](ue_ue.PartyBeaconHost.md#staticclass)

## Constructors

### constructor

• **new PartyBeaconHost**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[constructor](ue_ue.OnlineBeaconHostObject.md#constructor)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ActorLabel](ue_ue.OnlineBeaconHostObject.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[AttachmentReplication](ue_ue.OnlineBeaconHostObject.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[AutoReceiveInput](ue_ue.OnlineBeaconHostObject.md#autoreceiveinput)

___

### BeaconTypeName

• **BeaconTypeName**: `string`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[BeaconTypeName](ue_ue.OnlineBeaconHostObject.md#beacontypename)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[BlueprintCreatedComponents](ue_ue.OnlineBeaconHostObject.md#blueprintcreatedcomponents)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[Children](ue_ue.OnlineBeaconHostObject.md#children)

___

### ClientActors

• **ClientActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`OnlineBeaconClient`](ue_ue.OnlineBeaconClient.md)\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ClientActors](ue_ue.OnlineBeaconHostObject.md#clientactors)

___

### ClientBeaconActorClass

• **ClientBeaconActorClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ClientBeaconActorClass](ue_ue.OnlineBeaconHostObject.md#clientbeaconactorclass)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ControllingMatineeActors](ue_ue.OnlineBeaconHostObject.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[CustomTimeDilation](ue_ue.OnlineBeaconHostObject.md#customtimedilation)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.OnlineBeaconHostObject.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[FolderPath](ue_ue.OnlineBeaconHostObject.md#folderpath)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GroupActor](ue_ue.OnlineBeaconHostObject.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[HiddenEditorViews](ue_ue.OnlineBeaconHostObject.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[InitialLifeSpan](ue_ue.OnlineBeaconHostObject.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[InputComponent](ue_ue.OnlineBeaconHostObject.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[InputPriority](ue_ue.OnlineBeaconHostObject.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[InstanceComponents](ue_ue.OnlineBeaconHostObject.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[Instigator](ue_ue.OnlineBeaconHostObject.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[Layers](ue_ue.OnlineBeaconHostObject.md#layers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[MinNetUpdateFrequency](ue_ue.OnlineBeaconHostObject.md#minnetupdatefrequency)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[NetCullDistanceSquared](ue_ue.OnlineBeaconHostObject.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[NetDormancy](ue_ue.OnlineBeaconHostObject.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[NetDriverName](ue_ue.OnlineBeaconHostObject.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[NetPriority](ue_ue.OnlineBeaconHostObject.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[NetTag](ue_ue.OnlineBeaconHostObject.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[NetUpdateFrequency](ue_ue.OnlineBeaconHostObject.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnActorBeginOverlap](ue_ue.OnlineBeaconHostObject.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnActorEndOverlap](ue_ue.OnlineBeaconHostObject.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnActorHit](ue_ue.OnlineBeaconHostObject.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnBeginCursorOver](ue_ue.OnlineBeaconHostObject.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnClicked](ue_ue.OnlineBeaconHostObject.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnDestroyed](ue_ue.OnlineBeaconHostObject.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnEndCursorOver](ue_ue.OnlineBeaconHostObject.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnEndPlay](ue_ue.OnlineBeaconHostObject.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnInputTouchBegin](ue_ue.OnlineBeaconHostObject.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnInputTouchEnd](ue_ue.OnlineBeaconHostObject.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnInputTouchEnter](ue_ue.OnlineBeaconHostObject.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnInputTouchLeave](ue_ue.OnlineBeaconHostObject.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnReleased](ue_ue.OnlineBeaconHostObject.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnTakeAnyDamage](ue_ue.OnlineBeaconHostObject.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnTakePointDamage](ue_ue.OnlineBeaconHostObject.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnTakeRadialDamage](ue_ue.OnlineBeaconHostObject.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[Owner](ue_ue.OnlineBeaconHostObject.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ParentComponent](ue_ue.OnlineBeaconHostObject.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ParentComponentActor](ue_ue.OnlineBeaconHostObject.md#parentcomponentactor)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[PivotOffset](ue_ue.OnlineBeaconHostObject.md#pivotoffset)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[PrimaryActorTick](ue_ue.OnlineBeaconHostObject.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[RemoteRole](ue_ue.OnlineBeaconHostObject.md#remoterole)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReplicatedMovement](ue_ue.OnlineBeaconHostObject.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[Role](ue_ue.OnlineBeaconHostObject.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[RootComponent](ue_ue.OnlineBeaconHostObject.md#rootcomponent)

___

### SessionTimeoutSecs

• **SessionTimeoutSecs**: `number`

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SpawnCollisionHandlingMethod](ue_ue.OnlineBeaconHostObject.md#spawncollisionhandlingmethod)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SpriteScale](ue_ue.OnlineBeaconHostObject.md#spritescale)

___

### State

• **State**: [`PartyBeaconState`](ue_ue.PartyBeaconState.md)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[Tags](ue_ue.OnlineBeaconHostObject.md#tags)

___

### TravelSessionTimeoutSecs

• **TravelSessionTimeoutSecs**: `number`

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.OnlineBeaconHostObject.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[__tid_Actor__](ue_ue.OnlineBeaconHostObject.md#__tid_actor__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[__tid_Object__](ue_ue.OnlineBeaconHostObject.md#__tid_object__)

___

### \_\_tid\_OnlineBeaconHostObject\_\_

• **\_\_tid\_OnlineBeaconHostObject\_\_**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[__tid_OnlineBeaconHostObject__](ue_ue.OnlineBeaconHostObject.md#__tid_onlinebeaconhostobject__)

___

### \_\_tid\_PartyBeaconHost\_\_

• **\_\_tid\_PartyBeaconHost\_\_**: `boolean`

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bActorEnableCollision](ue_ue.OnlineBeaconHostObject.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bActorIsBeingDestroyed](ue_ue.OnlineBeaconHostObject.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bActorLabelEditable](ue_ue.OnlineBeaconHostObject.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bActorSeamlessTraveled](ue_ue.OnlineBeaconHostObject.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.OnlineBeaconHostObject.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bAllowTickBeforeBeginPlay](ue_ue.OnlineBeaconHostObject.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bAlwaysRelevant](ue_ue.OnlineBeaconHostObject.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bAutoDestroyWhenFinished](ue_ue.OnlineBeaconHostObject.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bBlockInput](ue_ue.OnlineBeaconHostObject.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bCanBeDamaged](ue_ue.OnlineBeaconHostObject.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bCanBeInCluster](ue_ue.OnlineBeaconHostObject.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bCollideWhenPlacing](ue_ue.OnlineBeaconHostObject.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bEditable](ue_ue.OnlineBeaconHostObject.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bEnableAutoLODGeneration](ue_ue.OnlineBeaconHostObject.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bExchangedRoles](ue_ue.OnlineBeaconHostObject.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bFindCameraComponentWhenViewTarget](ue_ue.OnlineBeaconHostObject.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.OnlineBeaconHostObject.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bHidden](ue_ue.OnlineBeaconHostObject.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bHiddenEd](ue_ue.OnlineBeaconHostObject.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bHiddenEdLayer](ue_ue.OnlineBeaconHostObject.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bHiddenEdLevel](ue_ue.OnlineBeaconHostObject.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bHiddenEdTemporary](ue_ue.OnlineBeaconHostObject.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bIgnoresOriginShifting](ue_ue.OnlineBeaconHostObject.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bIsEditorOnlyActor](ue_ue.OnlineBeaconHostObject.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bIsEditorPreviewActor](ue_ue.OnlineBeaconHostObject.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bListedInSceneOutliner](ue_ue.OnlineBeaconHostObject.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bLockLocation](ue_ue.OnlineBeaconHostObject.md#blocklocation)

___

### bLogoutOnSessionTimeout

• **bLogoutOnSessionTimeout**: `boolean`

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bNetLoadOnClient](ue_ue.OnlineBeaconHostObject.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bNetStartup](ue_ue.OnlineBeaconHostObject.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bNetTemporary](ue_ue.OnlineBeaconHostObject.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bNetUseOwnerRelevancy](ue_ue.OnlineBeaconHostObject.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bOnlyRelevantToOwner](ue_ue.OnlineBeaconHostObject.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bOptimizeBPComponentData](ue_ue.OnlineBeaconHostObject.md#boptimizebpcomponentdata)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bRelevantForLevelBounds](ue_ue.OnlineBeaconHostObject.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bRelevantForNetworkReplays](ue_ue.OnlineBeaconHostObject.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bReplayRewindable](ue_ue.OnlineBeaconHostObject.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bReplicateMovement](ue_ue.OnlineBeaconHostObject.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bReplicates](ue_ue.OnlineBeaconHostObject.md#breplicates)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[bTearOff](ue_ue.OnlineBeaconHostObject.md#btearoff)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ActorHasTag](ue_ue.OnlineBeaconHostObject.md#actorhastag)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[AddComponent](ue_ue.OnlineBeaconHostObject.md#addcomponent)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[AddTickPrerequisiteActor](ue_ue.OnlineBeaconHostObject.md#addtickprerequisiteactor)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[AddTickPrerequisiteComponent](ue_ue.OnlineBeaconHostObject.md#addtickprerequisitecomponent)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[CreateDefaultSubobject](ue_ue.OnlineBeaconHostObject.md#createdefaultsubobject)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[DetachRootComponentFromParent](ue_ue.OnlineBeaconHostObject.md#detachrootcomponentfromparent)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[DisableInput](ue_ue.OnlineBeaconHostObject.md#disableinput)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[EnableInput](ue_ue.OnlineBeaconHostObject.md#enableinput)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ExecuteUbergraph](ue_ue.OnlineBeaconHostObject.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[FlushNetDormancy](ue_ue.OnlineBeaconHostObject.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ForceNetUpdate](ue_ue.OnlineBeaconHostObject.md#forcenetupdate)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetActorBounds](ue_ue.OnlineBeaconHostObject.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetActorEnableCollision](ue_ue.OnlineBeaconHostObject.md#getactorenablecollision)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetActorEyesViewPoint](ue_ue.OnlineBeaconHostObject.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetActorForwardVector](ue_ue.OnlineBeaconHostObject.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetActorLabel](ue_ue.OnlineBeaconHostObject.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetActorRelativeScale3D](ue_ue.OnlineBeaconHostObject.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetActorRightVector](ue_ue.OnlineBeaconHostObject.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetActorScale3D](ue_ue.OnlineBeaconHostObject.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetActorTickInterval](ue_ue.OnlineBeaconHostObject.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetActorTimeDilation](ue_ue.OnlineBeaconHostObject.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetActorUpVector](ue_ue.OnlineBeaconHostObject.md#getactorupvector)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetAllChildActors](ue_ue.OnlineBeaconHostObject.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetAttachParentActor](ue_ue.OnlineBeaconHostObject.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetAttachParentSocketName](ue_ue.OnlineBeaconHostObject.md#getattachparentsocketname)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetAttachedActors](ue_ue.OnlineBeaconHostObject.md#getattachedactors)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetClass](ue_ue.OnlineBeaconHostObject.md#getclass)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetComponentByClass](ue_ue.OnlineBeaconHostObject.md#getcomponentbyclass)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetComponentsByInterface](ue_ue.OnlineBeaconHostObject.md#getcomponentsbyinterface)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetComponentsByTag](ue_ue.OnlineBeaconHostObject.md#getcomponentsbytag)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetDistanceTo](ue_ue.OnlineBeaconHostObject.md#getdistanceto)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetDotProductTo](ue_ue.OnlineBeaconHostObject.md#getdotproductto)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetFolderPath](ue_ue.OnlineBeaconHostObject.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetGameTimeSinceCreation](ue_ue.OnlineBeaconHostObject.md#getgametimesincecreation)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetHorizontalDistanceTo](ue_ue.OnlineBeaconHostObject.md#gethorizontaldistanceto)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetHorizontalDotProductTo](ue_ue.OnlineBeaconHostObject.md#gethorizontaldotproductto)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetInputAxisKeyValue](ue_ue.OnlineBeaconHostObject.md#getinputaxiskeyvalue)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetInputAxisValue](ue_ue.OnlineBeaconHostObject.md#getinputaxisvalue)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetInputVectorAxisValue](ue_ue.OnlineBeaconHostObject.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetInstigator](ue_ue.OnlineBeaconHostObject.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetInstigatorController](ue_ue.OnlineBeaconHostObject.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetLifeSpan](ue_ue.OnlineBeaconHostObject.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetLocalRole](ue_ue.OnlineBeaconHostObject.md#getlocalrole)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetName](ue_ue.OnlineBeaconHostObject.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetOuter](ue_ue.OnlineBeaconHostObject.md#getouter)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetOverlappingActors](ue_ue.OnlineBeaconHostObject.md#getoverlappingactors)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetOverlappingComponents](ue_ue.OnlineBeaconHostObject.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetOwner](ue_ue.OnlineBeaconHostObject.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetParentActor](ue_ue.OnlineBeaconHostObject.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetParentComponent](ue_ue.OnlineBeaconHostObject.md#getparentcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetRemoteRole](ue_ue.OnlineBeaconHostObject.md#getremoterole)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetSquaredDistanceTo](ue_ue.OnlineBeaconHostObject.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetTickableWhenPaused](ue_ue.OnlineBeaconHostObject.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetTransform](ue_ue.OnlineBeaconHostObject.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetVelocity](ue_ue.OnlineBeaconHostObject.md#getvelocity)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetVerticalDistanceTo](ue_ue.OnlineBeaconHostObject.md#getverticaldistanceto)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[GetWorld](ue_ue.OnlineBeaconHostObject.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[HasAuthority](ue_ue.OnlineBeaconHostObject.md#hasauthority)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[IsActorBeingDestroyed](ue_ue.OnlineBeaconHostObject.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[IsActorTickEnabled](ue_ue.OnlineBeaconHostObject.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[IsChildActor](ue_ue.OnlineBeaconHostObject.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[IsEditable](ue_ue.OnlineBeaconHostObject.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[IsHiddenEd](ue_ue.OnlineBeaconHostObject.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[IsHiddenEdAtStartup](ue_ue.OnlineBeaconHostObject.md#ishiddenedatstartup)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[IsOverlappingActor](ue_ue.OnlineBeaconHostObject.md#isoverlappingactor)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[IsSelectable](ue_ue.OnlineBeaconHostObject.md#isselectable)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[IsTemporarilyHiddenInEditor](ue_ue.OnlineBeaconHostObject.md#istemporarilyhiddenineditor)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_AddActorLocalOffset](ue_ue.OnlineBeaconHostObject.md#k2_addactorlocaloffset)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_AddActorLocalRotation](ue_ue.OnlineBeaconHostObject.md#k2_addactorlocalrotation)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_AddActorLocalTransform](ue_ue.OnlineBeaconHostObject.md#k2_addactorlocaltransform)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_AddActorWorldOffset](ue_ue.OnlineBeaconHostObject.md#k2_addactorworldoffset)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_AddActorWorldRotation](ue_ue.OnlineBeaconHostObject.md#k2_addactorworldrotation)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_AddActorWorldTransform](ue_ue.OnlineBeaconHostObject.md#k2_addactorworldtransform)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_AttachRootComponentTo](ue_ue.OnlineBeaconHostObject.md#k2_attachrootcomponentto)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_AttachRootComponentToActor](ue_ue.OnlineBeaconHostObject.md#k2_attachrootcomponenttoactor)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_AttachToActor](ue_ue.OnlineBeaconHostObject.md#k2_attachtoactor)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_AttachToComponent](ue_ue.OnlineBeaconHostObject.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_DestroyActor](ue_ue.OnlineBeaconHostObject.md#k2_destroyactor)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_DestroyComponent](ue_ue.OnlineBeaconHostObject.md#k2_destroycomponent)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_DetachFromActor](ue_ue.OnlineBeaconHostObject.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_GetActorLocation](ue_ue.OnlineBeaconHostObject.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_GetActorRotation](ue_ue.OnlineBeaconHostObject.md#k2_getactorrotation)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_GetComponentsByClass](ue_ue.OnlineBeaconHostObject.md#k2_getcomponentsbyclass)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_GetRootComponent](ue_ue.OnlineBeaconHostObject.md#k2_getrootcomponent)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_OnBecomeViewTarget](ue_ue.OnlineBeaconHostObject.md#k2_onbecomeviewtarget)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_OnEndViewTarget](ue_ue.OnlineBeaconHostObject.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_OnReset](ue_ue.OnlineBeaconHostObject.md#k2_onreset)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_SetActorLocation](ue_ue.OnlineBeaconHostObject.md#k2_setactorlocation)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_SetActorLocationAndRotation](ue_ue.OnlineBeaconHostObject.md#k2_setactorlocationandrotation)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_SetActorRelativeLocation](ue_ue.OnlineBeaconHostObject.md#k2_setactorrelativelocation)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_SetActorRelativeRotation](ue_ue.OnlineBeaconHostObject.md#k2_setactorrelativerotation)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_SetActorRelativeTransform](ue_ue.OnlineBeaconHostObject.md#k2_setactorrelativetransform)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_SetActorRotation](ue_ue.OnlineBeaconHostObject.md#k2_setactorrotation)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_SetActorTransform](ue_ue.OnlineBeaconHostObject.md#k2_setactortransform)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[K2_TeleportTo](ue_ue.OnlineBeaconHostObject.md#k2_teleportto)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[MakeMIDForMaterial](ue_ue.OnlineBeaconHostObject.md#makemidformaterial)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[MakeNoise](ue_ue.OnlineBeaconHostObject.md#makenoise)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnRep_AttachmentReplication](ue_ue.OnlineBeaconHostObject.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnRep_Instigator](ue_ue.OnlineBeaconHostObject.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnRep_Owner](ue_ue.OnlineBeaconHostObject.md#onrep_owner)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnRep_ReplicateMovement](ue_ue.OnlineBeaconHostObject.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[OnRep_ReplicatedMovement](ue_ue.OnlineBeaconHostObject.md#onrep_replicatedmovement)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[PrestreamTextures](ue_ue.OnlineBeaconHostObject.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceiveActorBeginCursorOver](ue_ue.OnlineBeaconHostObject.md#receiveactorbegincursorover)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceiveActorBeginOverlap](ue_ue.OnlineBeaconHostObject.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceiveActorEndCursorOver](ue_ue.OnlineBeaconHostObject.md#receiveactorendcursorover)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceiveActorEndOverlap](ue_ue.OnlineBeaconHostObject.md#receiveactorendoverlap)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceiveActorOnClicked](ue_ue.OnlineBeaconHostObject.md#receiveactoronclicked)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceiveActorOnInputTouchBegin](ue_ue.OnlineBeaconHostObject.md#receiveactoroninputtouchbegin)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceiveActorOnInputTouchEnd](ue_ue.OnlineBeaconHostObject.md#receiveactoroninputtouchend)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceiveActorOnInputTouchEnter](ue_ue.OnlineBeaconHostObject.md#receiveactoroninputtouchenter)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceiveActorOnInputTouchLeave](ue_ue.OnlineBeaconHostObject.md#receiveactoroninputtouchleave)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceiveActorOnReleased](ue_ue.OnlineBeaconHostObject.md#receiveactoronreleased)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceiveAnyDamage](ue_ue.OnlineBeaconHostObject.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceiveBeginPlay](ue_ue.OnlineBeaconHostObject.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceiveDestroyed](ue_ue.OnlineBeaconHostObject.md#receivedestroyed)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceiveEndPlay](ue_ue.OnlineBeaconHostObject.md#receiveendplay)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceiveHit](ue_ue.OnlineBeaconHostObject.md#receivehit)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceivePointDamage](ue_ue.OnlineBeaconHostObject.md#receivepointdamage)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceiveRadialDamage](ue_ue.OnlineBeaconHostObject.md#receiveradialdamage)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[ReceiveTick](ue_ue.OnlineBeaconHostObject.md#receivetick)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[RemoveTickPrerequisiteActor](ue_ue.OnlineBeaconHostObject.md#removetickprerequisiteactor)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[RemoveTickPrerequisiteComponent](ue_ue.OnlineBeaconHostObject.md#removetickprerequisitecomponent)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SetActorEnableCollision](ue_ue.OnlineBeaconHostObject.md#setactorenablecollision)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SetActorHiddenInGame](ue_ue.OnlineBeaconHostObject.md#setactorhiddeningame)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SetActorLabel](ue_ue.OnlineBeaconHostObject.md#setactorlabel)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SetActorRelativeScale3D](ue_ue.OnlineBeaconHostObject.md#setactorrelativescale3d)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SetActorScale3D](ue_ue.OnlineBeaconHostObject.md#setactorscale3d)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SetActorTickEnabled](ue_ue.OnlineBeaconHostObject.md#setactortickenabled)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SetActorTickInterval](ue_ue.OnlineBeaconHostObject.md#setactortickinterval)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SetFolderPath](ue_ue.OnlineBeaconHostObject.md#setfolderpath)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SetIsTemporarilyHiddenInEditor](ue_ue.OnlineBeaconHostObject.md#setistemporarilyhiddenineditor)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SetLifeSpan](ue_ue.OnlineBeaconHostObject.md#setlifespan)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SetNetDormancy](ue_ue.OnlineBeaconHostObject.md#setnetdormancy)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SetOwner](ue_ue.OnlineBeaconHostObject.md#setowner)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SetReplicateMovement](ue_ue.OnlineBeaconHostObject.md#setreplicatemovement)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SetReplicates](ue_ue.OnlineBeaconHostObject.md#setreplicates)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SetTickGroup](ue_ue.OnlineBeaconHostObject.md#settickgroup)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SetTickableWhenPaused](ue_ue.OnlineBeaconHostObject.md#settickablewhenpaused)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[SnapRootComponentTo](ue_ue.OnlineBeaconHostObject.md#snaprootcomponentto)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[TearOff](ue_ue.OnlineBeaconHostObject.md#tearoff)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[UserConstructionScript](ue_ue.OnlineBeaconHostObject.md#userconstructionscript)

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

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[WasRecentlyRendered](ue_ue.OnlineBeaconHostObject.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PartyBeaconHost`](ue_ue.PartyBeaconHost.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PartyBeaconHost`](ue_ue.PartyBeaconHost.md)

#### Overrides

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[Find](ue_ue.OnlineBeaconHostObject.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PartyBeaconHost`](ue_ue.PartyBeaconHost.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PartyBeaconHost`](ue_ue.PartyBeaconHost.md)

#### Overrides

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[Load](ue_ue.OnlineBeaconHostObject.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[OnlineBeaconHostObject](ue_ue.OnlineBeaconHostObject.md).[StaticClass](ue_ue.OnlineBeaconHostObject.md#staticclass)
