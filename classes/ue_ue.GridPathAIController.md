[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GridPathAIController

# Class: GridPathAIController

[ue/ue](../modules/ue_ue.md).GridPathAIController

## Hierarchy

- [`AIController`](ue_ue.AIController.md)

  ↳ **`GridPathAIController`**

## Table of contents

### Constructors

- [constructor](ue_ue.GridPathAIController.md#constructor)

### Properties

- [ActionsComp](ue_ue.GridPathAIController.md#actionscomp)
- [ActorLabel](ue_ue.GridPathAIController.md#actorlabel)
- [AttachmentReplication](ue_ue.GridPathAIController.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.GridPathAIController.md#autoreceiveinput)
- [Blackboard](ue_ue.GridPathAIController.md#blackboard)
- [BlueprintCreatedComponents](ue_ue.GridPathAIController.md#blueprintcreatedcomponents)
- [BrainComponent](ue_ue.GridPathAIController.md#braincomponent)
- [CachedGameplayTasksComponent](ue_ue.GridPathAIController.md#cachedgameplaytaskscomponent)
- [Character](ue_ue.GridPathAIController.md#character)
- [Children](ue_ue.GridPathAIController.md#children)
- [ControlRotation](ue_ue.GridPathAIController.md#controlrotation)
- [ControllingMatineeActors](ue_ue.GridPathAIController.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.GridPathAIController.md#customtimedilation)
- [DefaultNavigationFilterClass](ue_ue.GridPathAIController.md#defaultnavigationfilterclass)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.GridPathAIController.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.GridPathAIController.md#folderpath)
- [GroupActor](ue_ue.GridPathAIController.md#groupactor)
- [HiddenEditorViews](ue_ue.GridPathAIController.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.GridPathAIController.md#initiallifespan)
- [InputComponent](ue_ue.GridPathAIController.md#inputcomponent)
- [InputPriority](ue_ue.GridPathAIController.md#inputpriority)
- [InstanceComponents](ue_ue.GridPathAIController.md#instancecomponents)
- [Instigator](ue_ue.GridPathAIController.md#instigator)
- [Layers](ue_ue.GridPathAIController.md#layers)
- [MinNetUpdateFrequency](ue_ue.GridPathAIController.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.GridPathAIController.md#netculldistancesquared)
- [NetDormancy](ue_ue.GridPathAIController.md#netdormancy)
- [NetDriverName](ue_ue.GridPathAIController.md#netdrivername)
- [NetPriority](ue_ue.GridPathAIController.md#netpriority)
- [NetTag](ue_ue.GridPathAIController.md#nettag)
- [NetUpdateFrequency](ue_ue.GridPathAIController.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.GridPathAIController.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.GridPathAIController.md#onactorendoverlap)
- [OnActorHit](ue_ue.GridPathAIController.md#onactorhit)
- [OnBeginCursorOver](ue_ue.GridPathAIController.md#onbegincursorover)
- [OnClicked](ue_ue.GridPathAIController.md#onclicked)
- [OnDestroyed](ue_ue.GridPathAIController.md#ondestroyed)
- [OnEndCursorOver](ue_ue.GridPathAIController.md#onendcursorover)
- [OnEndPlay](ue_ue.GridPathAIController.md#onendplay)
- [OnInputTouchBegin](ue_ue.GridPathAIController.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.GridPathAIController.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.GridPathAIController.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.GridPathAIController.md#oninputtouchleave)
- [OnInstigatedAnyDamage](ue_ue.GridPathAIController.md#oninstigatedanydamage)
- [OnReleased](ue_ue.GridPathAIController.md#onreleased)
- [OnTakeAnyDamage](ue_ue.GridPathAIController.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.GridPathAIController.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.GridPathAIController.md#ontakeradialdamage)
- [Owner](ue_ue.GridPathAIController.md#owner)
- [ParentComponent](ue_ue.GridPathAIController.md#parentcomponent)
- [ParentComponentActor](ue_ue.GridPathAIController.md#parentcomponentactor)
- [PathFollowingComponent](ue_ue.GridPathAIController.md#pathfollowingcomponent)
- [Pawn](ue_ue.GridPathAIController.md#pawn)
- [PerceptionComponent](ue_ue.GridPathAIController.md#perceptioncomponent)
- [PivotOffset](ue_ue.GridPathAIController.md#pivotoffset)
- [PlayerState](ue_ue.GridPathAIController.md#playerstate)
- [PrimaryActorTick](ue_ue.GridPathAIController.md#primaryactortick)
- [ReceiveMoveCompleted](ue_ue.GridPathAIController.md#receivemovecompleted)
- [RemoteRole](ue_ue.GridPathAIController.md#remoterole)
- [ReplicatedMovement](ue_ue.GridPathAIController.md#replicatedmovement)
- [Role](ue_ue.GridPathAIController.md#role)
- [RootComponent](ue_ue.GridPathAIController.md#rootcomponent)
- [SpawnCollisionHandlingMethod](ue_ue.GridPathAIController.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.GridPathAIController.md#spritescale)
- [StateName](ue_ue.GridPathAIController.md#statename)
- [Tags](ue_ue.GridPathAIController.md#tags)
- [TransformComponent](ue_ue.GridPathAIController.md#transformcomponent)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.GridPathAIController.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_AIController\_\_](ue_ue.GridPathAIController.md#__tid_aicontroller__)
- [\_\_tid\_Actor\_\_](ue_ue.GridPathAIController.md#__tid_actor__)
- [\_\_tid\_Controller\_\_](ue_ue.GridPathAIController.md#__tid_controller__)
- [\_\_tid\_GridPathAIController\_\_](ue_ue.GridPathAIController.md#__tid_gridpathaicontroller__)
- [\_\_tid\_Object\_\_](ue_ue.GridPathAIController.md#__tid_object__)
- [bActorEnableCollision](ue_ue.GridPathAIController.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.GridPathAIController.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.GridPathAIController.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.GridPathAIController.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.GridPathAIController.md#ballowreceivetickeventondedicatedserver)
- [bAllowStrafe](ue_ue.GridPathAIController.md#ballowstrafe)
- [bAllowTickBeforeBeginPlay](ue_ue.GridPathAIController.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.GridPathAIController.md#balwaysrelevant)
- [bAttachToPawn](ue_ue.GridPathAIController.md#battachtopawn)
- [bAutoDestroyWhenFinished](ue_ue.GridPathAIController.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.GridPathAIController.md#bblockinput)
- [bCanBeDamaged](ue_ue.GridPathAIController.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.GridPathAIController.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.GridPathAIController.md#bcollidewhenplacing)
- [bEditable](ue_ue.GridPathAIController.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.GridPathAIController.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.GridPathAIController.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.GridPathAIController.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.GridPathAIController.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.GridPathAIController.md#bhidden)
- [bHiddenEd](ue_ue.GridPathAIController.md#bhiddened)
- [bHiddenEdLayer](ue_ue.GridPathAIController.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.GridPathAIController.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.GridPathAIController.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.GridPathAIController.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.GridPathAIController.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.GridPathAIController.md#biseditorpreviewactor)
- [bLOSflag](ue_ue.GridPathAIController.md#blosflag)
- [bListedInSceneOutliner](ue_ue.GridPathAIController.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.GridPathAIController.md#blocklocation)
- [bNetLoadOnClient](ue_ue.GridPathAIController.md#bnetloadonclient)
- [bNetStartup](ue_ue.GridPathAIController.md#bnetstartup)
- [bNetTemporary](ue_ue.GridPathAIController.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.GridPathAIController.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.GridPathAIController.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.GridPathAIController.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.GridPathAIController.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.GridPathAIController.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.GridPathAIController.md#breplayrewindable)
- [bReplicateMovement](ue_ue.GridPathAIController.md#breplicatemovement)
- [bReplicates](ue_ue.GridPathAIController.md#breplicates)
- [bSetControlRotationFromPawnOrientation](ue_ue.GridPathAIController.md#bsetcontrolrotationfrompawnorientation)
- [bSkipExtraLOSChecks](ue_ue.GridPathAIController.md#bskipextraloschecks)
- [bStopAILogicOnUnposses](ue_ue.GridPathAIController.md#bstopailogiconunposses)
- [bTearOff](ue_ue.GridPathAIController.md#btearoff)
- [bWantsPlayerState](ue_ue.GridPathAIController.md#bwantsplayerstate)

### Methods

- [ActorHasTag](ue_ue.GridPathAIController.md#actorhastag)
- [AddComponent](ue_ue.GridPathAIController.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.GridPathAIController.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.GridPathAIController.md#addtickprerequisitecomponent)
- [CastToPlayerController](ue_ue.GridPathAIController.md#casttoplayercontroller)
- [ClaimTaskResource](ue_ue.GridPathAIController.md#claimtaskresource)
- [ClientSetLocation](ue_ue.GridPathAIController.md#clientsetlocation)
- [ClientSetRotation](ue_ue.GridPathAIController.md#clientsetrotation)
- [CreateDefaultSubobject](ue_ue.GridPathAIController.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.GridPathAIController.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.GridPathAIController.md#disableinput)
- [EnableInput](ue_ue.GridPathAIController.md#enableinput)
- [ExecuteUbergraph](ue_ue.GridPathAIController.md#executeubergraph)
- [FlushNetDormancy](ue_ue.GridPathAIController.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.GridPathAIController.md#forcenetupdate)
- [GetAIPerceptionComponent](ue_ue.GridPathAIController.md#getaiperceptioncomponent)
- [GetActorBounds](ue_ue.GridPathAIController.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.GridPathAIController.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.GridPathAIController.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.GridPathAIController.md#getactorforwardvector)
- [GetActorLabel](ue_ue.GridPathAIController.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.GridPathAIController.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.GridPathAIController.md#getactorrightvector)
- [GetActorScale3D](ue_ue.GridPathAIController.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.GridPathAIController.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.GridPathAIController.md#getactortimedilation)
- [GetActorUpVector](ue_ue.GridPathAIController.md#getactorupvector)
- [GetAllChildActors](ue_ue.GridPathAIController.md#getallchildactors)
- [GetAttachParentActor](ue_ue.GridPathAIController.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.GridPathAIController.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.GridPathAIController.md#getattachedactors)
- [GetClass](ue_ue.GridPathAIController.md#getclass)
- [GetComponentByClass](ue_ue.GridPathAIController.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.GridPathAIController.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.GridPathAIController.md#getcomponentsbytag)
- [GetControlRotation](ue_ue.GridPathAIController.md#getcontrolrotation)
- [GetDesiredRotation](ue_ue.GridPathAIController.md#getdesiredrotation)
- [GetDistanceTo](ue_ue.GridPathAIController.md#getdistanceto)
- [GetDotProductTo](ue_ue.GridPathAIController.md#getdotproductto)
- [GetFocalPoint](ue_ue.GridPathAIController.md#getfocalpoint)
- [GetFocalPointOnActor](ue_ue.GridPathAIController.md#getfocalpointonactor)
- [GetFocusActor](ue_ue.GridPathAIController.md#getfocusactor)
- [GetFolderPath](ue_ue.GridPathAIController.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.GridPathAIController.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.GridPathAIController.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.GridPathAIController.md#gethorizontaldotproductto)
- [GetImmediateMoveDestination](ue_ue.GridPathAIController.md#getimmediatemovedestination)
- [GetInputAxisKeyValue](ue_ue.GridPathAIController.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.GridPathAIController.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.GridPathAIController.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.GridPathAIController.md#getinstigator)
- [GetInstigatorController](ue_ue.GridPathAIController.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.GridPathAIController.md#getlifespan)
- [GetLocalRole](ue_ue.GridPathAIController.md#getlocalrole)
- [GetMoveStatus](ue_ue.GridPathAIController.md#getmovestatus)
- [GetName](ue_ue.GridPathAIController.md#getname)
- [GetOuter](ue_ue.GridPathAIController.md#getouter)
- [GetOverlappingActors](ue_ue.GridPathAIController.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.GridPathAIController.md#getoverlappingcomponents)
- [GetOwner](ue_ue.GridPathAIController.md#getowner)
- [GetParentActor](ue_ue.GridPathAIController.md#getparentactor)
- [GetParentComponent](ue_ue.GridPathAIController.md#getparentcomponent)
- [GetPathFollowingComponent](ue_ue.GridPathAIController.md#getpathfollowingcomponent)
- [GetRemoteRole](ue_ue.GridPathAIController.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.GridPathAIController.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.GridPathAIController.md#gettickablewhenpaused)
- [GetTransform](ue_ue.GridPathAIController.md#gettransform)
- [GetVelocity](ue_ue.GridPathAIController.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.GridPathAIController.md#getverticaldistanceto)
- [GetViewTarget](ue_ue.GridPathAIController.md#getviewtarget)
- [GetWorld](ue_ue.GridPathAIController.md#getworld)
- [HasAuthority](ue_ue.GridPathAIController.md#hasauthority)
- [HasPartialPath](ue_ue.GridPathAIController.md#haspartialpath)
- [IsActorBeingDestroyed](ue_ue.GridPathAIController.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.GridPathAIController.md#isactortickenabled)
- [IsChildActor](ue_ue.GridPathAIController.md#ischildactor)
- [IsEditable](ue_ue.GridPathAIController.md#iseditable)
- [IsHiddenEd](ue_ue.GridPathAIController.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.GridPathAIController.md#ishiddenedatstartup)
- [IsLocalController](ue_ue.GridPathAIController.md#islocalcontroller)
- [IsLocalPlayerController](ue_ue.GridPathAIController.md#islocalplayercontroller)
- [IsLookInputIgnored](ue_ue.GridPathAIController.md#islookinputignored)
- [IsMoveInputIgnored](ue_ue.GridPathAIController.md#ismoveinputignored)
- [IsOverlappingActor](ue_ue.GridPathAIController.md#isoverlappingactor)
- [IsPlayerController](ue_ue.GridPathAIController.md#isplayercontroller)
- [IsSelectable](ue_ue.GridPathAIController.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.GridPathAIController.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.GridPathAIController.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.GridPathAIController.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.GridPathAIController.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.GridPathAIController.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.GridPathAIController.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.GridPathAIController.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.GridPathAIController.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.GridPathAIController.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.GridPathAIController.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.GridPathAIController.md#k2_attachtocomponent)
- [K2\_ClearFocus](ue_ue.GridPathAIController.md#k2_clearfocus)
- [K2\_DestroyActor](ue_ue.GridPathAIController.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.GridPathAIController.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.GridPathAIController.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.GridPathAIController.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.GridPathAIController.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.GridPathAIController.md#k2_getcomponentsbyclass)
- [K2\_GetPawn](ue_ue.GridPathAIController.md#k2_getpawn)
- [K2\_GetRootComponent](ue_ue.GridPathAIController.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.GridPathAIController.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.GridPathAIController.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.GridPathAIController.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.GridPathAIController.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.GridPathAIController.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.GridPathAIController.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.GridPathAIController.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.GridPathAIController.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.GridPathAIController.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.GridPathAIController.md#k2_setactortransform)
- [K2\_SetFocalPoint](ue_ue.GridPathAIController.md#k2_setfocalpoint)
- [K2\_SetFocus](ue_ue.GridPathAIController.md#k2_setfocus)
- [K2\_TeleportTo](ue_ue.GridPathAIController.md#k2_teleportto)
- [LineOfSightTo](ue_ue.GridPathAIController.md#lineofsightto)
- [MakeMIDForMaterial](ue_ue.GridPathAIController.md#makemidformaterial)
- [MakeNoise](ue_ue.GridPathAIController.md#makenoise)
- [MoveToActor](ue_ue.GridPathAIController.md#movetoactor)
- [MoveToLocation](ue_ue.GridPathAIController.md#movetolocation)
- [OnGameplayTaskResourcesClaimed](ue_ue.GridPathAIController.md#ongameplaytaskresourcesclaimed)
- [OnRep\_AttachmentReplication](ue_ue.GridPathAIController.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.GridPathAIController.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.GridPathAIController.md#onrep_owner)
- [OnRep\_Pawn](ue_ue.GridPathAIController.md#onrep_pawn)
- [OnRep\_PlayerState](ue_ue.GridPathAIController.md#onrep_playerstate)
- [OnRep\_ReplicateMovement](ue_ue.GridPathAIController.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.GridPathAIController.md#onrep_replicatedmovement)
- [OnUsingBlackBoard](ue_ue.GridPathAIController.md#onusingblackboard)
- [Possess](ue_ue.GridPathAIController.md#possess)
- [PrestreamTextures](ue_ue.GridPathAIController.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.GridPathAIController.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.GridPathAIController.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.GridPathAIController.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.GridPathAIController.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.GridPathAIController.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.GridPathAIController.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.GridPathAIController.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.GridPathAIController.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.GridPathAIController.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.GridPathAIController.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.GridPathAIController.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.GridPathAIController.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.GridPathAIController.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.GridPathAIController.md#receiveendplay)
- [ReceiveHit](ue_ue.GridPathAIController.md#receivehit)
- [ReceiveInstigatedAnyDamage](ue_ue.GridPathAIController.md#receiveinstigatedanydamage)
- [ReceivePointDamage](ue_ue.GridPathAIController.md#receivepointdamage)
- [ReceivePossess](ue_ue.GridPathAIController.md#receivepossess)
- [ReceiveRadialDamage](ue_ue.GridPathAIController.md#receiveradialdamage)
- [ReceiveTick](ue_ue.GridPathAIController.md#receivetick)
- [ReceiveUnPossess](ue_ue.GridPathAIController.md#receiveunpossess)
- [RemoveTickPrerequisiteActor](ue_ue.GridPathAIController.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.GridPathAIController.md#removetickprerequisitecomponent)
- [ResetIgnoreInputFlags](ue_ue.GridPathAIController.md#resetignoreinputflags)
- [ResetIgnoreLookInput](ue_ue.GridPathAIController.md#resetignorelookinput)
- [ResetIgnoreMoveInput](ue_ue.GridPathAIController.md#resetignoremoveinput)
- [RunBehaviorTree](ue_ue.GridPathAIController.md#runbehaviortree)
- [SetActorEnableCollision](ue_ue.GridPathAIController.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.GridPathAIController.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.GridPathAIController.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.GridPathAIController.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.GridPathAIController.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.GridPathAIController.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.GridPathAIController.md#setactortickinterval)
- [SetControlRotation](ue_ue.GridPathAIController.md#setcontrolrotation)
- [SetFolderPath](ue_ue.GridPathAIController.md#setfolderpath)
- [SetIgnoreLookInput](ue_ue.GridPathAIController.md#setignorelookinput)
- [SetIgnoreMoveInput](ue_ue.GridPathAIController.md#setignoremoveinput)
- [SetInitialLocationAndRotation](ue_ue.GridPathAIController.md#setinitiallocationandrotation)
- [SetIsTemporarilyHiddenInEditor](ue_ue.GridPathAIController.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.GridPathAIController.md#setlifespan)
- [SetMoveBlockDetection](ue_ue.GridPathAIController.md#setmoveblockdetection)
- [SetNetDormancy](ue_ue.GridPathAIController.md#setnetdormancy)
- [SetOwner](ue_ue.GridPathAIController.md#setowner)
- [SetPathFollowingComponent](ue_ue.GridPathAIController.md#setpathfollowingcomponent)
- [SetReplicateMovement](ue_ue.GridPathAIController.md#setreplicatemovement)
- [SetReplicates](ue_ue.GridPathAIController.md#setreplicates)
- [SetTickGroup](ue_ue.GridPathAIController.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.GridPathAIController.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.GridPathAIController.md#snaprootcomponentto)
- [StopMovement](ue_ue.GridPathAIController.md#stopmovement)
- [TearOff](ue_ue.GridPathAIController.md#tearoff)
- [UnPossess](ue_ue.GridPathAIController.md#unpossess)
- [UnclaimTaskResource](ue_ue.GridPathAIController.md#unclaimtaskresource)
- [UseBlackboard](ue_ue.GridPathAIController.md#useblackboard)
- [UserConstructionScript](ue_ue.GridPathAIController.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.GridPathAIController.md#wasrecentlyrendered)
- [Find](ue_ue.GridPathAIController.md#find)
- [Load](ue_ue.GridPathAIController.md#load)
- [StaticClass](ue_ue.GridPathAIController.md#staticclass)

## Constructors

### constructor

• **new GridPathAIController**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AIController](ue_ue.AIController.md).[constructor](ue_ue.AIController.md#constructor)

## Properties

### ActionsComp

• **ActionsComp**: [`PawnActionsComponent`](ue_ue.PawnActionsComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[ActionsComp](ue_ue.AIController.md#actionscomp)

___

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[AIController](ue_ue.AIController.md).[ActorLabel](ue_ue.AIController.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[AttachmentReplication](ue_ue.AIController.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[AutoReceiveInput](ue_ue.AIController.md#autoreceiveinput)

___

### Blackboard

• **Blackboard**: [`BlackboardComponent`](ue_ue.BlackboardComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[Blackboard](ue_ue.AIController.md#blackboard)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[AIController](ue_ue.AIController.md).[BlueprintCreatedComponents](ue_ue.AIController.md#blueprintcreatedcomponents)

___

### BrainComponent

• **BrainComponent**: [`BrainComponent`](ue_ue.BrainComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[BrainComponent](ue_ue.AIController.md#braincomponent)

___

### CachedGameplayTasksComponent

• **CachedGameplayTasksComponent**: [`GameplayTasksComponent`](ue_ue.GameplayTasksComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[CachedGameplayTasksComponent](ue_ue.AIController.md#cachedgameplaytaskscomponent)

___

### Character

• **Character**: [`Character`](ue_ue.Character.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[Character](ue_ue.AIController.md#character)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[AIController](ue_ue.AIController.md).[Children](ue_ue.AIController.md#children)

___

### ControlRotation

• **ControlRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[ControlRotation](ue_ue.AIController.md#controlrotation)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[AIController](ue_ue.AIController.md).[ControllingMatineeActors](ue_ue.AIController.md#controllingmatineeactors)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[CustomTimeDilation](ue_ue.AIController.md#customtimedilation)

___

### DefaultNavigationFilterClass

• **DefaultNavigationFilterClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[DefaultNavigationFilterClass](ue_ue.AIController.md#defaultnavigationfilterclass)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.AIController.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[AIController](ue_ue.AIController.md).[FolderPath](ue_ue.AIController.md#folderpath)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GroupActor](ue_ue.AIController.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[AIController](ue_ue.AIController.md).[HiddenEditorViews](ue_ue.AIController.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[InitialLifeSpan](ue_ue.AIController.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[InputComponent](ue_ue.AIController.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[InputPriority](ue_ue.AIController.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[AIController](ue_ue.AIController.md).[InstanceComponents](ue_ue.AIController.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[Instigator](ue_ue.AIController.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[Layers](ue_ue.AIController.md#layers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[MinNetUpdateFrequency](ue_ue.AIController.md#minnetupdatefrequency)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[NetCullDistanceSquared](ue_ue.AIController.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[NetDormancy](ue_ue.AIController.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[AIController](ue_ue.AIController.md).[NetDriverName](ue_ue.AIController.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[NetPriority](ue_ue.AIController.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[NetTag](ue_ue.AIController.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[NetUpdateFrequency](ue_ue.AIController.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnActorBeginOverlap](ue_ue.AIController.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnActorEndOverlap](ue_ue.AIController.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnActorHit](ue_ue.AIController.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnBeginCursorOver](ue_ue.AIController.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnClicked](ue_ue.AIController.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnDestroyed](ue_ue.AIController.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnEndCursorOver](ue_ue.AIController.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnEndPlay](ue_ue.AIController.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnInputTouchBegin](ue_ue.AIController.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnInputTouchEnd](ue_ue.AIController.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnInputTouchEnter](ue_ue.AIController.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnInputTouchLeave](ue_ue.AIController.md#oninputtouchleave)

___

### OnInstigatedAnyDamage

• **OnInstigatedAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnInstigatedAnyDamage](ue_ue.AIController.md#oninstigatedanydamage)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnReleased](ue_ue.AIController.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnTakeAnyDamage](ue_ue.AIController.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnTakePointDamage](ue_ue.AIController.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnTakeRadialDamage](ue_ue.AIController.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[Owner](ue_ue.AIController.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[AIController](ue_ue.AIController.md).[ParentComponent](ue_ue.AIController.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[AIController](ue_ue.AIController.md).[ParentComponentActor](ue_ue.AIController.md#parentcomponentactor)

___

### PathFollowingComponent

• **PathFollowingComponent**: [`PathFollowingComponent`](ue_ue.PathFollowingComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[PathFollowingComponent](ue_ue.AIController.md#pathfollowingcomponent)

___

### Pawn

• **Pawn**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[Pawn](ue_ue.AIController.md#pawn)

___

### PerceptionComponent

• **PerceptionComponent**: [`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[PerceptionComponent](ue_ue.AIController.md#perceptioncomponent)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[PivotOffset](ue_ue.AIController.md#pivotoffset)

___

### PlayerState

• **PlayerState**: [`PlayerState`](ue_ue.PlayerState.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[PlayerState](ue_ue.AIController.md#playerstate)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[PrimaryActorTick](ue_ue.AIController.md#primaryactortick)

___

### ReceiveMoveCompleted

• **ReceiveMoveCompleted**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`RequestID`: [`AIRequestID`](ue_ue.AIRequestID.md), `Result`: [`EPathFollowingResult`](../enums/ue_ue.EPathFollowingResult.md)) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[ReceiveMoveCompleted](ue_ue.AIController.md#receivemovecompleted)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[RemoteRole](ue_ue.AIController.md#remoterole)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[ReplicatedMovement](ue_ue.AIController.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[Role](ue_ue.AIController.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[RootComponent](ue_ue.AIController.md#rootcomponent)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[SpawnCollisionHandlingMethod](ue_ue.AIController.md#spawncollisionhandlingmethod)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[SpriteScale](ue_ue.AIController.md#spritescale)

___

### StateName

• **StateName**: `string`

#### Inherited from

[AIController](ue_ue.AIController.md).[StateName](ue_ue.AIController.md#statename)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[Tags](ue_ue.AIController.md#tags)

___

### TransformComponent

• **TransformComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[TransformComponent](ue_ue.AIController.md#transformcomponent)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.AIController.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_AIController\_\_

• **\_\_tid\_AIController\_\_**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[__tid_AIController__](ue_ue.AIController.md#__tid_aicontroller__)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[__tid_Actor__](ue_ue.AIController.md#__tid_actor__)

___

### \_\_tid\_Controller\_\_

• **\_\_tid\_Controller\_\_**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[__tid_Controller__](ue_ue.AIController.md#__tid_controller__)

___

### \_\_tid\_GridPathAIController\_\_

• **\_\_tid\_GridPathAIController\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[__tid_Object__](ue_ue.AIController.md#__tid_object__)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bActorEnableCollision](ue_ue.AIController.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bActorIsBeingDestroyed](ue_ue.AIController.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bActorLabelEditable](ue_ue.AIController.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bActorSeamlessTraveled](ue_ue.AIController.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.AIController.md#ballowreceivetickeventondedicatedserver)

___

### bAllowStrafe

• **bAllowStrafe**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bAllowStrafe](ue_ue.AIController.md#ballowstrafe)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bAllowTickBeforeBeginPlay](ue_ue.AIController.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bAlwaysRelevant](ue_ue.AIController.md#balwaysrelevant)

___

### bAttachToPawn

• **bAttachToPawn**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bAttachToPawn](ue_ue.AIController.md#battachtopawn)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bAutoDestroyWhenFinished](ue_ue.AIController.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bBlockInput](ue_ue.AIController.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bCanBeDamaged](ue_ue.AIController.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bCanBeInCluster](ue_ue.AIController.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bCollideWhenPlacing](ue_ue.AIController.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bEditable](ue_ue.AIController.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bEnableAutoLODGeneration](ue_ue.AIController.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bExchangedRoles](ue_ue.AIController.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bFindCameraComponentWhenViewTarget](ue_ue.AIController.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.AIController.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bHidden](ue_ue.AIController.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bHiddenEd](ue_ue.AIController.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bHiddenEdLayer](ue_ue.AIController.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bHiddenEdLevel](ue_ue.AIController.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bHiddenEdTemporary](ue_ue.AIController.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bIgnoresOriginShifting](ue_ue.AIController.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bIsEditorOnlyActor](ue_ue.AIController.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bIsEditorPreviewActor](ue_ue.AIController.md#biseditorpreviewactor)

___

### bLOSflag

• **bLOSflag**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bLOSflag](ue_ue.AIController.md#blosflag)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bListedInSceneOutliner](ue_ue.AIController.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bLockLocation](ue_ue.AIController.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bNetLoadOnClient](ue_ue.AIController.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bNetStartup](ue_ue.AIController.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bNetTemporary](ue_ue.AIController.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bNetUseOwnerRelevancy](ue_ue.AIController.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bOnlyRelevantToOwner](ue_ue.AIController.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bOptimizeBPComponentData](ue_ue.AIController.md#boptimizebpcomponentdata)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bRelevantForLevelBounds](ue_ue.AIController.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bRelevantForNetworkReplays](ue_ue.AIController.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bReplayRewindable](ue_ue.AIController.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bReplicateMovement](ue_ue.AIController.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bReplicates](ue_ue.AIController.md#breplicates)

___

### bSetControlRotationFromPawnOrientation

• **bSetControlRotationFromPawnOrientation**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bSetControlRotationFromPawnOrientation](ue_ue.AIController.md#bsetcontrolrotationfrompawnorientation)

___

### bSkipExtraLOSChecks

• **bSkipExtraLOSChecks**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bSkipExtraLOSChecks](ue_ue.AIController.md#bskipextraloschecks)

___

### bStopAILogicOnUnposses

• **bStopAILogicOnUnposses**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bStopAILogicOnUnposses](ue_ue.AIController.md#bstopailogiconunposses)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bTearOff](ue_ue.AIController.md#btearoff)

___

### bWantsPlayerState

• **bWantsPlayerState**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bWantsPlayerState](ue_ue.AIController.md#bwantsplayerstate)

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

[AIController](ue_ue.AIController.md).[ActorHasTag](ue_ue.AIController.md#actorhastag)

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

[AIController](ue_ue.AIController.md).[AddComponent](ue_ue.AIController.md#addcomponent)

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

[AIController](ue_ue.AIController.md).[AddTickPrerequisiteActor](ue_ue.AIController.md#addtickprerequisiteactor)

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

[AIController](ue_ue.AIController.md).[AddTickPrerequisiteComponent](ue_ue.AIController.md#addtickprerequisitecomponent)

___

### CastToPlayerController

▸ **CastToPlayerController**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[CastToPlayerController](ue_ue.AIController.md#casttoplayercontroller)

___

### ClaimTaskResource

▸ **ClaimTaskResource**(`ResourceClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ResourceClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[ClaimTaskResource](ue_ue.AIController.md#claimtaskresource)

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

[AIController](ue_ue.AIController.md).[ClientSetLocation](ue_ue.AIController.md#clientsetlocation)

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

[AIController](ue_ue.AIController.md).[ClientSetRotation](ue_ue.AIController.md#clientsetrotation)

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

[AIController](ue_ue.AIController.md).[CreateDefaultSubobject](ue_ue.AIController.md#createdefaultsubobject)

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

[AIController](ue_ue.AIController.md).[DetachRootComponentFromParent](ue_ue.AIController.md#detachrootcomponentfromparent)

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

[AIController](ue_ue.AIController.md).[DisableInput](ue_ue.AIController.md#disableinput)

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

[AIController](ue_ue.AIController.md).[EnableInput](ue_ue.AIController.md#enableinput)

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

[AIController](ue_ue.AIController.md).[ExecuteUbergraph](ue_ue.AIController.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[FlushNetDormancy](ue_ue.AIController.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[ForceNetUpdate](ue_ue.AIController.md#forcenetupdate)

___

### GetAIPerceptionComponent

▸ **GetAIPerceptionComponent**(): [`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)

#### Returns

[`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetAIPerceptionComponent](ue_ue.AIController.md#getaiperceptioncomponent)

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

[AIController](ue_ue.AIController.md).[GetActorBounds](ue_ue.AIController.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorEnableCollision](ue_ue.AIController.md#getactorenablecollision)

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

[AIController](ue_ue.AIController.md).[GetActorEyesViewPoint](ue_ue.AIController.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorForwardVector](ue_ue.AIController.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorLabel](ue_ue.AIController.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorRelativeScale3D](ue_ue.AIController.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorRightVector](ue_ue.AIController.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorScale3D](ue_ue.AIController.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorTickInterval](ue_ue.AIController.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorTimeDilation](ue_ue.AIController.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorUpVector](ue_ue.AIController.md#getactorupvector)

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

[AIController](ue_ue.AIController.md).[GetAllChildActors](ue_ue.AIController.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetAttachParentActor](ue_ue.AIController.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetAttachParentSocketName](ue_ue.AIController.md#getattachparentsocketname)

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

[AIController](ue_ue.AIController.md).[GetAttachedActors](ue_ue.AIController.md#getattachedactors)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetClass](ue_ue.AIController.md#getclass)

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

[AIController](ue_ue.AIController.md).[GetComponentByClass](ue_ue.AIController.md#getcomponentbyclass)

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

[AIController](ue_ue.AIController.md).[GetComponentsByInterface](ue_ue.AIController.md#getcomponentsbyinterface)

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

[AIController](ue_ue.AIController.md).[GetComponentsByTag](ue_ue.AIController.md#getcomponentsbytag)

___

### GetControlRotation

▸ **GetControlRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetControlRotation](ue_ue.AIController.md#getcontrolrotation)

___

### GetDesiredRotation

▸ **GetDesiredRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetDesiredRotation](ue_ue.AIController.md#getdesiredrotation)

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

[AIController](ue_ue.AIController.md).[GetDistanceTo](ue_ue.AIController.md#getdistanceto)

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

[AIController](ue_ue.AIController.md).[GetDotProductTo](ue_ue.AIController.md#getdotproductto)

___

### GetFocalPoint

▸ **GetFocalPoint**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetFocalPoint](ue_ue.AIController.md#getfocalpoint)

___

### GetFocalPointOnActor

▸ **GetFocalPointOnActor**(`Actor`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetFocalPointOnActor](ue_ue.AIController.md#getfocalpointonactor)

___

### GetFocusActor

▸ **GetFocusActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetFocusActor](ue_ue.AIController.md#getfocusactor)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetFolderPath](ue_ue.AIController.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetGameTimeSinceCreation](ue_ue.AIController.md#getgametimesincecreation)

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

[AIController](ue_ue.AIController.md).[GetHorizontalDistanceTo](ue_ue.AIController.md#gethorizontaldistanceto)

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

[AIController](ue_ue.AIController.md).[GetHorizontalDotProductTo](ue_ue.AIController.md#gethorizontaldotproductto)

___

### GetImmediateMoveDestination

▸ **GetImmediateMoveDestination**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetImmediateMoveDestination](ue_ue.AIController.md#getimmediatemovedestination)

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

[AIController](ue_ue.AIController.md).[GetInputAxisKeyValue](ue_ue.AIController.md#getinputaxiskeyvalue)

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

[AIController](ue_ue.AIController.md).[GetInputAxisValue](ue_ue.AIController.md#getinputaxisvalue)

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

[AIController](ue_ue.AIController.md).[GetInputVectorAxisValue](ue_ue.AIController.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetInstigator](ue_ue.AIController.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetInstigatorController](ue_ue.AIController.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetLifeSpan](ue_ue.AIController.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetLocalRole](ue_ue.AIController.md#getlocalrole)

___

### GetMoveStatus

▸ **GetMoveStatus**(): [`EPathFollowingStatus`](../enums/ue_ue.EPathFollowingStatus.md)

#### Returns

[`EPathFollowingStatus`](../enums/ue_ue.EPathFollowingStatus.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetMoveStatus](ue_ue.AIController.md#getmovestatus)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetName](ue_ue.AIController.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetOuter](ue_ue.AIController.md#getouter)

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

[AIController](ue_ue.AIController.md).[GetOverlappingActors](ue_ue.AIController.md#getoverlappingactors)

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

[AIController](ue_ue.AIController.md).[GetOverlappingComponents](ue_ue.AIController.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetOwner](ue_ue.AIController.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetParentActor](ue_ue.AIController.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetParentComponent](ue_ue.AIController.md#getparentcomponent)

___

### GetPathFollowingComponent

▸ **GetPathFollowingComponent**(): [`PathFollowingComponent`](ue_ue.PathFollowingComponent.md)

#### Returns

[`PathFollowingComponent`](ue_ue.PathFollowingComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetPathFollowingComponent](ue_ue.AIController.md#getpathfollowingcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetRemoteRole](ue_ue.AIController.md#getremoterole)

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

[AIController](ue_ue.AIController.md).[GetSquaredDistanceTo](ue_ue.AIController.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetTickableWhenPaused](ue_ue.AIController.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetTransform](ue_ue.AIController.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetVelocity](ue_ue.AIController.md#getvelocity)

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

[AIController](ue_ue.AIController.md).[GetVerticalDistanceTo](ue_ue.AIController.md#getverticaldistanceto)

___

### GetViewTarget

▸ **GetViewTarget**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetViewTarget](ue_ue.AIController.md#getviewtarget)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetWorld](ue_ue.AIController.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[HasAuthority](ue_ue.AIController.md#hasauthority)

___

### HasPartialPath

▸ **HasPartialPath**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[HasPartialPath](ue_ue.AIController.md#haspartialpath)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsActorBeingDestroyed](ue_ue.AIController.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsActorTickEnabled](ue_ue.AIController.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsChildActor](ue_ue.AIController.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsEditable](ue_ue.AIController.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsHiddenEd](ue_ue.AIController.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsHiddenEdAtStartup](ue_ue.AIController.md#ishiddenedatstartup)

___

### IsLocalController

▸ **IsLocalController**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsLocalController](ue_ue.AIController.md#islocalcontroller)

___

### IsLocalPlayerController

▸ **IsLocalPlayerController**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsLocalPlayerController](ue_ue.AIController.md#islocalplayercontroller)

___

### IsLookInputIgnored

▸ **IsLookInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsLookInputIgnored](ue_ue.AIController.md#islookinputignored)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsMoveInputIgnored](ue_ue.AIController.md#ismoveinputignored)

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

[AIController](ue_ue.AIController.md).[IsOverlappingActor](ue_ue.AIController.md#isoverlappingactor)

___

### IsPlayerController

▸ **IsPlayerController**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsPlayerController](ue_ue.AIController.md#isplayercontroller)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsSelectable](ue_ue.AIController.md#isselectable)

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

[AIController](ue_ue.AIController.md).[IsTemporarilyHiddenInEditor](ue_ue.AIController.md#istemporarilyhiddenineditor)

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

[AIController](ue_ue.AIController.md).[K2_AddActorLocalOffset](ue_ue.AIController.md#k2_addactorlocaloffset)

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

[AIController](ue_ue.AIController.md).[K2_AddActorLocalRotation](ue_ue.AIController.md#k2_addactorlocalrotation)

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

[AIController](ue_ue.AIController.md).[K2_AddActorLocalTransform](ue_ue.AIController.md#k2_addactorlocaltransform)

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

[AIController](ue_ue.AIController.md).[K2_AddActorWorldOffset](ue_ue.AIController.md#k2_addactorworldoffset)

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

[AIController](ue_ue.AIController.md).[K2_AddActorWorldRotation](ue_ue.AIController.md#k2_addactorworldrotation)

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

[AIController](ue_ue.AIController.md).[K2_AddActorWorldTransform](ue_ue.AIController.md#k2_addactorworldtransform)

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

[AIController](ue_ue.AIController.md).[K2_AttachRootComponentTo](ue_ue.AIController.md#k2_attachrootcomponentto)

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

[AIController](ue_ue.AIController.md).[K2_AttachRootComponentToActor](ue_ue.AIController.md#k2_attachrootcomponenttoactor)

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

[AIController](ue_ue.AIController.md).[K2_AttachToActor](ue_ue.AIController.md#k2_attachtoactor)

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

[AIController](ue_ue.AIController.md).[K2_AttachToComponent](ue_ue.AIController.md#k2_attachtocomponent)

___

### K2\_ClearFocus

▸ **K2_ClearFocus**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[K2_ClearFocus](ue_ue.AIController.md#k2_clearfocus)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[K2_DestroyActor](ue_ue.AIController.md#k2_destroyactor)

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

[AIController](ue_ue.AIController.md).[K2_DestroyComponent](ue_ue.AIController.md#k2_destroycomponent)

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

[AIController](ue_ue.AIController.md).[K2_DetachFromActor](ue_ue.AIController.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[K2_GetActorLocation](ue_ue.AIController.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[K2_GetActorRotation](ue_ue.AIController.md#k2_getactorrotation)

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

[AIController](ue_ue.AIController.md).[K2_GetComponentsByClass](ue_ue.AIController.md#k2_getcomponentsbyclass)

___

### K2\_GetPawn

▸ **K2_GetPawn**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[K2_GetPawn](ue_ue.AIController.md#k2_getpawn)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[K2_GetRootComponent](ue_ue.AIController.md#k2_getrootcomponent)

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

[AIController](ue_ue.AIController.md).[K2_OnBecomeViewTarget](ue_ue.AIController.md#k2_onbecomeviewtarget)

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

[AIController](ue_ue.AIController.md).[K2_OnEndViewTarget](ue_ue.AIController.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[K2_OnReset](ue_ue.AIController.md#k2_onreset)

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

[AIController](ue_ue.AIController.md).[K2_SetActorLocation](ue_ue.AIController.md#k2_setactorlocation)

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

[AIController](ue_ue.AIController.md).[K2_SetActorLocationAndRotation](ue_ue.AIController.md#k2_setactorlocationandrotation)

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

[AIController](ue_ue.AIController.md).[K2_SetActorRelativeLocation](ue_ue.AIController.md#k2_setactorrelativelocation)

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

[AIController](ue_ue.AIController.md).[K2_SetActorRelativeRotation](ue_ue.AIController.md#k2_setactorrelativerotation)

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

[AIController](ue_ue.AIController.md).[K2_SetActorRelativeTransform](ue_ue.AIController.md#k2_setactorrelativetransform)

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

[AIController](ue_ue.AIController.md).[K2_SetActorRotation](ue_ue.AIController.md#k2_setactorrotation)

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

[AIController](ue_ue.AIController.md).[K2_SetActorTransform](ue_ue.AIController.md#k2_setactortransform)

___

### K2\_SetFocalPoint

▸ **K2_SetFocalPoint**(`FP`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FP` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[K2_SetFocalPoint](ue_ue.AIController.md#k2_setfocalpoint)

___

### K2\_SetFocus

▸ **K2_SetFocus**(`NewFocus`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewFocus` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[K2_SetFocus](ue_ue.AIController.md#k2_setfocus)

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

[AIController](ue_ue.AIController.md).[K2_TeleportTo](ue_ue.AIController.md#k2_teleportto)

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

[AIController](ue_ue.AIController.md).[LineOfSightTo](ue_ue.AIController.md#lineofsightto)

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

[AIController](ue_ue.AIController.md).[MakeMIDForMaterial](ue_ue.AIController.md#makemidformaterial)

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

[AIController](ue_ue.AIController.md).[MakeNoise](ue_ue.AIController.md#makenoise)

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

#### Inherited from

[AIController](ue_ue.AIController.md).[MoveToActor](ue_ue.AIController.md#movetoactor)

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

#### Inherited from

[AIController](ue_ue.AIController.md).[MoveToLocation](ue_ue.AIController.md#movetolocation)

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

#### Inherited from

[AIController](ue_ue.AIController.md).[OnGameplayTaskResourcesClaimed](ue_ue.AIController.md#ongameplaytaskresourcesclaimed)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[OnRep_AttachmentReplication](ue_ue.AIController.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[OnRep_Instigator](ue_ue.AIController.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[OnRep_Owner](ue_ue.AIController.md#onrep_owner)

___

### OnRep\_Pawn

▸ **OnRep_Pawn**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[OnRep_Pawn](ue_ue.AIController.md#onrep_pawn)

___

### OnRep\_PlayerState

▸ **OnRep_PlayerState**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[OnRep_PlayerState](ue_ue.AIController.md#onrep_playerstate)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[OnRep_ReplicateMovement](ue_ue.AIController.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[OnRep_ReplicatedMovement](ue_ue.AIController.md#onrep_replicatedmovement)

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

#### Inherited from

[AIController](ue_ue.AIController.md).[OnUsingBlackBoard](ue_ue.AIController.md#onusingblackboard)

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

[AIController](ue_ue.AIController.md).[Possess](ue_ue.AIController.md#possess)

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

[AIController](ue_ue.AIController.md).[PrestreamTextures](ue_ue.AIController.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[ReceiveActorBeginCursorOver](ue_ue.AIController.md#receiveactorbegincursorover)

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

[AIController](ue_ue.AIController.md).[ReceiveActorBeginOverlap](ue_ue.AIController.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[ReceiveActorEndCursorOver](ue_ue.AIController.md#receiveactorendcursorover)

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

[AIController](ue_ue.AIController.md).[ReceiveActorEndOverlap](ue_ue.AIController.md#receiveactorendoverlap)

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

[AIController](ue_ue.AIController.md).[ReceiveActorOnClicked](ue_ue.AIController.md#receiveactoronclicked)

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

[AIController](ue_ue.AIController.md).[ReceiveActorOnInputTouchBegin](ue_ue.AIController.md#receiveactoroninputtouchbegin)

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

[AIController](ue_ue.AIController.md).[ReceiveActorOnInputTouchEnd](ue_ue.AIController.md#receiveactoroninputtouchend)

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

[AIController](ue_ue.AIController.md).[ReceiveActorOnInputTouchEnter](ue_ue.AIController.md#receiveactoroninputtouchenter)

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

[AIController](ue_ue.AIController.md).[ReceiveActorOnInputTouchLeave](ue_ue.AIController.md#receiveactoroninputtouchleave)

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

[AIController](ue_ue.AIController.md).[ReceiveActorOnReleased](ue_ue.AIController.md#receiveactoronreleased)

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

[AIController](ue_ue.AIController.md).[ReceiveAnyDamage](ue_ue.AIController.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[ReceiveBeginPlay](ue_ue.AIController.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[ReceiveDestroyed](ue_ue.AIController.md#receivedestroyed)

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

[AIController](ue_ue.AIController.md).[ReceiveEndPlay](ue_ue.AIController.md#receiveendplay)

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

[AIController](ue_ue.AIController.md).[ReceiveHit](ue_ue.AIController.md#receivehit)

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

[AIController](ue_ue.AIController.md).[ReceiveInstigatedAnyDamage](ue_ue.AIController.md#receiveinstigatedanydamage)

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

[AIController](ue_ue.AIController.md).[ReceivePointDamage](ue_ue.AIController.md#receivepointdamage)

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

[AIController](ue_ue.AIController.md).[ReceivePossess](ue_ue.AIController.md#receivepossess)

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

[AIController](ue_ue.AIController.md).[ReceiveRadialDamage](ue_ue.AIController.md#receiveradialdamage)

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

[AIController](ue_ue.AIController.md).[ReceiveTick](ue_ue.AIController.md#receivetick)

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

[AIController](ue_ue.AIController.md).[ReceiveUnPossess](ue_ue.AIController.md#receiveunpossess)

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

[AIController](ue_ue.AIController.md).[RemoveTickPrerequisiteActor](ue_ue.AIController.md#removetickprerequisiteactor)

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

[AIController](ue_ue.AIController.md).[RemoveTickPrerequisiteComponent](ue_ue.AIController.md#removetickprerequisitecomponent)

___

### ResetIgnoreInputFlags

▸ **ResetIgnoreInputFlags**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[ResetIgnoreInputFlags](ue_ue.AIController.md#resetignoreinputflags)

___

### ResetIgnoreLookInput

▸ **ResetIgnoreLookInput**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[ResetIgnoreLookInput](ue_ue.AIController.md#resetignorelookinput)

___

### ResetIgnoreMoveInput

▸ **ResetIgnoreMoveInput**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[ResetIgnoreMoveInput](ue_ue.AIController.md#resetignoremoveinput)

___

### RunBehaviorTree

▸ **RunBehaviorTree**(`BTAsset`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BTAsset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BehaviorTree`](ue_ue.BehaviorTree.md)\> |

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[RunBehaviorTree](ue_ue.AIController.md#runbehaviortree)

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

[AIController](ue_ue.AIController.md).[SetActorEnableCollision](ue_ue.AIController.md#setactorenablecollision)

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

[AIController](ue_ue.AIController.md).[SetActorHiddenInGame](ue_ue.AIController.md#setactorhiddeningame)

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

[AIController](ue_ue.AIController.md).[SetActorLabel](ue_ue.AIController.md#setactorlabel)

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

[AIController](ue_ue.AIController.md).[SetActorRelativeScale3D](ue_ue.AIController.md#setactorrelativescale3d)

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

[AIController](ue_ue.AIController.md).[SetActorScale3D](ue_ue.AIController.md#setactorscale3d)

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

[AIController](ue_ue.AIController.md).[SetActorTickEnabled](ue_ue.AIController.md#setactortickenabled)

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

[AIController](ue_ue.AIController.md).[SetActorTickInterval](ue_ue.AIController.md#setactortickinterval)

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

[AIController](ue_ue.AIController.md).[SetControlRotation](ue_ue.AIController.md#setcontrolrotation)

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

[AIController](ue_ue.AIController.md).[SetFolderPath](ue_ue.AIController.md#setfolderpath)

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

[AIController](ue_ue.AIController.md).[SetIgnoreLookInput](ue_ue.AIController.md#setignorelookinput)

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

[AIController](ue_ue.AIController.md).[SetIgnoreMoveInput](ue_ue.AIController.md#setignoremoveinput)

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

[AIController](ue_ue.AIController.md).[SetInitialLocationAndRotation](ue_ue.AIController.md#setinitiallocationandrotation)

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

[AIController](ue_ue.AIController.md).[SetIsTemporarilyHiddenInEditor](ue_ue.AIController.md#setistemporarilyhiddenineditor)

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

[AIController](ue_ue.AIController.md).[SetLifeSpan](ue_ue.AIController.md#setlifespan)

___

### SetMoveBlockDetection

▸ **SetMoveBlockDetection**(`bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[SetMoveBlockDetection](ue_ue.AIController.md#setmoveblockdetection)

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

[AIController](ue_ue.AIController.md).[SetNetDormancy](ue_ue.AIController.md#setnetdormancy)

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

[AIController](ue_ue.AIController.md).[SetOwner](ue_ue.AIController.md#setowner)

___

### SetPathFollowingComponent

▸ **SetPathFollowingComponent**(`NewPFComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPFComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PathFollowingComponent`](ue_ue.PathFollowingComponent.md)\> |

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[SetPathFollowingComponent](ue_ue.AIController.md#setpathfollowingcomponent)

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

[AIController](ue_ue.AIController.md).[SetReplicateMovement](ue_ue.AIController.md#setreplicatemovement)

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

[AIController](ue_ue.AIController.md).[SetReplicates](ue_ue.AIController.md#setreplicates)

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

[AIController](ue_ue.AIController.md).[SetTickGroup](ue_ue.AIController.md#settickgroup)

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

[AIController](ue_ue.AIController.md).[SetTickableWhenPaused](ue_ue.AIController.md#settickablewhenpaused)

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

[AIController](ue_ue.AIController.md).[SnapRootComponentTo](ue_ue.AIController.md#snaprootcomponentto)

___

### StopMovement

▸ **StopMovement**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[StopMovement](ue_ue.AIController.md#stopmovement)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[TearOff](ue_ue.AIController.md#tearoff)

___

### UnPossess

▸ **UnPossess**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[UnPossess](ue_ue.AIController.md#unpossess)

___

### UnclaimTaskResource

▸ **UnclaimTaskResource**(`ResourceClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ResourceClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[UnclaimTaskResource](ue_ue.AIController.md#unclaimtaskresource)

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

#### Inherited from

[AIController](ue_ue.AIController.md).[UseBlackboard](ue_ue.AIController.md#useblackboard)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[UserConstructionScript](ue_ue.AIController.md#userconstructionscript)

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

[AIController](ue_ue.AIController.md).[WasRecentlyRendered](ue_ue.AIController.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GridPathAIController`](ue_ue.GridPathAIController.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GridPathAIController`](ue_ue.GridPathAIController.md)

#### Overrides

[AIController](ue_ue.AIController.md).[Find](ue_ue.AIController.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GridPathAIController`](ue_ue.GridPathAIController.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GridPathAIController`](ue_ue.GridPathAIController.md)

#### Overrides

[AIController](ue_ue.AIController.md).[Load](ue_ue.AIController.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AIController](ue_ue.AIController.md).[StaticClass](ue_ue.AIController.md#staticclass)
