[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GizmoActor

# Class: GizmoActor

[ue/ue](../modules/ue_ue.md).GizmoActor

## Hierarchy

- [`InternalToolFrameworkActor`](ue_ue.InternalToolFrameworkActor.md)

  ↳ **`GizmoActor`**

  ↳↳ [`TransformGizmoActor`](ue_ue.TransformGizmoActor.md)

## Table of contents

### Constructors

- [constructor](ue_ue.GizmoActor.md#constructor)

### Properties

- [ActorLabel](ue_ue.GizmoActor.md#actorlabel)
- [AttachmentReplication](ue_ue.GizmoActor.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.GizmoActor.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.GizmoActor.md#blueprintcreatedcomponents)
- [Children](ue_ue.GizmoActor.md#children)
- [ControllingMatineeActors](ue_ue.GizmoActor.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.GizmoActor.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.GizmoActor.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.GizmoActor.md#folderpath)
- [GroupActor](ue_ue.GizmoActor.md#groupactor)
- [HiddenEditorViews](ue_ue.GizmoActor.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.GizmoActor.md#initiallifespan)
- [InputComponent](ue_ue.GizmoActor.md#inputcomponent)
- [InputPriority](ue_ue.GizmoActor.md#inputpriority)
- [InstanceComponents](ue_ue.GizmoActor.md#instancecomponents)
- [Instigator](ue_ue.GizmoActor.md#instigator)
- [Layers](ue_ue.GizmoActor.md#layers)
- [MinNetUpdateFrequency](ue_ue.GizmoActor.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.GizmoActor.md#netculldistancesquared)
- [NetDormancy](ue_ue.GizmoActor.md#netdormancy)
- [NetDriverName](ue_ue.GizmoActor.md#netdrivername)
- [NetPriority](ue_ue.GizmoActor.md#netpriority)
- [NetTag](ue_ue.GizmoActor.md#nettag)
- [NetUpdateFrequency](ue_ue.GizmoActor.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.GizmoActor.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.GizmoActor.md#onactorendoverlap)
- [OnActorHit](ue_ue.GizmoActor.md#onactorhit)
- [OnBeginCursorOver](ue_ue.GizmoActor.md#onbegincursorover)
- [OnClicked](ue_ue.GizmoActor.md#onclicked)
- [OnDestroyed](ue_ue.GizmoActor.md#ondestroyed)
- [OnEndCursorOver](ue_ue.GizmoActor.md#onendcursorover)
- [OnEndPlay](ue_ue.GizmoActor.md#onendplay)
- [OnInputTouchBegin](ue_ue.GizmoActor.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.GizmoActor.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.GizmoActor.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.GizmoActor.md#oninputtouchleave)
- [OnReleased](ue_ue.GizmoActor.md#onreleased)
- [OnTakeAnyDamage](ue_ue.GizmoActor.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.GizmoActor.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.GizmoActor.md#ontakeradialdamage)
- [Owner](ue_ue.GizmoActor.md#owner)
- [ParentComponent](ue_ue.GizmoActor.md#parentcomponent)
- [ParentComponentActor](ue_ue.GizmoActor.md#parentcomponentactor)
- [PivotOffset](ue_ue.GizmoActor.md#pivotoffset)
- [PrimaryActorTick](ue_ue.GizmoActor.md#primaryactortick)
- [RemoteRole](ue_ue.GizmoActor.md#remoterole)
- [ReplicatedMovement](ue_ue.GizmoActor.md#replicatedmovement)
- [Role](ue_ue.GizmoActor.md#role)
- [RootComponent](ue_ue.GizmoActor.md#rootcomponent)
- [SpawnCollisionHandlingMethod](ue_ue.GizmoActor.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.GizmoActor.md#spritescale)
- [Tags](ue_ue.GizmoActor.md#tags)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.GizmoActor.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.GizmoActor.md#__tid_actor__)
- [\_\_tid\_GizmoActor\_\_](ue_ue.GizmoActor.md#__tid_gizmoactor__)
- [\_\_tid\_InternalToolFrameworkActor\_\_](ue_ue.GizmoActor.md#__tid_internaltoolframeworkactor__)
- [\_\_tid\_Object\_\_](ue_ue.GizmoActor.md#__tid_object__)
- [bActorEnableCollision](ue_ue.GizmoActor.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.GizmoActor.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.GizmoActor.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.GizmoActor.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.GizmoActor.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.GizmoActor.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.GizmoActor.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.GizmoActor.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.GizmoActor.md#bblockinput)
- [bCanBeDamaged](ue_ue.GizmoActor.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.GizmoActor.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.GizmoActor.md#bcollidewhenplacing)
- [bEditable](ue_ue.GizmoActor.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.GizmoActor.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.GizmoActor.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.GizmoActor.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.GizmoActor.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.GizmoActor.md#bhidden)
- [bHiddenEd](ue_ue.GizmoActor.md#bhiddened)
- [bHiddenEdLayer](ue_ue.GizmoActor.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.GizmoActor.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.GizmoActor.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.GizmoActor.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.GizmoActor.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.GizmoActor.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.GizmoActor.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.GizmoActor.md#blocklocation)
- [bNetLoadOnClient](ue_ue.GizmoActor.md#bnetloadonclient)
- [bNetStartup](ue_ue.GizmoActor.md#bnetstartup)
- [bNetTemporary](ue_ue.GizmoActor.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.GizmoActor.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.GizmoActor.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.GizmoActor.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.GizmoActor.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.GizmoActor.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.GizmoActor.md#breplayrewindable)
- [bReplicateMovement](ue_ue.GizmoActor.md#breplicatemovement)
- [bReplicates](ue_ue.GizmoActor.md#breplicates)
- [bTearOff](ue_ue.GizmoActor.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.GizmoActor.md#actorhastag)
- [AddComponent](ue_ue.GizmoActor.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.GizmoActor.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.GizmoActor.md#addtickprerequisitecomponent)
- [CreateDefaultSubobject](ue_ue.GizmoActor.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.GizmoActor.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.GizmoActor.md#disableinput)
- [EnableInput](ue_ue.GizmoActor.md#enableinput)
- [ExecuteUbergraph](ue_ue.GizmoActor.md#executeubergraph)
- [FlushNetDormancy](ue_ue.GizmoActor.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.GizmoActor.md#forcenetupdate)
- [GetActorBounds](ue_ue.GizmoActor.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.GizmoActor.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.GizmoActor.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.GizmoActor.md#getactorforwardvector)
- [GetActorLabel](ue_ue.GizmoActor.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.GizmoActor.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.GizmoActor.md#getactorrightvector)
- [GetActorScale3D](ue_ue.GizmoActor.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.GizmoActor.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.GizmoActor.md#getactortimedilation)
- [GetActorUpVector](ue_ue.GizmoActor.md#getactorupvector)
- [GetAllChildActors](ue_ue.GizmoActor.md#getallchildactors)
- [GetAttachParentActor](ue_ue.GizmoActor.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.GizmoActor.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.GizmoActor.md#getattachedactors)
- [GetClass](ue_ue.GizmoActor.md#getclass)
- [GetComponentByClass](ue_ue.GizmoActor.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.GizmoActor.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.GizmoActor.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.GizmoActor.md#getdistanceto)
- [GetDotProductTo](ue_ue.GizmoActor.md#getdotproductto)
- [GetFolderPath](ue_ue.GizmoActor.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.GizmoActor.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.GizmoActor.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.GizmoActor.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.GizmoActor.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.GizmoActor.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.GizmoActor.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.GizmoActor.md#getinstigator)
- [GetInstigatorController](ue_ue.GizmoActor.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.GizmoActor.md#getlifespan)
- [GetLocalRole](ue_ue.GizmoActor.md#getlocalrole)
- [GetName](ue_ue.GizmoActor.md#getname)
- [GetOuter](ue_ue.GizmoActor.md#getouter)
- [GetOverlappingActors](ue_ue.GizmoActor.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.GizmoActor.md#getoverlappingcomponents)
- [GetOwner](ue_ue.GizmoActor.md#getowner)
- [GetParentActor](ue_ue.GizmoActor.md#getparentactor)
- [GetParentComponent](ue_ue.GizmoActor.md#getparentcomponent)
- [GetRemoteRole](ue_ue.GizmoActor.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.GizmoActor.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.GizmoActor.md#gettickablewhenpaused)
- [GetTransform](ue_ue.GizmoActor.md#gettransform)
- [GetVelocity](ue_ue.GizmoActor.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.GizmoActor.md#getverticaldistanceto)
- [GetWorld](ue_ue.GizmoActor.md#getworld)
- [HasAuthority](ue_ue.GizmoActor.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.GizmoActor.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.GizmoActor.md#isactortickenabled)
- [IsChildActor](ue_ue.GizmoActor.md#ischildactor)
- [IsEditable](ue_ue.GizmoActor.md#iseditable)
- [IsHiddenEd](ue_ue.GizmoActor.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.GizmoActor.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.GizmoActor.md#isoverlappingactor)
- [IsSelectable](ue_ue.GizmoActor.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.GizmoActor.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.GizmoActor.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.GizmoActor.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.GizmoActor.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.GizmoActor.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.GizmoActor.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.GizmoActor.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.GizmoActor.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.GizmoActor.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.GizmoActor.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.GizmoActor.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.GizmoActor.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.GizmoActor.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.GizmoActor.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.GizmoActor.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.GizmoActor.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.GizmoActor.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.GizmoActor.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.GizmoActor.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.GizmoActor.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.GizmoActor.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.GizmoActor.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.GizmoActor.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.GizmoActor.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.GizmoActor.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.GizmoActor.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.GizmoActor.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.GizmoActor.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.GizmoActor.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.GizmoActor.md#makemidformaterial)
- [MakeNoise](ue_ue.GizmoActor.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.GizmoActor.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.GizmoActor.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.GizmoActor.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.GizmoActor.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.GizmoActor.md#onrep_replicatedmovement)
- [PrestreamTextures](ue_ue.GizmoActor.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.GizmoActor.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.GizmoActor.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.GizmoActor.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.GizmoActor.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.GizmoActor.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.GizmoActor.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.GizmoActor.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.GizmoActor.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.GizmoActor.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.GizmoActor.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.GizmoActor.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.GizmoActor.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.GizmoActor.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.GizmoActor.md#receiveendplay)
- [ReceiveHit](ue_ue.GizmoActor.md#receivehit)
- [ReceivePointDamage](ue_ue.GizmoActor.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.GizmoActor.md#receiveradialdamage)
- [ReceiveTick](ue_ue.GizmoActor.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.GizmoActor.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.GizmoActor.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.GizmoActor.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.GizmoActor.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.GizmoActor.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.GizmoActor.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.GizmoActor.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.GizmoActor.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.GizmoActor.md#setactortickinterval)
- [SetFolderPath](ue_ue.GizmoActor.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.GizmoActor.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.GizmoActor.md#setlifespan)
- [SetNetDormancy](ue_ue.GizmoActor.md#setnetdormancy)
- [SetOwner](ue_ue.GizmoActor.md#setowner)
- [SetReplicateMovement](ue_ue.GizmoActor.md#setreplicatemovement)
- [SetReplicates](ue_ue.GizmoActor.md#setreplicates)
- [SetTickGroup](ue_ue.GizmoActor.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.GizmoActor.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.GizmoActor.md#snaprootcomponentto)
- [TearOff](ue_ue.GizmoActor.md#tearoff)
- [UserConstructionScript](ue_ue.GizmoActor.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.GizmoActor.md#wasrecentlyrendered)
- [Find](ue_ue.GizmoActor.md#find)
- [Load](ue_ue.GizmoActor.md#load)
- [StaticClass](ue_ue.GizmoActor.md#staticclass)

## Constructors

### constructor

• **new GizmoActor**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[constructor](ue_ue.InternalToolFrameworkActor.md#constructor)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ActorLabel](ue_ue.InternalToolFrameworkActor.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[AttachmentReplication](ue_ue.InternalToolFrameworkActor.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[AutoReceiveInput](ue_ue.InternalToolFrameworkActor.md#autoreceiveinput)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[BlueprintCreatedComponents](ue_ue.InternalToolFrameworkActor.md#blueprintcreatedcomponents)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[Children](ue_ue.InternalToolFrameworkActor.md#children)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ControllingMatineeActors](ue_ue.InternalToolFrameworkActor.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[CustomTimeDilation](ue_ue.InternalToolFrameworkActor.md#customtimedilation)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.InternalToolFrameworkActor.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[FolderPath](ue_ue.InternalToolFrameworkActor.md#folderpath)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GroupActor](ue_ue.InternalToolFrameworkActor.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[HiddenEditorViews](ue_ue.InternalToolFrameworkActor.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[InitialLifeSpan](ue_ue.InternalToolFrameworkActor.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[InputComponent](ue_ue.InternalToolFrameworkActor.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[InputPriority](ue_ue.InternalToolFrameworkActor.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[InstanceComponents](ue_ue.InternalToolFrameworkActor.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[Instigator](ue_ue.InternalToolFrameworkActor.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[Layers](ue_ue.InternalToolFrameworkActor.md#layers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[MinNetUpdateFrequency](ue_ue.InternalToolFrameworkActor.md#minnetupdatefrequency)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[NetCullDistanceSquared](ue_ue.InternalToolFrameworkActor.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[NetDormancy](ue_ue.InternalToolFrameworkActor.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[NetDriverName](ue_ue.InternalToolFrameworkActor.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[NetPriority](ue_ue.InternalToolFrameworkActor.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[NetTag](ue_ue.InternalToolFrameworkActor.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[NetUpdateFrequency](ue_ue.InternalToolFrameworkActor.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnActorBeginOverlap](ue_ue.InternalToolFrameworkActor.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnActorEndOverlap](ue_ue.InternalToolFrameworkActor.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnActorHit](ue_ue.InternalToolFrameworkActor.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnBeginCursorOver](ue_ue.InternalToolFrameworkActor.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnClicked](ue_ue.InternalToolFrameworkActor.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnDestroyed](ue_ue.InternalToolFrameworkActor.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnEndCursorOver](ue_ue.InternalToolFrameworkActor.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnEndPlay](ue_ue.InternalToolFrameworkActor.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnInputTouchBegin](ue_ue.InternalToolFrameworkActor.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnInputTouchEnd](ue_ue.InternalToolFrameworkActor.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnInputTouchEnter](ue_ue.InternalToolFrameworkActor.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnInputTouchLeave](ue_ue.InternalToolFrameworkActor.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnReleased](ue_ue.InternalToolFrameworkActor.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnTakeAnyDamage](ue_ue.InternalToolFrameworkActor.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnTakePointDamage](ue_ue.InternalToolFrameworkActor.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnTakeRadialDamage](ue_ue.InternalToolFrameworkActor.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[Owner](ue_ue.InternalToolFrameworkActor.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ParentComponent](ue_ue.InternalToolFrameworkActor.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ParentComponentActor](ue_ue.InternalToolFrameworkActor.md#parentcomponentactor)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[PivotOffset](ue_ue.InternalToolFrameworkActor.md#pivotoffset)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[PrimaryActorTick](ue_ue.InternalToolFrameworkActor.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[RemoteRole](ue_ue.InternalToolFrameworkActor.md#remoterole)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReplicatedMovement](ue_ue.InternalToolFrameworkActor.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[Role](ue_ue.InternalToolFrameworkActor.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[RootComponent](ue_ue.InternalToolFrameworkActor.md#rootcomponent)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SpawnCollisionHandlingMethod](ue_ue.InternalToolFrameworkActor.md#spawncollisionhandlingmethod)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SpriteScale](ue_ue.InternalToolFrameworkActor.md#spritescale)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[Tags](ue_ue.InternalToolFrameworkActor.md#tags)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.InternalToolFrameworkActor.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[__tid_Actor__](ue_ue.InternalToolFrameworkActor.md#__tid_actor__)

___

### \_\_tid\_GizmoActor\_\_

• **\_\_tid\_GizmoActor\_\_**: `boolean`

___

### \_\_tid\_InternalToolFrameworkActor\_\_

• **\_\_tid\_InternalToolFrameworkActor\_\_**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[__tid_InternalToolFrameworkActor__](ue_ue.InternalToolFrameworkActor.md#__tid_internaltoolframeworkactor__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[__tid_Object__](ue_ue.InternalToolFrameworkActor.md#__tid_object__)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bActorEnableCollision](ue_ue.InternalToolFrameworkActor.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bActorIsBeingDestroyed](ue_ue.InternalToolFrameworkActor.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bActorLabelEditable](ue_ue.InternalToolFrameworkActor.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bActorSeamlessTraveled](ue_ue.InternalToolFrameworkActor.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.InternalToolFrameworkActor.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bAllowTickBeforeBeginPlay](ue_ue.InternalToolFrameworkActor.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bAlwaysRelevant](ue_ue.InternalToolFrameworkActor.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bAutoDestroyWhenFinished](ue_ue.InternalToolFrameworkActor.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bBlockInput](ue_ue.InternalToolFrameworkActor.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bCanBeDamaged](ue_ue.InternalToolFrameworkActor.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bCanBeInCluster](ue_ue.InternalToolFrameworkActor.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bCollideWhenPlacing](ue_ue.InternalToolFrameworkActor.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bEditable](ue_ue.InternalToolFrameworkActor.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bEnableAutoLODGeneration](ue_ue.InternalToolFrameworkActor.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bExchangedRoles](ue_ue.InternalToolFrameworkActor.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bFindCameraComponentWhenViewTarget](ue_ue.InternalToolFrameworkActor.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.InternalToolFrameworkActor.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bHidden](ue_ue.InternalToolFrameworkActor.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bHiddenEd](ue_ue.InternalToolFrameworkActor.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bHiddenEdLayer](ue_ue.InternalToolFrameworkActor.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bHiddenEdLevel](ue_ue.InternalToolFrameworkActor.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bHiddenEdTemporary](ue_ue.InternalToolFrameworkActor.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bIgnoresOriginShifting](ue_ue.InternalToolFrameworkActor.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bIsEditorOnlyActor](ue_ue.InternalToolFrameworkActor.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bIsEditorPreviewActor](ue_ue.InternalToolFrameworkActor.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bListedInSceneOutliner](ue_ue.InternalToolFrameworkActor.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bLockLocation](ue_ue.InternalToolFrameworkActor.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bNetLoadOnClient](ue_ue.InternalToolFrameworkActor.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bNetStartup](ue_ue.InternalToolFrameworkActor.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bNetTemporary](ue_ue.InternalToolFrameworkActor.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bNetUseOwnerRelevancy](ue_ue.InternalToolFrameworkActor.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bOnlyRelevantToOwner](ue_ue.InternalToolFrameworkActor.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bOptimizeBPComponentData](ue_ue.InternalToolFrameworkActor.md#boptimizebpcomponentdata)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bRelevantForLevelBounds](ue_ue.InternalToolFrameworkActor.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bRelevantForNetworkReplays](ue_ue.InternalToolFrameworkActor.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bReplayRewindable](ue_ue.InternalToolFrameworkActor.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bReplicateMovement](ue_ue.InternalToolFrameworkActor.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bReplicates](ue_ue.InternalToolFrameworkActor.md#breplicates)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[bTearOff](ue_ue.InternalToolFrameworkActor.md#btearoff)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ActorHasTag](ue_ue.InternalToolFrameworkActor.md#actorhastag)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[AddComponent](ue_ue.InternalToolFrameworkActor.md#addcomponent)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[AddTickPrerequisiteActor](ue_ue.InternalToolFrameworkActor.md#addtickprerequisiteactor)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[AddTickPrerequisiteComponent](ue_ue.InternalToolFrameworkActor.md#addtickprerequisitecomponent)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[CreateDefaultSubobject](ue_ue.InternalToolFrameworkActor.md#createdefaultsubobject)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[DetachRootComponentFromParent](ue_ue.InternalToolFrameworkActor.md#detachrootcomponentfromparent)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[DisableInput](ue_ue.InternalToolFrameworkActor.md#disableinput)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[EnableInput](ue_ue.InternalToolFrameworkActor.md#enableinput)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ExecuteUbergraph](ue_ue.InternalToolFrameworkActor.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[FlushNetDormancy](ue_ue.InternalToolFrameworkActor.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ForceNetUpdate](ue_ue.InternalToolFrameworkActor.md#forcenetupdate)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetActorBounds](ue_ue.InternalToolFrameworkActor.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetActorEnableCollision](ue_ue.InternalToolFrameworkActor.md#getactorenablecollision)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetActorEyesViewPoint](ue_ue.InternalToolFrameworkActor.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetActorForwardVector](ue_ue.InternalToolFrameworkActor.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetActorLabel](ue_ue.InternalToolFrameworkActor.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetActorRelativeScale3D](ue_ue.InternalToolFrameworkActor.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetActorRightVector](ue_ue.InternalToolFrameworkActor.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetActorScale3D](ue_ue.InternalToolFrameworkActor.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetActorTickInterval](ue_ue.InternalToolFrameworkActor.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetActorTimeDilation](ue_ue.InternalToolFrameworkActor.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetActorUpVector](ue_ue.InternalToolFrameworkActor.md#getactorupvector)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetAllChildActors](ue_ue.InternalToolFrameworkActor.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetAttachParentActor](ue_ue.InternalToolFrameworkActor.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetAttachParentSocketName](ue_ue.InternalToolFrameworkActor.md#getattachparentsocketname)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetAttachedActors](ue_ue.InternalToolFrameworkActor.md#getattachedactors)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetClass](ue_ue.InternalToolFrameworkActor.md#getclass)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetComponentByClass](ue_ue.InternalToolFrameworkActor.md#getcomponentbyclass)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetComponentsByInterface](ue_ue.InternalToolFrameworkActor.md#getcomponentsbyinterface)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetComponentsByTag](ue_ue.InternalToolFrameworkActor.md#getcomponentsbytag)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetDistanceTo](ue_ue.InternalToolFrameworkActor.md#getdistanceto)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetDotProductTo](ue_ue.InternalToolFrameworkActor.md#getdotproductto)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetFolderPath](ue_ue.InternalToolFrameworkActor.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetGameTimeSinceCreation](ue_ue.InternalToolFrameworkActor.md#getgametimesincecreation)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetHorizontalDistanceTo](ue_ue.InternalToolFrameworkActor.md#gethorizontaldistanceto)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetHorizontalDotProductTo](ue_ue.InternalToolFrameworkActor.md#gethorizontaldotproductto)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetInputAxisKeyValue](ue_ue.InternalToolFrameworkActor.md#getinputaxiskeyvalue)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetInputAxisValue](ue_ue.InternalToolFrameworkActor.md#getinputaxisvalue)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetInputVectorAxisValue](ue_ue.InternalToolFrameworkActor.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetInstigator](ue_ue.InternalToolFrameworkActor.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetInstigatorController](ue_ue.InternalToolFrameworkActor.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetLifeSpan](ue_ue.InternalToolFrameworkActor.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetLocalRole](ue_ue.InternalToolFrameworkActor.md#getlocalrole)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetName](ue_ue.InternalToolFrameworkActor.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetOuter](ue_ue.InternalToolFrameworkActor.md#getouter)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetOverlappingActors](ue_ue.InternalToolFrameworkActor.md#getoverlappingactors)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetOverlappingComponents](ue_ue.InternalToolFrameworkActor.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetOwner](ue_ue.InternalToolFrameworkActor.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetParentActor](ue_ue.InternalToolFrameworkActor.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetParentComponent](ue_ue.InternalToolFrameworkActor.md#getparentcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetRemoteRole](ue_ue.InternalToolFrameworkActor.md#getremoterole)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetSquaredDistanceTo](ue_ue.InternalToolFrameworkActor.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetTickableWhenPaused](ue_ue.InternalToolFrameworkActor.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetTransform](ue_ue.InternalToolFrameworkActor.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetVelocity](ue_ue.InternalToolFrameworkActor.md#getvelocity)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetVerticalDistanceTo](ue_ue.InternalToolFrameworkActor.md#getverticaldistanceto)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[GetWorld](ue_ue.InternalToolFrameworkActor.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[HasAuthority](ue_ue.InternalToolFrameworkActor.md#hasauthority)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[IsActorBeingDestroyed](ue_ue.InternalToolFrameworkActor.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[IsActorTickEnabled](ue_ue.InternalToolFrameworkActor.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[IsChildActor](ue_ue.InternalToolFrameworkActor.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[IsEditable](ue_ue.InternalToolFrameworkActor.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[IsHiddenEd](ue_ue.InternalToolFrameworkActor.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[IsHiddenEdAtStartup](ue_ue.InternalToolFrameworkActor.md#ishiddenedatstartup)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[IsOverlappingActor](ue_ue.InternalToolFrameworkActor.md#isoverlappingactor)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[IsSelectable](ue_ue.InternalToolFrameworkActor.md#isselectable)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[IsTemporarilyHiddenInEditor](ue_ue.InternalToolFrameworkActor.md#istemporarilyhiddenineditor)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_AddActorLocalOffset](ue_ue.InternalToolFrameworkActor.md#k2_addactorlocaloffset)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_AddActorLocalRotation](ue_ue.InternalToolFrameworkActor.md#k2_addactorlocalrotation)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_AddActorLocalTransform](ue_ue.InternalToolFrameworkActor.md#k2_addactorlocaltransform)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_AddActorWorldOffset](ue_ue.InternalToolFrameworkActor.md#k2_addactorworldoffset)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_AddActorWorldRotation](ue_ue.InternalToolFrameworkActor.md#k2_addactorworldrotation)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_AddActorWorldTransform](ue_ue.InternalToolFrameworkActor.md#k2_addactorworldtransform)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_AttachRootComponentTo](ue_ue.InternalToolFrameworkActor.md#k2_attachrootcomponentto)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_AttachRootComponentToActor](ue_ue.InternalToolFrameworkActor.md#k2_attachrootcomponenttoactor)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_AttachToActor](ue_ue.InternalToolFrameworkActor.md#k2_attachtoactor)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_AttachToComponent](ue_ue.InternalToolFrameworkActor.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_DestroyActor](ue_ue.InternalToolFrameworkActor.md#k2_destroyactor)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_DestroyComponent](ue_ue.InternalToolFrameworkActor.md#k2_destroycomponent)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_DetachFromActor](ue_ue.InternalToolFrameworkActor.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_GetActorLocation](ue_ue.InternalToolFrameworkActor.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_GetActorRotation](ue_ue.InternalToolFrameworkActor.md#k2_getactorrotation)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_GetComponentsByClass](ue_ue.InternalToolFrameworkActor.md#k2_getcomponentsbyclass)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_GetRootComponent](ue_ue.InternalToolFrameworkActor.md#k2_getrootcomponent)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_OnBecomeViewTarget](ue_ue.InternalToolFrameworkActor.md#k2_onbecomeviewtarget)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_OnEndViewTarget](ue_ue.InternalToolFrameworkActor.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_OnReset](ue_ue.InternalToolFrameworkActor.md#k2_onreset)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_SetActorLocation](ue_ue.InternalToolFrameworkActor.md#k2_setactorlocation)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_SetActorLocationAndRotation](ue_ue.InternalToolFrameworkActor.md#k2_setactorlocationandrotation)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_SetActorRelativeLocation](ue_ue.InternalToolFrameworkActor.md#k2_setactorrelativelocation)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_SetActorRelativeRotation](ue_ue.InternalToolFrameworkActor.md#k2_setactorrelativerotation)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_SetActorRelativeTransform](ue_ue.InternalToolFrameworkActor.md#k2_setactorrelativetransform)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_SetActorRotation](ue_ue.InternalToolFrameworkActor.md#k2_setactorrotation)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_SetActorTransform](ue_ue.InternalToolFrameworkActor.md#k2_setactortransform)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[K2_TeleportTo](ue_ue.InternalToolFrameworkActor.md#k2_teleportto)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[MakeMIDForMaterial](ue_ue.InternalToolFrameworkActor.md#makemidformaterial)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[MakeNoise](ue_ue.InternalToolFrameworkActor.md#makenoise)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnRep_AttachmentReplication](ue_ue.InternalToolFrameworkActor.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnRep_Instigator](ue_ue.InternalToolFrameworkActor.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnRep_Owner](ue_ue.InternalToolFrameworkActor.md#onrep_owner)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnRep_ReplicateMovement](ue_ue.InternalToolFrameworkActor.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[OnRep_ReplicatedMovement](ue_ue.InternalToolFrameworkActor.md#onrep_replicatedmovement)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[PrestreamTextures](ue_ue.InternalToolFrameworkActor.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceiveActorBeginCursorOver](ue_ue.InternalToolFrameworkActor.md#receiveactorbegincursorover)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceiveActorBeginOverlap](ue_ue.InternalToolFrameworkActor.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceiveActorEndCursorOver](ue_ue.InternalToolFrameworkActor.md#receiveactorendcursorover)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceiveActorEndOverlap](ue_ue.InternalToolFrameworkActor.md#receiveactorendoverlap)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceiveActorOnClicked](ue_ue.InternalToolFrameworkActor.md#receiveactoronclicked)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceiveActorOnInputTouchBegin](ue_ue.InternalToolFrameworkActor.md#receiveactoroninputtouchbegin)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceiveActorOnInputTouchEnd](ue_ue.InternalToolFrameworkActor.md#receiveactoroninputtouchend)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceiveActorOnInputTouchEnter](ue_ue.InternalToolFrameworkActor.md#receiveactoroninputtouchenter)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceiveActorOnInputTouchLeave](ue_ue.InternalToolFrameworkActor.md#receiveactoroninputtouchleave)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceiveActorOnReleased](ue_ue.InternalToolFrameworkActor.md#receiveactoronreleased)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceiveAnyDamage](ue_ue.InternalToolFrameworkActor.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceiveBeginPlay](ue_ue.InternalToolFrameworkActor.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceiveDestroyed](ue_ue.InternalToolFrameworkActor.md#receivedestroyed)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceiveEndPlay](ue_ue.InternalToolFrameworkActor.md#receiveendplay)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceiveHit](ue_ue.InternalToolFrameworkActor.md#receivehit)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceivePointDamage](ue_ue.InternalToolFrameworkActor.md#receivepointdamage)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceiveRadialDamage](ue_ue.InternalToolFrameworkActor.md#receiveradialdamage)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[ReceiveTick](ue_ue.InternalToolFrameworkActor.md#receivetick)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[RemoveTickPrerequisiteActor](ue_ue.InternalToolFrameworkActor.md#removetickprerequisiteactor)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[RemoveTickPrerequisiteComponent](ue_ue.InternalToolFrameworkActor.md#removetickprerequisitecomponent)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SetActorEnableCollision](ue_ue.InternalToolFrameworkActor.md#setactorenablecollision)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SetActorHiddenInGame](ue_ue.InternalToolFrameworkActor.md#setactorhiddeningame)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SetActorLabel](ue_ue.InternalToolFrameworkActor.md#setactorlabel)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SetActorRelativeScale3D](ue_ue.InternalToolFrameworkActor.md#setactorrelativescale3d)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SetActorScale3D](ue_ue.InternalToolFrameworkActor.md#setactorscale3d)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SetActorTickEnabled](ue_ue.InternalToolFrameworkActor.md#setactortickenabled)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SetActorTickInterval](ue_ue.InternalToolFrameworkActor.md#setactortickinterval)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SetFolderPath](ue_ue.InternalToolFrameworkActor.md#setfolderpath)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SetIsTemporarilyHiddenInEditor](ue_ue.InternalToolFrameworkActor.md#setistemporarilyhiddenineditor)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SetLifeSpan](ue_ue.InternalToolFrameworkActor.md#setlifespan)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SetNetDormancy](ue_ue.InternalToolFrameworkActor.md#setnetdormancy)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SetOwner](ue_ue.InternalToolFrameworkActor.md#setowner)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SetReplicateMovement](ue_ue.InternalToolFrameworkActor.md#setreplicatemovement)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SetReplicates](ue_ue.InternalToolFrameworkActor.md#setreplicates)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SetTickGroup](ue_ue.InternalToolFrameworkActor.md#settickgroup)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SetTickableWhenPaused](ue_ue.InternalToolFrameworkActor.md#settickablewhenpaused)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[SnapRootComponentTo](ue_ue.InternalToolFrameworkActor.md#snaprootcomponentto)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[TearOff](ue_ue.InternalToolFrameworkActor.md#tearoff)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[UserConstructionScript](ue_ue.InternalToolFrameworkActor.md#userconstructionscript)

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

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[WasRecentlyRendered](ue_ue.InternalToolFrameworkActor.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GizmoActor`](ue_ue.GizmoActor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GizmoActor`](ue_ue.GizmoActor.md)

#### Overrides

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[Find](ue_ue.InternalToolFrameworkActor.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GizmoActor`](ue_ue.GizmoActor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GizmoActor`](ue_ue.GizmoActor.md)

#### Overrides

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[Load](ue_ue.InternalToolFrameworkActor.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InternalToolFrameworkActor](ue_ue.InternalToolFrameworkActor.md).[StaticClass](ue_ue.InternalToolFrameworkActor.md#staticclass)
