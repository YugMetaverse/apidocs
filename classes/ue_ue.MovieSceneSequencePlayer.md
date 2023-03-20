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

#### Defined in

[ue/ue.d.ts:14220](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14220)

## Properties

### CurrentNumLoops

• **CurrentNumLoops**: `number`

#### Defined in

[ue/ue.d.ts:14231](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14231)

___

### DurationFrames

• **DurationFrames**: `number`

#### Defined in

[ue/ue.d.ts:14230](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14230)

___

### NetSyncProps

• **NetSyncProps**: [`MovieSceneSequenceReplProperties`](ue_ue.MovieSceneSequenceReplProperties.md)

#### Defined in

[ue/ue.d.ts:14234](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14234)

___

### OnFinished

• **OnFinished**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:14225](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14225)

___

### OnPause

• **OnPause**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:14224](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14224)

___

### OnPlay

• **OnPlay**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:14221](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14221)

___

### OnPlayReverse

• **OnPlayReverse**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:14222](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14222)

___

### OnStop

• **OnStop**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:14223](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14223)

___

### PlaybackClient

• **PlaybackClient**: [`MovieScenePlaybackClient`](ue_ue.MovieScenePlaybackClient.md)

#### Defined in

[ue/ue.d.ts:14235](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14235)

___

### PlaybackSettings

• **PlaybackSettings**: [`MovieSceneSequencePlaybackSettings`](ue_ue.MovieSceneSequencePlaybackSettings.md)

#### Defined in

[ue/ue.d.ts:14232](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14232)

___

### RootTemplateInstance

• **RootTemplateInstance**: [`MovieSceneRootEvaluationTemplateInstance`](ue_ue.MovieSceneRootEvaluationTemplateInstance.md)

#### Defined in

[ue/ue.d.ts:14233](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14233)

___

### Sequence

• **Sequence**: [`MovieSceneSequence`](ue_ue.MovieSceneSequence.md)

#### Defined in

[ue/ue.d.ts:14228](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14228)

___

### StartTime

• **StartTime**: [`FrameNumber`](ue_ue.FrameNumber.md)

#### Defined in

[ue/ue.d.ts:14229](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14229)

___

### Status

• **Status**: [`EMovieScenePlayerStatus`](../enums/ue_ue.EMovieScenePlayerStatus.md)

#### Defined in

[ue/ue.d.ts:14226](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14226)

___

### \_\_tid\_MovieSceneSequencePlayer\_\_

• **\_\_tid\_MovieSceneSequencePlayer\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14285](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14285)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bReversePlayback

• **bReversePlayback**: `boolean`

#### Defined in

[ue/ue.d.ts:14227](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14227)

## Methods

### ChangePlaybackDirection

▸ **ChangePlaybackDirection**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14236](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14236)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetBoundObjects

▸ **GetBoundObjects**(`ObjectBinding`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ObjectBinding` | [`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md) |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:14237](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14237)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetCurrentTime

▸ **GetCurrentTime**(): [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Returns

[`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Defined in

[ue/ue.d.ts:14238](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14238)

___

### GetDisableCameraCuts

▸ **GetDisableCameraCuts**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:14239](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14239)

___

### GetDuration

▸ **GetDuration**(): [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Returns

[`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Defined in

[ue/ue.d.ts:14240](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14240)

___

### GetEndTime

▸ **GetEndTime**(): [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Returns

[`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Defined in

[ue/ue.d.ts:14241](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14241)

___

### GetFrameDuration

▸ **GetFrameDuration**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:14242](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14242)

___

### GetFrameRate

▸ **GetFrameRate**(): [`FrameRate`](ue_ue.FrameRate.md)

#### Returns

[`FrameRate`](ue_ue.FrameRate.md)

#### Defined in

[ue/ue.d.ts:14243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14243)

___

### GetLength

▸ **GetLength**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:14244](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14244)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetObjectBindings

▸ **GetObjectBindings**(`InObject`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `InObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)\>

#### Defined in

[ue/ue.d.ts:14245](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14245)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetPlayRate

▸ **GetPlayRate**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:14249](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14249)

___

### GetPlaybackEnd

▸ **GetPlaybackEnd**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:14246](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14246)

___

### GetPlaybackPosition

▸ **GetPlaybackPosition**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:14247](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14247)

___

### GetPlaybackStart

▸ **GetPlaybackStart**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:14248](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14248)

___

### GetStartTime

▸ **GetStartTime**(): [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Returns

[`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md)

#### Defined in

[ue/ue.d.ts:14250](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14250)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### GoToEndAndStop

▸ **GoToEndAndStop**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14251](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14251)

___

### IsPaused

▸ **IsPaused**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:14252](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14252)

___

### IsPlaying

▸ **IsPlaying**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:14253](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14253)

___

### IsReversed

▸ **IsReversed**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:14254](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14254)

___

### JumpToFrame

▸ **JumpToFrame**(`NewPosition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPosition` | [`FrameTime`](ue_ue.FrameTime.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14255](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14255)

___

### JumpToMarkedFrame

▸ **JumpToMarkedFrame**(`InLabel`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLabel` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:14256](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14256)

___

### JumpToPosition

▸ **JumpToPosition**(`NewPlaybackPosition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlaybackPosition` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14257](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14257)

___

### JumpToSeconds

▸ **JumpToSeconds**(`TimeInSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeInSeconds` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14258](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14258)

___

### Pause

▸ **Pause**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14259](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14259)

___

### Play

▸ **Play**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14260](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14260)

___

### PlayLooping

▸ **PlayLooping**(`NumLoops?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumLoops?` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14261](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14261)

___

### PlayReverse

▸ **PlayReverse**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14262](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14262)

___

### PlayToFrame

▸ **PlayToFrame**(`NewPosition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPosition` | [`FrameTime`](ue_ue.FrameTime.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14263](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14263)

___

### PlayToMarkedFrame

▸ **PlayToMarkedFrame**(`InLabel`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLabel` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:14264](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14264)

___

### PlayToSeconds

▸ **PlayToSeconds**(`TimeInSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeInSeconds` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14265](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14265)

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

#### Defined in

[ue/ue.d.ts:14266](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14266)

___

### RPC\_OnStopEvent

▸ **RPC_OnStopEvent**(`StoppedTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StoppedTime` | [`FrameTime`](ue_ue.FrameTime.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14267](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14267)

___

### Scrub

▸ **Scrub**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14268](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14268)

___

### ScrubToFrame

▸ **ScrubToFrame**(`NewPosition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPosition` | [`FrameTime`](ue_ue.FrameTime.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14269](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14269)

___

### ScrubToMarkedFrame

▸ **ScrubToMarkedFrame**(`InLabel`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLabel` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:14270](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14270)

___

### ScrubToSeconds

▸ **ScrubToSeconds**(`TimeInSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeInSeconds` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14271](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14271)

___

### SetDisableCameraCuts

▸ **SetDisableCameraCuts**(`bInDisableCameraCuts`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInDisableCameraCuts` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14272](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14272)

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

#### Defined in

[ue/ue.d.ts:14273](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14273)

___

### SetFrameRate

▸ **SetFrameRate**(`FrameRate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FrameRate` | [`FrameRate`](ue_ue.FrameRate.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14274](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14274)

___

### SetPlayRate

▸ **SetPlayRate**(`PlayRate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayRate` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14277](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14277)

___

### SetPlaybackPosition

▸ **SetPlaybackPosition**(`NewPlaybackPosition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPlaybackPosition` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14275](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14275)

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

#### Defined in

[ue/ue.d.ts:14276](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14276)

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

#### Defined in

[ue/ue.d.ts:14278](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14278)

___

### Stop

▸ **Stop**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14279](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14279)

___

### StopAtCurrentTime

▸ **StopAtCurrentTime**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14280](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14280)

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

#### Defined in

[ue/ue.d.ts:14282](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14282)

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

#### Defined in

[ue/ue.d.ts:14283](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14283)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:14281](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14281)
