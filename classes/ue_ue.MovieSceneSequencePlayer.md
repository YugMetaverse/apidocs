[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneSequencePlayer

# Class: MovieSceneSequencePlayer

[ue/ue](../modules/ue_ue.md).MovieSceneSequencePlayer

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MovieSceneSequencePlayer`**

  ↳↳ [`ActorSequencePlayer`](ue_ue.ActorSequencePlayer.md)

  ↳↳ [`LevelSequencePlayer`](ue_ue.LevelSequencePlayer.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneSequencePlayer.md#constructor)

### Properties

- [CurrentNumLoops](ue_ue.MovieSceneSequencePlayer.md#currentnumloops)
- [DurationFrames](ue_ue.MovieSceneSequencePlayer.md#durationframes)
- [NetSyncProps](ue_ue.MovieSceneSequencePlayer.md#netsyncprops)
- [OnFinished](ue_ue.MovieSceneSequencePlayer.md#onfinished)
- [OnPause](ue_ue.MovieSceneSequencePlayer.md#onpause)
- [OnPlay](ue_ue.MovieSceneSequencePlayer.md#onplay)
- [OnPlayReverse](ue_ue.MovieSceneSequencePlayer.md#onplayreverse)
- [OnStop](ue_ue.MovieSceneSequencePlayer.md#onstop)
- [PlaybackClient](ue_ue.MovieSceneSequencePlayer.md#playbackclient)
- [PlaybackSettings](ue_ue.MovieSceneSequencePlayer.md#playbacksettings)
- [RootTemplateInstance](ue_ue.MovieSceneSequencePlayer.md#roottemplateinstance)
- [Sequence](ue_ue.MovieSceneSequencePlayer.md#sequence)
- [StartTime](ue_ue.MovieSceneSequencePlayer.md#starttime)
- [Status](ue_ue.MovieSceneSequencePlayer.md#status)
- [\_\_tid\_MovieSceneSequencePlayer\_\_](ue_ue.MovieSceneSequencePlayer.md#__tid_moviescenesequenceplayer__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneSequencePlayer.md#__tid_object__)
- [bReversePlayback](ue_ue.MovieSceneSequencePlayer.md#breverseplayback)

### Methods

- [ChangePlaybackDirection](ue_ue.MovieSceneSequencePlayer.md#changeplaybackdirection)
- [CreateDefaultSubobject](ue_ue.MovieSceneSequencePlayer.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneSequencePlayer.md#executeubergraph)
- [GetBoundObjects](ue_ue.MovieSceneSequencePlayer.md#getboundobjects)
- [GetClass](ue_ue.MovieSceneSequencePlayer.md#getclass)
- [GetCurrentTime](ue_ue.MovieSceneSequencePlayer.md#getcurrenttime)
- [GetDisableCameraCuts](ue_ue.MovieSceneSequencePlayer.md#getdisablecameracuts)
- [GetDuration](ue_ue.MovieSceneSequencePlayer.md#getduration)
- [GetEndTime](ue_ue.MovieSceneSequencePlayer.md#getendtime)
- [GetFrameDuration](ue_ue.MovieSceneSequencePlayer.md#getframeduration)
- [GetFrameRate](ue_ue.MovieSceneSequencePlayer.md#getframerate)
- [GetLength](ue_ue.MovieSceneSequencePlayer.md#getlength)
- [GetName](ue_ue.MovieSceneSequencePlayer.md#getname)
- [GetObjectBindings](ue_ue.MovieSceneSequencePlayer.md#getobjectbindings)
- [GetOuter](ue_ue.MovieSceneSequencePlayer.md#getouter)
- [GetPlayRate](ue_ue.MovieSceneSequencePlayer.md#getplayrate)
- [GetPlaybackEnd](ue_ue.MovieSceneSequencePlayer.md#getplaybackend)
- [GetPlaybackPosition](ue_ue.MovieSceneSequencePlayer.md#getplaybackposition)
- [GetPlaybackStart](ue_ue.MovieSceneSequencePlayer.md#getplaybackstart)
- [GetStartTime](ue_ue.MovieSceneSequencePlayer.md#getstarttime)
- [GetWorld](ue_ue.MovieSceneSequencePlayer.md#getworld)
- [GoToEndAndStop](ue_ue.MovieSceneSequencePlayer.md#gotoendandstop)
- [IsPaused](ue_ue.MovieSceneSequencePlayer.md#ispaused)
- [IsPlaying](ue_ue.MovieSceneSequencePlayer.md#isplaying)
- [IsReversed](ue_ue.MovieSceneSequencePlayer.md#isreversed)
- [JumpToFrame](ue_ue.MovieSceneSequencePlayer.md#jumptoframe)
- [JumpToMarkedFrame](ue_ue.MovieSceneSequencePlayer.md#jumptomarkedframe)
- [JumpToPosition](ue_ue.MovieSceneSequencePlayer.md#jumptoposition)
- [JumpToSeconds](ue_ue.MovieSceneSequencePlayer.md#jumptoseconds)
- [Pause](ue_ue.MovieSceneSequencePlayer.md#pause)
- [Play](ue_ue.MovieSceneSequencePlayer.md#play)
- [PlayLooping](ue_ue.MovieSceneSequencePlayer.md#playlooping)
- [PlayReverse](ue_ue.MovieSceneSequencePlayer.md#playreverse)
- [PlayToFrame](ue_ue.MovieSceneSequencePlayer.md#playtoframe)
- [PlayToMarkedFrame](ue_ue.MovieSceneSequencePlayer.md#playtomarkedframe)
- [PlayToSeconds](ue_ue.MovieSceneSequencePlayer.md#playtoseconds)
- [RPC\_ExplicitServerUpdateEvent](ue_ue.MovieSceneSequencePlayer.md#rpc_explicitserverupdateevent)
- [RPC\_OnStopEvent](ue_ue.MovieSceneSequencePlayer.md#rpc_onstopevent)
- [Scrub](ue_ue.MovieSceneSequencePlayer.md#scrub)
- [ScrubToFrame](ue_ue.MovieSceneSequencePlayer.md#scrubtoframe)
- [ScrubToMarkedFrame](ue_ue.MovieSceneSequencePlayer.md#scrubtomarkedframe)
- [ScrubToSeconds](ue_ue.MovieSceneSequencePlayer.md#scrubtoseconds)
- [SetDisableCameraCuts](ue_ue.MovieSceneSequencePlayer.md#setdisablecameracuts)
- [SetFrameRange](ue_ue.MovieSceneSequencePlayer.md#setframerange)
- [SetFrameRate](ue_ue.MovieSceneSequencePlayer.md#setframerate)
- [SetPlayRate](ue_ue.MovieSceneSequencePlayer.md#setplayrate)
- [SetPlaybackPosition](ue_ue.MovieSceneSequencePlayer.md#setplaybackposition)
- [SetPlaybackRange](ue_ue.MovieSceneSequencePlayer.md#setplaybackrange)
- [SetTimeRange](ue_ue.MovieSceneSequencePlayer.md#settimerange)
- [Stop](ue_ue.MovieSceneSequencePlayer.md#stop)
- [StopAtCurrentTime](ue_ue.MovieSceneSequencePlayer.md#stopatcurrenttime)
- [Find](ue_ue.MovieSceneSequencePlayer.md#find)
- [Load](ue_ue.MovieSceneSequencePlayer.md#load)
- [StaticClass](ue_ue.MovieSceneSequencePlayer.md#staticclass)

## Constructors

### constructor

• **new MovieSceneSequencePlayer**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### CurrentNumLoops

• **CurrentNumLoops**: `number`

___

### DurationFrames

• **DurationFrames**: `number`

___

### NetSyncProps

• **NetSyncProps**: [`MovieSceneSequenceReplProperties`](ue_ue.MovieSceneSequenceReplProperties.md)

___

### OnFinished

• **OnFinished**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnPause

• **OnPause**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnPlay

• **OnPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnPlayReverse

• **OnPlayReverse**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnStop

• **OnStop**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### PlaybackClient

• **PlaybackClient**: [`MovieScenePlaybackClient`](ue_ue.MovieScenePlaybackClient.md)

___

### PlaybackSettings

• **PlaybackSettings**: [`MovieSceneSequencePlaybackSettings`](ue_ue.MovieSceneSequencePlaybackSettings.md)

___

### RootTemplateInstance

• **RootTemplateInstance**: [`MovieSceneRootEvaluationTemplateInstance`](ue_ue.MovieSceneRootEvaluationTemplateInstance.md)

___

### Sequence

• **Sequence**: [`MovieSceneSequence`](ue_ue.MovieSceneSequence.md)

___

### StartTime

• **StartTime**: [`FrameNumber`](ue_ue.FrameNumber.md)

___

### Status

• **Status**: [`EMovieScenePlayerStatus`](../enums/ue_ue.EMovieScenePlayerStatus.md)

___

### \_\_tid\_MovieSceneSequencePlayer\_\_

• **\_\_tid\_MovieSceneSequencePlayer\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bReversePlayback

• **bReversePlayback**: `boolean`

## Methods

### ChangePlaybackDirection

▸ **ChangePlaybackDirection**(): `void`

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

### GetBoundObjects

▸ **GetBoundObjects**(`ObjectBinding`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ObjectBinding` | [`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md) |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetCurrentTime

▸ **GetCurrentTime**(): [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Returns

[`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

___

### GetDisableCameraCuts

▸ **GetDisableCameraCuts**(): `boolean`

#### Returns

`boolean`

___

### GetDuration

▸ **GetDuration**(): [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Returns

[`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

___

### GetEndTime

▸ **GetEndTime**(): [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Returns

[`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

___

### GetFrameDuration

▸ **GetFrameDuration**(): `number`

#### Returns

`number`

___

### GetFrameRate

▸ **GetFrameRate**(): [`FrameRate`](ue_ue.FrameRate.md)

#### Returns

[`FrameRate`](ue_ue.FrameRate.md)

___

### GetLength

▸ **GetLength**(): `number`

#### Returns

`number`

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetObjectBindings

▸ **GetObjectBindings**(`InObject`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `InObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)\>

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetPlayRate

▸ **GetPlayRate**(): `number`

#### Returns

`number`

___

### GetPlaybackEnd

▸ **GetPlaybackEnd**(): `number`

#### Returns

`number`

___

### GetPlaybackPosition

▸ **GetPlaybackPosition**(): `number`

#### Returns

`number`

___

### GetPlaybackStart

▸ **GetPlaybackStart**(): `number`

#### Returns

`number`

___

### GetStartTime

▸ **GetStartTime**(): [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Returns

[`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### GoToEndAndStop

▸ **GoToEndAndStop**(): `void`

#### Returns

`void`

___

### IsPaused

▸ **IsPaused**(): `boolean`

#### Returns

`boolean`

___

### IsPlaying

▸ **IsPlaying**(): `boolean`

#### Returns

`boolean`

___

### IsReversed

▸ **IsReversed**(): `boolean`

#### Returns

`boolean`

___

### JumpToFrame

▸ **JumpToFrame**(`NewPosition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPosition` | [`FrameTime`](ue_ue.FrameTime.md) |

#### Returns

`void`

___

### JumpToMarkedFrame

▸ **JumpToMarkedFrame**(`InLabel`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLabel` | `string` |

#### Returns

`boolean`

___

### JumpToPosition

▸ **JumpToPosition**(`NewPlaybackPosition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlaybackPosition` | `number` |

#### Returns

`void`

___

### JumpToSeconds

▸ **JumpToSeconds**(`TimeInSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeInSeconds` | `number` |

#### Returns

`void`

___

### Pause

▸ **Pause**(): `void`

#### Returns

`void`

___

### Play

▸ **Play**(): `void`

#### Returns

`void`

___

### PlayLooping

▸ **PlayLooping**(`NumLoops?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumLoops?` | `number` |

#### Returns

`void`

___

### PlayReverse

▸ **PlayReverse**(): `void`

#### Returns

`void`

___

### PlayToFrame

▸ **PlayToFrame**(`NewPosition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPosition` | [`FrameTime`](ue_ue.FrameTime.md) |

#### Returns

`void`

___

### PlayToMarkedFrame

▸ **PlayToMarkedFrame**(`InLabel`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLabel` | `string` |

#### Returns

`boolean`

___

### PlayToSeconds

▸ **PlayToSeconds**(`TimeInSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeInSeconds` | `number` |

#### Returns

`void`

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

___

### RPC\_OnStopEvent

▸ **RPC_OnStopEvent**(`StoppedTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StoppedTime` | [`FrameTime`](ue_ue.FrameTime.md) |

#### Returns

`void`

___

### Scrub

▸ **Scrub**(): `void`

#### Returns

`void`

___

### ScrubToFrame

▸ **ScrubToFrame**(`NewPosition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPosition` | [`FrameTime`](ue_ue.FrameTime.md) |

#### Returns

`void`

___

### ScrubToMarkedFrame

▸ **ScrubToMarkedFrame**(`InLabel`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLabel` | `string` |

#### Returns

`boolean`

___

### ScrubToSeconds

▸ **ScrubToSeconds**(`TimeInSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeInSeconds` | `number` |

#### Returns

`void`

___

### SetDisableCameraCuts

▸ **SetDisableCameraCuts**(`bInDisableCameraCuts`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInDisableCameraCuts` | `boolean` |

#### Returns

`void`

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

___

### SetFrameRate

▸ **SetFrameRate**(`FrameRate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FrameRate` | [`FrameRate`](ue_ue.FrameRate.md) |

#### Returns

`void`

___

### SetPlayRate

▸ **SetPlayRate**(`PlayRate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayRate` | `number` |

#### Returns

`void`

___

### SetPlaybackPosition

▸ **SetPlaybackPosition**(`NewPlaybackPosition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlaybackPosition` | `number` |

#### Returns

`void`

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

___

### Stop

▸ **Stop**(): `void`

#### Returns

`void`

___

### StopAtCurrentTime

▸ **StopAtCurrentTime**(): `void`

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneSequencePlayer`](ue_ue.MovieSceneSequencePlayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneSequencePlayer`](ue_ue.MovieSceneSequencePlayer.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneSequencePlayer`](ue_ue.MovieSceneSequencePlayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneSequencePlayer`](ue_ue.MovieSceneSequencePlayer.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
