[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Controller

# Class: Controller

[ue/ue](../modules/ue_ue.md).Controller

## Hierarchy

- [`Actor`](ue_ue.Actor.md)

  ↳ **`Controller`**

  ↳↳ [`PlayerController`](ue_ue.PlayerController.md)

  ↳↳ [`AIController`](ue_ue.AIController.md)

## Table of contents

### Constructors

- [constructor](ue_ue.Controller.md#constructor)

### Properties

- [ActorLabel](ue_ue.Controller.md#actorlabel)
- [AttachmentReplication](ue_ue.Controller.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.Controller.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.Controller.md#blueprintcreatedcomponents)
- [Character](ue_ue.Controller.md#character)
- [Children](ue_ue.Controller.md#children)
- [ControlRotation](ue_ue.Controller.md#controlrotation)
- [ControllingMatineeActors](ue_ue.Controller.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.Controller.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.Controller.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.Controller.md#folderpath)
- [GroupActor](ue_ue.Controller.md#groupactor)
- [HiddenEditorViews](ue_ue.Controller.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.Controller.md#initiallifespan)
- [InputComponent](ue_ue.Controller.md#inputcomponent)
- [InputPriority](ue_ue.Controller.md#inputpriority)
- [InstanceComponents](ue_ue.Controller.md#instancecomponents)
- [Instigator](ue_ue.Controller.md#instigator)
- [Layers](ue_ue.Controller.md#layers)
- [MinNetUpdateFrequency](ue_ue.Controller.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.Controller.md#netculldistancesquared)
- [NetDormancy](ue_ue.Controller.md#netdormancy)
- [NetDriverName](ue_ue.Controller.md#netdrivername)
- [NetPriority](ue_ue.Controller.md#netpriority)
- [NetTag](ue_ue.Controller.md#nettag)
- [NetUpdateFrequency](ue_ue.Controller.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.Controller.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.Controller.md#onactorendoverlap)
- [OnActorHit](ue_ue.Controller.md#onactorhit)
- [OnBeginCursorOver](ue_ue.Controller.md#onbegincursorover)
- [OnClicked](ue_ue.Controller.md#onclicked)
- [OnDestroyed](ue_ue.Controller.md#ondestroyed)
- [OnEndCursorOver](ue_ue.Controller.md#onendcursorover)
- [OnEndPlay](ue_ue.Controller.md#onendplay)
- [OnInputTouchBegin](ue_ue.Controller.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.Controller.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.Controller.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.Controller.md#oninputtouchleave)
- [OnInstigatedAnyDamage](ue_ue.Controller.md#oninstigatedanydamage)
- [OnReleased](ue_ue.Controller.md#onreleased)
- [OnTakeAnyDamage](ue_ue.Controller.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.Controller.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.Controller.md#ontakeradialdamage)
- [Owner](ue_ue.Controller.md#owner)
- [ParentComponent](ue_ue.Controller.md#parentcomponent)
- [ParentComponentActor](ue_ue.Controller.md#parentcomponentactor)
- [Pawn](ue_ue.Controller.md#pawn)
- [PivotOffset](ue_ue.Controller.md#pivotoffset)
- [PlayerState](ue_ue.Controller.md#playerstate)
- [PrimaryActorTick](ue_ue.Controller.md#primaryactortick)
- [RemoteRole](ue_ue.Controller.md#remoterole)
- [ReplicatedMovement](ue_ue.Controller.md#replicatedmovement)
- [Role](ue_ue.Controller.md#role)
- [RootComponent](ue_ue.Controller.md#rootcomponent)
- [SpawnCollisionHandlingMethod](ue_ue.Controller.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.Controller.md#spritescale)
- [StateName](ue_ue.Controller.md#statename)
- [Tags](ue_ue.Controller.md#tags)
- [TransformComponent](ue_ue.Controller.md#transformcomponent)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.Controller.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.Controller.md#__tid_actor__)
- [\_\_tid\_Controller\_\_](ue_ue.Controller.md#__tid_controller__)
- [\_\_tid\_Object\_\_](ue_ue.Controller.md#__tid_object__)
- [bActorEnableCollision](ue_ue.Controller.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.Controller.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.Controller.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.Controller.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.Controller.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.Controller.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.Controller.md#balwaysrelevant)
- [bAttachToPawn](ue_ue.Controller.md#battachtopawn)
- [bAutoDestroyWhenFinished](ue_ue.Controller.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.Controller.md#bblockinput)
- [bCanBeDamaged](ue_ue.Controller.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.Controller.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.Controller.md#bcollidewhenplacing)
- [bEditable](ue_ue.Controller.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.Controller.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.Controller.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.Controller.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.Controller.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.Controller.md#bhidden)
- [bHiddenEd](ue_ue.Controller.md#bhiddened)
- [bHiddenEdLayer](ue_ue.Controller.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.Controller.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.Controller.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.Controller.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.Controller.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.Controller.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.Controller.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.Controller.md#blocklocation)
- [bNetLoadOnClient](ue_ue.Controller.md#bnetloadonclient)
- [bNetStartup](ue_ue.Controller.md#bnetstartup)
- [bNetTemporary](ue_ue.Controller.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.Controller.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.Controller.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.Controller.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.Controller.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.Controller.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.Controller.md#breplayrewindable)
- [bReplicateMovement](ue_ue.Controller.md#breplicatemovement)
- [bReplicates](ue_ue.Controller.md#breplicates)
- [bTearOff](ue_ue.Controller.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.Controller.md#actorhastag)
- [AddComponent](ue_ue.Controller.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.Controller.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.Controller.md#addtickprerequisitecomponent)
- [CastToPlayerController](ue_ue.Controller.md#casttoplayercontroller)
- [ClientSetLocation](ue_ue.Controller.md#clientsetlocation)
- [ClientSetRotation](ue_ue.Controller.md#clientsetrotation)
- [CreateDefaultSubobject](ue_ue.Controller.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.Controller.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.Controller.md#disableinput)
- [EnableInput](ue_ue.Controller.md#enableinput)
- [ExecuteUbergraph](ue_ue.Controller.md#executeubergraph)
- [FlushNetDormancy](ue_ue.Controller.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.Controller.md#forcenetupdate)
- [GetActorBounds](ue_ue.Controller.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.Controller.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.Controller.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.Controller.md#getactorforwardvector)
- [GetActorLabel](ue_ue.Controller.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.Controller.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.Controller.md#getactorrightvector)
- [GetActorScale3D](ue_ue.Controller.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.Controller.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.Controller.md#getactortimedilation)
- [GetActorUpVector](ue_ue.Controller.md#getactorupvector)
- [GetAllChildActors](ue_ue.Controller.md#getallchildactors)
- [GetAttachParentActor](ue_ue.Controller.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.Controller.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.Controller.md#getattachedactors)
- [GetClass](ue_ue.Controller.md#getclass)
- [GetComponentByClass](ue_ue.Controller.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.Controller.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.Controller.md#getcomponentsbytag)
- [GetControlRotation](ue_ue.Controller.md#getcontrolrotation)
- [GetDesiredRotation](ue_ue.Controller.md#getdesiredrotation)
- [GetDistanceTo](ue_ue.Controller.md#getdistanceto)
- [GetDotProductTo](ue_ue.Controller.md#getdotproductto)
- [GetFolderPath](ue_ue.Controller.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.Controller.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.Controller.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.Controller.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.Controller.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.Controller.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.Controller.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.Controller.md#getinstigator)
- [GetInstigatorController](ue_ue.Controller.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.Controller.md#getlifespan)
- [GetLocalRole](ue_ue.Controller.md#getlocalrole)
- [GetName](ue_ue.Controller.md#getname)
- [GetOuter](ue_ue.Controller.md#getouter)
- [GetOverlappingActors](ue_ue.Controller.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.Controller.md#getoverlappingcomponents)
- [GetOwner](ue_ue.Controller.md#getowner)
- [GetParentActor](ue_ue.Controller.md#getparentactor)
- [GetParentComponent](ue_ue.Controller.md#getparentcomponent)
- [GetRemoteRole](ue_ue.Controller.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.Controller.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.Controller.md#gettickablewhenpaused)
- [GetTransform](ue_ue.Controller.md#gettransform)
- [GetVelocity](ue_ue.Controller.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.Controller.md#getverticaldistanceto)
- [GetViewTarget](ue_ue.Controller.md#getviewtarget)
- [GetWorld](ue_ue.Controller.md#getworld)
- [HasAuthority](ue_ue.Controller.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.Controller.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.Controller.md#isactortickenabled)
- [IsChildActor](ue_ue.Controller.md#ischildactor)
- [IsEditable](ue_ue.Controller.md#iseditable)
- [IsHiddenEd](ue_ue.Controller.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.Controller.md#ishiddenedatstartup)
- [IsLocalController](ue_ue.Controller.md#islocalcontroller)
- [IsLocalPlayerController](ue_ue.Controller.md#islocalplayercontroller)
- [IsLookInputIgnored](ue_ue.Controller.md#islookinputignored)
- [IsMoveInputIgnored](ue_ue.Controller.md#ismoveinputignored)
- [IsOverlappingActor](ue_ue.Controller.md#isoverlappingactor)
- [IsPlayerController](ue_ue.Controller.md#isplayercontroller)
- [IsSelectable](ue_ue.Controller.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.Controller.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.Controller.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.Controller.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.Controller.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.Controller.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.Controller.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.Controller.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.Controller.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.Controller.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.Controller.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.Controller.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.Controller.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.Controller.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.Controller.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.Controller.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.Controller.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.Controller.md#k2_getcomponentsbyclass)
- [K2\_GetPawn](ue_ue.Controller.md#k2_getpawn)
- [K2\_GetRootComponent](ue_ue.Controller.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.Controller.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.Controller.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.Controller.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.Controller.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.Controller.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.Controller.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.Controller.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.Controller.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.Controller.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.Controller.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.Controller.md#k2_teleportto)
- [LineOfSightTo](ue_ue.Controller.md#lineofsightto)
- [MakeMIDForMaterial](ue_ue.Controller.md#makemidformaterial)
- [MakeNoise](ue_ue.Controller.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.Controller.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.Controller.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.Controller.md#onrep_owner)
- [OnRep\_Pawn](ue_ue.Controller.md#onrep_pawn)
- [OnRep\_PlayerState](ue_ue.Controller.md#onrep_playerstate)
- [OnRep\_ReplicateMovement](ue_ue.Controller.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.Controller.md#onrep_replicatedmovement)
- [Possess](ue_ue.Controller.md#possess)
- [PrestreamTextures](ue_ue.Controller.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.Controller.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.Controller.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.Controller.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.Controller.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.Controller.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.Controller.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.Controller.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.Controller.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.Controller.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.Controller.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.Controller.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.Controller.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.Controller.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.Controller.md#receiveendplay)
- [ReceiveHit](ue_ue.Controller.md#receivehit)
- [ReceiveInstigatedAnyDamage](ue_ue.Controller.md#receiveinstigatedanydamage)
- [ReceivePointDamage](ue_ue.Controller.md#receivepointdamage)
- [ReceivePossess](ue_ue.Controller.md#receivepossess)
- [ReceiveRadialDamage](ue_ue.Controller.md#receiveradialdamage)
- [ReceiveTick](ue_ue.Controller.md#receivetick)
- [ReceiveUnPossess](ue_ue.Controller.md#receiveunpossess)
- [RemoveTickPrerequisiteActor](ue_ue.Controller.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.Controller.md#removetickprerequisitecomponent)
- [ResetIgnoreInputFlags](ue_ue.Controller.md#resetignoreinputflags)
- [ResetIgnoreLookInput](ue_ue.Controller.md#resetignorelookinput)
- [ResetIgnoreMoveInput](ue_ue.Controller.md#resetignoremoveinput)
- [SetActorEnableCollision](ue_ue.Controller.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.Controller.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.Controller.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.Controller.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.Controller.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.Controller.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.Controller.md#setactortickinterval)
- [SetControlRotation](ue_ue.Controller.md#setcontrolrotation)
- [SetFolderPath](ue_ue.Controller.md#setfolderpath)
- [SetIgnoreLookInput](ue_ue.Controller.md#setignorelookinput)
- [SetIgnoreMoveInput](ue_ue.Controller.md#setignoremoveinput)
- [SetInitialLocationAndRotation](ue_ue.Controller.md#setinitiallocationandrotation)
- [SetIsTemporarilyHiddenInEditor](ue_ue.Controller.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.Controller.md#setlifespan)
- [SetNetDormancy](ue_ue.Controller.md#setnetdormancy)
- [SetOwner](ue_ue.Controller.md#setowner)
- [SetReplicateMovement](ue_ue.Controller.md#setreplicatemovement)
- [SetReplicates](ue_ue.Controller.md#setreplicates)
- [SetTickGroup](ue_ue.Controller.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.Controller.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.Controller.md#snaprootcomponentto)
- [StopMovement](ue_ue.Controller.md#stopmovement)
- [TearOff](ue_ue.Controller.md#tearoff)
- [UnPossess](ue_ue.Controller.md#unpossess)
- [UserConstructionScript](ue_ue.Controller.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.Controller.md#wasrecentlyrendered)
- [Find](ue_ue.Controller.md#find)
- [Load](ue_ue.Controller.md#load)
- [StaticClass](ue_ue.Controller.md#staticclass)

## Constructors

### constructor

• **new Controller**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Actor](ue_ue.Actor.md).[constructor](ue_ue.Actor.md#constructor)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[Actor](ue_ue.Actor.md).[ActorLabel](ue_ue.Actor.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[AttachmentReplication](ue_ue.Actor.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[AutoReceiveInput](ue_ue.Actor.md#autoreceiveinput)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Actor](ue_ue.Actor.md).[BlueprintCreatedComponents](ue_ue.Actor.md#blueprintcreatedcomponents)

___

### Character

• **Character**: [`Character`](ue_ue.Character.md)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Actor](ue_ue.Actor.md).[Children](ue_ue.Actor.md#children)

___

### ControlRotation

• **ControlRotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[Actor](ue_ue.Actor.md).[ControllingMatineeActors](ue_ue.Actor.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[CustomTimeDilation](ue_ue.Actor.md#customtimedilation)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.Actor.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[Actor](ue_ue.Actor.md).[FolderPath](ue_ue.Actor.md#folderpath)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GroupActor](ue_ue.Actor.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[Actor](ue_ue.Actor.md).[HiddenEditorViews](ue_ue.Actor.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[InitialLifeSpan](ue_ue.Actor.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[InputComponent](ue_ue.Actor.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[InputPriority](ue_ue.Actor.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Actor](ue_ue.Actor.md).[InstanceComponents](ue_ue.Actor.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[Instigator](ue_ue.Actor.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[Layers](ue_ue.Actor.md#layers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[MinNetUpdateFrequency](ue_ue.Actor.md#minnetupdatefrequency)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[NetCullDistanceSquared](ue_ue.Actor.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[NetDormancy](ue_ue.Actor.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[Actor](ue_ue.Actor.md).[NetDriverName](ue_ue.Actor.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[NetPriority](ue_ue.Actor.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[NetTag](ue_ue.Actor.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[NetUpdateFrequency](ue_ue.Actor.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnActorBeginOverlap](ue_ue.Actor.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnActorEndOverlap](ue_ue.Actor.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnActorHit](ue_ue.Actor.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnBeginCursorOver](ue_ue.Actor.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnClicked](ue_ue.Actor.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnDestroyed](ue_ue.Actor.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnEndCursorOver](ue_ue.Actor.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnEndPlay](ue_ue.Actor.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnInputTouchBegin](ue_ue.Actor.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnInputTouchEnd](ue_ue.Actor.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnInputTouchEnter](ue_ue.Actor.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnInputTouchLeave](ue_ue.Actor.md#oninputtouchleave)

___

### OnInstigatedAnyDamage

• **OnInstigatedAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnReleased](ue_ue.Actor.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnTakeAnyDamage](ue_ue.Actor.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnTakePointDamage](ue_ue.Actor.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnTakeRadialDamage](ue_ue.Actor.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[Owner](ue_ue.Actor.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[Actor](ue_ue.Actor.md).[ParentComponent](ue_ue.Actor.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Actor](ue_ue.Actor.md).[ParentComponentActor](ue_ue.Actor.md#parentcomponentactor)

___

### Pawn

• **Pawn**: [`Pawn`](ue_ue.Pawn.md)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[PivotOffset](ue_ue.Actor.md#pivotoffset)

___

### PlayerState

• **PlayerState**: [`PlayerState`](ue_ue.PlayerState.md)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[PrimaryActorTick](ue_ue.Actor.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[RemoteRole](ue_ue.Actor.md#remoterole)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[ReplicatedMovement](ue_ue.Actor.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[Role](ue_ue.Actor.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[RootComponent](ue_ue.Actor.md#rootcomponent)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[SpawnCollisionHandlingMethod](ue_ue.Actor.md#spawncollisionhandlingmethod)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[SpriteScale](ue_ue.Actor.md#spritescale)

___

### StateName

• **StateName**: `string`

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[Tags](ue_ue.Actor.md#tags)

___

### TransformComponent

• **TransformComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.Actor.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[__tid_Actor__](ue_ue.Actor.md#__tid_actor__)

___

### \_\_tid\_Controller\_\_

• **\_\_tid\_Controller\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[__tid_Object__](ue_ue.Actor.md#__tid_object__)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bActorEnableCollision](ue_ue.Actor.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bActorIsBeingDestroyed](ue_ue.Actor.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bActorLabelEditable](ue_ue.Actor.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bActorSeamlessTraveled](ue_ue.Actor.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.Actor.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bAllowTickBeforeBeginPlay](ue_ue.Actor.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bAlwaysRelevant](ue_ue.Actor.md#balwaysrelevant)

___

### bAttachToPawn

• **bAttachToPawn**: `boolean`

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bAutoDestroyWhenFinished](ue_ue.Actor.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bBlockInput](ue_ue.Actor.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bCanBeDamaged](ue_ue.Actor.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bCanBeInCluster](ue_ue.Actor.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bCollideWhenPlacing](ue_ue.Actor.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bEditable](ue_ue.Actor.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bEnableAutoLODGeneration](ue_ue.Actor.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bExchangedRoles](ue_ue.Actor.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bFindCameraComponentWhenViewTarget](ue_ue.Actor.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.Actor.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bHidden](ue_ue.Actor.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bHiddenEd](ue_ue.Actor.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bHiddenEdLayer](ue_ue.Actor.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bHiddenEdLevel](ue_ue.Actor.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bHiddenEdTemporary](ue_ue.Actor.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bIgnoresOriginShifting](ue_ue.Actor.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bIsEditorOnlyActor](ue_ue.Actor.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bIsEditorPreviewActor](ue_ue.Actor.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bListedInSceneOutliner](ue_ue.Actor.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bLockLocation](ue_ue.Actor.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bNetLoadOnClient](ue_ue.Actor.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bNetStartup](ue_ue.Actor.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bNetTemporary](ue_ue.Actor.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bNetUseOwnerRelevancy](ue_ue.Actor.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bOnlyRelevantToOwner](ue_ue.Actor.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bOptimizeBPComponentData](ue_ue.Actor.md#boptimizebpcomponentdata)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bRelevantForLevelBounds](ue_ue.Actor.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bRelevantForNetworkReplays](ue_ue.Actor.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bReplayRewindable](ue_ue.Actor.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bReplicateMovement](ue_ue.Actor.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bReplicates](ue_ue.Actor.md#breplicates)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bTearOff](ue_ue.Actor.md#btearoff)

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

[Actor](ue_ue.Actor.md).[ActorHasTag](ue_ue.Actor.md#actorhastag)

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

[Actor](ue_ue.Actor.md).[AddComponent](ue_ue.Actor.md#addcomponent)

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

[Actor](ue_ue.Actor.md).[AddTickPrerequisiteActor](ue_ue.Actor.md#addtickprerequisiteactor)

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

[Actor](ue_ue.Actor.md).[AddTickPrerequisiteComponent](ue_ue.Actor.md#addtickprerequisitecomponent)

___

### CastToPlayerController

▸ **CastToPlayerController**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

___

### ClientSetLocation

▸ **ClientSetLocation**(`NewLocation`, `NewRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

___

### ClientSetRotation

▸ **ClientSetRotation**(`NewRotation`, `bResetCamera`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bResetCamera` | `boolean` |

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

[Actor](ue_ue.Actor.md).[CreateDefaultSubobject](ue_ue.Actor.md#createdefaultsubobject)

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

[Actor](ue_ue.Actor.md).[DetachRootComponentFromParent](ue_ue.Actor.md#detachrootcomponentfromparent)

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

[Actor](ue_ue.Actor.md).[DisableInput](ue_ue.Actor.md#disableinput)

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

[Actor](ue_ue.Actor.md).[EnableInput](ue_ue.Actor.md#enableinput)

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

[Actor](ue_ue.Actor.md).[ExecuteUbergraph](ue_ue.Actor.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[FlushNetDormancy](ue_ue.Actor.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[ForceNetUpdate](ue_ue.Actor.md#forcenetupdate)

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

[Actor](ue_ue.Actor.md).[GetActorBounds](ue_ue.Actor.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorEnableCollision](ue_ue.Actor.md#getactorenablecollision)

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

[Actor](ue_ue.Actor.md).[GetActorEyesViewPoint](ue_ue.Actor.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorForwardVector](ue_ue.Actor.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorLabel](ue_ue.Actor.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorRelativeScale3D](ue_ue.Actor.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorRightVector](ue_ue.Actor.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorScale3D](ue_ue.Actor.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorTickInterval](ue_ue.Actor.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorTimeDilation](ue_ue.Actor.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorUpVector](ue_ue.Actor.md#getactorupvector)

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

[Actor](ue_ue.Actor.md).[GetAllChildActors](ue_ue.Actor.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetAttachParentActor](ue_ue.Actor.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetAttachParentSocketName](ue_ue.Actor.md#getattachparentsocketname)

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

[Actor](ue_ue.Actor.md).[GetAttachedActors](ue_ue.Actor.md#getattachedactors)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetClass](ue_ue.Actor.md#getclass)

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

[Actor](ue_ue.Actor.md).[GetComponentByClass](ue_ue.Actor.md#getcomponentbyclass)

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

[Actor](ue_ue.Actor.md).[GetComponentsByInterface](ue_ue.Actor.md#getcomponentsbyinterface)

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

[Actor](ue_ue.Actor.md).[GetComponentsByTag](ue_ue.Actor.md#getcomponentsbytag)

___

### GetControlRotation

▸ **GetControlRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### GetDesiredRotation

▸ **GetDesiredRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

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

[Actor](ue_ue.Actor.md).[GetDistanceTo](ue_ue.Actor.md#getdistanceto)

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

[Actor](ue_ue.Actor.md).[GetDotProductTo](ue_ue.Actor.md#getdotproductto)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetFolderPath](ue_ue.Actor.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetGameTimeSinceCreation](ue_ue.Actor.md#getgametimesincecreation)

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

[Actor](ue_ue.Actor.md).[GetHorizontalDistanceTo](ue_ue.Actor.md#gethorizontaldistanceto)

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

[Actor](ue_ue.Actor.md).[GetHorizontalDotProductTo](ue_ue.Actor.md#gethorizontaldotproductto)

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

[Actor](ue_ue.Actor.md).[GetInputAxisKeyValue](ue_ue.Actor.md#getinputaxiskeyvalue)

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

[Actor](ue_ue.Actor.md).[GetInputAxisValue](ue_ue.Actor.md#getinputaxisvalue)

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

[Actor](ue_ue.Actor.md).[GetInputVectorAxisValue](ue_ue.Actor.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetInstigator](ue_ue.Actor.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetInstigatorController](ue_ue.Actor.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetLifeSpan](ue_ue.Actor.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetLocalRole](ue_ue.Actor.md#getlocalrole)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetName](ue_ue.Actor.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetOuter](ue_ue.Actor.md#getouter)

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

[Actor](ue_ue.Actor.md).[GetOverlappingActors](ue_ue.Actor.md#getoverlappingactors)

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

[Actor](ue_ue.Actor.md).[GetOverlappingComponents](ue_ue.Actor.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetOwner](ue_ue.Actor.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetParentActor](ue_ue.Actor.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetParentComponent](ue_ue.Actor.md#getparentcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetRemoteRole](ue_ue.Actor.md#getremoterole)

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

[Actor](ue_ue.Actor.md).[GetSquaredDistanceTo](ue_ue.Actor.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetTickableWhenPaused](ue_ue.Actor.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetTransform](ue_ue.Actor.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetVelocity](ue_ue.Actor.md#getvelocity)

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

[Actor](ue_ue.Actor.md).[GetVerticalDistanceTo](ue_ue.Actor.md#getverticaldistanceto)

___

### GetViewTarget

▸ **GetViewTarget**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetWorld](ue_ue.Actor.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[HasAuthority](ue_ue.Actor.md#hasauthority)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[IsActorBeingDestroyed](ue_ue.Actor.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[IsActorTickEnabled](ue_ue.Actor.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[IsChildActor](ue_ue.Actor.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[IsEditable](ue_ue.Actor.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[IsHiddenEd](ue_ue.Actor.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[IsHiddenEdAtStartup](ue_ue.Actor.md#ishiddenedatstartup)

___

### IsLocalController

▸ **IsLocalController**(): `boolean`

#### Returns

`boolean`

___

### IsLocalPlayerController

▸ **IsLocalPlayerController**(): `boolean`

#### Returns

`boolean`

___

### IsLookInputIgnored

▸ **IsLookInputIgnored**(): `boolean`

#### Returns

`boolean`

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

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

[Actor](ue_ue.Actor.md).[IsOverlappingActor](ue_ue.Actor.md#isoverlappingactor)

___

### IsPlayerController

▸ **IsPlayerController**(): `boolean`

#### Returns

`boolean`

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[IsSelectable](ue_ue.Actor.md#isselectable)

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

[Actor](ue_ue.Actor.md).[IsTemporarilyHiddenInEditor](ue_ue.Actor.md#istemporarilyhiddenineditor)

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

[Actor](ue_ue.Actor.md).[K2_AddActorLocalOffset](ue_ue.Actor.md#k2_addactorlocaloffset)

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

[Actor](ue_ue.Actor.md).[K2_AddActorLocalRotation](ue_ue.Actor.md#k2_addactorlocalrotation)

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

[Actor](ue_ue.Actor.md).[K2_AddActorLocalTransform](ue_ue.Actor.md#k2_addactorlocaltransform)

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

[Actor](ue_ue.Actor.md).[K2_AddActorWorldOffset](ue_ue.Actor.md#k2_addactorworldoffset)

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

[Actor](ue_ue.Actor.md).[K2_AddActorWorldRotation](ue_ue.Actor.md#k2_addactorworldrotation)

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

[Actor](ue_ue.Actor.md).[K2_AddActorWorldTransform](ue_ue.Actor.md#k2_addactorworldtransform)

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

[Actor](ue_ue.Actor.md).[K2_AttachRootComponentTo](ue_ue.Actor.md#k2_attachrootcomponentto)

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

[Actor](ue_ue.Actor.md).[K2_AttachRootComponentToActor](ue_ue.Actor.md#k2_attachrootcomponenttoactor)

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

[Actor](ue_ue.Actor.md).[K2_AttachToActor](ue_ue.Actor.md#k2_attachtoactor)

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

[Actor](ue_ue.Actor.md).[K2_AttachToComponent](ue_ue.Actor.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[K2_DestroyActor](ue_ue.Actor.md#k2_destroyactor)

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

[Actor](ue_ue.Actor.md).[K2_DestroyComponent](ue_ue.Actor.md#k2_destroycomponent)

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

[Actor](ue_ue.Actor.md).[K2_DetachFromActor](ue_ue.Actor.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[K2_GetActorLocation](ue_ue.Actor.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[K2_GetActorRotation](ue_ue.Actor.md#k2_getactorrotation)

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

[Actor](ue_ue.Actor.md).[K2_GetComponentsByClass](ue_ue.Actor.md#k2_getcomponentsbyclass)

___

### K2\_GetPawn

▸ **K2_GetPawn**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[K2_GetRootComponent](ue_ue.Actor.md#k2_getrootcomponent)

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

[Actor](ue_ue.Actor.md).[K2_OnBecomeViewTarget](ue_ue.Actor.md#k2_onbecomeviewtarget)

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

[Actor](ue_ue.Actor.md).[K2_OnEndViewTarget](ue_ue.Actor.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[K2_OnReset](ue_ue.Actor.md#k2_onreset)

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

[Actor](ue_ue.Actor.md).[K2_SetActorLocation](ue_ue.Actor.md#k2_setactorlocation)

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

[Actor](ue_ue.Actor.md).[K2_SetActorLocationAndRotation](ue_ue.Actor.md#k2_setactorlocationandrotation)

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

[Actor](ue_ue.Actor.md).[K2_SetActorRelativeLocation](ue_ue.Actor.md#k2_setactorrelativelocation)

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

[Actor](ue_ue.Actor.md).[K2_SetActorRelativeRotation](ue_ue.Actor.md#k2_setactorrelativerotation)

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

[Actor](ue_ue.Actor.md).[K2_SetActorRelativeTransform](ue_ue.Actor.md#k2_setactorrelativetransform)

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

[Actor](ue_ue.Actor.md).[K2_SetActorRotation](ue_ue.Actor.md#k2_setactorrotation)

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

[Actor](ue_ue.Actor.md).[K2_SetActorTransform](ue_ue.Actor.md#k2_setactortransform)

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

[Actor](ue_ue.Actor.md).[K2_TeleportTo](ue_ue.Actor.md#k2_teleportto)

___

### LineOfSightTo

▸ **LineOfSightTo**(`Other`, `ViewPoint?`, `bAlternateChecks?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `ViewPoint?` | [`Vector`](ue_ue_s.Vector.md) |
| `bAlternateChecks?` | `boolean` |

#### Returns

`boolean`

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

[Actor](ue_ue.Actor.md).[MakeMIDForMaterial](ue_ue.Actor.md#makemidformaterial)

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

[Actor](ue_ue.Actor.md).[MakeNoise](ue_ue.Actor.md#makenoise)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[OnRep_AttachmentReplication](ue_ue.Actor.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[OnRep_Instigator](ue_ue.Actor.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[OnRep_Owner](ue_ue.Actor.md#onrep_owner)

___

### OnRep\_Pawn

▸ **OnRep_Pawn**(): `void`

#### Returns

`void`

___

### OnRep\_PlayerState

▸ **OnRep_PlayerState**(): `void`

#### Returns

`void`

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[OnRep_ReplicateMovement](ue_ue.Actor.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[OnRep_ReplicatedMovement](ue_ue.Actor.md#onrep_replicatedmovement)

___

### Possess

▸ **Possess**(`InPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

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

[Actor](ue_ue.Actor.md).[PrestreamTextures](ue_ue.Actor.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[ReceiveActorBeginCursorOver](ue_ue.Actor.md#receiveactorbegincursorover)

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

[Actor](ue_ue.Actor.md).[ReceiveActorBeginOverlap](ue_ue.Actor.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[ReceiveActorEndCursorOver](ue_ue.Actor.md#receiveactorendcursorover)

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

[Actor](ue_ue.Actor.md).[ReceiveActorEndOverlap](ue_ue.Actor.md#receiveactorendoverlap)

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

[Actor](ue_ue.Actor.md).[ReceiveActorOnClicked](ue_ue.Actor.md#receiveactoronclicked)

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

[Actor](ue_ue.Actor.md).[ReceiveActorOnInputTouchBegin](ue_ue.Actor.md#receiveactoroninputtouchbegin)

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

[Actor](ue_ue.Actor.md).[ReceiveActorOnInputTouchEnd](ue_ue.Actor.md#receiveactoroninputtouchend)

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

[Actor](ue_ue.Actor.md).[ReceiveActorOnInputTouchEnter](ue_ue.Actor.md#receiveactoroninputtouchenter)

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

[Actor](ue_ue.Actor.md).[ReceiveActorOnInputTouchLeave](ue_ue.Actor.md#receiveactoroninputtouchleave)

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

[Actor](ue_ue.Actor.md).[ReceiveActorOnReleased](ue_ue.Actor.md#receiveactoronreleased)

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

[Actor](ue_ue.Actor.md).[ReceiveAnyDamage](ue_ue.Actor.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[ReceiveBeginPlay](ue_ue.Actor.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[ReceiveDestroyed](ue_ue.Actor.md#receivedestroyed)

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

[Actor](ue_ue.Actor.md).[ReceiveEndPlay](ue_ue.Actor.md#receiveendplay)

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

[Actor](ue_ue.Actor.md).[ReceiveHit](ue_ue.Actor.md#receivehit)

___

### ReceiveInstigatedAnyDamage

▸ **ReceiveInstigatedAnyDamage**(`Damage`, `DamageType`, `DamagedActor`, `DamageCauser`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Damage` | `number` |
| `DamageType` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\> |
| `DamagedActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `DamageCauser` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

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

[Actor](ue_ue.Actor.md).[ReceivePointDamage](ue_ue.Actor.md#receivepointdamage)

___

### ReceivePossess

▸ **ReceivePossess**(`PossessedPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PossessedPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

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

[Actor](ue_ue.Actor.md).[ReceiveRadialDamage](ue_ue.Actor.md#receiveradialdamage)

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

[Actor](ue_ue.Actor.md).[ReceiveTick](ue_ue.Actor.md#receivetick)

___

### ReceiveUnPossess

▸ **ReceiveUnPossess**(`UnpossessedPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `UnpossessedPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

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

[Actor](ue_ue.Actor.md).[RemoveTickPrerequisiteActor](ue_ue.Actor.md#removetickprerequisiteactor)

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

[Actor](ue_ue.Actor.md).[RemoveTickPrerequisiteComponent](ue_ue.Actor.md#removetickprerequisitecomponent)

___

### ResetIgnoreInputFlags

▸ **ResetIgnoreInputFlags**(): `void`

#### Returns

`void`

___

### ResetIgnoreLookInput

▸ **ResetIgnoreLookInput**(): `void`

#### Returns

`void`

___

### ResetIgnoreMoveInput

▸ **ResetIgnoreMoveInput**(): `void`

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

[Actor](ue_ue.Actor.md).[SetActorEnableCollision](ue_ue.Actor.md#setactorenablecollision)

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

[Actor](ue_ue.Actor.md).[SetActorHiddenInGame](ue_ue.Actor.md#setactorhiddeningame)

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

[Actor](ue_ue.Actor.md).[SetActorLabel](ue_ue.Actor.md#setactorlabel)

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

[Actor](ue_ue.Actor.md).[SetActorRelativeScale3D](ue_ue.Actor.md#setactorrelativescale3d)

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

[Actor](ue_ue.Actor.md).[SetActorScale3D](ue_ue.Actor.md#setactorscale3d)

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

[Actor](ue_ue.Actor.md).[SetActorTickEnabled](ue_ue.Actor.md#setactortickenabled)

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

[Actor](ue_ue.Actor.md).[SetActorTickInterval](ue_ue.Actor.md#setactortickinterval)

___

### SetControlRotation

▸ **SetControlRotation**(`NewRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

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

[Actor](ue_ue.Actor.md).[SetFolderPath](ue_ue.Actor.md#setfolderpath)

___

### SetIgnoreLookInput

▸ **SetIgnoreLookInput**(`bNewLookInput`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewLookInput` | `boolean` |

#### Returns

`void`

___

### SetIgnoreMoveInput

▸ **SetIgnoreMoveInput**(`bNewMoveInput`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewMoveInput` | `boolean` |

#### Returns

`void`

___

### SetInitialLocationAndRotation

▸ **SetInitialLocationAndRotation**(`NewLocation`, `NewRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

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

[Actor](ue_ue.Actor.md).[SetIsTemporarilyHiddenInEditor](ue_ue.Actor.md#setistemporarilyhiddenineditor)

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

[Actor](ue_ue.Actor.md).[SetLifeSpan](ue_ue.Actor.md#setlifespan)

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

[Actor](ue_ue.Actor.md).[SetNetDormancy](ue_ue.Actor.md#setnetdormancy)

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

[Actor](ue_ue.Actor.md).[SetOwner](ue_ue.Actor.md#setowner)

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

[Actor](ue_ue.Actor.md).[SetReplicateMovement](ue_ue.Actor.md#setreplicatemovement)

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

[Actor](ue_ue.Actor.md).[SetReplicates](ue_ue.Actor.md#setreplicates)

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

[Actor](ue_ue.Actor.md).[SetTickGroup](ue_ue.Actor.md#settickgroup)

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

[Actor](ue_ue.Actor.md).[SetTickableWhenPaused](ue_ue.Actor.md#settickablewhenpaused)

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

[Actor](ue_ue.Actor.md).[SnapRootComponentTo](ue_ue.Actor.md#snaprootcomponentto)

___

### StopMovement

▸ **StopMovement**(): `void`

#### Returns

`void`

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[TearOff](ue_ue.Actor.md#tearoff)

___

### UnPossess

▸ **UnPossess**(): `void`

#### Returns

`void`

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[UserConstructionScript](ue_ue.Actor.md#userconstructionscript)

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

[Actor](ue_ue.Actor.md).[WasRecentlyRendered](ue_ue.Actor.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Controller`](ue_ue.Controller.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Overrides

[Actor](ue_ue.Actor.md).[Find](ue_ue.Actor.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`Controller`](ue_ue.Controller.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Overrides

[Actor](ue_ue.Actor.md).[Load](ue_ue.Actor.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Actor](ue_ue.Actor.md).[StaticClass](ue_ue.Actor.md#staticclass)
