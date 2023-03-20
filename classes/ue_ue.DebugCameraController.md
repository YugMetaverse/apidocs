[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DebugCameraController

# Class: DebugCameraController

[ue/ue](../modules/ue_ue.md).DebugCameraController

## Hierarchy

- [`PlayerController`](ue_ue.PlayerController.md)

  ↳ **`DebugCameraController`**

  ↳↳ [`VisualLoggerCameraController`](ue_ue.VisualLoggerCameraController.md)

## Table of contents

### Constructors

- [constructor](ue_ue.DebugCameraController.md#constructor)

### Properties

- [AcknowledgedPawn](ue_ue.DebugCameraController.md#acknowledgedpawn)
- [ActiveForceFeedbackEffects](ue_ue.DebugCameraController.md#activeforcefeedbackeffects)
- [ActorLabel](ue_ue.DebugCameraController.md#actorlabel)
- [AttachmentReplication](ue_ue.DebugCameraController.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.DebugCameraController.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.DebugCameraController.md#blueprintcreatedcomponents)
- [Character](ue_ue.DebugCameraController.md#character)
- [CheatClass](ue_ue.DebugCameraController.md#cheatclass)
- [CheatManager](ue_ue.DebugCameraController.md#cheatmanager)
- [Children](ue_ue.DebugCameraController.md#children)
- [ClickEventKeys](ue_ue.DebugCameraController.md#clickeventkeys)
- [ClientCap](ue_ue.DebugCameraController.md#clientcap)
- [ControlRotation](ue_ue.DebugCameraController.md#controlrotation)
- [ControllingDirTrackInst](ue_ue.DebugCameraController.md#controllingdirtrackinst)
- [ControllingMatineeActors](ue_ue.DebugCameraController.md#controllingmatineeactors)
- [CurrentClickTraceChannel](ue_ue.DebugCameraController.md#currentclicktracechannel)
- [CurrentMouseCursor](ue_ue.DebugCameraController.md#currentmousecursor)
- [CurrentTouchInterface](ue_ue.DebugCameraController.md#currenttouchinterface)
- [CustomTimeDilation](ue_ue.DebugCameraController.md#customtimedilation)
- [DefaultClickTraceChannel](ue_ue.DebugCameraController.md#defaultclicktracechannel)
- [DefaultMouseCursor](ue_ue.DebugCameraController.md#defaultmousecursor)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.DebugCameraController.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [DrawFrustum](ue_ue.DebugCameraController.md#drawfrustum)
- [FolderPath](ue_ue.DebugCameraController.md#folderpath)
- [ForceFeedbackScale](ue_ue.DebugCameraController.md#forcefeedbackscale)
- [GroupActor](ue_ue.DebugCameraController.md#groupactor)
- [HiddenActors](ue_ue.DebugCameraController.md#hiddenactors)
- [HiddenEditorViews](ue_ue.DebugCameraController.md#hiddeneditorviews)
- [HiddenPrimitiveComponents](ue_ue.DebugCameraController.md#hiddenprimitivecomponents)
- [HitResultTraceDistance](ue_ue.DebugCameraController.md#hitresulttracedistance)
- [InactiveStateInputComponent](ue_ue.DebugCameraController.md#inactivestateinputcomponent)
- [InitialAccel](ue_ue.DebugCameraController.md#initialaccel)
- [InitialDecel](ue_ue.DebugCameraController.md#initialdecel)
- [InitialLifeSpan](ue_ue.DebugCameraController.md#initiallifespan)
- [InitialMaxSpeed](ue_ue.DebugCameraController.md#initialmaxspeed)
- [InputComponent](ue_ue.DebugCameraController.md#inputcomponent)
- [InputPitchScale](ue_ue.DebugCameraController.md#inputpitchscale)
- [InputPriority](ue_ue.DebugCameraController.md#inputpriority)
- [InputRollScale](ue_ue.DebugCameraController.md#inputrollscale)
- [InputYawScale](ue_ue.DebugCameraController.md#inputyawscale)
- [InstanceComponents](ue_ue.DebugCameraController.md#instancecomponents)
- [Instigator](ue_ue.DebugCameraController.md#instigator)
- [LastCompletedSeamlessTravelCount](ue_ue.DebugCameraController.md#lastcompletedseamlesstravelcount)
- [LastSpectatorStateSynchTime](ue_ue.DebugCameraController.md#lastspectatorstatesynchtime)
- [LastSpectatorSyncLocation](ue_ue.DebugCameraController.md#lastspectatorsynclocation)
- [LastSpectatorSyncRotation](ue_ue.DebugCameraController.md#lastspectatorsyncrotation)
- [Layers](ue_ue.DebugCameraController.md#layers)
- [MinNetUpdateFrequency](ue_ue.DebugCameraController.md#minnetupdatefrequency)
- [MyHUD](ue_ue.DebugCameraController.md#myhud)
- [NetConnection](ue_ue.DebugCameraController.md#netconnection)
- [NetCullDistanceSquared](ue_ue.DebugCameraController.md#netculldistancesquared)
- [NetDormancy](ue_ue.DebugCameraController.md#netdormancy)
- [NetDriverName](ue_ue.DebugCameraController.md#netdrivername)
- [NetPlayerIndex](ue_ue.DebugCameraController.md#netplayerindex)
- [NetPriority](ue_ue.DebugCameraController.md#netpriority)
- [NetTag](ue_ue.DebugCameraController.md#nettag)
- [NetUpdateFrequency](ue_ue.DebugCameraController.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.DebugCameraController.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.DebugCameraController.md#onactorendoverlap)
- [OnActorHit](ue_ue.DebugCameraController.md#onactorhit)
- [OnBeginCursorOver](ue_ue.DebugCameraController.md#onbegincursorover)
- [OnClicked](ue_ue.DebugCameraController.md#onclicked)
- [OnDestroyed](ue_ue.DebugCameraController.md#ondestroyed)
- [OnEndCursorOver](ue_ue.DebugCameraController.md#onendcursorover)
- [OnEndPlay](ue_ue.DebugCameraController.md#onendplay)
- [OnInputTouchBegin](ue_ue.DebugCameraController.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.DebugCameraController.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.DebugCameraController.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.DebugCameraController.md#oninputtouchleave)
- [OnInstigatedAnyDamage](ue_ue.DebugCameraController.md#oninstigatedanydamage)
- [OnReleased](ue_ue.DebugCameraController.md#onreleased)
- [OnTakeAnyDamage](ue_ue.DebugCameraController.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.DebugCameraController.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.DebugCameraController.md#ontakeradialdamage)
- [OriginalControllerRef](ue_ue.DebugCameraController.md#originalcontrollerref)
- [OriginalPlayer](ue_ue.DebugCameraController.md#originalplayer)
- [Owner](ue_ue.DebugCameraController.md#owner)
- [ParentComponent](ue_ue.DebugCameraController.md#parentcomponent)
- [ParentComponentActor](ue_ue.DebugCameraController.md#parentcomponentactor)
- [Pawn](ue_ue.DebugCameraController.md#pawn)
- [PendingSwapConnection](ue_ue.DebugCameraController.md#pendingswapconnection)
- [PivotOffset](ue_ue.DebugCameraController.md#pivotoffset)
- [Player](ue_ue.DebugCameraController.md#player)
- [PlayerCameraManager](ue_ue.DebugCameraController.md#playercameramanager)
- [PlayerCameraManagerClass](ue_ue.DebugCameraController.md#playercameramanagerclass)
- [PlayerInput](ue_ue.DebugCameraController.md#playerinput)
- [PlayerState](ue_ue.DebugCameraController.md#playerstate)
- [PrimaryActorTick](ue_ue.DebugCameraController.md#primaryactortick)
- [RemoteRole](ue_ue.DebugCameraController.md#remoterole)
- [ReplicatedMovement](ue_ue.DebugCameraController.md#replicatedmovement)
- [Role](ue_ue.DebugCameraController.md#role)
- [RootComponent](ue_ue.DebugCameraController.md#rootcomponent)
- [SeamlessTravelCount](ue_ue.DebugCameraController.md#seamlesstravelcount)
- [SelectedActor](ue_ue.DebugCameraController.md#selectedactor)
- [SelectedComponent](ue_ue.DebugCameraController.md#selectedcomponent)
- [SelectedHitPoint](ue_ue.DebugCameraController.md#selectedhitpoint)
- [SmoothTargetViewRotationSpeed](ue_ue.DebugCameraController.md#smoothtargetviewrotationspeed)
- [SpawnCollisionHandlingMethod](ue_ue.DebugCameraController.md#spawncollisionhandlingmethod)
- [SpawnLocation](ue_ue.DebugCameraController.md#spawnlocation)
- [SpectatorPawn](ue_ue.DebugCameraController.md#spectatorpawn)
- [SpeedScale](ue_ue.DebugCameraController.md#speedscale)
- [SpriteScale](ue_ue.DebugCameraController.md#spritescale)
- [StateName](ue_ue.DebugCameraController.md#statename)
- [Tags](ue_ue.DebugCameraController.md#tags)
- [TargetViewRotation](ue_ue.DebugCameraController.md#targetviewrotation)
- [TransformComponent](ue_ue.DebugCameraController.md#transformcomponent)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.DebugCameraController.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.DebugCameraController.md#__tid_actor__)
- [\_\_tid\_Controller\_\_](ue_ue.DebugCameraController.md#__tid_controller__)
- [\_\_tid\_DebugCameraController\_\_](ue_ue.DebugCameraController.md#__tid_debugcameracontroller__)
- [\_\_tid\_Object\_\_](ue_ue.DebugCameraController.md#__tid_object__)
- [\_\_tid\_PlayerController\_\_](ue_ue.DebugCameraController.md#__tid_playercontroller__)
- [bActorEnableCollision](ue_ue.DebugCameraController.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.DebugCameraController.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.DebugCameraController.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.DebugCameraController.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.DebugCameraController.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.DebugCameraController.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.DebugCameraController.md#balwaysrelevant)
- [bAttachToPawn](ue_ue.DebugCameraController.md#battachtopawn)
- [bAutoDestroyWhenFinished](ue_ue.DebugCameraController.md#bautodestroywhenfinished)
- [bAutoManageActiveCameraTarget](ue_ue.DebugCameraController.md#bautomanageactivecameratarget)
- [bBlockInput](ue_ue.DebugCameraController.md#bblockinput)
- [bCanBeDamaged](ue_ue.DebugCameraController.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.DebugCameraController.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.DebugCameraController.md#bcollidewhenplacing)
- [bEditable](ue_ue.DebugCameraController.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.DebugCameraController.md#benableautolodgeneration)
- [bEnableBufferVisualization](ue_ue.DebugCameraController.md#benablebuffervisualization)
- [bEnableBufferVisualizationFullMode](ue_ue.DebugCameraController.md#benablebuffervisualizationfullmode)
- [bEnableClickEvents](ue_ue.DebugCameraController.md#benableclickevents)
- [bEnableMouseOverEvents](ue_ue.DebugCameraController.md#benablemouseoverevents)
- [bEnableTouchEvents](ue_ue.DebugCameraController.md#benabletouchevents)
- [bEnableTouchOverEvents](ue_ue.DebugCameraController.md#benabletouchoverevents)
- [bExchangedRoles](ue_ue.DebugCameraController.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.DebugCameraController.md#bfindcameracomponentwhenviewtarget)
- [bForceFeedbackEnabled](ue_ue.DebugCameraController.md#bforcefeedbackenabled)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.DebugCameraController.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.DebugCameraController.md#bhidden)
- [bHiddenEd](ue_ue.DebugCameraController.md#bhiddened)
- [bHiddenEdLayer](ue_ue.DebugCameraController.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.DebugCameraController.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.DebugCameraController.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.DebugCameraController.md#bignoresoriginshifting)
- [bIsBufferVisualizationInputSetup](ue_ue.DebugCameraController.md#bisbuffervisualizationinputsetup)
- [bIsEditorOnlyActor](ue_ue.DebugCameraController.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.DebugCameraController.md#biseditorpreviewactor)
- [bIsFrozenRendering](ue_ue.DebugCameraController.md#bisfrozenrendering)
- [bIsLocalPlayerController](ue_ue.DebugCameraController.md#bislocalplayercontroller)
- [bIsOrbitingSelectedActor](ue_ue.DebugCameraController.md#bisorbitingselectedactor)
- [bLastDisplayEnabled](ue_ue.DebugCameraController.md#blastdisplayenabled)
- [bListedInSceneOutliner](ue_ue.DebugCameraController.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.DebugCameraController.md#blocklocation)
- [bNetLoadOnClient](ue_ue.DebugCameraController.md#bnetloadonclient)
- [bNetStartup](ue_ue.DebugCameraController.md#bnetstartup)
- [bNetTemporary](ue_ue.DebugCameraController.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.DebugCameraController.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.DebugCameraController.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.DebugCameraController.md#boptimizebpcomponentdata)
- [bOrbitPivotUseCenter](ue_ue.DebugCameraController.md#borbitpivotusecenter)
- [bPlayerIsWaiting](ue_ue.DebugCameraController.md#bplayeriswaiting)
- [bRelevantForLevelBounds](ue_ue.DebugCameraController.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.DebugCameraController.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.DebugCameraController.md#breplayrewindable)
- [bReplicateMovement](ue_ue.DebugCameraController.md#breplicatemovement)
- [bReplicates](ue_ue.DebugCameraController.md#breplicates)
- [bShouldPerformFullTickWhenPaused](ue_ue.DebugCameraController.md#bshouldperformfulltickwhenpaused)
- [bShowMouseCursor](ue_ue.DebugCameraController.md#bshowmousecursor)
- [bShowSelectedInfo](ue_ue.DebugCameraController.md#bshowselectedinfo)
- [bTearOff](ue_ue.DebugCameraController.md#btearoff)

### Methods

- [ActivateTouchInterface](ue_ue.DebugCameraController.md#activatetouchinterface)
- [ActorHasTag](ue_ue.DebugCameraController.md#actorhastag)
- [AddComponent](ue_ue.DebugCameraController.md#addcomponent)
- [AddPitchInput](ue_ue.DebugCameraController.md#addpitchinput)
- [AddRollInput](ue_ue.DebugCameraController.md#addrollinput)
- [AddTickPrerequisiteActor](ue_ue.DebugCameraController.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.DebugCameraController.md#addtickprerequisitecomponent)
- [AddYawInput](ue_ue.DebugCameraController.md#addyawinput)
- [Camera](ue_ue.DebugCameraController.md#camera)
- [CanRestartPlayer](ue_ue.DebugCameraController.md#canrestartplayer)
- [CastToPlayerController](ue_ue.DebugCameraController.md#casttoplayercontroller)
- [ClearAudioListenerAttenuationOverride](ue_ue.DebugCameraController.md#clearaudiolistenerattenuationoverride)
- [ClearAudioListenerOverride](ue_ue.DebugCameraController.md#clearaudiolisteneroverride)
- [ClientAddTextureStreamingLoc](ue_ue.DebugCameraController.md#clientaddtexturestreamingloc)
- [ClientCancelPendingMapChange](ue_ue.DebugCameraController.md#clientcancelpendingmapchange)
- [ClientCapBandwidth](ue_ue.DebugCameraController.md#clientcapbandwidth)
- [ClientClearCameraLensEffects](ue_ue.DebugCameraController.md#clientclearcameralenseffects)
- [ClientCommitMapChange](ue_ue.DebugCameraController.md#clientcommitmapchange)
- [ClientEnableNetworkVoice](ue_ue.DebugCameraController.md#clientenablenetworkvoice)
- [ClientEndOnlineSession](ue_ue.DebugCameraController.md#clientendonlinesession)
- [ClientFlushLevelStreaming](ue_ue.DebugCameraController.md#clientflushlevelstreaming)
- [ClientForceGarbageCollection](ue_ue.DebugCameraController.md#clientforcegarbagecollection)
- [ClientGameEnded](ue_ue.DebugCameraController.md#clientgameended)
- [ClientGotoState](ue_ue.DebugCameraController.md#clientgotostate)
- [ClientIgnoreLookInput](ue_ue.DebugCameraController.md#clientignorelookinput)
- [ClientIgnoreMoveInput](ue_ue.DebugCameraController.md#clientignoremoveinput)
- [ClientMessage](ue_ue.DebugCameraController.md#clientmessage)
- [ClientMutePlayer](ue_ue.DebugCameraController.md#clientmuteplayer)
- [ClientPlayCameraAnim](ue_ue.DebugCameraController.md#clientplaycameraanim)
- [ClientPlayCameraShake](ue_ue.DebugCameraController.md#clientplaycamerashake)
- [ClientPlayForceFeedback\_Internal](ue_ue.DebugCameraController.md#clientplayforcefeedback_internal)
- [ClientPlaySound](ue_ue.DebugCameraController.md#clientplaysound)
- [ClientPlaySoundAtLocation](ue_ue.DebugCameraController.md#clientplaysoundatlocation)
- [ClientPrepareMapChange](ue_ue.DebugCameraController.md#clientpreparemapchange)
- [ClientPrestreamTextures](ue_ue.DebugCameraController.md#clientprestreamtextures)
- [ClientReceiveLocalizedMessage](ue_ue.DebugCameraController.md#clientreceivelocalizedmessage)
- [ClientRepObjRef](ue_ue.DebugCameraController.md#clientrepobjref)
- [ClientReset](ue_ue.DebugCameraController.md#clientreset)
- [ClientRestart](ue_ue.DebugCameraController.md#clientrestart)
- [ClientRetryClientRestart](ue_ue.DebugCameraController.md#clientretryclientrestart)
- [ClientReturnToMainMenu](ue_ue.DebugCameraController.md#clientreturntomainmenu)
- [ClientReturnToMainMenuWithTextReason](ue_ue.DebugCameraController.md#clientreturntomainmenuwithtextreason)
- [ClientSetBlockOnAsyncLoading](ue_ue.DebugCameraController.md#clientsetblockonasyncloading)
- [ClientSetCameraFade](ue_ue.DebugCameraController.md#clientsetcamerafade)
- [ClientSetCameraMode](ue_ue.DebugCameraController.md#clientsetcameramode)
- [ClientSetCinematicMode](ue_ue.DebugCameraController.md#clientsetcinematicmode)
- [ClientSetForceMipLevelsToBeResident](ue_ue.DebugCameraController.md#clientsetforcemiplevelstoberesident)
- [ClientSetHUD](ue_ue.DebugCameraController.md#clientsethud)
- [ClientSetLocation](ue_ue.DebugCameraController.md#clientsetlocation)
- [ClientSetRotation](ue_ue.DebugCameraController.md#clientsetrotation)
- [ClientSetSpectatorWaiting](ue_ue.DebugCameraController.md#clientsetspectatorwaiting)
- [ClientSetViewTarget](ue_ue.DebugCameraController.md#clientsetviewtarget)
- [ClientSpawnCameraLensEffect](ue_ue.DebugCameraController.md#clientspawncameralenseffect)
- [ClientStartOnlineSession](ue_ue.DebugCameraController.md#clientstartonlinesession)
- [ClientStopCameraAnim](ue_ue.DebugCameraController.md#clientstopcameraanim)
- [ClientStopCameraShake](ue_ue.DebugCameraController.md#clientstopcamerashake)
- [ClientStopForceFeedback](ue_ue.DebugCameraController.md#clientstopforcefeedback)
- [ClientTeamMessage](ue_ue.DebugCameraController.md#clientteammessage)
- [ClientTravel](ue_ue.DebugCameraController.md#clienttravel)
- [ClientTravelInternal](ue_ue.DebugCameraController.md#clienttravelinternal)
- [ClientUnmutePlayer](ue_ue.DebugCameraController.md#clientunmuteplayer)
- [ClientUpdateLevelStreamingStatus](ue_ue.DebugCameraController.md#clientupdatelevelstreamingstatus)
- [ClientUpdateMultipleLevelsStreamingStatus](ue_ue.DebugCameraController.md#clientupdatemultiplelevelsstreamingstatus)
- [ClientVoiceHandshakeComplete](ue_ue.DebugCameraController.md#clientvoicehandshakecomplete)
- [ClientWasKicked](ue_ue.DebugCameraController.md#clientwaskicked)
- [ConsoleKey](ue_ue.DebugCameraController.md#consolekey)
- [CreateDefaultSubobject](ue_ue.DebugCameraController.md#createdefaultsubobject)
- [DeprojectMousePositionToWorld](ue_ue.DebugCameraController.md#deprojectmousepositiontoworld)
- [DeprojectScreenPositionToWorld](ue_ue.DebugCameraController.md#deprojectscreenpositiontoworld)
- [DetachRootComponentFromParent](ue_ue.DebugCameraController.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.DebugCameraController.md#disableinput)
- [EnableCheats](ue_ue.DebugCameraController.md#enablecheats)
- [EnableInput](ue_ue.DebugCameraController.md#enableinput)
- [ExecuteUbergraph](ue_ue.DebugCameraController.md#executeubergraph)
- [FOV](ue_ue.DebugCameraController.md#fov)
- [FlushNetDormancy](ue_ue.DebugCameraController.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.DebugCameraController.md#forcenetupdate)
- [GetActorBounds](ue_ue.DebugCameraController.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.DebugCameraController.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.DebugCameraController.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.DebugCameraController.md#getactorforwardvector)
- [GetActorLabel](ue_ue.DebugCameraController.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.DebugCameraController.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.DebugCameraController.md#getactorrightvector)
- [GetActorScale3D](ue_ue.DebugCameraController.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.DebugCameraController.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.DebugCameraController.md#getactortimedilation)
- [GetActorUpVector](ue_ue.DebugCameraController.md#getactorupvector)
- [GetAllChildActors](ue_ue.DebugCameraController.md#getallchildactors)
- [GetAttachParentActor](ue_ue.DebugCameraController.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.DebugCameraController.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.DebugCameraController.md#getattachedactors)
- [GetClass](ue_ue.DebugCameraController.md#getclass)
- [GetComponentByClass](ue_ue.DebugCameraController.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.DebugCameraController.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.DebugCameraController.md#getcomponentsbytag)
- [GetControlRotation](ue_ue.DebugCameraController.md#getcontrolrotation)
- [GetDesiredRotation](ue_ue.DebugCameraController.md#getdesiredrotation)
- [GetDistanceTo](ue_ue.DebugCameraController.md#getdistanceto)
- [GetDotProductTo](ue_ue.DebugCameraController.md#getdotproductto)
- [GetFocalLocation](ue_ue.DebugCameraController.md#getfocallocation)
- [GetFolderPath](ue_ue.DebugCameraController.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.DebugCameraController.md#getgametimesincecreation)
- [GetHUD](ue_ue.DebugCameraController.md#gethud)
- [GetHitResultUnderCursor](ue_ue.DebugCameraController.md#gethitresultundercursor)
- [GetHitResultUnderCursorByChannel](ue_ue.DebugCameraController.md#gethitresultundercursorbychannel)
- [GetHitResultUnderCursorForObjects](ue_ue.DebugCameraController.md#gethitresultundercursorforobjects)
- [GetHitResultUnderFinger](ue_ue.DebugCameraController.md#gethitresultunderfinger)
- [GetHitResultUnderFingerByChannel](ue_ue.DebugCameraController.md#gethitresultunderfingerbychannel)
- [GetHitResultUnderFingerForObjects](ue_ue.DebugCameraController.md#gethitresultunderfingerforobjects)
- [GetHorizontalDistanceTo](ue_ue.DebugCameraController.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.DebugCameraController.md#gethorizontaldotproductto)
- [GetInputAnalogKeyState](ue_ue.DebugCameraController.md#getinputanalogkeystate)
- [GetInputAnalogStickState](ue_ue.DebugCameraController.md#getinputanalogstickstate)
- [GetInputAxisKeyValue](ue_ue.DebugCameraController.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.DebugCameraController.md#getinputaxisvalue)
- [GetInputKeyTimeDown](ue_ue.DebugCameraController.md#getinputkeytimedown)
- [GetInputMotionState](ue_ue.DebugCameraController.md#getinputmotionstate)
- [GetInputMouseDelta](ue_ue.DebugCameraController.md#getinputmousedelta)
- [GetInputTouchState](ue_ue.DebugCameraController.md#getinputtouchstate)
- [GetInputVectorAxisValue](ue_ue.DebugCameraController.md#getinputvectoraxisvalue)
- [GetInputVectorKeyState](ue_ue.DebugCameraController.md#getinputvectorkeystate)
- [GetInstigator](ue_ue.DebugCameraController.md#getinstigator)
- [GetInstigatorController](ue_ue.DebugCameraController.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.DebugCameraController.md#getlifespan)
- [GetLocalRole](ue_ue.DebugCameraController.md#getlocalrole)
- [GetMousePosition](ue_ue.DebugCameraController.md#getmouseposition)
- [GetName](ue_ue.DebugCameraController.md#getname)
- [GetOuter](ue_ue.DebugCameraController.md#getouter)
- [GetOverlappingActors](ue_ue.DebugCameraController.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.DebugCameraController.md#getoverlappingcomponents)
- [GetOwner](ue_ue.DebugCameraController.md#getowner)
- [GetParentActor](ue_ue.DebugCameraController.md#getparentactor)
- [GetParentComponent](ue_ue.DebugCameraController.md#getparentcomponent)
- [GetRemoteRole](ue_ue.DebugCameraController.md#getremoterole)
- [GetSelectedActor](ue_ue.DebugCameraController.md#getselectedactor)
- [GetSpectatorPawn](ue_ue.DebugCameraController.md#getspectatorpawn)
- [GetSquaredDistanceTo](ue_ue.DebugCameraController.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.DebugCameraController.md#gettickablewhenpaused)
- [GetTransform](ue_ue.DebugCameraController.md#gettransform)
- [GetVelocity](ue_ue.DebugCameraController.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.DebugCameraController.md#getverticaldistanceto)
- [GetViewTarget](ue_ue.DebugCameraController.md#getviewtarget)
- [GetViewportSize](ue_ue.DebugCameraController.md#getviewportsize)
- [GetWorld](ue_ue.DebugCameraController.md#getworld)
- [HasAuthority](ue_ue.DebugCameraController.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.DebugCameraController.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.DebugCameraController.md#isactortickenabled)
- [IsChildActor](ue_ue.DebugCameraController.md#ischildactor)
- [IsEditable](ue_ue.DebugCameraController.md#iseditable)
- [IsHiddenEd](ue_ue.DebugCameraController.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.DebugCameraController.md#ishiddenedatstartup)
- [IsInputKeyDown](ue_ue.DebugCameraController.md#isinputkeydown)
- [IsLocalController](ue_ue.DebugCameraController.md#islocalcontroller)
- [IsLocalPlayerController](ue_ue.DebugCameraController.md#islocalplayercontroller)
- [IsLookInputIgnored](ue_ue.DebugCameraController.md#islookinputignored)
- [IsMoveInputIgnored](ue_ue.DebugCameraController.md#ismoveinputignored)
- [IsOverlappingActor](ue_ue.DebugCameraController.md#isoverlappingactor)
- [IsPlayerController](ue_ue.DebugCameraController.md#isplayercontroller)
- [IsSelectable](ue_ue.DebugCameraController.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.DebugCameraController.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.DebugCameraController.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.DebugCameraController.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.DebugCameraController.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.DebugCameraController.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.DebugCameraController.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.DebugCameraController.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.DebugCameraController.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.DebugCameraController.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.DebugCameraController.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.DebugCameraController.md#k2_attachtocomponent)
- [K2\_ClientPlayForceFeedback](ue_ue.DebugCameraController.md#k2_clientplayforcefeedback)
- [K2\_DestroyActor](ue_ue.DebugCameraController.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.DebugCameraController.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.DebugCameraController.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.DebugCameraController.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.DebugCameraController.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.DebugCameraController.md#k2_getcomponentsbyclass)
- [K2\_GetPawn](ue_ue.DebugCameraController.md#k2_getpawn)
- [K2\_GetRootComponent](ue_ue.DebugCameraController.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.DebugCameraController.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.DebugCameraController.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.DebugCameraController.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.DebugCameraController.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.DebugCameraController.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.DebugCameraController.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.DebugCameraController.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.DebugCameraController.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.DebugCameraController.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.DebugCameraController.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.DebugCameraController.md#k2_teleportto)
- [LineOfSightTo](ue_ue.DebugCameraController.md#lineofsightto)
- [LocalTravel](ue_ue.DebugCameraController.md#localtravel)
- [MakeMIDForMaterial](ue_ue.DebugCameraController.md#makemidformaterial)
- [MakeNoise](ue_ue.DebugCameraController.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.DebugCameraController.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.DebugCameraController.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.DebugCameraController.md#onrep_owner)
- [OnRep\_Pawn](ue_ue.DebugCameraController.md#onrep_pawn)
- [OnRep\_PlayerState](ue_ue.DebugCameraController.md#onrep_playerstate)
- [OnRep\_ReplicateMovement](ue_ue.DebugCameraController.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.DebugCameraController.md#onrep_replicatedmovement)
- [OnServerStartedVisualLogger](ue_ue.DebugCameraController.md#onserverstartedvisuallogger)
- [Pause](ue_ue.DebugCameraController.md#pause)
- [PlayDynamicForceFeedback](ue_ue.DebugCameraController.md#playdynamicforcefeedback)
- [PlayHapticEffect](ue_ue.DebugCameraController.md#playhapticeffect)
- [Possess](ue_ue.DebugCameraController.md#possess)
- [PrestreamTextures](ue_ue.DebugCameraController.md#prestreamtextures)
- [ProjectWorldLocationToScreen](ue_ue.DebugCameraController.md#projectworldlocationtoscreen)
- [ReceiveActorBeginCursorOver](ue_ue.DebugCameraController.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.DebugCameraController.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.DebugCameraController.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.DebugCameraController.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.DebugCameraController.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.DebugCameraController.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.DebugCameraController.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.DebugCameraController.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.DebugCameraController.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.DebugCameraController.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.DebugCameraController.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.DebugCameraController.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.DebugCameraController.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.DebugCameraController.md#receiveendplay)
- [ReceiveHit](ue_ue.DebugCameraController.md#receivehit)
- [ReceiveInstigatedAnyDamage](ue_ue.DebugCameraController.md#receiveinstigatedanydamage)
- [ReceiveOnActivate](ue_ue.DebugCameraController.md#receiveonactivate)
- [ReceiveOnActorSelected](ue_ue.DebugCameraController.md#receiveonactorselected)
- [ReceiveOnDeactivate](ue_ue.DebugCameraController.md#receiveondeactivate)
- [ReceivePointDamage](ue_ue.DebugCameraController.md#receivepointdamage)
- [ReceivePossess](ue_ue.DebugCameraController.md#receivepossess)
- [ReceiveRadialDamage](ue_ue.DebugCameraController.md#receiveradialdamage)
- [ReceiveTick](ue_ue.DebugCameraController.md#receivetick)
- [ReceiveUnPossess](ue_ue.DebugCameraController.md#receiveunpossess)
- [RemoveTickPrerequisiteActor](ue_ue.DebugCameraController.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.DebugCameraController.md#removetickprerequisitecomponent)
- [ResetControllerLightColor](ue_ue.DebugCameraController.md#resetcontrollerlightcolor)
- [ResetIgnoreInputFlags](ue_ue.DebugCameraController.md#resetignoreinputflags)
- [ResetIgnoreLookInput](ue_ue.DebugCameraController.md#resetignorelookinput)
- [ResetIgnoreMoveInput](ue_ue.DebugCameraController.md#resetignoremoveinput)
- [RestartLevel](ue_ue.DebugCameraController.md#restartlevel)
- [SendToConsole](ue_ue.DebugCameraController.md#sendtoconsole)
- [ServerAcknowledgePossession](ue_ue.DebugCameraController.md#serveracknowledgepossession)
- [ServerCamera](ue_ue.DebugCameraController.md#servercamera)
- [ServerChangeName](ue_ue.DebugCameraController.md#serverchangename)
- [ServerCheckClientPossession](ue_ue.DebugCameraController.md#servercheckclientpossession)
- [ServerCheckClientPossessionReliable](ue_ue.DebugCameraController.md#servercheckclientpossessionreliable)
- [ServerExec](ue_ue.DebugCameraController.md#serverexec)
- [ServerExecRPC](ue_ue.DebugCameraController.md#serverexecrpc)
- [ServerMutePlayer](ue_ue.DebugCameraController.md#servermuteplayer)
- [ServerNotifyLoadedWorld](ue_ue.DebugCameraController.md#servernotifyloadedworld)
- [ServerPause](ue_ue.DebugCameraController.md#serverpause)
- [ServerRestartPlayer](ue_ue.DebugCameraController.md#serverrestartplayer)
- [ServerSetSpectatorLocation](ue_ue.DebugCameraController.md#serversetspectatorlocation)
- [ServerSetSpectatorWaiting](ue_ue.DebugCameraController.md#serversetspectatorwaiting)
- [ServerShortTimeout](ue_ue.DebugCameraController.md#servershorttimeout)
- [ServerToggleAILogging](ue_ue.DebugCameraController.md#servertoggleailogging)
- [ServerUnmutePlayer](ue_ue.DebugCameraController.md#serverunmuteplayer)
- [ServerUpdateCamera](ue_ue.DebugCameraController.md#serverupdatecamera)
- [ServerUpdateLevelVisibility](ue_ue.DebugCameraController.md#serverupdatelevelvisibility)
- [ServerUpdateMultipleLevelsVisibility](ue_ue.DebugCameraController.md#serverupdatemultiplelevelsvisibility)
- [ServerVerifyViewTarget](ue_ue.DebugCameraController.md#serververifyviewtarget)
- [ServerViewNextPlayer](ue_ue.DebugCameraController.md#serverviewnextplayer)
- [ServerViewPrevPlayer](ue_ue.DebugCameraController.md#serverviewprevplayer)
- [ServerViewSelf](ue_ue.DebugCameraController.md#serverviewself)
- [SetActorEnableCollision](ue_ue.DebugCameraController.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.DebugCameraController.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.DebugCameraController.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.DebugCameraController.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.DebugCameraController.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.DebugCameraController.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.DebugCameraController.md#setactortickinterval)
- [SetAudioListenerAttenuationOverride](ue_ue.DebugCameraController.md#setaudiolistenerattenuationoverride)
- [SetAudioListenerOverride](ue_ue.DebugCameraController.md#setaudiolisteneroverride)
- [SetCinematicMode](ue_ue.DebugCameraController.md#setcinematicmode)
- [SetControlRotation](ue_ue.DebugCameraController.md#setcontrolrotation)
- [SetControllerLightColor](ue_ue.DebugCameraController.md#setcontrollerlightcolor)
- [SetDisableHaptics](ue_ue.DebugCameraController.md#setdisablehaptics)
- [SetFolderPath](ue_ue.DebugCameraController.md#setfolderpath)
- [SetHapticsByValue](ue_ue.DebugCameraController.md#sethapticsbyvalue)
- [SetIgnoreLookInput](ue_ue.DebugCameraController.md#setignorelookinput)
- [SetIgnoreMoveInput](ue_ue.DebugCameraController.md#setignoremoveinput)
- [SetInitialLocationAndRotation](ue_ue.DebugCameraController.md#setinitiallocationandrotation)
- [SetIsTemporarilyHiddenInEditor](ue_ue.DebugCameraController.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.DebugCameraController.md#setlifespan)
- [SetMouseCursorWidget](ue_ue.DebugCameraController.md#setmousecursorwidget)
- [SetMouseLocation](ue_ue.DebugCameraController.md#setmouselocation)
- [SetName](ue_ue.DebugCameraController.md#setname)
- [SetNetDormancy](ue_ue.DebugCameraController.md#setnetdormancy)
- [SetOwner](ue_ue.DebugCameraController.md#setowner)
- [SetPawnMovementSpeedScale](ue_ue.DebugCameraController.md#setpawnmovementspeedscale)
- [SetReplicateMovement](ue_ue.DebugCameraController.md#setreplicatemovement)
- [SetReplicates](ue_ue.DebugCameraController.md#setreplicates)
- [SetTickGroup](ue_ue.DebugCameraController.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.DebugCameraController.md#settickablewhenpaused)
- [SetViewTargetWithBlend](ue_ue.DebugCameraController.md#setviewtargetwithblend)
- [SetVirtualJoystickVisibility](ue_ue.DebugCameraController.md#setvirtualjoystickvisibility)
- [ShowDebugSelectedInfo](ue_ue.DebugCameraController.md#showdebugselectedinfo)
- [SnapRootComponentTo](ue_ue.DebugCameraController.md#snaprootcomponentto)
- [StartFire](ue_ue.DebugCameraController.md#startfire)
- [StopHapticEffect](ue_ue.DebugCameraController.md#stophapticeffect)
- [StopMovement](ue_ue.DebugCameraController.md#stopmovement)
- [SwitchLevel](ue_ue.DebugCameraController.md#switchlevel)
- [TearOff](ue_ue.DebugCameraController.md#tearoff)
- [TestServerLevelVisibilityChange](ue_ue.DebugCameraController.md#testserverlevelvisibilitychange)
- [ToggleDisplay](ue_ue.DebugCameraController.md#toggledisplay)
- [ToggleSpeaking](ue_ue.DebugCameraController.md#togglespeaking)
- [UnPossess](ue_ue.DebugCameraController.md#unpossess)
- [UserConstructionScript](ue_ue.DebugCameraController.md#userconstructionscript)
- [WasInputKeyJustPressed](ue_ue.DebugCameraController.md#wasinputkeyjustpressed)
- [WasInputKeyJustReleased](ue_ue.DebugCameraController.md#wasinputkeyjustreleased)
- [WasRecentlyRendered](ue_ue.DebugCameraController.md#wasrecentlyrendered)
- [Find](ue_ue.DebugCameraController.md#find)
- [Load](ue_ue.DebugCameraController.md#load)
- [StaticClass](ue_ue.DebugCameraController.md#staticclass)

## Constructors

### constructor

• **new DebugCameraController**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PlayerController](ue_ue.PlayerController.md).[constructor](ue_ue.PlayerController.md#constructor)

## Properties

### AcknowledgedPawn

• **AcknowledgedPawn**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[AcknowledgedPawn](ue_ue.PlayerController.md#acknowledgedpawn)

___

### ActiveForceFeedbackEffects

• **ActiveForceFeedbackEffects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActiveForceFeedbackEffect`](ue_ue.ActiveForceFeedbackEffect.md)\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ActiveForceFeedbackEffects](ue_ue.PlayerController.md#activeforcefeedbackeffects)

___

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ActorLabel](ue_ue.PlayerController.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[AttachmentReplication](ue_ue.PlayerController.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[AutoReceiveInput](ue_ue.PlayerController.md#autoreceiveinput)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[BlueprintCreatedComponents](ue_ue.PlayerController.md#blueprintcreatedcomponents)

___

### Character

• **Character**: [`Character`](ue_ue.Character.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[Character](ue_ue.PlayerController.md#character)

___

### CheatClass

• **CheatClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[CheatClass](ue_ue.PlayerController.md#cheatclass)

___

### CheatManager

• **CheatManager**: [`CheatManager`](ue_ue.CheatManager.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[CheatManager](ue_ue.PlayerController.md#cheatmanager)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[Children](ue_ue.PlayerController.md#children)

___

### ClickEventKeys

• **ClickEventKeys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Key`](ue_ue.Key.md)\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClickEventKeys](ue_ue.PlayerController.md#clickeventkeys)

___

### ClientCap

• **ClientCap**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientCap](ue_ue.PlayerController.md#clientcap)

___

### ControlRotation

• **ControlRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ControlRotation](ue_ue.PlayerController.md#controlrotation)

___

### ControllingDirTrackInst

• **ControllingDirTrackInst**: [`InterpTrackInstDirector`](ue_ue.InterpTrackInstDirector.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ControllingDirTrackInst](ue_ue.PlayerController.md#controllingdirtrackinst)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ControllingMatineeActors](ue_ue.PlayerController.md#controllingmatineeactors)

___

### CurrentClickTraceChannel

• **CurrentClickTraceChannel**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[CurrentClickTraceChannel](ue_ue.PlayerController.md#currentclicktracechannel)

___

### CurrentMouseCursor

• **CurrentMouseCursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[CurrentMouseCursor](ue_ue.PlayerController.md#currentmousecursor)

___

### CurrentTouchInterface

• **CurrentTouchInterface**: [`TouchInterface`](ue_ue.TouchInterface.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[CurrentTouchInterface](ue_ue.PlayerController.md#currenttouchinterface)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[CustomTimeDilation](ue_ue.PlayerController.md#customtimedilation)

___

### DefaultClickTraceChannel

• **DefaultClickTraceChannel**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[DefaultClickTraceChannel](ue_ue.PlayerController.md#defaultclicktracechannel)

___

### DefaultMouseCursor

• **DefaultMouseCursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[DefaultMouseCursor](ue_ue.PlayerController.md#defaultmousecursor)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.PlayerController.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### DrawFrustum

• **DrawFrustum**: [`DrawFrustumComponent`](ue_ue.DrawFrustumComponent.md)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[FolderPath](ue_ue.PlayerController.md#folderpath)

___

### ForceFeedbackScale

• **ForceFeedbackScale**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ForceFeedbackScale](ue_ue.PlayerController.md#forcefeedbackscale)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GroupActor](ue_ue.PlayerController.md#groupactor)

___

### HiddenActors

• **HiddenActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[HiddenActors](ue_ue.PlayerController.md#hiddenactors)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[HiddenEditorViews](ue_ue.PlayerController.md#hiddeneditorviews)

___

### HiddenPrimitiveComponents

• **HiddenPrimitiveComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[HiddenPrimitiveComponents](ue_ue.PlayerController.md#hiddenprimitivecomponents)

___

### HitResultTraceDistance

• **HitResultTraceDistance**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[HitResultTraceDistance](ue_ue.PlayerController.md#hitresulttracedistance)

___

### InactiveStateInputComponent

• **InactiveStateInputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[InactiveStateInputComponent](ue_ue.PlayerController.md#inactivestateinputcomponent)

___

### InitialAccel

• **InitialAccel**: `number`

___

### InitialDecel

• **InitialDecel**: `number`

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[InitialLifeSpan](ue_ue.PlayerController.md#initiallifespan)

___

### InitialMaxSpeed

• **InitialMaxSpeed**: `number`

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[InputComponent](ue_ue.PlayerController.md#inputcomponent)

___

### InputPitchScale

• **InputPitchScale**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[InputPitchScale](ue_ue.PlayerController.md#inputpitchscale)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[InputPriority](ue_ue.PlayerController.md#inputpriority)

___

### InputRollScale

• **InputRollScale**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[InputRollScale](ue_ue.PlayerController.md#inputrollscale)

___

### InputYawScale

• **InputYawScale**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[InputYawScale](ue_ue.PlayerController.md#inputyawscale)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[InstanceComponents](ue_ue.PlayerController.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[Instigator](ue_ue.PlayerController.md#instigator)

___

### LastCompletedSeamlessTravelCount

• **LastCompletedSeamlessTravelCount**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[LastCompletedSeamlessTravelCount](ue_ue.PlayerController.md#lastcompletedseamlesstravelcount)

___

### LastSpectatorStateSynchTime

• **LastSpectatorStateSynchTime**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[LastSpectatorStateSynchTime](ue_ue.PlayerController.md#lastspectatorstatesynchtime)

___

### LastSpectatorSyncLocation

• **LastSpectatorSyncLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[LastSpectatorSyncLocation](ue_ue.PlayerController.md#lastspectatorsynclocation)

___

### LastSpectatorSyncRotation

• **LastSpectatorSyncRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[LastSpectatorSyncRotation](ue_ue.PlayerController.md#lastspectatorsyncrotation)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[Layers](ue_ue.PlayerController.md#layers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[MinNetUpdateFrequency](ue_ue.PlayerController.md#minnetupdatefrequency)

___

### MyHUD

• **MyHUD**: [`HUD`](ue_ue.HUD.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[MyHUD](ue_ue.PlayerController.md#myhud)

___

### NetConnection

• **NetConnection**: [`NetConnection`](ue_ue.NetConnection.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[NetConnection](ue_ue.PlayerController.md#netconnection)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[NetCullDistanceSquared](ue_ue.PlayerController.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[NetDormancy](ue_ue.PlayerController.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[NetDriverName](ue_ue.PlayerController.md#netdrivername)

___

### NetPlayerIndex

• **NetPlayerIndex**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[NetPlayerIndex](ue_ue.PlayerController.md#netplayerindex)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[NetPriority](ue_ue.PlayerController.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[NetTag](ue_ue.PlayerController.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[NetUpdateFrequency](ue_ue.PlayerController.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnActorBeginOverlap](ue_ue.PlayerController.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnActorEndOverlap](ue_ue.PlayerController.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnActorHit](ue_ue.PlayerController.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnBeginCursorOver](ue_ue.PlayerController.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnClicked](ue_ue.PlayerController.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnDestroyed](ue_ue.PlayerController.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnEndCursorOver](ue_ue.PlayerController.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnEndPlay](ue_ue.PlayerController.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnInputTouchBegin](ue_ue.PlayerController.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnInputTouchEnd](ue_ue.PlayerController.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnInputTouchEnter](ue_ue.PlayerController.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnInputTouchLeave](ue_ue.PlayerController.md#oninputtouchleave)

___

### OnInstigatedAnyDamage

• **OnInstigatedAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnInstigatedAnyDamage](ue_ue.PlayerController.md#oninstigatedanydamage)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnReleased](ue_ue.PlayerController.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnTakeAnyDamage](ue_ue.PlayerController.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnTakePointDamage](ue_ue.PlayerController.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnTakeRadialDamage](ue_ue.PlayerController.md#ontakeradialdamage)

___

### OriginalControllerRef

• **OriginalControllerRef**: [`PlayerController`](ue_ue.PlayerController.md)

___

### OriginalPlayer

• **OriginalPlayer**: [`Player`](ue_ue.Player.md)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[Owner](ue_ue.PlayerController.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ParentComponent](ue_ue.PlayerController.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ParentComponentActor](ue_ue.PlayerController.md#parentcomponentactor)

___

### Pawn

• **Pawn**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[Pawn](ue_ue.PlayerController.md#pawn)

___

### PendingSwapConnection

• **PendingSwapConnection**: [`NetConnection`](ue_ue.NetConnection.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[PendingSwapConnection](ue_ue.PlayerController.md#pendingswapconnection)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[PivotOffset](ue_ue.PlayerController.md#pivotoffset)

___

### Player

• **Player**: [`Player`](ue_ue.Player.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[Player](ue_ue.PlayerController.md#player)

___

### PlayerCameraManager

• **PlayerCameraManager**: [`PlayerCameraManager`](ue_ue.PlayerCameraManager.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[PlayerCameraManager](ue_ue.PlayerController.md#playercameramanager)

___

### PlayerCameraManagerClass

• **PlayerCameraManagerClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[PlayerCameraManagerClass](ue_ue.PlayerController.md#playercameramanagerclass)

___

### PlayerInput

• **PlayerInput**: [`PlayerInput`](ue_ue.PlayerInput.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[PlayerInput](ue_ue.PlayerController.md#playerinput)

___

### PlayerState

• **PlayerState**: [`PlayerState`](ue_ue.PlayerState.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[PlayerState](ue_ue.PlayerController.md#playerstate)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[PrimaryActorTick](ue_ue.PlayerController.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[RemoteRole](ue_ue.PlayerController.md#remoterole)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ReplicatedMovement](ue_ue.PlayerController.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[Role](ue_ue.PlayerController.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[RootComponent](ue_ue.PlayerController.md#rootcomponent)

___

### SeamlessTravelCount

• **SeamlessTravelCount**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SeamlessTravelCount](ue_ue.PlayerController.md#seamlesstravelcount)

___

### SelectedActor

• **SelectedActor**: [`Actor`](ue_ue.Actor.md)

___

### SelectedComponent

• **SelectedComponent**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

___

### SelectedHitPoint

• **SelectedHitPoint**: [`HitResult`](ue_ue.HitResult.md)

___

### SmoothTargetViewRotationSpeed

• **SmoothTargetViewRotationSpeed**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SmoothTargetViewRotationSpeed](ue_ue.PlayerController.md#smoothtargetviewrotationspeed)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SpawnCollisionHandlingMethod](ue_ue.PlayerController.md#spawncollisionhandlingmethod)

___

### SpawnLocation

• **SpawnLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SpawnLocation](ue_ue.PlayerController.md#spawnlocation)

___

### SpectatorPawn

• **SpectatorPawn**: [`SpectatorPawn`](ue_ue.SpectatorPawn.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SpectatorPawn](ue_ue.PlayerController.md#spectatorpawn)

___

### SpeedScale

• **SpeedScale**: `number`

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SpriteScale](ue_ue.PlayerController.md#spritescale)

___

### StateName

• **StateName**: `string`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[StateName](ue_ue.PlayerController.md#statename)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[Tags](ue_ue.PlayerController.md#tags)

___

### TargetViewRotation

• **TargetViewRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[TargetViewRotation](ue_ue.PlayerController.md#targetviewrotation)

___

### TransformComponent

• **TransformComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[TransformComponent](ue_ue.PlayerController.md#transformcomponent)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.PlayerController.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[__tid_Actor__](ue_ue.PlayerController.md#__tid_actor__)

___

### \_\_tid\_Controller\_\_

• **\_\_tid\_Controller\_\_**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[__tid_Controller__](ue_ue.PlayerController.md#__tid_controller__)

___

### \_\_tid\_DebugCameraController\_\_

• **\_\_tid\_DebugCameraController\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[__tid_Object__](ue_ue.PlayerController.md#__tid_object__)

___

### \_\_tid\_PlayerController\_\_

• **\_\_tid\_PlayerController\_\_**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[__tid_PlayerController__](ue_ue.PlayerController.md#__tid_playercontroller__)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bActorEnableCollision](ue_ue.PlayerController.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bActorIsBeingDestroyed](ue_ue.PlayerController.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bActorLabelEditable](ue_ue.PlayerController.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bActorSeamlessTraveled](ue_ue.PlayerController.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.PlayerController.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bAllowTickBeforeBeginPlay](ue_ue.PlayerController.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bAlwaysRelevant](ue_ue.PlayerController.md#balwaysrelevant)

___

### bAttachToPawn

• **bAttachToPawn**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bAttachToPawn](ue_ue.PlayerController.md#battachtopawn)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bAutoDestroyWhenFinished](ue_ue.PlayerController.md#bautodestroywhenfinished)

___

### bAutoManageActiveCameraTarget

• **bAutoManageActiveCameraTarget**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bAutoManageActiveCameraTarget](ue_ue.PlayerController.md#bautomanageactivecameratarget)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bBlockInput](ue_ue.PlayerController.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bCanBeDamaged](ue_ue.PlayerController.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bCanBeInCluster](ue_ue.PlayerController.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bCollideWhenPlacing](ue_ue.PlayerController.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bEditable](ue_ue.PlayerController.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bEnableAutoLODGeneration](ue_ue.PlayerController.md#benableautolodgeneration)

___

### bEnableBufferVisualization

• **bEnableBufferVisualization**: `boolean`

___

### bEnableBufferVisualizationFullMode

• **bEnableBufferVisualizationFullMode**: `boolean`

___

### bEnableClickEvents

• **bEnableClickEvents**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bEnableClickEvents](ue_ue.PlayerController.md#benableclickevents)

___

### bEnableMouseOverEvents

• **bEnableMouseOverEvents**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bEnableMouseOverEvents](ue_ue.PlayerController.md#benablemouseoverevents)

___

### bEnableTouchEvents

• **bEnableTouchEvents**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bEnableTouchEvents](ue_ue.PlayerController.md#benabletouchevents)

___

### bEnableTouchOverEvents

• **bEnableTouchOverEvents**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bEnableTouchOverEvents](ue_ue.PlayerController.md#benabletouchoverevents)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bExchangedRoles](ue_ue.PlayerController.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bFindCameraComponentWhenViewTarget](ue_ue.PlayerController.md#bfindcameracomponentwhenviewtarget)

___

### bForceFeedbackEnabled

• **bForceFeedbackEnabled**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bForceFeedbackEnabled](ue_ue.PlayerController.md#bforcefeedbackenabled)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.PlayerController.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bHidden](ue_ue.PlayerController.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bHiddenEd](ue_ue.PlayerController.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bHiddenEdLayer](ue_ue.PlayerController.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bHiddenEdLevel](ue_ue.PlayerController.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bHiddenEdTemporary](ue_ue.PlayerController.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bIgnoresOriginShifting](ue_ue.PlayerController.md#bignoresoriginshifting)

___

### bIsBufferVisualizationInputSetup

• **bIsBufferVisualizationInputSetup**: `boolean`

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bIsEditorOnlyActor](ue_ue.PlayerController.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bIsEditorPreviewActor](ue_ue.PlayerController.md#biseditorpreviewactor)

___

### bIsFrozenRendering

• **bIsFrozenRendering**: `boolean`

___

### bIsLocalPlayerController

• **bIsLocalPlayerController**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bIsLocalPlayerController](ue_ue.PlayerController.md#bislocalplayercontroller)

___

### bIsOrbitingSelectedActor

• **bIsOrbitingSelectedActor**: `boolean`

___

### bLastDisplayEnabled

• **bLastDisplayEnabled**: `boolean`

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bListedInSceneOutliner](ue_ue.PlayerController.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bLockLocation](ue_ue.PlayerController.md#blocklocation)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bNetLoadOnClient](ue_ue.PlayerController.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bNetStartup](ue_ue.PlayerController.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bNetTemporary](ue_ue.PlayerController.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bNetUseOwnerRelevancy](ue_ue.PlayerController.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bOnlyRelevantToOwner](ue_ue.PlayerController.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bOptimizeBPComponentData](ue_ue.PlayerController.md#boptimizebpcomponentdata)

___

### bOrbitPivotUseCenter

• **bOrbitPivotUseCenter**: `boolean`

___

### bPlayerIsWaiting

• **bPlayerIsWaiting**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bPlayerIsWaiting](ue_ue.PlayerController.md#bplayeriswaiting)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bRelevantForLevelBounds](ue_ue.PlayerController.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bRelevantForNetworkReplays](ue_ue.PlayerController.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bReplayRewindable](ue_ue.PlayerController.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bReplicateMovement](ue_ue.PlayerController.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bReplicates](ue_ue.PlayerController.md#breplicates)

___

### bShouldPerformFullTickWhenPaused

• **bShouldPerformFullTickWhenPaused**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bShouldPerformFullTickWhenPaused](ue_ue.PlayerController.md#bshouldperformfulltickwhenpaused)

___

### bShowMouseCursor

• **bShowMouseCursor**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bShowMouseCursor](ue_ue.PlayerController.md#bshowmousecursor)

___

### bShowSelectedInfo

• **bShowSelectedInfo**: `boolean`

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[bTearOff](ue_ue.PlayerController.md#btearoff)

## Methods

### ActivateTouchInterface

▸ **ActivateTouchInterface**(`NewTouchInterface`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTouchInterface` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TouchInterface`](ue_ue.TouchInterface.md)\> |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ActivateTouchInterface](ue_ue.PlayerController.md#activatetouchinterface)

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

[PlayerController](ue_ue.PlayerController.md).[ActorHasTag](ue_ue.PlayerController.md#actorhastag)

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

[PlayerController](ue_ue.PlayerController.md).[AddComponent](ue_ue.PlayerController.md#addcomponent)

___

### AddPitchInput

▸ **AddPitchInput**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[AddPitchInput](ue_ue.PlayerController.md#addpitchinput)

___

### AddRollInput

▸ **AddRollInput**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[AddRollInput](ue_ue.PlayerController.md#addrollinput)

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

[PlayerController](ue_ue.PlayerController.md).[AddTickPrerequisiteActor](ue_ue.PlayerController.md#addtickprerequisiteactor)

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

[PlayerController](ue_ue.PlayerController.md).[AddTickPrerequisiteComponent](ue_ue.PlayerController.md#addtickprerequisitecomponent)

___

### AddYawInput

▸ **AddYawInput**(`Val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Val` | `number` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[AddYawInput](ue_ue.PlayerController.md#addyawinput)

___

### Camera

▸ **Camera**(`NewMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMode` | `string` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[Camera](ue_ue.PlayerController.md#camera)

___

### CanRestartPlayer

▸ **CanRestartPlayer**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[CanRestartPlayer](ue_ue.PlayerController.md#canrestartplayer)

___

### CastToPlayerController

▸ **CastToPlayerController**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[CastToPlayerController](ue_ue.PlayerController.md#casttoplayercontroller)

___

### ClearAudioListenerAttenuationOverride

▸ **ClearAudioListenerAttenuationOverride**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClearAudioListenerAttenuationOverride](ue_ue.PlayerController.md#clearaudiolistenerattenuationoverride)

___

### ClearAudioListenerOverride

▸ **ClearAudioListenerOverride**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClearAudioListenerOverride](ue_ue.PlayerController.md#clearaudiolisteneroverride)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientAddTextureStreamingLoc](ue_ue.PlayerController.md#clientaddtexturestreamingloc)

___

### ClientCancelPendingMapChange

▸ **ClientCancelPendingMapChange**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientCancelPendingMapChange](ue_ue.PlayerController.md#clientcancelpendingmapchange)

___

### ClientCapBandwidth

▸ **ClientCapBandwidth**(`Cap`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Cap` | `number` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientCapBandwidth](ue_ue.PlayerController.md#clientcapbandwidth)

___

### ClientClearCameraLensEffects

▸ **ClientClearCameraLensEffects**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientClearCameraLensEffects](ue_ue.PlayerController.md#clientclearcameralenseffects)

___

### ClientCommitMapChange

▸ **ClientCommitMapChange**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientCommitMapChange](ue_ue.PlayerController.md#clientcommitmapchange)

___

### ClientEnableNetworkVoice

▸ **ClientEnableNetworkVoice**(`bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientEnableNetworkVoice](ue_ue.PlayerController.md#clientenablenetworkvoice)

___

### ClientEndOnlineSession

▸ **ClientEndOnlineSession**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientEndOnlineSession](ue_ue.PlayerController.md#clientendonlinesession)

___

### ClientFlushLevelStreaming

▸ **ClientFlushLevelStreaming**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientFlushLevelStreaming](ue_ue.PlayerController.md#clientflushlevelstreaming)

___

### ClientForceGarbageCollection

▸ **ClientForceGarbageCollection**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientForceGarbageCollection](ue_ue.PlayerController.md#clientforcegarbagecollection)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientGameEnded](ue_ue.PlayerController.md#clientgameended)

___

### ClientGotoState

▸ **ClientGotoState**(`NewState`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewState` | `string` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientGotoState](ue_ue.PlayerController.md#clientgotostate)

___

### ClientIgnoreLookInput

▸ **ClientIgnoreLookInput**(`bIgnore`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIgnore` | `boolean` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientIgnoreLookInput](ue_ue.PlayerController.md#clientignorelookinput)

___

### ClientIgnoreMoveInput

▸ **ClientIgnoreMoveInput**(`bIgnore`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIgnore` | `boolean` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientIgnoreMoveInput](ue_ue.PlayerController.md#clientignoremoveinput)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientMessage](ue_ue.PlayerController.md#clientmessage)

___

### ClientMutePlayer

▸ **ClientMutePlayer**(`PlayerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerId` | [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md) |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientMutePlayer](ue_ue.PlayerController.md#clientmuteplayer)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientPlayCameraAnim](ue_ue.PlayerController.md#clientplaycameraanim)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientPlayCameraShake](ue_ue.PlayerController.md#clientplaycamerashake)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientPlayForceFeedback_Internal](ue_ue.PlayerController.md#clientplayforcefeedback_internal)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientPlaySound](ue_ue.PlayerController.md#clientplaysound)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientPlaySoundAtLocation](ue_ue.PlayerController.md#clientplaysoundatlocation)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientPrepareMapChange](ue_ue.PlayerController.md#clientpreparemapchange)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientPrestreamTextures](ue_ue.PlayerController.md#clientprestreamtextures)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientReceiveLocalizedMessage](ue_ue.PlayerController.md#clientreceivelocalizedmessage)

___

### ClientRepObjRef

▸ **ClientRepObjRef**(`Object`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Object` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientRepObjRef](ue_ue.PlayerController.md#clientrepobjref)

___

### ClientReset

▸ **ClientReset**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientReset](ue_ue.PlayerController.md#clientreset)

___

### ClientRestart

▸ **ClientRestart**(`NewPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientRestart](ue_ue.PlayerController.md#clientrestart)

___

### ClientRetryClientRestart

▸ **ClientRetryClientRestart**(`NewPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientRetryClientRestart](ue_ue.PlayerController.md#clientretryclientrestart)

___

### ClientReturnToMainMenu

▸ **ClientReturnToMainMenu**(`ReturnReason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ReturnReason` | `string` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientReturnToMainMenu](ue_ue.PlayerController.md#clientreturntomainmenu)

___

### ClientReturnToMainMenuWithTextReason

▸ **ClientReturnToMainMenuWithTextReason**(`ReturnReason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ReturnReason` | `string` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientReturnToMainMenuWithTextReason](ue_ue.PlayerController.md#clientreturntomainmenuwithtextreason)

___

### ClientSetBlockOnAsyncLoading

▸ **ClientSetBlockOnAsyncLoading**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientSetBlockOnAsyncLoading](ue_ue.PlayerController.md#clientsetblockonasyncloading)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientSetCameraFade](ue_ue.PlayerController.md#clientsetcamerafade)

___

### ClientSetCameraMode

▸ **ClientSetCameraMode**(`NewCamMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewCamMode` | `string` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientSetCameraMode](ue_ue.PlayerController.md#clientsetcameramode)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientSetCinematicMode](ue_ue.PlayerController.md#clientsetcinematicmode)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientSetForceMipLevelsToBeResident](ue_ue.PlayerController.md#clientsetforcemiplevelstoberesident)

___

### ClientSetHUD

▸ **ClientSetHUD**(`NewHUDClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewHUDClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientSetHUD](ue_ue.PlayerController.md#clientsethud)

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

[PlayerController](ue_ue.PlayerController.md).[ClientSetLocation](ue_ue.PlayerController.md#clientsetlocation)

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

[PlayerController](ue_ue.PlayerController.md).[ClientSetRotation](ue_ue.PlayerController.md#clientsetrotation)

___

### ClientSetSpectatorWaiting

▸ **ClientSetSpectatorWaiting**(`bWaiting`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bWaiting` | `boolean` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientSetSpectatorWaiting](ue_ue.PlayerController.md#clientsetspectatorwaiting)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientSetViewTarget](ue_ue.PlayerController.md#clientsetviewtarget)

___

### ClientSpawnCameraLensEffect

▸ **ClientSpawnCameraLensEffect**(`LensEffectEmitterClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LensEffectEmitterClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientSpawnCameraLensEffect](ue_ue.PlayerController.md#clientspawncameralenseffect)

___

### ClientStartOnlineSession

▸ **ClientStartOnlineSession**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientStartOnlineSession](ue_ue.PlayerController.md#clientstartonlinesession)

___

### ClientStopCameraAnim

▸ **ClientStopCameraAnim**(`AnimToStop`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimToStop` | [`$Nullable`](../modules/puerts.md#$nullable)<[`CameraAnim`](ue_ue.CameraAnim.md)\> |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientStopCameraAnim](ue_ue.PlayerController.md#clientstopcameraanim)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientStopCameraShake](ue_ue.PlayerController.md#clientstopcamerashake)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientStopForceFeedback](ue_ue.PlayerController.md#clientstopforcefeedback)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientTeamMessage](ue_ue.PlayerController.md#clientteammessage)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientTravel](ue_ue.PlayerController.md#clienttravel)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientTravelInternal](ue_ue.PlayerController.md#clienttravelinternal)

___

### ClientUnmutePlayer

▸ **ClientUnmutePlayer**(`PlayerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerId` | [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md) |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientUnmutePlayer](ue_ue.PlayerController.md#clientunmuteplayer)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientUpdateLevelStreamingStatus](ue_ue.PlayerController.md#clientupdatelevelstreamingstatus)

___

### ClientUpdateMultipleLevelsStreamingStatus

▸ **ClientUpdateMultipleLevelsStreamingStatus**(`LevelStatuses`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LevelStatuses` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UpdateLevelStreamingLevelStatus`](ue_ue.UpdateLevelStreamingLevelStatus.md)\> |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientUpdateMultipleLevelsStreamingStatus](ue_ue.PlayerController.md#clientupdatemultiplelevelsstreamingstatus)

___

### ClientVoiceHandshakeComplete

▸ **ClientVoiceHandshakeComplete**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientVoiceHandshakeComplete](ue_ue.PlayerController.md#clientvoicehandshakecomplete)

___

### ClientWasKicked

▸ **ClientWasKicked**(`KickReason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KickReason` | `string` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ClientWasKicked](ue_ue.PlayerController.md#clientwaskicked)

___

### ConsoleKey

▸ **ConsoleKey**(`Key`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ConsoleKey](ue_ue.PlayerController.md#consolekey)

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

[PlayerController](ue_ue.PlayerController.md).[CreateDefaultSubobject](ue_ue.PlayerController.md#createdefaultsubobject)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[DeprojectMousePositionToWorld](ue_ue.PlayerController.md#deprojectmousepositiontoworld)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[DeprojectScreenPositionToWorld](ue_ue.PlayerController.md#deprojectscreenpositiontoworld)

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

[PlayerController](ue_ue.PlayerController.md).[DetachRootComponentFromParent](ue_ue.PlayerController.md#detachrootcomponentfromparent)

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

[PlayerController](ue_ue.PlayerController.md).[DisableInput](ue_ue.PlayerController.md#disableinput)

___

### EnableCheats

▸ **EnableCheats**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[EnableCheats](ue_ue.PlayerController.md#enablecheats)

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

[PlayerController](ue_ue.PlayerController.md).[EnableInput](ue_ue.PlayerController.md#enableinput)

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

[PlayerController](ue_ue.PlayerController.md).[ExecuteUbergraph](ue_ue.PlayerController.md#executeubergraph)

___

### FOV

▸ **FOV**(`NewFOV`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewFOV` | `number` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[FOV](ue_ue.PlayerController.md#fov)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[FlushNetDormancy](ue_ue.PlayerController.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ForceNetUpdate](ue_ue.PlayerController.md#forcenetupdate)

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

[PlayerController](ue_ue.PlayerController.md).[GetActorBounds](ue_ue.PlayerController.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetActorEnableCollision](ue_ue.PlayerController.md#getactorenablecollision)

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

[PlayerController](ue_ue.PlayerController.md).[GetActorEyesViewPoint](ue_ue.PlayerController.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetActorForwardVector](ue_ue.PlayerController.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetActorLabel](ue_ue.PlayerController.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetActorRelativeScale3D](ue_ue.PlayerController.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetActorRightVector](ue_ue.PlayerController.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetActorScale3D](ue_ue.PlayerController.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetActorTickInterval](ue_ue.PlayerController.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetActorTimeDilation](ue_ue.PlayerController.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetActorUpVector](ue_ue.PlayerController.md#getactorupvector)

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

[PlayerController](ue_ue.PlayerController.md).[GetAllChildActors](ue_ue.PlayerController.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetAttachParentActor](ue_ue.PlayerController.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetAttachParentSocketName](ue_ue.PlayerController.md#getattachparentsocketname)

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

[PlayerController](ue_ue.PlayerController.md).[GetAttachedActors](ue_ue.PlayerController.md#getattachedactors)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetClass](ue_ue.PlayerController.md#getclass)

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

[PlayerController](ue_ue.PlayerController.md).[GetComponentByClass](ue_ue.PlayerController.md#getcomponentbyclass)

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

[PlayerController](ue_ue.PlayerController.md).[GetComponentsByInterface](ue_ue.PlayerController.md#getcomponentsbyinterface)

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

[PlayerController](ue_ue.PlayerController.md).[GetComponentsByTag](ue_ue.PlayerController.md#getcomponentsbytag)

___

### GetControlRotation

▸ **GetControlRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetControlRotation](ue_ue.PlayerController.md#getcontrolrotation)

___

### GetDesiredRotation

▸ **GetDesiredRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetDesiredRotation](ue_ue.PlayerController.md#getdesiredrotation)

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

[PlayerController](ue_ue.PlayerController.md).[GetDistanceTo](ue_ue.PlayerController.md#getdistanceto)

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

[PlayerController](ue_ue.PlayerController.md).[GetDotProductTo](ue_ue.PlayerController.md#getdotproductto)

___

### GetFocalLocation

▸ **GetFocalLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetFocalLocation](ue_ue.PlayerController.md#getfocallocation)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetFolderPath](ue_ue.PlayerController.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetGameTimeSinceCreation](ue_ue.PlayerController.md#getgametimesincecreation)

___

### GetHUD

▸ **GetHUD**(): [`HUD`](ue_ue.HUD.md)

#### Returns

[`HUD`](ue_ue.HUD.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetHUD](ue_ue.PlayerController.md#gethud)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetHitResultUnderCursor](ue_ue.PlayerController.md#gethitresultundercursor)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetHitResultUnderCursorByChannel](ue_ue.PlayerController.md#gethitresultundercursorbychannel)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetHitResultUnderCursorForObjects](ue_ue.PlayerController.md#gethitresultundercursorforobjects)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetHitResultUnderFinger](ue_ue.PlayerController.md#gethitresultunderfinger)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetHitResultUnderFingerByChannel](ue_ue.PlayerController.md#gethitresultunderfingerbychannel)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetHitResultUnderFingerForObjects](ue_ue.PlayerController.md#gethitresultunderfingerforobjects)

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

[PlayerController](ue_ue.PlayerController.md).[GetHorizontalDistanceTo](ue_ue.PlayerController.md#gethorizontaldistanceto)

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

[PlayerController](ue_ue.PlayerController.md).[GetHorizontalDotProductTo](ue_ue.PlayerController.md#gethorizontaldotproductto)

___

### GetInputAnalogKeyState

▸ **GetInputAnalogKeyState**(`Key`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetInputAnalogKeyState](ue_ue.PlayerController.md#getinputanalogkeystate)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetInputAnalogStickState](ue_ue.PlayerController.md#getinputanalogstickstate)

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

[PlayerController](ue_ue.PlayerController.md).[GetInputAxisKeyValue](ue_ue.PlayerController.md#getinputaxiskeyvalue)

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

[PlayerController](ue_ue.PlayerController.md).[GetInputAxisValue](ue_ue.PlayerController.md#getinputaxisvalue)

___

### GetInputKeyTimeDown

▸ **GetInputKeyTimeDown**(`Key`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetInputKeyTimeDown](ue_ue.PlayerController.md#getinputkeytimedown)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetInputMotionState](ue_ue.PlayerController.md#getinputmotionstate)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetInputMouseDelta](ue_ue.PlayerController.md#getinputmousedelta)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetInputTouchState](ue_ue.PlayerController.md#getinputtouchstate)

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

[PlayerController](ue_ue.PlayerController.md).[GetInputVectorAxisValue](ue_ue.PlayerController.md#getinputvectoraxisvalue)

___

### GetInputVectorKeyState

▸ **GetInputVectorKeyState**(`Key`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetInputVectorKeyState](ue_ue.PlayerController.md#getinputvectorkeystate)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetInstigator](ue_ue.PlayerController.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetInstigatorController](ue_ue.PlayerController.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetLifeSpan](ue_ue.PlayerController.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetLocalRole](ue_ue.PlayerController.md#getlocalrole)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetMousePosition](ue_ue.PlayerController.md#getmouseposition)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetName](ue_ue.PlayerController.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetOuter](ue_ue.PlayerController.md#getouter)

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

[PlayerController](ue_ue.PlayerController.md).[GetOverlappingActors](ue_ue.PlayerController.md#getoverlappingactors)

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

[PlayerController](ue_ue.PlayerController.md).[GetOverlappingComponents](ue_ue.PlayerController.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetOwner](ue_ue.PlayerController.md#getowner)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetParentActor](ue_ue.PlayerController.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetParentComponent](ue_ue.PlayerController.md#getparentcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetRemoteRole](ue_ue.PlayerController.md#getremoterole)

___

### GetSelectedActor

▸ **GetSelectedActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

___

### GetSpectatorPawn

▸ **GetSpectatorPawn**(): [`SpectatorPawn`](ue_ue.SpectatorPawn.md)

#### Returns

[`SpectatorPawn`](ue_ue.SpectatorPawn.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetSpectatorPawn](ue_ue.PlayerController.md#getspectatorpawn)

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

[PlayerController](ue_ue.PlayerController.md).[GetSquaredDistanceTo](ue_ue.PlayerController.md#getsquareddistanceto)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetTickableWhenPaused](ue_ue.PlayerController.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetTransform](ue_ue.PlayerController.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetVelocity](ue_ue.PlayerController.md#getvelocity)

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

[PlayerController](ue_ue.PlayerController.md).[GetVerticalDistanceTo](ue_ue.PlayerController.md#getverticaldistanceto)

___

### GetViewTarget

▸ **GetViewTarget**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetViewTarget](ue_ue.PlayerController.md#getviewtarget)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetViewportSize](ue_ue.PlayerController.md#getviewportsize)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[GetWorld](ue_ue.PlayerController.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[HasAuthority](ue_ue.PlayerController.md#hasauthority)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[IsActorBeingDestroyed](ue_ue.PlayerController.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[IsActorTickEnabled](ue_ue.PlayerController.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[IsChildActor](ue_ue.PlayerController.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[IsEditable](ue_ue.PlayerController.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[IsHiddenEd](ue_ue.PlayerController.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[IsHiddenEdAtStartup](ue_ue.PlayerController.md#ishiddenedatstartup)

___

### IsInputKeyDown

▸ **IsInputKeyDown**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[IsInputKeyDown](ue_ue.PlayerController.md#isinputkeydown)

___

### IsLocalController

▸ **IsLocalController**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[IsLocalController](ue_ue.PlayerController.md#islocalcontroller)

___

### IsLocalPlayerController

▸ **IsLocalPlayerController**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[IsLocalPlayerController](ue_ue.PlayerController.md#islocalplayercontroller)

___

### IsLookInputIgnored

▸ **IsLookInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[IsLookInputIgnored](ue_ue.PlayerController.md#islookinputignored)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[IsMoveInputIgnored](ue_ue.PlayerController.md#ismoveinputignored)

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

[PlayerController](ue_ue.PlayerController.md).[IsOverlappingActor](ue_ue.PlayerController.md#isoverlappingactor)

___

### IsPlayerController

▸ **IsPlayerController**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[IsPlayerController](ue_ue.PlayerController.md#isplayercontroller)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[IsSelectable](ue_ue.PlayerController.md#isselectable)

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

[PlayerController](ue_ue.PlayerController.md).[IsTemporarilyHiddenInEditor](ue_ue.PlayerController.md#istemporarilyhiddenineditor)

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

[PlayerController](ue_ue.PlayerController.md).[K2_AddActorLocalOffset](ue_ue.PlayerController.md#k2_addactorlocaloffset)

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

[PlayerController](ue_ue.PlayerController.md).[K2_AddActorLocalRotation](ue_ue.PlayerController.md#k2_addactorlocalrotation)

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

[PlayerController](ue_ue.PlayerController.md).[K2_AddActorLocalTransform](ue_ue.PlayerController.md#k2_addactorlocaltransform)

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

[PlayerController](ue_ue.PlayerController.md).[K2_AddActorWorldOffset](ue_ue.PlayerController.md#k2_addactorworldoffset)

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

[PlayerController](ue_ue.PlayerController.md).[K2_AddActorWorldRotation](ue_ue.PlayerController.md#k2_addactorworldrotation)

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

[PlayerController](ue_ue.PlayerController.md).[K2_AddActorWorldTransform](ue_ue.PlayerController.md#k2_addactorworldtransform)

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

[PlayerController](ue_ue.PlayerController.md).[K2_AttachRootComponentTo](ue_ue.PlayerController.md#k2_attachrootcomponentto)

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

[PlayerController](ue_ue.PlayerController.md).[K2_AttachRootComponentToActor](ue_ue.PlayerController.md#k2_attachrootcomponenttoactor)

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

[PlayerController](ue_ue.PlayerController.md).[K2_AttachToActor](ue_ue.PlayerController.md#k2_attachtoactor)

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

[PlayerController](ue_ue.PlayerController.md).[K2_AttachToComponent](ue_ue.PlayerController.md#k2_attachtocomponent)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[K2_ClientPlayForceFeedback](ue_ue.PlayerController.md#k2_clientplayforcefeedback)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[K2_DestroyActor](ue_ue.PlayerController.md#k2_destroyactor)

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

[PlayerController](ue_ue.PlayerController.md).[K2_DestroyComponent](ue_ue.PlayerController.md#k2_destroycomponent)

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

[PlayerController](ue_ue.PlayerController.md).[K2_DetachFromActor](ue_ue.PlayerController.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[K2_GetActorLocation](ue_ue.PlayerController.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[K2_GetActorRotation](ue_ue.PlayerController.md#k2_getactorrotation)

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

[PlayerController](ue_ue.PlayerController.md).[K2_GetComponentsByClass](ue_ue.PlayerController.md#k2_getcomponentsbyclass)

___

### K2\_GetPawn

▸ **K2_GetPawn**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[K2_GetPawn](ue_ue.PlayerController.md#k2_getpawn)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[K2_GetRootComponent](ue_ue.PlayerController.md#k2_getrootcomponent)

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

[PlayerController](ue_ue.PlayerController.md).[K2_OnBecomeViewTarget](ue_ue.PlayerController.md#k2_onbecomeviewtarget)

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

[PlayerController](ue_ue.PlayerController.md).[K2_OnEndViewTarget](ue_ue.PlayerController.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[K2_OnReset](ue_ue.PlayerController.md#k2_onreset)

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

[PlayerController](ue_ue.PlayerController.md).[K2_SetActorLocation](ue_ue.PlayerController.md#k2_setactorlocation)

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

[PlayerController](ue_ue.PlayerController.md).[K2_SetActorLocationAndRotation](ue_ue.PlayerController.md#k2_setactorlocationandrotation)

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

[PlayerController](ue_ue.PlayerController.md).[K2_SetActorRelativeLocation](ue_ue.PlayerController.md#k2_setactorrelativelocation)

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

[PlayerController](ue_ue.PlayerController.md).[K2_SetActorRelativeRotation](ue_ue.PlayerController.md#k2_setactorrelativerotation)

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

[PlayerController](ue_ue.PlayerController.md).[K2_SetActorRelativeTransform](ue_ue.PlayerController.md#k2_setactorrelativetransform)

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

[PlayerController](ue_ue.PlayerController.md).[K2_SetActorRotation](ue_ue.PlayerController.md#k2_setactorrotation)

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

[PlayerController](ue_ue.PlayerController.md).[K2_SetActorTransform](ue_ue.PlayerController.md#k2_setactortransform)

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

[PlayerController](ue_ue.PlayerController.md).[K2_TeleportTo](ue_ue.PlayerController.md#k2_teleportto)

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

[PlayerController](ue_ue.PlayerController.md).[LineOfSightTo](ue_ue.PlayerController.md#lineofsightto)

___

### LocalTravel

▸ **LocalTravel**(`URL`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `URL` | `string` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[LocalTravel](ue_ue.PlayerController.md#localtravel)

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

[PlayerController](ue_ue.PlayerController.md).[MakeMIDForMaterial](ue_ue.PlayerController.md#makemidformaterial)

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

[PlayerController](ue_ue.PlayerController.md).[MakeNoise](ue_ue.PlayerController.md#makenoise)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnRep_AttachmentReplication](ue_ue.PlayerController.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnRep_Instigator](ue_ue.PlayerController.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnRep_Owner](ue_ue.PlayerController.md#onrep_owner)

___

### OnRep\_Pawn

▸ **OnRep_Pawn**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnRep_Pawn](ue_ue.PlayerController.md#onrep_pawn)

___

### OnRep\_PlayerState

▸ **OnRep_PlayerState**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnRep_PlayerState](ue_ue.PlayerController.md#onrep_playerstate)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnRep_ReplicateMovement](ue_ue.PlayerController.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnRep_ReplicatedMovement](ue_ue.PlayerController.md#onrep_replicatedmovement)

___

### OnServerStartedVisualLogger

▸ **OnServerStartedVisualLogger**(`bIsLogging`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIsLogging` | `boolean` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[OnServerStartedVisualLogger](ue_ue.PlayerController.md#onserverstartedvisuallogger)

___

### Pause

▸ **Pause**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[Pause](ue_ue.PlayerController.md#pause)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[PlayDynamicForceFeedback](ue_ue.PlayerController.md#playdynamicforcefeedback)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[PlayHapticEffect](ue_ue.PlayerController.md#playhapticeffect)

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

[PlayerController](ue_ue.PlayerController.md).[Possess](ue_ue.PlayerController.md#possess)

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

[PlayerController](ue_ue.PlayerController.md).[PrestreamTextures](ue_ue.PlayerController.md#prestreamtextures)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ProjectWorldLocationToScreen](ue_ue.PlayerController.md#projectworldlocationtoscreen)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ReceiveActorBeginCursorOver](ue_ue.PlayerController.md#receiveactorbegincursorover)

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

[PlayerController](ue_ue.PlayerController.md).[ReceiveActorBeginOverlap](ue_ue.PlayerController.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ReceiveActorEndCursorOver](ue_ue.PlayerController.md#receiveactorendcursorover)

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

[PlayerController](ue_ue.PlayerController.md).[ReceiveActorEndOverlap](ue_ue.PlayerController.md#receiveactorendoverlap)

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

[PlayerController](ue_ue.PlayerController.md).[ReceiveActorOnClicked](ue_ue.PlayerController.md#receiveactoronclicked)

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

[PlayerController](ue_ue.PlayerController.md).[ReceiveActorOnInputTouchBegin](ue_ue.PlayerController.md#receiveactoroninputtouchbegin)

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

[PlayerController](ue_ue.PlayerController.md).[ReceiveActorOnInputTouchEnd](ue_ue.PlayerController.md#receiveactoroninputtouchend)

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

[PlayerController](ue_ue.PlayerController.md).[ReceiveActorOnInputTouchEnter](ue_ue.PlayerController.md#receiveactoroninputtouchenter)

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

[PlayerController](ue_ue.PlayerController.md).[ReceiveActorOnInputTouchLeave](ue_ue.PlayerController.md#receiveactoroninputtouchleave)

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

[PlayerController](ue_ue.PlayerController.md).[ReceiveActorOnReleased](ue_ue.PlayerController.md#receiveactoronreleased)

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

[PlayerController](ue_ue.PlayerController.md).[ReceiveAnyDamage](ue_ue.PlayerController.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ReceiveBeginPlay](ue_ue.PlayerController.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ReceiveDestroyed](ue_ue.PlayerController.md#receivedestroyed)

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

[PlayerController](ue_ue.PlayerController.md).[ReceiveEndPlay](ue_ue.PlayerController.md#receiveendplay)

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

[PlayerController](ue_ue.PlayerController.md).[ReceiveHit](ue_ue.PlayerController.md#receivehit)

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

[PlayerController](ue_ue.PlayerController.md).[ReceiveInstigatedAnyDamage](ue_ue.PlayerController.md#receiveinstigatedanydamage)

___

### ReceiveOnActivate

▸ **ReceiveOnActivate**(`OriginalPC`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OriginalPC` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

___

### ReceiveOnActorSelected

▸ **ReceiveOnActorSelected**(`NewSelectedActor`, `SelectHitLocation`, `SelectHitNormal`, `Hit`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewSelectedActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `SelectHitLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `SelectHitNormal` | [`Vector`](ue_ue_s.Vector.md) |
| `Hit` | [`HitResult`](ue_ue.HitResult.md) |

#### Returns

`void`

___

### ReceiveOnDeactivate

▸ **ReceiveOnDeactivate**(`RestoredPC`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `RestoredPC` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

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

[PlayerController](ue_ue.PlayerController.md).[ReceivePointDamage](ue_ue.PlayerController.md#receivepointdamage)

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

[PlayerController](ue_ue.PlayerController.md).[ReceivePossess](ue_ue.PlayerController.md#receivepossess)

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

[PlayerController](ue_ue.PlayerController.md).[ReceiveRadialDamage](ue_ue.PlayerController.md#receiveradialdamage)

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

[PlayerController](ue_ue.PlayerController.md).[ReceiveTick](ue_ue.PlayerController.md#receivetick)

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

[PlayerController](ue_ue.PlayerController.md).[ReceiveUnPossess](ue_ue.PlayerController.md#receiveunpossess)

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

[PlayerController](ue_ue.PlayerController.md).[RemoveTickPrerequisiteActor](ue_ue.PlayerController.md#removetickprerequisiteactor)

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

[PlayerController](ue_ue.PlayerController.md).[RemoveTickPrerequisiteComponent](ue_ue.PlayerController.md#removetickprerequisitecomponent)

___

### ResetControllerLightColor

▸ **ResetControllerLightColor**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ResetControllerLightColor](ue_ue.PlayerController.md#resetcontrollerlightcolor)

___

### ResetIgnoreInputFlags

▸ **ResetIgnoreInputFlags**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ResetIgnoreInputFlags](ue_ue.PlayerController.md#resetignoreinputflags)

___

### ResetIgnoreLookInput

▸ **ResetIgnoreLookInput**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ResetIgnoreLookInput](ue_ue.PlayerController.md#resetignorelookinput)

___

### ResetIgnoreMoveInput

▸ **ResetIgnoreMoveInput**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ResetIgnoreMoveInput](ue_ue.PlayerController.md#resetignoremoveinput)

___

### RestartLevel

▸ **RestartLevel**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[RestartLevel](ue_ue.PlayerController.md#restartlevel)

___

### SendToConsole

▸ **SendToConsole**(`Command`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Command` | `string` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SendToConsole](ue_ue.PlayerController.md#sendtoconsole)

___

### ServerAcknowledgePossession

▸ **ServerAcknowledgePossession**(`P`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `P` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerAcknowledgePossession](ue_ue.PlayerController.md#serveracknowledgepossession)

___

### ServerCamera

▸ **ServerCamera**(`NewMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMode` | `string` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerCamera](ue_ue.PlayerController.md#servercamera)

___

### ServerChangeName

▸ **ServerChangeName**(`S`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `S` | `string` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerChangeName](ue_ue.PlayerController.md#serverchangename)

___

### ServerCheckClientPossession

▸ **ServerCheckClientPossession**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerCheckClientPossession](ue_ue.PlayerController.md#servercheckclientpossession)

___

### ServerCheckClientPossessionReliable

▸ **ServerCheckClientPossessionReliable**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerCheckClientPossessionReliable](ue_ue.PlayerController.md#servercheckclientpossessionreliable)

___

### ServerExec

▸ **ServerExec**(`Msg`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Msg` | `string` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerExec](ue_ue.PlayerController.md#serverexec)

___

### ServerExecRPC

▸ **ServerExecRPC**(`Msg`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Msg` | `string` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerExecRPC](ue_ue.PlayerController.md#serverexecrpc)

___

### ServerMutePlayer

▸ **ServerMutePlayer**(`PlayerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerId` | [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md) |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerMutePlayer](ue_ue.PlayerController.md#servermuteplayer)

___

### ServerNotifyLoadedWorld

▸ **ServerNotifyLoadedWorld**(`WorldPackageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldPackageName` | `string` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerNotifyLoadedWorld](ue_ue.PlayerController.md#servernotifyloadedworld)

___

### ServerPause

▸ **ServerPause**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerPause](ue_ue.PlayerController.md#serverpause)

___

### ServerRestartPlayer

▸ **ServerRestartPlayer**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerRestartPlayer](ue_ue.PlayerController.md#serverrestartplayer)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerSetSpectatorLocation](ue_ue.PlayerController.md#serversetspectatorlocation)

___

### ServerSetSpectatorWaiting

▸ **ServerSetSpectatorWaiting**(`bWaiting`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bWaiting` | `boolean` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerSetSpectatorWaiting](ue_ue.PlayerController.md#serversetspectatorwaiting)

___

### ServerShortTimeout

▸ **ServerShortTimeout**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerShortTimeout](ue_ue.PlayerController.md#servershorttimeout)

___

### ServerToggleAILogging

▸ **ServerToggleAILogging**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerToggleAILogging](ue_ue.PlayerController.md#servertoggleailogging)

___

### ServerUnmutePlayer

▸ **ServerUnmutePlayer**(`PlayerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerId` | [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md) |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerUnmutePlayer](ue_ue.PlayerController.md#serverunmuteplayer)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerUpdateCamera](ue_ue.PlayerController.md#serverupdatecamera)

___

### ServerUpdateLevelVisibility

▸ **ServerUpdateLevelVisibility**(`LevelVisibility`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LevelVisibility` | [`UpdateLevelVisibilityLevelInfo`](ue_ue.UpdateLevelVisibilityLevelInfo.md) |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerUpdateLevelVisibility](ue_ue.PlayerController.md#serverupdatelevelvisibility)

___

### ServerUpdateMultipleLevelsVisibility

▸ **ServerUpdateMultipleLevelsVisibility**(`LevelVisibilities`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LevelVisibilities` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UpdateLevelVisibilityLevelInfo`](ue_ue.UpdateLevelVisibilityLevelInfo.md)\> |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerUpdateMultipleLevelsVisibility](ue_ue.PlayerController.md#serverupdatemultiplelevelsvisibility)

___

### ServerVerifyViewTarget

▸ **ServerVerifyViewTarget**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerVerifyViewTarget](ue_ue.PlayerController.md#serververifyviewtarget)

___

### ServerViewNextPlayer

▸ **ServerViewNextPlayer**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerViewNextPlayer](ue_ue.PlayerController.md#serverviewnextplayer)

___

### ServerViewPrevPlayer

▸ **ServerViewPrevPlayer**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerViewPrevPlayer](ue_ue.PlayerController.md#serverviewprevplayer)

___

### ServerViewSelf

▸ **ServerViewSelf**(`TransitionParams`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TransitionParams` | [`ViewTargetTransitionParams`](ue_ue.ViewTargetTransitionParams.md) |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ServerViewSelf](ue_ue.PlayerController.md#serverviewself)

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

[PlayerController](ue_ue.PlayerController.md).[SetActorEnableCollision](ue_ue.PlayerController.md#setactorenablecollision)

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

[PlayerController](ue_ue.PlayerController.md).[SetActorHiddenInGame](ue_ue.PlayerController.md#setactorhiddeningame)

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

[PlayerController](ue_ue.PlayerController.md).[SetActorLabel](ue_ue.PlayerController.md#setactorlabel)

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

[PlayerController](ue_ue.PlayerController.md).[SetActorRelativeScale3D](ue_ue.PlayerController.md#setactorrelativescale3d)

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

[PlayerController](ue_ue.PlayerController.md).[SetActorScale3D](ue_ue.PlayerController.md#setactorscale3d)

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

[PlayerController](ue_ue.PlayerController.md).[SetActorTickEnabled](ue_ue.PlayerController.md#setactortickenabled)

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

[PlayerController](ue_ue.PlayerController.md).[SetActorTickInterval](ue_ue.PlayerController.md#setactortickinterval)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SetAudioListenerAttenuationOverride](ue_ue.PlayerController.md#setaudiolistenerattenuationoverride)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SetAudioListenerOverride](ue_ue.PlayerController.md#setaudiolisteneroverride)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SetCinematicMode](ue_ue.PlayerController.md#setcinematicmode)

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

[PlayerController](ue_ue.PlayerController.md).[SetControlRotation](ue_ue.PlayerController.md#setcontrolrotation)

___

### SetControllerLightColor

▸ **SetControllerLightColor**(`Color`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Color` | [`Color`](ue_ue_s.Color.md) |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SetControllerLightColor](ue_ue.PlayerController.md#setcontrollerlightcolor)

___

### SetDisableHaptics

▸ **SetDisableHaptics**(`bNewDisabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewDisabled` | `boolean` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SetDisableHaptics](ue_ue.PlayerController.md#setdisablehaptics)

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

[PlayerController](ue_ue.PlayerController.md).[SetFolderPath](ue_ue.PlayerController.md#setfolderpath)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SetHapticsByValue](ue_ue.PlayerController.md#sethapticsbyvalue)

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

[PlayerController](ue_ue.PlayerController.md).[SetIgnoreLookInput](ue_ue.PlayerController.md#setignorelookinput)

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

[PlayerController](ue_ue.PlayerController.md).[SetIgnoreMoveInput](ue_ue.PlayerController.md#setignoremoveinput)

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

[PlayerController](ue_ue.PlayerController.md).[SetInitialLocationAndRotation](ue_ue.PlayerController.md#setinitiallocationandrotation)

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

[PlayerController](ue_ue.PlayerController.md).[SetIsTemporarilyHiddenInEditor](ue_ue.PlayerController.md#setistemporarilyhiddenineditor)

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

[PlayerController](ue_ue.PlayerController.md).[SetLifeSpan](ue_ue.PlayerController.md#setlifespan)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SetMouseCursorWidget](ue_ue.PlayerController.md#setmousecursorwidget)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SetMouseLocation](ue_ue.PlayerController.md#setmouselocation)

___

### SetName

▸ **SetName**(`S`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `S` | `string` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SetName](ue_ue.PlayerController.md#setname)

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

[PlayerController](ue_ue.PlayerController.md).[SetNetDormancy](ue_ue.PlayerController.md#setnetdormancy)

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

[PlayerController](ue_ue.PlayerController.md).[SetOwner](ue_ue.PlayerController.md#setowner)

___

### SetPawnMovementSpeedScale

▸ **SetPawnMovementSpeedScale**(`NewSpeedScale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewSpeedScale` | `number` |

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

[PlayerController](ue_ue.PlayerController.md).[SetReplicateMovement](ue_ue.PlayerController.md#setreplicatemovement)

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

[PlayerController](ue_ue.PlayerController.md).[SetReplicates](ue_ue.PlayerController.md#setreplicates)

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

[PlayerController](ue_ue.PlayerController.md).[SetTickGroup](ue_ue.PlayerController.md#settickgroup)

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

[PlayerController](ue_ue.PlayerController.md).[SetTickableWhenPaused](ue_ue.PlayerController.md#settickablewhenpaused)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SetViewTargetWithBlend](ue_ue.PlayerController.md#setviewtargetwithblend)

___

### SetVirtualJoystickVisibility

▸ **SetVirtualJoystickVisibility**(`bVisible`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bVisible` | `boolean` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SetVirtualJoystickVisibility](ue_ue.PlayerController.md#setvirtualjoystickvisibility)

___

### ShowDebugSelectedInfo

▸ **ShowDebugSelectedInfo**(): `void`

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

[PlayerController](ue_ue.PlayerController.md).[SnapRootComponentTo](ue_ue.PlayerController.md#snaprootcomponentto)

___

### StartFire

▸ **StartFire**(`FireModeNum?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FireModeNum?` | `number` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[StartFire](ue_ue.PlayerController.md#startfire)

___

### StopHapticEffect

▸ **StopHapticEffect**(`Hand`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[StopHapticEffect](ue_ue.PlayerController.md#stophapticeffect)

___

### StopMovement

▸ **StopMovement**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[StopMovement](ue_ue.PlayerController.md#stopmovement)

___

### SwitchLevel

▸ **SwitchLevel**(`URL`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `URL` | `string` |

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[SwitchLevel](ue_ue.PlayerController.md#switchlevel)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[TearOff](ue_ue.PlayerController.md#tearoff)

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[TestServerLevelVisibilityChange](ue_ue.PlayerController.md#testserverlevelvisibilitychange)

___

### ToggleDisplay

▸ **ToggleDisplay**(): `void`

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

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[ToggleSpeaking](ue_ue.PlayerController.md#togglespeaking)

___

### UnPossess

▸ **UnPossess**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[UnPossess](ue_ue.PlayerController.md#unpossess)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[UserConstructionScript](ue_ue.PlayerController.md#userconstructionscript)

___

### WasInputKeyJustPressed

▸ **WasInputKeyJustPressed**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[WasInputKeyJustPressed](ue_ue.PlayerController.md#wasinputkeyjustpressed)

___

### WasInputKeyJustReleased

▸ **WasInputKeyJustReleased**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

#### Inherited from

[PlayerController](ue_ue.PlayerController.md).[WasInputKeyJustReleased](ue_ue.PlayerController.md#wasinputkeyjustreleased)

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

[PlayerController](ue_ue.PlayerController.md).[WasRecentlyRendered](ue_ue.PlayerController.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DebugCameraController`](ue_ue.DebugCameraController.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DebugCameraController`](ue_ue.DebugCameraController.md)

#### Overrides

[PlayerController](ue_ue.PlayerController.md).[Find](ue_ue.PlayerController.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DebugCameraController`](ue_ue.DebugCameraController.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DebugCameraController`](ue_ue.DebugCameraController.md)

#### Overrides

[PlayerController](ue_ue.PlayerController.md).[Load](ue_ue.PlayerController.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PlayerController](ue_ue.PlayerController.md).[StaticClass](ue_ue.PlayerController.md#staticclass)
