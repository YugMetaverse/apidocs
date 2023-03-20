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

## Properties

### ActiveAnimNotifyState

• **ActiveAnimNotifyState**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)\>

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[ActiveAnimNotifyState](ue_ue.AnimInstance.md#activeanimnotifystate)

___

### CurrentAsset

• **CurrentAsset**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

___

### CurrentSkeleton

• **CurrentSkeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[CurrentSkeleton](ue_ue.AnimInstance.md#currentskeleton)

___

### DeltaTime

• **DeltaTime**: `number`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[DeltaTime](ue_ue.AnimInstance.md#deltatime)

___

### NotifyQueue

• **NotifyQueue**: [`AnimNotifyQueue`](ue_ue.AnimNotifyQueue.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[NotifyQueue](ue_ue.AnimInstance.md#notifyqueue)

___

### OnAllMontageInstancesEnded

• **OnAllMontageInstancesEnded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[OnAllMontageInstancesEnded](ue_ue.AnimInstance.md#onallmontageinstancesended)

___

### OnMontageBlendingOut

• **OnMontageBlendingOut**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>, `bInterrupted`: `boolean`) => `void`\>

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[OnMontageBlendingOut](ue_ue.AnimInstance.md#onmontageblendingout)

___

### OnMontageEnded

• **OnMontageEnded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>, `bInterrupted`: `boolean`) => `void`\>

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[OnMontageEnded](ue_ue.AnimInstance.md#onmontageended)

___

### OnMontageStarted

• **OnMontageStarted**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>) => `void`\>

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[OnMontageStarted](ue_ue.AnimInstance.md#onmontagestarted)

___

### PostCompileValidationClassName

• **PostCompileValidationClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[PostCompileValidationClassName](ue_ue.AnimInstance.md#postcompilevalidationclassname)

___

### PostEvaluateAnimEvent

• **PostEvaluateAnimEvent**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\>

___

### RootMotionMode

• **RootMotionMode**: [`ERootMotionMode`](../enums/ue_ue.ERootMotionMode.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[RootMotionMode](ue_ue.AnimInstance.md#rootmotionmode)

___

### \_\_tid\_AnimInstance\_\_

• **\_\_tid\_AnimInstance\_\_**: `boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[__tid_AnimInstance__](ue_ue.AnimInstance.md#__tid_animinstance__)

___

### \_\_tid\_AnimSingleNodeInstance\_\_

• **\_\_tid\_AnimSingleNodeInstance\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[__tid_Object__](ue_ue.AnimInstance.md#__tid_object__)

___

### bCanUseParallelUpdateAnimation

• **bCanUseParallelUpdateAnimation**: `boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[bCanUseParallelUpdateAnimation](ue_ue.AnimInstance.md#bcanuseparallelupdateanimation)

___

### bQueueMontageEvents

• **bQueueMontageEvents**: `boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[bQueueMontageEvents](ue_ue.AnimInstance.md#bqueuemontageevents)

___

### bRunUpdatesInWorkerThreads

• **bRunUpdatesInWorkerThreads**: `boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[bRunUpdatesInWorkerThreads](ue_ue.AnimInstance.md#brunupdatesinworkerthreads)

___

### bUseMultiThreadedAnimationUpdate

• **bUseMultiThreadedAnimationUpdate**: `boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[bUseMultiThreadedAnimationUpdate](ue_ue.AnimInstance.md#busemultithreadedanimationupdate)

___

### bUsingCopyPoseFromMesh

• **bUsingCopyPoseFromMesh**: `boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[bUsingCopyPoseFromMesh](ue_ue.AnimInstance.md#busingcopyposefrommesh)

___

### bWarnAboutBlueprintUsage

• **bWarnAboutBlueprintUsage**: `boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[bWarnAboutBlueprintUsage](ue_ue.AnimInstance.md#bwarnaboutblueprintusage)

## Methods

### BlueprintBeginPlay

▸ **BlueprintBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[BlueprintBeginPlay](ue_ue.AnimInstance.md#blueprintbeginplay)

___

### BlueprintInitializeAnimation

▸ **BlueprintInitializeAnimation**(): `void`

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[BlueprintInitializeAnimation](ue_ue.AnimInstance.md#blueprintinitializeanimation)

___

### BlueprintPostEvaluateAnimation

▸ **BlueprintPostEvaluateAnimation**(): `void`

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[BlueprintPostEvaluateAnimation](ue_ue.AnimInstance.md#blueprintpostevaluateanimation)

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

___

### ClearMorphTargets

▸ **ClearMorphTargets**(): `void`

#### Returns

`void`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[ClearMorphTargets](ue_ue.AnimInstance.md#clearmorphtargets)

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

___

### GetAnimationAsset

▸ **GetAnimationAsset**(): [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Returns

[`AnimationAsset`](ue_ue.AnimationAsset.md)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetClass](ue_ue.AnimInstance.md#getclass)

___

### GetCurrentActiveMontage

▸ **GetCurrentActiveMontage**(): [`AnimMontage`](ue_ue.AnimMontage.md)

#### Returns

[`AnimMontage`](ue_ue.AnimMontage.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetCurrentActiveMontage](ue_ue.AnimInstance.md#getcurrentactivemontage)

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

___

### GetLength

▸ **GetLength**(): `number`

#### Returns

`number`

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

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetName](ue_ue.AnimInstance.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetOuter](ue_ue.AnimInstance.md#getouter)

___

### GetOwningActor

▸ **GetOwningActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetOwningActor](ue_ue.AnimInstance.md#getowningactor)

___

### GetOwningComponent

▸ **GetOwningComponent**(): [`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)

#### Returns

[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetOwningComponent](ue_ue.AnimInstance.md#getowningcomponent)

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

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[GetWorld](ue_ue.AnimInstance.md#getworld)

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

___

### IsAnyMontagePlaying

▸ **IsAnyMontagePlaying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[IsAnyMontagePlaying](ue_ue.AnimInstance.md#isanymontageplaying)

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

___

### SetBlendSpaceInput

▸ **SetBlendSpaceInput**(`InBlendInput`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBlendInput` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### SetLooping

▸ **SetLooping**(`bIsLooping`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIsLooping` | `boolean` |

#### Returns

`void`

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

___

### SetPlayRate

▸ **SetPlayRate**(`InPlayRate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPlayRate` | `number` |

#### Returns

`void`

___

### SetPlaying

▸ **SetPlaying**(`bIsPlaying`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIsPlaying` | `boolean` |

#### Returns

`void`

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

___

### SetReverse

▸ **SetReverse**(`bInReverse`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInReverse` | `boolean` |

#### Returns

`void`

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

___

### StopAnim

▸ **StopAnim**(): `void`

#### Returns

`void`

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

___

### TryGetPawnOwner

▸ **TryGetPawnOwner**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[AnimInstance](ue_ue.AnimInstance.md).[TryGetPawnOwner](ue_ue.AnimInstance.md#trygetpawnowner)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimInstance](ue_ue.AnimInstance.md).[StaticClass](ue_ue.AnimInstance.md#staticclass)
