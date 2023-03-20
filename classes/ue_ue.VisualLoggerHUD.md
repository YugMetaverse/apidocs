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

#### Defined in

[ue/ue.d.ts:65320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65320)

## Properties

### ActorLabel

• **ActorLabel**: `string`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ActorLabel](ue_ue.DebugCameraHUD.md#actorlabel)

#### Defined in

[ue/ue.d.ts:13176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13176)

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[AttachmentReplication](ue_ue.DebugCameraHUD.md#attachmentreplication)

#### Defined in

[ue/ue.d.ts:13151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13151)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[AutoReceiveInput](ue_ue.DebugCameraHUD.md#autoreceiveinput)

#### Defined in

[ue/ue.d.ts:13157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13157)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[BlueprintCreatedComponents](ue_ue.DebugCameraHUD.md#blueprintcreatedcomponents)

#### Defined in

[ue/ue.d.ts:13206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13206)

___

### Canvas

• **Canvas**: [`Canvas`](ue_ue.Canvas.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Canvas](ue_ue.DebugCameraHUD.md#canvas)

#### Defined in

[ue/ue.d.ts:6180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6180)

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Children](ue_ue.DebugCameraHUD.md#children)

#### Defined in

[ue/ue.d.ts:13166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13166)

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ControllingMatineeActors](ue_ue.DebugCameraHUD.md#controllingmatineeactors)

#### Defined in

[ue/ue.d.ts:13169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13169)

___

### CurrentTargetIndex

• **CurrentTargetIndex**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[CurrentTargetIndex](ue_ue.DebugCameraHUD.md#currenttargetindex)

#### Defined in

[ue/ue.d.ts:6173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6173)

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[CustomTimeDilation](ue_ue.DebugCameraHUD.md#customtimedilation)

#### Defined in

[ue/ue.d.ts:13150](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13150)

___

### DebugCanvas

• **DebugCanvas**: [`Canvas`](ue_ue.Canvas.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DebugCanvas](ue_ue.DebugCameraHUD.md#debugcanvas)

#### Defined in

[ue/ue.d.ts:6181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6181)

___

### DebugDisplay

• **DebugDisplay**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DebugDisplay](ue_ue.DebugCameraHUD.md#debugdisplay)

#### Defined in

[ue/ue.d.ts:6178](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6178)

___

### DebugTextList

• **DebugTextList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DebugTextInfo`](ue_ue.DebugTextInfo.md)\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DebugTextList](ue_ue.DebugCameraHUD.md#debugtextlist)

#### Defined in

[ue/ue.d.ts:6182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6182)

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.DebugCameraHUD.md#defaultupdateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13146](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13146)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[FolderPath](ue_ue.DebugCameraHUD.md#folderpath)

#### Defined in

[ue/ue.d.ts:13177](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13177)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GroupActor](ue_ue.DebugCameraHUD.md#groupactor)

#### Defined in

[ue/ue.d.ts:13173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13173)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[HiddenEditorViews](ue_ue.DebugCameraHUD.md#hiddeneditorviews)

#### Defined in

[ue/ue.d.ts:13175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13175)

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[InitialLifeSpan](ue_ue.DebugCameraHUD.md#initiallifespan)

#### Defined in

[ue/ue.d.ts:13149](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13149)

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[InputComponent](ue_ue.DebugCameraHUD.md#inputcomponent)

#### Defined in

[ue/ue.d.ts:13159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13159)

___

### InputPriority

• **InputPriority**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[InputPriority](ue_ue.DebugCameraHUD.md#inputpriority)

#### Defined in

[ue/ue.d.ts:13158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13158)

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[InstanceComponents](ue_ue.DebugCameraHUD.md#instancecomponents)

#### Defined in

[ue/ue.d.ts:13205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13205)

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Instigator](ue_ue.DebugCameraHUD.md#instigator)

#### Defined in

[ue/ue.d.ts:13165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13165)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Layers](ue_ue.DebugCameraHUD.md#layers)

#### Defined in

[ue/ue.d.ts:13170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13170)

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[MinNetUpdateFrequency](ue_ue.DebugCameraHUD.md#minnetupdatefrequency)

#### Defined in

[ue/ue.d.ts:13163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13163)

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[NetCullDistanceSquared](ue_ue.DebugCameraHUD.md#netculldistancesquared)

#### Defined in

[ue/ue.d.ts:13160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13160)

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[NetDormancy](ue_ue.DebugCameraHUD.md#netdormancy)

#### Defined in

[ue/ue.d.ts:13155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13155)

___

### NetDriverName

• **NetDriverName**: `string`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[NetDriverName](ue_ue.DebugCameraHUD.md#netdrivername)

#### Defined in

[ue/ue.d.ts:13153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13153)

___

### NetPriority

• **NetPriority**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[NetPriority](ue_ue.DebugCameraHUD.md#netpriority)

#### Defined in

[ue/ue.d.ts:13164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13164)

___

### NetTag

• **NetTag**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[NetTag](ue_ue.DebugCameraHUD.md#nettag)

#### Defined in

[ue/ue.d.ts:13161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13161)

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[NetUpdateFrequency](ue_ue.DebugCameraHUD.md#netupdatefrequency)

#### Defined in

[ue/ue.d.ts:13162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13162)

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnActorBeginOverlap](ue_ue.DebugCameraHUD.md#onactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13192)

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnActorEndOverlap](ue_ue.DebugCameraHUD.md#onactorendoverlap)

#### Defined in

[ue/ue.d.ts:13193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13193)

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnActorHit](ue_ue.DebugCameraHUD.md#onactorhit)

#### Defined in

[ue/ue.d.ts:13202](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13202)

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnBeginCursorOver](ue_ue.DebugCameraHUD.md#onbegincursorover)

#### Defined in

[ue/ue.d.ts:13194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13194)

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnClicked](ue_ue.DebugCameraHUD.md#onclicked)

#### Defined in

[ue/ue.d.ts:13196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13196)

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnDestroyed](ue_ue.DebugCameraHUD.md#ondestroyed)

#### Defined in

[ue/ue.d.ts:13203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13203)

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnEndCursorOver](ue_ue.DebugCameraHUD.md#onendcursorover)

#### Defined in

[ue/ue.d.ts:13195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13195)

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnEndPlay](ue_ue.DebugCameraHUD.md#onendplay)

#### Defined in

[ue/ue.d.ts:13204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13204)

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnInputTouchBegin](ue_ue.DebugCameraHUD.md#oninputtouchbegin)

#### Defined in

[ue/ue.d.ts:13198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13198)

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnInputTouchEnd](ue_ue.DebugCameraHUD.md#oninputtouchend)

#### Defined in

[ue/ue.d.ts:13199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13199)

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnInputTouchEnter](ue_ue.DebugCameraHUD.md#oninputtouchenter)

#### Defined in

[ue/ue.d.ts:13200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13200)

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnInputTouchLeave](ue_ue.DebugCameraHUD.md#oninputtouchleave)

#### Defined in

[ue/ue.d.ts:13201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13201)

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnReleased](ue_ue.DebugCameraHUD.md#onreleased)

#### Defined in

[ue/ue.d.ts:13197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13197)

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnTakeAnyDamage](ue_ue.DebugCameraHUD.md#ontakeanydamage)

#### Defined in

[ue/ue.d.ts:13189](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13189)

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnTakePointDamage](ue_ue.DebugCameraHUD.md#ontakepointdamage)

#### Defined in

[ue/ue.d.ts:13190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13190)

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnTakeRadialDamage](ue_ue.DebugCameraHUD.md#ontakeradialdamage)

#### Defined in

[ue/ue.d.ts:13191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13191)

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Owner](ue_ue.DebugCameraHUD.md#owner)

#### Defined in

[ue/ue.d.ts:13152](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13152)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ParentComponent](ue_ue.DebugCameraHUD.md#parentcomponent)

#### Defined in

[ue/ue.d.ts:13172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13172)

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ParentComponentActor](ue_ue.DebugCameraHUD.md#parentcomponentactor)

#### Defined in

[ue/ue.d.ts:13171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13171)

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[PivotOffset](ue_ue.DebugCameraHUD.md#pivotoffset)

#### Defined in

[ue/ue.d.ts:13168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13168)

___

### PlayerOwner

• **PlayerOwner**: [`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[PlayerOwner](ue_ue.DebugCameraHUD.md#playerowner)

#### Defined in

[ue/ue.d.ts:6169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6169)

___

### PostRenderedActors

• **PostRenderedActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[PostRenderedActors](ue_ue.DebugCameraHUD.md#postrenderedactors)

#### Defined in

[ue/ue.d.ts:6177](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6177)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[PrimaryActorTick](ue_ue.DebugCameraHUD.md#primaryactortick)

#### Defined in

[ue/ue.d.ts:13115](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13115)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[RemoteRole](ue_ue.DebugCameraHUD.md#remoterole)

#### Defined in

[ue/ue.d.ts:13147](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13147)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReplicatedMovement](ue_ue.DebugCameraHUD.md#replicatedmovement)

#### Defined in

[ue/ue.d.ts:13148](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13148)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Role](ue_ue.DebugCameraHUD.md#role)

#### Defined in

[ue/ue.d.ts:13154](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13154)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[RootComponent](ue_ue.DebugCameraHUD.md#rootcomponent)

#### Defined in

[ue/ue.d.ts:13167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13167)

___

### ShowDebugTargetActor

• **ShowDebugTargetActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ShowDebugTargetActor](ue_ue.DebugCameraHUD.md#showdebugtargetactor)

#### Defined in

[ue/ue.d.ts:6184](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6184)

___

### ShowDebugTargetDesiredClass

• **ShowDebugTargetDesiredClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ShowDebugTargetDesiredClass](ue_ue.DebugCameraHUD.md#showdebugtargetdesiredclass)

#### Defined in

[ue/ue.d.ts:6183](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6183)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SpawnCollisionHandlingMethod](ue_ue.DebugCameraHUD.md#spawncollisionhandlingmethod)

#### Defined in

[ue/ue.d.ts:13156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13156)

___

### SpriteScale

• **SpriteScale**: `number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SpriteScale](ue_ue.DebugCameraHUD.md#spritescale)

#### Defined in

[ue/ue.d.ts:13174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13174)

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[Tags](ue_ue.DebugCameraHUD.md#tags)

#### Defined in

[ue/ue.d.ts:13188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13188)

___

### ToggledDebugCategories

• **ToggledDebugCategories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ToggledDebugCategories](ue_ue.DebugCameraHUD.md#toggleddebugcategories)

#### Defined in

[ue/ue.d.ts:6179](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6179)

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[UpdateOverlapsMethodDuringLevelStreaming](ue_ue.DebugCameraHUD.md#updateoverlapsmethodduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13145](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13145)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[__tid_Actor__](ue_ue.DebugCameraHUD.md#__tid_actor__)

#### Defined in

[ue/ue.d.ts:13348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13348)

___

### \_\_tid\_DebugCameraHUD\_\_

• **\_\_tid\_DebugCameraHUD\_\_**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[__tid_DebugCameraHUD__](ue_ue.DebugCameraHUD.md#__tid_debugcamerahud__)

#### Defined in

[ue/ue.d.ts:30272](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30272)

___

### \_\_tid\_HUD\_\_

• **\_\_tid\_HUD\_\_**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[__tid_HUD__](ue_ue.DebugCameraHUD.md#__tid_hud__)

#### Defined in

[ue/ue.d.ts:6218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6218)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[__tid_Object__](ue_ue.DebugCameraHUD.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_VisualLoggerHUD\_\_

• **\_\_tid\_VisualLoggerHUD\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:65325](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65325)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bActorEnableCollision](ue_ue.DebugCameraHUD.md#bactorenablecollision)

#### Defined in

[ue/ue.d.ts:13143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13143)

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bActorIsBeingDestroyed](ue_ue.DebugCameraHUD.md#bactorisbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13144](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13144)

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bActorLabelEditable](ue_ue.DebugCameraHUD.md#bactorlabeleditable)

#### Defined in

[ue/ue.d.ts:13183](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13183)

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bActorSeamlessTraveled](ue_ue.DebugCameraHUD.md#bactorseamlesstraveled)

#### Defined in

[ue/ue.d.ts:13139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13139)

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bAllowReceiveTickEventOnDedicatedServer](ue_ue.DebugCameraHUD.md#ballowreceivetickeventondedicatedserver)

#### Defined in

[ue/ue.d.ts:13142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13142)

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bAllowTickBeforeBeginPlay](ue_ue.DebugCameraHUD.md#ballowtickbeforebeginplay)

#### Defined in

[ue/ue.d.ts:13129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13129)

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bAlwaysRelevant](ue_ue.DebugCameraHUD.md#balwaysrelevant)

#### Defined in

[ue/ue.d.ts:13120](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13120)

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bAutoDestroyWhenFinished](ue_ue.DebugCameraHUD.md#bautodestroywhenfinished)

#### Defined in

[ue/ue.d.ts:13130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13130)

___

### bBlockInput

• **bBlockInput**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bBlockInput](ue_ue.DebugCameraHUD.md#bblockinput)

#### Defined in

[ue/ue.d.ts:13131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13131)

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bCanBeDamaged](ue_ue.DebugCameraHUD.md#bcanbedamaged)

#### Defined in

[ue/ue.d.ts:13132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13132)

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bCanBeInCluster](ue_ue.DebugCameraHUD.md#bcanbeincluster)

#### Defined in

[ue/ue.d.ts:13141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13141)

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bCollideWhenPlacing](ue_ue.DebugCameraHUD.md#bcollidewhenplacing)

#### Defined in

[ue/ue.d.ts:13133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13133)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bEditable](ue_ue.DebugCameraHUD.md#beditable)

#### Defined in

[ue/ue.d.ts:13184](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13184)

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bEnableAutoLODGeneration](ue_ue.DebugCameraHUD.md#benableautolodgeneration)

#### Defined in

[ue/ue.d.ts:13137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13137)

___

### bEnableDebugTextShadow

• **bEnableDebugTextShadow**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bEnableDebugTextShadow](ue_ue.DebugCameraHUD.md#benabledebugtextshadow)

#### Defined in

[ue/ue.d.ts:6176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6176)

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bExchangedRoles](ue_ue.DebugCameraHUD.md#bexchangedroles)

#### Defined in

[ue/ue.d.ts:13123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13123)

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bFindCameraComponentWhenViewTarget](ue_ue.DebugCameraHUD.md#bfindcameracomponentwhenviewtarget)

#### Defined in

[ue/ue.d.ts:13134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13134)

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bGenerateOverlapEventsDuringLevelStreaming](ue_ue.DebugCameraHUD.md#bgenerateoverlapeventsduringlevelstreaming)

#### Defined in

[ue/ue.d.ts:13135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13135)

___

### bHidden

• **bHidden**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bHidden](ue_ue.DebugCameraHUD.md#bhidden)

#### Defined in

[ue/ue.d.ts:13116](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13116)

___

### bHiddenEd

• **bHiddenEd**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bHiddenEd](ue_ue.DebugCameraHUD.md#bhiddened)

#### Defined in

[ue/ue.d.ts:13178](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13178)

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bHiddenEdLayer](ue_ue.DebugCameraHUD.md#bhiddenedlayer)

#### Defined in

[ue/ue.d.ts:13180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13180)

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bHiddenEdLevel](ue_ue.DebugCameraHUD.md#bhiddenedlevel)

#### Defined in

[ue/ue.d.ts:13181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13181)

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bHiddenEdTemporary](ue_ue.DebugCameraHUD.md#bhiddenedtemporary)

#### Defined in

[ue/ue.d.ts:13187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13187)

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bIgnoresOriginShifting](ue_ue.DebugCameraHUD.md#bignoresoriginshifting)

#### Defined in

[ue/ue.d.ts:13136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13136)

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bIsEditorOnlyActor](ue_ue.DebugCameraHUD.md#biseditoronlyactor)

#### Defined in

[ue/ue.d.ts:13138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13138)

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bIsEditorPreviewActor](ue_ue.DebugCameraHUD.md#biseditorpreviewactor)

#### Defined in

[ue/ue.d.ts:13179](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13179)

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bListedInSceneOutliner](ue_ue.DebugCameraHUD.md#blistedinsceneoutliner)

#### Defined in

[ue/ue.d.ts:13185](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13185)

___

### bLockLocation

• **bLockLocation**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bLockLocation](ue_ue.DebugCameraHUD.md#blocklocation)

#### Defined in

[ue/ue.d.ts:13182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13182)

___

### bLostFocusPaused

• **bLostFocusPaused**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bLostFocusPaused](ue_ue.DebugCameraHUD.md#blostfocuspaused)

#### Defined in

[ue/ue.d.ts:6170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6170)

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bNetLoadOnClient](ue_ue.DebugCameraHUD.md#bnetloadonclient)

#### Defined in

[ue/ue.d.ts:13124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13124)

___

### bNetStartup

• **bNetStartup**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bNetStartup](ue_ue.DebugCameraHUD.md#bnetstartup)

#### Defined in

[ue/ue.d.ts:13118](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13118)

___

### bNetTemporary

• **bNetTemporary**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bNetTemporary](ue_ue.DebugCameraHUD.md#bnettemporary)

#### Defined in

[ue/ue.d.ts:13117](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13117)

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bNetUseOwnerRelevancy](ue_ue.DebugCameraHUD.md#bnetuseownerrelevancy)

#### Defined in

[ue/ue.d.ts:13125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13125)

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bOnlyRelevantToOwner](ue_ue.DebugCameraHUD.md#bonlyrelevanttoowner)

#### Defined in

[ue/ue.d.ts:13119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13119)

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bOptimizeBPComponentData](ue_ue.DebugCameraHUD.md#boptimizebpcomponentdata)

#### Defined in

[ue/ue.d.ts:13186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13186)

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bRelevantForLevelBounds](ue_ue.DebugCameraHUD.md#brelevantforlevelbounds)

#### Defined in

[ue/ue.d.ts:13127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13127)

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bRelevantForNetworkReplays](ue_ue.DebugCameraHUD.md#brelevantfornetworkreplays)

#### Defined in

[ue/ue.d.ts:13126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13126)

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bReplayRewindable](ue_ue.DebugCameraHUD.md#breplayrewindable)

#### Defined in

[ue/ue.d.ts:13128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13128)

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bReplicateMovement](ue_ue.DebugCameraHUD.md#breplicatemovement)

#### Defined in

[ue/ue.d.ts:13121](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13121)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bReplicates](ue_ue.DebugCameraHUD.md#breplicates)

#### Defined in

[ue/ue.d.ts:13140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13140)

___

### bShowDebugInfo

• **bShowDebugInfo**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bShowDebugInfo](ue_ue.DebugCameraHUD.md#bshowdebuginfo)

#### Defined in

[ue/ue.d.ts:6172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6172)

___

### bShowHUD

• **bShowHUD**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bShowHUD](ue_ue.DebugCameraHUD.md#bshowhud)

#### Defined in

[ue/ue.d.ts:6171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6171)

___

### bShowHitBoxDebugInfo

• **bShowHitBoxDebugInfo**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bShowHitBoxDebugInfo](ue_ue.DebugCameraHUD.md#bshowhitboxdebuginfo)

#### Defined in

[ue/ue.d.ts:6174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6174)

___

### bShowOverlays

• **bShowOverlays**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bShowOverlays](ue_ue.DebugCameraHUD.md#bshowoverlays)

#### Defined in

[ue/ue.d.ts:6175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6175)

___

### bTearOff

• **bTearOff**: `boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[bTearOff](ue_ue.DebugCameraHUD.md#btearoff)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ActorHasTag](ue_ue.DebugCameraHUD.md#actorhastag)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[AddComponent](ue_ue.DebugCameraHUD.md#addcomponent)

#### Defined in

[ue/ue.d.ts:13208](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13208)

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

#### Defined in

[ue/ue.d.ts:6185](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6185)

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

#### Defined in

[ue/ue.d.ts:6186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6186)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[AddTickPrerequisiteComponent](ue_ue.DebugCameraHUD.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:13210](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13210)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:6187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6187)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[DisableInput](ue_ue.DebugCameraHUD.md#disableinput)

#### Defined in

[ue/ue.d.ts:13212](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13212)

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

#### Defined in

[ue/ue.d.ts:6188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6188)

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

#### Defined in

[ue/ue.d.ts:6189](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6189)

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

#### Defined in

[ue/ue.d.ts:6190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6190)

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

#### Defined in

[ue/ue.d.ts:6191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6191)

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

#### Defined in

[ue/ue.d.ts:6192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6192)

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

#### Defined in

[ue/ue.d.ts:6193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6193)

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

#### Defined in

[ue/ue.d.ts:6194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6194)

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

#### Defined in

[ue/ue.d.ts:6195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6195)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ExecuteUbergraph](ue_ue.DebugCameraHUD.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[FlushNetDormancy](ue_ue.DebugCameraHUD.md#flushnetdormancy)

#### Defined in

[ue/ue.d.ts:13214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13214)

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ForceNetUpdate](ue_ue.DebugCameraHUD.md#forcenetupdate)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorBounds](ue_ue.DebugCameraHUD.md#getactorbounds)

#### Defined in

[ue/ue.d.ts:13216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13216)

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorEnableCollision](ue_ue.DebugCameraHUD.md#getactorenablecollision)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorEyesViewPoint](ue_ue.DebugCameraHUD.md#getactoreyesviewpoint)

#### Defined in

[ue/ue.d.ts:13218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13218)

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorForwardVector](ue_ue.DebugCameraHUD.md#getactorforwardvector)

#### Defined in

[ue/ue.d.ts:13219](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13219)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorLabel](ue_ue.DebugCameraHUD.md#getactorlabel)

#### Defined in

[ue/ue.d.ts:13220](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13220)

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorRelativeScale3D](ue_ue.DebugCameraHUD.md#getactorrelativescale3d)

#### Defined in

[ue/ue.d.ts:13221](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13221)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorRightVector](ue_ue.DebugCameraHUD.md#getactorrightvector)

#### Defined in

[ue/ue.d.ts:13222](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13222)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorScale3D](ue_ue.DebugCameraHUD.md#getactorscale3d)

#### Defined in

[ue/ue.d.ts:13223](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13223)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorTickInterval](ue_ue.DebugCameraHUD.md#getactortickinterval)

#### Defined in

[ue/ue.d.ts:13224](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13224)

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorTimeDilation](ue_ue.DebugCameraHUD.md#getactortimedilation)

#### Defined in

[ue/ue.d.ts:13225](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13225)

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetActorUpVector](ue_ue.DebugCameraHUD.md#getactorupvector)

#### Defined in

[ue/ue.d.ts:13226](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13226)

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

#### Defined in

[ue/ue.d.ts:6196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6196)

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

#### Defined in

[ue/ue.d.ts:13227](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13227)

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetAttachParentActor](ue_ue.DebugCameraHUD.md#getattachparentactor)

#### Defined in

[ue/ue.d.ts:13229](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13229)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetAttachParentSocketName](ue_ue.DebugCameraHUD.md#getattachparentsocketname)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetAttachedActors](ue_ue.DebugCameraHUD.md#getattachedactors)

#### Defined in

[ue/ue.d.ts:13228](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13228)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetClass](ue_ue.DebugCameraHUD.md#getclass)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetComponentByClass](ue_ue.DebugCameraHUD.md#getcomponentbyclass)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetComponentsByInterface](ue_ue.DebugCameraHUD.md#getcomponentsbyinterface)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetComponentsByTag](ue_ue.DebugCameraHUD.md#getcomponentsbytag)

#### Defined in

[ue/ue.d.ts:13233](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13233)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetDotProductTo](ue_ue.DebugCameraHUD.md#getdotproductto)

#### Defined in

[ue/ue.d.ts:13235](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13235)

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetFolderPath](ue_ue.DebugCameraHUD.md#getfolderpath)

#### Defined in

[ue/ue.d.ts:13236](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13236)

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetGameTimeSinceCreation](ue_ue.DebugCameraHUD.md#getgametimesincecreation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetHorizontalDistanceTo](ue_ue.DebugCameraHUD.md#gethorizontaldistanceto)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetHorizontalDotProductTo](ue_ue.DebugCameraHUD.md#gethorizontaldotproductto)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetInputAxisKeyValue](ue_ue.DebugCameraHUD.md#getinputaxiskeyvalue)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetInputAxisValue](ue_ue.DebugCameraHUD.md#getinputaxisvalue)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetInputVectorAxisValue](ue_ue.DebugCameraHUD.md#getinputvectoraxisvalue)

#### Defined in

[ue/ue.d.ts:13242](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13242)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetInstigator](ue_ue.DebugCameraHUD.md#getinstigator)

#### Defined in

[ue/ue.d.ts:13243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13243)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetInstigatorController](ue_ue.DebugCameraHUD.md#getinstigatorcontroller)

#### Defined in

[ue/ue.d.ts:13244](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13244)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetLifeSpan](ue_ue.DebugCameraHUD.md#getlifespan)

#### Defined in

[ue/ue.d.ts:13245](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13245)

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetLocalRole](ue_ue.DebugCameraHUD.md#getlocalrole)

#### Defined in

[ue/ue.d.ts:13246](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13246)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetName](ue_ue.DebugCameraHUD.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetOuter](ue_ue.DebugCameraHUD.md#getouter)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetOverlappingActors](ue_ue.DebugCameraHUD.md#getoverlappingactors)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetOverlappingComponents](ue_ue.DebugCameraHUD.md#getoverlappingcomponents)

#### Defined in

[ue/ue.d.ts:13248](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13248)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetOwner](ue_ue.DebugCameraHUD.md#getowner)

#### Defined in

[ue/ue.d.ts:13249](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13249)

___

### GetOwningPawn

▸ **GetOwningPawn**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetOwningPawn](ue_ue.DebugCameraHUD.md#getowningpawn)

#### Defined in

[ue/ue.d.ts:6197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6197)

___

### GetOwningPlayerController

▸ **GetOwningPlayerController**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetOwningPlayerController](ue_ue.DebugCameraHUD.md#getowningplayercontroller)

#### Defined in

[ue/ue.d.ts:6198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6198)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetParentActor](ue_ue.DebugCameraHUD.md#getparentactor)

#### Defined in

[ue/ue.d.ts:13250](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13250)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetParentComponent](ue_ue.DebugCameraHUD.md#getparentcomponent)

#### Defined in

[ue/ue.d.ts:13251](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13251)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetRemoteRole](ue_ue.DebugCameraHUD.md#getremoterole)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetSquaredDistanceTo](ue_ue.DebugCameraHUD.md#getsquareddistanceto)

#### Defined in

[ue/ue.d.ts:13253](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13253)

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

#### Defined in

[ue/ue.d.ts:6199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6199)

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetTickableWhenPaused](ue_ue.DebugCameraHUD.md#gettickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13254](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13254)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetTransform](ue_ue.DebugCameraHUD.md#gettransform)

#### Defined in

[ue/ue.d.ts:13255](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13255)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetVelocity](ue_ue.DebugCameraHUD.md#getvelocity)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetVerticalDistanceTo](ue_ue.DebugCameraHUD.md#getverticaldistanceto)

#### Defined in

[ue/ue.d.ts:13257](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13257)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[GetWorld](ue_ue.DebugCameraHUD.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[HasAuthority](ue_ue.DebugCameraHUD.md#hasauthority)

#### Defined in

[ue/ue.d.ts:13258](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13258)

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsActorBeingDestroyed](ue_ue.DebugCameraHUD.md#isactorbeingdestroyed)

#### Defined in

[ue/ue.d.ts:13259](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13259)

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsActorTickEnabled](ue_ue.DebugCameraHUD.md#isactortickenabled)

#### Defined in

[ue/ue.d.ts:13260](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13260)

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsChildActor](ue_ue.DebugCameraHUD.md#ischildactor)

#### Defined in

[ue/ue.d.ts:13261](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13261)

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsEditable](ue_ue.DebugCameraHUD.md#iseditable)

#### Defined in

[ue/ue.d.ts:13262](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13262)

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsHiddenEd](ue_ue.DebugCameraHUD.md#ishiddened)

#### Defined in

[ue/ue.d.ts:13263](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13263)

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsHiddenEdAtStartup](ue_ue.DebugCameraHUD.md#ishiddenedatstartup)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsOverlappingActor](ue_ue.DebugCameraHUD.md#isoverlappingactor)

#### Defined in

[ue/ue.d.ts:13265](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13265)

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsSelectable](ue_ue.DebugCameraHUD.md#isselectable)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[IsTemporarilyHiddenInEditor](ue_ue.DebugCameraHUD.md#istemporarilyhiddenineditor)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AddActorLocalOffset](ue_ue.DebugCameraHUD.md#k2_addactorlocaloffset)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AddActorLocalRotation](ue_ue.DebugCameraHUD.md#k2_addactorlocalrotation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AddActorLocalTransform](ue_ue.DebugCameraHUD.md#k2_addactorlocaltransform)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AddActorWorldOffset](ue_ue.DebugCameraHUD.md#k2_addactorworldoffset)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AddActorWorldRotation](ue_ue.DebugCameraHUD.md#k2_addactorworldrotation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AddActorWorldTransform](ue_ue.DebugCameraHUD.md#k2_addactorworldtransform)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AttachRootComponentTo](ue_ue.DebugCameraHUD.md#k2_attachrootcomponentto)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AttachRootComponentToActor](ue_ue.DebugCameraHUD.md#k2_attachrootcomponenttoactor)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AttachToActor](ue_ue.DebugCameraHUD.md#k2_attachtoactor)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_AttachToComponent](ue_ue.DebugCameraHUD.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:13277](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13277)

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_DestroyActor](ue_ue.DebugCameraHUD.md#k2_destroyactor)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_DestroyComponent](ue_ue.DebugCameraHUD.md#k2_destroycomponent)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_DetachFromActor](ue_ue.DebugCameraHUD.md#k2_detachfromactor)

#### Defined in

[ue/ue.d.ts:13280](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13280)

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_GetActorLocation](ue_ue.DebugCameraHUD.md#k2_getactorlocation)

#### Defined in

[ue/ue.d.ts:13281](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13281)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_GetActorRotation](ue_ue.DebugCameraHUD.md#k2_getactorrotation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_GetComponentsByClass](ue_ue.DebugCameraHUD.md#k2_getcomponentsbyclass)

#### Defined in

[ue/ue.d.ts:13283](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13283)

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_GetRootComponent](ue_ue.DebugCameraHUD.md#k2_getrootcomponent)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_OnBecomeViewTarget](ue_ue.DebugCameraHUD.md#k2_onbecomeviewtarget)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_OnEndViewTarget](ue_ue.DebugCameraHUD.md#k2_onendviewtarget)

#### Defined in

[ue/ue.d.ts:13286](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13286)

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_OnReset](ue_ue.DebugCameraHUD.md#k2_onreset)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_SetActorLocation](ue_ue.DebugCameraHUD.md#k2_setactorlocation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_SetActorLocationAndRotation](ue_ue.DebugCameraHUD.md#k2_setactorlocationandrotation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_SetActorRelativeLocation](ue_ue.DebugCameraHUD.md#k2_setactorrelativelocation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_SetActorRelativeRotation](ue_ue.DebugCameraHUD.md#k2_setactorrelativerotation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_SetActorRelativeTransform](ue_ue.DebugCameraHUD.md#k2_setactorrelativetransform)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_SetActorRotation](ue_ue.DebugCameraHUD.md#k2_setactorrotation)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_SetActorTransform](ue_ue.DebugCameraHUD.md#k2_setactortransform)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[K2_TeleportTo](ue_ue.DebugCameraHUD.md#k2_teleportto)

#### Defined in

[ue/ue.d.ts:13295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13295)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[MakeNoise](ue_ue.DebugCameraHUD.md#makenoise)

#### Defined in

[ue/ue.d.ts:13297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13297)

___

### NextDebugTarget

▸ **NextDebugTarget**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[NextDebugTarget](ue_ue.DebugCameraHUD.md#nextdebugtarget)

#### Defined in

[ue/ue.d.ts:6200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6200)

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnRep_AttachmentReplication](ue_ue.DebugCameraHUD.md#onrep_attachmentreplication)

#### Defined in

[ue/ue.d.ts:13298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13298)

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnRep_Instigator](ue_ue.DebugCameraHUD.md#onrep_instigator)

#### Defined in

[ue/ue.d.ts:13299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13299)

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnRep_Owner](ue_ue.DebugCameraHUD.md#onrep_owner)

#### Defined in

[ue/ue.d.ts:13300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13300)

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnRep_ReplicateMovement](ue_ue.DebugCameraHUD.md#onrep_replicatemovement)

#### Defined in

[ue/ue.d.ts:13302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13302)

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[OnRep_ReplicatedMovement](ue_ue.DebugCameraHUD.md#onrep_replicatedmovement)

#### Defined in

[ue/ue.d.ts:13301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13301)

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

#### Defined in

[ue/ue.d.ts:13303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13303)

___

### PreviousDebugTarget

▸ **PreviousDebugTarget**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[PreviousDebugTarget](ue_ue.DebugCameraHUD.md#previousdebugtarget)

#### Defined in

[ue/ue.d.ts:6201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6201)

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

#### Defined in

[ue/ue.d.ts:6202](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6202)

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorBeginCursorOver](ue_ue.DebugCameraHUD.md#receiveactorbegincursorover)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorBeginOverlap](ue_ue.DebugCameraHUD.md#receiveactorbeginoverlap)

#### Defined in

[ue/ue.d.ts:13305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13305)

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorEndCursorOver](ue_ue.DebugCameraHUD.md#receiveactorendcursorover)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorEndOverlap](ue_ue.DebugCameraHUD.md#receiveactorendoverlap)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorOnClicked](ue_ue.DebugCameraHUD.md#receiveactoronclicked)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorOnInputTouchBegin](ue_ue.DebugCameraHUD.md#receiveactoroninputtouchbegin)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorOnInputTouchEnd](ue_ue.DebugCameraHUD.md#receiveactoroninputtouchend)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorOnInputTouchEnter](ue_ue.DebugCameraHUD.md#receiveactoroninputtouchenter)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorOnInputTouchLeave](ue_ue.DebugCameraHUD.md#receiveactoroninputtouchleave)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveActorOnReleased](ue_ue.DebugCameraHUD.md#receiveactoronreleased)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveAnyDamage](ue_ue.DebugCameraHUD.md#receiveanydamage)

#### Defined in

[ue/ue.d.ts:13314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13314)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveBeginPlay](ue_ue.DebugCameraHUD.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:13315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13315)

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveDestroyed](ue_ue.DebugCameraHUD.md#receivedestroyed)

#### Defined in

[ue/ue.d.ts:13316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13316)

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

#### Defined in

[ue/ue.d.ts:6203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6203)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveHit](ue_ue.DebugCameraHUD.md#receivehit)

#### Defined in

[ue/ue.d.ts:13318](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13318)

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

#### Defined in

[ue/ue.d.ts:6204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6204)

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

#### Defined in

[ue/ue.d.ts:6205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6205)

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

#### Defined in

[ue/ue.d.ts:6206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6206)

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

#### Defined in

[ue/ue.d.ts:6207](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6207)

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

#### Defined in

[ue/ue.d.ts:13319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13319)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ReceiveTick](ue_ue.DebugCameraHUD.md#receivetick)

#### Defined in

[ue/ue.d.ts:13321](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13321)

___

### RemoveAllDebugStrings

▸ **RemoveAllDebugStrings**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[RemoveAllDebugStrings](ue_ue.DebugCameraHUD.md#removealldebugstrings)

#### Defined in

[ue/ue.d.ts:6208](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6208)

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

#### Defined in

[ue/ue.d.ts:6209](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6209)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[RemoveTickPrerequisiteComponent](ue_ue.DebugCameraHUD.md#removetickprerequisitecomponent)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetActorEnableCollision](ue_ue.DebugCameraHUD.md#setactorenablecollision)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetActorHiddenInGame](ue_ue.DebugCameraHUD.md#setactorhiddeningame)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetActorLabel](ue_ue.DebugCameraHUD.md#setactorlabel)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetActorRelativeScale3D](ue_ue.DebugCameraHUD.md#setactorrelativescale3d)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetActorScale3D](ue_ue.DebugCameraHUD.md#setactorscale3d)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetActorTickEnabled](ue_ue.DebugCameraHUD.md#setactortickenabled)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetActorTickInterval](ue_ue.DebugCameraHUD.md#setactortickinterval)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetFolderPath](ue_ue.DebugCameraHUD.md#setfolderpath)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetIsTemporarilyHiddenInEditor](ue_ue.DebugCameraHUD.md#setistemporarilyhiddenineditor)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetLifeSpan](ue_ue.DebugCameraHUD.md#setlifespan)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetNetDormancy](ue_ue.DebugCameraHUD.md#setnetdormancy)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetOwner](ue_ue.DebugCameraHUD.md#setowner)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetReplicateMovement](ue_ue.DebugCameraHUD.md#setreplicatemovement)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetReplicates](ue_ue.DebugCameraHUD.md#setreplicates)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetTickGroup](ue_ue.DebugCameraHUD.md#settickgroup)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[SetTickableWhenPaused](ue_ue.DebugCameraHUD.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:13338](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13338)

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

#### Defined in

[ue/ue.d.ts:6210](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6210)

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

#### Defined in

[ue/ue.d.ts:6211](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6211)

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

#### Defined in

[ue/ue.d.ts:6212](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6212)

___

### ShowHUD

▸ **ShowHUD**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[ShowHUD](ue_ue.DebugCameraHUD.md#showhud)

#### Defined in

[ue/ue.d.ts:6213](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6213)

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

#### Defined in

[ue/ue.d.ts:13340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13340)

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[TearOff](ue_ue.DebugCameraHUD.md#tearoff)

#### Defined in

[ue/ue.d.ts:13341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13341)

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

#### Inherited from

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[UserConstructionScript](ue_ue.DebugCameraHUD.md#userconstructionscript)

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

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[WasRecentlyRendered](ue_ue.DebugCameraHUD.md#wasrecentlyrendered)

#### Defined in

[ue/ue.d.ts:13343](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13343)

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

#### Defined in

[ue/ue.d.ts:65322](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65322)

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

#### Defined in

[ue/ue.d.ts:65323](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65323)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DebugCameraHUD](ue_ue.DebugCameraHUD.md).[StaticClass](ue_ue.DebugCameraHUD.md#staticclass)

#### Defined in

[ue/ue.d.ts:65321](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65321)
