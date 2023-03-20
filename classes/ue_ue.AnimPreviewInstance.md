[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimPreviewInstance

# Class: AnimPreviewInstance

[ue/ue](../modules/ue_ue.md).AnimPreviewInstance

## Hierarchy

- [`AnimSingleNodeInstance`](ue_ue.AnimSingleNodeInstance.md)

  ↳ **`AnimPreviewInstance`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimPreviewInstance.md#constructor)

### Properties

- [ActiveAnimNotifyState](ue_ue.AnimPreviewInstance.md#activeanimnotifystate)
- [CurrentAsset](ue_ue.AnimPreviewInstance.md#currentasset)
- [CurrentSkeleton](ue_ue.AnimPreviewInstance.md#currentskeleton)
- [DeltaTime](ue_ue.AnimPreviewInstance.md#deltatime)
- [MontagePreviewStartSectionIdx](ue_ue.AnimPreviewInstance.md#montagepreviewstartsectionidx)
- [MontagePreviewType](ue_ue.AnimPreviewInstance.md#montagepreviewtype)
- [NotifyQueue](ue_ue.AnimPreviewInstance.md#notifyqueue)
- [OnAllMontageInstancesEnded](ue_ue.AnimPreviewInstance.md#onallmontageinstancesended)
- [OnMontageBlendingOut](ue_ue.AnimPreviewInstance.md#onmontageblendingout)
- [OnMontageEnded](ue_ue.AnimPreviewInstance.md#onmontageended)
- [OnMontageStarted](ue_ue.AnimPreviewInstance.md#onmontagestarted)
- [PostCompileValidationClassName](ue_ue.AnimPreviewInstance.md#postcompilevalidationclassname)
- [PostEvaluateAnimEvent](ue_ue.AnimPreviewInstance.md#postevaluateanimevent)
- [RootMotionMode](ue_ue.AnimPreviewInstance.md#rootmotionmode)
- [\_\_tid\_AnimInstance\_\_](ue_ue.AnimPreviewInstance.md#__tid_animinstance__)
- [\_\_tid\_AnimPreviewInstance\_\_](ue_ue.AnimPreviewInstance.md#__tid_animpreviewinstance__)
- [\_\_tid\_AnimSingleNodeInstance\_\_](ue_ue.AnimPreviewInstance.md#__tid_animsinglenodeinstance__)
- [\_\_tid\_Object\_\_](ue_ue.AnimPreviewInstance.md#__tid_object__)
- [bCanUseParallelUpdateAnimation](ue_ue.AnimPreviewInstance.md#bcanuseparallelupdateanimation)
- [bQueueMontageEvents](ue_ue.AnimPreviewInstance.md#bqueuemontageevents)
- [bRunUpdatesInWorkerThreads](ue_ue.AnimPreviewInstance.md#brunupdatesinworkerthreads)
- [bUseMultiThreadedAnimationUpdate](ue_ue.AnimPreviewInstance.md#busemultithreadedanimationupdate)
- [bUsingCopyPoseFromMesh](ue_ue.AnimPreviewInstance.md#busingcopyposefrommesh)
- [bWarnAboutBlueprintUsage](ue_ue.AnimPreviewInstance.md#bwarnaboutblueprintusage)

### Methods

- [BlueprintBeginPlay](ue_ue.AnimPreviewInstance.md#blueprintbeginplay)
- [BlueprintInitializeAnimation](ue_ue.AnimPreviewInstance.md#blueprintinitializeanimation)
- [BlueprintPostEvaluateAnimation](ue_ue.AnimPreviewInstance.md#blueprintpostevaluateanimation)
- [BlueprintUpdateAnimation](ue_ue.AnimPreviewInstance.md#blueprintupdateanimation)
- [CalculateDirection](ue_ue.AnimPreviewInstance.md#calculatedirection)
- [ClearMorphTargets](ue_ue.AnimPreviewInstance.md#clearmorphtargets)
- [CreateDefaultSubobject](ue_ue.AnimPreviewInstance.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimPreviewInstance.md#executeubergraph)
- [GetActiveCurveNames](ue_ue.AnimPreviewInstance.md#getactivecurvenames)
- [GetAllCurveNames](ue_ue.AnimPreviewInstance.md#getallcurvenames)
- [GetAnimationAsset](ue_ue.AnimPreviewInstance.md#getanimationasset)
- [GetClass](ue_ue.AnimPreviewInstance.md#getclass)
- [GetCurrentActiveMontage](ue_ue.AnimPreviewInstance.md#getcurrentactivemontage)
- [GetCurrentStateName](ue_ue.AnimPreviewInstance.md#getcurrentstatename)
- [GetCurveValue](ue_ue.AnimPreviewInstance.md#getcurvevalue)
- [GetInstanceAssetPlayerLength](ue_ue.AnimPreviewInstance.md#getinstanceassetplayerlength)
- [GetInstanceAssetPlayerTime](ue_ue.AnimPreviewInstance.md#getinstanceassetplayertime)
- [GetInstanceAssetPlayerTimeFraction](ue_ue.AnimPreviewInstance.md#getinstanceassetplayertimefraction)
- [GetInstanceAssetPlayerTimeFromEnd](ue_ue.AnimPreviewInstance.md#getinstanceassetplayertimefromend)
- [GetInstanceAssetPlayerTimeFromEndFraction](ue_ue.AnimPreviewInstance.md#getinstanceassetplayertimefromendfraction)
- [GetInstanceCurrentStateElapsedTime](ue_ue.AnimPreviewInstance.md#getinstancecurrentstateelapsedtime)
- [GetInstanceMachineWeight](ue_ue.AnimPreviewInstance.md#getinstancemachineweight)
- [GetInstanceStateWeight](ue_ue.AnimPreviewInstance.md#getinstancestateweight)
- [GetInstanceTransitionCrossfadeDuration](ue_ue.AnimPreviewInstance.md#getinstancetransitioncrossfadeduration)
- [GetInstanceTransitionTimeElapsed](ue_ue.AnimPreviewInstance.md#getinstancetransitiontimeelapsed)
- [GetInstanceTransitionTimeElapsedFraction](ue_ue.AnimPreviewInstance.md#getinstancetransitiontimeelapsedfraction)
- [GetLength](ue_ue.AnimPreviewInstance.md#getlength)
- [GetLinkedAnimGraphInstanceByTag](ue_ue.AnimPreviewInstance.md#getlinkedanimgraphinstancebytag)
- [GetLinkedAnimGraphInstancesByTag](ue_ue.AnimPreviewInstance.md#getlinkedanimgraphinstancesbytag)
- [GetLinkedAnimLayerInstanceByClass](ue_ue.AnimPreviewInstance.md#getlinkedanimlayerinstancebyclass)
- [GetLinkedAnimLayerInstanceByGroup](ue_ue.AnimPreviewInstance.md#getlinkedanimlayerinstancebygroup)
- [GetName](ue_ue.AnimPreviewInstance.md#getname)
- [GetOuter](ue_ue.AnimPreviewInstance.md#getouter)
- [GetOwningActor](ue_ue.AnimPreviewInstance.md#getowningactor)
- [GetOwningComponent](ue_ue.AnimPreviewInstance.md#getowningcomponent)
- [GetRelevantAnimLength](ue_ue.AnimPreviewInstance.md#getrelevantanimlength)
- [GetRelevantAnimTime](ue_ue.AnimPreviewInstance.md#getrelevantanimtime)
- [GetRelevantAnimTimeFraction](ue_ue.AnimPreviewInstance.md#getrelevantanimtimefraction)
- [GetRelevantAnimTimeRemaining](ue_ue.AnimPreviewInstance.md#getrelevantanimtimeremaining)
- [GetRelevantAnimTimeRemainingFraction](ue_ue.AnimPreviewInstance.md#getrelevantanimtimeremainingfraction)
- [GetSyncGroupPosition](ue_ue.AnimPreviewInstance.md#getsyncgroupposition)
- [GetTimeToClosestMarker](ue_ue.AnimPreviewInstance.md#gettimetoclosestmarker)
- [GetWorld](ue_ue.AnimPreviewInstance.md#getworld)
- [HasMarkerBeenHitThisFrame](ue_ue.AnimPreviewInstance.md#hasmarkerbeenhitthisframe)
- [IsAnyMontagePlaying](ue_ue.AnimPreviewInstance.md#isanymontageplaying)
- [IsPlayingSlotAnimation](ue_ue.AnimPreviewInstance.md#isplayingslotanimation)
- [IsSyncGroupBetweenMarkers](ue_ue.AnimPreviewInstance.md#issyncgroupbetweenmarkers)
- [LinkAnimClassLayers](ue_ue.AnimPreviewInstance.md#linkanimclasslayers)
- [LinkAnimGraphByTag](ue_ue.AnimPreviewInstance.md#linkanimgraphbytag)
- [LockAIResources](ue_ue.AnimPreviewInstance.md#lockairesources)
- [Montage\_GetBlendTime](ue_ue.AnimPreviewInstance.md#montage_getblendtime)
- [Montage\_GetCurrentSection](ue_ue.AnimPreviewInstance.md#montage_getcurrentsection)
- [Montage\_GetIsStopped](ue_ue.AnimPreviewInstance.md#montage_getisstopped)
- [Montage\_GetPlayRate](ue_ue.AnimPreviewInstance.md#montage_getplayrate)
- [Montage\_GetPosition](ue_ue.AnimPreviewInstance.md#montage_getposition)
- [Montage\_IsActive](ue_ue.AnimPreviewInstance.md#montage_isactive)
- [Montage\_IsPlaying](ue_ue.AnimPreviewInstance.md#montage_isplaying)
- [Montage\_JumpToSection](ue_ue.AnimPreviewInstance.md#montage_jumptosection)
- [Montage\_JumpToSectionsEnd](ue_ue.AnimPreviewInstance.md#montage_jumptosectionsend)
- [Montage\_Pause](ue_ue.AnimPreviewInstance.md#montage_pause)
- [Montage\_Play](ue_ue.AnimPreviewInstance.md#montage_play)
- [Montage\_Resume](ue_ue.AnimPreviewInstance.md#montage_resume)
- [Montage\_SetNextSection](ue_ue.AnimPreviewInstance.md#montage_setnextsection)
- [Montage\_SetPlayRate](ue_ue.AnimPreviewInstance.md#montage_setplayrate)
- [Montage\_SetPosition](ue_ue.AnimPreviewInstance.md#montage_setposition)
- [Montage\_Stop](ue_ue.AnimPreviewInstance.md#montage_stop)
- [PlayAnim](ue_ue.AnimPreviewInstance.md#playanim)
- [PlaySlotAnimation](ue_ue.AnimPreviewInstance.md#playslotanimation)
- [PlaySlotAnimationAsDynamicMontage](ue_ue.AnimPreviewInstance.md#playslotanimationasdynamicmontage)
- [ResetDynamics](ue_ue.AnimPreviewInstance.md#resetdynamics)
- [SavePoseSnapshot](ue_ue.AnimPreviewInstance.md#saveposesnapshot)
- [SetAnimationAsset](ue_ue.AnimPreviewInstance.md#setanimationasset)
- [SetBlendSpaceInput](ue_ue.AnimPreviewInstance.md#setblendspaceinput)
- [SetLooping](ue_ue.AnimPreviewInstance.md#setlooping)
- [SetMorphTarget](ue_ue.AnimPreviewInstance.md#setmorphtarget)
- [SetPlayRate](ue_ue.AnimPreviewInstance.md#setplayrate)
- [SetPlaying](ue_ue.AnimPreviewInstance.md#setplaying)
- [SetPosition](ue_ue.AnimPreviewInstance.md#setposition)
- [SetPositionWithPreviousTime](ue_ue.AnimPreviewInstance.md#setpositionwithprevioustime)
- [SetPreviewCurveOverride](ue_ue.AnimPreviewInstance.md#setpreviewcurveoverride)
- [SetReverse](ue_ue.AnimPreviewInstance.md#setreverse)
- [SetRootMotionMode](ue_ue.AnimPreviewInstance.md#setrootmotionmode)
- [SnapshotPose](ue_ue.AnimPreviewInstance.md#snapshotpose)
- [StopAnim](ue_ue.AnimPreviewInstance.md#stopanim)
- [StopSlotAnimation](ue_ue.AnimPreviewInstance.md#stopslotanimation)
- [TryGetPawnOwner](ue_ue.AnimPreviewInstance.md#trygetpawnowner)
- [UnlinkAnimClassLayers](ue_ue.AnimPreviewInstance.md#unlinkanimclasslayers)
- [UnlockAIResources](ue_ue.AnimPreviewInstance.md#unlockairesources)
- [Find](ue_ue.AnimPreviewInstance.md#find)
- [Load](ue_ue.AnimPreviewInstance.md#load)
- [StaticClass](ue_ue.AnimPreviewInstance.md#staticclass)

## Constructors

### constructor

• **new AnimPreviewInstance**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[constructor](ue_ue.AnimSingleNodeInstance.md#constructor)

#### Defined in

[ue/ue.d.ts:20288](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20288)

## Properties

### ActiveAnimNotifyState

• **ActiveAnimNotifyState**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)\>

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[ActiveAnimNotifyState](ue_ue.AnimSingleNodeInstance.md#activeanimnotifystate)

#### Defined in

[ue/ue.d.ts:5106](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5106)

___

### CurrentAsset

• **CurrentAsset**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[CurrentAsset](ue_ue.AnimSingleNodeInstance.md#currentasset)

#### Defined in

[ue/ue.d.ts:20264](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20264)

___

### CurrentSkeleton

• **CurrentSkeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[CurrentSkeleton](ue_ue.AnimSingleNodeInstance.md#currentskeleton)

#### Defined in

[ue/ue.d.ts:5091](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5091)

___

### DeltaTime

• **DeltaTime**: `number`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[DeltaTime](ue_ue.AnimSingleNodeInstance.md#deltatime)

#### Defined in

[ue/ue.d.ts:5093](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5093)

___

### MontagePreviewStartSectionIdx

• **MontagePreviewStartSectionIdx**: `number`

#### Defined in

[ue/ue.d.ts:20290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20290)

___

### MontagePreviewType

• **MontagePreviewType**: [`EMontagePreviewType`](../enums/ue_ue.EMontagePreviewType.md)

#### Defined in

[ue/ue.d.ts:20289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20289)

___

### NotifyQueue

• **NotifyQueue**: [`AnimNotifyQueue`](ue_ue.AnimNotifyQueue.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[NotifyQueue](ue_ue.AnimSingleNodeInstance.md#notifyqueue)

#### Defined in

[ue/ue.d.ts:5105](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5105)

___

### OnAllMontageInstancesEnded

• **OnAllMontageInstancesEnded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[OnAllMontageInstancesEnded](ue_ue.AnimSingleNodeInstance.md#onallmontageinstancesended)

#### Defined in

[ue/ue.d.ts:5103](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5103)

___

### OnMontageBlendingOut

• **OnMontageBlendingOut**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>, `bInterrupted`: `boolean`) => `void`\>

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[OnMontageBlendingOut](ue_ue.AnimSingleNodeInstance.md#onmontageblendingout)

#### Defined in

[ue/ue.d.ts:5100](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5100)

___

### OnMontageEnded

• **OnMontageEnded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>, `bInterrupted`: `boolean`) => `void`\>

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[OnMontageEnded](ue_ue.AnimSingleNodeInstance.md#onmontageended)

#### Defined in

[ue/ue.d.ts:5102](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5102)

___

### OnMontageStarted

• **OnMontageStarted**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>) => `void`\>

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[OnMontageStarted](ue_ue.AnimSingleNodeInstance.md#onmontagestarted)

#### Defined in

[ue/ue.d.ts:5101](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5101)

___

### PostCompileValidationClassName

• **PostCompileValidationClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[PostCompileValidationClassName](ue_ue.AnimSingleNodeInstance.md#postcompilevalidationclassname)

#### Defined in

[ue/ue.d.ts:5104](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5104)

___

### PostEvaluateAnimEvent

• **PostEvaluateAnimEvent**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\>

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[PostEvaluateAnimEvent](ue_ue.AnimSingleNodeInstance.md#postevaluateanimevent)

#### Defined in

[ue/ue.d.ts:20265](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20265)

___

### RootMotionMode

• **RootMotionMode**: [`ERootMotionMode`](../enums/ue_ue.ERootMotionMode.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[RootMotionMode](ue_ue.AnimSingleNodeInstance.md#rootmotionmode)

#### Defined in

[ue/ue.d.ts:5092](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5092)

___

### \_\_tid\_AnimInstance\_\_

• **\_\_tid\_AnimInstance\_\_**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[__tid_AnimInstance__](ue_ue.AnimSingleNodeInstance.md#__tid_animinstance__)

#### Defined in

[ue/ue.d.ts:5180](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5180)

___

### \_\_tid\_AnimPreviewInstance\_\_

• **\_\_tid\_AnimPreviewInstance\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:20295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20295)

___

### \_\_tid\_AnimSingleNodeInstance\_\_

• **\_\_tid\_AnimSingleNodeInstance\_\_**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[__tid_AnimSingleNodeInstance__](ue_ue.AnimSingleNodeInstance.md#__tid_animsinglenodeinstance__)

#### Defined in

[ue/ue.d.ts:20283](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20283)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[__tid_Object__](ue_ue.AnimSingleNodeInstance.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bCanUseParallelUpdateAnimation

• **bCanUseParallelUpdateAnimation**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[bCanUseParallelUpdateAnimation](ue_ue.AnimSingleNodeInstance.md#bcanuseparallelupdateanimation)

#### Defined in

[ue/ue.d.ts:5095](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5095)

___

### bQueueMontageEvents

• **bQueueMontageEvents**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[bQueueMontageEvents](ue_ue.AnimSingleNodeInstance.md#bqueuemontageevents)

#### Defined in

[ue/ue.d.ts:5099](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5099)

___

### bRunUpdatesInWorkerThreads

• **bRunUpdatesInWorkerThreads**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[bRunUpdatesInWorkerThreads](ue_ue.AnimSingleNodeInstance.md#brunupdatesinworkerthreads)

#### Defined in

[ue/ue.d.ts:5094](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5094)

___

### bUseMultiThreadedAnimationUpdate

• **bUseMultiThreadedAnimationUpdate**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[bUseMultiThreadedAnimationUpdate](ue_ue.AnimSingleNodeInstance.md#busemultithreadedanimationupdate)

#### Defined in

[ue/ue.d.ts:5097](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5097)

___

### bUsingCopyPoseFromMesh

• **bUsingCopyPoseFromMesh**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[bUsingCopyPoseFromMesh](ue_ue.AnimSingleNodeInstance.md#busingcopyposefrommesh)

#### Defined in

[ue/ue.d.ts:5098](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5098)

___

### bWarnAboutBlueprintUsage

• **bWarnAboutBlueprintUsage**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[bWarnAboutBlueprintUsage](ue_ue.AnimSingleNodeInstance.md#bwarnaboutblueprintusage)

#### Defined in

[ue/ue.d.ts:5096](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5096)

## Methods

### BlueprintBeginPlay

▸ **BlueprintBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[BlueprintBeginPlay](ue_ue.AnimSingleNodeInstance.md#blueprintbeginplay)

#### Defined in

[ue/ue.d.ts:5107](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5107)

___

### BlueprintInitializeAnimation

▸ **BlueprintInitializeAnimation**(): `void`

#### Returns

`void`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[BlueprintInitializeAnimation](ue_ue.AnimSingleNodeInstance.md#blueprintinitializeanimation)

#### Defined in

[ue/ue.d.ts:5108](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5108)

___

### BlueprintPostEvaluateAnimation

▸ **BlueprintPostEvaluateAnimation**(): `void`

#### Returns

`void`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[BlueprintPostEvaluateAnimation](ue_ue.AnimSingleNodeInstance.md#blueprintpostevaluateanimation)

#### Defined in

[ue/ue.d.ts:5109](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5109)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[BlueprintUpdateAnimation](ue_ue.AnimSingleNodeInstance.md#blueprintupdateanimation)

#### Defined in

[ue/ue.d.ts:5110](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5110)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[CalculateDirection](ue_ue.AnimSingleNodeInstance.md#calculatedirection)

#### Defined in

[ue/ue.d.ts:5111](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5111)

___

### ClearMorphTargets

▸ **ClearMorphTargets**(): `void`

#### Returns

`void`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[ClearMorphTargets](ue_ue.AnimSingleNodeInstance.md#clearmorphtargets)

#### Defined in

[ue/ue.d.ts:5112](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5112)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[CreateDefaultSubobject](ue_ue.AnimSingleNodeInstance.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[ExecuteUbergraph](ue_ue.AnimSingleNodeInstance.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetActiveCurveNames](ue_ue.AnimSingleNodeInstance.md#getactivecurvenames)

#### Defined in

[ue/ue.d.ts:5113](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5113)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetAllCurveNames](ue_ue.AnimSingleNodeInstance.md#getallcurvenames)

#### Defined in

[ue/ue.d.ts:5114](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5114)

___

### GetAnimationAsset

▸ **GetAnimationAsset**(): [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Returns

[`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetAnimationAsset](ue_ue.AnimSingleNodeInstance.md#getanimationasset)

#### Defined in

[ue/ue.d.ts:20266](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20266)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetClass](ue_ue.AnimSingleNodeInstance.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetCurrentActiveMontage

▸ **GetCurrentActiveMontage**(): [`AnimMontage`](ue_ue.AnimMontage.md)

#### Returns

[`AnimMontage`](ue_ue.AnimMontage.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetCurrentActiveMontage](ue_ue.AnimSingleNodeInstance.md#getcurrentactivemontage)

#### Defined in

[ue/ue.d.ts:5115](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5115)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetCurrentStateName](ue_ue.AnimSingleNodeInstance.md#getcurrentstatename)

#### Defined in

[ue/ue.d.ts:5116](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5116)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetCurveValue](ue_ue.AnimSingleNodeInstance.md#getcurvevalue)

#### Defined in

[ue/ue.d.ts:5117](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5117)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetInstanceAssetPlayerLength](ue_ue.AnimSingleNodeInstance.md#getinstanceassetplayerlength)

#### Defined in

[ue/ue.d.ts:5118](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5118)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetInstanceAssetPlayerTime](ue_ue.AnimSingleNodeInstance.md#getinstanceassetplayertime)

#### Defined in

[ue/ue.d.ts:5119](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5119)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetInstanceAssetPlayerTimeFraction](ue_ue.AnimSingleNodeInstance.md#getinstanceassetplayertimefraction)

#### Defined in

[ue/ue.d.ts:5120](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5120)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetInstanceAssetPlayerTimeFromEnd](ue_ue.AnimSingleNodeInstance.md#getinstanceassetplayertimefromend)

#### Defined in

[ue/ue.d.ts:5121](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5121)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetInstanceAssetPlayerTimeFromEndFraction](ue_ue.AnimSingleNodeInstance.md#getinstanceassetplayertimefromendfraction)

#### Defined in

[ue/ue.d.ts:5122](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5122)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetInstanceCurrentStateElapsedTime](ue_ue.AnimSingleNodeInstance.md#getinstancecurrentstateelapsedtime)

#### Defined in

[ue/ue.d.ts:5123](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5123)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetInstanceMachineWeight](ue_ue.AnimSingleNodeInstance.md#getinstancemachineweight)

#### Defined in

[ue/ue.d.ts:5124](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5124)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetInstanceStateWeight](ue_ue.AnimSingleNodeInstance.md#getinstancestateweight)

#### Defined in

[ue/ue.d.ts:5125](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5125)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetInstanceTransitionCrossfadeDuration](ue_ue.AnimSingleNodeInstance.md#getinstancetransitioncrossfadeduration)

#### Defined in

[ue/ue.d.ts:5126](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5126)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetInstanceTransitionTimeElapsed](ue_ue.AnimSingleNodeInstance.md#getinstancetransitiontimeelapsed)

#### Defined in

[ue/ue.d.ts:5127](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5127)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetInstanceTransitionTimeElapsedFraction](ue_ue.AnimSingleNodeInstance.md#getinstancetransitiontimeelapsedfraction)

#### Defined in

[ue/ue.d.ts:5128](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5128)

___

### GetLength

▸ **GetLength**(): `number`

#### Returns

`number`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetLength](ue_ue.AnimSingleNodeInstance.md#getlength)

#### Defined in

[ue/ue.d.ts:20267](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20267)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetLinkedAnimGraphInstanceByTag](ue_ue.AnimSingleNodeInstance.md#getlinkedanimgraphinstancebytag)

#### Defined in

[ue/ue.d.ts:5129](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5129)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetLinkedAnimGraphInstancesByTag](ue_ue.AnimSingleNodeInstance.md#getlinkedanimgraphinstancesbytag)

#### Defined in

[ue/ue.d.ts:5130](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5130)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetLinkedAnimLayerInstanceByClass](ue_ue.AnimSingleNodeInstance.md#getlinkedanimlayerinstancebyclass)

#### Defined in

[ue/ue.d.ts:5131](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5131)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetLinkedAnimLayerInstanceByGroup](ue_ue.AnimSingleNodeInstance.md#getlinkedanimlayerinstancebygroup)

#### Defined in

[ue/ue.d.ts:5132](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5132)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetName](ue_ue.AnimSingleNodeInstance.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetOuter](ue_ue.AnimSingleNodeInstance.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetOwningActor

▸ **GetOwningActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetOwningActor](ue_ue.AnimSingleNodeInstance.md#getowningactor)

#### Defined in

[ue/ue.d.ts:5133](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5133)

___

### GetOwningComponent

▸ **GetOwningComponent**(): [`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)

#### Returns

[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetOwningComponent](ue_ue.AnimSingleNodeInstance.md#getowningcomponent)

#### Defined in

[ue/ue.d.ts:5134](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5134)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetRelevantAnimLength](ue_ue.AnimSingleNodeInstance.md#getrelevantanimlength)

#### Defined in

[ue/ue.d.ts:5135](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5135)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetRelevantAnimTime](ue_ue.AnimSingleNodeInstance.md#getrelevantanimtime)

#### Defined in

[ue/ue.d.ts:5136](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5136)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetRelevantAnimTimeFraction](ue_ue.AnimSingleNodeInstance.md#getrelevantanimtimefraction)

#### Defined in

[ue/ue.d.ts:5137](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5137)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetRelevantAnimTimeRemaining](ue_ue.AnimSingleNodeInstance.md#getrelevantanimtimeremaining)

#### Defined in

[ue/ue.d.ts:5138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5138)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetRelevantAnimTimeRemainingFraction](ue_ue.AnimSingleNodeInstance.md#getrelevantanimtimeremainingfraction)

#### Defined in

[ue/ue.d.ts:5139](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5139)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetSyncGroupPosition](ue_ue.AnimSingleNodeInstance.md#getsyncgroupposition)

#### Defined in

[ue/ue.d.ts:5140](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5140)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetTimeToClosestMarker](ue_ue.AnimSingleNodeInstance.md#gettimetoclosestmarker)

#### Defined in

[ue/ue.d.ts:5141](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5141)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetWorld](ue_ue.AnimSingleNodeInstance.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[HasMarkerBeenHitThisFrame](ue_ue.AnimSingleNodeInstance.md#hasmarkerbeenhitthisframe)

#### Defined in

[ue/ue.d.ts:5142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5142)

___

### IsAnyMontagePlaying

▸ **IsAnyMontagePlaying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[IsAnyMontagePlaying](ue_ue.AnimSingleNodeInstance.md#isanymontageplaying)

#### Defined in

[ue/ue.d.ts:5143](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5143)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[IsPlayingSlotAnimation](ue_ue.AnimSingleNodeInstance.md#isplayingslotanimation)

#### Defined in

[ue/ue.d.ts:5144](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5144)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[IsSyncGroupBetweenMarkers](ue_ue.AnimSingleNodeInstance.md#issyncgroupbetweenmarkers)

#### Defined in

[ue/ue.d.ts:5145](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5145)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[LinkAnimClassLayers](ue_ue.AnimSingleNodeInstance.md#linkanimclasslayers)

#### Defined in

[ue/ue.d.ts:5146](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5146)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[LinkAnimGraphByTag](ue_ue.AnimSingleNodeInstance.md#linkanimgraphbytag)

#### Defined in

[ue/ue.d.ts:5147](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5147)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[LockAIResources](ue_ue.AnimSingleNodeInstance.md#lockairesources)

#### Defined in

[ue/ue.d.ts:5148](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5148)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Montage_GetBlendTime](ue_ue.AnimSingleNodeInstance.md#montage_getblendtime)

#### Defined in

[ue/ue.d.ts:5149](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5149)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Montage_GetCurrentSection](ue_ue.AnimSingleNodeInstance.md#montage_getcurrentsection)

#### Defined in

[ue/ue.d.ts:5150](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5150)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Montage_GetIsStopped](ue_ue.AnimSingleNodeInstance.md#montage_getisstopped)

#### Defined in

[ue/ue.d.ts:5151](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5151)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Montage_GetPlayRate](ue_ue.AnimSingleNodeInstance.md#montage_getplayrate)

#### Defined in

[ue/ue.d.ts:5152](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5152)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Montage_GetPosition](ue_ue.AnimSingleNodeInstance.md#montage_getposition)

#### Defined in

[ue/ue.d.ts:5153](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5153)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Montage_IsActive](ue_ue.AnimSingleNodeInstance.md#montage_isactive)

#### Defined in

[ue/ue.d.ts:5154](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5154)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Montage_IsPlaying](ue_ue.AnimSingleNodeInstance.md#montage_isplaying)

#### Defined in

[ue/ue.d.ts:5155](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5155)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Montage_JumpToSection](ue_ue.AnimSingleNodeInstance.md#montage_jumptosection)

#### Defined in

[ue/ue.d.ts:5156](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5156)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Montage_JumpToSectionsEnd](ue_ue.AnimSingleNodeInstance.md#montage_jumptosectionsend)

#### Defined in

[ue/ue.d.ts:5157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5157)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Montage_Pause](ue_ue.AnimSingleNodeInstance.md#montage_pause)

#### Defined in

[ue/ue.d.ts:5158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5158)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Montage_Play](ue_ue.AnimSingleNodeInstance.md#montage_play)

#### Defined in

[ue/ue.d.ts:5159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5159)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Montage_Resume](ue_ue.AnimSingleNodeInstance.md#montage_resume)

#### Defined in

[ue/ue.d.ts:5160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5160)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Montage_SetNextSection](ue_ue.AnimSingleNodeInstance.md#montage_setnextsection)

#### Defined in

[ue/ue.d.ts:5161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5161)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Montage_SetPlayRate](ue_ue.AnimSingleNodeInstance.md#montage_setplayrate)

#### Defined in

[ue/ue.d.ts:5162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5162)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Montage_SetPosition](ue_ue.AnimSingleNodeInstance.md#montage_setposition)

#### Defined in

[ue/ue.d.ts:5163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5163)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Montage_Stop](ue_ue.AnimSingleNodeInstance.md#montage_stop)

#### Defined in

[ue/ue.d.ts:5164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5164)

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

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[PlayAnim](ue_ue.AnimSingleNodeInstance.md#playanim)

#### Defined in

[ue/ue.d.ts:20268](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20268)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[PlaySlotAnimation](ue_ue.AnimSingleNodeInstance.md#playslotanimation)

#### Defined in

[ue/ue.d.ts:5165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5165)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[PlaySlotAnimationAsDynamicMontage](ue_ue.AnimSingleNodeInstance.md#playslotanimationasdynamicmontage)

#### Defined in

[ue/ue.d.ts:5166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5166)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[ResetDynamics](ue_ue.AnimSingleNodeInstance.md#resetdynamics)

#### Defined in

[ue/ue.d.ts:5167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5167)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[SavePoseSnapshot](ue_ue.AnimSingleNodeInstance.md#saveposesnapshot)

#### Defined in

[ue/ue.d.ts:5168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5168)

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

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[SetAnimationAsset](ue_ue.AnimSingleNodeInstance.md#setanimationasset)

#### Defined in

[ue/ue.d.ts:20269](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20269)

___

### SetBlendSpaceInput

▸ **SetBlendSpaceInput**(`InBlendInput`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBlendInput` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[SetBlendSpaceInput](ue_ue.AnimSingleNodeInstance.md#setblendspaceinput)

#### Defined in

[ue/ue.d.ts:20270](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20270)

___

### SetLooping

▸ **SetLooping**(`bIsLooping`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIsLooping` | `boolean` |

#### Returns

`void`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[SetLooping](ue_ue.AnimSingleNodeInstance.md#setlooping)

#### Defined in

[ue/ue.d.ts:20271](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20271)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[SetMorphTarget](ue_ue.AnimSingleNodeInstance.md#setmorphtarget)

#### Defined in

[ue/ue.d.ts:5169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5169)

___

### SetPlayRate

▸ **SetPlayRate**(`InPlayRate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPlayRate` | `number` |

#### Returns

`void`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[SetPlayRate](ue_ue.AnimSingleNodeInstance.md#setplayrate)

#### Defined in

[ue/ue.d.ts:20273](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20273)

___

### SetPlaying

▸ **SetPlaying**(`bIsPlaying`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIsPlaying` | `boolean` |

#### Returns

`void`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[SetPlaying](ue_ue.AnimSingleNodeInstance.md#setplaying)

#### Defined in

[ue/ue.d.ts:20272](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20272)

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

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[SetPosition](ue_ue.AnimSingleNodeInstance.md#setposition)

#### Defined in

[ue/ue.d.ts:20274](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20274)

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

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[SetPositionWithPreviousTime](ue_ue.AnimSingleNodeInstance.md#setpositionwithprevioustime)

#### Defined in

[ue/ue.d.ts:20275](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20275)

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

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[SetPreviewCurveOverride](ue_ue.AnimSingleNodeInstance.md#setpreviewcurveoverride)

#### Defined in

[ue/ue.d.ts:20276](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20276)

___

### SetReverse

▸ **SetReverse**(`bInReverse`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInReverse` | `boolean` |

#### Returns

`void`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[SetReverse](ue_ue.AnimSingleNodeInstance.md#setreverse)

#### Defined in

[ue/ue.d.ts:20277](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20277)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[SetRootMotionMode](ue_ue.AnimSingleNodeInstance.md#setrootmotionmode)

#### Defined in

[ue/ue.d.ts:5170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5170)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[SnapshotPose](ue_ue.AnimSingleNodeInstance.md#snapshotpose)

#### Defined in

[ue/ue.d.ts:5171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5171)

___

### StopAnim

▸ **StopAnim**(): `void`

#### Returns

`void`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[StopAnim](ue_ue.AnimSingleNodeInstance.md#stopanim)

#### Defined in

[ue/ue.d.ts:20278](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20278)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[StopSlotAnimation](ue_ue.AnimSingleNodeInstance.md#stopslotanimation)

#### Defined in

[ue/ue.d.ts:5172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5172)

___

### TryGetPawnOwner

▸ **TryGetPawnOwner**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[TryGetPawnOwner](ue_ue.AnimSingleNodeInstance.md#trygetpawnowner)

#### Defined in

[ue/ue.d.ts:5173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5173)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[UnlinkAnimClassLayers](ue_ue.AnimSingleNodeInstance.md#unlinkanimclasslayers)

#### Defined in

[ue/ue.d.ts:5174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5174)

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

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[UnlockAIResources](ue_ue.AnimSingleNodeInstance.md#unlockairesources)

#### Defined in

[ue/ue.d.ts:5175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5175)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimPreviewInstance`](ue_ue.AnimPreviewInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimPreviewInstance`](ue_ue.AnimPreviewInstance.md)

#### Overrides

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Find](ue_ue.AnimSingleNodeInstance.md#find)

#### Defined in

[ue/ue.d.ts:20292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20292)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimPreviewInstance`](ue_ue.AnimPreviewInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimPreviewInstance`](ue_ue.AnimPreviewInstance.md)

#### Overrides

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[Load](ue_ue.AnimSingleNodeInstance.md#load)

#### Defined in

[ue/ue.d.ts:20293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20293)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[StaticClass](ue_ue.AnimSingleNodeInstance.md#staticclass)

#### Defined in

[ue/ue.d.ts:20291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20291)