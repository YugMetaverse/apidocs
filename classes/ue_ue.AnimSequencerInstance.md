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

## Properties

### ActiveAnimNotifyState

• **ActiveAnimNotifyState**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)\>

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[ActiveAnimNotifyState](ue_ue.AnimCustomInstance.md#activeanimnotifystate)

___

### CurrentSkeleton

• **CurrentSkeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[CurrentSkeleton](ue_ue.AnimCustomInstance.md#currentskeleton)

___

### DeltaTime

• **DeltaTime**: `number`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[DeltaTime](ue_ue.AnimCustomInstance.md#deltatime)

___

### NotifyQueue

• **NotifyQueue**: [`AnimNotifyQueue`](ue_ue.AnimNotifyQueue.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[NotifyQueue](ue_ue.AnimCustomInstance.md#notifyqueue)

___

### OnAllMontageInstancesEnded

• **OnAllMontageInstancesEnded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[OnAllMontageInstancesEnded](ue_ue.AnimCustomInstance.md#onallmontageinstancesended)

___

### OnMontageBlendingOut

• **OnMontageBlendingOut**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>, `bInterrupted`: `boolean`) => `void`\>

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[OnMontageBlendingOut](ue_ue.AnimCustomInstance.md#onmontageblendingout)

___

### OnMontageEnded

• **OnMontageEnded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>, `bInterrupted`: `boolean`) => `void`\>

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[OnMontageEnded](ue_ue.AnimCustomInstance.md#onmontageended)

___

### OnMontageStarted

• **OnMontageStarted**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>) => `void`\>

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[OnMontageStarted](ue_ue.AnimCustomInstance.md#onmontagestarted)

___

### PostCompileValidationClassName

• **PostCompileValidationClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[PostCompileValidationClassName](ue_ue.AnimCustomInstance.md#postcompilevalidationclassname)

___

### RootMotionMode

• **RootMotionMode**: [`ERootMotionMode`](../enums/ue_ue.ERootMotionMode.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[RootMotionMode](ue_ue.AnimCustomInstance.md#rootmotionmode)

___

### \_\_tid\_AnimCustomInstance\_\_

• **\_\_tid\_AnimCustomInstance\_\_**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[__tid_AnimCustomInstance__](ue_ue.AnimCustomInstance.md#__tid_animcustominstance__)

___

### \_\_tid\_AnimInstance\_\_

• **\_\_tid\_AnimInstance\_\_**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[__tid_AnimInstance__](ue_ue.AnimCustomInstance.md#__tid_animinstance__)

___

### \_\_tid\_AnimSequencerInstance\_\_

• **\_\_tid\_AnimSequencerInstance\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[__tid_Object__](ue_ue.AnimCustomInstance.md#__tid_object__)

___

### bCanUseParallelUpdateAnimation

• **bCanUseParallelUpdateAnimation**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[bCanUseParallelUpdateAnimation](ue_ue.AnimCustomInstance.md#bcanuseparallelupdateanimation)

___

### bQueueMontageEvents

• **bQueueMontageEvents**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[bQueueMontageEvents](ue_ue.AnimCustomInstance.md#bqueuemontageevents)

___

### bRunUpdatesInWorkerThreads

• **bRunUpdatesInWorkerThreads**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[bRunUpdatesInWorkerThreads](ue_ue.AnimCustomInstance.md#brunupdatesinworkerthreads)

___

### bUseMultiThreadedAnimationUpdate

• **bUseMultiThreadedAnimationUpdate**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[bUseMultiThreadedAnimationUpdate](ue_ue.AnimCustomInstance.md#busemultithreadedanimationupdate)

___

### bUsingCopyPoseFromMesh

• **bUsingCopyPoseFromMesh**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[bUsingCopyPoseFromMesh](ue_ue.AnimCustomInstance.md#busingcopyposefrommesh)

___

### bWarnAboutBlueprintUsage

• **bWarnAboutBlueprintUsage**: `boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[bWarnAboutBlueprintUsage](ue_ue.AnimCustomInstance.md#bwarnaboutblueprintusage)

## Methods

### BlueprintBeginPlay

▸ **BlueprintBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[BlueprintBeginPlay](ue_ue.AnimCustomInstance.md#blueprintbeginplay)

___

### BlueprintInitializeAnimation

▸ **BlueprintInitializeAnimation**(): `void`

#### Returns

`void`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[BlueprintInitializeAnimation](ue_ue.AnimCustomInstance.md#blueprintinitializeanimation)

___

### BlueprintPostEvaluateAnimation

▸ **BlueprintPostEvaluateAnimation**(): `void`

#### Returns

`void`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[BlueprintPostEvaluateAnimation](ue_ue.AnimCustomInstance.md#blueprintpostevaluateanimation)

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

___

### ClearMorphTargets

▸ **ClearMorphTargets**(): `void`

#### Returns

`void`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[ClearMorphTargets](ue_ue.AnimCustomInstance.md#clearmorphtargets)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetClass](ue_ue.AnimCustomInstance.md#getclass)

___

### GetCurrentActiveMontage

▸ **GetCurrentActiveMontage**(): [`AnimMontage`](ue_ue.AnimMontage.md)

#### Returns

[`AnimMontage`](ue_ue.AnimMontage.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetCurrentActiveMontage](ue_ue.AnimCustomInstance.md#getcurrentactivemontage)

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

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetName](ue_ue.AnimCustomInstance.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetOuter](ue_ue.AnimCustomInstance.md#getouter)

___

### GetOwningActor

▸ **GetOwningActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetOwningActor](ue_ue.AnimCustomInstance.md#getowningactor)

___

### GetOwningComponent

▸ **GetOwningComponent**(): [`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)

#### Returns

[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetOwningComponent](ue_ue.AnimCustomInstance.md#getowningcomponent)

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

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[GetWorld](ue_ue.AnimCustomInstance.md#getworld)

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

___

### IsAnyMontagePlaying

▸ **IsAnyMontagePlaying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[IsAnyMontagePlaying](ue_ue.AnimCustomInstance.md#isanymontageplaying)

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

___

### TryGetPawnOwner

▸ **TryGetPawnOwner**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[TryGetPawnOwner](ue_ue.AnimCustomInstance.md#trygetpawnowner)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimCustomInstance](ue_ue.AnimCustomInstance.md).[StaticClass](ue_ue.AnimCustomInstance.md#staticclass)
