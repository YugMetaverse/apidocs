[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AbstractNavData

# Class: AbstractNavData

[ue/ue](../modules/ue_ue.md).AbstractNavData

## Hierarchy

- [`NavigationData`](ue_ue.NavigationData.md)

  ↳ **`AbstractNavData`**

## Table of contents

### Constructors

- [constructor](ue_ue.AbstractNavData.md#constructor)

### Properties

- [ActorLabel](ue_ue.AbstractNavData.md#actorlabel)
- [AttachmentReplication](ue_ue.AbstractNavData.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.AbstractNavData.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.AbstractNavData.md#blueprintcreatedcomponents)
- [Children](ue_ue.AbstractNavData.md#children)
- [ControllingMatineeActors](ue_ue.AbstractNavData.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.AbstractNavData.md#customtimedilation)
- [DataVersion](ue_ue.AbstractNavData.md#dataversion)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.AbstractNavData.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.AbstractNavData.md#folderpath)
- [GroupActor](ue_ue.AbstractNavData.md#groupactor)
- [HiddenEditorViews](ue_ue.AbstractNavData.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.AbstractNavData.md#initiallifespan)
- [InputComponent](ue_ue.AbstractNavData.md#inputcomponent)
- [InputPriority](ue_ue.AbstractNavData.md#inputpriority)
- [InstanceComponents](ue_ue.AbstractNavData.md#instancecomponents)
- [Instigator](ue_ue.AbstractNavData.md#instigator)
- [Layers](ue_ue.AbstractNavData.md#layers)
- [MinNetUpdateFrequency](ue_ue.AbstractNavData.md#minnetupdatefrequency)
- [NavDataConfig](ue_ue.AbstractNavData.md#navdataconfig)
- [NetCullDistanceSquared](ue_ue.AbstractNavData.md#netculldistancesquared)
- [NetDormancy](ue_ue.AbstractNavData.md#netdormancy)
- [NetDriverName](ue_ue.AbstractNavData.md#netdrivername)
- [NetPriority](ue_ue.AbstractNavData.md#netpriority)
- [NetTag](ue_ue.AbstractNavData.md#nettag)
- [NetUpdateFrequency](ue_ue.AbstractNavData.md#netupdatefrequency)
- [ObservedPathsTickInterval](ue_ue.AbstractNavData.md#observedpathstickinterval)
- [OnActorBeginOverlap](ue_ue.AbstractNavData.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.AbstractNavData.md#onactorendoverlap)
- [OnActorHit](ue_ue.AbstractNavData.md#onactorhit)
- [OnBeginCursorOver](ue_ue.AbstractNavData.md#onbegincursorover)
- [OnClicked](ue_ue.AbstractNavData.md#onclicked)
- [OnDestroyed](ue_ue.AbstractNavData.md#ondestroyed)
- [OnEndCursorOver](ue_ue.AbstractNavData.md#onendcursorover)
- [OnEndPlay](ue_ue.AbstractNavData.md#onendplay)
- [OnInputTouchBegin](ue_ue.AbstractNavData.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.AbstractNavData.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.AbstractNavData.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.AbstractNavData.md#oninputtouchleave)
- [OnReleased](ue_ue.AbstractNavData.md#onreleased)
- [OnTakeAnyDamage](ue_ue.AbstractNavData.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.AbstractNavData.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.AbstractNavData.md#ontakeradialdamage)
- [Owner](ue_ue.AbstractNavData.md#owner)
- [ParentComponent](ue_ue.AbstractNavData.md#parentcomponent)
- [ParentComponentActor](ue_ue.AbstractNavData.md#parentcomponentactor)
- [PivotOffset](ue_ue.AbstractNavData.md#pivotoffset)
- [PrimaryActorTick](ue_ue.AbstractNavData.md#primaryactortick)
- [RemoteRole](ue_ue.AbstractNavData.md#remoterole)
- [RenderingComp](ue_ue.AbstractNavData.md#renderingcomp)
- [ReplicatedMovement](ue_ue.AbstractNavData.md#replicatedmovement)
- [Role](ue_ue.AbstractNavData.md#role)
- [RootComponent](ue_ue.AbstractNavData.md#rootcomponent)
- [RuntimeGeneration](ue_ue.AbstractNavData.md#runtimegeneration)
- [SpawnCollisionHandlingMethod](ue_ue.AbstractNavData.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.AbstractNavData.md#spritescale)
- [SupportedAreas](ue_ue.AbstractNavData.md#supportedareas)
- [Tags](ue_ue.AbstractNavData.md#tags)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.AbstractNavData.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_AbstractNavData\_\_](ue_ue.AbstractNavData.md#__tid_abstractnavdata__)
- [\_\_tid\_Actor\_\_](ue_ue.AbstractNavData.md#__tid_actor__)
- [\_\_tid\_NavigationData\_\_](ue_ue.AbstractNavData.md#__tid_navigationdata__)
- [\_\_tid\_Object\_\_](ue_ue.AbstractNavData.md#__tid_object__)
- [bActorEnableCollision](ue_ue.AbstractNavData.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.AbstractNavData.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.AbstractNavData.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.AbstractNavData.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.AbstractNavData.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.AbstractNavData.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.AbstractNavData.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.AbstractNavData.md#bautodestroywhenfinished)
- [bAutoDestroyWhenNoNavigation](ue_ue.AbstractNavData.md#bautodestroywhennonavigation)
- [bBlockInput](ue_ue.AbstractNavData.md#bblockinput)
- [bCanBeDamaged](ue_ue.AbstractNavData.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.AbstractNavData.md#bcanbeincluster)
- [bCanBeMainNavData](ue_ue.AbstractNavData.md#bcanbemainnavdata)
- [bCanSpawnOnRebuild](ue_ue.AbstractNavData.md#bcanspawnonrebuild)
- [bCollideWhenPlacing](ue_ue.AbstractNavData.md#bcollidewhenplacing)
- [bEditable](ue_ue.AbstractNavData.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.AbstractNavData.md#benableautolodgeneration)
- [bEnableDrawing](ue_ue.AbstractNavData.md#benabledrawing)
- [bExchangedRoles](ue_ue.AbstractNavData.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.AbstractNavData.md#bfindcameracomponentwhenviewtarget)
- [bForceRebuildOnLoad](ue_ue.AbstractNavData.md#bforcerebuildonload)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.AbstractNavData.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.AbstractNavData.md#bhidden)
- [bHiddenEd](ue_ue.AbstractNavData.md#bhiddened)
- [bHiddenEdLayer](ue_ue.AbstractNavData.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.AbstractNavData.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.AbstractNavData.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.AbstractNavData.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.AbstractNavData.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.AbstractNavData.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.AbstractNavData.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.AbstractNavData.md#blocklocation)
- [bNetLoadOnClient](ue_ue.AbstractNavData.md#bnetloadonclient)
- [bNetStartup](ue_ue.AbstractNavData.md#bnetstartup)
- [bNetTemporary](ue_ue.AbstractNavData.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.AbstractNavData.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.AbstractNavData.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.AbstractNavData.md#boptimizebpcomponentdata)
- [bRebuildAtRuntime](ue_ue.AbstractNavData.md#brebuildatruntime)
- [bRelevantForLevelBounds](ue_ue.AbstractNavData.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.AbstractNavData.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.AbstractNavData.md#breplayrewindable)
- [bReplicateMovement](ue_ue.AbstractNavData.md#breplicatemovement)
- [bReplicates](ue_ue.AbstractNavData.md#breplicates)
- [bTearOff](ue_ue.AbstractNavData.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.AbstractNavData.md#actorhastag)
- [AddComponent](ue_ue.AbstractNavData.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.AbstractNavData.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.AbstractNavData.md#addtickprerequisitecomponent)
- [CreateDefaultSubobject](ue_ue.AbstractNavData.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.AbstractNavData.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.AbstractNavData.md#disableinput)
- [EnableInput](ue_ue.AbstractNavData.md#enableinput)
- [ExecuteUbergraph](ue_ue.AbstractNavData.md#executeubergraph)
- [FlushNetDormancy](ue_ue.AbstractNavData.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.AbstractNavData.md#forcenetupdate)
- [GetActorBounds](ue_ue.AbstractNavData.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.AbstractNavData.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.AbstractNavData.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.AbstractNavData.md#getactorforwardvector)
- [GetActorLabel](ue_ue.AbstractNavData.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.AbstractNavData.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.AbstractNavData.md#getactorrightvector)
- [GetActorScale3D](ue_ue.AbstractNavData.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.AbstractNavData.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.AbstractNavData.md#getactortimedilation)
- [GetActorUpVector](ue_ue.AbstractNavData.md#getactorupvector)
- [GetAllChildActors](ue_ue.AbstractNavData.md#getallchildactors)
- [GetAttachParentActor](ue_ue.AbstractNavData.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.AbstractNavData.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.AbstractNavData.md#getattachedactors)
- [GetClass](ue_ue.AbstractNavData.md#getclass)
- [GetComponentByClass](ue_ue.AbstractNavData.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.AbstractNavData.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.AbstractNavData.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.AbstractNavData.md#getdistanceto)
- [GetDotProductTo](ue_ue.AbstractNavData.md#getdotproductto)
- [GetFolderPath](ue_ue.AbstractNavData.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.AbstractNavData.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.AbstractNavData.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.AbstractNavData.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.AbstractNavData.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.AbstractNavData.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.AbstractNavData.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.AbstractNavData.md#getinstigator)
- [GetInstigatorController](ue_ue.AbstractNavData.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.AbstractNavData.md#getlifespan)
- [GetLocalRole](ue_ue.AbstractNavData.md#getlocalrole)
- [GetName](ue_ue.AbstractNavData.md#getname)
- [GetOuter](ue_ue.AbstractNavData.md#getouter)
- [GetOverlappingActors](ue_ue.AbstractNavData.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.AbstractNavData.md#getoverlappingcomponents)
- [GetOwner](ue_ue.AbstractNavData.md#getowner)
- [GetParentActor](ue_ue.AbstractNavData.md#getparentactor)
- [GetParentComponent](ue_ue.AbstractNavData.md#getparentcomponent)
- [GetRemoteRole](ue_ue.AbstractNavData.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.AbstractNavData.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.AbstractNavData.md#gettickablewhenpaused)
- [GetTransform](ue_ue.AbstractNavData.md#gettransform)
- [GetVelocity](ue_ue.AbstractNavData.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.AbstractNavData.md#getverticaldistanceto)
- [GetWorld](ue_ue.AbstractNavData.md#getworld)
- [HasAuthority](ue_ue.AbstractNavData.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.AbstractNavData.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.AbstractNavData.md#isactortickenabled)
- [IsChildActor](ue_ue.AbstractNavData.md#ischildactor)
- [IsEditable](ue_ue.AbstractNavData.md#iseditable)
- [IsHiddenEd](ue_ue.AbstractNavData.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.AbstractNavData.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.AbstractNavData.md#isoverlappingactor)
- [IsSelectable](ue_ue.AbstractNavData.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.AbstractNavData.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.AbstractNavData.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.AbstractNavData.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.AbstractNavData.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.AbstractNavData.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.AbstractNavData.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.AbstractNavData.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.AbstractNavData.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.AbstractNavData.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.AbstractNavData.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.AbstractNavData.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.AbstractNavData.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.AbstractNavData.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.AbstractNavData.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.AbstractNavData.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.AbstractNavData.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.AbstractNavData.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.AbstractNavData.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.AbstractNavData.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.AbstractNavData.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.AbstractNavData.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.AbstractNavData.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.AbstractNavData.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.AbstractNavData.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.AbstractNavData.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.AbstractNavData.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.AbstractNavData.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.AbstractNavData.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.AbstractNavData.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.AbstractNavData.md#makemidformaterial)
- [MakeNoise](ue_ue.AbstractNavData.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.AbstractNavData.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.AbstractNavData.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.AbstractNavData.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.AbstractNavData.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.AbstractNavData.md#onrep_replicatedmovement)
- [PrestreamTextures](ue_ue.AbstractNavData.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.AbstractNavData.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.AbstractNavData.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.AbstractNavData.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.AbstractNavData.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.AbstractNavData.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.AbstractNavData.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.AbstractNavData.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.AbstractNavData.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.AbstractNavData.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.AbstractNavData.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.AbstractNavData.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.AbstractNavData.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.AbstractNavData.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.AbstractNavData.md#receiveendplay)
- [ReceiveHit](ue_ue.AbstractNavData.md#receivehit)
- [ReceivePointDamage](ue_ue.AbstractNavData.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.AbstractNavData.md#receiveradialdamage)
- [ReceiveTick](ue_ue.AbstractNavData.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.AbstractNavData.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.AbstractNavData.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.AbstractNavData.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.AbstractNavData.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.AbstractNavData.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.AbstractNavData.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.AbstractNavData.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.AbstractNavData.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.AbstractNavData.md#setactortickinterval)
- [SetFolderPath](ue_ue.AbstractNavData.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.AbstractNavData.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.AbstractNavData.md#setlifespan)
- [SetNetDormancy](ue_ue.AbstractNavData.md#setnetdormancy)
- [SetOwner](ue_ue.AbstractNavData.md#setowner)
- [SetReplicateMovement](ue_ue.AbstractNavData.md#setreplicatemovement)
- [SetReplicates](ue_ue.AbstractNavData.md#setreplicates)
- [SetTickGroup](ue_ue.AbstractNavData.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.AbstractNavData.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.AbstractNavData.md#snaprootcomponentto)
- [TearOff](ue_ue.AbstractNavData.md#tearoff)
- [UserConstructionScript](ue_ue.AbstractNavData.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.AbstractNavData.md#wasrecentlyrendered)
- [Find](ue_ue.AbstractNavData.md#find)
- [Load](ue_ue.AbstractNavData.md#load)
- [StaticClass](ue_ue.AbstractNavData.md#staticclass)

## Constructors

### constructor

• **new AbstractNavData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[NavigationData](ue_ue.NavigationData.md).[constructor](ue_ue.NavigationData.md#constructor)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ActorLabel](ue_ue.NavigationData.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[AttachmentReplication](ue_ue.NavigationData.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[AutoReceiveInput](ue_ue.NavigationData.md#autoreceiveinput)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[BlueprintCreatedComponents](ue_ue.NavigationData.md#blueprintcreatedcomponents)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[Children](ue_ue.NavigationData.md#children)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ControllingMatineeActors](ue_ue.NavigationData.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[CustomTimeDilation](ue_ue.NavigationData.md#customtimedilation)

___

### DataVersion

• **DataVersion**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[DataVersion](ue_ue.NavigationData.md#dataversion)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.NavigationData.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[FolderPath](ue_ue.NavigationData.md#folderpath)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GroupActor](ue_ue.NavigationData.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[HiddenEditorViews](ue_ue.NavigationData.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[InitialLifeSpan](ue_ue.NavigationData.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[InputComponent](ue_ue.NavigationData.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[InputPriority](ue_ue.NavigationData.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[InstanceComponents](ue_ue.NavigationData.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[Instigator](ue_ue.NavigationData.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[Layers](ue_ue.NavigationData.md#layers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[MinNetUpdateFrequency](ue_ue.NavigationData.md#minnetupdatefrequency)

___

### NavDataConfig

• **NavDataConfig**: [`NavDataConfig`](ue_ue.NavDataConfig.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[NavDataConfig](ue_ue.NavigationData.md#navdataconfig)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[NetCullDistanceSquared](ue_ue.NavigationData.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[NetDormancy](ue_ue.NavigationData.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[NetDriverName](ue_ue.NavigationData.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[NetPriority](ue_ue.NavigationData.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[NetTag](ue_ue.NavigationData.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[NetUpdateFrequency](ue_ue.NavigationData.md#netupdatefrequency)

___

### ObservedPathsTickInterval

• **ObservedPathsTickInterval**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ObservedPathsTickInterval](ue_ue.NavigationData.md#observedpathstickinterval)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnActorBeginOverlap](ue_ue.NavigationData.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnActorEndOverlap](ue_ue.NavigationData.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnActorHit](ue_ue.NavigationData.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnBeginCursorOver](ue_ue.NavigationData.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnClicked](ue_ue.NavigationData.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnDestroyed](ue_ue.NavigationData.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnEndCursorOver](ue_ue.NavigationData.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnEndPlay](ue_ue.NavigationData.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnInputTouchBegin](ue_ue.NavigationData.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnInputTouchEnd](ue_ue.NavigationData.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnInputTouchEnter](ue_ue.NavigationData.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnInputTouchLeave](ue_ue.NavigationData.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnReleased](ue_ue.NavigationData.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnTakeAnyDamage](ue_ue.NavigationData.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnTakePointDamage](ue_ue.NavigationData.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnTakeRadialDamage](ue_ue.NavigationData.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[Owner](ue_ue.NavigationData.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ParentComponent](ue_ue.NavigationData.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ParentComponentActor](ue_ue.NavigationData.md#parentcomponentactor)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[PivotOffset](ue_ue.NavigationData.md#pivotoffset)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[PrimaryActorTick](ue_ue.NavigationData.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[RemoteRole](ue_ue.NavigationData.md#remoterole)

___

### RenderingComp

• **RenderingComp**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[RenderingComp](ue_ue.NavigationData.md#renderingcomp)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ReplicatedMovement](ue_ue.NavigationData.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[Role](ue_ue.NavigationData.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[RootComponent](ue_ue.NavigationData.md#rootcomponent)

___

### RuntimeGeneration

• **RuntimeGeneration**: [`ERuntimeGenerationType`](../enums/ue_ue.ERuntimeGenerationType.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[RuntimeGeneration](ue_ue.NavigationData.md#runtimegeneration)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[SpawnCollisionHandlingMethod](ue_ue.NavigationData.md#spawncollisionhandlingmethod)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[SpriteScale](ue_ue.NavigationData.md#spritescale)

___

### SupportedAreas

• **SupportedAreas**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SupportedAreaData`](ue_ue.SupportedAreaData.md)\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[SupportedAreas](ue_ue.NavigationData.md#supportedareas)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[Tags](ue_ue.NavigationData.md#tags)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.NavigationData.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_AbstractNavData\_\_

• **\_\_tid\_AbstractNavData\_\_**: `boolean`

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[__tid_Actor__](ue_ue.NavigationData.md#__tid_actor__)

___

### \_\_tid\_NavigationData\_\_

• **\_\_tid\_NavigationData\_\_**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[__tid_NavigationData__](ue_ue.NavigationData.md#__tid_navigationdata__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[__tid_Object__](ue_ue.NavigationData.md#__tid_object__)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bActorEnableCollision](ue_ue.NavigationData.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bActorIsBeingDestroyed](ue_ue.NavigationData.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bActorLabelEditable](ue_ue.NavigationData.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bActorSeamlessTraveled](ue_ue.NavigationData.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.NavigationData.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bAllowTickBeforeBeginPlay](ue_ue.NavigationData.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bAlwaysRelevant](ue_ue.NavigationData.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bAutoDestroyWhenFinished](ue_ue.NavigationData.md#bautodestroywhenfinished)

___

### bAutoDestroyWhenNoNavigation

• **bAutoDestroyWhenNoNavigation**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bAutoDestroyWhenNoNavigation](ue_ue.NavigationData.md#bautodestroywhennonavigation)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bBlockInput](ue_ue.NavigationData.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bCanBeDamaged](ue_ue.NavigationData.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bCanBeInCluster](ue_ue.NavigationData.md#bcanbeincluster)

___

### bCanBeMainNavData

• **bCanBeMainNavData**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bCanBeMainNavData](ue_ue.NavigationData.md#bcanbemainnavdata)

___

### bCanSpawnOnRebuild

• **bCanSpawnOnRebuild**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bCanSpawnOnRebuild](ue_ue.NavigationData.md#bcanspawnonrebuild)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bCollideWhenPlacing](ue_ue.NavigationData.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bEditable](ue_ue.NavigationData.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bEnableAutoLODGeneration](ue_ue.NavigationData.md#benableautolodgeneration)

___

### bEnableDrawing

• **bEnableDrawing**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bEnableDrawing](ue_ue.NavigationData.md#benabledrawing)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bExchangedRoles](ue_ue.NavigationData.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bFindCameraComponentWhenViewTarget](ue_ue.NavigationData.md#bfindcameracomponentwhenviewtarget)

___

### bForceRebuildOnLoad

• **bForceRebuildOnLoad**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bForceRebuildOnLoad](ue_ue.NavigationData.md#bforcerebuildonload)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.NavigationData.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bHidden](ue_ue.NavigationData.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bHiddenEd](ue_ue.NavigationData.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bHiddenEdLayer](ue_ue.NavigationData.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bHiddenEdLevel](ue_ue.NavigationData.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bHiddenEdTemporary](ue_ue.NavigationData.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bIgnoresOriginShifting](ue_ue.NavigationData.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bIsEditorOnlyActor](ue_ue.NavigationData.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bIsEditorPreviewActor](ue_ue.NavigationData.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bListedInSceneOutliner](ue_ue.NavigationData.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bLockLocation](ue_ue.NavigationData.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bNetLoadOnClient](ue_ue.NavigationData.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bNetStartup](ue_ue.NavigationData.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bNetTemporary](ue_ue.NavigationData.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bNetUseOwnerRelevancy](ue_ue.NavigationData.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bOnlyRelevantToOwner](ue_ue.NavigationData.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bOptimizeBPComponentData](ue_ue.NavigationData.md#boptimizebpcomponentdata)

___

### bRebuildAtRuntime

• **bRebuildAtRuntime**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bRebuildAtRuntime](ue_ue.NavigationData.md#brebuildatruntime)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bRelevantForLevelBounds](ue_ue.NavigationData.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bRelevantForNetworkReplays](ue_ue.NavigationData.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bReplayRewindable](ue_ue.NavigationData.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bReplicateMovement](ue_ue.NavigationData.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bReplicates](ue_ue.NavigationData.md#breplicates)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[bTearOff](ue_ue.NavigationData.md#btearoff)

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

[NavigationData](ue_ue.NavigationData.md).[ActorHasTag](ue_ue.NavigationData.md#actorhastag)

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

[NavigationData](ue_ue.NavigationData.md).[AddComponent](ue_ue.NavigationData.md#addcomponent)

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

[NavigationData](ue_ue.NavigationData.md).[AddTickPrerequisiteActor](ue_ue.NavigationData.md#addtickprerequisiteactor)

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

[NavigationData](ue_ue.NavigationData.md).[AddTickPrerequisiteComponent](ue_ue.NavigationData.md#addtickprerequisitecomponent)

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

[NavigationData](ue_ue.NavigationData.md).[CreateDefaultSubobject](ue_ue.NavigationData.md#createdefaultsubobject)

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

[NavigationData](ue_ue.NavigationData.md).[DetachRootComponentFromParent](ue_ue.NavigationData.md#detachrootcomponentfromparent)

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

[NavigationData](ue_ue.NavigationData.md).[DisableInput](ue_ue.NavigationData.md#disableinput)

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

[NavigationData](ue_ue.NavigationData.md).[EnableInput](ue_ue.NavigationData.md#enableinput)

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

[NavigationData](ue_ue.NavigationData.md).[ExecuteUbergraph](ue_ue.NavigationData.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[FlushNetDormancy](ue_ue.NavigationData.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ForceNetUpdate](ue_ue.NavigationData.md#forcenetupdate)

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

[NavigationData](ue_ue.NavigationData.md).[GetActorBounds](ue_ue.NavigationData.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorEnableCollision](ue_ue.NavigationData.md#getactorenablecollision)

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

[NavigationData](ue_ue.NavigationData.md).[GetActorEyesViewPoint](ue_ue.NavigationData.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorForwardVector](ue_ue.NavigationData.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorLabel](ue_ue.NavigationData.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorRelativeScale3D](ue_ue.NavigationData.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorRightVector](ue_ue.NavigationData.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorScale3D](ue_ue.NavigationData.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorTickInterval](ue_ue.NavigationData.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorTimeDilation](ue_ue.NavigationData.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetActorUpVector](ue_ue.NavigationData.md#getactorupvector)

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

[NavigationData](ue_ue.NavigationData.md).[GetAllChildActors](ue_ue.NavigationData.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetAttachParentActor](ue_ue.NavigationData.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetAttachParentSocketName](ue_ue.NavigationData.md#getattachparentsocketname)

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

[NavigationData](ue_ue.NavigationData.md).[GetAttachedActors](ue_ue.NavigationData.md#getattachedactors)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetClass](ue_ue.NavigationData.md#getclass)

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

[NavigationData](ue_ue.NavigationData.md).[GetComponentByClass](ue_ue.NavigationData.md#getcomponentbyclass)

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

[NavigationData](ue_ue.NavigationData.md).[GetComponentsByInterface](ue_ue.NavigationData.md#getcomponentsbyinterface)

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

[NavigationData](ue_ue.NavigationData.md).[GetComponentsByTag](ue_ue.NavigationData.md#getcomponentsbytag)

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

[NavigationData](ue_ue.NavigationData.md).[GetDistanceTo](ue_ue.NavigationData.md#getdistanceto)

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

[NavigationData](ue_ue.NavigationData.md).[GetDotProductTo](ue_ue.NavigationData.md#getdotproductto)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetFolderPath](ue_ue.NavigationData.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetGameTimeSinceCreation](ue_ue.NavigationData.md#getgametimesincecreation)

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

[NavigationData](ue_ue.NavigationData.md).[GetHorizontalDistanceTo](ue_ue.NavigationData.md#gethorizontaldistanceto)

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

[NavigationData](ue_ue.NavigationData.md).[GetHorizontalDotProductTo](ue_ue.NavigationData.md#gethorizontaldotproductto)

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

[NavigationData](ue_ue.NavigationData.md).[GetInputAxisKeyValue](ue_ue.NavigationData.md#getinputaxiskeyvalue)

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

[NavigationData](ue_ue.NavigationData.md).[GetInputAxisValue](ue_ue.NavigationData.md#getinputaxisvalue)

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

[NavigationData](ue_ue.NavigationData.md).[GetInputVectorAxisValue](ue_ue.NavigationData.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetInstigator](ue_ue.NavigationData.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetInstigatorController](ue_ue.NavigationData.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetLifeSpan](ue_ue.NavigationData.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetLocalRole](ue_ue.NavigationData.md#getlocalrole)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetName](ue_ue.NavigationData.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetOuter](ue_ue.NavigationData.md#getouter)

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

[NavigationData](ue_ue.NavigationData.md).[GetOverlappingActors](ue_ue.NavigationData.md#getoverlappingactors)

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

[NavigationData](ue_ue.NavigationData.md).[GetOverlappingComponents](ue_ue.NavigationData.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetOwner](ue_ue.NavigationData.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetParentActor](ue_ue.NavigationData.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetParentComponent](ue_ue.NavigationData.md#getparentcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetRemoteRole](ue_ue.NavigationData.md#getremoterole)

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

[NavigationData](ue_ue.NavigationData.md).[GetSquaredDistanceTo](ue_ue.NavigationData.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetTickableWhenPaused](ue_ue.NavigationData.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetTransform](ue_ue.NavigationData.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetVelocity](ue_ue.NavigationData.md#getvelocity)

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

[NavigationData](ue_ue.NavigationData.md).[GetVerticalDistanceTo](ue_ue.NavigationData.md#getverticaldistanceto)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[GetWorld](ue_ue.NavigationData.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[HasAuthority](ue_ue.NavigationData.md#hasauthority)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[IsActorBeingDestroyed](ue_ue.NavigationData.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[IsActorTickEnabled](ue_ue.NavigationData.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[IsChildActor](ue_ue.NavigationData.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[IsEditable](ue_ue.NavigationData.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[IsHiddenEd](ue_ue.NavigationData.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[IsHiddenEdAtStartup](ue_ue.NavigationData.md#ishiddenedatstartup)

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

[NavigationData](ue_ue.NavigationData.md).[IsOverlappingActor](ue_ue.NavigationData.md#isoverlappingactor)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[IsSelectable](ue_ue.NavigationData.md#isselectable)

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

[NavigationData](ue_ue.NavigationData.md).[IsTemporarilyHiddenInEditor](ue_ue.NavigationData.md#istemporarilyhiddenineditor)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AddActorLocalOffset](ue_ue.NavigationData.md#k2_addactorlocaloffset)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AddActorLocalRotation](ue_ue.NavigationData.md#k2_addactorlocalrotation)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AddActorLocalTransform](ue_ue.NavigationData.md#k2_addactorlocaltransform)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AddActorWorldOffset](ue_ue.NavigationData.md#k2_addactorworldoffset)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AddActorWorldRotation](ue_ue.NavigationData.md#k2_addactorworldrotation)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AddActorWorldTransform](ue_ue.NavigationData.md#k2_addactorworldtransform)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AttachRootComponentTo](ue_ue.NavigationData.md#k2_attachrootcomponentto)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AttachRootComponentToActor](ue_ue.NavigationData.md#k2_attachrootcomponenttoactor)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AttachToActor](ue_ue.NavigationData.md#k2_attachtoactor)

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

[NavigationData](ue_ue.NavigationData.md).[K2_AttachToComponent](ue_ue.NavigationData.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[K2_DestroyActor](ue_ue.NavigationData.md#k2_destroyactor)

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

[NavigationData](ue_ue.NavigationData.md).[K2_DestroyComponent](ue_ue.NavigationData.md#k2_destroycomponent)

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

[NavigationData](ue_ue.NavigationData.md).[K2_DetachFromActor](ue_ue.NavigationData.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[K2_GetActorLocation](ue_ue.NavigationData.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[K2_GetActorRotation](ue_ue.NavigationData.md#k2_getactorrotation)

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

[NavigationData](ue_ue.NavigationData.md).[K2_GetComponentsByClass](ue_ue.NavigationData.md#k2_getcomponentsbyclass)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[K2_GetRootComponent](ue_ue.NavigationData.md#k2_getrootcomponent)

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

[NavigationData](ue_ue.NavigationData.md).[K2_OnBecomeViewTarget](ue_ue.NavigationData.md#k2_onbecomeviewtarget)

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

[NavigationData](ue_ue.NavigationData.md).[K2_OnEndViewTarget](ue_ue.NavigationData.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[K2_OnReset](ue_ue.NavigationData.md#k2_onreset)

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

[NavigationData](ue_ue.NavigationData.md).[K2_SetActorLocation](ue_ue.NavigationData.md#k2_setactorlocation)

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

[NavigationData](ue_ue.NavigationData.md).[K2_SetActorLocationAndRotation](ue_ue.NavigationData.md#k2_setactorlocationandrotation)

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

[NavigationData](ue_ue.NavigationData.md).[K2_SetActorRelativeLocation](ue_ue.NavigationData.md#k2_setactorrelativelocation)

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

[NavigationData](ue_ue.NavigationData.md).[K2_SetActorRelativeRotation](ue_ue.NavigationData.md#k2_setactorrelativerotation)

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

[NavigationData](ue_ue.NavigationData.md).[K2_SetActorRelativeTransform](ue_ue.NavigationData.md#k2_setactorrelativetransform)

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

[NavigationData](ue_ue.NavigationData.md).[K2_SetActorRotation](ue_ue.NavigationData.md#k2_setactorrotation)

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

[NavigationData](ue_ue.NavigationData.md).[K2_SetActorTransform](ue_ue.NavigationData.md#k2_setactortransform)

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

[NavigationData](ue_ue.NavigationData.md).[K2_TeleportTo](ue_ue.NavigationData.md#k2_teleportto)

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

[NavigationData](ue_ue.NavigationData.md).[MakeMIDForMaterial](ue_ue.NavigationData.md#makemidformaterial)

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

[NavigationData](ue_ue.NavigationData.md).[MakeNoise](ue_ue.NavigationData.md#makenoise)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnRep_AttachmentReplication](ue_ue.NavigationData.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnRep_Instigator](ue_ue.NavigationData.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnRep_Owner](ue_ue.NavigationData.md#onrep_owner)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnRep_ReplicateMovement](ue_ue.NavigationData.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[OnRep_ReplicatedMovement](ue_ue.NavigationData.md#onrep_replicatedmovement)

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

[NavigationData](ue_ue.NavigationData.md).[PrestreamTextures](ue_ue.NavigationData.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorBeginCursorOver](ue_ue.NavigationData.md#receiveactorbegincursorover)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorBeginOverlap](ue_ue.NavigationData.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorEndCursorOver](ue_ue.NavigationData.md#receiveactorendcursorover)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorEndOverlap](ue_ue.NavigationData.md#receiveactorendoverlap)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorOnClicked](ue_ue.NavigationData.md#receiveactoronclicked)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorOnInputTouchBegin](ue_ue.NavigationData.md#receiveactoroninputtouchbegin)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorOnInputTouchEnd](ue_ue.NavigationData.md#receiveactoroninputtouchend)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorOnInputTouchEnter](ue_ue.NavigationData.md#receiveactoroninputtouchenter)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorOnInputTouchLeave](ue_ue.NavigationData.md#receiveactoroninputtouchleave)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveActorOnReleased](ue_ue.NavigationData.md#receiveactoronreleased)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveAnyDamage](ue_ue.NavigationData.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ReceiveBeginPlay](ue_ue.NavigationData.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[ReceiveDestroyed](ue_ue.NavigationData.md#receivedestroyed)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveEndPlay](ue_ue.NavigationData.md#receiveendplay)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveHit](ue_ue.NavigationData.md#receivehit)

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

[NavigationData](ue_ue.NavigationData.md).[ReceivePointDamage](ue_ue.NavigationData.md#receivepointdamage)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveRadialDamage](ue_ue.NavigationData.md#receiveradialdamage)

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

[NavigationData](ue_ue.NavigationData.md).[ReceiveTick](ue_ue.NavigationData.md#receivetick)

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

[NavigationData](ue_ue.NavigationData.md).[RemoveTickPrerequisiteActor](ue_ue.NavigationData.md#removetickprerequisiteactor)

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

[NavigationData](ue_ue.NavigationData.md).[RemoveTickPrerequisiteComponent](ue_ue.NavigationData.md#removetickprerequisitecomponent)

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

[NavigationData](ue_ue.NavigationData.md).[SetActorEnableCollision](ue_ue.NavigationData.md#setactorenablecollision)

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

[NavigationData](ue_ue.NavigationData.md).[SetActorHiddenInGame](ue_ue.NavigationData.md#setactorhiddeningame)

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

[NavigationData](ue_ue.NavigationData.md).[SetActorLabel](ue_ue.NavigationData.md#setactorlabel)

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

[NavigationData](ue_ue.NavigationData.md).[SetActorRelativeScale3D](ue_ue.NavigationData.md#setactorrelativescale3d)

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

[NavigationData](ue_ue.NavigationData.md).[SetActorScale3D](ue_ue.NavigationData.md#setactorscale3d)

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

[NavigationData](ue_ue.NavigationData.md).[SetActorTickEnabled](ue_ue.NavigationData.md#setactortickenabled)

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

[NavigationData](ue_ue.NavigationData.md).[SetActorTickInterval](ue_ue.NavigationData.md#setactortickinterval)

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

[NavigationData](ue_ue.NavigationData.md).[SetFolderPath](ue_ue.NavigationData.md#setfolderpath)

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

[NavigationData](ue_ue.NavigationData.md).[SetIsTemporarilyHiddenInEditor](ue_ue.NavigationData.md#setistemporarilyhiddenineditor)

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

[NavigationData](ue_ue.NavigationData.md).[SetLifeSpan](ue_ue.NavigationData.md#setlifespan)

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

[NavigationData](ue_ue.NavigationData.md).[SetNetDormancy](ue_ue.NavigationData.md#setnetdormancy)

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

[NavigationData](ue_ue.NavigationData.md).[SetOwner](ue_ue.NavigationData.md#setowner)

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

[NavigationData](ue_ue.NavigationData.md).[SetReplicateMovement](ue_ue.NavigationData.md#setreplicatemovement)

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

[NavigationData](ue_ue.NavigationData.md).[SetReplicates](ue_ue.NavigationData.md#setreplicates)

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

[NavigationData](ue_ue.NavigationData.md).[SetTickGroup](ue_ue.NavigationData.md#settickgroup)

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

[NavigationData](ue_ue.NavigationData.md).[SetTickableWhenPaused](ue_ue.NavigationData.md#settickablewhenpaused)

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

[NavigationData](ue_ue.NavigationData.md).[SnapRootComponentTo](ue_ue.NavigationData.md#snaprootcomponentto)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[TearOff](ue_ue.NavigationData.md#tearoff)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[NavigationData](ue_ue.NavigationData.md).[UserConstructionScript](ue_ue.NavigationData.md#userconstructionscript)

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

[NavigationData](ue_ue.NavigationData.md).[WasRecentlyRendered](ue_ue.NavigationData.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AbstractNavData`](ue_ue.AbstractNavData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AbstractNavData`](ue_ue.AbstractNavData.md)

#### Overrides

[NavigationData](ue_ue.NavigationData.md).[Find](ue_ue.NavigationData.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AbstractNavData`](ue_ue.AbstractNavData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AbstractNavData`](ue_ue.AbstractNavData.md)

#### Overrides

[NavigationData](ue_ue.NavigationData.md).[Load](ue_ue.NavigationData.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[NavigationData](ue_ue.NavigationData.md).[StaticClass](ue_ue.NavigationData.md#staticclass)
