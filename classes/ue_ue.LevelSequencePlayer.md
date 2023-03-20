[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelSequencePlayer

# Class: LevelSequencePlayer

[ue/ue](../modules/ue_ue.md).LevelSequencePlayer

## Hierarchy

- [`MovieSceneSequencePlayer`](ue_ue.MovieSceneSequencePlayer.md)

  ↳ **`LevelSequencePlayer`**

## Table of contents

### Constructors

- [constructor](ue_ue.LevelSequencePlayer.md#constructor)

### Properties

- [CurrentNumLoops](ue_ue.LevelSequencePlayer.md#currentnumloops)
- [DurationFrames](ue_ue.LevelSequencePlayer.md#durationframes)
- [NetSyncProps](ue_ue.LevelSequencePlayer.md#netsyncprops)
- [OnCameraCut](ue_ue.LevelSequencePlayer.md#oncameracut)
- [OnFinished](ue_ue.LevelSequencePlayer.md#onfinished)
- [OnPause](ue_ue.LevelSequencePlayer.md#onpause)
- [OnPlay](ue_ue.LevelSequencePlayer.md#onplay)
- [OnPlayReverse](ue_ue.LevelSequencePlayer.md#onplayreverse)
- [OnStop](ue_ue.LevelSequencePlayer.md#onstop)
- [PlaybackClient](ue_ue.LevelSequencePlayer.md#playbackclient)
- [PlaybackSettings](ue_ue.LevelSequencePlayer.md#playbacksettings)
- [RootTemplateInstance](ue_ue.LevelSequencePlayer.md#roottemplateinstance)
- [Sequence](ue_ue.LevelSequencePlayer.md#sequence)
- [StartTime](ue_ue.LevelSequencePlayer.md#starttime)
- [Status](ue_ue.LevelSequencePlayer.md#status)
- [\_\_tid\_LevelSequencePlayer\_\_](ue_ue.LevelSequencePlayer.md#__tid_levelsequenceplayer__)
- [\_\_tid\_MovieSceneSequencePlayer\_\_](ue_ue.LevelSequencePlayer.md#__tid_moviescenesequenceplayer__)
- [\_\_tid\_Object\_\_](ue_ue.LevelSequencePlayer.md#__tid_object__)
- [bReversePlayback](ue_ue.LevelSequencePlayer.md#breverseplayback)

### Methods

- [ChangePlaybackDirection](ue_ue.LevelSequencePlayer.md#changeplaybackdirection)
- [CreateDefaultSubobject](ue_ue.LevelSequencePlayer.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LevelSequencePlayer.md#executeubergraph)
- [GetActiveCameraComponent](ue_ue.LevelSequencePlayer.md#getactivecameracomponent)
- [GetBoundObjects](ue_ue.LevelSequencePlayer.md#getboundobjects)
- [GetClass](ue_ue.LevelSequencePlayer.md#getclass)
- [GetCurrentTime](ue_ue.LevelSequencePlayer.md#getcurrenttime)
- [GetDisableCameraCuts](ue_ue.LevelSequencePlayer.md#getdisablecameracuts)
- [GetDuration](ue_ue.LevelSequencePlayer.md#getduration)
- [GetEndTime](ue_ue.LevelSequencePlayer.md#getendtime)
- [GetFrameDuration](ue_ue.LevelSequencePlayer.md#getframeduration)
- [GetFrameRate](ue_ue.LevelSequencePlayer.md#getframerate)
- [GetLength](ue_ue.LevelSequencePlayer.md#getlength)
- [GetName](ue_ue.LevelSequencePlayer.md#getname)
- [GetObjectBindings](ue_ue.LevelSequencePlayer.md#getobjectbindings)
- [GetOuter](ue_ue.LevelSequencePlayer.md#getouter)
- [GetPlayRate](ue_ue.LevelSequencePlayer.md#getplayrate)
- [GetPlaybackEnd](ue_ue.LevelSequencePlayer.md#getplaybackend)
- [GetPlaybackPosition](ue_ue.LevelSequencePlayer.md#getplaybackposition)
- [GetPlaybackStart](ue_ue.LevelSequencePlayer.md#getplaybackstart)
- [GetStartTime](ue_ue.LevelSequencePlayer.md#getstarttime)
- [GetWorld](ue_ue.LevelSequencePlayer.md#getworld)
- [GoToEndAndStop](ue_ue.LevelSequencePlayer.md#gotoendandstop)
- [IsPaused](ue_ue.LevelSequencePlayer.md#ispaused)
- [IsPlaying](ue_ue.LevelSequencePlayer.md#isplaying)
- [IsReversed](ue_ue.LevelSequencePlayer.md#isreversed)
- [JumpToFrame](ue_ue.LevelSequencePlayer.md#jumptoframe)
- [JumpToMarkedFrame](ue_ue.LevelSequencePlayer.md#jumptomarkedframe)
- [JumpToPosition](ue_ue.LevelSequencePlayer.md#jumptoposition)
- [JumpToSeconds](ue_ue.LevelSequencePlayer.md#jumptoseconds)
- [Pause](ue_ue.LevelSequencePlayer.md#pause)
- [Play](ue_ue.LevelSequencePlayer.md#play)
- [PlayLooping](ue_ue.LevelSequencePlayer.md#playlooping)
- [PlayReverse](ue_ue.LevelSequencePlayer.md#playreverse)
- [PlayToFrame](ue_ue.LevelSequencePlayer.md#playtoframe)
- [PlayToMarkedFrame](ue_ue.LevelSequencePlayer.md#playtomarkedframe)
- [PlayToSeconds](ue_ue.LevelSequencePlayer.md#playtoseconds)
- [RPC\_ExplicitServerUpdateEvent](ue_ue.LevelSequencePlayer.md#rpc_explicitserverupdateevent)
- [RPC\_OnStopEvent](ue_ue.LevelSequencePlayer.md#rpc_onstopevent)
- [Scrub](ue_ue.LevelSequencePlayer.md#scrub)
- [ScrubToFrame](ue_ue.LevelSequencePlayer.md#scrubtoframe)
- [ScrubToMarkedFrame](ue_ue.LevelSequencePlayer.md#scrubtomarkedframe)
- [ScrubToSeconds](ue_ue.LevelSequencePlayer.md#scrubtoseconds)
- [SetDisableCameraCuts](ue_ue.LevelSequencePlayer.md#setdisablecameracuts)
- [SetFrameRange](ue_ue.LevelSequencePlayer.md#setframerange)
- [SetFrameRate](ue_ue.LevelSequencePlayer.md#setframerate)
- [SetPlayRate](ue_ue.LevelSequencePlayer.md#setplayrate)
- [SetPlaybackPosition](ue_ue.LevelSequencePlayer.md#setplaybackposition)
- [SetPlaybackRange](ue_ue.LevelSequencePlayer.md#setplaybackrange)
- [SetTimeRange](ue_ue.LevelSequencePlayer.md#settimerange)
- [Stop](ue_ue.LevelSequencePlayer.md#stop)
- [StopAtCurrentTime](ue_ue.LevelSequencePlayer.md#stopatcurrenttime)
- [CreateLevelSequencePlayer](ue_ue.LevelSequencePlayer.md#createlevelsequenceplayer)
- [Find](ue_ue.LevelSequencePlayer.md#find)
- [Load](ue_ue.LevelSequencePlayer.md#load)
- [StaticClass](ue_ue.LevelSequencePlayer.md#staticclass)

## Constructors

### constructor

• **new LevelSequencePlayer**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[constructor](ue_ue.MovieSceneSequencePlayer.md#constructor)

#### Defined in

[ue/ue.d.ts:22656](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22656)

## Properties

### CurrentNumLoops

• **CurrentNumLoops**: `number`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[CurrentNumLoops](ue_ue.MovieSceneSequencePlayer.md#currentnumloops)

#### Defined in

[ue/ue.d.ts:14231](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14231)

___

### DurationFrames

• **DurationFrames**: `number`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[DurationFrames](ue_ue.MovieSceneSequencePlayer.md#durationframes)

#### Defined in

[ue/ue.d.ts:14230](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14230)

___

### NetSyncProps

• **NetSyncProps**: [`MovieSceneSequenceReplProperties`](ue_ue.MovieSceneSequenceReplProperties.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[NetSyncProps](ue_ue.MovieSceneSequencePlayer.md#netsyncprops)

#### Defined in

[ue/ue.d.ts:14234](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14234)

___

### OnCameraCut

• **OnCameraCut**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`CameraComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`CameraComponent`](ue_ue.CameraComponent.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:22657](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22657)

___

### OnFinished

• **OnFinished**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[OnFinished](ue_ue.MovieSceneSequencePlayer.md#onfinished)

#### Defined in

[ue/ue.d.ts:14225](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14225)

___

### OnPause

• **OnPause**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[OnPause](ue_ue.MovieSceneSequencePlayer.md#onpause)

#### Defined in

[ue/ue.d.ts:14224](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14224)

___

### OnPlay

• **OnPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[OnPlay](ue_ue.MovieSceneSequencePlayer.md#onplay)

#### Defined in

[ue/ue.d.ts:14221](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14221)

___

### OnPlayReverse

• **OnPlayReverse**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[OnPlayReverse](ue_ue.MovieSceneSequencePlayer.md#onplayreverse)

#### Defined in

[ue/ue.d.ts:14222](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14222)

___

### OnStop

• **OnStop**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[OnStop](ue_ue.MovieSceneSequencePlayer.md#onstop)

#### Defined in

[ue/ue.d.ts:14223](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14223)

___

### PlaybackClient

• **PlaybackClient**: [`MovieScenePlaybackClient`](ue_ue.MovieScenePlaybackClient.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[PlaybackClient](ue_ue.MovieSceneSequencePlayer.md#playbackclient)

#### Defined in

[ue/ue.d.ts:14235](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14235)

___

### PlaybackSettings

• **PlaybackSettings**: [`MovieSceneSequencePlaybackSettings`](ue_ue.MovieSceneSequencePlaybackSettings.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[PlaybackSettings](ue_ue.MovieSceneSequencePlayer.md#playbacksettings)

#### Defined in

[ue/ue.d.ts:14232](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14232)

___

### RootTemplateInstance

• **RootTemplateInstance**: [`MovieSceneRootEvaluationTemplateInstance`](ue_ue.MovieSceneRootEvaluationTemplateInstance.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[RootTemplateInstance](ue_ue.MovieSceneSequencePlayer.md#roottemplateinstance)

#### Defined in

[ue/ue.d.ts:14233](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14233)

___

### Sequence

• **Sequence**: [`MovieSceneSequence`](ue_ue.MovieSceneSequence.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[Sequence](ue_ue.MovieSceneSequencePlayer.md#sequence)

#### Defined in

[ue/ue.d.ts:14228](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14228)

___

### StartTime

• **StartTime**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[StartTime](ue_ue.MovieSceneSequencePlayer.md#starttime)

#### Defined in

[ue/ue.d.ts:14229](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14229)

___

### Status

• **Status**: [`EMovieScenePlayerStatus`](../enums/ue_ue.EMovieScenePlayerStatus.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[Status](ue_ue.MovieSceneSequencePlayer.md#status)

#### Defined in

[ue/ue.d.ts:14226](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14226)

___

### \_\_tid\_LevelSequencePlayer\_\_

• **\_\_tid\_LevelSequencePlayer\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:22664](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22664)

___

### \_\_tid\_MovieSceneSequencePlayer\_\_

• **\_\_tid\_MovieSceneSequencePlayer\_\_**: `boolean`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[__tid_MovieSceneSequencePlayer__](ue_ue.MovieSceneSequencePlayer.md#__tid_moviescenesequenceplayer__)

#### Defined in

[ue/ue.d.ts:14285](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14285)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[__tid_Object__](ue_ue.MovieSceneSequencePlayer.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bReversePlayback

• **bReversePlayback**: `boolean`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[bReversePlayback](ue_ue.MovieSceneSequencePlayer.md#breverseplayback)

#### Defined in

[ue/ue.d.ts:14227](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14227)

## Methods

### ChangePlaybackDirection

▸ **ChangePlaybackDirection**(): `void`

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[ChangePlaybackDirection](ue_ue.MovieSceneSequencePlayer.md#changeplaybackdirection)

#### Defined in

[ue/ue.d.ts:14236](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14236)

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

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[CreateDefaultSubobject](ue_ue.MovieSceneSequencePlayer.md#createdefaultsubobject)

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

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[ExecuteUbergraph](ue_ue.MovieSceneSequencePlayer.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetActiveCameraComponent

▸ **GetActiveCameraComponent**(): [`CameraComponent`](ue_ue.CameraComponent.md)

#### Returns

[`CameraComponent`](ue_ue.CameraComponent.md)

#### Defined in

[ue/ue.d.ts:22658](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22658)

___

### GetBoundObjects

▸ **GetBoundObjects**(`ObjectBinding`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ObjectBinding` | [`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md) |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetBoundObjects](ue_ue.MovieSceneSequencePlayer.md#getboundobjects)

#### Defined in

[ue/ue.d.ts:14237](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14237)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetClass](ue_ue.MovieSceneSequencePlayer.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetCurrentTime

▸ **GetCurrentTime**(): [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Returns

[`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetCurrentTime](ue_ue.MovieSceneSequencePlayer.md#getcurrenttime)

#### Defined in

[ue/ue.d.ts:14238](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14238)

___

### GetDisableCameraCuts

▸ **GetDisableCameraCuts**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetDisableCameraCuts](ue_ue.MovieSceneSequencePlayer.md#getdisablecameracuts)

#### Defined in

[ue/ue.d.ts:14239](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14239)

___

### GetDuration

▸ **GetDuration**(): [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Returns

[`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetDuration](ue_ue.MovieSceneSequencePlayer.md#getduration)

#### Defined in

[ue/ue.d.ts:14240](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14240)

___

### GetEndTime

▸ **GetEndTime**(): [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Returns

[`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetEndTime](ue_ue.MovieSceneSequencePlayer.md#getendtime)

#### Defined in

[ue/ue.d.ts:14241](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14241)

___

### GetFrameDuration

▸ **GetFrameDuration**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetFrameDuration](ue_ue.MovieSceneSequencePlayer.md#getframeduration)

#### Defined in

[ue/ue.d.ts:14242](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14242)

___

### GetFrameRate

▸ **GetFrameRate**(): [`FrameRate`](ue_ue.FrameRate.md)

#### Returns

[`FrameRate`](ue_ue.FrameRate.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetFrameRate](ue_ue.MovieSceneSequencePlayer.md#getframerate)

#### Defined in

[ue/ue.d.ts:14243](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14243)

___

### GetLength

▸ **GetLength**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetLength](ue_ue.MovieSceneSequencePlayer.md#getlength)

#### Defined in

[ue/ue.d.ts:14244](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14244)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetName](ue_ue.MovieSceneSequencePlayer.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetObjectBindings

▸ **GetObjectBindings**(`InObject`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `InObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)\>

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetObjectBindings](ue_ue.MovieSceneSequencePlayer.md#getobjectbindings)

#### Defined in

[ue/ue.d.ts:14245](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14245)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetOuter](ue_ue.MovieSceneSequencePlayer.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetPlayRate

▸ **GetPlayRate**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetPlayRate](ue_ue.MovieSceneSequencePlayer.md#getplayrate)

#### Defined in

[ue/ue.d.ts:14249](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14249)

___

### GetPlaybackEnd

▸ **GetPlaybackEnd**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetPlaybackEnd](ue_ue.MovieSceneSequencePlayer.md#getplaybackend)

#### Defined in

[ue/ue.d.ts:14246](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14246)

___

### GetPlaybackPosition

▸ **GetPlaybackPosition**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetPlaybackPosition](ue_ue.MovieSceneSequencePlayer.md#getplaybackposition)

#### Defined in

[ue/ue.d.ts:14247](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14247)

___

### GetPlaybackStart

▸ **GetPlaybackStart**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetPlaybackStart](ue_ue.MovieSceneSequencePlayer.md#getplaybackstart)

#### Defined in

[ue/ue.d.ts:14248](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14248)

___

### GetStartTime

▸ **GetStartTime**(): [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Returns

[`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetStartTime](ue_ue.MovieSceneSequencePlayer.md#getstarttime)

#### Defined in

[ue/ue.d.ts:14250](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14250)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetWorld](ue_ue.MovieSceneSequencePlayer.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### GoToEndAndStop

▸ **GoToEndAndStop**(): `void`

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GoToEndAndStop](ue_ue.MovieSceneSequencePlayer.md#gotoendandstop)

#### Defined in

[ue/ue.d.ts:14251](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14251)

___

### IsPaused

▸ **IsPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[IsPaused](ue_ue.MovieSceneSequencePlayer.md#ispaused)

#### Defined in

[ue/ue.d.ts:14252](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14252)

___

### IsPlaying

▸ **IsPlaying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[IsPlaying](ue_ue.MovieSceneSequencePlayer.md#isplaying)

#### Defined in

[ue/ue.d.ts:14253](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14253)

___

### IsReversed

▸ **IsReversed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[IsReversed](ue_ue.MovieSceneSequencePlayer.md#isreversed)

#### Defined in

[ue/ue.d.ts:14254](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14254)

___

### JumpToFrame

▸ **JumpToFrame**(`NewPosition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPosition` | [`FrameTime`](ue_ue.FrameTime.md) |

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[JumpToFrame](ue_ue.MovieSceneSequencePlayer.md#jumptoframe)

#### Defined in

[ue/ue.d.ts:14255](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14255)

___

### JumpToMarkedFrame

▸ **JumpToMarkedFrame**(`InLabel`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLabel` | `string` |

#### Returns

`boolean`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[JumpToMarkedFrame](ue_ue.MovieSceneSequencePlayer.md#jumptomarkedframe)

#### Defined in

[ue/ue.d.ts:14256](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14256)

___

### JumpToPosition

▸ **JumpToPosition**(`NewPlaybackPosition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlaybackPosition` | `number` |

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[JumpToPosition](ue_ue.MovieSceneSequencePlayer.md#jumptoposition)

#### Defined in

[ue/ue.d.ts:14257](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14257)

___

### JumpToSeconds

▸ **JumpToSeconds**(`TimeInSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeInSeconds` | `number` |

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[JumpToSeconds](ue_ue.MovieSceneSequencePlayer.md#jumptoseconds)

#### Defined in

[ue/ue.d.ts:14258](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14258)

___

### Pause

▸ **Pause**(): `void`

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[Pause](ue_ue.MovieSceneSequencePlayer.md#pause)

#### Defined in

[ue/ue.d.ts:14259](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14259)

___

### Play

▸ **Play**(): `void`

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[Play](ue_ue.MovieSceneSequencePlayer.md#play)

#### Defined in

[ue/ue.d.ts:14260](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14260)

___

### PlayLooping

▸ **PlayLooping**(`NumLoops?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumLoops?` | `number` |

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[PlayLooping](ue_ue.MovieSceneSequencePlayer.md#playlooping)

#### Defined in

[ue/ue.d.ts:14261](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14261)

___

### PlayReverse

▸ **PlayReverse**(): `void`

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[PlayReverse](ue_ue.MovieSceneSequencePlayer.md#playreverse)

#### Defined in

[ue/ue.d.ts:14262](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14262)

___

### PlayToFrame

▸ **PlayToFrame**(`NewPosition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPosition` | [`FrameTime`](ue_ue.FrameTime.md) |

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[PlayToFrame](ue_ue.MovieSceneSequencePlayer.md#playtoframe)

#### Defined in

[ue/ue.d.ts:14263](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14263)

___

### PlayToMarkedFrame

▸ **PlayToMarkedFrame**(`InLabel`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLabel` | `string` |

#### Returns

`boolean`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[PlayToMarkedFrame](ue_ue.MovieSceneSequencePlayer.md#playtomarkedframe)

#### Defined in

[ue/ue.d.ts:14264](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14264)

___

### PlayToSeconds

▸ **PlayToSeconds**(`TimeInSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeInSeconds` | `number` |

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[PlayToSeconds](ue_ue.MovieSceneSequencePlayer.md#playtoseconds)

#### Defined in

[ue/ue.d.ts:14265](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14265)

___

### RPC\_ExplicitServerUpdateEvent

▸ **RPC_ExplicitServerUpdateEvent**(`Method`, `RelevantTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Method` | [`EUpdatePositionMethod`](../enums/ue_ue.EUpdatePositionMethod.md) |
| `RelevantTime` | [`FrameTime`](ue_ue.FrameTime.md) |

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[RPC_ExplicitServerUpdateEvent](ue_ue.MovieSceneSequencePlayer.md#rpc_explicitserverupdateevent)

#### Defined in

[ue/ue.d.ts:14266](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14266)

___

### RPC\_OnStopEvent

▸ **RPC_OnStopEvent**(`StoppedTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StoppedTime` | [`FrameTime`](ue_ue.FrameTime.md) |

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[RPC_OnStopEvent](ue_ue.MovieSceneSequencePlayer.md#rpc_onstopevent)

#### Defined in

[ue/ue.d.ts:14267](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14267)

___

### Scrub

▸ **Scrub**(): `void`

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[Scrub](ue_ue.MovieSceneSequencePlayer.md#scrub)

#### Defined in

[ue/ue.d.ts:14268](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14268)

___

### ScrubToFrame

▸ **ScrubToFrame**(`NewPosition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPosition` | [`FrameTime`](ue_ue.FrameTime.md) |

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[ScrubToFrame](ue_ue.MovieSceneSequencePlayer.md#scrubtoframe)

#### Defined in

[ue/ue.d.ts:14269](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14269)

___

### ScrubToMarkedFrame

▸ **ScrubToMarkedFrame**(`InLabel`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLabel` | `string` |

#### Returns

`boolean`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[ScrubToMarkedFrame](ue_ue.MovieSceneSequencePlayer.md#scrubtomarkedframe)

#### Defined in

[ue/ue.d.ts:14270](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14270)

___

### ScrubToSeconds

▸ **ScrubToSeconds**(`TimeInSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeInSeconds` | `number` |

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[ScrubToSeconds](ue_ue.MovieSceneSequencePlayer.md#scrubtoseconds)

#### Defined in

[ue/ue.d.ts:14271](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14271)

___

### SetDisableCameraCuts

▸ **SetDisableCameraCuts**(`bInDisableCameraCuts`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInDisableCameraCuts` | `boolean` |

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[SetDisableCameraCuts](ue_ue.MovieSceneSequencePlayer.md#setdisablecameracuts)

#### Defined in

[ue/ue.d.ts:14272](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14272)

___

### SetFrameRange

▸ **SetFrameRange**(`StartFrame`, `Duration`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StartFrame` | `number` |
| `Duration` | `number` |

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[SetFrameRange](ue_ue.MovieSceneSequencePlayer.md#setframerange)

#### Defined in

[ue/ue.d.ts:14273](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14273)

___

### SetFrameRate

▸ **SetFrameRate**(`FrameRate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FrameRate` | [`FrameRate`](ue_ue.FrameRate.md) |

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[SetFrameRate](ue_ue.MovieSceneSequencePlayer.md#setframerate)

#### Defined in

[ue/ue.d.ts:14274](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14274)

___

### SetPlayRate

▸ **SetPlayRate**(`PlayRate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayRate` | `number` |

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[SetPlayRate](ue_ue.MovieSceneSequencePlayer.md#setplayrate)

#### Defined in

[ue/ue.d.ts:14277](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14277)

___

### SetPlaybackPosition

▸ **SetPlaybackPosition**(`NewPlaybackPosition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlaybackPosition` | `number` |

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[SetPlaybackPosition](ue_ue.MovieSceneSequencePlayer.md#setplaybackposition)

#### Defined in

[ue/ue.d.ts:14275](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14275)

___

### SetPlaybackRange

▸ **SetPlaybackRange**(`NewStartTime`, `NewEndTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewStartTime` | `number` |
| `NewEndTime` | `number` |

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[SetPlaybackRange](ue_ue.MovieSceneSequencePlayer.md#setplaybackrange)

#### Defined in

[ue/ue.d.ts:14276](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14276)

___

### SetTimeRange

▸ **SetTimeRange**(`StartTime`, `Duration`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StartTime` | `number` |
| `Duration` | `number` |

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[SetTimeRange](ue_ue.MovieSceneSequencePlayer.md#settimerange)

#### Defined in

[ue/ue.d.ts:14278](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14278)

___

### Stop

▸ **Stop**(): `void`

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[Stop](ue_ue.MovieSceneSequencePlayer.md#stop)

#### Defined in

[ue/ue.d.ts:14279](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14279)

___

### StopAtCurrentTime

▸ **StopAtCurrentTime**(): `void`

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[StopAtCurrentTime](ue_ue.MovieSceneSequencePlayer.md#stopatcurrenttime)

#### Defined in

[ue/ue.d.ts:14280](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14280)

___

### CreateLevelSequencePlayer

▸ `Static` **CreateLevelSequencePlayer**(`WorldContextObject`, `LevelSequence`, `Settings`, `OutActor`): [`LevelSequencePlayer`](ue_ue.LevelSequencePlayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `LevelSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`LevelSequence`](ue_ue.LevelSequence.md)\> |
| `Settings` | [`MovieSceneSequencePlaybackSettings`](ue_ue.MovieSceneSequencePlaybackSettings.md) |
| `OutActor` | [`$Ref`](../interfaces/puerts._Ref.md)<[`LevelSequenceActor`](ue_ue.LevelSequenceActor.md)\> |

#### Returns

[`LevelSequencePlayer`](ue_ue.LevelSequencePlayer.md)

#### Defined in

[ue/ue.d.ts:22659](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22659)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LevelSequencePlayer`](ue_ue.LevelSequencePlayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LevelSequencePlayer`](ue_ue.LevelSequencePlayer.md)

#### Overrides

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[Find](ue_ue.MovieSceneSequencePlayer.md#find)

#### Defined in

[ue/ue.d.ts:22661](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22661)

___

### Load

▸ `Static` **Load**(`InName`): [`LevelSequencePlayer`](ue_ue.LevelSequencePlayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LevelSequencePlayer`](ue_ue.LevelSequencePlayer.md)

#### Overrides

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[Load](ue_ue.MovieSceneSequencePlayer.md#load)

#### Defined in

[ue/ue.d.ts:22662](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22662)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[StaticClass](ue_ue.MovieSceneSequencePlayer.md#staticclass)

#### Defined in

[ue/ue.d.ts:22660](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22660)
