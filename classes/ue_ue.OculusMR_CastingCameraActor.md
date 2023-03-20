[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / OculusMR\_CastingCameraActor

# Class: OculusMR\_CastingCameraActor

[ue/ue](../modules/ue_ue.md).OculusMR_CastingCameraActor

## Hierarchy

- [`SceneCapture2D`](ue_ue.SceneCapture2D.md)

  ↳ **`OculusMR_CastingCameraActor`**

## Table of contents

### Constructors

- [constructor](ue_ue.OculusMR_CastingCameraActor.md#constructor)

### Properties

- [ActorLabel](ue_ue.OculusMR_CastingCameraActor.md#actorlabel)
- [AttachmentReplication](ue_ue.OculusMR_CastingCameraActor.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.OculusMR_CastingCameraActor.md#autoreceiveinput)
- [BackdropMaterialInstance](ue_ue.OculusMR_CastingCameraActor.md#backdropmaterialinstance)
- [BackgroundRenderTargets](ue_ue.OculusMR_CastingCameraActor.md#backgroundrendertargets)
- [BlueprintCreatedComponents](ue_ue.OculusMR_CastingCameraActor.md#blueprintcreatedcomponents)
- [BoundaryActor](ue_ue.OculusMR_CastingCameraActor.md#boundaryactor)
- [BoundarySceneCaptureActor](ue_ue.OculusMR_CastingCameraActor.md#boundaryscenecaptureactor)
- [CameraColorTexture](ue_ue.OculusMR_CastingCameraActor.md#cameracolortexture)
- [CameraDepthTexture](ue_ue.OculusMR_CastingCameraActor.md#cameradepthtexture)
- [CameraFrameMaterialInstance](ue_ue.OculusMR_CastingCameraActor.md#cameraframematerialinstance)
- [CaptureComponent2D](ue_ue.OculusMR_CastingCameraActor.md#capturecomponent2d)
- [Children](ue_ue.OculusMR_CastingCameraActor.md#children)
- [ChromaKeyLitMaterial](ue_ue.OculusMR_CastingCameraActor.md#chromakeylitmaterial)
- [ChromaKeyLitMaterialInstance](ue_ue.OculusMR_CastingCameraActor.md#chromakeylitmaterialinstance)
- [ChromaKeyMaterial](ue_ue.OculusMR_CastingCameraActor.md#chromakeymaterial)
- [ChromaKeyMaterialInstance](ue_ue.OculusMR_CastingCameraActor.md#chromakeymaterialinstance)
- [ControllingMatineeActors](ue_ue.OculusMR_CastingCameraActor.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.OculusMR_CastingCameraActor.md#customtimedilation)
- [DefaultTexture\_White](ue_ue.OculusMR_CastingCameraActor.md#defaulttexture_white)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.OculusMR_CastingCameraActor.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.OculusMR_CastingCameraActor.md#folderpath)
- [ForegroundCaptureActor](ue_ue.OculusMR_CastingCameraActor.md#foregroundcaptureactor)
- [ForegroundRenderTargets](ue_ue.OculusMR_CastingCameraActor.md#foregroundrendertargets)
- [GroupActor](ue_ue.OculusMR_CastingCameraActor.md#groupactor)
- [HiddenEditorViews](ue_ue.OculusMR_CastingCameraActor.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.OculusMR_CastingCameraActor.md#initiallifespan)
- [InputComponent](ue_ue.OculusMR_CastingCameraActor.md#inputcomponent)
- [InputPriority](ue_ue.OculusMR_CastingCameraActor.md#inputpriority)
- [InstanceComponents](ue_ue.OculusMR_CastingCameraActor.md#instancecomponents)
- [Instigator](ue_ue.OculusMR_CastingCameraActor.md#instigator)
- [Layers](ue_ue.OculusMR_CastingCameraActor.md#layers)
- [MRSettings](ue_ue.OculusMR_CastingCameraActor.md#mrsettings)
- [MRState](ue_ue.OculusMR_CastingCameraActor.md#mrstate)
- [MeshComp](ue_ue.OculusMR_CastingCameraActor.md#meshcomp)
- [MinNetUpdateFrequency](ue_ue.OculusMR_CastingCameraActor.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.OculusMR_CastingCameraActor.md#netculldistancesquared)
- [NetDormancy](ue_ue.OculusMR_CastingCameraActor.md#netdormancy)
- [NetDriverName](ue_ue.OculusMR_CastingCameraActor.md#netdrivername)
- [NetPriority](ue_ue.OculusMR_CastingCameraActor.md#netpriority)
- [NetTag](ue_ue.OculusMR_CastingCameraActor.md#nettag)
- [NetUpdateFrequency](ue_ue.OculusMR_CastingCameraActor.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.OculusMR_CastingCameraActor.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.OculusMR_CastingCameraActor.md#onactorendoverlap)
- [OnActorHit](ue_ue.OculusMR_CastingCameraActor.md#onactorhit)
- [OnBeginCursorOver](ue_ue.OculusMR_CastingCameraActor.md#onbegincursorover)
- [OnClicked](ue_ue.OculusMR_CastingCameraActor.md#onclicked)
- [OnDestroyed](ue_ue.OculusMR_CastingCameraActor.md#ondestroyed)
- [OnEndCursorOver](ue_ue.OculusMR_CastingCameraActor.md#onendcursorover)
- [OnEndPlay](ue_ue.OculusMR_CastingCameraActor.md#onendplay)
- [OnInputTouchBegin](ue_ue.OculusMR_CastingCameraActor.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.OculusMR_CastingCameraActor.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.OculusMR_CastingCameraActor.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.OculusMR_CastingCameraActor.md#oninputtouchleave)
- [OnReleased](ue_ue.OculusMR_CastingCameraActor.md#onreleased)
- [OnTakeAnyDamage](ue_ue.OculusMR_CastingCameraActor.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.OculusMR_CastingCameraActor.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.OculusMR_CastingCameraActor.md#ontakeradialdamage)
- [OpaqueColoredMaterial](ue_ue.OculusMR_CastingCameraActor.md#opaquecoloredmaterial)
- [Owner](ue_ue.OculusMR_CastingCameraActor.md#owner)
- [ParentComponent](ue_ue.OculusMR_CastingCameraActor.md#parentcomponent)
- [ParentComponentActor](ue_ue.OculusMR_CastingCameraActor.md#parentcomponentactor)
- [PivotOffset](ue_ue.OculusMR_CastingCameraActor.md#pivotoffset)
- [PlaneMeshComponent](ue_ue.OculusMR_CastingCameraActor.md#planemeshcomponent)
- [PrimaryActorTick](ue_ue.OculusMR_CastingCameraActor.md#primaryactortick)
- [RemoteRole](ue_ue.OculusMR_CastingCameraActor.md#remoterole)
- [ReplicatedMovement](ue_ue.OculusMR_CastingCameraActor.md#replicatedmovement)
- [Role](ue_ue.OculusMR_CastingCameraActor.md#role)
- [RootComponent](ue_ue.OculusMR_CastingCameraActor.md#rootcomponent)
- [SceneComponent](ue_ue.OculusMR_CastingCameraActor.md#scenecomponent)
- [SpawnCollisionHandlingMethod](ue_ue.OculusMR_CastingCameraActor.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.OculusMR_CastingCameraActor.md#spritescale)
- [Tags](ue_ue.OculusMR_CastingCameraActor.md#tags)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.OculusMR_CastingCameraActor.md#updateoverlapsmethodduringlevelstreaming)
- [VRNotificationComponent](ue_ue.OculusMR_CastingCameraActor.md#vrnotificationcomponent)
- [\_\_tid\_Actor\_\_](ue_ue.OculusMR_CastingCameraActor.md#__tid_actor__)
- [\_\_tid\_Object\_\_](ue_ue.OculusMR_CastingCameraActor.md#__tid_object__)
- [\_\_tid\_OculusMR\_CastingCameraActor\_\_](ue_ue.OculusMR_CastingCameraActor.md#__tid_oculusmr_castingcameraactor__)
- [\_\_tid\_SceneCapture2D\_\_](ue_ue.OculusMR_CastingCameraActor.md#__tid_scenecapture2d__)
- [\_\_tid\_SceneCapture\_\_](ue_ue.OculusMR_CastingCameraActor.md#__tid_scenecapture__)
- [bActorEnableCollision](ue_ue.OculusMR_CastingCameraActor.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.OculusMR_CastingCameraActor.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.OculusMR_CastingCameraActor.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.OculusMR_CastingCameraActor.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.OculusMR_CastingCameraActor.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.OculusMR_CastingCameraActor.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.OculusMR_CastingCameraActor.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.OculusMR_CastingCameraActor.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.OculusMR_CastingCameraActor.md#bblockinput)
- [bCanBeDamaged](ue_ue.OculusMR_CastingCameraActor.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.OculusMR_CastingCameraActor.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.OculusMR_CastingCameraActor.md#bcollidewhenplacing)
- [bEditable](ue_ue.OculusMR_CastingCameraActor.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.OculusMR_CastingCameraActor.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.OculusMR_CastingCameraActor.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.OculusMR_CastingCameraActor.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.OculusMR_CastingCameraActor.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.OculusMR_CastingCameraActor.md#bhidden)
- [bHiddenEd](ue_ue.OculusMR_CastingCameraActor.md#bhiddened)
- [bHiddenEdLayer](ue_ue.OculusMR_CastingCameraActor.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.OculusMR_CastingCameraActor.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.OculusMR_CastingCameraActor.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.OculusMR_CastingCameraActor.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.OculusMR_CastingCameraActor.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.OculusMR_CastingCameraActor.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.OculusMR_CastingCameraActor.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.OculusMR_CastingCameraActor.md#blocklocation)
- [bNetLoadOnClient](ue_ue.OculusMR_CastingCameraActor.md#bnetloadonclient)
- [bNetStartup](ue_ue.OculusMR_CastingCameraActor.md#bnetstartup)
- [bNetTemporary](ue_ue.OculusMR_CastingCameraActor.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.OculusMR_CastingCameraActor.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.OculusMR_CastingCameraActor.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.OculusMR_CastingCameraActor.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.OculusMR_CastingCameraActor.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.OculusMR_CastingCameraActor.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.OculusMR_CastingCameraActor.md#breplayrewindable)
- [bReplicateMovement](ue_ue.OculusMR_CastingCameraActor.md#breplicatemovement)
- [bReplicates](ue_ue.OculusMR_CastingCameraActor.md#breplicates)
- [bTearOff](ue_ue.OculusMR_CastingCameraActor.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.OculusMR_CastingCameraActor.md#actorhastag)
- [AddComponent](ue_ue.OculusMR_CastingCameraActor.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.OculusMR_CastingCameraActor.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.OculusMR_CastingCameraActor.md#addtickprerequisitecomponent)
- [CreateDefaultSubobject](ue_ue.OculusMR_CastingCameraActor.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.OculusMR_CastingCameraActor.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.OculusMR_CastingCameraActor.md#disableinput)
- [EnableInput](ue_ue.OculusMR_CastingCameraActor.md#enableinput)
- [ExecuteUbergraph](ue_ue.OculusMR_CastingCameraActor.md#executeubergraph)
- [FlushNetDormancy](ue_ue.OculusMR_CastingCameraActor.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.OculusMR_CastingCameraActor.md#forcenetupdate)
- [GetActorBounds](ue_ue.OculusMR_CastingCameraActor.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.OculusMR_CastingCameraActor.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.OculusMR_CastingCameraActor.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.OculusMR_CastingCameraActor.md#getactorforwardvector)
- [GetActorLabel](ue_ue.OculusMR_CastingCameraActor.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.OculusMR_CastingCameraActor.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.OculusMR_CastingCameraActor.md#getactorrightvector)
- [GetActorScale3D](ue_ue.OculusMR_CastingCameraActor.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.OculusMR_CastingCameraActor.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.OculusMR_CastingCameraActor.md#getactortimedilation)
- [GetActorUpVector](ue_ue.OculusMR_CastingCameraActor.md#getactorupvector)
- [GetAllChildActors](ue_ue.OculusMR_CastingCameraActor.md#getallchildactors)
- [GetAttachParentActor](ue_ue.OculusMR_CastingCameraActor.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.OculusMR_CastingCameraActor.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.OculusMR_CastingCameraActor.md#getattachedactors)
- [GetClass](ue_ue.OculusMR_CastingCameraActor.md#getclass)
- [GetComponentByClass](ue_ue.OculusMR_CastingCameraActor.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.OculusMR_CastingCameraActor.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.OculusMR_CastingCameraActor.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.OculusMR_CastingCameraActor.md#getdistanceto)
- [GetDotProductTo](ue_ue.OculusMR_CastingCameraActor.md#getdotproductto)
- [GetFolderPath](ue_ue.OculusMR_CastingCameraActor.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.OculusMR_CastingCameraActor.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.OculusMR_CastingCameraActor.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.OculusMR_CastingCameraActor.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.OculusMR_CastingCameraActor.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.OculusMR_CastingCameraActor.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.OculusMR_CastingCameraActor.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.OculusMR_CastingCameraActor.md#getinstigator)
- [GetInstigatorController](ue_ue.OculusMR_CastingCameraActor.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.OculusMR_CastingCameraActor.md#getlifespan)
- [GetLocalRole](ue_ue.OculusMR_CastingCameraActor.md#getlocalrole)
- [GetName](ue_ue.OculusMR_CastingCameraActor.md#getname)
- [GetOuter](ue_ue.OculusMR_CastingCameraActor.md#getouter)
- [GetOverlappingActors](ue_ue.OculusMR_CastingCameraActor.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.OculusMR_CastingCameraActor.md#getoverlappingcomponents)
- [GetOwner](ue_ue.OculusMR_CastingCameraActor.md#getowner)
- [GetParentActor](ue_ue.OculusMR_CastingCameraActor.md#getparentactor)
- [GetParentComponent](ue_ue.OculusMR_CastingCameraActor.md#getparentcomponent)
- [GetRemoteRole](ue_ue.OculusMR_CastingCameraActor.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.OculusMR_CastingCameraActor.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.OculusMR_CastingCameraActor.md#gettickablewhenpaused)
- [GetTransform](ue_ue.OculusMR_CastingCameraActor.md#gettransform)
- [GetVelocity](ue_ue.OculusMR_CastingCameraActor.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.OculusMR_CastingCameraActor.md#getverticaldistanceto)
- [GetWorld](ue_ue.OculusMR_CastingCameraActor.md#getworld)
- [HasAuthority](ue_ue.OculusMR_CastingCameraActor.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.OculusMR_CastingCameraActor.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.OculusMR_CastingCameraActor.md#isactortickenabled)
- [IsChildActor](ue_ue.OculusMR_CastingCameraActor.md#ischildactor)
- [IsEditable](ue_ue.OculusMR_CastingCameraActor.md#iseditable)
- [IsHiddenEd](ue_ue.OculusMR_CastingCameraActor.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.OculusMR_CastingCameraActor.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.OculusMR_CastingCameraActor.md#isoverlappingactor)
- [IsSelectable](ue_ue.OculusMR_CastingCameraActor.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.OculusMR_CastingCameraActor.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.OculusMR_CastingCameraActor.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.OculusMR_CastingCameraActor.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.OculusMR_CastingCameraActor.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.OculusMR_CastingCameraActor.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.OculusMR_CastingCameraActor.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.OculusMR_CastingCameraActor.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.OculusMR_CastingCameraActor.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.OculusMR_CastingCameraActor.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.OculusMR_CastingCameraActor.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.OculusMR_CastingCameraActor.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.OculusMR_CastingCameraActor.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.OculusMR_CastingCameraActor.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.OculusMR_CastingCameraActor.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.OculusMR_CastingCameraActor.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.OculusMR_CastingCameraActor.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.OculusMR_CastingCameraActor.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.OculusMR_CastingCameraActor.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.OculusMR_CastingCameraActor.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.OculusMR_CastingCameraActor.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.OculusMR_CastingCameraActor.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.OculusMR_CastingCameraActor.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.OculusMR_CastingCameraActor.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.OculusMR_CastingCameraActor.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.OculusMR_CastingCameraActor.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.OculusMR_CastingCameraActor.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.OculusMR_CastingCameraActor.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.OculusMR_CastingCameraActor.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.OculusMR_CastingCameraActor.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.OculusMR_CastingCameraActor.md#makemidformaterial)
- [MakeNoise](ue_ue.OculusMR_CastingCameraActor.md#makenoise)
- [OnInterpToggle](ue_ue.OculusMR_CastingCameraActor.md#oninterptoggle)
- [OnRep\_AttachmentReplication](ue_ue.OculusMR_CastingCameraActor.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.OculusMR_CastingCameraActor.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.OculusMR_CastingCameraActor.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.OculusMR_CastingCameraActor.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.OculusMR_CastingCameraActor.md#onrep_replicatedmovement)
- [PrestreamTextures](ue_ue.OculusMR_CastingCameraActor.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.OculusMR_CastingCameraActor.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.OculusMR_CastingCameraActor.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.OculusMR_CastingCameraActor.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.OculusMR_CastingCameraActor.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.OculusMR_CastingCameraActor.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.OculusMR_CastingCameraActor.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.OculusMR_CastingCameraActor.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.OculusMR_CastingCameraActor.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.OculusMR_CastingCameraActor.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.OculusMR_CastingCameraActor.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.OculusMR_CastingCameraActor.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.OculusMR_CastingCameraActor.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.OculusMR_CastingCameraActor.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.OculusMR_CastingCameraActor.md#receiveendplay)
- [ReceiveHit](ue_ue.OculusMR_CastingCameraActor.md#receivehit)
- [ReceivePointDamage](ue_ue.OculusMR_CastingCameraActor.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.OculusMR_CastingCameraActor.md#receiveradialdamage)
- [ReceiveTick](ue_ue.OculusMR_CastingCameraActor.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.OculusMR_CastingCameraActor.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.OculusMR_CastingCameraActor.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.OculusMR_CastingCameraActor.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.OculusMR_CastingCameraActor.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.OculusMR_CastingCameraActor.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.OculusMR_CastingCameraActor.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.OculusMR_CastingCameraActor.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.OculusMR_CastingCameraActor.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.OculusMR_CastingCameraActor.md#setactortickinterval)
- [SetFolderPath](ue_ue.OculusMR_CastingCameraActor.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.OculusMR_CastingCameraActor.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.OculusMR_CastingCameraActor.md#setlifespan)
- [SetNetDormancy](ue_ue.OculusMR_CastingCameraActor.md#setnetdormancy)
- [SetOwner](ue_ue.OculusMR_CastingCameraActor.md#setowner)
- [SetReplicateMovement](ue_ue.OculusMR_CastingCameraActor.md#setreplicatemovement)
- [SetReplicates](ue_ue.OculusMR_CastingCameraActor.md#setreplicates)
- [SetTickGroup](ue_ue.OculusMR_CastingCameraActor.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.OculusMR_CastingCameraActor.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.OculusMR_CastingCameraActor.md#snaprootcomponentto)
- [TearOff](ue_ue.OculusMR_CastingCameraActor.md#tearoff)
- [UserConstructionScript](ue_ue.OculusMR_CastingCameraActor.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.OculusMR_CastingCameraActor.md#wasrecentlyrendered)
- [Find](ue_ue.OculusMR_CastingCameraActor.md#find)
- [Load](ue_ue.OculusMR_CastingCameraActor.md#load)
- [StaticClass](ue_ue.OculusMR_CastingCameraActor.md#staticclass)

## Constructors

### constructor

• **new OculusMR_CastingCameraActor**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SceneCapture2D](ue_ue.SceneCapture2D.md).[constructor](ue_ue.SceneCapture2D.md#constructor)

#### Defined in

[ue/ue.d.ts:54028](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54028)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ActorLabel](ue_ue.SceneCapture2D.md#actorlabel)

#### Defined in

[ue/ue.d.ts:13176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13176)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[AttachmentReplication](ue_ue.SceneCapture2D.md#attachmentreplication)

#### Defined in

[ue/ue.d.ts:13151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13151)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[AutoReceiveInput](ue_ue.SceneCapture2D.md#autoreceiveinput)

#### Defined in

[ue/ue.d.ts:13157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13157)

___

### BackdropMaterialInstance

• **BackdropMaterialInstance**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:54039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54039)

___

### BackgroundRenderTargets

• **BackgroundRenderTargets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)\>

#### Defined in

[ue/ue.d.ts:54043](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54043)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[BlueprintCreatedComponents](ue_ue.SceneCapture2D.md#blueprintcreatedcomponents)

#### Defined in

[ue/ue.d.ts:13206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13206)

___

### BoundaryActor

• **BoundaryActor**: [`OculusMR_BoundaryActor`](ue_ue.OculusMR_BoundaryActor.md)

#### Defined in

[ue/ue.d.ts:54040](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54040)

___

### BoundarySceneCaptureActor

• **BoundarySceneCaptureActor**: [`SceneCapture2D`](ue_ue.SceneCapture2D.md)

#### Defined in

[ue/ue.d.ts:54041](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54041)

___

### CameraColorTexture

• **CameraColorTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:54030](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54030)

___

### CameraDepthTexture

• **CameraDepthTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:54031](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54031)

___

### CameraFrameMaterialInstance

• **CameraFrameMaterialInstance**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:54038](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54038)

___

### CaptureComponent2D

• **CaptureComponent2D**: [`SceneCaptureComponent2D`](ue_ue.SceneCaptureComponent2D.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[CaptureComponent2D](ue_ue.SceneCapture2D.md#capturecomponent2d)

#### Defined in

[ue/ue.d.ts:53910](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53910)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[Children](ue_ue.SceneCapture2D.md#children)

#### Defined in

[ue/ue.d.ts:13166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13166)

___

### ChromaKeyLitMaterial

• **ChromaKeyLitMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:54034](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54034)

___

### ChromaKeyLitMaterialInstance

• **ChromaKeyLitMaterialInstance**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:54037](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54037)

___

### ChromaKeyMaterial

• **ChromaKeyMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:54033](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54033)

___

### ChromaKeyMaterialInstance

• **ChromaKeyMaterialInstance**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:54036](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54036)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ControllingMatineeActors](ue_ue.SceneCapture2D.md#controllingmatineeactors)

#### Defined in

[ue/ue.d.ts:13169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13169)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[CustomTimeDilation](ue_ue.SceneCapture2D.md#customtimedilation)

#### Defined in

[ue/ue.d.ts:13150](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13150)

___

### DefaultTexture\_White

• **DefaultTexture\_White**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:54042](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54042)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.SceneCapture2D.md#defaultupdateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13146](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13146)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[FolderPath](ue_ue.SceneCapture2D.md#folderpath)

#### Defined in

[ue/ue.d.ts:13177](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13177)

___

### ForegroundCaptureActor

• **ForegroundCaptureActor**: [`SceneCapture2D`](ue_ue.SceneCapture2D.md)

#### Defined in

[ue/ue.d.ts:54044](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54044)

___

### ForegroundRenderTargets

• **ForegroundRenderTargets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)\>

#### Defined in

[ue/ue.d.ts:54045](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54045)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GroupActor](ue_ue.SceneCapture2D.md#groupactor)

#### Defined in

[ue/ue.d.ts:13173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13173)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[HiddenEditorViews](ue_ue.SceneCapture2D.md#hiddeneditorviews)

#### Defined in

[ue/ue.d.ts:13175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13175)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[InitialLifeSpan](ue_ue.SceneCapture2D.md#initiallifespan)

#### Defined in

[ue/ue.d.ts:13149](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13149)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[InputComponent](ue_ue.SceneCapture2D.md#inputcomponent)

#### Defined in

[ue/ue.d.ts:13159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13159)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[InputPriority](ue_ue.SceneCapture2D.md#inputpriority)

#### Defined in

[ue/ue.d.ts:13158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13158)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[InstanceComponents](ue_ue.SceneCapture2D.md#instancecomponents)

#### Defined in

[ue/ue.d.ts:13205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13205)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[Instigator](ue_ue.SceneCapture2D.md#instigator)

#### Defined in

[ue/ue.d.ts:13165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13165)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[Layers](ue_ue.SceneCapture2D.md#layers)

#### Defined in

[ue/ue.d.ts:13170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13170)

___

### MRSettings

• **MRSettings**: [`OculusMR_Settings`](ue_ue.OculusMR_Settings.md)

#### Defined in

[ue/ue.d.ts:54046](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54046)

___

### MRState

• **MRState**: [`OculusMR_State`](ue_ue.OculusMR_State.md)

#### Defined in

[ue/ue.d.ts:54047](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54047)

___

### MeshComp

• **MeshComp**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[MeshComp](ue_ue.SceneCapture2D.md#meshcomp)

#### Defined in

[ue/ue.d.ts:53826](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53826)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[MinNetUpdateFrequency](ue_ue.SceneCapture2D.md#minnetupdatefrequency)

#### Defined in

[ue/ue.d.ts:13163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13163)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[NetCullDistanceSquared](ue_ue.SceneCapture2D.md#netculldistancesquared)

#### Defined in

[ue/ue.d.ts:13160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13160)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[NetDormancy](ue_ue.SceneCapture2D.md#netdormancy)

#### Defined in

[ue/ue.d.ts:13155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13155)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[NetDriverName](ue_ue.SceneCapture2D.md#netdrivername)

#### Defined in

[ue/ue.d.ts:13153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13153)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[NetPriority](ue_ue.SceneCapture2D.md#netpriority)

#### Defined in

[ue/ue.d.ts:13164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13164)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[NetTag](ue_ue.SceneCapture2D.md#nettag)

#### Defined in

[ue/ue.d.ts:13161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13161)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[NetUpdateFrequency](ue_ue.SceneCapture2D.md#netupdatefrequency)

#### Defined in

[ue/ue.d.ts:13162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13162)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnActorBeginOverlap](ue_ue.SceneCapture2D.md#onactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13192)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnActorEndOverlap](ue_ue.SceneCapture2D.md#onactorendoverlap)

#### Defined in

[ue/ue.d.ts:13193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13193)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnActorHit](ue_ue.SceneCapture2D.md#onactorhit)

#### Defined in

[ue/ue.d.ts:13202](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13202)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnBeginCursorOver](ue_ue.SceneCapture2D.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:13194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13194)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnClicked](ue_ue.SceneCapture2D.md#onclicked)

#### Defined in

[ue/ue.d.ts:13196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13196)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnDestroyed](ue_ue.SceneCapture2D.md#ondestroyed)

#### Defined in

[ue/ue.d.ts:13203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13203)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnEndCursorOver](ue_ue.SceneCapture2D.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:13195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13195)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnEndPlay](ue_ue.SceneCapture2D.md#onendplay)

#### Defined in

[ue/ue.d.ts:13204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13204)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnInputTouchBegin](ue_ue.SceneCapture2D.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13198)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnInputTouchEnd](ue_ue.SceneCapture2D.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:13199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13199)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnInputTouchEnter](ue_ue.SceneCapture2D.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:13200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13200)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnInputTouchLeave](ue_ue.SceneCapture2D.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:13201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13201)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnReleased](ue_ue.SceneCapture2D.md#onreleased)

#### Defined in

[ue/ue.d.ts:13197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13197)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnTakeAnyDamage](ue_ue.SceneCapture2D.md#ontakeanydamage)

#### Defined in

[ue/ue.d.ts:13189](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13189)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnTakePointDamage](ue_ue.SceneCapture2D.md#ontakepointdamage)

#### Defined in

[ue/ue.d.ts:13190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13190)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnTakeRadialDamage](ue_ue.SceneCapture2D.md#ontakeradialdamage)

#### Defined in

[ue/ue.d.ts:13191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13191)

___

### OpaqueColoredMaterial

• **OpaqueColoredMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:54035](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54035)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[Owner](ue_ue.SceneCapture2D.md#owner)

#### Defined in

[ue/ue.d.ts:13152](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13152)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ParentComponent](ue_ue.SceneCapture2D.md#parentcomponent)

#### Defined in

[ue/ue.d.ts:13172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13172)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ParentComponentActor](ue_ue.SceneCapture2D.md#parentcomponentactor)

#### Defined in

[ue/ue.d.ts:13171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13171)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[PivotOffset](ue_ue.SceneCapture2D.md#pivotoffset)

#### Defined in

[ue/ue.d.ts:13168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13168)

___

### PlaneMeshComponent

• **PlaneMeshComponent**: [`OculusMR_PlaneMeshComponent`](ue_ue.OculusMR_PlaneMeshComponent.md)

#### Defined in

[ue/ue.d.ts:54032](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54032)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[PrimaryActorTick](ue_ue.SceneCapture2D.md#primaryactortick)

#### Defined in

[ue/ue.d.ts:13115](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13115)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[RemoteRole](ue_ue.SceneCapture2D.md#remoterole)

#### Defined in

[ue/ue.d.ts:13147](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13147)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReplicatedMovement](ue_ue.SceneCapture2D.md#replicatedmovement)

#### Defined in

[ue/ue.d.ts:13148](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13148)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[Role](ue_ue.SceneCapture2D.md#role)

#### Defined in

[ue/ue.d.ts:13154](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13154)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[RootComponent](ue_ue.SceneCapture2D.md#rootcomponent)

#### Defined in

[ue/ue.d.ts:13167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13167)

___

### SceneComponent

• **SceneComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SceneComponent](ue_ue.SceneCapture2D.md#scenecomponent)

#### Defined in

[ue/ue.d.ts:53827](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53827)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SpawnCollisionHandlingMethod](ue_ue.SceneCapture2D.md#spawncollisionhandlingmethod)

#### Defined in

[ue/ue.d.ts:13156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13156)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SpriteScale](ue_ue.SceneCapture2D.md#spritescale)

#### Defined in

[ue/ue.d.ts:13174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13174)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[Tags](ue_ue.SceneCapture2D.md#tags)

#### Defined in

[ue/ue.d.ts:13188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13188)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.SceneCapture2D.md#updateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13145](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13145)

___

### VRNotificationComponent

• **VRNotificationComponent**: [`VRNotificationsComponent`](ue_ue.VRNotificationsComponent.md)

#### Defined in

[ue/ue.d.ts:54029](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54029)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[__tid_Actor__](ue_ue.SceneCapture2D.md#__tid_actor__)

#### Defined in

[ue/ue.d.ts:13348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13348)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[__tid_Object__](ue_ue.SceneCapture2D.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_OculusMR\_CastingCameraActor\_\_

• **\_\_tid\_OculusMR\_CastingCameraActor\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:54052](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54052)

___

### \_\_tid\_SceneCapture2D\_\_

• **\_\_tid\_SceneCapture2D\_\_**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[__tid_SceneCapture2D__](ue_ue.SceneCapture2D.md#__tid_scenecapture2d__)

#### Defined in

[ue/ue.d.ts:53916](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53916)

___

### \_\_tid\_SceneCapture\_\_

• **\_\_tid\_SceneCapture\_\_**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[__tid_SceneCapture__](ue_ue.SceneCapture2D.md#__tid_scenecapture__)

#### Defined in

[ue/ue.d.ts:53832](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53832)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bActorEnableCollision](ue_ue.SceneCapture2D.md#bactorenablecollision)

#### Defined in

[ue/ue.d.ts:13143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13143)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bActorIsBeingDestroyed](ue_ue.SceneCapture2D.md#bactorisbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13144](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13144)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bActorLabelEditable](ue_ue.SceneCapture2D.md#bactorlabeleditable)

#### Defined in

[ue/ue.d.ts:13183](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13183)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bActorSeamlessTraveled](ue_ue.SceneCapture2D.md#bactorseamlesstraveled)

#### Defined in

[ue/ue.d.ts:13139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13139)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.SceneCapture2D.md#ballowreceivetickeventondedicatedserver)

#### Defined in

[ue/ue.d.ts:13142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13142)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bAllowTickBeforeBeginPlay](ue_ue.SceneCapture2D.md#ballowtickbeforebeginplay)

#### Defined in

[ue/ue.d.ts:13129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13129)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bAlwaysRelevant](ue_ue.SceneCapture2D.md#balwaysrelevant)

#### Defined in

[ue/ue.d.ts:13120](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13120)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bAutoDestroyWhenFinished](ue_ue.SceneCapture2D.md#bautodestroywhenfinished)

#### Defined in

[ue/ue.d.ts:13130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13130)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bBlockInput](ue_ue.SceneCapture2D.md#bblockinput)

#### Defined in

[ue/ue.d.ts:13131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13131)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bCanBeDamaged](ue_ue.SceneCapture2D.md#bcanbedamaged)

#### Defined in

[ue/ue.d.ts:13132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13132)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bCanBeInCluster](ue_ue.SceneCapture2D.md#bcanbeincluster)

#### Defined in

[ue/ue.d.ts:13141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13141)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bCollideWhenPlacing](ue_ue.SceneCapture2D.md#bcollidewhenplacing)

#### Defined in

[ue/ue.d.ts:13133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13133)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bEditable](ue_ue.SceneCapture2D.md#beditable)

#### Defined in

[ue/ue.d.ts:13184](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13184)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bEnableAutoLODGeneration](ue_ue.SceneCapture2D.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:13137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13137)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bExchangedRoles](ue_ue.SceneCapture2D.md#bexchangedroles)

#### Defined in

[ue/ue.d.ts:13123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13123)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bFindCameraComponentWhenViewTarget](ue_ue.SceneCapture2D.md#bfindcameracomponentwhenviewtarget)

#### Defined in

[ue/ue.d.ts:13134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13134)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.SceneCapture2D.md#bgenerateoverlapeventsduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13135)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bHidden](ue_ue.SceneCapture2D.md#bhidden)

#### Defined in

[ue/ue.d.ts:13116](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13116)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bHiddenEd](ue_ue.SceneCapture2D.md#bhiddened)

#### Defined in

[ue/ue.d.ts:13178](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13178)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bHiddenEdLayer](ue_ue.SceneCapture2D.md#bhiddenedlayer)

#### Defined in

[ue/ue.d.ts:13180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13180)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bHiddenEdLevel](ue_ue.SceneCapture2D.md#bhiddenedlevel)

#### Defined in

[ue/ue.d.ts:13181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13181)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bHiddenEdTemporary](ue_ue.SceneCapture2D.md#bhiddenedtemporary)

#### Defined in

[ue/ue.d.ts:13187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13187)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bIgnoresOriginShifting](ue_ue.SceneCapture2D.md#bignoresoriginshifting)

#### Defined in

[ue/ue.d.ts:13136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13136)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bIsEditorOnlyActor](ue_ue.SceneCapture2D.md#biseditoronlyactor)

#### Defined in

[ue/ue.d.ts:13138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13138)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bIsEditorPreviewActor](ue_ue.SceneCapture2D.md#biseditorpreviewactor)

#### Defined in

[ue/ue.d.ts:13179](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13179)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bListedInSceneOutliner](ue_ue.SceneCapture2D.md#blistedinsceneoutliner)

#### Defined in

[ue/ue.d.ts:13185](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13185)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bLockLocation](ue_ue.SceneCapture2D.md#blocklocation)

#### Defined in

[ue/ue.d.ts:13182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13182)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bNetLoadOnClient](ue_ue.SceneCapture2D.md#bnetloadonclient)

#### Defined in

[ue/ue.d.ts:13124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13124)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bNetStartup](ue_ue.SceneCapture2D.md#bnetstartup)

#### Defined in

[ue/ue.d.ts:13118](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13118)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bNetTemporary](ue_ue.SceneCapture2D.md#bnettemporary)

#### Defined in

[ue/ue.d.ts:13117](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13117)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bNetUseOwnerRelevancy](ue_ue.SceneCapture2D.md#bnetuseownerrelevancy)

#### Defined in

[ue/ue.d.ts:13125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13125)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bOnlyRelevantToOwner](ue_ue.SceneCapture2D.md#bonlyrelevanttoowner)

#### Defined in

[ue/ue.d.ts:13119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13119)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bOptimizeBPComponentData](ue_ue.SceneCapture2D.md#boptimizebpcomponentdata)

#### Defined in

[ue/ue.d.ts:13186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13186)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bRelevantForLevelBounds](ue_ue.SceneCapture2D.md#brelevantforlevelbounds)

#### Defined in

[ue/ue.d.ts:13127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13127)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bRelevantForNetworkReplays](ue_ue.SceneCapture2D.md#brelevantfornetworkreplays)

#### Defined in

[ue/ue.d.ts:13126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13126)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bReplayRewindable](ue_ue.SceneCapture2D.md#breplayrewindable)

#### Defined in

[ue/ue.d.ts:13128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13128)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bReplicateMovement](ue_ue.SceneCapture2D.md#breplicatemovement)

#### Defined in

[ue/ue.d.ts:13121](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13121)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bReplicates](ue_ue.SceneCapture2D.md#breplicates)

#### Defined in

[ue/ue.d.ts:13140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13140)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[bTearOff](ue_ue.SceneCapture2D.md#btearoff)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ActorHasTag](ue_ue.SceneCapture2D.md#actorhastag)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[AddComponent](ue_ue.SceneCapture2D.md#addcomponent)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[AddTickPrerequisiteActor](ue_ue.SceneCapture2D.md#addtickprerequisiteactor)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[AddTickPrerequisiteComponent](ue_ue.SceneCapture2D.md#addtickprerequisitecomponent)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[CreateDefaultSubobject](ue_ue.SceneCapture2D.md#createdefaultsubobject)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[DetachRootComponentFromParent](ue_ue.SceneCapture2D.md#detachrootcomponentfromparent)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[DisableInput](ue_ue.SceneCapture2D.md#disableinput)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[EnableInput](ue_ue.SceneCapture2D.md#enableinput)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ExecuteUbergraph](ue_ue.SceneCapture2D.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[FlushNetDormancy](ue_ue.SceneCapture2D.md#flushnetdormancy)

#### Defined in

[ue/ue.d.ts:13214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13214)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ForceNetUpdate](ue_ue.SceneCapture2D.md#forcenetupdate)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetActorBounds](ue_ue.SceneCapture2D.md#getactorbounds)

#### Defined in

[ue/ue.d.ts:13216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13216)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetActorEnableCollision](ue_ue.SceneCapture2D.md#getactorenablecollision)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetActorEyesViewPoint](ue_ue.SceneCapture2D.md#getactoreyesviewpoint)

#### Defined in

[ue/ue.d.ts:13218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13218)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetActorForwardVector](ue_ue.SceneCapture2D.md#getactorforwardvector)

#### Defined in

[ue/ue.d.ts:13219](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13219)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetActorLabel](ue_ue.SceneCapture2D.md#getactorlabel)

#### Defined in

[ue/ue.d.ts:13220](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13220)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetActorRelativeScale3D](ue_ue.SceneCapture2D.md#getactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13221](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13221)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetActorRightVector](ue_ue.SceneCapture2D.md#getactorrightvector)

#### Defined in

[ue/ue.d.ts:13222](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13222)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetActorScale3D](ue_ue.SceneCapture2D.md#getactorscale3d)

#### Defined in

[ue/ue.d.ts:13223](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13223)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetActorTickInterval](ue_ue.SceneCapture2D.md#getactortickinterval)

#### Defined in

[ue/ue.d.ts:13224](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13224)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetActorTimeDilation](ue_ue.SceneCapture2D.md#getactortimedilation)

#### Defined in

[ue/ue.d.ts:13225](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13225)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetActorUpVector](ue_ue.SceneCapture2D.md#getactorupvector)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetAllChildActors](ue_ue.SceneCapture2D.md#getallchildactors)

#### Defined in

[ue/ue.d.ts:13227](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13227)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetAttachParentActor](ue_ue.SceneCapture2D.md#getattachparentactor)

#### Defined in

[ue/ue.d.ts:13229](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13229)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetAttachParentSocketName](ue_ue.SceneCapture2D.md#getattachparentsocketname)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetAttachedActors](ue_ue.SceneCapture2D.md#getattachedactors)

#### Defined in

[ue/ue.d.ts:13228](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13228)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetClass](ue_ue.SceneCapture2D.md#getclass)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetComponentByClass](ue_ue.SceneCapture2D.md#getcomponentbyclass)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetComponentsByInterface](ue_ue.SceneCapture2D.md#getcomponentsbyinterface)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetComponentsByTag](ue_ue.SceneCapture2D.md#getcomponentsbytag)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetDistanceTo](ue_ue.SceneCapture2D.md#getdistanceto)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetDotProductTo](ue_ue.SceneCapture2D.md#getdotproductto)

#### Defined in

[ue/ue.d.ts:13235](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13235)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetFolderPath](ue_ue.SceneCapture2D.md#getfolderpath)

#### Defined in

[ue/ue.d.ts:13236](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13236)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetGameTimeSinceCreation](ue_ue.SceneCapture2D.md#getgametimesincecreation)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetHorizontalDistanceTo](ue_ue.SceneCapture2D.md#gethorizontaldistanceto)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetHorizontalDotProductTo](ue_ue.SceneCapture2D.md#gethorizontaldotproductto)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetInputAxisKeyValue](ue_ue.SceneCapture2D.md#getinputaxiskeyvalue)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetInputAxisValue](ue_ue.SceneCapture2D.md#getinputaxisvalue)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetInputVectorAxisValue](ue_ue.SceneCapture2D.md#getinputvectoraxisvalue)

#### Defined in

[ue/ue.d.ts:13242](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13242)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetInstigator](ue_ue.SceneCapture2D.md#getinstigator)

#### Defined in

[ue/ue.d.ts:13243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13243)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetInstigatorController](ue_ue.SceneCapture2D.md#getinstigatorcontroller)

#### Defined in

[ue/ue.d.ts:13244](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13244)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetLifeSpan](ue_ue.SceneCapture2D.md#getlifespan)

#### Defined in

[ue/ue.d.ts:13245](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13245)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetLocalRole](ue_ue.SceneCapture2D.md#getlocalrole)

#### Defined in

[ue/ue.d.ts:13246](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13246)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetName](ue_ue.SceneCapture2D.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetOuter](ue_ue.SceneCapture2D.md#getouter)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetOverlappingActors](ue_ue.SceneCapture2D.md#getoverlappingactors)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetOverlappingComponents](ue_ue.SceneCapture2D.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:13248](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13248)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetOwner](ue_ue.SceneCapture2D.md#getowner)

#### Defined in

[ue/ue.d.ts:13249](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13249)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetParentActor](ue_ue.SceneCapture2D.md#getparentactor)

#### Defined in

[ue/ue.d.ts:13250](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13250)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetParentComponent](ue_ue.SceneCapture2D.md#getparentcomponent)

#### Defined in

[ue/ue.d.ts:13251](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13251)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetRemoteRole](ue_ue.SceneCapture2D.md#getremoterole)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetSquaredDistanceTo](ue_ue.SceneCapture2D.md#getsquareddistanceto)

#### Defined in

[ue/ue.d.ts:13253](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13253)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetTickableWhenPaused](ue_ue.SceneCapture2D.md#gettickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13254](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13254)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetTransform](ue_ue.SceneCapture2D.md#gettransform)

#### Defined in

[ue/ue.d.ts:13255](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13255)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetVelocity](ue_ue.SceneCapture2D.md#getvelocity)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetVerticalDistanceTo](ue_ue.SceneCapture2D.md#getverticaldistanceto)

#### Defined in

[ue/ue.d.ts:13257](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13257)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[GetWorld](ue_ue.SceneCapture2D.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[HasAuthority](ue_ue.SceneCapture2D.md#hasauthority)

#### Defined in

[ue/ue.d.ts:13258](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13258)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[IsActorBeingDestroyed](ue_ue.SceneCapture2D.md#isactorbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13259](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13259)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[IsActorTickEnabled](ue_ue.SceneCapture2D.md#isactortickenabled)

#### Defined in

[ue/ue.d.ts:13260](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13260)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[IsChildActor](ue_ue.SceneCapture2D.md#ischildactor)

#### Defined in

[ue/ue.d.ts:13261](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13261)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[IsEditable](ue_ue.SceneCapture2D.md#iseditable)

#### Defined in

[ue/ue.d.ts:13262](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13262)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[IsHiddenEd](ue_ue.SceneCapture2D.md#ishiddened)

#### Defined in

[ue/ue.d.ts:13263](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13263)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[IsHiddenEdAtStartup](ue_ue.SceneCapture2D.md#ishiddenedatstartup)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[IsOverlappingActor](ue_ue.SceneCapture2D.md#isoverlappingactor)

#### Defined in

[ue/ue.d.ts:13265](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13265)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[IsSelectable](ue_ue.SceneCapture2D.md#isselectable)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[IsTemporarilyHiddenInEditor](ue_ue.SceneCapture2D.md#istemporarilyhiddenineditor)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_AddActorLocalOffset](ue_ue.SceneCapture2D.md#k2_addactorlocaloffset)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_AddActorLocalRotation](ue_ue.SceneCapture2D.md#k2_addactorlocalrotation)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_AddActorLocalTransform](ue_ue.SceneCapture2D.md#k2_addactorlocaltransform)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_AddActorWorldOffset](ue_ue.SceneCapture2D.md#k2_addactorworldoffset)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_AddActorWorldRotation](ue_ue.SceneCapture2D.md#k2_addactorworldrotation)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_AddActorWorldTransform](ue_ue.SceneCapture2D.md#k2_addactorworldtransform)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_AttachRootComponentTo](ue_ue.SceneCapture2D.md#k2_attachrootcomponentto)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_AttachRootComponentToActor](ue_ue.SceneCapture2D.md#k2_attachrootcomponenttoactor)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_AttachToActor](ue_ue.SceneCapture2D.md#k2_attachtoactor)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_AttachToComponent](ue_ue.SceneCapture2D.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:13277](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13277)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_DestroyActor](ue_ue.SceneCapture2D.md#k2_destroyactor)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_DestroyComponent](ue_ue.SceneCapture2D.md#k2_destroycomponent)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_DetachFromActor](ue_ue.SceneCapture2D.md#k2_detachfromactor)

#### Defined in

[ue/ue.d.ts:13280](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13280)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_GetActorLocation](ue_ue.SceneCapture2D.md#k2_getactorlocation)

#### Defined in

[ue/ue.d.ts:13281](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13281)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_GetActorRotation](ue_ue.SceneCapture2D.md#k2_getactorrotation)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_GetComponentsByClass](ue_ue.SceneCapture2D.md#k2_getcomponentsbyclass)

#### Defined in

[ue/ue.d.ts:13283](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13283)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_GetRootComponent](ue_ue.SceneCapture2D.md#k2_getrootcomponent)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_OnBecomeViewTarget](ue_ue.SceneCapture2D.md#k2_onbecomeviewtarget)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_OnEndViewTarget](ue_ue.SceneCapture2D.md#k2_onendviewtarget)

#### Defined in

[ue/ue.d.ts:13286](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13286)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_OnReset](ue_ue.SceneCapture2D.md#k2_onreset)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_SetActorLocation](ue_ue.SceneCapture2D.md#k2_setactorlocation)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_SetActorLocationAndRotation](ue_ue.SceneCapture2D.md#k2_setactorlocationandrotation)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_SetActorRelativeLocation](ue_ue.SceneCapture2D.md#k2_setactorrelativelocation)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_SetActorRelativeRotation](ue_ue.SceneCapture2D.md#k2_setactorrelativerotation)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_SetActorRelativeTransform](ue_ue.SceneCapture2D.md#k2_setactorrelativetransform)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_SetActorRotation](ue_ue.SceneCapture2D.md#k2_setactorrotation)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_SetActorTransform](ue_ue.SceneCapture2D.md#k2_setactortransform)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[K2_TeleportTo](ue_ue.SceneCapture2D.md#k2_teleportto)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[MakeMIDForMaterial](ue_ue.SceneCapture2D.md#makemidformaterial)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[MakeNoise](ue_ue.SceneCapture2D.md#makenoise)

#### Defined in

[ue/ue.d.ts:13297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13297)

___

### OnInterpToggle

▸ **OnInterpToggle**(`bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

#### Returns

`void`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnInterpToggle](ue_ue.SceneCapture2D.md#oninterptoggle)

#### Defined in

[ue/ue.d.ts:53911](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53911)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnRep_AttachmentReplication](ue_ue.SceneCapture2D.md#onrep_attachmentreplication)

#### Defined in

[ue/ue.d.ts:13298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13298)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnRep_Instigator](ue_ue.SceneCapture2D.md#onrep_instigator)

#### Defined in

[ue/ue.d.ts:13299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13299)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnRep_Owner](ue_ue.SceneCapture2D.md#onrep_owner)

#### Defined in

[ue/ue.d.ts:13300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13300)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnRep_ReplicateMovement](ue_ue.SceneCapture2D.md#onrep_replicatemovement)

#### Defined in

[ue/ue.d.ts:13302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13302)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[OnRep_ReplicatedMovement](ue_ue.SceneCapture2D.md#onrep_replicatedmovement)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[PrestreamTextures](ue_ue.SceneCapture2D.md#prestreamtextures)

#### Defined in

[ue/ue.d.ts:13303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13303)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceiveActorBeginCursorOver](ue_ue.SceneCapture2D.md#receiveactorbegincursorover)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceiveActorBeginOverlap](ue_ue.SceneCapture2D.md#receiveactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13305)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceiveActorEndCursorOver](ue_ue.SceneCapture2D.md#receiveactorendcursorover)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceiveActorEndOverlap](ue_ue.SceneCapture2D.md#receiveactorendoverlap)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceiveActorOnClicked](ue_ue.SceneCapture2D.md#receiveactoronclicked)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceiveActorOnInputTouchBegin](ue_ue.SceneCapture2D.md#receiveactoroninputtouchbegin)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceiveActorOnInputTouchEnd](ue_ue.SceneCapture2D.md#receiveactoroninputtouchend)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceiveActorOnInputTouchEnter](ue_ue.SceneCapture2D.md#receiveactoroninputtouchenter)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceiveActorOnInputTouchLeave](ue_ue.SceneCapture2D.md#receiveactoroninputtouchleave)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceiveActorOnReleased](ue_ue.SceneCapture2D.md#receiveactoronreleased)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceiveAnyDamage](ue_ue.SceneCapture2D.md#receiveanydamage)

#### Defined in

[ue/ue.d.ts:13314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13314)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceiveBeginPlay](ue_ue.SceneCapture2D.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:13315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13315)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceiveDestroyed](ue_ue.SceneCapture2D.md#receivedestroyed)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceiveEndPlay](ue_ue.SceneCapture2D.md#receiveendplay)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceiveHit](ue_ue.SceneCapture2D.md#receivehit)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceivePointDamage](ue_ue.SceneCapture2D.md#receivepointdamage)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceiveRadialDamage](ue_ue.SceneCapture2D.md#receiveradialdamage)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[ReceiveTick](ue_ue.SceneCapture2D.md#receivetick)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[RemoveTickPrerequisiteActor](ue_ue.SceneCapture2D.md#removetickprerequisiteactor)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[RemoveTickPrerequisiteComponent](ue_ue.SceneCapture2D.md#removetickprerequisitecomponent)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SetActorEnableCollision](ue_ue.SceneCapture2D.md#setactorenablecollision)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SetActorHiddenInGame](ue_ue.SceneCapture2D.md#setactorhiddeningame)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SetActorLabel](ue_ue.SceneCapture2D.md#setactorlabel)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SetActorRelativeScale3D](ue_ue.SceneCapture2D.md#setactorrelativescale3d)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SetActorScale3D](ue_ue.SceneCapture2D.md#setactorscale3d)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SetActorTickEnabled](ue_ue.SceneCapture2D.md#setactortickenabled)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SetActorTickInterval](ue_ue.SceneCapture2D.md#setactortickinterval)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SetFolderPath](ue_ue.SceneCapture2D.md#setfolderpath)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SetIsTemporarilyHiddenInEditor](ue_ue.SceneCapture2D.md#setistemporarilyhiddenineditor)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SetLifeSpan](ue_ue.SceneCapture2D.md#setlifespan)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SetNetDormancy](ue_ue.SceneCapture2D.md#setnetdormancy)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SetOwner](ue_ue.SceneCapture2D.md#setowner)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SetReplicateMovement](ue_ue.SceneCapture2D.md#setreplicatemovement)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SetReplicates](ue_ue.SceneCapture2D.md#setreplicates)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SetTickGroup](ue_ue.SceneCapture2D.md#settickgroup)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SetTickableWhenPaused](ue_ue.SceneCapture2D.md#settickablewhenpaused)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[SnapRootComponentTo](ue_ue.SceneCapture2D.md#snaprootcomponentto)

#### Defined in

[ue/ue.d.ts:13340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13340)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[TearOff](ue_ue.SceneCapture2D.md#tearoff)

#### Defined in

[ue/ue.d.ts:13341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13341)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCapture2D](ue_ue.SceneCapture2D.md).[UserConstructionScript](ue_ue.SceneCapture2D.md#userconstructionscript)

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

[SceneCapture2D](ue_ue.SceneCapture2D.md).[WasRecentlyRendered](ue_ue.SceneCapture2D.md#wasrecentlyrendered)

#### Defined in

[ue/ue.d.ts:13343](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13343)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`OculusMR_CastingCameraActor`](ue_ue.OculusMR_CastingCameraActor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`OculusMR_CastingCameraActor`](ue_ue.OculusMR_CastingCameraActor.md)

#### Overrides

[SceneCapture2D](ue_ue.SceneCapture2D.md).[Find](ue_ue.SceneCapture2D.md#find)

#### Defined in

[ue/ue.d.ts:54049](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54049)

___

### Load

▸ `Static` **Load**(`InName`): [`OculusMR_CastingCameraActor`](ue_ue.OculusMR_CastingCameraActor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`OculusMR_CastingCameraActor`](ue_ue.OculusMR_CastingCameraActor.md)

#### Overrides

[SceneCapture2D](ue_ue.SceneCapture2D.md).[Load](ue_ue.SceneCapture2D.md#load)

#### Defined in

[ue/ue.d.ts:54050](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54050)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SceneCapture2D](ue_ue.SceneCapture2D.md).[StaticClass](ue_ue.SceneCapture2D.md#staticclass)

#### Defined in

[ue/ue.d.ts:54048](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L54048)
