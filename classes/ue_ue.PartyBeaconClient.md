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

#### Defined in

[ue/ue.d.ts:56857](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56857)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ActorLabel](ue_ue.OnlineBeaconClient.md#actorlabel)

#### Defined in

[ue/ue.d.ts:13176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13176)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[AttachmentReplication](ue_ue.OnlineBeaconClient.md#attachmentreplication)

#### Defined in

[ue/ue.d.ts:13151](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13151)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[AutoReceiveInput](ue_ue.OnlineBeaconClient.md#autoreceiveinput)

#### Defined in

[ue/ue.d.ts:13157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13157)

___

### BeaconConnection

• **BeaconConnection**: [`NetConnection`](ue_ue.NetConnection.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[BeaconConnection](ue_ue.OnlineBeaconClient.md#beaconconnection)

#### Defined in

[ue/ue.d.ts:54197](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54197)

___

### BeaconConnectionInitialTimeout

• **BeaconConnectionInitialTimeout**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[BeaconConnectionInitialTimeout](ue_ue.OnlineBeaconClient.md#beaconconnectioninitialtimeout)

#### Defined in

[ue/ue.d.ts:54172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54172)

___

### BeaconConnectionTimeout

• **BeaconConnectionTimeout**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[BeaconConnectionTimeout](ue_ue.OnlineBeaconClient.md#beaconconnectiontimeout)

#### Defined in

[ue/ue.d.ts:54173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54173)

___

### BeaconOwner

• **BeaconOwner**: [`OnlineBeaconHostObject`](ue_ue.OnlineBeaconHostObject.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[BeaconOwner](ue_ue.OnlineBeaconClient.md#beaconowner)

#### Defined in

[ue/ue.d.ts:54196](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54196)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[BlueprintCreatedComponents](ue_ue.OnlineBeaconClient.md#blueprintcreatedcomponents)

#### Defined in

[ue/ue.d.ts:13206](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13206)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[Children](ue_ue.OnlineBeaconClient.md#children)

#### Defined in

[ue/ue.d.ts:13166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13166)

___

### ConnectionState

• **ConnectionState**: [`EBeaconConnectionState`](../enums/ue_ue.EBeaconConnectionState.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ConnectionState](ue_ue.OnlineBeaconClient.md#connectionstate)

#### Defined in

[ue/ue.d.ts:54198](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54198)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ControllingMatineeActors](ue_ue.OnlineBeaconClient.md#controllingmatineeactors)

#### Defined in

[ue/ue.d.ts:13169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13169)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[CustomTimeDilation](ue_ue.OnlineBeaconClient.md#customtimedilation)

#### Defined in

[ue/ue.d.ts:13150](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13150)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.OnlineBeaconClient.md#defaultupdateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13146](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13146)

___

### DestSessionId

• **DestSessionId**: `string`

#### Defined in

[ue/ue.d.ts:56858](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56858)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[FolderPath](ue_ue.OnlineBeaconClient.md#folderpath)

#### Defined in

[ue/ue.d.ts:13177](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13177)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GroupActor](ue_ue.OnlineBeaconClient.md#groupactor)

#### Defined in

[ue/ue.d.ts:13173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13173)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[HiddenEditorViews](ue_ue.OnlineBeaconClient.md#hiddeneditorviews)

#### Defined in

[ue/ue.d.ts:13175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13175)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[InitialLifeSpan](ue_ue.OnlineBeaconClient.md#initiallifespan)

#### Defined in

[ue/ue.d.ts:13149](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13149)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[InputComponent](ue_ue.OnlineBeaconClient.md#inputcomponent)

#### Defined in

[ue/ue.d.ts:13159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13159)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[InputPriority](ue_ue.OnlineBeaconClient.md#inputpriority)

#### Defined in

[ue/ue.d.ts:13158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13158)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[InstanceComponents](ue_ue.OnlineBeaconClient.md#instancecomponents)

#### Defined in

[ue/ue.d.ts:13205](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13205)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[Instigator](ue_ue.OnlineBeaconClient.md#instigator)

#### Defined in

[ue/ue.d.ts:13165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13165)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[Layers](ue_ue.OnlineBeaconClient.md#layers)

#### Defined in

[ue/ue.d.ts:13170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13170)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[MinNetUpdateFrequency](ue_ue.OnlineBeaconClient.md#minnetupdatefrequency)

#### Defined in

[ue/ue.d.ts:13163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13163)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[NetCullDistanceSquared](ue_ue.OnlineBeaconClient.md#netculldistancesquared)

#### Defined in

[ue/ue.d.ts:13160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13160)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[NetDormancy](ue_ue.OnlineBeaconClient.md#netdormancy)

#### Defined in

[ue/ue.d.ts:13155](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13155)

___

### NetDriver

• **NetDriver**: [`NetDriver`](ue_ue.NetDriver.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[NetDriver](ue_ue.OnlineBeaconClient.md#netdriver)

#### Defined in

[ue/ue.d.ts:54174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54174)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[NetDriverName](ue_ue.OnlineBeaconClient.md#netdrivername)

#### Defined in

[ue/ue.d.ts:13153](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13153)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[NetPriority](ue_ue.OnlineBeaconClient.md#netpriority)

#### Defined in

[ue/ue.d.ts:13164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13164)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[NetTag](ue_ue.OnlineBeaconClient.md#nettag)

#### Defined in

[ue/ue.d.ts:13161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13161)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[NetUpdateFrequency](ue_ue.OnlineBeaconClient.md#netupdatefrequency)

#### Defined in

[ue/ue.d.ts:13162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13162)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnActorBeginOverlap](ue_ue.OnlineBeaconClient.md#onactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13192](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13192)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnActorEndOverlap](ue_ue.OnlineBeaconClient.md#onactorendoverlap)

#### Defined in

[ue/ue.d.ts:13193](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13193)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnActorHit](ue_ue.OnlineBeaconClient.md#onactorhit)

#### Defined in

[ue/ue.d.ts:13202](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13202)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnBeginCursorOver](ue_ue.OnlineBeaconClient.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:13194](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13194)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnClicked](ue_ue.OnlineBeaconClient.md#onclicked)

#### Defined in

[ue/ue.d.ts:13196](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13196)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnDestroyed](ue_ue.OnlineBeaconClient.md#ondestroyed)

#### Defined in

[ue/ue.d.ts:13203](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13203)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnEndCursorOver](ue_ue.OnlineBeaconClient.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:13195](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13195)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnEndPlay](ue_ue.OnlineBeaconClient.md#onendplay)

#### Defined in

[ue/ue.d.ts:13204](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13204)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnInputTouchBegin](ue_ue.OnlineBeaconClient.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13198](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13198)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnInputTouchEnd](ue_ue.OnlineBeaconClient.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:13199](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13199)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnInputTouchEnter](ue_ue.OnlineBeaconClient.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:13200](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13200)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnInputTouchLeave](ue_ue.OnlineBeaconClient.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:13201](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13201)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnReleased](ue_ue.OnlineBeaconClient.md#onreleased)

#### Defined in

[ue/ue.d.ts:13197](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13197)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnTakeAnyDamage](ue_ue.OnlineBeaconClient.md#ontakeanydamage)

#### Defined in

[ue/ue.d.ts:13189](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13189)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnTakePointDamage](ue_ue.OnlineBeaconClient.md#ontakepointdamage)

#### Defined in

[ue/ue.d.ts:13190](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13190)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnTakeRadialDamage](ue_ue.OnlineBeaconClient.md#ontakeradialdamage)

#### Defined in

[ue/ue.d.ts:13191](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13191)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[Owner](ue_ue.OnlineBeaconClient.md#owner)

#### Defined in

[ue/ue.d.ts:13152](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13152)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ParentComponent](ue_ue.OnlineBeaconClient.md#parentcomponent)

#### Defined in

[ue/ue.d.ts:13172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13172)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ParentComponentActor](ue_ue.OnlineBeaconClient.md#parentcomponentactor)

#### Defined in

[ue/ue.d.ts:13171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13171)

___

### PendingReservation

• **PendingReservation**: [`PartyReservation`](ue_ue.PartyReservation.md)

#### Defined in

[ue/ue.d.ts:56859](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56859)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[PivotOffset](ue_ue.OnlineBeaconClient.md#pivotoffset)

#### Defined in

[ue/ue.d.ts:13168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13168)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[PrimaryActorTick](ue_ue.OnlineBeaconClient.md#primaryactortick)

#### Defined in

[ue/ue.d.ts:13115](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13115)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[RemoteRole](ue_ue.OnlineBeaconClient.md#remoterole)

#### Defined in

[ue/ue.d.ts:13147](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13147)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReplicatedMovement](ue_ue.OnlineBeaconClient.md#replicatedmovement)

#### Defined in

[ue/ue.d.ts:13148](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13148)

___

### RequestType

• **RequestType**: [`EClientRequestType`](../enums/ue_ue.EClientRequestType.md)

#### Defined in

[ue/ue.d.ts:56860](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56860)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[Role](ue_ue.OnlineBeaconClient.md#role)

#### Defined in

[ue/ue.d.ts:13154](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13154)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[RootComponent](ue_ue.OnlineBeaconClient.md#rootcomponent)

#### Defined in

[ue/ue.d.ts:13167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13167)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SpawnCollisionHandlingMethod](ue_ue.OnlineBeaconClient.md#spawncollisionhandlingmethod)

#### Defined in

[ue/ue.d.ts:13156](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13156)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SpriteScale](ue_ue.OnlineBeaconClient.md#spritescale)

#### Defined in

[ue/ue.d.ts:13174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13174)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[Tags](ue_ue.OnlineBeaconClient.md#tags)

#### Defined in

[ue/ue.d.ts:13188](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13188)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.OnlineBeaconClient.md#updateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13145](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13145)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[__tid_Actor__](ue_ue.OnlineBeaconClient.md#__tid_actor__)

#### Defined in

[ue/ue.d.ts:13348](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13348)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[__tid_Object__](ue_ue.OnlineBeaconClient.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_OnlineBeaconClient\_\_

• **\_\_tid\_OnlineBeaconClient\_\_**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[__tid_OnlineBeaconClient__](ue_ue.OnlineBeaconClient.md#__tid_onlinebeaconclient__)

#### Defined in

[ue/ue.d.ts:54204](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54204)

___

### \_\_tid\_OnlineBeacon\_\_

• **\_\_tid\_OnlineBeacon\_\_**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[__tid_OnlineBeacon__](ue_ue.OnlineBeaconClient.md#__tid_onlinebeacon__)

#### Defined in

[ue/ue.d.ts:54179](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54179)

___

### \_\_tid\_PartyBeaconClient\_\_

• **\_\_tid\_PartyBeaconClient\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:56875](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56875)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bActorEnableCollision](ue_ue.OnlineBeaconClient.md#bactorenablecollision)

#### Defined in

[ue/ue.d.ts:13143](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13143)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bActorIsBeingDestroyed](ue_ue.OnlineBeaconClient.md#bactorisbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13144](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13144)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bActorLabelEditable](ue_ue.OnlineBeaconClient.md#bactorlabeleditable)

#### Defined in

[ue/ue.d.ts:13183](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13183)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bActorSeamlessTraveled](ue_ue.OnlineBeaconClient.md#bactorseamlesstraveled)

#### Defined in

[ue/ue.d.ts:13139](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13139)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.OnlineBeaconClient.md#ballowreceivetickeventondedicatedserver)

#### Defined in

[ue/ue.d.ts:13142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13142)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bAllowTickBeforeBeginPlay](ue_ue.OnlineBeaconClient.md#ballowtickbeforebeginplay)

#### Defined in

[ue/ue.d.ts:13129](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13129)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bAlwaysRelevant](ue_ue.OnlineBeaconClient.md#balwaysrelevant)

#### Defined in

[ue/ue.d.ts:13120](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13120)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bAutoDestroyWhenFinished](ue_ue.OnlineBeaconClient.md#bautodestroywhenfinished)

#### Defined in

[ue/ue.d.ts:13130](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13130)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bBlockInput](ue_ue.OnlineBeaconClient.md#bblockinput)

#### Defined in

[ue/ue.d.ts:13131](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13131)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bCanBeDamaged](ue_ue.OnlineBeaconClient.md#bcanbedamaged)

#### Defined in

[ue/ue.d.ts:13132](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13132)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bCanBeInCluster](ue_ue.OnlineBeaconClient.md#bcanbeincluster)

#### Defined in

[ue/ue.d.ts:13141](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13141)

___

### bCancelReservation

• **bCancelReservation**: `boolean`

#### Defined in

[ue/ue.d.ts:56862](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56862)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bCollideWhenPlacing](ue_ue.OnlineBeaconClient.md#bcollidewhenplacing)

#### Defined in

[ue/ue.d.ts:13133](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13133)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bEditable](ue_ue.OnlineBeaconClient.md#beditable)

#### Defined in

[ue/ue.d.ts:13184](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13184)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bEnableAutoLODGeneration](ue_ue.OnlineBeaconClient.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:13137](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13137)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bExchangedRoles](ue_ue.OnlineBeaconClient.md#bexchangedroles)

#### Defined in

[ue/ue.d.ts:13123](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13123)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bFindCameraComponentWhenViewTarget](ue_ue.OnlineBeaconClient.md#bfindcameracomponentwhenviewtarget)

#### Defined in

[ue/ue.d.ts:13134](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13134)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.OnlineBeaconClient.md#bgenerateoverlapeventsduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13135](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13135)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bHidden](ue_ue.OnlineBeaconClient.md#bhidden)

#### Defined in

[ue/ue.d.ts:13116](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13116)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bHiddenEd](ue_ue.OnlineBeaconClient.md#bhiddened)

#### Defined in

[ue/ue.d.ts:13178](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13178)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bHiddenEdLayer](ue_ue.OnlineBeaconClient.md#bhiddenedlayer)

#### Defined in

[ue/ue.d.ts:13180](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13180)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bHiddenEdLevel](ue_ue.OnlineBeaconClient.md#bhiddenedlevel)

#### Defined in

[ue/ue.d.ts:13181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13181)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bHiddenEdTemporary](ue_ue.OnlineBeaconClient.md#bhiddenedtemporary)

#### Defined in

[ue/ue.d.ts:13187](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13187)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bIgnoresOriginShifting](ue_ue.OnlineBeaconClient.md#bignoresoriginshifting)

#### Defined in

[ue/ue.d.ts:13136](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13136)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bIsEditorOnlyActor](ue_ue.OnlineBeaconClient.md#biseditoronlyactor)

#### Defined in

[ue/ue.d.ts:13138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13138)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bIsEditorPreviewActor](ue_ue.OnlineBeaconClient.md#biseditorpreviewactor)

#### Defined in

[ue/ue.d.ts:13179](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13179)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bListedInSceneOutliner](ue_ue.OnlineBeaconClient.md#blistedinsceneoutliner)

#### Defined in

[ue/ue.d.ts:13185](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13185)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bLockLocation](ue_ue.OnlineBeaconClient.md#blocklocation)

#### Defined in

[ue/ue.d.ts:13182](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13182)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bNetLoadOnClient](ue_ue.OnlineBeaconClient.md#bnetloadonclient)

#### Defined in

[ue/ue.d.ts:13124](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13124)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bNetStartup](ue_ue.OnlineBeaconClient.md#bnetstartup)

#### Defined in

[ue/ue.d.ts:13118](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13118)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bNetTemporary](ue_ue.OnlineBeaconClient.md#bnettemporary)

#### Defined in

[ue/ue.d.ts:13117](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13117)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bNetUseOwnerRelevancy](ue_ue.OnlineBeaconClient.md#bnetuseownerrelevancy)

#### Defined in

[ue/ue.d.ts:13125](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13125)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bOnlyRelevantToOwner](ue_ue.OnlineBeaconClient.md#bonlyrelevanttoowner)

#### Defined in

[ue/ue.d.ts:13119](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13119)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bOptimizeBPComponentData](ue_ue.OnlineBeaconClient.md#boptimizebpcomponentdata)

#### Defined in

[ue/ue.d.ts:13186](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13186)

___

### bPendingReservationSent

• **bPendingReservationSent**: `boolean`

#### Defined in

[ue/ue.d.ts:56861](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56861)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bRelevantForLevelBounds](ue_ue.OnlineBeaconClient.md#brelevantforlevelbounds)

#### Defined in

[ue/ue.d.ts:13127](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13127)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bRelevantForNetworkReplays](ue_ue.OnlineBeaconClient.md#brelevantfornetworkreplays)

#### Defined in

[ue/ue.d.ts:13126](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13126)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bReplayRewindable](ue_ue.OnlineBeaconClient.md#breplayrewindable)

#### Defined in

[ue/ue.d.ts:13128](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13128)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bReplicateMovement](ue_ue.OnlineBeaconClient.md#breplicatemovement)

#### Defined in

[ue/ue.d.ts:13121](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13121)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bReplicates](ue_ue.OnlineBeaconClient.md#breplicates)

#### Defined in

[ue/ue.d.ts:13140](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13140)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[bTearOff](ue_ue.OnlineBeaconClient.md#btearoff)

#### Defined in

[ue/ue.d.ts:13122](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13122)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[AddComponent](ue_ue.OnlineBeaconClient.md#addcomponent)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[AddTickPrerequisiteActor](ue_ue.OnlineBeaconClient.md#addtickprerequisiteactor)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[AddTickPrerequisiteComponent](ue_ue.OnlineBeaconClient.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13210](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13210)

___

### ClientCancelReservationResponse

▸ **ClientCancelReservationResponse**(`ReservationResponse`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ReservationResponse` | [`EPartyReservationResult`](../enums/ue_ue.EPartyReservationResult.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:56863](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56863)

___

### ClientOnConnected

▸ **ClientOnConnected**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ClientOnConnected](ue_ue.OnlineBeaconClient.md#clientonconnected)

#### Defined in

[ue/ue.d.ts:54199](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54199)

___

### ClientReservationResponse

▸ **ClientReservationResponse**(`ReservationResponse`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ReservationResponse` | [`EPartyReservationResult`](../enums/ue_ue.EPartyReservationResult.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:56864](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56864)

___

### ClientSendReservationFull

▸ **ClientSendReservationFull**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:56865](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56865)

___

### ClientSendReservationUpdates

▸ **ClientSendReservationUpdates**(`NumRemainingReservations`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumRemainingReservations` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:56866](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56866)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[DetachRootComponentFromParent](ue_ue.OnlineBeaconClient.md#detachrootcomponentfromparent)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[DisableInput](ue_ue.OnlineBeaconClient.md#disableinput)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[EnableInput](ue_ue.OnlineBeaconClient.md#enableinput)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ExecuteUbergraph](ue_ue.OnlineBeaconClient.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[FlushNetDormancy](ue_ue.OnlineBeaconClient.md#flushnetdormancy)

#### Defined in

[ue/ue.d.ts:13214](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13214)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ForceNetUpdate](ue_ue.OnlineBeaconClient.md#forcenetupdate)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorBounds](ue_ue.OnlineBeaconClient.md#getactorbounds)

#### Defined in

[ue/ue.d.ts:13216](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13216)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorEnableCollision](ue_ue.OnlineBeaconClient.md#getactorenablecollision)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorEyesViewPoint](ue_ue.OnlineBeaconClient.md#getactoreyesviewpoint)

#### Defined in

[ue/ue.d.ts:13218](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13218)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorForwardVector](ue_ue.OnlineBeaconClient.md#getactorforwardvector)

#### Defined in

[ue/ue.d.ts:13219](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13219)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorLabel](ue_ue.OnlineBeaconClient.md#getactorlabel)

#### Defined in

[ue/ue.d.ts:13220](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13220)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorRelativeScale3D](ue_ue.OnlineBeaconClient.md#getactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13221](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13221)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorRightVector](ue_ue.OnlineBeaconClient.md#getactorrightvector)

#### Defined in

[ue/ue.d.ts:13222](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13222)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorScale3D](ue_ue.OnlineBeaconClient.md#getactorscale3d)

#### Defined in

[ue/ue.d.ts:13223](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13223)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorTickInterval](ue_ue.OnlineBeaconClient.md#getactortickinterval)

#### Defined in

[ue/ue.d.ts:13224](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13224)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorTimeDilation](ue_ue.OnlineBeaconClient.md#getactortimedilation)

#### Defined in

[ue/ue.d.ts:13225](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13225)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetActorUpVector](ue_ue.OnlineBeaconClient.md#getactorupvector)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetAllChildActors](ue_ue.OnlineBeaconClient.md#getallchildactors)

#### Defined in

[ue/ue.d.ts:13227](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13227)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetAttachParentActor](ue_ue.OnlineBeaconClient.md#getattachparentactor)

#### Defined in

[ue/ue.d.ts:13229](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13229)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetAttachParentSocketName](ue_ue.OnlineBeaconClient.md#getattachparentsocketname)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetAttachedActors](ue_ue.OnlineBeaconClient.md#getattachedactors)

#### Defined in

[ue/ue.d.ts:13228](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13228)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetClass](ue_ue.OnlineBeaconClient.md#getclass)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetComponentByClass](ue_ue.OnlineBeaconClient.md#getcomponentbyclass)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetComponentsByInterface](ue_ue.OnlineBeaconClient.md#getcomponentsbyinterface)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetComponentsByTag](ue_ue.OnlineBeaconClient.md#getcomponentsbytag)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetDistanceTo](ue_ue.OnlineBeaconClient.md#getdistanceto)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetDotProductTo](ue_ue.OnlineBeaconClient.md#getdotproductto)

#### Defined in

[ue/ue.d.ts:13235](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13235)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetFolderPath](ue_ue.OnlineBeaconClient.md#getfolderpath)

#### Defined in

[ue/ue.d.ts:13236](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13236)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetGameTimeSinceCreation](ue_ue.OnlineBeaconClient.md#getgametimesincecreation)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetHorizontalDistanceTo](ue_ue.OnlineBeaconClient.md#gethorizontaldistanceto)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetHorizontalDotProductTo](ue_ue.OnlineBeaconClient.md#gethorizontaldotproductto)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetInputAxisKeyValue](ue_ue.OnlineBeaconClient.md#getinputaxiskeyvalue)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetInputAxisValue](ue_ue.OnlineBeaconClient.md#getinputaxisvalue)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetInputVectorAxisValue](ue_ue.OnlineBeaconClient.md#getinputvectoraxisvalue)

#### Defined in

[ue/ue.d.ts:13242](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13242)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetInstigator](ue_ue.OnlineBeaconClient.md#getinstigator)

#### Defined in

[ue/ue.d.ts:13243](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13243)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetInstigatorController](ue_ue.OnlineBeaconClient.md#getinstigatorcontroller)

#### Defined in

[ue/ue.d.ts:13244](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13244)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetLifeSpan](ue_ue.OnlineBeaconClient.md#getlifespan)

#### Defined in

[ue/ue.d.ts:13245](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13245)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetLocalRole](ue_ue.OnlineBeaconClient.md#getlocalrole)

#### Defined in

[ue/ue.d.ts:13246](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13246)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetName](ue_ue.OnlineBeaconClient.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetOuter](ue_ue.OnlineBeaconClient.md#getouter)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetOverlappingActors](ue_ue.OnlineBeaconClient.md#getoverlappingactors)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetOverlappingComponents](ue_ue.OnlineBeaconClient.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:13248](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13248)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetOwner](ue_ue.OnlineBeaconClient.md#getowner)

#### Defined in

[ue/ue.d.ts:13249](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13249)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetParentActor](ue_ue.OnlineBeaconClient.md#getparentactor)

#### Defined in

[ue/ue.d.ts:13250](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13250)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetParentComponent](ue_ue.OnlineBeaconClient.md#getparentcomponent)

#### Defined in

[ue/ue.d.ts:13251](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13251)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetRemoteRole](ue_ue.OnlineBeaconClient.md#getremoterole)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetSquaredDistanceTo](ue_ue.OnlineBeaconClient.md#getsquareddistanceto)

#### Defined in

[ue/ue.d.ts:13253](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13253)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetTickableWhenPaused](ue_ue.OnlineBeaconClient.md#gettickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13254](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13254)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetTransform](ue_ue.OnlineBeaconClient.md#gettransform)

#### Defined in

[ue/ue.d.ts:13255](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13255)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetVelocity](ue_ue.OnlineBeaconClient.md#getvelocity)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetVerticalDistanceTo](ue_ue.OnlineBeaconClient.md#getverticaldistanceto)

#### Defined in

[ue/ue.d.ts:13257](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13257)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[GetWorld](ue_ue.OnlineBeaconClient.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[HasAuthority](ue_ue.OnlineBeaconClient.md#hasauthority)

#### Defined in

[ue/ue.d.ts:13258](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13258)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsActorBeingDestroyed](ue_ue.OnlineBeaconClient.md#isactorbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13259](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13259)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsActorTickEnabled](ue_ue.OnlineBeaconClient.md#isactortickenabled)

#### Defined in

[ue/ue.d.ts:13260](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13260)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsChildActor](ue_ue.OnlineBeaconClient.md#ischildactor)

#### Defined in

[ue/ue.d.ts:13261](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13261)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsEditable](ue_ue.OnlineBeaconClient.md#iseditable)

#### Defined in

[ue/ue.d.ts:13262](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13262)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsHiddenEd](ue_ue.OnlineBeaconClient.md#ishiddened)

#### Defined in

[ue/ue.d.ts:13263](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13263)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsHiddenEdAtStartup](ue_ue.OnlineBeaconClient.md#ishiddenedatstartup)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsOverlappingActor](ue_ue.OnlineBeaconClient.md#isoverlappingactor)

#### Defined in

[ue/ue.d.ts:13265](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13265)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsSelectable](ue_ue.OnlineBeaconClient.md#isselectable)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[IsTemporarilyHiddenInEditor](ue_ue.OnlineBeaconClient.md#istemporarilyhiddenineditor)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AddActorLocalOffset](ue_ue.OnlineBeaconClient.md#k2_addactorlocaloffset)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AddActorLocalRotation](ue_ue.OnlineBeaconClient.md#k2_addactorlocalrotation)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AddActorLocalTransform](ue_ue.OnlineBeaconClient.md#k2_addactorlocaltransform)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AddActorWorldOffset](ue_ue.OnlineBeaconClient.md#k2_addactorworldoffset)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AddActorWorldRotation](ue_ue.OnlineBeaconClient.md#k2_addactorworldrotation)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AddActorWorldTransform](ue_ue.OnlineBeaconClient.md#k2_addactorworldtransform)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AttachRootComponentTo](ue_ue.OnlineBeaconClient.md#k2_attachrootcomponentto)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AttachRootComponentToActor](ue_ue.OnlineBeaconClient.md#k2_attachrootcomponenttoactor)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AttachToActor](ue_ue.OnlineBeaconClient.md#k2_attachtoactor)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_AttachToComponent](ue_ue.OnlineBeaconClient.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:13277](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13277)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_DestroyActor](ue_ue.OnlineBeaconClient.md#k2_destroyactor)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_DestroyComponent](ue_ue.OnlineBeaconClient.md#k2_destroycomponent)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_DetachFromActor](ue_ue.OnlineBeaconClient.md#k2_detachfromactor)

#### Defined in

[ue/ue.d.ts:13280](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13280)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_GetActorLocation](ue_ue.OnlineBeaconClient.md#k2_getactorlocation)

#### Defined in

[ue/ue.d.ts:13281](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13281)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_GetActorRotation](ue_ue.OnlineBeaconClient.md#k2_getactorrotation)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_GetComponentsByClass](ue_ue.OnlineBeaconClient.md#k2_getcomponentsbyclass)

#### Defined in

[ue/ue.d.ts:13283](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13283)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_GetRootComponent](ue_ue.OnlineBeaconClient.md#k2_getrootcomponent)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_OnBecomeViewTarget](ue_ue.OnlineBeaconClient.md#k2_onbecomeviewtarget)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_OnEndViewTarget](ue_ue.OnlineBeaconClient.md#k2_onendviewtarget)

#### Defined in

[ue/ue.d.ts:13286](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13286)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_OnReset](ue_ue.OnlineBeaconClient.md#k2_onreset)

#### Defined in

[ue/ue.d.ts:13287](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13287)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_SetActorLocationAndRotation](ue_ue.OnlineBeaconClient.md#k2_setactorlocationandrotation)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_SetActorRelativeLocation](ue_ue.OnlineBeaconClient.md#k2_setactorrelativelocation)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_SetActorRelativeRotation](ue_ue.OnlineBeaconClient.md#k2_setactorrelativerotation)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_SetActorRelativeTransform](ue_ue.OnlineBeaconClient.md#k2_setactorrelativetransform)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_SetActorRotation](ue_ue.OnlineBeaconClient.md#k2_setactorrotation)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_SetActorTransform](ue_ue.OnlineBeaconClient.md#k2_setactortransform)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[K2_TeleportTo](ue_ue.OnlineBeaconClient.md#k2_teleportto)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[MakeMIDForMaterial](ue_ue.OnlineBeaconClient.md#makemidformaterial)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[MakeNoise](ue_ue.OnlineBeaconClient.md#makenoise)

#### Defined in

[ue/ue.d.ts:13297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13297)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnRep_AttachmentReplication](ue_ue.OnlineBeaconClient.md#onrep_attachmentreplication)

#### Defined in

[ue/ue.d.ts:13298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13298)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnRep_Instigator](ue_ue.OnlineBeaconClient.md#onrep_instigator)

#### Defined in

[ue/ue.d.ts:13299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13299)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnRep_Owner](ue_ue.OnlineBeaconClient.md#onrep_owner)

#### Defined in

[ue/ue.d.ts:13300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13300)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnRep_ReplicateMovement](ue_ue.OnlineBeaconClient.md#onrep_replicatemovement)

#### Defined in

[ue/ue.d.ts:13302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13302)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[OnRep_ReplicatedMovement](ue_ue.OnlineBeaconClient.md#onrep_replicatedmovement)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[PrestreamTextures](ue_ue.OnlineBeaconClient.md#prestreamtextures)

#### Defined in

[ue/ue.d.ts:13303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13303)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorBeginCursorOver](ue_ue.OnlineBeaconClient.md#receiveactorbegincursorover)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorBeginOverlap](ue_ue.OnlineBeaconClient.md#receiveactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13305)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorEndCursorOver](ue_ue.OnlineBeaconClient.md#receiveactorendcursorover)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorEndOverlap](ue_ue.OnlineBeaconClient.md#receiveactorendoverlap)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorOnClicked](ue_ue.OnlineBeaconClient.md#receiveactoronclicked)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorOnInputTouchBegin](ue_ue.OnlineBeaconClient.md#receiveactoroninputtouchbegin)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorOnInputTouchEnd](ue_ue.OnlineBeaconClient.md#receiveactoroninputtouchend)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorOnInputTouchEnter](ue_ue.OnlineBeaconClient.md#receiveactoroninputtouchenter)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorOnInputTouchLeave](ue_ue.OnlineBeaconClient.md#receiveactoroninputtouchleave)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveActorOnReleased](ue_ue.OnlineBeaconClient.md#receiveactoronreleased)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveAnyDamage](ue_ue.OnlineBeaconClient.md#receiveanydamage)

#### Defined in

[ue/ue.d.ts:13314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13314)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveBeginPlay](ue_ue.OnlineBeaconClient.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:13315](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13315)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveDestroyed](ue_ue.OnlineBeaconClient.md#receivedestroyed)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveEndPlay](ue_ue.OnlineBeaconClient.md#receiveendplay)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveHit](ue_ue.OnlineBeaconClient.md#receivehit)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceivePointDamage](ue_ue.OnlineBeaconClient.md#receivepointdamage)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveRadialDamage](ue_ue.OnlineBeaconClient.md#receiveradialdamage)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[ReceiveTick](ue_ue.OnlineBeaconClient.md#receivetick)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[RemoveTickPrerequisiteActor](ue_ue.OnlineBeaconClient.md#removetickprerequisiteactor)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[RemoveTickPrerequisiteComponent](ue_ue.OnlineBeaconClient.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13323)

___

### ServerCancelReservationRequest

▸ **ServerCancelReservationRequest**(`PartyLeader`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PartyLeader` | [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:56867](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56867)

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

#### Defined in

[ue/ue.d.ts:56868](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56868)

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

#### Defined in

[ue/ue.d.ts:56869](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56869)

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

#### Defined in

[ue/ue.d.ts:56870](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56870)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetActorHiddenInGame](ue_ue.OnlineBeaconClient.md#setactorhiddeningame)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetActorLabel](ue_ue.OnlineBeaconClient.md#setactorlabel)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetActorRelativeScale3D](ue_ue.OnlineBeaconClient.md#setactorrelativescale3d)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetActorScale3D](ue_ue.OnlineBeaconClient.md#setactorscale3d)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetActorTickEnabled](ue_ue.OnlineBeaconClient.md#setactortickenabled)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetActorTickInterval](ue_ue.OnlineBeaconClient.md#setactortickinterval)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetFolderPath](ue_ue.OnlineBeaconClient.md#setfolderpath)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetIsTemporarilyHiddenInEditor](ue_ue.OnlineBeaconClient.md#setistemporarilyhiddenineditor)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetLifeSpan](ue_ue.OnlineBeaconClient.md#setlifespan)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetNetDormancy](ue_ue.OnlineBeaconClient.md#setnetdormancy)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetOwner](ue_ue.OnlineBeaconClient.md#setowner)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetReplicateMovement](ue_ue.OnlineBeaconClient.md#setreplicatemovement)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetReplicates](ue_ue.OnlineBeaconClient.md#setreplicates)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetTickGroup](ue_ue.OnlineBeaconClient.md#settickgroup)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SetTickableWhenPaused](ue_ue.OnlineBeaconClient.md#settickablewhenpaused)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[SnapRootComponentTo](ue_ue.OnlineBeaconClient.md#snaprootcomponentto)

#### Defined in

[ue/ue.d.ts:13340](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13340)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[TearOff](ue_ue.OnlineBeaconClient.md#tearoff)

#### Defined in

[ue/ue.d.ts:13341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13341)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[UserConstructionScript](ue_ue.OnlineBeaconClient.md#userconstructionscript)

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

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[WasRecentlyRendered](ue_ue.OnlineBeaconClient.md#wasrecentlyrendered)

#### Defined in

[ue/ue.d.ts:13343](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13343)

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

#### Defined in

[ue/ue.d.ts:56872](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56872)

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

#### Defined in

[ue/ue.d.ts:56873](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56873)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[OnlineBeaconClient](ue_ue.OnlineBeaconClient.md).[StaticClass](ue_ue.OnlineBeaconClient.md#staticclass)

#### Defined in

[ue/ue.d.ts:56871](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56871)
