[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TransformGizmoActor

# Class: TransformGizmoActor

[ue/ue](../modules/ue_ue.md).TransformGizmoActor

## Hierarchy

- [`GizmoActor`](ue_ue.GizmoActor.md)

  ↳ **`TransformGizmoActor`**

## Table of contents

### Constructors

- [constructor](ue_ue.TransformGizmoActor.md#constructor)

### Properties

- [ActorLabel](ue_ue.TransformGizmoActor.md#actorlabel)
- [AttachmentReplication](ue_ue.TransformGizmoActor.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.TransformGizmoActor.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.TransformGizmoActor.md#blueprintcreatedcomponents)
- [Children](ue_ue.TransformGizmoActor.md#children)
- [ControllingMatineeActors](ue_ue.TransformGizmoActor.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.TransformGizmoActor.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.TransformGizmoActor.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.TransformGizmoActor.md#folderpath)
- [GroupActor](ue_ue.TransformGizmoActor.md#groupactor)
- [HiddenEditorViews](ue_ue.TransformGizmoActor.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.TransformGizmoActor.md#initiallifespan)
- [InputComponent](ue_ue.TransformGizmoActor.md#inputcomponent)
- [InputPriority](ue_ue.TransformGizmoActor.md#inputpriority)
- [InstanceComponents](ue_ue.TransformGizmoActor.md#instancecomponents)
- [Instigator](ue_ue.TransformGizmoActor.md#instigator)
- [Layers](ue_ue.TransformGizmoActor.md#layers)
- [MinNetUpdateFrequency](ue_ue.TransformGizmoActor.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.TransformGizmoActor.md#netculldistancesquared)
- [NetDormancy](ue_ue.TransformGizmoActor.md#netdormancy)
- [NetDriverName](ue_ue.TransformGizmoActor.md#netdrivername)
- [NetPriority](ue_ue.TransformGizmoActor.md#netpriority)
- [NetTag](ue_ue.TransformGizmoActor.md#nettag)
- [NetUpdateFrequency](ue_ue.TransformGizmoActor.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.TransformGizmoActor.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.TransformGizmoActor.md#onactorendoverlap)
- [OnActorHit](ue_ue.TransformGizmoActor.md#onactorhit)
- [OnBeginCursorOver](ue_ue.TransformGizmoActor.md#onbegincursorover)
- [OnClicked](ue_ue.TransformGizmoActor.md#onclicked)
- [OnDestroyed](ue_ue.TransformGizmoActor.md#ondestroyed)
- [OnEndCursorOver](ue_ue.TransformGizmoActor.md#onendcursorover)
- [OnEndPlay](ue_ue.TransformGizmoActor.md#onendplay)
- [OnInputTouchBegin](ue_ue.TransformGizmoActor.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.TransformGizmoActor.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.TransformGizmoActor.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.TransformGizmoActor.md#oninputtouchleave)
- [OnReleased](ue_ue.TransformGizmoActor.md#onreleased)
- [OnTakeAnyDamage](ue_ue.TransformGizmoActor.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.TransformGizmoActor.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.TransformGizmoActor.md#ontakeradialdamage)
- [Owner](ue_ue.TransformGizmoActor.md#owner)
- [ParentComponent](ue_ue.TransformGizmoActor.md#parentcomponent)
- [ParentComponentActor](ue_ue.TransformGizmoActor.md#parentcomponentactor)
- [PivotOffset](ue_ue.TransformGizmoActor.md#pivotoffset)
- [PrimaryActorTick](ue_ue.TransformGizmoActor.md#primaryactortick)
- [RemoteRole](ue_ue.TransformGizmoActor.md#remoterole)
- [ReplicatedMovement](ue_ue.TransformGizmoActor.md#replicatedmovement)
- [Role](ue_ue.TransformGizmoActor.md#role)
- [RootComponent](ue_ue.TransformGizmoActor.md#rootcomponent)
- [RotateX](ue_ue.TransformGizmoActor.md#rotatex)
- [RotateY](ue_ue.TransformGizmoActor.md#rotatey)
- [RotateZ](ue_ue.TransformGizmoActor.md#rotatez)
- [SpawnCollisionHandlingMethod](ue_ue.TransformGizmoActor.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.TransformGizmoActor.md#spritescale)
- [Tags](ue_ue.TransformGizmoActor.md#tags)
- [TranslateX](ue_ue.TransformGizmoActor.md#translatex)
- [TranslateXY](ue_ue.TransformGizmoActor.md#translatexy)
- [TranslateXZ](ue_ue.TransformGizmoActor.md#translatexz)
- [TranslateY](ue_ue.TransformGizmoActor.md#translatey)
- [TranslateYZ](ue_ue.TransformGizmoActor.md#translateyz)
- [TranslateZ](ue_ue.TransformGizmoActor.md#translatez)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.TransformGizmoActor.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.TransformGizmoActor.md#__tid_actor__)
- [\_\_tid\_GizmoActor\_\_](ue_ue.TransformGizmoActor.md#__tid_gizmoactor__)
- [\_\_tid\_InternalToolFrameworkActor\_\_](ue_ue.TransformGizmoActor.md#__tid_internaltoolframeworkactor__)
- [\_\_tid\_Object\_\_](ue_ue.TransformGizmoActor.md#__tid_object__)
- [\_\_tid\_TransformGizmoActor\_\_](ue_ue.TransformGizmoActor.md#__tid_transformgizmoactor__)
- [bActorEnableCollision](ue_ue.TransformGizmoActor.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.TransformGizmoActor.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.TransformGizmoActor.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.TransformGizmoActor.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.TransformGizmoActor.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.TransformGizmoActor.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.TransformGizmoActor.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.TransformGizmoActor.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.TransformGizmoActor.md#bblockinput)
- [bCanBeDamaged](ue_ue.TransformGizmoActor.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.TransformGizmoActor.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.TransformGizmoActor.md#bcollidewhenplacing)
- [bEditable](ue_ue.TransformGizmoActor.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.TransformGizmoActor.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.TransformGizmoActor.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.TransformGizmoActor.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.TransformGizmoActor.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.TransformGizmoActor.md#bhidden)
- [bHiddenEd](ue_ue.TransformGizmoActor.md#bhiddened)
- [bHiddenEdLayer](ue_ue.TransformGizmoActor.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.TransformGizmoActor.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.TransformGizmoActor.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.TransformGizmoActor.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.TransformGizmoActor.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.TransformGizmoActor.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.TransformGizmoActor.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.TransformGizmoActor.md#blocklocation)
- [bNetLoadOnClient](ue_ue.TransformGizmoActor.md#bnetloadonclient)
- [bNetStartup](ue_ue.TransformGizmoActor.md#bnetstartup)
- [bNetTemporary](ue_ue.TransformGizmoActor.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.TransformGizmoActor.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.TransformGizmoActor.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.TransformGizmoActor.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.TransformGizmoActor.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.TransformGizmoActor.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.TransformGizmoActor.md#breplayrewindable)
- [bReplicateMovement](ue_ue.TransformGizmoActor.md#breplicatemovement)
- [bReplicates](ue_ue.TransformGizmoActor.md#breplicates)
- [bTearOff](ue_ue.TransformGizmoActor.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.TransformGizmoActor.md#actorhastag)
- [AddComponent](ue_ue.TransformGizmoActor.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.TransformGizmoActor.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.TransformGizmoActor.md#addtickprerequisitecomponent)
- [CreateDefaultSubobject](ue_ue.TransformGizmoActor.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.TransformGizmoActor.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.TransformGizmoActor.md#disableinput)
- [EnableInput](ue_ue.TransformGizmoActor.md#enableinput)
- [ExecuteUbergraph](ue_ue.TransformGizmoActor.md#executeubergraph)
- [FlushNetDormancy](ue_ue.TransformGizmoActor.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.TransformGizmoActor.md#forcenetupdate)
- [GetActorBounds](ue_ue.TransformGizmoActor.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.TransformGizmoActor.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.TransformGizmoActor.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.TransformGizmoActor.md#getactorforwardvector)
- [GetActorLabel](ue_ue.TransformGizmoActor.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.TransformGizmoActor.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.TransformGizmoActor.md#getactorrightvector)
- [GetActorScale3D](ue_ue.TransformGizmoActor.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.TransformGizmoActor.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.TransformGizmoActor.md#getactortimedilation)
- [GetActorUpVector](ue_ue.TransformGizmoActor.md#getactorupvector)
- [GetAllChildActors](ue_ue.TransformGizmoActor.md#getallchildactors)
- [GetAttachParentActor](ue_ue.TransformGizmoActor.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.TransformGizmoActor.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.TransformGizmoActor.md#getattachedactors)
- [GetClass](ue_ue.TransformGizmoActor.md#getclass)
- [GetComponentByClass](ue_ue.TransformGizmoActor.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.TransformGizmoActor.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.TransformGizmoActor.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.TransformGizmoActor.md#getdistanceto)
- [GetDotProductTo](ue_ue.TransformGizmoActor.md#getdotproductto)
- [GetFolderPath](ue_ue.TransformGizmoActor.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.TransformGizmoActor.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.TransformGizmoActor.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.TransformGizmoActor.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.TransformGizmoActor.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.TransformGizmoActor.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.TransformGizmoActor.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.TransformGizmoActor.md#getinstigator)
- [GetInstigatorController](ue_ue.TransformGizmoActor.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.TransformGizmoActor.md#getlifespan)
- [GetLocalRole](ue_ue.TransformGizmoActor.md#getlocalrole)
- [GetName](ue_ue.TransformGizmoActor.md#getname)
- [GetOuter](ue_ue.TransformGizmoActor.md#getouter)
- [GetOverlappingActors](ue_ue.TransformGizmoActor.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.TransformGizmoActor.md#getoverlappingcomponents)
- [GetOwner](ue_ue.TransformGizmoActor.md#getowner)
- [GetParentActor](ue_ue.TransformGizmoActor.md#getparentactor)
- [GetParentComponent](ue_ue.TransformGizmoActor.md#getparentcomponent)
- [GetRemoteRole](ue_ue.TransformGizmoActor.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.TransformGizmoActor.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.TransformGizmoActor.md#gettickablewhenpaused)
- [GetTransform](ue_ue.TransformGizmoActor.md#gettransform)
- [GetVelocity](ue_ue.TransformGizmoActor.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.TransformGizmoActor.md#getverticaldistanceto)
- [GetWorld](ue_ue.TransformGizmoActor.md#getworld)
- [HasAuthority](ue_ue.TransformGizmoActor.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.TransformGizmoActor.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.TransformGizmoActor.md#isactortickenabled)
- [IsChildActor](ue_ue.TransformGizmoActor.md#ischildactor)
- [IsEditable](ue_ue.TransformGizmoActor.md#iseditable)
- [IsHiddenEd](ue_ue.TransformGizmoActor.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.TransformGizmoActor.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.TransformGizmoActor.md#isoverlappingactor)
- [IsSelectable](ue_ue.TransformGizmoActor.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.TransformGizmoActor.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.TransformGizmoActor.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.TransformGizmoActor.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.TransformGizmoActor.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.TransformGizmoActor.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.TransformGizmoActor.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.TransformGizmoActor.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.TransformGizmoActor.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.TransformGizmoActor.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.TransformGizmoActor.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.TransformGizmoActor.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.TransformGizmoActor.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.TransformGizmoActor.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.TransformGizmoActor.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.TransformGizmoActor.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.TransformGizmoActor.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.TransformGizmoActor.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.TransformGizmoActor.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.TransformGizmoActor.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.TransformGizmoActor.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.TransformGizmoActor.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.TransformGizmoActor.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.TransformGizmoActor.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.TransformGizmoActor.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.TransformGizmoActor.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.TransformGizmoActor.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.TransformGizmoActor.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.TransformGizmoActor.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.TransformGizmoActor.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.TransformGizmoActor.md#makemidformaterial)
- [MakeNoise](ue_ue.TransformGizmoActor.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.TransformGizmoActor.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.TransformGizmoActor.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.TransformGizmoActor.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.TransformGizmoActor.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.TransformGizmoActor.md#onrep_replicatedmovement)
- [PrestreamTextures](ue_ue.TransformGizmoActor.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.TransformGizmoActor.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.TransformGizmoActor.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.TransformGizmoActor.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.TransformGizmoActor.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.TransformGizmoActor.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.TransformGizmoActor.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.TransformGizmoActor.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.TransformGizmoActor.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.TransformGizmoActor.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.TransformGizmoActor.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.TransformGizmoActor.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.TransformGizmoActor.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.TransformGizmoActor.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.TransformGizmoActor.md#receiveendplay)
- [ReceiveHit](ue_ue.TransformGizmoActor.md#receivehit)
- [ReceivePointDamage](ue_ue.TransformGizmoActor.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.TransformGizmoActor.md#receiveradialdamage)
- [ReceiveTick](ue_ue.TransformGizmoActor.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.TransformGizmoActor.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.TransformGizmoActor.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.TransformGizmoActor.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.TransformGizmoActor.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.TransformGizmoActor.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.TransformGizmoActor.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.TransformGizmoActor.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.TransformGizmoActor.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.TransformGizmoActor.md#setactortickinterval)
- [SetFolderPath](ue_ue.TransformGizmoActor.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.TransformGizmoActor.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.TransformGizmoActor.md#setlifespan)
- [SetNetDormancy](ue_ue.TransformGizmoActor.md#setnetdormancy)
- [SetOwner](ue_ue.TransformGizmoActor.md#setowner)
- [SetReplicateMovement](ue_ue.TransformGizmoActor.md#setreplicatemovement)
- [SetReplicates](ue_ue.TransformGizmoActor.md#setreplicates)
- [SetTickGroup](ue_ue.TransformGizmoActor.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.TransformGizmoActor.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.TransformGizmoActor.md#snaprootcomponentto)
- [TearOff](ue_ue.TransformGizmoActor.md#tearoff)
- [UserConstructionScript](ue_ue.TransformGizmoActor.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.TransformGizmoActor.md#wasrecentlyrendered)
- [Find](ue_ue.TransformGizmoActor.md#find)
- [Load](ue_ue.TransformGizmoActor.md#load)
- [StaticClass](ue_ue.TransformGizmoActor.md#staticclass)

## Constructors

### constructor

• **new TransformGizmoActor**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GizmoActor](ue_ue.GizmoActor.md).[constructor](ue_ue.GizmoActor.md#constructor)

#### Defined in

[ue/ue.d.ts:64105](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64105)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[ActorLabel](ue_ue.GizmoActor.md#actorlabel)

#### Defined in

[ue/ue.d.ts:13176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13176)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[AttachmentReplication](ue_ue.GizmoActor.md#attachmentreplication)

#### Defined in

[ue/ue.d.ts:13151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13151)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[AutoReceiveInput](ue_ue.GizmoActor.md#autoreceiveinput)

#### Defined in

[ue/ue.d.ts:13157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13157)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[BlueprintCreatedComponents](ue_ue.GizmoActor.md#blueprintcreatedcomponents)

#### Defined in

[ue/ue.d.ts:13206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13206)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[Children](ue_ue.GizmoActor.md#children)

#### Defined in

[ue/ue.d.ts:13166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13166)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[ControllingMatineeActors](ue_ue.GizmoActor.md#controllingmatineeactors)

#### Defined in

[ue/ue.d.ts:13169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13169)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[CustomTimeDilation](ue_ue.GizmoActor.md#customtimedilation)

#### Defined in

[ue/ue.d.ts:13150](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13150)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.GizmoActor.md#defaultupdateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13146](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13146)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[FolderPath](ue_ue.GizmoActor.md#folderpath)

#### Defined in

[ue/ue.d.ts:13177](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13177)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GroupActor](ue_ue.GizmoActor.md#groupactor)

#### Defined in

[ue/ue.d.ts:13173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13173)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[HiddenEditorViews](ue_ue.GizmoActor.md#hiddeneditorviews)

#### Defined in

[ue/ue.d.ts:13175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13175)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[InitialLifeSpan](ue_ue.GizmoActor.md#initiallifespan)

#### Defined in

[ue/ue.d.ts:13149](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13149)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[InputComponent](ue_ue.GizmoActor.md#inputcomponent)

#### Defined in

[ue/ue.d.ts:13159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13159)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[InputPriority](ue_ue.GizmoActor.md#inputpriority)

#### Defined in

[ue/ue.d.ts:13158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13158)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[InstanceComponents](ue_ue.GizmoActor.md#instancecomponents)

#### Defined in

[ue/ue.d.ts:13205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13205)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[Instigator](ue_ue.GizmoActor.md#instigator)

#### Defined in

[ue/ue.d.ts:13165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13165)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[Layers](ue_ue.GizmoActor.md#layers)

#### Defined in

[ue/ue.d.ts:13170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13170)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[MinNetUpdateFrequency](ue_ue.GizmoActor.md#minnetupdatefrequency)

#### Defined in

[ue/ue.d.ts:13163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13163)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[NetCullDistanceSquared](ue_ue.GizmoActor.md#netculldistancesquared)

#### Defined in

[ue/ue.d.ts:13160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13160)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[NetDormancy](ue_ue.GizmoActor.md#netdormancy)

#### Defined in

[ue/ue.d.ts:13155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13155)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[NetDriverName](ue_ue.GizmoActor.md#netdrivername)

#### Defined in

[ue/ue.d.ts:13153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13153)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[NetPriority](ue_ue.GizmoActor.md#netpriority)

#### Defined in

[ue/ue.d.ts:13164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13164)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[NetTag](ue_ue.GizmoActor.md#nettag)

#### Defined in

[ue/ue.d.ts:13161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13161)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[NetUpdateFrequency](ue_ue.GizmoActor.md#netupdatefrequency)

#### Defined in

[ue/ue.d.ts:13162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13162)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnActorBeginOverlap](ue_ue.GizmoActor.md#onactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13192)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnActorEndOverlap](ue_ue.GizmoActor.md#onactorendoverlap)

#### Defined in

[ue/ue.d.ts:13193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13193)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnActorHit](ue_ue.GizmoActor.md#onactorhit)

#### Defined in

[ue/ue.d.ts:13202](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13202)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnBeginCursorOver](ue_ue.GizmoActor.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:13194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13194)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnClicked](ue_ue.GizmoActor.md#onclicked)

#### Defined in

[ue/ue.d.ts:13196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13196)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnDestroyed](ue_ue.GizmoActor.md#ondestroyed)

#### Defined in

[ue/ue.d.ts:13203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13203)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnEndCursorOver](ue_ue.GizmoActor.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:13195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13195)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnEndPlay](ue_ue.GizmoActor.md#onendplay)

#### Defined in

[ue/ue.d.ts:13204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13204)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnInputTouchBegin](ue_ue.GizmoActor.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13198)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnInputTouchEnd](ue_ue.GizmoActor.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:13199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13199)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnInputTouchEnter](ue_ue.GizmoActor.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:13200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13200)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnInputTouchLeave](ue_ue.GizmoActor.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:13201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13201)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnReleased](ue_ue.GizmoActor.md#onreleased)

#### Defined in

[ue/ue.d.ts:13197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13197)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnTakeAnyDamage](ue_ue.GizmoActor.md#ontakeanydamage)

#### Defined in

[ue/ue.d.ts:13189](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13189)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnTakePointDamage](ue_ue.GizmoActor.md#ontakepointdamage)

#### Defined in

[ue/ue.d.ts:13190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13190)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnTakeRadialDamage](ue_ue.GizmoActor.md#ontakeradialdamage)

#### Defined in

[ue/ue.d.ts:13191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13191)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[Owner](ue_ue.GizmoActor.md#owner)

#### Defined in

[ue/ue.d.ts:13152](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13152)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[ParentComponent](ue_ue.GizmoActor.md#parentcomponent)

#### Defined in

[ue/ue.d.ts:13172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13172)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[ParentComponentActor](ue_ue.GizmoActor.md#parentcomponentactor)

#### Defined in

[ue/ue.d.ts:13171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13171)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[PivotOffset](ue_ue.GizmoActor.md#pivotoffset)

#### Defined in

[ue/ue.d.ts:13168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13168)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[PrimaryActorTick](ue_ue.GizmoActor.md#primaryactortick)

#### Defined in

[ue/ue.d.ts:13115](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13115)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[RemoteRole](ue_ue.GizmoActor.md#remoterole)

#### Defined in

[ue/ue.d.ts:13147](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13147)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[ReplicatedMovement](ue_ue.GizmoActor.md#replicatedmovement)

#### Defined in

[ue/ue.d.ts:13148](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13148)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[Role](ue_ue.GizmoActor.md#role)

#### Defined in

[ue/ue.d.ts:13154](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13154)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[RootComponent](ue_ue.GizmoActor.md#rootcomponent)

#### Defined in

[ue/ue.d.ts:13167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13167)

___

### RotateX

• **RotateX**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Defined in

[ue/ue.d.ts:64112](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64112)

___

### RotateY

• **RotateY**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Defined in

[ue/ue.d.ts:64113](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64113)

___

### RotateZ

• **RotateZ**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Defined in

[ue/ue.d.ts:64114](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64114)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[SpawnCollisionHandlingMethod](ue_ue.GizmoActor.md#spawncollisionhandlingmethod)

#### Defined in

[ue/ue.d.ts:13156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13156)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[SpriteScale](ue_ue.GizmoActor.md#spritescale)

#### Defined in

[ue/ue.d.ts:13174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13174)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[Tags](ue_ue.GizmoActor.md#tags)

#### Defined in

[ue/ue.d.ts:13188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13188)

___

### TranslateX

• **TranslateX**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Defined in

[ue/ue.d.ts:64106](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64106)

___

### TranslateXY

• **TranslateXY**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Defined in

[ue/ue.d.ts:64111](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64111)

___

### TranslateXZ

• **TranslateXZ**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Defined in

[ue/ue.d.ts:64110](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64110)

___

### TranslateY

• **TranslateY**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Defined in

[ue/ue.d.ts:64107](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64107)

___

### TranslateYZ

• **TranslateYZ**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Defined in

[ue/ue.d.ts:64109](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64109)

___

### TranslateZ

• **TranslateZ**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Defined in

[ue/ue.d.ts:64108](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64108)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.GizmoActor.md#updateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13145](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13145)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[__tid_Actor__](ue_ue.GizmoActor.md#__tid_actor__)

#### Defined in

[ue/ue.d.ts:13348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13348)

___

### \_\_tid\_GizmoActor\_\_

• **\_\_tid\_GizmoActor\_\_**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[__tid_GizmoActor__](ue_ue.GizmoActor.md#__tid_gizmoactor__)

#### Defined in

[ue/ue.d.ts:37881](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37881)

___

### \_\_tid\_InternalToolFrameworkActor\_\_

• **\_\_tid\_InternalToolFrameworkActor\_\_**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[__tid_InternalToolFrameworkActor__](ue_ue.GizmoActor.md#__tid_internaltoolframeworkactor__)

#### Defined in

[ue/ue.d.ts:37872](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37872)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[__tid_Object__](ue_ue.GizmoActor.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_TransformGizmoActor\_\_

• **\_\_tid\_TransformGizmoActor\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64119)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bActorEnableCollision](ue_ue.GizmoActor.md#bactorenablecollision)

#### Defined in

[ue/ue.d.ts:13143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13143)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bActorIsBeingDestroyed](ue_ue.GizmoActor.md#bactorisbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13144](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13144)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bActorLabelEditable](ue_ue.GizmoActor.md#bactorlabeleditable)

#### Defined in

[ue/ue.d.ts:13183](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13183)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bActorSeamlessTraveled](ue_ue.GizmoActor.md#bactorseamlesstraveled)

#### Defined in

[ue/ue.d.ts:13139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13139)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.GizmoActor.md#ballowreceivetickeventondedicatedserver)

#### Defined in

[ue/ue.d.ts:13142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13142)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bAllowTickBeforeBeginPlay](ue_ue.GizmoActor.md#ballowtickbeforebeginplay)

#### Defined in

[ue/ue.d.ts:13129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13129)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bAlwaysRelevant](ue_ue.GizmoActor.md#balwaysrelevant)

#### Defined in

[ue/ue.d.ts:13120](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13120)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bAutoDestroyWhenFinished](ue_ue.GizmoActor.md#bautodestroywhenfinished)

#### Defined in

[ue/ue.d.ts:13130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13130)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bBlockInput](ue_ue.GizmoActor.md#bblockinput)

#### Defined in

[ue/ue.d.ts:13131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13131)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bCanBeDamaged](ue_ue.GizmoActor.md#bcanbedamaged)

#### Defined in

[ue/ue.d.ts:13132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13132)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bCanBeInCluster](ue_ue.GizmoActor.md#bcanbeincluster)

#### Defined in

[ue/ue.d.ts:13141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13141)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bCollideWhenPlacing](ue_ue.GizmoActor.md#bcollidewhenplacing)

#### Defined in

[ue/ue.d.ts:13133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13133)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bEditable](ue_ue.GizmoActor.md#beditable)

#### Defined in

[ue/ue.d.ts:13184](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13184)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bEnableAutoLODGeneration](ue_ue.GizmoActor.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:13137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13137)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bExchangedRoles](ue_ue.GizmoActor.md#bexchangedroles)

#### Defined in

[ue/ue.d.ts:13123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13123)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bFindCameraComponentWhenViewTarget](ue_ue.GizmoActor.md#bfindcameracomponentwhenviewtarget)

#### Defined in

[ue/ue.d.ts:13134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13134)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.GizmoActor.md#bgenerateoverlapeventsduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13135)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bHidden](ue_ue.GizmoActor.md#bhidden)

#### Defined in

[ue/ue.d.ts:13116](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13116)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bHiddenEd](ue_ue.GizmoActor.md#bhiddened)

#### Defined in

[ue/ue.d.ts:13178](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13178)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bHiddenEdLayer](ue_ue.GizmoActor.md#bhiddenedlayer)

#### Defined in

[ue/ue.d.ts:13180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13180)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bHiddenEdLevel](ue_ue.GizmoActor.md#bhiddenedlevel)

#### Defined in

[ue/ue.d.ts:13181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13181)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bHiddenEdTemporary](ue_ue.GizmoActor.md#bhiddenedtemporary)

#### Defined in

[ue/ue.d.ts:13187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13187)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bIgnoresOriginShifting](ue_ue.GizmoActor.md#bignoresoriginshifting)

#### Defined in

[ue/ue.d.ts:13136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13136)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bIsEditorOnlyActor](ue_ue.GizmoActor.md#biseditoronlyactor)

#### Defined in

[ue/ue.d.ts:13138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13138)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bIsEditorPreviewActor](ue_ue.GizmoActor.md#biseditorpreviewactor)

#### Defined in

[ue/ue.d.ts:13179](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13179)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bListedInSceneOutliner](ue_ue.GizmoActor.md#blistedinsceneoutliner)

#### Defined in

[ue/ue.d.ts:13185](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13185)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bLockLocation](ue_ue.GizmoActor.md#blocklocation)

#### Defined in

[ue/ue.d.ts:13182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13182)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bNetLoadOnClient](ue_ue.GizmoActor.md#bnetloadonclient)

#### Defined in

[ue/ue.d.ts:13124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13124)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bNetStartup](ue_ue.GizmoActor.md#bnetstartup)

#### Defined in

[ue/ue.d.ts:13118](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13118)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bNetTemporary](ue_ue.GizmoActor.md#bnettemporary)

#### Defined in

[ue/ue.d.ts:13117](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13117)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bNetUseOwnerRelevancy](ue_ue.GizmoActor.md#bnetuseownerrelevancy)

#### Defined in

[ue/ue.d.ts:13125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13125)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bOnlyRelevantToOwner](ue_ue.GizmoActor.md#bonlyrelevanttoowner)

#### Defined in

[ue/ue.d.ts:13119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13119)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bOptimizeBPComponentData](ue_ue.GizmoActor.md#boptimizebpcomponentdata)

#### Defined in

[ue/ue.d.ts:13186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13186)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bRelevantForLevelBounds](ue_ue.GizmoActor.md#brelevantforlevelbounds)

#### Defined in

[ue/ue.d.ts:13127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13127)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bRelevantForNetworkReplays](ue_ue.GizmoActor.md#brelevantfornetworkreplays)

#### Defined in

[ue/ue.d.ts:13126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13126)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bReplayRewindable](ue_ue.GizmoActor.md#breplayrewindable)

#### Defined in

[ue/ue.d.ts:13128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13128)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bReplicateMovement](ue_ue.GizmoActor.md#breplicatemovement)

#### Defined in

[ue/ue.d.ts:13121](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13121)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bReplicates](ue_ue.GizmoActor.md#breplicates)

#### Defined in

[ue/ue.d.ts:13140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13140)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[bTearOff](ue_ue.GizmoActor.md#btearoff)

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

[GizmoActor](ue_ue.GizmoActor.md).[ActorHasTag](ue_ue.GizmoActor.md#actorhastag)

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

[GizmoActor](ue_ue.GizmoActor.md).[AddComponent](ue_ue.GizmoActor.md#addcomponent)

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

[GizmoActor](ue_ue.GizmoActor.md).[AddTickPrerequisiteActor](ue_ue.GizmoActor.md#addtickprerequisiteactor)

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

[GizmoActor](ue_ue.GizmoActor.md).[AddTickPrerequisiteComponent](ue_ue.GizmoActor.md#addtickprerequisitecomponent)

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

[GizmoActor](ue_ue.GizmoActor.md).[CreateDefaultSubobject](ue_ue.GizmoActor.md#createdefaultsubobject)

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

[GizmoActor](ue_ue.GizmoActor.md).[DetachRootComponentFromParent](ue_ue.GizmoActor.md#detachrootcomponentfromparent)

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

[GizmoActor](ue_ue.GizmoActor.md).[DisableInput](ue_ue.GizmoActor.md#disableinput)

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

[GizmoActor](ue_ue.GizmoActor.md).[EnableInput](ue_ue.GizmoActor.md#enableinput)

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

[GizmoActor](ue_ue.GizmoActor.md).[ExecuteUbergraph](ue_ue.GizmoActor.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[FlushNetDormancy](ue_ue.GizmoActor.md#flushnetdormancy)

#### Defined in

[ue/ue.d.ts:13214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13214)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[ForceNetUpdate](ue_ue.GizmoActor.md#forcenetupdate)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetActorBounds](ue_ue.GizmoActor.md#getactorbounds)

#### Defined in

[ue/ue.d.ts:13216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13216)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetActorEnableCollision](ue_ue.GizmoActor.md#getactorenablecollision)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetActorEyesViewPoint](ue_ue.GizmoActor.md#getactoreyesviewpoint)

#### Defined in

[ue/ue.d.ts:13218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13218)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetActorForwardVector](ue_ue.GizmoActor.md#getactorforwardvector)

#### Defined in

[ue/ue.d.ts:13219](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13219)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetActorLabel](ue_ue.GizmoActor.md#getactorlabel)

#### Defined in

[ue/ue.d.ts:13220](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13220)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetActorRelativeScale3D](ue_ue.GizmoActor.md#getactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13221](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13221)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetActorRightVector](ue_ue.GizmoActor.md#getactorrightvector)

#### Defined in

[ue/ue.d.ts:13222](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13222)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetActorScale3D](ue_ue.GizmoActor.md#getactorscale3d)

#### Defined in

[ue/ue.d.ts:13223](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13223)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetActorTickInterval](ue_ue.GizmoActor.md#getactortickinterval)

#### Defined in

[ue/ue.d.ts:13224](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13224)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetActorTimeDilation](ue_ue.GizmoActor.md#getactortimedilation)

#### Defined in

[ue/ue.d.ts:13225](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13225)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetActorUpVector](ue_ue.GizmoActor.md#getactorupvector)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetAllChildActors](ue_ue.GizmoActor.md#getallchildactors)

#### Defined in

[ue/ue.d.ts:13227](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13227)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetAttachParentActor](ue_ue.GizmoActor.md#getattachparentactor)

#### Defined in

[ue/ue.d.ts:13229](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13229)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetAttachParentSocketName](ue_ue.GizmoActor.md#getattachparentsocketname)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetAttachedActors](ue_ue.GizmoActor.md#getattachedactors)

#### Defined in

[ue/ue.d.ts:13228](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13228)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetClass](ue_ue.GizmoActor.md#getclass)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetComponentByClass](ue_ue.GizmoActor.md#getcomponentbyclass)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetComponentsByInterface](ue_ue.GizmoActor.md#getcomponentsbyinterface)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetComponentsByTag](ue_ue.GizmoActor.md#getcomponentsbytag)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetDistanceTo](ue_ue.GizmoActor.md#getdistanceto)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetDotProductTo](ue_ue.GizmoActor.md#getdotproductto)

#### Defined in

[ue/ue.d.ts:13235](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13235)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetFolderPath](ue_ue.GizmoActor.md#getfolderpath)

#### Defined in

[ue/ue.d.ts:13236](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13236)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetGameTimeSinceCreation](ue_ue.GizmoActor.md#getgametimesincecreation)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetHorizontalDistanceTo](ue_ue.GizmoActor.md#gethorizontaldistanceto)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetHorizontalDotProductTo](ue_ue.GizmoActor.md#gethorizontaldotproductto)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetInputAxisKeyValue](ue_ue.GizmoActor.md#getinputaxiskeyvalue)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetInputAxisValue](ue_ue.GizmoActor.md#getinputaxisvalue)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetInputVectorAxisValue](ue_ue.GizmoActor.md#getinputvectoraxisvalue)

#### Defined in

[ue/ue.d.ts:13242](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13242)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetInstigator](ue_ue.GizmoActor.md#getinstigator)

#### Defined in

[ue/ue.d.ts:13243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13243)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetInstigatorController](ue_ue.GizmoActor.md#getinstigatorcontroller)

#### Defined in

[ue/ue.d.ts:13244](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13244)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetLifeSpan](ue_ue.GizmoActor.md#getlifespan)

#### Defined in

[ue/ue.d.ts:13245](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13245)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetLocalRole](ue_ue.GizmoActor.md#getlocalrole)

#### Defined in

[ue/ue.d.ts:13246](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13246)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetName](ue_ue.GizmoActor.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetOuter](ue_ue.GizmoActor.md#getouter)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetOverlappingActors](ue_ue.GizmoActor.md#getoverlappingactors)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetOverlappingComponents](ue_ue.GizmoActor.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:13248](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13248)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetOwner](ue_ue.GizmoActor.md#getowner)

#### Defined in

[ue/ue.d.ts:13249](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13249)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetParentActor](ue_ue.GizmoActor.md#getparentactor)

#### Defined in

[ue/ue.d.ts:13250](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13250)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetParentComponent](ue_ue.GizmoActor.md#getparentcomponent)

#### Defined in

[ue/ue.d.ts:13251](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13251)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetRemoteRole](ue_ue.GizmoActor.md#getremoterole)

#### Defined in

[ue/ue.d.ts:13252](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13252)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetSquaredDistanceTo](ue_ue.GizmoActor.md#getsquareddistanceto)

#### Defined in

[ue/ue.d.ts:13253](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13253)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetTickableWhenPaused](ue_ue.GizmoActor.md#gettickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13254](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13254)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetTransform](ue_ue.GizmoActor.md#gettransform)

#### Defined in

[ue/ue.d.ts:13255](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13255)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetVelocity](ue_ue.GizmoActor.md#getvelocity)

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

[GizmoActor](ue_ue.GizmoActor.md).[GetVerticalDistanceTo](ue_ue.GizmoActor.md#getverticaldistanceto)

#### Defined in

[ue/ue.d.ts:13257](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13257)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[GetWorld](ue_ue.GizmoActor.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[HasAuthority](ue_ue.GizmoActor.md#hasauthority)

#### Defined in

[ue/ue.d.ts:13258](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13258)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[IsActorBeingDestroyed](ue_ue.GizmoActor.md#isactorbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13259](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13259)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[IsActorTickEnabled](ue_ue.GizmoActor.md#isactortickenabled)

#### Defined in

[ue/ue.d.ts:13260](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13260)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[IsChildActor](ue_ue.GizmoActor.md#ischildactor)

#### Defined in

[ue/ue.d.ts:13261](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13261)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[IsEditable](ue_ue.GizmoActor.md#iseditable)

#### Defined in

[ue/ue.d.ts:13262](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13262)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[IsHiddenEd](ue_ue.GizmoActor.md#ishiddened)

#### Defined in

[ue/ue.d.ts:13263](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13263)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[IsHiddenEdAtStartup](ue_ue.GizmoActor.md#ishiddenedatstartup)

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

[GizmoActor](ue_ue.GizmoActor.md).[IsOverlappingActor](ue_ue.GizmoActor.md#isoverlappingactor)

#### Defined in

[ue/ue.d.ts:13265](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13265)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[IsSelectable](ue_ue.GizmoActor.md#isselectable)

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

[GizmoActor](ue_ue.GizmoActor.md).[IsTemporarilyHiddenInEditor](ue_ue.GizmoActor.md#istemporarilyhiddenineditor)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_AddActorLocalOffset](ue_ue.GizmoActor.md#k2_addactorlocaloffset)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_AddActorLocalRotation](ue_ue.GizmoActor.md#k2_addactorlocalrotation)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_AddActorLocalTransform](ue_ue.GizmoActor.md#k2_addactorlocaltransform)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_AddActorWorldOffset](ue_ue.GizmoActor.md#k2_addactorworldoffset)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_AddActorWorldRotation](ue_ue.GizmoActor.md#k2_addactorworldrotation)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_AddActorWorldTransform](ue_ue.GizmoActor.md#k2_addactorworldtransform)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_AttachRootComponentTo](ue_ue.GizmoActor.md#k2_attachrootcomponentto)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_AttachRootComponentToActor](ue_ue.GizmoActor.md#k2_attachrootcomponenttoactor)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_AttachToActor](ue_ue.GizmoActor.md#k2_attachtoactor)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_AttachToComponent](ue_ue.GizmoActor.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:13277](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13277)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[K2_DestroyActor](ue_ue.GizmoActor.md#k2_destroyactor)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_DestroyComponent](ue_ue.GizmoActor.md#k2_destroycomponent)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_DetachFromActor](ue_ue.GizmoActor.md#k2_detachfromactor)

#### Defined in

[ue/ue.d.ts:13280](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13280)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[K2_GetActorLocation](ue_ue.GizmoActor.md#k2_getactorlocation)

#### Defined in

[ue/ue.d.ts:13281](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13281)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[K2_GetActorRotation](ue_ue.GizmoActor.md#k2_getactorrotation)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_GetComponentsByClass](ue_ue.GizmoActor.md#k2_getcomponentsbyclass)

#### Defined in

[ue/ue.d.ts:13283](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13283)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[K2_GetRootComponent](ue_ue.GizmoActor.md#k2_getrootcomponent)

#### Defined in

[ue/ue.d.ts:13284](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13284)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_OnBecomeViewTarget](ue_ue.GizmoActor.md#k2_onbecomeviewtarget)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_OnEndViewTarget](ue_ue.GizmoActor.md#k2_onendviewtarget)

#### Defined in

[ue/ue.d.ts:13286](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13286)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[K2_OnReset](ue_ue.GizmoActor.md#k2_onreset)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_SetActorLocation](ue_ue.GizmoActor.md#k2_setactorlocation)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_SetActorLocationAndRotation](ue_ue.GizmoActor.md#k2_setactorlocationandrotation)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_SetActorRelativeLocation](ue_ue.GizmoActor.md#k2_setactorrelativelocation)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_SetActorRelativeRotation](ue_ue.GizmoActor.md#k2_setactorrelativerotation)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_SetActorRelativeTransform](ue_ue.GizmoActor.md#k2_setactorrelativetransform)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_SetActorRotation](ue_ue.GizmoActor.md#k2_setactorrotation)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_SetActorTransform](ue_ue.GizmoActor.md#k2_setactortransform)

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

[GizmoActor](ue_ue.GizmoActor.md).[K2_TeleportTo](ue_ue.GizmoActor.md#k2_teleportto)

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

[GizmoActor](ue_ue.GizmoActor.md).[MakeMIDForMaterial](ue_ue.GizmoActor.md#makemidformaterial)

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

[GizmoActor](ue_ue.GizmoActor.md).[MakeNoise](ue_ue.GizmoActor.md#makenoise)

#### Defined in

[ue/ue.d.ts:13297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13297)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnRep_AttachmentReplication](ue_ue.GizmoActor.md#onrep_attachmentreplication)

#### Defined in

[ue/ue.d.ts:13298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13298)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnRep_Instigator](ue_ue.GizmoActor.md#onrep_instigator)

#### Defined in

[ue/ue.d.ts:13299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13299)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnRep_Owner](ue_ue.GizmoActor.md#onrep_owner)

#### Defined in

[ue/ue.d.ts:13300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13300)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnRep_ReplicateMovement](ue_ue.GizmoActor.md#onrep_replicatemovement)

#### Defined in

[ue/ue.d.ts:13302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13302)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[OnRep_ReplicatedMovement](ue_ue.GizmoActor.md#onrep_replicatedmovement)

#### Defined in

[ue/ue.d.ts:13301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13301)

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

[GizmoActor](ue_ue.GizmoActor.md).[PrestreamTextures](ue_ue.GizmoActor.md#prestreamtextures)

#### Defined in

[ue/ue.d.ts:13303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13303)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[ReceiveActorBeginCursorOver](ue_ue.GizmoActor.md#receiveactorbegincursorover)

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

[GizmoActor](ue_ue.GizmoActor.md).[ReceiveActorBeginOverlap](ue_ue.GizmoActor.md#receiveactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13305)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[ReceiveActorEndCursorOver](ue_ue.GizmoActor.md#receiveactorendcursorover)

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

[GizmoActor](ue_ue.GizmoActor.md).[ReceiveActorEndOverlap](ue_ue.GizmoActor.md#receiveactorendoverlap)

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

[GizmoActor](ue_ue.GizmoActor.md).[ReceiveActorOnClicked](ue_ue.GizmoActor.md#receiveactoronclicked)

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

[GizmoActor](ue_ue.GizmoActor.md).[ReceiveActorOnInputTouchBegin](ue_ue.GizmoActor.md#receiveactoroninputtouchbegin)

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

[GizmoActor](ue_ue.GizmoActor.md).[ReceiveActorOnInputTouchEnd](ue_ue.GizmoActor.md#receiveactoroninputtouchend)

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

[GizmoActor](ue_ue.GizmoActor.md).[ReceiveActorOnInputTouchEnter](ue_ue.GizmoActor.md#receiveactoroninputtouchenter)

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

[GizmoActor](ue_ue.GizmoActor.md).[ReceiveActorOnInputTouchLeave](ue_ue.GizmoActor.md#receiveactoroninputtouchleave)

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

[GizmoActor](ue_ue.GizmoActor.md).[ReceiveActorOnReleased](ue_ue.GizmoActor.md#receiveactoronreleased)

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

[GizmoActor](ue_ue.GizmoActor.md).[ReceiveAnyDamage](ue_ue.GizmoActor.md#receiveanydamage)

#### Defined in

[ue/ue.d.ts:13314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13314)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[ReceiveBeginPlay](ue_ue.GizmoActor.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:13315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13315)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[ReceiveDestroyed](ue_ue.GizmoActor.md#receivedestroyed)

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

[GizmoActor](ue_ue.GizmoActor.md).[ReceiveEndPlay](ue_ue.GizmoActor.md#receiveendplay)

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

[GizmoActor](ue_ue.GizmoActor.md).[ReceiveHit](ue_ue.GizmoActor.md#receivehit)

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

[GizmoActor](ue_ue.GizmoActor.md).[ReceivePointDamage](ue_ue.GizmoActor.md#receivepointdamage)

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

[GizmoActor](ue_ue.GizmoActor.md).[ReceiveRadialDamage](ue_ue.GizmoActor.md#receiveradialdamage)

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

[GizmoActor](ue_ue.GizmoActor.md).[ReceiveTick](ue_ue.GizmoActor.md#receivetick)

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

[GizmoActor](ue_ue.GizmoActor.md).[RemoveTickPrerequisiteActor](ue_ue.GizmoActor.md#removetickprerequisiteactor)

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

[GizmoActor](ue_ue.GizmoActor.md).[RemoveTickPrerequisiteComponent](ue_ue.GizmoActor.md#removetickprerequisitecomponent)

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

[GizmoActor](ue_ue.GizmoActor.md).[SetActorEnableCollision](ue_ue.GizmoActor.md#setactorenablecollision)

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

[GizmoActor](ue_ue.GizmoActor.md).[SetActorHiddenInGame](ue_ue.GizmoActor.md#setactorhiddeningame)

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

[GizmoActor](ue_ue.GizmoActor.md).[SetActorLabel](ue_ue.GizmoActor.md#setactorlabel)

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

[GizmoActor](ue_ue.GizmoActor.md).[SetActorRelativeScale3D](ue_ue.GizmoActor.md#setactorrelativescale3d)

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

[GizmoActor](ue_ue.GizmoActor.md).[SetActorScale3D](ue_ue.GizmoActor.md#setactorscale3d)

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

[GizmoActor](ue_ue.GizmoActor.md).[SetActorTickEnabled](ue_ue.GizmoActor.md#setactortickenabled)

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

[GizmoActor](ue_ue.GizmoActor.md).[SetActorTickInterval](ue_ue.GizmoActor.md#setactortickinterval)

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

[GizmoActor](ue_ue.GizmoActor.md).[SetFolderPath](ue_ue.GizmoActor.md#setfolderpath)

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

[GizmoActor](ue_ue.GizmoActor.md).[SetIsTemporarilyHiddenInEditor](ue_ue.GizmoActor.md#setistemporarilyhiddenineditor)

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

[GizmoActor](ue_ue.GizmoActor.md).[SetLifeSpan](ue_ue.GizmoActor.md#setlifespan)

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

[GizmoActor](ue_ue.GizmoActor.md).[SetNetDormancy](ue_ue.GizmoActor.md#setnetdormancy)

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

[GizmoActor](ue_ue.GizmoActor.md).[SetOwner](ue_ue.GizmoActor.md#setowner)

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

[GizmoActor](ue_ue.GizmoActor.md).[SetReplicateMovement](ue_ue.GizmoActor.md#setreplicatemovement)

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

[GizmoActor](ue_ue.GizmoActor.md).[SetReplicates](ue_ue.GizmoActor.md#setreplicates)

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

[GizmoActor](ue_ue.GizmoActor.md).[SetTickGroup](ue_ue.GizmoActor.md#settickgroup)

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

[GizmoActor](ue_ue.GizmoActor.md).[SetTickableWhenPaused](ue_ue.GizmoActor.md#settickablewhenpaused)

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

[GizmoActor](ue_ue.GizmoActor.md).[SnapRootComponentTo](ue_ue.GizmoActor.md#snaprootcomponentto)

#### Defined in

[ue/ue.d.ts:13340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13340)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[TearOff](ue_ue.GizmoActor.md#tearoff)

#### Defined in

[ue/ue.d.ts:13341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13341)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[GizmoActor](ue_ue.GizmoActor.md).[UserConstructionScript](ue_ue.GizmoActor.md#userconstructionscript)

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

[GizmoActor](ue_ue.GizmoActor.md).[WasRecentlyRendered](ue_ue.GizmoActor.md#wasrecentlyrendered)

#### Defined in

[ue/ue.d.ts:13343](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13343)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TransformGizmoActor`](ue_ue.TransformGizmoActor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TransformGizmoActor`](ue_ue.TransformGizmoActor.md)

#### Overrides

[GizmoActor](ue_ue.GizmoActor.md).[Find](ue_ue.GizmoActor.md#find)

#### Defined in

[ue/ue.d.ts:64116](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64116)

___

### Load

▸ `Static` **Load**(`InName`): [`TransformGizmoActor`](ue_ue.TransformGizmoActor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TransformGizmoActor`](ue_ue.TransformGizmoActor.md)

#### Overrides

[GizmoActor](ue_ue.GizmoActor.md).[Load](ue_ue.GizmoActor.md#load)

#### Defined in

[ue/ue.d.ts:64117](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64117)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GizmoActor](ue_ue.GizmoActor.md).[StaticClass](ue_ue.GizmoActor.md#staticclass)

#### Defined in

[ue/ue.d.ts:64115](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64115)
