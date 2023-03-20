[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ArchVisCharacter

# Class: ArchVisCharacter

[ue/ue](../modules/ue_ue.md).ArchVisCharacter

## Hierarchy

- [`Character`](ue_ue.Character.md)

  ↳ **`ArchVisCharacter`**

## Table of contents

### Constructors

- [constructor](ue_ue.ArchVisCharacter.md#constructor)

### Properties

- [AIControllerClass](ue_ue.ArchVisCharacter.md#aicontrollerclass)
- [ActorLabel](ue_ue.ArchVisCharacter.md#actorlabel)
- [AnimRootMotionTranslationScale](ue_ue.ArchVisCharacter.md#animrootmotiontranslationscale)
- [ArrowComponent](ue_ue.ArchVisCharacter.md#arrowcomponent)
- [AttachmentReplication](ue_ue.ArchVisCharacter.md#attachmentreplication)
- [AutoPossessAI](ue_ue.ArchVisCharacter.md#autopossessai)
- [AutoPossessPlayer](ue_ue.ArchVisCharacter.md#autopossessplayer)
- [AutoReceiveInput](ue_ue.ArchVisCharacter.md#autoreceiveinput)
- [BaseEyeHeight](ue_ue.ArchVisCharacter.md#baseeyeheight)
- [BaseRotationOffset](ue_ue.ArchVisCharacter.md#baserotationoffset)
- [BaseTranslationOffset](ue_ue.ArchVisCharacter.md#basetranslationoffset)
- [BasedMovement](ue_ue.ArchVisCharacter.md#basedmovement)
- [BlueprintCreatedComponents](ue_ue.ArchVisCharacter.md#blueprintcreatedcomponents)
- [CapsuleComponent](ue_ue.ArchVisCharacter.md#capsulecomponent)
- [CharacterMovement](ue_ue.ArchVisCharacter.md#charactermovement)
- [Children](ue_ue.ArchVisCharacter.md#children)
- [ClientRootMotionParams](ue_ue.ArchVisCharacter.md#clientrootmotionparams)
- [ControlInputVector](ue_ue.ArchVisCharacter.md#controlinputvector)
- [Controller](ue_ue.ArchVisCharacter.md#controller)
- [ControllingMatineeActors](ue_ue.ArchVisCharacter.md#controllingmatineeactors)
- [CrouchedEyeHeight](ue_ue.ArchVisCharacter.md#crouchedeyeheight)
- [CustomTimeDilation](ue_ue.ArchVisCharacter.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.ArchVisCharacter.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.ArchVisCharacter.md#folderpath)
- [GroupActor](ue_ue.ArchVisCharacter.md#groupactor)
- [HiddenEditorViews](ue_ue.ArchVisCharacter.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.ArchVisCharacter.md#initiallifespan)
- [InputComponent](ue_ue.ArchVisCharacter.md#inputcomponent)
- [InputPriority](ue_ue.ArchVisCharacter.md#inputpriority)
- [InstanceComponents](ue_ue.ArchVisCharacter.md#instancecomponents)
- [Instigator](ue_ue.ArchVisCharacter.md#instigator)
- [JumpCurrentCount](ue_ue.ArchVisCharacter.md#jumpcurrentcount)
- [JumpForceTimeRemaining](ue_ue.ArchVisCharacter.md#jumpforcetimeremaining)
- [JumpKeyHoldTime](ue_ue.ArchVisCharacter.md#jumpkeyholdtime)
- [JumpMaxCount](ue_ue.ArchVisCharacter.md#jumpmaxcount)
- [JumpMaxHoldTime](ue_ue.ArchVisCharacter.md#jumpmaxholdtime)
- [LastControlInputVector](ue_ue.ArchVisCharacter.md#lastcontrolinputvector)
- [LastHitBy](ue_ue.ArchVisCharacter.md#lasthitby)
- [Layers](ue_ue.ArchVisCharacter.md#layers)
- [LookUpAtRateAxisName](ue_ue.ArchVisCharacter.md#lookupatrateaxisname)
- [LookUpAxisName](ue_ue.ArchVisCharacter.md#lookupaxisname)
- [Mesh](ue_ue.ArchVisCharacter.md#mesh)
- [MinNetUpdateFrequency](ue_ue.ArchVisCharacter.md#minnetupdatefrequency)
- [MouseSensitivityScale\_Pitch](ue_ue.ArchVisCharacter.md#mousesensitivityscale_pitch)
- [MouseSensitivityScale\_Yaw](ue_ue.ArchVisCharacter.md#mousesensitivityscale_yaw)
- [MoveForwardAxisName](ue_ue.ArchVisCharacter.md#moveforwardaxisname)
- [MoveRightAxisName](ue_ue.ArchVisCharacter.md#moverightaxisname)
- [MovementModeChangedDelegate](ue_ue.ArchVisCharacter.md#movementmodechangeddelegate)
- [NetCullDistanceSquared](ue_ue.ArchVisCharacter.md#netculldistancesquared)
- [NetDormancy](ue_ue.ArchVisCharacter.md#netdormancy)
- [NetDriverName](ue_ue.ArchVisCharacter.md#netdrivername)
- [NetPriority](ue_ue.ArchVisCharacter.md#netpriority)
- [NetTag](ue_ue.ArchVisCharacter.md#nettag)
- [NetUpdateFrequency](ue_ue.ArchVisCharacter.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.ArchVisCharacter.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.ArchVisCharacter.md#onactorendoverlap)
- [OnActorHit](ue_ue.ArchVisCharacter.md#onactorhit)
- [OnBeginCursorOver](ue_ue.ArchVisCharacter.md#onbegincursorover)
- [OnCharacterMovementUpdated](ue_ue.ArchVisCharacter.md#oncharactermovementupdated)
- [OnClicked](ue_ue.ArchVisCharacter.md#onclicked)
- [OnDestroyed](ue_ue.ArchVisCharacter.md#ondestroyed)
- [OnEndCursorOver](ue_ue.ArchVisCharacter.md#onendcursorover)
- [OnEndPlay](ue_ue.ArchVisCharacter.md#onendplay)
- [OnInputTouchBegin](ue_ue.ArchVisCharacter.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.ArchVisCharacter.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.ArchVisCharacter.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.ArchVisCharacter.md#oninputtouchleave)
- [OnReachedJumpApex](ue_ue.ArchVisCharacter.md#onreachedjumpapex)
- [OnReleased](ue_ue.ArchVisCharacter.md#onreleased)
- [OnTakeAnyDamage](ue_ue.ArchVisCharacter.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.ArchVisCharacter.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.ArchVisCharacter.md#ontakeradialdamage)
- [Owner](ue_ue.ArchVisCharacter.md#owner)
- [ParentComponent](ue_ue.ArchVisCharacter.md#parentcomponent)
- [ParentComponentActor](ue_ue.ArchVisCharacter.md#parentcomponentactor)
- [PivotOffset](ue_ue.ArchVisCharacter.md#pivotoffset)
- [PlayerState](ue_ue.ArchVisCharacter.md#playerstate)
- [PrimaryActorTick](ue_ue.ArchVisCharacter.md#primaryactortick)
- [ProxyJumpForceStartedTime](ue_ue.ArchVisCharacter.md#proxyjumpforcestartedtime)
- [RemoteRole](ue_ue.ArchVisCharacter.md#remoterole)
- [RemoteViewPitch](ue_ue.ArchVisCharacter.md#remoteviewpitch)
- [RepRootMotion](ue_ue.ArchVisCharacter.md#reprootmotion)
- [ReplayLastTransformUpdateTimeStamp](ue_ue.ArchVisCharacter.md#replaylasttransformupdatetimestamp)
- [ReplicatedBasedMovement](ue_ue.ArchVisCharacter.md#replicatedbasedmovement)
- [ReplicatedMovement](ue_ue.ArchVisCharacter.md#replicatedmovement)
- [ReplicatedMovementMode](ue_ue.ArchVisCharacter.md#replicatedmovementmode)
- [ReplicatedServerLastTransformUpdateTimeStamp](ue_ue.ArchVisCharacter.md#replicatedserverlasttransformupdatetimestamp)
- [Role](ue_ue.ArchVisCharacter.md#role)
- [RootComponent](ue_ue.ArchVisCharacter.md#rootcomponent)
- [RootMotionRepMoves](ue_ue.ArchVisCharacter.md#rootmotionrepmoves)
- [SavedRootMotion](ue_ue.ArchVisCharacter.md#savedrootmotion)
- [SpawnCollisionHandlingMethod](ue_ue.ArchVisCharacter.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.ArchVisCharacter.md#spritescale)
- [Tags](ue_ue.ArchVisCharacter.md#tags)
- [TurnAtRateAxisName](ue_ue.ArchVisCharacter.md#turnatrateaxisname)
- [TurnAxisName](ue_ue.ArchVisCharacter.md#turnaxisname)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.ArchVisCharacter.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.ArchVisCharacter.md#__tid_actor__)
- [\_\_tid\_ArchVisCharacter\_\_](ue_ue.ArchVisCharacter.md#__tid_archvischaracter__)
- [\_\_tid\_Character\_\_](ue_ue.ArchVisCharacter.md#__tid_character__)
- [\_\_tid\_Object\_\_](ue_ue.ArchVisCharacter.md#__tid_object__)
- [\_\_tid\_Pawn\_\_](ue_ue.ArchVisCharacter.md#__tid_pawn__)
- [bActorEnableCollision](ue_ue.ArchVisCharacter.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.ArchVisCharacter.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.ArchVisCharacter.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.ArchVisCharacter.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.ArchVisCharacter.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.ArchVisCharacter.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.ArchVisCharacter.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.ArchVisCharacter.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.ArchVisCharacter.md#bblockinput)
- [bCanAffectNavigationGeneration](ue_ue.ArchVisCharacter.md#bcanaffectnavigationgeneration)
- [bCanBeDamaged](ue_ue.ArchVisCharacter.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.ArchVisCharacter.md#bcanbeincluster)
- [bClientCheckEncroachmentOnNetUpdate](ue_ue.ArchVisCharacter.md#bclientcheckencroachmentonnetupdate)
- [bClientResimulateRootMotion](ue_ue.ArchVisCharacter.md#bclientresimulaterootmotion)
- [bClientResimulateRootMotionSources](ue_ue.ArchVisCharacter.md#bclientresimulaterootmotionsources)
- [bClientUpdating](ue_ue.ArchVisCharacter.md#bclientupdating)
- [bClientWasFalling](ue_ue.ArchVisCharacter.md#bclientwasfalling)
- [bCollideWhenPlacing](ue_ue.ArchVisCharacter.md#bcollidewhenplacing)
- [bEditable](ue_ue.ArchVisCharacter.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.ArchVisCharacter.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.ArchVisCharacter.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.ArchVisCharacter.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.ArchVisCharacter.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.ArchVisCharacter.md#bhidden)
- [bHiddenEd](ue_ue.ArchVisCharacter.md#bhiddened)
- [bHiddenEdLayer](ue_ue.ArchVisCharacter.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.ArchVisCharacter.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.ArchVisCharacter.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.ArchVisCharacter.md#bignoresoriginshifting)
- [bInBaseReplication](ue_ue.ArchVisCharacter.md#binbasereplication)
- [bIsCrouched](ue_ue.ArchVisCharacter.md#biscrouched)
- [bIsEditorOnlyActor](ue_ue.ArchVisCharacter.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.ArchVisCharacter.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.ArchVisCharacter.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.ArchVisCharacter.md#blocklocation)
- [bNetLoadOnClient](ue_ue.ArchVisCharacter.md#bnetloadonclient)
- [bNetStartup](ue_ue.ArchVisCharacter.md#bnetstartup)
- [bNetTemporary](ue_ue.ArchVisCharacter.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.ArchVisCharacter.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.ArchVisCharacter.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.ArchVisCharacter.md#boptimizebpcomponentdata)
- [bPressedJump](ue_ue.ArchVisCharacter.md#bpressedjump)
- [bProxyIsJumpForceApplied](ue_ue.ArchVisCharacter.md#bproxyisjumpforceapplied)
- [bRelevantForLevelBounds](ue_ue.ArchVisCharacter.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.ArchVisCharacter.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.ArchVisCharacter.md#breplayrewindable)
- [bReplicateMovement](ue_ue.ArchVisCharacter.md#breplicatemovement)
- [bReplicates](ue_ue.ArchVisCharacter.md#breplicates)
- [bServerMoveIgnoreRootMotion](ue_ue.ArchVisCharacter.md#bservermoveignorerootmotion)
- [bSimGravityDisabled](ue_ue.ArchVisCharacter.md#bsimgravitydisabled)
- [bTearOff](ue_ue.ArchVisCharacter.md#btearoff)
- [bUseControllerRotationPitch](ue_ue.ArchVisCharacter.md#busecontrollerrotationpitch)
- [bUseControllerRotationRoll](ue_ue.ArchVisCharacter.md#busecontrollerrotationroll)
- [bUseControllerRotationYaw](ue_ue.ArchVisCharacter.md#busecontrollerrotationyaw)
- [bWasJumping](ue_ue.ArchVisCharacter.md#bwasjumping)

### Methods

- [ActorHasTag](ue_ue.ArchVisCharacter.md#actorhastag)
- [AddComponent](ue_ue.ArchVisCharacter.md#addcomponent)
- [AddControllerPitchInput](ue_ue.ArchVisCharacter.md#addcontrollerpitchinput)
- [AddControllerRollInput](ue_ue.ArchVisCharacter.md#addcontrollerrollinput)
- [AddControllerYawInput](ue_ue.ArchVisCharacter.md#addcontrolleryawinput)
- [AddMovementInput](ue_ue.ArchVisCharacter.md#addmovementinput)
- [AddTickPrerequisiteActor](ue_ue.ArchVisCharacter.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.ArchVisCharacter.md#addtickprerequisitecomponent)
- [CacheInitialMeshOffset](ue_ue.ArchVisCharacter.md#cacheinitialmeshoffset)
- [CanCrouch](ue_ue.ArchVisCharacter.md#cancrouch)
- [CanJump](ue_ue.ArchVisCharacter.md#canjump)
- [CanJumpInternal](ue_ue.ArchVisCharacter.md#canjumpinternal)
- [ClientAckGoodMove](ue_ue.ArchVisCharacter.md#clientackgoodmove)
- [ClientAdjustPosition](ue_ue.ArchVisCharacter.md#clientadjustposition)
- [ClientAdjustRootMotionPosition](ue_ue.ArchVisCharacter.md#clientadjustrootmotionposition)
- [ClientAdjustRootMotionSourcePosition](ue_ue.ArchVisCharacter.md#clientadjustrootmotionsourceposition)
- [ClientCheatFly](ue_ue.ArchVisCharacter.md#clientcheatfly)
- [ClientCheatGhost](ue_ue.ArchVisCharacter.md#clientcheatghost)
- [ClientCheatWalk](ue_ue.ArchVisCharacter.md#clientcheatwalk)
- [ClientVeryShortAdjustPosition](ue_ue.ArchVisCharacter.md#clientveryshortadjustposition)
- [ConsumeMovementInputVector](ue_ue.ArchVisCharacter.md#consumemovementinputvector)
- [CreateDefaultSubobject](ue_ue.ArchVisCharacter.md#createdefaultsubobject)
- [Crouch](ue_ue.ArchVisCharacter.md#crouch)
- [DetachFromControllerPendingDestroy](ue_ue.ArchVisCharacter.md#detachfromcontrollerpendingdestroy)
- [DetachRootComponentFromParent](ue_ue.ArchVisCharacter.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.ArchVisCharacter.md#disableinput)
- [EnableInput](ue_ue.ArchVisCharacter.md#enableinput)
- [ExecuteUbergraph](ue_ue.ArchVisCharacter.md#executeubergraph)
- [FlushNetDormancy](ue_ue.ArchVisCharacter.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.ArchVisCharacter.md#forcenetupdate)
- [GetActorBounds](ue_ue.ArchVisCharacter.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.ArchVisCharacter.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.ArchVisCharacter.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.ArchVisCharacter.md#getactorforwardvector)
- [GetActorLabel](ue_ue.ArchVisCharacter.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.ArchVisCharacter.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.ArchVisCharacter.md#getactorrightvector)
- [GetActorScale3D](ue_ue.ArchVisCharacter.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.ArchVisCharacter.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.ArchVisCharacter.md#getactortimedilation)
- [GetActorUpVector](ue_ue.ArchVisCharacter.md#getactorupvector)
- [GetAllChildActors](ue_ue.ArchVisCharacter.md#getallchildactors)
- [GetAnimRootMotionTranslationScale](ue_ue.ArchVisCharacter.md#getanimrootmotiontranslationscale)
- [GetAttachParentActor](ue_ue.ArchVisCharacter.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.ArchVisCharacter.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.ArchVisCharacter.md#getattachedactors)
- [GetBaseAimRotation](ue_ue.ArchVisCharacter.md#getbaseaimrotation)
- [GetBaseRotationOffsetRotator](ue_ue.ArchVisCharacter.md#getbaserotationoffsetrotator)
- [GetBaseTranslationOffset](ue_ue.ArchVisCharacter.md#getbasetranslationoffset)
- [GetClass](ue_ue.ArchVisCharacter.md#getclass)
- [GetComponentByClass](ue_ue.ArchVisCharacter.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.ArchVisCharacter.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.ArchVisCharacter.md#getcomponentsbytag)
- [GetControlRotation](ue_ue.ArchVisCharacter.md#getcontrolrotation)
- [GetController](ue_ue.ArchVisCharacter.md#getcontroller)
- [GetCurrentMontage](ue_ue.ArchVisCharacter.md#getcurrentmontage)
- [GetDistanceTo](ue_ue.ArchVisCharacter.md#getdistanceto)
- [GetDotProductTo](ue_ue.ArchVisCharacter.md#getdotproductto)
- [GetFolderPath](ue_ue.ArchVisCharacter.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.ArchVisCharacter.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.ArchVisCharacter.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.ArchVisCharacter.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.ArchVisCharacter.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.ArchVisCharacter.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.ArchVisCharacter.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.ArchVisCharacter.md#getinstigator)
- [GetInstigatorController](ue_ue.ArchVisCharacter.md#getinstigatorcontroller)
- [GetLastMovementInputVector](ue_ue.ArchVisCharacter.md#getlastmovementinputvector)
- [GetLifeSpan](ue_ue.ArchVisCharacter.md#getlifespan)
- [GetLocalRole](ue_ue.ArchVisCharacter.md#getlocalrole)
- [GetMovementComponent](ue_ue.ArchVisCharacter.md#getmovementcomponent)
- [GetName](ue_ue.ArchVisCharacter.md#getname)
- [GetNavAgentLocation](ue_ue.ArchVisCharacter.md#getnavagentlocation)
- [GetOuter](ue_ue.ArchVisCharacter.md#getouter)
- [GetOverlappingActors](ue_ue.ArchVisCharacter.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.ArchVisCharacter.md#getoverlappingcomponents)
- [GetOwner](ue_ue.ArchVisCharacter.md#getowner)
- [GetParentActor](ue_ue.ArchVisCharacter.md#getparentactor)
- [GetParentComponent](ue_ue.ArchVisCharacter.md#getparentcomponent)
- [GetPendingMovementInputVector](ue_ue.ArchVisCharacter.md#getpendingmovementinputvector)
- [GetRemoteRole](ue_ue.ArchVisCharacter.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.ArchVisCharacter.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.ArchVisCharacter.md#gettickablewhenpaused)
- [GetTransform](ue_ue.ArchVisCharacter.md#gettransform)
- [GetVelocity](ue_ue.ArchVisCharacter.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.ArchVisCharacter.md#getverticaldistanceto)
- [GetWorld](ue_ue.ArchVisCharacter.md#getworld)
- [HasAnyRootMotion](ue_ue.ArchVisCharacter.md#hasanyrootmotion)
- [HasAuthority](ue_ue.ArchVisCharacter.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.ArchVisCharacter.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.ArchVisCharacter.md#isactortickenabled)
- [IsBotControlled](ue_ue.ArchVisCharacter.md#isbotcontrolled)
- [IsChildActor](ue_ue.ArchVisCharacter.md#ischildactor)
- [IsControlled](ue_ue.ArchVisCharacter.md#iscontrolled)
- [IsEditable](ue_ue.ArchVisCharacter.md#iseditable)
- [IsHiddenEd](ue_ue.ArchVisCharacter.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.ArchVisCharacter.md#ishiddenedatstartup)
- [IsJumpProvidingForce](ue_ue.ArchVisCharacter.md#isjumpprovidingforce)
- [IsLocallyControlled](ue_ue.ArchVisCharacter.md#islocallycontrolled)
- [IsMoveInputIgnored](ue_ue.ArchVisCharacter.md#ismoveinputignored)
- [IsOverlappingActor](ue_ue.ArchVisCharacter.md#isoverlappingactor)
- [IsPawnControlled](ue_ue.ArchVisCharacter.md#ispawncontrolled)
- [IsPlayerControlled](ue_ue.ArchVisCharacter.md#isplayercontrolled)
- [IsPlayingNetworkedRootMotionMontage](ue_ue.ArchVisCharacter.md#isplayingnetworkedrootmotionmontage)
- [IsPlayingRootMotion](ue_ue.ArchVisCharacter.md#isplayingrootmotion)
- [IsSelectable](ue_ue.ArchVisCharacter.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.ArchVisCharacter.md#istemporarilyhiddenineditor)
- [Jump](ue_ue.ArchVisCharacter.md#jump)
- [K2\_AddActorLocalOffset](ue_ue.ArchVisCharacter.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.ArchVisCharacter.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.ArchVisCharacter.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.ArchVisCharacter.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.ArchVisCharacter.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.ArchVisCharacter.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.ArchVisCharacter.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.ArchVisCharacter.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.ArchVisCharacter.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.ArchVisCharacter.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.ArchVisCharacter.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.ArchVisCharacter.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.ArchVisCharacter.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.ArchVisCharacter.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.ArchVisCharacter.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.ArchVisCharacter.md#k2_getcomponentsbyclass)
- [K2\_GetMovementInputVector](ue_ue.ArchVisCharacter.md#k2_getmovementinputvector)
- [K2\_GetRootComponent](ue_ue.ArchVisCharacter.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.ArchVisCharacter.md#k2_onbecomeviewtarget)
- [K2\_OnEndCrouch](ue_ue.ArchVisCharacter.md#k2_onendcrouch)
- [K2\_OnEndViewTarget](ue_ue.ArchVisCharacter.md#k2_onendviewtarget)
- [K2\_OnMovementModeChanged](ue_ue.ArchVisCharacter.md#k2_onmovementmodechanged)
- [K2\_OnReset](ue_ue.ArchVisCharacter.md#k2_onreset)
- [K2\_OnStartCrouch](ue_ue.ArchVisCharacter.md#k2_onstartcrouch)
- [K2\_SetActorLocation](ue_ue.ArchVisCharacter.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.ArchVisCharacter.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.ArchVisCharacter.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.ArchVisCharacter.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.ArchVisCharacter.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.ArchVisCharacter.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.ArchVisCharacter.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.ArchVisCharacter.md#k2_teleportto)
- [K2\_UpdateCustomMovement](ue_ue.ArchVisCharacter.md#k2_updatecustommovement)
- [LaunchCharacter](ue_ue.ArchVisCharacter.md#launchcharacter)
- [LaunchPawn](ue_ue.ArchVisCharacter.md#launchpawn)
- [MakeMIDForMaterial](ue_ue.ArchVisCharacter.md#makemidformaterial)
- [MakeNoise](ue_ue.ArchVisCharacter.md#makenoise)
- [OnJumped](ue_ue.ArchVisCharacter.md#onjumped)
- [OnLanded](ue_ue.ArchVisCharacter.md#onlanded)
- [OnLaunched](ue_ue.ArchVisCharacter.md#onlaunched)
- [OnRep\_AttachmentReplication](ue_ue.ArchVisCharacter.md#onrep_attachmentreplication)
- [OnRep\_Controller](ue_ue.ArchVisCharacter.md#onrep_controller)
- [OnRep\_Instigator](ue_ue.ArchVisCharacter.md#onrep_instigator)
- [OnRep\_IsCrouched](ue_ue.ArchVisCharacter.md#onrep_iscrouched)
- [OnRep\_Owner](ue_ue.ArchVisCharacter.md#onrep_owner)
- [OnRep\_PlayerState](ue_ue.ArchVisCharacter.md#onrep_playerstate)
- [OnRep\_ReplayLastTransformUpdateTimeStamp](ue_ue.ArchVisCharacter.md#onrep_replaylasttransformupdatetimestamp)
- [OnRep\_ReplicateMovement](ue_ue.ArchVisCharacter.md#onrep_replicatemovement)
- [OnRep\_ReplicatedBasedMovement](ue_ue.ArchVisCharacter.md#onrep_replicatedbasedmovement)
- [OnRep\_ReplicatedMovement](ue_ue.ArchVisCharacter.md#onrep_replicatedmovement)
- [OnRep\_RootMotion](ue_ue.ArchVisCharacter.md#onrep_rootmotion)
- [OnWalkingOffLedge](ue_ue.ArchVisCharacter.md#onwalkingoffledge)
- [PawnMakeNoise](ue_ue.ArchVisCharacter.md#pawnmakenoise)
- [PlayAnimMontage](ue_ue.ArchVisCharacter.md#playanimmontage)
- [PrestreamTextures](ue_ue.ArchVisCharacter.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.ArchVisCharacter.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.ArchVisCharacter.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.ArchVisCharacter.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.ArchVisCharacter.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.ArchVisCharacter.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.ArchVisCharacter.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.ArchVisCharacter.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.ArchVisCharacter.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.ArchVisCharacter.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.ArchVisCharacter.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.ArchVisCharacter.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.ArchVisCharacter.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.ArchVisCharacter.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.ArchVisCharacter.md#receiveendplay)
- [ReceiveHit](ue_ue.ArchVisCharacter.md#receivehit)
- [ReceivePointDamage](ue_ue.ArchVisCharacter.md#receivepointdamage)
- [ReceivePossessed](ue_ue.ArchVisCharacter.md#receivepossessed)
- [ReceiveRadialDamage](ue_ue.ArchVisCharacter.md#receiveradialdamage)
- [ReceiveTick](ue_ue.ArchVisCharacter.md#receivetick)
- [ReceiveUnpossessed](ue_ue.ArchVisCharacter.md#receiveunpossessed)
- [RemoveTickPrerequisiteActor](ue_ue.ArchVisCharacter.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.ArchVisCharacter.md#removetickprerequisitecomponent)
- [RootMotionDebugClientPrintOnScreen](ue_ue.ArchVisCharacter.md#rootmotiondebugclientprintonscreen)
- [ServerMove](ue_ue.ArchVisCharacter.md#servermove)
- [ServerMoveDual](ue_ue.ArchVisCharacter.md#servermovedual)
- [ServerMoveDualHybridRootMotion](ue_ue.ArchVisCharacter.md#servermovedualhybridrootmotion)
- [ServerMoveDualNoBase](ue_ue.ArchVisCharacter.md#servermovedualnobase)
- [ServerMoveNoBase](ue_ue.ArchVisCharacter.md#servermovenobase)
- [ServerMoveOld](ue_ue.ArchVisCharacter.md#servermoveold)
- [SetActorEnableCollision](ue_ue.ArchVisCharacter.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.ArchVisCharacter.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.ArchVisCharacter.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.ArchVisCharacter.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.ArchVisCharacter.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.ArchVisCharacter.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.ArchVisCharacter.md#setactortickinterval)
- [SetCanAffectNavigationGeneration](ue_ue.ArchVisCharacter.md#setcanaffectnavigationgeneration)
- [SetFolderPath](ue_ue.ArchVisCharacter.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.ArchVisCharacter.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.ArchVisCharacter.md#setlifespan)
- [SetNetDormancy](ue_ue.ArchVisCharacter.md#setnetdormancy)
- [SetOwner](ue_ue.ArchVisCharacter.md#setowner)
- [SetReplicateMovement](ue_ue.ArchVisCharacter.md#setreplicatemovement)
- [SetReplicates](ue_ue.ArchVisCharacter.md#setreplicates)
- [SetTickGroup](ue_ue.ArchVisCharacter.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.ArchVisCharacter.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.ArchVisCharacter.md#snaprootcomponentto)
- [SpawnDefaultController](ue_ue.ArchVisCharacter.md#spawndefaultcontroller)
- [StopAnimMontage](ue_ue.ArchVisCharacter.md#stopanimmontage)
- [StopJumping](ue_ue.ArchVisCharacter.md#stopjumping)
- [TearOff](ue_ue.ArchVisCharacter.md#tearoff)
- [UnCrouch](ue_ue.ArchVisCharacter.md#uncrouch)
- [UserConstructionScript](ue_ue.ArchVisCharacter.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.ArchVisCharacter.md#wasrecentlyrendered)
- [Find](ue_ue.ArchVisCharacter.md#find)
- [GetMovementBaseActor](ue_ue.ArchVisCharacter.md#getmovementbaseactor)
- [Load](ue_ue.ArchVisCharacter.md#load)
- [StaticClass](ue_ue.ArchVisCharacter.md#staticclass)

## Constructors

### constructor

• **new ArchVisCharacter**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Character](ue_ue.Character.md).[constructor](ue_ue.Character.md#constructor)

## Properties

### AIControllerClass

• **AIControllerClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Character](ue_ue.Character.md).[AIControllerClass](ue_ue.Character.md#aicontrollerclass)

___

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[Character](ue_ue.Character.md).[ActorLabel](ue_ue.Character.md#actorlabel)

___

### AnimRootMotionTranslationScale

• **AnimRootMotionTranslationScale**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[AnimRootMotionTranslationScale](ue_ue.Character.md#animrootmotiontranslationscale)

___

### ArrowComponent

• **ArrowComponent**: [`ArrowComponent`](ue_ue.ArrowComponent.md)

#### Inherited from

[Character](ue_ue.Character.md).[ArrowComponent](ue_ue.Character.md#arrowcomponent)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[Character](ue_ue.Character.md).[AttachmentReplication](ue_ue.Character.md#attachmentreplication)

___

### AutoPossessAI

• **AutoPossessAI**: [`EAutoPossessAI`](../enums/ue_ue.EAutoPossessAI.md)

#### Inherited from

[Character](ue_ue.Character.md).[AutoPossessAI](ue_ue.Character.md#autopossessai)

___

### AutoPossessPlayer

• **AutoPossessPlayer**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[Character](ue_ue.Character.md).[AutoPossessPlayer](ue_ue.Character.md#autopossessplayer)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[Character](ue_ue.Character.md).[AutoReceiveInput](ue_ue.Character.md#autoreceiveinput)

___

### BaseEyeHeight

• **BaseEyeHeight**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[BaseEyeHeight](ue_ue.Character.md#baseeyeheight)

___

### BaseRotationOffset

• **BaseRotationOffset**: [`Quat`](ue_ue_s.Quat.md)

#### Inherited from

[Character](ue_ue.Character.md).[BaseRotationOffset](ue_ue.Character.md#baserotationoffset)

___

### BaseTranslationOffset

• **BaseTranslationOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Character](ue_ue.Character.md).[BaseTranslationOffset](ue_ue.Character.md#basetranslationoffset)

___

### BasedMovement

• **BasedMovement**: [`BasedMovementInfo`](ue_ue.BasedMovementInfo.md)

#### Inherited from

[Character](ue_ue.Character.md).[BasedMovement](ue_ue.Character.md#basedmovement)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Character](ue_ue.Character.md).[BlueprintCreatedComponents](ue_ue.Character.md#blueprintcreatedcomponents)

___

### CapsuleComponent

• **CapsuleComponent**: [`CapsuleComponent`](ue_ue.CapsuleComponent.md)

#### Inherited from

[Character](ue_ue.Character.md).[CapsuleComponent](ue_ue.Character.md#capsulecomponent)

___

### CharacterMovement

• **CharacterMovement**: [`CharacterMovementComponent`](ue_ue.CharacterMovementComponent.md)

#### Inherited from

[Character](ue_ue.Character.md).[CharacterMovement](ue_ue.Character.md#charactermovement)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Character](ue_ue.Character.md).[Children](ue_ue.Character.md#children)

___

### ClientRootMotionParams

• **ClientRootMotionParams**: [`RootMotionMovementParams`](ue_ue.RootMotionMovementParams.md)

#### Inherited from

[Character](ue_ue.Character.md).[ClientRootMotionParams](ue_ue.Character.md#clientrootmotionparams)

___

### ControlInputVector

• **ControlInputVector**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Character](ue_ue.Character.md).[ControlInputVector](ue_ue.Character.md#controlinputvector)

___

### Controller

• **Controller**: [`Controller`](ue_ue.Controller.md)

#### Inherited from

[Character](ue_ue.Character.md).[Controller](ue_ue.Character.md#controller)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[Character](ue_ue.Character.md).[ControllingMatineeActors](ue_ue.Character.md#controllingmatineeactors)

___

### CrouchedEyeHeight

• **CrouchedEyeHeight**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[CrouchedEyeHeight](ue_ue.Character.md#crouchedeyeheight)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[CustomTimeDilation](ue_ue.Character.md#customtimedilation)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Character](ue_ue.Character.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.Character.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[Character](ue_ue.Character.md).[FolderPath](ue_ue.Character.md#folderpath)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Character](ue_ue.Character.md).[GroupActor](ue_ue.Character.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[Character](ue_ue.Character.md).[HiddenEditorViews](ue_ue.Character.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[InitialLifeSpan](ue_ue.Character.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[Character](ue_ue.Character.md).[InputComponent](ue_ue.Character.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[InputPriority](ue_ue.Character.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Character](ue_ue.Character.md).[InstanceComponents](ue_ue.Character.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Character](ue_ue.Character.md).[Instigator](ue_ue.Character.md#instigator)

___

### JumpCurrentCount

• **JumpCurrentCount**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[JumpCurrentCount](ue_ue.Character.md#jumpcurrentcount)

___

### JumpForceTimeRemaining

• **JumpForceTimeRemaining**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[JumpForceTimeRemaining](ue_ue.Character.md#jumpforcetimeremaining)

___

### JumpKeyHoldTime

• **JumpKeyHoldTime**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[JumpKeyHoldTime](ue_ue.Character.md#jumpkeyholdtime)

___

### JumpMaxCount

• **JumpMaxCount**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[JumpMaxCount](ue_ue.Character.md#jumpmaxcount)

___

### JumpMaxHoldTime

• **JumpMaxHoldTime**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[JumpMaxHoldTime](ue_ue.Character.md#jumpmaxholdtime)

___

### LastControlInputVector

• **LastControlInputVector**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Character](ue_ue.Character.md).[LastControlInputVector](ue_ue.Character.md#lastcontrolinputvector)

___

### LastHitBy

• **LastHitBy**: [`Controller`](ue_ue.Controller.md)

#### Inherited from

[Character](ue_ue.Character.md).[LastHitBy](ue_ue.Character.md#lasthitby)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Character](ue_ue.Character.md).[Layers](ue_ue.Character.md#layers)

___

### LookUpAtRateAxisName

• **LookUpAtRateAxisName**: `string`

___

### LookUpAxisName

• **LookUpAxisName**: `string`

___

### Mesh

• **Mesh**: [`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)

#### Inherited from

[Character](ue_ue.Character.md).[Mesh](ue_ue.Character.md#mesh)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[MinNetUpdateFrequency](ue_ue.Character.md#minnetupdatefrequency)

___

### MouseSensitivityScale\_Pitch

• **MouseSensitivityScale\_Pitch**: `number`

___

### MouseSensitivityScale\_Yaw

• **MouseSensitivityScale\_Yaw**: `number`

___

### MoveForwardAxisName

• **MoveForwardAxisName**: `string`

___

### MoveRightAxisName

• **MoveRightAxisName**: `string`

___

### MovementModeChangedDelegate

• **MovementModeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Character`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Character`](ue_ue.Character.md)\>, `PrevMovementMode`: [`EMovementMode`](../enums/ue_ue.EMovementMode.md), `PreviousCustomMode`: `number`) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[MovementModeChangedDelegate](ue_ue.Character.md#movementmodechangeddelegate)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[NetCullDistanceSquared](ue_ue.Character.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[Character](ue_ue.Character.md).[NetDormancy](ue_ue.Character.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[Character](ue_ue.Character.md).[NetDriverName](ue_ue.Character.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[NetPriority](ue_ue.Character.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[NetTag](ue_ue.Character.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[NetUpdateFrequency](ue_ue.Character.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnActorBeginOverlap](ue_ue.Character.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnActorEndOverlap](ue_ue.Character.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnActorHit](ue_ue.Character.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnBeginCursorOver](ue_ue.Character.md#onbegincursorover)

___

### OnCharacterMovementUpdated

• **OnCharacterMovementUpdated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DeltaSeconds`: `number`, `OldLocation`: [`Vector`](ue_ue_s.Vector.md), `OldVelocity`: [`Vector`](ue_ue_s.Vector.md)) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnCharacterMovementUpdated](ue_ue.Character.md#oncharactermovementupdated)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnClicked](ue_ue.Character.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnDestroyed](ue_ue.Character.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnEndCursorOver](ue_ue.Character.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnEndPlay](ue_ue.Character.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnInputTouchBegin](ue_ue.Character.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnInputTouchEnd](ue_ue.Character.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnInputTouchEnter](ue_ue.Character.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnInputTouchLeave](ue_ue.Character.md#oninputtouchleave)

___

### OnReachedJumpApex

• **OnReachedJumpApex**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnReachedJumpApex](ue_ue.Character.md#onreachedjumpapex)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnReleased](ue_ue.Character.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnTakeAnyDamage](ue_ue.Character.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnTakePointDamage](ue_ue.Character.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Character](ue_ue.Character.md).[OnTakeRadialDamage](ue_ue.Character.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Character](ue_ue.Character.md).[Owner](ue_ue.Character.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[Character](ue_ue.Character.md).[ParentComponent](ue_ue.Character.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Character](ue_ue.Character.md).[ParentComponentActor](ue_ue.Character.md#parentcomponentactor)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Character](ue_ue.Character.md).[PivotOffset](ue_ue.Character.md#pivotoffset)

___

### PlayerState

• **PlayerState**: [`PlayerState`](ue_ue.PlayerState.md)

#### Inherited from

[Character](ue_ue.Character.md).[PlayerState](ue_ue.Character.md#playerstate)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[Character](ue_ue.Character.md).[PrimaryActorTick](ue_ue.Character.md#primaryactortick)

___

### ProxyJumpForceStartedTime

• **ProxyJumpForceStartedTime**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[ProxyJumpForceStartedTime](ue_ue.Character.md#proxyjumpforcestartedtime)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Character](ue_ue.Character.md).[RemoteRole](ue_ue.Character.md#remoterole)

___

### RemoteViewPitch

• **RemoteViewPitch**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[RemoteViewPitch](ue_ue.Character.md#remoteviewpitch)

___

### RepRootMotion

• **RepRootMotion**: [`RepRootMotionMontage`](ue_ue.RepRootMotionMontage.md)

#### Inherited from

[Character](ue_ue.Character.md).[RepRootMotion](ue_ue.Character.md#reprootmotion)

___

### ReplayLastTransformUpdateTimeStamp

• **ReplayLastTransformUpdateTimeStamp**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[ReplayLastTransformUpdateTimeStamp](ue_ue.Character.md#replaylasttransformupdatetimestamp)

___

### ReplicatedBasedMovement

• **ReplicatedBasedMovement**: [`BasedMovementInfo`](ue_ue.BasedMovementInfo.md)

#### Inherited from

[Character](ue_ue.Character.md).[ReplicatedBasedMovement](ue_ue.Character.md#replicatedbasedmovement)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[Character](ue_ue.Character.md).[ReplicatedMovement](ue_ue.Character.md#replicatedmovement)

___

### ReplicatedMovementMode

• **ReplicatedMovementMode**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[ReplicatedMovementMode](ue_ue.Character.md#replicatedmovementmode)

___

### ReplicatedServerLastTransformUpdateTimeStamp

• **ReplicatedServerLastTransformUpdateTimeStamp**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[ReplicatedServerLastTransformUpdateTimeStamp](ue_ue.Character.md#replicatedserverlasttransformupdatetimestamp)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Character](ue_ue.Character.md).[Role](ue_ue.Character.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Character](ue_ue.Character.md).[RootComponent](ue_ue.Character.md#rootcomponent)

___

### RootMotionRepMoves

• **RootMotionRepMoves**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimulatedRootMotionReplicatedMove`](ue_ue.SimulatedRootMotionReplicatedMove.md)\>

#### Inherited from

[Character](ue_ue.Character.md).[RootMotionRepMoves](ue_ue.Character.md#rootmotionrepmoves)

___

### SavedRootMotion

• **SavedRootMotion**: [`RootMotionSourceGroup`](ue_ue.RootMotionSourceGroup.md)

#### Inherited from

[Character](ue_ue.Character.md).[SavedRootMotion](ue_ue.Character.md#savedrootmotion)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[Character](ue_ue.Character.md).[SpawnCollisionHandlingMethod](ue_ue.Character.md#spawncollisionhandlingmethod)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[Character](ue_ue.Character.md).[SpriteScale](ue_ue.Character.md#spritescale)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Character](ue_ue.Character.md).[Tags](ue_ue.Character.md#tags)

___

### TurnAtRateAxisName

• **TurnAtRateAxisName**: `string`

___

### TurnAxisName

• **TurnAxisName**: `string`

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Character](ue_ue.Character.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.Character.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[__tid_Actor__](ue_ue.Character.md#__tid_actor__)

___

### \_\_tid\_ArchVisCharacter\_\_

• **\_\_tid\_ArchVisCharacter\_\_**: `boolean`

___

### \_\_tid\_Character\_\_

• **\_\_tid\_Character\_\_**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[__tid_Character__](ue_ue.Character.md#__tid_character__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[__tid_Object__](ue_ue.Character.md#__tid_object__)

___

### \_\_tid\_Pawn\_\_

• **\_\_tid\_Pawn\_\_**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[__tid_Pawn__](ue_ue.Character.md#__tid_pawn__)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bActorEnableCollision](ue_ue.Character.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bActorIsBeingDestroyed](ue_ue.Character.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bActorLabelEditable](ue_ue.Character.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bActorSeamlessTraveled](ue_ue.Character.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.Character.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bAllowTickBeforeBeginPlay](ue_ue.Character.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bAlwaysRelevant](ue_ue.Character.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bAutoDestroyWhenFinished](ue_ue.Character.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bBlockInput](ue_ue.Character.md#bblockinput)

___

### bCanAffectNavigationGeneration

• **bCanAffectNavigationGeneration**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bCanAffectNavigationGeneration](ue_ue.Character.md#bcanaffectnavigationgeneration)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bCanBeDamaged](ue_ue.Character.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bCanBeInCluster](ue_ue.Character.md#bcanbeincluster)

___

### bClientCheckEncroachmentOnNetUpdate

• **bClientCheckEncroachmentOnNetUpdate**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bClientCheckEncroachmentOnNetUpdate](ue_ue.Character.md#bclientcheckencroachmentonnetupdate)

___

### bClientResimulateRootMotion

• **bClientResimulateRootMotion**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bClientResimulateRootMotion](ue_ue.Character.md#bclientresimulaterootmotion)

___

### bClientResimulateRootMotionSources

• **bClientResimulateRootMotionSources**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bClientResimulateRootMotionSources](ue_ue.Character.md#bclientresimulaterootmotionsources)

___

### bClientUpdating

• **bClientUpdating**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bClientUpdating](ue_ue.Character.md#bclientupdating)

___

### bClientWasFalling

• **bClientWasFalling**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bClientWasFalling](ue_ue.Character.md#bclientwasfalling)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bCollideWhenPlacing](ue_ue.Character.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bEditable](ue_ue.Character.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bEnableAutoLODGeneration](ue_ue.Character.md#benableautolodgeneration)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bExchangedRoles](ue_ue.Character.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bFindCameraComponentWhenViewTarget](ue_ue.Character.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.Character.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bHidden](ue_ue.Character.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bHiddenEd](ue_ue.Character.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bHiddenEdLayer](ue_ue.Character.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bHiddenEdLevel](ue_ue.Character.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bHiddenEdTemporary](ue_ue.Character.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bIgnoresOriginShifting](ue_ue.Character.md#bignoresoriginshifting)

___

### bInBaseReplication

• **bInBaseReplication**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bInBaseReplication](ue_ue.Character.md#binbasereplication)

___

### bIsCrouched

• **bIsCrouched**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bIsCrouched](ue_ue.Character.md#biscrouched)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bIsEditorOnlyActor](ue_ue.Character.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bIsEditorPreviewActor](ue_ue.Character.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bListedInSceneOutliner](ue_ue.Character.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bLockLocation](ue_ue.Character.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bNetLoadOnClient](ue_ue.Character.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bNetStartup](ue_ue.Character.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bNetTemporary](ue_ue.Character.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bNetUseOwnerRelevancy](ue_ue.Character.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bOnlyRelevantToOwner](ue_ue.Character.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bOptimizeBPComponentData](ue_ue.Character.md#boptimizebpcomponentdata)

___

### bPressedJump

• **bPressedJump**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bPressedJump](ue_ue.Character.md#bpressedjump)

___

### bProxyIsJumpForceApplied

• **bProxyIsJumpForceApplied**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bProxyIsJumpForceApplied](ue_ue.Character.md#bproxyisjumpforceapplied)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bRelevantForLevelBounds](ue_ue.Character.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bRelevantForNetworkReplays](ue_ue.Character.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bReplayRewindable](ue_ue.Character.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bReplicateMovement](ue_ue.Character.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bReplicates](ue_ue.Character.md#breplicates)

___

### bServerMoveIgnoreRootMotion

• **bServerMoveIgnoreRootMotion**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bServerMoveIgnoreRootMotion](ue_ue.Character.md#bservermoveignorerootmotion)

___

### bSimGravityDisabled

• **bSimGravityDisabled**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bSimGravityDisabled](ue_ue.Character.md#bsimgravitydisabled)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bTearOff](ue_ue.Character.md#btearoff)

___

### bUseControllerRotationPitch

• **bUseControllerRotationPitch**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bUseControllerRotationPitch](ue_ue.Character.md#busecontrollerrotationpitch)

___

### bUseControllerRotationRoll

• **bUseControllerRotationRoll**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bUseControllerRotationRoll](ue_ue.Character.md#busecontrollerrotationroll)

___

### bUseControllerRotationYaw

• **bUseControllerRotationYaw**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bUseControllerRotationYaw](ue_ue.Character.md#busecontrollerrotationyaw)

___

### bWasJumping

• **bWasJumping**: `boolean`

#### Inherited from

[Character](ue_ue.Character.md).[bWasJumping](ue_ue.Character.md#bwasjumping)

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

[Character](ue_ue.Character.md).[ActorHasTag](ue_ue.Character.md#actorhastag)

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

[Character](ue_ue.Character.md).[AddComponent](ue_ue.Character.md#addcomponent)

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

[Character](ue_ue.Character.md).[AddControllerPitchInput](ue_ue.Character.md#addcontrollerpitchinput)

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

[Character](ue_ue.Character.md).[AddControllerRollInput](ue_ue.Character.md#addcontrollerrollinput)

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

[Character](ue_ue.Character.md).[AddControllerYawInput](ue_ue.Character.md#addcontrolleryawinput)

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

[Character](ue_ue.Character.md).[AddMovementInput](ue_ue.Character.md#addmovementinput)

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

[Character](ue_ue.Character.md).[AddTickPrerequisiteActor](ue_ue.Character.md#addtickprerequisiteactor)

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

[Character](ue_ue.Character.md).[AddTickPrerequisiteComponent](ue_ue.Character.md#addtickprerequisitecomponent)

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

#### Inherited from

[Character](ue_ue.Character.md).[CacheInitialMeshOffset](ue_ue.Character.md#cacheinitialmeshoffset)

___

### CanCrouch

▸ **CanCrouch**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[CanCrouch](ue_ue.Character.md#cancrouch)

___

### CanJump

▸ **CanJump**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[CanJump](ue_ue.Character.md#canjump)

___

### CanJumpInternal

▸ **CanJumpInternal**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[CanJumpInternal](ue_ue.Character.md#canjumpinternal)

___

### ClientAckGoodMove

▸ **ClientAckGoodMove**(`TimeStamp`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeStamp` | `number` |

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[ClientAckGoodMove](ue_ue.Character.md#clientackgoodmove)

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

#### Inherited from

[Character](ue_ue.Character.md).[ClientAdjustPosition](ue_ue.Character.md#clientadjustposition)

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

#### Inherited from

[Character](ue_ue.Character.md).[ClientAdjustRootMotionPosition](ue_ue.Character.md#clientadjustrootmotionposition)

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

#### Inherited from

[Character](ue_ue.Character.md).[ClientAdjustRootMotionSourcePosition](ue_ue.Character.md#clientadjustrootmotionsourceposition)

___

### ClientCheatFly

▸ **ClientCheatFly**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[ClientCheatFly](ue_ue.Character.md#clientcheatfly)

___

### ClientCheatGhost

▸ **ClientCheatGhost**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[ClientCheatGhost](ue_ue.Character.md#clientcheatghost)

___

### ClientCheatWalk

▸ **ClientCheatWalk**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[ClientCheatWalk](ue_ue.Character.md#clientcheatwalk)

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

#### Inherited from

[Character](ue_ue.Character.md).[ClientVeryShortAdjustPosition](ue_ue.Character.md#clientveryshortadjustposition)

___

### ConsumeMovementInputVector

▸ **ConsumeMovementInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Character](ue_ue.Character.md).[ConsumeMovementInputVector](ue_ue.Character.md#consumemovementinputvector)

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

[Character](ue_ue.Character.md).[CreateDefaultSubobject](ue_ue.Character.md#createdefaultsubobject)

___

### Crouch

▸ **Crouch**(`bClientSimulation?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bClientSimulation?` | `boolean` |

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[Crouch](ue_ue.Character.md#crouch)

___

### DetachFromControllerPendingDestroy

▸ **DetachFromControllerPendingDestroy**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[DetachFromControllerPendingDestroy](ue_ue.Character.md#detachfromcontrollerpendingdestroy)

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

[Character](ue_ue.Character.md).[DetachRootComponentFromParent](ue_ue.Character.md#detachrootcomponentfromparent)

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

[Character](ue_ue.Character.md).[DisableInput](ue_ue.Character.md#disableinput)

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

[Character](ue_ue.Character.md).[EnableInput](ue_ue.Character.md#enableinput)

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

[Character](ue_ue.Character.md).[ExecuteUbergraph](ue_ue.Character.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[FlushNetDormancy](ue_ue.Character.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[ForceNetUpdate](ue_ue.Character.md#forcenetupdate)

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

[Character](ue_ue.Character.md).[GetActorBounds](ue_ue.Character.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[GetActorEnableCollision](ue_ue.Character.md#getactorenablecollision)

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

[Character](ue_ue.Character.md).[GetActorEyesViewPoint](ue_ue.Character.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetActorForwardVector](ue_ue.Character.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[Character](ue_ue.Character.md).[GetActorLabel](ue_ue.Character.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetActorRelativeScale3D](ue_ue.Character.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetActorRightVector](ue_ue.Character.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetActorScale3D](ue_ue.Character.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[Character](ue_ue.Character.md).[GetActorTickInterval](ue_ue.Character.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[Character](ue_ue.Character.md).[GetActorTimeDilation](ue_ue.Character.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetActorUpVector](ue_ue.Character.md#getactorupvector)

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

[Character](ue_ue.Character.md).[GetAllChildActors](ue_ue.Character.md#getallchildactors)

___

### GetAnimRootMotionTranslationScale

▸ **GetAnimRootMotionTranslationScale**(): `number`

#### Returns

`number`

#### Inherited from

[Character](ue_ue.Character.md).[GetAnimRootMotionTranslationScale](ue_ue.Character.md#getanimrootmotiontranslationscale)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetAttachParentActor](ue_ue.Character.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[Character](ue_ue.Character.md).[GetAttachParentSocketName](ue_ue.Character.md#getattachparentsocketname)

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

[Character](ue_ue.Character.md).[GetAttachedActors](ue_ue.Character.md#getattachedactors)

___

### GetBaseAimRotation

▸ **GetBaseAimRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetBaseAimRotation](ue_ue.Character.md#getbaseaimrotation)

___

### GetBaseRotationOffsetRotator

▸ **GetBaseRotationOffsetRotator**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetBaseRotationOffsetRotator](ue_ue.Character.md#getbaserotationoffsetrotator)

___

### GetBaseTranslationOffset

▸ **GetBaseTranslationOffset**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetBaseTranslationOffset](ue_ue.Character.md#getbasetranslationoffset)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetClass](ue_ue.Character.md#getclass)

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

[Character](ue_ue.Character.md).[GetComponentByClass](ue_ue.Character.md#getcomponentbyclass)

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

[Character](ue_ue.Character.md).[GetComponentsByInterface](ue_ue.Character.md#getcomponentsbyinterface)

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

[Character](ue_ue.Character.md).[GetComponentsByTag](ue_ue.Character.md#getcomponentsbytag)

___

### GetControlRotation

▸ **GetControlRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetControlRotation](ue_ue.Character.md#getcontrolrotation)

___

### GetController

▸ **GetController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetController](ue_ue.Character.md#getcontroller)

___

### GetCurrentMontage

▸ **GetCurrentMontage**(): [`AnimMontage`](ue_ue.AnimMontage.md)

#### Returns

[`AnimMontage`](ue_ue.AnimMontage.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetCurrentMontage](ue_ue.Character.md#getcurrentmontage)

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

[Character](ue_ue.Character.md).[GetDistanceTo](ue_ue.Character.md#getdistanceto)

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

[Character](ue_ue.Character.md).[GetDotProductTo](ue_ue.Character.md#getdotproductto)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[Character](ue_ue.Character.md).[GetFolderPath](ue_ue.Character.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[Character](ue_ue.Character.md).[GetGameTimeSinceCreation](ue_ue.Character.md#getgametimesincecreation)

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

[Character](ue_ue.Character.md).[GetHorizontalDistanceTo](ue_ue.Character.md#gethorizontaldistanceto)

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

[Character](ue_ue.Character.md).[GetHorizontalDotProductTo](ue_ue.Character.md#gethorizontaldotproductto)

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

[Character](ue_ue.Character.md).[GetInputAxisKeyValue](ue_ue.Character.md#getinputaxiskeyvalue)

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

[Character](ue_ue.Character.md).[GetInputAxisValue](ue_ue.Character.md#getinputaxisvalue)

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

[Character](ue_ue.Character.md).[GetInputVectorAxisValue](ue_ue.Character.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetInstigator](ue_ue.Character.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetInstigatorController](ue_ue.Character.md#getinstigatorcontroller)

___

### GetLastMovementInputVector

▸ **GetLastMovementInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetLastMovementInputVector](ue_ue.Character.md#getlastmovementinputvector)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[Character](ue_ue.Character.md).[GetLifeSpan](ue_ue.Character.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetLocalRole](ue_ue.Character.md#getlocalrole)

___

### GetMovementComponent

▸ **GetMovementComponent**(): [`PawnMovementComponent`](ue_ue.PawnMovementComponent.md)

#### Returns

[`PawnMovementComponent`](ue_ue.PawnMovementComponent.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetMovementComponent](ue_ue.Character.md#getmovementcomponent)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Character](ue_ue.Character.md).[GetName](ue_ue.Character.md#getname)

___

### GetNavAgentLocation

▸ **GetNavAgentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetNavAgentLocation](ue_ue.Character.md#getnavagentlocation)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetOuter](ue_ue.Character.md#getouter)

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

[Character](ue_ue.Character.md).[GetOverlappingActors](ue_ue.Character.md#getoverlappingactors)

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

[Character](ue_ue.Character.md).[GetOverlappingComponents](ue_ue.Character.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetOwner](ue_ue.Character.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetParentActor](ue_ue.Character.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetParentComponent](ue_ue.Character.md#getparentcomponent)

___

### GetPendingMovementInputVector

▸ **GetPendingMovementInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetPendingMovementInputVector](ue_ue.Character.md#getpendingmovementinputvector)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetRemoteRole](ue_ue.Character.md#getremoterole)

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

[Character](ue_ue.Character.md).[GetSquaredDistanceTo](ue_ue.Character.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[GetTickableWhenPaused](ue_ue.Character.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetTransform](ue_ue.Character.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetVelocity](ue_ue.Character.md#getvelocity)

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

[Character](ue_ue.Character.md).[GetVerticalDistanceTo](ue_ue.Character.md#getverticaldistanceto)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Character](ue_ue.Character.md).[GetWorld](ue_ue.Character.md#getworld)

___

### HasAnyRootMotion

▸ **HasAnyRootMotion**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[HasAnyRootMotion](ue_ue.Character.md#hasanyrootmotion)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[HasAuthority](ue_ue.Character.md#hasauthority)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[IsActorBeingDestroyed](ue_ue.Character.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[IsActorTickEnabled](ue_ue.Character.md#isactortickenabled)

___

### IsBotControlled

▸ **IsBotControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[IsBotControlled](ue_ue.Character.md#isbotcontrolled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[IsChildActor](ue_ue.Character.md#ischildactor)

___

### IsControlled

▸ **IsControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[IsControlled](ue_ue.Character.md#iscontrolled)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[IsEditable](ue_ue.Character.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[IsHiddenEd](ue_ue.Character.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[IsHiddenEdAtStartup](ue_ue.Character.md#ishiddenedatstartup)

___

### IsJumpProvidingForce

▸ **IsJumpProvidingForce**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[IsJumpProvidingForce](ue_ue.Character.md#isjumpprovidingforce)

___

### IsLocallyControlled

▸ **IsLocallyControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[IsLocallyControlled](ue_ue.Character.md#islocallycontrolled)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[IsMoveInputIgnored](ue_ue.Character.md#ismoveinputignored)

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

[Character](ue_ue.Character.md).[IsOverlappingActor](ue_ue.Character.md#isoverlappingactor)

___

### IsPawnControlled

▸ **IsPawnControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[IsPawnControlled](ue_ue.Character.md#ispawncontrolled)

___

### IsPlayerControlled

▸ **IsPlayerControlled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[IsPlayerControlled](ue_ue.Character.md#isplayercontrolled)

___

### IsPlayingNetworkedRootMotionMontage

▸ **IsPlayingNetworkedRootMotionMontage**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[IsPlayingNetworkedRootMotionMontage](ue_ue.Character.md#isplayingnetworkedrootmotionmontage)

___

### IsPlayingRootMotion

▸ **IsPlayingRootMotion**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[IsPlayingRootMotion](ue_ue.Character.md#isplayingrootmotion)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Character](ue_ue.Character.md).[IsSelectable](ue_ue.Character.md#isselectable)

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

[Character](ue_ue.Character.md).[IsTemporarilyHiddenInEditor](ue_ue.Character.md#istemporarilyhiddenineditor)

___

### Jump

▸ **Jump**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[Jump](ue_ue.Character.md#jump)

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

[Character](ue_ue.Character.md).[K2_AddActorLocalOffset](ue_ue.Character.md#k2_addactorlocaloffset)

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

[Character](ue_ue.Character.md).[K2_AddActorLocalRotation](ue_ue.Character.md#k2_addactorlocalrotation)

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

[Character](ue_ue.Character.md).[K2_AddActorLocalTransform](ue_ue.Character.md#k2_addactorlocaltransform)

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

[Character](ue_ue.Character.md).[K2_AddActorWorldOffset](ue_ue.Character.md#k2_addactorworldoffset)

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

[Character](ue_ue.Character.md).[K2_AddActorWorldRotation](ue_ue.Character.md#k2_addactorworldrotation)

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

[Character](ue_ue.Character.md).[K2_AddActorWorldTransform](ue_ue.Character.md#k2_addactorworldtransform)

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

[Character](ue_ue.Character.md).[K2_AttachRootComponentTo](ue_ue.Character.md#k2_attachrootcomponentto)

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

[Character](ue_ue.Character.md).[K2_AttachRootComponentToActor](ue_ue.Character.md#k2_attachrootcomponenttoactor)

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

[Character](ue_ue.Character.md).[K2_AttachToActor](ue_ue.Character.md#k2_attachtoactor)

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

[Character](ue_ue.Character.md).[K2_AttachToComponent](ue_ue.Character.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[K2_DestroyActor](ue_ue.Character.md#k2_destroyactor)

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

[Character](ue_ue.Character.md).[K2_DestroyComponent](ue_ue.Character.md#k2_destroycomponent)

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

[Character](ue_ue.Character.md).[K2_DetachFromActor](ue_ue.Character.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Character](ue_ue.Character.md).[K2_GetActorLocation](ue_ue.Character.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Character](ue_ue.Character.md).[K2_GetActorRotation](ue_ue.Character.md#k2_getactorrotation)

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

[Character](ue_ue.Character.md).[K2_GetComponentsByClass](ue_ue.Character.md#k2_getcomponentsbyclass)

___

### K2\_GetMovementInputVector

▸ **K2_GetMovementInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Character](ue_ue.Character.md).[K2_GetMovementInputVector](ue_ue.Character.md#k2_getmovementinputvector)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Character](ue_ue.Character.md).[K2_GetRootComponent](ue_ue.Character.md#k2_getrootcomponent)

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

[Character](ue_ue.Character.md).[K2_OnBecomeViewTarget](ue_ue.Character.md#k2_onbecomeviewtarget)

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

#### Inherited from

[Character](ue_ue.Character.md).[K2_OnEndCrouch](ue_ue.Character.md#k2_onendcrouch)

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

[Character](ue_ue.Character.md).[K2_OnEndViewTarget](ue_ue.Character.md#k2_onendviewtarget)

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

#### Inherited from

[Character](ue_ue.Character.md).[K2_OnMovementModeChanged](ue_ue.Character.md#k2_onmovementmodechanged)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[K2_OnReset](ue_ue.Character.md#k2_onreset)

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

#### Inherited from

[Character](ue_ue.Character.md).[K2_OnStartCrouch](ue_ue.Character.md#k2_onstartcrouch)

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

[Character](ue_ue.Character.md).[K2_SetActorLocation](ue_ue.Character.md#k2_setactorlocation)

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

[Character](ue_ue.Character.md).[K2_SetActorLocationAndRotation](ue_ue.Character.md#k2_setactorlocationandrotation)

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

[Character](ue_ue.Character.md).[K2_SetActorRelativeLocation](ue_ue.Character.md#k2_setactorrelativelocation)

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

[Character](ue_ue.Character.md).[K2_SetActorRelativeRotation](ue_ue.Character.md#k2_setactorrelativerotation)

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

[Character](ue_ue.Character.md).[K2_SetActorRelativeTransform](ue_ue.Character.md#k2_setactorrelativetransform)

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

[Character](ue_ue.Character.md).[K2_SetActorRotation](ue_ue.Character.md#k2_setactorrotation)

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

[Character](ue_ue.Character.md).[K2_SetActorTransform](ue_ue.Character.md#k2_setactortransform)

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

[Character](ue_ue.Character.md).[K2_TeleportTo](ue_ue.Character.md#k2_teleportto)

___

### K2\_UpdateCustomMovement

▸ **K2_UpdateCustomMovement**(`DeltaTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaTime` | `number` |

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[K2_UpdateCustomMovement](ue_ue.Character.md#k2_updatecustommovement)

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

#### Inherited from

[Character](ue_ue.Character.md).[LaunchCharacter](ue_ue.Character.md#launchcharacter)

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

[Character](ue_ue.Character.md).[LaunchPawn](ue_ue.Character.md#launchpawn)

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

[Character](ue_ue.Character.md).[MakeMIDForMaterial](ue_ue.Character.md#makemidformaterial)

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

[Character](ue_ue.Character.md).[MakeNoise](ue_ue.Character.md#makenoise)

___

### OnJumped

▸ **OnJumped**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[OnJumped](ue_ue.Character.md#onjumped)

___

### OnLanded

▸ **OnLanded**(`Hit`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hit` | [`HitResult`](ue_ue.HitResult.md) |

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[OnLanded](ue_ue.Character.md#onlanded)

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

#### Inherited from

[Character](ue_ue.Character.md).[OnLaunched](ue_ue.Character.md#onlaunched)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[OnRep_AttachmentReplication](ue_ue.Character.md#onrep_attachmentreplication)

___

### OnRep\_Controller

▸ **OnRep_Controller**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[OnRep_Controller](ue_ue.Character.md#onrep_controller)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[OnRep_Instigator](ue_ue.Character.md#onrep_instigator)

___

### OnRep\_IsCrouched

▸ **OnRep_IsCrouched**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[OnRep_IsCrouched](ue_ue.Character.md#onrep_iscrouched)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[OnRep_Owner](ue_ue.Character.md#onrep_owner)

___

### OnRep\_PlayerState

▸ **OnRep_PlayerState**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[OnRep_PlayerState](ue_ue.Character.md#onrep_playerstate)

___

### OnRep\_ReplayLastTransformUpdateTimeStamp

▸ **OnRep_ReplayLastTransformUpdateTimeStamp**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[OnRep_ReplayLastTransformUpdateTimeStamp](ue_ue.Character.md#onrep_replaylasttransformupdatetimestamp)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[OnRep_ReplicateMovement](ue_ue.Character.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedBasedMovement

▸ **OnRep_ReplicatedBasedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[OnRep_ReplicatedBasedMovement](ue_ue.Character.md#onrep_replicatedbasedmovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[OnRep_ReplicatedMovement](ue_ue.Character.md#onrep_replicatedmovement)

___

### OnRep\_RootMotion

▸ **OnRep_RootMotion**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[OnRep_RootMotion](ue_ue.Character.md#onrep_rootmotion)

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

#### Inherited from

[Character](ue_ue.Character.md).[OnWalkingOffLedge](ue_ue.Character.md#onwalkingoffledge)

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

[Character](ue_ue.Character.md).[PawnMakeNoise](ue_ue.Character.md#pawnmakenoise)

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

#### Inherited from

[Character](ue_ue.Character.md).[PlayAnimMontage](ue_ue.Character.md#playanimmontage)

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

[Character](ue_ue.Character.md).[PrestreamTextures](ue_ue.Character.md#prestreamtextures)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[ReceiveActorBeginCursorOver](ue_ue.Character.md#receiveactorbegincursorover)

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

[Character](ue_ue.Character.md).[ReceiveActorBeginOverlap](ue_ue.Character.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[ReceiveActorEndCursorOver](ue_ue.Character.md#receiveactorendcursorover)

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

[Character](ue_ue.Character.md).[ReceiveActorEndOverlap](ue_ue.Character.md#receiveactorendoverlap)

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

[Character](ue_ue.Character.md).[ReceiveActorOnClicked](ue_ue.Character.md#receiveactoronclicked)

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

[Character](ue_ue.Character.md).[ReceiveActorOnInputTouchBegin](ue_ue.Character.md#receiveactoroninputtouchbegin)

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

[Character](ue_ue.Character.md).[ReceiveActorOnInputTouchEnd](ue_ue.Character.md#receiveactoroninputtouchend)

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

[Character](ue_ue.Character.md).[ReceiveActorOnInputTouchEnter](ue_ue.Character.md#receiveactoroninputtouchenter)

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

[Character](ue_ue.Character.md).[ReceiveActorOnInputTouchLeave](ue_ue.Character.md#receiveactoroninputtouchleave)

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

[Character](ue_ue.Character.md).[ReceiveActorOnReleased](ue_ue.Character.md#receiveactoronreleased)

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

[Character](ue_ue.Character.md).[ReceiveAnyDamage](ue_ue.Character.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[ReceiveBeginPlay](ue_ue.Character.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[ReceiveDestroyed](ue_ue.Character.md#receivedestroyed)

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

[Character](ue_ue.Character.md).[ReceiveEndPlay](ue_ue.Character.md#receiveendplay)

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

[Character](ue_ue.Character.md).[ReceiveHit](ue_ue.Character.md#receivehit)

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

[Character](ue_ue.Character.md).[ReceivePointDamage](ue_ue.Character.md#receivepointdamage)

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

[Character](ue_ue.Character.md).[ReceivePossessed](ue_ue.Character.md#receivepossessed)

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

[Character](ue_ue.Character.md).[ReceiveRadialDamage](ue_ue.Character.md#receiveradialdamage)

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

[Character](ue_ue.Character.md).[ReceiveTick](ue_ue.Character.md#receivetick)

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

[Character](ue_ue.Character.md).[ReceiveUnpossessed](ue_ue.Character.md#receiveunpossessed)

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

[Character](ue_ue.Character.md).[RemoveTickPrerequisiteActor](ue_ue.Character.md#removetickprerequisiteactor)

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

[Character](ue_ue.Character.md).[RemoveTickPrerequisiteComponent](ue_ue.Character.md#removetickprerequisitecomponent)

___

### RootMotionDebugClientPrintOnScreen

▸ **RootMotionDebugClientPrintOnScreen**(`InString`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InString` | `string` |

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[RootMotionDebugClientPrintOnScreen](ue_ue.Character.md#rootmotiondebugclientprintonscreen)

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

#### Inherited from

[Character](ue_ue.Character.md).[ServerMove](ue_ue.Character.md#servermove)

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

#### Inherited from

[Character](ue_ue.Character.md).[ServerMoveDual](ue_ue.Character.md#servermovedual)

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

#### Inherited from

[Character](ue_ue.Character.md).[ServerMoveDualHybridRootMotion](ue_ue.Character.md#servermovedualhybridrootmotion)

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

#### Inherited from

[Character](ue_ue.Character.md).[ServerMoveDualNoBase](ue_ue.Character.md#servermovedualnobase)

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

#### Inherited from

[Character](ue_ue.Character.md).[ServerMoveNoBase](ue_ue.Character.md#servermovenobase)

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

#### Inherited from

[Character](ue_ue.Character.md).[ServerMoveOld](ue_ue.Character.md#servermoveold)

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

[Character](ue_ue.Character.md).[SetActorEnableCollision](ue_ue.Character.md#setactorenablecollision)

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

[Character](ue_ue.Character.md).[SetActorHiddenInGame](ue_ue.Character.md#setactorhiddeningame)

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

[Character](ue_ue.Character.md).[SetActorLabel](ue_ue.Character.md#setactorlabel)

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

[Character](ue_ue.Character.md).[SetActorRelativeScale3D](ue_ue.Character.md#setactorrelativescale3d)

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

[Character](ue_ue.Character.md).[SetActorScale3D](ue_ue.Character.md#setactorscale3d)

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

[Character](ue_ue.Character.md).[SetActorTickEnabled](ue_ue.Character.md#setactortickenabled)

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

[Character](ue_ue.Character.md).[SetActorTickInterval](ue_ue.Character.md#setactortickinterval)

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

[Character](ue_ue.Character.md).[SetCanAffectNavigationGeneration](ue_ue.Character.md#setcanaffectnavigationgeneration)

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

[Character](ue_ue.Character.md).[SetFolderPath](ue_ue.Character.md#setfolderpath)

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

[Character](ue_ue.Character.md).[SetIsTemporarilyHiddenInEditor](ue_ue.Character.md#setistemporarilyhiddenineditor)

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

[Character](ue_ue.Character.md).[SetLifeSpan](ue_ue.Character.md#setlifespan)

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

[Character](ue_ue.Character.md).[SetNetDormancy](ue_ue.Character.md#setnetdormancy)

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

[Character](ue_ue.Character.md).[SetOwner](ue_ue.Character.md#setowner)

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

[Character](ue_ue.Character.md).[SetReplicateMovement](ue_ue.Character.md#setreplicatemovement)

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

[Character](ue_ue.Character.md).[SetReplicates](ue_ue.Character.md#setreplicates)

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

[Character](ue_ue.Character.md).[SetTickGroup](ue_ue.Character.md#settickgroup)

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

[Character](ue_ue.Character.md).[SetTickableWhenPaused](ue_ue.Character.md#settickablewhenpaused)

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

[Character](ue_ue.Character.md).[SnapRootComponentTo](ue_ue.Character.md#snaprootcomponentto)

___

### SpawnDefaultController

▸ **SpawnDefaultController**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[SpawnDefaultController](ue_ue.Character.md#spawndefaultcontroller)

___

### StopAnimMontage

▸ **StopAnimMontage**(`AnimMontage?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimMontage?` | [`AnimMontage`](ue_ue.AnimMontage.md) |

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[StopAnimMontage](ue_ue.Character.md#stopanimmontage)

___

### StopJumping

▸ **StopJumping**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[StopJumping](ue_ue.Character.md#stopjumping)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[TearOff](ue_ue.Character.md#tearoff)

___

### UnCrouch

▸ **UnCrouch**(`bClientSimulation?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bClientSimulation?` | `boolean` |

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[UnCrouch](ue_ue.Character.md#uncrouch)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[Character](ue_ue.Character.md).[UserConstructionScript](ue_ue.Character.md#userconstructionscript)

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

[Character](ue_ue.Character.md).[WasRecentlyRendered](ue_ue.Character.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ArchVisCharacter`](ue_ue.ArchVisCharacter.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ArchVisCharacter`](ue_ue.ArchVisCharacter.md)

#### Overrides

[Character](ue_ue.Character.md).[Find](ue_ue.Character.md#find)

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

[Character](ue_ue.Character.md).[GetMovementBaseActor](ue_ue.Character.md#getmovementbaseactor)

___

### Load

▸ `Static` **Load**(`InName`): [`ArchVisCharacter`](ue_ue.ArchVisCharacter.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ArchVisCharacter`](ue_ue.ArchVisCharacter.md)

#### Overrides

[Character](ue_ue.Character.md).[Load](ue_ue.Character.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Character](ue_ue.Character.md).[StaticClass](ue_ue.Character.md#staticclass)
