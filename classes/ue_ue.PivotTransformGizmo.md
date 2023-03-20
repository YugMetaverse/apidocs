[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PivotTransformGizmo

# Class: PivotTransformGizmo

[ue/ue](../modules/ue_ue.md).PivotTransformGizmo

## Hierarchy

- [`BaseTransformGizmo`](ue_ue.BaseTransformGizmo.md)

  ↳ **`PivotTransformGizmo`**

## Table of contents

### Constructors

- [constructor](ue_ue.PivotTransformGizmo.md#constructor)

### Properties

- [ActorLabel](ue_ue.PivotTransformGizmo.md#actorlabel)
- [AllHandleGroups](ue_ue.PivotTransformGizmo.md#allhandlegroups)
- [AttachmentReplication](ue_ue.PivotTransformGizmo.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.PivotTransformGizmo.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.PivotTransformGizmo.md#blueprintcreatedcomponents)
- [Children](ue_ue.PivotTransformGizmo.md#children)
- [ControllingMatineeActors](ue_ue.PivotTransformGizmo.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.PivotTransformGizmo.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.PivotTransformGizmo.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.PivotTransformGizmo.md#folderpath)
- [GroupActor](ue_ue.PivotTransformGizmo.md#groupactor)
- [HiddenEditorViews](ue_ue.PivotTransformGizmo.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.PivotTransformGizmo.md#initiallifespan)
- [InputComponent](ue_ue.PivotTransformGizmo.md#inputcomponent)
- [InputPriority](ue_ue.PivotTransformGizmo.md#inputpriority)
- [InstanceComponents](ue_ue.PivotTransformGizmo.md#instancecomponents)
- [Instigator](ue_ue.PivotTransformGizmo.md#instigator)
- [LastDraggingHandle](ue_ue.PivotTransformGizmo.md#lastdragginghandle)
- [Layers](ue_ue.PivotTransformGizmo.md#layers)
- [MinNetUpdateFrequency](ue_ue.PivotTransformGizmo.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.PivotTransformGizmo.md#netculldistancesquared)
- [NetDormancy](ue_ue.PivotTransformGizmo.md#netdormancy)
- [NetDriverName](ue_ue.PivotTransformGizmo.md#netdrivername)
- [NetPriority](ue_ue.PivotTransformGizmo.md#netpriority)
- [NetTag](ue_ue.PivotTransformGizmo.md#nettag)
- [NetUpdateFrequency](ue_ue.PivotTransformGizmo.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.PivotTransformGizmo.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.PivotTransformGizmo.md#onactorendoverlap)
- [OnActorHit](ue_ue.PivotTransformGizmo.md#onactorhit)
- [OnBeginCursorOver](ue_ue.PivotTransformGizmo.md#onbegincursorover)
- [OnClicked](ue_ue.PivotTransformGizmo.md#onclicked)
- [OnDestroyed](ue_ue.PivotTransformGizmo.md#ondestroyed)
- [OnEndCursorOver](ue_ue.PivotTransformGizmo.md#onendcursorover)
- [OnEndPlay](ue_ue.PivotTransformGizmo.md#onendplay)
- [OnInputTouchBegin](ue_ue.PivotTransformGizmo.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.PivotTransformGizmo.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.PivotTransformGizmo.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.PivotTransformGizmo.md#oninputtouchleave)
- [OnReleased](ue_ue.PivotTransformGizmo.md#onreleased)
- [OnTakeAnyDamage](ue_ue.PivotTransformGizmo.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.PivotTransformGizmo.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.PivotTransformGizmo.md#ontakeradialdamage)
- [Owner](ue_ue.PivotTransformGizmo.md#owner)
- [ParentComponent](ue_ue.PivotTransformGizmo.md#parentcomponent)
- [ParentComponentActor](ue_ue.PivotTransformGizmo.md#parentcomponentactor)
- [PivotOffset](ue_ue.PivotTransformGizmo.md#pivotoffset)
- [PlaneTranslationGizmoHandleGroup](ue_ue.PivotTransformGizmo.md#planetranslationgizmohandlegroup)
- [PrimaryActorTick](ue_ue.PivotTransformGizmo.md#primaryactortick)
- [RemoteRole](ue_ue.PivotTransformGizmo.md#remoterole)
- [ReplicatedMovement](ue_ue.PivotTransformGizmo.md#replicatedmovement)
- [Role](ue_ue.PivotTransformGizmo.md#role)
- [RootComponent](ue_ue.PivotTransformGizmo.md#rootcomponent)
- [RotationGizmoHandleGroup](ue_ue.PivotTransformGizmo.md#rotationgizmohandlegroup)
- [ScaleGizmoHandleGroup](ue_ue.PivotTransformGizmo.md#scalegizmohandlegroup)
- [SceneComponent](ue_ue.PivotTransformGizmo.md#scenecomponent)
- [SpawnCollisionHandlingMethod](ue_ue.PivotTransformGizmo.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.PivotTransformGizmo.md#spritescale)
- [StretchGizmoHandleGroup](ue_ue.PivotTransformGizmo.md#stretchgizmohandlegroup)
- [Tags](ue_ue.PivotTransformGizmo.md#tags)
- [TranslationGizmoHandleGroup](ue_ue.PivotTransformGizmo.md#translationgizmohandlegroup)
- [UniformScaleGizmoHandleGroup](ue_ue.PivotTransformGizmo.md#uniformscalegizmohandlegroup)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.PivotTransformGizmo.md#updateoverlapsmethodduringlevelstreaming)
- [WorldInteraction](ue_ue.PivotTransformGizmo.md#worldinteraction)
- [\_\_tid\_Actor\_\_](ue_ue.PivotTransformGizmo.md#__tid_actor__)
- [\_\_tid\_BaseTransformGizmo\_\_](ue_ue.PivotTransformGizmo.md#__tid_basetransformgizmo__)
- [\_\_tid\_Object\_\_](ue_ue.PivotTransformGizmo.md#__tid_object__)
- [\_\_tid\_PivotTransformGizmo\_\_](ue_ue.PivotTransformGizmo.md#__tid_pivottransformgizmo__)
- [bActorEnableCollision](ue_ue.PivotTransformGizmo.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.PivotTransformGizmo.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.PivotTransformGizmo.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.PivotTransformGizmo.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.PivotTransformGizmo.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.PivotTransformGizmo.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.PivotTransformGizmo.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.PivotTransformGizmo.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.PivotTransformGizmo.md#bblockinput)
- [bCanBeDamaged](ue_ue.PivotTransformGizmo.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.PivotTransformGizmo.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.PivotTransformGizmo.md#bcollidewhenplacing)
- [bEditable](ue_ue.PivotTransformGizmo.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.PivotTransformGizmo.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.PivotTransformGizmo.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.PivotTransformGizmo.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.PivotTransformGizmo.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.PivotTransformGizmo.md#bhidden)
- [bHiddenEd](ue_ue.PivotTransformGizmo.md#bhiddened)
- [bHiddenEdLayer](ue_ue.PivotTransformGizmo.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.PivotTransformGizmo.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.PivotTransformGizmo.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.PivotTransformGizmo.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.PivotTransformGizmo.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.PivotTransformGizmo.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.PivotTransformGizmo.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.PivotTransformGizmo.md#blocklocation)
- [bNetLoadOnClient](ue_ue.PivotTransformGizmo.md#bnetloadonclient)
- [bNetStartup](ue_ue.PivotTransformGizmo.md#bnetstartup)
- [bNetTemporary](ue_ue.PivotTransformGizmo.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.PivotTransformGizmo.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.PivotTransformGizmo.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.PivotTransformGizmo.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.PivotTransformGizmo.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.PivotTransformGizmo.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.PivotTransformGizmo.md#breplayrewindable)
- [bReplicateMovement](ue_ue.PivotTransformGizmo.md#breplicatemovement)
- [bReplicates](ue_ue.PivotTransformGizmo.md#breplicates)
- [bTearOff](ue_ue.PivotTransformGizmo.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.PivotTransformGizmo.md#actorhastag)
- [AddComponent](ue_ue.PivotTransformGizmo.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.PivotTransformGizmo.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PivotTransformGizmo.md#addtickprerequisitecomponent)
- [CreateDefaultSubobject](ue_ue.PivotTransformGizmo.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.PivotTransformGizmo.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.PivotTransformGizmo.md#disableinput)
- [EnableInput](ue_ue.PivotTransformGizmo.md#enableinput)
- [ExecuteUbergraph](ue_ue.PivotTransformGizmo.md#executeubergraph)
- [FlushNetDormancy](ue_ue.PivotTransformGizmo.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.PivotTransformGizmo.md#forcenetupdate)
- [GetActorBounds](ue_ue.PivotTransformGizmo.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.PivotTransformGizmo.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.PivotTransformGizmo.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.PivotTransformGizmo.md#getactorforwardvector)
- [GetActorLabel](ue_ue.PivotTransformGizmo.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.PivotTransformGizmo.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.PivotTransformGizmo.md#getactorrightvector)
- [GetActorScale3D](ue_ue.PivotTransformGizmo.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.PivotTransformGizmo.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.PivotTransformGizmo.md#getactortimedilation)
- [GetActorUpVector](ue_ue.PivotTransformGizmo.md#getactorupvector)
- [GetAllChildActors](ue_ue.PivotTransformGizmo.md#getallchildactors)
- [GetAttachParentActor](ue_ue.PivotTransformGizmo.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.PivotTransformGizmo.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.PivotTransformGizmo.md#getattachedactors)
- [GetClass](ue_ue.PivotTransformGizmo.md#getclass)
- [GetComponentByClass](ue_ue.PivotTransformGizmo.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.PivotTransformGizmo.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.PivotTransformGizmo.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.PivotTransformGizmo.md#getdistanceto)
- [GetDotProductTo](ue_ue.PivotTransformGizmo.md#getdotproductto)
- [GetFolderPath](ue_ue.PivotTransformGizmo.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.PivotTransformGizmo.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.PivotTransformGizmo.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.PivotTransformGizmo.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.PivotTransformGizmo.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.PivotTransformGizmo.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.PivotTransformGizmo.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.PivotTransformGizmo.md#getinstigator)
- [GetInstigatorController](ue_ue.PivotTransformGizmo.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.PivotTransformGizmo.md#getlifespan)
- [GetLocalRole](ue_ue.PivotTransformGizmo.md#getlocalrole)
- [GetName](ue_ue.PivotTransformGizmo.md#getname)
- [GetOuter](ue_ue.PivotTransformGizmo.md#getouter)
- [GetOverlappingActors](ue_ue.PivotTransformGizmo.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.PivotTransformGizmo.md#getoverlappingcomponents)
- [GetOwner](ue_ue.PivotTransformGizmo.md#getowner)
- [GetParentActor](ue_ue.PivotTransformGizmo.md#getparentactor)
- [GetParentComponent](ue_ue.PivotTransformGizmo.md#getparentcomponent)
- [GetRemoteRole](ue_ue.PivotTransformGizmo.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.PivotTransformGizmo.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.PivotTransformGizmo.md#gettickablewhenpaused)
- [GetTransform](ue_ue.PivotTransformGizmo.md#gettransform)
- [GetVelocity](ue_ue.PivotTransformGizmo.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.PivotTransformGizmo.md#getverticaldistanceto)
- [GetWorld](ue_ue.PivotTransformGizmo.md#getworld)
- [HasAuthority](ue_ue.PivotTransformGizmo.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.PivotTransformGizmo.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.PivotTransformGizmo.md#isactortickenabled)
- [IsChildActor](ue_ue.PivotTransformGizmo.md#ischildactor)
- [IsEditable](ue_ue.PivotTransformGizmo.md#iseditable)
- [IsHiddenEd](ue_ue.PivotTransformGizmo.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.PivotTransformGizmo.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.PivotTransformGizmo.md#isoverlappingactor)
- [IsSelectable](ue_ue.PivotTransformGizmo.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.PivotTransformGizmo.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.PivotTransformGizmo.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.PivotTransformGizmo.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.PivotTransformGizmo.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.PivotTransformGizmo.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.PivotTransformGizmo.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.PivotTransformGizmo.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.PivotTransformGizmo.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.PivotTransformGizmo.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.PivotTransformGizmo.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.PivotTransformGizmo.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.PivotTransformGizmo.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.PivotTransformGizmo.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.PivotTransformGizmo.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.PivotTransformGizmo.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.PivotTransformGizmo.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.PivotTransformGizmo.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.PivotTransformGizmo.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.PivotTransformGizmo.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.PivotTransformGizmo.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.PivotTransformGizmo.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.PivotTransformGizmo.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.PivotTransformGizmo.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.PivotTransformGizmo.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.PivotTransformGizmo.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.PivotTransformGizmo.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.PivotTransformGizmo.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.PivotTransformGizmo.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.PivotTransformGizmo.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.PivotTransformGizmo.md#makemidformaterial)
- [MakeNoise](ue_ue.PivotTransformGizmo.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.PivotTransformGizmo.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.PivotTransformGizmo.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.PivotTransformGizmo.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.PivotTransformGizmo.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.PivotTransformGizmo.md#onrep_replicatedmovement)
- [PrestreamTextures](ue_ue.PivotTransformGizmo.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.PivotTransformGizmo.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.PivotTransformGizmo.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.PivotTransformGizmo.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.PivotTransformGizmo.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.PivotTransformGizmo.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.PivotTransformGizmo.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.PivotTransformGizmo.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.PivotTransformGizmo.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.PivotTransformGizmo.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.PivotTransformGizmo.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.PivotTransformGizmo.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.PivotTransformGizmo.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.PivotTransformGizmo.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.PivotTransformGizmo.md#receiveendplay)
- [ReceiveHit](ue_ue.PivotTransformGizmo.md#receivehit)
- [ReceivePointDamage](ue_ue.PivotTransformGizmo.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.PivotTransformGizmo.md#receiveradialdamage)
- [ReceiveTick](ue_ue.PivotTransformGizmo.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.PivotTransformGizmo.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PivotTransformGizmo.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.PivotTransformGizmo.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.PivotTransformGizmo.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.PivotTransformGizmo.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.PivotTransformGizmo.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.PivotTransformGizmo.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.PivotTransformGizmo.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.PivotTransformGizmo.md#setactortickinterval)
- [SetFolderPath](ue_ue.PivotTransformGizmo.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.PivotTransformGizmo.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.PivotTransformGizmo.md#setlifespan)
- [SetNetDormancy](ue_ue.PivotTransformGizmo.md#setnetdormancy)
- [SetOwner](ue_ue.PivotTransformGizmo.md#setowner)
- [SetReplicateMovement](ue_ue.PivotTransformGizmo.md#setreplicatemovement)
- [SetReplicates](ue_ue.PivotTransformGizmo.md#setreplicates)
- [SetTickGroup](ue_ue.PivotTransformGizmo.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PivotTransformGizmo.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.PivotTransformGizmo.md#snaprootcomponentto)
- [TearOff](ue_ue.PivotTransformGizmo.md#tearoff)
- [UserConstructionScript](ue_ue.PivotTransformGizmo.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.PivotTransformGizmo.md#wasrecentlyrendered)
- [Find](ue_ue.PivotTransformGizmo.md#find)
- [Load](ue_ue.PivotTransformGizmo.md#load)
- [StaticClass](ue_ue.PivotTransformGizmo.md#staticclass)

## Constructors

### constructor

• **new PivotTransformGizmo**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[constructor](ue_ue.BaseTransformGizmo.md#constructor)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ActorLabel](ue_ue.BaseTransformGizmo.md#actorlabel)

___

### AllHandleGroups

• **AllHandleGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GizmoHandleGroup`](ue_ue.GizmoHandleGroup.md)\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[AllHandleGroups](ue_ue.BaseTransformGizmo.md#allhandlegroups)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[AttachmentReplication](ue_ue.BaseTransformGizmo.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[AutoReceiveInput](ue_ue.BaseTransformGizmo.md#autoreceiveinput)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[BlueprintCreatedComponents](ue_ue.BaseTransformGizmo.md#blueprintcreatedcomponents)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[Children](ue_ue.BaseTransformGizmo.md#children)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ControllingMatineeActors](ue_ue.BaseTransformGizmo.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[CustomTimeDilation](ue_ue.BaseTransformGizmo.md#customtimedilation)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.BaseTransformGizmo.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[FolderPath](ue_ue.BaseTransformGizmo.md#folderpath)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GroupActor](ue_ue.BaseTransformGizmo.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[HiddenEditorViews](ue_ue.BaseTransformGizmo.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[InitialLifeSpan](ue_ue.BaseTransformGizmo.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[InputComponent](ue_ue.BaseTransformGizmo.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[InputPriority](ue_ue.BaseTransformGizmo.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[InstanceComponents](ue_ue.BaseTransformGizmo.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[Instigator](ue_ue.BaseTransformGizmo.md#instigator)

___

### LastDraggingHandle

• **LastDraggingHandle**: [`ActorComponent`](ue_ue.ActorComponent.md)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[Layers](ue_ue.BaseTransformGizmo.md#layers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[MinNetUpdateFrequency](ue_ue.BaseTransformGizmo.md#minnetupdatefrequency)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[NetCullDistanceSquared](ue_ue.BaseTransformGizmo.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[NetDormancy](ue_ue.BaseTransformGizmo.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[NetDriverName](ue_ue.BaseTransformGizmo.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[NetPriority](ue_ue.BaseTransformGizmo.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[NetTag](ue_ue.BaseTransformGizmo.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[NetUpdateFrequency](ue_ue.BaseTransformGizmo.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnActorBeginOverlap](ue_ue.BaseTransformGizmo.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnActorEndOverlap](ue_ue.BaseTransformGizmo.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnActorHit](ue_ue.BaseTransformGizmo.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnBeginCursorOver](ue_ue.BaseTransformGizmo.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnClicked](ue_ue.BaseTransformGizmo.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnDestroyed](ue_ue.BaseTransformGizmo.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnEndCursorOver](ue_ue.BaseTransformGizmo.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnEndPlay](ue_ue.BaseTransformGizmo.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnInputTouchBegin](ue_ue.BaseTransformGizmo.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnInputTouchEnd](ue_ue.BaseTransformGizmo.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnInputTouchEnter](ue_ue.BaseTransformGizmo.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnInputTouchLeave](ue_ue.BaseTransformGizmo.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnReleased](ue_ue.BaseTransformGizmo.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnTakeAnyDamage](ue_ue.BaseTransformGizmo.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnTakePointDamage](ue_ue.BaseTransformGizmo.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnTakeRadialDamage](ue_ue.BaseTransformGizmo.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[Owner](ue_ue.BaseTransformGizmo.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ParentComponent](ue_ue.BaseTransformGizmo.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ParentComponentActor](ue_ue.BaseTransformGizmo.md#parentcomponentactor)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[PivotOffset](ue_ue.BaseTransformGizmo.md#pivotoffset)

___

### PlaneTranslationGizmoHandleGroup

• **PlaneTranslationGizmoHandleGroup**: [`PivotPlaneTranslationGizmoHandleGroup`](ue_ue.PivotPlaneTranslationGizmoHandleGroup.md)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[PrimaryActorTick](ue_ue.BaseTransformGizmo.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[RemoteRole](ue_ue.BaseTransformGizmo.md#remoterole)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReplicatedMovement](ue_ue.BaseTransformGizmo.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[Role](ue_ue.BaseTransformGizmo.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[RootComponent](ue_ue.BaseTransformGizmo.md#rootcomponent)

___

### RotationGizmoHandleGroup

• **RotationGizmoHandleGroup**: [`PivotRotationGizmoHandleGroup`](ue_ue.PivotRotationGizmoHandleGroup.md)

___

### ScaleGizmoHandleGroup

• **ScaleGizmoHandleGroup**: [`PivotScaleGizmoHandleGroup`](ue_ue.PivotScaleGizmoHandleGroup.md)

___

### SceneComponent

• **SceneComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SceneComponent](ue_ue.BaseTransformGizmo.md#scenecomponent)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SpawnCollisionHandlingMethod](ue_ue.BaseTransformGizmo.md#spawncollisionhandlingmethod)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SpriteScale](ue_ue.BaseTransformGizmo.md#spritescale)

___

### StretchGizmoHandleGroup

• **StretchGizmoHandleGroup**: [`StretchGizmoHandleGroup`](ue_ue.StretchGizmoHandleGroup.md)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[Tags](ue_ue.BaseTransformGizmo.md#tags)

___

### TranslationGizmoHandleGroup

• **TranslationGizmoHandleGroup**: [`PivotTranslationGizmoHandleGroup`](ue_ue.PivotTranslationGizmoHandleGroup.md)

___

### UniformScaleGizmoHandleGroup

• **UniformScaleGizmoHandleGroup**: [`UniformScaleGizmoHandleGroup`](ue_ue.UniformScaleGizmoHandleGroup.md)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.BaseTransformGizmo.md#updateoverlapsmethodduringlevelstreaming)

___

### WorldInteraction

• **WorldInteraction**: [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[WorldInteraction](ue_ue.BaseTransformGizmo.md#worldinteraction)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[__tid_Actor__](ue_ue.BaseTransformGizmo.md#__tid_actor__)

___

### \_\_tid\_BaseTransformGizmo\_\_

• **\_\_tid\_BaseTransformGizmo\_\_**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[__tid_BaseTransformGizmo__](ue_ue.BaseTransformGizmo.md#__tid_basetransformgizmo__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[__tid_Object__](ue_ue.BaseTransformGizmo.md#__tid_object__)

___

### \_\_tid\_PivotTransformGizmo\_\_

• **\_\_tid\_PivotTransformGizmo\_\_**: `boolean`

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bActorEnableCollision](ue_ue.BaseTransformGizmo.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bActorIsBeingDestroyed](ue_ue.BaseTransformGizmo.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bActorLabelEditable](ue_ue.BaseTransformGizmo.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bActorSeamlessTraveled](ue_ue.BaseTransformGizmo.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.BaseTransformGizmo.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bAllowTickBeforeBeginPlay](ue_ue.BaseTransformGizmo.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bAlwaysRelevant](ue_ue.BaseTransformGizmo.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bAutoDestroyWhenFinished](ue_ue.BaseTransformGizmo.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bBlockInput](ue_ue.BaseTransformGizmo.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bCanBeDamaged](ue_ue.BaseTransformGizmo.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bCanBeInCluster](ue_ue.BaseTransformGizmo.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bCollideWhenPlacing](ue_ue.BaseTransformGizmo.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bEditable](ue_ue.BaseTransformGizmo.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bEnableAutoLODGeneration](ue_ue.BaseTransformGizmo.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bExchangedRoles](ue_ue.BaseTransformGizmo.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bFindCameraComponentWhenViewTarget](ue_ue.BaseTransformGizmo.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.BaseTransformGizmo.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bHidden](ue_ue.BaseTransformGizmo.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bHiddenEd](ue_ue.BaseTransformGizmo.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bHiddenEdLayer](ue_ue.BaseTransformGizmo.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bHiddenEdLevel](ue_ue.BaseTransformGizmo.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bHiddenEdTemporary](ue_ue.BaseTransformGizmo.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bIgnoresOriginShifting](ue_ue.BaseTransformGizmo.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bIsEditorOnlyActor](ue_ue.BaseTransformGizmo.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bIsEditorPreviewActor](ue_ue.BaseTransformGizmo.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bListedInSceneOutliner](ue_ue.BaseTransformGizmo.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bLockLocation](ue_ue.BaseTransformGizmo.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bNetLoadOnClient](ue_ue.BaseTransformGizmo.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bNetStartup](ue_ue.BaseTransformGizmo.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bNetTemporary](ue_ue.BaseTransformGizmo.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bNetUseOwnerRelevancy](ue_ue.BaseTransformGizmo.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bOnlyRelevantToOwner](ue_ue.BaseTransformGizmo.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bOptimizeBPComponentData](ue_ue.BaseTransformGizmo.md#boptimizebpcomponentdata)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bRelevantForLevelBounds](ue_ue.BaseTransformGizmo.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bRelevantForNetworkReplays](ue_ue.BaseTransformGizmo.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bReplayRewindable](ue_ue.BaseTransformGizmo.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bReplicateMovement](ue_ue.BaseTransformGizmo.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bReplicates](ue_ue.BaseTransformGizmo.md#breplicates)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bTearOff](ue_ue.BaseTransformGizmo.md#btearoff)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ActorHasTag](ue_ue.BaseTransformGizmo.md#actorhastag)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[AddComponent](ue_ue.BaseTransformGizmo.md#addcomponent)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[AddTickPrerequisiteActor](ue_ue.BaseTransformGizmo.md#addtickprerequisiteactor)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[AddTickPrerequisiteComponent](ue_ue.BaseTransformGizmo.md#addtickprerequisitecomponent)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[CreateDefaultSubobject](ue_ue.BaseTransformGizmo.md#createdefaultsubobject)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[DetachRootComponentFromParent](ue_ue.BaseTransformGizmo.md#detachrootcomponentfromparent)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[DisableInput](ue_ue.BaseTransformGizmo.md#disableinput)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[EnableInput](ue_ue.BaseTransformGizmo.md#enableinput)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ExecuteUbergraph](ue_ue.BaseTransformGizmo.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[FlushNetDormancy](ue_ue.BaseTransformGizmo.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ForceNetUpdate](ue_ue.BaseTransformGizmo.md#forcenetupdate)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorBounds](ue_ue.BaseTransformGizmo.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorEnableCollision](ue_ue.BaseTransformGizmo.md#getactorenablecollision)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorEyesViewPoint](ue_ue.BaseTransformGizmo.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorForwardVector](ue_ue.BaseTransformGizmo.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorLabel](ue_ue.BaseTransformGizmo.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorRelativeScale3D](ue_ue.BaseTransformGizmo.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorRightVector](ue_ue.BaseTransformGizmo.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorScale3D](ue_ue.BaseTransformGizmo.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorTickInterval](ue_ue.BaseTransformGizmo.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorTimeDilation](ue_ue.BaseTransformGizmo.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorUpVector](ue_ue.BaseTransformGizmo.md#getactorupvector)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetAllChildActors](ue_ue.BaseTransformGizmo.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetAttachParentActor](ue_ue.BaseTransformGizmo.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetAttachParentSocketName](ue_ue.BaseTransformGizmo.md#getattachparentsocketname)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetAttachedActors](ue_ue.BaseTransformGizmo.md#getattachedactors)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetClass](ue_ue.BaseTransformGizmo.md#getclass)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetComponentByClass](ue_ue.BaseTransformGizmo.md#getcomponentbyclass)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetComponentsByInterface](ue_ue.BaseTransformGizmo.md#getcomponentsbyinterface)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetComponentsByTag](ue_ue.BaseTransformGizmo.md#getcomponentsbytag)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetDistanceTo](ue_ue.BaseTransformGizmo.md#getdistanceto)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetDotProductTo](ue_ue.BaseTransformGizmo.md#getdotproductto)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetFolderPath](ue_ue.BaseTransformGizmo.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetGameTimeSinceCreation](ue_ue.BaseTransformGizmo.md#getgametimesincecreation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetHorizontalDistanceTo](ue_ue.BaseTransformGizmo.md#gethorizontaldistanceto)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetHorizontalDotProductTo](ue_ue.BaseTransformGizmo.md#gethorizontaldotproductto)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetInputAxisKeyValue](ue_ue.BaseTransformGizmo.md#getinputaxiskeyvalue)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetInputAxisValue](ue_ue.BaseTransformGizmo.md#getinputaxisvalue)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetInputVectorAxisValue](ue_ue.BaseTransformGizmo.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetInstigator](ue_ue.BaseTransformGizmo.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetInstigatorController](ue_ue.BaseTransformGizmo.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetLifeSpan](ue_ue.BaseTransformGizmo.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetLocalRole](ue_ue.BaseTransformGizmo.md#getlocalrole)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetName](ue_ue.BaseTransformGizmo.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetOuter](ue_ue.BaseTransformGizmo.md#getouter)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetOverlappingActors](ue_ue.BaseTransformGizmo.md#getoverlappingactors)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetOverlappingComponents](ue_ue.BaseTransformGizmo.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetOwner](ue_ue.BaseTransformGizmo.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetParentActor](ue_ue.BaseTransformGizmo.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetParentComponent](ue_ue.BaseTransformGizmo.md#getparentcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetRemoteRole](ue_ue.BaseTransformGizmo.md#getremoterole)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetSquaredDistanceTo](ue_ue.BaseTransformGizmo.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetTickableWhenPaused](ue_ue.BaseTransformGizmo.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetTransform](ue_ue.BaseTransformGizmo.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetVelocity](ue_ue.BaseTransformGizmo.md#getvelocity)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetVerticalDistanceTo](ue_ue.BaseTransformGizmo.md#getverticaldistanceto)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetWorld](ue_ue.BaseTransformGizmo.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[HasAuthority](ue_ue.BaseTransformGizmo.md#hasauthority)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsActorBeingDestroyed](ue_ue.BaseTransformGizmo.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsActorTickEnabled](ue_ue.BaseTransformGizmo.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsChildActor](ue_ue.BaseTransformGizmo.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsEditable](ue_ue.BaseTransformGizmo.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsHiddenEd](ue_ue.BaseTransformGizmo.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsHiddenEdAtStartup](ue_ue.BaseTransformGizmo.md#ishiddenedatstartup)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsOverlappingActor](ue_ue.BaseTransformGizmo.md#isoverlappingactor)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsSelectable](ue_ue.BaseTransformGizmo.md#isselectable)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsTemporarilyHiddenInEditor](ue_ue.BaseTransformGizmo.md#istemporarilyhiddenineditor)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AddActorLocalOffset](ue_ue.BaseTransformGizmo.md#k2_addactorlocaloffset)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AddActorLocalRotation](ue_ue.BaseTransformGizmo.md#k2_addactorlocalrotation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AddActorLocalTransform](ue_ue.BaseTransformGizmo.md#k2_addactorlocaltransform)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AddActorWorldOffset](ue_ue.BaseTransformGizmo.md#k2_addactorworldoffset)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AddActorWorldRotation](ue_ue.BaseTransformGizmo.md#k2_addactorworldrotation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AddActorWorldTransform](ue_ue.BaseTransformGizmo.md#k2_addactorworldtransform)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AttachRootComponentTo](ue_ue.BaseTransformGizmo.md#k2_attachrootcomponentto)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AttachRootComponentToActor](ue_ue.BaseTransformGizmo.md#k2_attachrootcomponenttoactor)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AttachToActor](ue_ue.BaseTransformGizmo.md#k2_attachtoactor)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AttachToComponent](ue_ue.BaseTransformGizmo.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_DestroyActor](ue_ue.BaseTransformGizmo.md#k2_destroyactor)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_DestroyComponent](ue_ue.BaseTransformGizmo.md#k2_destroycomponent)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_DetachFromActor](ue_ue.BaseTransformGizmo.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_GetActorLocation](ue_ue.BaseTransformGizmo.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_GetActorRotation](ue_ue.BaseTransformGizmo.md#k2_getactorrotation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_GetComponentsByClass](ue_ue.BaseTransformGizmo.md#k2_getcomponentsbyclass)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_GetRootComponent](ue_ue.BaseTransformGizmo.md#k2_getrootcomponent)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_OnBecomeViewTarget](ue_ue.BaseTransformGizmo.md#k2_onbecomeviewtarget)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_OnEndViewTarget](ue_ue.BaseTransformGizmo.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_OnReset](ue_ue.BaseTransformGizmo.md#k2_onreset)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_SetActorLocation](ue_ue.BaseTransformGizmo.md#k2_setactorlocation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_SetActorLocationAndRotation](ue_ue.BaseTransformGizmo.md#k2_setactorlocationandrotation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_SetActorRelativeLocation](ue_ue.BaseTransformGizmo.md#k2_setactorrelativelocation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_SetActorRelativeRotation](ue_ue.BaseTransformGizmo.md#k2_setactorrelativerotation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_SetActorRelativeTransform](ue_ue.BaseTransformGizmo.md#k2_setactorrelativetransform)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_SetActorRotation](ue_ue.BaseTransformGizmo.md#k2_setactorrotation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_SetActorTransform](ue_ue.BaseTransformGizmo.md#k2_setactortransform)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_TeleportTo](ue_ue.BaseTransformGizmo.md#k2_teleportto)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[MakeMIDForMaterial](ue_ue.BaseTransformGizmo.md#makemidformaterial)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[MakeNoise](ue_ue.BaseTransformGizmo.md#makenoise)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnRep_AttachmentReplication](ue_ue.BaseTransformGizmo.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnRep_Instigator](ue_ue.BaseTransformGizmo.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnRep_Owner](ue_ue.BaseTransformGizmo.md#onrep_owner)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnRep_ReplicateMovement](ue_ue.BaseTransformGizmo.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnRep_ReplicatedMovement](ue_ue.BaseTransformGizmo.md#onrep_replicatedmovement)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[PrestreamTextures](ue_ue.BaseTransformGizmo.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorBeginCursorOver](ue_ue.BaseTransformGizmo.md#receiveactorbegincursorover)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorBeginOverlap](ue_ue.BaseTransformGizmo.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorEndCursorOver](ue_ue.BaseTransformGizmo.md#receiveactorendcursorover)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorEndOverlap](ue_ue.BaseTransformGizmo.md#receiveactorendoverlap)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorOnClicked](ue_ue.BaseTransformGizmo.md#receiveactoronclicked)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorOnInputTouchBegin](ue_ue.BaseTransformGizmo.md#receiveactoroninputtouchbegin)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorOnInputTouchEnd](ue_ue.BaseTransformGizmo.md#receiveactoroninputtouchend)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorOnInputTouchEnter](ue_ue.BaseTransformGizmo.md#receiveactoroninputtouchenter)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorOnInputTouchLeave](ue_ue.BaseTransformGizmo.md#receiveactoroninputtouchleave)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorOnReleased](ue_ue.BaseTransformGizmo.md#receiveactoronreleased)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveAnyDamage](ue_ue.BaseTransformGizmo.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveBeginPlay](ue_ue.BaseTransformGizmo.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveDestroyed](ue_ue.BaseTransformGizmo.md#receivedestroyed)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveEndPlay](ue_ue.BaseTransformGizmo.md#receiveendplay)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveHit](ue_ue.BaseTransformGizmo.md#receivehit)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceivePointDamage](ue_ue.BaseTransformGizmo.md#receivepointdamage)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveRadialDamage](ue_ue.BaseTransformGizmo.md#receiveradialdamage)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveTick](ue_ue.BaseTransformGizmo.md#receivetick)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[RemoveTickPrerequisiteActor](ue_ue.BaseTransformGizmo.md#removetickprerequisiteactor)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[RemoveTickPrerequisiteComponent](ue_ue.BaseTransformGizmo.md#removetickprerequisitecomponent)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetActorEnableCollision](ue_ue.BaseTransformGizmo.md#setactorenablecollision)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetActorHiddenInGame](ue_ue.BaseTransformGizmo.md#setactorhiddeningame)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetActorLabel](ue_ue.BaseTransformGizmo.md#setactorlabel)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetActorRelativeScale3D](ue_ue.BaseTransformGizmo.md#setactorrelativescale3d)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetActorScale3D](ue_ue.BaseTransformGizmo.md#setactorscale3d)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetActorTickEnabled](ue_ue.BaseTransformGizmo.md#setactortickenabled)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetActorTickInterval](ue_ue.BaseTransformGizmo.md#setactortickinterval)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetFolderPath](ue_ue.BaseTransformGizmo.md#setfolderpath)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetIsTemporarilyHiddenInEditor](ue_ue.BaseTransformGizmo.md#setistemporarilyhiddenineditor)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetLifeSpan](ue_ue.BaseTransformGizmo.md#setlifespan)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetNetDormancy](ue_ue.BaseTransformGizmo.md#setnetdormancy)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetOwner](ue_ue.BaseTransformGizmo.md#setowner)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetReplicateMovement](ue_ue.BaseTransformGizmo.md#setreplicatemovement)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetReplicates](ue_ue.BaseTransformGizmo.md#setreplicates)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetTickGroup](ue_ue.BaseTransformGizmo.md#settickgroup)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetTickableWhenPaused](ue_ue.BaseTransformGizmo.md#settickablewhenpaused)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SnapRootComponentTo](ue_ue.BaseTransformGizmo.md#snaprootcomponentto)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[TearOff](ue_ue.BaseTransformGizmo.md#tearoff)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[UserConstructionScript](ue_ue.BaseTransformGizmo.md#userconstructionscript)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[WasRecentlyRendered](ue_ue.BaseTransformGizmo.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PivotTransformGizmo`](ue_ue.PivotTransformGizmo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PivotTransformGizmo`](ue_ue.PivotTransformGizmo.md)

#### Overrides

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[Find](ue_ue.BaseTransformGizmo.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PivotTransformGizmo`](ue_ue.PivotTransformGizmo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PivotTransformGizmo`](ue_ue.PivotTransformGizmo.md)

#### Overrides

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[Load](ue_ue.BaseTransformGizmo.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[StaticClass](ue_ue.BaseTransformGizmo.md#staticclass)
