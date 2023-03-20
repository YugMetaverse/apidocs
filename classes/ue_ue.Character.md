[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Character

# Class: Character

[ue/ue](../modules/ue_ue.md).Character

## Hierarchy

- [`Pawn`](ue_ue.Pawn.md)

  ↳ **`Character`**

  ↳↳ [`ArchVisCharacter`](ue_ue.ArchVisCharacter.md)

  ↳↳ [`EQSTestingPawn`](ue_ue.EQSTestingPawn.md)

  ↳↳ [`PaperCharacter`](ue_ue.PaperCharacter.md)

## Table of contents

### Constructors

- [constructor](ue_ue.Character.md#constructor)

### Properties

- [AIControllerClass](ue_ue.Character.md#aicontrollerclass)
- [ActorLabel](ue_ue.Character.md#actorlabel)
- [AnimRootMotionTranslationScale](ue_ue.Character.md#animrootmotiontranslationscale)
- [ArrowComponent](ue_ue.Character.md#arrowcomponent)
- [AttachmentReplication](ue_ue.Character.md#attachmentreplication)
- [AutoPossessAI](ue_ue.Character.md#autopossessai)
- [AutoPossessPlayer](ue_ue.Character.md#autopossessplayer)
- [AutoReceiveInput](ue_ue.Character.md#autoreceiveinput)
- [BaseEyeHeight](ue_ue.Character.md#baseeyeheight)
- [BaseRotationOffset](ue_ue.Character.md#baserotationoffset)
- [BaseTranslationOffset](ue_ue.Character.md#basetranslationoffset)
- [BasedMovement](ue_ue.Character.md#basedmovement)
- [BlueprintCreatedComponents](ue_ue.Character.md#blueprintcreatedcomponents)
- [CapsuleComponent](ue_ue.Character.md#capsulecomponent)
- [CharacterMovement](ue_ue.Character.md#charactermovement)
- [Children](ue_ue.Character.md#children)
- [ClientRootMotionParams](ue_ue.Character.md#clientrootmotionparams)
- [ControlInputVector](ue_ue.Character.md#controlinputvector)
- [Controller](ue_ue.Character.md#controller)
- [ControllingMatineeActors](ue_ue.Character.md#controllingmatineeactors)
- [CrouchedEyeHeight](ue_ue.Character.md#crouchedeyeheight)
- [CustomTimeDilation](ue_ue.Character.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.Character.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.Character.md#folderpath)
- [GroupActor](ue_ue.Character.md#groupactor)
- [HiddenEditorViews](ue_ue.Character.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.Character.md#initiallifespan)
- [InputComponent](ue_ue.Character.md#inputcomponent)
- [InputPriority](ue_ue.Character.md#inputpriority)
- [InstanceComponents](ue_ue.Character.md#instancecomponents)
- [Instigator](ue_ue.Character.md#instigator)
- [JumpCurrentCount](ue_ue.Character.md#jumpcurrentcount)
- [JumpForceTimeRemaining](ue_ue.Character.md#jumpforcetimeremaining)
- [JumpKeyHoldTime](ue_ue.Character.md#jumpkeyholdtime)
- [JumpMaxCount](ue_ue.Character.md#jumpmaxcount)
- [JumpMaxHoldTime](ue_ue.Character.md#jumpmaxholdtime)
- [LastControlInputVector](ue_ue.Character.md#lastcontrolinputvector)
- [LastHitBy](ue_ue.Character.md#lasthitby)
- [Layers](ue_ue.Character.md#layers)
- [Mesh](ue_ue.Character.md#mesh)
- [MinNetUpdateFrequency](ue_ue.Character.md#minnetupdatefrequency)
- [MovementModeChangedDelegate](ue_ue.Character.md#movementmodechangeddelegate)
- [NetCullDistanceSquared](ue_ue.Character.md#netculldistancesquared)
- [NetDormancy](ue_ue.Character.md#netdormancy)
- [NetDriverName](ue_ue.Character.md#netdrivername)
- [NetPriority](ue_ue.Character.md#netpriority)
- [NetTag](ue_ue.Character.md#nettag)
- [NetUpdateFrequency](ue_ue.Character.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.Character.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.Character.md#onactorendoverlap)
- [OnActorHit](ue_ue.Character.md#onactorhit)
- [OnBeginCursorOver](ue_ue.Character.md#onbegincursorover)
- [OnCharacterMovementUpdated](ue_ue.Character.md#oncharactermovementupdated)
- [OnClicked](ue_ue.Character.md#onclicked)
- [OnDestroyed](ue_ue.Character.md#ondestroyed)
- [OnEndCursorOver](ue_ue.Character.md#onendcursorover)
- [OnEndPlay](ue_ue.Character.md#onendplay)
- [OnInputTouchBegin](ue_ue.Character.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.Character.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.Character.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.Character.md#oninputtouchleave)
- [OnReachedJumpApex](ue_ue.Character.md#onreachedjumpapex)
- [OnReleased](ue_ue.Character.md#onreleased)
- [OnTakeAnyDamage](ue_ue.Character.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.Character.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.Character.md#ontakeradialdamage)
- [Owner](ue_ue.Character.md#owner)
- [ParentComponent](ue_ue.Character.md#parentcomponent)
- [ParentComponentActor](ue_ue.Character.md#parentcomponentactor)
- [PivotOffset](ue_ue.Character.md#pivotoffset)
- [PlayerState](ue_ue.Character.md#playerstate)
- [PrimaryActorTick](ue_ue.Character.md#primaryactortick)
- [ProxyJumpForceStartedTime](ue_ue.Character.md#proxyjumpforcestartedtime)
- [RemoteRole](ue_ue.Character.md#remoterole)
- [RemoteViewPitch](ue_ue.Character.md#remoteviewpitch)
- [RepRootMotion](ue_ue.Character.md#reprootmotion)
- [ReplayLastTransformUpdateTimeStamp](ue_ue.Character.md#replaylasttransformupdatetimestamp)
- [ReplicatedBasedMovement](ue_ue.Character.md#replicatedbasedmovement)
- [ReplicatedMovement](ue_ue.Character.md#replicatedmovement)
- [ReplicatedMovementMode](ue_ue.Character.md#replicatedmovementmode)
- [ReplicatedServerLastTransformUpdateTimeStamp](ue_ue.Character.md#replicatedserverlasttransformupdatetimestamp)
- [Role](ue_ue.Character.md#role)
- [RootComponent](ue_ue.Character.md#rootcomponent)
- [RootMotionRepMoves](ue_ue.Character.md#rootmotionrepmoves)
- [SavedRootMotion](ue_ue.Character.md#savedrootmotion)
- [SpawnCollisionHandlingMethod](ue_ue.Character.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.Character.md#spritescale)
- [Tags](ue_ue.Character.md#tags)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.Character.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.Character.md#__tid_actor__)
- [\_\_tid\_Character\_\_](ue_ue.Character.md#__tid_character__)
- [\_\_tid\_Object\_\_](ue_ue.Character.md#__tid_object__)
- [\_\_tid\_Pawn\_\_](ue_ue.Character.md#__tid_pawn__)
- [bActorEnableCollision](ue_ue.Character.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.Character.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.Character.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.Character.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.Character.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.Character.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.Character.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.Character.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.Character.md#bblockinput)
- [bCanAffectNavigationGeneration](ue_ue.Character.md#bcanaffectnavigationgeneration)
- [bCanBeDamaged](ue_ue.Character.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.Character.md#bcanbeincluster)
- [bClientCheckEncroachmentOnNetUpdate](ue_ue.Character.md#bclientcheckencroachmentonnetupdate)
- [bClientResimulateRootMotion](ue_ue.Character.md#bclientresimulaterootmotion)
- [bClientResimulateRootMotionSources](ue_ue.Character.md#bclientresimulaterootmotionsources)
- [bClientUpdating](ue_ue.Character.md#bclientupdating)
- [bClientWasFalling](ue_ue.Character.md#bclientwasfalling)
- [bCollideWhenPlacing](ue_ue.Character.md#bcollidewhenplacing)
- [bEditable](ue_ue.Character.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.Character.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.Character.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.Character.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.Character.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.Character.md#bhidden)
- [bHiddenEd](ue_ue.Character.md#bhiddened)
- [bHiddenEdLayer](ue_ue.Character.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.Character.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.Character.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.Character.md#bignoresoriginshifting)
- [bInBaseReplication](ue_ue.Character.md#binbasereplication)
- [bIsCrouched](ue_ue.Character.md#biscrouched)
- [bIsEditorOnlyActor](ue_ue.Character.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.Character.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.Character.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.Character.md#blocklocation)
- [bNetLoadOnClient](ue_ue.Character.md#bnetloadonclient)
- [bNetStartup](ue_ue.Character.md#bnetstartup)
- [bNetTemporary](ue_ue.Character.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.Character.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.Character.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.Character.md#boptimizebpcomponentdata)
- [bPressedJump](ue_ue.Character.md#bpressedjump)
- [bProxyIsJumpForceApplied](ue_ue.Character.md#bproxyisjumpforceapplied)
- [bRelevantForLevelBounds](ue_ue.Character.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.Character.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.Character.md#breplayrewindable)
- [bReplicateMovement](ue_ue.Character.md#breplicatemovement)
- [bReplicates](ue_ue.Character.md#breplicates)
- [bServerMoveIgnoreRootMotion](ue_ue.Character.md#bservermoveignorerootmotion)
- [bSimGravityDisabled](ue_ue.Character.md#bsimgravitydisabled)
- [bTearOff](ue_ue.Character.md#btearoff)
- [bUseControllerRotationPitch](ue_ue.Character.md#busecontrollerrotationpitch)
- [bUseControllerRotationRoll](ue_ue.Character.md#busecontrollerrotationroll)
- [bUseControllerRotationYaw](ue_ue.Character.md#busecontrollerrotationyaw)
- [bWasJumping](ue_ue.Character.md#bwasjumping)

### Methods

- [ActorHasTag](ue_ue.Character.md#actorhastag)
- [AddComponent](ue_ue.Character.md#addcomponent)
- [AddControllerPitchInput](ue_ue.Character.md#addcontrollerpitchinput)
- [AddControllerRollInput](ue_ue.Character.md#addcontrollerrollinput)
- [AddControllerYawInput](ue_ue.Character.md#addcontrolleryawinput)
- [AddMovementInput](ue_ue.Character.md#addmovementinput)
- [AddTickPrerequisiteActor](ue_ue.Character.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.Character.md#addtickprerequisitecomponent)
- [CacheInitialMeshOffset](ue_ue.Character.md#cacheinitialmeshoffset)
- [CanCrouch](ue_ue.Character.md#cancrouch)
- [CanJump](ue_ue.Character.md#canjump)
- [CanJumpInternal](ue_ue.Character.md#canjumpinternal)
- [ClientAckGoodMove](ue_ue.Character.md#clientackgoodmove)
- [ClientAdjustPosition](ue_ue.Character.md#clientadjustposition)
- [ClientAdjustRootMotionPosition](ue_ue.Character.md#clientadjustrootmotionposition)
- [ClientAdjustRootMotionSourcePosition](ue_ue.Character.md#clientadjustrootmotionsourceposition)
- [ClientCheatFly](ue_ue.Character.md#clientcheatfly)
- [ClientCheatGhost](ue_ue.Character.md#clientcheatghost)
- [ClientCheatWalk](ue_ue.Character.md#clientcheatwalk)
- [ClientVeryShortAdjustPosition](ue_ue.Character.md#clientveryshortadjustposition)
- [ConsumeMovementInputVector](ue_ue.Character.md#consumemovementinputvector)
- [CreateDefaultSubobject](ue_ue.Character.md#createdefaultsubobject)
- [Crouch](ue_ue.Character.md#crouch)
- [DetachFromControllerPendingDestroy](ue_ue.Character.md#detachfromcontrollerpendingdestroy)
- [DetachRootComponentFromParent](ue_ue.Character.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.Character.md#disableinput)
- [EnableInput](ue_ue.Character.md#enableinput)
- [ExecuteUbergraph](ue_ue.Character.md#executeubergraph)
- [FlushNetDormancy](ue_ue.Character.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.Character.md#forcenetupdate)
- [GetActorBounds](ue_ue.Character.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.Character.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.Character.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.Character.md#getactorforwardvector)
- [GetActorLabel](ue_ue.Character.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.Character.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.Character.md#getactorrightvector)
- [GetActorScale3D](ue_ue.Character.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.Character.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.Character.md#getactortimedilation)
- [GetActorUpVector](ue_ue.Character.md#getactorupvector)
- [GetAllChildActors](ue_ue.Character.md#getallchildactors)
- [GetAnimRootMotionTranslationScale](ue_ue.Character.md#getanimrootmotiontranslationscale)
- [GetAttachParentActor](ue_ue.Character.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.Character.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.Character.md#getattachedactors)
- [GetBaseAimRotation](ue_ue.Character.md#getbaseaimrotation)
- [GetBaseRotationOffsetRotator](ue_ue.Character.md#getbaserotationoffsetrotator)
- [GetBaseTranslationOffset](ue_ue.Character.md#getbasetranslationoffset)
- [GetClass](ue_ue.Character.md#getclass)
- [GetComponentByClass](ue_ue.Character.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.Character.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.Character.md#getcomponentsbytag)
- [GetControlRotation](ue_ue.Character.md#getcontrolrotation)
- [GetController](ue_ue.Character.md#getcontroller)
- [GetCurrentMontage](ue_ue.Character.md#getcurrentmontage)
- [GetDistanceTo](ue_ue.Character.md#getdistanceto)
- [GetDotProductTo](ue_ue.Character.md#getdotproductto)
- [GetFolderPath](ue_ue.Character.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.Character.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.Character.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.Character.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.Character.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.Character.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.Character.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.Character.md#getinstigator)
- [GetInstigatorController](ue_ue.Character.md#getinstigatorcontroller)
- [GetLastMovementInputVector](ue_ue.Character.md#getlastmovementinputvector)
- [GetLifeSpan](ue_ue.Character.md#getlifespan)
- [GetLocalRole](ue_ue.Character.md#getlocalrole)
- [GetMovementComponent](ue_ue.Character.md#getmovementcomponent)
- [GetName](ue_ue.Character.md#getname)
- [GetNavAgentLocation](ue_ue.Character.md#getnavagentlocation)
- [GetOuter](ue_ue.Character.md#getouter)
- [GetOverlappingActors](ue_ue.Character.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.Character.md#getoverlappingcomponents)
- [GetOwner](ue_ue.Character.md#getowner)
- [GetParentActor](ue_ue.Character.md#getparentactor)
- [GetParentComponent](ue_ue.Character.md#getparentcomponent)
- [GetPendingMovementInputVector](ue_ue.Character.md#getpendingmovementinputvector)
- [GetRemoteRole](ue_ue.Character.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.Character.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.Character.md#gettickablewhenpaused)
- [GetTransform](ue_ue.Character.md#gettransform)
- [GetVelocity](ue_ue.Character.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.Character.md#getverticaldistanceto)
- [GetWorld](ue_ue.Character.md#getworld)
- [HasAnyRootMotion](ue_ue.Character.md#hasanyrootmotion)
- [HasAuthority](ue_ue.Character.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.Character.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.Character.md#isactortickenabled)
- [IsBotControlled](ue_ue.Character.md#isbotcontrolled)
- [IsChildActor](ue_ue.Character.md#ischildactor)
- [IsControlled](ue_ue.Character.md#iscontrolled)
- [IsEditable](ue_ue.Character.md#iseditable)
- [IsHiddenEd](ue_ue.Character.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.Character.md#ishiddenedatstartup)
- [IsJumpProvidingForce](ue_ue.Character.md#isjumpprovidingforce)
- [IsLocallyControlled](ue_ue.Character.md#islocallycontrolled)
- [IsMoveInputIgnored](ue_ue.Character.md#ismoveinputignored)
- [IsOverlappingActor](ue_ue.Character.md#isoverlappingactor)
- [IsPawnControlled](ue_ue.Character.md#ispawncontrolled)
- [IsPlayerControlled](ue_ue.Character.md#isplayercontrolled)
- [IsPlayingNetworkedRootMotionMontage](ue_ue.Character.md#isplayingnetworkedrootmotionmontage)
- [IsPlayingRootMotion](ue_ue.Character.md#isplayingrootmotion)
- [IsSelectable](ue_ue.Character.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.Character.md#istemporarilyhiddenineditor)
- [Jump](ue_ue.Character.md#jump)
- [K2\_AddActorLocalOffset](ue_ue.Character.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.Character.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.Character.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.Character.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.Character.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.Character.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.Character.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.Character.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.Character.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.Character.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.Character.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.Character.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.Character.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.Character.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.Character.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.Character.md#k2_getcomponentsbyclass)
- [K2\_GetMovementInputVector](ue_ue.Character.md#k2_getmovementinputvector)
- [K2\_GetRootComponent](ue_ue.Character.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.Character.md#k2_onbecomeviewtarget)
- [K2\_OnEndCrouch](ue_ue.Character.md#k2_onendcrouch)
- [K2\_OnEndViewTarget](ue_ue.Character.md#k2_onendviewtarget)
- [K2\_OnMovementModeChanged](ue_ue.Character.md#k2_onmovementmodechanged)
- [K2\_OnReset](ue_ue.Character.md#k2_onreset)
- [K2\_OnStartCrouch](ue_ue.Character.md#k2_onstartcrouch)
- [K2\_SetActorLocation](ue_ue.Character.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.Character.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.Character.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.Character.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.Character.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.Character.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.Character.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.Character.md#k2_teleportto)
- [K2\_UpdateCustomMovement](ue_ue.Character.md#k2_updatecustommovement)
- [LaunchCharacter](ue_ue.Character.md#launchcharacter)
- [LaunchPawn](ue_ue.Character.md#launchpawn)
- [MakeMIDForMaterial](ue_ue.Character.md#makemidformaterial)
- [MakeNoise](ue_ue.Character.md#makenoise)
- [OnJumped](ue_ue.Character.md#onjumped)
- [OnLanded](ue_ue.Character.md#onlanded)
- [OnLaunched](ue_ue.Character.md#onlaunched)
- [OnRep\_AttachmentReplication](ue_ue.Character.md#onrep_attachmentreplication)
- [OnRep\_Controller](ue_ue.Character.md#onrep_controller)
- [OnRep\_Instigator](ue_ue.Character.md#onrep_instigator)
- [OnRep\_IsCrouched](ue_ue.Character.md#onrep_iscrouched)
- [OnRep\_Owner](ue_ue.Character.md#onrep_owner)
- [OnRep\_PlayerState](ue_ue.Character.md#onrep_playerstate)
- [OnRep\_ReplayLastTransformUpdateTimeStamp](ue_ue.Character.md#onrep_replaylasttransformupdatetimestamp)
- [OnRep\_ReplicateMovement](ue_ue.Character.md#onrep_replicatemovement)
- [OnRep\_ReplicatedBasedMovement](ue_ue.Character.md#onrep_replicatedbasedmovement)
- [OnRep\_ReplicatedMovement](ue_ue.Character.md#onrep_replicatedmovement)
- [OnRep\_RootMotion](ue_ue.Character.md#onrep_rootmotion)
- [OnWalkingOffLedge](ue_ue.Character.md#onwalkingoffledge)
- [PawnMakeNoise](ue_ue.Character.md#pawnmakenoise)
- [PlayAnimMontage](ue_ue.Character.md#playanimmontage)
- [PrestreamTextures](ue_ue.Character.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.Character.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.Character.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.Character.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.Character.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.Character.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.Character.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.Character.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.Character.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.Character.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.Character.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.Character.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.Character.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.Character.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.Character.md#receiveendplay)
- [ReceiveHit](ue_ue.Character.md#receivehit)
- [ReceivePointDamage](ue_ue.Character.md#receivepointdamage)
- [ReceivePossessed](ue_ue.Character.md#receivepossessed)
- [ReceiveRadialDamage](ue_ue.Character.md#receiveradialdamage)
- [ReceiveTick](ue_ue.Character.md#receivetick)
- [ReceiveUnpossessed](ue_ue.Character.md#receiveunpossessed)
- [RemoveTickPrerequisiteActor](ue_ue.Character.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.Character.md#removetickprerequisitecomponent)
- [RootMotionDebugClientPrintOnScreen](ue_ue.Character.md#rootmotiondebugclientprintonscreen)
- [ServerMove](ue_ue.Character.md#servermove)
- [ServerMoveDual](ue_ue.Character.md#servermovedual)
- [ServerMoveDualHybridRootMotion](ue_ue.Character.md#servermovedualhybridrootmotion)
- [ServerMoveDualNoBase](ue_ue.Character.md#servermovedualnobase)
- [ServerMoveNoBase](ue_ue.Character.md#servermovenobase)
- [ServerMoveOld](ue_ue.Character.md#servermoveold)
- [SetActorEnableCollision](ue_ue.Character.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.Character.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.Character.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.Character.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.Character.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.Character.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.Character.md#setactortickinterval)
- [SetCanAffectNavigationGeneration](ue_ue.Character.md#setcanaffectnavigationgeneration)
- [SetFolderPath](ue_ue.Character.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.Character.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.Character.md#setlifespan)
- [SetNetDormancy](ue_ue.Character.md#setnetdormancy)
- [SetOwner](ue_ue.Character.md#setowner)
- [SetReplicateMovement](ue_ue.Character.md#setreplicatemovement)
- [SetReplicates](ue_ue.Character.md#setreplicates)
- [SetTickGroup](ue_ue.Character.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.Character.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.Character.md#snaprootcomponentto)
- [SpawnDefaultController](ue_ue.Character.md#spawndefaultcontroller)
- [StopAnimMontage](ue_ue.Character.md#stopanimmontage)
- [StopJumping](ue_ue.Character.md#stopjumping)
- [TearOff](ue_ue.Character.md#tearoff)
- [UnCrouch](ue_ue.Character.md#uncrouch)
- [UserConstructionScript](ue_ue.Character.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.Character.md#wasrecentlyrendered)
- [Find](ue_ue.Character.md#find)
- [GetMovementBaseActor](ue_ue.Character.md#getmovementbaseactor)
- [Load](ue_ue.Character.md#load)
- [StaticClass](ue_ue.Character.md#staticclass)

## Constructors

### constructor

• **new Character**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Pawn](ue_ue.Pawn.md).[constructor](ue_ue.Pawn.md#constructor)

#### Defined in

[ue/ue.d.ts:5945](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5945)

## Properties

### AIControllerClass

• **AIControllerClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[AIControllerClass](ue_ue.Pawn.md#aicontrollerclass)

#### Defined in

[ue/ue.d.ts:12510](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12510)

___

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ActorLabel](ue_ue.Pawn.md#actorlabel)

#### Defined in

[ue/ue.d.ts:13176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13176)

___

### AnimRootMotionTranslationScale

• **AnimRootMotionTranslationScale**: `number`

#### Defined in

[ue/ue.d.ts:5952](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5952)

___

### ArrowComponent

• **ArrowComponent**: [`ArrowComponent`](ue_ue.ArrowComponent.md)

#### Defined in

[ue/ue.d.ts:5949](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5949)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[AttachmentReplication](ue_ue.Pawn.md#attachmentreplication)

#### Defined in

[ue/ue.d.ts:13151](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13151)

___

### AutoPossessAI

• **AutoPossessAI**: [`EAutoPossessAI`](../enums/ue_ue.EAutoPossessAI.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[AutoPossessAI](ue_ue.Pawn.md#autopossessai)

#### Defined in

[ue/ue.d.ts:12508](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12508)

___

### AutoPossessPlayer

• **AutoPossessPlayer**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[AutoPossessPlayer](ue_ue.Pawn.md#autopossessplayer)

#### Defined in

[ue/ue.d.ts:12507](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12507)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[AutoReceiveInput](ue_ue.Pawn.md#autoreceiveinput)

#### Defined in

[ue/ue.d.ts:13157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13157)

___

### BaseEyeHeight

• **BaseEyeHeight**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[BaseEyeHeight](ue_ue.Pawn.md#baseeyeheight)

#### Defined in

[ue/ue.d.ts:12506](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12506)

___

### BaseRotationOffset

• **BaseRotationOffset**: [`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue.d.ts:5954](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5954)

___

### BaseTranslationOffset

• **BaseTranslationOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5953](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5953)

___

### BasedMovement

• **BasedMovement**: [`BasedMovementInfo`](ue_ue.BasedMovementInfo.md)

#### Defined in

[ue/ue.d.ts:5950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5950)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[BlueprintCreatedComponents](ue_ue.Pawn.md#blueprintcreatedcomponents)

#### Defined in

[ue/ue.d.ts:13206](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13206)

___

### CapsuleComponent

• **CapsuleComponent**: [`CapsuleComponent`](ue_ue.CapsuleComponent.md)

#### Defined in

[ue/ue.d.ts:5948](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5948)

___

### CharacterMovement

• **CharacterMovement**: [`CharacterMovementComponent`](ue_ue.CharacterMovementComponent.md)

#### Defined in

[ue/ue.d.ts:5947](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5947)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[Children](ue_ue.Pawn.md#children)

#### Defined in

[ue/ue.d.ts:13166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13166)

___

### ClientRootMotionParams

• **ClientRootMotionParams**: [`RootMotionMovementParams`](ue_ue.RootMotionMovementParams.md)

#### Defined in

[ue/ue.d.ts:5981](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5981)

___

### ControlInputVector

• **ControlInputVector**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ControlInputVector](ue_ue.Pawn.md#controlinputvector)

#### Defined in

[ue/ue.d.ts:12514](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12514)

___

### Controller

• **Controller**: [`Controller`](ue_ue.Controller.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[Controller](ue_ue.Pawn.md#controller)

#### Defined in

[ue/ue.d.ts:12513](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12513)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ControllingMatineeActors](ue_ue.Pawn.md#controllingmatineeactors)

#### Defined in

[ue/ue.d.ts:13169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13169)

___

### CrouchedEyeHeight

• **CrouchedEyeHeight**: `number`

#### Defined in

[ue/ue.d.ts:5959](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5959)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[CustomTimeDilation](ue_ue.Pawn.md#customtimedilation)

#### Defined in

[ue/ue.d.ts:13150](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13150)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.Pawn.md#defaultupdateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13146](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13146)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[FolderPath](ue_ue.Pawn.md#folderpath)

#### Defined in

[ue/ue.d.ts:13177](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13177)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GroupActor](ue_ue.Pawn.md#groupactor)

#### Defined in

[ue/ue.d.ts:13173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13173)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[HiddenEditorViews](ue_ue.Pawn.md#hiddeneditorviews)

#### Defined in

[ue/ue.d.ts:13175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13175)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[InitialLifeSpan](ue_ue.Pawn.md#initiallifespan)

#### Defined in

[ue/ue.d.ts:13149](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13149)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[InputComponent](ue_ue.Pawn.md#inputcomponent)

#### Defined in

[ue/ue.d.ts:13159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13159)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[InputPriority](ue_ue.Pawn.md#inputpriority)

#### Defined in

[ue/ue.d.ts:13158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13158)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[InstanceComponents](ue_ue.Pawn.md#instancecomponents)

#### Defined in

[ue/ue.d.ts:13205](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13205)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[Instigator](ue_ue.Pawn.md#instigator)

#### Defined in

[ue/ue.d.ts:13165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13165)

___

### JumpCurrentCount

• **JumpCurrentCount**: `number`

#### Defined in

[ue/ue.d.ts:5976](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5976)

___

### JumpForceTimeRemaining

• **JumpForceTimeRemaining**: `number`

#### Defined in

[ue/ue.d.ts:5972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5972)

___

### JumpKeyHoldTime

• **JumpKeyHoldTime**: `number`

#### Defined in

[ue/ue.d.ts:5971](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5971)

___

### JumpMaxCount

• **JumpMaxCount**: `number`

#### Defined in

[ue/ue.d.ts:5975](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5975)

___

### JumpMaxHoldTime

• **JumpMaxHoldTime**: `number`

#### Defined in

[ue/ue.d.ts:5974](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5974)

___

### LastControlInputVector

• **LastControlInputVector**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[LastControlInputVector](ue_ue.Pawn.md#lastcontrolinputvector)

#### Defined in

[ue/ue.d.ts:12515](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12515)

___

### LastHitBy

• **LastHitBy**: [`Controller`](ue_ue.Controller.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[LastHitBy](ue_ue.Pawn.md#lasthitby)

#### Defined in

[ue/ue.d.ts:12512](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12512)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[Layers](ue_ue.Pawn.md#layers)

#### Defined in

[ue/ue.d.ts:13170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13170)

___

### Mesh

• **Mesh**: [`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)

#### Defined in

[ue/ue.d.ts:5946](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5946)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[MinNetUpdateFrequency](ue_ue.Pawn.md#minnetupdatefrequency)

#### Defined in

[ue/ue.d.ts:13163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13163)

___

### MovementModeChangedDelegate

• **MovementModeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Character`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Character`](ue_ue.Character.md)\>, `PrevMovementMode`: [`EMovementMode`](../enums/ue_ue.EMovementMode.md), `PreviousCustomMode`: `number`) => `void`\>

#### Defined in

[ue/ue.d.ts:5978](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5978)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[NetCullDistanceSquared](ue_ue.Pawn.md#netculldistancesquared)

#### Defined in

[ue/ue.d.ts:13160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13160)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[NetDormancy](ue_ue.Pawn.md#netdormancy)

#### Defined in

[ue/ue.d.ts:13155](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13155)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[NetDriverName](ue_ue.Pawn.md#netdrivername)

#### Defined in

[ue/ue.d.ts:13153](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13153)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[NetPriority](ue_ue.Pawn.md#netpriority)

#### Defined in

[ue/ue.d.ts:13164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13164)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[NetTag](ue_ue.Pawn.md#nettag)

#### Defined in

[ue/ue.d.ts:13161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13161)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[NetUpdateFrequency](ue_ue.Pawn.md#netupdatefrequency)

#### Defined in

[ue/ue.d.ts:13162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13162)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnActorBeginOverlap](ue_ue.Pawn.md#onactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13192](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13192)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnActorEndOverlap](ue_ue.Pawn.md#onactorendoverlap)

#### Defined in

[ue/ue.d.ts:13193](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13193)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnActorHit](ue_ue.Pawn.md#onactorhit)

#### Defined in

[ue/ue.d.ts:13202](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13202)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnBeginCursorOver](ue_ue.Pawn.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:13194](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13194)

___

### OnCharacterMovementUpdated

• **OnCharacterMovementUpdated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DeltaSeconds`: `number`, `OldLocation`: [`Vector`](ue_ue_s.Vector.md), `OldVelocity`: [`Vector`](ue_ue_s.Vector.md)) => `void`\>

#### Defined in

[ue/ue.d.ts:5979](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5979)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnClicked](ue_ue.Pawn.md#onclicked)

#### Defined in

[ue/ue.d.ts:13196](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13196)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnDestroyed](ue_ue.Pawn.md#ondestroyed)

#### Defined in

[ue/ue.d.ts:13203](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13203)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnEndCursorOver](ue_ue.Pawn.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:13195](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13195)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnEndPlay](ue_ue.Pawn.md#onendplay)

#### Defined in

[ue/ue.d.ts:13204](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13204)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnInputTouchBegin](ue_ue.Pawn.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13198](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13198)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnInputTouchEnd](ue_ue.Pawn.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:13199](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13199)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnInputTouchEnter](ue_ue.Pawn.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:13200](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13200)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnInputTouchLeave](ue_ue.Pawn.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:13201](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13201)

___

### OnReachedJumpApex

• **OnReachedJumpApex**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:5977](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5977)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnReleased](ue_ue.Pawn.md#onreleased)

#### Defined in

[ue/ue.d.ts:13197](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13197)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnTakeAnyDamage](ue_ue.Pawn.md#ontakeanydamage)

#### Defined in

[ue/ue.d.ts:13189](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13189)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnTakePointDamage](ue_ue.Pawn.md#ontakepointdamage)

#### Defined in

[ue/ue.d.ts:13190](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13190)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnTakeRadialDamage](ue_ue.Pawn.md#ontakeradialdamage)

#### Defined in

[ue/ue.d.ts:13191](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13191)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[Owner](ue_ue.Pawn.md#owner)

#### Defined in

[ue/ue.d.ts:13152](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13152)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ParentComponent](ue_ue.Pawn.md#parentcomponent)

#### Defined in

[ue/ue.d.ts:13172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13172)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ParentComponentActor](ue_ue.Pawn.md#parentcomponentactor)

#### Defined in

[ue/ue.d.ts:13171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13171)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[PivotOffset](ue_ue.Pawn.md#pivotoffset)

#### Defined in

[ue/ue.d.ts:13168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13168)

___

### PlayerState

• **PlayerState**: [`PlayerState`](ue_ue.PlayerState.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[PlayerState](ue_ue.Pawn.md#playerstate)

#### Defined in

[ue/ue.d.ts:12511](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12511)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[PrimaryActorTick](ue_ue.Pawn.md#primaryactortick)

#### Defined in

[ue/ue.d.ts:13115](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13115)

___

### ProxyJumpForceStartedTime

• **ProxyJumpForceStartedTime**: `number`

#### Defined in

[ue/ue.d.ts:5973](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5973)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[RemoteRole](ue_ue.Pawn.md#remoterole)

#### Defined in

[ue/ue.d.ts:13147](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13147)

___

### RemoteViewPitch

• **RemoteViewPitch**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[RemoteViewPitch](ue_ue.Pawn.md#remoteviewpitch)

#### Defined in

[ue/ue.d.ts:12509](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12509)

___

### RepRootMotion

• **RepRootMotion**: [`RepRootMotionMontage`](ue_ue.RepRootMotionMontage.md)

#### Defined in

[ue/ue.d.ts:5983](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5983)

___

### ReplayLastTransformUpdateTimeStamp

• **ReplayLastTransformUpdateTimeStamp**: `number`

#### Defined in

[ue/ue.d.ts:5956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5956)

___

### ReplicatedBasedMovement

• **ReplicatedBasedMovement**: [`BasedMovementInfo`](ue_ue.BasedMovementInfo.md)

#### Defined in

[ue/ue.d.ts:5951](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5951)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ReplicatedMovement](ue_ue.Pawn.md#replicatedmovement)

#### Defined in

[ue/ue.d.ts:13148](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13148)

___

### ReplicatedMovementMode

• **ReplicatedMovementMode**: `number`

#### Defined in

[ue/ue.d.ts:5957](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5957)

___

### ReplicatedServerLastTransformUpdateTimeStamp

• **ReplicatedServerLastTransformUpdateTimeStamp**: `number`

#### Defined in

[ue/ue.d.ts:5955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5955)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[Role](ue_ue.Pawn.md#role)

#### Defined in

[ue/ue.d.ts:13154](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13154)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[RootComponent](ue_ue.Pawn.md#rootcomponent)

#### Defined in

[ue/ue.d.ts:13167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13167)

___

### RootMotionRepMoves

• **RootMotionRepMoves**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimulatedRootMotionReplicatedMove`](ue_ue.SimulatedRootMotionReplicatedMove.md)\>

#### Defined in

[ue/ue.d.ts:5982](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5982)

___

### SavedRootMotion

• **SavedRootMotion**: [`RootMotionSourceGroup`](ue_ue.RootMotionSourceGroup.md)

#### Defined in

[ue/ue.d.ts:5980](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5980)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[SpawnCollisionHandlingMethod](ue_ue.Pawn.md#spawncollisionhandlingmethod)

#### Defined in

[ue/ue.d.ts:13156](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13156)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[SpriteScale](ue_ue.Pawn.md#spritescale)

#### Defined in

[ue/ue.d.ts:13174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13174)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Pawn](ue_ue.Pawn.md).[Tags](ue_ue.Pawn.md#tags)

#### Defined in

[ue/ue.d.ts:13188](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13188)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.Pawn.md#updateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13145](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13145)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[__tid_Actor__](ue_ue.Pawn.md#__tid_actor__)

#### Defined in

[ue/ue.d.ts:13348](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13348)

___

### \_\_tid\_Character\_\_

• **\_\_tid\_Character\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:6034](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6034)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[__tid_Object__](ue_ue.Pawn.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_Pawn\_\_

• **\_\_tid\_Pawn\_\_**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[__tid_Pawn__](ue_ue.Pawn.md#__tid_pawn__)

#### Defined in

[ue/ue.d.ts:12549](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12549)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bActorEnableCollision](ue_ue.Pawn.md#bactorenablecollision)

#### Defined in

[ue/ue.d.ts:13143](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13143)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bActorIsBeingDestroyed](ue_ue.Pawn.md#bactorisbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13144](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13144)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bActorLabelEditable](ue_ue.Pawn.md#bactorlabeleditable)

#### Defined in

[ue/ue.d.ts:13183](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13183)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bActorSeamlessTraveled](ue_ue.Pawn.md#bactorseamlesstraveled)

#### Defined in

[ue/ue.d.ts:13139](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13139)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.Pawn.md#ballowreceivetickeventondedicatedserver)

#### Defined in

[ue/ue.d.ts:13142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13142)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bAllowTickBeforeBeginPlay](ue_ue.Pawn.md#ballowtickbeforebeginplay)

#### Defined in

[ue/ue.d.ts:13129](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13129)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bAlwaysRelevant](ue_ue.Pawn.md#balwaysrelevant)

#### Defined in

[ue/ue.d.ts:13120](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13120)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bAutoDestroyWhenFinished](ue_ue.Pawn.md#bautodestroywhenfinished)

#### Defined in

[ue/ue.d.ts:13130](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13130)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bBlockInput](ue_ue.Pawn.md#bblockinput)

#### Defined in

[ue/ue.d.ts:13131](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13131)

___

### bCanAffectNavigationGeneration

• **bCanAffectNavigationGeneration**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bCanAffectNavigationGeneration](ue_ue.Pawn.md#bcanaffectnavigationgeneration)

#### Defined in

[ue/ue.d.ts:12505](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12505)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bCanBeDamaged](ue_ue.Pawn.md#bcanbedamaged)

#### Defined in

[ue/ue.d.ts:13132](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13132)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bCanBeInCluster](ue_ue.Pawn.md#bcanbeincluster)

#### Defined in

[ue/ue.d.ts:13141](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13141)

___

### bClientCheckEncroachmentOnNetUpdate

• **bClientCheckEncroachmentOnNetUpdate**: `boolean`

#### Defined in

[ue/ue.d.ts:5968](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5968)

___

### bClientResimulateRootMotion

• **bClientResimulateRootMotion**: `boolean`

#### Defined in

[ue/ue.d.ts:5965](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5965)

___

### bClientResimulateRootMotionSources

• **bClientResimulateRootMotionSources**: `boolean`

#### Defined in

[ue/ue.d.ts:5966](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5966)

___

### bClientUpdating

• **bClientUpdating**: `boolean`

#### Defined in

[ue/ue.d.ts:5963](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5963)

___

### bClientWasFalling

• **bClientWasFalling**: `boolean`

#### Defined in

[ue/ue.d.ts:5964](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5964)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bCollideWhenPlacing](ue_ue.Pawn.md#bcollidewhenplacing)

#### Defined in

[ue/ue.d.ts:13133](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13133)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bEditable](ue_ue.Pawn.md#beditable)

#### Defined in

[ue/ue.d.ts:13184](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13184)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bEnableAutoLODGeneration](ue_ue.Pawn.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:13137](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13137)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bExchangedRoles](ue_ue.Pawn.md#bexchangedroles)

#### Defined in

[ue/ue.d.ts:13123](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13123)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bFindCameraComponentWhenViewTarget](ue_ue.Pawn.md#bfindcameracomponentwhenviewtarget)

#### Defined in

[ue/ue.d.ts:13134](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13134)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.Pawn.md#bgenerateoverlapeventsduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13135](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13135)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bHidden](ue_ue.Pawn.md#bhidden)

#### Defined in

[ue/ue.d.ts:13116](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13116)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bHiddenEd](ue_ue.Pawn.md#bhiddened)

#### Defined in

[ue/ue.d.ts:13178](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13178)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bHiddenEdLayer](ue_ue.Pawn.md#bhiddenedlayer)

#### Defined in

[ue/ue.d.ts:13180](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13180)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bHiddenEdLevel](ue_ue.Pawn.md#bhiddenedlevel)

#### Defined in

[ue/ue.d.ts:13181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13181)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bHiddenEdTemporary](ue_ue.Pawn.md#bhiddenedtemporary)

#### Defined in

[ue/ue.d.ts:13187](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13187)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bIgnoresOriginShifting](ue_ue.Pawn.md#bignoresoriginshifting)

#### Defined in

[ue/ue.d.ts:13136](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13136)

___

### bInBaseReplication

• **bInBaseReplication**: `boolean`

#### Defined in

[ue/ue.d.ts:5958](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5958)

___

### bIsCrouched

• **bIsCrouched**: `boolean`

#### Defined in

[ue/ue.d.ts:5960](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5960)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bIsEditorOnlyActor](ue_ue.Pawn.md#biseditoronlyactor)

#### Defined in

[ue/ue.d.ts:13138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13138)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bIsEditorPreviewActor](ue_ue.Pawn.md#biseditorpreviewactor)

#### Defined in

[ue/ue.d.ts:13179](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13179)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bListedInSceneOutliner](ue_ue.Pawn.md#blistedinsceneoutliner)

#### Defined in

[ue/ue.d.ts:13185](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13185)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bLockLocation](ue_ue.Pawn.md#blocklocation)

#### Defined in

[ue/ue.d.ts:13182](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13182)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bNetLoadOnClient](ue_ue.Pawn.md#bnetloadonclient)

#### Defined in

[ue/ue.d.ts:13124](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13124)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bNetStartup](ue_ue.Pawn.md#bnetstartup)

#### Defined in

[ue/ue.d.ts:13118](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13118)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bNetTemporary](ue_ue.Pawn.md#bnettemporary)

#### Defined in

[ue/ue.d.ts:13117](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13117)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bNetUseOwnerRelevancy](ue_ue.Pawn.md#bnetuseownerrelevancy)

#### Defined in

[ue/ue.d.ts:13125](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13125)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bOnlyRelevantToOwner](ue_ue.Pawn.md#bonlyrelevanttoowner)

#### Defined in

[ue/ue.d.ts:13119](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13119)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bOptimizeBPComponentData](ue_ue.Pawn.md#boptimizebpcomponentdata)

#### Defined in

[ue/ue.d.ts:13186](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13186)

___

### bPressedJump

• **bPressedJump**: `boolean`

#### Defined in

[ue/ue.d.ts:5962](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5962)

___

### bProxyIsJumpForceApplied

• **bProxyIsJumpForceApplied**: `boolean`

#### Defined in

[ue/ue.d.ts:5961](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5961)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bRelevantForLevelBounds](ue_ue.Pawn.md#brelevantforlevelbounds)

#### Defined in

[ue/ue.d.ts:13127](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13127)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bRelevantForNetworkReplays](ue_ue.Pawn.md#brelevantfornetworkreplays)

#### Defined in

[ue/ue.d.ts:13126](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13126)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bReplayRewindable](ue_ue.Pawn.md#breplayrewindable)

#### Defined in

[ue/ue.d.ts:13128](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13128)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bReplicateMovement](ue_ue.Pawn.md#breplicatemovement)

#### Defined in

[ue/ue.d.ts:13121](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13121)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bReplicates](ue_ue.Pawn.md#breplicates)

#### Defined in

[ue/ue.d.ts:13140](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13140)

___

### bServerMoveIgnoreRootMotion

• **bServerMoveIgnoreRootMotion**: `boolean`

#### Defined in

[ue/ue.d.ts:5969](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5969)

___

### bSimGravityDisabled

• **bSimGravityDisabled**: `boolean`

#### Defined in

[ue/ue.d.ts:5967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5967)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bTearOff](ue_ue.Pawn.md#btearoff)

#### Defined in

[ue/ue.d.ts:13122](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13122)

___

### bUseControllerRotationPitch

• **bUseControllerRotationPitch**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bUseControllerRotationPitch](ue_ue.Pawn.md#busecontrollerrotationpitch)

#### Defined in

[ue/ue.d.ts:12502](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12502)

___

### bUseControllerRotationRoll

• **bUseControllerRotationRoll**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bUseControllerRotationRoll](ue_ue.Pawn.md#busecontrollerrotationroll)

#### Defined in

[ue/ue.d.ts:12504](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12504)

___

### bUseControllerRotationYaw

• **bUseControllerRotationYaw**: `boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[bUseControllerRotationYaw](ue_ue.Pawn.md#busecontrollerrotationyaw)

#### Defined in

[ue/ue.d.ts:12503](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12503)

___

### bWasJumping

• **bWasJumping**: `boolean`

#### Defined in

[ue/ue.d.ts:5970](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5970)

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

[Pawn](ue_ue.Pawn.md).[AddComponent](ue_ue.Pawn.md#addcomponent)

#### Defined in

[ue/ue.d.ts:13208](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13208)

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

#### Defined in

[ue/ue.d.ts:12516](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12516)

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

#### Defined in

[ue/ue.d.ts:12517](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12517)

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

#### Defined in

[ue/ue.d.ts:12518](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12518)

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

#### Defined in

[ue/ue.d.ts:12519](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12519)

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

[Pawn](ue_ue.Pawn.md).[AddTickPrerequisiteComponent](ue_ue.Pawn.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13210](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13210)

___

### CacheInitialMeshOffset

▸ **CacheInitialMeshOffset**(`MeshRelativeLocation`, `MeshRelativeRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MeshRelativeLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `MeshRelativeRotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:5984](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5984)

___

### CanCrouch

▸ **CanCrouch**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:5985](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5985)

___

### CanJump

▸ **CanJump**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:5986](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5986)

___

### CanJumpInternal

▸ **CanJumpInternal**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:5987](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5987)

___

### ClientAckGoodMove

▸ **ClientAckGoodMove**(`TimeStamp`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeStamp` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:5988](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5988)

___

### ClientAdjustPosition

▸ **ClientAdjustPosition**(`TimeStamp`, `NewLoc`, `NewVel`, `NewBase`, `NewBaseBoneName`, `bHasBase`, `bBaseRelativePosition`, `ServerMovementMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeStamp` | `number` |
| `NewLoc` | [`Vector`](ue_ue_s.Vector.md) |
| `NewVel` | [`Vector`](ue_ue_s.Vector.md) |
| `NewBase` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `NewBaseBoneName` | `string` |
| `bHasBase` | `boolean` |
| `bBaseRelativePosition` | `boolean` |
| `ServerMovementMode` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:5989](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5989)

___

### ClientAdjustRootMotionPosition

▸ **ClientAdjustRootMotionPosition**(`TimeStamp`, `ServerMontageTrackPosition`, `ServerLoc`, `ServerRotation`, `ServerVelZ`, `ServerBase`, `ServerBoneName`, `bHasBase`, `bBaseRelativePosition`, `ServerMovementMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeStamp` | `number` |
| `ServerMontageTrackPosition` | `number` |
| `ServerLoc` | [`Vector`](ue_ue_s.Vector.md) |
| `ServerRotation` | [`Vector_NetQuantizeNormal`](ue_ue.Vector_NetQuantizeNormal.md) |
| `ServerVelZ` | `number` |
| `ServerBase` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `ServerBoneName` | `string` |
| `bHasBase` | `boolean` |
| `bBaseRelativePosition` | `boolean` |
| `ServerMovementMode` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:5990](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5990)

___

### ClientAdjustRootMotionSourcePosition

▸ **ClientAdjustRootMotionSourcePosition**(`TimeStamp`, `ServerRootMotion`, `bHasAnimRootMotion`, `ServerMontageTrackPosition`, `ServerLoc`, `ServerRotation`, `ServerVelZ`, `ServerBase`, `ServerBoneName`, `bHasBase`, `bBaseRelativePosition`, `ServerMovementMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeStamp` | `number` |
| `ServerRootMotion` | [`RootMotionSourceGroup`](ue_ue.RootMotionSourceGroup.md) |
| `bHasAnimRootMotion` | `boolean` |
| `ServerMontageTrackPosition` | `number` |
| `ServerLoc` | [`Vector`](ue_ue_s.Vector.md) |
| `ServerRotation` | [`Vector_NetQuantizeNormal`](ue_ue.Vector_NetQuantizeNormal.md) |
| `ServerVelZ` | `number` |
| `ServerBase` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `ServerBoneName` | `string` |
| `bHasBase` | `boolean` |
| `bBaseRelativePosition` | `boolean` |
| `ServerMovementMode` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:5991](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5991)

___

### ClientCheatFly

▸ **ClientCheatFly**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:5992](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5992)

___

### ClientCheatGhost

▸ **ClientCheatGhost**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:5993](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5993)

___

### ClientCheatWalk

▸ **ClientCheatWalk**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:5994](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5994)

___

### ClientVeryShortAdjustPosition

▸ **ClientVeryShortAdjustPosition**(`TimeStamp`, `NewLoc`, `NewBase`, `NewBaseBoneName`, `bHasBase`, `bBaseRelativePosition`, `ServerMovementMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeStamp` | `number` |
| `NewLoc` | [`Vector`](ue_ue_s.Vector.md) |
| `NewBase` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `NewBaseBoneName` | `string` |
| `bHasBase` | `boolean` |
| `bBaseRelativePosition` | `boolean` |
| `ServerMovementMode` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:5995](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5995)

___

### ConsumeMovementInputVector

▸ **ConsumeMovementInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ConsumeMovementInputVector](ue_ue.Pawn.md#consumemovementinputvector)

#### Defined in

[ue/ue.d.ts:12520](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12520)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### Crouch

▸ **Crouch**(`bClientSimulation?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bClientSimulation?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:5996](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5996)

___

### DetachFromControllerPendingDestroy

▸ **DetachFromControllerPendingDestroy**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[DetachFromControllerPendingDestroy](ue_ue.Pawn.md#detachfromcontrollerpendingdestroy)

#### Defined in

[ue/ue.d.ts:12521](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12521)

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

[Pawn](ue_ue.Pawn.md).[DisableInput](ue_ue.Pawn.md#disableinput)

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

[Pawn](ue_ue.Pawn.md).[EnableInput](ue_ue.Pawn.md#enableinput)

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

[Pawn](ue_ue.Pawn.md).[ExecuteUbergraph](ue_ue.Pawn.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[FlushNetDormancy](ue_ue.Pawn.md#flushnetdormancy)

#### Defined in

[ue/ue.d.ts:13214](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13214)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ForceNetUpdate](ue_ue.Pawn.md#forcenetupdate)

#### Defined in

[ue/ue.d.ts:13215](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13215)

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

#### Defined in

[ue/ue.d.ts:13216](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13216)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorEnableCollision](ue_ue.Pawn.md#getactorenablecollision)

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

[Pawn](ue_ue.Pawn.md).[GetActorEyesViewPoint](ue_ue.Pawn.md#getactoreyesviewpoint)

#### Defined in

[ue/ue.d.ts:13218](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13218)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorForwardVector](ue_ue.Pawn.md#getactorforwardvector)

#### Defined in

[ue/ue.d.ts:13219](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13219)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorLabel](ue_ue.Pawn.md#getactorlabel)

#### Defined in

[ue/ue.d.ts:13220](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13220)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorRelativeScale3D](ue_ue.Pawn.md#getactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13221](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13221)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorRightVector](ue_ue.Pawn.md#getactorrightvector)

#### Defined in

[ue/ue.d.ts:13222](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13222)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorScale3D](ue_ue.Pawn.md#getactorscale3d)

#### Defined in

[ue/ue.d.ts:13223](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13223)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorTickInterval](ue_ue.Pawn.md#getactortickinterval)

#### Defined in

[ue/ue.d.ts:13224](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13224)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorTimeDilation](ue_ue.Pawn.md#getactortimedilation)

#### Defined in

[ue/ue.d.ts:13225](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13225)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetActorUpVector](ue_ue.Pawn.md#getactorupvector)

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

[Pawn](ue_ue.Pawn.md).[GetAllChildActors](ue_ue.Pawn.md#getallchildactors)

#### Defined in

[ue/ue.d.ts:13227](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13227)

___

### GetAnimRootMotionTranslationScale

▸ **GetAnimRootMotionTranslationScale**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:5997](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5997)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetAttachParentActor](ue_ue.Pawn.md#getattachparentactor)

#### Defined in

[ue/ue.d.ts:13229](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13229)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetAttachParentSocketName](ue_ue.Pawn.md#getattachparentsocketname)

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

[Pawn](ue_ue.Pawn.md).[GetAttachedActors](ue_ue.Pawn.md#getattachedactors)

#### Defined in

[ue/ue.d.ts:13228](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13228)

___

### GetBaseAimRotation

▸ **GetBaseAimRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetBaseAimRotation](ue_ue.Pawn.md#getbaseaimrotation)

#### Defined in

[ue/ue.d.ts:12522](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12522)

___

### GetBaseRotationOffsetRotator

▸ **GetBaseRotationOffsetRotator**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:5998](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5998)

___

### GetBaseTranslationOffset

▸ **GetBaseTranslationOffset**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5999](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5999)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetClass](ue_ue.Pawn.md#getclass)

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

[Pawn](ue_ue.Pawn.md).[GetComponentByClass](ue_ue.Pawn.md#getcomponentbyclass)

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

[Pawn](ue_ue.Pawn.md).[GetComponentsByInterface](ue_ue.Pawn.md#getcomponentsbyinterface)

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

[Pawn](ue_ue.Pawn.md).[GetComponentsByTag](ue_ue.Pawn.md#getcomponentsbytag)

#### Defined in

[ue/ue.d.ts:13233](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13233)

___

### GetControlRotation

▸ **GetControlRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetControlRotation](ue_ue.Pawn.md#getcontrolrotation)

#### Defined in

[ue/ue.d.ts:12524](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12524)

___

### GetController

▸ **GetController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetController](ue_ue.Pawn.md#getcontroller)

#### Defined in

[ue/ue.d.ts:12523](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12523)

___

### GetCurrentMontage

▸ **GetCurrentMontage**(): [`AnimMontage`](ue_ue.AnimMontage.md)

#### Returns

[`AnimMontage`](ue_ue.AnimMontage.md)

#### Defined in

[ue/ue.d.ts:6000](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6000)

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

[Pawn](ue_ue.Pawn.md).[GetDotProductTo](ue_ue.Pawn.md#getdotproductto)

#### Defined in

[ue/ue.d.ts:13235](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13235)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetFolderPath](ue_ue.Pawn.md#getfolderpath)

#### Defined in

[ue/ue.d.ts:13236](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13236)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetGameTimeSinceCreation](ue_ue.Pawn.md#getgametimesincecreation)

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

[Pawn](ue_ue.Pawn.md).[GetHorizontalDistanceTo](ue_ue.Pawn.md#gethorizontaldistanceto)

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

[Pawn](ue_ue.Pawn.md).[GetHorizontalDotProductTo](ue_ue.Pawn.md#gethorizontaldotproductto)

#### Defined in

[ue/ue.d.ts:13239](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13239)

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

[Pawn](ue_ue.Pawn.md).[GetInputAxisValue](ue_ue.Pawn.md#getinputaxisvalue)

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

[Pawn](ue_ue.Pawn.md).[GetInputVectorAxisValue](ue_ue.Pawn.md#getinputvectoraxisvalue)

#### Defined in

[ue/ue.d.ts:13242](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13242)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetInstigator](ue_ue.Pawn.md#getinstigator)

#### Defined in

[ue/ue.d.ts:13243](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13243)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetInstigatorController](ue_ue.Pawn.md#getinstigatorcontroller)

#### Defined in

[ue/ue.d.ts:13244](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13244)

___

### GetLastMovementInputVector

▸ **GetLastMovementInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetLastMovementInputVector](ue_ue.Pawn.md#getlastmovementinputvector)

#### Defined in

[ue/ue.d.ts:12525](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12525)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetLifeSpan](ue_ue.Pawn.md#getlifespan)

#### Defined in

[ue/ue.d.ts:13245](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13245)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetLocalRole](ue_ue.Pawn.md#getlocalrole)

#### Defined in

[ue/ue.d.ts:13246](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13246)

___

### GetMovementComponent

▸ **GetMovementComponent**(): [`PawnMovementComponent`](ue_ue.PawnMovementComponent.md)

#### Returns

[`PawnMovementComponent`](ue_ue.PawnMovementComponent.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetMovementComponent](ue_ue.Pawn.md#getmovementcomponent)

#### Defined in

[ue/ue.d.ts:12526](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12526)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetName](ue_ue.Pawn.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetNavAgentLocation

▸ **GetNavAgentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetNavAgentLocation](ue_ue.Pawn.md#getnavagentlocation)

#### Defined in

[ue/ue.d.ts:12527](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12527)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetOuter](ue_ue.Pawn.md#getouter)

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

[Pawn](ue_ue.Pawn.md).[GetOverlappingActors](ue_ue.Pawn.md#getoverlappingactors)

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

[Pawn](ue_ue.Pawn.md).[GetOverlappingComponents](ue_ue.Pawn.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:13248](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13248)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetOwner](ue_ue.Pawn.md#getowner)

#### Defined in

[ue/ue.d.ts:13249](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13249)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetParentActor](ue_ue.Pawn.md#getparentactor)

#### Defined in

[ue/ue.d.ts:13250](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13250)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetParentComponent](ue_ue.Pawn.md#getparentcomponent)

#### Defined in

[ue/ue.d.ts:13251](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13251)

___

### GetPendingMovementInputVector

▸ **GetPendingMovementInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetPendingMovementInputVector](ue_ue.Pawn.md#getpendingmovementinputvector)

#### Defined in

[ue/ue.d.ts:12528](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12528)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetRemoteRole](ue_ue.Pawn.md#getremoterole)

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

[Pawn](ue_ue.Pawn.md).[GetSquaredDistanceTo](ue_ue.Pawn.md#getsquareddistanceto)

#### Defined in

[ue/ue.d.ts:13253](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13253)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetTickableWhenPaused](ue_ue.Pawn.md#gettickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13254](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13254)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetTransform](ue_ue.Pawn.md#gettransform)

#### Defined in

[ue/ue.d.ts:13255](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13255)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetVelocity](ue_ue.Pawn.md#getvelocity)

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

[Pawn](ue_ue.Pawn.md).[GetVerticalDistanceTo](ue_ue.Pawn.md#getverticaldistanceto)

#### Defined in

[ue/ue.d.ts:13257](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13257)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[GetWorld](ue_ue.Pawn.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### HasAnyRootMotion

▸ **HasAnyRootMotion**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:6001](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6001)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[HasAuthority](ue_ue.Pawn.md#hasauthority)

#### Defined in

[ue/ue.d.ts:13258](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13258)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsActorBeingDestroyed](ue_ue.Pawn.md#isactorbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13259](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13259)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsActorTickEnabled](ue_ue.Pawn.md#isactortickenabled)

#### Defined in

[ue/ue.d.ts:13260](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13260)

___

### IsBotControlled

▸ **IsBotControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsBotControlled](ue_ue.Pawn.md#isbotcontrolled)

#### Defined in

[ue/ue.d.ts:12529](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12529)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsChildActor](ue_ue.Pawn.md#ischildactor)

#### Defined in

[ue/ue.d.ts:13261](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13261)

___

### IsControlled

▸ **IsControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsControlled](ue_ue.Pawn.md#iscontrolled)

#### Defined in

[ue/ue.d.ts:12530](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12530)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsEditable](ue_ue.Pawn.md#iseditable)

#### Defined in

[ue/ue.d.ts:13262](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13262)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsHiddenEd](ue_ue.Pawn.md#ishiddened)

#### Defined in

[ue/ue.d.ts:13263](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13263)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsHiddenEdAtStartup](ue_ue.Pawn.md#ishiddenedatstartup)

#### Defined in

[ue/ue.d.ts:13264](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13264)

___

### IsJumpProvidingForce

▸ **IsJumpProvidingForce**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:6002](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6002)

___

### IsLocallyControlled

▸ **IsLocallyControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsLocallyControlled](ue_ue.Pawn.md#islocallycontrolled)

#### Defined in

[ue/ue.d.ts:12531](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12531)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsMoveInputIgnored](ue_ue.Pawn.md#ismoveinputignored)

#### Defined in

[ue/ue.d.ts:12532](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12532)

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

#### Defined in

[ue/ue.d.ts:13265](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13265)

___

### IsPawnControlled

▸ **IsPawnControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsPawnControlled](ue_ue.Pawn.md#ispawncontrolled)

#### Defined in

[ue/ue.d.ts:12533](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12533)

___

### IsPlayerControlled

▸ **IsPlayerControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsPlayerControlled](ue_ue.Pawn.md#isplayercontrolled)

#### Defined in

[ue/ue.d.ts:12534](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12534)

___

### IsPlayingNetworkedRootMotionMontage

▸ **IsPlayingNetworkedRootMotionMontage**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:6003](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6003)

___

### IsPlayingRootMotion

▸ **IsPlayingRootMotion**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:6004](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6004)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[IsSelectable](ue_ue.Pawn.md#isselectable)

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

[Pawn](ue_ue.Pawn.md).[IsTemporarilyHiddenInEditor](ue_ue.Pawn.md#istemporarilyhiddenineditor)

#### Defined in

[ue/ue.d.ts:13267](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13267)

___

### Jump

▸ **Jump**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6005](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6005)

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

[Pawn](ue_ue.Pawn.md).[K2_AddActorLocalRotation](ue_ue.Pawn.md#k2_addactorlocalrotation)

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

[Pawn](ue_ue.Pawn.md).[K2_AddActorLocalTransform](ue_ue.Pawn.md#k2_addactorlocaltransform)

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

[Pawn](ue_ue.Pawn.md).[K2_AddActorWorldOffset](ue_ue.Pawn.md#k2_addactorworldoffset)

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

[Pawn](ue_ue.Pawn.md).[K2_AddActorWorldRotation](ue_ue.Pawn.md#k2_addactorworldrotation)

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

[Pawn](ue_ue.Pawn.md).[K2_AddActorWorldTransform](ue_ue.Pawn.md#k2_addactorworldtransform)

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

[Pawn](ue_ue.Pawn.md).[K2_AttachRootComponentTo](ue_ue.Pawn.md#k2_attachrootcomponentto)

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

[Pawn](ue_ue.Pawn.md).[K2_AttachRootComponentToActor](ue_ue.Pawn.md#k2_attachrootcomponenttoactor)

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

[Pawn](ue_ue.Pawn.md).[K2_AttachToActor](ue_ue.Pawn.md#k2_attachtoactor)

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

[Pawn](ue_ue.Pawn.md).[K2_AttachToComponent](ue_ue.Pawn.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:13277](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13277)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[K2_DestroyActor](ue_ue.Pawn.md#k2_destroyactor)

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

[Pawn](ue_ue.Pawn.md).[K2_DestroyComponent](ue_ue.Pawn.md#k2_destroycomponent)

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

[Pawn](ue_ue.Pawn.md).[K2_DetachFromActor](ue_ue.Pawn.md#k2_detachfromactor)

#### Defined in

[ue/ue.d.ts:13280](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13280)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[K2_GetActorLocation](ue_ue.Pawn.md#k2_getactorlocation)

#### Defined in

[ue/ue.d.ts:13281](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13281)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[K2_GetActorRotation](ue_ue.Pawn.md#k2_getactorrotation)

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

[Pawn](ue_ue.Pawn.md).[K2_GetComponentsByClass](ue_ue.Pawn.md#k2_getcomponentsbyclass)

#### Defined in

[ue/ue.d.ts:13283](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13283)

___

### K2\_GetMovementInputVector

▸ **K2_GetMovementInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[K2_GetMovementInputVector](ue_ue.Pawn.md#k2_getmovementinputvector)

#### Defined in

[ue/ue.d.ts:12535](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12535)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Pawn](ue_ue.Pawn.md).[K2_GetRootComponent](ue_ue.Pawn.md#k2_getrootcomponent)

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

[Pawn](ue_ue.Pawn.md).[K2_OnBecomeViewTarget](ue_ue.Pawn.md#k2_onbecomeviewtarget)

#### Defined in

[ue/ue.d.ts:13285](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13285)

___

### K2\_OnEndCrouch

▸ **K2_OnEndCrouch**(`HalfHeightAdjust`, `ScaledHalfHeightAdjust`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `HalfHeightAdjust` | `number` |
| `ScaledHalfHeightAdjust` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6006](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6006)

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

#### Defined in

[ue/ue.d.ts:13286](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13286)

___

### K2\_OnMovementModeChanged

▸ **K2_OnMovementModeChanged**(`PrevMovementMode`, `NewMovementMode`, `PrevCustomMode`, `NewCustomMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrevMovementMode` | [`EMovementMode`](../enums/ue_ue.EMovementMode.md) |
| `NewMovementMode` | [`EMovementMode`](../enums/ue_ue.EMovementMode.md) |
| `PrevCustomMode` | `number` |
| `NewCustomMode` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6007](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6007)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[K2_OnReset](ue_ue.Pawn.md#k2_onreset)

#### Defined in

[ue/ue.d.ts:13287](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13287)

___

### K2\_OnStartCrouch

▸ **K2_OnStartCrouch**(`HalfHeightAdjust`, `ScaledHalfHeightAdjust`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `HalfHeightAdjust` | `number` |
| `ScaledHalfHeightAdjust` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6008](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6008)

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

[Pawn](ue_ue.Pawn.md).[K2_SetActorLocationAndRotation](ue_ue.Pawn.md#k2_setactorlocationandrotation)

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

[Pawn](ue_ue.Pawn.md).[K2_SetActorRelativeLocation](ue_ue.Pawn.md#k2_setactorrelativelocation)

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

[Pawn](ue_ue.Pawn.md).[K2_SetActorRelativeRotation](ue_ue.Pawn.md#k2_setactorrelativerotation)

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

[Pawn](ue_ue.Pawn.md).[K2_SetActorRelativeTransform](ue_ue.Pawn.md#k2_setactorrelativetransform)

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

[Pawn](ue_ue.Pawn.md).[K2_SetActorRotation](ue_ue.Pawn.md#k2_setactorrotation)

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

[Pawn](ue_ue.Pawn.md).[K2_SetActorTransform](ue_ue.Pawn.md#k2_setactortransform)

#### Defined in

[ue/ue.d.ts:13294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13294)

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

#### Defined in

[ue/ue.d.ts:13295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13295)

___

### K2\_UpdateCustomMovement

▸ **K2_UpdateCustomMovement**(`DeltaTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaTime` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6009](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6009)

___

### LaunchCharacter

▸ **LaunchCharacter**(`LaunchVelocity`, `bXYOverride`, `bZOverride`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LaunchVelocity` | [`Vector`](ue_ue_s.Vector.md) |
| `bXYOverride` | `boolean` |
| `bZOverride` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6010](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6010)

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

#### Defined in

[ue/ue.d.ts:12536](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12536)

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

[Pawn](ue_ue.Pawn.md).[MakeNoise](ue_ue.Pawn.md#makenoise)

#### Defined in

[ue/ue.d.ts:13297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13297)

___

### OnJumped

▸ **OnJumped**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6011](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6011)

___

### OnLanded

▸ **OnLanded**(`Hit`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hit` | [`HitResult`](ue_ue.HitResult.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6012](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6012)

___

### OnLaunched

▸ **OnLaunched**(`LaunchVelocity`, `bXYOverride`, `bZOverride`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LaunchVelocity` | [`Vector`](ue_ue_s.Vector.md) |
| `bXYOverride` | `boolean` |
| `bZOverride` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6013](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6013)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnRep_AttachmentReplication](ue_ue.Pawn.md#onrep_attachmentreplication)

#### Defined in

[ue/ue.d.ts:13298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13298)

___

### OnRep\_Controller

▸ **OnRep_Controller**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnRep_Controller](ue_ue.Pawn.md#onrep_controller)

#### Defined in

[ue/ue.d.ts:12537](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12537)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnRep_Instigator](ue_ue.Pawn.md#onrep_instigator)

#### Defined in

[ue/ue.d.ts:13299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13299)

___

### OnRep\_IsCrouched

▸ **OnRep_IsCrouched**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6014](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6014)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnRep_Owner](ue_ue.Pawn.md#onrep_owner)

#### Defined in

[ue/ue.d.ts:13300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13300)

___

### OnRep\_PlayerState

▸ **OnRep_PlayerState**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnRep_PlayerState](ue_ue.Pawn.md#onrep_playerstate)

#### Defined in

[ue/ue.d.ts:12538](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12538)

___

### OnRep\_ReplayLastTransformUpdateTimeStamp

▸ **OnRep_ReplayLastTransformUpdateTimeStamp**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6015](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6015)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnRep_ReplicateMovement](ue_ue.Pawn.md#onrep_replicatemovement)

#### Defined in

[ue/ue.d.ts:13302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13302)

___

### OnRep\_ReplicatedBasedMovement

▸ **OnRep_ReplicatedBasedMovement**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6016](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6016)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[OnRep_ReplicatedMovement](ue_ue.Pawn.md#onrep_replicatedmovement)

#### Defined in

[ue/ue.d.ts:13301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13301)

___

### OnRep\_RootMotion

▸ **OnRep_RootMotion**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6017](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6017)

___

### OnWalkingOffLedge

▸ **OnWalkingOffLedge**(`PreviousFloorImpactNormal`, `PreviousFloorContactNormal`, `PreviousLocation`, `TimeDelta`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PreviousFloorImpactNormal` | [`Vector`](ue_ue_s.Vector.md) |
| `PreviousFloorContactNormal` | [`Vector`](ue_ue_s.Vector.md) |
| `PreviousLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `TimeDelta` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6018](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6018)

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

#### Defined in

[ue/ue.d.ts:12539](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12539)

___

### PlayAnimMontage

▸ **PlayAnimMontage**(`AnimMontage`, `InPlayRate?`, `StartSectionName?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimMontage` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\> |
| `InPlayRate?` | `number` |
| `StartSectionName?` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:6019](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6019)

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

#### Defined in

[ue/ue.d.ts:13303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13303)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ReceiveActorBeginCursorOver](ue_ue.Pawn.md#receiveactorbegincursorover)

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

[Pawn](ue_ue.Pawn.md).[ReceiveActorBeginOverlap](ue_ue.Pawn.md#receiveactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13305)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ReceiveActorEndCursorOver](ue_ue.Pawn.md#receiveactorendcursorover)

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

[Pawn](ue_ue.Pawn.md).[ReceiveActorEndOverlap](ue_ue.Pawn.md#receiveactorendoverlap)

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

[Pawn](ue_ue.Pawn.md).[ReceiveActorOnClicked](ue_ue.Pawn.md#receiveactoronclicked)

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

[Pawn](ue_ue.Pawn.md).[ReceiveActorOnInputTouchBegin](ue_ue.Pawn.md#receiveactoroninputtouchbegin)

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

[Pawn](ue_ue.Pawn.md).[ReceiveActorOnInputTouchEnd](ue_ue.Pawn.md#receiveactoroninputtouchend)

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

[Pawn](ue_ue.Pawn.md).[ReceiveActorOnInputTouchEnter](ue_ue.Pawn.md#receiveactoroninputtouchenter)

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

[Pawn](ue_ue.Pawn.md).[ReceiveActorOnInputTouchLeave](ue_ue.Pawn.md#receiveactoroninputtouchleave)

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

[Pawn](ue_ue.Pawn.md).[ReceiveActorOnReleased](ue_ue.Pawn.md#receiveactoronreleased)

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

[Pawn](ue_ue.Pawn.md).[ReceiveAnyDamage](ue_ue.Pawn.md#receiveanydamage)

#### Defined in

[ue/ue.d.ts:13314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13314)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ReceiveBeginPlay](ue_ue.Pawn.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:13315](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13315)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[ReceiveDestroyed](ue_ue.Pawn.md#receivedestroyed)

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

[Pawn](ue_ue.Pawn.md).[ReceiveEndPlay](ue_ue.Pawn.md#receiveendplay)

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

[Pawn](ue_ue.Pawn.md).[ReceiveHit](ue_ue.Pawn.md#receivehit)

#### Defined in

[ue/ue.d.ts:13318](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13318)

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

#### Defined in

[ue/ue.d.ts:13319](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13319)

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

#### Defined in

[ue/ue.d.ts:12540](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12540)

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

[Pawn](ue_ue.Pawn.md).[ReceiveTick](ue_ue.Pawn.md#receivetick)

#### Defined in

[ue/ue.d.ts:13321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13321)

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

#### Defined in

[ue/ue.d.ts:12541](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12541)

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

[Pawn](ue_ue.Pawn.md).[RemoveTickPrerequisiteComponent](ue_ue.Pawn.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13323)

___

### RootMotionDebugClientPrintOnScreen

▸ **RootMotionDebugClientPrintOnScreen**(`InString`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InString` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6020](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6020)

___

### ServerMove

▸ **ServerMove**(`TimeStamp`, `InAccel`, `ClientLoc`, `CompressedMoveFlags`, `ClientRoll`, `View`, `ClientMovementBase`, `ClientBaseBoneName`, `ClientMovementMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeStamp` | `number` |
| `InAccel` | [`Vector_NetQuantize10`](ue_ue.Vector_NetQuantize10.md) |
| `ClientLoc` | [`Vector_NetQuantize100`](ue_ue.Vector_NetQuantize100.md) |
| `CompressedMoveFlags` | `number` |
| `ClientRoll` | `number` |
| `View` | `number` |
| `ClientMovementBase` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `ClientBaseBoneName` | `string` |
| `ClientMovementMode` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6021](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6021)

___

### ServerMoveDual

▸ **ServerMoveDual**(`TimeStamp0`, `InAccel0`, `PendingFlags`, `View0`, `TimeStamp`, `InAccel`, `ClientLoc`, `NewFlags`, `ClientRoll`, `View`, `ClientMovementBase`, `ClientBaseBoneName`, `ClientMovementMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeStamp0` | `number` |
| `InAccel0` | [`Vector_NetQuantize10`](ue_ue.Vector_NetQuantize10.md) |
| `PendingFlags` | `number` |
| `View0` | `number` |
| `TimeStamp` | `number` |
| `InAccel` | [`Vector_NetQuantize10`](ue_ue.Vector_NetQuantize10.md) |
| `ClientLoc` | [`Vector_NetQuantize100`](ue_ue.Vector_NetQuantize100.md) |
| `NewFlags` | `number` |
| `ClientRoll` | `number` |
| `View` | `number` |
| `ClientMovementBase` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `ClientBaseBoneName` | `string` |
| `ClientMovementMode` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6022](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6022)

___

### ServerMoveDualHybridRootMotion

▸ **ServerMoveDualHybridRootMotion**(`TimeStamp0`, `InAccel0`, `PendingFlags`, `View0`, `TimeStamp`, `InAccel`, `ClientLoc`, `NewFlags`, `ClientRoll`, `View`, `ClientMovementBase`, `ClientBaseBoneName`, `ClientMovementMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeStamp0` | `number` |
| `InAccel0` | [`Vector_NetQuantize10`](ue_ue.Vector_NetQuantize10.md) |
| `PendingFlags` | `number` |
| `View0` | `number` |
| `TimeStamp` | `number` |
| `InAccel` | [`Vector_NetQuantize10`](ue_ue.Vector_NetQuantize10.md) |
| `ClientLoc` | [`Vector_NetQuantize100`](ue_ue.Vector_NetQuantize100.md) |
| `NewFlags` | `number` |
| `ClientRoll` | `number` |
| `View` | `number` |
| `ClientMovementBase` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `ClientBaseBoneName` | `string` |
| `ClientMovementMode` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6023](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6023)

___

### ServerMoveDualNoBase

▸ **ServerMoveDualNoBase**(`TimeStamp0`, `InAccel0`, `PendingFlags`, `View0`, `TimeStamp`, `InAccel`, `ClientLoc`, `NewFlags`, `ClientRoll`, `View`, `ClientMovementMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeStamp0` | `number` |
| `InAccel0` | [`Vector_NetQuantize10`](ue_ue.Vector_NetQuantize10.md) |
| `PendingFlags` | `number` |
| `View0` | `number` |
| `TimeStamp` | `number` |
| `InAccel` | [`Vector_NetQuantize10`](ue_ue.Vector_NetQuantize10.md) |
| `ClientLoc` | [`Vector_NetQuantize100`](ue_ue.Vector_NetQuantize100.md) |
| `NewFlags` | `number` |
| `ClientRoll` | `number` |
| `View` | `number` |
| `ClientMovementMode` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6024](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6024)

___

### ServerMoveNoBase

▸ **ServerMoveNoBase**(`TimeStamp`, `InAccel`, `ClientLoc`, `CompressedMoveFlags`, `ClientRoll`, `View`, `ClientMovementMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeStamp` | `number` |
| `InAccel` | [`Vector_NetQuantize10`](ue_ue.Vector_NetQuantize10.md) |
| `ClientLoc` | [`Vector_NetQuantize100`](ue_ue.Vector_NetQuantize100.md) |
| `CompressedMoveFlags` | `number` |
| `ClientRoll` | `number` |
| `View` | `number` |
| `ClientMovementMode` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6025](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6025)

___

### ServerMoveOld

▸ **ServerMoveOld**(`OldTimeStamp`, `OldAccel`, `OldMoveFlags`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OldTimeStamp` | `number` |
| `OldAccel` | [`Vector_NetQuantize10`](ue_ue.Vector_NetQuantize10.md) |
| `OldMoveFlags` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6026](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6026)

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

[Pawn](ue_ue.Pawn.md).[SetActorHiddenInGame](ue_ue.Pawn.md#setactorhiddeningame)

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

[Pawn](ue_ue.Pawn.md).[SetActorLabel](ue_ue.Pawn.md#setactorlabel)

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

[Pawn](ue_ue.Pawn.md).[SetActorRelativeScale3D](ue_ue.Pawn.md#setactorrelativescale3d)

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

[Pawn](ue_ue.Pawn.md).[SetActorScale3D](ue_ue.Pawn.md#setactorscale3d)

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

[Pawn](ue_ue.Pawn.md).[SetActorTickEnabled](ue_ue.Pawn.md#setactortickenabled)

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

[Pawn](ue_ue.Pawn.md).[SetActorTickInterval](ue_ue.Pawn.md#setactortickinterval)

#### Defined in

[ue/ue.d.ts:13330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13330)

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

#### Defined in

[ue/ue.d.ts:12542](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12542)

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

#### Defined in

[ue/ue.d.ts:13331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13331)

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

[Pawn](ue_ue.Pawn.md).[SetLifeSpan](ue_ue.Pawn.md#setlifespan)

#### Defined in

[ue/ue.d.ts:13333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13333)

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

[Pawn](ue_ue.Pawn.md).[SetOwner](ue_ue.Pawn.md#setowner)

#### Defined in

[ue/ue.d.ts:13335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13335)

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

[Pawn](ue_ue.Pawn.md).[SetReplicates](ue_ue.Pawn.md#setreplicates)

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

[Pawn](ue_ue.Pawn.md).[SetTickGroup](ue_ue.Pawn.md#settickgroup)

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

[Pawn](ue_ue.Pawn.md).[SetTickableWhenPaused](ue_ue.Pawn.md#settickablewhenpaused)

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

[Pawn](ue_ue.Pawn.md).[SnapRootComponentTo](ue_ue.Pawn.md#snaprootcomponentto)

#### Defined in

[ue/ue.d.ts:13340](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13340)

___

### SpawnDefaultController

▸ **SpawnDefaultController**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[SpawnDefaultController](ue_ue.Pawn.md#spawndefaultcontroller)

#### Defined in

[ue/ue.d.ts:12543](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12543)

___

### StopAnimMontage

▸ **StopAnimMontage**(`AnimMontage?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimMontage?` | [`AnimMontage`](ue_ue.AnimMontage.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6027](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6027)

___

### StopJumping

▸ **StopJumping**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6028](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6028)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[TearOff](ue_ue.Pawn.md#tearoff)

#### Defined in

[ue/ue.d.ts:13341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13341)

___

### UnCrouch

▸ **UnCrouch**(`bClientSimulation?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bClientSimulation?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6029](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6029)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[Pawn](ue_ue.Pawn.md).[UserConstructionScript](ue_ue.Pawn.md#userconstructionscript)

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

[Pawn](ue_ue.Pawn.md).[WasRecentlyRendered](ue_ue.Pawn.md#wasrecentlyrendered)

#### Defined in

[ue/ue.d.ts:13343](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13343)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Character`](ue_ue.Character.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Character`](ue_ue.Character.md)

#### Overrides

[Pawn](ue_ue.Pawn.md).[Find](ue_ue.Pawn.md#find)

#### Defined in

[ue/ue.d.ts:6031](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6031)

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

#### Defined in

[ue/ue.d.ts:12544](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12544)

___

### Load

▸ `Static` **Load**(`InName`): [`Character`](ue_ue.Character.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Character`](ue_ue.Character.md)

#### Overrides

[Pawn](ue_ue.Pawn.md).[Load](ue_ue.Pawn.md#load)

#### Defined in

[ue/ue.d.ts:6032](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6032)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Pawn](ue_ue.Pawn.md).[StaticClass](ue_ue.Pawn.md#staticclass)

#### Defined in

[ue/ue.d.ts:6030](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6030)
