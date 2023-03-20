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

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ActorLabel](ue_ue.Emitter.md#actorlabel)

___

### ArrowComponent

• **ArrowComponent**: [`ArrowComponent`](ue_ue.ArrowComponent.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ArrowComponent](ue_ue.Emitter.md#arrowcomponent)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[AttachmentReplication](ue_ue.Emitter.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[AutoReceiveInput](ue_ue.Emitter.md#autoreceiveinput)

___

### BaseCamera

• **BaseCamera**: [`PlayerCameraManager`](ue_ue.PlayerCameraManager.md)

___

### BaseFOV

• **BaseFOV**: `number`

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[BlueprintCreatedComponents](ue_ue.Emitter.md#blueprintcreatedcomponents)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[Children](ue_ue.Emitter.md#children)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ControllingMatineeActors](ue_ue.Emitter.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[CustomTimeDilation](ue_ue.Emitter.md#customtimedilation)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.Emitter.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### DistFromCamera

• **DistFromCamera**: `number`

___

### EmittersToTreatAsSame

• **EmittersToTreatAsSame**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Class`](ue_ue.Class.md)\>

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[FolderPath](ue_ue.Emitter.md#folderpath)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GroupActor](ue_ue.Emitter.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[HiddenEditorViews](ue_ue.Emitter.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[InitialLifeSpan](ue_ue.Emitter.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[InputComponent](ue_ue.Emitter.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[InputPriority](ue_ue.Emitter.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[InstanceComponents](ue_ue.Emitter.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[Instigator](ue_ue.Emitter.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[Layers](ue_ue.Emitter.md#layers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[MinNetUpdateFrequency](ue_ue.Emitter.md#minnetupdatefrequency)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[NetCullDistanceSquared](ue_ue.Emitter.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[NetDormancy](ue_ue.Emitter.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[NetDriverName](ue_ue.Emitter.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[NetPriority](ue_ue.Emitter.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[NetTag](ue_ue.Emitter.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[NetUpdateFrequency](ue_ue.Emitter.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnActorBeginOverlap](ue_ue.Emitter.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnActorEndOverlap](ue_ue.Emitter.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnActorHit](ue_ue.Emitter.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnBeginCursorOver](ue_ue.Emitter.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnClicked](ue_ue.Emitter.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnDestroyed](ue_ue.Emitter.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnEndCursorOver](ue_ue.Emitter.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnEndPlay](ue_ue.Emitter.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnInputTouchBegin](ue_ue.Emitter.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnInputTouchEnd](ue_ue.Emitter.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnInputTouchEnter](ue_ue.Emitter.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnInputTouchLeave](ue_ue.Emitter.md#oninputtouchleave)

___

### OnParticleBurst

• **OnParticleBurst**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`EventName`: `string`, `EmitterTime`: `number`, `ParticleCount`: `number`) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnParticleBurst](ue_ue.Emitter.md#onparticleburst)

___

### OnParticleCollide

• **OnParticleCollide**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`EventName`: `string`, `EmitterTime`: `number`, `ParticleTime`: `number`, `Location`: [`Vector`](ue_ue_s.Vector.md), `Velocity`: [`Vector`](ue_ue_s.Vector.md), `Direction`: [`Vector`](ue_ue_s.Vector.md), `Normal`: [`Vector`](ue_ue_s.Vector.md), `BoneName`: `string`, `PhysMat`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnParticleCollide](ue_ue.Emitter.md#onparticlecollide)

___

### OnParticleDeath

• **OnParticleDeath**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`EventName`: `string`, `EmitterTime`: `number`, `ParticleTime`: `number`, `Location`: [`Vector`](ue_ue_s.Vector.md), `Velocity`: [`Vector`](ue_ue_s.Vector.md), `Direction`: [`Vector`](ue_ue_s.Vector.md)) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnParticleDeath](ue_ue.Emitter.md#onparticledeath)

___

### OnParticleSpawn

• **OnParticleSpawn**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`EventName`: `string`, `EmitterTime`: `number`, `Location`: [`Vector`](ue_ue_s.Vector.md), `Velocity`: [`Vector`](ue_ue_s.Vector.md)) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnParticleSpawn](ue_ue.Emitter.md#onparticlespawn)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnReleased](ue_ue.Emitter.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnTakeAnyDamage](ue_ue.Emitter.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnTakePointDamage](ue_ue.Emitter.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnTakeRadialDamage](ue_ue.Emitter.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[Owner](ue_ue.Emitter.md#owner)

___

### PS\_CameraEffect

• **PS\_CameraEffect**: [`ParticleSystem`](ue_ue.ParticleSystem.md)

___

### PS\_CameraEffectNonExtremeContent

• **PS\_CameraEffectNonExtremeContent**: [`ParticleSystem`](ue_ue.ParticleSystem.md)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ParentComponent](ue_ue.Emitter.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ParentComponentActor](ue_ue.Emitter.md#parentcomponentactor)

___

### ParticleSystemComponent

• **ParticleSystemComponent**: [`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ParticleSystemComponent](ue_ue.Emitter.md#particlesystemcomponent)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[PivotOffset](ue_ue.Emitter.md#pivotoffset)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[PrimaryActorTick](ue_ue.Emitter.md#primaryactortick)

___

### RelativeTransform

• **RelativeTransform**: [`Transform`](ue_ue_s.Transform.md)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[RemoteRole](ue_ue.Emitter.md#remoterole)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ReplicatedMovement](ue_ue.Emitter.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[Role](ue_ue.Emitter.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[RootComponent](ue_ue.Emitter.md#rootcomponent)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[SpawnCollisionHandlingMethod](ue_ue.Emitter.md#spawncollisionhandlingmethod)

___

### SpriteComponent

• **SpriteComponent**: [`BillboardComponent`](ue_ue.BillboardComponent.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[SpriteComponent](ue_ue.Emitter.md#spritecomponent)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[SpriteScale](ue_ue.Emitter.md#spritescale)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Emitter](ue_ue.Emitter.md).[Tags](ue_ue.Emitter.md#tags)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.Emitter.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[__tid_Actor__](ue_ue.Emitter.md#__tid_actor__)

___

### \_\_tid\_EmitterCameraLensEffectBase\_\_

• **\_\_tid\_EmitterCameraLensEffectBase\_\_**: `boolean`

___

### \_\_tid\_Emitter\_\_

• **\_\_tid\_Emitter\_\_**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[__tid_Emitter__](ue_ue.Emitter.md#__tid_emitter__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[__tid_Object__](ue_ue.Emitter.md#__tid_object__)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bActorEnableCollision](ue_ue.Emitter.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bActorIsBeingDestroyed](ue_ue.Emitter.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bActorLabelEditable](ue_ue.Emitter.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bActorSeamlessTraveled](ue_ue.Emitter.md#bactorseamlesstraveled)

___

### bAllowMultipleInstances

• **bAllowMultipleInstances**: `boolean`

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.Emitter.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bAllowTickBeforeBeginPlay](ue_ue.Emitter.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bAlwaysRelevant](ue_ue.Emitter.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bAutoDestroyWhenFinished](ue_ue.Emitter.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bBlockInput](ue_ue.Emitter.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bCanBeDamaged](ue_ue.Emitter.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bCanBeInCluster](ue_ue.Emitter.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bCollideWhenPlacing](ue_ue.Emitter.md#bcollidewhenplacing)

___

### bCurrentlyActive

• **bCurrentlyActive**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bCurrentlyActive](ue_ue.Emitter.md#bcurrentlyactive)

___

### bDestroyOnSystemFinish

• **bDestroyOnSystemFinish**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bDestroyOnSystemFinish](ue_ue.Emitter.md#bdestroyonsystemfinish)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bEditable](ue_ue.Emitter.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bEnableAutoLODGeneration](ue_ue.Emitter.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bExchangedRoles](ue_ue.Emitter.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bFindCameraComponentWhenViewTarget](ue_ue.Emitter.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.Emitter.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bHidden](ue_ue.Emitter.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bHiddenEd](ue_ue.Emitter.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bHiddenEdLayer](ue_ue.Emitter.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bHiddenEdLevel](ue_ue.Emitter.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bHiddenEdTemporary](ue_ue.Emitter.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bIgnoresOriginShifting](ue_ue.Emitter.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bIsEditorOnlyActor](ue_ue.Emitter.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bIsEditorPreviewActor](ue_ue.Emitter.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bListedInSceneOutliner](ue_ue.Emitter.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bLockLocation](ue_ue.Emitter.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bNetLoadOnClient](ue_ue.Emitter.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bNetStartup](ue_ue.Emitter.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bNetTemporary](ue_ue.Emitter.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bNetUseOwnerRelevancy](ue_ue.Emitter.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bOnlyRelevantToOwner](ue_ue.Emitter.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bOptimizeBPComponentData](ue_ue.Emitter.md#boptimizebpcomponentdata)

___

### bPostUpdateTickGroup

• **bPostUpdateTickGroup**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bPostUpdateTickGroup](ue_ue.Emitter.md#bpostupdatetickgroup)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bRelevantForLevelBounds](ue_ue.Emitter.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bRelevantForNetworkReplays](ue_ue.Emitter.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bReplayRewindable](ue_ue.Emitter.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bReplicateMovement](ue_ue.Emitter.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bReplicates](ue_ue.Emitter.md#breplicates)

___

### bResetWhenRetriggered

• **bResetWhenRetriggered**: `boolean`

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[bTearOff](ue_ue.Emitter.md#btearoff)

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[Activate](ue_ue.Emitter.md#activate)

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

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[Deactivate](ue_ue.Emitter.md#deactivate)

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

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[FlushNetDormancy](ue_ue.Emitter.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ForceNetUpdate](ue_ue.Emitter.md#forcenetupdate)

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

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorEnableCollision](ue_ue.Emitter.md#getactorenablecollision)

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

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorForwardVector](ue_ue.Emitter.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorLabel](ue_ue.Emitter.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorRelativeScale3D](ue_ue.Emitter.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorRightVector](ue_ue.Emitter.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorScale3D](ue_ue.Emitter.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorTickInterval](ue_ue.Emitter.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorTimeDilation](ue_ue.Emitter.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetActorUpVector](ue_ue.Emitter.md#getactorupvector)

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

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetAttachParentActor](ue_ue.Emitter.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetAttachParentSocketName](ue_ue.Emitter.md#getattachparentsocketname)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetClass](ue_ue.Emitter.md#getclass)

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

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetFolderPath](ue_ue.Emitter.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetGameTimeSinceCreation](ue_ue.Emitter.md#getgametimesincecreation)

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

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetInstigator](ue_ue.Emitter.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetInstigatorController](ue_ue.Emitter.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetLifeSpan](ue_ue.Emitter.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetLocalRole](ue_ue.Emitter.md#getlocalrole)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetName](ue_ue.Emitter.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetOuter](ue_ue.Emitter.md#getouter)

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

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetOwner](ue_ue.Emitter.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetParentActor](ue_ue.Emitter.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetParentComponent](ue_ue.Emitter.md#getparentcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetRemoteRole](ue_ue.Emitter.md#getremoterole)

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

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetTickableWhenPaused](ue_ue.Emitter.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetTransform](ue_ue.Emitter.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetVelocity](ue_ue.Emitter.md#getvelocity)

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

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[GetWorld](ue_ue.Emitter.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[HasAuthority](ue_ue.Emitter.md#hasauthority)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[IsActive](ue_ue.Emitter.md#isactive)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[IsActorBeingDestroyed](ue_ue.Emitter.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[IsActorTickEnabled](ue_ue.Emitter.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[IsChildActor](ue_ue.Emitter.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[IsEditable](ue_ue.Emitter.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[IsHiddenEd](ue_ue.Emitter.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[IsHiddenEdAtStartup](ue_ue.Emitter.md#ishiddenedatstartup)

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

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[IsSelectable](ue_ue.Emitter.md#isselectable)

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

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[K2_DestroyActor](ue_ue.Emitter.md#k2_destroyactor)

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

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[K2_GetActorLocation](ue_ue.Emitter.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[K2_GetActorRotation](ue_ue.Emitter.md#k2_getactorrotation)

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

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Emitter](ue_ue.Emitter.md).[K2_GetRootComponent](ue_ue.Emitter.md#k2_getrootcomponent)

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

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[K2_OnReset](ue_ue.Emitter.md#k2_onreset)

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

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnRep_AttachmentReplication](ue_ue.Emitter.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnRep_Instigator](ue_ue.Emitter.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnRep_Owner](ue_ue.Emitter.md#onrep_owner)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnRep_ReplicateMovement](ue_ue.Emitter.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnRep_ReplicatedMovement](ue_ue.Emitter.md#onrep_replicatedmovement)

___

### OnRep\_bCurrentlyActive

▸ **OnRep_bCurrentlyActive**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[OnRep_bCurrentlyActive](ue_ue.Emitter.md#onrep_bcurrentlyactive)

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

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ReceiveActorBeginCursorOver](ue_ue.Emitter.md#receiveactorbegincursorover)

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

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ReceiveActorEndCursorOver](ue_ue.Emitter.md#receiveactorendcursorover)

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

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ReceiveBeginPlay](ue_ue.Emitter.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ReceiveDestroyed](ue_ue.Emitter.md#receivedestroyed)

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

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[TearOff](ue_ue.Emitter.md#tearoff)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[ToggleActive](ue_ue.Emitter.md#toggleactive)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[Emitter](ue_ue.Emitter.md).[UserConstructionScript](ue_ue.Emitter.md#userconstructionscript)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Emitter](ue_ue.Emitter.md).[StaticClass](ue_ue.Emitter.md#staticclass)
