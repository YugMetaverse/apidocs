[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PlayerController

# Class: PlayerController

[ue/ue](../modules/ue_ue.md).PlayerController

## Hierarchy

- [`Controller`](ue_ue.Controller.md)

  ↳ **`PlayerController`**

  ↳↳ [`DebugCameraController`](ue_ue.DebugCameraController.md)

  ↳↳ [`ARSharedWorldPlayerController`](ue_ue.ARSharedWorldPlayerController.md)

## Table of contents

### Constructors

- [constructor](ue_ue.PlayerController.md#constructor)

### Properties

- [AcknowledgedPawn](ue_ue.PlayerController.md#acknowledgedpawn)
- [ActiveForceFeedbackEffects](ue_ue.PlayerController.md#activeforcefeedbackeffects)
- [ActorLabel](ue_ue.PlayerController.md#actorlabel)
- [AttachmentReplication](ue_ue.PlayerController.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.PlayerController.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.PlayerController.md#blueprintcreatedcomponents)
- [Character](ue_ue.PlayerController.md#character)
- [CheatClass](ue_ue.PlayerController.md#cheatclass)
- [CheatManager](ue_ue.PlayerController.md#cheatmanager)
- [Children](ue_ue.PlayerController.md#children)
- [ClickEventKeys](ue_ue.PlayerController.md#clickeventkeys)
- [ClientCap](ue_ue.PlayerController.md#clientcap)
- [ControlRotation](ue_ue.PlayerController.md#controlrotation)
- [ControllingDirTrackInst](ue_ue.PlayerController.md#controllingdirtrackinst)
- [ControllingMatineeActors](ue_ue.PlayerController.md#controllingmatineeactors)
- [CurrentClickTraceChannel](ue_ue.PlayerController.md#currentclicktracechannel)
- [CurrentMouseCursor](ue_ue.PlayerController.md#currentmousecursor)
- [CurrentTouchInterface](ue_ue.PlayerController.md#currenttouchinterface)
- [CustomTimeDilation](ue_ue.PlayerController.md#customtimedilation)
- [DefaultClickTraceChannel](ue_ue.PlayerController.md#defaultclicktracechannel)
- [DefaultMouseCursor](ue_ue.PlayerController.md#defaultmousecursor)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.PlayerController.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.PlayerController.md#folderpath)
- [ForceFeedbackScale](ue_ue.PlayerController.md#forcefeedbackscale)
- [GroupActor](ue_ue.PlayerController.md#groupactor)
- [HiddenActors](ue_ue.PlayerController.md#hiddenactors)
- [HiddenEditorViews](ue_ue.PlayerController.md#hiddeneditorviews)
- [HiddenPrimitiveComponents](ue_ue.PlayerController.md#hiddenprimitivecomponents)
- [HitResultTraceDistance](ue_ue.PlayerController.md#hitresulttracedistance)
- [InactiveStateInputComponent](ue_ue.PlayerController.md#inactivestateinputcomponent)
- [InitialLifeSpan](ue_ue.PlayerController.md#initiallifespan)
- [InputComponent](ue_ue.PlayerController.md#inputcomponent)
- [InputPitchScale](ue_ue.PlayerController.md#inputpitchscale)
- [InputPriority](ue_ue.PlayerController.md#inputpriority)
- [InputRollScale](ue_ue.PlayerController.md#inputrollscale)
- [InputYawScale](ue_ue.PlayerController.md#inputyawscale)
- [InstanceComponents](ue_ue.PlayerController.md#instancecomponents)
- [Instigator](ue_ue.PlayerController.md#instigator)
- [LastCompletedSeamlessTravelCount](ue_ue.PlayerController.md#lastcompletedseamlesstravelcount)
- [LastSpectatorStateSynchTime](ue_ue.PlayerController.md#lastspectatorstatesynchtime)
- [LastSpectatorSyncLocation](ue_ue.PlayerController.md#lastspectatorsynclocation)
- [LastSpectatorSyncRotation](ue_ue.PlayerController.md#lastspectatorsyncrotation)
- [Layers](ue_ue.PlayerController.md#layers)
- [MinNetUpdateFrequency](ue_ue.PlayerController.md#minnetupdatefrequency)
- [MyHUD](ue_ue.PlayerController.md#myhud)
- [NetConnection](ue_ue.PlayerController.md#netconnection)
- [NetCullDistanceSquared](ue_ue.PlayerController.md#netculldistancesquared)
- [NetDormancy](ue_ue.PlayerController.md#netdormancy)
- [NetDriverName](ue_ue.PlayerController.md#netdrivername)
- [NetPlayerIndex](ue_ue.PlayerController.md#netplayerindex)
- [NetPriority](ue_ue.PlayerController.md#netpriority)
- [NetTag](ue_ue.PlayerController.md#nettag)
- [NetUpdateFrequency](ue_ue.PlayerController.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.PlayerController.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.PlayerController.md#onactorendoverlap)
- [OnActorHit](ue_ue.PlayerController.md#onactorhit)
- [OnBeginCursorOver](ue_ue.PlayerController.md#onbegincursorover)
- [OnClicked](ue_ue.PlayerController.md#onclicked)
- [OnDestroyed](ue_ue.PlayerController.md#ondestroyed)
- [OnEndCursorOver](ue_ue.PlayerController.md#onendcursorover)
- [OnEndPlay](ue_ue.PlayerController.md#onendplay)
- [OnInputTouchBegin](ue_ue.PlayerController.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.PlayerController.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.PlayerController.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.PlayerController.md#oninputtouchleave)
- [OnInstigatedAnyDamage](ue_ue.PlayerController.md#oninstigatedanydamage)
- [OnReleased](ue_ue.PlayerController.md#onreleased)
- [OnTakeAnyDamage](ue_ue.PlayerController.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.PlayerController.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.PlayerController.md#ontakeradialdamage)
- [Owner](ue_ue.PlayerController.md#owner)
- [ParentComponent](ue_ue.PlayerController.md#parentcomponent)
- [ParentComponentActor](ue_ue.PlayerController.md#parentcomponentactor)
- [Pawn](ue_ue.PlayerController.md#pawn)
- [PendingSwapConnection](ue_ue.PlayerController.md#pendingswapconnection)
- [PivotOffset](ue_ue.PlayerController.md#pivotoffset)
- [Player](ue_ue.PlayerController.md#player)
- [PlayerCameraManager](ue_ue.PlayerController.md#playercameramanager)
- [PlayerCameraManagerClass](ue_ue.PlayerController.md#playercameramanagerclass)
- [PlayerInput](ue_ue.PlayerController.md#playerinput)
- [PlayerState](ue_ue.PlayerController.md#playerstate)
- [PrimaryActorTick](ue_ue.PlayerController.md#primaryactortick)
- [RemoteRole](ue_ue.PlayerController.md#remoterole)
- [ReplicatedMovement](ue_ue.PlayerController.md#replicatedmovement)
- [Role](ue_ue.PlayerController.md#role)
- [RootComponent](ue_ue.PlayerController.md#rootcomponent)
- [SeamlessTravelCount](ue_ue.PlayerController.md#seamlesstravelcount)
- [SmoothTargetViewRotationSpeed](ue_ue.PlayerController.md#smoothtargetviewrotationspeed)
- [SpawnCollisionHandlingMethod](ue_ue.PlayerController.md#spawncollisionhandlingmethod)
- [SpawnLocation](ue_ue.PlayerController.md#spawnlocation)
- [SpectatorPawn](ue_ue.PlayerController.md#spectatorpawn)
- [SpriteScale](ue_ue.PlayerController.md#spritescale)
- [StateName](ue_ue.PlayerController.md#statename)
- [Tags](ue_ue.PlayerController.md#tags)
- [TargetViewRotation](ue_ue.PlayerController.md#targetviewrotation)
- [TransformComponent](ue_ue.PlayerController.md#transformcomponent)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.PlayerController.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.PlayerController.md#__tid_actor__)
- [\_\_tid\_Controller\_\_](ue_ue.PlayerController.md#__tid_controller__)
- [\_\_tid\_Object\_\_](ue_ue.PlayerController.md#__tid_object__)
- [\_\_tid\_PlayerController\_\_](ue_ue.PlayerController.md#__tid_playercontroller__)
- [bActorEnableCollision](ue_ue.PlayerController.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.PlayerController.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.PlayerController.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.PlayerController.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.PlayerController.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.PlayerController.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.PlayerController.md#balwaysrelevant)
- [bAttachToPawn](ue_ue.PlayerController.md#battachtopawn)
- [bAutoDestroyWhenFinished](ue_ue.PlayerController.md#bautodestroywhenfinished)
- [bAutoManageActiveCameraTarget](ue_ue.PlayerController.md#bautomanageactivecameratarget)
- [bBlockInput](ue_ue.PlayerController.md#bblockinput)
- [bCanBeDamaged](ue_ue.PlayerController.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.PlayerController.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.PlayerController.md#bcollidewhenplacing)
- [bEditable](ue_ue.PlayerController.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.PlayerController.md#benableautolodgeneration)
- [bEnableClickEvents](ue_ue.PlayerController.md#benableclickevents)
- [bEnableMouseOverEvents](ue_ue.PlayerController.md#benablemouseoverevents)
- [bEnableTouchEvents](ue_ue.PlayerController.md#benabletouchevents)
- [bEnableTouchOverEvents](ue_ue.PlayerController.md#benabletouchoverevents)
- [bExchangedRoles](ue_ue.PlayerController.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.PlayerController.md#bfindcameracomponentwhenviewtarget)
- [bForceFeedbackEnabled](ue_ue.PlayerController.md#bforcefeedbackenabled)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.PlayerController.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.PlayerController.md#bhidden)
- [bHiddenEd](ue_ue.PlayerController.md#bhiddened)
- [bHiddenEdLayer](ue_ue.PlayerController.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.PlayerController.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.PlayerController.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.PlayerController.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.PlayerController.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.PlayerController.md#biseditorpreviewactor)
- [bIsLocalPlayerController](ue_ue.PlayerController.md#bislocalplayercontroller)
- [bListedInSceneOutliner](ue_ue.PlayerController.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.PlayerController.md#blocklocation)
- [bNetLoadOnClient](ue_ue.PlayerController.md#bnetloadonclient)
- [bNetStartup](ue_ue.PlayerController.md#bnetstartup)
- [bNetTemporary](ue_ue.PlayerController.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.PlayerController.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.PlayerController.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.PlayerController.md#boptimizebpcomponentdata)
- [bPlayerIsWaiting](ue_ue.PlayerController.md#bplayeriswaiting)
- [bRelevantForLevelBounds](ue_ue.PlayerController.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.PlayerController.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.PlayerController.md#breplayrewindable)
- [bReplicateMovement](ue_ue.PlayerController.md#breplicatemovement)
- [bReplicates](ue_ue.PlayerController.md#breplicates)
- [bShouldPerformFullTickWhenPaused](ue_ue.PlayerController.md#bshouldperformfulltickwhenpaused)
- [bShowMouseCursor](ue_ue.PlayerController.md#bshowmousecursor)
- [bTearOff](ue_ue.PlayerController.md#btearoff)

### Methods

- [ActivateTouchInterface](ue_ue.PlayerController.md#activatetouchinterface)
- [ActorHasTag](ue_ue.PlayerController.md#actorhastag)
- [AddComponent](ue_ue.PlayerController.md#addcomponent)
- [AddPitchInput](ue_ue.PlayerController.md#addpitchinput)
- [AddRollInput](ue_ue.PlayerController.md#addrollinput)
- [AddTickPrerequisiteActor](ue_ue.PlayerController.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PlayerController.md#addtickprerequisitecomponent)
- [AddYawInput](ue_ue.PlayerController.md#addyawinput)
- [Camera](ue_ue.PlayerController.md#camera)
- [CanRestartPlayer](ue_ue.PlayerController.md#canrestartplayer)
- [CastToPlayerController](ue_ue.PlayerController.md#casttoplayercontroller)
- [ClearAudioListenerAttenuationOverride](ue_ue.PlayerController.md#clearaudiolistenerattenuationoverride)
- [ClearAudioListenerOverride](ue_ue.PlayerController.md#clearaudiolisteneroverride)
- [ClientAddTextureStreamingLoc](ue_ue.PlayerController.md#clientaddtexturestreamingloc)
- [ClientCancelPendingMapChange](ue_ue.PlayerController.md#clientcancelpendingmapchange)
- [ClientCapBandwidth](ue_ue.PlayerController.md#clientcapbandwidth)
- [ClientClearCameraLensEffects](ue_ue.PlayerController.md#clientclearcameralenseffects)
- [ClientCommitMapChange](ue_ue.PlayerController.md#clientcommitmapchange)
- [ClientEnableNetworkVoice](ue_ue.PlayerController.md#clientenablenetworkvoice)
- [ClientEndOnlineSession](ue_ue.PlayerController.md#clientendonlinesession)
- [ClientFlushLevelStreaming](ue_ue.PlayerController.md#clientflushlevelstreaming)
- [ClientForceGarbageCollection](ue_ue.PlayerController.md#clientforcegarbagecollection)
- [ClientGameEnded](ue_ue.PlayerController.md#clientgameended)
- [ClientGotoState](ue_ue.PlayerController.md#clientgotostate)
- [ClientIgnoreLookInput](ue_ue.PlayerController.md#clientignorelookinput)
- [ClientIgnoreMoveInput](ue_ue.PlayerController.md#clientignoremoveinput)
- [ClientMessage](ue_ue.PlayerController.md#clientmessage)
- [ClientMutePlayer](ue_ue.PlayerController.md#clientmuteplayer)
- [ClientPlayCameraAnim](ue_ue.PlayerController.md#clientplaycameraanim)
- [ClientPlayCameraShake](ue_ue.PlayerController.md#clientplaycamerashake)
- [ClientPlayForceFeedback\_Internal](ue_ue.PlayerController.md#clientplayforcefeedback_internal)
- [ClientPlaySound](ue_ue.PlayerController.md#clientplaysound)
- [ClientPlaySoundAtLocation](ue_ue.PlayerController.md#clientplaysoundatlocation)
- [ClientPrepareMapChange](ue_ue.PlayerController.md#clientpreparemapchange)
- [ClientPrestreamTextures](ue_ue.PlayerController.md#clientprestreamtextures)
- [ClientReceiveLocalizedMessage](ue_ue.PlayerController.md#clientreceivelocalizedmessage)
- [ClientRepObjRef](ue_ue.PlayerController.md#clientrepobjref)
- [ClientReset](ue_ue.PlayerController.md#clientreset)
- [ClientRestart](ue_ue.PlayerController.md#clientrestart)
- [ClientRetryClientRestart](ue_ue.PlayerController.md#clientretryclientrestart)
- [ClientReturnToMainMenu](ue_ue.PlayerController.md#clientreturntomainmenu)
- [ClientReturnToMainMenuWithTextReason](ue_ue.PlayerController.md#clientreturntomainmenuwithtextreason)
- [ClientSetBlockOnAsyncLoading](ue_ue.PlayerController.md#clientsetblockonasyncloading)
- [ClientSetCameraFade](ue_ue.PlayerController.md#clientsetcamerafade)
- [ClientSetCameraMode](ue_ue.PlayerController.md#clientsetcameramode)
- [ClientSetCinematicMode](ue_ue.PlayerController.md#clientsetcinematicmode)
- [ClientSetForceMipLevelsToBeResident](ue_ue.PlayerController.md#clientsetforcemiplevelstoberesident)
- [ClientSetHUD](ue_ue.PlayerController.md#clientsethud)
- [ClientSetLocation](ue_ue.PlayerController.md#clientsetlocation)
- [ClientSetRotation](ue_ue.PlayerController.md#clientsetrotation)
- [ClientSetSpectatorWaiting](ue_ue.PlayerController.md#clientsetspectatorwaiting)
- [ClientSetViewTarget](ue_ue.PlayerController.md#clientsetviewtarget)
- [ClientSpawnCameraLensEffect](ue_ue.PlayerController.md#clientspawncameralenseffect)
- [ClientStartOnlineSession](ue_ue.PlayerController.md#clientstartonlinesession)
- [ClientStopCameraAnim](ue_ue.PlayerController.md#clientstopcameraanim)
- [ClientStopCameraShake](ue_ue.PlayerController.md#clientstopcamerashake)
- [ClientStopForceFeedback](ue_ue.PlayerController.md#clientstopforcefeedback)
- [ClientTeamMessage](ue_ue.PlayerController.md#clientteammessage)
- [ClientTravel](ue_ue.PlayerController.md#clienttravel)
- [ClientTravelInternal](ue_ue.PlayerController.md#clienttravelinternal)
- [ClientUnmutePlayer](ue_ue.PlayerController.md#clientunmuteplayer)
- [ClientUpdateLevelStreamingStatus](ue_ue.PlayerController.md#clientupdatelevelstreamingstatus)
- [ClientUpdateMultipleLevelsStreamingStatus](ue_ue.PlayerController.md#clientupdatemultiplelevelsstreamingstatus)
- [ClientVoiceHandshakeComplete](ue_ue.PlayerController.md#clientvoicehandshakecomplete)
- [ClientWasKicked](ue_ue.PlayerController.md#clientwaskicked)
- [ConsoleKey](ue_ue.PlayerController.md#consolekey)
- [CreateDefaultSubobject](ue_ue.PlayerController.md#createdefaultsubobject)
- [DeprojectMousePositionToWorld](ue_ue.PlayerController.md#deprojectmousepositiontoworld)
- [DeprojectScreenPositionToWorld](ue_ue.PlayerController.md#deprojectscreenpositiontoworld)
- [DetachRootComponentFromParent](ue_ue.PlayerController.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.PlayerController.md#disableinput)
- [EnableCheats](ue_ue.PlayerController.md#enablecheats)
- [EnableInput](ue_ue.PlayerController.md#enableinput)
- [ExecuteUbergraph](ue_ue.PlayerController.md#executeubergraph)
- [FOV](ue_ue.PlayerController.md#fov)
- [FlushNetDormancy](ue_ue.PlayerController.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.PlayerController.md#forcenetupdate)
- [GetActorBounds](ue_ue.PlayerController.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.PlayerController.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.PlayerController.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.PlayerController.md#getactorforwardvector)
- [GetActorLabel](ue_ue.PlayerController.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.PlayerController.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.PlayerController.md#getactorrightvector)
- [GetActorScale3D](ue_ue.PlayerController.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.PlayerController.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.PlayerController.md#getactortimedilation)
- [GetActorUpVector](ue_ue.PlayerController.md#getactorupvector)
- [GetAllChildActors](ue_ue.PlayerController.md#getallchildactors)
- [GetAttachParentActor](ue_ue.PlayerController.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.PlayerController.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.PlayerController.md#getattachedactors)
- [GetClass](ue_ue.PlayerController.md#getclass)
- [GetComponentByClass](ue_ue.PlayerController.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.PlayerController.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.PlayerController.md#getcomponentsbytag)
- [GetControlRotation](ue_ue.PlayerController.md#getcontrolrotation)
- [GetDesiredRotation](ue_ue.PlayerController.md#getdesiredrotation)
- [GetDistanceTo](ue_ue.PlayerController.md#getdistanceto)
- [GetDotProductTo](ue_ue.PlayerController.md#getdotproductto)
- [GetFocalLocation](ue_ue.PlayerController.md#getfocallocation)
- [GetFolderPath](ue_ue.PlayerController.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.PlayerController.md#getgametimesincecreation)
- [GetHUD](ue_ue.PlayerController.md#gethud)
- [GetHitResultUnderCursor](ue_ue.PlayerController.md#gethitresultundercursor)
- [GetHitResultUnderCursorByChannel](ue_ue.PlayerController.md#gethitresultundercursorbychannel)
- [GetHitResultUnderCursorForObjects](ue_ue.PlayerController.md#gethitresultundercursorforobjects)
- [GetHitResultUnderFinger](ue_ue.PlayerController.md#gethitresultunderfinger)
- [GetHitResultUnderFingerByChannel](ue_ue.PlayerController.md#gethitresultunderfingerbychannel)
- [GetHitResultUnderFingerForObjects](ue_ue.PlayerController.md#gethitresultunderfingerforobjects)
- [GetHorizontalDistanceTo](ue_ue.PlayerController.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.PlayerController.md#gethorizontaldotproductto)
- [GetInputAnalogKeyState](ue_ue.PlayerController.md#getinputanalogkeystate)
- [GetInputAnalogStickState](ue_ue.PlayerController.md#getinputanalogstickstate)
- [GetInputAxisKeyValue](ue_ue.PlayerController.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.PlayerController.md#getinputaxisvalue)
- [GetInputKeyTimeDown](ue_ue.PlayerController.md#getinputkeytimedown)
- [GetInputMotionState](ue_ue.PlayerController.md#getinputmotionstate)
- [GetInputMouseDelta](ue_ue.PlayerController.md#getinputmousedelta)
- [GetInputTouchState](ue_ue.PlayerController.md#getinputtouchstate)
- [GetInputVectorAxisValue](ue_ue.PlayerController.md#getinputvectoraxisvalue)
- [GetInputVectorKeyState](ue_ue.PlayerController.md#getinputvectorkeystate)
- [GetInstigator](ue_ue.PlayerController.md#getinstigator)
- [GetInstigatorController](ue_ue.PlayerController.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.PlayerController.md#getlifespan)
- [GetLocalRole](ue_ue.PlayerController.md#getlocalrole)
- [GetMousePosition](ue_ue.PlayerController.md#getmouseposition)
- [GetName](ue_ue.PlayerController.md#getname)
- [GetOuter](ue_ue.PlayerController.md#getouter)
- [GetOverlappingActors](ue_ue.PlayerController.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.PlayerController.md#getoverlappingcomponents)
- [GetOwner](ue_ue.PlayerController.md#getowner)
- [GetParentActor](ue_ue.PlayerController.md#getparentactor)
- [GetParentComponent](ue_ue.PlayerController.md#getparentcomponent)
- [GetRemoteRole](ue_ue.PlayerController.md#getremoterole)
- [GetSpectatorPawn](ue_ue.PlayerController.md#getspectatorpawn)
- [GetSquaredDistanceTo](ue_ue.PlayerController.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.PlayerController.md#gettickablewhenpaused)
- [GetTransform](ue_ue.PlayerController.md#gettransform)
- [GetVelocity](ue_ue.PlayerController.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.PlayerController.md#getverticaldistanceto)
- [GetViewTarget](ue_ue.PlayerController.md#getviewtarget)
- [GetViewportSize](ue_ue.PlayerController.md#getviewportsize)
- [GetWorld](ue_ue.PlayerController.md#getworld)
- [HasAuthority](ue_ue.PlayerController.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.PlayerController.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.PlayerController.md#isactortickenabled)
- [IsChildActor](ue_ue.PlayerController.md#ischildactor)
- [IsEditable](ue_ue.PlayerController.md#iseditable)
- [IsHiddenEd](ue_ue.PlayerController.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.PlayerController.md#ishiddenedatstartup)
- [IsInputKeyDown](ue_ue.PlayerController.md#isinputkeydown)
- [IsLocalController](ue_ue.PlayerController.md#islocalcontroller)
- [IsLocalPlayerController](ue_ue.PlayerController.md#islocalplayercontroller)
- [IsLookInputIgnored](ue_ue.PlayerController.md#islookinputignored)
- [IsMoveInputIgnored](ue_ue.PlayerController.md#ismoveinputignored)
- [IsOverlappingActor](ue_ue.PlayerController.md#isoverlappingactor)
- [IsPlayerController](ue_ue.PlayerController.md#isplayercontroller)
- [IsSelectable](ue_ue.PlayerController.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.PlayerController.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.PlayerController.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.PlayerController.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.PlayerController.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.PlayerController.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.PlayerController.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.PlayerController.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.PlayerController.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.PlayerController.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.PlayerController.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.PlayerController.md#k2_attachtocomponent)
- [K2\_ClientPlayForceFeedback](ue_ue.PlayerController.md#k2_clientplayforcefeedback)
- [K2\_DestroyActor](ue_ue.PlayerController.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.PlayerController.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.PlayerController.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.PlayerController.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.PlayerController.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.PlayerController.md#k2_getcomponentsbyclass)
- [K2\_GetPawn](ue_ue.PlayerController.md#k2_getpawn)
- [K2\_GetRootComponent](ue_ue.PlayerController.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.PlayerController.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.PlayerController.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.PlayerController.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.PlayerController.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.PlayerController.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.PlayerController.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.PlayerController.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.PlayerController.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.PlayerController.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.PlayerController.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.PlayerController.md#k2_teleportto)
- [LineOfSightTo](ue_ue.PlayerController.md#lineofsightto)
- [LocalTravel](ue_ue.PlayerController.md#localtravel)
- [MakeMIDForMaterial](ue_ue.PlayerController.md#makemidformaterial)
- [MakeNoise](ue_ue.PlayerController.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.PlayerController.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.PlayerController.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.PlayerController.md#onrep_owner)
- [OnRep\_Pawn](ue_ue.PlayerController.md#onrep_pawn)
- [OnRep\_PlayerState](ue_ue.PlayerController.md#onrep_playerstate)
- [OnRep\_ReplicateMovement](ue_ue.PlayerController.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.PlayerController.md#onrep_replicatedmovement)
- [OnServerStartedVisualLogger](ue_ue.PlayerController.md#onserverstartedvisuallogger)
- [Pause](ue_ue.PlayerController.md#pause)
- [PlayDynamicForceFeedback](ue_ue.PlayerController.md#playdynamicforcefeedback)
- [PlayHapticEffect](ue_ue.PlayerController.md#playhapticeffect)
- [Possess](ue_ue.PlayerController.md#possess)
- [PrestreamTextures](ue_ue.PlayerController.md#prestreamtextures)
- [ProjectWorldLocationToScreen](ue_ue.PlayerController.md#projectworldlocationtoscreen)
- [ReceiveActorBeginCursorOver](ue_ue.PlayerController.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.PlayerController.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.PlayerController.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.PlayerController.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.PlayerController.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.PlayerController.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.PlayerController.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.PlayerController.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.PlayerController.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.PlayerController.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.PlayerController.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.PlayerController.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.PlayerController.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.PlayerController.md#receiveendplay)
- [ReceiveHit](ue_ue.PlayerController.md#receivehit)
- [ReceiveInstigatedAnyDamage](ue_ue.PlayerController.md#receiveinstigatedanydamage)
- [ReceivePointDamage](ue_ue.PlayerController.md#receivepointdamage)
- [ReceivePossess](ue_ue.PlayerController.md#receivepossess)
- [ReceiveRadialDamage](ue_ue.PlayerController.md#receiveradialdamage)
- [ReceiveTick](ue_ue.PlayerController.md#receivetick)
- [ReceiveUnPossess](ue_ue.PlayerController.md#receiveunpossess)
- [RemoveTickPrerequisiteActor](ue_ue.PlayerController.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PlayerController.md#removetickprerequisitecomponent)
- [ResetControllerLightColor](ue_ue.PlayerController.md#resetcontrollerlightcolor)
- [ResetIgnoreInputFlags](ue_ue.PlayerController.md#resetignoreinputflags)
- [ResetIgnoreLookInput](ue_ue.PlayerController.md#resetignorelookinput)
- [ResetIgnoreMoveInput](ue_ue.PlayerController.md#resetignoremoveinput)
- [RestartLevel](ue_ue.PlayerController.md#restartlevel)
- [SendToConsole](ue_ue.PlayerController.md#sendtoconsole)
- [ServerAcknowledgePossession](ue_ue.PlayerController.md#serveracknowledgepossession)
- [ServerCamera](ue_ue.PlayerController.md#servercamera)
- [ServerChangeName](ue_ue.PlayerController.md#serverchangename)
- [ServerCheckClientPossession](ue_ue.PlayerController.md#servercheckclientpossession)
- [ServerCheckClientPossessionReliable](ue_ue.PlayerController.md#servercheckclientpossessionreliable)
- [ServerExec](ue_ue.PlayerController.md#serverexec)
- [ServerExecRPC](ue_ue.PlayerController.md#serverexecrpc)
- [ServerMutePlayer](ue_ue.PlayerController.md#servermuteplayer)
- [ServerNotifyLoadedWorld](ue_ue.PlayerController.md#servernotifyloadedworld)
- [ServerPause](ue_ue.PlayerController.md#serverpause)
- [ServerRestartPlayer](ue_ue.PlayerController.md#serverrestartplayer)
- [ServerSetSpectatorLocation](ue_ue.PlayerController.md#serversetspectatorlocation)
- [ServerSetSpectatorWaiting](ue_ue.PlayerController.md#serversetspectatorwaiting)
- [ServerShortTimeout](ue_ue.PlayerController.md#servershorttimeout)
- [ServerToggleAILogging](ue_ue.PlayerController.md#servertoggleailogging)
- [ServerUnmutePlayer](ue_ue.PlayerController.md#serverunmuteplayer)
- [ServerUpdateCamera](ue_ue.PlayerController.md#serverupdatecamera)
- [ServerUpdateLevelVisibility](ue_ue.PlayerController.md#serverupdatelevelvisibility)
- [ServerUpdateMultipleLevelsVisibility](ue_ue.PlayerController.md#serverupdatemultiplelevelsvisibility)
- [ServerVerifyViewTarget](ue_ue.PlayerController.md#serververifyviewtarget)
- [ServerViewNextPlayer](ue_ue.PlayerController.md#serverviewnextplayer)
- [ServerViewPrevPlayer](ue_ue.PlayerController.md#serverviewprevplayer)
- [ServerViewSelf](ue_ue.PlayerController.md#serverviewself)
- [SetActorEnableCollision](ue_ue.PlayerController.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.PlayerController.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.PlayerController.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.PlayerController.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.PlayerController.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.PlayerController.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.PlayerController.md#setactortickinterval)
- [SetAudioListenerAttenuationOverride](ue_ue.PlayerController.md#setaudiolistenerattenuationoverride)
- [SetAudioListenerOverride](ue_ue.PlayerController.md#setaudiolisteneroverride)
- [SetCinematicMode](ue_ue.PlayerController.md#setcinematicmode)
- [SetControlRotation](ue_ue.PlayerController.md#setcontrolrotation)
- [SetControllerLightColor](ue_ue.PlayerController.md#setcontrollerlightcolor)
- [SetDisableHaptics](ue_ue.PlayerController.md#setdisablehaptics)
- [SetFolderPath](ue_ue.PlayerController.md#setfolderpath)
- [SetHapticsByValue](ue_ue.PlayerController.md#sethapticsbyvalue)
- [SetIgnoreLookInput](ue_ue.PlayerController.md#setignorelookinput)
- [SetIgnoreMoveInput](ue_ue.PlayerController.md#setignoremoveinput)
- [SetInitialLocationAndRotation](ue_ue.PlayerController.md#setinitiallocationandrotation)
- [SetIsTemporarilyHiddenInEditor](ue_ue.PlayerController.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.PlayerController.md#setlifespan)
- [SetMouseCursorWidget](ue_ue.PlayerController.md#setmousecursorwidget)
- [SetMouseLocation](ue_ue.PlayerController.md#setmouselocation)
- [SetName](ue_ue.PlayerController.md#setname)
- [SetNetDormancy](ue_ue.PlayerController.md#setnetdormancy)
- [SetOwner](ue_ue.PlayerController.md#setowner)
- [SetReplicateMovement](ue_ue.PlayerController.md#setreplicatemovement)
- [SetReplicates](ue_ue.PlayerController.md#setreplicates)
- [SetTickGroup](ue_ue.PlayerController.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PlayerController.md#settickablewhenpaused)
- [SetViewTargetWithBlend](ue_ue.PlayerController.md#setviewtargetwithblend)
- [SetVirtualJoystickVisibility](ue_ue.PlayerController.md#setvirtualjoystickvisibility)
- [SnapRootComponentTo](ue_ue.PlayerController.md#snaprootcomponentto)
- [StartFire](ue_ue.PlayerController.md#startfire)
- [StopHapticEffect](ue_ue.PlayerController.md#stophapticeffect)
- [StopMovement](ue_ue.PlayerController.md#stopmovement)
- [SwitchLevel](ue_ue.PlayerController.md#switchlevel)
- [TearOff](ue_ue.PlayerController.md#tearoff)
- [TestServerLevelVisibilityChange](ue_ue.PlayerController.md#testserverlevelvisibilitychange)
- [ToggleSpeaking](ue_ue.PlayerController.md#togglespeaking)
- [UnPossess](ue_ue.PlayerController.md#unpossess)
- [UserConstructionScript](ue_ue.PlayerController.md#userconstructionscript)
- [WasInputKeyJustPressed](ue_ue.PlayerController.md#wasinputkeyjustpressed)
- [WasInputKeyJustReleased](ue_ue.PlayerController.md#wasinputkeyjustreleased)
- [WasRecentlyRendered](ue_ue.PlayerController.md#wasrecentlyrendered)
- [Find](ue_ue.PlayerController.md#find)
- [Load](ue_ue.PlayerController.md#load)
- [StaticClass](ue_ue.PlayerController.md#staticclass)

## Constructors

### constructor

• **new PlayerController**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Controller](ue_ue.Controller.md).[constructor](ue_ue.Controller.md#constructor)

## Properties

### AcknowledgedPawn

• **AcknowledgedPawn**: [`Pawn`](ue_ue.Pawn.md)

___

### ActiveForceFeedbackEffects

• **ActiveForceFeedbackEffects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActiveForceFeedbackEffect`](ue_ue.ActiveForceFeedbackEffect.md)\>

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

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Controller](ue_ue.Controller.md).[BlueprintCreatedComponents](ue_ue.Controller.md#blueprintcreatedcomponents)

___

### Character

• **Character**: [`Character`](ue_ue.Character.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[Character](ue_ue.Controller.md#character)

___

### CheatClass

• **CheatClass**: [`Class`](ue_ue.Class.md)

___

### CheatManager

• **CheatManager**: [`CheatManager`](ue_ue.CheatManager.md)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Controller](ue_ue.Controller.md).[Children](ue_ue.Controller.md#children)

___

### ClickEventKeys

• **ClickEventKeys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Key`](ue_ue.Key.md)\>

___

### ClientCap

• **ClientCap**: `number`

___

### ControlRotation

• **ControlRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[ControlRotation](ue_ue.Controller.md#controlrotation)

___

### ControllingDirTrackInst

• **ControllingDirTrackInst**: [`InterpTrackInstDirector`](ue_ue.InterpTrackInstDirector.md)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[Controller](ue_ue.Controller.md).[ControllingMatineeActors](ue_ue.Controller.md#controllingmatineeactors)

___

### CurrentClickTraceChannel

• **CurrentClickTraceChannel**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

___

### CurrentMouseCursor

• **CurrentMouseCursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

___

### CurrentTouchInterface

• **CurrentTouchInterface**: [`TouchInterface`](ue_ue.TouchInterface.md)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[CustomTimeDilation](ue_ue.Controller.md#customtimedilation)

___

### DefaultClickTraceChannel

• **DefaultClickTraceChannel**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

___

### DefaultMouseCursor

• **DefaultMouseCursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

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

### ForceFeedbackScale

• **ForceFeedbackScale**: `number`

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GroupActor](ue_ue.Controller.md#groupactor)

___

### HiddenActors

• **HiddenActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[Controller](ue_ue.Controller.md).[HiddenEditorViews](ue_ue.Controller.md#hiddeneditorviews)

___

### HiddenPrimitiveComponents

• **HiddenPrimitiveComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>\>

___

### HitResultTraceDistance

• **HitResultTraceDistance**: `number`

___

### InactiveStateInputComponent

• **InactiveStateInputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

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

### InputPitchScale

• **InputPitchScale**: `number`

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[InputPriority](ue_ue.Controller.md#inputpriority)

___

### InputRollScale

• **InputRollScale**: `number`

___

### InputYawScale

• **InputYawScale**: `number`

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

### LastCompletedSeamlessTravelCount

• **LastCompletedSeamlessTravelCount**: `number`

___

### LastSpectatorStateSynchTime

• **LastSpectatorStateSynchTime**: `number`

___

### LastSpectatorSyncLocation

• **LastSpectatorSyncLocation**: [`Vector`](ue_ue_s.Vector.md)

___

### LastSpectatorSyncRotation

• **LastSpectatorSyncRotation**: [`Rotator`](ue_ue_s.Rotator.md)

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

### MyHUD

• **MyHUD**: [`HUD`](ue_ue.HUD.md)

___

### NetConnection

• **NetConnection**: [`NetConnection`](ue_ue.NetConnection.md)

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

### NetPlayerIndex

• **NetPlayerIndex**: `number`

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

### Pawn

• **Pawn**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[Pawn](ue_ue.Controller.md#pawn)

___

### PendingSwapConnection

• **PendingSwapConnection**: [`NetConnection`](ue_ue.NetConnection.md)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[PivotOffset](ue_ue.Controller.md#pivotoffset)

___

### Player

• **Player**: [`Player`](ue_ue.Player.md)

___

### PlayerCameraManager

• **PlayerCameraManager**: [`PlayerCameraManager`](ue_ue.PlayerCameraManager.md)

___

### PlayerCameraManagerClass

• **PlayerCameraManagerClass**: [`Class`](ue_ue.Class.md)

___

### PlayerInput

• **PlayerInput**: [`PlayerInput`](ue_ue.PlayerInput.md)

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

### SeamlessTravelCount

• **SeamlessTravelCount**: `number`

___

### SmoothTargetViewRotationSpeed

• **SmoothTargetViewRotationSpeed**: `number`

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[SpawnCollisionHandlingMethod](ue_ue.Controller.md#spawncollisionhandlingmethod)

___

### SpawnLocation

• **SpawnLocation**: [`Vector`](ue_ue_s.Vector.md)

___

### SpectatorPawn

• **SpectatorPawn**: [`SpectatorPawn`](ue_ue.SpectatorPawn.md)

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

### TargetViewRotation

• **TargetViewRotation**: [`Rotator`](ue_ue_s.Rotator.md)

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

### \_\_tid\_PlayerController\_\_

• **\_\_tid\_PlayerController\_\_**: `boolean`

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

### bAutoManageActiveCameraTarget

• **bAutoManageActiveCameraTarget**: `boolean`

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

### bEnableClickEvents

• **bEnableClickEvents**: `boolean`

___

### bEnableMouseOverEvents

• **bEnableMouseOverEvents**: `boolean`

___

### bEnableTouchEvents

• **bEnableTouchEvents**: `boolean`

___

### bEnableTouchOverEvents

• **bEnableTouchOverEvents**: `boolean`

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

### bForceFeedbackEnabled

• **bForceFeedbackEnabled**: `boolean`

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

### bIsLocalPlayerController

• **bIsLocalPlayerController**: `boolean`

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

### bPlayerIsWaiting

• **bPlayerIsWaiting**: `boolean`

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

### bShouldPerformFullTickWhenPaused

• **bShouldPerformFullTickWhenPaused**: `boolean`

___

### bShowMouseCursor

• **bShowMouseCursor**: `boolean`

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bTearOff](ue_ue.Controller.md#btearoff)

## Methods

### ActivateTouchInterface

▸ **ActivateTouchInterface**(`NewTouchInterface`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTouchInterface` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TouchInterface`](ue_ue.TouchInterface.md)\> |

#### Returns

`void`

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

### AddPitchInput

▸ **AddPitchInput**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

___

### AddRollInput

▸ **AddRollInput**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

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

### AddYawInput

▸ **AddYawInput**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

___

### Camera

▸ **Camera**(`NewMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMode` | `string` |

#### Returns

`void`

___

### CanRestartPlayer

▸ **CanRestartPlayer**(): `boolean`

#### Returns

`boolean`

___

### CastToPlayerController

▸ **CastToPlayerController**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[CastToPlayerController](ue_ue.Controller.md#casttoplayercontroller)

___

### ClearAudioListenerAttenuationOverride

▸ **ClearAudioListenerAttenuationOverride**(): `void`

#### Returns

`void`

___

### ClearAudioListenerOverride

▸ **ClearAudioListenerOverride**(): `void`

#### Returns

`void`

___

### ClientAddTextureStreamingLoc

▸ **ClientAddTextureStreamingLoc**(`InLoc`, `Duration`, `bOverrideLocation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLoc` | [`Vector`](ue_ue_s.Vector.md) |
| `Duration` | `number` |
| `bOverrideLocation` | `boolean` |

#### Returns

`void`

___

### ClientCancelPendingMapChange

▸ **ClientCancelPendingMapChange**(): `void`

#### Returns

`void`

___

### ClientCapBandwidth

▸ **ClientCapBandwidth**(`Cap`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Cap` | `number` |

#### Returns

`void`

___

### ClientClearCameraLensEffects

▸ **ClientClearCameraLensEffects**(): `void`

#### Returns

`void`

___

### ClientCommitMapChange

▸ **ClientCommitMapChange**(): `void`

#### Returns

`void`

___

### ClientEnableNetworkVoice

▸ **ClientEnableNetworkVoice**(`bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

#### Returns

`void`

___

### ClientEndOnlineSession

▸ **ClientEndOnlineSession**(): `void`

#### Returns

`void`

___

### ClientFlushLevelStreaming

▸ **ClientFlushLevelStreaming**(): `void`

#### Returns

`void`

___

### ClientForceGarbageCollection

▸ **ClientForceGarbageCollection**(): `void`

#### Returns

`void`

___

### ClientGameEnded

▸ **ClientGameEnded**(`EndGameFocus`, `bIsWinner`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EndGameFocus` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `bIsWinner` | `boolean` |

#### Returns

`void`

___

### ClientGotoState

▸ **ClientGotoState**(`NewState`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewState` | `string` |

#### Returns

`void`

___

### ClientIgnoreLookInput

▸ **ClientIgnoreLookInput**(`bIgnore`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIgnore` | `boolean` |

#### Returns

`void`

___

### ClientIgnoreMoveInput

▸ **ClientIgnoreMoveInput**(`bIgnore`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIgnore` | `boolean` |

#### Returns

`void`

___

### ClientMessage

▸ **ClientMessage**(`S`, `Type`, `MsgLifeTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `S` | `string` |
| `Type` | `string` |
| `MsgLifeTime` | `number` |

#### Returns

`void`

___

### ClientMutePlayer

▸ **ClientMutePlayer**(`PlayerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerId` | [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md) |

#### Returns

`void`

___

### ClientPlayCameraAnim

▸ **ClientPlayCameraAnim**(`AnimToPlay`, `Scale?`, `Rate?`, `BlendInTime?`, `BlendOutTime?`, `bLoop?`, `bRandomStartTime?`, `Space?`, `CustomPlaySpace?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimToPlay` | [`$Nullable`](../modules/puerts.md#$nullable)<[`CameraAnim`](ue_ue.CameraAnim.md)\> |
| `Scale?` | `number` |
| `Rate?` | `number` |
| `BlendInTime?` | `number` |
| `BlendOutTime?` | `number` |
| `bLoop?` | `boolean` |
| `bRandomStartTime?` | `boolean` |
| `Space?` | [`ECameraAnimPlaySpace`](../enums/ue_ue.ECameraAnimPlaySpace.md) |
| `CustomPlaySpace?` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

___

### ClientPlayCameraShake

▸ **ClientPlayCameraShake**(`Shake`, `Scale?`, `PlaySpace?`, `UserPlaySpaceRot?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Shake` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `Scale?` | `number` |
| `PlaySpace?` | [`ECameraAnimPlaySpace`](../enums/ue_ue.ECameraAnimPlaySpace.md) |
| `UserPlaySpaceRot?` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

___

### ClientPlayForceFeedback\_Internal

▸ **ClientPlayForceFeedback_Internal**(`ForceFeedbackEffect`, `Params`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ForceFeedbackEffect` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ForceFeedbackEffect`](ue_ue.ForceFeedbackEffect.md)\> |
| `Params` | [`ForceFeedbackParameters`](ue_ue.ForceFeedbackParameters.md) |

#### Returns

`void`

___

### ClientPlaySound

▸ **ClientPlaySound**(`Sound`, `VolumeMultiplier`, `PitchMultiplier`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Sound` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundBase`](ue_ue.SoundBase.md)\> |
| `VolumeMultiplier` | `number` |
| `PitchMultiplier` | `number` |

#### Returns

`void`

___

### ClientPlaySoundAtLocation

▸ **ClientPlaySoundAtLocation**(`Sound`, `Location`, `VolumeMultiplier`, `PitchMultiplier`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Sound` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundBase`](ue_ue.SoundBase.md)\> |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `VolumeMultiplier` | `number` |
| `PitchMultiplier` | `number` |

#### Returns

`void`

___

### ClientPrepareMapChange

▸ **ClientPrepareMapChange**(`LevelName`, `bFirst`, `bLast`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LevelName` | `string` |
| `bFirst` | `boolean` |
| `bLast` | `boolean` |

#### Returns

`void`

___

### ClientPrestreamTextures

▸ **ClientPrestreamTextures**(`ForcedActor`, `ForceDuration`, `bEnableStreaming`, `CinematicTextureGroups`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ForcedActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `ForceDuration` | `number` |
| `bEnableStreaming` | `boolean` |
| `CinematicTextureGroups` | `number` |

#### Returns

`void`

___

### ClientReceiveLocalizedMessage

▸ **ClientReceiveLocalizedMessage**(`Message`, `Switch`, `RelatedPlayerState_1`, `RelatedPlayerState_2`, `OptionalObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Message` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `Switch` | `number` |
| `RelatedPlayerState_1` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerState`](ue_ue.PlayerState.md)\> |
| `RelatedPlayerState_2` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerState`](ue_ue.PlayerState.md)\> |
| `OptionalObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### ClientRepObjRef

▸ **ClientRepObjRef**(`Object`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Object` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### ClientReset

▸ **ClientReset**(): `void`

#### Returns

`void`

___

### ClientRestart

▸ **ClientRestart**(`NewPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

___

### ClientRetryClientRestart

▸ **ClientRetryClientRestart**(`NewPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

___

### ClientReturnToMainMenu

▸ **ClientReturnToMainMenu**(`ReturnReason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ReturnReason` | `string` |

#### Returns

`void`

___

### ClientReturnToMainMenuWithTextReason

▸ **ClientReturnToMainMenuWithTextReason**(`ReturnReason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ReturnReason` | `string` |

#### Returns

`void`

___

### ClientSetBlockOnAsyncLoading

▸ **ClientSetBlockOnAsyncLoading**(): `void`

#### Returns

`void`

___

### ClientSetCameraFade

▸ **ClientSetCameraFade**(`bEnableFading`, `FadeColor`, `FadeAlpha`, `FadeTime`, `bFadeAudio`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnableFading` | `boolean` |
| `FadeColor` | [`Color`](ue_ue_s.Color.md) |
| `FadeAlpha` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `FadeTime` | `number` |
| `bFadeAudio` | `boolean` |

#### Returns

`void`

___

### ClientSetCameraMode

▸ **ClientSetCameraMode**(`NewCamMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewCamMode` | `string` |

#### Returns

`void`

___

### ClientSetCinematicMode

▸ **ClientSetCinematicMode**(`bInCinematicMode`, `bAffectsMovement`, `bAffectsTurning`, `bAffectsHUD`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInCinematicMode` | `boolean` |
| `bAffectsMovement` | `boolean` |
| `bAffectsTurning` | `boolean` |
| `bAffectsHUD` | `boolean` |

#### Returns

`void`

___

### ClientSetForceMipLevelsToBeResident

▸ **ClientSetForceMipLevelsToBeResident**(`Material`, `ForceDuration`, `CinematicTextureGroups`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `ForceDuration` | `number` |
| `CinematicTextureGroups` | `number` |

#### Returns

`void`

___

### ClientSetHUD

▸ **ClientSetHUD**(`NewHUDClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewHUDClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

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

### ClientSetSpectatorWaiting

▸ **ClientSetSpectatorWaiting**(`bWaiting`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bWaiting` | `boolean` |

#### Returns

`void`

___

### ClientSetViewTarget

▸ **ClientSetViewTarget**(`A`, `TransitionParams`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `TransitionParams` | [`ViewTargetTransitionParams`](ue_ue.ViewTargetTransitionParams.md) |

#### Returns

`void`

___

### ClientSpawnCameraLensEffect

▸ **ClientSpawnCameraLensEffect**(`LensEffectEmitterClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LensEffectEmitterClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

___

### ClientStartOnlineSession

▸ **ClientStartOnlineSession**(): `void`

#### Returns

`void`

___

### ClientStopCameraAnim

▸ **ClientStopCameraAnim**(`AnimToStop`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimToStop` | [`$Nullable`](../modules/puerts.md#$nullable)<[`CameraAnim`](ue_ue.CameraAnim.md)\> |

#### Returns

`void`

___

### ClientStopCameraShake

▸ **ClientStopCameraShake**(`Shake`, `bImmediately?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Shake` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `bImmediately?` | `boolean` |

#### Returns

`void`

___

### ClientStopForceFeedback

▸ **ClientStopForceFeedback**(`ForceFeedbackEffect`, `Tag`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ForceFeedbackEffect` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ForceFeedbackEffect`](ue_ue.ForceFeedbackEffect.md)\> |
| `Tag` | `string` |

#### Returns

`void`

___

### ClientTeamMessage

▸ **ClientTeamMessage**(`SenderPlayerState`, `S`, `Type`, `MsgLifeTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SenderPlayerState` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerState`](ue_ue.PlayerState.md)\> |
| `S` | `string` |
| `Type` | `string` |
| `MsgLifeTime` | `number` |

#### Returns

`void`

___

### ClientTravel

▸ **ClientTravel**(`URL`, `TravelType`, `bSeamless`, `MapPackageGuid`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `URL` | `string` |
| `TravelType` | [`ETravelType`](../enums/ue_ue.ETravelType.md) |
| `bSeamless` | `boolean` |
| `MapPackageGuid` | [`Guid`](ue_ue_s.Guid.md) |

#### Returns

`void`

___

### ClientTravelInternal

▸ **ClientTravelInternal**(`URL`, `TravelType`, `bSeamless`, `MapPackageGuid`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `URL` | `string` |
| `TravelType` | [`ETravelType`](../enums/ue_ue.ETravelType.md) |
| `bSeamless` | `boolean` |
| `MapPackageGuid` | [`Guid`](ue_ue_s.Guid.md) |

#### Returns

`void`

___

### ClientUnmutePlayer

▸ **ClientUnmutePlayer**(`PlayerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerId` | [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md) |

#### Returns

`void`

___

### ClientUpdateLevelStreamingStatus

▸ **ClientUpdateLevelStreamingStatus**(`PackageName`, `bNewShouldBeLoaded`, `bNewShouldBeVisible`, `bNewShouldBlockOnLoad`, `LODIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackageName` | `string` |
| `bNewShouldBeLoaded` | `boolean` |
| `bNewShouldBeVisible` | `boolean` |
| `bNewShouldBlockOnLoad` | `boolean` |
| `LODIndex` | `number` |

#### Returns

`void`

___

### ClientUpdateMultipleLevelsStreamingStatus

▸ **ClientUpdateMultipleLevelsStreamingStatus**(`LevelStatuses`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LevelStatuses` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UpdateLevelStreamingLevelStatus`](ue_ue.UpdateLevelStreamingLevelStatus.md)\> |

#### Returns

`void`

___

### ClientVoiceHandshakeComplete

▸ **ClientVoiceHandshakeComplete**(): `void`

#### Returns

`void`

___

### ClientWasKicked

▸ **ClientWasKicked**(`KickReason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KickReason` | `string` |

#### Returns

`void`

___

### ConsoleKey

▸ **ConsoleKey**(`Key`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

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

[Controller](ue_ue.Controller.md).[CreateDefaultSubobject](ue_ue.Controller.md#createdefaultsubobject)

___

### DeprojectMousePositionToWorld

▸ **DeprojectMousePositionToWorld**(`WorldLocation`, `WorldDirection`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `WorldDirection` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`boolean`

___

### DeprojectScreenPositionToWorld

▸ **DeprojectScreenPositionToWorld**(`ScreenX`, `ScreenY`, `WorldLocation`, `WorldDirection`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ScreenX` | `number` |
| `ScreenY` | `number` |
| `WorldLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `WorldDirection` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`boolean`

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

### EnableCheats

▸ **EnableCheats**(): `void`

#### Returns

`void`

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

### FOV

▸ **FOV**(`NewFOV`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewFOV` | `number` |

#### Returns

`void`

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

### GetFocalLocation

▸ **GetFocalLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

### GetHUD

▸ **GetHUD**(): [`HUD`](ue_ue.HUD.md)

#### Returns

[`HUD`](ue_ue.HUD.md)

___

### GetHitResultUnderCursor

▸ **GetHitResultUnderCursor**(`TraceChannel`, `bTraceComplex`, `HitResult`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TraceChannel` | [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md) |
| `bTraceComplex` | `boolean` |
| `HitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |

#### Returns

`boolean`

___

### GetHitResultUnderCursorByChannel

▸ **GetHitResultUnderCursorByChannel**(`TraceChannel`, `bTraceComplex`, `HitResult`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TraceChannel` | [`ETraceTypeQuery`](../enums/ue_ue.ETraceTypeQuery.md) |
| `bTraceComplex` | `boolean` |
| `HitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |

#### Returns

`boolean`

___

### GetHitResultUnderCursorForObjects

▸ **GetHitResultUnderCursorForObjects**(`ObjectTypes`, `bTraceComplex`, `HitResult`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ObjectTypes` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EObjectTypeQuery`](../enums/ue_ue.EObjectTypeQuery.md)\> |
| `bTraceComplex` | `boolean` |
| `HitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |

#### Returns

`boolean`

___

### GetHitResultUnderFinger

▸ **GetHitResultUnderFinger**(`FingerIndex`, `TraceChannel`, `bTraceComplex`, `HitResult`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FingerIndex` | [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md) |
| `TraceChannel` | [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md) |
| `bTraceComplex` | `boolean` |
| `HitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |

#### Returns

`boolean`

___

### GetHitResultUnderFingerByChannel

▸ **GetHitResultUnderFingerByChannel**(`FingerIndex`, `TraceChannel`, `bTraceComplex`, `HitResult`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FingerIndex` | [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md) |
| `TraceChannel` | [`ETraceTypeQuery`](../enums/ue_ue.ETraceTypeQuery.md) |
| `bTraceComplex` | `boolean` |
| `HitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |

#### Returns

`boolean`

___

### GetHitResultUnderFingerForObjects

▸ **GetHitResultUnderFingerForObjects**(`FingerIndex`, `ObjectTypes`, `bTraceComplex`, `HitResult`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FingerIndex` | [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md) |
| `ObjectTypes` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EObjectTypeQuery`](../enums/ue_ue.EObjectTypeQuery.md)\> |
| `bTraceComplex` | `boolean` |
| `HitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |

#### Returns

`boolean`

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

### GetInputAnalogKeyState

▸ **GetInputAnalogKeyState**(`Key`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`number`

___

### GetInputAnalogStickState

▸ **GetInputAnalogStickState**(`WhichStick`, `StickX`, `StickY`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WhichStick` | [`EControllerAnalogStick`](../enums/ue_ue.EControllerAnalogStick.md) |
| `StickX` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `StickY` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

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

### GetInputKeyTimeDown

▸ **GetInputKeyTimeDown**(`Key`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`number`

___

### GetInputMotionState

▸ **GetInputMotionState**(`Tilt`, `RotationRate`, `Gravity`, `Acceleration`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tilt` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `RotationRate` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `Gravity` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `Acceleration` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

___

### GetInputMouseDelta

▸ **GetInputMouseDelta**(`DeltaX`, `DeltaY`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaX` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `DeltaY` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

___

### GetInputTouchState

▸ **GetInputTouchState**(`FingerIndex`, `LocationX`, `LocationY`, `bIsCurrentlyPressed`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FingerIndex` | [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md) |
| `LocationX` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `LocationY` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `bIsCurrentlyPressed` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`void`

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

### GetInputVectorKeyState

▸ **GetInputVectorKeyState**(`Key`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

### GetMousePosition

▸ **GetMousePosition**(`LocationX`, `LocationY`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LocationX` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `LocationY` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`boolean`

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

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetRemoteRole](ue_ue.Controller.md#getremoterole)

___

### GetSpectatorPawn

▸ **GetSpectatorPawn**(): [`SpectatorPawn`](ue_ue.SpectatorPawn.md)

#### Returns

[`SpectatorPawn`](ue_ue.SpectatorPawn.md)

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

### GetViewportSize

▸ **GetViewportSize**(`SizeX`, `SizeY`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SizeX` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `SizeY` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

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

### IsInputKeyDown

▸ **IsInputKeyDown**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

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

### K2\_ClientPlayForceFeedback

▸ **K2_ClientPlayForceFeedback**(`ForceFeedbackEffect`, `Tag`, `bLooping`, `bIgnoreTimeDilation`, `bPlayWhilePaused`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ForceFeedbackEffect` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ForceFeedbackEffect`](ue_ue.ForceFeedbackEffect.md)\> |
| `Tag` | `string` |
| `bLooping` | `boolean` |
| `bIgnoreTimeDilation` | `boolean` |
| `bPlayWhilePaused` | `boolean` |

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

### LocalTravel

▸ **LocalTravel**(`URL`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `URL` | `string` |

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

### OnServerStartedVisualLogger

▸ **OnServerStartedVisualLogger**(`bIsLogging`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIsLogging` | `boolean` |

#### Returns

`void`

___

### Pause

▸ **Pause**(): `void`

#### Returns

`void`

___

### PlayDynamicForceFeedback

▸ **PlayDynamicForceFeedback**(`Intensity`, `Duration`, `bAffectsLeftLarge`, `bAffectsLeftSmall`, `bAffectsRightLarge`, `bAffectsRightSmall`, `Action`, `LatentInfo`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Intensity` | `number` |
| `Duration` | `number` |
| `bAffectsLeftLarge` | `boolean` |
| `bAffectsLeftSmall` | `boolean` |
| `bAffectsRightLarge` | `boolean` |
| `bAffectsRightSmall` | `boolean` |
| `Action` | [`EDynamicForceFeedbackAction`](../enums/ue_ue.EDynamicForceFeedbackAction.md) |
| `LatentInfo` | [`LatentActionInfo`](ue_ue.LatentActionInfo.md) |

#### Returns

`void`

___

### PlayHapticEffect

▸ **PlayHapticEffect**(`HapticEffect`, `Hand`, `Scale?`, `bLoop?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `HapticEffect` | [`$Nullable`](../modules/puerts.md#$nullable)<[`HapticFeedbackEffect_Base`](ue_ue.HapticFeedbackEffect_Base.md)\> |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |
| `Scale?` | `number` |
| `bLoop?` | `boolean` |

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

### ProjectWorldLocationToScreen

▸ **ProjectWorldLocationToScreen**(`WorldLocation`, `ScreenLocation`, `bPlayerViewportRelative?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `ScreenLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\> |
| `bPlayerViewportRelative?` | `boolean` |

#### Returns

`boolean`

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

### ResetControllerLightColor

▸ **ResetControllerLightColor**(): `void`

#### Returns

`void`

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

### RestartLevel

▸ **RestartLevel**(): `void`

#### Returns

`void`

___

### SendToConsole

▸ **SendToConsole**(`Command`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Command` | `string` |

#### Returns

`void`

___

### ServerAcknowledgePossession

▸ **ServerAcknowledgePossession**(`P`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `P` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

___

### ServerCamera

▸ **ServerCamera**(`NewMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMode` | `string` |

#### Returns

`void`

___

### ServerChangeName

▸ **ServerChangeName**(`S`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `S` | `string` |

#### Returns

`void`

___

### ServerCheckClientPossession

▸ **ServerCheckClientPossession**(): `void`

#### Returns

`void`

___

### ServerCheckClientPossessionReliable

▸ **ServerCheckClientPossessionReliable**(): `void`

#### Returns

`void`

___

### ServerExec

▸ **ServerExec**(`Msg`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Msg` | `string` |

#### Returns

`void`

___

### ServerExecRPC

▸ **ServerExecRPC**(`Msg`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Msg` | `string` |

#### Returns

`void`

___

### ServerMutePlayer

▸ **ServerMutePlayer**(`PlayerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerId` | [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md) |

#### Returns

`void`

___

### ServerNotifyLoadedWorld

▸ **ServerNotifyLoadedWorld**(`WorldPackageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldPackageName` | `string` |

#### Returns

`void`

___

### ServerPause

▸ **ServerPause**(): `void`

#### Returns

`void`

___

### ServerRestartPlayer

▸ **ServerRestartPlayer**(): `void`

#### Returns

`void`

___

### ServerSetSpectatorLocation

▸ **ServerSetSpectatorLocation**(`NewLoc`, `NewRot`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLoc` | [`Vector`](ue_ue_s.Vector.md) |
| `NewRot` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

___

### ServerSetSpectatorWaiting

▸ **ServerSetSpectatorWaiting**(`bWaiting`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bWaiting` | `boolean` |

#### Returns

`void`

___

### ServerShortTimeout

▸ **ServerShortTimeout**(): `void`

#### Returns

`void`

___

### ServerToggleAILogging

▸ **ServerToggleAILogging**(): `void`

#### Returns

`void`

___

### ServerUnmutePlayer

▸ **ServerUnmutePlayer**(`PlayerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerId` | [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md) |

#### Returns

`void`

___

### ServerUpdateCamera

▸ **ServerUpdateCamera**(`CamLoc`, `CamPitchAndYaw`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `CamLoc` | [`Vector_NetQuantize`](ue_ue.Vector_NetQuantize.md) |
| `CamPitchAndYaw` | `number` |

#### Returns

`void`

___

### ServerUpdateLevelVisibility

▸ **ServerUpdateLevelVisibility**(`LevelVisibility`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LevelVisibility` | [`UpdateLevelVisibilityLevelInfo`](ue_ue.UpdateLevelVisibilityLevelInfo.md) |

#### Returns

`void`

___

### ServerUpdateMultipleLevelsVisibility

▸ **ServerUpdateMultipleLevelsVisibility**(`LevelVisibilities`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LevelVisibilities` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UpdateLevelVisibilityLevelInfo`](ue_ue.UpdateLevelVisibilityLevelInfo.md)\> |

#### Returns

`void`

___

### ServerVerifyViewTarget

▸ **ServerVerifyViewTarget**(): `void`

#### Returns

`void`

___

### ServerViewNextPlayer

▸ **ServerViewNextPlayer**(): `void`

#### Returns

`void`

___

### ServerViewPrevPlayer

▸ **ServerViewPrevPlayer**(): `void`

#### Returns

`void`

___

### ServerViewSelf

▸ **ServerViewSelf**(`TransitionParams`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TransitionParams` | [`ViewTargetTransitionParams`](ue_ue.ViewTargetTransitionParams.md) |

#### Returns

`void`

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

### SetAudioListenerAttenuationOverride

▸ **SetAudioListenerAttenuationOverride**(`AttachToComponent`, `AttenuationLocationOVerride`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AttachToComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `AttenuationLocationOVerride` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### SetAudioListenerOverride

▸ **SetAudioListenerOverride**(`AttachToComponent`, `Location`, `Rotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AttachToComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

___

### SetCinematicMode

▸ **SetCinematicMode**(`bInCinematicMode`, `bHidePlayer`, `bAffectsHUD`, `bAffectsMovement`, `bAffectsTurning`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInCinematicMode` | `boolean` |
| `bHidePlayer` | `boolean` |
| `bAffectsHUD` | `boolean` |
| `bAffectsMovement` | `boolean` |
| `bAffectsTurning` | `boolean` |

#### Returns

`void`

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

### SetControllerLightColor

▸ **SetControllerLightColor**(`Color`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Color` | [`Color`](ue_ue_s.Color.md) |

#### Returns

`void`

___

### SetDisableHaptics

▸ **SetDisableHaptics**(`bNewDisabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewDisabled` | `boolean` |

#### Returns

`void`

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

### SetHapticsByValue

▸ **SetHapticsByValue**(`Frequency`, `Amplitude`, `Hand`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Frequency` | `number` |
| `Amplitude` | `number` |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |

#### Returns

`void`

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

### SetMouseCursorWidget

▸ **SetMouseCursorWidget**(`Cursor`, `CursorWidget`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Cursor` | [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md) |
| `CursorWidget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\> |

#### Returns

`void`

___

### SetMouseLocation

▸ **SetMouseLocation**(`X`, `Y`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `X` | `number` |
| `Y` | `number` |

#### Returns

`void`

___

### SetName

▸ **SetName**(`S`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `S` | `string` |

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

### SetViewTargetWithBlend

▸ **SetViewTargetWithBlend**(`NewViewTarget`, `BlendTime?`, `BlendFunc?`, `BlendExp?`, `bLockOutgoing?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewViewTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `BlendTime?` | `number` |
| `BlendFunc?` | [`EViewTargetBlendFunction`](../enums/ue_ue.EViewTargetBlendFunction.md) |
| `BlendExp?` | `number` |
| `bLockOutgoing?` | `boolean` |

#### Returns

`void`

___

### SetVirtualJoystickVisibility

▸ **SetVirtualJoystickVisibility**(`bVisible`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bVisible` | `boolean` |

#### Returns

`void`

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

### StartFire

▸ **StartFire**(`FireModeNum?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FireModeNum?` | `number` |

#### Returns

`void`

___

### StopHapticEffect

▸ **StopHapticEffect**(`Hand`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |

#### Returns

`void`

___

### StopMovement

▸ **StopMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[StopMovement](ue_ue.Controller.md#stopmovement)

___

### SwitchLevel

▸ **SwitchLevel**(`URL`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `URL` | `string` |

#### Returns

`void`

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[TearOff](ue_ue.Controller.md#tearoff)

___

### TestServerLevelVisibilityChange

▸ **TestServerLevelVisibilityChange**(`PackageName`, `FileName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackageName` | `string` |
| `FileName` | `string` |

#### Returns

`void`

___

### ToggleSpeaking

▸ **ToggleSpeaking**(`bInSpeaking`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInSpeaking` | `boolean` |

#### Returns

`void`

___

### UnPossess

▸ **UnPossess**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[UnPossess](ue_ue.Controller.md#unpossess)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[UserConstructionScript](ue_ue.Controller.md#userconstructionscript)

___

### WasInputKeyJustPressed

▸ **WasInputKeyJustPressed**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

___

### WasInputKeyJustReleased

▸ **WasInputKeyJustReleased**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PlayerController`](ue_ue.PlayerController.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Overrides

[Controller](ue_ue.Controller.md).[Find](ue_ue.Controller.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PlayerController`](ue_ue.PlayerController.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Overrides

[Controller](ue_ue.Controller.md).[Load](ue_ue.Controller.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Controller](ue_ue.Controller.md).[StaticClass](ue_ue.Controller.md#staticclass)
