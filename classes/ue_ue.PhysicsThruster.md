[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PhysicsThruster

# Class: PhysicsThruster

[ue/ue](../modules/ue_ue.md).PhysicsThruster

## Hierarchy

- [`RigidBodyBase`](ue_ue.RigidBodyBase.md)

  ↳ **`PhysicsThruster`**

## Table of contents

### Constructors

- [constructor](ue_ue.PhysicsThruster.md#constructor)

### Properties

- [ActorLabel](ue_ue.PhysicsThruster.md#actorlabel)
- [ArrowComponent](ue_ue.PhysicsThruster.md#arrowcomponent)
- [AttachmentReplication](ue_ue.PhysicsThruster.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.PhysicsThruster.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.PhysicsThruster.md#blueprintcreatedcomponents)
- [Children](ue_ue.PhysicsThruster.md#children)
- [ControllingMatineeActors](ue_ue.PhysicsThruster.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.PhysicsThruster.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.PhysicsThruster.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.PhysicsThruster.md#folderpath)
- [GroupActor](ue_ue.PhysicsThruster.md#groupactor)
- [HiddenEditorViews](ue_ue.PhysicsThruster.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.PhysicsThruster.md#initiallifespan)
- [InputComponent](ue_ue.PhysicsThruster.md#inputcomponent)
- [InputPriority](ue_ue.PhysicsThruster.md#inputpriority)
- [InstanceComponents](ue_ue.PhysicsThruster.md#instancecomponents)
- [Instigator](ue_ue.PhysicsThruster.md#instigator)
- [Layers](ue_ue.PhysicsThruster.md#layers)
- [MinNetUpdateFrequency](ue_ue.PhysicsThruster.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.PhysicsThruster.md#netculldistancesquared)
- [NetDormancy](ue_ue.PhysicsThruster.md#netdormancy)
- [NetDriverName](ue_ue.PhysicsThruster.md#netdrivername)
- [NetPriority](ue_ue.PhysicsThruster.md#netpriority)
- [NetTag](ue_ue.PhysicsThruster.md#nettag)
- [NetUpdateFrequency](ue_ue.PhysicsThruster.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.PhysicsThruster.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.PhysicsThruster.md#onactorendoverlap)
- [OnActorHit](ue_ue.PhysicsThruster.md#onactorhit)
- [OnBeginCursorOver](ue_ue.PhysicsThruster.md#onbegincursorover)
- [OnClicked](ue_ue.PhysicsThruster.md#onclicked)
- [OnDestroyed](ue_ue.PhysicsThruster.md#ondestroyed)
- [OnEndCursorOver](ue_ue.PhysicsThruster.md#onendcursorover)
- [OnEndPlay](ue_ue.PhysicsThruster.md#onendplay)
- [OnInputTouchBegin](ue_ue.PhysicsThruster.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.PhysicsThruster.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.PhysicsThruster.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.PhysicsThruster.md#oninputtouchleave)
- [OnReleased](ue_ue.PhysicsThruster.md#onreleased)
- [OnTakeAnyDamage](ue_ue.PhysicsThruster.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.PhysicsThruster.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.PhysicsThruster.md#ontakeradialdamage)
- [Owner](ue_ue.PhysicsThruster.md#owner)
- [ParentComponent](ue_ue.PhysicsThruster.md#parentcomponent)
- [ParentComponentActor](ue_ue.PhysicsThruster.md#parentcomponentactor)
- [PivotOffset](ue_ue.PhysicsThruster.md#pivotoffset)
- [PrimaryActorTick](ue_ue.PhysicsThruster.md#primaryactortick)
- [RemoteRole](ue_ue.PhysicsThruster.md#remoterole)
- [ReplicatedMovement](ue_ue.PhysicsThruster.md#replicatedmovement)
- [Role](ue_ue.PhysicsThruster.md#role)
- [RootComponent](ue_ue.PhysicsThruster.md#rootcomponent)
- [SpawnCollisionHandlingMethod](ue_ue.PhysicsThruster.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.PhysicsThruster.md#spritescale)
- [Tags](ue_ue.PhysicsThruster.md#tags)
- [ThrusterComponent](ue_ue.PhysicsThruster.md#thrustercomponent)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.PhysicsThruster.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.PhysicsThruster.md#__tid_actor__)
- [\_\_tid\_Object\_\_](ue_ue.PhysicsThruster.md#__tid_object__)
- [\_\_tid\_PhysicsThruster\_\_](ue_ue.PhysicsThruster.md#__tid_physicsthruster__)
- [\_\_tid\_RigidBodyBase\_\_](ue_ue.PhysicsThruster.md#__tid_rigidbodybase__)
- [bActorEnableCollision](ue_ue.PhysicsThruster.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.PhysicsThruster.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.PhysicsThruster.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.PhysicsThruster.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.PhysicsThruster.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.PhysicsThruster.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.PhysicsThruster.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.PhysicsThruster.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.PhysicsThruster.md#bblockinput)
- [bCanBeDamaged](ue_ue.PhysicsThruster.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.PhysicsThruster.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.PhysicsThruster.md#bcollidewhenplacing)
- [bEditable](ue_ue.PhysicsThruster.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.PhysicsThruster.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.PhysicsThruster.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.PhysicsThruster.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.PhysicsThruster.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.PhysicsThruster.md#bhidden)
- [bHiddenEd](ue_ue.PhysicsThruster.md#bhiddened)
- [bHiddenEdLayer](ue_ue.PhysicsThruster.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.PhysicsThruster.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.PhysicsThruster.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.PhysicsThruster.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.PhysicsThruster.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.PhysicsThruster.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.PhysicsThruster.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.PhysicsThruster.md#blocklocation)
- [bNetLoadOnClient](ue_ue.PhysicsThruster.md#bnetloadonclient)
- [bNetStartup](ue_ue.PhysicsThruster.md#bnetstartup)
- [bNetTemporary](ue_ue.PhysicsThruster.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.PhysicsThruster.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.PhysicsThruster.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.PhysicsThruster.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.PhysicsThruster.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.PhysicsThruster.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.PhysicsThruster.md#breplayrewindable)
- [bReplicateMovement](ue_ue.PhysicsThruster.md#breplicatemovement)
- [bReplicates](ue_ue.PhysicsThruster.md#breplicates)
- [bTearOff](ue_ue.PhysicsThruster.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.PhysicsThruster.md#actorhastag)
- [AddComponent](ue_ue.PhysicsThruster.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.PhysicsThruster.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PhysicsThruster.md#addtickprerequisitecomponent)
- [CreateDefaultSubobject](ue_ue.PhysicsThruster.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.PhysicsThruster.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.PhysicsThruster.md#disableinput)
- [EnableInput](ue_ue.PhysicsThruster.md#enableinput)
- [ExecuteUbergraph](ue_ue.PhysicsThruster.md#executeubergraph)
- [FlushNetDormancy](ue_ue.PhysicsThruster.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.PhysicsThruster.md#forcenetupdate)
- [GetActorBounds](ue_ue.PhysicsThruster.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.PhysicsThruster.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.PhysicsThruster.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.PhysicsThruster.md#getactorforwardvector)
- [GetActorLabel](ue_ue.PhysicsThruster.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.PhysicsThruster.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.PhysicsThruster.md#getactorrightvector)
- [GetActorScale3D](ue_ue.PhysicsThruster.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.PhysicsThruster.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.PhysicsThruster.md#getactortimedilation)
- [GetActorUpVector](ue_ue.PhysicsThruster.md#getactorupvector)
- [GetAllChildActors](ue_ue.PhysicsThruster.md#getallchildactors)
- [GetAttachParentActor](ue_ue.PhysicsThruster.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.PhysicsThruster.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.PhysicsThruster.md#getattachedactors)
- [GetClass](ue_ue.PhysicsThruster.md#getclass)
- [GetComponentByClass](ue_ue.PhysicsThruster.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.PhysicsThruster.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.PhysicsThruster.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.PhysicsThruster.md#getdistanceto)
- [GetDotProductTo](ue_ue.PhysicsThruster.md#getdotproductto)
- [GetFolderPath](ue_ue.PhysicsThruster.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.PhysicsThruster.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.PhysicsThruster.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.PhysicsThruster.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.PhysicsThruster.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.PhysicsThruster.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.PhysicsThruster.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.PhysicsThruster.md#getinstigator)
- [GetInstigatorController](ue_ue.PhysicsThruster.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.PhysicsThruster.md#getlifespan)
- [GetLocalRole](ue_ue.PhysicsThruster.md#getlocalrole)
- [GetName](ue_ue.PhysicsThruster.md#getname)
- [GetOuter](ue_ue.PhysicsThruster.md#getouter)
- [GetOverlappingActors](ue_ue.PhysicsThruster.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.PhysicsThruster.md#getoverlappingcomponents)
- [GetOwner](ue_ue.PhysicsThruster.md#getowner)
- [GetParentActor](ue_ue.PhysicsThruster.md#getparentactor)
- [GetParentComponent](ue_ue.PhysicsThruster.md#getparentcomponent)
- [GetRemoteRole](ue_ue.PhysicsThruster.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.PhysicsThruster.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.PhysicsThruster.md#gettickablewhenpaused)
- [GetTransform](ue_ue.PhysicsThruster.md#gettransform)
- [GetVelocity](ue_ue.PhysicsThruster.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.PhysicsThruster.md#getverticaldistanceto)
- [GetWorld](ue_ue.PhysicsThruster.md#getworld)
- [HasAuthority](ue_ue.PhysicsThruster.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.PhysicsThruster.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.PhysicsThruster.md#isactortickenabled)
- [IsChildActor](ue_ue.PhysicsThruster.md#ischildactor)
- [IsEditable](ue_ue.PhysicsThruster.md#iseditable)
- [IsHiddenEd](ue_ue.PhysicsThruster.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.PhysicsThruster.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.PhysicsThruster.md#isoverlappingactor)
- [IsSelectable](ue_ue.PhysicsThruster.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.PhysicsThruster.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.PhysicsThruster.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.PhysicsThruster.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.PhysicsThruster.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.PhysicsThruster.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.PhysicsThruster.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.PhysicsThruster.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.PhysicsThruster.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.PhysicsThruster.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.PhysicsThruster.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.PhysicsThruster.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.PhysicsThruster.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.PhysicsThruster.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.PhysicsThruster.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.PhysicsThruster.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.PhysicsThruster.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.PhysicsThruster.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.PhysicsThruster.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.PhysicsThruster.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.PhysicsThruster.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.PhysicsThruster.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.PhysicsThruster.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.PhysicsThruster.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.PhysicsThruster.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.PhysicsThruster.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.PhysicsThruster.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.PhysicsThruster.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.PhysicsThruster.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.PhysicsThruster.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.PhysicsThruster.md#makemidformaterial)
- [MakeNoise](ue_ue.PhysicsThruster.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.PhysicsThruster.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.PhysicsThruster.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.PhysicsThruster.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.PhysicsThruster.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.PhysicsThruster.md#onrep_replicatedmovement)
- [PrestreamTextures](ue_ue.PhysicsThruster.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.PhysicsThruster.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.PhysicsThruster.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.PhysicsThruster.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.PhysicsThruster.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.PhysicsThruster.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.PhysicsThruster.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.PhysicsThruster.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.PhysicsThruster.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.PhysicsThruster.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.PhysicsThruster.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.PhysicsThruster.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.PhysicsThruster.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.PhysicsThruster.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.PhysicsThruster.md#receiveendplay)
- [ReceiveHit](ue_ue.PhysicsThruster.md#receivehit)
- [ReceivePointDamage](ue_ue.PhysicsThruster.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.PhysicsThruster.md#receiveradialdamage)
- [ReceiveTick](ue_ue.PhysicsThruster.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.PhysicsThruster.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PhysicsThruster.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.PhysicsThruster.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.PhysicsThruster.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.PhysicsThruster.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.PhysicsThruster.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.PhysicsThruster.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.PhysicsThruster.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.PhysicsThruster.md#setactortickinterval)
- [SetFolderPath](ue_ue.PhysicsThruster.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.PhysicsThruster.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.PhysicsThruster.md#setlifespan)
- [SetNetDormancy](ue_ue.PhysicsThruster.md#setnetdormancy)
- [SetOwner](ue_ue.PhysicsThruster.md#setowner)
- [SetReplicateMovement](ue_ue.PhysicsThruster.md#setreplicatemovement)
- [SetReplicates](ue_ue.PhysicsThruster.md#setreplicates)
- [SetTickGroup](ue_ue.PhysicsThruster.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PhysicsThruster.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.PhysicsThruster.md#snaprootcomponentto)
- [TearOff](ue_ue.PhysicsThruster.md#tearoff)
- [UserConstructionScript](ue_ue.PhysicsThruster.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.PhysicsThruster.md#wasrecentlyrendered)
- [Find](ue_ue.PhysicsThruster.md#find)
- [Load](ue_ue.PhysicsThruster.md#load)
- [StaticClass](ue_ue.PhysicsThruster.md#staticclass)

## Constructors

### constructor

• **new PhysicsThruster**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[RigidBodyBase](ue_ue.RigidBodyBase.md).[constructor](ue_ue.RigidBodyBase.md#constructor)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ActorLabel](ue_ue.RigidBodyBase.md#actorlabel)

___

### ArrowComponent

• **ArrowComponent**: [`ArrowComponent`](ue_ue.ArrowComponent.md)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[AttachmentReplication](ue_ue.RigidBodyBase.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[AutoReceiveInput](ue_ue.RigidBodyBase.md#autoreceiveinput)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[BlueprintCreatedComponents](ue_ue.RigidBodyBase.md#blueprintcreatedcomponents)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[Children](ue_ue.RigidBodyBase.md#children)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ControllingMatineeActors](ue_ue.RigidBodyBase.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[CustomTimeDilation](ue_ue.RigidBodyBase.md#customtimedilation)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.RigidBodyBase.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[FolderPath](ue_ue.RigidBodyBase.md#folderpath)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GroupActor](ue_ue.RigidBodyBase.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[HiddenEditorViews](ue_ue.RigidBodyBase.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[InitialLifeSpan](ue_ue.RigidBodyBase.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[InputComponent](ue_ue.RigidBodyBase.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[InputPriority](ue_ue.RigidBodyBase.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[InstanceComponents](ue_ue.RigidBodyBase.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[Instigator](ue_ue.RigidBodyBase.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[Layers](ue_ue.RigidBodyBase.md#layers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[MinNetUpdateFrequency](ue_ue.RigidBodyBase.md#minnetupdatefrequency)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[NetCullDistanceSquared](ue_ue.RigidBodyBase.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[NetDormancy](ue_ue.RigidBodyBase.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[NetDriverName](ue_ue.RigidBodyBase.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[NetPriority](ue_ue.RigidBodyBase.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[NetTag](ue_ue.RigidBodyBase.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[NetUpdateFrequency](ue_ue.RigidBodyBase.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnActorBeginOverlap](ue_ue.RigidBodyBase.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnActorEndOverlap](ue_ue.RigidBodyBase.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnActorHit](ue_ue.RigidBodyBase.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnBeginCursorOver](ue_ue.RigidBodyBase.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnClicked](ue_ue.RigidBodyBase.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnDestroyed](ue_ue.RigidBodyBase.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnEndCursorOver](ue_ue.RigidBodyBase.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnEndPlay](ue_ue.RigidBodyBase.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnInputTouchBegin](ue_ue.RigidBodyBase.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnInputTouchEnd](ue_ue.RigidBodyBase.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnInputTouchEnter](ue_ue.RigidBodyBase.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnInputTouchLeave](ue_ue.RigidBodyBase.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnReleased](ue_ue.RigidBodyBase.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnTakeAnyDamage](ue_ue.RigidBodyBase.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnTakePointDamage](ue_ue.RigidBodyBase.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnTakeRadialDamage](ue_ue.RigidBodyBase.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[Owner](ue_ue.RigidBodyBase.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ParentComponent](ue_ue.RigidBodyBase.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ParentComponentActor](ue_ue.RigidBodyBase.md#parentcomponentactor)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[PivotOffset](ue_ue.RigidBodyBase.md#pivotoffset)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[PrimaryActorTick](ue_ue.RigidBodyBase.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[RemoteRole](ue_ue.RigidBodyBase.md#remoterole)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReplicatedMovement](ue_ue.RigidBodyBase.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[Role](ue_ue.RigidBodyBase.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[RootComponent](ue_ue.RigidBodyBase.md#rootcomponent)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SpawnCollisionHandlingMethod](ue_ue.RigidBodyBase.md#spawncollisionhandlingmethod)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SpriteScale](ue_ue.RigidBodyBase.md#spritescale)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[Tags](ue_ue.RigidBodyBase.md#tags)

___

### ThrusterComponent

• **ThrusterComponent**: [`PhysicsThrusterComponent`](ue_ue.PhysicsThrusterComponent.md)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.RigidBodyBase.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[__tid_Actor__](ue_ue.RigidBodyBase.md#__tid_actor__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[__tid_Object__](ue_ue.RigidBodyBase.md#__tid_object__)

___

### \_\_tid\_PhysicsThruster\_\_

• **\_\_tid\_PhysicsThruster\_\_**: `boolean`

___

### \_\_tid\_RigidBodyBase\_\_

• **\_\_tid\_RigidBodyBase\_\_**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[__tid_RigidBodyBase__](ue_ue.RigidBodyBase.md#__tid_rigidbodybase__)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bActorEnableCollision](ue_ue.RigidBodyBase.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bActorIsBeingDestroyed](ue_ue.RigidBodyBase.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bActorLabelEditable](ue_ue.RigidBodyBase.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bActorSeamlessTraveled](ue_ue.RigidBodyBase.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.RigidBodyBase.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bAllowTickBeforeBeginPlay](ue_ue.RigidBodyBase.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bAlwaysRelevant](ue_ue.RigidBodyBase.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bAutoDestroyWhenFinished](ue_ue.RigidBodyBase.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bBlockInput](ue_ue.RigidBodyBase.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bCanBeDamaged](ue_ue.RigidBodyBase.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bCanBeInCluster](ue_ue.RigidBodyBase.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bCollideWhenPlacing](ue_ue.RigidBodyBase.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bEditable](ue_ue.RigidBodyBase.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bEnableAutoLODGeneration](ue_ue.RigidBodyBase.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bExchangedRoles](ue_ue.RigidBodyBase.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bFindCameraComponentWhenViewTarget](ue_ue.RigidBodyBase.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.RigidBodyBase.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bHidden](ue_ue.RigidBodyBase.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bHiddenEd](ue_ue.RigidBodyBase.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bHiddenEdLayer](ue_ue.RigidBodyBase.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bHiddenEdLevel](ue_ue.RigidBodyBase.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bHiddenEdTemporary](ue_ue.RigidBodyBase.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bIgnoresOriginShifting](ue_ue.RigidBodyBase.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bIsEditorOnlyActor](ue_ue.RigidBodyBase.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bIsEditorPreviewActor](ue_ue.RigidBodyBase.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bListedInSceneOutliner](ue_ue.RigidBodyBase.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bLockLocation](ue_ue.RigidBodyBase.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bNetLoadOnClient](ue_ue.RigidBodyBase.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bNetStartup](ue_ue.RigidBodyBase.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bNetTemporary](ue_ue.RigidBodyBase.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bNetUseOwnerRelevancy](ue_ue.RigidBodyBase.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bOnlyRelevantToOwner](ue_ue.RigidBodyBase.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bOptimizeBPComponentData](ue_ue.RigidBodyBase.md#boptimizebpcomponentdata)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bRelevantForLevelBounds](ue_ue.RigidBodyBase.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bRelevantForNetworkReplays](ue_ue.RigidBodyBase.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bReplayRewindable](ue_ue.RigidBodyBase.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bReplicateMovement](ue_ue.RigidBodyBase.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bReplicates](ue_ue.RigidBodyBase.md#breplicates)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bTearOff](ue_ue.RigidBodyBase.md#btearoff)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ActorHasTag](ue_ue.RigidBodyBase.md#actorhastag)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[AddComponent](ue_ue.RigidBodyBase.md#addcomponent)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[AddTickPrerequisiteActor](ue_ue.RigidBodyBase.md#addtickprerequisiteactor)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[AddTickPrerequisiteComponent](ue_ue.RigidBodyBase.md#addtickprerequisitecomponent)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[CreateDefaultSubobject](ue_ue.RigidBodyBase.md#createdefaultsubobject)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[DetachRootComponentFromParent](ue_ue.RigidBodyBase.md#detachrootcomponentfromparent)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[DisableInput](ue_ue.RigidBodyBase.md#disableinput)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[EnableInput](ue_ue.RigidBodyBase.md#enableinput)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ExecuteUbergraph](ue_ue.RigidBodyBase.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[FlushNetDormancy](ue_ue.RigidBodyBase.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ForceNetUpdate](ue_ue.RigidBodyBase.md#forcenetupdate)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorBounds](ue_ue.RigidBodyBase.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorEnableCollision](ue_ue.RigidBodyBase.md#getactorenablecollision)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorEyesViewPoint](ue_ue.RigidBodyBase.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorForwardVector](ue_ue.RigidBodyBase.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorLabel](ue_ue.RigidBodyBase.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorRelativeScale3D](ue_ue.RigidBodyBase.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorRightVector](ue_ue.RigidBodyBase.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorScale3D](ue_ue.RigidBodyBase.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorTickInterval](ue_ue.RigidBodyBase.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorTimeDilation](ue_ue.RigidBodyBase.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorUpVector](ue_ue.RigidBodyBase.md#getactorupvector)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetAllChildActors](ue_ue.RigidBodyBase.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetAttachParentActor](ue_ue.RigidBodyBase.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetAttachParentSocketName](ue_ue.RigidBodyBase.md#getattachparentsocketname)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetAttachedActors](ue_ue.RigidBodyBase.md#getattachedactors)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetClass](ue_ue.RigidBodyBase.md#getclass)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetComponentByClass](ue_ue.RigidBodyBase.md#getcomponentbyclass)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetComponentsByInterface](ue_ue.RigidBodyBase.md#getcomponentsbyinterface)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetComponentsByTag](ue_ue.RigidBodyBase.md#getcomponentsbytag)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetDistanceTo](ue_ue.RigidBodyBase.md#getdistanceto)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetDotProductTo](ue_ue.RigidBodyBase.md#getdotproductto)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetFolderPath](ue_ue.RigidBodyBase.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetGameTimeSinceCreation](ue_ue.RigidBodyBase.md#getgametimesincecreation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetHorizontalDistanceTo](ue_ue.RigidBodyBase.md#gethorizontaldistanceto)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetHorizontalDotProductTo](ue_ue.RigidBodyBase.md#gethorizontaldotproductto)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetInputAxisKeyValue](ue_ue.RigidBodyBase.md#getinputaxiskeyvalue)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetInputAxisValue](ue_ue.RigidBodyBase.md#getinputaxisvalue)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetInputVectorAxisValue](ue_ue.RigidBodyBase.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetInstigator](ue_ue.RigidBodyBase.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetInstigatorController](ue_ue.RigidBodyBase.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetLifeSpan](ue_ue.RigidBodyBase.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetLocalRole](ue_ue.RigidBodyBase.md#getlocalrole)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetName](ue_ue.RigidBodyBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetOuter](ue_ue.RigidBodyBase.md#getouter)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetOverlappingActors](ue_ue.RigidBodyBase.md#getoverlappingactors)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetOverlappingComponents](ue_ue.RigidBodyBase.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetOwner](ue_ue.RigidBodyBase.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetParentActor](ue_ue.RigidBodyBase.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetParentComponent](ue_ue.RigidBodyBase.md#getparentcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetRemoteRole](ue_ue.RigidBodyBase.md#getremoterole)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetSquaredDistanceTo](ue_ue.RigidBodyBase.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetTickableWhenPaused](ue_ue.RigidBodyBase.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetTransform](ue_ue.RigidBodyBase.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetVelocity](ue_ue.RigidBodyBase.md#getvelocity)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetVerticalDistanceTo](ue_ue.RigidBodyBase.md#getverticaldistanceto)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetWorld](ue_ue.RigidBodyBase.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[HasAuthority](ue_ue.RigidBodyBase.md#hasauthority)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsActorBeingDestroyed](ue_ue.RigidBodyBase.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsActorTickEnabled](ue_ue.RigidBodyBase.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsChildActor](ue_ue.RigidBodyBase.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsEditable](ue_ue.RigidBodyBase.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsHiddenEd](ue_ue.RigidBodyBase.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsHiddenEdAtStartup](ue_ue.RigidBodyBase.md#ishiddenedatstartup)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsOverlappingActor](ue_ue.RigidBodyBase.md#isoverlappingactor)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsSelectable](ue_ue.RigidBodyBase.md#isselectable)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsTemporarilyHiddenInEditor](ue_ue.RigidBodyBase.md#istemporarilyhiddenineditor)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AddActorLocalOffset](ue_ue.RigidBodyBase.md#k2_addactorlocaloffset)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AddActorLocalRotation](ue_ue.RigidBodyBase.md#k2_addactorlocalrotation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AddActorLocalTransform](ue_ue.RigidBodyBase.md#k2_addactorlocaltransform)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AddActorWorldOffset](ue_ue.RigidBodyBase.md#k2_addactorworldoffset)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AddActorWorldRotation](ue_ue.RigidBodyBase.md#k2_addactorworldrotation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AddActorWorldTransform](ue_ue.RigidBodyBase.md#k2_addactorworldtransform)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AttachRootComponentTo](ue_ue.RigidBodyBase.md#k2_attachrootcomponentto)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AttachRootComponentToActor](ue_ue.RigidBodyBase.md#k2_attachrootcomponenttoactor)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AttachToActor](ue_ue.RigidBodyBase.md#k2_attachtoactor)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AttachToComponent](ue_ue.RigidBodyBase.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_DestroyActor](ue_ue.RigidBodyBase.md#k2_destroyactor)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_DestroyComponent](ue_ue.RigidBodyBase.md#k2_destroycomponent)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_DetachFromActor](ue_ue.RigidBodyBase.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_GetActorLocation](ue_ue.RigidBodyBase.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_GetActorRotation](ue_ue.RigidBodyBase.md#k2_getactorrotation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_GetComponentsByClass](ue_ue.RigidBodyBase.md#k2_getcomponentsbyclass)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_GetRootComponent](ue_ue.RigidBodyBase.md#k2_getrootcomponent)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_OnBecomeViewTarget](ue_ue.RigidBodyBase.md#k2_onbecomeviewtarget)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_OnEndViewTarget](ue_ue.RigidBodyBase.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_OnReset](ue_ue.RigidBodyBase.md#k2_onreset)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_SetActorLocation](ue_ue.RigidBodyBase.md#k2_setactorlocation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_SetActorLocationAndRotation](ue_ue.RigidBodyBase.md#k2_setactorlocationandrotation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_SetActorRelativeLocation](ue_ue.RigidBodyBase.md#k2_setactorrelativelocation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_SetActorRelativeRotation](ue_ue.RigidBodyBase.md#k2_setactorrelativerotation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_SetActorRelativeTransform](ue_ue.RigidBodyBase.md#k2_setactorrelativetransform)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_SetActorRotation](ue_ue.RigidBodyBase.md#k2_setactorrotation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_SetActorTransform](ue_ue.RigidBodyBase.md#k2_setactortransform)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_TeleportTo](ue_ue.RigidBodyBase.md#k2_teleportto)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[MakeMIDForMaterial](ue_ue.RigidBodyBase.md#makemidformaterial)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[MakeNoise](ue_ue.RigidBodyBase.md#makenoise)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnRep_AttachmentReplication](ue_ue.RigidBodyBase.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnRep_Instigator](ue_ue.RigidBodyBase.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnRep_Owner](ue_ue.RigidBodyBase.md#onrep_owner)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnRep_ReplicateMovement](ue_ue.RigidBodyBase.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnRep_ReplicatedMovement](ue_ue.RigidBodyBase.md#onrep_replicatedmovement)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[PrestreamTextures](ue_ue.RigidBodyBase.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorBeginCursorOver](ue_ue.RigidBodyBase.md#receiveactorbegincursorover)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorBeginOverlap](ue_ue.RigidBodyBase.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorEndCursorOver](ue_ue.RigidBodyBase.md#receiveactorendcursorover)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorEndOverlap](ue_ue.RigidBodyBase.md#receiveactorendoverlap)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorOnClicked](ue_ue.RigidBodyBase.md#receiveactoronclicked)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorOnInputTouchBegin](ue_ue.RigidBodyBase.md#receiveactoroninputtouchbegin)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorOnInputTouchEnd](ue_ue.RigidBodyBase.md#receiveactoroninputtouchend)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorOnInputTouchEnter](ue_ue.RigidBodyBase.md#receiveactoroninputtouchenter)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorOnInputTouchLeave](ue_ue.RigidBodyBase.md#receiveactoroninputtouchleave)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorOnReleased](ue_ue.RigidBodyBase.md#receiveactoronreleased)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveAnyDamage](ue_ue.RigidBodyBase.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveBeginPlay](ue_ue.RigidBodyBase.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveDestroyed](ue_ue.RigidBodyBase.md#receivedestroyed)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveEndPlay](ue_ue.RigidBodyBase.md#receiveendplay)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveHit](ue_ue.RigidBodyBase.md#receivehit)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceivePointDamage](ue_ue.RigidBodyBase.md#receivepointdamage)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveRadialDamage](ue_ue.RigidBodyBase.md#receiveradialdamage)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveTick](ue_ue.RigidBodyBase.md#receivetick)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[RemoveTickPrerequisiteActor](ue_ue.RigidBodyBase.md#removetickprerequisiteactor)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[RemoveTickPrerequisiteComponent](ue_ue.RigidBodyBase.md#removetickprerequisitecomponent)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetActorEnableCollision](ue_ue.RigidBodyBase.md#setactorenablecollision)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetActorHiddenInGame](ue_ue.RigidBodyBase.md#setactorhiddeningame)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetActorLabel](ue_ue.RigidBodyBase.md#setactorlabel)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetActorRelativeScale3D](ue_ue.RigidBodyBase.md#setactorrelativescale3d)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetActorScale3D](ue_ue.RigidBodyBase.md#setactorscale3d)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetActorTickEnabled](ue_ue.RigidBodyBase.md#setactortickenabled)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetActorTickInterval](ue_ue.RigidBodyBase.md#setactortickinterval)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetFolderPath](ue_ue.RigidBodyBase.md#setfolderpath)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetIsTemporarilyHiddenInEditor](ue_ue.RigidBodyBase.md#setistemporarilyhiddenineditor)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetLifeSpan](ue_ue.RigidBodyBase.md#setlifespan)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetNetDormancy](ue_ue.RigidBodyBase.md#setnetdormancy)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetOwner](ue_ue.RigidBodyBase.md#setowner)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetReplicateMovement](ue_ue.RigidBodyBase.md#setreplicatemovement)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetReplicates](ue_ue.RigidBodyBase.md#setreplicates)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetTickGroup](ue_ue.RigidBodyBase.md#settickgroup)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetTickableWhenPaused](ue_ue.RigidBodyBase.md#settickablewhenpaused)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SnapRootComponentTo](ue_ue.RigidBodyBase.md#snaprootcomponentto)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[TearOff](ue_ue.RigidBodyBase.md#tearoff)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[UserConstructionScript](ue_ue.RigidBodyBase.md#userconstructionscript)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[WasRecentlyRendered](ue_ue.RigidBodyBase.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PhysicsThruster`](ue_ue.PhysicsThruster.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PhysicsThruster`](ue_ue.PhysicsThruster.md)

#### Overrides

[RigidBodyBase](ue_ue.RigidBodyBase.md).[Find](ue_ue.RigidBodyBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PhysicsThruster`](ue_ue.PhysicsThruster.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PhysicsThruster`](ue_ue.PhysicsThruster.md)

#### Overrides

[RigidBodyBase](ue_ue.RigidBodyBase.md).[Load](ue_ue.RigidBodyBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[RigidBodyBase](ue_ue.RigidBodyBase.md).[StaticClass](ue_ue.RigidBodyBase.md#staticclass)
