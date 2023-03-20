[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimSequencerInstance

# Class: AnimSequencerInstance

[ue/ue](../modules/ue_ue.md).AnimSequencerInstance

## Hierarchy

- [`AnimCustomInstance`](ue_ue.AnimCustomInstance.md)

  ↳ **`AnimSequencerInstance`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimSequencerInstance.md#constructor)

### Properties

- [ActiveAnimNotifyState](ue_ue.AnimSequencerInstance.md#activeanimnotifystate)
- [CurrentSkeleton](ue_ue.AnimSequencerInstance.md#currentskeleton)
- [DeltaTime](ue_ue.AnimSequencerInstance.md#deltatime)
- [NotifyQueue](ue_ue.AnimSequencerInstance.md#notifyqueue)
- [OnAllMontageInstancesEnded](ue_ue.AnimSequencerInstance.md#onallmontageinstancesended)
- [OnMontageBlendingOut](ue_ue.AnimSequencerInstance.md#onmontageblendingout)
- [OnMontageEnded](ue_ue.AnimSequencerInstance.md#onmontageended)
- [OnMontageStarted](ue_ue.AnimSequencerInstance.md#onmontagestarted)
- [PostCompileValidationClassName](ue_ue.AnimSequencerInstance.md#postcompilevalidationclassname)
- [RootMotionMode](ue_ue.AnimSequencerInstance.md#rootmotionmode)
- [\_\_tid\_AnimCustomInstance\_\_](ue_ue.AnimSequencerInstance.md#__tid_animcustominstance__)
- [\_\_tid\_AnimInstance\_\_](ue_ue.AnimSequencerInstance.md#__tid_animinstance__)
- [\_\_tid\_AnimSequencerInstance\_\_](ue_ue.AnimSequencerInstance.md#__tid_animsequencerinstance__)
- [\_\_tid\_Object\_\_](ue_ue.AnimSequencerInstance.md#__tid_object__)
- [bCanUseParallelUpdateAnimation](ue_ue.AnimSequencerInstance.md#bcanuseparallelupdateanimation)
- [bQueueMontageEvents](ue_ue.AnimSequencerInstance.md#bqueuemontageevents)
- [bRunUpdatesInWorkerThreads](ue_ue.AnimSequencerInstance.md#brunupdatesinworkerthreads)
- [bUseMultiThreadedAnimationUpdate](ue_ue.AnimSequencerInstance.md#busemultithreadedanimationupdate)
- [bUsingCopyPoseFromMesh](ue_ue.AnimSequencerInstance.md#busingcopyposefrommesh)
- [bWarnAboutBlueprintUsage](ue_ue.AnimSequencerInstance.md#bwarnaboutblueprintusage)

### Methods

- [BlueprintBeginPlay](ue_ue.AnimSequencerInstance.md#blueprintbeginplay)
- [BlueprintInitializeAnimation](ue_ue.AnimSequencerInstance.md#blueprintinitializeanimation)
- [BlueprintPostEvaluateAnimation](ue_ue.AnimSequencerInstance.md#blueprintpostevaluateanimation)
- [BlueprintUpdateAnimation](ue_ue.AnimSequencerInstance.md#blueprintupdateanimation)
- [CalculateDirection](ue_ue.AnimSequencerInstance.md#calculatedirection)
- [ClearMorphTargets](ue_ue.AnimSequencerInstance.md#clearmorphtargets)
- [CreateDefaultSubobject](ue_ue.AnimSequencerInstance.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimSequencerInstance.md#executeubergraph)
- [GetActiveCurveNames](ue_ue.AnimSequencerInstance.md#getactivecurvenames)
- [GetAllCurveNames](ue_ue.AnimSequencerInstance.md#getallcurvenames)
- [GetClass](ue_ue.AnimSequencerInstance.md#getclass)
- [GetCurrentActiveMontage](ue_ue.AnimSequencerInstance.md#getcurrentactivemontage)
- [GetCurrentStateName](ue_ue.AnimSequencerInstance.md#getcurrentstatename)
- [GetCurveValue](ue_ue.AnimSequencerInstance.md#getcurvevalue)
- [GetInstanceAssetPlayerLength](ue_ue.AnimSequencerInstance.md#getinstanceassetplayerlength)
- [GetInstanceAssetPlayerTime](ue_ue.AnimSequencerInstance.md#getinstanceassetplayertime)
- [GetInstanceAssetPlayerTimeFraction](ue_ue.AnimSequencerInstance.md#getinstanceassetplayertimefraction)
- [GetInstanceAssetPlayerTimeFromEnd](ue_ue.AnimSequencerInstance.md#getinstanceassetplayertimefromend)
- [GetInstanceAssetPlayerTimeFromEndFraction](ue_ue.AnimSequencerInstance.md#getinstanceassetplayertimefromendfraction)
- [GetInstanceCurrentStateElapsedTime](ue_ue.AnimSequencerInstance.md#getinstancecurrentstateelapsedtime)
- [GetInstanceMachineWeight](ue_ue.AnimSequencerInstance.md#getinstancemachineweight)
- [GetInstanceStateWeight](ue_ue.AnimSequencerInstance.md#getinstancestateweight)
- [GetInstanceTransitionCrossfadeDuration](ue_ue.AnimSequencerInstance.md#getinstancetransitioncrossfadeduration)
- [GetInstanceTransitionTimeElapsed](ue_ue.AnimSequencerInstance.md#getinstancetransitiontimeelapsed)
- [GetInstanceTransitionTimeElapsedFraction](ue_ue.AnimSequencerInstance.md#getinstancetransitiontimeelapsedfraction)
- [GetLinkedAnimGraphInstanceByTag](ue_ue.AnimSequencerInstance.md#getlinkedanimgraphinstancebytag)
- [GetLinkedAnimGraphInstancesByTag](ue_ue.AnimSequencerInstance.md#getlinkedanimgraphinstancesbytag)
- [GetLinkedAnimLayerInstanceByClass](ue_ue.AnimSequencerInstance.md#getlinkedanimlayerinstancebyclass)
- [GetLinkedAnimLayerInstanceByGroup](ue_ue.AnimSequencerInstance.md#getlinkedanimlayerinstancebygroup)
- [GetName](ue_ue.AnimSequencerInstance.md#getname)
- [GetOuter](ue_ue.AnimSequencerInstance.md#getouter)
- [GetOwningActor](ue_ue.AnimSequencerInstance.md#getowningactor)
- [GetOwningComponent](ue_ue.AnimSequencerInstance.md#getowningcomponent)
- [GetRelevantAnimLength](ue_ue.AnimSequencerInstance.md#getrelevantanimlength)
- [GetRelevantAnimTime](ue_ue.AnimSequencerInstance.md#getrelevantanimtime)
- [GetRelevantAnimTimeFraction](ue_ue.AnimSequencerInstance.md#getrelevantanimtimefraction)
- [GetRelevantAnimTimeRemaining](ue_ue.AnimSequencerInstance.md#getrelevantanimtimeremaining)
- [GetRelevantAnimTimeRemainingFraction](ue_ue.AnimSequencerInstance.md#getrelevantanimtimeremainingfraction)
- [GetSyncGroupPosition](ue_ue.AnimSequencerInstance.md#getsyncgroupposition)
- [GetTimeToClosestMarker](ue_ue.AnimSequencerInstance.md#gettimetoclosestmarker)
- [GetWorld](ue_ue.AnimSequencerInstance.md#getworld)
- [HasMarkerBeenHitThisFrame](ue_ue.AnimSequencerInstance.md#hasmarkerbeenhitthisframe)
- [IsAnyMontagePlaying](ue_ue.AnimSequencerInstance.md#isanymontageplaying)
- [IsPlayingSlotAnimation](ue_ue.AnimSequencerInstance.md#isplayingslotanimation)
- [IsSyncGroupBetweenMarkers](ue_ue.AnimSequencerInstance.md#issyncgroupbetweenmarkers)
- [LinkAnimClassLayers](ue_ue.AnimSequencerInstance.md#linkanimclasslayers)
- [LinkAnimGraphByTag](ue_ue.AnimSequencerInstance.md#linkanimgraphbytag)
- [LockAIResources](ue_ue.AnimSequencerInstance.md#lockairesources)
- [Montage\_GetBlendTime](ue_ue.AnimSequencerInstance.md#montage_getblendtime)
- [Montage\_GetCurrentSection](ue_ue.AnimSequencerInstance.md#montage_getcurrentsection)
- [Montage\_GetIsStopped](ue_ue.AnimSequencerInstance.md#montage_getisstopped)
- [Montage\_GetPlayRate](ue_ue.AnimSequencerInstance.md#montage_getplayrate)
- [Montage\_GetPosition](ue_ue.AnimSequencerInstance.md#montage_getposition)
- [Montage\_IsActive](ue_ue.AnimSequencerInstance.md#montage_isactive)
- [Montage\_IsPlaying](ue_ue.AnimSequencerInstance.md#montage_isplaying)
- [Montage\_JumpToSection](ue_ue.AnimSequencerInstance.md#montage_jumptosection)
- [Montage\_JumpToSectionsEnd](ue_ue.AnimSequencerInstance.md#montage_jumptosectionsend)
- [Montage\_Pause](ue_ue.AnimSequencerInstance.md#montage_pause)
- [Montage\_Play](ue_ue.AnimSequencerInstance.md#montage_play)
- [Montage\_Resume](ue_ue.AnimSequencerInstance.md#montage_resume)
- [Montage\_SetNextSection](ue_ue.AnimSequencerInstance.md#montage_setnextsection)
- [Montage\_SetPlayRate](ue_ue.AnimSequencerInstance.md#montage_setplayrate)
- [Montage\_SetPosition](ue_ue.AnimSequencerInstance.md#montage_setposition)
- [Montage\_Stop](ue_ue.AnimSequencerInstance.md#montage_stop)
- [PlaySlotAnimation](ue_ue.AnimSequencerInstance.md#playslotanimation)
- [PlaySlotAnimationAsDynamicMontage](ue_ue.AnimSequencerInstance.md#playslotanimationasdynamicmontage)
- [ResetDynamics](ue_ue.AnimSequencerInstance.md#resetdynamics)
- [SavePoseSnapshot](ue_ue.AnimSequencerInstance.md#saveposesnapshot)
- [SetMorphTarget](ue_ue.AnimSequencerInstance.md#setmorphtarget)
- [SetRootMotionMode](ue_ue.AnimSequencerInstance.md#setrootmotionmode)
- [SnapshotPose](ue_ue.AnimSequencerInstance.md#snapshotpose)
- [StopSlotAnimation](ue_ue.AnimSequencerInstance.md#stopslotanimation)
- [TryGetPawnOwner](ue_ue.AnimSequencerInstance.md#trygetpawnowner)
- [UnlinkAnimClassLayers](ue_ue.AnimSequencerInstance.md#unlinkanimclasslayers)
- [UnlockAIResources](ue_ue.AnimSequencerInstance.md#unlockairesources)
- [Find](ue_ue.AnimSequencerInstance.md#find)
- [Load](ue_ue.AnimSequencerInstance.md#load)
- [StaticClass](ue_ue.AnimSequencerInstance.md#staticclass)

## Constructors

### constructor

• **new AnimSequencerInstance**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[constructor](ue_ue.AnimCustomInstance.md#constructor)

#### Defined in

[ue/ue.d.ts:20371](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20371)

## Properties

### ActiveAnimNotifyState

• **ActiveAnimNotifyState**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)\>

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[ActiveAnimNotifyState](ue_ue.AnimCustomInstance.md#activeanimnotifystate)

#### Defined in

[ue/ue.d.ts:5106](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5106)

___

### CurrentSkeleton

• **CurrentSkeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[CurrentSkeleton](ue_ue.AnimCustomInstance.md#currentskeleton)

#### Defined in

[ue/ue.d.ts:5091](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5091)

___

### DeltaTime

• **DeltaTime**: `number`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[DeltaTime](ue_ue.AnimCustomInstance.md#deltatime)

#### Defined in

[ue/ue.d.ts:5093](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5093)

___

### NotifyQueue

• **NotifyQueue**: [`AnimNotifyQueue`](ue_ue.AnimNotifyQueue.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[NotifyQueue](ue_ue.AnimCustomInstance.md#notifyqueue)

#### Defined in

[ue/ue.d.ts:5105](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5105)

___

### OnAllMontageInstancesEnded

• **OnAllMontageInstancesEnded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[OnAllMontageInstancesEnded](ue_ue.AnimCustomInstance.md#onallmontageinstancesended)

#### Defined in

[ue/ue.d.ts:5103](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5103)

___

### OnMontageBlendingOut

• **OnMontageBlendingOut**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>, `bInterrupted`: `boolean`) => `void`\>

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[OnMontageBlendingOut](ue_ue.AnimCustomInstance.md#onmontageblendingout)

#### Defined in

[ue/ue.d.ts:5100](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5100)

___

### OnMontageEnded

• **OnMontageEnded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>, `bInterrupted`: `boolean`) => `void`\>

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[OnMontageEnded](ue_ue.AnimCustomInstance.md#onmontageended)

#### Defined in

[ue/ue.d.ts:5102](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5102)

___

### OnMontageStarted

• **OnMontageStarted**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>) => `void`\>

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[OnMontageStarted](ue_ue.AnimCustomInstance.md#onmontagestarted)

#### Defined in

[ue/ue.d.ts:5101](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5101)

___

### PostCompileValidationClassName

• **PostCompileValidationClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[PostCompileValidationClassName](ue_ue.AnimCustomInstance.md#postcompilevalidationclassname)

#### Defined in

[ue/ue.d.ts:5104](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5104)

___

### RootMotionMode

• **RootMotionMode**: [`ERootMotionMode`](../enums/ue_ue.ERootMotionMode.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[RootMotionMode](ue_ue.AnimCustomInstance.md#rootmotionmode)

#### Defined in

[ue/ue.d.ts:5092](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5092)

___

### \_\_tid\_AnimCustomInstance\_\_

• **\_\_tid\_AnimCustomInstance\_\_**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[__tid_AnimCustomInstance__](ue_ue.AnimCustomInstance.md#__tid_animcustominstance__)

#### Defined in

[ue/ue.d.ts:17527](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17527)

___

### \_\_tid\_AnimInstance\_\_

• **\_\_tid\_AnimInstance\_\_**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[__tid_AnimInstance__](ue_ue.AnimCustomInstance.md#__tid_animinstance__)

#### Defined in

[ue/ue.d.ts:5180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5180)

___

### \_\_tid\_AnimSequencerInstance\_\_

• **\_\_tid\_AnimSequencerInstance\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:20376](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20376)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[__tid_Object__](ue_ue.AnimCustomInstance.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bCanUseParallelUpdateAnimation

• **bCanUseParallelUpdateAnimation**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[bCanUseParallelUpdateAnimation](ue_ue.AnimCustomInstance.md#bcanuseparallelupdateanimation)

#### Defined in

[ue/ue.d.ts:5095](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5095)

___

### bQueueMontageEvents

• **bQueueMontageEvents**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[bQueueMontageEvents](ue_ue.AnimCustomInstance.md#bqueuemontageevents)

#### Defined in

[ue/ue.d.ts:5099](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5099)

___

### bRunUpdatesInWorkerThreads

• **bRunUpdatesInWorkerThreads**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[bRunUpdatesInWorkerThreads](ue_ue.AnimCustomInstance.md#brunupdatesinworkerthreads)

#### Defined in

[ue/ue.d.ts:5094](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5094)

___

### bUseMultiThreadedAnimationUpdate

• **bUseMultiThreadedAnimationUpdate**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[bUseMultiThreadedAnimationUpdate](ue_ue.AnimCustomInstance.md#busemultithreadedanimationupdate)

#### Defined in

[ue/ue.d.ts:5097](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5097)

___

### bUsingCopyPoseFromMesh

• **bUsingCopyPoseFromMesh**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[bUsingCopyPoseFromMesh](ue_ue.AnimCustomInstance.md#busingcopyposefrommesh)

#### Defined in

[ue/ue.d.ts:5098](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5098)

___

### bWarnAboutBlueprintUsage

• **bWarnAboutBlueprintUsage**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[bWarnAboutBlueprintUsage](ue_ue.AnimCustomInstance.md#bwarnaboutblueprintusage)

#### Defined in

[ue/ue.d.ts:5096](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5096)

## Methods

### BlueprintBeginPlay

▸ **BlueprintBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[BlueprintBeginPlay](ue_ue.AnimCustomInstance.md#blueprintbeginplay)

#### Defined in

[ue/ue.d.ts:5107](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5107)

___

### BlueprintInitializeAnimation

▸ **BlueprintInitializeAnimation**(): `void`

#### Returns

`void`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[BlueprintInitializeAnimation](ue_ue.AnimCustomInstance.md#blueprintinitializeanimation)

#### Defined in

[ue/ue.d.ts:5108](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5108)

___

### BlueprintPostEvaluateAnimation

▸ **BlueprintPostEvaluateAnimation**(): `void`

#### Returns

`void`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[BlueprintPostEvaluateAnimation](ue_ue.AnimCustomInstance.md#blueprintpostevaluateanimation)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[BlueprintUpdateAnimation](ue_ue.AnimCustomInstance.md#blueprintupdateanimation)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[CalculateDirection](ue_ue.AnimCustomInstance.md#calculatedirection)

#### Defined in

[ue/ue.d.ts:5111](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5111)

___

### ClearMorphTargets

▸ **ClearMorphTargets**(): `void`

#### Returns

`void`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[ClearMorphTargets](ue_ue.AnimCustomInstance.md#clearmorphtargets)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[CreateDefaultSubobject](ue_ue.AnimCustomInstance.md#createdefaultsubobject)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[ExecuteUbergraph](ue_ue.AnimCustomInstance.md#executeubergraph)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetActiveCurveNames](ue_ue.AnimCustomInstance.md#getactivecurvenames)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetAllCurveNames](ue_ue.AnimCustomInstance.md#getallcurvenames)

#### Defined in

[ue/ue.d.ts:5114](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5114)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetClass](ue_ue.AnimCustomInstance.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetCurrentActiveMontage

▸ **GetCurrentActiveMontage**(): [`AnimMontage`](ue_ue.AnimMontage.md)

#### Returns

[`AnimMontage`](ue_ue.AnimMontage.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetCurrentActiveMontage](ue_ue.AnimCustomInstance.md#getcurrentactivemontage)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetCurrentStateName](ue_ue.AnimCustomInstance.md#getcurrentstatename)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetCurveValue](ue_ue.AnimCustomInstance.md#getcurvevalue)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetInstanceAssetPlayerLength](ue_ue.AnimCustomInstance.md#getinstanceassetplayerlength)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetInstanceAssetPlayerTime](ue_ue.AnimCustomInstance.md#getinstanceassetplayertime)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetInstanceAssetPlayerTimeFraction](ue_ue.AnimCustomInstance.md#getinstanceassetplayertimefraction)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetInstanceAssetPlayerTimeFromEnd](ue_ue.AnimCustomInstance.md#getinstanceassetplayertimefromend)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetInstanceAssetPlayerTimeFromEndFraction](ue_ue.AnimCustomInstance.md#getinstanceassetplayertimefromendfraction)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetInstanceCurrentStateElapsedTime](ue_ue.AnimCustomInstance.md#getinstancecurrentstateelapsedtime)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetInstanceMachineWeight](ue_ue.AnimCustomInstance.md#getinstancemachineweight)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetInstanceStateWeight](ue_ue.AnimCustomInstance.md#getinstancestateweight)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetInstanceTransitionCrossfadeDuration](ue_ue.AnimCustomInstance.md#getinstancetransitioncrossfadeduration)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetInstanceTransitionTimeElapsed](ue_ue.AnimCustomInstance.md#getinstancetransitiontimeelapsed)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetInstanceTransitionTimeElapsedFraction](ue_ue.AnimCustomInstance.md#getinstancetransitiontimeelapsedfraction)

#### Defined in

[ue/ue.d.ts:5128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5128)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetLinkedAnimGraphInstanceByTag](ue_ue.AnimCustomInstance.md#getlinkedanimgraphinstancebytag)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetLinkedAnimGraphInstancesByTag](ue_ue.AnimCustomInstance.md#getlinkedanimgraphinstancesbytag)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetLinkedAnimLayerInstanceByClass](ue_ue.AnimCustomInstance.md#getlinkedanimlayerinstancebyclass)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetLinkedAnimLayerInstanceByGroup](ue_ue.AnimCustomInstance.md#getlinkedanimlayerinstancebygroup)

#### Defined in

[ue/ue.d.ts:5132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5132)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetName](ue_ue.AnimCustomInstance.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetOuter](ue_ue.AnimCustomInstance.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOwningActor

▸ **GetOwningActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetOwningActor](ue_ue.AnimCustomInstance.md#getowningactor)

#### Defined in

[ue/ue.d.ts:5133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5133)

___

### GetOwningComponent

▸ **GetOwningComponent**(): [`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)

#### Returns

[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetOwningComponent](ue_ue.AnimCustomInstance.md#getowningcomponent)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetRelevantAnimLength](ue_ue.AnimCustomInstance.md#getrelevantanimlength)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetRelevantAnimTime](ue_ue.AnimCustomInstance.md#getrelevantanimtime)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetRelevantAnimTimeFraction](ue_ue.AnimCustomInstance.md#getrelevantanimtimefraction)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetRelevantAnimTimeRemaining](ue_ue.AnimCustomInstance.md#getrelevantanimtimeremaining)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetRelevantAnimTimeRemainingFraction](ue_ue.AnimCustomInstance.md#getrelevantanimtimeremainingfraction)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetSyncGroupPosition](ue_ue.AnimCustomInstance.md#getsyncgroupposition)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetTimeToClosestMarker](ue_ue.AnimCustomInstance.md#gettimetoclosestmarker)

#### Defined in

[ue/ue.d.ts:5141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5141)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetWorld](ue_ue.AnimCustomInstance.md#getworld)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[HasMarkerBeenHitThisFrame](ue_ue.AnimCustomInstance.md#hasmarkerbeenhitthisframe)

#### Defined in

[ue/ue.d.ts:5142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5142)

___

### IsAnyMontagePlaying

▸ **IsAnyMontagePlaying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[IsAnyMontagePlaying](ue_ue.AnimCustomInstance.md#isanymontageplaying)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[IsPlayingSlotAnimation](ue_ue.AnimCustomInstance.md#isplayingslotanimation)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[IsSyncGroupBetweenMarkers](ue_ue.AnimCustomInstance.md#issyncgroupbetweenmarkers)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[LinkAnimClassLayers](ue_ue.AnimCustomInstance.md#linkanimclasslayers)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[LinkAnimGraphByTag](ue_ue.AnimCustomInstance.md#linkanimgraphbytag)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[LockAIResources](ue_ue.AnimCustomInstance.md#lockairesources)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Montage_GetBlendTime](ue_ue.AnimCustomInstance.md#montage_getblendtime)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Montage_GetCurrentSection](ue_ue.AnimCustomInstance.md#montage_getcurrentsection)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Montage_GetIsStopped](ue_ue.AnimCustomInstance.md#montage_getisstopped)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Montage_GetPlayRate](ue_ue.AnimCustomInstance.md#montage_getplayrate)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Montage_GetPosition](ue_ue.AnimCustomInstance.md#montage_getposition)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Montage_IsActive](ue_ue.AnimCustomInstance.md#montage_isactive)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Montage_IsPlaying](ue_ue.AnimCustomInstance.md#montage_isplaying)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Montage_JumpToSection](ue_ue.AnimCustomInstance.md#montage_jumptosection)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Montage_JumpToSectionsEnd](ue_ue.AnimCustomInstance.md#montage_jumptosectionsend)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Montage_Pause](ue_ue.AnimCustomInstance.md#montage_pause)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Montage_Play](ue_ue.AnimCustomInstance.md#montage_play)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Montage_Resume](ue_ue.AnimCustomInstance.md#montage_resume)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Montage_SetNextSection](ue_ue.AnimCustomInstance.md#montage_setnextsection)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Montage_SetPlayRate](ue_ue.AnimCustomInstance.md#montage_setplayrate)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Montage_SetPosition](ue_ue.AnimCustomInstance.md#montage_setposition)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Montage_Stop](ue_ue.AnimCustomInstance.md#montage_stop)

#### Defined in

[ue/ue.d.ts:5164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5164)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[PlaySlotAnimation](ue_ue.AnimCustomInstance.md#playslotanimation)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[PlaySlotAnimationAsDynamicMontage](ue_ue.AnimCustomInstance.md#playslotanimationasdynamicmontage)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[ResetDynamics](ue_ue.AnimCustomInstance.md#resetdynamics)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[SavePoseSnapshot](ue_ue.AnimCustomInstance.md#saveposesnapshot)

#### Defined in

[ue/ue.d.ts:5168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5168)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[SetMorphTarget](ue_ue.AnimCustomInstance.md#setmorphtarget)

#### Defined in

[ue/ue.d.ts:5169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5169)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[SetRootMotionMode](ue_ue.AnimCustomInstance.md#setrootmotionmode)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[SnapshotPose](ue_ue.AnimCustomInstance.md#snapshotpose)

#### Defined in

[ue/ue.d.ts:5171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5171)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[StopSlotAnimation](ue_ue.AnimCustomInstance.md#stopslotanimation)

#### Defined in

[ue/ue.d.ts:5172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5172)

___

### TryGetPawnOwner

▸ **TryGetPawnOwner**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[TryGetPawnOwner](ue_ue.AnimCustomInstance.md#trygetpawnowner)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[UnlinkAnimClassLayers](ue_ue.AnimCustomInstance.md#unlinkanimclasslayers)

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

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[UnlockAIResources](ue_ue.AnimCustomInstance.md#unlockairesources)

#### Defined in

[ue/ue.d.ts:5175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5175)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimSequencerInstance`](ue_ue.AnimSequencerInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimSequencerInstance`](ue_ue.AnimSequencerInstance.md)

#### Overrides

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Find](ue_ue.AnimCustomInstance.md#find)

#### Defined in

[ue/ue.d.ts:20373](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20373)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimSequencerInstance`](ue_ue.AnimSequencerInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimSequencerInstance`](ue_ue.AnimSequencerInstance.md)

#### Overrides

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[Load](ue_ue.AnimCustomInstance.md#load)

#### Defined in

[ue/ue.d.ts:20374](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20374)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[StaticClass](ue_ue.AnimCustomInstance.md#staticclass)

#### Defined in

[ue/ue.d.ts:20372](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20372)
