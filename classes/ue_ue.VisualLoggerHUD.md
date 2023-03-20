[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VisualLoggerHUD

# Class: VisualLoggerHUD

[ue/ue](../modules/ue_ue.md).VisualLoggerHUD

## Hierarchy

- [`DebugCameraHUD`](ue_ue.DebugCameraHUD.md)

  ↳ **`VisualLoggerHUD`**

## Table of contents

### Constructors

- [constructor](ue_ue.VisualLoggerHUD.md#constructor)

### Properties

- [ActorLabel](ue_ue.VisualLoggerHUD.md#actorlabel)
- [AttachmentReplication](ue_ue.VisualLoggerHUD.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.VisualLoggerHUD.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.VisualLoggerHUD.md#blueprintcreatedcomponents)
- [Canvas](ue_ue.VisualLoggerHUD.md#canvas)
- [Children](ue_ue.VisualLoggerHUD.md#children)
- [ControllingMatineeActors](ue_ue.VisualLoggerHUD.md#controllingmatineeactors)
- [CurrentTargetIndex](ue_ue.VisualLoggerHUD.md#currenttargetindex)
- [CustomTimeDilation](ue_ue.VisualLoggerHUD.md#customtimedilation)
- [DebugCanvas](ue_ue.VisualLoggerHUD.md#debugcanvas)
- [DebugDisplay](ue_ue.VisualLoggerHUD.md#debugdisplay)
- [DebugTextList](ue_ue.VisualLoggerHUD.md#debugtextlist)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.VisualLoggerHUD.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.VisualLoggerHUD.md#folderpath)
- [GroupActor](ue_ue.VisualLoggerHUD.md#groupactor)
- [HiddenEditorViews](ue_ue.VisualLoggerHUD.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.VisualLoggerHUD.md#initiallifespan)
- [InputComponent](ue_ue.VisualLoggerHUD.md#inputcomponent)
- [InputPriority](ue_ue.VisualLoggerHUD.md#inputpriority)
- [InstanceComponents](ue_ue.VisualLoggerHUD.md#instancecomponents)
- [Instigator](ue_ue.VisualLoggerHUD.md#instigator)
- [Layers](ue_ue.VisualLoggerHUD.md#layers)
- [MinNetUpdateFrequency](ue_ue.VisualLoggerHUD.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.VisualLoggerHUD.md#netculldistancesquared)
- [NetDormancy](ue_ue.VisualLoggerHUD.md#netdormancy)
- [NetDriverName](ue_ue.VisualLoggerHUD.md#netdrivername)
- [NetPriority](ue_ue.VisualLoggerHUD.md#netpriority)
- [NetTag](ue_ue.VisualLoggerHUD.md#nettag)
- [NetUpdateFrequency](ue_ue.VisualLoggerHUD.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.VisualLoggerHUD.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.VisualLoggerHUD.md#onactorendoverlap)
- [OnActorHit](ue_ue.VisualLoggerHUD.md#onactorhit)
- [OnBeginCursorOver](ue_ue.VisualLoggerHUD.md#onbegincursorover)
- [OnClicked](ue_ue.VisualLoggerHUD.md#onclicked)
- [OnDestroyed](ue_ue.VisualLoggerHUD.md#ondestroyed)
- [OnEndCursorOver](ue_ue.VisualLoggerHUD.md#onendcursorover)
- [OnEndPlay](ue_ue.VisualLoggerHUD.md#onendplay)
- [OnInputTouchBegin](ue_ue.VisualLoggerHUD.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.VisualLoggerHUD.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.VisualLoggerHUD.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.VisualLoggerHUD.md#oninputtouchleave)
- [OnReleased](ue_ue.VisualLoggerHUD.md#onreleased)
- [OnTakeAnyDamage](ue_ue.VisualLoggerHUD.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.VisualLoggerHUD.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.VisualLoggerHUD.md#ontakeradialdamage)
- [Owner](ue_ue.VisualLoggerHUD.md#owner)
- [ParentComponent](ue_ue.VisualLoggerHUD.md#parentcomponent)
- [ParentComponentActor](ue_ue.VisualLoggerHUD.md#parentcomponentactor)
- [PivotOffset](ue_ue.VisualLoggerHUD.md#pivotoffset)
- [PlayerOwner](ue_ue.VisualLoggerHUD.md#playerowner)
- [PostRenderedActors](ue_ue.VisualLoggerHUD.md#postrenderedactors)
- [PrimaryActorTick](ue_ue.VisualLoggerHUD.md#primaryactortick)
- [RemoteRole](ue_ue.VisualLoggerHUD.md#remoterole)
- [ReplicatedMovement](ue_ue.VisualLoggerHUD.md#replicatedmovement)
- [Role](ue_ue.VisualLoggerHUD.md#role)
- [RootComponent](ue_ue.VisualLoggerHUD.md#rootcomponent)
- [ShowDebugTargetActor](ue_ue.VisualLoggerHUD.md#showdebugtargetactor)
- [ShowDebugTargetDesiredClass](ue_ue.VisualLoggerHUD.md#showdebugtargetdesiredclass)
- [SpawnCollisionHandlingMethod](ue_ue.VisualLoggerHUD.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.VisualLoggerHUD.md#spritescale)
- [Tags](ue_ue.VisualLoggerHUD.md#tags)
- [ToggledDebugCategories](ue_ue.VisualLoggerHUD.md#toggleddebugcategories)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.VisualLoggerHUD.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.VisualLoggerHUD.md#__tid_actor__)
- [\_\_tid\_DebugCameraHUD\_\_](ue_ue.VisualLoggerHUD.md#__tid_debugcamerahud__)
- [\_\_tid\_HUD\_\_](ue_ue.VisualLoggerHUD.md#__tid_hud__)
- [\_\_tid\_Object\_\_](ue_ue.VisualLoggerHUD.md#__tid_object__)
- [\_\_tid\_VisualLoggerHUD\_\_](ue_ue.VisualLoggerHUD.md#__tid_visualloggerhud__)
- [bActorEnableCollision](ue_ue.VisualLoggerHUD.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.VisualLoggerHUD.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.VisualLoggerHUD.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.VisualLoggerHUD.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.VisualLoggerHUD.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.VisualLoggerHUD.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.VisualLoggerHUD.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.VisualLoggerHUD.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.VisualLoggerHUD.md#bblockinput)
- [bCanBeDamaged](ue_ue.VisualLoggerHUD.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.VisualLoggerHUD.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.VisualLoggerHUD.md#bcollidewhenplacing)
- [bEditable](ue_ue.VisualLoggerHUD.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.VisualLoggerHUD.md#benableautolodgeneration)
- [bEnableDebugTextShadow](ue_ue.VisualLoggerHUD.md#benabledebugtextshadow)
- [bExchangedRoles](ue_ue.VisualLoggerHUD.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.VisualLoggerHUD.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.VisualLoggerHUD.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.VisualLoggerHUD.md#bhidden)
- [bHiddenEd](ue_ue.VisualLoggerHUD.md#bhiddened)
- [bHiddenEdLayer](ue_ue.VisualLoggerHUD.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.VisualLoggerHUD.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.VisualLoggerHUD.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.VisualLoggerHUD.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.VisualLoggerHUD.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.VisualLoggerHUD.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.VisualLoggerHUD.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.VisualLoggerHUD.md#blocklocation)
- [bLostFocusPaused](ue_ue.VisualLoggerHUD.md#blostfocuspaused)
- [bNetLoadOnClient](ue_ue.VisualLoggerHUD.md#bnetloadonclient)
- [bNetStartup](ue_ue.VisualLoggerHUD.md#bnetstartup)
- [bNetTemporary](ue_ue.VisualLoggerHUD.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.VisualLoggerHUD.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.VisualLoggerHUD.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.VisualLoggerHUD.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.VisualLoggerHUD.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.VisualLoggerHUD.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.VisualLoggerHUD.md#breplayrewindable)
- [bReplicateMovement](ue_ue.VisualLoggerHUD.md#breplicatemovement)
- [bReplicates](ue_ue.VisualLoggerHUD.md#breplicates)
- [bShowDebugInfo](ue_ue.VisualLoggerHUD.md#bshowdebuginfo)
- [bShowHUD](ue_ue.VisualLoggerHUD.md#bshowhud)
- [bShowHitBoxDebugInfo](ue_ue.VisualLoggerHUD.md#bshowhitboxdebuginfo)
- [bShowOverlays](ue_ue.VisualLoggerHUD.md#bshowoverlays)
- [bTearOff](ue_ue.VisualLoggerHUD.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.VisualLoggerHUD.md#actorhastag)
- [AddComponent](ue_ue.VisualLoggerHUD.md#addcomponent)
- [AddDebugText](ue_ue.VisualLoggerHUD.md#adddebugtext)
- [AddHitBox](ue_ue.VisualLoggerHUD.md#addhitbox)
- [AddTickPrerequisiteActor](ue_ue.VisualLoggerHUD.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.VisualLoggerHUD.md#addtickprerequisitecomponent)
- [CreateDefaultSubobject](ue_ue.VisualLoggerHUD.md#createdefaultsubobject)
- [Deproject](ue_ue.VisualLoggerHUD.md#deproject)
- [DetachRootComponentFromParent](ue_ue.VisualLoggerHUD.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.VisualLoggerHUD.md#disableinput)
- [DrawLine](ue_ue.VisualLoggerHUD.md#drawline)
- [DrawMaterial](ue_ue.VisualLoggerHUD.md#drawmaterial)
- [DrawMaterialSimple](ue_ue.VisualLoggerHUD.md#drawmaterialsimple)
- [DrawMaterialTriangle](ue_ue.VisualLoggerHUD.md#drawmaterialtriangle)
- [DrawRect](ue_ue.VisualLoggerHUD.md#drawrect)
- [DrawText](ue_ue.VisualLoggerHUD.md#drawtext)
- [DrawTexture](ue_ue.VisualLoggerHUD.md#drawtexture)
- [DrawTextureSimple](ue_ue.VisualLoggerHUD.md#drawtexturesimple)
- [EnableInput](ue_ue.VisualLoggerHUD.md#enableinput)
- [ExecuteUbergraph](ue_ue.VisualLoggerHUD.md#executeubergraph)
- [FlushNetDormancy](ue_ue.VisualLoggerHUD.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.VisualLoggerHUD.md#forcenetupdate)
- [GetActorBounds](ue_ue.VisualLoggerHUD.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.VisualLoggerHUD.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.VisualLoggerHUD.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.VisualLoggerHUD.md#getactorforwardvector)
- [GetActorLabel](ue_ue.VisualLoggerHUD.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.VisualLoggerHUD.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.VisualLoggerHUD.md#getactorrightvector)
- [GetActorScale3D](ue_ue.VisualLoggerHUD.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.VisualLoggerHUD.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.VisualLoggerHUD.md#getactortimedilation)
- [GetActorUpVector](ue_ue.VisualLoggerHUD.md#getactorupvector)
- [GetActorsInSelectionRectangle](ue_ue.VisualLoggerHUD.md#getactorsinselectionrectangle)
- [GetAllChildActors](ue_ue.VisualLoggerHUD.md#getallchildactors)
- [GetAttachParentActor](ue_ue.VisualLoggerHUD.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.VisualLoggerHUD.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.VisualLoggerHUD.md#getattachedactors)
- [GetClass](ue_ue.VisualLoggerHUD.md#getclass)
- [GetComponentByClass](ue_ue.VisualLoggerHUD.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.VisualLoggerHUD.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.VisualLoggerHUD.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.VisualLoggerHUD.md#getdistanceto)
- [GetDotProductTo](ue_ue.VisualLoggerHUD.md#getdotproductto)
- [GetFolderPath](ue_ue.VisualLoggerHUD.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.VisualLoggerHUD.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.VisualLoggerHUD.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.VisualLoggerHUD.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.VisualLoggerHUD.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.VisualLoggerHUD.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.VisualLoggerHUD.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.VisualLoggerHUD.md#getinstigator)
- [GetInstigatorController](ue_ue.VisualLoggerHUD.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.VisualLoggerHUD.md#getlifespan)
- [GetLocalRole](ue_ue.VisualLoggerHUD.md#getlocalrole)
- [GetName](ue_ue.VisualLoggerHUD.md#getname)
- [GetOuter](ue_ue.VisualLoggerHUD.md#getouter)
- [GetOverlappingActors](ue_ue.VisualLoggerHUD.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.VisualLoggerHUD.md#getoverlappingcomponents)
- [GetOwner](ue_ue.VisualLoggerHUD.md#getowner)
- [GetOwningPawn](ue_ue.VisualLoggerHUD.md#getowningpawn)
- [GetOwningPlayerController](ue_ue.VisualLoggerHUD.md#getowningplayercontroller)
- [GetParentActor](ue_ue.VisualLoggerHUD.md#getparentactor)
- [GetParentComponent](ue_ue.VisualLoggerHUD.md#getparentcomponent)
- [GetRemoteRole](ue_ue.VisualLoggerHUD.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.VisualLoggerHUD.md#getsquareddistanceto)
- [GetTextSize](ue_ue.VisualLoggerHUD.md#gettextsize)
- [GetTickableWhenPaused](ue_ue.VisualLoggerHUD.md#gettickablewhenpaused)
- [GetTransform](ue_ue.VisualLoggerHUD.md#gettransform)
- [GetVelocity](ue_ue.VisualLoggerHUD.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.VisualLoggerHUD.md#getverticaldistanceto)
- [GetWorld](ue_ue.VisualLoggerHUD.md#getworld)
- [HasAuthority](ue_ue.VisualLoggerHUD.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.VisualLoggerHUD.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.VisualLoggerHUD.md#isactortickenabled)
- [IsChildActor](ue_ue.VisualLoggerHUD.md#ischildactor)
- [IsEditable](ue_ue.VisualLoggerHUD.md#iseditable)
- [IsHiddenEd](ue_ue.VisualLoggerHUD.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.VisualLoggerHUD.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.VisualLoggerHUD.md#isoverlappingactor)
- [IsSelectable](ue_ue.VisualLoggerHUD.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.VisualLoggerHUD.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.VisualLoggerHUD.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.VisualLoggerHUD.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.VisualLoggerHUD.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.VisualLoggerHUD.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.VisualLoggerHUD.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.VisualLoggerHUD.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.VisualLoggerHUD.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.VisualLoggerHUD.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.VisualLoggerHUD.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.VisualLoggerHUD.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.VisualLoggerHUD.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.VisualLoggerHUD.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.VisualLoggerHUD.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.VisualLoggerHUD.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.VisualLoggerHUD.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.VisualLoggerHUD.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.VisualLoggerHUD.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.VisualLoggerHUD.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.VisualLoggerHUD.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.VisualLoggerHUD.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.VisualLoggerHUD.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.VisualLoggerHUD.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.VisualLoggerHUD.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.VisualLoggerHUD.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.VisualLoggerHUD.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.VisualLoggerHUD.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.VisualLoggerHUD.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.VisualLoggerHUD.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.VisualLoggerHUD.md#makemidformaterial)
- [MakeNoise](ue_ue.VisualLoggerHUD.md#makenoise)
- [NextDebugTarget](ue_ue.VisualLoggerHUD.md#nextdebugtarget)
- [OnRep\_AttachmentReplication](ue_ue.VisualLoggerHUD.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.VisualLoggerHUD.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.VisualLoggerHUD.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.VisualLoggerHUD.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.VisualLoggerHUD.md#onrep_replicatedmovement)
- [PrestreamTextures](ue_ue.VisualLoggerHUD.md#prestreamtextures)
- [PreviousDebugTarget](ue_ue.VisualLoggerHUD.md#previousdebugtarget)
- [Project](ue_ue.VisualLoggerHUD.md#project)
- [ReceiveActorBeginCursorOver](ue_ue.VisualLoggerHUD.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.VisualLoggerHUD.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.VisualLoggerHUD.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.VisualLoggerHUD.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.VisualLoggerHUD.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.VisualLoggerHUD.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.VisualLoggerHUD.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.VisualLoggerHUD.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.VisualLoggerHUD.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.VisualLoggerHUD.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.VisualLoggerHUD.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.VisualLoggerHUD.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.VisualLoggerHUD.md#receivedestroyed)
- [ReceiveDrawHUD](ue_ue.VisualLoggerHUD.md#receivedrawhud)
- [ReceiveEndPlay](ue_ue.VisualLoggerHUD.md#receiveendplay)
- [ReceiveHit](ue_ue.VisualLoggerHUD.md#receivehit)
- [ReceiveHitBoxBeginCursorOver](ue_ue.VisualLoggerHUD.md#receivehitboxbegincursorover)
- [ReceiveHitBoxClick](ue_ue.VisualLoggerHUD.md#receivehitboxclick)
- [ReceiveHitBoxEndCursorOver](ue_ue.VisualLoggerHUD.md#receivehitboxendcursorover)
- [ReceiveHitBoxRelease](ue_ue.VisualLoggerHUD.md#receivehitboxrelease)
- [ReceivePointDamage](ue_ue.VisualLoggerHUD.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.VisualLoggerHUD.md#receiveradialdamage)
- [ReceiveTick](ue_ue.VisualLoggerHUD.md#receivetick)
- [RemoveAllDebugStrings](ue_ue.VisualLoggerHUD.md#removealldebugstrings)
- [RemoveDebugText](ue_ue.VisualLoggerHUD.md#removedebugtext)
- [RemoveTickPrerequisiteActor](ue_ue.VisualLoggerHUD.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.VisualLoggerHUD.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.VisualLoggerHUD.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.VisualLoggerHUD.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.VisualLoggerHUD.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.VisualLoggerHUD.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.VisualLoggerHUD.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.VisualLoggerHUD.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.VisualLoggerHUD.md#setactortickinterval)
- [SetFolderPath](ue_ue.VisualLoggerHUD.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.VisualLoggerHUD.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.VisualLoggerHUD.md#setlifespan)
- [SetNetDormancy](ue_ue.VisualLoggerHUD.md#setnetdormancy)
- [SetOwner](ue_ue.VisualLoggerHUD.md#setowner)
- [SetReplicateMovement](ue_ue.VisualLoggerHUD.md#setreplicatemovement)
- [SetReplicates](ue_ue.VisualLoggerHUD.md#setreplicates)
- [SetTickGroup](ue_ue.VisualLoggerHUD.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.VisualLoggerHUD.md#settickablewhenpaused)
- [ShowDebug](ue_ue.VisualLoggerHUD.md#showdebug)
- [ShowDebugForReticleTargetToggle](ue_ue.VisualLoggerHUD.md#showdebugforreticletargettoggle)
- [ShowDebugToggleSubCategory](ue_ue.VisualLoggerHUD.md#showdebugtogglesubcategory)
- [ShowHUD](ue_ue.VisualLoggerHUD.md#showhud)
- [SnapRootComponentTo](ue_ue.VisualLoggerHUD.md#snaprootcomponentto)
- [TearOff](ue_ue.VisualLoggerHUD.md#tearoff)
- [UserConstructionScript](ue_ue.VisualLoggerHUD.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.VisualLoggerHUD.md#wasrecentlyrendered)
- [Find](ue_ue.VisualLoggerHUD.md#find)
- [Load](ue_ue.VisualLoggerHUD.md#load)
- [StaticClass](ue_ue.VisualLoggerHUD.md#staticclass)

## Constructors

### constructor

• **new VisualLoggerHUD**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[constructor](ue_ue.DebugCameraHUD.md#constructor)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ActorLabel](ue_ue.DebugCameraHUD.md#actorlabel)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[AttachmentReplication](ue_ue.DebugCameraHUD.md#attachmentreplication)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[AutoReceiveInput](ue_ue.DebugCameraHUD.md#autoreceiveinput)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[BlueprintCreatedComponents](ue_ue.DebugCameraHUD.md#blueprintcreatedcomponents)

___

### Canvas

• **Canvas**: [`Canvas`](ue_ue.Canvas.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Canvas](ue_ue.DebugCameraHUD.md#canvas)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Children](ue_ue.DebugCameraHUD.md#children)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ControllingMatineeActors](ue_ue.DebugCameraHUD.md#controllingmatineeactors)

___

### CurrentTargetIndex

• **CurrentTargetIndex**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[CurrentTargetIndex](ue_ue.DebugCameraHUD.md#currenttargetindex)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[CustomTimeDilation](ue_ue.DebugCameraHUD.md#customtimedilation)

___

### DebugCanvas

• **DebugCanvas**: [`Canvas`](ue_ue.Canvas.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DebugCanvas](ue_ue.DebugCameraHUD.md#debugcanvas)

___

### DebugDisplay

• **DebugDisplay**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DebugDisplay](ue_ue.DebugCameraHUD.md#debugdisplay)

___

### DebugTextList

• **DebugTextList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DebugTextInfo`](ue_ue.DebugTextInfo.md)\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DebugTextList](ue_ue.DebugCameraHUD.md#debugtextlist)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.DebugCameraHUD.md#defaultupdateoverlapsmethodduringlevelstreaming)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[FolderPath](ue_ue.DebugCameraHUD.md#folderpath)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GroupActor](ue_ue.DebugCameraHUD.md#groupactor)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[HiddenEditorViews](ue_ue.DebugCameraHUD.md#hiddeneditorviews)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[InitialLifeSpan](ue_ue.DebugCameraHUD.md#initiallifespan)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[InputComponent](ue_ue.DebugCameraHUD.md#inputcomponent)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[InputPriority](ue_ue.DebugCameraHUD.md#inputpriority)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[InstanceComponents](ue_ue.DebugCameraHUD.md#instancecomponents)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Instigator](ue_ue.DebugCameraHUD.md#instigator)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Layers](ue_ue.DebugCameraHUD.md#layers)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[MinNetUpdateFrequency](ue_ue.DebugCameraHUD.md#minnetupdatefrequency)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[NetCullDistanceSquared](ue_ue.DebugCameraHUD.md#netculldistancesquared)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[NetDormancy](ue_ue.DebugCameraHUD.md#netdormancy)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[NetDriverName](ue_ue.DebugCameraHUD.md#netdrivername)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[NetPriority](ue_ue.DebugCameraHUD.md#netpriority)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[NetTag](ue_ue.DebugCameraHUD.md#nettag)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[NetUpdateFrequency](ue_ue.DebugCameraHUD.md#netupdatefrequency)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnActorBeginOverlap](ue_ue.DebugCameraHUD.md#onactorbeginoverlap)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnActorEndOverlap](ue_ue.DebugCameraHUD.md#onactorendoverlap)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnActorHit](ue_ue.DebugCameraHUD.md#onactorhit)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnBeginCursorOver](ue_ue.DebugCameraHUD.md#onbegincursorover)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnClicked](ue_ue.DebugCameraHUD.md#onclicked)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnDestroyed](ue_ue.DebugCameraHUD.md#ondestroyed)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnEndCursorOver](ue_ue.DebugCameraHUD.md#onendcursorover)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnEndPlay](ue_ue.DebugCameraHUD.md#onendplay)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnInputTouchBegin](ue_ue.DebugCameraHUD.md#oninputtouchbegin)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnInputTouchEnd](ue_ue.DebugCameraHUD.md#oninputtouchend)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnInputTouchEnter](ue_ue.DebugCameraHUD.md#oninputtouchenter)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnInputTouchLeave](ue_ue.DebugCameraHUD.md#oninputtouchleave)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnReleased](ue_ue.DebugCameraHUD.md#onreleased)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnTakeAnyDamage](ue_ue.DebugCameraHUD.md#ontakeanydamage)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnTakePointDamage](ue_ue.DebugCameraHUD.md#ontakepointdamage)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnTakeRadialDamage](ue_ue.DebugCameraHUD.md#ontakeradialdamage)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Owner](ue_ue.DebugCameraHUD.md#owner)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ParentComponent](ue_ue.DebugCameraHUD.md#parentcomponent)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ParentComponentActor](ue_ue.DebugCameraHUD.md#parentcomponentactor)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[PivotOffset](ue_ue.DebugCameraHUD.md#pivotoffset)

___

### PlayerOwner

• **PlayerOwner**: [`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[PlayerOwner](ue_ue.DebugCameraHUD.md#playerowner)

___

### PostRenderedActors

• **PostRenderedActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[PostRenderedActors](ue_ue.DebugCameraHUD.md#postrenderedactors)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[PrimaryActorTick](ue_ue.DebugCameraHUD.md#primaryactortick)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[RemoteRole](ue_ue.DebugCameraHUD.md#remoterole)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReplicatedMovement](ue_ue.DebugCameraHUD.md#replicatedmovement)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Role](ue_ue.DebugCameraHUD.md#role)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[RootComponent](ue_ue.DebugCameraHUD.md#rootcomponent)

___

### ShowDebugTargetActor

• **ShowDebugTargetActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ShowDebugTargetActor](ue_ue.DebugCameraHUD.md#showdebugtargetactor)

___

### ShowDebugTargetDesiredClass

• **ShowDebugTargetDesiredClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ShowDebugTargetDesiredClass](ue_ue.DebugCameraHUD.md#showdebugtargetdesiredclass)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SpawnCollisionHandlingMethod](ue_ue.DebugCameraHUD.md#spawncollisionhandlingmethod)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SpriteScale](ue_ue.DebugCameraHUD.md#spritescale)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Tags](ue_ue.DebugCameraHUD.md#tags)

___

### ToggledDebugCategories

• **ToggledDebugCategories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ToggledDebugCategories](ue_ue.DebugCameraHUD.md#toggleddebugcategories)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.DebugCameraHUD.md#updateoverlapsmethodduringlevelstreaming)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[__tid_Actor__](ue_ue.DebugCameraHUD.md#__tid_actor__)

___

### \_\_tid\_DebugCameraHUD\_\_

• **\_\_tid\_DebugCameraHUD\_\_**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[__tid_DebugCameraHUD__](ue_ue.DebugCameraHUD.md#__tid_debugcamerahud__)

___

### \_\_tid\_HUD\_\_

• **\_\_tid\_HUD\_\_**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[__tid_HUD__](ue_ue.DebugCameraHUD.md#__tid_hud__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[__tid_Object__](ue_ue.DebugCameraHUD.md#__tid_object__)

___

### \_\_tid\_VisualLoggerHUD\_\_

• **\_\_tid\_VisualLoggerHUD\_\_**: `boolean`

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bActorEnableCollision](ue_ue.DebugCameraHUD.md#bactorenablecollision)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bActorIsBeingDestroyed](ue_ue.DebugCameraHUD.md#bactorisbeingdestroyed)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bActorLabelEditable](ue_ue.DebugCameraHUD.md#bactorlabeleditable)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bActorSeamlessTraveled](ue_ue.DebugCameraHUD.md#bactorseamlesstraveled)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.DebugCameraHUD.md#ballowreceivetickeventondedicatedserver)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bAllowTickBeforeBeginPlay](ue_ue.DebugCameraHUD.md#ballowtickbeforebeginplay)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bAlwaysRelevant](ue_ue.DebugCameraHUD.md#balwaysrelevant)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bAutoDestroyWhenFinished](ue_ue.DebugCameraHUD.md#bautodestroywhenfinished)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bBlockInput](ue_ue.DebugCameraHUD.md#bblockinput)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bCanBeDamaged](ue_ue.DebugCameraHUD.md#bcanbedamaged)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bCanBeInCluster](ue_ue.DebugCameraHUD.md#bcanbeincluster)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bCollideWhenPlacing](ue_ue.DebugCameraHUD.md#bcollidewhenplacing)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bEditable](ue_ue.DebugCameraHUD.md#beditable)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bEnableAutoLODGeneration](ue_ue.DebugCameraHUD.md#benableautolodgeneration)

___

### bEnableDebugTextShadow

• **bEnableDebugTextShadow**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bEnableDebugTextShadow](ue_ue.DebugCameraHUD.md#benabledebugtextshadow)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bExchangedRoles](ue_ue.DebugCameraHUD.md#bexchangedroles)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bFindCameraComponentWhenViewTarget](ue_ue.DebugCameraHUD.md#bfindcameracomponentwhenviewtarget)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.DebugCameraHUD.md#bgenerateoverlapeventsduringlevelstreaming)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bHidden](ue_ue.DebugCameraHUD.md#bhidden)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bHiddenEd](ue_ue.DebugCameraHUD.md#bhiddened)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bHiddenEdLayer](ue_ue.DebugCameraHUD.md#bhiddenedlayer)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bHiddenEdLevel](ue_ue.DebugCameraHUD.md#bhiddenedlevel)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bHiddenEdTemporary](ue_ue.DebugCameraHUD.md#bhiddenedtemporary)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bIgnoresOriginShifting](ue_ue.DebugCameraHUD.md#bignoresoriginshifting)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bIsEditorOnlyActor](ue_ue.DebugCameraHUD.md#biseditoronlyactor)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bIsEditorPreviewActor](ue_ue.DebugCameraHUD.md#biseditorpreviewactor)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bListedInSceneOutliner](ue_ue.DebugCameraHUD.md#blistedinsceneoutliner)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bLockLocation](ue_ue.DebugCameraHUD.md#blocklocation)

___

### bLostFocusPaused

• **bLostFocusPaused**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bLostFocusPaused](ue_ue.DebugCameraHUD.md#blostfocuspaused)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bNetLoadOnClient](ue_ue.DebugCameraHUD.md#bnetloadonclient)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bNetStartup](ue_ue.DebugCameraHUD.md#bnetstartup)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bNetTemporary](ue_ue.DebugCameraHUD.md#bnettemporary)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bNetUseOwnerRelevancy](ue_ue.DebugCameraHUD.md#bnetuseownerrelevancy)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bOnlyRelevantToOwner](ue_ue.DebugCameraHUD.md#bonlyrelevanttoowner)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bOptimizeBPComponentData](ue_ue.DebugCameraHUD.md#boptimizebpcomponentdata)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bRelevantForLevelBounds](ue_ue.DebugCameraHUD.md#brelevantforlevelbounds)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bRelevantForNetworkReplays](ue_ue.DebugCameraHUD.md#brelevantfornetworkreplays)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bReplayRewindable](ue_ue.DebugCameraHUD.md#breplayrewindable)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bReplicateMovement](ue_ue.DebugCameraHUD.md#breplicatemovement)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bReplicates](ue_ue.DebugCameraHUD.md#breplicates)

___

### bShowDebugInfo

• **bShowDebugInfo**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bShowDebugInfo](ue_ue.DebugCameraHUD.md#bshowdebuginfo)

___

### bShowHUD

• **bShowHUD**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bShowHUD](ue_ue.DebugCameraHUD.md#bshowhud)

___

### bShowHitBoxDebugInfo

• **bShowHitBoxDebugInfo**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bShowHitBoxDebugInfo](ue_ue.DebugCameraHUD.md#bshowhitboxdebuginfo)

___

### bShowOverlays

• **bShowOverlays**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bShowOverlays](ue_ue.DebugCameraHUD.md#bshowoverlays)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bTearOff](ue_ue.DebugCameraHUD.md#btearoff)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ActorHasTag](ue_ue.DebugCameraHUD.md#actorhastag)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[AddComponent](ue_ue.DebugCameraHUD.md#addcomponent)

___

### AddDebugText

▸ **AddDebugText**(`DebugText`, `SrcActor`, `Duration`, `Offset`, `DesiredOffset`, `TextColor`, `bSkipOverwriteCheck`, `bAbsoluteLocation`, `bKeepAttachedToActor`, `InFont`, `FontScale`, `bDrawShadow`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DebugText` | `string` |
| `SrcActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `Duration` | `number` |
| `Offset` | [`Vector`](ue_ue_s.Vector.md) |
| `DesiredOffset` | [`Vector`](ue_ue_s.Vector.md) |
| `TextColor` | [`Color`](ue_ue_s.Color.md) |
| `bSkipOverwriteCheck` | `boolean` |
| `bAbsoluteLocation` | `boolean` |
| `bKeepAttachedToActor` | `boolean` |
| `InFont` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Font`](ue_ue.Font.md)\> |
| `FontScale` | `number` |
| `bDrawShadow` | `boolean` |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[AddDebugText](ue_ue.DebugCameraHUD.md#adddebugtext)

___

### AddHitBox

▸ **AddHitBox**(`Position`, `Size`, `InName`, `bConsumesInput`, `Priority?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Position` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `Size` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `InName` | `string` |
| `bConsumesInput` | `boolean` |
| `Priority?` | `number` |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[AddHitBox](ue_ue.DebugCameraHUD.md#addhitbox)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[AddTickPrerequisiteActor](ue_ue.DebugCameraHUD.md#addtickprerequisiteactor)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[AddTickPrerequisiteComponent](ue_ue.DebugCameraHUD.md#addtickprerequisitecomponent)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[CreateDefaultSubobject](ue_ue.DebugCameraHUD.md#createdefaultsubobject)

___

### Deproject

▸ **Deproject**(`ScreenX`, `ScreenY`, `WorldPosition`, `WorldDirection`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ScreenX` | `number` |
| `ScreenY` | `number` |
| `WorldPosition` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `WorldDirection` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Deproject](ue_ue.DebugCameraHUD.md#deproject)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DetachRootComponentFromParent](ue_ue.DebugCameraHUD.md#detachrootcomponentfromparent)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DisableInput](ue_ue.DebugCameraHUD.md#disableinput)

___

### DrawLine

▸ **DrawLine**(`StartScreenX`, `StartScreenY`, `EndScreenX`, `EndScreenY`, `LineColor`, `LineThickness?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StartScreenX` | `number` |
| `StartScreenY` | `number` |
| `EndScreenX` | `number` |
| `EndScreenY` | `number` |
| `LineColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `LineThickness?` | `number` |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DrawLine](ue_ue.DebugCameraHUD.md#drawline)

___

### DrawMaterial

▸ **DrawMaterial**(`Material`, `ScreenX`, `ScreenY`, `ScreenW`, `ScreenH`, `MaterialU`, `MaterialV`, `MaterialUWidth`, `MaterialVHeight`, `Scale?`, `bScalePosition?`, `Rotation?`, `RotPivot?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `ScreenX` | `number` |
| `ScreenY` | `number` |
| `ScreenW` | `number` |
| `ScreenH` | `number` |
| `MaterialU` | `number` |
| `MaterialV` | `number` |
| `MaterialUWidth` | `number` |
| `MaterialVHeight` | `number` |
| `Scale?` | `number` |
| `bScalePosition?` | `boolean` |
| `Rotation?` | `number` |
| `RotPivot?` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DrawMaterial](ue_ue.DebugCameraHUD.md#drawmaterial)

___

### DrawMaterialSimple

▸ **DrawMaterialSimple**(`Material`, `ScreenX`, `ScreenY`, `ScreenW`, `ScreenH`, `Scale?`, `bScalePosition?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `ScreenX` | `number` |
| `ScreenY` | `number` |
| `ScreenW` | `number` |
| `ScreenH` | `number` |
| `Scale?` | `number` |
| `bScalePosition?` | `boolean` |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DrawMaterialSimple](ue_ue.DebugCameraHUD.md#drawmaterialsimple)

___

### DrawMaterialTriangle

▸ **DrawMaterialTriangle**(`Material`, `V0_Pos`, `V1_Pos`, `V2_Pos`, `V0_UV`, `V1_UV`, `V2_UV`, `V0_Color?`, `V1_Color?`, `V2_Color?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `V0_Pos` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `V1_Pos` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `V2_Pos` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `V0_UV` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `V1_UV` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `V2_UV` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `V0_Color?` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `V1_Color?` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `V2_Color?` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DrawMaterialTriangle](ue_ue.DebugCameraHUD.md#drawmaterialtriangle)

___

### DrawRect

▸ **DrawRect**(`RectColor`, `ScreenX`, `ScreenY`, `ScreenW`, `ScreenH`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `RectColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `ScreenX` | `number` |
| `ScreenY` | `number` |
| `ScreenW` | `number` |
| `ScreenH` | `number` |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DrawRect](ue_ue.DebugCameraHUD.md#drawrect)

___

### DrawText

▸ **DrawText**(`Text`, `TextColor`, `ScreenX`, `ScreenY`, `Font?`, `Scale?`, `bScalePosition?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Text` | `string` |
| `TextColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `ScreenX` | `number` |
| `ScreenY` | `number` |
| `Font?` | [`Font`](ue_ue.Font.md) |
| `Scale?` | `number` |
| `bScalePosition?` | `boolean` |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DrawText](ue_ue.DebugCameraHUD.md#drawtext)

___

### DrawTexture

▸ **DrawTexture**(`Texture`, `ScreenX`, `ScreenY`, `ScreenW`, `ScreenH`, `TextureU`, `TextureV`, `TextureUWidth`, `TextureVHeight`, `TintColor?`, `BlendMode?`, `Scale?`, `bScalePosition?`, `Rotation?`, `RotPivot?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Texture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `ScreenX` | `number` |
| `ScreenY` | `number` |
| `ScreenW` | `number` |
| `ScreenH` | `number` |
| `TextureU` | `number` |
| `TextureV` | `number` |
| `TextureUWidth` | `number` |
| `TextureVHeight` | `number` |
| `TintColor?` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `BlendMode?` | [`EBlendMode`](../enums/ue_ue.EBlendMode.md) |
| `Scale?` | `number` |
| `bScalePosition?` | `boolean` |
| `Rotation?` | `number` |
| `RotPivot?` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DrawTexture](ue_ue.DebugCameraHUD.md#drawtexture)

___

### DrawTextureSimple

▸ **DrawTextureSimple**(`Texture`, `ScreenX`, `ScreenY`, `Scale?`, `bScalePosition?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Texture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `ScreenX` | `number` |
| `ScreenY` | `number` |
| `Scale?` | `number` |
| `bScalePosition?` | `boolean` |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DrawTextureSimple](ue_ue.DebugCameraHUD.md#drawtexturesimple)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[EnableInput](ue_ue.DebugCameraHUD.md#enableinput)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ExecuteUbergraph](ue_ue.DebugCameraHUD.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[FlushNetDormancy](ue_ue.DebugCameraHUD.md#flushnetdormancy)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ForceNetUpdate](ue_ue.DebugCameraHUD.md#forcenetupdate)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorBounds](ue_ue.DebugCameraHUD.md#getactorbounds)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorEnableCollision](ue_ue.DebugCameraHUD.md#getactorenablecollision)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorEyesViewPoint](ue_ue.DebugCameraHUD.md#getactoreyesviewpoint)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorForwardVector](ue_ue.DebugCameraHUD.md#getactorforwardvector)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorLabel](ue_ue.DebugCameraHUD.md#getactorlabel)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorRelativeScale3D](ue_ue.DebugCameraHUD.md#getactorrelativescale3d)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorRightVector](ue_ue.DebugCameraHUD.md#getactorrightvector)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorScale3D](ue_ue.DebugCameraHUD.md#getactorscale3d)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorTickInterval](ue_ue.DebugCameraHUD.md#getactortickinterval)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorTimeDilation](ue_ue.DebugCameraHUD.md#getactortimedilation)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorUpVector](ue_ue.DebugCameraHUD.md#getactorupvector)

___

### GetActorsInSelectionRectangle

▸ **GetActorsInSelectionRectangle**(`ClassFilter`, `FirstPoint`, `SecondPoint`, `OutActors`, `bIncludeNonCollidingComponents?`, `bActorMustBeFullyEnclosed?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ClassFilter` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `FirstPoint` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `SecondPoint` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `OutActors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |
| `bIncludeNonCollidingComponents?` | `boolean` |
| `bActorMustBeFullyEnclosed?` | `boolean` |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorsInSelectionRectangle](ue_ue.DebugCameraHUD.md#getactorsinselectionrectangle)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetAllChildActors](ue_ue.DebugCameraHUD.md#getallchildactors)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetAttachParentActor](ue_ue.DebugCameraHUD.md#getattachparentactor)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetAttachParentSocketName](ue_ue.DebugCameraHUD.md#getattachparentsocketname)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetAttachedActors](ue_ue.DebugCameraHUD.md#getattachedactors)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetClass](ue_ue.DebugCameraHUD.md#getclass)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetComponentByClass](ue_ue.DebugCameraHUD.md#getcomponentbyclass)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetComponentsByInterface](ue_ue.DebugCameraHUD.md#getcomponentsbyinterface)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetComponentsByTag](ue_ue.DebugCameraHUD.md#getcomponentsbytag)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetDistanceTo](ue_ue.DebugCameraHUD.md#getdistanceto)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetDotProductTo](ue_ue.DebugCameraHUD.md#getdotproductto)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetFolderPath](ue_ue.DebugCameraHUD.md#getfolderpath)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetGameTimeSinceCreation](ue_ue.DebugCameraHUD.md#getgametimesincecreation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetHorizontalDistanceTo](ue_ue.DebugCameraHUD.md#gethorizontaldistanceto)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetHorizontalDotProductTo](ue_ue.DebugCameraHUD.md#gethorizontaldotproductto)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetInputAxisKeyValue](ue_ue.DebugCameraHUD.md#getinputaxiskeyvalue)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetInputAxisValue](ue_ue.DebugCameraHUD.md#getinputaxisvalue)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetInputVectorAxisValue](ue_ue.DebugCameraHUD.md#getinputvectoraxisvalue)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetInstigator](ue_ue.DebugCameraHUD.md#getinstigator)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetInstigatorController](ue_ue.DebugCameraHUD.md#getinstigatorcontroller)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetLifeSpan](ue_ue.DebugCameraHUD.md#getlifespan)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetLocalRole](ue_ue.DebugCameraHUD.md#getlocalrole)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetName](ue_ue.DebugCameraHUD.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetOuter](ue_ue.DebugCameraHUD.md#getouter)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetOverlappingActors](ue_ue.DebugCameraHUD.md#getoverlappingactors)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetOverlappingComponents](ue_ue.DebugCameraHUD.md#getoverlappingcomponents)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetOwner](ue_ue.DebugCameraHUD.md#getowner)

___

### GetOwningPawn

▸ **GetOwningPawn**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetOwningPawn](ue_ue.DebugCameraHUD.md#getowningpawn)

___

### GetOwningPlayerController

▸ **GetOwningPlayerController**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetOwningPlayerController](ue_ue.DebugCameraHUD.md#getowningplayercontroller)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetParentActor](ue_ue.DebugCameraHUD.md#getparentactor)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetParentComponent](ue_ue.DebugCameraHUD.md#getparentcomponent)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetRemoteRole](ue_ue.DebugCameraHUD.md#getremoterole)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetSquaredDistanceTo](ue_ue.DebugCameraHUD.md#getsquareddistanceto)

___

### GetTextSize

▸ **GetTextSize**(`Text`, `OutWidth`, `OutHeight`, `Font?`, `Scale?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Text` | `string` |
| `OutWidth` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `OutHeight` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `Font?` | [`Font`](ue_ue.Font.md) |
| `Scale?` | `number` |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetTextSize](ue_ue.DebugCameraHUD.md#gettextsize)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetTickableWhenPaused](ue_ue.DebugCameraHUD.md#gettickablewhenpaused)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetTransform](ue_ue.DebugCameraHUD.md#gettransform)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetVelocity](ue_ue.DebugCameraHUD.md#getvelocity)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetVerticalDistanceTo](ue_ue.DebugCameraHUD.md#getverticaldistanceto)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetWorld](ue_ue.DebugCameraHUD.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[HasAuthority](ue_ue.DebugCameraHUD.md#hasauthority)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsActorBeingDestroyed](ue_ue.DebugCameraHUD.md#isactorbeingdestroyed)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsActorTickEnabled](ue_ue.DebugCameraHUD.md#isactortickenabled)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsChildActor](ue_ue.DebugCameraHUD.md#ischildactor)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsEditable](ue_ue.DebugCameraHUD.md#iseditable)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsHiddenEd](ue_ue.DebugCameraHUD.md#ishiddened)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsHiddenEdAtStartup](ue_ue.DebugCameraHUD.md#ishiddenedatstartup)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsOverlappingActor](ue_ue.DebugCameraHUD.md#isoverlappingactor)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsSelectable](ue_ue.DebugCameraHUD.md#isselectable)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsTemporarilyHiddenInEditor](ue_ue.DebugCameraHUD.md#istemporarilyhiddenineditor)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AddActorLocalOffset](ue_ue.DebugCameraHUD.md#k2_addactorlocaloffset)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AddActorLocalRotation](ue_ue.DebugCameraHUD.md#k2_addactorlocalrotation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AddActorLocalTransform](ue_ue.DebugCameraHUD.md#k2_addactorlocaltransform)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AddActorWorldOffset](ue_ue.DebugCameraHUD.md#k2_addactorworldoffset)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AddActorWorldRotation](ue_ue.DebugCameraHUD.md#k2_addactorworldrotation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AddActorWorldTransform](ue_ue.DebugCameraHUD.md#k2_addactorworldtransform)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AttachRootComponentTo](ue_ue.DebugCameraHUD.md#k2_attachrootcomponentto)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AttachRootComponentToActor](ue_ue.DebugCameraHUD.md#k2_attachrootcomponenttoactor)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AttachToActor](ue_ue.DebugCameraHUD.md#k2_attachtoactor)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AttachToComponent](ue_ue.DebugCameraHUD.md#k2_attachtocomponent)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_DestroyActor](ue_ue.DebugCameraHUD.md#k2_destroyactor)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_DestroyComponent](ue_ue.DebugCameraHUD.md#k2_destroycomponent)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_DetachFromActor](ue_ue.DebugCameraHUD.md#k2_detachfromactor)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_GetActorLocation](ue_ue.DebugCameraHUD.md#k2_getactorlocation)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_GetActorRotation](ue_ue.DebugCameraHUD.md#k2_getactorrotation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_GetComponentsByClass](ue_ue.DebugCameraHUD.md#k2_getcomponentsbyclass)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_GetRootComponent](ue_ue.DebugCameraHUD.md#k2_getrootcomponent)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_OnBecomeViewTarget](ue_ue.DebugCameraHUD.md#k2_onbecomeviewtarget)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_OnEndViewTarget](ue_ue.DebugCameraHUD.md#k2_onendviewtarget)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_OnReset](ue_ue.DebugCameraHUD.md#k2_onreset)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_SetActorLocation](ue_ue.DebugCameraHUD.md#k2_setactorlocation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_SetActorLocationAndRotation](ue_ue.DebugCameraHUD.md#k2_setactorlocationandrotation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_SetActorRelativeLocation](ue_ue.DebugCameraHUD.md#k2_setactorrelativelocation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_SetActorRelativeRotation](ue_ue.DebugCameraHUD.md#k2_setactorrelativerotation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_SetActorRelativeTransform](ue_ue.DebugCameraHUD.md#k2_setactorrelativetransform)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_SetActorRotation](ue_ue.DebugCameraHUD.md#k2_setactorrotation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_SetActorTransform](ue_ue.DebugCameraHUD.md#k2_setactortransform)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_TeleportTo](ue_ue.DebugCameraHUD.md#k2_teleportto)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[MakeMIDForMaterial](ue_ue.DebugCameraHUD.md#makemidformaterial)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[MakeNoise](ue_ue.DebugCameraHUD.md#makenoise)

___

### NextDebugTarget

▸ **NextDebugTarget**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[NextDebugTarget](ue_ue.DebugCameraHUD.md#nextdebugtarget)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnRep_AttachmentReplication](ue_ue.DebugCameraHUD.md#onrep_attachmentreplication)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnRep_Instigator](ue_ue.DebugCameraHUD.md#onrep_instigator)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnRep_Owner](ue_ue.DebugCameraHUD.md#onrep_owner)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnRep_ReplicateMovement](ue_ue.DebugCameraHUD.md#onrep_replicatemovement)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnRep_ReplicatedMovement](ue_ue.DebugCameraHUD.md#onrep_replicatedmovement)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[PrestreamTextures](ue_ue.DebugCameraHUD.md#prestreamtextures)

___

### PreviousDebugTarget

▸ **PreviousDebugTarget**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[PreviousDebugTarget](ue_ue.DebugCameraHUD.md#previousdebugtarget)

___

### Project

▸ **Project**(`Location`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Project](ue_ue.DebugCameraHUD.md#project)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorBeginCursorOver](ue_ue.DebugCameraHUD.md#receiveactorbegincursorover)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorBeginOverlap](ue_ue.DebugCameraHUD.md#receiveactorbeginoverlap)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorEndCursorOver](ue_ue.DebugCameraHUD.md#receiveactorendcursorover)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorEndOverlap](ue_ue.DebugCameraHUD.md#receiveactorendoverlap)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorOnClicked](ue_ue.DebugCameraHUD.md#receiveactoronclicked)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorOnInputTouchBegin](ue_ue.DebugCameraHUD.md#receiveactoroninputtouchbegin)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorOnInputTouchEnd](ue_ue.DebugCameraHUD.md#receiveactoroninputtouchend)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorOnInputTouchEnter](ue_ue.DebugCameraHUD.md#receiveactoroninputtouchenter)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorOnInputTouchLeave](ue_ue.DebugCameraHUD.md#receiveactoroninputtouchleave)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorOnReleased](ue_ue.DebugCameraHUD.md#receiveactoronreleased)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveAnyDamage](ue_ue.DebugCameraHUD.md#receiveanydamage)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveBeginPlay](ue_ue.DebugCameraHUD.md#receivebeginplay)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveDestroyed](ue_ue.DebugCameraHUD.md#receivedestroyed)

___

### ReceiveDrawHUD

▸ **ReceiveDrawHUD**(`SizeX`, `SizeY`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SizeX` | `number` |
| `SizeY` | `number` |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveDrawHUD](ue_ue.DebugCameraHUD.md#receivedrawhud)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveEndPlay](ue_ue.DebugCameraHUD.md#receiveendplay)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveHit](ue_ue.DebugCameraHUD.md#receivehit)

___

### ReceiveHitBoxBeginCursorOver

▸ **ReceiveHitBoxBeginCursorOver**(`BoxName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoxName` | `string` |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveHitBoxBeginCursorOver](ue_ue.DebugCameraHUD.md#receivehitboxbegincursorover)

___

### ReceiveHitBoxClick

▸ **ReceiveHitBoxClick**(`BoxName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoxName` | `string` |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveHitBoxClick](ue_ue.DebugCameraHUD.md#receivehitboxclick)

___

### ReceiveHitBoxEndCursorOver

▸ **ReceiveHitBoxEndCursorOver**(`BoxName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoxName` | `string` |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveHitBoxEndCursorOver](ue_ue.DebugCameraHUD.md#receivehitboxendcursorover)

___

### ReceiveHitBoxRelease

▸ **ReceiveHitBoxRelease**(`BoxName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoxName` | `string` |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveHitBoxRelease](ue_ue.DebugCameraHUD.md#receivehitboxrelease)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceivePointDamage](ue_ue.DebugCameraHUD.md#receivepointdamage)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveRadialDamage](ue_ue.DebugCameraHUD.md#receiveradialdamage)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveTick](ue_ue.DebugCameraHUD.md#receivetick)

___

### RemoveAllDebugStrings

▸ **RemoveAllDebugStrings**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[RemoveAllDebugStrings](ue_ue.DebugCameraHUD.md#removealldebugstrings)

___

### RemoveDebugText

▸ **RemoveDebugText**(`SrcActor`, `bLeaveDurationText`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SrcActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `bLeaveDurationText` | `boolean` |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[RemoveDebugText](ue_ue.DebugCameraHUD.md#removedebugtext)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[RemoveTickPrerequisiteActor](ue_ue.DebugCameraHUD.md#removetickprerequisiteactor)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[RemoveTickPrerequisiteComponent](ue_ue.DebugCameraHUD.md#removetickprerequisitecomponent)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetActorEnableCollision](ue_ue.DebugCameraHUD.md#setactorenablecollision)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetActorHiddenInGame](ue_ue.DebugCameraHUD.md#setactorhiddeningame)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetActorLabel](ue_ue.DebugCameraHUD.md#setactorlabel)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetActorRelativeScale3D](ue_ue.DebugCameraHUD.md#setactorrelativescale3d)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetActorScale3D](ue_ue.DebugCameraHUD.md#setactorscale3d)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetActorTickEnabled](ue_ue.DebugCameraHUD.md#setactortickenabled)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetActorTickInterval](ue_ue.DebugCameraHUD.md#setactortickinterval)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetFolderPath](ue_ue.DebugCameraHUD.md#setfolderpath)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetIsTemporarilyHiddenInEditor](ue_ue.DebugCameraHUD.md#setistemporarilyhiddenineditor)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetLifeSpan](ue_ue.DebugCameraHUD.md#setlifespan)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetNetDormancy](ue_ue.DebugCameraHUD.md#setnetdormancy)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetOwner](ue_ue.DebugCameraHUD.md#setowner)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetReplicateMovement](ue_ue.DebugCameraHUD.md#setreplicatemovement)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetReplicates](ue_ue.DebugCameraHUD.md#setreplicates)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetTickGroup](ue_ue.DebugCameraHUD.md#settickgroup)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetTickableWhenPaused](ue_ue.DebugCameraHUD.md#settickablewhenpaused)

___

### ShowDebug

▸ **ShowDebug**(`DebugType?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DebugType?` | `string` |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ShowDebug](ue_ue.DebugCameraHUD.md#showdebug)

___

### ShowDebugForReticleTargetToggle

▸ **ShowDebugForReticleTargetToggle**(`DesiredClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DesiredClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ShowDebugForReticleTargetToggle](ue_ue.DebugCameraHUD.md#showdebugforreticletargettoggle)

___

### ShowDebugToggleSubCategory

▸ **ShowDebugToggleSubCategory**(`Category`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Category` | `string` |

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ShowDebugToggleSubCategory](ue_ue.DebugCameraHUD.md#showdebugtogglesubcategory)

___

### ShowHUD

▸ **ShowHUD**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ShowHUD](ue_ue.DebugCameraHUD.md#showhud)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SnapRootComponentTo](ue_ue.DebugCameraHUD.md#snaprootcomponentto)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[TearOff](ue_ue.DebugCameraHUD.md#tearoff)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[UserConstructionScript](ue_ue.DebugCameraHUD.md#userconstructionscript)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[WasRecentlyRendered](ue_ue.DebugCameraHUD.md#wasrecentlyrendered)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VisualLoggerHUD`](ue_ue.VisualLoggerHUD.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VisualLoggerHUD`](ue_ue.VisualLoggerHUD.md)

#### Overrides

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Find](ue_ue.DebugCameraHUD.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`VisualLoggerHUD`](ue_ue.VisualLoggerHUD.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VisualLoggerHUD`](ue_ue.VisualLoggerHUD.md)

#### Overrides

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Load](ue_ue.DebugCameraHUD.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[StaticClass](ue_ue.DebugCameraHUD.md#staticclass)
