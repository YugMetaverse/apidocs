[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InteractiveFoliageActor

# Class: InteractiveFoliageActor

[ue/ue](../modules/ue_ue.md).InteractiveFoliageActor

## Hierarchy

- [`StaticMeshActor`](ue_ue.StaticMeshActor.md)

  ↳ **`InteractiveFoliageActor`**

## Table of contents

### Constructors

- [constructor](ue_ue.InteractiveFoliageActor.md#constructor)

### Properties

- [ActorLabel](ue_ue.InteractiveFoliageActor.md#actorlabel)
- [AttachmentReplication](ue_ue.InteractiveFoliageActor.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.InteractiveFoliageActor.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.InteractiveFoliageActor.md#blueprintcreatedcomponents)
- [CapsuleComponent](ue_ue.InteractiveFoliageActor.md#capsulecomponent)
- [Children](ue_ue.InteractiveFoliageActor.md#children)
- [ControllingMatineeActors](ue_ue.InteractiveFoliageActor.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.InteractiveFoliageActor.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.InteractiveFoliageActor.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.InteractiveFoliageActor.md#folderpath)
- [FoliageDamageImpulseScale](ue_ue.InteractiveFoliageActor.md#foliagedamageimpulsescale)
- [FoliageDamping](ue_ue.InteractiveFoliageActor.md#foliagedamping)
- [FoliageForce](ue_ue.InteractiveFoliageActor.md#foliageforce)
- [FoliagePosition](ue_ue.InteractiveFoliageActor.md#foliageposition)
- [FoliageStiffness](ue_ue.InteractiveFoliageActor.md#foliagestiffness)
- [FoliageStiffnessQuadratic](ue_ue.InteractiveFoliageActor.md#foliagestiffnessquadratic)
- [FoliageTouchImpulseScale](ue_ue.InteractiveFoliageActor.md#foliagetouchimpulsescale)
- [FoliageVelocity](ue_ue.InteractiveFoliageActor.md#foliagevelocity)
- [GroupActor](ue_ue.InteractiveFoliageActor.md#groupactor)
- [HiddenEditorViews](ue_ue.InteractiveFoliageActor.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.InteractiveFoliageActor.md#initiallifespan)
- [InputComponent](ue_ue.InteractiveFoliageActor.md#inputcomponent)
- [InputPriority](ue_ue.InteractiveFoliageActor.md#inputpriority)
- [InstanceComponents](ue_ue.InteractiveFoliageActor.md#instancecomponents)
- [Instigator](ue_ue.InteractiveFoliageActor.md#instigator)
- [Layers](ue_ue.InteractiveFoliageActor.md#layers)
- [Mass](ue_ue.InteractiveFoliageActor.md#mass)
- [MaxDamageImpulse](ue_ue.InteractiveFoliageActor.md#maxdamageimpulse)
- [MaxForce](ue_ue.InteractiveFoliageActor.md#maxforce)
- [MaxTouchImpulse](ue_ue.InteractiveFoliageActor.md#maxtouchimpulse)
- [MinNetUpdateFrequency](ue_ue.InteractiveFoliageActor.md#minnetupdatefrequency)
- [NavigationGeometryGatheringMode](ue_ue.InteractiveFoliageActor.md#navigationgeometrygatheringmode)
- [NetCullDistanceSquared](ue_ue.InteractiveFoliageActor.md#netculldistancesquared)
- [NetDormancy](ue_ue.InteractiveFoliageActor.md#netdormancy)
- [NetDriverName](ue_ue.InteractiveFoliageActor.md#netdrivername)
- [NetPriority](ue_ue.InteractiveFoliageActor.md#netpriority)
- [NetTag](ue_ue.InteractiveFoliageActor.md#nettag)
- [NetUpdateFrequency](ue_ue.InteractiveFoliageActor.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.InteractiveFoliageActor.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.InteractiveFoliageActor.md#onactorendoverlap)
- [OnActorHit](ue_ue.InteractiveFoliageActor.md#onactorhit)
- [OnBeginCursorOver](ue_ue.InteractiveFoliageActor.md#onbegincursorover)
- [OnClicked](ue_ue.InteractiveFoliageActor.md#onclicked)
- [OnDestroyed](ue_ue.InteractiveFoliageActor.md#ondestroyed)
- [OnEndCursorOver](ue_ue.InteractiveFoliageActor.md#onendcursorover)
- [OnEndPlay](ue_ue.InteractiveFoliageActor.md#onendplay)
- [OnInputTouchBegin](ue_ue.InteractiveFoliageActor.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.InteractiveFoliageActor.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.InteractiveFoliageActor.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.InteractiveFoliageActor.md#oninputtouchleave)
- [OnReleased](ue_ue.InteractiveFoliageActor.md#onreleased)
- [OnTakeAnyDamage](ue_ue.InteractiveFoliageActor.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.InteractiveFoliageActor.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.InteractiveFoliageActor.md#ontakeradialdamage)
- [Owner](ue_ue.InteractiveFoliageActor.md#owner)
- [ParentComponent](ue_ue.InteractiveFoliageActor.md#parentcomponent)
- [ParentComponentActor](ue_ue.InteractiveFoliageActor.md#parentcomponentactor)
- [PivotOffset](ue_ue.InteractiveFoliageActor.md#pivotoffset)
- [PrimaryActorTick](ue_ue.InteractiveFoliageActor.md#primaryactortick)
- [RemoteRole](ue_ue.InteractiveFoliageActor.md#remoterole)
- [ReplicatedMovement](ue_ue.InteractiveFoliageActor.md#replicatedmovement)
- [Role](ue_ue.InteractiveFoliageActor.md#role)
- [RootComponent](ue_ue.InteractiveFoliageActor.md#rootcomponent)
- [SpawnCollisionHandlingMethod](ue_ue.InteractiveFoliageActor.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.InteractiveFoliageActor.md#spritescale)
- [StaticMeshComponent](ue_ue.InteractiveFoliageActor.md#staticmeshcomponent)
- [Tags](ue_ue.InteractiveFoliageActor.md#tags)
- [TouchingActorEntryPosition](ue_ue.InteractiveFoliageActor.md#touchingactorentryposition)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.InteractiveFoliageActor.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.InteractiveFoliageActor.md#__tid_actor__)
- [\_\_tid\_InteractiveFoliageActor\_\_](ue_ue.InteractiveFoliageActor.md#__tid_interactivefoliageactor__)
- [\_\_tid\_Object\_\_](ue_ue.InteractiveFoliageActor.md#__tid_object__)
- [\_\_tid\_StaticMeshActor\_\_](ue_ue.InteractiveFoliageActor.md#__tid_staticmeshactor__)
- [bActorEnableCollision](ue_ue.InteractiveFoliageActor.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.InteractiveFoliageActor.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.InteractiveFoliageActor.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.InteractiveFoliageActor.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.InteractiveFoliageActor.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.InteractiveFoliageActor.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.InteractiveFoliageActor.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.InteractiveFoliageActor.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.InteractiveFoliageActor.md#bblockinput)
- [bCanBeDamaged](ue_ue.InteractiveFoliageActor.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.InteractiveFoliageActor.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.InteractiveFoliageActor.md#bcollidewhenplacing)
- [bEditable](ue_ue.InteractiveFoliageActor.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.InteractiveFoliageActor.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.InteractiveFoliageActor.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.InteractiveFoliageActor.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.InteractiveFoliageActor.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.InteractiveFoliageActor.md#bhidden)
- [bHiddenEd](ue_ue.InteractiveFoliageActor.md#bhiddened)
- [bHiddenEdLayer](ue_ue.InteractiveFoliageActor.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.InteractiveFoliageActor.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.InteractiveFoliageActor.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.InteractiveFoliageActor.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.InteractiveFoliageActor.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.InteractiveFoliageActor.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.InteractiveFoliageActor.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.InteractiveFoliageActor.md#blocklocation)
- [bNetLoadOnClient](ue_ue.InteractiveFoliageActor.md#bnetloadonclient)
- [bNetStartup](ue_ue.InteractiveFoliageActor.md#bnetstartup)
- [bNetTemporary](ue_ue.InteractiveFoliageActor.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.InteractiveFoliageActor.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.InteractiveFoliageActor.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.InteractiveFoliageActor.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.InteractiveFoliageActor.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.InteractiveFoliageActor.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.InteractiveFoliageActor.md#breplayrewindable)
- [bReplicateMovement](ue_ue.InteractiveFoliageActor.md#breplicatemovement)
- [bReplicates](ue_ue.InteractiveFoliageActor.md#breplicates)
- [bStaticMeshReplicateMovement](ue_ue.InteractiveFoliageActor.md#bstaticmeshreplicatemovement)
- [bTearOff](ue_ue.InteractiveFoliageActor.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.InteractiveFoliageActor.md#actorhastag)
- [AddComponent](ue_ue.InteractiveFoliageActor.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.InteractiveFoliageActor.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.InteractiveFoliageActor.md#addtickprerequisitecomponent)
- [CapsuleTouched](ue_ue.InteractiveFoliageActor.md#capsuletouched)
- [CreateDefaultSubobject](ue_ue.InteractiveFoliageActor.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.InteractiveFoliageActor.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.InteractiveFoliageActor.md#disableinput)
- [EnableInput](ue_ue.InteractiveFoliageActor.md#enableinput)
- [ExecuteUbergraph](ue_ue.InteractiveFoliageActor.md#executeubergraph)
- [FlushNetDormancy](ue_ue.InteractiveFoliageActor.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.InteractiveFoliageActor.md#forcenetupdate)
- [GetActorBounds](ue_ue.InteractiveFoliageActor.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.InteractiveFoliageActor.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.InteractiveFoliageActor.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.InteractiveFoliageActor.md#getactorforwardvector)
- [GetActorLabel](ue_ue.InteractiveFoliageActor.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.InteractiveFoliageActor.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.InteractiveFoliageActor.md#getactorrightvector)
- [GetActorScale3D](ue_ue.InteractiveFoliageActor.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.InteractiveFoliageActor.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.InteractiveFoliageActor.md#getactortimedilation)
- [GetActorUpVector](ue_ue.InteractiveFoliageActor.md#getactorupvector)
- [GetAllChildActors](ue_ue.InteractiveFoliageActor.md#getallchildactors)
- [GetAttachParentActor](ue_ue.InteractiveFoliageActor.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.InteractiveFoliageActor.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.InteractiveFoliageActor.md#getattachedactors)
- [GetClass](ue_ue.InteractiveFoliageActor.md#getclass)
- [GetComponentByClass](ue_ue.InteractiveFoliageActor.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.InteractiveFoliageActor.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.InteractiveFoliageActor.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.InteractiveFoliageActor.md#getdistanceto)
- [GetDotProductTo](ue_ue.InteractiveFoliageActor.md#getdotproductto)
- [GetFolderPath](ue_ue.InteractiveFoliageActor.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.InteractiveFoliageActor.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.InteractiveFoliageActor.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.InteractiveFoliageActor.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.InteractiveFoliageActor.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.InteractiveFoliageActor.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.InteractiveFoliageActor.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.InteractiveFoliageActor.md#getinstigator)
- [GetInstigatorController](ue_ue.InteractiveFoliageActor.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.InteractiveFoliageActor.md#getlifespan)
- [GetLocalRole](ue_ue.InteractiveFoliageActor.md#getlocalrole)
- [GetName](ue_ue.InteractiveFoliageActor.md#getname)
- [GetOuter](ue_ue.InteractiveFoliageActor.md#getouter)
- [GetOverlappingActors](ue_ue.InteractiveFoliageActor.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.InteractiveFoliageActor.md#getoverlappingcomponents)
- [GetOwner](ue_ue.InteractiveFoliageActor.md#getowner)
- [GetParentActor](ue_ue.InteractiveFoliageActor.md#getparentactor)
- [GetParentComponent](ue_ue.InteractiveFoliageActor.md#getparentcomponent)
- [GetRemoteRole](ue_ue.InteractiveFoliageActor.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.InteractiveFoliageActor.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.InteractiveFoliageActor.md#gettickablewhenpaused)
- [GetTransform](ue_ue.InteractiveFoliageActor.md#gettransform)
- [GetVelocity](ue_ue.InteractiveFoliageActor.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.InteractiveFoliageActor.md#getverticaldistanceto)
- [GetWorld](ue_ue.InteractiveFoliageActor.md#getworld)
- [HasAuthority](ue_ue.InteractiveFoliageActor.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.InteractiveFoliageActor.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.InteractiveFoliageActor.md#isactortickenabled)
- [IsChildActor](ue_ue.InteractiveFoliageActor.md#ischildactor)
- [IsEditable](ue_ue.InteractiveFoliageActor.md#iseditable)
- [IsHiddenEd](ue_ue.InteractiveFoliageActor.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.InteractiveFoliageActor.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.InteractiveFoliageActor.md#isoverlappingactor)
- [IsSelectable](ue_ue.InteractiveFoliageActor.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.InteractiveFoliageActor.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.InteractiveFoliageActor.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.InteractiveFoliageActor.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.InteractiveFoliageActor.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.InteractiveFoliageActor.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.InteractiveFoliageActor.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.InteractiveFoliageActor.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.InteractiveFoliageActor.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.InteractiveFoliageActor.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.InteractiveFoliageActor.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.InteractiveFoliageActor.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.InteractiveFoliageActor.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.InteractiveFoliageActor.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.InteractiveFoliageActor.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.InteractiveFoliageActor.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.InteractiveFoliageActor.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.InteractiveFoliageActor.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.InteractiveFoliageActor.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.InteractiveFoliageActor.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.InteractiveFoliageActor.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.InteractiveFoliageActor.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.InteractiveFoliageActor.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.InteractiveFoliageActor.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.InteractiveFoliageActor.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.InteractiveFoliageActor.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.InteractiveFoliageActor.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.InteractiveFoliageActor.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.InteractiveFoliageActor.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.InteractiveFoliageActor.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.InteractiveFoliageActor.md#makemidformaterial)
- [MakeNoise](ue_ue.InteractiveFoliageActor.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.InteractiveFoliageActor.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.InteractiveFoliageActor.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.InteractiveFoliageActor.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.InteractiveFoliageActor.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.InteractiveFoliageActor.md#onrep_replicatedmovement)
- [PrestreamTextures](ue_ue.InteractiveFoliageActor.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.InteractiveFoliageActor.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.InteractiveFoliageActor.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.InteractiveFoliageActor.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.InteractiveFoliageActor.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.InteractiveFoliageActor.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.InteractiveFoliageActor.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.InteractiveFoliageActor.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.InteractiveFoliageActor.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.InteractiveFoliageActor.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.InteractiveFoliageActor.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.InteractiveFoliageActor.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.InteractiveFoliageActor.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.InteractiveFoliageActor.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.InteractiveFoliageActor.md#receiveendplay)
- [ReceiveHit](ue_ue.InteractiveFoliageActor.md#receivehit)
- [ReceivePointDamage](ue_ue.InteractiveFoliageActor.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.InteractiveFoliageActor.md#receiveradialdamage)
- [ReceiveTick](ue_ue.InteractiveFoliageActor.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.InteractiveFoliageActor.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.InteractiveFoliageActor.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.InteractiveFoliageActor.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.InteractiveFoliageActor.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.InteractiveFoliageActor.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.InteractiveFoliageActor.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.InteractiveFoliageActor.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.InteractiveFoliageActor.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.InteractiveFoliageActor.md#setactortickinterval)
- [SetFolderPath](ue_ue.InteractiveFoliageActor.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.InteractiveFoliageActor.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.InteractiveFoliageActor.md#setlifespan)
- [SetMobility](ue_ue.InteractiveFoliageActor.md#setmobility)
- [SetNetDormancy](ue_ue.InteractiveFoliageActor.md#setnetdormancy)
- [SetOwner](ue_ue.InteractiveFoliageActor.md#setowner)
- [SetReplicateMovement](ue_ue.InteractiveFoliageActor.md#setreplicatemovement)
- [SetReplicates](ue_ue.InteractiveFoliageActor.md#setreplicates)
- [SetTickGroup](ue_ue.InteractiveFoliageActor.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.InteractiveFoliageActor.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.InteractiveFoliageActor.md#snaprootcomponentto)
- [TearOff](ue_ue.InteractiveFoliageActor.md#tearoff)
- [UserConstructionScript](ue_ue.InteractiveFoliageActor.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.InteractiveFoliageActor.md#wasrecentlyrendered)
- [Find](ue_ue.InteractiveFoliageActor.md#find)
- [Load](ue_ue.InteractiveFoliageActor.md#load)
- [StaticClass](ue_ue.InteractiveFoliageActor.md#staticclass)

## Constructors

### constructor

• **new InteractiveFoliageActor**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[StaticMeshActor](ue_ue.StaticMeshActor.md).[constructor](ue_ue.StaticMeshActor.md#constructor)

#### Defined in

[ue/ue.d.ts:39503](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39503)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ActorLabel](ue_ue.StaticMeshActor.md#actorlabel)

#### Defined in

[ue/ue.d.ts:13176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13176)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[AttachmentReplication](ue_ue.StaticMeshActor.md#attachmentreplication)

#### Defined in

[ue/ue.d.ts:13151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13151)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[AutoReceiveInput](ue_ue.StaticMeshActor.md#autoreceiveinput)

#### Defined in

[ue/ue.d.ts:13157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13157)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[BlueprintCreatedComponents](ue_ue.StaticMeshActor.md#blueprintcreatedcomponents)

#### Defined in

[ue/ue.d.ts:13206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13206)

___

### CapsuleComponent

• **CapsuleComponent**: [`CapsuleComponent`](ue_ue.CapsuleComponent.md)

#### Defined in

[ue/ue.d.ts:39504](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39504)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[Children](ue_ue.StaticMeshActor.md#children)

#### Defined in

[ue/ue.d.ts:13166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13166)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ControllingMatineeActors](ue_ue.StaticMeshActor.md#controllingmatineeactors)

#### Defined in

[ue/ue.d.ts:13169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13169)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[CustomTimeDilation](ue_ue.StaticMeshActor.md#customtimedilation)

#### Defined in

[ue/ue.d.ts:13150](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13150)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.StaticMeshActor.md#defaultupdateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13146](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13146)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[FolderPath](ue_ue.StaticMeshActor.md#folderpath)

#### Defined in

[ue/ue.d.ts:13177](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13177)

___

### FoliageDamageImpulseScale

• **FoliageDamageImpulseScale**: `number`

#### Defined in

[ue/ue.d.ts:39509](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39509)

___

### FoliageDamping

• **FoliageDamping**: `number`

#### Defined in

[ue/ue.d.ts:39513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39513)

___

### FoliageForce

• **FoliageForce**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:39507](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39507)

___

### FoliagePosition

• **FoliagePosition**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:39508](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39508)

___

### FoliageStiffness

• **FoliageStiffness**: `number`

#### Defined in

[ue/ue.d.ts:39511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39511)

___

### FoliageStiffnessQuadratic

• **FoliageStiffnessQuadratic**: `number`

#### Defined in

[ue/ue.d.ts:39512](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39512)

___

### FoliageTouchImpulseScale

• **FoliageTouchImpulseScale**: `number`

#### Defined in

[ue/ue.d.ts:39510](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39510)

___

### FoliageVelocity

• **FoliageVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:39506](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39506)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GroupActor](ue_ue.StaticMeshActor.md#groupactor)

#### Defined in

[ue/ue.d.ts:13173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13173)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[HiddenEditorViews](ue_ue.StaticMeshActor.md#hiddeneditorviews)

#### Defined in

[ue/ue.d.ts:13175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13175)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[InitialLifeSpan](ue_ue.StaticMeshActor.md#initiallifespan)

#### Defined in

[ue/ue.d.ts:13149](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13149)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[InputComponent](ue_ue.StaticMeshActor.md#inputcomponent)

#### Defined in

[ue/ue.d.ts:13159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13159)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[InputPriority](ue_ue.StaticMeshActor.md#inputpriority)

#### Defined in

[ue/ue.d.ts:13158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13158)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[InstanceComponents](ue_ue.StaticMeshActor.md#instancecomponents)

#### Defined in

[ue/ue.d.ts:13205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13205)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[Instigator](ue_ue.StaticMeshActor.md#instigator)

#### Defined in

[ue/ue.d.ts:13165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13165)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[Layers](ue_ue.StaticMeshActor.md#layers)

#### Defined in

[ue/ue.d.ts:13170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13170)

___

### Mass

• **Mass**: `number`

#### Defined in

[ue/ue.d.ts:39517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39517)

___

### MaxDamageImpulse

• **MaxDamageImpulse**: `number`

#### Defined in

[ue/ue.d.ts:39514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39514)

___

### MaxForce

• **MaxForce**: `number`

#### Defined in

[ue/ue.d.ts:39516](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39516)

___

### MaxTouchImpulse

• **MaxTouchImpulse**: `number`

#### Defined in

[ue/ue.d.ts:39515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39515)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[MinNetUpdateFrequency](ue_ue.StaticMeshActor.md#minnetupdatefrequency)

#### Defined in

[ue/ue.d.ts:13163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13163)

___

### NavigationGeometryGatheringMode

• **NavigationGeometryGatheringMode**: [`ENavDataGatheringMode`](../enums/ue_ue.ENavDataGatheringMode.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[NavigationGeometryGatheringMode](ue_ue.StaticMeshActor.md#navigationgeometrygatheringmode)

#### Defined in

[ue/ue.d.ts:39493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39493)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[NetCullDistanceSquared](ue_ue.StaticMeshActor.md#netculldistancesquared)

#### Defined in

[ue/ue.d.ts:13160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13160)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[NetDormancy](ue_ue.StaticMeshActor.md#netdormancy)

#### Defined in

[ue/ue.d.ts:13155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13155)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[NetDriverName](ue_ue.StaticMeshActor.md#netdrivername)

#### Defined in

[ue/ue.d.ts:13153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13153)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[NetPriority](ue_ue.StaticMeshActor.md#netpriority)

#### Defined in

[ue/ue.d.ts:13164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13164)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[NetTag](ue_ue.StaticMeshActor.md#nettag)

#### Defined in

[ue/ue.d.ts:13161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13161)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[NetUpdateFrequency](ue_ue.StaticMeshActor.md#netupdatefrequency)

#### Defined in

[ue/ue.d.ts:13162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13162)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnActorBeginOverlap](ue_ue.StaticMeshActor.md#onactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13192)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnActorEndOverlap](ue_ue.StaticMeshActor.md#onactorendoverlap)

#### Defined in

[ue/ue.d.ts:13193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13193)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnActorHit](ue_ue.StaticMeshActor.md#onactorhit)

#### Defined in

[ue/ue.d.ts:13202](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13202)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnBeginCursorOver](ue_ue.StaticMeshActor.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:13194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13194)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnClicked](ue_ue.StaticMeshActor.md#onclicked)

#### Defined in

[ue/ue.d.ts:13196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13196)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnDestroyed](ue_ue.StaticMeshActor.md#ondestroyed)

#### Defined in

[ue/ue.d.ts:13203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13203)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnEndCursorOver](ue_ue.StaticMeshActor.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:13195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13195)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnEndPlay](ue_ue.StaticMeshActor.md#onendplay)

#### Defined in

[ue/ue.d.ts:13204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13204)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnInputTouchBegin](ue_ue.StaticMeshActor.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13198)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnInputTouchEnd](ue_ue.StaticMeshActor.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:13199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13199)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnInputTouchEnter](ue_ue.StaticMeshActor.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:13200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13200)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnInputTouchLeave](ue_ue.StaticMeshActor.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:13201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13201)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnReleased](ue_ue.StaticMeshActor.md#onreleased)

#### Defined in

[ue/ue.d.ts:13197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13197)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnTakeAnyDamage](ue_ue.StaticMeshActor.md#ontakeanydamage)

#### Defined in

[ue/ue.d.ts:13189](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13189)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnTakePointDamage](ue_ue.StaticMeshActor.md#ontakepointdamage)

#### Defined in

[ue/ue.d.ts:13190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13190)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnTakeRadialDamage](ue_ue.StaticMeshActor.md#ontakeradialdamage)

#### Defined in

[ue/ue.d.ts:13191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13191)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[Owner](ue_ue.StaticMeshActor.md#owner)

#### Defined in

[ue/ue.d.ts:13152](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13152)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ParentComponent](ue_ue.StaticMeshActor.md#parentcomponent)

#### Defined in

[ue/ue.d.ts:13172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13172)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ParentComponentActor](ue_ue.StaticMeshActor.md#parentcomponentactor)

#### Defined in

[ue/ue.d.ts:13171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13171)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[PivotOffset](ue_ue.StaticMeshActor.md#pivotoffset)

#### Defined in

[ue/ue.d.ts:13168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13168)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[PrimaryActorTick](ue_ue.StaticMeshActor.md#primaryactortick)

#### Defined in

[ue/ue.d.ts:13115](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13115)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[RemoteRole](ue_ue.StaticMeshActor.md#remoterole)

#### Defined in

[ue/ue.d.ts:13147](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13147)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReplicatedMovement](ue_ue.StaticMeshActor.md#replicatedmovement)

#### Defined in

[ue/ue.d.ts:13148](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13148)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[Role](ue_ue.StaticMeshActor.md#role)

#### Defined in

[ue/ue.d.ts:13154](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13154)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[RootComponent](ue_ue.StaticMeshActor.md#rootcomponent)

#### Defined in

[ue/ue.d.ts:13167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13167)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SpawnCollisionHandlingMethod](ue_ue.StaticMeshActor.md#spawncollisionhandlingmethod)

#### Defined in

[ue/ue.d.ts:13156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13156)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SpriteScale](ue_ue.StaticMeshActor.md#spritescale)

#### Defined in

[ue/ue.d.ts:13174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13174)

___

### StaticMeshComponent

• **StaticMeshComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[StaticMeshComponent](ue_ue.StaticMeshActor.md#staticmeshcomponent)

#### Defined in

[ue/ue.d.ts:39491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39491)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[Tags](ue_ue.StaticMeshActor.md#tags)

#### Defined in

[ue/ue.d.ts:13188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13188)

___

### TouchingActorEntryPosition

• **TouchingActorEntryPosition**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:39505](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39505)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.StaticMeshActor.md#updateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13145](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13145)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[__tid_Actor__](ue_ue.StaticMeshActor.md#__tid_actor__)

#### Defined in

[ue/ue.d.ts:13348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13348)

___

### \_\_tid\_InteractiveFoliageActor\_\_

• **\_\_tid\_InteractiveFoliageActor\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:39523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39523)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[__tid_Object__](ue_ue.StaticMeshActor.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_StaticMeshActor\_\_

• **\_\_tid\_StaticMeshActor\_\_**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[__tid_StaticMeshActor__](ue_ue.StaticMeshActor.md#__tid_staticmeshactor__)

#### Defined in

[ue/ue.d.ts:39499](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39499)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bActorEnableCollision](ue_ue.StaticMeshActor.md#bactorenablecollision)

#### Defined in

[ue/ue.d.ts:13143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13143)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bActorIsBeingDestroyed](ue_ue.StaticMeshActor.md#bactorisbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13144](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13144)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bActorLabelEditable](ue_ue.StaticMeshActor.md#bactorlabeleditable)

#### Defined in

[ue/ue.d.ts:13183](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13183)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bActorSeamlessTraveled](ue_ue.StaticMeshActor.md#bactorseamlesstraveled)

#### Defined in

[ue/ue.d.ts:13139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13139)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.StaticMeshActor.md#ballowreceivetickeventondedicatedserver)

#### Defined in

[ue/ue.d.ts:13142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13142)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bAllowTickBeforeBeginPlay](ue_ue.StaticMeshActor.md#ballowtickbeforebeginplay)

#### Defined in

[ue/ue.d.ts:13129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13129)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bAlwaysRelevant](ue_ue.StaticMeshActor.md#balwaysrelevant)

#### Defined in

[ue/ue.d.ts:13120](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13120)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bAutoDestroyWhenFinished](ue_ue.StaticMeshActor.md#bautodestroywhenfinished)

#### Defined in

[ue/ue.d.ts:13130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13130)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bBlockInput](ue_ue.StaticMeshActor.md#bblockinput)

#### Defined in

[ue/ue.d.ts:13131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13131)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bCanBeDamaged](ue_ue.StaticMeshActor.md#bcanbedamaged)

#### Defined in

[ue/ue.d.ts:13132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13132)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bCanBeInCluster](ue_ue.StaticMeshActor.md#bcanbeincluster)

#### Defined in

[ue/ue.d.ts:13141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13141)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bCollideWhenPlacing](ue_ue.StaticMeshActor.md#bcollidewhenplacing)

#### Defined in

[ue/ue.d.ts:13133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13133)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bEditable](ue_ue.StaticMeshActor.md#beditable)

#### Defined in

[ue/ue.d.ts:13184](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13184)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bEnableAutoLODGeneration](ue_ue.StaticMeshActor.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:13137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13137)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bExchangedRoles](ue_ue.StaticMeshActor.md#bexchangedroles)

#### Defined in

[ue/ue.d.ts:13123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13123)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bFindCameraComponentWhenViewTarget](ue_ue.StaticMeshActor.md#bfindcameracomponentwhenviewtarget)

#### Defined in

[ue/ue.d.ts:13134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13134)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.StaticMeshActor.md#bgenerateoverlapeventsduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13135)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bHidden](ue_ue.StaticMeshActor.md#bhidden)

#### Defined in

[ue/ue.d.ts:13116](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13116)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bHiddenEd](ue_ue.StaticMeshActor.md#bhiddened)

#### Defined in

[ue/ue.d.ts:13178](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13178)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bHiddenEdLayer](ue_ue.StaticMeshActor.md#bhiddenedlayer)

#### Defined in

[ue/ue.d.ts:13180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13180)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bHiddenEdLevel](ue_ue.StaticMeshActor.md#bhiddenedlevel)

#### Defined in

[ue/ue.d.ts:13181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13181)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bHiddenEdTemporary](ue_ue.StaticMeshActor.md#bhiddenedtemporary)

#### Defined in

[ue/ue.d.ts:13187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13187)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bIgnoresOriginShifting](ue_ue.StaticMeshActor.md#bignoresoriginshifting)

#### Defined in

[ue/ue.d.ts:13136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13136)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bIsEditorOnlyActor](ue_ue.StaticMeshActor.md#biseditoronlyactor)

#### Defined in

[ue/ue.d.ts:13138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13138)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bIsEditorPreviewActor](ue_ue.StaticMeshActor.md#biseditorpreviewactor)

#### Defined in

[ue/ue.d.ts:13179](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13179)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bListedInSceneOutliner](ue_ue.StaticMeshActor.md#blistedinsceneoutliner)

#### Defined in

[ue/ue.d.ts:13185](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13185)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bLockLocation](ue_ue.StaticMeshActor.md#blocklocation)

#### Defined in

[ue/ue.d.ts:13182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13182)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bNetLoadOnClient](ue_ue.StaticMeshActor.md#bnetloadonclient)

#### Defined in

[ue/ue.d.ts:13124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13124)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bNetStartup](ue_ue.StaticMeshActor.md#bnetstartup)

#### Defined in

[ue/ue.d.ts:13118](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13118)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bNetTemporary](ue_ue.StaticMeshActor.md#bnettemporary)

#### Defined in

[ue/ue.d.ts:13117](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13117)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bNetUseOwnerRelevancy](ue_ue.StaticMeshActor.md#bnetuseownerrelevancy)

#### Defined in

[ue/ue.d.ts:13125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13125)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bOnlyRelevantToOwner](ue_ue.StaticMeshActor.md#bonlyrelevanttoowner)

#### Defined in

[ue/ue.d.ts:13119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13119)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bOptimizeBPComponentData](ue_ue.StaticMeshActor.md#boptimizebpcomponentdata)

#### Defined in

[ue/ue.d.ts:13186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13186)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bRelevantForLevelBounds](ue_ue.StaticMeshActor.md#brelevantforlevelbounds)

#### Defined in

[ue/ue.d.ts:13127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13127)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bRelevantForNetworkReplays](ue_ue.StaticMeshActor.md#brelevantfornetworkreplays)

#### Defined in

[ue/ue.d.ts:13126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13126)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bReplayRewindable](ue_ue.StaticMeshActor.md#breplayrewindable)

#### Defined in

[ue/ue.d.ts:13128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13128)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bReplicateMovement](ue_ue.StaticMeshActor.md#breplicatemovement)

#### Defined in

[ue/ue.d.ts:13121](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13121)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bReplicates](ue_ue.StaticMeshActor.md#breplicates)

#### Defined in

[ue/ue.d.ts:13140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13140)

___

### bStaticMeshReplicateMovement

• **bStaticMeshReplicateMovement**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bStaticMeshReplicateMovement](ue_ue.StaticMeshActor.md#bstaticmeshreplicatemovement)

#### Defined in

[ue/ue.d.ts:39492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39492)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bTearOff](ue_ue.StaticMeshActor.md#btearoff)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ActorHasTag](ue_ue.StaticMeshActor.md#actorhastag)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[AddComponent](ue_ue.StaticMeshActor.md#addcomponent)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[AddTickPrerequisiteActor](ue_ue.StaticMeshActor.md#addtickprerequisiteactor)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[AddTickPrerequisiteComponent](ue_ue.StaticMeshActor.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13210](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13210)

___

### CapsuleTouched

▸ **CapsuleTouched**(`OverlappedComp`, `Other`, `OtherComp`, `OtherBodyIndex`, `bFromSweep`, `OverlapInfo`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OverlappedComp` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `Other` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `OtherComp` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `OtherBodyIndex` | `number` |
| `bFromSweep` | `boolean` |
| `OverlapInfo` | [`HitResult`](ue_ue.HitResult.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:39518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39518)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[CreateDefaultSubobject](ue_ue.StaticMeshActor.md#createdefaultsubobject)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[DetachRootComponentFromParent](ue_ue.StaticMeshActor.md#detachrootcomponentfromparent)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[DisableInput](ue_ue.StaticMeshActor.md#disableinput)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[EnableInput](ue_ue.StaticMeshActor.md#enableinput)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ExecuteUbergraph](ue_ue.StaticMeshActor.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[FlushNetDormancy](ue_ue.StaticMeshActor.md#flushnetdormancy)

#### Defined in

[ue/ue.d.ts:13214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13214)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ForceNetUpdate](ue_ue.StaticMeshActor.md#forcenetupdate)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorBounds](ue_ue.StaticMeshActor.md#getactorbounds)

#### Defined in

[ue/ue.d.ts:13216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13216)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorEnableCollision](ue_ue.StaticMeshActor.md#getactorenablecollision)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorEyesViewPoint](ue_ue.StaticMeshActor.md#getactoreyesviewpoint)

#### Defined in

[ue/ue.d.ts:13218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13218)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorForwardVector](ue_ue.StaticMeshActor.md#getactorforwardvector)

#### Defined in

[ue/ue.d.ts:13219](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13219)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorLabel](ue_ue.StaticMeshActor.md#getactorlabel)

#### Defined in

[ue/ue.d.ts:13220](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13220)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorRelativeScale3D](ue_ue.StaticMeshActor.md#getactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13221](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13221)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorRightVector](ue_ue.StaticMeshActor.md#getactorrightvector)

#### Defined in

[ue/ue.d.ts:13222](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13222)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorScale3D](ue_ue.StaticMeshActor.md#getactorscale3d)

#### Defined in

[ue/ue.d.ts:13223](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13223)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorTickInterval](ue_ue.StaticMeshActor.md#getactortickinterval)

#### Defined in

[ue/ue.d.ts:13224](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13224)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorTimeDilation](ue_ue.StaticMeshActor.md#getactortimedilation)

#### Defined in

[ue/ue.d.ts:13225](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13225)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorUpVector](ue_ue.StaticMeshActor.md#getactorupvector)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetAllChildActors](ue_ue.StaticMeshActor.md#getallchildactors)

#### Defined in

[ue/ue.d.ts:13227](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13227)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetAttachParentActor](ue_ue.StaticMeshActor.md#getattachparentactor)

#### Defined in

[ue/ue.d.ts:13229](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13229)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetAttachParentSocketName](ue_ue.StaticMeshActor.md#getattachparentsocketname)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetAttachedActors](ue_ue.StaticMeshActor.md#getattachedactors)

#### Defined in

[ue/ue.d.ts:13228](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13228)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetClass](ue_ue.StaticMeshActor.md#getclass)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetComponentByClass](ue_ue.StaticMeshActor.md#getcomponentbyclass)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetComponentsByInterface](ue_ue.StaticMeshActor.md#getcomponentsbyinterface)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetComponentsByTag](ue_ue.StaticMeshActor.md#getcomponentsbytag)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetDistanceTo](ue_ue.StaticMeshActor.md#getdistanceto)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetDotProductTo](ue_ue.StaticMeshActor.md#getdotproductto)

#### Defined in

[ue/ue.d.ts:13235](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13235)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetFolderPath](ue_ue.StaticMeshActor.md#getfolderpath)

#### Defined in

[ue/ue.d.ts:13236](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13236)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetGameTimeSinceCreation](ue_ue.StaticMeshActor.md#getgametimesincecreation)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetHorizontalDistanceTo](ue_ue.StaticMeshActor.md#gethorizontaldistanceto)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetHorizontalDotProductTo](ue_ue.StaticMeshActor.md#gethorizontaldotproductto)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetInputAxisKeyValue](ue_ue.StaticMeshActor.md#getinputaxiskeyvalue)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetInputAxisValue](ue_ue.StaticMeshActor.md#getinputaxisvalue)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetInputVectorAxisValue](ue_ue.StaticMeshActor.md#getinputvectoraxisvalue)

#### Defined in

[ue/ue.d.ts:13242](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13242)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetInstigator](ue_ue.StaticMeshActor.md#getinstigator)

#### Defined in

[ue/ue.d.ts:13243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13243)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetInstigatorController](ue_ue.StaticMeshActor.md#getinstigatorcontroller)

#### Defined in

[ue/ue.d.ts:13244](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13244)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetLifeSpan](ue_ue.StaticMeshActor.md#getlifespan)

#### Defined in

[ue/ue.d.ts:13245](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13245)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetLocalRole](ue_ue.StaticMeshActor.md#getlocalrole)

#### Defined in

[ue/ue.d.ts:13246](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13246)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetName](ue_ue.StaticMeshActor.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetOuter](ue_ue.StaticMeshActor.md#getouter)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetOverlappingActors](ue_ue.StaticMeshActor.md#getoverlappingactors)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetOverlappingComponents](ue_ue.StaticMeshActor.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:13248](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13248)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetOwner](ue_ue.StaticMeshActor.md#getowner)

#### Defined in

[ue/ue.d.ts:13249](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13249)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetParentActor](ue_ue.StaticMeshActor.md#getparentactor)

#### Defined in

[ue/ue.d.ts:13250](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13250)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetParentComponent](ue_ue.StaticMeshActor.md#getparentcomponent)

#### Defined in

[ue/ue.d.ts:13251](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13251)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetRemoteRole](ue_ue.StaticMeshActor.md#getremoterole)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetSquaredDistanceTo](ue_ue.StaticMeshActor.md#getsquareddistanceto)

#### Defined in

[ue/ue.d.ts:13253](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13253)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetTickableWhenPaused](ue_ue.StaticMeshActor.md#gettickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13254](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13254)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetTransform](ue_ue.StaticMeshActor.md#gettransform)

#### Defined in

[ue/ue.d.ts:13255](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13255)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetVelocity](ue_ue.StaticMeshActor.md#getvelocity)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetVerticalDistanceTo](ue_ue.StaticMeshActor.md#getverticaldistanceto)

#### Defined in

[ue/ue.d.ts:13257](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13257)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetWorld](ue_ue.StaticMeshActor.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[HasAuthority](ue_ue.StaticMeshActor.md#hasauthority)

#### Defined in

[ue/ue.d.ts:13258](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13258)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[IsActorBeingDestroyed](ue_ue.StaticMeshActor.md#isactorbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13259](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13259)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[IsActorTickEnabled](ue_ue.StaticMeshActor.md#isactortickenabled)

#### Defined in

[ue/ue.d.ts:13260](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13260)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[IsChildActor](ue_ue.StaticMeshActor.md#ischildactor)

#### Defined in

[ue/ue.d.ts:13261](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13261)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[IsEditable](ue_ue.StaticMeshActor.md#iseditable)

#### Defined in

[ue/ue.d.ts:13262](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13262)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[IsHiddenEd](ue_ue.StaticMeshActor.md#ishiddened)

#### Defined in

[ue/ue.d.ts:13263](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13263)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[IsHiddenEdAtStartup](ue_ue.StaticMeshActor.md#ishiddenedatstartup)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[IsOverlappingActor](ue_ue.StaticMeshActor.md#isoverlappingactor)

#### Defined in

[ue/ue.d.ts:13265](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13265)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[IsSelectable](ue_ue.StaticMeshActor.md#isselectable)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[IsTemporarilyHiddenInEditor](ue_ue.StaticMeshActor.md#istemporarilyhiddenineditor)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_AddActorLocalOffset](ue_ue.StaticMeshActor.md#k2_addactorlocaloffset)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_AddActorLocalRotation](ue_ue.StaticMeshActor.md#k2_addactorlocalrotation)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_AddActorLocalTransform](ue_ue.StaticMeshActor.md#k2_addactorlocaltransform)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_AddActorWorldOffset](ue_ue.StaticMeshActor.md#k2_addactorworldoffset)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_AddActorWorldRotation](ue_ue.StaticMeshActor.md#k2_addactorworldrotation)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_AddActorWorldTransform](ue_ue.StaticMeshActor.md#k2_addactorworldtransform)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_AttachRootComponentTo](ue_ue.StaticMeshActor.md#k2_attachrootcomponentto)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_AttachRootComponentToActor](ue_ue.StaticMeshActor.md#k2_attachrootcomponenttoactor)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_AttachToActor](ue_ue.StaticMeshActor.md#k2_attachtoactor)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_AttachToComponent](ue_ue.StaticMeshActor.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:13277](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13277)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_DestroyActor](ue_ue.StaticMeshActor.md#k2_destroyactor)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_DestroyComponent](ue_ue.StaticMeshActor.md#k2_destroycomponent)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_DetachFromActor](ue_ue.StaticMeshActor.md#k2_detachfromactor)

#### Defined in

[ue/ue.d.ts:13280](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13280)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_GetActorLocation](ue_ue.StaticMeshActor.md#k2_getactorlocation)

#### Defined in

[ue/ue.d.ts:13281](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13281)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_GetActorRotation](ue_ue.StaticMeshActor.md#k2_getactorrotation)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_GetComponentsByClass](ue_ue.StaticMeshActor.md#k2_getcomponentsbyclass)

#### Defined in

[ue/ue.d.ts:13283](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13283)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_GetRootComponent](ue_ue.StaticMeshActor.md#k2_getrootcomponent)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_OnBecomeViewTarget](ue_ue.StaticMeshActor.md#k2_onbecomeviewtarget)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_OnEndViewTarget](ue_ue.StaticMeshActor.md#k2_onendviewtarget)

#### Defined in

[ue/ue.d.ts:13286](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13286)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_OnReset](ue_ue.StaticMeshActor.md#k2_onreset)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_SetActorLocation](ue_ue.StaticMeshActor.md#k2_setactorlocation)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_SetActorLocationAndRotation](ue_ue.StaticMeshActor.md#k2_setactorlocationandrotation)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_SetActorRelativeLocation](ue_ue.StaticMeshActor.md#k2_setactorrelativelocation)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_SetActorRelativeRotation](ue_ue.StaticMeshActor.md#k2_setactorrelativerotation)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_SetActorRelativeTransform](ue_ue.StaticMeshActor.md#k2_setactorrelativetransform)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_SetActorRotation](ue_ue.StaticMeshActor.md#k2_setactorrotation)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_SetActorTransform](ue_ue.StaticMeshActor.md#k2_setactortransform)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_TeleportTo](ue_ue.StaticMeshActor.md#k2_teleportto)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[MakeMIDForMaterial](ue_ue.StaticMeshActor.md#makemidformaterial)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[MakeNoise](ue_ue.StaticMeshActor.md#makenoise)

#### Defined in

[ue/ue.d.ts:13297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13297)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnRep_AttachmentReplication](ue_ue.StaticMeshActor.md#onrep_attachmentreplication)

#### Defined in

[ue/ue.d.ts:13298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13298)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnRep_Instigator](ue_ue.StaticMeshActor.md#onrep_instigator)

#### Defined in

[ue/ue.d.ts:13299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13299)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnRep_Owner](ue_ue.StaticMeshActor.md#onrep_owner)

#### Defined in

[ue/ue.d.ts:13300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13300)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnRep_ReplicateMovement](ue_ue.StaticMeshActor.md#onrep_replicatemovement)

#### Defined in

[ue/ue.d.ts:13302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13302)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnRep_ReplicatedMovement](ue_ue.StaticMeshActor.md#onrep_replicatedmovement)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[PrestreamTextures](ue_ue.StaticMeshActor.md#prestreamtextures)

#### Defined in

[ue/ue.d.ts:13303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13303)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveActorBeginCursorOver](ue_ue.StaticMeshActor.md#receiveactorbegincursorover)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveActorBeginOverlap](ue_ue.StaticMeshActor.md#receiveactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13305)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveActorEndCursorOver](ue_ue.StaticMeshActor.md#receiveactorendcursorover)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveActorEndOverlap](ue_ue.StaticMeshActor.md#receiveactorendoverlap)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveActorOnClicked](ue_ue.StaticMeshActor.md#receiveactoronclicked)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveActorOnInputTouchBegin](ue_ue.StaticMeshActor.md#receiveactoroninputtouchbegin)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveActorOnInputTouchEnd](ue_ue.StaticMeshActor.md#receiveactoroninputtouchend)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveActorOnInputTouchEnter](ue_ue.StaticMeshActor.md#receiveactoroninputtouchenter)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveActorOnInputTouchLeave](ue_ue.StaticMeshActor.md#receiveactoroninputtouchleave)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveActorOnReleased](ue_ue.StaticMeshActor.md#receiveactoronreleased)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveAnyDamage](ue_ue.StaticMeshActor.md#receiveanydamage)

#### Defined in

[ue/ue.d.ts:13314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13314)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveBeginPlay](ue_ue.StaticMeshActor.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:13315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13315)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveDestroyed](ue_ue.StaticMeshActor.md#receivedestroyed)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveEndPlay](ue_ue.StaticMeshActor.md#receiveendplay)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveHit](ue_ue.StaticMeshActor.md#receivehit)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceivePointDamage](ue_ue.StaticMeshActor.md#receivepointdamage)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveRadialDamage](ue_ue.StaticMeshActor.md#receiveradialdamage)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveTick](ue_ue.StaticMeshActor.md#receivetick)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[RemoveTickPrerequisiteActor](ue_ue.StaticMeshActor.md#removetickprerequisiteactor)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[RemoveTickPrerequisiteComponent](ue_ue.StaticMeshActor.md#removetickprerequisitecomponent)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SetActorEnableCollision](ue_ue.StaticMeshActor.md#setactorenablecollision)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SetActorHiddenInGame](ue_ue.StaticMeshActor.md#setactorhiddeningame)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SetActorLabel](ue_ue.StaticMeshActor.md#setactorlabel)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SetActorRelativeScale3D](ue_ue.StaticMeshActor.md#setactorrelativescale3d)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SetActorScale3D](ue_ue.StaticMeshActor.md#setactorscale3d)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SetActorTickEnabled](ue_ue.StaticMeshActor.md#setactortickenabled)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SetActorTickInterval](ue_ue.StaticMeshActor.md#setactortickinterval)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SetFolderPath](ue_ue.StaticMeshActor.md#setfolderpath)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SetIsTemporarilyHiddenInEditor](ue_ue.StaticMeshActor.md#setistemporarilyhiddenineditor)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SetLifeSpan](ue_ue.StaticMeshActor.md#setlifespan)

#### Defined in

[ue/ue.d.ts:13333](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13333)

___

### SetMobility

▸ **SetMobility**(`InMobility`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InMobility` | [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md) |

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SetMobility](ue_ue.StaticMeshActor.md#setmobility)

#### Defined in

[ue/ue.d.ts:39494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39494)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SetNetDormancy](ue_ue.StaticMeshActor.md#setnetdormancy)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SetOwner](ue_ue.StaticMeshActor.md#setowner)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SetReplicateMovement](ue_ue.StaticMeshActor.md#setreplicatemovement)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SetReplicates](ue_ue.StaticMeshActor.md#setreplicates)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SetTickGroup](ue_ue.StaticMeshActor.md#settickgroup)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SetTickableWhenPaused](ue_ue.StaticMeshActor.md#settickablewhenpaused)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SnapRootComponentTo](ue_ue.StaticMeshActor.md#snaprootcomponentto)

#### Defined in

[ue/ue.d.ts:13340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13340)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[TearOff](ue_ue.StaticMeshActor.md#tearoff)

#### Defined in

[ue/ue.d.ts:13341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13341)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[UserConstructionScript](ue_ue.StaticMeshActor.md#userconstructionscript)

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

[StaticMeshActor](ue_ue.StaticMeshActor.md).[WasRecentlyRendered](ue_ue.StaticMeshActor.md#wasrecentlyrendered)

#### Defined in

[ue/ue.d.ts:13343](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13343)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InteractiveFoliageActor`](ue_ue.InteractiveFoliageActor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InteractiveFoliageActor`](ue_ue.InteractiveFoliageActor.md)

#### Overrides

[StaticMeshActor](ue_ue.StaticMeshActor.md).[Find](ue_ue.StaticMeshActor.md#find)

#### Defined in

[ue/ue.d.ts:39520](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39520)

___

### Load

▸ `Static` **Load**(`InName`): [`InteractiveFoliageActor`](ue_ue.InteractiveFoliageActor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InteractiveFoliageActor`](ue_ue.InteractiveFoliageActor.md)

#### Overrides

[StaticMeshActor](ue_ue.StaticMeshActor.md).[Load](ue_ue.StaticMeshActor.md#load)

#### Defined in

[ue/ue.d.ts:39521](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39521)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[StaticMeshActor](ue_ue.StaticMeshActor.md).[StaticClass](ue_ue.StaticMeshActor.md#staticclass)

#### Defined in

[ue/ue.d.ts:39519](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39519)
