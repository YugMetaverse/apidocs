[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EmitterCameraLensEffectBase

# Class: EmitterCameraLensEffectBase

[ue/ue](../modules/ue_ue.md).EmitterCameraLensEffectBase

## Hierarchy

- [`Emitter`](ue_ue.Emitter.md)

  ↳ **`EmitterCameraLensEffectBase`**

## Table of contents

### Constructors

- [constructor](ue_ue.EmitterCameraLensEffectBase.md#constructor)

### Properties

- [ActorLabel](ue_ue.EmitterCameraLensEffectBase.md#actorlabel)
- [ArrowComponent](ue_ue.EmitterCameraLensEffectBase.md#arrowcomponent)
- [AttachmentReplication](ue_ue.EmitterCameraLensEffectBase.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.EmitterCameraLensEffectBase.md#autoreceiveinput)
- [BaseCamera](ue_ue.EmitterCameraLensEffectBase.md#basecamera)
- [BaseFOV](ue_ue.EmitterCameraLensEffectBase.md#basefov)
- [BlueprintCreatedComponents](ue_ue.EmitterCameraLensEffectBase.md#blueprintcreatedcomponents)
- [Children](ue_ue.EmitterCameraLensEffectBase.md#children)
- [ControllingMatineeActors](ue_ue.EmitterCameraLensEffectBase.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.EmitterCameraLensEffectBase.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.EmitterCameraLensEffectBase.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [DistFromCamera](ue_ue.EmitterCameraLensEffectBase.md#distfromcamera)
- [EmittersToTreatAsSame](ue_ue.EmitterCameraLensEffectBase.md#emitterstotreatassame)
- [FolderPath](ue_ue.EmitterCameraLensEffectBase.md#folderpath)
- [GroupActor](ue_ue.EmitterCameraLensEffectBase.md#groupactor)
- [HiddenEditorViews](ue_ue.EmitterCameraLensEffectBase.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.EmitterCameraLensEffectBase.md#initiallifespan)
- [InputComponent](ue_ue.EmitterCameraLensEffectBase.md#inputcomponent)
- [InputPriority](ue_ue.EmitterCameraLensEffectBase.md#inputpriority)
- [InstanceComponents](ue_ue.EmitterCameraLensEffectBase.md#instancecomponents)
- [Instigator](ue_ue.EmitterCameraLensEffectBase.md#instigator)
- [Layers](ue_ue.EmitterCameraLensEffectBase.md#layers)
- [MinNetUpdateFrequency](ue_ue.EmitterCameraLensEffectBase.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.EmitterCameraLensEffectBase.md#netculldistancesquared)
- [NetDormancy](ue_ue.EmitterCameraLensEffectBase.md#netdormancy)
- [NetDriverName](ue_ue.EmitterCameraLensEffectBase.md#netdrivername)
- [NetPriority](ue_ue.EmitterCameraLensEffectBase.md#netpriority)
- [NetTag](ue_ue.EmitterCameraLensEffectBase.md#nettag)
- [NetUpdateFrequency](ue_ue.EmitterCameraLensEffectBase.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.EmitterCameraLensEffectBase.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.EmitterCameraLensEffectBase.md#onactorendoverlap)
- [OnActorHit](ue_ue.EmitterCameraLensEffectBase.md#onactorhit)
- [OnBeginCursorOver](ue_ue.EmitterCameraLensEffectBase.md#onbegincursorover)
- [OnClicked](ue_ue.EmitterCameraLensEffectBase.md#onclicked)
- [OnDestroyed](ue_ue.EmitterCameraLensEffectBase.md#ondestroyed)
- [OnEndCursorOver](ue_ue.EmitterCameraLensEffectBase.md#onendcursorover)
- [OnEndPlay](ue_ue.EmitterCameraLensEffectBase.md#onendplay)
- [OnInputTouchBegin](ue_ue.EmitterCameraLensEffectBase.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.EmitterCameraLensEffectBase.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.EmitterCameraLensEffectBase.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.EmitterCameraLensEffectBase.md#oninputtouchleave)
- [OnParticleBurst](ue_ue.EmitterCameraLensEffectBase.md#onparticleburst)
- [OnParticleCollide](ue_ue.EmitterCameraLensEffectBase.md#onparticlecollide)
- [OnParticleDeath](ue_ue.EmitterCameraLensEffectBase.md#onparticledeath)
- [OnParticleSpawn](ue_ue.EmitterCameraLensEffectBase.md#onparticlespawn)
- [OnReleased](ue_ue.EmitterCameraLensEffectBase.md#onreleased)
- [OnTakeAnyDamage](ue_ue.EmitterCameraLensEffectBase.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.EmitterCameraLensEffectBase.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.EmitterCameraLensEffectBase.md#ontakeradialdamage)
- [Owner](ue_ue.EmitterCameraLensEffectBase.md#owner)
- [PS\_CameraEffect](ue_ue.EmitterCameraLensEffectBase.md#ps_cameraeffect)
- [PS\_CameraEffectNonExtremeContent](ue_ue.EmitterCameraLensEffectBase.md#ps_cameraeffectnonextremecontent)
- [ParentComponent](ue_ue.EmitterCameraLensEffectBase.md#parentcomponent)
- [ParentComponentActor](ue_ue.EmitterCameraLensEffectBase.md#parentcomponentactor)
- [ParticleSystemComponent](ue_ue.EmitterCameraLensEffectBase.md#particlesystemcomponent)
- [PivotOffset](ue_ue.EmitterCameraLensEffectBase.md#pivotoffset)
- [PrimaryActorTick](ue_ue.EmitterCameraLensEffectBase.md#primaryactortick)
- [RelativeTransform](ue_ue.EmitterCameraLensEffectBase.md#relativetransform)
- [RemoteRole](ue_ue.EmitterCameraLensEffectBase.md#remoterole)
- [ReplicatedMovement](ue_ue.EmitterCameraLensEffectBase.md#replicatedmovement)
- [Role](ue_ue.EmitterCameraLensEffectBase.md#role)
- [RootComponent](ue_ue.EmitterCameraLensEffectBase.md#rootcomponent)
- [SpawnCollisionHandlingMethod](ue_ue.EmitterCameraLensEffectBase.md#spawncollisionhandlingmethod)
- [SpriteComponent](ue_ue.EmitterCameraLensEffectBase.md#spritecomponent)
- [SpriteScale](ue_ue.EmitterCameraLensEffectBase.md#spritescale)
- [Tags](ue_ue.EmitterCameraLensEffectBase.md#tags)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.EmitterCameraLensEffectBase.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.EmitterCameraLensEffectBase.md#__tid_actor__)
- [\_\_tid\_EmitterCameraLensEffectBase\_\_](ue_ue.EmitterCameraLensEffectBase.md#__tid_emittercameralenseffectbase__)
- [\_\_tid\_Emitter\_\_](ue_ue.EmitterCameraLensEffectBase.md#__tid_emitter__)
- [\_\_tid\_Object\_\_](ue_ue.EmitterCameraLensEffectBase.md#__tid_object__)
- [bActorEnableCollision](ue_ue.EmitterCameraLensEffectBase.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.EmitterCameraLensEffectBase.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.EmitterCameraLensEffectBase.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.EmitterCameraLensEffectBase.md#bactorseamlesstraveled)
- [bAllowMultipleInstances](ue_ue.EmitterCameraLensEffectBase.md#ballowmultipleinstances)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.EmitterCameraLensEffectBase.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.EmitterCameraLensEffectBase.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.EmitterCameraLensEffectBase.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.EmitterCameraLensEffectBase.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.EmitterCameraLensEffectBase.md#bblockinput)
- [bCanBeDamaged](ue_ue.EmitterCameraLensEffectBase.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.EmitterCameraLensEffectBase.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.EmitterCameraLensEffectBase.md#bcollidewhenplacing)
- [bCurrentlyActive](ue_ue.EmitterCameraLensEffectBase.md#bcurrentlyactive)
- [bDestroyOnSystemFinish](ue_ue.EmitterCameraLensEffectBase.md#bdestroyonsystemfinish)
- [bEditable](ue_ue.EmitterCameraLensEffectBase.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.EmitterCameraLensEffectBase.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.EmitterCameraLensEffectBase.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.EmitterCameraLensEffectBase.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.EmitterCameraLensEffectBase.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.EmitterCameraLensEffectBase.md#bhidden)
- [bHiddenEd](ue_ue.EmitterCameraLensEffectBase.md#bhiddened)
- [bHiddenEdLayer](ue_ue.EmitterCameraLensEffectBase.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.EmitterCameraLensEffectBase.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.EmitterCameraLensEffectBase.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.EmitterCameraLensEffectBase.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.EmitterCameraLensEffectBase.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.EmitterCameraLensEffectBase.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.EmitterCameraLensEffectBase.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.EmitterCameraLensEffectBase.md#blocklocation)
- [bNetLoadOnClient](ue_ue.EmitterCameraLensEffectBase.md#bnetloadonclient)
- [bNetStartup](ue_ue.EmitterCameraLensEffectBase.md#bnetstartup)
- [bNetTemporary](ue_ue.EmitterCameraLensEffectBase.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.EmitterCameraLensEffectBase.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.EmitterCameraLensEffectBase.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.EmitterCameraLensEffectBase.md#boptimizebpcomponentdata)
- [bPostUpdateTickGroup](ue_ue.EmitterCameraLensEffectBase.md#bpostupdatetickgroup)
- [bRelevantForLevelBounds](ue_ue.EmitterCameraLensEffectBase.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.EmitterCameraLensEffectBase.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.EmitterCameraLensEffectBase.md#breplayrewindable)
- [bReplicateMovement](ue_ue.EmitterCameraLensEffectBase.md#breplicatemovement)
- [bReplicates](ue_ue.EmitterCameraLensEffectBase.md#breplicates)
- [bResetWhenRetriggered](ue_ue.EmitterCameraLensEffectBase.md#bresetwhenretriggered)
- [bTearOff](ue_ue.EmitterCameraLensEffectBase.md#btearoff)

### Methods

- [Activate](ue_ue.EmitterCameraLensEffectBase.md#activate)
- [ActorHasTag](ue_ue.EmitterCameraLensEffectBase.md#actorhastag)
- [AddComponent](ue_ue.EmitterCameraLensEffectBase.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.EmitterCameraLensEffectBase.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.EmitterCameraLensEffectBase.md#addtickprerequisitecomponent)
- [CreateDefaultSubobject](ue_ue.EmitterCameraLensEffectBase.md#createdefaultsubobject)
- [Deactivate](ue_ue.EmitterCameraLensEffectBase.md#deactivate)
- [DetachRootComponentFromParent](ue_ue.EmitterCameraLensEffectBase.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.EmitterCameraLensEffectBase.md#disableinput)
- [EnableInput](ue_ue.EmitterCameraLensEffectBase.md#enableinput)
- [ExecuteUbergraph](ue_ue.EmitterCameraLensEffectBase.md#executeubergraph)
- [FlushNetDormancy](ue_ue.EmitterCameraLensEffectBase.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.EmitterCameraLensEffectBase.md#forcenetupdate)
- [GetActorBounds](ue_ue.EmitterCameraLensEffectBase.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.EmitterCameraLensEffectBase.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.EmitterCameraLensEffectBase.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.EmitterCameraLensEffectBase.md#getactorforwardvector)
- [GetActorLabel](ue_ue.EmitterCameraLensEffectBase.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.EmitterCameraLensEffectBase.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.EmitterCameraLensEffectBase.md#getactorrightvector)
- [GetActorScale3D](ue_ue.EmitterCameraLensEffectBase.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.EmitterCameraLensEffectBase.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.EmitterCameraLensEffectBase.md#getactortimedilation)
- [GetActorUpVector](ue_ue.EmitterCameraLensEffectBase.md#getactorupvector)
- [GetAllChildActors](ue_ue.EmitterCameraLensEffectBase.md#getallchildactors)
- [GetAttachParentActor](ue_ue.EmitterCameraLensEffectBase.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.EmitterCameraLensEffectBase.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.EmitterCameraLensEffectBase.md#getattachedactors)
- [GetClass](ue_ue.EmitterCameraLensEffectBase.md#getclass)
- [GetComponentByClass](ue_ue.EmitterCameraLensEffectBase.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.EmitterCameraLensEffectBase.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.EmitterCameraLensEffectBase.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.EmitterCameraLensEffectBase.md#getdistanceto)
- [GetDotProductTo](ue_ue.EmitterCameraLensEffectBase.md#getdotproductto)
- [GetFolderPath](ue_ue.EmitterCameraLensEffectBase.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.EmitterCameraLensEffectBase.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.EmitterCameraLensEffectBase.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.EmitterCameraLensEffectBase.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.EmitterCameraLensEffectBase.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.EmitterCameraLensEffectBase.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.EmitterCameraLensEffectBase.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.EmitterCameraLensEffectBase.md#getinstigator)
- [GetInstigatorController](ue_ue.EmitterCameraLensEffectBase.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.EmitterCameraLensEffectBase.md#getlifespan)
- [GetLocalRole](ue_ue.EmitterCameraLensEffectBase.md#getlocalrole)
- [GetName](ue_ue.EmitterCameraLensEffectBase.md#getname)
- [GetOuter](ue_ue.EmitterCameraLensEffectBase.md#getouter)
- [GetOverlappingActors](ue_ue.EmitterCameraLensEffectBase.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.EmitterCameraLensEffectBase.md#getoverlappingcomponents)
- [GetOwner](ue_ue.EmitterCameraLensEffectBase.md#getowner)
- [GetParentActor](ue_ue.EmitterCameraLensEffectBase.md#getparentactor)
- [GetParentComponent](ue_ue.EmitterCameraLensEffectBase.md#getparentcomponent)
- [GetRemoteRole](ue_ue.EmitterCameraLensEffectBase.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.EmitterCameraLensEffectBase.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.EmitterCameraLensEffectBase.md#gettickablewhenpaused)
- [GetTransform](ue_ue.EmitterCameraLensEffectBase.md#gettransform)
- [GetVelocity](ue_ue.EmitterCameraLensEffectBase.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.EmitterCameraLensEffectBase.md#getverticaldistanceto)
- [GetWorld](ue_ue.EmitterCameraLensEffectBase.md#getworld)
- [HasAuthority](ue_ue.EmitterCameraLensEffectBase.md#hasauthority)
- [IsActive](ue_ue.EmitterCameraLensEffectBase.md#isactive)
- [IsActorBeingDestroyed](ue_ue.EmitterCameraLensEffectBase.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.EmitterCameraLensEffectBase.md#isactortickenabled)
- [IsChildActor](ue_ue.EmitterCameraLensEffectBase.md#ischildactor)
- [IsEditable](ue_ue.EmitterCameraLensEffectBase.md#iseditable)
- [IsHiddenEd](ue_ue.EmitterCameraLensEffectBase.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.EmitterCameraLensEffectBase.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.EmitterCameraLensEffectBase.md#isoverlappingactor)
- [IsSelectable](ue_ue.EmitterCameraLensEffectBase.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.EmitterCameraLensEffectBase.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.EmitterCameraLensEffectBase.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.EmitterCameraLensEffectBase.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.EmitterCameraLensEffectBase.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.EmitterCameraLensEffectBase.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.EmitterCameraLensEffectBase.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.EmitterCameraLensEffectBase.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.EmitterCameraLensEffectBase.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.EmitterCameraLensEffectBase.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.EmitterCameraLensEffectBase.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.EmitterCameraLensEffectBase.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.EmitterCameraLensEffectBase.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.EmitterCameraLensEffectBase.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.EmitterCameraLensEffectBase.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.EmitterCameraLensEffectBase.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.EmitterCameraLensEffectBase.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.EmitterCameraLensEffectBase.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.EmitterCameraLensEffectBase.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.EmitterCameraLensEffectBase.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.EmitterCameraLensEffectBase.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.EmitterCameraLensEffectBase.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.EmitterCameraLensEffectBase.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.EmitterCameraLensEffectBase.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.EmitterCameraLensEffectBase.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.EmitterCameraLensEffectBase.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.EmitterCameraLensEffectBase.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.EmitterCameraLensEffectBase.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.EmitterCameraLensEffectBase.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.EmitterCameraLensEffectBase.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.EmitterCameraLensEffectBase.md#makemidformaterial)
- [MakeNoise](ue_ue.EmitterCameraLensEffectBase.md#makenoise)
- [OnParticleSystemFinished](ue_ue.EmitterCameraLensEffectBase.md#onparticlesystemfinished)
- [OnRep\_AttachmentReplication](ue_ue.EmitterCameraLensEffectBase.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.EmitterCameraLensEffectBase.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.EmitterCameraLensEffectBase.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.EmitterCameraLensEffectBase.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.EmitterCameraLensEffectBase.md#onrep_replicatedmovement)
- [OnRep\_bCurrentlyActive](ue_ue.EmitterCameraLensEffectBase.md#onrep_bcurrentlyactive)
- [PrestreamTextures](ue_ue.EmitterCameraLensEffectBase.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.EmitterCameraLensEffectBase.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.EmitterCameraLensEffectBase.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.EmitterCameraLensEffectBase.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.EmitterCameraLensEffectBase.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.EmitterCameraLensEffectBase.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.EmitterCameraLensEffectBase.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.EmitterCameraLensEffectBase.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.EmitterCameraLensEffectBase.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.EmitterCameraLensEffectBase.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.EmitterCameraLensEffectBase.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.EmitterCameraLensEffectBase.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.EmitterCameraLensEffectBase.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.EmitterCameraLensEffectBase.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.EmitterCameraLensEffectBase.md#receiveendplay)
- [ReceiveHit](ue_ue.EmitterCameraLensEffectBase.md#receivehit)
- [ReceivePointDamage](ue_ue.EmitterCameraLensEffectBase.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.EmitterCameraLensEffectBase.md#receiveradialdamage)
- [ReceiveTick](ue_ue.EmitterCameraLensEffectBase.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.EmitterCameraLensEffectBase.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.EmitterCameraLensEffectBase.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.EmitterCameraLensEffectBase.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.EmitterCameraLensEffectBase.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.EmitterCameraLensEffectBase.md#setactorlabel)
- [SetActorParameter](ue_ue.EmitterCameraLensEffectBase.md#setactorparameter)
- [SetActorRelativeScale3D](ue_ue.EmitterCameraLensEffectBase.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.EmitterCameraLensEffectBase.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.EmitterCameraLensEffectBase.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.EmitterCameraLensEffectBase.md#setactortickinterval)
- [SetColorParameter](ue_ue.EmitterCameraLensEffectBase.md#setcolorparameter)
- [SetFloatParameter](ue_ue.EmitterCameraLensEffectBase.md#setfloatparameter)
- [SetFolderPath](ue_ue.EmitterCameraLensEffectBase.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.EmitterCameraLensEffectBase.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.EmitterCameraLensEffectBase.md#setlifespan)
- [SetMaterialParameter](ue_ue.EmitterCameraLensEffectBase.md#setmaterialparameter)
- [SetNetDormancy](ue_ue.EmitterCameraLensEffectBase.md#setnetdormancy)
- [SetOwner](ue_ue.EmitterCameraLensEffectBase.md#setowner)
- [SetReplicateMovement](ue_ue.EmitterCameraLensEffectBase.md#setreplicatemovement)
- [SetReplicates](ue_ue.EmitterCameraLensEffectBase.md#setreplicates)
- [SetTemplate](ue_ue.EmitterCameraLensEffectBase.md#settemplate)
- [SetTickGroup](ue_ue.EmitterCameraLensEffectBase.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.EmitterCameraLensEffectBase.md#settickablewhenpaused)
- [SetVectorParameter](ue_ue.EmitterCameraLensEffectBase.md#setvectorparameter)
- [SnapRootComponentTo](ue_ue.EmitterCameraLensEffectBase.md#snaprootcomponentto)
- [TearOff](ue_ue.EmitterCameraLensEffectBase.md#tearoff)
- [ToggleActive](ue_ue.EmitterCameraLensEffectBase.md#toggleactive)
- [UserConstructionScript](ue_ue.EmitterCameraLensEffectBase.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.EmitterCameraLensEffectBase.md#wasrecentlyrendered)
- [Find](ue_ue.EmitterCameraLensEffectBase.md#find)
- [Load](ue_ue.EmitterCameraLensEffectBase.md#load)
- [StaticClass](ue_ue.EmitterCameraLensEffectBase.md#staticclass)

## Constructors

### constructor

• **new EmitterCameraLensEffectBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Emitter](ue_ue.Emitter.md).[constructor](ue_ue.Emitter.md#constructor)

#### Defined in

[ue/ue.d.ts:7389](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7389)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ActorLabel](ue_ue.Emitter.md#actorlabel)

#### Defined in

[ue/ue.d.ts:13176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13176)

___

### ArrowComponent

• **ArrowComponent**: [`ArrowComponent`](ue_ue.ArrowComponent.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ArrowComponent](ue_ue.Emitter.md#arrowcomponent)

#### Defined in

[ue/ue.d.ts:7368](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7368)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[AttachmentReplication](ue_ue.Emitter.md#attachmentreplication)

#### Defined in

[ue/ue.d.ts:13151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13151)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[AutoReceiveInput](ue_ue.Emitter.md#autoreceiveinput)

#### Defined in

[ue/ue.d.ts:13157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13157)

___

### BaseCamera

• **BaseCamera**: [`PlayerCameraManager`](ue_ue.PlayerCameraManager.md)

#### Defined in

[ue/ue.d.ts:7392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7392)

___

### BaseFOV

• **BaseFOV**: `number`

#### Defined in

[ue/ue.d.ts:7394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7394)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[BlueprintCreatedComponents](ue_ue.Emitter.md#blueprintcreatedcomponents)

#### Defined in

[ue/ue.d.ts:13206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13206)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[Children](ue_ue.Emitter.md#children)

#### Defined in

[ue/ue.d.ts:13166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13166)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ControllingMatineeActors](ue_ue.Emitter.md#controllingmatineeactors)

#### Defined in

[ue/ue.d.ts:13169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13169)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[CustomTimeDilation](ue_ue.Emitter.md#customtimedilation)

#### Defined in

[ue/ue.d.ts:13150](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13150)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.Emitter.md#defaultupdateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13146](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13146)

___

### DistFromCamera

• **DistFromCamera**: `number`

#### Defined in

[ue/ue.d.ts:7398](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7398)

___

### EmittersToTreatAsSame

• **EmittersToTreatAsSame**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Class`](ue_ue.Class.md)\>

#### Defined in

[ue/ue.d.ts:7397](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7397)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[FolderPath](ue_ue.Emitter.md#folderpath)

#### Defined in

[ue/ue.d.ts:13177](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13177)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GroupActor](ue_ue.Emitter.md#groupactor)

#### Defined in

[ue/ue.d.ts:13173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13173)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[HiddenEditorViews](ue_ue.Emitter.md#hiddeneditorviews)

#### Defined in

[ue/ue.d.ts:13175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13175)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[InitialLifeSpan](ue_ue.Emitter.md#initiallifespan)

#### Defined in

[ue/ue.d.ts:13149](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13149)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[InputComponent](ue_ue.Emitter.md#inputcomponent)

#### Defined in

[ue/ue.d.ts:13159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13159)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[InputPriority](ue_ue.Emitter.md#inputpriority)

#### Defined in

[ue/ue.d.ts:13158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13158)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[InstanceComponents](ue_ue.Emitter.md#instancecomponents)

#### Defined in

[ue/ue.d.ts:13205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13205)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[Instigator](ue_ue.Emitter.md#instigator)

#### Defined in

[ue/ue.d.ts:13165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13165)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[Layers](ue_ue.Emitter.md#layers)

#### Defined in

[ue/ue.d.ts:13170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13170)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[MinNetUpdateFrequency](ue_ue.Emitter.md#minnetupdatefrequency)

#### Defined in

[ue/ue.d.ts:13163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13163)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[NetCullDistanceSquared](ue_ue.Emitter.md#netculldistancesquared)

#### Defined in

[ue/ue.d.ts:13160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13160)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[NetDormancy](ue_ue.Emitter.md#netdormancy)

#### Defined in

[ue/ue.d.ts:13155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13155)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[NetDriverName](ue_ue.Emitter.md#netdrivername)

#### Defined in

[ue/ue.d.ts:13153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13153)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[NetPriority](ue_ue.Emitter.md#netpriority)

#### Defined in

[ue/ue.d.ts:13164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13164)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[NetTag](ue_ue.Emitter.md#nettag)

#### Defined in

[ue/ue.d.ts:13161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13161)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[NetUpdateFrequency](ue_ue.Emitter.md#netupdatefrequency)

#### Defined in

[ue/ue.d.ts:13162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13162)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnActorBeginOverlap](ue_ue.Emitter.md#onactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13192)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnActorEndOverlap](ue_ue.Emitter.md#onactorendoverlap)

#### Defined in

[ue/ue.d.ts:13193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13193)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnActorHit](ue_ue.Emitter.md#onactorhit)

#### Defined in

[ue/ue.d.ts:13202](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13202)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnBeginCursorOver](ue_ue.Emitter.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:13194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13194)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnClicked](ue_ue.Emitter.md#onclicked)

#### Defined in

[ue/ue.d.ts:13196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13196)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnDestroyed](ue_ue.Emitter.md#ondestroyed)

#### Defined in

[ue/ue.d.ts:13203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13203)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnEndCursorOver](ue_ue.Emitter.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:13195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13195)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnEndPlay](ue_ue.Emitter.md#onendplay)

#### Defined in

[ue/ue.d.ts:13204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13204)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnInputTouchBegin](ue_ue.Emitter.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13198)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnInputTouchEnd](ue_ue.Emitter.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:13199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13199)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnInputTouchEnter](ue_ue.Emitter.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:13200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13200)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnInputTouchLeave](ue_ue.Emitter.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:13201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13201)

___

### OnParticleBurst

• **OnParticleBurst**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`EventName`: `string`, `EmitterTime`: `number`, `ParticleCount`: `number`) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnParticleBurst](ue_ue.Emitter.md#onparticleburst)

#### Defined in

[ue/ue.d.ts:7364](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7364)

___

### OnParticleCollide

• **OnParticleCollide**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`EventName`: `string`, `EmitterTime`: `number`, `ParticleTime`: `number`, `Location`: [`Vector`](ue_ue_s.Vector.md), `Velocity`: [`Vector`](ue_ue_s.Vector.md), `Direction`: [`Vector`](ue_ue_s.Vector.md), `Normal`: [`Vector`](ue_ue_s.Vector.md), `BoneName`: `string`, `PhysMat`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnParticleCollide](ue_ue.Emitter.md#onparticlecollide)

#### Defined in

[ue/ue.d.ts:7366](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7366)

___

### OnParticleDeath

• **OnParticleDeath**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`EventName`: `string`, `EmitterTime`: `number`, `ParticleTime`: `number`, `Location`: [`Vector`](ue_ue_s.Vector.md), `Velocity`: [`Vector`](ue_ue_s.Vector.md), `Direction`: [`Vector`](ue_ue_s.Vector.md)) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnParticleDeath](ue_ue.Emitter.md#onparticledeath)

#### Defined in

[ue/ue.d.ts:7365](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7365)

___

### OnParticleSpawn

• **OnParticleSpawn**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`EventName`: `string`, `EmitterTime`: `number`, `Location`: [`Vector`](ue_ue_s.Vector.md), `Velocity`: [`Vector`](ue_ue_s.Vector.md)) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnParticleSpawn](ue_ue.Emitter.md#onparticlespawn)

#### Defined in

[ue/ue.d.ts:7363](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7363)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnReleased](ue_ue.Emitter.md#onreleased)

#### Defined in

[ue/ue.d.ts:13197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13197)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnTakeAnyDamage](ue_ue.Emitter.md#ontakeanydamage)

#### Defined in

[ue/ue.d.ts:13189](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13189)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnTakePointDamage](ue_ue.Emitter.md#ontakepointdamage)

#### Defined in

[ue/ue.d.ts:13190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13190)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnTakeRadialDamage](ue_ue.Emitter.md#ontakeradialdamage)

#### Defined in

[ue/ue.d.ts:13191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13191)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[Owner](ue_ue.Emitter.md#owner)

#### Defined in

[ue/ue.d.ts:13152](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13152)

___

### PS\_CameraEffect

• **PS\_CameraEffect**: [`ParticleSystem`](ue_ue.ParticleSystem.md)

#### Defined in

[ue/ue.d.ts:7390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7390)

___

### PS\_CameraEffectNonExtremeContent

• **PS\_CameraEffectNonExtremeContent**: [`ParticleSystem`](ue_ue.ParticleSystem.md)

#### Defined in

[ue/ue.d.ts:7391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7391)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ParentComponent](ue_ue.Emitter.md#parentcomponent)

#### Defined in

[ue/ue.d.ts:13172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13172)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ParentComponentActor](ue_ue.Emitter.md#parentcomponentactor)

#### Defined in

[ue/ue.d.ts:13171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13171)

___

### ParticleSystemComponent

• **ParticleSystemComponent**: [`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ParticleSystemComponent](ue_ue.Emitter.md#particlesystemcomponent)

#### Defined in

[ue/ue.d.ts:7359](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7359)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[PivotOffset](ue_ue.Emitter.md#pivotoffset)

#### Defined in

[ue/ue.d.ts:13168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13168)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[PrimaryActorTick](ue_ue.Emitter.md#primaryactortick)

#### Defined in

[ue/ue.d.ts:13115](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13115)

___

### RelativeTransform

• **RelativeTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:7393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7393)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[RemoteRole](ue_ue.Emitter.md#remoterole)

#### Defined in

[ue/ue.d.ts:13147](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13147)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ReplicatedMovement](ue_ue.Emitter.md#replicatedmovement)

#### Defined in

[ue/ue.d.ts:13148](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13148)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[Role](ue_ue.Emitter.md#role)

#### Defined in

[ue/ue.d.ts:13154](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13154)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[RootComponent](ue_ue.Emitter.md#rootcomponent)

#### Defined in

[ue/ue.d.ts:13167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13167)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[SpawnCollisionHandlingMethod](ue_ue.Emitter.md#spawncollisionhandlingmethod)

#### Defined in

[ue/ue.d.ts:13156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13156)

___

### SpriteComponent

• **SpriteComponent**: [`BillboardComponent`](ue_ue.BillboardComponent.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[SpriteComponent](ue_ue.Emitter.md#spritecomponent)

#### Defined in

[ue/ue.d.ts:7367](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7367)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[SpriteScale](ue_ue.Emitter.md#spritescale)

#### Defined in

[ue/ue.d.ts:13174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13174)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[Tags](ue_ue.Emitter.md#tags)

#### Defined in

[ue/ue.d.ts:13188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13188)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.Emitter.md#updateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13145](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13145)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[__tid_Actor__](ue_ue.Emitter.md#__tid_actor__)

#### Defined in

[ue/ue.d.ts:13348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13348)

___

### \_\_tid\_EmitterCameraLensEffectBase\_\_

• **\_\_tid\_EmitterCameraLensEffectBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:7403](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7403)

___

### \_\_tid\_Emitter\_\_

• **\_\_tid\_Emitter\_\_**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[__tid_Emitter__](ue_ue.Emitter.md#__tid_emitter__)

#### Defined in

[ue/ue.d.ts:7385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7385)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[__tid_Object__](ue_ue.Emitter.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bActorEnableCollision](ue_ue.Emitter.md#bactorenablecollision)

#### Defined in

[ue/ue.d.ts:13143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13143)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bActorIsBeingDestroyed](ue_ue.Emitter.md#bactorisbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13144](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13144)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bActorLabelEditable](ue_ue.Emitter.md#bactorlabeleditable)

#### Defined in

[ue/ue.d.ts:13183](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13183)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bActorSeamlessTraveled](ue_ue.Emitter.md#bactorseamlesstraveled)

#### Defined in

[ue/ue.d.ts:13139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13139)

___

### bAllowMultipleInstances

• **bAllowMultipleInstances**: `boolean`

#### Defined in

[ue/ue.d.ts:7395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7395)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.Emitter.md#ballowreceivetickeventondedicatedserver)

#### Defined in

[ue/ue.d.ts:13142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13142)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bAllowTickBeforeBeginPlay](ue_ue.Emitter.md#ballowtickbeforebeginplay)

#### Defined in

[ue/ue.d.ts:13129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13129)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bAlwaysRelevant](ue_ue.Emitter.md#balwaysrelevant)

#### Defined in

[ue/ue.d.ts:13120](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13120)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bAutoDestroyWhenFinished](ue_ue.Emitter.md#bautodestroywhenfinished)

#### Defined in

[ue/ue.d.ts:13130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13130)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bBlockInput](ue_ue.Emitter.md#bblockinput)

#### Defined in

[ue/ue.d.ts:13131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13131)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bCanBeDamaged](ue_ue.Emitter.md#bcanbedamaged)

#### Defined in

[ue/ue.d.ts:13132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13132)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bCanBeInCluster](ue_ue.Emitter.md#bcanbeincluster)

#### Defined in

[ue/ue.d.ts:13141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13141)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bCollideWhenPlacing](ue_ue.Emitter.md#bcollidewhenplacing)

#### Defined in

[ue/ue.d.ts:13133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13133)

___

### bCurrentlyActive

• **bCurrentlyActive**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bCurrentlyActive](ue_ue.Emitter.md#bcurrentlyactive)

#### Defined in

[ue/ue.d.ts:7362](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7362)

___

### bDestroyOnSystemFinish

• **bDestroyOnSystemFinish**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bDestroyOnSystemFinish](ue_ue.Emitter.md#bdestroyonsystemfinish)

#### Defined in

[ue/ue.d.ts:7360](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7360)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bEditable](ue_ue.Emitter.md#beditable)

#### Defined in

[ue/ue.d.ts:13184](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13184)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bEnableAutoLODGeneration](ue_ue.Emitter.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:13137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13137)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bExchangedRoles](ue_ue.Emitter.md#bexchangedroles)

#### Defined in

[ue/ue.d.ts:13123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13123)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bFindCameraComponentWhenViewTarget](ue_ue.Emitter.md#bfindcameracomponentwhenviewtarget)

#### Defined in

[ue/ue.d.ts:13134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13134)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.Emitter.md#bgenerateoverlapeventsduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13135)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bHidden](ue_ue.Emitter.md#bhidden)

#### Defined in

[ue/ue.d.ts:13116](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13116)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bHiddenEd](ue_ue.Emitter.md#bhiddened)

#### Defined in

[ue/ue.d.ts:13178](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13178)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bHiddenEdLayer](ue_ue.Emitter.md#bhiddenedlayer)

#### Defined in

[ue/ue.d.ts:13180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13180)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bHiddenEdLevel](ue_ue.Emitter.md#bhiddenedlevel)

#### Defined in

[ue/ue.d.ts:13181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13181)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bHiddenEdTemporary](ue_ue.Emitter.md#bhiddenedtemporary)

#### Defined in

[ue/ue.d.ts:13187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13187)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bIgnoresOriginShifting](ue_ue.Emitter.md#bignoresoriginshifting)

#### Defined in

[ue/ue.d.ts:13136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13136)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bIsEditorOnlyActor](ue_ue.Emitter.md#biseditoronlyactor)

#### Defined in

[ue/ue.d.ts:13138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13138)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bIsEditorPreviewActor](ue_ue.Emitter.md#biseditorpreviewactor)

#### Defined in

[ue/ue.d.ts:13179](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13179)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bListedInSceneOutliner](ue_ue.Emitter.md#blistedinsceneoutliner)

#### Defined in

[ue/ue.d.ts:13185](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13185)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bLockLocation](ue_ue.Emitter.md#blocklocation)

#### Defined in

[ue/ue.d.ts:13182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13182)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bNetLoadOnClient](ue_ue.Emitter.md#bnetloadonclient)

#### Defined in

[ue/ue.d.ts:13124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13124)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bNetStartup](ue_ue.Emitter.md#bnetstartup)

#### Defined in

[ue/ue.d.ts:13118](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13118)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bNetTemporary](ue_ue.Emitter.md#bnettemporary)

#### Defined in

[ue/ue.d.ts:13117](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13117)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bNetUseOwnerRelevancy](ue_ue.Emitter.md#bnetuseownerrelevancy)

#### Defined in

[ue/ue.d.ts:13125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13125)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bOnlyRelevantToOwner](ue_ue.Emitter.md#bonlyrelevanttoowner)

#### Defined in

[ue/ue.d.ts:13119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13119)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bOptimizeBPComponentData](ue_ue.Emitter.md#boptimizebpcomponentdata)

#### Defined in

[ue/ue.d.ts:13186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13186)

___

### bPostUpdateTickGroup

• **bPostUpdateTickGroup**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bPostUpdateTickGroup](ue_ue.Emitter.md#bpostupdatetickgroup)

#### Defined in

[ue/ue.d.ts:7361](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7361)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bRelevantForLevelBounds](ue_ue.Emitter.md#brelevantforlevelbounds)

#### Defined in

[ue/ue.d.ts:13127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13127)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bRelevantForNetworkReplays](ue_ue.Emitter.md#brelevantfornetworkreplays)

#### Defined in

[ue/ue.d.ts:13126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13126)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bReplayRewindable](ue_ue.Emitter.md#breplayrewindable)

#### Defined in

[ue/ue.d.ts:13128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13128)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bReplicateMovement](ue_ue.Emitter.md#breplicatemovement)

#### Defined in

[ue/ue.d.ts:13121](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13121)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bReplicates](ue_ue.Emitter.md#breplicates)

#### Defined in

[ue/ue.d.ts:13140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13140)

___

### bResetWhenRetriggered

• **bResetWhenRetriggered**: `boolean`

#### Defined in

[ue/ue.d.ts:7396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7396)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bTearOff](ue_ue.Emitter.md#btearoff)

#### Defined in

[ue/ue.d.ts:13122](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13122)

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[Activate](ue_ue.Emitter.md#activate)

#### Defined in

[ue/ue.d.ts:7369](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7369)

___

### ActorHasTag

▸ **ActorHasTag**(`Tag`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tag` | `string` |

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ActorHasTag](ue_ue.Emitter.md#actorhastag)

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

[Emitter](ue_ue.Emitter.md).[AddComponent](ue_ue.Emitter.md#addcomponent)

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

[Emitter](ue_ue.Emitter.md).[AddTickPrerequisiteActor](ue_ue.Emitter.md#addtickprerequisiteactor)

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

[Emitter](ue_ue.Emitter.md).[AddTickPrerequisiteComponent](ue_ue.Emitter.md#addtickprerequisitecomponent)

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

[Emitter](ue_ue.Emitter.md).[CreateDefaultSubobject](ue_ue.Emitter.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[Deactivate](ue_ue.Emitter.md#deactivate)

#### Defined in

[ue/ue.d.ts:7370](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7370)

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

[Emitter](ue_ue.Emitter.md).[DetachRootComponentFromParent](ue_ue.Emitter.md#detachrootcomponentfromparent)

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

[Emitter](ue_ue.Emitter.md).[DisableInput](ue_ue.Emitter.md#disableinput)

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

[Emitter](ue_ue.Emitter.md).[EnableInput](ue_ue.Emitter.md#enableinput)

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

[Emitter](ue_ue.Emitter.md).[ExecuteUbergraph](ue_ue.Emitter.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[FlushNetDormancy](ue_ue.Emitter.md#flushnetdormancy)

#### Defined in

[ue/ue.d.ts:13214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13214)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ForceNetUpdate](ue_ue.Emitter.md#forcenetupdate)

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

[Emitter](ue_ue.Emitter.md).[GetActorBounds](ue_ue.Emitter.md#getactorbounds)

#### Defined in

[ue/ue.d.ts:13216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13216)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorEnableCollision](ue_ue.Emitter.md#getactorenablecollision)

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

[Emitter](ue_ue.Emitter.md).[GetActorEyesViewPoint](ue_ue.Emitter.md#getactoreyesviewpoint)

#### Defined in

[ue/ue.d.ts:13218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13218)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorForwardVector](ue_ue.Emitter.md#getactorforwardvector)

#### Defined in

[ue/ue.d.ts:13219](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13219)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorLabel](ue_ue.Emitter.md#getactorlabel)

#### Defined in

[ue/ue.d.ts:13220](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13220)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorRelativeScale3D](ue_ue.Emitter.md#getactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13221](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13221)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorRightVector](ue_ue.Emitter.md#getactorrightvector)

#### Defined in

[ue/ue.d.ts:13222](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13222)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorScale3D](ue_ue.Emitter.md#getactorscale3d)

#### Defined in

[ue/ue.d.ts:13223](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13223)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorTickInterval](ue_ue.Emitter.md#getactortickinterval)

#### Defined in

[ue/ue.d.ts:13224](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13224)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorTimeDilation](ue_ue.Emitter.md#getactortimedilation)

#### Defined in

[ue/ue.d.ts:13225](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13225)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorUpVector](ue_ue.Emitter.md#getactorupvector)

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

[Emitter](ue_ue.Emitter.md).[GetAllChildActors](ue_ue.Emitter.md#getallchildactors)

#### Defined in

[ue/ue.d.ts:13227](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13227)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetAttachParentActor](ue_ue.Emitter.md#getattachparentactor)

#### Defined in

[ue/ue.d.ts:13229](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13229)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetAttachParentSocketName](ue_ue.Emitter.md#getattachparentsocketname)

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

[Emitter](ue_ue.Emitter.md).[GetAttachedActors](ue_ue.Emitter.md#getattachedactors)

#### Defined in

[ue/ue.d.ts:13228](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13228)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetClass](ue_ue.Emitter.md#getclass)

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

[Emitter](ue_ue.Emitter.md).[GetComponentByClass](ue_ue.Emitter.md#getcomponentbyclass)

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

[Emitter](ue_ue.Emitter.md).[GetComponentsByInterface](ue_ue.Emitter.md#getcomponentsbyinterface)

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

[Emitter](ue_ue.Emitter.md).[GetComponentsByTag](ue_ue.Emitter.md#getcomponentsbytag)

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

[Emitter](ue_ue.Emitter.md).[GetDistanceTo](ue_ue.Emitter.md#getdistanceto)

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

[Emitter](ue_ue.Emitter.md).[GetDotProductTo](ue_ue.Emitter.md#getdotproductto)

#### Defined in

[ue/ue.d.ts:13235](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13235)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetFolderPath](ue_ue.Emitter.md#getfolderpath)

#### Defined in

[ue/ue.d.ts:13236](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13236)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetGameTimeSinceCreation](ue_ue.Emitter.md#getgametimesincecreation)

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

[Emitter](ue_ue.Emitter.md).[GetHorizontalDistanceTo](ue_ue.Emitter.md#gethorizontaldistanceto)

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

[Emitter](ue_ue.Emitter.md).[GetHorizontalDotProductTo](ue_ue.Emitter.md#gethorizontaldotproductto)

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

[Emitter](ue_ue.Emitter.md).[GetInputAxisKeyValue](ue_ue.Emitter.md#getinputaxiskeyvalue)

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

[Emitter](ue_ue.Emitter.md).[GetInputAxisValue](ue_ue.Emitter.md#getinputaxisvalue)

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

[Emitter](ue_ue.Emitter.md).[GetInputVectorAxisValue](ue_ue.Emitter.md#getinputvectoraxisvalue)

#### Defined in

[ue/ue.d.ts:13242](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13242)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetInstigator](ue_ue.Emitter.md#getinstigator)

#### Defined in

[ue/ue.d.ts:13243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13243)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetInstigatorController](ue_ue.Emitter.md#getinstigatorcontroller)

#### Defined in

[ue/ue.d.ts:13244](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13244)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetLifeSpan](ue_ue.Emitter.md#getlifespan)

#### Defined in

[ue/ue.d.ts:13245](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13245)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetLocalRole](ue_ue.Emitter.md#getlocalrole)

#### Defined in

[ue/ue.d.ts:13246](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13246)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetName](ue_ue.Emitter.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetOuter](ue_ue.Emitter.md#getouter)

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

[Emitter](ue_ue.Emitter.md).[GetOverlappingActors](ue_ue.Emitter.md#getoverlappingactors)

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

[Emitter](ue_ue.Emitter.md).[GetOverlappingComponents](ue_ue.Emitter.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:13248](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13248)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetOwner](ue_ue.Emitter.md#getowner)

#### Defined in

[ue/ue.d.ts:13249](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13249)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetParentActor](ue_ue.Emitter.md#getparentactor)

#### Defined in

[ue/ue.d.ts:13250](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13250)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetParentComponent](ue_ue.Emitter.md#getparentcomponent)

#### Defined in

[ue/ue.d.ts:13251](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13251)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetRemoteRole](ue_ue.Emitter.md#getremoterole)

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

[Emitter](ue_ue.Emitter.md).[GetSquaredDistanceTo](ue_ue.Emitter.md#getsquareddistanceto)

#### Defined in

[ue/ue.d.ts:13253](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13253)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetTickableWhenPaused](ue_ue.Emitter.md#gettickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13254](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13254)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetTransform](ue_ue.Emitter.md#gettransform)

#### Defined in

[ue/ue.d.ts:13255](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13255)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetVelocity](ue_ue.Emitter.md#getvelocity)

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

[Emitter](ue_ue.Emitter.md).[GetVerticalDistanceTo](ue_ue.Emitter.md#getverticaldistanceto)

#### Defined in

[ue/ue.d.ts:13257](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13257)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetWorld](ue_ue.Emitter.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[HasAuthority](ue_ue.Emitter.md#hasauthority)

#### Defined in

[ue/ue.d.ts:13258](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13258)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[IsActive](ue_ue.Emitter.md#isactive)

#### Defined in

[ue/ue.d.ts:7371](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7371)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[IsActorBeingDestroyed](ue_ue.Emitter.md#isactorbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13259](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13259)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[IsActorTickEnabled](ue_ue.Emitter.md#isactortickenabled)

#### Defined in

[ue/ue.d.ts:13260](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13260)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[IsChildActor](ue_ue.Emitter.md#ischildactor)

#### Defined in

[ue/ue.d.ts:13261](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13261)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[IsEditable](ue_ue.Emitter.md#iseditable)

#### Defined in

[ue/ue.d.ts:13262](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13262)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[IsHiddenEd](ue_ue.Emitter.md#ishiddened)

#### Defined in

[ue/ue.d.ts:13263](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13263)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[IsHiddenEdAtStartup](ue_ue.Emitter.md#ishiddenedatstartup)

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

[Emitter](ue_ue.Emitter.md).[IsOverlappingActor](ue_ue.Emitter.md#isoverlappingactor)

#### Defined in

[ue/ue.d.ts:13265](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13265)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[IsSelectable](ue_ue.Emitter.md#isselectable)

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

[Emitter](ue_ue.Emitter.md).[IsTemporarilyHiddenInEditor](ue_ue.Emitter.md#istemporarilyhiddenineditor)

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

[Emitter](ue_ue.Emitter.md).[K2_AddActorLocalOffset](ue_ue.Emitter.md#k2_addactorlocaloffset)

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

[Emitter](ue_ue.Emitter.md).[K2_AddActorLocalRotation](ue_ue.Emitter.md#k2_addactorlocalrotation)

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

[Emitter](ue_ue.Emitter.md).[K2_AddActorLocalTransform](ue_ue.Emitter.md#k2_addactorlocaltransform)

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

[Emitter](ue_ue.Emitter.md).[K2_AddActorWorldOffset](ue_ue.Emitter.md#k2_addactorworldoffset)

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

[Emitter](ue_ue.Emitter.md).[K2_AddActorWorldRotation](ue_ue.Emitter.md#k2_addactorworldrotation)

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

[Emitter](ue_ue.Emitter.md).[K2_AddActorWorldTransform](ue_ue.Emitter.md#k2_addactorworldtransform)

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

[Emitter](ue_ue.Emitter.md).[K2_AttachRootComponentTo](ue_ue.Emitter.md#k2_attachrootcomponentto)

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

[Emitter](ue_ue.Emitter.md).[K2_AttachRootComponentToActor](ue_ue.Emitter.md#k2_attachrootcomponenttoactor)

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

[Emitter](ue_ue.Emitter.md).[K2_AttachToActor](ue_ue.Emitter.md#k2_attachtoactor)

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

[Emitter](ue_ue.Emitter.md).[K2_AttachToComponent](ue_ue.Emitter.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:13277](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13277)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[K2_DestroyActor](ue_ue.Emitter.md#k2_destroyactor)

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

[Emitter](ue_ue.Emitter.md).[K2_DestroyComponent](ue_ue.Emitter.md#k2_destroycomponent)

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

[Emitter](ue_ue.Emitter.md).[K2_DetachFromActor](ue_ue.Emitter.md#k2_detachfromactor)

#### Defined in

[ue/ue.d.ts:13280](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13280)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[K2_GetActorLocation](ue_ue.Emitter.md#k2_getactorlocation)

#### Defined in

[ue/ue.d.ts:13281](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13281)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[K2_GetActorRotation](ue_ue.Emitter.md#k2_getactorrotation)

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

[Emitter](ue_ue.Emitter.md).[K2_GetComponentsByClass](ue_ue.Emitter.md#k2_getcomponentsbyclass)

#### Defined in

[ue/ue.d.ts:13283](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13283)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[K2_GetRootComponent](ue_ue.Emitter.md#k2_getrootcomponent)

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

[Emitter](ue_ue.Emitter.md).[K2_OnBecomeViewTarget](ue_ue.Emitter.md#k2_onbecomeviewtarget)

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

[Emitter](ue_ue.Emitter.md).[K2_OnEndViewTarget](ue_ue.Emitter.md#k2_onendviewtarget)

#### Defined in

[ue/ue.d.ts:13286](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13286)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[K2_OnReset](ue_ue.Emitter.md#k2_onreset)

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

[Emitter](ue_ue.Emitter.md).[K2_SetActorLocation](ue_ue.Emitter.md#k2_setactorlocation)

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

[Emitter](ue_ue.Emitter.md).[K2_SetActorLocationAndRotation](ue_ue.Emitter.md#k2_setactorlocationandrotation)

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

[Emitter](ue_ue.Emitter.md).[K2_SetActorRelativeLocation](ue_ue.Emitter.md#k2_setactorrelativelocation)

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

[Emitter](ue_ue.Emitter.md).[K2_SetActorRelativeRotation](ue_ue.Emitter.md#k2_setactorrelativerotation)

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

[Emitter](ue_ue.Emitter.md).[K2_SetActorRelativeTransform](ue_ue.Emitter.md#k2_setactorrelativetransform)

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

[Emitter](ue_ue.Emitter.md).[K2_SetActorRotation](ue_ue.Emitter.md#k2_setactorrotation)

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

[Emitter](ue_ue.Emitter.md).[K2_SetActorTransform](ue_ue.Emitter.md#k2_setactortransform)

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

[Emitter](ue_ue.Emitter.md).[K2_TeleportTo](ue_ue.Emitter.md#k2_teleportto)

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

[Emitter](ue_ue.Emitter.md).[MakeMIDForMaterial](ue_ue.Emitter.md#makemidformaterial)

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

[Emitter](ue_ue.Emitter.md).[MakeNoise](ue_ue.Emitter.md#makenoise)

#### Defined in

[ue/ue.d.ts:13297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13297)

___

### OnParticleSystemFinished

▸ **OnParticleSystemFinished**(`FinishedComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FinishedComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)\> |

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnParticleSystemFinished](ue_ue.Emitter.md#onparticlesystemfinished)

#### Defined in

[ue/ue.d.ts:7372](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7372)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnRep_AttachmentReplication](ue_ue.Emitter.md#onrep_attachmentreplication)

#### Defined in

[ue/ue.d.ts:13298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13298)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnRep_Instigator](ue_ue.Emitter.md#onrep_instigator)

#### Defined in

[ue/ue.d.ts:13299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13299)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnRep_Owner](ue_ue.Emitter.md#onrep_owner)

#### Defined in

[ue/ue.d.ts:13300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13300)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnRep_ReplicateMovement](ue_ue.Emitter.md#onrep_replicatemovement)

#### Defined in

[ue/ue.d.ts:13302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13302)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnRep_ReplicatedMovement](ue_ue.Emitter.md#onrep_replicatedmovement)

#### Defined in

[ue/ue.d.ts:13301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13301)

___

### OnRep\_bCurrentlyActive

▸ **OnRep_bCurrentlyActive**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnRep_bCurrentlyActive](ue_ue.Emitter.md#onrep_bcurrentlyactive)

#### Defined in

[ue/ue.d.ts:7373](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7373)

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

[Emitter](ue_ue.Emitter.md).[PrestreamTextures](ue_ue.Emitter.md#prestreamtextures)

#### Defined in

[ue/ue.d.ts:13303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13303)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ReceiveActorBeginCursorOver](ue_ue.Emitter.md#receiveactorbegincursorover)

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

[Emitter](ue_ue.Emitter.md).[ReceiveActorBeginOverlap](ue_ue.Emitter.md#receiveactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13305)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ReceiveActorEndCursorOver](ue_ue.Emitter.md#receiveactorendcursorover)

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

[Emitter](ue_ue.Emitter.md).[ReceiveActorEndOverlap](ue_ue.Emitter.md#receiveactorendoverlap)

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

[Emitter](ue_ue.Emitter.md).[ReceiveActorOnClicked](ue_ue.Emitter.md#receiveactoronclicked)

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

[Emitter](ue_ue.Emitter.md).[ReceiveActorOnInputTouchBegin](ue_ue.Emitter.md#receiveactoroninputtouchbegin)

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

[Emitter](ue_ue.Emitter.md).[ReceiveActorOnInputTouchEnd](ue_ue.Emitter.md#receiveactoroninputtouchend)

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

[Emitter](ue_ue.Emitter.md).[ReceiveActorOnInputTouchEnter](ue_ue.Emitter.md#receiveactoroninputtouchenter)

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

[Emitter](ue_ue.Emitter.md).[ReceiveActorOnInputTouchLeave](ue_ue.Emitter.md#receiveactoroninputtouchleave)

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

[Emitter](ue_ue.Emitter.md).[ReceiveActorOnReleased](ue_ue.Emitter.md#receiveactoronreleased)

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

[Emitter](ue_ue.Emitter.md).[ReceiveAnyDamage](ue_ue.Emitter.md#receiveanydamage)

#### Defined in

[ue/ue.d.ts:13314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13314)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ReceiveBeginPlay](ue_ue.Emitter.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:13315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13315)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ReceiveDestroyed](ue_ue.Emitter.md#receivedestroyed)

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

[Emitter](ue_ue.Emitter.md).[ReceiveEndPlay](ue_ue.Emitter.md#receiveendplay)

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

[Emitter](ue_ue.Emitter.md).[ReceiveHit](ue_ue.Emitter.md#receivehit)

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

[Emitter](ue_ue.Emitter.md).[ReceivePointDamage](ue_ue.Emitter.md#receivepointdamage)

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

[Emitter](ue_ue.Emitter.md).[ReceiveRadialDamage](ue_ue.Emitter.md#receiveradialdamage)

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

[Emitter](ue_ue.Emitter.md).[ReceiveTick](ue_ue.Emitter.md#receivetick)

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

[Emitter](ue_ue.Emitter.md).[RemoveTickPrerequisiteActor](ue_ue.Emitter.md#removetickprerequisiteactor)

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

[Emitter](ue_ue.Emitter.md).[RemoveTickPrerequisiteComponent](ue_ue.Emitter.md#removetickprerequisitecomponent)

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

[Emitter](ue_ue.Emitter.md).[SetActorEnableCollision](ue_ue.Emitter.md#setactorenablecollision)

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

[Emitter](ue_ue.Emitter.md).[SetActorHiddenInGame](ue_ue.Emitter.md#setactorhiddeningame)

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

[Emitter](ue_ue.Emitter.md).[SetActorLabel](ue_ue.Emitter.md#setactorlabel)

#### Defined in

[ue/ue.d.ts:13326](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13326)

___

### SetActorParameter

▸ **SetActorParameter**(`ParameterName`, `Param`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `Param` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[SetActorParameter](ue_ue.Emitter.md#setactorparameter)

#### Defined in

[ue/ue.d.ts:7374](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7374)

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

[Emitter](ue_ue.Emitter.md).[SetActorRelativeScale3D](ue_ue.Emitter.md#setactorrelativescale3d)

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

[Emitter](ue_ue.Emitter.md).[SetActorScale3D](ue_ue.Emitter.md#setactorscale3d)

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

[Emitter](ue_ue.Emitter.md).[SetActorTickEnabled](ue_ue.Emitter.md#setactortickenabled)

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

[Emitter](ue_ue.Emitter.md).[SetActorTickInterval](ue_ue.Emitter.md#setactortickinterval)

#### Defined in

[ue/ue.d.ts:13330](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13330)

___

### SetColorParameter

▸ **SetColorParameter**(`ParameterName`, `Param`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `Param` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[SetColorParameter](ue_ue.Emitter.md#setcolorparameter)

#### Defined in

[ue/ue.d.ts:7375](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7375)

___

### SetFloatParameter

▸ **SetFloatParameter**(`ParameterName`, `Param`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `Param` | `number` |

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[SetFloatParameter](ue_ue.Emitter.md#setfloatparameter)

#### Defined in

[ue/ue.d.ts:7376](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7376)

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

[Emitter](ue_ue.Emitter.md).[SetFolderPath](ue_ue.Emitter.md#setfolderpath)

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

[Emitter](ue_ue.Emitter.md).[SetIsTemporarilyHiddenInEditor](ue_ue.Emitter.md#setistemporarilyhiddenineditor)

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

[Emitter](ue_ue.Emitter.md).[SetLifeSpan](ue_ue.Emitter.md#setlifespan)

#### Defined in

[ue/ue.d.ts:13333](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13333)

___

### SetMaterialParameter

▸ **SetMaterialParameter**(`ParameterName`, `Param`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `Param` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[SetMaterialParameter](ue_ue.Emitter.md#setmaterialparameter)

#### Defined in

[ue/ue.d.ts:7377](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7377)

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

[Emitter](ue_ue.Emitter.md).[SetNetDormancy](ue_ue.Emitter.md#setnetdormancy)

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

[Emitter](ue_ue.Emitter.md).[SetOwner](ue_ue.Emitter.md#setowner)

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

[Emitter](ue_ue.Emitter.md).[SetReplicateMovement](ue_ue.Emitter.md#setreplicatemovement)

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

[Emitter](ue_ue.Emitter.md).[SetReplicates](ue_ue.Emitter.md#setreplicates)

#### Defined in

[ue/ue.d.ts:13337](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13337)

___

### SetTemplate

▸ **SetTemplate**(`NewTemplate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTemplate` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ParticleSystem`](ue_ue.ParticleSystem.md)\> |

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[SetTemplate](ue_ue.Emitter.md#settemplate)

#### Defined in

[ue/ue.d.ts:7378](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7378)

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

[Emitter](ue_ue.Emitter.md).[SetTickGroup](ue_ue.Emitter.md#settickgroup)

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

[Emitter](ue_ue.Emitter.md).[SetTickableWhenPaused](ue_ue.Emitter.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13338](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13338)

___

### SetVectorParameter

▸ **SetVectorParameter**(`ParameterName`, `Param`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `Param` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[SetVectorParameter](ue_ue.Emitter.md#setvectorparameter)

#### Defined in

[ue/ue.d.ts:7379](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7379)

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

[Emitter](ue_ue.Emitter.md).[SnapRootComponentTo](ue_ue.Emitter.md#snaprootcomponentto)

#### Defined in

[ue/ue.d.ts:13340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13340)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[TearOff](ue_ue.Emitter.md#tearoff)

#### Defined in

[ue/ue.d.ts:13341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13341)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ToggleActive](ue_ue.Emitter.md#toggleactive)

#### Defined in

[ue/ue.d.ts:7380](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7380)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[UserConstructionScript](ue_ue.Emitter.md#userconstructionscript)

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

[Emitter](ue_ue.Emitter.md).[WasRecentlyRendered](ue_ue.Emitter.md#wasrecentlyrendered)

#### Defined in

[ue/ue.d.ts:13343](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13343)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EmitterCameraLensEffectBase`](ue_ue.EmitterCameraLensEffectBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EmitterCameraLensEffectBase`](ue_ue.EmitterCameraLensEffectBase.md)

#### Overrides

[Emitter](ue_ue.Emitter.md).[Find](ue_ue.Emitter.md#find)

#### Defined in

[ue/ue.d.ts:7400](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7400)

___

### Load

▸ `Static` **Load**(`InName`): [`EmitterCameraLensEffectBase`](ue_ue.EmitterCameraLensEffectBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EmitterCameraLensEffectBase`](ue_ue.EmitterCameraLensEffectBase.md)

#### Overrides

[Emitter](ue_ue.Emitter.md).[Load](ue_ue.Emitter.md#load)

#### Defined in

[ue/ue.d.ts:7401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7401)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Emitter](ue_ue.Emitter.md).[StaticClass](ue_ue.Emitter.md#staticclass)

#### Defined in

[ue/ue.d.ts:7399](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7399)
