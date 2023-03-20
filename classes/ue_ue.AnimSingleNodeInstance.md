[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimSingleNodeInstance

# Class: AnimSingleNodeInstance

[ue/ue](../modules/ue_ue.md).AnimSingleNodeInstance

## Hierarchy

- [`AnimInstance`](ue_ue.AnimInstance.md)

  ↳ **`AnimSingleNodeInstance`**

  ↳↳ [`AnimPreviewInstance`](ue_ue.AnimPreviewInstance.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimSingleNodeInstance.md#constructor)

### Properties

- [ActiveAnimNotifyState](ue_ue.AnimSingleNodeInstance.md#activeanimnotifystate)
- [CurrentAsset](ue_ue.AnimSingleNodeInstance.md#currentasset)
- [CurrentSkeleton](ue_ue.AnimSingleNodeInstance.md#currentskeleton)
- [DeltaTime](ue_ue.AnimSingleNodeInstance.md#deltatime)
- [NotifyQueue](ue_ue.AnimSingleNodeInstance.md#notifyqueue)
- [OnAllMontageInstancesEnded](ue_ue.AnimSingleNodeInstance.md#onallmontageinstancesended)
- [OnMontageBlendingOut](ue_ue.AnimSingleNodeInstance.md#onmontageblendingout)
- [OnMontageEnded](ue_ue.AnimSingleNodeInstance.md#onmontageended)
- [OnMontageStarted](ue_ue.AnimSingleNodeInstance.md#onmontagestarted)
- [PostCompileValidationClassName](ue_ue.AnimSingleNodeInstance.md#postcompilevalidationclassname)
- [PostEvaluateAnimEvent](ue_ue.AnimSingleNodeInstance.md#postevaluateanimevent)
- [RootMotionMode](ue_ue.AnimSingleNodeInstance.md#rootmotionmode)
- [\_\_tid\_AnimInstance\_\_](ue_ue.AnimSingleNodeInstance.md#__tid_animinstance__)
- [\_\_tid\_AnimSingleNodeInstance\_\_](ue_ue.AnimSingleNodeInstance.md#__tid_animsinglenodeinstance__)
- [\_\_tid\_Object\_\_](ue_ue.AnimSingleNodeInstance.md#__tid_object__)
- [bCanUseParallelUpdateAnimation](ue_ue.AnimSingleNodeInstance.md#bcanuseparallelupdateanimation)
- [bQueueMontageEvents](ue_ue.AnimSingleNodeInstance.md#bqueuemontageevents)
- [bRunUpdatesInWorkerThreads](ue_ue.AnimSingleNodeInstance.md#brunupdatesinworkerthreads)
- [bUseMultiThreadedAnimationUpdate](ue_ue.AnimSingleNodeInstance.md#busemultithreadedanimationupdate)
- [bUsingCopyPoseFromMesh](ue_ue.AnimSingleNodeInstance.md#busingcopyposefrommesh)
- [bWarnAboutBlueprintUsage](ue_ue.AnimSingleNodeInstance.md#bwarnaboutblueprintusage)

### Methods

- [BlueprintBeginPlay](ue_ue.AnimSingleNodeInstance.md#blueprintbeginplay)
- [BlueprintInitializeAnimation](ue_ue.AnimSingleNodeInstance.md#blueprintinitializeanimation)
- [BlueprintPostEvaluateAnimation](ue_ue.AnimSingleNodeInstance.md#blueprintpostevaluateanimation)
- [BlueprintUpdateAnimation](ue_ue.AnimSingleNodeInstance.md#blueprintupdateanimation)
- [CalculateDirection](ue_ue.AnimSingleNodeInstance.md#calculatedirection)
- [ClearMorphTargets](ue_ue.AnimSingleNodeInstance.md#clearmorphtargets)
- [CreateDefaultSubobject](ue_ue.AnimSingleNodeInstance.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimSingleNodeInstance.md#executeubergraph)
- [GetActiveCurveNames](ue_ue.AnimSingleNodeInstance.md#getactivecurvenames)
- [GetAllCurveNames](ue_ue.AnimSingleNodeInstance.md#getallcurvenames)
- [GetAnimationAsset](ue_ue.AnimSingleNodeInstance.md#getanimationasset)
- [GetClass](ue_ue.AnimSingleNodeInstance.md#getclass)
- [GetCurrentActiveMontage](ue_ue.AnimSingleNodeInstance.md#getcurrentactivemontage)
- [GetCurrentStateName](ue_ue.AnimSingleNodeInstance.md#getcurrentstatename)
- [GetCurveValue](ue_ue.AnimSingleNodeInstance.md#getcurvevalue)
- [GetInstanceAssetPlayerLength](ue_ue.AnimSingleNodeInstance.md#getinstanceassetplayerlength)
- [GetInstanceAssetPlayerTime](ue_ue.AnimSingleNodeInstance.md#getinstanceassetplayertime)
- [GetInstanceAssetPlayerTimeFraction](ue_ue.AnimSingleNodeInstance.md#getinstanceassetplayertimefraction)
- [GetInstanceAssetPlayerTimeFromEnd](ue_ue.AnimSingleNodeInstance.md#getinstanceassetplayertimefromend)
- [GetInstanceAssetPlayerTimeFromEndFraction](ue_ue.AnimSingleNodeInstance.md#getinstanceassetplayertimefromendfraction)
- [GetInstanceCurrentStateElapsedTime](ue_ue.AnimSingleNodeInstance.md#getinstancecurrentstateelapsedtime)
- [GetInstanceMachineWeight](ue_ue.AnimSingleNodeInstance.md#getinstancemachineweight)
- [GetInstanceStateWeight](ue_ue.AnimSingleNodeInstance.md#getinstancestateweight)
- [GetInstanceTransitionCrossfadeDuration](ue_ue.AnimSingleNodeInstance.md#getinstancetransitioncrossfadeduration)
- [GetInstanceTransitionTimeElapsed](ue_ue.AnimSingleNodeInstance.md#getinstancetransitiontimeelapsed)
- [GetInstanceTransitionTimeElapsedFraction](ue_ue.AnimSingleNodeInstance.md#getinstancetransitiontimeelapsedfraction)
- [GetLength](ue_ue.AnimSingleNodeInstance.md#getlength)
- [GetLinkedAnimGraphInstanceByTag](ue_ue.AnimSingleNodeInstance.md#getlinkedanimgraphinstancebytag)
- [GetLinkedAnimGraphInstancesByTag](ue_ue.AnimSingleNodeInstance.md#getlinkedanimgraphinstancesbytag)
- [GetLinkedAnimLayerInstanceByClass](ue_ue.AnimSingleNodeInstance.md#getlinkedanimlayerinstancebyclass)
- [GetLinkedAnimLayerInstanceByGroup](ue_ue.AnimSingleNodeInstance.md#getlinkedanimlayerinstancebygroup)
- [GetName](ue_ue.AnimSingleNodeInstance.md#getname)
- [GetOuter](ue_ue.AnimSingleNodeInstance.md#getouter)
- [GetOwningActor](ue_ue.AnimSingleNodeInstance.md#getowningactor)
- [GetOwningComponent](ue_ue.AnimSingleNodeInstance.md#getowningcomponent)
- [GetRelevantAnimLength](ue_ue.AnimSingleNodeInstance.md#getrelevantanimlength)
- [GetRelevantAnimTime](ue_ue.AnimSingleNodeInstance.md#getrelevantanimtime)
- [GetRelevantAnimTimeFraction](ue_ue.AnimSingleNodeInstance.md#getrelevantanimtimefraction)
- [GetRelevantAnimTimeRemaining](ue_ue.AnimSingleNodeInstance.md#getrelevantanimtimeremaining)
- [GetRelevantAnimTimeRemainingFraction](ue_ue.AnimSingleNodeInstance.md#getrelevantanimtimeremainingfraction)
- [GetSyncGroupPosition](ue_ue.AnimSingleNodeInstance.md#getsyncgroupposition)
- [GetTimeToClosestMarker](ue_ue.AnimSingleNodeInstance.md#gettimetoclosestmarker)
- [GetWorld](ue_ue.AnimSingleNodeInstance.md#getworld)
- [HasMarkerBeenHitThisFrame](ue_ue.AnimSingleNodeInstance.md#hasmarkerbeenhitthisframe)
- [IsAnyMontagePlaying](ue_ue.AnimSingleNodeInstance.md#isanymontageplaying)
- [IsPlayingSlotAnimation](ue_ue.AnimSingleNodeInstance.md#isplayingslotanimation)
- [IsSyncGroupBetweenMarkers](ue_ue.AnimSingleNodeInstance.md#issyncgroupbetweenmarkers)
- [LinkAnimClassLayers](ue_ue.AnimSingleNodeInstance.md#linkanimclasslayers)
- [LinkAnimGraphByTag](ue_ue.AnimSingleNodeInstance.md#linkanimgraphbytag)
- [LockAIResources](ue_ue.AnimSingleNodeInstance.md#lockairesources)
- [Montage\_GetBlendTime](ue_ue.AnimSingleNodeInstance.md#montage_getblendtime)
- [Montage\_GetCurrentSection](ue_ue.AnimSingleNodeInstance.md#montage_getcurrentsection)
- [Montage\_GetIsStopped](ue_ue.AnimSingleNodeInstance.md#montage_getisstopped)
- [Montage\_GetPlayRate](ue_ue.AnimSingleNodeInstance.md#montage_getplayrate)
- [Montage\_GetPosition](ue_ue.AnimSingleNodeInstance.md#montage_getposition)
- [Montage\_IsActive](ue_ue.AnimSingleNodeInstance.md#montage_isactive)
- [Montage\_IsPlaying](ue_ue.AnimSingleNodeInstance.md#montage_isplaying)
- [Montage\_JumpToSection](ue_ue.AnimSingleNodeInstance.md#montage_jumptosection)
- [Montage\_JumpToSectionsEnd](ue_ue.AnimSingleNodeInstance.md#montage_jumptosectionsend)
- [Montage\_Pause](ue_ue.AnimSingleNodeInstance.md#montage_pause)
- [Montage\_Play](ue_ue.AnimSingleNodeInstance.md#montage_play)
- [Montage\_Resume](ue_ue.AnimSingleNodeInstance.md#montage_resume)
- [Montage\_SetNextSection](ue_ue.AnimSingleNodeInstance.md#montage_setnextsection)
- [Montage\_SetPlayRate](ue_ue.AnimSingleNodeInstance.md#montage_setplayrate)
- [Montage\_SetPosition](ue_ue.AnimSingleNodeInstance.md#montage_setposition)
- [Montage\_Stop](ue_ue.AnimSingleNodeInstance.md#montage_stop)
- [PlayAnim](ue_ue.AnimSingleNodeInstance.md#playanim)
- [PlaySlotAnimation](ue_ue.AnimSingleNodeInstance.md#playslotanimation)
- [PlaySlotAnimationAsDynamicMontage](ue_ue.AnimSingleNodeInstance.md#playslotanimationasdynamicmontage)
- [ResetDynamics](ue_ue.AnimSingleNodeInstance.md#resetdynamics)
- [SavePoseSnapshot](ue_ue.AnimSingleNodeInstance.md#saveposesnapshot)
- [SetAnimationAsset](ue_ue.AnimSingleNodeInstance.md#setanimationasset)
- [SetBlendSpaceInput](ue_ue.AnimSingleNodeInstance.md#setblendspaceinput)
- [SetLooping](ue_ue.AnimSingleNodeInstance.md#setlooping)
- [SetMorphTarget](ue_ue.AnimSingleNodeInstance.md#setmorphtarget)
- [SetPlayRate](ue_ue.AnimSingleNodeInstance.md#setplayrate)
- [SetPlaying](ue_ue.AnimSingleNodeInstance.md#setplaying)
- [SetPosition](ue_ue.AnimSingleNodeInstance.md#setposition)
- [SetPositionWithPreviousTime](ue_ue.AnimSingleNodeInstance.md#setpositionwithprevioustime)
- [SetPreviewCurveOverride](ue_ue.AnimSingleNodeInstance.md#setpreviewcurveoverride)
- [SetReverse](ue_ue.AnimSingleNodeInstance.md#setreverse)
- [SetRootMotionMode](ue_ue.AnimSingleNodeInstance.md#setrootmotionmode)
- [SnapshotPose](ue_ue.AnimSingleNodeInstance.md#snapshotpose)
- [StopAnim](ue_ue.AnimSingleNodeInstance.md#stopanim)
- [StopSlotAnimation](ue_ue.AnimSingleNodeInstance.md#stopslotanimation)
- [TryGetPawnOwner](ue_ue.AnimSingleNodeInstance.md#trygetpawnowner)
- [UnlinkAnimClassLayers](ue_ue.AnimSingleNodeInstance.md#unlinkanimclasslayers)
- [UnlockAIResources](ue_ue.AnimSingleNodeInstance.md#unlockairesources)
- [Find](ue_ue.AnimSingleNodeInstance.md#find)
- [Load](ue_ue.AnimSingleNodeInstance.md#load)
- [StaticClass](ue_ue.AnimSingleNodeInstance.md#staticclass)

## Constructors

### constructor

• **new AnimSingleNodeInstance**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimInstance](ue_ue.AnimInstance.md).[constructor](ue_ue.AnimInstance.md#constructor)

#### Defined in

[ue/ue.d.ts:20263](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20263)

## Properties

### ActiveAnimNotifyState

• **ActiveAnimNotifyState**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)\>

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[ActiveAnimNotifyState](ue_ue.AnimInstance.md#activeanimnotifystate)

#### Defined in

[ue/ue.d.ts:5106](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5106)

___

### CurrentAsset

• **CurrentAsset**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Defined in

[ue/ue.d.ts:20264](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20264)

___

### CurrentSkeleton

• **CurrentSkeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[CurrentSkeleton](ue_ue.AnimInstance.md#currentskeleton)

#### Defined in

[ue/ue.d.ts:5091](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5091)

___

### DeltaTime

• **DeltaTime**: `number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[DeltaTime](ue_ue.AnimInstance.md#deltatime)

#### Defined in

[ue/ue.d.ts:5093](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5093)

___

### NotifyQueue

• **NotifyQueue**: [`AnimNotifyQueue`](ue_ue.AnimNotifyQueue.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[NotifyQueue](ue_ue.AnimInstance.md#notifyqueue)

#### Defined in

[ue/ue.d.ts:5105](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5105)

___

### OnAllMontageInstancesEnded

• **OnAllMontageInstancesEnded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[OnAllMontageInstancesEnded](ue_ue.AnimInstance.md#onallmontageinstancesended)

#### Defined in

[ue/ue.d.ts:5103](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5103)

___

### OnMontageBlendingOut

• **OnMontageBlendingOut**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>, `bInterrupted`: `boolean`) => `void`\>

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[OnMontageBlendingOut](ue_ue.AnimInstance.md#onmontageblendingout)

#### Defined in

[ue/ue.d.ts:5100](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5100)

___

### OnMontageEnded

• **OnMontageEnded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>, `bInterrupted`: `boolean`) => `void`\>

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[OnMontageEnded](ue_ue.AnimInstance.md#onmontageended)

#### Defined in

[ue/ue.d.ts:5102](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5102)

___

### OnMontageStarted

• **OnMontageStarted**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>) => `void`\>

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[OnMontageStarted](ue_ue.AnimInstance.md#onmontagestarted)

#### Defined in

[ue/ue.d.ts:5101](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5101)

___

### PostCompileValidationClassName

• **PostCompileValidationClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[PostCompileValidationClassName](ue_ue.AnimInstance.md#postcompilevalidationclassname)

#### Defined in

[ue/ue.d.ts:5104](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5104)

___

### PostEvaluateAnimEvent

• **PostEvaluateAnimEvent**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:20265](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20265)

___

### RootMotionMode

• **RootMotionMode**: [`ERootMotionMode`](../enums/ue_ue.ERootMotionMode.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[RootMotionMode](ue_ue.AnimInstance.md#rootmotionmode)

#### Defined in

[ue/ue.d.ts:5092](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5092)

___

### \_\_tid\_AnimInstance\_\_

• **\_\_tid\_AnimInstance\_\_**: `boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[__tid_AnimInstance__](ue_ue.AnimInstance.md#__tid_animinstance__)

#### Defined in

[ue/ue.d.ts:5180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5180)

___

### \_\_tid\_AnimSingleNodeInstance\_\_

• **\_\_tid\_AnimSingleNodeInstance\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:20283](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20283)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[__tid_Object__](ue_ue.AnimInstance.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bCanUseParallelUpdateAnimation

• **bCanUseParallelUpdateAnimation**: `boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[bCanUseParallelUpdateAnimation](ue_ue.AnimInstance.md#bcanuseparallelupdateanimation)

#### Defined in

[ue/ue.d.ts:5095](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5095)

___

### bQueueMontageEvents

• **bQueueMontageEvents**: `boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[bQueueMontageEvents](ue_ue.AnimInstance.md#bqueuemontageevents)

#### Defined in

[ue/ue.d.ts:5099](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5099)

___

### bRunUpdatesInWorkerThreads

• **bRunUpdatesInWorkerThreads**: `boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[bRunUpdatesInWorkerThreads](ue_ue.AnimInstance.md#brunupdatesinworkerthreads)

#### Defined in

[ue/ue.d.ts:5094](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5094)

___

### bUseMultiThreadedAnimationUpdate

• **bUseMultiThreadedAnimationUpdate**: `boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[bUseMultiThreadedAnimationUpdate](ue_ue.AnimInstance.md#busemultithreadedanimationupdate)

#### Defined in

[ue/ue.d.ts:5097](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5097)

___

### bUsingCopyPoseFromMesh

• **bUsingCopyPoseFromMesh**: `boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[bUsingCopyPoseFromMesh](ue_ue.AnimInstance.md#busingcopyposefrommesh)

#### Defined in

[ue/ue.d.ts:5098](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5098)

___

### bWarnAboutBlueprintUsage

• **bWarnAboutBlueprintUsage**: `boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[bWarnAboutBlueprintUsage](ue_ue.AnimInstance.md#bwarnaboutblueprintusage)

#### Defined in

[ue/ue.d.ts:5096](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5096)

## Methods

### BlueprintBeginPlay

▸ **BlueprintBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[BlueprintBeginPlay](ue_ue.AnimInstance.md#blueprintbeginplay)

#### Defined in

[ue/ue.d.ts:5107](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5107)

___

### BlueprintInitializeAnimation

▸ **BlueprintInitializeAnimation**(): `void`

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[BlueprintInitializeAnimation](ue_ue.AnimInstance.md#blueprintinitializeanimation)

#### Defined in

[ue/ue.d.ts:5108](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5108)

___

### BlueprintPostEvaluateAnimation

▸ **BlueprintPostEvaluateAnimation**(): `void`

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[BlueprintPostEvaluateAnimation](ue_ue.AnimInstance.md#blueprintpostevaluateanimation)

#### Defined in

[ue/ue.d.ts:5109](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5109)

___

### BlueprintUpdateAnimation

▸ **BlueprintUpdateAnimation**(`DeltaTimeX`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaTimeX` | `number` |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[BlueprintUpdateAnimation](ue_ue.AnimInstance.md#blueprintupdateanimation)

#### Defined in

[ue/ue.d.ts:5110](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5110)

___

### CalculateDirection

▸ **CalculateDirection**(`Velocity`, `BaseRotation`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Velocity` | [`Vector`](ue_ue_s.Vector.md) |
| `BaseRotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[CalculateDirection](ue_ue.AnimInstance.md#calculatedirection)

#### Defined in

[ue/ue.d.ts:5111](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5111)

___

### ClearMorphTargets

▸ **ClearMorphTargets**(): `void`

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[ClearMorphTargets](ue_ue.AnimInstance.md#clearmorphtargets)

#### Defined in

[ue/ue.d.ts:5112](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5112)

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

[AnimInstance](ue_ue.AnimInstance.md).[CreateDefaultSubobject](ue_ue.AnimInstance.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[AnimInstance](ue_ue.AnimInstance.md).[ExecuteUbergraph](ue_ue.AnimInstance.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetActiveCurveNames

▸ **GetActiveCurveNames**(`CurveType`, `OutNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `CurveType` | [`EAnimCurveType`](../enums/ue_ue.EAnimCurveType.md) |
| `OutNames` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetActiveCurveNames](ue_ue.AnimInstance.md#getactivecurvenames)

#### Defined in

[ue/ue.d.ts:5113](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5113)

___

### GetAllCurveNames

▸ **GetAllCurveNames**(`OutNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutNames` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetAllCurveNames](ue_ue.AnimInstance.md#getallcurvenames)

#### Defined in

[ue/ue.d.ts:5114](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5114)

___

### GetAnimationAsset

▸ **GetAnimationAsset**(): [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Returns

[`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Defined in

[ue/ue.d.ts:20266](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20266)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetClass](ue_ue.AnimInstance.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetCurrentActiveMontage

▸ **GetCurrentActiveMontage**(): [`AnimMontage`](ue_ue.AnimMontage.md)

#### Returns

[`AnimMontage`](ue_ue.AnimMontage.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetCurrentActiveMontage](ue_ue.AnimInstance.md#getcurrentactivemontage)

#### Defined in

[ue/ue.d.ts:5115](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5115)

___

### GetCurrentStateName

▸ **GetCurrentStateName**(`MachineIndex`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MachineIndex` | `number` |

#### Returns

`string`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetCurrentStateName](ue_ue.AnimInstance.md#getcurrentstatename)

#### Defined in

[ue/ue.d.ts:5116](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5116)

___

### GetCurveValue

▸ **GetCurveValue**(`CurveName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `CurveName` | `string` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetCurveValue](ue_ue.AnimInstance.md#getcurvevalue)

#### Defined in

[ue/ue.d.ts:5117](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5117)

___

### GetInstanceAssetPlayerLength

▸ **GetInstanceAssetPlayerLength**(`AssetPlayerIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetPlayerIndex` | `number` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetInstanceAssetPlayerLength](ue_ue.AnimInstance.md#getinstanceassetplayerlength)

#### Defined in

[ue/ue.d.ts:5118](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5118)

___

### GetInstanceAssetPlayerTime

▸ **GetInstanceAssetPlayerTime**(`AssetPlayerIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetPlayerIndex` | `number` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetInstanceAssetPlayerTime](ue_ue.AnimInstance.md#getinstanceassetplayertime)

#### Defined in

[ue/ue.d.ts:5119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5119)

___

### GetInstanceAssetPlayerTimeFraction

▸ **GetInstanceAssetPlayerTimeFraction**(`AssetPlayerIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetPlayerIndex` | `number` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetInstanceAssetPlayerTimeFraction](ue_ue.AnimInstance.md#getinstanceassetplayertimefraction)

#### Defined in

[ue/ue.d.ts:5120](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5120)

___

### GetInstanceAssetPlayerTimeFromEnd

▸ **GetInstanceAssetPlayerTimeFromEnd**(`AssetPlayerIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetPlayerIndex` | `number` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetInstanceAssetPlayerTimeFromEnd](ue_ue.AnimInstance.md#getinstanceassetplayertimefromend)

#### Defined in

[ue/ue.d.ts:5121](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5121)

___

### GetInstanceAssetPlayerTimeFromEndFraction

▸ **GetInstanceAssetPlayerTimeFromEndFraction**(`AssetPlayerIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetPlayerIndex` | `number` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetInstanceAssetPlayerTimeFromEndFraction](ue_ue.AnimInstance.md#getinstanceassetplayertimefromendfraction)

#### Defined in

[ue/ue.d.ts:5122](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5122)

___

### GetInstanceCurrentStateElapsedTime

▸ **GetInstanceCurrentStateElapsedTime**(`MachineIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MachineIndex` | `number` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetInstanceCurrentStateElapsedTime](ue_ue.AnimInstance.md#getinstancecurrentstateelapsedtime)

#### Defined in

[ue/ue.d.ts:5123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5123)

___

### GetInstanceMachineWeight

▸ **GetInstanceMachineWeight**(`MachineIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MachineIndex` | `number` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetInstanceMachineWeight](ue_ue.AnimInstance.md#getinstancemachineweight)

#### Defined in

[ue/ue.d.ts:5124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5124)

___

### GetInstanceStateWeight

▸ **GetInstanceStateWeight**(`MachineIndex`, `StateIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MachineIndex` | `number` |
| `StateIndex` | `number` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetInstanceStateWeight](ue_ue.AnimInstance.md#getinstancestateweight)

#### Defined in

[ue/ue.d.ts:5125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5125)

___

### GetInstanceTransitionCrossfadeDuration

▸ **GetInstanceTransitionCrossfadeDuration**(`MachineIndex`, `TransitionIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MachineIndex` | `number` |
| `TransitionIndex` | `number` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetInstanceTransitionCrossfadeDuration](ue_ue.AnimInstance.md#getinstancetransitioncrossfadeduration)

#### Defined in

[ue/ue.d.ts:5126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5126)

___

### GetInstanceTransitionTimeElapsed

▸ **GetInstanceTransitionTimeElapsed**(`MachineIndex`, `TransitionIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MachineIndex` | `number` |
| `TransitionIndex` | `number` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetInstanceTransitionTimeElapsed](ue_ue.AnimInstance.md#getinstancetransitiontimeelapsed)

#### Defined in

[ue/ue.d.ts:5127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5127)

___

### GetInstanceTransitionTimeElapsedFraction

▸ **GetInstanceTransitionTimeElapsedFraction**(`MachineIndex`, `TransitionIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MachineIndex` | `number` |
| `TransitionIndex` | `number` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetInstanceTransitionTimeElapsedFraction](ue_ue.AnimInstance.md#getinstancetransitiontimeelapsedfraction)

#### Defined in

[ue/ue.d.ts:5128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5128)

___

### GetLength

▸ **GetLength**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:20267](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20267)

___

### GetLinkedAnimGraphInstanceByTag

▸ **GetLinkedAnimGraphInstanceByTag**(`InTag`): [`AnimInstance`](ue_ue.AnimInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTag` | `string` |

#### Returns

[`AnimInstance`](ue_ue.AnimInstance.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetLinkedAnimGraphInstanceByTag](ue_ue.AnimInstance.md#getlinkedanimgraphinstancebytag)

#### Defined in

[ue/ue.d.ts:5129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5129)

___

### GetLinkedAnimGraphInstancesByTag

▸ **GetLinkedAnimGraphInstancesByTag**(`InTag`, `OutLinkedInstances`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTag` | `string` |
| `OutLinkedInstances` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimInstance`](ue_ue.AnimInstance.md)\>\> |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetLinkedAnimGraphInstancesByTag](ue_ue.AnimInstance.md#getlinkedanimgraphinstancesbytag)

#### Defined in

[ue/ue.d.ts:5130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5130)

___

### GetLinkedAnimLayerInstanceByClass

▸ **GetLinkedAnimLayerInstanceByClass**(`InClass`): [`AnimInstance`](ue_ue.AnimInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`AnimInstance`](ue_ue.AnimInstance.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetLinkedAnimLayerInstanceByClass](ue_ue.AnimInstance.md#getlinkedanimlayerinstancebyclass)

#### Defined in

[ue/ue.d.ts:5131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5131)

___

### GetLinkedAnimLayerInstanceByGroup

▸ **GetLinkedAnimLayerInstanceByGroup**(`InGroup`): [`AnimInstance`](ue_ue.AnimInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InGroup` | `string` |

#### Returns

[`AnimInstance`](ue_ue.AnimInstance.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetLinkedAnimLayerInstanceByGroup](ue_ue.AnimInstance.md#getlinkedanimlayerinstancebygroup)

#### Defined in

[ue/ue.d.ts:5132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5132)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetName](ue_ue.AnimInstance.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetOuter](ue_ue.AnimInstance.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOwningActor

▸ **GetOwningActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetOwningActor](ue_ue.AnimInstance.md#getowningactor)

#### Defined in

[ue/ue.d.ts:5133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5133)

___

### GetOwningComponent

▸ **GetOwningComponent**(): [`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)

#### Returns

[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetOwningComponent](ue_ue.AnimInstance.md#getowningcomponent)

#### Defined in

[ue/ue.d.ts:5134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5134)

___

### GetRelevantAnimLength

▸ **GetRelevantAnimLength**(`MachineIndex`, `StateIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MachineIndex` | `number` |
| `StateIndex` | `number` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetRelevantAnimLength](ue_ue.AnimInstance.md#getrelevantanimlength)

#### Defined in

[ue/ue.d.ts:5135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5135)

___

### GetRelevantAnimTime

▸ **GetRelevantAnimTime**(`MachineIndex`, `StateIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MachineIndex` | `number` |
| `StateIndex` | `number` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetRelevantAnimTime](ue_ue.AnimInstance.md#getrelevantanimtime)

#### Defined in

[ue/ue.d.ts:5136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5136)

___

### GetRelevantAnimTimeFraction

▸ **GetRelevantAnimTimeFraction**(`MachineIndex`, `StateIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MachineIndex` | `number` |
| `StateIndex` | `number` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetRelevantAnimTimeFraction](ue_ue.AnimInstance.md#getrelevantanimtimefraction)

#### Defined in

[ue/ue.d.ts:5137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5137)

___

### GetRelevantAnimTimeRemaining

▸ **GetRelevantAnimTimeRemaining**(`MachineIndex`, `StateIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MachineIndex` | `number` |
| `StateIndex` | `number` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetRelevantAnimTimeRemaining](ue_ue.AnimInstance.md#getrelevantanimtimeremaining)

#### Defined in

[ue/ue.d.ts:5138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5138)

___

### GetRelevantAnimTimeRemainingFraction

▸ **GetRelevantAnimTimeRemainingFraction**(`MachineIndex`, `StateIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MachineIndex` | `number` |
| `StateIndex` | `number` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetRelevantAnimTimeRemainingFraction](ue_ue.AnimInstance.md#getrelevantanimtimeremainingfraction)

#### Defined in

[ue/ue.d.ts:5139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5139)

___

### GetSyncGroupPosition

▸ **GetSyncGroupPosition**(`InSyncGroupName`): [`MarkerSyncAnimPosition`](ue_ue.MarkerSyncAnimPosition.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSyncGroupName` | `string` |

#### Returns

[`MarkerSyncAnimPosition`](ue_ue.MarkerSyncAnimPosition.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetSyncGroupPosition](ue_ue.AnimInstance.md#getsyncgroupposition)

#### Defined in

[ue/ue.d.ts:5140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5140)

___

### GetTimeToClosestMarker

▸ **GetTimeToClosestMarker**(`SyncGroup`, `MarkerName`, `OutMarkerTime`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SyncGroup` | `string` |
| `MarkerName` | `string` |
| `OutMarkerTime` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetTimeToClosestMarker](ue_ue.AnimInstance.md#gettimetoclosestmarker)

#### Defined in

[ue/ue.d.ts:5141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5141)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetWorld](ue_ue.AnimInstance.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### HasMarkerBeenHitThisFrame

▸ **HasMarkerBeenHitThisFrame**(`SyncGroup`, `MarkerName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SyncGroup` | `string` |
| `MarkerName` | `string` |

#### Returns

`boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[HasMarkerBeenHitThisFrame](ue_ue.AnimInstance.md#hasmarkerbeenhitthisframe)

#### Defined in

[ue/ue.d.ts:5142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5142)

___

### IsAnyMontagePlaying

▸ **IsAnyMontagePlaying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[IsAnyMontagePlaying](ue_ue.AnimInstance.md#isanymontageplaying)

#### Defined in

[ue/ue.d.ts:5143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5143)

___

### IsPlayingSlotAnimation

▸ **IsPlayingSlotAnimation**(`Asset`, `SlotNodeName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Asset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)\> |
| `SlotNodeName` | `string` |

#### Returns

`boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[IsPlayingSlotAnimation](ue_ue.AnimInstance.md#isplayingslotanimation)

#### Defined in

[ue/ue.d.ts:5144](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5144)

___

### IsSyncGroupBetweenMarkers

▸ **IsSyncGroupBetweenMarkers**(`InSyncGroupName`, `PreviousMarker`, `NextMarker`, `bRespectMarkerOrder?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSyncGroupName` | `string` |
| `PreviousMarker` | `string` |
| `NextMarker` | `string` |
| `bRespectMarkerOrder?` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[IsSyncGroupBetweenMarkers](ue_ue.AnimInstance.md#issyncgroupbetweenmarkers)

#### Defined in

[ue/ue.d.ts:5145](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5145)

___

### LinkAnimClassLayers

▸ **LinkAnimClassLayers**(`InClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[LinkAnimClassLayers](ue_ue.AnimInstance.md#linkanimclasslayers)

#### Defined in

[ue/ue.d.ts:5146](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5146)

___

### LinkAnimGraphByTag

▸ **LinkAnimGraphByTag**(`InTag`, `InClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTag` | `string` |
| `InClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[LinkAnimGraphByTag](ue_ue.AnimInstance.md#linkanimgraphbytag)

#### Defined in

[ue/ue.d.ts:5147](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5147)

___

### LockAIResources

▸ **LockAIResources**(`bLockMovement`, `LockAILogic`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bLockMovement` | `boolean` |
| `LockAILogic` | `boolean` |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[LockAIResources](ue_ue.AnimInstance.md#lockairesources)

#### Defined in

[ue/ue.d.ts:5148](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5148)

___

### Montage\_GetBlendTime

▸ **Montage_GetBlendTime**(`Montage`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Montage` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\> |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[Montage_GetBlendTime](ue_ue.AnimInstance.md#montage_getblendtime)

#### Defined in

[ue/ue.d.ts:5149](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5149)

___

### Montage\_GetCurrentSection

▸ **Montage_GetCurrentSection**(`Montage?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Montage?` | [`AnimMontage`](ue_ue.AnimMontage.md) |

#### Returns

`string`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[Montage_GetCurrentSection](ue_ue.AnimInstance.md#montage_getcurrentsection)

#### Defined in

[ue/ue.d.ts:5150](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5150)

___

### Montage\_GetIsStopped

▸ **Montage_GetIsStopped**(`Montage`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Montage` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\> |

#### Returns

`boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[Montage_GetIsStopped](ue_ue.AnimInstance.md#montage_getisstopped)

#### Defined in

[ue/ue.d.ts:5151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5151)

___

### Montage\_GetPlayRate

▸ **Montage_GetPlayRate**(`Montage`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Montage` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\> |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[Montage_GetPlayRate](ue_ue.AnimInstance.md#montage_getplayrate)

#### Defined in

[ue/ue.d.ts:5152](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5152)

___

### Montage\_GetPosition

▸ **Montage_GetPosition**(`Montage`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Montage` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\> |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[Montage_GetPosition](ue_ue.AnimInstance.md#montage_getposition)

#### Defined in

[ue/ue.d.ts:5153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5153)

___

### Montage\_IsActive

▸ **Montage_IsActive**(`Montage`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Montage` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\> |

#### Returns

`boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[Montage_IsActive](ue_ue.AnimInstance.md#montage_isactive)

#### Defined in

[ue/ue.d.ts:5154](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5154)

___

### Montage\_IsPlaying

▸ **Montage_IsPlaying**(`Montage`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Montage` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\> |

#### Returns

`boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[Montage_IsPlaying](ue_ue.AnimInstance.md#montage_isplaying)

#### Defined in

[ue/ue.d.ts:5155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5155)

___

### Montage\_JumpToSection

▸ **Montage_JumpToSection**(`SectionName`, `Montage?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SectionName` | `string` |
| `Montage?` | [`AnimMontage`](ue_ue.AnimMontage.md) |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[Montage_JumpToSection](ue_ue.AnimInstance.md#montage_jumptosection)

#### Defined in

[ue/ue.d.ts:5156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5156)

___

### Montage\_JumpToSectionsEnd

▸ **Montage_JumpToSectionsEnd**(`SectionName`, `Montage?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SectionName` | `string` |
| `Montage?` | [`AnimMontage`](ue_ue.AnimMontage.md) |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[Montage_JumpToSectionsEnd](ue_ue.AnimInstance.md#montage_jumptosectionsend)

#### Defined in

[ue/ue.d.ts:5157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5157)

___

### Montage\_Pause

▸ **Montage_Pause**(`Montage?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Montage?` | [`AnimMontage`](ue_ue.AnimMontage.md) |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[Montage_Pause](ue_ue.AnimInstance.md#montage_pause)

#### Defined in

[ue/ue.d.ts:5158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5158)

___

### Montage\_Play

▸ **Montage_Play**(`MontageToPlay`, `InPlayRate?`, `ReturnValueType?`, `InTimeToStartMontageAt?`, `bStopAllMontages?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MontageToPlay` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\> |
| `InPlayRate?` | `number` |
| `ReturnValueType?` | [`EMontagePlayReturnType`](../enums/ue_ue.EMontagePlayReturnType.md) |
| `InTimeToStartMontageAt?` | `number` |
| `bStopAllMontages?` | `boolean` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[Montage_Play](ue_ue.AnimInstance.md#montage_play)

#### Defined in

[ue/ue.d.ts:5159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5159)

___

### Montage\_Resume

▸ **Montage_Resume**(`Montage`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Montage` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\> |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[Montage_Resume](ue_ue.AnimInstance.md#montage_resume)

#### Defined in

[ue/ue.d.ts:5160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5160)

___

### Montage\_SetNextSection

▸ **Montage_SetNextSection**(`SectionNameToChange`, `NextSection`, `Montage?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SectionNameToChange` | `string` |
| `NextSection` | `string` |
| `Montage?` | [`AnimMontage`](ue_ue.AnimMontage.md) |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[Montage_SetNextSection](ue_ue.AnimInstance.md#montage_setnextsection)

#### Defined in

[ue/ue.d.ts:5161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5161)

___

### Montage\_SetPlayRate

▸ **Montage_SetPlayRate**(`Montage`, `NewPlayRate?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Montage` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\> |
| `NewPlayRate?` | `number` |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[Montage_SetPlayRate](ue_ue.AnimInstance.md#montage_setplayrate)

#### Defined in

[ue/ue.d.ts:5162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5162)

___

### Montage\_SetPosition

▸ **Montage_SetPosition**(`Montage`, `NewPosition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Montage` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\> |
| `NewPosition` | `number` |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[Montage_SetPosition](ue_ue.AnimInstance.md#montage_setposition)

#### Defined in

[ue/ue.d.ts:5163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5163)

___

### Montage\_Stop

▸ **Montage_Stop**(`InBlendOutTime`, `Montage?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBlendOutTime` | `number` |
| `Montage?` | [`AnimMontage`](ue_ue.AnimMontage.md) |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[Montage_Stop](ue_ue.AnimInstance.md#montage_stop)

#### Defined in

[ue/ue.d.ts:5164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5164)

___

### PlayAnim

▸ **PlayAnim**(`bIsLooping?`, `InPlayRate?`, `InStartPosition?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIsLooping?` | `boolean` |
| `InPlayRate?` | `number` |
| `InStartPosition?` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:20268](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20268)

___

### PlaySlotAnimation

▸ **PlaySlotAnimation**(`Asset`, `SlotNodeName`, `BlendInTime?`, `BlendOutTime?`, `InPlayRate?`, `LoopCount?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Asset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)\> |
| `SlotNodeName` | `string` |
| `BlendInTime?` | `number` |
| `BlendOutTime?` | `number` |
| `InPlayRate?` | `number` |
| `LoopCount?` | `number` |

#### Returns

`number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[PlaySlotAnimation](ue_ue.AnimInstance.md#playslotanimation)

#### Defined in

[ue/ue.d.ts:5165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5165)

___

### PlaySlotAnimationAsDynamicMontage

▸ **PlaySlotAnimationAsDynamicMontage**(`Asset`, `SlotNodeName`, `BlendInTime?`, `BlendOutTime?`, `InPlayRate?`, `LoopCount?`, `BlendOutTriggerTime?`, `InTimeToStartMontageAt?`): [`AnimMontage`](ue_ue.AnimMontage.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Asset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)\> |
| `SlotNodeName` | `string` |
| `BlendInTime?` | `number` |
| `BlendOutTime?` | `number` |
| `InPlayRate?` | `number` |
| `LoopCount?` | `number` |
| `BlendOutTriggerTime?` | `number` |
| `InTimeToStartMontageAt?` | `number` |

#### Returns

[`AnimMontage`](ue_ue.AnimMontage.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[PlaySlotAnimationAsDynamicMontage](ue_ue.AnimInstance.md#playslotanimationasdynamicmontage)

#### Defined in

[ue/ue.d.ts:5166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5166)

___

### ResetDynamics

▸ **ResetDynamics**(`InTeleportType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTeleportType` | [`ETeleportType`](../enums/ue_ue.ETeleportType.md) |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[ResetDynamics](ue_ue.AnimInstance.md#resetdynamics)

#### Defined in

[ue/ue.d.ts:5167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5167)

___

### SavePoseSnapshot

▸ **SavePoseSnapshot**(`SnapshotName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SnapshotName` | `string` |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[SavePoseSnapshot](ue_ue.AnimInstance.md#saveposesnapshot)

#### Defined in

[ue/ue.d.ts:5168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5168)

___

### SetAnimationAsset

▸ **SetAnimationAsset**(`NewAsset`, `bIsLooping?`, `InPlayRate?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAsset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimationAsset`](ue_ue.AnimationAsset.md)\> |
| `bIsLooping?` | `boolean` |
| `InPlayRate?` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:20269](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20269)

___

### SetBlendSpaceInput

▸ **SetBlendSpaceInput**(`InBlendInput`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBlendInput` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:20270](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20270)

___

### SetLooping

▸ **SetLooping**(`bIsLooping`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIsLooping` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:20271](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20271)

___

### SetMorphTarget

▸ **SetMorphTarget**(`MorphTargetName`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MorphTargetName` | `string` |
| `Value` | `number` |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[SetMorphTarget](ue_ue.AnimInstance.md#setmorphtarget)

#### Defined in

[ue/ue.d.ts:5169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5169)

___

### SetPlayRate

▸ **SetPlayRate**(`InPlayRate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPlayRate` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:20273](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20273)

___

### SetPlaying

▸ **SetPlaying**(`bIsPlaying`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIsPlaying` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:20272](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20272)

___

### SetPosition

▸ **SetPosition**(`InPosition`, `bFireNotifies?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPosition` | `number` |
| `bFireNotifies?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:20274](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20274)

___

### SetPositionWithPreviousTime

▸ **SetPositionWithPreviousTime**(`InPosition`, `InPreviousTime`, `bFireNotifies?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPosition` | `number` |
| `InPreviousTime` | `number` |
| `bFireNotifies?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:20275](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20275)

___

### SetPreviewCurveOverride

▸ **SetPreviewCurveOverride**(`PoseName`, `Value`, `bRemoveIfZero`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PoseName` | `string` |
| `Value` | `number` |
| `bRemoveIfZero` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:20276](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20276)

___

### SetReverse

▸ **SetReverse**(`bInReverse`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInReverse` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:20277](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20277)

___

### SetRootMotionMode

▸ **SetRootMotionMode**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | [`ERootMotionMode`](../enums/ue_ue.ERootMotionMode.md) |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[SetRootMotionMode](ue_ue.AnimInstance.md#setrootmotionmode)

#### Defined in

[ue/ue.d.ts:5170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5170)

___

### SnapshotPose

▸ **SnapshotPose**(`Snapshot`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Snapshot` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PoseSnapshot`](ue_ue.PoseSnapshot.md)\> |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[SnapshotPose](ue_ue.AnimInstance.md#snapshotpose)

#### Defined in

[ue/ue.d.ts:5171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5171)

___

### StopAnim

▸ **StopAnim**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:20278](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20278)

___

### StopSlotAnimation

▸ **StopSlotAnimation**(`InBlendOutTime?`, `SlotNodeName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBlendOutTime?` | `number` |
| `SlotNodeName?` | `string` |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[StopSlotAnimation](ue_ue.AnimInstance.md#stopslotanimation)

#### Defined in

[ue/ue.d.ts:5172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5172)

___

### TryGetPawnOwner

▸ **TryGetPawnOwner**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[TryGetPawnOwner](ue_ue.AnimInstance.md#trygetpawnowner)

#### Defined in

[ue/ue.d.ts:5173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5173)

___

### UnlinkAnimClassLayers

▸ **UnlinkAnimClassLayers**(`InClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[UnlinkAnimClassLayers](ue_ue.AnimInstance.md#unlinkanimclasslayers)

#### Defined in

[ue/ue.d.ts:5174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5174)

___

### UnlockAIResources

▸ **UnlockAIResources**(`bUnlockMovement`, `UnlockAILogic`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bUnlockMovement` | `boolean` |
| `UnlockAILogic` | `boolean` |

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[UnlockAIResources](ue_ue.AnimInstance.md#unlockairesources)

#### Defined in

[ue/ue.d.ts:5175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5175)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimSingleNodeInstance`](ue_ue.AnimSingleNodeInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimSingleNodeInstance`](ue_ue.AnimSingleNodeInstance.md)

#### Overrides

[AnimInstance](ue_ue.AnimInstance.md).[Find](ue_ue.AnimInstance.md#find)

#### Defined in

[ue/ue.d.ts:20280](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20280)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimSingleNodeInstance`](ue_ue.AnimSingleNodeInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimSingleNodeInstance`](ue_ue.AnimSingleNodeInstance.md)

#### Overrides

[AnimInstance](ue_ue.AnimInstance.md).[Load](ue_ue.AnimInstance.md#load)

#### Defined in

[ue/ue.d.ts:20281](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20281)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimInstance](ue_ue.AnimInstance.md).[StaticClass](ue_ue.AnimInstance.md#staticclass)

#### Defined in

[ue/ue.d.ts:20279](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20279)
