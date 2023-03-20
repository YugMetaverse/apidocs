[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorUtilityCamera

# Class: EditorUtilityCamera

[ue/ue](../modules/ue_ue.md).EditorUtilityCamera

## Hierarchy

- [`CameraActor`](ue_ue.CameraActor.md)

  ↳ **`EditorUtilityCamera`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditorUtilityCamera.md#constructor)

### Properties

- [ActorLabel](ue_ue.EditorUtilityCamera.md#actorlabel)
- [AspectRatio](ue_ue.EditorUtilityCamera.md#aspectratio)
- [AttachmentReplication](ue_ue.EditorUtilityCamera.md#attachmentreplication)
- [AutoActivateForPlayer](ue_ue.EditorUtilityCamera.md#autoactivateforplayer)
- [AutoReceiveInput](ue_ue.EditorUtilityCamera.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.EditorUtilityCamera.md#blueprintcreatedcomponents)
- [CameraComponent](ue_ue.EditorUtilityCamera.md#cameracomponent)
- [Children](ue_ue.EditorUtilityCamera.md#children)
- [ControllingMatineeActors](ue_ue.EditorUtilityCamera.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.EditorUtilityCamera.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.EditorUtilityCamera.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FOVAngle](ue_ue.EditorUtilityCamera.md#fovangle)
- [FolderPath](ue_ue.EditorUtilityCamera.md#folderpath)
- [GroupActor](ue_ue.EditorUtilityCamera.md#groupactor)
- [HiddenEditorViews](ue_ue.EditorUtilityCamera.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.EditorUtilityCamera.md#initiallifespan)
- [InputComponent](ue_ue.EditorUtilityCamera.md#inputcomponent)
- [InputPriority](ue_ue.EditorUtilityCamera.md#inputpriority)
- [InstanceComponents](ue_ue.EditorUtilityCamera.md#instancecomponents)
- [Instigator](ue_ue.EditorUtilityCamera.md#instigator)
- [Layers](ue_ue.EditorUtilityCamera.md#layers)
- [MinNetUpdateFrequency](ue_ue.EditorUtilityCamera.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.EditorUtilityCamera.md#netculldistancesquared)
- [NetDormancy](ue_ue.EditorUtilityCamera.md#netdormancy)
- [NetDriverName](ue_ue.EditorUtilityCamera.md#netdrivername)
- [NetPriority](ue_ue.EditorUtilityCamera.md#netpriority)
- [NetTag](ue_ue.EditorUtilityCamera.md#nettag)
- [NetUpdateFrequency](ue_ue.EditorUtilityCamera.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.EditorUtilityCamera.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.EditorUtilityCamera.md#onactorendoverlap)
- [OnActorHit](ue_ue.EditorUtilityCamera.md#onactorhit)
- [OnBeginCursorOver](ue_ue.EditorUtilityCamera.md#onbegincursorover)
- [OnClicked](ue_ue.EditorUtilityCamera.md#onclicked)
- [OnDestroyed](ue_ue.EditorUtilityCamera.md#ondestroyed)
- [OnEndCursorOver](ue_ue.EditorUtilityCamera.md#onendcursorover)
- [OnEndPlay](ue_ue.EditorUtilityCamera.md#onendplay)
- [OnInputTouchBegin](ue_ue.EditorUtilityCamera.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.EditorUtilityCamera.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.EditorUtilityCamera.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.EditorUtilityCamera.md#oninputtouchleave)
- [OnReleased](ue_ue.EditorUtilityCamera.md#onreleased)
- [OnTakeAnyDamage](ue_ue.EditorUtilityCamera.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.EditorUtilityCamera.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.EditorUtilityCamera.md#ontakeradialdamage)
- [Owner](ue_ue.EditorUtilityCamera.md#owner)
- [ParentComponent](ue_ue.EditorUtilityCamera.md#parentcomponent)
- [ParentComponentActor](ue_ue.EditorUtilityCamera.md#parentcomponentactor)
- [PivotOffset](ue_ue.EditorUtilityCamera.md#pivotoffset)
- [PostProcessBlendWeight](ue_ue.EditorUtilityCamera.md#postprocessblendweight)
- [PostProcessSettings](ue_ue.EditorUtilityCamera.md#postprocesssettings)
- [PrimaryActorTick](ue_ue.EditorUtilityCamera.md#primaryactortick)
- [RemoteRole](ue_ue.EditorUtilityCamera.md#remoterole)
- [ReplicatedMovement](ue_ue.EditorUtilityCamera.md#replicatedmovement)
- [Role](ue_ue.EditorUtilityCamera.md#role)
- [RootComponent](ue_ue.EditorUtilityCamera.md#rootcomponent)
- [SceneComponent](ue_ue.EditorUtilityCamera.md#scenecomponent)
- [SpawnCollisionHandlingMethod](ue_ue.EditorUtilityCamera.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.EditorUtilityCamera.md#spritescale)
- [Tags](ue_ue.EditorUtilityCamera.md#tags)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.EditorUtilityCamera.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.EditorUtilityCamera.md#__tid_actor__)
- [\_\_tid\_CameraActor\_\_](ue_ue.EditorUtilityCamera.md#__tid_cameraactor__)
- [\_\_tid\_EditorUtilityCamera\_\_](ue_ue.EditorUtilityCamera.md#__tid_editorutilitycamera__)
- [\_\_tid\_Object\_\_](ue_ue.EditorUtilityCamera.md#__tid_object__)
- [bActorEnableCollision](ue_ue.EditorUtilityCamera.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.EditorUtilityCamera.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.EditorUtilityCamera.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.EditorUtilityCamera.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.EditorUtilityCamera.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.EditorUtilityCamera.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.EditorUtilityCamera.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.EditorUtilityCamera.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.EditorUtilityCamera.md#bblockinput)
- [bCanBeDamaged](ue_ue.EditorUtilityCamera.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.EditorUtilityCamera.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.EditorUtilityCamera.md#bcollidewhenplacing)
- [bConstrainAspectRatio](ue_ue.EditorUtilityCamera.md#bconstrainaspectratio)
- [bEditable](ue_ue.EditorUtilityCamera.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.EditorUtilityCamera.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.EditorUtilityCamera.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.EditorUtilityCamera.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.EditorUtilityCamera.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.EditorUtilityCamera.md#bhidden)
- [bHiddenEd](ue_ue.EditorUtilityCamera.md#bhiddened)
- [bHiddenEdLayer](ue_ue.EditorUtilityCamera.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.EditorUtilityCamera.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.EditorUtilityCamera.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.EditorUtilityCamera.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.EditorUtilityCamera.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.EditorUtilityCamera.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.EditorUtilityCamera.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.EditorUtilityCamera.md#blocklocation)
- [bNetLoadOnClient](ue_ue.EditorUtilityCamera.md#bnetloadonclient)
- [bNetStartup](ue_ue.EditorUtilityCamera.md#bnetstartup)
- [bNetTemporary](ue_ue.EditorUtilityCamera.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.EditorUtilityCamera.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.EditorUtilityCamera.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.EditorUtilityCamera.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.EditorUtilityCamera.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.EditorUtilityCamera.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.EditorUtilityCamera.md#breplayrewindable)
- [bReplicateMovement](ue_ue.EditorUtilityCamera.md#breplicatemovement)
- [bReplicates](ue_ue.EditorUtilityCamera.md#breplicates)
- [bTearOff](ue_ue.EditorUtilityCamera.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.EditorUtilityCamera.md#actorhastag)
- [AddComponent](ue_ue.EditorUtilityCamera.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.EditorUtilityCamera.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.EditorUtilityCamera.md#addtickprerequisitecomponent)
- [CreateDefaultSubobject](ue_ue.EditorUtilityCamera.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.EditorUtilityCamera.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.EditorUtilityCamera.md#disableinput)
- [EnableInput](ue_ue.EditorUtilityCamera.md#enableinput)
- [ExecuteUbergraph](ue_ue.EditorUtilityCamera.md#executeubergraph)
- [FlushNetDormancy](ue_ue.EditorUtilityCamera.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.EditorUtilityCamera.md#forcenetupdate)
- [GetActorBounds](ue_ue.EditorUtilityCamera.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.EditorUtilityCamera.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.EditorUtilityCamera.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.EditorUtilityCamera.md#getactorforwardvector)
- [GetActorLabel](ue_ue.EditorUtilityCamera.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.EditorUtilityCamera.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.EditorUtilityCamera.md#getactorrightvector)
- [GetActorScale3D](ue_ue.EditorUtilityCamera.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.EditorUtilityCamera.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.EditorUtilityCamera.md#getactortimedilation)
- [GetActorUpVector](ue_ue.EditorUtilityCamera.md#getactorupvector)
- [GetAllChildActors](ue_ue.EditorUtilityCamera.md#getallchildactors)
- [GetAttachParentActor](ue_ue.EditorUtilityCamera.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.EditorUtilityCamera.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.EditorUtilityCamera.md#getattachedactors)
- [GetAutoActivatePlayerIndex](ue_ue.EditorUtilityCamera.md#getautoactivateplayerindex)
- [GetClass](ue_ue.EditorUtilityCamera.md#getclass)
- [GetComponentByClass](ue_ue.EditorUtilityCamera.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.EditorUtilityCamera.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.EditorUtilityCamera.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.EditorUtilityCamera.md#getdistanceto)
- [GetDotProductTo](ue_ue.EditorUtilityCamera.md#getdotproductto)
- [GetFolderPath](ue_ue.EditorUtilityCamera.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.EditorUtilityCamera.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.EditorUtilityCamera.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.EditorUtilityCamera.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.EditorUtilityCamera.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.EditorUtilityCamera.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.EditorUtilityCamera.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.EditorUtilityCamera.md#getinstigator)
- [GetInstigatorController](ue_ue.EditorUtilityCamera.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.EditorUtilityCamera.md#getlifespan)
- [GetLocalRole](ue_ue.EditorUtilityCamera.md#getlocalrole)
- [GetName](ue_ue.EditorUtilityCamera.md#getname)
- [GetOuter](ue_ue.EditorUtilityCamera.md#getouter)
- [GetOverlappingActors](ue_ue.EditorUtilityCamera.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.EditorUtilityCamera.md#getoverlappingcomponents)
- [GetOwner](ue_ue.EditorUtilityCamera.md#getowner)
- [GetParentActor](ue_ue.EditorUtilityCamera.md#getparentactor)
- [GetParentComponent](ue_ue.EditorUtilityCamera.md#getparentcomponent)
- [GetRemoteRole](ue_ue.EditorUtilityCamera.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.EditorUtilityCamera.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.EditorUtilityCamera.md#gettickablewhenpaused)
- [GetTransform](ue_ue.EditorUtilityCamera.md#gettransform)
- [GetVelocity](ue_ue.EditorUtilityCamera.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.EditorUtilityCamera.md#getverticaldistanceto)
- [GetWorld](ue_ue.EditorUtilityCamera.md#getworld)
- [HasAuthority](ue_ue.EditorUtilityCamera.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.EditorUtilityCamera.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.EditorUtilityCamera.md#isactortickenabled)
- [IsChildActor](ue_ue.EditorUtilityCamera.md#ischildactor)
- [IsEditable](ue_ue.EditorUtilityCamera.md#iseditable)
- [IsHiddenEd](ue_ue.EditorUtilityCamera.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.EditorUtilityCamera.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.EditorUtilityCamera.md#isoverlappingactor)
- [IsSelectable](ue_ue.EditorUtilityCamera.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.EditorUtilityCamera.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.EditorUtilityCamera.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.EditorUtilityCamera.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.EditorUtilityCamera.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.EditorUtilityCamera.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.EditorUtilityCamera.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.EditorUtilityCamera.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.EditorUtilityCamera.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.EditorUtilityCamera.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.EditorUtilityCamera.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.EditorUtilityCamera.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.EditorUtilityCamera.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.EditorUtilityCamera.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.EditorUtilityCamera.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.EditorUtilityCamera.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.EditorUtilityCamera.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.EditorUtilityCamera.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.EditorUtilityCamera.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.EditorUtilityCamera.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.EditorUtilityCamera.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.EditorUtilityCamera.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.EditorUtilityCamera.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.EditorUtilityCamera.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.EditorUtilityCamera.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.EditorUtilityCamera.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.EditorUtilityCamera.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.EditorUtilityCamera.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.EditorUtilityCamera.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.EditorUtilityCamera.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.EditorUtilityCamera.md#makemidformaterial)
- [MakeNoise](ue_ue.EditorUtilityCamera.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.EditorUtilityCamera.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.EditorUtilityCamera.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.EditorUtilityCamera.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.EditorUtilityCamera.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.EditorUtilityCamera.md#onrep_replicatedmovement)
- [PrestreamTextures](ue_ue.EditorUtilityCamera.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.EditorUtilityCamera.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.EditorUtilityCamera.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.EditorUtilityCamera.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.EditorUtilityCamera.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.EditorUtilityCamera.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.EditorUtilityCamera.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.EditorUtilityCamera.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.EditorUtilityCamera.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.EditorUtilityCamera.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.EditorUtilityCamera.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.EditorUtilityCamera.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.EditorUtilityCamera.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.EditorUtilityCamera.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.EditorUtilityCamera.md#receiveendplay)
- [ReceiveHit](ue_ue.EditorUtilityCamera.md#receivehit)
- [ReceivePointDamage](ue_ue.EditorUtilityCamera.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.EditorUtilityCamera.md#receiveradialdamage)
- [ReceiveTick](ue_ue.EditorUtilityCamera.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.EditorUtilityCamera.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.EditorUtilityCamera.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.EditorUtilityCamera.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.EditorUtilityCamera.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.EditorUtilityCamera.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.EditorUtilityCamera.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.EditorUtilityCamera.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.EditorUtilityCamera.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.EditorUtilityCamera.md#setactortickinterval)
- [SetFolderPath](ue_ue.EditorUtilityCamera.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.EditorUtilityCamera.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.EditorUtilityCamera.md#setlifespan)
- [SetNetDormancy](ue_ue.EditorUtilityCamera.md#setnetdormancy)
- [SetOwner](ue_ue.EditorUtilityCamera.md#setowner)
- [SetReplicateMovement](ue_ue.EditorUtilityCamera.md#setreplicatemovement)
- [SetReplicates](ue_ue.EditorUtilityCamera.md#setreplicates)
- [SetTickGroup](ue_ue.EditorUtilityCamera.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.EditorUtilityCamera.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.EditorUtilityCamera.md#snaprootcomponentto)
- [TearOff](ue_ue.EditorUtilityCamera.md#tearoff)
- [UserConstructionScript](ue_ue.EditorUtilityCamera.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.EditorUtilityCamera.md#wasrecentlyrendered)
- [Find](ue_ue.EditorUtilityCamera.md#find)
- [Load](ue_ue.EditorUtilityCamera.md#load)
- [StaticClass](ue_ue.EditorUtilityCamera.md#staticclass)

## Constructors

### constructor

• **new EditorUtilityCamera**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[CameraActor](ue_ue.CameraActor.md).[constructor](ue_ue.CameraActor.md#constructor)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[ActorLabel](ue_ue.CameraActor.md#actorlabel)

___

### AspectRatio

• **AspectRatio**: `number`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[AspectRatio](ue_ue.CameraActor.md#aspectratio)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[AttachmentReplication](ue_ue.CameraActor.md#attachmentreplication)

___

### AutoActivateForPlayer

• **AutoActivateForPlayer**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[AutoActivateForPlayer](ue_ue.CameraActor.md#autoactivateforplayer)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[AutoReceiveInput](ue_ue.CameraActor.md#autoreceiveinput)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[BlueprintCreatedComponents](ue_ue.CameraActor.md#blueprintcreatedcomponents)

___

### CameraComponent

• **CameraComponent**: [`CameraComponent`](ue_ue.CameraComponent.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[CameraComponent](ue_ue.CameraActor.md#cameracomponent)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[Children](ue_ue.CameraActor.md#children)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[ControllingMatineeActors](ue_ue.CameraActor.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[CustomTimeDilation](ue_ue.CameraActor.md#customtimedilation)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.CameraActor.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FOVAngle

• **FOVAngle**: `number`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[FOVAngle](ue_ue.CameraActor.md#fovangle)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[FolderPath](ue_ue.CameraActor.md#folderpath)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GroupActor](ue_ue.CameraActor.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[HiddenEditorViews](ue_ue.CameraActor.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[InitialLifeSpan](ue_ue.CameraActor.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[InputComponent](ue_ue.CameraActor.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[InputPriority](ue_ue.CameraActor.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[InstanceComponents](ue_ue.CameraActor.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[Instigator](ue_ue.CameraActor.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[Layers](ue_ue.CameraActor.md#layers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[MinNetUpdateFrequency](ue_ue.CameraActor.md#minnetupdatefrequency)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[NetCullDistanceSquared](ue_ue.CameraActor.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[NetDormancy](ue_ue.CameraActor.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[NetDriverName](ue_ue.CameraActor.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[NetPriority](ue_ue.CameraActor.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[NetTag](ue_ue.CameraActor.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[NetUpdateFrequency](ue_ue.CameraActor.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnActorBeginOverlap](ue_ue.CameraActor.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnActorEndOverlap](ue_ue.CameraActor.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnActorHit](ue_ue.CameraActor.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnBeginCursorOver](ue_ue.CameraActor.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnClicked](ue_ue.CameraActor.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnDestroyed](ue_ue.CameraActor.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnEndCursorOver](ue_ue.CameraActor.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnEndPlay](ue_ue.CameraActor.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnInputTouchBegin](ue_ue.CameraActor.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnInputTouchEnd](ue_ue.CameraActor.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnInputTouchEnter](ue_ue.CameraActor.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnInputTouchLeave](ue_ue.CameraActor.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnReleased](ue_ue.CameraActor.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnTakeAnyDamage](ue_ue.CameraActor.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnTakePointDamage](ue_ue.CameraActor.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnTakeRadialDamage](ue_ue.CameraActor.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[Owner](ue_ue.CameraActor.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[ParentComponent](ue_ue.CameraActor.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[ParentComponentActor](ue_ue.CameraActor.md#parentcomponentactor)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[PivotOffset](ue_ue.CameraActor.md#pivotoffset)

___

### PostProcessBlendWeight

• **PostProcessBlendWeight**: `number`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[PostProcessBlendWeight](ue_ue.CameraActor.md#postprocessblendweight)

___

### PostProcessSettings

• **PostProcessSettings**: [`PostProcessSettings`](ue_ue.PostProcessSettings.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[PostProcessSettings](ue_ue.CameraActor.md#postprocesssettings)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[PrimaryActorTick](ue_ue.CameraActor.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[RemoteRole](ue_ue.CameraActor.md#remoterole)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[ReplicatedMovement](ue_ue.CameraActor.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[Role](ue_ue.CameraActor.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[RootComponent](ue_ue.CameraActor.md#rootcomponent)

___

### SceneComponent

• **SceneComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[SceneComponent](ue_ue.CameraActor.md#scenecomponent)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[SpawnCollisionHandlingMethod](ue_ue.CameraActor.md#spawncollisionhandlingmethod)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[SpriteScale](ue_ue.CameraActor.md#spritescale)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[Tags](ue_ue.CameraActor.md#tags)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.CameraActor.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[__tid_Actor__](ue_ue.CameraActor.md#__tid_actor__)

___

### \_\_tid\_CameraActor\_\_

• **\_\_tid\_CameraActor\_\_**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[__tid_CameraActor__](ue_ue.CameraActor.md#__tid_cameraactor__)

___

### \_\_tid\_EditorUtilityCamera\_\_

• **\_\_tid\_EditorUtilityCamera\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[__tid_Object__](ue_ue.CameraActor.md#__tid_object__)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bActorEnableCollision](ue_ue.CameraActor.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bActorIsBeingDestroyed](ue_ue.CameraActor.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bActorLabelEditable](ue_ue.CameraActor.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bActorSeamlessTraveled](ue_ue.CameraActor.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.CameraActor.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bAllowTickBeforeBeginPlay](ue_ue.CameraActor.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bAlwaysRelevant](ue_ue.CameraActor.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bAutoDestroyWhenFinished](ue_ue.CameraActor.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bBlockInput](ue_ue.CameraActor.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bCanBeDamaged](ue_ue.CameraActor.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bCanBeInCluster](ue_ue.CameraActor.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bCollideWhenPlacing](ue_ue.CameraActor.md#bcollidewhenplacing)

___

### bConstrainAspectRatio

• **bConstrainAspectRatio**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bConstrainAspectRatio](ue_ue.CameraActor.md#bconstrainaspectratio)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bEditable](ue_ue.CameraActor.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bEnableAutoLODGeneration](ue_ue.CameraActor.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bExchangedRoles](ue_ue.CameraActor.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bFindCameraComponentWhenViewTarget](ue_ue.CameraActor.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.CameraActor.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bHidden](ue_ue.CameraActor.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bHiddenEd](ue_ue.CameraActor.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bHiddenEdLayer](ue_ue.CameraActor.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bHiddenEdLevel](ue_ue.CameraActor.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bHiddenEdTemporary](ue_ue.CameraActor.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bIgnoresOriginShifting](ue_ue.CameraActor.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bIsEditorOnlyActor](ue_ue.CameraActor.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bIsEditorPreviewActor](ue_ue.CameraActor.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bListedInSceneOutliner](ue_ue.CameraActor.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bLockLocation](ue_ue.CameraActor.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bNetLoadOnClient](ue_ue.CameraActor.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bNetStartup](ue_ue.CameraActor.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bNetTemporary](ue_ue.CameraActor.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bNetUseOwnerRelevancy](ue_ue.CameraActor.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bOnlyRelevantToOwner](ue_ue.CameraActor.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bOptimizeBPComponentData](ue_ue.CameraActor.md#boptimizebpcomponentdata)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bRelevantForLevelBounds](ue_ue.CameraActor.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bRelevantForNetworkReplays](ue_ue.CameraActor.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bReplayRewindable](ue_ue.CameraActor.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bReplicateMovement](ue_ue.CameraActor.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bReplicates](ue_ue.CameraActor.md#breplicates)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[bTearOff](ue_ue.CameraActor.md#btearoff)

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

[CameraActor](ue_ue.CameraActor.md).[ActorHasTag](ue_ue.CameraActor.md#actorhastag)

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

[CameraActor](ue_ue.CameraActor.md).[AddComponent](ue_ue.CameraActor.md#addcomponent)

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

[CameraActor](ue_ue.CameraActor.md).[AddTickPrerequisiteActor](ue_ue.CameraActor.md#addtickprerequisiteactor)

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

[CameraActor](ue_ue.CameraActor.md).[AddTickPrerequisiteComponent](ue_ue.CameraActor.md#addtickprerequisitecomponent)

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

[CameraActor](ue_ue.CameraActor.md).[CreateDefaultSubobject](ue_ue.CameraActor.md#createdefaultsubobject)

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

[CameraActor](ue_ue.CameraActor.md).[DetachRootComponentFromParent](ue_ue.CameraActor.md#detachrootcomponentfromparent)

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

[CameraActor](ue_ue.CameraActor.md).[DisableInput](ue_ue.CameraActor.md#disableinput)

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

[CameraActor](ue_ue.CameraActor.md).[EnableInput](ue_ue.CameraActor.md#enableinput)

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

[CameraActor](ue_ue.CameraActor.md).[ExecuteUbergraph](ue_ue.CameraActor.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[FlushNetDormancy](ue_ue.CameraActor.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[ForceNetUpdate](ue_ue.CameraActor.md#forcenetupdate)

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

[CameraActor](ue_ue.CameraActor.md).[GetActorBounds](ue_ue.CameraActor.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetActorEnableCollision](ue_ue.CameraActor.md#getactorenablecollision)

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

[CameraActor](ue_ue.CameraActor.md).[GetActorEyesViewPoint](ue_ue.CameraActor.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetActorForwardVector](ue_ue.CameraActor.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetActorLabel](ue_ue.CameraActor.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetActorRelativeScale3D](ue_ue.CameraActor.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetActorRightVector](ue_ue.CameraActor.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetActorScale3D](ue_ue.CameraActor.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetActorTickInterval](ue_ue.CameraActor.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetActorTimeDilation](ue_ue.CameraActor.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetActorUpVector](ue_ue.CameraActor.md#getactorupvector)

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

[CameraActor](ue_ue.CameraActor.md).[GetAllChildActors](ue_ue.CameraActor.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetAttachParentActor](ue_ue.CameraActor.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetAttachParentSocketName](ue_ue.CameraActor.md#getattachparentsocketname)

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

[CameraActor](ue_ue.CameraActor.md).[GetAttachedActors](ue_ue.CameraActor.md#getattachedactors)

___

### GetAutoActivatePlayerIndex

▸ **GetAutoActivatePlayerIndex**(): `number`

#### Returns

`number`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetAutoActivatePlayerIndex](ue_ue.CameraActor.md#getautoactivateplayerindex)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetClass](ue_ue.CameraActor.md#getclass)

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

[CameraActor](ue_ue.CameraActor.md).[GetComponentByClass](ue_ue.CameraActor.md#getcomponentbyclass)

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

[CameraActor](ue_ue.CameraActor.md).[GetComponentsByInterface](ue_ue.CameraActor.md#getcomponentsbyinterface)

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

[CameraActor](ue_ue.CameraActor.md).[GetComponentsByTag](ue_ue.CameraActor.md#getcomponentsbytag)

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

[CameraActor](ue_ue.CameraActor.md).[GetDistanceTo](ue_ue.CameraActor.md#getdistanceto)

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

[CameraActor](ue_ue.CameraActor.md).[GetDotProductTo](ue_ue.CameraActor.md#getdotproductto)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetFolderPath](ue_ue.CameraActor.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetGameTimeSinceCreation](ue_ue.CameraActor.md#getgametimesincecreation)

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

[CameraActor](ue_ue.CameraActor.md).[GetHorizontalDistanceTo](ue_ue.CameraActor.md#gethorizontaldistanceto)

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

[CameraActor](ue_ue.CameraActor.md).[GetHorizontalDotProductTo](ue_ue.CameraActor.md#gethorizontaldotproductto)

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

[CameraActor](ue_ue.CameraActor.md).[GetInputAxisKeyValue](ue_ue.CameraActor.md#getinputaxiskeyvalue)

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

[CameraActor](ue_ue.CameraActor.md).[GetInputAxisValue](ue_ue.CameraActor.md#getinputaxisvalue)

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

[CameraActor](ue_ue.CameraActor.md).[GetInputVectorAxisValue](ue_ue.CameraActor.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetInstigator](ue_ue.CameraActor.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetInstigatorController](ue_ue.CameraActor.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetLifeSpan](ue_ue.CameraActor.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetLocalRole](ue_ue.CameraActor.md#getlocalrole)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetName](ue_ue.CameraActor.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetOuter](ue_ue.CameraActor.md#getouter)

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

[CameraActor](ue_ue.CameraActor.md).[GetOverlappingActors](ue_ue.CameraActor.md#getoverlappingactors)

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

[CameraActor](ue_ue.CameraActor.md).[GetOverlappingComponents](ue_ue.CameraActor.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetOwner](ue_ue.CameraActor.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetParentActor](ue_ue.CameraActor.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetParentComponent](ue_ue.CameraActor.md#getparentcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetRemoteRole](ue_ue.CameraActor.md#getremoterole)

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

[CameraActor](ue_ue.CameraActor.md).[GetSquaredDistanceTo](ue_ue.CameraActor.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetTickableWhenPaused](ue_ue.CameraActor.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetTransform](ue_ue.CameraActor.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetVelocity](ue_ue.CameraActor.md#getvelocity)

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

[CameraActor](ue_ue.CameraActor.md).[GetVerticalDistanceTo](ue_ue.CameraActor.md#getverticaldistanceto)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[GetWorld](ue_ue.CameraActor.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[HasAuthority](ue_ue.CameraActor.md#hasauthority)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[IsActorBeingDestroyed](ue_ue.CameraActor.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[IsActorTickEnabled](ue_ue.CameraActor.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[IsChildActor](ue_ue.CameraActor.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[IsEditable](ue_ue.CameraActor.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[IsHiddenEd](ue_ue.CameraActor.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[IsHiddenEdAtStartup](ue_ue.CameraActor.md#ishiddenedatstartup)

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

[CameraActor](ue_ue.CameraActor.md).[IsOverlappingActor](ue_ue.CameraActor.md#isoverlappingactor)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[IsSelectable](ue_ue.CameraActor.md#isselectable)

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

[CameraActor](ue_ue.CameraActor.md).[IsTemporarilyHiddenInEditor](ue_ue.CameraActor.md#istemporarilyhiddenineditor)

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

[CameraActor](ue_ue.CameraActor.md).[K2_AddActorLocalOffset](ue_ue.CameraActor.md#k2_addactorlocaloffset)

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

[CameraActor](ue_ue.CameraActor.md).[K2_AddActorLocalRotation](ue_ue.CameraActor.md#k2_addactorlocalrotation)

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

[CameraActor](ue_ue.CameraActor.md).[K2_AddActorLocalTransform](ue_ue.CameraActor.md#k2_addactorlocaltransform)

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

[CameraActor](ue_ue.CameraActor.md).[K2_AddActorWorldOffset](ue_ue.CameraActor.md#k2_addactorworldoffset)

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

[CameraActor](ue_ue.CameraActor.md).[K2_AddActorWorldRotation](ue_ue.CameraActor.md#k2_addactorworldrotation)

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

[CameraActor](ue_ue.CameraActor.md).[K2_AddActorWorldTransform](ue_ue.CameraActor.md#k2_addactorworldtransform)

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

[CameraActor](ue_ue.CameraActor.md).[K2_AttachRootComponentTo](ue_ue.CameraActor.md#k2_attachrootcomponentto)

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

[CameraActor](ue_ue.CameraActor.md).[K2_AttachRootComponentToActor](ue_ue.CameraActor.md#k2_attachrootcomponenttoactor)

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

[CameraActor](ue_ue.CameraActor.md).[K2_AttachToActor](ue_ue.CameraActor.md#k2_attachtoactor)

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

[CameraActor](ue_ue.CameraActor.md).[K2_AttachToComponent](ue_ue.CameraActor.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[K2_DestroyActor](ue_ue.CameraActor.md#k2_destroyactor)

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

[CameraActor](ue_ue.CameraActor.md).[K2_DestroyComponent](ue_ue.CameraActor.md#k2_destroycomponent)

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

[CameraActor](ue_ue.CameraActor.md).[K2_DetachFromActor](ue_ue.CameraActor.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[K2_GetActorLocation](ue_ue.CameraActor.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[K2_GetActorRotation](ue_ue.CameraActor.md#k2_getactorrotation)

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

[CameraActor](ue_ue.CameraActor.md).[K2_GetComponentsByClass](ue_ue.CameraActor.md#k2_getcomponentsbyclass)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[K2_GetRootComponent](ue_ue.CameraActor.md#k2_getrootcomponent)

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

[CameraActor](ue_ue.CameraActor.md).[K2_OnBecomeViewTarget](ue_ue.CameraActor.md#k2_onbecomeviewtarget)

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

[CameraActor](ue_ue.CameraActor.md).[K2_OnEndViewTarget](ue_ue.CameraActor.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[K2_OnReset](ue_ue.CameraActor.md#k2_onreset)

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

[CameraActor](ue_ue.CameraActor.md).[K2_SetActorLocation](ue_ue.CameraActor.md#k2_setactorlocation)

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

[CameraActor](ue_ue.CameraActor.md).[K2_SetActorLocationAndRotation](ue_ue.CameraActor.md#k2_setactorlocationandrotation)

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

[CameraActor](ue_ue.CameraActor.md).[K2_SetActorRelativeLocation](ue_ue.CameraActor.md#k2_setactorrelativelocation)

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

[CameraActor](ue_ue.CameraActor.md).[K2_SetActorRelativeRotation](ue_ue.CameraActor.md#k2_setactorrelativerotation)

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

[CameraActor](ue_ue.CameraActor.md).[K2_SetActorRelativeTransform](ue_ue.CameraActor.md#k2_setactorrelativetransform)

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

[CameraActor](ue_ue.CameraActor.md).[K2_SetActorRotation](ue_ue.CameraActor.md#k2_setactorrotation)

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

[CameraActor](ue_ue.CameraActor.md).[K2_SetActorTransform](ue_ue.CameraActor.md#k2_setactortransform)

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

[CameraActor](ue_ue.CameraActor.md).[K2_TeleportTo](ue_ue.CameraActor.md#k2_teleportto)

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

[CameraActor](ue_ue.CameraActor.md).[MakeMIDForMaterial](ue_ue.CameraActor.md#makemidformaterial)

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

[CameraActor](ue_ue.CameraActor.md).[MakeNoise](ue_ue.CameraActor.md#makenoise)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnRep_AttachmentReplication](ue_ue.CameraActor.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnRep_Instigator](ue_ue.CameraActor.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnRep_Owner](ue_ue.CameraActor.md#onrep_owner)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnRep_ReplicateMovement](ue_ue.CameraActor.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[OnRep_ReplicatedMovement](ue_ue.CameraActor.md#onrep_replicatedmovement)

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

[CameraActor](ue_ue.CameraActor.md).[PrestreamTextures](ue_ue.CameraActor.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[ReceiveActorBeginCursorOver](ue_ue.CameraActor.md#receiveactorbegincursorover)

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

[CameraActor](ue_ue.CameraActor.md).[ReceiveActorBeginOverlap](ue_ue.CameraActor.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[ReceiveActorEndCursorOver](ue_ue.CameraActor.md#receiveactorendcursorover)

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

[CameraActor](ue_ue.CameraActor.md).[ReceiveActorEndOverlap](ue_ue.CameraActor.md#receiveactorendoverlap)

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

[CameraActor](ue_ue.CameraActor.md).[ReceiveActorOnClicked](ue_ue.CameraActor.md#receiveactoronclicked)

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

[CameraActor](ue_ue.CameraActor.md).[ReceiveActorOnInputTouchBegin](ue_ue.CameraActor.md#receiveactoroninputtouchbegin)

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

[CameraActor](ue_ue.CameraActor.md).[ReceiveActorOnInputTouchEnd](ue_ue.CameraActor.md#receiveactoroninputtouchend)

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

[CameraActor](ue_ue.CameraActor.md).[ReceiveActorOnInputTouchEnter](ue_ue.CameraActor.md#receiveactoroninputtouchenter)

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

[CameraActor](ue_ue.CameraActor.md).[ReceiveActorOnInputTouchLeave](ue_ue.CameraActor.md#receiveactoroninputtouchleave)

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

[CameraActor](ue_ue.CameraActor.md).[ReceiveActorOnReleased](ue_ue.CameraActor.md#receiveactoronreleased)

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

[CameraActor](ue_ue.CameraActor.md).[ReceiveAnyDamage](ue_ue.CameraActor.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[ReceiveBeginPlay](ue_ue.CameraActor.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[ReceiveDestroyed](ue_ue.CameraActor.md#receivedestroyed)

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

[CameraActor](ue_ue.CameraActor.md).[ReceiveEndPlay](ue_ue.CameraActor.md#receiveendplay)

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

[CameraActor](ue_ue.CameraActor.md).[ReceiveHit](ue_ue.CameraActor.md#receivehit)

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

[CameraActor](ue_ue.CameraActor.md).[ReceivePointDamage](ue_ue.CameraActor.md#receivepointdamage)

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

[CameraActor](ue_ue.CameraActor.md).[ReceiveRadialDamage](ue_ue.CameraActor.md#receiveradialdamage)

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

[CameraActor](ue_ue.CameraActor.md).[ReceiveTick](ue_ue.CameraActor.md#receivetick)

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

[CameraActor](ue_ue.CameraActor.md).[RemoveTickPrerequisiteActor](ue_ue.CameraActor.md#removetickprerequisiteactor)

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

[CameraActor](ue_ue.CameraActor.md).[RemoveTickPrerequisiteComponent](ue_ue.CameraActor.md#removetickprerequisitecomponent)

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

[CameraActor](ue_ue.CameraActor.md).[SetActorEnableCollision](ue_ue.CameraActor.md#setactorenablecollision)

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

[CameraActor](ue_ue.CameraActor.md).[SetActorHiddenInGame](ue_ue.CameraActor.md#setactorhiddeningame)

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

[CameraActor](ue_ue.CameraActor.md).[SetActorLabel](ue_ue.CameraActor.md#setactorlabel)

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

[CameraActor](ue_ue.CameraActor.md).[SetActorRelativeScale3D](ue_ue.CameraActor.md#setactorrelativescale3d)

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

[CameraActor](ue_ue.CameraActor.md).[SetActorScale3D](ue_ue.CameraActor.md#setactorscale3d)

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

[CameraActor](ue_ue.CameraActor.md).[SetActorTickEnabled](ue_ue.CameraActor.md#setactortickenabled)

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

[CameraActor](ue_ue.CameraActor.md).[SetActorTickInterval](ue_ue.CameraActor.md#setactortickinterval)

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

[CameraActor](ue_ue.CameraActor.md).[SetFolderPath](ue_ue.CameraActor.md#setfolderpath)

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

[CameraActor](ue_ue.CameraActor.md).[SetIsTemporarilyHiddenInEditor](ue_ue.CameraActor.md#setistemporarilyhiddenineditor)

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

[CameraActor](ue_ue.CameraActor.md).[SetLifeSpan](ue_ue.CameraActor.md#setlifespan)

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

[CameraActor](ue_ue.CameraActor.md).[SetNetDormancy](ue_ue.CameraActor.md#setnetdormancy)

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

[CameraActor](ue_ue.CameraActor.md).[SetOwner](ue_ue.CameraActor.md#setowner)

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

[CameraActor](ue_ue.CameraActor.md).[SetReplicateMovement](ue_ue.CameraActor.md#setreplicatemovement)

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

[CameraActor](ue_ue.CameraActor.md).[SetReplicates](ue_ue.CameraActor.md#setreplicates)

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

[CameraActor](ue_ue.CameraActor.md).[SetTickGroup](ue_ue.CameraActor.md#settickgroup)

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

[CameraActor](ue_ue.CameraActor.md).[SetTickableWhenPaused](ue_ue.CameraActor.md#settickablewhenpaused)

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

[CameraActor](ue_ue.CameraActor.md).[SnapRootComponentTo](ue_ue.CameraActor.md#snaprootcomponentto)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[TearOff](ue_ue.CameraActor.md#tearoff)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[CameraActor](ue_ue.CameraActor.md).[UserConstructionScript](ue_ue.CameraActor.md#userconstructionscript)

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

[CameraActor](ue_ue.CameraActor.md).[WasRecentlyRendered](ue_ue.CameraActor.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorUtilityCamera`](ue_ue.EditorUtilityCamera.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorUtilityCamera`](ue_ue.EditorUtilityCamera.md)

#### Overrides

[CameraActor](ue_ue.CameraActor.md).[Find](ue_ue.CameraActor.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorUtilityCamera`](ue_ue.EditorUtilityCamera.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorUtilityCamera`](ue_ue.EditorUtilityCamera.md)

#### Overrides

[CameraActor](ue_ue.CameraActor.md).[Load](ue_ue.CameraActor.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[CameraActor](ue_ue.CameraActor.md).[StaticClass](ue_ue.CameraActor.md#staticclass)
