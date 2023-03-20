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

#### Defined in

[ue/ue.d.ts:57829](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57829)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ActorLabel](ue_ue.BaseTransformGizmo.md#actorlabel)

#### Defined in

[ue/ue.d.ts:13176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13176)

___

### AllHandleGroups

• **AllHandleGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GizmoHandleGroup`](ue_ue.GizmoHandleGroup.md)\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[AllHandleGroups](ue_ue.BaseTransformGizmo.md#allhandlegroups)

#### Defined in

[ue/ue.d.ts:14427](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14427)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[AttachmentReplication](ue_ue.BaseTransformGizmo.md#attachmentreplication)

#### Defined in

[ue/ue.d.ts:13151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13151)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[AutoReceiveInput](ue_ue.BaseTransformGizmo.md#autoreceiveinput)

#### Defined in

[ue/ue.d.ts:13157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13157)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[BlueprintCreatedComponents](ue_ue.BaseTransformGizmo.md#blueprintcreatedcomponents)

#### Defined in

[ue/ue.d.ts:13206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13206)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[Children](ue_ue.BaseTransformGizmo.md#children)

#### Defined in

[ue/ue.d.ts:13166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13166)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ControllingMatineeActors](ue_ue.BaseTransformGizmo.md#controllingmatineeactors)

#### Defined in

[ue/ue.d.ts:13169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13169)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[CustomTimeDilation](ue_ue.BaseTransformGizmo.md#customtimedilation)

#### Defined in

[ue/ue.d.ts:13150](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13150)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.BaseTransformGizmo.md#defaultupdateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13146](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13146)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[FolderPath](ue_ue.BaseTransformGizmo.md#folderpath)

#### Defined in

[ue/ue.d.ts:13177](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13177)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GroupActor](ue_ue.BaseTransformGizmo.md#groupactor)

#### Defined in

[ue/ue.d.ts:13173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13173)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[HiddenEditorViews](ue_ue.BaseTransformGizmo.md#hiddeneditorviews)

#### Defined in

[ue/ue.d.ts:13175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13175)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[InitialLifeSpan](ue_ue.BaseTransformGizmo.md#initiallifespan)

#### Defined in

[ue/ue.d.ts:13149](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13149)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[InputComponent](ue_ue.BaseTransformGizmo.md#inputcomponent)

#### Defined in

[ue/ue.d.ts:13159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13159)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[InputPriority](ue_ue.BaseTransformGizmo.md#inputpriority)

#### Defined in

[ue/ue.d.ts:13158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13158)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[InstanceComponents](ue_ue.BaseTransformGizmo.md#instancecomponents)

#### Defined in

[ue/ue.d.ts:13205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13205)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[Instigator](ue_ue.BaseTransformGizmo.md#instigator)

#### Defined in

[ue/ue.d.ts:13165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13165)

___

### LastDraggingHandle

• **LastDraggingHandle**: [`ActorComponent`](ue_ue.ActorComponent.md)

#### Defined in

[ue/ue.d.ts:57836](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57836)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[Layers](ue_ue.BaseTransformGizmo.md#layers)

#### Defined in

[ue/ue.d.ts:13170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13170)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[MinNetUpdateFrequency](ue_ue.BaseTransformGizmo.md#minnetupdatefrequency)

#### Defined in

[ue/ue.d.ts:13163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13163)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[NetCullDistanceSquared](ue_ue.BaseTransformGizmo.md#netculldistancesquared)

#### Defined in

[ue/ue.d.ts:13160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13160)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[NetDormancy](ue_ue.BaseTransformGizmo.md#netdormancy)

#### Defined in

[ue/ue.d.ts:13155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13155)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[NetDriverName](ue_ue.BaseTransformGizmo.md#netdrivername)

#### Defined in

[ue/ue.d.ts:13153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13153)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[NetPriority](ue_ue.BaseTransformGizmo.md#netpriority)

#### Defined in

[ue/ue.d.ts:13164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13164)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[NetTag](ue_ue.BaseTransformGizmo.md#nettag)

#### Defined in

[ue/ue.d.ts:13161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13161)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[NetUpdateFrequency](ue_ue.BaseTransformGizmo.md#netupdatefrequency)

#### Defined in

[ue/ue.d.ts:13162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13162)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnActorBeginOverlap](ue_ue.BaseTransformGizmo.md#onactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13192)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnActorEndOverlap](ue_ue.BaseTransformGizmo.md#onactorendoverlap)

#### Defined in

[ue/ue.d.ts:13193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13193)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnActorHit](ue_ue.BaseTransformGizmo.md#onactorhit)

#### Defined in

[ue/ue.d.ts:13202](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13202)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnBeginCursorOver](ue_ue.BaseTransformGizmo.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:13194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13194)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnClicked](ue_ue.BaseTransformGizmo.md#onclicked)

#### Defined in

[ue/ue.d.ts:13196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13196)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnDestroyed](ue_ue.BaseTransformGizmo.md#ondestroyed)

#### Defined in

[ue/ue.d.ts:13203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13203)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnEndCursorOver](ue_ue.BaseTransformGizmo.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:13195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13195)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnEndPlay](ue_ue.BaseTransformGizmo.md#onendplay)

#### Defined in

[ue/ue.d.ts:13204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13204)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnInputTouchBegin](ue_ue.BaseTransformGizmo.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13198)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnInputTouchEnd](ue_ue.BaseTransformGizmo.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:13199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13199)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnInputTouchEnter](ue_ue.BaseTransformGizmo.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:13200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13200)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnInputTouchLeave](ue_ue.BaseTransformGizmo.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:13201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13201)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnReleased](ue_ue.BaseTransformGizmo.md#onreleased)

#### Defined in

[ue/ue.d.ts:13197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13197)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnTakeAnyDamage](ue_ue.BaseTransformGizmo.md#ontakeanydamage)

#### Defined in

[ue/ue.d.ts:13189](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13189)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnTakePointDamage](ue_ue.BaseTransformGizmo.md#ontakepointdamage)

#### Defined in

[ue/ue.d.ts:13190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13190)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnTakeRadialDamage](ue_ue.BaseTransformGizmo.md#ontakeradialdamage)

#### Defined in

[ue/ue.d.ts:13191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13191)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[Owner](ue_ue.BaseTransformGizmo.md#owner)

#### Defined in

[ue/ue.d.ts:13152](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13152)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ParentComponent](ue_ue.BaseTransformGizmo.md#parentcomponent)

#### Defined in

[ue/ue.d.ts:13172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13172)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ParentComponentActor](ue_ue.BaseTransformGizmo.md#parentcomponentactor)

#### Defined in

[ue/ue.d.ts:13171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13171)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[PivotOffset](ue_ue.BaseTransformGizmo.md#pivotoffset)

#### Defined in

[ue/ue.d.ts:13168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13168)

___

### PlaneTranslationGizmoHandleGroup

• **PlaneTranslationGizmoHandleGroup**: [`PivotPlaneTranslationGizmoHandleGroup`](ue_ue.PivotPlaneTranslationGizmoHandleGroup.md)

#### Defined in

[ue/ue.d.ts:57833](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57833)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[PrimaryActorTick](ue_ue.BaseTransformGizmo.md#primaryactortick)

#### Defined in

[ue/ue.d.ts:13115](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13115)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[RemoteRole](ue_ue.BaseTransformGizmo.md#remoterole)

#### Defined in

[ue/ue.d.ts:13147](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13147)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReplicatedMovement](ue_ue.BaseTransformGizmo.md#replicatedmovement)

#### Defined in

[ue/ue.d.ts:13148](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13148)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[Role](ue_ue.BaseTransformGizmo.md#role)

#### Defined in

[ue/ue.d.ts:13154](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13154)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[RootComponent](ue_ue.BaseTransformGizmo.md#rootcomponent)

#### Defined in

[ue/ue.d.ts:13167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13167)

___

### RotationGizmoHandleGroup

• **RotationGizmoHandleGroup**: [`PivotRotationGizmoHandleGroup`](ue_ue.PivotRotationGizmoHandleGroup.md)

#### Defined in

[ue/ue.d.ts:57834](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57834)

___

### ScaleGizmoHandleGroup

• **ScaleGizmoHandleGroup**: [`PivotScaleGizmoHandleGroup`](ue_ue.PivotScaleGizmoHandleGroup.md)

#### Defined in

[ue/ue.d.ts:57832](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57832)

___

### SceneComponent

• **SceneComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SceneComponent](ue_ue.BaseTransformGizmo.md#scenecomponent)

#### Defined in

[ue/ue.d.ts:14426](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14426)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SpawnCollisionHandlingMethod](ue_ue.BaseTransformGizmo.md#spawncollisionhandlingmethod)

#### Defined in

[ue/ue.d.ts:13156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13156)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SpriteScale](ue_ue.BaseTransformGizmo.md#spritescale)

#### Defined in

[ue/ue.d.ts:13174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13174)

___

### StretchGizmoHandleGroup

• **StretchGizmoHandleGroup**: [`StretchGizmoHandleGroup`](ue_ue.StretchGizmoHandleGroup.md)

#### Defined in

[ue/ue.d.ts:57835](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57835)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[Tags](ue_ue.BaseTransformGizmo.md#tags)

#### Defined in

[ue/ue.d.ts:13188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13188)

___

### TranslationGizmoHandleGroup

• **TranslationGizmoHandleGroup**: [`PivotTranslationGizmoHandleGroup`](ue_ue.PivotTranslationGizmoHandleGroup.md)

#### Defined in

[ue/ue.d.ts:57831](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57831)

___

### UniformScaleGizmoHandleGroup

• **UniformScaleGizmoHandleGroup**: [`UniformScaleGizmoHandleGroup`](ue_ue.UniformScaleGizmoHandleGroup.md)

#### Defined in

[ue/ue.d.ts:57830](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57830)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.BaseTransformGizmo.md#updateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13145](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13145)

___

### WorldInteraction

• **WorldInteraction**: [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[WorldInteraction](ue_ue.BaseTransformGizmo.md#worldinteraction)

#### Defined in

[ue/ue.d.ts:14428](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14428)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[__tid_Actor__](ue_ue.BaseTransformGizmo.md#__tid_actor__)

#### Defined in

[ue/ue.d.ts:13348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13348)

___

### \_\_tid\_BaseTransformGizmo\_\_

• **\_\_tid\_BaseTransformGizmo\_\_**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[__tid_BaseTransformGizmo__](ue_ue.BaseTransformGizmo.md#__tid_basetransformgizmo__)

#### Defined in

[ue/ue.d.ts:14433](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14433)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[__tid_Object__](ue_ue.BaseTransformGizmo.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PivotTransformGizmo\_\_

• **\_\_tid\_PivotTransformGizmo\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:57841](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57841)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bActorEnableCollision](ue_ue.BaseTransformGizmo.md#bactorenablecollision)

#### Defined in

[ue/ue.d.ts:13143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13143)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bActorIsBeingDestroyed](ue_ue.BaseTransformGizmo.md#bactorisbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13144](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13144)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bActorLabelEditable](ue_ue.BaseTransformGizmo.md#bactorlabeleditable)

#### Defined in

[ue/ue.d.ts:13183](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13183)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bActorSeamlessTraveled](ue_ue.BaseTransformGizmo.md#bactorseamlesstraveled)

#### Defined in

[ue/ue.d.ts:13139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13139)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.BaseTransformGizmo.md#ballowreceivetickeventondedicatedserver)

#### Defined in

[ue/ue.d.ts:13142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13142)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bAllowTickBeforeBeginPlay](ue_ue.BaseTransformGizmo.md#ballowtickbeforebeginplay)

#### Defined in

[ue/ue.d.ts:13129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13129)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bAlwaysRelevant](ue_ue.BaseTransformGizmo.md#balwaysrelevant)

#### Defined in

[ue/ue.d.ts:13120](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13120)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bAutoDestroyWhenFinished](ue_ue.BaseTransformGizmo.md#bautodestroywhenfinished)

#### Defined in

[ue/ue.d.ts:13130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13130)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bBlockInput](ue_ue.BaseTransformGizmo.md#bblockinput)

#### Defined in

[ue/ue.d.ts:13131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13131)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bCanBeDamaged](ue_ue.BaseTransformGizmo.md#bcanbedamaged)

#### Defined in

[ue/ue.d.ts:13132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13132)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bCanBeInCluster](ue_ue.BaseTransformGizmo.md#bcanbeincluster)

#### Defined in

[ue/ue.d.ts:13141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13141)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bCollideWhenPlacing](ue_ue.BaseTransformGizmo.md#bcollidewhenplacing)

#### Defined in

[ue/ue.d.ts:13133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13133)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bEditable](ue_ue.BaseTransformGizmo.md#beditable)

#### Defined in

[ue/ue.d.ts:13184](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13184)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bEnableAutoLODGeneration](ue_ue.BaseTransformGizmo.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:13137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13137)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bExchangedRoles](ue_ue.BaseTransformGizmo.md#bexchangedroles)

#### Defined in

[ue/ue.d.ts:13123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13123)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bFindCameraComponentWhenViewTarget](ue_ue.BaseTransformGizmo.md#bfindcameracomponentwhenviewtarget)

#### Defined in

[ue/ue.d.ts:13134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13134)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.BaseTransformGizmo.md#bgenerateoverlapeventsduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13135)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bHidden](ue_ue.BaseTransformGizmo.md#bhidden)

#### Defined in

[ue/ue.d.ts:13116](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13116)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bHiddenEd](ue_ue.BaseTransformGizmo.md#bhiddened)

#### Defined in

[ue/ue.d.ts:13178](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13178)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bHiddenEdLayer](ue_ue.BaseTransformGizmo.md#bhiddenedlayer)

#### Defined in

[ue/ue.d.ts:13180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13180)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bHiddenEdLevel](ue_ue.BaseTransformGizmo.md#bhiddenedlevel)

#### Defined in

[ue/ue.d.ts:13181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13181)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bHiddenEdTemporary](ue_ue.BaseTransformGizmo.md#bhiddenedtemporary)

#### Defined in

[ue/ue.d.ts:13187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13187)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bIgnoresOriginShifting](ue_ue.BaseTransformGizmo.md#bignoresoriginshifting)

#### Defined in

[ue/ue.d.ts:13136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13136)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bIsEditorOnlyActor](ue_ue.BaseTransformGizmo.md#biseditoronlyactor)

#### Defined in

[ue/ue.d.ts:13138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13138)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bIsEditorPreviewActor](ue_ue.BaseTransformGizmo.md#biseditorpreviewactor)

#### Defined in

[ue/ue.d.ts:13179](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13179)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bListedInSceneOutliner](ue_ue.BaseTransformGizmo.md#blistedinsceneoutliner)

#### Defined in

[ue/ue.d.ts:13185](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13185)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bLockLocation](ue_ue.BaseTransformGizmo.md#blocklocation)

#### Defined in

[ue/ue.d.ts:13182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13182)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bNetLoadOnClient](ue_ue.BaseTransformGizmo.md#bnetloadonclient)

#### Defined in

[ue/ue.d.ts:13124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13124)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bNetStartup](ue_ue.BaseTransformGizmo.md#bnetstartup)

#### Defined in

[ue/ue.d.ts:13118](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13118)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bNetTemporary](ue_ue.BaseTransformGizmo.md#bnettemporary)

#### Defined in

[ue/ue.d.ts:13117](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13117)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bNetUseOwnerRelevancy](ue_ue.BaseTransformGizmo.md#bnetuseownerrelevancy)

#### Defined in

[ue/ue.d.ts:13125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13125)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bOnlyRelevantToOwner](ue_ue.BaseTransformGizmo.md#bonlyrelevanttoowner)

#### Defined in

[ue/ue.d.ts:13119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13119)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bOptimizeBPComponentData](ue_ue.BaseTransformGizmo.md#boptimizebpcomponentdata)

#### Defined in

[ue/ue.d.ts:13186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13186)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bRelevantForLevelBounds](ue_ue.BaseTransformGizmo.md#brelevantforlevelbounds)

#### Defined in

[ue/ue.d.ts:13127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13127)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bRelevantForNetworkReplays](ue_ue.BaseTransformGizmo.md#brelevantfornetworkreplays)

#### Defined in

[ue/ue.d.ts:13126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13126)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bReplayRewindable](ue_ue.BaseTransformGizmo.md#breplayrewindable)

#### Defined in

[ue/ue.d.ts:13128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13128)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bReplicateMovement](ue_ue.BaseTransformGizmo.md#breplicatemovement)

#### Defined in

[ue/ue.d.ts:13121](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13121)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bReplicates](ue_ue.BaseTransformGizmo.md#breplicates)

#### Defined in

[ue/ue.d.ts:13140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13140)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[bTearOff](ue_ue.BaseTransformGizmo.md#btearoff)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ActorHasTag](ue_ue.BaseTransformGizmo.md#actorhastag)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[AddComponent](ue_ue.BaseTransformGizmo.md#addcomponent)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[AddTickPrerequisiteActor](ue_ue.BaseTransformGizmo.md#addtickprerequisiteactor)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[AddTickPrerequisiteComponent](ue_ue.BaseTransformGizmo.md#addtickprerequisitecomponent)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[CreateDefaultSubobject](ue_ue.BaseTransformGizmo.md#createdefaultsubobject)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[DetachRootComponentFromParent](ue_ue.BaseTransformGizmo.md#detachrootcomponentfromparent)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[DisableInput](ue_ue.BaseTransformGizmo.md#disableinput)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[EnableInput](ue_ue.BaseTransformGizmo.md#enableinput)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ExecuteUbergraph](ue_ue.BaseTransformGizmo.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[FlushNetDormancy](ue_ue.BaseTransformGizmo.md#flushnetdormancy)

#### Defined in

[ue/ue.d.ts:13214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13214)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ForceNetUpdate](ue_ue.BaseTransformGizmo.md#forcenetupdate)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorBounds](ue_ue.BaseTransformGizmo.md#getactorbounds)

#### Defined in

[ue/ue.d.ts:13216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13216)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorEnableCollision](ue_ue.BaseTransformGizmo.md#getactorenablecollision)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorEyesViewPoint](ue_ue.BaseTransformGizmo.md#getactoreyesviewpoint)

#### Defined in

[ue/ue.d.ts:13218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13218)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorForwardVector](ue_ue.BaseTransformGizmo.md#getactorforwardvector)

#### Defined in

[ue/ue.d.ts:13219](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13219)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorLabel](ue_ue.BaseTransformGizmo.md#getactorlabel)

#### Defined in

[ue/ue.d.ts:13220](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13220)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorRelativeScale3D](ue_ue.BaseTransformGizmo.md#getactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13221](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13221)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorRightVector](ue_ue.BaseTransformGizmo.md#getactorrightvector)

#### Defined in

[ue/ue.d.ts:13222](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13222)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorScale3D](ue_ue.BaseTransformGizmo.md#getactorscale3d)

#### Defined in

[ue/ue.d.ts:13223](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13223)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorTickInterval](ue_ue.BaseTransformGizmo.md#getactortickinterval)

#### Defined in

[ue/ue.d.ts:13224](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13224)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorTimeDilation](ue_ue.BaseTransformGizmo.md#getactortimedilation)

#### Defined in

[ue/ue.d.ts:13225](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13225)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetActorUpVector](ue_ue.BaseTransformGizmo.md#getactorupvector)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetAllChildActors](ue_ue.BaseTransformGizmo.md#getallchildactors)

#### Defined in

[ue/ue.d.ts:13227](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13227)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetAttachParentActor](ue_ue.BaseTransformGizmo.md#getattachparentactor)

#### Defined in

[ue/ue.d.ts:13229](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13229)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetAttachParentSocketName](ue_ue.BaseTransformGizmo.md#getattachparentsocketname)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetAttachedActors](ue_ue.BaseTransformGizmo.md#getattachedactors)

#### Defined in

[ue/ue.d.ts:13228](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13228)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetClass](ue_ue.BaseTransformGizmo.md#getclass)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetComponentByClass](ue_ue.BaseTransformGizmo.md#getcomponentbyclass)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetComponentsByInterface](ue_ue.BaseTransformGizmo.md#getcomponentsbyinterface)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetComponentsByTag](ue_ue.BaseTransformGizmo.md#getcomponentsbytag)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetDistanceTo](ue_ue.BaseTransformGizmo.md#getdistanceto)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetDotProductTo](ue_ue.BaseTransformGizmo.md#getdotproductto)

#### Defined in

[ue/ue.d.ts:13235](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13235)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetFolderPath](ue_ue.BaseTransformGizmo.md#getfolderpath)

#### Defined in

[ue/ue.d.ts:13236](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13236)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetGameTimeSinceCreation](ue_ue.BaseTransformGizmo.md#getgametimesincecreation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetHorizontalDistanceTo](ue_ue.BaseTransformGizmo.md#gethorizontaldistanceto)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetHorizontalDotProductTo](ue_ue.BaseTransformGizmo.md#gethorizontaldotproductto)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetInputAxisKeyValue](ue_ue.BaseTransformGizmo.md#getinputaxiskeyvalue)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetInputAxisValue](ue_ue.BaseTransformGizmo.md#getinputaxisvalue)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetInputVectorAxisValue](ue_ue.BaseTransformGizmo.md#getinputvectoraxisvalue)

#### Defined in

[ue/ue.d.ts:13242](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13242)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetInstigator](ue_ue.BaseTransformGizmo.md#getinstigator)

#### Defined in

[ue/ue.d.ts:13243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13243)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetInstigatorController](ue_ue.BaseTransformGizmo.md#getinstigatorcontroller)

#### Defined in

[ue/ue.d.ts:13244](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13244)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetLifeSpan](ue_ue.BaseTransformGizmo.md#getlifespan)

#### Defined in

[ue/ue.d.ts:13245](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13245)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetLocalRole](ue_ue.BaseTransformGizmo.md#getlocalrole)

#### Defined in

[ue/ue.d.ts:13246](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13246)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetName](ue_ue.BaseTransformGizmo.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetOuter](ue_ue.BaseTransformGizmo.md#getouter)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetOverlappingActors](ue_ue.BaseTransformGizmo.md#getoverlappingactors)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetOverlappingComponents](ue_ue.BaseTransformGizmo.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:13248](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13248)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetOwner](ue_ue.BaseTransformGizmo.md#getowner)

#### Defined in

[ue/ue.d.ts:13249](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13249)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetParentActor](ue_ue.BaseTransformGizmo.md#getparentactor)

#### Defined in

[ue/ue.d.ts:13250](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13250)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetParentComponent](ue_ue.BaseTransformGizmo.md#getparentcomponent)

#### Defined in

[ue/ue.d.ts:13251](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13251)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetRemoteRole](ue_ue.BaseTransformGizmo.md#getremoterole)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetSquaredDistanceTo](ue_ue.BaseTransformGizmo.md#getsquareddistanceto)

#### Defined in

[ue/ue.d.ts:13253](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13253)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetTickableWhenPaused](ue_ue.BaseTransformGizmo.md#gettickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13254](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13254)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetTransform](ue_ue.BaseTransformGizmo.md#gettransform)

#### Defined in

[ue/ue.d.ts:13255](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13255)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetVelocity](ue_ue.BaseTransformGizmo.md#getvelocity)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetVerticalDistanceTo](ue_ue.BaseTransformGizmo.md#getverticaldistanceto)

#### Defined in

[ue/ue.d.ts:13257](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13257)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[GetWorld](ue_ue.BaseTransformGizmo.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[HasAuthority](ue_ue.BaseTransformGizmo.md#hasauthority)

#### Defined in

[ue/ue.d.ts:13258](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13258)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsActorBeingDestroyed](ue_ue.BaseTransformGizmo.md#isactorbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13259](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13259)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsActorTickEnabled](ue_ue.BaseTransformGizmo.md#isactortickenabled)

#### Defined in

[ue/ue.d.ts:13260](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13260)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsChildActor](ue_ue.BaseTransformGizmo.md#ischildactor)

#### Defined in

[ue/ue.d.ts:13261](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13261)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsEditable](ue_ue.BaseTransformGizmo.md#iseditable)

#### Defined in

[ue/ue.d.ts:13262](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13262)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsHiddenEd](ue_ue.BaseTransformGizmo.md#ishiddened)

#### Defined in

[ue/ue.d.ts:13263](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13263)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsHiddenEdAtStartup](ue_ue.BaseTransformGizmo.md#ishiddenedatstartup)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsOverlappingActor](ue_ue.BaseTransformGizmo.md#isoverlappingactor)

#### Defined in

[ue/ue.d.ts:13265](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13265)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsSelectable](ue_ue.BaseTransformGizmo.md#isselectable)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[IsTemporarilyHiddenInEditor](ue_ue.BaseTransformGizmo.md#istemporarilyhiddenineditor)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AddActorLocalOffset](ue_ue.BaseTransformGizmo.md#k2_addactorlocaloffset)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AddActorLocalRotation](ue_ue.BaseTransformGizmo.md#k2_addactorlocalrotation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AddActorLocalTransform](ue_ue.BaseTransformGizmo.md#k2_addactorlocaltransform)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AddActorWorldOffset](ue_ue.BaseTransformGizmo.md#k2_addactorworldoffset)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AddActorWorldRotation](ue_ue.BaseTransformGizmo.md#k2_addactorworldrotation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AddActorWorldTransform](ue_ue.BaseTransformGizmo.md#k2_addactorworldtransform)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AttachRootComponentTo](ue_ue.BaseTransformGizmo.md#k2_attachrootcomponentto)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AttachRootComponentToActor](ue_ue.BaseTransformGizmo.md#k2_attachrootcomponenttoactor)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AttachToActor](ue_ue.BaseTransformGizmo.md#k2_attachtoactor)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_AttachToComponent](ue_ue.BaseTransformGizmo.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:13277](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13277)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_DestroyActor](ue_ue.BaseTransformGizmo.md#k2_destroyactor)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_DestroyComponent](ue_ue.BaseTransformGizmo.md#k2_destroycomponent)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_DetachFromActor](ue_ue.BaseTransformGizmo.md#k2_detachfromactor)

#### Defined in

[ue/ue.d.ts:13280](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13280)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_GetActorLocation](ue_ue.BaseTransformGizmo.md#k2_getactorlocation)

#### Defined in

[ue/ue.d.ts:13281](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13281)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_GetActorRotation](ue_ue.BaseTransformGizmo.md#k2_getactorrotation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_GetComponentsByClass](ue_ue.BaseTransformGizmo.md#k2_getcomponentsbyclass)

#### Defined in

[ue/ue.d.ts:13283](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13283)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_GetRootComponent](ue_ue.BaseTransformGizmo.md#k2_getrootcomponent)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_OnBecomeViewTarget](ue_ue.BaseTransformGizmo.md#k2_onbecomeviewtarget)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_OnEndViewTarget](ue_ue.BaseTransformGizmo.md#k2_onendviewtarget)

#### Defined in

[ue/ue.d.ts:13286](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13286)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_OnReset](ue_ue.BaseTransformGizmo.md#k2_onreset)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_SetActorLocation](ue_ue.BaseTransformGizmo.md#k2_setactorlocation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_SetActorLocationAndRotation](ue_ue.BaseTransformGizmo.md#k2_setactorlocationandrotation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_SetActorRelativeLocation](ue_ue.BaseTransformGizmo.md#k2_setactorrelativelocation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_SetActorRelativeRotation](ue_ue.BaseTransformGizmo.md#k2_setactorrelativerotation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_SetActorRelativeTransform](ue_ue.BaseTransformGizmo.md#k2_setactorrelativetransform)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_SetActorRotation](ue_ue.BaseTransformGizmo.md#k2_setactorrotation)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_SetActorTransform](ue_ue.BaseTransformGizmo.md#k2_setactortransform)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[K2_TeleportTo](ue_ue.BaseTransformGizmo.md#k2_teleportto)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[MakeMIDForMaterial](ue_ue.BaseTransformGizmo.md#makemidformaterial)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[MakeNoise](ue_ue.BaseTransformGizmo.md#makenoise)

#### Defined in

[ue/ue.d.ts:13297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13297)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnRep_AttachmentReplication](ue_ue.BaseTransformGizmo.md#onrep_attachmentreplication)

#### Defined in

[ue/ue.d.ts:13298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13298)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnRep_Instigator](ue_ue.BaseTransformGizmo.md#onrep_instigator)

#### Defined in

[ue/ue.d.ts:13299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13299)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnRep_Owner](ue_ue.BaseTransformGizmo.md#onrep_owner)

#### Defined in

[ue/ue.d.ts:13300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13300)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnRep_ReplicateMovement](ue_ue.BaseTransformGizmo.md#onrep_replicatemovement)

#### Defined in

[ue/ue.d.ts:13302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13302)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[OnRep_ReplicatedMovement](ue_ue.BaseTransformGizmo.md#onrep_replicatedmovement)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[PrestreamTextures](ue_ue.BaseTransformGizmo.md#prestreamtextures)

#### Defined in

[ue/ue.d.ts:13303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13303)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorBeginCursorOver](ue_ue.BaseTransformGizmo.md#receiveactorbegincursorover)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorBeginOverlap](ue_ue.BaseTransformGizmo.md#receiveactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13305)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorEndCursorOver](ue_ue.BaseTransformGizmo.md#receiveactorendcursorover)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorEndOverlap](ue_ue.BaseTransformGizmo.md#receiveactorendoverlap)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorOnClicked](ue_ue.BaseTransformGizmo.md#receiveactoronclicked)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorOnInputTouchBegin](ue_ue.BaseTransformGizmo.md#receiveactoroninputtouchbegin)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorOnInputTouchEnd](ue_ue.BaseTransformGizmo.md#receiveactoroninputtouchend)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorOnInputTouchEnter](ue_ue.BaseTransformGizmo.md#receiveactoroninputtouchenter)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorOnInputTouchLeave](ue_ue.BaseTransformGizmo.md#receiveactoroninputtouchleave)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveActorOnReleased](ue_ue.BaseTransformGizmo.md#receiveactoronreleased)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveAnyDamage](ue_ue.BaseTransformGizmo.md#receiveanydamage)

#### Defined in

[ue/ue.d.ts:13314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13314)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveBeginPlay](ue_ue.BaseTransformGizmo.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:13315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13315)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveDestroyed](ue_ue.BaseTransformGizmo.md#receivedestroyed)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveEndPlay](ue_ue.BaseTransformGizmo.md#receiveendplay)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveHit](ue_ue.BaseTransformGizmo.md#receivehit)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceivePointDamage](ue_ue.BaseTransformGizmo.md#receivepointdamage)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveRadialDamage](ue_ue.BaseTransformGizmo.md#receiveradialdamage)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[ReceiveTick](ue_ue.BaseTransformGizmo.md#receivetick)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[RemoveTickPrerequisiteActor](ue_ue.BaseTransformGizmo.md#removetickprerequisiteactor)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[RemoveTickPrerequisiteComponent](ue_ue.BaseTransformGizmo.md#removetickprerequisitecomponent)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetActorEnableCollision](ue_ue.BaseTransformGizmo.md#setactorenablecollision)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetActorHiddenInGame](ue_ue.BaseTransformGizmo.md#setactorhiddeningame)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetActorLabel](ue_ue.BaseTransformGizmo.md#setactorlabel)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetActorRelativeScale3D](ue_ue.BaseTransformGizmo.md#setactorrelativescale3d)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetActorScale3D](ue_ue.BaseTransformGizmo.md#setactorscale3d)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetActorTickEnabled](ue_ue.BaseTransformGizmo.md#setactortickenabled)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetActorTickInterval](ue_ue.BaseTransformGizmo.md#setactortickinterval)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetFolderPath](ue_ue.BaseTransformGizmo.md#setfolderpath)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetIsTemporarilyHiddenInEditor](ue_ue.BaseTransformGizmo.md#setistemporarilyhiddenineditor)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetLifeSpan](ue_ue.BaseTransformGizmo.md#setlifespan)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetNetDormancy](ue_ue.BaseTransformGizmo.md#setnetdormancy)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetOwner](ue_ue.BaseTransformGizmo.md#setowner)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetReplicateMovement](ue_ue.BaseTransformGizmo.md#setreplicatemovement)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetReplicates](ue_ue.BaseTransformGizmo.md#setreplicates)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetTickGroup](ue_ue.BaseTransformGizmo.md#settickgroup)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SetTickableWhenPaused](ue_ue.BaseTransformGizmo.md#settickablewhenpaused)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[SnapRootComponentTo](ue_ue.BaseTransformGizmo.md#snaprootcomponentto)

#### Defined in

[ue/ue.d.ts:13340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13340)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[TearOff](ue_ue.BaseTransformGizmo.md#tearoff)

#### Defined in

[ue/ue.d.ts:13341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13341)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[UserConstructionScript](ue_ue.BaseTransformGizmo.md#userconstructionscript)

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

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[WasRecentlyRendered](ue_ue.BaseTransformGizmo.md#wasrecentlyrendered)

#### Defined in

[ue/ue.d.ts:13343](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13343)

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

#### Defined in

[ue/ue.d.ts:57838](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57838)

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

#### Defined in

[ue/ue.d.ts:57839](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57839)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BaseTransformGizmo](ue_ue.BaseTransformGizmo.md).[StaticClass](ue_ue.BaseTransformGizmo.md#staticclass)

#### Defined in

[ue/ue.d.ts:57837](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57837)
