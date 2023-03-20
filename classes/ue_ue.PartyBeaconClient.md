[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PartyBeaconClient

# Class: PartyBeaconClient

[ue/ue](../modules/ue_ue.md).PartyBeaconClient

## Hierarchy

- [`OnlineBeaconClient`](ue_ue.OnlineBeaconClient.md)

  ↳ **`PartyBeaconClient`**

## Table of contents

### Constructors

- [constructor](ue_ue.PartyBeaconClient.md#constructor)

### Properties

- [ActorLabel](ue_ue.PartyBeaconClient.md#actorlabel)
- [AttachmentReplication](ue_ue.PartyBeaconClient.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.PartyBeaconClient.md#autoreceiveinput)
- [BeaconConnection](ue_ue.PartyBeaconClient.md#beaconconnection)
- [BeaconConnectionInitialTimeout](ue_ue.PartyBeaconClient.md#beaconconnectioninitialtimeout)
- [BeaconConnectionTimeout](ue_ue.PartyBeaconClient.md#beaconconnectiontimeout)
- [BeaconOwner](ue_ue.PartyBeaconClient.md#beaconowner)
- [BlueprintCreatedComponents](ue_ue.PartyBeaconClient.md#blueprintcreatedcomponents)
- [Children](ue_ue.PartyBeaconClient.md#children)
- [ConnectionState](ue_ue.PartyBeaconClient.md#connectionstate)
- [ControllingMatineeActors](ue_ue.PartyBeaconClient.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.PartyBeaconClient.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.PartyBeaconClient.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [DestSessionId](ue_ue.PartyBeaconClient.md#destsessionid)
- [FolderPath](ue_ue.PartyBeaconClient.md#folderpath)
- [GroupActor](ue_ue.PartyBeaconClient.md#groupactor)
- [HiddenEditorViews](ue_ue.PartyBeaconClient.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.PartyBeaconClient.md#initiallifespan)
- [InputComponent](ue_ue.PartyBeaconClient.md#inputcomponent)
- [InputPriority](ue_ue.PartyBeaconClient.md#inputpriority)
- [InstanceComponents](ue_ue.PartyBeaconClient.md#instancecomponents)
- [Instigator](ue_ue.PartyBeaconClient.md#instigator)
- [Layers](ue_ue.PartyBeaconClient.md#layers)
- [MinNetUpdateFrequency](ue_ue.PartyBeaconClient.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.PartyBeaconClient.md#netculldistancesquared)
- [NetDormancy](ue_ue.PartyBeaconClient.md#netdormancy)
- [NetDriver](ue_ue.PartyBeaconClient.md#netdriver)
- [NetDriverName](ue_ue.PartyBeaconClient.md#netdrivername)
- [NetPriority](ue_ue.PartyBeaconClient.md#netpriority)
- [NetTag](ue_ue.PartyBeaconClient.md#nettag)
- [NetUpdateFrequency](ue_ue.PartyBeaconClient.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.PartyBeaconClient.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.PartyBeaconClient.md#onactorendoverlap)
- [OnActorHit](ue_ue.PartyBeaconClient.md#onactorhit)
- [OnBeginCursorOver](ue_ue.PartyBeaconClient.md#onbegincursorover)
- [OnClicked](ue_ue.PartyBeaconClient.md#onclicked)
- [OnDestroyed](ue_ue.PartyBeaconClient.md#ondestroyed)
- [OnEndCursorOver](ue_ue.PartyBeaconClient.md#onendcursorover)
- [OnEndPlay](ue_ue.PartyBeaconClient.md#onendplay)
- [OnInputTouchBegin](ue_ue.PartyBeaconClient.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.PartyBeaconClient.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.PartyBeaconClient.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.PartyBeaconClient.md#oninputtouchleave)
- [OnReleased](ue_ue.PartyBeaconClient.md#onreleased)
- [OnTakeAnyDamage](ue_ue.PartyBeaconClient.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.PartyBeaconClient.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.PartyBeaconClient.md#ontakeradialdamage)
- [Owner](ue_ue.PartyBeaconClient.md#owner)
- [ParentComponent](ue_ue.PartyBeaconClient.md#parentcomponent)
- [ParentComponentActor](ue_ue.PartyBeaconClient.md#parentcomponentactor)
- [PendingReservation](ue_ue.PartyBeaconClient.md#pendingreservation)
- [PivotOffset](ue_ue.PartyBeaconClient.md#pivotoffset)
- [PrimaryActorTick](ue_ue.PartyBeaconClient.md#primaryactortick)
- [RemoteRole](ue_ue.PartyBeaconClient.md#remoterole)
- [ReplicatedMovement](ue_ue.PartyBeaconClient.md#replicatedmovement)
- [RequestType](ue_ue.PartyBeaconClient.md#requesttype)
- [Role](ue_ue.PartyBeaconClient.md#role)
- [RootComponent](ue_ue.PartyBeaconClient.md#rootcomponent)
- [SpawnCollisionHandlingMethod](ue_ue.PartyBeaconClient.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.PartyBeaconClient.md#spritescale)
- [Tags](ue_ue.PartyBeaconClient.md#tags)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.PartyBeaconClient.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.PartyBeaconClient.md#__tid_actor__)
- [\_\_tid\_Object\_\_](ue_ue.PartyBeaconClient.md#__tid_object__)
- [\_\_tid\_OnlineBeaconClient\_\_](ue_ue.PartyBeaconClient.md#__tid_onlinebeaconclient__)
- [\_\_tid\_OnlineBeacon\_\_](ue_ue.PartyBeaconClient.md#__tid_onlinebeacon__)
- [\_\_tid\_PartyBeaconClient\_\_](ue_ue.PartyBeaconClient.md#__tid_partybeaconclient__)
- [bActorEnableCollision](ue_ue.PartyBeaconClient.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.PartyBeaconClient.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.PartyBeaconClient.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.PartyBeaconClient.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.PartyBeaconClient.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.PartyBeaconClient.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.PartyBeaconClient.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.PartyBeaconClient.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.PartyBeaconClient.md#bblockinput)
- [bCanBeDamaged](ue_ue.PartyBeaconClient.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.PartyBeaconClient.md#bcanbeincluster)
- [bCancelReservation](ue_ue.PartyBeaconClient.md#bcancelreservation)
- [bCollideWhenPlacing](ue_ue.PartyBeaconClient.md#bcollidewhenplacing)
- [bEditable](ue_ue.PartyBeaconClient.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.PartyBeaconClient.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.PartyBeaconClient.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.PartyBeaconClient.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.PartyBeaconClient.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.PartyBeaconClient.md#bhidden)
- [bHiddenEd](ue_ue.PartyBeaconClient.md#bhiddened)
- [bHiddenEdLayer](ue_ue.PartyBeaconClient.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.PartyBeaconClient.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.PartyBeaconClient.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.PartyBeaconClient.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.PartyBeaconClient.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.PartyBeaconClient.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.PartyBeaconClient.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.PartyBeaconClient.md#blocklocation)
- [bNetLoadOnClient](ue_ue.PartyBeaconClient.md#bnetloadonclient)
- [bNetStartup](ue_ue.PartyBeaconClient.md#bnetstartup)
- [bNetTemporary](ue_ue.PartyBeaconClient.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.PartyBeaconClient.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.PartyBeaconClient.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.PartyBeaconClient.md#boptimizebpcomponentdata)
- [bPendingReservationSent](ue_ue.PartyBeaconClient.md#bpendingreservationsent)
- [bRelevantForLevelBounds](ue_ue.PartyBeaconClient.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.PartyBeaconClient.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.PartyBeaconClient.md#breplayrewindable)
- [bReplicateMovement](ue_ue.PartyBeaconClient.md#breplicatemovement)
- [bReplicates](ue_ue.PartyBeaconClient.md#breplicates)
- [bTearOff](ue_ue.PartyBeaconClient.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.PartyBeaconClient.md#actorhastag)
- [AddComponent](ue_ue.PartyBeaconClient.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.PartyBeaconClient.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PartyBeaconClient.md#addtickprerequisitecomponent)
- [ClientCancelReservationResponse](ue_ue.PartyBeaconClient.md#clientcancelreservationresponse)
- [ClientOnConnected](ue_ue.PartyBeaconClient.md#clientonconnected)
- [ClientReservationResponse](ue_ue.PartyBeaconClient.md#clientreservationresponse)
- [ClientSendReservationFull](ue_ue.PartyBeaconClient.md#clientsendreservationfull)
- [ClientSendReservationUpdates](ue_ue.PartyBeaconClient.md#clientsendreservationupdates)
- [CreateDefaultSubobject](ue_ue.PartyBeaconClient.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.PartyBeaconClient.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.PartyBeaconClient.md#disableinput)
- [EnableInput](ue_ue.PartyBeaconClient.md#enableinput)
- [ExecuteUbergraph](ue_ue.PartyBeaconClient.md#executeubergraph)
- [FlushNetDormancy](ue_ue.PartyBeaconClient.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.PartyBeaconClient.md#forcenetupdate)
- [GetActorBounds](ue_ue.PartyBeaconClient.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.PartyBeaconClient.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.PartyBeaconClient.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.PartyBeaconClient.md#getactorforwardvector)
- [GetActorLabel](ue_ue.PartyBeaconClient.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.PartyBeaconClient.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.PartyBeaconClient.md#getactorrightvector)
- [GetActorScale3D](ue_ue.PartyBeaconClient.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.PartyBeaconClient.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.PartyBeaconClient.md#getactortimedilation)
- [GetActorUpVector](ue_ue.PartyBeaconClient.md#getactorupvector)
- [GetAllChildActors](ue_ue.PartyBeaconClient.md#getallchildactors)
- [GetAttachParentActor](ue_ue.PartyBeaconClient.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.PartyBeaconClient.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.PartyBeaconClient.md#getattachedactors)
- [GetClass](ue_ue.PartyBeaconClient.md#getclass)
- [GetComponentByClass](ue_ue.PartyBeaconClient.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.PartyBeaconClient.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.PartyBeaconClient.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.PartyBeaconClient.md#getdistanceto)
- [GetDotProductTo](ue_ue.PartyBeaconClient.md#getdotproductto)
- [GetFolderPath](ue_ue.PartyBeaconClient.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.PartyBeaconClient.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.PartyBeaconClient.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.PartyBeaconClient.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.PartyBeaconClient.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.PartyBeaconClient.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.PartyBeaconClient.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.PartyBeaconClient.md#getinstigator)
- [GetInstigatorController](ue_ue.PartyBeaconClient.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.PartyBeaconClient.md#getlifespan)
- [GetLocalRole](ue_ue.PartyBeaconClient.md#getlocalrole)
- [GetName](ue_ue.PartyBeaconClient.md#getname)
- [GetOuter](ue_ue.PartyBeaconClient.md#getouter)
- [GetOverlappingActors](ue_ue.PartyBeaconClient.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.PartyBeaconClient.md#getoverlappingcomponents)
- [GetOwner](ue_ue.PartyBeaconClient.md#getowner)
- [GetParentActor](ue_ue.PartyBeaconClient.md#getparentactor)
- [GetParentComponent](ue_ue.PartyBeaconClient.md#getparentcomponent)
- [GetRemoteRole](ue_ue.PartyBeaconClient.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.PartyBeaconClient.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.PartyBeaconClient.md#gettickablewhenpaused)
- [GetTransform](ue_ue.PartyBeaconClient.md#gettransform)
- [GetVelocity](ue_ue.PartyBeaconClient.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.PartyBeaconClient.md#getverticaldistanceto)
- [GetWorld](ue_ue.PartyBeaconClient.md#getworld)
- [HasAuthority](ue_ue.PartyBeaconClient.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.PartyBeaconClient.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.PartyBeaconClient.md#isactortickenabled)
- [IsChildActor](ue_ue.PartyBeaconClient.md#ischildactor)
- [IsEditable](ue_ue.PartyBeaconClient.md#iseditable)
- [IsHiddenEd](ue_ue.PartyBeaconClient.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.PartyBeaconClient.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.PartyBeaconClient.md#isoverlappingactor)
- [IsSelectable](ue_ue.PartyBeaconClient.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.PartyBeaconClient.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.PartyBeaconClient.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.PartyBeaconClient.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.PartyBeaconClient.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.PartyBeaconClient.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.PartyBeaconClient.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.PartyBeaconClient.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.PartyBeaconClient.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.PartyBeaconClient.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.PartyBeaconClient.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.PartyBeaconClient.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.PartyBeaconClient.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.PartyBeaconClient.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.PartyBeaconClient.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.PartyBeaconClient.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.PartyBeaconClient.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.PartyBeaconClient.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.PartyBeaconClient.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.PartyBeaconClient.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.PartyBeaconClient.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.PartyBeaconClient.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.PartyBeaconClient.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.PartyBeaconClient.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.PartyBeaconClient.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.PartyBeaconClient.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.PartyBeaconClient.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.PartyBeaconClient.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.PartyBeaconClient.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.PartyBeaconClient.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.PartyBeaconClient.md#makemidformaterial)
- [MakeNoise](ue_ue.PartyBeaconClient.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.PartyBeaconClient.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.PartyBeaconClient.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.PartyBeaconClient.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.PartyBeaconClient.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.PartyBeaconClient.md#onrep_replicatedmovement)
- [PrestreamTextures](ue_ue.PartyBeaconClient.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.PartyBeaconClient.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.PartyBeaconClient.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.PartyBeaconClient.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.PartyBeaconClient.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.PartyBeaconClient.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.PartyBeaconClient.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.PartyBeaconClient.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.PartyBeaconClient.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.PartyBeaconClient.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.PartyBeaconClient.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.PartyBeaconClient.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.PartyBeaconClient.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.PartyBeaconClient.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.PartyBeaconClient.md#receiveendplay)
- [ReceiveHit](ue_ue.PartyBeaconClient.md#receivehit)
- [ReceivePointDamage](ue_ue.PartyBeaconClient.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.PartyBeaconClient.md#receiveradialdamage)
- [ReceiveTick](ue_ue.PartyBeaconClient.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.PartyBeaconClient.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PartyBeaconClient.md#removetickprerequisitecomponent)
- [ServerCancelReservationRequest](ue_ue.PartyBeaconClient.md#servercancelreservationrequest)
- [ServerRemoveMemberFromReservationRequest](ue_ue.PartyBeaconClient.md#serverremovememberfromreservationrequest)
- [ServerReservationRequest](ue_ue.PartyBeaconClient.md#serverreservationrequest)
- [ServerUpdateReservationRequest](ue_ue.PartyBeaconClient.md#serverupdatereservationrequest)
- [SetActorEnableCollision](ue_ue.PartyBeaconClient.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.PartyBeaconClient.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.PartyBeaconClient.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.PartyBeaconClient.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.PartyBeaconClient.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.PartyBeaconClient.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.PartyBeaconClient.md#setactortickinterval)
- [SetFolderPath](ue_ue.PartyBeaconClient.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.PartyBeaconClient.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.PartyBeaconClient.md#setlifespan)
- [SetNetDormancy](ue_ue.PartyBeaconClient.md#setnetdormancy)
- [SetOwner](ue_ue.PartyBeaconClient.md#setowner)
- [SetReplicateMovement](ue_ue.PartyBeaconClient.md#setreplicatemovement)
- [SetReplicates](ue_ue.PartyBeaconClient.md#setreplicates)
- [SetTickGroup](ue_ue.PartyBeaconClient.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PartyBeaconClient.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.PartyBeaconClient.md#snaprootcomponentto)
- [TearOff](ue_ue.PartyBeaconClient.md#tearoff)
- [UserConstructionScript](ue_ue.PartyBeaconClient.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.PartyBeaconClient.md#wasrecentlyrendered)
- [Find](ue_ue.PartyBeaconClient.md#find)
- [Load](ue_ue.PartyBeaconClient.md#load)
- [StaticClass](ue_ue.PartyBeaconClient.md#staticclass)

## Constructors

### constructor

• **new PartyBeaconClient**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[constructor](ue_ue.OnlineBeaconClient.md#constructor)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ActorLabel](ue_ue.OnlineBeaconClient.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[AttachmentReplication](ue_ue.OnlineBeaconClient.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[AutoReceiveInput](ue_ue.OnlineBeaconClient.md#autoreceiveinput)

___

### BeaconConnection

• **BeaconConnection**: [`NetConnection`](ue_ue.NetConnection.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[BeaconConnection](ue_ue.OnlineBeaconClient.md#beaconconnection)

___

### BeaconConnectionInitialTimeout

• **BeaconConnectionInitialTimeout**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[BeaconConnectionInitialTimeout](ue_ue.OnlineBeaconClient.md#beaconconnectioninitialtimeout)

___

### BeaconConnectionTimeout

• **BeaconConnectionTimeout**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[BeaconConnectionTimeout](ue_ue.OnlineBeaconClient.md#beaconconnectiontimeout)

___

### BeaconOwner

• **BeaconOwner**: [`OnlineBeaconHostObject`](ue_ue.OnlineBeaconHostObject.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[BeaconOwner](ue_ue.OnlineBeaconClient.md#beaconowner)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[BlueprintCreatedComponents](ue_ue.OnlineBeaconClient.md#blueprintcreatedcomponents)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[Children](ue_ue.OnlineBeaconClient.md#children)

___

### ConnectionState

• **ConnectionState**: [`EBeaconConnectionState`](../enums/ue_ue.EBeaconConnectionState.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ConnectionState](ue_ue.OnlineBeaconClient.md#connectionstate)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ControllingMatineeActors](ue_ue.OnlineBeaconClient.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[CustomTimeDilation](ue_ue.OnlineBeaconClient.md#customtimedilation)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.OnlineBeaconClient.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### DestSessionId

• **DestSessionId**: `string`

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[FolderPath](ue_ue.OnlineBeaconClient.md#folderpath)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GroupActor](ue_ue.OnlineBeaconClient.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[HiddenEditorViews](ue_ue.OnlineBeaconClient.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[InitialLifeSpan](ue_ue.OnlineBeaconClient.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[InputComponent](ue_ue.OnlineBeaconClient.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[InputPriority](ue_ue.OnlineBeaconClient.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[InstanceComponents](ue_ue.OnlineBeaconClient.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[Instigator](ue_ue.OnlineBeaconClient.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[Layers](ue_ue.OnlineBeaconClient.md#layers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[MinNetUpdateFrequency](ue_ue.OnlineBeaconClient.md#minnetupdatefrequency)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[NetCullDistanceSquared](ue_ue.OnlineBeaconClient.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[NetDormancy](ue_ue.OnlineBeaconClient.md#netdormancy)

___

### NetDriver

• **NetDriver**: [`NetDriver`](ue_ue.NetDriver.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[NetDriver](ue_ue.OnlineBeaconClient.md#netdriver)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[NetDriverName](ue_ue.OnlineBeaconClient.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[NetPriority](ue_ue.OnlineBeaconClient.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[NetTag](ue_ue.OnlineBeaconClient.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[NetUpdateFrequency](ue_ue.OnlineBeaconClient.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnActorBeginOverlap](ue_ue.OnlineBeaconClient.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnActorEndOverlap](ue_ue.OnlineBeaconClient.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnActorHit](ue_ue.OnlineBeaconClient.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnBeginCursorOver](ue_ue.OnlineBeaconClient.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnClicked](ue_ue.OnlineBeaconClient.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnDestroyed](ue_ue.OnlineBeaconClient.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnEndCursorOver](ue_ue.OnlineBeaconClient.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnEndPlay](ue_ue.OnlineBeaconClient.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnInputTouchBegin](ue_ue.OnlineBeaconClient.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnInputTouchEnd](ue_ue.OnlineBeaconClient.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnInputTouchEnter](ue_ue.OnlineBeaconClient.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnInputTouchLeave](ue_ue.OnlineBeaconClient.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnReleased](ue_ue.OnlineBeaconClient.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnTakeAnyDamage](ue_ue.OnlineBeaconClient.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnTakePointDamage](ue_ue.OnlineBeaconClient.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnTakeRadialDamage](ue_ue.OnlineBeaconClient.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[Owner](ue_ue.OnlineBeaconClient.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ParentComponent](ue_ue.OnlineBeaconClient.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ParentComponentActor](ue_ue.OnlineBeaconClient.md#parentcomponentactor)

___

### PendingReservation

• **PendingReservation**: [`PartyReservation`](ue_ue.PartyReservation.md)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[PivotOffset](ue_ue.OnlineBeaconClient.md#pivotoffset)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[PrimaryActorTick](ue_ue.OnlineBeaconClient.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[RemoteRole](ue_ue.OnlineBeaconClient.md#remoterole)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReplicatedMovement](ue_ue.OnlineBeaconClient.md#replicatedmovement)

___

### RequestType

• **RequestType**: [`EClientRequestType`](../enums/ue_ue.EClientRequestType.md)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[Role](ue_ue.OnlineBeaconClient.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[RootComponent](ue_ue.OnlineBeaconClient.md#rootcomponent)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SpawnCollisionHandlingMethod](ue_ue.OnlineBeaconClient.md#spawncollisionhandlingmethod)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SpriteScale](ue_ue.OnlineBeaconClient.md#spritescale)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[Tags](ue_ue.OnlineBeaconClient.md#tags)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.OnlineBeaconClient.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[__tid_Actor__](ue_ue.OnlineBeaconClient.md#__tid_actor__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[__tid_Object__](ue_ue.OnlineBeaconClient.md#__tid_object__)

___

### \_\_tid\_OnlineBeaconClient\_\_

• **\_\_tid\_OnlineBeaconClient\_\_**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[__tid_OnlineBeaconClient__](ue_ue.OnlineBeaconClient.md#__tid_onlinebeaconclient__)

___

### \_\_tid\_OnlineBeacon\_\_

• **\_\_tid\_OnlineBeacon\_\_**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[__tid_OnlineBeacon__](ue_ue.OnlineBeaconClient.md#__tid_onlinebeacon__)

___

### \_\_tid\_PartyBeaconClient\_\_

• **\_\_tid\_PartyBeaconClient\_\_**: `boolean`

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bActorEnableCollision](ue_ue.OnlineBeaconClient.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bActorIsBeingDestroyed](ue_ue.OnlineBeaconClient.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bActorLabelEditable](ue_ue.OnlineBeaconClient.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bActorSeamlessTraveled](ue_ue.OnlineBeaconClient.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.OnlineBeaconClient.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bAllowTickBeforeBeginPlay](ue_ue.OnlineBeaconClient.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bAlwaysRelevant](ue_ue.OnlineBeaconClient.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bAutoDestroyWhenFinished](ue_ue.OnlineBeaconClient.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bBlockInput](ue_ue.OnlineBeaconClient.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bCanBeDamaged](ue_ue.OnlineBeaconClient.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bCanBeInCluster](ue_ue.OnlineBeaconClient.md#bcanbeincluster)

___

### bCancelReservation

• **bCancelReservation**: `boolean`

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bCollideWhenPlacing](ue_ue.OnlineBeaconClient.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bEditable](ue_ue.OnlineBeaconClient.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bEnableAutoLODGeneration](ue_ue.OnlineBeaconClient.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bExchangedRoles](ue_ue.OnlineBeaconClient.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bFindCameraComponentWhenViewTarget](ue_ue.OnlineBeaconClient.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.OnlineBeaconClient.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bHidden](ue_ue.OnlineBeaconClient.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bHiddenEd](ue_ue.OnlineBeaconClient.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bHiddenEdLayer](ue_ue.OnlineBeaconClient.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bHiddenEdLevel](ue_ue.OnlineBeaconClient.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bHiddenEdTemporary](ue_ue.OnlineBeaconClient.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bIgnoresOriginShifting](ue_ue.OnlineBeaconClient.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bIsEditorOnlyActor](ue_ue.OnlineBeaconClient.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bIsEditorPreviewActor](ue_ue.OnlineBeaconClient.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bListedInSceneOutliner](ue_ue.OnlineBeaconClient.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bLockLocation](ue_ue.OnlineBeaconClient.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bNetLoadOnClient](ue_ue.OnlineBeaconClient.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bNetStartup](ue_ue.OnlineBeaconClient.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bNetTemporary](ue_ue.OnlineBeaconClient.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bNetUseOwnerRelevancy](ue_ue.OnlineBeaconClient.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bOnlyRelevantToOwner](ue_ue.OnlineBeaconClient.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bOptimizeBPComponentData](ue_ue.OnlineBeaconClient.md#boptimizebpcomponentdata)

___

### bPendingReservationSent

• **bPendingReservationSent**: `boolean`

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bRelevantForLevelBounds](ue_ue.OnlineBeaconClient.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bRelevantForNetworkReplays](ue_ue.OnlineBeaconClient.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bReplayRewindable](ue_ue.OnlineBeaconClient.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bReplicateMovement](ue_ue.OnlineBeaconClient.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bReplicates](ue_ue.OnlineBeaconClient.md#breplicates)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bTearOff](ue_ue.OnlineBeaconClient.md#btearoff)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ActorHasTag](ue_ue.OnlineBeaconClient.md#actorhastag)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[AddComponent](ue_ue.OnlineBeaconClient.md#addcomponent)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[AddTickPrerequisiteActor](ue_ue.OnlineBeaconClient.md#addtickprerequisiteactor)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[AddTickPrerequisiteComponent](ue_ue.OnlineBeaconClient.md#addtickprerequisitecomponent)

___

### ClientCancelReservationResponse

▸ **ClientCancelReservationResponse**(`ReservationResponse`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ReservationResponse` | [`EPartyReservationResult`](../enums/ue_ue.EPartyReservationResult.md) |

#### Returns

`void`

___

### ClientOnConnected

▸ **ClientOnConnected**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ClientOnConnected](ue_ue.OnlineBeaconClient.md#clientonconnected)

___

### ClientReservationResponse

▸ **ClientReservationResponse**(`ReservationResponse`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ReservationResponse` | [`EPartyReservationResult`](../enums/ue_ue.EPartyReservationResult.md) |

#### Returns

`void`

___

### ClientSendReservationFull

▸ **ClientSendReservationFull**(): `void`

#### Returns

`void`

___

### ClientSendReservationUpdates

▸ **ClientSendReservationUpdates**(`NumRemainingReservations`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumRemainingReservations` | `number` |

#### Returns

`void`

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[CreateDefaultSubobject](ue_ue.OnlineBeaconClient.md#createdefaultsubobject)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[DetachRootComponentFromParent](ue_ue.OnlineBeaconClient.md#detachrootcomponentfromparent)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[DisableInput](ue_ue.OnlineBeaconClient.md#disableinput)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[EnableInput](ue_ue.OnlineBeaconClient.md#enableinput)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ExecuteUbergraph](ue_ue.OnlineBeaconClient.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[FlushNetDormancy](ue_ue.OnlineBeaconClient.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ForceNetUpdate](ue_ue.OnlineBeaconClient.md#forcenetupdate)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorBounds](ue_ue.OnlineBeaconClient.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorEnableCollision](ue_ue.OnlineBeaconClient.md#getactorenablecollision)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorEyesViewPoint](ue_ue.OnlineBeaconClient.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorForwardVector](ue_ue.OnlineBeaconClient.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorLabel](ue_ue.OnlineBeaconClient.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorRelativeScale3D](ue_ue.OnlineBeaconClient.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorRightVector](ue_ue.OnlineBeaconClient.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorScale3D](ue_ue.OnlineBeaconClient.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorTickInterval](ue_ue.OnlineBeaconClient.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorTimeDilation](ue_ue.OnlineBeaconClient.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorUpVector](ue_ue.OnlineBeaconClient.md#getactorupvector)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetAllChildActors](ue_ue.OnlineBeaconClient.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetAttachParentActor](ue_ue.OnlineBeaconClient.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetAttachParentSocketName](ue_ue.OnlineBeaconClient.md#getattachparentsocketname)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetAttachedActors](ue_ue.OnlineBeaconClient.md#getattachedactors)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetClass](ue_ue.OnlineBeaconClient.md#getclass)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetComponentByClass](ue_ue.OnlineBeaconClient.md#getcomponentbyclass)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetComponentsByInterface](ue_ue.OnlineBeaconClient.md#getcomponentsbyinterface)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetComponentsByTag](ue_ue.OnlineBeaconClient.md#getcomponentsbytag)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetDistanceTo](ue_ue.OnlineBeaconClient.md#getdistanceto)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetDotProductTo](ue_ue.OnlineBeaconClient.md#getdotproductto)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetFolderPath](ue_ue.OnlineBeaconClient.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetGameTimeSinceCreation](ue_ue.OnlineBeaconClient.md#getgametimesincecreation)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetHorizontalDistanceTo](ue_ue.OnlineBeaconClient.md#gethorizontaldistanceto)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetHorizontalDotProductTo](ue_ue.OnlineBeaconClient.md#gethorizontaldotproductto)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetInputAxisKeyValue](ue_ue.OnlineBeaconClient.md#getinputaxiskeyvalue)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetInputAxisValue](ue_ue.OnlineBeaconClient.md#getinputaxisvalue)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetInputVectorAxisValue](ue_ue.OnlineBeaconClient.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetInstigator](ue_ue.OnlineBeaconClient.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetInstigatorController](ue_ue.OnlineBeaconClient.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetLifeSpan](ue_ue.OnlineBeaconClient.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetLocalRole](ue_ue.OnlineBeaconClient.md#getlocalrole)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetName](ue_ue.OnlineBeaconClient.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetOuter](ue_ue.OnlineBeaconClient.md#getouter)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetOverlappingActors](ue_ue.OnlineBeaconClient.md#getoverlappingactors)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetOverlappingComponents](ue_ue.OnlineBeaconClient.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetOwner](ue_ue.OnlineBeaconClient.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetParentActor](ue_ue.OnlineBeaconClient.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetParentComponent](ue_ue.OnlineBeaconClient.md#getparentcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetRemoteRole](ue_ue.OnlineBeaconClient.md#getremoterole)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetSquaredDistanceTo](ue_ue.OnlineBeaconClient.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetTickableWhenPaused](ue_ue.OnlineBeaconClient.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetTransform](ue_ue.OnlineBeaconClient.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetVelocity](ue_ue.OnlineBeaconClient.md#getvelocity)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetVerticalDistanceTo](ue_ue.OnlineBeaconClient.md#getverticaldistanceto)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetWorld](ue_ue.OnlineBeaconClient.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[HasAuthority](ue_ue.OnlineBeaconClient.md#hasauthority)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsActorBeingDestroyed](ue_ue.OnlineBeaconClient.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsActorTickEnabled](ue_ue.OnlineBeaconClient.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsChildActor](ue_ue.OnlineBeaconClient.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsEditable](ue_ue.OnlineBeaconClient.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsHiddenEd](ue_ue.OnlineBeaconClient.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsHiddenEdAtStartup](ue_ue.OnlineBeaconClient.md#ishiddenedatstartup)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsOverlappingActor](ue_ue.OnlineBeaconClient.md#isoverlappingactor)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsSelectable](ue_ue.OnlineBeaconClient.md#isselectable)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsTemporarilyHiddenInEditor](ue_ue.OnlineBeaconClient.md#istemporarilyhiddenineditor)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AddActorLocalOffset](ue_ue.OnlineBeaconClient.md#k2_addactorlocaloffset)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AddActorLocalRotation](ue_ue.OnlineBeaconClient.md#k2_addactorlocalrotation)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AddActorLocalTransform](ue_ue.OnlineBeaconClient.md#k2_addactorlocaltransform)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AddActorWorldOffset](ue_ue.OnlineBeaconClient.md#k2_addactorworldoffset)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AddActorWorldRotation](ue_ue.OnlineBeaconClient.md#k2_addactorworldrotation)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AddActorWorldTransform](ue_ue.OnlineBeaconClient.md#k2_addactorworldtransform)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AttachRootComponentTo](ue_ue.OnlineBeaconClient.md#k2_attachrootcomponentto)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AttachRootComponentToActor](ue_ue.OnlineBeaconClient.md#k2_attachrootcomponenttoactor)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AttachToActor](ue_ue.OnlineBeaconClient.md#k2_attachtoactor)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AttachToComponent](ue_ue.OnlineBeaconClient.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_DestroyActor](ue_ue.OnlineBeaconClient.md#k2_destroyactor)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_DestroyComponent](ue_ue.OnlineBeaconClient.md#k2_destroycomponent)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_DetachFromActor](ue_ue.OnlineBeaconClient.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_GetActorLocation](ue_ue.OnlineBeaconClient.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_GetActorRotation](ue_ue.OnlineBeaconClient.md#k2_getactorrotation)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_GetComponentsByClass](ue_ue.OnlineBeaconClient.md#k2_getcomponentsbyclass)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_GetRootComponent](ue_ue.OnlineBeaconClient.md#k2_getrootcomponent)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_OnBecomeViewTarget](ue_ue.OnlineBeaconClient.md#k2_onbecomeviewtarget)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_OnEndViewTarget](ue_ue.OnlineBeaconClient.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_OnReset](ue_ue.OnlineBeaconClient.md#k2_onreset)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_SetActorLocation](ue_ue.OnlineBeaconClient.md#k2_setactorlocation)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_SetActorLocationAndRotation](ue_ue.OnlineBeaconClient.md#k2_setactorlocationandrotation)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_SetActorRelativeLocation](ue_ue.OnlineBeaconClient.md#k2_setactorrelativelocation)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_SetActorRelativeRotation](ue_ue.OnlineBeaconClient.md#k2_setactorrelativerotation)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_SetActorRelativeTransform](ue_ue.OnlineBeaconClient.md#k2_setactorrelativetransform)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_SetActorRotation](ue_ue.OnlineBeaconClient.md#k2_setactorrotation)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_SetActorTransform](ue_ue.OnlineBeaconClient.md#k2_setactortransform)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_TeleportTo](ue_ue.OnlineBeaconClient.md#k2_teleportto)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[MakeMIDForMaterial](ue_ue.OnlineBeaconClient.md#makemidformaterial)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[MakeNoise](ue_ue.OnlineBeaconClient.md#makenoise)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnRep_AttachmentReplication](ue_ue.OnlineBeaconClient.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnRep_Instigator](ue_ue.OnlineBeaconClient.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnRep_Owner](ue_ue.OnlineBeaconClient.md#onrep_owner)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnRep_ReplicateMovement](ue_ue.OnlineBeaconClient.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnRep_ReplicatedMovement](ue_ue.OnlineBeaconClient.md#onrep_replicatedmovement)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[PrestreamTextures](ue_ue.OnlineBeaconClient.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorBeginCursorOver](ue_ue.OnlineBeaconClient.md#receiveactorbegincursorover)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorBeginOverlap](ue_ue.OnlineBeaconClient.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorEndCursorOver](ue_ue.OnlineBeaconClient.md#receiveactorendcursorover)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorEndOverlap](ue_ue.OnlineBeaconClient.md#receiveactorendoverlap)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorOnClicked](ue_ue.OnlineBeaconClient.md#receiveactoronclicked)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorOnInputTouchBegin](ue_ue.OnlineBeaconClient.md#receiveactoroninputtouchbegin)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorOnInputTouchEnd](ue_ue.OnlineBeaconClient.md#receiveactoroninputtouchend)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorOnInputTouchEnter](ue_ue.OnlineBeaconClient.md#receiveactoroninputtouchenter)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorOnInputTouchLeave](ue_ue.OnlineBeaconClient.md#receiveactoroninputtouchleave)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorOnReleased](ue_ue.OnlineBeaconClient.md#receiveactoronreleased)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveAnyDamage](ue_ue.OnlineBeaconClient.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveBeginPlay](ue_ue.OnlineBeaconClient.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveDestroyed](ue_ue.OnlineBeaconClient.md#receivedestroyed)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveEndPlay](ue_ue.OnlineBeaconClient.md#receiveendplay)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveHit](ue_ue.OnlineBeaconClient.md#receivehit)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceivePointDamage](ue_ue.OnlineBeaconClient.md#receivepointdamage)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveRadialDamage](ue_ue.OnlineBeaconClient.md#receiveradialdamage)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveTick](ue_ue.OnlineBeaconClient.md#receivetick)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[RemoveTickPrerequisiteActor](ue_ue.OnlineBeaconClient.md#removetickprerequisiteactor)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[RemoveTickPrerequisiteComponent](ue_ue.OnlineBeaconClient.md#removetickprerequisitecomponent)

___

### ServerCancelReservationRequest

▸ **ServerCancelReservationRequest**(`PartyLeader`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PartyLeader` | [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md) |

#### Returns

`void`

___

### ServerRemoveMemberFromReservationRequest

▸ **ServerRemoveMemberFromReservationRequest**(`SessionId`, `ReservationUpdate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SessionId` | `string` |
| `ReservationUpdate` | [`PartyReservation`](ue_ue.PartyReservation.md) |

#### Returns

`void`

___

### ServerReservationRequest

▸ **ServerReservationRequest**(`SessionId`, `Reservation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SessionId` | `string` |
| `Reservation` | [`PartyReservation`](ue_ue.PartyReservation.md) |

#### Returns

`void`

___

### ServerUpdateReservationRequest

▸ **ServerUpdateReservationRequest**(`SessionId`, `ReservationUpdate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SessionId` | `string` |
| `ReservationUpdate` | [`PartyReservation`](ue_ue.PartyReservation.md) |

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetActorEnableCollision](ue_ue.OnlineBeaconClient.md#setactorenablecollision)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetActorHiddenInGame](ue_ue.OnlineBeaconClient.md#setactorhiddeningame)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetActorLabel](ue_ue.OnlineBeaconClient.md#setactorlabel)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetActorRelativeScale3D](ue_ue.OnlineBeaconClient.md#setactorrelativescale3d)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetActorScale3D](ue_ue.OnlineBeaconClient.md#setactorscale3d)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetActorTickEnabled](ue_ue.OnlineBeaconClient.md#setactortickenabled)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetActorTickInterval](ue_ue.OnlineBeaconClient.md#setactortickinterval)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetFolderPath](ue_ue.OnlineBeaconClient.md#setfolderpath)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetIsTemporarilyHiddenInEditor](ue_ue.OnlineBeaconClient.md#setistemporarilyhiddenineditor)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetLifeSpan](ue_ue.OnlineBeaconClient.md#setlifespan)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetNetDormancy](ue_ue.OnlineBeaconClient.md#setnetdormancy)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetOwner](ue_ue.OnlineBeaconClient.md#setowner)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetReplicateMovement](ue_ue.OnlineBeaconClient.md#setreplicatemovement)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetReplicates](ue_ue.OnlineBeaconClient.md#setreplicates)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetTickGroup](ue_ue.OnlineBeaconClient.md#settickgroup)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetTickableWhenPaused](ue_ue.OnlineBeaconClient.md#settickablewhenpaused)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SnapRootComponentTo](ue_ue.OnlineBeaconClient.md#snaprootcomponentto)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[TearOff](ue_ue.OnlineBeaconClient.md#tearoff)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[UserConstructionScript](ue_ue.OnlineBeaconClient.md#userconstructionscript)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[WasRecentlyRendered](ue_ue.OnlineBeaconClient.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PartyBeaconClient`](ue_ue.PartyBeaconClient.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PartyBeaconClient`](ue_ue.PartyBeaconClient.md)

#### Overrides

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[Find](ue_ue.OnlineBeaconClient.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PartyBeaconClient`](ue_ue.PartyBeaconClient.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PartyBeaconClient`](ue_ue.PartyBeaconClient.md)

#### Overrides

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[Load](ue_ue.OnlineBeaconClient.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[StaticClass](ue_ue.OnlineBeaconClient.md#staticclass)
