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

## Properties

### CurrentNumLoops

• **CurrentNumLoops**: `number`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[CurrentNumLoops](ue_ue.MovieSceneSequencePlayer.md#currentnumloops)

___

### DurationFrames

• **DurationFrames**: `number`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[DurationFrames](ue_ue.MovieSceneSequencePlayer.md#durationframes)

___

### NetSyncProps

• **NetSyncProps**: [`MovieSceneSequenceReplProperties`](ue_ue.MovieSceneSequenceReplProperties.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[NetSyncProps](ue_ue.MovieSceneSequencePlayer.md#netsyncprops)

___

### OnCameraCut

• **OnCameraCut**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`CameraComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`CameraComponent`](ue_ue.CameraComponent.md)\>) => `void`\>

___

### OnFinished

• **OnFinished**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[OnFinished](ue_ue.MovieSceneSequencePlayer.md#onfinished)

___

### OnPause

• **OnPause**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[OnPause](ue_ue.MovieSceneSequencePlayer.md#onpause)

___

### OnPlay

• **OnPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[OnPlay](ue_ue.MovieSceneSequencePlayer.md#onplay)

___

### OnPlayReverse

• **OnPlayReverse**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[OnPlayReverse](ue_ue.MovieSceneSequencePlayer.md#onplayreverse)

___

### OnStop

• **OnStop**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[OnStop](ue_ue.MovieSceneSequencePlayer.md#onstop)

___

### PlaybackClient

• **PlaybackClient**: [`MovieScenePlaybackClient`](ue_ue.MovieScenePlaybackClient.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[PlaybackClient](ue_ue.MovieSceneSequencePlayer.md#playbackclient)

___

### PlaybackSettings

• **PlaybackSettings**: [`MovieSceneSequencePlaybackSettings`](ue_ue.MovieSceneSequencePlaybackSettings.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[PlaybackSettings](ue_ue.MovieSceneSequencePlayer.md#playbacksettings)

___

### RootTemplateInstance

• **RootTemplateInstance**: [`MovieSceneRootEvaluationTemplateInstance`](ue_ue.MovieSceneRootEvaluationTemplateInstance.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[RootTemplateInstance](ue_ue.MovieSceneSequencePlayer.md#roottemplateinstance)

___

### Sequence

• **Sequence**: [`MovieSceneSequence`](ue_ue.MovieSceneSequence.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[Sequence](ue_ue.MovieSceneSequencePlayer.md#sequence)

___

### StartTime

• **StartTime**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[StartTime](ue_ue.MovieSceneSequencePlayer.md#starttime)

___

### Status

• **Status**: [`EMovieScenePlayerStatus`](../enums/ue_ue.EMovieScenePlayerStatus.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[Status](ue_ue.MovieSceneSequencePlayer.md#status)

___

### \_\_tid\_LevelSequencePlayer\_\_

• **\_\_tid\_LevelSequencePlayer\_\_**: `boolean`

___

### \_\_tid\_MovieSceneSequencePlayer\_\_

• **\_\_tid\_MovieSceneSequencePlayer\_\_**: `boolean`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[__tid_MovieSceneSequencePlayer__](ue_ue.MovieSceneSequencePlayer.md#__tid_moviescenesequenceplayer__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[__tid_Object__](ue_ue.MovieSceneSequencePlayer.md#__tid_object__)

___

### bReversePlayback

• **bReversePlayback**: `boolean`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[bReversePlayback](ue_ue.MovieSceneSequencePlayer.md#breverseplayback)

## Methods

### ChangePlaybackDirection

▸ **ChangePlaybackDirection**(): `void`

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[ChangePlaybackDirection](ue_ue.MovieSceneSequencePlayer.md#changeplaybackdirection)

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

___

### GetActiveCameraComponent

▸ **GetActiveCameraComponent**(): [`CameraComponent`](ue_ue.CameraComponent.md)

#### Returns

[`CameraComponent`](ue_ue.CameraComponent.md)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetClass](ue_ue.MovieSceneSequencePlayer.md#getclass)

___

### GetCurrentTime

▸ **GetCurrentTime**(): [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Returns

[`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetCurrentTime](ue_ue.MovieSceneSequencePlayer.md#getcurrenttime)

___

### GetDisableCameraCuts

▸ **GetDisableCameraCuts**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetDisableCameraCuts](ue_ue.MovieSceneSequencePlayer.md#getdisablecameracuts)

___

### GetDuration

▸ **GetDuration**(): [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Returns

[`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetDuration](ue_ue.MovieSceneSequencePlayer.md#getduration)

___

### GetEndTime

▸ **GetEndTime**(): [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Returns

[`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetEndTime](ue_ue.MovieSceneSequencePlayer.md#getendtime)

___

### GetFrameDuration

▸ **GetFrameDuration**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetFrameDuration](ue_ue.MovieSceneSequencePlayer.md#getframeduration)

___

### GetFrameRate

▸ **GetFrameRate**(): [`FrameRate`](ue_ue.FrameRate.md)

#### Returns

[`FrameRate`](ue_ue.FrameRate.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetFrameRate](ue_ue.MovieSceneSequencePlayer.md#getframerate)

___

### GetLength

▸ **GetLength**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetLength](ue_ue.MovieSceneSequencePlayer.md#getlength)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetName](ue_ue.MovieSceneSequencePlayer.md#getname)

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

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetOuter](ue_ue.MovieSceneSequencePlayer.md#getouter)

___

### GetPlayRate

▸ **GetPlayRate**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetPlayRate](ue_ue.MovieSceneSequencePlayer.md#getplayrate)

___

### GetPlaybackEnd

▸ **GetPlaybackEnd**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetPlaybackEnd](ue_ue.MovieSceneSequencePlayer.md#getplaybackend)

___

### GetPlaybackPosition

▸ **GetPlaybackPosition**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetPlaybackPosition](ue_ue.MovieSceneSequencePlayer.md#getplaybackposition)

___

### GetPlaybackStart

▸ **GetPlaybackStart**(): `number`

#### Returns

`number`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetPlaybackStart](ue_ue.MovieSceneSequencePlayer.md#getplaybackstart)

___

### GetStartTime

▸ **GetStartTime**(): [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Returns

[`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetStartTime](ue_ue.MovieSceneSequencePlayer.md#getstarttime)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GetWorld](ue_ue.MovieSceneSequencePlayer.md#getworld)

___

### GoToEndAndStop

▸ **GoToEndAndStop**(): `void`

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[GoToEndAndStop](ue_ue.MovieSceneSequencePlayer.md#gotoendandstop)

___

### IsPaused

▸ **IsPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[IsPaused](ue_ue.MovieSceneSequencePlayer.md#ispaused)

___

### IsPlaying

▸ **IsPlaying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[IsPlaying](ue_ue.MovieSceneSequencePlayer.md#isplaying)

___

### IsReversed

▸ **IsReversed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[IsReversed](ue_ue.MovieSceneSequencePlayer.md#isreversed)

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

___

### Pause

▸ **Pause**(): `void`

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[Pause](ue_ue.MovieSceneSequencePlayer.md#pause)

___

### Play

▸ **Play**(): `void`

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[Play](ue_ue.MovieSceneSequencePlayer.md#play)

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

___

### PlayReverse

▸ **PlayReverse**(): `void`

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[PlayReverse](ue_ue.MovieSceneSequencePlayer.md#playreverse)

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

___

### Scrub

▸ **Scrub**(): `void`

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[Scrub](ue_ue.MovieSceneSequencePlayer.md#scrub)

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

___

### Stop

▸ **Stop**(): `void`

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[Stop](ue_ue.MovieSceneSequencePlayer.md#stop)

___

### StopAtCurrentTime

▸ **StopAtCurrentTime**(): `void`

#### Returns

`void`

#### Inherited from

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[StopAtCurrentTime](ue_ue.MovieSceneSequencePlayer.md#stopatcurrenttime)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneSequencePlayer](ue_ue.MovieSceneSequencePlayer.md).[StaticClass](ue_ue.MovieSceneSequencePlayer.md#staticclass)
