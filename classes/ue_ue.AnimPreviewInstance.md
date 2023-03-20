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

## Properties

### ActiveAnimNotifyState

• **ActiveAnimNotifyState**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)\>

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[ActiveAnimNotifyState](ue_ue.AnimSingleNodeInstance.md#activeanimnotifystate)

___

### CurrentAsset

• **CurrentAsset**: [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[CurrentAsset](ue_ue.AnimSingleNodeInstance.md#currentasset)

___

### CurrentSkeleton

• **CurrentSkeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[CurrentSkeleton](ue_ue.AnimSingleNodeInstance.md#currentskeleton)

___

### DeltaTime

• **DeltaTime**: `number`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[DeltaTime](ue_ue.AnimSingleNodeInstance.md#deltatime)

___

### MontagePreviewStartSectionIdx

• **MontagePreviewStartSectionIdx**: `number`

___

### MontagePreviewType

• **MontagePreviewType**: [`EMontagePreviewType`](../enums/ue_ue.EMontagePreviewType.md)

___

### NotifyQueue

• **NotifyQueue**: [`AnimNotifyQueue`](ue_ue.AnimNotifyQueue.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[NotifyQueue](ue_ue.AnimSingleNodeInstance.md#notifyqueue)

___

### OnAllMontageInstancesEnded

• **OnAllMontageInstancesEnded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[OnAllMontageInstancesEnded](ue_ue.AnimSingleNodeInstance.md#onallmontageinstancesended)

___

### OnMontageBlendingOut

• **OnMontageBlendingOut**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>, `bInterrupted`: `boolean`) => `void`\>

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[OnMontageBlendingOut](ue_ue.AnimSingleNodeInstance.md#onmontageblendingout)

___

### OnMontageEnded

• **OnMontageEnded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>, `bInterrupted`: `boolean`) => `void`\>

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[OnMontageEnded](ue_ue.AnimSingleNodeInstance.md#onmontageended)

___

### OnMontageStarted

• **OnMontageStarted**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Montage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\>) => `void`\>

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[OnMontageStarted](ue_ue.AnimSingleNodeInstance.md#onmontagestarted)

___

### PostCompileValidationClassName

• **PostCompileValidationClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[PostCompileValidationClassName](ue_ue.AnimSingleNodeInstance.md#postcompilevalidationclassname)

___

### PostEvaluateAnimEvent

• **PostEvaluateAnimEvent**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\>

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[PostEvaluateAnimEvent](ue_ue.AnimSingleNodeInstance.md#postevaluateanimevent)

___

### RootMotionMode

• **RootMotionMode**: [`ERootMotionMode`](../enums/ue_ue.ERootMotionMode.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[RootMotionMode](ue_ue.AnimSingleNodeInstance.md#rootmotionmode)

___

### \_\_tid\_AnimInstance\_\_

• **\_\_tid\_AnimInstance\_\_**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[__tid_AnimInstance__](ue_ue.AnimSingleNodeInstance.md#__tid_animinstance__)

___

### \_\_tid\_AnimPreviewInstance\_\_

• **\_\_tid\_AnimPreviewInstance\_\_**: `boolean`

___

### \_\_tid\_AnimSingleNodeInstance\_\_

• **\_\_tid\_AnimSingleNodeInstance\_\_**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[__tid_AnimSingleNodeInstance__](ue_ue.AnimSingleNodeInstance.md#__tid_animsinglenodeinstance__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[__tid_Object__](ue_ue.AnimSingleNodeInstance.md#__tid_object__)

___

### bCanUseParallelUpdateAnimation

• **bCanUseParallelUpdateAnimation**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[bCanUseParallelUpdateAnimation](ue_ue.AnimSingleNodeInstance.md#bcanuseparallelupdateanimation)

___

### bQueueMontageEvents

• **bQueueMontageEvents**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[bQueueMontageEvents](ue_ue.AnimSingleNodeInstance.md#bqueuemontageevents)

___

### bRunUpdatesInWorkerThreads

• **bRunUpdatesInWorkerThreads**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[bRunUpdatesInWorkerThreads](ue_ue.AnimSingleNodeInstance.md#brunupdatesinworkerthreads)

___

### bUseMultiThreadedAnimationUpdate

• **bUseMultiThreadedAnimationUpdate**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[bUseMultiThreadedAnimationUpdate](ue_ue.AnimSingleNodeInstance.md#busemultithreadedanimationupdate)

___

### bUsingCopyPoseFromMesh

• **bUsingCopyPoseFromMesh**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[bUsingCopyPoseFromMesh](ue_ue.AnimSingleNodeInstance.md#busingcopyposefrommesh)

___

### bWarnAboutBlueprintUsage

• **bWarnAboutBlueprintUsage**: `boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[bWarnAboutBlueprintUsage](ue_ue.AnimSingleNodeInstance.md#bwarnaboutblueprintusage)

## Methods

### BlueprintBeginPlay

▸ **BlueprintBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[BlueprintBeginPlay](ue_ue.AnimSingleNodeInstance.md#blueprintbeginplay)

___

### BlueprintInitializeAnimation

▸ **BlueprintInitializeAnimation**(): `void`

#### Returns

`void`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[BlueprintInitializeAnimation](ue_ue.AnimSingleNodeInstance.md#blueprintinitializeanimation)

___

### BlueprintPostEvaluateAnimation

▸ **BlueprintPostEvaluateAnimation**(): `void`

#### Returns

`void`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[BlueprintPostEvaluateAnimation](ue_ue.AnimSingleNodeInstance.md#blueprintpostevaluateanimation)

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

___

### ClearMorphTargets

▸ **ClearMorphTargets**(): `void`

#### Returns

`void`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[ClearMorphTargets](ue_ue.AnimSingleNodeInstance.md#clearmorphtargets)

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

___

### GetAnimationAsset

▸ **GetAnimationAsset**(): [`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Returns

[`AnimationAsset`](ue_ue.AnimationAsset.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetAnimationAsset](ue_ue.AnimSingleNodeInstance.md#getanimationasset)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetClass](ue_ue.AnimSingleNodeInstance.md#getclass)

___

### GetCurrentActiveMontage

▸ **GetCurrentActiveMontage**(): [`AnimMontage`](ue_ue.AnimMontage.md)

#### Returns

[`AnimMontage`](ue_ue.AnimMontage.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetCurrentActiveMontage](ue_ue.AnimSingleNodeInstance.md#getcurrentactivemontage)

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

___

### GetLength

▸ **GetLength**(): `number`

#### Returns

`number`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetLength](ue_ue.AnimSingleNodeInstance.md#getlength)

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

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetName](ue_ue.AnimSingleNodeInstance.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetOuter](ue_ue.AnimSingleNodeInstance.md#getouter)

___

### GetOwningActor

▸ **GetOwningActor**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetOwningActor](ue_ue.AnimSingleNodeInstance.md#getowningactor)

___

### GetOwningComponent

▸ **GetOwningComponent**(): [`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)

#### Returns

[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetOwningComponent](ue_ue.AnimSingleNodeInstance.md#getowningcomponent)

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

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[GetWorld](ue_ue.AnimSingleNodeInstance.md#getworld)

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

___

### IsAnyMontagePlaying

▸ **IsAnyMontagePlaying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[IsAnyMontagePlaying](ue_ue.AnimSingleNodeInstance.md#isanymontageplaying)

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

___

### StopAnim

▸ **StopAnim**(): `void`

#### Returns

`void`

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[StopAnim](ue_ue.AnimSingleNodeInstance.md#stopanim)

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

___

### TryGetPawnOwner

▸ **TryGetPawnOwner**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[TryGetPawnOwner](ue_ue.AnimSingleNodeInstance.md#trygetpawnowner)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimSingleNodeInstance](ue_ue.AnimSingleNodeInstance.md).[StaticClass](ue_ue.AnimSingleNodeInstance.md#staticclass)
