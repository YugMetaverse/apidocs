[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VREditorFloatingUI

# Class: VREditorFloatingUI

[ue/ue](../modules/ue_ue.md).VREditorFloatingUI

## Hierarchy

- [`VREditorBaseActor`](ue_ue.VREditorBaseActor.md)

  ↳ **`VREditorFloatingUI`**

  ↳↳ [`VREditorDockableWindow`](ue_ue.VREditorDockableWindow.md)

  ↳↳ [`VREditorFloatingCameraUI`](ue_ue.VREditorFloatingCameraUI.md)

## Table of contents

### Constructors

- [constructor](ue_ue.VREditorFloatingUI.md#constructor)

### Properties

- [ActorLabel](ue_ue.VREditorFloatingUI.md#actorlabel)
- [AttachmentReplication](ue_ue.VREditorFloatingUI.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.VREditorFloatingUI.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.VREditorFloatingUI.md#blueprintcreatedcomponents)
- [Children](ue_ue.VREditorFloatingUI.md#children)
- [ControllingMatineeActors](ue_ue.VREditorFloatingUI.md#controllingmatineeactors)
- [CreationContext](ue_ue.VREditorFloatingUI.md#creationcontext)
- [CustomTimeDilation](ue_ue.VREditorFloatingUI.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.VREditorFloatingUI.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.VREditorFloatingUI.md#folderpath)
- [GroupActor](ue_ue.VREditorFloatingUI.md#groupactor)
- [HiddenEditorViews](ue_ue.VREditorFloatingUI.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.VREditorFloatingUI.md#initiallifespan)
- [InputComponent](ue_ue.VREditorFloatingUI.md#inputcomponent)
- [InputPriority](ue_ue.VREditorFloatingUI.md#inputpriority)
- [InstanceComponents](ue_ue.VREditorFloatingUI.md#instancecomponents)
- [Instigator](ue_ue.VREditorFloatingUI.md#instigator)
- [Layers](ue_ue.VREditorFloatingUI.md#layers)
- [MinNetUpdateFrequency](ue_ue.VREditorFloatingUI.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.VREditorFloatingUI.md#netculldistancesquared)
- [NetDormancy](ue_ue.VREditorFloatingUI.md#netdormancy)
- [NetDriverName](ue_ue.VREditorFloatingUI.md#netdrivername)
- [NetPriority](ue_ue.VREditorFloatingUI.md#netpriority)
- [NetTag](ue_ue.VREditorFloatingUI.md#nettag)
- [NetUpdateFrequency](ue_ue.VREditorFloatingUI.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.VREditorFloatingUI.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.VREditorFloatingUI.md#onactorendoverlap)
- [OnActorHit](ue_ue.VREditorFloatingUI.md#onactorhit)
- [OnBeginCursorOver](ue_ue.VREditorFloatingUI.md#onbegincursorover)
- [OnClicked](ue_ue.VREditorFloatingUI.md#onclicked)
- [OnDestroyed](ue_ue.VREditorFloatingUI.md#ondestroyed)
- [OnEndCursorOver](ue_ue.VREditorFloatingUI.md#onendcursorover)
- [OnEndPlay](ue_ue.VREditorFloatingUI.md#onendplay)
- [OnInputTouchBegin](ue_ue.VREditorFloatingUI.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.VREditorFloatingUI.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.VREditorFloatingUI.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.VREditorFloatingUI.md#oninputtouchleave)
- [OnReleased](ue_ue.VREditorFloatingUI.md#onreleased)
- [OnTakeAnyDamage](ue_ue.VREditorFloatingUI.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.VREditorFloatingUI.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.VREditorFloatingUI.md#ontakeradialdamage)
- [Owner](ue_ue.VREditorFloatingUI.md#owner)
- [ParentComponent](ue_ue.VREditorFloatingUI.md#parentcomponent)
- [ParentComponentActor](ue_ue.VREditorFloatingUI.md#parentcomponentactor)
- [PivotOffset](ue_ue.VREditorFloatingUI.md#pivotoffset)
- [PrimaryActorTick](ue_ue.VREditorFloatingUI.md#primaryactortick)
- [RemoteRole](ue_ue.VREditorFloatingUI.md#remoterole)
- [ReplicatedMovement](ue_ue.VREditorFloatingUI.md#replicatedmovement)
- [Role](ue_ue.VREditorFloatingUI.md#role)
- [RootComponent](ue_ue.VREditorFloatingUI.md#rootcomponent)
- [SpawnCollisionHandlingMethod](ue_ue.VREditorFloatingUI.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.VREditorFloatingUI.md#spritescale)
- [Tags](ue_ue.VREditorFloatingUI.md#tags)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.VREditorFloatingUI.md#updateoverlapsmethodduringlevelstreaming)
- [UserWidget](ue_ue.VREditorFloatingUI.md#userwidget)
- [UserWidgetClass](ue_ue.VREditorFloatingUI.md#userwidgetclass)
- [VRMode](ue_ue.VREditorFloatingUI.md#vrmode)
- [WidgetComponent](ue_ue.VREditorFloatingUI.md#widgetcomponent)
- [WindowMeshComponent](ue_ue.VREditorFloatingUI.md#windowmeshcomponent)
- [\_\_tid\_Actor\_\_](ue_ue.VREditorFloatingUI.md#__tid_actor__)
- [\_\_tid\_Object\_\_](ue_ue.VREditorFloatingUI.md#__tid_object__)
- [\_\_tid\_VREditorBaseActor\_\_](ue_ue.VREditorFloatingUI.md#__tid_vreditorbaseactor__)
- [\_\_tid\_VREditorFloatingUI\_\_](ue_ue.VREditorFloatingUI.md#__tid_vreditorfloatingui__)
- [bActorEnableCollision](ue_ue.VREditorFloatingUI.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.VREditorFloatingUI.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.VREditorFloatingUI.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.VREditorFloatingUI.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.VREditorFloatingUI.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.VREditorFloatingUI.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.VREditorFloatingUI.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.VREditorFloatingUI.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.VREditorFloatingUI.md#bblockinput)
- [bCanBeDamaged](ue_ue.VREditorFloatingUI.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.VREditorFloatingUI.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.VREditorFloatingUI.md#bcollidewhenplacing)
- [bEditable](ue_ue.VREditorFloatingUI.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.VREditorFloatingUI.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.VREditorFloatingUI.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.VREditorFloatingUI.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.VREditorFloatingUI.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.VREditorFloatingUI.md#bhidden)
- [bHiddenEd](ue_ue.VREditorFloatingUI.md#bhiddened)
- [bHiddenEdLayer](ue_ue.VREditorFloatingUI.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.VREditorFloatingUI.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.VREditorFloatingUI.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.VREditorFloatingUI.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.VREditorFloatingUI.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.VREditorFloatingUI.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.VREditorFloatingUI.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.VREditorFloatingUI.md#blocklocation)
- [bNetLoadOnClient](ue_ue.VREditorFloatingUI.md#bnetloadonclient)
- [bNetStartup](ue_ue.VREditorFloatingUI.md#bnetstartup)
- [bNetTemporary](ue_ue.VREditorFloatingUI.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.VREditorFloatingUI.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.VREditorFloatingUI.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.VREditorFloatingUI.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.VREditorFloatingUI.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.VREditorFloatingUI.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.VREditorFloatingUI.md#breplayrewindable)
- [bReplicateMovement](ue_ue.VREditorFloatingUI.md#breplicatemovement)
- [bReplicates](ue_ue.VREditorFloatingUI.md#breplicates)
- [bTearOff](ue_ue.VREditorFloatingUI.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.VREditorFloatingUI.md#actorhastag)
- [AddComponent](ue_ue.VREditorFloatingUI.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.VREditorFloatingUI.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.VREditorFloatingUI.md#addtickprerequisitecomponent)
- [CreateDefaultSubobject](ue_ue.VREditorFloatingUI.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.VREditorFloatingUI.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.VREditorFloatingUI.md#disableinput)
- [EnableInput](ue_ue.VREditorFloatingUI.md#enableinput)
- [ExecuteUbergraph](ue_ue.VREditorFloatingUI.md#executeubergraph)
- [FlushNetDormancy](ue_ue.VREditorFloatingUI.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.VREditorFloatingUI.md#forcenetupdate)
- [GetActorBounds](ue_ue.VREditorFloatingUI.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.VREditorFloatingUI.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.VREditorFloatingUI.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.VREditorFloatingUI.md#getactorforwardvector)
- [GetActorLabel](ue_ue.VREditorFloatingUI.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.VREditorFloatingUI.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.VREditorFloatingUI.md#getactorrightvector)
- [GetActorScale3D](ue_ue.VREditorFloatingUI.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.VREditorFloatingUI.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.VREditorFloatingUI.md#getactortimedilation)
- [GetActorUpVector](ue_ue.VREditorFloatingUI.md#getactorupvector)
- [GetAllChildActors](ue_ue.VREditorFloatingUI.md#getallchildactors)
- [GetAttachParentActor](ue_ue.VREditorFloatingUI.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.VREditorFloatingUI.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.VREditorFloatingUI.md#getattachedactors)
- [GetClass](ue_ue.VREditorFloatingUI.md#getclass)
- [GetComponentByClass](ue_ue.VREditorFloatingUI.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.VREditorFloatingUI.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.VREditorFloatingUI.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.VREditorFloatingUI.md#getdistanceto)
- [GetDotProductTo](ue_ue.VREditorFloatingUI.md#getdotproductto)
- [GetFolderPath](ue_ue.VREditorFloatingUI.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.VREditorFloatingUI.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.VREditorFloatingUI.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.VREditorFloatingUI.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.VREditorFloatingUI.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.VREditorFloatingUI.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.VREditorFloatingUI.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.VREditorFloatingUI.md#getinstigator)
- [GetInstigatorController](ue_ue.VREditorFloatingUI.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.VREditorFloatingUI.md#getlifespan)
- [GetLocalRole](ue_ue.VREditorFloatingUI.md#getlocalrole)
- [GetName](ue_ue.VREditorFloatingUI.md#getname)
- [GetOuter](ue_ue.VREditorFloatingUI.md#getouter)
- [GetOverlappingActors](ue_ue.VREditorFloatingUI.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.VREditorFloatingUI.md#getoverlappingcomponents)
- [GetOwner](ue_ue.VREditorFloatingUI.md#getowner)
- [GetParentActor](ue_ue.VREditorFloatingUI.md#getparentactor)
- [GetParentComponent](ue_ue.VREditorFloatingUI.md#getparentcomponent)
- [GetRemoteRole](ue_ue.VREditorFloatingUI.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.VREditorFloatingUI.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.VREditorFloatingUI.md#gettickablewhenpaused)
- [GetTransform](ue_ue.VREditorFloatingUI.md#gettransform)
- [GetVelocity](ue_ue.VREditorFloatingUI.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.VREditorFloatingUI.md#getverticaldistanceto)
- [GetWorld](ue_ue.VREditorFloatingUI.md#getworld)
- [HasAuthority](ue_ue.VREditorFloatingUI.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.VREditorFloatingUI.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.VREditorFloatingUI.md#isactortickenabled)
- [IsChildActor](ue_ue.VREditorFloatingUI.md#ischildactor)
- [IsEditable](ue_ue.VREditorFloatingUI.md#iseditable)
- [IsHiddenEd](ue_ue.VREditorFloatingUI.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.VREditorFloatingUI.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.VREditorFloatingUI.md#isoverlappingactor)
- [IsSelectable](ue_ue.VREditorFloatingUI.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.VREditorFloatingUI.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.VREditorFloatingUI.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.VREditorFloatingUI.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.VREditorFloatingUI.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.VREditorFloatingUI.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.VREditorFloatingUI.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.VREditorFloatingUI.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.VREditorFloatingUI.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.VREditorFloatingUI.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.VREditorFloatingUI.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.VREditorFloatingUI.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.VREditorFloatingUI.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.VREditorFloatingUI.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.VREditorFloatingUI.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.VREditorFloatingUI.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.VREditorFloatingUI.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.VREditorFloatingUI.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.VREditorFloatingUI.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.VREditorFloatingUI.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.VREditorFloatingUI.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.VREditorFloatingUI.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.VREditorFloatingUI.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.VREditorFloatingUI.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.VREditorFloatingUI.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.VREditorFloatingUI.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.VREditorFloatingUI.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.VREditorFloatingUI.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.VREditorFloatingUI.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.VREditorFloatingUI.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.VREditorFloatingUI.md#makemidformaterial)
- [MakeNoise](ue_ue.VREditorFloatingUI.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.VREditorFloatingUI.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.VREditorFloatingUI.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.VREditorFloatingUI.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.VREditorFloatingUI.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.VREditorFloatingUI.md#onrep_replicatedmovement)
- [PrestreamTextures](ue_ue.VREditorFloatingUI.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.VREditorFloatingUI.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.VREditorFloatingUI.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.VREditorFloatingUI.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.VREditorFloatingUI.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.VREditorFloatingUI.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.VREditorFloatingUI.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.VREditorFloatingUI.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.VREditorFloatingUI.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.VREditorFloatingUI.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.VREditorFloatingUI.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.VREditorFloatingUI.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.VREditorFloatingUI.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.VREditorFloatingUI.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.VREditorFloatingUI.md#receiveendplay)
- [ReceiveHit](ue_ue.VREditorFloatingUI.md#receivehit)
- [ReceivePointDamage](ue_ue.VREditorFloatingUI.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.VREditorFloatingUI.md#receiveradialdamage)
- [ReceiveTick](ue_ue.VREditorFloatingUI.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.VREditorFloatingUI.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.VREditorFloatingUI.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.VREditorFloatingUI.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.VREditorFloatingUI.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.VREditorFloatingUI.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.VREditorFloatingUI.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.VREditorFloatingUI.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.VREditorFloatingUI.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.VREditorFloatingUI.md#setactortickinterval)
- [SetFolderPath](ue_ue.VREditorFloatingUI.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.VREditorFloatingUI.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.VREditorFloatingUI.md#setlifespan)
- [SetNetDormancy](ue_ue.VREditorFloatingUI.md#setnetdormancy)
- [SetOwner](ue_ue.VREditorFloatingUI.md#setowner)
- [SetReplicateMovement](ue_ue.VREditorFloatingUI.md#setreplicatemovement)
- [SetReplicates](ue_ue.VREditorFloatingUI.md#setreplicates)
- [SetTickGroup](ue_ue.VREditorFloatingUI.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.VREditorFloatingUI.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.VREditorFloatingUI.md#snaprootcomponentto)
- [TearOff](ue_ue.VREditorFloatingUI.md#tearoff)
- [UserConstructionScript](ue_ue.VREditorFloatingUI.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.VREditorFloatingUI.md#wasrecentlyrendered)
- [Find](ue_ue.VREditorFloatingUI.md#find)
- [Load](ue_ue.VREditorFloatingUI.md#load)
- [StaticClass](ue_ue.VREditorFloatingUI.md#staticclass)

## Constructors

### constructor

• **new VREditorFloatingUI**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[constructor](ue_ue.VREditorBaseActor.md#constructor)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ActorLabel](ue_ue.VREditorBaseActor.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[AttachmentReplication](ue_ue.VREditorBaseActor.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[AutoReceiveInput](ue_ue.VREditorBaseActor.md#autoreceiveinput)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[BlueprintCreatedComponents](ue_ue.VREditorBaseActor.md#blueprintcreatedcomponents)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[Children](ue_ue.VREditorBaseActor.md#children)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ControllingMatineeActors](ue_ue.VREditorBaseActor.md#controllingmatineeactors)

___

### CreationContext

• **CreationContext**: [`VREditorFloatingUICreationContext`](ue_ue.VREditorFloatingUICreationContext.md)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[CustomTimeDilation](ue_ue.VREditorBaseActor.md#customtimedilation)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.VREditorBaseActor.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[FolderPath](ue_ue.VREditorBaseActor.md#folderpath)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GroupActor](ue_ue.VREditorBaseActor.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[HiddenEditorViews](ue_ue.VREditorBaseActor.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[InitialLifeSpan](ue_ue.VREditorBaseActor.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[InputComponent](ue_ue.VREditorBaseActor.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[InputPriority](ue_ue.VREditorBaseActor.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[InstanceComponents](ue_ue.VREditorBaseActor.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[Instigator](ue_ue.VREditorBaseActor.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[Layers](ue_ue.VREditorBaseActor.md#layers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[MinNetUpdateFrequency](ue_ue.VREditorBaseActor.md#minnetupdatefrequency)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[NetCullDistanceSquared](ue_ue.VREditorBaseActor.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[NetDormancy](ue_ue.VREditorBaseActor.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[NetDriverName](ue_ue.VREditorBaseActor.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[NetPriority](ue_ue.VREditorBaseActor.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[NetTag](ue_ue.VREditorBaseActor.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[NetUpdateFrequency](ue_ue.VREditorBaseActor.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnActorBeginOverlap](ue_ue.VREditorBaseActor.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnActorEndOverlap](ue_ue.VREditorBaseActor.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnActorHit](ue_ue.VREditorBaseActor.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnBeginCursorOver](ue_ue.VREditorBaseActor.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnClicked](ue_ue.VREditorBaseActor.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnDestroyed](ue_ue.VREditorBaseActor.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnEndCursorOver](ue_ue.VREditorBaseActor.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnEndPlay](ue_ue.VREditorBaseActor.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnInputTouchBegin](ue_ue.VREditorBaseActor.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnInputTouchEnd](ue_ue.VREditorBaseActor.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnInputTouchEnter](ue_ue.VREditorBaseActor.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnInputTouchLeave](ue_ue.VREditorBaseActor.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnReleased](ue_ue.VREditorBaseActor.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnTakeAnyDamage](ue_ue.VREditorBaseActor.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnTakePointDamage](ue_ue.VREditorBaseActor.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnTakeRadialDamage](ue_ue.VREditorBaseActor.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[Owner](ue_ue.VREditorBaseActor.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ParentComponent](ue_ue.VREditorBaseActor.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ParentComponentActor](ue_ue.VREditorBaseActor.md#parentcomponentactor)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[PivotOffset](ue_ue.VREditorBaseActor.md#pivotoffset)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[PrimaryActorTick](ue_ue.VREditorBaseActor.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[RemoteRole](ue_ue.VREditorBaseActor.md#remoterole)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReplicatedMovement](ue_ue.VREditorBaseActor.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[Role](ue_ue.VREditorBaseActor.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[RootComponent](ue_ue.VREditorBaseActor.md#rootcomponent)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SpawnCollisionHandlingMethod](ue_ue.VREditorBaseActor.md#spawncollisionhandlingmethod)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SpriteScale](ue_ue.VREditorBaseActor.md#spritescale)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[Tags](ue_ue.VREditorBaseActor.md#tags)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.VREditorBaseActor.md#updateoverlapsmethodduringlevelstreaming)

___

### UserWidget

• **UserWidget**: [`UserWidget`](ue_ue.UserWidget.md)

___

### UserWidgetClass

• **UserWidgetClass**: [`Class`](ue_ue.Class.md)

___

### VRMode

• **VRMode**: [`VREditorMode`](ue_ue.VREditorMode.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[VRMode](ue_ue.VREditorBaseActor.md#vrmode)

___

### WidgetComponent

• **WidgetComponent**: [`VREditorWidgetComponent`](ue_ue.VREditorWidgetComponent.md)

___

### WindowMeshComponent

• **WindowMeshComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[__tid_Actor__](ue_ue.VREditorBaseActor.md#__tid_actor__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[__tid_Object__](ue_ue.VREditorBaseActor.md#__tid_object__)

___

### \_\_tid\_VREditorBaseActor\_\_

• **\_\_tid\_VREditorBaseActor\_\_**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[__tid_VREditorBaseActor__](ue_ue.VREditorBaseActor.md#__tid_vreditorbaseactor__)

___

### \_\_tid\_VREditorFloatingUI\_\_

• **\_\_tid\_VREditorFloatingUI\_\_**: `boolean`

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bActorEnableCollision](ue_ue.VREditorBaseActor.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bActorIsBeingDestroyed](ue_ue.VREditorBaseActor.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bActorLabelEditable](ue_ue.VREditorBaseActor.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bActorSeamlessTraveled](ue_ue.VREditorBaseActor.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.VREditorBaseActor.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bAllowTickBeforeBeginPlay](ue_ue.VREditorBaseActor.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bAlwaysRelevant](ue_ue.VREditorBaseActor.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bAutoDestroyWhenFinished](ue_ue.VREditorBaseActor.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bBlockInput](ue_ue.VREditorBaseActor.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bCanBeDamaged](ue_ue.VREditorBaseActor.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bCanBeInCluster](ue_ue.VREditorBaseActor.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bCollideWhenPlacing](ue_ue.VREditorBaseActor.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bEditable](ue_ue.VREditorBaseActor.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bEnableAutoLODGeneration](ue_ue.VREditorBaseActor.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bExchangedRoles](ue_ue.VREditorBaseActor.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bFindCameraComponentWhenViewTarget](ue_ue.VREditorBaseActor.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.VREditorBaseActor.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bHidden](ue_ue.VREditorBaseActor.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bHiddenEd](ue_ue.VREditorBaseActor.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bHiddenEdLayer](ue_ue.VREditorBaseActor.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bHiddenEdLevel](ue_ue.VREditorBaseActor.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bHiddenEdTemporary](ue_ue.VREditorBaseActor.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bIgnoresOriginShifting](ue_ue.VREditorBaseActor.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bIsEditorOnlyActor](ue_ue.VREditorBaseActor.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bIsEditorPreviewActor](ue_ue.VREditorBaseActor.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bListedInSceneOutliner](ue_ue.VREditorBaseActor.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bLockLocation](ue_ue.VREditorBaseActor.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bNetLoadOnClient](ue_ue.VREditorBaseActor.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bNetStartup](ue_ue.VREditorBaseActor.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bNetTemporary](ue_ue.VREditorBaseActor.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bNetUseOwnerRelevancy](ue_ue.VREditorBaseActor.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bOnlyRelevantToOwner](ue_ue.VREditorBaseActor.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bOptimizeBPComponentData](ue_ue.VREditorBaseActor.md#boptimizebpcomponentdata)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bRelevantForLevelBounds](ue_ue.VREditorBaseActor.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bRelevantForNetworkReplays](ue_ue.VREditorBaseActor.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bReplayRewindable](ue_ue.VREditorBaseActor.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bReplicateMovement](ue_ue.VREditorBaseActor.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bReplicates](ue_ue.VREditorBaseActor.md#breplicates)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[bTearOff](ue_ue.VREditorBaseActor.md#btearoff)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ActorHasTag](ue_ue.VREditorBaseActor.md#actorhastag)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[AddComponent](ue_ue.VREditorBaseActor.md#addcomponent)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[AddTickPrerequisiteActor](ue_ue.VREditorBaseActor.md#addtickprerequisiteactor)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[AddTickPrerequisiteComponent](ue_ue.VREditorBaseActor.md#addtickprerequisitecomponent)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[CreateDefaultSubobject](ue_ue.VREditorBaseActor.md#createdefaultsubobject)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[DetachRootComponentFromParent](ue_ue.VREditorBaseActor.md#detachrootcomponentfromparent)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[DisableInput](ue_ue.VREditorBaseActor.md#disableinput)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[EnableInput](ue_ue.VREditorBaseActor.md#enableinput)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ExecuteUbergraph](ue_ue.VREditorBaseActor.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[FlushNetDormancy](ue_ue.VREditorBaseActor.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ForceNetUpdate](ue_ue.VREditorBaseActor.md#forcenetupdate)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetActorBounds](ue_ue.VREditorBaseActor.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetActorEnableCollision](ue_ue.VREditorBaseActor.md#getactorenablecollision)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetActorEyesViewPoint](ue_ue.VREditorBaseActor.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetActorForwardVector](ue_ue.VREditorBaseActor.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetActorLabel](ue_ue.VREditorBaseActor.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetActorRelativeScale3D](ue_ue.VREditorBaseActor.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetActorRightVector](ue_ue.VREditorBaseActor.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetActorScale3D](ue_ue.VREditorBaseActor.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetActorTickInterval](ue_ue.VREditorBaseActor.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetActorTimeDilation](ue_ue.VREditorBaseActor.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetActorUpVector](ue_ue.VREditorBaseActor.md#getactorupvector)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetAllChildActors](ue_ue.VREditorBaseActor.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetAttachParentActor](ue_ue.VREditorBaseActor.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetAttachParentSocketName](ue_ue.VREditorBaseActor.md#getattachparentsocketname)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetAttachedActors](ue_ue.VREditorBaseActor.md#getattachedactors)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetClass](ue_ue.VREditorBaseActor.md#getclass)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetComponentByClass](ue_ue.VREditorBaseActor.md#getcomponentbyclass)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetComponentsByInterface](ue_ue.VREditorBaseActor.md#getcomponentsbyinterface)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetComponentsByTag](ue_ue.VREditorBaseActor.md#getcomponentsbytag)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetDistanceTo](ue_ue.VREditorBaseActor.md#getdistanceto)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetDotProductTo](ue_ue.VREditorBaseActor.md#getdotproductto)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetFolderPath](ue_ue.VREditorBaseActor.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetGameTimeSinceCreation](ue_ue.VREditorBaseActor.md#getgametimesincecreation)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetHorizontalDistanceTo](ue_ue.VREditorBaseActor.md#gethorizontaldistanceto)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetHorizontalDotProductTo](ue_ue.VREditorBaseActor.md#gethorizontaldotproductto)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetInputAxisKeyValue](ue_ue.VREditorBaseActor.md#getinputaxiskeyvalue)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetInputAxisValue](ue_ue.VREditorBaseActor.md#getinputaxisvalue)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetInputVectorAxisValue](ue_ue.VREditorBaseActor.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetInstigator](ue_ue.VREditorBaseActor.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetInstigatorController](ue_ue.VREditorBaseActor.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetLifeSpan](ue_ue.VREditorBaseActor.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetLocalRole](ue_ue.VREditorBaseActor.md#getlocalrole)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetName](ue_ue.VREditorBaseActor.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetOuter](ue_ue.VREditorBaseActor.md#getouter)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetOverlappingActors](ue_ue.VREditorBaseActor.md#getoverlappingactors)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetOverlappingComponents](ue_ue.VREditorBaseActor.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetOwner](ue_ue.VREditorBaseActor.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetParentActor](ue_ue.VREditorBaseActor.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetParentComponent](ue_ue.VREditorBaseActor.md#getparentcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetRemoteRole](ue_ue.VREditorBaseActor.md#getremoterole)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetSquaredDistanceTo](ue_ue.VREditorBaseActor.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetTickableWhenPaused](ue_ue.VREditorBaseActor.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetTransform](ue_ue.VREditorBaseActor.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetVelocity](ue_ue.VREditorBaseActor.md#getvelocity)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetVerticalDistanceTo](ue_ue.VREditorBaseActor.md#getverticaldistanceto)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[GetWorld](ue_ue.VREditorBaseActor.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[HasAuthority](ue_ue.VREditorBaseActor.md#hasauthority)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[IsActorBeingDestroyed](ue_ue.VREditorBaseActor.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[IsActorTickEnabled](ue_ue.VREditorBaseActor.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[IsChildActor](ue_ue.VREditorBaseActor.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[IsEditable](ue_ue.VREditorBaseActor.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[IsHiddenEd](ue_ue.VREditorBaseActor.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[IsHiddenEdAtStartup](ue_ue.VREditorBaseActor.md#ishiddenedatstartup)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[IsOverlappingActor](ue_ue.VREditorBaseActor.md#isoverlappingactor)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[IsSelectable](ue_ue.VREditorBaseActor.md#isselectable)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[IsTemporarilyHiddenInEditor](ue_ue.VREditorBaseActor.md#istemporarilyhiddenineditor)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_AddActorLocalOffset](ue_ue.VREditorBaseActor.md#k2_addactorlocaloffset)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_AddActorLocalRotation](ue_ue.VREditorBaseActor.md#k2_addactorlocalrotation)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_AddActorLocalTransform](ue_ue.VREditorBaseActor.md#k2_addactorlocaltransform)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_AddActorWorldOffset](ue_ue.VREditorBaseActor.md#k2_addactorworldoffset)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_AddActorWorldRotation](ue_ue.VREditorBaseActor.md#k2_addactorworldrotation)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_AddActorWorldTransform](ue_ue.VREditorBaseActor.md#k2_addactorworldtransform)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_AttachRootComponentTo](ue_ue.VREditorBaseActor.md#k2_attachrootcomponentto)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_AttachRootComponentToActor](ue_ue.VREditorBaseActor.md#k2_attachrootcomponenttoactor)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_AttachToActor](ue_ue.VREditorBaseActor.md#k2_attachtoactor)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_AttachToComponent](ue_ue.VREditorBaseActor.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_DestroyActor](ue_ue.VREditorBaseActor.md#k2_destroyactor)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_DestroyComponent](ue_ue.VREditorBaseActor.md#k2_destroycomponent)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_DetachFromActor](ue_ue.VREditorBaseActor.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_GetActorLocation](ue_ue.VREditorBaseActor.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_GetActorRotation](ue_ue.VREditorBaseActor.md#k2_getactorrotation)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_GetComponentsByClass](ue_ue.VREditorBaseActor.md#k2_getcomponentsbyclass)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_GetRootComponent](ue_ue.VREditorBaseActor.md#k2_getrootcomponent)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_OnBecomeViewTarget](ue_ue.VREditorBaseActor.md#k2_onbecomeviewtarget)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_OnEndViewTarget](ue_ue.VREditorBaseActor.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_OnReset](ue_ue.VREditorBaseActor.md#k2_onreset)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_SetActorLocation](ue_ue.VREditorBaseActor.md#k2_setactorlocation)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_SetActorLocationAndRotation](ue_ue.VREditorBaseActor.md#k2_setactorlocationandrotation)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_SetActorRelativeLocation](ue_ue.VREditorBaseActor.md#k2_setactorrelativelocation)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_SetActorRelativeRotation](ue_ue.VREditorBaseActor.md#k2_setactorrelativerotation)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_SetActorRelativeTransform](ue_ue.VREditorBaseActor.md#k2_setactorrelativetransform)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_SetActorRotation](ue_ue.VREditorBaseActor.md#k2_setactorrotation)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_SetActorTransform](ue_ue.VREditorBaseActor.md#k2_setactortransform)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[K2_TeleportTo](ue_ue.VREditorBaseActor.md#k2_teleportto)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[MakeMIDForMaterial](ue_ue.VREditorBaseActor.md#makemidformaterial)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[MakeNoise](ue_ue.VREditorBaseActor.md#makenoise)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnRep_AttachmentReplication](ue_ue.VREditorBaseActor.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnRep_Instigator](ue_ue.VREditorBaseActor.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnRep_Owner](ue_ue.VREditorBaseActor.md#onrep_owner)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnRep_ReplicateMovement](ue_ue.VREditorBaseActor.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[OnRep_ReplicatedMovement](ue_ue.VREditorBaseActor.md#onrep_replicatedmovement)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[PrestreamTextures](ue_ue.VREditorBaseActor.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceiveActorBeginCursorOver](ue_ue.VREditorBaseActor.md#receiveactorbegincursorover)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceiveActorBeginOverlap](ue_ue.VREditorBaseActor.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceiveActorEndCursorOver](ue_ue.VREditorBaseActor.md#receiveactorendcursorover)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceiveActorEndOverlap](ue_ue.VREditorBaseActor.md#receiveactorendoverlap)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceiveActorOnClicked](ue_ue.VREditorBaseActor.md#receiveactoronclicked)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceiveActorOnInputTouchBegin](ue_ue.VREditorBaseActor.md#receiveactoroninputtouchbegin)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceiveActorOnInputTouchEnd](ue_ue.VREditorBaseActor.md#receiveactoroninputtouchend)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceiveActorOnInputTouchEnter](ue_ue.VREditorBaseActor.md#receiveactoroninputtouchenter)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceiveActorOnInputTouchLeave](ue_ue.VREditorBaseActor.md#receiveactoroninputtouchleave)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceiveActorOnReleased](ue_ue.VREditorBaseActor.md#receiveactoronreleased)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceiveAnyDamage](ue_ue.VREditorBaseActor.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceiveBeginPlay](ue_ue.VREditorBaseActor.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceiveDestroyed](ue_ue.VREditorBaseActor.md#receivedestroyed)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceiveEndPlay](ue_ue.VREditorBaseActor.md#receiveendplay)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceiveHit](ue_ue.VREditorBaseActor.md#receivehit)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceivePointDamage](ue_ue.VREditorBaseActor.md#receivepointdamage)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceiveRadialDamage](ue_ue.VREditorBaseActor.md#receiveradialdamage)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[ReceiveTick](ue_ue.VREditorBaseActor.md#receivetick)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[RemoveTickPrerequisiteActor](ue_ue.VREditorBaseActor.md#removetickprerequisiteactor)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[RemoveTickPrerequisiteComponent](ue_ue.VREditorBaseActor.md#removetickprerequisitecomponent)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SetActorEnableCollision](ue_ue.VREditorBaseActor.md#setactorenablecollision)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SetActorHiddenInGame](ue_ue.VREditorBaseActor.md#setactorhiddeningame)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SetActorLabel](ue_ue.VREditorBaseActor.md#setactorlabel)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SetActorRelativeScale3D](ue_ue.VREditorBaseActor.md#setactorrelativescale3d)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SetActorScale3D](ue_ue.VREditorBaseActor.md#setactorscale3d)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SetActorTickEnabled](ue_ue.VREditorBaseActor.md#setactortickenabled)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SetActorTickInterval](ue_ue.VREditorBaseActor.md#setactortickinterval)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SetFolderPath](ue_ue.VREditorBaseActor.md#setfolderpath)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SetIsTemporarilyHiddenInEditor](ue_ue.VREditorBaseActor.md#setistemporarilyhiddenineditor)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SetLifeSpan](ue_ue.VREditorBaseActor.md#setlifespan)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SetNetDormancy](ue_ue.VREditorBaseActor.md#setnetdormancy)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SetOwner](ue_ue.VREditorBaseActor.md#setowner)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SetReplicateMovement](ue_ue.VREditorBaseActor.md#setreplicatemovement)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SetReplicates](ue_ue.VREditorBaseActor.md#setreplicates)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SetTickGroup](ue_ue.VREditorBaseActor.md#settickgroup)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SetTickableWhenPaused](ue_ue.VREditorBaseActor.md#settickablewhenpaused)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[SnapRootComponentTo](ue_ue.VREditorBaseActor.md#snaprootcomponentto)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[TearOff](ue_ue.VREditorBaseActor.md#tearoff)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[UserConstructionScript](ue_ue.VREditorBaseActor.md#userconstructionscript)

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

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[WasRecentlyRendered](ue_ue.VREditorBaseActor.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VREditorFloatingUI`](ue_ue.VREditorFloatingUI.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VREditorFloatingUI`](ue_ue.VREditorFloatingUI.md)

#### Overrides

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[Find](ue_ue.VREditorBaseActor.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`VREditorFloatingUI`](ue_ue.VREditorFloatingUI.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VREditorFloatingUI`](ue_ue.VREditorFloatingUI.md)

#### Overrides

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[Load](ue_ue.VREditorBaseActor.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[VREditorBaseActor](ue_ue.VREditorBaseActor.md).[StaticClass](ue_ue.VREditorBaseActor.md#staticclass)
