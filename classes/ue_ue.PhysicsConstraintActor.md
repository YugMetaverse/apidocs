[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PhysicsConstraintActor

# Class: PhysicsConstraintActor

[ue/ue](../modules/ue_ue.md).PhysicsConstraintActor

## Hierarchy

- [`RigidBodyBase`](ue_ue.RigidBodyBase.md)

  ↳ **`PhysicsConstraintActor`**

## Table of contents

### Constructors

- [constructor](ue_ue.PhysicsConstraintActor.md#constructor)

### Properties

- [ActorLabel](ue_ue.PhysicsConstraintActor.md#actorlabel)
- [AttachmentReplication](ue_ue.PhysicsConstraintActor.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.PhysicsConstraintActor.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.PhysicsConstraintActor.md#blueprintcreatedcomponents)
- [Children](ue_ue.PhysicsConstraintActor.md#children)
- [ConstraintActor1](ue_ue.PhysicsConstraintActor.md#constraintactor1)
- [ConstraintActor2](ue_ue.PhysicsConstraintActor.md#constraintactor2)
- [ConstraintComp](ue_ue.PhysicsConstraintActor.md#constraintcomp)
- [ControllingMatineeActors](ue_ue.PhysicsConstraintActor.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.PhysicsConstraintActor.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.PhysicsConstraintActor.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.PhysicsConstraintActor.md#folderpath)
- [GroupActor](ue_ue.PhysicsConstraintActor.md#groupactor)
- [HiddenEditorViews](ue_ue.PhysicsConstraintActor.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.PhysicsConstraintActor.md#initiallifespan)
- [InputComponent](ue_ue.PhysicsConstraintActor.md#inputcomponent)
- [InputPriority](ue_ue.PhysicsConstraintActor.md#inputpriority)
- [InstanceComponents](ue_ue.PhysicsConstraintActor.md#instancecomponents)
- [Instigator](ue_ue.PhysicsConstraintActor.md#instigator)
- [Layers](ue_ue.PhysicsConstraintActor.md#layers)
- [MinNetUpdateFrequency](ue_ue.PhysicsConstraintActor.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.PhysicsConstraintActor.md#netculldistancesquared)
- [NetDormancy](ue_ue.PhysicsConstraintActor.md#netdormancy)
- [NetDriverName](ue_ue.PhysicsConstraintActor.md#netdrivername)
- [NetPriority](ue_ue.PhysicsConstraintActor.md#netpriority)
- [NetTag](ue_ue.PhysicsConstraintActor.md#nettag)
- [NetUpdateFrequency](ue_ue.PhysicsConstraintActor.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.PhysicsConstraintActor.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.PhysicsConstraintActor.md#onactorendoverlap)
- [OnActorHit](ue_ue.PhysicsConstraintActor.md#onactorhit)
- [OnBeginCursorOver](ue_ue.PhysicsConstraintActor.md#onbegincursorover)
- [OnClicked](ue_ue.PhysicsConstraintActor.md#onclicked)
- [OnDestroyed](ue_ue.PhysicsConstraintActor.md#ondestroyed)
- [OnEndCursorOver](ue_ue.PhysicsConstraintActor.md#onendcursorover)
- [OnEndPlay](ue_ue.PhysicsConstraintActor.md#onendplay)
- [OnInputTouchBegin](ue_ue.PhysicsConstraintActor.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.PhysicsConstraintActor.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.PhysicsConstraintActor.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.PhysicsConstraintActor.md#oninputtouchleave)
- [OnReleased](ue_ue.PhysicsConstraintActor.md#onreleased)
- [OnTakeAnyDamage](ue_ue.PhysicsConstraintActor.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.PhysicsConstraintActor.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.PhysicsConstraintActor.md#ontakeradialdamage)
- [Owner](ue_ue.PhysicsConstraintActor.md#owner)
- [ParentComponent](ue_ue.PhysicsConstraintActor.md#parentcomponent)
- [ParentComponentActor](ue_ue.PhysicsConstraintActor.md#parentcomponentactor)
- [PivotOffset](ue_ue.PhysicsConstraintActor.md#pivotoffset)
- [PrimaryActorTick](ue_ue.PhysicsConstraintActor.md#primaryactortick)
- [RemoteRole](ue_ue.PhysicsConstraintActor.md#remoterole)
- [ReplicatedMovement](ue_ue.PhysicsConstraintActor.md#replicatedmovement)
- [Role](ue_ue.PhysicsConstraintActor.md#role)
- [RootComponent](ue_ue.PhysicsConstraintActor.md#rootcomponent)
- [SpawnCollisionHandlingMethod](ue_ue.PhysicsConstraintActor.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.PhysicsConstraintActor.md#spritescale)
- [Tags](ue_ue.PhysicsConstraintActor.md#tags)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.PhysicsConstraintActor.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.PhysicsConstraintActor.md#__tid_actor__)
- [\_\_tid\_Object\_\_](ue_ue.PhysicsConstraintActor.md#__tid_object__)
- [\_\_tid\_PhysicsConstraintActor\_\_](ue_ue.PhysicsConstraintActor.md#__tid_physicsconstraintactor__)
- [\_\_tid\_RigidBodyBase\_\_](ue_ue.PhysicsConstraintActor.md#__tid_rigidbodybase__)
- [bActorEnableCollision](ue_ue.PhysicsConstraintActor.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.PhysicsConstraintActor.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.PhysicsConstraintActor.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.PhysicsConstraintActor.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.PhysicsConstraintActor.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.PhysicsConstraintActor.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.PhysicsConstraintActor.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.PhysicsConstraintActor.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.PhysicsConstraintActor.md#bblockinput)
- [bCanBeDamaged](ue_ue.PhysicsConstraintActor.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.PhysicsConstraintActor.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.PhysicsConstraintActor.md#bcollidewhenplacing)
- [bDisableCollision](ue_ue.PhysicsConstraintActor.md#bdisablecollision)
- [bEditable](ue_ue.PhysicsConstraintActor.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.PhysicsConstraintActor.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.PhysicsConstraintActor.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.PhysicsConstraintActor.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.PhysicsConstraintActor.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.PhysicsConstraintActor.md#bhidden)
- [bHiddenEd](ue_ue.PhysicsConstraintActor.md#bhiddened)
- [bHiddenEdLayer](ue_ue.PhysicsConstraintActor.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.PhysicsConstraintActor.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.PhysicsConstraintActor.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.PhysicsConstraintActor.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.PhysicsConstraintActor.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.PhysicsConstraintActor.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.PhysicsConstraintActor.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.PhysicsConstraintActor.md#blocklocation)
- [bNetLoadOnClient](ue_ue.PhysicsConstraintActor.md#bnetloadonclient)
- [bNetStartup](ue_ue.PhysicsConstraintActor.md#bnetstartup)
- [bNetTemporary](ue_ue.PhysicsConstraintActor.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.PhysicsConstraintActor.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.PhysicsConstraintActor.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.PhysicsConstraintActor.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.PhysicsConstraintActor.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.PhysicsConstraintActor.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.PhysicsConstraintActor.md#breplayrewindable)
- [bReplicateMovement](ue_ue.PhysicsConstraintActor.md#breplicatemovement)
- [bReplicates](ue_ue.PhysicsConstraintActor.md#breplicates)
- [bTearOff](ue_ue.PhysicsConstraintActor.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.PhysicsConstraintActor.md#actorhastag)
- [AddComponent](ue_ue.PhysicsConstraintActor.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.PhysicsConstraintActor.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PhysicsConstraintActor.md#addtickprerequisitecomponent)
- [CreateDefaultSubobject](ue_ue.PhysicsConstraintActor.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.PhysicsConstraintActor.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.PhysicsConstraintActor.md#disableinput)
- [EnableInput](ue_ue.PhysicsConstraintActor.md#enableinput)
- [ExecuteUbergraph](ue_ue.PhysicsConstraintActor.md#executeubergraph)
- [FlushNetDormancy](ue_ue.PhysicsConstraintActor.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.PhysicsConstraintActor.md#forcenetupdate)
- [GetActorBounds](ue_ue.PhysicsConstraintActor.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.PhysicsConstraintActor.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.PhysicsConstraintActor.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.PhysicsConstraintActor.md#getactorforwardvector)
- [GetActorLabel](ue_ue.PhysicsConstraintActor.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.PhysicsConstraintActor.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.PhysicsConstraintActor.md#getactorrightvector)
- [GetActorScale3D](ue_ue.PhysicsConstraintActor.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.PhysicsConstraintActor.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.PhysicsConstraintActor.md#getactortimedilation)
- [GetActorUpVector](ue_ue.PhysicsConstraintActor.md#getactorupvector)
- [GetAllChildActors](ue_ue.PhysicsConstraintActor.md#getallchildactors)
- [GetAttachParentActor](ue_ue.PhysicsConstraintActor.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.PhysicsConstraintActor.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.PhysicsConstraintActor.md#getattachedactors)
- [GetClass](ue_ue.PhysicsConstraintActor.md#getclass)
- [GetComponentByClass](ue_ue.PhysicsConstraintActor.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.PhysicsConstraintActor.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.PhysicsConstraintActor.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.PhysicsConstraintActor.md#getdistanceto)
- [GetDotProductTo](ue_ue.PhysicsConstraintActor.md#getdotproductto)
- [GetFolderPath](ue_ue.PhysicsConstraintActor.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.PhysicsConstraintActor.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.PhysicsConstraintActor.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.PhysicsConstraintActor.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.PhysicsConstraintActor.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.PhysicsConstraintActor.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.PhysicsConstraintActor.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.PhysicsConstraintActor.md#getinstigator)
- [GetInstigatorController](ue_ue.PhysicsConstraintActor.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.PhysicsConstraintActor.md#getlifespan)
- [GetLocalRole](ue_ue.PhysicsConstraintActor.md#getlocalrole)
- [GetName](ue_ue.PhysicsConstraintActor.md#getname)
- [GetOuter](ue_ue.PhysicsConstraintActor.md#getouter)
- [GetOverlappingActors](ue_ue.PhysicsConstraintActor.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.PhysicsConstraintActor.md#getoverlappingcomponents)
- [GetOwner](ue_ue.PhysicsConstraintActor.md#getowner)
- [GetParentActor](ue_ue.PhysicsConstraintActor.md#getparentactor)
- [GetParentComponent](ue_ue.PhysicsConstraintActor.md#getparentcomponent)
- [GetRemoteRole](ue_ue.PhysicsConstraintActor.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.PhysicsConstraintActor.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.PhysicsConstraintActor.md#gettickablewhenpaused)
- [GetTransform](ue_ue.PhysicsConstraintActor.md#gettransform)
- [GetVelocity](ue_ue.PhysicsConstraintActor.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.PhysicsConstraintActor.md#getverticaldistanceto)
- [GetWorld](ue_ue.PhysicsConstraintActor.md#getworld)
- [HasAuthority](ue_ue.PhysicsConstraintActor.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.PhysicsConstraintActor.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.PhysicsConstraintActor.md#isactortickenabled)
- [IsChildActor](ue_ue.PhysicsConstraintActor.md#ischildactor)
- [IsEditable](ue_ue.PhysicsConstraintActor.md#iseditable)
- [IsHiddenEd](ue_ue.PhysicsConstraintActor.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.PhysicsConstraintActor.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.PhysicsConstraintActor.md#isoverlappingactor)
- [IsSelectable](ue_ue.PhysicsConstraintActor.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.PhysicsConstraintActor.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.PhysicsConstraintActor.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.PhysicsConstraintActor.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.PhysicsConstraintActor.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.PhysicsConstraintActor.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.PhysicsConstraintActor.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.PhysicsConstraintActor.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.PhysicsConstraintActor.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.PhysicsConstraintActor.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.PhysicsConstraintActor.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.PhysicsConstraintActor.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.PhysicsConstraintActor.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.PhysicsConstraintActor.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.PhysicsConstraintActor.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.PhysicsConstraintActor.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.PhysicsConstraintActor.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.PhysicsConstraintActor.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.PhysicsConstraintActor.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.PhysicsConstraintActor.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.PhysicsConstraintActor.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.PhysicsConstraintActor.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.PhysicsConstraintActor.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.PhysicsConstraintActor.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.PhysicsConstraintActor.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.PhysicsConstraintActor.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.PhysicsConstraintActor.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.PhysicsConstraintActor.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.PhysicsConstraintActor.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.PhysicsConstraintActor.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.PhysicsConstraintActor.md#makemidformaterial)
- [MakeNoise](ue_ue.PhysicsConstraintActor.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.PhysicsConstraintActor.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.PhysicsConstraintActor.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.PhysicsConstraintActor.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.PhysicsConstraintActor.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.PhysicsConstraintActor.md#onrep_replicatedmovement)
- [PrestreamTextures](ue_ue.PhysicsConstraintActor.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.PhysicsConstraintActor.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.PhysicsConstraintActor.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.PhysicsConstraintActor.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.PhysicsConstraintActor.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.PhysicsConstraintActor.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.PhysicsConstraintActor.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.PhysicsConstraintActor.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.PhysicsConstraintActor.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.PhysicsConstraintActor.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.PhysicsConstraintActor.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.PhysicsConstraintActor.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.PhysicsConstraintActor.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.PhysicsConstraintActor.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.PhysicsConstraintActor.md#receiveendplay)
- [ReceiveHit](ue_ue.PhysicsConstraintActor.md#receivehit)
- [ReceivePointDamage](ue_ue.PhysicsConstraintActor.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.PhysicsConstraintActor.md#receiveradialdamage)
- [ReceiveTick](ue_ue.PhysicsConstraintActor.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.PhysicsConstraintActor.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PhysicsConstraintActor.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.PhysicsConstraintActor.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.PhysicsConstraintActor.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.PhysicsConstraintActor.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.PhysicsConstraintActor.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.PhysicsConstraintActor.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.PhysicsConstraintActor.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.PhysicsConstraintActor.md#setactortickinterval)
- [SetFolderPath](ue_ue.PhysicsConstraintActor.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.PhysicsConstraintActor.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.PhysicsConstraintActor.md#setlifespan)
- [SetNetDormancy](ue_ue.PhysicsConstraintActor.md#setnetdormancy)
- [SetOwner](ue_ue.PhysicsConstraintActor.md#setowner)
- [SetReplicateMovement](ue_ue.PhysicsConstraintActor.md#setreplicatemovement)
- [SetReplicates](ue_ue.PhysicsConstraintActor.md#setreplicates)
- [SetTickGroup](ue_ue.PhysicsConstraintActor.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PhysicsConstraintActor.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.PhysicsConstraintActor.md#snaprootcomponentto)
- [TearOff](ue_ue.PhysicsConstraintActor.md#tearoff)
- [UserConstructionScript](ue_ue.PhysicsConstraintActor.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.PhysicsConstraintActor.md#wasrecentlyrendered)
- [Find](ue_ue.PhysicsConstraintActor.md#find)
- [Load](ue_ue.PhysicsConstraintActor.md#load)
- [StaticClass](ue_ue.PhysicsConstraintActor.md#staticclass)

## Constructors

### constructor

• **new PhysicsConstraintActor**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[RigidBodyBase](ue_ue.RigidBodyBase.md).[constructor](ue_ue.RigidBodyBase.md#constructor)

#### Defined in

[ue/ue.d.ts:57509](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57509)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ActorLabel](ue_ue.RigidBodyBase.md#actorlabel)

#### Defined in

[ue/ue.d.ts:13176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13176)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[AttachmentReplication](ue_ue.RigidBodyBase.md#attachmentreplication)

#### Defined in

[ue/ue.d.ts:13151](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13151)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[AutoReceiveInput](ue_ue.RigidBodyBase.md#autoreceiveinput)

#### Defined in

[ue/ue.d.ts:13157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13157)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[BlueprintCreatedComponents](ue_ue.RigidBodyBase.md#blueprintcreatedcomponents)

#### Defined in

[ue/ue.d.ts:13206](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13206)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[Children](ue_ue.RigidBodyBase.md#children)

#### Defined in

[ue/ue.d.ts:13166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13166)

___

### ConstraintActor1

• **ConstraintActor1**: [`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:57511](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57511)

___

### ConstraintActor2

• **ConstraintActor2**: [`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:57512](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57512)

___

### ConstraintComp

• **ConstraintComp**: [`PhysicsConstraintComponent`](ue_ue.PhysicsConstraintComponent.md)

#### Defined in

[ue/ue.d.ts:57510](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57510)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ControllingMatineeActors](ue_ue.RigidBodyBase.md#controllingmatineeactors)

#### Defined in

[ue/ue.d.ts:13169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13169)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[CustomTimeDilation](ue_ue.RigidBodyBase.md#customtimedilation)

#### Defined in

[ue/ue.d.ts:13150](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13150)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.RigidBodyBase.md#defaultupdateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13146](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13146)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[FolderPath](ue_ue.RigidBodyBase.md#folderpath)

#### Defined in

[ue/ue.d.ts:13177](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13177)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GroupActor](ue_ue.RigidBodyBase.md#groupactor)

#### Defined in

[ue/ue.d.ts:13173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13173)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[HiddenEditorViews](ue_ue.RigidBodyBase.md#hiddeneditorviews)

#### Defined in

[ue/ue.d.ts:13175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13175)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[InitialLifeSpan](ue_ue.RigidBodyBase.md#initiallifespan)

#### Defined in

[ue/ue.d.ts:13149](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13149)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[InputComponent](ue_ue.RigidBodyBase.md#inputcomponent)

#### Defined in

[ue/ue.d.ts:13159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13159)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[InputPriority](ue_ue.RigidBodyBase.md#inputpriority)

#### Defined in

[ue/ue.d.ts:13158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13158)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[InstanceComponents](ue_ue.RigidBodyBase.md#instancecomponents)

#### Defined in

[ue/ue.d.ts:13205](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13205)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[Instigator](ue_ue.RigidBodyBase.md#instigator)

#### Defined in

[ue/ue.d.ts:13165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13165)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[Layers](ue_ue.RigidBodyBase.md#layers)

#### Defined in

[ue/ue.d.ts:13170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13170)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[MinNetUpdateFrequency](ue_ue.RigidBodyBase.md#minnetupdatefrequency)

#### Defined in

[ue/ue.d.ts:13163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13163)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[NetCullDistanceSquared](ue_ue.RigidBodyBase.md#netculldistancesquared)

#### Defined in

[ue/ue.d.ts:13160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13160)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[NetDormancy](ue_ue.RigidBodyBase.md#netdormancy)

#### Defined in

[ue/ue.d.ts:13155](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13155)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[NetDriverName](ue_ue.RigidBodyBase.md#netdrivername)

#### Defined in

[ue/ue.d.ts:13153](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13153)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[NetPriority](ue_ue.RigidBodyBase.md#netpriority)

#### Defined in

[ue/ue.d.ts:13164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13164)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[NetTag](ue_ue.RigidBodyBase.md#nettag)

#### Defined in

[ue/ue.d.ts:13161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13161)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[NetUpdateFrequency](ue_ue.RigidBodyBase.md#netupdatefrequency)

#### Defined in

[ue/ue.d.ts:13162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13162)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnActorBeginOverlap](ue_ue.RigidBodyBase.md#onactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13192](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13192)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnActorEndOverlap](ue_ue.RigidBodyBase.md#onactorendoverlap)

#### Defined in

[ue/ue.d.ts:13193](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13193)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnActorHit](ue_ue.RigidBodyBase.md#onactorhit)

#### Defined in

[ue/ue.d.ts:13202](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13202)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnBeginCursorOver](ue_ue.RigidBodyBase.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:13194](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13194)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnClicked](ue_ue.RigidBodyBase.md#onclicked)

#### Defined in

[ue/ue.d.ts:13196](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13196)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnDestroyed](ue_ue.RigidBodyBase.md#ondestroyed)

#### Defined in

[ue/ue.d.ts:13203](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13203)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnEndCursorOver](ue_ue.RigidBodyBase.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:13195](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13195)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnEndPlay](ue_ue.RigidBodyBase.md#onendplay)

#### Defined in

[ue/ue.d.ts:13204](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13204)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnInputTouchBegin](ue_ue.RigidBodyBase.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13198](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13198)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnInputTouchEnd](ue_ue.RigidBodyBase.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:13199](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13199)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnInputTouchEnter](ue_ue.RigidBodyBase.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:13200](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13200)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnInputTouchLeave](ue_ue.RigidBodyBase.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:13201](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13201)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnReleased](ue_ue.RigidBodyBase.md#onreleased)

#### Defined in

[ue/ue.d.ts:13197](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13197)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnTakeAnyDamage](ue_ue.RigidBodyBase.md#ontakeanydamage)

#### Defined in

[ue/ue.d.ts:13189](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13189)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnTakePointDamage](ue_ue.RigidBodyBase.md#ontakepointdamage)

#### Defined in

[ue/ue.d.ts:13190](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13190)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnTakeRadialDamage](ue_ue.RigidBodyBase.md#ontakeradialdamage)

#### Defined in

[ue/ue.d.ts:13191](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13191)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[Owner](ue_ue.RigidBodyBase.md#owner)

#### Defined in

[ue/ue.d.ts:13152](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13152)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ParentComponent](ue_ue.RigidBodyBase.md#parentcomponent)

#### Defined in

[ue/ue.d.ts:13172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13172)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ParentComponentActor](ue_ue.RigidBodyBase.md#parentcomponentactor)

#### Defined in

[ue/ue.d.ts:13171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13171)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[PivotOffset](ue_ue.RigidBodyBase.md#pivotoffset)

#### Defined in

[ue/ue.d.ts:13168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13168)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[PrimaryActorTick](ue_ue.RigidBodyBase.md#primaryactortick)

#### Defined in

[ue/ue.d.ts:13115](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13115)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[RemoteRole](ue_ue.RigidBodyBase.md#remoterole)

#### Defined in

[ue/ue.d.ts:13147](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13147)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReplicatedMovement](ue_ue.RigidBodyBase.md#replicatedmovement)

#### Defined in

[ue/ue.d.ts:13148](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13148)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[Role](ue_ue.RigidBodyBase.md#role)

#### Defined in

[ue/ue.d.ts:13154](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13154)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[RootComponent](ue_ue.RigidBodyBase.md#rootcomponent)

#### Defined in

[ue/ue.d.ts:13167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13167)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SpawnCollisionHandlingMethod](ue_ue.RigidBodyBase.md#spawncollisionhandlingmethod)

#### Defined in

[ue/ue.d.ts:13156](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13156)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SpriteScale](ue_ue.RigidBodyBase.md#spritescale)

#### Defined in

[ue/ue.d.ts:13174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13174)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[Tags](ue_ue.RigidBodyBase.md#tags)

#### Defined in

[ue/ue.d.ts:13188](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13188)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.RigidBodyBase.md#updateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13145](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13145)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[__tid_Actor__](ue_ue.RigidBodyBase.md#__tid_actor__)

#### Defined in

[ue/ue.d.ts:13348](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13348)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[__tid_Object__](ue_ue.RigidBodyBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PhysicsConstraintActor\_\_

• **\_\_tid\_PhysicsConstraintActor\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:57518](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57518)

___

### \_\_tid\_RigidBodyBase\_\_

• **\_\_tid\_RigidBodyBase\_\_**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[__tid_RigidBodyBase__](ue_ue.RigidBodyBase.md#__tid_rigidbodybase__)

#### Defined in

[ue/ue.d.ts:57443](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57443)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bActorEnableCollision](ue_ue.RigidBodyBase.md#bactorenablecollision)

#### Defined in

[ue/ue.d.ts:13143](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13143)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bActorIsBeingDestroyed](ue_ue.RigidBodyBase.md#bactorisbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13144](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13144)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bActorLabelEditable](ue_ue.RigidBodyBase.md#bactorlabeleditable)

#### Defined in

[ue/ue.d.ts:13183](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13183)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bActorSeamlessTraveled](ue_ue.RigidBodyBase.md#bactorseamlesstraveled)

#### Defined in

[ue/ue.d.ts:13139](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13139)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.RigidBodyBase.md#ballowreceivetickeventondedicatedserver)

#### Defined in

[ue/ue.d.ts:13142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13142)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bAllowTickBeforeBeginPlay](ue_ue.RigidBodyBase.md#ballowtickbeforebeginplay)

#### Defined in

[ue/ue.d.ts:13129](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13129)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bAlwaysRelevant](ue_ue.RigidBodyBase.md#balwaysrelevant)

#### Defined in

[ue/ue.d.ts:13120](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13120)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bAutoDestroyWhenFinished](ue_ue.RigidBodyBase.md#bautodestroywhenfinished)

#### Defined in

[ue/ue.d.ts:13130](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13130)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bBlockInput](ue_ue.RigidBodyBase.md#bblockinput)

#### Defined in

[ue/ue.d.ts:13131](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13131)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bCanBeDamaged](ue_ue.RigidBodyBase.md#bcanbedamaged)

#### Defined in

[ue/ue.d.ts:13132](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13132)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bCanBeInCluster](ue_ue.RigidBodyBase.md#bcanbeincluster)

#### Defined in

[ue/ue.d.ts:13141](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13141)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bCollideWhenPlacing](ue_ue.RigidBodyBase.md#bcollidewhenplacing)

#### Defined in

[ue/ue.d.ts:13133](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13133)

___

### bDisableCollision

• **bDisableCollision**: `boolean`

#### Defined in

[ue/ue.d.ts:57513](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57513)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bEditable](ue_ue.RigidBodyBase.md#beditable)

#### Defined in

[ue/ue.d.ts:13184](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13184)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bEnableAutoLODGeneration](ue_ue.RigidBodyBase.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:13137](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13137)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bExchangedRoles](ue_ue.RigidBodyBase.md#bexchangedroles)

#### Defined in

[ue/ue.d.ts:13123](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13123)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bFindCameraComponentWhenViewTarget](ue_ue.RigidBodyBase.md#bfindcameracomponentwhenviewtarget)

#### Defined in

[ue/ue.d.ts:13134](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13134)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.RigidBodyBase.md#bgenerateoverlapeventsduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13135](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13135)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bHidden](ue_ue.RigidBodyBase.md#bhidden)

#### Defined in

[ue/ue.d.ts:13116](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13116)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bHiddenEd](ue_ue.RigidBodyBase.md#bhiddened)

#### Defined in

[ue/ue.d.ts:13178](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13178)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bHiddenEdLayer](ue_ue.RigidBodyBase.md#bhiddenedlayer)

#### Defined in

[ue/ue.d.ts:13180](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13180)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bHiddenEdLevel](ue_ue.RigidBodyBase.md#bhiddenedlevel)

#### Defined in

[ue/ue.d.ts:13181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13181)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bHiddenEdTemporary](ue_ue.RigidBodyBase.md#bhiddenedtemporary)

#### Defined in

[ue/ue.d.ts:13187](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13187)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bIgnoresOriginShifting](ue_ue.RigidBodyBase.md#bignoresoriginshifting)

#### Defined in

[ue/ue.d.ts:13136](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13136)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bIsEditorOnlyActor](ue_ue.RigidBodyBase.md#biseditoronlyactor)

#### Defined in

[ue/ue.d.ts:13138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13138)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bIsEditorPreviewActor](ue_ue.RigidBodyBase.md#biseditorpreviewactor)

#### Defined in

[ue/ue.d.ts:13179](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13179)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bListedInSceneOutliner](ue_ue.RigidBodyBase.md#blistedinsceneoutliner)

#### Defined in

[ue/ue.d.ts:13185](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13185)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bLockLocation](ue_ue.RigidBodyBase.md#blocklocation)

#### Defined in

[ue/ue.d.ts:13182](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13182)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bNetLoadOnClient](ue_ue.RigidBodyBase.md#bnetloadonclient)

#### Defined in

[ue/ue.d.ts:13124](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13124)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bNetStartup](ue_ue.RigidBodyBase.md#bnetstartup)

#### Defined in

[ue/ue.d.ts:13118](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13118)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bNetTemporary](ue_ue.RigidBodyBase.md#bnettemporary)

#### Defined in

[ue/ue.d.ts:13117](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13117)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bNetUseOwnerRelevancy](ue_ue.RigidBodyBase.md#bnetuseownerrelevancy)

#### Defined in

[ue/ue.d.ts:13125](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13125)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bOnlyRelevantToOwner](ue_ue.RigidBodyBase.md#bonlyrelevanttoowner)

#### Defined in

[ue/ue.d.ts:13119](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13119)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bOptimizeBPComponentData](ue_ue.RigidBodyBase.md#boptimizebpcomponentdata)

#### Defined in

[ue/ue.d.ts:13186](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13186)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bRelevantForLevelBounds](ue_ue.RigidBodyBase.md#brelevantforlevelbounds)

#### Defined in

[ue/ue.d.ts:13127](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13127)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bRelevantForNetworkReplays](ue_ue.RigidBodyBase.md#brelevantfornetworkreplays)

#### Defined in

[ue/ue.d.ts:13126](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13126)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bReplayRewindable](ue_ue.RigidBodyBase.md#breplayrewindable)

#### Defined in

[ue/ue.d.ts:13128](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13128)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bReplicateMovement](ue_ue.RigidBodyBase.md#breplicatemovement)

#### Defined in

[ue/ue.d.ts:13121](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13121)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bReplicates](ue_ue.RigidBodyBase.md#breplicates)

#### Defined in

[ue/ue.d.ts:13140](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13140)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[bTearOff](ue_ue.RigidBodyBase.md#btearoff)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ActorHasTag](ue_ue.RigidBodyBase.md#actorhastag)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[AddComponent](ue_ue.RigidBodyBase.md#addcomponent)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[AddTickPrerequisiteActor](ue_ue.RigidBodyBase.md#addtickprerequisiteactor)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[AddTickPrerequisiteComponent](ue_ue.RigidBodyBase.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13210](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13210)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[DetachRootComponentFromParent](ue_ue.RigidBodyBase.md#detachrootcomponentfromparent)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[DisableInput](ue_ue.RigidBodyBase.md#disableinput)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[EnableInput](ue_ue.RigidBodyBase.md#enableinput)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ExecuteUbergraph](ue_ue.RigidBodyBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[FlushNetDormancy](ue_ue.RigidBodyBase.md#flushnetdormancy)

#### Defined in

[ue/ue.d.ts:13214](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13214)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ForceNetUpdate](ue_ue.RigidBodyBase.md#forcenetupdate)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorBounds](ue_ue.RigidBodyBase.md#getactorbounds)

#### Defined in

[ue/ue.d.ts:13216](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13216)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorEnableCollision](ue_ue.RigidBodyBase.md#getactorenablecollision)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorEyesViewPoint](ue_ue.RigidBodyBase.md#getactoreyesviewpoint)

#### Defined in

[ue/ue.d.ts:13218](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13218)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorForwardVector](ue_ue.RigidBodyBase.md#getactorforwardvector)

#### Defined in

[ue/ue.d.ts:13219](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13219)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorLabel](ue_ue.RigidBodyBase.md#getactorlabel)

#### Defined in

[ue/ue.d.ts:13220](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13220)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorRelativeScale3D](ue_ue.RigidBodyBase.md#getactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13221](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13221)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorRightVector](ue_ue.RigidBodyBase.md#getactorrightvector)

#### Defined in

[ue/ue.d.ts:13222](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13222)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorScale3D](ue_ue.RigidBodyBase.md#getactorscale3d)

#### Defined in

[ue/ue.d.ts:13223](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13223)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorTickInterval](ue_ue.RigidBodyBase.md#getactortickinterval)

#### Defined in

[ue/ue.d.ts:13224](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13224)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorTimeDilation](ue_ue.RigidBodyBase.md#getactortimedilation)

#### Defined in

[ue/ue.d.ts:13225](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13225)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetActorUpVector](ue_ue.RigidBodyBase.md#getactorupvector)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetAllChildActors](ue_ue.RigidBodyBase.md#getallchildactors)

#### Defined in

[ue/ue.d.ts:13227](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13227)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetAttachParentActor](ue_ue.RigidBodyBase.md#getattachparentactor)

#### Defined in

[ue/ue.d.ts:13229](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13229)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetAttachParentSocketName](ue_ue.RigidBodyBase.md#getattachparentsocketname)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetAttachedActors](ue_ue.RigidBodyBase.md#getattachedactors)

#### Defined in

[ue/ue.d.ts:13228](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13228)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetClass](ue_ue.RigidBodyBase.md#getclass)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetComponentByClass](ue_ue.RigidBodyBase.md#getcomponentbyclass)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetComponentsByInterface](ue_ue.RigidBodyBase.md#getcomponentsbyinterface)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetComponentsByTag](ue_ue.RigidBodyBase.md#getcomponentsbytag)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetDistanceTo](ue_ue.RigidBodyBase.md#getdistanceto)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetDotProductTo](ue_ue.RigidBodyBase.md#getdotproductto)

#### Defined in

[ue/ue.d.ts:13235](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13235)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetFolderPath](ue_ue.RigidBodyBase.md#getfolderpath)

#### Defined in

[ue/ue.d.ts:13236](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13236)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetGameTimeSinceCreation](ue_ue.RigidBodyBase.md#getgametimesincecreation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetHorizontalDistanceTo](ue_ue.RigidBodyBase.md#gethorizontaldistanceto)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetHorizontalDotProductTo](ue_ue.RigidBodyBase.md#gethorizontaldotproductto)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetInputAxisKeyValue](ue_ue.RigidBodyBase.md#getinputaxiskeyvalue)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetInputAxisValue](ue_ue.RigidBodyBase.md#getinputaxisvalue)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetInputVectorAxisValue](ue_ue.RigidBodyBase.md#getinputvectoraxisvalue)

#### Defined in

[ue/ue.d.ts:13242](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13242)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetInstigator](ue_ue.RigidBodyBase.md#getinstigator)

#### Defined in

[ue/ue.d.ts:13243](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13243)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetInstigatorController](ue_ue.RigidBodyBase.md#getinstigatorcontroller)

#### Defined in

[ue/ue.d.ts:13244](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13244)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetLifeSpan](ue_ue.RigidBodyBase.md#getlifespan)

#### Defined in

[ue/ue.d.ts:13245](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13245)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetLocalRole](ue_ue.RigidBodyBase.md#getlocalrole)

#### Defined in

[ue/ue.d.ts:13246](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13246)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetName](ue_ue.RigidBodyBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetOuter](ue_ue.RigidBodyBase.md#getouter)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetOverlappingActors](ue_ue.RigidBodyBase.md#getoverlappingactors)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetOverlappingComponents](ue_ue.RigidBodyBase.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:13248](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13248)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetOwner](ue_ue.RigidBodyBase.md#getowner)

#### Defined in

[ue/ue.d.ts:13249](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13249)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetParentActor](ue_ue.RigidBodyBase.md#getparentactor)

#### Defined in

[ue/ue.d.ts:13250](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13250)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetParentComponent](ue_ue.RigidBodyBase.md#getparentcomponent)

#### Defined in

[ue/ue.d.ts:13251](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13251)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetRemoteRole](ue_ue.RigidBodyBase.md#getremoterole)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetSquaredDistanceTo](ue_ue.RigidBodyBase.md#getsquareddistanceto)

#### Defined in

[ue/ue.d.ts:13253](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13253)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetTickableWhenPaused](ue_ue.RigidBodyBase.md#gettickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13254](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13254)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetTransform](ue_ue.RigidBodyBase.md#gettransform)

#### Defined in

[ue/ue.d.ts:13255](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13255)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetVelocity](ue_ue.RigidBodyBase.md#getvelocity)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetVerticalDistanceTo](ue_ue.RigidBodyBase.md#getverticaldistanceto)

#### Defined in

[ue/ue.d.ts:13257](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13257)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[GetWorld](ue_ue.RigidBodyBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[HasAuthority](ue_ue.RigidBodyBase.md#hasauthority)

#### Defined in

[ue/ue.d.ts:13258](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13258)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsActorBeingDestroyed](ue_ue.RigidBodyBase.md#isactorbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13259](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13259)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsActorTickEnabled](ue_ue.RigidBodyBase.md#isactortickenabled)

#### Defined in

[ue/ue.d.ts:13260](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13260)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsChildActor](ue_ue.RigidBodyBase.md#ischildactor)

#### Defined in

[ue/ue.d.ts:13261](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13261)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsEditable](ue_ue.RigidBodyBase.md#iseditable)

#### Defined in

[ue/ue.d.ts:13262](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13262)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsHiddenEd](ue_ue.RigidBodyBase.md#ishiddened)

#### Defined in

[ue/ue.d.ts:13263](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13263)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsHiddenEdAtStartup](ue_ue.RigidBodyBase.md#ishiddenedatstartup)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsOverlappingActor](ue_ue.RigidBodyBase.md#isoverlappingactor)

#### Defined in

[ue/ue.d.ts:13265](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13265)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsSelectable](ue_ue.RigidBodyBase.md#isselectable)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[IsTemporarilyHiddenInEditor](ue_ue.RigidBodyBase.md#istemporarilyhiddenineditor)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AddActorLocalOffset](ue_ue.RigidBodyBase.md#k2_addactorlocaloffset)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AddActorLocalRotation](ue_ue.RigidBodyBase.md#k2_addactorlocalrotation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AddActorLocalTransform](ue_ue.RigidBodyBase.md#k2_addactorlocaltransform)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AddActorWorldOffset](ue_ue.RigidBodyBase.md#k2_addactorworldoffset)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AddActorWorldRotation](ue_ue.RigidBodyBase.md#k2_addactorworldrotation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AddActorWorldTransform](ue_ue.RigidBodyBase.md#k2_addactorworldtransform)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AttachRootComponentTo](ue_ue.RigidBodyBase.md#k2_attachrootcomponentto)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AttachRootComponentToActor](ue_ue.RigidBodyBase.md#k2_attachrootcomponenttoactor)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AttachToActor](ue_ue.RigidBodyBase.md#k2_attachtoactor)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_AttachToComponent](ue_ue.RigidBodyBase.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:13277](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13277)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_DestroyActor](ue_ue.RigidBodyBase.md#k2_destroyactor)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_DestroyComponent](ue_ue.RigidBodyBase.md#k2_destroycomponent)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_DetachFromActor](ue_ue.RigidBodyBase.md#k2_detachfromactor)

#### Defined in

[ue/ue.d.ts:13280](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13280)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_GetActorLocation](ue_ue.RigidBodyBase.md#k2_getactorlocation)

#### Defined in

[ue/ue.d.ts:13281](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13281)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_GetActorRotation](ue_ue.RigidBodyBase.md#k2_getactorrotation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_GetComponentsByClass](ue_ue.RigidBodyBase.md#k2_getcomponentsbyclass)

#### Defined in

[ue/ue.d.ts:13283](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13283)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_GetRootComponent](ue_ue.RigidBodyBase.md#k2_getrootcomponent)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_OnBecomeViewTarget](ue_ue.RigidBodyBase.md#k2_onbecomeviewtarget)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_OnEndViewTarget](ue_ue.RigidBodyBase.md#k2_onendviewtarget)

#### Defined in

[ue/ue.d.ts:13286](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13286)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_OnReset](ue_ue.RigidBodyBase.md#k2_onreset)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_SetActorLocation](ue_ue.RigidBodyBase.md#k2_setactorlocation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_SetActorLocationAndRotation](ue_ue.RigidBodyBase.md#k2_setactorlocationandrotation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_SetActorRelativeLocation](ue_ue.RigidBodyBase.md#k2_setactorrelativelocation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_SetActorRelativeRotation](ue_ue.RigidBodyBase.md#k2_setactorrelativerotation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_SetActorRelativeTransform](ue_ue.RigidBodyBase.md#k2_setactorrelativetransform)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_SetActorRotation](ue_ue.RigidBodyBase.md#k2_setactorrotation)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_SetActorTransform](ue_ue.RigidBodyBase.md#k2_setactortransform)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[K2_TeleportTo](ue_ue.RigidBodyBase.md#k2_teleportto)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[MakeMIDForMaterial](ue_ue.RigidBodyBase.md#makemidformaterial)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[MakeNoise](ue_ue.RigidBodyBase.md#makenoise)

#### Defined in

[ue/ue.d.ts:13297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13297)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnRep_AttachmentReplication](ue_ue.RigidBodyBase.md#onrep_attachmentreplication)

#### Defined in

[ue/ue.d.ts:13298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13298)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnRep_Instigator](ue_ue.RigidBodyBase.md#onrep_instigator)

#### Defined in

[ue/ue.d.ts:13299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13299)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnRep_Owner](ue_ue.RigidBodyBase.md#onrep_owner)

#### Defined in

[ue/ue.d.ts:13300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13300)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnRep_ReplicateMovement](ue_ue.RigidBodyBase.md#onrep_replicatemovement)

#### Defined in

[ue/ue.d.ts:13302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13302)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[OnRep_ReplicatedMovement](ue_ue.RigidBodyBase.md#onrep_replicatedmovement)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[PrestreamTextures](ue_ue.RigidBodyBase.md#prestreamtextures)

#### Defined in

[ue/ue.d.ts:13303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13303)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorBeginCursorOver](ue_ue.RigidBodyBase.md#receiveactorbegincursorover)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorBeginOverlap](ue_ue.RigidBodyBase.md#receiveactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13305)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorEndCursorOver](ue_ue.RigidBodyBase.md#receiveactorendcursorover)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorEndOverlap](ue_ue.RigidBodyBase.md#receiveactorendoverlap)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorOnClicked](ue_ue.RigidBodyBase.md#receiveactoronclicked)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorOnInputTouchBegin](ue_ue.RigidBodyBase.md#receiveactoroninputtouchbegin)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorOnInputTouchEnd](ue_ue.RigidBodyBase.md#receiveactoroninputtouchend)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorOnInputTouchEnter](ue_ue.RigidBodyBase.md#receiveactoroninputtouchenter)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorOnInputTouchLeave](ue_ue.RigidBodyBase.md#receiveactoroninputtouchleave)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveActorOnReleased](ue_ue.RigidBodyBase.md#receiveactoronreleased)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveAnyDamage](ue_ue.RigidBodyBase.md#receiveanydamage)

#### Defined in

[ue/ue.d.ts:13314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13314)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveBeginPlay](ue_ue.RigidBodyBase.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:13315](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13315)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveDestroyed](ue_ue.RigidBodyBase.md#receivedestroyed)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveEndPlay](ue_ue.RigidBodyBase.md#receiveendplay)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveHit](ue_ue.RigidBodyBase.md#receivehit)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceivePointDamage](ue_ue.RigidBodyBase.md#receivepointdamage)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveRadialDamage](ue_ue.RigidBodyBase.md#receiveradialdamage)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[ReceiveTick](ue_ue.RigidBodyBase.md#receivetick)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[RemoveTickPrerequisiteActor](ue_ue.RigidBodyBase.md#removetickprerequisiteactor)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[RemoveTickPrerequisiteComponent](ue_ue.RigidBodyBase.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13323)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetActorHiddenInGame](ue_ue.RigidBodyBase.md#setactorhiddeningame)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetActorLabel](ue_ue.RigidBodyBase.md#setactorlabel)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetActorRelativeScale3D](ue_ue.RigidBodyBase.md#setactorrelativescale3d)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetActorScale3D](ue_ue.RigidBodyBase.md#setactorscale3d)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetActorTickEnabled](ue_ue.RigidBodyBase.md#setactortickenabled)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetActorTickInterval](ue_ue.RigidBodyBase.md#setactortickinterval)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetFolderPath](ue_ue.RigidBodyBase.md#setfolderpath)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetIsTemporarilyHiddenInEditor](ue_ue.RigidBodyBase.md#setistemporarilyhiddenineditor)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetLifeSpan](ue_ue.RigidBodyBase.md#setlifespan)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetNetDormancy](ue_ue.RigidBodyBase.md#setnetdormancy)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetOwner](ue_ue.RigidBodyBase.md#setowner)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetReplicateMovement](ue_ue.RigidBodyBase.md#setreplicatemovement)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetReplicates](ue_ue.RigidBodyBase.md#setreplicates)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetTickGroup](ue_ue.RigidBodyBase.md#settickgroup)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SetTickableWhenPaused](ue_ue.RigidBodyBase.md#settickablewhenpaused)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[SnapRootComponentTo](ue_ue.RigidBodyBase.md#snaprootcomponentto)

#### Defined in

[ue/ue.d.ts:13340](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13340)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[TearOff](ue_ue.RigidBodyBase.md#tearoff)

#### Defined in

[ue/ue.d.ts:13341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13341)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[RigidBodyBase](ue_ue.RigidBodyBase.md).[UserConstructionScript](ue_ue.RigidBodyBase.md#userconstructionscript)

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

[RigidBodyBase](ue_ue.RigidBodyBase.md).[WasRecentlyRendered](ue_ue.RigidBodyBase.md#wasrecentlyrendered)

#### Defined in

[ue/ue.d.ts:13343](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13343)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PhysicsConstraintActor`](ue_ue.PhysicsConstraintActor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PhysicsConstraintActor`](ue_ue.PhysicsConstraintActor.md)

#### Overrides

[RigidBodyBase](ue_ue.RigidBodyBase.md).[Find](ue_ue.RigidBodyBase.md#find)

#### Defined in

[ue/ue.d.ts:57515](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57515)

___

### Load

▸ `Static` **Load**(`InName`): [`PhysicsConstraintActor`](ue_ue.PhysicsConstraintActor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PhysicsConstraintActor`](ue_ue.PhysicsConstraintActor.md)

#### Overrides

[RigidBodyBase](ue_ue.RigidBodyBase.md).[Load](ue_ue.RigidBodyBase.md#load)

#### Defined in

[ue/ue.d.ts:57516](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57516)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[RigidBodyBase](ue_ue.RigidBodyBase.md).[StaticClass](ue_ue.RigidBodyBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:57514](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57514)
