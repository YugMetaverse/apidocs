[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PlayerState

# Class: PlayerState

[ue/ue](../modules/ue_ue.md).PlayerState

## Hierarchy

- [`Info`](ue_ue.Info.md)

  ↳ **`PlayerState`**

## Table of contents

### Constructors

- [constructor](ue_ue.PlayerState.md#constructor)

### Properties

- [ActorLabel](ue_ue.PlayerState.md#actorlabel)
- [AttachmentReplication](ue_ue.PlayerState.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.PlayerState.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.PlayerState.md#blueprintcreatedcomponents)
- [Children](ue_ue.PlayerState.md#children)
- [ControllingMatineeActors](ue_ue.PlayerState.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.PlayerState.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.PlayerState.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [EngineMessageClass](ue_ue.PlayerState.md#enginemessageclass)
- [FolderPath](ue_ue.PlayerState.md#folderpath)
- [GroupActor](ue_ue.PlayerState.md#groupactor)
- [HiddenEditorViews](ue_ue.PlayerState.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.PlayerState.md#initiallifespan)
- [InputComponent](ue_ue.PlayerState.md#inputcomponent)
- [InputPriority](ue_ue.PlayerState.md#inputpriority)
- [InstanceComponents](ue_ue.PlayerState.md#instancecomponents)
- [Instigator](ue_ue.PlayerState.md#instigator)
- [Layers](ue_ue.PlayerState.md#layers)
- [MinNetUpdateFrequency](ue_ue.PlayerState.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.PlayerState.md#netculldistancesquared)
- [NetDormancy](ue_ue.PlayerState.md#netdormancy)
- [NetDriverName](ue_ue.PlayerState.md#netdrivername)
- [NetPriority](ue_ue.PlayerState.md#netpriority)
- [NetTag](ue_ue.PlayerState.md#nettag)
- [NetUpdateFrequency](ue_ue.PlayerState.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.PlayerState.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.PlayerState.md#onactorendoverlap)
- [OnActorHit](ue_ue.PlayerState.md#onactorhit)
- [OnBeginCursorOver](ue_ue.PlayerState.md#onbegincursorover)
- [OnClicked](ue_ue.PlayerState.md#onclicked)
- [OnDestroyed](ue_ue.PlayerState.md#ondestroyed)
- [OnEndCursorOver](ue_ue.PlayerState.md#onendcursorover)
- [OnEndPlay](ue_ue.PlayerState.md#onendplay)
- [OnInputTouchBegin](ue_ue.PlayerState.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.PlayerState.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.PlayerState.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.PlayerState.md#oninputtouchleave)
- [OnReleased](ue_ue.PlayerState.md#onreleased)
- [OnTakeAnyDamage](ue_ue.PlayerState.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.PlayerState.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.PlayerState.md#ontakeradialdamage)
- [Owner](ue_ue.PlayerState.md#owner)
- [ParentComponent](ue_ue.PlayerState.md#parentcomponent)
- [ParentComponentActor](ue_ue.PlayerState.md#parentcomponentactor)
- [PawnPrivate](ue_ue.PlayerState.md#pawnprivate)
- [Ping](ue_ue.PlayerState.md#ping)
- [PivotOffset](ue_ue.PlayerState.md#pivotoffset)
- [PlayerId](ue_ue.PlayerState.md#playerid)
- [PlayerName](ue_ue.PlayerState.md#playername)
- [PlayerNamePrivate](ue_ue.PlayerState.md#playernameprivate)
- [PrimaryActorTick](ue_ue.PlayerState.md#primaryactortick)
- [RemoteRole](ue_ue.PlayerState.md#remoterole)
- [ReplicatedMovement](ue_ue.PlayerState.md#replicatedmovement)
- [Role](ue_ue.PlayerState.md#role)
- [RootComponent](ue_ue.PlayerState.md#rootcomponent)
- [SavedNetworkAddress](ue_ue.PlayerState.md#savednetworkaddress)
- [Score](ue_ue.PlayerState.md#score)
- [SpawnCollisionHandlingMethod](ue_ue.PlayerState.md#spawncollisionhandlingmethod)
- [SpriteComponent](ue_ue.PlayerState.md#spritecomponent)
- [SpriteScale](ue_ue.PlayerState.md#spritescale)
- [StartTime](ue_ue.PlayerState.md#starttime)
- [Tags](ue_ue.PlayerState.md#tags)
- [UniqueId](ue_ue.PlayerState.md#uniqueid)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.PlayerState.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.PlayerState.md#__tid_actor__)
- [\_\_tid\_Info\_\_](ue_ue.PlayerState.md#__tid_info__)
- [\_\_tid\_Object\_\_](ue_ue.PlayerState.md#__tid_object__)
- [\_\_tid\_PlayerState\_\_](ue_ue.PlayerState.md#__tid_playerstate__)
- [bActorEnableCollision](ue_ue.PlayerState.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.PlayerState.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.PlayerState.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.PlayerState.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.PlayerState.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.PlayerState.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.PlayerState.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.PlayerState.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.PlayerState.md#bblockinput)
- [bCanBeDamaged](ue_ue.PlayerState.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.PlayerState.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.PlayerState.md#bcollidewhenplacing)
- [bEditable](ue_ue.PlayerState.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.PlayerState.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.PlayerState.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.PlayerState.md#bfindcameracomponentwhenviewtarget)
- [bFromPreviousLevel](ue_ue.PlayerState.md#bfrompreviouslevel)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.PlayerState.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.PlayerState.md#bhidden)
- [bHiddenEd](ue_ue.PlayerState.md#bhiddened)
- [bHiddenEdLayer](ue_ue.PlayerState.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.PlayerState.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.PlayerState.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.PlayerState.md#bignoresoriginshifting)
- [bIsABot](ue_ue.PlayerState.md#bisabot)
- [bIsEditorOnlyActor](ue_ue.PlayerState.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.PlayerState.md#biseditorpreviewactor)
- [bIsInactive](ue_ue.PlayerState.md#bisinactive)
- [bIsSpectator](ue_ue.PlayerState.md#bisspectator)
- [bListedInSceneOutliner](ue_ue.PlayerState.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.PlayerState.md#blocklocation)
- [bNetLoadOnClient](ue_ue.PlayerState.md#bnetloadonclient)
- [bNetStartup](ue_ue.PlayerState.md#bnetstartup)
- [bNetTemporary](ue_ue.PlayerState.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.PlayerState.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.PlayerState.md#bonlyrelevanttoowner)
- [bOnlySpectator](ue_ue.PlayerState.md#bonlyspectator)
- [bOptimizeBPComponentData](ue_ue.PlayerState.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.PlayerState.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.PlayerState.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.PlayerState.md#breplayrewindable)
- [bReplicateMovement](ue_ue.PlayerState.md#breplicatemovement)
- [bReplicates](ue_ue.PlayerState.md#breplicates)
- [bShouldUpdateReplicatedPing](ue_ue.PlayerState.md#bshouldupdatereplicatedping)
- [bTearOff](ue_ue.PlayerState.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.PlayerState.md#actorhastag)
- [AddComponent](ue_ue.PlayerState.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.PlayerState.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PlayerState.md#addtickprerequisitecomponent)
- [CreateDefaultSubobject](ue_ue.PlayerState.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.PlayerState.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.PlayerState.md#disableinput)
- [EnableInput](ue_ue.PlayerState.md#enableinput)
- [ExecuteUbergraph](ue_ue.PlayerState.md#executeubergraph)
- [FlushNetDormancy](ue_ue.PlayerState.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.PlayerState.md#forcenetupdate)
- [GetActorBounds](ue_ue.PlayerState.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.PlayerState.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.PlayerState.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.PlayerState.md#getactorforwardvector)
- [GetActorLabel](ue_ue.PlayerState.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.PlayerState.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.PlayerState.md#getactorrightvector)
- [GetActorScale3D](ue_ue.PlayerState.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.PlayerState.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.PlayerState.md#getactortimedilation)
- [GetActorUpVector](ue_ue.PlayerState.md#getactorupvector)
- [GetAllChildActors](ue_ue.PlayerState.md#getallchildactors)
- [GetAttachParentActor](ue_ue.PlayerState.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.PlayerState.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.PlayerState.md#getattachedactors)
- [GetClass](ue_ue.PlayerState.md#getclass)
- [GetComponentByClass](ue_ue.PlayerState.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.PlayerState.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.PlayerState.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.PlayerState.md#getdistanceto)
- [GetDotProductTo](ue_ue.PlayerState.md#getdotproductto)
- [GetFolderPath](ue_ue.PlayerState.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.PlayerState.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.PlayerState.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.PlayerState.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.PlayerState.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.PlayerState.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.PlayerState.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.PlayerState.md#getinstigator)
- [GetInstigatorController](ue_ue.PlayerState.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.PlayerState.md#getlifespan)
- [GetLocalRole](ue_ue.PlayerState.md#getlocalrole)
- [GetName](ue_ue.PlayerState.md#getname)
- [GetOuter](ue_ue.PlayerState.md#getouter)
- [GetOverlappingActors](ue_ue.PlayerState.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.PlayerState.md#getoverlappingcomponents)
- [GetOwner](ue_ue.PlayerState.md#getowner)
- [GetParentActor](ue_ue.PlayerState.md#getparentactor)
- [GetParentComponent](ue_ue.PlayerState.md#getparentcomponent)
- [GetPlayerName](ue_ue.PlayerState.md#getplayername)
- [GetRemoteRole](ue_ue.PlayerState.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.PlayerState.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.PlayerState.md#gettickablewhenpaused)
- [GetTransform](ue_ue.PlayerState.md#gettransform)
- [GetVelocity](ue_ue.PlayerState.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.PlayerState.md#getverticaldistanceto)
- [GetWorld](ue_ue.PlayerState.md#getworld)
- [HasAuthority](ue_ue.PlayerState.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.PlayerState.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.PlayerState.md#isactortickenabled)
- [IsChildActor](ue_ue.PlayerState.md#ischildactor)
- [IsEditable](ue_ue.PlayerState.md#iseditable)
- [IsHiddenEd](ue_ue.PlayerState.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.PlayerState.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.PlayerState.md#isoverlappingactor)
- [IsSelectable](ue_ue.PlayerState.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.PlayerState.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.PlayerState.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.PlayerState.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.PlayerState.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.PlayerState.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.PlayerState.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.PlayerState.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.PlayerState.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.PlayerState.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.PlayerState.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.PlayerState.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.PlayerState.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.PlayerState.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.PlayerState.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.PlayerState.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.PlayerState.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.PlayerState.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.PlayerState.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.PlayerState.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.PlayerState.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.PlayerState.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.PlayerState.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.PlayerState.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.PlayerState.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.PlayerState.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.PlayerState.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.PlayerState.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.PlayerState.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.PlayerState.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.PlayerState.md#makemidformaterial)
- [MakeNoise](ue_ue.PlayerState.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.PlayerState.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.PlayerState.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.PlayerState.md#onrep_owner)
- [OnRep\_PlayerId](ue_ue.PlayerState.md#onrep_playerid)
- [OnRep\_PlayerName](ue_ue.PlayerState.md#onrep_playername)
- [OnRep\_ReplicateMovement](ue_ue.PlayerState.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.PlayerState.md#onrep_replicatedmovement)
- [OnRep\_Score](ue_ue.PlayerState.md#onrep_score)
- [OnRep\_UniqueId](ue_ue.PlayerState.md#onrep_uniqueid)
- [OnRep\_bIsInactive](ue_ue.PlayerState.md#onrep_bisinactive)
- [PrestreamTextures](ue_ue.PlayerState.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.PlayerState.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.PlayerState.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.PlayerState.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.PlayerState.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.PlayerState.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.PlayerState.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.PlayerState.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.PlayerState.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.PlayerState.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.PlayerState.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.PlayerState.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.PlayerState.md#receivebeginplay)
- [ReceiveCopyProperties](ue_ue.PlayerState.md#receivecopyproperties)
- [ReceiveDestroyed](ue_ue.PlayerState.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.PlayerState.md#receiveendplay)
- [ReceiveHit](ue_ue.PlayerState.md#receivehit)
- [ReceiveOverrideWith](ue_ue.PlayerState.md#receiveoverridewith)
- [ReceivePointDamage](ue_ue.PlayerState.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.PlayerState.md#receiveradialdamage)
- [ReceiveTick](ue_ue.PlayerState.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.PlayerState.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PlayerState.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.PlayerState.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.PlayerState.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.PlayerState.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.PlayerState.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.PlayerState.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.PlayerState.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.PlayerState.md#setactortickinterval)
- [SetFolderPath](ue_ue.PlayerState.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.PlayerState.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.PlayerState.md#setlifespan)
- [SetNetDormancy](ue_ue.PlayerState.md#setnetdormancy)
- [SetOwner](ue_ue.PlayerState.md#setowner)
- [SetReplicateMovement](ue_ue.PlayerState.md#setreplicatemovement)
- [SetReplicates](ue_ue.PlayerState.md#setreplicates)
- [SetTickGroup](ue_ue.PlayerState.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PlayerState.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.PlayerState.md#snaprootcomponentto)
- [TearOff](ue_ue.PlayerState.md#tearoff)
- [UserConstructionScript](ue_ue.PlayerState.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.PlayerState.md#wasrecentlyrendered)
- [Find](ue_ue.PlayerState.md#find)
- [Load](ue_ue.PlayerState.md#load)
- [StaticClass](ue_ue.PlayerState.md#staticclass)

## Constructors

### constructor

• **new PlayerState**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Info](ue_ue.Info.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.Info.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### EngineMessageClass

• **EngineMessageClass**: [`Class`](ue_ue.Class.md)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[Info](ue_ue.Info.md).[FolderPath](ue_ue.Info.md#folderpath)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Info](ue_ue.Info.md).[GroupActor](ue_ue.Info.md#groupactor)

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

### PawnPrivate

• **PawnPrivate**: [`Pawn`](ue_ue.Pawn.md)

___

### Ping

• **Ping**: `number`

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Info](ue_ue.Info.md).[PivotOffset](ue_ue.Info.md#pivotoffset)

___

### PlayerId

• **PlayerId**: `number`

___

### PlayerName

• **PlayerName**: `string`

___

### PlayerNamePrivate

• **PlayerNamePrivate**: `string`

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

### SavedNetworkAddress

• **SavedNetworkAddress**: `string`

___

### Score

• **Score**: `number`

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[Info](ue_ue.Info.md).[SpawnCollisionHandlingMethod](ue_ue.Info.md#spawncollisionhandlingmethod)

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

### StartTime

• **StartTime**: `number`

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Info](ue_ue.Info.md).[Tags](ue_ue.Info.md#tags)

___

### UniqueId

• **UniqueId**: [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md)

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

### \_\_tid\_PlayerState\_\_

• **\_\_tid\_PlayerState\_\_**: `boolean`

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

### bFromPreviousLevel

• **bFromPreviousLevel**: `boolean`

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

### bIsABot

• **bIsABot**: `boolean`

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

### bIsInactive

• **bIsInactive**: `boolean`

___

### bIsSpectator

• **bIsSpectator**: `boolean`

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

### bOnlySpectator

• **bOnlySpectator**: `boolean`

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bOptimizeBPComponentData](ue_ue.Info.md#boptimizebpcomponentdata)

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

### bShouldUpdateReplicatedPing

• **bShouldUpdateReplicatedPing**: `boolean`

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[Info](ue_ue.Info.md).[bTearOff](ue_ue.Info.md#btearoff)

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

### GetPlayerName

▸ **GetPlayerName**(): `string`

#### Returns

`string`

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

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Info](ue_ue.Info.md).[HasAuthority](ue_ue.Info.md#hasauthority)

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

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[Info](ue_ue.Info.md).[K2_OnReset](ue_ue.Info.md#k2_onreset)

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

### OnRep\_PlayerId

▸ **OnRep_PlayerId**(): `void`

#### Returns

`void`

___

### OnRep\_PlayerName

▸ **OnRep_PlayerName**(): `void`

#### Returns

`void`

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

### OnRep\_Score

▸ **OnRep_Score**(): `void`

#### Returns

`void`

___

### OnRep\_UniqueId

▸ **OnRep_UniqueId**(): `void`

#### Returns

`void`

___

### OnRep\_bIsInactive

▸ **OnRep_bIsInactive**(): `void`

#### Returns

`void`

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

### ReceiveCopyProperties

▸ **ReceiveCopyProperties**(`NewPlayerState`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlayerState` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerState`](ue_ue.PlayerState.md)\> |

#### Returns

`void`

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

### ReceiveOverrideWith

▸ **ReceiveOverrideWith**(`OldPlayerState`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OldPlayerState` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerState`](ue_ue.PlayerState.md)\> |

#### Returns

`void`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PlayerState`](ue_ue.PlayerState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PlayerState`](ue_ue.PlayerState.md)

#### Overrides

[Info](ue_ue.Info.md).[Find](ue_ue.Info.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PlayerState`](ue_ue.PlayerState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PlayerState`](ue_ue.PlayerState.md)

#### Overrides

[Info](ue_ue.Info.md).[Load](ue_ue.Info.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Info](ue_ue.Info.md).[StaticClass](ue_ue.Info.md#staticclass)
