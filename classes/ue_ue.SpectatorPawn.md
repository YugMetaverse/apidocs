[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SpectatorPawn

# Class: SpectatorPawn

[ue/ue](../modules/ue_ue.md).SpectatorPawn

## Hierarchy

- [`DefaultPawn`](ue_ue.DefaultPawn.md)

  ↳ **`SpectatorPawn`**

## Table of contents

### Constructors

- [constructor](ue_ue.SpectatorPawn.md#constructor)

### Properties

- [AIControllerClass](ue_ue.SpectatorPawn.md#aicontrollerclass)
- [ActorLabel](ue_ue.SpectatorPawn.md#actorlabel)
- [AttachmentReplication](ue_ue.SpectatorPawn.md#attachmentreplication)
- [AutoPossessAI](ue_ue.SpectatorPawn.md#autopossessai)
- [AutoPossessPlayer](ue_ue.SpectatorPawn.md#autopossessplayer)
- [AutoReceiveInput](ue_ue.SpectatorPawn.md#autoreceiveinput)
- [BaseEyeHeight](ue_ue.SpectatorPawn.md#baseeyeheight)
- [BaseLookUpRate](ue_ue.SpectatorPawn.md#baselookuprate)
- [BaseTurnRate](ue_ue.SpectatorPawn.md#baseturnrate)
- [BlueprintCreatedComponents](ue_ue.SpectatorPawn.md#blueprintcreatedcomponents)
- [Children](ue_ue.SpectatorPawn.md#children)
- [CollisionComponent](ue_ue.SpectatorPawn.md#collisioncomponent)
- [ControlInputVector](ue_ue.SpectatorPawn.md#controlinputvector)
- [Controller](ue_ue.SpectatorPawn.md#controller)
- [ControllingMatineeActors](ue_ue.SpectatorPawn.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.SpectatorPawn.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.SpectatorPawn.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.SpectatorPawn.md#folderpath)
- [GroupActor](ue_ue.SpectatorPawn.md#groupactor)
- [HiddenEditorViews](ue_ue.SpectatorPawn.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.SpectatorPawn.md#initiallifespan)
- [InputComponent](ue_ue.SpectatorPawn.md#inputcomponent)
- [InputPriority](ue_ue.SpectatorPawn.md#inputpriority)
- [InstanceComponents](ue_ue.SpectatorPawn.md#instancecomponents)
- [Instigator](ue_ue.SpectatorPawn.md#instigator)
- [LastControlInputVector](ue_ue.SpectatorPawn.md#lastcontrolinputvector)
- [LastHitBy](ue_ue.SpectatorPawn.md#lasthitby)
- [Layers](ue_ue.SpectatorPawn.md#layers)
- [MeshComponent](ue_ue.SpectatorPawn.md#meshcomponent)
- [MinNetUpdateFrequency](ue_ue.SpectatorPawn.md#minnetupdatefrequency)
- [MovementComponent](ue_ue.SpectatorPawn.md#movementcomponent)
- [NetCullDistanceSquared](ue_ue.SpectatorPawn.md#netculldistancesquared)
- [NetDormancy](ue_ue.SpectatorPawn.md#netdormancy)
- [NetDriverName](ue_ue.SpectatorPawn.md#netdrivername)
- [NetPriority](ue_ue.SpectatorPawn.md#netpriority)
- [NetTag](ue_ue.SpectatorPawn.md#nettag)
- [NetUpdateFrequency](ue_ue.SpectatorPawn.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.SpectatorPawn.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.SpectatorPawn.md#onactorendoverlap)
- [OnActorHit](ue_ue.SpectatorPawn.md#onactorhit)
- [OnBeginCursorOver](ue_ue.SpectatorPawn.md#onbegincursorover)
- [OnClicked](ue_ue.SpectatorPawn.md#onclicked)
- [OnDestroyed](ue_ue.SpectatorPawn.md#ondestroyed)
- [OnEndCursorOver](ue_ue.SpectatorPawn.md#onendcursorover)
- [OnEndPlay](ue_ue.SpectatorPawn.md#onendplay)
- [OnInputTouchBegin](ue_ue.SpectatorPawn.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.SpectatorPawn.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.SpectatorPawn.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.SpectatorPawn.md#oninputtouchleave)
- [OnReleased](ue_ue.SpectatorPawn.md#onreleased)
- [OnTakeAnyDamage](ue_ue.SpectatorPawn.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.SpectatorPawn.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.SpectatorPawn.md#ontakeradialdamage)
- [Owner](ue_ue.SpectatorPawn.md#owner)
- [ParentComponent](ue_ue.SpectatorPawn.md#parentcomponent)
- [ParentComponentActor](ue_ue.SpectatorPawn.md#parentcomponentactor)
- [PivotOffset](ue_ue.SpectatorPawn.md#pivotoffset)
- [PlayerState](ue_ue.SpectatorPawn.md#playerstate)
- [PrimaryActorTick](ue_ue.SpectatorPawn.md#primaryactortick)
- [RemoteRole](ue_ue.SpectatorPawn.md#remoterole)
- [RemoteViewPitch](ue_ue.SpectatorPawn.md#remoteviewpitch)
- [ReplicatedMovement](ue_ue.SpectatorPawn.md#replicatedmovement)
- [Role](ue_ue.SpectatorPawn.md#role)
- [RootComponent](ue_ue.SpectatorPawn.md#rootcomponent)
- [SpawnCollisionHandlingMethod](ue_ue.SpectatorPawn.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.SpectatorPawn.md#spritescale)
- [Tags](ue_ue.SpectatorPawn.md#tags)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.SpectatorPawn.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.SpectatorPawn.md#__tid_actor__)
- [\_\_tid\_DefaultPawn\_\_](ue_ue.SpectatorPawn.md#__tid_defaultpawn__)
- [\_\_tid\_Object\_\_](ue_ue.SpectatorPawn.md#__tid_object__)
- [\_\_tid\_Pawn\_\_](ue_ue.SpectatorPawn.md#__tid_pawn__)
- [\_\_tid\_SpectatorPawn\_\_](ue_ue.SpectatorPawn.md#__tid_spectatorpawn__)
- [bActorEnableCollision](ue_ue.SpectatorPawn.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.SpectatorPawn.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.SpectatorPawn.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.SpectatorPawn.md#bactorseamlesstraveled)
- [bAddDefaultMovementBindings](ue_ue.SpectatorPawn.md#badddefaultmovementbindings)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.SpectatorPawn.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.SpectatorPawn.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.SpectatorPawn.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.SpectatorPawn.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.SpectatorPawn.md#bblockinput)
- [bCanAffectNavigationGeneration](ue_ue.SpectatorPawn.md#bcanaffectnavigationgeneration)
- [bCanBeDamaged](ue_ue.SpectatorPawn.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.SpectatorPawn.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.SpectatorPawn.md#bcollidewhenplacing)
- [bEditable](ue_ue.SpectatorPawn.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.SpectatorPawn.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.SpectatorPawn.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.SpectatorPawn.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.SpectatorPawn.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.SpectatorPawn.md#bhidden)
- [bHiddenEd](ue_ue.SpectatorPawn.md#bhiddened)
- [bHiddenEdLayer](ue_ue.SpectatorPawn.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.SpectatorPawn.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.SpectatorPawn.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.SpectatorPawn.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.SpectatorPawn.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.SpectatorPawn.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.SpectatorPawn.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.SpectatorPawn.md#blocklocation)
- [bNetLoadOnClient](ue_ue.SpectatorPawn.md#bnetloadonclient)
- [bNetStartup](ue_ue.SpectatorPawn.md#bnetstartup)
- [bNetTemporary](ue_ue.SpectatorPawn.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.SpectatorPawn.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.SpectatorPawn.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.SpectatorPawn.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.SpectatorPawn.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.SpectatorPawn.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.SpectatorPawn.md#breplayrewindable)
- [bReplicateMovement](ue_ue.SpectatorPawn.md#breplicatemovement)
- [bReplicates](ue_ue.SpectatorPawn.md#breplicates)
- [bTearOff](ue_ue.SpectatorPawn.md#btearoff)
- [bUseControllerRotationPitch](ue_ue.SpectatorPawn.md#busecontrollerrotationpitch)
- [bUseControllerRotationRoll](ue_ue.SpectatorPawn.md#busecontrollerrotationroll)
- [bUseControllerRotationYaw](ue_ue.SpectatorPawn.md#busecontrollerrotationyaw)

### Methods

- [ActorHasTag](ue_ue.SpectatorPawn.md#actorhastag)
- [AddComponent](ue_ue.SpectatorPawn.md#addcomponent)
- [AddControllerPitchInput](ue_ue.SpectatorPawn.md#addcontrollerpitchinput)
- [AddControllerRollInput](ue_ue.SpectatorPawn.md#addcontrollerrollinput)
- [AddControllerYawInput](ue_ue.SpectatorPawn.md#addcontrolleryawinput)
- [AddMovementInput](ue_ue.SpectatorPawn.md#addmovementinput)
- [AddTickPrerequisiteActor](ue_ue.SpectatorPawn.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.SpectatorPawn.md#addtickprerequisitecomponent)
- [ConsumeMovementInputVector](ue_ue.SpectatorPawn.md#consumemovementinputvector)
- [CreateDefaultSubobject](ue_ue.SpectatorPawn.md#createdefaultsubobject)
- [DetachFromControllerPendingDestroy](ue_ue.SpectatorPawn.md#detachfromcontrollerpendingdestroy)
- [DetachRootComponentFromParent](ue_ue.SpectatorPawn.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.SpectatorPawn.md#disableinput)
- [EnableInput](ue_ue.SpectatorPawn.md#enableinput)
- [ExecuteUbergraph](ue_ue.SpectatorPawn.md#executeubergraph)
- [FlushNetDormancy](ue_ue.SpectatorPawn.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.SpectatorPawn.md#forcenetupdate)
- [GetActorBounds](ue_ue.SpectatorPawn.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.SpectatorPawn.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.SpectatorPawn.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.SpectatorPawn.md#getactorforwardvector)
- [GetActorLabel](ue_ue.SpectatorPawn.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.SpectatorPawn.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.SpectatorPawn.md#getactorrightvector)
- [GetActorScale3D](ue_ue.SpectatorPawn.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.SpectatorPawn.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.SpectatorPawn.md#getactortimedilation)
- [GetActorUpVector](ue_ue.SpectatorPawn.md#getactorupvector)
- [GetAllChildActors](ue_ue.SpectatorPawn.md#getallchildactors)
- [GetAttachParentActor](ue_ue.SpectatorPawn.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.SpectatorPawn.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.SpectatorPawn.md#getattachedactors)
- [GetBaseAimRotation](ue_ue.SpectatorPawn.md#getbaseaimrotation)
- [GetClass](ue_ue.SpectatorPawn.md#getclass)
- [GetComponentByClass](ue_ue.SpectatorPawn.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.SpectatorPawn.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.SpectatorPawn.md#getcomponentsbytag)
- [GetControlRotation](ue_ue.SpectatorPawn.md#getcontrolrotation)
- [GetController](ue_ue.SpectatorPawn.md#getcontroller)
- [GetDistanceTo](ue_ue.SpectatorPawn.md#getdistanceto)
- [GetDotProductTo](ue_ue.SpectatorPawn.md#getdotproductto)
- [GetFolderPath](ue_ue.SpectatorPawn.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.SpectatorPawn.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.SpectatorPawn.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.SpectatorPawn.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.SpectatorPawn.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.SpectatorPawn.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.SpectatorPawn.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.SpectatorPawn.md#getinstigator)
- [GetInstigatorController](ue_ue.SpectatorPawn.md#getinstigatorcontroller)
- [GetLastMovementInputVector](ue_ue.SpectatorPawn.md#getlastmovementinputvector)
- [GetLifeSpan](ue_ue.SpectatorPawn.md#getlifespan)
- [GetLocalRole](ue_ue.SpectatorPawn.md#getlocalrole)
- [GetMovementComponent](ue_ue.SpectatorPawn.md#getmovementcomponent)
- [GetName](ue_ue.SpectatorPawn.md#getname)
- [GetNavAgentLocation](ue_ue.SpectatorPawn.md#getnavagentlocation)
- [GetOuter](ue_ue.SpectatorPawn.md#getouter)
- [GetOverlappingActors](ue_ue.SpectatorPawn.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.SpectatorPawn.md#getoverlappingcomponents)
- [GetOwner](ue_ue.SpectatorPawn.md#getowner)
- [GetParentActor](ue_ue.SpectatorPawn.md#getparentactor)
- [GetParentComponent](ue_ue.SpectatorPawn.md#getparentcomponent)
- [GetPendingMovementInputVector](ue_ue.SpectatorPawn.md#getpendingmovementinputvector)
- [GetRemoteRole](ue_ue.SpectatorPawn.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.SpectatorPawn.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.SpectatorPawn.md#gettickablewhenpaused)
- [GetTransform](ue_ue.SpectatorPawn.md#gettransform)
- [GetVelocity](ue_ue.SpectatorPawn.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.SpectatorPawn.md#getverticaldistanceto)
- [GetWorld](ue_ue.SpectatorPawn.md#getworld)
- [HasAuthority](ue_ue.SpectatorPawn.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.SpectatorPawn.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.SpectatorPawn.md#isactortickenabled)
- [IsBotControlled](ue_ue.SpectatorPawn.md#isbotcontrolled)
- [IsChildActor](ue_ue.SpectatorPawn.md#ischildactor)
- [IsControlled](ue_ue.SpectatorPawn.md#iscontrolled)
- [IsEditable](ue_ue.SpectatorPawn.md#iseditable)
- [IsHiddenEd](ue_ue.SpectatorPawn.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.SpectatorPawn.md#ishiddenedatstartup)
- [IsLocallyControlled](ue_ue.SpectatorPawn.md#islocallycontrolled)
- [IsMoveInputIgnored](ue_ue.SpectatorPawn.md#ismoveinputignored)
- [IsOverlappingActor](ue_ue.SpectatorPawn.md#isoverlappingactor)
- [IsPawnControlled](ue_ue.SpectatorPawn.md#ispawncontrolled)
- [IsPlayerControlled](ue_ue.SpectatorPawn.md#isplayercontrolled)
- [IsSelectable](ue_ue.SpectatorPawn.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.SpectatorPawn.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.SpectatorPawn.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.SpectatorPawn.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.SpectatorPawn.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.SpectatorPawn.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.SpectatorPawn.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.SpectatorPawn.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.SpectatorPawn.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.SpectatorPawn.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.SpectatorPawn.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.SpectatorPawn.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.SpectatorPawn.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.SpectatorPawn.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.SpectatorPawn.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.SpectatorPawn.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.SpectatorPawn.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.SpectatorPawn.md#k2_getcomponentsbyclass)
- [K2\_GetMovementInputVector](ue_ue.SpectatorPawn.md#k2_getmovementinputvector)
- [K2\_GetRootComponent](ue_ue.SpectatorPawn.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.SpectatorPawn.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.SpectatorPawn.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.SpectatorPawn.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.SpectatorPawn.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.SpectatorPawn.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.SpectatorPawn.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.SpectatorPawn.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.SpectatorPawn.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.SpectatorPawn.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.SpectatorPawn.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.SpectatorPawn.md#k2_teleportto)
- [LaunchPawn](ue_ue.SpectatorPawn.md#launchpawn)
- [LookUpAtRate](ue_ue.SpectatorPawn.md#lookupatrate)
- [MakeMIDForMaterial](ue_ue.SpectatorPawn.md#makemidformaterial)
- [MakeNoise](ue_ue.SpectatorPawn.md#makenoise)
- [MoveForward](ue_ue.SpectatorPawn.md#moveforward)
- [MoveRight](ue_ue.SpectatorPawn.md#moveright)
- [MoveUp\_World](ue_ue.SpectatorPawn.md#moveup_world)
- [OnRep\_AttachmentReplication](ue_ue.SpectatorPawn.md#onrep_attachmentreplication)
- [OnRep\_Controller](ue_ue.SpectatorPawn.md#onrep_controller)
- [OnRep\_Instigator](ue_ue.SpectatorPawn.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.SpectatorPawn.md#onrep_owner)
- [OnRep\_PlayerState](ue_ue.SpectatorPawn.md#onrep_playerstate)
- [OnRep\_ReplicateMovement](ue_ue.SpectatorPawn.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.SpectatorPawn.md#onrep_replicatedmovement)
- [PawnMakeNoise](ue_ue.SpectatorPawn.md#pawnmakenoise)
- [PrestreamTextures](ue_ue.SpectatorPawn.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.SpectatorPawn.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.SpectatorPawn.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.SpectatorPawn.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.SpectatorPawn.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.SpectatorPawn.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.SpectatorPawn.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.SpectatorPawn.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.SpectatorPawn.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.SpectatorPawn.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.SpectatorPawn.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.SpectatorPawn.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.SpectatorPawn.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.SpectatorPawn.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.SpectatorPawn.md#receiveendplay)
- [ReceiveHit](ue_ue.SpectatorPawn.md#receivehit)
- [ReceivePointDamage](ue_ue.SpectatorPawn.md#receivepointdamage)
- [ReceivePossessed](ue_ue.SpectatorPawn.md#receivepossessed)
- [ReceiveRadialDamage](ue_ue.SpectatorPawn.md#receiveradialdamage)
- [ReceiveTick](ue_ue.SpectatorPawn.md#receivetick)
- [ReceiveUnpossessed](ue_ue.SpectatorPawn.md#receiveunpossessed)
- [RemoveTickPrerequisiteActor](ue_ue.SpectatorPawn.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.SpectatorPawn.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.SpectatorPawn.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.SpectatorPawn.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.SpectatorPawn.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.SpectatorPawn.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.SpectatorPawn.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.SpectatorPawn.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.SpectatorPawn.md#setactortickinterval)
- [SetCanAffectNavigationGeneration](ue_ue.SpectatorPawn.md#setcanaffectnavigationgeneration)
- [SetFolderPath](ue_ue.SpectatorPawn.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.SpectatorPawn.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.SpectatorPawn.md#setlifespan)
- [SetNetDormancy](ue_ue.SpectatorPawn.md#setnetdormancy)
- [SetOwner](ue_ue.SpectatorPawn.md#setowner)
- [SetReplicateMovement](ue_ue.SpectatorPawn.md#setreplicatemovement)
- [SetReplicates](ue_ue.SpectatorPawn.md#setreplicates)
- [SetTickGroup](ue_ue.SpectatorPawn.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.SpectatorPawn.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.SpectatorPawn.md#snaprootcomponentto)
- [SpawnDefaultController](ue_ue.SpectatorPawn.md#spawndefaultcontroller)
- [TearOff](ue_ue.SpectatorPawn.md#tearoff)
- [TurnAtRate](ue_ue.SpectatorPawn.md#turnatrate)
- [UserConstructionScript](ue_ue.SpectatorPawn.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.SpectatorPawn.md#wasrecentlyrendered)
- [Find](ue_ue.SpectatorPawn.md#find)
- [GetMovementBaseActor](ue_ue.SpectatorPawn.md#getmovementbaseactor)
- [Load](ue_ue.SpectatorPawn.md#load)
- [StaticClass](ue_ue.SpectatorPawn.md#staticclass)

## Constructors

### constructor

• **new SpectatorPawn**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DefaultPawn](ue_ue.DefaultPawn.md).[constructor](ue_ue.DefaultPawn.md#constructor)

## Properties

### AIControllerClass

• **AIControllerClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[AIControllerClass](ue_ue.DefaultPawn.md#aicontrollerclass)

___

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[ActorLabel](ue_ue.DefaultPawn.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[AttachmentReplication](ue_ue.DefaultPawn.md#attachmentreplication)

___

### AutoPossessAI

• **AutoPossessAI**: [`EAutoPossessAI`](../enums/ue_ue.EAutoPossessAI.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[AutoPossessAI](ue_ue.DefaultPawn.md#autopossessai)

___

### AutoPossessPlayer

• **AutoPossessPlayer**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[AutoPossessPlayer](ue_ue.DefaultPawn.md#autopossessplayer)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[AutoReceiveInput](ue_ue.DefaultPawn.md#autoreceiveinput)

___

### BaseEyeHeight

• **BaseEyeHeight**: `number`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[BaseEyeHeight](ue_ue.DefaultPawn.md#baseeyeheight)

___

### BaseLookUpRate

• **BaseLookUpRate**: `number`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[BaseLookUpRate](ue_ue.DefaultPawn.md#baselookuprate)

___

### BaseTurnRate

• **BaseTurnRate**: `number`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[BaseTurnRate](ue_ue.DefaultPawn.md#baseturnrate)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[BlueprintCreatedComponents](ue_ue.DefaultPawn.md#blueprintcreatedcomponents)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[Children](ue_ue.DefaultPawn.md#children)

___

### CollisionComponent

• **CollisionComponent**: [`SphereComponent`](ue_ue.SphereComponent.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[CollisionComponent](ue_ue.DefaultPawn.md#collisioncomponent)

___

### ControlInputVector

• **ControlInputVector**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[ControlInputVector](ue_ue.DefaultPawn.md#controlinputvector)

___

### Controller

• **Controller**: [`Controller`](ue_ue.Controller.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[Controller](ue_ue.DefaultPawn.md#controller)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[ControllingMatineeActors](ue_ue.DefaultPawn.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[CustomTimeDilation](ue_ue.DefaultPawn.md#customtimedilation)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.DefaultPawn.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[FolderPath](ue_ue.DefaultPawn.md#folderpath)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GroupActor](ue_ue.DefaultPawn.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[HiddenEditorViews](ue_ue.DefaultPawn.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[InitialLifeSpan](ue_ue.DefaultPawn.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[InputComponent](ue_ue.DefaultPawn.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[InputPriority](ue_ue.DefaultPawn.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[InstanceComponents](ue_ue.DefaultPawn.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[Instigator](ue_ue.DefaultPawn.md#instigator)

___

### LastControlInputVector

• **LastControlInputVector**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[LastControlInputVector](ue_ue.DefaultPawn.md#lastcontrolinputvector)

___

### LastHitBy

• **LastHitBy**: [`Controller`](ue_ue.Controller.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[LastHitBy](ue_ue.DefaultPawn.md#lasthitby)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[Layers](ue_ue.DefaultPawn.md#layers)

___

### MeshComponent

• **MeshComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[MeshComponent](ue_ue.DefaultPawn.md#meshcomponent)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[MinNetUpdateFrequency](ue_ue.DefaultPawn.md#minnetupdatefrequency)

___

### MovementComponent

• **MovementComponent**: [`PawnMovementComponent`](ue_ue.PawnMovementComponent.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[MovementComponent](ue_ue.DefaultPawn.md#movementcomponent)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[NetCullDistanceSquared](ue_ue.DefaultPawn.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[NetDormancy](ue_ue.DefaultPawn.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[NetDriverName](ue_ue.DefaultPawn.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[NetPriority](ue_ue.DefaultPawn.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[NetTag](ue_ue.DefaultPawn.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[NetUpdateFrequency](ue_ue.DefaultPawn.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnActorBeginOverlap](ue_ue.DefaultPawn.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnActorEndOverlap](ue_ue.DefaultPawn.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnActorHit](ue_ue.DefaultPawn.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnBeginCursorOver](ue_ue.DefaultPawn.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnClicked](ue_ue.DefaultPawn.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnDestroyed](ue_ue.DefaultPawn.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnEndCursorOver](ue_ue.DefaultPawn.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnEndPlay](ue_ue.DefaultPawn.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnInputTouchBegin](ue_ue.DefaultPawn.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnInputTouchEnd](ue_ue.DefaultPawn.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnInputTouchEnter](ue_ue.DefaultPawn.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnInputTouchLeave](ue_ue.DefaultPawn.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnReleased](ue_ue.DefaultPawn.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnTakeAnyDamage](ue_ue.DefaultPawn.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnTakePointDamage](ue_ue.DefaultPawn.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnTakeRadialDamage](ue_ue.DefaultPawn.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[Owner](ue_ue.DefaultPawn.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[ParentComponent](ue_ue.DefaultPawn.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[ParentComponentActor](ue_ue.DefaultPawn.md#parentcomponentactor)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[PivotOffset](ue_ue.DefaultPawn.md#pivotoffset)

___

### PlayerState

• **PlayerState**: [`PlayerState`](ue_ue.PlayerState.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[PlayerState](ue_ue.DefaultPawn.md#playerstate)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[PrimaryActorTick](ue_ue.DefaultPawn.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[RemoteRole](ue_ue.DefaultPawn.md#remoterole)

___

### RemoteViewPitch

• **RemoteViewPitch**: `number`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[RemoteViewPitch](ue_ue.DefaultPawn.md#remoteviewpitch)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[ReplicatedMovement](ue_ue.DefaultPawn.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[Role](ue_ue.DefaultPawn.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[RootComponent](ue_ue.DefaultPawn.md#rootcomponent)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[SpawnCollisionHandlingMethod](ue_ue.DefaultPawn.md#spawncollisionhandlingmethod)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[SpriteScale](ue_ue.DefaultPawn.md#spritescale)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[Tags](ue_ue.DefaultPawn.md#tags)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.DefaultPawn.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[__tid_Actor__](ue_ue.DefaultPawn.md#__tid_actor__)

___

### \_\_tid\_DefaultPawn\_\_

• **\_\_tid\_DefaultPawn\_\_**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[__tid_DefaultPawn__](ue_ue.DefaultPawn.md#__tid_defaultpawn__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[__tid_Object__](ue_ue.DefaultPawn.md#__tid_object__)

___

### \_\_tid\_Pawn\_\_

• **\_\_tid\_Pawn\_\_**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[__tid_Pawn__](ue_ue.DefaultPawn.md#__tid_pawn__)

___

### \_\_tid\_SpectatorPawn\_\_

• **\_\_tid\_SpectatorPawn\_\_**: `boolean`

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bActorEnableCollision](ue_ue.DefaultPawn.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bActorIsBeingDestroyed](ue_ue.DefaultPawn.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bActorLabelEditable](ue_ue.DefaultPawn.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bActorSeamlessTraveled](ue_ue.DefaultPawn.md#bactorseamlesstraveled)

___

### bAddDefaultMovementBindings

• **bAddDefaultMovementBindings**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bAddDefaultMovementBindings](ue_ue.DefaultPawn.md#badddefaultmovementbindings)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.DefaultPawn.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bAllowTickBeforeBeginPlay](ue_ue.DefaultPawn.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bAlwaysRelevant](ue_ue.DefaultPawn.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bAutoDestroyWhenFinished](ue_ue.DefaultPawn.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bBlockInput](ue_ue.DefaultPawn.md#bblockinput)

___

### bCanAffectNavigationGeneration

• **bCanAffectNavigationGeneration**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bCanAffectNavigationGeneration](ue_ue.DefaultPawn.md#bcanaffectnavigationgeneration)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bCanBeDamaged](ue_ue.DefaultPawn.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bCanBeInCluster](ue_ue.DefaultPawn.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bCollideWhenPlacing](ue_ue.DefaultPawn.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bEditable](ue_ue.DefaultPawn.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bEnableAutoLODGeneration](ue_ue.DefaultPawn.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bExchangedRoles](ue_ue.DefaultPawn.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bFindCameraComponentWhenViewTarget](ue_ue.DefaultPawn.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.DefaultPawn.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bHidden](ue_ue.DefaultPawn.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bHiddenEd](ue_ue.DefaultPawn.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bHiddenEdLayer](ue_ue.DefaultPawn.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bHiddenEdLevel](ue_ue.DefaultPawn.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bHiddenEdTemporary](ue_ue.DefaultPawn.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bIgnoresOriginShifting](ue_ue.DefaultPawn.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bIsEditorOnlyActor](ue_ue.DefaultPawn.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bIsEditorPreviewActor](ue_ue.DefaultPawn.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bListedInSceneOutliner](ue_ue.DefaultPawn.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bLockLocation](ue_ue.DefaultPawn.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bNetLoadOnClient](ue_ue.DefaultPawn.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bNetStartup](ue_ue.DefaultPawn.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bNetTemporary](ue_ue.DefaultPawn.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bNetUseOwnerRelevancy](ue_ue.DefaultPawn.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bOnlyRelevantToOwner](ue_ue.DefaultPawn.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bOptimizeBPComponentData](ue_ue.DefaultPawn.md#boptimizebpcomponentdata)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bRelevantForLevelBounds](ue_ue.DefaultPawn.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bRelevantForNetworkReplays](ue_ue.DefaultPawn.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bReplayRewindable](ue_ue.DefaultPawn.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bReplicateMovement](ue_ue.DefaultPawn.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bReplicates](ue_ue.DefaultPawn.md#breplicates)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bTearOff](ue_ue.DefaultPawn.md#btearoff)

___

### bUseControllerRotationPitch

• **bUseControllerRotationPitch**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bUseControllerRotationPitch](ue_ue.DefaultPawn.md#busecontrollerrotationpitch)

___

### bUseControllerRotationRoll

• **bUseControllerRotationRoll**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bUseControllerRotationRoll](ue_ue.DefaultPawn.md#busecontrollerrotationroll)

___

### bUseControllerRotationYaw

• **bUseControllerRotationYaw**: `boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[bUseControllerRotationYaw](ue_ue.DefaultPawn.md#busecontrollerrotationyaw)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[ActorHasTag](ue_ue.DefaultPawn.md#actorhastag)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[AddComponent](ue_ue.DefaultPawn.md#addcomponent)

___

### AddControllerPitchInput

▸ **AddControllerPitchInput**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[AddControllerPitchInput](ue_ue.DefaultPawn.md#addcontrollerpitchinput)

___

### AddControllerRollInput

▸ **AddControllerRollInput**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[AddControllerRollInput](ue_ue.DefaultPawn.md#addcontrollerrollinput)

___

### AddControllerYawInput

▸ **AddControllerYawInput**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[AddControllerYawInput](ue_ue.DefaultPawn.md#addcontrolleryawinput)

___

### AddMovementInput

▸ **AddMovementInput**(`WorldDirection`, `ScaleValue?`, `bForce?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldDirection` | [`Vector`](ue_ue_s.Vector.md) |
| `ScaleValue?` | `number` |
| `bForce?` | `boolean` |

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[AddMovementInput](ue_ue.DefaultPawn.md#addmovementinput)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[AddTickPrerequisiteActor](ue_ue.DefaultPawn.md#addtickprerequisiteactor)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[AddTickPrerequisiteComponent](ue_ue.DefaultPawn.md#addtickprerequisitecomponent)

___

### ConsumeMovementInputVector

▸ **ConsumeMovementInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[ConsumeMovementInputVector](ue_ue.DefaultPawn.md#consumemovementinputvector)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[CreateDefaultSubobject](ue_ue.DefaultPawn.md#createdefaultsubobject)

___

### DetachFromControllerPendingDestroy

▸ **DetachFromControllerPendingDestroy**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[DetachFromControllerPendingDestroy](ue_ue.DefaultPawn.md#detachfromcontrollerpendingdestroy)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[DetachRootComponentFromParent](ue_ue.DefaultPawn.md#detachrootcomponentfromparent)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[DisableInput](ue_ue.DefaultPawn.md#disableinput)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[EnableInput](ue_ue.DefaultPawn.md#enableinput)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[ExecuteUbergraph](ue_ue.DefaultPawn.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[FlushNetDormancy](ue_ue.DefaultPawn.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[ForceNetUpdate](ue_ue.DefaultPawn.md#forcenetupdate)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetActorBounds](ue_ue.DefaultPawn.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetActorEnableCollision](ue_ue.DefaultPawn.md#getactorenablecollision)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetActorEyesViewPoint](ue_ue.DefaultPawn.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetActorForwardVector](ue_ue.DefaultPawn.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetActorLabel](ue_ue.DefaultPawn.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetActorRelativeScale3D](ue_ue.DefaultPawn.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetActorRightVector](ue_ue.DefaultPawn.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetActorScale3D](ue_ue.DefaultPawn.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetActorTickInterval](ue_ue.DefaultPawn.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetActorTimeDilation](ue_ue.DefaultPawn.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetActorUpVector](ue_ue.DefaultPawn.md#getactorupvector)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetAllChildActors](ue_ue.DefaultPawn.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetAttachParentActor](ue_ue.DefaultPawn.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetAttachParentSocketName](ue_ue.DefaultPawn.md#getattachparentsocketname)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetAttachedActors](ue_ue.DefaultPawn.md#getattachedactors)

___

### GetBaseAimRotation

▸ **GetBaseAimRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetBaseAimRotation](ue_ue.DefaultPawn.md#getbaseaimrotation)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetClass](ue_ue.DefaultPawn.md#getclass)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetComponentByClass](ue_ue.DefaultPawn.md#getcomponentbyclass)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetComponentsByInterface](ue_ue.DefaultPawn.md#getcomponentsbyinterface)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetComponentsByTag](ue_ue.DefaultPawn.md#getcomponentsbytag)

___

### GetControlRotation

▸ **GetControlRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetControlRotation](ue_ue.DefaultPawn.md#getcontrolrotation)

___

### GetController

▸ **GetController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetController](ue_ue.DefaultPawn.md#getcontroller)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetDistanceTo](ue_ue.DefaultPawn.md#getdistanceto)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetDotProductTo](ue_ue.DefaultPawn.md#getdotproductto)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetFolderPath](ue_ue.DefaultPawn.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetGameTimeSinceCreation](ue_ue.DefaultPawn.md#getgametimesincecreation)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetHorizontalDistanceTo](ue_ue.DefaultPawn.md#gethorizontaldistanceto)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetHorizontalDotProductTo](ue_ue.DefaultPawn.md#gethorizontaldotproductto)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetInputAxisKeyValue](ue_ue.DefaultPawn.md#getinputaxiskeyvalue)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetInputAxisValue](ue_ue.DefaultPawn.md#getinputaxisvalue)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetInputVectorAxisValue](ue_ue.DefaultPawn.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetInstigator](ue_ue.DefaultPawn.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetInstigatorController](ue_ue.DefaultPawn.md#getinstigatorcontroller)

___

### GetLastMovementInputVector

▸ **GetLastMovementInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetLastMovementInputVector](ue_ue.DefaultPawn.md#getlastmovementinputvector)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetLifeSpan](ue_ue.DefaultPawn.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetLocalRole](ue_ue.DefaultPawn.md#getlocalrole)

___

### GetMovementComponent

▸ **GetMovementComponent**(): [`PawnMovementComponent`](ue_ue.PawnMovementComponent.md)

#### Returns

[`PawnMovementComponent`](ue_ue.PawnMovementComponent.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetMovementComponent](ue_ue.DefaultPawn.md#getmovementcomponent)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetName](ue_ue.DefaultPawn.md#getname)

___

### GetNavAgentLocation

▸ **GetNavAgentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetNavAgentLocation](ue_ue.DefaultPawn.md#getnavagentlocation)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetOuter](ue_ue.DefaultPawn.md#getouter)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetOverlappingActors](ue_ue.DefaultPawn.md#getoverlappingactors)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetOverlappingComponents](ue_ue.DefaultPawn.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetOwner](ue_ue.DefaultPawn.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetParentActor](ue_ue.DefaultPawn.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetParentComponent](ue_ue.DefaultPawn.md#getparentcomponent)

___

### GetPendingMovementInputVector

▸ **GetPendingMovementInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetPendingMovementInputVector](ue_ue.DefaultPawn.md#getpendingmovementinputvector)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetRemoteRole](ue_ue.DefaultPawn.md#getremoterole)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetSquaredDistanceTo](ue_ue.DefaultPawn.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetTickableWhenPaused](ue_ue.DefaultPawn.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetTransform](ue_ue.DefaultPawn.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetVelocity](ue_ue.DefaultPawn.md#getvelocity)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[GetVerticalDistanceTo](ue_ue.DefaultPawn.md#getverticaldistanceto)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetWorld](ue_ue.DefaultPawn.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[HasAuthority](ue_ue.DefaultPawn.md#hasauthority)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[IsActorBeingDestroyed](ue_ue.DefaultPawn.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[IsActorTickEnabled](ue_ue.DefaultPawn.md#isactortickenabled)

___

### IsBotControlled

▸ **IsBotControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[IsBotControlled](ue_ue.DefaultPawn.md#isbotcontrolled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[IsChildActor](ue_ue.DefaultPawn.md#ischildactor)

___

### IsControlled

▸ **IsControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[IsControlled](ue_ue.DefaultPawn.md#iscontrolled)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[IsEditable](ue_ue.DefaultPawn.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[IsHiddenEd](ue_ue.DefaultPawn.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[IsHiddenEdAtStartup](ue_ue.DefaultPawn.md#ishiddenedatstartup)

___

### IsLocallyControlled

▸ **IsLocallyControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[IsLocallyControlled](ue_ue.DefaultPawn.md#islocallycontrolled)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[IsMoveInputIgnored](ue_ue.DefaultPawn.md#ismoveinputignored)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[IsOverlappingActor](ue_ue.DefaultPawn.md#isoverlappingactor)

___

### IsPawnControlled

▸ **IsPawnControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[IsPawnControlled](ue_ue.DefaultPawn.md#ispawncontrolled)

___

### IsPlayerControlled

▸ **IsPlayerControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[IsPlayerControlled](ue_ue.DefaultPawn.md#isplayercontrolled)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[IsSelectable](ue_ue.DefaultPawn.md#isselectable)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[IsTemporarilyHiddenInEditor](ue_ue.DefaultPawn.md#istemporarilyhiddenineditor)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_AddActorLocalOffset](ue_ue.DefaultPawn.md#k2_addactorlocaloffset)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_AddActorLocalRotation](ue_ue.DefaultPawn.md#k2_addactorlocalrotation)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_AddActorLocalTransform](ue_ue.DefaultPawn.md#k2_addactorlocaltransform)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_AddActorWorldOffset](ue_ue.DefaultPawn.md#k2_addactorworldoffset)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_AddActorWorldRotation](ue_ue.DefaultPawn.md#k2_addactorworldrotation)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_AddActorWorldTransform](ue_ue.DefaultPawn.md#k2_addactorworldtransform)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_AttachRootComponentTo](ue_ue.DefaultPawn.md#k2_attachrootcomponentto)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_AttachRootComponentToActor](ue_ue.DefaultPawn.md#k2_attachrootcomponenttoactor)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_AttachToActor](ue_ue.DefaultPawn.md#k2_attachtoactor)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_AttachToComponent](ue_ue.DefaultPawn.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_DestroyActor](ue_ue.DefaultPawn.md#k2_destroyactor)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_DestroyComponent](ue_ue.DefaultPawn.md#k2_destroycomponent)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_DetachFromActor](ue_ue.DefaultPawn.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_GetActorLocation](ue_ue.DefaultPawn.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_GetActorRotation](ue_ue.DefaultPawn.md#k2_getactorrotation)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_GetComponentsByClass](ue_ue.DefaultPawn.md#k2_getcomponentsbyclass)

___

### K2\_GetMovementInputVector

▸ **K2_GetMovementInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_GetMovementInputVector](ue_ue.DefaultPawn.md#k2_getmovementinputvector)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_GetRootComponent](ue_ue.DefaultPawn.md#k2_getrootcomponent)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_OnBecomeViewTarget](ue_ue.DefaultPawn.md#k2_onbecomeviewtarget)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_OnEndViewTarget](ue_ue.DefaultPawn.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_OnReset](ue_ue.DefaultPawn.md#k2_onreset)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_SetActorLocation](ue_ue.DefaultPawn.md#k2_setactorlocation)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_SetActorLocationAndRotation](ue_ue.DefaultPawn.md#k2_setactorlocationandrotation)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_SetActorRelativeLocation](ue_ue.DefaultPawn.md#k2_setactorrelativelocation)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_SetActorRelativeRotation](ue_ue.DefaultPawn.md#k2_setactorrelativerotation)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_SetActorRelativeTransform](ue_ue.DefaultPawn.md#k2_setactorrelativetransform)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_SetActorRotation](ue_ue.DefaultPawn.md#k2_setactorrotation)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_SetActorTransform](ue_ue.DefaultPawn.md#k2_setactortransform)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[K2_TeleportTo](ue_ue.DefaultPawn.md#k2_teleportto)

___

### LaunchPawn

▸ **LaunchPawn**(`LaunchVelocity`, `bXYOverride`, `bZOverride`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LaunchVelocity` | [`Vector`](ue_ue_s.Vector.md) |
| `bXYOverride` | `boolean` |
| `bZOverride` | `boolean` |

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[LaunchPawn](ue_ue.DefaultPawn.md#launchpawn)

___

### LookUpAtRate

▸ **LookUpAtRate**(`Rate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Rate` | `number` |

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[LookUpAtRate](ue_ue.DefaultPawn.md#lookupatrate)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[MakeMIDForMaterial](ue_ue.DefaultPawn.md#makemidformaterial)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[MakeNoise](ue_ue.DefaultPawn.md#makenoise)

___

### MoveForward

▸ **MoveForward**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[MoveForward](ue_ue.DefaultPawn.md#moveforward)

___

### MoveRight

▸ **MoveRight**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[MoveRight](ue_ue.DefaultPawn.md#moveright)

___

### MoveUp\_World

▸ **MoveUp_World**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[MoveUp_World](ue_ue.DefaultPawn.md#moveup_world)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnRep_AttachmentReplication](ue_ue.DefaultPawn.md#onrep_attachmentreplication)

___

### OnRep\_Controller

▸ **OnRep_Controller**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnRep_Controller](ue_ue.DefaultPawn.md#onrep_controller)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnRep_Instigator](ue_ue.DefaultPawn.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnRep_Owner](ue_ue.DefaultPawn.md#onrep_owner)

___

### OnRep\_PlayerState

▸ **OnRep_PlayerState**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnRep_PlayerState](ue_ue.DefaultPawn.md#onrep_playerstate)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnRep_ReplicateMovement](ue_ue.DefaultPawn.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[OnRep_ReplicatedMovement](ue_ue.DefaultPawn.md#onrep_replicatedmovement)

___

### PawnMakeNoise

▸ **PawnMakeNoise**(`Loudness`, `NoiseLocation`, `bUseNoiseMakerLocation?`, `NoiseMaker?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Loudness` | `number` |
| `NoiseLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `bUseNoiseMakerLocation?` | `boolean` |
| `NoiseMaker?` | [`Actor`](ue_ue.Actor.md) |

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[PawnMakeNoise](ue_ue.DefaultPawn.md#pawnmakenoise)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[PrestreamTextures](ue_ue.DefaultPawn.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveActorBeginCursorOver](ue_ue.DefaultPawn.md#receiveactorbegincursorover)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveActorBeginOverlap](ue_ue.DefaultPawn.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveActorEndCursorOver](ue_ue.DefaultPawn.md#receiveactorendcursorover)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveActorEndOverlap](ue_ue.DefaultPawn.md#receiveactorendoverlap)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveActorOnClicked](ue_ue.DefaultPawn.md#receiveactoronclicked)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveActorOnInputTouchBegin](ue_ue.DefaultPawn.md#receiveactoroninputtouchbegin)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveActorOnInputTouchEnd](ue_ue.DefaultPawn.md#receiveactoroninputtouchend)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveActorOnInputTouchEnter](ue_ue.DefaultPawn.md#receiveactoroninputtouchenter)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveActorOnInputTouchLeave](ue_ue.DefaultPawn.md#receiveactoroninputtouchleave)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveActorOnReleased](ue_ue.DefaultPawn.md#receiveactoronreleased)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveAnyDamage](ue_ue.DefaultPawn.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveBeginPlay](ue_ue.DefaultPawn.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveDestroyed](ue_ue.DefaultPawn.md#receivedestroyed)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveEndPlay](ue_ue.DefaultPawn.md#receiveendplay)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveHit](ue_ue.DefaultPawn.md#receivehit)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceivePointDamage](ue_ue.DefaultPawn.md#receivepointdamage)

___

### ReceivePossessed

▸ **ReceivePossessed**(`NewController`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceivePossessed](ue_ue.DefaultPawn.md#receivepossessed)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveRadialDamage](ue_ue.DefaultPawn.md#receiveradialdamage)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveTick](ue_ue.DefaultPawn.md#receivetick)

___

### ReceiveUnpossessed

▸ **ReceiveUnpossessed**(`OldController`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OldController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[ReceiveUnpossessed](ue_ue.DefaultPawn.md#receiveunpossessed)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[RemoveTickPrerequisiteActor](ue_ue.DefaultPawn.md#removetickprerequisiteactor)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[RemoveTickPrerequisiteComponent](ue_ue.DefaultPawn.md#removetickprerequisitecomponent)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[SetActorEnableCollision](ue_ue.DefaultPawn.md#setactorenablecollision)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[SetActorHiddenInGame](ue_ue.DefaultPawn.md#setactorhiddeningame)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[SetActorLabel](ue_ue.DefaultPawn.md#setactorlabel)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[SetActorRelativeScale3D](ue_ue.DefaultPawn.md#setactorrelativescale3d)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[SetActorScale3D](ue_ue.DefaultPawn.md#setactorscale3d)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[SetActorTickEnabled](ue_ue.DefaultPawn.md#setactortickenabled)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[SetActorTickInterval](ue_ue.DefaultPawn.md#setactortickinterval)

___

### SetCanAffectNavigationGeneration

▸ **SetCanAffectNavigationGeneration**(`bNewValue`, `bForceUpdate?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `boolean` |
| `bForceUpdate?` | `boolean` |

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[SetCanAffectNavigationGeneration](ue_ue.DefaultPawn.md#setcanaffectnavigationgeneration)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[SetFolderPath](ue_ue.DefaultPawn.md#setfolderpath)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[SetIsTemporarilyHiddenInEditor](ue_ue.DefaultPawn.md#setistemporarilyhiddenineditor)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[SetLifeSpan](ue_ue.DefaultPawn.md#setlifespan)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[SetNetDormancy](ue_ue.DefaultPawn.md#setnetdormancy)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[SetOwner](ue_ue.DefaultPawn.md#setowner)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[SetReplicateMovement](ue_ue.DefaultPawn.md#setreplicatemovement)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[SetReplicates](ue_ue.DefaultPawn.md#setreplicates)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[SetTickGroup](ue_ue.DefaultPawn.md#settickgroup)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[SetTickableWhenPaused](ue_ue.DefaultPawn.md#settickablewhenpaused)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[SnapRootComponentTo](ue_ue.DefaultPawn.md#snaprootcomponentto)

___

### SpawnDefaultController

▸ **SpawnDefaultController**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[SpawnDefaultController](ue_ue.DefaultPawn.md#spawndefaultcontroller)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[TearOff](ue_ue.DefaultPawn.md#tearoff)

___

### TurnAtRate

▸ **TurnAtRate**(`Rate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Rate` | `number` |

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[TurnAtRate](ue_ue.DefaultPawn.md#turnatrate)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[UserConstructionScript](ue_ue.DefaultPawn.md#userconstructionscript)

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

[DefaultPawn](ue_ue.DefaultPawn.md).[WasRecentlyRendered](ue_ue.DefaultPawn.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SpectatorPawn`](ue_ue.SpectatorPawn.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SpectatorPawn`](ue_ue.SpectatorPawn.md)

#### Overrides

[DefaultPawn](ue_ue.DefaultPawn.md).[Find](ue_ue.DefaultPawn.md#find)

___

### GetMovementBaseActor

▸ `Static` **GetMovementBaseActor**(`Pawn`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Pawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[DefaultPawn](ue_ue.DefaultPawn.md).[GetMovementBaseActor](ue_ue.DefaultPawn.md#getmovementbaseactor)

___

### Load

▸ `Static` **Load**(`InName`): [`SpectatorPawn`](ue_ue.SpectatorPawn.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SpectatorPawn`](ue_ue.SpectatorPawn.md)

#### Overrides

[DefaultPawn](ue_ue.DefaultPawn.md).[Load](ue_ue.DefaultPawn.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DefaultPawn](ue_ue.DefaultPawn.md).[StaticClass](ue_ue.DefaultPawn.md#staticclass)
