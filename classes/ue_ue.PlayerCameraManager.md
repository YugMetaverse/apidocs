[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PlayerCameraManager

# Class: PlayerCameraManager

[ue/ue](../modules/ue_ue.md).PlayerCameraManager

## Hierarchy

- [`Actor`](ue_ue.Actor.md)

  ↳ **`PlayerCameraManager`**

## Table of contents

### Constructors

- [constructor](ue_ue.PlayerCameraManager.md#constructor)

### Properties

- [ActiveAnims](ue_ue.PlayerCameraManager.md#activeanims)
- [ActorLabel](ue_ue.PlayerCameraManager.md#actorlabel)
- [AnimCameraActor](ue_ue.PlayerCameraManager.md#animcameraactor)
- [AnimInstPool](ue_ue.PlayerCameraManager.md#animinstpool)
- [AttachmentReplication](ue_ue.PlayerCameraManager.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.PlayerCameraManager.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.PlayerCameraManager.md#blueprintcreatedcomponents)
- [CachedCameraShakeMod](ue_ue.PlayerCameraManager.md#cachedcamerashakemod)
- [CameraCache](ue_ue.PlayerCameraManager.md#cameracache)
- [CameraCachePrivate](ue_ue.PlayerCameraManager.md#cameracacheprivate)
- [CameraLensEffects](ue_ue.PlayerCameraManager.md#cameralenseffects)
- [Children](ue_ue.PlayerCameraManager.md#children)
- [ControllingMatineeActors](ue_ue.PlayerCameraManager.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.PlayerCameraManager.md#customtimedilation)
- [DefaultAspectRatio](ue_ue.PlayerCameraManager.md#defaultaspectratio)
- [DefaultFOV](ue_ue.PlayerCameraManager.md#defaultfov)
- [DefaultModifiers](ue_ue.PlayerCameraManager.md#defaultmodifiers)
- [DefaultOrthoWidth](ue_ue.PlayerCameraManager.md#defaultorthowidth)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.PlayerCameraManager.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.PlayerCameraManager.md#folderpath)
- [FreeAnims](ue_ue.PlayerCameraManager.md#freeanims)
- [FreeCamDistance](ue_ue.PlayerCameraManager.md#freecamdistance)
- [FreeCamOffset](ue_ue.PlayerCameraManager.md#freecamoffset)
- [GroupActor](ue_ue.PlayerCameraManager.md#groupactor)
- [HiddenEditorViews](ue_ue.PlayerCameraManager.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.PlayerCameraManager.md#initiallifespan)
- [InputComponent](ue_ue.PlayerCameraManager.md#inputcomponent)
- [InputPriority](ue_ue.PlayerCameraManager.md#inputpriority)
- [InstanceComponents](ue_ue.PlayerCameraManager.md#instancecomponents)
- [Instigator](ue_ue.PlayerCameraManager.md#instigator)
- [LastFrameCameraCache](ue_ue.PlayerCameraManager.md#lastframecameracache)
- [LastFrameCameraCachePrivate](ue_ue.PlayerCameraManager.md#lastframecameracacheprivate)
- [Layers](ue_ue.PlayerCameraManager.md#layers)
- [MinNetUpdateFrequency](ue_ue.PlayerCameraManager.md#minnetupdatefrequency)
- [ModifierList](ue_ue.PlayerCameraManager.md#modifierlist)
- [NetCullDistanceSquared](ue_ue.PlayerCameraManager.md#netculldistancesquared)
- [NetDormancy](ue_ue.PlayerCameraManager.md#netdormancy)
- [NetDriverName](ue_ue.PlayerCameraManager.md#netdrivername)
- [NetPriority](ue_ue.PlayerCameraManager.md#netpriority)
- [NetTag](ue_ue.PlayerCameraManager.md#nettag)
- [NetUpdateFrequency](ue_ue.PlayerCameraManager.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.PlayerCameraManager.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.PlayerCameraManager.md#onactorendoverlap)
- [OnActorHit](ue_ue.PlayerCameraManager.md#onactorhit)
- [OnBeginCursorOver](ue_ue.PlayerCameraManager.md#onbegincursorover)
- [OnClicked](ue_ue.PlayerCameraManager.md#onclicked)
- [OnDestroyed](ue_ue.PlayerCameraManager.md#ondestroyed)
- [OnEndCursorOver](ue_ue.PlayerCameraManager.md#onendcursorover)
- [OnEndPlay](ue_ue.PlayerCameraManager.md#onendplay)
- [OnInputTouchBegin](ue_ue.PlayerCameraManager.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.PlayerCameraManager.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.PlayerCameraManager.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.PlayerCameraManager.md#oninputtouchleave)
- [OnReleased](ue_ue.PlayerCameraManager.md#onreleased)
- [OnTakeAnyDamage](ue_ue.PlayerCameraManager.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.PlayerCameraManager.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.PlayerCameraManager.md#ontakeradialdamage)
- [Owner](ue_ue.PlayerCameraManager.md#owner)
- [PCOwner](ue_ue.PlayerCameraManager.md#pcowner)
- [ParentComponent](ue_ue.PlayerCameraManager.md#parentcomponent)
- [ParentComponentActor](ue_ue.PlayerCameraManager.md#parentcomponentactor)
- [PendingViewTarget](ue_ue.PlayerCameraManager.md#pendingviewtarget)
- [PivotOffset](ue_ue.PlayerCameraManager.md#pivotoffset)
- [PostProcessBlendCache](ue_ue.PlayerCameraManager.md#postprocessblendcache)
- [PrimaryActorTick](ue_ue.PlayerCameraManager.md#primaryactortick)
- [RemoteRole](ue_ue.PlayerCameraManager.md#remoterole)
- [ReplicatedMovement](ue_ue.PlayerCameraManager.md#replicatedmovement)
- [Role](ue_ue.PlayerCameraManager.md#role)
- [RootComponent](ue_ue.PlayerCameraManager.md#rootcomponent)
- [ServerUpdateCameraTimeout](ue_ue.PlayerCameraManager.md#serverupdatecameratimeout)
- [SpawnCollisionHandlingMethod](ue_ue.PlayerCameraManager.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.PlayerCameraManager.md#spritescale)
- [Tags](ue_ue.PlayerCameraManager.md#tags)
- [TransformComponent](ue_ue.PlayerCameraManager.md#transformcomponent)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.PlayerCameraManager.md#updateoverlapsmethodduringlevelstreaming)
- [ViewPitchMax](ue_ue.PlayerCameraManager.md#viewpitchmax)
- [ViewPitchMin](ue_ue.PlayerCameraManager.md#viewpitchmin)
- [ViewRollMax](ue_ue.PlayerCameraManager.md#viewrollmax)
- [ViewRollMin](ue_ue.PlayerCameraManager.md#viewrollmin)
- [ViewTarget](ue_ue.PlayerCameraManager.md#viewtarget)
- [ViewTargetOffset](ue_ue.PlayerCameraManager.md#viewtargetoffset)
- [ViewYawMax](ue_ue.PlayerCameraManager.md#viewyawmax)
- [ViewYawMin](ue_ue.PlayerCameraManager.md#viewyawmin)
- [\_\_tid\_Actor\_\_](ue_ue.PlayerCameraManager.md#__tid_actor__)
- [\_\_tid\_Object\_\_](ue_ue.PlayerCameraManager.md#__tid_object__)
- [\_\_tid\_PlayerCameraManager\_\_](ue_ue.PlayerCameraManager.md#__tid_playercameramanager__)
- [bActorEnableCollision](ue_ue.PlayerCameraManager.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.PlayerCameraManager.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.PlayerCameraManager.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.PlayerCameraManager.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.PlayerCameraManager.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.PlayerCameraManager.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.PlayerCameraManager.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.PlayerCameraManager.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.PlayerCameraManager.md#bblockinput)
- [bCanBeDamaged](ue_ue.PlayerCameraManager.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.PlayerCameraManager.md#bcanbeincluster)
- [bClientSimulatingViewTarget](ue_ue.PlayerCameraManager.md#bclientsimulatingviewtarget)
- [bCollideWhenPlacing](ue_ue.PlayerCameraManager.md#bcollidewhenplacing)
- [bDefaultConstrainAspectRatio](ue_ue.PlayerCameraManager.md#bdefaultconstrainaspectratio)
- [bEditable](ue_ue.PlayerCameraManager.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.PlayerCameraManager.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.PlayerCameraManager.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.PlayerCameraManager.md#bfindcameracomponentwhenviewtarget)
- [bGameCameraCutThisFrame](ue_ue.PlayerCameraManager.md#bgamecameracutthisframe)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.PlayerCameraManager.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.PlayerCameraManager.md#bhidden)
- [bHiddenEd](ue_ue.PlayerCameraManager.md#bhiddened)
- [bHiddenEdLayer](ue_ue.PlayerCameraManager.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.PlayerCameraManager.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.PlayerCameraManager.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.PlayerCameraManager.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.PlayerCameraManager.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.PlayerCameraManager.md#biseditorpreviewactor)
- [bIsOrthographic](ue_ue.PlayerCameraManager.md#bisorthographic)
- [bListedInSceneOutliner](ue_ue.PlayerCameraManager.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.PlayerCameraManager.md#blocklocation)
- [bNetLoadOnClient](ue_ue.PlayerCameraManager.md#bnetloadonclient)
- [bNetStartup](ue_ue.PlayerCameraManager.md#bnetstartup)
- [bNetTemporary](ue_ue.PlayerCameraManager.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.PlayerCameraManager.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.PlayerCameraManager.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.PlayerCameraManager.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.PlayerCameraManager.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.PlayerCameraManager.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.PlayerCameraManager.md#breplayrewindable)
- [bReplicateMovement](ue_ue.PlayerCameraManager.md#breplicatemovement)
- [bReplicates](ue_ue.PlayerCameraManager.md#breplicates)
- [bTearOff](ue_ue.PlayerCameraManager.md#btearoff)
- [bUseClientSideCameraUpdates](ue_ue.PlayerCameraManager.md#buseclientsidecameraupdates)

### Methods

- [ActorHasTag](ue_ue.PlayerCameraManager.md#actorhastag)
- [AddCameraLensEffect](ue_ue.PlayerCameraManager.md#addcameralenseffect)
- [AddComponent](ue_ue.PlayerCameraManager.md#addcomponent)
- [AddNewCameraModifier](ue_ue.PlayerCameraManager.md#addnewcameramodifier)
- [AddTickPrerequisiteActor](ue_ue.PlayerCameraManager.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PlayerCameraManager.md#addtickprerequisitecomponent)
- [BlueprintUpdateCamera](ue_ue.PlayerCameraManager.md#blueprintupdatecamera)
- [ClearCameraLensEffects](ue_ue.PlayerCameraManager.md#clearcameralenseffects)
- [CreateDefaultSubobject](ue_ue.PlayerCameraManager.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.PlayerCameraManager.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.PlayerCameraManager.md#disableinput)
- [EnableInput](ue_ue.PlayerCameraManager.md#enableinput)
- [ExecuteUbergraph](ue_ue.PlayerCameraManager.md#executeubergraph)
- [FindCameraModifierByClass](ue_ue.PlayerCameraManager.md#findcameramodifierbyclass)
- [FlushNetDormancy](ue_ue.PlayerCameraManager.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.PlayerCameraManager.md#forcenetupdate)
- [GetActorBounds](ue_ue.PlayerCameraManager.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.PlayerCameraManager.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.PlayerCameraManager.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.PlayerCameraManager.md#getactorforwardvector)
- [GetActorLabel](ue_ue.PlayerCameraManager.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.PlayerCameraManager.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.PlayerCameraManager.md#getactorrightvector)
- [GetActorScale3D](ue_ue.PlayerCameraManager.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.PlayerCameraManager.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.PlayerCameraManager.md#getactortimedilation)
- [GetActorUpVector](ue_ue.PlayerCameraManager.md#getactorupvector)
- [GetAllChildActors](ue_ue.PlayerCameraManager.md#getallchildactors)
- [GetAttachParentActor](ue_ue.PlayerCameraManager.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.PlayerCameraManager.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.PlayerCameraManager.md#getattachedactors)
- [GetCameraLocation](ue_ue.PlayerCameraManager.md#getcameralocation)
- [GetCameraRotation](ue_ue.PlayerCameraManager.md#getcamerarotation)
- [GetClass](ue_ue.PlayerCameraManager.md#getclass)
- [GetComponentByClass](ue_ue.PlayerCameraManager.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.PlayerCameraManager.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.PlayerCameraManager.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.PlayerCameraManager.md#getdistanceto)
- [GetDotProductTo](ue_ue.PlayerCameraManager.md#getdotproductto)
- [GetFOVAngle](ue_ue.PlayerCameraManager.md#getfovangle)
- [GetFolderPath](ue_ue.PlayerCameraManager.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.PlayerCameraManager.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.PlayerCameraManager.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.PlayerCameraManager.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.PlayerCameraManager.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.PlayerCameraManager.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.PlayerCameraManager.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.PlayerCameraManager.md#getinstigator)
- [GetInstigatorController](ue_ue.PlayerCameraManager.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.PlayerCameraManager.md#getlifespan)
- [GetLocalRole](ue_ue.PlayerCameraManager.md#getlocalrole)
- [GetName](ue_ue.PlayerCameraManager.md#getname)
- [GetOuter](ue_ue.PlayerCameraManager.md#getouter)
- [GetOverlappingActors](ue_ue.PlayerCameraManager.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.PlayerCameraManager.md#getoverlappingcomponents)
- [GetOwner](ue_ue.PlayerCameraManager.md#getowner)
- [GetOwningPlayerController](ue_ue.PlayerCameraManager.md#getowningplayercontroller)
- [GetParentActor](ue_ue.PlayerCameraManager.md#getparentactor)
- [GetParentComponent](ue_ue.PlayerCameraManager.md#getparentcomponent)
- [GetRemoteRole](ue_ue.PlayerCameraManager.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.PlayerCameraManager.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.PlayerCameraManager.md#gettickablewhenpaused)
- [GetTransform](ue_ue.PlayerCameraManager.md#gettransform)
- [GetVelocity](ue_ue.PlayerCameraManager.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.PlayerCameraManager.md#getverticaldistanceto)
- [GetWorld](ue_ue.PlayerCameraManager.md#getworld)
- [HasAuthority](ue_ue.PlayerCameraManager.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.PlayerCameraManager.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.PlayerCameraManager.md#isactortickenabled)
- [IsChildActor](ue_ue.PlayerCameraManager.md#ischildactor)
- [IsEditable](ue_ue.PlayerCameraManager.md#iseditable)
- [IsHiddenEd](ue_ue.PlayerCameraManager.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.PlayerCameraManager.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.PlayerCameraManager.md#isoverlappingactor)
- [IsSelectable](ue_ue.PlayerCameraManager.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.PlayerCameraManager.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.PlayerCameraManager.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.PlayerCameraManager.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.PlayerCameraManager.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.PlayerCameraManager.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.PlayerCameraManager.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.PlayerCameraManager.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.PlayerCameraManager.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.PlayerCameraManager.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.PlayerCameraManager.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.PlayerCameraManager.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.PlayerCameraManager.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.PlayerCameraManager.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.PlayerCameraManager.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.PlayerCameraManager.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.PlayerCameraManager.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.PlayerCameraManager.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.PlayerCameraManager.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.PlayerCameraManager.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.PlayerCameraManager.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.PlayerCameraManager.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.PlayerCameraManager.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.PlayerCameraManager.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.PlayerCameraManager.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.PlayerCameraManager.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.PlayerCameraManager.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.PlayerCameraManager.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.PlayerCameraManager.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.PlayerCameraManager.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.PlayerCameraManager.md#makemidformaterial)
- [MakeNoise](ue_ue.PlayerCameraManager.md#makenoise)
- [OnPhotographyMultiPartCaptureEnd](ue_ue.PlayerCameraManager.md#onphotographymultipartcaptureend)
- [OnPhotographyMultiPartCaptureStart](ue_ue.PlayerCameraManager.md#onphotographymultipartcapturestart)
- [OnPhotographySessionEnd](ue_ue.PlayerCameraManager.md#onphotographysessionend)
- [OnPhotographySessionStart](ue_ue.PlayerCameraManager.md#onphotographysessionstart)
- [OnRep\_AttachmentReplication](ue_ue.PlayerCameraManager.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.PlayerCameraManager.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.PlayerCameraManager.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.PlayerCameraManager.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.PlayerCameraManager.md#onrep_replicatedmovement)
- [PhotographyCameraModify](ue_ue.PlayerCameraManager.md#photographycameramodify)
- [PlayCameraAnim](ue_ue.PlayerCameraManager.md#playcameraanim)
- [PlayCameraShake](ue_ue.PlayerCameraManager.md#playcamerashake)
- [PrestreamTextures](ue_ue.PlayerCameraManager.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.PlayerCameraManager.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.PlayerCameraManager.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.PlayerCameraManager.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.PlayerCameraManager.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.PlayerCameraManager.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.PlayerCameraManager.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.PlayerCameraManager.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.PlayerCameraManager.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.PlayerCameraManager.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.PlayerCameraManager.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.PlayerCameraManager.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.PlayerCameraManager.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.PlayerCameraManager.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.PlayerCameraManager.md#receiveendplay)
- [ReceiveHit](ue_ue.PlayerCameraManager.md#receivehit)
- [ReceivePointDamage](ue_ue.PlayerCameraManager.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.PlayerCameraManager.md#receiveradialdamage)
- [ReceiveTick](ue_ue.PlayerCameraManager.md#receivetick)
- [RemoveCameraLensEffect](ue_ue.PlayerCameraManager.md#removecameralenseffect)
- [RemoveCameraModifier](ue_ue.PlayerCameraManager.md#removecameramodifier)
- [RemoveTickPrerequisiteActor](ue_ue.PlayerCameraManager.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PlayerCameraManager.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.PlayerCameraManager.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.PlayerCameraManager.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.PlayerCameraManager.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.PlayerCameraManager.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.PlayerCameraManager.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.PlayerCameraManager.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.PlayerCameraManager.md#setactortickinterval)
- [SetFolderPath](ue_ue.PlayerCameraManager.md#setfolderpath)
- [SetGameCameraCutThisFrame](ue_ue.PlayerCameraManager.md#setgamecameracutthisframe)
- [SetIsTemporarilyHiddenInEditor](ue_ue.PlayerCameraManager.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.PlayerCameraManager.md#setlifespan)
- [SetManualCameraFade](ue_ue.PlayerCameraManager.md#setmanualcamerafade)
- [SetNetDormancy](ue_ue.PlayerCameraManager.md#setnetdormancy)
- [SetOwner](ue_ue.PlayerCameraManager.md#setowner)
- [SetReplicateMovement](ue_ue.PlayerCameraManager.md#setreplicatemovement)
- [SetReplicates](ue_ue.PlayerCameraManager.md#setreplicates)
- [SetTickGroup](ue_ue.PlayerCameraManager.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PlayerCameraManager.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.PlayerCameraManager.md#snaprootcomponentto)
- [StartCameraFade](ue_ue.PlayerCameraManager.md#startcamerafade)
- [StopAllCameraAnims](ue_ue.PlayerCameraManager.md#stopallcameraanims)
- [StopAllCameraShakes](ue_ue.PlayerCameraManager.md#stopallcamerashakes)
- [StopAllInstancesOfCameraAnim](ue_ue.PlayerCameraManager.md#stopallinstancesofcameraanim)
- [StopAllInstancesOfCameraShake](ue_ue.PlayerCameraManager.md#stopallinstancesofcamerashake)
- [StopCameraAnimInst](ue_ue.PlayerCameraManager.md#stopcameraaniminst)
- [StopCameraFade](ue_ue.PlayerCameraManager.md#stopcamerafade)
- [StopCameraShake](ue_ue.PlayerCameraManager.md#stopcamerashake)
- [TearOff](ue_ue.PlayerCameraManager.md#tearoff)
- [UserConstructionScript](ue_ue.PlayerCameraManager.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.PlayerCameraManager.md#wasrecentlyrendered)
- [Find](ue_ue.PlayerCameraManager.md#find)
- [Load](ue_ue.PlayerCameraManager.md#load)
- [StaticClass](ue_ue.PlayerCameraManager.md#staticclass)

## Constructors

### constructor

• **new PlayerCameraManager**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Actor](ue_ue.Actor.md).[constructor](ue_ue.Actor.md#constructor)

## Properties

### ActiveAnims

• **ActiveAnims**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CameraAnimInst`](ue_ue.CameraAnimInst.md)\>

___

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[Actor](ue_ue.Actor.md).[ActorLabel](ue_ue.Actor.md#actorlabel)

___

### AnimCameraActor

• **AnimCameraActor**: [`CameraActor`](ue_ue.CameraActor.md)

___

### AnimInstPool

• **AnimInstPool**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`CameraAnimInst`](ue_ue.CameraAnimInst.md)\>

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[AttachmentReplication](ue_ue.Actor.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[AutoReceiveInput](ue_ue.Actor.md#autoreceiveinput)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Actor](ue_ue.Actor.md).[BlueprintCreatedComponents](ue_ue.Actor.md#blueprintcreatedcomponents)

___

### CachedCameraShakeMod

• **CachedCameraShakeMod**: [`CameraModifier_CameraShake`](ue_ue.CameraModifier_CameraShake.md)

___

### CameraCache

• **CameraCache**: [`CameraCacheEntry`](ue_ue.CameraCacheEntry.md)

___

### CameraCachePrivate

• **CameraCachePrivate**: [`CameraCacheEntry`](ue_ue.CameraCacheEntry.md)

___

### CameraLensEffects

• **CameraLensEffects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EmitterCameraLensEffectBase`](ue_ue.EmitterCameraLensEffectBase.md)\>

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Actor](ue_ue.Actor.md).[Children](ue_ue.Actor.md#children)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[Actor](ue_ue.Actor.md).[ControllingMatineeActors](ue_ue.Actor.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[CustomTimeDilation](ue_ue.Actor.md#customtimedilation)

___

### DefaultAspectRatio

• **DefaultAspectRatio**: `number`

___

### DefaultFOV

• **DefaultFOV**: `number`

___

### DefaultModifiers

• **DefaultModifiers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Class`](ue_ue.Class.md)\>

___

### DefaultOrthoWidth

• **DefaultOrthoWidth**: `number`

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.Actor.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[Actor](ue_ue.Actor.md).[FolderPath](ue_ue.Actor.md#folderpath)

___

### FreeAnims

• **FreeAnims**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CameraAnimInst`](ue_ue.CameraAnimInst.md)\>

___

### FreeCamDistance

• **FreeCamDistance**: `number`

___

### FreeCamOffset

• **FreeCamOffset**: [`Vector`](ue_ue_s.Vector.md)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GroupActor](ue_ue.Actor.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[Actor](ue_ue.Actor.md).[HiddenEditorViews](ue_ue.Actor.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[InitialLifeSpan](ue_ue.Actor.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[InputComponent](ue_ue.Actor.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[InputPriority](ue_ue.Actor.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Actor](ue_ue.Actor.md).[InstanceComponents](ue_ue.Actor.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[Instigator](ue_ue.Actor.md#instigator)

___

### LastFrameCameraCache

• **LastFrameCameraCache**: [`CameraCacheEntry`](ue_ue.CameraCacheEntry.md)

___

### LastFrameCameraCachePrivate

• **LastFrameCameraCachePrivate**: [`CameraCacheEntry`](ue_ue.CameraCacheEntry.md)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[Layers](ue_ue.Actor.md#layers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[MinNetUpdateFrequency](ue_ue.Actor.md#minnetupdatefrequency)

___

### ModifierList

• **ModifierList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CameraModifier`](ue_ue.CameraModifier.md)\>

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[NetCullDistanceSquared](ue_ue.Actor.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[NetDormancy](ue_ue.Actor.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[Actor](ue_ue.Actor.md).[NetDriverName](ue_ue.Actor.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[NetPriority](ue_ue.Actor.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[NetTag](ue_ue.Actor.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[NetUpdateFrequency](ue_ue.Actor.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnActorBeginOverlap](ue_ue.Actor.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnActorEndOverlap](ue_ue.Actor.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnActorHit](ue_ue.Actor.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnBeginCursorOver](ue_ue.Actor.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnClicked](ue_ue.Actor.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnDestroyed](ue_ue.Actor.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnEndCursorOver](ue_ue.Actor.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnEndPlay](ue_ue.Actor.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnInputTouchBegin](ue_ue.Actor.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnInputTouchEnd](ue_ue.Actor.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnInputTouchEnter](ue_ue.Actor.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnInputTouchLeave](ue_ue.Actor.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnReleased](ue_ue.Actor.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnTakeAnyDamage](ue_ue.Actor.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnTakePointDamage](ue_ue.Actor.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[OnTakeRadialDamage](ue_ue.Actor.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[Owner](ue_ue.Actor.md#owner)

___

### PCOwner

• **PCOwner**: [`PlayerController`](ue_ue.PlayerController.md)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[Actor](ue_ue.Actor.md).[ParentComponent](ue_ue.Actor.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Actor](ue_ue.Actor.md).[ParentComponentActor](ue_ue.Actor.md#parentcomponentactor)

___

### PendingViewTarget

• **PendingViewTarget**: [`TViewTarget`](ue_ue.TViewTarget.md)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[PivotOffset](ue_ue.Actor.md#pivotoffset)

___

### PostProcessBlendCache

• **PostProcessBlendCache**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PostProcessSettings`](ue_ue.PostProcessSettings.md)\>

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[PrimaryActorTick](ue_ue.Actor.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[RemoteRole](ue_ue.Actor.md#remoterole)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[ReplicatedMovement](ue_ue.Actor.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[Role](ue_ue.Actor.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[RootComponent](ue_ue.Actor.md#rootcomponent)

___

### ServerUpdateCameraTimeout

• **ServerUpdateCameraTimeout**: `number`

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[SpawnCollisionHandlingMethod](ue_ue.Actor.md#spawncollisionhandlingmethod)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[Actor](ue_ue.Actor.md).[SpriteScale](ue_ue.Actor.md#spritescale)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Actor](ue_ue.Actor.md).[Tags](ue_ue.Actor.md#tags)

___

### TransformComponent

• **TransformComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.Actor.md#updateoverlapsmethodduringlevelstreaming)

___

### ViewPitchMax

• **ViewPitchMax**: `number`

___

### ViewPitchMin

• **ViewPitchMin**: `number`

___

### ViewRollMax

• **ViewRollMax**: `number`

___

### ViewRollMin

• **ViewRollMin**: `number`

___

### ViewTarget

• **ViewTarget**: [`TViewTarget`](ue_ue.TViewTarget.md)

___

### ViewTargetOffset

• **ViewTargetOffset**: [`Vector`](ue_ue_s.Vector.md)

___

### ViewYawMax

• **ViewYawMax**: `number`

___

### ViewYawMin

• **ViewYawMin**: `number`

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[__tid_Actor__](ue_ue.Actor.md#__tid_actor__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[__tid_Object__](ue_ue.Actor.md#__tid_object__)

___

### \_\_tid\_PlayerCameraManager\_\_

• **\_\_tid\_PlayerCameraManager\_\_**: `boolean`

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bActorEnableCollision](ue_ue.Actor.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bActorIsBeingDestroyed](ue_ue.Actor.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bActorLabelEditable](ue_ue.Actor.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bActorSeamlessTraveled](ue_ue.Actor.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.Actor.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bAllowTickBeforeBeginPlay](ue_ue.Actor.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bAlwaysRelevant](ue_ue.Actor.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bAutoDestroyWhenFinished](ue_ue.Actor.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bBlockInput](ue_ue.Actor.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bCanBeDamaged](ue_ue.Actor.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bCanBeInCluster](ue_ue.Actor.md#bcanbeincluster)

___

### bClientSimulatingViewTarget

• **bClientSimulatingViewTarget**: `boolean`

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bCollideWhenPlacing](ue_ue.Actor.md#bcollidewhenplacing)

___

### bDefaultConstrainAspectRatio

• **bDefaultConstrainAspectRatio**: `boolean`

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bEditable](ue_ue.Actor.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bEnableAutoLODGeneration](ue_ue.Actor.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bExchangedRoles](ue_ue.Actor.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bFindCameraComponentWhenViewTarget](ue_ue.Actor.md#bfindcameracomponentwhenviewtarget)

___

### bGameCameraCutThisFrame

• **bGameCameraCutThisFrame**: `boolean`

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.Actor.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bHidden](ue_ue.Actor.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bHiddenEd](ue_ue.Actor.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bHiddenEdLayer](ue_ue.Actor.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bHiddenEdLevel](ue_ue.Actor.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bHiddenEdTemporary](ue_ue.Actor.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bIgnoresOriginShifting](ue_ue.Actor.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bIsEditorOnlyActor](ue_ue.Actor.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bIsEditorPreviewActor](ue_ue.Actor.md#biseditorpreviewactor)

___

### bIsOrthographic

• **bIsOrthographic**: `boolean`

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bListedInSceneOutliner](ue_ue.Actor.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bLockLocation](ue_ue.Actor.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bNetLoadOnClient](ue_ue.Actor.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bNetStartup](ue_ue.Actor.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bNetTemporary](ue_ue.Actor.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bNetUseOwnerRelevancy](ue_ue.Actor.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bOnlyRelevantToOwner](ue_ue.Actor.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bOptimizeBPComponentData](ue_ue.Actor.md#boptimizebpcomponentdata)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bRelevantForLevelBounds](ue_ue.Actor.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bRelevantForNetworkReplays](ue_ue.Actor.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bReplayRewindable](ue_ue.Actor.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bReplicateMovement](ue_ue.Actor.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bReplicates](ue_ue.Actor.md#breplicates)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[bTearOff](ue_ue.Actor.md#btearoff)

___

### bUseClientSideCameraUpdates

• **bUseClientSideCameraUpdates**: `boolean`

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

[Actor](ue_ue.Actor.md).[ActorHasTag](ue_ue.Actor.md#actorhastag)

___

### AddCameraLensEffect

▸ **AddCameraLensEffect**(`LensEffectEmitterClass`): [`EmitterCameraLensEffectBase`](ue_ue.EmitterCameraLensEffectBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `LensEffectEmitterClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`EmitterCameraLensEffectBase`](ue_ue.EmitterCameraLensEffectBase.md)

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

[Actor](ue_ue.Actor.md).[AddComponent](ue_ue.Actor.md#addcomponent)

___

### AddNewCameraModifier

▸ **AddNewCameraModifier**(`ModifierClass`): [`CameraModifier`](ue_ue.CameraModifier.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ModifierClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`CameraModifier`](ue_ue.CameraModifier.md)

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

[Actor](ue_ue.Actor.md).[AddTickPrerequisiteActor](ue_ue.Actor.md#addtickprerequisiteactor)

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

[Actor](ue_ue.Actor.md).[AddTickPrerequisiteComponent](ue_ue.Actor.md#addtickprerequisitecomponent)

___

### BlueprintUpdateCamera

▸ **BlueprintUpdateCamera**(`CameraTarget`, `NewCameraLocation`, `NewCameraRotation`, `NewCameraFOV`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `CameraTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `NewCameraLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `NewCameraRotation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |
| `NewCameraFOV` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`boolean`

___

### ClearCameraLensEffects

▸ **ClearCameraLensEffects**(): `void`

#### Returns

`void`

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

[Actor](ue_ue.Actor.md).[CreateDefaultSubobject](ue_ue.Actor.md#createdefaultsubobject)

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

[Actor](ue_ue.Actor.md).[DetachRootComponentFromParent](ue_ue.Actor.md#detachrootcomponentfromparent)

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

[Actor](ue_ue.Actor.md).[DisableInput](ue_ue.Actor.md#disableinput)

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

[Actor](ue_ue.Actor.md).[EnableInput](ue_ue.Actor.md#enableinput)

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

[Actor](ue_ue.Actor.md).[ExecuteUbergraph](ue_ue.Actor.md#executeubergraph)

___

### FindCameraModifierByClass

▸ **FindCameraModifierByClass**(`ModifierClass`): [`CameraModifier`](ue_ue.CameraModifier.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ModifierClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`CameraModifier`](ue_ue.CameraModifier.md)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[FlushNetDormancy](ue_ue.Actor.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[ForceNetUpdate](ue_ue.Actor.md#forcenetupdate)

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

[Actor](ue_ue.Actor.md).[GetActorBounds](ue_ue.Actor.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorEnableCollision](ue_ue.Actor.md#getactorenablecollision)

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

[Actor](ue_ue.Actor.md).[GetActorEyesViewPoint](ue_ue.Actor.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorForwardVector](ue_ue.Actor.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorLabel](ue_ue.Actor.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorRelativeScale3D](ue_ue.Actor.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorRightVector](ue_ue.Actor.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorScale3D](ue_ue.Actor.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorTickInterval](ue_ue.Actor.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorTimeDilation](ue_ue.Actor.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetActorUpVector](ue_ue.Actor.md#getactorupvector)

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

[Actor](ue_ue.Actor.md).[GetAllChildActors](ue_ue.Actor.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetAttachParentActor](ue_ue.Actor.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetAttachParentSocketName](ue_ue.Actor.md#getattachparentsocketname)

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

[Actor](ue_ue.Actor.md).[GetAttachedActors](ue_ue.Actor.md#getattachedactors)

___

### GetCameraLocation

▸ **GetCameraLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetCameraRotation

▸ **GetCameraRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetClass](ue_ue.Actor.md#getclass)

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

[Actor](ue_ue.Actor.md).[GetComponentByClass](ue_ue.Actor.md#getcomponentbyclass)

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

[Actor](ue_ue.Actor.md).[GetComponentsByInterface](ue_ue.Actor.md#getcomponentsbyinterface)

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

[Actor](ue_ue.Actor.md).[GetComponentsByTag](ue_ue.Actor.md#getcomponentsbytag)

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

[Actor](ue_ue.Actor.md).[GetDistanceTo](ue_ue.Actor.md#getdistanceto)

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

[Actor](ue_ue.Actor.md).[GetDotProductTo](ue_ue.Actor.md#getdotproductto)

___

### GetFOVAngle

▸ **GetFOVAngle**(): `number`

#### Returns

`number`

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetFolderPath](ue_ue.Actor.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetGameTimeSinceCreation](ue_ue.Actor.md#getgametimesincecreation)

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

[Actor](ue_ue.Actor.md).[GetHorizontalDistanceTo](ue_ue.Actor.md#gethorizontaldistanceto)

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

[Actor](ue_ue.Actor.md).[GetHorizontalDotProductTo](ue_ue.Actor.md#gethorizontaldotproductto)

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

[Actor](ue_ue.Actor.md).[GetInputAxisKeyValue](ue_ue.Actor.md#getinputaxiskeyvalue)

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

[Actor](ue_ue.Actor.md).[GetInputAxisValue](ue_ue.Actor.md#getinputaxisvalue)

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

[Actor](ue_ue.Actor.md).[GetInputVectorAxisValue](ue_ue.Actor.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetInstigator](ue_ue.Actor.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetInstigatorController](ue_ue.Actor.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetLifeSpan](ue_ue.Actor.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetLocalRole](ue_ue.Actor.md#getlocalrole)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetName](ue_ue.Actor.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetOuter](ue_ue.Actor.md#getouter)

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

[Actor](ue_ue.Actor.md).[GetOverlappingActors](ue_ue.Actor.md#getoverlappingactors)

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

[Actor](ue_ue.Actor.md).[GetOverlappingComponents](ue_ue.Actor.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetOwner](ue_ue.Actor.md#getowner)

___

### GetOwningPlayerController

▸ **GetOwningPlayerController**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetParentActor](ue_ue.Actor.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetParentComponent](ue_ue.Actor.md#getparentcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetRemoteRole](ue_ue.Actor.md#getremoterole)

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

[Actor](ue_ue.Actor.md).[GetSquaredDistanceTo](ue_ue.Actor.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[GetTickableWhenPaused](ue_ue.Actor.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetTransform](ue_ue.Actor.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetVelocity](ue_ue.Actor.md#getvelocity)

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

[Actor](ue_ue.Actor.md).[GetVerticalDistanceTo](ue_ue.Actor.md#getverticaldistanceto)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[GetWorld](ue_ue.Actor.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[HasAuthority](ue_ue.Actor.md#hasauthority)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[IsActorBeingDestroyed](ue_ue.Actor.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[IsActorTickEnabled](ue_ue.Actor.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[IsChildActor](ue_ue.Actor.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[IsEditable](ue_ue.Actor.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[IsHiddenEd](ue_ue.Actor.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[IsHiddenEdAtStartup](ue_ue.Actor.md#ishiddenedatstartup)

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

[Actor](ue_ue.Actor.md).[IsOverlappingActor](ue_ue.Actor.md#isoverlappingactor)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Actor](ue_ue.Actor.md).[IsSelectable](ue_ue.Actor.md#isselectable)

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

[Actor](ue_ue.Actor.md).[IsTemporarilyHiddenInEditor](ue_ue.Actor.md#istemporarilyhiddenineditor)

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

[Actor](ue_ue.Actor.md).[K2_AddActorLocalOffset](ue_ue.Actor.md#k2_addactorlocaloffset)

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

[Actor](ue_ue.Actor.md).[K2_AddActorLocalRotation](ue_ue.Actor.md#k2_addactorlocalrotation)

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

[Actor](ue_ue.Actor.md).[K2_AddActorLocalTransform](ue_ue.Actor.md#k2_addactorlocaltransform)

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

[Actor](ue_ue.Actor.md).[K2_AddActorWorldOffset](ue_ue.Actor.md#k2_addactorworldoffset)

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

[Actor](ue_ue.Actor.md).[K2_AddActorWorldRotation](ue_ue.Actor.md#k2_addactorworldrotation)

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

[Actor](ue_ue.Actor.md).[K2_AddActorWorldTransform](ue_ue.Actor.md#k2_addactorworldtransform)

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

[Actor](ue_ue.Actor.md).[K2_AttachRootComponentTo](ue_ue.Actor.md#k2_attachrootcomponentto)

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

[Actor](ue_ue.Actor.md).[K2_AttachRootComponentToActor](ue_ue.Actor.md#k2_attachrootcomponenttoactor)

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

[Actor](ue_ue.Actor.md).[K2_AttachToActor](ue_ue.Actor.md#k2_attachtoactor)

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

[Actor](ue_ue.Actor.md).[K2_AttachToComponent](ue_ue.Actor.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[K2_DestroyActor](ue_ue.Actor.md#k2_destroyactor)

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

[Actor](ue_ue.Actor.md).[K2_DestroyComponent](ue_ue.Actor.md#k2_destroycomponent)

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

[Actor](ue_ue.Actor.md).[K2_DetachFromActor](ue_ue.Actor.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[K2_GetActorLocation](ue_ue.Actor.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[K2_GetActorRotation](ue_ue.Actor.md#k2_getactorrotation)

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

[Actor](ue_ue.Actor.md).[K2_GetComponentsByClass](ue_ue.Actor.md#k2_getcomponentsbyclass)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Actor](ue_ue.Actor.md).[K2_GetRootComponent](ue_ue.Actor.md#k2_getrootcomponent)

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

[Actor](ue_ue.Actor.md).[K2_OnBecomeViewTarget](ue_ue.Actor.md#k2_onbecomeviewtarget)

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

[Actor](ue_ue.Actor.md).[K2_OnEndViewTarget](ue_ue.Actor.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[K2_OnReset](ue_ue.Actor.md#k2_onreset)

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

[Actor](ue_ue.Actor.md).[K2_SetActorLocation](ue_ue.Actor.md#k2_setactorlocation)

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

[Actor](ue_ue.Actor.md).[K2_SetActorLocationAndRotation](ue_ue.Actor.md#k2_setactorlocationandrotation)

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

[Actor](ue_ue.Actor.md).[K2_SetActorRelativeLocation](ue_ue.Actor.md#k2_setactorrelativelocation)

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

[Actor](ue_ue.Actor.md).[K2_SetActorRelativeRotation](ue_ue.Actor.md#k2_setactorrelativerotation)

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

[Actor](ue_ue.Actor.md).[K2_SetActorRelativeTransform](ue_ue.Actor.md#k2_setactorrelativetransform)

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

[Actor](ue_ue.Actor.md).[K2_SetActorRotation](ue_ue.Actor.md#k2_setactorrotation)

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

[Actor](ue_ue.Actor.md).[K2_SetActorTransform](ue_ue.Actor.md#k2_setactortransform)

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

[Actor](ue_ue.Actor.md).[K2_TeleportTo](ue_ue.Actor.md#k2_teleportto)

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

[Actor](ue_ue.Actor.md).[MakeMIDForMaterial](ue_ue.Actor.md#makemidformaterial)

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

[Actor](ue_ue.Actor.md).[MakeNoise](ue_ue.Actor.md#makenoise)

___

### OnPhotographyMultiPartCaptureEnd

▸ **OnPhotographyMultiPartCaptureEnd**(): `void`

#### Returns

`void`

___

### OnPhotographyMultiPartCaptureStart

▸ **OnPhotographyMultiPartCaptureStart**(): `void`

#### Returns

`void`

___

### OnPhotographySessionEnd

▸ **OnPhotographySessionEnd**(): `void`

#### Returns

`void`

___

### OnPhotographySessionStart

▸ **OnPhotographySessionStart**(): `void`

#### Returns

`void`

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[OnRep_AttachmentReplication](ue_ue.Actor.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[OnRep_Instigator](ue_ue.Actor.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[OnRep_Owner](ue_ue.Actor.md#onrep_owner)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[OnRep_ReplicateMovement](ue_ue.Actor.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[OnRep_ReplicatedMovement](ue_ue.Actor.md#onrep_replicatedmovement)

___

### PhotographyCameraModify

▸ **PhotographyCameraModify**(`NewCameraLocation`, `PreviousCameraLocation`, `OriginalCameraLocation`, `ResultCameraLocation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewCameraLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `PreviousCameraLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `OriginalCameraLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `ResultCameraLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

___

### PlayCameraAnim

▸ **PlayCameraAnim**(`Anim`, `Rate?`, `Scale?`, `BlendInTime?`, `BlendOutTime?`, `bLoop?`, `bRandomStartTime?`, `Duration?`, `PlaySpace?`, `UserPlaySpaceRot?`): [`CameraAnimInst`](ue_ue.CameraAnimInst.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Anim` | [`$Nullable`](../modules/puerts.md#$nullable)<[`CameraAnim`](ue_ue.CameraAnim.md)\> |
| `Rate?` | `number` |
| `Scale?` | `number` |
| `BlendInTime?` | `number` |
| `BlendOutTime?` | `number` |
| `bLoop?` | `boolean` |
| `bRandomStartTime?` | `boolean` |
| `Duration?` | `number` |
| `PlaySpace?` | [`ECameraAnimPlaySpace`](../enums/ue_ue.ECameraAnimPlaySpace.md) |
| `UserPlaySpaceRot?` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

[`CameraAnimInst`](ue_ue.CameraAnimInst.md)

___

### PlayCameraShake

▸ **PlayCameraShake**(`ShakeClass`, `Scale?`, `PlaySpace?`, `UserPlaySpaceRot?`): [`CameraShake`](ue_ue.CameraShake.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ShakeClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `Scale?` | `number` |
| `PlaySpace?` | [`ECameraAnimPlaySpace`](../enums/ue_ue.ECameraAnimPlaySpace.md) |
| `UserPlaySpaceRot?` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

[`CameraShake`](ue_ue.CameraShake.md)

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

[Actor](ue_ue.Actor.md).[PrestreamTextures](ue_ue.Actor.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[ReceiveActorBeginCursorOver](ue_ue.Actor.md#receiveactorbegincursorover)

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

[Actor](ue_ue.Actor.md).[ReceiveActorBeginOverlap](ue_ue.Actor.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[ReceiveActorEndCursorOver](ue_ue.Actor.md#receiveactorendcursorover)

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

[Actor](ue_ue.Actor.md).[ReceiveActorEndOverlap](ue_ue.Actor.md#receiveactorendoverlap)

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

[Actor](ue_ue.Actor.md).[ReceiveActorOnClicked](ue_ue.Actor.md#receiveactoronclicked)

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

[Actor](ue_ue.Actor.md).[ReceiveActorOnInputTouchBegin](ue_ue.Actor.md#receiveactoroninputtouchbegin)

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

[Actor](ue_ue.Actor.md).[ReceiveActorOnInputTouchEnd](ue_ue.Actor.md#receiveactoroninputtouchend)

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

[Actor](ue_ue.Actor.md).[ReceiveActorOnInputTouchEnter](ue_ue.Actor.md#receiveactoroninputtouchenter)

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

[Actor](ue_ue.Actor.md).[ReceiveActorOnInputTouchLeave](ue_ue.Actor.md#receiveactoroninputtouchleave)

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

[Actor](ue_ue.Actor.md).[ReceiveActorOnReleased](ue_ue.Actor.md#receiveactoronreleased)

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

[Actor](ue_ue.Actor.md).[ReceiveAnyDamage](ue_ue.Actor.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[ReceiveBeginPlay](ue_ue.Actor.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[ReceiveDestroyed](ue_ue.Actor.md#receivedestroyed)

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

[Actor](ue_ue.Actor.md).[ReceiveEndPlay](ue_ue.Actor.md#receiveendplay)

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

[Actor](ue_ue.Actor.md).[ReceiveHit](ue_ue.Actor.md#receivehit)

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

[Actor](ue_ue.Actor.md).[ReceivePointDamage](ue_ue.Actor.md#receivepointdamage)

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

[Actor](ue_ue.Actor.md).[ReceiveRadialDamage](ue_ue.Actor.md#receiveradialdamage)

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

[Actor](ue_ue.Actor.md).[ReceiveTick](ue_ue.Actor.md#receivetick)

___

### RemoveCameraLensEffect

▸ **RemoveCameraLensEffect**(`Emitter`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Emitter` | [`$Nullable`](../modules/puerts.md#$nullable)<[`EmitterCameraLensEffectBase`](ue_ue.EmitterCameraLensEffectBase.md)\> |

#### Returns

`void`

___

### RemoveCameraModifier

▸ **RemoveCameraModifier**(`ModifierToRemove`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ModifierToRemove` | [`$Nullable`](../modules/puerts.md#$nullable)<[`CameraModifier`](ue_ue.CameraModifier.md)\> |

#### Returns

`boolean`

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

[Actor](ue_ue.Actor.md).[RemoveTickPrerequisiteActor](ue_ue.Actor.md#removetickprerequisiteactor)

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

[Actor](ue_ue.Actor.md).[RemoveTickPrerequisiteComponent](ue_ue.Actor.md#removetickprerequisitecomponent)

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

[Actor](ue_ue.Actor.md).[SetActorEnableCollision](ue_ue.Actor.md#setactorenablecollision)

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

[Actor](ue_ue.Actor.md).[SetActorHiddenInGame](ue_ue.Actor.md#setactorhiddeningame)

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

[Actor](ue_ue.Actor.md).[SetActorLabel](ue_ue.Actor.md#setactorlabel)

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

[Actor](ue_ue.Actor.md).[SetActorRelativeScale3D](ue_ue.Actor.md#setactorrelativescale3d)

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

[Actor](ue_ue.Actor.md).[SetActorScale3D](ue_ue.Actor.md#setactorscale3d)

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

[Actor](ue_ue.Actor.md).[SetActorTickEnabled](ue_ue.Actor.md#setactortickenabled)

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

[Actor](ue_ue.Actor.md).[SetActorTickInterval](ue_ue.Actor.md#setactortickinterval)

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

[Actor](ue_ue.Actor.md).[SetFolderPath](ue_ue.Actor.md#setfolderpath)

___

### SetGameCameraCutThisFrame

▸ **SetGameCameraCutThisFrame**(): `void`

#### Returns

`void`

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

[Actor](ue_ue.Actor.md).[SetIsTemporarilyHiddenInEditor](ue_ue.Actor.md#setistemporarilyhiddenineditor)

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

[Actor](ue_ue.Actor.md).[SetLifeSpan](ue_ue.Actor.md#setlifespan)

___

### SetManualCameraFade

▸ **SetManualCameraFade**(`InFadeAmount`, `Color`, `bInFadeAudio`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFadeAmount` | `number` |
| `Color` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `bInFadeAudio` | `boolean` |

#### Returns

`void`

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

[Actor](ue_ue.Actor.md).[SetNetDormancy](ue_ue.Actor.md#setnetdormancy)

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

[Actor](ue_ue.Actor.md).[SetOwner](ue_ue.Actor.md#setowner)

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

[Actor](ue_ue.Actor.md).[SetReplicateMovement](ue_ue.Actor.md#setreplicatemovement)

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

[Actor](ue_ue.Actor.md).[SetReplicates](ue_ue.Actor.md#setreplicates)

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

[Actor](ue_ue.Actor.md).[SetTickGroup](ue_ue.Actor.md#settickgroup)

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

[Actor](ue_ue.Actor.md).[SetTickableWhenPaused](ue_ue.Actor.md#settickablewhenpaused)

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

[Actor](ue_ue.Actor.md).[SnapRootComponentTo](ue_ue.Actor.md#snaprootcomponentto)

___

### StartCameraFade

▸ **StartCameraFade**(`FromAlpha`, `ToAlpha`, `Duration`, `Color`, `bShouldFadeAudio?`, `bHoldWhenFinished?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FromAlpha` | `number` |
| `ToAlpha` | `number` |
| `Duration` | `number` |
| `Color` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `bShouldFadeAudio?` | `boolean` |
| `bHoldWhenFinished?` | `boolean` |

#### Returns

`void`

___

### StopAllCameraAnims

▸ **StopAllCameraAnims**(`bImmediate?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bImmediate?` | `boolean` |

#### Returns

`void`

___

### StopAllCameraShakes

▸ **StopAllCameraShakes**(`bImmediately?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bImmediately?` | `boolean` |

#### Returns

`void`

___

### StopAllInstancesOfCameraAnim

▸ **StopAllInstancesOfCameraAnim**(`Anim`, `bImmediate?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Anim` | [`$Nullable`](../modules/puerts.md#$nullable)<[`CameraAnim`](ue_ue.CameraAnim.md)\> |
| `bImmediate?` | `boolean` |

#### Returns

`void`

___

### StopAllInstancesOfCameraShake

▸ **StopAllInstancesOfCameraShake**(`Shake`, `bImmediately?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Shake` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `bImmediately?` | `boolean` |

#### Returns

`void`

___

### StopCameraAnimInst

▸ **StopCameraAnimInst**(`AnimInst`, `bImmediate?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimInst` | [`$Nullable`](../modules/puerts.md#$nullable)<[`CameraAnimInst`](ue_ue.CameraAnimInst.md)\> |
| `bImmediate?` | `boolean` |

#### Returns

`void`

___

### StopCameraFade

▸ **StopCameraFade**(): `void`

#### Returns

`void`

___

### StopCameraShake

▸ **StopCameraShake**(`ShakeInstance`, `bImmediately?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ShakeInstance` | [`$Nullable`](../modules/puerts.md#$nullable)<[`CameraShake`](ue_ue.CameraShake.md)\> |
| `bImmediately?` | `boolean` |

#### Returns

`void`

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[TearOff](ue_ue.Actor.md#tearoff)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[Actor](ue_ue.Actor.md).[UserConstructionScript](ue_ue.Actor.md#userconstructionscript)

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

[Actor](ue_ue.Actor.md).[WasRecentlyRendered](ue_ue.Actor.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PlayerCameraManager`](ue_ue.PlayerCameraManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PlayerCameraManager`](ue_ue.PlayerCameraManager.md)

#### Overrides

[Actor](ue_ue.Actor.md).[Find](ue_ue.Actor.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PlayerCameraManager`](ue_ue.PlayerCameraManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PlayerCameraManager`](ue_ue.PlayerCameraManager.md)

#### Overrides

[Actor](ue_ue.Actor.md).[Load](ue_ue.Actor.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Actor](ue_ue.Actor.md).[StaticClass](ue_ue.Actor.md#staticclass)
