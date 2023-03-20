[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Actor

# Class: Actor

[ue/ue](../modules/ue_ue.md).Actor

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`Actor`**

  ↳↳ [`Info`](ue_ue.Info.md)

  ↳↳ [`HUD`](ue_ue.HUD.md)

  ↳↳ [`Emitter`](ue_ue.Emitter.md)

  ↳↳ [`CameraActor`](ue_ue.CameraActor.md)

  ↳↳ [`PlayerCameraManager`](ue_ue.PlayerCameraManager.md)

  ↳↳ [`LevelScriptActor`](ue_ue.LevelScriptActor.md)

  ↳↳ [`NavigationObjectBase`](ue_ue.NavigationObjectBase.md)

  ↳↳ [`ParticleEventManager`](ue_ue.ParticleEventManager.md)

  ↳↳ [`Controller`](ue_ue.Controller.md)

  ↳↳ [`Pawn`](ue_ue.Pawn.md)

  ↳↳ [`Brush`](ue_ue.Brush.md)

  ↳↳ [`MatineeActor`](ue_ue.MatineeActor.md)

  ↳↳ [`NavigationData`](ue_ue.NavigationData.md)

  ↳↳ [`BaseTransformGizmo`](ue_ue.BaseTransformGizmo.md)

  ↳↳ [`AmbientSound`](ue_ue.AmbientSound.md)

  ↳↳ [`AnimationEditorPreviewActor`](ue_ue.AnimationEditorPreviewActor.md)

  ↳↳ [`SkeletalMeshActor`](ue_ue.SkeletalMeshActor.md)

  ↳↳ [`AROriginActor`](ue_ue.AROriginActor.md)

  ↳↳ [`LevelSequenceActor`](ue_ue.LevelSequenceActor.md)

  ↳↳ [`BandwidthTestActor`](ue_ue.BandwidthTestActor.md)

  ↳↳ [`ReflectionCapture`](ue_ue.ReflectionCapture.md)

  ↳↳ [`Light`](ue_ue.Light.md)

  ↳↳ [`BP_Sky_Sphere_C`](ue_ue.Engine.EngineSky.BP_Sky_Sphere.BP_Sky_Sphere_C.md)

  ↳↳ [`CableActor`](ue_ue.CableActor.md)

  ↳↳ [`CameraRig_Crane`](ue_ue.CameraRig_Crane.md)

  ↳↳ [`CameraRig_Rail`](ue_ue.CameraRig_Rail.md)

  ↳↳ [`ChaosSolverActor`](ue_ue.ChaosSolverActor.md)

  ↳↳ [`FieldSystemActor`](ue_ue.FieldSystemActor.md)

  ↳↳ [`GeometryCollectionDebugDrawActor`](ue_ue.GeometryCollectionDebugDrawActor.md)

  ↳↳ [`GeometryCollectionRenderLevelSetActor`](ue_ue.GeometryCollectionRenderLevelSetActor.md)

  ↳↳ [`GeometryCollectionActor`](ue_ue.GeometryCollectionActor.md)

  ↳↳ [`ControlPointMeshActor`](ue_ue.ControlPointMeshActor.md)

  ↳↳ [`DatasmithAreaLightActor`](ue_ue.DatasmithAreaLightActor.md)

  ↳↳ [`DatasmithImportedSequencesActor`](ue_ue.DatasmithImportedSequencesActor.md)

  ↳↳ [`DatasmithSceneActor`](ue_ue.DatasmithSceneActor.md)

  ↳↳ [`DecalActor`](ue_ue.DecalActor.md)

  ↳↳ [`DocumentationActor`](ue_ue.DocumentationActor.md)

  ↳↳ [`EditorUtilityActor`](ue_ue.EditorUtilityActor.md)

  ↳↳ [`FloatingText`](ue_ue.FloatingText.md)

  ↳↳ [`FunctionalTest`](ue_ue.FunctionalTest.md)

  ↳↳ [`GameplayDebuggerCategoryReplicator`](ue_ue.GameplayDebuggerCategoryReplicator.md)

  ↳↳ [`GameplayDebuggerPlayerManager`](ue_ue.GameplayDebuggerPlayerManager.md)

  ↳↳ [`GeometryCacheActor`](ue_ue.GeometryCacheActor.md)

  ↳↳ [`InternalToolFrameworkActor`](ue_ue.InternalToolFrameworkActor.md)

  ↳↳ [`GroupActor`](ue_ue.GroupActor.md)

  ↳↳ [`LODActor`](ue_ue.LODActor.md)

  ↳↳ [`InstancedFoliageActor`](ue_ue.InstancedFoliageActor.md)

  ↳↳ [`StaticMeshActor`](ue_ue.StaticMeshActor.md)

  ↳↳ [`LandscapeProxy`](ue_ue.LandscapeProxy.md)

  ↳↳ [`LandscapeBlueprintBrushBase`](ue_ue.LandscapeBlueprintBrushBase.md)

  ↳↳ [`LandscapeGizmoActor`](ue_ue.LandscapeGizmoActor.md)

  ↳↳ [`LandscapeMeshProxyActor`](ue_ue.LandscapeMeshProxyActor.md)

  ↳↳ [`LandscapePlaceholder`](ue_ue.LandscapePlaceholder.md)

  ↳↳ [`LevelBounds`](ue_ue.LevelBounds.md)

  ↳↳ [`LevelVariantSetsActor`](ue_ue.LevelVariantSetsActor.md)

  ↳↳ [`LightmassPortal`](ue_ue.LightmassPortal.md)

  ↳↳ [`MainActor`](ue_ue.MainActor.md)

  ↳↳ [`Manipulator`](ue_ue.Manipulator.md)

  ↳↳ [`MaterialInstanceActor`](ue_ue.MaterialInstanceActor.md)

  ↳↳ [`NavigationGraphNode`](ue_ue.NavigationGraphNode.md)

  ↳↳ [`NavigationTestingActor`](ue_ue.NavigationTestingActor.md)

  ↳↳ [`NavLinkProxy`](ue_ue.NavLinkProxy.md)

  ↳↳ [`NavSystemConfigOverride`](ue_ue.NavSystemConfigOverride.md)

  ↳↳ [`Note`](ue_ue.Note.md)

  ↳↳ [`NUTActor`](ue_ue.NUTActor.md)

  ↳↳ [`SceneCapture`](ue_ue.SceneCapture.md)

  ↳↳ [`OculusMR_BoundaryActor`](ue_ue.OculusMR_BoundaryActor.md)

  ↳↳ [`OnlineBeacon`](ue_ue.OnlineBeacon.md)

  ↳↳ [`OnlineBeaconHostObject`](ue_ue.OnlineBeaconHostObject.md)

  ↳↳ [`PaperFlipbookActor`](ue_ue.PaperFlipbookActor.md)

  ↳↳ [`PaperGroupedSpriteActor`](ue_ue.PaperGroupedSpriteActor.md)

  ↳↳ [`PaperSpriteActor`](ue_ue.PaperSpriteActor.md)

  ↳↳ [`PaperTerrainActor`](ue_ue.PaperTerrainActor.md)

  ↳↳ [`PaperTileMapActor`](ue_ue.PaperTileMapActor.md)

  ↳↳ [`PhasedAutomationActorBase`](ue_ue.PhasedAutomationActorBase.md)

  ↳↳ [`RigidBodyBase`](ue_ue.RigidBodyBase.md)

  ↳↳ [`PlacedEditorUtilityBase`](ue_ue.PlacedEditorUtilityBase.md)

  ↳↳ [`RuntimeVirtualTextureVolume`](ue_ue.RuntimeVirtualTextureVolume.md)

  ↳↳ [`SequenceRecorderGroup`](ue_ue.SequenceRecorderGroup.md)

  ↳↳ [`SequencerKeyActor`](ue_ue.SequencerKeyActor.md)

  ↳↳ [`SequencerMeshTrail`](ue_ue.SequencerMeshTrail.md)

  ↳↳ [`SplineMeshActor`](ue_ue.SplineMeshActor.md)

  ↳↳ [`SwitchActor`](ue_ue.SwitchActor.md)

  ↳↳ [`TargetPoint`](ue_ue.TargetPoint.md)

  ↳↳ [`TestBaseCls`](ue_ue.TestBaseCls.md)

  ↳↳ [`TextRenderActor`](ue_ue.TextRenderActor.md)

  ↳↳ [`TriggerBase`](ue_ue.TriggerBase.md)

  ↳↳ [`VariantManagerTestActor`](ue_ue.VariantManagerTestActor.md)

  ↳↳ [`VectorFieldVolume`](ue_ue.VectorFieldVolume.md)

  ↳↳ [`VisualLoggerRenderingActor`](ue_ue.VisualLoggerRenderingActor.md)

  ↳↳ [`VREditorAvatarActor`](ue_ue.VREditorAvatarActor.md)

  ↳↳ [`VREditorBaseActor`](ue_ue.VREditorBaseActor.md)

  ↳↳ [`VREditorTeleporter`](ue_ue.VREditorTeleporter.md)

  ↳↳ [`Animal_C`](ue_ue_bp.Game.Blueprints.TypeScript.Animal.Animal_C.md)

  ↳↳ [`MyTestActor_C`](ue_ue_bp.Game.Blueprints.TypeScript.MyTestActor.MyTestActor_C.md)

  ↳↳ [`TsTestActor_C`](ue_ue_bp.Game.Blueprints.TypeScript.TsTestActor.TsTestActor_C.md)

  ↳↳ [`AnotherActor_C`](ue_ue_bp.Game.Blueprints.TypeScript.Modules.AnotherActor.AnotherActor_C.md)

  ↳↳ [`MixinSuperTestBase_C`](ue_ue_bp.Game.StarterContent.MixinSuperTestBase.MixinSuperTestBase_C.md)

  ↳↳ [`MixinTest_C`](ue_ue_bp.Game.StarterContent.MixinTest.MixinTest_C.md)

  ↳↳ [`TestBlueprint_C`](ue_ue_bp.Game.StarterContent.TestBlueprint.TestBlueprint_C.md)

## Table of contents

### Constructors

- [constructor](ue_ue.Actor.md#constructor)

### Properties

- [ActorLabel](ue_ue.Actor.md#actorlabel)
- [AttachmentReplication](ue_ue.Actor.md#attachmentreplication)
- [AutoReceiveInput](ue_ue.Actor.md#autoreceiveinput)
- [BlueprintCreatedComponents](ue_ue.Actor.md#blueprintcreatedcomponents)
- [Children](ue_ue.Actor.md#children)
- [ControllingMatineeActors](ue_ue.Actor.md#controllingmatineeactors)
- [CustomTimeDilation](ue_ue.Actor.md#customtimedilation)
- [DefaultUpdateOverlapsMethodDuringLevelStreaming](ue_ue.Actor.md#defaultupdateoverlapsmethodduringlevelstreaming)
- [FolderPath](ue_ue.Actor.md#folderpath)
- [GroupActor](ue_ue.Actor.md#groupactor)
- [HiddenEditorViews](ue_ue.Actor.md#hiddeneditorviews)
- [InitialLifeSpan](ue_ue.Actor.md#initiallifespan)
- [InputComponent](ue_ue.Actor.md#inputcomponent)
- [InputPriority](ue_ue.Actor.md#inputpriority)
- [InstanceComponents](ue_ue.Actor.md#instancecomponents)
- [Instigator](ue_ue.Actor.md#instigator)
- [Layers](ue_ue.Actor.md#layers)
- [MinNetUpdateFrequency](ue_ue.Actor.md#minnetupdatefrequency)
- [NetCullDistanceSquared](ue_ue.Actor.md#netculldistancesquared)
- [NetDormancy](ue_ue.Actor.md#netdormancy)
- [NetDriverName](ue_ue.Actor.md#netdrivername)
- [NetPriority](ue_ue.Actor.md#netpriority)
- [NetTag](ue_ue.Actor.md#nettag)
- [NetUpdateFrequency](ue_ue.Actor.md#netupdatefrequency)
- [OnActorBeginOverlap](ue_ue.Actor.md#onactorbeginoverlap)
- [OnActorEndOverlap](ue_ue.Actor.md#onactorendoverlap)
- [OnActorHit](ue_ue.Actor.md#onactorhit)
- [OnBeginCursorOver](ue_ue.Actor.md#onbegincursorover)
- [OnClicked](ue_ue.Actor.md#onclicked)
- [OnDestroyed](ue_ue.Actor.md#ondestroyed)
- [OnEndCursorOver](ue_ue.Actor.md#onendcursorover)
- [OnEndPlay](ue_ue.Actor.md#onendplay)
- [OnInputTouchBegin](ue_ue.Actor.md#oninputtouchbegin)
- [OnInputTouchEnd](ue_ue.Actor.md#oninputtouchend)
- [OnInputTouchEnter](ue_ue.Actor.md#oninputtouchenter)
- [OnInputTouchLeave](ue_ue.Actor.md#oninputtouchleave)
- [OnReleased](ue_ue.Actor.md#onreleased)
- [OnTakeAnyDamage](ue_ue.Actor.md#ontakeanydamage)
- [OnTakePointDamage](ue_ue.Actor.md#ontakepointdamage)
- [OnTakeRadialDamage](ue_ue.Actor.md#ontakeradialdamage)
- [Owner](ue_ue.Actor.md#owner)
- [ParentComponent](ue_ue.Actor.md#parentcomponent)
- [ParentComponentActor](ue_ue.Actor.md#parentcomponentactor)
- [PivotOffset](ue_ue.Actor.md#pivotoffset)
- [PrimaryActorTick](ue_ue.Actor.md#primaryactortick)
- [RemoteRole](ue_ue.Actor.md#remoterole)
- [ReplicatedMovement](ue_ue.Actor.md#replicatedmovement)
- [Role](ue_ue.Actor.md#role)
- [RootComponent](ue_ue.Actor.md#rootcomponent)
- [SpawnCollisionHandlingMethod](ue_ue.Actor.md#spawncollisionhandlingmethod)
- [SpriteScale](ue_ue.Actor.md#spritescale)
- [Tags](ue_ue.Actor.md#tags)
- [UpdateOverlapsMethodDuringLevelStreaming](ue_ue.Actor.md#updateoverlapsmethodduringlevelstreaming)
- [\_\_tid\_Actor\_\_](ue_ue.Actor.md#__tid_actor__)
- [\_\_tid\_Object\_\_](ue_ue.Actor.md#__tid_object__)
- [bActorEnableCollision](ue_ue.Actor.md#bactorenablecollision)
- [bActorIsBeingDestroyed](ue_ue.Actor.md#bactorisbeingdestroyed)
- [bActorLabelEditable](ue_ue.Actor.md#bactorlabeleditable)
- [bActorSeamlessTraveled](ue_ue.Actor.md#bactorseamlesstraveled)
- [bAllowReceiveTickEventOnDedicatedServer](ue_ue.Actor.md#ballowreceivetickeventondedicatedserver)
- [bAllowTickBeforeBeginPlay](ue_ue.Actor.md#ballowtickbeforebeginplay)
- [bAlwaysRelevant](ue_ue.Actor.md#balwaysrelevant)
- [bAutoDestroyWhenFinished](ue_ue.Actor.md#bautodestroywhenfinished)
- [bBlockInput](ue_ue.Actor.md#bblockinput)
- [bCanBeDamaged](ue_ue.Actor.md#bcanbedamaged)
- [bCanBeInCluster](ue_ue.Actor.md#bcanbeincluster)
- [bCollideWhenPlacing](ue_ue.Actor.md#bcollidewhenplacing)
- [bEditable](ue_ue.Actor.md#beditable)
- [bEnableAutoLODGeneration](ue_ue.Actor.md#benableautolodgeneration)
- [bExchangedRoles](ue_ue.Actor.md#bexchangedroles)
- [bFindCameraComponentWhenViewTarget](ue_ue.Actor.md#bfindcameracomponentwhenviewtarget)
- [bGenerateOverlapEventsDuringLevelStreaming](ue_ue.Actor.md#bgenerateoverlapeventsduringlevelstreaming)
- [bHidden](ue_ue.Actor.md#bhidden)
- [bHiddenEd](ue_ue.Actor.md#bhiddened)
- [bHiddenEdLayer](ue_ue.Actor.md#bhiddenedlayer)
- [bHiddenEdLevel](ue_ue.Actor.md#bhiddenedlevel)
- [bHiddenEdTemporary](ue_ue.Actor.md#bhiddenedtemporary)
- [bIgnoresOriginShifting](ue_ue.Actor.md#bignoresoriginshifting)
- [bIsEditorOnlyActor](ue_ue.Actor.md#biseditoronlyactor)
- [bIsEditorPreviewActor](ue_ue.Actor.md#biseditorpreviewactor)
- [bListedInSceneOutliner](ue_ue.Actor.md#blistedinsceneoutliner)
- [bLockLocation](ue_ue.Actor.md#blocklocation)
- [bNetLoadOnClient](ue_ue.Actor.md#bnetloadonclient)
- [bNetStartup](ue_ue.Actor.md#bnetstartup)
- [bNetTemporary](ue_ue.Actor.md#bnettemporary)
- [bNetUseOwnerRelevancy](ue_ue.Actor.md#bnetuseownerrelevancy)
- [bOnlyRelevantToOwner](ue_ue.Actor.md#bonlyrelevanttoowner)
- [bOptimizeBPComponentData](ue_ue.Actor.md#boptimizebpcomponentdata)
- [bRelevantForLevelBounds](ue_ue.Actor.md#brelevantforlevelbounds)
- [bRelevantForNetworkReplays](ue_ue.Actor.md#brelevantfornetworkreplays)
- [bReplayRewindable](ue_ue.Actor.md#breplayrewindable)
- [bReplicateMovement](ue_ue.Actor.md#breplicatemovement)
- [bReplicates](ue_ue.Actor.md#breplicates)
- [bTearOff](ue_ue.Actor.md#btearoff)

### Methods

- [ActorHasTag](ue_ue.Actor.md#actorhastag)
- [AddComponent](ue_ue.Actor.md#addcomponent)
- [AddTickPrerequisiteActor](ue_ue.Actor.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.Actor.md#addtickprerequisitecomponent)
- [CreateDefaultSubobject](ue_ue.Actor.md#createdefaultsubobject)
- [DetachRootComponentFromParent](ue_ue.Actor.md#detachrootcomponentfromparent)
- [DisableInput](ue_ue.Actor.md#disableinput)
- [EnableInput](ue_ue.Actor.md#enableinput)
- [ExecuteUbergraph](ue_ue.Actor.md#executeubergraph)
- [FlushNetDormancy](ue_ue.Actor.md#flushnetdormancy)
- [ForceNetUpdate](ue_ue.Actor.md#forcenetupdate)
- [GetActorBounds](ue_ue.Actor.md#getactorbounds)
- [GetActorEnableCollision](ue_ue.Actor.md#getactorenablecollision)
- [GetActorEyesViewPoint](ue_ue.Actor.md#getactoreyesviewpoint)
- [GetActorForwardVector](ue_ue.Actor.md#getactorforwardvector)
- [GetActorLabel](ue_ue.Actor.md#getactorlabel)
- [GetActorRelativeScale3D](ue_ue.Actor.md#getactorrelativescale3d)
- [GetActorRightVector](ue_ue.Actor.md#getactorrightvector)
- [GetActorScale3D](ue_ue.Actor.md#getactorscale3d)
- [GetActorTickInterval](ue_ue.Actor.md#getactortickinterval)
- [GetActorTimeDilation](ue_ue.Actor.md#getactortimedilation)
- [GetActorUpVector](ue_ue.Actor.md#getactorupvector)
- [GetAllChildActors](ue_ue.Actor.md#getallchildactors)
- [GetAttachParentActor](ue_ue.Actor.md#getattachparentactor)
- [GetAttachParentSocketName](ue_ue.Actor.md#getattachparentsocketname)
- [GetAttachedActors](ue_ue.Actor.md#getattachedactors)
- [GetClass](ue_ue.Actor.md#getclass)
- [GetComponentByClass](ue_ue.Actor.md#getcomponentbyclass)
- [GetComponentsByInterface](ue_ue.Actor.md#getcomponentsbyinterface)
- [GetComponentsByTag](ue_ue.Actor.md#getcomponentsbytag)
- [GetDistanceTo](ue_ue.Actor.md#getdistanceto)
- [GetDotProductTo](ue_ue.Actor.md#getdotproductto)
- [GetFolderPath](ue_ue.Actor.md#getfolderpath)
- [GetGameTimeSinceCreation](ue_ue.Actor.md#getgametimesincecreation)
- [GetHorizontalDistanceTo](ue_ue.Actor.md#gethorizontaldistanceto)
- [GetHorizontalDotProductTo](ue_ue.Actor.md#gethorizontaldotproductto)
- [GetInputAxisKeyValue](ue_ue.Actor.md#getinputaxiskeyvalue)
- [GetInputAxisValue](ue_ue.Actor.md#getinputaxisvalue)
- [GetInputVectorAxisValue](ue_ue.Actor.md#getinputvectoraxisvalue)
- [GetInstigator](ue_ue.Actor.md#getinstigator)
- [GetInstigatorController](ue_ue.Actor.md#getinstigatorcontroller)
- [GetLifeSpan](ue_ue.Actor.md#getlifespan)
- [GetLocalRole](ue_ue.Actor.md#getlocalrole)
- [GetName](ue_ue.Actor.md#getname)
- [GetOuter](ue_ue.Actor.md#getouter)
- [GetOverlappingActors](ue_ue.Actor.md#getoverlappingactors)
- [GetOverlappingComponents](ue_ue.Actor.md#getoverlappingcomponents)
- [GetOwner](ue_ue.Actor.md#getowner)
- [GetParentActor](ue_ue.Actor.md#getparentactor)
- [GetParentComponent](ue_ue.Actor.md#getparentcomponent)
- [GetRemoteRole](ue_ue.Actor.md#getremoterole)
- [GetSquaredDistanceTo](ue_ue.Actor.md#getsquareddistanceto)
- [GetTickableWhenPaused](ue_ue.Actor.md#gettickablewhenpaused)
- [GetTransform](ue_ue.Actor.md#gettransform)
- [GetVelocity](ue_ue.Actor.md#getvelocity)
- [GetVerticalDistanceTo](ue_ue.Actor.md#getverticaldistanceto)
- [GetWorld](ue_ue.Actor.md#getworld)
- [HasAuthority](ue_ue.Actor.md#hasauthority)
- [IsActorBeingDestroyed](ue_ue.Actor.md#isactorbeingdestroyed)
- [IsActorTickEnabled](ue_ue.Actor.md#isactortickenabled)
- [IsChildActor](ue_ue.Actor.md#ischildactor)
- [IsEditable](ue_ue.Actor.md#iseditable)
- [IsHiddenEd](ue_ue.Actor.md#ishiddened)
- [IsHiddenEdAtStartup](ue_ue.Actor.md#ishiddenedatstartup)
- [IsOverlappingActor](ue_ue.Actor.md#isoverlappingactor)
- [IsSelectable](ue_ue.Actor.md#isselectable)
- [IsTemporarilyHiddenInEditor](ue_ue.Actor.md#istemporarilyhiddenineditor)
- [K2\_AddActorLocalOffset](ue_ue.Actor.md#k2_addactorlocaloffset)
- [K2\_AddActorLocalRotation](ue_ue.Actor.md#k2_addactorlocalrotation)
- [K2\_AddActorLocalTransform](ue_ue.Actor.md#k2_addactorlocaltransform)
- [K2\_AddActorWorldOffset](ue_ue.Actor.md#k2_addactorworldoffset)
- [K2\_AddActorWorldRotation](ue_ue.Actor.md#k2_addactorworldrotation)
- [K2\_AddActorWorldTransform](ue_ue.Actor.md#k2_addactorworldtransform)
- [K2\_AttachRootComponentTo](ue_ue.Actor.md#k2_attachrootcomponentto)
- [K2\_AttachRootComponentToActor](ue_ue.Actor.md#k2_attachrootcomponenttoactor)
- [K2\_AttachToActor](ue_ue.Actor.md#k2_attachtoactor)
- [K2\_AttachToComponent](ue_ue.Actor.md#k2_attachtocomponent)
- [K2\_DestroyActor](ue_ue.Actor.md#k2_destroyactor)
- [K2\_DestroyComponent](ue_ue.Actor.md#k2_destroycomponent)
- [K2\_DetachFromActor](ue_ue.Actor.md#k2_detachfromactor)
- [K2\_GetActorLocation](ue_ue.Actor.md#k2_getactorlocation)
- [K2\_GetActorRotation](ue_ue.Actor.md#k2_getactorrotation)
- [K2\_GetComponentsByClass](ue_ue.Actor.md#k2_getcomponentsbyclass)
- [K2\_GetRootComponent](ue_ue.Actor.md#k2_getrootcomponent)
- [K2\_OnBecomeViewTarget](ue_ue.Actor.md#k2_onbecomeviewtarget)
- [K2\_OnEndViewTarget](ue_ue.Actor.md#k2_onendviewtarget)
- [K2\_OnReset](ue_ue.Actor.md#k2_onreset)
- [K2\_SetActorLocation](ue_ue.Actor.md#k2_setactorlocation)
- [K2\_SetActorLocationAndRotation](ue_ue.Actor.md#k2_setactorlocationandrotation)
- [K2\_SetActorRelativeLocation](ue_ue.Actor.md#k2_setactorrelativelocation)
- [K2\_SetActorRelativeRotation](ue_ue.Actor.md#k2_setactorrelativerotation)
- [K2\_SetActorRelativeTransform](ue_ue.Actor.md#k2_setactorrelativetransform)
- [K2\_SetActorRotation](ue_ue.Actor.md#k2_setactorrotation)
- [K2\_SetActorTransform](ue_ue.Actor.md#k2_setactortransform)
- [K2\_TeleportTo](ue_ue.Actor.md#k2_teleportto)
- [MakeMIDForMaterial](ue_ue.Actor.md#makemidformaterial)
- [MakeNoise](ue_ue.Actor.md#makenoise)
- [OnRep\_AttachmentReplication](ue_ue.Actor.md#onrep_attachmentreplication)
- [OnRep\_Instigator](ue_ue.Actor.md#onrep_instigator)
- [OnRep\_Owner](ue_ue.Actor.md#onrep_owner)
- [OnRep\_ReplicateMovement](ue_ue.Actor.md#onrep_replicatemovement)
- [OnRep\_ReplicatedMovement](ue_ue.Actor.md#onrep_replicatedmovement)
- [PrestreamTextures](ue_ue.Actor.md#prestreamtextures)
- [ReceiveActorBeginCursorOver](ue_ue.Actor.md#receiveactorbegincursorover)
- [ReceiveActorBeginOverlap](ue_ue.Actor.md#receiveactorbeginoverlap)
- [ReceiveActorEndCursorOver](ue_ue.Actor.md#receiveactorendcursorover)
- [ReceiveActorEndOverlap](ue_ue.Actor.md#receiveactorendoverlap)
- [ReceiveActorOnClicked](ue_ue.Actor.md#receiveactoronclicked)
- [ReceiveActorOnInputTouchBegin](ue_ue.Actor.md#receiveactoroninputtouchbegin)
- [ReceiveActorOnInputTouchEnd](ue_ue.Actor.md#receiveactoroninputtouchend)
- [ReceiveActorOnInputTouchEnter](ue_ue.Actor.md#receiveactoroninputtouchenter)
- [ReceiveActorOnInputTouchLeave](ue_ue.Actor.md#receiveactoroninputtouchleave)
- [ReceiveActorOnReleased](ue_ue.Actor.md#receiveactoronreleased)
- [ReceiveAnyDamage](ue_ue.Actor.md#receiveanydamage)
- [ReceiveBeginPlay](ue_ue.Actor.md#receivebeginplay)
- [ReceiveDestroyed](ue_ue.Actor.md#receivedestroyed)
- [ReceiveEndPlay](ue_ue.Actor.md#receiveendplay)
- [ReceiveHit](ue_ue.Actor.md#receivehit)
- [ReceivePointDamage](ue_ue.Actor.md#receivepointdamage)
- [ReceiveRadialDamage](ue_ue.Actor.md#receiveradialdamage)
- [ReceiveTick](ue_ue.Actor.md#receivetick)
- [RemoveTickPrerequisiteActor](ue_ue.Actor.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.Actor.md#removetickprerequisitecomponent)
- [SetActorEnableCollision](ue_ue.Actor.md#setactorenablecollision)
- [SetActorHiddenInGame](ue_ue.Actor.md#setactorhiddeningame)
- [SetActorLabel](ue_ue.Actor.md#setactorlabel)
- [SetActorRelativeScale3D](ue_ue.Actor.md#setactorrelativescale3d)
- [SetActorScale3D](ue_ue.Actor.md#setactorscale3d)
- [SetActorTickEnabled](ue_ue.Actor.md#setactortickenabled)
- [SetActorTickInterval](ue_ue.Actor.md#setactortickinterval)
- [SetFolderPath](ue_ue.Actor.md#setfolderpath)
- [SetIsTemporarilyHiddenInEditor](ue_ue.Actor.md#setistemporarilyhiddenineditor)
- [SetLifeSpan](ue_ue.Actor.md#setlifespan)
- [SetNetDormancy](ue_ue.Actor.md#setnetdormancy)
- [SetOwner](ue_ue.Actor.md#setowner)
- [SetReplicateMovement](ue_ue.Actor.md#setreplicatemovement)
- [SetReplicates](ue_ue.Actor.md#setreplicates)
- [SetTickGroup](ue_ue.Actor.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.Actor.md#settickablewhenpaused)
- [SnapRootComponentTo](ue_ue.Actor.md#snaprootcomponentto)
- [TearOff](ue_ue.Actor.md#tearoff)
- [UserConstructionScript](ue_ue.Actor.md#userconstructionscript)
- [WasRecentlyRendered](ue_ue.Actor.md#wasrecentlyrendered)
- [Find](ue_ue.Actor.md#find)
- [Load](ue_ue.Actor.md#load)
- [StaticClass](ue_ue.Actor.md#staticclass)

## Constructors

### constructor

• **new Actor**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ActorLabel

• **ActorLabel**: `string`

___

### AttachmentReplication

• **AttachmentReplication**: [`RepAttachment`](ue_ue.RepAttachment.md)

___

### AutoReceiveInput

• **AutoReceiveInput**: [`EAutoReceiveInput`](../enums/ue_ue.EAutoReceiveInput.md)

___

### BlueprintCreatedComponents

• **BlueprintCreatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

___

### Children

• **Children**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

___

### ControllingMatineeActors

• **ControllingMatineeActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MatineeActor`](ue_ue.MatineeActor.md)\>

___

### CustomTimeDilation

• **CustomTimeDilation**: `number`

___

### DefaultUpdateOverlapsMethodDuringLevelStreaming

• **DefaultUpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

___

### FolderPath

• **FolderPath**: `string`

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

___

### InitialLifeSpan

• **InitialLifeSpan**: `number`

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

___

### InputPriority

• **InputPriority**: `number`

___

### InstanceComponents

• **InstanceComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

___

### Instigator

• **Instigator**: [`Pawn`](ue_ue.Pawn.md)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### MinNetUpdateFrequency

• **MinNetUpdateFrequency**: `number`

___

### NetCullDistanceSquared

• **NetCullDistanceSquared**: `number`

___

### NetDormancy

• **NetDormancy**: [`ENetDormancy`](../enums/ue_ue.ENetDormancy.md)

___

### NetDriverName

• **NetDriverName**: `string`

___

### NetPriority

• **NetPriority**: `number`

___

### NetTag

• **NetTag**: `number`

___

### NetUpdateFrequency

• **NetUpdateFrequency**: `number`

___

### OnActorBeginOverlap

• **OnActorBeginOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

___

### OnActorEndOverlap

• **OnActorEndOverlap**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OverlappedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

___

### OnActorHit

• **OnActorHit**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SelfActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `OtherActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `NormalImpulse`: [`Vector`](ue_ue_s.Vector.md), `Hit`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

___

### OnBeginCursorOver

• **OnBeginCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

___

### OnClicked

• **OnClicked**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonPressed`: [`Key`](ue_ue.Key.md)) => `void`\>

___

### OnDestroyed

• **OnDestroyed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DestroyedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

___

### OnEndCursorOver

• **OnEndCursorOver**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

___

### OnEndPlay

• **OnEndPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `EndPlayReason`: [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md)) => `void`\>

___

### OnInputTouchBegin

• **OnInputTouchBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

___

### OnInputTouchEnd

• **OnInputTouchEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

___

### OnInputTouchEnter

• **OnInputTouchEnter**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

___

### OnInputTouchLeave

• **OnInputTouchLeave**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FingerIndex`: [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md), `TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

___

### OnReleased

• **OnReleased**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TouchedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `ButtonReleased`: [`Key`](ue_ue.Key.md)) => `void`\>

___

### OnTakeAnyDamage

• **OnTakeAnyDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

___

### OnTakePointDamage

• **OnTakePointDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `HitLocation`: [`Vector`](ue_ue_s.Vector.md), `FHitComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>, `BoneName`: `string`, `ShotFromDirection`: [`Vector`](ue_ue_s.Vector.md), `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

___

### OnTakeRadialDamage

• **OnTakeRadialDamage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`DamagedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Damage`: `number`, `DamageType`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DamageType`](ue_ue.DamageType.md)\>, `Origin`: [`Vector`](ue_ue_s.Vector.md), `HitInfo`: [`HitResult`](ue_ue.HitResult.md), `InstigatedBy`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\>, `DamageCauser`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

___

### Owner

• **Owner**: [`Actor`](ue_ue.Actor.md)

___

### ParentComponent

• **ParentComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`ChildActorComponent`](ue_ue.ChildActorComponent.md)\>

___

### ParentComponentActor

• **ParentComponentActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

___

### PivotOffset

• **PivotOffset**: [`Vector`](ue_ue_s.Vector.md)

___

### PrimaryActorTick

• **PrimaryActorTick**: [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

___

### RemoteRole

• **RemoteRole**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

___

### ReplicatedMovement

• **ReplicatedMovement**: [`RepMovement`](ue_ue.RepMovement.md)

___

### Role

• **Role**: [`ENetRole`](../enums/ue_ue.ENetRole.md)

___

### RootComponent

• **RootComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

___

### SpawnCollisionHandlingMethod

• **SpawnCollisionHandlingMethod**: [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md)

___

### SpriteScale

• **SpriteScale**: `number`

___

### Tags

• **Tags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### UpdateOverlapsMethodDuringLevelStreaming

• **UpdateOverlapsMethodDuringLevelStreaming**: [`EActorUpdateOverlapsMethod`](../enums/ue_ue.EActorUpdateOverlapsMethod.md)

___

### \_\_tid\_Actor\_\_

• **\_\_tid\_Actor\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bActorEnableCollision

• **bActorEnableCollision**: `boolean`

___

### bActorIsBeingDestroyed

• **bActorIsBeingDestroyed**: `boolean`

___

### bActorLabelEditable

• **bActorLabelEditable**: `boolean`

___

### bActorSeamlessTraveled

• **bActorSeamlessTraveled**: `boolean`

___

### bAllowReceiveTickEventOnDedicatedServer

• **bAllowReceiveTickEventOnDedicatedServer**: `boolean`

___

### bAllowTickBeforeBeginPlay

• **bAllowTickBeforeBeginPlay**: `boolean`

___

### bAlwaysRelevant

• **bAlwaysRelevant**: `boolean`

___

### bAutoDestroyWhenFinished

• **bAutoDestroyWhenFinished**: `boolean`

___

### bBlockInput

• **bBlockInput**: `boolean`

___

### bCanBeDamaged

• **bCanBeDamaged**: `boolean`

___

### bCanBeInCluster

• **bCanBeInCluster**: `boolean`

___

### bCollideWhenPlacing

• **bCollideWhenPlacing**: `boolean`

___

### bEditable

• **bEditable**: `boolean`

___

### bEnableAutoLODGeneration

• **bEnableAutoLODGeneration**: `boolean`

___

### bExchangedRoles

• **bExchangedRoles**: `boolean`

___

### bFindCameraComponentWhenViewTarget

• **bFindCameraComponentWhenViewTarget**: `boolean`

___

### bGenerateOverlapEventsDuringLevelStreaming

• **bGenerateOverlapEventsDuringLevelStreaming**: `boolean`

___

### bHidden

• **bHidden**: `boolean`

___

### bHiddenEd

• **bHiddenEd**: `boolean`

___

### bHiddenEdLayer

• **bHiddenEdLayer**: `boolean`

___

### bHiddenEdLevel

• **bHiddenEdLevel**: `boolean`

___

### bHiddenEdTemporary

• **bHiddenEdTemporary**: `boolean`

___

### bIgnoresOriginShifting

• **bIgnoresOriginShifting**: `boolean`

___

### bIsEditorOnlyActor

• **bIsEditorOnlyActor**: `boolean`

___

### bIsEditorPreviewActor

• **bIsEditorPreviewActor**: `boolean`

___

### bListedInSceneOutliner

• **bListedInSceneOutliner**: `boolean`

___

### bLockLocation

• **bLockLocation**: `boolean`

___

### bNetLoadOnClient

• **bNetLoadOnClient**: `boolean`

___

### bNetStartup

• **bNetStartup**: `boolean`

___

### bNetTemporary

• **bNetTemporary**: `boolean`

___

### bNetUseOwnerRelevancy

• **bNetUseOwnerRelevancy**: `boolean`

___

### bOnlyRelevantToOwner

• **bOnlyRelevantToOwner**: `boolean`

___

### bOptimizeBPComponentData

• **bOptimizeBPComponentData**: `boolean`

___

### bRelevantForLevelBounds

• **bRelevantForLevelBounds**: `boolean`

___

### bRelevantForNetworkReplays

• **bRelevantForNetworkReplays**: `boolean`

___

### bReplayRewindable

• **bReplayRewindable**: `boolean`

___

### bReplicateMovement

• **bReplicateMovement**: `boolean`

___

### bReplicates

• **bReplicates**: `boolean`

___

### bTearOff

• **bTearOff**: `boolean`

## Methods

### ActorHasTag

▸ **ActorHasTag**(`Tag`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tag` | `string` |

#### Returns

`boolean`

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

___

### AddTickPrerequisiteActor

▸ **AddTickPrerequisiteActor**(`PrerequisiteActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### AddTickPrerequisiteComponent

▸ **AddTickPrerequisiteComponent**(`PrerequisiteComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\> |

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

___

### DetachRootComponentFromParent

▸ **DetachRootComponentFromParent**(`bMaintainWorldPosition?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bMaintainWorldPosition?` | `boolean` |

#### Returns

`void`

___

### DisableInput

▸ **DisableInput**(`PlayerController`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### FlushNetDormancy

▸ **FlushNetDormancy**(): `void`

#### Returns

`void`

___

### ForceNetUpdate

▸ **ForceNetUpdate**(): `void`

#### Returns

`void`

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

___

### GetActorEnableCollision

▸ **GetActorEnableCollision**(): `boolean`

#### Returns

`boolean`

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

___

### GetActorForwardVector

▸ **GetActorForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetActorLabel

▸ **GetActorLabel**(): `string`

#### Returns

`string`

___

### GetActorRelativeScale3D

▸ **GetActorRelativeScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetActorRightVector

▸ **GetActorRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetActorScale3D

▸ **GetActorScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetActorTickInterval

▸ **GetActorTickInterval**(): `number`

#### Returns

`number`

___

### GetActorTimeDilation

▸ **GetActorTimeDilation**(): `number`

#### Returns

`number`

___

### GetActorUpVector

▸ **GetActorUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

___

### GetAttachParentActor

▸ **GetAttachParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

___

### GetAttachParentSocketName

▸ **GetAttachParentSocketName**(): `string`

#### Returns

`string`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetComponentByClass

▸ **GetComponentByClass**(`ComponentClass`): [`ActorComponent`](ue_ue.ActorComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ComponentClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`ActorComponent`](ue_ue.ActorComponent.md)

___

### GetComponentsByInterface

▸ **GetComponentsByInterface**(`Interface`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Interface` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

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

___

### GetDistanceTo

▸ **GetDistanceTo**(`OtherActor`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`number`

___

### GetDotProductTo

▸ **GetDotProductTo**(`OtherActor`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`number`

___

### GetFolderPath

▸ **GetFolderPath**(): `string`

#### Returns

`string`

___

### GetGameTimeSinceCreation

▸ **GetGameTimeSinceCreation**(): `number`

#### Returns

`number`

___

### GetHorizontalDistanceTo

▸ **GetHorizontalDistanceTo**(`OtherActor`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`number`

___

### GetHorizontalDotProductTo

▸ **GetHorizontalDotProductTo**(`OtherActor`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`number`

___

### GetInputAxisKeyValue

▸ **GetInputAxisKeyValue**(`InputAxisKey`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InputAxisKey` | [`Key`](ue_ue.Key.md) |

#### Returns

`number`

___

### GetInputAxisValue

▸ **GetInputAxisValue**(`InputAxisName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InputAxisName` | `string` |

#### Returns

`number`

___

### GetInputVectorAxisValue

▸ **GetInputVectorAxisValue**(`InputAxisKey`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InputAxisKey` | [`Key`](ue_ue.Key.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetInstigator

▸ **GetInstigator**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

___

### GetInstigatorController

▸ **GetInstigatorController**(): [`Controller`](ue_ue.Controller.md)

#### Returns

[`Controller`](ue_ue.Controller.md)

___

### GetLifeSpan

▸ **GetLifeSpan**(): `number`

#### Returns

`number`

___

### GetLocalRole

▸ **GetLocalRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

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

___

### GetOverlappingComponents

▸ **GetOverlappingComponents**(`OverlappingComponents`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OverlappingComponents` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>\> |

#### Returns

`void`

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

___

### GetParentActor

▸ **GetParentActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

___

### GetParentComponent

▸ **GetParentComponent**(): [`ChildActorComponent`](ue_ue.ChildActorComponent.md)

#### Returns

[`ChildActorComponent`](ue_ue.ChildActorComponent.md)

___

### GetRemoteRole

▸ **GetRemoteRole**(): [`ENetRole`](../enums/ue_ue.ENetRole.md)

#### Returns

[`ENetRole`](../enums/ue_ue.ENetRole.md)

___

### GetSquaredDistanceTo

▸ **GetSquaredDistanceTo**(`OtherActor`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`number`

___

### GetTickableWhenPaused

▸ **GetTickableWhenPaused**(): `boolean`

#### Returns

`boolean`

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

___

### GetVelocity

▸ **GetVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetVerticalDistanceTo

▸ **GetVerticalDistanceTo**(`OtherActor`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`number`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### HasAuthority

▸ **HasAuthority**(): `boolean`

#### Returns

`boolean`

___

### IsActorBeingDestroyed

▸ **IsActorBeingDestroyed**(): `boolean`

#### Returns

`boolean`

___

### IsActorTickEnabled

▸ **IsActorTickEnabled**(): `boolean`

#### Returns

`boolean`

___

### IsChildActor

▸ **IsChildActor**(): `boolean`

#### Returns

`boolean`

___

### IsEditable

▸ **IsEditable**(): `boolean`

#### Returns

`boolean`

___

### IsHiddenEd

▸ **IsHiddenEd**(): `boolean`

#### Returns

`boolean`

___

### IsHiddenEdAtStartup

▸ **IsHiddenEdAtStartup**(): `boolean`

#### Returns

`boolean`

___

### IsOverlappingActor

▸ **IsOverlappingActor**(`Other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`boolean`

___

### IsSelectable

▸ **IsSelectable**(): `boolean`

#### Returns

`boolean`

___

### IsTemporarilyHiddenInEditor

▸ **IsTemporarilyHiddenInEditor**(`bIncludeParent?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIncludeParent?` | `boolean` |

#### Returns

`boolean`

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

___

### K2\_DestroyActor

▸ **K2_DestroyActor**(): `void`

#### Returns

`void`

___

### K2\_DestroyComponent

▸ **K2_DestroyComponent**(`Component`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Component` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\> |

#### Returns

`void`

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

___

### K2\_GetActorLocation

▸ **K2_GetActorLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### K2\_GetActorRotation

▸ **K2_GetActorRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### K2\_GetComponentsByClass

▸ **K2_GetComponentsByClass**(`ComponentClass`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ComponentClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

___

### K2\_GetRootComponent

▸ **K2_GetRootComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

___

### K2\_OnBecomeViewTarget

▸ **K2_OnBecomeViewTarget**(`PC`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PC` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

___

### K2\_OnEndViewTarget

▸ **K2_OnEndViewTarget**(`PC`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PC` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

___

### K2\_OnReset

▸ **K2_OnReset**(): `void`

#### Returns

`void`

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

___

### MakeMIDForMaterial

▸ **MakeMIDForMaterial**(`Parent`): [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Parent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |

#### Returns

[`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

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

___

### OnRep\_AttachmentReplication

▸ **OnRep_AttachmentReplication**(): `void`

#### Returns

`void`

___

### OnRep\_Instigator

▸ **OnRep_Instigator**(): `void`

#### Returns

`void`

___

### OnRep\_Owner

▸ **OnRep_Owner**(): `void`

#### Returns

`void`

___

### OnRep\_ReplicateMovement

▸ **OnRep_ReplicateMovement**(): `void`

#### Returns

`void`

___

### OnRep\_ReplicatedMovement

▸ **OnRep_ReplicatedMovement**(): `void`

#### Returns

`void`

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

___

### ReceiveActorBeginCursorOver

▸ **ReceiveActorBeginCursorOver**(): `void`

#### Returns

`void`

___

### ReceiveActorBeginOverlap

▸ **ReceiveActorBeginOverlap**(`OtherActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### ReceiveActorEndCursorOver

▸ **ReceiveActorEndCursorOver**(): `void`

#### Returns

`void`

___

### ReceiveActorEndOverlap

▸ **ReceiveActorEndOverlap**(`OtherActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### ReceiveActorOnClicked

▸ **ReceiveActorOnClicked**(`ButtonPressed`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ButtonPressed` | [`Key`](ue_ue.Key.md) |

#### Returns

`void`

___

### ReceiveActorOnInputTouchBegin

▸ **ReceiveActorOnInputTouchBegin**(`FingerIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FingerIndex` | [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md) |

#### Returns

`void`

___

### ReceiveActorOnInputTouchEnd

▸ **ReceiveActorOnInputTouchEnd**(`FingerIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FingerIndex` | [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md) |

#### Returns

`void`

___

### ReceiveActorOnInputTouchEnter

▸ **ReceiveActorOnInputTouchEnter**(`FingerIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FingerIndex` | [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md) |

#### Returns

`void`

___

### ReceiveActorOnInputTouchLeave

▸ **ReceiveActorOnInputTouchLeave**(`FingerIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FingerIndex` | [`ETouchIndex`](../enums/ue_ue.ETouchIndex.md) |

#### Returns

`void`

___

### ReceiveActorOnReleased

▸ **ReceiveActorOnReleased**(`ButtonReleased`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ButtonReleased` | [`Key`](ue_ue.Key.md) |

#### Returns

`void`

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

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

___

### ReceiveDestroyed

▸ **ReceiveDestroyed**(): `void`

#### Returns

`void`

___

### ReceiveEndPlay

▸ **ReceiveEndPlay**(`EndPlayReason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EndPlayReason` | [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md) |

#### Returns

`void`

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

___

### ReceiveTick

▸ **ReceiveTick**(`DeltaSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaSeconds` | `number` |

#### Returns

`void`

___

### RemoveTickPrerequisiteActor

▸ **RemoveTickPrerequisiteActor**(`PrerequisiteActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### RemoveTickPrerequisiteComponent

▸ **RemoveTickPrerequisiteComponent**(`PrerequisiteComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\> |

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

___

### SetActorHiddenInGame

▸ **SetActorHiddenInGame**(`bNewHidden`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewHidden` | `boolean` |

#### Returns

`void`

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

___

### SetActorRelativeScale3D

▸ **SetActorRelativeScale3D**(`NewRelativeScale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRelativeScale` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### SetActorScale3D

▸ **SetActorScale3D**(`NewScale3D`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScale3D` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### SetActorTickEnabled

▸ **SetActorTickEnabled**(`bEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnabled` | `boolean` |

#### Returns

`void`

___

### SetActorTickInterval

▸ **SetActorTickInterval**(`TickInterval`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TickInterval` | `number` |

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

___

### SetIsTemporarilyHiddenInEditor

▸ **SetIsTemporarilyHiddenInEditor**(`bIsHidden`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIsHidden` | `boolean` |

#### Returns

`void`

___

### SetLifeSpan

▸ **SetLifeSpan**(`InLifespan`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLifespan` | `number` |

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

___

### SetOwner

▸ **SetOwner**(`NewOwner`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

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

___

### SetReplicates

▸ **SetReplicates**(`bInReplicates`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInReplicates` | `boolean` |

#### Returns

`void`

___

### SetTickGroup

▸ **SetTickGroup**(`NewTickGroup`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTickGroup` | [`ETickingGroup`](../enums/ue_ue.ETickingGroup.md) |

#### Returns

`void`

___

### SetTickableWhenPaused

▸ **SetTickableWhenPaused**(`bTickableWhenPaused`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bTickableWhenPaused` | `boolean` |

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

___

### TearOff

▸ **TearOff**(): `void`

#### Returns

`void`

___

### UserConstructionScript

▸ **UserConstructionScript**(): `void`

#### Returns

`void`

___

### WasRecentlyRendered

▸ **WasRecentlyRendered**(`Tolerance?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance?` | `number` |

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
