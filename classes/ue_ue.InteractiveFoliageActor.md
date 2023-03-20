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

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ActorLabel](ue_ue.StaticMeshActor.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[AttachmentReplication](ue_ue.StaticMeshActor.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[AutoReceiveInput](ue_ue.StaticMeshActor.md#autoreceiveinput)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[BlueprintCreatedComponents](ue_ue.StaticMeshActor.md#blueprintcreatedcomponents)

___

### CapsuleComponent

• **CapsuleComponent**: [`CapsuleComponent`](ue_ue.CapsuleComponent.md)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[Children](ue_ue.StaticMeshActor.md#children)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ControllingMatineeActors](ue_ue.StaticMeshActor.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[CustomTimeDilation](ue_ue.StaticMeshActor.md#customtimedilation)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.StaticMeshActor.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[FolderPath](ue_ue.StaticMeshActor.md#folderpath)

___

### FoliageDamageImpulseScale

• **FoliageDamageImpulseScale**: `number`

___

### FoliageDamping

• **FoliageDamping**: `number`

___

### FoliageForce

• **FoliageForce**: [`Vector`](ue_ue_s.Vector.md)

___

### FoliagePosition

• **FoliagePosition**: [`Vector`](ue_ue_s.Vector.md)

___

### FoliageStiffness

• **FoliageStiffness**: `number`

___

### FoliageStiffnessQuadratic

• **FoliageStiffnessQuadratic**: `number`

___

### FoliageTouchImpulseScale

• **FoliageTouchImpulseScale**: `number`

___

### FoliageVelocity

• **FoliageVelocity**: [`Vector`](ue_ue_s.Vector.md)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GroupActor](ue_ue.StaticMeshActor.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[HiddenEditorViews](ue_ue.StaticMeshActor.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[InitialLifeSpan](ue_ue.StaticMeshActor.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[InputComponent](ue_ue.StaticMeshActor.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[InputPriority](ue_ue.StaticMeshActor.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[InstanceComponents](ue_ue.StaticMeshActor.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[Instigator](ue_ue.StaticMeshActor.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[Layers](ue_ue.StaticMeshActor.md#layers)

___

### Mass

• **Mass**: `number`

___

### MaxDamageImpulse

• **MaxDamageImpulse**: `number`

___

### MaxForce

• **MaxForce**: `number`

___

### MaxTouchImpulse

• **MaxTouchImpulse**: `number`

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[MinNetUpdateFrequency](ue_ue.StaticMeshActor.md#minnetupdatefrequency)

___

### NavigationGeometryGatheringMode

• **NavigationGeometryGatheringMode**: [`ENavDataGatheringMode`](../enums/ue_ue.ENavDataGatheringMode.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[NavigationGeometryGatheringMode](ue_ue.StaticMeshActor.md#navigationgeometrygatheringmode)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[NetCullDistanceSquared](ue_ue.StaticMeshActor.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[NetDormancy](ue_ue.StaticMeshActor.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[NetDriverName](ue_ue.StaticMeshActor.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[NetPriority](ue_ue.StaticMeshActor.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[NetTag](ue_ue.StaticMeshActor.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[NetUpdateFrequency](ue_ue.StaticMeshActor.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnActorBeginOverlap](ue_ue.StaticMeshActor.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnActorEndOverlap](ue_ue.StaticMeshActor.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnActorHit](ue_ue.StaticMeshActor.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnBeginCursorOver](ue_ue.StaticMeshActor.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnClicked](ue_ue.StaticMeshActor.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnDestroyed](ue_ue.StaticMeshActor.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnEndCursorOver](ue_ue.StaticMeshActor.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnEndPlay](ue_ue.StaticMeshActor.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnInputTouchBegin](ue_ue.StaticMeshActor.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnInputTouchEnd](ue_ue.StaticMeshActor.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnInputTouchEnter](ue_ue.StaticMeshActor.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnInputTouchLeave](ue_ue.StaticMeshActor.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnReleased](ue_ue.StaticMeshActor.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnTakeAnyDamage](ue_ue.StaticMeshActor.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnTakePointDamage](ue_ue.StaticMeshActor.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnTakeRadialDamage](ue_ue.StaticMeshActor.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[Owner](ue_ue.StaticMeshActor.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ParentComponent](ue_ue.StaticMeshActor.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ParentComponentActor](ue_ue.StaticMeshActor.md#parentcomponentactor)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[PivotOffset](ue_ue.StaticMeshActor.md#pivotoffset)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[PrimaryActorTick](ue_ue.StaticMeshActor.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[RemoteRole](ue_ue.StaticMeshActor.md#remoterole)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReplicatedMovement](ue_ue.StaticMeshActor.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[Role](ue_ue.StaticMeshActor.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[RootComponent](ue_ue.StaticMeshActor.md#rootcomponent)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SpawnCollisionHandlingMethod](ue_ue.StaticMeshActor.md#spawncollisionhandlingmethod)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[SpriteScale](ue_ue.StaticMeshActor.md#spritescale)

___

### StaticMeshComponent

• **StaticMeshComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[StaticMeshComponent](ue_ue.StaticMeshActor.md#staticmeshcomponent)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[Tags](ue_ue.StaticMeshActor.md#tags)

___

### TouchingActorEntryPosition

• **TouchingActorEntryPosition**: [`Vector`](ue_ue_s.Vector.md)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.StaticMeshActor.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[__tid_Actor__](ue_ue.StaticMeshActor.md#__tid_actor__)

___

### \_\_tid\_InteractiveFoliageActor\_\_

• **\_\_tid\_InteractiveFoliageActor\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[__tid_Object__](ue_ue.StaticMeshActor.md#__tid_object__)

___

### \_\_tid\_StaticMeshActor\_\_

• **\_\_tid\_StaticMeshActor\_\_**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[__tid_StaticMeshActor__](ue_ue.StaticMeshActor.md#__tid_staticmeshactor__)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bActorEnableCollision](ue_ue.StaticMeshActor.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bActorIsBeingDestroyed](ue_ue.StaticMeshActor.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bActorLabelEditable](ue_ue.StaticMeshActor.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bActorSeamlessTraveled](ue_ue.StaticMeshActor.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.StaticMeshActor.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bAllowTickBeforeBeginPlay](ue_ue.StaticMeshActor.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bAlwaysRelevant](ue_ue.StaticMeshActor.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bAutoDestroyWhenFinished](ue_ue.StaticMeshActor.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bBlockInput](ue_ue.StaticMeshActor.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bCanBeDamaged](ue_ue.StaticMeshActor.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bCanBeInCluster](ue_ue.StaticMeshActor.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bCollideWhenPlacing](ue_ue.StaticMeshActor.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bEditable](ue_ue.StaticMeshActor.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bEnableAutoLODGeneration](ue_ue.StaticMeshActor.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bExchangedRoles](ue_ue.StaticMeshActor.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bFindCameraComponentWhenViewTarget](ue_ue.StaticMeshActor.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.StaticMeshActor.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bHidden](ue_ue.StaticMeshActor.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bHiddenEd](ue_ue.StaticMeshActor.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bHiddenEdLayer](ue_ue.StaticMeshActor.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bHiddenEdLevel](ue_ue.StaticMeshActor.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bHiddenEdTemporary](ue_ue.StaticMeshActor.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bIgnoresOriginShifting](ue_ue.StaticMeshActor.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bIsEditorOnlyActor](ue_ue.StaticMeshActor.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bIsEditorPreviewActor](ue_ue.StaticMeshActor.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bListedInSceneOutliner](ue_ue.StaticMeshActor.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bLockLocation](ue_ue.StaticMeshActor.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bNetLoadOnClient](ue_ue.StaticMeshActor.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bNetStartup](ue_ue.StaticMeshActor.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bNetTemporary](ue_ue.StaticMeshActor.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bNetUseOwnerRelevancy](ue_ue.StaticMeshActor.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bOnlyRelevantToOwner](ue_ue.StaticMeshActor.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bOptimizeBPComponentData](ue_ue.StaticMeshActor.md#boptimizebpcomponentdata)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bRelevantForLevelBounds](ue_ue.StaticMeshActor.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bRelevantForNetworkReplays](ue_ue.StaticMeshActor.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bReplayRewindable](ue_ue.StaticMeshActor.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bReplicateMovement](ue_ue.StaticMeshActor.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bReplicates](ue_ue.StaticMeshActor.md#breplicates)

___

### bStaticMeshReplicateMovement

• **bStaticMeshReplicateMovement**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bStaticMeshReplicateMovement](ue_ue.StaticMeshActor.md#bstaticmeshreplicatemovement)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[bTearOff](ue_ue.StaticMeshActor.md#btearoff)

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

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[FlushNetDormancy](ue_ue.StaticMeshActor.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ForceNetUpdate](ue_ue.StaticMeshActor.md#forcenetupdate)

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

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorEnableCollision](ue_ue.StaticMeshActor.md#getactorenablecollision)

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

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorForwardVector](ue_ue.StaticMeshActor.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorLabel](ue_ue.StaticMeshActor.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorRelativeScale3D](ue_ue.StaticMeshActor.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorRightVector](ue_ue.StaticMeshActor.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorScale3D](ue_ue.StaticMeshActor.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorTickInterval](ue_ue.StaticMeshActor.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorTimeDilation](ue_ue.StaticMeshActor.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetActorUpVector](ue_ue.StaticMeshActor.md#getactorupvector)

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

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetAttachParentActor](ue_ue.StaticMeshActor.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetAttachParentSocketName](ue_ue.StaticMeshActor.md#getattachparentsocketname)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetClass](ue_ue.StaticMeshActor.md#getclass)

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

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetFolderPath](ue_ue.StaticMeshActor.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetGameTimeSinceCreation](ue_ue.StaticMeshActor.md#getgametimesincecreation)

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

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetInstigator](ue_ue.StaticMeshActor.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetInstigatorController](ue_ue.StaticMeshActor.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetLifeSpan](ue_ue.StaticMeshActor.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetLocalRole](ue_ue.StaticMeshActor.md#getlocalrole)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetName](ue_ue.StaticMeshActor.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetOuter](ue_ue.StaticMeshActor.md#getouter)

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

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetOwner](ue_ue.StaticMeshActor.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetParentActor](ue_ue.StaticMeshActor.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetParentComponent](ue_ue.StaticMeshActor.md#getparentcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetRemoteRole](ue_ue.StaticMeshActor.md#getremoterole)

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

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetTickableWhenPaused](ue_ue.StaticMeshActor.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetTransform](ue_ue.StaticMeshActor.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetVelocity](ue_ue.StaticMeshActor.md#getvelocity)

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

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[GetWorld](ue_ue.StaticMeshActor.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[HasAuthority](ue_ue.StaticMeshActor.md#hasauthority)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[IsActorBeingDestroyed](ue_ue.StaticMeshActor.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[IsActorTickEnabled](ue_ue.StaticMeshActor.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[IsChildActor](ue_ue.StaticMeshActor.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[IsEditable](ue_ue.StaticMeshActor.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[IsHiddenEd](ue_ue.StaticMeshActor.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[IsHiddenEdAtStartup](ue_ue.StaticMeshActor.md#ishiddenedatstartup)

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

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[IsSelectable](ue_ue.StaticMeshActor.md#isselectable)

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

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_DestroyActor](ue_ue.StaticMeshActor.md#k2_destroyactor)

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

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_GetActorLocation](ue_ue.StaticMeshActor.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_GetActorRotation](ue_ue.StaticMeshActor.md#k2_getactorrotation)

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

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_GetRootComponent](ue_ue.StaticMeshActor.md#k2_getrootcomponent)

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

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[K2_OnReset](ue_ue.StaticMeshActor.md#k2_onreset)

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

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnRep_AttachmentReplication](ue_ue.StaticMeshActor.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnRep_Instigator](ue_ue.StaticMeshActor.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnRep_Owner](ue_ue.StaticMeshActor.md#onrep_owner)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnRep_ReplicateMovement](ue_ue.StaticMeshActor.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[OnRep_ReplicatedMovement](ue_ue.StaticMeshActor.md#onrep_replicatedmovement)

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

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveActorBeginCursorOver](ue_ue.StaticMeshActor.md#receiveactorbegincursorover)

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

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveActorEndCursorOver](ue_ue.StaticMeshActor.md#receiveactorendcursorover)

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

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveBeginPlay](ue_ue.StaticMeshActor.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[ReceiveDestroyed](ue_ue.StaticMeshActor.md#receivedestroyed)

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

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[TearOff](ue_ue.StaticMeshActor.md#tearoff)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[StaticMeshActor](ue_ue.StaticMeshActor.md).[UserConstructionScript](ue_ue.StaticMeshActor.md#userconstructionscript)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[StaticMeshActor](ue_ue.StaticMeshActor.md).[StaticClass](ue_ue.StaticMeshActor.md#staticclass)
