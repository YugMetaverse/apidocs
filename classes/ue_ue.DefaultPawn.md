[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DefaultPawn

# Class: DefaultPawn

[ue/ue](../modules/ue_ue.md).DefaultPawn

## Hierarchy

- [`Pawn`](ue_ue.Pawn.md)

  ↳ **`DefaultPawn`**

  ↳↳ [`SpectatorPawn`](ue_ue.SpectatorPawn.md)

## Table of contents

### Constructors

- [constructor](ue_ue.DefaultPawn.md#constructor)

### Properties

- [AIControllerClass](ue_ue.DefaultPawn.md#aicontrollerclass)
- [ActorLabel](ue_ue.DefaultPawn.md#actorlabel)
- [AttachmentReplication](ue_ue.DefaultPawn.md#attachmentreplication)
- [AutoPossessAI](ue_ue.DefaultPawn.md#autopossessai)
- [AutoPossessPlayer](ue_ue.DefaultPawn.md#autopossessplayer)
- [AutoReceiveInput](ue_ue.DefaultPawn.md#autoreceiveinput)
- [BaseEyeHeight](ue_ue.DefaultPawn.md#baseeyeheight)
- [BaseLookUpRate](ue_ue.DefaultPawn.md#baselookuprate)
- [BaseTurnRate](ue_ue.DefaultPawn.md#baseturnrate)
- [BlueprintCreatedComponents](ue_ue.DefaultPawn.md#blueprintcreatedcomponents)
- [Children](ue_ue.DefaultPawn.md#children)
- [CollisionComponent](ue_ue.DefaultPawn.md#collisioncomponent)
- [ControlInputVector](ue_ue.DefaultPawn.md#controlinputvector)
- [Controller](ue_ue.DefaultPawn.md#controller)
- [ControllingMatineeActors](ue_ue.DefaultPawn.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.DefaultPawn.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.DefaultPawn.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.DefaultPawn.md#folderpath)
- [GroupActor](ue_ue.DefaultPawn.md#groupactor)
- [HiddenEditorViews](ue_ue.DefaultPawn.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.DefaultPawn.md#initiallifespan)
- [InputComponent](ue_ue.DefaultPawn.md#inputcomponent)
- [InputPriority](ue_ue.DefaultPawn.md#inputpriority)
- [InstanceComponents](ue_ue.DefaultPawn.md#instancecomponents)
- [Instigator](ue_ue.DefaultPawn.md#instigator)
- [LastControlInputVector](ue_ue.DefaultPawn.md#lastcontrolinputvector)
- [LastHitBy](ue_ue.DefaultPawn.md#lasthitby)
- [Layers](ue_ue.DefaultPawn.md#layers)
- [MeshComponent](ue_ue.DefaultPawn.md#meshcomponent)
- [MinNetUpdateFrequency](ue_ue.DefaultPawn.md#minnetupdatefrequency)
- [MovementComponent](ue_ue.DefaultPawn.md#movementcomponent)
- [NetCullDistanceSquared](ue_ue.DefaultPawn.md#netculldistancesquared)
- [NetDormancy](ue_ue.DefaultPawn.md#netdormancy)
- [NetDriverName](ue_ue.DefaultPawn.md#netdrivername)
- [NetPriority](ue_ue.DefaultPawn.md#netpriority)
- [NetTag](ue_ue.DefaultPawn.md#nettag)
- [NetUpdateFrequency](ue_ue.DefaultPawn.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.DefaultPawn.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.DefaultPawn.md#onactorendoverlap)
- [OnActorHit](ue_ue.DefaultPawn.md#onactorhit)
- [OnBeginCursorOver](ue_ue.DefaultPawn.md#onbegincursorover)
- [OnClicked](ue_ue.DefaultPawn.md#onclicked)
- [OnDestroyed](ue_ue.DefaultPawn.md#ondestroyed)
- [OnEndCursorOver](ue_ue.DefaultPawn.md#onendcursorover)
- [OnEndPlay](ue_ue.DefaultPawn.md#onendplay)
- [OnInputTouchBegin](ue_ue.DefaultPawn.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.DefaultPawn.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.DefaultPawn.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.DefaultPawn.md#oninputtouchleave)
- [OnReleased](ue_ue.DefaultPawn.md#onreleased)
- [OnTakeAnyDamage](ue_ue.DefaultPawn.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.DefaultPawn.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.DefaultPawn.md#ontakeradialdamage)
- [Owner](ue_ue.DefaultPawn.md#owner)
- [ParentComponent](ue_ue.DefaultPawn.md#parentcomponent)
- [ParentComponentActor](ue_ue.DefaultPawn.md#parentcomponentactor)
- [PivotOffset](ue_ue.DefaultPawn.md#pivotoffset)
- [PlayerState](ue_ue.DefaultPawn.md#playerstate)
- [PrimaryActorTick](ue_ue.DefaultPawn.md#primaryactortick)
- [RemoteRole](ue_ue.DefaultPawn.md#remoterole)
- [RemoteViewPitch](ue_ue.DefaultPawn.md#remoteviewpitch)
- [ReplicatedMovement](ue_ue.DefaultPawn.md#replicatedmovement)
- [Role](ue_ue.DefaultPawn.md#role)
- [RootComponent](ue_ue.DefaultPawn.md#rootcomponent)
- [SpawnCollisionHandlingMethod](ue_ue.DefaultPawn.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.DefaultPawn.md#spritescale)
- [Tags](ue_ue.DefaultPawn.md#tags)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.DefaultPawn.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.DefaultPawn.md#__tid_actor__)
- [\_\_tid\_DefaultPawn\_\_](ue_ue.DefaultPawn.md#__tid_defaultpawn__)
- [\_\_tid\_Object\_\_](ue_ue.DefaultPawn.md#__tid_object__)
- [\_\_tid\_Pawn\_\_](ue_ue.DefaultPawn.md#__tid_pawn__)
- [bActorEnableCollision](ue_ue.DefaultPawn.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.DefaultPawn.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.DefaultPawn.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.DefaultPawn.md#bactorseamlesstraveled)
- [bAddDefaultMovementBindings](ue_ue.DefaultPawn.md#badddefaultmovementbindings)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.DefaultPawn.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.DefaultPawn.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.DefaultPawn.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.DefaultPawn.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.DefaultPawn.md#bblockinput)
- [bCanAffectNavigationGeneration](ue_ue.DefaultPawn.md#bcanaffectnavigationgeneration)
- [bCanBeDamaged](ue_ue.DefaultPawn.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.DefaultPawn.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.DefaultPawn.md#bcollidewhenplacing)
- [bEditable](ue_ue.DefaultPawn.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.DefaultPawn.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.DefaultPawn.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.DefaultPawn.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.DefaultPawn.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.DefaultPawn.md#bhidden)
- [bHiddenEd](ue_ue.DefaultPawn.md#bhiddened)
- [bHiddenEdLayer](ue_ue.DefaultPawn.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.DefaultPawn.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.DefaultPawn.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.DefaultPawn.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.DefaultPawn.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.DefaultPawn.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.DefaultPawn.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.DefaultPawn.md#blocklocation)
- [bNetLoadOnClient](ue_ue.DefaultPawn.md#bnetloadonclient)
- [bNetStartup](ue_ue.DefaultPawn.md#bnetstartup)
- [bNetTemporary](ue_ue.DefaultPawn.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.DefaultPawn.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.DefaultPawn.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.DefaultPawn.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.DefaultPawn.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.DefaultPawn.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.DefaultPawn.md#breplayrewindable)
- [bReplicateMovement](ue_ue.DefaultPawn.md#breplicatemovement)
- [bReplicates](ue_ue.DefaultPawn.md#breplicates)
- [bTearOff](ue_ue.DefaultPawn.md#btearoff)
- [bUseControllerRotationPitch](ue_ue.DefaultPawn.md#busecontrollerrotationpitch)
- [bUseControllerRotationRoll](ue_ue.DefaultPawn.md#busecontrollerrotationroll)
- [bUseControllerRotationYaw](ue_ue.DefaultPawn.md#busecontrollerrotationyaw)

### Methods

- [ActorHasTag](ue_ue.DefaultPawn.md#actorhastag)
- [AddComponent](ue_ue.DefaultPawn.md#addcomponent)
- [AddControllerPitchInput](ue_ue.DefaultPawn.md#addcontrollerpitchinput)
- [AddControllerRollInput](ue_ue.DefaultPawn.md#addcontrollerrollinput)
- [AddControllerYawInput](ue_ue.DefaultPawn.md#addcontrolleryawinput)
- [AddMovementInput](ue_ue.DefaultPawn.md#addmovementinput)
- [AddTickPrerequisiteActor](ue_ue.DefaultPawn.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.DefaultPawn.md#addtickprerequisitecomponent)
- [ConsumeMovementInputVector](ue_ue.DefaultPawn.md#consumemovementinputvector)
- [CreateDefaultSubobject](ue_ue.DefaultPawn.md#createdefaultsubobject)
- [DetachFromControllerPendingDestroy](ue_ue.DefaultPawn.md#detachfromcontrollerpendingdestroy)
- [DetachRootComponentFromParent](ue_ue.DefaultPawn.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.DefaultPawn.md#disableinput)
- [EnableInput](ue_ue.DefaultPawn.md#enableinput)
- [ExecuteUbergraph](ue_ue.DefaultPawn.md#executeubergraph)
- [FlushNetDormancy](ue_ue.DefaultPawn.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.DefaultPawn.md#forcenetupdate)
- [GetActorBounds](ue_ue.DefaultPawn.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.DefaultPawn.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.DefaultPawn.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.DefaultPawn.md#getactorforwardvector)
- [GetActorLabel](ue_ue.DefaultPawn.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.DefaultPawn.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.DefaultPawn.md#getactorrightvector)
- [GetActorScale3D](ue_ue.DefaultPawn.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.DefaultPawn.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.DefaultPawn.md#getactortimedilation)
- [GetActorUpVector](ue_ue.DefaultPawn.md#getactorupvector)
- [GetAllChildActors](ue_ue.DefaultPawn.md#getallchildactors)
- [GetAttachParentActor](ue_ue.DefaultPawn.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.DefaultPawn.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.DefaultPawn.md#getattachedactors)
- [GetBaseAimRotation](ue_ue.DefaultPawn.md#getbaseaimrotation)
- [GetClass](ue_ue.DefaultPawn.md#getclass)
- [GetComponentByClass](ue_ue.DefaultPawn.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.DefaultPawn.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.DefaultPawn.md#getcomponentsbytag)
- [GetControlRotation](ue_ue.DefaultPawn.md#getcontrolrotation)
- [GetController](ue_ue.DefaultPawn.md#getcontroller)
- [GetDistanceTo](ue_ue.DefaultPawn.md#getdistanceto)
- [GetDotProductTo](ue_ue.DefaultPawn.md#getdotproductto)
- [GetFolderPath](ue_ue.DefaultPawn.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.DefaultPawn.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.DefaultPawn.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.DefaultPawn.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.DefaultPawn.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.DefaultPawn.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.DefaultPawn.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.DefaultPawn.md#getinstigator)
- [GetInstigatorController](ue_ue.DefaultPawn.md#getinstigatorcontroller)
- [GetLastMovementInputVector](ue_ue.DefaultPawn.md#getlastmovementinputvector)
- [GetLifeSpan](ue_ue.DefaultPawn.md#getlifespan)
- [GetLocalRole](ue_ue.DefaultPawn.md#getlocalrole)
- [GetMovementComponent](ue_ue.DefaultPawn.md#getmovementcomponent)
- [GetName](ue_ue.DefaultPawn.md#getname)
- [GetNavAgentLocation](ue_ue.DefaultPawn.md#getnavagentlocation)
- [GetOuter](ue_ue.DefaultPawn.md#getouter)
- [GetOverlappingActors](ue_ue.DefaultPawn.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.DefaultPawn.md#getoverlappingcomponents)
- [GetOwner](ue_ue.DefaultPawn.md#getowner)
- [GetParentActor](ue_ue.DefaultPawn.md#getparentactor)
- [GetParentComponent](ue_ue.DefaultPawn.md#getparentcomponent)
- [GetPendingMovementInputVector](ue_ue.DefaultPawn.md#getpendingmovementinputvector)
- [GetRemoteRole](ue_ue.DefaultPawn.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.DefaultPawn.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.DefaultPawn.md#gettickablewhenpaused)
- [GetTransform](ue_ue.DefaultPawn.md#gettransform)
- [GetVelocity](ue_ue.DefaultPawn.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.DefaultPawn.md#getverticaldistanceto)
- [GetWorld](ue_ue.DefaultPawn.md#getworld)
- [HasAuthority](ue_ue.DefaultPawn.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.DefaultPawn.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.DefaultPawn.md#isactortickenabled)
- [IsBotControlled](ue_ue.DefaultPawn.md#isbotcontrolled)
- [IsChildActor](ue_ue.DefaultPawn.md#ischildactor)
- [IsControlled](ue_ue.DefaultPawn.md#iscontrolled)
- [IsEditable](ue_ue.DefaultPawn.md#iseditable)
- [IsHiddenEd](ue_ue.DefaultPawn.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.DefaultPawn.md#ishiddenedatstartup)
- [IsLocallyControlled](ue_ue.DefaultPawn.md#islocallycontrolled)
- [IsMoveInputIgnored](ue_ue.DefaultPawn.md#ismoveinputignored)
- [IsOverlappingActor](ue_ue.DefaultPawn.md#isoverlappingactor)
- [IsPawnControlled](ue_ue.DefaultPawn.md#ispawncontrolled)
- [IsPlayerControlled](ue_ue.DefaultPawn.md#isplayercontrolled)
- [IsSelectable](ue_ue.DefaultPawn.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.DefaultPawn.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.DefaultPawn.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.DefaultPawn.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.DefaultPawn.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.DefaultPawn.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.DefaultPawn.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.DefaultPawn.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.DefaultPawn.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.DefaultPawn.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.DefaultPawn.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.DefaultPawn.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.DefaultPawn.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.DefaultPawn.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.DefaultPawn.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.DefaultPawn.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.DefaultPawn.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.DefaultPawn.md#k2_getcomponentsbyclass)
- [K2\_GetMovementInputVector](ue_ue.DefaultPawn.md#k2_getmovementinputvector)
- [K2\_GetRootComponent](ue_ue.DefaultPawn.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.DefaultPawn.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.DefaultPawn.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.DefaultPawn.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.DefaultPawn.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.DefaultPawn.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.DefaultPawn.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.DefaultPawn.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.DefaultPawn.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.DefaultPawn.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.DefaultPawn.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.DefaultPawn.md#k2_teleportto)
- [LaunchPawn](ue_ue.DefaultPawn.md#launchpawn)
- [LookUpAtRate](ue_ue.DefaultPawn.md#lookupatrate)
- [MakeMIDForMaterial](ue_ue.DefaultPawn.md#makemidformaterial)
- [MakeNoise](ue_ue.DefaultPawn.md#makenoise)
- [MoveForward](ue_ue.DefaultPawn.md#moveforward)
- [MoveRight](ue_ue.DefaultPawn.md#moveright)
- [MoveUp\_World](ue_ue.DefaultPawn.md#moveup_world)
- [OnRep\_AttachmentReplication](ue_ue.DefaultPawn.md#onrep_attachmentreplication)
- [OnRep\_Controller](ue_ue.DefaultPawn.md#onrep_controller)
- [OnRep\_Instigator](ue_ue.DefaultPawn.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.DefaultPawn.md#onrep_owner)
- [OnRep\_PlayerState](ue_ue.DefaultPawn.md#onrep_playerstate)
- [OnRep\_ReplicateMovement](ue_ue.DefaultPawn.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.DefaultPawn.md#onrep_replicatedmovement)
- [PawnMakeNoise](ue_ue.DefaultPawn.md#pawnmakenoise)
- [PrestreamTextures](ue_ue.DefaultPawn.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.DefaultPawn.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.DefaultPawn.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.DefaultPawn.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.DefaultPawn.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.DefaultPawn.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.DefaultPawn.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.DefaultPawn.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.DefaultPawn.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.DefaultPawn.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.DefaultPawn.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.DefaultPawn.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.DefaultPawn.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.DefaultPawn.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.DefaultPawn.md#receiveendplay)
- [ReceiveHit](ue_ue.DefaultPawn.md#receivehit)
- [ReceivePointDamage](ue_ue.DefaultPawn.md#receivepointdamage)
- [ReceivePossessed](ue_ue.DefaultPawn.md#receivepossessed)
- [ReceiveRadialDamage](ue_ue.DefaultPawn.md#receiveradialdamage)
- [ReceiveTick](ue_ue.DefaultPawn.md#receivetick)
- [ReceiveUnpossessed](ue_ue.DefaultPawn.md#receiveunpossessed)
- [RemoveTickPrerequisiteActor](ue_ue.DefaultPawn.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.DefaultPawn.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.DefaultPawn.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.DefaultPawn.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.DefaultPawn.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.DefaultPawn.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.DefaultPawn.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.DefaultPawn.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.DefaultPawn.md#setactortickinterval)
- [SetCanAffectNavigationGeneration](ue_ue.DefaultPawn.md#setcanaffectnavigationgeneration)
- [SetFolderPath](ue_ue.DefaultPawn.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.DefaultPawn.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.DefaultPawn.md#setlifespan)
- [SetNetDormancy](ue_ue.DefaultPawn.md#setnetdormancy)
- [SetOwner](ue_ue.DefaultPawn.md#setowner)
- [SetReplicateMovement](ue_ue.DefaultPawn.md#setreplicatemovement)
- [SetReplicates](ue_ue.DefaultPawn.md#setreplicates)
- [SetTickGroup](ue_ue.DefaultPawn.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.DefaultPawn.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.DefaultPawn.md#snaprootcomponentto)
- [SpawnDefaultController](ue_ue.DefaultPawn.md#spawndefaultcontroller)
- [TearOff](ue_ue.DefaultPawn.md#tearoff)
- [TurnAtRate](ue_ue.DefaultPawn.md#turnatrate)
- [UserConstructionScript](ue_ue.DefaultPawn.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.DefaultPawn.md#wasrecentlyrendered)
- [Find](ue_ue.DefaultPawn.md#find)
- [GetMovementBaseActor](ue_ue.DefaultPawn.md#getmovementbaseactor)
- [Load](ue_ue.DefaultPawn.md#load)
- [StaticClass](ue_ue.DefaultPawn.md#staticclass)

## Constructors

### constructor

• **new DefaultPawn**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Pawn](ue_ue.Pawn.md).[constructor](ue_ue.Pawn.md#constructor)

## Properties

### AIControllerClass

• **AIControllerClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[AIControllerClass](ue_ue.Pawn.md#aicontrollerclass)

___

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ActorLabel](ue_ue.Pawn.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[AttachmentReplication](ue_ue.Pawn.md#attachmentreplication)

___

### AutoPossessAI

• **AutoPossessAI**: [`EAutoPossessAI`](../enums/ue_ue.EAutoPossessAI.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[AutoPossessAI](ue_ue.Pawn.md#autopossessai)

___

### AutoPossessPlayer

• **AutoPossessPlayer**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[AutoPossessPlayer](ue_ue.Pawn.md#autopossessplayer)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[AutoReceiveInput](ue_ue.Pawn.md#autoreceiveinput)

___

### BaseEyeHeight

• **BaseEyeHeight**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[BaseEyeHeight](ue_ue.Pawn.md#baseeyeheight)

___

### BaseLookUpRate

• **BaseLookUpRate**: `number`

___

### BaseTurnRate

• **BaseTurnRate**: `number`

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[BlueprintCreatedComponents](ue_ue.Pawn.md#blueprintcreatedcomponents)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[Children](ue_ue.Pawn.md#children)

___

### CollisionComponent

• **CollisionComponent**: [`SphereComponent`](ue_ue.SphereComponent.md)

___

### ControlInputVector

• **ControlInputVector**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ControlInputVector](ue_ue.Pawn.md#controlinputvector)

___

### Controller

• **Controller**: [`Controller`](ue_ue.Controller.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[Controller](ue_ue.Pawn.md#controller)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ControllingMatineeActors](ue_ue.Pawn.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[CustomTimeDilation](ue_ue.Pawn.md#customtimedilation)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.Pawn.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[FolderPath](ue_ue.Pawn.md#folderpath)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GroupActor](ue_ue.Pawn.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[HiddenEditorViews](ue_ue.Pawn.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[InitialLifeSpan](ue_ue.Pawn.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[InputComponent](ue_ue.Pawn.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[InputPriority](ue_ue.Pawn.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[InstanceComponents](ue_ue.Pawn.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[Instigator](ue_ue.Pawn.md#instigator)

___

### LastControlInputVector

• **LastControlInputVector**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[LastControlInputVector](ue_ue.Pawn.md#lastcontrolinputvector)

___

### LastHitBy

• **LastHitBy**: [`Controller`](ue_ue.Controller.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[LastHitBy](ue_ue.Pawn.md#lasthitby)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[Layers](ue_ue.Pawn.md#layers)

___

### MeshComponent

• **MeshComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[MinNetUpdateFrequency](ue_ue.Pawn.md#minnetupdatefrequency)

___

### MovementComponent

• **MovementComponent**: [`PawnMovementComponent`](ue_ue.PawnMovementComponent.md)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[NetCullDistanceSquared](ue_ue.Pawn.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[NetDormancy](ue_ue.Pawn.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[NetDriverName](ue_ue.Pawn.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[NetPriority](ue_ue.Pawn.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[NetTag](ue_ue.Pawn.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[NetUpdateFrequency](ue_ue.Pawn.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnActorBeginOverlap](ue_ue.Pawn.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnActorEndOverlap](ue_ue.Pawn.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnActorHit](ue_ue.Pawn.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnBeginCursorOver](ue_ue.Pawn.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnClicked](ue_ue.Pawn.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnDestroyed](ue_ue.Pawn.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnEndCursorOver](ue_ue.Pawn.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnEndPlay](ue_ue.Pawn.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnInputTouchBegin](ue_ue.Pawn.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnInputTouchEnd](ue_ue.Pawn.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnInputTouchEnter](ue_ue.Pawn.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnInputTouchLeave](ue_ue.Pawn.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnReleased](ue_ue.Pawn.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnTakeAnyDamage](ue_ue.Pawn.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnTakePointDamage](ue_ue.Pawn.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnTakeRadialDamage](ue_ue.Pawn.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[Owner](ue_ue.Pawn.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ParentComponent](ue_ue.Pawn.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ParentComponentActor](ue_ue.Pawn.md#parentcomponentactor)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[PivotOffset](ue_ue.Pawn.md#pivotoffset)

___

### PlayerState

• **PlayerState**: [`PlayerState`](ue_ue.PlayerState.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[PlayerState](ue_ue.Pawn.md#playerstate)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[PrimaryActorTick](ue_ue.Pawn.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[RemoteRole](ue_ue.Pawn.md#remoterole)

___

### RemoteViewPitch

• **RemoteViewPitch**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[RemoteViewPitch](ue_ue.Pawn.md#remoteviewpitch)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ReplicatedMovement](ue_ue.Pawn.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[Role](ue_ue.Pawn.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[RootComponent](ue_ue.Pawn.md#rootcomponent)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[SpawnCollisionHandlingMethod](ue_ue.Pawn.md#spawncollisionhandlingmethod)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[SpriteScale](ue_ue.Pawn.md#spritescale)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[Tags](ue_ue.Pawn.md#tags)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.Pawn.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[__tid_Actor__](ue_ue.Pawn.md#__tid_actor__)

___

### \_\_tid\_DefaultPawn\_\_

• **\_\_tid\_DefaultPawn\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[__tid_Object__](ue_ue.Pawn.md#__tid_object__)

___

### \_\_tid\_Pawn\_\_

• **\_\_tid\_Pawn\_\_**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[__tid_Pawn__](ue_ue.Pawn.md#__tid_pawn__)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bActorEnableCollision](ue_ue.Pawn.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bActorIsBeingDestroyed](ue_ue.Pawn.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bActorLabelEditable](ue_ue.Pawn.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bActorSeamlessTraveled](ue_ue.Pawn.md#bactorseamlesstraveled)

___

### bAddDefaultMovementBindings

• **bAddDefaultMovementBindings**: `boolean`

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.Pawn.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bAllowTickBeforeBeginPlay](ue_ue.Pawn.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bAlwaysRelevant](ue_ue.Pawn.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bAutoDestroyWhenFinished](ue_ue.Pawn.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bBlockInput](ue_ue.Pawn.md#bblockinput)

___

### bCanAffectNavigationGeneration

• **bCanAffectNavigationGeneration**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bCanAffectNavigationGeneration](ue_ue.Pawn.md#bcanaffectnavigationgeneration)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bCanBeDamaged](ue_ue.Pawn.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bCanBeInCluster](ue_ue.Pawn.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bCollideWhenPlacing](ue_ue.Pawn.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bEditable](ue_ue.Pawn.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bEnableAutoLODGeneration](ue_ue.Pawn.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bExchangedRoles](ue_ue.Pawn.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bFindCameraComponentWhenViewTarget](ue_ue.Pawn.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.Pawn.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bHidden](ue_ue.Pawn.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bHiddenEd](ue_ue.Pawn.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bHiddenEdLayer](ue_ue.Pawn.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bHiddenEdLevel](ue_ue.Pawn.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bHiddenEdTemporary](ue_ue.Pawn.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bIgnoresOriginShifting](ue_ue.Pawn.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bIsEditorOnlyActor](ue_ue.Pawn.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bIsEditorPreviewActor](ue_ue.Pawn.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bListedInSceneOutliner](ue_ue.Pawn.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bLockLocation](ue_ue.Pawn.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bNetLoadOnClient](ue_ue.Pawn.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bNetStartup](ue_ue.Pawn.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bNetTemporary](ue_ue.Pawn.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bNetUseOwnerRelevancy](ue_ue.Pawn.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bOnlyRelevantToOwner](ue_ue.Pawn.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bOptimizeBPComponentData](ue_ue.Pawn.md#boptimizebpcomponentdata)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bRelevantForLevelBounds](ue_ue.Pawn.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bRelevantForNetworkReplays](ue_ue.Pawn.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bReplayRewindable](ue_ue.Pawn.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bReplicateMovement](ue_ue.Pawn.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bReplicates](ue_ue.Pawn.md#breplicates)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bTearOff](ue_ue.Pawn.md#btearoff)

___

### bUseControllerRotationPitch

• **bUseControllerRotationPitch**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bUseControllerRotationPitch](ue_ue.Pawn.md#busecontrollerrotationpitch)

___

### bUseControllerRotationRoll

• **bUseControllerRotationRoll**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bUseControllerRotationRoll](ue_ue.Pawn.md#busecontrollerrotationroll)

___

### bUseControllerRotationYaw

• **bUseControllerRotationYaw**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bUseControllerRotationYaw](ue_ue.Pawn.md#busecontrollerrotationyaw)

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

[Pawn](ue_ue.Pawn.md).[ActorHasTag](ue_ue.Pawn.md#actorhastag)

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

[Pawn](ue_ue.Pawn.md).[AddComponent](ue_ue.Pawn.md#addcomponent)

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

[Pawn](ue_ue.Pawn.md).[AddControllerPitchInput](ue_ue.Pawn.md#addcontrollerpitchinput)

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

[Pawn](ue_ue.Pawn.md).[AddControllerRollInput](ue_ue.Pawn.md#addcontrollerrollinput)

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

[Pawn](ue_ue.Pawn.md).[AddControllerYawInput](ue_ue.Pawn.md#addcontrolleryawinput)

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

[Pawn](ue_ue.Pawn.md).[AddMovementInput](ue_ue.Pawn.md#addmovementinput)

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

[Pawn](ue_ue.Pawn.md).[AddTickPrerequisiteActor](ue_ue.Pawn.md#addtickprerequisiteactor)

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

[Pawn](ue_ue.Pawn.md).[AddTickPrerequisiteComponent](ue_ue.Pawn.md#addtickprerequisitecomponent)

___

### ConsumeMovementInputVector

▸ **ConsumeMovementInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ConsumeMovementInputVector](ue_ue.Pawn.md#consumemovementinputvector)

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

[Pawn](ue_ue.Pawn.md).[CreateDefaultSubobject](ue_ue.Pawn.md#createdefaultsubobject)

___

### DetachFromControllerPendingDestroy

▸ **DetachFromControllerPendingDestroy**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[DetachFromControllerPendingDestroy](ue_ue.Pawn.md#detachfromcontrollerpendingdestroy)

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

[Pawn](ue_ue.Pawn.md).[DetachRootComponentFromParent](ue_ue.Pawn.md#detachrootcomponentfromparent)

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

[Pawn](ue_ue.Pawn.md).[DisableInput](ue_ue.Pawn.md#disableinput)

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

[Pawn](ue_ue.Pawn.md).[EnableInput](ue_ue.Pawn.md#enableinput)

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

[Pawn](ue_ue.Pawn.md).[ExecuteUbergraph](ue_ue.Pawn.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[FlushNetDormancy](ue_ue.Pawn.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ForceNetUpdate](ue_ue.Pawn.md#forcenetupdate)

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

[Pawn](ue_ue.Pawn.md).[GetActorBounds](ue_ue.Pawn.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorEnableCollision](ue_ue.Pawn.md#getactorenablecollision)

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

[Pawn](ue_ue.Pawn.md).[GetActorEyesViewPoint](ue_ue.Pawn.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorForwardVector](ue_ue.Pawn.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorLabel](ue_ue.Pawn.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorRelativeScale3D](ue_ue.Pawn.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorRightVector](ue_ue.Pawn.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorScale3D](ue_ue.Pawn.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorTickInterval](ue_ue.Pawn.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorTimeDilation](ue_ue.Pawn.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorUpVector](ue_ue.Pawn.md#getactorupvector)

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

[Pawn](ue_ue.Pawn.md).[GetAllChildActors](ue_ue.Pawn.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetAttachParentActor](ue_ue.Pawn.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetAttachParentSocketName](ue_ue.Pawn.md#getattachparentsocketname)

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

[Pawn](ue_ue.Pawn.md).[GetAttachedActors](ue_ue.Pawn.md#getattachedactors)

___

### GetBaseAimRotation

▸ **GetBaseAimRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetBaseAimRotation](ue_ue.Pawn.md#getbaseaimrotation)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetClass](ue_ue.Pawn.md#getclass)

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

[Pawn](ue_ue.Pawn.md).[GetComponentByClass](ue_ue.Pawn.md#getcomponentbyclass)

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

[Pawn](ue_ue.Pawn.md).[GetComponentsByInterface](ue_ue.Pawn.md#getcomponentsbyinterface)

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

[Pawn](ue_ue.Pawn.md).[GetComponentsByTag](ue_ue.Pawn.md#getcomponentsbytag)

___

### GetControlRotation

▸ **GetControlRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetControlRotation](ue_ue.Pawn.md#getcontrolrotation)

___

### GetController

▸ **GetController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetController](ue_ue.Pawn.md#getcontroller)

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

[Pawn](ue_ue.Pawn.md).[GetDistanceTo](ue_ue.Pawn.md#getdistanceto)

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

[Pawn](ue_ue.Pawn.md).[GetDotProductTo](ue_ue.Pawn.md#getdotproductto)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetFolderPath](ue_ue.Pawn.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetGameTimeSinceCreation](ue_ue.Pawn.md#getgametimesincecreation)

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

[Pawn](ue_ue.Pawn.md).[GetHorizontalDistanceTo](ue_ue.Pawn.md#gethorizontaldistanceto)

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

[Pawn](ue_ue.Pawn.md).[GetHorizontalDotProductTo](ue_ue.Pawn.md#gethorizontaldotproductto)

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

[Pawn](ue_ue.Pawn.md).[GetInputAxisKeyValue](ue_ue.Pawn.md#getinputaxiskeyvalue)

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

[Pawn](ue_ue.Pawn.md).[GetInputAxisValue](ue_ue.Pawn.md#getinputaxisvalue)

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

[Pawn](ue_ue.Pawn.md).[GetInputVectorAxisValue](ue_ue.Pawn.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetInstigator](ue_ue.Pawn.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetInstigatorController](ue_ue.Pawn.md#getinstigatorcontroller)

___

### GetLastMovementInputVector

▸ **GetLastMovementInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetLastMovementInputVector](ue_ue.Pawn.md#getlastmovementinputvector)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetLifeSpan](ue_ue.Pawn.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetLocalRole](ue_ue.Pawn.md#getlocalrole)

___

### GetMovementComponent

▸ **GetMovementComponent**(): [`PawnMovementComponent`](ue_ue.PawnMovementComponent.md)

#### Returns

[`PawnMovementComponent`](ue_ue.PawnMovementComponent.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetMovementComponent](ue_ue.Pawn.md#getmovementcomponent)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetName](ue_ue.Pawn.md#getname)

___

### GetNavAgentLocation

▸ **GetNavAgentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetNavAgentLocation](ue_ue.Pawn.md#getnavagentlocation)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetOuter](ue_ue.Pawn.md#getouter)

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

[Pawn](ue_ue.Pawn.md).[GetOverlappingActors](ue_ue.Pawn.md#getoverlappingactors)

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

[Pawn](ue_ue.Pawn.md).[GetOverlappingComponents](ue_ue.Pawn.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetOwner](ue_ue.Pawn.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetParentActor](ue_ue.Pawn.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetParentComponent](ue_ue.Pawn.md#getparentcomponent)

___

### GetPendingMovementInputVector

▸ **GetPendingMovementInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetPendingMovementInputVector](ue_ue.Pawn.md#getpendingmovementinputvector)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetRemoteRole](ue_ue.Pawn.md#getremoterole)

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

[Pawn](ue_ue.Pawn.md).[GetSquaredDistanceTo](ue_ue.Pawn.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetTickableWhenPaused](ue_ue.Pawn.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetTransform](ue_ue.Pawn.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetVelocity](ue_ue.Pawn.md#getvelocity)

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

[Pawn](ue_ue.Pawn.md).[GetVerticalDistanceTo](ue_ue.Pawn.md#getverticaldistanceto)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetWorld](ue_ue.Pawn.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[HasAuthority](ue_ue.Pawn.md#hasauthority)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsActorBeingDestroyed](ue_ue.Pawn.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsActorTickEnabled](ue_ue.Pawn.md#isactortickenabled)

___

### IsBotControlled

▸ **IsBotControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsBotControlled](ue_ue.Pawn.md#isbotcontrolled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsChildActor](ue_ue.Pawn.md#ischildactor)

___

### IsControlled

▸ **IsControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsControlled](ue_ue.Pawn.md#iscontrolled)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsEditable](ue_ue.Pawn.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsHiddenEd](ue_ue.Pawn.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsHiddenEdAtStartup](ue_ue.Pawn.md#ishiddenedatstartup)

___

### IsLocallyControlled

▸ **IsLocallyControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsLocallyControlled](ue_ue.Pawn.md#islocallycontrolled)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsMoveInputIgnored](ue_ue.Pawn.md#ismoveinputignored)

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

[Pawn](ue_ue.Pawn.md).[IsOverlappingActor](ue_ue.Pawn.md#isoverlappingactor)

___

### IsPawnControlled

▸ **IsPawnControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsPawnControlled](ue_ue.Pawn.md#ispawncontrolled)

___

### IsPlayerControlled

▸ **IsPlayerControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsPlayerControlled](ue_ue.Pawn.md#isplayercontrolled)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsSelectable](ue_ue.Pawn.md#isselectable)

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

[Pawn](ue_ue.Pawn.md).[IsTemporarilyHiddenInEditor](ue_ue.Pawn.md#istemporarilyhiddenineditor)

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

[Pawn](ue_ue.Pawn.md).[K2_AddActorLocalOffset](ue_ue.Pawn.md#k2_addactorlocaloffset)

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

[Pawn](ue_ue.Pawn.md).[K2_AddActorLocalRotation](ue_ue.Pawn.md#k2_addactorlocalrotation)

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

[Pawn](ue_ue.Pawn.md).[K2_AddActorLocalTransform](ue_ue.Pawn.md#k2_addactorlocaltransform)

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

[Pawn](ue_ue.Pawn.md).[K2_AddActorWorldOffset](ue_ue.Pawn.md#k2_addactorworldoffset)

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

[Pawn](ue_ue.Pawn.md).[K2_AddActorWorldRotation](ue_ue.Pawn.md#k2_addactorworldrotation)

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

[Pawn](ue_ue.Pawn.md).[K2_AddActorWorldTransform](ue_ue.Pawn.md#k2_addactorworldtransform)

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

[Pawn](ue_ue.Pawn.md).[K2_AttachRootComponentTo](ue_ue.Pawn.md#k2_attachrootcomponentto)

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

[Pawn](ue_ue.Pawn.md).[K2_AttachRootComponentToActor](ue_ue.Pawn.md#k2_attachrootcomponenttoactor)

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

[Pawn](ue_ue.Pawn.md).[K2_AttachToActor](ue_ue.Pawn.md#k2_attachtoactor)

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

[Pawn](ue_ue.Pawn.md).[K2_AttachToComponent](ue_ue.Pawn.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[K2_DestroyActor](ue_ue.Pawn.md#k2_destroyactor)

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

[Pawn](ue_ue.Pawn.md).[K2_DestroyComponent](ue_ue.Pawn.md#k2_destroycomponent)

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

[Pawn](ue_ue.Pawn.md).[K2_DetachFromActor](ue_ue.Pawn.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[K2_GetActorLocation](ue_ue.Pawn.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[K2_GetActorRotation](ue_ue.Pawn.md#k2_getactorrotation)

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

[Pawn](ue_ue.Pawn.md).[K2_GetComponentsByClass](ue_ue.Pawn.md#k2_getcomponentsbyclass)

___

### K2\_GetMovementInputVector

▸ **K2_GetMovementInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[K2_GetMovementInputVector](ue_ue.Pawn.md#k2_getmovementinputvector)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[K2_GetRootComponent](ue_ue.Pawn.md#k2_getrootcomponent)

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

[Pawn](ue_ue.Pawn.md).[K2_OnBecomeViewTarget](ue_ue.Pawn.md#k2_onbecomeviewtarget)

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

[Pawn](ue_ue.Pawn.md).[K2_OnEndViewTarget](ue_ue.Pawn.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[K2_OnReset](ue_ue.Pawn.md#k2_onreset)

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

[Pawn](ue_ue.Pawn.md).[K2_SetActorLocation](ue_ue.Pawn.md#k2_setactorlocation)

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

[Pawn](ue_ue.Pawn.md).[K2_SetActorLocationAndRotation](ue_ue.Pawn.md#k2_setactorlocationandrotation)

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

[Pawn](ue_ue.Pawn.md).[K2_SetActorRelativeLocation](ue_ue.Pawn.md#k2_setactorrelativelocation)

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

[Pawn](ue_ue.Pawn.md).[K2_SetActorRelativeRotation](ue_ue.Pawn.md#k2_setactorrelativerotation)

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

[Pawn](ue_ue.Pawn.md).[K2_SetActorRelativeTransform](ue_ue.Pawn.md#k2_setactorrelativetransform)

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

[Pawn](ue_ue.Pawn.md).[K2_SetActorRotation](ue_ue.Pawn.md#k2_setactorrotation)

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

[Pawn](ue_ue.Pawn.md).[K2_SetActorTransform](ue_ue.Pawn.md#k2_setactortransform)

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

[Pawn](ue_ue.Pawn.md).[K2_TeleportTo](ue_ue.Pawn.md#k2_teleportto)

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

[Pawn](ue_ue.Pawn.md).[LaunchPawn](ue_ue.Pawn.md#launchpawn)

___

### LookUpAtRate

▸ **LookUpAtRate**(`Rate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Rate` | `number` |

#### Returns

`void`

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

[Pawn](ue_ue.Pawn.md).[MakeMIDForMaterial](ue_ue.Pawn.md#makemidformaterial)

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

[Pawn](ue_ue.Pawn.md).[MakeNoise](ue_ue.Pawn.md#makenoise)

___

### MoveForward

▸ **MoveForward**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

___

### MoveRight

▸ **MoveRight**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

___

### MoveUp\_World

▸ **MoveUp_World**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnRep_AttachmentReplication](ue_ue.Pawn.md#onrep_attachmentreplication)

___

### OnRep\_Controller

▸ **OnRep_Controller**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnRep_Controller](ue_ue.Pawn.md#onrep_controller)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnRep_Instigator](ue_ue.Pawn.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnRep_Owner](ue_ue.Pawn.md#onrep_owner)

___

### OnRep\_PlayerState

▸ **OnRep_PlayerState**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnRep_PlayerState](ue_ue.Pawn.md#onrep_playerstate)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnRep_ReplicateMovement](ue_ue.Pawn.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnRep_ReplicatedMovement](ue_ue.Pawn.md#onrep_replicatedmovement)

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

[Pawn](ue_ue.Pawn.md).[PawnMakeNoise](ue_ue.Pawn.md#pawnmakenoise)

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

[Pawn](ue_ue.Pawn.md).[PrestreamTextures](ue_ue.Pawn.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ReceiveActorBeginCursorOver](ue_ue.Pawn.md#receiveactorbegincursorover)

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

[Pawn](ue_ue.Pawn.md).[ReceiveActorBeginOverlap](ue_ue.Pawn.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ReceiveActorEndCursorOver](ue_ue.Pawn.md#receiveactorendcursorover)

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

[Pawn](ue_ue.Pawn.md).[ReceiveActorEndOverlap](ue_ue.Pawn.md#receiveactorendoverlap)

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

[Pawn](ue_ue.Pawn.md).[ReceiveActorOnClicked](ue_ue.Pawn.md#receiveactoronclicked)

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

[Pawn](ue_ue.Pawn.md).[ReceiveActorOnInputTouchBegin](ue_ue.Pawn.md#receiveactoroninputtouchbegin)

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

[Pawn](ue_ue.Pawn.md).[ReceiveActorOnInputTouchEnd](ue_ue.Pawn.md#receiveactoroninputtouchend)

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

[Pawn](ue_ue.Pawn.md).[ReceiveActorOnInputTouchEnter](ue_ue.Pawn.md#receiveactoroninputtouchenter)

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

[Pawn](ue_ue.Pawn.md).[ReceiveActorOnInputTouchLeave](ue_ue.Pawn.md#receiveactoroninputtouchleave)

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

[Pawn](ue_ue.Pawn.md).[ReceiveActorOnReleased](ue_ue.Pawn.md#receiveactoronreleased)

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

[Pawn](ue_ue.Pawn.md).[ReceiveAnyDamage](ue_ue.Pawn.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ReceiveBeginPlay](ue_ue.Pawn.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ReceiveDestroyed](ue_ue.Pawn.md#receivedestroyed)

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

[Pawn](ue_ue.Pawn.md).[ReceiveEndPlay](ue_ue.Pawn.md#receiveendplay)

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

[Pawn](ue_ue.Pawn.md).[ReceiveHit](ue_ue.Pawn.md#receivehit)

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

[Pawn](ue_ue.Pawn.md).[ReceivePointDamage](ue_ue.Pawn.md#receivepointdamage)

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

[Pawn](ue_ue.Pawn.md).[ReceivePossessed](ue_ue.Pawn.md#receivepossessed)

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

[Pawn](ue_ue.Pawn.md).[ReceiveRadialDamage](ue_ue.Pawn.md#receiveradialdamage)

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

[Pawn](ue_ue.Pawn.md).[ReceiveTick](ue_ue.Pawn.md#receivetick)

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

[Pawn](ue_ue.Pawn.md).[ReceiveUnpossessed](ue_ue.Pawn.md#receiveunpossessed)

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

[Pawn](ue_ue.Pawn.md).[RemoveTickPrerequisiteActor](ue_ue.Pawn.md#removetickprerequisiteactor)

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

[Pawn](ue_ue.Pawn.md).[RemoveTickPrerequisiteComponent](ue_ue.Pawn.md#removetickprerequisitecomponent)

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

[Pawn](ue_ue.Pawn.md).[SetActorEnableCollision](ue_ue.Pawn.md#setactorenablecollision)

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

[Pawn](ue_ue.Pawn.md).[SetActorHiddenInGame](ue_ue.Pawn.md#setactorhiddeningame)

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

[Pawn](ue_ue.Pawn.md).[SetActorLabel](ue_ue.Pawn.md#setactorlabel)

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

[Pawn](ue_ue.Pawn.md).[SetActorRelativeScale3D](ue_ue.Pawn.md#setactorrelativescale3d)

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

[Pawn](ue_ue.Pawn.md).[SetActorScale3D](ue_ue.Pawn.md#setactorscale3d)

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

[Pawn](ue_ue.Pawn.md).[SetActorTickEnabled](ue_ue.Pawn.md#setactortickenabled)

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

[Pawn](ue_ue.Pawn.md).[SetActorTickInterval](ue_ue.Pawn.md#setactortickinterval)

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

[Pawn](ue_ue.Pawn.md).[SetCanAffectNavigationGeneration](ue_ue.Pawn.md#setcanaffectnavigationgeneration)

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

[Pawn](ue_ue.Pawn.md).[SetFolderPath](ue_ue.Pawn.md#setfolderpath)

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

[Pawn](ue_ue.Pawn.md).[SetIsTemporarilyHiddenInEditor](ue_ue.Pawn.md#setistemporarilyhiddenineditor)

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

[Pawn](ue_ue.Pawn.md).[SetLifeSpan](ue_ue.Pawn.md#setlifespan)

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

[Pawn](ue_ue.Pawn.md).[SetNetDormancy](ue_ue.Pawn.md#setnetdormancy)

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

[Pawn](ue_ue.Pawn.md).[SetOwner](ue_ue.Pawn.md#setowner)

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

[Pawn](ue_ue.Pawn.md).[SetReplicateMovement](ue_ue.Pawn.md#setreplicatemovement)

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

[Pawn](ue_ue.Pawn.md).[SetReplicates](ue_ue.Pawn.md#setreplicates)

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

[Pawn](ue_ue.Pawn.md).[SetTickGroup](ue_ue.Pawn.md#settickgroup)

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

[Pawn](ue_ue.Pawn.md).[SetTickableWhenPaused](ue_ue.Pawn.md#settickablewhenpaused)

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

[Pawn](ue_ue.Pawn.md).[SnapRootComponentTo](ue_ue.Pawn.md#snaprootcomponentto)

___

### SpawnDefaultController

▸ **SpawnDefaultController**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[SpawnDefaultController](ue_ue.Pawn.md#spawndefaultcontroller)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[TearOff](ue_ue.Pawn.md#tearoff)

___

### TurnAtRate

▸ **TurnAtRate**(`Rate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Rate` | `number` |

#### Returns

`void`

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[UserConstructionScript](ue_ue.Pawn.md#userconstructionscript)

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

[Pawn](ue_ue.Pawn.md).[WasRecentlyRendered](ue_ue.Pawn.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DefaultPawn`](ue_ue.DefaultPawn.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DefaultPawn`](ue_ue.DefaultPawn.md)

#### Overrides

[Pawn](ue_ue.Pawn.md).[Find](ue_ue.Pawn.md#find)

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

[Pawn](ue_ue.Pawn.md).[GetMovementBaseActor](ue_ue.Pawn.md#getmovementbaseactor)

___

### Load

▸ `Static` **Load**(`InName`): [`DefaultPawn`](ue_ue.DefaultPawn.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DefaultPawn`](ue_ue.DefaultPawn.md)

#### Overrides

[Pawn](ue_ue.Pawn.md).[Load](ue_ue.Pawn.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Pawn](ue_ue.Pawn.md).[StaticClass](ue_ue.Pawn.md#staticclass)
