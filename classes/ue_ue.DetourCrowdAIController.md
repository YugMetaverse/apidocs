[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DetourCrowdAIController

# Class: DetourCrowdAIController

[ue/ue](../modules/ue_ue.md).DetourCrowdAIController

## Hierarchy

- [`AIController`](ue_ue.AIController.md)

  ↳ **`DetourCrowdAIController`**

## Table of contents

### Constructors

- [constructor](ue_ue.DetourCrowdAIController.md#constructor)

### Properties

- [ActionsComp](ue_ue.DetourCrowdAIController.md#actionscomp)
- [ActorLabel](ue_ue.DetourCrowdAIController.md#actorlabel)
- [AttachmentReplication](ue_ue.DetourCrowdAIController.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.DetourCrowdAIController.md#autoreceiveinput)
- [Blackboard](ue_ue.DetourCrowdAIController.md#blackboard)
- [BlueprintCreatedComponents](ue_ue.DetourCrowdAIController.md#blueprintcreatedcomponents)
- [BrainComponent](ue_ue.DetourCrowdAIController.md#braincomponent)
- [CachedGameplayTasksComponent](ue_ue.DetourCrowdAIController.md#cachedgameplaytaskscomponent)
- [Character](ue_ue.DetourCrowdAIController.md#character)
- [Children](ue_ue.DetourCrowdAIController.md#children)
- [ControlRotation](ue_ue.DetourCrowdAIController.md#controlrotation)
- [ControllingMatineeActors](ue_ue.DetourCrowdAIController.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.DetourCrowdAIController.md#customtimedilation)
- [DefaultNavigationFilterClass](ue_ue.DetourCrowdAIController.md#defaultnavigationfilterclass)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.DetourCrowdAIController.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.DetourCrowdAIController.md#folderpath)
- [GroupActor](ue_ue.DetourCrowdAIController.md#groupactor)
- [HiddenEditorViews](ue_ue.DetourCrowdAIController.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.DetourCrowdAIController.md#initiallifespan)
- [InputComponent](ue_ue.DetourCrowdAIController.md#inputcomponent)
- [InputPriority](ue_ue.DetourCrowdAIController.md#inputpriority)
- [InstanceComponents](ue_ue.DetourCrowdAIController.md#instancecomponents)
- [Instigator](ue_ue.DetourCrowdAIController.md#instigator)
- [Layers](ue_ue.DetourCrowdAIController.md#layers)
- [MinNetUpdateFrequency](ue_ue.DetourCrowdAIController.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.DetourCrowdAIController.md#netculldistancesquared)
- [NetDormancy](ue_ue.DetourCrowdAIController.md#netdormancy)
- [NetDriverName](ue_ue.DetourCrowdAIController.md#netdrivername)
- [NetPriority](ue_ue.DetourCrowdAIController.md#netpriority)
- [NetTag](ue_ue.DetourCrowdAIController.md#nettag)
- [NetUpdateFrequency](ue_ue.DetourCrowdAIController.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.DetourCrowdAIController.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.DetourCrowdAIController.md#onactorendoverlap)
- [OnActorHit](ue_ue.DetourCrowdAIController.md#onactorhit)
- [OnBeginCursorOver](ue_ue.DetourCrowdAIController.md#onbegincursorover)
- [OnClicked](ue_ue.DetourCrowdAIController.md#onclicked)
- [OnDestroyed](ue_ue.DetourCrowdAIController.md#ondestroyed)
- [OnEndCursorOver](ue_ue.DetourCrowdAIController.md#onendcursorover)
- [OnEndPlay](ue_ue.DetourCrowdAIController.md#onendplay)
- [OnInputTouchBegin](ue_ue.DetourCrowdAIController.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.DetourCrowdAIController.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.DetourCrowdAIController.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.DetourCrowdAIController.md#oninputtouchleave)
- [OnInstigatedAnyDamage](ue_ue.DetourCrowdAIController.md#oninstigatedanydamage)
- [OnReleased](ue_ue.DetourCrowdAIController.md#onreleased)
- [OnTakeAnyDamage](ue_ue.DetourCrowdAIController.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.DetourCrowdAIController.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.DetourCrowdAIController.md#ontakeradialdamage)
- [Owner](ue_ue.DetourCrowdAIController.md#owner)
- [ParentComponent](ue_ue.DetourCrowdAIController.md#parentcomponent)
- [ParentComponentActor](ue_ue.DetourCrowdAIController.md#parentcomponentactor)
- [PathFollowingComponent](ue_ue.DetourCrowdAIController.md#pathfollowingcomponent)
- [Pawn](ue_ue.DetourCrowdAIController.md#pawn)
- [PerceptionComponent](ue_ue.DetourCrowdAIController.md#perceptioncomponent)
- [PivotOffset](ue_ue.DetourCrowdAIController.md#pivotoffset)
- [PlayerState](ue_ue.DetourCrowdAIController.md#playerstate)
- [PrimaryActorTick](ue_ue.DetourCrowdAIController.md#primaryactortick)
- [ReceiveMoveCompleted](ue_ue.DetourCrowdAIController.md#receivemovecompleted)
- [RemoteRole](ue_ue.DetourCrowdAIController.md#remoterole)
- [ReplicatedMovement](ue_ue.DetourCrowdAIController.md#replicatedmovement)
- [Role](ue_ue.DetourCrowdAIController.md#role)
- [RootComponent](ue_ue.DetourCrowdAIController.md#rootcomponent)
- [SpawnCollisionHandlingMethod](ue_ue.DetourCrowdAIController.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.DetourCrowdAIController.md#spritescale)
- [StateName](ue_ue.DetourCrowdAIController.md#statename)
- [Tags](ue_ue.DetourCrowdAIController.md#tags)
- [TransformComponent](ue_ue.DetourCrowdAIController.md#transformcomponent)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.DetourCrowdAIController.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_AIController\_\_](ue_ue.DetourCrowdAIController.md#__tid_aicontroller__)
- [\_\_tid\_Actor\_\_](ue_ue.DetourCrowdAIController.md#__tid_actor__)
- [\_\_tid\_Controller\_\_](ue_ue.DetourCrowdAIController.md#__tid_controller__)
- [\_\_tid\_DetourCrowdAIController\_\_](ue_ue.DetourCrowdAIController.md#__tid_detourcrowdaicontroller__)
- [\_\_tid\_Object\_\_](ue_ue.DetourCrowdAIController.md#__tid_object__)
- [bActorEnableCollision](ue_ue.DetourCrowdAIController.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.DetourCrowdAIController.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.DetourCrowdAIController.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.DetourCrowdAIController.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.DetourCrowdAIController.md#ballowreceivetickeventondedicatedserver)
- [bAllowStrafe](ue_ue.DetourCrowdAIController.md#ballowstrafe)
- [bAllowTickBeforeBeginPlay](ue_ue.DetourCrowdAIController.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.DetourCrowdAIController.md#balwaysrelevant)
- [bAttachToPawn](ue_ue.DetourCrowdAIController.md#battachtopawn)
- [bAutoDestroyWhenFinished](ue_ue.DetourCrowdAIController.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.DetourCrowdAIController.md#bblockinput)
- [bCanBeDamaged](ue_ue.DetourCrowdAIController.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.DetourCrowdAIController.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.DetourCrowdAIController.md#bcollidewhenplacing)
- [bEditable](ue_ue.DetourCrowdAIController.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.DetourCrowdAIController.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.DetourCrowdAIController.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.DetourCrowdAIController.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.DetourCrowdAIController.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.DetourCrowdAIController.md#bhidden)
- [bHiddenEd](ue_ue.DetourCrowdAIController.md#bhiddened)
- [bHiddenEdLayer](ue_ue.DetourCrowdAIController.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.DetourCrowdAIController.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.DetourCrowdAIController.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.DetourCrowdAIController.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.DetourCrowdAIController.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.DetourCrowdAIController.md#biseditorpreviewactor)
- [bLOSflag](ue_ue.DetourCrowdAIController.md#blosflag)
- [bListedInSceneOutliner](ue_ue.DetourCrowdAIController.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.DetourCrowdAIController.md#blocklocation)
- [bNetLoadOnClient](ue_ue.DetourCrowdAIController.md#bnetloadonclient)
- [bNetStartup](ue_ue.DetourCrowdAIController.md#bnetstartup)
- [bNetTemporary](ue_ue.DetourCrowdAIController.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.DetourCrowdAIController.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.DetourCrowdAIController.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.DetourCrowdAIController.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.DetourCrowdAIController.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.DetourCrowdAIController.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.DetourCrowdAIController.md#breplayrewindable)
- [bReplicateMovement](ue_ue.DetourCrowdAIController.md#breplicatemovement)
- [bReplicates](ue_ue.DetourCrowdAIController.md#breplicates)
- [bSetControlRotationFromPawnOrientation](ue_ue.DetourCrowdAIController.md#bsetcontrolrotationfrompawnorientation)
- [bSkipExtraLOSChecks](ue_ue.DetourCrowdAIController.md#bskipextraloschecks)
- [bStopAILogicOnUnposses](ue_ue.DetourCrowdAIController.md#bstopailogiconunposses)
- [bTearOff](ue_ue.DetourCrowdAIController.md#btearoff)
- [bWantsPlayerState](ue_ue.DetourCrowdAIController.md#bwantsplayerstate)

### Methods

- [ActorHasTag](ue_ue.DetourCrowdAIController.md#actorhastag)
- [AddComponent](ue_ue.DetourCrowdAIController.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.DetourCrowdAIController.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.DetourCrowdAIController.md#addtickprerequisitecomponent)
- [CastToPlayerController](ue_ue.DetourCrowdAIController.md#casttoplayercontroller)
- [ClaimTaskResource](ue_ue.DetourCrowdAIController.md#claimtaskresource)
- [ClientSetLocation](ue_ue.DetourCrowdAIController.md#clientsetlocation)
- [ClientSetRotation](ue_ue.DetourCrowdAIController.md#clientsetrotation)
- [CreateDefaultSubobject](ue_ue.DetourCrowdAIController.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.DetourCrowdAIController.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.DetourCrowdAIController.md#disableinput)
- [EnableInput](ue_ue.DetourCrowdAIController.md#enableinput)
- [ExecuteUbergraph](ue_ue.DetourCrowdAIController.md#executeubergraph)
- [FlushNetDormancy](ue_ue.DetourCrowdAIController.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.DetourCrowdAIController.md#forcenetupdate)
- [GetAIPerceptionComponent](ue_ue.DetourCrowdAIController.md#getaiperceptioncomponent)
- [GetActorBounds](ue_ue.DetourCrowdAIController.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.DetourCrowdAIController.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.DetourCrowdAIController.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.DetourCrowdAIController.md#getactorforwardvector)
- [GetActorLabel](ue_ue.DetourCrowdAIController.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.DetourCrowdAIController.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.DetourCrowdAIController.md#getactorrightvector)
- [GetActorScale3D](ue_ue.DetourCrowdAIController.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.DetourCrowdAIController.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.DetourCrowdAIController.md#getactortimedilation)
- [GetActorUpVector](ue_ue.DetourCrowdAIController.md#getactorupvector)
- [GetAllChildActors](ue_ue.DetourCrowdAIController.md#getallchildactors)
- [GetAttachParentActor](ue_ue.DetourCrowdAIController.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.DetourCrowdAIController.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.DetourCrowdAIController.md#getattachedactors)
- [GetClass](ue_ue.DetourCrowdAIController.md#getclass)
- [GetComponentByClass](ue_ue.DetourCrowdAIController.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.DetourCrowdAIController.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.DetourCrowdAIController.md#getcomponentsbytag)
- [GetControlRotation](ue_ue.DetourCrowdAIController.md#getcontrolrotation)
- [GetDesiredRotation](ue_ue.DetourCrowdAIController.md#getdesiredrotation)
- [GetDistanceTo](ue_ue.DetourCrowdAIController.md#getdistanceto)
- [GetDotProductTo](ue_ue.DetourCrowdAIController.md#getdotproductto)
- [GetFocalPoint](ue_ue.DetourCrowdAIController.md#getfocalpoint)
- [GetFocalPointOnActor](ue_ue.DetourCrowdAIController.md#getfocalpointonactor)
- [GetFocusActor](ue_ue.DetourCrowdAIController.md#getfocusactor)
- [GetFolderPath](ue_ue.DetourCrowdAIController.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.DetourCrowdAIController.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.DetourCrowdAIController.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.DetourCrowdAIController.md#gethorizontaldotproductto)
- [GetImmediateMoveDestination](ue_ue.DetourCrowdAIController.md#getimmediatemovedestination)
- [GetInputAxisKeyValue](ue_ue.DetourCrowdAIController.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.DetourCrowdAIController.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.DetourCrowdAIController.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.DetourCrowdAIController.md#getinstigator)
- [GetInstigatorController](ue_ue.DetourCrowdAIController.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.DetourCrowdAIController.md#getlifespan)
- [GetLocalRole](ue_ue.DetourCrowdAIController.md#getlocalrole)
- [GetMoveStatus](ue_ue.DetourCrowdAIController.md#getmovestatus)
- [GetName](ue_ue.DetourCrowdAIController.md#getname)
- [GetOuter](ue_ue.DetourCrowdAIController.md#getouter)
- [GetOverlappingActors](ue_ue.DetourCrowdAIController.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.DetourCrowdAIController.md#getoverlappingcomponents)
- [GetOwner](ue_ue.DetourCrowdAIController.md#getowner)
- [GetParentActor](ue_ue.DetourCrowdAIController.md#getparentactor)
- [GetParentComponent](ue_ue.DetourCrowdAIController.md#getparentcomponent)
- [GetPathFollowingComponent](ue_ue.DetourCrowdAIController.md#getpathfollowingcomponent)
- [GetRemoteRole](ue_ue.DetourCrowdAIController.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.DetourCrowdAIController.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.DetourCrowdAIController.md#gettickablewhenpaused)
- [GetTransform](ue_ue.DetourCrowdAIController.md#gettransform)
- [GetVelocity](ue_ue.DetourCrowdAIController.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.DetourCrowdAIController.md#getverticaldistanceto)
- [GetViewTarget](ue_ue.DetourCrowdAIController.md#getviewtarget)
- [GetWorld](ue_ue.DetourCrowdAIController.md#getworld)
- [HasAuthority](ue_ue.DetourCrowdAIController.md#hasauthority)
- [HasPartialPath](ue_ue.DetourCrowdAIController.md#haspartialpath)
- [IsActorBeingDestroyed](ue_ue.DetourCrowdAIController.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.DetourCrowdAIController.md#isactortickenabled)
- [IsChildActor](ue_ue.DetourCrowdAIController.md#ischildactor)
- [IsEditable](ue_ue.DetourCrowdAIController.md#iseditable)
- [IsHiddenEd](ue_ue.DetourCrowdAIController.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.DetourCrowdAIController.md#ishiddenedatstartup)
- [IsLocalController](ue_ue.DetourCrowdAIController.md#islocalcontroller)
- [IsLocalPlayerController](ue_ue.DetourCrowdAIController.md#islocalplayercontroller)
- [IsLookInputIgnored](ue_ue.DetourCrowdAIController.md#islookinputignored)
- [IsMoveInputIgnored](ue_ue.DetourCrowdAIController.md#ismoveinputignored)
- [IsOverlappingActor](ue_ue.DetourCrowdAIController.md#isoverlappingactor)
- [IsPlayerController](ue_ue.DetourCrowdAIController.md#isplayercontroller)
- [IsSelectable](ue_ue.DetourCrowdAIController.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.DetourCrowdAIController.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.DetourCrowdAIController.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.DetourCrowdAIController.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.DetourCrowdAIController.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.DetourCrowdAIController.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.DetourCrowdAIController.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.DetourCrowdAIController.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.DetourCrowdAIController.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.DetourCrowdAIController.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.DetourCrowdAIController.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.DetourCrowdAIController.md#k2_attachtocomponent)
- [K2\_ClearFocus](ue_ue.DetourCrowdAIController.md#k2_clearfocus)
- [K2\_DestroyActor](ue_ue.DetourCrowdAIController.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.DetourCrowdAIController.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.DetourCrowdAIController.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.DetourCrowdAIController.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.DetourCrowdAIController.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.DetourCrowdAIController.md#k2_getcomponentsbyclass)
- [K2\_GetPawn](ue_ue.DetourCrowdAIController.md#k2_getpawn)
- [K2\_GetRootComponent](ue_ue.DetourCrowdAIController.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.DetourCrowdAIController.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.DetourCrowdAIController.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.DetourCrowdAIController.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.DetourCrowdAIController.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.DetourCrowdAIController.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.DetourCrowdAIController.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.DetourCrowdAIController.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.DetourCrowdAIController.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.DetourCrowdAIController.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.DetourCrowdAIController.md#k2_setactortransform)
- [K2\_SetFocalPoint](ue_ue.DetourCrowdAIController.md#k2_setfocalpoint)
- [K2\_SetFocus](ue_ue.DetourCrowdAIController.md#k2_setfocus)
- [K2\_TeleportTo](ue_ue.DetourCrowdAIController.md#k2_teleportto)
- [LineOfSightTo](ue_ue.DetourCrowdAIController.md#lineofsightto)
- [MakeMIDForMaterial](ue_ue.DetourCrowdAIController.md#makemidformaterial)
- [MakeNoise](ue_ue.DetourCrowdAIController.md#makenoise)
- [MoveToActor](ue_ue.DetourCrowdAIController.md#movetoactor)
- [MoveToLocation](ue_ue.DetourCrowdAIController.md#movetolocation)
- [OnGameplayTaskResourcesClaimed](ue_ue.DetourCrowdAIController.md#ongameplaytaskresourcesclaimed)
- [OnRep\_AttachmentReplication](ue_ue.DetourCrowdAIController.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.DetourCrowdAIController.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.DetourCrowdAIController.md#onrep_owner)
- [OnRep\_Pawn](ue_ue.DetourCrowdAIController.md#onrep_pawn)
- [OnRep\_PlayerState](ue_ue.DetourCrowdAIController.md#onrep_playerstate)
- [OnRep\_ReplicateMovement](ue_ue.DetourCrowdAIController.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.DetourCrowdAIController.md#onrep_replicatedmovement)
- [OnUsingBlackBoard](ue_ue.DetourCrowdAIController.md#onusingblackboard)
- [Possess](ue_ue.DetourCrowdAIController.md#possess)
- [PrestreamTextures](ue_ue.DetourCrowdAIController.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.DetourCrowdAIController.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.DetourCrowdAIController.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.DetourCrowdAIController.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.DetourCrowdAIController.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.DetourCrowdAIController.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.DetourCrowdAIController.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.DetourCrowdAIController.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.DetourCrowdAIController.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.DetourCrowdAIController.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.DetourCrowdAIController.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.DetourCrowdAIController.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.DetourCrowdAIController.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.DetourCrowdAIController.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.DetourCrowdAIController.md#receiveendplay)
- [ReceiveHit](ue_ue.DetourCrowdAIController.md#receivehit)
- [ReceiveInstigatedAnyDamage](ue_ue.DetourCrowdAIController.md#receiveinstigatedanydamage)
- [ReceivePointDamage](ue_ue.DetourCrowdAIController.md#receivepointdamage)
- [ReceivePossess](ue_ue.DetourCrowdAIController.md#receivepossess)
- [ReceiveRadialDamage](ue_ue.DetourCrowdAIController.md#receiveradialdamage)
- [ReceiveTick](ue_ue.DetourCrowdAIController.md#receivetick)
- [ReceiveUnPossess](ue_ue.DetourCrowdAIController.md#receiveunpossess)
- [RemoveTickPrerequisiteActor](ue_ue.DetourCrowdAIController.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.DetourCrowdAIController.md#removetickprerequisitecomponent)
- [ResetIgnoreInputFlags](ue_ue.DetourCrowdAIController.md#resetignoreinputflags)
- [ResetIgnoreLookInput](ue_ue.DetourCrowdAIController.md#resetignorelookinput)
- [ResetIgnoreMoveInput](ue_ue.DetourCrowdAIController.md#resetignoremoveinput)
- [RunBehaviorTree](ue_ue.DetourCrowdAIController.md#runbehaviortree)
- [SetActorEnableCollision](ue_ue.DetourCrowdAIController.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.DetourCrowdAIController.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.DetourCrowdAIController.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.DetourCrowdAIController.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.DetourCrowdAIController.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.DetourCrowdAIController.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.DetourCrowdAIController.md#setactortickinterval)
- [SetControlRotation](ue_ue.DetourCrowdAIController.md#setcontrolrotation)
- [SetFolderPath](ue_ue.DetourCrowdAIController.md#setfolderpath)
- [SetIgnoreLookInput](ue_ue.DetourCrowdAIController.md#setignorelookinput)
- [SetIgnoreMoveInput](ue_ue.DetourCrowdAIController.md#setignoremoveinput)
- [SetInitialLocationAndRotation](ue_ue.DetourCrowdAIController.md#setinitiallocationandrotation)
- [SetIsTemporarilyHiddenInEditor](ue_ue.DetourCrowdAIController.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.DetourCrowdAIController.md#setlifespan)
- [SetMoveBlockDetection](ue_ue.DetourCrowdAIController.md#setmoveblockdetection)
- [SetNetDormancy](ue_ue.DetourCrowdAIController.md#setnetdormancy)
- [SetOwner](ue_ue.DetourCrowdAIController.md#setowner)
- [SetPathFollowingComponent](ue_ue.DetourCrowdAIController.md#setpathfollowingcomponent)
- [SetReplicateMovement](ue_ue.DetourCrowdAIController.md#setreplicatemovement)
- [SetReplicates](ue_ue.DetourCrowdAIController.md#setreplicates)
- [SetTickGroup](ue_ue.DetourCrowdAIController.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.DetourCrowdAIController.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.DetourCrowdAIController.md#snaprootcomponentto)
- [StopMovement](ue_ue.DetourCrowdAIController.md#stopmovement)
- [TearOff](ue_ue.DetourCrowdAIController.md#tearoff)
- [UnPossess](ue_ue.DetourCrowdAIController.md#unpossess)
- [UnclaimTaskResource](ue_ue.DetourCrowdAIController.md#unclaimtaskresource)
- [UseBlackboard](ue_ue.DetourCrowdAIController.md#useblackboard)
- [UserConstructionScript](ue_ue.DetourCrowdAIController.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.DetourCrowdAIController.md#wasrecentlyrendered)
- [Find](ue_ue.DetourCrowdAIController.md#find)
- [Load](ue_ue.DetourCrowdAIController.md#load)
- [StaticClass](ue_ue.DetourCrowdAIController.md#staticclass)

## Constructors

### constructor

• **new DetourCrowdAIController**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AIController](ue_ue.AIController.md).[constructor](ue_ue.AIController.md#constructor)

#### Defined in

[ue/ue.d.ts:30752](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30752)

## Properties

### ActionsComp

• **ActionsComp**: [`PawnActionsComponent`](ue_ue.PawnActionsComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[ActionsComp](ue_ue.AIController.md#actionscomp)

#### Defined in

[ue/ue.d.ts:14950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14950)

___

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[AIController](ue_ue.AIController.md).[ActorLabel](ue_ue.AIController.md#actorlabel)

#### Defined in

[ue/ue.d.ts:13176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13176)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[AttachmentReplication](ue_ue.AIController.md#attachmentreplication)

#### Defined in

[ue/ue.d.ts:13151](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13151)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[AutoReceiveInput](ue_ue.AIController.md#autoreceiveinput)

#### Defined in

[ue/ue.d.ts:13157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13157)

___

### Blackboard

• **Blackboard**: [`BlackboardComponent`](ue_ue.BlackboardComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[Blackboard](ue_ue.AIController.md#blackboard)

#### Defined in

[ue/ue.d.ts:14951](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14951)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[AIController](ue_ue.AIController.md).[BlueprintCreatedComponents](ue_ue.AIController.md#blueprintcreatedcomponents)

#### Defined in

[ue/ue.d.ts:13206](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13206)

___

### BrainComponent

• **BrainComponent**: [`BrainComponent`](ue_ue.BrainComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[BrainComponent](ue_ue.AIController.md#braincomponent)

#### Defined in

[ue/ue.d.ts:14948](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14948)

___

### CachedGameplayTasksComponent

• **CachedGameplayTasksComponent**: [`GameplayTasksComponent`](ue_ue.GameplayTasksComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[CachedGameplayTasksComponent](ue_ue.AIController.md#cachedgameplaytaskscomponent)

#### Defined in

[ue/ue.d.ts:14952](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14952)

___

### Character

• **Character**: [`Character`](ue_ue.Character.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[Character](ue_ue.AIController.md#character)

#### Defined in

[ue/ue.d.ts:12461](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12461)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[AIController](ue_ue.AIController.md).[Children](ue_ue.AIController.md#children)

#### Defined in

[ue/ue.d.ts:13166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13166)

___

### ControlRotation

• **ControlRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[ControlRotation](ue_ue.AIController.md#controlrotation)

#### Defined in

[ue/ue.d.ts:12463](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12463)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[AIController](ue_ue.AIController.md).[ControllingMatineeActors](ue_ue.AIController.md#controllingmatineeactors)

#### Defined in

[ue/ue.d.ts:13169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13169)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[CustomTimeDilation](ue_ue.AIController.md#customtimedilation)

#### Defined in

[ue/ue.d.ts:13150](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13150)

___

### DefaultNavigationFilterClass

• **DefaultNavigationFilterClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[DefaultNavigationFilterClass](ue_ue.AIController.md#defaultnavigationfilterclass)

#### Defined in

[ue/ue.d.ts:14953](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14953)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.AIController.md#defaultupdateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13146](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13146)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[AIController](ue_ue.AIController.md).[FolderPath](ue_ue.AIController.md#folderpath)

#### Defined in

[ue/ue.d.ts:13177](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13177)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GroupActor](ue_ue.AIController.md#groupactor)

#### Defined in

[ue/ue.d.ts:13173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13173)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[AIController](ue_ue.AIController.md).[HiddenEditorViews](ue_ue.AIController.md#hiddeneditorviews)

#### Defined in

[ue/ue.d.ts:13175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13175)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[InitialLifeSpan](ue_ue.AIController.md#initiallifespan)

#### Defined in

[ue/ue.d.ts:13149](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13149)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[InputComponent](ue_ue.AIController.md#inputcomponent)

#### Defined in

[ue/ue.d.ts:13159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13159)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[InputPriority](ue_ue.AIController.md#inputpriority)

#### Defined in

[ue/ue.d.ts:13158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13158)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[AIController](ue_ue.AIController.md).[InstanceComponents](ue_ue.AIController.md#instancecomponents)

#### Defined in

[ue/ue.d.ts:13205](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13205)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[Instigator](ue_ue.AIController.md#instigator)

#### Defined in

[ue/ue.d.ts:13165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13165)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[Layers](ue_ue.AIController.md#layers)

#### Defined in

[ue/ue.d.ts:13170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13170)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[MinNetUpdateFrequency](ue_ue.AIController.md#minnetupdatefrequency)

#### Defined in

[ue/ue.d.ts:13163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13163)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[NetCullDistanceSquared](ue_ue.AIController.md#netculldistancesquared)

#### Defined in

[ue/ue.d.ts:13160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13160)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[NetDormancy](ue_ue.AIController.md#netdormancy)

#### Defined in

[ue/ue.d.ts:13155](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13155)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[AIController](ue_ue.AIController.md).[NetDriverName](ue_ue.AIController.md#netdrivername)

#### Defined in

[ue/ue.d.ts:13153](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13153)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[NetPriority](ue_ue.AIController.md#netpriority)

#### Defined in

[ue/ue.d.ts:13164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13164)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[NetTag](ue_ue.AIController.md#nettag)

#### Defined in

[ue/ue.d.ts:13161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13161)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[NetUpdateFrequency](ue_ue.AIController.md#netupdatefrequency)

#### Defined in

[ue/ue.d.ts:13162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13162)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnActorBeginOverlap](ue_ue.AIController.md#onactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13192](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13192)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnActorEndOverlap](ue_ue.AIController.md#onactorendoverlap)

#### Defined in

[ue/ue.d.ts:13193](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13193)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnActorHit](ue_ue.AIController.md#onactorhit)

#### Defined in

[ue/ue.d.ts:13202](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13202)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnBeginCursorOver](ue_ue.AIController.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:13194](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13194)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnClicked](ue_ue.AIController.md#onclicked)

#### Defined in

[ue/ue.d.ts:13196](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13196)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnDestroyed](ue_ue.AIController.md#ondestroyed)

#### Defined in

[ue/ue.d.ts:13203](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13203)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnEndCursorOver](ue_ue.AIController.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:13195](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13195)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnEndPlay](ue_ue.AIController.md#onendplay)

#### Defined in

[ue/ue.d.ts:13204](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13204)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnInputTouchBegin](ue_ue.AIController.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13198](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13198)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnInputTouchEnd](ue_ue.AIController.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:13199](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13199)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnInputTouchEnter](ue_ue.AIController.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:13200](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13200)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnInputTouchLeave](ue_ue.AIController.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:13201](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13201)

___

### OnInstigatedAnyDamage

• **OnInstigatedAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnInstigatedAnyDamage](ue_ue.AIController.md#oninstigatedanydamage)

#### Defined in

[ue/ue.d.ts:12458](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12458)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnReleased](ue_ue.AIController.md#onreleased)

#### Defined in

[ue/ue.d.ts:13197](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13197)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnTakeAnyDamage](ue_ue.AIController.md#ontakeanydamage)

#### Defined in

[ue/ue.d.ts:13189](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13189)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnTakePointDamage](ue_ue.AIController.md#ontakepointdamage)

#### Defined in

[ue/ue.d.ts:13190](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13190)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[OnTakeRadialDamage](ue_ue.AIController.md#ontakeradialdamage)

#### Defined in

[ue/ue.d.ts:13191](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13191)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[Owner](ue_ue.AIController.md#owner)

#### Defined in

[ue/ue.d.ts:13152](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13152)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[AIController](ue_ue.AIController.md).[ParentComponent](ue_ue.AIController.md#parentcomponent)

#### Defined in

[ue/ue.d.ts:13172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13172)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[AIController](ue_ue.AIController.md).[ParentComponentActor](ue_ue.AIController.md#parentcomponentactor)

#### Defined in

[ue/ue.d.ts:13171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13171)

___

### PathFollowingComponent

• **PathFollowingComponent**: [`PathFollowingComponent`](ue_ue.PathFollowingComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[PathFollowingComponent](ue_ue.AIController.md#pathfollowingcomponent)

#### Defined in

[ue/ue.d.ts:14947](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14947)

___

### Pawn

• **Pawn**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[Pawn](ue_ue.AIController.md#pawn)

#### Defined in

[ue/ue.d.ts:12460](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12460)

___

### PerceptionComponent

• **PerceptionComponent**: [`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[PerceptionComponent](ue_ue.AIController.md#perceptioncomponent)

#### Defined in

[ue/ue.d.ts:14949](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14949)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[PivotOffset](ue_ue.AIController.md#pivotoffset)

#### Defined in

[ue/ue.d.ts:13168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13168)

___

### PlayerState

• **PlayerState**: [`PlayerState`](ue_ue.PlayerState.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[PlayerState](ue_ue.AIController.md#playerstate)

#### Defined in

[ue/ue.d.ts:12457](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12457)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[PrimaryActorTick](ue_ue.AIController.md#primaryactortick)

#### Defined in

[ue/ue.d.ts:13115](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13115)

___

### ReceiveMoveCompleted

• **ReceiveMoveCompleted**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`RequestID`: [`AIRequestID`](ue_ue.AIRequestID.md), `Result`: [`EPathFollowingResult`](../enums/ue_ue.EPathFollowingResult.md)) => `void`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[ReceiveMoveCompleted](ue_ue.AIController.md#receivemovecompleted)

#### Defined in

[ue/ue.d.ts:14954](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14954)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[RemoteRole](ue_ue.AIController.md#remoterole)

#### Defined in

[ue/ue.d.ts:13147](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13147)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[ReplicatedMovement](ue_ue.AIController.md#replicatedmovement)

#### Defined in

[ue/ue.d.ts:13148](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13148)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[Role](ue_ue.AIController.md#role)

#### Defined in

[ue/ue.d.ts:13154](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13154)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[RootComponent](ue_ue.AIController.md#rootcomponent)

#### Defined in

[ue/ue.d.ts:13167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13167)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[SpawnCollisionHandlingMethod](ue_ue.AIController.md#spawncollisionhandlingmethod)

#### Defined in

[ue/ue.d.ts:13156](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13156)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[AIController](ue_ue.AIController.md).[SpriteScale](ue_ue.AIController.md#spritescale)

#### Defined in

[ue/ue.d.ts:13174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13174)

___

### StateName

• **StateName**: `string`

#### Inherited from

[AIController](ue_ue.AIController.md).[StateName](ue_ue.AIController.md#statename)

#### Defined in

[ue/ue.d.ts:12459](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12459)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AIController](ue_ue.AIController.md).[Tags](ue_ue.AIController.md#tags)

#### Defined in

[ue/ue.d.ts:13188](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13188)

___

### TransformComponent

• **TransformComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[TransformComponent](ue_ue.AIController.md#transformcomponent)

#### Defined in

[ue/ue.d.ts:12462](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12462)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.AIController.md#updateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13145](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13145)

___

### \_\_tid\_AIController\_\_

• **\_\_tid\_AIController\_\_**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[__tid_AIController__](ue_ue.AIController.md#__tid_aicontroller__)

#### Defined in

[ue/ue.d.ts:14980](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14980)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[__tid_Actor__](ue_ue.AIController.md#__tid_actor__)

#### Defined in

[ue/ue.d.ts:13348](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13348)

___

### \_\_tid\_Controller\_\_

• **\_\_tid\_Controller\_\_**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[__tid_Controller__](ue_ue.AIController.md#__tid_controller__)

#### Defined in

[ue/ue.d.ts:12497](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12497)

___

### \_\_tid\_DetourCrowdAIController\_\_

• **\_\_tid\_DetourCrowdAIController\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:30757](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30757)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[__tid_Object__](ue_ue.AIController.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bActorEnableCollision](ue_ue.AIController.md#bactorenablecollision)

#### Defined in

[ue/ue.d.ts:13143](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13143)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bActorIsBeingDestroyed](ue_ue.AIController.md#bactorisbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13144](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13144)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bActorLabelEditable](ue_ue.AIController.md#bactorlabeleditable)

#### Defined in

[ue/ue.d.ts:13183](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13183)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bActorSeamlessTraveled](ue_ue.AIController.md#bactorseamlesstraveled)

#### Defined in

[ue/ue.d.ts:13139](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13139)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.AIController.md#ballowreceivetickeventondedicatedserver)

#### Defined in

[ue/ue.d.ts:13142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13142)

___

### bAllowStrafe

• **bAllowStrafe**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bAllowStrafe](ue_ue.AIController.md#ballowstrafe)

#### Defined in

[ue/ue.d.ts:14944](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14944)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bAllowTickBeforeBeginPlay](ue_ue.AIController.md#ballowtickbeforebeginplay)

#### Defined in

[ue/ue.d.ts:13129](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13129)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bAlwaysRelevant](ue_ue.AIController.md#balwaysrelevant)

#### Defined in

[ue/ue.d.ts:13120](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13120)

___

### bAttachToPawn

• **bAttachToPawn**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bAttachToPawn](ue_ue.AIController.md#battachtopawn)

#### Defined in

[ue/ue.d.ts:12464](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12464)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bAutoDestroyWhenFinished](ue_ue.AIController.md#bautodestroywhenfinished)

#### Defined in

[ue/ue.d.ts:13130](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13130)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bBlockInput](ue_ue.AIController.md#bblockinput)

#### Defined in

[ue/ue.d.ts:13131](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13131)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bCanBeDamaged](ue_ue.AIController.md#bcanbedamaged)

#### Defined in

[ue/ue.d.ts:13132](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13132)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bCanBeInCluster](ue_ue.AIController.md#bcanbeincluster)

#### Defined in

[ue/ue.d.ts:13141](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13141)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bCollideWhenPlacing](ue_ue.AIController.md#bcollidewhenplacing)

#### Defined in

[ue/ue.d.ts:13133](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13133)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bEditable](ue_ue.AIController.md#beditable)

#### Defined in

[ue/ue.d.ts:13184](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13184)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bEnableAutoLODGeneration](ue_ue.AIController.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:13137](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13137)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bExchangedRoles](ue_ue.AIController.md#bexchangedroles)

#### Defined in

[ue/ue.d.ts:13123](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13123)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bFindCameraComponentWhenViewTarget](ue_ue.AIController.md#bfindcameracomponentwhenviewtarget)

#### Defined in

[ue/ue.d.ts:13134](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13134)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.AIController.md#bgenerateoverlapeventsduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13135](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13135)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bHidden](ue_ue.AIController.md#bhidden)

#### Defined in

[ue/ue.d.ts:13116](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13116)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bHiddenEd](ue_ue.AIController.md#bhiddened)

#### Defined in

[ue/ue.d.ts:13178](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13178)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bHiddenEdLayer](ue_ue.AIController.md#bhiddenedlayer)

#### Defined in

[ue/ue.d.ts:13180](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13180)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bHiddenEdLevel](ue_ue.AIController.md#bhiddenedlevel)

#### Defined in

[ue/ue.d.ts:13181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13181)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bHiddenEdTemporary](ue_ue.AIController.md#bhiddenedtemporary)

#### Defined in

[ue/ue.d.ts:13187](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13187)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bIgnoresOriginShifting](ue_ue.AIController.md#bignoresoriginshifting)

#### Defined in

[ue/ue.d.ts:13136](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13136)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bIsEditorOnlyActor](ue_ue.AIController.md#biseditoronlyactor)

#### Defined in

[ue/ue.d.ts:13138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13138)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bIsEditorPreviewActor](ue_ue.AIController.md#biseditorpreviewactor)

#### Defined in

[ue/ue.d.ts:13179](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13179)

___

### bLOSflag

• **bLOSflag**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bLOSflag](ue_ue.AIController.md#blosflag)

#### Defined in

[ue/ue.d.ts:14942](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14942)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bListedInSceneOutliner](ue_ue.AIController.md#blistedinsceneoutliner)

#### Defined in

[ue/ue.d.ts:13185](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13185)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bLockLocation](ue_ue.AIController.md#blocklocation)

#### Defined in

[ue/ue.d.ts:13182](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13182)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bNetLoadOnClient](ue_ue.AIController.md#bnetloadonclient)

#### Defined in

[ue/ue.d.ts:13124](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13124)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bNetStartup](ue_ue.AIController.md#bnetstartup)

#### Defined in

[ue/ue.d.ts:13118](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13118)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bNetTemporary](ue_ue.AIController.md#bnettemporary)

#### Defined in

[ue/ue.d.ts:13117](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13117)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bNetUseOwnerRelevancy](ue_ue.AIController.md#bnetuseownerrelevancy)

#### Defined in

[ue/ue.d.ts:13125](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13125)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bOnlyRelevantToOwner](ue_ue.AIController.md#bonlyrelevanttoowner)

#### Defined in

[ue/ue.d.ts:13119](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13119)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bOptimizeBPComponentData](ue_ue.AIController.md#boptimizebpcomponentdata)

#### Defined in

[ue/ue.d.ts:13186](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13186)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bRelevantForLevelBounds](ue_ue.AIController.md#brelevantforlevelbounds)

#### Defined in

[ue/ue.d.ts:13127](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13127)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bRelevantForNetworkReplays](ue_ue.AIController.md#brelevantfornetworkreplays)

#### Defined in

[ue/ue.d.ts:13126](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13126)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bReplayRewindable](ue_ue.AIController.md#breplayrewindable)

#### Defined in

[ue/ue.d.ts:13128](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13128)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bReplicateMovement](ue_ue.AIController.md#breplicatemovement)

#### Defined in

[ue/ue.d.ts:13121](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13121)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bReplicates](ue_ue.AIController.md#breplicates)

#### Defined in

[ue/ue.d.ts:13140](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13140)

___

### bSetControlRotationFromPawnOrientation

• **bSetControlRotationFromPawnOrientation**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bSetControlRotationFromPawnOrientation](ue_ue.AIController.md#bsetcontrolrotationfrompawnorientation)

#### Defined in

[ue/ue.d.ts:14946](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14946)

___

### bSkipExtraLOSChecks

• **bSkipExtraLOSChecks**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bSkipExtraLOSChecks](ue_ue.AIController.md#bskipextraloschecks)

#### Defined in

[ue/ue.d.ts:14943](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14943)

___

### bStopAILogicOnUnposses

• **bStopAILogicOnUnposses**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bStopAILogicOnUnposses](ue_ue.AIController.md#bstopailogiconunposses)

#### Defined in

[ue/ue.d.ts:14941](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14941)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bTearOff](ue_ue.AIController.md#btearoff)

#### Defined in

[ue/ue.d.ts:13122](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13122)

___

### bWantsPlayerState

• **bWantsPlayerState**: `boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[bWantsPlayerState](ue_ue.AIController.md#bwantsplayerstate)

#### Defined in

[ue/ue.d.ts:14945](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14945)

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

#### Defined in

[ue/ue.d.ts:13207](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13207)

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

#### Defined in

[ue/ue.d.ts:13208](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13208)

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

#### Defined in

[ue/ue.d.ts:13209](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13209)

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

#### Defined in

[ue/ue.d.ts:13210](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13210)

___

### CastToPlayerController

▸ **CastToPlayerController**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[CastToPlayerController](ue_ue.AIController.md#casttoplayercontroller)

#### Defined in

[ue/ue.d.ts:12465](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12465)

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

#### Defined in

[ue/ue.d.ts:14955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14955)

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

#### Defined in

[ue/ue.d.ts:12466](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12466)

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

#### Defined in

[ue/ue.d.ts:12467](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12467)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:13211](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13211)

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

#### Defined in

[ue/ue.d.ts:13212](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13212)

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

#### Defined in

[ue/ue.d.ts:13213](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13213)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[FlushNetDormancy](ue_ue.AIController.md#flushnetdormancy)

#### Defined in

[ue/ue.d.ts:13214](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13214)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[ForceNetUpdate](ue_ue.AIController.md#forcenetupdate)

#### Defined in

[ue/ue.d.ts:13215](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13215)

___

### GetAIPerceptionComponent

▸ **GetAIPerceptionComponent**(): [`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)

#### Returns

[`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetAIPerceptionComponent](ue_ue.AIController.md#getaiperceptioncomponent)

#### Defined in

[ue/ue.d.ts:14956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14956)

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

#### Defined in

[ue/ue.d.ts:13216](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13216)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorEnableCollision](ue_ue.AIController.md#getactorenablecollision)

#### Defined in

[ue/ue.d.ts:13217](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13217)

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

#### Defined in

[ue/ue.d.ts:13218](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13218)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorForwardVector](ue_ue.AIController.md#getactorforwardvector)

#### Defined in

[ue/ue.d.ts:13219](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13219)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorLabel](ue_ue.AIController.md#getactorlabel)

#### Defined in

[ue/ue.d.ts:13220](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13220)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorRelativeScale3D](ue_ue.AIController.md#getactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13221](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13221)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorRightVector](ue_ue.AIController.md#getactorrightvector)

#### Defined in

[ue/ue.d.ts:13222](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13222)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorScale3D](ue_ue.AIController.md#getactorscale3d)

#### Defined in

[ue/ue.d.ts:13223](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13223)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorTickInterval](ue_ue.AIController.md#getactortickinterval)

#### Defined in

[ue/ue.d.ts:13224](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13224)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorTimeDilation](ue_ue.AIController.md#getactortimedilation)

#### Defined in

[ue/ue.d.ts:13225](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13225)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetActorUpVector](ue_ue.AIController.md#getactorupvector)

#### Defined in

[ue/ue.d.ts:13226](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13226)

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

#### Defined in

[ue/ue.d.ts:13227](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13227)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetAttachParentActor](ue_ue.AIController.md#getattachparentactor)

#### Defined in

[ue/ue.d.ts:13229](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13229)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetAttachParentSocketName](ue_ue.AIController.md#getattachparentsocketname)

#### Defined in

[ue/ue.d.ts:13230](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13230)

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

#### Defined in

[ue/ue.d.ts:13228](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13228)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetClass](ue_ue.AIController.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

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

#### Defined in

[ue/ue.d.ts:13231](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13231)

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

#### Defined in

[ue/ue.d.ts:13232](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13232)

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

#### Defined in

[ue/ue.d.ts:13233](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13233)

___

### GetControlRotation

▸ **GetControlRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetControlRotation](ue_ue.AIController.md#getcontrolrotation)

#### Defined in

[ue/ue.d.ts:12468](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12468)

___

### GetDesiredRotation

▸ **GetDesiredRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetDesiredRotation](ue_ue.AIController.md#getdesiredrotation)

#### Defined in

[ue/ue.d.ts:12469](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12469)

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

#### Defined in

[ue/ue.d.ts:13234](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13234)

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

#### Defined in

[ue/ue.d.ts:13235](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13235)

___

### GetFocalPoint

▸ **GetFocalPoint**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetFocalPoint](ue_ue.AIController.md#getfocalpoint)

#### Defined in

[ue/ue.d.ts:14957](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14957)

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

#### Defined in

[ue/ue.d.ts:14958](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14958)

___

### GetFocusActor

▸ **GetFocusActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetFocusActor](ue_ue.AIController.md#getfocusactor)

#### Defined in

[ue/ue.d.ts:14959](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14959)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetFolderPath](ue_ue.AIController.md#getfolderpath)

#### Defined in

[ue/ue.d.ts:13236](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13236)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetGameTimeSinceCreation](ue_ue.AIController.md#getgametimesincecreation)

#### Defined in

[ue/ue.d.ts:13237](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13237)

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

#### Defined in

[ue/ue.d.ts:13238](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13238)

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

#### Defined in

[ue/ue.d.ts:13239](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13239)

___

### GetImmediateMoveDestination

▸ **GetImmediateMoveDestination**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetImmediateMoveDestination](ue_ue.AIController.md#getimmediatemovedestination)

#### Defined in

[ue/ue.d.ts:14960](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14960)

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

#### Defined in

[ue/ue.d.ts:13240](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13240)

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

#### Defined in

[ue/ue.d.ts:13241](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13241)

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

#### Defined in

[ue/ue.d.ts:13242](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13242)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetInstigator](ue_ue.AIController.md#getinstigator)

#### Defined in

[ue/ue.d.ts:13243](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13243)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetInstigatorController](ue_ue.AIController.md#getinstigatorcontroller)

#### Defined in

[ue/ue.d.ts:13244](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13244)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetLifeSpan](ue_ue.AIController.md#getlifespan)

#### Defined in

[ue/ue.d.ts:13245](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13245)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetLocalRole](ue_ue.AIController.md#getlocalrole)

#### Defined in

[ue/ue.d.ts:13246](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13246)

___

### GetMoveStatus

▸ **GetMoveStatus**(): [`EPathFollowingStatus`](../enums/ue_ue.EPathFollowingStatus.md)

#### Returns

[`EPathFollowingStatus`](../enums/ue_ue.EPathFollowingStatus.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetMoveStatus](ue_ue.AIController.md#getmovestatus)

#### Defined in

[ue/ue.d.ts:14961](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14961)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetName](ue_ue.AIController.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetOuter](ue_ue.AIController.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

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

#### Defined in

[ue/ue.d.ts:13247](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13247)

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

#### Defined in

[ue/ue.d.ts:13248](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13248)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetOwner](ue_ue.AIController.md#getowner)

#### Defined in

[ue/ue.d.ts:13249](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13249)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetParentActor](ue_ue.AIController.md#getparentactor)

#### Defined in

[ue/ue.d.ts:13250](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13250)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetParentComponent](ue_ue.AIController.md#getparentcomponent)

#### Defined in

[ue/ue.d.ts:13251](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13251)

___

### GetPathFollowingComponent

▸ **GetPathFollowingComponent**(): [`PathFollowingComponent`](ue_ue.PathFollowingComponent.md)

#### Returns

[`PathFollowingComponent`](ue_ue.PathFollowingComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetPathFollowingComponent](ue_ue.AIController.md#getpathfollowingcomponent)

#### Defined in

[ue/ue.d.ts:14962](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14962)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetRemoteRole](ue_ue.AIController.md#getremoterole)

#### Defined in

[ue/ue.d.ts:13252](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13252)

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

#### Defined in

[ue/ue.d.ts:13253](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13253)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[GetTickableWhenPaused](ue_ue.AIController.md#gettickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13254](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13254)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetTransform](ue_ue.AIController.md#gettransform)

#### Defined in

[ue/ue.d.ts:13255](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13255)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetVelocity](ue_ue.AIController.md#getvelocity)

#### Defined in

[ue/ue.d.ts:13256](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13256)

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

#### Defined in

[ue/ue.d.ts:13257](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13257)

___

### GetViewTarget

▸ **GetViewTarget**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetViewTarget](ue_ue.AIController.md#getviewtarget)

#### Defined in

[ue/ue.d.ts:12470](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12470)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[GetWorld](ue_ue.AIController.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[HasAuthority](ue_ue.AIController.md#hasauthority)

#### Defined in

[ue/ue.d.ts:13258](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13258)

___

### HasPartialPath

▸ **HasPartialPath**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[HasPartialPath](ue_ue.AIController.md#haspartialpath)

#### Defined in

[ue/ue.d.ts:14963](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14963)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsActorBeingDestroyed](ue_ue.AIController.md#isactorbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13259](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13259)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsActorTickEnabled](ue_ue.AIController.md#isactortickenabled)

#### Defined in

[ue/ue.d.ts:13260](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13260)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsChildActor](ue_ue.AIController.md#ischildactor)

#### Defined in

[ue/ue.d.ts:13261](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13261)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsEditable](ue_ue.AIController.md#iseditable)

#### Defined in

[ue/ue.d.ts:13262](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13262)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsHiddenEd](ue_ue.AIController.md#ishiddened)

#### Defined in

[ue/ue.d.ts:13263](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13263)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsHiddenEdAtStartup](ue_ue.AIController.md#ishiddenedatstartup)

#### Defined in

[ue/ue.d.ts:13264](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13264)

___

### IsLocalController

▸ **IsLocalController**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsLocalController](ue_ue.AIController.md#islocalcontroller)

#### Defined in

[ue/ue.d.ts:12471](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12471)

___

### IsLocalPlayerController

▸ **IsLocalPlayerController**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsLocalPlayerController](ue_ue.AIController.md#islocalplayercontroller)

#### Defined in

[ue/ue.d.ts:12472](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12472)

___

### IsLookInputIgnored

▸ **IsLookInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsLookInputIgnored](ue_ue.AIController.md#islookinputignored)

#### Defined in

[ue/ue.d.ts:12473](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12473)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsMoveInputIgnored](ue_ue.AIController.md#ismoveinputignored)

#### Defined in

[ue/ue.d.ts:12474](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12474)

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

#### Defined in

[ue/ue.d.ts:13265](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13265)

___

### IsPlayerController

▸ **IsPlayerController**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsPlayerController](ue_ue.AIController.md#isplayercontroller)

#### Defined in

[ue/ue.d.ts:12475](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12475)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AIController](ue_ue.AIController.md).[IsSelectable](ue_ue.AIController.md#isselectable)

#### Defined in

[ue/ue.d.ts:13266](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13266)

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

#### Defined in

[ue/ue.d.ts:13267](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13267)

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

#### Defined in

[ue/ue.d.ts:13268](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13268)

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

#### Defined in

[ue/ue.d.ts:13269](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13269)

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

#### Defined in

[ue/ue.d.ts:13270](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13270)

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

#### Defined in

[ue/ue.d.ts:13271](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13271)

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

#### Defined in

[ue/ue.d.ts:13272](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13272)

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

#### Defined in

[ue/ue.d.ts:13273](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13273)

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

#### Defined in

[ue/ue.d.ts:13274](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13274)

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

#### Defined in

[ue/ue.d.ts:13275](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13275)

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

#### Defined in

[ue/ue.d.ts:13276](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13276)

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

#### Defined in

[ue/ue.d.ts:13277](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13277)

___

### K2\_ClearFocus

▸ **K2_ClearFocus**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[K2_ClearFocus](ue_ue.AIController.md#k2_clearfocus)

#### Defined in

[ue/ue.d.ts:14964](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14964)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[K2_DestroyActor](ue_ue.AIController.md#k2_destroyactor)

#### Defined in

[ue/ue.d.ts:13278](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13278)

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

#### Defined in

[ue/ue.d.ts:13279](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13279)

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

#### Defined in

[ue/ue.d.ts:13280](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13280)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[K2_GetActorLocation](ue_ue.AIController.md#k2_getactorlocation)

#### Defined in

[ue/ue.d.ts:13281](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13281)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[K2_GetActorRotation](ue_ue.AIController.md#k2_getactorrotation)

#### Defined in

[ue/ue.d.ts:13282](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13282)

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

#### Defined in

[ue/ue.d.ts:13283](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13283)

___

### K2\_GetPawn

▸ **K2_GetPawn**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[K2_GetPawn](ue_ue.AIController.md#k2_getpawn)

#### Defined in

[ue/ue.d.ts:12476](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12476)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[AIController](ue_ue.AIController.md).[K2_GetRootComponent](ue_ue.AIController.md#k2_getrootcomponent)

#### Defined in

[ue/ue.d.ts:13284](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13284)

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

#### Defined in

[ue/ue.d.ts:13285](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13285)

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

#### Defined in

[ue/ue.d.ts:13286](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13286)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[K2_OnReset](ue_ue.AIController.md#k2_onreset)

#### Defined in

[ue/ue.d.ts:13287](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13287)

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

#### Defined in

[ue/ue.d.ts:13288](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13288)

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

#### Defined in

[ue/ue.d.ts:13289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13289)

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

#### Defined in

[ue/ue.d.ts:13290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13290)

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

#### Defined in

[ue/ue.d.ts:13291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13291)

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

#### Defined in

[ue/ue.d.ts:13292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13292)

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

#### Defined in

[ue/ue.d.ts:13293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13293)

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

#### Defined in

[ue/ue.d.ts:13294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13294)

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

#### Defined in

[ue/ue.d.ts:14965](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14965)

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

#### Defined in

[ue/ue.d.ts:14966](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14966)

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

#### Defined in

[ue/ue.d.ts:13295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13295)

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

#### Defined in

[ue/ue.d.ts:12477](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12477)

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

#### Defined in

[ue/ue.d.ts:13296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13296)

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

#### Defined in

[ue/ue.d.ts:13297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13297)

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

#### Defined in

[ue/ue.d.ts:14967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14967)

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

#### Defined in

[ue/ue.d.ts:14968](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14968)

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

#### Defined in

[ue/ue.d.ts:14969](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14969)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[OnRep_AttachmentReplication](ue_ue.AIController.md#onrep_attachmentreplication)

#### Defined in

[ue/ue.d.ts:13298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13298)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[OnRep_Instigator](ue_ue.AIController.md#onrep_instigator)

#### Defined in

[ue/ue.d.ts:13299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13299)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[OnRep_Owner](ue_ue.AIController.md#onrep_owner)

#### Defined in

[ue/ue.d.ts:13300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13300)

___

### OnRep\_Pawn

▸ **OnRep_Pawn**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[OnRep_Pawn](ue_ue.AIController.md#onrep_pawn)

#### Defined in

[ue/ue.d.ts:12478](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12478)

___

### OnRep\_PlayerState

▸ **OnRep_PlayerState**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[OnRep_PlayerState](ue_ue.AIController.md#onrep_playerstate)

#### Defined in

[ue/ue.d.ts:12479](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12479)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[OnRep_ReplicateMovement](ue_ue.AIController.md#onrep_replicatemovement)

#### Defined in

[ue/ue.d.ts:13302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13302)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[OnRep_ReplicatedMovement](ue_ue.AIController.md#onrep_replicatedmovement)

#### Defined in

[ue/ue.d.ts:13301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13301)

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

#### Defined in

[ue/ue.d.ts:14970](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14970)

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

#### Defined in

[ue/ue.d.ts:12480](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12480)

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

#### Defined in

[ue/ue.d.ts:13303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13303)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[ReceiveActorBeginCursorOver](ue_ue.AIController.md#receiveactorbegincursorover)

#### Defined in

[ue/ue.d.ts:13304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13304)

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

#### Defined in

[ue/ue.d.ts:13305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13305)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[ReceiveActorEndCursorOver](ue_ue.AIController.md#receiveactorendcursorover)

#### Defined in

[ue/ue.d.ts:13306](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13306)

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

#### Defined in

[ue/ue.d.ts:13307](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13307)

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

#### Defined in

[ue/ue.d.ts:13308](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13308)

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

#### Defined in

[ue/ue.d.ts:13309](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13309)

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

#### Defined in

[ue/ue.d.ts:13310](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13310)

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

#### Defined in

[ue/ue.d.ts:13311](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13311)

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

#### Defined in

[ue/ue.d.ts:13312](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13312)

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

#### Defined in

[ue/ue.d.ts:13313](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13313)

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

#### Defined in

[ue/ue.d.ts:13314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13314)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[ReceiveBeginPlay](ue_ue.AIController.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:13315](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13315)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[ReceiveDestroyed](ue_ue.AIController.md#receivedestroyed)

#### Defined in

[ue/ue.d.ts:13316](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13316)

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

#### Defined in

[ue/ue.d.ts:13317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13317)

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

#### Defined in

[ue/ue.d.ts:13318](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13318)

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

#### Defined in

[ue/ue.d.ts:12481](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12481)

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

#### Defined in

[ue/ue.d.ts:13319](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13319)

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

#### Defined in

[ue/ue.d.ts:12482](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12482)

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

#### Defined in

[ue/ue.d.ts:13320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13320)

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

#### Defined in

[ue/ue.d.ts:13321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13321)

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

#### Defined in

[ue/ue.d.ts:12483](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12483)

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

#### Defined in

[ue/ue.d.ts:13322](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13322)

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

#### Defined in

[ue/ue.d.ts:13323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13323)

___

### ResetIgnoreInputFlags

▸ **ResetIgnoreInputFlags**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[ResetIgnoreInputFlags](ue_ue.AIController.md#resetignoreinputflags)

#### Defined in

[ue/ue.d.ts:12484](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12484)

___

### ResetIgnoreLookInput

▸ **ResetIgnoreLookInput**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[ResetIgnoreLookInput](ue_ue.AIController.md#resetignorelookinput)

#### Defined in

[ue/ue.d.ts:12485](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12485)

___

### ResetIgnoreMoveInput

▸ **ResetIgnoreMoveInput**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[ResetIgnoreMoveInput](ue_ue.AIController.md#resetignoremoveinput)

#### Defined in

[ue/ue.d.ts:12486](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12486)

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

#### Defined in

[ue/ue.d.ts:14971](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14971)

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

#### Defined in

[ue/ue.d.ts:13324](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13324)

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

#### Defined in

[ue/ue.d.ts:13325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13325)

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

#### Defined in

[ue/ue.d.ts:13326](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13326)

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

#### Defined in

[ue/ue.d.ts:13327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13327)

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

#### Defined in

[ue/ue.d.ts:13328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13328)

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

#### Defined in

[ue/ue.d.ts:13329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13329)

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

#### Defined in

[ue/ue.d.ts:13330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13330)

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

#### Defined in

[ue/ue.d.ts:12487](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12487)

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

#### Defined in

[ue/ue.d.ts:13331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13331)

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

#### Defined in

[ue/ue.d.ts:12488](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12488)

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

#### Defined in

[ue/ue.d.ts:12489](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12489)

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

#### Defined in

[ue/ue.d.ts:12490](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12490)

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

#### Defined in

[ue/ue.d.ts:13332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13332)

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

#### Defined in

[ue/ue.d.ts:13333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13333)

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

#### Defined in

[ue/ue.d.ts:14972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14972)

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

#### Defined in

[ue/ue.d.ts:13334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13334)

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

#### Defined in

[ue/ue.d.ts:13335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13335)

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

#### Defined in

[ue/ue.d.ts:14973](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14973)

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

#### Defined in

[ue/ue.d.ts:13336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13336)

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

#### Defined in

[ue/ue.d.ts:13337](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13337)

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

#### Defined in

[ue/ue.d.ts:13339](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13339)

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

#### Defined in

[ue/ue.d.ts:13338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13338)

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

#### Defined in

[ue/ue.d.ts:13340](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13340)

___

### StopMovement

▸ **StopMovement**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[StopMovement](ue_ue.AIController.md#stopmovement)

#### Defined in

[ue/ue.d.ts:12491](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12491)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[TearOff](ue_ue.AIController.md#tearoff)

#### Defined in

[ue/ue.d.ts:13341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13341)

___

### UnPossess

▸ **UnPossess**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[UnPossess](ue_ue.AIController.md#unpossess)

#### Defined in

[ue/ue.d.ts:12492](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12492)

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

#### Defined in

[ue/ue.d.ts:14974](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14974)

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

#### Defined in

[ue/ue.d.ts:14975](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14975)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[AIController](ue_ue.AIController.md).[UserConstructionScript](ue_ue.AIController.md#userconstructionscript)

#### Defined in

[ue/ue.d.ts:13342](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13342)

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

#### Defined in

[ue/ue.d.ts:13343](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13343)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DetourCrowdAIController`](ue_ue.DetourCrowdAIController.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DetourCrowdAIController`](ue_ue.DetourCrowdAIController.md)

#### Overrides

[AIController](ue_ue.AIController.md).[Find](ue_ue.AIController.md#find)

#### Defined in

[ue/ue.d.ts:30754](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30754)

___

### Load

▸ `Static` **Load**(`InName`): [`DetourCrowdAIController`](ue_ue.DetourCrowdAIController.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DetourCrowdAIController`](ue_ue.DetourCrowdAIController.md)

#### Overrides

[AIController](ue_ue.AIController.md).[Load](ue_ue.AIController.md#load)

#### Defined in

[ue/ue.d.ts:30755](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30755)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AIController](ue_ue.AIController.md).[StaticClass](ue_ue.AIController.md#staticclass)

#### Defined in

[ue/ue.d.ts:30753](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30753)
