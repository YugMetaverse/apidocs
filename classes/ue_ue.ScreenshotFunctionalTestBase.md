[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ScreenshotFunctionalTestBase

# Class: ScreenshotFunctionalTestBase

[ue/ue](../modules/ue_ue.md).ScreenshotFunctionalTestBase

## Hierarchy

- [`FunctionalTest`](ue_ue.FunctionalTest.md)

  ↳ **`ScreenshotFunctionalTestBase`**

  ↳↳ [`FunctionalUIScreenshotTest`](ue_ue.FunctionalUIScreenshotTest.md)

  ↳↳ [`ScreenshotFunctionalTest`](ue_ue.ScreenshotFunctionalTest.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ScreenshotFunctionalTestBase.md#constructor)

### Properties

- [ActorLabel](ue_ue.ScreenshotFunctionalTestBase.md#actorlabel)
- [AttachmentReplication](ue_ue.ScreenshotFunctionalTestBase.md#attachmentreplication)
- [Author](ue_ue.ScreenshotFunctionalTestBase.md#author)
- [AutoDestroyActors](ue_ue.ScreenshotFunctionalTestBase.md#autodestroyactors)
- [AutoReceiveInput](ue_ue.ScreenshotFunctionalTestBase.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.ScreenshotFunctionalTestBase.md#blueprintcreatedcomponents)
- [Children](ue_ue.ScreenshotFunctionalTestBase.md#children)
- [ControllingMatineeActors](ue_ue.ScreenshotFunctionalTestBase.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.ScreenshotFunctionalTestBase.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.ScreenshotFunctionalTestBase.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [Description](ue_ue.ScreenshotFunctionalTestBase.md#description)
- [FolderPath](ue_ue.ScreenshotFunctionalTestBase.md#folderpath)
- [GroupActor](ue_ue.ScreenshotFunctionalTestBase.md#groupactor)
- [HiddenEditorViews](ue_ue.ScreenshotFunctionalTestBase.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.ScreenshotFunctionalTestBase.md#initiallifespan)
- [InputComponent](ue_ue.ScreenshotFunctionalTestBase.md#inputcomponent)
- [InputPriority](ue_ue.ScreenshotFunctionalTestBase.md#inputpriority)
- [InstanceComponents](ue_ue.ScreenshotFunctionalTestBase.md#instancecomponents)
- [Instigator](ue_ue.ScreenshotFunctionalTestBase.md#instigator)
- [Layers](ue_ue.ScreenshotFunctionalTestBase.md#layers)
- [LogErrorHandling](ue_ue.ScreenshotFunctionalTestBase.md#logerrorhandling)
- [LogWarningHandling](ue_ue.ScreenshotFunctionalTestBase.md#logwarninghandling)
- [MinNetUpdateFrequency](ue_ue.ScreenshotFunctionalTestBase.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.ScreenshotFunctionalTestBase.md#netculldistancesquared)
- [NetDormancy](ue_ue.ScreenshotFunctionalTestBase.md#netdormancy)
- [NetDriverName](ue_ue.ScreenshotFunctionalTestBase.md#netdrivername)
- [NetPriority](ue_ue.ScreenshotFunctionalTestBase.md#netpriority)
- [NetTag](ue_ue.ScreenshotFunctionalTestBase.md#nettag)
- [NetUpdateFrequency](ue_ue.ScreenshotFunctionalTestBase.md#netupdatefrequency)
- [Notes](ue_ue.ScreenshotFunctionalTestBase.md#notes)
- [ObservationPoint](ue_ue.ScreenshotFunctionalTestBase.md#observationpoint)
- [OnActorBeginOverlap](ue_ue.ScreenshotFunctionalTestBase.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.ScreenshotFunctionalTestBase.md#onactorendoverlap)
- [OnActorHit](ue_ue.ScreenshotFunctionalTestBase.md#onactorhit)
- [OnBeginCursorOver](ue_ue.ScreenshotFunctionalTestBase.md#onbegincursorover)
- [OnClicked](ue_ue.ScreenshotFunctionalTestBase.md#onclicked)
- [OnDestroyed](ue_ue.ScreenshotFunctionalTestBase.md#ondestroyed)
- [OnEndCursorOver](ue_ue.ScreenshotFunctionalTestBase.md#onendcursorover)
- [OnEndPlay](ue_ue.ScreenshotFunctionalTestBase.md#onendplay)
- [OnInputTouchBegin](ue_ue.ScreenshotFunctionalTestBase.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.ScreenshotFunctionalTestBase.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.ScreenshotFunctionalTestBase.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.ScreenshotFunctionalTestBase.md#oninputtouchleave)
- [OnReleased](ue_ue.ScreenshotFunctionalTestBase.md#onreleased)
- [OnTakeAnyDamage](ue_ue.ScreenshotFunctionalTestBase.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.ScreenshotFunctionalTestBase.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.ScreenshotFunctionalTestBase.md#ontakeradialdamage)
- [OnTestFinished](ue_ue.ScreenshotFunctionalTestBase.md#ontestfinished)
- [OnTestPrepare](ue_ue.ScreenshotFunctionalTestBase.md#ontestprepare)
- [OnTestStart](ue_ue.ScreenshotFunctionalTestBase.md#onteststart)
- [Owner](ue_ue.ScreenshotFunctionalTestBase.md#owner)
- [ParentComponent](ue_ue.ScreenshotFunctionalTestBase.md#parentcomponent)
- [ParentComponentActor](ue_ue.ScreenshotFunctionalTestBase.md#parentcomponentactor)
- [PivotOffset](ue_ue.ScreenshotFunctionalTestBase.md#pivotoffset)
- [PreparationTimeLimit](ue_ue.ScreenshotFunctionalTestBase.md#preparationtimelimit)
- [PrimaryActorTick](ue_ue.ScreenshotFunctionalTestBase.md#primaryactortick)
- [RandomNumbersStream](ue_ue.ScreenshotFunctionalTestBase.md#randomnumbersstream)
- [RemoteRole](ue_ue.ScreenshotFunctionalTestBase.md#remoterole)
- [RenderComp](ue_ue.ScreenshotFunctionalTestBase.md#rendercomp)
- [ReplicatedMovement](ue_ue.ScreenshotFunctionalTestBase.md#replicatedmovement)
- [Result](ue_ue.ScreenshotFunctionalTestBase.md#result)
- [Role](ue_ue.ScreenshotFunctionalTestBase.md#role)
- [RootComponent](ue_ue.ScreenshotFunctionalTestBase.md#rootcomponent)
- [ScreenshotCamera](ue_ue.ScreenshotFunctionalTestBase.md#screenshotcamera)
- [ScreenshotOptions](ue_ue.ScreenshotFunctionalTestBase.md#screenshotoptions)
- [SpawnCollisionHandlingMethod](ue_ue.ScreenshotFunctionalTestBase.md#spawncollisionhandlingmethod)
- [SpriteComponent](ue_ue.ScreenshotFunctionalTestBase.md#spritecomponent)
- [SpriteScale](ue_ue.ScreenshotFunctionalTestBase.md#spritescale)
- [Tags](ue_ue.ScreenshotFunctionalTestBase.md#tags)
- [TestName](ue_ue.ScreenshotFunctionalTestBase.md#testname)
- [TimeLimit](ue_ue.ScreenshotFunctionalTestBase.md#timelimit)
- [TimesUpMessage](ue_ue.ScreenshotFunctionalTestBase.md#timesupmessage)
- [TimesUpResult](ue_ue.ScreenshotFunctionalTestBase.md#timesupresult)
- [TotalTime](ue_ue.ScreenshotFunctionalTestBase.md#totaltime)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.ScreenshotFunctionalTestBase.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.ScreenshotFunctionalTestBase.md#__tid_actor__)
- [\_\_tid\_FunctionalTest\_\_](ue_ue.ScreenshotFunctionalTestBase.md#__tid_functionaltest__)
- [\_\_tid\_Object\_\_](ue_ue.ScreenshotFunctionalTestBase.md#__tid_object__)
- [\_\_tid\_ScreenshotFunctionalTestBase\_\_](ue_ue.ScreenshotFunctionalTestBase.md#__tid_screenshotfunctionaltestbase__)
- [bActorEnableCollision](ue_ue.ScreenshotFunctionalTestBase.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.ScreenshotFunctionalTestBase.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.ScreenshotFunctionalTestBase.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.ScreenshotFunctionalTestBase.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.ScreenshotFunctionalTestBase.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.ScreenshotFunctionalTestBase.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.ScreenshotFunctionalTestBase.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.ScreenshotFunctionalTestBase.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.ScreenshotFunctionalTestBase.md#bblockinput)
- [bCanBeDamaged](ue_ue.ScreenshotFunctionalTestBase.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.ScreenshotFunctionalTestBase.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.ScreenshotFunctionalTestBase.md#bcollidewhenplacing)
- [bEditable](ue_ue.ScreenshotFunctionalTestBase.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.ScreenshotFunctionalTestBase.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.ScreenshotFunctionalTestBase.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.ScreenshotFunctionalTestBase.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.ScreenshotFunctionalTestBase.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.ScreenshotFunctionalTestBase.md#bhidden)
- [bHiddenEd](ue_ue.ScreenshotFunctionalTestBase.md#bhiddened)
- [bHiddenEdLayer](ue_ue.ScreenshotFunctionalTestBase.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.ScreenshotFunctionalTestBase.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.ScreenshotFunctionalTestBase.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.ScreenshotFunctionalTestBase.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.ScreenshotFunctionalTestBase.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.ScreenshotFunctionalTestBase.md#biseditorpreviewactor)
- [bIsEnabled](ue_ue.ScreenshotFunctionalTestBase.md#bisenabled)
- [bIsRunning](ue_ue.ScreenshotFunctionalTestBase.md#bisrunning)
- [bListedInSceneOutliner](ue_ue.ScreenshotFunctionalTestBase.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.ScreenshotFunctionalTestBase.md#blocklocation)
- [bNetLoadOnClient](ue_ue.ScreenshotFunctionalTestBase.md#bnetloadonclient)
- [bNetStartup](ue_ue.ScreenshotFunctionalTestBase.md#bnetstartup)
- [bNetTemporary](ue_ue.ScreenshotFunctionalTestBase.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.ScreenshotFunctionalTestBase.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.ScreenshotFunctionalTestBase.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.ScreenshotFunctionalTestBase.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.ScreenshotFunctionalTestBase.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.ScreenshotFunctionalTestBase.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.ScreenshotFunctionalTestBase.md#breplayrewindable)
- [bReplicateMovement](ue_ue.ScreenshotFunctionalTestBase.md#breplicatemovement)
- [bReplicates](ue_ue.ScreenshotFunctionalTestBase.md#breplicates)
- [bTearOff](ue_ue.ScreenshotFunctionalTestBase.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.ScreenshotFunctionalTestBase.md#actorhastag)
- [AddComponent](ue_ue.ScreenshotFunctionalTestBase.md#addcomponent)
- [AddError](ue_ue.ScreenshotFunctionalTestBase.md#adderror)
- [AddRerun](ue_ue.ScreenshotFunctionalTestBase.md#addrerun)
- [AddTickPrerequisiteActor](ue_ue.ScreenshotFunctionalTestBase.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.ScreenshotFunctionalTestBase.md#addtickprerequisitecomponent)
- [AddWarning](ue_ue.ScreenshotFunctionalTestBase.md#addwarning)
- [AssertEqual\_Bool](ue_ue.ScreenshotFunctionalTestBase.md#assertequal_bool)
- [AssertEqual\_Float](ue_ue.ScreenshotFunctionalTestBase.md#assertequal_float)
- [AssertEqual\_Int](ue_ue.ScreenshotFunctionalTestBase.md#assertequal_int)
- [AssertEqual\_Name](ue_ue.ScreenshotFunctionalTestBase.md#assertequal_name)
- [AssertEqual\_Rotator](ue_ue.ScreenshotFunctionalTestBase.md#assertequal_rotator)
- [AssertEqual\_String](ue_ue.ScreenshotFunctionalTestBase.md#assertequal_string)
- [AssertEqual\_TraceQueryResults](ue_ue.ScreenshotFunctionalTestBase.md#assertequal_tracequeryresults)
- [AssertEqual\_Transform](ue_ue.ScreenshotFunctionalTestBase.md#assertequal_transform)
- [AssertEqual\_Vector](ue_ue.ScreenshotFunctionalTestBase.md#assertequal_vector)
- [AssertFalse](ue_ue.ScreenshotFunctionalTestBase.md#assertfalse)
- [AssertIsValid](ue_ue.ScreenshotFunctionalTestBase.md#assertisvalid)
- [AssertNotEqual\_Rotator](ue_ue.ScreenshotFunctionalTestBase.md#assertnotequal_rotator)
- [AssertNotEqual\_String](ue_ue.ScreenshotFunctionalTestBase.md#assertnotequal_string)
- [AssertNotEqual\_Transform](ue_ue.ScreenshotFunctionalTestBase.md#assertnotequal_transform)
- [AssertNotEqual\_Vector](ue_ue.ScreenshotFunctionalTestBase.md#assertnotequal_vector)
- [AssertTrue](ue_ue.ScreenshotFunctionalTestBase.md#asserttrue)
- [AssertValue\_DateTime](ue_ue.ScreenshotFunctionalTestBase.md#assertvalue_datetime)
- [AssertValue\_Float](ue_ue.ScreenshotFunctionalTestBase.md#assertvalue_float)
- [AssertValue\_Int](ue_ue.ScreenshotFunctionalTestBase.md#assertvalue_int)
- [CreateDefaultSubobject](ue_ue.ScreenshotFunctionalTestBase.md#createdefaultsubobject)
- [DebugGatherRelevantActors](ue_ue.ScreenshotFunctionalTestBase.md#debuggatherrelevantactors)
- [DetachRootComponentFromParent](ue_ue.ScreenshotFunctionalTestBase.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.ScreenshotFunctionalTestBase.md#disableinput)
- [EnableInput](ue_ue.ScreenshotFunctionalTestBase.md#enableinput)
- [ExecuteUbergraph](ue_ue.ScreenshotFunctionalTestBase.md#executeubergraph)
- [FinishTest](ue_ue.ScreenshotFunctionalTestBase.md#finishtest)
- [FlushNetDormancy](ue_ue.ScreenshotFunctionalTestBase.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.ScreenshotFunctionalTestBase.md#forcenetupdate)
- [GetActorBounds](ue_ue.ScreenshotFunctionalTestBase.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.ScreenshotFunctionalTestBase.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.ScreenshotFunctionalTestBase.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.ScreenshotFunctionalTestBase.md#getactorforwardvector)
- [GetActorLabel](ue_ue.ScreenshotFunctionalTestBase.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.ScreenshotFunctionalTestBase.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.ScreenshotFunctionalTestBase.md#getactorrightvector)
- [GetActorScale3D](ue_ue.ScreenshotFunctionalTestBase.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.ScreenshotFunctionalTestBase.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.ScreenshotFunctionalTestBase.md#getactortimedilation)
- [GetActorUpVector](ue_ue.ScreenshotFunctionalTestBase.md#getactorupvector)
- [GetAllChildActors](ue_ue.ScreenshotFunctionalTestBase.md#getallchildactors)
- [GetAttachParentActor](ue_ue.ScreenshotFunctionalTestBase.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.ScreenshotFunctionalTestBase.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.ScreenshotFunctionalTestBase.md#getattachedactors)
- [GetClass](ue_ue.ScreenshotFunctionalTestBase.md#getclass)
- [GetComponentByClass](ue_ue.ScreenshotFunctionalTestBase.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.ScreenshotFunctionalTestBase.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.ScreenshotFunctionalTestBase.md#getcomponentsbytag)
- [GetCurrentRerunReason](ue_ue.ScreenshotFunctionalTestBase.md#getcurrentrerunreason)
- [GetDistanceTo](ue_ue.ScreenshotFunctionalTestBase.md#getdistanceto)
- [GetDotProductTo](ue_ue.ScreenshotFunctionalTestBase.md#getdotproductto)
- [GetFolderPath](ue_ue.ScreenshotFunctionalTestBase.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.ScreenshotFunctionalTestBase.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.ScreenshotFunctionalTestBase.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.ScreenshotFunctionalTestBase.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.ScreenshotFunctionalTestBase.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.ScreenshotFunctionalTestBase.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.ScreenshotFunctionalTestBase.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.ScreenshotFunctionalTestBase.md#getinstigator)
- [GetInstigatorController](ue_ue.ScreenshotFunctionalTestBase.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.ScreenshotFunctionalTestBase.md#getlifespan)
- [GetLocalRole](ue_ue.ScreenshotFunctionalTestBase.md#getlocalrole)
- [GetName](ue_ue.ScreenshotFunctionalTestBase.md#getname)
- [GetOuter](ue_ue.ScreenshotFunctionalTestBase.md#getouter)
- [GetOverlappingActors](ue_ue.ScreenshotFunctionalTestBase.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.ScreenshotFunctionalTestBase.md#getoverlappingcomponents)
- [GetOwner](ue_ue.ScreenshotFunctionalTestBase.md#getowner)
- [GetParentActor](ue_ue.ScreenshotFunctionalTestBase.md#getparentactor)
- [GetParentComponent](ue_ue.ScreenshotFunctionalTestBase.md#getparentcomponent)
- [GetRemoteRole](ue_ue.ScreenshotFunctionalTestBase.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.ScreenshotFunctionalTestBase.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.ScreenshotFunctionalTestBase.md#gettickablewhenpaused)
- [GetTransform](ue_ue.ScreenshotFunctionalTestBase.md#gettransform)
- [GetVelocity](ue_ue.ScreenshotFunctionalTestBase.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.ScreenshotFunctionalTestBase.md#getverticaldistanceto)
- [GetWorld](ue_ue.ScreenshotFunctionalTestBase.md#getworld)
- [HasAuthority](ue_ue.ScreenshotFunctionalTestBase.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.ScreenshotFunctionalTestBase.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.ScreenshotFunctionalTestBase.md#isactortickenabled)
- [IsChildActor](ue_ue.ScreenshotFunctionalTestBase.md#ischildactor)
- [IsEditable](ue_ue.ScreenshotFunctionalTestBase.md#iseditable)
- [IsEnabled](ue_ue.ScreenshotFunctionalTestBase.md#isenabled)
- [IsHiddenEd](ue_ue.ScreenshotFunctionalTestBase.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.ScreenshotFunctionalTestBase.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.ScreenshotFunctionalTestBase.md#isoverlappingactor)
- [IsReady](ue_ue.ScreenshotFunctionalTestBase.md#isready)
- [IsRunning](ue_ue.ScreenshotFunctionalTestBase.md#isrunning)
- [IsSelectable](ue_ue.ScreenshotFunctionalTestBase.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.ScreenshotFunctionalTestBase.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.ScreenshotFunctionalTestBase.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.ScreenshotFunctionalTestBase.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.ScreenshotFunctionalTestBase.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.ScreenshotFunctionalTestBase.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.ScreenshotFunctionalTestBase.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.ScreenshotFunctionalTestBase.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.ScreenshotFunctionalTestBase.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.ScreenshotFunctionalTestBase.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.ScreenshotFunctionalTestBase.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.ScreenshotFunctionalTestBase.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.ScreenshotFunctionalTestBase.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.ScreenshotFunctionalTestBase.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.ScreenshotFunctionalTestBase.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.ScreenshotFunctionalTestBase.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.ScreenshotFunctionalTestBase.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.ScreenshotFunctionalTestBase.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.ScreenshotFunctionalTestBase.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.ScreenshotFunctionalTestBase.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.ScreenshotFunctionalTestBase.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.ScreenshotFunctionalTestBase.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.ScreenshotFunctionalTestBase.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.ScreenshotFunctionalTestBase.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.ScreenshotFunctionalTestBase.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.ScreenshotFunctionalTestBase.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.ScreenshotFunctionalTestBase.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.ScreenshotFunctionalTestBase.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.ScreenshotFunctionalTestBase.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.ScreenshotFunctionalTestBase.md#k2_teleportto)
- [LogMessage](ue_ue.ScreenshotFunctionalTestBase.md#logmessage)
- [MakeMIDForMaterial](ue_ue.ScreenshotFunctionalTestBase.md#makemidformaterial)
- [MakeNoise](ue_ue.ScreenshotFunctionalTestBase.md#makenoise)
- [OnAdditionalTestFinishedMessageRequest](ue_ue.ScreenshotFunctionalTestBase.md#onadditionaltestfinishedmessagerequest)
- [OnRep\_AttachmentReplication](ue_ue.ScreenshotFunctionalTestBase.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.ScreenshotFunctionalTestBase.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.ScreenshotFunctionalTestBase.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.ScreenshotFunctionalTestBase.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.ScreenshotFunctionalTestBase.md#onrep_replicatedmovement)
- [OnWantsReRunCheck](ue_ue.ScreenshotFunctionalTestBase.md#onwantsreruncheck)
- [PrestreamTextures](ue_ue.ScreenshotFunctionalTestBase.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.ScreenshotFunctionalTestBase.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.ScreenshotFunctionalTestBase.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.ScreenshotFunctionalTestBase.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.ScreenshotFunctionalTestBase.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.ScreenshotFunctionalTestBase.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.ScreenshotFunctionalTestBase.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.ScreenshotFunctionalTestBase.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.ScreenshotFunctionalTestBase.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.ScreenshotFunctionalTestBase.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.ScreenshotFunctionalTestBase.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.ScreenshotFunctionalTestBase.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.ScreenshotFunctionalTestBase.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.ScreenshotFunctionalTestBase.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.ScreenshotFunctionalTestBase.md#receiveendplay)
- [ReceiveHit](ue_ue.ScreenshotFunctionalTestBase.md#receivehit)
- [ReceivePointDamage](ue_ue.ScreenshotFunctionalTestBase.md#receivepointdamage)
- [ReceivePrepareTest](ue_ue.ScreenshotFunctionalTestBase.md#receivepreparetest)
- [ReceiveRadialDamage](ue_ue.ScreenshotFunctionalTestBase.md#receiveradialdamage)
- [ReceiveStartTest](ue_ue.ScreenshotFunctionalTestBase.md#receivestarttest)
- [ReceiveTick](ue_ue.ScreenshotFunctionalTestBase.md#receivetick)
- [RegisterAutoDestroyActor](ue_ue.ScreenshotFunctionalTestBase.md#registerautodestroyactor)
- [RemoveTickPrerequisiteActor](ue_ue.ScreenshotFunctionalTestBase.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.ScreenshotFunctionalTestBase.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.ScreenshotFunctionalTestBase.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.ScreenshotFunctionalTestBase.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.ScreenshotFunctionalTestBase.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.ScreenshotFunctionalTestBase.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.ScreenshotFunctionalTestBase.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.ScreenshotFunctionalTestBase.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.ScreenshotFunctionalTestBase.md#setactortickinterval)
- [SetFolderPath](ue_ue.ScreenshotFunctionalTestBase.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.ScreenshotFunctionalTestBase.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.ScreenshotFunctionalTestBase.md#setlifespan)
- [SetNetDormancy](ue_ue.ScreenshotFunctionalTestBase.md#setnetdormancy)
- [SetOwner](ue_ue.ScreenshotFunctionalTestBase.md#setowner)
- [SetReplicateMovement](ue_ue.ScreenshotFunctionalTestBase.md#setreplicatemovement)
- [SetReplicates](ue_ue.ScreenshotFunctionalTestBase.md#setreplicates)
- [SetTickGroup](ue_ue.ScreenshotFunctionalTestBase.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.ScreenshotFunctionalTestBase.md#settickablewhenpaused)
- [SetTimeLimit](ue_ue.ScreenshotFunctionalTestBase.md#settimelimit)
- [SnapRootComponentTo](ue_ue.ScreenshotFunctionalTestBase.md#snaprootcomponentto)
- [TearOff](ue_ue.ScreenshotFunctionalTestBase.md#tearoff)
- [UserConstructionScript](ue_ue.ScreenshotFunctionalTestBase.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.ScreenshotFunctionalTestBase.md#wasrecentlyrendered)
- [Find](ue_ue.ScreenshotFunctionalTestBase.md#find)
- [Load](ue_ue.ScreenshotFunctionalTestBase.md#load)
- [StaticClass](ue_ue.ScreenshotFunctionalTestBase.md#staticclass)

## Constructors

### constructor

• **new ScreenshotFunctionalTestBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FunctionalTest](ue_ue.FunctionalTest.md).[constructor](ue_ue.FunctionalTest.md#constructor)

#### Defined in

[ue/ue.d.ts:36517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36517)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[ActorLabel](ue_ue.FunctionalTest.md#actorlabel)

#### Defined in

[ue/ue.d.ts:13176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13176)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AttachmentReplication](ue_ue.FunctionalTest.md#attachmentreplication)

#### Defined in

[ue/ue.d.ts:13151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13151)

___

### Author

• **Author**: `string`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[Author](ue_ue.FunctionalTest.md#author)

#### Defined in

[ue/ue.d.ts:36336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36336)

___

### AutoDestroyActors

• **AutoDestroyActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AutoDestroyActors](ue_ue.FunctionalTest.md#autodestroyactors)

#### Defined in

[ue/ue.d.ts:36348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36348)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AutoReceiveInput](ue_ue.FunctionalTest.md#autoreceiveinput)

#### Defined in

[ue/ue.d.ts:13157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13157)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[BlueprintCreatedComponents](ue_ue.FunctionalTest.md#blueprintcreatedcomponents)

#### Defined in

[ue/ue.d.ts:13206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13206)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[Children](ue_ue.FunctionalTest.md#children)

#### Defined in

[ue/ue.d.ts:13166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13166)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[ControllingMatineeActors](ue_ue.FunctionalTest.md#controllingmatineeactors)

#### Defined in

[ue/ue.d.ts:13169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13169)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[CustomTimeDilation](ue_ue.FunctionalTest.md#customtimedilation)

#### Defined in

[ue/ue.d.ts:13150](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13150)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.FunctionalTest.md#defaultupdateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13146](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13146)

___

### Description

• **Description**: `string`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[Description](ue_ue.FunctionalTest.md#description)

#### Defined in

[ue/ue.d.ts:36337](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36337)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[FolderPath](ue_ue.FunctionalTest.md#folderpath)

#### Defined in

[ue/ue.d.ts:13177](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13177)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GroupActor](ue_ue.FunctionalTest.md#groupactor)

#### Defined in

[ue/ue.d.ts:13173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13173)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[HiddenEditorViews](ue_ue.FunctionalTest.md#hiddeneditorviews)

#### Defined in

[ue/ue.d.ts:13175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13175)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[InitialLifeSpan](ue_ue.FunctionalTest.md#initiallifespan)

#### Defined in

[ue/ue.d.ts:13149](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13149)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[InputComponent](ue_ue.FunctionalTest.md#inputcomponent)

#### Defined in

[ue/ue.d.ts:13159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13159)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[InputPriority](ue_ue.FunctionalTest.md#inputpriority)

#### Defined in

[ue/ue.d.ts:13158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13158)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[InstanceComponents](ue_ue.FunctionalTest.md#instancecomponents)

#### Defined in

[ue/ue.d.ts:13205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13205)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[Instigator](ue_ue.FunctionalTest.md#instigator)

#### Defined in

[ue/ue.d.ts:13165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13165)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[Layers](ue_ue.FunctionalTest.md#layers)

#### Defined in

[ue/ue.d.ts:13170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13170)

___

### LogErrorHandling

• **LogErrorHandling**: [`EFunctionalTestLogHandling`](../enums/ue_ue.EFunctionalTestLogHandling.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[LogErrorHandling](ue_ue.FunctionalTest.md#logerrorhandling)

#### Defined in

[ue/ue.d.ts:36334](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36334)

___

### LogWarningHandling

• **LogWarningHandling**: [`EFunctionalTestLogHandling`](../enums/ue_ue.EFunctionalTestLogHandling.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[LogWarningHandling](ue_ue.FunctionalTest.md#logwarninghandling)

#### Defined in

[ue/ue.d.ts:36335](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36335)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[MinNetUpdateFrequency](ue_ue.FunctionalTest.md#minnetupdatefrequency)

#### Defined in

[ue/ue.d.ts:13163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13163)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[NetCullDistanceSquared](ue_ue.FunctionalTest.md#netculldistancesquared)

#### Defined in

[ue/ue.d.ts:13160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13160)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[NetDormancy](ue_ue.FunctionalTest.md#netdormancy)

#### Defined in

[ue/ue.d.ts:13155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13155)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[NetDriverName](ue_ue.FunctionalTest.md#netdrivername)

#### Defined in

[ue/ue.d.ts:13153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13153)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[NetPriority](ue_ue.FunctionalTest.md#netpriority)

#### Defined in

[ue/ue.d.ts:13164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13164)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[NetTag](ue_ue.FunctionalTest.md#nettag)

#### Defined in

[ue/ue.d.ts:13161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13161)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[NetUpdateFrequency](ue_ue.FunctionalTest.md#netupdatefrequency)

#### Defined in

[ue/ue.d.ts:13162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13162)

___

### Notes

• **Notes**: `string`

#### Defined in

[ue/ue.d.ts:36518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36518)

___

### ObservationPoint

• **ObservationPoint**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[ObservationPoint](ue_ue.FunctionalTest.md#observationpoint)

#### Defined in

[ue/ue.d.ts:36338](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36338)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnActorBeginOverlap](ue_ue.FunctionalTest.md#onactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13192)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnActorEndOverlap](ue_ue.FunctionalTest.md#onactorendoverlap)

#### Defined in

[ue/ue.d.ts:13193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13193)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnActorHit](ue_ue.FunctionalTest.md#onactorhit)

#### Defined in

[ue/ue.d.ts:13202](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13202)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnBeginCursorOver](ue_ue.FunctionalTest.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:13194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13194)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnClicked](ue_ue.FunctionalTest.md#onclicked)

#### Defined in

[ue/ue.d.ts:13196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13196)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnDestroyed](ue_ue.FunctionalTest.md#ondestroyed)

#### Defined in

[ue/ue.d.ts:13203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13203)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnEndCursorOver](ue_ue.FunctionalTest.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:13195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13195)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnEndPlay](ue_ue.FunctionalTest.md#onendplay)

#### Defined in

[ue/ue.d.ts:13204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13204)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnInputTouchBegin](ue_ue.FunctionalTest.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13198)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnInputTouchEnd](ue_ue.FunctionalTest.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:13199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13199)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnInputTouchEnter](ue_ue.FunctionalTest.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:13200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13200)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnInputTouchLeave](ue_ue.FunctionalTest.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:13201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13201)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnReleased](ue_ue.FunctionalTest.md#onreleased)

#### Defined in

[ue/ue.d.ts:13197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13197)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnTakeAnyDamage](ue_ue.FunctionalTest.md#ontakeanydamage)

#### Defined in

[ue/ue.d.ts:13189](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13189)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnTakePointDamage](ue_ue.FunctionalTest.md#ontakepointdamage)

#### Defined in

[ue/ue.d.ts:13190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13190)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnTakeRadialDamage](ue_ue.FunctionalTest.md#ontakeradialdamage)

#### Defined in

[ue/ue.d.ts:13191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13191)

___

### OnTestFinished

• **OnTestFinished**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnTestFinished](ue_ue.FunctionalTest.md#ontestfinished)

#### Defined in

[ue/ue.d.ts:36347](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36347)

___

### OnTestPrepare

• **OnTestPrepare**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnTestPrepare](ue_ue.FunctionalTest.md#ontestprepare)

#### Defined in

[ue/ue.d.ts:36345](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36345)

___

### OnTestStart

• **OnTestStart**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnTestStart](ue_ue.FunctionalTest.md#onteststart)

#### Defined in

[ue/ue.d.ts:36346](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36346)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[Owner](ue_ue.FunctionalTest.md#owner)

#### Defined in

[ue/ue.d.ts:13152](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13152)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[ParentComponent](ue_ue.FunctionalTest.md#parentcomponent)

#### Defined in

[ue/ue.d.ts:13172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13172)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[ParentComponentActor](ue_ue.FunctionalTest.md#parentcomponentactor)

#### Defined in

[ue/ue.d.ts:13171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13171)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[PivotOffset](ue_ue.FunctionalTest.md#pivotoffset)

#### Defined in

[ue/ue.d.ts:13168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13168)

___

### PreparationTimeLimit

• **PreparationTimeLimit**: `number`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[PreparationTimeLimit](ue_ue.FunctionalTest.md#preparationtimelimit)

#### Defined in

[ue/ue.d.ts:36341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36341)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[PrimaryActorTick](ue_ue.FunctionalTest.md#primaryactortick)

#### Defined in

[ue/ue.d.ts:13115](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13115)

___

### RandomNumbersStream

• **RandomNumbersStream**: [`RandomStream`](ue_ue.RandomStream.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[RandomNumbersStream](ue_ue.FunctionalTest.md#randomnumbersstream)

#### Defined in

[ue/ue.d.ts:36339](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36339)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[RemoteRole](ue_ue.FunctionalTest.md#remoterole)

#### Defined in

[ue/ue.d.ts:13147](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13147)

___

### RenderComp

• **RenderComp**: [`FuncTestRenderingComponent`](ue_ue.FuncTestRenderingComponent.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[RenderComp](ue_ue.FunctionalTest.md#rendercomp)

#### Defined in

[ue/ue.d.ts:36349](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36349)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[ReplicatedMovement](ue_ue.FunctionalTest.md#replicatedmovement)

#### Defined in

[ue/ue.d.ts:13148](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13148)

___

### Result

• **Result**: [`EFunctionalTestResult`](../enums/ue_ue.EFunctionalTestResult.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[Result](ue_ue.FunctionalTest.md#result)

#### Defined in

[ue/ue.d.ts:36340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36340)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[Role](ue_ue.FunctionalTest.md#role)

#### Defined in

[ue/ue.d.ts:13154](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13154)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[RootComponent](ue_ue.FunctionalTest.md#rootcomponent)

#### Defined in

[ue/ue.d.ts:13167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13167)

___

### ScreenshotCamera

• **ScreenshotCamera**: [`CameraComponent`](ue_ue.CameraComponent.md)

#### Defined in

[ue/ue.d.ts:36519](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36519)

___

### ScreenshotOptions

• **ScreenshotOptions**: [`AutomationScreenshotOptions`](ue_ue.AutomationScreenshotOptions.md)

#### Defined in

[ue/ue.d.ts:36520](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36520)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[SpawnCollisionHandlingMethod](ue_ue.FunctionalTest.md#spawncollisionhandlingmethod)

#### Defined in

[ue/ue.d.ts:13156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13156)

___

### SpriteComponent

• **SpriteComponent**: [`BillboardComponent`](ue_ue.BillboardComponent.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[SpriteComponent](ue_ue.FunctionalTest.md#spritecomponent)

#### Defined in

[ue/ue.d.ts:36332](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36332)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[SpriteScale](ue_ue.FunctionalTest.md#spritescale)

#### Defined in

[ue/ue.d.ts:13174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13174)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[Tags](ue_ue.FunctionalTest.md#tags)

#### Defined in

[ue/ue.d.ts:13188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13188)

___

### TestName

• **TestName**: [`TextRenderComponent`](ue_ue.TextRenderComponent.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[TestName](ue_ue.FunctionalTest.md#testname)

#### Defined in

[ue/ue.d.ts:36350](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36350)

___

### TimeLimit

• **TimeLimit**: `number`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[TimeLimit](ue_ue.FunctionalTest.md#timelimit)

#### Defined in

[ue/ue.d.ts:36342](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36342)

___

### TimesUpMessage

• **TimesUpMessage**: `string`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[TimesUpMessage](ue_ue.FunctionalTest.md#timesupmessage)

#### Defined in

[ue/ue.d.ts:36343](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36343)

___

### TimesUpResult

• **TimesUpResult**: [`EFunctionalTestResult`](../enums/ue_ue.EFunctionalTestResult.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[TimesUpResult](ue_ue.FunctionalTest.md#timesupresult)

#### Defined in

[ue/ue.d.ts:36344](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36344)

___

### TotalTime

• **TotalTime**: `number`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[TotalTime](ue_ue.FunctionalTest.md#totaltime)

#### Defined in

[ue/ue.d.ts:36352](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36352)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.FunctionalTest.md#updateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13145](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13145)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[__tid_Actor__](ue_ue.FunctionalTest.md#__tid_actor__)

#### Defined in

[ue/ue.d.ts:13348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13348)

___

### \_\_tid\_FunctionalTest\_\_

• **\_\_tid\_FunctionalTest\_\_**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[__tid_FunctionalTest__](ue_ue.FunctionalTest.md#__tid_functionaltest__)

#### Defined in

[ue/ue.d.ts:36392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36392)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[__tid_Object__](ue_ue.FunctionalTest.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_ScreenshotFunctionalTestBase\_\_

• **\_\_tid\_ScreenshotFunctionalTestBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:36525](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36525)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bActorEnableCollision](ue_ue.FunctionalTest.md#bactorenablecollision)

#### Defined in

[ue/ue.d.ts:13143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13143)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bActorIsBeingDestroyed](ue_ue.FunctionalTest.md#bactorisbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13144](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13144)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bActorLabelEditable](ue_ue.FunctionalTest.md#bactorlabeleditable)

#### Defined in

[ue/ue.d.ts:13183](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13183)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bActorSeamlessTraveled](ue_ue.FunctionalTest.md#bactorseamlesstraveled)

#### Defined in

[ue/ue.d.ts:13139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13139)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.FunctionalTest.md#ballowreceivetickeventondedicatedserver)

#### Defined in

[ue/ue.d.ts:13142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13142)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bAllowTickBeforeBeginPlay](ue_ue.FunctionalTest.md#ballowtickbeforebeginplay)

#### Defined in

[ue/ue.d.ts:13129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13129)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bAlwaysRelevant](ue_ue.FunctionalTest.md#balwaysrelevant)

#### Defined in

[ue/ue.d.ts:13120](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13120)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bAutoDestroyWhenFinished](ue_ue.FunctionalTest.md#bautodestroywhenfinished)

#### Defined in

[ue/ue.d.ts:13130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13130)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bBlockInput](ue_ue.FunctionalTest.md#bblockinput)

#### Defined in

[ue/ue.d.ts:13131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13131)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bCanBeDamaged](ue_ue.FunctionalTest.md#bcanbedamaged)

#### Defined in

[ue/ue.d.ts:13132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13132)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bCanBeInCluster](ue_ue.FunctionalTest.md#bcanbeincluster)

#### Defined in

[ue/ue.d.ts:13141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13141)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bCollideWhenPlacing](ue_ue.FunctionalTest.md#bcollidewhenplacing)

#### Defined in

[ue/ue.d.ts:13133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13133)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bEditable](ue_ue.FunctionalTest.md#beditable)

#### Defined in

[ue/ue.d.ts:13184](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13184)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bEnableAutoLODGeneration](ue_ue.FunctionalTest.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:13137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13137)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bExchangedRoles](ue_ue.FunctionalTest.md#bexchangedroles)

#### Defined in

[ue/ue.d.ts:13123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13123)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bFindCameraComponentWhenViewTarget](ue_ue.FunctionalTest.md#bfindcameracomponentwhenviewtarget)

#### Defined in

[ue/ue.d.ts:13134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13134)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.FunctionalTest.md#bgenerateoverlapeventsduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13135)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bHidden](ue_ue.FunctionalTest.md#bhidden)

#### Defined in

[ue/ue.d.ts:13116](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13116)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bHiddenEd](ue_ue.FunctionalTest.md#bhiddened)

#### Defined in

[ue/ue.d.ts:13178](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13178)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bHiddenEdLayer](ue_ue.FunctionalTest.md#bhiddenedlayer)

#### Defined in

[ue/ue.d.ts:13180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13180)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bHiddenEdLevel](ue_ue.FunctionalTest.md#bhiddenedlevel)

#### Defined in

[ue/ue.d.ts:13181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13181)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bHiddenEdTemporary](ue_ue.FunctionalTest.md#bhiddenedtemporary)

#### Defined in

[ue/ue.d.ts:13187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13187)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bIgnoresOriginShifting](ue_ue.FunctionalTest.md#bignoresoriginshifting)

#### Defined in

[ue/ue.d.ts:13136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13136)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bIsEditorOnlyActor](ue_ue.FunctionalTest.md#biseditoronlyactor)

#### Defined in

[ue/ue.d.ts:13138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13138)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bIsEditorPreviewActor](ue_ue.FunctionalTest.md#biseditorpreviewactor)

#### Defined in

[ue/ue.d.ts:13179](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13179)

___

### bIsEnabled

• **bIsEnabled**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bIsEnabled](ue_ue.FunctionalTest.md#bisenabled)

#### Defined in

[ue/ue.d.ts:36333](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36333)

___

### bIsRunning

• **bIsRunning**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bIsRunning](ue_ue.FunctionalTest.md#bisrunning)

#### Defined in

[ue/ue.d.ts:36351](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36351)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bListedInSceneOutliner](ue_ue.FunctionalTest.md#blistedinsceneoutliner)

#### Defined in

[ue/ue.d.ts:13185](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13185)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bLockLocation](ue_ue.FunctionalTest.md#blocklocation)

#### Defined in

[ue/ue.d.ts:13182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13182)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bNetLoadOnClient](ue_ue.FunctionalTest.md#bnetloadonclient)

#### Defined in

[ue/ue.d.ts:13124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13124)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bNetStartup](ue_ue.FunctionalTest.md#bnetstartup)

#### Defined in

[ue/ue.d.ts:13118](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13118)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bNetTemporary](ue_ue.FunctionalTest.md#bnettemporary)

#### Defined in

[ue/ue.d.ts:13117](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13117)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bNetUseOwnerRelevancy](ue_ue.FunctionalTest.md#bnetuseownerrelevancy)

#### Defined in

[ue/ue.d.ts:13125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13125)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bOnlyRelevantToOwner](ue_ue.FunctionalTest.md#bonlyrelevanttoowner)

#### Defined in

[ue/ue.d.ts:13119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13119)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bOptimizeBPComponentData](ue_ue.FunctionalTest.md#boptimizebpcomponentdata)

#### Defined in

[ue/ue.d.ts:13186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13186)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bRelevantForLevelBounds](ue_ue.FunctionalTest.md#brelevantforlevelbounds)

#### Defined in

[ue/ue.d.ts:13127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13127)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bRelevantForNetworkReplays](ue_ue.FunctionalTest.md#brelevantfornetworkreplays)

#### Defined in

[ue/ue.d.ts:13126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13126)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bReplayRewindable](ue_ue.FunctionalTest.md#breplayrewindable)

#### Defined in

[ue/ue.d.ts:13128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13128)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bReplicateMovement](ue_ue.FunctionalTest.md#breplicatemovement)

#### Defined in

[ue/ue.d.ts:13121](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13121)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bReplicates](ue_ue.FunctionalTest.md#breplicates)

#### Defined in

[ue/ue.d.ts:13140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13140)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[bTearOff](ue_ue.FunctionalTest.md#btearoff)

#### Defined in

[ue/ue.d.ts:13122](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13122)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[ActorHasTag](ue_ue.FunctionalTest.md#actorhastag)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[AddComponent](ue_ue.FunctionalTest.md#addcomponent)

#### Defined in

[ue/ue.d.ts:13208](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13208)

___

### AddError

▸ **AddError**(`Message`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Message` | `string` |

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AddError](ue_ue.FunctionalTest.md#adderror)

#### Defined in

[ue/ue.d.ts:36353](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36353)

___

### AddRerun

▸ **AddRerun**(`Reason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Reason` | `string` |

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AddRerun](ue_ue.FunctionalTest.md#addrerun)

#### Defined in

[ue/ue.d.ts:36354](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36354)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[AddTickPrerequisiteActor](ue_ue.FunctionalTest.md#addtickprerequisiteactor)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[AddTickPrerequisiteComponent](ue_ue.FunctionalTest.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13210](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13210)

___

### AddWarning

▸ **AddWarning**(`Message`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Message` | `string` |

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AddWarning](ue_ue.FunctionalTest.md#addwarning)

#### Defined in

[ue/ue.d.ts:36355](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36355)

___

### AssertEqual\_Bool

▸ **AssertEqual_Bool**(`Actual`, `Expected`, `What`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actual` | `boolean` |
| `Expected` | `boolean` |
| `What` | `string` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertEqual_Bool](ue_ue.FunctionalTest.md#assertequal_bool)

#### Defined in

[ue/ue.d.ts:36356](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36356)

___

### AssertEqual\_Float

▸ **AssertEqual_Float**(`Actual`, `Expected`, `What`, `Tolerance?`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actual` | `number` |
| `Expected` | `number` |
| `What` | `string` |
| `Tolerance?` | `number` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertEqual_Float](ue_ue.FunctionalTest.md#assertequal_float)

#### Defined in

[ue/ue.d.ts:36357](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36357)

___

### AssertEqual\_Int

▸ **AssertEqual_Int**(`Actual`, `Expected`, `What`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actual` | `number` |
| `Expected` | `number` |
| `What` | `string` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertEqual_Int](ue_ue.FunctionalTest.md#assertequal_int)

#### Defined in

[ue/ue.d.ts:36358](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36358)

___

### AssertEqual\_Name

▸ **AssertEqual_Name**(`Actual`, `Expected`, `What`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actual` | `string` |
| `Expected` | `string` |
| `What` | `string` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertEqual_Name](ue_ue.FunctionalTest.md#assertequal_name)

#### Defined in

[ue/ue.d.ts:36359](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36359)

___

### AssertEqual\_Rotator

▸ **AssertEqual_Rotator**(`Actual`, `Expected`, `What`, `Tolerance?`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actual` | [`Rotator`](ue_ue_s.Rotator.md) |
| `Expected` | [`Rotator`](ue_ue_s.Rotator.md) |
| `What` | `string` |
| `Tolerance?` | `number` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertEqual_Rotator](ue_ue.FunctionalTest.md#assertequal_rotator)

#### Defined in

[ue/ue.d.ts:36360](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36360)

___

### AssertEqual\_String

▸ **AssertEqual_String**(`Actual`, `Expected`, `What`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actual` | `string` |
| `Expected` | `string` |
| `What` | `string` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertEqual_String](ue_ue.FunctionalTest.md#assertequal_string)

#### Defined in

[ue/ue.d.ts:36361](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36361)

___

### AssertEqual\_TraceQueryResults

▸ **AssertEqual_TraceQueryResults**(`Actual`, `Expected`, `What`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actual` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TraceQueryTestResults`](ue_ue.TraceQueryTestResults.md)\> |
| `Expected` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TraceQueryTestResults`](ue_ue.TraceQueryTestResults.md)\> |
| `What` | `string` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertEqual_TraceQueryResults](ue_ue.FunctionalTest.md#assertequal_tracequeryresults)

#### Defined in

[ue/ue.d.ts:36362](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36362)

___

### AssertEqual\_Transform

▸ **AssertEqual_Transform**(`Actual`, `Expected`, `What`, `Tolerance?`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actual` | [`Transform`](ue_ue_s.Transform.md) |
| `Expected` | [`Transform`](ue_ue_s.Transform.md) |
| `What` | `string` |
| `Tolerance?` | `number` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertEqual_Transform](ue_ue.FunctionalTest.md#assertequal_transform)

#### Defined in

[ue/ue.d.ts:36363](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36363)

___

### AssertEqual\_Vector

▸ **AssertEqual_Vector**(`Actual`, `Expected`, `What`, `Tolerance?`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actual` | [`Vector`](ue_ue_s.Vector.md) |
| `Expected` | [`Vector`](ue_ue_s.Vector.md) |
| `What` | `string` |
| `Tolerance?` | `number` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertEqual_Vector](ue_ue.FunctionalTest.md#assertequal_vector)

#### Defined in

[ue/ue.d.ts:36364](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36364)

___

### AssertFalse

▸ **AssertFalse**(`Condition`, `Message`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Condition` | `boolean` |
| `Message` | `string` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertFalse](ue_ue.FunctionalTest.md#assertfalse)

#### Defined in

[ue/ue.d.ts:36365](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36365)

___

### AssertIsValid

▸ **AssertIsValid**(`Object`, `Message`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Object` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Message` | `string` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertIsValid](ue_ue.FunctionalTest.md#assertisvalid)

#### Defined in

[ue/ue.d.ts:36366](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36366)

___

### AssertNotEqual\_Rotator

▸ **AssertNotEqual_Rotator**(`Actual`, `NotExpected`, `What`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actual` | [`Rotator`](ue_ue_s.Rotator.md) |
| `NotExpected` | [`Rotator`](ue_ue_s.Rotator.md) |
| `What` | `string` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertNotEqual_Rotator](ue_ue.FunctionalTest.md#assertnotequal_rotator)

#### Defined in

[ue/ue.d.ts:36367](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36367)

___

### AssertNotEqual\_String

▸ **AssertNotEqual_String**(`Actual`, `NotExpected`, `What`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actual` | `string` |
| `NotExpected` | `string` |
| `What` | `string` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertNotEqual_String](ue_ue.FunctionalTest.md#assertnotequal_string)

#### Defined in

[ue/ue.d.ts:36368](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36368)

___

### AssertNotEqual\_Transform

▸ **AssertNotEqual_Transform**(`Actual`, `NotExpected`, `What`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actual` | [`Transform`](ue_ue_s.Transform.md) |
| `NotExpected` | [`Transform`](ue_ue_s.Transform.md) |
| `What` | `string` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertNotEqual_Transform](ue_ue.FunctionalTest.md#assertnotequal_transform)

#### Defined in

[ue/ue.d.ts:36369](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36369)

___

### AssertNotEqual\_Vector

▸ **AssertNotEqual_Vector**(`Actual`, `NotExpected`, `What`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actual` | [`Vector`](ue_ue_s.Vector.md) |
| `NotExpected` | [`Vector`](ue_ue_s.Vector.md) |
| `What` | `string` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertNotEqual_Vector](ue_ue.FunctionalTest.md#assertnotequal_vector)

#### Defined in

[ue/ue.d.ts:36370](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36370)

___

### AssertTrue

▸ **AssertTrue**(`Condition`, `Message`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Condition` | `boolean` |
| `Message` | `string` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertTrue](ue_ue.FunctionalTest.md#asserttrue)

#### Defined in

[ue/ue.d.ts:36371](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36371)

___

### AssertValue\_DateTime

▸ **AssertValue_DateTime**(`Actual`, `ShouldBe`, `Expected`, `What`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actual` | [`DateTime`](ue_ue.DateTime.md) |
| `ShouldBe` | [`EComparisonMethod`](../enums/ue_ue.EComparisonMethod.md) |
| `Expected` | [`DateTime`](ue_ue.DateTime.md) |
| `What` | `string` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertValue_DateTime](ue_ue.FunctionalTest.md#assertvalue_datetime)

#### Defined in

[ue/ue.d.ts:36372](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36372)

___

### AssertValue\_Float

▸ **AssertValue_Float**(`Actual`, `ShouldBe`, `Expected`, `What`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actual` | `number` |
| `ShouldBe` | [`EComparisonMethod`](../enums/ue_ue.EComparisonMethod.md) |
| `Expected` | `number` |
| `What` | `string` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertValue_Float](ue_ue.FunctionalTest.md#assertvalue_float)

#### Defined in

[ue/ue.d.ts:36373](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36373)

___

### AssertValue\_Int

▸ **AssertValue_Int**(`Actual`, `ShouldBe`, `Expected`, `What`, `ContextObject?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actual` | `number` |
| `ShouldBe` | [`EComparisonMethod`](../enums/ue_ue.EComparisonMethod.md) |
| `Expected` | `number` |
| `What` | `string` |
| `ContextObject?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[AssertValue_Int](ue_ue.FunctionalTest.md#assertvalue_int)

#### Defined in

[ue/ue.d.ts:36374](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36374)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[CreateDefaultSubobject](ue_ue.FunctionalTest.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### DebugGatherRelevantActors

▸ **DebugGatherRelevantActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[DebugGatherRelevantActors](ue_ue.FunctionalTest.md#debuggatherrelevantactors)

#### Defined in

[ue/ue.d.ts:36375](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36375)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[DetachRootComponentFromParent](ue_ue.FunctionalTest.md#detachrootcomponentfromparent)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[DisableInput](ue_ue.FunctionalTest.md#disableinput)

#### Defined in

[ue/ue.d.ts:13212](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13212)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[EnableInput](ue_ue.FunctionalTest.md#enableinput)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[ExecuteUbergraph](ue_ue.FunctionalTest.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### FinishTest

▸ **FinishTest**(`TestResult`, `Message`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TestResult` | [`EFunctionalTestResult`](../enums/ue_ue.EFunctionalTestResult.md) |
| `Message` | `string` |

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[FinishTest](ue_ue.FunctionalTest.md#finishtest)

#### Defined in

[ue/ue.d.ts:36376](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36376)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[FlushNetDormancy](ue_ue.FunctionalTest.md#flushnetdormancy)

#### Defined in

[ue/ue.d.ts:13214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13214)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[ForceNetUpdate](ue_ue.FunctionalTest.md#forcenetupdate)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetActorBounds](ue_ue.FunctionalTest.md#getactorbounds)

#### Defined in

[ue/ue.d.ts:13216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13216)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetActorEnableCollision](ue_ue.FunctionalTest.md#getactorenablecollision)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetActorEyesViewPoint](ue_ue.FunctionalTest.md#getactoreyesviewpoint)

#### Defined in

[ue/ue.d.ts:13218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13218)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetActorForwardVector](ue_ue.FunctionalTest.md#getactorforwardvector)

#### Defined in

[ue/ue.d.ts:13219](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13219)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetActorLabel](ue_ue.FunctionalTest.md#getactorlabel)

#### Defined in

[ue/ue.d.ts:13220](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13220)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetActorRelativeScale3D](ue_ue.FunctionalTest.md#getactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13221](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13221)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetActorRightVector](ue_ue.FunctionalTest.md#getactorrightvector)

#### Defined in

[ue/ue.d.ts:13222](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13222)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetActorScale3D](ue_ue.FunctionalTest.md#getactorscale3d)

#### Defined in

[ue/ue.d.ts:13223](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13223)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetActorTickInterval](ue_ue.FunctionalTest.md#getactortickinterval)

#### Defined in

[ue/ue.d.ts:13224](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13224)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetActorTimeDilation](ue_ue.FunctionalTest.md#getactortimedilation)

#### Defined in

[ue/ue.d.ts:13225](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13225)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetActorUpVector](ue_ue.FunctionalTest.md#getactorupvector)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetAllChildActors](ue_ue.FunctionalTest.md#getallchildactors)

#### Defined in

[ue/ue.d.ts:13227](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13227)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetAttachParentActor](ue_ue.FunctionalTest.md#getattachparentactor)

#### Defined in

[ue/ue.d.ts:13229](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13229)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetAttachParentSocketName](ue_ue.FunctionalTest.md#getattachparentsocketname)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetAttachedActors](ue_ue.FunctionalTest.md#getattachedactors)

#### Defined in

[ue/ue.d.ts:13228](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13228)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetClass](ue_ue.FunctionalTest.md#getclass)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetComponentByClass](ue_ue.FunctionalTest.md#getcomponentbyclass)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetComponentsByInterface](ue_ue.FunctionalTest.md#getcomponentsbyinterface)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetComponentsByTag](ue_ue.FunctionalTest.md#getcomponentsbytag)

#### Defined in

[ue/ue.d.ts:13233](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13233)

___

### GetCurrentRerunReason

▸ **GetCurrentRerunReason**(): `string`

#### Returns

`string`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetCurrentRerunReason](ue_ue.FunctionalTest.md#getcurrentrerunreason)

#### Defined in

[ue/ue.d.ts:36377](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36377)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetDistanceTo](ue_ue.FunctionalTest.md#getdistanceto)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetDotProductTo](ue_ue.FunctionalTest.md#getdotproductto)

#### Defined in

[ue/ue.d.ts:13235](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13235)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetFolderPath](ue_ue.FunctionalTest.md#getfolderpath)

#### Defined in

[ue/ue.d.ts:13236](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13236)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetGameTimeSinceCreation](ue_ue.FunctionalTest.md#getgametimesincecreation)

#### Defined in

[ue/ue.d.ts:13237](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13237)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetHorizontalDistanceTo](ue_ue.FunctionalTest.md#gethorizontaldistanceto)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetHorizontalDotProductTo](ue_ue.FunctionalTest.md#gethorizontaldotproductto)

#### Defined in

[ue/ue.d.ts:13239](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13239)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetInputAxisKeyValue](ue_ue.FunctionalTest.md#getinputaxiskeyvalue)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetInputAxisValue](ue_ue.FunctionalTest.md#getinputaxisvalue)

#### Defined in

[ue/ue.d.ts:13241](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13241)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetInputVectorAxisValue](ue_ue.FunctionalTest.md#getinputvectoraxisvalue)

#### Defined in

[ue/ue.d.ts:13242](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13242)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetInstigator](ue_ue.FunctionalTest.md#getinstigator)

#### Defined in

[ue/ue.d.ts:13243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13243)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetInstigatorController](ue_ue.FunctionalTest.md#getinstigatorcontroller)

#### Defined in

[ue/ue.d.ts:13244](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13244)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetLifeSpan](ue_ue.FunctionalTest.md#getlifespan)

#### Defined in

[ue/ue.d.ts:13245](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13245)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetLocalRole](ue_ue.FunctionalTest.md#getlocalrole)

#### Defined in

[ue/ue.d.ts:13246](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13246)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetName](ue_ue.FunctionalTest.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetOuter](ue_ue.FunctionalTest.md#getouter)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetOverlappingActors](ue_ue.FunctionalTest.md#getoverlappingactors)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetOverlappingComponents](ue_ue.FunctionalTest.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:13248](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13248)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetOwner](ue_ue.FunctionalTest.md#getowner)

#### Defined in

[ue/ue.d.ts:13249](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13249)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetParentActor](ue_ue.FunctionalTest.md#getparentactor)

#### Defined in

[ue/ue.d.ts:13250](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13250)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetParentComponent](ue_ue.FunctionalTest.md#getparentcomponent)

#### Defined in

[ue/ue.d.ts:13251](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13251)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetRemoteRole](ue_ue.FunctionalTest.md#getremoterole)

#### Defined in

[ue/ue.d.ts:13252](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13252)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetSquaredDistanceTo](ue_ue.FunctionalTest.md#getsquareddistanceto)

#### Defined in

[ue/ue.d.ts:13253](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13253)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetTickableWhenPaused](ue_ue.FunctionalTest.md#gettickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13254](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13254)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetTransform](ue_ue.FunctionalTest.md#gettransform)

#### Defined in

[ue/ue.d.ts:13255](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13255)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetVelocity](ue_ue.FunctionalTest.md#getvelocity)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[GetVerticalDistanceTo](ue_ue.FunctionalTest.md#getverticaldistanceto)

#### Defined in

[ue/ue.d.ts:13257](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13257)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[GetWorld](ue_ue.FunctionalTest.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[HasAuthority](ue_ue.FunctionalTest.md#hasauthority)

#### Defined in

[ue/ue.d.ts:13258](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13258)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[IsActorBeingDestroyed](ue_ue.FunctionalTest.md#isactorbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13259](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13259)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[IsActorTickEnabled](ue_ue.FunctionalTest.md#isactortickenabled)

#### Defined in

[ue/ue.d.ts:13260](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13260)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[IsChildActor](ue_ue.FunctionalTest.md#ischildactor)

#### Defined in

[ue/ue.d.ts:13261](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13261)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[IsEditable](ue_ue.FunctionalTest.md#iseditable)

#### Defined in

[ue/ue.d.ts:13262](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13262)

___

### IsEnabled

▸ **IsEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[IsEnabled](ue_ue.FunctionalTest.md#isenabled)

#### Defined in

[ue/ue.d.ts:36378](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36378)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[IsHiddenEd](ue_ue.FunctionalTest.md#ishiddened)

#### Defined in

[ue/ue.d.ts:13263](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13263)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[IsHiddenEdAtStartup](ue_ue.FunctionalTest.md#ishiddenedatstartup)

#### Defined in

[ue/ue.d.ts:13264](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13264)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[IsOverlappingActor](ue_ue.FunctionalTest.md#isoverlappingactor)

#### Defined in

[ue/ue.d.ts:13265](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13265)

___

### IsReady

▸ **IsReady**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[IsReady](ue_ue.FunctionalTest.md#isready)

#### Defined in

[ue/ue.d.ts:36379](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36379)

___

### IsRunning

▸ **IsRunning**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[IsRunning](ue_ue.FunctionalTest.md#isrunning)

#### Defined in

[ue/ue.d.ts:36380](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36380)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[IsSelectable](ue_ue.FunctionalTest.md#isselectable)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[IsTemporarilyHiddenInEditor](ue_ue.FunctionalTest.md#istemporarilyhiddenineditor)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_AddActorLocalOffset](ue_ue.FunctionalTest.md#k2_addactorlocaloffset)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_AddActorLocalRotation](ue_ue.FunctionalTest.md#k2_addactorlocalrotation)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_AddActorLocalTransform](ue_ue.FunctionalTest.md#k2_addactorlocaltransform)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_AddActorWorldOffset](ue_ue.FunctionalTest.md#k2_addactorworldoffset)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_AddActorWorldRotation](ue_ue.FunctionalTest.md#k2_addactorworldrotation)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_AddActorWorldTransform](ue_ue.FunctionalTest.md#k2_addactorworldtransform)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_AttachRootComponentTo](ue_ue.FunctionalTest.md#k2_attachrootcomponentto)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_AttachRootComponentToActor](ue_ue.FunctionalTest.md#k2_attachrootcomponenttoactor)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_AttachToActor](ue_ue.FunctionalTest.md#k2_attachtoactor)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_AttachToComponent](ue_ue.FunctionalTest.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:13277](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13277)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_DestroyActor](ue_ue.FunctionalTest.md#k2_destroyactor)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_DestroyComponent](ue_ue.FunctionalTest.md#k2_destroycomponent)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_DetachFromActor](ue_ue.FunctionalTest.md#k2_detachfromactor)

#### Defined in

[ue/ue.d.ts:13280](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13280)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_GetActorLocation](ue_ue.FunctionalTest.md#k2_getactorlocation)

#### Defined in

[ue/ue.d.ts:13281](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13281)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_GetActorRotation](ue_ue.FunctionalTest.md#k2_getactorrotation)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_GetComponentsByClass](ue_ue.FunctionalTest.md#k2_getcomponentsbyclass)

#### Defined in

[ue/ue.d.ts:13283](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13283)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_GetRootComponent](ue_ue.FunctionalTest.md#k2_getrootcomponent)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_OnBecomeViewTarget](ue_ue.FunctionalTest.md#k2_onbecomeviewtarget)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_OnEndViewTarget](ue_ue.FunctionalTest.md#k2_onendviewtarget)

#### Defined in

[ue/ue.d.ts:13286](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13286)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_OnReset](ue_ue.FunctionalTest.md#k2_onreset)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_SetActorLocation](ue_ue.FunctionalTest.md#k2_setactorlocation)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_SetActorLocationAndRotation](ue_ue.FunctionalTest.md#k2_setactorlocationandrotation)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_SetActorRelativeLocation](ue_ue.FunctionalTest.md#k2_setactorrelativelocation)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_SetActorRelativeRotation](ue_ue.FunctionalTest.md#k2_setactorrelativerotation)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_SetActorRelativeTransform](ue_ue.FunctionalTest.md#k2_setactorrelativetransform)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_SetActorRotation](ue_ue.FunctionalTest.md#k2_setactorrotation)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_SetActorTransform](ue_ue.FunctionalTest.md#k2_setactortransform)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[K2_TeleportTo](ue_ue.FunctionalTest.md#k2_teleportto)

#### Defined in

[ue/ue.d.ts:13295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13295)

___

### LogMessage

▸ **LogMessage**(`Message`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Message` | `string` |

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[LogMessage](ue_ue.FunctionalTest.md#logmessage)

#### Defined in

[ue/ue.d.ts:36381](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36381)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[MakeMIDForMaterial](ue_ue.FunctionalTest.md#makemidformaterial)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[MakeNoise](ue_ue.FunctionalTest.md#makenoise)

#### Defined in

[ue/ue.d.ts:13297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13297)

___

### OnAdditionalTestFinishedMessageRequest

▸ **OnAdditionalTestFinishedMessageRequest**(`TestResult`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TestResult` | [`EFunctionalTestResult`](../enums/ue_ue.EFunctionalTestResult.md) |

#### Returns

`string`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnAdditionalTestFinishedMessageRequest](ue_ue.FunctionalTest.md#onadditionaltestfinishedmessagerequest)

#### Defined in

[ue/ue.d.ts:36382](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36382)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnRep_AttachmentReplication](ue_ue.FunctionalTest.md#onrep_attachmentreplication)

#### Defined in

[ue/ue.d.ts:13298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13298)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnRep_Instigator](ue_ue.FunctionalTest.md#onrep_instigator)

#### Defined in

[ue/ue.d.ts:13299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13299)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnRep_Owner](ue_ue.FunctionalTest.md#onrep_owner)

#### Defined in

[ue/ue.d.ts:13300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13300)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnRep_ReplicateMovement](ue_ue.FunctionalTest.md#onrep_replicatemovement)

#### Defined in

[ue/ue.d.ts:13302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13302)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnRep_ReplicatedMovement](ue_ue.FunctionalTest.md#onrep_replicatedmovement)

#### Defined in

[ue/ue.d.ts:13301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13301)

___

### OnWantsReRunCheck

▸ **OnWantsReRunCheck**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[OnWantsReRunCheck](ue_ue.FunctionalTest.md#onwantsreruncheck)

#### Defined in

[ue/ue.d.ts:36383](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36383)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[PrestreamTextures](ue_ue.FunctionalTest.md#prestreamtextures)

#### Defined in

[ue/ue.d.ts:13303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13303)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveActorBeginCursorOver](ue_ue.FunctionalTest.md#receiveactorbegincursorover)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveActorBeginOverlap](ue_ue.FunctionalTest.md#receiveactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13305)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveActorEndCursorOver](ue_ue.FunctionalTest.md#receiveactorendcursorover)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveActorEndOverlap](ue_ue.FunctionalTest.md#receiveactorendoverlap)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveActorOnClicked](ue_ue.FunctionalTest.md#receiveactoronclicked)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveActorOnInputTouchBegin](ue_ue.FunctionalTest.md#receiveactoroninputtouchbegin)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveActorOnInputTouchEnd](ue_ue.FunctionalTest.md#receiveactoroninputtouchend)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveActorOnInputTouchEnter](ue_ue.FunctionalTest.md#receiveactoroninputtouchenter)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveActorOnInputTouchLeave](ue_ue.FunctionalTest.md#receiveactoroninputtouchleave)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveActorOnReleased](ue_ue.FunctionalTest.md#receiveactoronreleased)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveAnyDamage](ue_ue.FunctionalTest.md#receiveanydamage)

#### Defined in

[ue/ue.d.ts:13314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13314)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveBeginPlay](ue_ue.FunctionalTest.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:13315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13315)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveDestroyed](ue_ue.FunctionalTest.md#receivedestroyed)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveEndPlay](ue_ue.FunctionalTest.md#receiveendplay)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveHit](ue_ue.FunctionalTest.md#receivehit)

#### Defined in

[ue/ue.d.ts:13318](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13318)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceivePointDamage](ue_ue.FunctionalTest.md#receivepointdamage)

#### Defined in

[ue/ue.d.ts:13319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13319)

___

### ReceivePrepareTest

▸ **ReceivePrepareTest**(): `void`

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceivePrepareTest](ue_ue.FunctionalTest.md#receivepreparetest)

#### Defined in

[ue/ue.d.ts:36384](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36384)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveRadialDamage](ue_ue.FunctionalTest.md#receiveradialdamage)

#### Defined in

[ue/ue.d.ts:13320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13320)

___

### ReceiveStartTest

▸ **ReceiveStartTest**(): `void`

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveStartTest](ue_ue.FunctionalTest.md#receivestarttest)

#### Defined in

[ue/ue.d.ts:36385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36385)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[ReceiveTick](ue_ue.FunctionalTest.md#receivetick)

#### Defined in

[ue/ue.d.ts:13321](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13321)

___

### RegisterAutoDestroyActor

▸ **RegisterAutoDestroyActor**(`ActorToAutoDestroy`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActorToAutoDestroy` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[RegisterAutoDestroyActor](ue_ue.FunctionalTest.md#registerautodestroyactor)

#### Defined in

[ue/ue.d.ts:36386](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36386)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[RemoveTickPrerequisiteActor](ue_ue.FunctionalTest.md#removetickprerequisiteactor)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[RemoveTickPrerequisiteComponent](ue_ue.FunctionalTest.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13323](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13323)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[SetActorEnableCollision](ue_ue.FunctionalTest.md#setactorenablecollision)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[SetActorHiddenInGame](ue_ue.FunctionalTest.md#setactorhiddeningame)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[SetActorLabel](ue_ue.FunctionalTest.md#setactorlabel)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[SetActorRelativeScale3D](ue_ue.FunctionalTest.md#setactorrelativescale3d)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[SetActorScale3D](ue_ue.FunctionalTest.md#setactorscale3d)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[SetActorTickEnabled](ue_ue.FunctionalTest.md#setactortickenabled)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[SetActorTickInterval](ue_ue.FunctionalTest.md#setactortickinterval)

#### Defined in

[ue/ue.d.ts:13330](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13330)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[SetFolderPath](ue_ue.FunctionalTest.md#setfolderpath)

#### Defined in

[ue/ue.d.ts:13331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13331)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[SetIsTemporarilyHiddenInEditor](ue_ue.FunctionalTest.md#setistemporarilyhiddenineditor)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[SetLifeSpan](ue_ue.FunctionalTest.md#setlifespan)

#### Defined in

[ue/ue.d.ts:13333](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13333)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[SetNetDormancy](ue_ue.FunctionalTest.md#setnetdormancy)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[SetOwner](ue_ue.FunctionalTest.md#setowner)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[SetReplicateMovement](ue_ue.FunctionalTest.md#setreplicatemovement)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[SetReplicates](ue_ue.FunctionalTest.md#setreplicates)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[SetTickGroup](ue_ue.FunctionalTest.md#settickgroup)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[SetTickableWhenPaused](ue_ue.FunctionalTest.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13338](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13338)

___

### SetTimeLimit

▸ **SetTimeLimit**(`NewTimeLimit`, `ResultWhenTimeRunsOut`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTimeLimit` | `number` |
| `ResultWhenTimeRunsOut` | [`EFunctionalTestResult`](../enums/ue_ue.EFunctionalTestResult.md) |

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[SetTimeLimit](ue_ue.FunctionalTest.md#settimelimit)

#### Defined in

[ue/ue.d.ts:36387](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36387)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[SnapRootComponentTo](ue_ue.FunctionalTest.md#snaprootcomponentto)

#### Defined in

[ue/ue.d.ts:13340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13340)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[TearOff](ue_ue.FunctionalTest.md#tearoff)

#### Defined in

[ue/ue.d.ts:13341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13341)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[FunctionalTest](ue_ue.FunctionalTest.md).[UserConstructionScript](ue_ue.FunctionalTest.md#userconstructionscript)

#### Defined in

[ue/ue.d.ts:13342](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13342)

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

[FunctionalTest](ue_ue.FunctionalTest.md).[WasRecentlyRendered](ue_ue.FunctionalTest.md#wasrecentlyrendered)

#### Defined in

[ue/ue.d.ts:13343](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13343)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ScreenshotFunctionalTestBase`](ue_ue.ScreenshotFunctionalTestBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ScreenshotFunctionalTestBase`](ue_ue.ScreenshotFunctionalTestBase.md)

#### Overrides

[FunctionalTest](ue_ue.FunctionalTest.md).[Find](ue_ue.FunctionalTest.md#find)

#### Defined in

[ue/ue.d.ts:36522](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36522)

___

### Load

▸ `Static` **Load**(`InName`): [`ScreenshotFunctionalTestBase`](ue_ue.ScreenshotFunctionalTestBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ScreenshotFunctionalTestBase`](ue_ue.ScreenshotFunctionalTestBase.md)

#### Overrides

[FunctionalTest](ue_ue.FunctionalTest.md).[Load](ue_ue.FunctionalTest.md#load)

#### Defined in

[ue/ue.d.ts:36523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36523)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FunctionalTest](ue_ue.FunctionalTest.md).[StaticClass](ue_ue.FunctionalTest.md#staticclass)

#### Defined in

[ue/ue.d.ts:36521](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36521)
