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

#### Defined in

[ue/ue.d.ts:12267](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12267)

## Properties

### AcknowledgedPawn

• **AcknowledgedPawn**: [`Pawn`](ue_ue.Pawn.md)

#### Defined in

[ue/ue.d.ts:12269](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12269)

___

### ActiveForceFeedbackEffects

• **ActiveForceFeedbackEffects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActiveForceFeedbackEffect`](ue_ue.ActiveForceFeedbackEffect.md)\>

#### Defined in

[ue/ue.d.ts:12286](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12286)

___

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[Controller](ue_ue.Controller.md).[ActorLabel](ue_ue.Controller.md#actorlabel)

#### Defined in

[ue/ue.d.ts:13176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13176)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[AttachmentReplication](ue_ue.Controller.md#attachmentreplication)

#### Defined in

[ue/ue.d.ts:13151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13151)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[AutoReceiveInput](ue_ue.Controller.md#autoreceiveinput)

#### Defined in

[ue/ue.d.ts:13157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13157)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Controller](ue_ue.Controller.md).[BlueprintCreatedComponents](ue_ue.Controller.md#blueprintcreatedcomponents)

#### Defined in

[ue/ue.d.ts:13206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13206)

___

### Character

• **Character**: [`Character`](ue_ue.Character.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[Character](ue_ue.Controller.md#character)

#### Defined in

[ue/ue.d.ts:12461](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12461)

___

### CheatClass

• **CheatClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:12284](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12284)

___

### CheatManager

• **CheatManager**: [`CheatManager`](ue_ue.CheatManager.md)

#### Defined in

[ue/ue.d.ts:12283](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12283)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Controller](ue_ue.Controller.md).[Children](ue_ue.Controller.md#children)

#### Defined in

[ue/ue.d.ts:13166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13166)

___

### ClickEventKeys

• **ClickEventKeys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Key`](ue_ue.Key.md)\>

#### Defined in

[ue/ue.d.ts:12301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12301)

___

### ClientCap

• **ClientCap**: `number`

#### Defined in

[ue/ue.d.ts:12282](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12282)

___

### ControlRotation

• **ControlRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[ControlRotation](ue_ue.Controller.md#controlrotation)

#### Defined in

[ue/ue.d.ts:12463](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12463)

___

### ControllingDirTrackInst

• **ControllingDirTrackInst**: [`InterpTrackInstDirector`](ue_ue.InterpTrackInstDirector.md)

#### Defined in

[ue/ue.d.ts:12270](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12270)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[Controller](ue_ue.Controller.md).[ControllingMatineeActors](ue_ue.Controller.md#controllingmatineeactors)

#### Defined in

[ue/ue.d.ts:13169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13169)

___

### CurrentClickTraceChannel

• **CurrentClickTraceChannel**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Defined in

[ue/ue.d.ts:12305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12305)

___

### CurrentMouseCursor

• **CurrentMouseCursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Defined in

[ue/ue.d.ts:12303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12303)

___

### CurrentTouchInterface

• **CurrentTouchInterface**: [`TouchInterface`](ue_ue.TouchInterface.md)

#### Defined in

[ue/ue.d.ts:12311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12311)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[CustomTimeDilation](ue_ue.Controller.md#customtimedilation)

#### Defined in

[ue/ue.d.ts:13150](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13150)

___

### DefaultClickTraceChannel

• **DefaultClickTraceChannel**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Defined in

[ue/ue.d.ts:12304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12304)

___

### DefaultMouseCursor

• **DefaultMouseCursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Defined in

[ue/ue.d.ts:12302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12302)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.Controller.md#defaultupdateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13146](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13146)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[Controller](ue_ue.Controller.md).[FolderPath](ue_ue.Controller.md#folderpath)

#### Defined in

[ue/ue.d.ts:13177](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13177)

___

### ForceFeedbackScale

• **ForceFeedbackScale**: `number`

#### Defined in

[ue/ue.d.ts:12300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12300)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GroupActor](ue_ue.Controller.md#groupactor)

#### Defined in

[ue/ue.d.ts:13173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13173)

___

### HiddenActors

• **HiddenActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:12277](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12277)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[Controller](ue_ue.Controller.md).[HiddenEditorViews](ue_ue.Controller.md#hiddeneditorviews)

#### Defined in

[ue/ue.d.ts:13175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13175)

___

### HiddenPrimitiveComponents

• **HiddenPrimitiveComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>\>

#### Defined in

[ue/ue.d.ts:12278](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12278)

___

### HitResultTraceDistance

• **HitResultTraceDistance**: `number`

#### Defined in

[ue/ue.d.ts:12306](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12306)

___

### InactiveStateInputComponent

• **InactiveStateInputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Defined in

[ue/ue.d.ts:12309](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12309)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[InitialLifeSpan](ue_ue.Controller.md#initiallifespan)

#### Defined in

[ue/ue.d.ts:13149](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13149)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[InputComponent](ue_ue.Controller.md#inputcomponent)

#### Defined in

[ue/ue.d.ts:13159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13159)

___

### InputPitchScale

• **InputPitchScale**: `number`

#### Defined in

[ue/ue.d.ts:12292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12292)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[InputPriority](ue_ue.Controller.md#inputpriority)

#### Defined in

[ue/ue.d.ts:13158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13158)

___

### InputRollScale

• **InputRollScale**: `number`

#### Defined in

[ue/ue.d.ts:12293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12293)

___

### InputYawScale

• **InputYawScale**: `number`

#### Defined in

[ue/ue.d.ts:12291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12291)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Controller](ue_ue.Controller.md).[InstanceComponents](ue_ue.Controller.md#instancecomponents)

#### Defined in

[ue/ue.d.ts:13205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13205)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[Instigator](ue_ue.Controller.md#instigator)

#### Defined in

[ue/ue.d.ts:13165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13165)

___

### LastCompletedSeamlessTravelCount

• **LastCompletedSeamlessTravelCount**: `number`

#### Defined in

[ue/ue.d.ts:12308](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12308)

___

### LastSpectatorStateSynchTime

• **LastSpectatorStateSynchTime**: `number`

#### Defined in

[ue/ue.d.ts:12279](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12279)

___

### LastSpectatorSyncLocation

• **LastSpectatorSyncLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:12280](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12280)

___

### LastSpectatorSyncRotation

• **LastSpectatorSyncRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:12281](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12281)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[Layers](ue_ue.Controller.md#layers)

#### Defined in

[ue/ue.d.ts:13170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13170)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[MinNetUpdateFrequency](ue_ue.Controller.md#minnetupdatefrequency)

#### Defined in

[ue/ue.d.ts:13163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13163)

___

### MyHUD

• **MyHUD**: [`HUD`](ue_ue.HUD.md)

#### Defined in

[ue/ue.d.ts:12271](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12271)

___

### NetConnection

• **NetConnection**: [`NetConnection`](ue_ue.NetConnection.md)

#### Defined in

[ue/ue.d.ts:12290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12290)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[NetCullDistanceSquared](ue_ue.Controller.md#netculldistancesquared)

#### Defined in

[ue/ue.d.ts:13160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13160)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[NetDormancy](ue_ue.Controller.md#netdormancy)

#### Defined in

[ue/ue.d.ts:13155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13155)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[Controller](ue_ue.Controller.md).[NetDriverName](ue_ue.Controller.md#netdrivername)

#### Defined in

[ue/ue.d.ts:13153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13153)

___

### NetPlayerIndex

• **NetPlayerIndex**: `number`

#### Defined in

[ue/ue.d.ts:12288](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12288)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[NetPriority](ue_ue.Controller.md#netpriority)

#### Defined in

[ue/ue.d.ts:13164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13164)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[NetTag](ue_ue.Controller.md#nettag)

#### Defined in

[ue/ue.d.ts:13161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13161)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[NetUpdateFrequency](ue_ue.Controller.md#netupdatefrequency)

#### Defined in

[ue/ue.d.ts:13162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13162)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnActorBeginOverlap](ue_ue.Controller.md#onactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13192)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnActorEndOverlap](ue_ue.Controller.md#onactorendoverlap)

#### Defined in

[ue/ue.d.ts:13193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13193)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnActorHit](ue_ue.Controller.md#onactorhit)

#### Defined in

[ue/ue.d.ts:13202](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13202)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnBeginCursorOver](ue_ue.Controller.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:13194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13194)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnClicked](ue_ue.Controller.md#onclicked)

#### Defined in

[ue/ue.d.ts:13196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13196)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnDestroyed](ue_ue.Controller.md#ondestroyed)

#### Defined in

[ue/ue.d.ts:13203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13203)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnEndCursorOver](ue_ue.Controller.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:13195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13195)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnEndPlay](ue_ue.Controller.md#onendplay)

#### Defined in

[ue/ue.d.ts:13204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13204)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnInputTouchBegin](ue_ue.Controller.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13198)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnInputTouchEnd](ue_ue.Controller.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:13199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13199)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnInputTouchEnter](ue_ue.Controller.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:13200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13200)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnInputTouchLeave](ue_ue.Controller.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:13201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13201)

___

### OnInstigatedAnyDamage

• **OnInstigatedAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnInstigatedAnyDamage](ue_ue.Controller.md#oninstigatedanydamage)

#### Defined in

[ue/ue.d.ts:12458](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12458)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnReleased](ue_ue.Controller.md#onreleased)

#### Defined in

[ue/ue.d.ts:13197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13197)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnTakeAnyDamage](ue_ue.Controller.md#ontakeanydamage)

#### Defined in

[ue/ue.d.ts:13189](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13189)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnTakePointDamage](ue_ue.Controller.md#ontakepointdamage)

#### Defined in

[ue/ue.d.ts:13190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13190)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[OnTakeRadialDamage](ue_ue.Controller.md#ontakeradialdamage)

#### Defined in

[ue/ue.d.ts:13191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13191)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[Owner](ue_ue.Controller.md#owner)

#### Defined in

[ue/ue.d.ts:13152](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13152)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[Controller](ue_ue.Controller.md).[ParentComponent](ue_ue.Controller.md#parentcomponent)

#### Defined in

[ue/ue.d.ts:13172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13172)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[Controller](ue_ue.Controller.md).[ParentComponentActor](ue_ue.Controller.md#parentcomponentactor)

#### Defined in

[ue/ue.d.ts:13171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13171)

___

### Pawn

• **Pawn**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[Pawn](ue_ue.Controller.md#pawn)

#### Defined in

[ue/ue.d.ts:12460](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12460)

___

### PendingSwapConnection

• **PendingSwapConnection**: [`NetConnection`](ue_ue.NetConnection.md)

#### Defined in

[ue/ue.d.ts:12289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12289)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[PivotOffset](ue_ue.Controller.md#pivotoffset)

#### Defined in

[ue/ue.d.ts:13168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13168)

___

### Player

• **Player**: [`Player`](ue_ue.Player.md)

#### Defined in

[ue/ue.d.ts:12268](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12268)

___

### PlayerCameraManager

• **PlayerCameraManager**: [`PlayerCameraManager`](ue_ue.PlayerCameraManager.md)

#### Defined in

[ue/ue.d.ts:12272](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12272)

___

### PlayerCameraManagerClass

• **PlayerCameraManagerClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:12273](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12273)

___

### PlayerInput

• **PlayerInput**: [`PlayerInput`](ue_ue.PlayerInput.md)

#### Defined in

[ue/ue.d.ts:12285](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12285)

___

### PlayerState

• **PlayerState**: [`PlayerState`](ue_ue.PlayerState.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[PlayerState](ue_ue.Controller.md#playerstate)

#### Defined in

[ue/ue.d.ts:12457](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12457)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[PrimaryActorTick](ue_ue.Controller.md#primaryactortick)

#### Defined in

[ue/ue.d.ts:13115](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13115)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[RemoteRole](ue_ue.Controller.md#remoterole)

#### Defined in

[ue/ue.d.ts:13147](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13147)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[ReplicatedMovement](ue_ue.Controller.md#replicatedmovement)

#### Defined in

[ue/ue.d.ts:13148](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13148)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[Role](ue_ue.Controller.md#role)

#### Defined in

[ue/ue.d.ts:13154](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13154)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[RootComponent](ue_ue.Controller.md#rootcomponent)

#### Defined in

[ue/ue.d.ts:13167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13167)

___

### SeamlessTravelCount

• **SeamlessTravelCount**: `number`

#### Defined in

[ue/ue.d.ts:12307](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12307)

___

### SmoothTargetViewRotationSpeed

• **SmoothTargetViewRotationSpeed**: `number`

#### Defined in

[ue/ue.d.ts:12276](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12276)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[SpawnCollisionHandlingMethod](ue_ue.Controller.md#spawncollisionhandlingmethod)

#### Defined in

[ue/ue.d.ts:13156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13156)

___

### SpawnLocation

• **SpawnLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:12314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12314)

___

### SpectatorPawn

• **SpectatorPawn**: [`SpectatorPawn`](ue_ue.SpectatorPawn.md)

#### Defined in

[ue/ue.d.ts:12312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12312)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[Controller](ue_ue.Controller.md).[SpriteScale](ue_ue.Controller.md#spritescale)

#### Defined in

[ue/ue.d.ts:13174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13174)

___

### StateName

• **StateName**: `string`

#### Inherited from

[Controller](ue_ue.Controller.md).[StateName](ue_ue.Controller.md#statename)

#### Defined in

[ue/ue.d.ts:12459](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12459)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Controller](ue_ue.Controller.md).[Tags](ue_ue.Controller.md#tags)

#### Defined in

[ue/ue.d.ts:13188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13188)

___

### TargetViewRotation

• **TargetViewRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:12275](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12275)

___

### TransformComponent

• **TransformComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[TransformComponent](ue_ue.Controller.md#transformcomponent)

#### Defined in

[ue/ue.d.ts:12462](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12462)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.Controller.md#updateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13145](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13145)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[__tid_Actor__](ue_ue.Controller.md#__tid_actor__)

#### Defined in

[ue/ue.d.ts:13348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13348)

___

### \_\_tid\_Controller\_\_

• **\_\_tid\_Controller\_\_**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[__tid_Controller__](ue_ue.Controller.md#__tid_controller__)

#### Defined in

[ue/ue.d.ts:12497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12497)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[__tid_Object__](ue_ue.Controller.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PlayerController\_\_

• **\_\_tid\_PlayerController\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:12452](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12452)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bActorEnableCollision](ue_ue.Controller.md#bactorenablecollision)

#### Defined in

[ue/ue.d.ts:13143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13143)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bActorIsBeingDestroyed](ue_ue.Controller.md#bactorisbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13144](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13144)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bActorLabelEditable](ue_ue.Controller.md#bactorlabeleditable)

#### Defined in

[ue/ue.d.ts:13183](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13183)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bActorSeamlessTraveled](ue_ue.Controller.md#bactorseamlesstraveled)

#### Defined in

[ue/ue.d.ts:13139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13139)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.Controller.md#ballowreceivetickeventondedicatedserver)

#### Defined in

[ue/ue.d.ts:13142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13142)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bAllowTickBeforeBeginPlay](ue_ue.Controller.md#ballowtickbeforebeginplay)

#### Defined in

[ue/ue.d.ts:13129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13129)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bAlwaysRelevant](ue_ue.Controller.md#balwaysrelevant)

#### Defined in

[ue/ue.d.ts:13120](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13120)

___

### bAttachToPawn

• **bAttachToPawn**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bAttachToPawn](ue_ue.Controller.md#battachtopawn)

#### Defined in

[ue/ue.d.ts:12464](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12464)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bAutoDestroyWhenFinished](ue_ue.Controller.md#bautodestroywhenfinished)

#### Defined in

[ue/ue.d.ts:13130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13130)

___

### bAutoManageActiveCameraTarget

• **bAutoManageActiveCameraTarget**: `boolean`

#### Defined in

[ue/ue.d.ts:12274](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12274)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bBlockInput](ue_ue.Controller.md#bblockinput)

#### Defined in

[ue/ue.d.ts:13131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13131)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bCanBeDamaged](ue_ue.Controller.md#bcanbedamaged)

#### Defined in

[ue/ue.d.ts:13132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13132)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bCanBeInCluster](ue_ue.Controller.md#bcanbeincluster)

#### Defined in

[ue/ue.d.ts:13141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13141)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bCollideWhenPlacing](ue_ue.Controller.md#bcollidewhenplacing)

#### Defined in

[ue/ue.d.ts:13133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13133)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bEditable](ue_ue.Controller.md#beditable)

#### Defined in

[ue/ue.d.ts:13184](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13184)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bEnableAutoLODGeneration](ue_ue.Controller.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:13137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13137)

___

### bEnableClickEvents

• **bEnableClickEvents**: `boolean`

#### Defined in

[ue/ue.d.ts:12295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12295)

___

### bEnableMouseOverEvents

• **bEnableMouseOverEvents**: `boolean`

#### Defined in

[ue/ue.d.ts:12297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12297)

___

### bEnableTouchEvents

• **bEnableTouchEvents**: `boolean`

#### Defined in

[ue/ue.d.ts:12296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12296)

___

### bEnableTouchOverEvents

• **bEnableTouchOverEvents**: `boolean`

#### Defined in

[ue/ue.d.ts:12298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12298)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bExchangedRoles](ue_ue.Controller.md#bexchangedroles)

#### Defined in

[ue/ue.d.ts:13123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13123)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bFindCameraComponentWhenViewTarget](ue_ue.Controller.md#bfindcameracomponentwhenviewtarget)

#### Defined in

[ue/ue.d.ts:13134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13134)

___

### bForceFeedbackEnabled

• **bForceFeedbackEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:12299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12299)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.Controller.md#bgenerateoverlapeventsduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13135)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bHidden](ue_ue.Controller.md#bhidden)

#### Defined in

[ue/ue.d.ts:13116](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13116)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bHiddenEd](ue_ue.Controller.md#bhiddened)

#### Defined in

[ue/ue.d.ts:13178](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13178)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bHiddenEdLayer](ue_ue.Controller.md#bhiddenedlayer)

#### Defined in

[ue/ue.d.ts:13180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13180)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bHiddenEdLevel](ue_ue.Controller.md#bhiddenedlevel)

#### Defined in

[ue/ue.d.ts:13181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13181)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bHiddenEdTemporary](ue_ue.Controller.md#bhiddenedtemporary)

#### Defined in

[ue/ue.d.ts:13187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13187)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bIgnoresOriginShifting](ue_ue.Controller.md#bignoresoriginshifting)

#### Defined in

[ue/ue.d.ts:13136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13136)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bIsEditorOnlyActor](ue_ue.Controller.md#biseditoronlyactor)

#### Defined in

[ue/ue.d.ts:13138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13138)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bIsEditorPreviewActor](ue_ue.Controller.md#biseditorpreviewactor)

#### Defined in

[ue/ue.d.ts:13179](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13179)

___

### bIsLocalPlayerController

• **bIsLocalPlayerController**: `boolean`

#### Defined in

[ue/ue.d.ts:12313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12313)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bListedInSceneOutliner](ue_ue.Controller.md#blistedinsceneoutliner)

#### Defined in

[ue/ue.d.ts:13185](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13185)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bLockLocation](ue_ue.Controller.md#blocklocation)

#### Defined in

[ue/ue.d.ts:13182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13182)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bNetLoadOnClient](ue_ue.Controller.md#bnetloadonclient)

#### Defined in

[ue/ue.d.ts:13124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13124)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bNetStartup](ue_ue.Controller.md#bnetstartup)

#### Defined in

[ue/ue.d.ts:13118](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13118)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bNetTemporary](ue_ue.Controller.md#bnettemporary)

#### Defined in

[ue/ue.d.ts:13117](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13117)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bNetUseOwnerRelevancy](ue_ue.Controller.md#bnetuseownerrelevancy)

#### Defined in

[ue/ue.d.ts:13125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13125)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bOnlyRelevantToOwner](ue_ue.Controller.md#bonlyrelevanttoowner)

#### Defined in

[ue/ue.d.ts:13119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13119)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bOptimizeBPComponentData](ue_ue.Controller.md#boptimizebpcomponentdata)

#### Defined in

[ue/ue.d.ts:13186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13186)

___

### bPlayerIsWaiting

• **bPlayerIsWaiting**: `boolean`

#### Defined in

[ue/ue.d.ts:12287](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12287)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bRelevantForLevelBounds](ue_ue.Controller.md#brelevantforlevelbounds)

#### Defined in

[ue/ue.d.ts:13127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13127)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bRelevantForNetworkReplays](ue_ue.Controller.md#brelevantfornetworkreplays)

#### Defined in

[ue/ue.d.ts:13126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13126)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bReplayRewindable](ue_ue.Controller.md#breplayrewindable)

#### Defined in

[ue/ue.d.ts:13128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13128)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bReplicateMovement](ue_ue.Controller.md#breplicatemovement)

#### Defined in

[ue/ue.d.ts:13121](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13121)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bReplicates](ue_ue.Controller.md#breplicates)

#### Defined in

[ue/ue.d.ts:13140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13140)

___

### bShouldPerformFullTickWhenPaused

• **bShouldPerformFullTickWhenPaused**: `boolean`

#### Defined in

[ue/ue.d.ts:12310](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12310)

___

### bShowMouseCursor

• **bShowMouseCursor**: `boolean`

#### Defined in

[ue/ue.d.ts:12294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12294)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[bTearOff](ue_ue.Controller.md#btearoff)

#### Defined in

[ue/ue.d.ts:13122](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13122)

## Methods

### ActivateTouchInterface

▸ **ActivateTouchInterface**(`NewTouchInterface`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTouchInterface` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TouchInterface`](ue_ue.TouchInterface.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12315)

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

[Controller](ue_ue.Controller.md).[AddComponent](ue_ue.Controller.md#addcomponent)

#### Defined in

[ue/ue.d.ts:13208](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13208)

___

### AddPitchInput

▸ **AddPitchInput**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12316)

___

### AddRollInput

▸ **AddRollInput**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12317](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12317)

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

[Controller](ue_ue.Controller.md).[AddTickPrerequisiteComponent](ue_ue.Controller.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13210](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13210)

___

### AddYawInput

▸ **AddYawInput**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12318](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12318)

___

### Camera

▸ **Camera**(`NewMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMode` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12319)

___

### CanRestartPlayer

▸ **CanRestartPlayer**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:12320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12320)

___

### CastToPlayerController

▸ **CastToPlayerController**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[CastToPlayerController](ue_ue.Controller.md#casttoplayercontroller)

#### Defined in

[ue/ue.d.ts:12465](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12465)

___

### ClearAudioListenerAttenuationOverride

▸ **ClearAudioListenerAttenuationOverride**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12321](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12321)

___

### ClearAudioListenerOverride

▸ **ClearAudioListenerOverride**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12322](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12322)

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

#### Defined in

[ue/ue.d.ts:12323](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12323)

___

### ClientCancelPendingMapChange

▸ **ClientCancelPendingMapChange**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12324](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12324)

___

### ClientCapBandwidth

▸ **ClientCapBandwidth**(`Cap`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Cap` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12325](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12325)

___

### ClientClearCameraLensEffects

▸ **ClientClearCameraLensEffects**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12326](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12326)

___

### ClientCommitMapChange

▸ **ClientCommitMapChange**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12327](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12327)

___

### ClientEnableNetworkVoice

▸ **ClientEnableNetworkVoice**(`bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12328](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12328)

___

### ClientEndOnlineSession

▸ **ClientEndOnlineSession**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12329)

___

### ClientFlushLevelStreaming

▸ **ClientFlushLevelStreaming**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12330](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12330)

___

### ClientForceGarbageCollection

▸ **ClientForceGarbageCollection**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12331)

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

#### Defined in

[ue/ue.d.ts:12332](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12332)

___

### ClientGotoState

▸ **ClientGotoState**(`NewState`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewState` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12333](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12333)

___

### ClientIgnoreLookInput

▸ **ClientIgnoreLookInput**(`bIgnore`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIgnore` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12334](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12334)

___

### ClientIgnoreMoveInput

▸ **ClientIgnoreMoveInput**(`bIgnore`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIgnore` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12335](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12335)

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

#### Defined in

[ue/ue.d.ts:12336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12336)

___

### ClientMutePlayer

▸ **ClientMutePlayer**(`PlayerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerId` | [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12337](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12337)

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

#### Defined in

[ue/ue.d.ts:12338](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12338)

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

#### Defined in

[ue/ue.d.ts:12339](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12339)

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

#### Defined in

[ue/ue.d.ts:12340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12340)

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

#### Defined in

[ue/ue.d.ts:12341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12341)

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

#### Defined in

[ue/ue.d.ts:12342](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12342)

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

#### Defined in

[ue/ue.d.ts:12343](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12343)

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

#### Defined in

[ue/ue.d.ts:12344](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12344)

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

#### Defined in

[ue/ue.d.ts:12345](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12345)

___

### ClientRepObjRef

▸ **ClientRepObjRef**(`Object`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Object` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12346](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12346)

___

### ClientReset

▸ **ClientReset**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12347](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12347)

___

### ClientRestart

▸ **ClientRestart**(`NewPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12348)

___

### ClientRetryClientRestart

▸ **ClientRetryClientRestart**(`NewPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12349](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12349)

___

### ClientReturnToMainMenu

▸ **ClientReturnToMainMenu**(`ReturnReason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ReturnReason` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12350](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12350)

___

### ClientReturnToMainMenuWithTextReason

▸ **ClientReturnToMainMenuWithTextReason**(`ReturnReason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ReturnReason` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12351](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12351)

___

### ClientSetBlockOnAsyncLoading

▸ **ClientSetBlockOnAsyncLoading**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12352](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12352)

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

#### Defined in

[ue/ue.d.ts:12353](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12353)

___

### ClientSetCameraMode

▸ **ClientSetCameraMode**(`NewCamMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewCamMode` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12354](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12354)

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

#### Defined in

[ue/ue.d.ts:12355](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12355)

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

#### Defined in

[ue/ue.d.ts:12356](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12356)

___

### ClientSetHUD

▸ **ClientSetHUD**(`NewHUDClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewHUDClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12357](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12357)

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

#### Defined in

[ue/ue.d.ts:12466](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12466)

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

#### Defined in

[ue/ue.d.ts:12467](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12467)

___

### ClientSetSpectatorWaiting

▸ **ClientSetSpectatorWaiting**(`bWaiting`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bWaiting` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12358](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12358)

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

#### Defined in

[ue/ue.d.ts:12359](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12359)

___

### ClientSpawnCameraLensEffect

▸ **ClientSpawnCameraLensEffect**(`LensEffectEmitterClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LensEffectEmitterClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12360](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12360)

___

### ClientStartOnlineSession

▸ **ClientStartOnlineSession**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12361](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12361)

___

### ClientStopCameraAnim

▸ **ClientStopCameraAnim**(`AnimToStop`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimToStop` | [`$Nullable`](../modules/puerts.md#$nullable)<[`CameraAnim`](ue_ue.CameraAnim.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12362](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12362)

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

#### Defined in

[ue/ue.d.ts:12363](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12363)

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

#### Defined in

[ue/ue.d.ts:12364](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12364)

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

#### Defined in

[ue/ue.d.ts:12365](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12365)

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

#### Defined in

[ue/ue.d.ts:12366](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12366)

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

#### Defined in

[ue/ue.d.ts:12367](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12367)

___

### ClientUnmutePlayer

▸ **ClientUnmutePlayer**(`PlayerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerId` | [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12368](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12368)

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

#### Defined in

[ue/ue.d.ts:12369](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12369)

___

### ClientUpdateMultipleLevelsStreamingStatus

▸ **ClientUpdateMultipleLevelsStreamingStatus**(`LevelStatuses`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LevelStatuses` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UpdateLevelStreamingLevelStatus`](ue_ue.UpdateLevelStreamingLevelStatus.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12370](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12370)

___

### ClientVoiceHandshakeComplete

▸ **ClientVoiceHandshakeComplete**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12371](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12371)

___

### ClientWasKicked

▸ **ClientWasKicked**(`KickReason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KickReason` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12372](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12372)

___

### ConsoleKey

▸ **ConsoleKey**(`Key`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12373](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12373)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12374](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12374)

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

#### Defined in

[ue/ue.d.ts:12375](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12375)

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

[Controller](ue_ue.Controller.md).[DisableInput](ue_ue.Controller.md#disableinput)

#### Defined in

[ue/ue.d.ts:13212](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13212)

___

### EnableCheats

▸ **EnableCheats**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12376](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12376)

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

[Controller](ue_ue.Controller.md).[ExecuteUbergraph](ue_ue.Controller.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### FOV

▸ **FOV**(`NewFOV`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewFOV` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12377](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12377)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[FlushNetDormancy](ue_ue.Controller.md#flushnetdormancy)

#### Defined in

[ue/ue.d.ts:13214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13214)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ForceNetUpdate](ue_ue.Controller.md#forcenetupdate)

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

[Controller](ue_ue.Controller.md).[GetActorBounds](ue_ue.Controller.md#getactorbounds)

#### Defined in

[ue/ue.d.ts:13216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13216)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorEnableCollision](ue_ue.Controller.md#getactorenablecollision)

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

[Controller](ue_ue.Controller.md).[GetActorEyesViewPoint](ue_ue.Controller.md#getactoreyesviewpoint)

#### Defined in

[ue/ue.d.ts:13218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13218)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorForwardVector](ue_ue.Controller.md#getactorforwardvector)

#### Defined in

[ue/ue.d.ts:13219](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13219)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorLabel](ue_ue.Controller.md#getactorlabel)

#### Defined in

[ue/ue.d.ts:13220](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13220)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorRelativeScale3D](ue_ue.Controller.md#getactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13221](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13221)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorRightVector](ue_ue.Controller.md#getactorrightvector)

#### Defined in

[ue/ue.d.ts:13222](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13222)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorScale3D](ue_ue.Controller.md#getactorscale3d)

#### Defined in

[ue/ue.d.ts:13223](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13223)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorTickInterval](ue_ue.Controller.md#getactortickinterval)

#### Defined in

[ue/ue.d.ts:13224](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13224)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorTimeDilation](ue_ue.Controller.md#getactortimedilation)

#### Defined in

[ue/ue.d.ts:13225](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13225)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetActorUpVector](ue_ue.Controller.md#getactorupvector)

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

[Controller](ue_ue.Controller.md).[GetAllChildActors](ue_ue.Controller.md#getallchildactors)

#### Defined in

[ue/ue.d.ts:13227](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13227)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetAttachParentActor](ue_ue.Controller.md#getattachparentactor)

#### Defined in

[ue/ue.d.ts:13229](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13229)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetAttachParentSocketName](ue_ue.Controller.md#getattachparentsocketname)

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

[Controller](ue_ue.Controller.md).[GetAttachedActors](ue_ue.Controller.md#getattachedactors)

#### Defined in

[ue/ue.d.ts:13228](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13228)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetClass](ue_ue.Controller.md#getclass)

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

[Controller](ue_ue.Controller.md).[GetComponentByClass](ue_ue.Controller.md#getcomponentbyclass)

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

[Controller](ue_ue.Controller.md).[GetComponentsByInterface](ue_ue.Controller.md#getcomponentsbyinterface)

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

[Controller](ue_ue.Controller.md).[GetComponentsByTag](ue_ue.Controller.md#getcomponentsbytag)

#### Defined in

[ue/ue.d.ts:13233](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13233)

___

### GetControlRotation

▸ **GetControlRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetControlRotation](ue_ue.Controller.md#getcontrolrotation)

#### Defined in

[ue/ue.d.ts:12468](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12468)

___

### GetDesiredRotation

▸ **GetDesiredRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetDesiredRotation](ue_ue.Controller.md#getdesiredrotation)

#### Defined in

[ue/ue.d.ts:12469](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12469)

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

[Controller](ue_ue.Controller.md).[GetDotProductTo](ue_ue.Controller.md#getdotproductto)

#### Defined in

[ue/ue.d.ts:13235](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13235)

___

### GetFocalLocation

▸ **GetFocalLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:12378](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12378)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetFolderPath](ue_ue.Controller.md#getfolderpath)

#### Defined in

[ue/ue.d.ts:13236](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13236)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetGameTimeSinceCreation](ue_ue.Controller.md#getgametimesincecreation)

#### Defined in

[ue/ue.d.ts:13237](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13237)

___

### GetHUD

▸ **GetHUD**(): [`HUD`](ue_ue.HUD.md)

#### Returns

[`HUD`](ue_ue.HUD.md)

#### Defined in

[ue/ue.d.ts:12385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12385)

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

#### Defined in

[ue/ue.d.ts:12379](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12379)

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

#### Defined in

[ue/ue.d.ts:12380](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12380)

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

#### Defined in

[ue/ue.d.ts:12381](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12381)

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

#### Defined in

[ue/ue.d.ts:12382](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12382)

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

#### Defined in

[ue/ue.d.ts:12383](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12383)

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

#### Defined in

[ue/ue.d.ts:12384](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12384)

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

[Controller](ue_ue.Controller.md).[GetHorizontalDotProductTo](ue_ue.Controller.md#gethorizontaldotproductto)

#### Defined in

[ue/ue.d.ts:13239](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13239)

___

### GetInputAnalogKeyState

▸ **GetInputAnalogKeyState**(`Key`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:12386](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12386)

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

#### Defined in

[ue/ue.d.ts:12387](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12387)

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

[Controller](ue_ue.Controller.md).[GetInputAxisValue](ue_ue.Controller.md#getinputaxisvalue)

#### Defined in

[ue/ue.d.ts:13241](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13241)

___

### GetInputKeyTimeDown

▸ **GetInputKeyTimeDown**(`Key`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:12388](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12388)

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

#### Defined in

[ue/ue.d.ts:12389](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12389)

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

#### Defined in

[ue/ue.d.ts:12390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12390)

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

#### Defined in

[ue/ue.d.ts:12391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12391)

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

#### Defined in

[ue/ue.d.ts:13242](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13242)

___

### GetInputVectorKeyState

▸ **GetInputVectorKeyState**(`Key`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:12392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12392)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetInstigator](ue_ue.Controller.md#getinstigator)

#### Defined in

[ue/ue.d.ts:13243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13243)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetInstigatorController](ue_ue.Controller.md#getinstigatorcontroller)

#### Defined in

[ue/ue.d.ts:13244](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13244)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetLifeSpan](ue_ue.Controller.md#getlifespan)

#### Defined in

[ue/ue.d.ts:13245](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13245)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetLocalRole](ue_ue.Controller.md#getlocalrole)

#### Defined in

[ue/ue.d.ts:13246](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13246)

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

#### Defined in

[ue/ue.d.ts:12393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12393)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetName](ue_ue.Controller.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetOuter](ue_ue.Controller.md#getouter)

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

[Controller](ue_ue.Controller.md).[GetOverlappingActors](ue_ue.Controller.md#getoverlappingactors)

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

[Controller](ue_ue.Controller.md).[GetOverlappingComponents](ue_ue.Controller.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:13248](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13248)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetOwner](ue_ue.Controller.md#getowner)

#### Defined in

[ue/ue.d.ts:13249](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13249)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetParentActor](ue_ue.Controller.md#getparentactor)

#### Defined in

[ue/ue.d.ts:13250](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13250)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetParentComponent](ue_ue.Controller.md#getparentcomponent)

#### Defined in

[ue/ue.d.ts:13251](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13251)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetRemoteRole](ue_ue.Controller.md#getremoterole)

#### Defined in

[ue/ue.d.ts:13252](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13252)

___

### GetSpectatorPawn

▸ **GetSpectatorPawn**(): [`SpectatorPawn`](ue_ue.SpectatorPawn.md)

#### Returns

[`SpectatorPawn`](ue_ue.SpectatorPawn.md)

#### Defined in

[ue/ue.d.ts:12394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12394)

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

#### Defined in

[ue/ue.d.ts:13253](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13253)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[GetTickableWhenPaused](ue_ue.Controller.md#gettickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13254](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13254)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetTransform](ue_ue.Controller.md#gettransform)

#### Defined in

[ue/ue.d.ts:13255](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13255)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetVelocity](ue_ue.Controller.md#getvelocity)

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

[Controller](ue_ue.Controller.md).[GetVerticalDistanceTo](ue_ue.Controller.md#getverticaldistanceto)

#### Defined in

[ue/ue.d.ts:13257](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13257)

___

### GetViewTarget

▸ **GetViewTarget**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetViewTarget](ue_ue.Controller.md#getviewtarget)

#### Defined in

[ue/ue.d.ts:12470](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12470)

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

#### Defined in

[ue/ue.d.ts:12395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12395)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[GetWorld](ue_ue.Controller.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[HasAuthority](ue_ue.Controller.md#hasauthority)

#### Defined in

[ue/ue.d.ts:13258](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13258)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsActorBeingDestroyed](ue_ue.Controller.md#isactorbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13259](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13259)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsActorTickEnabled](ue_ue.Controller.md#isactortickenabled)

#### Defined in

[ue/ue.d.ts:13260](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13260)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsChildActor](ue_ue.Controller.md#ischildactor)

#### Defined in

[ue/ue.d.ts:13261](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13261)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsEditable](ue_ue.Controller.md#iseditable)

#### Defined in

[ue/ue.d.ts:13262](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13262)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsHiddenEd](ue_ue.Controller.md#ishiddened)

#### Defined in

[ue/ue.d.ts:13263](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13263)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsHiddenEdAtStartup](ue_ue.Controller.md#ishiddenedatstartup)

#### Defined in

[ue/ue.d.ts:13264](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13264)

___

### IsInputKeyDown

▸ **IsInputKeyDown**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:12396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12396)

___

### IsLocalController

▸ **IsLocalController**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsLocalController](ue_ue.Controller.md#islocalcontroller)

#### Defined in

[ue/ue.d.ts:12471](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12471)

___

### IsLocalPlayerController

▸ **IsLocalPlayerController**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsLocalPlayerController](ue_ue.Controller.md#islocalplayercontroller)

#### Defined in

[ue/ue.d.ts:12472](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12472)

___

### IsLookInputIgnored

▸ **IsLookInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsLookInputIgnored](ue_ue.Controller.md#islookinputignored)

#### Defined in

[ue/ue.d.ts:12473](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12473)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsMoveInputIgnored](ue_ue.Controller.md#ismoveinputignored)

#### Defined in

[ue/ue.d.ts:12474](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12474)

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

#### Defined in

[ue/ue.d.ts:13265](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13265)

___

### IsPlayerController

▸ **IsPlayerController**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsPlayerController](ue_ue.Controller.md#isplayercontroller)

#### Defined in

[ue/ue.d.ts:12475](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12475)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Controller](ue_ue.Controller.md).[IsSelectable](ue_ue.Controller.md#isselectable)

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

[Controller](ue_ue.Controller.md).[IsTemporarilyHiddenInEditor](ue_ue.Controller.md#istemporarilyhiddenineditor)

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

[Controller](ue_ue.Controller.md).[K2_AddActorLocalOffset](ue_ue.Controller.md#k2_addactorlocaloffset)

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

[Controller](ue_ue.Controller.md).[K2_AddActorLocalRotation](ue_ue.Controller.md#k2_addactorlocalrotation)

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

[Controller](ue_ue.Controller.md).[K2_AddActorLocalTransform](ue_ue.Controller.md#k2_addactorlocaltransform)

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

[Controller](ue_ue.Controller.md).[K2_AddActorWorldOffset](ue_ue.Controller.md#k2_addactorworldoffset)

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

[Controller](ue_ue.Controller.md).[K2_AddActorWorldRotation](ue_ue.Controller.md#k2_addactorworldrotation)

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

[Controller](ue_ue.Controller.md).[K2_AddActorWorldTransform](ue_ue.Controller.md#k2_addactorworldtransform)

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

[Controller](ue_ue.Controller.md).[K2_AttachRootComponentTo](ue_ue.Controller.md#k2_attachrootcomponentto)

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

[Controller](ue_ue.Controller.md).[K2_AttachRootComponentToActor](ue_ue.Controller.md#k2_attachrootcomponenttoactor)

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

[Controller](ue_ue.Controller.md).[K2_AttachToActor](ue_ue.Controller.md#k2_attachtoactor)

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

[Controller](ue_ue.Controller.md).[K2_AttachToComponent](ue_ue.Controller.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:13277](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13277)

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

#### Defined in

[ue/ue.d.ts:12397](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12397)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[K2_DestroyActor](ue_ue.Controller.md#k2_destroyactor)

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

[Controller](ue_ue.Controller.md).[K2_DestroyComponent](ue_ue.Controller.md#k2_destroycomponent)

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

[Controller](ue_ue.Controller.md).[K2_DetachFromActor](ue_ue.Controller.md#k2_detachfromactor)

#### Defined in

[ue/ue.d.ts:13280](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13280)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[K2_GetActorLocation](ue_ue.Controller.md#k2_getactorlocation)

#### Defined in

[ue/ue.d.ts:13281](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13281)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[K2_GetActorRotation](ue_ue.Controller.md#k2_getactorrotation)

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

[Controller](ue_ue.Controller.md).[K2_GetComponentsByClass](ue_ue.Controller.md#k2_getcomponentsbyclass)

#### Defined in

[ue/ue.d.ts:13283](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13283)

___

### K2\_GetPawn

▸ **K2_GetPawn**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[K2_GetPawn](ue_ue.Controller.md#k2_getpawn)

#### Defined in

[ue/ue.d.ts:12476](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12476)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[Controller](ue_ue.Controller.md).[K2_GetRootComponent](ue_ue.Controller.md#k2_getrootcomponent)

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

[Controller](ue_ue.Controller.md).[K2_OnBecomeViewTarget](ue_ue.Controller.md#k2_onbecomeviewtarget)

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

[Controller](ue_ue.Controller.md).[K2_OnEndViewTarget](ue_ue.Controller.md#k2_onendviewtarget)

#### Defined in

[ue/ue.d.ts:13286](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13286)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[K2_OnReset](ue_ue.Controller.md#k2_onreset)

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

[Controller](ue_ue.Controller.md).[K2_SetActorLocation](ue_ue.Controller.md#k2_setactorlocation)

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

[Controller](ue_ue.Controller.md).[K2_SetActorLocationAndRotation](ue_ue.Controller.md#k2_setactorlocationandrotation)

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

[Controller](ue_ue.Controller.md).[K2_SetActorRelativeLocation](ue_ue.Controller.md#k2_setactorrelativelocation)

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

[Controller](ue_ue.Controller.md).[K2_SetActorRelativeRotation](ue_ue.Controller.md#k2_setactorrelativerotation)

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

[Controller](ue_ue.Controller.md).[K2_SetActorRelativeTransform](ue_ue.Controller.md#k2_setactorrelativetransform)

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

[Controller](ue_ue.Controller.md).[K2_SetActorRotation](ue_ue.Controller.md#k2_setactorrotation)

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

[Controller](ue_ue.Controller.md).[K2_SetActorTransform](ue_ue.Controller.md#k2_setactortransform)

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

[Controller](ue_ue.Controller.md).[K2_TeleportTo](ue_ue.Controller.md#k2_teleportto)

#### Defined in

[ue/ue.d.ts:13295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13295)

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

#### Defined in

[ue/ue.d.ts:12477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12477)

___

### LocalTravel

▸ **LocalTravel**(`URL`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `URL` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12398](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12398)

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

[Controller](ue_ue.Controller.md).[MakeNoise](ue_ue.Controller.md#makenoise)

#### Defined in

[ue/ue.d.ts:13297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13297)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[OnRep_AttachmentReplication](ue_ue.Controller.md#onrep_attachmentreplication)

#### Defined in

[ue/ue.d.ts:13298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13298)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[OnRep_Instigator](ue_ue.Controller.md#onrep_instigator)

#### Defined in

[ue/ue.d.ts:13299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13299)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[OnRep_Owner](ue_ue.Controller.md#onrep_owner)

#### Defined in

[ue/ue.d.ts:13300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13300)

___

### OnRep\_Pawn

▸ **OnRep_Pawn**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[OnRep_Pawn](ue_ue.Controller.md#onrep_pawn)

#### Defined in

[ue/ue.d.ts:12478](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12478)

___

### OnRep\_PlayerState

▸ **OnRep_PlayerState**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[OnRep_PlayerState](ue_ue.Controller.md#onrep_playerstate)

#### Defined in

[ue/ue.d.ts:12479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12479)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[OnRep_ReplicateMovement](ue_ue.Controller.md#onrep_replicatemovement)

#### Defined in

[ue/ue.d.ts:13302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13302)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[OnRep_ReplicatedMovement](ue_ue.Controller.md#onrep_replicatedmovement)

#### Defined in

[ue/ue.d.ts:13301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13301)

___

### OnServerStartedVisualLogger

▸ **OnServerStartedVisualLogger**(`bIsLogging`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIsLogging` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12399](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12399)

___

### Pause

▸ **Pause**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12400](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12400)

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

#### Defined in

[ue/ue.d.ts:12401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12401)

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

#### Defined in

[ue/ue.d.ts:12402](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12402)

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

#### Defined in

[ue/ue.d.ts:12480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12480)

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

#### Defined in

[ue/ue.d.ts:13303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13303)

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

#### Defined in

[ue/ue.d.ts:12403](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12403)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ReceiveActorBeginCursorOver](ue_ue.Controller.md#receiveactorbegincursorover)

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

[Controller](ue_ue.Controller.md).[ReceiveActorBeginOverlap](ue_ue.Controller.md#receiveactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13305)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ReceiveActorEndCursorOver](ue_ue.Controller.md#receiveactorendcursorover)

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

[Controller](ue_ue.Controller.md).[ReceiveActorEndOverlap](ue_ue.Controller.md#receiveactorendoverlap)

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

[Controller](ue_ue.Controller.md).[ReceiveActorOnClicked](ue_ue.Controller.md#receiveactoronclicked)

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

[Controller](ue_ue.Controller.md).[ReceiveActorOnInputTouchBegin](ue_ue.Controller.md#receiveactoroninputtouchbegin)

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

[Controller](ue_ue.Controller.md).[ReceiveActorOnInputTouchEnd](ue_ue.Controller.md#receiveactoroninputtouchend)

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

[Controller](ue_ue.Controller.md).[ReceiveActorOnInputTouchEnter](ue_ue.Controller.md#receiveactoroninputtouchenter)

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

[Controller](ue_ue.Controller.md).[ReceiveActorOnInputTouchLeave](ue_ue.Controller.md#receiveactoroninputtouchleave)

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

[Controller](ue_ue.Controller.md).[ReceiveActorOnReleased](ue_ue.Controller.md#receiveactoronreleased)

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

[Controller](ue_ue.Controller.md).[ReceiveAnyDamage](ue_ue.Controller.md#receiveanydamage)

#### Defined in

[ue/ue.d.ts:13314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13314)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ReceiveBeginPlay](ue_ue.Controller.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:13315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13315)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ReceiveDestroyed](ue_ue.Controller.md#receivedestroyed)

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

[Controller](ue_ue.Controller.md).[ReceiveEndPlay](ue_ue.Controller.md#receiveendplay)

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

[Controller](ue_ue.Controller.md).[ReceiveHit](ue_ue.Controller.md#receivehit)

#### Defined in

[ue/ue.d.ts:13318](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13318)

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

#### Defined in

[ue/ue.d.ts:12481](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12481)

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

#### Defined in

[ue/ue.d.ts:13319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13319)

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

#### Defined in

[ue/ue.d.ts:12482](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12482)

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

[Controller](ue_ue.Controller.md).[ReceiveTick](ue_ue.Controller.md#receivetick)

#### Defined in

[ue/ue.d.ts:13321](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13321)

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

#### Defined in

[ue/ue.d.ts:12483](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12483)

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

[Controller](ue_ue.Controller.md).[RemoveTickPrerequisiteComponent](ue_ue.Controller.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13323](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13323)

___

### ResetControllerLightColor

▸ **ResetControllerLightColor**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12404](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12404)

___

### ResetIgnoreInputFlags

▸ **ResetIgnoreInputFlags**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ResetIgnoreInputFlags](ue_ue.Controller.md#resetignoreinputflags)

#### Defined in

[ue/ue.d.ts:12484](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12484)

___

### ResetIgnoreLookInput

▸ **ResetIgnoreLookInput**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ResetIgnoreLookInput](ue_ue.Controller.md#resetignorelookinput)

#### Defined in

[ue/ue.d.ts:12485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12485)

___

### ResetIgnoreMoveInput

▸ **ResetIgnoreMoveInput**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[ResetIgnoreMoveInput](ue_ue.Controller.md#resetignoremoveinput)

#### Defined in

[ue/ue.d.ts:12486](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12486)

___

### RestartLevel

▸ **RestartLevel**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12405](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12405)

___

### SendToConsole

▸ **SendToConsole**(`Command`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Command` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12406](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12406)

___

### ServerAcknowledgePossession

▸ **ServerAcknowledgePossession**(`P`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `P` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12407](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12407)

___

### ServerCamera

▸ **ServerCamera**(`NewMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMode` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12408](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12408)

___

### ServerChangeName

▸ **ServerChangeName**(`S`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `S` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12409](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12409)

___

### ServerCheckClientPossession

▸ **ServerCheckClientPossession**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12410](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12410)

___

### ServerCheckClientPossessionReliable

▸ **ServerCheckClientPossessionReliable**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12411](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12411)

___

### ServerExec

▸ **ServerExec**(`Msg`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Msg` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12412](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12412)

___

### ServerExecRPC

▸ **ServerExecRPC**(`Msg`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Msg` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12413](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12413)

___

### ServerMutePlayer

▸ **ServerMutePlayer**(`PlayerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerId` | [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12414](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12414)

___

### ServerNotifyLoadedWorld

▸ **ServerNotifyLoadedWorld**(`WorldPackageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldPackageName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12415](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12415)

___

### ServerPause

▸ **ServerPause**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12416](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12416)

___

### ServerRestartPlayer

▸ **ServerRestartPlayer**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12417](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12417)

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

#### Defined in

[ue/ue.d.ts:12418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12418)

___

### ServerSetSpectatorWaiting

▸ **ServerSetSpectatorWaiting**(`bWaiting`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bWaiting` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12419](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12419)

___

### ServerShortTimeout

▸ **ServerShortTimeout**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12420](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12420)

___

### ServerToggleAILogging

▸ **ServerToggleAILogging**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12421](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12421)

___

### ServerUnmutePlayer

▸ **ServerUnmutePlayer**(`PlayerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerId` | [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12422](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12422)

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

#### Defined in

[ue/ue.d.ts:12423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12423)

___

### ServerUpdateLevelVisibility

▸ **ServerUpdateLevelVisibility**(`LevelVisibility`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LevelVisibility` | [`UpdateLevelVisibilityLevelInfo`](ue_ue.UpdateLevelVisibilityLevelInfo.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12424](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12424)

___

### ServerUpdateMultipleLevelsVisibility

▸ **ServerUpdateMultipleLevelsVisibility**(`LevelVisibilities`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LevelVisibilities` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UpdateLevelVisibilityLevelInfo`](ue_ue.UpdateLevelVisibilityLevelInfo.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12425](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12425)

___

### ServerVerifyViewTarget

▸ **ServerVerifyViewTarget**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12426](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12426)

___

### ServerViewNextPlayer

▸ **ServerViewNextPlayer**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12427](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12427)

___

### ServerViewPrevPlayer

▸ **ServerViewPrevPlayer**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12428](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12428)

___

### ServerViewSelf

▸ **ServerViewSelf**(`TransitionParams`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TransitionParams` | [`ViewTargetTransitionParams`](ue_ue.ViewTargetTransitionParams.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12429](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12429)

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

[Controller](ue_ue.Controller.md).[SetActorHiddenInGame](ue_ue.Controller.md#setactorhiddeningame)

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

[Controller](ue_ue.Controller.md).[SetActorLabel](ue_ue.Controller.md#setactorlabel)

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

[Controller](ue_ue.Controller.md).[SetActorRelativeScale3D](ue_ue.Controller.md#setactorrelativescale3d)

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

[Controller](ue_ue.Controller.md).[SetActorScale3D](ue_ue.Controller.md#setactorscale3d)

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

[Controller](ue_ue.Controller.md).[SetActorTickEnabled](ue_ue.Controller.md#setactortickenabled)

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

[Controller](ue_ue.Controller.md).[SetActorTickInterval](ue_ue.Controller.md#setactortickinterval)

#### Defined in

[ue/ue.d.ts:13330](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13330)

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

#### Defined in

[ue/ue.d.ts:12430](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12430)

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

#### Defined in

[ue/ue.d.ts:12431](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12431)

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

#### Defined in

[ue/ue.d.ts:12432](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12432)

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

#### Defined in

[ue/ue.d.ts:12487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12487)

___

### SetControllerLightColor

▸ **SetControllerLightColor**(`Color`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Color` | [`Color`](ue_ue_s.Color.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12433](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12433)

___

### SetDisableHaptics

▸ **SetDisableHaptics**(`bNewDisabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewDisabled` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12434](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12434)

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

#### Defined in

[ue/ue.d.ts:13331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13331)

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

#### Defined in

[ue/ue.d.ts:12435](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12435)

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

#### Defined in

[ue/ue.d.ts:12488](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12488)

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

#### Defined in

[ue/ue.d.ts:12489](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12489)

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

#### Defined in

[ue/ue.d.ts:12490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12490)

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

[Controller](ue_ue.Controller.md).[SetLifeSpan](ue_ue.Controller.md#setlifespan)

#### Defined in

[ue/ue.d.ts:13333](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13333)

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

#### Defined in

[ue/ue.d.ts:12436](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12436)

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

#### Defined in

[ue/ue.d.ts:12437](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12437)

___

### SetName

▸ **SetName**(`S`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `S` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12438](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12438)

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

[Controller](ue_ue.Controller.md).[SetOwner](ue_ue.Controller.md#setowner)

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

[Controller](ue_ue.Controller.md).[SetReplicateMovement](ue_ue.Controller.md#setreplicatemovement)

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

[Controller](ue_ue.Controller.md).[SetReplicates](ue_ue.Controller.md#setreplicates)

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

[Controller](ue_ue.Controller.md).[SetTickGroup](ue_ue.Controller.md#settickgroup)

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

[Controller](ue_ue.Controller.md).[SetTickableWhenPaused](ue_ue.Controller.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13338](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13338)

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

#### Defined in

[ue/ue.d.ts:12439](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12439)

___

### SetVirtualJoystickVisibility

▸ **SetVirtualJoystickVisibility**(`bVisible`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bVisible` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12440](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12440)

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

#### Defined in

[ue/ue.d.ts:13340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13340)

___

### StartFire

▸ **StartFire**(`FireModeNum?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FireModeNum?` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12441](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12441)

___

### StopHapticEffect

▸ **StopHapticEffect**(`Hand`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12442](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12442)

___

### StopMovement

▸ **StopMovement**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[StopMovement](ue_ue.Controller.md#stopmovement)

#### Defined in

[ue/ue.d.ts:12491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12491)

___

### SwitchLevel

▸ **SwitchLevel**(`URL`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `URL` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12443](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12443)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[TearOff](ue_ue.Controller.md#tearoff)

#### Defined in

[ue/ue.d.ts:13341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13341)

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

#### Defined in

[ue/ue.d.ts:12444](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12444)

___

### ToggleSpeaking

▸ **ToggleSpeaking**(`bInSpeaking`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInSpeaking` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12445](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12445)

___

### UnPossess

▸ **UnPossess**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[UnPossess](ue_ue.Controller.md#unpossess)

#### Defined in

[ue/ue.d.ts:12492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12492)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[Controller](ue_ue.Controller.md).[UserConstructionScript](ue_ue.Controller.md#userconstructionscript)

#### Defined in

[ue/ue.d.ts:13342](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13342)

___

### WasInputKeyJustPressed

▸ **WasInputKeyJustPressed**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:12446](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12446)

___

### WasInputKeyJustReleased

▸ **WasInputKeyJustReleased**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:12447](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12447)

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

#### Defined in

[ue/ue.d.ts:13343](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13343)

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

#### Defined in

[ue/ue.d.ts:12449](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12449)

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

#### Defined in

[ue/ue.d.ts:12450](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12450)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Controller](ue_ue.Controller.md).[StaticClass](ue_ue.Controller.md#staticclass)

#### Defined in

[ue/ue.d.ts:12448](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12448)
