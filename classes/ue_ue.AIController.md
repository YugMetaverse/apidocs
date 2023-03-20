[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AIController

# Class: AIController

[ue/ue](../modules/ue_ue.md).AIController

## Hierarchy

- [`Controller`](ue_ue.Controller.md)

  ↳ **`AIController`**

  ↳↳ [`DetourCrowdAIController`](ue_ue.DetourCrowdAIController.md)

  ↳↳ [`GridPathAIController`](ue_ue.GridPathAIController.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AIController.md#constructor)

### Properties

- [ActionsComp](ue_ue.AIController.md#actionscomp)
- [ActorLabel](ue_ue.AIController.md#actorlabel)
- [AttachmentReplication](ue_ue.AIController.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.AIController.md#autoreceiveinput)
- [Blackboard](ue_ue.AIController.md#blackboard)
- [BlueprintCreatedComponents](ue_ue.AIController.md#blueprintcreatedcomponents)
- [BrainComponent](ue_ue.AIController.md#braincomponent)
- [CachedGameplayTasksComponent](ue_ue.AIController.md#cachedgameplaytaskscomponent)
- [Character](ue_ue.AIController.md#character)
- [Children](ue_ue.AIController.md#children)
- [ControlRotation](ue_ue.AIController.md#controlrotation)
- [ControllingMatineeActors](ue_ue.AIController.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.AIController.md#customtimedilation)
- [DefaultNavigationFilterClass](ue_ue.AIController.md#defaultnavigationfilterclass)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.AIController.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.AIController.md#folderpath)
- [GroupActor](ue_ue.AIController.md#groupactor)
- [HiddenEditorViews](ue_ue.AIController.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.AIController.md#initiallifespan)
- [InputComponent](ue_ue.AIController.md#inputcomponent)
- [InputPriority](ue_ue.AIController.md#inputpriority)
- [InstanceComponents](ue_ue.AIController.md#instancecomponents)
- [Instigator](ue_ue.AIController.md#instigator)
- [Layers](ue_ue.AIController.md#layers)
- [MinNetUpdateFrequency](ue_ue.AIController.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.AIController.md#netculldistancesquared)
- [NetDormancy](ue_ue.AIController.md#netdormancy)
- [NetDriverName](ue_ue.AIController.md#netdrivername)
- [NetPriority](ue_ue.AIController.md#netpriority)
- [NetTag](ue_ue.AIController.md#nettag)
- [NetUpdateFrequency](ue_ue.AIController.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.AIController.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.AIController.md#onactorendoverlap)
- [OnActorHit](ue_ue.AIController.md#onactorhit)
- [OnBeginCursorOver](ue_ue.AIController.md#onbegincursorover)
- [OnClicked](ue_ue.AIController.md#onclicked)
- [OnDestroyed](ue_ue.AIController.md#ondestroyed)
- [OnEndCursorOver](ue_ue.AIController.md#onendcursorover)
- [OnEndPlay](ue_ue.AIController.md#onendplay)
- [OnInputTouchBegin](ue_ue.AIController.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.AIController.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.AIController.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.AIController.md#oninputtouchleave)
- [OnInstigatedAnyDamage](ue_ue.AIController.md#oninstigatedanydamage)
- [OnReleased](ue_ue.AIController.md#onreleased)
- [OnTakeAnyDamage](ue_ue.AIController.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.AIController.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.AIController.md#ontakeradialdamage)
- [Owner](ue_ue.AIController.md#owner)
- [ParentComponent](ue_ue.AIController.md#parentcomponent)
- [ParentComponentActor](ue_ue.AIController.md#parentcomponentactor)
- [PathFollowingComponent](ue_ue.AIController.md#pathfollowingcomponent)
- [Pawn](ue_ue.AIController.md#pawn)
- [PerceptionComponent](ue_ue.AIController.md#perceptioncomponent)
- [PivotOffset](ue_ue.AIController.md#pivotoffset)
- [PlayerState](ue_ue.AIController.md#playerstate)
- [PrimaryActorTick](ue_ue.AIController.md#primaryactortick)
- [ReceiveMoveCompleted](ue_ue.AIController.md#receivemovecompleted)
- [RemoteRole](ue_ue.AIController.md#remoterole)
- [ReplicatedMovement](ue_ue.AIController.md#replicatedmovement)
- [Role](ue_ue.AIController.md#role)
- [RootComponent](ue_ue.AIController.md#rootcomponent)
- [SpawnCollisionHandlingMethod](ue_ue.AIController.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.AIController.md#spritescale)
- [StateName](ue_ue.AIController.md#statename)
- [Tags](ue_ue.AIController.md#tags)
- [TransformComponent](ue_ue.AIController.md#transformcomponent)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.AIController.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_AIController\_\_](ue_ue.AIController.md#__tid_aicontroller__)
- [\_\_tid\_Actor\_\_](ue_ue.AIController.md#__tid_actor__)
- [\_\_tid\_Controller\_\_](ue_ue.AIController.md#__tid_controller__)
- [\_\_tid\_Object\_\_](ue_ue.AIController.md#__tid_object__)
- [bActorEnableCollision](ue_ue.AIController.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.AIController.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.AIController.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.AIController.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.AIController.md#ballowreceivetickeventondedicatedserver)
- [bAllowStrafe](ue_ue.AIController.md#ballowstrafe)
- [bAllowTickBeforeBeginPlay](ue_ue.AIController.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.AIController.md#balwaysrelevant)
- [bAttachToPawn](ue_ue.AIController.md#battachtopawn)
- [bAutoDestroyWhenFinished](ue_ue.AIController.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.AIController.md#bblockinput)
- [bCanBeDamaged](ue_ue.AIController.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.AIController.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.AIController.md#bcollidewhenplacing)
- [bEditable](ue_ue.AIController.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.AIController.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.AIController.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.AIController.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.AIController.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.AIController.md#bhidden)
- [bHiddenEd](ue_ue.AIController.md#bhiddened)
- [bHiddenEdLayer](ue_ue.AIController.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.AIController.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.AIController.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.AIController.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.AIController.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.AIController.md#biseditorpreviewactor)
- [bLOSflag](ue_ue.AIController.md#blosflag)
- [bListedInSceneOutliner](ue_ue.AIController.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.AIController.md#blocklocation)
- [bNetLoadOnClient](ue_ue.AIController.md#bnetloadonclient)
- [bNetStartup](ue_ue.AIController.md#bnetstartup)
- [bNetTemporary](ue_ue.AIController.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.AIController.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.AIController.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.AIController.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.AIController.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.AIController.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.AIController.md#breplayrewindable)
- [bReplicateMovement](ue_ue.AIController.md#breplicatemovement)
- [bReplicates](ue_ue.AIController.md#breplicates)
- [bSetControlRotationFromPawnOrientation](ue_ue.AIController.md#bsetcontrolrotationfrompawnorientation)
- [bSkipExtraLOSChecks](ue_ue.AIController.md#bskipextraloschecks)
- [bStopAILogicOnUnposses](ue_ue.AIController.md#bstopailogiconunposses)
- [bTearOff](ue_ue.AIController.md#btearoff)
- [bWantsPlayerState](ue_ue.AIController.md#bwantsplayerstate)

### Methods

- [ActorHasTag](ue_ue.AIController.md#actorhastag)
- [AddComponent](ue_ue.AIController.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.AIController.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.AIController.md#addtickprerequisitecomponent)
- [CastToPlayerController](ue_ue.AIController.md#casttoplayercontroller)
- [ClaimTaskResource](ue_ue.AIController.md#claimtaskresource)
- [ClientSetLocation](ue_ue.AIController.md#clientsetlocation)
- [ClientSetRotation](ue_ue.AIController.md#clientsetrotation)
- [CreateDefaultSubobject](ue_ue.AIController.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.AIController.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.AIController.md#disableinput)
- [EnableInput](ue_ue.AIController.md#enableinput)
- [ExecuteUbergraph](ue_ue.AIController.md#executeubergraph)
- [FlushNetDormancy](ue_ue.AIController.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.AIController.md#forcenetupdate)
- [GetAIPerceptionComponent](ue_ue.AIController.md#getaiperceptioncomponent)
- [GetActorBounds](ue_ue.AIController.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.AIController.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.AIController.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.AIController.md#getactorforwardvector)
- [GetActorLabel](ue_ue.AIController.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.AIController.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.AIController.md#getactorrightvector)
- [GetActorScale3D](ue_ue.AIController.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.AIController.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.AIController.md#getactortimedilation)
- [GetActorUpVector](ue_ue.AIController.md#getactorupvector)
- [GetAllChildActors](ue_ue.AIController.md#getallchildactors)
- [GetAttachParentActor](ue_ue.AIController.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.AIController.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.AIController.md#getattachedactors)
- [GetClass](ue_ue.AIController.md#getclass)
- [GetComponentByClass](ue_ue.AIController.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.AIController.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.AIController.md#getcomponentsbytag)
- [GetControlRotation](ue_ue.AIController.md#getcontrolrotation)
- [GetDesiredRotation](ue_ue.AIController.md#getdesiredrotation)
- [GetDistanceTo](ue_ue.AIController.md#getdistanceto)
- [GetDotProductTo](ue_ue.AIController.md#getdotproductto)
- [GetFocalPoint](ue_ue.AIController.md#getfocalpoint)
- [GetFocalPointOnActor](ue_ue.AIController.md#getfocalpointonactor)
- [GetFocusActor](ue_ue.AIController.md#getfocusactor)
- [GetFolderPath](ue_ue.AIController.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.AIController.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.AIController.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.AIController.md#gethorizontaldotproductto)
- [GetImmediateMoveDestination](ue_ue.AIController.md#getimmediatemovedestination)
- [GetInputAxisKeyValue](ue_ue.AIController.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.AIController.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.AIController.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.AIController.md#getinstigator)
- [GetInstigatorController](ue_ue.AIController.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.AIController.md#getlifespan)
- [GetLocalRole](ue_ue.AIController.md#getlocalrole)
- [GetMoveStatus](ue_ue.AIController.md#getmovestatus)
- [GetName](ue_ue.AIController.md#getname)
- [GetOuter](ue_ue.AIController.md#getouter)
- [GetOverlappingActors](ue_ue.AIController.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.AIController.md#getoverlappingcomponents)
- [GetOwner](ue_ue.AIController.md#getowner)
- [GetParentActor](ue_ue.AIController.md#getparentactor)
- [GetParentComponent](ue_ue.AIController.md#getparentcomponent)
- [GetPathFollowingComponent](ue_ue.AIController.md#getpathfollowingcomponent)
- [GetRemoteRole](ue_ue.AIController.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.AIController.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.AIController.md#gettickablewhenpaused)
- [GetTransform](ue_ue.AIController.md#gettransform)
- [GetVelocity](ue_ue.AIController.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.AIController.md#getverticaldistanceto)
- [GetViewTarget](ue_ue.AIController.md#getviewtarget)
- [GetWorld](ue_ue.AIController.md#getworld)
- [HasAuthority](ue_ue.AIController.md#hasauthority)
- [HasPartialPath](ue_ue.AIController.md#haspartialpath)
- [IsActorBeingDestroyed](ue_ue.AIController.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.AIController.md#isactortickenabled)
- [IsChildActor](ue_ue.AIController.md#ischildactor)
- [IsEditable](ue_ue.AIController.md#iseditable)
- [IsHiddenEd](ue_ue.AIController.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.AIController.md#ishiddenedatstartup)
- [IsLocalController](ue_ue.AIController.md#islocalcontroller)
- [IsLocalPlayerController](ue_ue.AIController.md#islocalplayercontroller)
- [IsLookInputIgnored](ue_ue.AIController.md#islookinputignored)
- [IsMoveInputIgnored](ue_ue.AIController.md#ismoveinputignored)
- [IsOverlappingActor](ue_ue.AIController.md#isoverlappingactor)
- [IsPlayerController](ue_ue.AIController.md#isplayercontroller)
- [IsSelectable](ue_ue.AIController.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.AIController.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.AIController.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.AIController.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.AIController.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.AIController.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.AIController.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.AIController.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.AIController.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.AIController.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.AIController.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.AIController.md#k2_attachtocomponent)
- [K2\_ClearFocus](ue_ue.AIController.md#k2_clearfocus)
- [K2\_DestroyActor](ue_ue.AIController.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.AIController.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.AIController.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.AIController.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.AIController.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.AIController.md#k2_getcomponentsbyclass)
- [K2\_GetPawn](ue_ue.AIController.md#k2_getpawn)
- [K2\_GetRootComponent](ue_ue.AIController.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.AIController.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.AIController.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.AIController.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.AIController.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.AIController.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.AIController.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.AIController.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.AIController.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.AIController.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.AIController.md#k2_setactortransform)
- [K2\_SetFocalPoint](ue_ue.AIController.md#k2_setfocalpoint)
- [K2\_SetFocus](ue_ue.AIController.md#k2_setfocus)
- [K2\_TeleportTo](ue_ue.AIController.md#k2_teleportto)
- [LineOfSightTo](ue_ue.AIController.md#lineofsightto)
- [MakeMIDForMaterial](ue_ue.AIController.md#makemidformaterial)
- [MakeNoise](ue_ue.AIController.md#makenoise)
- [MoveToActor](ue_ue.AIController.md#movetoactor)
- [MoveToLocation](ue_ue.AIController.md#movetolocation)
- [OnGameplayTaskResourcesClaimed](ue_ue.AIController.md#ongameplaytaskresourcesclaimed)
- [OnRep\_AttachmentReplication](ue_ue.AIController.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.AIController.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.AIController.md#onrep_owner)
- [OnRep\_Pawn](ue_ue.AIController.md#onrep_pawn)
- [OnRep\_PlayerState](ue_ue.AIController.md#onrep_playerstate)
- [OnRep\_ReplicateMovement](ue_ue.AIController.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.AIController.md#onrep_replicatedmovement)
- [OnUsingBlackBoard](ue_ue.AIController.md#onusingblackboard)
- [Possess](ue_ue.AIController.md#possess)
- [PrestreamTextures](ue_ue.AIController.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.AIController.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.AIController.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.AIController.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.AIController.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.AIController.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.AIController.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.AIController.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.AIController.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.AIController.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.AIController.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.AIController.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.AIController.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.AIController.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.AIController.md#receiveendplay)
- [ReceiveHit](ue_ue.AIController.md#receivehit)
- [ReceiveInstigatedAnyDamage](ue_ue.AIController.md#receiveinstigatedanydamage)
- [ReceivePointDamage](ue_ue.AIController.md#receivepointdamage)
- [ReceivePossess](ue_ue.AIController.md#receivepossess)
- [ReceiveRadialDamage](ue_ue.AIController.md#receiveradialdamage)
- [ReceiveTick](ue_ue.AIController.md#receivetick)
- [ReceiveUnPossess](ue_ue.AIController.md#receiveunpossess)
- [RemoveTickPrerequisiteActor](ue_ue.AIController.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.AIController.md#removetickprerequisitecomponent)
- [ResetIgnoreInputFlags](ue_ue.AIController.md#resetignoreinputflags)
- [ResetIgnoreLookInput](ue_ue.AIController.md#resetignorelookinput)
- [ResetIgnoreMoveInput](ue_ue.AIController.md#resetignoremoveinput)
- [RunBehaviorTree](ue_ue.AIController.md#runbehaviortree)
- [SetActorEnableCollision](ue_ue.AIController.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.AIController.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.AIController.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.AIController.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.AIController.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.AIController.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.AIController.md#setactortickinterval)
- [SetControlRotation](ue_ue.AIController.md#setcontrolrotation)
- [SetFolderPath](ue_ue.AIController.md#setfolderpath)
- [SetIgnoreLookInput](ue_ue.AIController.md#setignorelookinput)
- [SetIgnoreMoveInput](ue_ue.AIController.md#setignoremoveinput)
- [SetInitialLocationAndRotation](ue_ue.AIController.md#setinitiallocationandrotation)
- [SetIsTemporarilyHiddenInEditor](ue_ue.AIController.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.AIController.md#setlifespan)
- [SetMoveBlockDetection](ue_ue.AIController.md#setmoveblockdetection)
- [SetNetDormancy](ue_ue.AIController.md#setnetdormancy)
- [SetOwner](ue_ue.AIController.md#setowner)
- [SetPathFollowingComponent](ue_ue.AIController.md#setpathfollowingcomponent)
- [SetReplicateMovement](ue_ue.AIController.md#setreplicatemovement)
- [SetReplicates](ue_ue.AIController.md#setreplicates)
- [SetTickGroup](ue_ue.AIController.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.AIController.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.AIController.md#snaprootcomponentto)
- [StopMovement](ue_ue.AIController.md#stopmovement)
- [TearOff](ue_ue.AIController.md#tearoff)
- [UnPossess](ue_ue.AIController.md#unpossess)
- [UnclaimTaskResource](ue_ue.AIController.md#unclaimtaskresource)
- [UseBlackboard](ue_ue.AIController.md#useblackboard)
- [UserConstructionScript](ue_ue.AIController.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.AIController.md#wasrecentlyrendered)
- [Find](ue_ue.AIController.md#find)
- [Load](ue_ue.AIController.md#load)
- [StaticClass](ue_ue.AIController.md#staticclass)

## Constructors

### constructor

• **new AIController**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Controller](ue_ue.Controller.md).[constructor](ue_ue.Controller.md#constructor)

## Properties

### ActionsComp

• **ActionsComp**: [`PawnActionsComponent`](ue_ue.PawnActionsComponent.md)

___

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[Controller](ue_ue.Controller.md).[ActorLabel](ue_ue.Controller.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[AttachmentReplication](ue_ue.Controller.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[AutoReceiveInput](ue_ue.Controller.md#autoreceiveinput)

___

### Blackboard

• **Blackboard**: [`BlackboardComponent`](ue_ue.BlackboardComponent.md)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Controller](ue_ue.Controller.md).[BlueprintCreatedComponents](ue_ue.Controller.md#blueprintcreatedcomponents)

___

### BrainComponent

• **BrainComponent**: [`BrainComponent`](ue_ue.BrainComponent.md)

___

### CachedGameplayTasksComponent

• **CachedGameplayTasksComponent**: [`GameplayTasksComponent`](ue_ue.GameplayTasksComponent.md)

___

### Character

• **Character**: [`Character`](ue_ue.Character.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[Character](ue_ue.Controller.md#character)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Controller](ue_ue.Controller.md).[Children](ue_ue.Controller.md#children)

___

### ControlRotation

• **ControlRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[ControlRotation](ue_ue.Controller.md#controlrotation)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[Controller](ue_ue.Controller.md).[ControllingMatineeActors](ue_ue.Controller.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[CustomTimeDilation](ue_ue.Controller.md#customtimedilation)

___

### DefaultNavigationFilterClass

• **DefaultNavigationFilterClass**: [`Class`](ue_ue.Class.md)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.Controller.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[Controller](ue_ue.Controller.md).[FolderPath](ue_ue.Controller.md#folderpath)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GroupActor](ue_ue.Controller.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[Controller](ue_ue.Controller.md).[HiddenEditorViews](ue_ue.Controller.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[InitialLifeSpan](ue_ue.Controller.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[InputComponent](ue_ue.Controller.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[InputPriority](ue_ue.Controller.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Controller](ue_ue.Controller.md).[InstanceComponents](ue_ue.Controller.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[Instigator](ue_ue.Controller.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[Layers](ue_ue.Controller.md#layers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[MinNetUpdateFrequency](ue_ue.Controller.md#minnetupdatefrequency)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[NetCullDistanceSquared](ue_ue.Controller.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[NetDormancy](ue_ue.Controller.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[Controller](ue_ue.Controller.md).[NetDriverName](ue_ue.Controller.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[NetPriority](ue_ue.Controller.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[NetTag](ue_ue.Controller.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[NetUpdateFrequency](ue_ue.Controller.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnActorBeginOverlap](ue_ue.Controller.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnActorEndOverlap](ue_ue.Controller.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnActorHit](ue_ue.Controller.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnBeginCursorOver](ue_ue.Controller.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnClicked](ue_ue.Controller.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnDestroyed](ue_ue.Controller.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnEndCursorOver](ue_ue.Controller.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnEndPlay](ue_ue.Controller.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnInputTouchBegin](ue_ue.Controller.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnInputTouchEnd](ue_ue.Controller.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnInputTouchEnter](ue_ue.Controller.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnInputTouchLeave](ue_ue.Controller.md#oninputtouchleave)

___

### OnInstigatedAnyDamage

• **OnInstigatedAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnInstigatedAnyDamage](ue_ue.Controller.md#oninstigatedanydamage)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnReleased](ue_ue.Controller.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnTakeAnyDamage](ue_ue.Controller.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnTakePointDamage](ue_ue.Controller.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnTakeRadialDamage](ue_ue.Controller.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[Owner](ue_ue.Controller.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[Controller](ue_ue.Controller.md).[ParentComponent](ue_ue.Controller.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Controller](ue_ue.Controller.md).[ParentComponentActor](ue_ue.Controller.md#parentcomponentactor)

___

### PathFollowingComponent

• **PathFollowingComponent**: [`PathFollowingComponent`](ue_ue.PathFollowingComponent.md)

___

### Pawn

• **Pawn**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[Pawn](ue_ue.Controller.md#pawn)

___

### PerceptionComponent

• **PerceptionComponent**: [`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[PivotOffset](ue_ue.Controller.md#pivotoffset)

___

### PlayerState

• **PlayerState**: [`PlayerState`](ue_ue.PlayerState.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[PlayerState](ue_ue.Controller.md#playerstate)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[PrimaryActorTick](ue_ue.Controller.md#primaryactortick)

___

### ReceiveMoveCompleted

• **ReceiveMoveCompleted**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`RequestID`: [`AIRequestID`](ue_ue.AIRequestID.md), `Result`: [`EPathFollowingResult`](../enums/ue_ue.EPathFollowingResult.md)) => `void`\>

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[RemoteRole](ue_ue.Controller.md#remoterole)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[ReplicatedMovement](ue_ue.Controller.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[Role](ue_ue.Controller.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[RootComponent](ue_ue.Controller.md#rootcomponent)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[SpawnCollisionHandlingMethod](ue_ue.Controller.md#spawncollisionhandlingmethod)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[SpriteScale](ue_ue.Controller.md#spritescale)

___

### StateName

• **StateName**: `string`

#### Inherited from

[Controller](ue_ue.Controller.md).[StateName](ue_ue.Controller.md#statename)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[Tags](ue_ue.Controller.md#tags)

___

### TransformComponent

• **TransformComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[TransformComponent](ue_ue.Controller.md#transformcomponent)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.Controller.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_AIController\_\_

• **\_\_tid\_AIController\_\_**: `boolean`

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[__tid_Actor__](ue_ue.Controller.md#__tid_actor__)

___

### \_\_tid\_Controller\_\_

• **\_\_tid\_Controller\_\_**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[__tid_Controller__](ue_ue.Controller.md#__tid_controller__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[__tid_Object__](ue_ue.Controller.md#__tid_object__)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bActorEnableCollision](ue_ue.Controller.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bActorIsBeingDestroyed](ue_ue.Controller.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bActorLabelEditable](ue_ue.Controller.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bActorSeamlessTraveled](ue_ue.Controller.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.Controller.md#ballowreceivetickeventondedicatedserver)

___

### bAllowStrafe

• **bAllowStrafe**: `boolean`

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bAllowTickBeforeBeginPlay](ue_ue.Controller.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bAlwaysRelevant](ue_ue.Controller.md#balwaysrelevant)

___

### bAttachToPawn

• **bAttachToPawn**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bAttachToPawn](ue_ue.Controller.md#battachtopawn)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bAutoDestroyWhenFinished](ue_ue.Controller.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bBlockInput](ue_ue.Controller.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bCanBeDamaged](ue_ue.Controller.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bCanBeInCluster](ue_ue.Controller.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bCollideWhenPlacing](ue_ue.Controller.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bEditable](ue_ue.Controller.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bEnableAutoLODGeneration](ue_ue.Controller.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bExchangedRoles](ue_ue.Controller.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bFindCameraComponentWhenViewTarget](ue_ue.Controller.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.Controller.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bHidden](ue_ue.Controller.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bHiddenEd](ue_ue.Controller.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bHiddenEdLayer](ue_ue.Controller.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bHiddenEdLevel](ue_ue.Controller.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bHiddenEdTemporary](ue_ue.Controller.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bIgnoresOriginShifting](ue_ue.Controller.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bIsEditorOnlyActor](ue_ue.Controller.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bIsEditorPreviewActor](ue_ue.Controller.md#biseditorpreviewactor)

___

### bLOSflag

• **bLOSflag**: `boolean`

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bListedInSceneOutliner](ue_ue.Controller.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bLockLocation](ue_ue.Controller.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bNetLoadOnClient](ue_ue.Controller.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bNetStartup](ue_ue.Controller.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bNetTemporary](ue_ue.Controller.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bNetUseOwnerRelevancy](ue_ue.Controller.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bOnlyRelevantToOwner](ue_ue.Controller.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bOptimizeBPComponentData](ue_ue.Controller.md#boptimizebpcomponentdata)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bRelevantForLevelBounds](ue_ue.Controller.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bRelevantForNetworkReplays](ue_ue.Controller.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bReplayRewindable](ue_ue.Controller.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bReplicateMovement](ue_ue.Controller.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bReplicates](ue_ue.Controller.md#breplicates)

___

### bSetControlRotationFromPawnOrientation

• **bSetControlRotationFromPawnOrientation**: `boolean`

___

### bSkipExtraLOSChecks

• **bSkipExtraLOSChecks**: `boolean`

___

### bStopAILogicOnUnposses

• **bStopAILogicOnUnposses**: `boolean`

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bTearOff](ue_ue.Controller.md#btearoff)

___

### bWantsPlayerState

• **bWantsPlayerState**: `boolean`

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

[Controller](ue_ue.Controller.md).[ActorHasTag](ue_ue.Controller.md#actorhastag)

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

[Controller](ue_ue.Controller.md).[AddComponent](ue_ue.Controller.md#addcomponent)

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

[Controller](ue_ue.Controller.md).[AddTickPrerequisiteActor](ue_ue.Controller.md#addtickprerequisiteactor)

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

[Controller](ue_ue.Controller.md).[AddTickPrerequisiteComponent](ue_ue.Controller.md#addtickprerequisitecomponent)

___

### CastToPlayerController

▸ **CastToPlayerController**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[CastToPlayerController](ue_ue.Controller.md#casttoplayercontroller)

___

### ClaimTaskResource

▸ **ClaimTaskResource**(`ResourceClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ResourceClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

___

### ClientSetLocation

▸ **ClientSetLocation**(`NewLocation`, `NewRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ClientSetLocation](ue_ue.Controller.md#clientsetlocation)

___

### ClientSetRotation

▸ **ClientSetRotation**(`NewRotation`, `bResetCamera`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bResetCamera` | `boolean` |

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ClientSetRotation](ue_ue.Controller.md#clientsetrotation)

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

[Controller](ue_ue.Controller.md).[CreateDefaultSubobject](ue_ue.Controller.md#createdefaultsubobject)

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

[Controller](ue_ue.Controller.md).[DetachRootComponentFromParent](ue_ue.Controller.md#detachrootcomponentfromparent)

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

[Controller](ue_ue.Controller.md).[DisableInput](ue_ue.Controller.md#disableinput)

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

[Controller](ue_ue.Controller.md).[EnableInput](ue_ue.Controller.md#enableinput)

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

[Controller](ue_ue.Controller.md).[ExecuteUbergraph](ue_ue.Controller.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[FlushNetDormancy](ue_ue.Controller.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ForceNetUpdate](ue_ue.Controller.md#forcenetupdate)

___

### GetAIPerceptionComponent

▸ **GetAIPerceptionComponent**(): [`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)

#### Returns

[`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)

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

[Controller](ue_ue.Controller.md).[GetActorBounds](ue_ue.Controller.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorEnableCollision](ue_ue.Controller.md#getactorenablecollision)

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

[Controller](ue_ue.Controller.md).[GetActorEyesViewPoint](ue_ue.Controller.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorForwardVector](ue_ue.Controller.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorLabel](ue_ue.Controller.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorRelativeScale3D](ue_ue.Controller.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorRightVector](ue_ue.Controller.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorScale3D](ue_ue.Controller.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorTickInterval](ue_ue.Controller.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorTimeDilation](ue_ue.Controller.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorUpVector](ue_ue.Controller.md#getactorupvector)

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

[Controller](ue_ue.Controller.md).[GetAllChildActors](ue_ue.Controller.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetAttachParentActor](ue_ue.Controller.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetAttachParentSocketName](ue_ue.Controller.md#getattachparentsocketname)

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

[Controller](ue_ue.Controller.md).[GetAttachedActors](ue_ue.Controller.md#getattachedactors)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetClass](ue_ue.Controller.md#getclass)

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

[Controller](ue_ue.Controller.md).[GetComponentByClass](ue_ue.Controller.md#getcomponentbyclass)

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

[Controller](ue_ue.Controller.md).[GetComponentsByInterface](ue_ue.Controller.md#getcomponentsbyinterface)

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

[Controller](ue_ue.Controller.md).[GetComponentsByTag](ue_ue.Controller.md#getcomponentsbytag)

___

### GetControlRotation

▸ **GetControlRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetControlRotation](ue_ue.Controller.md#getcontrolrotation)

___

### GetDesiredRotation

▸ **GetDesiredRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetDesiredRotation](ue_ue.Controller.md#getdesiredrotation)

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

[Controller](ue_ue.Controller.md).[GetDistanceTo](ue_ue.Controller.md#getdistanceto)

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

[Controller](ue_ue.Controller.md).[GetDotProductTo](ue_ue.Controller.md#getdotproductto)

___

### GetFocalPoint

▸ **GetFocalPoint**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetFocalPointOnActor

▸ **GetFocalPointOnActor**(`Actor`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetFocusActor

▸ **GetFocusActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetFolderPath](ue_ue.Controller.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetGameTimeSinceCreation](ue_ue.Controller.md#getgametimesincecreation)

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

[Controller](ue_ue.Controller.md).[GetHorizontalDistanceTo](ue_ue.Controller.md#gethorizontaldistanceto)

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

[Controller](ue_ue.Controller.md).[GetHorizontalDotProductTo](ue_ue.Controller.md#gethorizontaldotproductto)

___

### GetImmediateMoveDestination

▸ **GetImmediateMoveDestination**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

[Controller](ue_ue.Controller.md).[GetInputAxisKeyValue](ue_ue.Controller.md#getinputaxiskeyvalue)

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

[Controller](ue_ue.Controller.md).[GetInputAxisValue](ue_ue.Controller.md#getinputaxisvalue)

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

[Controller](ue_ue.Controller.md).[GetInputVectorAxisValue](ue_ue.Controller.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetInstigator](ue_ue.Controller.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetInstigatorController](ue_ue.Controller.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetLifeSpan](ue_ue.Controller.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetLocalRole](ue_ue.Controller.md#getlocalrole)

___

### GetMoveStatus

▸ **GetMoveStatus**(): [`EPathFollowingStatus`](../enums/ue_ue.EPathFollowingStatus.md)

#### Returns

[`EPathFollowingStatus`](../enums/ue_ue.EPathFollowingStatus.md)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetName](ue_ue.Controller.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetOuter](ue_ue.Controller.md#getouter)

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

[Controller](ue_ue.Controller.md).[GetOverlappingActors](ue_ue.Controller.md#getoverlappingactors)

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

[Controller](ue_ue.Controller.md).[GetOverlappingComponents](ue_ue.Controller.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetOwner](ue_ue.Controller.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetParentActor](ue_ue.Controller.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetParentComponent](ue_ue.Controller.md#getparentcomponent)

___

### GetPathFollowingComponent

▸ **GetPathFollowingComponent**(): [`PathFollowingComponent`](ue_ue.PathFollowingComponent.md)

#### Returns

[`PathFollowingComponent`](ue_ue.PathFollowingComponent.md)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetRemoteRole](ue_ue.Controller.md#getremoterole)

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

[Controller](ue_ue.Controller.md).[GetSquaredDistanceTo](ue_ue.Controller.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetTickableWhenPaused](ue_ue.Controller.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetTransform](ue_ue.Controller.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetVelocity](ue_ue.Controller.md#getvelocity)

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

[Controller](ue_ue.Controller.md).[GetVerticalDistanceTo](ue_ue.Controller.md#getverticaldistanceto)

___

### GetViewTarget

▸ **GetViewTarget**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetViewTarget](ue_ue.Controller.md#getviewtarget)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetWorld](ue_ue.Controller.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[HasAuthority](ue_ue.Controller.md#hasauthority)

___

### HasPartialPath

▸ **HasPartialPath**(): `boolean`

#### Returns

`boolean`

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsActorBeingDestroyed](ue_ue.Controller.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsActorTickEnabled](ue_ue.Controller.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsChildActor](ue_ue.Controller.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsEditable](ue_ue.Controller.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsHiddenEd](ue_ue.Controller.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsHiddenEdAtStartup](ue_ue.Controller.md#ishiddenedatstartup)

___

### IsLocalController

▸ **IsLocalController**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsLocalController](ue_ue.Controller.md#islocalcontroller)

___

### IsLocalPlayerController

▸ **IsLocalPlayerController**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsLocalPlayerController](ue_ue.Controller.md#islocalplayercontroller)

___

### IsLookInputIgnored

▸ **IsLookInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsLookInputIgnored](ue_ue.Controller.md#islookinputignored)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsMoveInputIgnored](ue_ue.Controller.md#ismoveinputignored)

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

[Controller](ue_ue.Controller.md).[IsOverlappingActor](ue_ue.Controller.md#isoverlappingactor)

___

### IsPlayerController

▸ **IsPlayerController**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsPlayerController](ue_ue.Controller.md#isplayercontroller)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsSelectable](ue_ue.Controller.md#isselectable)

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

[Controller](ue_ue.Controller.md).[IsTemporarilyHiddenInEditor](ue_ue.Controller.md#istemporarilyhiddenineditor)

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

[Controller](ue_ue.Controller.md).[K2_AddActorLocalOffset](ue_ue.Controller.md#k2_addactorlocaloffset)

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

[Controller](ue_ue.Controller.md).[K2_AddActorLocalRotation](ue_ue.Controller.md#k2_addactorlocalrotation)

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

[Controller](ue_ue.Controller.md).[K2_AddActorLocalTransform](ue_ue.Controller.md#k2_addactorlocaltransform)

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

[Controller](ue_ue.Controller.md).[K2_AddActorWorldOffset](ue_ue.Controller.md#k2_addactorworldoffset)

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

[Controller](ue_ue.Controller.md).[K2_AddActorWorldRotation](ue_ue.Controller.md#k2_addactorworldrotation)

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

[Controller](ue_ue.Controller.md).[K2_AddActorWorldTransform](ue_ue.Controller.md#k2_addactorworldtransform)

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

[Controller](ue_ue.Controller.md).[K2_AttachRootComponentTo](ue_ue.Controller.md#k2_attachrootcomponentto)

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

[Controller](ue_ue.Controller.md).[K2_AttachRootComponentToActor](ue_ue.Controller.md#k2_attachrootcomponenttoactor)

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

[Controller](ue_ue.Controller.md).[K2_AttachToActor](ue_ue.Controller.md#k2_attachtoactor)

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

[Controller](ue_ue.Controller.md).[K2_AttachToComponent](ue_ue.Controller.md#k2_attachtocomponent)

___

### K2\_ClearFocus

▸ **K2_ClearFocus**(): `void`

#### Returns

`void`

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[K2_DestroyActor](ue_ue.Controller.md#k2_destroyactor)

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

[Controller](ue_ue.Controller.md).[K2_DestroyComponent](ue_ue.Controller.md#k2_destroycomponent)

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

[Controller](ue_ue.Controller.md).[K2_DetachFromActor](ue_ue.Controller.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[K2_GetActorLocation](ue_ue.Controller.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[K2_GetActorRotation](ue_ue.Controller.md#k2_getactorrotation)

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

[Controller](ue_ue.Controller.md).[K2_GetComponentsByClass](ue_ue.Controller.md#k2_getcomponentsbyclass)

___

### K2\_GetPawn

▸ **K2_GetPawn**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[K2_GetPawn](ue_ue.Controller.md#k2_getpawn)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[K2_GetRootComponent](ue_ue.Controller.md#k2_getrootcomponent)

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

[Controller](ue_ue.Controller.md).[K2_OnBecomeViewTarget](ue_ue.Controller.md#k2_onbecomeviewtarget)

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

[Controller](ue_ue.Controller.md).[K2_OnEndViewTarget](ue_ue.Controller.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[K2_OnReset](ue_ue.Controller.md#k2_onreset)

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

[Controller](ue_ue.Controller.md).[K2_SetActorLocation](ue_ue.Controller.md#k2_setactorlocation)

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

[Controller](ue_ue.Controller.md).[K2_SetActorLocationAndRotation](ue_ue.Controller.md#k2_setactorlocationandrotation)

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

[Controller](ue_ue.Controller.md).[K2_SetActorRelativeLocation](ue_ue.Controller.md#k2_setactorrelativelocation)

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

[Controller](ue_ue.Controller.md).[K2_SetActorRelativeRotation](ue_ue.Controller.md#k2_setactorrelativerotation)

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

[Controller](ue_ue.Controller.md).[K2_SetActorRelativeTransform](ue_ue.Controller.md#k2_setactorrelativetransform)

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

[Controller](ue_ue.Controller.md).[K2_SetActorRotation](ue_ue.Controller.md#k2_setactorrotation)

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

[Controller](ue_ue.Controller.md).[K2_SetActorTransform](ue_ue.Controller.md#k2_setactortransform)

___

### K2\_SetFocalPoint

▸ **K2_SetFocalPoint**(`FP`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FP` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### K2\_SetFocus

▸ **K2_SetFocus**(`NewFocus`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewFocus` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

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

[Controller](ue_ue.Controller.md).[K2_TeleportTo](ue_ue.Controller.md#k2_teleportto)

___

### LineOfSightTo

▸ **LineOfSightTo**(`Other`, `ViewPoint?`, `bAlternateChecks?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `ViewPoint?` | [`Vector`](ue_ue_s.Vector.md) |
| `bAlternateChecks?` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[LineOfSightTo](ue_ue.Controller.md#lineofsightto)

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

[Controller](ue_ue.Controller.md).[MakeMIDForMaterial](ue_ue.Controller.md#makemidformaterial)

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

[Controller](ue_ue.Controller.md).[MakeNoise](ue_ue.Controller.md#makenoise)

___

### MoveToActor

▸ **MoveToActor**(`Goal`, `AcceptanceRadius?`, `bStopOnOverlap?`, `bUsePathfinding?`, `bCanStrafe?`, `FilterClass?`, `bAllowPartialPath?`): [`EPathFollowingRequestResult`](../enums/ue_ue.EPathFollowingRequestResult.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Goal` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `AcceptanceRadius?` | `number` |
| `bStopOnOverlap?` | `boolean` |
| `bUsePathfinding?` | `boolean` |
| `bCanStrafe?` | `boolean` |
| `FilterClass?` | [`Class`](ue_ue.Class.md) |
| `bAllowPartialPath?` | `boolean` |

#### Returns

[`EPathFollowingRequestResult`](../enums/ue_ue.EPathFollowingRequestResult.md)

___

### MoveToLocation

▸ **MoveToLocation**(`Dest`, `AcceptanceRadius?`, `bStopOnOverlap?`, `bUsePathfinding?`, `bProjectDestinationToNavigation?`, `bCanStrafe?`, `FilterClass?`, `bAllowPartialPath?`): [`EPathFollowingRequestResult`](../enums/ue_ue.EPathFollowingRequestResult.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Dest` | [`Vector`](ue_ue_s.Vector.md) |
| `AcceptanceRadius?` | `number` |
| `bStopOnOverlap?` | `boolean` |
| `bUsePathfinding?` | `boolean` |
| `bProjectDestinationToNavigation?` | `boolean` |
| `bCanStrafe?` | `boolean` |
| `FilterClass?` | [`Class`](ue_ue.Class.md) |
| `bAllowPartialPath?` | `boolean` |

#### Returns

[`EPathFollowingRequestResult`](../enums/ue_ue.EPathFollowingRequestResult.md)

___

### OnGameplayTaskResourcesClaimed

▸ **OnGameplayTaskResourcesClaimed**(`NewlyClaimed`, `FreshlyReleased`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewlyClaimed` | [`GameplayResourceSet`](ue_ue.GameplayResourceSet.md) |
| `FreshlyReleased` | [`GameplayResourceSet`](ue_ue.GameplayResourceSet.md) |

#### Returns

`void`

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[OnRep_AttachmentReplication](ue_ue.Controller.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[OnRep_Instigator](ue_ue.Controller.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[OnRep_Owner](ue_ue.Controller.md#onrep_owner)

___

### OnRep\_Pawn

▸ **OnRep_Pawn**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[OnRep_Pawn](ue_ue.Controller.md#onrep_pawn)

___

### OnRep\_PlayerState

▸ **OnRep_PlayerState**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[OnRep_PlayerState](ue_ue.Controller.md#onrep_playerstate)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[OnRep_ReplicateMovement](ue_ue.Controller.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[OnRep_ReplicatedMovement](ue_ue.Controller.md#onrep_replicatedmovement)

___

### OnUsingBlackBoard

▸ **OnUsingBlackBoard**(`BlackboardComp`, `BlackboardAsset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BlackboardComp` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BlackboardComponent`](ue_ue.BlackboardComponent.md)\> |
| `BlackboardAsset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BlackboardData`](ue_ue.BlackboardData.md)\> |

#### Returns

`void`

___

### Possess

▸ **Possess**(`InPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[Possess](ue_ue.Controller.md#possess)

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

[Controller](ue_ue.Controller.md).[PrestreamTextures](ue_ue.Controller.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ReceiveActorBeginCursorOver](ue_ue.Controller.md#receiveactorbegincursorover)

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

[Controller](ue_ue.Controller.md).[ReceiveActorBeginOverlap](ue_ue.Controller.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ReceiveActorEndCursorOver](ue_ue.Controller.md#receiveactorendcursorover)

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

[Controller](ue_ue.Controller.md).[ReceiveActorEndOverlap](ue_ue.Controller.md#receiveactorendoverlap)

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

[Controller](ue_ue.Controller.md).[ReceiveActorOnClicked](ue_ue.Controller.md#receiveactoronclicked)

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

[Controller](ue_ue.Controller.md).[ReceiveActorOnInputTouchBegin](ue_ue.Controller.md#receiveactoroninputtouchbegin)

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

[Controller](ue_ue.Controller.md).[ReceiveActorOnInputTouchEnd](ue_ue.Controller.md#receiveactoroninputtouchend)

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

[Controller](ue_ue.Controller.md).[ReceiveActorOnInputTouchEnter](ue_ue.Controller.md#receiveactoroninputtouchenter)

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

[Controller](ue_ue.Controller.md).[ReceiveActorOnInputTouchLeave](ue_ue.Controller.md#receiveactoroninputtouchleave)

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

[Controller](ue_ue.Controller.md).[ReceiveActorOnReleased](ue_ue.Controller.md#receiveactoronreleased)

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

[Controller](ue_ue.Controller.md).[ReceiveAnyDamage](ue_ue.Controller.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ReceiveBeginPlay](ue_ue.Controller.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ReceiveDestroyed](ue_ue.Controller.md#receivedestroyed)

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

[Controller](ue_ue.Controller.md).[ReceiveEndPlay](ue_ue.Controller.md#receiveendplay)

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

[Controller](ue_ue.Controller.md).[ReceiveHit](ue_ue.Controller.md#receivehit)

___

### ReceiveInstigatedAnyDamage

▸ **ReceiveInstigatedAnyDamage**(`Damage`, `DamageType`, `DamagedActor`, `DamageCauser`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Damage` | `number` |
| `DamageType` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\> |
| `DamagedActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `DamageCauser` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ReceiveInstigatedAnyDamage](ue_ue.Controller.md#receiveinstigatedanydamage)

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

[Controller](ue_ue.Controller.md).[ReceivePointDamage](ue_ue.Controller.md#receivepointdamage)

___

### ReceivePossess

▸ **ReceivePossess**(`PossessedPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PossessedPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ReceivePossess](ue_ue.Controller.md#receivepossess)

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

[Controller](ue_ue.Controller.md).[ReceiveRadialDamage](ue_ue.Controller.md#receiveradialdamage)

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

[Controller](ue_ue.Controller.md).[ReceiveTick](ue_ue.Controller.md#receivetick)

___

### ReceiveUnPossess

▸ **ReceiveUnPossess**(`UnpossessedPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `UnpossessedPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ReceiveUnPossess](ue_ue.Controller.md#receiveunpossess)

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

[Controller](ue_ue.Controller.md).[RemoveTickPrerequisiteActor](ue_ue.Controller.md#removetickprerequisiteactor)

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

[Controller](ue_ue.Controller.md).[RemoveTickPrerequisiteComponent](ue_ue.Controller.md#removetickprerequisitecomponent)

___

### ResetIgnoreInputFlags

▸ **ResetIgnoreInputFlags**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ResetIgnoreInputFlags](ue_ue.Controller.md#resetignoreinputflags)

___

### ResetIgnoreLookInput

▸ **ResetIgnoreLookInput**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ResetIgnoreLookInput](ue_ue.Controller.md#resetignorelookinput)

___

### ResetIgnoreMoveInput

▸ **ResetIgnoreMoveInput**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ResetIgnoreMoveInput](ue_ue.Controller.md#resetignoremoveinput)

___

### RunBehaviorTree

▸ **RunBehaviorTree**(`BTAsset`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BTAsset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BehaviorTree`](ue_ue.BehaviorTree.md)\> |

#### Returns

`boolean`

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

[Controller](ue_ue.Controller.md).[SetActorEnableCollision](ue_ue.Controller.md#setactorenablecollision)

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

[Controller](ue_ue.Controller.md).[SetActorHiddenInGame](ue_ue.Controller.md#setactorhiddeningame)

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

[Controller](ue_ue.Controller.md).[SetActorLabel](ue_ue.Controller.md#setactorlabel)

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

[Controller](ue_ue.Controller.md).[SetActorRelativeScale3D](ue_ue.Controller.md#setactorrelativescale3d)

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

[Controller](ue_ue.Controller.md).[SetActorScale3D](ue_ue.Controller.md#setactorscale3d)

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

[Controller](ue_ue.Controller.md).[SetActorTickEnabled](ue_ue.Controller.md#setactortickenabled)

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

[Controller](ue_ue.Controller.md).[SetActorTickInterval](ue_ue.Controller.md#setactortickinterval)

___

### SetControlRotation

▸ **SetControlRotation**(`NewRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[SetControlRotation](ue_ue.Controller.md#setcontrolrotation)

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

[Controller](ue_ue.Controller.md).[SetFolderPath](ue_ue.Controller.md#setfolderpath)

___

### SetIgnoreLookInput

▸ **SetIgnoreLookInput**(`bNewLookInput`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewLookInput` | `boolean` |

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[SetIgnoreLookInput](ue_ue.Controller.md#setignorelookinput)

___

### SetIgnoreMoveInput

▸ **SetIgnoreMoveInput**(`bNewMoveInput`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewMoveInput` | `boolean` |

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[SetIgnoreMoveInput](ue_ue.Controller.md#setignoremoveinput)

___

### SetInitialLocationAndRotation

▸ **SetInitialLocationAndRotation**(`NewLocation`, `NewRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[SetInitialLocationAndRotation](ue_ue.Controller.md#setinitiallocationandrotation)

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

[Controller](ue_ue.Controller.md).[SetIsTemporarilyHiddenInEditor](ue_ue.Controller.md#setistemporarilyhiddenineditor)

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

[Controller](ue_ue.Controller.md).[SetLifeSpan](ue_ue.Controller.md#setlifespan)

___

### SetMoveBlockDetection

▸ **SetMoveBlockDetection**(`bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

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

[Controller](ue_ue.Controller.md).[SetNetDormancy](ue_ue.Controller.md#setnetdormancy)

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

[Controller](ue_ue.Controller.md).[SetOwner](ue_ue.Controller.md#setowner)

___

### SetPathFollowingComponent

▸ **SetPathFollowingComponent**(`NewPFComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPFComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PathFollowingComponent`](ue_ue.PathFollowingComponent.md)\> |

#### Returns

`void`

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

[Controller](ue_ue.Controller.md).[SetReplicateMovement](ue_ue.Controller.md#setreplicatemovement)

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

[Controller](ue_ue.Controller.md).[SetReplicates](ue_ue.Controller.md#setreplicates)

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

[Controller](ue_ue.Controller.md).[SetTickGroup](ue_ue.Controller.md#settickgroup)

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

[Controller](ue_ue.Controller.md).[SetTickableWhenPaused](ue_ue.Controller.md#settickablewhenpaused)

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

[Controller](ue_ue.Controller.md).[SnapRootComponentTo](ue_ue.Controller.md#snaprootcomponentto)

___

### StopMovement

▸ **StopMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[StopMovement](ue_ue.Controller.md#stopmovement)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[TearOff](ue_ue.Controller.md#tearoff)

___

### UnPossess

▸ **UnPossess**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[UnPossess](ue_ue.Controller.md#unpossess)

___

### UnclaimTaskResource

▸ **UnclaimTaskResource**(`ResourceClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ResourceClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

___

### UseBlackboard

▸ **UseBlackboard**(`BlackboardAsset`, `BlackboardComponent`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BlackboardAsset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BlackboardData`](ue_ue.BlackboardData.md)\> |
| `BlackboardComponent` | [`$Ref`](../interfaces/puerts._Ref.md)<[`BlackboardComponent`](ue_ue.BlackboardComponent.md)\> |

#### Returns

`boolean`

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[UserConstructionScript](ue_ue.Controller.md#userconstructionscript)

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

[Controller](ue_ue.Controller.md).[WasRecentlyRendered](ue_ue.Controller.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AIController`](ue_ue.AIController.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AIController`](ue_ue.AIController.md)

#### Overrides

[Controller](ue_ue.Controller.md).[Find](ue_ue.Controller.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AIController`](ue_ue.AIController.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AIController`](ue_ue.AIController.md)

#### Overrides

[Controller](ue_ue.Controller.md).[Load](ue_ue.Controller.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Controller](ue_ue.Controller.md).[StaticClass](ue_ue.Controller.md#staticclass)
